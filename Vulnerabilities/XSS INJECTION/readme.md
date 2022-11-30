# Cross-Site Scripting (XSS)
Cross-site scripting occurs when attackers or malicious users can manipulate a web site or web application to return malicious JavaScript to users. When this malicious JavaScript is executed in the user’s browser, all of the user’s interactions with the site (including but not limited to authentication and payment) can be compromised by the attacker.
## Primary types of cross-site scripting
- DOM-based XSS
- Reflected XSS
- Stored XSS
## Preventing XSS Attacks
XSS vulnerabilities are incredibly easy to create by accident. To prevent them, you need to put in place good coding practices, code review processes, and multiple layers of defense.

The easiest way to prevent XSS would be to never allow users to supply data that is rendered into the page, but the fact is that this isn’t a practical answer, since most applications store and manipulate user input in some form. Unfortunately, there is no single foolproof way to prevent XSS. Therefore, it is important to have multiple layers of defense against cross-site scripting.
- Validate and sanitize user-provided data
- HTML Encoding
- Use a security encoding library
