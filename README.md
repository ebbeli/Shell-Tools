# Shell Tools

Repository for miscellaneous more or less usefu shell scripts made by me.
You can find these scripts especially useful with Anbernic's handheld consoles. I use them with my RG35xx.
To use any of the scripts run it in directory containing files/folders for processing.

Use "bash scriptName -h / -help" for info if needed.

## cleanNUMs

This script cleans numbers at the start of filenames.
It only cleans numbers if there is one or multiple spaces after them. It also deletes the unnecessary spaces.

Use "bash cleanNUMs -s" to save script's output to "filenames.txt" which is created in the used folder.

## folder2list

Script goes through directory and folders in it.
It makes playlist for each folder's .cue, .ccd & .chd -files.
Each folder gets its own playlist.

## files2folder

Script goes through folder and checks if there is multiple file types with same name"
If found, creates folder using that name and moves matching files into it."

### EXTRA / USE AS COMMAND

If you want to use this as basic command tool wihout using it from directory.

1. Create directory bin to your home folder (Example: "/home/user")
2. Extract directory to created folder. ( At least scripts you want to use.)
   - `cd Shell-Tools`
   - `mv * /home/bin/`
3. Add this PATG to your .profile or .bash_profile
   - `sudo echo 'export PATH=$PATH":$HOME/bin"' >> /home/user/.profile`
4. Sometimes you have to make the file executable again with this command.
   - `chmod +x scriptName`
5. Reload .profile
   - `~/.bash_profile`
6. Now you can use it anywhere with command line with(Remember case sensitivity):
   - `cleanNUMs -h`

Ps. After doing that you can add your own scripts into folder to use as commands. It's convient so you can easily separate them from installed ones.
