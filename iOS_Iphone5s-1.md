#### Test 86891305c474d20_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86891305c474d20/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2E248D12-84F6-4EFD-A55F-1DEB3792AA51/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/2E248D12-84F6-4EFD-A55F-1DEB3792AA51/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86891305c474d20/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86891305c474d20/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3116EC93-F95D-4A6B-82D7-7DB7A295DCA0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56516"
,(lldb)     command script import "/tmp/2E248D12-84F6-4EFD-A55F-1DEB3792AA51/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-27 12:58:45.813 ThaliTest[3358:6784633] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A3DCAB01-DA03-4FDA-80B7-940A22A66E84/Library/Cookies/Cookies.binarycookies
,2016-09-27 12:58:45.929 ThaliTest[3358:6784633] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-27 12:58:45.931 ThaliTest[3358:6784633] Multi-tasking -> Device: YES, App: YES
,2016-09-27 12:58:45.958 ThaliTest[3358:6784633] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 12:58:47.897 ThaliTest[3358:6784633] Using UIWebView
,2016-09-27 12:58:47.908 ThaliTest[3358:6784633] [CDVTimer][handleopenurl] 0.542998ms
,2016-09-27 12:58:47.917 ThaliTest[3358:6784633] [CDVTimer][intentandnavigationfilter] 8.296967ms
2016-09-27 12:58:47.918 ThaliTest[3358:6784633] [CDVTimer][gesturehandler] 0.423968ms
2016-09-27 12:58:47.919 ThaliTest[3358:6784633] [CDVTimer][TotalPluginS,tartup] 11.268973ms
,2016-09-27 12:58:54.762 ThaliTest[3358:6784633] Resetting plugins due to page load.
,2016-09-27 12:58:58.614 ThaliTest[3358:6784633] Finished load of: file:///var/mobile/Containers/Bundle/Application/3116EC93-F95D-4A6B-82D7-7DB7A295DCA0/ThaliTest.app/www/index.html
,2016-09-27 12:58:58.931 ThaliTest[3358:6784633] JXcore Cordova plugin initializing
,2016-09-27 12:58:58.932 ThaliTest[3358:6784869] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x139575b20>
,Optional("577F43BC-B097-4794-840A-90C42139B0DA")
,nil
,nil
,Optional("593AA172-3F9A-455D-95E8-D5F245A9CD75")
,Optional("9A949830-F5D5-48CC-8ED6-26193992A882")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  56
,Number of passed tests:  56
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  14.92528796195984
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
