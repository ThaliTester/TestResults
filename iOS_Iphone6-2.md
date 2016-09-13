#### Test 836273370459b7a_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/836273370459b7a/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/4121F133-86E6-4857-BDD3-75C920F224EE/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/4121F133-86E6-4857-BDD3-75C920F224EE/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/836273370459b7a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/836273370459b7a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/62AD4815-0850-4D3B-883E-65743414C798/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49739"
,(lldb)     command script import "/tmp/4121F133-86E6-4857-BDD3-75C920F224EE/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 07:32:42.435 ThaliTest[627:651789] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F9F7DB2D-7840-492C-9464-827B6194092C/Library/Cookies/Cookies.binarycookies
,2016-09-13 07:32:42.772 ThaliTest[627:651789] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 07:32:42.773 ThaliTest[627:651789] Multi-tasking -> Device: YES, App: YES
,2016-09-13 07:32:42.795 ThaliTest[627:651789] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 07:32:43.232 ThaliTest[627:651789] Using UIWebView
,2016-09-13 07:32:43.238 ThaliTest[627:651789] [CDVTimer][handleopenurl] 0.371993ms
,2016-09-13 07:32:43.246 ThaliTest[627:651789] [CDVTimer][intentandnavigationfilter] 7.268965ms
2016-09-13 07:32:43.247 ThaliTest[627:651789] [CDVTimer][gesturehandler] 0.319004ms
2016-09-13 07:32:43.247 ThaliTest[627:651789] [CDVTimer][TotalPluginStartup,] 9.629011ms
,2016-09-13 07:32:49.416 ThaliTest[627:651789] Resetting plugins due to page load.
,2016-09-13 07:32:49.737 ThaliTest[627:651789] Finished load of: file:///var/containers/Bundle/Application/62AD4815-0850-4D3B-883E-65743414C798/ThaliTest.app/www/index.html
,2016-09-13 07:32:50.078 ThaliTest[627:651789] JXcore Cordova plugin initializing
,2016-09-13 07:32:50.079 ThaliTest[627:651983] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 07:32:56.559 ThaliTest[627:651983] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-13 07:32:56.559 ThaliTest[627:651983] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-13 07:32:56.560 ThaliTest[627:651983,] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-13 07:32:56.561 ThaliTest[627:651983] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,2016-09-13 07:32:56.956 ThaliTest[627:651983] jxcore: executeNativeTests: success
Total number of executed tests:  2
,Number of passed tests:  2
Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  0.004395008087158203
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
