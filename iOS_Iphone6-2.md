#### Test 8526390229a14d1_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8526390229a14d1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/1F7F6E8F-59C6-4647-A379-D1D6F1304AE1/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/1F7F6E8F-59C6-4647-A379-D1D6F1304AE1/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8526390229a14d1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8526390229a14d1/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/A367B754-36FA-48FE-B8C2-7E2006873728/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50116"
,(lldb)     command script import "/tmp/1F7F6E8F-59C6-4647-A379-D1D6F1304AE1/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 13:14:59.296 ThaliTest[735:795782] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D095851D-1E9D-4523-B64C-E39DF8490345/Library/Cookies/Cookies.binarycookies
,2016-09-14 13:14:59.334 ThaliTest[735:795782] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 13:14:59.336 ThaliTest[735:795782] Multi-tasking -> Device: YES, App: YES
,2016-09-14 13:14:59.349 ThaliTest[735:795782] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 13:14:59.672 ThaliTest[735:795782] Using UIWebView
,2016-09-14 13:14:59.677 ThaliTest[735:795782] [CDVTimer][handleopenurl] 0.193000ms
,2016-09-14 13:14:59.681 ThaliTest[735:795782] [CDVTimer][intentandnavigationfilter] 3.504992ms
2016-09-14 13:14:59.681 ThaliTest[735:795782] [CDVTimer][gesturehandler] 0.146985ms
2016-09-14 13:14:59.681 ThaliTest[735:795782] [CDVTimer][TotalPluginStartup] 4.679024ms
,2016-09-14 13:15:05.349 ThaliTest[735:795782] Resetting plugins due to page load.
,2016-09-14 13:15:05.840 ThaliTest[735:795782] Finished load of: file:///var/containers/Bundle/Application/A367B754-36FA-48FE-B8C2-7E2006873728/ThaliTest.app/www/index.html
,2016-09-14 13:15:06.312 ThaliTest[735:795782] JXcore Cordova plugin initializing
,2016-09-14 13:15:06.313 ThaliTest[735:795975] JXcore instance initializing
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
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x129643420>
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-14 13:15:28.255 ThaliTest[735:795782] BTM: attaching to BTServer
,2016-09-14 13:15:29.400 ThaliTest[735:795782] BTM: local device power state changed
2016-09-14 13:15:29.400 ThaliTest[735:795782] BTM: power is now off
,2016-09-14 13:15:30.180 ThaliTest[735:795782] BTM: local device power state changed
2016-09-14 13:15:30.181 ThaliTest[735:795782] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  16.56212997436523
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
