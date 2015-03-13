# tv-player
Script to play videos from trollvids without flash

This is a very badly coded script that will hopefully make it easier for me to keep track of the changes that I do to it.

It helps to make the script executable, placing it in $HOME/bin, or in your $PATH. You don't really need the .sh extension but you can add it if you want.

Requirements:
	-mpv with networking support(ffmpeg with networking)
	-youtube-dl
	-everything else should be on a default linux install
	-bash
	-echo
	-grep
	-sed
	-touch
	-wget

Uses:
	./tv-player URL
	./tv-player -h
	./tv-player -d URL
	or
	tv-player URL
	tv-player -h
	tv-player -d URL

Errors:
Currently, the script should tell you if something went wrong and exit.
I think the most obvious error or problem that the script might have is searching specifically for docs.google.com or drive.google.com. I'll get around to fixing that later.

To-Do:
I want to add the option to get low quality videos. Currently, the script will get only HD and use LD as a fallback. I also want to add a way to add a custom PATH and custom youtube-dl options.

Finally, chances are, if you could compile/install mpv and youtube-dl, you can probably handle a script like this. I'll try rewriting or cleaning the code and not have so many temporary files created.

Any help, comments, or jokes(CS Grad) are appreaciated.
