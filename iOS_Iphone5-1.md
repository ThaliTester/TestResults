#### Test 57924002d5e0b14_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/57924002d5e0b14/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/F267ACB5-4238-45F9-A8B5-333A90FDAB52/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/F267ACB5-4238-45F9-A8B5-333A90FDAB52/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/57924002d5e0b14/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/57924002d5e0b14/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65063"
,(lldb)     command script import "/tmp/F267ACB5-4238-45F9-A8B5-333A90FDAB52/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-02 20:15:23.945 ThaliTest[2397:7502398] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E5137E48-A5EB-4F22-8FB9-E0189C07C4DA/Library/Cookies/Cookies.binarycookies
,2016-02-02 20:15:24.063 ThaliTest[2397:7502398] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-02 20:15:24.065 ThaliTest[2397:7502398] Multi-tasking -> Device: YES, App: YES
,2016-02-02 20:15:24.070 ThaliTest[2397:7502398] Unlimited access to network resources
,2016-02-02 20:15:24.082 ThaliTest[2397:7502398] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-02 20:15:30.476 ThaliTest[2397:7502398] Resetting plugins due to page load.
,2016-02-02 20:15:32.759 ThaliTest[2397:7502398] Finished load of: file:///var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/index.html
,2016-02-02 20:15:32.945 ThaliTest[2397:7502398] JXcore Cordova plugin initializing
,2016-02-02 20:15:33.073 ThaliTest[2397:7502624] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

ok 4 firstPromise testValue

,ok 5 secondPromise setTimeout

ok 6 secondPromise result

ok 7 secondPromise testValue

ok 8 thirdPromise in promise

ok 9 thirdPromise result

ok 10 thirdPromise testValue

,# setup

,# basic

,# teardown

,ok 11 sane

# setup

,# another

,# teardown

,ok 12 sane

,# setup

,# Can call start/stopListeningForAdvertisements

,# teardown

,2016-02-02 20:21:38.862 ThaliTest[2397:7502624] jxcore: startListeningForAdvertisements
,2016-02-02 20:21:38.864 ThaliTest[2397:7502624] multipeer manager: start client restart timer: 0x166acbf0
2016-02-02 20:21:38.865 ThaliTest[2397:7502624] jxcore: startListeningForAdvertisements: success
ok 13 Can call startListeningForAdvertisements with,out error

2016-02-02 20:21:38.866 ThaliTest[2397:7502624] jxcore: stopListeningForAdvertisements
2016-02-02 20:21:38.866 ThaliTest[2397:7502624] multipeer manager: stop client timer
2016-02-02 20:21:38.867 ThaliTest[2397:7502624] jxcore: stopListeningForAdvertisements: success
ok 14 Can call stopListeningForAdvertisements without error

# setup

,2016-02-02 20:21:41.586 ThaliTest[2397:7502624] jxcore: stopListeningForAdvertisements
2016-02-02 20:21:41.587 ThaliTest[2397:7502624] jxcore: stopListeningForAdvertisements: success
ok 15 Should be able to call stopListeningForAdvertisments in teardown,

2016-02-02 20:21:41.588 ThaliTest[2397:7502624] jxcore: stopAdvertisingAndListening
2016-02-02 20:21:41.588 ThaliTest[2397:7502624] THEMultipeerManager stopping peer
2016-02-02 20:21:41.588 ThaliTest[2397:7502624] jxcore: stopAdvertisingAndListening: success
ok 16 Should be able to call stopAdvertisingAndListening in teardown

# Calling startListeningForAdvertisements twice is an error

,# teardown

,2016-02-02 20:21:51.748 ThaliTest[2397:7502624] jxcore: startListeningForAdvertisements
2016-02-02 20:21:51.749 ThaliTest[2397:7502624] multipeer manager: start client restart timer: 0x166acbf0
2016-02-02 20:21:51.749 ThaliTest[2397:7502624] jxcore: star,tListeningForAdvertisements: success
ok 17 Can call startListeningForAdvertisements without error

2016-02-02 20:21:51.750 ThaliTest[2397:7502624] jxcore: startListeningForAdvertisements
2016-02-02 20:21:51.750 ThaliTest[2397:7502624] jxcore: startList,eningForAdvertisements: failure
ok 18 Calling start twice is an error

ok 19 Error must be "Call Stop!"

# setup

,2016-02-02 20:21:56.729 ThaliTest[2397:7502624] jxcore: stopListeningForAdvertisements
2016-02-02 20:21:56.730 ThaliTest[2397:7502624] multipeer manager: stop client timer
2016-02-02 20:21:56.730 ThaliTest[2397:7502624] jxcore: stopListeningForAdvertisements: success
ok 20 Should be able to call stopListeningForAdvertisments in teardown

2016-02-02 20:21:56.731 ThaliTest[2397:7502624] jxcore: stopAdvertisingAndListening
2016-02-02 20:21:56.731 ThaliTest[2397:7502624] THEMultipeerManager stopping peer,
2016-02-02 20:21:56.731 ThaliTest[2397:7502624] jxcore: stopAdvertisingAndListening: success
ok 21 Should be able to call stopAdvertisingAndListening in teardown

,# Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-02-02 20:22:01.148 ThaliTest[2397:7502624] jxcore: startUpdateAdvertisingAndListening
2016-02-02 20:22:01.148 ThaliTest[2397:7502624] server: starting A7CC9F36-3785-4D77-A0BB-30B8B4EF8585:1
2016-02-02 20:22:01.149 ThaliTest[2397:7502624] multipeer m,anager: start client restart timer: 0x166acbf0
2016-02-02 20:22:01.149 ThaliTest[2397:7502624] THEMultipeerManager initialized peer A7CC9F36-3785-4D77-A0BB-30B8B4EF8585:1
2016-02-02 20:22:01.149 ThaliTest[2397:7502624] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 22 Can call startUpdateAdvertisingAndListening without error

2016-02-02 20:22:01.150 ThaliTest[2397:7502624] jxcore: stopAdvertisingAndListening
2016-02-02 20:22:01.150 ThaliTest[2397:7502624] THEMultipeerManager stopping peer
,2016-02-02 20:22:01.150 ThaliTest[2397:7502624] multipeer manager: stop client timer
2016-02-02 20:22:01.159 ThaliTest[2397:7502624] jxcore: stopAdvertisingAndListening: success
ok 23 Can call stopAdvertisingAndListening without error

# setup

,2016-02-02 20:22:04.032 ThaliTest[2397:7502624] jxcore: stopListeningForAdvertisements
2016-02-02 20:22:04.033 ThaliTest[2397:7502624] jxcore: stopListeningForAdvertisements: success
ok 24 Should be able to call stopListeningForAdvertisments in teardown,

2016-02-02 20:22:04.034 ThaliTest[2397:7502624] jxcore: stopAdvertisingAndListening
2016-02-02 20:22:04.034 ThaliTest[2397:7502624] THEMultipeerManager stopping peer
2016-02-02 20:22:04.034 ThaliTest[2397:7502624] jxcore: stopAdvertisingAndListening: ,success
ok 25 Should be able to call stopAdvertisingAndListening in teardown

# Calling startUpdateAdvertisingAndListening twice is NOT and error

,# teardown

,2016-02-02 20:22:14.647 ThaliTest[2397:7502624] jxcore: startUpdateAdvertisingAndListening
2016-02-02 20:22:14.647 ThaliTest[2397:7502624] server: starting A7CC9F36-3785-4D77-A0BB-30B8B4EF8585:2
2016-02-02 20:22:14.648 ThaliTest[2397:7502624] multipeer m,anager: start client restart timer: 0x166acbf0
2016-02-02 20:22:14.648 ThaliTest[2397:7502624] THEMultipeerManager initialized peer A7CC9F36-3785-4D77-A0BB-30B8B4EF8585:2
2016-02-02 20:22:14.649 ThaliTest[2397:7502624] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 26 Can call startUpdateAdvertisingAndListening without error

2016-02-02 20:22:14.650 ThaliTest[2397:7502624] jxcore: startUpdateAdvertisingAndListening
2016-02-02 20:22:14.650 ThaliTest[2397:7502624] THEMultipeerManager stopping pe,er
2016-02-02 20:22:14.650 ThaliTest[2397:7502624] multipeer manager: stop client timer
2016-02-02 20:22:14.650 ThaliTest[2397:7502624] server: starting A7CC9F36-3785-4D77-A0BB-30B8B4EF8585:3
2016-02-02 20:22:14.651 ThaliTest[2397:7502624] multipeer ma,n,ager: start client restart timer: 0x166acbf0
2016-02-02 20:22:14.660 ThaliTest[2397:7502624] THEMultipeerManager initialized peer A7CC9F36-3785-4D77-A0BB-30B8B4EF8585:3
2016-02-02 20:22:14.660 ThaliTest[2397:7502624] jxcore: startUpdateAdvertisingAndList,ening: success
ok 27 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-02-02 20:22:16.049 ThaliTest[2397:7502624] jxcore: stopListeningForAdvertisements
2016-02-02 20:22:16.049 ThaliTest[2397:7502624] jxcore: stopListeningForAdvertisements: success
ok 28 Should be able to call stopListeningForAdvertisments in teardown,

2016-02-02 20:22:16.051 ThaliTest[2397:7502624] jxcore: stopAdvertisingAndListening
2016-02-02 20:22:16.051 ThaliTest[2397:7502624] THEMultipeerManager stopping peer
2016-02-02 20:22:16.051 ThaliTest[2397:7502624] multipeer manager: stop client timer,
2016-02-02 20:22:16.051 ThaliTest[2397:7502624] jxcore: stopAdvertisingAndListening: success
ok 29 Should be able to call stopAdvertisingAndListening in teardown

,# peerAvailabilityChange is called

,# teardown

,2016-02-02 20:22:21.812 ThaliTest[2397:7502624] jxcore: startUpdateAdvertisingAndListening
2016-02-02 20:22:21.812 ThaliTest[2397:7502624] server: starting A7CC9F36-3785-4D77-A0BB-30B8B4EF8585:4
2016-02-02 20:22:21.812 ThaliTest[2397:7502624] multipeer m,anager: start client restart timer: 0x166acbf0
2016-02-02 20:22:21.813 ThaliTest[2397:7502624] THEMultipeerManager initialized peer A7CC9F36-3785-4D77-A0BB-30B8B4EF8585:4
2016-02-02 20:22:21.813 ThaliTest[2397:7502624] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 30 Can call startUpdateAdvertisingAndListeningwithout error

2016-02-02 20:22:21.814 ThaliTest[2397:7502624] jxcore: startListeningForAdvertisements
2016-02-02 20:22:21.814 ThaliTest[2397:7502624] multipeer manager: stop client time,r
2016-02-02 20:22:21.815 ThaliTest[2397:7502624] multipeer manager: start client restart timer: 0x166acbf0
2016-02-02 20:22:21.815 ThaliTest[2397:7502624] jxcore: startListeningForAdvertisements: success
ok 31 Can call startListeningForAdvertisements w,ithout error

,2016-02-02 20:22:23.906 ThaliTest[2397:7502398] client: found new peer: 26326E4D-B311-489D-9239-A89C69C0A211:4
ok 32 peers must be an array

ok 33 peers must not be zero-length

ok 34 peer must have peerIdentifier

ok 35 peerIdentifier must be a str,ing

ok 36 peer must have peerAvailable

ok 37 peer must have pleaseConnect

,# setup

,2016-02-02 20:22:25.186 ThaliTest[2397:7502624] jxcore: stopListeningForAdvertisements
2016-02-02 20:22:25.186 ThaliTest[2397:7502624] jxcore: stopListeningForAdvertisements: success
ok 38 Should be able to call stopListeningForAdvertisments in teardown,

2016-02-02 20:22:25.187 ThaliTest[2397:7502624] jxcore: stopAdvertisingAndListening
2016-02-02 20:22:25.187 ThaliTest[2397:7502624] THEMultipeerManager stopping peer
2016-02-02 20:22:25.187 ThaliTest[2397:7502624] multipeer manager: stop client timer,
2016-02-02 20:22:25.188 ThaliTest[2397:7502624] jxcore: stopAdvertisingAndListening: success
ok 39 Should be able to call stopAdvertisingAndListening in teardown

# Can connect to a remote peer

,# teardown

,2016-02-02 20:23:15.028 ThaliTest[2397:7502624] Error!: net is not defined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js","_functionNa,me":"","_lineNumber":"117","_columnNumber":"7","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js:117:7"},{"_fileName":"/private/var/mobile/Conta,iners/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"declareTest/</<","_lineNumber":"82","_columnNumber":"7","_msg":"    at declareTest/</<@/private/var/mobile/Containers/Bundle/Applicat,ion/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/lib/thali-tape.js:82:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modu,les/component-emitter/index.js","_functionName":"on","_lineNumber":"63","_columnNumber":"5","_msg":"    at on@/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node,_modules/component-emitter/index.js:63:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":,"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_module,s/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lin,eNumber":"263","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5"},{"_fileName":"/pr,ivate/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"221","_columnNumber":"7","_msg":"    at Soc,ket.prototype.onpacket@/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A1442,CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Cont,ainers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6,EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bu,ndle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F4,3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"333","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/A144,2CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3"}]
Uncaught Exception: ReferenceError: net is not defined

,[ { _fileName: '/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js',
    _functionName: '',
    _lineNumber: '117',
    _columnNumber: '7',
    _msg: '    at, @/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js:117:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EF,E3F43/ThaliTest.app/www/jxcore/lib/thali-tape.js',
    _functionName: 'declareTest/</<',
    _lineNumber: '82',
    _columnNumber: '7',
    _msg: '    at declareTest/</<@/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE,3F43/ThaliTest.app/www/jxcore/lib/thali-tape.js:82:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',,
    _functionName: 'on',
    _lineNumber: '63',
    _columnNumber: '5',
    _msg: '    at on@/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/co,mponent-emitter/index.js:63:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: ',Emitter.prototype.emit',
    _lineNumber: '131',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-clie,nt/node_modules/component-emitter/index.js:131:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.,prototype.onevent',
    _lineNumber: '263',
    _columnNumber: '5',
    _msg: '    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/,lib/socket.js:263:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.onpacket',
    _li,neNumber: '221',
    _columnNumber: '7',
    _msg: '    at Socket.prototype.onpacket@/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7' },
  ,{ _fileName: '/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21,',
    _columnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
 , { _fileName: '/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineN,umber: '131',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/in,dex.js:131:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js',
    _functionName: 'Manager.prototype.ondecoded',
    _lineN,umber: '333',
    _columnNumber: '3',
    _msg: '    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3' },
  ,toString: [Function] ]

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

ReferenceError: net is not defined (/private/var/mobile/Containers/Bundle/Application/A1442CFF-F05C-45AC-B7CC-31BC6EFE3F43/ThaliTest.app/www/jxcore/bv_test
```
