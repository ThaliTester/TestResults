#### Test 55613145ac448d4_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55613145ac448d4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/1A1F4474-9D1B-4F13-BE6F-27AB1B9BD460/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/1A1F4474-9D1B-4F13-BE6F-27AB1B9BD460/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55613145ac448d4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55613145ac448d4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A16CE881-C1C9-4A10-9A09-D142E452A1B4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53204"
,(lldb)     command script import "/tmp/1A1F4474-9D1B-4F13-BE6F-27AB1B9BD460/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success,
(lldb)     autoexit
,2016-01-12 11:58:28.793 ThaliTest[1291:4182009] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B55195AA-B762-4B49-8158-3A0145204888/Library/Cookies/Cookies.binarycookies
,2016-01-12 11:58:28.910 ThaliTest[1291:4182009] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-12 11:58:28.912 ThaliTest[1291:4182009] Multi-tasking -> Device: YES, App: YES
,2016-01-12 11:58:28.917 ThaliTest[1291:4182009] Unlimited access to network resources
,2016-01-12 11:58:28.929 ThaliTest[1291:4182009] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-12 11:58:34.933 ThaliTest[1291:4182009] Resetting plugins due to page load.
,2016-01-12 11:58:36.986 ThaliTest[1291:4182009] Finished load of: file:///var/mobile/Containers/Bundle/Application/A16CE881-C1C9-4A10-9A09-D142E452A1B4/ThaliTest.app/www/index.html
,2016-01-12 11:58:37.175 ThaliTest[1291:4182009] JXcore Cordova plugin initializing
,2016-01-12 11:58:37.177 ThaliTest[1291:4182146] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone5-1
,Test app app.js loaded
,TAP version 13
,# setup
,# multiplex can send data
,# teardown
,ok 1 String should be length:200
# setup
,# muxServerBridge
,# teardown
,server bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed

```
