#### Test 83627337140e0c5_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337140e0c5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/75835E1F-134E-47AF-A529-8A53418A40A8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/75835E1F-134E-47AF-A529-8A53418A40A8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337140e0c5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337140e0c5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A62FA5AF-528E-4DF6-B930-5D37CE520769/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59960"
,(lldb)     command script import "/tmp/75835E1F-134E-47AF-A529-8A53418A40A8/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-07 09:04:37.264 ThaliTest[1761:3704238] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/17A20924-EDFB-4A38-BAB0-A53C8D3BF0A8/Library/Cookies/Cookies.binarycookies
,2016-09-07 09:04:37.520 ThaliTest[1761:3704238] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-07 09:04:37.521 ThaliTest[1761:3704238] Multi-tasking -> Device: YES, App: YES
,2016-09-07 09:04:37.538 ThaliTest[1761:3704238] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-07 09:04:38.314 ThaliTest[1761:3704238] Using UIWebView
2016-09-07 09:04:38.317 ThaliTest[1761:3704238] [CDVTimer][handleopenurl] 0.140965ms
2016-09-07 09:04:38.320 ThaliTest[1761:3704238] [CDVTimer][intentandnavigationfilter] 2.613008ms
2016-09-07 09:04:38.320 ThaliTest[1761:3704238] [CDVTimer][gesturehandler] 0.160992ms
2016-09-07 09:04:38.320 ThaliTest[1761:3704238] [CDVTimer][TotalPluginStartup] 3.500998ms
,2016-09-07 09:04:41.284 ThaliTest[1761:3704238] Resetting plugins due to page load.
,2016-09-07 09:04:42.685 ThaliTest[1761:3704238] Finished load of: file:///var/mobile/Containers/Bundle/Application/A62FA5AF-528E-4DF6-B930-5D37CE520769/ThaliTest.app/www/index.html
,2016-09-07 09:04:42.875 ThaliTest[1761:3704238] JXcore Cordova plugin initializing
,2016-09-07 09:04:42.876 ThaliTest[1761:3704408] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-07 09:04:50.766 ThaliTest[1761:3704408] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-07 09:04:50.767 ThaliTest[1761:3704408] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-07 09:04:50.768 ThaliTest[1761:3704408] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-09-07 09:04:50.770 ThaliTest[1761:3704408] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,2016-09-07 09:04:51.170 ThaliTest[1761:3704408] jxcore: executeNativeTests: success
,Total number of executed tests:  2
Number of passed tests:  2
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.003493010997772217
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
