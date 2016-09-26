#### Test 867085185d3628e_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/867085185d3628e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/D66086A7-3202-403F-BF0F-795DB4AA3D31/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/D66086A7-3202-403F-BF0F-795DB4AA3D31/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/867085185d3628e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/867085185d3628e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/AD3DF33D-7BDF-4555-8843-C776D225E5FF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55911"
,(lldb)     command script import "/tmp/D66086A7-3202-403F-BF0F-795DB4AA3D31/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-26 12:32:38.174 ThaliTest[1652:2155184] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4B9C25D2-E0AB-43F7-B06E-EF59DB7210B3/Library/Cookies/Cookies.binarycookies
,2016-09-26 12:32:38.217 ThaliTest[1652:2155184] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-26 12:32:38.218 ThaliTest[1652:2155184] Multi-tasking -> Device: YES, App: YES
,2016-09-26 12:32:38.230 ThaliTest[1652:2155184] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-26 12:32:38.546 ThaliTest[1652:2155184] Using UIWebView
,2016-09-26 12:32:38.550 ThaliTest[1652:2155184] [CDVTimer][handleopenurl] 0.275970ms
,2016-09-26 12:32:38.554 ThaliTest[1652:2155184] [CDVTimer][intentandnavigationfilter] 3.497958ms
2016-09-26 12:32:38.554 ThaliTest[1652:2155184] [CDVTimer][gesturehandler] 0.165999ms
2016-09-26 12:32:38.554 ThaliTest[1652:2155184] [CDVTimer][TotalPluginS,tartup] 4.754007ms
,2016-09-26 12:32:44.932 ThaliTest[1652:2155184] Resetting plugins due to page load.
,2016-09-26 12:32:45.621 ThaliTest[1652:2155184] Finished load of: file:///var/containers/Bundle/Application/AD3DF33D-7BDF-4555-8843-C776D225E5FF/ThaliTest.app/www/index.html
,2016-09-26 12:32:46.037 ThaliTest[1652:2155184] JXcore Cordova plugin initializing
,2016-09-26 12:32:46.038 ThaliTest[1652:2155367] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x156be3740>
,Optional("F90D4265-A124-45BF-96A8-0A92820D65F0")
,nil
,nil
,Optional("8053AB52-208F-4E01-9DBF-CC155843FACD")
,Optional("DFC2C9DA-1AD5-4B2D-B8DC-1EC43430F70B")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  55
Number of passed tests:  55
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  14.54733800888062
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
