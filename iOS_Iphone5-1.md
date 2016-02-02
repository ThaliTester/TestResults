#### Test 575312431f256a6_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/575312431f256a6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/F54E2443-D7B7-4924-994C-D17CED9A67F2/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/F54E2443-D7B7-4924-994C-D17CED9A67F2/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/575312431f256a6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/575312431f256a6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64886"
,(lldb)     command script import "/tmp/F54E2443-D7B7-4924-994C-D17CED9A67F2/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-02 18:23:39.445 ThaliTest[2373:7487891] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/446B6888-7A98-4E0C-9F1F-6A4AA26B609A/Library/Cookies/Cookies.binarycookies
,2016-02-02 18:23:39.547 ThaliTest[2373:7487891] Apache Cordova native platform version 3.9.2 is starting.
2016-02-02 18:23:39.548 ThaliTest[2373:7487891] Multi-tasking -> Device: YES, App: YES
,2016-02-02 18:23:39.553 ThaliTest[2373:7487891] Unlimited access to network resources
,2016-02-02 18:23:39.564 ThaliTest[2373:7487891] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-02 18:23:46.059 ThaliTest[2373:7487891] Resetting plugins due to page load.
,2016-02-02 18:23:48.345 ThaliTest[2373:7487891] Finished load of: file:///var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/index.html
,2016-02-02 18:23:48.531 ThaliTest[2373:7487891] JXcore Cordova plugin initializing
,2016-02-02 18:23:48.658 ThaliTest[2373:7488126] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded
,
,TAP version 13

,# setup

,# multiplex can send data

,# teardown

,ok 1 String should be length:200

# setup

,# enqueue and run in order

,# teardown

,ok 2 firstPromise setTimeout

,ok 3 firstPromise result

ok 4 firstPromise testValue

,ok 5 secondPromise setTimeout

,ok 6 secondPromise result

ok 7 secondPromise testValue

ok 8 thirdPromise in promise

ok 9 thirdPromise result

ok 10 thirdPromise testValue

# setup

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

,2016-02-02 18:30:21.980 ThaliTest[2373:7488126] jxcore: startListeningForAdvertisements
,2016-02-02 18:30:21.982 ThaliTest[2373:7488126] multipeer manager: start client restart timer: 0x176f5b80
2016-02-02 18:30:21.983 ThaliTest[2373:7488126] jxcore: startListeningForAdvertisements: success
ok 13 Can call startListeningForAdvertisements with,out error

2016-02-02 18:30:21.984 ThaliTest[2373:7488126] jxcore: stopListeningForAdvertisements
2016-02-02 18:30:21.984 ThaliTest[2373:7488126] multipeer manager: stop client timer
2016-02-02 18:30:21.984 ThaliTest[2373:7488126] jxcore: stopListening,ForAdvertisements: success
ok 14 Can call stopListeningForAdvertisements without error

# setup

,2016-02-02 18:30:46.121 ThaliTest[2373:7488126] jxcore: stopListeningForAdvertisements
2016-02-02 18:30:46.121 ThaliTest[2373:7488126] jxcore: stopListeningForAdvertisements: success
ok 15 Should be able to call stopListeningForAdvertisments in teardown,

2016-02-02 18:30:46.122 ThaliTest[2373:7488126] jxcore: stopAdvertisingAndListening
2016-02-02 18:30:46.122 ThaliTest[2373:7488126] THEMultipeerManager stopping peer
2016-02-02 18:30:46.122 ThaliTest[2373:7488126] jxcore: stopAdvertisingAndListening: ,success
ok 16 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startListeningForAdvertisements twice is an error

,# teardown

,2016-02-02 18:30:55.727 ThaliTest[2373:7488126] jxcore: startListeningForAdvertisements
2016-02-02 18:30:55.728 ThaliTest[2373:7488126] multipeer manager: start client restart timer: 0x176f5b80
2016-02-02 18:30:55.728 ThaliTest[2373:7488126] jxcore: startListeningForAdvertisements: success
,ok 17 Can call startListeningForAdvertisements without error

2016-02-02 18:30:55.730 ThaliTest[2373:7488126] jxcore: startListeningForAdvertisements
,2016-02-02 18:30:55.730 ThaliTest[2373:7488126] jxcore: startListeningForAdvertisements: failure
,ok 18 Calling start twice is an error

ok 19 Error must be "Call Stop!"

,# setup

,2016-02-02 18:31:15.729 ThaliTest[2373:7487891] multipeer manager: restart client
,2016-02-02 18:31:17.222 ThaliTest[2373:7488126] jxcore: stopListeningForAdvertisements
2016-02-02 18:31:17.222 ThaliTest[2373:7488126] multipeer manager: stop client timer
2016-02-02 18:31:17.223 ThaliTest[2373:7488126] jxcore: stopListeningForAdvertisem,ents: success
ok 20 Should be able to call stopListeningForAdvertisments in teardown

2016-02-02 18:31:17.223 ThaliTest[2373:7488126] jxcore: stopAdvertisingAndListening
2016-02-02 18:31:17.224 ThaliTest[2373:7488126] THEMultipeerManager stopping peer,
2016-02-02 18:31:17.224 ThaliTest[2373:7488126] jxcore: stopAdvertisingAndListening: success
ok 21 Should be able to call stopAdvertisingAndListening in teardown

,# Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-02-02 18:31:18.058 ThaliTest[2373:7488126] jxcore: startUpdateAdvertisingAndListening
2016-02-02 18:31:18.058 ThaliTest[2373:7488126] server: starting 235D5B73-4DF1-4526-AC37-461C084169C7:1
2016-02-02 18:31:18.059 ThaliTest[2373:7488126] multipeer m,anager: start client restart timer: 0x176f5b80
2016-02-02 18:31:18.059 ThaliTest[2373:7488126] THEMultipeerManager initialized peer 235D5B73-4DF1-4526-AC37-461C084169C7:1
2016-02-02 18:31:18.059 ThaliTest[2373:7488126] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 22 Can call startUpdateAdvertisingAndListening without error

2016-02-02 18:31:18.061 ThaliTest[2373:7488126] jxcore: stopAdvertisingAndListening
2016-02-02 18:31:18.061 ThaliTest[2373:7488126] THEMultipeerManager stopping peer
201,6-02-02 18:31:18.061 ThaliTest[2373:7488126] multipeer manager: stop client timer
2016-02-02 18:31:18.062 ThaliTest[2373:7488126] jxcore: stopAdvertisingAndListening: success
ok 23 Can call stopAdvertisingAndListening without error

# setup

,2016-02-02 18:31:18.296 ThaliTest[2373:7488126] jxcore: stopListeningForAdvertisements
2016-02-02 18:31:18.296 ThaliTest[2373:7488126] jxcore: stopListeningForAdvertisements: success
ok 24 Should be able to call stopListeningForAdvertisments in teardown,

2016-02-02 18:31:18.297 ThaliTest[2373:7488126] jxcore: stopAdvertisingAndListening
2016-02-02 18:31:18.297 ThaliTest[2373:7488126] THEMultipeerManager stopping peer
2016-02-02 18:31:18.298 ThaliTest[2373:7488126] jxcore: stopAdvertisingAndListening: ,success
ok 25 Should be able to call stopAdvertisingAndListening in teardown

# Calling startUpdateAdvertisingAndListening twice is NOT and error

,# teardown

,2016-02-02 18:31:18.736 ThaliTest[2373:7488126] jxcore: startUpdateAdvertisingAndListening
2016-02-02 18:31:18.736 ThaliTest[2373:7488126] server: starting 235D5B73-4DF1-4526-AC37-461C084169C7:2
2016-02-02 18:31:18.737 ThaliTest[2373:7488126] multipeer m,anager: start client restart timer: 0x176f5b80
2016-02-02 18:31:18.737 ThaliTest[2373:7488126] THEMultipeerManager initialized peer 235D5B73-4DF1-4526-AC37-461C084169C7:2
2016-02-02 18:31:18.737 ThaliTest[2373:7488126] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 26 Can call startUpdateAdvertisingAndListening without error

2016-02-02 18:31:18.738 ThaliTest[2373:7488126] jxcore: startUpdateAdvertisingAndListening
2016-02-02 18:31:18.739 ThaliTest[2373:7488126] THEMultipeerManager stopping peer
,2016-02-02 18:31:18.739 ThaliTest[2373:7488126] multipeer manager: stop client timer
2016-02-02 18:31:18.744 ThaliTest[2373:7488126] server: starting 235D5B73-4DF1-4526-AC37-461C084169C7:3
2016-02-02 18:31:18.745 ThaliTest[2373:7488126] multipeer manager,: start client restart timer: 0x176f5b80
2016-02-02 18:31:18.745 ThaliTest[2373:7488126] THEMultipeerManager initialized peer 235D5B73-4DF1-4526-AC37-461C084169C7:3
,2016-02-02 18:31:18.745 ThaliTest[2373:7488126] jxcore: startUpdateAdvertisingAndListening: success
ok 27 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-02-02 18:31:18.852 ThaliTest[2373:7488126] jxcore: stopListeningForAdvertisements
2016-02-02 18:31:18.852 ThaliTest[2373:7488126] jxcore: stopListeningForAdvertisements: success
ok 28 Should be able to call stopListeningForAdvertisments in teardown,

2016-02-02 18:31:18.853 ThaliTest[2373:7488126] jxcore: stopAdvertisingAndListening
2016-02-02 18:31:18.853 ThaliTest[2373:7488126] THEMultipeerManager stopping peer
2016-02-02 18:31:18.853 ThaliTest[2373:7488126] multipeer manager: stop client timer,
2016-02-02 18:31:18.853 ThaliTest[2373:7488126] jxcore: stopAdvertisingAndListening: success
ok 29 Should be able to call stopAdvertisingAndListening in teardown

# peerAvailabilityChange is called

,# teardown

,2016-02-02 18:31:19.258 ThaliTest[2373:7488126] jxcore: startUpdateAdvertisingAndListening
2016-02-02 18:31:19.258 ThaliTest[2373:7488126] server: starting 235D5B73-4DF1-4526-AC37-461C084169C7:4
2016-02-02 18:31:19.259 ThaliTest[2373:7488126] multipeer m,anager: start client restart timer: 0x176f5b80
2016-02-02 18:31:19.259 ThaliTest[2373:7488126] THEMultipeerManager initialized peer 235D5B73-4DF1-4526-AC37-461C084169C7:4
2016-02-02 18:31:19.259 ThaliTest[2373:7488126] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 30 Can call startUpdateAdvertisingAndListeningwithout error

2016-02-02 18:31:19.260 ThaliTest[2373:7488126] jxcore: startListeningForAdvertisements
2016-02-02 18:31:19.260 ThaliTest[2373:7488126] multipeer manager: stop client timer
,2016-02-02 18:31:19.261 ThaliTest[2373:7488126] multipeer manager: start client restart timer: 0x176f5b80
2016-02-02 18:31:19.268 ThaliTest[2373:7488126] jxcore: startListeningForAdvertisements: success
ok 31 Can call startListeningForAdvertisements without error

,2016-02-02 18:31:20.449 ThaliTest[2373:7487891] client: found new peer: 79492C6D-2855-47DA-B38F-770B5B64986E:4
ok 32 peers must be an array

,ok 33 peers must not be zero-length

,ok 34 peer must have peerIdentifier

,ok 35 peerIdentifier must be a string

,ok 36 peer must have peerAvailable

,ok 37 peer must have pleaseConnect

,# setup

,2016-02-02 18:31:21.312 ThaliTest[2373:7488126] jxcore: stopListeningForAdvertisements
2016-02-02 18:31:21.312 ThaliTest[2373:7488126] jxcore: stopListeningForAdvertisements: success
ok 38 Should be able to call stopListeningForAdvertisments in teardown,

2016-02-02 18:31:21.313 ThaliTest[2373:7488126] jxcore: stopAdvertisingAndListening
2016-02-02 18:31:21.313 ThaliTest[2373:7488126] THEMultipeerManager stopping peer
2016-02-02 18:31:21.313 ThaliTest[2373:7488126] multipeer manager: stop client timer,
2016-02-02 18:31:21.314 ThaliTest[2373:7488126] jxcore: stopAdvertisingAndListening: success
ok 39 Should be able to call stopAdvertisingAndListening in teardown

# Can connect to a remote peer

,# teardown

,2016-02-02 18:31:23.486 ThaliTest[2373:7488126] Error!: net is not defined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js","_functionNa,me":"","_lineNumber":"117","_columnNumber":"7","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js:117:7"},{"_fileName":"/private/var/mobile/Conta,iners/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"declareTest/</<","_lineNumber":"82","_columnNumber":"7","_msg":"    at declareTest/</<@/private/var/mobile/Containers/Bundle/Applicat,ion/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/lib/thali-tape.js:82:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modu,les/component-emitter/index.js","_functionName":"on","_lineNumber":"63","_columnNumber":"5","_msg":"    at on@/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node,_modules/component-emitter/index.js:63:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":,"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_module,s/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_li,neNumber":"263","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5"},{"_fileName":"/p,rivate/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"221","_columnNumber":"7","_msg":"    at So,cket.prototype.onpacket@/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/3E0F,461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Con,tainers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-3129,09BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/B,undle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F,6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"333","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/3E0,F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3"}]
Uncaught Exception: ReferenceError: net is not defined

,[ { _fileName: '/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js',
    _functionName: '',
    _lineNumber: '117',
    _columnNumber: '7',
    _msg: '    at, @/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js:117:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909B,A4F6D/ThaliTest.app/www/jxcore/lib/thali-tape.js',
    _functionName: 'declareTest/</<',
    _lineNumber: '82',
    _columnNumber: '7',
    _msg: '    at declareTest/</<@/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA,4F6D/ThaliTest.app/www/jxcore/lib/thali-tape.js:82:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js,',,
    _functionName: 'on',
    _lineNumber: '63',
    _columnNumber: '5',
    _msg: '    at on@/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/co,mponent-emitter/index.js:63:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: ',Emitter.prototype.emit',
    _lineNumber: '131',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-clie,nt/node_modules/component-emitter/index.js:131:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket,.,prototype.onevent',
    _lineNumber: '263',
    _columnNumber: '5',
    _msg: '    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/,lib/socket.js:263:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.onpacket',
    _li,neNumber: '221',
,    _columnNumber: '7',
    _msg: '    at Socket.prototype.onpacket@/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7' },
  { _fileName: '/pri,vate/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21',
    _columnNum,ber: '12',
    _msg: '    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
  { _fileName: '/pr,ivate/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '131',
   , _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7' },
,  { _fileName: '/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js',
    _functionName: 'Manager.prototype.ondecoded',
    _lineNumber: '333',
    ,_columnNumber: '3',
    _msg: '    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/3E0F461F-EA7D-4051-BC55-312909BA4F6D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3' },
  toString: [Function,] ]

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****


```
