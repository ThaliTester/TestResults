#### Test 850469114943827_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469114943827/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/4E6F604B-A728-4BEF-AEF8-54944B486A41/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/4E6F604B-A728-4BEF-AEF8-54944B486A41/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469114943827/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469114943827/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/86BB4403-1F9F-4679-8A7C-029958A17AEB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63268"
,(lldb)     command script import "/tmp/4E6F604B-A728-4BEF-AEF8-54944B486A41/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 09:10:23.025 ThaliTest[3122:5552478] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/52735924-51AF-4466-A61F-545F3BE95BFB/Library/Cookies/Cookies.binarycookies
,2016-09-23 09:10:23.377 ThaliTest[3122:5552478] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 09:10:23.378 ThaliTest[3122:5552478] Multi-tasking -> Device: YES, App: YES
,2016-09-23 09:10:23.397 ThaliTest[3122:5552478] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 09:10:25.308 ThaliTest[3122:5552478] Using UIWebView
,2016-09-23 09:10:25.315 ThaliTest[3122:5552478] [CDVTimer][handleopenurl] 0.468969ms
,2016-09-23 09:10:25.322 ThaliTest[3122:5552478] [CDVTimer][intentandnavigationfilter] 6.510973ms
,2016-09-23 09:10:25.323 ThaliTest[3122:5552478] [CDVTimer][gesturehandler] 0.353992ms
,2016-09-23 09:10:25.323 ThaliTest[3122:5552478] [CDVTimer][TotalPluginStartup] 9.149015ms
,2016-09-23 09:10:31.900 ThaliTest[3122:5552478] Resetting plugins due to page load.
,2016-09-23 09:10:35.383 ThaliTest[3122:5552478] Finished load of: file:///var/mobile/Containers/Bundle/Application/86BB4403-1F9F-4679-8A7C-029958A17AEB/ThaliTest.app/www/index.html
,2016-09-23 09:10:35.600 ThaliTest[3122:5552478] JXcore Cordova plugin initializing
,2016-09-23 09:10:35.601 ThaliTest[3122:5552748] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,* thread #1: tid = 0x54b95e, 0x00000001200c4ecc dyld`ImageLoader::trieWalk(unsigned char const*, unsigned char const*, char const*) + 204, queue = 'com.apple.main-thread'
  * frame #0: 0x00000001200c4ecc dyld`ImageLoader::trieWalk(unsigned char const*, unsigned char const*, char const*) + 204
    frame #1: 0x00000001200c0520 dyld`ImageLoaderMegaDylib::hasDylib(char const*, unsigned int*) const + 40
    frame #2: 0x00000001200c06c0 dyld`ImageLoaderMegaDylib::findImageIndex(char const*) const + 28
    frame #3: 0x00000001200c1260 dyld`ImageLoaderMegaDylib::findExportedSymbolAddress(ImageLoader::LinkContext const&, char const*, ImageLoader const*, int, bool, ImageLoader const**, unsigned long*) const + 84
    frame #4: 0x00000001200cb9f4 dyld`ImageLoaderMachOCompressed::resolveTwolevel(ImageLoader::LinkContext const&, char const*, ImageLoader const*, ImageLoader const*, unsigned int, bool, bool, ImageLoader const**) + 116
    frame #5: 0x00000001200cbc44 dyld`ImageLoaderMachOCompressed::resolve(ImageLoader::LinkContext const&, char const*, unsigned char, long, ImageLoader const**, ImageLoaderMachOCompressed::LastLookup*, bool) + 280
    frame #6: 0x00000001200ccd98 dyld`ImageLoaderMachOCompressed::doBindFastLazySymbol(unsigned int, ImageLoader::LinkContext const&, void (*)(), void (*)()) + 204
    frame #7: 0x00000001200b7e38 dyld`dyld::fastBindLazySymbol(ImageLoader**, unsigned long) + 104
    frame #8: 0x000000019b420bb0 libdyld.dylib`dyld_stub_binder + 60
    frame #9: 0x00000001009217ac XCTest`-[XCTestCase performTest:] + 524
    frame #10: 0x000000010091f1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #11: 0x000000010091f1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #12: 0x000000010091f1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #13: 0x0000000186eafe60 Foundation`<redacted> + 340
    frame #14: 0x0000000185f24544 CoreFoundation`<redacted> + 24
    frame #15: 0x0000000185f23fd8 CoreFoundation`<redacted> + 540
    frame #16: 0x0000000185f21cd8 CoreFoundation`<redacted> + 724
    frame #17: 0x0000000185e50ca0 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #18: 0x0000000190ed0088 GraphicsServices`GSEventRunModal + 180
    frame #19: 0x000000018b568ffc UIKit`UIApplicationMain + 204
    frame #20: 0x00000001000c1d34 ThaliTest`main + 76
    frame #21: 0x000000019b4228b8 libdyld.dylib`<redacted> + 4

```
