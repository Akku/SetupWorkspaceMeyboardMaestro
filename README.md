SetupWorkspaceMeyboardMaestro
=============================

A set of macros to setup my work environment. Includes checking wheter I'm connected to my Home or Work network SSID, then checking if a second monitor is attached and then starting / closing apps that I only want to run on Work or at Home. After that, my prefferred window layout gets setup.

The control flow is:
- At System Wake or Hotkey or Triggered by the ScreenChange Marco (running all 5 seconds to recognize if the screens have changed)
- Configure Workspace (finds SSID)
- Position (Home) (XOR) Position (Work)
- (XOR) --> one of the 4 Position macros 

===== Adapting for your needs =====
You'll have to change your SSID, if you have a second monitor you'll have to check if it has the boundaries that I've used, and of course you should configure your apps and window sizes yourself, but my macros can serve as a starting point.
