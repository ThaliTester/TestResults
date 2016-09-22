#### Test 85046911f11c404_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911f11c404/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/5251607D-567C-4335-B8ED-4A9707B399D2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/5251607D-567C-4335-B8ED-4A9707B399D2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911f11c404/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911f11c404/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/57A52A50-342E-46FC-B1D1-CACD60783425/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62003"
,(lldb)     command script import "/tmp/5251607D-567C-4335-B8ED-4A9707B399D2/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 12:23:43.838 ThaliTest[2911:5967543] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/98AD92E9-204B-4CB9-92F4-EABC44C780FE/Library/Cookies/Cookies.binarycookies
,2016-09-22 12:23:43.953 ThaliTest[2911:5967543] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 12:23:43.955 ThaliTest[2911:5967543] Multi-tasking -> Device: YES, App: YES
,2016-09-22 12:23:43.978 ThaliTest[2911:5967543] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 12:23:45.542 ThaliTest[2911:5967543] Using UIWebView
,2016-09-22 12:23:45.551 ThaliTest[2911:5967543] [CDVTimer][handleopenurl] 0.467002ms
,2016-09-22 12:23:45.559 ThaliTest[2911:5967543] [CDVTimer][intentandnavigationfilter] 8.152962ms
2016-09-22 12:23:45.560 ThaliTest[2911:5967543] [CDVTimer][gesturehandler] 0.406981ms
2016-09-22 12:23:45.561 ThaliTest[2911:5967543] [CDVTimer][TotalPluginS,tartup] 10.869980ms
,2016-09-22 12:23:51.444 ThaliTest[2911:5967543] Resetting plugins due to page load.
,2016-09-22 12:23:54.874 ThaliTest[2911:5967543] Finished load of: file:///var/mobile/Containers/Bundle/Application/57A52A50-342E-46FC-B1D1-CACD60783425/ThaliTest.app/www/index.html
,2016-09-22 12:23:55.186 ThaliTest[2911:5967543] JXcore Cordova plugin initializing
,2016-09-22 12:23:55.187 ThaliTest[2911:5967796] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
,received session: <ThaliCore.Session: 0x159a93de0>
,Optional("784034E5-D0DD-4EB7-B8D7-4F2155ADBDFA")
,nil
,nil
,Optional("4AB9E606-4F2A-4BEF-897B-F7079B64E19C")
,Optional("D2EAA5E0-DEAB-4696-9BBB-8A2DB81C2187")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 12:24:18.776 ThaliTest[2911:5967543] BTM: attaching to BTServer
,2016-09-22 12:24:19.458 ThaliTest[2911:5967543] BTM: local device power state changed
2016-09-22 12:24:19.459 ThaliTest[2911:5967543] BTM: power is now on
,2016-09-22 12:24:24.207 ThaliTest[2911:5967543] BTM: local device power state changed
2016-09-22 12:24:24.208 ThaliTest[2911:5967543] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  20.24581599235535
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
