#### Test 86453613e903f38_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86453613e903f38/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/FE216263-CBE8-4362-A16C-4A13C1293A98/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/FE216263-CBE8-4362-A16C-4A13C1293A98/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86453613e903f38/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86453613e903f38/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/F041B33E-9651-461D-92E6-53F08148E3B3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58959"
,(lldb)     command script import "/tmp/FE216263-CBE8-4362-A16C-4A13C1293A98/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 23:07:18.115 ThaliTest[1403:1750639] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3234E119-862F-4D62-8A5F-A4F537F1638C/Library/Cookies/Cookies.binarycookies
,2016-09-22 23:07:18.183 ThaliTest[1403:1750639] Apache Cordova native platform version 4.2.1 is starting.
2016-09-22 23:07:18.185 ThaliTest[1403:1750639] Multi-tasking -> Device: YES, App: YES
,2016-09-22 23:07:18.205 ThaliTest[1403:1750639] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 23:07:18.699 ThaliTest[1403:1750639] Using UIWebView
,2016-09-22 23:07:18.706 ThaliTest[1403:1750639] [CDVTimer][handleopenurl] 0.352025ms
,2016-09-22 23:07:18.713 ThaliTest[1403:1750639] [CDVTimer][intentandnavigationfilter] 6.924987ms
2016-09-22 23:07:18.714 ThaliTest[1403:1750639] [CDVTimer][gesturehandler] 0.266016ms
2016-09-22 23:07:18.714 ThaliTest[1403:1750639] [CDVTimer][TotalPluginS,tartup] 9.078026ms
,2016-09-22 23:07:24.348 ThaliTest[1403:1750639] Resetting plugins due to page load.
,2016-09-22 23:07:24.793 ThaliTest[1403:1750639] Finished load of: file:///var/containers/Bundle/Application/F041B33E-9651-461D-92E6-53F08148E3B3/ThaliTest.app/www/index.html
,2016-09-22 23:07:25.131 ThaliTest[1403:1750639] JXcore Cordova plugin initializing
,2016-09-22 23:07:25.133 ThaliTest[1403:1750809] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x14e75e320>
,Optional("80284D33-B300-4BB5-9FE9-6D41BD4BA5AD")
,nil
,nil
,Optional("F3E3574B-14D0-480B-BF61-37F024F940AB")
,Optional("86E65901-C4EE-44B3-AB74-15F9411F6136")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 23:07:47.112 ThaliTest[1403:1750639] BTM: attaching to BTServer
,2016-09-22 23:07:47.804 ThaliTest[1403:1750639] BTM: local device power state changed
2016-09-22 23:07:47.811 ThaliTest[1403:1750639] BTM: power is now on
,2016-09-22 23:07:52.504 ThaliTest[1403:1750639] BTM: local device power state changed
2016-09-22 23:07:52.504 ThaliTest[1403:1750639] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  20.16145998239517
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
