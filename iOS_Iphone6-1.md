#### Test 830701775d60530_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/830701775d60530/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/D4351508-BF75-4276-BC7E-53729BF5A3D4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/D4351508-BF75-4276-BC7E-53729BF5A3D4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/830701775d60530/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/830701775d60530/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/89487576-8C00-4F90-B4D2-1729C4AAC9D9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58224"
,(lldb)     command script import "/tmp/D4351508-BF75-4276-BC7E-53729BF5A3D4/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-12 14:40:34.545 ThaliTest[406:481417] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F1914D7E-7D3A-4024-ABAE-6FDF5F862DA1/Library/Cookies/Cookies.binarycookies
,2016-09-12 14:40:34.795 ThaliTest[406:481417] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-12 14:40:34.797 ThaliTest[406:481417] Multi-tasking -> Device: YES, App: YES
,2016-09-12 14:40:34.819 ThaliTest[406:481417] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-12 14:40:35.247 ThaliTest[406:481417] Using UIWebView
,2016-09-12 14:40:35.257 ThaliTest[406:481417] [CDVTimer][handleopenurl] 0.383973ms
,2016-09-12 14:40:35.265 ThaliTest[406:481417] [CDVTimer][intentandnavigationfilter] 7.261992ms
2016-09-12 14:40:35.266 ThaliTest[406:481417] [CDVTimer][gesturehandler] 0.357985ms
2016-09-12 14:40:35.266 ThaliTest[406:481417] [CDVTimer][TotalPluginStartup] 9.607017ms
,2016-09-12 14:40:41.218 ThaliTest[406:481417] Resetting plugins due to page load.
,2016-09-12 14:40:41.481 ThaliTest[406:481417] Finished load of: file:///var/containers/Bundle/Application/89487576-8C00-4F90-B4D2-1729C4AAC9D9/ThaliTest.app/www/index.html
,2016-09-12 14:40:41.818 ThaliTest[406:481417] JXcore Cordova plugin initializing
,2016-09-12 14:40:41.819 ThaliTest[406:481617] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
Total number of executed tests:  16
Number of passed tests:  16
Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  38.53711998462677
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
