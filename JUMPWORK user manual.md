# Login

![image-20240814151003482](C:\Users\29131\AppData\Roaming\Typora\typora-user-images\image-20240814151003482.png)

Use Steam's one-click login; before logging in, you must check the box to agree to the Terms of Service and Privacy Policy

# Check the camera connection

If this is your first time using the device, please check whether the camera is functioning properly.

- First, unzip the software folder, then open OrbbecViewer.

<img src="D:\working\软件\EN\open OrbbecViewer.png" alt="open OrbbecViewer" style="zoom:50%;" />

Check if the connection is via a USB 3.0 port or higher.

<img src="D:\working\软件\EN\Check Interface.png" alt="Check Interface" style="zoom:50%;" />

Click on "Depth." If the depth map is displayed correctly, the camera is functioning properly.

<img src="D:\working\软件\EN\depth.png" alt="depth" style="zoom:50%;" />

# Connect Camera

First, select either single-camera mode or dual-camera mode based on the number of cameras you are using. The default mode is single-camera mode.

<img src="D:\working\软件\EN\choose single camera.png" alt="choose single camera" style="zoom:40%;" />

## Single-camera

<img src="D:\working\软件\EN\home page.png" alt="home page" style="zoom:40%;" />

The camera comes with two types of cables: a power cable and a data cable. Please connect the USB end of the data cable to a USB 3.0 port on your computer.

There are two ways to connect the camera:

- One option is automatic connection. You need to check "Auto-connect on startup." If the camera cables are connected before starting the software, it will automatically detect and connect the camera.
- Manual connection: If the camera's cables were not connected before launching the software, you will need to manually click "Connect" after connecting the camera.

After a few seconds, the camera's status will change from "Pending Connection" to "Connecting" and finally to "Connected."

If the camera is accidentally disconnected during use, the software will automatically display a pop-up notification. In this case, you will need to exit the software and restart it to reconnect.

![image-20240813141622835](C:\Users\29131\AppData\Roaming\Typora\typora-user-images\image-20240813141622835.png)

## Double-camera

### **Installation and Placement**

The camera comes with two types of cables: a power cable and a data cable. Please connect the USB end of the data cable to a USB 3.0 port on your computer.

Place the two cameras along a diagonal line, with a minimum diagonal distance of 3 meters and a maximum of 9 meters.

The cameras can be positioned at half the height of a person, or they can be mounted on a wall with the angle tilted downward.

### Connect

There are two ways to connect the camera:

- Automatic connection.：If the camera's cables are fully connected before launching the software, the software will automatically detect and connect to the camera.。
- Manual connection: If the camera's cables were not connected before launching the software, you will need to manually click "Connect" after connecting the camera.

After the camera status shows as "Connected," click the "Calibrate" button. A five-second countdown will begin. Before the countdown ends, immediately place the A4 calibration paper within the shared field of view of the two cameras.【The A4 calibration paper file can be found in the root directory of the installation path: ：\Printingthis\A4.PDF，Please use double-sided printing to ensure that the patterns on both sides are perfectly aligned after printing.】，Avoid blocking the patterns on the calibration paper. Wait for the calibration to complete. A voice prompt will confirm successful calibration, and the software will automatically proceed to the next page. If the calibration accuracy is insufficient, you will need to recalibrate.

![image-20240814153936701](C:\Users\29131\AppData\Roaming\Typora\typora-user-images\image-20240814153936701.png)



# Align Trackers

<img src="D:\working\软件\EN\align trackers.png" alt="align trackers" style="zoom:40%;" />

Once the camera is successfully connected, the software will automatically navigate to the node alignment interface.

There are two alignment methods:

- Raise your left hand in VR and use the controller's ray to click the "Align" button on the raised-hand panel.
- Click the "Align" button in the software to perform the alignment.

After entering the alignment mode, immediately assume an A-Pose and hold the position, then pull the trigger on the controller.

Alternatively, keep your arms naturally hanging down and pull the trigger on the controller.

Look down to observe the skeletal position; if the skeletal position is correct, the alignment is successful.

## HUD display

When the raise hand display window is closed in VR, you can reopen it using the software's button. If the toggle button is green, it indicates that it is open; if the toggle button is gray, it indicates that it is closed.

<img src="D:\working\软件\EN\overlay.png" alt="overlay" style="zoom:40%;" />

# Motion Capture

- For motion capture, first import the FBX model.
  - The FBX model's skeleton must meet the same requirements as outlined on [help.wonderdynamics.com](https://help.wonderdynamics.com/character-creation/ai-mocap-system/markerless-motion-capture/bone-mapping-distribution-and-tpose).
  - After clicking "Start Recording," the FBX model will begin to follow your movements. When you click "Stop Recording," the FBX model will stop following.
  - Click the "Export" button, choose the directory where you want to save the BVH file, and then save the file.

<img src="D:\working\软件\EN\motion capture.png" alt="motion capture" style="zoom:40%;" />

- Open the imported BVH format video using Blender,File--Import--Motion Capture(.bvh).

# Action Demo

- After the camera is connected, you can preview your movements. The distance between you and the camera should be approximately 1.5 meters.
- Motion Capture Pars: Displays parameters for motion preview, status, frame rate, and latency, among other details.
- Click the "Motion Capture Setting" button to toggle the preview on or off.

<img src="D:\working\软件\EN\action demo.png" alt="action demo" style="zoom:40%;" />

# System Setting

<img src="D:\working\软件\EN\system settings.png" alt="system settings" style="zoom:40%;" />

1. **Select Language**:  You can choose between English and Simplified Chinese, with English being the default.

2. **Software Update**: Displays the current version number of the software and whether a new version is available.

3. **Tracking Mode Select **: You can choose between full-body tracking and half-body tracking.

4. **Help**: For more information, you can visit the official JUMPWORK website.







