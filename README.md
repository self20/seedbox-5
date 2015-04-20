## Seedbox install script for Debian 7/8 64-bit - clean install

#### Not yet ready for production/live server

## Install
Make sure you have sudo installed already. `sudo -V` if not, install: `apt-get install sudo`
First download the script to your machine. The Droplr link will always go to the master branch (install file).
You're welcome to check the redirect yourself. It's a simple URL shortener.
```
# curl
└> curl -L https://d.pr/1kfR4 > install_seedbox

# wget
└> wget -O install_seedbox https://d.pr/1kfR4
```
Then to install
```
sudo ./install_seedbox
```

### My back story
This base script has been put together by me (bbashy) using my knowledge in setting up rTorrent/libTorrent/ruTorrent.
I try to use the latest versions for things, many other scripts use Apache, which is fine... I just prefer Nginx. I run the exact same setup
and it runs perfectly, I seed every version of Mint, Debian, Ubuntu and Arch Linux OSs.

### Notice
I do not know much bash scripting but I'm testing this script heavily so it will be pretty stable. If you see something wrong or a part that
could be done better. Please let me know in the issues or open a pull request fixing it (please explain the problem and how it makes it better).

### Important
I do not take responsibility if this script causes any system errors, loss of data or problems with your server or machine.