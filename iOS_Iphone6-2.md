#### Test 8291407367fbc55_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8291407367fbc55/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/838A101E-8F24-45A1-BAAE-759D8B4C8A8F/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/838A101E-8F24-45A1-BAAE-759D8B4C8A8F/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8291407367fbc55/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8291407367fbc55/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/CC047B19-7A84-40A3-B7B1-FCE7711B237E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61434"
,(lldb)     command script import "/tmp/838A101E-8F24-45A1-BAAE-759D8B4C8A8F/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 00:40:45.699 ThaliTest[560:613606] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3939646A-11A5-4053-A43D-6050A7870425/Library/Cookies/Cookies.binarycookies
,2016-09-13 00:40:45.885 ThaliTest[560:613606] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 00:40:45.886 ThaliTest[560:613606] Multi-tasking -> Device: YES, App: YES
,2016-09-13 00:40:45.902 ThaliTest[560:613606] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 00:40:46.175 ThaliTest[560:613606] Using UIWebView
,2016-09-13 00:40:46.179 ThaliTest[560:613606] [CDVTimer][handleopenurl] 0.154018ms
,2016-09-13 00:40:46.181 ThaliTest[560:613606] [CDVTimer][intentandnavigationfilter] 2.278030ms
2016-09-13 00:40:46.182 ThaliTest[560:613606] [CDVTimer][gesturehandler] 0.108004ms
2016-09-13 00:40:46.182 ThaliTest[560:613606] [CDVTimer][TotalPluginStartup,] 3.149033ms
,2016-09-13 00:40:49.773 ThaliTest[560:613606] Resetting plugins due to page load.
,2016-09-13 00:40:50.014 ThaliTest[560:613606] Finished load of: file:///var/containers/Bundle/Application/CC047B19-7A84-40A3-B7B1-FCE7711B237E/ThaliTest.app/www/index.html
,2016-09-13 00:40:50.351 ThaliTest[560:613606] JXcore Cordova plugin initializing
2016-09-13 00:40:50.351 ThaliTest[560:613772] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x1643fdf0>
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
*Native tests were executed*
Total number of executed tests:  48
Number of passed tests:  48
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  11.08899801969528
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
