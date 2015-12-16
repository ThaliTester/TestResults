#### Test 50650278e989a4f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278e989a4f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A524B724-9DFF-401E-B12A-7DCBB8741D3C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/A524B724-9DFF-401E-B12A-7DCBB8741D3C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278e989a4f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278e989a4f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2285BBB9-87AC-47AC-99F5-C08634143159/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58210"
,(lldb)     command script import "/tmp/A524B724-9DFF-401E-B12A-7DCBB8741D3C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-16 03:29:08.334 ThaliTest[234:35036] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F7BBAB81-42C1-4C02-B789-AE0B5CFE637D/Library/Cookies/Cookies.binarycookies
,2015-12-16 03:29:08.737 ThaliTest[234:35036] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 03:29:08.738 ThaliTest[234:35036] Multi-tasking -> Device: YES, App: YES
,2015-12-16 03:29:08.747 ThaliTest[234:35036] Unlimited access to network resources
,2015-12-16 03:29:08.756 ThaliTest[234:35036] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 03:29:18.378 ThaliTest[234:35036] Resetting plugins due to page load.
,2015-12-16 03:29:22.175 ThaliTest[234:35036] Finished load of: file:///var/mobile/Containers/Bundle/Application/2285BBB9-87AC-47AC-99F5-C08634143159/ThaliTest.app/www/index.html
,2015-12-16 03:29:22.326 ThaliTest[234:35036] JXcore Cordova plugin initializing
,2015-12-16 03:29:22.327 ThaliTest[234:35282] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-16 03:29:23.329 ThaliTest[234:35036] THREAD WARNING: ['JXcore'] took '72.045898' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-16 03:34:22.029 ThaliTest[234:35282] jxcore: startBroadcasting
,2015-12-16 03:34:22.047 ThaliTest[234:35282] server: starting Apple-IpadAir2-1_PT165.HVBgzg==
,2015-12-16 03:34:22.051 ThaliTest[234:35282] multipeer session: start timer: 0x1860f2e0
2015-12-16 03:34:22.053 ThaliTest[234:35282] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT165
2015-12-16 03:34:22.055 ThaliTest[234:35282] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-16 03:34:52.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:35:22.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:35:52.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:36:22.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:36:52.053 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:37:22.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:37:52.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:38:22.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:38:52.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:39:22.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:39:52.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:40:22.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:40:52.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:41:22.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:41:52.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:42:22.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:42:52.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:43:22.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:43:52.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:44:22.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:44:52.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:45:22.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:45:52.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:46:22.053 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:46:52.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:47:22.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:47:52.053 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:48:22.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:48:52.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:49:22.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:49:52.054 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:50:22.039 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:50:52.039 ThaliTest[234:35036] multipeer session: restart
,timeout now
,weAreDoneNow
,done, now sending data to server
,2015-12-16 03:51:22.039 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:51:52.039 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:52:22.039 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:52:52.039 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:53:22.039 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:53:52.039 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:54:22.039 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:54:52.039 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:55:22.038 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:55:52.039 ThaliTest[234:35036] multipeer session: restart
,2015-12-16 03:56:22.039 ThaliTest[234:35036] multipeer session: restart

```
