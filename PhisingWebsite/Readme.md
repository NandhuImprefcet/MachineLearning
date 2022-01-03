Title: Detecting Phishing website using data mining techniques
Description: The technological advancement paved the way for the development of 
e-commerce sites and even most of the people started shopping online where they 
give their sensitive information like bank details, username, password, etc. 
Fraudsters used this opportunity and created fake sites that look similar to the 
original to collect sensitive user data. In this data mining project, students will 
develop an algorithm to detect the phishing sites based on the characteristics like 
security and encryption criteria, URL, domain identity, etc. 
Details
Domain: The URL itself.
Ranking: Page Ranking
isIp: Is there an IP address in the weblink
valid: This data is fetched from google's whois API that tells us more about the 
current
status of the URL's registration.
activeDuration: Also from whois API. Gives the duration of the time since the
registration up until now.
urlLen: It is simply the length of the URL
is@: If the link has a '@' character then it's value = 1
isredirect: If the link has double dashes, there is a chance that it is a redirect. 1-> 
multiple
dashes present together.
haveDash: If there are any dashes in the domain name.
domainLen: The length of just the domain name.
noOfSubdomain: The number of subdomains preset in the URL.
Labels: 0 -> Legitimate website , 1 -> Phishing Link/ Spam Link
Task
Based on the given features, classify the website as legitimate website or phishing 
website link.
Dataset Link: https://www.kaggle.com/aman9d/phishing-dat
