# Shopee Challenge
## General Discription
Due to the recent COVID-19 pandemic across the globe, many individuals are increasingly turning to online platforms like Shopee to purchase their daily necessities. This surge in online orders has placed a strain onto Shopee and our logistics providers but customer expectations on the timely delivery of their goods remain high. On-time delivery is arguably one of the most important factors of success in the eCommerce industry and now more than ever, we need to ensure the orders reach our buyers on time in order to build our users’ confidence in us.

In order to handle the millions of parcels that need to be delivered everyday, we have engaged multiple logistics providers across the region. Only the best logistics providers that are able to meet Shopee’s delivery standards are partnered with us.

The performance of these providers is monitored regularly and each provider is held accountable based on the Service Level Agreements (SLA). Late deliveries are flagged out and penalties are imposed on the providers to ensure they perform their utmost.

The consistent monitoring and process of holding our logistics providers accountable allows us to maintain our promise of timely deliveries to our buyers.

### Task
Identify all the orders that are considered late depending on the Service Level Agreements (SLA) with our Logistics Provider.

For the purpose of this question, assume that all deliveries are considered successful by the second attempt.

For more detail about the challenge, please visit 
[Kaggle](https://www.kaggle.com/competitions/open-shopee-code-league-logistic/overview)

## Note
This is my personal approach for Shopee Challenge. In this project, I try to utilize the chaining method
in pandas and encapsulate code as function _(rather than split them in several code cell)_. This is a useful
practice which helps us the avoid duplicate the code.

## Requirements:
- Basic library for scientific computing: `pandas`, `numpy`
- Since the data file is quite large **(~750 MB)**, I also have the support from `modin[ray]`
which is a drop-in placement `import modin.pandas as pd` for speeding the reading and manipulating
the data.