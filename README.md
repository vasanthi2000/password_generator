# Password-Generator

This project is a Java Console Application to generate random passwords and perform password strength checks.

## Introduction

With the growing trend of hacking attacks, everyone should create different and complex passwords for their diverse accounts to keep them secure. Remembering every password is not humanly possible and noting it down somewhere is not a wise idea. Hence, people take the help of Password generators to create strong and complex passwords for their accounts. To generate such functionality all by yourself, you can take advantage of the function that java offers. Whenever a user is developing an account on a new website, you can use that program to develop a password. To take the safety of the password a notch above, you can enforce such functionality so that it saves passwords in encrypted form.
While working on it, I decided to include a password strength checker feature that checks the overall strength of the entered password. I was pretty happy with how it turned out, but I realized that it was not very straightforward to use for someone who does not know how it is supposed to work. So, I decided to create a GUI for the application for the next step, which is available in the Password-Services repository.

## Functionalities

### 1. Generating a Password:

- The user answers with "Yes" or "No" to questions about using uppercase letters, lowercase letters, numbers, or symbols.
- The user then enters the desired length of the password.
- A password alphabet is generated based on the user's answers, which is a string containing the chosen characters.
- Random characters from the password alphabet are selected and combined to form a completely random string according to the user's preferences.
- The randomly generated password is then displayed on the console.

### 2. Checking a Password's Strength:

The strength check is based on the following criteria:
- The password uses uppercase letters.
- The password uses lowercase letters.
- The password uses numbers.
- The password uses symbols.
- The length of the password is 8 or more (8 is often the minimum required length for a decent password).
- The length of the password is 16 or more (16 is considered to be the minimum length for a good password).

These criteria are used to calculate a score for the password, which determines the message displayed to the user indicating the strength of the password (weak/medium/good/great).

### 3. Displaying Useful Information:

This is a minor feature that displays information for the user on the console about password security, such as avoiding using the same password twice, avoiding character repetition, keyboard patterns, dictionary words, letter or number sequences, etc.
