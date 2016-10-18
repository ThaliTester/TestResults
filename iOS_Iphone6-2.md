#### Test 896247960a9c9d6_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/896247960a9c9d6/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C3C52767-EE64-4D86-828E-F0389B83894A/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/C3C52767-EE64-4D86-828E-F0389B83894A/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/896247960a9c9d6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/896247960a9c9d6/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/76C579A8-8BA1-4429-AF4D-30FBBEBC1CB1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65246"
,(lldb)     command script import "/tmp/C3C52767-EE64-4D86-828E-F0389B83894A/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-18 07:12:02.386 ThaliTest[2540:4585950] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/414C4FA8-A538-448C-B3A3-63C25659C20B/Library/Cookies/Cookies.binarycookies
,2016-10-18 07:12:02.454 ThaliTest[2540:4585950] Apache Cordova native platform version 4.2.1 is starting.
2016-10-18 07:12:02.455 ThaliTest[2540:4585950] Multi-tasking -> Device: YES, App: YES
,2016-10-18 07:12:02.479 ThaliTest[2540:4585950] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-18 07:12:02.872 ThaliTest[2540:4585950] Using UIWebView
,2016-10-18 07:12:02.879 ThaliTest[2540:4585950] [CDVTimer][handleopenurl] 0.228047ms
,2016-10-18 07:12:02.885 ThaliTest[2540:4585950] [CDVTimer][intentandnavigationfilter] 5.576015ms
2016-10-18 07:12:02.886 ThaliTest[2540:4585950] [CDVTimer][gesturehandler] 0.207007ms
2016-10-18 07:12:02.886 ThaliTest[2540:4585950] [CDVTimer][TotalPluginStartup] 7.184982ms
,2016-10-18 07:12:08.550 ThaliTest[2540:4585950] Resetting plugins due to page load.
,2016-10-18 07:12:09.057 ThaliTest[2540:4585950] Finished load of: file:///var/containers/Bundle/Application/76C579A8-8BA1-4429-AF4D-30FBBEBC1CB1/ThaliTest.app/www/index.html
,2016-10-18 07:12:09.430 ThaliTest[2540:4585950] JXcore Cordova plugin initializing
,2016-10-18 07:12:09.430 ThaliTest[2540:4586121] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-18 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-18 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-18 14:12:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-10-18 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-18 14:12:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-10-18 14:12:44 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  104
Number of passed tests:  104
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.97753697633743
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
