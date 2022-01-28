# Supercharged bashrc

Colored bashrc for linux

Features:
* Git branch hinting when your current path is in git project
* Full colored terminal with better reading scheme
* Next line commands ( after line with `user@path(branch)` )

## How to install

To replace your current bash simply run:

for root
```
wget  -O /root/.bashrc "https://raw.githubusercontent.com/vichaunter/bashrc/master/bashrc"
```
or for your user
```
wget  -O /home/${USER}/.bashrc "https://raw.githubusercontent.com/vichaunter/bashrc/master/bashrc"
```

after download just execute exec to apply changes
```
exec bash
```

Enjoy!

## Troubleshooting

If you receive an error `__git_ps1: command not found` just install git
```
sudo apt install git
```
