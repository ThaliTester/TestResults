#### Test 836273379690449_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/836273379690449/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/848D4019-4AF9-4B21-B4ED-8351AF02B900/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/848D4019-4AF9-4B21-B4ED-8351AF02B900/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/836273379690449/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/836273379690449/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/09811A7F-2976-459B-872A-F1B3258CF78E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56629"
,(lldb)     command script import "/tmp/848D4019-4AF9-4B21-B4ED-8351AF02B900/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,error: process launch failed: timed out trying to launch app
,(lldb)     autoexit

```
