#slopymf
A simple Python 3 command-line screenshot tool for pomf.se, based on [pymf](https://github.com/savoca/pymf) using slop and maim. 

##Requirements
* python-requests (python3)
* pyperclip (python3)
* slop
* maim
* xclip

##Obtaining requirements
###pyperclip and requests
In most cases, requests comes by default with Python 3. However, both can be installed using pip.

    pip install requests
    pip install pyperclip

###slop and maim
Depending on your distribution, slop and maim may be obtained via the package manager. Failing that, both [slop](https://github.com/naelstrof/slop) and [maim](https://github.com/naelstrof/maim) can be built from source.

###xclip
xclip is available in pretty much every package manager. for a debian-based system,

    sudo apt-get install xclip

##Usage
Place slopymf in the same directory as pymfconfig. Execute slopymf, and select the region to capture. A link to your screenshot will be placed in your clipboard. 
