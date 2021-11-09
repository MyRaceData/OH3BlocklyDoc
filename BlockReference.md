# openHAB Blockly Reference
openHAB specific Blockly language block reference
##### *Blocks available as of version 3.2.0.M4 (release date: 7 Oct. 2021)* #####
###### image of openHAB specific block catagories ######
![GetItemState](https://github.com/MyRaceData/BlocklyImg/blob/main/toolboxcatagories.png)
## Items and Things
###### image of Items and Things catagory ######
![ItemsAndThings](https://github.com/MyRaceData/BlocklyImg/blob/main/itemsandthings.png)
### Item
###### Block image: ######
![GetItemState](https://github.com/MyRaceData/BlocklyImg/blob/main/item.png)

Function:
Retrieves a specific **Item**  or **Group** for use in other item related functions

Notes:
1. Clicking 'MyItem' displays a list of **Items** to pick from
### Get Item ###
###### Block image: ######
![GetItemState](https://github.com/MyRaceData/BlocklyImg/blob/main/getitem.png)

Function:
Gets an **Item** for use in other item related functions

Notes:
1. Clicking 'MyItem' displays a list of **Items** to pick from
### Get Members of Group ###
###### Block image: ######
![GetItemState](https://github.com/MyRaceData/BlocklyImg/blob/main/getmemberofgroup.png)

Function:
Gets the members of a **group**

Notes:
1. A valid group must be used
### Get State of Item ###
###### Block image: ######
![GetItemState](https://github.com/MyRaceData/BlocklyImg/blob/main/getstateofitem.png)

Function:
Get the current state of an **Item**

Notes:
### Get Name of Item ###
###### Block image: ######
![GetItemState](https://github.com/MyRaceData/BlocklyImg/blob/main/getnameofitem.png)

Function:
Get the current name, label, state, catagory, tags, groups, or type of an **Item**
![GetItemState](https://github.com/MyRaceData/BlocklyImg/blob/main/itemnameoptions.png)

Notes:






### Send Command
Block image:

![GetItemState](https://github.com/MyRaceData/OH3BlocklyDoc/blob/main/SendCommand.png)

Function:
Sends a Command to an **Item**

Notes:
1. valid input is like **Items** eg. ON or OFF for a switch
2. Clicking 'MyItem' displays a list of **Items** to pick from

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

