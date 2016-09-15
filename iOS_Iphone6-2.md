#### Test 83627337176b608_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337176b608/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/81C286B3-56ED-4D96-871D-F8E8A4199F1F/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/81C286B3-56ED-4D96-871D-F8E8A4199F1F/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337176b608/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337176b608/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/76559A94-A99B-48C0-9A46-2E28D51D4F66/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59231"
,(lldb)     command script import "/tmp/81C286B3-56ED-4D96-871D-F8E8A4199F1F/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 07:28:35.559 ThaliTest[861:892912] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9880E357-165B-494A-80F9-CB8092E60F60/Library/Cookies/Cookies.binarycookies
,2016-09-15 07:28:35.914 ThaliTest[861:892912] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 07:28:35.916 ThaliTest[861:892912] Multi-tasking -> Device: YES, App: YES
,2016-09-15 07:28:35.943 ThaliTest[861:892912] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 07:28:36.462 ThaliTest[861:892912] Using UIWebView
,2016-09-15 07:28:36.472 ThaliTest[861:892912] [CDVTimer][handleopenurl] 0.428021ms
,2016-09-15 07:28:36.480 ThaliTest[861:892912] [CDVTimer][intentandnavigationfilter] 7.357001ms
2016-09-15 07:28:36.481 ThaliTest[861:892912] [CDVTimer][gesturehandler] 0.415027ms
2016-09-15 07:28:36.482 ThaliTest[861:892912] [CDVTimer][TotalPluginStartup,] 10.217965ms
,2016-09-15 07:28:42.699 ThaliTest[861:892912] Resetting plugins due to page load.
,2016-09-15 07:28:43.052 ThaliTest[861:892912] Finished load of: file:///var/containers/Bundle/Application/76559A94-A99B-48C0-9A46-2E28D51D4F66/ThaliTest.app/www/index.html
,2016-09-15 07:28:43.411 ThaliTest[861:892912] JXcore Cordova plugin initializing
,2016-09-15 07:28:43.412 ThaliTest[861:893095] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-15 07:28:49.899 ThaliTest[861:893095] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-15 07:28:49.900 ThaliTest[861:893095] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-15 07:28:49.900 ThaliTest[861:893095] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-15 07:28:49.902 ThaliTest[861:893095] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-15 07:28:50.278 ThaliTest[861:893095] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  0.004527032375335693
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
