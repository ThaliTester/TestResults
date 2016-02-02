#### Test 57924002d5e0b14_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/57924002d5e0b14/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/43B82CAD-D8A4-4CF2-9C23-3FA75E803AC2/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/43B82CAD-D8A4-4CF2-9C23-3FA75E803AC2/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/57924002d5e0b14/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/57924002d5e0b14/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65101"
,(lldb)     command script import "/tmp/43B82CAD-D8A4-4CF2-9C23-3FA75E803AC2/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-02 20:16:43.553 ThaliTest[1091:1924229] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/39738D4F-C231-48E1-A198-31832BDA5DDD/Library/Cookies/Cookies.binarycookies
,2016-02-02 20:16:43.926 ThaliTest[1091:1924229] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-02 20:16:43.927 ThaliTest[1091:1924229] Multi-tasking -> Device: YES, App: YES
,2016-02-02 20:16:43.937 ThaliTest[1091:1924229] Unlimited access to network resources
,2016-02-02 20:16:43.946 ThaliTest[1091:1924229] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-02 20:16:53.999 ThaliTest[1091:1924229] Resetting plugins due to page load.
,2016-02-02 20:16:57.337 ThaliTest[1091:1924229] Finished load of: file:///var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/index.html
,2016-02-02 20:16:57.511 ThaliTest[1091:1924229] JXcore Cordova plugin initializing
,2016-02-02 20:16:57.620 ThaliTest[1091:1924565] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,2016-02-02 20:21:41.018 ThaliTest[1091:1924565] jxcore: startListeningForAdvertisements
,2016-02-02 20:21:41.021 ThaliTest[1091:1924565] multipeer manager: start client restart timer: 0x175a4b90
2016-02-02 20:21:41.021 ThaliTest[1091:1924565] jxcore: startListeningForAdvertisements: success
ok 13 Can call startListeningForAdvertisements with,out error

2016-02-02 20:21:41.023 ThaliTest[1091:1924565] jxcore: stopListeningForAdvertisements
2016-02-02 20:21:41.024 ThaliTest[1091:1924565] multipeer manager: stop client timer
2016-02-02 20:21:41.024 ThaliTest[1091:1924565] jxcore: stopListening,ForAdvertisements: success
ok 14 Can call stopListeningForAdvertisements without error

,# setup

,2016-02-02 20:21:41.051 ThaliTest[1091:1924565] jxcore: stopListeningForAdvertisements
2016-02-02 20:21:41.051 ThaliTest[1091:1924565] jxcore: stopListeningForAdvertisements: success
ok 15 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 20:21:41.053 ThaliTest[1091:1924565] jxcore: stopAdvertisingAndListening
2016-02-02 20:21:41.053 ThaliTest[1091:1924565] THEMultipeerManager stopping peer
2016-02-02 20:21:41.054 ThaliTest[1091:1924565] jxcore: stopAdvertisingAndListening: suc,cess
ok 16 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startListeningForAdvertisements twice is an error

,# teardown

,2016-02-02 20:21:56.319 ThaliTest[1091:1924565] jxcore: startListeningForAdvertisements
2016-02-02 20:21:56.321 ThaliTest[1091:1924565] multipeer manager: start client restart timer: 0x175a4b90
2016-02-02 20:21:56.321 ThaliTest[1091:1924565] jxcore: startListeningForAdvertisements: success
ok 17 Can call startListeningForAdvertisements without error

,2016-02-02 20:21:56.324 ThaliTest[1091:1924565] jxcore: startListeningForAdvertisements
2016-02-02 20:21:56.325 ThaliTest[1091:1924565] jxcore: startListeningForAdvertisements: failure
ok 18 Calling start twice is an error

ok 19 Error must be "Call Stop!"

,# setup

,2016-02-02 20:21:56.413 ThaliTest[1091:1924565] jxcore: stopListeningForAdvertisements
,2016-02-02 20:21:56.415 ThaliTest[1091:1924565] multipeer manager: stop client timer
,2016-02-02 20:21:56.419 ThaliTest[1091:1924565] jxcore: stopListeningForAdvertisements: success
,ok 20 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 20:21:56.422 ThaliTest[1091:1924565] jxcore: stopAdvertisingAndListening
2016-02-02 20:21:56.422 ThaliTest[1091:1924565] THEMultipeerManager stopping peer
,2016-02-02 20:21:56.424 ThaliTest[1091:1924565] jxcore: stopAdvertisingAndListening: success
,ok 21 Should be able to call stopAdvertisingAndListening in teardown

,# Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-02-02 20:22:03.520 ThaliTest[1091:1924565] jxcore: startUpdateAdvertisingAndListening
2016-02-02 20:22:03.521 ThaliTest[1091:1924565] server: starting 26326E4D-B311-489D-9239-A89C69C0A211:1
2016-02-02 20:22:03.522 ThaliTest[1091:1924565] multipeer m,anager: start client restart timer: 0x175a4b90
2016-02-02 20:22:03.522 ThaliTest[1091:1924565] THEMultipeerManager initialized peer 26326E4D-B311-489D-9239-A89C69C0A211:1
2016-02-02 20:22:03.522 ThaliTest[1091:1924565] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 22 Can call startUpdateAdvertisingAndListening without error

,2016-02-02 20:22:03.524 ThaliTest[1091:1924565] jxcore: stopAdvertisingAndListening
,2016-02-02 20:22:03.526 ThaliTest[1091:1924565] THEMultipeerManager stopping peer
2016-02-02 20:22:03.528 ThaliTest[1091:1924565] multipeer manager: stop client timer
2016-02-02 20:22:03.530 ThaliTest[1091:1924565] jxcore: stopAdvertisingAndListening: success
ok 23 Can call stopAdvertisingAndListening without error

,# setup

,2016-02-02 20:22:03.793 ThaliTest[1091:1924565] jxcore: stopListeningForAdvertisements
2016-02-02 20:22:03.794 ThaliTest[1091:1924565] jxcore: stopListeningForAdvertisements: success
ok 24 Should be able to call stopListeningForAdvertisments in teardown,

,2016-02-02 20:22:03.795 ThaliTest[1091:1924565] jxcore: stopAdvertisingAndListening
,2016-02-02 20:22:03.796 ThaliTest[1091:1924565] THEMultipeerManager stopping peer
2016-02-02 20:22:03.797 ThaliTest[1091:1924565] jxcore: stopAdvertisingAndListening: success
ok 25 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startUpdateAdvertisingAndListening twice is NOT and error

,# teardown

,2016-02-02 20:22:04.342 ThaliTest[1091:1924565] jxcore: startUpdateAdvertisingAndListening
2016-02-02 20:22:04.343 ThaliTest[1091:1924565] server: starting 26326E4D-B311-489D-9239-A89C69C0A211:2
2016-02-02 20:22:04.344 ThaliTest[1091:1924565] multipeer m,anager: start client restart timer: 0x175a4b90
2016-02-02 20:22:04.344 ThaliTest[1091:1924565] THEMultipeerManager initialized peer 26326E4D-B311-489D-9239-A89C69C0A211:2
2016-02-02 20:22:04.345 ThaliTest[1091:1924565] jxcore: startUpdateAdvertisingAndListening: success
ok 26 Can call startUpdateAdvertisingAndListening without error

,2016-02-02 20:22:04.348 ThaliTest[1091:1924565] jxcore: startUpdateAdvertisingAndListening
,2016-02-02 20:22:04.348 ThaliTest[1091:1924565] THEMultipeerManager stopping peer
2016-02-02 20:22:04.349 ThaliTest[1091:1924565] multipeer manager: stop client timer
2016-02-02 20:22:04.349 ThaliTest[1091:1924565] server: starting 26326E4D-B311-489D-923,9-A89C69C0A211:3
2016-02-02 20:22:04.350 ThaliTest[1091:1924565] multipeer manager: start client restart timer: 0x175a4b90
2016-02-02 20:22:04.351 ThaliTest[1091:1924565] THEMultipeerManager initialized peer 26326E4D-B311-489D-9239-A89C69C0A211:3
,2016-02-02 20:22:04.351 ThaliTest[1091:1924565] jxcore: startUpdateAdvertisingAndListening: success
,ok 27 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-02-02 20:22:16.818 ThaliTest[1091:1924565] jxcore: stopListeningForAdvertisements
2016-02-02 20:22:16.819 ThaliTest[1091:1924565] jxcore: stopListeningForAdvertisements: success
ok 28 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 20:22:16.820 ThaliTest[1091:1924565] jxcore: stopAdvertisingAndListening
2016-02-02 20:22:16.821 ThaliTest[1091:1924565] THEMultipeerManager stopping peer
,2016-02-02 20:22:16.822 ThaliTest[1091:1924565] multipeer manager: stop client timer
,2016-02-02 20:22:16.822 ThaliTest[1091:1924565] jxcore: stopAdvertisingAndListening: success
ok 29 Should be able to call stopAdvertisingAndListening in teardown

,# peerAvailabilityChange is called

,# teardown

,2016-02-02 20:22:21.830 ThaliTest[1091:1924565] jxcore: startUpdateAdvertisingAndListening
2016-02-02 20:22:21.831 ThaliTest[1091:1924565] server: starting 26326E4D-B311-489D-9239-A89C69C0A211:4
2016-02-02 20:22:21.832 ThaliTest[1091:1924565] multipeer m,anager: start client restart timer: 0x175a4b90
2016-02-02 20:22:21.832 ThaliTest[1091:1924565] THEMultipeerManager initialized peer 26326E4D-B311-489D-9239-A89C69C0A211:4
2016-02-02 20:22:21.832 ThaliTest[1091:1924565] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 30 Can call startUpdateAdvertisingAndListeningwithout error

2016-02-02 20:22:21.834 ThaliTest[1091:1924565] jxcore: startListeningForAdvertisements
2016-02-02 20:22:21.835 ThaliTest[1091:1924565] multipeer manager: stop client time,r
2016-02-02 20:22:21.835 ThaliTest[1091:1924565] multipeer manager: start client restart timer: 0x175a4b90
2016-02-02 20:22:21.836 ThaliTest[1091:1924565] jxcore: startListeningForAdvertisements: success
ok 31 Can call startListeningForAdvertisements w,ithout error

,2016-02-02 20:22:23.759 ThaliTest[1091:1924229] client: found new peer: A7CC9F36-3785-4D77-A0BB-30B8B4EF8585:4
ok 32 peers must be an array

,ok 33 peers must not be zero-length

,ok 34 peer must have peerIdentifier

,ok 35 peerIdentifier must be a string

,ok 36 peer must have peerAvailable

,ok 37 peer must have pleaseConnect

,# setup

,2016-02-02 20:22:25.912 ThaliTest[1091:1924565] jxcore: stopListeningForAdvertisements
2016-02-02 20:22:25.913 ThaliTest[1091:1924565] jxcore: stopListeningForAdvertisements: success
ok 38 Should be able to call stopListeningForAdvertisments in teardown,

,2016-02-02 20:22:25.915 ThaliTest[1091:1924565] jxcore: stopAdvertisingAndListening
2016-02-02 20:22:25.915 ThaliTest[1091:1924565] THEMultipeerManager stopping peer
2016-02-02 20:22:25.917 ThaliTest[1091:1924565] multipeer manager: stop client timer
2016-02-02 20:22:25.917 ThaliTest[1091:1924565] jxcore: stopAdvertisingAndListening: success
ok 39 Should be able to call stopAdvertisingAndListening in teardown

,# Can connect to a remote peer

,# teardown

,2016-02-02 20:22:30.586 ThaliTest[1091:1924565] Error!: net is not defined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js","_functionNa,me":"","_lineNumber":"117","_columnNumber":"7","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js:117:7"},{"_fileName":"/private/var/mobile/Conta,iners/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"declareTest/</<","_lineNumber":"82","_columnNumber":"7","_msg":"    at declareTest/</<@/private/var/mobile/Containers/Bundle/Applicat,ion/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/lib/thali-tape.js:82:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modu,les/component-emitter/index.js","_functionName":"on","_lineNumber":"63","_columnNumber":"5","_msg":"    at on@/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node,_modules/component-emitter/index.js:63:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":,"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_module,s/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lin,eNumber":"263","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5"},{"_fileName":"/pr,ivate/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"221","_columnNumber":"7","_msg":"    at Soc,ket.prototype.onpacket@/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/B20D8,482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Cont,ainers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA2,20EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bu,ndle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B,8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"333","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/B20,D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3"}]
Uncaught Exception: ReferenceError: net is not defined

,[ { _fileName: '/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js',
    _functionName: '',
    _lineNumber: '117',
    _columnNumber: '7',
    _msg: '    at, @/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js:117:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220,EE3B8/ThaliTest.app/www/jxcore/lib/thali-tape.js',
    _functionName: 'declareTest/</<',
    _lineNumber: '82',
    _columnNumber: '7',
    _msg: '    at declareTest/</<@/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220E,E3B8/ThaliTest.app/www/jxcore/lib/thali-tape.js:82:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',,
    _functionName: 'on',
    _lineNumber: '63',
    _columnNumber: '5',
    _msg: '    at on@/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/co,mponent-emitter/index.js:63:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: ',Emitter.prototype.emit',
    _lineNumber: '131',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-clie,nt/node_modules/component-emitter/index.js:131:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.,prototype.onevent',
    _lineNumber: '263',
    _columnNumber: '5',
    _msg: '    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/,lib/socket.js:263:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.onpacket',
    _li,neNumber: '221',
    _columnNumber: '7',
    _msg: '    at Socket.prototype.onpacket@/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7' },
  ,{ _fileName: '/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21,',
    _columnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
 , { _fileName: '/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineN,umber: '131',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/in,dex.js:131:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js',
    _functionName: 'Manager.prototype.ondecoded',
    _lineNu,mber: '333',
    _columnNumber: '3',
    _msg: '    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3' },
  t,oString: [Function] ]

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

ReferenceError: net is not defined (/private/var/mobile/Containers/Bundle/Application/B20D8482-170B-455D-B89A-66BA220EE3B8/ThaliTest.app/www/jxcore/bv_tests
```
