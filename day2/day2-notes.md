Day 2 — Understanding man Pages and Linux Help Tools
====================================================

Overview
--------
Today I practiced using the built-in Linux help tools that sysadmins use on real servers.
These tools allow me to learn commands, understand options, and troubleshoot systems even
when I do not have internet access.

Tools I used today:
- man
- man -k
- apropos
- whatis
- command --help

These skills are essential for Linux system administration, cybersecurity, and cloud roles.

What I Learned
--------------

1. How to Read man Pages
I learned the structure of a man page:
- NAME
- SYNOPSIS
- DESCRIPTION
- OPTIONS
- EXAMPLES

Navigation keys:
- Space: page down
- Enter: line down
- b: page up
- /text: search
- n: next match
- q: quit

2. Finding Commands When I Do Not Know the Name
I used these tools to search by keyword:
- apropos <keyword>
- man -k <keyword>
- whatis <command>

3. When to Use --help
--help gives a quick summary and list of options.
man gives full documentation and examples.

Example:
ls --help | head -5

4. Understanding man Sections
I learned why commands and files appear in different manual sections:
- Section 1: user commands
- Section 5: configuration files
- Section 8: administrative commands

Example:
man 1 passwd  -> command
man 5 passwd  -> file format

Day 2 Lab — Answers
--------------------

Task 1: Find command to show current directory
- Command: pwd
- Section: 1
- Description: print name of current/working directory

Task 2: Find the flag that creates nested directories
- Command: mkdir
- Flag: -p
- Description: create parent directories as needed

Task 3: Find command that shows the beginning of a file
- Command: head
- Default lines: 10
- How I found it: man head

Task 4: Find ls flag for human-readable file sizes
- Flag: -h
- Meaning: show sizes like 1K, 234M, 2G

Task 5: Identify man section for /etc/shadow
- Section: 5
- Description: shadowed password file

Key Takeaways
-------------
- Linux includes powerful documentation tools.
- man pages are critical for sysadmins and security professionals.
- I am getting more comfortable finding answers without guessing.
- Understanding man sections helps me interpret documentation quickly.
- These skills will help later with services, networking, permissions, and security.

Next Steps
----------
On Day 3 I will continue building core command-line skills and practice real-world tasks.
