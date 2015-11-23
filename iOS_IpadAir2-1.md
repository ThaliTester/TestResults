#### Test 503880196b4ec73_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/503880196b4ec73/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/04403ABC-D8BC-4CB5-9F1E-0A0B2980BBB5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/04403ABC-D8BC-4CB5-9F1E-0A0B2980BBB5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/503880196b4ec73/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/503880196b4ec73/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4DCC8009-1F8C-4F40-8708-93C686CCD213/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53861"
,(lldb)     command script import "/tmp/04403ABC-D8BC-4CB5-9F1E-0A0B2980BBB5/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-23 20:19:05.119 HelloWorld[1139:1463678] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/833EA943-107D-4E58-BDBC-EA6B24E29497/Library/Cookies/Cookies.binarycookies
,2015-11-23 20:19:05.397 HelloWorld[1139:1463678] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-23 20:19:05.398 HelloWorld[1139:1463678] Multi-tasking -> Device: YES, App: YES
,2015-11-23 20:19:05.400 HelloWorld[1139:1463678] Unlimited access to network resources
,2015-11-23 20:19:05.405 HelloWorld[1139:1463678] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-23 20:19:09.471 HelloWorld[1139:1463678] Resetting plugins due to page load.
,2015-11-23 20:19:10.718 HelloWorld[1139:1463678] Finished load of: file:///var/mobile/Containers/Bundle/Application/4DCC8009-1F8C-4F40-8708-93C686CCD213/HelloWorld.app/www/index.html
,2015-11-23 20:19:10.772 HelloWorld[1139:1463678] JXcore Cordova plugin initializing
,2015-11-23 20:19:10.773 HelloWorld[1139:1463834] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
Total memory 2084569088
Free memory 759545856
execPath /private/var/mobile/Containers/Bundle/Application/4DCC8009-1F8C-4F40-8708-93C686CCD213/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/4DCC8009-1,F8C-4F40-8708-93C686CCD213/HelloWorld.app/www/jxcore/
userPath []
2015-11-23 20:19:10.951 HelloWorld[1139:1463834] Native method ScreenInfo not found.
2015-11-23 20:19:10.951 HelloWorld[1139:1463834] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5092  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
