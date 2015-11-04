# ElementaryOS_config
Simple "TODO" list after each new installation of ElementaryOS

*	[Programming](#programming)
	*	[Editors](#editors)
	*	[Programming languages](#programming_languages)
*	[Social Network clients](#social_network_clients)
*	[Photography & Cinema](#photo_cinema)
*	[Utilities](#utilities)

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

## <a name="utilities"></a>Utilities

### Confort

#### Redshift

*	Download [Redshift](https://github.com/jonls/redshift/releases)
*	```cd redshift/```
*	```./configure && ./make && sudo ./make install```
*	Copy the redshift configuration file (root of this folder - for French guys) in ```~/.config/```
*	Run the redshift program with ```/usr/local/bin/redshift-gtk```

### Productivity
