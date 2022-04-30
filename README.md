# corona-chatbot-final-future-ready-talent
Build an Chatbot using Microsoft Azure Technology.

Chatbots are nothing new. In fact, they have been around in some form since the '60s. But those chatbots were nothing like what we have today with machine learning (ML) algorithms, which allow them to learn how to interact with users more effectively over time. Many companies are competing with their own variants to stand out from the pack, like Microsoft with its Azure platform.
click this link to check my chatbot https://portal.azure.com/#@abhisheknikam0508gmail.onmicrosoft.com/resource/subscriptions/e534eb46-26cf-43f3-8a66-5c86209b52de/resourceGroups/QnABotCovid123/providers/Microsoft.BotService/botServices/qnabotcovid123-bot/test

click this link to path my chatbot https://portal.azure.com/#@abhisheknikam0508gmail.onmicrosoft.com/resource/subscriptions/e534eb46-26cf-43f3-8a66-5c86209b52de/resourceGroups/QnABotCovid123/providers/Microsoft.BotService/botServices/qnabotcovid123-bot/overview
The QnA Maker Service enables you to build, train and publish a simple question and answer bot based on FAQ URLs, structured documents or editorial content in minutes. In this sample, we demonstrate how to use the QnA Maker service to answer questions based on a FAQ text file used as input.

Concepts introduced in this sample::
The QnA Maker Service enables you to build, train and publish a simple question and answer bot based on FAQ URLs, structured documents or editorial content in minutes. In this sample, we demonstrate -.how to use the Active Learning to generate suggestions for knowledge base. -.how to use the Multiturn experience for the knowledge base .
Prerequisites::
Follow instructions https://docs.microsoft.com/en-us/azure/cognitive-services/qnamaker/how-to/multiturn-conversation to create multiturn experience.
Follow instructions https://docs.microsoft.com/en-us/azure/cognitive-services/qnamaker/quickstarts/create-publish-knowledge-base to import and publish your newly created QnA Maker service.
Update appsettings.json with your kbid (KnowledgeBase Id), endpointKey and endpointHost. QnA knowledge base setup and application configuration steps can be found here.
(Optional) Follow instructions here to set up the QnA Maker CLI to deploy the model.

Configure Cognitive Service Model::
Create a Knowledge Base in QnAMaker Portal.
Import "smartLightFAQ.tsv" file, in QnAMaker Portal.
Save and Train the model.
Create Bot from Publish page.
Test bot with Web Chat.
Capture values of settings like"QnAAuthKey" from
"Configuration" page of created bot, in Azure Portal.
Updated appsettings.json with values as needed.
Use value of "QnAAuthKey" for setting "QnAEndpointKey".
Capture KnowledgeBase Id, HostName and EndpointKey current published app

Testing the bot using Bot Framework Emulator::
https://github.com/microsoft/botframework-emulator is a desktop application that allows bot developers to test and debug their bots on localhost or running remotely through a tunnel.

Install the Bot Framework Emulator version 4.3.0 or greater from here
Connect to the bot using Bot Framework Emulator
Launch Bot Framework Emulator
File -> Open Bot
Enter a Bot URL of http://localhost:3978/api/messages

Deploy the bot to Azure::
See Deploy https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-howto-deploy-azure?view=azure-bot-service-4.0 bot to Azure for instructions.

The deployment process assumes you have an account on Microsoft Azure and are able to log into the https://portal.azure.com/.

If you are new to Microsoft Azure, please refer to Getting started with Azure for guidance on how to get started on Azure.
