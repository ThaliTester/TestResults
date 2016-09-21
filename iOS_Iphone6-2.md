#### Test 85046911c074ee1_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911c074ee1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/9721FC3F-B59A-4066-B141-9BD823A0A3E4/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/9721FC3F-B59A-4066-B141-9BD823A0A3E4/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911c074ee1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911c074ee1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/6AA74B96-80CA-45D4-BF71-82FD3B80C55A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56626"
,(lldb)     command script import "/tmp/9721FC3F-B59A-4066-B141-9BD823A0A3E4/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 04:39:31.732 ThaliTest[1197:1539681] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5CA073C1-9422-4CD0-8AD8-48586E80B6E1/Library/Cookies/Cookies.binarycookies
,2016-09-21 04:39:31.923 ThaliTest[1197:1539681] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 04:39:31.924 ThaliTest[1197:1539681] Multi-tasking -> Device: YES, App: YES
,2016-09-21 04:39:31.943 ThaliTest[1197:1539681] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 04:39:32.366 ThaliTest[1197:1539681] Using UIWebView
,2016-09-21 04:39:32.374 ThaliTest[1197:1539681] [CDVTimer][handleopenurl] 0.373006ms
,2016-09-21 04:39:32.382 ThaliTest[1197:1539681] [CDVTimer][intentandnavigationfilter] 7.376969ms
2016-09-21 04:39:32.383 ThaliTest[1197:1539681] [CDVTimer][gesturehandler] 0.355005ms
2016-09-21 04:39:32.384 ThaliTest[1197:1539681] [CDVTimer][TotalPluginStartup] 10.016024ms
,2016-09-21 04:39:38.225 ThaliTest[1197:1539681] Resetting plugins due to page load.
,2016-09-21 04:39:38.734 ThaliTest[1197:1539681] Finished load of: file:///var/containers/Bundle/Application/6AA74B96-80CA-45D4-BF71-82FD3B80C55A/ThaliTest.app/www/index.html
,2016-09-21 04:39:39.134 ThaliTest[1197:1539681] JXcore Cordova plugin initializing
,2016-09-21 04:39:39.135 ThaliTest[1197:1539920] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 04:39:45.728 ThaliTest[1197:1539920] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-21 04:39:45.728 ThaliTest[1197:1539920] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-21 04:39:45.728 ThaliTest[1197:1539920] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-21 04:39:45.730 ThaliTest[1197:1539920] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 04:39:46.114 ThaliTest[1197:1539920] jxcore: executeNativeTests: success
*Native tests were executed*
Total number of executed tests:  2
,Number of passed tests:  2
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.004330992698669434
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
