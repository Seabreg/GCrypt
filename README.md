<pre>
    ▄▄▄▄      ▄▄▄▄                                          
  ██▀▀▀▀█   ██▀▀▀▀█                                  ██     
 ██        ██▀        ██▄████  ▀██  ███  ██▄███▄   ███████  
 ██  ▄▄▄▄  ██         ██▀       ██▄ ██   ██▀  ▀██    ██     
 ██  ▀▀██  ██▄        ██         ████▀   ██    ██    ██     
  ██▄▄▄██   ██▄▄▄▄█   ██          ███    ███▄▄██▀    ██▄▄▄  
    ▀▀▀▀      ▀▀▀▀    ▀▀          ██     ██ ▀▀▀       ▀▀▀▀  
                                ███      ██                 
</pre>

# Simple file encryption tool written in C/C++

![Screenshot](https://github.com/GasparVardanyan/GCrypt/raw/master/screenshot.png)

## Installation

### Installation on BlackArch Linux
`sudo pacman -Syy gcrypt`

### Installation on Arch Linux
`mkdir GCrypt`<br>
`cd GCrypt`<br>
`wget https://raw.githubusercontent.com/GasparVardanyan/GCrypt/master/blackarch/PKGBUILD`<br>
`makepkg -si`

### Installation on Linux
`git clone https://github.com/GasparVardanyan/GCrypt.git`<br>
`cd GCrypt`<br>
`sh $PWD/compile.sh`<br>
`sudo cp $PWD/gcrypt /bin/`<br>
`sudo chmod +x /bin/gcrypt`

### Windows executables
[Download GCrypt 32-bit](https://raw.githubusercontent.com/GasparVardanyan/GCrypt/master/windows/gcrypt32.exe)<br>
[Download GCrypt 64-bit](https://raw.githubusercontent.com/GasparVardanyan/GCrypt/master/windows/gcrypt64.exe)
