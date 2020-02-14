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

**The delegate authorization problem **
How can I let a website or client access my data without giving my password ?

## What is OAuth2.0 ?

OAuth 2.0 is the industry-standard protocol for authorization

OAuth2.0 solves the problem of deledated authorization for e.g.











