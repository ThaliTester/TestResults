#### Test 561517803567b2a_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/561517803567b2a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/8098C294-7DD6-4455-9BCC-290983B710DA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/8098C294-7DD6-4455-9BCC-290983B710DA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/561517803567b2a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/561517803567b2a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CA17202F-9B96-4277-AC76-C4D970841BB1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56048"
,(lldb)     command script import "/tmp/8098C294-7DD6-4455-9BCC-290983B710DA/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-15 11:58:47.482 ThaliTest[2050:4405165] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/264E5BF0-119A-4F9D-97E8-C7BC7D50887B/Library/Cookies/Cookies.binarycookies
,2016-01-15 11:58:47.718 ThaliTest[2050:4405165] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-15 11:58:47.719 ThaliTest[2050:4405165] Multi-tasking -> Device: YES, App: YES
,2016-01-15 11:58:47.725 ThaliTest[2050:4405165] Unlimited access to network resources
,2016-01-15 11:58:47.731 ThaliTest[2050:4405165] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-15 11:58:51.873 ThaliTest[2050:4405165] Resetting plugins due to page load.
,2016-01-15 11:58:53.173 ThaliTest[2050:4405165] Finished load of: file:///var/mobile/Containers/Bundle/Application/CA17202F-9B96-4277-AC76-C4D970841BB1/ThaliTest.app/www/index.html
,2016-01-15 11:58:53.313 ThaliTest[2050:4405165] JXcore Cordova plugin initializing
2016-01-15 11:58:53.313 ThaliTest[2050:4405349] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data


```
