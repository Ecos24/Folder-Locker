cls
@ECHO OFF
title Folder Locker
if EXIST "Control Panel.{21EC2020-3AEA-1069-A2DD-08002B30309D}" goto UNLOCK
if NOT EXIST SecureFolder goto MDSecureFolder
:CONFIRM
echo ------------------------------------------
echo This Trick is Enforced by Divyang
echo -------------------------------------------
echo Are you sure to lock this folder? (Y/N)
set/p "cho=>"
if %cho%==Y goto LOCK
if %cho%==y goto LOCK
if %cho%==n goto END
if %cho%==N goto END
echo Invalid choice.
pause
goto CONFIRM
:LOCK
ren SecureFolder "Control Panel.{21EC2020-3AEA-1069-A2DD-08002B30309D}"
attrib +h +s "Control Panel.{21EC2020-3AEA-1069-A2DD-08002B30309D}"
echo Folder locked
pause
goto End
:UNLOCK
echo ----------------------------------------------
echo  Going to Private Files 
echo ----------------------------------------------
echo Enter password to Unlock Your Secure Folder
set/p "pass=-->"
if NOT %pass%== putpasswordhere goto FAIL
attrib -h -s "Control Panel.{21EC2020-3AEA-1069-A2DD-08002B30309D}"
ren "Control Panel.{21EC2020-3AEA-1069-A2DD-08002B30309D}" SecureFolder
echo Folder Unlocked successfully by you.
pause
goto End
:FAIL
echo Invalid password you mooronn!!!
pause
goto end
:MDSecureFolder
md SecureFolder
echo SecureFolder created successfully
pause
goto End
:End
