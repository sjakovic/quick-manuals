# Setup SSH keys

```shell script
$ ssh-keygen -t rsa
```
Output:
```shell script
Generating public/private rsa key pair.
Enter file in which to save the key (/home/username/.ssh/id_rsa):
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /home/username/.ssh/id_rsa.
Your public key has been saved in /home/username/.ssh/id_rsa.pub.
The key fingerprint is:
SHA256:oQOvjWsVjhj0VvDsRrASownYIVfVkt9G4uZsdIogJyA demo@b
The key's randomart image is:
+---[RSA 2048]----+
|   ....o         |
|E + . * . o      |
| * o + o.+ .     |
|. + . X.o.o .    |
| . o O+*S * o    |
|  . *o  . =      |
|   = ..  .       |
|  . . + *+       |
|     +.          |
+----[SHA256]-----+
```
Copy ssh keys to server:
```
$ ssh-copy-id user@server_ip
```
