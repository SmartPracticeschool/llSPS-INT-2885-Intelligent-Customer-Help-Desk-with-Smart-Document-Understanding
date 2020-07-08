# llSPS-INT-2885-Intelligent-Customer-Help-Desk-with-Smart-Document-Understanding
Intelligent Customer Help Desk with Smart Document Understanding

This is the repository for files related to project with the title mentioned above which is built with the help of IBM Cloud services like IBM Watson Assistant, Watson Discovery, Watson Cloud Functions and Node Red App. 
This is submitted as a partial fulfillment for "Artificial Intelligence Developer" Internship Program provided by SmartInternz at Smartbrigde.

#Project Description : The typical customer care chatbot can answer simple questions, such as store locations and hours, directions, and maybe even making appointments. 
When a question falls outside of the scope of the pre-determined question set, the option is typically to tell the customer the question isn’t valid or offer to speak to a real person.


In this project, there will be another option. If the customer question is about the operation of a device, the application shall pass the question onto Watson Discovery Service, which has been pre-loaded with the device’s owners manual. 
So now, instead of “Would you like to speak to a customer representative?” we can return relevant sections of the owners manual to help solve our customers’ problems. 
To take it a step further, the project shall use the Smart Document Understanding feature of Watson Discovery to train it on what text in the owners manual is important and what is not.
This will improve the answers returned from the queries. 

#Scope of Work: Create a customer care dialog skill in Watson Assistant
Use Smart Document Understanding to build an enhanced Watson Discovery collection 
Create an IBM Cloud Functions web action that allows Watson Assistant to post queries to Watson Discovery 
Build a web application with integration to all these services & deploy the same on IBM Cloud Platform

The dataset or the document used for training in this project is the "Ecobee3_userguide" manual which is been added to the Watson Discovery for training.
The same has been included with this repo.

After Deployment : NodeRed Dashboard Link: https://node-red-lhjca.eu-gb.mybluemix.net/ui/#!/0?socketid=Oo_9kRzoCo1dVSDgAAAA

