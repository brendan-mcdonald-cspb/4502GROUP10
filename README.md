ABSTRACT
Credit card fraud costs consumers and banks money every single day despite multiple systems in place to attempt to stop it. Rates of online purchases compared to purchases made in person are now at all time highs, and quick and reliable fraud detection has become paramount. 
Using basic information about the transaction, customer, and merchant, we explored the data to learn more about underlying trends, and developed additional features to flag transactions with a higher probability of fraudulent activity. We achieved this using Python to mine, manipulate, visualize, and summarize our dataset of ~1.3M transactions.
Using a combined set of raw and feature engineered data points as its training baseline, our model was able to predict fraudulent transactions with up to 95% accuracy using a Random Forest approach.
PROBLEM STATEMENT/MOTIVATION
The credit card industry is responsible for processing billions of dollars in transactions on a daily basis, which makes timely and reliable detection of fraud paramount. An entire industry has sprung up to support the banking and credit card transaction markets in fraud detection, using all variants of regression analysis, decision trees, neural networks, and all types of AI/ML analysis to describe and make decisions using data. 
Non cash payments increased at a rate of 9.5 percent per year since 2018 with payments value reaching $128.51 trillion in 2021 [1] 
The value of card payments rose 10% annually since 2018 with card payments value reaching $9.43 trillion in 2021 [1]
In person card fraud decreased due to adoption of embedded chips in cards [2]
Remote fraud increased, accounting for $4.57 billion in 2016 and growing since then [2]
In 2016, the fraud rate for credit cards alone was 14.9 “basis points” meaning for every $10,000 spent, $1.49 was fraudulent [2]

The primary motivation of this work is to determine if we can predict fraudulent transactions before they are executed using a limited number of data points available about the customer. By reducing the frequency of fraudulent transactions, costs to administer bank accounts and facilitate transactions are reduced, benefitting both corporation and consumer. Additionally, merchants can use this analysis to determine areas of high risk that impact their business, allowing them to make changes to their operations to reduce the probability of fraudulent customer activity. 
