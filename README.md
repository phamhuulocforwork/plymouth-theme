# **BillArch**
An Arch linux splash screen for plymouth
<img src="./preview.gif" alt="billarch-plymouth">

# Manual Installtion
```
$ git clone https://github.com/phamhuulocforwork/plymouth-theme
$ sudo cp -a . /usr/share/plymouth/themes/billarch
```
# Setup
```
# The theme should be listed here
$ sudo plymouth-set-default-theme -l

# Change plymouth theme
$ sudo plymouth-set-default-theme -R billarch
```
