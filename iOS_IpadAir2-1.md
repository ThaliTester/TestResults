#### Test 896247960a9c9d6_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/896247960a9c9d6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/F3C8E44B-3EEC-4A45-9C4F-2FBDF409C12E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F3C8E44B-3EEC-4A45-9C4F-2FBDF409C12E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/896247960a9c9d6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/896247960a9c9d6/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C2318600-D123-464A-B80D-EB9F88A16A41/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65240"
,(lldb)     command script import "/tmp/F3C8E44B-3EEC-4A45-9C4F-2FBDF409C12E/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-18 16:12:00.845 ThaliTest[4427:8679395] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B1D8E5B1-7637-4EC7-A463-9D6E61D12C35/Library/Cookies/Cookies.binarycookies
,2016-10-18 16:12:01.181 ThaliTest[4427:8679395] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-18 16:12:01.183 ThaliTest[4427:8679395] Multi-tasking -> Device: YES, App: YES
,2016-10-18 16:12:01.202 ThaliTest[4427:8679395] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-18 16:12:03.106 ThaliTest[4427:8679395] Using UIWebView
,2016-10-18 16:12:03.113 ThaliTest[4427:8679395] [CDVTimer][handleopenurl] 0.378013ms
,2016-10-18 16:12:03.120 ThaliTest[4427:8679395] [CDVTimer][intentandnavigationfilter] 6.708026ms
,2016-10-18 16:12:03.121 ThaliTest[4427:8679395] [CDVTimer][gesturehandler] 0.320017ms
,2016-10-18 16:12:03.122 ThaliTest[4427:8679395] [CDVTimer][TotalPluginStartup] 9.418011ms
,2016-10-18 16:12:09.461 ThaliTest[4427:8679395] Resetting plugins due to page load.
,2016-10-18 16:12:12.732 ThaliTest[4427:8679395] Finished load of: file:///var/mobile/Containers/Bundle/Application/C2318600-D123-464A-B80D-EB9F88A16A41/ThaliTest.app/www/index.html
,2016-10-18 16:12:12.999 ThaliTest[4427:8679395] JXcore Cordova plugin initializing
2016-10-18 16:12:13.000 ThaliTest[4427:8679647] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-18 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-18 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-18 14:12:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-10-18 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-18 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-10-18 14:12:55 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
Number of passed tests:  104
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  32.8811439871788
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
