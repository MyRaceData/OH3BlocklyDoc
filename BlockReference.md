# openHAB Blockly Reference
openHAB specific Blockly language block reference
##### *Blocks available as of version 3.2.0.M4 (release date: 7 Oct. 2021)* #####
###### image of openHAB specific block catagories ######
![GetItemState](https://github.com/MyRaceData/BlocklyImg/blob/main/toolboxcatagories.png)
___
### Table of Contents ###
* [Items and Things](https://github.com/MyRaceData/OH3BlocklyDoc/blob/main/BlockReference.md#items-and-things)
* [Timers and Delays](https://github.com/MyRaceData/OH3BlocklyDoc/blob/main/BlockReference.md#timers-and-delays)
* [Voice and Multimedia](https://github.com/MyRaceData/OH3BlocklyDoc/blob/main/BlockReference.md#voice-and-multimedia)
* [Notifications](https://github.com/MyRaceData/OH3BlocklyDoc/blob/main/BlockReference.md#notifications)
* [Value Storage](https://github.com/MyRaceData/OH3BlocklyDoc/blob/main/BlockReference.md#value-storage)
* [Logging and Output](https://github.com/MyRaceData/OH3BlocklyDoc/blob/main/BlockReference.md#logging-and-output)
___
## Items and Things
###### image of Items and Things catagory ######
![ItemsAndThings](https://github.com/MyRaceData/BlocklyImg/blob/main/itemsandthings.png)
### Item
###### Block image: ######
![Item](https://github.com/MyRaceData/BlocklyImg/blob/main/item.png)

Function:
Retrieves a specific **Item**  or **Group** for use in other item related functions

Notes:
1. Clicking 'MyItem' displays a list of **Items** to pick from
### Get Item ###
###### Block image: ######
![GetItem](https://github.com/MyRaceData/BlocklyImg/blob/main/getitem.png)

Function:
Gets an **Item** for use in other item related functions

Notes:
1. Clicking 'MyItem' displays a list of **Items** to pick from
### Get Members of Group ###
###### Block image: ######
![Getmember](https://github.com/MyRaceData/BlocklyImg/blob/main/getmemberofgroup.png)

Function:
Gets the members of a **group**

Notes:
1. A valid group must be used
### Get State of Item ###
###### Block image: ######
![GetItemState](https://github.com/MyRaceData/BlocklyImg/blob/main/getstateofitem.png)

Function:
Get the current state of an **Item**  or **Group**

Notes:
### Get Name of Item ###
###### Block image: ######
![GetItemName](https://github.com/MyRaceData/BlocklyImg/blob/main/getnameofitem.png)

Function:
Get the current name, label, state, catagory, tags, groups, or type of an **Item**
![ItemOptions](https://github.com/MyRaceData/BlocklyImg/blob/main/itemnameoptions.png)

Notes:
### Send Command ###
###### Block image: ######

![SendCommand](https://github.com/MyRaceData/OH3BlocklyDoc/blob/main/SendCommand.png)

Function:
Sends a command or posts an update to an **Item**  or **Group**

![Sendoptions](https://github.com/MyRaceData/BlocklyImg/blob/main/sendoptions.png)

Notes:
1. valid input is like **Items** eg. ON or OFF for a switch
2. Clicking 'MyItem' displays a list of **Items** to pick from
___
## Timers and Delays ##
###### image of Timers and Delays catagory ######
![TimersAndDelays](https://github.com/MyRaceData/BlocklyImg/blob/main/timersanddelays1.png)
### Thread Sleep ###
###### Block image: ######

![ThreadSleep](https://github.com/MyRaceData/BlocklyImg/blob/main/threadsleep.png)

Function:
Suspends execution of the rule for a given period of time

Notes:
1. unit of time (ms) is milliseconds
2. 1000 ms = 1 second
3. a number may be directly entered into pink box 

### After *period of time* Do With Timer ###
###### Block image: ######

![AfterTimeDoWithTimer](https://github.com/MyRaceData/BlocklyImg/blob/main/afterxdowithtimer.png)

Function:
Schedule a task to be performed at a specified period in the future

Notes:
1. a number may be directly entered into gray box

Options for time

![Time Options](https://github.com/MyRaceData/BlocklyImg/blob/main/timeroptions.png)

### After *period of time* Do With Timer With Reschedule ###
###### Block image: ######

![AfterTimeDoWithTimerWithRetrigger](https://github.com/MyRaceData/BlocklyImg/blob/main/afterXdowithtimerretrigger.png)

Function:
Schedule a task to be performed at a specified period in the future with the ability to reschedule, cancel or ignore the timer in the event the timer is retriggered

Options for Reschedule

![Reschedule Options](https://github.com/MyRaceData/BlocklyImg/blob/main/rescheduleoptions.png)

Notes:
1. a number may be directly entered into gray box
2. If reschedule is selected, the timer will restart if the timer is retriggered
3. If cancel is selected, retriggering the timer will cancel it
4. If do nothing is selected, retriggering the timer will be ignored

### Cancel Timer ###
###### Block image: ######

![CancelTimer](https://github.com/MyRaceData/BlocklyImg/blob/main/canceltimer.png)

Function:
Cancels a named timer

Notes:

### Timer is Active ###
###### Block image: ######

![TimerIsActive](https://github.com/MyRaceData/BlocklyImg/blob/main/timerisactive.png)

Function:
Determines if a named timer is active

Notes:
1. For use in conditional

### Timer is Running ###
###### Block image: ######

![TimerIsRunning](https://github.com/MyRaceData/BlocklyImg/blob/main/timerisrunning.png)

Function:
Determines if a named timer is running

Notes:
1. For use in conditional
___
## Voice and Multimedia
###### image of Voice and Multimedia catagory ######
![VoiceandMultimedia](https://github.com/MyRaceData/BlocklyImg/blob/main/voiceandmultimedia.png)

### Play Audio ###
###### Block image: ######

![PlayAudio](https://github.com/MyRaceData/BlocklyImg/blob/main/playfile.png)

Function:
Plays an audio file on an audio sink

Notes:
1. audio file must reside in userfiles/openhab/sounds
2. specify an available audio sink
###### image of default options: ######
![PlayOptions](https://github.com/MyRaceData/BlocklyImg/blob/main/playoptions.png)

### Play Audio with Volume ###
###### Block image: ######

![PlayAudiowithVol](https://github.com/MyRaceData/BlocklyImg/blob/main/playfilewv.png)

Function:
Plays an audio file on an audio sink at a set volume

Notes:
1. audio file must reside in userfiles/openhab/sounds
2. specify an available audio sink

### Play Stream ###
###### Block image: ######

![PlayStream](https://github.com/MyRaceData/BlocklyImg/blob/main/playstream.png)

Function:
Starts an stream playing on an audio sink

Notes:
1. specify an available audio sink

### Stop Stream ###
###### Block image: ######

![StopStream](https://github.com/MyRaceData/BlocklyImg/blob/main/stopstream.png)

Function:
Stops a playing stream on the specified audio sink

Notes:

### Say ###
###### Block image: ######

![Say](https://github.com/MyRaceData/BlocklyImg/blob/main/say.png)

Function:
Determines if a named timer is running

Notes:
___
## Notifications
###### image of Notifications catagory ######
![Notifications](https://github.com/MyRaceData/BlocklyImg/blob/main/notifications.png)


### Send Notification Email ###
###### Block image: ######

![SendNotificationEmail](https://github.com/MyRaceData/BlocklyImg/blob/main/sendemail.png)

Function:
Sends a notification to an email address

Notes:
1. Provide valid email address

### Send Notification to All Devices ###
###### Block image: ######

![SendNotificationAllDevices](https://github.com/MyRaceData/BlocklyImg/blob/main/sendnotification.png)

Function:
Sends a notification to all devices

Notes:


### Send Notification to Log Only ###
###### Block image: ######

![SendNotificationtoLog](https://github.com/MyRaceData/BlocklyImg/blob/main/sendnotificationlog.png)

Function:
Sends a notification to the log

Notes:
___
## Value Storage
###### image of Value Storage catagory ######
![Value Storage](https://github.com/MyRaceData/BlocklyImg/blob/main/valuestorage.png)


### Store Value ###
###### Block image: ######

![StoreValue](https://github.com/MyRaceData/BlocklyImg/blob/main/storevalue.png)

Function:
Stores a value in a keyed pair for use in the future

Notes:
1. Provide a unique key name

### Get Stored Value ###
###### Block image: ######

![GetStoredValue](https://github.com/MyRaceData/BlocklyImg/blob/main/getvalue.png)

Function:
Retrieves a stored value in a keyed pair

Notes:
1. Provide previously named key

___
## Logging and Output
###### image of Logging and Output catagory ######
![Logging and Output](https://github.com/MyRaceData/BlocklyImg/blob/main/loggingandoutput.png)
### Log Statement
###### Block image: ######

![GetItemState](https://github.com/MyRaceData/OH3BlocklyDoc/blob/main/OHLog.png)

Function:
Sends a entry to the openHAB log file

Notes:
Drop down list for log statement severity
Levels:
1. error
2. warn
3. info
4. debug
5. trace

![LogLevel](https://github.com/MyRaceData/OH3BlocklyDoc/blob/main/logLevelcrop.png)

