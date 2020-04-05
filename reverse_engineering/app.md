# App

## Debug menu

In the iOS app there is a `UIVIewController` labeled `BBDebugArea`. I wrote a small MobileSubstrate tweak that uses the inbox button as a trigger to open `BBDebugArea`. From what I've seen, the proper way to open `BBDebugMenu` is through `BB.DebugSettings`, but unfortunately `BB.DebugSettings` storyboard file is missing from the app.

![](images/bbdebugarea_1.png | width=100)

### Console tab
- Receives data from various sources: All (0x00), Debug (0x02), MD (0x03), Batt (0x04), PLink (0x05), Phone (0x06), RLink (0x07), Remote (0x08), and Accessory (0x09)
- Has the ability to send commands

### Telemetry tab
- Ability to email logs
- "Git" button tries to clone from a private Boosted Bitbucket repo but fails
- "Start" button starts telemetry from either MD or Battery
- Starting the telemetry results in data in the console

### Tools tab
- None of the buttons are functional

### HwInfo tab
- Shows firmware versions and serial numbers of the board
- Nothing interesting

If anyone has any additional information about this menu, please share.