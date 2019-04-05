![Alt text](/screenshots/logo-wide.png)

A lightweight Javascript web application that features two password tools.

* Strength Check - Tests the strength of a password and estimates how long it may take to brute-force it. Tips on improving the password's strength are also provided. 

![Alt text](/screenshots/screenshot3.png)

* Breach Check - Checks a password against Have I Been Pwned's breach database.

![Alt text](/screenshots/screenshot2.png)

PassCheck doesn't log or store passwords that have been entered into it, the only place your password is transmitted to is to haveibeenpwned.com over a HTTPS connection. No information regarding you is logged against that password, so it is not possible to identify what user or IP address has checked a password on the site.

# Setup

To use this on your web server, drop all the files into your web root directory and amend as you see fit (display, embed content into an existing webpage etc.) The default index.html files is set to display a logo from an image hosted at images/passcheck.png - add an image to that location if a photo is required.

It is highly recommend that, if you use this application on an Internet-facing web server, that you use HTTPS to ensure that passwords entered into it are not passed from the user to your web server in plain text.
