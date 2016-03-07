#### Test 6170335106d974e_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6170335106d974e/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/A0F4C460-8BAA-4EA8-BFB4-EA919B1A4AB0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A0F4C460-8BAA-4EA8-BFB4-EA919B1A4AB0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/6170335106d974e/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6170335106d974e/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E4506D5E-BEE8-4C43-979B-AB9CEB12D11B/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50991"
,(lldb)     command script import "/tmp/A0F4C460-8BAA-4EA8-BFB4-EA919B1A4AB0/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-07 14:39:48.633 HelloWorld[835:1200859] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/36A9DDC5-6F90-4C1B-9EE2-E31AE05BAC28/Library/Cookies/Cookies.binarycookies
,2016-03-07 14:39:49.001 HelloWorld[835:1200859] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-07 14:39:49.002 HelloWorld[835:1200859] Multi-tasking -> Device: YES, App: YES
,2016-03-07 14:39:49.011 HelloWorld[835:1200859] Unlimited access to network resources
,2016-03-07 14:39:49.020 HelloWorld[835:1200859] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-07 14:39:57.735 HelloWorld[835:1200859] Resetting plugins due to page load.
,2016-03-07 14:40:00.954 HelloWorld[835:1200859] Finished load of: file:///var/mobile/Containers/Bundle/Application/E4506D5E-BEE8-4C43-979B-AB9CEB12D11B/HelloWorld.app/www/index.html
,2016-03-07 14:40:01.044 HelloWorld[835:1200859] JXcore Cordova plugin initializing
2016-03-07 14:40:01.045 HelloWorld[835:1201043] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,>> Apple-Iphone5s-1

,Total memory 1048576000

Free memory 639025152

execPath /private/var/mobile/Containers/Bundle/Application/E4506D5E-BEE8-4C43-979B-AB9CEB12D11B/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/E4506D5E-BEE8-4C43-979B-A,B9CEB12D11B/HelloWorld.app/www/jxcore/

userPath []

2016-03-07 14:40:01.277 HelloWorld[835:1201043] Native method ScreenInfo not found.
2016-03-07 14:40:01.277 HelloWorld[835:1201043] Native method ScreenBrightness not found.
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5120  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
