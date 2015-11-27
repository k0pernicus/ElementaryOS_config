# ElementaryOS_config
Simple "TODO" list after each new installation of ElementaryOS

*	[Programming](#programming)
	*	[Editors](#editors)
	*	[Programming languages](#programming_languages)
*	[Social Network clients](#social_network_clients)
*	[Photography & Cinema](#photo_cinema)
*	[Utilities](#utilities)
	*	[Comfort](#comfort)
	*	[Productivity](#productivity)

## <a name="programming"></a>Programming

### <a name="editors"></a>Editors

#### Vim

*	Install Vim with ```sudo apt-get install vim```
*	You can ask to your machine to make Vim as default editor for **git** with:
	*	```git config --global core.editor "vim"```
	*	```export GIT_EDITOR=vim```

#### Atom

*	Make sure that **nodeJS** is installed with ```sudo apt-get install nodejs```
*	Download the version 1.0.19 of [Atom](https://github.com/atom/atom/releases/tag/v1.0.19) - the current release (1.1.0) does'nt work at all with ElementaryOS. If you don't want to download and install the latest version of Atom each time:
	*	```sudo add-apt-repository ppa:webupd8team/atom```
	*	```sudo apt-get update```
	*	```sudo apt-get install atom```
*	You can now install some cool stuff for this editor with **apm**, like:
	*	```apm install minimap```
	*	```apm install vim-mode```
	*	```apm install editor-stats```
	*	etc... 

### <a name="programming_languages"></a>Programming languages

#### Rust

*	Install Rust with ```curl -sSf https://static.rust-lang.org/rustup.sh | sh```
*	Install plugins for Atom:
	*	```apm install cargo-test-runner```
	*	```apm install language-rust```
	*	```apm install linter```
	*	```apm install linter-rust```
	*	```apm install racer```
	*	```apm install rust-api-docs-helper```

#### OCaml

*	Install ledit (to have some cool stuff on your terminal when you interprete Ocaml) with ```sudo apt-get install ledit```
*	Install the Ocaml compiler with ```sudo apt-get install ocaml```

#### Python

*	Install pip2 with: ```sudo apt-get install python-pip```
*	Install pip3 with: ```sudo apt-get install python3-pip```

## <a name="social_network_clients"></a>Social Network clients

#### Hangups - Hangouts client in your console

*	Use pip to install **hangups**: ```sudo pip3 install hangups```

#### Reditr - Reddit Linux client

*	Please to install ```libudev0``` on:
	*	https://launchpad.net/ubuntu/+source/udev/175-0ubuntu19/+build/4325790/+files/libudev0_175-0ubuntu19_i386.deb
	*	https://launchpad.net/ubuntu/+source/udev/175-0ubuntu19/+build/4325788/+files/libudev0_175-0ubuntu19_amd64.deb 
*	Install previous libraries with ```sudo dpkg --install <thepackage.deb>
*	Download [Reditr](http://reditr.com/?page=download)
*	Install the software with ```sudo dpkg --install <thepackage.deb>```

## <a name="photo_cinema"></a>Photography & Cinema

#### FadeIn - for scriptwriting

*	Download [FadeIn](http://www.fadeinpro.com/page.pl?content=download)
*	Install the software with ```sudo dpkg --install <thepackage.deb>```

## <a name="utilities"></a> Utilities

### <a name="comfort"></a> Comfort

#### Elementary Tweaks

*	Please to install the community PPA on the system: ```sudo apt-add-repository ppa:mpstark/elementary-tweaks-daily``
*	Update: ```sudo apt-get update```
*	Install elementary-tweaks with ```sudo apt-get install elementary-tweaks```

#### Numix

*	Please to install the community PPA on your system: ```sudo add-apt-repository ppa:numix/ppa```
*	Update: ```sudo apt-get update```
*	Install numix with ```sudo apt-get install numix-icon-theme-circle```

#### Transparent theme

*	Please to install the community PPA on your system: ```sudo add-apt-repository ppa:yunnxx/elementary```
*	Update: ```sudo apt-get update```
*	Install transparent theme with ```sudo apt-get install elementary-transparent-theme```

#### Super-wingpanel

*	Install Super-wingpanel with ```sudo apt-get install super-wingpanel```

#### Redshift

*	Download [Redshift](https://github.com/jonls/redshift/releases)
*	```cd redshift/```
*	```./configure && ./make && sudo ./make install```
*	Copy the redshift configuration file (root of this folder - for French guys) in ```~/.config/```
*	Run the redshift program with ```/usr/local/bin/redshift-gtk```

### <a name="productivity"></a> Productivity

#### Touchpad (for Zenbook UX303LN)

*	Please to install the community PPA on your system: ```sudo add-apt-repository ppa:hanipouspilot/focaltech-dkms```
*	Update: ```sudo apt-get update```
*	Install **focaltech**: ```sudo apt-get install focaltech-dkms```

*	To have multitouch on your touchpad, please to install **ginn** with:
	*	```sudo apt-get install ginn```
	*	Copy the ginn configuration file (wishes.xml) in ```/etc/```
	*	Run the ginn program with ```ginn /etc/wishes.xml```

#### Automatic installation of GPU drivers

*	Run ```sudo ubuntu-drivers autoinstall```

#### TLP (Power manager)

*	Please to install the community PPA on your system: ```sudo add-apt-repository ppa:linrunner/tlp```
*	Update: ```sudo apt-get update``` 
*	Install **tlp** and **powertop**: ```sudo apt-get install tlp tlp-rdw powertop```
*	Active **tlp** with ```sudo tlp start```

#### GPG

*	Install the software with ```sudo apt-get install gnupg2```
*	Import all your private & public keys (in a ```keys``` directory): ```for key in keys/; do gpg --import $key; done```
