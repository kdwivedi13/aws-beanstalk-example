# Deloitte - aws-beanstalk-example
aws-beanstalk-example : API that will use a string as input and does a find and replace for certain words and outputs the result. For example: replace Google for Google©

Request - 
curl --location --request POST 'http://kapildeloitteapp-env.eba-ryhgwq4v.us-east-1.elasticbeanstalk.com/append-copyright-symbol' \
--header 'Content-Type: text/plain' \
--data-raw 'We really like the new security features of Google Cloud'

Response - 
We really like the new security features of Google© Cloud
