Welcome to aur-install
----
A simple, one-command AUR package installer for arch linux. Simply type
 > aur-install <package_name>
 
 just the way you do with `pacman` and you're done! The script handles dependecy checks, so just follow the on-screen prompts the way you'd do with pacman.
<br/>

Installation
----
Navigate to the `aur-install` directory in the terminal (or open the terminal in that directory from your file manager) and type:

 > sudo chmod u+x ./install-a-i.sh  
 > sudo ./install-a-i.sh
 
The installer script places the `aur-install` script in to your `/usr/bin` folder and makes it readable/writeable by all users, so it can be invoked from any directory.
 
Running
----
<b>DO NOT RUN `aur-install` AS `sudo`</b>. Just type in

 > aur-install <package_name>
 
 License
 ----
 aur-install is licenced under the terms of the MIT License as of the time you're reading this sentence.
