----------------------------------------------------------------------------------------------------------------------------------------
# Alpakit
This Unreal Editor plugin is for creating content-only plugin mods, avoiding reliance upon UE4SS or widgets to manage mod life cycle, in addition to isolation of cooking and packaging from the rest of your project, and auto-copying to game installation upon packaging.


1. Unzip the downloaded archive.
1. Copy the `Engine` folder to your Unreal Editor installation root folder e.g. C:\Unreal Engine\UE_5.3\
2. Copy the `Mods` folder to your project installation root e.g. C:\Altar-Main\Altar\ (NOT Altar-main\Altar\Plugins)
3. Attempt to open Unreal Editor and use the plugin.

----------------------------------------------------------------------------------------------------------------------------------------
*4. If you are warned that it was built for a different version then you will need to build/rebuild `AutomationScripts.Automation.csproj` in Visual Studio (even if you have Launcher Unreal Editor build; all .Net tools come with source files).
   a. If you do not have Visual Studio, download Visual Studio 2022 Community 2022 here: https://www.junian.net/dev/visual-studio-community-download-links/
   b. If you have not set up your Visual Studio environment for Unreal Engine and Oblivion Remastered, you can find more information on the Oblivion Remastered Modding Discord and also here: https://dev.epicgames.com/documentation/en-us/unreal-engine/setting-up-visual-studio-development-environment-for-cplusplus-projects-in-unreal-engine
   --------------------------------------------------------------
 A. Do this by opening your .sln in Visual Studio. 
    X If you do not have one then right click your .uproject and select "Generate Visual Studio project files".
 B. In the Solution Explorer on the right side of the window, navigate to Programs > Automation > AutomationScripts.Automation.
 C. Right-click and select "Build".
 D. If for whatever reason this was insufficient and compilation fails with errors specific to AutomationScripts or the plugin fails to work perfectly on opening Unreal Editor, then repeat steps B and C but choose "Rebuild"
 E. If for whatever reason you still face issues, feel free to raise an Issue or let me know personally.
----------------------------------------------------------------------------------------------------------------------------------------
# Credits
Alpakit courtesy of https://github.com/satisfactorymodding/SatisfactoryUnrealProject (hard fork)
Kein for Altar SDK and his source fork of AlpakitSO.
----------------------------------------------------------------------------------------------------------------------------------------

