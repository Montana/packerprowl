# Packer Scripts for Prowl

The first thing is you can pick what script you need, as soon as you start the Vagrant box, via 

<pre>vagrant up</pre> 

Once you've done that make sure you have all of the dependecies you need, run 

<pre>brew install qt</pre> 

Once you've done that, install VMWare Fusion, these scripts are made for and optimzed for VMWare Fusion rather than VirtualBox, in the Prowl private repo, there are some keys left to get the $80 version of VMWare Fusion, so please look in there if you need VMWare Fusion. 

https://www.vmware.com/products/fusion.html

As soon as you have VMWare Fusion installed, run 

<pre>packer build virtualbox.json</pre> 

Even though it says "virtualbox.json" in the command, it will work on VMWare Fusion just fine. Again, these scripts are optimized for VMWare Fusion, but you can use VirtualBox if you must. If you're not familiar with VirtualBox, read the documentation, which can be found here 

https://www.virtualbox.org/wiki/Technical_documentation


