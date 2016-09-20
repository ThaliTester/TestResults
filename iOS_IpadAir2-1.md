#### Test 850469116350bd7_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469116350bd7/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/D7FA06A1-CA5C-4DB5-81BB-E48045BBB76C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D7FA06A1-CA5C-4DB5-81BB-E48045BBB76C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469116350bd7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469116350bd7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/03970796-A414-47EB-AA8E-D5BC4CAFD373/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53889"
,(lldb)     command script import "/tmp/D7FA06A1-CA5C-4DB5-81BB-E48045BBB76C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-20 09:35:31.535 ThaliTest[2742:5149091] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4CAEE6FD-F189-4DBA-9917-7C784C2B7FF7/Library/Cookies/Cookies.binarycookies
,2016-09-20 09:35:31.923 ThaliTest[2742:5149091] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-20 09:35:31.924 ThaliTest[2742:5149091] Multi-tasking -> Device: YES, App: YES
,2016-09-20 09:35:31.944 ThaliTest[2742:5149091] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-20 09:35:34.086 ThaliTest[2742:5149091] Using UIWebView
,2016-09-20 09:35:34.096 ThaliTest[2742:5149091] [CDVTimer][handleopenurl] 0.375032ms
,2016-09-20 09:35:34.104 ThaliTest[2742:5149091] [CDVTimer][intentandnavigationfilter] 7.219970ms
,2016-09-20 09:35:34.104 ThaliTest[2742:5149091] [CDVTimer][gesturehandler] 0.360966ms
,2016-09-20 09:35:34.105 ThaliTest[2742:5149091] [CDVTimer][TotalPluginStartup] 9.546041ms
,2016-09-20 09:35:41.687 ThaliTest[2742:5149091] Resetting plugins due to page load.
,2016-09-20 09:35:45.852 ThaliTest[2742:5149091] Finished load of: file:///var/mobile/Containers/Bundle/Application/03970796-A414-47EB-AA8E-D5BC4CAFD373/ThaliTest.app/www/index.html
,2016-09-20 09:35:46.049 ThaliTest[2742:5149091] JXcore Cordova plugin initializing
,2016-09-20 09:35:46.050 ThaliTest[2742:5149366] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-20 09:35:52.169 ThaliTest[2742:5149366] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-20 09:35:52.170 ThaliTest[2742:5149366] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-20 09:35:52.170 ThaliTest[2742:5149366] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-20 09:35:52.172 ThaliTest[2742:5149366] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-20 09:35:52.462 ThaliTest[2742:5149366] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005015969276428223
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
