#### Test 82914073f44248e_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073f44248e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/DC67013C-0702-4ED7-8398-209C5D7FEDAD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/DC67013C-0702-4ED7-8398-209C5D7FEDAD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073f44248e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073f44248e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8E3DE57B-193A-4FC3-8F66-D8A223C42077/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57252"
,(lldb)     command script import "/tmp/DC67013C-0702-4ED7-8398-209C5D7FEDAD/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-06 18:55:39.405 ThaliTest[1270:2178524] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8D2530EE-91AB-43A3-8862-04146AA76FE2/Library/Cookies/Cookies.binarycookies
,2016-09-06 18:55:39.863 ThaliTest[1270:2178524] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-06 18:55:39.865 ThaliTest[1270:2178524] Multi-tasking -> Device: YES, App: YES
,2016-09-06 18:55:39.892 ThaliTest[1270:2178524] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-06 18:55:42.156 ThaliTest[1270:2178524] Using UIWebView
,2016-09-06 18:55:42.164 ThaliTest[1270:2178524] [CDVTimer][handleopenurl] 0.625014ms
,2016-09-06 18:55:42.171 ThaliTest[1270:2178524] [CDVTimer][intentandnavigationfilter] 7.305026ms
2016-09-06 18:55:42.172 ThaliTest[1270:2178524] [CDVTimer][gesturehandler] 0.369012ms
2016-09-06 18:55:42.173 ThaliTest[1270:2178524] [CDVTimer][TotalPluginS,tartup] 9.896994ms
,2016-09-06 18:55:49.579 ThaliTest[1270:2178524] Resetting plugins due to page load.
,2016-09-06 18:55:53.692 ThaliTest[1270:2178524] Finished load of: file:///var/mobile/Containers/Bundle/Application/8E3DE57B-193A-4FC3-8F66-D8A223C42077/ThaliTest.app/www/index.html
,2016-09-06 18:55:53.905 ThaliTest[1270:2178524] JXcore Cordova plugin initializing
2016-09-06 18:55:53.906 ThaliTest[1270:2179432] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
Total number of executed tests:  38
Number of passed tests:  38
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  11.88394194841385
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackgroun
```
