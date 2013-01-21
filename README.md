SetupWorkspaceMeyboardMaestro
=============================

A set of macros to setup my work environment. Includes checking wheter I'm connected to my Home or Work network SSID, then checking if a second monitor is attached and then starting / closing apps that I only want to run on Work or at Home. After that, my prefferred window layout gets setup.

The control flow is:
- At System Wake or Hotkey or Triggered by the ScreenChange Marco (running all 5 seconds to recognize if the screens have changed)
- Configure Workspace -->
- Position (Home) || Position (Work)
--> one of the 4 Position macros 