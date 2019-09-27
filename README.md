# Linux_battery_power

This repository contains the script through which battery power is notified to user.

## User

I have created this script for myself, But in case you also want to use or fork or modify these Scripts than feel free to make changes

## Prorpose

This script runs using a cronjob and will notify the various battery levels

## Example Notification

### Battery Level 98%
Please unplug the power Source, To avoid anytype of heating or battery issue.

### Battery Level 25%
Only 25% of the battery is remaining --> customizable

### Battery level 19%
Please plug the power Source, Otherwise you may loose your ongoing work

### Battery level 17%
Please plug the power Source, Otherwise you may loose your ongoing work

### Battery level 15%
Please plug the power Source, Otherwise you may loose your ongoing work

### Battery level 10% - Reserve
Sleep the Linux System

### Additional Notification
You can add in scripts configuration file


## Working of Script

It will create a cronJob which will trigger the file in background after every 1 min which will check and notify the user according to the configuration provided
