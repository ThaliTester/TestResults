#### Test 79763830e108614_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830e108614/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/B1D56C86-F035-442A-95C1-09E6D1FCC9AE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B1D56C86-F035-442A-95C1-09E6D1FCC9AE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830e108614/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830e108614/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C3FBFDA2-DC2C-48B4-949C-CF7DC4CE8D8E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51251"
,(lldb)     command script import "/tmp/B1D56C86-F035-442A-95C1-09E6D1FCC9AE/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-08-24 13:22:47.767 ThaliTest[885:1678053] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0AF4431B-5150-4631-8A02-54158D930386/Library/Cookies/Cookies.binarycookies
,2016-08-24 13:22:48.208 ThaliTest[885:1678053] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-24 13:22:48.209 ThaliTest[885:1678053] Multi-tasking -> Device: YES, App: YES
,2016-08-24 13:22:48.227 ThaliTest[885:1678053] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-24 13:22:50.254 ThaliTest[885:1678053] Using UIWebView
,2016-08-24 13:22:50.261 ThaliTest[885:1678053] [CDVTimer][handleopenurl] 0.423014ms
,2016-08-24 13:22:50.268 ThaliTest[885:1678053] [CDVTimer][intentandnavigationfilter] 6.724954ms
,2016-08-24 13:22:50.269 ThaliTest[885:1678053] [CDVTimer][gesturehandler] 0.319004ms
,2016-08-24 13:22:50.269 ThaliTest[885:1678053] [CDVTimer][TotalPluginStartup] 9.307027ms
,2016-08-24 13:22:56.855 ThaliTest[885:1678053] Resetting plugins due to page load.
,2016-08-24 13:23:00.667 ThaliTest[885:1678053] Finished load of: file:///var/mobile/Containers/Bundle/Application/C3FBFDA2-DC2C-48B4-949C-CF7DC4CE8D8E/ThaliTest.app/www/index.html
,2016-08-24 13:23:00.816 ThaliTest[885:1678053] JXcore Cordova plugin initializing
,2016-08-24 13:23:00.816 ThaliTest[885:1678318] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-24 13:23:06.918 ThaliTest[885:1678318] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-24 13:23:06.918 ThaliTest[885:1678318] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-08-24 13:23:06.918 ThaliTest[885:1678318] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-24 13:23:06.920 ThaliTest[885:1678318] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-24 13:23:07.173 ThaliTest[885:1678318] Native method executeNativeTests not found.
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
