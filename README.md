# Lab 8 - Starter
Self 
https://y1qu.github.io/Lab8_Starter/
1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

Within a Github action that runs whenever code is pushed because in this way we can detect errors right after the code pushed so we can locate the block of code updated that cause the error and fixed it immediately.

2) Would you use an end to end test to check if a function is returning the correct output? 

No.

3) Would you use a unit test to test the “message” feature of a messaging application? Why or why not? For this question, assume the “message” feature allows a user to write and send a message to another user.

No I wouldn't because the message feature required interaction so I would perfer to use the E2E test method.

4) Would you use a unit test to test the “max message length” feature of a messaging application? Why or why not? For this question, assume the “max message length” feature prevents the user from typing more than 80 characters.

Yes, I would use unit test to test the max message length because it only test on an individual component without needs to interact with other parts of the application.