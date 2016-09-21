#### Test 83268893ec4b63c_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83268893ec4b63c/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/B7CD2633-9BAD-47CB-B9C1-7199EF6691E2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B7CD2633-9BAD-47CB-B9C1-7199EF6691E2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83268893ec4b63c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83268893ec4b63c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D9A47D2E-BFBA-4927-BE80-0A6A41F5A447/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63838"
,(lldb)     command script import "/tmp/B7CD2633-9BAD-47CB-B9C1-7199EF6691E2/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 16:48:10.749 ThaliTest[2889:5320764] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F7AFA995-2705-4C5B-A933-172E3B205192/Library/Cookies/Cookies.binarycookies
,2016-09-21 16:48:11.137 ThaliTest[2889:5320764] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 16:48:11.139 ThaliTest[2889:5320764] Multi-tasking -> Device: YES, App: YES
,2016-09-21 16:48:11.159 ThaliTest[2889:5320764] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 16:48:13.144 ThaliTest[2889:5320764] Using UIWebView
,2016-09-21 16:48:13.151 ThaliTest[2889:5320764] [CDVTimer][handleopenurl] 0.331998ms
,2016-09-21 16:48:13.157 ThaliTest[2889:5320764] [CDVTimer][intentandnavigationfilter] 6.295025ms
,2016-09-21 16:48:13.158 ThaliTest[2889:5320764] [CDVTimer][gesturehandler] 0.299037ms
,2016-09-21 16:48:13.159 ThaliTest[2889:5320764] [CDVTimer][TotalPluginStartup] 8.778989ms
,2016-09-21 16:48:19.529 ThaliTest[2889:5320764] Resetting plugins due to page load.
,2016-09-21 16:48:22.682 ThaliTest[2889:5320764] Finished load of: file:///var/mobile/Containers/Bundle/Application/D9A47D2E-BFBA-4927-BE80-0A6A41F5A447/ThaliTest.app/www/index.html
,2016-09-21 16:48:22.952 ThaliTest[2889:5320764] JXcore Cordova plugin initializing
,2016-09-21 16:48:22.953 ThaliTest[2889:5320989] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
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
,2016-09-21 16:48:29.648 ThaliTest[2889:5320764] BTM: attaching to BTServer
,2016-09-21 16:48:40.538 ThaliTest[2889:5320764] BTM: local device power state changed
2016-09-21 16:48:40.539 ThaliTest[2889:5320764] BTM: power is now on
,2016-09-21 16:48:45.240 ThaliTest[2889:5320764] BTM: local device power state changed
2016-09-21 16:48:45.241 ThaliTest[2889:5320764] BTM: power is now off
,received session: <ThaliCore.Session: 0x13f037b10>
,Optional("CDA075D7-D6A9-4277-B213-6E6B8520DE45")
,nil
,nil
,Optional("A1EE6CE0-902B-4393-B249-AA6B1B369916")
,Optional("98017590-365F-4AE3-99C9-9E420588044D")
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  54
,Number of failed tests:  2
,Number of ignored tests:  0
,Total duration:  34.19360202550888
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
