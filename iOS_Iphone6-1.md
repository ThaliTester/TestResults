#### Test 5497026179923a9_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5497026179923a9/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A1ECFF24-79E8-4D3C-A626-C35AD04F92C7/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A1ECFF24-79E8-4D3C-A626-C35AD04F92C7/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5497026179923a9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5497026179923a9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1417D94D-87CD-4168-9B73-D21DA78F8D60/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51963"
,(lldb)     command script import "/tmp/A1ECFF24-79E8-4D3C-A626-C35AD04F92C7/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-11 11:49:07.564 ThaliTest[1700:3649514] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0B70DF75-7C0F-40E8-A3D6-A6B369B4A8D3/Library/Cookies/Cookies.binarycookies
,2016-01-11 11:49:07.912 ThaliTest[1700:3649514] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-11 11:49:07.914 ThaliTest[1700:3649514] Multi-tasking -> Device: YES, App: YES
,2016-01-11 11:49:07.923 ThaliTest[1700:3649514] Unlimited access to network resources
,2016-01-11 11:49:07.935 ThaliTest[1700:3649514] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-11 11:49:16.524 ThaliTest[1700:3649514] Resetting plugins due to page load.
,2016-01-11 11:49:19.526 ThaliTest[1700:3649514] Finished load of: file:///var/mobile/Containers/Bundle/Application/1417D94D-87CD-4168-9B73-D21DA78F8D60/ThaliTest.app/www/index.html
,2016-01-11 11:49:19.711 ThaliTest[1700:3649514] JXcore Cordova plugin initializing
,2016-01-11 11:49:19.713 ThaliTest[1700:3649726] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone6-1
,Test app app.js loaded
,--= Surplus to requirements =--
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
