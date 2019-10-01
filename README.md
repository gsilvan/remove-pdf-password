# remove-pdf-password
A shellscript to decrypt all pdf files sharing the same password in a folder. Some lecturer tend to encrypt their slides. That's why I made this script to not let me annoy.
## Requirements
 - bash
 - qpdf
## Install and usage
### Arch Linux
```bash
pacman -S qpdf
```
### Debian
```bash
apt-get install qpdf
```

Download the pdf files to a folder using `wget`, `curl` or whatever you like and follow this usage:
```bash
cd ~/PDF/folder
wget https://raw.githubusercontent.com/gsilvan/remove-pdf-password/master/freepdf
chmod +x freepdf
./freepdf "your password"
```
