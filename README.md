# voting-app
This is a voting-app which provides an interface for the user to vote and another interface to show the result.The application consists of
various components such as web application developed in Python to provide the user with an interface to choose between two options.
When you make selection, the vote is stored in Redis.This vote is then processed by an Worker, which is an application written in .NET.
The Worker application takes the new vote and update the persistent data base which is PostgreSQL.Finally, the result of the vote is
displayed in a web interface which is written in Node.js.
