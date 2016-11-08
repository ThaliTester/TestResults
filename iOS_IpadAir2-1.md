#### Test 896247960fcbde9_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/896247960fcbde9/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/5E9C08D8-FB32-437A-ABE5-5042A1B5A528/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/5E9C08D8-FB32-437A-ABE5-5042A1B5A528/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/896247960fcbde9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/896247960fcbde9/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DBB5AAA7-6F9A-47EC-805A-16B113A8AF75/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64560"
,(lldb)     command script import "/tmp/5E9C08D8-FB32-437A-ABE5-5042A1B5A528/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-08 11:17:10.638 ThaliTest[5216:11238068] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/66787374-A579-46BB-9EFA-92596AEB6794/Library/Cookies/Cookies.binarycookies
,2016-11-08 11:17:10.973 ThaliTest[5216:11238068] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-08 11:17:10.974 ThaliTest[5216:11238068] Multi-tasking -> Device: YES, App: YES
,2016-11-08 11:17:10.990 ThaliTest[5216:11238068] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-08 11:17:12.795 ThaliTest[5216:11238068] Using UIWebView
,2016-11-08 11:17:12.801 ThaliTest[5216:11238068] [CDVTimer][handleopenurl] 0.387013ms
,2016-11-08 11:17:12.808 ThaliTest[5216:11238068] [CDVTimer][intentandnavigationfilter] 6.398022ms
,2016-11-08 11:17:12.809 ThaliTest[5216:11238068] [CDVTimer][gesturehandler] 0.298023ms
,2016-11-08 11:17:12.809 ThaliTest[5216:11238068] [CDVTimer][TotalPluginStartup] 8.795023ms
,2016-11-08 11:17:19.355 ThaliTest[5216:11238068] Resetting plugins due to page load.
,2016-11-08 11:17:22.534 ThaliTest[5216:11238068] Finished load of: file:///var/mobile/Containers/Bundle/Application/DBB5AAA7-6F9A-47EC-805A-16B113A8AF75/ThaliTest.app/www/index.html
,2016-11-08 11:17:22.807 ThaliTest[5216:11238068] JXcore Cordova plugin initializing
,2016-11-08 11:17:22.808 ThaliTest[5216:11238326] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-08 10:17:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-08 10:17:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-08 10:17:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-08 10:17:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-08 10:17:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-08 10:18:07 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  35.04493999481201
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
