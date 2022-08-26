# wsl2
## What is WSL?
WSL is a linux kernel running on Windows. WSL stands for Windows System Linux. WSL2 means WSL version 2.<br>
Use following link to know how to install WSL, distributions and setting default version of wsl.<br>
https://docs.microsoft.com/en-us/windows/wsl/install

**Note:** I have used Ubuntu 20.04 distribution which is available in MICROSOFT STORE. You can use your own distribution. Following procedure works on Ubuntu distribution, where as others, not tested.

## To install development tools on ubuntu
`sudo apt update`<br>
`sudo apt install build-essential`

## To run systemd and snap
https://github.com/DamionGans/ubuntu-wsl2-systemd-script <br>

After enabling systemd, snap demon can be run in wsl environment. By default snapd is installed, if not using following to install. <br>
`sudo apt update`<br>
`sudo apt install snapd`<br>

Go through the following link for installation of microk8s using snap <br>
https://microk8s.io/

## To install docker
https://docs.docker.com/engine/install/ubuntu/
