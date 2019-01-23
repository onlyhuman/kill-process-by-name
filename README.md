# kill-process-by-name
A small script that searches for running process's PID and kills all its sub-processes.
The **propose** of this script is to automate the killing of a process tree (e.g. via crontab) if you are not want to run a script any more but it hangs other users doing their work, like when your script is modifing a DB but after 4PM you don't watch for the DB changes bot your other colleagues cannot run the same script. 
## Usage
killPTByName firefox
