#### Test 83268893665f77c_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83268893665f77c/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CF8CC5DF-B5D2-4060-BC24-04CE0C5B1A85/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/CF8CC5DF-B5D2-4060-BC24-04CE0C5B1A85/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83268893665f77c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83268893665f77c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/918389CC-52B6-4377-80FB-068416C5812C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50208"
,(lldb)     command script import "/tmp/CF8CC5DF-B5D2-4060-BC24-04CE0C5B1A85/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-06 16:54:29.513 ThaliTest[1258:2165377] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F24B540C-4FE8-4516-A403-C7B5026BECE5/Library/Cookies/Cookies.binarycookies
,2016-09-06 16:54:29.961 ThaliTest[1258:2165377] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-06 16:54:29.963 ThaliTest[1258:2165377] Multi-tasking -> Device: YES, App: YES
,2016-09-06 16:54:29.984 ThaliTest[1258:2165377] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-06 16:54:31.664 ThaliTest[1258:2165377] Using UIWebView
,2016-09-06 16:54:31.674 ThaliTest[1258:2165377] [CDVTimer][handleopenurl] 0.613987ms
,2016-09-06 16:54:31.683 ThaliTest[1258:2165377] [CDVTimer][intentandnavigationfilter] 8.345008ms
2016-09-06 16:54:31.684 ThaliTest[1258:2165377] [CDVTimer][gesturehandler] 0.386000ms
2016-09-06 16:54:31.684 ThaliTest[1258:2165377] [CDVTimer][TotalPluginS,tartup] 11.047006ms
,2016-09-06 16:54:37.662 ThaliTest[1258:2165377] Resetting plugins due to page load.
,2016-09-06 16:54:40.222 ThaliTest[1258:2165377] Finished load of: file:///var/mobile/Containers/Bundle/Application/918389CC-52B6-4377-80FB-068416C5812C/ThaliTest.app/www/index.html
,2016-09-06 16:54:40.458 ThaliTest[1258:2165377] JXcore Cordova plugin initializing
,2016-09-06 16:54:40.460 ThaliTest[1258:2165616] JXcore instance initializing
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
,Total number of executed tests:  44
,Number of passed tests:  44
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  12.56106495857239
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
