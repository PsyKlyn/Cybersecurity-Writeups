# HTB Dancing

## objective
find open share and get access

## steps
1. scan target using nmap
2. find smb port open
3. use smbclient to connect
4. list shares
5. access share without password
6. find flag inside

## result
i access smb share and get flag

## what i learn
- smb share can be open without auth
- need to check all shares
- enumeration is very important
