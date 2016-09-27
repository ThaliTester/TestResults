#### Test 85046911aaecdb3_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911aaecdb3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/0319CF8B-E456-4023-AFB7-8141E3EA0950/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0319CF8B-E456-4023-AFB7-8141E3EA0950/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911aaecdb3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911aaecdb3/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9452B547-115B-4186-B3C8-24C862FCF674/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57830"
,(lldb)     command script import "/tmp/0319CF8B-E456-4023-AFB7-8141E3EA0950/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-09-27 09:23:36.251 ThaliTest[3317:6756273] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C35B1BF6-4F5D-431D-8463-C45F7F436147/Library/Cookies/Cookies.binarycookies
,2016-09-27 09:23:36.850 ThaliTest[3317:6756273] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-27 09:23:36.851 ThaliTest[3317:6756273] Multi-tasking -> Device: YES, App: YES
,2016-09-27 09:23:36.868 ThaliTest[3317:6756273] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 09:23:38.345 ThaliTest[3317:6756273] Using UIWebView
,2016-09-27 09:23:38.353 ThaliTest[3317:6756273] [CDVTimer][handleopenurl] 0.513017ms
,2016-09-27 09:23:38.363 ThaliTest[3317:6756273] [CDVTimer][intentandnavigationfilter] 9.395003ms
2016-09-27 09:23:38.364 ThaliTest[3317:6756273] [CDVTimer][gesturehandler] 0.442982ms
2016-09-27 09:23:38.365 ThaliTest[3317:6756273] [CDVTimer][TotalPluginS,tartup] 12.440979ms
,2016-09-27 09:23:44.102 ThaliTest[3317:6756273] Resetting plugins due to page load.
,2016-09-27 09:23:46.930 ThaliTest[3317:6756273] Finished load of: file:///var/mobile/Containers/Bundle/Application/9452B547-115B-4186-B3C8-24C862FCF674/ThaliTest.app/www/index.html
,2016-09-27 09:23:47.182 ThaliTest[3317:6756273] JXcore Cordova plugin initializing
,2016-09-27 09:23:47.184 ThaliTest[3317:6756493] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  12
,Number of passed tests:  12
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.06307601928710938
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
