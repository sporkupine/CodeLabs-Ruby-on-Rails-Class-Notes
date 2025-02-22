# Class 5 - The Ruby Programming Language Part 4

- [Project - Covid-19 Tracker and CLI Part 4](https://github.com/cruzgerman216/CodeLabs-Ruby-on-Rails-Class-Notes/blob/main/C05-Intro-To-Ruby-Part-4/CLI_Project_part_4.md)

## Authentication Systems 
Passwords are vulnerable to hackers. They are never stored as just strings in the database. To help combat security issues, there are tools that allow the programer to hash passwords to prevent these security vulnerabilities. We can use Bcrypt. 

## Bcrypt 
Bcrypt is a sophisticated and secure hash algorithm designed by The OpenBSD project for hashing passwords. The bcrypt Ruby gem provides a simple warpper for safely handling passwords. 

## Hashing vs Encrypting 
Don't get hashing and encrypting mixed up. They are both different. Encryption is "two-way", meaning you can encrypt data but also decrypt the encryption to gain this secret data. Whereas, hashing is "one-way", meaning it turns data into a irreversible state. The only way to check if the data is correct is to compare it to this hash. 

---

#### References
- https://github.com/bcrypt-ruby/bcrypt-ruby
- https://rubygems.org/gems/bcrypt/versions/3.1.12#:~:text=bcrypt()%20is%20a%20sophisticated,wrapper%20for%20safely%20handling%20passwords.
- http://ruby-for-beginners.rubymonstas.org/advanced/modules.html#:~:text=In%20Ruby%2C%20modules%20are%20somewhat,not%20have%20a%20method%20new%20.

--- 
- [Next Class](https://github.com/cruzgerman216/CodeLabs-Ruby-on-Rails-Class-Notes/blob/main/C07-Intro-To-Rails/ruby_on_rails_notes.md)
