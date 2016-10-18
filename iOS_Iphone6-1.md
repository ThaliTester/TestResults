#### Test 896247960a9c9d6_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/896247960a9c9d6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F5A9CCA2-2704-4476-BC49-FA7CE42D47E3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F5A9CCA2-2704-4476-BC49-FA7CE42D47E3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/896247960a9c9d6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/896247960a9c9d6/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/7145E4E4-801C-49D7-96A8-DFC3B7727667/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65244"
,(lldb)     command script import "/tmp/F5A9CCA2-2704-4476-BC49-FA7CE42D47E3/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-10-18 16:11:59.852 ThaliTest[2428:5088497] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9C4B273C-08A3-4961-AF53-3BCC530F962B/Library/Cookies/Cookies.binarycookies
,2016-10-18 16:11:59.893 ThaliTest[2428:5088497] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-18 16:11:59.894 ThaliTest[2428:5088497] Multi-tasking -> Device: YES, App: YES
,2016-10-18 16:11:59.908 ThaliTest[2428:5088497] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-18 16:12:00.182 ThaliTest[2428:5088497] Using UIWebView
,2016-10-18 16:12:00.185 ThaliTest[2428:5088497] [CDVTimer][handleopenurl] 0.223994ms
,2016-10-18 16:12:00.189 ThaliTest[2428:5088497] [CDVTimer][intentandnavigationfilter] 3.463030ms
2016-10-18 16:12:00.189 ThaliTest[2428:5088497] [CDVTimer][gesturehandler] 0.119984ms
2016-10-18 16:12:00.189 ThaliTest[2428:5088497] [CDVTimer][TotalPluginS,tartup] 4.499972ms
,2016-10-18 16:12:05.034 ThaliTest[2428:5088497] Resetting plugins due to page load.
,2016-10-18 16:12:05.363 ThaliTest[2428:5088497] Finished load of: file:///var/containers/Bundle/Application/7145E4E4-801C-49D7-96A8-DFC3B7727667/ThaliTest.app/www/index.html
,2016-10-18 16:12:05.729 ThaliTest[2428:5088497] JXcore Cordova plugin initializing
,2016-10-18 16:12:05.730 ThaliTest[2428:5088661] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-18 14:12:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-18 14:12:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-18 14:12:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-18 14:12:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-18 14:12:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,Asynchronous wait failed: Exceeded timeout of 15 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,2016-10-18 14:12:55 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  103
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  39.34482300281525
,Failed to execute UT.
,2016-10-18 14:12:55 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
