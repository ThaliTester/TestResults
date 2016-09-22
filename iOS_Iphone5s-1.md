#### Test 85046911906f2db_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911906f2db/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CDDDC1ED-F06A-4E4E-9A99-C6A049322C9A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/CDDDC1ED-F06A-4E4E-9A99-C6A049322C9A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911906f2db/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911906f2db/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/143F0240-38C6-4DEF-91C0-ED33389BD6FC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51263"
,(lldb)     command script import "/tmp/CDDDC1ED-F06A-4E4E-9A99-C6A049322C9A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 08:58:43.868 ThaliTest[2858:5938883] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/585AC3D5-F1E8-432D-9E57-FF4C50E020AF/Library/Cookies/Cookies.binarycookies
,2016-09-22 08:58:44.282 ThaliTest[2858:5938883] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 08:58:44.283 ThaliTest[2858:5938883] Multi-tasking -> Device: YES, App: YES
,2016-09-22 08:58:44.303 ThaliTest[2858:5938883] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 08:58:45.932 ThaliTest[2858:5938883] Using UIWebView
,2016-09-22 08:58:45.940 ThaliTest[2858:5938883] [CDVTimer][handleopenurl] 0.647008ms
,2016-09-22 08:58:45.949 ThaliTest[2858:5938883] [CDVTimer][intentandnavigationfilter] 7.955968ms
2016-09-22 08:58:45.950 ThaliTest[2858:5938883] [CDVTimer][gesturehandler] 0.427008ms
2016-09-22 08:58:45.950 ThaliTest[2858:5938883] [CDVTimer][TotalPluginS,tartup] 10.890961ms
,2016-09-22 08:58:51.640 ThaliTest[2858:5938883] Resetting plugins due to page load.
,2016-09-22 08:58:54.925 ThaliTest[2858:5938883] Finished load of: file:///var/mobile/Containers/Bundle/Application/143F0240-38C6-4DEF-91C0-ED33389BD6FC/ThaliTest.app/www/index.html
,2016-09-22 08:58:55.174 ThaliTest[2858:5938883] JXcore Cordova plugin initializing
,2016-09-22 08:58:55.175 ThaliTest[2858:5939155] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,2016-09-22 08:59:03.341 ThaliTest[2858:5939155] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-22 08:59:03.342 ThaliTest[2858:5939155] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-22 08:59:03.342 ThaliTest[2858:5939155] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-22 08:59:03.345 ThaliTest[2858:5939155] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-22 08:59:03.736 ThaliTest[2858:5939155] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.007250010967254639
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
