#### Test 558877588826def_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/558877588826def/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/1F75505E-AA93-424F-A484-8A0B9F1186DA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/1F75505E-AA93-424F-A484-8A0B9F1186DA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/558877588826def/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/558877588826def/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5BA4270D-A0C7-4391-A6D7-07BCB4E580A3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54678"
,(lldb)     command script import "/tmp/1F75505E-AA93-424F-A484-8A0B9F1186DA/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-13 13:35:29.070 ThaliTest[1918:4100757] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E1E4AF9B-0C4E-4EC2-B768-AC786D784259/Library/Cookies/Cookies.binarycookies
,2016-01-13 13:35:29.298 ThaliTest[1918:4100757] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-13 13:35:29.299 ThaliTest[1918:4100757] Multi-tasking -> Device: YES, App: YES
,2016-01-13 13:35:29.305 ThaliTest[1918:4100757] Unlimited access to network resources
,2016-01-13 13:35:29.311 ThaliTest[1918:4100757] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-13 13:35:33.527 ThaliTest[1918:4100757] Resetting plugins due to page load.
,2016-01-13 13:35:35.020 ThaliTest[1918:4100757] Finished load of: file:///var/mobile/Containers/Bundle/Application/5BA4270D-A0C7-4391-A6D7-07BCB4E580A3/ThaliTest.app/www/index.html
,2016-01-13 13:35:35.153 ThaliTest[1918:4100757] JXcore Cordova plugin initializing
,2016-01-13 13:35:35.155 ThaliTest[1918:4100910] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-IpadAir2-1
,Test app app.js loaded
,--= Surplus to requirements =--
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
