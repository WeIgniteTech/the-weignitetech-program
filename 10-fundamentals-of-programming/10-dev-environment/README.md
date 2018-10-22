# Dev environment
> The dev environment is a fundamental asset for the programmer. It contributes to the quality of the code (by ensuring its predictability) and gives the programmer the possibility to fully control the build process.    

## Learning goals
This topic will guide you through: 
* understand what a dev environment is
* what a (good) dev environment can help you with
* install and build your own dev environment
* understand the importance of predictability in the build (and run) process
* getting familiar with the terminal and the command line
* getting familiar with the Linux system
 
## Prerequisite to this topic 
> No reading or homework from a previous session before this one. 
  * Create a `GitHub` account
  * Install the following software on your machine (you might need to restart your machine if your system requires so): 
    * [VirtualBox (5.2.20)](https://www.virtualbox.org/wiki/Downloads)
    * [Vagrant (2.2.0)](https://www.vagrantup.com/downloads.html)
  * Curious? Read this [blog post](https://www.getzephyr.com/insights/benefits-standardized-development-environments-agile-development)

## Content of the session
> The session is approx. 3 hours. We start first by installing a predefined dev environment (a Linux desktop running in a Virtual Machine). When the dev environment is installed we we personalize it and get familiar with it. 

  * From your machine (aka `Host`)

    * Create a `WIT` folder and copy the following `Vagrantfile` into the same folder: (TODO: link to a VagrantFile `raw`)
    * Open a terminal and go to your `WIT` folder where the `Vagrantfile` is now copied
    * Run `vagrant up`
      (a Lubuntu desktop - a Linux distribution - will be running in a virtual machine) 

  * In the VM (aka `Guest`)
    * Explore the newly installed VM together

  * Exercises (TODO)
    * create your user
    * setup your GitHub account
    * setup your dotfiles (TODO)


## Further reading
 * [Intro to Vagrant](https://www.vagrantup.com/intro/index.html)
 * [Learn the command line](https://www.codecademy.com/learn/learn-the-command-line) 
 * [Tips & tricks](https://itsfoss.com/linux-command-tricks/)
