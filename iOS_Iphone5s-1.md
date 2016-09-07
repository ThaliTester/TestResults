#### Test 82914073126c10a_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073126c10a/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/1096B015-8708-4B72-BA3A-7B776E7FA119/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/1096B015-8708-4B72-BA3A-7B776E7FA119/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073126c10a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073126c10a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6C05E39D-5CED-435B-B993-3D06142176DD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55552"
,(lldb)     command script import "/tmp/1096B015-8708-4B72-BA3A-7B776E7FA119/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-07 15:27:55.913 ThaliTest[1820:3746822] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/15CE4F76-EB45-4975-9FAF-5E28A0575982/Library/Cookies/Cookies.binarycookies
,2016-09-07 15:27:56.164 ThaliTest[1820:3746822] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-07 15:27:56.165 ThaliTest[1820:3746822] Multi-tasking -> Device: YES, App: YES
,2016-09-07 15:27:56.186 ThaliTest[1820:3746822] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-07 15:27:56.975 ThaliTest[1820:3746822] Using UIWebView
2016-09-07 15:27:56.978 ThaliTest[1820:3746822] [CDVTimer][handleopenurl] 0.160992ms
2016-09-07 15:27:56.981 ThaliTest[1820:3746822] [CDVTimer][intentandnavigationfilter] 2.581000ms
2016-09,-07 15:27:56.981 ThaliTest[1820:3746822] [CDVTimer][gesturehandler] 0.120044ms
2016-09-07 15:27:56.981 ThaliTest[1820:3746822] [CDVTimer][TotalPluginStartup] 3.441989ms
,2016-09-07 15:27:59.919 ThaliTest[1820:3746822] Resetting plugins due to page load.
,2016-09-07 15:28:01.360 ThaliTest[1820:3746822] Finished load of: file:///var/mobile/Containers/Bundle/Application/6C05E39D-5CED-435B-B993-3D06142176DD/ThaliTest.app/www/index.html
,2016-09-07 15:28:01.548 ThaliTest[1820:3746822] JXcore Cordova plugin initializing
,2016-09-07 15:28:01.549 ThaliTest[1820:3747003] JXcore instance initializing
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
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  38
Number of passed tests:  38
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  12.36688500642776
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
