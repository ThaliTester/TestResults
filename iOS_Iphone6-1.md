#### Test 575312431f256a6_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/575312431f256a6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/55E1233E-5EF4-4DD7-BFFC-DAE6C68A05E6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/55E1233E-5EF4-4DD7-BFFC-DAE6C68A05E6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/575312431f256a6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/575312431f256a6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64924"
,(lldb)     command script import "/tmp/55E1233E-5EF4-4DD7-BFFC-DAE6C68A05E6/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-02 18:25:01.375 ThaliTest[1075:1911655] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AC48723D-2115-4FC2-A001-5C1D1F6796A0/Library/Cookies/Cookies.binarycookies
,2016-02-02 18:25:01.859 ThaliTest[1075:1911655] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-02 18:25:01.860 ThaliTest[1075:1911655] Multi-tasking -> Device: YES, App: YES
,2016-02-02 18:25:01.870 ThaliTest[1075:1911655] Unlimited access to network resources
,2016-02-02 18:25:01.880 ThaliTest[1075:1911655] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-02 18:25:10.949 ThaliTest[1075:1911655] Resetting plugins due to page load.
,2016-02-02 18:25:14.706 ThaliTest[1075:1911655] Finished load of: file:///var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/index.html
,2016-02-02 18:25:14.897 ThaliTest[1075:1911655] JXcore Cordova plugin initializing
,2016-02-02 18:25:15.000 ThaliTest[1075:1911922] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,appEnteringBackground wasn't registered

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

,2016-02-02 18:30:23.142 ThaliTest[1075:1911922] jxcore: startListeningForAdvertisements
,2016-02-02 18:30:23.145 ThaliTest[1075:1911922] multipeer manager: start client restart timer: 0x175de2e0
,2016-02-02 18:30:23.146 ThaliTest[1075:1911922] jxcore: startListeningForAdvertisements: success
,ok 13 Can call startListeningForAdvertisements without error

2016-02-02 18:30:23.149 ThaliTest[1075:1911922] jxcore: stopListeningForAdvertisements
2016-02-02 18:30:23.150 ThaliTest[1075:1911922] multipeer manager: stop client timer
,2016-02-02 18:30:23.152 ThaliTest[1075:1911922] jxcore: stopListeningForAdvertisements: success
,ok 14 Can call stopListeningForAdvertisements without error

,# setup

,2016-02-02 18:30:47.942 ThaliTest[1075:1911922] jxcore: stopListeningForAdvertisements
2016-02-02 18:30:47.943 ThaliTest[1075:1911922] jxcore: stopListeningForAdvertisements: success
ok 15 Should be able to call stopListeningForAdvertisments in teardown,

2016-02-02 18:30:47.945 ThaliTest[1075:1911922] jxcore: stopAdvertisingAndListening
,2016-02-02 18:30:47.946 ThaliTest[1075:1911922] THEMultipeerManager stopping peer
2016-02-02 18:30:47.946 ThaliTest[1075:1911922] jxcore: stopAdvertisingAndListening: success
ok 16 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startListeningForAdvertisements twice is an error

,# teardown

,2016-02-02 18:30:51.562 ThaliTest[1075:1911922] jxcore: startListeningForAdvertisements
2016-02-02 18:30:51.563 ThaliTest[1075:1911922] multipeer manager: start client restart timer: 0x175de2e0
2016-02-02 18:30:51.564 ThaliTest[1075:1911922] jxcore: star,tListeningForAdvertisements: success
ok 17 Can call startListeningForAdvertisements without error

,2016-02-02 18:30:51.566 ThaliTest[1075:1911922] jxcore: startListeningForAdvertisements
2016-02-02 18:30:51.566 ThaliTest[1075:1911922] jxcore: startListeningForAdvertisements: failure
,ok 18 Calling start twice is an error

ok 19 Error must be "Call Stop!"

,# setup

,2016-02-02 18:31:11.565 ThaliTest[1075:1911655] multipeer manager: restart client
,2016-02-02 18:31:17.256 ThaliTest[1075:1911922] jxcore: stopListeningForAdvertisements
2016-02-02 18:31:17.256 ThaliTest[1075:1911922] multipeer manager: stop client timer
2016-02-02 18:31:17.257 ThaliTest[1075:1911922] jxcore: stopListeningForAdvertisements: success
,ok 20 Should be able to call stopListeningForAdvertisments in teardown

2016-02-02 18:31:17.260 ThaliTest[1075:1911922] jxcore: stopAdvertisingAndListening
2016-02-02 18:31:17.261 ThaliTest[1075:1911922] THEMultipeerManager stopping peer
,2016-02-02 18:31:17.263 ThaliTest[1075:1911922] jxcore: stopAdvertisingAndListening: success
ok 21 Should be able to call stopAdvertisingAndListening in teardown

,# Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-02-02 18:31:18.122 ThaliTest[1075:1911922] jxcore: startUpdateAdvertisingAndListening
2016-02-02 18:31:18.123 ThaliTest[1075:1911922] server: starting 79492C6D-2855-47DA-B38F-770B5B64986E:1
2016-02-02 18:31:18.124 ThaliTest[1075:1911922] multipeer m,anager: start client restart timer: 0x175de2e0
2016-02-02 18:31:18.125 ThaliTest[1075:1911922] THEMultipeerManager initialized peer 79492C6D-2855-47DA-B38F-770B5B64986E:1
2016-02-02 18:31:18.125 ThaliTest[1075:1911922] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 22 Can call startUpdateAdvertisingAndListening without error

2016-02-02 18:31:18.127 ThaliTest[1075:1911922] jxcore: stopAdvertisingAndListening
2016-02-02 18:31:18.127 ThaliTest[1075:1911922] THEMultipeerManager stopping peer
201,6-02-02 18:31:18.128 ThaliTest[1075:1911922] multipeer manager: stop client timer
2016-02-02 18:31:18.128 ThaliTest[1075:1911922] jxcore: stopAdvertisingAndListening: success
ok 23 Can call stopAdvertisingAndListening without error
,
,# setup

,2016-02-02 18:31:18.302 ThaliTest[1075:1911922] jxcore: stopListeningForAdvertisements
2016-02-02 18:31:18.303 ThaliTest[1075:1911922] jxcore: stopListeningForAdvertisements: success
ok 24 Should be able to call stopListeningForAdvertisments in teardown

2016-02-02 18:31:18.305 ThaliTest[1075:1911922] jxcore: stopAdvertisingAndListening
,2016-02-02 18:31:18.305 ThaliTest[1075:1911922] THEMultipeerManager stopping peer
,2016-02-02 18:31:18.305 ThaliTest[1075:1911922] jxcore: stopAdvertisingAndListening: success
,ok 25 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startUpdateAdvertisingAndListening twice is NOT and error

,# teardown

,2016-02-02 18:31:18.749 ThaliTest[1075:1911922] jxcore: startUpdateAdvertisingAndListening
2016-02-02 18:31:18.750 ThaliTest[1075:1911922] server: starting 79492C6D-2855-47DA-B38F-770B5B64986E:2
2016-02-02 18:31:18.750 ThaliTest[1075:1911922] multipeer m,anager: start client restart timer: 0x175de2e0
2016-02-02 18:31:18.751 ThaliTest[1075:1911922] THEMultipeerManager initialized peer 79492C6D-2855-47DA-B38F-770B5B64986E:2
2016-02-02 18:31:18.751 ThaliTest[1075:1911922] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 26 Can call startUpdateAdvertisingAndListening without error

2016-02-02 18:31:18.753 ThaliTest[1075:1911922] jxcore: startUpdateAdvertisingAndListening
2016-02-02 18:31:18.754 ThaliTest[1075:1911922] THEMultipeerManager stopping pe,er
2016-02-02 18:31:18.754 ThaliTest[1075:1911922] multipeer manager: stop client timer
2016-02-02 18:31:18.755 ThaliTest[1075:1911922] server: starting 79492C6D-2855-47DA-B38F-770B5B64986E:3
2016-02-02 18:31:18.755 ThaliTest[1075:1911922] multipeer man,ager: start client restart timer: 0x175de2e0
2016-02-02 18:31:18.760 ThaliTest[1075:1911922] THEMultipeerManager initialized peer 79492C6D-2855-47DA-B38F-770B5B64986E:3
2016-02-02 18:31:18.760 ThaliTest[1075:1911922] jxcore: startUpdateAdvertisingAndListening: success
ok 27 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-02-02 18:31:18.981 ThaliTest[1075:1911922] jxcore: stopListeningForAdvertisements
2016-02-02 18:31:18.982 ThaliTest[1075:1911922] jxcore: stopListeningForAdvertisements: success
ok 28 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 18:31:18.983 ThaliTest[1075:1911922] jxcore: stopAdvertisingAndListening
2016-02-02 18:31:18.984 ThaliTest[1075:1911922] THEMultipeerManager stopping peer
2016-02-02 18:31:18.984 ThaliTest[1075:1911922] multipeer manager: stop client timer
20,16-02-02 18:31:18.985 ThaliTest[1075:1911922] jxcore: stopAdvertisingAndListening: success
ok 29 Should be able to call stopAdvertisingAndListening in teardown

,# peerAvailabilityChange is called

,# teardown

,2016-02-02 18:31:19.152 ThaliTest[1075:1911922] jxcore: startUpdateAdvertisingAndListening
2016-02-02 18:31:19.153 ThaliTest[1075:1911922] server: starting 79492C6D-2855-47DA-B38F-770B5B64986E:4
2016-02-02 18:31:19.153 ThaliTest[1075:1911922] multipeer m,anager: start client restart timer: 0x175de2e0
2016-02-02 18:31:19.154 ThaliTest[1075:1911922] THEMultipeerManager initialized peer 79492C6D-2855-47DA-B38F-770B5B64986E:4
2016-02-02 18:31:19.154 ThaliTest[1075:1911922] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 30 Can call startUpdateAdvertisingAndListeningwithout error

2016-02-02 18:31:19.156 ThaliTest[1075:1911922] jxcore: startListeningForAdvertisements
2016-02-02 18:31:19.156 ThaliTest[1075:1911922] multipeer manager: stop client time,r
2016-02-02 18:31:19.157 ThaliTest[1075:1911922] multipeer manager: start client restart timer: 0x175de2e0
2016-02-02 18:31:19.157 ThaliTest[1075:1911922] jxcore: startListeningForAdvertisements: success
ok 31 Can call startListeningForAdvertisements w,ithout error

,2016-02-02 18:31:20.432 ThaliTest[1075:1911655] client: found new peer: 235D5B73-4DF1-4526-AC37-461C084169C7:4
ok 32 peers must be an array

,ok 33 peers must not be zero-length

ok 34 peer must have peerIdentifier

ok 35 peerIdentifier must be a string

ok 36 peer must have peerAvailable

ok 37 peer must have pleaseConnect

,# setup

,2016-02-02 18:31:21.140 ThaliTest[1075:1911922] jxcore: stopListeningForAdvertisements
2016-02-02 18:31:21.141 ThaliTest[1075:1911922] jxcore: stopListeningForAdvertisements: success
ok 38 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 18:31:21.142 ThaliTest[1075:1911922] jxcore: stopAdvertisingAndListening
2016-02-02 18:31:21.143 ThaliTest[1075:1911922] THEMultipeerManager stopping peer
2016-02-02 18:31:21.143 ThaliTest[1075:1911922] multipeer manager: stop client timer
20,16-02-02 18:31:21.144 ThaliTest[1075:1911922] jxcore: stopAdvertisingAndListening: success
ok 39 Should be able to call stopAdvertisingAndListening in teardown

,# Can connect to a remote peer

,# teardown

,2016-02-02 18:31:23.333 ThaliTest[1075:1911922] Error!: net is not defined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js","_functionNa,me":"","_lineNumber":"117","_columnNumber":"7","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js:117:7"},{"_fileName":"/private/var/mobile/Conta,iners/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"declareTest/</<","_lineNumber":"82","_columnNumber":"7","_msg":"    at declareTest/</<@/private/var/mobile/Containers/Bundle/Applicat,ion/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/lib/thali-tape.js:82:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modu,les/component-emitter/index.js","_functionName":"on","_lineNumber":"63","_columnNumber":"5","_msg":"    at on@/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node,_modules/component-emitter/index.js:63:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":,"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_module,s/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lin,eNumber":"263","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5"},{"_fileName":"/pr,ivate/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"221","_columnNumber":"7","_msg":"    at Soc,ket.prototype.onpacket@/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/F0373,3CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Cont,ainers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CF,D7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bu,ndle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F566,4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"333","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/F037,33CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3"}]
Uncaught Exception: ReferenceError: net is not defined

,[ { _fileName: '/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js',
    _functionName: '',
    _lineNumber: '117',
    _columnNumber: '7',
    _msg: '    at, @/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js:117:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7,F5664/ThaliTest.app/www/jxcore/lib/thali-tape.js',
    _functionName: 'declareTest/</<',
    _lineNumber: '82',
    _columnNumber: '7',
    _msg: '    at declareTest/</<@/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F,5664/ThaliTest.app/www/jxcore/lib/thali-tape.js:82:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',,
    _functionName: 'on',
    _lineNumber: '63',
    _columnNumber: '5',
    _msg: '    at on@/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/co,mponent-emitter/index.js:63:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: ',Emitter.prototype.emit',
    _lineNumber: '131',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-clie,nt/node_modules/component-emitter/index.js:131:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.,prototype.onevent',
    _lineNumber: '263',
    _columnNumber: '5',
    _msg: '    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/,lib/socket.js:263:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.onpacket',
    _li,neNumber: '221',
    _columnNumber: '7',
    _msg: '    at Socket.prototype.onpacket@/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7' },
  ,{ _fileName: '/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21,',
    _columnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
,  { _fileName: '/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _line,Number: '131',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/i,ndex.js:131:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js',
    _functionName: 'Manager.prototype.ondecoded',
    _lineN,umber: '333',
    _columnNumber: '3',
    _msg: '    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3' },
  ,toString: [Function] ]

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

ReferenceError: net is not defined (/private/var/mobile/Containers/Bundle/Application/F03733CA-7CB5-4884-8DF9-ED9CFD7F5664/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js 117:6)


```
