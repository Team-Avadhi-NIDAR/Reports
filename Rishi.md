1. Mission Start

   Both drones will start at the same time but the movement of delivery drone will be lagging 30 sec by scout drone and start the pre-planned zigzag mission.

   The Delivery Drone follows 30 seconds behind on the same track.

2. Area Scanning (Zigzag Pattern)

   The Scout Drone flies the zigzag path and continuously scans the ground.

   It uses a downward-facing camera and computer vision to detect red-colored markers representing survivors.

3. Survivor Detection

   When a red target is detected, the Scout Drone:

   Captures the GPS location (geotag).

   Stops, Stores and sends the data immediately to the Delivery Drone (via radio or ground control).

   Continues flying forward.

4. Delivery Drone Response

   The Delivery Drone is already following 30 seconds behind.

   When it receives a survivor’s location:

   It diverts slightly from the path (if needed) and navigates to the marked GPS point.

5. Drops the payload using a servo-based release system.

   After the drop, it returns to the same scanning path and continues behind the Scout.

Mission Completion

After the entire area is scanned:

Both drones return to the launch point automatically.

Land safely and log the mission data (video, GPS tags, drop points).


## Sync Between Drones ##

The 30seconds delay keeps both drones on the same flight path, avoiding collision and making coordination simple.

The GPS and flight software ensure both stay synced during the mission.

All movements are automated or preplanned




So we have to calculate few things if we go with this 

not sure about 10 m lag cause (launch area is 6ft x 6ft)
we can have 30 sec lag between both the drones 
