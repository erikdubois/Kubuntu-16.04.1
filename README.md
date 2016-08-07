# Kubuntu 16.04.1


We start our journey with a clean install.

Take a look at the various scripts and run the ones you like. Change content if need be.


Some icons we like ...

Using Sardi icons from  http://sourceforge.net/projects/sardi/

![Screenshots]()

![Screenshots]()

![Screenshots]()


or 

using Super Ultra Flat Numix Remix icons from https://github.com/erikdubois/Super-Ultra-Flat-Numix-Remix


#1 Kernel and nvidia

As described at http://erikdubois.be/ I try to get the latest of everything but on a testpc first mind you! This attitude tends to break things. You have been warned. But the best way to learn about linux.

The first time I suggest you follow the steps in the article.

I have written a script to automate my installations. 

You can run any of these scripts by downloading the zip file from github. Go to the download folder and right-click to Extract here.

Go inside the folder and right-click <b>in a blank space</b> to go to the terminal. Now your terminal is opened in this extracted folder.

You have a choice. 

	- kernel 3.x
	- kernel 4.3.x
	- kernel 4.4.x
	- kernel 4.5.x
	- kernel 4.6.x
	- kernel 4.7.x

If you want to install a kernel 3.x or a kernel 4.x, I have to take a different approach for my hardware. Therefor I have split it up in two files.

	- ./update-to-the-last-stable-3.19.8-kernel-vx.sh 
	- ./update-to-the-last-stable-4.6-kernel-vx.sh
 

Do not forget to type "./" in front of the name.


Type in the terminal

	- ./update-to-the-last-stable-3.19.8-kernel-vx.sh 
	
	or 
	
	- ./update-to-the-last-stable-4.6-kernel-vx.sh 


The drivers for your graphic card might well be supported already. So no need to install third party drivers.
Nvidia drivers will <b>NOT</b> be installed as they are very specific to your hardware. But checkout the code.
This code can be uncommented.

	# sudo add-apt-repository -y ppa:xorg-edgers/ppa
	# sudo apt-get update
	# sudo apt-get install nvidia-340 -y (for example)

Check on Nvidia.com which driver you should use.

Some examples of the kernel test.



# kernel 4.6

![Screenshots]()




#2 Software installation

We start the installation script of all the needed software in the same way as above.

	- ./install-all-needed-software-at-once-vx.sh

Do not forget to type "./" in front of the name.

The best of them 

	Spotify
	Sublime Text
	Variety
	Inkscape
	Plank
	Screenfetch
	Numix Icons
	Google Chrome
	...

Or you choose to install the ones you want one by one.




#3 Aureola conky

Conky has changed its configuration to lua syntax.
This will my place to collect them all.

https://github.com/erikdubois/Aureola


![Screenshots]()

![Screenshots]()




Plank
------------------

Plank is NOT implemented here since we have the launcher.

Not sure but I believe Plank was already installed in Ubuntu Mate.

Start plank from the menu. Right-click the plank and choose preferences and put in on top. I choose a transparent theme.
But there are more themes out there if you want.
If you want to autostart this everytime.
Type in the menu " startup". Start startup applications.
Add application and choose plank or do it the old way and point to /usr/bin/plank.

![Screenshots](http://i.imgur.com/arie1IY.jpg)

A tutorial has been written here : 

http://erikdubois.be/install-plank-linux-mint-17-3-set-preferences-add-themes-autostart/




------------------------------------
#But that is the fun in Linux.

You can do whatever <b>Y O U</b> want.

Share the knowledge.
------------------------------------



