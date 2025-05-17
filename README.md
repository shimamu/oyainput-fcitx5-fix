# oyainput-fcitx5-fix
This is a fork of [oyainput](https://github.com/inwskatsube/oyainput), modified to support Fcitx5.  
This project is not intended to replace the original but serves as a workaround for Fcitx5 environments until official support is available.  
I have tested this on Fedora 42.

# oyainput
software to emulate Japanese thum shift keyboard (oyayubi-shift keyboard)


# What is this?
It is software to emulate Japanese thum shift keyboard(oyayubi shift keyboard).  
This is only for Linux, recommend Ubuntu 16.04LTS or Higher.


# How to install
Simply enter commands as follows on terminal to make and install.

    $ make clean; make; sudo make install

If not, You need install gnu make and gcc, to compile.

    $ sudo apt-get install -y make gcc

Note. You must be able to run sudo, or need to be root with su command.


# Usage

    $ oyainput [username]


# Configure
Conig file is made on first run.   
location is  `(Home Dir)/.oyainputconf`


