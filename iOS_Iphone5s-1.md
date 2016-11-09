#### Test 89624796d0595a7_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/89624796d0595a7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6D2B4FA3-6ACA-4F21-84FB-05B02B509683/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/6D2B4FA3-6ACA-4F21-84FB-05B02B509683/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/89624796d0595a7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/89624796d0595a7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E7139350-7C3F-4E1A-8781-FCE0659065C6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58831"
,(lldb)     command script import "/tmp/6D2B4FA3-6ACA-4F21-84FB-05B02B509683/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-09 11:53:20.626 ThaliTest[5410:13644438] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7DD7FFA6-FC35-4B3E-B76F-638F500DAB82/Library/Cookies/Cookies.binarycookies
,2016-11-09 11:53:20.737 ThaliTest[5410:13644438] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-09 11:53:20.739 ThaliTest[5410:13644438] Multi-tasking -> Device: YES, App: YES
,2016-11-09 11:53:20.759 ThaliTest[5410:13644438] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-09 11:53:22.838 ThaliTest[5410:13644438] Using UIWebView
,2016-11-09 11:53:22.847 ThaliTest[5410:13644438] [CDVTimer][handleopenurl] 0.487983ms
,2016-11-09 11:53:22.856 ThaliTest[5410:13644438] [CDVTimer][intentandnavigationfilter] 8.278012ms
2016-11-09 11:53:22.857 ThaliTest[5410:13644438] [CDVTimer][gesturehandler] 0.387967ms
2016-11-09 11:53:22.857 ThaliTest[5410:13644438] [CDVTimer][TotalPlug,inStartup] 11.317015ms
,2016-11-09 11:53:30.395 ThaliTest[5410:13644438] Resetting plugins due to page load.
,2016-11-09 11:53:34.691 ThaliTest[5410:13644438] Finished load of: file:///var/mobile/Containers/Bundle/Application/E7139350-7C3F-4E1A-8781-FCE0659065C6/ThaliTest.app/www/index.html
,2016-11-09 11:53:35.030 ThaliTest[5410:13644438] JXcore Cordova plugin initializing
,2016-11-09 11:53:35.031 ThaliTest[5410:13644686] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-09 10:53:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-09 10:53:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-09 10:53:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-09 10:53:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-09 10:53:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-09 10:54:13 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.48358601331711
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
