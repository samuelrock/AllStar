# AllStar
_______________________________________________________________________________________________

Patches and files to compile AllStar Asterisk on a Debian i386 Platforms.

This is a work in progress that has been forked from N4IRS. The plan is to modify the scripting
to make the installer run under a installation environment that is currently in production and 
not destroy the current system. 

If you are installing from a newly initialized drive you will be required to do a base install 
of debian then run the asterisk installation script here. 

This modified script is geared towards x86 platforms only, Thin Clients are cheaper and 
more powerful than SBCs I see no need for SBCs as controllers. If your looking for SBC 
installations you should use the original scripting and or images from N4IRS.

I started the mods to N4IRS scripting to make custom install files for our link system.
I do not plan on supporting this out side of the Louisiana Link System but if you have a use
for what is posted by all means use it.

K5MOB

_______________________________________________________________________________________________

Quick and dirty:

Download the zip file from the link at the right

cd /tmp

wget --no-check-certificate https://github.com/N4IRS/AllStar/archive/master.zip

apt-get install unzip -y

rm -f AllStar-master

ln -s /srv AllStar-master

unzip master.zip

rm AllStar-master

cd /srv

Copy the platform specific file to /srv

Example: cp platforms/rpi/rpi2/* /srv


login: root	password: debian

Debian Bare Metal x86 installer (Current)

http://tinyurl.com/x86-DIAL

Debian Bare Metal Debian amd64 and i386 installer (Release Candidate)

http://dvswitch.org/files/DIAL/amd64-i386-DIAL-RC1.tar.gz

Alternate:
http://tinyurl.com/amd64-i386-DIAL-RC1


Raspberry Pi 2/3 disk image (Current)

http://tinyurl.com/rpi2-dial-V101

Raspberry Pi 2/3 Raspbian disk image (Release Candidate)

http://dvswitch.org/files/DIAL/RAT_RC1.tar.gz

Alternate:
http://tinyurl.com/DIAL-RAT-RC1


Android IAX Client

https://play.google.com/store/apps/details?id=org.dvswitch

