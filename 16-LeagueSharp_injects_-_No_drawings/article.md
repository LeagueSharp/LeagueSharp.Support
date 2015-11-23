This was tested with Windows 7 (64 bit) and Windows 8 (64 bit). It might work with 32 bit systems as well (step 3 and 4 are redundant then).

 1. Go to your system32 folder (%windir%\system32)
 2. Delete every file which starts with "d3dx9_" (make a backup to be sure)
 3. Go to your SysWOW64 folder (%windir%\SysWOW64)
 4. Repeat this step from 2
 5. Reinstall Download DirectX (June 2010) here [DirectX](http://download.microsoft.com/download/8/4/A/84A35BF1-DAFE-4AE8-82AF-AD2AE20B6B14/directx_Jun2010_redist.exe)
 7. Run it as administrator
 8. Accept license agreement
 9. Select extraction folder. DirectX won't be installed there, it's just a temporary folder for installation files
 10. Wait for extraction to finish
 11. Open extraction folder, find DXsetup.exe in that folder. Run it as administrator
 12. Accept license agreement, proceed through installation

Reboot your computer.
LeagueSharp should now work as intended.

If Leaguesharp is still not showing ingame do the next following thing,

 1. Run League of legends borderless as shown [here](http://i.imgur.com/hL4CmnJ.gifv)
 2. Check if you've enabled drawings on the Loader.exe
 3. Go to loader.exe than settings and have show drawings enabled as shown [here](https://img.joduska.me/?q=http://i1383.photobucket.com/albums/ah312/myzka_korea/3241252212_zpsfwihbaej.png)
 
If you've tried everything and drawings are still not showing for you Check for the following things,

 1. Check nothing is conflicting with Our loader.exe As Cursevoice/TeamspeakOverlay/SteamOVerlay/Mouse-keymenus
 2. Have atleast one assembly injecting
 
if you've met these requirements and menus are still not showing remove the "Config" folder of Leagueoflegends

 1. Go to "C:\Riot Games\League of Legends\" Look for a folder called "Config" and remove it
