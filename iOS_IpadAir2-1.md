#### Test 852639026a23328_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/852639026a23328/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/B3159E5F-D670-43B8-95CB-3D3E24B928F4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B3159E5F-D670-43B8-95CB-3D3E24B928F4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/852639026a23328/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/852639026a23328/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3C11025B-1060-4313-AE71-B246B451467A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61082"
,(lldb)     command script import "/tmp/B3159E5F-D670-43B8-95CB-3D3E24B928F4/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-20 14:46:06.993 ThaliTest[2779:5180017] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/70D04DAB-1F1B-48A7-97DF-791E23A0FC00/Library/Cookies/Cookies.binarycookies
,2016-09-20 14:46:07.302 ThaliTest[2779:5180017] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-20 14:46:07.303 ThaliTest[2779:5180017] Multi-tasking -> Device: YES, App: YES
,2016-09-20 14:46:07.317 ThaliTest[2779:5180017] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-20 14:46:09.011 ThaliTest[2779:5180017] Using UIWebView
,2016-09-20 14:46:09.021 ThaliTest[2779:5180017] [CDVTimer][handleopenurl] 0.349998ms
,2016-09-20 14:46:09.028 ThaliTest[2779:5180017] [CDVTimer][intentandnavigationfilter] 6.871998ms
,2016-09-20 14:46:09.029 ThaliTest[2779:5180017] [CDVTimer][gesturehandler] 0.334024ms
,2016-09-20 14:46:09.029 ThaliTest[2779:5180017] [CDVTimer][TotalPluginStartup] 9.132981ms
,2016-09-20 14:46:15.371 ThaliTest[2779:5180017] Resetting plugins due to page load.
,2016-09-20 14:46:18.426 ThaliTest[2779:5180017] Finished load of: file:///var/mobile/Containers/Bundle/Application/3C11025B-1060-4313-AE71-B246B451467A/ThaliTest.app/www/index.html
,2016-09-20 14:46:18.637 ThaliTest[2779:5180017] JXcore Cordova plugin initializing
,2016-09-20 14:46:18.638 ThaliTest[2779:5180241] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-20 14:46:25.318 ThaliTest[2779:5180017] BTM: attaching to BTServer
,2016-09-20 14:46:26.106 ThaliTest[2779:5180017] BTM: local device power state changed
2016-09-20 14:46:26.106 ThaliTest[2779:5180017] BTM: power is now on
,2016-09-20 14:46:30.779 ThaliTest[2779:5180017] BTM: local device power state changed
2016-09-20 14:46:30.780 ThaliTest[2779:5180017] BTM: power is now off
,received session: <ThaliCore.Session: 0x14f3c1590>
,Optional("98308FF8-4836-4530-9C2B-91E2EBDF40E2")
,nil
,nil
,Optional("DE436D35-457F-462A-AE82-E57DE507847C")
,Optional("0D957E1A-14E3-4E1E-B0AF-4A8CEA57487B")
,*Native tests were executed*
,Total number of executed tests:  50
Number of passed tests:  50
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  23.85936897993088
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
