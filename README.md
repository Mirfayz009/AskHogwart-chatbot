
# AskHogwart-chatbot
This chatbot can answer questions about Hogwarts Summer School.

You can visit my chatbot by writing Hogwartschotbot in telegram

a.	Architecture overview:
 
Data storage of chatbot that I have created is 5KB. My chatbot does not do any embedding or keyword search, because it does not uses Chat-gpt or other ai to answer. I programmed my chatbot myself it provides you with list of question and you should enter question number to get answer. I added as the last question full information about the project. Reason why I did not use ai to create chatbot because I thought using ai is illegal. If user chooses the question “Where I can follow Hogwarts Summer School?”, it directs the user to  Hogwarts Summer School  Telegram, Youtube , Instagram channel. My chatbot uses API to do this.
b.	Main functionalities are
1.It provides you with questions and you should choose number only
2.It provides you with exact and short answers
3.Start interaction with command /start
4.Show a list of questions with command /question
5.Provides you with extra information
6.It is avaiable 24/7
Limitations are 
Do not use any embedding or keyword search
No LLM system
c. How you validated that answers never drift beyond the given knowledge base.
While creating my chatbot I fully used the information from knowledge base without adding  any extra information. My chatbot does not use any Ai to answer to question. Therefore there can not be any extra details which are not given in the knowledge base. I uploaded my code in gitignore section

