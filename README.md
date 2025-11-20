# SMTP-Tester

Simple form page in ASP.NET that test the connection to a mail server via SMTP

## File structure

- _root_
  HTML pages and files for indexing
- **css**
  Only css files
- **images**
  All images, icons and logos of the site
- **lib**
  External libraries used by the application

## Code structure

The page is simply divided in:

- **_HTML Part_**
  A form where input SMTP credentials
- **_Script C#_**
  That tests the credentials by trying to send an email using _SmtpClient_
