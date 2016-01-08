#### Test 54970261d953416_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/54970261d953416/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/4C3879A8-FF8A-45EE-B65F-AADEE12774EC/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/4C3879A8-FF8A-45EE-B65F-AADEE12774EC/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/54970261d953416/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/54970261d953416/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/706E7661-9761-4A74-8E89-7B53E75456F8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51113"
,(lldb)     command script import "/tmp/4C3879A8-FF8A-45EE-B65F-AADEE12774EC/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 20:11:53.952 ThaliTest[1136:3621391] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/510839CD-7C68-4EF0-AFB6-8AFDE7BAA570/Library/Cookies/Cookies.binarycookies
,2016-01-08 20:11:54.078 ThaliTest[1136:3621391] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 20:11:54.079 ThaliTest[1136:3621391] Multi-tasking -> Device: YES, App: YES
,2016-01-08 20:11:54.084 ThaliTest[1136:3621391] Unlimited access to network resources
,2016-01-08 20:11:54.096 ThaliTest[1136:3621391] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 20:12:04.898 ThaliTest[1136:3621391] Resetting plugins due to page load.
,2016-01-08 20:12:08.592 ThaliTest[1136:3621391] Finished load of: file:///var/mobile/Containers/Bundle/Application/706E7661-9761-4A74-8E89-7B53E75456F8/ThaliTest.app/www/index.html
,2016-01-08 20:12:08.801 ThaliTest[1136:3621391] JXcore Cordova plugin initializing
,2016-01-08 20:12:08.803 ThaliTest[1136:3621582] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded
,--= Surplus to requirements =--
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
