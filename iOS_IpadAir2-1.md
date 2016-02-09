#### Test 58751238ee11130_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58751238ee11130/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/495097F6-C559-4690-932D-EA30276D2C33/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/495097F6-C559-4690-932D-EA30276D2C33/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58751238ee11130/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58751238ee11130/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B3934E57-102E-4A40-982B-C74E0DB5A9DA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53298"
,(lldb)     command script import "/tmp/495097F6-C559-4690-932D-EA30276D2C33/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-02-09 15:20:20.839 ThaliTest[1112:1767624] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/280233D6-45AF-4B10-84C5-DA52122FA7D5/Library/Cookies/Cookies.binarycookies
,2016-02-09 15:20:21.215 ThaliTest[1112:1767624] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-09 15:20:21.216 ThaliTest[1112:1767624] Multi-tasking -> Device: YES, App: YES
,2016-02-09 15:20:21.225 ThaliTest[1112:1767624] Unlimited access to network resources
,2016-02-09 15:20:21.233 ThaliTest[1112:1767624] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 15:20:29.670 ThaliTest[1112:1767624] Resetting plugins due to page load.
,2016-02-09 15:20:32.933 ThaliTest[1112:1767624] Finished load of: file:///var/mobile/Containers/Bundle/Application/B3934E57-102E-4A40-982B-C74E0DB5A9DA/ThaliTest.app/www/index.html
,2016-02-09 15:20:33.096 ThaliTest[1112:1767624] JXcore Cordova plugin initializing
2016-02-09 15:20:33.097 ThaliTest[1112:1767859] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3934E57-102E-4A40-982B-C74E0DB5A9DA/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3934E57-102E-4A40-982B-C74E0DB5A9DA/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3934E57-102E-4A40-982B-C74E0DB5A9DA/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3934E57-102E-4A40-982B-C74E0DB5A9DA/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3934E57-102E-4A40-982B-C74E0DB5A9DA/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3934E57-102E-4A40-982B-C74E0DB5A9DA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3934E57-102E-4A40-982B-C74E0DB5A9DA/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3934E57-102E-4A40-982B-C74E0DB5A9DA/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3934E57-102E-4A40-982B-C74E0DB5A9DA/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,# successfully create a new pkcs12 file and return hash value

,# teardown

,ok 13 should be equal

,ok 14 null

,ok 15 (unnamed assert)

,ok 16 should be equal

,ok 17 should not throw

# setup

,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 18 (unnamed assert)

,ok 19 (unnamed assert)

,ok 20 should not throw

,ok 21 should be equal

,ok 22 should be equal

,# setup

,# failed to extract public key because of corrupt pkcs12 file

,# teardown

,ok 23 should be equal

,# setup

,# failed to get mobile documents path

,# teardown

,ok 24 should be equal

,# setup

,# #init should register the peerAvailabilityChanged event

,# teardown

,ok 25 should be equal

,ok 26 should be equal

,ok 27 should be equal

,# setup

,# #init should register the networkChanged event

,# teardown

,ok 28 should be equal

,# setup

,# #startBroadcasting should throw on null device name

,# teardown

,ok 29 should throw

,# setup

,# #startBroadcasting should throw on empty string device name

,# teardown

,ok 30 should throw

,# setup

,# #startBroadcasting should throw on non-number port

,# teardown

,ok 31 should throw

,# setup

,# #startBroadcasting should throw on NaN port

,# teardown

,ok 32 should throw

,# setup

,# #startBroadcasting should throw on negative port

,# teardown

,ok 33 should throw

,# setup

,# #startBroadcasting should throw on too large port

,# teardown

,ok 34 should throw

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,# teardown

,ok 35 should be equal

,ok 36 should be equal

,ok 37 should be equal

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,# teardown

,ok 38 should be equal

,ok 39 should be equal

,ok 40 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,# teardown

,ok 41 should be equal

,ok 42 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,# teardown

,ok 43 should be equal

,ok 44 should be equal

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,# teardown

,ok 45 should be equal

,ok 46 should be equal

,ok 47 should be equal

,# setup

,# #connect should call Mobile("Connect") and handle an error

,# teardown

,ok 48 should be equal

,ok 49 should be equal

,# setup

,# should call Mobile("Disconnect") without an error

,# teardown

,ok 50 should be equal

,ok 51 should be equal

,# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 52 should be equal

,ok 53 should be equal

,# setup

,# #start should fail if called twice in a row

,# teardown

,ok 54 specific error should be received

,# setup

,# #startListeningForAdvertisements should fail if start not called

,# teardown

,ok 55 specific error should be returned

,# setup

,# should be able to call #stopListeningForAdvertisements many times

,# teardown

,ok 56 error should be null

,ok 57 error should be null

,# setup

,# should be able to call #startListeningForAdvertisements many times

,# teardown

,ok 58 error should be null

,ok 59 error should be null

,# setup

,# should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,ok 60 error should be null

,ok 61 error should be null

,# setup

,# #startUpdateAdvertisingAndListening should fail if start not called

,# teardown

,ok 62 specific error should be returned

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-02-09 15:24:46.087 ThaliTest[1112:1767859] jxcore: startBroadcasting
,2016-02-09 15:24:46.102 ThaliTest[1112:1767859] server: starting 1455027886086.1112.NguO4w==
,2016-02-09 15:24:46.103 ThaliTest[1112:1767859] multipeer session: start timer: 0x1575a530
2016-02-09 15:24:46.104 ThaliTest[1112:1767859] THEMultipeerSession initialized peer 1455027886086.1112
,2016-02-09 15:24:46.105 ThaliTest[1112:1767859] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error

2016-02-09 15:24:46.109 ThaliTest[1112:1767859] jxcore: stopBroadcasting
2016-02-09 15:24:46.110 ThaliTest[1112:1767859] THEMultipeerSession stopping peer
2016-02-09 15:24:46.110 ThaliTest[1,112:1767859] multipeer session: stop timer
2016-02-09 15:24:46.111 ThaliTest[1112:1767859] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error

2016-02-09 15:24:46.115 ThaliTest[1112:1767859] jxcore: startBroadcasting
,2016-02-09 15:24:46.120 ThaliTest[1112:1767859] server: starting 1455027886114.1112.YFoU5A==
,2016-02-09 15:24:46.124 ThaliTest[1112:1767859] multipeer session: start timer: 0x183691a0
,2016-02-09 15:24:46.130 ThaliTest[1112:1767859] THEMultipeerSession initialized peer 1455027886114.1112
,2016-02-09 15:24:46.131 ThaliTest[1112:1767859] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error

,2016-02-09 15:24:46.134 ThaliTest[1112:1767859] jxcore: stopBroadcasting
,2016-02-09 15:24:46.135 ThaliTest[1112:1767859] THEMultipeerSession stopping peer
,2016-02-09 15:24:46.136 ThaliTest[1112:1767859] multipeer session: stop timer
,2016-02-09 15:24:46.137 ThaliTest[1112:1767859] jxcore: stopBroadcasting: success
,ok 66 Should be able to call stopBroadcasting without error

,2016-02-09 15:24:46.143 ThaliTest[1112:1767859] jxcore: startBroadcasting
,2016-02-09 15:24:46.146 ThaliTest[1112:1767859] server: starting 1455027886142.1112.G2WwXg==
,2016-02-09 15:24:46.149 ThaliTest[1112:1767859] multipeer session: start timer: 0x157564f0
,2016-02-09 15:24:46.153 ThaliTest[1112:1767859] THEMultipeerSession initialized peer 1455027886142.1112
,2016-02-09 15:24:46.155 ThaliTest[1112:1767859] jxcore: startBroadcasting: success
,ok 67 Should be able to call startBroadcasting without error

,2016-02-09 15:24:46.158 ThaliTest[1112:1767859] jxcore: stopBroadcasting
,2016-02-09 15:24:46.159 ThaliTest[1112:1767859] THEMultipeerSession stopping peer
,2016-02-09 15:24:46.160 ThaliTest[1112:1767859] multipeer session: stop timer
,2016-02-09 15:24:46.162 ThaliTest[1112:1767859] jxcore: stopBroadcasting: success
,ok 68 Should be able to call stopBroadcasting without error
,
,2016-02-09 15:24:46.167 ThaliTest[1112:1767859] jxcore: startBroadcasting
,2016-02-09 15:24:46.171 ThaliTest[1112:1767859] server: starting 1455027886166.1112.3euT+Q==
,2016-02-09 15:24:46.173 ThaliTest[1112:1767859] multipeer session: start timer: 0x176202f0
,2016-02-09 15:24:46.177 ThaliTest[1112:1767859] THEMultipeerSession initialized peer 1455027886166.1112
,2016-02-09 15:24:46.179 ThaliTest[1112:1767859] jxcore: startBroadcasting: success
,ok 69 Should be able to call startBroadcasting without error

,2016-02-09 15:24:46.182 ThaliTest[1112:1767859] jxcore: stopBroadcasting
,2016-02-09 15:24:46.182 ThaliTest[1112:1767859] THEMultipeerSession stopping peer
,2016-02-09 15:24:46.183 ThaliTest[1112:1767859] multipeer session: stop timer
,2016-02-09 15:24:46.186 ThaliTest[1112:1767859] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error

,2016-02-09 15:24:46.188 ThaliTest[1112:1767859] jxcore: startBroadcasting
,2016-02-09 15:24:46.191 ThaliTest[1112:1767859] server: starting 1455027886188.1112.0KEYDg==
,2016-02-09 15:24:46.192 ThaliTest[1112:1767859] multipeer session: start timer: 0x15758380
,2016-02-09 15:24:46.195 ThaliTest[1112:1767859] THEMultipeerSession initialized peer 1455027886188.1112
,2016-02-09 15:24:46.196 ThaliTest[1112:1767859] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error

,2016-02-09 15:24:46.198 ThaliTest[1112:1767859] jxcore: stopBroadcasting
,2016-02-09 15:24:46.199 ThaliTest[1112:1767859] THEMultipeerSession stopping peer
,2016-02-09 15:24:46.199 ThaliTest[1112:1767859] multipeer session: stop timer
,2016-02-09 15:24:46.201 ThaliTest[1112:1767859] jxcore: stopBroadcasting: success
,ok 72 Should be able to call stopBroadcasting without error

,2016-02-09 15:24:46.205 ThaliTest[1112:1767859] jxcore: startBroadcasting
,2016-02-09 15:24:46.207 ThaliTest[1112:1767859] server: starting 1455027886204.1112.Y2/aXw==
,2016-02-09 15:24:46.209 ThaliTest[1112:1767859] multipeer session: start timer: 0x1836a2f0
,2016-02-09 15:24:46.213 ThaliTest[1112:1767859] THEMultipeerSession initialized peer 1455027886204.1112
,2016-02-09 15:24:46.213 ThaliTest[1112:1767859] jxcore: startBroadcasting: success
,ok 73 Should be able to call startBroadcasting without error

,2016-02-09 15:24:46.215 ThaliTest[1112:1767859] jxcore: stopBroadcasting
,2016-02-09 15:24:46.216 ThaliTest[1112:1767859] THEMultipeerSession stopping peer
,2016-02-09 15:24:46.217 ThaliTest[1112:1767859] multipeer session: stop timer
,2016-02-09 15:24:46.220 ThaliTest[1112:1767859] jxcore: stopBroadcasting: success
,ok 74 Should be able to call stopBroadcasting without error

,2016-02-09 15:24:46.223 ThaliTest[1112:1767859] jxcore: startBroadcasting
,2016-02-09 15:24:46.225 ThaliTest[1112:1767859] server: starting 1455027886222.1112.HKzvUQ==
,2016-02-09 15:24:46.226 ThaliTest[1112:1767859] multipeer session: start timer: 0x1836acf0
,2016-02-09 15:24:46.228 ThaliTest[1112:1767859] THEMultipeerSession initialized peer 1455027886222.1112
,2016-02-09 15:24:46.230 ThaliTest[1112:1767859] jxcore: startBroadcasting: success
,ok 75 Should be able to call startBroadcasting without error

,2016-02-09 15:24:46.233 ThaliTest[1112:1767859] jxcore: stopBroadcasting
,2016-02-09 15:24:46.233 ThaliTest[1112:1767859] THEMultipeerSession stopping peer
,2016-02-09 15:24:46.234 ThaliTest[1112:1767859] multipeer session: stop timer
,2016-02-09 15:24:46.237 ThaliTest[1112:1767859] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,2016-02-09 15:24:46.239 ThaliTest[1112:1767859] jxcore: startBroadcasting
,2016-02-09 15:24:46.242 ThaliTest[1112:1767859] server: starting 1455027886239.1112.CM5Lsw==
,2016-02-09 15:24:46.243 ThaliTest[1112:1767859] multipeer session: start timer: 0x1836afc0
,2016-02-09 15:24:46.247 ThaliTest[1112:1767859] THEMultipeerSession initialized peer 1455027886239.1112
,2016-02-09 15:24:46.248 ThaliTest[1112:1767859] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

,2016-02-09 15:24:46.249 ThaliTest[1112:1767859] jxcore: stopBroadcasting
,2016-02-09 15:24:46.250 ThaliTest[1112:1767859] THEMultipeerSession stopping peer
,2016-02-09 15:24:46.251 ThaliTest[1112:1767859] multipeer session: stop timer
,2016-02-09 15:24:46.252 ThaliTest[1112:1767859] jxcore: stopBroadcasting: success
,ok 78 Should be able to call stopBroadcasting without error

,2016-02-09 15:24:46.256 ThaliTest[1112:1767859] jxcore: startBroadcasting
,2016-02-09 15:24:46.258 ThaliTest[1112:1767859] server: starting 1455027886255.1112.5z2yzQ==
,2016-02-09 15:24:46.259 ThaliTest[1112:1767859] multipeer session: start timer: 0x1774f190
,2016-02-09 15:24:46.262 ThaliTest[1112:1767859] THEMultipeerSession initialized peer 1455027886255.1112
,2016-02-09 15:24:46.263 ThaliTest[1112:1767859] jxcore: startBroadcasting: success
,ok 79 Should be able to call startBroadcasting without error

,2016-02-09 15:24:46.265 ThaliTest[1112:1767859] jxcore: stopBroadcasting
,2016-02-09 15:24:46.265 ThaliTest[1112:1767859] THEMultipeerSession stopping peer
,2016-02-09 15:24:46.265 ThaliTest[1112:1767859] multipeer session: stop timer
,2016-02-09 15:24:46.266 ThaliTest[1112:1767859] jxcore: stopBroadcasting: success
,ok 80 Should be able to call stopBroadcasting without error

,2016-02-09 15:24:46.269 ThaliTest[1112:1767859] jxcore: startBroadcasting
,2016-02-09 15:24:46.271 ThaliTest[1112:1767859] server: starting 1455027886269.1112.y3UHxA==
,2016-02-09 15:24:46.272 ThaliTest[1112:1767859] multipeer session: start timer: 0x157589f0
,2016-02-09 15:24:46.274 ThaliTest[1112:1767859] THEMultipeerSession initialized peer 1455027886269.1112
,2016-02-09 15:24:46.275 ThaliTest[1112:1767859] jxcore: startBroadcasting: success
,ok 81 Should be able to call startBroadcasting without error

,2016-02-09 15:24:46.277 ThaliTest[1112:1767859] jxcore: stopBroadcasting
,2016-02-09 15:24:46.277 ThaliTest[1112:1767859] THEMultipeerSession stopping peer
,2016-02-09 15:24:46.278 ThaliTest[1112:1767859] multipeer session: stop timer
,2016-02-09 15:24:46.280 ThaliTest[1112:1767859] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-09 15:24:46.888 ThaliTest[1112:1767859] jxcore: startBroadcasting
,2016-02-09 15:24:46.891 ThaliTest[1112:1767859] server: starting 1455027886887.1112.q217wA==
,2016-02-09 15:24:46.892 ThaliTest[1112:1767859] multipeer session: start timer: 0x15700fc0
2016-02-09 15:24:46.892 ThaliTest[1112:1767859] THEMultipeerSession initialized peer 1455027886887.1112
2016-02-09 15:24:46.892 ThaliTest[1112:1767859] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-02-09 15:24:46.895 ThaliTest[1112:1767859] jxcore: startBroadcasting
2016-02-09 15:24:46.895 ThaliTest[1112:1767859] jxcore: startBroadcasting: failure
,ok 84 Cannot call startBroadcasting twice

2016-02-09 15:24:46.899 ThaliTest[1112:1767859] jxcore: stopBroadcasting
2016-02-09 15:24:46.900 ThaliTest[1112:1767859] THEMultipeerSession stopping peer
2016-02-09 15:24:46.900 ThaliTest[1112:1767859] multip,eer session: stop timer
2016-02-09 15:24:46.900 ThaliTest[1112:1767859] jxcore: stopBroadcasting: success
,ok 85 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-09 15:24:47.101 ThaliTest[1112:1767859] jxcore: startBroadcasting
,2016-02-09 15:24:47.105 ThaliTest[1112:1767859] server: starting 1455027887101.1112.TzP5HQ==
,2016-02-09 15:24:47.105 ThaliTest[1112:1767859] multipeer session: start timer: 0x183739e0
2016-02-09 15:24:47.106 ThaliTest[1112:1767859] THEMultipeerSession initialized peer 1455027887101.1112
2016-02-09 15:24:47.106 ThaliTest[1112:1767859] jxcore: startBroadcasting: success
,ok 86 Should be able to call startBroadcasting without error

2016-02-09 15:24:47.109 ThaliTest[1112:1767859] jxcore: connect foobar
2016-02-09 15:24:47.109 ThaliTest[1112:1767859] client: unknown peer foobar
,2016-02-09 15:24:47.111 ThaliTest[1112:1767859] jxcore: connect: fail: Unknown peer
,ok 87 Should not connect to a bad peer

,2016-02-09 15:24:47.116 ThaliTest[1112:1767859] jxcore: stopBroadcasting
2016-02-09 15:24:47.116 ThaliTest[1112:1767859] THEMultipeerSession stopping peer
,2016-02-09 15:24:47.117 ThaliTest[1112:1767859] multipeer session: stop timer
,2016-02-09 15:24:47.118 ThaliTest[1112:1767859] jxcore: stopBroadcasting: success
,ok 88 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-09 15:24:47.510 ThaliTest[1112:1767859] jxcore: startBroadcasting
,2016-02-09 15:24:47.513 ThaliTest[1112:1767859] server: starting 1455027887510.1112.7pBY4Q==
,2016-02-09 15:24:47.514 ThaliTest[1112:1767859] multipeer session: start timer: 0x17726100
,2016-02-09 15:24:47.515 ThaliTest[1112:1767859] THEMultipeerSession initialized peer 1455027887510.1112
,2016-02-09 15:24:47.515 ThaliTest[1112:1767859] jxcore: startBroadcasting: success
,ok 89 Should be able to call startBroadcasting without error

2016-02-09 15:24:47.518 ThaliTest[1112:1767859] jxcore: disconnect
2016-02-09 15:24:47.518 ThaliTest[1112:1767859] jxcore: disconnect: fail
,ok 90 Disconnect should fail to a non-existant peer 

2016-02-09 15:24:47.522 ThaliTest[1112:1767859] jxcore: stopBroadcasting
2016-02-09 15:24:47.522 ThaliTest[1112:1767859] THEMultipeerSession stopping peer
2016-02-09 15:24:47.523 ThaliTest[1112:1767,859] multipeer session: stop timer
2016-02-09 15:24:47.524 ThaliTest[1112:1767859] jxcore: stopBroadcasting: success
ok 91 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-09 15:24:47.980 ThaliTest[1112:1767859] jxcore: startBroadcasting
,2016-02-09 15:24:47.983 ThaliTest[1112:1767859] server: starting 1455027887979.1112.D0vGWQ==
,2016-02-09 15:24:47.984 ThaliTest[1112:1767859] multipeer session: start timer: 0x18376630
,2016-02-09 15:24:47.985 ThaliTest[1112:1767859] THEMultipeerSession initialized peer 1455027887979.1112
2016-02-09 15:24:47.985 ThaliTest[1112:1767859] jxcore: startBroadcasting: success
,ok 92 Should be able to call startBroadcasting without error

,2016-02-09 15:24:49.222 ThaliTest[1112:1767624] client: found peer: 1455027886397.1656.QY39eg==
,2016-02-09 15:24:49.225 ThaliTest[1112:1767859] jxcore: connect 1455027886397.1656.QY39eg==
2016-02-09 15:24:49.225 ThaliTest[1112:1767859] client session: connect
,2016-02-09 15:24:49.225 ThaliTest[1112:1767859] client session: stateChange:0->1 1455027886397.1656.QY39eg==
,2016-02-09 15:24:49.433 ThaliTest[1112:1767624] multipeer session: reset timer
2016-02-09 15:24:49.433 ThaliTest[1112:1767624] multipeer session: stop timer
,2016-02-09 15:24:49.434 ThaliTest[1112:1767624] multipeer session: start timer: 0x18376630
2016-02-09 15:24:49.434 ThaliTest[1112:1767624] server session: connect
,2016-02-09 15:24:49.435 ThaliTest[1112:1767624] server session: stateChange:0->1 1455027886397.1656
,2016-02-09 15:24:49.441 ThaliTest[1112:1767624] server: accepting invitation 1455027886397.1656
,2016-02-09 15:24:51.921 ThaliTest[1112:1768270] server session: connected
2016-02-09 15:24:51.922 ThaliTest[1112:1768270] server session: stateChange:1->2 1455027886397.1656
,2016-02-09 15:24:51.929 ThaliTest[1112:1767624] server relay: socket disconnected
,2016-02-09 15:24:51.929 ThaliTest[1112:1767624] server relay: 0x1837aa50 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 15:24:52.007 ThaliTest[1112:1768270] server session: not connected 1455027886397.1656
,2016-02-09 15:24:52.014 ThaliTest[1112:1768275] client session: connected
,2016-02-09 15:24:52.014 ThaliTest[1112:1768275] client session: stateChange:1->2 1455027886397.1656.QY39eg==
,2016-02-09 15:24:52.018 ThaliTest[1112:1768275] client session: fireConnectCallback: 1455027886397.1656.QY39eg==
2016-02-09 15:24:52.018 ThaliTest[1112:1768275] jxcore: connect: success
,ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-09 15:24:52.023 ThaliTest[1112:1767859] jxcore: disconnect
,2016-02-09 15:24:52.024 ThaliTest[1112:1767859] client session: disconnectFromPeer: 1455027886397.1656.QY39eg==
,2016-02-09 15:24:52.025 ThaliTest[1112:1767859] client session: disconnect
2016-02-09 15:24:52.025 ThaliTest[1112:1767859] client session: stateChange:2->0 1455027886397.1656.QY39eg==
,2016-02-09 15:24:52.035 ThaliTest[1112:1767859] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 15:24:52.837 ThaliTest[1112:1767859] jxcore: stopBroadcasting
,2016-02-09 15:24:52.838 ThaliTest[1112:1767859] THEMultipeerSession stopping peer
,2016-02-09 15:24:52.838 ThaliTest[1112:1767859] multipeer session: stop timer
2016-02-09 15:24:52.839 ThaliTest[1112:1767859] server session: disconnect
,2016-02-09 15:24:52.839 ThaliTest[1112:1767859] server session: stateChange:2->0 1455027886397.1656
,2016-02-09 15:24:52.846 ThaliTest[1112:1767859] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-09 15:24:53.388 ThaliTest[1112:1767859] jxcore: startBroadcasting
,2016-02-09 15:24:53.391 ThaliTest[1112:1767859] server: starting 1455027893387.1112.SYMpiA==
,2016-02-09 15:24:53.392 ThaliTest[1112:1767859] multipeer session: start timer: 0x1838a5a0
2016-02-09 15:24:53.392 ThaliTest[1112:1767859] THEMultipeerSession initialized peer 1455027893387.1112
2016-02-09 15:24:53.393 ThaliTest[1112:1767859] jxcore: startBroadcasting: success
ok 96 Should be able to call startBroadcasting without error

,2016-02-09 15:24:53.965 ThaliTest[1112:1767624] client: found peer: 1455027886397.1656.QY39eg==
,2016-02-09 15:24:53.967 ThaliTest[1112:1767859] jxcore: connect 1455027886397.1656.QY39eg==
,2016-02-09 15:24:53.968 ThaliTest[1112:1767859] client session: connect
,2016-02-09 15:24:53.968 ThaliTest[1112:1767859] client session: stateChange:0->1 1455027886397.1656.QY39eg==
,2016-02-09 15:24:54.432 ThaliTest[1112:1767624] client: lost peer: 1455027886397.1656.QY39eg==
2016-02-09 15:24:54.432 ThaliTest[1112:1767624] client session: onPeerLost: 1455027886397.1656.QY39eg==
,2016-02-09 15:24:54.433 ThaliTest[1112:1767624] client session: onLinkFailure: 1455027886397.1656.QY39eg==
2016-02-09 15:24:54.433 ThaliTest[1112:1767624] client session: disconnect
,2016-02-09 15:24:54.433 ThaliTest[1112:1767624] client session: stateChange:1->0 1455027886397.1656.QY39eg==
,2016-02-09 15:24:54.434 ThaliTest[1112:1767624] client session: fireConnectCallback: 1455027886397.1656.QY39eg==
2016-02-09 15:24:54.434 ThaliTest[1112:1767624] jxcore: connect: fail: Peer disconnected
,2016-02-09 15:24:54.469 ThaliTest[1112:1767624] client: found peer: 1455027891810.1656./UnS+w==
,2016-02-09 15:24:54.470 ThaliTest[1112:1767859] jxcore: connect 1455027891810.1656./UnS+w==
2016-02-09 15:24:54.471 ThaliTest[1112:1767859] client session: connect
,2016-02-09 15:24:54.471 ThaliTest[1112:1767859] client session: stateChange:0->1 1455027891810.1656./UnS+w==
,2016-02-09 15:24:54.534 ThaliTest[1112:1767624] multipeer session: reset timer
2016-02-09 15:24:54.535 ThaliTest[1112:1767624] multipeer session: stop timer
2016-02-09 15:24:54.535 ThaliTest[1112:1767624] multipeer session: start timer: 0x1838a5a0
2016-02-09 15:24:54.535 ThaliTest[1112:1767624] server session: connect
,2016-02-09 15:24:54.536 ThaliTest[1112:1767624] server session: stateChange:0->1 1455027891810.1656
,2016-02-09 15:24:54.542 ThaliTest[1112:1767624] server: accepting invitation 1455027891810.1656
,2016-02-09 15:24:55.437 ThaliTest[1112:1767859] jxcore: connect 1455027886397.1656.QY39eg==
,2016-02-09 15:24:55.438 ThaliTest[1112:1767859] client: connect: unreachable 1455027886397.1656.QY39eg==
,2016-02-09 15:24:55.438 ThaliTest[1112:1767859] jxcore: connect: fail: Peer unreachable
,2016-02-09 15:24:56.959 ThaliTest[1112:1768270] client session: connected
2016-02-09 15:24:56.959 ThaliTest[1112:1768270] client session: stateChange:1->2 1455027891810.1656./UnS+w==
,2016-02-09 15:24:56.963 ThaliTest[1112:1768270] client session: fireConnectCallback: 1455027891810.1656./UnS+w==
2016-02-09 15:24:56.963 ThaliTest[1112:1768270] jxcore: connect: success
,ok 97 Should be able to connect without error

,ok 98 Port should be within range

,2016-02-09 15:24:56.968 ThaliTest[1112:1767859] jxcore: connect 1455027891810.1656./UnS+w==
,2016-02-09 15:24:56.969 ThaliTest[1112:1767859] client: already connect(ing/ed) to 1455027891810.1656./UnS+w==
,2016-02-09 15:24:56.969 ThaliTest[1112:1767859] jxcore: connect: fail: Aleady connecting
,ok 99 Should fail on double connect

,2016-02-09 15:24:56.973 ThaliTest[1112:1767859] jxcore: disconnect
,2016-02-09 15:24:56.973 ThaliTest[1112:1767859] client session: disconnectFromPeer: 1455027891810.1656./UnS+w==
,2016-02-09 15:24:56.974 ThaliTest[1112:1767859] client session: disconnect
2016-02-09 15:24:56.974 ThaliTest[1112:1767859] client session: stateChange:2->0 1455027891810.1656./UnS+w==
,2016-02-09 15:24:57.048 ThaliTest[1112:1767859] jxcore: disconnect: success
,ok 100 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 15:24:57.103 ThaliTest[1112:1768276] server session: connected
,2016-02-09 15:24:57.104 ThaliTest[1112:1768276] server session: stateChange:1->2 1455027891810.1656
,2016-02-09 15:24:57.127 ThaliTest[1112:1767624] server relay: socket disconnected
,2016-02-09 15:24:57.127 ThaliTest[1112:1767624] server relay: 0x18390840 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 15:24:57.198 ThaliTest[1112:1768270] server session: not connected 1455027891810.1656
,calling stopBroadcasting

,2016-02-09 15:24:59.089 ThaliTest[1112:1767859] jxcore: stopBroadcasting
,2016-02-09 15:24:59.090 ThaliTest[1112:1767859] THEMultipeerSession stopping peer
,2016-02-09 15:24:59.090 ThaliTest[1112:1767859] multipeer session: stop timer
2016-02-09 15:24:59.091 ThaliTest[1112:1767859] server session: disconnect
2016-02-09 15:24:59.091 ThaliTest[1112:1767859] server session: stateChange:2->0 1455027891810.1656
2016-02-09 15:24:59.092 ThaliTest[1112:1767859] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-09 15:25:14.797 ThaliTest[1112:1767859] jxcore: startBroadcasting
,2016-02-09 15:25:14.801 ThaliTest[1112:1767859] server: starting 1455027914797.1112.3mgFjw==
,2016-02-09 15:25:14.802 ThaliTest[1112:1767859] multipeer session: start timer: 0x180c1160
,2016-02-09 15:25:14.802 ThaliTest[1112:1767859] THEMultipeerSession initialized peer 1455027914797.1112
,2016-02-09 15:25:14.803 ThaliTest[1112:1767859] jxcore: startBroadcasting: success
ok 101 Should be able to call startBroadcasting without error

,2016-02-09 15:25:16.154 ThaliTest[1112:1767624] client: found peer: 1455027913363.1656.wtaGUA==
,2016-02-09 15:25:16.157 ThaliTest[1112:1767859] jxcore: connect 1455027913363.1656.wtaGUA==
2016-02-09 15:25:16.158 ThaliTest[1112:1767859] client session: connect
,2016-02-09 15:25:16.158 ThaliTest[1112:1767859] client session: stateChange:0->1 1455027913363.1656.wtaGUA==
,2016-02-09 15:25:16.221 ThaliTest[1112:1767624] multipeer session: reset timer
2016-02-09 15:25:16.221 ThaliTest[1112:1767624] multipeer session: stop timer
2016-02-09 15:25:16.222 ThaliTest[1112:1767624] multipeer session: start timer: 0x180c1160
2016-,02-09 15:25:16.222 ThaliTest[1112:1767624] server session: connect
2016-02-09 15:25:16.222 ThaliTest[1112:1767624] server session: stateChange:0->1 1455027913363.1656
,2016-02-09 15:25:16.230 ThaliTest[1112:1767624] server: accepting invitation 1455027913363.1656
,2016-02-09 15:25:19.239 ThaliTest[1112:1768378] server session: connected
2016-02-09 15:25:19.239 ThaliTest[1112:1768378] server session: stateChange:1->2 1455027913363.1656
,2016-02-09 15:25:19.246 ThaliTest[1112:1767624] server relay: socket disconnected
,2016-02-09 15:25:19.246 ThaliTest[1112:1767624] server relay: 0x183b24e0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 15:25:19.302 ThaliTest[1112:1768376] server session: not connected 1455027913363.1656
,2016-02-09 15:25:19.371 ThaliTest[1112:1768376] client session: connected
2016-02-09 15:25:19.372 ThaliTest[1112:1768376] client session: stateChange:1->2 1455027913363.1656.wtaGUA==
,2016-02-09 15:25:19.376 ThaliTest[1112:1768376] client session: fireConnectCallback: 1455027913363.1656.wtaGUA==
2016-02-09 15:25:19.377 ThaliTest[1112:1768376] jxcore: connect: success
,ok 102 Should be able to connect without error

,ok 103 Port should be within range

,2016-02-09 15:25:19.380 ThaliTest[1112:1767859] jxcore: disconnect
,2016-02-09 15:25:19.381 ThaliTest[1112:1767859] client session: disconnectFromPeer: 1455027913363.1656.wtaGUA==
,2016-02-09 15:25:19.382 ThaliTest[1112:1767859] client session: disconnect
,2016-02-09 15:25:19.383 ThaliTest[1112:1767859] client session: stateChange:2->0 1455027913363.1656.wtaGUA==
,2016-02-09 15:25:19.392 ThaliTest[1112:1767859] jxcore: disconnect: success
,ok 104 Should be able to disconnect without error

2016-02-09 15:25:19.398 ThaliTest[1112:1767859] jxcore: disconnect
2016-02-09 15:25:19.398 ThaliTest[1112:1767859] jxcore: disconnect: fail
,ok 105 Disconnect should fail 

,setting stopBroadcasting callback and ending test.
,
,# setup

,calling stopBroadcasting

,2016-02-09 15:25:20.123 ThaliTest[1112:1767859] jxcore: stopBroadcasting
,2016-02-09 15:25:20.123 ThaliTest[1112:1767859] THEMultipeerSession stopping peer
,2016-02-09 15:25:20.124 ThaliTest[1112:1767859] multipeer session: stop timer
,2016-02-09 15:25:20.124 ThaliTest[1112:1767859] server session: disconnect
,2016-02-09 15:25:20.125 ThaliTest[1112:1767859] server session: stateChange:2->0 1455027913363.1656
,2016-02-09 15:25:20.130 ThaliTest[1112:1767859] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 56267

,2016-02-09 15:25:23.092 ThaliTest[1112:1767859] jxcore: startBroadcasting
,2016-02-09 15:25:23.093 ThaliTest[1112:1767859] server: starting 1455027923092.1112.F6XCDg==
,2016-02-09 15:25:23.094 ThaliTest[1112:1767859] multipeer session: start timer: 0x17725e50
2016-02-09 15:25:23.094 ThaliTest[1112:1767859] THEMultipeerSession initialized peer 1455027923092.1112
2016-02-09 15:25:23.094 ThaliTest[1112:1767859] jxcore: startBroadcasting: success
,ok 106 Should be able to call startBroadcasting without error

,2016-02-09 15:25:23.360 ThaliTest[1112:1767624] client: found peer: 1455027913363.1656.wtaGUA==
,2016-02-09 15:25:23.361 ThaliTest[1112:1767859] jxcore: connect 1455027913363.1656.wtaGUA==
2016-02-09 15:25:23.361 ThaliTest[1112:1767859] client session: connect
2016-02-09 15:25:23.361 ThaliTest[1112:1767859] client session: stateChange:0->1 1455027913363.1656.wtaGUA==
,2016-02-09 15:25:24.498 ThaliTest[1112:1767624] client: found peer: 1455027921553.1656.tNBT+A==
,2016-02-09 15:25:24.500 ThaliTest[1112:1767859] jxcore: connect 1455027921553.1656.tNBT+A==
2016-02-09 15:25:24.500 ThaliTest[1112:1767859] client session: connect
2016-02-09 15:25:24.500 ThaliTest[1112:1767859] client session: stateChange:0->1 1455027921553.1656.tNBT+A==
,2016-02-09 15:25:24.907 ThaliTest[1112:1767624] multipeer session: reset timer
2016-02-09 15:25:24.908 ThaliTest[1112:1767624] multipeer session: stop timer
2016-02-09 15:25:24.908 ThaliTest[1112:1767624] multipeer session: start timer: 0x17725e50
,2016-02-09 15:25:24.908 ThaliTest[1112:1767624] server session: connect
2016-02-09 15:25:24.909 ThaliTest[1112:1767624] server session: stateChange:0->1 1455027921553.1656
,2016-02-09 15:25:24.915 ThaliTest[1112:1767624] server: accepting invitation 1455027921553.1656
,2016-02-09 15:25:27.342 ThaliTest[1112:1768413] server session: connected
,2016-02-09 15:25:27.342 ThaliTest[1112:1768413] server session: stateChange:1->2 1455027921553.1656
,2016-02-09 15:25:27.348 ThaliTest[1112:1767624] server relay: connected (to port: 56267)
,2016-02-09 15:25:27.422 ThaliTest[1112:1768413] client session: connected
2016-02-09 15:25:27.422 ThaliTest[1112:1768413] client session: stateChange:1->2 1455027921553.1656.tNBT+A==
,2016-02-09 15:25:27.430 ThaliTest[1112:1768413] client session: fireConnectCallback: 1455027921553.1656.tNBT+A==
,2016-02-09 15:25:27.430 ThaliTest[1112:1768413] jxcore: connect: success
,ok 107 Should be able to connect without error

,ok 108 Port should be within range

,2016-02-09 15:25:27.439 ThaliTest[1112:1767624] client: relay established
,2016-02-09 15:25:27.439 ThaliTest[1112:1767624] client: new accepted socket: 0x172de630
,data in 5475

,data in 6570

,data in 21900

,data in 25185

,data in 35425

,data in 94170

,data in 117165

,data in 131072

,ok 109 the test messages should be equal

,2016-02-09 15:25:27.781 ThaliTest[1112:1767859] jxcore: disconnect
,2016-02-09 15:25:27.781 ThaliTest[1112:1767859] client session: disconnectFromPeer: 1455027921553.1656.tNBT+A==
,2016-02-09 15:25:27.782 ThaliTest[1112:1767859] client session: disconnect
,2016-02-09 15:25:27.782 ThaliTest[1112:1767859] client session: stateChange:2->0 1455027921553.1656.tNBT+A==
,2016-02-09 15:25:27.789 ThaliTest[1112:1767859] jxcore: disconnect: success
,ok 110 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 15:25:27.816 ThaliTest[1112:1768377] server session: not connected 1455027921553.1656
,calling stopBroadcasting

,2016-02-09 15:25:27.900 ThaliTest[1112:1767859] jxcore: stopBroadcasting
,2016-02-09 15:25:27.901 ThaliTest[1112:1767859] THEMultipeerSession stopping peer
,2016-02-09 15:25:27.901 ThaliTest[1112:1767859] multipeer session: stop timer
,2016-02-09 15:25:27.903 ThaliTest[1112:1767859] client session: disconnect
2016-02-09 15:25:27.904 ThaliTest[1112:1767859] client session: stateChange:1->0 1455027913363.1656.wtaGUA==
,2016-02-09 15:25:27.907 ThaliTest[1112:1767859] server session: disconnect
,2016-02-09 15:25:27.908 ThaliTest[1112:1767859] server session: stateChange:2->0 1455027921553.1656
,2016-02-09 15:25:27.920 ThaliTest[1112:1767859] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 56274

,2016-02-09 15:25:28.427 ThaliTest[1112:1767859] jxcore: startBroadcasting
,2016-02-09 15:25:28.431 ThaliTest[1112:1767859] server: starting 1455027928427.1112.k6j4Ag==
,2016-02-09 15:25:28.432 ThaliTest[1112:1767859] multipeer session: start timer: 0x15591e20
,2016-02-09 15:25:28.432 ThaliTest[1112:1767859] THEMultipeerSession initialized peer 1455027928427.1112
,2016-02-09 15:25:28.433 ThaliTest[1112:1767859] jxcore: startBroadcasting: success
ok 111 Should be able to call startBroadcasting without error

,2016-02-09 15:25:29.123 ThaliTest[1112:1767624] client: found peer: 1455027913363.1656.wtaGUA==
,[{"peerIdentifier":"1455027913363.1656.wtaGUA==","peerName":"(null)","peerAvailable":true}]

,2016-02-09 15:25:29.126 ThaliTest[1112:1767859] jxcore: connect 1455027913363.1656.wtaGUA==
,2016-02-09 15:25:29.126 ThaliTest[1112:1767859] client session: connect
,2016-02-09 15:25:29.127 ThaliTest[1112:1767859] client session: stateChange:0->1 1455027913363.1656.wtaGUA==
,2016-02-09 15:25:29.198 ThaliTest[1112:1767624] client: found peer: 1455027926836.1656.x1ojrQ==
[{"peerIdentifier":"1455027926836.1656.x1ojrQ==","peerName":"(null)","peerAvailable":true}]

2016-02-09 15:25:29.199 ThaliTest[1112:1767859] jxcore: connect 1455027926836.1656.x1ojrQ==
2016-02-09 15:25:29.200 ThaliTest[1112:1767859] client session: connect
,2016-02-09 15:25:29.200 ThaliTest[1112:1767859] client session: stateChange:0->1 1455027926836.1656.x1ojrQ==
,2016-02-09 15:25:29.791 ThaliTest[1112:1767624] multipeer session: reset timer
2016-02-09 15:25:29.793 ThaliTest[1112:1767624] multipeer session: stop timer
2016-02-09 15:25:29.793 ThaliTest[1112:1767624] multipeer session: start timer: 0x15591e20
2016-02-09 15:25:29.793 ThaliTest[1112:1767624] server session: connect
2016-02-09 15:25:29.793 ThaliTest[1112:1767624] server session: stateChange:0->1 1455027926836.1656
,2016-02-09 15:25:29.798 ThaliTest[1112:1767624] server: accepting invitation 1455027926836.1656
,2016-02-09 15:25:31.942 ThaliTest[1112:1768376] client session: connected
,2016-02-09 15:25:31.942 ThaliTest[1112:1768376] client session: stateChange:1->2 1455027926836.1656.x1ojrQ==
,2016-02-09 15:25:31.948 ThaliTest[1112:1768377] client session: fireConnectCallback: 1455027926836.1656.x1ojrQ==
2016-02-09 15:25:31.949 ThaliTest[1112:1768377] jxcore: connect: success
,ok 112 Should be able to connect without error

,ok 113 Port should be within range

,ok 114 First connect should succeed

,2016-02-09 15:25:32.011 ThaliTest[1112:1767624] client: relay established
2016-02-09 15:25:32.011 ThaliTest[1112:1767624] client: new accepted socket: 0x156a5ef0
,ok 115 the test messages should be equal

,ok 116 First send should succeed
,
,2016-02-09 15:25:32.096 ThaliTest[1112:1767624] client: socket closed
,2016-02-09 15:25:32.096 ThaliTest[1112:1767624] client relay: socket disconnected
,2016-02-09 15:25:32.097 ThaliTest[1112:1767624] client relay: 0x156a5ef0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-09 15:25:32.097 ThaliTest[1112:1767624] client session: socket closed: 1455027926836.1656.x1ojrQ==
,2016-02-09 15:25:32.098 ThaliTest[1112:1767624] client session: onLinkFailure: 1455027926836.1656.x1ojrQ==
2016-02-09 15:25:32.098 ThaliTest[1112:1767624] client session: disconnect
2016-02-09 15:25:32.098 ThaliTest[1112:1767624] client session: stateChange:2->0 1455027926836.1656.x1ojrQ==
,2016-02-09 15:25:32.107 ThaliTest[1112:1767624] client session: fireConnectionErrorEvent: 1455027926836.1656.x1ojrQ==
,2016-02-09 15:25:32.118 ThaliTest[1112:1767859] jxcore: connect 1455027926836.1656.x1ojrQ==
,2016-02-09 15:25:32.119 ThaliTest[1112:1767859] client session: connect
,2016-02-09 15:25:32.119 ThaliTest[1112:1767859] client session: stateChange:0->1 1455027926836.1656.x1ojrQ==
,2016-02-09 15:25:32.369 ThaliTest[1112:1768407] server session: connected
2016-02-09 15:25:32.369 ThaliTest[1112:1768407] server session: stateChange:1->2 1455027926836.1656
,2016-02-09 15:25:32.404 ThaliTest[1112:1767624] server relay: connected (to port: 56274)
,2016-02-09 15:25:32.540 ThaliTest[1112:1768377] server session: not connected 1455027926836.1656
,2016-02-09 15:25:32.601 ThaliTest[1112:1767624] multipeer session: reset timer
2016-02-09 15:25:32.602 ThaliTest[1112:1767624] multipeer session: stop timer
2016-02-09 15:25:32.602 ThaliTest[1112:1767624] multipeer session: start timer: 0x15591e20
2016-,02-09 15:25:32.602 ThaliTest[1112:1767624] server: disconnecting to refresh session (1455027926836.1656)
2016-02-09 15:25:32.602 ThaliTest[1112:1767624] server session: disconnect
2016-02-09 15:25:32.602 ThaliTest[1112:1767624] server session: stateChang,e:2->0 1455027926836.1656
2016-02-09 15:25:32.605 ThaliTest[1112:1767624] server session: connect
,2016-02-09 15:25:32.605 ThaliTest[1112:1767624] server session: stateChange:0->1 1455027926836.1656
,2016-02-09 15:25:32.614 ThaliTest[1112:1767624] server: accepting invitation 1455027926836.1656
,2016-02-09 15:25:42.402 ThaliTest[1112:1768407] server session: connected
2016-02-09 15:25:42.403 ThaliTest[1112:1768407] server session: stateChange:1->2 1455027926836.1656
,2016-02-09 15:25:42.544 ThaliTest[1112:1767624] server relay: connected (to port: 56274)
,2016-02-09 15:25:42.612 ThaliTest[1112:1768407] client session: connected
2016-02-09 15:25:42.613 ThaliTest[1112:1768407] client session: stateChange:1->2 1455027926836.1656.x1ojrQ==
,2016-02-09 15:25:42.891 ThaliTest[1112:1768414] client session: fireConnectCallback: 1455027926836.1656.x1ojrQ==
2016-02-09 15:25:42.892 ThaliTest[1112:1768414] jxcore: connect: success
,ok 117 Should be able to connect without error

,ok 118 Port should be within range

,ok 119 Second connect should succeed

,2016-02-09 15:25:42.925 ThaliTest[1112:1767624] client: relay established
2016-02-09 15:25:42.926 ThaliTest[1112:1767624] client: new accepted socket: 0x181b1760
,2016-02-09 15:25:45.359 ThaliTest[1112:1768414] server session: not connected 1455027926836.1656
,ok 120 the test messages should be equal

,ok 121 Second send should succeed

,# setup

,2016-02-09 15:25:46.729 ThaliTest[1112:1767624] client: socket closed
,2016-02-09 15:25:46.730 ThaliTest[1112:1767624] client relay: socket disconnected
,2016-02-09 15:25:46.730 ThaliTest[1112:1767624] client relay: 0x181b1760 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-09 15:25:46.731 ThaliTest[1112:1767624] client session: socket closed: 1455027926836.1656.x1ojrQ==
2016-02-09 15:25:46.731 ThaliTest[1112:1767624] client session: onLinkFailure: 1455027926836.1656.x1ojrQ==
,2016-02-09 15:25:46.731 ThaliTest[1112:1767624] client session: disconnect
2016-02-09 15:25:46.731 ThaliTest[1112:1767624] client session: stateChange:2->0 1455027926836.1656.x1ojrQ==
,2016-02-09 15:25:46.736 ThaliTest[1112:1767624] client session: fireConnectionErrorEvent: 1455027926836.1656.x1ojrQ==
,calling stopBroadcasting

,2016-02-09 15:25:46.859 ThaliTest[1112:1767859] jxcore: stopBroadcasting
,2016-02-09 15:25:46.859 ThaliTest[1112:1767859] THEMultipeerSession stopping peer
,2016-02-09 15:25:46.860 ThaliTest[1112:1767859] multipeer session: stop timer
,2016-02-09 15:25:46.861 ThaliTest[1112:1767859] client session: disconnect
2016-02-09 15:25:46.861 ThaliTest[1112:1767859] client session: stateChange:1->0 1455027913363.1656.wtaGUA==
,2016-02-09 15:25:46.864 ThaliTest[1112:1767859] server session: disconnect
2016-02-09 15:25:46.864 ThaliTest[1112:1767859] server session: stateChange:2->0 1455027926836.1656
,2016-02-09 15:25:46.869 ThaliTest[1112:1767859] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/280233D6-45AF-4B10-84C5-DA52122FA7D5/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 122 starting event should occur in right order

,2016-02-09 15:25:48.039 ThaliTest[1112:1767859] jxcore: startBroadcasting
,2016-02-09 15:25:48.042 ThaliTest[1112:1767859] server: starting nNJbi8ca0mhCyrEBAuD8rA.F9WQHw==
,2016-02-09 15:25:48.042 ThaliTest[1112:1767859] multipeer session: start timer: 0x156363c0
2016-02-09 15:25:48.042 ThaliTest[1112:1767859] THEMultipeerSession initialized peer nNJbi8ca0mhCyrEBAuD8rA
2016-02-09 15:25:48.042 ThaliTest[1112:1767859] jxcore: startBroadcasting: success
,ok 123 started event should occur in right order

,Now in TRM stop

,State of this._isStarted: true

,ok 124 stopping event should occur in right order

About to call stopBroadcasting

2016-02-09 15:25:48.044 ThaliTest[1112:1767859] jxcore: stopBroadcasting
,2016-02-09 15:25:48.044 ThaliTest[1112:1767859] THEMultipeerSession stopping peer
2016-02-09 15:25:48.045 ThaliTest[1112:1767859] multipeer session: stop timer
,2016-02-09 15:25:48.045 ThaliTest[1112:1767859] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

ok 125 stopped event should occur in right order
,
,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/280233D6-45AF-4B10-84C5-DA52122FA7D5/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 15:25:48.542 ThaliTest[1112:1767859] jxcore: startBroadcasting
,2016-02-09 15:25:48.546 ThaliTest[1112:1767859] server: starting nNJbi8ca0mhCyrEBAuD8rA.fJXzGA==
,2016-02-09 15:25:48.547 ThaliTest[1112:1767859] multipeer session: start timer: 0x1749dfa0
,2016-02-09 15:25:48.549 ThaliTest[1112:1767859] THEMultipeerSession initialized peer nNJbi8ca0mhCyrEBAuD8rA
2016-02-09 15:25:48.550 ThaliTest[1112:1767859] jxcore: startBroadcasting: success
,ok 126 getDeviceIdentity should not return an error

ok 127 deviceName should not be null

Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

,2016-02-09 15:25:48.555 ThaliTest[1112:1767859] jxcore: stopBroadcasting
2016-02-09 15:25:48.555 ThaliTest[1112:1767859] THEMultipeerSession stopping peer
2016-02-09 15:25:48.555 ThaliTest[1112:1767859] multipeer session: stop timer
2016-02-09 15:25:48.,556 ThaliTest[1112:1767859] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/280233D6-45AF-4B10-84C5-DA52122FA7D5/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 15:25:51.578 ThaliTest[1112:1767859] jxcore: startBroadcasting
,2016-02-09 15:25:51.579 ThaliTest[1112:1767859] server: starting nNJbi8ca0mhCyrEBAuD8rA.eoriNA==
,2016-02-09 15:25:51.580 ThaliTest[1112:1767859] multipeer session: start timer: 0x17484320
2016-02-09 15:25:51.580 ThaliTest[1112:1767859] THEMultipeerSession initialized peer nNJbi8ca0mhCyrEBAuD8rA
2016-02-09 15:25:51.580 ThaliTest[1112:1767859] jxcore: startBroadcasting: success
,ok 128 getDeviceIdentity should not return an error

ok 129 deviceName should not be null

,2016-02-09 15:25:51.584 ThaliTest[1112:1767624] client: found peer: 1455027926836.1656.x1ojrQ==
,2016-02-09 15:25:55.581 ThaliTest[1112:1767624] client: lost peer: 1455027926836.1656.x1ojrQ==
2016-02-09 15:25:55.581 ThaliTest[1112:1767624] client session: onPeerLost: 1455027926836.1656.x1ojrQ==
,2016-02-09 15:25:55.603 ThaliTest[1112:1767624] client: found peer: CqTws3O_Kmbx6iHoCFOQOw.9t0p+g==
,2016-02-09 15:25:55.603 ThaliTest[1112:1767859] jxcore: connect 1455027926836.1656.x1ojrQ==
,2016-02-09 15:25:55.604 ThaliTest[1112:1767859] client: connect: unreachable 1455027926836.1656.x1ojrQ==
2016-02-09 15:25:55.604 ThaliTest[1112:1767859] jxcore: connect: fail: Peer unreachable
,Connect error with error: Error: Peer unreachable

2016-02-09 15:25:55.605 ThaliTest[1112:1767859] jxcore: connect CqTws3O_Kmbx6iHoCFOQOw.9t0p+g==
,2016-02-09 15:25:55.605 ThaliTest[1112:1767859] client session: connect
,2016-02-09 15:25:55.605 ThaliTest[1112:1767859] client session: stateChange:0->1 CqTws3O_Kmbx6iHoCFOQOw.9t0p+g==
,2016-02-09 15:25:55.656 ThaliTest[1112:1767859] jxcore: disconnect
2016-02-09 15:25:55.656 ThaliTest[1112:1767859] jxcore: disconnect: fail
Disconnect error with error: Error: Not connected to specified peer

peerIdentifier not available 1455027926836.1656.x1ojrQ==

,ok 130 Should be able to put doc without error

,ok 131 1st change of local doc should contain local id

,2016-02-09 15:25:56.526 ThaliTest[1112:1767624] multipeer session: reset timer
2016-02-09 15:25:56.526 ThaliTest[1112:1767624] multipeer session: stop timer
2016-02-09 15:25:56.526 ThaliTest[1112:1767624] multipeer session: start timer: 0x17484320
2016-02-09 15:25:56.527 ThaliTest[1112:1767624] server session: connect
,2016-02-09 15:25:56.527 ThaliTest[1112:1767624] server session: stateChange:0->1 CqTws3O_Kmbx6iHoCFOQOw
,2016-02-09 15:25:56.534 ThaliTest[1112:1767624] server: accepting invitation CqTws3O_Kmbx6iHoCFOQOw
,2016-02-09 15:25:58.857 ThaliTest[1112:1768537] server session: connected
,2016-02-09 15:25:58.857 ThaliTest[1112:1768537] server session: stateChange:1->2 CqTws3O_Kmbx6iHoCFOQOw
,2016-02-09 15:25:58.862 ThaliTest[1112:1767624] server relay: connected (to port: 56289)
,server bridge: new client socket

,2016-02-09 15:25:59.453 ThaliTest[1112:1768565] client session: connected
,2016-02-09 15:25:59.454 ThaliTest[1112:1768565] client session: stateChange:1->2 CqTws3O_Kmbx6iHoCFOQOw.9t0p+g==
,2016-02-09 15:25:59.456 ThaliTest[1112:1768565] client session: fireConnectCallback: CqTws3O_Kmbx6iHoCFOQOw.9t0p+g==
2016-02-09 15:25:59.457 ThaliTest[1112:1768565] jxcore: connect: success
,2016-02-09 15:25:59.462 ThaliTest[1112:1767624] client: relay established
2016-02-09 15:25:59.462 ThaliTest[1112:1767624] client: new accepted socket: 0x175df190
,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,ok 132 1st change of remote doc should contain remote id

,ok 133 Can update remote doc without error

,null

,{ ok: true,
  id: 'ffb50cbe-8b3c-47a2-8644-8514cd4e1875',
  rev: '2-b610418394fcd952e8e70e60bc3adfd6' }

,client bridge: new client socket

,ok 134 Remote changes occur in strict order
,
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

,client bridge: socket closed

,client bridge: socket closed

,ok 135 Local changes occur in strict order

,ok 136 2nd change of local doc should contain remote id

,# setup

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,Now in TRM stop

,State of this._isStarted: true

About to call stopBroadcasting

,2016-02-09 15:26:09.886 ThaliTest[1112:1767859] jxcore: stopBroadcasting
,2016-02-09 15:26:09.886 ThaliTest[1112:1767859] THEMultipeerSession stopping peer
,2016-02-09 15:26:09.887 ThaliTest[1112:1767859] multipeer session: stop timer
,2016-02-09 15:26:09.888 ThaliTest[1112:1767859] client session: disconnect
,2016-02-09 15:26:09.888 ThaliTest[1112:1767859] client session: stateChange:2->0 CqTws3O_Kmbx6iHoCFOQOw.9t0p+g==
,2016-02-09 15:26:09.950 ThaliTest[1112:1768414] server session: not connected CqTws3O_Kmbx6iHoCFOQOw
,2016-02-09 15:26:09.960 ThaliTest[1112:1767859] server session: disconnect
2016-02-09 15:26:09.961 ThaliTest[1112:1767859] server session: stateChange:2->0 CqTws3O_Kmbx6iHoCFOQOw
,2016-02-09 15:26:09.966 ThaliTest[1112:1767859] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,Error in mux client bridge Error: write EPIPE

,# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,client bridge: socket closed

,incoming client socket error Error: read ECONNRESET

,mux server bridge listener closed

,server bridge: socket closed

,syncRetry called when not started

,# teardown

,client bridge: socket closed

,client bridge: socket closed

,appEnteredForeground wasn't registered

,appEnteringBackground wasn't registered


```
