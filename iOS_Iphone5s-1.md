#### Test 85046911c074ee1_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911c074ee1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/62EB0749-8200-4A16-8014-B0079F36A609/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/62EB0749-8200-4A16-8014-B0079F36A609/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911c074ee1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911c074ee1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/884B59F3-025C-41A4-BFEB-60F80267E6D5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56624"
,(lldb)     command script import "/tmp/62EB0749-8200-4A16-8014-B0079F36A609/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 13:39:17.227 ThaliTest[2762:5807896] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/75BF2A72-D9A4-4A16-9DC9-093417D8DBAF/Library/Cookies/Cookies.binarycookies
,2016-09-21 13:39:17.500 ThaliTest[2762:5807896] Apache Cordova native platform version 4.2.1 is starting.
2016-09-21 13:39:17.501 ThaliTest[2762:5807896] Multi-tasking -> Device: YES, App: YES
,2016-09-21 13:39:17.520 ThaliTest[2762:5807896] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 13:39:18.328 ThaliTest[2762:5807896] Using UIWebView
,2016-09-21 13:39:18.333 ThaliTest[2762:5807896] [CDVTimer][handleopenurl] 0.177979ms
2016-09-21 13:39:18.336 ThaliTest[2762:5807896] [CDVTimer][intentandnavigationfilter] 2.662003ms
2016-09-21 13:39:18.336 ThaliTest[2762:5807896] [CDVTimer][gesturehandle,r] 0.122011ms
2016-09-21 13:39:18.336 ThaliTest[2762:5807896] [CDVTimer][TotalPluginStartup] 3.574014ms
,2016-09-21 13:39:21.355 ThaliTest[2762:5807896] Resetting plugins due to page load.
,2016-09-21 13:39:22.774 ThaliTest[2762:5807896] Finished load of: file:///var/mobile/Containers/Bundle/Application/884B59F3-025C-41A4-BFEB-60F80267E6D5/ThaliTest.app/www/index.html
,2016-09-21 13:39:22.963 ThaliTest[2762:5807896] JXcore Cordova plugin initializing
2016-09-21 13:39:22.963 ThaliTest[2762:5808075] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 13:39:30.789 ThaliTest[2762:5808075] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-21 13:39:30.790 ThaliTest[2762:5808075] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-21 13:39:30.790 ThaliTest[2762:5808075] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-21 13:39:30.792 ThaliTest[2762:5808075] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 13:39:31.176 ThaliTest[2762:5808075] jxcore: executeNativeTests: success
*Native tests were executed*
Total number of executed tests:  2
Number of passed tests:  2
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.006660997867584229
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
