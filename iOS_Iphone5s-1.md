#### Test 57132760f6ec045_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/57132760f6ec045/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/961FCDC5-E5C4-4465-9021-0CCE4DE847D7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/961FCDC5-E5C4-4465-9021-0CCE4DE847D7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/57132760f6ec045/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/57132760f6ec045/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B3E0E5B5-E336-449C-8754-06DD8DCC7C53/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60788"
,(lldb)     command script import "/tmp/961FCDC5-E5C4-4465-9021-0CCE4DE847D7/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-25 22:42:03.916 ThaliTest[2573:7255619] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CCBE44E8-1656-41FE-8AA1-925F7AD6F22B/Library/Cookies/Cookies.binarycookies
,2016-01-25 22:42:04.219 ThaliTest[2573:7255619] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-25 22:42:04.221 ThaliTest[2573:7255619] Multi-tasking -> Device: YES, App: YES
,2016-01-25 22:42:04.228 ThaliTest[2573:7255619] Unlimited access to network resources
,2016-01-25 22:42:04.238 ThaliTest[2573:7255619] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-25 22:42:08.863 ThaliTest[2573:7255619] Resetting plugins due to page load.
,2016-01-25 22:42:10.548 ThaliTest[2573:7255619] Finished load of: file:///var/mobile/Containers/Bundle/Application/B3E0E5B5-E336-449C-8754-06DD8DCC7C53/ThaliTest.app/www/index.html
,2016-01-25 22:42:10.761 ThaliTest[2573:7255619] JXcore Cordova plugin initializing
2016-01-25 22:42:10.762 ThaliTest[2573:7255781] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E0E5B5-E336-449C-8754-06DD8DCC7C53/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E0E5B5-E336-449C-8754-06DD8DCC7C53/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E0E5B5-E336-449C-8754-06DD8DCC7C53/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E0E5B5-E336-449C-8754-06DD8DCC7C53/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E0E5B5-E336-449C-8754-06DD8DCC7C53/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E0E5B5-E336-449C-8754-06DD8DCC7C53/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E0E5B5-E336-449C-8754-06DD8DCC7C53/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,# teardown

,ok 1 String should be length:200

,# setup

,# basic

,# teardown

,ok 2 sane

# setup

,# another

,# teardown

,ok 3 sane

,# setup

,# successfully create a new pkcs12 file and return hash value

,# teardown

,ok 4 should be equal

,ok 5 null

,ok 6 (unnamed assert)

,ok 7 should be equal

,ok 8 should not throw
,
,# setup
,
,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 9 (unnamed assert)

,ok 10 (unnamed assert)

ok 11 should not throw

,ok 12 should be equal

,ok 13 should be equal

,# setup

,# failed to extract public key because of corrupt pkcs12 file

,# teardown

,ok 14 should be equal

,# setup

,# failed to get mobile documents path

,# teardown

,ok 15 should be equal

,# setup

,# #init should register the peerAvailabilityChanged event

,# teardown

,ok 16 should be equal

,ok 17 should be equal

,ok 18 should be equal

,# setup

,# #init should register the networkChanged event

,# teardown

,ok 19 should be equal

,# setup

,# #startBroadcasting should throw on null device name

,# teardown

,ok 20 should throw

,# setup

,# #startBroadcasting should throw on empty string device name

,# teardown

,ok 21 should throw

,# setup

,# #startBroadcasting should throw on non-number port

,# teardown

,ok 22 should throw

,# setup

,# #startBroadcasting should throw on NaN port

,# teardown

,ok 23 should throw

,# setup

,# #startBroadcasting should throw on negative port

,# teardown

,ok 24 should throw

,# setup

,# #startBroadcasting should throw on too large port

,# teardown

,ok 25 should throw

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,# teardown

,ok 26 should be equal

ok 27 should be equal

,ok 28 should be equal

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,# teardown

,ok 29 should be equal

ok 30 should be equal

,ok 31 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,# teardown

,ok 32 should be equal

ok 33 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,# teardown

,ok 34 should be equal

ok 35 should be equal

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,# teardown

,ok 36 should be equal

,ok 37 should be equal

,ok 38 should be equal

,# setup

,# #connect should call Mobile("Connect") and handle an error

,# teardown

,ok 39 should be equal

ok 40 should be equal

,# setup

,# should call Mobile("Disconnect") without an error

,# teardown

,ok 41 should be equal

ok 42 should be equal

,# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 43 should be equal

ok 44 should be equal

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-01-25 22:48:02.019 ThaliTest[2573:7255781] jxcore: startBroadcasting
,2016-01-25 22:48:02.028 ThaliTest[2573:7255781] server: starting 1453758482019.2573.cEHfrQ==
,2016-01-25 22:48:02.030 ThaliTest[2573:7255781] multipeer session: start timer: 0x16ab4c70
2016-01-25 22:48:02.035 ThaliTest[2573:7255781] THEMultipeerSession initialized peer 1453758482019.2573
,2016-01-25 22:48:02.035 ThaliTest[2573:7255781] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error

,2016-01-25 22:48:02.038 ThaliTest[2573:7255781] jxcore: stopBroadcasting
,2016-01-25 22:48:02.038 ThaliTest[2573:7255781] THEMultipeerSession stopping peer
,2016-01-25 22:48:02.039 ThaliTest[2573:7255781] multipeer session: stop timer
,2016-01-25 22:48:02.041 ThaliTest[2573:7255781] jxcore: stopBroadcasting: success
,ok 46 Should be able to call stopBroadcasting without error

,2016-01-25 22:48:02.044 ThaliTest[2573:7255781] jxcore: startBroadcasting
,2016-01-25 22:48:02.046 ThaliTest[2573:7255781] server: starting 1453758482043.2573.sTNVGg==
,2016-01-25 22:48:02.048 ThaliTest[2573:7255781] multipeer session: start timer: 0x159660d0
,2016-01-25 22:48:02.051 ThaliTest[2573:7255781] THEMultipeerSession initialized peer 1453758482043.2573
,2016-01-25 22:48:02.052 ThaliTest[2573:7255781] jxcore: startBroadcasting: success
,ok 47 Should be able to call startBroadcasting without error

,2016-01-25 22:48:02.053 ThaliTest[2573:7255781] jxcore: stopBroadcasting
,2016-01-25 22:48:02.054 ThaliTest[2573:7255781] THEMultipeerSession stopping peer
,2016-01-25 22:48:02.055 ThaliTest[2573:7255781] multipeer session: stop timer
,2016-01-25 22:48:02.057 ThaliTest[2573:7255781] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error

,2016-01-25 22:48:02.059 ThaliTest[2573:7255781] jxcore: startBroadcasting
,2016-01-25 22:48:02.062 ThaliTest[2573:7255781] server: starting 1453758482059.2573.4Zzevw==
,2016-01-25 22:48:02.063 ThaliTest[2573:7255781] multipeer session: start timer: 0x16d89150
,2016-01-25 22:48:02.066 ThaliTest[2573:7255781] THEMultipeerSession initialized peer 1453758482059.2573
,2016-01-25 22:48:02.068 ThaliTest[2573:7255781] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,
,2016-01-25 22:48:02.072 ThaliTest[2573:7255781] jxcore: stopBroadcasting
,2016-01-25 22:48:02.073 ThaliTest[2573:7255781] THEMultipeerSession stopping peer
,2016-01-25 22:48:02.074 ThaliTest[2573:7255781] multipeer session: stop timer
,2016-01-25 22:48:02.075 ThaliTest[2573:7255781] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error

,2016-01-25 22:48:02.080 ThaliTest[2573:7255781] jxcore: startBroadcasting
,2016-01-25 22:48:02.082 ThaliTest[2573:7255781] server: starting 1453758482079.2573.enXavg==
,2016-01-25 22:48:02.083 ThaliTest[2573:7255781] multipeer session: start timer: 0x16d89150
,2016-01-25 22:48:02.088 ThaliTest[2573:7255781] THEMultipeerSession initialized peer 1453758482079.2573
,2016-01-25 22:48:02.092 ThaliTest[2573:7255781] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error

,2016-01-25 22:48:02.096 ThaliTest[2573:7255781] jxcore: stopBroadcasting
,2016-01-25 22:48:02.096 ThaliTest[2573:7255781] THEMultipeerSession stopping peer
,2016-01-25 22:48:02.097 ThaliTest[2573:7255781] multipeer session: stop timer
,2016-01-25 22:48:02.098 ThaliTest[2573:7255781] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error

,2016-01-25 22:48:02.102 ThaliTest[2573:7255781] jxcore: startBroadcasting
,2016-01-25 22:48:02.105 ThaliTest[2573:7255781] server: starting 1453758482102.2573.Z4B39Q==
,2016-01-25 22:48:02.108 ThaliTest[2573:7255781] multipeer session: start timer: 0x15c88460
,2016-01-25 22:48:02.110 ThaliTest[2573:7255781] THEMultipeerSession initialized peer 1453758482102.2573
,2016-01-25 22:48:02.112 ThaliTest[2573:7255781] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error

,2016-01-25 22:48:02.114 ThaliTest[2573:7255781] jxcore: stopBroadcasting
,2016-01-25 22:48:02.114 ThaliTest[2573:7255781] THEMultipeerSession stopping peer
,2016-01-25 22:48:02.115 ThaliTest[2573:7255781] multipeer session: stop timer
,2016-01-25 22:48:02.117 ThaliTest[2573:7255781] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error

,2016-01-25 22:48:02.120 ThaliTest[2573:7255781] jxcore: startBroadcasting
,2016-01-25 22:48:02.122 ThaliTest[2573:7255781] server: starting 1453758482119.2573.VdkUiQ==
,2016-01-25 22:48:02.124 ThaliTest[2573:7255781] multipeer session: start timer: 0x16d80710
,2016-01-25 22:48:02.127 ThaliTest[2573:7255781] THEMultipeerSession initialized peer 1453758482119.2573
,2016-01-25 22:48:02.129 ThaliTest[2573:7255781] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error

,2016-01-25 22:48:02.131 ThaliTest[2573:7255781] jxcore: stopBroadcasting
,2016-01-25 22:48:02.132 ThaliTest[2573:7255781] THEMultipeerSession stopping peer
,2016-01-25 22:48:02.133 ThaliTest[2573:7255781] multipeer session: stop timer
,2016-01-25 22:48:02.134 ThaliTest[2573:7255781] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error

,2016-01-25 22:48:02.137 ThaliTest[2573:7255781] jxcore: startBroadcasting
,2016-01-25 22:48:02.141 ThaliTest[2573:7255781] server: starting 1453758482137.2573.vxbTQg==
,2016-01-25 22:48:02.143 ThaliTest[2573:7255781] multipeer session: start timer: 0x16adbf60
,2016-01-25 22:48:02.147 ThaliTest[2573:7255781] THEMultipeerSession initialized peer 1453758482137.2573
,2016-01-25 22:48:02.148 ThaliTest[2573:7255781] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error

,2016-01-25 22:48:02.150 ThaliTest[2573:7255781] jxcore: stopBroadcasting
,2016-01-25 22:48:02.150 ThaliTest[2573:7255781] THEMultipeerSession stopping peer
,2016-01-25 22:48:02.151 ThaliTest[2573:7255781] multipeer session: stop timer
,2016-01-25 22:48:02.153 ThaliTest[2573:7255781] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error

,2016-01-25 22:48:02.156 ThaliTest[2573:7255781] jxcore: startBroadcasting
,2016-01-25 22:48:02.158 ThaliTest[2573:7255781] server: starting 1453758482155.2573.0Ym3dg==
,2016-01-25 22:48:02.159 ThaliTest[2573:7255781] multipeer session: start timer: 0x16adc750
,2016-01-25 22:48:02.162 ThaliTest[2573:7255781] THEMultipeerSession initialized peer 1453758482155.2573
,2016-01-25 22:48:02.163 ThaliTest[2573:7255781] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error

,2016-01-25 22:48:02.165 ThaliTest[2573:7255781] jxcore: stopBroadcasting
,2016-01-25 22:48:02.166 ThaliTest[2573:7255781] THEMultipeerSession stopping peer
,2016-01-25 22:48:02.167 ThaliTest[2573:7255781] multipeer session: stop timer
,2016-01-25 22:48:02.169 ThaliTest[2573:7255781] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error

,2016-01-25 22:48:02.171 ThaliTest[2573:7255781] jxcore: startBroadcasting
,2016-01-25 22:48:02.173 ThaliTest[2573:7255781] server: starting 1453758482171.2573.pMPokQ==
,2016-01-25 22:48:02.174 ThaliTest[2573:7255781] multipeer session: start timer: 0x16add6b0
,2016-01-25 22:48:02.176 ThaliTest[2573:7255781] THEMultipeerSession initialized peer 1453758482171.2573
2016-01-25 22:48:02.179 ThaliTest[2573:7255781] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error

,2016-01-25 22:48:02.180 ThaliTest[2573:7255781] jxcore: stopBroadcasting
,2016-01-25 22:48:02.181 ThaliTest[2573:7255781] THEMultipeerSession stopping peer
,2016-01-25 22:48:02.181 ThaliTest[2573:7255781] multipeer session: stop timer
,2016-01-25 22:48:02.182 ThaliTest[2573:7255781] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error

,2016-01-25 22:48:02.186 ThaliTest[2573:7255781] jxcore: startBroadcasting
,2016-01-25 22:48:02.188 ThaliTest[2573:7255781] server: starting 1453758482186.2573.jcZyMw==
,2016-01-25 22:48:02.190 ThaliTest[2573:7255781] multipeer session: start timer: 0x16d81440
,2016-01-25 22:48:02.192 ThaliTest[2573:7255781] THEMultipeerSession initialized peer 1453758482186.2573
,2016-01-25 22:48:02.194 ThaliTest[2573:7255781] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error

,2016-01-25 22:48:02.195 ThaliTest[2573:7255781] jxcore: stopBroadcasting
,2016-01-25 22:48:02.196 ThaliTest[2573:7255781] THEMultipeerSession stopping peer
,2016-01-25 22:48:02.196 ThaliTest[2573:7255781] multipeer session: stop timer
,2016-01-25 22:48:02.197 ThaliTest[2573:7255781] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-25 22:48:02.397 ThaliTest[2573:7255781] jxcore: startBroadcasting
,2016-01-25 22:48:02.399 ThaliTest[2573:7255781] server: starting 1453758482397.2573.VKOkJg==
,2016-01-25 22:48:02.404 ThaliTest[2573:7255781] multipeer session: start timer: 0x16d837b0
,2016-01-25 22:48:02.405 ThaliTest[2573:7255781] THEMultipeerSession initialized peer 1453758482397.2573
,2016-01-25 22:48:02.406 ThaliTest[2573:7255781] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error

,2016-01-25 22:48:02.408 ThaliTest[2573:7255781] jxcore: startBroadcasting
,2016-01-25 22:48:02.408 ThaliTest[2573:7255781] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice

,2016-01-25 22:48:02.411 ThaliTest[2573:7255781] jxcore: stopBroadcasting
,2016-01-25 22:48:02.412 ThaliTest[2573:7255781] THEMultipeerSession stopping peer
,2016-01-25 22:48:02.412 ThaliTest[2573:7255781] multipeer session: stop timer
,2016-01-25 22:48:02.413 ThaliTest[2573:7255781] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-25 22:48:02.824 ThaliTest[2573:7255781] jxcore: startBroadcasting
,2016-01-25 22:48:02.826 ThaliTest[2573:7255781] server: starting 1453758482824.2573.fGirqw==
2016-01-25 22:48:02.826 ThaliTest[2573:7255781] multipeer session: start timer: 0x16a4f0a0
2016-01-25 22:48:02.826 ThaliTest[2573:7255781] THEMultipeerSession initialized peer 1453758482824.2573
2016-01-25 22:48:02.827 ThaliTest[2573:7255781] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error

2016-01-25 22:48:02.828 ThaliTest[2573:7255781] jxcore: connect foobar
2,016-01-25 22:48:02.828 ThaliTest[2573:7255781] client: unknown peer foobar
2016-01-25 22:48:02.828 ThaliTest[2573:7255781] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer

2016-01-25 22:48:02.831 ThaliTest[2573:7255781] jxcore: stopBroadcasting
2016-01-25 22:48:02.831 ThaliTest[2573:7255781] THEMultipeerSession stopping peer
,2016-01-25 22:48:02.831 ThaliTest[2573:7255781] multipeer session: stop timer
2016-01-25 22:48:02.833 ThaliTest[2573:7255781] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-25 22:48:03.011 ThaliTest[2573:7255781] jxcore: startBroadcasting
,2016-01-25 22:48:03.014 ThaliTest[2573:7255781] server: starting 1453758483011.2573.5oq/Hg==
2016-01-25 22:48:03.015 ThaliTest[2573:7255781] multipeer session: start timer: 0x15eebd20
2016-01-25 22:48:03.015 ThaliTest[2573:7255781] THEMultipeerSession initialized peer 1453758483011.2573
2016-01-25 22:48:03.015 ThaliTest[2573:7255781] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error

2016-01-25 22:48:03.016 ThaliTest[2573:7255781] jxcore: disconnect
2016-,01-25 22:48:03.016 ThaliTest[2573:7255781] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 

2016-01-25 22:48:03.018 ThaliTest[2573:7255781] jxcore: stopBroadcasting
2016-01-25 22:48:03.018 ThaliTest[2573:7255781] THEMultip,eerSession stopping peer
2016-01-25 22:48:03.018 ThaliTest[2573:7255781] multipeer session: stop timer
2016-01-25 22:48:03.018 ThaliTest[2573:7255781] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-25 22:48:03.479 ThaliTest[2573:7255781] jxcore: startBroadcasting
,2016-01-25 22:48:03.481 ThaliTest[2573:7255781] server: starting 1453758483479.2573.JQH/bg==
2016-01-25 22:48:03.482 ThaliTest[2573:7255781] multipeer session: start timer: 0x16b1b630
2016-01-25 22:48:03.482 ThaliTest[2573:7255781] THEMultipeerSession in,itialized peer 1453758483479.2573
2016-01-25 22:48:03.482 ThaliTest[2573:7255781] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

,2016-01-25 22:48:04.743 ThaliTest[2573:7255619] client: found peer: 1453758483517.493.6i8lLA==
2016-01-25 22:48:04.744 ThaliTest[2573:7255781] jxcore: connect 1453758483517.493.6i8lLA==
2016-01-25 22:48:04.744 ThaliTest[2573:7255781] client session: connect
2016-01-25 22:48:04.744 ThaliTest[2573:7255781] client session: stateChange:0->1 1453758483517.493.6i8lLA==
,2016-01-25 22:48:05.178 ThaliTest[2573:7255619] multipeer session: reset timer
2016-01-25 22:48:05.179 ThaliTest[2573:7255619] multipeer session: stop timer
2016-01-25 22:48:05.179 ThaliTest[2573:7255619] multipeer session: start timer: 0x16b1b630
2016-,01-25 22:48:05.179 ThaliTest[2573:7255619] server session: connect
2016-01-25 22:48:05.179 ThaliTest[2573:7255619] server session: stateChange:0->1 1453758483517.493
,2016-01-25 22:48:05.184 ThaliTest[2573:7255619] server: accepting invitation 1453758483517.493
,2016-01-25 22:48:07.610 ThaliTest[2573:7258334] server session: connected
,2016-01-25 22:48:07.610 ThaliTest[2573:7258334] server session: stateChange:1->2 1453758483517.493
,2016-01-25 22:48:07.634 ThaliTest[2573:7255619] server relay: socket disconnected
2016-01-25 22:48:07.634 ThaliTest[2573:7255619] server relay: 0x16b25af0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-25 22:48:07.868 ThaliTest[2573:7258335] client session: connected
2016-01-25 22:48:07.868 ThaliTest[2573:7258335] client session: stateChange:1->2 1453758483517.493.6i8lLA==
,2016-01-25 22:48:07.896 ThaliTest[2573:7258336] client session: fireConnectCallback: 1453758483517.493.6i8lLA==
2016-01-25 22:48:07.896 ThaliTest[2573:7258336] jxcore: connect: success
ok 75 Should be able to connect without error

,ok 76 Port should be within range

,2016-01-25 22:48:07.898 ThaliTest[2573:7255781] jxcore: disconnect
2016-01-25 22:48:07.898 ThaliTest[2573:7255781] client session: disconnectFromPeer: 1453758483517.493.6i8lLA==
2016-01-25 22:48:07.898 ThaliTest[2573:7255781] client session: disconnect
2016-01-25 22:48:07.898 ThaliTest[2573:7255781] client session: stateChange:2->0 1453758483517.493.6i8lLA==
,2016-01-25 22:48:07.903 ThaliTest[2573:7255781] jxcore: disconnect: success
ok 77 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-25 22:48:08.197 ThaliTest[2573:7255781] jxcore: stopBroadcasting
2016-01-25 22:48:08.197 ThaliTest[2573:7255781] THEMultipeerSession stopping peer
2016-01-25 22:48:08.197 ThaliTest[2573:7255781] multipeer session: stop timer
2016-01-25 22:48:08.,198 ThaliTest[2573:7255781] server session: disconnect
2016-01-25 22:48:08.198 ThaliTest[2573:7255781] server session: stateChange:2->0 1453758483517.493
,2016-01-25 22:48:08.208 ThaliTest[2573:7255781] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-25 22:48:10.639 ThaliTest[2573:7255781] jxcore: startBroadcasting
,2016-01-25 22:48:10.641 ThaliTest[2573:7255781] server: starting 1453758490639.2573.VXkvvQ==
2016-01-25 22:48:10.641 ThaliTest[2573:7255781] multipeer session: start timer: 0x16b3dce0
2016-01-25 22:48:10.641 ThaliTest[2573:7255781] THEMultipeerSession initialized peer 1453758490639.2573
2016-01-25 22:48:10.641 ThaliTest[2573:7255781] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error

,2016-01-25 22:48:11.545 ThaliTest[2573:7255619] client: found peer: 1453758490707.493.6LlK6w==
,2016-01-25 22:48:11.546 ThaliTest[2573:7255781] jxcore: connect 1453758490707.493.6LlK6w==
2016-01-25 22:48:11.546 ThaliTest[2573:7255781] client session: connect
2016-01-25 22:48:11.546 ThaliTest[2573:7255781] client session: stateChange:0->1 1453758490,707.493.6LlK6w==
,2016-01-25 22:48:12.066 ThaliTest[2573:7255619] multipeer session: reset timer
2016-01-25 22:48:12.066 ThaliTest[2573:7255619] multipeer session: stop timer
2016-01-25 22:48:12.066 ThaliTest[2573:7255619] multipeer session: start timer: 0x16b3dce0
2016-,01-25 22:48:12.066 ThaliTest[2573:7255619] server session: connect
2016-01-25 22:48:12.066 ThaliTest[2573:7255619] server session: stateChange:0->1 1453758490707.493
,2016-01-25 22:48:12.071 ThaliTest[2573:7255619] server: accepting invitation 1453758490707.493
,2016-01-25 22:48:14.578 ThaliTest[2573:7258350] server session: connected
2016-01-25 22:48:14.578 ThaliTest[2573:7258350] server session: stateChange:1->2 1453758490707.493
,2016-01-25 22:48:14.581 ThaliTest[2573:7255619] server relay: socket disconnected
2016-01-25 22:48:14.581 ThaliTest[2573:7255619] server relay: 0x15ec4ae0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-25 22:48:14.626 ThaliTest[2573:7258334] client session: connected
2016-01-25 22:48:14.626 ThaliTest[2573:7258334] client session: stateChange:1->2 1453758490707.493.6LlK6w==
,2016-01-25 22:48:14.644 ThaliTest[2573:7258350] client session: fireConnectCallback: 1453758490707.493.6LlK6w==
2016-01-25 22:48:14.645 ThaliTest[2573:7258350] jxcore: connect: success
ok 79 Should be able to connect without error

,ok 80 Port should be within range

,2016-01-25 22:48:14.646 ThaliTest[2573:7255781] jxcore: connect 1453758490707.493.6LlK6w==
2016-01-25 22:48:14.647 ThaliTest[2573:7255781] client: already connect(ing/ed) to 1453758490707.493.6LlK6w==
2016-01-25 22:48:14.647 ThaliTest[2573:7255781] jxcore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect

,2016-01-25 22:48:14.648 ThaliTest[2573:7255781] jxcore: disconnect
2016-01-25 22:48:14.649 ThaliTest[2573:7255781] client session: disconnectFromPeer: 1453758490707.493.6LlK6w==
2016-01-25 22:48:14.649 ThaliTest[2573:7255781] client session: disconnect
,2016-01-25 22:48:14.649 ThaliTest[2573:7255781] client session: stateChange:2->0 1453758490707.493.6LlK6w==
,2016-01-25 22:48:14.710 ThaliTest[2573:7258350] server session: not connected 1453758490707.493
,2016-01-25 22:48:14.712 ThaliTest[2573:7255781] jxcore: disconnect: success
,ok 82 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-25 22:48:15.058 ThaliTest[2573:7255781] jxcore: stopBroadcasting
2016-01-25 22:48:15.059 ThaliTest[2573:7255781] THEMultipeerSession stopping peer
2016-01-25 22:48:15.059 ThaliTest[2573:7255781] multipeer session: stop timer
2016-01-25 22:48:15.059 ThaliTest[2573:7255781] server session: disconnect
2016-01-25 22:48:15.059 ThaliTest[2573:7255781] server session: stateChange:2->0 1453758490707.493
2016-01-25 22:48:15.060 ThaliTest[2573:7255781] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-25 22:48:15.607 ThaliTest[2573:7255781] jxcore: startBroadcasting
,2016-01-25 22:48:15.609 ThaliTest[2573:7255781] server: starting 1453758495607.2573.yyw6pw==
2016-01-25 22:48:15.609 ThaliTest[2573:7255781] multipeer session: start timer: 0x15903e40
2016-01-25 22:48:15.609 ThaliTest[2573:7255781] THEMultipeerSession initialized peer 1453758495607.2573
2016-01-25 22:48:15.609 ThaliTest[2573:7255781] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-25 22:48:16.185 ThaliTest[2573:7255619] client: found peer: 1453758490707.493.6LlK6w==
,2016-01-25 22:48:16.186 ThaliTest[2573:7255781] jxcore: connect 1453758490707.493.6LlK6w==
2016-01-25 22:48:16.187 ThaliTest[2573:7255781] client session: connect
2016-01-25 22:48:16.187 ThaliTest[2573:7255781] client session: stateChange:0->1 1453758490707.493.6LlK6w==
,2016-01-25 22:48:18.356 ThaliTest[2573:7255619] multipeer session: reset timer
2016-01-25 22:48:18.356 ThaliTest[2573:7255619] multipeer session: stop timer
2016-01-25 22:48:18.356 ThaliTest[2573:7255619] multipeer session: start timer: 0x15903e40
2016-,01-25 22:48:18.356 ThaliTest[2573:7255619] server session: connect
2016-01-25 22:48:18.356 ThaliTest[2573:7255619] server session: stateChange:0->1 1453758497006.493
,2016-01-25 22:48:18.360 ThaliTest[2573:7255619] server: accepting invitation 1453758497006.493
,2016-01-25 22:48:18.389 ThaliTest[2573:7255619] client: lost peer: 1453758490707.493.6LlK6w==
2016-01-25 22:48:18.389 ThaliTest[2573:7255619] client session: onPeerLost: 1453758490707.493.6LlK6w==
2016-01-25 22:48:18.390 ThaliTest[2573:7255619] client session: onLinkFailure: 1453758490707.493.6LlK6w==
2016-01-25 22:48:18.390 ThaliTest[2573:7255619] client session: disconnect
2016-01-25 22:48:18.390 ThaliTest[2573:7255619] client session: stateChange:1->0 1453758490707.493.6LlK6w==
2016-01-25 22:48:18.3,92 ThaliTest[2573:7255619] client session: fireConnectCallback: 1453758490707.493.6LlK6w==
2016-01-25 22:48:18.392 ThaliTest[2573:7255619] jxcore: connect: fail: Peer disconnected
2016-01-25 22:48:18.393 ThaliTest[2573:7255619] client: found peer: 1453758497006.493.XIyKWg==
,2016-01-25 22:48:18.395 ThaliTest[2573:7255781] jxcore: connect 1453758497006.493.XIyKWg==
2016-01-25 22:48:18.400 ThaliTest[2573:7255781] client session: connect
2016-01-25 22:48:18.400 ThaliTest[2573:7255781] client session: stateChange:0->1 1453758497006.493.XIyKWg==
,2016-01-25 22:48:19.400 ThaliTest[2573:7255781] jxcore: connect 1453758490707.493.6LlK6w==
2016-01-25 22:48:19.400 ThaliTest[2573:7255781] client: connect: unreachable 1453758490707.493.6LlK6w==
2016-01-25 22:48:19.400 ThaliTest[2573:7255781] jxcore: connect: fail: Peer unreachable
,2016-01-25 22:48:21.114 ThaliTest[2573:7258335] server session: connected
2016-01-25 22:48:21.114 ThaliTest[2573:7258335] server session: stateChange:1->2 1453758497006.493
,2016-01-25 22:48:21.118 ThaliTest[2573:7255619] server relay: socket disconnected
2016-01-25 22:48:21.119 ThaliTest[2573:7255619] server relay: 0x16bef660 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-25 22:48:21.195 ThaliTest[2573:7258334] server session: not connected 1453758497006.493
,2016-01-25 22:48:21.380 ThaliTest[2573:7258334] client session: connected
2016-01-25 22:48:21.380 ThaliTest[2573:7258334] client session: stateChange:1->2 1453758497006.493.XIyKWg==
,2016-01-25 22:48:21.386 ThaliTest[2573:7258334] client session: fireConnectCallback: 1453758497006.493.XIyKWg==
2016-01-25 22:48:21.386 ThaliTest[2573:7258334] jxcore: connect: success
ok 84 Should be able to connect without error

ok 85 Port should be within range

2016-01-25 22:48:21.388 ThaliTest[2573:7255781] jxcore: disconnect
2016-01-25 22:48:21.389 ThaliTest[2573:7255781] client session: disconnectFromPeer: 1453758497006.493.XIyKWg==
2016-01-25 22:48:21.389 ThaliTest[2573:7255781] client session: disconnect
2016-01-25 22:48:21.389 ThaliTest[2573:7255781] client session: stateChange:2->0 1453758497006.493.XIyKWg==
,2016-01-25 22:48:21.465 ThaliTest[2573:7255781] jxcore: disconnect: success
ok 86 Should be able to disconnect without error

2016-01-25 22:48:21.466 ThaliTest[2573:7255781] jxcore: disconnect
2016-01-25 22:48:21.466 ThaliTest[2573:7255781] jxcore: disconnect: fail
ok 87 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

2016-01-25 22:48:21.831 ThaliTest[2573:7255781] jxcore: stopBroadcasting
2016-01-25 22:48:21.831 ThaliTest[2573:7255781] THEMultipeerSession stopping peer
2016-01-25 22:48:21.831 ThaliTest[2573:7255781] multipeer session: stop, timer
2016-01-25 22:48:21.832 ThaliTest[2573:7255781] server session: disconnect
2016-01-25 22:48:21.832 ThaliTest[2573:7255781] server session: stateChange:2->0 1453758497006.493
2016-01-25 22:48:21.832 ThaliTest[2573:7255781] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 63757

,2016-01-25 22:48:23.142 ThaliTest[2573:7255781] jxcore: startBroadcasting
,2016-01-25 22:48:23.145 ThaliTest[2573:7255781] server: starting 1453758503142.2573.KND68g==
,2016-01-25 22:48:23.148 ThaliTest[2573:7255781] multipeer session: start timer: 0x16bf5370
,2016-01-25 22:48:23.152 ThaliTest[2573:7255781] THEMultipeerSession initialized peer 1453758503142.2573
,2016-01-25 22:48:23.153 ThaliTest[2573:7255781] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error

,2016-01-25 22:48:24.663 ThaliTest[2573:7255619] client: found peer: 1453758502986.493.FryYxg==
2016-01-25 22:48:24.664 ThaliTest[2573:7255781] jxcore: connect 1453758502986.493.FryYxg==
2016-01-25 22:48:24.665 ThaliTest[2573:7255781] client session: connect
2016-01-25 22:48:24.665 ThaliTest[2573:7255781] client session: stateChange:0->1 1453758502986.493.FryYxg==
,2016-01-25 22:48:24.769 ThaliTest[2573:7255619] multipeer session: reset timer
,2016-01-25 22:48:24.770 ThaliTest[2573:7255619] multipeer session: stop timer
2016-01-25 22:48:24.770 ThaliTest[2573:7255619] multipeer session: start timer: 0x16bf5370
2016-01-25 22:48:24.770 ThaliTest[2573:7255619] server session: connect
,2016-01-25 22:48:24.770 ThaliTest[2573:7255619] server session: stateChange:0->1 1453758502986.493
,2016-01-25 22:48:24.774 ThaliTest[2573:7255619] server: accepting invitation 1453758502986.493
,2016-01-25 22:48:27.307 ThaliTest[2573:7258405] server session: connected
2016-01-25 22:48:27.307 ThaliTest[2573:7258405] server session: stateChange:1->2 1453758502986.493
,2016-01-25 22:48:27.357 ThaliTest[2573:7255619] server relay: connected (to port: 63757)
,2016-01-25 22:48:27.829 ThaliTest[2573:7258349] client session: connected
2016-01-25 22:48:27.829 ThaliTest[2573:7258349] client session: stateChange:1->2 1453758502986.493.FryYxg==
,2016-01-25 22:48:27.887 ThaliTest[2573:7258405] client session: fireConnectCallback: 1453758502986.493.FryYxg==
2016-01-25 22:48:27.887 ThaliTest[2573:7258405] jxcore: connect: success
,ok 89 Should be able to connect without error

ok 90 Port should be within range

,2016-01-25 22:48:27.891 ThaliTest[2573:7255619] client: relay established
2016-01-25 22:48:27.891 ThaliTest[2573:7255619] client: new accepted socket: 0x16a49bb0
,2016-01-25 22:48:27.919 ThaliTest[2573:7258405] server session: not connected 1453758502986.493
,data in 5475

,data in 6570

,data in 10950

,data in 25185

,data in 38325

,data in 82125

,data in 91980

,data in 95265

,data in 127009

,data in 131072

,ok 91 the test messages should be equal

,2016-01-25 22:48:28.529 ThaliTest[2573:7255781] jxcore: disconnect
2016-01-25 22:48:28.530 ThaliTest[2573:7255781] client session: disconnectFromPeer: 1453758502986.493.FryYxg==
2016-01-25 22:48:28.530 ThaliTest[2573:7255781] client session: disconnect
2016-01-25 22:48:28.530 ThaliTest[2573:7255781] client session: stateChange:2->0 1453758502986.493.FryYxg==
,2016-01-25 22:48:28.537 ThaliTest[2573:7255781] jxcore: disconnect: success
ok 92 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

# setup

,calling stopBroadcasting

,2016-01-25 22:48:28.644 ThaliTest[2573:7255781] jxcore: stopBroadcasting
2016-01-25 22:48:28.644 ThaliTest[2573:7255781] THEMultipeerSession stopping peer
2016-01-25 22:48:28.644 ThaliTest[2573:7255781] multipeer session: stop timer
2016-01-25 22:48:28.645 ThaliTest[2573:7255781] server session: disconnect
2016-01-25 22:48:28.645 ThaliTest[2573:7255781] server session: stateChange:2->0 1453758502986.493
,2016-01-25 22:48:28.648 ThaliTest[2573:7255781] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 63763

,2016-01-25 22:48:28.743 ThaliTest[2573:7255781] jxcore: startBroadcasting
,2016-01-25 22:48:28.744 ThaliTest[2573:7255781] server: starting 1453758508742.2573.8F72Rw==
2016-01-25 22:48:28.745 ThaliTest[2573:7255781] multipeer session: start timer: 0x16be8610
2016-01-25 22:48:28.745 ThaliTest[2573:7255781] THEMultipeerSession initialized peer 1453758508742.2573
2016-01-25 22:48:28.745 ThaliTest[2573:7255781] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error

,2016-01-25 22:48:29.521 ThaliTest[2573:7255619] client: found peer: 1453758503142.2573.KND68g==
2016-01-25 22:48:29.521 ThaliTest[2573:7255619] client: found peer: 1453758502986.493.FryYxg==
[{"peerIdentifier":"1453758503142.2573.KND68g==","peerName":"(null)","peerAvailable":true}]

2016-01-25 22:48:29.523 ThaliTest[2573:7255781] jxcore: connect 1453758503142.2573.KND68g==
2016-01-25 22:48:29.523 ThaliTest[2573:7255781] client session: connect
2016-01-25 22:48:29.523 ThaliTest[2573:7255781] client session: stateChange:0->1 1453758503142.2573.KND68g==
,[{"peerIdentifier":"1453758502986.493.FryYxg==","peerName":"(null)","peerAvailable":true}]

2016-01-25 22:48:29.535 ThaliTest[2573:7255781] jxcore: connect 1453758502986.493.FryYxg==
2016-01-25 22:48:29.536 ThaliTest[2573:7255781] client session: connect
2016-01-25 22:48:29.536 ThaliTest[2573:7255781] client session: stateChange:0->1 1453758502986.493.FryYxg==
,2016-01-25 22:48:29.865 ThaliTest[2573:7255619] client: lost peer: 1453758503142.2573.KND68g==
2016-01-25 22:48:29.865 ThaliTest[2573:7255619] client session: onPeerLost: 1453758503142.2573.KND68g==
2016-01-25 22:48:29.865 ThaliTest[2573:7255619] client session: onLinkFailure: 1453758503142.2573.KND68g==
2016-01-25 22:48:29.866 ThaliTest[2573:7255619] client session: disconnect
2016-01-25 22:48:29.866 ThaliTest[2573:7255619] client session: stateChange:1->0 1453758503142.2573.KND68g==
2016-01-25 22:48:,29.866 ThaliTest[2573:7255619] client session: fireConnectCallback: 1453758503142.2573.KND68g==
2016-01-25 22:48:29.866 ThaliTest[2573:7255619] jxcore: connect: fail: Peer disconnected
2016-01-25 22:48:29.866 ThaliTest[2573:7255619] client: lost peer: 14,53758502986.493.FryYxg==
2016-01-25 22:48:29.867 ThaliTest[2573:7255619] client session: onPeerLost: 1453758502986.493.FryYxg==
2016-01-25 22:48:29.867 ThaliTest[2573:7255619] client session: onLinkFailure: 1453758502986.493.FryYxg==
2016-01-25 22:48:29,.867 ThaliTest[2573:7255619] client session: disconnect
2016-01-25 22:48:29.868 ThaliTest[2573:7255619] client session: stateChange:1->0 1453758502986.493.FryYxg==
2016-01-25 22:48:29.869 ThaliTest[2573:7255619] client session: fireConnectCallback: 1453758502986.493.FryYxg==
2016-01-25 22:48:29.869 ThaliTest[2573:7255619] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1453758503142.2573.KND68g==","peerName":"(null)","peerAvailable":false}]

[{"peerIdentifier":"1453758502986.493.FryYxg==",,"peerName":"(null)","peerAvailable":false}]

,2016-01-25 22:48:29.948 ThaliTest[2573:7255619] client: found peer: 1453758508774.493.PEbBJQ==
[{"peerIdentifier":"1453758508774.493.PEbBJQ==","peerName":"(null)","peerAvailable":true}]

2016-01-25 22:48:29.949 ThaliTest[2573:7255781] jxcore: connect 14,53758508774.493.PEbBJQ==
2016-01-25 22:48:29.950 ThaliTest[2573:7255781] client session: connect
2016-01-25 22:48:29.950 ThaliTest[2573:7255781] client session: stateChange:0->1 1453758508774.493.PEbBJQ==
,2016-01-25 22:48:30.007 ThaliTest[2573:7255619] multipeer session: reset timer
2016-01-25 22:48:30.007 ThaliTest[2573:7255619] multipeer session: stop timer
2016-01-25 22:48:30.007 ThaliTest[2573:7255619] multipeer session: start timer: 0x16be8610
2016-01-25 22:48:30.008 ThaliTest[2573:7255619] server session: connect
2016-01-25 22:48:30.008 ThaliTest[2573:7255619] server session: stateChange:0->1 1453758508774.493
,2016-01-25 22:48:30.011 ThaliTest[2573:7255619] server: accepting invitation 1453758508774.493
,2016-01-25 22:48:30.873 ThaliTest[2573:7255781] jxcore: connect 1453758503142.2573.KND68g==
2016-01-25 22:48:30.873 ThaliTest[2573:7255781] client: connect: unreachable 1453758503142.2573.KND68g==
2016-01-25 22:48:30.874 ThaliTest[2573:7255781] jxcore: connect: fail: Peer unreachable
,2016-01-25 22:48:30.875 ThaliTest[2573:7255781] jxcore: connect 1453758502986.493.FryYxg==
2016-01-25 22:48:30.875 ThaliTest[2573:7255781] client: connect: unreachable 1453758502986.493.FryYxg==
2016-01-25 22:48:30.875 ThaliTest[2573:7255781] jxcore: connect: fail: Peer unreachable
,2016-01-25 22:48:32.460 ThaliTest[2573:7258349] server session: connected
2016-01-25 22:48:32.460 ThaliTest[2573:7258349] server session: stateChange:1->2 1453758508774.493
,2016-01-25 22:48:32.479 ThaliTest[2573:7255619] server relay: connected (to port: 63763)
,2016-01-25 22:48:32.611 ThaliTest[2573:7258349] server session: not connected 1453758508774.493
,2016-01-25 22:48:32.707 ThaliTest[2573:7258349] client session: connected
2016-01-25 22:48:32.707 ThaliTest[2573:7258349] client session: stateChange:1->2 1453758508774.493.PEbBJQ==
,2016-01-25 22:48:32.731 ThaliTest[2573:7258335] client session: fireConnectCallback: 1453758508774.493.PEbBJQ==
2016-01-25 22:48:32.731 ThaliTest[2573:7258335] jxcore: connect: success
,ok 94 Should be able to connect without error

,ok 95 Port should be within range

,ok 96 First connect should succeed

,2016-01-25 22:48:32.744 ThaliTest[2573:7255619] client: relay established
2016-01-25 22:48:32.744 ThaliTest[2573:7255619] client: new accepted socket: 0x16a52370
,2016-01-25 22:48:32.773 ThaliTest[2573:7255619] multipeer session: reset timer
,2016-01-25 22:48:32.773 ThaliTest[2573:7255619] multipeer session: stop timer
2016-01-25 22:48:32.773 ThaliTest[2573:7255619] multipeer session: start timer: 0x16be8610
,2016-01-25 22:48:32.773 ThaliTest[2573:7255619] server: disconnecting to refresh session (1453758508774.493)
2016-01-25 22:48:32.773 ThaliTest[2573:7255619] server session: disconnect
2016-01-25 22:48:32.774 ThaliTest[2573:7255619] server session: stateChange:2->0 1453758508774.493
,2016-01-25 22:48:32.777 ThaliTest[2573:7255619] server session: connect
,2016-01-25 22:48:32.778 ThaliTest[2573:7255619] server session: stateChange:0->1 1453758508774.493
,2016-01-25 22:48:32.787 ThaliTest[2573:7255619] server: accepting invitation 1453758508774.493
,ok 97 the test messages should be equal

ok 98 First send should succeed

,2016-01-25 22:48:32.853 ThaliTest[2573:7255619] client: socket closed
2016-01-25 22:48:32.853 ThaliTest[2573:7255619] client relay: socket disconnected
2016-01-25 22:48:32.853 ThaliTest[2573:7255619] client relay: 0x16a52370 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-25 22:48:32.853 ThaliTest[2573:7255619] client session: socket closed: 1453758508774.493.PEbBJQ==
2016-01-25 22:48:32.854 ThaliTest[2573:7255619] client session: onLinkFailure: 1453758508774.493.PEbBJQ==
2016-01-25 22:48:32.854 ThaliTest[2573:7255619] client session: disconnect
2016-01-25 22:48:32.854 ThaliTest[2573:7255619] client session: stateChange:2->0 1453,758508774.493.PEbBJQ==
,2016-01-25 22:48:32.867 ThaliTest[2573:7255619] client session: fireConnectionErrorEvent: 1453758508774.493.PEbBJQ==
,2016-01-25 22:48:32.869 ThaliTest[2573:7255781] jxcore: connect 1453758508774.493.PEbBJQ==
,2016-01-25 22:48:32.870 ThaliTest[2573:7255781] client session: connect
,2016-01-25 22:48:32.871 ThaliTest[2573:7255781] client session: stateChange:0->1 1453758508774.493.PEbBJQ==
,2016-01-25 22:48:35.411 ThaliTest[2573:7258334] server session: connected
2016-01-25 22:48:35.412 ThaliTest[2573:7258334] server session: stateChange:1->2 1453758508774.493
,2016-01-25 22:48:35.428 ThaliTest[2573:7255619] server relay: connected (to port: 63763)
,2016-01-25 22:48:35.585 ThaliTest[2573:7258350] server session: not connected 1453758508774.493
,2016-01-25 22:48:35.721 ThaliTest[2573:7258350] client session: connected
2016-01-25 22:48:35.722 ThaliTest[2573:7258350] client session: stateChange:1->2 1453758508774.493.PEbBJQ==
,2016-01-25 22:48:35.780 ThaliTest[2573:7258350] client session: fireConnectCallback: 1453758508774.493.PEbBJQ==
2016-01-25 22:48:35.780 ThaliTest[2573:7258350] jxcore: connect: success
ok 99 Should be able to connect without error

ok 100 Port should be within range

ok 101 Second connect should succeed

,2016-01-25 22:48:35.795 ThaliTest[2573:7255619] client: relay established
2016-01-25 22:48:35.796 ThaliTest[2573:7255619] client: new accepted socket: 0x16bda390
,ok 102 the test messages should be equal

,ok 103 Second send should succeed

# setup

,2016-01-25 22:48:35.862 ThaliTest[2573:7255619] client: socket closed
2016-01-25 22:48:35.862 ThaliTest[2573:7255619] client relay: socket disconnected
2016-01-25 22:48:35.862 ThaliTest[2573:7255619] client relay: 0x16bda390 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-25 22:48:35.862 ThaliTest[2573:7255619] client session: socket closed: 1453758508774.493.PEbBJQ==
2016-01-25 2,2:48:35.862 ThaliTest[2573:7255619] client session: onLinkFailure: 1453758508774.493.PEbBJQ==
2016-01-25 22:48:35.862 ThaliTest[2573:7255619] client session: disconnect
2016-01-25 22:48:35.862 ThaliTest[2573:7255619] client session: stateChange:2->0 1453,758508774.493.PEbBJQ==
2016-01-25 22:48:35.870 ThaliTest[2573:7255619] client session: fireConnectionErrorEvent: 1453758508774.493.PEbBJQ==
,calling stopBroadcasting

2016-01-25 22:48:35.981 ThaliTest[2573:7255781] jxcore: stopBroadcasting
2016-01-25 22:48:35.981 ThaliTest[2573:7255781] THEMultipeerSession stopping peer
2016-01-25 22:48:35.981 ThaliTest[2573:7255781] multipeer session: stop timer
2016-01-25 22:48:35.981 ThaliTest[2573:7255781] server session: disconnect
,2016-01-25 22:48:35.982 ThaliTest[2573:7255781] server session: stateChange:2->0 1453758508774.493
,2016-01-25 22:48:35.987 ThaliTest[2573:7255781] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/CCBE44E8-1656-41FE-8AA1-925F7AD6F22B/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 104 starting event should occur in right order

,2016-01-25 22:48:36.607 ThaliTest[2573:7255781] jxcore: startBroadcasting
,2016-01-25 22:48:36.609 ThaliTest[2573:7255781] server: starting m0DogFG2ls-s2IDbNWmIyA.U7LUig==
,2016-01-25 22:48:36.611 ThaliTest[2573:7255781] multipeer session: start timer: 0x16a46ef0
2016-01-25 22:48:36.613 ThaliTest[2573:7255781] THEMultipeerSession initialized peer m0DogFG2ls-s2IDbNWmIyA
,2016-01-25 22:48:36.614 ThaliTest[2573:7255781] jxcore: startBroadcasting: success
,ok 105 started event should occur in right order

,Now in TRM stop

State of this._isStarted: true
,
,ok 106 stopping event should occur in right order

,About to call stopBroadcasting

,2016-01-25 22:48:36.619 ThaliTest[2573:7255781] jxcore: stopBroadcasting
,2016-01-25 22:48:36.619 ThaliTest[2573:7255781] THEMultipeerSession stopping peer
,2016-01-25 22:48:36.620 ThaliTest[2573:7255781] multipeer session: stop timer
,2016-01-25 22:48:36.623 ThaliTest[2573:7255781] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,
,ok 107 stopped event should occur in right order

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/CCBE44E8-1656-41FE-8AA1-925F7AD6F22B/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-25 22:48:37.142 ThaliTest[2573:7255781] jxcore: startBroadcasting
,2016-01-25 22:48:37.144 ThaliTest[2573:7255781] server: starting m0DogFG2ls-s2IDbNWmIyA.YB1kxA==
2016-01-25 22:48:37.144 ThaliTest[2573:7255781] multipeer session: start timer: 0x16be4140
2016-01-25 22:48:37.145 ThaliTest[2573:7255781] THEMultipeerSessio,n initialized peer m0DogFG2ls-s2IDbNWmIyA
2016-01-25 22:48:37.145 ThaliTest[2573:7255781] jxcore: startBroadcasting: success
ok 108 getDeviceIdentity should not return an error

ok 109 deviceName should not be null

Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

2016-01-25 22:48:37.147 ThaliTest[2573:7255781] jxcore: stopBroadcasting
2016-01-25 22:48:37.147 ThaliTest[2573:7255781] THEMultipeerSession stopping peer
2016-01-25 22:48:37.147 ThaliTest[2573:7255781,] multipeer session: stop timer
2016-01-25 22:48:37.147 ThaliTest[2573:7255781] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/CCBE44E8-1656-41FE-8AA1-925F7AD6F22B/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-25 22:48:40.696 ThaliTest[2573:7255781] jxcore: startBroadcasting
,2016-01-25 22:48:40.699 ThaliTest[2573:7255781] server: starting m0DogFG2ls-s2IDbNWmIyA.a+MVCQ==
,2016-01-25 22:48:40.700 ThaliTest[2573:7255781] multipeer session: start timer: 0x1788c8d0
,2016-01-25 22:48:40.704 ThaliTest[2573:7255781] THEMultipeerSession initialized peer m0DogFG2ls-s2IDbNWmIyA
,2016-01-25 22:48:40.705 ThaliTest[2573:7255781] jxcore: startBroadcasting: success
,ok 110 getDeviceIdentity should not return an error

,ok 111 deviceName should not be null

,2016-01-25 22:48:41.414 ThaliTest[2573:7255619] client: found peer: NqTluJzHtE2jMQ4WW3MIsw.4mR9sg==
,2016-01-25 22:48:46.317 ThaliTest[2573:7255781] jxcore: connect NqTluJzHtE2jMQ4WW3MIsw.4mR9sg==
,2016-01-25 22:48:46.319 ThaliTest[2573:7255781] client session: connect
,2016-01-25 22:48:46.320 ThaliTest[2573:7255781] client session: stateChange:0->1 NqTluJzHtE2jMQ4WW3MIsw.4mR9sg==
,ok 112 Should be able to put doc without error

,ok 113 1st change of local doc should contain local id

,2016-01-25 22:48:46.602 ThaliTest[2573:7255619] multipeer session: reset timer
2016-01-25 22:48:46.602 ThaliTest[2573:7255619] multipeer session: stop timer
2016-01-25 22:48:46.602 ThaliTest[2573:7255619] multipeer session: start timer: 0x1788c8d0
2016-01-25 22:48:46.603 ThaliTest[2573:7255619] server session: connect
2016-01-25 22:48:46.603 ThaliTest[2573:7255619] server session: stateChange:0->1 NqTluJzHtE2jMQ4WW3MIsw
,2016-01-25 22:48:46.608 ThaliTest[2573:7255619] server: accepting invitation NqTluJzHtE2jMQ4WW3MIsw
,2016-01-25 22:48:49.326 ThaliTest[2573:7258349] server session: connected
2016-01-25 22:48:49.326 ThaliTest[2573:7258349] server session: stateChange:1->2 NqTluJzHtE2jMQ4WW3MIsw
,2016-01-25 22:48:49.335 ThaliTest[2573:7255619] server relay: connected (to port: 63782)
,server bridge: new client socket

,2016-01-25 22:48:49.454 ThaliTest[2573:7258536] client session: connected
2016-01-25 22:48:49.455 ThaliTest[2573:7258536] client session: stateChange:1->2 NqTluJzHtE2jMQ4WW3MIsw.4mR9sg==
,2016-01-25 22:48:49.475 ThaliTest[2573:7258336] client session: fireConnectCallback: NqTluJzHtE2jMQ4WW3MIsw.4mR9sg==
2016-01-25 22:48:49.475 ThaliTest[2573:7258336] jxcore: connect: success
,2016-01-25 22:48:49.482 ThaliTest[2573:7255619] client: relay established
2016-01-25 22:48:49.482 ThaliTest[2573:7255619] client: new accepted socket: 0x16b21d40
,client bridge: new client socket

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
,
client bridge: socket closed
,
,client bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed
,
,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,ok 114 1st change of remote doc should contain remote id

,ok 115 Can update remote doc without error

,null

,{ ok: true,
  id: '6154bfa7-99b8-4315-b40d-c1e1ea05b188',
  rev: '2-7cea1d385d7a7e22952fa541afa60198' }

,client bridge: new client socket
,
,ok 116 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,ok 117 Local changes occur in strict order

,ok 118 2nd change of local doc should contain remote id

,# setup

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket
,
,Now in TRM stop

,State of this._isStarted: true

,About to call stopBroadcasting

,2016-01-25 22:49:03.777 ThaliTest[2573:7255781] jxcore: stopBroadcasting
,2016-01-25 22:49:03.778 ThaliTest[2573:7255781] THEMultipeerSession stopping peer
,2016-01-25 22:49:03.779 ThaliTest[2573:7255781] multipeer session: stop timer
,2016-01-25 22:49:03.780 ThaliTest[2573:7255781] client session: disconnect
2016-01-25 22:49:03.780 ThaliTest[2573:7255781] client session: stateChange:2->0 NqTluJzHtE2jMQ4WW3MIsw.4mR9sg==
,2016-01-25 22:49:03.849 ThaliTest[2573:7255781] server session: disconnect
2016-01-25 22:49:03.849 ThaliTest[2573:7255781] server session: stateChange:2->0 NqTluJzHtE2jMQ4WW3MIsw
,2016-01-25 22:49:03.927 ThaliTest[2573:7255781] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,# #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

,client bridge: socket closed
,
,server bridge: socket closed

,# teardown

,ok 119 should be equal

,# setup

,# #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation

,# teardown

,ok 120 should not be equal

# setup

,# verify that Thali-specific messages are filtered correctly

,# teardown

,ok 121 irrelevant messages should be ignored

ok 122 relevant messages should not be ignored

ok 123 messages from this device should be ignored

,Tests Complete

,Total: 0	Passed: 0	Failed: 0

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
