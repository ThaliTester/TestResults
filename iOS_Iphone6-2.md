#### Test 8552588742df921_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8552588742df921/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/3738436E-6B4E-4F4E-8F98-A75EE6976F03/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/3738436E-6B4E-4F4E-8F98-A75EE6976F03/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8552588742df921/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8552588742df921/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/A3BC757C-F7DB-40AF-B053-3A5094114B75/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58564"
,(lldb)     command script import "/tmp/3738436E-6B4E-4F4E-8F98-A75EE6976F03/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-16 01:26:56.844 ThaliTest[914:977672] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0EC0CB0D-BF67-4C1A-8B5F-DA5E43845BCE/Library/Cookies/Cookies.binarycookies
,2016-09-16 01:26:57.035 ThaliTest[914:977672] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-16 01:26:57.036 ThaliTest[914:977672] Multi-tasking -> Device: YES, App: YES
,2016-09-16 01:26:57.054 ThaliTest[914:977672] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-16 01:26:57.445 ThaliTest[914:977672] Using UIWebView
,2016-09-16 01:26:57.454 ThaliTest[914:977672] [CDVTimer][handleopenurl] 0.375986ms
,2016-09-16 01:26:57.461 ThaliTest[914:977672] [CDVTimer][intentandnavigationfilter] 6.266952ms
2016-09-16 01:26:57.462 ThaliTest[914:977672] [CDVTimer][gesturehandler] 0.225008ms
2016-09-16 01:26:57.462 ThaliTest[914:977672] [CDVTimer][TotalPluginStartup] 8.141994ms
,2016-09-16 01:27:03.282 ThaliTest[914:977672] Resetting plugins due to page load.
,2016-09-16 01:27:03.836 ThaliTest[914:977672] Finished load of: file:///var/containers/Bundle/Application/A3BC757C-F7DB-40AF-B053-3A5094114B75/ThaliTest.app/www/index.html
,2016-09-16 01:27:04.236 ThaliTest[914:977672] JXcore Cordova plugin initializing
,2016-09-16 01:27:04.237 ThaliTest[914:977868] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-16 01:27:10.761 ThaliTest[914:977868] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-16 01:27:10.762 ThaliTest[914:977868] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-16 01:27:10.762 ThaliTest[914:977868] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-16 01:27:10.764 ThaliTest[914:977868] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-16 01:27:11.146 ThaliTest[914:977868] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.004185020923614502
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
