# Linux
Linux on Win
Launch linux on windows 
1st step downloand all nessesery services - i used AI - after 10minutes i fixed problems with wsl 0x80370114
checking web - by ip a,r
check open ports by ss -tuln
check who is in my web by ip neigh command 
check open ports by ss -tuln
Install fw  - and check status

sudo apt install ufw
sudo ufw enable
sudo ufw status verbose
sudo ufw allow from 192.168.0.0/24 to any port 22 - closed ssh to world
Make defense for bruteforce by root@DESKTOP-DJV9MDR:/home/xyz# sudo ufw limit 10/tcp
Addes user by..root@DESKTOP-DJV9MDR:/home/xyz# sudo adduser testowy_najlepszy
info: Adding user `testowy_najlepszy' ...
info: Selecting UID/GID from range 1000 to 59999 ...
info: Adding new group `testowy_najlepszy' (1001) ...
info: Adding new user `testowy_najlepszy' (1001) with group `testowy_najlepszy (1001)' ...
info: Creating home directory `/home/testowy_najlepszy' ...
info: Copying files from `/etc/skel' ...
New password:
Retype new password:
passwd: password updated successfully
Changing the user information for testowy_najlepszy
Enter the new value, or press ENTER for the default
        Full Name []: User2
        Room Number []: 2
        Work Phone []: 999 203 033
        Home Phone []: 423 234 343
        Other []: read me in vault.exe in ours password manager
Is the information correct? [Y/n] y
info: Adding new user `testowy_najlepszy' to supplemental / extra groups `users' ...
info: Adding user `testowy_najlepszy' to group `users' ...
root@DESKTOP-DJV9MDR:/home/xyz#
Added MFA to ROOT
sudo apt install libpam-google-authenticator - Using Al with guadience
