#### Test 8344405013e13cf_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8344405013e13cf/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/D7619505-2293-41A0-87B2-6EA403A6B59A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/D7619505-2293-41A0-87B2-6EA403A6B59A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8344405013e13cf/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8344405013e13cf/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F2FCFBB2-4A39-47E8-A532-DB19E9AF5E92/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61844"
,(lldb)     command script import "/tmp/D7619505-2293-41A0-87B2-6EA403A6B59A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-31 14:54:12.919 ThaliTest[1350:2703966] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E50F7E87-04B7-4C16-881A-905C0AA799FD/Library/Cookies/Cookies.binarycookies
,2016-08-31 14:54:13.363 ThaliTest[1350:2703966] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-31 14:54:13.364 ThaliTest[1350:2703966] Multi-tasking -> Device: YES, App: YES
,2016-08-31 14:54:13.386 ThaliTest[1350:2703966] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-31 14:54:15.200 ThaliTest[1350:2703966] Using UIWebView
,2016-08-31 14:54:15.208 ThaliTest[1350:2703966] [CDVTimer][handleopenurl] 0.469029ms
,2016-08-31 14:54:15.216 ThaliTest[1350:2703966] [CDVTimer][intentandnavigationfilter] 8.099020ms
2016-08-31 14:54:15.217 ThaliTest[1350:2703966] [CDVTimer][gesturehandler] 0.387013ms
2016-08-31 14:54:15.218 ThaliTest[1350:2703966] [CDVTimer][TotalPluginS,tartup] 10.885000ms
,2016-08-31 14:54:20.894 ThaliTest[1350:2703966] Resetting plugins due to page load.
,2016-08-31 14:54:23.560 ThaliTest[1350:2703966] Finished load of: file:///var/mobile/Containers/Bundle/Application/F2FCFBB2-4A39-47E8-A532-DB19E9AF5E92/ThaliTest.app/www/index.html
,2016-08-31 14:54:23.805 ThaliTest[1350:2703966] JXcore Cordova plugin initializing
,2016-08-31 14:54:23.806 ThaliTest[1350:2704193] JXcore instance initializing
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
Total number of executed tests:  15
Number of passed tests:  15
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  38.56933903694153
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackgroun
```
