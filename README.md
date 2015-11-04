# ElementaryOS_config
Simple "TODO" list after each new installation of ElementaryOS

*	[Programming languages](#programming_languages)
*	[Social Network clients](#social_network_clients)
*	[Photography & Cinema](#photo_cinema)
*	[Utilities](#utilities)

## <a name="programming_languages"></a>Programming languages

### Rust

*	Install Rust with ```curl -sSf https://static.rust-lang.org/rustup.sh | sh```

### OCaml

*	Install ledit (to have some cool stuff on your terminal when you interprete Ocaml) with ```sudo apt-get install ledit```
*	Install the Ocaml compiler with ```sudo apt-get install ocaml```

## <a name="social_network_clients"></a>Social Network clients

### Reditr - Reddit Linux client

*	Please to install ```libudev0``` on:
	*	https://launchpad.net/ubuntu/+source/udev/175-0ubuntu19/+build/4325790/+files/libudev0_175-0ubuntu19_i386.deb
	*	https://launchpad.net/ubuntu/+source/udev/175-0ubuntu19/+build/4325788/+files/libudev0_175-0ubuntu19_amd64.deb 
*	Install previous libraries with ```sudo dpkg --install <thepackage.deb>
*	Download [Reditr](http://reditr.com/?page=download)
*	Install the software with ```sudo dpkg --install <thepackage.deb>```

## <a name="photo_cinema"></a>Photography & Cinema

### FadeIn - for scriptwriting

*	Download [FadeIn](http://www.fadeinpro.com/page.pl?content=download)
*	Install the software with ```sudo dpkg --install <thepackage.deb>```

## <a name="utilities"></a>Utilities

### Redshift

*	Download [Redshift](https://github.com/jonls/redshift/releases)
*	```cd redshift/```
*	```./configure && ./make && sudo ./make install```
*	Copy the redshift configuration file (root of this folder - for French guys) in ```~/.config/```
*	Run the redshift program with ```/usr/local/bin/redshift-gtk```
