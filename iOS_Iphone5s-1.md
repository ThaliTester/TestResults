#### Test 6170335145aca32_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6170335145aca32/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/3D64AF97-882F-4E49-A455-0422F7D09592/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/3D64AF97-882F-4E49-A455-0422F7D09592/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6170335145aca32/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6170335145aca32/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5DA1BDFB-C041-4D7E-B9B7-BBED2743DD7D/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49475"
,(lldb)     command script import "/tmp/3D64AF97-882F-4E49-A455-0422F7D09592/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-08 10:02:06.429 HelloWorld[910:1323815] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/76163C29-09CB-453D-B456-FE89AB895130/Library/Cookies/Cookies.binarycookies
,2016-03-08 10:02:06.833 HelloWorld[910:1323815] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-08 10:02:06.835 HelloWorld[910:1323815] Multi-tasking -> Device: YES, App: YES
,2016-03-08 10:02:06.838 HelloWorld[910:1323815] Unlimited access to network resources
,2016-03-08 10:02:06.847 HelloWorld[910:1323815] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-08 10:02:15.127 HelloWorld[910:1323815] Resetting plugins due to page load.
,2016-03-08 10:02:18.024 HelloWorld[910:1323815] Finished load of: file:///var/mobile/Containers/Bundle/Application/5DA1BDFB-C041-4D7E-B9B7-BBED2743DD7D/HelloWorld.app/www/index.html
,2016-03-08 10:02:18.129 HelloWorld[910:1323815] JXcore Cordova plugin initializing
2016-03-08 10:02:18.130 HelloWorld[910:1324007] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,>> Apple-Iphone5s-1

Total memory 1048576000

Free memory 605192192

execPath /private/var/mobile/Containers/Bundle/Application/5DA1BDFB-C041-4D7E-B9B7-BBED2743DD7D/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/5D,A1BDFB-C041-4D7E-B9B7-BBED2743DD7D/HelloWorld.app/www/jxcore/

userPath []

2016-03-08 10:02:18.348 HelloWorld[910:1324007] Native method ScreenInfo not found.
2016-03-08 10:02:18.349 HelloWorld[910:1324007] Native method ScreenBrightness not found.
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5114  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
