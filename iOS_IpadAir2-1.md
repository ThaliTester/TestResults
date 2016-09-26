#### Test 864825826cfc86f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/864825826cfc86f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/9A8641AF-692E-48F5-A504-C4098DECE20C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/9A8641AF-692E-48F5-A504-C4098DECE20C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/864825826cfc86f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/864825826cfc86f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0D4D37DF-EC47-433C-B4AC-4B20F87BE673/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62092"
,(lldb)     command script import "/tmp/9A8641AF-692E-48F5-A504-C4098DECE20C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-26 16:58:43.916 ThaliTest[3371:5974097] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/19CFE344-3F09-4638-B8BD-3993BD24E735/Library/Cookies/Cookies.binarycookies
,2016-09-26 16:58:44.302 ThaliTest[3371:5974097] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-26 16:58:44.304 ThaliTest[3371:5974097] Multi-tasking -> Device: YES, App: YES
,2016-09-26 16:58:44.325 ThaliTest[3371:5974097] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-26 16:58:46.364 ThaliTest[3371:5974097] Using UIWebView
,2016-09-26 16:58:46.370 ThaliTest[3371:5974097] [CDVTimer][handleopenurl] 0.374019ms
,2016-09-26 16:58:46.377 ThaliTest[3371:5974097] [CDVTimer][intentandnavigationfilter] 6.389022ms
,2016-09-26 16:58:46.378 ThaliTest[3371:5974097] [CDVTimer][gesturehandler] 0.286043ms
2016-09-26 16:58:46.378 ThaliTest[3371:5974097] [CDVTimer][TotalPluginStartup] 8.525014ms
,2016-09-26 16:58:53.335 ThaliTest[3371:5974097] Resetting plugins due to page load.
,2016-09-26 16:58:56.596 ThaliTest[3371:5974097] Finished load of: file:///var/mobile/Containers/Bundle/Application/0D4D37DF-EC47-433C-B4AC-4B20F87BE673/ThaliTest.app/www/index.html
,2016-09-26 16:58:56.871 ThaliTest[3371:5974097] JXcore Cordova plugin initializing
,2016-09-26 16:58:56.872 ThaliTest[3371:5974344] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x15c640160>
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Optional("45B14DCC-E769-4155-8459-D47F65121828")
,nil
,nil
,Optional("C4C7AA63-29D5-4AAE-A9BB-1A379FB4925A")
,Optional("A7CD75D3-8E08-4DAC-9286-5B2670258A15")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  55
,Number of passed tests:  53
,Number of failed tests:  2
Number of ignored tests:  0
,Total duration:  18.46722400188446
Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
