# xskulker
The tool "xskulker" has been designed as a replacement for the skulker script to remove files and also old empty directories from a USS directory structure. The routine is written in REXX completely and exploits USS APIs. This should provide a better performance over the original script. It can be used efficiently in a z/OS UNIX sysplex sharing environment and only if the file system(s) containing the files is/are owned locally are searched for candidates to get deleted.
