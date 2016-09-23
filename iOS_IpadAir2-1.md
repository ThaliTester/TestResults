#### Test 8326889395f7d73_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8326889395f7d73/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/FFD81DC9-6925-4660-86C8-803E8228BDA4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/FFD81DC9-6925-4660-86C8-803E8228BDA4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8326889395f7d73/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8326889395f7d73/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C91AAA7F-1036-4455-A342-89AFA8CA0105/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59706"
,(lldb)     command script import "/tmp/FFD81DC9-6925-4660-86C8-803E8228BDA4/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 12:55:44.428 ThaliTest[3171:5577403] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/95309E06-66D3-48CC-8435-7E035B5E8B66/Library/Cookies/Cookies.binarycookies
,2016-09-23 12:55:44.815 ThaliTest[3171:5577403] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 12:55:44.817 ThaliTest[3171:5577403] Multi-tasking -> Device: YES, App: YES
,2016-09-23 12:55:44.840 ThaliTest[3171:5577403] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 12:55:46.867 ThaliTest[3171:5577403] Using UIWebView
,2016-09-23 12:55:46.876 ThaliTest[3171:5577403] [CDVTimer][handleopenurl] 0.331998ms
,2016-09-23 12:55:46.883 ThaliTest[3171:5577403] [CDVTimer][intentandnavigationfilter] 6.314993ms
,2016-09-23 12:55:46.884 ThaliTest[3171:5577403] [CDVTimer][gesturehandler] 0.292003ms
,2016-09-23 12:55:46.884 ThaliTest[3171:5577403] [CDVTimer][TotalPluginStartup] 8.530021ms
,2016-09-23 12:55:53.128 ThaliTest[3171:5577403] Resetting plugins due to page load.
,2016-09-23 12:55:55.968 ThaliTest[3171:5577403] Finished load of: file:///var/mobile/Containers/Bundle/Application/C91AAA7F-1036-4455-A342-89AFA8CA0105/ThaliTest.app/www/index.html
,2016-09-23 12:55:56.231 ThaliTest[3171:5577403] JXcore Cordova plugin initializing
,2016-09-23 12:55:56.232 ThaliTest[3171:5577662] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x13973ef40>
,Optional("B8C9E141-C512-499F-8222-9B87418069B7")
,nil
,nil
,Optional("E69D1A23-9173-4E8A-A2FB-6F5C210F3074")
,Optional("CFE55D6A-0975-4247-A532-E02B0DC09B51")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 12:56:21.961 ThaliTest[3171:5577403] BTM: attaching to BTServer
,2016-09-23 12:56:32.835 ThaliTest[3171:5577403] BTM: local device power state changed
2016-09-23 12:56:32.835 ThaliTest[3171:5577403] BTM: power is now on
,2016-09-23 12:56:37.505 ThaliTest[3171:5577403] BTM: local device power state changed
2016-09-23 12:56:37.506 ThaliTest[3171:5577403] BTM: power is now off
,*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  54
,Number of failed tests:  2
,Number of ignored tests:  0
,Total duration:  34.74037194252014
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
