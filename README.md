# ptf-prep
A bash script to prep a clean, minimal install of Ubuntu with the base packages and programs for running the PenTesters Toolkit

Note for installing wifipumpkin3:
wifipumpkin3 installer requires python3.7, however this is a deprecated version. To install with a version of python3 >= 3.7 already installed (what this script will install by default), simply making a symbolic link for python3.7 pointed to python3 will suffice.
If you plan to install wifipumpkin3, uncomment line 88 (in the section "Mapping python3.7 to python3") to create this symlink. 

Known bugs
--------------------
The current version of this script is still unable to resolve installation issues with airpwn-ng and peanuts. The rest of the wireless modules appear to install successfully.


