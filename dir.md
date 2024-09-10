## Food Ordering Management System has Directory traversal vulnerability

## Affected version: 
Food Ordering Management System - 1.0

## Software:
https://www.sourcecodester.com/php/15689/food-ordering-management-system-php-and-mysql-free-source-code.html

## Vulnerability File:
http://localhost/foms/includes/

## Description:
Food Ordering Management System 1.0 is vulnerable to a directory traversal attack in /foms/includes/. An attacker can exploit this vulnerability to directly obtain sensitive server information. A malicious attacker could exploit this vulnerability to obtain sensitive information in the server database.

Status: CRITICAL

POC
```
http://localhost/foms/includes/
```

Direct access to this route can cause a directory traversal attack.

![CleanShot 2024-09-10 at 16 42 19@2x](https://github.com/user-attachments/assets/9d65dc72-375b-4921-b6e2-8b31a5ca1f4a)



