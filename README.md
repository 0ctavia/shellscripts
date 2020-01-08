# Bash Scripts

Repository for small bash scripting projects.

## Initialise

First bash script. This script, when executed, will create a specific file structure often used in our projects throughout the BeCode training.
This script is POSIX compliant.

## Lefthanded

**This script requires xinput to work.**
Second bash script. Having switched to non-GUI I wanted a quick script to modify certain input types (the mouse) to a left-handed mode while leaving others (such as the touchpad) in right-handed mode. 
This script will prompt the user to enable or disable the lefthanded mode on a user-selected input device.

## Reactcomponent

Small script created for and with co-students to initialise React Components.
Many thanks to [Matis](https://github.com/MKaramen) and [Julien](https://github.com/ggbjulien).

## Installing the scripts

These scripts can either be placed in a directory specified in your PATH or can be symlinked. 
As a personal preference, I symlink to /usr/local/bin .

Do not forget to make it executable. 

*Note: create a symlink*

``` ln -s /path/to/original/file /path/to/where/symlink/should/be ```
