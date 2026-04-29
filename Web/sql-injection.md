# SQL Injection Practice

## objective
test login bypass using sql injection

## tools
- burp suite

## steps
1. open burp suite
2. intercept login request
3. send to repeater
4. try payload: ' OR 1=1 --
5. send request

## result
login bypass success

## what i learn
- input not validated is dangerous
- sql query can be changed
- need to sanitize input
