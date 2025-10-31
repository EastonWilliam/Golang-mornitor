
# Website Monitoring and Alerting using Golang

This application monitor websites with expected status code. If the response status code does not match with expected status code, connection refused from server, then it triggers an email and alerts user

### Prerequisites

- Go
- Configure a SMTP server - [SMTP settings for Gmail](hhttps://myaccount.google.com/u/4/security) - Enable Less secure app access
- set GMAIL_ID, GMAIL_PASSWORD as environment variables

### Golang packages

- net/http
- time
- net/smtp
- os


### Demo


