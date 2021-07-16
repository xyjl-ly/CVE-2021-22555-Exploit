# CVE-2021-22555-Exploit
CVE-2021-22555 Exploit

By Andy Nguyen

## INFO
A heap out-of-bounds write affecting Linux since v2.6.19-rc1 was discovered in net/netfilter/x_tables.c. This allows an attacker to gain privileges or cause a DoS (via heap memory corruption) through user name space


## 編譯
```
gcc -m32 -static -o exploit exploit.c
./exploit
```

## 測試版本
Exploit tested on Ubuntu 5.8.0-48-generic and COS 5.4.89+.
