#### Test 80912877c1aacde_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/80912877c1aacde/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/D5CF4B33-1308-41C6-91AD-FE59810A4F50/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D5CF4B33-1308-41C6-91AD-FE59810A4F50/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/80912877c1aacde/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/80912877c1aacde/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/367B45DC-15EA-4B47-9DAB-460C9CCD5234/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56020"
,(lldb)     command script import "/tmp/D5CF4B33-1308-41C6-91AD-FE59810A4F50/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,dyld: Library not loaded: @rpath/ThaliCore.framework/ThaliCore
  Referenced from: /var/mobile/Containers/Bundle/Application/367B45DC-15EA-4B47-9DAB-460C9CCD5234/ThaliTest.app/ThaliTest
  Reason: no suitable image found.  Did find:
	/private/var/mobile/C,ontainers/Bundle/Application/367B45DC-15EA-4B47-9DAB-460C9CCD5234/ThaliTest.app/Frameworks/ThaliCore.framework/ThaliCore: mmap() errno=1 validating first page of '/private/var/mobile/Containers/Bundle/Application/367B45DC-15EA-4B47-9DAB-460C9CCD5234/ThaliTest.app/Frameworks/ThaliCore.framework/ThaliCore'
	/private/var/mobile/Containers/Bundle/Application/367B45DC-15EA-4B47-9DAB-460C9CCD5234/ThaliTest.app/Frameworks/ThaliCore.framework/ThaliCore: mmap() errno=1 validating first page of '/private/var/mobile/,Containers/Bundle/Application/367B45DC-15EA-4B47-9DAB-460C9CCD5234/ThaliTest.app/Frameworks/ThaliCore.framework/ThaliCore'
,* thread #1: tid = 0x1d98, 0x1fe9908c dyld`dyld_fatal_error, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
  * frame #0: 0x1fe9908c dyld`dyld_fatal_error
    frame #1: 0x1fe9b99a dyld`dyld::halt(char const*) + 74
    frame #2: 0x1fe9deaa dyld`dyld::_main(macho_header const*, unsigned long, int, char const**, char const**, char const**, unsigned long*) + 4298
    frame #3: 0x1fe991ee dyld`dyldbootstrap::start(macho_header const*, int, char const**, long, macho_header const*, unsigned long*) + 342
    frame #4: 0x1fe99040 dyld`_dyld_start + 64

```
