#### Test 85046911b09b63d_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911b09b63d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/6A3CAF53-0526-4ED1-A5B0-ECD238103EA9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/6A3CAF53-0526-4ED1-A5B0-ECD238103EA9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911b09b63d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911b09b63d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/97E57001-B1CC-43A4-A71F-689BF42DFDDB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64793"
,(lldb)     command script import "/tmp/6A3CAF53-0526-4ED1-A5B0-ECD238103EA9/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 09:54:15.916 ThaliTest[3131:5557188] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/08658397-A5AB-42F6-93B4-F98689B037A3/Library/Cookies/Cookies.binarycookies
,2016-09-23 09:54:16.295 ThaliTest[3131:5557188] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 09:54:16.297 ThaliTest[3131:5557188] Multi-tasking -> Device: YES, App: YES
,2016-09-23 09:54:16.318 ThaliTest[3131:5557188] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 09:54:18.271 ThaliTest[3131:5557188] Using UIWebView
,2016-09-23 09:54:18.281 ThaliTest[3131:5557188] [CDVTimer][handleopenurl] 0.418007ms
,2016-09-23 09:54:18.288 ThaliTest[3131:5557188] [CDVTimer][intentandnavigationfilter] 6.693006ms
2016-09-23 09:54:18.289 ThaliTest[3131:5557188] [CDVTimer][gesturehandler] 0.329018ms
,2016-09-23 09:54:18.289 ThaliTest[3131:5557188] [CDVTimer][TotalPluginStartup] 9.015977ms
,2016-09-23 09:54:24.723 ThaliTest[3131:5557188] Resetting plugins due to page load.
,2016-09-23 09:54:27.504 ThaliTest[3131:5557188] Finished load of: file:///var/mobile/Containers/Bundle/Application/97E57001-B1CC-43A4-A71F-689BF42DFDDB/ThaliTest.app/www/index.html
,2016-09-23 09:54:27.709 ThaliTest[3131:5557188] JXcore Cordova plugin initializing
,2016-09-23 09:54:27.710 ThaliTest[3131:5557437] JXcore instance initializing
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
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 09:54:34.378 ThaliTest[3131:5557188] BTM: attaching to BTServer
,2016-09-23 09:54:35.189 ThaliTest[3131:5557188] BTM: local device power state changed
2016-09-23 09:54:35.190 ThaliTest[3131:5557188] BTM: power is now on
,2016-09-23 09:54:39.899 ThaliTest[3131:5557188] BTM: local device power state changed
2016-09-23 09:54:39.900 ThaliTest[3131:5557188] BTM: power is now off
,*Native tests were executed*
,Total number of executed tests:  7
,Number of passed tests:  7
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  5.686598002910614
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
