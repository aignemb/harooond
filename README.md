Harpoon for Directories

Created by aignemb and inspired by harpoon by ThePrimeagen 
    (https://github.com/ThePrimeagen/harpoon)

Used to dynamically assign an alias to a directory for quick terminal navigation.

Setup:
* Clone this repository to any directory 
    - I use $HOME/.config

* Add these lines to your sheel config file (e.g. .zshrc)
    HPD_PATH="<path to directory where you cloned repository"
    source $HPD_PATH/hpd_init

* Change #!/bin/zsh to your reflect your shell of choice in all executable files
    - I am hoping to change this to be done automatically in the future

* Set up aliases as you wish by changing HPD_HK# inside of the hpd_data file
    - By default they are set to a, s, and f
    - If you want to change these I suggest double checking that they are not
      already used

Use:
* To add an alias to the current working directory, type
    <alias> -a 
    - Note that the alias must already be configured in hpd_data
    - As noted above, pre-configured aliases are a, s, and f

* To navigate back to that directory from anywhere, type
    <alias><enter>

* To display currently harpooned directories, type one of the following
    harpoond
    hpd # default alias
    <custom alias> # can be configured in hpd_data file
     
Notes:
* I welcome any comments to suggestions!
