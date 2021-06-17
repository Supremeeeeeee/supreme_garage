Garage system for ESX Servers

Some Code has been re-worked. Supports Cars, Boats, & Aircrafts. This Garage Script only takes into account the Vehicles Purchased in the Car/Boat/Aircraft Shop or any other Shop that sells Vehicles. Players can also go to the Pound to retrieve their Vehicle if its lost or Destroyed for a Fee. During a reboot all Vehicles go back to the Garage.

# Features:
- Uses the BT-Target System
* Unable to Store Vehicles you don't own.
* Ability to Kick people who try to Cheat using the Garage & Set Custom Kick Message.
* Private Property Garages.
* Vehicle Impound
* Aircraft, Boat, & Car Garage.
* Aircraft, Boat, & Car Impound.
* JOB Impound.

preview - https://streamable.com/cedkni

# Requirements:
* Required:
* [bt-target] (https://github.com/brentN5/bt-target)
* [esx_vehicleshop](https://github.com/ESX-Org/esx_vehicleshop)
i have d3x_vehicleshop so you will have to change it back to esx_vehicleshop or your custom vehicle script

* Optional:
  * [esx_aircraftshop](i will release my version of this really soon)

# Download & Installation:
1) Download the .zip.
2) Extract the .zip or Open the .zip.
3) Place `supreme_garage` in your ESX Directory
4) Add `supreme_garage` to your server.cfg

# KNOWN BUGS:
* There is a Limit on how many Vehicles that can be in each garage. For me it was 36 Vehicles in the Car Garage but after that i couldn't pull anymore out. You can still buy more Boats & Planes if the Car Garage is at 36.
* If you are having problems with the SQL from esx_vehicleshop try the SQL from here. If a problem with the SQL from here try esx_vehicleshop SQL. If still having problems please submit an issue.

# How to Use:
* To Store a Vehicle in the Garage:
  * Pull into the Blue Marker
  * Open the menu
  * Select Return Vehicle

* To Retrieve a Vehicle in the Garage:
  * Walk into the Green Marker & Use Your Left ALT
  * Open the menu
  * Select View Vehicle List

* To Retrieve a Vehicle from the Pound:
  * Walk into the Blue Marker
  * Open the menu
  * Select the Vehicle from the list


- Future Updates

* Impounds compatible with BT-Target
- Menu list will be completley changed to (nh-context)
