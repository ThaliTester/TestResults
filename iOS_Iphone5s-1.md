#### Test 83276082d331142_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83276082d331142/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/168CA1C2-F84C-4A8F-923B-C4E1E1777A9E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/168CA1C2-F84C-4A8F-923B-C4E1E1777A9E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83276082d331142/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83276082d331142/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A2AB3EDD-BA8E-401B-8A85-FE005CAA7FC3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49925"
,(lldb)     command script import "/tmp/168CA1C2-F84C-4A8F-923B-C4E1E1777A9E/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 13:29:16.057 ThaliTest[2349:4886686] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/764BA323-B153-4EC7-A020-B9C35567066A/Library/Cookies/Cookies.binarycookies
,2016-09-15 13:29:16.325 ThaliTest[2349:4886686] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 13:29:16.326 ThaliTest[2349:4886686] Multi-tasking -> Device: YES, App: YES
,2016-09-15 13:29:16.343 ThaliTest[2349:4886686] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 13:29:17.200 ThaliTest[2349:4886686] Using UIWebView
,2016-09-15 13:29:17.204 ThaliTest[2349:4886686] [CDVTimer][handleopenurl] 0.168979ms
2016-09-15 13:29:17.207 ThaliTest[2349:4886686] [CDVTimer][intentandnavigationfilter] 2.609968ms
2016-09-15 13:29:17.207 ThaliTest[2349:4886686] [CDVTimer][gesturehandle,r] 0.124991ms
2016-09-15 13:29:17.207 ThaliTest[2349:4886686] [CDVTimer][TotalPluginStartup] 3.536046ms
,2016-09-15 13:29:20.408 ThaliTest[2349:4886686] Resetting plugins due to page load.
,2016-09-15 13:29:21.758 ThaliTest[2349:4886686] Finished load of: file:///var/mobile/Containers/Bundle/Application/A2AB3EDD-BA8E-401B-8A85-FE005CAA7FC3/ThaliTest.app/www/index.html
,2016-09-15 13:29:21.945 ThaliTest[2349:4886686] JXcore Cordova plugin initializing
,2016-09-15 13:29:21.945 ThaliTest[2349:4886855] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-15 13:29:29.786 ThaliTest[2349:4886855] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-15 13:29:29.787 ThaliTest[2349:4886855] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-15 13:29:29.787 ThaliTest[2349:4,886855] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-09-15 13:29:29.789 ThaliTest[2349:4886855] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,2016-09-15 13:29:30.183 ThaliTest[2349:4886855] jxcore: executeNativeTests: success
Total number of executed tests:  2
Number of passed tests:  2
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.006622016429901123
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
