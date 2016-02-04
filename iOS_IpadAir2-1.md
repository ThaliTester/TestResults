#### Test 58135655a1ee273_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58135655a1ee273/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/0EFC3A68-AAFB-4C44-871E-FCFAC0E7AFA9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/0EFC3A68-AAFB-4C44-871E-FCFAC0E7AFA9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58135655a1ee273/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58135655a1ee273/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1AC20CC7-1E2E-4EF6-AE12-B1BB939F890E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50337"
,(lldb)     command script import "/tmp/0EFC3A68-AAFB-4C44-871E-FCFAC0E7AFA9/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-04 15:45:30.884 ThaliTest[676:989664] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BAE148A8-0BBF-46CC-84C0-375B192ABBC4/Library/Cookies/Cookies.binarycookies
,2016-02-04 15:45:31.248 ThaliTest[676:989664] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-04 15:45:31.249 ThaliTest[676:989664] Multi-tasking -> Device: YES, App: YES
,2016-02-04 15:45:31.258 ThaliTest[676:989664] Unlimited access to network resources
,2016-02-04 15:45:31.267 ThaliTest[676:989664] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-04 15:45:41.207 ThaliTest[676:989664] Resetting plugins due to page load.
,2016-02-04 15:45:45.301 ThaliTest[676:989664] Finished load of: file:///var/mobile/Containers/Bundle/Application/1AC20CC7-1E2E-4EF6-AE12-B1BB939F890E/ThaliTest.app/www/index.html
,2016-02-04 15:45:45.458 ThaliTest[676:989664] JXcore Cordova plugin initializing
,2016-02-04 15:45:45.459 ThaliTest[676:989918] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1AC20CC7-1E2E-4EF6-AE12-B1BB939F890E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1AC20CC7-1E2E-4EF6-AE12-B1BB939F890E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1AC20CC7-1E2E-4EF6-AE12-B1BB939F890E/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1AC20CC7-1E2E-4EF6-AE12-B1BB939F890E/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1AC20CC7-1E2E-4EF6-AE12-B1BB939F890E/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1AC20CC7-1E2E-4EF6-AE12-B1BB939F890E/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1AC20CC7-1E2E-4EF6-AE12-B1BB939F890E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1AC20CC7-1E2E-4EF6-AE12-B1BB939F890E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,got: setup_multiplex can send data

,ack: setup_multiplex can send data_ok

,# teardown

,ok 1 String should be length:200

,# setup

,# enqueue and run in order

,got: setup_enqueue and run in order

ack: setup_enqueue and run in order_ok

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

# setup

,# successfully read a previous pkcs12 file and return hash value
,
,got: setup_successfully read a previous pkcs12 file and return hash value

,ack: setup_successfully read a previous pkcs12 file and return hash value_ok

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
,
,# teardown

,ok 25 should be equal

,ok 26 should be equal

,ok 27 should be equal

,# setup

,# #init should register the networkChanged event

,got: setup_#init should register the networkChanged event

ack: setup_#init should register the networkChanged event_ok

,# teardown

,ok 28 should be equal

,# setup

,# #startBroadcasting should throw on null device name

,got: setup_#startBroadcasting should throw on null device name

,ack: setup_#startBroadcasting should throw on null device name_ok

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

ack: setup_#startBroadcasting should throw on NaN port_ok

,# teardown

,ok 32 should throw

,# setup

,# #startBroadcasting should throw on negative port

,got: setup_#startBroadcasting should throw on negative port

ack: setup_#startBroadcasting should throw on negative port_ok

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

ack: setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error_ok

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

ack: setup_#connect should call Mobile("Connect") with a port and without an error_ok

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

ack: setup_should call Mobile("Disconnect") and handle an error_ok

,# teardown

,ok 52 should be equal

,ok 53 should be equal

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,got: setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

ack: setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error_ok

,# teardown

,2016-02-04 15:51:35.968 ThaliTest[676:989918] jxcore: startBroadcasting
,2016-02-04 15:51:35.984 ThaliTest[676:989918] server: starting 1454597495967.676.DQm11Q==
,2016-02-04 15:51:35.986 ThaliTest[676:989918] multipeer session: start timer: 0x1926cd60
,2016-02-04 15:51:35.986 ThaliTest[676:989918] THEMultipeerSession initialized peer 1454597495967.676
,2016-02-04 15:51:35.988 ThaliTest[676:989918] jxcore: startBroadcasting: success
,ok 54 Should be able to call startBroadcasting without error

2016-02-04 15:51:35.991 ThaliTest[676:989918] jxcore: stopBroadcasting
2016-02-04 15:51:35.991 ThaliTest[676:989918] THEMultipeerSession stopping peer
,2016-02-04 15:51:35.991 ThaliTest[676:989918] multipeer session: stop timer
,2016-02-04 15:51:35.993 ThaliTest[676:989918] jxcore: stopBroadcasting: success
ok 55 Should be able to call stopBroadcasting without error

,2016-02-04 15:51:35.997 ThaliTest[676:989918] jxcore: startBroadcasting
,2016-02-04 15:51:36.007 ThaliTest[676:989918] server: starting 1454597495997.676.07JSAA==
,2016-02-04 15:51:36.010 ThaliTest[676:989918] multipeer session: start timer: 0x18659280
,2016-02-04 15:51:36.013 ThaliTest[676:989918] THEMultipeerSession initialized peer 1454597495997.676
,2016-02-04 15:51:36.014 ThaliTest[676:989918] jxcore: startBroadcasting: success
,ok 56 Should be able to call startBroadcasting without error

,2016-02-04 15:51:36.018 ThaliTest[676:989918] jxcore: stopBroadcasting
2016-02-04 15:51:36.018 ThaliTest[676:989918] THEMultipeerSession stopping peer
,2016-02-04 15:51:36.020 ThaliTest[676:989918] multipeer session: stop timer
,2016-02-04 15:51:36.022 ThaliTest[676:989918] jxcore: stopBroadcasting: success
,ok 57 Should be able to call stopBroadcasting without error

,2016-02-04 15:51:36.029 ThaliTest[676:989918] jxcore: startBroadcasting
,2016-02-04 15:51:36.033 ThaliTest[676:989918] server: starting 1454597496029.676.m1PljA==
,2016-02-04 15:51:36.035 ThaliTest[676:989918] multipeer session: start timer: 0x192924f0
,2016-02-04 15:51:36.040 ThaliTest[676:989918] THEMultipeerSession initialized peer 1454597496029.676
,2016-02-04 15:51:36.042 ThaliTest[676:989918] jxcore: startBroadcasting: success
,ok 58 Should be able to call startBroadcasting without error

,2016-02-04 15:51:36.046 ThaliTest[676:989918] jxcore: stopBroadcasting
,2016-02-04 15:51:36.047 ThaliTest[676:989918] THEMultipeerSession stopping peer
,2016-02-04 15:51:36.048 ThaliTest[676:989918] multipeer session: stop timer
,2016-02-04 15:51:36.053 ThaliTest[676:989918] jxcore: stopBroadcasting: success
,ok 59 Should be able to call stopBroadcasting without error

,2016-02-04 15:51:36.056 ThaliTest[676:989918] jxcore: startBroadcasting
,2016-02-04 15:51:36.059 ThaliTest[676:989918] server: starting 1454597496055.676.gbmtNQ==
,2016-02-04 15:51:36.061 ThaliTest[676:989918] multipeer session: start timer: 0x185ec020
,2016-02-04 15:51:36.067 ThaliTest[676:989918] THEMultipeerSession initialized peer 1454597496055.676
,2016-02-04 15:51:36.069 ThaliTest[676:989918] jxcore: startBroadcasting: success
,ok 60 Should be able to call startBroadcasting without error

,2016-02-04 15:51:36.071 ThaliTest[676:989918] jxcore: stopBroadcasting
,2016-02-04 15:51:36.071 ThaliTest[676:989918] THEMultipeerSession stopping peer
,2016-02-04 15:51:36.072 ThaliTest[676:989918] multipeer session: stop timer
,2016-02-04 15:51:36.074 ThaliTest[676:989918] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error

,2016-02-04 15:51:36.077 ThaliTest[676:989918] jxcore: startBroadcasting
,2016-02-04 15:51:36.079 ThaliTest[676:989918] server: starting 1454597496076.676.NrBfgw==
,2016-02-04 15:51:36.081 ThaliTest[676:989918] multipeer session: start timer: 0x19347ff0
,2016-02-04 15:51:36.084 ThaliTest[676:989918] THEMultipeerSession initialized peer 1454597496076.676
,2016-02-04 15:51:36.085 ThaliTest[676:989918] jxcore: startBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error

,2016-02-04 15:51:36.087 ThaliTest[676:989918] jxcore: stopBroadcasting
,2016-02-04 15:51:36.088 ThaliTest[676:989918] THEMultipeerSession stopping peer
,2016-02-04 15:51:36.088 ThaliTest[676:989918] multipeer session: stop timer
,2016-02-04 15:51:36.091 ThaliTest[676:989918] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error

,2016-02-04 15:51:36.093 ThaliTest[676:989918] jxcore: startBroadcasting
,2016-02-04 15:51:36.095 ThaliTest[676:989918] server: starting 1454597496092.676.RmZ3cA==
,2016-02-04 15:51:36.096 ThaliTest[676:989918] multipeer session: start timer: 0x19281910
,2016-02-04 15:51:36.100 ThaliTest[676:989918] THEMultipeerSession initialized peer 1454597496092.676
,2016-02-04 15:51:36.102 ThaliTest[676:989918] jxcore: startBroadcasting: success
,ok 64 Should be able to call startBroadcasting without error

,2016-02-04 15:51:36.103 ThaliTest[676:989918] jxcore: stopBroadcasting
,2016-02-04 15:51:36.104 ThaliTest[676:989918] THEMultipeerSession stopping peer
,2016-02-04 15:51:36.104 ThaliTest[676:989918] multipeer session: stop timer
,2016-02-04 15:51:36.106 ThaliTest[676:989918] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error

,2016-02-04 15:51:36.109 ThaliTest[676:989918] jxcore: startBroadcasting
,2016-02-04 15:51:36.111 ThaliTest[676:989918] server: starting 1454597496109.676.spzo5w==
,2016-02-04 15:51:36.113 ThaliTest[676:989918] multipeer session: start timer: 0x19281910
,2016-02-04 15:51:36.117 ThaliTest[676:989918] THEMultipeerSession initialized peer 1454597496109.676
,2016-02-04 15:51:36.118 ThaliTest[676:989918] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error

,2016-02-04 15:51:36.121 ThaliTest[676:989918] jxcore: stopBroadcasting
,2016-02-04 15:51:36.122 ThaliTest[676:989918] THEMultipeerSession stopping peer
,2016-02-04 15:51:36.122 ThaliTest[676:989918] multipeer session: stop timer
,2016-02-04 15:51:36.122 ThaliTest[676:989918] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

2016-02-04 15:51:36.125 ThaliTest[676:989918] jxcore: startBroadcasting
,2016-02-04 15:51:36.127 ThaliTest[676:989918] server: starting 1454597496124.676.M/iFmA==
,2016-02-04 15:51:36.128 ThaliTest[676:989918] multipeer session: start timer: 0x192939f0
2016-02-04 15:51:36.129 ThaliTest[676:989918] THEMultipeerSession initialized peer 1454597496124.676
2016-02-04 15:51:36.129 ThaliTest[676:989918] jxcore: startBroad,casting: success
ok 68 Should be able to call startBroadcasting without error

,2016-02-04 15:51:36.130 ThaliTest[676:989918] jxcore: stopBroadcasting
2016-02-04 15:51:36.130 ThaliTest[676:989918] THEMultipeerSession stopping peer
2016-02-04 15:51:36.131 ThaliTest[676:989918] multipeer session: stop timer
2016-02-04 15:51:36.131 ThaliTest[676:989918] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

2016-02-04 15:51:36.133 ThaliTest[676:989918] jxcore: startBroadcasting
,2016-02-04 15:51:36.136 ThaliTest[676:989918] server: starting 1454597496132.676.3OX6CA==
2016-02-04 15:51:36.137 ThaliTest[676:989918] multipeer session: start timer: 0x19294330
2016-02-04 15:51:36.137 ThaliTest[676:989918] THEMultipeerSession initialized peer 1454597496132.676
2016-02-04 15:51:36.137 ThaliTest[676:989918] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

2016-02-04 15:51:36.139 ThaliTest[676:989918] jxcore: stopBroadcasting
2016-02-04 15:51:36.139 ThaliTest[676:989918] THEMultipeerSession stopping peer
2016-02-04 15:51:36.139 ThaliTest[676:989918] multipeer session: stop timer
2016-02-04 15:51:36.140 ThaliTest[676:989918] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

2016-02-04 15:51:36.141 ThaliTest[676:989918] jxcore: startBroadcasting
,2016-02-04 15:51:36.145 ThaliTest[676:989918] server: starting 1454597496141.676.sRh8vA==
2016-02-04 15:51:36.146 ThaliTest[676:989918] multipeer session: start timer: 0x1935b6e0
2016-02-04 15:51:36.146 ThaliTest[676:989918] THEMultipeerSession initialized peer 1454597496141.676
2016-02-04 15:51:36.146 ThaliTest[676:989918] jxcore: startBroadcasting: success
ok 72 Should be able to call startBroadcasting without error

2016-02-04 15:51:36.147 ThaliTest[676:989918] jxcore: stopBroadcasting
2016-02-04 ,15:51:36.148 ThaliTest[676:989918] THEMultipeerSession stopping peer
2016-02-04 15:51:36.148 ThaliTest[676:989918] multipeer session: stop timer
2016-02-04 15:51:36.148 ThaliTest[676:989918] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,got: setup_ThaliEmitter calls startBroadcasting twice with error

,ack: setup_ThaliEmitter calls startBroadcasting twice with error_ok

,# teardown

,2016-02-04 15:51:38.551 ThaliTest[676:989918] jxcore: startBroadcasting
,2016-02-04 15:51:38.555 ThaliTest[676:989918] server: starting 1454597498551.676.70Q+2A==
,2016-02-04 15:51:38.555 ThaliTest[676:989918] multipeer session: start timer: 0x19281a40
,2016-02-04 15:51:38.556 ThaliTest[676:989918] THEMultipeerSession initialized peer 1454597498551.676
2016-02-04 15:51:38.557 ThaliTest[676:989918] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

,2016-02-04 15:51:38.559 ThaliTest[676:989918] jxcore: startBroadcasting
,2016-02-04 15:51:38.560 ThaliTest[676:989918] jxcore: startBroadcasting: failure
,ok 75 Cannot call startBroadcasting twice

,2016-02-04 15:51:38.565 ThaliTest[676:989918] jxcore: stopBroadcasting
2016-02-04 15:51:38.566 ThaliTest[676:989918] THEMultipeerSession stopping peer
2016-02-04 15:51:38.566 ThaliTest[676:989918] multipeer session: stop timer
,2016-02-04 15:51:38.567 ThaliTest[676:989918] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,got: setup_ThaliEmitter throws on connection to bad peer

ack: setup_ThaliEmitter throws on connection to bad peer_ok

,# teardown

,2016-02-04 15:51:39.058 ThaliTest[676:989918] jxcore: startBroadcasting
,2016-02-04 15:51:39.062 ThaliTest[676:989918] server: starting 1454597499057.676.357ifA==
,2016-02-04 15:51:39.062 ThaliTest[676:989918] multipeer session: start timer: 0x19387280
2016-02-04 15:51:39.064 ThaliTest[676:989918] THEMultipeerSession initialized peer 1454597499057.676
,2016-02-04 15:51:39.064 ThaliTest[676:989918] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

,2016-02-04 15:51:39.067 ThaliTest[676:989918] jxcore: connect foobar
2016-02-04 15:51:39.068 ThaliTest[676:989918] client: unknown peer foobar
2016-02-04 15:51:39.068 ThaliTest[676:989918] jxcore: connect: fail: Unknown peer
,ok 78 Should not connect to a bad peer

2016-02-04 15:51:39.074 ThaliTest[676:989918] jxcore: stopBroadcasting
2016-02-04 15:51:39.074 ThaliTest[676:989918] THEMultipeerSession stopping peer
,2016-02-04 15:51:39.074 ThaliTest[676:989918] multipeer session: stop timer
,2016-02-04 15:51:39.075 ThaliTest[676:989918] jxcore: stopBroadcasting: success
,ok 79 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,got: setup_ThaliEmitter throws on disconnect to bad peer

ack: setup_ThaliEmitter throws on disconnect to bad peer_ok

,# teardown

,2016-02-04 15:51:39.934 ThaliTest[676:989918] jxcore: startBroadcasting
,2016-02-04 15:51:39.938 ThaliTest[676:989918] server: starting 1454597499934.676.mVlRsA==
,2016-02-04 15:51:39.939 ThaliTest[676:989918] multipeer session: start timer: 0x19297270
,2016-02-04 15:51:39.939 ThaliTest[676:989918] THEMultipeerSession initialized peer 1454597499934.676
2016-02-04 15:51:39.940 ThaliTest[676:989918] jxcore: startBroadcasting: success
,ok 80 Should be able to call startBroadcasting without error

,2016-02-04 15:51:39.943 ThaliTest[676:989918] jxcore: disconnect
2016-02-04 15:51:39.944 ThaliTest[676:989918] jxcore: disconnect: fail
,ok 81 Disconnect should fail to a non-existant peer 

,2016-02-04 15:51:39.954 ThaliTest[676:989918] jxcore: stopBroadcasting
,2016-02-04 15:51:39.954 ThaliTest[676:989918] THEMultipeerSession stopping peer
,2016-02-04 15:51:39.955 ThaliTest[676:989918] multipeer session: stop timer
,2016-02-04 15:51:39.959 ThaliTest[676:989918] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,got: setup_ThaliEmitter can discover and connect to peers

,ack: setup_ThaliEmitter can discover and connect to peers_ok

,# teardown

,2016-02-04 15:51:40.498 ThaliTest[676:989918] jxcore: startBroadcasting
,2016-02-04 15:51:40.501 ThaliTest[676:989918] server: starting 1454597500498.676.HfYy9g==
,2016-02-04 15:51:40.502 ThaliTest[676:989918] multipeer session: start timer: 0x185886d0
,2016-02-04 15:51:40.503 ThaliTest[676:989918] THEMultipeerSession initialized peer 1454597500498.676
2016-02-04 15:51:40.503 ThaliTest[676:989918] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error

,2016-02-04 15:51:41.350 ThaliTest[676:989664] client: found peer: 1454597497326.1249.RCotcQ==
,2016-02-04 15:51:41.352 ThaliTest[676:989918] jxcore: connect 1454597497326.1249.RCotcQ==
,2016-02-04 15:51:41.353 ThaliTest[676:989918] client session: connect
,2016-02-04 15:51:41.354 ThaliTest[676:989918] client session: stateChange:0->1 1454597497326.1249.RCotcQ==
,2016-02-04 15:51:42.970 ThaliTest[676:989664] multipeer session: reset timer
2016-02-04 15:51:42.970 ThaliTest[676:989664] multipeer session: stop timer
,2016-02-04 15:51:42.971 ThaliTest[676:989664] multipeer session: start timer: 0x185886d0
2016-02-04 15:51:42.971 ThaliTest[676:989664] server session: connect
2016-02-04 15:51:42.971 ThaliTest[676:989664] server session: stateChange:0->1 1454597497326.1249
,2016-02-04 15:51:42.979 ThaliTest[676:989664] server: accepting invitation 1454597497326.1249
,2016-02-04 15:51:44.948 ThaliTest[676:990486] client session: connected
,2016-02-04 15:51:44.948 ThaliTest[676:990486] client session: stateChange:1->2 1454597497326.1249.RCotcQ==
,2016-02-04 15:51:44.970 ThaliTest[676:990490] client session: fireConnectCallback: 1454597497326.1249.RCotcQ==
2016-02-04 15:51:44.970 ThaliTest[676:990490] jxcore: connect: success
,ok 84 Should be able to connect without error

,ok 85 Port should be within range

,2016-02-04 15:51:44.975 ThaliTest[676:989918] jxcore: disconnect
,2016-02-04 15:51:44.975 ThaliTest[676:989918] client session: disconnectFromPeer: 1454597497326.1249.RCotcQ==
,2016-02-04 15:51:44.976 ThaliTest[676:989918] client session: disconnect
2016-02-04 15:51:44.977 ThaliTest[676:989918] client session: stateChange:2->0 1454597497326.1249.RCotcQ==
,2016-02-04 15:51:45.050 ThaliTest[676:989918] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,2016-02-04 15:51:45.422 ThaliTest[676:990490] server session: connected
2016-02-04 15:51:45.423 ThaliTest[676:990490] server session: stateChange:1->2 1454597497326.1249
,2016-02-04 15:51:45.439 ThaliTest[676:989664] server relay: socket disconnected
,2016-02-04 15:51:45.439 ThaliTest[676:989664] server relay: 0x19298b40 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-04 15:51:45.469 ThaliTest[676:990490] server session: not connected 1454597497326.1249
,calling stopBroadcasting

,2016-02-04 15:51:45.809 ThaliTest[676:989918] jxcore: stopBroadcasting
,2016-02-04 15:51:45.810 ThaliTest[676:989918] THEMultipeerSession stopping peer
,2016-02-04 15:51:45.810 ThaliTest[676:989918] multipeer session: stop timer
,2016-02-04 15:51:45.811 ThaliTest[676:989918] server session: disconnect
,2016-02-04 15:51:45.813 ThaliTest[676:989918] server session: stateChange:2->0 1454597497326.1249
,2016-02-04 15:51:46.022 ThaliTest[676:989918] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,
,# ThaliEmitter can discover and connect to peers and then fail on double connect

,got: setup_ThaliEmitter can discover and connect to peers and then fail on double connect

ack: setup_ThaliEmitter can discover and connect to peers and then fail on double connect_ok

,# teardown

,2016-02-04 15:51:46.860 ThaliTest[676:989918] jxcore: startBroadcasting
,2016-02-04 15:51:46.863 ThaliTest[676:989918] server: starting 1454597506859.676.VbGEdw==
,2016-02-04 15:51:46.864 ThaliTest[676:989918] multipeer session: start timer: 0x19769260
2016-02-04 15:51:46.866 ThaliTest[676:989918] THEMultipeerSession initialized peer 1454597506859.676
,2016-02-04 15:51:46.866 ThaliTest[676:989918] jxcore: startBroadcasting: success
,ok 87 Should be able to call startBroadcasting without error

,2016-02-04 15:51:47.032 ThaliTest[676:989664] client: found peer: 1454597497326.1249.RCotcQ==
,2016-02-04 15:51:47.033 ThaliTest[676:989918] jxcore: connect 1454597497326.1249.RCotcQ==
2016-02-04 15:51:47.034 ThaliTest[676:989918] client session: connect
2016-02-04 15:51:47.035 ThaliTest[676:989918] client session: stateChange:0->1 1454597497326.1249.RCotcQ==
,2016-02-04 15:51:48.098 ThaliTest[676:989664] client: found peer: 1454597503653.1249.7uAEDQ==
,2016-02-04 15:51:48.099 ThaliTest[676:989918] jxcore: connect 1454597503653.1249.7uAEDQ==
2016-02-04 15:51:48.100 ThaliTest[676:989918] client session: connect
2016-02-04 15:51:48.100 ThaliTest[676:989918] client session: stateChange:0->1 1454597503653.1249.7uAEDQ==
,2016-02-04 15:51:48.166 ThaliTest[676:989664] multipeer session: reset timer
2016-02-04 15:51:48.167 ThaliTest[676:989664] multipeer session: stop timer
2016-02-04 15:51:48.167 ThaliTest[676:989664] multipeer session: start timer: 0x19769260
,2016-02-04 15:51:48.167 ThaliTest[676:989664] server session: connect
2016-02-04 15:51:48.168 ThaliTest[676:989664] server session: stateChange:0->1 1454597503653.1249
,2016-02-04 15:51:48.176 ThaliTest[676:989664] server: accepting invitation 1454597503653.1249
,2016-02-04 15:51:50.637 ThaliTest[676:990490] client session: connected
2016-02-04 15:51:50.637 ThaliTest[676:990490] client session: stateChange:1->2 1454597503653.1249.7uAEDQ==
,2016-02-04 15:51:50.646 ThaliTest[676:990490] server session: connected
2016-02-04 15:51:50.647 ThaliTest[676:990490] server session: stateChange:1->2 1454597503653.1249
,2016-02-04 15:51:50.655 ThaliTest[676:990486] client session: fireConnectCallback: 1454597503653.1249.7uAEDQ==
2016-02-04 15:51:50.655 ThaliTest[676:990486] jxcore: connect: success
,ok 88 Should be able to connect without error

,ok 89 Port should be within range

,2016-02-04 15:51:50.659 ThaliTest[676:989918] jxcore: connect 1454597503653.1249.7uAEDQ==
,2016-02-04 15:51:50.660 ThaliTest[676:989918] client: already connect(ing/ed) to 1454597503653.1249.7uAEDQ==
,2016-02-04 15:51:50.660 ThaliTest[676:989918] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

,2016-02-04 15:51:50.663 ThaliTest[676:989918] jxcore: disconnect
,2016-02-04 15:51:50.664 ThaliTest[676:989918] client session: disconnectFromPeer: 1454597503653.1249.7uAEDQ==
,2016-02-04 15:51:50.664 ThaliTest[676:989918] client session: disconnect
,2016-02-04 15:51:50.665 ThaliTest[676:989918] client session: stateChange:2->0 1454597503653.1249.7uAEDQ==
,2016-02-04 15:51:50.674 ThaliTest[676:989918] jxcore: disconnect: success
ok 91 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-04 15:51:50.703 ThaliTest[676:989664] server relay: socket disconnected
2016-02-04 15:51:50.703 ThaliTest[676:989664] server relay: 0x195122f0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-04 15:51:50.710 ThaliTest[676:990533] server session: not connected 1454597503653.1249
,calling stopBroadcasting

,2016-02-04 15:51:51.064 ThaliTest[676:989918] jxcore: stopBroadcasting
,2016-02-04 15:51:51.065 ThaliTest[676:989918] THEMultipeerSession stopping peer
,2016-02-04 15:51:51.065 ThaliTest[676:989918] multipeer session: stop timer
,2016-02-04 15:51:51.066 ThaliTest[676:989918] client session: disconnect
2016-02-04 15:51:51.067 ThaliTest[676:989918] client session: stateChange:1->0 1454597497326.1249.RCotcQ==
,2016-02-04 15:51:51.068 ThaliTest[676:989918] server session: disconnect
2016-02-04 15:51:51.069 ThaliTest[676:989918] server session: stateChange:2->0 1454597503653.1249
2016-02-04 15:51:51.070 ThaliTest[676:989918] jxcore: stopBroadcasting: success
st,opBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,got: setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect

ack: setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect_ok

,# teardown

,2016-02-04 15:51:51.585 ThaliTest[676:989918] jxcore: startBroadcasting
,2016-02-04 15:51:51.588 ThaliTest[676:989918] server: starting 1454597511584.676.AhDAFw==
,2016-02-04 15:51:51.589 ThaliTest[676:989918] multipeer session: start timer: 0x19284970
2016-02-04 15:51:51.590 ThaliTest[676:989918] THEMultipeerSession initialized peer 1454597511584.676
2016-02-04 15:51:51.590 ThaliTest[676:989918] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-04 15:51:52.726 ThaliTest[676:989664] client: found peer: 1454597508389.1249.w1EDxA==
,2016-02-04 15:51:52.728 ThaliTest[676:989918] jxcore: connect 1454597508389.1249.w1EDxA==
2016-02-04 15:51:52.729 ThaliTest[676:989918] client session: connect
2016-02-04 15:51:52.729 ThaliTest[676:989918] client session: stateChange:0->1 1454597508389.1249.w1EDxA==
,2016-02-04 15:51:52.829 ThaliTest[676:989664] multipeer session: reset timer
2016-02-04 15:51:52.829 ThaliTest[676:989664] multipeer session: stop timer
2016-02-04 15:51:52.829 ThaliTest[676:989664] multipeer session: start timer: 0x19284970
,2016-02-04 15:51:52.830 ThaliTest[676:989664] server session: connect
2016-02-04 15:51:52.830 ThaliTest[676:989664] server session: stateChange:0->1 1454597508389.1249
,2016-02-04 15:51:52.836 ThaliTest[676:989664] server: accepting invitation 1454597508389.1249
,2016-02-04 15:51:55.371 ThaliTest[676:990486] server session: connected
2016-02-04 15:51:55.372 ThaliTest[676:990486] server session: stateChange:1->2 1454597508389.1249
,2016-02-04 15:51:55.378 ThaliTest[676:989664] server relay: socket disconnected
,2016-02-04 15:51:55.379 ThaliTest[676:989664] server relay: 0x19722870 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-04 15:51:55.434 ThaliTest[676:990484] server session: not connected 1454597508389.1249
,2016-02-04 15:51:55.639 ThaliTest[676:990484] client session: connected
2016-02-04 15:51:55.640 ThaliTest[676:990484] client session: stateChange:1->2 1454597508389.1249.w1EDxA==
,2016-02-04 15:51:55.654 ThaliTest[676:990486] client session: fireConnectCallback: 1454597508389.1249.w1EDxA==
2016-02-04 15:51:55.654 ThaliTest[676:990486] jxcore: connect: success
,ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-04 15:51:55.658 ThaliTest[676:989918] jxcore: disconnect
,2016-02-04 15:51:55.659 ThaliTest[676:989918] client session: disconnectFromPeer: 1454597508389.1249.w1EDxA==
2016-02-04 15:51:55.659 ThaliTest[676:989918] client session: disconnect
2016-02-04 15:51:55.660 ThaliTest[676:989918] client session: stateChange:2->0 1454597508389.1249.w1EDxA==
,2016-02-04 15:51:55.730 ThaliTest[676:989918] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error

,2016-02-04 15:51:55.732 ThaliTest[676:989918] jxcore: disconnect
,2016-02-04 15:51:55.733 ThaliTest[676:989918] jxcore: disconnect: fail
,ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-04 15:51:55.774 ThaliTest[676:989918] jxcore: stopBroadcasting
,2016-02-04 15:51:55.774 ThaliTest[676:989918] THEMultipeerSession stopping peer
,2016-02-04 15:51:55.775 ThaliTest[676:989918] multipeer session: stop timer
,2016-02-04 15:51:55.776 ThaliTest[676:989918] server session: disconnect
2016-02-04 15:51:55.777 ThaliTest[676:989918] server session: stateChange:2->0 1454597508389.1249
2016-02-04 15:51:55.779 ThaliTest[676:989918] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,got: setup_ThaliEmitter can connect and send data

ack: setup_ThaliEmitter can connect and send data_ok

,# teardown

,echo server started on port: 53404

,2016-02-04 15:51:56.803 ThaliTest[676:989918] jxcore: startBroadcasting
,2016-02-04 15:51:56.805 ThaliTest[676:989918] server: starting 1454597516803.676.tCIDsA==
,2016-02-04 15:51:56.805 ThaliTest[676:989918] multipeer session: start timer: 0x1939a2f0
2016-02-04 15:51:56.805 ThaliTest[676:989918] THEMultipeerSession initialized peer 1454597516803.676
2016-02-04 15:51:56.805 ThaliTest[676:989918] jxcore: startBroadcasting: success
ok 97 Should be able to call startBroadcasting without error

,2016-02-04 15:51:57.007 ThaliTest[676:989664] client: found peer: 1454597508389.1249.w1EDxA==
,2016-02-04 15:51:57.007 ThaliTest[676:989918] jxcore: connect 1454597508389.1249.w1EDxA==
2016-02-04 15:51:57.007 ThaliTest[676:989918] client session: connect
2016-02-04 15:51:57.008 ThaliTest[676:989918] client session: stateChange:0->1 1454597508389.1249.w1EDxA==
,2016-02-04 15:51:57.602 ThaliTest[676:989664] client: found peer: 1454597513456.1249.aLHd3A==
,2016-02-04 15:51:57.603 ThaliTest[676:989918] jxcore: connect 1454597513456.1249.aLHd3A==
2016-02-04 15:51:57.604 ThaliTest[676:989918] client session: connect
2016-02-04 15:51:57.604 ThaliTest[676:989918] client session: stateChange:0->1 1454597513456.1249.aLHd3A==
,2016-02-04 15:51:58.132 ThaliTest[676:989664] multipeer session: reset timer
2016-02-04 15:51:58.133 ThaliTest[676:989664] multipeer session: stop timer
2016-02-04 15:51:58.133 ThaliTest[676:989664] multipeer session: start timer: 0x1939a2f0
2016-02-04 ,15:51:58.133 ThaliTest[676:989664] server session: connect
2016-02-04 15:51:58.133 ThaliTest[676:989664] server session: stateChange:0->1 1454597513456.1249
,2016-02-04 15:51:58.139 ThaliTest[676:989664] server: accepting invitation 1454597513456.1249
,2016-02-04 15:52:00.363 ThaliTest[676:990571] client session: connected
,2016-02-04 15:52:00.364 ThaliTest[676:990571] client session: stateChange:1->2 1454597513456.1249.aLHd3A==
,2016-02-04 15:52:00.367 ThaliTest[676:990571] client session: fireConnectCallback: 1454597513456.1249.aLHd3A==
2016-02-04 15:52:00.367 ThaliTest[676:990571] jxcore: connect: success
,ok 98 Should be able to connect without error

,ok 99 Port should be within range

,2016-02-04 15:52:00.373 ThaliTest[676:989664] client: relay established
2016-02-04 15:52:00.373 ThaliTest[676:989664] client: new accepted socket: 0x19734ea0
,data in 25185

,data in 32850

,data in 36135

,data in 41610

,data in 55632

,data in 61320

,data in 75555

,data in 87600

,data in 91980

,data in 95265

,data in 100740

,data in 117165

,data in 131072

,ok 100 the test messages should be equal

,2016-02-04 15:52:00.664 ThaliTest[676:989918] jxcore: disconnect
2016-02-04 15:52:00.664 ThaliTest[676:989918] client session: disconnectFromPeer: 1454597513456.1249.aLHd3A==
2016-02-04 15:52:00.664 ThaliTest[676:989918] client session: disconnect
2016-02-04 15:52:00.664 ThaliTest[676:989918] client session: stateChange:2->0 1454597513456.1249.aLHd3A==
,2016-02-04 15:52:00.675 ThaliTest[676:989918] jxcore: disconnect: success
ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-04 15:52:00.707 ThaliTest[676:990490] server session: connected
,2016-02-04 15:52:00.707 ThaliTest[676:990490] server session: stateChange:1->2 1454597513456.1249
,2016-02-04 15:52:00.746 ThaliTest[676:989664] server relay: connected (to port: 53404)
,2016-02-04 15:52:01.062 ThaliTest[676:990571] server session: not connected 1454597513456.1249
,calling stopBroadcasting

,2016-02-04 15:52:01.104 ThaliTest[676:989918] jxcore: stopBroadcasting
,2016-02-04 15:52:01.104 ThaliTest[676:989918] THEMultipeerSession stopping peer
2016-02-04 15:52:01.105 ThaliTest[676:989918] multipeer session: stop timer
,2016-02-04 15:52:01.106 ThaliTest[676:989918] client session: disconnect
2016-02-04 15:52:01.106 ThaliTest[676:989918] client session: stateChange:1->0 1454597508389.1249.w1EDxA==
,2016-02-04 15:52:01.107 ThaliTest[676:989918] server session: disconnect
2016-02-04 15:52:01.108 ThaliTest[676:989918] server session: stateChange:2->0 1454597513456.1249
,2016-02-04 15:52:01.115 ThaliTest[676:989918] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,got: setup_ThaliEmitter handles socket disconnect correctly

ack: setup_ThaliEmitter handles socket disconnect correctly_ok

,# teardown

,echo server started on port: 53411

,2016-02-04 15:52:01.598 ThaliTest[676:989918] jxcore: startBroadcasting
,2016-02-04 15:52:01.601 ThaliTest[676:989918] server: starting 1454597521597.676.0LsCjw==
,2016-02-04 15:52:01.602 ThaliTest[676:989918] multipeer session: start timer: 0x1928d640
,2016-02-04 15:52:01.603 ThaliTest[676:989918] THEMultipeerSession initialized peer 1454597521597.676
2016-02-04 15:52:01.603 ThaliTest[676:989918] jxcore: startBroadcasting: success
,ok 102 Should be able to call startBroadcasting without error

,2016-02-04 15:52:02.436 ThaliTest[676:989664] client: found peer: 1454597513456.1249.aLHd3A==
,[{"peerIdentifier":"1454597513456.1249.aLHd3A==","peerName":"(null)","peerAvailable":true}]

,2016-02-04 15:52:02.439 ThaliTest[676:989918] jxcore: connect 1454597513456.1249.aLHd3A==
,2016-02-04 15:52:02.439 ThaliTest[676:989918] client session: connect
,2016-02-04 15:52:02.440 ThaliTest[676:989918] client session: stateChange:0->1 1454597513456.1249.aLHd3A==
,2016-02-04 15:52:02.881 ThaliTest[676:989664] client: lost peer: 1454597513456.1249.aLHd3A==
2016-02-04 15:52:02.881 ThaliTest[676:989664] client session: onPeerLost: 1454597513456.1249.aLHd3A==
2016-02-04 15:52:02.881 ThaliTest[676:989664] client sessio,n: onLinkFailure: 1454597513456.1249.aLHd3A==
,2016-02-04 15:52:02.882 ThaliTest[676:989664] client session: disconnect
2016-02-04 15:52:02.884 ThaliTest[676:989664] client session: stateChange:1->0 1454597513456.1249.aLHd3A==
,2016-02-04 15:52:02.884 ThaliTest[676:989664] client session: fireConnectCallback: 1454597513456.1249.aLHd3A==
2016-02-04 15:52:02.885 ThaliTest[676:989664] jxcore: connect: fail: Peer disconnected
,2016-02-04 15:52:02.885 ThaliTest[676:989664] client: found peer: 1454597518408.1249.VlewzQ==
,[{"peerIdentifier":"1454597513456.1249.aLHd3A==","peerName":"(null)","peerAvailable":false}]

[{"peerIdentifier":"1454597518408.1249.VlewzQ==","peerName":"(null)","peerAvailable":true}]

,2016-02-04 15:52:02.891 ThaliTest[676:989918] jxcore: connect 1454597518408.1249.VlewzQ==
2016-02-04 15:52:02.892 ThaliTest[676:989918] client session: connect
2016-02-04 15:52:02.892 ThaliTest[676:989918] client session: stateChange:0->1 1454597518408.1,249.VlewzQ==
,2016-02-04 15:52:02.897 ThaliTest[676:989664] multipeer session: reset timer
2016-02-04 15:52:02.897 ThaliTest[676:989664] multipeer session: stop timer
2016-02-04 15:52:02.897 ThaliTest[676:989664] multipeer session: start timer: 0x1928d640
2016-02-04 15:52:02.898 ThaliTest[676:989664] server session: connect
,2016-02-04 15:52:02.898 ThaliTest[676:989664] server session: stateChange:0->1 1454597518408.1249
,2016-02-04 15:52:02.907 ThaliTest[676:989664] server: accepting invitation 1454597518408.1249
,2016-02-04 15:52:03.899 ThaliTest[676:989918] jxcore: connect 1454597513456.1249.aLHd3A==
2016-02-04 15:52:03.900 ThaliTest[676:989918] client: connect: unreachable 1454597513456.1249.aLHd3A==
,2016-02-04 15:52:03.900 ThaliTest[676:989918] jxcore: connect: fail: Peer unreachable
,2016-02-04 15:52:07.456 ThaliTest[676:990571] server session: connected
2016-02-04 15:52:07.456 ThaliTest[676:990571] server session: stateChange:1->2 1454597518408.1249
,2016-02-04 15:52:07.464 ThaliTest[676:989664] server relay: connected (to port: 53411)
,2016-02-04 15:52:07.571 ThaliTest[676:990571] client session: connected
,2016-02-04 15:52:07.572 ThaliTest[676:990571] client session: stateChange:1->2 1454597518408.1249.VlewzQ==
,2016-02-04 15:52:07.577 ThaliTest[676:990486] client session: fireConnectCallback: 1454597518408.1249.VlewzQ==
2016-02-04 15:52:07.578 ThaliTest[676:990486] jxcore: connect: success
,ok 103 Should be able to connect without error

,ok 104 Port should be within range

,ok 105 First connect should succeed

,2016-02-04 15:52:07.612 ThaliTest[676:989664] client: relay established
2016-02-04 15:52:07.612 ThaliTest[676:989664] client: new accepted socket: 0x195f2920
,2016-02-04 15:52:08.533 ThaliTest[676:989664] multipeer session: reset timer
2016-02-04 15:52:08.533 ThaliTest[676:989664] multipeer session: stop timer
,2016-02-04 15:52:08.534 ThaliTest[676:989664] multipeer session: start timer: 0x1928d640
2016-02-04 15:52:08.534 ThaliTest[676:989664] server: disconnecting to refresh session (1454597518408.1249)
2016-02-04 15:52:08.534 ThaliTest[676:989664] server sess,ion: disconnect
2016-02-04 15:52:08.535 ThaliTest[676:989664] server session: stateChange:2->0 1454597518408.1249
,2016-02-04 15:52:08.548 ThaliTest[676:989664] server session: connect
2016-02-04 15:52:08.549 ThaliTest[676:989664] server session: stateChange:0->1 1454597518408.1249
,2016-02-04 15:52:08.560 ThaliTest[676:989664] server: accepting invitation 1454597518408.1249
,2016-02-04 15:52:08.827 ThaliTest[676:990486] server session: not connected 1454597518408.1249
,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-02-04 15:52:09.296 ThaliTest[676:989664] client: socket closed
,2016-02-04 15:52:09.296 ThaliTest[676:989664] client relay: socket disconnected
,2016-02-04 15:52:09.297 ThaliTest[676:989664] client relay: 0x195f2920 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-04 15:52:09.297 ThaliTest[676:989664] client session: socket closed: 1454597518408.1249.VlewzQ==
,2016-02-04 15:52:09.297 ThaliTest[676:989664] client session: onLinkFailure: 1454597518408.1249.VlewzQ==
2016-02-04 15:52:09.298 ThaliTest[676:989664] client session: disconnect
2016-02-04 15:52:09.298 ThaliTest[676:989664] client session: stateChange:2->0 1454597518408.1249.VlewzQ==
,2016-02-04 15:52:09.309 ThaliTest[676:989664] client session: fireConnectionErrorEvent: 1454597518408.1249.VlewzQ==
,2016-02-04 15:52:09.315 ThaliTest[676:989918] jxcore: connect 1454597518408.1249.VlewzQ==
2016-02-04 15:52:09.316 ThaliTest[676:989918] client session: connect
2016-02-04 15:52:09.316 ThaliTest[676:989918] client session: stateChange:0->1 1454597518408.1249.VlewzQ==
,2016-02-04 15:52:11.845 ThaliTest[676:990484] client session: connected
2016-02-04 15:52:11.846 ThaliTest[676:990484] client session: stateChange:1->2 1454597518408.1249.VlewzQ==
,2016-02-04 15:52:12.270 ThaliTest[676:990484] client session: fireConnectCallback: 1454597518408.1249.VlewzQ==
2016-02-04 15:52:12.270 ThaliTest[676:990484] jxcore: connect: success
,ok 108 Should be able to connect without error

,ok 109 Port should be within range

,ok 110 Second connect should succeed

,2016-02-04 15:52:12.305 ThaliTest[676:989664] client: relay established
2016-02-04 15:52:12.306 ThaliTest[676:989664] client: new accepted socket: 0x167844b0
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-02-04 15:52:12.365 ThaliTest[676:989664] client: socket closed
,2016-02-04 15:52:12.366 ThaliTest[676:989664] client relay: socket disconnected
,2016-02-04 15:52:12.366 ThaliTest[676:989664] client relay: 0x167844b0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-04 15:52:12.366 ThaliTest[676:989664] client session: socket closed: 1454597518408.1249.VlewzQ==
,2016-02-04 15:52:12.367 ThaliTest[676:989664] client session: onLinkFailure: 1454597518408.1249.VlewzQ==
2016-02-04 15:52:12.367 ThaliTest[676:989664] client session: disconnect
2016-02-04 15:52:12.367 ThaliTest[676:989664] client session: stateChange:2-,>0 1454597518408.1249.VlewzQ==
,2016-02-04 15:52:12.378 ThaliTest[676:989664] client session: fireConnectionErrorEvent: 1454597518408.1249.VlewzQ==
,2016-02-04 15:52:22.348 ThaliTest[676:989664] multipeer session: reset timer
2016-02-04 15:52:22.348 ThaliTest[676:989664] multipeer session: stop timer
,2016-02-04 15:52:22.348 ThaliTest[676:989664] multipeer session: start timer: 0x1928d640
,2016-02-04 15:52:22.349 ThaliTest[676:989664] server: disconnecting to refresh session (1454597518408.1249)
2016-02-04 15:52:22.349 ThaliTest[676:989664] server session: disconnect
,2016-02-04 15:52:22.350 ThaliTest[676:989664] server session: stateChange:1->0 1454597518408.1249
,2016-02-04 15:52:22.404 ThaliTest[676:989664] server session: connect
2016-02-04 15:52:22.405 ThaliTest[676:989664] server session: stateChange:0->1 1454597518408.1249
,2016-02-04 15:52:22.412 ThaliTest[676:989664] server: accepting invitation 1454597518408.1249
,2016-02-04 15:52:23.489 ThaliTest[676:990685] server session: connected
,2016-02-04 15:52:23.489 ThaliTest[676:990685] server session: stateChange:1->2 1454597518408.1249
,2016-02-04 15:52:23.559 ThaliTest[676:989664] server relay: connected (to port: 53411)
,calling stopBroadcasting

,2016-02-04 15:52:24.086 ThaliTest[676:989918] jxcore: stopBroadcasting
,2016-02-04 15:52:24.086 ThaliTest[676:989918] THEMultipeerSession stopping peer
,2016-02-04 15:52:24.087 ThaliTest[676:989918] multipeer session: stop timer
,2016-02-04 15:52:24.088 ThaliTest[676:989918] server session: disconnect
2016-02-04 15:52:24.088 ThaliTest[676:989918] server session: stateChange:2->0 1454597518408.1249
,2016-02-04 15:52:24.112 ThaliTest[676:989918] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,got: setup_ThaliReplicationManager can call start without error

ack: setup_ThaliReplicationManager can call start without error_ok

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/BAE148A8-0BBF-46CC-84C0-375B192ABBC4/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-02-04 15:52:24.581 ThaliTest[676:989918] jxcore: startBroadcasting
,2016-02-04 15:52:24.582 ThaliTest[676:989918] server: starting vlAFZKiNNOMCwc-IYmCk_g.yKvuAA==
,2016-02-04 15:52:24.583 ThaliTest[676:989918] multipeer session: start timer: 0x1964bb80
2016-02-04 15:52:24.583 ThaliTest[676:989918] THEMultipeerSession initialized peer vlAFZKiNNOMCwc-IYmCk_g
2016-02-04 15:52:24.583 ThaliTest[676:989918] jxcore: startBroadcasting: success
,ok 114 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

,ok 115 stopping event should occur in right order

About to call stopBroadcasting

2016-02-04 15:52:24.585 ThaliTest[676:989918] jxcore: stopBroadcasting
2016-02-04 15:52:24.585 ThaliTest[676:989918] THEMultipeerSession stopping peer
2016-02-04 15:52:24.585 ThaliTest[676:989918] multipeer session: stop timer
2016-02-04 15:52:24.585 ThaliTest[676:989918] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,ok 116 stopped event should occur in right order

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager receives identity

,got: setup_ThaliReplicationManager receives identity

ack: setup_ThaliReplicationManager receives identity_ok

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/BAE148A8-0BBF-46CC-84C0-375B192ABBC4/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-04 15:52:25.105 ThaliTest[676:989918] jxcore: startBroadcasting
,2016-02-04 15:52:25.108 ThaliTest[676:989918] server: starting vlAFZKiNNOMCwc-IYmCk_g.I1v29Q==
,2016-02-04 15:52:25.109 ThaliTest[676:989918] multipeer session: start timer: 0x192a0da0
2016-02-04 15:52:25.110 ThaliTest[676:989918] THEMultipeerSession initialized peer vlAFZKiNNOMCwc-IYmCk_g
2016-02-04 15:52:25.110 ThaliTest[676:989918] jxcore: startBroadcasting: success
,ok 117 getDeviceIdentity should not return an error

,ok 118 deviceName should not be null

Now in TRM stop

State of this._isStarted: true

,About to call stopBroadcasting
,
,2016-02-04 15:52:25.115 ThaliTest[676:989918] jxcore: stopBroadcasting
2016-02-04 15:52:25.115 ThaliTest[676:989918] THEMultipeerSession stopping peer
2016-02-04 15:52:25.116 ThaliTest[676:989918] multipeer session: stop timer
2016-02-04 15:52:25.116 ThaliTest[676:989918] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager replicates database

,got: setup_ThaliReplicationManager replicates database

ack: setup_ThaliReplicationManager replicates database_ok

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/BAE148A8-0BBF-46CC-84C0-375B192ABBC4/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-04 15:52:27.763 ThaliTest[676:989918] jxcore: startBroadcasting
,2016-02-04 15:52:27.764 ThaliTest[676:989918] server: starting vlAFZKiNNOMCwc-IYmCk_g.b0VzbQ==
,2016-02-04 15:52:27.765 ThaliTest[676:989918] multipeer session: start timer: 0x192ea700
2016-02-04 15:52:27.765 ThaliTest[676:989918] THEMultipeerSession initialized peer vlAFZKiNNOMCwc-IYmCk_g
2016-02-04 15:52:27.765 ThaliTest[676:989918] jxcore: startBroadcasting: success
,ok 119 getDeviceIdentity should not return an error

ok 120 deviceName should not be null

,2016-02-04 15:52:27.771 ThaliTest[676:989664] client: found peer: 1454597518408.1249.VlewzQ==
,2016-02-04 15:52:31.815 ThaliTest[676:989664] client: found peer: iJ73fAElE3Jb_XissQ1iBQ.Pzo0yw==
,2016-02-04 15:52:31.843 ThaliTest[676:989918] jxcore: connect 1454597518408.1249.VlewzQ==
2016-02-04 15:52:31.843 ThaliTest[676:989918] client session: connect
,2016-02-04 15:52:31.843 ThaliTest[676:989918] client session: stateChange:0->1 1454597518408.1249.VlewzQ==
,2016-02-04 15:52:31.846 ThaliTest[676:989918] jxcore: connect iJ73fAElE3Jb_XissQ1iBQ.Pzo0yw==
2016-02-04 15:52:31.846 ThaliTest[676:989918] client session: connect
2016-02-04 15:52:31.846 ThaliTest[676:989918] client session: stateChange:0->1 iJ73fAElE3J,b_XissQ1iBQ.Pzo0yw==
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-02-04 15:52:32.665 ThaliTest[676:989664] multipeer session: reset timer
2016-02-04 15:52:32.665 ThaliTest[676:989664] multipeer session: stop timer
2016-02-04 15:52:32.665 ThaliTest[676:989664] multipeer session: start timer: 0x192ea700
2016-02-04 ,15:52:32.666 ThaliTest[676:989664] server session: connect
2016-02-04 15:52:32.666 ThaliTest[676:989664] server session: stateChange:0->1 iJ73fAElE3Jb_XissQ1iBQ
,2016-02-04 15:52:32.673 ThaliTest[676:989664] server: accepting invitation iJ73fAElE3Jb_XissQ1iBQ
,2016-02-04 15:52:35.717 ThaliTest[676:990711] server session: connected
2016-02-04 15:52:35.717 ThaliTest[676:990711] server session: stateChange:1->2 iJ73fAElE3Jb_XissQ1iBQ
,2016-02-04 15:52:35.742 ThaliTest[676:989664] server relay: connected (to port: 53429)
,server bridge: new client socket

,2016-02-04 15:52:37.858 ThaliTest[676:990711] client session: connected
2016-02-04 15:52:37.858 ThaliTest[676:990711] client session: stateChange:1->2 iJ73fAElE3Jb_XissQ1iBQ.Pzo0yw==
,2016-02-04 15:52:37.884 ThaliTest[676:990484] client session: fireConnectCallback: iJ73fAElE3Jb_XissQ1iBQ.Pzo0yw==
2016-02-04 15:52:37.884 ThaliTest[676:990484] jxcore: connect: success
,2016-02-04 15:52:38.002 ThaliTest[676:989664] client: relay established
2016-02-04 15:52:38.002 ThaliTest[676:989664] client: new accepted socket: 0x1677a210
,client bridge: new client socket

,client bridge: new client socket

,ok 123 1st change of remote doc should contain remote id

,ok 124 Can update remote doc without error

,null

,{ ok: true,
  id: '61f07a27-dddb-4fd2-96e5-20a5c9df28cc',
  rev: '2-1672e812a360f5d5036b02fc3e9e30d4' }

,ok 125 Remote changes occur in strict order

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket
,
,client bridge: new client socket

,client bridge: socket closed
,
,2016-02-04 15:52:43.778 ThaliTest[676:989664] client: lost peer: 1454597518408.1249.VlewzQ==
2016-02-04 15:52:43.779 ThaliTest[676:989664] client session: onPeerLost: 1454597518408.1249.VlewzQ==
2016-02-04 15:52:43.779 ThaliTest[676:989664] client sessio,n: onLinkFailure: 1454597518408.1249.VlewzQ==
2016-02-04 15:52:43.779 ThaliTest[676:989664] client session: disconnect
2016-02-04 15:52:43.780 ThaliTest[676:989664] client session: stateChange:1->0 1454597518408.1249.VlewzQ==
,2016-02-04 15:52:43.780 ThaliTest[676:989664] client session: fireConnectCallback: 1454597518408.1249.VlewzQ==
2016-02-04 15:52:43.781 ThaliTest[676:989664] jxcore: connect: fail: Peer disconnected
,client bridge: new client socket
,
,Connect error with error: Error: Peer disconnected

,2016-02-04 15:52:43.838 ThaliTest[676:989918] jxcore: disconnect
,2016-02-04 15:52:43.838 ThaliTest[676:989918] jxcore: disconnect: fail
,Disconnect error with error: Error: Not connected to specified peer

peerIdentifier not available 1454597518408.1249.VlewzQ==

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,ok 126 Local changes occur in strict order

,ok 127 2nd change of local doc should contain remote id

,# setup

,client bridge: new client socket

,Now in TRM stop

,State of this._isStarted: true

About to call stopBroadcasting

,2016-02-04 15:52:47.210 ThaliTest[676:989918] jxcore: stopBroadcasting
,2016-02-04 15:52:47.210 ThaliTest[676:989918] THEMultipeerSession stopping peer
,2016-02-04 15:52:47.210 ThaliTest[676:989918] multipeer session: stop timer
,2016-02-04 15:52:47.211 ThaliTest[676:989918] client session: disconnect
,2016-02-04 15:52:47.211 ThaliTest[676:989918] client session: stateChange:2->0 iJ73fAElE3Jb_XissQ1iBQ.Pzo0yw==
,2016-02-04 15:52:47.217 ThaliTest[676:989918] server session: disconnect
2016-02-04 15:52:47.217 ThaliTest[676:989918] server session: stateChange:2->0 iJ73fAElE3Jb_XissQ1iBQ
,2016-02-04 15:52:47.229 ThaliTest[676:989918] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,client bridge: socket closed

,mux server bridge listener closed

,server bridge: socket closed

,client bridge: socket closed

,client bridge: socket closed


```
