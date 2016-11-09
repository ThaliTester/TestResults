#### Test 89624796d0595a7_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/89624796d0595a7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/77FC9567-E04D-4B12-AED5-DF5346F97F4F/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/77FC9567-E04D-4B12-AED5-DF5346F97F4F/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/89624796d0595a7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/89624796d0595a7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/3EB6E4E7-12A7-4761-999E-4DD7A9AC08CD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58827"
,(lldb)     command script import "/tmp/77FC9567-E04D-4B12-AED5-DF5346F97F4F/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-09 02:52:59.279 ThaliTest[3197:7160567] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/612ED942-E853-4FF8-AC9A-4D5161931E29/Library/Cookies/Cookies.binarycookies
,2016-11-09 02:52:59.368 ThaliTest[3197:7160567] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-09 02:52:59.371 ThaliTest[3197:7160567] Multi-tasking -> Device: YES, App: YES
,2016-11-09 02:52:59.394 ThaliTest[3197:7160567] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-09 02:52:59.959 ThaliTest[3197:7160567] Using UIWebView
,2016-11-09 02:52:59.971 ThaliTest[3197:7160567] [CDVTimer][handleopenurl] 0.404000ms
,2016-11-09 02:52:59.978 ThaliTest[3197:7160567] [CDVTimer][intentandnavigationfilter] 6.999969ms
2016-11-09 02:52:59.979 ThaliTest[3197:7160567] [CDVTimer][gesturehandler] 0.342965ms
2016-11-09 02:52:59.979 ThaliTest[3197:7160567] [CDVTimer][TotalPluginStartup] 9.481013ms
,2016-11-09 02:53:06.192 ThaliTest[3197:7160567] Resetting plugins due to page load.
,2016-11-09 02:53:06.625 ThaliTest[3197:7160567] Finished load of: file:///var/containers/Bundle/Application/3EB6E4E7-12A7-4761-999E-4DD7A9AC08CD/ThaliTest.app/www/index.html
,2016-11-09 02:53:06.972 ThaliTest[3197:7160567] JXcore Cordova plugin initializing
,2016-11-09 02:53:06.972 ThaliTest[3197:7160748] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-09 10:53:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-09 10:53:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-09 10:53:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-09 10:53:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-09 10:53:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-09 10:53:43 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.63211196660995
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
