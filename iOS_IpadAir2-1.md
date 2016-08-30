#### Test 797638307ede68b_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/797638307ede68b/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/5AD1B45F-D4CC-4CB0-96F4-5321E75ECD6D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/5AD1B45F-D4CC-4CB0-96F4-5321E75ECD6D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/797638307ede68b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/797638307ede68b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BD43AEC5-4134-4CCA-8562-FEEEC3EBFB4C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64437"
,(lldb)     command script import "/tmp/5AD1B45F-D4CC-4CB0-96F4-5321E75ECD6D/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 15:27:26.850 ThaliTest[1356:2505413] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D50FD3B9-648E-463E-BEC6-AF2238B5B5B8/Library/Cookies/Cookies.binarycookies
,2016-08-30 15:27:27.244 ThaliTest[1356:2505413] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 15:27:27.246 ThaliTest[1356:2505413] Multi-tasking -> Device: YES, App: YES
,2016-08-30 15:27:27.264 ThaliTest[1356:2505413] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 15:27:29.155 ThaliTest[1356:2505413] Using UIWebView
,2016-08-30 15:27:29.165 ThaliTest[1356:2505413] [CDVTimer][handleopenurl] 0.455976ms
,2016-08-30 15:27:29.173 ThaliTest[1356:2505413] [CDVTimer][intentandnavigationfilter] 7.203996ms
,2016-08-30 15:27:29.175 ThaliTest[1356:2505413] [CDVTimer][gesturehandler] 0.842035ms
2016-08-30 15:27:29.175 ThaliTest[1356:2505413] [CDVTimer][TotalPluginStartup] 11.613965ms
,2016-08-30 15:27:35.470 ThaliTest[1356:2505413] Resetting plugins due to page load.
,2016-08-30 15:27:39.101 ThaliTest[1356:2505413] Finished load of: file:///var/mobile/Containers/Bundle/Application/BD43AEC5-4134-4CCA-8562-FEEEC3EBFB4C/ThaliTest.app/www/index.html
,2016-08-30 15:27:39.305 ThaliTest[1356:2505413] JXcore Cordova plugin initializing
,2016-08-30 15:27:39.306 ThaliTest[1356:2505659] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-30 15:27:45.458 ThaliTest[1356:2505659] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-30 15:27:45.458 ThaliTest[1356:2505659] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-08-30 15:27:45.458 ThaliTest[1356:2505659] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-30 15:27:45.460 ThaliTest[1356:2505659] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-30 15:27:45.749 ThaliTest[1356:2505659] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005123019218444824
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
