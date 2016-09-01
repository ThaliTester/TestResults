#### Test 83268893751f823_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83268893751f823/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/0238515F-4EF2-49E6-8CF1-5F3F277E6D7C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0238515F-4EF2-49E6-8CF1-5F3F277E6D7C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/83268893751f823/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83268893751f823/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0CE3EFDE-E8A6-4AFC-B428-4F513ECF72F8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49846"
,(lldb)     command script import "/tmp/0238515F-4EF2-49E6-8CF1-5F3F277E6D7C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-01 18:47:41.319 ThaliTest[1449:2881144] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1AE3BB4C-121F-45EF-9ED6-B257731D3E87/Library/Cookies/Cookies.binarycookies
,2016-09-01 18:47:41.748 ThaliTest[1449:2881144] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-01 18:47:41.750 ThaliTest[1449:2881144] Multi-tasking -> Device: YES, App: YES
,2016-09-01 18:47:41.776 ThaliTest[1449:2881144] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-01 18:47:43.384 ThaliTest[1449:2881144] Using UIWebView
,2016-09-01 18:47:43.392 ThaliTest[1449:2881144] [CDVTimer][handleopenurl] 0.477016ms
,2016-09-01 18:47:43.401 ThaliTest[1449:2881144] [CDVTimer][intentandnavigationfilter] 8.038998ms
2016-09-01 18:47:43.402 ThaliTest[1449:2881144] [CDVTimer][gesturehandler] 0.387967ms
2016-09-01 18:47:43.402 ThaliTest[1449:2881144] [CDVTimer][TotalPluginStartup] 10.890007ms
,2016-09-01 18:47:49.528 ThaliTest[1449:2881144] Resetting plugins due to page load.
,2016-09-01 18:47:52.486 ThaliTest[1449:2881144] Finished load of: file:///var/mobile/Containers/Bundle/Application/0CE3EFDE-E8A6-4AFC-B428-4F513ECF72F8/ThaliTest.app/www/index.html
,2016-09-01 18:47:52.718 ThaliTest[1449:2881144] JXcore Cordova plugin initializing
,2016-09-01 18:47:52.719 ThaliTest[1449:2881370] JXcore instance initializing
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
Total number of executed tests:  25
Number of passed tests:  25
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  42.43729603290558
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
