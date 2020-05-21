# google
https://google.qwiklabs.com

mac bash error
ls: .: Operation not permitted

# mac command
version catalina
mac version check command 
sw_vers


https://support.apple.com/ja-jp/guide/terminal/welcome/mac

# install command
mac home brew install
 /usr/bin/ruby -e "$(curl -fsSL  https://raw.githubusercontent.com/Homebrew/install/master/install)"  

sudo brew install wget
Error: Running Homebrew as root is extremely dangerous and no longer supported.
As Homebrew does not drop privileges on installation you would be giving all
build scripts full access to your system.

brew install wget
Updating Homebrew...
Error: The following directories are not writable by your user:
/usr/local/bin

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/bin

And make sure that your user has write permission.
  chmod u+w /usr/local/bin

sudo chown -R $(whoami) /usr/local/bin

success
brew install wget
