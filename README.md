## Using Git for ASNA AVR Coders

This repository contains the associated files and other collateral that accompanies the ASNA Using Git for AVR Coders video series.


##### Put these files in your `c:\users\<yourname>` folder.

	.bash_profile
	.bashsrc
	.gitconfig

`.bash_profile` launches the `.bashsrc` file. This `.bashsrc` file launches the SSH agent so you'll only be asked for the SSH key once when staring a Bash shell.

`.gitconfig` provides Git with configuration info. This file assumes you've installed WinMerge and SourceTree. It also provides several handy Git command aliases.  

##### Create a `bin` folder in your `c:\users\<yourname>` folder and put these files there: 

	.gitignore 
	my-git-init 

By default, the `c:\users\<yourname>\bin` in the Bash shell's path statement. `my-git-init` is a Bash shell command that copies the `.gitignore` to the current folder and then does `git init` to initialize a repository. 

To use `my-git-init`, navigate with Windows File Explorer to a folder that you want to put in Git source control. The right-click and select `Git Bash here`. In the Bash shell presented, type `my-git-init`. That copies in the `.gitignore` file into the folder and initializes a new Git repo there.      

##### The PowerPoint file is the PowerPoint used in the videos.  
