#### Test 549702618c0ebdb_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/549702618c0ebdb/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/3A8615E0-19EB-465D-8BF2-058893AE1A2C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/3A8615E0-19EB-465D-8BF2-058893AE1A2C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/549702618c0ebdb/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/549702618c0ebdb/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/037259B8-642B-47B0-A53C-05F1E4A8562A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50408"
,(lldb)     command script import "/tmp/3A8615E0-19EB-465D-8BF2-058893AE1A2C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-01-08 16:30:44.659 ThaliTest[1547:3338869] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CC199EC1-F4CB-474B-9639-CC398D81CAF3/Library/Cookies/Cookies.binarycookies
,2016-01-08 16:30:45.059 ThaliTest[1547:3338869] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 16:30:45.060 ThaliTest[1547:3338869] Multi-tasking -> Device: YES, App: YES
,2016-01-08 16:30:45.069 ThaliTest[1547:3338869] Unlimited access to network resources
,2016-01-08 16:30:45.078 ThaliTest[1547:3338869] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 16:30:53.103 ThaliTest[1547:3338869] Resetting plugins due to page load.
,2016-01-08 16:30:56.418 ThaliTest[1547:3338869] Finished load of: file:///var/mobile/Containers/Bundle/Application/037259B8-642B-47B0-A53C-05F1E4A8562A/ThaliTest.app/www/index.html
,2016-01-08 16:30:56.582 ThaliTest[1547:3338869] JXcore Cordova plugin initializing
2016-01-08 16:30:56.582 ThaliTest[1547:3339110] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
