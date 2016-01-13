#### Test 55902202f27eba5_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55902202f27eba5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/50A91986-6645-4B03-A7F4-6180722D427E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/50A91986-6645-4B03-A7F4-6180722D427E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55902202f27eba5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55902202f27eba5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/41516F22-D500-4042-9B92-E2AC642DF2DD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55089"
,(lldb)     command script import "/tmp/50A91986-6645-4B03-A7F4-6180722D427E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-13 16:33:56.303 ThaliTest[1892:3967544] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9CA4F92E-623C-4F2E-8794-027580E64734/Library/Cookies/Cookies.binarycookies
,2016-01-13 16:33:56.536 ThaliTest[1892:3967544] Apache Cordova native platform version 3.9.2 is starting.
2016-01-13 16:33:56.537 ThaliTest[1892:3967544] Multi-tasking -> Device: YES, App: YES
,2016-01-13 16:33:56.544 ThaliTest[1892:3967544] Unlimited access to network resources
2016-01-13 16:33:56.551 ThaliTest[1892:3967544] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.,
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-13 16:34:00.793 ThaliTest[1892:3967544] Resetting plugins due to page load.
,2016-01-13 16:34:02.301 ThaliTest[1892:3967544] Finished load of: file:///var/mobile/Containers/Bundle/Application/41516F22-D500-4042-9B92-E2AC642DF2DD/ThaliTest.app/www/index.html
,2016-01-13 16:34:02.461 ThaliTest[1892:3967544] JXcore Cordova plugin initializing
,2016-01-13 16:34:02.462 ThaliTest[1892:3967710] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone6-1
,Test app app.js loaded
,--= Surplus to requirements =--
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
