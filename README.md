# Hubitat
Hubitat zone

http://HubIP/hub/zigbee/getChildAndRouteInfo

def today = timeToday(null, location.timeZone) 
use (groovy.time.TimeCategory) { 
newDate1 = today+3.hours
 }
 logMsg "New Date: " + newDate1
