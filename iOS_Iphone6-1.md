#### Test 85960304727dacc_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85960304727dacc/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/801F3BDE-BDC5-4A6A-A2E9-468F158C3D49/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/801F3BDE-BDC5-4A6A-A2E9-468F158C3D49/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85960304727dacc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85960304727dacc/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/80EDC49E-C558-4708-BA18-2ABA848678DB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53047"
,(lldb)     command script import "/tmp/801F3BDE-BDC5-4A6A-A2E9-468F158C3D49/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 14:59:58.501 ThaliTest[1196:1750954] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9B55FEE3-6452-4A9A-8DA8-31502B358261/Library/Cookies/Cookies.binarycookies
,2016-09-22 14:59:58.589 ThaliTest[1196:1750954] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 14:59:58.591 ThaliTest[1196:1750954] Multi-tasking -> Device: YES, App: YES
,2016-09-22 14:59:58.611 ThaliTest[1196:1750954] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 14:59:59.098 ThaliTest[1196:1750954] Using UIWebView
,2016-09-22 14:59:59.105 ThaliTest[1196:1750954] [CDVTimer][handleopenurl] 0.531018ms
,2016-09-22 14:59:59.113 ThaliTest[1196:1750954] [CDVTimer][intentandnavigationfilter] 7.077038ms
2016-09-22 14:59:59.113 ThaliTest[1196:1750954] [CDVTimer][gesturehandler] 0.290990ms
2016-09-22 14:59:59.114 ThaliTest[1196:1750954] [CDVTimer][TotalPluginStartup] 9.483993ms
,2016-09-22 15:00:04.447 ThaliTest[1196:1750954] Resetting plugins due to page load.
,2016-09-22 15:00:04.729 ThaliTest[1196:1750954] Finished load of: file:///var/containers/Bundle/Application/80EDC49E-C558-4708-BA18-2ABA848678DB/ThaliTest.app/www/index.html
,2016-09-22 15:00:05.061 ThaliTest[1196:1750954] JXcore Cordova plugin initializing
,2016-09-22 15:00:05.062 ThaliTest[1196:1751121] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x151557880>
,Optional("FBF6AD61-A1F3-4FC1-B961-49628026D355")
,nil
,nil
,Optional("D10F89B0-70F4-4F69-8E83-690A7DFC8D58")
,Optional("574B13DF-BD74-43C1-ACDB-F594EEAEFBF8")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-22 15:00:26.884 ThaliTest[1196:1750954] BTM: attaching to BTServer
,2016-09-22 15:00:27.629 ThaliTest[1196:1750954] BTM: local device power state changed
2016-09-22 15:00:27.629 ThaliTest[1196:1750954] BTM: power is now on
,2016-09-22 15:00:32.315 ThaliTest[1196:1750954] BTM: local device power state changed
2016-09-22 15:00:32.316 ThaliTest[1196:1750954] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  19.86355400085449
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
