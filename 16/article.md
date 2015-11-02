This was tested with Windows 7 (64 bit) and Windows 8 (64 bit). It might work with 32 bit systems as well (step 3 and 4 are redundant then).

 1. Go to your system32 folder (%windir%\system32)
 2. Delete every file which starts with "d3dx9_" (make a backup to be sure)
 3. Go to your SysWOW64 folder (%windir%\SysWOW64)
 4. Repeat step 2
 5. Reinstall [DirectX](http://download.microsoft.com/download/8/4/A/84A35BF1-DAFE-4AE8-82AF-AD2AE20B6B14/directx_Jun2010_redist.exe)

Reboot your computer.
LeagueSharp should now work as intended.
