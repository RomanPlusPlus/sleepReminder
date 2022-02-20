# sleepReminder
This bash script generates periodic popup and a voice messages, reminding you to go to bed.

The messages are generated at random intervals to make it harder to ignore them.

# Setup 

The script works in Ubuntu. Could work in other *nixes.

It makes sense to manually launch the script first, to see if it works in your OS. In a few seconds after the launch, you should see a popup and hear a synthetic voice reminding you to go to bed. 

If it works, add the script to cron, like this:

```3 20 * * * XDG_RUNTIME_DIR=/run/user/$(id -u) /bin/bash '/PATH_TO/sleepReminder'```

Don't forget to replace `PATH_TO` with your own path.

# Customisation

You can change the message text and the delay between the reminders. See the "SETTINGS" section in the script. 
