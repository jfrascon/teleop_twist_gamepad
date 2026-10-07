# Gamepad setup software

This directory collects manufacturer utilities and setup instructions for gamepads used with `teleop_twist_gamepad`. Each gamepad has its own directory containing the available tools, their provenance and the documented procedure.

| Gamepad | Available instructions |
| --- | --- |
| [Logitech F710](logitech_f710/README.md) | Reconnect the wireless receiver in Windows 10 and calibrate the joystick in Ubuntu. |

PlayStation 4 controllers are also used, but their setup procedure has not yet been documented here.

These resources are maintained in the source repository and are not installed by CMake or required to launch teleoperation. Manufacturer executables remain third-party software subject to their own terms; the package's Apache-2.0 license does not apply to them.
