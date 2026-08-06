# OverTheWire-Bandit-Writeups
A complete step-by-step documentation and write-up of my solutions for the OverTheWire Bandit wargame, featuring explanations, terminal commands, and screenshots for every level.
## Level 1 -> Level 2

**Goal:** 
Read the password from a file named `-` located in the home directory.

**Commands Used:**
`cat ./-`

**Explanation:**
The `-` character is usually interpreted by commands as standard input (stdin) or standard output (stdout). To read a file named `-`, you have to specify its relative or absolute path so the terminal knows it's a filename.

**Screenshot:**
