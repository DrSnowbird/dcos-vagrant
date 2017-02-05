## Version work smoothly: 5.0.24. (I think 5.0.20 should be the same) 

* DC/OS Vagran VirtualBox Box image is 5.0.20
* I use 5.0.24 seems to have no glitch

Though, you can use "vagrant plug-in manager for VirtualBox". But, I don't have much luck for many trials and failures. And, it takes far much longer time for VirtualBox to upgrade the version for the images on the fly. 

My opinion, after my many failures in trying overcome the version incompatibility, such as the latest 5.1.* or, 5.0.32, all turned to have been wasting my time!

Make sure that you uninstall all the virtual box version completely before you reinstall the specific VirtualBox version.
```
sudo yum remove -y virtualbox*
or
sudo apt-get remove -y virtualbox*
```
Again, Use VirtualBox 5.0.24!! Then you will have the best smooth roll out. Use the following links to download both VirtualBox 5.0.24 and Extension and then follow your OS specifics to install. Then, run DC/OS Vagrant. You will have very easy installation/deployment.
 
```
http://download.virtualbox.org/virtualbox/5.0.20/
http://download.virtualbox.org/virtualbox/5.0.24/
```
