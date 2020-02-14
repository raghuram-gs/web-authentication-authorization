# OAuth2.0 and OpenId Connect  

## How authentication has evolved

### A basic simple login or Forms authentication

![](Images/BasicLogin.png)

Above system has to 

* Store user info securely
* Hash password
* Maintain or change the hash algorithm
* Take care of maintanance of security of the system


The login mechanism has evolved and we have new scenarios like mobile apps and web apps which is described below:

# Use case for identity 

* Simple login - Using forms and cookies
* Single sign-on across sites - SAML
* Mobile app login - How to achieve ? Cannot have cookies and need a long live session
* Delegate authorization - How to give access without sharing a password ?


**The delegate authorization problem**

How can I let a website or client access my data without giving my password ?

How a typical authorization works today

![](Images/AuthorizationExample.png)

## What is OAuth 2.0 ?

OAuth 2.0 is the industry-standard protocol for authorization

It solves the problem of delegated authorization


### OAuth 2.0 Terminologies


* Resource owner

One who owns the resource. If you have an account with Google or Facebook then you are the owner of these accounts


* Client

The application that needs the resource. 

It is the application(E.g Mobile app or Web app) that the resource owner uses which wants the data from the accounts(for e.g Google or facebook) of the resource owner.

* Authorization server

The system which grants the permission upon consent of the resource owner to access data (for e.g. accounts.google.com)

* 








