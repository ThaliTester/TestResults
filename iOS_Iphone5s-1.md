#### Test 83627337381d561_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337381d561/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8CE436AC-2CCD-4E79-8BE7-FA66329D36D3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8CE436AC-2CCD-4E79-8BE7-FA66329D36D3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337381d561/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337381d561/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/659F9A1D-31E0-477D-98A2-1C73ED93FF0F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64527"
,(lldb)     command script import "/tmp/8CE436AC-2CCD-4E79-8BE7-FA66329D36D3/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-07 11:35:32.170 ThaliTest[1785:3720924] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DF447948-2647-4EC5-AA97-9EAE8007308D/Library/Cookies/Cookies.binarycookies
,2016-09-07 11:35:32.436 ThaliTest[1785:3720924] Apache Cordova native platform version 4.1.1 is starting.
2016-09-07 11:35:32.437 ThaliTest[1785:3720924] Multi-tasking -> Device: YES, App: YES
,2016-09-07 11:35:32.456 ThaliTest[1785:3720924] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-07 11:35:33.309 ThaliTest[1785:3720924] Using UIWebView
,2016-09-07 11:35:33.312 ThaliTest[1785:3720924] [CDVTimer][handleopenurl] 0.289023ms
2016-09-07 11:35:33.315 ThaliTest[1785:3720924] [CDVTimer][intentandnavigationfilter] 2.792001ms
2016-09-07 11:35:33.315 ThaliTest[1785:3720924] [CDVTimer][gesturehandle,r] 0.122964ms
2016-09-07 11:35:33.315 ThaliTest[1785:3720924] [CDVTimer][TotalPluginStartup] 3.814995ms
,2016-09-07 11:35:36.478 ThaliTest[1785:3720924] Resetting plugins due to page load.
,2016-09-07 11:35:37.741 ThaliTest[1785:3720924] Finished load of: file:///var/mobile/Containers/Bundle/Application/659F9A1D-31E0-477D-98A2-1C73ED93FF0F/ThaliTest.app/www/index.html
,2016-09-07 11:35:37.925 ThaliTest[1785:3720924] JXcore Cordova plugin initializing
,2016-09-07 11:35:37.926 ThaliTest[1785:3721097] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-07 11:35:45.648 ThaliTest[1785:3721097] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-07 11:35:45.649 ThaliTest[1785:3721097] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-07 11:35:45.650 ThaliTest[1785:3721097] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {,"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-09-07 11:35:45.652 ThaliTest[1785:3721097] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,2016-09-07 11:35:46.030 ThaliTest[1785:3721097] jxcore: executeNativeTests: success
Total number of executed tests:  2
Number of passed tests:  2
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  0.004995048046112061
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
