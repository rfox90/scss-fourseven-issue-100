# scss-fourseven

This repo demonstrated [Issue #100](https://github.com/fourseven/meteor-scss/issues/100) with the fourseven-scss meteor package on windows.

running this on windows lead to:

```
Your app is crashing. Here's the latest log.

Started MongoDB.
Started your app.

App running at: http://localhost:3010/
   Type Control-C twice to stop.

Errors prevented startup:

While building the application:
D:/Documents/GitHub/scss-fourseven/index.scss:2:9: Scss compiler error: file to import not found or unreadable: scssmain.scss
Current dir: D:/Documents/GitHub/scss-fourseven/


Your application has errors. Waiting for file change.
```
The problem was fixed in version 3.2.0!

Thanks!
