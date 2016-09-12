#### Test 83070177a758936_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83070177a758936/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/005A7B34-A2CB-4DCF-A852-97B721B8827F/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/005A7B34-A2CB-4DCF-A852-97B721B8827F/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83070177a758936/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83070177a758936/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/6EDBCF4B-7660-47E6-94F7-28A8C3F5C001/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56625"
,(lldb)     command script import "/tmp/005A7B34-A2CB-4DCF-A852-97B721B8827F/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-12 04:48:57.876 ThaliTest[494:520865] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C9F9F452-BE2E-4931-8951-DA7BBF5D8F42/Library/Cookies/Cookies.binarycookies
,2016-09-12 04:48:58.466 ThaliTest[494:520865] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-12 04:48:58.469 ThaliTest[494:520865] Multi-tasking -> Device: YES, App: YES
,2016-09-12 04:48:58.506 ThaliTest[494:520865] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-12 04:48:59.139 ThaliTest[494:520865] Using UIWebView
,2016-09-12 04:48:59.147 ThaliTest[494:520865] [CDVTimer][handleopenurl] 0.418007ms
,2016-09-12 04:48:59.158 ThaliTest[494:520865] [CDVTimer][intentandnavigationfilter] 10.018945ms
2016-09-12 04:48:59.159 ThaliTest[494:520865] [CDVTimer][gesturehandler] 0.502050ms
2016-09-12 04:48:59.159 ThaliTest[494:520865] [CDVTimer][TotalPluginStartup] 12.764990ms
,2016-09-12 04:49:07.300 ThaliTest[494:520865] Resetting plugins due to page load.
,2016-09-12 04:49:07.905 ThaliTest[494:520865] Finished load of: file:///var/containers/Bundle/Application/6EDBCF4B-7660-47E6-94F7-28A8C3F5C001/ThaliTest.app/www/index.html
,2016-09-12 04:49:08.390 ThaliTest[494:520865] JXcore Cordova plugin initializing
,2016-09-12 04:49:08.392 ThaliTest[494:521100] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
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
Number of ignored tests:  0
,Total duration:  38.0165039896965
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
