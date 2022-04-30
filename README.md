# corona-chatbot-final-future-ready-talent

Build an Chatbot using Microsoft Azure Technology.

Chatbots are nothing new. In fact, they have been around in some form since the '60s. But those chatbots were nothing like what we have today with machine learning (ML) algorithms, which allow them to learn how to interact with users more effectively over time. Many companies are competing with their own variants to stand out from the pack, like Microsoft with its Azure platform.
click this link to check my chatbot https://portal.azure.com/#@abhisheknikam0508gmail.onmicrosoft.com/resource/subscriptions/e534eb46-26cf-43f3-8a66-5c86209b52de/resourceGroups/QnABotCovid123/providers/Microsoft.BotService/botServices/qnabotcovid123-bot/test

click this link to path my chatbot https://portal.azure.com/#@abhisheknikam0508gmail.onmicrosoft.com/resource/subscriptions/e534eb46-26cf-43f3-8a66-5c86209b52de/resourceGroups/QnABotCovid123/providers/Microsoft.BotService/botServices/qnabotcovid123-bot/overview
The QnA Maker Service enables you to build, train and publish a simple question and answer bot based on FAQ URLs, structured documents or editorial content in minutes. In this sample, we demonstrate how to use the QnA Maker service to answer questions based on a FAQ text file used as input.

# Concepts introduced in this sample::
The QnA Maker Service enables you to build, train and publish a simple question and answer bot based on FAQ URLs, structured documents or editorial content in minutes. In this sample, we demonstrate -.how to use the Active Learning to generate suggestions for knowledge base. -.how to use the Multiturn experience for the knowledge base .
# Prerequisites::
1)Follow instructions https://docs.microsoft.com/en-us/azure/cognitive-services/qnamaker/how-to/multiturn-conversation to create multiturn experience.
2)Follow instructions https://docs.microsoft.com/en-us/azure/cognitive-services/qnamaker/quickstarts/create-publish-knowledge-base to import and publish your newly created QnA Maker service.
3)Update appsettings.json with your kbid (KnowledgeBase Id), endpointKey and endpointHost. QnA knowledge base setup and application configuration steps can be found here.
4)(Optional) Follow instructions https://github.com/Microsoft/botbuilder-tools/tree/master/packages/QnAMaker to set up the QnA Maker CLI to deploy the model.

# Configure Cognitive Service Model::
1)Create a Knowledge Base in QnAMaker Portal.
2)Import "smartLightFAQ.tsv" file, in QnAMaker Portal.
3)Save and Train the model.
4)Create Bot from Publish page.
5)Test bot with Web Chat.
6)Capture values of settings like"QnAAuthKey" from
7)"Configuration" page of created bot, in Azure Portal.
8)Updated appsettings.json with values as needed.
9)Use value of "QnAAuthKey" for setting "QnAEndpointKey".
10)Capture KnowledgeBase Id, HostName and EndpointKey current published app
# Try Active Learning
1)Once your QnA Maker service is up and you have published the sample KB, try the following queries to trigger the Train API on the bot.
2)Sample query: "light"
3)You can observe that, Multiple answers are returned with high score.

# Testing the bot using Bot Framework Emulator::
1)https://github.com/microsoft/botframework-emulator is a desktop application that allows bot developers to test and debug their bots on localhost or running remotely through a tunnel.

2)Install the Bot Framework Emulator version 4.3.0 or greater from https://github.com/Microsoft/BotFramework-Emulator/releases
3)Connect to the bot using Bot Framework Emulator
4)Launch Bot Framework Emulator
File -> Open Bot
Enter a Bot URL of http://localhost:3978/api/messages

# Deploy the bot to Azure::
See Deploy https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-howto-deploy-azure?view=azure-bot-service-4.0 bot to Azure for instructions.

The deployment process assumes you have an account on Microsoft Azure and are able to log into the https://portal.azure.com/.

If you are new to Microsoft Azure, please refer to Getting started with Azure for guidance on how to get started on Azure.


