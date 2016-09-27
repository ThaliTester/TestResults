#### Test 8689130568a1443_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8689130568a1443/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/03AA6063-5F4E-4069-8344-43FABE08DAED/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/03AA6063-5F4E-4069-8344-43FABE08DAED/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8689130568a1443/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8689130568a1443/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/430F6A86-E043-4CD4-A070-FAC3EC734A8B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56348"
,(lldb)     command script import "/tmp/03AA6063-5F4E-4069-8344-43FABE08DAED/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-27 12:51:56.903 ThaliTest[1526:2375822] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FB9013F2-FE9F-437E-992C-8A1AA2CD8648/Library/Cookies/Cookies.binarycookies
,2016-09-27 12:51:56.943 ThaliTest[1526:2375822] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-27 12:51:56.944 ThaliTest[1526:2375822] Multi-tasking -> Device: YES, App: YES
,2016-09-27 12:51:56.956 ThaliTest[1526:2375822] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 12:51:57.242 ThaliTest[1526:2375822] Using UIWebView
,2016-09-27 12:51:57.249 ThaliTest[1526:2375822] [CDVTimer][handleopenurl] 0.232995ms
,2016-09-27 12:51:57.253 ThaliTest[1526:2375822] [CDVTimer][intentandnavigationfilter] 3.425002ms
2016-09-27 12:51:57.253 ThaliTest[1526:2375822] [CDVTimer][gesturehandler] 0.165999ms
2016-09-27 12:51:57.253 ThaliTest[1526:2375822] [CDVTimer][TotalPluginS,tartup] 4.669011ms
,2016-09-27 12:52:02.623 ThaliTest[1526:2375822] Resetting plugins due to page load.
,2016-09-27 12:52:03.005 ThaliTest[1526:2375822] Finished load of: file:///var/containers/Bundle/Application/430F6A86-E043-4CD4-A070-FAC3EC734A8B/ThaliTest.app/www/index.html
,2016-09-27 12:52:03.339 ThaliTest[1526:2375822] JXcore Cordova plugin initializing
,2016-09-27 12:52:03.340 ThaliTest[1526:2375981] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x1392c0d20>
,Optional("0B96A2C6-F5FE-415F-ABF2-D3ADEF169EA2")
nil
,nil
,Optional("8E94CE2E-03F8-4966-8581-2F7EC9BB5D74")
,Optional("3256E192-AE95-4EA8-B73A-F657007B025F")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  56
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.41380196809769
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
