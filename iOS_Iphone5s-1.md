#### Test 82914073fb4f932_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073fb4f932/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F9CD4866-C93A-4449-83C7-E76BFBE21338/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F9CD4866-C93A-4449-83C7-E76BFBE21338/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073fb4f932/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073fb4f932/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EE16AB05-EB49-4014-9B79-5858C640B33E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61848"
,(lldb)     command script import "/tmp/F9CD4866-C93A-4449-83C7-E76BFBE21338/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 19:24:25.014 ThaliTest[2254:4768624] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FD464475-44DB-4723-AA3F-09BBC3612791/Library/Cookies/Cookies.binarycookies
,2016-09-14 19:24:25.125 ThaliTest[2254:4768624] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 19:24:25.127 ThaliTest[2254:4768624] Multi-tasking -> Device: YES, App: YES
,2016-09-14 19:24:25.151 ThaliTest[2254:4768624] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 19:24:26.619 ThaliTest[2254:4768624] Using UIWebView
,2016-09-14 19:24:26.628 ThaliTest[2254:4768624] [CDVTimer][handleopenurl] 0.669003ms
,2016-09-14 19:24:26.636 ThaliTest[2254:4768624] [CDVTimer][intentandnavigationfilter] 7.999003ms
2016-09-14 19:24:26.637 ThaliTest[2254:4768624] [CDVTimer][gesturehandler] 0.440001ms
2016-09-14 19:24:26.638 ThaliTest[2254:4768624] [CDVTimer][TotalPluginS,tartup] 10.998964ms
,2016-09-14 19:24:32.622 ThaliTest[2254:4768624] Resetting plugins due to page load.
,2016-09-14 19:24:36.162 ThaliTest[2254:4768624] Finished load of: file:///var/mobile/Containers/Bundle/Application/EE16AB05-EB49-4014-9B79-5858C640B33E/ThaliTest.app/www/index.html
,2016-09-14 19:24:36.464 ThaliTest[2254:4768624] JXcore Cordova plugin initializing
,2016-09-14 19:24:36.465 ThaliTest[2254:4768840] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
,2016-09-14 19:24:45.386 ThaliTest[2254:4768624] BTM: attaching to BTServer
,2016-09-14 19:24:49.980 ThaliTest[2254:4768624] BTM: local device power state changed
2016-09-14 19:24:49.981 ThaliTest[2254:4768624] BTM: power is now off
,2016-09-14 19:24:50.792 ThaliTest[2254:4768624] BTM: local device power state changed
2016-09-14 19:24:50.793 ThaliTest[2254:4768624] BTM: power is now on
,received session: <ThaliCore.Session: 0x15e0abe70>
,*Native tests were executed*
Total number of executed tests:  48
,Number of passed tests:  48
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  16.63099300861359
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
