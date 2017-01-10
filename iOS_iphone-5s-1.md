#### Test 100892963a470a85_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/100892963a470a85/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/0E63F48E-FFDC-4CBB-A797-8333A2EB3F60/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0E63F48E-FFDC-4CBB-A797-8333A2EB3F60/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/100892963a470a85/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/100892963a470a85/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7BDD3830-FA3F-493D-9146-B6B9F6D0B5DE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59210"
,(lldb)     command script import "/tmp/0E63F48E-FFDC-4CBB-A797-8333A2EB3F60/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-10 16:53:04.425 ThaliTest[2206:5233815] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6B896135-4086-4DD6-A7B3-E306E594CF2D/Library/Cookies/Cookies.binarycookies
,2017-01-10 16:53:04.925 ThaliTest[2206:5233815] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-10 16:53:04.927 ThaliTest[2206:5233815] Multi-tasking -> Device: YES, App: YES
,2017-01-10 16:53:04.945 ThaliTest[2206:5233815] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-10 16:53:05.762 ThaliTest[2206:5233815] Using UIWebView
2017-01-10 16:53:05.765 ThaliTest[2206:5233815] [CDVTimer][handleopenurl] 0.163972ms
2017-01-10 16:53:05.770 ThaliTest[2206:5233815] [CDVTimer][intentandnavigationfilter] 4.319966ms
2017-01-10 16:53:05.770 ThaliTest[2206:5233815] [CDVTimer][gesturehandler] 0.135005ms
2017-01-10 16:53:05.770 ThaliTest[2206:5233815] [CDVTimer][TotalPluginStartup] 5.295038ms
,2017-01-10 16:53:08.936 ThaliTest[2206:5233815] Resetting plugins due to page load.
,2017-01-10 16:53:10.419 ThaliTest[2206:5233815] Finished load of: file:///var/mobile/Containers/Bundle/Application/7BDD3830-FA3F-493D-9146-B6B9F6D0B5DE/ThaliTest.app/www/index.html
,2017-01-10 16:53:10.668 ThaliTest[2206:5233815] JXcore Cordova plugin initializing
,2017-01-10 16:53:10.670 ThaliTest[2206:5233996] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-10 15:53:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-10 15:53:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-10 15:53:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2017-01-10 15:53:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-10 15:53:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-10 15:53:48 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
Number of ignored tests:  0
Total duration:  23.26111894845963
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
