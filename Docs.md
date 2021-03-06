<p>
    <h2>Cron Job</h2>
    <ul>
        <li>Description: A cron job is a automated servvice in linux that you can use to run a script in schedule, Moreover you can notiy someone using email/sendmail</ul>
        <li>Usage: crontab -e  [to edit user's crontab]</li>
        <li>Values provided for [m h  dom mon dow   command] (minute (m), hour (h), day of month (dom), month (mon), and day of week (dow))</li>
        <li>You might need to add yourself to the crontab user group using: usermod -a -G crontab (username)</li>
    </ul>
</p>

<p>
    <h2>Extra Notes</h2>
    <ul>
        <li>/etc/passwd contains users registerd on the system which can perform actions and have a shell assosciated to them</li>
        <li>There are 7 file types in linux</li>
        <li>Log directory: /var/log</li>
        <li>Types of logs: boot, chronyd, cron, maillog, secure, messages, httpd</li>
    </ul>
</p>

<p>
    <h2>Commands</h2>
    <ul>
        <li>scp: Command to securely transfer files between servers "scp [OPTION] [user@]SRC_HOST:]file1 [user@]DEST_HOST:]file2</li>
        <li>last: lists users who had logged in earlier</li>
        <li>awk: returns particular columns</li>
        <li>To log a message to the syslog: logger -t error "Hey therea"</li>
        <li>To run a command in the background you use nohup and &</li>
        <li>In conditions, if the variable will ahve a digit or integer value we use -eq, for charachters we use == </li>
        <li>usermod -L will disable the users </li>
        <li>The command used to check processes: ps -ef</li>
        <li>sed command is used to perform manipulation on the data within a file that appears as output, it doesn't change the original file. For example: sed 's/lenny/gan/g' filename (this will replace lenny everywhere with gan), to change in the original file add -i flag to the command. Another example: sed -i '/^$/d' filename  (Delete empty lines in the original file also)</li>
    </ul>
</p>

<p>
    <h3>Wild cards </h3>
    <ul>
        <li>* - represents zero or more charachters </li>
        <li>? - represents a single character, example: ls -l ?abcd.txt </li>
        <li>[] - represents a range of characters, example: touch file[1..9].txt, ls -l *[cd]* //either c or d</li>
    </ul>
</p>

<p>
    <h3>Soft Links and Hard links</h3>
    <ul>
        <li>Inode: Pointer o number of a file on the hard disk</li>
        <li>SoftLink: Link will be removed if file is removed or renamed (command: ln -s)</li>
        <li>Hard Link: Deleting or renaming or moving the original file will not affect the hard link (command: ln)<li>
    </ul> 
 </p>

 <p>
    <h3>File Ownership</h3>
    <ul>
    <li>chown changes the ownership of a file</li>
    <li>chgrp changes the group pwnership of a file</li>
    <li>Recurrsiove ownership change -R</li>
 </ul>
 </p>

 <p>
    <h3>Combining and splitting files </h3>
    <ul>
        <li>cat file1 file2 file3 > file4</li>
        <li>split file4</li>
        <li>split -l 300 file.txt childfile : will split file.txt into 300 lines per file and output to childfilea, childfileab and childfileabc</li>
    </ul>
 </p>

 <p>
    <h3>Utility Commands</h3>
    <ul>
        <li>date</li>
        <li>uptime</li>
        <li>hostname</li>
        <li>unmae</li>
        <li>which</li>
        <li>cal</li>
        <li>bc</li>
    </ul>
</p>

<p>
    <h3>Terminal Commands</h3>
    <ul>
        <li>script: It stores terminal activities in a log file that can be named by a user, when a nme is not provided, the default file name typescript is used</li>
        <li>exit</li>
        <li>clear</li>
    </ul>
</p>

<p>
    <h3>Aliases</h3>
    <ul>
        <li>alias dir="ls -l | grep ^d"</li>
        <li>alias tell="whoami; hostname"</li>
    </ul>
</p>

<p>
    <h3>NIC bonding</h3>
    <ul>
        <li>Network Interface Card bonding</li>
        <li>Aggregation of multiple NIC into a single interface bond</li>
    </ul>
</p>

<p>
    <h3>Linux OS Hardening</h3>
    <ul>
        <li>User Account</li>
        <li>User account</li>
        <li>Stop Un-wanted services</li>
        <li>Check on listening ports</li>
        <li>Secure SSh Configuration</li>
        <li>Enable SELinux</li>
        <li>Change Listening services Port Numbers</li>
        <li>Keep your OS up to date (Security Patches</li>
    </ul>
</p>
