#### Test 506502789318894_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502789318894/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/DD496A58-7833-42D0-B7D0-144739459415/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/DD496A58-7833-42D0-B7D0-144739459415/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502789318894/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502789318894/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/18E0DC36-114D-40CD-BD0F-F8600DFC3D04/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56812"
,(lldb)     command script import "/tmp/DD496A58-7833-42D0-B7D0-144739459415/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-27 12:40:15.053 ThaliTest[1894:1521545] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/172DFE9E-4C16-420B-8689-B8C7D4C15020/Library/Cookies/Cookies.binarycookies
,2015-11-27 12:40:15.434 ThaliTest[1894:1521545] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-27 12:40:15.435 ThaliTest[1894:1521545] Multi-tasking -> Device: YES, App: YES
,2015-11-27 12:40:15.443 ThaliTest[1894:1521545] Unlimited access to network resources
,2015-11-27 12:40:15.449 ThaliTest[1894:1521545] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-27 12:40:18.865 ThaliTest[1894:1521545] Resetting plugins due to page load.
,2015-11-27 12:40:19.198 ThaliTest[1894:1521545] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/18E0DC36-114D-40CD-BD0F-F8600DFC3D04/ThaliTest.app/www/index.html
,2015-11-27 12:40:19.324 ThaliTest[1894:1521545] JXcore Cordova plugin initializing
2015-11-27 12:40:19.326 ThaliTest[1894:1521680] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,my name is : Apple-Iphone6-1_PT8409
,check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded

```
