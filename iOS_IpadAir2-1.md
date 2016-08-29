#### Test 82914073a7b15c1_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073a7b15c1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/CBCABCCD-9FA6-4D3A-9A1A-EF7903CD4428/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/CBCABCCD-9FA6-4D3A-9A1A-EF7903CD4428/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073a7b15c1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073a7b15c1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E3473079-C322-4E5F-8933-7EDB9D9CB6DA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57797"
,(lldb)     command script import "/tmp/CBCABCCD-9FA6-4D3A-9A1A-EF7903CD4428/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-29 18:38:35.249 ThaliTest[1291:2393772] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/25CEE37F-C7F0-4C1A-BFDE-C806A301F7F6/Library/Cookies/Cookies.binarycookies
,2016-08-29 18:38:35.656 ThaliTest[1291:2393772] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-29 18:38:35.657 ThaliTest[1291:2393772] Multi-tasking -> Device: YES, App: YES
,2016-08-29 18:38:35.677 ThaliTest[1291:2393772] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 18:38:37.834 ThaliTest[1291:2393772] Using UIWebView
,2016-08-29 18:38:37.844 ThaliTest[1291:2393772] [CDVTimer][handleopenurl] 0.443995ms
,2016-08-29 18:38:37.852 ThaliTest[1291:2393772] [CDVTimer][intentandnavigationfilter] 7.458031ms
,2016-08-29 18:38:37.853 ThaliTest[1291:2393772] [CDVTimer][gesturehandler] 0.347018ms
2016-08-29 18:38:37.853 ThaliTest[1291:2393772] [CDVTimer][TotalPluginStartup] 10.309041ms
,2016-08-29 18:38:44.338 ThaliTest[1291:2393772] Resetting plugins due to page load.
,2016-08-29 18:38:48.525 ThaliTest[1291:2393772] Finished load of: file:///var/mobile/Containers/Bundle/Application/E3473079-C322-4E5F-8933-7EDB9D9CB6DA/ThaliTest.app/www/index.html
,2016-08-29 18:38:48.741 ThaliTest[1291:2393772] JXcore Cordova plugin initializing
2016-08-29 18:38:48.742 ThaliTest[1291:2394064] JXcore instance initializing
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
Total number of executed tests:  20
Number of passed tests:  20
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  43.64476102590561
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
