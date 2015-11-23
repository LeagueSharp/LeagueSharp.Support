This was tested with Windows 7 (64 bit) and Windows 8 (64 bit). It might work with 32 bit systems as well (step 3 and 4 are redundant then).

 1. Go to your system32 folder (%windir%\system32)
 2. Delete every file which starts with "d3dx9_" (make a backup to be sure)
 3. Go to your SysWOW64 folder (%windir%\SysWOW64)
 4. Repeat step 2
 5. Reinstall [DirectX (June 2010)](http://download.microsoft.com/download/8/4/A/84A35BF1-DAFE-4AE8-82AF-AD2AE20B6B14/directx_Jun2010_redist.exe)
 
Please keep in mind that the setup you just downloaded **only extracts** the actual installation of DirectX. You have to run the setup afterwards from the folder you extracted it to. The setup is named "DXSetup.exe".

After you have successfully installed DirectX, reboot your computer.

LeagueSharp should now work as intended.

In case you are still facing issues with the drawings, please assure that ["Show Drawings" is enabled in the loader](http://i.imgur.com/oHYK3wc.png). Moreover, make sure that you are running League of Legends in [borderless windowed mode](https://i.imgur.com/hL4CmnJ.gifv).

If none of the above helped you to solve your issue, please make sure that no software is running in the background which could possibily interfere with LeagueSharp. Software, which interacts with League of Legends or open windows in general (TeamViewer, Curse Voice, Steam, Mouse drivers) are known to cause these kind of issues. 

You can also try to reset your League of Legend's configuration by removing the "Config" folder from your League of Legends folder.
