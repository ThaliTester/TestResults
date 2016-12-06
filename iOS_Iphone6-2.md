#### Test 95321062378f266_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/95321062378f266/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/53C81D13-8593-40F4-997F-8724D61FF978/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/53C81D13-8593-40F4-997F-8724D61FF978/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/95321062378f266/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/95321062378f266/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/A4C68F22-B6D0-4786-9723-C17EF140FBDE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60476"
,(lldb)     command script import "/tmp/53C81D13-8593-40F4-997F-8724D61FF978/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,Traceback (most recent call last):
  File "/tmp/53C81D13-8593-40F4-997F-8724D61FF978/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py", line 35, in run_command
,    lldb.target.Launch(lldb.SBLaunchInfo(shlex.split(args[1] and args[1] or '')), error)
,IndexError: ,list index out of range
,(lldb)     autoexit

```
