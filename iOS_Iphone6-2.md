#### Test 83268893feeea5a_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83268893feeea5a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/9D81659F-87F2-4E86-89A1-AC369B612225/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/9D81659F-87F2-4E86-89A1-AC369B612225/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83268893feeea5a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83268893feeea5a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/DEF7630E-0275-4198-9505-99209304BFD5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61647"
,(lldb)     command script import "/tmp/9D81659F-87F2-4E86-89A1-AC369B612225/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 07:18:26.634 ThaliTest[1221:1554484] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8F1D16B4-D76E-441F-810D-64CCEC77E107/Library/Cookies/Cookies.binarycookies
,2016-09-21 07:18:26.671 ThaliTest[1221:1554484] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 07:18:26.672 ThaliTest[1221:1554484] Multi-tasking -> Device: YES, App: YES
,2016-09-21 07:18:26.685 ThaliTest[1221:1554484] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 07:18:27.011 ThaliTest[1221:1554484] Using UIWebView
,2016-09-21 07:18:27.017 ThaliTest[1221:1554484] [CDVTimer][handleopenurl] 0.198960ms
,2016-09-21 07:18:27.021 ThaliTest[1221:1554484] [CDVTimer][intentandnavigationfilter] 3.715992ms
2016-09-21 07:18:27.021 ThaliTest[1221:1554484] [CDVTimer][gesturehandler] 0.139952ms
2016-09-21 07:18:27.021 ThaliTest[1221:1554484] [CDVTimer][TotalPluginS,tartup] 4.884958ms
,2016-09-21 07:18:32.450 ThaliTest[1221:1554484] Resetting plugins due to page load.
,2016-09-21 07:18:32.919 ThaliTest[1221:1554484] Finished load of: file:///var/containers/Bundle/Application/DEF7630E-0275-4198-9505-99209304BFD5/ThaliTest.app/www/index.html
,2016-09-21 07:18:33.386 ThaliTest[1221:1554484] JXcore Cordova plugin initializing
,2016-09-21 07:18:33.387 ThaliTest[1221:1554644] JXcore instance initializing
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
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x146c85130>
,Optional("4CF107CB-8997-4C11-850F-82DE6B648EE3")
nil
nil
Optional("F605693D-81AC-488E-90EF-4250B3A0E117")
Optional("5B3A3838-BF3E-4DBF-A543-053E227EDFBF")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-21 07:18:55.124 ThaliTest[1221:1554484] BTM: attaching to BTServer
,2016-09-21 07:18:56.254 ThaliTest[1221:1554484] BTM: local device power state changed
2016-09-21 07:18:56.257 ThaliTest[1221:1554484] BTM: power is now off
,2016-09-21 07:18:57.022 ThaliTest[1221:1554484] BTM: local device power state changed
2016-09-21 07:18:57.023 ThaliTest[1221:1554484] BTM: power is now on
,*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  56
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  16.37273800373077
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
