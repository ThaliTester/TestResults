#### Test 86185956533f65d_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86185956533f65d/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/ECE6C96A-7C87-41CF-84BD-5427CD423D15/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/ECE6C96A-7C87-41CF-84BD-5427CD423D15/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86185956533f65d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86185956533f65d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/ACA65B21-A2ED-4BA0-B9F9-C7D6ADAABADC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53490"
,(lldb)     command script import "/tmp/ECE6C96A-7C87-41CF-84BD-5427CD423D15/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 17:55:37.657 ThaliTest[2897:5327316] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BCB25BF1-1D27-4D1C-97DE-86AEC79C44D3/Library/Cookies/Cookies.binarycookies
,2016-09-21 17:55:37.973 ThaliTest[2897:5327316] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 17:55:37.974 ThaliTest[2897:5327316] Multi-tasking -> Device: YES, App: YES
,2016-09-21 17:55:37.989 ThaliTest[2897:5327316] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 17:55:39.595 ThaliTest[2897:5327316] Using UIWebView
,2016-09-21 17:55:39.604 ThaliTest[2897:5327316] [CDVTimer][handleopenurl] 0.353038ms
,2016-09-21 17:55:39.611 ThaliTest[2897:5327316] [CDVTimer][intentandnavigationfilter] 6.843030ms
,2016-09-21 17:55:39.612 ThaliTest[2897:5327316] [CDVTimer][gesturehandler] 0.325978ms
,2016-09-21 17:55:39.612 ThaliTest[2897:5327316] [CDVTimer][TotalPluginStartup] 9.128034ms
,2016-09-21 17:55:46.053 ThaliTest[2897:5327316] Resetting plugins due to page load.
,2016-09-21 17:55:49.118 ThaliTest[2897:5327316] Finished load of: file:///var/mobile/Containers/Bundle/Application/ACA65B21-A2ED-4BA0-B9F9-C7D6ADAABADC/ThaliTest.app/www/index.html
,2016-09-21 17:55:49.337 ThaliTest[2897:5327316] JXcore Cordova plugin initializing
,2016-09-21 17:55:49.338 ThaliTest[2897:5327569] JXcore instance initializing
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
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-21 17:55:55.975 ThaliTest[2897:5327316] BTM: attaching to BTServer
,2016-09-21 17:55:56.783 ThaliTest[2897:5327316] BTM: local device power state changed
2016-09-21 17:55:56.783 ThaliTest[2897:5327316] BTM: power is now on
,2016-09-21 17:56:01.449 ThaliTest[2897:5327316] BTM: local device power state changed
2016-09-21 17:56:01.450 ThaliTest[2897:5327316] BTM: power is now off
,received session: <ThaliCore.Session: 0x14a6ab5d0>
,Optional("9BE1EE5D-9BFB-492E-ACD3-CB090891C12E")
,nil
,nil
,Optional("6807C825-6DAC-4019-B8BB-DA0950BD5604")
,Optional("2D484C05-4BEE-4BD9-9C03-BE77DA51E8D8")
,*Native tests were executed*
Total number of executed tests:  50
,Number of passed tests:  50
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.98337894678116
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
