# HW3
RPC LOOP(mode = 0)
type UI/run will enter UI_gesture mode(mode = 1)
use gesture to select angle
ring is 30 degree
slope is 45 degree
line is 60 degree
push the user_button to confirm select angle and publish message to client
client will stop UI_gesture mode


type AD/run to enter angle_detection mode(mode = 2)
if tilt angle over the selected angle, it will publish message to client
if over ten times, client will stop angle_detection mode
