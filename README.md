# ENGR 120 Robot Project

To run code: Download RobotC and connect a VEX Robot. Port setup is provided in header of file. 


# Logic: 

Do an initial spin to find maximum IR (Detect Beacon) 

Move towards target at a variable speed depending on distance to target, measured by ultrasonic range finder 

If one of the IR detectors reads a higher value (by more than a margin or error), course correct by running one motor faster to change direction

When target is reached, drop crane to tether cable

Signal completion by hitting the 'That Was Easy' button with the back of the crane
