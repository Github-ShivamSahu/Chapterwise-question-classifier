# Chapterwise-question-classifier
so i have made a classifier ai using gemini flash 2.0
its objective is to classify questions from the question paper chapterwise.
it doesnt work for questions with digram.

THIS IS HOW IT WORKS:

1. extracts text using pdfplumber
2. i used prompt template to tell it to ignore oth language other than english as the question paper contains same question in 2 laguages (hindi and english)
3. then it maps out question according to given chapters

ACCURACY:

this is the first prototype i have made on this concept 
the ACCURACY is around 70% (if temperature = 0.3) #it performs best in this temperature


FUTURE DEVELOPMENT PLAN:

if you pass the pdf directly into chatbots the accuracy drops to around 55%
i will develop this prototype by creating an automated system that uses langdetect and regex to clean the data provided to chatbot
that will incerase the accuracy in future.
also ill exsperiment with diffirent techniques.
