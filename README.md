# Nephilim ROM

[<center><img src="https://lh3.googleusercontent.com/-6L7UueFqx8E/AAAAAAAAAAI/AAAAAAAAAA8/skAr5QExCGs/w360-h203-p-rw/photo.jpg" height="40%" width="40%;"/></center>](https://plus.google.com/u/0/communities/104401050580313496153)

Getting Started
---------------

To build Nephilim from source, you'll need to be familiar with
[Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository, use this command:

	repo init -u https://github.com/NephilimRenown/manifest.git -b oreo810-caf

Then to sync source, use this command:

	repo sync

After syncing is done, use these commands to build:

    1.) . build/envsetup.sh
    2.) brunch xxxx yyyy
    
    xxxx= device name aka shamu
    yyyy= build type (user,userdebug,eng)*

    *if no build type is specified "user" is default

    or
   
    . build/envsetup.sh && brunch shamu userdebug

# CAF VERSION INFO AND CREDITS #

Ground Zero Open Source Project 
"Opensource for anyone to use"

Submit your reviews to https://review.gzospgzr.com

Google Plus
https://plus.google.com/communities/109330559573276360638
