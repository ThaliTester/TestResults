#### Test 50242285e132180_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285e132180/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/60731FED-B20A-4B10-A51D-6F4D3AE506B3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/60731FED-B20A-4B10-A51D-6F4D3AE506B3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285e132180/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285e132180/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4C625F75-6599-4F39-891C-85F6B7A85A22/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50202"
,(lldb)     command script import "/tmp/60731FED-B20A-4B10-A51D-6F4D3AE506B3/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-07 16:09:54.680 HelloWorld[398:155033] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D333EC9D-0085-4A7E-A08A-CA7B64B4242C/Library/Cookies/Cookies.binarycookies
,2015-12-07 16:09:55.104 HelloWorld[398:155033] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-07 16:09:55.105 HelloWorld[398:155033] Multi-tasking -> Device: YES, App: YES
,2015-12-07 16:09:55.109 HelloWorld[398:155033] Unlimited access to network resources
,2015-12-07 16:09:55.120 HelloWorld[398:155033] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 16:10:03.742 HelloWorld[398:155033] Resetting plugins due to page load.
,2015-12-07 16:10:06.693 HelloWorld[398:155033] Finished load of: file:///var/mobile/Containers/Bundle/Application/4C625F75-6599-4F39-891C-85F6B7A85A22/HelloWorld.app/www/index.html
,2015-12-07 16:10:06.797 HelloWorld[398:155033] JXcore Cordova plugin initializing
,2015-12-07 16:10:06.799 HelloWorld[398:155225] JXcore instance initializing
Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
,Total memory 1048576000
,Free memory 903528448
,execPath /private/var/mobile/Containers/Bundle/Application/4C625F75-6599-4F39-891C-85F6B7A85A22/HelloWorld.app/HelloWorld
,process.cwd /var/mobile/Containers/Bundle/Application/4C625F75-6599-4F39-891C-85F6B7A85A22/HelloWorld.app/www/jxcore/
,userPath []
,2015-12-07 16:10:07.052 HelloWorld[398:155225] Native method ScreenInfo not found.
,2015-12-07 16:10:07.053 HelloWorld[398:155225] Native method ScreenBrightness not found.
,Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5139  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
