#### Test 58380500055030c_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58380500055030c/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/5B3924E6-E21F-48C4-B9F4-31206C5D405A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/5B3924E6-E21F-48C4-B9F4-31206C5D405A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58380500055030c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58380500055030c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A6F88124-8026-4F48-98A1-5FEC7C47A758/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52162"
,(lldb)     command script import "/tmp/5B3924E6-E21F-48C4-B9F4-31206C5D405A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-08 23:31:31.818 ThaliTest[963:1646694] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2CF87A51-86BF-448C-8667-0C5BEF34AD41/Library/Cookies/Cookies.binarycookies
,2016-02-08 23:31:32.174 ThaliTest[963:1646694] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-08 23:31:32.175 ThaliTest[963:1646694] Multi-tasking -> Device: YES, App: YES
,2016-02-08 23:31:32.183 ThaliTest[963:1646694] Unlimited access to network resources
,2016-02-08 23:31:32.190 ThaliTest[963:1646694] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-08 23:31:42.043 ThaliTest[963:1646694] Resetting plugins due to page load.
,2016-02-08 23:31:45.896 ThaliTest[963:1646694] Finished load of: file:///var/mobile/Containers/Bundle/Application/A6F88124-8026-4F48-98A1-5FEC7C47A758/ThaliTest.app/www/index.html
,2016-02-08 23:31:46.060 ThaliTest[963:1646694] JXcore Cordova plugin initializing
,2016-02-08 23:31:46.061 ThaliTest[963:1646929] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A6F88124-8026-4F48-98A1-5FEC7C47A758/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A6F88124-8026-4F48-98A1-5FEC7C47A758/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A6F88124-8026-4F48-98A1-5FEC7C47A758/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A6F88124-8026-4F48-98A1-5FEC7C47A758/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A6F88124-8026-4F48-98A1-5FEC7C47A758/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A6F88124-8026-4F48-98A1-5FEC7C47A758/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A6F88124-8026-4F48-98A1-5FEC7C47A758/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A6F88124-8026-4F48-98A1-5FEC7C47A758/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A6F88124-8026-4F48-98A1-5FEC7C47A758/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# #generatePreambleAndBeacons empty keys to notify

,ok 1 should be equal

,# teardown

,# setup

# #generatePreambleAndBeacons multiple keys to notify

,ok 2 should be equal

ok 3 should be equal

,ok 4 should be equal

,ok 5 should be equal

,# teardown

,# setup

,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,ok 6 should throw

# teardown

,# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,ok 7 should throw

# teardown

,# setup

,# #parseBeacons no beacons returns null

,ok 8 should be equal

# teardown

,# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,ok 9 should throw

,# teardown

,# setup

# #parseBeacons addressBookCallback fails decrypt

,ok 10 should be equal

# teardown

,# setup

,# #parseBeacons addressBookCallback returns null for all

,ok 11 (unnamed assert)

,ok 12 should be equal

,# teardown

,# setup

# #parseBeacons addressBookCallback returns public key

,ok 13 (unnamed assert)

,ok 14 (unnamed assert)

# teardown

,# setup

# #parseBeacons with beacons both for and not for the user

,ok 15 (unnamed assert)

# teardown

,# setup

,# multiplex can send data

,ok 16 String should be length:200

,# teardown

,# setup

,# enqueue and run in order

,ok 17 firstPromise setTimeout

,ok 18 firstPromise result

,ok 19 firstPromise testValue

,ok 20 secondPromise setTimeout

,ok 21 secondPromise result

,ok 22 secondPromise testValue

,ok 23 thirdPromise in promise

,ok 24 thirdPromise result

,ok 25 thirdPromise testValue

,# teardown

,# setup

,# basic

,ok 26 sane

,# teardown

,# setup

,# another

,ok 27 sane

,# teardown

,# setup

,# successfully create a new pkcs12 file and return hash value

,ok 28 should be equal

,ok 29 null

,ok 30 (unnamed assert)

,ok 31 should be equal

,ok 32 should not throw

# teardown

,# setup

,# successfully read a previous pkcs12 file and return hash value

,ok 33 (unnamed assert)

,ok 34 (unnamed assert)

,ok 35 should not throw

,ok 36 should be equal

ok 37 should be equal

,# teardown

,# setup

,# failed to extract public key because of corrupt pkcs12 file

,ok 38 should be equal

,# teardown

,# setup

,# failed to get mobile documents path

,ok 39 should be equal

,# teardown

,# setup

,# #init should register the peerAvailabilityChanged event

,ok 40 should be equal

,ok 41 should be equal

,ok 42 should be equal

,# teardown

,# setup

,# #init should register the networkChanged event

,ok 43 should be equal

,# teardown

,# setup

,# #startBroadcasting should throw on null device name

,ok 44 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on empty string device name

,ok 45 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on non-number port

,ok 46 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on NaN port

,ok 47 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on negative port

,ok 48 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on too large port

,ok 49 should throw

,# teardown

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,ok 50 should be equal

,ok 51 should be equal

,ok 52 should be equal

,# teardown

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,ok 53 should be equal

,ok 54 should be equal

,ok 55 should be equal

,# teardown

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,ok 56 should be equal

,ok 57 should be equal

,# teardown
,
,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,ok 58 should be equal

,ok 59 should be equal

,# teardown

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,ok 60 should be equal

,ok 61 should be equal

,ok 62 should be equal

,# teardown

,# setup

,# #connect should call Mobile("Connect") and handle an error

,ok 63 should be equal

,ok 64 should be equal

,# teardown

,# setup

,# should call Mobile("Disconnect") without an error

,ok 65 should be equal

,ok 66 should be equal

,# teardown

,# setup

,# should call Mobile("Disconnect") and handle an error

,ok 67 should be equal

,ok 68 should be equal

,# teardown

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,2016-02-08 23:36:27.093 ThaliTest[963:1646929] jxcore: startBroadcasting
,2016-02-08 23:36:27.108 ThaliTest[963:1646929] server: starting 1454970987092.963.wFOU6Q==
,2016-02-08 23:36:27.110 ThaliTest[963:1646929] multipeer session: start timer: 0x195650a0
2016-02-08 23:36:27.111 ThaliTest[963:1646929] THEMultipeerSession initialized peer 1454970987092.963
,2016-02-08 23:36:27.115 ThaliTest[963:1646929] jxcore: startBroadcasting: success
,ok 69 Should be able to call startBroadcasting without error

,2016-02-08 23:36:27.122 ThaliTest[963:1646929] jxcore: stopBroadcasting
,2016-02-08 23:36:27.122 ThaliTest[963:1646929] THEMultipeerSession stopping peer
,2016-02-08 23:36:27.123 ThaliTest[963:1646929] multipeer session: stop timer
,2016-02-08 23:36:27.127 ThaliTest[963:1646929] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error

,2016-02-08 23:36:27.132 ThaliTest[963:1646929] jxcore: startBroadcasting
,2016-02-08 23:36:27.137 ThaliTest[963:1646929] server: starting 1454970987131.963.jgoIUw==
,2016-02-08 23:36:27.139 ThaliTest[963:1646929] multipeer session: start timer: 0x1948f590
,2016-02-08 23:36:27.141 ThaliTest[963:1646929] THEMultipeerSession initialized peer 1454970987131.963
,2016-02-08 23:36:27.145 ThaliTest[963:1646929] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error

,2016-02-08 23:36:27.149 ThaliTest[963:1646929] jxcore: stopBroadcasting
,2016-02-08 23:36:27.149 ThaliTest[963:1646929] THEMultipeerSession stopping peer
,2016-02-08 23:36:27.150 ThaliTest[963:1646929] multipeer session: stop timer
,2016-02-08 23:36:27.152 ThaliTest[963:1646929] jxcore: stopBroadcasting: success
,ok 72 Should be able to call stopBroadcasting without error

,2016-02-08 23:36:27.157 ThaliTest[963:1646929] jxcore: startBroadcasting
,2016-02-08 23:36:27.161 ThaliTest[963:1646929] server: starting 1454970987157.963.ZMeRLA==
,2016-02-08 23:36:27.163 ThaliTest[963:1646929] multipeer session: start timer: 0x19490330
,2016-02-08 23:36:27.167 ThaliTest[963:1646929] THEMultipeerSession initialized peer 1454970987157.963
,2016-02-08 23:36:27.170 ThaliTest[963:1646929] jxcore: startBroadcasting: success
,ok 73 Should be able to call startBroadcasting without error

,2016-02-08 23:36:27.173 ThaliTest[963:1646929] jxcore: stopBroadcasting
,2016-02-08 23:36:27.173 ThaliTest[963:1646929] THEMultipeerSession stopping peer
,2016-02-08 23:36:27.174 ThaliTest[963:1646929] multipeer session: stop timer
,2016-02-08 23:36:27.178 ThaliTest[963:1646929] jxcore: stopBroadcasting: success
,ok 74 Should be able to call stopBroadcasting without error

,2016-02-08 23:36:27.182 ThaliTest[963:1646929] jxcore: startBroadcasting
,2016-02-08 23:36:27.186 ThaliTest[963:1646929] server: starting 1454970987181.963.06Z5Pw==
,2016-02-08 23:36:27.187 ThaliTest[963:1646929] multipeer session: start timer: 0x19490310
,2016-02-08 23:36:27.191 ThaliTest[963:1646929] THEMultipeerSession initialized peer 1454970987181.963
,2016-02-08 23:36:27.192 ThaliTest[963:1646929] jxcore: startBroadcasting: success
,ok 75 Should be able to call startBroadcasting without error

,2016-02-08 23:36:27.194 ThaliTest[963:1646929] jxcore: stopBroadcasting
2016-02-08 23:36:27.194 ThaliTest[963:1646929] THEMultipeerSession stopping peer
,2016-02-08 23:36:27.195 ThaliTest[963:1646929] multipeer session: stop timer
,2016-02-08 23:36:27.196 ThaliTest[963:1646929] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,2016-02-08 23:36:27.200 ThaliTest[963:1646929] jxcore: startBroadcasting
,2016-02-08 23:36:27.202 ThaliTest[963:1646929] server: starting 1454970987199.963.QABnFQ==
,2016-02-08 23:36:27.203 ThaliTest[963:1646929] multipeer session: start timer: 0x186624d0
,2016-02-08 23:36:27.206 ThaliTest[963:1646929] THEMultipeerSession initialized peer 1454970987199.963
,2016-02-08 23:36:27.208 ThaliTest[963:1646929] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

,2016-02-08 23:36:27.210 ThaliTest[963:1646929] jxcore: stopBroadcasting
,2016-02-08 23:36:27.211 ThaliTest[963:1646929] THEMultipeerSession stopping peer
,2016-02-08 23:36:27.211 ThaliTest[963:1646929] multipeer session: stop timer
,2016-02-08 23:36:27.213 ThaliTest[963:1646929] jxcore: stopBroadcasting: success
,ok 78 Should be able to call stopBroadcasting without error

,2016-02-08 23:36:27.216 ThaliTest[963:1646929] jxcore: startBroadcasting
,2016-02-08 23:36:27.219 ThaliTest[963:1646929] server: starting 1454970987216.963.9d/Q2Q==
,2016-02-08 23:36:27.220 ThaliTest[963:1646929] multipeer session: start timer: 0x18663590
,2016-02-08 23:36:27.224 ThaliTest[963:1646929] THEMultipeerSession initialized peer 1454970987216.963
,2016-02-08 23:36:27.225 ThaliTest[963:1646929] jxcore: startBroadcasting: success
,ok 79 Should be able to call startBroadcasting without error

,2016-02-08 23:36:27.227 ThaliTest[963:1646929] jxcore: stopBroadcasting
,2016-02-08 23:36:27.228 ThaliTest[963:1646929] THEMultipeerSession stopping peer
,2016-02-08 23:36:27.228 ThaliTest[963:1646929] multipeer session: stop timer
,2016-02-08 23:36:27.230 ThaliTest[963:1646929] jxcore: stopBroadcasting: success
,ok 80 Should be able to call stopBroadcasting without error

,2016-02-08 23:36:27.233 ThaliTest[963:1646929] jxcore: startBroadcasting
,2016-02-08 23:36:27.236 ThaliTest[963:1646929] server: starting 1454970987233.963.VRAr5A==
,2016-02-08 23:36:27.237 ThaliTest[963:1646929] multipeer session: start timer: 0x18528f80
,2016-02-08 23:36:27.241 ThaliTest[963:1646929] THEMultipeerSession initialized peer 1454970987233.963
,2016-02-08 23:36:27.242 ThaliTest[963:1646929] jxcore: startBroadcasting: success
,ok 81 Should be able to call startBroadcasting without error

,2016-02-08 23:36:27.244 ThaliTest[963:1646929] jxcore: stopBroadcasting
,2016-02-08 23:36:27.245 ThaliTest[963:1646929] THEMultipeerSession stopping peer
,2016-02-08 23:36:27.246 ThaliTest[963:1646929] multipeer session: stop timer
,2016-02-08 23:36:27.248 ThaliTest[963:1646929] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,2016-02-08 23:36:27.250 ThaliTest[963:1646929] jxcore: startBroadcasting
,2016-02-08 23:36:27.253 ThaliTest[963:1646929] server: starting 1454970987250.963.YWThBQ==
,2016-02-08 23:36:27.254 ThaliTest[963:1646929] multipeer session: start timer: 0x18663850
,2016-02-08 23:36:27.257 ThaliTest[963:1646929] THEMultipeerSession initialized peer 1454970987250.963
,2016-02-08 23:36:27.259 ThaliTest[963:1646929] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error

,2016-02-08 23:36:27.261 ThaliTest[963:1646929] jxcore: stopBroadcasting
,2016-02-08 23:36:27.262 ThaliTest[963:1646929] THEMultipeerSession stopping peer
,2016-02-08 23:36:27.262 ThaliTest[963:1646929] multipeer session: stop timer
,2016-02-08 23:36:27.265 ThaliTest[963:1646929] jxcore: stopBroadcasting: success
,ok 84 Should be able to call stopBroadcasting without error

,2016-02-08 23:36:27.267 ThaliTest[963:1646929] jxcore: startBroadcasting
,2016-02-08 23:36:27.269 ThaliTest[963:1646929] server: starting 1454970987266.963.Z6Qh2g==
,2016-02-08 23:36:27.270 ThaliTest[963:1646929] multipeer session: start timer: 0x183b8db0
,2016-02-08 23:36:27.271 ThaliTest[963:1646929] THEMultipeerSession initialized peer 1454970987266.963
,2016-02-08 23:36:27.273 ThaliTest[963:1646929] jxcore: startBroadcasting: success
,ok 85 Should be able to call startBroadcasting without error

,2016-02-08 23:36:27.274 ThaliTest[963:1646929] jxcore: stopBroadcasting
,2016-02-08 23:36:27.275 ThaliTest[963:1646929] THEMultipeerSession stopping peer
,2016-02-08 23:36:27.275 ThaliTest[963:1646929] multipeer session: stop timer
,2016-02-08 23:36:27.277 ThaliTest[963:1646929] jxcore: stopBroadcasting: success
,ok 86 Should be able to call stopBroadcasting without error

,2016-02-08 23:36:27.279 ThaliTest[963:1646929] jxcore: startBroadcasting
,2016-02-08 23:36:27.280 ThaliTest[963:1646929] server: starting 1454970987278.963.bkJraQ==
,2016-02-08 23:36:27.282 ThaliTest[963:1646929] multipeer session: start timer: 0x19492320
,2016-02-08 23:36:27.284 ThaliTest[963:1646929] THEMultipeerSession initialized peer 1454970987278.963
,2016-02-08 23:36:27.285 ThaliTest[963:1646929] jxcore: startBroadcasting: success
,ok 87 Should be able to call startBroadcasting without error

,2016-02-08 23:36:27.286 ThaliTest[963:1646929] jxcore: stopBroadcasting
,2016-02-08 23:36:27.287 ThaliTest[963:1646929] THEMultipeerSession stopping peer
,2016-02-08 23:36:27.287 ThaliTest[963:1646929] multipeer session: stop timer
,2016-02-08 23:36:27.289 ThaliTest[963:1646929] jxcore: stopBroadcasting: success
,ok 88 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,2016-02-08 23:36:27.547 ThaliTest[963:1646929] jxcore: startBroadcasting
,2016-02-08 23:36:27.550 ThaliTest[963:1646929] server: starting 1454970987546.963.0Cke+A==
,2016-02-08 23:36:27.551 ThaliTest[963:1646929] multipeer session: start timer: 0x16620700
,2016-02-08 23:36:27.552 ThaliTest[963:1646929] THEMultipeerSession initialized peer 1454970987546.963
2016-02-08 23:36:27.552 ThaliTest[963:1646929] jxcore: startBroadcasting: success
,ok 89 Should be able to call startBroadcasting without error

2016-02-08 23:36:27.555 ThaliTest[963:1646929] jxcore: startBroadcasting
2016-02-08 23:36:27.556 ThaliTest[963:1646929] jxcore: startBroadcasting: failure
,ok 90 Cannot call startBroadcasting twice

,2016-02-08 23:36:27.560 ThaliTest[963:1646929] jxcore: stopBroadcasting
2016-02-08 23:36:27.561 ThaliTest[963:1646929] THEMultipeerSession stopping peer
2016-02-08 23:36:27.561 ThaliTest[963:1646929] multipeer session: stop timer
2016-02-08 23:36:27.562 ThaliTest[963:1646929] jxcore: stopBroadcasting: success
,ok 91 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter throws on connection to bad peer

,2016-02-08 23:36:28.015 ThaliTest[963:1646929] jxcore: startBroadcasting
,2016-02-08 23:36:28.018 ThaliTest[963:1646929] server: starting 1454970988014.963.u0TwPQ==
,2016-02-08 23:36:28.019 ThaliTest[963:1646929] multipeer session: start timer: 0x1938ff20
2016-02-08 23:36:28.020 ThaliTest[963:1646929] THEMultipeerSession initialized peer 1454970988014.963
2016-02-08 23:36:28.020 ThaliTest[963:1646929] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-08 23:36:28.023 ThaliTest[963:1646929] jxcore: connect foobar
2016-02-08 23:36:28.024 ThaliTest[963:1646929] client: unknown peer foobar
2016-02-08 23:36:28.024 ThaliTest[963:1646929] jxcore: connect: fail: Unknown peer
ok 93 Should not connect to a bad peer

,2016-02-08 23:36:28.028 ThaliTest[963:1646929] jxcore: stopBroadcasting
2016-02-08 23:36:28.028 ThaliTest[963:1646929] THEMultipeerSession stopping peer
,2016-02-08 23:36:28.028 ThaliTest[963:1646929] multipeer session: stop timer
,2016-02-08 23:36:28.030 ThaliTest[963:1646929] jxcore: stopBroadcasting: success
,ok 94 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,2016-02-08 23:36:28.110 ThaliTest[963:1646929] jxcore: startBroadcasting
,2016-02-08 23:36:28.113 ThaliTest[963:1646929] server: starting 1454970988109.963.PTQY6Q==
,2016-02-08 23:36:28.114 ThaliTest[963:1646929] multipeer session: start timer: 0x1855f930
2016-02-08 23:36:28.114 ThaliTest[963:1646929] THEMultipeerSession initialized peer 1454970988109.963
2016-02-08 23:36:28.115 ThaliTest[963:1646929] jxcore: startBroadcasting: success
,ok 95 Should be able to call startBroadcasting without error

2016-02-08 23:36:28.118 ThaliTest[963:1646929] jxcore: disconnect
2016-02-08 23:36:28.119 ThaliTest[963:1646929] jxcore: disconnect: fail
,ok 96 Disconnect should fail to a non-existant peer 

2016-02-08 23:36:28.122 ThaliTest[963:1646929] jxcore: stopBroadcasting
2016-02-08 23:36:28.123 ThaliTest[963:1646929] THEMultipeerSession stopping peer
2016-02-08 23:36:28.123 ThaliTest[963:1646929] multipeer session: stop timer
2016-02-08 23:36:28.123 ThaliTest[963:1646929] jxcore: stopBroadcasting: success
,ok 97 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter can discover and connect to peers

,2016-02-08 23:36:28.484 ThaliTest[963:1646929] jxcore: startBroadcasting
,2016-02-08 23:36:28.488 ThaliTest[963:1646929] server: starting 1454970988484.963.uK8uJQ==
,2016-02-08 23:36:28.489 ThaliTest[963:1646929] multipeer session: start timer: 0x19389310
,2016-02-08 23:36:28.490 ThaliTest[963:1646929] THEMultipeerSession initialized peer 1454970988484.963
,2016-02-08 23:36:28.490 ThaliTest[963:1646929] jxcore: startBroadcasting: success
ok 98 Should be able to call startBroadcasting without error

,2016-02-08 23:36:29.774 ThaliTest[963:1646694] client: found peer: 1454970987898.1509.hEBz8w==
,2016-02-08 23:36:29.776 ThaliTest[963:1646929] jxcore: connect 1454970987898.1509.hEBz8w==
,2016-02-08 23:36:29.777 ThaliTest[963:1646929] client session: connect
,2016-02-08 23:36:29.778 ThaliTest[963:1646929] client session: stateChange:0->1 1454970987898.1509.hEBz8w==
,2016-02-08 23:36:30.543 ThaliTest[963:1646694] multipeer session: reset timer
2016-02-08 23:36:30.544 ThaliTest[963:1646694] multipeer session: stop timer
,2016-02-08 23:36:30.544 ThaliTest[963:1646694] multipeer session: start timer: 0x19389310
,2016-02-08 23:36:30.545 ThaliTest[963:1646694] server session: connect
,2016-02-08 23:36:30.545 ThaliTest[963:1646694] server session: stateChange:0->1 1454970987898.1509
,2016-02-08 23:36:30.552 ThaliTest[963:1646694] server: accepting invitation 1454970987898.1509
,2016-02-08 23:36:32.645 ThaliTest[963:1647479] client session: connected
2016-02-08 23:36:32.646 ThaliTest[963:1647479] client session: stateChange:1->2 1454970987898.1509.hEBz8w==
,2016-02-08 23:36:32.652 ThaliTest[963:1647479] client session: fireConnectCallback: 1454970987898.1509.hEBz8w==
2016-02-08 23:36:32.652 ThaliTest[963:1647479] jxcore: connect: success
,ok 99 Should be able to connect without error

,ok 100 Port should be within range

,2016-02-08 23:36:32.659 ThaliTest[963:1646929] jxcore: disconnect
2016-02-08 23:36:32.659 ThaliTest[963:1646929] client session: disconnectFromPeer: 1454970987898.1509.hEBz8w==
,2016-02-08 23:36:32.660 ThaliTest[963:1646929] client session: disconnect
,2016-02-08 23:36:32.660 ThaliTest[963:1646929] client session: stateChange:2->0 1454970987898.1509.hEBz8w==
,2016-02-08 23:36:32.669 ThaliTest[963:1646929] jxcore: disconnect: success
ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# teardown

,2016-02-08 23:36:32.972 ThaliTest[963:1647526] server session: connected
,2016-02-08 23:36:32.973 ThaliTest[963:1647526] server session: stateChange:1->2 1454970987898.1509
,2016-02-08 23:36:32.977 ThaliTest[963:1646694] server relay: socket disconnected
2016-02-08 23:36:32.977 ThaliTest[963:1646694] server relay: 0x194972c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-08 23:36:33.032 ThaliTest[963:1647481] server session: not connected 1454970987898.1509
,calling stopBroadcasting

,2016-02-08 23:36:33.254 ThaliTest[963:1646929] jxcore: stopBroadcasting
,2016-02-08 23:36:33.254 ThaliTest[963:1646929] THEMultipeerSession stopping peer
2016-02-08 23:36:33.255 ThaliTest[963:1646929] multipeer session: stop timer
,2016-02-08 23:36:33.256 ThaliTest[963:1646929] server session: disconnect
,2016-02-08 23:36:33.256 ThaliTest[963:1646929] server session: stateChange:2->0 1454970987898.1509
,2016-02-08 23:36:33.259 ThaliTest[963:1646929] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,2016-02-08 23:36:33.329 ThaliTest[963:1646929] jxcore: startBroadcasting
,2016-02-08 23:36:33.332 ThaliTest[963:1646929] server: starting 1454970993328.963.0wLGOA==
,2016-02-08 23:36:33.333 ThaliTest[963:1646929] multipeer session: start timer: 0x19497240
2016-02-08 23:36:33.333 ThaliTest[963:1646929] THEMultipeerSession initialized peer 1454970993328.963
2016-02-08 23:36:33.333 ThaliTest[963:1646929] jxcore: startBr,oadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-02-08 23:36:34.117 ThaliTest[963:1646694] client: found peer: 1454970988484.963.uK8uJQ==
,2016-02-08 23:36:34.118 ThaliTest[963:1646694] client: found peer: 1454970987898.1509.hEBz8w==
,2016-02-08 23:36:34.120 ThaliTest[963:1646929] jxcore: connect 1454970988484.963.uK8uJQ==
,2016-02-08 23:36:34.121 ThaliTest[963:1646929] client session: connect
,2016-02-08 23:36:34.122 ThaliTest[963:1646929] client session: stateChange:0->1 1454970988484.963.uK8uJQ==
,2016-02-08 23:36:34.129 ThaliTest[963:1646929] jxcore: connect 1454970987898.1509.hEBz8w==
2016-02-08 23:36:34.130 ThaliTest[963:1646929] client session: connect
2016-02-08 23:36:34.130 ThaliTest[963:1646929] client session: stateChange:0->1 1454970987898.1509.hEBz8w==
,2016-02-08 23:36:34.378 ThaliTest[963:1646694] client: lost peer: 1454970988484.963.uK8uJQ==
2016-02-08 23:36:34.378 ThaliTest[963:1646694] client session: onPeerLost: 1454970988484.963.uK8uJQ==
2016-02-08 23:36:34.378 ThaliTest[963:1646694] client sessi,on: onLinkFailure: 1454970988484.963.uK8uJQ==
2016-02-08 23:36:34.379 ThaliTest[963:1646694] client session: disconnect
2016-02-08 23:36:34.379 ThaliTest[963:1646694] client session: stateChange:1->0 1454970988484.963.uK8uJQ==
,2016-02-08 23:36:34.379 ThaliTest[963:1646694] client session: fireConnectCallback: 1454970988484.963.uK8uJQ==
2016-02-08 23:36:34.380 ThaliTest[963:1646694] jxcore: connect: fail: Peer disconnected
,2016-02-08 23:36:35.390 ThaliTest[963:1646929] jxcore: connect 1454970988484.963.uK8uJQ==
2016-02-08 23:36:35.390 ThaliTest[963:1646929] client: connect: unreachable 1454970988484.963.uK8uJQ==
,2016-02-08 23:36:35.391 ThaliTest[963:1646929] jxcore: connect: fail: Peer unreachable
,2016-02-08 23:36:35.431 ThaliTest[963:1646694] client: found peer: 1454970992751.1509.ZxVHkA==
,2016-02-08 23:36:35.433 ThaliTest[963:1646929] jxcore: connect 1454970992751.1509.ZxVHkA==
2016-02-08 23:36:35.434 ThaliTest[963:1646929] client session: connect
2016-02-08 23:36:35.434 ThaliTest[963:1646929] client session: stateChange:0->1 1454970992751.1509.ZxVHkA==
,2016-02-08 23:36:35.538 ThaliTest[963:1646694] multipeer session: reset timer
2016-02-08 23:36:35.538 ThaliTest[963:1646694] multipeer session: stop timer
,2016-02-08 23:36:35.538 ThaliTest[963:1646694] multipeer session: start timer: 0x19497240
2016-02-08 23:36:35.539 ThaliTest[963:1646694] server session: connect
,2016-02-08 23:36:35.539 ThaliTest[963:1646694] server session: stateChange:0->1 1454970992751.1509
,2016-02-08 23:36:35.546 ThaliTest[963:1646694] server: accepting invitation 1454970992751.1509
,2016-02-08 23:36:37.567 ThaliTest[963:1646694] client: lost peer: 1454970987898.1509.hEBz8w==
2016-02-08 23:36:37.568 ThaliTest[963:1646694] client session: onPeerLost: 1454970987898.1509.hEBz8w==
,2016-02-08 23:36:37.568 ThaliTest[963:1646694] client session: onLinkFailure: 1454970987898.1509.hEBz8w==
2016-02-08 23:36:37.568 ThaliTest[963:1646694] client session: disconnect
,2016-02-08 23:36:37.568 ThaliTest[963:1646694] client session: stateChange:1->0 1454970987898.1509.hEBz8w==
2016-02-08 23:36:37.569 ThaliTest[963:1646694] client session: fireConnectCallback: 1454970987898.1509.hEBz8w==
,2016-02-08 23:36:37.570 ThaliTest[963:1646694] jxcore: connect: fail: Peer disconnected
,2016-02-08 23:36:37.971 ThaliTest[963:1647528] server session: connected
,2016-02-08 23:36:37.971 ThaliTest[963:1647528] server session: stateChange:1->2 1454970992751.1509
,2016-02-08 23:36:38.004 ThaliTest[963:1646694] server relay: socket disconnected
,2016-02-08 23:36:38.004 ThaliTest[963:1646694] server relay: 0x166befa0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection r,efused} 
,2016-02-08 23:36:38.099 ThaliTest[963:1647527] server session: not connected 1454970992751.1509
,2016-02-08 23:36:38.115 ThaliTest[963:1647528] client session: connected
2016-02-08 23:36:38.115 ThaliTest[963:1647528] client session: stateChange:1->2 1454970992751.1509.ZxVHkA==
,2016-02-08 23:36:38.161 ThaliTest[963:1647528] client session: fireConnectCallback: 1454970992751.1509.ZxVHkA==
2016-02-08 23:36:38.161 ThaliTest[963:1647528] jxcore: connect: success
,ok 103 Should be able to connect without error

,ok 104 Port should be within range

,2016-02-08 23:36:38.165 ThaliTest[963:1646929] jxcore: connect 1454970992751.1509.ZxVHkA==
,2016-02-08 23:36:38.166 ThaliTest[963:1646929] client: already connect(ing/ed) to 1454970992751.1509.ZxVHkA==
,2016-02-08 23:36:38.166 ThaliTest[963:1646929] jxcore: connect: fail: Aleady connecting
,ok 105 Should fail on double connect

,2016-02-08 23:36:38.170 ThaliTest[963:1646929] jxcore: disconnect
,2016-02-08 23:36:38.170 ThaliTest[963:1646929] client session: disconnectFromPeer: 1454970992751.1509.ZxVHkA==
,2016-02-08 23:36:38.171 ThaliTest[963:1646929] client session: disconnect
,2016-02-08 23:36:38.171 ThaliTest[963:1646929] client session: stateChange:2->0 1454970992751.1509.ZxVHkA==
,2016-02-08 23:36:38.246 ThaliTest[963:1646929] jxcore: disconnect: success
,ok 106 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# teardown

,calling stopBroadcasting

,2016-02-08 23:36:38.510 ThaliTest[963:1646929] jxcore: stopBroadcasting
,2016-02-08 23:36:38.511 ThaliTest[963:1646929] THEMultipeerSession stopping peer
2016-02-08 23:36:38.511 ThaliTest[963:1646929] multipeer session: stop timer
,2016-02-08 23:36:38.512 ThaliTest[963:1646929] server session: disconnect
,2016-02-08 23:36:38.512 ThaliTest[963:1646929] server session: stateChange:2->0 1454970992751.1509
,2016-02-08 23:36:38.639 ThaliTest[963:1646929] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,2016-02-08 23:36:38.920 ThaliTest[963:1646929] jxcore: startBroadcasting
,2016-02-08 23:36:38.922 ThaliTest[963:1646929] server: starting 1454970998920.963.poLk/Q==
,2016-02-08 23:36:38.923 ThaliTest[963:1646929] multipeer session: start timer: 0x166016a0
2016-02-08 23:36:38.923 ThaliTest[963:1646929] THEMultipeerSession initialized peer 1454970998920.963
2016-02-08 23:36:38.924 ThaliTest[963:1646929] jxcore: startBroadcasting: success
,ok 107 Should be able to call startBroadcasting without error

,2016-02-08 23:36:39.694 ThaliTest[963:1646694] client: found peer: 1454970992751.1509.ZxVHkA==
,2016-02-08 23:36:39.696 ThaliTest[963:1646929] jxcore: connect 1454970992751.1509.ZxVHkA==
2016-02-08 23:36:39.696 ThaliTest[963:1646929] client session: connect
2016-02-08 23:36:39.696 ThaliTest[963:1646929] client session: stateChange:0->1 1454970992751.1509.ZxVHkA==
,2016-02-08 23:36:40.210 ThaliTest[963:1646694] client: found peer: 1454970998347.1509.1R+vrA==
,2016-02-08 23:36:40.211 ThaliTest[963:1646929] jxcore: connect 1454970998347.1509.1R+vrA==
2016-02-08 23:36:40.212 ThaliTest[963:1646929] client session: connect
2016-02-08 23:36:40.212 ThaliTest[963:1646929] client session: stateChange:0->1 145497099834,7.1509.1R+vrA==
,2016-02-08 23:36:42.577 ThaliTest[963:1646694] multipeer session: reset timer
2016-02-08 23:36:42.578 ThaliTest[963:1646694] multipeer session: stop timer
2016-02-08 23:36:42.578 ThaliTest[963:1646694] multipeer session: start timer: 0x166016a0
2016-02-08 23:36:42.578 ThaliTest[963:1646694] server session: connect
2016-02-08 23:36:42.579 ThaliTest[963:1646694] server session: stateChange:0->1 1454970998347.1509
,2016-02-08 23:36:42.586 ThaliTest[963:1646694] server: accepting invitation 1454970998347.1509
,2016-02-08 23:36:43.050 ThaliTest[963:1647485] client session: connected
2016-02-08 23:36:43.050 ThaliTest[963:1647485] client session: stateChange:1->2 1454970998347.1509.1R+vrA==
,2016-02-08 23:36:43.202 ThaliTest[963:1647528] client session: fireConnectCallback: 1454970998347.1509.1R+vrA==
,2016-02-08 23:36:43.202 ThaliTest[963:1647528] jxcore: connect: success
,ok 108 Should be able to connect without error

,ok 109 Port should be within range

,2016-02-08 23:36:43.207 ThaliTest[963:1646929] jxcore: disconnect
,2016-02-08 23:36:43.208 ThaliTest[963:1646929] client session: disconnectFromPeer: 1454970998347.1509.1R+vrA==
2016-02-08 23:36:43.208 ThaliTest[963:1646929] client session: disconnect
2016-02-08 23:36:43.209 ThaliTest[963:1646929] client session: stateChange:2->0 1454970998347.1509.1R+vrA==
,2016-02-08 23:36:43.281 ThaliTest[963:1646929] jxcore: disconnect: success
,ok 110 Should be able to disconnect without error

,2016-02-08 23:36:43.284 ThaliTest[963:1646929] jxcore: disconnect
,2016-02-08 23:36:43.285 ThaliTest[963:1646929] jxcore: disconnect: fail
,ok 111 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# teardown

,2016-02-08 23:36:44.312 ThaliTest[963:1646694] client: lost peer: 1454970992751.1509.ZxVHkA==
2016-02-08 23:36:44.312 ThaliTest[963:1646694] client session: onPeerLost: 1454970992751.1509.ZxVHkA==
,2016-02-08 23:36:44.313 ThaliTest[963:1646694] client session: onLinkFailure: 1454970992751.1509.ZxVHkA==
,2016-02-08 23:36:44.313 ThaliTest[963:1646694] client session: disconnect
2016-02-08 23:36:44.313 ThaliTest[963:1646694] client session: stateChange:1->0 1454970992751.1509.ZxVHkA==
,2016-02-08 23:36:44.314 ThaliTest[963:1646694] client session: fireConnectCallback: 1454970992751.1509.ZxVHkA==
,2016-02-08 23:36:44.314 ThaliTest[963:1646694] jxcore: connect: fail: Peer disconnected
,2016-02-08 23:36:46.623 ThaliTest[963:1647479] server session: connected
2016-02-08 23:36:46.624 ThaliTest[963:1647479] server session: stateChange:1->2 1454970998347.1509
,2016-02-08 23:36:46.675 ThaliTest[963:1646694] server relay: socket disconnected
,2016-02-08 23:36:46.675 ThaliTest[963:1646694] server relay: 0x18591fd0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-08 23:36:46.687 ThaliTest[963:1647479] server session: not connected 1454970998347.1509
,calling stopBroadcasting

2016-02-08 23:36:46.881 ThaliTest[963:1646929] jxcore: stopBroadcasting
2016-02-08 23:36:46.881 ThaliTest[963:1646929] THEMultipeerSession stopping peer
,2016-02-08 23:36:46.881 ThaliTest[963:1646929] multipeer session: stop timer
,2016-02-08 23:36:46.883 ThaliTest[963:1646929] server session: disconnect
2016-02-08 23:36:46.883 ThaliTest[963:1646929] server session: stateChange:2->0 1454970998347.1509
,2016-02-08 23:36:47.932 ThaliTest[963:1646929] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can connect and send data

,echo server started on port: 54854

,2016-02-08 23:36:48.990 ThaliTest[963:1646929] jxcore: startBroadcasting
,2016-02-08 23:36:48.991 ThaliTest[963:1646929] server: starting 1454971008989.963.vzmIcg==
,2016-02-08 23:36:48.991 ThaliTest[963:1646929] multipeer session: start timer: 0x1948ebc0
2016-02-08 23:36:48.991 ThaliTest[963:1646929] THEMultipeerSession initialized peer 1454971008989.963
2016-02-08 23:36:48.992 ThaliTest[963:1646929] jxcore: startBr,oadcasting: success
ok 112 Should be able to call startBroadcasting without error

,2016-02-08 23:36:48.996 ThaliTest[963:1646694] client: found peer: 1454970998347.1509.1R+vrA==
,2016-02-08 23:36:48.996 ThaliTest[963:1646929] jxcore: connect 1454970998347.1509.1R+vrA==
2016-02-08 23:36:48.996 ThaliTest[963:1646929] client session: connect
2016-02-08 23:36:48.996 ThaliTest[963:1646929] client session: stateChange:0->1 1454970998347.1509.1R+vrA==
,2016-02-08 23:36:50.247 ThaliTest[963:1646694] multipeer session: reset timer
2016-02-08 23:36:50.247 ThaliTest[963:1646694] multipeer session: stop timer
2016-02-08 23:36:50.248 ThaliTest[963:1646694] multipeer session: start timer: 0x1948ebc0
2016-02-08 23:36:50.248 ThaliTest[963:1646694] server session: connect
2016-02-08 23:36:50.248 ThaliTest[963:1646694] server session: stateChange:0->1 1454971008469.1509
,2016-02-08 23:36:50.255 ThaliTest[963:1646694] server: accepting invitation 1454971008469.1509
,2016-02-08 23:36:50.263 ThaliTest[963:1646694] client: found peer: 1454971008469.1509.LeNrqg==
,2016-02-08 23:36:50.266 ThaliTest[963:1646929] jxcore: connect 1454971008469.1509.LeNrqg==
2016-02-08 23:36:50.266 ThaliTest[963:1646929] client session: connect
2016-02-08 23:36:50.267 ThaliTest[963:1646929] client session: stateChange:0->1 1454971008469.1509.LeNrqg==
,2016-02-08 23:36:52.913 ThaliTest[963:1647528] server session: connected
,2016-02-08 23:36:52.913 ThaliTest[963:1647528] server session: stateChange:1->2 1454971008469.1509
,2016-02-08 23:36:52.940 ThaliTest[963:1646694] server relay: connected (to port: 54854)
,2016-02-08 23:36:53.249 ThaliTest[963:1647528] server session: not connected 1454971008469.1509
,2016-02-08 23:36:54.759 ThaliTest[963:1647485] client session: connected
2016-02-08 23:36:54.759 ThaliTest[963:1647485] client session: stateChange:1->2 1454971008469.1509.LeNrqg==
,2016-02-08 23:36:54.974 ThaliTest[963:1647628] client session: fireConnectCallback: 1454971008469.1509.LeNrqg==
2016-02-08 23:36:54.974 ThaliTest[963:1647628] jxcore: connect: success
,ok 113 Should be able to connect without error

,ok 114 Port should be within range

,2016-02-08 23:36:54.979 ThaliTest[963:1646694] client: relay established
2016-02-08 23:36:54.980 ThaliTest[963:1646694] client: new accepted socket: 0x166aa560
,data in 1095

,data in 26280

,data in 27375

,data in 28470

,data in 32850

,data in 39420

,data in 49275

,data in 60225

,data in 74460

,data in 91980

,data in 101835

,data in 112785

,data in 113880

,data in 118260

,data in 131072

,ok 115 the test messages should be equal

,2016-02-08 23:36:56.518 ThaliTest[963:1646929] jxcore: disconnect
,2016-02-08 23:36:56.518 ThaliTest[963:1646929] client session: disconnectFromPeer: 1454971008469.1509.LeNrqg==
,2016-02-08 23:36:56.519 ThaliTest[963:1646929] client session: disconnect
2016-02-08 23:36:56.519 ThaliTest[963:1646929] client session: stateChange:2->0 1454971008469.1509.LeNrqg==
,2016-02-08 23:36:56.529 ThaliTest[963:1646929] jxcore: disconnect: success
,ok 116 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# teardown

,calling stopBroadcasting

,2016-02-08 23:36:56.883 ThaliTest[963:1646929] jxcore: stopBroadcasting
,2016-02-08 23:36:56.883 ThaliTest[963:1646929] THEMultipeerSession stopping peer
,2016-02-08 23:36:56.884 ThaliTest[963:1646929] multipeer session: stop timer
,2016-02-08 23:36:56.885 ThaliTest[963:1646929] client session: disconnect
2016-02-08 23:36:56.885 ThaliTest[963:1646929] client session: stateChange:1->0 1454970998347.1509.1R+vrA==
2016-02-08 23:36:56.886 ThaliTest[963:1646929] server session: disconnec,t
2016-02-08 23:36:56.886 ThaliTest[963:1646929] server session: stateChange:2->0 1454971008469.1509
,2016-02-08 23:36:56.892 ThaliTest[963:1646929] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter handles socket disconnect correctly

,echo server started on port: 54863

,2016-02-08 23:36:57.388 ThaliTest[963:1646929] jxcore: startBroadcasting
,2016-02-08 23:36:57.392 ThaliTest[963:1646929] server: starting 1454971017387.963.XB3jRg==
,2016-02-08 23:36:57.393 ThaliTest[963:1646929] multipeer session: start timer: 0x16743030
2016-02-08 23:36:57.393 ThaliTest[963:1646929] THEMultipeerSession initialized peer 1454971017387.963
,2016-02-08 23:36:57.394 ThaliTest[963:1646929] jxcore: startBroadcasting: success
,ok 117 Should be able to call startBroadcasting without error

,2016-02-08 23:36:58.119 ThaliTest[963:1646694] client: found peer: 1454970998347.1509.1R+vrA==
,2016-02-08 23:36:58.120 ThaliTest[963:1646694] client: found peer: 1454971008469.1509.LeNrqg==
[{"peerIdentifier":"1454970998347.1509.1R+vrA==","peerName":"(null)","peerAvailable":true}]

,2016-02-08 23:36:58.122 ThaliTest[963:1646929] jxcore: connect 1454970998347.1509.1R+vrA==
2016-02-08 23:36:58.123 ThaliTest[963:1646929] client session: connect
2016-02-08 23:36:58.123 ThaliTest[963:1646929] client session: stateChange:0->1 1454970998347.1509.1R+vrA==
,[{"peerIdentifier":"1454971008469.1509.LeNrqg==","peerName":"(null)","peerAvailable":true}]

,2016-02-08 23:36:58.133 ThaliTest[963:1646929] jxcore: connect 1454971008469.1509.LeNrqg==
,2016-02-08 23:36:58.133 ThaliTest[963:1646929] client session: connect
,2016-02-08 23:36:58.134 ThaliTest[963:1646929] client session: stateChange:0->1 1454971008469.1509.LeNrqg==
,2016-02-08 23:36:58.486 ThaliTest[963:1646694] client: lost peer: 1454971008469.1509.LeNrqg==
2016-02-08 23:36:58.486 ThaliTest[963:1646694] client session: onPeerLost: 1454971008469.1509.LeNrqg==
2016-02-08 23:36:58.486 ThaliTest[963:1646694] client ses,sion: onLinkFailure: 1454971008469.1509.LeNrqg==
,2016-02-08 23:36:58.487 ThaliTest[963:1646694] client session: disconnect
2016-02-08 23:36:58.487 ThaliTest[963:1646694] client session: stateChange:1->0 1454971008469.1509.LeNrqg==
,2016-02-08 23:36:58.488 ThaliTest[963:1646694] client session: fireConnectCallback: 1454971008469.1509.LeNrqg==
2016-02-08 23:36:58.488 ThaliTest[963:1646694] jxcore: connect: fail: Peer disconnected
,[{"peerIdentifier":"1454971008469.1509.LeNrqg==","peerName":"(null)","peerAvailable":false}]

,2016-02-08 23:36:58.537 ThaliTest[963:1646694] client: found peer: 1454971016808.1509.5Fr2Vw==
,[{"peerIdentifier":"1454971016808.1509.5Fr2Vw==","peerName":"(null)","peerAvailable":true}]

,2016-02-08 23:36:58.539 ThaliTest[963:1646929] jxcore: connect 1454971016808.1509.5Fr2Vw==
,2016-02-08 23:36:58.539 ThaliTest[963:1646929] client session: connect
,2016-02-08 23:36:58.540 ThaliTest[963:1646929] client session: stateChange:0->1 1454971016808.1509.5Fr2Vw==
,2016-02-08 23:36:58.673 ThaliTest[963:1646694] multipeer session: reset timer
2016-02-08 23:36:58.673 ThaliTest[963:1646694] multipeer session: stop timer
2016-02-08 23:36:58.674 ThaliTest[963:1646694] multipeer session: start timer: 0x16743030
2016-02-,08 23:36:58.674 ThaliTest[963:1646694] server session: connect
2016-02-08 23:36:58.674 ThaliTest[963:1646694] server session: stateChange:0->1 1454971016808.1509
,2016-02-08 23:36:58.681 ThaliTest[963:1646694] server: accepting invitation 1454971016808.1509
,2016-02-08 23:36:59.500 ThaliTest[963:1646929] jxcore: connect 1454971008469.1509.LeNrqg==
,2016-02-08 23:36:59.500 ThaliTest[963:1646929] client: connect: unreachable 1454971008469.1509.LeNrqg==
,2016-02-08 23:36:59.501 ThaliTest[963:1646929] jxcore: connect: fail: Peer unreachable
,2016-02-08 23:37:01.297 ThaliTest[963:1647479] server session: connected
2016-02-08 23:37:01.297 ThaliTest[963:1647479] server session: stateChange:1->2 1454971016808.1509
,2016-02-08 23:37:01.305 ThaliTest[963:1646694] server relay: connected (to port: 54863)
,2016-02-08 23:37:01.423 ThaliTest[963:1647528] client session: connected
,2016-02-08 23:37:01.424 ThaliTest[963:1647528] client session: stateChange:1->2 1454971016808.1509.5Fr2Vw==
,2016-02-08 23:37:01.432 ThaliTest[963:1647479] client session: fireConnectCallback: 1454971016808.1509.5Fr2Vw==
2016-02-08 23:37:01.433 ThaliTest[963:1647479] jxcore: connect: success
,ok 118 Should be able to connect without error

,ok 119 Port should be within range

,ok 120 First connect should succeed

,2016-02-08 23:37:01.494 ThaliTest[963:1646694] client: relay established
2016-02-08 23:37:01.494 ThaliTest[963:1646694] client: new accepted socket: 0x190969e0
,2016-02-08 23:37:01.533 ThaliTest[963:1647479] server session: not connected 1454971016808.1509
,ok 121 the test messages should be equal

,ok 122 First send should succeed

,2016-02-08 23:37:01.600 ThaliTest[963:1646694] client: socket closed
,2016-02-08 23:37:01.600 ThaliTest[963:1646694] client relay: socket disconnected
,2016-02-08 23:37:01.601 ThaliTest[963:1646694] client relay: 0x190969e0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-08 23:37:01.601 ThaliTest[963:1646694] client session: socket closed: 1454971016808.1509.5Fr2Vw==
,2016-02-08 23:37:01.602 ThaliTest[963:1646694] client session: onLinkFailure: 1454971016808.1509.5Fr2Vw==
2016-02-08 23:37:01.602 ThaliTest[963:1646694] client session: disconnect
2016-02-08 23:37:01.602 ThaliTest[963:1646694] client session: stateChange:2->0 1454971016808.1509.5Fr2Vw==
,2016-02-08 23:37:01.615 ThaliTest[963:1646694] client session: fireConnectionErrorEvent: 1454971016808.1509.5Fr2Vw==
,2016-02-08 23:37:01.620 ThaliTest[963:1646929] jxcore: connect 1454971016808.1509.5Fr2Vw==
,2016-02-08 23:37:01.623 ThaliTest[963:1646694] multipeer session: reset timer
,2016-02-08 23:37:01.624 ThaliTest[963:1646694] multipeer session: stop timer
2016-02-08 23:37:01.624 ThaliTest[963:1646694] multipeer session: start timer: 0x16743030
,2016-02-08 23:37:01.622 ThaliTest[963:1646929] client session: connect
,2016-02-08 23:37:01.625 ThaliTest[963:1646694] server: disconnecting to refresh session (1454971016808.1509)
,2016-02-08 23:37:01.626 ThaliTest[963:1646694] server session: disconnect
,2016-02-08 23:37:01.628 ThaliTest[963:1646694] server session: stateChange:2->0 1454971016808.1509
2016-02-08 23:37:01.627 ThaliTest[963:1646929] client session: stateChange:0->1 1454971016808.1509.5Fr2Vw==
,2016-02-08 23:37:01.635 ThaliTest[963:1646694] server session: connect
2016-02-08 23:37:01.635 ThaliTest[963:1646694] server session: stateChange:0->1 1454971016808.1509
,2016-02-08 23:37:01.653 ThaliTest[963:1646694] server: accepting invitation 1454971016808.1509
,2016-02-08 23:37:04.371 ThaliTest[963:1647485] server session: connected
2016-02-08 23:37:04.371 ThaliTest[963:1647485] server session: stateChange:1->2 1454971016808.1509
,2016-02-08 23:37:04.379 ThaliTest[963:1646694] server relay: connected (to port: 54863)
,2016-02-08 23:37:04.542 ThaliTest[963:1647527] server session: not connected 1454971016808.1509
,2016-02-08 23:37:04.625 ThaliTest[963:1647527] client session: connected
2016-02-08 23:37:04.626 ThaliTest[963:1647527] client session: stateChange:1->2 1454971016808.1509.5Fr2Vw==
,2016-02-08 23:37:04.629 ThaliTest[963:1647527] client session: fireConnectCallback: 1454971016808.1509.5Fr2Vw==
2016-02-08 23:37:04.629 ThaliTest[963:1647527] jxcore: connect: success
,ok 123 Should be able to connect without error

,ok 124 Port should be within range

,ok 125 Second connect should succeed

,2016-02-08 23:37:04.664 ThaliTest[963:1646694] client: relay established
2016-02-08 23:37:04.664 ThaliTest[963:1646694] client: new accepted socket: 0x183c6380
,2016-02-08 23:37:04.713 ThaliTest[963:1646694] client: lost peer: 1454970998347.1509.1R+vrA==
,2016-02-08 23:37:04.714 ThaliTest[963:1646694] client session: onPeerLost: 1454970998347.1509.1R+vrA==
,2016-02-08 23:37:04.714 ThaliTest[963:1646694] client session: onLinkFailure: 1454970998347.1509.1R+vrA==
2016-02-08 23:37:04.714 ThaliTest[963:1646694] client session: disconnect
2016-02-08 23:37:04.714 ThaliTest[963:1646694] client session: stateChange,:1->0 1454970998347.1509.1R+vrA==
2016-02-08 23:37:04.715 ThaliTest[963:1646694] client session: fireConnectCallback: 1454970998347.1509.1R+vrA==
2016-02-08 23:37:04.716 ThaliTest[963:1646694] jxcore: connect: fail: Peer disconnected
,[{"peerIdentifier":"1454970998347.1509.1R+vrA==","peerName":"(null)","peerAvailable":false}]

,ok 126 the test messages should be equal

,ok 127 Second send should succeed

,# teardown

,2016-02-08 23:37:04.765 ThaliTest[963:1646694] client: socket closed
,2016-02-08 23:37:04.766 ThaliTest[963:1646694] client relay: socket disconnected
,2016-02-08 23:37:04.766 ThaliTest[963:1646694] client relay: 0x183c6380 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-08 23:37:0,4.766 ThaliTest[963:1646694] client session: socket closed: 1454971016808.1509.5Fr2Vw==
2016-02-08 23:37:04.767 ThaliTest[963:1646694] client session: onLinkFailure: 1454971016808.1509.5Fr2Vw==
2016-02-08 23:37:04.767 ThaliTest[963:1646694] client sessio,n: disconnect
2016-02-08 23:37:04.767 ThaliTest[963:1646694] client session: stateChange:2->0 1454971016808.1509.5Fr2Vw==
,2016-02-08 23:37:04.778 ThaliTest[963:1646694] client session: fireConnectionErrorEvent: 1454971016808.1509.5Fr2Vw==
,calling stopBroadcasting

2016-02-08 23:37:04.795 ThaliTest[963:1646929] jxcore: stopBroadcasting
2016-02-08 23:37:04.796 ThaliTest[963:1646929] THEMultipeerSession stopping peer
2016-02-08 23:37:04.796 ThaliTest[963:1646929] multipeer session: stop timer
2016-02-08 23:37:04.797 ThaliTest[963:1646929] server session: disconnect
,2016-02-08 23:37:04.797 ThaliTest[963:1646929] server session: stateChange:2->0 1454971016808.1509
,2016-02-08 23:37:04.886 ThaliTest[963:1646929] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# setup

,# ThaliReplicationManager can call start without error

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/2CF87A51-86BF-448C-8667-0C5BEF34AD41/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 128 starting event should occur in right order

,2016-02-08 23:37:05.434 ThaliTest[963:1646929] jxcore: startBroadcasting
,2016-02-08 23:37:05.437 ThaliTest[963:1646929] server: starting MO4x_LoLvtLb1O_NXKa3eQ.8kNPSg==
,2016-02-08 23:37:05.437 ThaliTest[963:1646929] multipeer session: start timer: 0x16786c10
2016-02-08 23:37:05.437 ThaliTest[963:1646929] THEMultipeerSession initialized peer MO4x_LoLvtLb1O_NXKa3eQ
2016-02-08 23:37:05.437 ThaliTest[963:1646929] jxcore: startBroadcasting: success
,ok 129 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 130 stopping event should occur in right order

About to call stopBroadcasting

,2016-02-08 23:37:05.439 ThaliTest[963:1646929] jxcore: stopBroadcasting
2016-02-08 23:37:05.439 ThaliTest[963:1646929] THEMultipeerSession stopping peer
2016-02-08 23:37:05.439 ThaliTest[963:1646929] multipeer session: stop timer
2016-02-08 23:37:05.439 ThaliTest[963:1646929] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,ok 131 stopped event should occur in right order

,mux server bridge listener closed

# teardown

,# setup

,# ThaliReplicationManager receives identity

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/2CF87A51-86BF-448C-8667-0C5BEF34AD41/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-08 23:37:05.719 ThaliTest[963:1646929] jxcore: connect 1454970998347.1509.1R+vrA==
2016-02-08 23:37:05.719 ThaliTest[963:1646929] Communications not enabled
,2016-02-08 23:37:05.719 ThaliTest[963:1646929] jxcore: connect: fail: app: Not initialised
,2016-02-08 23:37:05.738 ThaliTest[963:1646929] jxcore: startBroadcasting
,2016-02-08 23:37:05.740 ThaliTest[963:1646929] server: starting MO4x_LoLvtLb1O_NXKa3eQ.rxOMEA==
,2016-02-08 23:37:05.740 ThaliTest[963:1646929] multipeer session: start timer: 0x166ef4a0
,2016-02-08 23:37:05.741 ThaliTest[963:1646929] THEMultipeerSession initialized peer MO4x_LoLvtLb1O_NXKa3eQ
2016-02-08 23:37:05.741 ThaliTest[963:1646929] jxcore: startBroadcasting: success
ok 132 getDeviceIdentity should not return an error

,ok 133 deviceName should not be null

Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

2016-02-08 23:37:05.744 ThaliTest[963:1646929] jxcore: stopBroadcasting
,2016-02-08 23:37:05.744 ThaliTest[963:1646929] THEMultipeerSession stopping peer
,2016-02-08 23:37:05.745 ThaliTest[963:1646929] multipeer session: stop timer
,2016-02-08 23:37:05.746 ThaliTest[963:1646929] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# teardown

,# setup

,# ThaliReplicationManager replicates database

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/2CF87A51-86BF-448C-8667-0C5BEF34AD41/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-08 23:37:07.836 ThaliTest[963:1646929] jxcore: connect 1454970998347.1509.1R+vrA==
,2016-02-08 23:37:07.837 ThaliTest[963:1646929] Communications not enabled
2016-02-08 23:37:07.837 ThaliTest[963:1646929] jxcore: connect: fail: app: Not initialised
,2016-02-08 23:37:07.896 ThaliTest[963:1646929] jxcore: startBroadcasting
,2016-02-08 23:37:07.897 ThaliTest[963:1646929] server: starting MO4x_LoLvtLb1O_NXKa3eQ.yeJseg==
,2016-02-08 23:37:07.898 ThaliTest[963:1646929] multipeer session: start timer: 0x1662e490
2016-02-08 23:37:07.898 ThaliTest[963:1646929] THEMultipeerSession initialized peer MO4x_LoLvtLb1O_NXKa3eQ
2016-02-08 23:37:07.898 ThaliTest[963:1646929] jxcore: startBroadcasting: success
,ok 134 getDeviceIdentity should not return an error

ok 135 deviceName should not be null

,2016-02-08 23:37:09.057 ThaliTest[963:1646694] client: found peer: 8cjLUaU3CP8-JFk3KuK_lQ.OaQSEw==
,2016-02-08 23:37:11.921 ThaliTest[963:1646929] jxcore: connect 1454970998347.1509.1R+vrA==
,2016-02-08 23:37:11.922 ThaliTest[963:1646929] client: unknown peer 1454970998347.1509.1R+vrA==
2016-02-08 23:37:11.922 ThaliTest[963:1646929] jxcore: connect: fail: Unknown peer
,2016-02-08 23:37:11.947 ThaliTest[963:1646929] jxcore: connect 8cjLUaU3CP8-JFk3KuK_lQ.OaQSEw==
,2016-02-08 23:37:11.947 ThaliTest[963:1646929] client session: connect
2016-02-08 23:37:11.947 ThaliTest[963:1646929] client session: stateChange:0->1 8cjLUaU3CP8-JFk3KuK_lQ.OaQSEw==
,ok 136 Should be able to put doc without error

,ok 137 1st change of local doc should contain local id

,2016-02-08 23:37:12.625 ThaliTest[963:1646694] multipeer session: reset timer
2016-02-08 23:37:12.626 ThaliTest[963:1646694] multipeer session: stop timer
2016-02-08 23:37:12.626 ThaliTest[963:1646694] multipeer session: start timer: 0x1662e490
,2016-02-08 23:37:12.626 ThaliTest[963:1646694] server session: connect
2016-02-08 23:37:12.627 ThaliTest[963:1646694] server session: stateChange:0->1 8cjLUaU3CP8-JFk3KuK_lQ
,2016-02-08 23:37:12.634 ThaliTest[963:1646694] server: accepting invitation 8cjLUaU3CP8-JFk3KuK_lQ
,2016-02-08 23:37:12.924 ThaliTest[963:1646929] jxcore: connect 1454970998347.1509.1R+vrA==
2016-02-08 23:37:12.924 ThaliTest[963:1646929] client: unknown peer 1454970998347.1509.1R+vrA==
2016-02-08 23:37:12.925 ThaliTest[963:1646929] jxcore: connect: fail: Unknown peer
,2016-02-08 23:37:13.937 ThaliTest[963:1646929] jxcore: connect 1454970998347.1509.1R+vrA==
,2016-02-08 23:37:13.938 ThaliTest[963:1646929] client: unknown peer 1454970998347.1509.1R+vrA==
,2016-02-08 23:37:13.938 ThaliTest[963:1646929] jxcore: connect: fail: Unknown peer
,2016-02-08 23:37:14.948 ThaliTest[963:1646929] jxcore: connect 1454970998347.1509.1R+vrA==
,2016-02-08 23:37:14.949 ThaliTest[963:1646929] client: unknown peer 1454970998347.1509.1R+vrA==
,2016-02-08 23:37:14.949 ThaliTest[963:1646929] jxcore: connect: fail: Unknown peer
,2016-02-08 23:37:15.244 ThaliTest[963:1647628] client session: connected
2016-02-08 23:37:15.245 ThaliTest[963:1647628] client session: stateChange:1->2 8cjLUaU3CP8-JFk3KuK_lQ.OaQSEw==
,2016-02-08 23:37:15.252 ThaliTest[963:1647628] server session: connected
2016-02-08 23:37:15.252 ThaliTest[963:1647628] server session: stateChange:1->2 8cjLUaU3CP8-JFk3KuK_lQ
,2016-02-08 23:37:15.262 ThaliTest[963:1647677] client session: fireConnectCallback: 8cjLUaU3CP8-JFk3KuK_lQ.OaQSEw==
2016-02-08 23:37:15.262 ThaliTest[963:1647677] jxcore: connect: success
,2016-02-08 23:37:15.275 ThaliTest[963:1646694] client: relay established
2016-02-08 23:37:15.275 ThaliTest[963:1646694] client: new accepted socket: 0x1877d490
,2016-02-08 23:37:15.304 ThaliTest[963:1646694] server relay: connected (to port: 54883)
,server bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,2016-02-08 23:37:15.977 ThaliTest[963:1646929] jxcore: connect 1454970998347.1509.1R+vrA==
,2016-02-08 23:37:15.978 ThaliTest[963:1646929] client: unknown peer 1454970998347.1509.1R+vrA==
,2016-02-08 23:37:15.978 ThaliTest[963:1646929] jxcore: connect: fail: Unknown peer
,client bridge: new client socket

,client bridge: socket closed

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

,2016-02-08 23:37:16.988 ThaliTest[963:1646929] jxcore: connect 1454970998347.1509.1R+vrA==
2016-02-08 23:37:16.989 ThaliTest[963:1646929] client: unknown peer 1454970998347.1509.1R+vrA==
,2016-02-08 23:37:16.989 ThaliTest[963:1646929] jxcore: connect: fail: Unknown peer
,2016-02-08 23:37:17.052 ThaliTest[963:1646694] client: found peer: 1454970998347.1509.1R+vrA==
,2016-02-08 23:37:17.054 ThaliTest[963:1646929] jxcore: connect 1454970998347.1509.1R+vrA==
2016-02-08 23:37:17.054 ThaliTest[963:1646929] client session: connect
,2016-02-08 23:37:17.054 ThaliTest[963:1646929] client session: stateChange:0->1 1454970998347.1509.1R+vrA==
,client bridge: socket closed

,client bridge: new client socket
,
,2016-02-08 23:37:18.030 ThaliTest[963:1646929] jxcore: connect 1454970998347.1509.1R+vrA==
,2016-02-08 23:37:18.031 ThaliTest[963:1646929] client: already connect(ing/ed) to 1454970998347.1509.1R+vrA==
2016-02-08 23:37:18.031 ThaliTest[963:1646929] jxcore: connect: fail: Aleady connecting
,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,not ok 138 First connect should succeed

  ---

,    operator: ok

,    expected: true

,    actual:   false

  ...

,not ok 139 .end() called twice

,  ---

    operator: fail

,  ...

,client bridge: socket closed

,ok 140 1st change of remote doc should contain remote id

,ok 141 Can update remote doc without error

null

,{ ok: true,
  id: 'deec06ab-2872-4b4f-bce4-711c75646441',
  rev: '2-7a8735f2c69458305e20eca92e569f69' }

,client bridge: new client socket

,ok 142 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,2016-02-08 23:37:20.946 ThaliTest[963:1646694] client: lost peer: 1454970998347.1509.1R+vrA==
2016-02-08 23:37:20.947 ThaliTest[963:1646694] client session: onPeerLost: 1454970998347.1509.1R+vrA==
2016-02-08 23:37:20.947 ThaliTest[963:1646694] client ses,sion: onLinkFailure: 1454970998347.1509.1R+vrA==
2016-02-08 23:37:20.947 ThaliTest[963:1646694] client session: disconnect
2016-02-08 23:37:20.948 ThaliTest[963:1646694] client session: stateChange:1->0 1454970998347.1509.1R+vrA==
,2016-02-08 23:37:20.948 ThaliTest[963:1646694] client session: fireConnectCallback: 1454970998347.1509.1R+vrA==
2016-02-08 23:37:20.948 ThaliTest[963:1646694] jxcore: connect: fail: Peer disconnected
,Connect error with error: Error: Peer disconnected

,2016-02-08 23:37:20.977 ThaliTest[963:1646929] jxcore: disconnect
2016-02-08 23:37:20.978 ThaliTest[963:1646929] jxcore: disconnect: fail
,Disconnect error with error: Error: Not connected to specified peer

peerIdentifier not available 1454970998347.1509.1R+vrA==

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,ok 143 Local changes occur in strict order

,ok 144 2nd change of local doc should contain remote id

,# teardown

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

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

2016-02-08 23:37:26.221 ThaliTest[963:1646929] jxcore: stopBroadcasting
2016-02-08 23:37:26.222 ThaliTest[963:1646929] THEMultipeerSession stopping peer
2016-02-08 23:37:26.222 ThaliTest[963:1646929] multipeer session: stop timer
2016-02-08 23:37:26.222 ThaliTest[963:1646929] client session: disconnect
,2016-02-08 23:37:26.222 ThaliTest[963:1646929] client session: stateChange:2->0 8cjLUaU3CP8-JFk3KuK_lQ.OaQSEw==
,2016-02-08 23:37:26.254 ThaliTest[963:1647479] server session: not connected 8cjLUaU3CP8-JFk3KuK_lQ
,2016-02-08 23:37:26.265 ThaliTest[963:1646929] server session: disconnect
2016-02-08 23:37:26.265 ThaliTest[963:1646929] server session: stateChange:2->0 8cjLUaU3CP8-JFk3KuK_lQ
,2016-02-08 23:37:26.270 ThaliTest[963:1646929] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,# setup

,client bridge: socket closed

,mux server bridge listener closed

,2016-02-08 23:37:26.316 ThaliTest[963:1646929] Error!: connect ECONNREFUSED
Stack:[{"_fileName":"net.js","_functionName":"$c","_lineNumber":"837","_columnNumber":"7","_msg":"    at $c@net.js:837:7"},{"_fileName":"net.js","_functionName":"$09","_lineNumber":"829","_columnNumber":"13","_msg":"    at $09@net.js:829:13"},{"_fileName":"net.js","_functionName":"unknown","_lineNumber":"837","_columnNumber":"7","_msg":""}]
Uncaught Exception: Error: connect ECONNREFUSED

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
    _functionName: 'unknown',
    _lineNumber: '837',
    _columnNumber: '7',
    _msg: '' },
  toString: [Function] ]

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****


```
