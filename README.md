I cloned the repository using the git clone command.
```bash
git clone https://github.com/NkubaJr/submission_reminder_NkubaJr
cd submission_reminder_NkubaJr
```
I created a script file named create_environment.sh
```bash
vi create_environment.sh
```
In the script file input command to prompt the user to input the name that should replace the variable ${USER_NAME}

I also created the main directory submission_reminder_${USER_NAME}

In the main directory I also made subdirectories namely app, config, modules and assets

From these subdirectories I created files that have crucial roles in running the app
```bash
config.env → Stores environment variables
submissions.txt → Contains student assignment record
reminder.sh → Handles reminder notifications
functions.sh → Includes helper functions
```
I also created a script file in the main directory named startup.sh

startup.sh → Starts the application

After that, I gave execution permissions to these files using the chmod +x "file name" command

Then, I ran the script
```bash
./create_environment.sh
```
Lastly, I pushed the work onto github
```bash
git add .
git commit -m "App works!"
git push
```
