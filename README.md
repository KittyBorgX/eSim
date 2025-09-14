eSim Packaging
====

# Installing eSim on Ubuntu 25.04
#### Author: Krishna Ramasimha

> Disclaimer: All the code has been bundled into a zip file located in [Ubuntu-25.04](Ubuntu-25.04/) since there are changes to the `nghdl` package as well which cannot be included in this repository. Instructions for building are noted below.

eSim 2.5 now successfully builds and works on Ubuntu 25.04!

### Installation of the modified version for Ubuntu 25.04:

1. Clone the forked repository and checkout the installers branch:

```
git clone https://github.com/KittyBorgX/eSim.git && cd eSim
git checkout installers
```

2. Move the zip folder to a desired location (just an example given below):

```
mv Ubuntu-25.04/eSim-2.5.zip /home/krishna/
```

3. Unzip the folder and proceed with normal installation:
```
unzip eSim-2.5.zip
cd eSim-2.5
chmod +x install-eSim.sh
./install.sh --install
```

4. Installation should proceed normally and successfully install on Ubuntu 25.04

### Report

A detailed report can be found [here (click this)](Ubuntu-25.04/eSim_25.04_krishna_report.pdf)


# Packaging eSim for Distribution:

It contains all the documentation for packaging eSim for distribution.

1. eSim is currently packaged and distributed for Ubuntu OS (Linux) and MS Windows OS.

2. Refer the [documentation](Version_Change.md) for the changes to be done when a new release is to be made.

> Note: These changes have to be made `first` before proceeding with the packaging on either platform.

3. Refer the [documentation](Ubuntu/README.md) to package eSim for Ubuntu OS.

4. Refer the [documentation](Windows/README.md) to package eSim for Windows OS.
