# WebSecurity_Week8

Time spent: **12** hours spent in total

> Objective: Find and exploit the security vulnerabilities in three different versions (blue, green, and red) of the Globitek website.

The six possible exploits are:
- Username Enumeration
- Insecure Direct Object Reference
- SQL Injection
- Cross-site Scripting
- Cross-site Request Forgery
- Session Hijacking / Fixation

Each version of the site has been given two of the six vulnerabilities.

## Blue

**Vulnerability 1:** SQL Injection - The id parameter is un-sanitized and escapable on the salesperson page.

<img src='https://github.com/buttabu/WebSecurity_Week8/blob/master/Week8/Week8_GIFs/blue1.gif' title='SQLI' alt='SQLI' /> 

**Vulnerability 2:** Session Hijacking / Fixation - A new session ID is not regenerated when logging back in.

<img src='https://github.com/brandonmchin/CodePath/blob/master/Week8/Images/week8_sessid.gif' title='SESSID' alt='SESSID' /> 

## Red

**Vulnerability 3:** Insecure Direct Object Reference - Hidden salesperson IDs are accessible.

<img src='https://github.com/brandonmchin/CodePath/blob/master/Week8/Images/week8_idor.gif' title='IDOR' alt='IDOR' /> 


## Green

**Vulnerability 4:** Username Enumeration - Error message text becomes unbold if the username does not exist, revealing information to the attacker.

<img src='https://github.com/brandonmchin/CodePath/blob/master/Week8/Images/week8_enum.gif' title='Enumeration' alt='Enumeration' /> 

**Vulnerability 5:** Stored Cross-site Scripting - The "name" and "feedback" fields on the Feedback page are unsanitized. Guests can send malicious messages with embedded web scripts that will trigger once opened. 

<img src='https://github.com/brandonmchin/CodePath/blob/master/Week8/Images/week8_xss.gif' title='XSS' alt='XSS' /> 

## License

    Copyright 2017 Abu Butt

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
