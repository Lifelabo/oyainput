# oyainput-fcitx5-backspace-colon-swap
This is a fork of [yq0810/oyainput](https://github.com/yq0810/oyainput), which is a fork of the original [inwskatsube/oyainput](https://github.com/inwskatsube/oyainput), modified to support Fcitx5.
This project has the following features:
(1) supports fcitx5
(2) swaps backspace key and colon key even when ime is off.
(3) added KUTOUTENKAKUTEI item on .oyainputconf. When KUTOUTENKAKUTEI=TRUE, oyainput outputs Ctrl+M after kuten and touten.
  
This project is not intended to replace the original.  
I have tested this on MX Linux 25.

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


