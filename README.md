# DroneZBreak 
by mavicBreak

Change flight controller parameters of DJI Drones and upgrade/downgrade firmware natively on OSX

<img src='https://i.imgur.com/ZVcBkkd.png' />

<img src='https://i.imgur.com/23Kl0lj.png' />


**Supported macOS:** Sierra (OSX 10.12), El Capitan (OSX 10.11), might work on Yosemite (OSX 10.10)

`It is an unsigned macOS application which is not allowed to run on OSX by default. If you have problem with starting the application go to System Preferences > Security & Privacy > and enable the execution of the app.`

**Supported drones:** Mavic, Spark, P4P, Inspire 2, might work with other DJI drones

**Supported devices:** Mavic Remote Controller, DJI Goggles


**Features:**
+ Set parameters without DJI Assistant
+ Predefinied Normal+ and Sport+ modes
+ Parameters Factory Reset option
+ Firmware Flashing Utility with progress bar actively monitoring the process
+ Unlock drone if it is locked and forced to firmware upgrade
+ One click download & decrypt upgrade log file

**Notes:**

DroneZBreak is fail-safe. In case of application crash during firmware or parameter flashing your device is safe. The operation continues on the device itself regardless of the USB cable connection or application state.

If your drone firmware can not be detected upon startup and DroneZBreak gives an error one case might be because your firewall (like LittleSnitch) is blocking DJI Assistant outgoing connections therefore it is blocking the communication with your drone upgrade service. Thx for marck1991 doing a lot of tests to figure this out.

**How to use:**
1) Launch DJI Assistant 2 (preferably 1.1.2 or older version) or let DroneZBreak to start it automatically upon launch. DJI Assistant can be minimized but must be running in the background.

2) Power up your drone and connect it via USB. Wait a few seconds and the flight controller parameters are automatically recognized.

3) Change the settings and click ‘Apply’.

4) Hover the mouse over a UI element to get more details.

5) If an option is disabled after connection established then it might not supported in your drone's current firmware. Open an issue here to get support.

6) Normal+ and Sport+ options are predefined recommended maximum values for the corresponding modes by the developer.

7) ‘Reset’ will set factory default values.

8) Firmware Upgrade / Downgrade: use this option only with caution.


**Links:**

http://dji.retroroms.info/ - "Wiki"

https://github.com/jezzab/DUMLdore - Even windows users need some love, so DUMLDore was created to help archive, and flash dji_system.bin files on windows platforms.

https://github.com/hdnes/pyduml - Original script of firmware multi-platform flashing in Python

https://github.com/MAVProxyUser/DUMLrub - Ruby port of PyDUML, and firmware cherry picking tool. Allows rolling of custom firmware images.

https://github.com/MAVProxyUser/dji_system.bin - Current Archive of dji_system.bin files that compose firmware updates referenced by MD5 sum. These can be used to upgrade and downgrade, and root your I2, P4, Mavic, Spark, Goggles, and Mavic RC to your hearts content. (Use with pyduml, DUMLDore or DroneZBreak)

https://nolimitdronez.com - Alternative solution for Windows users with excellent live support.



Thanks to hostile, the_lord, P0V, hdnes, jezzab, kilrah, coldflake, freaky123, bin4ry and all the Slack members who spent countless effort and time to figure out all the stuff.
