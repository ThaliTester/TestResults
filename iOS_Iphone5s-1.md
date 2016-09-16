#### Test 8504691131acdd6_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8504691131acdd6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/032E540A-4778-44F8-B88A-C63188739AE9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/032E540A-4778-44F8-B88A-C63188739AE9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8504691131acdd6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8504691131acdd6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/ED591D66-B75F-40FC-BD1E-A5BB0B68153B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64748"
,(lldb)     command script import "/tmp/032E540A-4778-44F8-B88A-C63188739AE9/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-16 12:16:18.699 ThaliTest[2460:5035034] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C424F803-E396-4E46-9119-8265C3F405A6/Library/Cookies/Cookies.binarycookies
,2016-09-16 12:16:19.153 ThaliTest[2460:5035034] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-16 12:16:19.154 ThaliTest[2460:5035034] Multi-tasking -> Device: YES, App: YES
,2016-09-16 12:16:19.178 ThaliTest[2460:5035034] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-16 12:16:20.891 ThaliTest[2460:5035034] Using UIWebView
,2016-09-16 12:16:20.902 ThaliTest[2460:5035034] [CDVTimer][handleopenurl] 0.473976ms
,2016-09-16 12:16:20.910 ThaliTest[2460:5035034] [CDVTimer][intentandnavigationfilter] 8.121014ms
2016-09-16 12:16:20.911 ThaliTest[2460:5035034] [CDVTimer][gesturehandler] 0.373006ms
2016-09-16 12:16:20.912 ThaliTest[2460:5035034] [CDVTimer][TotalPluginS,tartup] 10.837018ms
,2016-09-16 12:16:26.659 ThaliTest[2460:5035034] Resetting plugins due to page load.
,2016-09-16 12:16:29.498 ThaliTest[2460:5035034] Finished load of: file:///var/mobile/Containers/Bundle/Application/ED591D66-B75F-40FC-BD1E-A5BB0B68153B/ThaliTest.app/www/index.html
,2016-09-16 12:16:29.747 ThaliTest[2460:5035034] JXcore Cordova plugin initializing
,2016-09-16 12:16:29.748 ThaliTest[2460:5035267] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-16 12:16:37.841 ThaliTest[2460:5035267] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-16 12:16:37.842 ThaliTest[2460:5035267] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-16 12:16:37.842 ThaliTest[2460:5035267] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-16 12:16:37.845 ThaliTest[2460:5035267] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-16 12:16:38.239 ThaliTest[2460:5035267] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.00530695915222168
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
