#### Test 99374565572e946_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99374565572e946/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/11ED5C32-8E1E-453E-AC75-906C6CFF49B3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/11ED5C32-8E1E-453E-AC75-906C6CFF49B3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99374565572e946/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99374565572e946/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8A30D6AA-AA77-4B19-B5DD-077ABFBE2E4F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64637"
,(lldb)     command script import "/tmp/11ED5C32-8E1E-453E-AC75-906C6CFF49B3/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-27 14:15:42.661 ThaliTest[1506:3200554] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9A75D7DD-8006-4E35-98D0-D215ECF6B9B4/Library/Cookies/Cookies.binarycookies
,2016-12-27 14:15:42.771 ThaliTest[1506:3200554] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-27 14:15:42.772 ThaliTest[1506:3200554] Multi-tasking -> Device: YES, App: YES
,2016-12-27 14:15:42.790 ThaliTest[1506:3200554] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-27 14:15:44.324 ThaliTest[1506:3200554] Using UIWebView
,2016-12-27 14:15:44.335 ThaliTest[1506:3200554] [CDVTimer][handleopenurl] 0.427008ms
,2016-12-27 14:15:44.346 ThaliTest[1506:3200554] [CDVTimer][intentandnavigationfilter] 10.087967ms
2016-12-27 14:15:44.347 ThaliTest[1506:3200554] [CDVTimer][gesturehandler] 0.455976ms
2016-12-27 14:15:44.348 ThaliTest[1506:3200554] [CDVTimer][TotalPlugin,Startup] 12.966990ms
,2016-12-27 14:15:50.480 ThaliTest[1506:3200554] Resetting plugins due to page load.
,2016-12-27 14:15:54.147 ThaliTest[1506:3200554] Finished load of: file:///var/mobile/Containers/Bundle/Application/8A30D6AA-AA77-4B19-B5DD-077ABFBE2E4F/ThaliTest.app/www/index.html
,2016-12-27 14:15:54.463 ThaliTest[1506:3200554] JXcore Cordova plugin initializing
,2016-12-27 14:15:54.464 ThaliTest[1506:3200773] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-27 13:16:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-27 13:16:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-27 13:16:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-27 13:16:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-27 13:16:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-27 13:16:32 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.86889398097992
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
