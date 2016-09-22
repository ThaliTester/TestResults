#### Test 85046911f11c404_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911f11c404/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/B891C833-E437-4B84-98BF-F34A1A7B4C03/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B891C833-E437-4B84-98BF-F34A1A7B4C03/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911f11c404/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911f11c404/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/083CAEA1-7ACF-496B-A9CA-6C6C2EC567A1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61999"
,(lldb)     command script import "/tmp/B891C833-E437-4B84-98BF-F34A1A7B4C03/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 12:23:44.446 ThaliTest[3009:5434108] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B677423F-2449-4B15-A87E-5427B4EF60F3/Library/Cookies/Cookies.binarycookies
,2016-09-22 12:23:44.816 ThaliTest[3009:5434108] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 12:23:44.817 ThaliTest[3009:5434108] Multi-tasking -> Device: YES, App: YES
,2016-09-22 12:23:44.837 ThaliTest[3009:5434108] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 12:23:46.849 ThaliTest[3009:5434108] Using UIWebView
,2016-09-22 12:23:46.858 ThaliTest[3009:5434108] [CDVTimer][handleopenurl] 0.331998ms
,2016-09-22 12:23:46.866 ThaliTest[3009:5434108] [CDVTimer][intentandnavigationfilter] 7.025003ms
,2016-09-22 12:23:46.867 ThaliTest[3009:5434108] [CDVTimer][gesturehandler] 0.303030ms
,2016-09-22 12:23:46.867 ThaliTest[3009:5434108] [CDVTimer][TotalPluginStartup] 9.345055ms
,2016-09-22 12:23:53.295 ThaliTest[3009:5434108] Resetting plugins due to page load.
,2016-09-22 12:23:56.263 ThaliTest[3009:5434108] Finished load of: file:///var/mobile/Containers/Bundle/Application/083CAEA1-7ACF-496B-A9CA-6C6C2EC567A1/ThaliTest.app/www/index.html
,2016-09-22 12:23:56.475 ThaliTest[3009:5434108] JXcore Cordova plugin initializing
,2016-09-22 12:23:56.475 ThaliTest[3009:5434356] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x1345865b0>
,Optional("D7FD2FB7-204C-42A9-9D6E-22F92CBF100F")
,nil
,nil
,Optional("CB1B21B2-4FFF-4166-AAC4-D8F71397262B")
,Optional("36EFB4A3-3C8F-43FE-AC03-4049802CD944")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 12:24:22.707 ThaliTest[3009:5434108] BTM: attaching to BTServer
,2016-09-22 12:24:23.507 ThaliTest[3009:5434108] BTM: local device power state changed
2016-09-22 12:24:23.507 ThaliTest[3009:5434108] BTM: power is now on
,2016-09-22 12:24:28.178 ThaliTest[3009:5434108] BTM: local device power state changed
2016-09-22 12:24:28.178 ThaliTest[3009:5434108] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.10889500379562
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
