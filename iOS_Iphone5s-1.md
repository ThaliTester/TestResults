#### Test 850469116954903_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469116954903/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/622ADE09-FFA5-4475-BF02-5E3965B37CF2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/622ADE09-FFA5-4475-BF02-5E3965B37CF2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469116954903/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469116954903/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F0B47F77-30AC-44CA-9440-E00ECFD8193C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60493"
,(lldb)     command script import "/tmp/622ADE09-FFA5-4475-BF02-5E3965B37CF2/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 08:23:26.344 ThaliTest[3005:6106025] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/88EDCE4B-C210-471F-9990-E1F9DF63DF39/Library/Cookies/Cookies.binarycookies
,2016-09-23 08:23:26.462 ThaliTest[3005:6106025] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 08:23:26.464 ThaliTest[3005:6106025] Multi-tasking -> Device: YES, App: YES
,2016-09-23 08:23:26.489 ThaliTest[3005:6106025] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 08:23:27.930 ThaliTest[3005:6106025] Using UIWebView
,2016-09-23 08:23:27.938 ThaliTest[3005:6106025] [CDVTimer][handleopenurl] 0.602007ms
,2016-09-23 08:23:27.947 ThaliTest[3005:6106025] [CDVTimer][intentandnavigationfilter] 8.305013ms
2016-09-23 08:23:27.948 ThaliTest[3005:6106025] [CDVTimer][gesturehandler] 0.391006ms
2016-09-23 08:23:27.948 ThaliTest[3005:6106025] [CDVTimer][TotalPluginStartup] 11.188030ms
,2016-09-23 08:23:33.701 ThaliTest[3005:6106025] Resetting plugins due to page load.
,2016-09-23 08:23:37.285 ThaliTest[3005:6106025] Finished load of: file:///var/mobile/Containers/Bundle/Application/F0B47F77-30AC-44CA-9440-E00ECFD8193C/ThaliTest.app/www/index.html
,2016-09-23 08:23:37.598 ThaliTest[3005:6106025] JXcore Cordova plugin initializing
,2016-09-23 08:23:37.599 ThaliTest[3005:6106246] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x14fd155b0>
,Optional("F79BE896-82B2-4BE8-A87D-A649B0D0169D")
,nil
,nil
,Optional("10CFA2D7-5D83-4828-93C7-393507D268ED")
,Optional("4F49A907-9DAB-48DF-9192-8F03BFA5BE7F")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 08:24:02.046 ThaliTest[3005:6106025] BTM: attaching to BTServer
,2016-09-23 08:24:02.748 ThaliTest[3005:6106025] BTM: local device power state changed
,2016-09-23 08:24:02.772 ThaliTest[3005:6106025] BTM: power is now on
,2016-09-23 08:24:07.484 ThaliTest[3005:6106025] BTM: local device power state changed
2016-09-23 08:24:07.484 ThaliTest[3005:6106025] BTM: power is now off
,*Native tests were executed*
,Total number of executed tests:  50
,Number of passed tests:  50
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  21.12862199544907
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
