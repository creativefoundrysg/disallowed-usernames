# Disallowed Usernames
The goal of this project is to create a universal database of disallowed usernames for web applications. 
This repository contains a list of keywords that should be banned/disallowed to prevent users from registering with, on your software projects and apps to prevent impersonation and phishing on your platform.

## Formats
CSV

## Why
For example, you don't want someone to sign-up with the username titled `support` or `administrator`.
And depending on your setup, they could probably generate something like:

http://example.com/support

or

http://support.example.com

and use this to send out emails impersonating as someone un-suspecting from your application.

## How to use this

You can import this file directly from your database's GUI (like phpMyAdmin, Sequel Pro, HeidiSQL).

# License
This project is licensed under the [MIT License](https://github.com/dsignr/disallowed-usernames/blob/master/LICENSE)
