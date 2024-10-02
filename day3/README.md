## Linux pipes

```cat test.txt | grep 'serchkey'``` ---> Only gives lines from that file that contains the key in ''

```cat test.txt | less``` ---> Prints out file content, but you have the possibility to scroll

```cat test.txt | head -4``` ---> Prints first four lines of conent

```cat test.txt | tail -4``` --> Prints last four lines of conent

### Login 

```ssh [user]@[hostname_or_ip]``` --> Command used to securely connect to a remote server or computer over a network


### Disk Usage
```df``` --> System disk space usage

```df -h``` --> Display sizes in a human-readable format (e.g., KB, MB, GB)

```df -T``` -->  Display the type of file system.

```df -h /home``` --> Display the disk space usage for the specified mount point in a human-readable format

### Process

```ps``` --> display information about currently running processes

```ps -f``` --> Display processes in full format

```ps -e``` --> Show all running processes

```ps -u (user)``` --> Display processes for specific user

```ps -aux``` --> Show all processes with detailed information.

```top``` --> Display all processes

```free``` --> Display free and used memory in system(RAM)

```free -h``` --> Display free and used memory in system(RAM) in a human-readable format

```nohup``` --> Store output of a command

```
nohup example:
nohup free -h ----> nohup will store output of free-h in nohup.out file
```