ShadowDukeInstaller
===================

Installation and updates for ShadowDukes Server setup

Based on ShadowDuke's 2.5 DayZ/Lingor Server

I created a install that lets you play either or by clicking on the link on the desktop or startmenu. 
uninstall support as well. THIS INSTALLER WILL OVERWRITE YOUR OLD DATABASE!  NOTES ON HOW TO INSTALL AND KEEP YOUR DATA 
AT THE BOTTOM OF THE README

Don't forget to grab the files from dayzmod and the files for lingor island. links can be found here
http://www.tunngle.net/community/topic/85461-dayz-1726-saintly-lingor-island-v034-server-files/

What is the installer?
Basically it is ShadowDuke's Saintly Server (https://github.com/ShadowDuke/Saintly-DayZ) files just packed up for people
who r non developers just to install and get to playing.

what does it do?
The installer gives you the option to install .net to 4.5 and install Microsoft Visual C++ 2010  x86 Redistributable.
Once it does that, it ask for your arma 2 operation arrowhead directory and installs all the files to that directory 
and runs the registry fix.  
Upon completion of the installation it brings you directly to the server tools window.
Here you can edit your config files to personalize your servers, update battleye scripts, run the servers, and reinstall
the databases if you feel the need to.  
The installer places 3 files on your desktop.  one to run lingor server, dayz server, and one for the server tools.  
You can only run one server at a time.  If you try to run two it will automatically kill the currently running server 
before it runs the new one.  
The install also places these files in your start menu and places an uninstall option under add/remove programs.  
 
 I thoroughly tested the file due to being an insomniac :)
 
 If you do encounter any issues please let me know asap so i can fix it and update it.  I'll roll out update when dayz or
 lingor island put out an update.  Don't expect on before then unless something big is fixed or added.
 
 These are original files and any alterations to them I can't really support but the forums are good for that.  
 
 Want to install and keep your old data?  back up the folder server_setup\xammp\mysql\data.
 run installer.
 if your data is from lingor place the data folder in server_setup\xammp\mysql\
 if your data is from dayz place the data folder in server_setup\xammp2\mysql\