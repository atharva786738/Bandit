# Level 6->7 

Objective: The password for the next level is stored somewhere on the server and has all of the following properties:

**owned by user bandit7, owned by group bandit6, 33 bytes in size**

1. command used is **_find / -type f -user bandit7 -group bandit6 -size 33c_** 


_find /_----> find for a file in entire filesystem

_-type f_----> search for a file type 

_-user bandit7_-----> owned by user bandit7

_-group bandit6_-----> owned by group bandit6

_-size 33c_----> is 33 bytes in size

2. response given is multiple file locations.
the one we need is **_/var/lib/dpkg/info/bandit7.password_**

3. use cat /var/lib/dpkg/info/bandit7.password to get password

Password: morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj