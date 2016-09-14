#### Test 82914073fb4f932_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073fb4f932/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/1E56A1A4-8EA6-4DBC-840D-0EBDB68CAFB8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/1E56A1A4-8EA6-4DBC-840D-0EBDB68CAFB8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073fb4f932/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073fb4f932/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/94FDF251-9709-4EE4-A6FA-4CF1FF35028B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61818"
,(lldb)     command script import "/tmp/1E56A1A4-8EA6-4DBC-840D-0EBDB68CAFB8/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 19:24:26.195 ThaliTest[2329:4436063] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/32C6837A-FBFF-4818-A68A-952106DB7F9D/Library/Cookies/Cookies.binarycookies
,2016-09-14 19:24:26.577 ThaliTest[2329:4436063] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 19:24:26.579 ThaliTest[2329:4436063] Multi-tasking -> Device: YES, App: YES
,2016-09-14 19:24:26.602 ThaliTest[2329:4436063] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 19:24:28.608 ThaliTest[2329:4436063] Using UIWebView
,2016-09-14 19:24:28.617 ThaliTest[2329:4436063] [CDVTimer][handleopenurl] 0.331998ms
,2016-09-14 19:24:28.624 ThaliTest[2329:4436063] [CDVTimer][intentandnavigationfilter] 6.497979ms
,2016-09-14 19:24:28.625 ThaliTest[2329:4436063] [CDVTimer][gesturehandler] 0.304997ms
,2016-09-14 19:24:28.625 ThaliTest[2329:4436063] [CDVTimer][TotalPluginStartup] 8.709013ms
,2016-09-14 19:24:35.134 ThaliTest[2329:4436063] Resetting plugins due to page load.
,2016-09-14 19:24:38.306 ThaliTest[2329:4436063] Finished load of: file:///var/mobile/Containers/Bundle/Application/94FDF251-9709-4EE4-A6FA-4CF1FF35028B/ThaliTest.app/www/index.html
,2016-09-14 19:24:38.524 ThaliTest[2329:4436063] JXcore Cordova plugin initializing
,2016-09-14 19:24:38.525 ThaliTest[2329:4436294] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x13fd044d0>
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-14 19:24:58.256 ThaliTest[2329:4436063] BTM: attaching to BTServer
,2016-09-14 19:24:59.238 ThaliTest[2329:4436063] BTM: local device power state changed
2016-09-14 19:24:59.238 ThaliTest[2329:4436063] BTM: power is now off
,2016-09-14 19:25:00.042 ThaliTest[2329:4436063] BTM: local device power state changed
2016-09-14 19:25:00.043 ThaliTest[2329:4436063] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  48
Number of passed tests:  47
Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  14.87813502550125
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
