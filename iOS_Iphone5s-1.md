#### Test 5497026186051be_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5497026186051be/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/021CD1ED-E049-4A24-B686-4D5000AAEDD7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/021CD1ED-E049-4A24-B686-4D5000AAEDD7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5497026186051be/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5497026186051be/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6E8B764E-E320-4C43-B3FA-848EC83A8C2A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52065"
,(lldb)     command script import "/tmp/021CD1ED-E049-4A24-B686-4D5000AAEDD7/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-11 12:27:05.952 ThaliTest[1709:3735255] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3BAC0CBF-A416-4160-AADA-1BA40603AC76/Library/Cookies/Cookies.binarycookies
,2016-01-11 12:27:06.222 ThaliTest[1709:3735255] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-11 12:27:06.223 ThaliTest[1709:3735255] Multi-tasking -> Device: YES, App: YES
,2016-01-11 12:27:06.231 ThaliTest[1709:3735255] Unlimited access to network resources
,2016-01-11 12:27:06.240 ThaliTest[1709:3735255] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-11 12:27:10.427 ThaliTest[1709:3735255] Resetting plugins due to page load.
,2016-01-11 12:27:11.926 ThaliTest[1709:3735255] Finished load of: file:///var/mobile/Containers/Bundle/Application/6E8B764E-E320-4C43-B3FA-848EC83A8C2A/ThaliTest.app/www/index.html
,2016-01-11 12:27:12.117 ThaliTest[1709:3735255] JXcore Cordova plugin initializing
2016-01-11 12:27:12.118 ThaliTest[1709:3735424] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone5s-1
,Test app app.js loaded
,TAP version 13
,# setup
,# multiplex can send data
,# teardown

```
