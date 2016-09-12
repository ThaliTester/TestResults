#### Test 846487400fb5c63_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/846487400fb5c63/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/547ADCF1-1C9F-43F0-8175-9131FC983189/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/547ADCF1-1C9F-43F0-8175-9131FC983189/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/846487400fb5c63/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/846487400fb5c63/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A1E2BEFA-8BC0-4A1F-9284-B902F9038D0E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54630"
,(lldb)     command script import "/tmp/547ADCF1-1C9F-43F0-8175-9131FC983189/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-12 13:09:37.081 ThaliTest[2095:4137030] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/770358E3-AF53-4AEE-8199-D614E5F50BB1/Library/Cookies/Cookies.binarycookies
,2016-09-12 13:09:37.342 ThaliTest[2095:4137030] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-12 13:09:37.343 ThaliTest[2095:4137030] Multi-tasking -> Device: YES, App: YES
,2016-09-12 13:09:37.356 ThaliTest[2095:4137030] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-12 13:09:38.194 ThaliTest[2095:4137030] Using UIWebView
,2016-09-12 13:09:38.196 ThaliTest[2095:4137030] [CDVTimer][handleopenurl] 0.117004ms
,2016-09-12 13:09:38.198 ThaliTest[2095:4137030] [CDVTimer][intentandnavigationfilter] 1.902997ms
,2016-09-12 13:09:38.198 ThaliTest[2095:4137030] [CDVTimer][gesturehandler] 0.086010ms
2016-09-12 13:09:38.198 ThaliTest[2095:4137030] [CDVTimer][TotalPluginStartup] 2.541006ms
,2016-09-12 13:09:41.288 ThaliTest[2095:4137030] Resetting plugins due to page load.
,2016-09-12 13:09:42.687 ThaliTest[2095:4137030] Finished load of: file:///var/mobile/Containers/Bundle/Application/A1E2BEFA-8BC0-4A1F-9284-B902F9038D0E/ThaliTest.app/www/index.html
,2016-09-12 13:09:42.813 ThaliTest[2095:4137030] JXcore Cordova plugin initializing
2016-09-12 13:09:42.814 ThaliTest[2095:4137214] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-12 13:09:48.685 ThaliTest[2095:4137214] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-12 13:09:48.685 ThaliTest[2095:4137214] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-12 13:09:48.685 ThaliTest[2095:4137214] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-12 13:09:48.687 ThaliTest[2095:4137214] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-12 13:09:48.969 ThaliTest[2095:4137214] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
Number of passed tests:  2
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  0.004522979259490967
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
