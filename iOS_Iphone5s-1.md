#### Test 82914073d0f9b46_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073d0f9b46/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/59E31619-40E5-4616-99D4-AD0F50445BB5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/59E31619-40E5-4616-99D4-AD0F50445BB5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073d0f9b46/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073d0f9b46/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F36EF632-2DFE-40E1-AFCB-0A4BA4D1ADA4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57453"
,(lldb)     command script import "/tmp/59E31619-40E5-4616-99D4-AD0F50445BB5/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-06 19:14:38.630 ThaliTest[1719:3621366] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/972B889E-2C05-4084-B25B-36B5D5C7F367/Library/Cookies/Cookies.binarycookies
,2016-09-06 19:14:38.888 ThaliTest[1719:3621366] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-06 19:14:38.889 ThaliTest[1719:3621366] Multi-tasking -> Device: YES, App: YES
,2016-09-06 19:14:38.909 ThaliTest[1719:3621366] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-06 19:14:39.686 ThaliTest[1719:3621366] Using UIWebView
2016-09-06 19:14:39.688 ThaliTest[1719:3621366] [CDVTimer][handleopenurl] 0.159979ms
2016-09-06 19:14:39.691 ThaliTest[1719:3621366] [CDVTimer][intentandnavigationfilter] 2.713025ms
2016-09-06 19:14:39.692 ThaliTest[1719:3621366] [CDVTimer][gesturehandler] 0.137985ms
2016-09-06 19:14:39.692 ThaliTest[1719:3621366] [CDVTimer][TotalPluginStartup] 3.593028ms
,2016-09-06 19:14:42.645 ThaliTest[1719:3621366] Resetting plugins due to page load.
,2016-09-06 19:14:44.069 ThaliTest[1719:3621366] Finished load of: file:///var/mobile/Containers/Bundle/Application/F36EF632-2DFE-40E1-AFCB-0A4BA4D1ADA4/ThaliTest.app/www/index.html
,2016-09-06 19:14:44.263 ThaliTest[1719:3621366] JXcore Cordova plugin initializing
,2016-09-06 19:14:44.264 ThaliTest[1719:3621547] JXcore instance initializing
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
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  38
Number of passed tests:  38
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  12.09016197919846
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
