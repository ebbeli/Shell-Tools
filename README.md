# Shell Tools
Repository for miscellaneous more or less usefu shell scripts made by me. 

## cleanNUMs
This script clean numbers from the beginning of filenames in folder it's been use.
It only cleans numbers if there is on or multiple spaces after them. It also deletes the spaces at the same time.

Use "bash cleanNUMs -h" to get help if needed.

Use "bash cleanNUMs -s" to save script's output to "filenames.txt" in the used folder.

### EXTRA / USE AS COMMAND

If you want to use this as basic command tool wihout using it from directory.

1. Create directory bin to your home folder (Example: "/home/user")
2. Extract directory to created folder. ( At least scripts you want to use.)
   - `cd Shell-Tools`
   - `mv * /home/bin/`
3. Add this PATG to your .profile or .bash_profile
   - `sudo echo 'export PATH=$PATH":$HOME/bin"' >> /home/user/.profile`
4. Reload .profile
   - `~/.bash_profile`
5. Now you can use it at command line with(Remember case sensitivity):
   - `cleanNUMs -h`

Ps. After doing that you can add your own scripts into folder to use as commands. It's convient so you can easily separate them from installed ones.

