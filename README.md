# PasswordComplexityTester

A challenge was given at work to create a password complexity checker in powershell. This is what I came up with that provides a clean user interface for entering the password and checking it against certain criteria.

This password complexity checker with test the following use cases:
  1. It ensures that the password entered has at least 12 characters and no more than 24 characters
  2. It ensures that you have at least one capital letter
  3. It ensures that you have at least one lowercase letter
  4. It ensures that you are using at least one number
  5. It ensures that you aren't using more than 2 same consecutive characters
  
If you don't enter a password, it just exits the script. Also, at the end if you successfully meet the criteria, it will ppp up a form that tells you that you have a successful password.
