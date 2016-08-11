#### Test 797638305bc0289_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/797638305bc0289/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/268EC468-7B93-4980-BB62-B4CC48959301/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/268EC468-7B93-4980-BB62-B4CC48959301/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/797638305bc0289/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/797638305bc0289/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B455AC92-F6A3-46E3-AC01-047B05DD0273/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58865"
,(lldb)     command script import "/tmp/268EC468-7B93-4980-BB62-B4CC48959301/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,dyld: Library not loaded: @rpath/ThaliCore.framework/ThaliCore
  Referenced from: /var/mobile/Containers/Bundle/Application/B455AC92-F6A3-46E3-AC01-047B05DD0273/ThaliTest.app/ThaliTest
  Reason: no suitable image found.  Did find:
	/private/var/mobile/Containers/Bundle/Application/B455AC92-F6A3-46E3-AC01-047B05DD0273/ThaliTest.app/Frameworks/ThaliCore.framework/ThaliCore: mmap() errno=1 validating first page of '/private/var/mobile/Containers/Bundle/Application/B455AC92-F6A3-46E3-AC01-047B05DD0273/ThaliTest.app/Frameworks/ThaliCore.framework/ThaliCore'
	/private/var/mobile/Containers/Bundle/Application/B455AC92-F6A3-46E3-AC01-047B05DD0273/ThaliTest.app/Frameworks/ThaliCore.framework/ThaliCore: mmap() errno=1 validating first page of '/private/var/mobile/,Containers/Bundle/Application/B455AC92-F6A3-46E3-AC01-047B05DD0273/ThaliTest.app/Frameworks/ThaliCore.framework/ThaliCore'
,Process 1410 stopped
* thread #1: tid = 0x3fcc5e, 0x1fee108c dyld`dyld_fatal_error, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
    frame #0: 0x1fee108c dyld`dyld_fatal_error
dyld`dyld_fatal_error:
->  0x1fee108c <+0>: trap   
    0x1fee1090 <+4>: nop    

dyld`gdb_image_notifier:
    0x1fee1094 <+0>: bx     lr

dyld`dyldbootstrap::start:
    0x1fee1098 <+0>: push   {r4, r5, r6, r7, lr}
,* thread #1: tid = 0x3fcc5e, 0x1fee108c dyld`dyld_fatal_error, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
  * frame #0: 0x1fee108c dyld`dyld_fatal_error
    frame #1: 0x1fee399a dyld`dyld::halt(char const*) + 74
    frame #2: 0x1fee5eaa dyld`dyld::_main(macho_header const*, unsigned long, int, char const**, char const**, char const**, unsigned long*) + 4298
    frame #3: 0x1fee11ee dyld`dyldbootstrap::start(macho_header const*, int, char const**, long, macho_header const*, unsigned long*) + 342
    frame #4: 0x1fee1040 dyld`_dyld_start + 64

```
