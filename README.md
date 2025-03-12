# Development-of-a-model-for-predicting-customer-churn-for-a-telecom-operator
**Project Description: Telecommunications**

The telecom operator "TeleDom" wants to combat customer churn. To achieve this, its employees will begin offering promo codes and special conditions to those who plan to discontinue services. To identify such customers in advance, the operator needs a model that will predict whether a subscriber will terminate the contract.

The operator provides two main types of services:

Landline Telephone Service: It is possible to connect a telephone to multiple lines simultaneously.
Internet: The connection can be of two types: via a phone line (DSL, Digital Subscriber Line) or fiber optic cable (Fiber optic).
Additionally, the following services are available:

Internet Security: Antivirus (DeviceProtection) and blocking unsafe websites (OnlineSecurity)
Dedicated Technical Support Line (TechSupport)
Cloud File Storage for Data Backup (OnlineBackup)
Streaming TV (StreamingTV) and movie catalog (StreamingMovies)
Customers can pay for services monthly or sign a contract for 1-2 years. Various payment options and the possibility of receiving an electronic receipt are available.

Description of Data

The data consists of files obtained from different sources:

contract_new.csv — contract information
personal_new.csv — personal data of the customer
internet_new.csv — information about internet services
phone_new.csv — information about telephony services
In all files, the column customerID contains the client’s code. Contract information is relevant as of February 1, 2020.
