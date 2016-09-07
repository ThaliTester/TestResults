#### Test 834440500e39eda_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/834440500e39eda/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/BB3DA465-32AA-476D-8D5F-34744B7AC263/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/BB3DA465-32AA-476D-8D5F-34744B7AC263/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/834440500e39eda/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/834440500e39eda/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FA1848B2-789E-4FCF-9CF5-D9FE763EE981/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62920"
,(lldb)     command script import "/tmp/BB3DA465-32AA-476D-8D5F-34744B7AC263/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-07 10:30:30.234 ThaliTest[1864:3483790] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/96EEC719-D42A-485E-9B05-D098C9F7FAD5/Library/Cookies/Cookies.binarycookies
,2016-09-07 10:30:30.470 ThaliTest[1864:3483790] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-07 10:30:30.471 ThaliTest[1864:3483790] Multi-tasking -> Device: YES, App: YES
,2016-09-07 10:30:30.485 ThaliTest[1864:3483790] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-07 10:30:31.286 ThaliTest[1864:3483790] Using UIWebView
,2016-09-07 10:30:31.288 ThaliTest[1864:3483790] [CDVTimer][handleopenurl] 0.110984ms
,2016-09-07 10:30:31.290 ThaliTest[1864:3483790] [CDVTimer][intentandnavigationfilter] 1.839042ms
2016-09-07 10:30:31.290 ThaliTest[1864:3483790] [CDVTimer][gesturehandler] 0.083983ms
2016-09-07 10:30:31.291 ThaliTest[1864:3483790] [CDVTimer][TotalPluginStartup] 2.470016ms
,2016-09-07 10:30:34.325 ThaliTest[1864:3483790] Resetting plugins due to page load.
,2016-09-07 10:30:35.726 ThaliTest[1864:3483790] Finished load of: file:///var/mobile/Containers/Bundle/Application/FA1848B2-789E-4FCF-9CF5-D9FE763EE981/ThaliTest.app/www/index.html
,2016-09-07 10:30:35.864 ThaliTest[1864:3483790] JXcore Cordova plugin initializing
,2016-09-07 10:30:35.865 ThaliTest[1864:3483967] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
Total number of executed tests:  15
,Number of passed tests:  15
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  38.59115594625473
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
