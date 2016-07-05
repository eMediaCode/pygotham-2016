##Set up `bash_profile`
The bash profile contains global options.  Here we will set up some shortcuts to save on typing.  


####Access bash_profile
This file is located in your home directory.  
To access it, use any editor of your choice.
```
$ emacs ~/.bash_profile
```

####Add these options

```bash
alias ls='ls -lGgo'
alias rm='rm -i'
alias home="cd /Users/reshamashaikh"
alias ds8="cd /Users/reshamashaikh/_ds/metis/metisgh/nyc16_ds8"
alias server="python -m SimpleHTTPServer"

```

####Alias example for project folder
```
reshama 🐘  $ pwd
/Users/reshamashaikh
reshama 🐘  $ ds8
reshama 🐘  $ pwd
/Users/reshamashaikh/_ds/metis/metisgh/nyc16_ds8
```
 
####Removing (or deleting) a File 


