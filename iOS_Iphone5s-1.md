#### Test 834526170a57107_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/834526170a57107/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/9915E381-DA1B-4A34-B283-BD857331FD7E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/9915E381-DA1B-4A34-B283-BD857331FD7E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/834526170a57107/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/834526170a57107/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C446A455-1E16-44C7-A382-C1F0C33D1B27/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64856"
,(lldb)     command script import "/tmp/9915E381-DA1B-4A34-B283-BD857331FD7E/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-31 15:53:18.010 ThaliTest[1365:2712083] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C0DF4ADC-B859-43D9-B04F-6CBDA174D087/Library/Cookies/Cookies.binarycookies
,2016-08-31 15:53:18.440 ThaliTest[1365:2712083] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-31 15:53:18.442 ThaliTest[1365:2712083] Multi-tasking -> Device: YES, App: YES
,2016-08-31 15:53:18.465 ThaliTest[1365:2712083] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-31 15:53:20.133 ThaliTest[1365:2712083] Using UIWebView
,2016-08-31 15:53:20.141 ThaliTest[1365:2712083] [CDVTimer][handleopenurl] 0.617027ms
,2016-08-31 15:53:20.150 ThaliTest[1365:2712083] [CDVTimer][intentandnavigationfilter] 7.941008ms
2016-08-31 15:53:20.151 ThaliTest[1365:2712083] [CDVTimer][gesturehandler] 0.365019ms
2016-08-31 15:53:20.151 ThaliTest[1365:2712083] [CDVTimer][TotalPluginS,tartup] 10.843992ms
,2016-08-31 15:53:26.138 ThaliTest[1365:2712083] Resetting plugins due to page load.
,2016-08-31 15:53:29.263 ThaliTest[1365:2712083] Finished load of: file:///var/mobile/Containers/Bundle/Application/C446A455-1E16-44C7-A382-C1F0C33D1B27/ThaliTest.app/www/index.html
,2016-08-31 15:53:29.521 ThaliTest[1365:2712083] JXcore Cordova plugin initializing
,2016-08-31 15:53:29.523 ThaliTest[1365:2712324] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
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
,Total number of executed tests:  5
Number of passed tests:  5
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.00804603099822998
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
