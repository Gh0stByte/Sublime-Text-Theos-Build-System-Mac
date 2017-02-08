# Theos Build

Theos Build is made to compile [Theos](http://github.com/theos/theos) projects convinently through Sublime Text.

This Sublime Text Build System supports the following:

- Theos (Full Clean [make clean & delete .theos])
- iPhone Package (Builds Package)
- iPhone Final Package (Builds Final Package)
- iPhone Install (Makes package and installs)
- Simject Install (Makes and installs to simject)
- iPhone Testing Upload (Uploads a debug package to dropbox)*
- iPhone Release Upload (Uploads a final package to dropbox)*
- Delete Last Package (Deletes last compiled package)

## Installation

- Clone repo
- Copy `Theos.sublime-build` to `~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/`
- Select Theos as build system in Sublime Text

Note: 
- To use Simject Install you will need the following file in your project folder:
  - [Simject](simject.sh) and change the YourProjectName to the projet name
- To use the Uploading configurations you will need dropbox_uploader
  - Download it from [Here](https://github.com/andreafabrizi/Dropbox-Uploader) and copy it to `/usr/bin` after you set it up

