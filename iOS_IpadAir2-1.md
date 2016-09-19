#### Test 85525887fe3c967_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85525887fe3c967/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/8CFE31C0-37C4-4768-9357-33460FE4E297/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/8CFE31C0-37C4-4768-9357-33460FE4E297/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85525887fe3c967/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85525887fe3c967/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DFCAF144-4DA6-4B41-8858-9EB14A796469/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59049"
,(lldb)     command script import "/tmp/8CFE31C0-37C4-4768-9357-33460FE4E297/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-19 15:01:23.345 ThaliTest[2684:5048119] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AC270A02-ABB9-42DE-976A-A3CA471B1D33/Library/Cookies/Cookies.binarycookies
,2016-09-19 15:01:23.752 ThaliTest[2684:5048119] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-19 15:01:23.753 ThaliTest[2684:5048119] Multi-tasking -> Device: YES, App: YES
,2016-09-19 15:01:23.772 ThaliTest[2684:5048119] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-19 15:01:25.664 ThaliTest[2684:5048119] Using UIWebView
,2016-09-19 15:01:25.670 ThaliTest[2684:5048119] [CDVTimer][handleopenurl] 0.366986ms
,2016-09-19 15:01:25.678 ThaliTest[2684:5048119] [CDVTimer][intentandnavigationfilter] 7.192016ms
,2016-09-19 15:01:25.679 ThaliTest[2684:5048119] [CDVTimer][gesturehandler] 0.353038ms
,2016-09-19 15:01:25.679 ThaliTest[2684:5048119] [CDVTimer][TotalPluginStartup] 9.424984ms
,2016-09-19 15:01:32.240 ThaliTest[2684:5048119] Resetting plugins due to page load.
,2016-09-19 15:01:36.330 ThaliTest[2684:5048119] Finished load of: file:///var/mobile/Containers/Bundle/Application/DFCAF144-4DA6-4B41-8858-9EB14A796469/ThaliTest.app/www/index.html
,2016-09-19 15:01:36.539 ThaliTest[2684:5048119] JXcore Cordova plugin initializing
,2016-09-19 15:01:36.540 ThaliTest[2684:5048375] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-19 15:01:42.692 ThaliTest[2684:5048375] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-19 15:01:42.693 ThaliTest[2684:5048375] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-19 15:01:42.693 ThaliTest[2684:5048375] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-19 15:01:42.694 ThaliTest[2684:5048375] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-19 15:01:42.982 ThaliTest[2684:5048375] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005061984062194824
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
