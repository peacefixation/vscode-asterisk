# Change Log
All notable changes to the "asterisksyntaxhighlighter" extension will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [1.2.0] - 2025/09/11
- Added block comment support
- Application & function patterns are now case-insensitive 
- Application & function patterns now include those from Asterisk 16 to 22   
- Added module configuration syntax highlighting
- Fixed syntax highlighting for variable assignment with space before equals

## [1.1.4] - 2021/02/09
- Ignore escaped quotes in quoted string match

## [1.1.3] - 2020/12/23
- Fixed quoted string match

## [1.1.2] - 2020/12/22
- Added ConfBridge, ExecIf, SetMusicOnHold, StopMixMonitor and Verbose applications
- Removed 'Asterismcmd' prefix from Bridge, HasVoicemail, MacroExit, MiniVM, and Pickup applications
- Added '+' character to the extension pattern regex to conform to E.164 international number format
- Added snippets for 'exten =' (en) and ' same =' (sn)

## [1.1.0] - 2020/06/13
- Added While and EndWhile applications

## [1.0.2] - 2019/05/10
- Adjusted example image in README
- Removed release notes in favour of change log

## [1.0.1] - 2019/05/10
- Added support for same =>  
- Allow ":" character in extension pattern  
- Fixed issue where special extension regex could partially match a custom extension  

## [1.0.0] - 2017/08/22
- Initial release