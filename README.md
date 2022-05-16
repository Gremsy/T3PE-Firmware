# T3PE-Firmware

# What's new?

## Control gimbal in the FOLLOW mode
- The Gimbal yaw follow the aircraft heading.

## Control gimbal in the LOCK mode
- The Gimbal move independently from the aircraft.

## Control gimbal with Herelink
Use S.Bus signal output from the Herelink for simultaneous control of Autopilot, Gimbal and camera as well.
- In Single mode
  + Scroll wheel controls the TILT or PAN axis (Channel 10).
  + Top button (Right) controls the Gimbal mode including 3 states (Toggle PAN or TILT and Reset Position) (Channel 9).
  + C button controls zoom in for camera (Channel 14).
  + D button controls zoom out for camera (Channel 14).
  + Trigger Camera (Channel 7).

## Control gimbal with MAVLink Compliant Flight Controller (Pixhawk and Cube)
Control gimbal with MAVLink Gimbal Protocol V1 and V2 from Flight Controller.

## Control gimbal with open source gSDK.
- Gremsy SDK to meet the requirements of those building solutions for various industrial applications.
- Refer: https://github.com/Gremsy/gSDK

## Control gimbal with open source MAVSDK.
- Refer: https://mavsdk.mavlink.io/main/en/index.html

## Go to home position when switching the gimbal mode automatically.

## Detect errors when initialization.
- Gimbal will dectect automatically when initialization and pop-up error on the
new gTune with troubleshooting guide.

## Start-up at a random position.

Please refer to Manual: https://gremsy.com/products/gremsy-pe
