#### Test 86174379abea55c_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86174379abea55c/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/8AB1EF78-B5B8-4A8D-BCDD-284842F3685F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/8AB1EF78-B5B8-4A8D-BCDD-284842F3685F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86174379abea55c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86174379abea55c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E4AC2BA4-4DB2-4DEC-BDA7-80F6214B9483/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56120"
,(lldb)     command script import "/tmp/8AB1EF78-B5B8-4A8D-BCDD-284842F3685F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 18:28:55.144 ThaliTest[2905:5331100] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/71E4D99C-EC10-4F6C-9EA8-23195363050B/Library/Cookies/Cookies.binarycookies
,2016-09-21 18:28:55.494 ThaliTest[2905:5331100] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 18:28:55.496 ThaliTest[2905:5331100] Multi-tasking -> Device: YES, App: YES
,2016-09-21 18:28:55.515 ThaliTest[2905:5331100] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 18:28:57.480 ThaliTest[2905:5331100] Using UIWebView
,2016-09-21 18:28:57.490 ThaliTest[2905:5331100] [CDVTimer][handleopenurl] 0.352979ms
,2016-09-21 18:28:57.498 ThaliTest[2905:5331100] [CDVTimer][intentandnavigationfilter] 6.896019ms
,2016-09-21 18:28:57.499 ThaliTest[2905:5331100] [CDVTimer][gesturehandler] 0.353992ms
,2016-09-21 18:28:57.499 ThaliTest[2905:5331100] [CDVTimer][TotalPluginStartup] 9.308994ms
,2016-09-21 18:29:04.184 ThaliTest[2905:5331100] Resetting plugins due to page load.
,2016-09-21 18:29:07.595 ThaliTest[2905:5331100] Finished load of: file:///var/mobile/Containers/Bundle/Application/E4AC2BA4-4DB2-4DEC-BDA7-80F6214B9483/ThaliTest.app/www/index.html
,2016-09-21 18:29:07.865 ThaliTest[2905:5331100] JXcore Cordova plugin initializing
,2016-09-21 18:29:07.866 ThaliTest[2905:5331355] JXcore instance initializing
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
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x157c7f7a0>
,Optional("21CCEB22-76CF-4D5D-B596-5CB628B9D36C")
,nil
,nil
,Optional("65E9AE9A-092D-4351-9024-CDB46124DC34")
,Optional("2042FD57-8FCD-4B46-B2BD-E4B9B37250B0")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-21 18:29:34.169 ThaliTest[2905:5331100] BTM: attaching to BTServer
,2016-09-21 18:29:34.977 ThaliTest[2905:5331100] BTM: local device power state changed
2016-09-21 18:29:34.978 ThaliTest[2905:5331100] BTM: power is now on
,2016-09-21 18:29:39.627 ThaliTest[2905:5331100] BTM: local device power state changed
2016-09-21 18:29:39.627 ThaliTest[2905:5331100] BTM: power is now off
,*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  55
,Number of failed tests:  1
,Number of ignored tests:  0
Total duration:  25.20906299352646
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
