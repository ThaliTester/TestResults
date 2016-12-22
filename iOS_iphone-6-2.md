#### Test 98710374837bb9b_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/98710374837bb9b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/19F4D81A-ACA4-4BF1-BDAA-6328A26F8454/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/19F4D81A-ACA4-4BF1-BDAA-6328A26F8454/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/98710374837bb9b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/98710374837bb9b/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/7743C767-E3CF-4075-8737-2F332246E8DA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50577"
,(lldb)     command script import "/tmp/19F4D81A-ACA4-4BF1-BDAA-6328A26F8454/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,error: process launch failed: timed out trying to launch app
,(lldb)     autoexit

```
