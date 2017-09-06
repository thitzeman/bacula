# Bacula
This repository contains instructions and configuration files for installing and using Bacula, an open source backup solution.
#### Author: [Tyler Hitzeman](https://github.com/tyler-hitzeman)

#
### Step 1: Learn about Bacula
* You should have a general understanding of the following topics before attempting to install and use Bacula:
    * The architecture (i.e., how `bacula-dir`, `bacula-sd`, and `bacula-fd` interact)
    * The `bconsole` command line
    * What version best meets your needs. I use version 9.0.3.

#### Read through Bacula's documentation at [blog.bacula.org](http://blog.bacula.org/what-is-bacula/)


#### Read through [Blue Ocean's Guides](https://www.digitalocean.com/community/tutorial_series/how-to-use-bacula-on-centos-7)
* These are well written and straightforward. 
* If you want to start using Bacula as quickly as possible, I recommend simply following those guides. 
* If you want to customize your Bacula instance by using a newer version and optimizing configurations, however, I suggest using my documentation as a supplemental resource.  

#### Review the [Configuration File Diagram](https://github.com/tyler-hitzeman/bacula/*image*.png) provided in this repository

#### Review the [Raw Configuration Files](https://github.com/tyler-hitzeman/bacula/configs) provided in this repository.


#
### Step 2: [Install Bacula Server](bacula-install-server.md)
* This tutorial installs Bacula Server on a CentOS 7 system.
#
### Step 3: [Install Bacula Client](bacula-install-client.md)
* This tutorial installs Bacula Client on a CentOS 7 system.
#
### Stuck? See if your problem is covered in the [Troubleshooting File](troubleshooting.md)




