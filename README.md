# Packer Scripts for Prowl

The first thing is install Packer, go to https://www.packer.io/intro/index.html. Moving on to the Packer scripts themselves you can pick what script you need, as soon as you start the Vagrant box, via 

<pre>vagrant init hashicorp/precise64</pre>

Or whatever box you want to Vagrant into, another example is 

<pre>vagrant init ubuntu/trusty64 

Then make the Vagrant box go up 

<pre>vagrant up</pre> 

Once you've done that make sure you have all of the dependecies you need, run 

<pre>brew install qt</pre> 

Once you've done that, install VMWare Fusion, these scripts are made for and optimzed for VMWare Fusion rather than VirtualBox, in the Prowl private repo, there are some keys left to get the $80 version of VMWare Fusion, so please look in there if you need VMWare Fusion

https://www.vmware.com/products/fusion.html

As soon as you have VMWare Fusion installed, run 

<pre>packer build virtualbox.json</pre> 

Even though it says "virtualbox.json" in the command, it will work on VMWare Fusion just fine. Again, these scripts are optimized for VMWare Fusion, but you can use VirtualBox if you must. If you're not familiar with VirtualBox, read the documentation, which can be found here 

https://www.virtualbox.org/wiki/Technical_documentation

These scripts are ideal to create identical images for different environments, to test Prowl on. Which is why these scripts exist. 

