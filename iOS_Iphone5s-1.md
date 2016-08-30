#### Test 832688932759c28_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/832688932759c28/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8D80C263-40B9-4CEE-A29C-90327FA8FD92/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8D80C263-40B9-4CEE-A29C-90327FA8FD92/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/832688932759c28/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/832688932759c28/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/372D2A2C-8195-4A8E-B8D8-7DB9C998C2C5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56367"
,(lldb)     command script import "/tmp/8D80C263-40B9-4CEE-A29C-90327FA8FD92/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 16:51:48.089 ThaliTest[1275:2566910] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AD4E51B5-4B65-4A2A-A0BB-A7FFF63788EB/Library/Cookies/Cookies.binarycookies
,2016-08-30 16:51:48.550 ThaliTest[1275:2566910] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 16:51:48.552 ThaliTest[1275:2566910] Multi-tasking -> Device: YES, App: YES
,2016-08-30 16:51:48.578 ThaliTest[1275:2566910] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 16:51:50.280 ThaliTest[1275:2566910] Using UIWebView
,2016-08-30 16:51:50.288 ThaliTest[1275:2566910] [CDVTimer][handleopenurl] 0.443995ms
,2016-08-30 16:51:50.297 ThaliTest[1275:2566910] [CDVTimer][intentandnavigationfilter] 8.322001ms
2016-08-30 16:51:50.298 ThaliTest[1275:2566910] [CDVTimer][gesturehandler] 0.375032ms
2016-08-30 16:51:50.298 ThaliTest[1275:2566910] [CDVTimer][TotalPluginS,tartup] 11.105001ms
,2016-08-30 16:51:56.148 ThaliTest[1275:2566910] Resetting plugins due to page load.
,2016-08-30 16:51:58.990 ThaliTest[1275:2566910] Finished load of: file:///var/mobile/Containers/Bundle/Application/372D2A2C-8195-4A8E-B8D8-7DB9C998C2C5/ThaliTest.app/www/index.html
,2016-08-30 16:51:59.234 ThaliTest[1275:2566910] JXcore Cordova plugin initializing
,2016-08-30 16:51:59.235 ThaliTest[1275:2567160] JXcore instance initializing
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
Total number of executed tests:  22
Number of passed tests:  22
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  43.2981830239296
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered

```
