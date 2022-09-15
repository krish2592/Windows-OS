### Windows 10 forgot password:

## Method 1: Using bootable drive
 1. Restart your pc and click on f9,f10,f11 or a f12 based on system
 2. Open cmd using "shift+10"
 3. CD to "windows/system32" path
 4. Type "regedit"
 5. Click on "HKEY_LOCAL_MACHINE" then on File on the top left
 6. Click on "Load Hive"
 7. Check drive d, e ,f or a g etc where you will get "windows" folder
 8. After finding "windows" folder
 9. Find "system32"
 11. Find "config"
 12. Find a file name "SYSTEM" and then click on it
 13. Give any name to folder eg. 1234
 14. Go back to "HKEY_LOCAL_MACHINE", you will get the file "1234"
 15. Expand folder you will get "Setup", click on it
 16. you will get "cmdline" in the value data type "cmd.exe"
 17. Go to "SetupType" and set value data to "2".
 13. Click back to file "1234" then on File on top you will get "Unload Hive"
 14. Click on "Unload Hive"
 15. Close cmd and installation window and then remove bootable drive 
 16. Restart you will get automatically a administrative cmd 
 17. Type command  "net user" you will get all list of user
 18. Type command "net user <user name> *" then enter
 19. You will get password to enter. Hit enter twice now you will get password  success message
 20. Now your password has removed
 21. Restart system


 ## Method 2: Automatic repair mode
 1. Force shut down window power button untill you will get automatic repair mode
 2. go to advance option 
 3. go to troubleshoot
 4. go to cmd
 5. Follow step 3 to 14 mentioned in Method1
 6. continue
 7. Follow 17 to 21 step of Method1

