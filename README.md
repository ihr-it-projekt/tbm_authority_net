# TBM Authority Net (Police)

A tool for the management of everyday police work.




# Features

- works on ESX and QB-Core
- [Access Control](./docs/AccessControl.md)
    - Boss can manage access to all features/grades
    - Grades can only access configured features
    - Boss has always full access
- [Charges Management](./docs/ChargesManagement.md)
- [Control Center](./docs/ControlCenter.md)
  - Control Center Agent can see position of an officer on map
  - Control Center Agent can remove officer from Patrol
  - Control Center Agent can manage patrols/vehicle/states of patrol
  - Patrol cleans (state/vehicle) automatically if no officer is related to a patrol
- [Patrols](./docs/Patrols.md)
  - Officers can join patrols 
  - Officer can change patrol state and vehicle
- [Files](./docs/Files.md)
  - Citizen Files can be created/searched by every value/deleted/edit
  - player name can be import when cop creates a new file
  - jail time/penalty calculator based on configured laws 
- [Human Resource](./docs/HumanResource.md)
  - hire function
  - fire function
  - promotion management
- [Laws/Law Books](./docs/Laws.md)
  - Law management
  - Laws Book management
- [Bonus payout management](./docs/Payout.md)
  - automatically count of online time
  - bonus payout based on online time and boss control
- [Vehicle Register](./docs/Vehicle.md)
  - easy vehicle registration. if the owner is in near of vehicle, vehicle data can be imported
  - different vehicle properties can be stored 
- Police can toggle duty on/off
- [Dark](./docs/DarkMode.md) and Light mode
- available languages german and english
- you can easy add your own language


## Requirements

- ESX or QBCore

## Installation

- move mod into resource folder
- configure your config.lua
- import import.sql
- Add this line in your `server.cfg`:
```
start tbm_authority_net
```

## Legal

### License

You are not allowed to use this mod without a licence. You are not allowed to share the code or republish it in any way. 
