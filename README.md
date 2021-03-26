# iR-APRSISD
Garmin/DeLorme inReach (or possibly other) KML feed to APRS-IS  forwarding daemon

 This is a KML-feed to APRS-IS forwarding daemon.  It was written for Garmin/DeLorme inReach devices, but might work elsewhere too.  It polls a KML feed in which it expects to find a point in rougly the form that the inReach online feeds use, with attendant course and altitude data.  It transfers each new point found there to APRS-IS.

This makes it possible to track an Iridium-based satellite device, say, on aprs.fi with all of the amateur radio stuff.  All you need is a machine attached to the internet to run the daemon, a device that's publishing a KML feed.

