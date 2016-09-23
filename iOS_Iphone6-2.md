#### Test 864536137cfe9e7_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/864536137cfe9e7/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/11DFBDB1-1B85-406D-AF14-40F776CE4B4A/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/11DFBDB1-1B85-406D-AF14-40F776CE4B4A/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/864536137cfe9e7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/864536137cfe9e7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/AC5FFBC9-C8A7-4EB1-AAC5-6F4D5C8FB358/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57187"
,(lldb)     command script import "/tmp/11DFBDB1-1B85-406D-AF14-40F776CE4B4A/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 22:38:33.878 ThaliTest[1395:1747527] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F648999B-4752-494F-AC8F-8817B39D6AAC/Library/Cookies/Cookies.binarycookies
,2016-09-22 22:38:33.950 ThaliTest[1395:1747527] Apache Cordova native platform version 4.2.1 is starting.
2016-09-22 22:38:33.952 ThaliTest[1395:1747527] Multi-tasking -> Device: YES, App: YES
,2016-09-22 22:38:33.969 ThaliTest[1395:1747527] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 22:38:34.383 ThaliTest[1395:1747527] Using UIWebView
,2016-09-22 22:38:34.394 ThaliTest[1395:1747527] [CDVTimer][handleopenurl] 0.376046ms
,2016-09-22 22:38:34.402 ThaliTest[1395:1747527] [CDVTimer][intentandnavigationfilter] 6.922007ms
2016-09-22 22:38:34.403 ThaliTest[1395:1747527] [CDVTimer][gesturehandler] 0.298977ms
2016-09-22 22:38:34.403 ThaliTest[1395:1747527] [CDVTimer][TotalPluginS,tartup] 9.202003ms
,2016-09-22 22:38:40.034 ThaliTest[1395:1747527] Resetting plugins due to page load.
,2016-09-22 22:38:40.469 ThaliTest[1395:1747527] Finished load of: file:///var/containers/Bundle/Application/AC5FFBC9-C8A7-4EB1-AAC5-6F4D5C8FB358/ThaliTest.app/www/index.html
,2016-09-22 22:38:40.811 ThaliTest[1395:1747527] JXcore Cordova plugin initializing
,2016-09-22 22:38:40.812 ThaliTest[1395:1747708] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x15fa8cb30>
,Optional("7C7C466B-2772-44EB-BB43-6D829D2134BE")
,nil
,nil
,Optional("49208E92-A287-46E2-A600-8FCFB5B0EE1E")
,Optional("A46BD8DD-C28B-4B13-9707-3BD4A2B29557")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 22:39:03.113 ThaliTest[1395:1747527] BTM: attaching to BTServer
,2016-09-22 22:39:03.926 ThaliTest[1395:1747527] BTM: local device power state changed
2016-09-22 22:39:03.938 ThaliTest[1395:1747527] BTM: power is now on
,2016-09-22 22:39:08.638 ThaliTest[1395:1747527] BTM: local device power state changed
2016-09-22 22:39:08.644 ThaliTest[1395:1747527] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  20.58684599399567
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
