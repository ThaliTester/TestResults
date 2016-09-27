#### Test 85046911aaecdb3_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911aaecdb3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/43AB56C2-BE4D-4CE4-A7A8-0F89CF42E96F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/43AB56C2-BE4D-4CE4-A7A8-0F89CF42E96F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911aaecdb3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911aaecdb3/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0B411DB7-2AB6-444F-9203-8B456F27385A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57828"
,(lldb)     command script import "/tmp/43AB56C2-BE4D-4CE4-A7A8-0F89CF42E96F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-27 09:23:28.813 ThaliTest[3408:6061566] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C3E1516B-37C7-429E-AA54-D01F9ED7B4EA/Library/Cookies/Cookies.binarycookies
,2016-09-27 09:23:29.057 ThaliTest[3408:6061566] Apache Cordova native platform version 4.2.1 is starting.
2016-09-27 09:23:29.058 ThaliTest[3408:6061566] Multi-tasking -> Device: YES, App: YES
,2016-09-27 09:23:29.071 ThaliTest[3408:6061566] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 09:23:29.945 ThaliTest[3408:6061566] Using UIWebView
,2016-09-27 09:23:29.948 ThaliTest[3408:6061566] [CDVTimer][handleopenurl] 0.100017ms
,2016-09-27 09:23:29.950 ThaliTest[3408:6061566] [CDVTimer][intentandnavigationfilter] 1.865029ms
2016-09-27 09:23:29.950 ThaliTest[3408:6061566] [CDVTimer][gesturehandler] 0.104010ms
2016-09-27 09:23:29.950 ThaliTest[3408:6061566] [CDVTimer][TotalPluginStartup] 2.525032ms
,2016-09-27 09:23:33.231 ThaliTest[3408:6061566] Resetting plugins due to page load.
,2016-09-27 09:23:34.532 ThaliTest[3408:6061566] Finished load of: file:///var/mobile/Containers/Bundle/Application/0B411DB7-2AB6-444F-9203-8B456F27385A/ThaliTest.app/www/index.html
,2016-09-27 09:23:34.677 ThaliTest[3408:6061566] JXcore Cordova plugin initializing
,2016-09-27 09:23:34.678 ThaliTest[3408:6061747] JXcore instance initializing
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
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  12
Number of passed tests:  12
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  0.01902604103088379
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
