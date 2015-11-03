# ElementaryOS_config
Simple "TODO" list for each new installation of ElementaryOS on my laptop

### Reditr - Reddit Linux client

*	Please to install ```libudev0``` on:
	*	https://launchpad.net/ubuntu/+source/udev/175-0ubuntu19/+build/4325790/+files/libudev0_175-0ubuntu19_i386.deb
	*	https://launchpad.net/ubuntu/+source/udev/175-0ubuntu19/+build/4325788/+files/libudev0_175-0ubuntu19_amd64.deb 
*	Install previous libraries with ```sudo dpkg --install <thepackage.deb>
*	Download [Reditr](http://reditr.com/?page=download)
*	Install the software with ```sudo dpkg --install <thepackage.deb>```

### FadeIn - for scriptwriting

*	Download [FadeIn](http://www.fadeinpro.com/page.pl?content=download)
*	Install the software with ```sudo dpkg --install <thepackage.deb>```

### Redshift

*	Download [Redshift](https://github.com/jonls/redshift/releases)
*	```cd redshift/```
*	```./configure && ./make && sudo ./make install```
*	Copy the redshift configuration file (root of this folder - for French guys) in ```~/.config/```
*	Run the redshift program with ```/usr/local/bin/redshift-gtk```
