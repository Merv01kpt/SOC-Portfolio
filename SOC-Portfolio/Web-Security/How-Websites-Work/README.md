# How Websites Work

## Room Overview
This TryHackMe room introduces how websites work and covers HTML, JavaScript, Sensitive Data Exposure, and HTML Injection.

## Task 1 - Theory
Learned how websites work using browsers, servers, HTML, CSS, and JavaScript.

## Task 2 - HTML
- Fixed broken image (missing jpg)
Flag: DOGHTML

## Task 3 - JavaScript
- Changed page text using DOM manipulation
Code: document .getElementById("demo").innerHTML = "Hack the Planet";
Flag: JSISFUN
- Added button to trigger action

## Task 4 - Sensitive Data Exposure 
Found exposed password in source code.
Flag: testpasswd

## Task 5 - HTML Injection
Input was reflected back on page (Welcome Mervyn)
Injected:
<a href="http://hacker.com">http://hacker.com</a>
Flag: HTML_INJ3CTION

## Skills Learned
- HTML basics
- JavaScript DOM manipulation
- Source code inspection
- Sensitive data exposure
- HTML injection testing
