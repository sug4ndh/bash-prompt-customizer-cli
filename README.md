bash-prompt-customizer-cli
==========================

Bash prompt customizer is a bash program that allows the users to customize their bash prompts by letting them select elements and colors. It also gives a preview of the elements that user has selected. It finally stores the created value of PS1 to ~/.bashrc file, if the user opts to save the generated configuration. On it's first run, it stores the default value of PS1 to ~/.bashrc with which PS1 can be restored to its initial value before running this program.        


###Usage


+ **(Optional)**  Back up your ~/.bashrc file
	```cp ~/.bashrc ~/.bashrc.orig```

+ Clone the repository
	```git clone https://github.com/sug4ndh/bash-prompt-customizer-cli.git```

+ Go inside the 'bash-prompt-customizer-cli' directory and execute the 'bash-prompt-customizer' file inside the 'src' directory.

	E.g. If you have cloned it inside your home directory, this command can be used
	
	*```~/bash-prompt-customizer-cli/src/bash-prompt-customizer```*

+ Finally, after you have saved the configuration, if you are in a terminal then close the terminal and reopen it. However, if you are in tty, logout and log back in and you will have your new prompt. 

Alternatively, you can download the zip file from [here](https://github.com/sug4ndh/bash-prompt-customizer-cli/archive/master.zip). Extract it and then execute the 'bash-prompt-customizer' file inside the 'src' directory.

E.g. If you have downloaded the zip file inside the ~/Downloads directory then run this command

*``` ~/Downloads/bash-prompt-customizer-cli-master/src/bash-prompt-customizer ```*
