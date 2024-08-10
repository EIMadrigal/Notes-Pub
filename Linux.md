## Linux

```bash
cat /etc/passwd  # list all users
sudo -i  # login with root
sudo -i -u username  # login another shell with user
sudo yum update  # update all existing packages
sudo yum install firewalld
systemctl --user restart httpd  # allow user run service without pw


ls /etc | wc -l
ls -ld ta*
ls -d *[0-9]*
ls -l xxx 2> files, standard error
ls -ad .*
ls -a | grep '^\.'
cat file | more
cat -n file | tail -8 | head -4
grep 'word' file
grep -rnw ./play -e 'Lion'

ls | egrep -o '^[a-zA-Z0-9.]*'

ksh | tee | ksh
```

### Linux

```bash
nslookup example.com  # A record
nslookup 192.168.38.7  # PTR record

telnet 192.168.38.7 443

sudo yum install bind-utils
dig example.com A +short +trace
dig +answer +noall example.com @8.8.8.8  # custom DNS server

```
