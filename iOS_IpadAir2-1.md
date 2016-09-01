#### Test 835917643a9a586_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/835917643a9a586/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/30784967-BBBF-41F7-ADAB-A72797548988/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/30784967-BBBF-41F7-ADAB-A72797548988/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/835917643a9a586/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/835917643a9a586/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B58F9A3D-94B7-4F32-AA3F-028E05E3FC08/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62053"
,(lldb)     command script import "/tmp/30784967-BBBF-41F7-ADAB-A72797548988/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-01 11:30:28.835 ThaliTest[1537:2741679] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DF86D685-B643-4B82-BE2A-10E10AEDA47E/Library/Cookies/Cookies.binarycookies
,2016-09-01 11:30:29.261 ThaliTest[1537:2741679] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-01 11:30:29.262 ThaliTest[1537:2741679] Multi-tasking -> Device: YES, App: YES
,2016-09-01 11:30:29.278 ThaliTest[1537:2741679] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-01 11:30:31.370 ThaliTest[1537:2741679] Using UIWebView
,2016-09-01 11:30:31.377 ThaliTest[1537:2741679] [CDVTimer][handleopenurl] 0.467002ms
,2016-09-01 11:30:31.385 ThaliTest[1537:2741679] [CDVTimer][intentandnavigationfilter] 7.537007ms
,2016-09-01 11:30:31.386 ThaliTest[1537:2741679] [CDVTimer][gesturehandler] 0.339985ms
,2016-09-01 11:30:31.386 ThaliTest[1537:2741679] [CDVTimer][TotalPluginStartup] 10.366023ms
,2016-09-01 11:30:38.277 ThaliTest[1537:2741679] Resetting plugins due to page load.
,2016-09-01 11:30:42.091 ThaliTest[1537:2741679] Finished load of: file:///var/mobile/Containers/Bundle/Application/B58F9A3D-94B7-4F32-AA3F-028E05E3FC08/ThaliTest.app/www/index.html
,2016-09-01 11:30:42.281 ThaliTest[1537:2741679] JXcore Cordova plugin initializing
,2016-09-01 11:30:42.282 ThaliTest[1537:2741949] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-01 11:30:48.444 ThaliTest[1537:2741949] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-01 11:30:48.445 ThaliTest[1537:2741949] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-01 11:30:48.445 ThaliTest[1537:2741949] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-01 11:30:48.447 ThaliTest[1537:2741949] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-01 11:30:48.736 ThaliTest[1537:2741949] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005156993865966797
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
