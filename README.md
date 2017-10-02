# Bash configuration on `earth0` 
This repository contains an example of a `.bashrc` file that will set up your environment on `earth0`. The file can be found in the `scripts` directory of this repository, and can be downloaded by (among other methods) clicking on the file name above, right-clicking the 'Raw' button in the top-right of the file view, and selecting 'Save Link As' (or equivalent).

## What is a `.bashrc` file?
A `.bashrc` file is a shell script that Bash runs every time you start Bash interactively. An example of starting Bash interactively is when you log in to `earth0` using `ssh`:

```
$ ssh USERNAME@earth0.york.ac.uk
```

A `.bashrc` file can contain any commands that you might use at the bash prompt. A typical use for the `.bashrc` file is environment modification, which is what the `.bashrc` file found in this repository is for. You can read more about `.bashrc` files (and other shell initialisation files) [here](http://tldp.org/LDP/Bash-Beginners-Guide/html/sect_03_01.html).

## Using this `.bashrc` file
To use the `.bashrc` file contained within this repository, simply download the file and place it in your `earth0` home directory with the file name `.bashrc`. **NOTE:** performing the following operation will overwrite any existing `.bashrc` in your `earth0` home directory. It is advised to make a copy of your existing `.bashrc` file before installing the `.bashrc` from this repository.

```
$ cd /work/home/USERNAME
$ wget -O .bashrc https://raw.githubusercontent.com/wacl-york/bashrc_earth0/master/scripts/bashrc
```

## Support & Troubleshooting
You can contact me at <killian.murphy@york.ac.uk> in the event of any issues with this `.bashrc`, or if you would like to go through the initial setup and confirm that the `.bashrc` is working correctly.
