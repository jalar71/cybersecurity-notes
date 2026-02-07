# Linux Fundamentals
---
The name "Linux" is actually an umbrella for multiple operating systems that are based on UNIX(another operatin system). Thanks to Linux being open-source, variants of Linux come in all shapes and sizes customized for the purpose of the system is being used for. \
Linux Commands 
| Commands | Description|
|:---|:---|
|`echo`| Output any text that we provide|
|`whoami`| What user we're currently logged in as|
|`ls -a`| List the contect (`-a` flag is used to show the hidden files as well.)|
|`cd`| Change Directory|
|`cat`|Concatenate|
|`pwd`|Present Working Directory |
|`find`| the name says it all|
|`wc`| Word count |
|`grep`| Search in the file for a word or text|
### Let's Take a look at how `find` could be used
If we know the filename, we can simply use 
```bash
find -name passwords.txt
```
This command will go through every folder in the current directory for that file.
Next if you want to look for all the files which have the `.txt` extension
```bash
find -name *.txt
```
