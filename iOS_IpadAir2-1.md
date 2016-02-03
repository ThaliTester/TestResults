#### Test 57924002a578a80_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/57924002a578a80/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/DC0688CD-00AD-4612-9C2B-FA3D08FD9492/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/DC0688CD-00AD-4612-9C2B-FA3D08FD9492/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/57924002a578a80/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/57924002a578a80/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65256"
,(lldb)     command script import "/tmp/DC0688CD-00AD-4612-9C2B-FA3D08FD9492/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-03 01:40:49.197 ThaliTest[537:758406] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/76F81A21-6B4F-42C4-853E-25FCC7357A87/Library/Cookies/Cookies.binarycookies
,2016-02-03 01:40:49.667 ThaliTest[537:758406] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-03 01:40:49.668 ThaliTest[537:758406] Multi-tasking -> Device: YES, App: YES
,2016-02-03 01:40:49.677 ThaliTest[537:758406] Unlimited access to network resources
,2016-02-03 01:40:49.686 ThaliTest[537:758406] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-03 01:40:59.582 ThaliTest[537:758406] Resetting plugins due to page load.
,2016-02-03 01:41:03.786 ThaliTest[537:758406] Finished load of: file:///var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/index.html
,2016-02-03 01:41:03.922 ThaliTest[537:758406] JXcore Cordova plugin initializing
,2016-02-03 01:41:03.923 ThaliTest[537:758647] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,# teardown

,ok 1 String should be length:200

,# setup

,# enqueue and run in order

,# teardown

,ok 2 firstPromise setTimeout

,ok 3 firstPromise result

,ok 4 firstPromise testValue

,ok 5 secondPromise setTimeout

,ok 6 secondPromise result

,ok 7 secondPromise testValue

,ok 8 thirdPromise in promise

,ok 9 thirdPromise result

,ok 10 thirdPromise testValue

,# setup

,# basic

,# teardown

,ok 11 sane

,# setup

,# another

,# teardown

,ok 12 sane

,# setup

,# Can call start/stopListeningForAdvertisements

,# teardown

,2016-02-03 01:45:48.942 ThaliTest[537:758647] jxcore: startListeningForAdvertisements
,2016-02-03 01:45:48.944 ThaliTest[537:758647] multipeer manager: start client restart timer: 0x15e9b9b0
2016-02-03 01:45:48.944 ThaliTest[537:758647] jxcore: startListeningForAdvertisements: success
,ok 13 Can call startListeningForAdvertisements without error

,2016-02-03 01:45:48.947 ThaliTest[537:758647] jxcore: stopListeningForAdvertisements
2016-02-03 01:45:48.948 ThaliTest[537:758647] multipeer manager: stop client timer
2016-02-03 01:45:48.948 ThaliTest[537:758647] jxcore: stopListeningForAdvertisements: ,success
,ok 14 Can call stopListeningForAdvertisements without error

,# setup

,2016-02-03 01:45:49.263 ThaliTest[537:758647] jxcore: stopListeningForAdvertisements
,2016-02-03 01:45:49.264 ThaliTest[537:758647] jxcore: stopListeningForAdvertisements: success
,ok 15 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-03 01:45:49.266 ThaliTest[537:758647] jxcore: stopAdvertisingAndListening
2016-02-03 01:45:49.267 ThaliTest[537:758647] THEMultipeerManager stopping peer
,2016-02-03 01:45:49.267 ThaliTest[537:758647] jxcore: stopAdvertisingAndListening: success
,ok 16 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startListeningForAdvertisements twice is an error

,# teardown

,2016-02-03 01:45:49.432 ThaliTest[537:758647] jxcore: startListeningForAdvertisements
,2016-02-03 01:45:49.434 ThaliTest[537:758647] multipeer manager: start client restart timer: 0x15e9b9b0
2016-02-03 01:45:49.434 ThaliTest[537:758647] jxcore: startListeningForAdvertisements: success
,ok 17 Can call startListeningForAdvertisements without error

2016-02-03 01:45:49.437 ThaliTest[537:758647] jxcore: startListeningForAdvertisements
2016-02-03 01:45:49.437 ThaliTest[537:758647] jxcore: startListeningForAdvertisements: failure
,ok 18 Calling start twice is an error

,ok 19 Error must be "Call Stop!"

,# setup

,2016-02-03 01:45:49.713 ThaliTest[537:758647] jxcore: stopListeningForAdvertisements
2016-02-03 01:45:49.714 ThaliTest[537:758647] multipeer manager: stop client timer
,2016-02-03 01:45:49.715 ThaliTest[537:758647] jxcore: stopListeningForAdvertisements: success
,ok 20 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-03 01:45:49.719 ThaliTest[537:758647] jxcore: stopAdvertisingAndListening
,2016-02-03 01:45:49.720 ThaliTest[537:758647] THEMultipeerManager stopping peer
,2016-02-03 01:45:49.720 ThaliTest[537:758647] jxcore: stopAdvertisingAndListening: success
,ok 21 Should be able to call stopAdvertisingAndListening in teardown

,# Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-02-03 01:45:49.776 ThaliTest[537:758647] jxcore: startUpdateAdvertisingAndListening
,2016-02-03 01:45:49.777 ThaliTest[537:758647] server: starting 604E1E12-82D2-49A4-92A0-2119F4D3B9A4:1
,2016-02-03 01:45:49.779 ThaliTest[537:758647] multipeer manager: start client restart timer: 0x15e9b9b0
,2016-02-03 01:45:49.779 ThaliTest[537:758647] THEMultipeerManager initialized peer 604E1E12-82D2-49A4-92A0-2119F4D3B9A4:1
2016-02-03 01:45:49.781 ThaliTest[537:758647] jxcore: startUpdateAdvertisingAndListening: success
ok 22 Can call startUpdateAdvertis,ingAndListening without error

2016-02-03 01:45:49.783 ThaliTest[537:758647] jxcore: stopAdvertisingAndListening
2016-02-03 01:45:49.784 ThaliTest[537:758647] THEMultipeerManager stopping peer
,2016-02-03 01:45:49.784 ThaliTest[537:758647] multipeer manager: stop client timer
,2016-02-03 01:45:49.788 ThaliTest[537:758647] jxcore: stopAdvertisingAndListening: success
ok 23 Can call stopAdvertisingAndListening without error

,# setup

,2016-02-03 01:45:49.813 ThaliTest[537:758647] jxcore: stopListeningForAdvertisements
,2016-02-03 01:45:49.813 ThaliTest[537:758647] jxcore: stopListeningForAdvertisements: success
,ok 24 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-03 01:45:49.816 ThaliTest[537:758647] jxcore: stopAdvertisingAndListening
,2016-02-03 01:45:49.816 ThaliTest[537:758647] THEMultipeerManager stopping peer
2016-02-03 01:45:49.817 ThaliTest[537:758647] jxcore: stopAdvertisingAndListening: success
,ok 25 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startUpdateAdvertisingAndListening twice is NOT and error

,# teardown

,2016-02-03 01:45:49.860 ThaliTest[537:758647] jxcore: startUpdateAdvertisingAndListening
,2016-02-03 01:45:49.862 ThaliTest[537:758647] server: starting 604E1E12-82D2-49A4-92A0-2119F4D3B9A4:2
,2016-02-03 01:45:49.863 ThaliTest[537:758647] multipeer manager: start client restart timer: 0x15e9b9b0
2016-02-03 01:45:49.863 ThaliTest[537:758647] THEMultipeerManager initialized peer 604E1E12-82D2-49A4-92A0-2119F4D3B9A4:2
2016-02-03 01:45:49.863 ThaliTest[537:758647] jxcore: startUpdateAdvertisingAndListening: success
,ok 26 Can call startUpdateAdvertisingAndListening without error

,2016-02-03 01:45:49.866 ThaliTest[537:758647] jxcore: startUpdateAdvertisingAndListening
2016-02-03 01:45:49.866 ThaliTest[537:758647] THEMultipeerManager stopping peer
2016-02-03 01:45:49.867 ThaliTest[537:758647] multipeer manager: stop client timer
,2016-02-03 01:45:49.867 ThaliTest[537:758647] server: starting 604E1E12-82D2-49A4-92A0-2119F4D3B9A4:3
,2016-02-03 01:45:49.869 ThaliTest[537:758647] multipeer manager: start client restart timer: 0x15e9b9b0
2016-02-03 01:45:49.869 ThaliTest[537:758647] THEMultipeerManager initialized peer 604E1E12-82D2-49A4-92A0-2119F4D3B9A4:3
2016-02-03 01:45:49.869 ThaliTest[537:758647] jxcore: startUpdateAdvertisingAndListening: success
ok 27 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-02-03 01:45:49.894 ThaliTest[537:758647] jxcore: stopListeningForAdvertisements
,2016-02-03 01:45:49.895 ThaliTest[537:758647] jxcore: stopListeningForAdvertisements: success
,ok 28 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-03 01:45:49.898 ThaliTest[537:758647] jxcore: stopAdvertisingAndListening
,2016-02-03 01:45:49.899 ThaliTest[537:758647] THEMultipeerManager stopping peer
,2016-02-03 01:45:49.899 ThaliTest[537:758647] multipeer manager: stop client timer
2016-02-03 01:45:49.900 ThaliTest[537:758647] jxcore: stopAdvertisingAndListening: success
,ok 29 Should be able to call stopAdvertisingAndListening in teardown

,# peerAvailabilityChange is called

,# teardown

,2016-02-03 01:45:49.945 ThaliTest[537:758647] jxcore: startUpdateAdvertisingAndListening
,2016-02-03 01:45:49.946 ThaliTest[537:758647] server: starting 604E1E12-82D2-49A4-92A0-2119F4D3B9A4:4
,2016-02-03 01:45:49.947 ThaliTest[537:758647] multipeer manager: start client restart timer: 0x15e9b9b0
2016-02-03 01:45:49.947 ThaliTest[537:758647] THEMultipeerManager initialized peer 604E1E12-82D2-49A4-92A0-2119F4D3B9A4:4
2016-02-03 01:45:49.948 Thal,iTest[537:758647] jxcore: startUpdateAdvertisingAndListening: success
,ok 30 Can call startUpdateAdvertisingAndListeningwithout error

2016-02-03 01:45:49.950 ThaliTest[537:758647] jxcore: startListeningForAdvertisements
,2016-02-03 01:45:49.950 ThaliTest[537:758647] multipeer manager: stop client timer
2016-02-03 01:45:49.952 ThaliTest[537:758647] multipeer manager: start client restart timer: 0x15e9b9b0
2016-02-03 01:45:49.952 ThaliTest[537:758647] jxcore: startListenin,gForAdvertisements: success
,ok 31 Can call startListeningForAdvertisements without error

,2016-02-03 01:45:51.104 ThaliTest[537:758406] client: found new peer: FF83CC42-8AAD-4E03-8AEC-0991285D1ADB:4
,ok 32 peers must be an array

,ok 33 peers must not be zero-length

,ok 34 peer must have peerIdentifier

,ok 35 peerIdentifier must be a string

,ok 36 peer must have peerAvailable

,ok 37 peer must have pleaseConnect

,# setup

,2016-02-03 01:45:52.719 ThaliTest[537:758647] jxcore: stopListeningForAdvertisements
2016-02-03 01:45:52.720 ThaliTest[537:758647] jxcore: stopListeningForAdvertisements: success
,ok 38 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-03 01:45:52.722 ThaliTest[537:758647] jxcore: stopAdvertisingAndListening
,2016-02-03 01:45:52.723 ThaliTest[537:758647] THEMultipeerManager stopping peer
,2016-02-03 01:45:52.724 ThaliTest[537:758647] multipeer manager: stop client timer
2016-02-03 01:45:52.724 ThaliTest[537:758647] jxcore: stopAdvertisingAndListening: success
,ok 39 Should be able to call stopAdvertisingAndListening in teardown

,# Can connect to a remote peer

,# teardown

,2016-02-03 01:46:09.784 ThaliTest[537:758647] Error!: net is not defined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js","_functionName,":"","_lineNumber":"117","_columnNumber":"7","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js:117:7"},{"_fileName":"/private/var/mobile/Contain,ers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"declareTest/</<","_lineNumber":"82","_columnNumber":"7","_msg":"    at declareTest/</<@/private/var/mobile/Containers/Bundle/Applicatio,n/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/lib/thali-tape.js:82:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_module,s/component-emitter/index.js","_functionName":"on","_lineNumber":"63","_columnNumber":"5","_msg":"    at on@/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_m,odules/component-emitter/index.js:63:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"E,mitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/,component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineN,umber":"263","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5"},{"_fileName":"/priv,ate/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"221","_columnNumber":"7","_msg":"    at Socke,t.prototype.onpacket@/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/E9C069D,D-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Contai,ners/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738,600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bund,le/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/,ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"333","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/E9C069,DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3"}]
Uncaught Exception: ReferenceError: net is not defined

,[ { _fileName: '/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js',
    _functionName: '',
    _lineNumber: '117',
    _columnNumber: '7',
    _msg: '    at, @/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js:117:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738,600F4/ThaliTest.app/www/jxcore/lib/thali-tape.js',
    _functionName: 'declareTest/</<',
    _lineNumber: '82',
    _columnNumber: '7',
    _msg: '    at declareTest/</<@/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F4137386,00F4/ThaliTest.app/www/jxcore/lib/thali-tape.js:82:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',,
    _functionName: 'on',
    _lineNumber: '63',
    _columnNumber: '5',
    _msg: '    at on@/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/co,mponent-emitter/index.js:63:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: ',Emitter.prototype.emit',
    _lineNumber: '131',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-clie,nt/node_modules/component-emitter/index.js:131:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.,prototype.onevent',
    _lineNumber: '263',
    _columnNumber: '5',
    _msg: '    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/,lib/socket.js:263:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.onpacket',
    _li,neNumber: '221',
    _columnNumber: '7',
    _msg: '    at Socket.prototype.onpacket@/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7' },
  ,{ _fileName: '/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21,',
    _columnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
 , { _fileName: '/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineN,umber: '131',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/in,dex.js:131:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js',
    _functionName: 'Manager.prototype.ondecoded',
    _lineNu,mber: '333',
    _columnNumber: '3',
    _msg: '    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3' },
  t,oString: [Function] ]

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

ReferenceError: net is not defined (/private/var/mobile/Containers/Bundle/Application/E9C069DD-D2A4-4032-854C-F413738600F4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js 117:6)


```
