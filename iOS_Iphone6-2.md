#### Test 829140738685e0d_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/829140738685e0d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/883C853F-965E-4001-BA71-8A18FED7A0EE/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/883C853F-965E-4001-BA71-8A18FED7A0EE/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/829140738685e0d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/829140738685e0d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/99A46B7F-0409-4668-875F-A75CF71F4CA6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52339"
,(lldb)     command script import "/tmp/883C853F-965E-4001-BA71-8A18FED7A0EE/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 04:56:44.297 ThaliTest[836:878710] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/93D77A0E-AC46-4A3A-8AAB-AEFE57CA9EA2/Library/Cookies/Cookies.binarycookies
,2016-09-15 04:56:44.334 ThaliTest[836:878710] Apache Cordova native platform version 4.1.1 is starting.
2016-09-15 04:56:44.335 ThaliTest[836:878710] Multi-tasking -> Device: YES, App: YES
,2016-09-15 04:56:44.349 ThaliTest[836:878710] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 04:56:44.674 ThaliTest[836:878710] Using UIWebView
,2016-09-15 04:56:44.680 ThaliTest[836:878710] [CDVTimer][handleopenurl] 0.209033ms
,2016-09-15 04:56:44.684 ThaliTest[836:878710] [CDVTimer][intentandnavigationfilter] 3.784001ms
2016-09-15 04:56:44.684 ThaliTest[836:878710] [CDVTimer][gesturehandler] 0.150979ms
2016-09-15 04:56:44.684 ThaliTest[836:878710] [CDVTimer][TotalPluginStartup,] 5.030990ms
,2016-09-15 04:56:50.587 ThaliTest[836:878710] Resetting plugins due to page load.
,2016-09-15 04:56:50.871 ThaliTest[836:878710] Finished load of: file:///var/containers/Bundle/Application/99A46B7F-0409-4668-875F-A75CF71F4CA6/ThaliTest.app/www/index.html
,2016-09-15 04:56:51.249 ThaliTest[836:878710] JXcore Cordova plugin initializing
,2016-09-15 04:56:51.250 ThaliTest[836:878898] JXcore instance initializing
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
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,2016-09-15 04:56:58.647 ThaliTest[836:878710] BTM: attaching to BTServer
,2016-09-15 04:57:03.225 ThaliTest[836:878710] BTM: local device power state changed
2016-09-15 04:57:03.229 ThaliTest[836:878710] BTM: power is now off
,2016-09-15 04:57:03.998 ThaliTest[836:878710] BTM: local device power state changed
2016-09-15 04:57:04.000 ThaliTest[836:878710] BTM: power is now on
,received session: <ThaliCore.Session: 0x124678df0>
,*Native tests were executed*
Total number of executed tests:  48
Number of passed tests:  48
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  16.11034202575684
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
