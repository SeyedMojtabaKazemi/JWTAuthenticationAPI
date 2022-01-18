# JWTAuthenticationAPI
Sample API with ASP.NET Core Restful API using JWT (Json Web Token) for login
This project was developed with .Net Core MVC archiructure

# Documentation

Swagger Url: https://localhost:44328/swagger/index.html

API Url: https://localhost:44328/

Online Document: https://documenter.getpostman.com/view/19206493/UVXkpbAQ

# Overview

### Controllers
This part contains of two controller that first is LoginController and user must first call Login Action from this controller then a token is generated.
after that user should call Get() Action from ValuesController and send the token that generated in previous level as Bearer Authorization from header.

### Model
this part contains UserModel for transfer user info

### Extensions
this part contains a ServiceExtension that provides sending bearer authorization via swagger
