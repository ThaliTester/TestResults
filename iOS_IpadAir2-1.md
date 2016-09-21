#### Test 85046911d6c2afe_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911d6c2afe/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/C8EE5EFC-0710-4B12-9398-5D6BDEAD85BF/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C8EE5EFC-0710-4B12-9398-5D6BDEAD85BF/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911d6c2afe/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911d6c2afe/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/97B261D0-888B-4DE2-ACD5-27653B1E57E5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49273"
,(lldb)     command script import "/tmp/C8EE5EFC-0710-4B12-9398-5D6BDEAD85BF/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 11:01:57.883 ThaliTest[2816:5283250] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/18DBEBA2-D5AC-487F-BA48-2AAD253A0711/Library/Cookies/Cookies.binarycookies
,2016-09-21 11:01:58.382 ThaliTest[2816:5283250] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 11:01:58.383 ThaliTest[2816:5283250] Multi-tasking -> Device: YES, App: YES
,2016-09-21 11:01:58.401 ThaliTest[2816:5283250] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 11:02:00.502 ThaliTest[2816:5283250] Using UIWebView
,2016-09-21 11:02:00.509 ThaliTest[2816:5283250] [CDVTimer][handleopenurl] 0.349998ms
,2016-09-21 11:02:00.516 ThaliTest[2816:5283250] [CDVTimer][intentandnavigationfilter] 6.470978ms
,2016-09-21 11:02:00.516 ThaliTest[2816:5283250] [CDVTimer][gesturehandler] 0.306010ms
,2016-09-21 11:02:00.517 ThaliTest[2816:5283250] [CDVTimer][TotalPluginStartup] 8.518994ms
,2016-09-21 11:02:08.983 ThaliTest[2816:5283250] Resetting plugins due to page load.
,2016-09-21 11:02:13.430 ThaliTest[2816:5283250] Finished load of: file:///var/mobile/Containers/Bundle/Application/97B261D0-888B-4DE2-ACD5-27653B1E57E5/ThaliTest.app/www/index.html
,2016-09-21 11:02:13.635 ThaliTest[2816:5283250] JXcore Cordova plugin initializing
,2016-09-21 11:02:13.636 ThaliTest[2816:5283552] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 11:02:19.756 ThaliTest[2816:5283552] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-21 11:02:19.756 ThaliTest[2816:5283552] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-21 11:02:19.756 ThaliTest[2816:5283552] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-21 11:02:19.758 ThaliTest[2816:5283552] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 11:02:20.045 ThaliTest[2816:5283552] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.005065023899078369
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
