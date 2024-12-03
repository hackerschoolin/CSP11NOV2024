# 27NOV2024 Commands Below

useradd ezhaan -p Hacker@123 -s /usr/bin/zsh -m

useradd abhiteja -p Hacker@123 -c IamIronMan -u 7777

useradd abhiteja2 -p 'chinni' -c IamIronMan

openssl passwd -1

useradd phani -p '$1$RNJhsNQI$6gWz8R8o3pWbCX2wc6hFl0' -c IamIronMan -u 6666

useradd ganesh -p '$1$RNJhsNQI$6gWz8R8o3pWbCX2wc6hFl0' -c IamIronMan -u 5555 -m -s /usr/bin/zsh

usermod -h

usermod chinni1 -s /bin/bash

usermod chinni2 -d /home/batman -m 

usermod chinni3 -u 9999

usermod chinni1 -g ezhaan

usermod chinni2 -G ezhaan

usermod chinni1 -L

usermod ganesh -L

usermod ganesh -U

usermod ganesh -l wayne

# 28NOV2024 Commands Below

userdel chinni

userdel -r chinni

userdel -f chinni

useradd pranay -m -p $(openssl passwd -1 chinni)
