#### Test 850469116a90ff6_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469116a90ff6/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/81EB717A-646D-4BF3-A186-41E4BB87BA29/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/81EB717A-646D-4BF3-A186-41E4BB87BA29/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469116a90ff6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469116a90ff6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/EDDE7DE9-4635-4363-8E8B-32E5783224BC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50045"
,(lldb)     command script import "/tmp/81EB717A-646D-4BF3-A186-41E4BB87BA29/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-09-19 22:34:03.454 ThaliTest[1076:1393445] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B8B41AD7-6D91-44B3-9B1F-550CA5DCCD5E/Library/Cookies/Cookies.binarycookies
,2016-09-19 22:34:03.751 ThaliTest[1076:1393445] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-19 22:34:03.753 ThaliTest[1076:1393445] Multi-tasking -> Device: YES, App: YES
,2016-09-19 22:34:03.779 ThaliTest[1076:1393445] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-19 22:34:04.291 ThaliTest[1076:1393445] Using UIWebView
,2016-09-19 22:34:04.297 ThaliTest[1076:1393445] [CDVTimer][handleopenurl] 0.387967ms
,2016-09-19 22:34:04.305 ThaliTest[1076:1393445] [CDVTimer][intentandnavigationfilter] 7.458031ms
2016-09-19 22:34:04.306 ThaliTest[1076:1393445] [CDVTimer][gesturehandler] 0.334978ms
2016-09-19 22:34:04.306 ThaliTest[1076:1393445] [CDVTimer][TotalPluginStartup] 10.125995ms
,2016-09-19 22:34:09.981 ThaliTest[1076:1393445] Resetting plugins due to page load.
,2016-09-19 22:34:10.487 ThaliTest[1076:1393445] Finished load of: file:///var/containers/Bundle/Application/EDDE7DE9-4635-4363-8E8B-32E5783224BC/ThaliTest.app/www/index.html
,2016-09-19 22:34:10.837 ThaliTest[1076:1393445] JXcore Cordova plugin initializing
,2016-09-19 22:34:10.838 ThaliTest[1076:1393629] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-19 22:34:17.475 ThaliTest[1076:1393629] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-19 22:34:17.476 ThaliTest[1076:1393629] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-19 22:34:17.476 ThaliTest[1076:1393629] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-19 22:34:17.478 ThaliTest[1076:1393629] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-19 22:34:17.883 ThaliTest[1076:1393629] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.004076004028320312
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
