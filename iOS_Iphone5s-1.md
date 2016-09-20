#### Test 832688934d87cf0_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/832688934d87cf0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F7CC0506-DBE6-4C04-A26B-BDE3FBE67C83/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F7CC0506-DBE6-4C04-A26B-BDE3FBE67C83/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/832688934d87cf0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/832688934d87cf0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/50FEFBE1-44C7-4FEE-823C-E77A89E90DCF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59625"
,(lldb)     command script import "/tmp/F7CC0506-DBE6-4C04-A26B-BDE3FBE67C83/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-09-20 14:30:15.522 ThaliTest[2686:5666689] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B9CF5376-7B96-449F-9D8C-96C308641617/Library/Cookies/Cookies.binarycookies
,2016-09-20 14:30:15.649 ThaliTest[2686:5666689] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-20 14:30:15.651 ThaliTest[2686:5666689] Multi-tasking -> Device: YES, App: YES
,2016-09-20 14:30:15.677 ThaliTest[2686:5666689] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-20 14:30:17.390 ThaliTest[2686:5666689] Using UIWebView
,2016-09-20 14:30:17.401 ThaliTest[2686:5666689] [CDVTimer][handleopenurl] 0.428021ms
,2016-09-20 14:30:17.412 ThaliTest[2686:5666689] [CDVTimer][intentandnavigationfilter] 9.902000ms
2016-09-20 14:30:17.413 ThaliTest[2686:5666689] [CDVTimer][gesturehandler] 0.395000ms
2016-09-20 14:30:17.413 ThaliTest[2686:5666689] [CDVTimer][TotalPluginS,tartup] 12.651980ms
,2016-09-20 14:30:23.340 ThaliTest[2686:5666689] Resetting plugins due to page load.
,2016-09-20 14:30:26.848 ThaliTest[2686:5666689] Finished load of: file:///var/mobile/Containers/Bundle/Application/50FEFBE1-44C7-4FEE-823C-E77A89E90DCF/ThaliTest.app/www/index.html
,2016-09-20 14:30:27.182 ThaliTest[2686:5666689] JXcore Cordova plugin initializing
,2016-09-20 14:30:27.183 ThaliTest[2686:5666890] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x15760c510>
,05E48F49-1AC9-4265-A2AD-294B4C459142
,Optional("05E48F49-1AC9-4265-A2AD-294B4C459142")
,nil
,nil
,
,363C367B-F88A-431F-8FE6-8D9CDCAA8E92
,Optional("363C367B-F88A-431F-8FE6-8D9CDCAA8E92")
,F7310E65-88BD-4319-B6DF-68B1BF666B6F
Optional("F7310E65-88BD-4319-B6DF-68B1BF666B6F")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-20 14:30:46.812 ThaliTest[2686:5666689] BTM: attaching to BTServer
,2016-09-20 14:30:47.917 ThaliTest[2686:5666689] BTM: local device power state changed
2016-09-20 14:30:47.917 ThaliTest[2686:5666689] BTM: power is now off
,2016-09-20 14:30:48.608 ThaliTest[2686:5666689] BTM: local device power state changed
2016-09-20 14:30:48.609 ThaliTest[2686:5666689] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  52
Number of passed tests:  52
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  12.691890001297
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
