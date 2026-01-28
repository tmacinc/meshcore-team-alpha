## feature requests

- BUG - stale time data when user entered geofence... 
    Set location source to "Phone GPS"
    Stand completely still for 35+ seconds (trigger geofence)
    Watch other user's status during the 30-second stationary detection window
    Expected: Should never show absurd times like "1d ago"
    Monitor logs: Check for any Invalid lastSeen timestamp warnings if defensive validation is added

- historical track when user selected on map

- preload map for your location so it's ready when you switch.

- fix if text active, stays active when switching chats.



- remember last chat window opened?



- broaden focus, hunting, backcountry, day-to-day, crisis, SAR

- Splash screen on launch, logo and name on first launch. Setting to disable

- Connection Tab
    1. scan button - change on launch to not be retry, switch to retry after first scan. add icon in the description text.
    2. pull and display radio settings - (add ability to configure radio settings) DONE
    3. Location tracking settings, option to change location update interval in minutes (already planned and in debug stage)

- Map tab
    1. ring interval: make customizable input for radius aside from predefined option.

- App settings
    1. customizable accent color
    2. light and dark mode

- Future capability
    1. EXFIL plans and sharing via bluetooth. See ReadyPlan for reference.


## DONE
- add mute notifications for specific chat options -DONE
- add indicator for waypoint received, and color code on map until clicked. Show who sent the waypoint.  DONE
- Allow sending of waypoints to all or specific user. REMOVED - NOT WANTED
- progress of waypoint sharing. DONE
- test if renaming device update contact properly. DONE - fixed naming bug and now works properly.
- Advert discovery - check behavior to avoid spamming on new contacts if they are sending telemetry. DONE - removed autodiscovery on channel messages. Requires advert or telemetry from new contact.
- Check why some contacts show Needs sync. Currently appears to only add contacts properly from adverts. DONE - these are placeholders for contacts that have only sent messages.
- Revist heard notifications - DONE Seem to be working. Doesn't look like channels can show received alerts.
- push waypoint edits to other users that already have the waypoints - DONE
- fix user display on map. Should be arrow with compass heading from device. DONE
- Fix delayed opening of sync window. DONE
- add unread below bar on chats. DONE
- click user on map allows send message to user. DONE
- auto send message on reconnect? Currently gets lost. DONE
- added companion battery voltage display to connection screen.
- Test/add companion gps data functionality. ADDED, seems working.
- Moved app persistence to BLE manager so the app behaives normally when not connected. Added stop button to notification to force stop the service if needed/for convenience.
- move delete local data button to settings as restore app defaults/wipe data and remove data deletion option from connection screen. DONE
- scan button - change on launch to not be retry, switch to retry after first scan. add icon in the description text.DONE
- pull and display radio settings - (add ability to configure radio settings) DONE
- User configurable telemetry intervals, time and distance based. DONE
- Convert TELE to binary to save transmission airtime. This will help integrate with firmware version also. DONE
- Check if bearings are handled properly, currently varying a lot while stationary. WORKING - added filter, movement based bearing when moving. DONE

### 1.0
- port to flutter for iOS support.