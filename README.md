# api
The API powering the CommunityPostalServicee code

## Base-Idea

Have a GraphDatabase with a very light REST-API on top. What is poewring the REST-API ist subjcet to who wants to create the code. Initial idea was a zend-expressive App but whatever it will be will be OK.

## Authentication

Authentication shall be done via OAuth so that we do not need to store passwords. That means to have multiple logins per user-account.

## Requirements

We will need to have at least one email-address per registered person so tht we can notify the people that will be needed to transport the item in question
