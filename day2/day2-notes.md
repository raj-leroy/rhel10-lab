Day 2 - Understanding man Pages and Linux Help Tools

I learned how to use the built-in Linux help tools today. These tools let me figure out commands and options without using Google. This is important for real production servers that might not have internet access.

I practiced using man, man -k, apropos, whatis, and --help. I worked inside the man pages, learned how to move around, and how to search inside them.

I learned how man pages are organized. Section 1 is for commands, section 5 is for configuration files, and section 8 is for system administration commands. I saw the difference by looking at man 1 passwd and man 5 passwd.

I used apropos and man -k to search for commands when I did not know the command name. I used whatis to get short descriptions. I used --help to get quick summaries.

For the lab:
- pwd shows the current directory
- mkdir -p creates nested directories
- head shows the beginning of a file and defaults to 10 lines
- ls -h shows human readable sizes
- /etc/shadow is documented in section 5 and is the shadowed password file

The main thing I learned today is how to find answers on my own by using the Linux documentation system. This will help me with everything else going forward.

Tomorrow I will move on to more command-line practice.

