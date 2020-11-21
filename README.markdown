# [Password checker](https://ericswpark.github.io/password-checker/)

Password strength. Password strength. Password strength.

A lot of "password strength checkers" implemented in major websites believe that more character types in your password will make your password stronger. That really isn't the case, so I tried creating a tool to show just how long your 8-character mix of passwords will resist brute-forcing.

The math and logic is really simple - step 1 decides the password character pool (so for lowercase alphabets, there would be 26 characters added to the pool, and so on), and step 2 decides the exponent to calculate the password space. Then, the password space is divided with guesses in order to find out how long brute-forcing your typical password will take.

This tool is not perfect - please do NOT base your security practices just from the results of this tool. I am not responsible for any problems that may arise from using this tool.

The best way of not getting your passwords cracked is using a password manager, like KeePassXC.