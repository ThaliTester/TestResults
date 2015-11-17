#### Test 50388019c82294c_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019c82294c/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/D4CE6949-5596-4243-9601-DD79399D9DB9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/D4CE6949-5596-4243-9601-DD79399D9DB9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019c82294c/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019c82294c/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E7474C89-F66A-430F-9565-5B4064DBBA8A/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53825"
,(lldb)     command script import "/tmp/D4CE6949-5596-4243-9601-DD79399D9DB9/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-17 18:40:49.954 HelloWorld[676:447514] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8F8EFB17-348C-48D4-9800-1C8CAB3F5617/Library/Cookies/Cookies.binarycookies
,2015-11-17 18:40:50.325 HelloWorld[676:447514] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-17 18:40:50.326 HelloWorld[676:447514] Multi-tasking -> Device: YES, App: YES
,2015-11-17 18:40:50.329 HelloWorld[676:447514] Unlimited access to network resources
,2015-11-17 18:40:50.334 HelloWorld[676:447514] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-17 18:40:54.107 HelloWorld[676:447514] Resetting plugins due to page load.
,2015-11-17 18:40:54.454 HelloWorld[676:447514] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/E7474C89-F66A-430F-9565-5B4064DBBA8A/HelloWorld.app/www/index.html
,2015-11-17 18:40:54.559 HelloWorld[676:447514] JXcore Cordova plugin initializing
2015-11-17 18:40:54.561 HelloWorld[676:447628] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
Total memory 1047695360
Free memory 246738944
execPath /private/var/mobile/Containers/Bundle/Application/E7474C89-F66A-430F-9565-5B4064DBBA8A/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/E7,474C89-F66A-430F-9565-5B4064DBBA8A/HelloWorld.app/www/jxcore/
userPath []
2015-11-17 18:40:54.818 HelloWorld[676:447628] Native method ScreenInfo not found.
2015-11-17 18:40:54.819 HelloWorld[676:447628] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5106  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
