#### Test 9799024461e9bd5_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9799024461e9bd5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/1B8C9826-B1F2-4F05-8358-F129798BAA34/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/1B8C9826-B1F2-4F05-8358-F129798BAA34/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9799024461e9bd5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9799024461e9bd5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/56152A04-16DA-470E-A108-5CEBFD4EB36E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59979"
,(lldb)     command script import "/tmp/1B8C9826-B1F2-4F05-8358-F129798BAA34/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-14 18:11:04.418 ThaliTest[798:1283536] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1DEAA7DD-0535-4C1C-823D-58F7466E806D/Library/Cookies/Cookies.binarycookies
,2016-12-14 18:11:04.538 ThaliTest[798:1283536] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-14 18:11:04.540 ThaliTest[798:1283536] Multi-tasking -> Device: YES, App: YES
,2016-12-14 18:11:04.565 ThaliTest[798:1283536] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-14 18:11:06.002 ThaliTest[798:1283536] Using UIWebView
,2016-12-14 18:11:06.013 ThaliTest[798:1283536] [CDVTimer][handleopenurl] 0.478983ms
,2016-12-14 18:11:06.024 ThaliTest[798:1283536] [CDVTimer][intentandnavigationfilter] 10.273993ms
2016-12-14 18:11:06.025 ThaliTest[798:1283536] [CDVTimer][gesturehandler] 0.380993ms
2016-12-14 18:11:06.025 ThaliTest[798:1283536] [CDVTimer][TotalPluginSta,rtup] 13.101995ms
,2016-12-14 18:11:11.832 ThaliTest[798:1283536] Resetting plugins due to page load.
,2016-12-14 18:11:14.772 ThaliTest[798:1283536] Finished load of: file:///var/mobile/Containers/Bundle/Application/56152A04-16DA-470E-A108-5CEBFD4EB36E/ThaliTest.app/www/index.html
,2016-12-14 18:11:15.071 ThaliTest[798:1283536] JXcore Cordova plugin initializing
,2016-12-14 18:11:15.073 ThaliTest[798:1283725] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-14 17:11:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-14 17:11:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-14 17:11:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-14 17:11:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-14 17:11:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-14 17:11:55 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  26.94735997915268
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
