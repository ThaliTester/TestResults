#### Test 83268893ec4b63c_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83268893ec4b63c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/AC788F81-BA18-4241-BC87-AAE86BB91B31/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/AC788F81-BA18-4241-BC87-AAE86BB91B31/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83268893ec4b63c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83268893ec4b63c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D8D663E7-8D3A-4DA7-BFD6-83242F90404E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63849"
,(lldb)     command script import "/tmp/AC788F81-BA18-4241-BC87-AAE86BB91B31/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 16:48:10.790 ThaliTest[2796:5830456] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/75F50A64-90A5-4607-AB06-237ED2100F41/Library/Cookies/Cookies.binarycookies
,2016-09-21 16:48:10.905 ThaliTest[2796:5830456] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 16:48:10.907 ThaliTest[2796:5830456] Multi-tasking -> Device: YES, App: YES
,2016-09-21 16:48:10.930 ThaliTest[2796:5830456] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 16:48:12.502 ThaliTest[2796:5830456] Using UIWebView
,2016-09-21 16:48:12.514 ThaliTest[2796:5830456] [CDVTimer][handleopenurl] 0.468016ms
,2016-09-21 16:48:12.523 ThaliTest[2796:5830456] [CDVTimer][intentandnavigationfilter] 8.343995ms
2016-09-21 16:48:12.523 ThaliTest[2796:5830456] [CDVTimer][gesturehandler] 0.367999ms
2016-09-21 16:48:12.524 ThaliTest[2796:5830456] [CDVTimer][TotalPluginS,tartup] 11.013031ms
,2016-09-21 16:48:18.443 ThaliTest[2796:5830456] Resetting plugins due to page load.
,2016-09-21 16:48:21.749 ThaliTest[2796:5830456] Finished load of: file:///var/mobile/Containers/Bundle/Application/D8D663E7-8D3A-4DA7-BFD6-83242F90404E/ThaliTest.app/www/index.html
,2016-09-21 16:48:22.059 ThaliTest[2796:5830456] JXcore Cordova plugin initializing
,2016-09-21 16:48:22.060 ThaliTest[2796:5830679] JXcore instance initializing
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
Optional(false)
,Optional(false)
Optional(true)
,2016-09-21 16:48:31.155 ThaliTest[2796:5830456] BTM: attaching to BTServer
,2016-09-21 16:48:42.432 ThaliTest[2796:5830456] BTM: local device power state changed
2016-09-21 16:48:42.432 ThaliTest[2796:5830456] BTM: power is now off
,received session: <ThaliCore.Session: 0x156ace3d0>
,Optional("82D04070-951A-4CB9-BEEA-818CD089CA2E")
,nil
,nil
,Optional("2104CC2C-AC69-42F2-8B14-6F1BC5F3A929")
,Optional("64342C6A-4CEF-4711-9892-D6DA8D842248")
,*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  54
,Number of failed tests:  2
,Number of ignored tests:  0
,Total duration:  25.44379198551178
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
