#### Test 506502789b39735_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502789b39735/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/6E431B19-5857-421F-B668-16FF5A1D59C5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/6E431B19-5857-421F-B668-16FF5A1D59C5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502789b39735/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502789b39735/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C1D60020-E2A5-47C2-96C9-366CA6257415/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58073"
,(lldb)     command script import "/tmp/6E431B19-5857-421F-B668-16FF5A1D59C5/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-16 02:32:44.864 ThaliTest[223:28684] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/53A1D958-87AB-4B61-AE64-E09A0732C371/Library/Cookies/Cookies.binarycookies
,2015-12-16 02:32:45.244 ThaliTest[223:28684] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 02:32:45.245 ThaliTest[223:28684] Multi-tasking -> Device: YES, App: YES
,2015-12-16 02:32:45.254 ThaliTest[223:28684] Unlimited access to network resources
,2015-12-16 02:32:45.262 ThaliTest[223:28684] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 02:32:55.064 ThaliTest[223:28684] Resetting plugins due to page load.
,2015-12-16 02:32:58.610 ThaliTest[223:28684] Finished load of: file:///var/mobile/Containers/Bundle/Application/C1D60020-E2A5-47C2-96C9-366CA6257415/ThaliTest.app/www/index.html
,2015-12-16 02:32:58.768 ThaliTest[223:28684] JXcore Cordova plugin initializing
,2015-12-16 02:32:58.769 ThaliTest[223:28918] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-16 02:32:59.754 ThaliTest[223:28684] THREAD WARNING: ['JXcore'] took '70.199951' ms. Plugin should use a background thread.
,Connected to the server!

```
