# sleepReminder
This bash script generates periodic popup and a voice messages, reminding you to go to bed.

The messages are generated at random intervals to make it harder to ignore them.

# Setup 

The script works in Ubuntu. Could work in other *nixes.

Just add the script to cron at the time when you should go to bed. For example:

```0 20 * * * path/to/sleepReminder```

# Customisation

You can change the message text and the delay between the reminders. See the "SETTINGS" section in the script. 
