# credit-card-fraud-detection
As the world is rapidly moving towards digitization and money transactions are becoming cashless, the use of credit cards has rapidly increased. The fraud activities associated with it have also been increasing which leads to a huge loss to the financial institutions. Therefore, we need to analyze and detect the fraudulent transaction from the non-fraudulent ones. In this paper, we present a comprehensive review of various methods used to detect credit card fraud. These methodologies include Hidden Markov Model, Decision Trees, Logistic Regression, Support Vector Machines (SVM), Genetic algorithm, Neural Networks, Random Forests, Bayesian Belief Network. A comprehensive analysis of various techniques is presented. We conclude the paper with the pros and cons of the same as stated in the respective papers.

# What is Credit Card Fraud Detection?
“Fraud detection is a set of activities that are taken to prevent money or property from being obtained through false pretenses.”

Fraud can be committed in different ways and in many industries. The majority of detection methods combine a variety of fraud detection datasets to form a connected overview of both valid and non-valid payment data to make a decision. This decision must consider IP address, geolocation, device identification, “BIN” data, global latitude/longitude, historic transaction patterns, and the actual transaction information. In practice, this means that merchants and issuers deploy analytically based responses that use internal and external data to apply a set of business rules or analytical algorithms to detect fraud.

Credit Card Fraud Detection with Machine Learning is a process of data investigation by a Data Science team and the development of a model that will provide the best results in revealing and preventing fraudulent transactions. This is achieved through bringing together all meaningful features of card users’ transactions, such as Date, User Zone, Product Category, Amount, Provider, Client’s Behavioral Patterns, etc. The information is then run through a subtly trained model that finds patterns and rules so that it can classify whether a transaction is fraudulent or is legitimate.

# How Does Credit Card Fraud Happen?
Credit card fraud is usually caused either by card owner’s negligence with his data or by a breach in a website’s security. Here are some examples:

1. A consumer reveals his credit card number to unfamiliar individuals.
2. A card is lost or stolen and someone else uses it.
3. Mail is stolen from the intended recipient and used by criminals.
4. Business employees copy cards or card numbers of its owner.
5. Making a counterfeit credit card.

When your card is lost or stolen, an unauthorized charge can happen; in other words, the person who finds it uses it for a purchase. Criminals can also forge your name and use the card or order some goods through a mobile phone or computer. Also, there is the problem of using a counterfeit credit card – a fake card that has the real account information that was stolen from holders. That is especially dangerous because the victims have their real cards, but do not know that someone has copied their card. Such fraudulent cards look quite legitimate and have the logos and encoded magnetic strips of the original one. Fraudulent credit cards are usually destroyed by the criminals after several successful payments, just before a victim realizes the problem and reports it.

# Credit Card Fraud Detection Systems and the Steps to Implement AI Fraud Detection Systems
# Credit Card Fraud Detection Systems:

Off-the-shelf fraud risk scores pulled from third parties (e.g. LexisNexis or MicroBilt).
Predictive machine learning models that learn from prior data and estimate the probability of a fraudulent credit card transaction.
Business rules that set conditions that the transaction must pass to be approved (e.g. no OFAC alert, SSN matches, below deposit/withdrawal limit, etc.).
Among these fraud analytics techniques, predictive Machine Learning models belong to smart Internet security solutions.

# AI Fraud Detection System Implementation Steps:

Data Mining. Implies classifying, grouping, and segmenting of data to search millions of transactions to find patterns and detect fraud.
Pattern Recognition. Implies detecting the classes, clusters, and patterns of suspicious behavior. Machine Learning here represents the choice of a model/set of models that best fit a certain business problem. For example, the neural networks approach helps automatically identify the characteristics most often found in fraudulent transactions; this method is most effective if you have a lot of transaction samples.
Once the Machine Learning-driven Fraud Protection module is integrated into the E-commerce platform, it starts tracking the transactions. Whenever a user requests a transaction, it is processed for some time. Depending on the level of predicted fraud probability, there are three possible outcomes:

1. If the probability is less than 10%, the transaction is allowed.
2 If the probability is between 10% and 80%, an additional authentication factor (e.g. a one-time SMS code, a fingerprint, or a Secret Question) should be applied.
3. If the probability is more than 80%, the transaction is frozen, so it should be processed manually.

