# WheelchairSimulator
KeyboardInputController (move with left and right key). This is attached to the GameManager obj, it is currently disabled. For debug use only.
ConnectionsHandler (a UDP Listener class attached to the GameManager obj) listens to UDP messages. There is an obj called UDPSenderTesterObj with a UDPSenderTester.cs script attached, which continuously broadcasts a float direction variable through UDP. You can change the direction variable in runtime to test out how it changes the direction of the movement.
