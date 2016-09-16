#### Test 8552588742df921_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8552588742df921/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/3B3CE4D6-8EE9-4CCA-A283-C5EE373BEAD1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/3B3CE4D6-8EE9-4CCA-A283-C5EE373BEAD1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8552588742df921/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8552588742df921/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/666D24CC-765F-4090-9595-402A8942D8AC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58567"
,(lldb)     command script import "/tmp/3B3CE4D6-8EE9-4CCA-A283-C5EE373BEAD1/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-16 10:27:03.836 ThaliTest[2536:4657477] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/14D018E5-DD82-41D1-B1EB-E0E4D269CA53/Library/Cookies/Cookies.binarycookies
,2016-09-16 10:27:04.211 ThaliTest[2536:4657477] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-16 10:27:04.212 ThaliTest[2536:4657477] Multi-tasking -> Device: YES, App: YES
,2016-09-16 10:27:04.230 ThaliTest[2536:4657477] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-16 10:27:06.239 ThaliTest[2536:4657477] Using UIWebView
,2016-09-16 10:27:06.248 ThaliTest[2536:4657477] [CDVTimer][handleopenurl] 0.386000ms
,2016-09-16 10:27:06.256 ThaliTest[2536:4657477] [CDVTimer][intentandnavigationfilter] 6.574988ms
,2016-09-16 10:27:06.256 ThaliTest[2536:4657477] [CDVTimer][gesturehandler] 0.322044ms
,2016-09-16 10:27:06.257 ThaliTest[2536:4657477] [CDVTimer][TotalPluginStartup] 8.812010ms
,2016-09-16 10:27:13.760 ThaliTest[2536:4657477] Resetting plugins due to page load.
,2016-09-16 10:27:17.718 ThaliTest[2536:4657477] Finished load of: file:///var/mobile/Containers/Bundle/Application/666D24CC-765F-4090-9595-402A8942D8AC/ThaliTest.app/www/index.html
,2016-09-16 10:27:17.921 ThaliTest[2536:4657477] JXcore Cordova plugin initializing
2016-09-16 10:27:17.922 ThaliTest[2536:4657750] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-16 10:27:24.106 ThaliTest[2536:4657750] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-16 10:27:24.107 ThaliTest[2536:4657750] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-16 10:27:24.107 ThaliTest[2536:4657750] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-16 10:27:24.108 ThaliTest[2536:4657750] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-16 10:27:24.398 ThaliTest[2536:4657750] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005120992660522461
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
