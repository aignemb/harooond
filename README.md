Harpoon for Directories

Created by aignemb and inspired by harpoon by ThePrimeagen 
    (https://github.com/ThePrimeagen/harpoon)

Used to dynamically assign an alias to a directory for quick terminal navigation.

Setup:
* clone this repository to any directory 
    - I use $HOME/.config

* add these lines to your sheel config file (e.g. .zshrc)
    HPD_PATH="<path to directory where you cloned repository"
    source $HPD_PATH/hpd_init

* set up aliases as you wish by changing HPD_HK# inside of the hpd_data file
    - by default they are set to a, s, and f
    - if you want to change these I suggest double checking that they are not
      already used

Use:
* to add an alias to the current working directory, type
    <alias> -a 
    - note that the alias must already be configured in hpd_data

* to navigate back to that directory from anywhere, type
    <alias> 

* to display currently harpooned directories, type on of the following
    harpoond
    hpd # default alias
    <custom alias> # can be configured in hpd_data file
