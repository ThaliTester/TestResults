#### Test 583805004f2b042_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/583805004f2b042/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/C23D607D-3E0C-42A5-BD6C-DF2C8214CA54/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/C23D607D-3E0C-42A5-BD6C-DF2C8214CA54/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/583805004f2b042/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/583805004f2b042/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7779FD42-391B-4FC2-ADFC-6926D3562BBC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53706"
,(lldb)     command script import "/tmp/C23D607D-3E0C-42A5-BD6C-DF2C8214CA54/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 17:34:52.242 ThaliTest[1699:2989114] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/25AD0D12-5625-442A-85B0-A09DDF24B384/Library/Cookies/Cookies.binarycookies
,2016-02-09 17:34:52.661 ThaliTest[1699:2989114] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-09 17:34:52.662 ThaliTest[1699:2989114] Multi-tasking -> Device: YES, App: YES
,2016-02-09 17:34:52.672 ThaliTest[1699:2989114] Unlimited access to network resources
,2016-02-09 17:34:52.681 ThaliTest[1699:2989114] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 17:35:02.444 ThaliTest[1699:2989114] Resetting plugins due to page load.
,2016-02-09 17:35:06.144 ThaliTest[1699:2989114] Finished load of: file:///var/mobile/Containers/Bundle/Application/7779FD42-391B-4FC2-ADFC-6926D3562BBC/ThaliTest.app/www/index.html
,2016-02-09 17:35:06.336 ThaliTest[1699:2989114] JXcore Cordova plugin initializing
2016-02-09 17:35:06.338 ThaliTest[1699:2989337] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7779FD42-391B-4FC2-ADFC-6926D3562BBC/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7779FD42-391B-4FC2-ADFC-6926D3562BBC/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7779FD42-391B-4FC2-ADFC-6926D3562BBC/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7779FD42-391B-4FC2-ADFC-6926D3562BBC/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7779FD42-391B-4FC2-ADFC-6926D3562BBC/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7779FD42-391B-4FC2-ADFC-6926D3562BBC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7779FD42-391B-4FC2-ADFC-6926D3562BBC/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7779FD42-391B-4FC2-ADFC-6926D3562BBC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7779FD42-391B-4FC2-ADFC-6926D3562BBC/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7779FD42-391B-4FC2-ADFC-6926D3562BBC/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# #generatePreambleAndBeacons null ECDH for local device

,ok 1 publicKeysToNotify cannot be null

# teardown

,# setup

# #generatePreambleAndBeacons null ECDH for local device

,ok 2 ecdhForLocalDevice cannot be null

# teardown

# setup

# #generatePreambleAndBeacons expiration out of range lower

ok 3 secondsUntilExpiration out of range.

# teardown

# setup

# #generatePreambleAndBeacons expiration out of range upper

,ok 4 secondsUntilExpiration out of range.

,# teardown

,# setup

# #generatePreambleAndBeacons empty keys to notify

,ok 5 should be equal

,# teardown

,# setup

# #generatePreambleAndBeacons multiple keys to notify

,ok 6 should be equal

ok 7 should be equal
,
,ok 8 should be equal

,ok 9 should be equal

,# teardown

,# setup

,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,ok 10 should throw

,# teardown

# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,ok 11 Preamble expiration must be a 64 bit integer

# teardown

,# setup

,# #parseBeacons expiration out of range lower

,ok 12 Expiration out of range
,
# teardown

,# setup

# #parseBeacons expiration out of range lower

,ok 13 Expiration out of range

# teardown

# setup

,# #parseBeacons no beacons returns null

,ok 14 should be equal

# teardown

# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,ok 15 Malformed encrypted beacon key ID

,# teardown

# setup

,# #parseBeacons addressBookCallback fails decrypt

,ok 16 should be equal

# teardown

,# setup

# #parseBeacons addressBookCallback returns no matches

,ok 17 should be equal

,ok 18 should be equal

# teardown

,# setup

,# #parseBeacons addressBookCallback returns public key

,ok 19 should be equal

,ok 20 (unnamed assert)

,# teardown

,# setup

,# #parseBeacons with beacons both for and not for the user

,ok 21 (unnamed assert)

,# teardown

,# setup

,# multiplex can send data

,ok 22 String should be length:200

,# teardown

,# setup

,# enqueue and run in order

,ok 23 firstPromise setTimeout

,ok 24 firstPromise result

,ok 25 firstPromise testValue

,ok 26 secondPromise setTimeout

,ok 27 secondPromise result

,ok 28 secondPromise testValue

,ok 29 thirdPromise in promise

,ok 30 thirdPromise result

,ok 31 thirdPromise testValue

,# teardown

,# setup

,# basic

,ok 32 sane

,# teardown

,# setup

,# another

,ok 33 sane

,# teardown

,# setup

,# successfully create a new pkcs12 file and return hash value

,ok 34 should be equal

,ok 35 null

,ok 36 (unnamed assert)

,ok 37 should be equal

,ok 38 should not throw

,# teardown

,# setup

,# successfully read a previous pkcs12 file and return hash value

,ok 39 (unnamed assert)

,ok 40 (unnamed assert)

,ok 41 should not throw

,ok 42 should be equal

,ok 43 should be equal

,# teardown

,# setup

,# failed to extract public key because of corrupt pkcs12 file

,ok 44 should be equal

,# teardown

,# setup

,# failed to get mobile documents path

,ok 45 should be equal

,# teardown

,# setup

,# #init should register the peerAvailabilityChanged event

,ok 46 should be equal

,ok 47 should be equal

,ok 48 should be equal

,# teardown

,# setup

,# #init should register the networkChanged event

,ok 49 should be equal

,# teardown

,# setup

,# #startBroadcasting should throw on null device name

,ok 50 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on empty string device name

,ok 51 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on non-number port

,ok 52 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on NaN port

,ok 53 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on negative port

,ok 54 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on too large port

,ok 55 should throw

,# teardown

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,ok 56 should be equal

,ok 57 should be equal

,ok 58 should be equal

,# teardown
,
,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,ok 59 should be equal

,ok 60 should be equal

,ok 61 should be equal

,# teardown

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,ok 62 should be equal

,ok 63 should be equal

,# teardown

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,ok 64 should be equal

,ok 65 should be equal

,# teardown

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,ok 66 should be equal

,ok 67 should be equal

,ok 68 should be equal

,# teardown

,# setup

,# #connect should call Mobile("Connect") and handle an error

,ok 69 should be equal

,ok 70 should be equal

,# teardown

,# setup

,# should call Mobile("Disconnect") without an error

,ok 71 should be equal

,ok 72 should be equal

,# teardown

,# setup

,# should call Mobile("Disconnect") and handle an error

,ok 73 should be equal

,ok 74 should be equal

,# teardown

,# setup

,# #start should fail if called twice in a row

,ok 75 specific error should be received

,# teardown

,# setup

,# #startListeningForAdvertisements should fail if start not called

,ok 76 specific error should be returned

,# teardown

,# setup

,# should be able to call #stopListeningForAdvertisements many times

,ok 77 error should be null

,ok 78 error should be null

,# teardown

,# setup

,# should be able to call #startListeningForAdvertisements many times

,ok 79 error should be null

,ok 80 error should be null

,# teardown

,# setup

,# should be able to call #startUpdateAdvertisingAndListening many times

,ok 81 error should be null

,ok 82 error should be null

,# teardown

,# setup

,# #startUpdateAdvertisingAndListening should fail if start not called

,ok 83 specific error should be returned

,# teardown

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,2016-02-09 17:39:16.028 ThaliTest[1699:2989337] jxcore: startBroadcasting
,2016-02-09 17:39:16.045 ThaliTest[1699:2989337] server: starting 1455035956028.1699.H4hvkg==
,2016-02-09 17:39:16.046 ThaliTest[1699:2989337] multipeer session: start timer: 0x16a09300
2016-02-09 17:39:16.047 ThaliTest[1699:2989337] THEMultipeerSession initialized peer 1455035956028.1699
2016-02-09 17:39:16.049 ThaliTest[1699:2989337] jxcore: sta,rtBroadcasting: success
ok 84 Should be able to call startBroadcasting without error

,2016-02-09 17:39:16.052 ThaliTest[1699:2989337] jxcore: stopBroadcasting
,2016-02-09 17:39:16.053 ThaliTest[1699:2989337] THEMultipeerSession stopping peer
2016-02-09 17:39:16.054 ThaliTest[1699:2989337] multipeer session: stop timer
2016-02-09 17:39:16.056 ThaliTest[1699:2989337] jxcore: stopBroadcasting: success
ok 85 Shoul,d be able to call stopBroadcasting without error

2016-02-09 17:39:16.058 ThaliTest[1699:2989337] jxcore: startBroadcasting
,2016-02-09 17:39:16.067 ThaliTest[1699:2989337] server: starting 1455035956057.1699.6cOdZQ==
2016-02-09 17:39:16.068 ThaliTest[1699:2989337] multipeer session: start timer: 0x15a63ab0
2016-02-09 17:39:16.068 ThaliTest[1699:2989337] THEMultipeerSession in,itialized peer 1455035956057.1699
2016-02-09 17:39:16.069 ThaliTest[1699:2989337] jxcore: startBroadcasting: success
ok 86 Should be able to call startBroadcasting without error

,2016-02-09 17:39:16.071 ThaliTest[1699:2989337] jxcore: stopBroadcasting
2016-02-09 17:39:16.072 ThaliTest[1699:2989337] THEMultipeerSession stopping peer
,2016-02-09 17:39:16.072 ThaliTest[1699:2989337] multipeer session: stop timer
,2016-02-09 17:39:16.074 ThaliTest[1699:2989337] jxcore: stopBroadcasting: success
ok 87 Should be able to call stopBroadcasting without error

,2016-02-09 17:39:16.076 ThaliTest[1699:2989337] jxcore: startBroadcasting
,2016-02-09 17:39:16.083 ThaliTest[1699:2989337] server: starting 1455035956076.1699.S2QUhQ==
2016-02-09 17:39:16.084 ThaliTest[1699:2989337] multipeer session: start timer: 0x16e3eb00
2016-02-09 17:39:16.084 ThaliTest[1699:2989337] THEMultipeerSession initialized peer 1455035956076.1699
,2016-02-09 17:39:16.085 ThaliTest[1699:2989337] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error

2016-02-09 17:39:16.091 ThaliTest[1699:2989337] jxcore: stopBroadcasting
2016-02-09 17:39:16.092 ThaliTest[,1699:2989337] THEMultipeerSession stopping peer
2016-02-09 17:39:16.092 ThaliTest[1699:2989337] multipeer session: stop timer
2016-02-09 17:39:16.092 ThaliTest[1699:2989337] jxcore: stopBroadcasting: success
ok 89 Should be able to call stopBroadcasting, without error

2016-02-09 17:39:16.094 ThaliTest[1699:2989337] jxcore: startBroadcasting
,2016-02-09 17:39:16.100 ThaliTest[1699:2989337] server: starting 1455035956093.1699.XRKuxg==
2016-02-09 17:39:16.101 ThaliTest[1699:2989337] multipeer session: start timer: 0x16920c40
2016-02-09 17:39:16.101 ThaliTest[1699:2989337] THEMultipeerSession in,itialized peer 1455035956093.1699
2016-02-09 17:39:16.107 ThaliTest[1699:2989337] jxcore: startBroadcasting: success
ok 90 Should be able to call startBroadcasting without error

2016-02-09 17:39:16.110 ThaliTest[1699:2989337] jxcore: stopBroadcasting,
2016-02-09 17:39:16.110 ThaliTest[1699:2989337] THEMultipeerSession stopping peer
2016-02-09 17:39:16.110 ThaliTest[1699:2989337] multipeer session: stop timer
2016-02-09 17:39:16.111 ThaliTest[1699:2989337] jxcore: stopBroadcasting: success
ok 91 Shou,ld be able to call stopBroadcasting without error

,2016-02-09 17:39:16.113 ThaliTest[1699:2989337] jxcore: startBroadcasting
,2016-02-09 17:39:16.124 ThaliTest[1699:2989337] server: starting 1455035956113.1699.Wl1QAA==
,2016-02-09 17:39:16.129 ThaliTest[1699:2989337] multipeer session: start timer: 0x16e3c460
2016-02-09 17:39:16.130 ThaliTest[1699:2989337] THEMultipeerSession initialized peer 1455035956113.1699
2016-02-09 17:39:16.130 ThaliTest[1699:2989337] jxcore: sta,rtBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

2016-02-09 17:39:16.132 ThaliTest[1699:2989337] jxcore: stopBroadcasting
2016-02-09 17:39:16.132 ThaliTest[1699:2989337] THEMultipeerSession stopping peer
2016-02-09, 17:39:16.133 ThaliTest[1699:2989337] multipeer session: stop timer
2016-02-09 17:39:16.133 ThaliTest[1699:2989337] jxcore: stopBroadcasting: success
ok 93 Should be able to call stopBroadcasting without error

2016-02-09 17:39:16.135 ThaliTest[1699:29,89337] jxcore: startBroadcasting
,2016-02-09 17:39:16.140 ThaliTest[1699:2989337] server: starting 1455035956134.1699.GAUiZQ==
2016-02-09 17:39:16.141 ThaliTest[1699:2989337] multipeer session: start timer: 0x16ac6890
2016-02-09 17:39:16.141 ThaliTest[1699:2989337] THEMultipeerSession initialized peer 1455035956134.1699
,2016-02-09 17:39:16.141 ThaliTest[1699:2989337] jxcore: startBroadcasting: success
,ok 94 Should be able to call startBroadcasting without error
,
,2016-02-09 17:39:16.151 ThaliTest[1699:2989337] jxcore: stopBroadcasting
,2016-02-09 17:39:16.152 ThaliTest[1699:2989337] THEMultipeerSession stopping peer
,2016-02-09 17:39:16.153 ThaliTest[1699:2989337] multipeer session: stop timer
,2016-02-09 17:39:16.153 ThaliTest[1699:2989337] jxcore: stopBroadcasting: success
,ok 95 Should be able to call stopBroadcasting without error
,
,2016-02-09 17:39:16.158 ThaliTest[1699:2989337] jxcore: startBroadcasting
,2016-02-09 17:39:16.160 ThaliTest[1699:2989337] server: starting 1455035956158.1699.aQD2nA==
,2016-02-09 17:39:16.162 ThaliTest[1699:2989337] multipeer session: start timer: 0x16953ff0
,2016-02-09 17:39:16.165 ThaliTest[1699:2989337] THEMultipeerSession initialized peer 1455035956158.1699
,2016-02-09 17:39:16.168 ThaliTest[1699:2989337] jxcore: startBroadcasting: success
,ok 96 Should be able to call startBroadcasting without error

,2016-02-09 17:39:16.171 ThaliTest[1699:2989337] jxcore: stopBroadcasting
,2016-02-09 17:39:16.171 ThaliTest[1699:2989337] THEMultipeerSession stopping peer
,2016-02-09 17:39:16.172 ThaliTest[1699:2989337] multipeer session: stop timer
,2016-02-09 17:39:16.177 ThaliTest[1699:2989337] jxcore: stopBroadcasting: success
,ok 97 Should be able to call stopBroadcasting without error

,2016-02-09 17:39:16.179 ThaliTest[1699:2989337] jxcore: startBroadcasting
,2016-02-09 17:39:16.181 ThaliTest[1699:2989337] server: starting 1455035956178.1699.boEoDw==
,2016-02-09 17:39:16.184 ThaliTest[1699:2989337] multipeer session: start timer: 0x16e401f0
,2016-02-09 17:39:16.186 ThaliTest[1699:2989337] THEMultipeerSession initialized peer 1455035956178.1699
,2016-02-09 17:39:16.190 ThaliTest[1699:2989337] jxcore: startBroadcasting: success
,ok 98 Should be able to call startBroadcasting without error

,2016-02-09 17:39:16.192 ThaliTest[1699:2989337] jxcore: stopBroadcasting
,2016-02-09 17:39:16.192 ThaliTest[1699:2989337] THEMultipeerSession stopping peer
,2016-02-09 17:39:16.193 ThaliTest[1699:2989337] multipeer session: stop timer
,2016-02-09 17:39:16.195 ThaliTest[1699:2989337] jxcore: stopBroadcasting: success
,ok 99 Should be able to call stopBroadcasting without error
,
,2016-02-09 17:39:16.199 ThaliTest[1699:2989337] jxcore: startBroadcasting
,2016-02-09 17:39:16.202 ThaliTest[1699:2989337] server: starting 1455035956199.1699.6takkQ==
,2016-02-09 17:39:16.205 ThaliTest[1699:2989337] multipeer session: start timer: 0x16934590
,2016-02-09 17:39:16.210 ThaliTest[1699:2989337] THEMultipeerSession initialized peer 1455035956199.1699
,2016-02-09 17:39:16.211 ThaliTest[1699:2989337] jxcore: startBroadcasting: success
,ok 100 Should be able to call startBroadcasting without error

,2016-02-09 17:39:16.213 ThaliTest[1699:2989337] jxcore: stopBroadcasting
,2016-02-09 17:39:16.213 ThaliTest[1699:2989337] THEMultipeerSession stopping peer
,2016-02-09 17:39:16.214 ThaliTest[1699:2989337] multipeer session: stop timer
,2016-02-09 17:39:16.216 ThaliTest[1699:2989337] jxcore: stopBroadcasting: success
,ok 101 Should be able to call stopBroadcasting without error

,2016-02-09 17:39:16.221 ThaliTest[1699:2989337] jxcore: startBroadcasting
,2016-02-09 17:39:16.224 ThaliTest[1699:2989337] server: starting 1455035956220.1699.8bJErw==
,2016-02-09 17:39:16.225 ThaliTest[1699:2989337] multipeer session: start timer: 0x16e3c110
,2016-02-09 17:39:16.229 ThaliTest[1699:2989337] THEMultipeerSession initialized peer 1455035956220.1699
,2016-02-09 17:39:16.233 ThaliTest[1699:2989337] jxcore: startBroadcasting: success
,ok 102 Should be able to call startBroadcasting without error

,2016-02-09 17:39:16.236 ThaliTest[1699:2989337] jxcore: stopBroadcasting
,2016-02-09 17:39:16.236 ThaliTest[1699:2989337] THEMultipeerSession stopping peer
,2016-02-09 17:39:16.237 ThaliTest[1699:2989337] multipeer session: stop timer
,2016-02-09 17:39:16.238 ThaliTest[1699:2989337] jxcore: stopBroadcasting: success
,ok 103 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,2016-02-09 17:39:16.504 ThaliTest[1699:2989337] jxcore: startBroadcasting
,2016-02-09 17:39:16.508 ThaliTest[1699:2989337] server: starting 1455035956504.1699.eete6g==
,2016-02-09 17:39:16.511 ThaliTest[1699:2989337] multipeer session: start timer: 0x16e41ec0
,2016-02-09 17:39:16.519 ThaliTest[1699:2989337] THEMultipeerSession initialized peer 1455035956504.1699
,2016-02-09 17:39:16.521 ThaliTest[1699:2989337] jxcore: startBroadcasting: success
,ok 104 Should be able to call startBroadcasting without error

,2016-02-09 17:39:16.526 ThaliTest[1699:2989337] jxcore: startBroadcasting
,2016-02-09 17:39:16.527 ThaliTest[1699:2989337] jxcore: startBroadcasting: failure
,ok 105 Cannot call startBroadcasting twice

,2016-02-09 17:39:16.532 ThaliTest[1699:2989337] jxcore: stopBroadcasting
,2016-02-09 17:39:16.533 ThaliTest[1699:2989337] THEMultipeerSession stopping peer
,2016-02-09 17:39:16.536 ThaliTest[1699:2989337] multipeer session: stop timer
,2016-02-09 17:39:16.539 ThaliTest[1699:2989337] jxcore: stopBroadcasting: success
,ok 106 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter throws on connection to bad peer

,2016-02-09 17:39:22.569 ThaliTest[1699:2989337] jxcore: startBroadcasting
,2016-02-09 17:39:22.574 ThaliTest[1699:2989337] server: starting 1455035962568.1699.+ekfhA==
2016-02-09 17:39:22.574 ThaliTest[1699:2989337] multipeer session: start timer: 0x16e486b0
2016-02-09 17:39:22.575 ThaliTest[1699:2989337] THEMultipeerSession in,itialized peer 1455035962568.1699
2016-02-09 17:39:22.575 ThaliTest[1699:2989337] jxcore: startBroadcasting: success
ok 107 Should be able to call startBroadcasting without error

2016-02-09 17:39:22.577 ThaliTest[1699:2989337] jxcore: connect foobar
,2016-02-09 17:39:22.578 ThaliTest[1699:2989337] client: unknown peer foobar
2016-02-09 17:39:22.578 ThaliTest[1699:2989337] jxcore: connect: fail: Unknown peer
,ok 108 Should not connect to a bad peer

,2016-02-09 17:39:22.582 ThaliTest[1699:2989337] jxcore: stopBroadcasting
2016-02-09 17:39:22.583 ThaliTest[1699:2989337] THEMultipeerSession stopping peer
2016-02-09 17:39:22.584 ThaliTest[1699:2989337] multipeer session: stop timer
2016-02-09 17:39:22.585 ThaliTest[1699:2989337] jxcore: stopBroadcasting: success
,ok 109 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,2016-02-09 17:39:29.206 ThaliTest[1699:2989337] jxcore: startBroadcasting
,2016-02-09 17:39:29.209 ThaliTest[1699:2989337] server: starting 1455035969205.1699.NGMJhg==
2016-02-09 17:39:29.210 ThaliTest[1699:2989337] multipeer session: start timer: 0x16c40640
2016-02-09 17:39:29.210 ThaliTest[1699:2989337] THEMultipeerSession in,itialized peer 1455035969205.1699
2016-02-09 17:39:29.211 ThaliTest[1699:2989337] jxcore: startBroadcasting: success
ok 110 Should be able to call startBroadcasting without error

2016-02-09 17:39:29.213 ThaliTest[1699:2989337] jxcore: disconnect
2016-02-09 17:39:29.214 ThaliTest[1699:2989337] jxcore: disconnect: fail
,ok 111 Disconnect should fail to a non-existant peer 

,2016-02-09 17:39:29.217 ThaliTest[1699:2989337] jxcore: stopBroadcasting
,2016-02-09 17:39:29.218 ThaliTest[1699:2989337] THEMultipeerSession stopping peer
,2016-02-09 17:39:29.219 ThaliTest[1699:2989337] multipeer session: stop timer
,2016-02-09 17:39:29.220 ThaliTest[1699:2989337] jxcore: stopBroadcasting: success
ok 112 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter can discover and connect to peers

,2016-02-09 17:39:32.720 ThaliTest[1699:2989337] jxcore: startBroadcasting
,2016-02-09 17:39:32.724 ThaliTest[1699:2989337] server: starting 1455035972720.1699.u2Muug==
2016-02-09 17:39:32.725 ThaliTest[1699:2989337] multipeer session: start timer: 0x16c43a90
2016-02-09 17:39:32.725 ThaliTest[1699:2989337] THEMultipeerSession in,itialized peer 1455035972720.1699
2016-02-09 17:39:32.726 ThaliTest[1699:2989337] jxcore: startBroadcasting: success
,ok 113 Should be able to call startBroadcasting without error

,2016-02-09 17:39:34.886 ThaliTest[1699:2989114] multipeer session: reset timer
2016-02-09 17:39:34.886 ThaliTest[1699:2989114] multipeer session: stop timer
2016-02-09 17:39:34.886 ThaliTest[1699:2989114] multipeer session: start timer: 0x16c43a90
2016-,02-09 17:39:34.887 ThaliTest[1699:2989114] server session: connect
2016-02-09 17:39:34.887 ThaliTest[1699:2989114] server session: stateChange:0->1 1455035975314.1160
,2016-02-09 17:39:34.899 ThaliTest[1699:2989114] server: accepting invitation 1455035975314.1160
,2016-02-09 17:39:35.001 ThaliTest[1699:2989114] client: found peer: 1455035975314.1160.ssJGLg==
2016-02-09 17:39:35.003 ThaliTest[1699:2989337] jxcore: connect 1455035975314.1160.ssJGLg==
2016-02-09 17:39:35.005 ThaliTest[1699:2989337] client session: connect
2016-02-09 17:39:35.005 ThaliTest[1699:2989337] client session: stateChange:0->1 1455035975314.1160.ssJGLg==
,2016-02-09 17:39:37.493 ThaliTest[1699:2989777] server session: connected
2016-02-09 17:39:37.493 ThaliTest[1699:2989777] server session: stateChange:1->2 1455035975314.1160
,2016-02-09 17:39:37.553 ThaliTest[1699:2989778] server session: not connected 1455035975314.1160
,2016-02-09 17:39:38.578 ThaliTest[1699:2989778] client session: connected
2016-02-09 17:39:38.579 ThaliTest[1699:2989778] client session: stateChange:1->2 1455035975314.1160.ssJGLg==
,2016-02-09 17:39:38.594 ThaliTest[1699:2989778] client session: fireConnectCallback: 1455035975314.1160.ssJGLg==
2016-02-09 17:39:38.594 ThaliTest[1699:2989778] jxcore: connect: success
,ok 114 Should be able to connect without error

,ok 115 Port should be within range

,2016-02-09 17:39:38.599 ThaliTest[1699:2989337] jxcore: disconnect
2016-02-09 17:39:38.600 ThaliTest[1699:2989337] client session: disconnectFromPeer: 1455035975314.1160.ssJGLg==
2016-02-09 17:39:38.600 ThaliTest[1699:2989337] client session: disconnect
,2016-02-09 17:39:38.601 ThaliTest[1699:2989337] client session: stateChange:2->0 1455035975314.1160.ssJGLg==
,2016-02-09 17:39:38.681 ThaliTest[1699:2989337] jxcore: disconnect: success
ok 116 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.
,
,# teardown

,calling stopBroadcasting

,2016-02-09 17:39:38.718 ThaliTest[1699:2989337] jxcore: stopBroadcasting
2016-02-09 17:39:38.719 ThaliTest[1699:2989337] THEMultipeerSession stopping peer
2016-02-09 17:39:38.719 ThaliTest[1699:2989337] multipeer session: stop timer
2016-02-09 17:39:38.,720 ThaliTest[1699:2989337] server session: disconnect
2016-02-09 17:39:38.720 ThaliTest[1699:2989337] server session: stateChange:2->0 1455035975314.1160
,2016-02-09 17:39:39.301 ThaliTest[1699:2989337] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# setup

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,2016-02-09 17:39:40.192 ThaliTest[1699:2989337] jxcore: startBroadcasting
,2016-02-09 17:39:40.196 ThaliTest[1699:2989337] server: starting 1455035980192.1699.WaSZTQ==
2016-02-09 17:39:40.197 ThaliTest[1699:2989337] multipeer session: start timer: 0x14548940
2016-02-09 17:39:40.197 ThaliTest[1699:2989337] THEMultipeerSession in,itialized peer 1455035980192.1699
2016-02-09 17:39:40.197 ThaliTest[1699:2989337] jxcore: startBroadcasting: success
ok 117 Should be able to call startBroadcasting without error

,2016-02-09 17:39:41.624 ThaliTest[1699:2989114] multipeer session: reset timer
2016-02-09 17:39:41.624 ThaliTest[1699:2989114] multipeer session: stop timer
2016-02-09 17:39:41.625 ThaliTest[1699:2989114] multipeer session: start timer: 0x14548940
2016-,02-09 17:39:41.625 ThaliTest[1699:2989114] server session: connect
,2016-02-09 17:39:41.625 ThaliTest[1699:2989114] server session: stateChange:0->1 1455035982337.1160
,2016-02-09 17:39:41.633 ThaliTest[1699:2989114] server: accepting invitation 1455035982337.1160
,2016-02-09 17:39:41.669 ThaliTest[1699:2989114] client: found peer: 1455035982337.1160.xnLe7Q==
2016-02-09 17:39:41.672 ThaliTest[1699:2989337] jxcore: connect 1455035982337.1160.xnLe7Q==
2016-02-09 17:39:41.673 ThaliTest[1699:2989337] client session: connect
2016-02-09 17:39:41.673 ThaliTest[1699:2989337] client session: stateChange:0->1 1455035982337.1160.xnLe7Q==
,2016-02-09 17:39:44.170 ThaliTest[1699:2989848] server session: connected
2016-02-09 17:39:44.173 ThaliTest[1699:2989848] server session: stateChange:1->2 1455035982337.1160
,2016-02-09 17:39:44.180 ThaliTest[1699:2989114] server relay: socket disconnected
2016-02-09 17:39:44.181 ThaliTest[1699:2989114] server relay: 0x16e5dab0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 17:39:44.236 ThaliTest[1699:2989847] server session: not connected 1455035982337.1160
,2016-02-09 17:39:44.404 ThaliTest[1699:2989848] client session: connected
,2016-02-09 17:39:44.405 ThaliTest[1699:2989848] client session: stateChange:1->2 1455035982337.1160.xnLe7Q==
,2016-02-09 17:39:44.410 ThaliTest[1699:2989848] client session: fireConnectCallback: 1455035982337.1160.xnLe7Q==
2016-02-09 17:39:44.410 ThaliTest[1699:2989848] jxcore: connect: success
ok 118 Should be able to connect without error

ok 119 Port should, be within range

2016-02-09 17:39:44.414 ThaliTest[1699:2989337] jxcore: connect 1455035982337.1160.xnLe7Q==
2016-02-09 17:39:44.414 ThaliTest[1699:2989337] client: already connect(ing/ed) to 1455035982337.1160.xnLe7Q==
2016-02-09 17:39:44.415 ThaliTe,st[1699:2989337] jxcore: connect: fail: Aleady connecting
ok 120 Should fail on double connect

,2016-02-09 17:39:44.418 ThaliTest[1699:2989337] jxcore: disconnect
,2016-02-09 17:39:44.418 ThaliTest[1699:2989337] client session: disconnectFromPeer: 1455035982337.1160.xnLe7Q==
,2016-02-09 17:39:44.420 ThaliTest[1699:2989337] client session: disconnect
,2016-02-09 17:39:44.421 ThaliTest[1699:2989337] client session: stateChange:2->0 1455035982337.1160.xnLe7Q==
,2016-02-09 17:39:44.499 ThaliTest[1699:2989337] jxcore: disconnect: success
,ok 121 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# teardown

,calling stopBroadcasting

,2016-02-09 17:39:44.551 ThaliTest[1699:2989337] jxcore: stopBroadcasting
2016-02-09 17:39:44.551 ThaliTest[1699:2989337] THEMultipeerSession stopping peer
2016-02-09 17:39:44.551 ThaliTest[1699:2989337] multipeer session: stop timer
2016-02-09 17:39:44.,552 ThaliTest[1699:2989337] server session: disconnect
2016-02-09 17:39:44.552 ThaliTest[1699:2989337] server session: stateChange:2->0 1455035982337.1160
2016-02-09 17:39:44.553 ThaliTest[1699:2989337] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined

# setup

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,2016-02-09 17:39:45.077 ThaliTest[1699:2989337] jxcore: startBroadcasting
,2016-02-09 17:39:45.081 ThaliTest[1699:2989337] server: starting 1455035985077.1699.X332/g==
2016-02-09 17:39:45.082 ThaliTest[1699:2989337] multipeer session: start timer: 0x16e565c0
2016-02-09 17:39:45.082 ThaliTest[1699:2989337] THEMultipeerSession initialized peer 1455035985077.1699
2016-02-09 17:39:45.083 ThaliTest[1699:2989337] jxcore: startBroadcasting: success
ok 122 Should be able to call startBroadcasting without error

,2016-02-09 17:39:46.188 ThaliTest[1699:2989114] client: found peer: 1455035986775.1160.2Cwjhw==
2016-02-09 17:39:46.189 ThaliTest[1699:2989337] jxcore: connect 1455035986775.1160.2Cwjhw==
2016-02-09 17:39:46.190 ThaliTest[1699:2989337] client session: co,nnect
2016-02-09 17:39:46.190 ThaliTest[1699:2989337] client session: stateChange:0->1 1455035986775.1160.2Cwjhw==
,2016-02-09 17:39:46.263 ThaliTest[1699:2989114] multipeer session: reset timer
2016-02-09 17:39:46.263 ThaliTest[1699:2989114] multipeer session: stop timer
2016-02-09 17:39:46.264 ThaliTest[1699:2989114] multipeer session: start timer: 0x16e565c0
2016-,02-09 17:39:46.264 ThaliTest[1699:2989114] server session: connect
2016-02-09 17:39:46.264 ThaliTest[1699:2989114] server session: stateChange:0->1 1455035986775.1160
,2016-02-09 17:39:46.276 ThaliTest[1699:2989114] server: accepting invitation 1455035986775.1160
,2016-02-09 17:39:48.708 ThaliTest[1699:2989831] client session: connected
2016-02-09 17:39:48.708 ThaliTest[1699:2989831] client session: stateChange:1->2 1455035986775.1160.2Cwjhw==
,2016-02-09 17:39:48.731 ThaliTest[1699:2989778] server session: connected
,2016-02-09 17:39:48.732 ThaliTest[1699:2989778] server session: stateChange:1->2 1455035986775.1160
,2016-02-09 17:39:48.746 ThaliTest[1699:2989847] client session: fireConnectCallback: 1455035986775.1160.2Cwjhw==
,2016-02-09 17:39:48.748 ThaliTest[1699:2989847] jxcore: connect: success
,ok 123 Should be able to connect without error

,ok 124 Port should be within range

,2016-02-09 17:39:48.753 ThaliTest[1699:2989337] jxcore: disconnect
,2016-02-09 17:39:48.754 ThaliTest[1699:2989337] client session: disconnectFromPeer: 1455035986775.1160.2Cwjhw==
,2016-02-09 17:39:48.755 ThaliTest[1699:2989337] client session: disconnect
,2016-02-09 17:39:48.757 ThaliTest[1699:2989337] client session: stateChange:2->0 1455035986775.1160.2Cwjhw==
,2016-02-09 17:39:48.768 ThaliTest[1699:2989114] server relay: socket disconnected
,2016-02-09 17:39:48.770 ThaliTest[1699:2989114] server relay: 0x16e5a770 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 17:39:48.793 ThaliTest[1699:2989847] server session: not connected 1455035986775.1160
,2016-02-09 17:39:48.865 ThaliTest[1699:2989337] jxcore: disconnect: success
ok 125 Should be able to disconnect without error

,2016-02-09 17:39:48.867 ThaliTest[1699:2989337] jxcore: disconnect
2016-02-09 17:39:48.868 ThaliTest[1699:2989337] jxcore: disconnect: fail
,ok 126 Disconnect should fail 

,setting stopBroadcasting callback and ending test.

,# teardown

,calling stopBroadcasting

2016-02-09 17:39:49.199 ThaliTest[1699:2989337] jxcore: stopBroadcasting
2016-02-09 17:39:49.199 ThaliTest[1699:2989337] THEMultipeerSession stopping peer
2016-02-09 17:39:49.200 ThaliTest[1699:2989337] multipeer session: stop timer
2016-02-09 17:39:49.200 ThaliTest[1699:2989337] server session: disconnect
2016-02-09 17:39:49.200 ThaliTest[1699:2989337] server session: stateChange:2->0 1455035986775.1160
2016-02-09 17:39:49.203 ThaliTest[1699:2989337] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# setup

,# ThaliEmitter can connect and send data

,echo server started on port: 60707

,2016-02-09 17:39:50.350 ThaliTest[1699:2989337] jxcore: startBroadcasting
,2016-02-09 17:39:50.352 ThaliTest[1699:2989337] server: starting 1455035990350.1699.a0DoHA==
2016-02-09 17:39:50.352 ThaliTest[1699:2989337] multipeer session: start timer: 0x16e4ef60
2016-02-09 17:39:50.352 ThaliTest[1699:2989337] THEMultipeerSession initialized peer 1455035990350.1699
2016-02-09 17:39:50.352 ThaliTest[1699:2989337] jxcore: startBroadcasting: success
ok 127 Should be able to call startBroadcasting without error

,2016-02-09 17:39:50.358 ThaliTest[1699:2989114] client: found peer: 1455035985077.1699.X332/g==
2016-02-09 17:39:50.359 ThaliTest[1699:2989114] client: found peer: 1455035986775.1160.2Cwjhw==
,2016-02-09 17:39:50.360 ThaliTest[1699:2989337] jxcore: connect 1455035985077.1699.X332/g==
2016-02-09 17:39:50.361 ThaliTest[1699:2989337] client session: connect
2016-02-09 17:39:50.361 ThaliTest[1699:2989337] client session: stateChange:0->1 1455035985077.1699.X332/g==
,2016-02-09 17:39:50.365 ThaliTest[1699:2989337] jxcore: connect 1455035986775.1160.2Cwjhw==
2016-02-09 17:39:50.366 ThaliTest[1699:2989337] client session: connect
2016-02-09 17:39:50.366 ThaliTest[1699:2989337] client session: stateChange:0->1 1455035986775.1160.2Cwjhw==
,2016-02-09 17:39:51.750 ThaliTest[1699:2989114] client: lost peer: 1455035985077.1699.X332/g==
2016-02-09 17:39:51.750 ThaliTest[1699:2989114] client session: onPeerLost: 1455035985077.1699.X332/g==
2016-02-09 17:39:51.750 ThaliTest[1699:2989114] client ,session: onLinkFailure: 1455035985077.1699.X332/g==
2016-02-09 17:39:51.750 ThaliTest[1699:2989114] client session: disconnect
2016-02-09 17:39:51.751 ThaliTest[1699:2989114] client session: stateChange:1->0 1455035985077.1699.X332/g==
2016-02-09 17:39:,51.751 ThaliTest[1699:2989114] client session: fireConnectCallback: 1455035985077.1699.X332/g==
2016-02-09 17:39:51.752 ThaliTest[1699:2989114] jxcore: connect: fail: Peer disconnected
,2016-02-09 17:39:52.540 ThaliTest[1699:2989114] client: found peer: 1455035991992.1160.dYOKkQ==
2016-02-09 17:39:52.542 ThaliTest[1699:2989337] jxcore: connect 1455035991992.1160.dYOKkQ==
2016-02-09 17:39:52.543 ThaliTest[1699:2989337] client session: connect
,2016-02-09 17:39:52.543 ThaliTest[1699:2989337] client session: stateChange:0->1 1455035991992.1160.dYOKkQ==
,2016-02-09 17:39:52.559 ThaliTest[1699:2989114] multipeer session: reset timer
2016-02-09 17:39:52.559 ThaliTest[1699:2989114] multipeer session: stop timer
2016-02-09 17:39:52.559 ThaliTest[1699:2989114] multipeer session: start timer: 0x16e4ef60
,2016-02-09 17:39:52.560 ThaliTest[1699:2989114] server session: connect
2016-02-09 17:39:52.562 ThaliTest[1699:2989114] server session: stateChange:0->1 1455035991992.1160
,2016-02-09 17:39:52.574 ThaliTest[1699:2989114] server: accepting invitation 1455035991992.1160
,2016-02-09 17:39:52.766 ThaliTest[1699:2989337] jxcore: connect 1455035985077.1699.X332/g==
2016-02-09 17:39:52.766 ThaliTest[1699:2989337] client: connect: unreachable 1455035985077.1699.X332/g==
2016-02-09 17:39:52.766 ThaliTest[1699:2989337] jxcore: connect: fail: Peer unreachable
,2016-02-09 17:39:58.418 ThaliTest[1699:2989777] server session: connected
2016-02-09 17:39:58.418 ThaliTest[1699:2989777] server session: stateChange:1->2 1455035991992.1160
,2016-02-09 17:39:59.553 ThaliTest[1699:2989847] client session: connected
2016-02-09 17:39:59.555 ThaliTest[1699:2989847] client session: stateChange:1->2 1455035991992.1160.dYOKkQ==
,2016-02-09 17:39:59.956 ThaliTest[1699:2989114] server relay: connected (to port: 60707)
,2016-02-09 17:40:02.060 ThaliTest[1699:2989831] client session: fireConnectCallback: 1455035991992.1160.dYOKkQ==
2016-02-09 17:40:02.060 ThaliTest[1699:2989831] jxcore: connect: success
ok 128 Should be able to connect without error

,ok 129 Port should be within range

,2016-02-09 17:40:02.067 ThaliTest[1699:2989114] client: relay established
2016-02-09 17:40:02.068 ThaliTest[1699:2989114] client: new accepted socket: 0x146ae720
,2016-02-09 17:40:03.564 ThaliTest[1699:2989114] client: lost peer: 1455035986775.1160.2Cwjhw==
2016-02-09 17:40:03.564 ThaliTest[1699:2989114] client session: onPeerLost: 1455035986775.1160.2Cwjhw==
2016-02-09 17:40:03.565 ThaliTest[1699:2989114] client ,session: onLinkFailure: 1455035986775.1160.2Cwjhw==
2016-02-09 17:40:03.565 ThaliTest[1699:2989114] client session: disconnect
2016-02-09 17:40:03.565 ThaliTest[1699:2989114] client session: stateChange:1->0 1455035986775.1160.2Cwjhw==
2016-02-09 17:40:,03.566 ThaliTest[1699:2989114] client session: fireConnectCallback: 1455035986775.1160.2Cwjhw==
2016-02-09 17:40:03.566 ThaliTest[1699:2989114] jxcore: connect: fail: Peer disconnected
,2016-02-09 17:40:04.581 ThaliTest[1699:2989337] jxcore: connect 1455035986775.1160.2Cwjhw==
2016-02-09 17:40:04.582 ThaliTest[1699:2989337] client: connect: unreachable 1455035986775.1160.2Cwjhw==
2016-02-09 17:40:04.582 ThaliTest[1699:2989337] jxcore: c,onnect: fail: Peer unreachable
,2016-02-09 17:40:13.939 ThaliTest[1699:2989847] client session: not connected 1455035991992.1160.dYOKkQ==
,2016-02-09 17:40:13.939 ThaliTest[1699:2989847] client session: onLinkFailure: 1455035991992.1160.dYOKkQ==
2016-02-09 17:40:13.942 ThaliTest[1699:2989847] client session: disconnect
2016-02-09 17:40:13.942 ThaliTest[1699:2989847] client session: stateChange:2->0 1455035991992.1160.dYOKkQ==
,2016-02-09 17:40:13.945 ThaliTest[1699:2989847] client session: fireConnectionErrorEvent: 1455035991992.1160.dYOKkQ==
,2016-02-09 17:40:22.560 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:40:22.602 ThaliTest[1699:2989114] client: found peer: 1455035991992.1160.dYOKkQ==
,2016-02-09 17:40:42.776 ThaliTest[1699:2989847] server session: not connected 1455035991992.1160
,2016-02-09 17:40:52.561 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:40:52.603 ThaliTest[1699:2989114] client: found peer: 1455035991992.1160.dYOKkQ==
,2016-02-09 17:41:22.561 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:41:22.605 ThaliTest[1699:2989114] client: found peer: 1455035991992.1160.dYOKkQ==
,2016-02-09 17:41:52.561 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:42:22.560 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:42:22.589 ThaliTest[1699:2989114] client: found peer: 1455035991992.1160.dYOKkQ==
,2016-02-09 17:42:52.561 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:42:52.597 ThaliTest[1699:2989114] client: found peer: 1455035991992.1160.dYOKkQ==
,2016-02-09 17:43:22.561 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:43:22.599 ThaliTest[1699:2989114] client: found peer: 1455035991992.1160.dYOKkQ==
,2016-02-09 17:43:52.560 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:43:52.599 ThaliTest[1699:2989114] client: found peer: 1455035991992.1160.dYOKkQ==
,2016-02-09 17:44:22.560 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:44:22.596 ThaliTest[1699:2989114] client: found peer: 1455035991992.1160.dYOKkQ==
,2016-02-09 17:44:52.560 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:44:52.597 ThaliTest[1699:2989114] client: found peer: 1455035991992.1160.dYOKkQ==
,2016-02-09 17:45:22.560 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:45:52.560 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:45:52.595 ThaliTest[1699:2989114] client: found peer: 1455035991992.1160.dYOKkQ==
,2016-02-09 17:46:22.561 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:46:22.600 ThaliTest[1699:2989114] client: found peer: 1455035991992.1160.dYOKkQ==
,2016-02-09 17:46:52.561 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:47:22.561 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:47:22.595 ThaliTest[1699:2989114] client: found peer: 1455035991992.1160.dYOKkQ==
,2016-02-09 17:47:52.561 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:47:52.591 ThaliTest[1699:2989114] client: found peer: 1455035991992.1160.dYOKkQ==
,2016-02-09 17:48:22.561 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:48:22.596 ThaliTest[1699:2989114] client: found peer: 1455035991992.1160.dYOKkQ==
,2016-02-09 17:48:52.561 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:49:22.561 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:49:22.595 ThaliTest[1699:2989114] client: found peer: 1455035991992.1160.dYOKkQ==
,2016-02-09 17:49:52.561 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:50:22.561 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:50:22.597 ThaliTest[1699:2989114] client: found peer: 1455035991992.1160.dYOKkQ==
,2016-02-09 17:50:52.561 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:50:52.596 ThaliTest[1699:2989114] client: found peer: 1455035991992.1160.dYOKkQ==
,2016-02-09 17:51:22.561 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:51:52.560 ThaliTest[1699:2989114] multipeer session: restart
,2016-02-09 17:51:52.590 ThaliTest[1699:2989114] client: found peer: 1455035991992.1160.dYOKkQ==
,2016-02-09 17:52:22.561 ThaliTest[1699:2989114] multipeer session: restart

```
