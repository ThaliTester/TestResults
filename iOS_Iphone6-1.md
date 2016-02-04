#### Test 58135655a1ee273_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58135655a1ee273/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/F1732C52-D3EE-40AC-B83A-030C6308C7D0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F1732C52-D3EE-40AC-B83A-030C6308C7D0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58135655a1ee273/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58135655a1ee273/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/202CC7EE-8B44-4774-844B-5661ADA08945/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50338"
,(lldb)     command script import "/tmp/F1732C52-D3EE-40AC-B83A-030C6308C7D0/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-04 15:45:27.288 ThaliTest[1249:2206144] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D94046F5-9391-4957-8852-0FFC94D1E28A/Library/Cookies/Cookies.binarycookies
,2016-02-04 15:45:27.657 ThaliTest[1249:2206144] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-04 15:45:27.659 ThaliTest[1249:2206144] Multi-tasking -> Device: YES, App: YES
,2016-02-04 15:45:27.668 ThaliTest[1249:2206144] Unlimited access to network resources
,2016-02-04 15:45:27.680 ThaliTest[1249:2206144] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-04 15:45:37.495 ThaliTest[1249:2206144] Resetting plugins due to page load.
,2016-02-04 15:45:40.865 ThaliTest[1249:2206144] Finished load of: file:///var/mobile/Containers/Bundle/Application/202CC7EE-8B44-4774-844B-5661ADA08945/ThaliTest.app/www/index.html
,2016-02-04 15:45:40.883 ThaliTest[1249:2206144] JXcore Cordova plugin initializing
2016-02-04 15:45:40.885 ThaliTest[1249:2206487] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!
,
,JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/202CC7EE-8B44-4774-844B-5661ADA08945/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/202CC7EE-8B44-4774-844B-5661ADA08945/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/202CC7EE-8B44-4774-844B-5661ADA08945/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/202CC7EE-8B44-4774-844B-5661ADA08945/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/202CC7EE-8B44-4774-844B-5661ADA08945/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/202CC7EE-8B44-4774-844B-5661ADA08945/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/202CC7EE-8B44-4774-844B-5661ADA08945/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/202CC7EE-8B44-4774-844B-5661ADA08945/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,ack: setup_basic_ok

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

,ack: setup_successfully create a new pkcs12 file and return hash value_ok

,# teardown

,ok 13 should be equal

,ok 14 null

,ok 15 (unnamed assert)

,ok 16 should be equal

,ok 17 should not throw

,# setup

,# successfully read a previous pkcs12 file and return hash value

,got: setup_successfully read a previous pkcs12 file and return hash value

,ack: setup_successfully read a previous pkcs12 file and return hash value_ok

,# teardown

,ok 18 (unnamed assert)

,ok 19 (unnamed assert)

,ok 20 should not throw

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

,ack: setup_failed to get mobile documents path_ok

,# teardown

,ok 24 should be equal

,# setup

,# #init should register the peerAvailabilityChanged event

,got: setup_#init should register the peerAvailabilityChanged event

ack: setup_#init should register the peerAvailabilityChanged event_ok

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

ack: setup_#startBroadcasting should throw on non-number port_ok

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

ack: setup_#startBroadcasting should throw on negative port_ok

,# teardown

,ok 33 should throw

,# setup

,# #startBroadcasting should throw on too large port

,got: setup_#startBroadcasting should throw on too large port

,ack: setup_#startBroadcasting should throw on too large port_ok

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

ack: setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error_ok

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

ack: setup_#connect should call Mobile("Connect") with a port and without an error_ok

,# teardown

,ok 45 should be equal

,ok 46 should be equal

,ok 47 should be equal

,# setup

,# #connect should call Mobile("Connect") and handle an error

,got: setup_#connect should call Mobile("Connect") and handle an error

,ack: setup_#connect should call Mobile("Connect") and handle an error_ok

,# teardown

,ok 48 should be equal

,ok 49 should be equal

,# setup

,# should call Mobile("Disconnect") without an error

,got: setup_should call Mobile("Disconnect") without an error

,ack: setup_should call Mobile("Disconnect") without an error_ok

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

ack: setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error_ok

,# teardown

,2016-02-04 15:51:32.016 ThaliTest[1249:2206487] jxcore: startBroadcasting
,2016-02-04 15:51:32.032 ThaliTest[1249:2206487] server: starting 1454597492015.1249.bXggKA==
,2016-02-04 15:51:32.033 ThaliTest[1249:2206487] multipeer session: start timer: 0x1a37ee20
2016-02-04 15:51:32.034 ThaliTest[1249:2206487] THEMultipeerSession initialized peer 1454597492015.1249
2016-02-04 15:51:32.035 ThaliTest[1249:2206487] jxcore: startBroadcasting: success
ok 54 Should be able to call startBroadcasting without error

,2016-02-04 15:51:32.038 ThaliTest[1249:2206487] jxcore: stopBroadcasting
2016-02-04 15:51:32.038 ThaliTest[1249:2206487] THEMultipeerSession stopping peer
2016-02-04 15:51:32.038 ThaliTest[1249:2206487] multipeer session: stop timer
2016-02-04 15:51:32.,041 ThaliTest[1249:2206487] jxcore: stopBroadcasting: success
ok 55 Should be able to call stopBroadcasting without error

2016-02-04 15:51:32.043 ThaliTest[1249:2206487] jxcore: startBroadcasting
,2016-02-04 15:51:32.047 ThaliTest[1249:2206487] server: starting 1454597492043.1249.SDfmgQ==
2016-02-04 15:51:32.048 ThaliTest[1249:2206487] multipeer session: start timer: 0x1a381920
2016-02-04 15:51:32.048 ThaliTest[1249:2206487] THEMultipeerSession initialized peer 1454597492043.1249
,2016-02-04 15:51:32.049 ThaliTest[1249:2206487] jxcore: startBroadcasting: success
ok 56 Should be able to call startBroadcasting without error

,2016-02-04 15:51:32.059 ThaliTest[1249:2206487] jxcore: stopBroadcasting
2016-02-04 15:51:32.060 ThaliTest[1249:2206487] THEMultipeerSession stopping peer
2016-02-04 15:51:32.060 ThaliTest[1249:2206487] multipeer session: stop timer
2016-02-04 15:51:32.061 ThaliTest[1249:2206487] jxcore: stopBroadcasting: success
ok 57 Should be able to call stopBroadcasting without error

,2016-02-04 15:51:32.063 ThaliTest[1249:2206487] jxcore: startBroadcasting
,2016-02-04 15:51:32.077 ThaliTest[1249:2206487] server: starting 1454597492062.1249.tvn+9g==
,2016-02-04 15:51:32.081 ThaliTest[1249:2206487] multipeer session: start timer: 0x19514cf0
,2016-02-04 15:51:32.088 ThaliTest[1249:2206487] THEMultipeerSession initialized peer 1454597492062.1249
,2016-02-04 15:51:32.090 ThaliTest[1249:2206487] jxcore: startBroadcasting: success
,ok 58 Should be able to call startBroadcasting without error
,
,2016-02-04 15:51:32.094 ThaliTest[1249:2206487] jxcore: stopBroadcasting
,2016-02-04 15:51:32.095 ThaliTest[1249:2206487] THEMultipeerSession stopping peer
,2016-02-04 15:51:32.096 ThaliTest[1249:2206487] multipeer session: stop timer
,2016-02-04 15:51:32.103 ThaliTest[1249:2206487] jxcore: stopBroadcasting: success
,ok 59 Should be able to call stopBroadcasting without error

,2016-02-04 15:51:32.106 ThaliTest[1249:2206487] jxcore: startBroadcasting
,2016-02-04 15:51:32.110 ThaliTest[1249:2206487] server: starting 1454597492106.1249.OXFdDw==
,2016-02-04 15:51:32.114 ThaliTest[1249:2206487] multipeer session: start timer: 0x1a381ca0
,2016-02-04 15:51:32.119 ThaliTest[1249:2206487] THEMultipeerSession initialized peer 1454597492106.1249
,2016-02-04 15:51:32.122 ThaliTest[1249:2206487] jxcore: startBroadcasting: success
,ok 60 Should be able to call startBroadcasting without error

,2016-02-04 15:51:32.124 ThaliTest[1249:2206487] jxcore: stopBroadcasting
,2016-02-04 15:51:32.125 ThaliTest[1249:2206487] THEMultipeerSession stopping peer
,2016-02-04 15:51:32.126 ThaliTest[1249:2206487] multipeer session: stop timer
,2016-02-04 15:51:32.130 ThaliTest[1249:2206487] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error

,2016-02-04 15:51:32.132 ThaliTest[1249:2206487] jxcore: startBroadcasting
,2016-02-04 15:51:32.135 ThaliTest[1249:2206487] server: starting 1454597492132.1249.xoGhCw==
,2016-02-04 15:51:32.137 ThaliTest[1249:2206487] multipeer session: start timer: 0x1a380160
,2016-02-04 15:51:32.142 ThaliTest[1249:2206487] THEMultipeerSession initialized peer 1454597492132.1249
,2016-02-04 15:51:32.143 ThaliTest[1249:2206487] jxcore: startBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error

,2016-02-04 15:51:32.146 ThaliTest[1249:2206487] jxcore: stopBroadcasting
,2016-02-04 15:51:32.146 ThaliTest[1249:2206487] THEMultipeerSession stopping peer
,2016-02-04 15:51:32.148 ThaliTest[1249:2206487] multipeer session: stop timer
,2016-02-04 15:51:32.151 ThaliTest[1249:2206487] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error

,2016-02-04 15:51:32.154 ThaliTest[1249:2206487] jxcore: startBroadcasting
,2016-02-04 15:51:32.157 ThaliTest[1249:2206487] server: starting 1454597492154.1249.zx+Kww==
,2016-02-04 15:51:32.159 ThaliTest[1249:2206487] multipeer session: start timer: 0x19486db0
,2016-02-04 15:51:32.163 ThaliTest[1249:2206487] THEMultipeerSession initialized peer 1454597492154.1249
2016-02-04 15:51:32.164 ThaliTest[1249:2206487] jxcore: startBroadcasting: success
,ok 64 Should be able to call startBroadcasting without error

,2016-02-04 15:51:32.167 ThaliTest[1249:2206487] jxcore: stopBroadcasting
,2016-02-04 15:51:32.168 ThaliTest[1249:2206487] THEMultipeerSession stopping peer
,2016-02-04 15:51:32.168 ThaliTest[1249:2206487] multipeer session: stop timer
,2016-02-04 15:51:32.170 ThaliTest[1249:2206487] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error

,2016-02-04 15:51:32.175 ThaliTest[1249:2206487] jxcore: startBroadcasting
,2016-02-04 15:51:32.178 ThaliTest[1249:2206487] server: starting 1454597492175.1249.RWxbCA==
,2016-02-04 15:51:32.180 ThaliTest[1249:2206487] multipeer session: start timer: 0x1a6a1410
,2016-02-04 15:51:32.186 ThaliTest[1249:2206487] THEMultipeerSession initialized peer 1454597492175.1249
,2016-02-04 15:51:32.187 ThaliTest[1249:2206487] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error

,2016-02-04 15:51:32.189 ThaliTest[1249:2206487] jxcore: stopBroadcasting
,2016-02-04 15:51:32.190 ThaliTest[1249:2206487] THEMultipeerSession stopping peer
,2016-02-04 15:51:32.191 ThaliTest[1249:2206487] multipeer session: stop timer
,2016-02-04 15:51:32.195 ThaliTest[1249:2206487] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,2016-02-04 15:51:32.197 ThaliTest[1249:2206487] jxcore: startBroadcasting
,2016-02-04 15:51:32.200 ThaliTest[1249:2206487] server: starting 1454597492197.1249.I+AjNw==
,2016-02-04 15:51:32.202 ThaliTest[1249:2206487] multipeer session: start timer: 0x1a6a0d80
,2016-02-04 15:51:32.208 ThaliTest[1249:2206487] THEMultipeerSession initialized peer 1454597492197.1249
,2016-02-04 15:51:32.209 ThaliTest[1249:2206487] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-02-04 15:51:32.211 ThaliTest[1249:2206487] jxcore: stopBroadcasting
,2016-02-04 15:51:32.212 ThaliTest[1249:2206487] THEMultipeerSession stopping peer
,2016-02-04 15:51:32.213 ThaliTest[1249:2206487] multipeer session: stop timer
,2016-02-04 15:51:32.214 ThaliTest[1249:2206487] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-02-04 15:51:32.219 ThaliTest[1249:2206487] jxcore: startBroadcasting
,2016-02-04 15:51:32.222 ThaliTest[1249:2206487] server: starting 1454597492219.1249.g1RHhA==
,2016-02-04 15:51:32.223 ThaliTest[1249:2206487] multipeer session: start timer: 0x1951cd60
,2016-02-04 15:51:32.226 ThaliTest[1249:2206487] THEMultipeerSession initialized peer 1454597492219.1249
,2016-02-04 15:51:32.227 ThaliTest[1249:2206487] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-02-04 15:51:32.230 ThaliTest[1249:2206487] jxcore: stopBroadcasting
,2016-02-04 15:51:32.230 ThaliTest[1249:2206487] THEMultipeerSession stopping peer
,2016-02-04 15:51:32.231 ThaliTest[1249:2206487] multipeer session: stop timer
,2016-02-04 15:51:32.231 ThaliTest[1249:2206487] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error
,
,2016-02-04 15:51:32.235 ThaliTest[1249:2206487] jxcore: startBroadcasting
,2016-02-04 15:51:32.237 ThaliTest[1249:2206487] server: starting 1454597492235.1249.JaSpsw==
,2016-02-04 15:51:32.238 ThaliTest[1249:2206487] multipeer session: start timer: 0x1a6a1c50
,2016-02-04 15:51:32.242 ThaliTest[1249:2206487] THEMultipeerSession initialized peer 1454597492235.1249
,2016-02-04 15:51:32.243 ThaliTest[1249:2206487] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-02-04 15:51:32.245 ThaliTest[1249:2206487] jxcore: stopBroadcasting
,2016-02-04 15:51:32.246 ThaliTest[1249:2206487] THEMultipeerSession stopping peer
,2016-02-04 15:51:32.247 ThaliTest[1249:2206487] multipeer session: stop timer
,2016-02-04 15:51:32.247 ThaliTest[1249:2206487] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,got: setup_ThaliEmitter calls startBroadcasting twice with error

,ack: setup_ThaliEmitter calls startBroadcasting twice with error_ok

,# teardown

,2016-02-04 15:51:35.361 ThaliTest[1249:2206487] jxcore: startBroadcasting
,2016-02-04 15:51:35.365 ThaliTest[1249:2206487] server: starting 1454597495360.1249.JLTidQ==
2016-02-04 15:51:35.366 ThaliTest[1249:2206487] multipeer session: start timer: 0x1a6a5380
2016-02-04 15:51:35.366 ThaliTest[1249:2206487] THEMultipeerSession in,itialized peer 1454597495360.1249
2016-02-04 15:51:35.366 ThaliTest[1249:2206487] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

2016-02-04 15:51:35.369 ThaliTest[1249:2206487] jxcore: startBroadcasting,
2016-02-04 15:51:35.369 ThaliTest[1249:2206487] jxcore: startBroadcasting: failure
,ok 75 Cannot call startBroadcasting twice

2016-02-04 15:51:35.375 ThaliTest[1249:2206487] jxcore: stopBroadcasting
2016-02-04 15:51:35.375 ThaliTest[1249:2206487] THEMultipeerSession stopping peer
2016-02-04 15:51:35.376 ThaliTest[1249:2206487] multip,eer session: stop timer
2016-02-04 15:51:35.376 ThaliTest[1249:2206487] jxcore: stopBroadcasting: success
ok 76 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on connection to bad peer

,got: setup_ThaliEmitter throws on connection to bad peer

,ack: setup_ThaliEmitter throws on connection to bad peer_ok

,# teardown

,2016-02-04 15:51:36.202 ThaliTest[1249:2206487] jxcore: startBroadcasting
,2016-02-04 15:51:36.205 ThaliTest[1249:2206487] server: starting 1454597496201.1249.qYTCEw==
2016-02-04 15:51:36.206 ThaliTest[1249:2206487] multipeer session: start timer: 0x1a6a8f50
2016-02-04 15:51:36.206 ThaliTest[1249:2206487] THEMultipeerSession in,itialized peer 1454597496201.1249
2016-02-04 15:51:36.207 ThaliTest[1249:2206487] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-02-04 15:51:36.210 ThaliTest[1249:2206487] jxcore: connect foobar
2,016-02-04 15:51:36.210 ThaliTest[1249:2206487] client: unknown peer foobar
2016-02-04 15:51:36.210 ThaliTest[1249:2206487] jxcore: connect: fail: Unknown peer
,ok 78 Should not connect to a bad peer

,2016-02-04 15:51:36.215 ThaliTest[1249:2206487] jxcore: stopBroadcasting
2016-02-04 15:51:36.216 ThaliTest[1249:2206487] THEMultipeerSession stopping peer
2016-02-04 15:51:36.217 ThaliTest[1249:2206487] multipeer session: stop timer
2016-02-04 15:51:36.217 ThaliTest[1249:2206487] jxcore: stopBroadcasting: success
ok 79 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,got: setup_ThaliEmitter throws on disconnect to bad peer

,ack: setup_ThaliEmitter throws on disconnect to bad peer_ok

,# teardown

,2016-02-04 15:51:36.766 ThaliTest[1249:2206487] jxcore: startBroadcasting
,2016-02-04 15:51:36.770 ThaliTest[1249:2206487] server: starting 1454597496766.1249.WQTTGw==
2016-02-04 15:51:36.771 ThaliTest[1249:2206487] multipeer session: start timer: 0x1a6c2d70
2016-02-04 15:51:36.771 ThaliTest[1249:2206487] THEMultipeerSession in,itialized peer 1454597496766.1249
2016-02-04 15:51:36.772 ThaliTest[1249:2206487] jxcore: startBroadcasting: success
ok 80 Should be able to call startBroadcasting without error

2016-02-04 15:51:36.774 ThaliTest[1249:2206487] jxcore: disconnect
2016-,02-04 15:51:36.774 ThaliTest[1249:2206487] jxcore: disconnect: fail
,ok 81 Disconnect should fail to a non-existant peer 

2016-02-04 15:51:36.780 ThaliTest[1249:2206487] jxcore: stopBroadcasting
,2016-02-04 15:51:36.780 ThaliTest[1249:2206487] THEMultipeerSession stopping peer
2016-02-04 15:51:36.781 ThaliTest[1249:2206487] multipeer session: stop timer
2016-02-04 15:51:36.782 ThaliTest[1249:2206487] jxcore: stopBroadcasting: success
ok 82 Shoul,d be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,got: setup_ThaliEmitter can discover and connect to peers

ack: setup_ThaliEmitter can discover and connect to peers_ok

,# teardown

,2016-02-04 15:51:37.327 ThaliTest[1249:2206487] jxcore: startBroadcasting
,2016-02-04 15:51:37.330 ThaliTest[1249:2206487] server: starting 1454597497326.1249.RCotcQ==
2016-02-04 15:51:37.331 ThaliTest[1249:2206487] multipeer session: start timer: 0x1a6b90b0
2016-02-04 15:51:37.332 ThaliTest[1249:2206487] THEMultipeerSession in,itialized peer 1454597497326.1249
2016-02-04 15:51:37.332 ThaliTest[1249:2206487] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-02-04 15:51:39.137 ThaliTest[1249:2206144] multipeer session: reset timer
2016-02-04 15:51:39.137 ThaliTest[1249:2206144] multipeer session: stop timer
2016-02-04 15:51:39.138 ThaliTest[1249:2206144] multipeer session: start timer: 0x1a6b90b0
2016-02-04 15:51:39.139 ThaliTest[1249:2206144] server session: connect
,2016-02-04 15:51:39.139 ThaliTest[1249:2206144] server session: stateChange:0->1 1454597500498.676
,2016-02-04 15:51:39.150 ThaliTest[1249:2206144] server: accepting invitation 1454597500498.676
,2016-02-04 15:51:39.692 ThaliTest[1249:2206144] client: found peer: 1454597500498.676.HfYy9g==
2016-02-04 15:51:39.694 ThaliTest[1249:2206487] jxcore: connect 1454597500498.676.HfYy9g==
2016-02-04 15:51:39.695 ThaliTest[1249:2206487] client session: connect
,2016-02-04 15:51:39.695 ThaliTest[1249:2206487] client session: stateChange:0->1 1454597500498.676.HfYy9g==
,2016-02-04 15:51:41.764 ThaliTest[1249:2207087] server session: connected
,2016-02-04 15:51:41.764 ThaliTest[1249:2207087] server session: stateChange:1->2 1454597500498.676
,2016-02-04 15:51:41.772 ThaliTest[1249:2206144] server relay: socket disconnected
2016-02-04 15:51:41.773 ThaliTest[1249:2206144] server relay: 0x1a5883d0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-04 15:51:41.811 ThaliTest[1249:2207084] server session: not connected 1454597500498.676
,2016-02-04 15:51:42.235 ThaliTest[1249:2207082] client session: connected
2016-02-04 15:51:42.235 ThaliTest[1249:2207082] client session: stateChange:1->2 1454597500498.676.HfYy9g==
,2016-02-04 15:51:42.239 ThaliTest[1249:2207082] client session: fireConnectCallback: 1454597500498.676.HfYy9g==
,2016-02-04 15:51:42.240 ThaliTest[1249:2207082] jxcore: connect: success
,ok 84 Should be able to connect without error

,ok 85 Port should be within range

,2016-02-04 15:51:42.245 ThaliTest[1249:2206487] jxcore: disconnect
2016-02-04 15:51:42.245 ThaliTest[1249:2206487] client session: disconnectFromPeer: 1454597500498.676.HfYy9g==
,2016-02-04 15:51:42.246 ThaliTest[1249:2206487] client session: disconnect
,2016-02-04 15:51:42.247 ThaliTest[1249:2206487] client session: stateChange:2->0 1454597500498.676.HfYy9g==
,2016-02-04 15:51:42.318 ThaliTest[1249:2206487] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-04 15:51:42.628 ThaliTest[1249:2206487] jxcore: stopBroadcasting
2016-02-04 15:51:42.628 ThaliTest[1249:2206487] THEMultipeerSession stopping peer
2016-02-04 15:51:42.628 ThaliTest[1249:2206487] multipeer session: stop timer
2016-02-04 15:51:42.,629 ThaliTest[1249:2206487] server session: disconnect
2016-02-04 15:51:42.629 ThaliTest[1249:2206487] server session: stateChange:2->0 1454597500498.676
2016-02-04 15:51:42.630 ThaliTest[1249:2206487] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect
,
,got: setup_ThaliEmitter can discover and connect to peers and then fail on double connect

,ack: setup_ThaliEmitter can discover and connect to peers and then fail on double connect_ok

,# teardown

,2016-02-04 15:51:43.654 ThaliTest[1249:2206487] jxcore: startBroadcasting
,2016-02-04 15:51:43.658 ThaliTest[1249:2206487] server: starting 1454597503653.1249.7uAEDQ==
2016-02-04 15:51:43.659 ThaliTest[1249:2206487] multipeer session: start timer: 0x1a57e540
2016-02-04 15:51:43.660 ThaliTest[1249:2206487] THEMultipeerSession in,itialized peer 1454597503653.1249
2016-02-04 15:51:43.660 ThaliTest[1249:2206487] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-02-04 15:51:43.868 ThaliTest[1249:2206144] client: found peer: 1454597500498.676.HfYy9g==
2016-02-04 15:51:43.870 ThaliTest[1249:2206487] jxcore: connect 1454597500498.676.HfYy9g==
2016-02-04 15:51:43.870 ThaliTest[1249:2206487] client session: conn,ect
2016-02-04 15:51:43.871 ThaliTest[1249:2206487] client session: stateChange:0->1 1454597500498.676.HfYy9g==
,2016-02-04 15:51:44.897 ThaliTest[1249:2206144] client: found peer: 1454597506859.676.VbGEdw==
2016-02-04 15:51:44.899 ThaliTest[1249:2206487] jxcore: connect 1454597506859.676.VbGEdw==
2016-02-04 15:51:44.899 ThaliTest[1249:2206487] client session: connect
2016-02-04 15:51:44.900 ThaliTest[1249:2206487] client session: stateChange:0->1 1454597506859.676.VbGEdw==
,2016-02-04 15:51:44.969 ThaliTest[1249:2206144] multipeer session: reset timer
2016-02-04 15:51:44.969 ThaliTest[1249:2206144] multipeer session: stop timer
2016-02-04 15:51:44.969 ThaliTest[1249:2206144] multipeer session: start timer: 0x1a57e540
,2016-02-04 15:51:44.970 ThaliTest[1249:2206144] server session: connect
2016-02-04 15:51:44.972 ThaliTest[1249:2206144] server session: stateChange:0->1 1454597506859.676
,2016-02-04 15:51:44.981 ThaliTest[1249:2206144] server: accepting invitation 1454597506859.676
,2016-02-04 15:51:47.450 ThaliTest[1249:2207082] server session: connected
2016-02-04 15:51:47.451 ThaliTest[1249:2207082] server session: stateChange:1->2 1454597506859.676
,2016-02-04 15:51:47.462 ThaliTest[1249:2206144] server relay: socket disconnected
,2016-02-04 15:51:47.464 ThaliTest[1249:2206144] server relay: 0x1a6be080 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-04 15:51:47.471 ThaliTest[1249:2207084] client session: connected
,2016-02-04 15:51:47.471 ThaliTest[1249:2207084] client session: stateChange:1->2 1454597506859.676.VbGEdw==
,2016-02-04 15:51:47.477 ThaliTest[1249:2207084] client session: fireConnectCallback: 1454597506859.676.VbGEdw==
2016-02-04 15:51:47.477 ThaliTest[1249:2207084] jxcore: connect: success
,ok 88 Should be able to connect without error

,ok 89 Port should be within range

,2016-02-04 15:51:47.481 ThaliTest[1249:2206487] jxcore: connect 1454597506859.676.VbGEdw==
,2016-02-04 15:51:47.481 ThaliTest[1249:2206487] client: already connect(ing/ed) to 1454597506859.676.VbGEdw==
,2016-02-04 15:51:47.482 ThaliTest[1249:2206487] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

,2016-02-04 15:51:47.486 ThaliTest[1249:2206487] jxcore: disconnect
,2016-02-04 15:51:47.488 ThaliTest[1249:2206487] client session: disconnectFromPeer: 1454597506859.676.VbGEdw==
,2016-02-04 15:51:47.488 ThaliTest[1249:2206487] client session: disconnect
,2016-02-04 15:51:47.489 ThaliTest[1249:2206487] client session: stateChange:2->0 1454597506859.676.VbGEdw==
,2016-02-04 15:51:47.526 ThaliTest[1249:2207084] server session: not connected 1454597506859.676
,2016-02-04 15:51:47.563 ThaliTest[1249:2206487] jxcore: disconnect: success
,ok 91 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-04 15:51:47.879 ThaliTest[1249:2206487] jxcore: stopBroadcasting
2016-02-04 15:51:47.879 ThaliTest[1249:2206487] THEMultipeerSession stopping peer
2016-02-04 15:51:47.880 ThaliTest[1249:2206487] multipeer session: stop timer
2016-02-04 15:51:47.,880 ThaliTest[1249:2206487] client session: disconnect
2016-02-04 15:51:47.880 ThaliTest[1249:2206487] client session: stateChange:1->0 1454597500498.676.HfYy9g==
2016-02-04 15:51:47.881 ThaliTest[1249:2206487] server session: disconnect
2016-02-04 15:5,1:47.882 ThaliTest[1249:2206487] server session: stateChange:2->0 1454597506859.676
2016-02-04 15:51:47.883 ThaliTest[1249:2206487] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers ,and then fail on double disconnect

,got: setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect

,ack: setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect_ok

,# teardown

,2016-02-04 15:51:48.390 ThaliTest[1249:2206487] jxcore: startBroadcasting
,2016-02-04 15:51:48.393 ThaliTest[1249:2206487] server: starting 1454597508389.1249.w1EDxA==
2016-02-04 15:51:48.394 ThaliTest[1249:2206487] multipeer session: start timer: 0x1a58b5a0
2016-02-04 15:51:48.394 ThaliTest[1249:2206487] THEMultipeerSession in,itialized peer 1454597508389.1249
2016-02-04 15:51:48.395 ThaliTest[1249:2206487] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-04 15:51:49.133 ThaliTest[1249:2206144] client: found peer: 1454597500498.676.HfYy9g==
2016-02-04 15:51:49.134 ThaliTest[1249:2206487] jxcore: connect 1454597500498.676.HfYy9g==
2016-02-04 15:51:49.135 ThaliTest[1249:2206487] client session: conn,ect
2016-02-04 15:51:49.135 ThaliTest[1249:2206487] client session: stateChange:0->1 1454597500498.676.HfYy9g==
,2016-02-04 15:51:49.160 ThaliTest[1249:2206144] client: found peer: 1454597511584.676.AhDAFw==
2016-02-04 15:51:49.162 ThaliTest[1249:2206487] jxcore: connect 1454597511584.676.AhDAFw==
2016-02-04 15:51:49.163 ThaliTest[1249:2206487] client session: conn,ect
2016-02-04 15:51:49.163 ThaliTest[1249:2206487] client session: stateChange:0->1 1454597511584.676.AhDAFw==
,2016-02-04 15:51:49.688 ThaliTest[1249:2206144] multipeer session: reset timer
2016-02-04 15:51:49.688 ThaliTest[1249:2206144] multipeer session: stop timer
2016-02-04 15:51:49.688 ThaliTest[1249:2206144] multipeer session: start timer: 0x1a58b5a0
2016-,02-04 15:51:49.689 ThaliTest[1249:2206144] server session: connect
2016-02-04 15:51:49.689 ThaliTest[1249:2206144] server session: stateChange:0->1 1454597511584.676
,2016-02-04 15:51:49.699 ThaliTest[1249:2206144] server: accepting invitation 1454597511584.676
,2016-02-04 15:51:52.173 ThaliTest[1249:2207086] client session: connected
2016-02-04 15:51:52.174 ThaliTest[1249:2207086] client session: stateChange:1->2 1454597511584.676.AhDAFw==
,2016-02-04 15:51:52.188 ThaliTest[1249:2207084] client session: fireConnectCallback: 1454597511584.676.AhDAFw==
2016-02-04 15:51:52.188 ThaliTest[1249:2207084] jxcore: connect: success
,ok 93 Should be able to connect without error

ok 94 Port should be within range

,2016-02-04 15:51:52.194 ThaliTest[1249:2206487] jxcore: disconnect
2016-02-04 15:51:52.194 ThaliTest[1249:2206487] client session: disconnectFromPeer: 1454597511584.676.AhDAFw==
2016-02-04 15:51:52.195 ThaliTest[1249:2206487] client session: disconnect
2016-02-04 15:51:52.195 ThaliTest[1249:2206487] client session: stateChange:2->0 1454597511584.676.AhDAFw==
,2016-02-04 15:51:52.208 ThaliTest[1249:2206487] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error

,2016-02-04 15:51:52.211 ThaliTest[1249:2206487] jxcore: disconnect
,2016-02-04 15:51:52.213 ThaliTest[1249:2206487] jxcore: disconnect: fail
,ok 96 Disconnect should fail 
,
,setting stopBroadcasting callback and ending test.
,
,# setup

,2016-02-04 15:51:52.441 ThaliTest[1249:2207084] server session: connected
,2016-02-04 15:51:52.441 ThaliTest[1249:2207084] server session: stateChange:1->2 1454597511584.676
,2016-02-04 15:51:52.473 ThaliTest[1249:2206144] server relay: socket disconnected
2016-02-04 15:51:52.474 ThaliTest[1249:2206144] server relay: 0x1a6ee2a0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-04 15:51:52.498 ThaliTest[1249:2207087] server session: not connected 1454597511584.676
,calling stopBroadcasting

,2016-02-04 15:51:52.586 ThaliTest[1249:2206487] jxcore: stopBroadcasting
2016-02-04 15:51:52.587 ThaliTest[1249:2206487] THEMultipeerSession stopping peer
2016-02-04 15:51:52.587 ThaliTest[1249:2206487] multipeer session: stop timer
2016-02-04 15:51:52.,587 ThaliTest[1249:2206487] client session: disconnect
2016-02-04 15:51:52.588 ThaliTest[1249:2206487] client session: stateChange:1->0 1454597500498.676.HfYy9g==
2016-02-04 15:51:52.588 ThaliTest[1249:2206487] server session: disconnect
2016-02-04 15:5,1:52.589 ThaliTest[1249:2206487] server session: stateChange:2->0 1454597511584.676
2016-02-04 15:51:52.591 ThaliTest[1249:2206487] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can connect and send data

,got: setup_ThaliEmitter can connect and send data

,ack: setup_ThaliEmitter can connect and send data_ok

,# teardown

,echo server started on port: 57018

,2016-02-04 15:51:53.456 ThaliTest[1249:2206487] jxcore: startBroadcasting
,2016-02-04 15:51:53.458 ThaliTest[1249:2206487] server: starting 1454597513456.1249.aLHd3A==
2016-02-04 15:51:53.458 ThaliTest[1249:2206487] multipeer session: start timer: 0x1a58cfa0
2016-02-04 15:51:53.458 ThaliTest[1249:2206487] THEMultipeerSession initialized peer 1454597513456.1249
2016-02-04 15:51:53.458 ThaliTest[1249:2206487] jxcore: startBroadcasting: success
ok 97 Should be able to call startBroadcasting without error

,2016-02-04 15:51:53.728 ThaliTest[1249:2206144] client: found peer: 1454597511584.676.AhDAFw==
2016-02-04 15:51:53.729 ThaliTest[1249:2206487] jxcore: connect 1454597511584.676.AhDAFw==
2016-02-04 15:51:53.729 ThaliTest[1249:2206487] client session: conn,ect
2016-02-04 15:51:53.729 ThaliTest[1249:2206487] client session: stateChange:0->1 1454597511584.676.AhDAFw==
,2016-02-04 15:51:54.815 ThaliTest[1249:2206144] multipeer session: reset timer
2016-02-04 15:51:54.816 ThaliTest[1249:2206144] multipeer session: stop timer
2016-02-04 15:51:54.816 ThaliTest[1249:2206144] multipeer session: start timer: 0x1a58cfa0
2016-02-04 15:51:54.816 ThaliTest[1249:2206144] server session: connect
2016-02-04 15:51:54.816 ThaliTest[1249:2206144] server session: stateChange:0->1 1454597516803.676
,2016-02-04 15:51:54.823 ThaliTest[1249:2206144] server: accepting invitation 1454597516803.676
,2016-02-04 15:51:54.896 ThaliTest[1249:2206144] client: found peer: 1454597516803.676.tCIDsA==
2016-02-04 15:51:54.897 ThaliTest[1249:2206487] jxcore: connect 1454597516803.676.tCIDsA==
2016-02-04 15:51:54.897 ThaliTest[1249:2206487] client session: connect
2016-02-04 15:51:54.897 ThaliTest[1249:2206487] client session: stateChange:0->1 1454597516803.676.tCIDsA==
,2016-02-04 15:51:57.164 ThaliTest[1249:2207087] server session: connected
2016-02-04 15:51:57.164 ThaliTest[1249:2207087] server session: stateChange:1->2 1454597516803.676
,2016-02-04 15:51:57.202 ThaliTest[1249:2206144] server relay: connected (to port: 57018)
,2016-02-04 15:51:57.510 ThaliTest[1249:2207086] client session: connected
2016-02-04 15:51:57.511 ThaliTest[1249:2207086] client session: stateChange:1->2 1454597516803.676.tCIDsA==
,2016-02-04 15:51:57.521 ThaliTest[1249:2207082] server session: not connected 1454597516803.676
,2016-02-04 15:51:57.545 ThaliTest[1249:2207084] client session: fireConnectCallback: 1454597516803.676.tCIDsA==
,2016-02-04 15:51:57.547 ThaliTest[1249:2207084] jxcore: connect: success
,ok 98 Should be able to connect without error

,ok 99 Port should be within range

,2016-02-04 15:51:57.553 ThaliTest[1249:2206144] client: relay established
2016-02-04 15:51:57.553 ThaliTest[1249:2206144] client: new accepted socket: 0x1a6e4970
,data in 1024

,data in 6570

,data in 17520

,data in 37230

,data in 48180

,data in 74460

,data in 91980

,data in 109500

,data in 131072

,ok 100 the test messages should be equal

,2016-02-04 15:51:57.816 ThaliTest[1249:2206487] jxcore: disconnect
2016-02-04 15:51:57.816 ThaliTest[1249:2206487] client session: disconnectFromPeer: 1454597516803.676.tCIDsA==
2016-02-04 15:51:57.816 ThaliTest[1249:2206487] client session: disconnect
2016-02-04 15:51:57.816 ThaliTest[1249:2206487] client session: stateChange:2->0 1454597516803.676.tCIDsA==
,2016-02-04 15:51:57.828 ThaliTest[1249:2206487] jxcore: disconnect: success
ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-04 15:51:57.905 ThaliTest[1249:2206487] jxcore: stopBroadcasting
2016-02-04 15:51:57.905 ThaliTest[1249:2206487] THEMultipeerSession stopping peer
2016-02-04 15:51:57.905 ThaliTest[1249:2206487] multipeer session: stop timer
2016-02-04 15:51:57.,906 ThaliTest[1249:2206487] client session: disconnect
2016-02-04 15:51:57.906 ThaliTest[1249:2206487] client session: stateChange:1->0 1454597511584.676.AhDAFw==
2016-02-04 15:51:57.907 ThaliTest[1249:2206487] server session: disconnect
2016-02-04 15:5,1:57.907 ThaliTest[1249:2206487] server session: stateChange:2->0 1454597516803.676
,2016-02-04 15:51:57.912 ThaliTest[1249:2206487] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter handles socket disconnect correctly

,got: setup_ThaliEmitter handles socket disconnect correctly

ack: setup_ThaliEmitter handles socket disconnect correctly_ok

,# teardown

,echo server started on port: 57025

,2016-02-04 15:51:58.410 ThaliTest[1249:2206487] jxcore: startBroadcasting
,2016-02-04 15:51:58.413 ThaliTest[1249:2206487] server: starting 1454597518408.1249.VlewzQ==
2016-02-04 15:51:58.414 ThaliTest[1249:2206487] multipeer session: start timer: 0x1a5f3b20
2016-02-04 15:51:58.414 ThaliTest[1249:2206487] THEMultipeerSession in,itialized peer 1454597518408.1249
2016-02-04 15:51:58.415 ThaliTest[1249:2206487] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-02-04 15:51:59.055 ThaliTest[1249:2206144] client: found peer: 1454597516803.676.tCIDsA==
[{"peerIdentifier":"1454597516803.676.tCIDsA==","peerName":"(null)","peerAvailable":true}]

2016-02-04 15:51:59.058 ThaliTest[1249:2206487] jxcore: connect 14,54597516803.676.tCIDsA==
2016-02-04 15:51:59.059 ThaliTest[1249:2206487] client session: connect
2016-02-04 15:51:59.059 ThaliTest[1249:2206487] client session: stateChange:0->1 1454597516803.676.tCIDsA==
,2016-02-04 15:51:59.607 ThaliTest[1249:2206144] client: lost peer: 1454597516803.676.tCIDsA==
2016-02-04 15:51:59.607 ThaliTest[1249:2206144] client session: onPeerLost: 1454597516803.676.tCIDsA==
2016-02-04 15:51:59.607 ThaliTest[1249:2206144] client se,ssion: onLinkFailure: 1454597516803.676.tCIDsA==
2016-02-04 15:51:59.607 ThaliTest[1249:2206144] client session: disconnect
2016-02-04 15:51:59.608 ThaliTest[1249:2206144] client session: stateChange:1->0 1454597516803.676.tCIDsA==
2016-02-04 15:51:59.6,08 ThaliTest[1249:2206144] client session: fireConnectCallback: 1454597516803.676.tCIDsA==
2016-02-04 15:51:59.609 ThaliTest[1249:2206144] jxcore: connect: fail: Peer disconnected
2016-02-04 15:51:59.611 ThaliTest[1249:2206144] client: found peer: 145459,7521597.676.0LsCjw==
[{"peerIdentifier":"1454597516803.676.tCIDsA==","peerName":"(null)","peerAvailable":false}]

[{"peerIdentifier":"1454597521597.676.0LsCjw==","peerName":"(null)","peerAvailable":true}]

2016-02-04 15:51:59.614 ThaliTest[1249:220648,7] jxcore: connect 1454597521597.676.0LsCjw==
,2016-02-04 15:51:59.618 ThaliTest[1249:2206487] client session: connect
,2016-02-04 15:51:59.619 ThaliTest[1249:2206487] client session: stateChange:0->1 1454597521597.676.0LsCjw==
,2016-02-04 15:51:59.836 ThaliTest[1249:2206144] multipeer session: reset timer
2016-02-04 15:51:59.836 ThaliTest[1249:2206144] multipeer session: stop timer
2016-02-04 15:51:59.837 ThaliTest[1249:2206144] multipeer session: start timer: 0x1a5f3b20
2016-02-04 15:51:59.837 ThaliTest[1249:2206144] server session: connect
2016-02-04 15:51:59.837 ThaliTest[1249:2206144] server session: stateChange:0->1 1454597521597.676
,2016-02-04 15:51:59.847 ThaliTest[1249:2206144] server: accepting invitation 1454597521597.676
,2016-02-04 15:52:00.616 ThaliTest[1249:2206487] jxcore: connect 1454597516803.676.tCIDsA==
2016-02-04 15:52:00.616 ThaliTest[1249:2206487] client: connect: unreachable 1454597516803.676.tCIDsA==
2016-02-04 15:52:00.617 ThaliTest[1249:2206487] jxcore: con,nect: fail: Peer unreachable
,2016-02-04 15:52:04.055 ThaliTest[1249:2207082] client session: connected
2016-02-04 15:52:04.055 ThaliTest[1249:2207082] client session: stateChange:1->2 1454597521597.676.0LsCjw==
,2016-02-04 15:52:04.260 ThaliTest[1249:2207084] server session: connected
,2016-02-04 15:52:04.260 ThaliTest[1249:2207084] server session: stateChange:1->2 1454597521597.676
,2016-02-04 15:52:04.498 ThaliTest[1249:2207082] client session: fireConnectCallback: 1454597521597.676.0LsCjw==
2016-02-04 15:52:04.498 ThaliTest[1249:2207082] jxcore: connect: success
ok 103 Should be able to connect without error

ok 104 Port should be within range

,ok 105 First connect should succeed

,2016-02-04 15:52:04.535 ThaliTest[1249:2206144] client: relay established
2016-02-04 15:52:04.536 ThaliTest[1249:2206144] client: new accepted socket: 0x1a5957e0
,2016-02-04 15:52:04.675 ThaliTest[1249:2206144] server relay: connected (to port: 57025)
,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-02-04 15:52:05.132 ThaliTest[1249:2206144] client: socket closed
2016-02-04 15:52:05.132 ThaliTest[1249:2206144] client relay: socket disconnected
2016-02-04 15:52:05.132 ThaliTest[1249:2206144] client relay: 0x1a5957e0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-04 15:52:05.133 ThaliTest[1249:2206144] client session: socket closed: 1454597521597.676.0LsCjw==
2016-02-04 1,5:52:05.133 ThaliTest[1249:2206144] client session: onLinkFailure: 1454597521597.676.0LsCjw==
2016-02-04 15:52:05.133 ThaliTest[1249:2206144] client session: disconnect
2016-02-04 15:52:05.133 ThaliTest[1249:2206144] client session: stateChange:2->0 1454597521597.676.0LsCjw==
,2016-02-04 15:52:05.213 ThaliTest[1249:2206144] client session: fireConnectionErrorEvent: 1454597521597.676.0LsCjw==
2016-02-04 15:52:05.217 ThaliTest[1249:2206487] jxcore: connect 1454597521597.676.0LsCjw==
2016-02-04 15:52:05.217 ThaliTest[1249:2206487,] client session: connect
2016-02-04 15:52:05.217 ThaliTest[1249:2206487] client session: stateChange:0->1 1454597521597.676.0LsCjw==
,2016-02-04 15:52:06.203 ThaliTest[1249:2207084] server session: not connected 1454597521597.676
,2016-02-04 15:52:06.219 ThaliTest[1249:2206144] multipeer session: reset timer
,2016-02-04 15:52:06.220 ThaliTest[1249:2206144] multipeer session: stop timer
,2016-02-04 15:52:06.222 ThaliTest[1249:2206144] multipeer session: start timer: 0x1a5f3b20
,2016-02-04 15:52:06.223 ThaliTest[1249:2206144] server: disconnecting to refresh session (1454597521597.676)
2016-02-04 15:52:06.227 ThaliTest[1249:2206144] server session: disconnect
2016-02-04 15:52:06.228 ThaliTest[1249:2206144] server session: stateChange:2->0 1454597521597.676
,2016-02-04 15:52:06.233 ThaliTest[1249:2206144] server session: connect
2016-02-04 15:52:06.234 ThaliTest[1249:2206144] server session: stateChange:0->1 1454597521597.676
,2016-02-04 15:52:06.268 ThaliTest[1249:2206144] server: accepting invitation 1454597521597.676
,2016-02-04 15:52:08.336 ThaliTest[1249:2207080] server session: connected
,2016-02-04 15:52:08.337 ThaliTest[1249:2207080] server session: stateChange:1->2 1454597521597.676
,2016-02-04 15:52:09.035 ThaliTest[1249:2206144] server relay: connected (to port: 57025)
,2016-02-04 15:52:09.206 ThaliTest[1249:2207082] server session: not connected 1454597521597.676
,2016-02-04 15:52:15.989 ThaliTest[1249:2207082] client session: not connected 1454597521597.676.0LsCjw==
2016-02-04 15:52:15.989 ThaliTest[1249:2207082] client session: onLinkFailure: 1454597521597.676.0LsCjw==
2016-02-04 15:52:15.990 ThaliTest[1249:2207,082] client session: disconnect
,2016-02-04 15:52:15.990 ThaliTest[1249:2207082] client session: stateChange:1->0 1454597521597.676.0LsCjw==
,2016-02-04 15:52:15.999 ThaliTest[1249:2207082] client session: fireConnectCallback: 1454597521597.676.0LsCjw==
2016-02-04 15:52:16.000 ThaliTest[1249:2207082] jxcore: connect: fail: Peer disconnected
,2016-02-04 15:52:17.009 ThaliTest[1249:2206487] jxcore: connect 1454597521597.676.0LsCjw==
2016-02-04 15:52:17.010 ThaliTest[1249:2206487] client session: connect
2016-02-04 15:52:17.010 ThaliTest[1249:2206487] client session: stateChange:0->1 1454597521597.676.0LsCjw==
,2016-02-04 15:52:20.289 ThaliTest[1249:2207084] client session: connected
2016-02-04 15:52:20.290 ThaliTest[1249:2207084] client session: stateChange:1->2 1454597521597.676.0LsCjw==
,2016-02-04 15:52:20.406 ThaliTest[1249:2207080] client session: fireConnectCallback: 1454597521597.676.0LsCjw==
2016-02-04 15:52:20.407 ThaliTest[1249:2207080] jxcore: connect: success
ok 108 Should be able to connect without error

ok 109 Port should be within range

,ok 110 Second connect should succeed

,2016-02-04 15:52:20.442 ThaliTest[1249:2206144] client: relay established
2016-02-04 15:52:20.442 ThaliTest[1249:2206144] client: new accepted socket: 0x1a5e27c0
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-02-04 15:52:20.831 ThaliTest[1249:2206144] client: socket closed
2016-02-04 15:52:20.831 ThaliTest[1249:2206144] client relay: socket disconnected
2016-02-04 15:52:20.832 ThaliTest[1249:2206144] client relay: 0x1a5e27c0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-04 15:52:20.832 ThaliTest[1249:2206144] client session: socket closed: 1454597521597.676.0LsCjw==
2016-02-04 1,5:52:20.832 ThaliTest[1249:2206144] client session: onLinkFailure: 1454597521597.676.0LsCjw==
2016-02-04 15:52:20.832 ThaliTest[1249:2206144] client session: disconnect
2016-02-04 15:52:20.833 ThaliTest[1249:2206144] client session: stateChange:2->0 1454,597521597.676.0LsCjw==
,2016-02-04 15:52:20.849 ThaliTest[1249:2206144] client session: fireConnectionErrorEvent: 1454597521597.676.0LsCjw==
,calling stopBroadcasting

,2016-02-04 15:52:20.896 ThaliTest[1249:2206487] jxcore: stopBroadcasting
,2016-02-04 15:52:20.898 ThaliTest[1249:2206487] THEMultipeerSession stopping peer
,2016-02-04 15:52:20.899 ThaliTest[1249:2206487] multipeer session: stop timer
,2016-02-04 15:52:20.901 ThaliTest[1249:2206487] server session: disconnect
,2016-02-04 15:52:20.911 ThaliTest[1249:2206487] server session: stateChange:2->0 1454597521597.676
,2016-02-04 15:52:20.924 ThaliTest[1249:2206487] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,
,# ThaliReplicationManager can call start without error
,
,got: setup_ThaliReplicationManager can call start without error

ack: setup_ThaliReplicationManager can call start without error_ok
,
,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/D94046F5-9391-4957-8852-0FFC94D1E28A/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-02-04 15:52:21.352 ThaliTest[1249:2206487] jxcore: startBroadcasting
,2016-02-04 15:52:21.353 ThaliTest[1249:2206487] server: starting iJ73fAElE3Jb_XissQ1iBQ.rIB9Uw==
2016-02-04 15:52:21.354 ThaliTest[1249:2206487] multipeer session: start timer: 0x1a313650
2016-02-04 15:52:21.354 ThaliTest[1249:2206487] THEMultipeerSessio,n initialized peer iJ73fAElE3Jb_XissQ1iBQ
2016-02-04 15:52:21.354 ThaliTest[1249:2206487] jxcore: startBroadcasting: success
ok 114 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 115 stopping event should occur in right order

About to call stopBroadcasting

2016-02-04 15:52:21.355 ThaliTest[1249:2206487] jxcore: stopBroadcasting
2016-02-04 15:52:21.355 ThaliTest[1249:2206487] THEMultipeerSession stopping peer
2016-02-04 15:52:21.355 ThaliTest[12,49:2206487] multipeer session: stop timer
2016-02-04 15:52:21.355 ThaliTest[1249:2206487] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

ok 116 stopped event should occur in right order

,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,got: setup_ThaliReplicationManager receives identity

ack: setup_ThaliReplicationManager receives identity_ok

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/D94046F5-9391-4957-8852-0FFC94D1E28A/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-04 15:52:21.851 ThaliTest[1249:2206487] jxcore: startBroadcasting
,2016-02-04 15:52:21.855 ThaliTest[1249:2206487] server: starting iJ73fAElE3Jb_XissQ1iBQ.2qJxSA==
2016-02-04 15:52:21.855 ThaliTest[1249:2206487] multipeer session: start timer: 0x1a67ce50
2016-02-04 15:52:21.856 ThaliTest[1249:2206487] THEMultipeerSessio,n initialized peer iJ73fAElE3Jb_XissQ1iBQ
2016-02-04 15:52:21.856 ThaliTest[1249:2206487] jxcore: startBroadcasting: success
ok 117 getDeviceIdentity should not return an error

ok 118 deviceName should not be null

Now in TRM stop

State of this._,isStarted: true

About to call stopBroadcasting

2016-02-04 15:52:21.860 ThaliTest[1249:2206487] jxcore: stopBroadcasting
,2016-02-04 15:52:21.860 ThaliTest[1249:2206487] THEMultipeerSession stopping peer
2016-02-04 15:52:21.861 ThaliTest[1249:2206487] multipeer session: stop timer
2016-02-04 15:52:21.861 ThaliTest[1249:2206487] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,got: setup_ThaliReplicationManager replicates database

,ack: setup_ThaliReplicationManager replicates database_ok

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/D94046F5-9391-4957-8852-0FFC94D1E28A/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-04 15:52:24.746 ThaliTest[1249:2206487] jxcore: startBroadcasting
,2016-02-04 15:52:24.748 ThaliTest[1249:2206487] server: starting iJ73fAElE3Jb_XissQ1iBQ.Pzo0yw==
2016-02-04 15:52:24.748 ThaliTest[1249:2206487] multipeer session: start timer: 0x1a46d150
2016-02-04 15:52:24.748 ThaliTest[1249:2206487] THEMultipeerSession initialized peer iJ73fAElE3Jb_XissQ1iBQ
,2016-02-04 15:52:24.750 ThaliTest[1249:2206487] jxcore: startBroadcasting: success
ok 119 getDeviceIdentity should not return an error

ok 120 deviceName should not be null

,2016-02-04 15:52:24.757 ThaliTest[1249:2206144] client: found peer: 1454597521597.676.0LsCjw==
,2016-02-04 15:52:29.340 ThaliTest[1249:2206144] client: found peer: vlAFZKiNNOMCwc-IYmCk_g.b0VzbQ==
,2016-02-04 15:52:29.374 ThaliTest[1249:2206487] jxcore: connect 1454597521597.676.0LsCjw==
,2016-02-04 15:52:29.375 ThaliTest[1249:2206487] client session: connect
,2016-02-04 15:52:29.375 ThaliTest[1249:2206487] client session: stateChange:0->1 1454597521597.676.0LsCjw==
,2016-02-04 15:52:29.384 ThaliTest[1249:2206487] jxcore: connect vlAFZKiNNOMCwc-IYmCk_g.b0VzbQ==
,2016-02-04 15:52:29.386 ThaliTest[1249:2206487] client session: connect
,2016-02-04 15:52:29.390 ThaliTest[1249:2206487] client session: stateChange:0->1 vlAFZKiNNOMCwc-IYmCk_g.b0VzbQ==
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-02-04 15:52:30.611 ThaliTest[1249:2206144] multipeer session: reset timer
2016-02-04 15:52:30.612 ThaliTest[1249:2206144] multipeer session: stop timer
2016-02-04 15:52:30.612 ThaliTest[1249:2206144] multipeer session: start timer: 0x1a46d150
2016-,02-04 15:52:30.612 ThaliTest[1249:2206144] server session: connect
2016-02-04 15:52:30.612 ThaliTest[1249:2206144] server session: stateChange:0->1 vlAFZKiNNOMCwc-IYmCk_g
,2016-02-04 15:52:30.624 ThaliTest[1249:2206144] server: accepting invitation vlAFZKiNNOMCwc-IYmCk_g
,2016-02-04 15:52:32.538 ThaliTest[1249:2207082] client session: connected
2016-02-04 15:52:32.538 ThaliTest[1249:2207082] client session: stateChange:1->2 vlAFZKiNNOMCwc-IYmCk_g.b0VzbQ==
,2016-02-04 15:52:32.544 ThaliTest[1249:2207082] client session: fireConnectCallback: vlAFZKiNNOMCwc-IYmCk_g.b0VzbQ==
2016-02-04 15:52:32.545 ThaliTest[1249:2207082] jxcore: connect: success
,2016-02-04 15:52:32.560 ThaliTest[1249:2206144] client: relay established
2016-02-04 15:52:32.560 ThaliTest[1249:2206144] client: new accepted socket: 0x1a45dca0
,client bridge: new client socket

,client bridge: new client socket
,
,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

2016-02-04 15:52:34.679 ThaliTest[1249:2207080] server session: connected
,2016-02-04 15:52:34.679 ThaliTest[1249:2207080] server session: stateChange:1->2 vlAFZKiNNOMCwc-IYmCk_g
,2016-02-04 15:52:34.690 ThaliTest[1249:2206144] server relay: connected (to port: 57045)
,server bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,ok 123 1st change of remote doc should contain remote id

,client bridge: new client socket
,
,ok 124 Can update remote doc without error

,null

,{ ok: true,
  id: '9ef40efc-3e3c-4425-b42e-7bf6e749e66d',
  rev: '2-73fc2892d85174a5a3a29736a2dc29e8' }

,ok 125 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,ok 126 Local changes occur in strict order

ok 127 2nd change of local doc should contain remote id

,client bridge: new client socket

# setup

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,Now in TRM stop

State of this._isStarted: true

,About to call stopBroadcasting

,2016-02-04 15:52:44.022 ThaliTest[1249:2206487] jxcore: stopBroadcasting
,2016-02-04 15:52:44.022 ThaliTest[1249:2206487] THEMultipeerSession stopping peer
,2016-02-04 15:52:44.023 ThaliTest[1249:2206487] multipeer session: stop timer
,2016-02-04 15:52:44.024 ThaliTest[1249:2206487] client session: disconnect
,2016-02-04 15:52:44.024 ThaliTest[1249:2206487] client session: stateChange:2->0 vlAFZKiNNOMCwc-IYmCk_g.b0VzbQ==
,2016-02-04 15:52:44.040 ThaliTest[1249:2207087] server session: not connected vlAFZKiNNOMCwc-IYmCk_g
,2016-02-04 15:52:44.052 ThaliTest[1249:2207087] client session: not connected vlAFZKiNNOMCwc-IYmCk_g.b0VzbQ==
,2016-02-04 15:52:44.056 ThaliTest[1249:2206487] client session: disconnect
2016-02-04 15:52:44.056 ThaliTest[1249:2207087] client session: onLinkFailure: vlAFZKiNNOMCwc-IYmCk_g.b0VzbQ==
2016-02-04 15:52:44.057 ThaliTest[1249:2206487] client session: stat,eChange:1->0 1454597521597.676.0LsCjw==
Assertion failed: ([self connectionState] != THEPeerSessionStateNotConnected), function -[THEMultipeerClientSession onLinkFailure], file /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerClientSession.m, line 124.
,Process 1249 stopped
* thread #17: tid = 0x21ad6f, 0x38fc7c84 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.MCSession.callbackQueue', stop reason = signal SIGABRT
    frame #0: 0x38fc7c84 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x38fc7c84 <+8>:  blo    0x38fc7c9c                ; <+32>
    0x38fc7c88 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x38fc7c8c <+16>: ldr    r12, [pc, r12]
    0x38fc7c90 <+20>: b      0x38fc7c98                ; <+28>
,* thread #17: tid = 0x21ad6f, 0x38fc7c84 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.MCSession.callbackQueue', stop reason = signal SIGABRT
  * frame #0: 0x38fc7c84 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x39067b46 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x38f5ff40 libsystem_c.dylib`abort + 108
    frame #3: 0x38f3f6ce libsystem_c.dylib`__assert_rtn + 302
    frame #4: 0x0003b676 ThaliTest`-[THEMultipeerClientSession onLinkFailure] + 290
    frame #5: 0x0003a836 ThaliTest`-[THEMultipeerPeerSession session:peer:didChangeState:] + 406
    frame #6: 0x29290272 MultipeerConnectivity`<redacted> + 118
    frame #7: 0x38ecfe2e libdispatch.dylib`<redacted> + 10
    frame #8: 0x38ed9fee libdispatch.dylib`<redacted> + 1762
    frame #9: 0x38ed2f86 libdispatch.dylib`<redacted> + 282
    frame #10: 0x38edb37c libdispatch.dylib`<redacted> + 400
    frame #11: 0x38edb1ea libdispatch.dylib`<redacted> + 94
    frame #12: 0x39064e0c libsystem_pthread.dylib`_pthread_wqthread + 1024
    frame #13: 0x390649fc libsystem_pthread.dylib`start_wqthread + 8

```
