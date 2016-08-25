#### Test 797638306764640_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/797638306764640/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/FE300671-6887-49C5-81C1-7FE38B1F7068/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/FE300671-6887-49C5-81C1-7FE38B1F7068/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/797638306764640/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/797638306764640/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AD080D5E-4D86-485B-9E20-27B0250C8E8E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50642"
,(lldb)     command script import "/tmp/FE300671-6887-49C5-81C1-7FE38B1F7068/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-25 15:23:44.642 ThaliTest[944:1831063] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/865C884C-1EFF-4DF1-A158-08A4F2AEDDFC/Library/Cookies/Cookies.binarycookies
,2016-08-25 15:23:45.030 ThaliTest[944:1831063] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-25 15:23:45.031 ThaliTest[944:1831063] Multi-tasking -> Device: YES, App: YES
,2016-08-25 15:23:45.051 ThaliTest[944:1831063] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-25 15:23:46.921 ThaliTest[944:1831063] Using UIWebView
,2016-08-25 15:23:46.929 ThaliTest[944:1831063] [CDVTimer][handleopenurl] 0.549018ms
,2016-08-25 15:23:46.936 ThaliTest[944:1831063] [CDVTimer][intentandnavigationfilter] 6.601989ms
,2016-08-25 15:23:46.937 ThaliTest[944:1831063] [CDVTimer][gesturehandler] 0.300050ms
,2016-08-25 15:23:46.937 ThaliTest[944:1831063] [CDVTimer][TotalPluginStartup] 9.185016ms
,2016-08-25 15:23:53.297 ThaliTest[944:1831063] Resetting plugins due to page load.
,2016-08-25 15:23:56.522 ThaliTest[944:1831063] Finished load of: file:///var/mobile/Containers/Bundle/Application/AD080D5E-4D86-485B-9E20-27B0250C8E8E/ThaliTest.app/www/index.html
,2016-08-25 15:23:56.752 ThaliTest[944:1831063] JXcore Cordova plugin initializing
,2016-08-25 15:23:56.753 ThaliTest[944:1831307] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-25 15:24:02.924 ThaliTest[944:1831307] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-25 15:24:02.925 ThaliTest[944:1831307] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-08-25 15:24:02.925 ThaliTest[944:1831307] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-25 15:24:02.926 ThaliTest[944:1831307] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-25 15:24:03.223 ThaliTest[944:1831307] jxcore: executeNativeTests: success
,Total number of executed tests:  3
Number of passed tests:  2
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  0.01320099830627441
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
