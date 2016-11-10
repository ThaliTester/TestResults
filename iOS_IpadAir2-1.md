#### Test 910208789f3a884_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/910208789f3a884/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/07E907FD-3AD2-4872-88F4-6884E133EC8A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/07E907FD-3AD2-4872-88F4-6884E133EC8A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/910208789f3a884/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/910208789f3a884/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3296218B-5FC1-4AB1-BE73-1FCD16107A34/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57841"
,(lldb)     command script import "/tmp/07E907FD-3AD2-4872-88F4-6884E133EC8A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-10 14:45:17.512 ThaliTest[5383:11518597] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5843D3EE-EE78-4765-8CCE-A5D50BDF19AB/Library/Cookies/Cookies.binarycookies
,2016-11-10 14:45:17.741 ThaliTest[5383:11518597] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-10 14:45:17.742 ThaliTest[5383:11518597] Multi-tasking -> Device: YES, App: YES
,2016-11-10 14:45:17.754 ThaliTest[5383:11518597] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-10 14:45:18.589 ThaliTest[5383:11518597] Using UIWebView
,2016-11-10 14:45:18.592 ThaliTest[5383:11518597] [CDVTimer][handleopenurl] 0.097990ms
,2016-11-10 14:45:18.594 ThaliTest[5383:11518597] [CDVTimer][intentandnavigationfilter] 1.854002ms
2016-11-10 14:45:18.594 ThaliTest[5383:11518597] [CDVTimer][gesturehandler] 0.075996ms
2016-11-10 14:45:18.594 ThaliTest[5383:11518597] [CDVTimer][TotalPluginStartup] 2.444029ms
,2016-11-10 14:45:21.727 ThaliTest[5383:11518597] Resetting plugins due to page load.
,2016-11-10 14:45:23.120 ThaliTest[5383:11518597] Finished load of: file:///var/mobile/Containers/Bundle/Application/3296218B-5FC1-4AB1-BE73-1FCD16107A34/ThaliTest.app/www/index.html
,2016-11-10 14:45:23.260 ThaliTest[5383:11518597] JXcore Cordova plugin initializing
,2016-11-10 14:45:23.261 ThaliTest[5383:11518788] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-10 13:45:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-10 13:45:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-10 13:45:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-10 13:45:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-10 13:45:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-10 13:46:07 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  34.74436300992966
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
