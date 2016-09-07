#### Test 843892648a10bf1_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/843892648a10bf1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/FFCBE849-6F5F-4FA5-8DBC-DDD100DDF717/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/FFCBE849-6F5F-4FA5-8DBC-DDD100DDF717/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/843892648a10bf1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/843892648a10bf1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/211F7BE1-D8BF-4B71-A87A-6A9BAC843844/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59823"
,(lldb)     command script import "/tmp/FFCBE849-6F5F-4FA5-8DBC-DDD100DDF717/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-08 01:27:31.077 ThaliTest[1931:3573079] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6991D353-DF92-47CB-82D8-AF181CE93FAF/Library/Cookies/Cookies.binarycookies
,2016-09-08 01:27:31.322 ThaliTest[1931:3573079] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-08 01:27:31.322 ThaliTest[1931:3573079] Multi-tasking -> Device: YES, App: YES
,2016-09-08 01:27:31.336 ThaliTest[1931:3573079] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-08 01:27:32.174 ThaliTest[1931:3573079] Using UIWebView
,2016-09-08 01:27:32.176 ThaliTest[1931:3573079] [CDVTimer][handleopenurl] 0.104010ms
,2016-09-08 01:27:32.178 ThaliTest[1931:3573079] [CDVTimer][intentandnavigationfilter] 1.869023ms
2016-09-08 01:27:32.178 ThaliTest[1931:3573079] [CDVTimer][gesturehandler] 0.082016ms
2016-09-08 01:27:32.178 ThaliTest[1931:3573079] [CDVTimer][TotalPluginStartup] 2.490997ms
,2016-09-08 01:27:35.308 ThaliTest[1931:3573079] Resetting plugins due to page load.
,2016-09-08 01:27:36.618 ThaliTest[1931:3573079] Finished load of: file:///var/mobile/Containers/Bundle/Application/211F7BE1-D8BF-4B71-A87A-6A9BAC843844/ThaliTest.app/www/index.html
,2016-09-08 01:27:36.752 ThaliTest[1931:3573079] JXcore Cordova plugin initializing
2016-09-08 01:27:36.752 ThaliTest[1931:3573278] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-08 01:27:45.100 ThaliTest[1931:3573278] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-08 01:27:45.100 ThaliTest[1931:3573278] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-08 01:27:45.100 ThaliTest[1931:3573278] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-08 01:27:45.102 ThaliTest[1931:3573278] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-08 01:27:45.388 ThaliTest[1931:3573278] jxcore: executeNativeTests: success
,*Native tests were executed*
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/211F7BE1-D8BF-4B71-A87A-6A9BAC843844/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/211F7BE1-D8BF-4B71-A87A-6A9BAC843844/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/211F7BE1-D8BF-4B71-A87A-6A9BAC843844/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/211F7BE1-D8BF-4B71-A87A-6A9BAC843844/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
,ERROR runTests: 
,2016-09-08 01:27:47.911 ThaliTest[1931:3573278] Error!: Error when loading file /private/var/mobile/Containers/Bundle/Application/211F7BE1-D8BF-4B71-A87A-6A9BAC843844/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find m,odule '../../thalilogger'
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/211F7BE1-D8BF-4B71-A87A-6A9BAC843844/ThaliTest.app/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at l,oadFile@/private/var/mobile/Containers/Bundle/Application/211F7BE1-D8BF-4B71-A87A-6A9BAC843844/ThaliTest.app/www/jxcore/runTests.js:26:11"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/211F7BE1-D8BF-4B71-A87A-6A9BAC843844/ThaliTest.app/w,ww/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/211F7BE1-D8BF-4B71-A87A-6A9BAC843844/ThaliTest.app/www/jxcore/runTests.js:38:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/211F7BE1-D8BF-4B71-A87A-6A9BAC843844/ThaliTest.app/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/211F7BE1-D8BF-4B71-A8,7A-6A9BAC843844/ThaliTest.app/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionN,ame":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,WARN testUtils: logCallback not set!
,[ { _fileName: '/private/var/mobile/Containers/Bundle/Application/211F7BE1-D8BF-4B71-A87A-6A9BAC843844/ThaliTest.app/www/jxcore/runTests.js',
    _functionName: 'loadFile',
    _lineNumber: '26',
    _columnNumber: '11',
    _msg: '    at loadFile@/pri,vate/var/mobile/Containers/Bundle/Application/211F7BE1-D8BF-4B71-A87A-6A9BAC843844/ThaliTest.app/www/jxcore/runTests.js:26:11' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/211F7BE1-D8BF-4B71-A87A-6A9BAC843844/ThaliTest.app/www/jxco,re/runTests.js',
    _functionName: '',
    _lineNumber: '38',
    _columnNumber: '7',
    _msg: '    at @/private/var/mobile/Containers/Bundle/Application/211F7BE1-D8BF-4B71-A87A-6A9BAC843844/ThaliTest.app/www/jxcore/runTests.js:38:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/211F7BE1-D8BF-4B71-A87A-6A9BAC843844/ThaliTest.app/www/jxcore/runTests.js',
    _functionName: '',
    _lineNumber: '35',
    _columnNumber: '3',
    _msg: '    at @/private/var/mobile/Containers/Bu,ndle/Application/211F7BE1-D8BF-4B71-A87A-6A9BAC843844/ThaliTest.app/www/jxcore/runTests.js:35:3' },
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
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
Error: Error when loading file /private/var/mobi
```
