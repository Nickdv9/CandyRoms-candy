Welcome to CandyRoms
===================


Getting Started
---------------

To get started with Candy7.1.2, you'll need to get familiar with
[Git and Repo](http://source.android.com/download/using-repo).

Please take note that we have two main line branches depending on
which hardware base your phone is working.

To initialize your local repository using the Candy7.1.2 trees, use this command:


	repo init -u git://github.com/CandyRoms/candy.git -b c7.1.2



Then sync up with this command:

	repo sync

To start your build run this command:

	. build/envsetup.sh && breakfast <device> && make -j8 candy

Gerrit 
------
We now have a gerrit. Please use it if you want your code to be reviewed.

URL : https://gerrit.bbqdroid.org

A great guide to using gerrit: http://forum.xda-developers.com/showthread.php?t=2628545
