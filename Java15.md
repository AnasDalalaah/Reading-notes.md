# BCrypt

## Password Hashing

In order to have a functional web application with user registration and for that we need a database with the users credentials, storing user's data can be dangerous , for an example we can't simply store passwords as plain texts , we need a way to encrypt and decrypt these passwords whenever it is necessary. A simple approach to solve this problem is to use hashing algorithms which "hash" the password to one long line of characters.

Hashing algorithms are powerful because:

- It is easy to compute the hash but difficult or even impossible to regenerate the original password if only the hash value is known.

- It's difficult to create an initial input that would match a specific desired output.

![hashing](https://images.ctfassets.net/23aumh6u8s0i/3xP2opDfoin34ScJZMBQB5/bd706f86ade6ad72513eea23d22b039b/encryption-flow)

### Some commonly used hashing algorithms are:

1. MD5

2. SHA

3. SHA-256

## jBCrypt
 is a Java™ implementation of OpenBSD's Blowfish password hashing code, as described in "A Future-Adaptable Password Scheme" by Niels Provos and David Mazières.

## The API is very simple:
```
// Hash a password for the first time
String hashed = BCrypt.hashpw(password, BCrypt.gensalt());

// gensalt's log_rounds parameter determines the complexity
// the work factor is 2**log_rounds, and the default is 10
String hashed = BCrypt.hashpw(password, BCrypt.gensalt(12));

// Check that an unencrypted password matches one that has
// previously been hashed
if (BCrypt.checkpw(candidate, hashed))
	System.out.println("It matches");
else
	System.out.println("It does not match");
```
