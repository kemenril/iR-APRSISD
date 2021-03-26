# iR-APRSISD
## Garmin/DeLorme inReach (or possibly other) KML feed to APRS-IS  forwarding daemon

This is a KML-feed to APRS-IS forwarding daemon. It was written for Garmin/DeLorme inReach devices, but might work elsewhere too. It polls a KML feed in which it expects to find a point in rougly the form that the inReach online feeds use, with attendant course, speed, and elevation data. It synthesizes an APRS position report for each point found there, complete with course, speed, and elevation data, and sends it to APRS-IS.
 
This makes it possible to track an Iridium-based satellite device, say, on aprs.fi with all of the amateur radio stuff.  All you need is a machine -- with the aprslib Python module installed -- attached to the internet to run the daemon, and a device that's publishing a KML feed.

