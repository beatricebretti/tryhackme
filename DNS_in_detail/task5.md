CNAME
`user@thm:~$ nslookup --type=CNAME shop.website.thm`
```
Server: 127.0.0.53
Address: 127.0.0.53#53

Non-authoritative answer:
shop.website.thm canonical name = shops.myshopify.com
```
TXT
`user@thm:~$ nslookup --type=TXT website.thm`
```
Server: 127.0.0.53
Address: 127.0.0.53#53

Non-authoritative answer:
website.thm text = "THM{7012BBA60997F35A9516C2E16D2944FF}"
```
MX record num priority 
`user@thm:~$ nslookup --type=MX website.thm`
```
Server: 127.0.0.53
Address: 127.0.0.53#53

Non-authoritative answer:
website.thm mail exchanger = 30 alt4.aspmx.l.google.com
```
IP Adress for A record
`user@thm:~$ nslookup --type=A www.website.thm`
```
Server: 127.0.0.53
Address: 127.0.0.53#53

Non-authoritative answer:
Name: www.website.thm
Address: 10.10.10.10
```