#### Test 79763830bc83054_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830bc83054/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/4DD5E3F2-E93A-4884-ACE3-CE103E71F62F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/4DD5E3F2-E93A-4884-ACE3-CE103E71F62F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830bc83054/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830bc83054/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DF8DA37C-321A-47A8-BC0F-C392BC09A541/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52753"
,(lldb)     command script import "/tmp/4DD5E3F2-E93A-4884-ACE3-CE103E71F62F/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-25 10:45:30.468 ThaliTest[821:1782092] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4906CD8C-02ED-4238-9870-44880665DD77/Library/Cookies/Cookies.binarycookies
,2016-08-25 10:45:30.909 ThaliTest[821:1782092] Apache Cordova native platform version 4.1.1 is starting.
2016-08-25 10:45:30.910 ThaliTest[821:1782092] Multi-tasking -> Device: YES, App: YES
,2016-08-25 10:45:30.931 ThaliTest[821:1782092] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-25 10:45:32.845 ThaliTest[821:1782092] Using UIWebView
,2016-08-25 10:45:32.854 ThaliTest[821:1782092] [CDVTimer][handleopenurl] 0.481963ms
,2016-08-25 10:45:32.862 ThaliTest[821:1782092] [CDVTimer][intentandnavigationfilter] 7.974982ms
2016-08-25 10:45:32.863 ThaliTest[821:1782092] [CDVTimer][gesturehandler] 0.375032ms
2016-08-25 10:45:32.864 ThaliTest[821:1782092] [CDVTimer][TotalPluginStar,tup] 10.702014ms
,2016-08-25 10:45:39.120 ThaliTest[821:1782092] Resetting plugins due to page load.
,2016-08-25 10:45:42.729 ThaliTest[821:1782092] Finished load of: file:///var/mobile/Containers/Bundle/Application/DF8DA37C-321A-47A8-BC0F-C392BC09A541/ThaliTest.app/www/index.html
,2016-08-25 10:45:42.982 ThaliTest[821:1782092] JXcore Cordova plugin initializing
,2016-08-25 10:45:42.983 ThaliTest[821:1782335] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-25 10:45:51.225 ThaliTest[821:1782335] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-25 10:45:51.226 ThaliTest[821:1782335] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-25 10:45:51.227 ThaliTest[821:1782335] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-25 10:45:51.229 ThaliTest[821:1782335] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-25 10:45:51.565 ThaliTest[821:1782335] Native method executeNativeTests not found.
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
