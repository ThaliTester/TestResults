#### Test 83268893919c9ad_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83268893919c9ad/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E0534F0E-CEB2-4EB1-9CBD-762F3CF4AF00/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E0534F0E-CEB2-4EB1-9CBD-762F3CF4AF00/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83268893919c9ad/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83268893919c9ad/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7F842E31-92C7-4F0B-9844-71BD1A7D2B97/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57923"
,(lldb)     command script import "/tmp/E0534F0E-CEB2-4EB1-9CBD-762F3CF4AF00/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 10:31:53.263 ThaliTest[2892:5953019] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9C26F067-FA54-47C4-8037-9EF7FD402DE9/Library/Cookies/Cookies.binarycookies
,2016-09-22 10:31:53.385 ThaliTest[2892:5953019] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 10:31:53.387 ThaliTest[2892:5953019] Multi-tasking -> Device: YES, App: YES
,2016-09-22 10:31:53.408 ThaliTest[2892:5953019] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 10:31:55.022 ThaliTest[2892:5953019] Using UIWebView
,2016-09-22 10:31:55.030 ThaliTest[2892:5953019] [CDVTimer][handleopenurl] 0.573039ms
,2016-09-22 10:31:55.039 ThaliTest[2892:5953019] [CDVTimer][intentandnavigationfilter] 8.406997ms
2016-09-22 10:31:55.040 ThaliTest[2892:5953019] [CDVTimer][gesturehandler] 0.434995ms
2016-09-22 10:31:55.040 ThaliTest[2892:5953019] [CDVTimer][TotalPluginS,tartup] 11.319995ms
,2016-09-22 10:32:00.748 ThaliTest[2892:5953019] Resetting plugins due to page load.
,2016-09-22 10:32:04.066 ThaliTest[2892:5953019] Finished load of: file:///var/mobile/Containers/Bundle/Application/7F842E31-92C7-4F0B-9844-71BD1A7D2B97/ThaliTest.app/www/index.html
,2016-09-22 10:32:04.370 ThaliTest[2892:5953019] JXcore Cordova plugin initializing
,2016-09-22 10:32:04.372 ThaliTest[2892:5953236] JXcore instance initializing
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
,Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 10:32:13.536 ThaliTest[2892:5953019] BTM: attaching to BTServer
,2016-09-22 10:32:14.196 ThaliTest[2892:5953019] BTM: local device power state changed
2016-09-22 10:32:14.197 ThaliTest[2892:5953019] BTM: power is now on
,2016-09-22 10:32:18.899 ThaliTest[2892:5953019] BTM: local device power state changed
2016-09-22 10:32:18.899 ThaliTest[2892:5953019] BTM: power is now off
,received session: <ThaliCore.Session: 0x1472d7fc0>
,Optional("06D70AF5-C948-4DD7-88F1-033712F029E0")
,nil
,nil
,Optional("E873F11F-D853-464D-A5C8-84ACF101C8E8")
,Optional("455BC117-32F6-4EE2-814C-F2CF46106EFC")
,*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  56
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  19.67876499891281
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
