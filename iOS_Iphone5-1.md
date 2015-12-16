#### Test 50650278dbf8a2a_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278dbf8a2a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/C780CF1B-6051-4EDB-B2C6-67654902AE6E/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/C780CF1B-6051-4EDB-B2C6-67654902AE6E/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278dbf8a2a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278dbf8a2a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EDF243E9-00E3-4D9D-9641-BD1B3C5EBBBD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57908"
,(lldb)     command script import "/tmp/C780CF1B-6051-4EDB-B2C6-67654902AE6E/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-16 01:36:34.080 ThaliTest[208:27303] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3B7C2E3E-384A-44CC-9141-AF148CB71A03/Library/Cookies/Cookies.binarycookies
,2015-12-16 01:36:34.201 ThaliTest[208:27303] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 01:36:34.203 ThaliTest[208:27303] Multi-tasking -> Device: YES, App: YES
,2015-12-16 01:36:34.210 ThaliTest[208:27303] Unlimited access to network resources
,2015-12-16 01:36:34.224 ThaliTest[208:27303] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 01:36:44.961 ThaliTest[208:27303] Resetting plugins due to page load.
,2015-12-16 01:36:49.528 ThaliTest[208:27303] Finished load of: file:///var/mobile/Containers/Bundle/Application/EDF243E9-00E3-4D9D-9641-BD1B3C5EBBBD/ThaliTest.app/www/index.html
,2015-12-16 01:36:49.744 ThaliTest[208:27303] JXcore Cordova plugin initializing
,2015-12-16 01:36:49.746 ThaliTest[208:27505] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-16 01:36:52.230 ThaliTest[208:27303] THREAD WARNING: ['JXcore'] took '154.026855' ms. Plugin should use a background thread.
,Connected to the server!

```
