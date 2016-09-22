#### Test 861743790af7a74_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/861743790af7a74/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/3F22A30E-865B-4540-918F-A69A59D2C279/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/3F22A30E-865B-4540-918F-A69A59D2C279/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/861743790af7a74/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/861743790af7a74/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/78115DBB-7529-4A5E-B71C-C752286B93A9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63462"
,(lldb)     command script import "/tmp/3F22A30E-865B-4540-918F-A69A59D2C279/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 12:39:47.801 ThaliTest[3017:5436671] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/12533E47-50C0-4590-9E1B-267C2DE61DEB/Library/Cookies/Cookies.binarycookies
,2016-09-22 12:39:48.181 ThaliTest[3017:5436671] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 12:39:48.183 ThaliTest[3017:5436671] Multi-tasking -> Device: YES, App: YES
,2016-09-22 12:39:48.203 ThaliTest[3017:5436671] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 12:39:50.166 ThaliTest[3017:5436671] Using UIWebView
,2016-09-22 12:39:50.175 ThaliTest[3017:5436671] [CDVTimer][handleopenurl] 0.345945ms
,2016-09-22 12:39:50.183 ThaliTest[3017:5436671] [CDVTimer][intentandnavigationfilter] 6.736040ms
,2016-09-22 12:39:50.183 ThaliTest[3017:5436671] [CDVTimer][gesturehandler] 0.283003ms
,2016-09-22 12:39:50.184 ThaliTest[3017:5436671] [CDVTimer][TotalPluginStartup] 8.906007ms
,2016-09-22 12:39:56.657 ThaliTest[3017:5436671] Resetting plugins due to page load.
,2016-09-22 12:40:00.149 ThaliTest[3017:5436671] Finished load of: file:///var/mobile/Containers/Bundle/Application/78115DBB-7529-4A5E-B71C-C752286B93A9/ThaliTest.app/www/index.html
,2016-09-22 12:40:00.312 ThaliTest[3017:5436671] JXcore Cordova plugin initializing
,2016-09-22 12:40:00.313 ThaliTest[3017:5436925] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x151f070c0>
,Optional("9788E4F1-C820-4BA4-AF9E-387F097E33AF")
,nil
,nil
,Optional("C1E5BAD5-32AB-4D85-9A1A-16F14A5DA51B")
,Optional("AB67A4DC-BA4B-44A4-AFF7-552105314400")
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 12:40:25.449 ThaliTest[3017:5436671] BTM: attaching to BTServer
,2016-09-22 12:40:26.228 ThaliTest[3017:5436671] BTM: local device power state changed
2016-09-22 12:40:26.228 ThaliTest[3017:5436671] BTM: power is now on
,2016-09-22 12:40:30.893 ThaliTest[3017:5436671] BTM: local device power state changed
2016-09-22 12:40:30.894 ThaliTest[3017:5436671] BTM: power is now off
,*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  52
,Number of failed tests:  4
,Number of ignored tests:  0
,Total duration:  24.06690299510956
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
