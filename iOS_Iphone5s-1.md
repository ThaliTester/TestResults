#### Test 8504691185ffef1_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8504691185ffef1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F94DD5C0-2CBB-4EC0-AA1B-480E72973951/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F94DD5C0-2CBB-4EC0-AA1B-480E72973951/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8504691185ffef1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8504691185ffef1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BE9E4196-72D1-4FFC-B522-2CA990EB23EE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59010"
,(lldb)     command script import "/tmp/F94DD5C0-2CBB-4EC0-AA1B-480E72973951/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-19 14:36:36.312 ThaliTest[2592:5505115] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E9BACA21-051B-4D2F-8EEF-39DDAC0733FC/Library/Cookies/Cookies.binarycookies
,2016-09-19 14:36:36.829 ThaliTest[2592:5505115] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-19 14:36:36.831 ThaliTest[2592:5505115] Multi-tasking -> Device: YES, App: YES
,2016-09-19 14:36:36.857 ThaliTest[2592:5505115] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-19 14:36:38.791 ThaliTest[2592:5505115] Using UIWebView
,2016-09-19 14:36:38.802 ThaliTest[2592:5505115] [CDVTimer][handleopenurl] 0.569046ms
,2016-09-19 14:36:38.811 ThaliTest[2592:5505115] [CDVTimer][intentandnavigationfilter] 7.898033ms
2016-09-19 14:36:38.812 ThaliTest[2592:5505115] [CDVTimer][gesturehandler] 0.401020ms
2016-09-19 14:36:38.812 ThaliTest[2592:5505115] [CDVTimer][TotalPluginStartup] 10.730028ms
,2016-09-19 14:36:45.974 ThaliTest[2592:5505115] Resetting plugins due to page load.
,2016-09-19 14:36:49.730 ThaliTest[2592:5505115] Finished load of: file:///var/mobile/Containers/Bundle/Application/BE9E4196-72D1-4FFC-B522-2CA990EB23EE/ThaliTest.app/www/index.html
,2016-09-19 14:36:49.984 ThaliTest[2592:5505115] JXcore Cordova plugin initializing
,2016-09-19 14:36:49.985 ThaliTest[2592:5505365] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-19 14:36:58.228 ThaliTest[2592:5505365] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-19 14:36:58.229 ThaliTest[2592:5505365] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-19 14:36:58.230 ThaliTest[2592:5505365] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-19 14:36:58.232 ThaliTest[2592:5505365] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-19 14:36:58.624 ThaliTest[2592:5505365] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
Number of passed tests:  2
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003297984600067139
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
