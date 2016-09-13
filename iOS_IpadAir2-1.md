#### Test 836273379690449_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/836273379690449/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/3C2B01DA-3E85-4806-A897-7135262A9BD6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/3C2B01DA-3E85-4806-A897-7135262A9BD6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/836273379690449/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/836273379690449/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0D041E2C-0DA8-40FD-8E3C-9C2751960A3A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56625"
,(lldb)     command script import "/tmp/3C2B01DA-3E85-4806-A897-7135262A9BD6/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 14:16:36.095 ThaliTest[2211:4278470] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/656C8E67-340D-4615-A904-C8E9B57B4CDA/Library/Cookies/Cookies.binarycookies
,2016-09-13 14:16:36.323 ThaliTest[2211:4278470] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 14:16:36.324 ThaliTest[2211:4278470] Multi-tasking -> Device: YES, App: YES
,2016-09-13 14:16:36.337 ThaliTest[2211:4278470] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 14:16:37.134 ThaliTest[2211:4278470] Using UIWebView
,2016-09-13 14:16:37.137 ThaliTest[2211:4278470] [CDVTimer][handleopenurl] 0.114024ms
,2016-09-13 14:16:37.139 ThaliTest[2211:4278470] [CDVTimer][intentandnavigationfilter] 1.909018ms
2016-09-13 14:16:37.139 ThaliTest[2211:4278470] [CDVTimer][gesturehandler] 0.090003ms
2016-09-13 14:16:37.139 ThaliTest[2211:4278470] [CDVTimer][TotalPluginStartup] 2.600968ms
,2016-09-13 14:16:40.146 ThaliTest[2211:4278470] Resetting plugins due to page load.
,2016-09-13 14:16:41.560 ThaliTest[2211:4278470] Finished load of: file:///var/mobile/Containers/Bundle/Application/0D041E2C-0DA8-40FD-8E3C-9C2751960A3A/ThaliTest.app/www/index.html
,2016-09-13 14:16:41.695 ThaliTest[2211:4278470] JXcore Cordova plugin initializing
2016-09-13 14:16:41.695 ThaliTest[2211:4278657] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 14:16:47.581 ThaliTest[2211:4278657] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-13 14:16:47.581 ThaliTest[2211:4278657] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-13 14:16:47.581 ThaliTest[2211:4278657] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-13 14:16:47.583 ThaliTest[2211:4278657] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,2016-09-13 14:16:47.866 ThaliTest[2211:4278657] jxcore: executeNativeTests: success
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.00457000732421875
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
