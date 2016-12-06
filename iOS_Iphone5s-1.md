#### Test 95321062378f266_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/95321062378f266/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,(lldb) command source -s 0 '/tmp/0941F2AE-BA6E-4835-B61B-3D9F2E9CD1FB/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0941F2AE-BA6E-4835-B61B-3D9F2E9CD1FB/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/95321062378f266/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/95321062378f266/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DC76ABA1-1218-4406-B252-70BD2BE2CC96/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60387"
,(lldb)     command script import "/tmp/0941F2AE-BA6E-4835-B61B-3D9F2E9CD1FB/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,Traceback (most recent call last):
  File "/tmp/0941F2AE-BA6E-4835-B61B-3D9F2E9CD1FB/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py", line 35, in run_command
,    lldb.target.Launch(lldb.SBLaunchInfo(shlex.split(args[1] and args[1] or '')), error)
IndexError: list index out of range
,(lldb)     autoexit

```
