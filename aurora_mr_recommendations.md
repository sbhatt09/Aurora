# Requirements

The operator wears MR glasses, sees the robot's camera feed and telemetry as floating windows, and sends driving commands back to the robot.

- ROS2 integration
- Live robot camera streaming
- Dashboard and telemetry visualization
- Enterprise deployment capability

---

# Hardware Recommendations

| Device              | True See-through MR | Availability              | Notes                          |
|--------------------|---------------------|---------------------------|--------------------------------|
| Magic Leap 2       | Yes                 | Remaining stock/resellers | Best technical fit if obtainable |
| Vuzix Shield       | Yes                 | Yes                       | Low MR capability              |
| PICO 4 Ultra Enterprise | No              | Yes                       | Best long-term flexibility     |

---

# Compatible Software Stack (Selected Hardware Platform)

- ROS 2
- GStreamer Pipeline / WebRTC
- ROS-TCP-Endpoint (ROS side)
- ROS-TCP-Connector (Unity side)
- Unity (C#)
- OpenXR
- XR Interaction Toolkit (optional)