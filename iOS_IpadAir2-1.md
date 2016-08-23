#### Test 79763830b1f5deb_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830b1f5deb/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/B0F7A5DA-F8AC-42B4-95B9-A9139E46E6B9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B0F7A5DA-F8AC-42B4-95B9-A9139E46E6B9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830b1f5deb/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830b1f5deb/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0A5629D9-7504-4A2A-B2DF-8590F4B745F8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58586"
,(lldb)     command script import "/tmp/B0F7A5DA-F8AC-42B4-95B9-A9139E46E6B9/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,dyld: Library not loaded: @rpath/ThaliCore.framework/ThaliCore
  Referenced from: /var/mobile/Containers/Bundle/Application/0A5629D9-7504-4A2A-B2DF-8590F4B745F8/ThaliTest.app/ThaliTest
  Reason: no suitable image found.  Did find:
	/private/var/mobile/C,ontainers/Bundle/Application/0A5629D9-7504-4A2A-B2DF-8590F4B745F8/ThaliTest.app/Frameworks/ThaliCore.framework/ThaliCore: mmap() errno=1 validating first page of '/private/var/mobile/Containers/Bundle/Application/0A5629D9-7504-4A2A-B2DF-8590F4B745F8/ThaliT,est.app/Frameworks/ThaliCore.framework/ThaliCore'
	/private/var/mobile/Containers/Bundle/Application/0A5629D9-7504-4A2A-B2DF-8590F4B745F8/ThaliTest.app/Frameworks/ThaliCore.framework/ThaliCore: mmap() errno=1 validating first page of '/private/var/mobile/,Containers/Bundle/Application/0A5629D9-7504-4A2A-B2DF-8590F4B745F8/ThaliTest.app/Frameworks/ThaliCore.framework/ThaliCore'
,Process 827 stopped
* thread #1: tid = 0x17b832, 0x1fe9508c dyld`dyld_fatal_error, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
    frame #0: 0x1fe9508c dyld`dyld_fatal_error
dyld`dyld_fatal_error:
->  0x1fe9508c <+0>: trap   
    0x1fe95090 <+4>: nop    

dyld`gdb_image_notifier:
    0x1fe95094 <+0>: bx     lr

dyld`dyldbootstrap::start:
    0x1fe95098 <+0>: push   {r4, r5, r6, r7, lr}
,* thread #1: tid = 0x17b832, 0x1fe9508c dyld`dyld_fatal_error, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
  * frame #0: 0x1fe9508c dyld`dyld_fatal_error
    frame #1: 0x1fe9799a dyld`dyld::halt(char const*) + 74
    frame #2: 0x1fe99eaa dyld`dyld::_main(macho_header const*, unsigned long, int, char const**, char const**, char const**, unsigned long*) + 4298
    frame #3: 0x1fe951ee dyld`dyldbootstrap::start(macho_header const*, int, char const**, long, macho_header const*, unsigned long*) + 342
    frame #4: 0x1fe95040 dyld`_dyld_start + 64

```
