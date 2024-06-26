# Analytics-in-Finance-Credit-card-approval-

Commercial banks receive a lot of applications for credit cards. Many of them get rejected for many reasons, like high loan balances, low income levels, or too many inquiries on an individual's credit report, for example. Manually analyzing these applications is mundane, error-prone, and time-consuming (and time is money!). Luckily, this task can be automated with the power of machine learning and pretty much every commercial bank does so nowadays. In this notebook, we will build an automatic credit card approval predictor using machine learning techniques, just like the real banks do.

# Motivation :-

Commercial banks receive a lot of applications for credit cards. Many of them get rejected for many reasons, like high loan balances, low income levels, or too many inquiries on an individual's credit report, for example. Manually analyzing these applications is mundane, error-prone, and time-consuming (and time is money!). This task can be automated with the power of machine learning and pretty much every commercial bank does so nowadays. In this notebook, we will build an automatic credit card approval predictor using machine learning techniques, just like the real banks do.

# Libraries Used:-

sklearn

pandas

numpy

seaborn

matplotlib

To install the above packages using pip, use command $pip install package-name

# Conclusion:-

The model did a good job overall. It was accurate most of the time, getting things right around 87.68% of the cases. It was particularly good at saying "yes" to the right people, with about 90.31% of its "yes" answers being correct. It also caught many of the real "yes" cases, about 96.12%. However, it struggled a bit in saying "no" correctly, with only 32.15% of its "no" answers being right. The overall score, called F1, was 93.12%, showing it did well in balancing everything.

One thing to remember is that the dataset was not balanced since 87% of clients were classified as good payers while only 13% were considered bad profile. Also, the dataset only had people who actually got the card, not those who were denied at first for other reasons, like unpaid debts. This might affect the model's performance in real situations. In the future, it would be a good idea to improve the model's ability to say "no" more accurately and consider these imbalances while making the model better.
