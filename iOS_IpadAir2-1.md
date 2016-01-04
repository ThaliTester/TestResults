#### Test 54970261c23922d_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/54970261c23922d/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A287108F-1009-4A58-88CE-BDFE0642F264/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/A287108F-1009-4A58-88CE-BDFE0642F264/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/54970261c23922d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/54970261c23922d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AF76C1EE-6894-41A8-A4AC-4A6452D6822C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64433"
,(lldb)     command script import "/tmp/A287108F-1009-4A58-88CE-BDFE0642F264/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-04 17:02:13.092 ThaliTest[1250:2744287] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BB50598F-2954-450F-92A1-94E5B5FB9988/Library/Cookies/Cookies.binarycookies
,2016-01-04 17:02:13.471 ThaliTest[1250:2744287] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-04 17:02:13.472 ThaliTest[1250:2744287] Multi-tasking -> Device: YES, App: YES
,2016-01-04 17:02:13.481 ThaliTest[1250:2744287] Unlimited access to network resources
,2016-01-04 17:02:13.490 ThaliTest[1250:2744287] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-04 17:02:23.077 ThaliTest[1250:2744287] Resetting plugins due to page load.
,2016-01-04 17:02:26.886 ThaliTest[1250:2744287] Finished load of: file:///var/mobile/Containers/Bundle/Application/AF76C1EE-6894-41A8-A4AC-4A6452D6822C/ThaliTest.app/www/index.html
,2016-01-04 17:02:27.053 ThaliTest[1250:2744287] JXcore Cordova plugin initializing
,2016-01-04 17:02:27.054 ThaliTest[1250:2744556] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started

```
