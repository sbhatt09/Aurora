## Requirements

The operator wears MR glasses, sees the robot's camera feed and telemetry as floating windows, and sends driving commands back to the robot.

-   ROS2 integration
-   Live robot camera streaming
-   Dashboard and telemetry visualization
-   Enterprise deployment capability

## Hardware Recommendations

  -----------------------------------------------------------------------
  Device            True See-through  Availability     Notes
                    MR                         
  ----------------- ----------------- ----------------- -----------------
  Magic Leap 2      Yes               Remaining stock/   Best technical
                                      resellers         fit if obtainable



  Vuzix Shield      Yes               Yes               Low MR
                                                        capability
                            

  PICO 4 Ultra      No                Yes               Best long-term
  Enterprise                                            flexibility
  -----------------------------------------------------------------------


### Compatible software stack for the selected hardware platform

-   ROS 2
-   Gstreamer Pipeline / WebRTC
-   ROS TCP endpoint (ROS end)
-   ROS TCP connector (Unity end)
-   Unity (C#)
-   OpenXR
-   XR Interaction Toolkit (Optional)