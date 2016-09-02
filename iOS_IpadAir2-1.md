#### Test 81418577ad1885e_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/81418577ad1885e/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/EABF4FE0-7650-4EA3-8F5D-54EE56FAF8E8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/EABF4FE0-7650-4EA3-8F5D-54EE56FAF8E8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/81418577ad1885e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/81418577ad1885e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8A1DE368-AA7A-4754-95D5-0B136CCCDF48/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55110"
,(lldb)     command script import "/tmp/EABF4FE0-7650-4EA3-8F5D-54EE56FAF8E8/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-02 12:06:31.377 ThaliTest[1591:2868969] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F3735934-892E-4EEA-AD08-145CB4A2AB24/Library/Cookies/Cookies.binarycookies
,2016-09-02 12:06:31.776 ThaliTest[1591:2868969] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-02 12:06:31.777 ThaliTest[1591:2868969] Multi-tasking -> Device: YES, App: YES
,2016-09-02 12:06:31.796 ThaliTest[1591:2868969] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-02 12:06:33.652 ThaliTest[1591:2868969] Using UIWebView
,2016-09-02 12:06:33.659 ThaliTest[1591:2868969] [CDVTimer][handleopenurl] 0.530005ms
,2016-09-02 12:06:33.666 ThaliTest[1591:2868969] [CDVTimer][intentandnavigationfilter] 6.950021ms
,2016-09-02 12:06:33.667 ThaliTest[1591:2868969] [CDVTimer][gesturehandler] 0.327051ms
,2016-09-02 12:06:33.667 ThaliTest[1591:2868969] [CDVTimer][TotalPluginStartup] 9.460986ms
,2016-09-02 12:06:40.189 ThaliTest[1591:2868969] Resetting plugins due to page load.
,2016-09-02 12:06:43.729 ThaliTest[1591:2868969] Finished load of: file:///var/mobile/Containers/Bundle/Application/8A1DE368-AA7A-4754-95D5-0B136CCCDF48/ThaliTest.app/www/index.html
,2016-09-02 12:06:43.938 ThaliTest[1591:2868969] JXcore Cordova plugin initializing
,2016-09-02 12:06:43.938 ThaliTest[1591:2869222] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-02 12:06:50.060 ThaliTest[1591:2869222] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-02 12:06:50.060 ThaliTest[1591:2869222] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-02 12:06:50.060 ThaliTest[1591:2869222] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-02 12:06:50.062 ThaliTest[1591:2869222] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-02 12:06:50.354 ThaliTest[1591:2869222] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005137979984283447
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
