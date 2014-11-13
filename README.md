ckan-vagrant-geodatagov
=======================

# Vagrant box for CKAN 

This attempts to use the ansible script from the (https://github.com/GSA/ckanext-geodatagov) GSA CKAN repository to make a dev setup.

## Setup

1. Install the latest [Virtualbox](https://www.virtualbox.org/wiki/Downloads)
2. Install the lastest [vagrant](http://downloads.vagrantup.com/)
3. Install pip
4. Install ansible
3. Clone this repository, eg `git clone git://github.com/ckan-vagrant-geodatagov.git`
4. Move to the directory with your terminal application `cd ckan-vagrant-geodatagov/`
5. setup the link
5. Create the instance `vagrant up`
6. Go get some coffee (it takes a few minutes)
7. Add to following line to `/etc/hosts` on your local machine:  `192.168.19.97 ckan.lo`
8. Open [http://ckan.lo](http://ckan.lo) in your browser.
	

You can log into your machine with the ```vagrant ssh``` command which will use keys that are autogenerated. That's the easiest way, but you should also be able to use standard ssh with a username and password, eg ```ssh 192.168.19.97 -l vagrant``` and the password is ```vagrant``` (root now?)