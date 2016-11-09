#### Test 89624796d0595a7_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/89624796d0595a7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/909A6971-E76C-4FDE-8C92-EB7C5A04FE40/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/909A6971-E76C-4FDE-8C92-EB7C5A04FE40/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/89624796d0595a7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/89624796d0595a7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BBAB0A52-D722-4A2D-B075-F3B919F93549/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58828"
,(lldb)     command script import "/tmp/909A6971-E76C-4FDE-8C92-EB7C5A04FE40/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-09 11:53:02.171 ThaliTest[5298:11373618] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9ABC544B-A0CB-44A4-A330-17B9DE026590/Library/Cookies/Cookies.binarycookies
,2016-11-09 11:53:02.514 ThaliTest[5298:11373618] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-09 11:53:02.515 ThaliTest[5298:11373618] Multi-tasking -> Device: YES, App: YES
,2016-11-09 11:53:02.531 ThaliTest[5298:11373618] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-09 11:53:04.511 ThaliTest[5298:11373618] Using UIWebView
,2016-11-09 11:53:04.520 ThaliTest[5298:11373618] [CDVTimer][handleopenurl] 0.333965ms
,2016-11-09 11:53:04.528 ThaliTest[5298:11373618] [CDVTimer][intentandnavigationfilter] 7.268012ms
,2016-11-09 11:53:04.529 ThaliTest[5298:11373618] [CDVTimer][gesturehandler] 0.356019ms
,2016-11-09 11:53:04.529 ThaliTest[5298:11373618] [CDVTimer][TotalPluginStartup] 9.535015ms
,2016-11-09 11:53:11.337 ThaliTest[5298:11373618] Resetting plugins due to page load.
,2016-11-09 11:53:14.479 ThaliTest[5298:11373618] Finished load of: file:///var/mobile/Containers/Bundle/Application/BBAB0A52-D722-4A2D-B075-F3B919F93549/ThaliTest.app/www/index.html
,2016-11-09 11:53:14.750 ThaliTest[5298:11373618] JXcore Cordova plugin initializing
,2016-11-09 11:53:14.750 ThaliTest[5298:11373872] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-09 10:53:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-09 10:53:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-09 10:53:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-09 10:53:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-09 10:53:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-09 10:53:59 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  34.84340798854828
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
