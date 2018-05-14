# Ubuntu18.04
Setting up everything I need on ubuntu 18.04

# install chrome :
using gdebi

sudo apt install gdebi-core
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo gdebi google-chrome-stable_current_amd64.deb


# install java 8 via ppa
sudo add-apt-repository ppa:webupd8team/java
sudo apt update
sudo apt install oracle-java8-set-default

# install git 
sudo apt -y install git
