### IDOR

IDOR, or Insecure Direct Object References, is a security vulnerability that occurs when an attacker 
can manipulate input to access unauthorized resources or perform actions on behalf of another user. 
This typically happens when an application doesn't properly validate and authorize user requests, 
allowing attackers to directly reference internal objects (like files, database records, or URLs) that they shouldn't have access to.

`Simple explanation of IDOR:`

Imagine you're in a library, and each book has a number on it. 
The librarian lets you borrow books based on the numbers you give them. 
But what if you change the number on a book to something you're not supposed to have? 
If the librarian doesn't check properly, you might end up with a book you're not allowed to borrow.

Similarly, in web applications, each user has their own ID or reference to their data. 
If the application doesn't validate these references properly, 
someone could change the reference and access or manipulate data they shouldn't.

```
Mitigation:
Access token
salted password
list privilage
Unguessable parameter
```
