#### Test 83627337b783869_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337b783869/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/86775709-C676-4A4C-8369-4D42022310EA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/86775709-C676-4A4C-8369-4D42022310EA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337b783869/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337b783869/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EF6184C0-D9BC-4963-9E7F-13B0CBA0E364/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61000"
,(lldb)     command script import "/tmp/86775709-C676-4A4C-8369-4D42022310EA/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 14:43:42.487 ThaliTest[2223:4735705] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7D566210-076D-4B9B-98D5-1EE49EDBF4D7/Library/Cookies/Cookies.binarycookies
,2016-09-14 14:43:42.962 ThaliTest[2223:4735705] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 14:43:42.964 ThaliTest[2223:4735705] Multi-tasking -> Device: YES, App: YES
,2016-09-14 14:43:42.990 ThaliTest[2223:4735705] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 14:43:44.808 ThaliTest[2223:4735705] Using UIWebView
,2016-09-14 14:43:44.818 ThaliTest[2223:4735705] [CDVTimer][handleopenurl] 0.448048ms
,2016-09-14 14:43:44.827 ThaliTest[2223:4735705] [CDVTimer][intentandnavigationfilter] 8.060992ms
2016-09-14 14:43:44.828 ThaliTest[2223:4735705] [CDVTimer][gesturehandler] 0.366032ms
2016-09-14 14:43:44.828 ThaliTest[2223:4735705] [CDVTimer][TotalPluginStartup] 10.658026ms
,2016-09-14 14:43:51.694 ThaliTest[2223:4735705] Resetting plugins due to page load.
,2016-09-14 14:43:55.458 ThaliTest[2223:4735705] Finished load of: file:///var/mobile/Containers/Bundle/Application/EF6184C0-D9BC-4963-9E7F-13B0CBA0E364/ThaliTest.app/www/index.html
,2016-09-14 14:43:55.777 ThaliTest[2223:4735705] JXcore Cordova plugin initializing
2016-09-14 14:43:55.778 ThaliTest[2223:4735931] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-14 14:44:03.859 ThaliTest[2223:4735931] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-14 14:44:03.860 ThaliTest[2223:4735931] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-14 14:44:03.860 ThaliTest[2223:4735931] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-14 14:44:03.862 ThaliTest[2223:4735931] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
