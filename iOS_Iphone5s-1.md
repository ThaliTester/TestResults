#### Test 82914073a6a0640_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073a6a0640/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8EE1550A-7B1A-45ED-AEFF-F205A588174A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8EE1550A-7B1A-45ED-AEFF-F205A588174A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073a6a0640/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073a6a0640/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/987B1FE8-8BC3-40EE-B57C-01818BCDE550/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64946"
,(lldb)     command script import "/tmp/8EE1550A-7B1A-45ED-AEFF-F205A588174A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 20:06:45.471 ThaliTest[2262:4774281] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4912E114-BA01-4A34-BE6F-B0CAFE494242/Library/Cookies/Cookies.binarycookies
,2016-09-14 20:06:45.534 ThaliTest[2262:4774281] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 20:06:45.536 ThaliTest[2262:4774281] Multi-tasking -> Device: YES, App: YES
,2016-09-14 20:06:45.553 ThaliTest[2262:4774281] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 20:06:46.390 ThaliTest[2262:4774281] Using UIWebView
,2016-09-14 20:06:46.394 ThaliTest[2262:4774281] [CDVTimer][handleopenurl] 0.187993ms
,2016-09-14 20:06:46.397 ThaliTest[2262:4774281] [CDVTimer][intentandnavigationfilter] 2.892017ms
2016-09-14 20:06:46.397 ThaliTest[2262:4774281] [CDVTimer][gesturehandler] 0.136971ms
2016-09-14 20:06:46.397 ThaliTest[2262:4774281] [CDVTimer][TotalPluginS,tartup] 4.069030ms
,2016-09-14 20:06:49.609 ThaliTest[2262:4774281] Resetting plugins due to page load.
,2016-09-14 20:06:51.201 ThaliTest[2262:4774281] Finished load of: file:///var/mobile/Containers/Bundle/Application/987B1FE8-8BC3-40EE-B57C-01818BCDE550/ThaliTest.app/www/index.html
,2016-09-14 20:06:51.400 ThaliTest[2262:4774281] JXcore Cordova plugin initializing
2016-09-14 20:06:51.401 ThaliTest[2262:4774468] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-14 20:07:00.136 ThaliTest[2262:4774281] BTM: attaching to BTServer
,2016-09-14 20:07:04.685 ThaliTest[2262:4774281] BTM: local device power state changed
2016-09-14 20:07:04.686 ThaliTest[2262:4774281] BTM: power is now off
,2016-09-14 20:07:05.374 ThaliTest[2262:4774281] BTM: local device power state changed
2016-09-14 20:07:05.375 ThaliTest[2262:4774281] BTM: power is now on
,received session: <ThaliCore.Session: 0x1573f1400>
,*Native tests were executed*
Total number of executed tests:  48
,Number of passed tests:  45
,Number of failed tests:  3
Number of ignored tests:  0
,Total duration:  17.47037994861603
Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
