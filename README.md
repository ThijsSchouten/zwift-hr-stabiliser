# zwift-hr-stabiliser
CLI to read HR from BLE source. Increases/decreases zwift watt% based on target HR. 

## Requirements

### Hardware
- Zwift setup 
- Bluetooth heartrate strap (preferebly one which allows two BLE connections)

### Python dependencies
Use pip to install dependencies from file or manually install the following dependencies:
- [AutoHotKey wrapper]( https://github.com/spyoungtech/ahk)
- [bleak] (https://github.com/hbldh/bleak)

### External Dependencies
[AutoHotKey](https://www.autohotkey.com/)
should be installed and available from PATH. 
On windows: 
- install AutoHotKey
- 'edit system environment variables' from start. 
- click 'Environment variables' 
- scroll to 'Path'
- add AutoHotKey installation folder (usually C:\Program Files\AutoHotkey)
- Dont forget to restart commandprompt

## Usage
### Setup paramaters
Target Heartrate:
Heartrate smoothing
