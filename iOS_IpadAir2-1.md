#### Test 82894682da71698_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82894682da71698/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/386159F5-0AA7-4A77-9F6B-B182D6D7775A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/386159F5-0AA7-4A77-9F6B-B182D6D7775A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82894682da71698/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82894682da71698/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FA4B6340-4ADC-40BA-B993-D1F063FEB4CA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53406"
,(lldb)     command script import "/tmp/386159F5-0AA7-4A77-9F6B-B182D6D7775A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 00:03:55.663 ThaliTest[2148:4200422] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E8C57893-DC41-491C-B548-18F49BFCEA16/Library/Cookies/Cookies.binarycookies
,2016-09-13 00:03:55.895 ThaliTest[2148:4200422] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 00:03:55.896 ThaliTest[2148:4200422] Multi-tasking -> Device: YES, App: YES
,2016-09-13 00:03:55.908 ThaliTest[2148:4200422] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 00:03:56.712 ThaliTest[2148:4200422] Using UIWebView
,2016-09-13 00:03:56.714 ThaliTest[2148:4200422] [CDVTimer][handleopenurl] 0.097036ms
,2016-09-13 00:03:56.717 ThaliTest[2148:4200422] [CDVTimer][intentandnavigationfilter] 2.063990ms
2016-09-13 00:03:56.717 ThaliTest[2148:4200422] [CDVTimer][gesturehandler] 0.082970ms
2016-09-13 00:03:56.717 ThaliTest[2148:4200422] [CDVTimer][TotalPluginStartup] 2.680004ms
,2016-09-13 00:03:59.874 ThaliTest[2148:4200422] Resetting plugins due to page load.
,2016-09-13 00:04:01.307 ThaliTest[2148:4200422] Finished load of: file:///var/mobile/Containers/Bundle/Application/FA4B6340-4ADC-40BA-B993-D1F063FEB4CA/ThaliTest.app/www/index.html
,2016-09-13 00:04:01.436 ThaliTest[2148:4200422] JXcore Cordova plugin initializing
,(JX_LoopOnce) Did you initialize the JXEngine instance for this thread? (ret_val: 0)
,2016-09-13 00:04:01.438 ThaliTest[2148:4200596] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-09-13 00:04:46.143 ThaliTest[2148:4200422] BTM: attaching to BTServer
,2016-09-13 00:04:47.217 ThaliTest[2148:4200422] BTM: local device power state changed
2016-09-13 00:04:47.218 ThaliTest[2148:4200422] BTM: power is now off
,2016-09-13 00:04:48.018 ThaliTest[2148:4200422] BTM: local device power state changed
2016-09-13 00:04:48.019 ThaliTest[2148:4200422] BTM: power is now on
,*Native tests were executed*
,Total number of executed tests:  16
,Number of passed tests:  16
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  40.33106601238251
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
