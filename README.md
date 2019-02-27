# LinuxInstall
# xubuntu-18.04.2 (64 bits)

## Where to install
### Dual Boot
### Virtual Machine

## After installation
### Guest Additions
### Installing SW with the cmd prompt
Open a terminal and type the following lines. When necessary type "y" to confirm instalation (Do you want to continue? [Y/n]).

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
$ sudo apt-get install apt-transport-https
$ echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
$ echo "deb https://download.sublimetext.com/ apt/dev/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
$ sudo apt-get update
$ sudo apt-get install sublime-text
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