#Amalgamated hosts file

This is a nice project i came across on hackernews from [Steven Black](https://github.com/StevenBlack/hosts)
 
This repo consolidates several reputable hosts files and merges them into a single amalgamated hosts file with duplicates removed. I didn't know i needed this until i used it. 

Simply clone the project somwhere on your machine 

    git clone https://github.com/StevenBlack/hosts.git 

**Usage:**

You can create a  custom host records, place them in file in `myhosts`. The contents of this file are prepended to the amalgamated hosts file during the update process.

Provide a copy of that new hosts file, and place its update url in `update.info`. The `updateHostsFile.py` routine will automatically refresh the hosts file from source each time a new amalgamated file is generated.

    python updateHostsFile.py

