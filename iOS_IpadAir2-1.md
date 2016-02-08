#### Test 58135655812b57f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58135655812b57f/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/0F8D87C7-A36E-4F6D-9F80-11B080A0F8D6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/0F8D87C7-A36E-4F6D-9F80-11B080A0F8D6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58135655812b57f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58135655812b57f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B0444233-D7B7-464A-8918-AE598FAB148C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51877"
,(lldb)     command script import "/tmp/0F8D87C7-A36E-4F6D-9F80-11B080A0F8D6/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-08 17:23:09.092 ThaliTest[908:1599322] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/98FA9E00-3896-4C11-8381-4EB842757530/Library/Cookies/Cookies.binarycookies
,2016-02-08 17:23:09.534 ThaliTest[908:1599322] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-08 17:23:09.536 ThaliTest[908:1599322] Multi-tasking -> Device: YES, App: YES
,2016-02-08 17:23:09.545 ThaliTest[908:1599322] Unlimited access to network resources
,2016-02-08 17:23:09.554 ThaliTest[908:1599322] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-08 17:23:18.711 ThaliTest[908:1599322] Resetting plugins due to page load.
,2016-02-08 17:23:22.325 ThaliTest[908:1599322] Finished load of: file:///var/mobile/Containers/Bundle/Application/B0444233-D7B7-464A-8918-AE598FAB148C/ThaliTest.app/www/index.html
,2016-02-08 17:23:22.487 ThaliTest[908:1599322] JXcore Cordova plugin initializing
,2016-02-08 17:23:22.488 ThaliTest[908:1599562] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B0444233-D7B7-464A-8918-AE598FAB148C/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B0444233-D7B7-464A-8918-AE598FAB148C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B0444233-D7B7-464A-8918-AE598FAB148C/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B0444233-D7B7-464A-8918-AE598FAB148C/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B0444233-D7B7-464A-8918-AE598FAB148C/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B0444233-D7B7-464A-8918-AE598FAB148C/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B0444233-D7B7-464A-8918-AE598FAB148C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B0444233-D7B7-464A-8918-AE598FAB148C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,got: setup_multiplex can send data

ack: setup_multiplex can send data_ok

,# teardown

,ok 1 String should be length:200

,# setup

,# enqueue and run in order

,got: setup_enqueue and run in order

,ack: setup_enqueue and run in order_ok

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

,got: setup_basic

ack: setup_basic_ok

,# teardown

,ok 11 sane

,# setup

,# another

,got: setup_another

ack: setup_another_ok

,# teardown

,ok 12 sane

,# setup

,# successfully create a new pkcs12 file and return hash value

,got: setup_successfully create a new pkcs12 file and return hash value

ack: setup_successfully create a new pkcs12 file and return hash value_ok

,# teardown

,ok 13 should be equal

,ok 14 null

,ok 15 (unnamed assert)

,ok 16 should be equal

,ok 17 should not throw

,# setup

,# successfully read a previous pkcs12 file and return hash value

,got: setup_successfully read a previous pkcs12 file and return hash value

ack: setup_successfully read a previous pkcs12 file and return hash value_ok

,# teardown

,ok 18 (unnamed assert)

,ok 19 (unnamed assert)

ok 20 should not throw

,ok 21 should be equal

ok 22 should be equal

,# setup

,# failed to extract public key because of corrupt pkcs12 file

,got: setup_failed to extract public key because of corrupt pkcs12 file

ack: setup_failed to extract public key because of corrupt pkcs12 file_ok

,# teardown

,ok 23 should be equal

,# setup

,# failed to get mobile documents path

,got: setup_failed to get mobile documents path

ack: setup_failed to get mobile documents path_ok

,# teardown

,ok 24 should be equal

,# setup

,# #init should register the peerAvailabilityChanged event

,got: setup_#init should register the peerAvailabilityChanged event

,ack: setup_#init should register the peerAvailabilityChanged event_ok

,# teardown

,ok 25 should be equal

,ok 26 should be equal

,ok 27 should be equal

,# setup

,# #init should register the networkChanged event

,got: setup_#init should register the networkChanged event

,ack: setup_#init should register the networkChanged event_ok

,# teardown

,ok 28 should be equal

,# setup

,# #startBroadcasting should throw on null device name

,got: setup_#startBroadcasting should throw on null device name

ack: setup_#startBroadcasting should throw on null device name_ok

,# teardown

,ok 29 should throw

,# setup

,# #startBroadcasting should throw on empty string device name

,got: setup_#startBroadcasting should throw on empty string device name

,ack: setup_#startBroadcasting should throw on empty string device name_ok

,# teardown

,ok 30 should throw

,# setup

,# #startBroadcasting should throw on non-number port

,got: setup_#startBroadcasting should throw on non-number port

,ack: setup_#startBroadcasting should throw on non-number port_ok

,# teardown

,ok 31 should throw

,# setup

,# #startBroadcasting should throw on NaN port

,got: setup_#startBroadcasting should throw on NaN port

,ack: setup_#startBroadcasting should throw on NaN port_ok

,# teardown

,ok 32 should throw

,# setup

,# #startBroadcasting should throw on negative port

,got: setup_#startBroadcasting should throw on negative port

,ack: setup_#startBroadcasting should throw on negative port_ok

,# teardown

,ok 33 should throw

,# setup

,# #startBroadcasting should throw on too large port

,got: setup_#startBroadcasting should throw on too large port

ack: setup_#startBroadcasting should throw on too large port_ok

,# teardown

,ok 34 should throw

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,got: setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

,ack: setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error_ok

,# teardown

,ok 35 should be equal

,ok 36 should be equal

,ok 37 should be equal

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,got: setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,ack: setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error_ok

,# teardown

,ok 38 should be equal

,ok 39 should be equal

,ok 40 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,got: setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

,ack: setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error_ok

,# teardown

,ok 41 should be equal

,ok 42 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,got: setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,ack: setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error_ok

,# teardown

,ok 43 should be equal

,ok 44 should be equal

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,got: setup_#connect should call Mobile("Connect") with a port and without an error

,ack: setup_#connect should call Mobile("Connect") with a port and without an error_ok

,# teardown

,ok 45 should be equal

,ok 46 should be equal

,ok 47 should be equal

,# setup

,# #connect should call Mobile("Connect") and handle an error

,got: setup_#connect should call Mobile("Connect") and handle an error

ack: setup_#connect should call Mobile("Connect") and handle an error_ok

,# teardown

,ok 48 should be equal

,ok 49 should be equal

,# setup

,# should call Mobile("Disconnect") without an error

,got: setup_should call Mobile("Disconnect") without an error

ack: setup_should call Mobile("Disconnect") without an error_ok

,# teardown

,ok 50 should be equal

,ok 51 should be equal

,# setup

,# should call Mobile("Disconnect") and handle an error

,got: setup_should call Mobile("Disconnect") and handle an error

,ack: setup_should call Mobile("Disconnect") and handle an error_ok

,# teardown

,ok 52 should be equal

,ok 53 should be equal

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,got: setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,ack: setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error_ok

,# teardown

,2016-02-08 17:28:18.067 ThaliTest[908:1599562] jxcore: startBroadcasting
,2016-02-08 17:28:18.084 ThaliTest[908:1599562] server: starting 1454948898067.908.RF7QLw==
,2016-02-08 17:28:18.085 ThaliTest[908:1599562] multipeer session: start timer: 0x163702d0
2016-02-08 17:28:18.086 ThaliTest[908:1599562] THEMultipeerSession initialized peer 1454948898067.908
,2016-02-08 17:28:18.086 ThaliTest[908:1599562] jxcore: startBroadcasting: success
,ok 54 Should be able to call startBroadcasting without error

2016-02-08 17:28:18.090 ThaliTest[908:1599562] jxcore: stopBroadcasting
2016-02-08 17:28:18.090 ThaliTest[908:1599562] THEMultipeerSession stopping peer
2016-02-08 17:28:18.091 ThaliTest[908:1599562] multipeer session: stop timer
,2016-02-08 17:28:18.092 ThaliTest[908:1599562] jxcore: stopBroadcasting: success
ok 55 Should be able to call stopBroadcasting without error

2016-02-08 17:28:18.095 ThaliTest[908:1599562] jxcore: startBroadcasting
,2016-02-08 17:28:18.101 ThaliTest[908:1599562] server: starting 1454948898094.908.eclr0Q==
2016-02-08 17:28:18.102 ThaliTest[908:1599562] multipeer session: start timer: 0x163702d0
,2016-02-08 17:28:18.102 ThaliTest[908:1599562] THEMultipeerSession initialized peer 1454948898094.908
2016-02-08 17:28:18.103 ThaliTest[908:1599562] jxcore: startBroadcasting: success
,ok 56 Should be able to call startBroadcasting without error

2016-02-08 17:28:18.106 ThaliTest[908:1599562] jxcore: stopBroadcasting
2016-02-08 17:28:18.107 ThaliTest[908:1599562] THEMultipeerSession stopping peer
2016-02-08 17:28:18.107 ThaliTest[908,:1599562] multipeer session: stop timer
2016-02-08 17:28:18.108 ThaliTest[908:1599562] jxcore: stopBroadcasting: success
,ok 57 Should be able to call stopBroadcasting without error

,2016-02-08 17:28:18.112 ThaliTest[908:1599562] jxcore: startBroadcasting
,2016-02-08 17:28:18.116 ThaliTest[908:1599562] server: starting 1454948898110.908.cHv6+w==
2016-02-08 17:28:18.117 ThaliTest[908:1599562] multipeer session: start timer: 0x173532d0
2016-02-08 17:28:18.118 ThaliTest[908:1599562] THEMultipeerSession initia,lized peer 1454948898110.908
2016-02-08 17:28:18.118 ThaliTest[908:1599562] jxcore: startBroadcasting: success
ok 58 Should be able to call startBroadcasting without error

2016-02-08 17:28:18.121 ThaliTest[908:1599562] jxcore: stopBroadcasting
2016-0,2-08 17:28:18.122 ThaliTest[908:1599562] THEMultipeerSession stopping peer
2016-02-08 17:28:18.122 ThaliTest[908:1599562] multipeer session: stop timer
2016-02-08 17:28:18.123 ThaliTest[908:1599562] jxcore: stopBroadcasting: success
,ok 59 Should be able to call stopBroadcasting without error

2016-02-08 17:28:18.126 ThaliTest[908:1599562] jxcore: startBroadcasting
,2016-02-08 17:28:18.132 ThaliTest[908:1599562] server: starting 1454948898125.908.L/yWUw==
,2016-02-08 17:28:18.135 ThaliTest[908:1599562] multipeer session: start timer: 0x1753efb0
2016-02-08 17:28:18.136 ThaliTest[908:1599562] THEMultipeerSession initialized peer 1454948898125.908
,2016-02-08 17:28:18.136 ThaliTest[908:1599562] jxcore: startBroadcasting: success
,ok 60 Should be able to call startBroadcasting without error

2016-02-08 17:28:18.139 ThaliTest[908:1599562] jxcore: stopBroadcasting
2016-02-08 17:28:18.139 ThaliTest[908:1599562] THEMultipeerSession stopping peer
2016-02-08 17:28:18.139 ThaliTest[908,:1599562] multipeer session: stop timer
2016-02-08 17:28:18.140 ThaliTest[908:1599562] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error

2016-02-08 17:28:18.142 ThaliTest[908:1599562] jxcore: startBroadcasting
,2016-02-08 17:28:18.148 ThaliTest[908:1599562] server: starting 1454948898142.908.rOTkJA==
2016-02-08 17:28:18.149 ThaliTest[908:1599562] multipeer session: start timer: 0x1753e1a0
2016-02-08 17:28:18.149 ThaliTest[908:1599562] THEMultipeerSession initia,lized peer 1454948898142.908
,2016-02-08 17:28:18.150 ThaliTest[908:1599562] jxcore: startBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error

,2016-02-08 17:28:18.152 ThaliTest[908:1599562] jxcore: stopBroadcasting
2016-02-08 17:28:18.153 ThaliTest[908:1599562] THEMultipeerSession stopping peer
2016-02-08 17:28:18.153 ThaliTest[908:1599562] multipeer session: stop timer
2016-02-08 17:28:18.154 ThaliTest[908:1599562] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error

2016-02-08 17:28:18.157 ThaliTest[908:1599562] jxcore: startBroadcasting
,2016-02-08 17:28:18.161 ThaliTest[908:1599562] server: starting 1454948898156.908.kx0exg==
2016-02-08 17:28:18.162 ThaliTest[908:1599562] multipeer session: start timer: 0x163b0840
2016-02-08 17:28:18.162 ThaliTest[908:1599562] THEMultipeerSession initialized peer 1454948898156.908
2016-02-08 17:28:18.162 ThaliTest[908:1599562] jxcore: startBroadcasting: success
,ok 64 Should be able to call startBroadcasting without error

2016-02-08 17:28:18.168 ThaliTest[908:1599562] jxcore: stopBroadcasting
2016-02-08 17:28:18.168 ThaliTest[908:1599562] THEMultipeerSession stopping peer
2016-02-08 17:28:18.168 ThaliTest[908,:1599562] multipeer session: stop timer
2016-02-08 17:28:18.169 ThaliTest[908:1599562] jxcore: stopBroadcasting: success
ok 65 Should be able to call stopBroadcasting without error

2016-02-08 17:28:18.170 ThaliTest[908:1599562] jxcore: startBroadcasting
,2016-02-08 17:28:18.175 ThaliTest[908:1599562] server: starting 1454948898170.908.2BXdaw==
,2016-02-08 17:28:18.176 ThaliTest[908:1599562] multipeer session: start timer: 0x1753be60
,2016-02-08 17:28:18.176 ThaliTest[908:1599562] THEMultipeerSession initialized peer 1454948898170.908
,2016-02-08 17:28:18.177 ThaliTest[908:1599562] jxcore: startBroadcasting: success
ok 66 Should be able to call startBroadcasting without error

2016-02-08 17:28:18.178 ThaliTest[908:1599562] jxcore: stopBroadcasting
,2016-02-08 17:28:18.178 ThaliTest[908:1599562] THEMultipeerSession stopping peer
,2016-02-08 17:28:18.179 ThaliTest[908:1599562] multipeer session: stop timer
,2016-02-08 17:28:18.179 ThaliTest[908:1599562] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error

,2016-02-08 17:28:18.181 ThaliTest[908:1599562] jxcore: startBroadcasting
,2016-02-08 17:28:18.186 ThaliTest[908:1599562] server: starting 1454948898180.908.nY5EwA==
,2016-02-08 17:28:18.187 ThaliTest[908:1599562] multipeer session: start timer: 0x1753f580
2016-02-08 17:28:18.187 ThaliTest[908:1599562] THEMultipeerSession initialized peer 1454948898180.908
2016-02-08 17:28:18.187 ThaliTest[908:1599562] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

2016-02-08 17:28:18.189 ThaliTest[908:1599562] jxcore: stopBroadcasting
2016-02-08 17:28:18.189 ThaliTest[908:1599562] THEMultipeerSession stopping peer
2016-02-08 17:28:18.190 ThaliTest[908,:1599562] multipeer session: stop timer
2016-02-08 17:28:18.191 ThaliTest[908:1599562] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-02-08 17:28:18.194 ThaliTest[908:1599562] jxcore: startBroadcasting
,2016-02-08 17:28:18.196 ThaliTest[908:1599562] server: starting 1454948898193.908.Tg65Mg==
,2016-02-08 17:28:18.197 ThaliTest[908:1599562] multipeer session: start timer: 0x16469230
2016-02-08 17:28:18.197 ThaliTest[908:1599562] THEMultipeerSession initialized peer 1454948898193.908
2016-02-08 17:28:18.198 ThaliTest[908:1599562] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

2016-02-08 17:28:18.199 ThaliTest[908:1599562] jxcore: stopBroadcasting
2016-02-08 17:28:18.200 ThaliTest[908:1599562] THEMultipeerSession stopping peer
2016-02-08 17:28:18.200 ThaliTest[908,:1599562] multipeer session: stop timer
2016-02-08 17:28:18.200 ThaliTest[908:1599562] jxcore: stopBroadcasting: success
ok 71 Should be able to call stopBroadcasting without error

2016-02-08 17:28:18.201 ThaliTest[908:1599562] jxcore: startBroadcasti,ng
,2016-02-08 17:28:18.204 ThaliTest[908:1599562] server: starting 1454948898201.908.dYpAkQ==
2016-02-08 17:28:18.205 ThaliTest[908:1599562] multipeer session: start timer: 0x17544610
2016-02-08 17:28:18.205 ThaliTest[908:1599562] THEMultipeerSession initia,lized peer 1454948898201.908
2016-02-08 17:28:18.205 ThaliTest[908:1599562] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-02-08 17:28:18.208 ThaliTest[908:1599562] jxcore: stopBroadcasting
,2016-02-08 17:28:18.209 ThaliTest[908:1599562] THEMultipeerSession stopping peer
,2016-02-08 17:28:18.209 ThaliTest[908:1599562] multipeer session: stop timer
,2016-02-08 17:28:18.211 ThaliTest[908:1599562] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
,
,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,got: setup_ThaliEmitter calls startBroadcasting twice with error

,ack: setup_ThaliEmitter calls startBroadcasting twice with error_ok

,# teardown

,2016-02-08 17:28:18.476 ThaliTest[908:1599562] jxcore: startBroadcasting
,2016-02-08 17:28:18.480 ThaliTest[908:1599562] server: starting 1454948898476.908.7ww7Gw==
,2016-02-08 17:28:18.481 ThaliTest[908:1599562] multipeer session: start timer: 0x175480a0
,2016-02-08 17:28:18.487 ThaliTest[908:1599562] THEMultipeerSession initialized peer 1454948898476.908
,2016-02-08 17:28:18.489 ThaliTest[908:1599562] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error

,2016-02-08 17:28:18.492 ThaliTest[908:1599562] jxcore: startBroadcasting
,2016-02-08 17:28:18.493 ThaliTest[908:1599562] jxcore: startBroadcasting: failure
,ok 75 Cannot call startBroadcasting twice

,2016-02-08 17:28:18.498 ThaliTest[908:1599562] jxcore: stopBroadcasting
,2016-02-08 17:28:18.498 ThaliTest[908:1599562] THEMultipeerSession stopping peer
,2016-02-08 17:28:18.499 ThaliTest[908:1599562] multipeer session: stop timer
,2016-02-08 17:28:18.502 ThaliTest[908:1599562] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,got: setup_ThaliEmitter throws on connection to bad peer

ack: setup_ThaliEmitter throws on connection to bad peer_ok

,# teardown

,2016-02-08 17:28:19.066 ThaliTest[908:1599562] jxcore: startBroadcasting
,2016-02-08 17:28:19.070 ThaliTest[908:1599562] server: starting 1454948899066.908.v0w/xQ==
,2016-02-08 17:28:19.071 ThaliTest[908:1599562] multipeer session: start timer: 0x1754bb70
2016-02-08 17:28:19.071 ThaliTest[908:1599562] THEMultipeerSession initialized peer 1454948899066.908
2016-02-08 17:28:19.072 ThaliTest[908:1599562] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

,2016-02-08 17:28:19.074 ThaliTest[908:1599562] jxcore: connect foobar
,2016-02-08 17:28:19.075 ThaliTest[908:1599562] client: unknown peer foobar
2016-02-08 17:28:19.075 ThaliTest[908:1599562] jxcore: connect: fail: Unknown peer
,ok 78 Should not connect to a bad peer

2016-02-08 17:28:19.080 ThaliTest[908:1599562] jxcore: stopBroadcasting
2016-02-08 17:28:19.080 ThaliTest[908:1599562] THEMultipeerSession stopping peer
,2016-02-08 17:28:19.080 ThaliTest[908:1599562] multipeer session: stop timer
2016-02-08 17:28:19.082 ThaliTest[908:1599562] jxcore: stopBroadcasting: success
,ok 79 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,got: setup_ThaliEmitter throws on disconnect to bad peer

ack: setup_ThaliEmitter throws on disconnect to bad peer_ok

,# teardown

,2016-02-08 17:28:19.560 ThaliTest[908:1599562] jxcore: startBroadcasting
,2016-02-08 17:28:19.564 ThaliTest[908:1599562] server: starting 1454948899560.908.3qk6qg==
,2016-02-08 17:28:19.564 ThaliTest[908:1599562] multipeer session: start timer: 0x163f3130
,2016-02-08 17:28:19.565 ThaliTest[908:1599562] THEMultipeerSession initialized peer 1454948899560.908
,2016-02-08 17:28:19.566 ThaliTest[908:1599562] jxcore: startBroadcasting: success
,ok 80 Should be able to call startBroadcasting without error

,2016-02-08 17:28:19.568 ThaliTest[908:1599562] jxcore: disconnect
2016-02-08 17:28:19.569 ThaliTest[908:1599562] jxcore: disconnect: fail
ok 81 Disconnect should fail to a non-existant peer 

,2016-02-08 17:28:19.573 ThaliTest[908:1599562] jxcore: stopBroadcasting
,2016-02-08 17:28:19.574 ThaliTest[908:1599562] THEMultipeerSession stopping peer
2016-02-08 17:28:19.575 ThaliTest[908:1599562] multipeer session: stop timer
,2016-02-08 17:28:19.576 ThaliTest[908:1599562] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,got: setup_ThaliEmitter can discover and connect to peers

,ack: setup_ThaliEmitter can discover and connect to peers_ok

,# teardown

,2016-02-08 17:28:20.167 ThaliTest[908:1599562] jxcore: startBroadcasting
,2016-02-08 17:28:20.171 ThaliTest[908:1599562] server: starting 1454948900167.908.a5rDug==
,2016-02-08 17:28:20.171 ThaliTest[908:1599562] multipeer session: start timer: 0x17022220
,2016-02-08 17:28:20.172 ThaliTest[908:1599562] THEMultipeerSession initialized peer 1454948900167.908
,2016-02-08 17:28:20.173 ThaliTest[908:1599562] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-02-08 17:28:21.287 ThaliTest[908:1599322] client: found peer: 1454948900215.1450.ANq4tA==
,2016-02-08 17:28:21.295 ThaliTest[908:1599562] jxcore: connect 1454948900215.1450.ANq4tA==
,2016-02-08 17:28:21.296 ThaliTest[908:1599562] client session: connect
2016-02-08 17:28:21.297 ThaliTest[908:1599562] client session: stateChange:0->1 1454948900215.1450.ANq4tA==
,2016-02-08 17:28:21.357 ThaliTest[908:1599322] multipeer session: reset timer
2016-02-08 17:28:21.358 ThaliTest[908:1599322] multipeer session: stop timer
2016-02-08 17:28:21.358 ThaliTest[908:1599322] multipeer session: start timer: 0x17022220
2016-02-,08 17:28:21.359 ThaliTest[908:1599322] server session: connect
2016-02-08 17:28:21.359 ThaliTest[908:1599322] server session: stateChange:0->1 1454948900215.1450
,2016-02-08 17:28:21.367 ThaliTest[908:1599322] server: accepting invitation 1454948900215.1450
,2016-02-08 17:28:23.997 ThaliTest[908:1600076] server session: connected
2016-02-08 17:28:23.998 ThaliTest[908:1600076] server session: stateChange:1->2 1454948900215.1450
,2016-02-08 17:28:24.061 ThaliTest[908:1600076] server session: not connected 1454948900215.1450
,2016-02-08 17:28:24.168 ThaliTest[908:1600070] client session: connected
,2016-02-08 17:28:24.169 ThaliTest[908:1600070] client session: stateChange:1->2 1454948900215.1450.ANq4tA==
,2016-02-08 17:28:24.187 ThaliTest[908:1600076] client session: fireConnectCallback: 1454948900215.1450.ANq4tA==
,2016-02-08 17:28:24.188 ThaliTest[908:1600076] jxcore: connect: success
,ok 84 Should be able to connect without error

,ok 85 Port should be within range

,2016-02-08 17:28:24.193 ThaliTest[908:1599562] jxcore: disconnect
,2016-02-08 17:28:24.194 ThaliTest[908:1599562] client session: disconnectFromPeer: 1454948900215.1450.ANq4tA==
2016-02-08 17:28:24.194 ThaliTest[908:1599562] client session: disconnect
2016-02-08 17:28:24.194 ThaliTest[908:1599562] client session: stateC,hange:2->0 1454948900215.1450.ANq4tA==
,2016-02-08 17:28:24.270 ThaliTest[908:1599562] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,calling stopBroadcasting

,2016-02-08 17:28:24.295 ThaliTest[908:1599562] jxcore: stopBroadcasting
,2016-02-08 17:28:24.296 ThaliTest[908:1599562] THEMultipeerSession stopping peer
,2016-02-08 17:28:24.296 ThaliTest[908:1599562] multipeer session: stop timer
,2016-02-08 17:28:24.297 ThaliTest[908:1599562] server session: disconnect
,2016-02-08 17:28:24.298 ThaliTest[908:1599562] server session: stateChange:2->0 1454948900215.1450
,2016-02-08 17:28:24.508 ThaliTest[908:1599562] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,got: setup_ThaliEmitter can discover and connect to peers and then fail on double connect

,ack: setup_ThaliEmitter can discover and connect to peers and then fail on double connect_ok

,# teardown

,2016-02-08 17:28:24.838 ThaliTest[908:1599562] jxcore: startBroadcasting
,2016-02-08 17:28:24.841 ThaliTest[908:1599562] server: starting 1454948904837.908.jiizJA==
,2016-02-08 17:28:24.842 ThaliTest[908:1599562] multipeer session: start timer: 0x165750c0
2016-02-08 17:28:24.843 ThaliTest[908:1599562] THEMultipeerSession initialized peer 1454948904837.908
2016-02-08 17:28:24.844 ThaliTest[908:1599562] jxcore: startBroadcasting: success
,ok 87 Should be able to call startBroadcasting without error

,2016-02-08 17:28:25.412 ThaliTest[908:1599322] client: found peer: 1454948900215.1450.ANq4tA==
,2016-02-08 17:28:25.414 ThaliTest[908:1599562] jxcore: connect 1454948900215.1450.ANq4tA==
2016-02-08 17:28:25.414 ThaliTest[908:1599562] client session: connect
2016-02-08 17:28:25.415 ThaliTest[908:1599562] client session: stateChange:0->1 1454948900215.1450.ANq4tA==
,2016-02-08 17:28:25.998 ThaliTest[908:1599322] client: found peer: 1454948904613.1450.3lffqg==
,2016-02-08 17:28:26.000 ThaliTest[908:1599562] jxcore: connect 1454948904613.1450.3lffqg==
2016-02-08 17:28:26.000 ThaliTest[908:1599562] client session: connect
2016-02-08 17:28:26.000 ThaliTest[908:1599562] client session: stateChange:0->1 1454948904613.1450.3lffqg==
,2016-02-08 17:28:26.265 ThaliTest[908:1599322] multipeer session: reset timer
2016-02-08 17:28:26.265 ThaliTest[908:1599322] multipeer session: stop timer
2016-02-08 17:28:26.265 ThaliTest[908:1599322] multipeer session: start timer: 0x165750c0
2016-02-08 17:28:26.266 ThaliTest[908:1599322] server session: connect
,2016-02-08 17:28:26.266 ThaliTest[908:1599322] server session: stateChange:0->1 1454948904613.1450
,2016-02-08 17:28:26.272 ThaliTest[908:1599322] server: accepting invitation 1454948904613.1450
,2016-02-08 17:28:27.466 ThaliTest[908:1599322] client: lost peer: 1454948900215.1450.ANq4tA==
2016-02-08 17:28:27.467 ThaliTest[908:1599322] client session: onPeerLost: 1454948900215.1450.ANq4tA==
2016-02-08 17:28:27.467 ThaliTest[908:1599322] client ses,sion: onLinkFailure: 1454948900215.1450.ANq4tA==
2016-02-08 17:28:27.467 ThaliTest[908:1599322] client session: disconnect
2016-02-08 17:28:27.468 ThaliTest[908:1599322] client session: stateChange:1->0 1454948900215.1450.ANq4tA==
2016-02-08 17:28:27.46,8 ThaliTest[908:1599322] client session: fireConnectCallback: 1454948900215.1450.ANq4tA==
2016-02-08 17:28:27.469 ThaliTest[908:1599322] jxcore: connect: fail: Peer disconnected
,2016-02-08 17:28:28.482 ThaliTest[908:1599562] jxcore: connect 1454948900215.1450.ANq4tA==
,2016-02-08 17:28:28.482 ThaliTest[908:1599562] client: connect: unreachable 1454948900215.1450.ANq4tA==
,2016-02-08 17:28:28.483 ThaliTest[908:1599562] jxcore: connect: fail: Peer unreachable
,2016-02-08 17:28:28.788 ThaliTest[908:1600070] client session: connected
2016-02-08 17:28:28.789 ThaliTest[908:1600070] client session: stateChange:1->2 1454948904613.1450.3lffqg==
,2016-02-08 17:28:28.792 ThaliTest[908:1600070] client session: fireConnectCallback: 1454948904613.1450.3lffqg==
,2016-02-08 17:28:28.793 ThaliTest[908:1600070] jxcore: connect: success
,ok 88 Should be able to connect without error

ok 89 Port should be within range

,2016-02-08 17:28:28.797 ThaliTest[908:1599562] jxcore: connect 1454948904613.1450.3lffqg==
,2016-02-08 17:28:28.798 ThaliTest[908:1599562] client: already connect(ing/ed) to 1454948904613.1450.3lffqg==
,2016-02-08 17:28:28.798 ThaliTest[908:1599562] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

,2016-02-08 17:28:28.803 ThaliTest[908:1599562] jxcore: disconnect
,2016-02-08 17:28:28.805 ThaliTest[908:1600070] server session: connected
,2016-02-08 17:28:28.804 ThaliTest[908:1599562] client session: disconnectFromPeer: 1454948904613.1450.3lffqg==
,2016-02-08 17:28:28.806 ThaliTest[908:1600070] server session: stateChange:1->2 1454948904613.1450
,2016-02-08 17:28:28.806 ThaliTest[908:1599562] client session: disconnect
,2016-02-08 17:28:28.808 ThaliTest[908:1599562] client session: stateChange:2->0 1454948904613.1450.3lffqg==
,2016-02-08 17:28:28.815 ThaliTest[908:1599322] server relay: socket disconnected
,2016-02-08 17:28:28.816 ThaliTest[908:1599322] server relay: 0x166bbc00 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-08 17:28:28.889 ThaliTest[908:1599562] jxcore: disconnect: success
,ok 91 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,2016-02-08 17:28:28.898 ThaliTest[908:1600074] server session: not connected 1454948904613.1450
,# setup

,calling stopBroadcasting

,2016-02-08 17:28:28.967 ThaliTest[908:1599562] jxcore: stopBroadcasting
,2016-02-08 17:28:28.967 ThaliTest[908:1599562] THEMultipeerSession stopping peer
2016-02-08 17:28:28.967 ThaliTest[908:1599562] multipeer session: stop timer
,2016-02-08 17:28:28.968 ThaliTest[908:1599562] server session: disconnect
2016-02-08 17:28:28.968 ThaliTest[908:1599562] server session: stateChange:2->0 1454948904613.1450
,2016-02-08 17:28:28.970 ThaliTest[908:1599562] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,got: setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect

,ack: setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect_ok

,# teardown

,2016-02-08 17:28:29.535 ThaliTest[908:1599562] jxcore: startBroadcasting
,2016-02-08 17:28:29.539 ThaliTest[908:1599562] server: starting 1454948909535.908.VAwgOA==
,2016-02-08 17:28:29.540 ThaliTest[908:1599562] multipeer session: start timer: 0x1659fd30
,2016-02-08 17:28:29.540 ThaliTest[908:1599562] THEMultipeerSession initialized peer 1454948909535.908
,2016-02-08 17:28:29.541 ThaliTest[908:1599562] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-08 17:28:30.357 ThaliTest[908:1599322] client: found peer: 1454948909304.1450.LkHJHA==
,2016-02-08 17:28:30.359 ThaliTest[908:1599562] jxcore: connect 1454948909304.1450.LkHJHA==
2016-02-08 17:28:30.359 ThaliTest[908:1599562] client session: connect
2016-02-08 17:28:30.360 ThaliTest[908:1599562] client session: stateChange:0->1 1454948909304.1450.LkHJHA==
,2016-02-08 17:28:30.786 ThaliTest[908:1599322] multipeer session: reset timer
2016-02-08 17:28:30.787 ThaliTest[908:1599322] multipeer session: stop timer
,2016-02-08 17:28:30.787 ThaliTest[908:1599322] multipeer session: start timer: 0x1659fd30
2016-02-08 17:28:30.787 ThaliTest[908:1599322] server session: connect
,2016-02-08 17:28:30.788 ThaliTest[908:1599322] server session: stateChange:0->1 1454948909304.1450
,2016-02-08 17:28:30.795 ThaliTest[908:1599322] server: accepting invitation 1454948909304.1450
,2016-02-08 17:28:33.238 ThaliTest[908:1600069] client session: connected
2016-02-08 17:28:33.239 ThaliTest[908:1600069] client session: stateChange:1->2 1454948909304.1450.LkHJHA==
,2016-02-08 17:28:33.255 ThaliTest[908:1600120] client session: fireConnectCallback: 1454948909304.1450.LkHJHA==
2016-02-08 17:28:33.256 ThaliTest[908:1600120] jxcore: connect: success
,ok 93 Should be able to connect without error

ok 94 Port should be within range

,2016-02-08 17:28:33.260 ThaliTest[908:1599562] jxcore: disconnect
2016-02-08 17:28:33.261 ThaliTest[908:1599562] client session: disconnectFromPeer: 1454948909304.1450.LkHJHA==
2016-02-08 17:28:33.261 ThaliTest[908:1599562] client session: disconnect
,2016-02-08 17:28:33.261 ThaliTest[908:1599562] client session: stateChange:2->0 1454948909304.1450.LkHJHA==
,2016-02-08 17:28:33.279 ThaliTest[908:1600076] server session: connected
,2016-02-08 17:28:33.279 ThaliTest[908:1600076] server session: stateChange:1->2 1454948909304.1450
,2016-02-08 17:28:33.295 ThaliTest[908:1599322] server relay: socket disconnected
,2016-02-08 17:28:33.295 ThaliTest[908:1599322] server relay: 0x147f63b0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-08 17:28:33.342 ThaliTest[908:1599562] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error

,2016-02-08 17:28:33.344 ThaliTest[908:1599562] jxcore: disconnect
,2016-02-08 17:28:33.345 ThaliTest[908:1599562] jxcore: disconnect: fail
,ok 96 Disconnect should fail 

,setting stopBroadcasting callback and ending test.

,2016-02-08 17:28:33.360 ThaliTest[908:1600074] server session: not connected 1454948909304.1450
,# setup

,calling stopBroadcasting

,2016-02-08 17:28:33.683 ThaliTest[908:1599562] jxcore: stopBroadcasting
,2016-02-08 17:28:33.684 ThaliTest[908:1599562] THEMultipeerSession stopping peer
,2016-02-08 17:28:33.684 ThaliTest[908:1599562] multipeer session: stop timer
2016-02-08 17:28:33.685 ThaliTest[908:1599562] server session: disconnect
,2016-02-08 17:28:33.686 ThaliTest[908:1599562] server session: stateChange:2->0 1454948909304.1450
,2016-02-08 17:28:33.688 ThaliTest[908:1599562] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,got: setup_ThaliEmitter can connect and send data

,ack: setup_ThaliEmitter can connect and send data_ok

,# teardown

,echo server started on port: 54416

,2016-02-08 17:28:34.518 ThaliTest[908:1599562] jxcore: startBroadcasting
,2016-02-08 17:28:34.520 ThaliTest[908:1599562] server: starting 1454948914518.908.qjeQqg==
,2016-02-08 17:28:34.520 ThaliTest[908:1599562] multipeer session: start timer: 0x170ce680
2016-02-08 17:28:34.520 ThaliTest[908:1599562] THEMultipeerSession initialized peer 1454948914518.908
2016-02-08 17:28:34.520 ThaliTest[908:1599562] jxcore: startBroadcasting: success
ok 97 Should be able to call startBroadcasting without error

,2016-02-08 17:28:35.957 ThaliTest[908:1599322] client: found peer: 1454948914523.1450./qNtqA==
,2016-02-08 17:28:35.958 ThaliTest[908:1599562] jxcore: connect 1454948914523.1450./qNtqA==
2016-02-08 17:28:35.959 ThaliTest[908:1599562] client session: connect
2016-02-08 17:28:35.959 ThaliTest[908:1599562] client session: stateChange:0->1 1454948914523.1450./qNtqA==
,2016-02-08 17:28:36.027 ThaliTest[908:1599322] multipeer session: reset timer
2016-02-08 17:28:36.027 ThaliTest[908:1599322] multipeer session: stop timer
,2016-02-08 17:28:36.028 ThaliTest[908:1599322] multipeer session: start timer: 0x170ce680
2016-02-08 17:28:36.028 ThaliTest[908:1599322] server session: connect
,2016-02-08 17:28:36.028 ThaliTest[908:1599322] server session: stateChange:0->1 1454948914523.1450
,2016-02-08 17:28:36.035 ThaliTest[908:1599322] server: accepting invitation 1454948914523.1450
,2016-02-08 17:28:38.718 ThaliTest[908:1600075] server session: connected
2016-02-08 17:28:38.718 ThaliTest[908:1600075] server session: stateChange:1->2 1454948914523.1450
,2016-02-08 17:28:38.783 ThaliTest[908:1599322] server relay: connected (to port: 54416)
,2016-02-08 17:28:38.899 ThaliTest[908:1600075] client session: connected
,2016-02-08 17:28:38.899 ThaliTest[908:1600075] client session: stateChange:1->2 1454948914523.1450./qNtqA==
,2016-02-08 17:28:39.052 ThaliTest[908:1600076] client session: fireConnectCallback: 1454948914523.1450./qNtqA==
2016-02-08 17:28:39.053 ThaliTest[908:1600076] jxcore: connect: success
ok 98 Should be able to connect without error

,ok 99 Port should be within range

,2016-02-08 17:28:39.062 ThaliTest[908:1599322] client: relay established
2016-02-08 17:28:39.063 ThaliTest[908:1599322] client: new accepted socket: 0x173196f0
,2016-02-08 17:28:39.302 ThaliTest[908:1600076] server session: not connected 1454948914523.1450
,data in 1095

,data in 16425

,data in 38325

,data in 41610

,data in 45990

,data in 61320

,data in 78840

,data in 79935

,data in 86505

,data in 131072

,ok 100 the test messages should be equal

,2016-02-08 17:28:39.675 ThaliTest[908:1599562] jxcore: disconnect
,2016-02-08 17:28:39.675 ThaliTest[908:1599562] client session: disconnectFromPeer: 1454948914523.1450./qNtqA==
,2016-02-08 17:28:39.675 ThaliTest[908:1599562] client session: disconnect
,2016-02-08 17:28:39.676 ThaliTest[908:1599562] client session: stateChange:2->0 1454948914523.1450./qNtqA==
,2016-02-08 17:28:39.738 ThaliTest[908:1599562] jxcore: disconnect: success
,ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.
,
,# setup

,calling stopBroadcasting

,2016-02-08 17:28:39.970 ThaliTest[908:1599562] jxcore: stopBroadcasting
,2016-02-08 17:28:39.970 ThaliTest[908:1599562] THEMultipeerSession stopping peer
,2016-02-08 17:28:39.971 ThaliTest[908:1599562] multipeer session: stop timer
,2016-02-08 17:28:39.972 ThaliTest[908:1599562] server session: disconnect
,2016-02-08 17:28:39.976 ThaliTest[908:1599562] server session: stateChange:2->0 1454948914523.1450
,2016-02-08 17:28:40.392 ThaliTest[908:1599562] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,got: setup_ThaliEmitter handles socket disconnect correctly

ack: setup_ThaliEmitter handles socket disconnect correctly_ok

,# teardown

,echo server started on port: 54422

,2016-02-08 17:28:40.545 ThaliTest[908:1599562] jxcore: startBroadcasting
,2016-02-08 17:28:40.548 ThaliTest[908:1599562] server: starting 1454948920544.908.v6tM6w==
,2016-02-08 17:28:40.549 ThaliTest[908:1599562] multipeer session: start timer: 0x16513280
2016-02-08 17:28:40.550 ThaliTest[908:1599562] THEMultipeerSession initialized peer 1454948920544.908
2016-02-08 17:28:40.550 ThaliTest[908:1599562] jxcore: startBroadcasting: success
,ok 102 Should be able to call startBroadcasting without error

,2016-02-08 17:28:41.723 ThaliTest[908:1599322] client: found peer: 1454948920315.1450.tJ+2tw==
,[{"peerIdentifier":"1454948920315.1450.tJ+2tw==","peerName":"(null)","peerAvailable":true}]

,2016-02-08 17:28:41.726 ThaliTest[908:1599562] jxcore: connect 1454948920315.1450.tJ+2tw==
,2016-02-08 17:28:41.727 ThaliTest[908:1599562] client session: connect
,2016-02-08 17:28:41.727 ThaliTest[908:1599562] client session: stateChange:0->1 1454948920315.1450.tJ+2tw==
,2016-02-08 17:28:41.858 ThaliTest[908:1599322] multipeer session: reset timer
,2016-02-08 17:28:41.859 ThaliTest[908:1599322] multipeer session: stop timer
,2016-02-08 17:28:41.859 ThaliTest[908:1599322] multipeer session: start timer: 0x16513280
,2016-02-08 17:28:41.859 ThaliTest[908:1599322] server session: connect
,2016-02-08 17:28:41.860 ThaliTest[908:1599322] server session: stateChange:0->1 1454948920315.1450
,2016-02-08 17:28:41.867 ThaliTest[908:1599322] server: accepting invitation 1454948920315.1450
,2016-02-08 17:28:44.332 ThaliTest[908:1600070] client session: connected
,2016-02-08 17:28:44.332 ThaliTest[908:1600070] client session: stateChange:1->2 1454948920315.1450.tJ+2tw==
,2016-02-08 17:28:44.360 ThaliTest[908:1600069] client session: fireConnectCallback: 1454948920315.1450.tJ+2tw==
2016-02-08 17:28:44.360 ThaliTest[908:1600069] jxcore: connect: success
,ok 103 Should be able to connect without error

,ok 104 Port should be within range

,ok 105 First connect should succeed

,2016-02-08 17:28:44.425 ThaliTest[908:1600069] server session: connected
2016-02-08 17:28:44.425 ThaliTest[908:1600069] server session: stateChange:1->2 1454948920315.1450
,2016-02-08 17:28:44.430 ThaliTest[908:1599322] client: relay established
2016-02-08 17:28:44.431 ThaliTest[908:1599322] client: new accepted socket: 0x16593960
,2016-02-08 17:28:44.451 ThaliTest[908:1599322] server relay: connected (to port: 54422)
,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-02-08 17:28:44.564 ThaliTest[908:1599322] client: socket closed
,2016-02-08 17:28:44.564 ThaliTest[908:1599322] client relay: socket disconnected
,2016-02-08 17:28:44.565 ThaliTest[908:1599322] client relay: 0x16593960 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-08 17:28:44.565 ThaliTest[908:1599322] client session: socket closed: 1454948920315.1450.tJ+2tw==
2016-02-08 17:28:44.565 ThaliTest[908:1599322] client session: onLinkFailure: 1454948920315.1450.tJ+2tw==
,2016-02-08 17:28:44.566 ThaliTest[908:1599322] client session: disconnect
2016-02-08 17:28:44.566 ThaliTest[908:1599322] client session: stateChange:2->0 1454948920315.1450.tJ+2tw==
,2016-02-08 17:28:44.575 ThaliTest[908:1599322] client session: fireConnectionErrorEvent: 1454948920315.1450.tJ+2tw==
,2016-02-08 17:28:44.579 ThaliTest[908:1599562] jxcore: connect 1454948920315.1450.tJ+2tw==
,2016-02-08 17:28:44.581 ThaliTest[908:1599562] client session: connect
,2016-02-08 17:28:44.582 ThaliTest[908:1599562] client session: stateChange:0->1 1454948920315.1450.tJ+2tw==
,2016-02-08 17:28:44.743 ThaliTest[908:1600076] server session: not connected 1454948920315.1450
,2016-02-08 17:28:44.944 ThaliTest[908:1599322] multipeer session: reset timer
2016-02-08 17:28:44.944 ThaliTest[908:1599322] multipeer session: stop timer
2016-02-08 17:28:44.945 ThaliTest[908:1599322] multipeer session: start timer: 0x16513280
2016-02-,08 17:28:44.945 ThaliTest[908:1599322] server: disconnecting to refresh session (1454948920315.1450)
2016-02-08 17:28:44.945 ThaliTest[908:1599322] server session: disconnect
2016-02-08 17:28:44.946 ThaliTest[908:1599322] server session: stateChange:2->0, 1454948920315.1450
,2016-02-08 17:28:44.950 ThaliTest[908:1599322] server session: connect
2016-02-08 17:28:44.950 ThaliTest[908:1599322] server session: stateChange:0->1 1454948920315.1450
,2016-02-08 17:28:44.961 ThaliTest[908:1599322] server: accepting invitation 1454948920315.1450
,2016-02-08 17:28:47.441 ThaliTest[908:1600069] server session: connected
2016-02-08 17:28:47.441 ThaliTest[908:1600069] server session: stateChange:1->2 1454948920315.1450
,2016-02-08 17:28:47.447 ThaliTest[908:1600200] client session: connected
2016-02-08 17:28:47.448 ThaliTest[908:1600200] client session: stateChange:1->2 1454948920315.1450.tJ+2tw==
,2016-02-08 17:28:47.497 ThaliTest[908:1599322] server relay: connected (to port: 54422)
,2016-02-08 17:28:47.502 ThaliTest[908:1600200] client session: fireConnectCallback: 1454948920315.1450.tJ+2tw==
,2016-02-08 17:28:47.503 ThaliTest[908:1600200] jxcore: connect: success
,ok 108 Should be able to connect without error

,ok 109 Port should be within range

,ok 110 Second connect should succeed

,2016-02-08 17:28:47.536 ThaliTest[908:1599322] client: relay established
2016-02-08 17:28:47.536 ThaliTest[908:1599322] client: new accepted socket: 0x170a1ab0
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-02-08 17:28:47.615 ThaliTest[908:1599322] client: socket closed
,2016-02-08 17:28:47.616 ThaliTest[908:1599322] client relay: socket disconnected
,2016-02-08 17:28:47.617 ThaliTest[908:1599322] client relay: 0x170a1ab0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-08 17:28:47.617 ThaliTest[908:1599322] client session: socket closed: 1454948920315.1450.tJ+2tw==
2016-02-08 17:28:47.617 ThaliTest[908:1599322] client session: onLinkFailure: 1454948920315.1450.tJ+2tw==
,2016-02-08 17:28:47.618 ThaliTest[908:1599322] client session: disconnect
,2016-02-08 17:28:47.618 ThaliTest[908:1599322] client session: stateChange:2->0 1454948920315.1450.tJ+2tw==
,2016-02-08 17:28:47.629 ThaliTest[908:1599322] client session: fireConnectionErrorEvent: 1454948920315.1450.tJ+2tw==
,2016-02-08 17:28:47.651 ThaliTest[908:1600070] server session: not connected 1454948920315.1450
,calling stopBroadcasting

,2016-02-08 17:28:48.366 ThaliTest[908:1599562] jxcore: stopBroadcasting
,2016-02-08 17:28:48.367 ThaliTest[908:1599562] THEMultipeerSession stopping peer
,2016-02-08 17:28:48.367 ThaliTest[908:1599562] multipeer session: stop timer
2016-02-08 17:28:48.368 ThaliTest[908:1599562] server session: disconnect
2016-02-08 17:28:48.368 ThaliTest[908:1599562] server session: stateChange:2->0 1454948920315.1450
,2016-02-08 17:28:48.377 ThaliTest[908:1599562] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,got: setup_ThaliReplicationManager can call start without error

ack: setup_ThaliReplicationManager can call start without error_ok

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/98FA9E00-3896-4C11-8381-4EB842757530/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-02-08 17:28:49.051 ThaliTest[908:1599562] jxcore: startBroadcasting
,2016-02-08 17:28:49.052 ThaliTest[908:1599562] server: starting 8YQKCGaSKtvCoZ666nmkBw.R03wCg==
,2016-02-08 17:28:49.053 ThaliTest[908:1599562] multipeer session: start timer: 0x17388290
2016-02-08 17:28:49.053 ThaliTest[908:1599562] THEMultipeerSession initialized peer 8YQKCGaSKtvCoZ666nmkBw
,2016-02-08 17:28:49.053 ThaliTest[908:1599562] jxcore: startBroadcasting: success
,ok 114 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 115 stopping event should occur in right order

About to call stopBroadcasting

,2016-02-08 17:28:49.055 ThaliTest[908:1599562] jxcore: stopBroadcasting
2016-02-08 17:28:49.056 ThaliTest[908:1599562] THEMultipeerSession stopping peer
2016-02-08 17:28:49.056 ThaliTest[908:1599562] multipeer session: stop timer
2016-02-08 17:28:49.056 ThaliTest[908:1599562] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,ok 116 stopped event should occur in right order

,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,got: setup_ThaliReplicationManager receives identity

ack: setup_ThaliReplicationManager receives identity_ok

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/98FA9E00-3896-4C11-8381-4EB842757530/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-08 17:28:49.842 ThaliTest[908:1599562] jxcore: startBroadcasting
,2016-02-08 17:28:49.846 ThaliTest[908:1599562] server: starting 8YQKCGaSKtvCoZ666nmkBw.D0CrAg==
,2016-02-08 17:28:49.846 ThaliTest[908:1599562] multipeer session: start timer: 0x170d0cd0
2016-02-08 17:28:49.847 ThaliTest[908:1599562] THEMultipeerSession initialized peer 8YQKCGaSKtvCoZ666nmkBw
2016-02-08 17:28:49.848 ThaliTest[908:1599562] jxcore: startBroadcasting: success
ok 117 getDeviceIdentity should not return an error

,ok 118 deviceName should not be null

Now in TRM stop

State of this._isStarted: true

,About to call stopBroadcasting

,2016-02-08 17:28:49.852 ThaliTest[908:1599562] jxcore: stopBroadcasting
2016-02-08 17:28:49.852 ThaliTest[908:1599562] THEMultipeerSession stopping peer
2016-02-08 17:28:49.852 ThaliTest[908:1599562] multipeer session: stop timer
2016-02-08 17:28:49.853, ThaliTest[908:1599562] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager replicates database

,got: setup_ThaliReplicationManager replicates database

,ack: setup_ThaliReplicationManager replicates database_ok

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/98FA9E00-3896-4C11-8381-4EB842757530/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-08 17:28:52.142 ThaliTest[908:1599562] jxcore: startBroadcasting
,2016-02-08 17:28:52.143 ThaliTest[908:1599562] server: starting 8YQKCGaSKtvCoZ666nmkBw.XdUDAg==
,2016-02-08 17:28:52.144 ThaliTest[908:1599562] multipeer session: start timer: 0x1647b9b0
,2016-02-08 17:28:52.144 ThaliTest[908:1599562] THEMultipeerSession initialized peer 8YQKCGaSKtvCoZ666nmkBw
,2016-02-08 17:28:52.144 ThaliTest[908:1599562] jxcore: startBroadcasting: success
,ok 119 getDeviceIdentity should not return an error

,ok 120 deviceName should not be null

,2016-02-08 17:28:52.148 ThaliTest[908:1599322] client: found peer: 1454948920315.1450.tJ+2tw==
,2016-02-08 17:28:56.216 ThaliTest[908:1599322] client: found peer: A8r5qr6EQ_jXLm5R5Z0FRA.WBGXkA==
,2016-02-08 17:28:56.239 ThaliTest[908:1599562] jxcore: connect 1454948920315.1450.tJ+2tw==
2016-02-08 17:28:56.239 ThaliTest[908:1599562] client session: connect
2016-02-08 17:28:56.239 ThaliTest[908:1599562] client session: stateChange:0->1 1454948920315.1450.tJ+2tw==
,2016-02-08 17:28:56.242 ThaliTest[908:1599562] jxcore: connect A8r5qr6EQ_jXLm5R5Z0FRA.WBGXkA==
2016-02-08 17:28:56.242 ThaliTest[908:1599562] client session: connect
,2016-02-08 17:28:56.242 ThaliTest[908:1599562] client session: stateChange:0->1 A8r5qr6EQ_jXLm5R5Z0FRA.WBGXkA==
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-02-08 17:28:56.999 ThaliTest[908:1599322] multipeer session: reset timer
2016-02-08 17:28:56.999 ThaliTest[908:1599322] multipeer session: stop timer
,2016-02-08 17:28:57.000 ThaliTest[908:1599322] multipeer session: start timer: 0x1647b9b0
,2016-02-08 17:28:57.000 ThaliTest[908:1599322] server session: connect
2016-02-08 17:28:57.001 ThaliTest[908:1599322] server session: stateChange:0->1 A8r5qr6EQ_jXLm5R5Z0FRA
,2016-02-08 17:28:57.007 ThaliTest[908:1599322] server: accepting invitation A8r5qr6EQ_jXLm5R5Z0FRA
,2016-02-08 17:28:59.336 ThaliTest[908:1600120] client session: connected
,2016-02-08 17:28:59.337 ThaliTest[908:1600120] client session: stateChange:1->2 A8r5qr6EQ_jXLm5R5Z0FRA.WBGXkA==
,2016-02-08 17:28:59.342 ThaliTest[908:1600120] client session: fireConnectCallback: A8r5qr6EQ_jXLm5R5Z0FRA.WBGXkA==
2016-02-08 17:28:59.342 ThaliTest[908:1600120] jxcore: connect: success
,2016-02-08 17:28:59.356 ThaliTest[908:1599322] client: relay established
2016-02-08 17:28:59.357 ThaliTest[908:1599322] client: new accepted socket: 0x145cc260
,client bridge: new client socket

,client bridge: new client socket

,2016-02-08 17:28:59.503 ThaliTest[908:1600200] server session: connected
2016-02-08 17:28:59.505 ThaliTest[908:1600200] server session: stateChange:1->2 A8r5qr6EQ_jXLm5R5Z0FRA
,2016-02-08 17:28:59.545 ThaliTest[908:1599322] server relay: connected (to port: 54437)
,server bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed
,
,client bridge: new client socket

,client bridge: socket closed
,
,client bridge: socket closed

,ok 123 1st change of remote doc should contain remote id
,
,ok 124 Can update remote doc without error
,
,null

,{ ok: true,
  id: '2ae2cefd-0670-4079-a02a-8418b163b50c',
  rev: '2-d43d76ab8a1ec395861ee72fb18bd741' }

,client bridge: new client socket

,ok 125 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

client bridge: socket closed

,ok 126 Local changes occur in strict order

,ok 127 2nd change of local doc should contain remote id

,# setup

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,Now in TRM stop

,State of this._isStarted: true

,About to call stopBroadcasting

,2016-02-08 17:29:10.370 ThaliTest[908:1599562] jxcore: stopBroadcasting
,2016-02-08 17:29:10.371 ThaliTest[908:1599562] THEMultipeerSession stopping peer
,2016-02-08 17:29:10.371 ThaliTest[908:1599562] multipeer session: stop timer
2016-02-08 17:29:10.372 ThaliTest[908:1599562] client session: disconnect
,2016-02-08 17:29:10.372 ThaliTest[908:1599562] client session: stateChange:2->0 A8r5qr6EQ_jXLm5R5Z0FRA.WBGXkA==
,2016-02-08 17:29:10.380 ThaliTest[908:1599562] client session: disconnect
2016-02-08 17:29:10.380 ThaliTest[908:1599562] client session: stateChange:1->0 1454948920315.1450.tJ+2tw==
2016-02-08 17:29:10.381 ThaliTest[908:1599562] server session: disconnect
2016-02-08 17:29:10.381 ThaliTest[908:1599562] server session: stateChange:2->0 A8r5qr6EQ_jXLm5R5Z0FRA
,2016-02-08 17:29:10.470 ThaliTest[908:1599562] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,2016-02-08 17:29:10.550 ThaliTest[908:1599562] Error!: connect ECONNREFUSED
Stack:[{"_fileName":"net.js","_functionName":"$c","_lineNumber":"837","_columnNumber":"7","_msg":"    at $c@net.js:837:7"},{"_fileName":"net.js","_functionName":"$09","_lineNumber":"829","_columnNumber":"13","_msg":"    at $09@net.js:829:13"},{"_fileName":"net.js","_functionName":"unknown","_lineNumber":"837","_columnNumber":"7","_msg":""}]
,Uncaught Exception: Error: connect ECONNREFUSED

,[ { _fileName: 'net.js',
    _functionName: '$c',
    _lineNumber: '837',
    _columnNumber: '7',
    _msg: '    at $c@net.js:837:7' },
  { _fileName: 'net.js',
    _functionName: '$09',
    _lineNumber: '829',
    _columnNumber: '13',
    _msg: ',    at $09@net.js:829:13' },
  { _fileName: 'net.js',
,    _functionName: 'unknown',
    _lineNumber: '837',
    _columnNumber: '7',
    _msg: '' },
  toString: [Function] ]

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****


```
