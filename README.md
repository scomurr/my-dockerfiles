# my-dockerfiles

Kali
docker build -t custom-kali .
alias kali='docker run -it --rm -v ~/Documents/kali-out:/mnt custom-kali /bin/bash'
