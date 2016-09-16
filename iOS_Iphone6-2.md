#### Test 83627337176b608_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337176b608/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A20FE323-6461-4296-904B-4091CF408772/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/A20FE323-6461-4296-904B-4091CF408772/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337176b608/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337176b608/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/DB5EACAB-4DCB-44B9-A5E6-661A8205D817/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55842"
,(lldb)     command script import "/tmp/A20FE323-6461-4296-904B-4091CF408772/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-16 01:00:52.626 ThaliTest[906:974738] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AC028950-E0AE-4F28-A569-5E572C3B1CA1/Library/Cookies/Cookies.binarycookies
,2016-09-16 01:00:52.946 ThaliTest[906:974738] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-16 01:00:52.948 ThaliTest[906:974738] Multi-tasking -> Device: YES, App: YES
,2016-09-16 01:00:52.973 ThaliTest[906:974738] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-16 01:00:53.515 ThaliTest[906:974738] Using UIWebView
,2016-09-16 01:00:53.525 ThaliTest[906:974738] [CDVTimer][handleopenurl] 0.467002ms
,2016-09-16 01:00:53.532 ThaliTest[906:974738] [CDVTimer][intentandnavigationfilter] 7.110000ms
2016-09-16 01:00:53.533 ThaliTest[906:974738] [CDVTimer][gesturehandler] 0.326991ms
2016-09-16 01:00:53.534 ThaliTest[906:974738] [CDVTimer][TotalPluginStartup,] 9.500027ms
,2016-09-16 01:00:59.167 ThaliTest[906:974738] Resetting plugins due to page load.
,2016-09-16 01:00:59.525 ThaliTest[906:974738] Finished load of: file:///var/containers/Bundle/Application/DB5EACAB-4DCB-44B9-A5E6-661A8205D817/ThaliTest.app/www/index.html
,2016-09-16 01:00:59.979 ThaliTest[906:974738] JXcore Cordova plugin initializing
2016-09-16 01:00:59.980 ThaliTest[906:974938] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-16 01:01:06.477 ThaliTest[906:974938] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-16 01:01:06.477 ThaliTest[906:974938] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-16 01:01:06.477 ThaliTest[906:974938] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-16 01:01:06.479 ThaliTest[906:974938] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-16 01:01:06.858 ThaliTest[906:974938] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.004455029964447021
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
