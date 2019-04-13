# Apex-config   

In the top my sensitivity and some other binds are bound. You might want to change that.   

videoconfig.txt location   
`C:\Users\[usr name]\Saved Games\Respawn\Apex\local`   

autoexec.cfg location   
`C:\Program Files (x86)\Origin Games\Apex\cfg`   
    
Due to some bug game wont start with commands in launch options any more. So we need to load it in another way.   
in `C:\Users\[usr name]\Saved Games\Respawn\Apex\local\settings.cfg` add `exec userconfig.cfg` and make it read only   

## Playing 4:3 stretched ##
You need to change resolution in game to be able to play without black bars (top/bot).   
Make sure you enable full-screen scaling mode in Nvidia settings.


## Nvidia profiles ##
### Performance profile ###
apex-performance-profile.nip

### SLI Profile + Performance profile ###
apex-sli-and-performance-profile.nip

### Load with ####
[nvidiaProfileInspector](https://github.com/Orbmu2k/nvidiaProfileInspector/releases)

##To-do##
* Adding all available commands to autoexec.cfg
* Removing all commands that isn't part of apex.
* Commenting all default values
* Commenting all descriptions (if available)
* Creating a default config with all default values to reset all settings.
* Split out all Performance commands to its own file.
