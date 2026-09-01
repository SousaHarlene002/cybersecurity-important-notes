## Password Security ##

# What is Password Security?

## Introduction

Password security is the practice of protecting passwords and authentication information from unauthorized access.

Passwords are one of the most common methods used to protect accounts, applications, devices, and online services.

A weak or compromised password can allow an attacker to access sensitive information or take control of an account.

For this reason, creating, storing, and managing passwords securely is an important part of cybersecurity.

---

## Why Are Passwords Important?

Passwords are commonly used to verify that a person is authorized to access an account or system.

They can protect:

* Email accounts
* Social media accounts
* Online banking accounts
* Computers and mobile devices
* Databases
* Company systems
* Cloud services
* Online applications

If an attacker obtains a password, they may be able to access the associated account.

---

## What Makes a Password Weak?

A weak password is easier for an attacker to guess or obtain.

Examples of weak passwords include:

* `123456`
* `password`
* `qwerty`
* A person's name
* A birthday
* A phone number
* Simple patterns
* The same password used on many websites

Personal information can sometimes be discovered through social media or other sources, making it a poor choice for passwords.

---

## What Makes a Password Strong?

A strong password should be difficult for others to guess.

Important characteristics include:

* Sufficient length
* Uniqueness
* Avoiding easily predictable information
* Avoiding common passwords
* Using a different password for each important account

Long passwords or passphrases can be easier to remember while still providing strong security.

For example, a passphrase made from several unrelated words can be stronger than a short, predictable password.

---

## Password Reuse

Password reuse occurs when the same password is used for multiple accounts.

This creates a significant security risk.

For example, imagine that a person uses the same password for their email and an online shopping account.

If the shopping account is compromised and the password is exposed, an attacker may try the same password on the person's email account.

This is sometimes called **credential stuffing** when attackers use previously exposed username and password combinations against other services.

Using unique passwords helps reduce this risk.

---

## Password Storage

Passwords should not normally be stored as plain text.

Secure systems generally protect passwords using specialized password hashing mechanisms.

A **password hash** is produced by applying a one-way cryptographic process to a password.

When a user logs in, the system can process the entered password and compare the result with the stored password verification data.

Modern password storage should use password-hashing algorithms designed specifically for this purpose, such as:

* Argon2
* bcrypt
* scrypt

A unique **salt** should also be used with password hashing to make certain attacks more difficult.

---

## Password Security and Authentication

Password security is only one part of authentication.

Authentication is the process of verifying a user's identity.

Other authentication factors can include:

* Something you know — such as a password
* Something you have — such as a security key or authentication device
* Something you are — such as a biometric characteristic

Using more than one factor can provide stronger protection than using a password alone.

This is known as **multi-factor authentication (MFA)**.

---

## Best Practices

Some important password security practices include:

* Use strong and unique passwords.
* Avoid using personal information in passwords.
* Do not reuse passwords across important accounts.
* Use a password manager when appropriate.
* Enable multi-factor authentication.
* Never share passwords with other people.
* Be careful when entering passwords on unfamiliar websites.
* Change a password when there is evidence that it has been compromised.
* Keep devices and software updated.

---

## Conclusion

Password security is an important part of protecting digital accounts and systems.

Strong and unique passwords can reduce the risk of unauthorized access, while password managers and multi-factor authentication can provide additional protection.

Understanding password security is also important for learning how attackers attempt to obtain passwords.

The next topics in this section will explore **strong passwords, password attacks, password managers, and multi-factor authentication** in greater detail.
