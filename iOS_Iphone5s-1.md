#### Test 61703351a2a4153_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61703351a2a4153/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/E3E86CCD-C5E2-4233-94DE-79E5013AA49D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E3E86CCD-C5E2-4233-94DE-79E5013AA49D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61703351a2a4153/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61703351a2a4153/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D591EC20-22E3-43A7-9F5D-BFE6999E31DC/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49731"
,(lldb)     command script import "/tmp/E3E86CCD-C5E2-4233-94DE-79E5013AA49D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-04 13:20:18.770 HelloWorld[668:753658] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B70E77D4-10A7-46C4-80A2-5C6CBD9F3DFC/Library/Cookies/Cookies.binarycookies
,2016-03-04 13:20:19.180 HelloWorld[668:753658] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-04 13:20:19.182 HelloWorld[668:753658] Multi-tasking -> Device: YES, App: YES
,2016-03-04 13:20:19.186 HelloWorld[668:753658] Unlimited access to network resources
,2016-03-04 13:20:19.197 HelloWorld[668:753658] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-04 13:20:27.974 HelloWorld[668:753658] Resetting plugins due to page load.
,2016-03-04 13:20:31.041 HelloWorld[668:753658] Finished load of: file:///var/mobile/Containers/Bundle/Application/D591EC20-22E3-43A7-9F5D-BFE6999E31DC/HelloWorld.app/www/index.html
,2016-03-04 13:20:31.145 HelloWorld[668:753658] JXcore Cordova plugin initializing
2016-03-04 13:20:31.146 HelloWorld[668:753839] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,>> Apple-Iphone5s-1

,Total memory 1048576000

,Free memory 545456128

execPath /private/var/mobile/Containers/Bundle/Application/D591EC20-22E3-43A7-9F5D-BFE6999E31DC/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/D591EC20-22E3-43A7-9F5D-BFE6999E31DC/HelloWorld.app/,www/jxcore/

userPath []

2016-03-04 13:20:31.370 HelloWorld[668:753839] Native method ScreenInfo not found.
2016-03-04 13:20:31.371 HelloWorld[668:753839] Native method ScreenBrightness not found.
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5133  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
