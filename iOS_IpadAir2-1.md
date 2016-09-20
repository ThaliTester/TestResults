#### Test 85960304ae0496b_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85960304ae0496b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/BF3AFBE6-5D7B-4A5F-8642-36D7990A8435/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/BF3AFBE6-5D7B-4A5F-8642-36D7990A8435/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85960304ae0496b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85960304ae0496b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/87BA881F-8B84-4F47-8886-AA0F1E4950CA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58079"
,(lldb)     command script import "/tmp/BF3AFBE6-5D7B-4A5F-8642-36D7990A8435/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-20 14:11:28.951 ThaliTest[2763:5174716] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FE8C2A1B-FDCF-4FA8-BACB-FDDB3149E37B/Library/Cookies/Cookies.binarycookies
,2016-09-20 14:11:29.323 ThaliTest[2763:5174716] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-20 14:11:29.324 ThaliTest[2763:5174716] Multi-tasking -> Device: YES, App: YES
,2016-09-20 14:11:29.342 ThaliTest[2763:5174716] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-20 14:11:31.248 ThaliTest[2763:5174716] Using UIWebView
,2016-09-20 14:11:31.256 ThaliTest[2763:5174716] [CDVTimer][handleopenurl] 0.397980ms
,2016-09-20 14:11:31.263 ThaliTest[2763:5174716] [CDVTimer][intentandnavigationfilter] 6.522000ms
,2016-09-20 14:11:31.264 ThaliTest[2763:5174716] [CDVTimer][gesturehandler] 0.317991ms
,2016-09-20 14:11:31.264 ThaliTest[2763:5174716] [CDVTimer][TotalPluginStartup] 8.804977ms
,2016-09-20 14:11:37.618 ThaliTest[2763:5174716] Resetting plugins due to page load.
,2016-09-20 14:11:41.322 ThaliTest[2763:5174716] Finished load of: file:///var/mobile/Containers/Bundle/Application/87BA881F-8B84-4F47-8886-AA0F1E4950CA/ThaliTest.app/www/index.html
,2016-09-20 14:11:41.533 ThaliTest[2763:5174716] JXcore Cordova plugin initializing
,2016-09-20 14:11:41.534 ThaliTest[2763:5174981] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-20 14:11:47.646 ThaliTest[2763:5174981] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-20 14:11:47.646 ThaliTest[2763:5174981] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-20 14:11:47.647 ThaliTest[2763:5174981] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-20 14:11:47.648 ThaliTest[2763:5174981] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-20 14:11:47.938 ThaliTest[2763:5174981] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005100011825561523
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
