#### Test 829140733a8c9ab_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/829140733a8c9ab/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/C4EF930E-1A0D-4C8B-A66F-A718F3F47879/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C4EF930E-1A0D-4C8B-A66F-A718F3F47879/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/829140733a8c9ab/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/829140733a8c9ab/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5311F0E4-853A-4D26-A2B1-9AC1A9DC925E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63341"
,(lldb)     command script import "/tmp/C4EF930E-1A0D-4C8B-A66F-A718F3F47879/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-31 15:24:01.861 ThaliTest[1463:2633886] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4CB684D4-9904-426C-A115-9A418DF3AD6E/Library/Cookies/Cookies.binarycookies
,2016-08-31 15:24:02.263 ThaliTest[1463:2633886] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-31 15:24:02.265 ThaliTest[1463:2633886] Multi-tasking -> Device: YES, App: YES
,2016-08-31 15:24:02.284 ThaliTest[1463:2633886] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-31 15:24:04.402 ThaliTest[1463:2633886] Using UIWebView
,2016-08-31 15:24:04.412 ThaliTest[1463:2633886] [CDVTimer][handleopenurl] 0.397027ms
,2016-08-31 15:24:04.419 ThaliTest[1463:2633886] [CDVTimer][intentandnavigationfilter] 6.660044ms
,2016-08-31 15:24:04.420 ThaliTest[1463:2633886] [CDVTimer][gesturehandler] 0.343978ms
,2016-08-31 15:24:04.420 ThaliTest[1463:2633886] [CDVTimer][TotalPluginStartup] 9.001017ms
,2016-08-31 15:24:11.033 ThaliTest[1463:2633886] Resetting plugins due to page load.
,2016-08-31 15:24:14.958 ThaliTest[1463:2633886] Finished load of: file:///var/mobile/Containers/Bundle/Application/5311F0E4-853A-4D26-A2B1-9AC1A9DC925E/ThaliTest.app/www/index.html
,2016-08-31 15:24:15.157 ThaliTest[1463:2633886] JXcore Cordova plugin initializing
,2016-08-31 15:24:15.157 ThaliTest[1463:2634143] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
Total number of executed tests:  22
,Number of passed tests:  22
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  43.70039701461792
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
