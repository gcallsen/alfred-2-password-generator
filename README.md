# Generate Password

This workflow generates a new password using openssl rand base64.
This method produces outputs pseudo-random bytes after seeding the random number
generator once. It performs a base64 encoding on the output.

## Download

[Alfred 2 Password Generator](https://github.com/gcallsen/alfred-2-password-generator/raw/master/generate_password.alfredworkflow)

## Useage

* Type 'pwd'
  * Optionally, press space bar and type a number to specify the length of your password.
  * By default it is 15 characters
* New password is copied to your clipboard
* Paste new password wherever you want it.
* Make sure to save it!

## Why
I use 1Password for my password management and love the generate password
feature. However, I'm lazy and it takes too long to access.
