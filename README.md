# Lab 8 - Starter

## no partners

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why. <br> Answer: Within a Github action that runs whenever code is pushed.
2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)<br> Answer: no. we can use unit test to test the result of a single function
3) Would you use a unit test to test the “message” feature of a messaging application? Why or why not? For this question, assume the “message” feature allows a user to write and send a message to another user.<br> no, because messaging might involve mutiple functions working together(networking, storing, syncing), unit might not be enough.
4)  Would you use a unit test to test the “max message length” feature of a messaging application? Why or why not? For this question, assume the “max message length” feature prevents the user from typing more than 80 characters. <br> Yes, since we only need to test whether the length exceeded the limit, no other function calls are involved.
