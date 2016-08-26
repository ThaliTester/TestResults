#### Test 82894682a24f9af_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82894682a24f9af/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/334265C2-50EB-4819-9344-7D16FFEAD911/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/334265C2-50EB-4819-9344-7D16FFEAD911/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82894682a24f9af/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82894682a24f9af/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9E542603-50E6-410E-9BB0-6ABE656CF901/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51616"
,(lldb)     command script import "/tmp/334265C2-50EB-4819-9344-7D16FFEAD911/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 17:35:57.763 ThaliTest[560:597886] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/37515BBC-BAF3-4FD4-A4FA-69C19CC9C422/Library/Cookies/Cookies.binarycookies
,2016-08-26 17:35:58.163 ThaliTest[560:597886] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 17:35:58.164 ThaliTest[560:597886] Multi-tasking -> Device: YES, App: YES
,2016-08-26 17:35:58.187 ThaliTest[560:597886] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 17:36:00.100 ThaliTest[560:597886] Using UIWebView
,2016-08-26 17:36:00.105 ThaliTest[560:597886] [CDVTimer][handleopenurl] 0.319004ms
,2016-08-26 17:36:00.110 ThaliTest[560:597886] [CDVTimer][intentandnavigationfilter] 5.052984ms
2016-08-26 17:36:00.111 ThaliTest[560:597886] [CDVTimer][gesturehandler] 0.225008ms
2016-08-26 17:36:00.111 ThaliTest[560:597886] [CDVTimer][TotalPluginStartup] 6.677985ms
,2016-08-26 17:36:06.526 ThaliTest[560:597886] Resetting plugins due to page load.
,2016-08-26 17:36:09.515 ThaliTest[560:597886] Finished load of: file:///var/mobile/Containers/Bundle/Application/9E542603-50E6-410E-9BB0-6ABE656CF901/ThaliTest.app/www/index.html
,2016-08-26 17:36:09.748 ThaliTest[560:597886] JXcore Cordova plugin initializing
,2016-08-26 17:36:09.749 ThaliTest[560:598125] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","wifi":"on","bluetoothLowEnergy":"off","bluetooth":"off"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
Total number of executed tests:  5
,Number of passed tests:  5
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.00655597448348999
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
