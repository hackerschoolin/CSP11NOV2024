> Take a snapshot of your vm before installing Nessus

> google "Nessus download"

> goto the tenable website and look for kali Nessus file and download

```bash
cd Downloads

dpkg -i NessusFile.DEB

systemctl start nessusd
```

> access at https://127.0.0.1:8834

> if you get security warning click advanced and continue

> Continue On Main Nessus Screen-> Pick Free Option Nessus Essentials-> Provide Firstname,lastname,email that you can access-> create username and password and remember for later-> submit

> wait for completion, and login

>if fails via gui

try `nessuscli update`

if cli command fails try after some time
