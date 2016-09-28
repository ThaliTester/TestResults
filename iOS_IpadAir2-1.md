#### Test 850469114456a2a_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469114456a2a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/7708BD39-C63B-4CB7-97DD-A38644F0624D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/7708BD39-C63B-4CB7-97DD-A38644F0624D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469114456a2a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469114456a2a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9441E9DC-AFC3-4352-A92F-BADA1B352706/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62752"
,(lldb)     command script import "/tmp/7708BD39-C63B-4CB7-97DD-A38644F0624D/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-28 10:49:38.233 ThaliTest[3520:6199002] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F7689376-BFFC-4817-BE02-730805E5095A/Library/Cookies/Cookies.binarycookies
,2016-09-28 10:49:38.583 ThaliTest[3520:6199002] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-28 10:49:38.585 ThaliTest[3520:6199002] Multi-tasking -> Device: YES, App: YES
,2016-09-28 10:49:38.605 ThaliTest[3520:6199002] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-28 10:49:40.518 ThaliTest[3520:6199002] Using UIWebView
,2016-09-28 10:49:40.525 ThaliTest[3520:6199002] [CDVTimer][handleopenurl] 0.406027ms
,2016-09-28 10:49:40.532 ThaliTest[3520:6199002] [CDVTimer][intentandnavigationfilter] 6.358027ms
,2016-09-28 10:49:40.532 ThaliTest[3520:6199002] [CDVTimer][gesturehandler] 0.287950ms
,2016-09-28 10:49:40.533 ThaliTest[3520:6199002] [CDVTimer][TotalPluginStartup] 8.558035ms
,2016-09-28 10:49:46.872 ThaliTest[3520:6199002] Resetting plugins due to page load.
,2016-09-28 10:49:49.865 ThaliTest[3520:6199002] Finished load of: file:///var/mobile/Containers/Bundle/Application/9441E9DC-AFC3-4352-A92F-BADA1B352706/ThaliTest.app/www/index.html
,2016-09-28 10:49:50.127 ThaliTest[3520:6199002] JXcore Cordova plugin initializing
,2016-09-28 10:49:50.128 ThaliTest[3520:6199276] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x154713700>
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Optional("E7722DAF-E245-4777-BAB6-5A96DF1AD4ED")
nil
,nil
,Optional("A7725263-51B6-4CC1-AF0D-0E2558B2BE9D")
,Optional("25B7C853-04BB-4569-96EA-876FC91C6CA6")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  55
Number of passed tests:  53
Number of failed tests:  2
Number of ignored tests:  0
,Total duration:  19.51667600870132
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
