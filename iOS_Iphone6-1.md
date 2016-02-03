#### Test 57924002a578a80_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/57924002a578a80/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/18E6A595-14E0-4DE3-8AED-77D95242170B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/18E6A595-14E0-4DE3-8AED-77D95242170B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/57924002a578a80/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/57924002a578a80/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65258"
,(lldb)     command script import "/tmp/18E6A595-14E0-4DE3-8AED-77D95242170B/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-03 01:40:46.447 ThaliTest[1109:1957915] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BF825B35-E393-4978-AF08-8B638F371784/Library/Cookies/Cookies.binarycookies
,2016-02-03 01:40:46.901 ThaliTest[1109:1957915] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-03 01:40:46.902 ThaliTest[1109:1957915] Multi-tasking -> Device: YES, App: YES
,2016-02-03 01:40:46.912 ThaliTest[1109:1957915] Unlimited access to network resources
,2016-02-03 01:40:46.926 ThaliTest[1109:1957915] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-03 01:40:56.711 ThaliTest[1109:1957915] Resetting plugins due to page load.
,2016-02-03 01:41:00.051 ThaliTest[1109:1957915] Finished load of: file:///var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/index.html
,2016-02-03 01:41:00.211 ThaliTest[1109:1957915] JXcore Cordova plugin initializing
,2016-02-03 01:41:00.316 ThaliTest[1109:1958282] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,2016-02-03 01:45:48.187 ThaliTest[1109:1958282] jxcore: startListeningForAdvertisements
,2016-02-03 01:45:48.189 ThaliTest[1109:1958282] multipeer manager: start client restart timer: 0x146c6b90
,2016-02-03 01:45:48.190 ThaliTest[1109:1958282] jxcore: startListeningForAdvertisements: success
ok 13 Can call startListeningForAdvertisements without error

,2016-02-03 01:45:48.194 ThaliTest[1109:1958282] jxcore: stopListeningForAdvertisements
2016-02-03 01:45:48.195 ThaliTest[1109:1958282] multipeer manager: stop client timer
2016-02-03 01:45:48.195 ThaliTest[1109:1958282] jxcore: stopListeningForAdvertisements: success
ok 14 Can call stopListeningForAdvertisements without error

,# setup

,2016-02-03 01:45:48.511 ThaliTest[1109:1958282] jxcore: stopListeningForAdvertisements
2016-02-03 01:45:48.512 ThaliTest[1109:1958282] jxcore: stopListeningForAdvertisements: success
ok 15 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-03 01:45:48.514 ThaliTest[1109:1958282] jxcore: stopAdvertisingAndListening
2016-02-03 01:45:48.514 ThaliTest[1109:1958282] THEMultipeerManager stopping peer
2016-02-03 01:45:48.515 ThaliTest[1109:1958282] jxcore: stopAdvertisingAndListening: suc,cess
ok 16 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startListeningForAdvertisements twice is an error

,# teardown

,2016-02-03 01:45:48.620 ThaliTest[1109:1958282] jxcore: startListeningForAdvertisements
2016-02-03 01:45:48.620 ThaliTest[1109:1958282] multipeer manager: start client restart timer: 0x146c6b90
2016-02-03 01:45:48.621 ThaliTest[1109:1958282] jxcore: star,tListeningForAdvertisements: success
ok 17 Can call startListeningForAdvertisements without error

,2016-02-03 01:45:48.623 ThaliTest[1109:1958282] jxcore: startListeningForAdvertisements
2016-02-03 01:45:48.623 ThaliTest[1109:1958282] jxcore: startListeningForAdvertisements: failure
,ok 18 Calling start twice is an error

ok 19 Error must be "Call Stop!"

,# setup

,2016-02-03 01:45:48.911 ThaliTest[1109:1958282] jxcore: stopListeningForAdvertisements
2016-02-03 01:45:48.912 ThaliTest[1109:1958282] multipeer manager: stop client timer
2016-02-03 01:45:48.912 ThaliTest[1109:1958282] jxcore: stopListeningForAdvertisem,ents: success
ok 20 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-03 01:45:48.914 ThaliTest[1109:1958282] jxcore: stopAdvertisingAndListening
,2016-02-03 01:45:48.915 ThaliTest[1109:1958282] THEMultipeerManager stopping peer
,2016-02-03 01:45:48.916 ThaliTest[1109:1958282] jxcore: stopAdvertisingAndListening: success
ok 21 Should be able to call stopAdvertisingAndListening in teardown

,# Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-02-03 01:45:48.973 ThaliTest[1109:1958282] jxcore: startUpdateAdvertisingAndListening
2016-02-03 01:45:48.974 ThaliTest[1109:1958282] server: starting FF83CC42-8AAD-4E03-8AEC-0991285D1ADB:1
2016-02-03 01:45:48.975 ThaliTest[1109:1958282] multipeer m,anager: start client restart timer: 0x146c6b90
2016-02-03 01:45:48.975 ThaliTest[1109:1958282] THEMultipeerManager initialized peer FF83CC42-8AAD-4E03-8AEC-0991285D1ADB:1
2016-02-03 01:45:48.975 ThaliTest[1109:1958282] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 22 Can call startUpdateAdvertisingAndListening without error

,2016-02-03 01:45:48.980 ThaliTest[1109:1958282] jxcore: stopAdvertisingAndListening
2016-02-03 01:45:48.980 ThaliTest[1109:1958282] THEMultipeerManager stopping peer
2016-02-03 01:45:48.980 ThaliTest[1109:1958282] multipeer manager: stop client timer
,2016-02-03 01:45:48.982 ThaliTest[1109:1958282] jxcore: stopAdvertisingAndListening: success
,ok 23 Can call stopAdvertisingAndListening without error

# setup

,2016-02-03 01:45:49.003 ThaliTest[1109:1958282] jxcore: stopListeningForAdvertisements
2016-02-03 01:45:49.004 ThaliTest[1109:1958282] jxcore: stopListeningForAdvertisements: success
ok 24 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-03 01:45:49.006 ThaliTest[1109:1958282] jxcore: stopAdvertisingAndListening
2016-02-03 01:45:49.006 ThaliTest[1109:1958282] THEMultipeerManager stopping peer
2016-02-03 01:45:49.007 ThaliTest[1109:1958282] jxcore: stopAdvertisingAndListening: suc,cess
ok 25 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startUpdateAdvertisingAndListening twice is NOT and error

,# teardown

,2016-02-03 01:45:49.050 ThaliTest[1109:1958282] jxcore: startUpdateAdvertisingAndListening
2016-02-03 01:45:49.050 ThaliTest[1109:1958282] server: starting FF83CC42-8AAD-4E03-8AEC-0991285D1ADB:2
2016-02-03 01:45:49.051 ThaliTest[1109:1958282] multipeer m,anager: start client restart timer: 0x146c6b90
2016-02-03 01:45:49.052 ThaliTest[1109:1958282] THEMultipeerManager initialized peer FF83CC42-8AAD-4E03-8AEC-0991285D1ADB:2
2016-02-03 01:45:49.052 ThaliTest[1109:1958282] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 26 Can call startUpdateAdvertisingAndListening without error

2016-02-03 01:45:49.054 ThaliTest[1109:1958282] jxcore: startUpdateAdvertisingAndListening
2016-02-03 01:45:49.054 ThaliTest[1109:1958282] THEMultipeerManager stopping pe,er
2016-02-03 01:45:49.055 ThaliTest[1109:1958282] multipeer manager: stop client timer
2016-02-03 01:45:49.055 ThaliTest[1109:1958282] server: starting FF83CC42-8AAD-4E03-8AEC-0991285D1ADB:3
2016-02-03 01:45:49.056 ThaliTest[1109:1958282] multipeer man,ager: start client restart timer: 0x146c6b90
2016-02-03 01:45:49.060 ThaliTest[1109:1958282] THEMultipeerManager initialized peer FF83CC42-8AAD-4E03-8AEC-0991285D1ADB:3
2016-02-03 01:45:49.060 ThaliTest[1109:1958282] jxcore: startUpdateAdvertisingAndListening: success
ok 27 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-02-03 01:45:49.086 ThaliTest[1109:1958282] jxcore: stopListeningForAdvertisements
2016-02-03 01:45:49.086 ThaliTest[1109:1958282] jxcore: stopListeningForAdvertisements: success
ok 28 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-03 01:45:49.088 ThaliTest[1109:1958282] jxcore: stopAdvertisingAndListening
2016-02-03 01:45:49.088 ThaliTest[1109:1958282] THEMultipeerManager stopping peer
2016-02-03 01:45:49.089 ThaliTest[1109:1958282] multipeer manager: stop client timer
2016-02-03 01:45:49.089 ThaliTest[1109:1958282] jxcore: stopAdvertisingAndListening: success
ok 29 Should be able to call stopAdvertisingAndListening in teardown

,# peerAvailabilityChange is called

,# teardown

,2016-02-03 01:45:49.134 ThaliTest[1109:1958282] jxcore: startUpdateAdvertisingAndListening
2016-02-03 01:45:49.134 ThaliTest[1109:1958282] server: starting FF83CC42-8AAD-4E03-8AEC-0991285D1ADB:4
2016-02-03 01:45:49.135 ThaliTest[1109:1958282] multipeer m,anager: start client restart timer: 0x146c6b90
2016-02-03 01:45:49.135 ThaliTest[1109:1958282] THEMultipeerManager initialized peer FF83CC42-8AAD-4E03-8AEC-0991285D1ADB:4
2016-02-03 01:45:49.135 ThaliTest[1109:1958282] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 30 Can call startUpdateAdvertisingAndListeningwithout error

2016-02-03 01:45:49.138 ThaliTest[1109:1958282] jxcore: startListeningForAdvertisements
2016-02-03 01:45:49.138 ThaliTest[1109:1958282] multipeer manager: stop client time,r
2016-02-03 01:45:49.138 ThaliTest[1109:1958282] multipeer manager: start client restart timer: 0x146c6b90
2016-02-03 01:45:49.139 ThaliTest[1109:1958282] jxcore: startListeningForAdvertisements: success
ok 31 Can call startListeningForAdvertisements w,ithout error

,2016-02-03 01:45:50.743 ThaliTest[1109:1957915] client: found new peer: 604E1E12-82D2-49A4-92A0-2119F4D3B9A4:4
ok 32 peers must be an array

,ok 33 peers must not be zero-length

ok 34 peer must have peerIdentifier

ok 35 peerIdentifier must be a string

ok 36 peer must have peerAvailable
,
,ok 37 peer must have pleaseConnect

,# setup

,2016-02-03 01:45:51.195 ThaliTest[1109:1958282] jxcore: stopListeningForAdvertisements
2016-02-03 01:45:51.196 ThaliTest[1109:1958282] jxcore: stopListeningForAdvertisements: success
ok 38 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-03 01:45:51.197 ThaliTest[1109:1958282] jxcore: stopAdvertisingAndListening
2016-02-03 01:45:51.198 ThaliTest[1109:1958282] THEMultipeerManager stopping peer
2016-02-03 01:45:51.198 ThaliTest[1109:1958282] multipeer manager: stop client timer
2016-02-03 01:45:51.199 ThaliTest[1109:1958282] jxcore: stopAdvertisingAndListening: success
ok 39 Should be able to call stopAdvertisingAndListening in teardown

,# Can connect to a remote peer

,# teardown

,2016-02-03 01:46:08.272 ThaliTest[1109:1958282] Error!: net is not defined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js","_functionNa,me":"","_lineNumber":"117","_columnNumber":"7","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js:117:7"},{"_fileName":"/private/var/mobile/Conta,iners/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"declareTest/</<","_lineNumber":"82","_columnNumber":"7","_msg":"    at declareTest/</<@/private/var/mobile/Containers/Bundle/Applicat,ion/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/lib/thali-tape.js:82:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modu,les/component-emitter/index.js","_functionName":"on","_lineNumber":"63","_columnNumber":"5","_msg":"    at on@/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node,_modules/component-emitter/index.js:63:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":,"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_module,s/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lin,eNumber":"263","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5"},{"_fileName":"/pr,ivate/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"221","_columnNumber":"7","_msg":"    at Soc,ket.prototype.onpacket@/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/FD825,49F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Cont,ainers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68,E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bu,ndle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F,2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"333","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/FD8,2549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3"}]
Uncaught Exception: ReferenceError: net is not defined

,[ { _fileName: '/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js',
    _functionName: '',
    _lineNumber: '117',
    _columnNumber: '7',
    _msg: '    at, @/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js:117:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7,392F2/ThaliTest.app/www/jxcore/lib/thali-tape.js',
    _functionName: 'declareTest/</<',
    _lineNumber: '82',
    _columnNumber: '7',
    _msg: '    at declareTest/</<@/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E73,92F2/ThaliTest.app/www/jxcore/lib/thali-tape.js:82:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',,
    _functionName: 'on',
    _lineNumber: '63',
    _columnNumber: '5',
    _msg: '    at on@/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/co,mponent-emitter/index.js:63:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: ',Emitter.prototype.emit',
    _lineNumber: '131',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-clie,nt/node_modules/component-emitter/index.js:131:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.,prototype.onevent',
    _lineNumber: '263',
    _columnNumber: '5',
    _msg: '    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/,lib/socket.js:263:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.onpacket',
    _li,neNumber: '221',
    _columnNumber: '7',
    _msg: '    at Socket.prototype.onpacket@/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7' },
  ,{ _fileName: '/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21,',
    _columnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
,  { _fileName: '/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _line,Number: '131',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/i,ndex.js:131:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js',
    _functionName: 'Manager.prototype.ondecoded',
    _lineN,umber: '333',
    _columnNumber: '3',
    _msg: '    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3' },
  ,toString: [Function] ]

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

ReferenceError: net is not defined (/private/var/mobile/Containers/Bundle/Application/FD82549F-2B71-40B0-B3FD-2BC68E7392F2/ThaliTest.app/www/jxcore/bv_test
```
