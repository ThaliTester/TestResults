#### Test 93371269d9d2d87_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/93371269d9d2d87/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/921DCA31-81A3-4E6D-B22E-538F61EF0347/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/921DCA31-81A3-4E6D-B22E-538F61EF0347/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/93371269d9d2d87/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/93371269d9d2d87/build_ios/ThaliTest.app' (arm64).
,(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/F80C80A3-B27E-4E97-ADDD-FE2C80E14A28/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60536"
,(lldb)     command script import "/tmp/921DCA31-81A3-4E6D-B22E-538F61EF0347/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-15 16:39:20.100 ThaliTest[3469:8893497] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/86517DAF-E70F-45A7-8289-73E25EDC4A2A/Library/Cookies/Cookies.binarycookies
,2016-11-15 16:39:20.181 ThaliTest[3469:8893497] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-15 16:39:20.184 ThaliTest[3469:8893497] Multi-tasking -> Device: YES, App: YES
,2016-11-15 16:39:20.205 ThaliTest[3469:8893497] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-15 16:39:20.824 ThaliTest[3469:8893497] Using UIWebView
2016-11-15 16:39:20.831 ThaliTest[3469:8893497] [CDVTimer][handleopenurl] 0.386000ms
,2016-11-15 16:39:20.842 ThaliTest[3469:8893497] [CDVTimer][intentandnavigationfilter] 10.017991ms
2016-11-15 16:39:20.843 ThaliTest[3469:8893497] [CDVTimer][gesturehandler] 0.450015ms
2016-11-15 16:39:20.843 ThaliTest[3469:8893497] [CDVTimer][TotalPluginStartup] 12.808979ms
,2016-11-15 16:39:27.939 ThaliTest[3469:8893497] Resetting plugins due to page load.
,2016-11-15 16:39:28.553 ThaliTest[3469:8893497] Finished load of: file:///var/containers/Bundle/Application/F80C80A3-B27E-4E97-ADDD-FE2C80E14A28/ThaliTest.app/www/index.html
,2016-11-15 16:39:28.962 ThaliTest[3469:8893497] JXcore Cordova plugin initializing
,2016-11-15 16:39:28.963 ThaliTest[3469:8893695] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-15 15:39:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-15 15:39:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-15 15:39:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-15 15:39:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-15 15:39:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-15 15:40:03 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  23.96393996477127
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
