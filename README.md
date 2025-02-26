# AutoCar

# ADAS Project Checklist

1. **Play with the Simulator**
   - [ ] Download and explore the [Udacity Self-Driving Car Simulator](https://github.com/udacity/self-driving-car-sim/tree/master).
   - [ ] Familiarize yourself with its features and controls.

2. **Dump Video from the Simulator**
   - [ ] Find a method to capture video output from the simulator.
   - [ ] Save video frames for further processing.

3. **Test with Vehicle-CV-ADAS**
   - [ ] Use the captured video as input to the [Vehicle-CV-ADAS project](https://github.com/jason-li-831202/Vehicle-CV-ADAS/tree/master).
   - [ ] Verify lane and object detection accuracy.

4. **Sync Video Input and Data Output**
   - [ ] Ensure synchronization between video input and data output.
   - [ ] Implement timestamping if necessary.

5. **Use Simple-PID for Control Parameters**
   - [ ] Implement the [Simple-PID controller](https://github.com/m-lundberg/simple-pid/tree/master).
   - [ ] Generate control parameters based on ADAS data outputs.

6. **Feedback Control Parameters to Unity**
   - [ ] Use [SocketIO](https://github.com/udacity/self-driving-car-sim/tree/master/Assets/SocketIO) in Unity and the socket library in Python for communication.
   - [ ] Ensure real-time feedback of control parameters to the simulator.

7. **Run Continuously**
   - [ ] Test the entire system for continuous operation.
   - [ ] Monitor for latency or synchronization issues.

8. **Replace PID with MPC**
   - [ ] Implement the [do-mpc controller](https://github.com/do-mpc/do-mpc).
   - [ ] Compare performance with the PID controller and make adjustments.