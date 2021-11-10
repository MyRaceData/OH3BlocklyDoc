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
### Send Command
Block image:

![SendCommand](https://github.com/MyRaceData/OH3BlocklyDoc/blob/main/SendCommand.png)

Function:
Sends a command or posts an update to an **Item**  or **Group**

![Sendoptions](https://github.com/MyRaceData/BlocklyImg/blob/main/sendoptions.png)

Notes:
1. valid input is like **Items** eg. ON or OFF for a switch
2. Clicking 'MyItem' displays a list of **Items** to pick from
___
## Timers and Delays
###### image of Timers and Delays catagory ######
![TimersAndDelays](https://github.com/MyRaceData/BlocklyImg/blob/main/timersanddelays1.png)
### Thread Sleep
Block image:

![ThreadSleep](https://github.com/MyRaceData/BlocklyImg/blob/main/threadsleep.png)

Function:
Suspends execution of the rule for a given period of time

Notes:
1. unit of time (ms) is milliseconds
2. 1000 ms = 1 second
___
## Voice and Multimedia
###### image of Voice and Multimedia catagory ######
![VoiceandMultimedia](https://github.com/MyRaceData/BlocklyImg/blob/main/voiceandmultimedia.png)
___
## Notifications
###### image of Notifications catagory ######
![Notifications](https://github.com/MyRaceData/BlocklyImg/blob/main/notifications.png)
___
## Value Storage
###### image of Value Storage catagory ######
![Value Storage](https://github.com/MyRaceData/BlocklyImg/blob/main/valuestorage.png)
___
## Logging and Output
###### image of Logging and Output catagory ######
![Logging and Output](https://github.com/MyRaceData/BlocklyImg/blob/main/loggingandoutput.png)
### Log Statement
Block image:

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

