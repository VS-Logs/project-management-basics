# LINUX Commands

<br/>

## File Commands

|Sl.No.| Commands    | Description              |
|------|-------------|--------------------------|
|  01.  |ls         | directory listing|
|  02.  |ls -al     | formatted listing with hidden files|
|  03.  |cd dir     |change directory to dir|
|  04.  |cd         | change to home|
|  05.  |pwd        | show current directory|
|  06.  |mkdir dir  | create a directory dir|
|  07.  |rm file    | delete file|
|  08.  |rm -r dir  | delete directory dir|
|  09.  |rm -f file | force remove file|
|  10.  |rm -rf dir | force remove directory dir *|
|  11.  |cp file1 file2 | copy file1 to file2|
|  12.  |cp -r dir1 dir2 | copy dir1 to dir2; create dir2 if it doesn't exist|
|  13.  |mv file1 file2 | rename or move file1 to file2 if file2 is an existing directory, moves file1 into directory file2|
|  14.  |ln -s file link | create symbolic link link to file|
|  15.  |touch file | create or update file|
|  16.  |cat > file | places standard input into file|
|  17.  |more file  | output the contents of file|
|  18.  |head file  | output the first 10 lines of file|
|  19.  |tail file  | output the last 10 lines of file|
|  20.  |tail -f file | output the contents of file as it grows, starting with the last 10 lines|

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Process Management

|Sl.No.| Commands    | Description              |
|------|-------------|--------------------------|
|  01. |ps | display your currently active processes|
|  02. |top | display all running processes|
|  03. |kill pid | kill process id pid|
|  04. |killall proc | kill all processes named proc *|
|  05. |bg | lists stopped or background jobs; resume a stopped job in the background|
|  06. |fg | brings the most recent job to foreground|
|  07. |fg n | brings job n to the foreground|

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## File Permissions

* chmod octal file – change the permissions of file to octal, which can be found separately for user, group, and world by adding
* 4 – read (r)
* 2 – write (w)
* 1 – execute (x)

### Examples

* `chmod 777` – read, write, execute for all
* `chmod 755` – rwx for owner, rx for group and world

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## SSH

* ssh user@host – connect to host as user
* ssh -p port user@host – connect to host on port port as user
* ssh-copy-id user@host – add your key to host for user to enable a keyed or passwordless login

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Searching

* grep pattern files – search for pattern in files
* grep -r pattern dir – search recursively for pattern in dir
* command | grep pattern – search for pattern in the output of command
* locate file – find all instances of file

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## System Info

|Sl.No.| Commands    | Description              |
|------|-------------|--------------------------|
|  01. |date | show the current date and time|
|  02. |cal | show this month's calendar|
|  03. |uptime | show current uptime|
|  04. |w | display who is online|
|  05. |whoami | who you are logged in as|
|  06. |finger user | display information about user|
|  07. |uname -a | show kernel information|
|  08. |cat /proc/cpuinfo | cpu information|
|  09. |cat /proc/meminfo | memory information|
|  10. |man command | show the manual for command|
|  11. |df | show disk usage|
|  12. |du | show directory space usage|
|  13. |free | show memory and swap usage|
|  14. |whereis app | show possible locations of app|
|  15. |which app | show which app will be run by default|

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Compression

|Sl.No.| Commands    | Description              |
|------|-------------|--------------------------|
|  01. |tar cf file.tar files | create a tar named file.tar containing files
|  02. |tar xf file.tar | extract the files from file.tar
|  03. |tar czf file.tar.gz files | create a tar with Gzip compression
|  04. |tar xzf file.tar.gz | extract a tar using Gzip
|  05. |tar cjf file.tar.bz2 | create a tar with Bzip2 compression
|  06. |tar xjf file.tar.bz2 | extract a tar using Bzip2
|  07. |gzip file | compresses file and renames it to file.gz
|  08. |gzip -d file.gz | decompresses file.gz back to file

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Network

* ping host – ping host and output results
* whois domain – get whois information for domain
* dig domain – get DNS information for domain
* dig -x host – reverse lookup host
* wget file – download file
* wget -c file – continue a stopped download

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Installation

* dpkg -i pkg.deb – install a package (Debian)
* rpm -Uvh pkg.rpm – install a package (RPM)

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Install from source

* ./configure
* make
* make install

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Shortcuts

* Ctrl+C – halts the current command
* Ctrl+Z – stops the current command, resume with
* fg in the foreground or bg in the background
* Ctrl+D – log out of current session, similar to exit
* Ctrl+W – erases one word in the current line
* Ctrl+U – erases the whole line
* Ctrl+R – type to bring up a recent command
* !! - repeats the last command
* exit – log out of current session

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

### List of Basic SSH Commands

|Sl.No.| Commands    | Description                                      |
|------|-------------|--------------------------------------------------|
| 01.  |ls	         |Show directory contents (list the names of files).|
| 02.  |ls -a        |List all files in a directory|
| 03.  |ls -h        |List files along with file sizes|
| 04.  |ls *.html    |list all files ending in .html|
| 05.  |cd	         |Change directory (e.g. cd /var/www will put you in the www directory)|
| 06.  |cd ~         |Go to the home folder|
| 07.  |cd /         |Go to the root directory|
| 08.  |cd -         |Go to the previous directory|
| 09.  |cd ..        |Move up one directory|
| 10.  |mkdir	     |Create a new folder (e.g. mkdir myfoldername)|
| 11.  |touch	     |Create a new file.|
| 12.  |rm	         |Delete a file (e.g. rm filename.html)|
| 13.  |rmdir        |Delete a folder (e.g. rmdir foldername)|
| 14.  |cat	         |Show the contents of a file (e.g. cat filename.html)|
| 15.  |pwd	         |Show current directory (full path to where you are right now).|
| 16.  |cp	         |Copy a file (e.g. cp index.html /mydirectory/index.html)|
| 17.  |mv	         |Move a file (e.g. mv index.html /mydirectory/index.html)|
| 18.  |grep	     |Search for a string (e.g. grep "word" index.html). Searches for “word” in the index.html file|
| 19.  |find	     |Search files and directories.|
| 20.  |vi/nano	     |Text editors.|
| 21.  |history	     |Show last 50 used commands.|
| 22.  |clear	     |Clear the terminal screen.|
| 23.  |tar	         |Create & Unpack compressed archives.|
| 24.  |wget	     |Download files and store them in your current directory (e.g. wget https://website.com/filename.ext)|
| 25.  |du	         |Get file size.|
| 26.  |vim          |Open or create a file with the Vim text editor (e.g. vim filename.html).|
| 28.  |nano         |Open or create a file with the nano text editor (e.g. nano filename.html)|
| 29.  |zip          |Compress a folder (e.g. zip -r folder.zip folder). Takes “folder” and compresses it as a file called “folder.zip”|
| 30.  |unzip        |Decompresses a folder (e.g. unzip folder.zip)
| 31.  |chmod        |Change a file’s permissions (e.g. chmod 604 folder). Use this Unix permissions calculator to determine which chmod command you should be using|
| 32.  |netstat      |Display network connections|
| 33.  |free-m       |Display your machine’s current memory usage|
| 34.  |exit         |Exit the remote server and return to your local machine SSH Keys|
| 35.  |cat filename.txt        | cat the contents of filename.txt to your screen|
| 36.  |tail                    |like cat, but only reads the end of the file|
| 37.  |tail /var/log/messages      |see the last 20 (by default) lines of /var/log/message|s|
| 38.  |tail -f /var/log/messages   |watch the file continuously, while it's being updat|ed|
| 39.  |tail -200 /var/log/messages |print the last 200 lines of the file to the screen|
| 40.  |more                        |like cat, but opens the file one screen at a time rather than all at once|
| 41.  |more /etc/userdomains       |browse through the userdomains file.|
| 42.  |pico                        |friendly, easy to use file editor|
| 43.  |pico /home/burst/public_html/index.html | edit the index page for the user's website.|
| 44.  |vi                          |another editor, tons of features|
| 45.  |vi /home/burst/public_html/index.html | edit the index page for the user's website.|
| 46.  |grep root /etc/passwd | shows all matches of root in /etc/passwd|
| 47.  |grep -v root /etc/passwd | shows all lines that do not match root|
| 48.  |touch /home/burst/public_html/404.html | create an empty file called 404.html in the directory /home/burst/public_html/|
| 49.  |ln | create's "links" between files and directories|
| 50.  |ln -s /home/username/tmp/webalizer webstats | Now you can display http://www.yourdomain.com/webstats to show your webalizer stats online. You can delete the symlink (webstats) and it will not delete the original stats on the server.|
| 51.  |rm filename.txt | deletes filename.txt, will more than likely ask if you really want to delete it|
| 52.  |rm -f filename.txt | deletes filename.txt, will not ask for confirmation before deleting.|
| 53.  |rm -rf tmp/ | recursively deletes the directory tmp, and all files in it, including subdirectories.|
| 54.  |last | shows who logged in and when|
| 55.  |last -20 | shows only the last 20 logins|
| 56.  |last -20 -a | shows last 20 logins, with the hostname in the last field|
| 57.  |w | shows who is currently logged in and where they are logged in from.|
| 58.  |netstat | shows all current network connections.|
| 59.  |netstat -an | shows all connections to the server, the source and destination ips and ports.|
| 60.  |netstat -rn | shows routing table for all ips bound to the server.|
| 61.  |top | shows live system processes in a nice table, memory information, uptime and other useful info.|
| 62.  |ps | ps is short for process status, which is similar to the top command. It's used to show currently running processes and their PID.|
| 63.  |ps U username | shows processes for a certain user|
| 64.  |ps aux | shows all system processes|
| 65.  |ps aux --forest | shows all system processes like the above but organizes in a hierarchy that's very useful!|
| 66.  |file | attempts to guess what type of file a file is by looking at it's content.|
| 67.  |file * | prints out a list of all files/directories in a directory|
| 68.  |du | shows disk usage.|
| 69.  |du -sh | shows a summary, in human-readble form, of total disk space used in the current directory, including subdirectories.|
| 70.  |du -sh * | same thing, but for each file and directory. helpful when finding large files taking up space.|
| 71.  |wc | word count|
| 72.  |wc -l filename.txt | tells how many lines are in filename.txt|
| 73.  |cp filename filename.backup | copies filename to filename.backup|
| 74.  |cp -a /home/burst/new_design/* /home/burst/public_html/ | copies all files, retaining permissions form one directory to another.|
| 75.  |find * -type d|xargs -i cp --verbose php.ini {} | copies your php.ini file into all directories recursively.|
| 76.  |kill | terminate a system process|
| 77.  |kill -9 PID EG | kill -9 431|
| 78.  |kill PID EG | kill 10550|

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>