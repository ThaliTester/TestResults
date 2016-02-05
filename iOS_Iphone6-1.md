#### Test 58497659c9ea290_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58497659c9ea290/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/E8C5DB1D-FC4D-43FC-9E47-D15F9561D38C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/E8C5DB1D-FC4D-43FC-9E47-D15F9561D38C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58497659c9ea290/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58497659c9ea290/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/74DCCE77-2675-47FF-A40A-4FB5B3089AA1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51039"
,(lldb)     command script import "/tmp/E8C5DB1D-FC4D-43FC-9E47-D15F9561D38C/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-06 00:26:18.988 ThaliTest[1334:2411338] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/989DA9F1-F2FB-449A-A968-CC1B80530830/Library/Cookies/Cookies.binarycookies
,2016-02-06 00:26:19.416 ThaliTest[1334:2411338] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-06 00:26:19.418 ThaliTest[1334:2411338] Multi-tasking -> Device: YES, App: YES
,2016-02-06 00:26:19.428 ThaliTest[1334:2411338] Unlimited access to network resources
,2016-02-06 00:26:19.442 ThaliTest[1334:2411338] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-06 00:26:29.102 ThaliTest[1334:2411338] Resetting plugins due to page load.
,2016-02-06 00:26:32.733 ThaliTest[1334:2411338] Finished load of: file:///var/mobile/Containers/Bundle/Application/74DCCE77-2675-47FF-A40A-4FB5B3089AA1/ThaliTest.app/www/index.html
,2016-02-06 00:26:32.924 ThaliTest[1334:2411338] JXcore Cordova plugin initializing
2016-02-06 00:26:32.924 ThaliTest[1334:2411577] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74DCCE77-2675-47FF-A40A-4FB5B3089AA1/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74DCCE77-2675-47FF-A40A-4FB5B3089AA1/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74DCCE77-2675-47FF-A40A-4FB5B3089AA1/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74DCCE77-2675-47FF-A40A-4FB5B3089AA1/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74DCCE77-2675-47FF-A40A-4FB5B3089AA1/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74DCCE77-2675-47FF-A40A-4FB5B3089AA1/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74DCCE77-2675-47FF-A40A-4FB5B3089AA1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74DCCE77-2675-47FF-A40A-4FB5B3089AA1/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74DCCE77-2675-47FF-A40A-4FB5B3089AA1/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# #generatePreambleAndBeacons empty keys to notify

,ok 1 should be equal

ok 2 should be equal

ok 3 should be equal

ok 4 should be equal

# teardown

# setup

# #generatePreambleAndBeacons multiple keys to notify

,ok 5 should be equal

ok 6 should be equal

ok 7 should be equal
,
,ok 8 should be equal

# teardown

,# setup

,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,ok 9 should throw

# teardown

# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,ok 10 should throw

# teardown

,# setup

,# #parseBeacons no beacons returns null

,ok 11 should be equal

,# teardown

,# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,ok 12 should throw

# teardown

,# setup

,# #parseBeacons addressBookCallback fails decrypt

,ok 13 should be equal

,# teardown

# setup

,# #parseBeacons addressBookCallback returns null for all

,ok 14 (unnamed assert)

,ok 15 should be equal

,# teardown

,# setup

,# #parseBeacons addressBookCallback returns public key

,ok 16 (unnamed assert)

,ok 17 (unnamed assert)

# teardown

,# setup

,# #parseBeacons with beacons both for and not for the user

,ok 18 (unnamed assert)

# teardown

,appEnteringBackground wasn't registered

,# setup

,# multiplex can send data

,ok 19 String should be length:200

,# teardown

,# setup

,# enqueue and run in order

,ok 20 firstPromise setTimeout

,ok 21 firstPromise result

,ok 22 firstPromise testValue

,ok 23 secondPromise setTimeout

,ok 24 secondPromise result

,ok 25 secondPromise testValue

,ok 26 thirdPromise in promise

,ok 27 thirdPromise result

,ok 28 thirdPromise testValue

,# teardown

,# setup

,# basic

,ok 29 sane

,# teardown

,# setup

,# another

,ok 30 sane

,# teardown

,# setup

,# successfully create a new pkcs12 file and return hash value

,ok 31 should be equal

,ok 32 null

,ok 33 (unnamed assert)

ok 34 should be equal

,ok 35 should not throw

# teardown

,# setup

,# successfully read a previous pkcs12 file and return hash value

,ok 36 (unnamed assert)

,ok 37 (unnamed assert)

ok 38 should not throw

,ok 39 should be equal

,ok 40 should be equal

,# teardown

,# setup

,# failed to extract public key because of corrupt pkcs12 file

,ok 41 should be equal

,# teardown

,# setup

,# failed to get mobile documents path

,ok 42 should be equal

,# teardown

,# setup

,# #init should register the peerAvailabilityChanged event

,ok 43 should be equal

,ok 44 should be equal

,ok 45 should be equal

,# teardown

,# setup

,# #init should register the networkChanged event

,ok 46 should be equal

,# teardown

,# setup

,# #startBroadcasting should throw on null device name

,ok 47 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on empty string device name

,ok 48 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on non-number port

,ok 49 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on NaN port

,ok 50 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on negative port

,ok 51 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on too large port

,ok 52 should throw

,# teardown

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,ok 53 should be equal

,ok 54 should be equal

,ok 55 should be equal

,# teardown

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,ok 56 should be equal

,ok 57 should be equal

,ok 58 should be equal

,# teardown

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,ok 59 should be equal

,ok 60 should be equal

,# teardown

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,ok 61 should be equal

,ok 62 should be equal

,# teardown

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,ok 63 should be equal

,ok 64 should be equal

,ok 65 should be equal

,# teardown

,# setup

,# #connect should call Mobile("Connect") and handle an error

,ok 66 should be equal

,ok 67 should be equal

,# teardown

,# setup

,# should call Mobile("Disconnect") without an error

,ok 68 should be equal

,ok 69 should be equal

,# teardown

,# setup

,# should call Mobile("Disconnect") and handle an error

,ok 70 should be equal

,ok 71 should be equal

,# teardown

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,2016-02-06 00:31:20.924 ThaliTest[1334:2411577] jxcore: startBroadcasting
,2016-02-06 00:31:20.939 ThaliTest[1334:2411577] server: starting 1454715080924.1334.I7KmKQ==
,2016-02-06 00:31:20.940 ThaliTest[1334:2411577] multipeer session: start timer: 0x1632eb50
,2016-02-06 00:31:20.941 ThaliTest[1334:2411577] THEMultipeerSession initialized peer 1454715080924.1334
,2016-02-06 00:31:20.942 ThaliTest[1334:2411577] jxcore: startBroadcasting: success
ok 72 Should be able to call startBroadcasting without error

2016-02-06 00:31:20.945 ThaliTest[1334:2411577] jxcore: stopBroadcasting
,2016-02-06 00:31:20.948 ThaliTest[1334:2411577] THEMultipeerSession stopping peer
,2016-02-06 00:31:20.956 ThaliTest[1334:2411577] multipeer session: stop timer
,2016-02-06 00:31:20.963 ThaliTest[1334:2411577] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,2016-02-06 00:31:20.967 ThaliTest[1334:2411577] jxcore: startBroadcasting
,2016-02-06 00:31:20.972 ThaliTest[1334:2411577] server: starting 1454715080966.1334.2BSlnw==
,2016-02-06 00:31:20.976 ThaliTest[1334:2411577] multipeer session: start timer: 0x1632eb50
,2016-02-06 00:31:20.985 ThaliTest[1334:2411577] THEMultipeerSession initialized peer 1454715080966.1334
,2016-02-06 00:31:20.985 ThaliTest[1334:2411577] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error

,2016-02-06 00:31:20.989 ThaliTest[1334:2411577] jxcore: stopBroadcasting
,2016-02-06 00:31:20.990 ThaliTest[1334:2411577] THEMultipeerSession stopping peer
,2016-02-06 00:31:20.992 ThaliTest[1334:2411577] multipeer session: stop timer
,2016-02-06 00:31:20.996 ThaliTest[1334:2411577] jxcore: stopBroadcasting: success
,ok 75 Should be able to call stopBroadcasting without error

,2016-02-06 00:31:21.003 ThaliTest[1334:2411577] jxcore: startBroadcasting
,2016-02-06 00:31:21.007 ThaliTest[1334:2411577] server: starting 1454715081002.1334.iEkUyw==
,2016-02-06 00:31:21.009 ThaliTest[1334:2411577] multipeer session: start timer: 0x17037740
,2016-02-06 00:31:21.018 ThaliTest[1334:2411577] THEMultipeerSession initialized peer 1454715081002.1334
,2016-02-06 00:31:21.020 ThaliTest[1334:2411577] jxcore: startBroadcasting: success
,ok 76 Should be able to call startBroadcasting without error

,2016-02-06 00:31:21.023 ThaliTest[1334:2411577] jxcore: stopBroadcasting
,2016-02-06 00:31:21.025 ThaliTest[1334:2411577] THEMultipeerSession stopping peer
,2016-02-06 00:31:21.026 ThaliTest[1334:2411577] multipeer session: stop timer
,2016-02-06 00:31:21.032 ThaliTest[1334:2411577] jxcore: stopBroadcasting: success
,ok 77 Should be able to call stopBroadcasting without error

,2016-02-06 00:31:21.035 ThaliTest[1334:2411577] jxcore: startBroadcasting
,2016-02-06 00:31:21.038 ThaliTest[1334:2411577] server: starting 1454715081035.1334.a8PCYQ==
,2016-02-06 00:31:21.040 ThaliTest[1334:2411577] multipeer session: start timer: 0x1702b310
,2016-02-06 00:31:21.043 ThaliTest[1334:2411577] THEMultipeerSession initialized peer 1454715081035.1334
,2016-02-06 00:31:21.045 ThaliTest[1334:2411577] jxcore: startBroadcasting: success
,ok 78 Should be able to call startBroadcasting without error
,
,2016-02-06 00:31:21.049 ThaliTest[1334:2411577] jxcore: stopBroadcasting
,2016-02-06 00:31:21.050 ThaliTest[1334:2411577] THEMultipeerSession stopping peer
,2016-02-06 00:31:21.051 ThaliTest[1334:2411577] multipeer session: stop timer
,2016-02-06 00:31:21.054 ThaliTest[1334:2411577] jxcore: stopBroadcasting: success
,ok 79 Should be able to call stopBroadcasting without error

,2016-02-06 00:31:21.058 ThaliTest[1334:2411577] jxcore: startBroadcasting
,2016-02-06 00:31:21.061 ThaliTest[1334:2411577] server: starting 1454715081058.1334.JYlRRQ==
,2016-02-06 00:31:21.066 ThaliTest[1334:2411577] multipeer session: start timer: 0x170296c0
,2016-02-06 00:31:21.069 ThaliTest[1334:2411577] THEMultipeerSession initialized peer 1454715081058.1334
,2016-02-06 00:31:21.071 ThaliTest[1334:2411577] jxcore: startBroadcasting: success
,ok 80 Should be able to call startBroadcasting without error

,2016-02-06 00:31:21.073 ThaliTest[1334:2411577] jxcore: stopBroadcasting
,2016-02-06 00:31:21.074 ThaliTest[1334:2411577] THEMultipeerSession stopping peer
,2016-02-06 00:31:21.075 ThaliTest[1334:2411577] multipeer session: stop timer
,2016-02-06 00:31:21.078 ThaliTest[1334:2411577] jxcore: stopBroadcasting: success
,ok 81 Should be able to call stopBroadcasting without error

,2016-02-06 00:31:21.081 ThaliTest[1334:2411577] jxcore: startBroadcasting
,2016-02-06 00:31:21.083 ThaliTest[1334:2411577] server: starting 1454715081080.1334.9dZPeg==
,2016-02-06 00:31:21.085 ThaliTest[1334:2411577] multipeer session: start timer: 0x1633b500
,2016-02-06 00:31:21.089 ThaliTest[1334:2411577] THEMultipeerSession initialized peer 1454715081080.1334
,2016-02-06 00:31:21.091 ThaliTest[1334:2411577] jxcore: startBroadcasting: success
,ok 82 Should be able to call startBroadcasting without error

,2016-02-06 00:31:21.094 ThaliTest[1334:2411577] jxcore: stopBroadcasting
,2016-02-06 00:31:21.095 ThaliTest[1334:2411577] THEMultipeerSession stopping peer
,2016-02-06 00:31:21.096 ThaliTest[1334:2411577] multipeer session: stop timer
,2016-02-06 00:31:21.100 ThaliTest[1334:2411577] jxcore: stopBroadcasting: success
,ok 83 Should be able to call stopBroadcasting without error

,2016-02-06 00:31:21.103 ThaliTest[1334:2411577] jxcore: startBroadcasting
,2016-02-06 00:31:21.106 ThaliTest[1334:2411577] server: starting 1454715081102.1334.HdEEpA==
,2016-02-06 00:31:21.108 ThaliTest[1334:2411577] multipeer session: start timer: 0x14d95a60
,2016-02-06 00:31:21.111 ThaliTest[1334:2411577] THEMultipeerSession initialized peer 1454715081102.1334
,2016-02-06 00:31:21.113 ThaliTest[1334:2411577] jxcore: startBroadcasting: success
,ok 84 Should be able to call startBroadcasting without error

,2016-02-06 00:31:21.116 ThaliTest[1334:2411577] jxcore: stopBroadcasting
,2016-02-06 00:31:21.117 ThaliTest[1334:2411577] THEMultipeerSession stopping peer
,2016-02-06 00:31:21.118 ThaliTest[1334:2411577] multipeer session: stop timer
,2016-02-06 00:31:21.121 ThaliTest[1334:2411577] jxcore: stopBroadcasting: success
,ok 85 Should be able to call stopBroadcasting without error

,2016-02-06 00:31:21.125 ThaliTest[1334:2411577] jxcore: startBroadcasting
,2016-02-06 00:31:21.128 ThaliTest[1334:2411577] server: starting 1454715081124.1334.+jNaQQ==
,2016-02-06 00:31:21.131 ThaliTest[1334:2411577] multipeer session: start timer: 0x16340ce0
,2016-02-06 00:31:21.132 ThaliTest[1334:2411577] THEMultipeerSession initialized peer 1454715081124.1334
,2016-02-06 00:31:21.133 ThaliTest[1334:2411577] jxcore: startBroadcasting: success
,ok 86 Should be able to call startBroadcasting without error

,2016-02-06 00:31:21.137 ThaliTest[1334:2411577] jxcore: stopBroadcasting
,2016-02-06 00:31:21.137 ThaliTest[1334:2411577] THEMultipeerSession stopping peer
,2016-02-06 00:31:21.138 ThaliTest[1334:2411577] multipeer session: stop timer
,2016-02-06 00:31:21.142 ThaliTest[1334:2411577] jxcore: stopBroadcasting: success
,ok 87 Should be able to call stopBroadcasting without error

,2016-02-06 00:31:21.143 ThaliTest[1334:2411577] jxcore: startBroadcasting
,2016-02-06 00:31:21.146 ThaliTest[1334:2411577] server: starting 1454715081143.1334.Ylia6A==
,2016-02-06 00:31:21.147 ThaliTest[1334:2411577] multipeer session: start timer: 0x16340bd0
,2016-02-06 00:31:21.151 ThaliTest[1334:2411577] THEMultipeerSession initialized peer 1454715081143.1334
,2016-02-06 00:31:21.152 ThaliTest[1334:2411577] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error

,2016-02-06 00:31:21.153 ThaliTest[1334:2411577] jxcore: stopBroadcasting
,2016-02-06 00:31:21.154 ThaliTest[1334:2411577] THEMultipeerSession stopping peer
,2016-02-06 00:31:21.155 ThaliTest[1334:2411577] multipeer session: stop timer
,2016-02-06 00:31:21.156 ThaliTest[1334:2411577] jxcore: stopBroadcasting: success
,ok 89 Should be able to call stopBroadcasting without error

,2016-02-06 00:31:21.160 ThaliTest[1334:2411577] jxcore: startBroadcasting
,2016-02-06 00:31:21.162 ThaliTest[1334:2411577] server: starting 1454715081159.1334.R4tV3A==
,2016-02-06 00:31:21.164 ThaliTest[1334:2411577] multipeer session: start timer: 0x16341ef0
,2016-02-06 00:31:21.165 ThaliTest[1334:2411577] THEMultipeerSession initialized peer 1454715081159.1334
,2016-02-06 00:31:21.166 ThaliTest[1334:2411577] jxcore: startBroadcasting: success
,ok 90 Should be able to call startBroadcasting without error

,2016-02-06 00:31:21.170 ThaliTest[1334:2411577] jxcore: stopBroadcasting
,2016-02-06 00:31:21.171 ThaliTest[1334:2411577] THEMultipeerSession stopping peer
,2016-02-06 00:31:21.171 ThaliTest[1334:2411577] multipeer session: stop timer
,2016-02-06 00:31:21.173 ThaliTest[1334:2411577] jxcore: stopBroadcasting: success
,ok 91 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,2016-02-06 00:31:21.240 ThaliTest[1334:2411577] jxcore: startBroadcasting
,2016-02-06 00:31:21.243 ThaliTest[1334:2411577] server: starting 1454715081240.1334.RCPi0Q==
,2016-02-06 00:31:21.245 ThaliTest[1334:2411577] multipeer session: start timer: 0x16207fb0
,2016-02-06 00:31:21.250 ThaliTest[1334:2411577] THEMultipeerSession initialized peer 1454715081240.1334
,2016-02-06 00:31:21.251 ThaliTest[1334:2411577] jxcore: startBroadcasting: success
,ok 92 Should be able to call startBroadcasting without error

,2016-02-06 00:31:21.254 ThaliTest[1334:2411577] jxcore: startBroadcasting
,2016-02-06 00:31:21.255 ThaliTest[1334:2411577] jxcore: startBroadcasting: failure
,ok 93 Cannot call startBroadcasting twice

,2016-02-06 00:31:21.259 ThaliTest[1334:2411577] jxcore: stopBroadcasting
,2016-02-06 00:31:21.259 ThaliTest[1334:2411577] THEMultipeerSession stopping peer
,2016-02-06 00:31:21.260 ThaliTest[1334:2411577] multipeer session: stop timer
,2016-02-06 00:31:21.262 ThaliTest[1334:2411577] jxcore: stopBroadcasting: success
,ok 94 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter throws on connection to bad peer

,2016-02-06 00:31:21.331 ThaliTest[1334:2411577] jxcore: startBroadcasting
,2016-02-06 00:31:21.334 ThaliTest[1334:2411577] server: starting 1454715081331.1334.gwBGzQ==
,2016-02-06 00:31:21.336 ThaliTest[1334:2411577] multipeer session: start timer: 0x163574c0
,2016-02-06 00:31:21.342 ThaliTest[1334:2411577] THEMultipeerSession initialized peer 1454715081331.1334
,2016-02-06 00:31:21.343 ThaliTest[1334:2411577] jxcore: startBroadcasting: success
,ok 95 Should be able to call startBroadcasting without error

,2016-02-06 00:31:21.347 ThaliTest[1334:2411577] jxcore: connect foobar
,2016-02-06 00:31:21.349 ThaliTest[1334:2411577] client: unknown peer foobar
,2016-02-06 00:31:21.350 ThaliTest[1334:2411577] jxcore: connect: fail: Unknown peer
,ok 96 Should not connect to a bad peer

,2016-02-06 00:31:21.354 ThaliTest[1334:2411577] jxcore: stopBroadcasting
,2016-02-06 00:31:21.355 ThaliTest[1334:2411577] THEMultipeerSession stopping peer
,2016-02-06 00:31:21.356 ThaliTest[1334:2411577] multipeer session: stop timer
,2016-02-06 00:31:21.358 ThaliTest[1334:2411577] jxcore: stopBroadcasting: success
,ok 97 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,2016-02-06 00:31:21.432 ThaliTest[1334:2411577] jxcore: startBroadcasting
,2016-02-06 00:31:21.436 ThaliTest[1334:2411577] server: starting 1454715081431.1334.zDxT6A==
,2016-02-06 00:31:21.439 ThaliTest[1334:2411577] multipeer session: start timer: 0x16234210
,2016-02-06 00:31:21.449 ThaliTest[1334:2411577] THEMultipeerSession initialized peer 1454715081431.1334
,2016-02-06 00:31:21.451 ThaliTest[1334:2411577] jxcore: startBroadcasting: success
,ok 98 Should be able to call startBroadcasting without error

,2016-02-06 00:31:21.454 ThaliTest[1334:2411577] jxcore: disconnect
,2016-02-06 00:31:21.456 ThaliTest[1334:2411577] jxcore: disconnect: fail
,ok 99 Disconnect should fail to a non-existant peer 

,2016-02-06 00:31:21.461 ThaliTest[1334:2411577] jxcore: stopBroadcasting
,2016-02-06 00:31:21.462 ThaliTest[1334:2411577] THEMultipeerSession stopping peer
,2016-02-06 00:31:21.463 ThaliTest[1334:2411577] multipeer session: stop timer
,2016-02-06 00:31:21.469 ThaliTest[1334:2411577] jxcore: stopBroadcasting: success
,ok 100 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter can discover and connect to peers

,2016-02-06 00:31:22.799 ThaliTest[1334:2411577] jxcore: startBroadcasting
,2016-02-06 00:31:22.803 ThaliTest[1334:2411577] server: starting 1454715082799.1334.u7t0sQ==
2016-02-06 00:31:22.804 ThaliTest[1334:2411577] multipeer session: start timer: 0x14e18320
2016-02-06 00:31:22.805 ThaliTest[1334:2411577] THEMultipeerSession in,itialized peer 1454715082799.1334
2016-02-06 00:31:22.805 ThaliTest[1334:2411577] jxcore: startBroadcasting: success
ok 101 Should be able to call startBroadcasting without error

,2016-02-06 00:31:23.639 ThaliTest[1334:2411338] client: found peer: 1454715084283.752.r483fQ==
,2016-02-06 00:31:23.642 ThaliTest[1334:2411577] jxcore: connect 1454715084283.752.r483fQ==
2016-02-06 00:31:23.642 ThaliTest[1334:2411577] client session: connect
2016-02-06 00:31:23.643 ThaliTest[1334:2411577] client session: stateChange:0->1 1454715084283.752.r483fQ==
,2016-02-06 00:31:24.277 ThaliTest[1334:2411338] multipeer session: reset timer
2016-02-06 00:31:24.278 ThaliTest[1334:2411338] multipeer session: stop timer
2016-02-06 00:31:24.278 ThaliTest[1334:2411338] multipeer session: start timer: 0x14e18320
2016-,02-06 00:31:24.278 ThaliTest[1334:2411338] server session: connect
2016-02-06 00:31:24.279 ThaliTest[1334:2411338] server session: stateChange:0->1 1454715084283.752
,2016-02-06 00:31:24.289 ThaliTest[1334:2411338] server: accepting invitation 1454715084283.752
,2016-02-06 00:31:26.941 ThaliTest[1334:2412263] server session: connected
2016-02-06 00:31:26.943 ThaliTest[1334:2412263] server session: stateChange:1->2 1454715084283.752
,2016-02-06 00:31:26.951 ThaliTest[1334:2411338] server relay: socket disconnected
2016-02-06 00:31:26.951 ThaliTest[1334:2411338] server relay: 0x16142860 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-06 00:31:27.019 ThaliTest[1334:2412267] server session: not connected 1454715084283.752
,2016-02-06 00:31:27.104 ThaliTest[1334:2412267] client session: connected
2016-02-06 00:31:27.104 ThaliTest[1334:2412267] client session: stateChange:1->2 1454715084283.752.r483fQ==
,2016-02-06 00:31:27.108 ThaliTest[1334:2412267] client session: fireConnectCallback: 1454715084283.752.r483fQ==
2016-02-06 00:31:27.108 ThaliTest[1334:2412267] jxcore: connect: success
ok 102 Should be able to connect without error

,ok 103 Port should be within range

,2016-02-06 00:31:27.112 ThaliTest[1334:2411577] jxcore: disconnect
2016-02-06 00:31:27.113 ThaliTest[1334:2411577] client session: disconnectFromPeer: 1454715084283.752.r483fQ==
2016-02-06 00:31:27.113 ThaliTest[1334:2411577] client session: disconnect
,2016-02-06 00:31:27.113 ThaliTest[1334:2411577] client session: stateChange:2->0 1454715084283.752.r483fQ==
,2016-02-06 00:31:27.194 ThaliTest[1334:2411577] jxcore: disconnect: success
ok 104 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# teardown

,calling stopBroadcasting

,2016-02-06 00:31:27.626 ThaliTest[1334:2411577] jxcore: stopBroadcasting
2016-02-06 00:31:27.627 ThaliTest[1334:2411577] THEMultipeerSession stopping peer
2016-02-06 00:31:27.627 ThaliTest[1334:2411577] multipeer session: stop timer
2016-02-06 00:31:27.,628 ThaliTest[1334:2411577] server session: disconnect
2016-02-06 00:31:27.628 ThaliTest[1334:2411577] server session: stateChange:2->0 1454715084283.752
2016-02-06 00:31:27.629 ThaliTest[1334:2411577] jxcore: stopBroadcasting: success
stopBroadcasting ,returned undefined

,# setup

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,2016-02-06 00:31:27.679 ThaliTest[1334:2411577] jxcore: startBroadcasting
,2016-02-06 00:31:27.682 ThaliTest[1334:2411577] server: starting 1454715087678.1334.N89O0g==
2016-02-06 00:31:27.683 ThaliTest[1334:2411577] multipeer session: start timer: 0x16172da0
2016-02-06 00:31:27.683 ThaliTest[1334:2411577] THEMultipeerSession in,itialized peer 1454715087678.1334
2016-02-06 00:31:27.684 ThaliTest[1334:2411577] jxcore: startBroadcasting: success
ok 105 Should be able to call startBroadcasting without error

,2016-02-06 00:31:27.699 ThaliTest[1334:2411338] client: found peer: 1454715084283.752.r483fQ==
2016-02-06 00:31:27.701 ThaliTest[1334:2411577] jxcore: connect 1454715084283.752.r483fQ==
2016-02-06 00:31:27.702 ThaliTest[1334:2411338] client: found peer: 1454715082799.1334.u7t0sQ==
2016-02-06 00:31:27.703 ThaliTest[1334:2411577] client session: connect
,2016-02-06 00:31:27.703 ThaliTest[1334:2411577] client session: stateChange:0->1 1454715084283.752.r483fQ==
,2016-02-06 00:31:27.718 ThaliTest[1334:2411577] jxcore: connect 1454715082799.1334.u7t0sQ==
2016-02-06 00:31:27.719 ThaliTest[1334:2411577] client session: connect
2016-02-06 00:31:27.719 ThaliTest[1334:2411577] client session: stateChange:0->1 145471508,2799.1334.u7t0sQ==
,2016-02-06 00:31:28.905 ThaliTest[1334:2411338] client: lost peer: 1454715084283.752.r483fQ==
2016-02-06 00:31:28.906 ThaliTest[1334:2411338] client session: onPeerLost: 1454715084283.752.r483fQ==
2016-02-06 00:31:28.906 ThaliTest[1334:2411338] client se,ssion: onLinkFailure: 1454715084283.752.r483fQ==
2016-02-06 00:31:28.906 ThaliTest[1334:2411338] client session: disconnect
2016-02-06 00:31:28.906 ThaliTest[1334:2411338] client session: stateChange:1->0 1454715084283.752.r483fQ==
2016-02-06 00:31:28.9,07 ThaliTest[1334:2411338] client session: fireConnectCallback: 1454715084283.752.r483fQ==
2016-02-06 00:31:28.907 ThaliTest[1334:2411338] jxcore: connect: fail: Peer disconnected
,2016-02-06 00:31:28.941 ThaliTest[1334:2411338] client: lost peer: 1454715082799.1334.u7t0sQ==
2016-02-06 00:31:28.942 ThaliTest[1334:2411338] client session: onPeerLost: 1454715082799.1334.u7t0sQ==
2016-02-06 00:31:28.942 ThaliTest[1334:2411338] client ,session: onLinkFailure: 1454715082799.1334.u7t0sQ==
2016-02-06 00:31:28.942 ThaliTest[1334:2411338] client session: disconnect
2016-02-06 00:31:28.943 ThaliTest[1334:2411338] client session: stateChange:1->0 1454715082799.1334.u7t0sQ==
2016-02-06 00:31:,28.943 ThaliTest[1334:2411338] client session: fireConnectCallback: 1454715082799.1334.u7t0sQ==
2016-02-06 00:31:28.944 ThaliTest[1334:2411338] jxcore: connect: fail: Peer disconnected
2016-02-06 00:31:28.944 ThaliTest[1334:2411338] client: found peer: 1454715089475.752.R2vO/A==
,2016-02-06 00:31:28.948 ThaliTest[1334:2411577] jxcore: connect 1454715089475.752.R2vO/A==
2016-02-06 00:31:28.949 ThaliTest[1334:2411577] client session: connect
2016-02-06 00:31:28.949 ThaliTest[1334:2411577] client session: stateChange:0->1 1454715089475.752.R2vO/A==
,2016-02-06 00:31:28.978 ThaliTest[1334:2411338] multipeer session: reset timer
2016-02-06 00:31:28.980 ThaliTest[1334:2411338] multipeer session: stop timer
2016-02-06 00:31:28.980 ThaliTest[1334:2411338] multipeer session: start timer: 0x16172da0
2016-,02-06 00:31:28.981 ThaliTest[1334:2411338] server session: connect
2016-02-06 00:31:28.981 ThaliTest[1334:2411338] server session: stateChange:0->1 1454715089475.752
,2016-02-06 00:31:28.993 ThaliTest[1334:2411338] server: accepting invitation 1454715089475.752
,2016-02-06 00:31:29.918 ThaliTest[1334:2411577] jxcore: connect 1454715084283.752.r483fQ==
2016-02-06 00:31:29.918 ThaliTest[1334:2411577] client: connect: unreachable 1454715084283.752.r483fQ==
2016-02-06 00:31:29.919 ThaliTest[1334:2411577] jxcore: connect: fail: Peer unreachable
,2016-02-06 00:31:29.957 ThaliTest[1334:2411577] jxcore: connect 1454715082799.1334.u7t0sQ==
2016-02-06 00:31:29.957 ThaliTest[1334:2411577] client: connect: unreachable 1454715082799.1334.u7t0sQ==
2016-02-06 00:31:29.958 ThaliTest[1334:2411577] jxcore: connect: fail: Peer unreachable
,2016-02-06 00:31:31.782 ThaliTest[1334:2412295] server session: connected
2016-02-06 00:31:31.782 ThaliTest[1334:2412295] server session: stateChange:1->2 1454715089475.752
,2016-02-06 00:31:31.791 ThaliTest[1334:2411338] server relay: socket disconnected
,2016-02-06 00:31:31.791 ThaliTest[1334:2411338] server relay: 0x17431bb0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-06 00:31:31.847 ThaliTest[1334:2412263] server session: not connected 1454715089475.752
,2016-02-06 00:31:31.947 ThaliTest[1334:2412263] client session: connected
2016-02-06 00:31:31.950 ThaliTest[1334:2412263] client session: stateChange:1->2 1454715089475.752.R2vO/A==
,2016-02-06 00:31:31.982 ThaliTest[1334:2412295] client session: fireConnectCallback: 1454715089475.752.R2vO/A==
2016-02-06 00:31:31.982 ThaliTest[1334:2412295] jxcore: connect: success
,ok 106 Should be able to connect without error

,ok 107 Port should be within range

,2016-02-06 00:31:31.988 ThaliTest[1334:2411577] jxcore: connect 1454715089475.752.R2vO/A==
2016-02-06 00:31:31.988 ThaliTest[1334:2411577] client: already connect(ing/ed) to 1454715089475.752.R2vO/A==
,2016-02-06 00:31:31.989 ThaliTest[1334:2411577] jxcore: connect: fail: Aleady connecting
,ok 108 Should fail on double connect

,2016-02-06 00:31:31.992 ThaliTest[1334:2411577] jxcore: disconnect
2016-02-06 00:31:31.993 ThaliTest[1334:2411577] client session: disconnectFromPeer: 1454715089475.752.R2vO/A==
2016-02-06 00:31:31.994 ThaliTest[1334:2411577] client session: disconnect
2016-02-06 00:31:31.994 ThaliTest[1334:2411577] client session: stateChange:2->0 1454715089475.752.R2vO/A==
,2016-02-06 00:31:32.002 ThaliTest[1334:2411577] jxcore: disconnect: success
ok 109 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# teardown

,calling stopBroadcasting

,2016-02-06 00:31:32.341 ThaliTest[1334:2411577] jxcore: stopBroadcasting
2016-02-06 00:31:32.342 ThaliTest[1334:2411577] THEMultipeerSession stopping peer
2016-02-06 00:31:32.342 ThaliTest[1334:2411577] multipeer session: stop timer
2016-02-06 00:31:32.,342 ThaliTest[1334:2411577] server session: disconnect
2016-02-06 00:31:32.343 ThaliTest[1334:2411577] server session: stateChange:2->0 1454715089475.752
2016-02-06 00:31:32.345 ThaliTest[1334:2411577] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,2016-02-06 00:31:35.046 ThaliTest[1334:2411577] jxcore: startBroadcasting
,2016-02-06 00:31:35.050 ThaliTest[1334:2411577] server: starting 1454715095046.1334.PB48UQ==
2016-02-06 00:31:35.051 ThaliTest[1334:2411577] multipeer session: start timer: 0x1758c350
2016-02-06 00:31:35.051 ThaliTest[1334:2411577] THEMultipeerSession initialized peer 1454715095046.1334
2016-02-06 00:31:35.052 ThaliTest[1334:2411577] jxcore: startBroadcasting: success
ok 110 Should be able to call startBroadcasting without error

,2016-02-06 00:31:36.277 ThaliTest[1334:2411338] client: found peer: 1454715096831.752.tQr+lw==
2016-02-06 00:31:36.278 ThaliTest[1334:2411577] jxcore: connect 1454715096831.752.tQr+lw==
2016-02-06 00:31:36.279 ThaliTest[1334:2411577] client session: connect
2016-02-06 00:31:36.279 ThaliTest[1334:2411577] client session: stateChange:0->1 1454715096831.752.tQr+lw==
,2016-02-06 00:31:36.720 ThaliTest[1334:2411338] multipeer session: reset timer
2016-02-06 00:31:36.720 ThaliTest[1334:2411338] multipeer session: stop timer
2016-02-06 00:31:36.720 ThaliTest[1334:2411338] multipeer session: start timer: 0x1758c350
2016-,02-06 00:31:36.721 ThaliTest[1334:2411338] server session: connect
2016-02-06 00:31:36.721 ThaliTest[1334:2411338] server session: stateChange:0->1 1454715096831.752
,2016-02-06 00:31:36.732 ThaliTest[1334:2411338] server: accepting invitation 1454715096831.752
,2016-02-06 00:31:40.808 ThaliTest[1334:2412344] server session: connected
2016-02-06 00:31:40.809 ThaliTest[1334:2412344] server session: stateChange:1->2 1454715096831.752
,2016-02-06 00:31:41.147 ThaliTest[1334:2412296] client session: connected
2016-02-06 00:31:41.148 ThaliTest[1334:2412296] client session: stateChange:1->2 1454715096831.752.tQr+lw==
,2016-02-06 00:31:41.316 ThaliTest[1334:2411338] server relay: socket disconnected
2016-02-06 00:31:41.316 ThaliTest[1334:2411338] server relay: 0x16176270 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-06 00:31:41.373 ThaliTest[1334:2412263] server session: not connected 1454715096831.752
,2016-02-06 00:31:41.419 ThaliTest[1334:2412263] client session: fireConnectCallback: 1454715096831.752.tQr+lw==
2016-02-06 00:31:41.419 ThaliTest[1334:2412263] jxcore: connect: success
ok 111 Should be able to connect without error

ok 112 Port should ,be within range

2016-02-06 00:31:41.423 ThaliTest[1334:2411577] jxcore: disconnect
2016-02-06 00:31:41.423 ThaliTest[1334:2411577] client session: disconnectFromPeer: 1454715096831.752.tQr+lw==
2016-02-06 00:31:41.424 ThaliTest[1334:2411577] client se,ssion: disconnect
2016-02-06 00:31:41.424 ThaliTest[1334:2411577] client session: stateChange:2->0 1454715096831.752.tQr+lw==
,2016-02-06 00:31:41.440 ThaliTest[1334:2411577] jxcore: disconnect: success
ok 113 Should be able to disconnect without error

2016-02-06 00:31:41.443 ThaliTest[1334:2411577] jxcore: disconnect
2016-02-06 00:31:41.443 ThaliTest[1334:2411577] jxcore: di,sconnect: fail
ok 114 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# teardown

,calling stopBroadcasting

,2016-02-06 00:31:41.584 ThaliTest[1334:2411577] jxcore: stopBroadcasting
2016-02-06 00:31:41.584 ThaliTest[1334:2411577] THEMultipeerSession stopping peer
2016-02-06 00:31:41.584 ThaliTest[1334:2411577] multipeer session: stop timer
2016-02-06 00:31:41.,585 ThaliTest[1334:2411577] server session: disconnect
2016-02-06 00:31:41.585 ThaliTest[1334:2411577] server session: stateChange:2->0 1454715096831.752
2016-02-06 00:31:41.586 ThaliTest[1334:2411577] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can connect and send data

,echo server started on port: 57513

,2016-02-06 00:31:42.291 ThaliTest[1334:2411577] jxcore: startBroadcasting
,2016-02-06 00:31:42.293 ThaliTest[1334:2411577] server: starting 1454715102291.1334.yAxPyA==
,2016-02-06 00:31:42.294 ThaliTest[1334:2411577] multipeer session: start timer: 0x172d64f0
,2016-02-06 00:31:42.296 ThaliTest[1334:2411577] THEMultipeerSession initialized peer 1454715102291.1334
,2016-02-06 00:31:42.297 ThaliTest[1334:2411577] jxcore: startBroadcasting: success
,ok 115 Should be able to call startBroadcasting without error

,2016-02-06 00:31:43.578 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==
2016-02-06 00:31:43.580 ThaliTest[1334:2411577] jxcore: connect 1454715104051.752.L2fN6A==
2016-02-06 00:31:43.580 ThaliTest[1334:2411577] client session: conn,ect
2016-02-06 00:31:43.580 ThaliTest[1334:2411577] client session: stateChange:0->1 1454715104051.752.L2fN6A==
,2016-02-06 00:31:43.606 ThaliTest[1334:2411338] multipeer session: reset timer
2016-02-06 00:31:43.607 ThaliTest[1334:2411338] multipeer session: stop timer
2016-02-06 00:31:43.607 ThaliTest[1334:2411338] multipeer session: start timer: 0x172d64f0
,2016-02-06 00:31:43.607 ThaliTest[1334:2411338] server session: connect
2016-02-06 00:31:43.610 ThaliTest[1334:2411338] server session: stateChange:0->1 1454715104051.752
,2016-02-06 00:31:43.625 ThaliTest[1334:2411338] server: accepting invitation 1454715104051.752
,2016-02-06 00:31:49.841 ThaliTest[1334:2412261] server session: connected
2016-02-06 00:31:49.841 ThaliTest[1334:2412261] server session: stateChange:1->2 1454715104051.752
,2016-02-06 00:31:49.852 ThaliTest[1334:2411338] server relay: connected (to port: 57513)
,2016-02-06 00:31:49.991 ThaliTest[1334:2412296] client session: connected
2016-02-06 00:31:49.991 ThaliTest[1334:2412296] client session: stateChange:1->2 1454715104051.752.L2fN6A==
,2016-02-06 00:31:50.003 ThaliTest[1334:2412296] client session: fireConnectCallback: 1454715104051.752.L2fN6A==
2016-02-06 00:31:50.003 ThaliTest[1334:2412296] jxcore: connect: success
ok 116 Should be able to connect without error

ok 117 Port should be within range

,2016-02-06 00:31:50.015 ThaliTest[1334:2411338] client: relay established
2016-02-06 00:31:50.016 ThaliTest[1334:2411338] client: new accepted socket: 0x14dbf4a0
,2016-02-06 00:32:01.095 ThaliTest[1334:2412440] client session: not connected 1454715104051.752.L2fN6A==
2016-02-06 00:32:01.096 ThaliTest[1334:2412440] client session: onLinkFailure: 1454715104051.752.L2fN6A==
2016-02-06 00:32:01.096 ThaliTest[1334:2412,440] client session: disconnect
2016-02-06 00:32:01.096 ThaliTest[1334:2412440] client session: stateChange:2->0 1454715104051.752.L2fN6A==
,2016-02-06 00:32:01.099 ThaliTest[1334:2412440] client session: fireConnectionErrorEvent: 1454715104051.752.L2fN6A==
,2016-02-06 00:32:13.609 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:32:13.648 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==
,2016-02-06 00:32:19.536 ThaliTest[1334:2412461] server session: not connected 1454715104051.752
,2016-02-06 00:32:43.609 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:32:43.645 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==
,2016-02-06 00:33:13.609 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:33:13.644 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==
,2016-02-06 00:33:43.609 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:33:43.644 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==
,2016-02-06 00:34:13.609 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:34:13.646 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==
,2016-02-06 00:34:43.608 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:34:43.645 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==
,2016-02-06 00:35:13.608 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:35:43.609 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:35:43.638 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==
,2016-02-06 00:36:13.609 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:36:13.639 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==
,2016-02-06 00:36:43.609 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:36:43.639 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==
,2016-02-06 00:37:13.609 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:37:13.640 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==
,appEnteredForeground wasn't registered

,2016-02-06 00:37:43.608 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:37:43.638 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==
,2016-02-06 00:38:13.609 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:38:13.639 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==
,2016-02-06 00:38:43.609 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:38:43.641 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==
,2016-02-06 00:39:13.609 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:39:13.637 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==
,2016-02-06 00:39:43.609 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:39:43.640 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==
,2016-02-06 00:40:13.609 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:40:43.609 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:40:43.637 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==
,2016-02-06 00:41:01.279 ThaliTest[1334:2411338] client: lost peer: 1454715104051.752.L2fN6A==
2016-02-06 00:41:01.279 ThaliTest[1334:2411338] client session: onPeerLost: 1454715104051.752.L2fN6A==
,2016-02-06 00:41:05.295 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==
,2016-02-06 00:41:05.297 ThaliTest[1334:2411577] jxcore: connect 1454715104051.752.L2fN6A==
2016-02-06 00:41:05.297 ThaliTest[1334:2411577] client session: connect
2016-02-06 00:41:05.298 ThaliTest[1334:2411577] client session: stateChange:0->1 1454715104051.752.L2fN6A==
,2016-02-06 00:41:11.869 ThaliTest[1334:2413791] client session: connected
2016-02-06 00:41:11.872 ThaliTest[1334:2413791] client session: stateChange:1->2 1454715104051.752.L2fN6A==
,2016-02-06 00:41:11.875 ThaliTest[1334:2413791] client session: fireConnectCallback: 1454715104051.752.L2fN6A==
2016-02-06 00:41:11.876 ThaliTest[1334:2413791] jxcore: connect: success
ok 118 Should be able to connect without error

ok 119 Port should be within range

,2016-02-06 00:41:11.884 ThaliTest[1334:2411338] client: relay established
2016-02-06 00:41:11.884 ThaliTest[1334:2411338] client: new accepted socket: 0x17199ca0
,data in 1095

,data in 2190

,data in 3285

,data in 4380

,2016-02-06 00:41:13.609 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:41:13.640 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==
,data in 5475

,data in 6570

,data in 7665

,data in 8760

,data in 9855

,data in 10950

,data in 12045

,data in 13140

,data in 14235

,data in 15330

,data in 16425

,data in 17520

,data in 18615

,data in 19710

,data in 20805

,data in 21900

,data in 22995

,data in 24090

,data in 25185

,data in 26280

,data in 27375

,data in 28470

,data in 29565

,data in 30660

,data in 31755

,data in 32850

,data in 33945

,data in 35040

,data in 36135

,data in 37230

,data in 38325

,data in 39420

,data in 40515

,data in 41610

,data in 42705

,data in 43800

,data in 44895

,data in 45990

,data in 47085

,data in 48180

,data in 49275

,data in 50370

,data in 51465

,data in 53655

,data in 54750

,data in 55845

,data in 58035

,data in 59130

,data in 60225

,data in 64605

,data in 66795

,data in 75555

,data in 76650

,data in 77745

,data in 78840

,data in 79935

,data in 81030

,data in 82125

,data in 83220

,data in 84315

,data in 85410

,data in 86505

,data in 87600

,data in 90885

,data in 91980

,data in 94170

,data in 95265

,data in 97455

,data in 98550

,data in 99645

,data in 100740

,data in 101835

,data in 102930

,data in 104025

,data in 105120

,data in 106215

,data in 107310

,data in 108405

,data in 109500

,data in 110595

,2016-02-06 00:41:43.609 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:41:43.640 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==
,data in 111690

,data in 112785

,data in 113809

,data in 113880

,data in 114975

,data in 116070

,data in 117165

,data in 118260

,data in 119355

,data in 120450

,data in 121545

,data in 122640

,data in 123735

,data in 125144

,data in 127020

,data in 128115

,data in 129210

,data in 130305

,data in 131072

,ok 120 the test messages should be equal

,2016-02-06 00:41:46.732 ThaliTest[1334:2411577] jxcore: disconnect
2016-02-06 00:41:46.733 ThaliTest[1334:2411577] client session: disconnectFromPeer: 1454715104051.752.L2fN6A==
2016-02-06 00:41:46.733 ThaliTest[1334:2411577] client session: disconnect
,2016-02-06 00:41:46.734 ThaliTest[1334:2411577] client session: stateChange:2->0 1454715104051.752.L2fN6A==
,2016-02-06 00:41:46.741 ThaliTest[1334:2411577] jxcore: disconnect: success
ok 121 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# teardown

,2016-02-06 00:42:13.608 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:42:43.609 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:42:43.638 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==
,2016-02-06 00:43:13.608 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:43:13.640 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==
,2016-02-06 00:43:43.609 ThaliTest[1334:2411338] multipeer session: restart
,2016-02-06 00:43:43.640 ThaliTest[1334:2411338] client: found peer: 1454715104051.752.L2fN6A==

```
