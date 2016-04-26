# Device API
## GET: /devices/:id
Returns page showing device information and possible actions.

* Monitor device
* Update configuration
* Get connection string
* Send message to device

## GET: /devices
Returns a list of all devices.

## DELETE: /devices/:id
Deletes device.

## POST: /devices
Adds a device. 

## POST: /devices/:id
Updates device conifiguration

## GET: /devices/:id/hub-keys
Returns hub keys registered for a device.

## PUT: /devices/:id/enabledstatus
Don't understand this one yet...

## GET: /devices/:id/commands
Shows available commands for this device.

## POST: /devices/:id/commands/:command
Issues a command to the device. 