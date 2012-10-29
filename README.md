# My DotFiles
These are just my dotfiles.

## Installation
```terminal
git clone git://github.com/HashAv/dotfiles ~/.dotfiles
cd ~/.dotfiles
ruby ./create_symlinks.rb
```

## If push master is not accepted, run
```
git remote set-url origin git@github.com:HashAv/dotfiles.git
```

## CentOS problems
This is needed to clone vundle and install other bundles
```
mkdir ~/certs
curl http://curl.haxx.se/ca/cacert.pem -o ~/certs/cacert.pem
```
Inside ~/.gitignore
```
[http]
sslCAinfo = /home/myUserName/certs/cacert.pem
```
