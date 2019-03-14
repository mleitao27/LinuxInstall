# LinuxInstall
# xubuntu-18.04.2 (64 bits)

## Where to install
### Dual Boot
/*Under construction*/
### Virtual Machine
/*Under construction*/

## After installation
### Installing SW with the cmd prompt
Open a terminal and type the following lines. When necessary type "y" to confirm instalation (Do you want to continue? [Y/n]). After installing all the packages you want from the list bellow make sure you run in the terminal:
```
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get reboot
```

#### Some essentials
```
$ sudo apt-get install build-essential
$ sudo apt-get install ddd
$ sudo apt-get install ddd-doc
$ sudo apt-get install doxygen
$ sudo apt-get install doxygen-gui
$ sudo apt-get install xxgdb
```

#### Chrom~~e~~ium
```
$ sudo apt-get install chromium-browser
```

#### Some editors
##### Sublime Text (The Best!!!)
```
$ wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
$ echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
$ sudo apt update && sudo apt install sublime-text
```
##### Others
```
$ sudo apt-get install gedit
$ sudo apt-get install geany
$ sudo apt-get install kate
$ sudo apt-get install vim
```
##### Kile for LaTeX
```
$ sudo apt-get install kile
```

#### Git
```
$ sudo apt-get install git
```
*check bellow for a nice git client (GitKraken)*

#### Python
##### v2
```
$ sudo apt-get install python-dev
$ sudo apt-get install python-pip
$ sudo apt-get install ipython
```
##### v3
```
$ sudo apt-get install python3-dev
$ sudo apt-get install python-pip3
$ sudo apt-get install ipython3
```

#### Wireshark
```
$ sudo apt-get install wireshark
```
Having problems in first use? Try:
```
$ sudo dpkg-reconfigure wireshark-common
$ sudo chmod +x /usr/bin/dumpcap
$ sudo gpasswd -a $USER wireshark
```

#### SDL library
##### v1
```
$ sudo apt-get install libsdl1.2-dev
$ sudo apt-get install libsdl-image1.2-dev
$ sudo apt-get install libsdl-gfx1.2-dev
$ sudo apt-get install libsdl-mixer1.2-dev
$ sudo apt-get install libsdl-net1.2-dev
$ sudo apt-get install libsdl-sound1.2-dev
$ sudo apt-get install libsdl-ttf2.0-dev
```
##### v2
```
$ sudo apt-get install libsdl2-dev
$ sudo apt-get install libsdl2-image-dev
$ sudo apt-get install libsdl2-ttf-dev
```

#### Codeblocks
```
$ sudo apt-get install codeblocks
$ sudo apt-get install codeblocks-contrib
```

### GitKraken (Git Client)
1. Visit the [GitKraken](https://www.gitkraken.com/download) page for the latest version
2. Download the [Linux(.deb)](https://www.gitkraken.com/download/linux-deb) option
3. After download click on the file and when the window pop up click on the **Install** button

### Guest Additions (VirtualBox)
1. Insert Guest Additions CD Image (**Devices** tab)
2. Open the CD you just mounted
3. In a terminal in the CD's directory run:
```
$ sudo ./VBoxLinuxAdditions.run
```

<!---TODO-->
<!---eclipse-->
<!---vlc-->
<!---atom-->
<!---java-->