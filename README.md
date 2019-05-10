Syntax highlighting for Asterisk dialplan.

## Features

Highlighting scopes include applications, functions, expressions, extension patterns, priority labels.  

![Syntax highlighting example](images/example.png)

Snippets:
- insert a new extension by typing 'e' then pressing 'TAB'. Tab stops at extension pattern, priority, application and application data
- insert a same extension by typing 's' then pressing 'TAB'. Tab stops at priority, application and application data 

## Known Issues

No support for AEL/AEL2.

## Release Notes

### 1.0.2

Added support for same =>  
Allow ":" character in extension pattern  
Fixed issue where special extension regex could partially match a custom extension  

### 1.0.0

Initial release.