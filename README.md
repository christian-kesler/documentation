# documentation
## Git setup

    git init
    git branch -m main
    
    git config --global user.name "someone@example.com"
    git config --global user.email "Some Name"
    
    git config credential.helper 'store'

## Debian (ubuntu) - tar.xz Extraction and Install

        tar -xf ${file}
        
        mv ${folder} ${path}{$folder}
        
        sudo unlink node
        ln -s node-v0.10.7-linux-x86 node
        
        vim ~/.profile
        
Inside VIM, bottom of file

        PATH=$PATH:$HOME/programs/node/bin
        
## WoeUSB Installation (Ubuntu 22.04 | With GUI)
https://www.youtube.com/watch?v=jGeRysEDgGE

    sudo add-apt-repository ppa:tomtomtom/woeusb -y
    sudo apt update
    sudo apt install woeusb woeusb-frontend-wxgtk -y

## WoeUSB Create Windows Bootable USB (Terminal)

        sudo ./woeusb-5.2.4.bash --device ./Win10_21H2_English_x64.iso /dev/sdb
        
Likely Error - Target media device is budy

Go into Disks app, find media disk, unmount, try again


## Reinstall Ubuntu Settings App

        sudo apt install gnome-control-center
        

## Podman install and setup

        sudo apt install podman
        alias docker=podman

## Podman container IP inspection

        podman inspect <id-or-name> |grep IPAddress

## Bootable Windows USB on Linux

https://itsfoss.com/bootable-windows-usb-linux/
