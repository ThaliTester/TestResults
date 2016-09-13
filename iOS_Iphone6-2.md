#### Test 82914073b4ce5c2_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073b4ce5c2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E7C21DCE-D059-4698-A9EF-A8C264A0F803/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/E7C21DCE-D059-4698-A9EF-A8C264A0F803/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073b4ce5c2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073b4ce5c2/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/03D20E2B-3C0C-40AB-9391-A4471278363C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58244"
,(lldb)     command script import "/tmp/E7C21DCE-D059-4698-A9EF-A8C264A0F803/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 06:11:32.361 ThaliTest[610:643495] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B415E606-6D61-48FD-8E89-2E9B4A751CF6/Library/Cookies/Cookies.binarycookies
,2016-09-13 06:11:32.398 ThaliTest[610:643495] Apache Cordova native platform version 4.1.1 is starting.
2016-09-13 06:11:32.398 ThaliTest[610:643495] Multi-tasking -> Device: YES, App: YES
,2016-09-13 06:11:32.414 ThaliTest[610:643495] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 06:11:32.747 ThaliTest[610:643495] Using UIWebView
,2016-09-13 06:11:32.752 ThaliTest[610:643495] [CDVTimer][handleopenurl] 0.283003ms
,2016-09-13 06:11:32.757 ThaliTest[610:643495] [CDVTimer][intentandnavigationfilter] 4.664958ms
2016-09-13 06:11:32.757 ThaliTest[610:643495] [CDVTimer][gesturehandler] 0.186980ms
2016-09-13 06:11:32.757 ThaliTest[610:643495] [CDVTimer][TotalPluginStartup] 6.258011ms
,2016-09-13 06:11:38.300 ThaliTest[610:643495] Resetting plugins due to page load.
,2016-09-13 06:11:38.639 ThaliTest[610:643495] Finished load of: file:///var/containers/Bundle/Application/03D20E2B-3C0C-40AB-9391-A4471278363C/ThaliTest.app/www/index.html
,2016-09-13 06:11:39.052 ThaliTest[610:643495] JXcore Cordova plugin initializing
,2016-09-13 06:11:39.053 ThaliTest[610:643664] JXcore instance initializing
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
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,2016-09-13 06:11:46.385 ThaliTest[610:643495] BTM: attaching to BTServer
,2016-09-13 06:11:50.954 ThaliTest[610:643495] BTM: local device power state changed
2016-09-13 06:11:50.955 ThaliTest[610:643495] BTM: power is now off
,2016-09-13 06:11:51.732 ThaliTest[610:643495] BTM: local device power state changed
2016-09-13 06:11:51.733 ThaliTest[610:643495] BTM: power is now on
,received session: <ThaliCore.Session: 0x160670420>
,*Native tests were executed*
Total number of executed tests:  48
,Number of passed tests:  48
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  16.40570896863937
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
