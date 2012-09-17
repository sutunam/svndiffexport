svndiffexport
=============

A sh script to export changed files between two SVN version

Install
########
wget https://raw.github.com/sutunam/svndiffexport/master/svndiffexport
chmod +x svndiffexport
mv svndiffexport /usr/bin/

Usage
######
svndiffexport [SVN Source path] [Version from witch to start the diff] [Version from witch to end the diff] [target directory]
Example:
svndiffexport /homme/user/source/path 22 HEAD /home/user/exportfolder