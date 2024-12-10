# Abstract

Credit card fraud costs consumers and banks money every single day despite multiple systems in place to attempt to stop it. Rates of online purchases compared to purchases made in person are now at all-time highs, and quick and reliable fraud detection has become paramount. 

Using basic information about the transaction, customer, and merchant, we explored the data to learn more about underlying trends and developed additional features to flag transactions with a higher probability of fraudulent activity. We achieved this using Python to mine, manipulate, visualize, and summarize our dataset of ~1.3M transactions.

Using a combined set of raw and feature-engineered data points as its training baseline, our model was able to predict fraudulent transactions with up to **95% accuracy** using a Random Forest approach.

---

# Problem Statement / Motivation

The credit card industry processes billions of dollars in transactions daily, making timely and reliable fraud detection essential. An entire industry has emerged to support the banking and credit card transaction markets in fraud detection, employing various techniques including regression analysis, decision trees, neural networks, and AI/ML methods to analyze and make decisions using data.

Key trends in the credit card and fraud landscape:

- **Non-cash payments** increased at a rate of 9.5% per year since 2018, with payments value reaching $128.51 trillion in 2021 [1].
- **Card payments value** grew 10% annually since 2018, reaching $9.43 trillion in 2021 [1].
- **In-person card fraud** decreased due to the adoption of embedded chips in cards [2].
- **Remote fraud** increased, accounting for $4.57 billion in 2016 and growing since then [2].
- In 2016, the fraud rate for credit cards was 14.9 basis points, meaning for every $10,000 spent, $1.49 was fraudulent [2].

## Motivation

This work seeks to determine if fraudulent transactions can be predicted before execution using a limited set of data points about the customer. By reducing the frequency of fraudulent transactions:

- **Costs** associated with administering bank accounts and facilitating transactions are reduced, benefiting both corporations and consumers.
- **Merchants** can use the analysis to identify high-risk areas impacting their business, enabling operational changes to reduce fraudulent activity.

---

**References:**

[1] Non-cash payment data source  
[2] Fraud data trends source
