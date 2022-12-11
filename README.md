# xampp

<!-- XAMP: For Linux and Android --->

<p align="center">
  <img src="https://img.shields.io/badge/Version-v1.0-red?style=for-the-badge">
  <img src="https://img.shields.io/github/license/AdarshAddee/XAMP?style=for-the-badge">
  <img src="https://img.shields.io/badge/poisk-ls-red?style=flat-square">
  <img src="https://img.shields.io/badge/Written%20In-Bash-darkcyan?style=flat-square">
</p>

<p align="center">
  <b>XAMPP - Server For Android..</b>
</p>

##

# XAMPP
XAMPP is a begginer friendly server for android which host(s) localhost(s) on android devices. <b>New feature for LINUX available after some time (Working on it!).</b> You can use this tool to start local server on android. After successfully executing tool, Just open <b>localhost:8080</b> to see your web page which is hosted on local server. 

## Features
- Begginer Friendly
- Supports CLI and GUI Mode
- Supports Multiple Servers
  - PHP
  - Python
  - Mysql
  - Apache2
  - Nginx

## Installation 
These are the following commands which can be used to install XAMP Serevr in Android (Termux).
- Install step-by-step!
  ```
  apt update && apt upgrade -y
  ```
  ```
  apt install git -y
  ```
  ```
  git clone https://github.com/poisk-ls/XAMPP.git
  ```
  
- **One Line Installion..**
- apt update && apt upgrade -y && apt install git -y && git clone https://github.com/poisk-ls/XAMPP.git
  
## Execution
These are the commands which can be used to execute XAMPP Serevr in Android (Termux).
- cd XAMPP
- chmod 777 xampp

>**(run)**
>- xampp

## Modes
XAMPP - Server Supports GUI & CLI Mode as Well!
- ### GUI Mode!
  XAMPP - Server in GUI Mode can be started with:
- ./xampp

- ### CLI Mode!
  XAMPP - Server  in CLI Mode have some arguments!
  ```
  ./xampp [args]
  ```
  
  Open xamp help page
  - ./xampp -h
  
  Here are some commands which can be used:
  ```
  usage: xampp [args]
  
  args:
    -h, --help            show help and exit
    -b, --banner          show banner and exit
    -py, --pyserver       start python server
    -php, --phpserver     start php server
    -ap2, --apache2       start apache2 server
    -ng, --nginx          start nginx server
    -v, --version         show version and exit
    
  stop service:
    -s, --stop            stop serving localhost service
  ```

<!--

<p align="center"><b>Open XAMPP in Cloud Shell</b></p>
<p align="center">
  <a href="https://shell.cloud.google.com/cloudshell/open?cloudshell_git_repo=https://github.com/AdarshAddee/XAMP.git&tutorial=README.md" target="_blank"><img src="https://gstatic.com/cloudssh/images/open-btn.svg"></a>
</p>

-->

## Dependencies
These are the following dependencies which are used by XAMP!
- PHP
- Python
- Mariadb
- Apache2
- Nginx

All these dependencies are going to install automatically when you run <b>xamp</b> server for the first time.

## Message 
You can use xampp server without using ``./`` also. As this may help you to start services more faster.

#
<p align="center"><b>pwd</b></p>

**/data/data/com.termux/files/usr/share/apache2/default-site/htdocs**
#




