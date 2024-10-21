# Level 13 -> 14

**Objective:** Objective: The password for the next level is stored in /etc/bandit_pass/bandit14 and can only be read by user bandit14. For this level, you don’t get the next password, but you get a private SSH key that can be used to log into the next level. Note: localhost is a hostname that refers to the machine you are working on

**Commands:**

1. **ls**
   - Output: `sshkey.private`
   
2. **exit** the current session to proceed with using the SSH key.

3. **Download** the private key (or use it directly for login).
   - Use the following command to log into `bandit14` using the private key:
   ```bash
   ssh -i sshkey.private bandit14@bandit.labs.overthewire.org -p 2220
   ```
 we are logged into bandit14.

To get the password for this current level we run the command

 **_cat /etc/bandit pass/bandit14_**

**Password:** MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS