# Folder-Locker
This is a simple Batch based Folder locker.
The Program on fresh Execution in a Directory will create a Directory named "SecureFolder", where users can put there private files.
The locked files will not be shown in Windows search.
There are two version of this Folder Locker.
1) lock_with_mask : This version needs EditV32/EditV64 depending upon your machine. In this version the user's password input      will be masked with '*'.
2) lock_without_mask : This version need's no dependencies & is a standalone program, but does not mask's user password input.

Two version were created due to the fact that the EditVXX.exe file is treated as virus by most of the antivirus & firewall.
I've tested the program with EditVXX.exe file and it proved to be safe for use.
But I cannot garuntee it in your case, So use the mask version at your own risk.

How to use:
  For mask version: Just save the lock_with_mask file with .bat extension in a directory along with EditVxx.exe.
                    The EditVxx.exe file can be found in the zip file provided along with its documentation.
                    EditV zip is not my creation to read it before using it.
  
  For without mask version : Just save the file with .bat extension in a directory & you are good to go.
