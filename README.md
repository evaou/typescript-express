# Express Server

## Setup

    $ npm init -y
    $ tsc --init

    $ npm install concurrently nodemon

    $ npm install express body-parser cookie-session
    $ npm install @types/express @types/cookie-session @types/body-parser

## Run

    $ npm start

## Term

- Middleware
  - does some processing of Reqeust and Response
  - e.g. body-parser adds body property onto Request
- Decorator
  - is applied as running the code
  - arguments in order
    - class prototype
    - property/method/accessor on the object
    - property descriptor
