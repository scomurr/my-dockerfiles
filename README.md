# my-dockerfiles

# Kali
* Build
>> docker build -t custom-kali .

* RC File
alias kali='docker run -it --rm -v ~/Documents/kali-out:/mnt custom-kali /bin/bash'
