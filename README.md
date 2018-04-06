# MOET-ml
MOET-Markup Language

These specs describe each step of the whole process to programmatically display your dapps on Quic keys to an MOET subscriber, through the YChain platform.

# Terminology:

Partner : individual or organization that aim at integrating their dapps on Quic Keys
Service URL: your dapp application URL endpoint, that provides UI by delivering usual xHTML pages which gets mapped to native android experience on Quic Keys

# Before starting
Before starting, get in touch with us at so that we can help you out.

# Using the markup language
The MOET-ml enables a simple and straight-forward way to provide a way for partner to integrate into the Quic Keys system by deeloping a simple web application that delivers xHTML pages.

MOET-ml is based on a subset of xHTML: MOET back-end server sends HTTP GET requests to Partner's application using HTTP, on behalf of the Quic Keys user, exactly like a web browser does. Partner's application is expected to reply with xHTML pages which gets turned into a android UX elements

# Security
Partner's application is expected to put Authorization header in every response with a token, that can be accessed from YChain's configuration page

# Some other notes
UTF-8 charset usage is mandatory
Don’t put special characters in your responses

# Examples 
Before specifying details of all the elements, let's build some quick examples

# Core xHTML
| Tag           | Attributes           | Mandatory  | Comments
| ------------- |:-------------:| -----:|-----:|
| `<html>`   |  | N | |
| `<head>`      |       |  N | |
| `<body>` |       |    N | |
| `<meta>` |       |     | |
| `<br>` |      |     | |  
| `<a>` |     |     | |  
| `<form>` |       |     | |  
| `<input>` |      |     | |  
