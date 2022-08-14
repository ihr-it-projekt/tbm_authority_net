# TBM Authority Net (Police)

A tool for the management of everyday police work.

See gallery for details

# Features

- works on ESX and QB-Core
- [Access Control](https://github.com/ihr-it-projekt/tbm_authority_net/blob/main/docs/accessControl.md)
    - Boss can manage access to all features/grades
    - Grades can only access configured features
    - Boss has always full access
- Charges Management
- Control Center
  - Control Center Agent can see position of an officer on map
  - Control Center Agent can remove officer from Patrol
  - Control Center Agent can manage patrols/vehicle/states of patrol
  - Patrol cleans (state/vehicle) automatically if no officer is related to a patrol
- Patrols
  - Officers can join patrols 
  - Officer can change patrol state and vehicle
- Files
  - Citizen Files can be created/searched by every value/deleted/edit
  - player name can be import when cop creates a new file
  - jail time/penalty calculator based on configured laws 
- Human Resource
  - hire function
  - fire function
  - promotion management
- Laws/Law Books
  - Law management
  - Laws Book management
- Bonus payout management
  - automatically count of online time
  - bonus payout based on online time and boss control
- vehicle register
  - easy vehicle registration. if the owner is in near of vehicle, vehicle data can be imported
  - different vehicle properties can be stored 
- Police can toggle duty on/off
- Dark and Light mode


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

## Gallery


### Charge

#### sdit

![charge edit](./docs/images/charge_edit.JPG "charge edit")

#### search

![charge search](./docs/images/charge_search.JPG "charge search")

#### search results
![charge search results](./docs/images/charge_search_result.JPG "charge search results")

#### states
![charge states](./docs/images/charge_states.JPG "charge states")

#### priorities
![charge priority](./docs/images/charge_priority.JPG "charge priority")

### Control Center

![Control Center](./docs/images/control_center.JPG "Control Center")

#### patrol names

![patrol names](./docs/images/control_center_manage_patrol_names.JPG "patrol names")

#### patrol states

![patrol states](./docs/images/control_center_manage_patrol_states.JPG "patrol states")

#### patrol vehicles

![patrol vehicles](./docs/images/control_center_manage_patrol_vehicles.JPG "patrol vehicles")

### darkmode

![darkmode](./docs/images/darkmode.JPG "darkmode")

### Files

#### file create

![file create](./docs/images/file_create.JPG "file create")

#### file edit

![file edit](./docs/images/file_edit.JPG "file edit")
![file edit 2](./docs/images/file_edit_2.JPG "file edit 2")

####

![](./docs/images/file_search.JPG "")

####

![](./docs/images/file_search_result.JPG "")

####

![](./docs/images/human_resource.JPG "")

####

![](./docs/images/law.JPG "")

####

![](./docs/images/law_bock_edit.JPG "")

####

![](./docs/images/law_create_law.JPG "")

####

![](./docs/images/law_create_law_book.JPG "")

####

![](./docs/images/law_edit.JPG "")

####

![](./docs/images/payout.JPG "")

####

![](./docs/images/payout_2.JPG "")

####

![](./docs/images/vehicle_create.JPG "")

####

![](./docs/images/vehicle_edit.JPG "")

####

![](./docs/images/vehicle_search.JPG "")

####

![](./docs/images/vehicle_search_results.JPG "")
## Legal
### License
You are not allowed to use this mod without a licence. You are not allowed to share the code or republish it in any way. 

