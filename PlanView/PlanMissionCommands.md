# Plan View - Mission Commands
Mission Commands are used to design autonomous missions for your vehicle.

The default mission command is "Waypoint". The available commands, by category, are:

Basic:
* Waypoint
* Land
* Takeoff
* Home Position

Loiter:
* Loiter
* Loiter (time)
* Loiter (altitude)

VTOL:
* VTOL takeoff and transition
* VTOL transition and land
* VTOL transition

Advanced:
* Jump to item
* Set servo
* Configure mount
* Control mount

Flight Control:
* Change speed
* Land start

Camera:
* Camera control
* Camera trigger distance


## Basic Commands
### Waypoint
The Waypoint command directs the vehicle in a straight line to the specified location at the specified altitude.

### Land
The Land command will attempt to land the vehicle at the specified location at the specified altitude. The success of the landing is dependent upon the landing parameters being set correctly for the vehicle being used. 
