#### Test 843892648a10bf1_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/843892648a10bf1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/60D8110D-71B3-4376-B583-631AB63DD797/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/60D8110D-71B3-4376-B583-631AB63DD797/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/843892648a10bf1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/843892648a10bf1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/222F0BF6-A085-46C1-976F-6425E7E9E15D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59821"
,(lldb)     command script import "/tmp/60D8110D-71B3-4376-B583-631AB63DD797/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-08 01:27:24.439 ThaliTest[1840:3803428] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C943B24E-712A-475B-AC01-8E2A8FE67DB9/Library/Cookies/Cookies.binarycookies
,2016-09-08 01:27:24.710 ThaliTest[1840:3803428] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-08 01:27:24.711 ThaliTest[1840:3803428] Multi-tasking -> Device: YES, App: YES
,2016-09-08 01:27:24.732 ThaliTest[1840:3803428] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-08 01:27:25.517 ThaliTest[1840:3803428] Using UIWebView
,2016-09-08 01:27:25.521 ThaliTest[1840:3803428] [CDVTimer][handleopenurl] 0.168025ms
2016-09-08 01:27:25.524 ThaliTest[1840:3803428] [CDVTimer][intentandnavigationfilter] 2.680004ms
2016-09-08 01:27:25.524 ThaliTest[1840:3803428] [CDVTimer][gesturehandle,r] 0.135005ms
2016-09-08 01:27:25.524 ThaliTest[1840:3803428] [CDVTimer][TotalPluginStartup] 3.616035ms
,2016-09-08 01:27:28.478 ThaliTest[1840:3803428] Resetting plugins due to page load.
,2016-09-08 01:27:29.878 ThaliTest[1840:3803428] Finished load of: file:///var/mobile/Containers/Bundle/Application/222F0BF6-A085-46C1-976F-6425E7E9E15D/ThaliTest.app/www/index.html
,2016-09-08 01:27:30.065 ThaliTest[1840:3803428] JXcore Cordova plugin initializing
,2016-09-08 01:27:30.066 ThaliTest[1840:3803614] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-08 01:27:41.175 ThaliTest[1840:3803614] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-08 01:27:41.176 ThaliTest[1840:3803614] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-08 01:27:41.177 ThaliTest[1840:3803614] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-08 01:27:41.180 ThaliTest[1840:3803614] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-08 01:27:41.557 ThaliTest[1840:3803614] jxcore: executeNativeTests: success
,*Native tests were executed*
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/222F0BF6-A085-46C1-976F-6425E7E9E15D/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/222F0BF6-A085-46C1-976F-6425E7E9E15D/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/222F0BF6-A085-46C1-976F-6425E7E9E15D/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/222F0BF6-A085-46C1-976F-6425E7E9E15D/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
,ERROR runTests: 
,2016-09-08 01:27:44.980 ThaliTest[1840:3803614] Error!: Error when loading file /private/var/mobile/Containers/Bundle/Application/222F0BF6-A085-46C1-976F-6425E7E9E15D/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find m,odule '../../thalilogger'
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/222F0BF6-A085-46C1-976F-6425E7E9E15D/ThaliTest.app/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/private/var/mobile/Containers/Bundle/Application/222F0BF6-A085-46C1-976F-6425E7E9E15D/ThaliTest.app/www/jxcore/runTests.js:26:11"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/222F0BF6-A085-46C1-976F-6425E7E9E15D/ThaliTest.app/w,ww/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/222F0BF6-A085-46C1-976F-6425E7E9E15D/ThaliTest.app/www/jxcore/runTests.js:38:7"},{"_fileName":"/private/var/m,obile/Containers/Bundle/Application/222F0BF6-A085-46C1-976F-6425E7E9E15D/ThaliTest.app/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/222F0BF6-A085-46C1-97,6F-6425E7E9E15D/ThaliTest.app/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionN,ame":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,WARN testUtils: logCallback not set!
,[ { _fileName: '/private/var/mobile/Containers/Bundle/Application/222F0BF6-A085-46C1-976F-6425E7E9E15D/ThaliTest.app/www/jxcore/runTests.js',
    _functionName: 'loadFile',
    _lineNumber: '26',
    _columnNumber: '11',
    _msg: '    at loadFile@/private/var/mobile/Containers/Bundle/Application/222F0BF6-A085-46C1-976F-6425E7E9E15D/ThaliTest.app/www/jxcore/runTests.js:26:11' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/222F0BF6-A085-46C1-976F-6425E7E9E15D/ThaliTest.app/www/jxcore/runTests.js',
    _functionName: '',
    _lineNumber: '38',
    _columnNumber: '7',
    _msg: '    at @/private/var/mobile/Containers/Bundle/Application/222F0BF6-A085-46C1-976F-6425E7E9E15D/ThaliTest.app/www/jxcore/runTests.js:38:7' },
  { _fileNam,e: '/private/var/mobile/Containers/Bundle/Application/222F0BF6-A085-46C1-976F-6425E7E9E15D/ThaliTest.app/www/jxcore/runTests.js',
    _functionName: '',
    _lineNumber: '35',
    _columnNumber: '3',
    _msg: '    at @/private/var/mobile/Containers/Bu,ndle/Application/222F0BF6-A085-46C1-976F-6425E7E9E15D/ThaliTest.app/www/jxcore/runTests.js:35:3' },
  { _fileName: 'module.js',
    _functionName: '$w.prototype._compile',
    _lineNumber: '621',
    _columnNumber: '8',
    _msg: '    at $w.prototype.,_compile@module.js:621:8' },
  { _fileName: 'module.js',
    _functionName: '$w._extensions[".js"]',
    _lineNumber: '651',
    _columnNumber: '1',
    _msg: '    at $w._extensions[".js"]@module.js:651:1' },
  { _fileName: 'module.js',
    _functio,nName: '$w.prototype.load',
    _lineNumber: '442',
    _columnNumber: '1',
    _msg: '    at $w.prototype.load@module.js:442:1' },
  toString: [Function] ]
,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
