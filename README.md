#slopymf
A simple Python 3 command-line screenshot tool for pomf.se, based on [pymf](https://github.com/savoca/pymf) using slop and maim. 

##Requirements
* python-requests (python3)
* slop
* maim
* xclip

##Obtaining requirements
###requests
In most cases, requests comes by default with Python 3. However, if not it can be installed using pip.

    pip install requests

###slop and maim
Depending on your distribution, slop and maim may be obtained via the package manager. Failing that, both [slop](https://github.com/naelstrof/slop) and [maim](https://github.com/naelstrof/maim) can be built from source.

###xclip (for clipboard output)
xclip is available in pretty much every package manager. for a debian-based system,

    sudo apt-get install xclip

##Usage
Place slopymf in the same directory as pymfconfig. Slopymf will output the file url to stdout. For example, execute

    python3 slopymf | xclip -selection c
to upload your screenshot and output the URL to your clipboard.
