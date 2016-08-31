#### Test 829140733a8c9ab_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/829140733a8c9ab/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/ADF64437-B031-40F4-98C7-1A64EE3A30D5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/ADF64437-B031-40F4-98C7-1A64EE3A30D5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/829140733a8c9ab/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/829140733a8c9ab/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/52006883-4A3E-44DF-B500-069F5429D586/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63342"
,(lldb)     command script import "/tmp/ADF64437-B031-40F4-98C7-1A64EE3A30D5/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-31 15:24:00.850 ThaliTest[934:1292444] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5C89B88A-338F-4EE3-95B9-ABDA9F5EA80F/Library/Cookies/Cookies.binarycookies
,2016-08-31 15:24:01.298 ThaliTest[934:1292444] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-31 15:24:01.300 ThaliTest[934:1292444] Multi-tasking -> Device: YES, App: YES
,2016-08-31 15:24:01.322 ThaliTest[934:1292444] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-31 15:24:03.174 ThaliTest[934:1292444] Using UIWebView
,2016-08-31 15:24:03.182 ThaliTest[934:1292444] [CDVTimer][handleopenurl] 0.437975ms
,2016-08-31 15:24:03.190 ThaliTest[934:1292444] [CDVTimer][intentandnavigationfilter] 7.434964ms
2016-08-31 15:24:03.191 ThaliTest[934:1292444] [CDVTimer][gesturehandler] 0.357032ms
2016-08-31 15:24:03.191 ThaliTest[934:1292444] [CDVTimer][TotalPluginStar,tup] 10.174990ms
,2016-08-31 15:24:10.218 ThaliTest[934:1292444] Resetting plugins due to page load.
,2016-08-31 15:24:13.812 ThaliTest[934:1292444] Finished load of: file:///var/mobile/Containers/Bundle/Application/52006883-4A3E-44DF-B500-069F5429D586/ThaliTest.app/www/index.html
,2016-08-31 15:24:14.035 ThaliTest[934:1292444] JXcore Cordova plugin initializing
2016-08-31 15:24:14.036 ThaliTest[934:1292712] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
Total number of executed tests:  22
Number of passed tests:  22
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  43.13214200735092
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
