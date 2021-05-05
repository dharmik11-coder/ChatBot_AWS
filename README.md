### Build ChatBot using Amazon Web Services
I have built a bot that can serve the purpose of ordering meal as well as getting responses to numerous AWS FAQ’s while ordering the food you want!
This is done with the help of machine learning technologies of **Amazon Web Services(AWS)** viz. **Lex and Kendra**.
I have created intents in Lex bot to OrderFood, OrderDessert and OrderDrinks as well as used a built-in intent based on AWS Kendra which serves as a powerful search query that was needed in this project to fulfill the requests for AWS FAQ’s coming through our bot. 
The website for this bot was hosted on **CloudFront** using **CloudFormation** stack with the required data and project files stored in **S3** bucket.
Use the **projectdocumentation.pdf** as a guide to create your own ChatBot!

The zip file contains :

**AgentAssistBot_3** zip folder for the bot that you can directly import to your AWS Lex service to build and test the bot on Lex console.

**FAQ_data.csv** file to import in your AWS Kendra index's FAQ and you can test it on the Kendra Search console to check replies for your query.

**resources.txt**(url endpoints) to help you host the bot and give it a User Interface using JavaScript with the help of AWS documentation.

**project_endpoint.txt** containing the URL of hosted project. (no longer in service to stop incurring charges from AWS as Kendra serivce gets out of free tier after several hours of usage)


