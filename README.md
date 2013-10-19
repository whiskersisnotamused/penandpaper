penandpaper
===========

To make contributions to the repo, you'll need a few things.  First, download a VM so you can get ubuntu running.  I'm currently running Ubuntu 12.04, and you can find 
an image of it on the SEMCAT shared drive.  I'm going to run penandpaper on rails v.3.2.13 and ruby 1.8.7, though I may upgrade those to match the dev environment
we're using at SEMCAT.  You will also need to install MySQL, as that's what I'll be using for the database.  It's best to install RVM, and it makes dealing with ruby much easier.

MySQL:
sudo apt-get install mysql-server

RVM:
https://rvm.io/rvm/install

Ruby on Rails:
https://www.digitalocean.com/community/articles/how-to-install-ruby-on-rails-on-ubuntu-12-04-lts-precise-pangolin-with-rvm


You will also need to download Git, and it's helpful to install the Git gui; instructions are at the following link:
https://www.digitalocean.com/community/articles/how-to-install-git-on-ubuntu-12-04


Git commands for making changes to penandpaper:

	To make a copy of this repo on your computer:
	git clone git@github.com:whiskersisnotamused/penandpaper.git

	To switch branches:
	git checkout branchnamegoeshere

	To download the most recent changes for your branch:
	git pull

	To store work you've just done and don't want overwritten by a pull:
	git stash

	To merge the files you just stashed back into your local repo copy:
	git stash pop

	To reset your local copy to what it was when you first pulled it, this is done in case you made changes you want to discard:
	git reset --hard HEAD

As for making commits, it's easiest to use the Git gui, as it'll let you select the files you like and add the commit message there.  So...do that...





