#### Test 506502789318894_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502789318894/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/08B5325D-141B-41C8-A91A-1D3225AADBA0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/08B5325D-141B-41C8-A91A-1D3225AADBA0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502789318894/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502789318894/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D1A67CA3-F9BE-4D9E-8CF9-035709D44813/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56810"
,(lldb)     command script import "/tmp/08B5325D-141B-41C8-A91A-1D3225AADBA0/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-27 12:39:27.814 ThaliTest[1466:2033244] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E774B9B1-F735-4227-897A-4A560BAEF239/Library/Cookies/Cookies.binarycookies
,2015-11-27 12:39:28.100 ThaliTest[1466:2033244] Apache Cordova native platform version 3.9.2 is starting.
2015-11-27 12:39:28.100 ThaliTest[1466:2033244] Multi-tasking -> Device: YES, App: YES
,2015-11-27 12:39:28.112 ThaliTest[1466:2033244] Unlimited access to network resources
,2015-11-27 12:39:28.118 ThaliTest[1466:2033244] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-27 12:39:32.350 ThaliTest[1466:2033244] Resetting plugins due to page load.
,2015-11-27 12:39:33.806 ThaliTest[1466:2033244] Finished load of: file:///var/mobile/Containers/Bundle/Application/D1A67CA3-F9BE-4D9E-8CF9-035709D44813/ThaliTest.app/www/index.html
,2015-11-27 12:39:33.958 ThaliTest[1466:2033244] JXcore Cordova plugin initializing
,2015-11-27 12:39:33.959 ThaliTest[1466:2033426] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,my name is : Apple-IpadAir2-1_PT8089
,check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded

```
