#### Test 5024228542a63d7_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5024228542a63d7/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/290944E2-F4BC-42BF-8EB2-CBA81677F5AF/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/290944E2-F4BC-42BF-8EB2-CBA81677F5AF/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/5024228542a63d7/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5024228542a63d7/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/888D610D-B205-4394-A778-3D43489F2F0D/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50848"
,(lldb)     command script import "/tmp/290944E2-F4BC-42BF-8EB2-CBA81677F5AF/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-01-08 19:08:36.035 HelloWorld[1557:3232577] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0F42711A-1F98-4C28-BD1E-1B335DB5DD7B/Library/Cookies/Cookies.binarycookies
,2016-01-08 19:08:36.469 HelloWorld[1557:3232577] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 19:08:36.471 HelloWorld[1557:3232577] Multi-tasking -> Device: YES, App: YES
,2016-01-08 19:08:36.481 HelloWorld[1557:3232577] Unlimited access to network resources
,2016-01-08 19:08:36.492 HelloWorld[1557:3232577] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 19:08:45.071 HelloWorld[1557:3232577] Resetting plugins due to page load.
,2016-01-08 19:08:48.123 HelloWorld[1557:3232577] Finished load of: file:///var/mobile/Containers/Bundle/Application/888D610D-B205-4394-A778-3D43489F2F0D/HelloWorld.app/www/index.html
,2016-01-08 19:08:48.213 HelloWorld[1557:3232577] JXcore Cordova plugin initializing
2016-01-08 19:08:48.214 HelloWorld[1557:3232776] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,>> Apple-Iphone5s-1

Total memory 1048576000

Free memory 926547968

execPath /private/var/mobile/Containers/Bundle/Application/888D610D-B205-4394-A778-3D43489F2F0D/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/88,8D610D-B205-4394-A778-3D43489F2F0D/HelloWorld.app/www/jxcore/

userPath []

2016-01-08 19:08:48.437 HelloWorld[1557:3232776] Native method ScreenInfo not found.
2016-01-08 19:08:48.437 HelloWorld[1557:3232776] Native method ScreenBrightness not found.,
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5125  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
