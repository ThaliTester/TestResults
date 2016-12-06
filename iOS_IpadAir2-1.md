#### Test 95321062378f266_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/95321062378f266/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,(lldb) command source -s 0 '/tmp/69D8305A-6889-4509-9866-ABB4D9E0497B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/69D8305A-6889-4509-9866-ABB4D9E0497B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/95321062378f266/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/95321062378f266/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A99EA4B9-56A9-493A-95E0-639D340702A1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60464"
,(lldb)     command script import "/tmp/69D8305A-6889-4509-9866-ABB4D9E0497B/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,Traceback (most recent call last):
  File "/tmp/69D8305A-6889-4509-9866-ABB4D9E0497B/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py", line 35, in run_command
,    lldb.target.Launch(lldb.SBLaunchInfo(shlex.split(args[1] and args[1] or '')), error)
IndexError: list index out of range
,(lldb)     autoexit

```
