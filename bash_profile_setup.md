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

---

####Alias shortcut example for project folder
Adding shortcuts save you lots of typing and time
```bash
reshama 🐘  $ pwd
/Users/reshamashaikh
reshama 🐘  $ ds8
reshama 🐘  $ pwd
/Users/reshamashaikh/_ds/metis/metisgh/nyc16_ds8
```

If I want to go back to my home directory, I can type the alias `home` that I added to my `~/.bash_profile` file  
```bash
reshama 🐘  $ pwd
/Users/reshamashaikh/_ds/metis/metisgh/pygotham-2016
reshama 🐘  $ home
reshama 🐘  $ pwd
/Users/reshamashaikh
reshama 🐘  $ 
```

---

####Removing (or deleting) a file 
Adding `alias rm='rm -i'` to your `bash_profile` includes an added check when deleting a file.   
```bash
reshama 🐘  $ ls *test*
-rw-r--r--  1   0 Jul  5 19:02 testfile.md
reshama 🐘  $ rm testfile.md
remove testfile.md? y
reshama 🐘  $ ls *test*
ls: *test*: No such file or directory
reshama 🐘  $ 
```

---

```bash
reshama 🐘  $ c
-bash: c: command not found
reshama 🐘  $ emacs ~/.bash_profile
reshama 🐘  $ source ~/.bash_profile
reshama 🐘  $ c
```
Typing `c` now clears my console (terminal)  
```
reshama 🐘  $ 
```



###References

[Nate Landau's post: My Mac OSX Bash Profile](https://natelandau.com/my-mac-osx-bash_profile/)
