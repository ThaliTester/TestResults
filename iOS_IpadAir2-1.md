#### Test 549702619369e5e_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/549702619369e5e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/2F99DB7A-692F-43A1-A96E-CA5C1BA93865/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/2F99DB7A-692F-43A1-A96E-CA5C1BA93865/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/549702619369e5e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/549702619369e5e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/21540180-81CB-46ED-A633-7283D2A41E8A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51393"
,(lldb)     command script import "/tmp/2F99DB7A-692F-43A1-A96E-CA5C1BA93865/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 23:26:05.739 ThaliTest[1628:3391857] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/38680586-4AD5-458F-9267-3223DD5C35D6/Library/Cookies/Cookies.binarycookies
,2016-01-08 23:26:06.072 ThaliTest[1628:3391857] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 23:26:06.073 ThaliTest[1628:3391857] Multi-tasking -> Device: YES, App: YES
,2016-01-08 23:26:06.081 ThaliTest[1628:3391857] Unlimited access to network resources
,2016-01-08 23:26:06.089 ThaliTest[1628:3391857] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 23:26:15.319 ThaliTest[1628:3391857] Resetting plugins due to page load.
,2016-01-08 23:26:18.718 ThaliTest[1628:3391857] Finished load of: file:///var/mobile/Containers/Bundle/Application/21540180-81CB-46ED-A633-7283D2A41E8A/ThaliTest.app/www/index.html
,2016-01-08 23:26:18.876 ThaliTest[1628:3391857] JXcore Cordova plugin initializing
,2016-01-08 23:26:18.877 ThaliTest[1628:3392075] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded
,TAP version 13
,# setup
,# multiplex can send data

```
