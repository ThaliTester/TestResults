#### Test 87116923cb17c22_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/87116923cb17c22/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A4E67ECB-9CCB-40D6-B87A-156235DD0B75/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/A4E67ECB-9CCB-40D6-B87A-156235DD0B75/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/87116923cb17c22/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/87116923cb17c22/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/001E5A97-1918-4E61-B128-0EB41F2F3399/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53784"
,(lldb)     command script import "/tmp/A4E67ECB-9CCB-40D6-B87A-156235DD0B75/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-29 02:18:41.650 ThaliTest[1869:2444677] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FE464002-2BDA-4A7B-A209-85FD2D260404/Library/Cookies/Cookies.binarycookies
,2016-09-29 02:18:41.697 ThaliTest[1869:2444677] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-29 02:18:41.698 ThaliTest[1869:2444677] Multi-tasking -> Device: YES, App: YES
,2016-09-29 02:18:41.713 ThaliTest[1869:2444677] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-29 02:18:42.033 ThaliTest[1869:2444677] Using UIWebView
,2016-09-29 02:18:42.037 ThaliTest[1869:2444677] [CDVTimer][handleopenurl] 0.198007ms
,2016-09-29 02:18:42.040 ThaliTest[1869:2444677] [CDVTimer][intentandnavigationfilter] 3.463030ms
2016-09-29 02:18:42.041 ThaliTest[1869:2444677] [CDVTimer][gesturehandler] 0.158012ms
2016-09-29 02:18:42.041 ThaliTest[1869:2444677] [CDVTimer][TotalPluginS,tartup] 4.716992ms
,2016-09-29 02:18:48.147 ThaliTest[1869:2444677] Resetting plugins due to page load.
,2016-09-29 02:18:48.573 ThaliTest[1869:2444677] Finished load of: file:///var/containers/Bundle/Application/001E5A97-1918-4E61-B128-0EB41F2F3399/ThaliTest.app/www/index.html
,2016-09-29 02:18:48.929 ThaliTest[1869:2444677] JXcore Cordova plugin initializing
,2016-09-29 02:18:48.930 ThaliTest[1869:2444866] JXcore instance initializing
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
,*Native tests were executed*
,Total number of executed tests:  54
,Number of passed tests:  54
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  16.50718003511429
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
