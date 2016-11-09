#### Test 89624796ae60baf_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/89624796ae60baf/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C74844FE-DB1E-4A31-BD01-205790A4BB13/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/C74844FE-DB1E-4A31-BD01-205790A4BB13/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/89624796ae60baf/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/89624796ae60baf/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2586F840-2403-4B38-986C-F78F1866F73C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62962"
,(lldb)     command script import "/tmp/C74844FE-DB1E-4A31-BD01-205790A4BB13/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-11-09 15:17:01.801 ThaliTest[5430:13668609] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5F7B1547-DCCD-46DF-A2A2-E49DD8E9DE71/Library/Cookies/Cookies.binarycookies
,2016-11-09 15:17:01.862 ThaliTest[5430:13668609] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-09 15:17:01.864 ThaliTest[5430:13668609] Multi-tasking -> Device: YES, App: YES
,2016-11-09 15:17:01.884 ThaliTest[5430:13668609] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-09 15:17:02.657 ThaliTest[5430:13668609] Using UIWebView
2016-11-09 15:17:02.660 ThaliTest[5430:13668609] [CDVTimer][handleopenurl] 0.223994ms
,2016-11-09 15:17:02.665 ThaliTest[5430:13668609] [CDVTimer][intentandnavigationfilter] 5.033016ms
2016-11-09 15:17:02.666 ThaliTest[5430:13668609] [CDVTimer][gesturehandler] 0.150979ms
2016-11-09 15:17:02.666 ThaliTest[5430:13668609] [CDVTimer][TotalPlug,inStartup] 6.368995ms
,2016-11-09 15:17:05.694 ThaliTest[5430:13668609] Resetting plugins due to page load.
,2016-11-09 15:17:07.283 ThaliTest[5430:13668609] Finished load of: file:///var/mobile/Containers/Bundle/Application/2586F840-2403-4B38-986C-F78F1866F73C/ThaliTest.app/www/index.html
,2016-11-09 15:17:07.473 ThaliTest[5430:13668609] JXcore Cordova plugin initializing
2016-11-09 15:17:07.473 ThaliTest[5430:13668769] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-09 14:17:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-09 14:17:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-09 14:17:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-09 14:17:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-09 14:17:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-09 14:17:43 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  23.34218794107437
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
