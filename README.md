Shell Scripts
=============

My helper shell scripts


Git Reminder
------------

Create a file in your home directory called "git-watched.txt" with a list of the working
directories you want to be notified about (one per line, full path), for example:

    /home/user/Project/FirstProject
    /home/user/Project/SecondProject

Use crontab -e and add the following line:

    */5 * * * * DISPLAY=:0 /home/user/bin/git-reminder

it won't work without specifying DISPLAY.

