This is AWS Lex based chatbot.

The above code is hosted on Amazon S3.
An API named "chatbot" is used to connect the S3 bucket to the lambda function which further connects to the lambda function.
An AWS Lex chatbot named VoiceBot is working at the backend.
DynamoDB "bot_table" stores the values fetched from the user. 

Sample Output- 
![Sample Output](https://user-images.githubusercontent.com/36268383/78229510-17bae300-749e-11ea-81f3-9e85bc91886f.png)
