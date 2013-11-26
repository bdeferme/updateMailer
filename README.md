updateMailer
============

This shell script checks a system for available updates and mails them to a predefined email address.
Surely there are other ways to accomplish this like apticron on debian but I wrote this for my company to have a small script that works across most platforms we use.

Features
--------

- Define a subject
- Define a 'from' email address
- Define a 'to' email address
- Works on Red Hat and Ubuntu flavored distributions
- Is able to use yum-security to only notify on security updates for CentOS
- ... read the source ;-)
