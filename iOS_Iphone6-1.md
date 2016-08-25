#### Test 79763830bc83054_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830bc83054/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6B780954-B99D-42E7-93A0-334F76A4DFEA/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/6B780954-B99D-42E7-93A0-334F76A4DFEA/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830bc83054/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830bc83054/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/707E7636-A2E9-46A4-84DB-1403A292513F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52750"
,(lldb)     command script import "/tmp/6B780954-B99D-42E7-93A0-334F76A4DFEA/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-25 10:45:27.498 ThaliTest[409:412593] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/58978589-DBD3-4DEC-BA7B-BAA3CBDA4315/Library/Cookies/Cookies.binarycookies
,2016-08-25 10:45:27.933 ThaliTest[409:412593] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-25 10:45:27.935 ThaliTest[409:412593] Multi-tasking -> Device: YES, App: YES
,2016-08-25 10:45:27.957 ThaliTest[409:412593] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-25 10:45:29.667 ThaliTest[409:412593] Using UIWebView
,2016-08-25 10:45:29.674 ThaliTest[409:412593] [CDVTimer][handleopenurl] 0.523984ms
,2016-08-25 10:45:29.682 ThaliTest[409:412593] [CDVTimer][intentandnavigationfilter] 7.302046ms
2016-08-25 10:45:29.683 ThaliTest[409:412593] [CDVTimer][gesturehandler] 0.351965ms
2016-08-25 10:45:29.683 ThaliTest[409:412593] [CDVTimer][TotalPluginStartup] 9.858966ms
,2016-08-25 10:45:36.230 ThaliTest[409:412593] Resetting plugins due to page load.
,2016-08-25 10:45:39.698 ThaliTest[409:412593] Finished load of: file:///var/mobile/Containers/Bundle/Application/707E7636-A2E9-46A4-84DB-1403A292513F/ThaliTest.app/www/index.html
,2016-08-25 10:45:39.997 ThaliTest[409:412593] JXcore Cordova plugin initializing
,2016-08-25 10:45:39.998 ThaliTest[409:412831] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-25 10:45:46.859 ThaliTest[409:412831] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-25 10:45:46.860 ThaliTest[409:412831] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-08-25 10:45:46.860 ThaliTest[409:412831] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-25 10:45:46.862 ThaliTest[409:412831] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-25 10:45:47.144 ThaliTest[409:412831] Native method executeNativeTests not found.
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
