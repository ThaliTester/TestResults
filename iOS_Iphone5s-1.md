#### Test 85046911aebbc53_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911aebbc53/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E155F445-2EE1-4D21-A9DE-446DCD76AFB4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
Executing commands in '/tmp/E155F445-2EE1-4D21-A9DE-446DCD76AFB4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911aebbc53/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911aebbc53/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B397E821-8D8B-4603-95E0-0097FEAE0EFF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53437"
,(lldb)     command script import "/tmp/E155F445-2EE1-4D21-A9DE-446DCD76AFB4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 09:43:33.206 ThaliTest[2871:5945271] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EA739422-948C-4307-9769-F6B074B39BA5/Library/Cookies/Cookies.binarycookies
,2016-09-22 09:43:33.333 ThaliTest[2871:5945271] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 09:43:33.336 ThaliTest[2871:5945271] Multi-tasking -> Device: YES, App: YES
,2016-09-22 09:43:33.356 ThaliTest[2871:5945271] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 09:43:34.920 ThaliTest[2871:5945271] Using UIWebView
,2016-09-22 09:43:34.928 ThaliTest[2871:5945271] [CDVTimer][handleopenurl] 0.686049ms
,2016-09-22 09:43:34.937 ThaliTest[2871:5945271] [CDVTimer][intentandnavigationfilter] 8.287966ms
2016-09-22 09:43:34.938 ThaliTest[2871:5945271] [CDVTimer][gesturehandler] 0.384986ms
2016-09-22 09:43:34.938 ThaliTest[2871:5945271] [CDVTimer][TotalPluginS,tartup] 11.251032ms
,2016-09-22 09:43:40.724 ThaliTest[2871:5945271] Resetting plugins due to page load.
,2016-09-22 09:43:44.134 ThaliTest[2871:5945271] Finished load of: file:///var/mobile/Containers/Bundle/Application/B397E821-8D8B-4603-95E0-0097FEAE0EFF/ThaliTest.app/www/index.html
,2016-09-22 09:43:44.432 ThaliTest[2871:5945271] JXcore Cordova plugin initializing
,2016-09-22 09:43:44.433 ThaliTest[2871:5945481] JXcore instance initializing
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
,2016-09-22 09:43:53.428 ThaliTest[2871:5945271] BTM: attaching to BTServer
,2016-09-22 09:43:54.108 ThaliTest[2871:5945271] BTM: local device power state changed
2016-09-22 09:43:54.109 ThaliTest[2871:5945271] BTM: power is now on
,2016-09-22 09:43:58.832 ThaliTest[2871:5945271] BTM: local device power state changed
2016-09-22 09:43:58.832 ThaliTest[2871:5945271] BTM: power is now off
,received session: <ThaliCore.Session: 0x12f6639a0>
,Optional("2C5972B6-B553-4077-915E-2E64A8F06AF6")
,nil
,nil
,Optional("6F86392C-1278-4E9E-B302-C2FE7B7F135E")
,Optional("62441BC0-213A-41CB-9E87-51AE93E7355A")
,*Native tests were executed*
,Total number of executed tests:  50
,Number of passed tests:  50
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  19.89546602964401
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
