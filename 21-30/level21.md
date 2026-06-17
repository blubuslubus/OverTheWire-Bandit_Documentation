
Goal: A program is running automatically at regular intervals from cron, the time-based job scheduler. Look in /etc/cron.d/ for the configuration and see what command is being executed.

Commands used:
  - ```ls```
  - ```cd```
  - ```cat```

Procedure:
  - Navigating to the required directory and reading the shell script like in the previous level, I understood exactly what was happening in the job. The script truely was easy to read.
  - To test if I understood it correctly, I ran the script with my user, and using the temp file directory I obtained, I could confirm the logic.
  - Now simply hardcoding the ```myname``` variable to ```bandit23```, I found the temp directory, and using ```cat``` I could retrieve the password.
