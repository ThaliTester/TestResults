#### Test 83070177a758936_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83070177a758936/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/19C1D421-BA80-4AAF-9B56-2304D56F6127/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/19C1D421-BA80-4AAF-9B56-2304D56F6127/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83070177a758936/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83070177a758936/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FCBCA664-78CD-42C1-BB3A-87C39BDC12AC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56620"
,(lldb)     command script import "/tmp/19C1D421-BA80-4AAF-9B56-2304D56F6127/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-12 13:48:32.362 ThaliTest[2030:4423336] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1888D921-9F07-456C-ACE8-0EDA9EBD99CB/Library/Cookies/Cookies.binarycookies
,2016-09-12 13:48:32.639 ThaliTest[2030:4423336] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-12 13:48:32.640 ThaliTest[2030:4423336] Multi-tasking -> Device: YES, App: YES
,2016-09-12 13:48:32.658 ThaliTest[2030:4423336] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-12 13:48:33.454 ThaliTest[2030:4423336] Using UIWebView
2016-09-12 13:48:33.456 ThaliTest[2030:4423336] [CDVTimer][handleopenurl] 0.140011ms
,2016-09-12 13:48:33.460 ThaliTest[2030:4423336] [CDVTimer][intentandnavigationfilter] 3.700972ms
2016-09-12 13:48:33.461 ThaliTest[2030:4423336] [CDVTimer][gesturehandler] 0.135958ms
2016-09-12 13:48:33.461 ThaliTest[2030:4423336] [CDVTimer][TotalPluginS,tartup] 4.604995ms
,2016-09-12 13:48:36.437 ThaliTest[2030:4423336] Resetting plugins due to page load.
,2016-09-12 13:48:37.853 ThaliTest[2030:4423336] Finished load of: file:///var/mobile/Containers/Bundle/Application/FCBCA664-78CD-42C1-BB3A-87C39BDC12AC/ThaliTest.app/www/index.html
,2016-09-12 13:48:38.044 ThaliTest[2030:4423336] JXcore Cordova plugin initializing
2016-09-12 13:48:38.044 ThaliTest[2030:4423509] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
Total number of executed tests:  16
Number of passed tests:  16
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  38.41445100307465
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
