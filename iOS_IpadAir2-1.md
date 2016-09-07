#### Test 82914073126c10a_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073126c10a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/6B2FB55F-2687-451F-BFC9-C5971122C694/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/6B2FB55F-2687-451F-BFC9-C5971122C694/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073126c10a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073126c10a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8B25CB71-FD77-41D1-926F-86324B6A1F9D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55550"
,(lldb)     command script import "/tmp/6B2FB55F-2687-451F-BFC9-C5971122C694/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-07 15:27:54.573 ThaliTest[1913:3516856] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/80FC8403-35CD-44D3-B2BD-ADE45BB458A3/Library/Cookies/Cookies.binarycookies
,2016-09-07 15:27:54.806 ThaliTest[1913:3516856] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-07 15:27:54.807 ThaliTest[1913:3516856] Multi-tasking -> Device: YES, App: YES
,2016-09-07 15:27:54.820 ThaliTest[1913:3516856] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-07 15:27:55.630 ThaliTest[1913:3516856] Using UIWebView
,2016-09-07 15:27:55.632 ThaliTest[1913:3516856] [CDVTimer][handleopenurl] 0.117958ms
,2016-09-07 15:27:55.634 ThaliTest[1913:3516856] [CDVTimer][intentandnavigationfilter] 1.917005ms
2016-09-07 15:27:55.635 ThaliTest[1913:3516856] [CDVTimer][gesturehandler] 0.089049ms
2016-09-07 15:27:55.635 ThaliTest[1913:3516856] [CDVTimer][TotalPluginStartup] 2.564013ms
,2016-09-07 15:27:58.663 ThaliTest[1913:3516856] Resetting plugins due to page load.
,2016-09-07 15:28:00.080 ThaliTest[1913:3516856] Finished load of: file:///var/mobile/Containers/Bundle/Application/8B25CB71-FD77-41D1-926F-86324B6A1F9D/ThaliTest.app/www/index.html
,2016-09-07 15:28:00.218 ThaliTest[1913:3516856] JXcore Cordova plugin initializing
,2016-09-07 15:28:00.219 ThaliTest[1913:3517041] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  38
Number of passed tests:  38
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  12.91201400756836
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
