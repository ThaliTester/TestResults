#### Test 87116923b621cb4_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/87116923b621cb4/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/669D8A9F-D932-4903-A91C-701332A467C1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/669D8A9F-D932-4903-A91C-701332A467C1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/87116923b621cb4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/87116923b621cb4/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/74C6EB7E-3FCB-426B-9D58-6E0C81D043E2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49305"
,(lldb)     command script import "/tmp/669D8A9F-D932-4903-A91C-701332A467C1/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-29 10:19:00.507 ThaliTest[3596:6324153] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/41274786-B151-4527-80FC-EFA1E4E53B7A/Library/Cookies/Cookies.binarycookies
,2016-09-29 10:19:00.863 ThaliTest[3596:6324153] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-29 10:19:00.864 ThaliTest[3596:6324153] Multi-tasking -> Device: YES, App: YES
,2016-09-29 10:19:00.886 ThaliTest[3596:6324153] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-29 10:19:02.875 ThaliTest[3596:6324153] Using UIWebView
,2016-09-29 10:19:02.882 ThaliTest[3596:6324153] [CDVTimer][handleopenurl] 0.627995ms
,2016-09-29 10:19:02.889 ThaliTest[3596:6324153] [CDVTimer][intentandnavigationfilter] 6.476998ms
,2016-09-29 10:19:02.890 ThaliTest[3596:6324153] [CDVTimer][gesturehandler] 0.308990ms
,2016-09-29 10:19:02.890 ThaliTest[3596:6324153] [CDVTimer][TotalPluginStartup] 9.092033ms
,2016-09-29 10:19:09.344 ThaliTest[3596:6324153] Resetting plugins due to page load.
,2016-09-29 10:19:12.525 ThaliTest[3596:6324153] Finished load of: file:///var/mobile/Containers/Bundle/Application/74C6EB7E-3FCB-426B-9D58-6E0C81D043E2/ThaliTest.app/www/index.html
,2016-09-29 10:19:12.737 ThaliTest[3596:6324153] JXcore Cordova plugin initializing
,2016-09-29 10:19:12.738 ThaliTest[3596:6324412] JXcore instance initializing
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
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  54
,Number of passed tests:  54
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.1381139755249
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
