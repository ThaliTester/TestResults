#### Test 85046911b09b63d_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911b09b63d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CC3EE759-A708-434E-8B24-4A6C4F5B2164/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/CC3EE759-A708-434E-8B24-4A6C4F5B2164/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911b09b63d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911b09b63d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/33C3B55A-1A4F-48ED-963C-137442E79901/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64795"
,(lldb)     command script import "/tmp/CC3EE759-A708-434E-8B24-4A6C4F5B2164/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 09:54:15.495 ThaliTest[3030:6118303] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/23D7807B-8BC0-442F-BA7E-904DDAFB211E/Library/Cookies/Cookies.binarycookies
,2016-09-23 09:54:15.615 ThaliTest[3030:6118303] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 09:54:15.616 ThaliTest[3030:6118303] Multi-tasking -> Device: YES, App: YES
,2016-09-23 09:54:15.638 ThaliTest[3030:6118303] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 09:54:17.229 ThaliTest[3030:6118303] Using UIWebView
,2016-09-23 09:54:17.241 ThaliTest[3030:6118303] [CDVTimer][handleopenurl] 0.531971ms
,2016-09-23 09:54:17.250 ThaliTest[3030:6118303] [CDVTimer][intentandnavigationfilter] 8.530021ms
2016-09-23 09:54:17.251 ThaliTest[3030:6118303] [CDVTimer][gesturehandler] 0.366032ms
2016-09-23 09:54:17.252 ThaliTest[3030:6118303] [CDVTimer][TotalPluginS,tartup] 12.098968ms
,2016-09-23 09:54:23.115 ThaliTest[3030:6118303] Resetting plugins due to page load.
,2016-09-23 09:54:26.629 ThaliTest[3030:6118303] Finished load of: file:///var/mobile/Containers/Bundle/Application/33C3B55A-1A4F-48ED-963C-137442E79901/ThaliTest.app/www/index.html
,2016-09-23 09:54:26.931 ThaliTest[3030:6118303] JXcore Cordova plugin initializing
,2016-09-23 09:54:26.932 ThaliTest[3030:6118511] JXcore instance initializing
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
,2016-09-23 09:54:35.998 ThaliTest[3030:6118303] BTM: attaching to BTServer
,2016-09-23 09:54:36.688 ThaliTest[3030:6118303] BTM: local device power state changed
2016-09-23 09:54:36.688 ThaliTest[3030:6118303] BTM: power is now on
,2016-09-23 09:54:41.428 ThaliTest[3030:6118303] BTM: local device power state changed
2016-09-23 09:54:41.428 ThaliTest[3030:6118303] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  7
Number of passed tests:  7
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  5.610505998134613
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
