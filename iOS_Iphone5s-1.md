#### Test 80912877c1aacde_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/80912877c1aacde/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/B06138B4-03BD-4D70-94B2-89E193BC630D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B06138B4-03BD-4D70-94B2-89E193BC630D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/80912877c1aacde/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/80912877c1aacde/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4B6B9C53-6C3A-4945-B466-665EBC061591/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56043"
,(lldb)     command script import "/tmp/B06138B4-03BD-4D70-94B2-89E193BC630D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,dyld: Library not loaded: @rpath/ThaliCore.framework/ThaliCore
  Referenced from: /var/mobile/Containers/Bundle/Application/4B6B9C53-6C3A-4945-B466-665EBC061591/ThaliTest.app/ThaliTest
  Reason: no suitable image found.  Did find:
	/private/var/mobile/C,ontainers/Bundle/Application/4B6B9C53-6C3A-4945-B466-665EBC061591/ThaliTest.app/Frameworks/ThaliCore.framework/ThaliCore: mmap() errno=1 validating first page of '/private/var/mobile/Containers/Bundle/Application/4B6B9C53-6C3A-4945-B466-665EBC061591/ThaliT,est.app/Frameworks/ThaliCore.framework/ThaliCore'
	/private/var/mobile/Containers/Bundle/Application/4B6B9C53-6C3A-4945-B466-665EBC061591/ThaliTest.app/Frameworks/ThaliCore.framework/ThaliCore: mmap() errno=1 validating first page of '/private/var/mobile/,Containers/Bundle/Application/4B6B9C53-6C3A-4945-B466-665EBC061591/ThaliTest.app/Frameworks/ThaliCore.framework/ThaliCore'
,* thread #1: tid = 0x1ff8, 0x1fe2908c dyld`dyld_fatal_error, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
  * frame #0: 0x1fe2908c dyld`dyld_fatal_error
    frame #1: 0x1fe2b99a dyld`dyld::halt(char const*) + 74
    frame #2: 0x1fe2deaa dyld`dyld::_main(macho_header const*, unsigned long, int, char const**, char const**, char const**, unsigned long*) + 4298
    frame #3: 0x1fe291ee dyld`dyldbootstrap::start(macho_header const*, int, char const**, long, macho_header const*, unsigned long*) + 342
    frame #4: 0x1fe29040 dyld`_dyld_start + 64

```
