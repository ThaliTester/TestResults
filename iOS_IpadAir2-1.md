#### Test 8621445004dab41_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8621445004dab41/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/900A6915-637C-4BC4-A7FA-174B38DFBB42/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/900A6915-637C-4BC4-A7FA-174B38DFBB42/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8621445004dab41/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8621445004dab41/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EC66104A-458F-4B21-969A-E8F8BCEBD45E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49739"
,(lldb)     command script import "/tmp/900A6915-637C-4BC4-A7FA-174B38DFBB42/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 01:03:43.179 ThaliTest[2929:5365308] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AA0B1C80-2C0C-4001-801A-C6D0D4B4EAC1/Library/Cookies/Cookies.binarycookies
,2016-09-22 01:03:43.529 ThaliTest[2929:5365308] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 01:03:43.531 ThaliTest[2929:5365308] Multi-tasking -> Device: YES, App: YES
,2016-09-22 01:03:43.549 ThaliTest[2929:5365308] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 01:03:45.607 ThaliTest[2929:5365308] Using UIWebView
,2016-09-22 01:03:45.616 ThaliTest[2929:5365308] [CDVTimer][handleopenurl] 0.347018ms
,2016-09-22 01:03:45.623 ThaliTest[2929:5365308] [CDVTimer][intentandnavigationfilter] 6.466985ms
,2016-09-22 01:03:45.624 ThaliTest[2929:5365308] [CDVTimer][gesturehandler] 0.302970ms
,2016-09-22 01:03:45.625 ThaliTest[2929:5365308] [CDVTimer][TotalPluginStartup] 8.659959ms
,2016-09-22 01:03:52.525 ThaliTest[2929:5365308] Resetting plugins due to page load.
,2016-09-22 01:03:56.525 ThaliTest[2929:5365308] Finished load of: file:///var/mobile/Containers/Bundle/Application/EC66104A-458F-4B21-969A-E8F8BCEBD45E/ThaliTest.app/www/index.html
,2016-09-22 01:03:56.796 ThaliTest[2929:5365308] JXcore Cordova plugin initializing
,2016-09-22 01:03:56.797 ThaliTest[2929:5365573] JXcore instance initializing
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
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x127f1cd00>
,Optional("7CD733DB-928C-4BB8-B4F6-97F43700BAB4")
,nil
,nil
,Optional("783767F5-D9D1-4FD7-970D-6B10B1E411B1")
,Optional("95CD6EE7-03FB-49F0-A75F-C32E7B8009EB")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-22 01:04:21.891 ThaliTest[2929:5365308] BTM: attaching to BTServer
,2016-09-22 01:04:22.698 ThaliTest[2929:5365308] BTM: local device power state changed
2016-09-22 01:04:22.703 ThaliTest[2929:5365308] BTM: power is now on
,2016-09-22 01:04:27.375 ThaliTest[2929:5365308] BTM: local device power state changed
2016-09-22 01:04:27.375 ThaliTest[2929:5365308] BTM: power is now off
,*Native tests were executed*
,Total number of executed tests:  50
Number of passed tests:  50
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.04192501306534
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
