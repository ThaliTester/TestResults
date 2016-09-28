#### Test 871169230429d0a_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/871169230429d0a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/EB827D28-9710-45C6-AC54-979106B0C03E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/EB827D28-9710-45C6-AC54-979106B0C03E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/871169230429d0a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/871169230429d0a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0DD8542C-6200-4F0B-AB7E-AB2F7274343F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55499"
,(lldb)     command script import "/tmp/EB827D28-9710-45C6-AC54-979106B0C03E/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-28 16:41:05.830 ThaliTest[3458:6973493] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2DFCCF45-3F2D-4166-B9EE-51D8B718020F/Library/Cookies/Cookies.binarycookies
,2016-09-28 16:41:06.494 ThaliTest[3458:6973493] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-28 16:41:06.496 ThaliTest[3458:6973493] Multi-tasking -> Device: YES, App: YES
,2016-09-28 16:41:06.517 ThaliTest[3458:6973493] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-28 16:41:08.123 ThaliTest[3458:6973493] Using UIWebView
,2016-09-28 16:41:08.132 ThaliTest[3458:6973493] [CDVTimer][handleopenurl] 0.476003ms
,2016-09-28 16:41:08.141 ThaliTest[3458:6973493] [CDVTimer][intentandnavigationfilter] 7.992029ms
2016-09-28 16:41:08.142 ThaliTest[3458:6973493] [CDVTimer][gesturehandler] 0.356972ms
2016-09-28 16:41:08.143 ThaliTest[3458:6973493] [CDVTimer][TotalPluginS,tartup] 11.752963ms
,2016-09-28 16:41:14.072 ThaliTest[3458:6973493] Resetting plugins due to page load.
,2016-09-28 16:41:16.850 ThaliTest[3458:6973493] Finished load of: file:///var/mobile/Containers/Bundle/Application/0DD8542C-6200-4F0B-AB7E-AB2F7274343F/ThaliTest.app/www/index.html
,2016-09-28 16:41:17.179 ThaliTest[3458:6973493] JXcore Cordova plugin initializing
,2016-09-28 16:41:17.180 ThaliTest[3458:6973723] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  54
Number of passed tests:  54
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  17.67514103651047
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
