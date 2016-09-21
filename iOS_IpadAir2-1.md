#### Test 850469111b8590e_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469111b8590e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/CF17F9C7-8CB9-4A3E-A7A1-6895E00603A2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/CF17F9C7-8CB9-4A3E-A7A1-6895E00603A2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469111b8590e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469111b8590e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/16D12F05-4CDA-4802-A424-FEE0792AEA51/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51563"
,(lldb)     command script import "/tmp/CF17F9C7-8CB9-4A3E-A7A1-6895E00603A2/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 11:56:24.561 ThaliTest[2826:5288921] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CB94F0E3-CC0F-49F0-82E8-FDA756C59994/Library/Cookies/Cookies.binarycookies
,2016-09-21 11:56:24.965 ThaliTest[2826:5288921] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 11:56:24.966 ThaliTest[2826:5288921] Multi-tasking -> Device: YES, App: YES
,2016-09-21 11:56:24.985 ThaliTest[2826:5288921] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 11:56:26.869 ThaliTest[2826:5288921] Using UIWebView
,2016-09-21 11:56:26.876 ThaliTest[2826:5288921] [CDVTimer][handleopenurl] 0.395000ms
,2016-09-21 11:56:26.884 ThaliTest[2826:5288921] [CDVTimer][intentandnavigationfilter] 7.368982ms
,2016-09-21 11:56:26.885 ThaliTest[2826:5288921] [CDVTimer][gesturehandler] 0.312984ms
,2016-09-21 11:56:26.885 ThaliTest[2826:5288921] [CDVTimer][TotalPluginStartup] 9.589970ms
,2016-09-21 11:56:33.241 ThaliTest[2826:5288921] Resetting plugins due to page load.
,2016-09-21 11:56:36.790 ThaliTest[2826:5288921] Finished load of: file:///var/mobile/Containers/Bundle/Application/16D12F05-4CDA-4802-A424-FEE0792AEA51/ThaliTest.app/www/index.html
,2016-09-21 11:56:36.994 ThaliTest[2826:5288921] JXcore Cordova plugin initializing
,2016-09-21 11:56:36.994 ThaliTest[2826:5289178] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 11:56:43.104 ThaliTest[2826:5289178] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-21 11:56:43.104 ThaliTest[2826:5289178] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-21 11:56:43.104 ThaliTest[2826:5289178] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-21 11:56:43.106 ThaliTest[2826:5289178] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 11:56:43.393 ThaliTest[2826:5289178] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.004886984825134277
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
