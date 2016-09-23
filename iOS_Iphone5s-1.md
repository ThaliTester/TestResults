#### Test 850469114943827_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469114943827/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2D61486D-C57E-47D1-B350-23D20FD6D9C1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/2D61486D-C57E-47D1-B350-23D20FD6D9C1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469114943827/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469114943827/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2B2FF602-AEF9-4EDB-BB00-0C526F2EB21E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63269"
,(lldb)     command script import "/tmp/2D61486D-C57E-47D1-B350-23D20FD6D9C1/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 09:10:20.384 ThaliTest[3021:6113447] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/78BA052E-037D-4ABE-B605-E57DBC4E6467/Library/Cookies/Cookies.binarycookies
,2016-09-23 09:10:20.506 ThaliTest[3021:6113447] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 09:10:20.508 ThaliTest[3021:6113447] Multi-tasking -> Device: YES, App: YES
,2016-09-23 09:10:20.533 ThaliTest[3021:6113447] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 09:10:22.079 ThaliTest[3021:6113447] Using UIWebView
,2016-09-23 09:10:22.087 ThaliTest[3021:6113447] [CDVTimer][handleopenurl] 0.595987ms
,2016-09-23 09:10:22.096 ThaliTest[3021:6113447] [CDVTimer][intentandnavigationfilter] 8.394003ms
2016-09-23 09:10:22.097 ThaliTest[3021:6113447] [CDVTimer][gesturehandler] 0.433028ms
2016-09-23 09:10:22.098 ThaliTest[3021:6113447] [CDVTimer][TotalPluginS,tartup] 11.332989ms
,2016-09-23 09:10:28.232 ThaliTest[3021:6113447] Resetting plugins due to page load.
,2016-09-23 09:10:31.837 ThaliTest[3021:6113447] Finished load of: file:///var/mobile/Containers/Bundle/Application/2B2FF602-AEF9-4EDB-BB00-0C526F2EB21E/ThaliTest.app/www/index.html
,2016-09-23 09:10:32.154 ThaliTest[3021:6113447] JXcore Cordova plugin initializing
,2016-09-23 09:10:32.155 ThaliTest[3021:6113670] JXcore instance initializing
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
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 09:10:41.110 ThaliTest[3021:6113447] BTM: attaching to BTServer
,2016-09-23 09:10:41.794 ThaliTest[3021:6113447] BTM: local device power state changed
2016-09-23 09:10:41.794 ThaliTest[3021:6113447] BTM: power is now on
,2016-09-23 09:10:46.531 ThaliTest[3021:6113447] BTM: local device power state changed
2016-09-23 09:10:46.531 ThaliTest[3021:6113447] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  7
Number of passed tests:  7
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  5.592970967292786
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
