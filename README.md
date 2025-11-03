# Michelle Grace - Death Doula - Website

## To install Zola
'
1. Go to https://github.com/getzola/zola/releases
1. Download the latest version for windows `zola-v<version>-x86_64-pc-windows-msvc.zip`
1. One of:
   1. Move the unzipped `zola.exe` to a location on the System Path
   2. Add the folder you unzipped `zola.exe` into to the System Path
      1. In the Start Menu, look up "Edit the system environment variables"
      2. In the System Properties menu that opens, choose the `Environment Variables...` button
      3. In the Environment Variables window, find `Path` in a list (top is user, bottom is system; probably doesn't matter which you use) and select it then press `Edit...`
      4. In the Edit Environment Variables window, press `New`, then fill in the path to where you unzipped `zola.exe` (in my case it was "E:\Downloads") then click `OK` and close all the windows
      5. (You'll probably have to restart VS Code [or whatever] to get the new Path value loaded)
      6. Now you should be able to do `which zola` or `which zola.exe` in the terminal and it will show the correct path.
   3. Remember to always call `zola.exe` with the full path to the file (avoiding needing to use System Path at all).
