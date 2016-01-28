#### Test 573480784751f5c_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/573480784751f5c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/E3BB1F50-0140-4582-B5AC-87529E360F89/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E3BB1F50-0140-4582-B5AC-87529E360F89/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/573480784751f5c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/573480784751f5c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/76456340-4BB6-4EF7-A533-76785ADFD1DF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62266"
,(lldb)     command script import "/tmp/E3BB1F50-0140-4582-B5AC-87529E360F89/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-28 13:51:37.250 ThaliTest[2793:7956167] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C33C27D9-B0ED-4082-80A5-5B6E9DF1B263/Library/Cookies/Cookies.binarycookies
,2016-01-28 13:51:37.539 ThaliTest[2793:7956167] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-28 13:51:37.540 ThaliTest[2793:7956167] Multi-tasking -> Device: YES, App: YES
,2016-01-28 13:51:37.545 ThaliTest[2793:7956167] Unlimited access to network resources
,2016-01-28 13:51:37.556 ThaliTest[2793:7956167] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-28 13:51:41.967 ThaliTest[2793:7956167] Resetting plugins due to page load.
,2016-01-28 13:51:43.356 ThaliTest[2793:7956167] Finished load of: file:///var/mobile/Containers/Bundle/Application/76456340-4BB6-4EF7-A533-76785ADFD1DF/ThaliTest.app/www/index.html
,2016-01-28 13:51:43.570 ThaliTest[2793:7956167] JXcore Cordova plugin initializing
2016-01-28 13:51:43.571 ThaliTest[2793:7956412] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5s-1
,
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/76456340-4BB6-4EF7-A533-76785ADFD1DF/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/76456340-4BB6-4EF7-A533-76785ADFD1DF/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/76456340-4BB6-4EF7-A533-76785ADFD1DF/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/76456340-4BB6-4EF7-A533-76785ADFD1DF/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/76456340-4BB6-4EF7-A533-76785ADFD1DF/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/76456340-4BB6-4EF7-A533-76785ADFD1DF/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/76456340-4BB6-4EF7-A533-76785ADFD1DF/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/76456340-4BB6-4EF7-A533-76785ADFD1DF/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

ok 3 firstPromise result

ok 4 firstPromise testValue

,ok 5 secondPromise setTimeout

ok 6 secondPromise result

ok 7 secondPromise testValue

ok 8 thirdPromise in promise

ok 9 thirdPromise result

ok 10 thirdPromise testValue

# setup

,# basic

,# teardown

,ok 11 sane

# setup

,# another

,# teardown

,ok 12 sane

,# setup

,# successfully create a new pkcs12 file and return hash value

,# teardown

,ok 13 should be equal

,ok 14 null

,ok 15 (unnamed assert)

ok 16 should be equal

,ok 17 should not throw

# setup

,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 18 (unnamed assert)

,ok 19 (unnamed assert)

ok 20 should not throw

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

ok 26 should be equal

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

# setup

,# #startBroadcasting should throw on non-number port

,# teardown

,ok 31 should throw

# setup

,# #startBroadcasting should throw on NaN port

,# teardown

,ok 32 should throw

# setup

,# #startBroadcasting should throw on negative port

,# teardown

,ok 33 should throw

# setup

,# #startBroadcasting should throw on too large port

,# teardown

,ok 34 should throw

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,# teardown

,ok 35 should be equal

ok 36 should be equal

ok 37 should be equal

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,# teardown

,ok 38 should be equal

,ok 39 should be equal

ok 40 should be equal

# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,# teardown

,ok 41 should be equal

ok 42 should be equal

# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,# teardown

,ok 43 should be equal

ok 44 should be equal

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,# teardown

,ok 45 should be equal

ok 46 should be equal

ok 47 should be equal

# setup

,# #connect should call Mobile("Connect") and handle an error

,# teardown

,ok 48 should be equal

ok 49 should be equal

,# setup

,# should call Mobile("Disconnect") without an error

,# teardown

,ok 50 should be equal

ok 51 should be equal

,# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 52 should be equal

ok 53 should be equal

# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-01-28 13:56:40.070 ThaliTest[2793:7956412] jxcore: startBroadcasting
,2016-01-28 13:56:40.078 ThaliTest[2793:7956412] server: starting 1453985800070.2793.VXoNIw==
2016-01-28 13:56:40.079 ThaliTest[2793:7956412] multipeer session: start timer: 0x1665c720
2016-01-28 13:56:40.079 ThaliTest[2793:7956412] THEMultipeerSession initialized peer 1453985800070.2793
2016-01-28 13:56:40.079 ThaliTest[2793:7956412] jxcore: startBroadcasting: success
ok 54 Should be able to call startBroadcasting without error

2016-01-28 13:56:40.081 ThaliTest[2793:7956412] jxcore: stopBroadcasting,
,2016-01-28 13:56:40.081 ThaliTest[2793:7956412] THEMultipeerSession stopping peer
2016-01-28 13:56:40.084 ThaliTest[2793:7956412] multipeer session: stop timer
2016-01-28 13:56:40.084 ThaliTest[2793:7956412] jxcore: stopBroadcasting: success
ok 55 Shoul,d be able to call stopBroadcasting without error

2016-01-28 13:56:40.085 ThaliTest[2793:7956412] jxcore: startBroadcasting
,2016-01-28 13:56:40.093 ThaliTest[2793:7956412] server: starting 1453985800085.2793.EoGI9Q==
2016-01-28 13:56:40.096 ThaliTest[2793:7956412] multipeer session: start timer: 0x1672ff50
2016-01-28 13:56:40.096 ThaliTest[2793:7956412] THEMultipeerSession in,itialized peer 1453985800085.2793
2016-01-28 13:56:40.096 ThaliTest[2793:7956412] jxcore: startBroadcasting: success
ok 56 Should be able to call startBroadcasting without error

2016-01-28 13:56:40.097 ThaliTest[2793:7956412] jxcore: stopBroadcasting,
2016-01-28 13:56:40.097 ThaliTest[2793:7956412] THEMultipeerSession stopping peer
2016-01-28 13:56:40.097 ThaliTest[2793:7956412] multipeer session: stop timer
,2016-01-28 13:56:40.098 ThaliTest[2793:7956412] jxcore: stopBroadcasting: success
,ok 57 Should be able to call stopBroadcasting without error

,2016-01-28 13:56:40.106 ThaliTest[2793:7956412] jxcore: startBroadcasting
,2016-01-28 13:56:40.109 ThaliTest[2793:7956412] server: starting 1453985800106.2793.foJ38g==
,2016-01-28 13:56:40.112 ThaliTest[2793:7956412] multipeer session: start timer: 0x1672eeb0
,2016-01-28 13:56:40.113 ThaliTest[2793:7956412] THEMultipeerSession initialized peer 1453985800106.2793
,2016-01-28 13:56:40.114 ThaliTest[2793:7956412] jxcore: startBroadcasting: success
,ok 58 Should be able to call startBroadcasting without error

,2016-01-28 13:56:40.115 ThaliTest[2793:7956412] jxcore: stopBroadcasting
,2016-01-28 13:56:40.116 ThaliTest[2793:7956412] THEMultipeerSession stopping peer
,2016-01-28 13:56:40.116 ThaliTest[2793:7956412] multipeer session: stop timer
,2016-01-28 13:56:40.119 ThaliTest[2793:7956412] jxcore: stopBroadcasting: success
,ok 59 Should be able to call stopBroadcasting without error

,2016-01-28 13:56:40.121 ThaliTest[2793:7956412] jxcore: startBroadcasting
,2016-01-28 13:56:40.123 ThaliTest[2793:7956412] server: starting 1453985800121.2793./wzjYQ==
,2016-01-28 13:56:40.125 ThaliTest[2793:7956412] multipeer session: start timer: 0x166562b0
,2016-01-28 13:56:40.127 ThaliTest[2793:7956412] THEMultipeerSession initialized peer 1453985800121.2793
,2016-01-28 13:56:40.128 ThaliTest[2793:7956412] jxcore: startBroadcasting: success
,ok 60 Should be able to call startBroadcasting without error

,2016-01-28 13:56:40.130 ThaliTest[2793:7956412] jxcore: stopBroadcasting
,2016-01-28 13:56:40.131 ThaliTest[2793:7956412] THEMultipeerSession stopping peer
,2016-01-28 13:56:40.131 ThaliTest[2793:7956412] multipeer session: stop timer
,2016-01-28 13:56:40.132 ThaliTest[2793:7956412] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error

,2016-01-28 13:56:40.135 ThaliTest[2793:7956412] jxcore: startBroadcasting
,2016-01-28 13:56:40.138 ThaliTest[2793:7956412] server: starting 1453985800135.2793.wihaKg==
,2016-01-28 13:56:40.139 ThaliTest[2793:7956412] multipeer session: start timer: 0x16653550
,2016-01-28 13:56:40.141 ThaliTest[2793:7956412] THEMultipeerSession initialized peer 1453985800135.2793
,2016-01-28 13:56:40.142 ThaliTest[2793:7956412] jxcore: startBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error
,
,2016-01-28 13:56:40.146 ThaliTest[2793:7956412] jxcore: stopBroadcasting
,2016-01-28 13:56:40.150 ThaliTest[2793:7956412] THEMultipeerSession stopping peer
,2016-01-28 13:56:40.153 ThaliTest[2793:7956412] multipeer session: stop timer
,2016-01-28 13:56:40.156 ThaliTest[2793:7956412] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error

,2016-01-28 13:56:40.158 ThaliTest[2793:7956412] jxcore: startBroadcasting
,2016-01-28 13:56:40.160 ThaliTest[2793:7956412] server: starting 1453985800158.2793.Tjwqsw==
,2016-01-28 13:56:40.166 ThaliTest[2793:7956412] multipeer session: start timer: 0x16731870
,2016-01-28 13:56:40.167 ThaliTest[2793:7956412] THEMultipeerSession initialized peer 1453985800158.2793
,2016-01-28 13:56:40.167 ThaliTest[2793:7956412] jxcore: startBroadcasting: success
,ok 64 Should be able to call startBroadcasting without error

,2016-01-28 13:56:40.169 ThaliTest[2793:7956412] jxcore: stopBroadcasting
,2016-01-28 13:56:40.170 ThaliTest[2793:7956412] THEMultipeerSession stopping peer
,2016-01-28 13:56:40.170 ThaliTest[2793:7956412] multipeer session: stop timer
,2016-01-28 13:56:40.171 ThaliTest[2793:7956412] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error
,
,2016-01-28 13:56:40.175 ThaliTest[2793:7956412] jxcore: startBroadcasting
,2016-01-28 13:56:40.178 ThaliTest[2793:7956412] server: starting 1453985800175.2793.mEigdQ==
,2016-01-28 13:56:40.182 ThaliTest[2793:7956412] multipeer session: start timer: 0x167246d0
,2016-01-28 13:56:40.183 ThaliTest[2793:7956412] THEMultipeerSession initialized peer 1453985800175.2793
,2016-01-28 13:56:40.184 ThaliTest[2793:7956412] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error

,2016-01-28 13:56:40.186 ThaliTest[2793:7956412] jxcore: stopBroadcasting
,2016-01-28 13:56:40.186 ThaliTest[2793:7956412] THEMultipeerSession stopping peer
,2016-01-28 13:56:40.187 ThaliTest[2793:7956412] multipeer session: stop timer
,2016-01-28 13:56:40.188 ThaliTest[2793:7956412] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,2016-01-28 13:56:40.193 ThaliTest[2793:7956412] jxcore: startBroadcasting
,2016-01-28 13:56:40.195 ThaliTest[2793:7956412] server: starting 1453985800192.2793.JAQWVQ==
,2016-01-28 13:56:40.197 ThaliTest[2793:7956412] multipeer session: start timer: 0x16724af0
,2016-01-28 13:56:40.199 ThaliTest[2793:7956412] THEMultipeerSession initialized peer 1453985800192.2793
,2016-01-28 13:56:40.200 ThaliTest[2793:7956412] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-01-28 13:56:40.202 ThaliTest[2793:7956412] jxcore: stopBroadcasting
,2016-01-28 13:56:40.202 ThaliTest[2793:7956412] THEMultipeerSession stopping peer
,2016-01-28 13:56:40.203 ThaliTest[2793:7956412] multipeer session: stop timer
,2016-01-28 13:56:40.205 ThaliTest[2793:7956412] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-01-28 13:56:40.207 ThaliTest[2793:7956412] jxcore: startBroadcasting
,2016-01-28 13:56:40.209 ThaliTest[2793:7956412] server: starting 1453985800207.2793.CRFUcg==
,2016-01-28 13:56:40.211 ThaliTest[2793:7956412] multipeer session: start timer: 0x16724ad0
,2016-01-28 13:56:40.213 ThaliTest[2793:7956412] THEMultipeerSession initialized peer 1453985800207.2793
,2016-01-28 13:56:40.214 ThaliTest[2793:7956412] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-01-28 13:56:40.215 ThaliTest[2793:7956412] jxcore: stopBroadcasting
,2016-01-28 13:56:40.216 ThaliTest[2793:7956412] THEMultipeerSession stopping peer
,2016-01-28 13:56:40.217 ThaliTest[2793:7956412] multipeer session: stop timer
,2016-01-28 13:56:40.217 ThaliTest[2793:7956412] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

,2016-01-28 13:56:40.221 ThaliTest[2793:7956412] jxcore: startBroadcasting
,2016-01-28 13:56:40.223 ThaliTest[2793:7956412] server: starting 1453985800221.2793.lkLMVg==
,2016-01-28 13:56:40.225 ThaliTest[2793:7956412] multipeer session: start timer: 0x16725c50
,2016-01-28 13:56:40.228 ThaliTest[2793:7956412] THEMultipeerSession initialized peer 1453985800221.2793
,2016-01-28 13:56:40.229 ThaliTest[2793:7956412] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-01-28 13:56:40.232 ThaliTest[2793:7956412] jxcore: stopBroadcasting
,2016-01-28 13:56:40.233 ThaliTest[2793:7956412] THEMultipeerSession stopping peer
,2016-01-28 13:56:40.234 ThaliTest[2793:7956412] multipeer session: stop timer
,2016-01-28 13:56:40.236 ThaliTest[2793:7956412] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-28 13:56:40.471 ThaliTest[2793:7956412] jxcore: startBroadcasting
,2016-01-28 13:56:40.474 ThaliTest[2793:7956412] server: starting 1453985800471.2793.3V81wA==
,2016-01-28 13:56:40.476 ThaliTest[2793:7956412] multipeer session: start timer: 0x1664f0c0
,2016-01-28 13:56:40.481 ThaliTest[2793:7956412] THEMultipeerSession initialized peer 1453985800471.2793
,2016-01-28 13:56:40.482 ThaliTest[2793:7956412] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error

,2016-01-28 13:56:40.485 ThaliTest[2793:7956412] jxcore: startBroadcasting
,2016-01-28 13:56:40.486 ThaliTest[2793:7956412] jxcore: startBroadcasting: failure
,ok 75 Cannot call startBroadcasting twice

,2016-01-28 13:56:40.489 ThaliTest[2793:7956412] jxcore: stopBroadcasting
,2016-01-28 13:56:40.490 ThaliTest[2793:7956412] THEMultipeerSession stopping peer
,2016-01-28 13:56:40.491 ThaliTest[2793:7956412] multipeer session: stop timer
,2016-01-28 13:56:40.494 ThaliTest[2793:7956412] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-28 13:56:41.386 ThaliTest[2793:7956412] jxcore: startBroadcasting
,2016-01-28 13:56:41.388 ThaliTest[2793:7956412] server: starting 1453985801386.2793.lUDEJw==
2016-01-28 13:56:41.389 ThaliTest[2793:7956412] multipeer session: start timer: 0x1663fc70
2016-01-28 13:56:41.389 ThaliTest[2793:7956412] THEMultipeerSession initialized peer 1453985801386.2793
2016-01-28 13:56:41.389 ThaliTest[2793:7956412] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

,2016-01-28 13:56:41.390 ThaliTest[2793:7956412] jxcore: connect foobar
2016-01-28 13:56:41.391 ThaliTest[2793:7956412] client: unknown peer foobar
2016-01-28 13:56:41.391 ThaliTest[2793:7956412] jxcore: connect: fail: Unknown peer
ok 78 Should not connect to a bad peer

2016-01-28 13:56:41.393 ThaliTest[2793:7956412] jxcore: stopBroadcasting
2016-01-28 13:56:41.393 ThaliTest[2793:7956412] THEMultipeerSession stopping peer
2016-01-28 13:56:41.393 ThaliTest[2793:7956412] multipeer session: stop timer
2016-01-28 13:56:41.393 ThaliTest[2793:7956412] jxcore: stopBroadcasting: success
ok 79 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-28 13:56:41.926 ThaliTest[2793:7956412] jxcore: startBroadcasting
,2016-01-28 13:56:41.928 ThaliTest[2793:7956412] server: starting 1453985801926.2793.EGQzaA==
2016-01-28 13:56:41.929 ThaliTest[2793:7956412] multipeer session: start timer: 0x15e4bb50
2016-01-28 13:56:41.929 ThaliTest[2793:7956412] THEMultipeerSession initialized peer 1453985801926.2793
2016-01-28 13:56:41.929 ThaliTest[2793:7956412] jxcore: startBroadcasting: success
ok 80 Should be able to call startBroadcasting without error

2016-01-28 13:56:41.930 ThaliTest[2793:7956412] jxcore: disconnect
2016-01-28 13:56:41.930 ThaliTest[2793:7956412] jxcore: disconnect: fail
,ok 81 Disconnect should fail to a non-existant peer 

2016-01-28 13:56:41.932 ThaliTest[2793:7956412] jxcore: stopBroadcasting
2016-01-28 13:56:41.932 ThaliTest[2793:7956412] THEMultipeerSession stopping peer
2016-01-28 13:56:41.932 ThaliTest[2793:7956,412] multipeer session: stop timer
2016-01-28 13:56:41.934 ThaliTest[2793:7956412] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-28 13:56:43.139 ThaliTest[2793:7956412] jxcore: startBroadcasting
,2016-01-28 13:56:43.141 ThaliTest[2793:7956412] server: starting 1453985803139.2793.GwKgxQ==
2016-01-28 13:56:43.141 ThaliTest[2793:7956412] multipeer session: start timer: 0x16644f10
2016-01-28 13:56:43.141 ThaliTest[2793:7956412] THEMultipeerSession initialized peer 1453985803139.2793
2016-01-28 13:56:43.141 ThaliTest[2793:7956412] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-28 13:56:43.953 ThaliTest[2793:7956167] client: found peer: 1453985806000.4112.rKeQtQ==
,2016-01-28 13:56:43.956 ThaliTest[2793:7956412] jxcore: connect 1453985806000.4112.rKeQtQ==
2016-01-28 13:56:43.956 ThaliTest[2793:7956412] client session: connect
2016-01-28 13:56:43.956 ThaliTest[2793:7956412] client session: stateChange:0->1 145398580,6000.4112.rKeQtQ==
,2016-01-28 13:56:44.368 ThaliTest[2793:7956167] multipeer session: reset timer
2016-01-28 13:56:44.368 ThaliTest[2793:7956167] multipeer session: stop timer
2016-01-28 13:56:44.369 ThaliTest[2793:7956167] multipeer session: start timer: 0x16644f10
2016-01-28 13:56:44.369 ThaliTest[2793:7956167] server session: connect
2016-01-28 13:56:44.369 ThaliTest[2793:7956167] server session: stateChange:0->1 1453985806000.4112
,2016-01-28 13:56:44.373 ThaliTest[2793:7956167] server: accepting invitation 1453985806000.4112
,2016-01-28 13:56:46.885 ThaliTest[2793:7957402] client session: connected
2016-01-28 13:56:46.885 ThaliTest[2793:7957402] client session: stateChange:1->2 1453985806000.4112.rKeQtQ==
,2016-01-28 13:56:46.894 ThaliTest[2793:7957401] client session: fireConnectCallback: 1453985806000.4112.rKeQtQ==
2016-01-28 13:56:46.895 ThaliTest[2793:7957401] jxcore: connect: success
,ok 84 Should be able to connect without error

,ok 85 Port should be within range

,2016-01-28 13:56:46.897 ThaliTest[2793:7956412] jxcore: disconnect
2016-01-28 13:56:46.897 ThaliTest[2793:7956412] client session: disconnectFromPeer: 1453985806000.4112.rKeQtQ==
2016-01-28 13:56:46.897 ThaliTest[2793:7956412] client session: disconnect
2016-01-28 13:56:46.897 ThaliTest[2793:7956412] client session: stateChange:2->0 1453985806000.4112.rKeQtQ==
,2016-01-28 13:56:46.902 ThaliTest[2793:7956412] jxcore: disconnect: success
ok 86 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,2016-01-28 13:56:46.915 ThaliTest[2793:7957402] server session: connected
2016-01-28 13:56:46.915 ThaliTest[2793:7957402] server session: stateChange:1->2 1453985806000.4112
,# setup

,2016-01-28 13:56:46.954 ThaliTest[2793:7957397] server session: not connected 1453985806000.4112
,2016-01-28 13:56:46.956 ThaliTest[2793:7956167] server relay: socket disconnected
2016-01-28 13:56:46.956 ThaliTest[2793:7956167] server relay: 0x14647260 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,calling stopBroadcasting

,2016-01-28 13:56:47.332 ThaliTest[2793:7956412] jxcore: stopBroadcasting
2016-01-28 13:56:47.332 ThaliTest[2793:7956412] THEMultipeerSession stopping peer
2016-01-28 13:56:47.333 ThaliTest[2793:7956412] multipeer session: stop timer
2016-01-28 13:56:47.,333 ThaliTest[2793:7956412] server session: disconnect
2016-01-28 13:56:47.333 ThaliTest[2793:7956412] server session: stateChange:2->0 1453985806000.4112
2016-01-28 13:56:47.333 ThaliTest[2793:7956412] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-28 13:56:47.853 ThaliTest[2793:7956412] jxcore: startBroadcasting
,2016-01-28 13:56:47.855 ThaliTest[2793:7956412] server: starting 1453985807853.2793.U9eTAQ==
,2016-01-28 13:56:47.855 ThaliTest[2793:7956412] multipeer session: start timer: 0x16604cd0
,2016-01-28 13:56:47.856 ThaliTest[2793:7956412] THEMultipeerSession initialized peer 1453985807853.2793
2016-01-28 13:56:47.856 ThaliTest[2793:7956412] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-01-28 13:56:48.627 ThaliTest[2793:7956167] client: found peer: 1453985806000.4112.rKeQtQ==
2016-01-28 13:56:48.628 ThaliTest[2793:7956412] jxcore: connect 1453985806000.4112.rKeQtQ==
2016-01-28 13:56:48.628 ThaliTest[2793:7956412] client session: connect
2016-01-28 13:56:48.628 ThaliTest[2793:7956412] client session: stateChange:0->1 1453985806000.4112.rKeQtQ==
,2016-01-28 13:56:49.031 ThaliTest[2793:7956167] client: lost peer: 1453985806000.4112.rKeQtQ==
2016-01-28 13:56:49.031 ThaliTest[2793:7956167] client session: onPeerLost: 1453985806000.4112.rKeQtQ==
2016-01-28 13:56:49.031 ThaliTest[2793:7956167] client session: onLinkFailure: 1453985806000.4112.rKeQtQ==
2016-01-28 13:56:49.031 ThaliTest[2793:7956167] client session: disconnect
2016-01-28 13:56:49.031 ThaliTest[2793:7956167] client session: stateChange:1->0 1453985806000.4112.rKeQtQ==
2016-01-28 13:56:49.032 ThaliTest[2793:7956167] client session: fireConnectCallback: 1453985806000.4112.rKeQtQ==
,2016-01-28 13:56:49.032 ThaliTest[2793:7956167] jxcore: connect: fail: Peer disconnected
,2016-01-28 13:56:49.086 ThaliTest[2793:7956167] client: found peer: 1453985810907.4112.shXuLA==
2016-01-28 13:56:49.086 ThaliTest[2793:7956412] jxcore: connect 1453985810907.4112.shXuLA==
2016-01-28 13:56:49.092 ThaliTest[2793:7956412] client session: connect
2016-01-28 13:56:49.092 ThaliTest[2793:7956412] client session: stateChange:0->1 1453985810907.4112.shXuLA==
,2016-01-28 13:56:49.504 ThaliTest[2793:7956167] multipeer session: reset timer
2016-01-28 13:56:49.504 ThaliTest[2793:7956167] multipeer session: stop timer
2016-01-28 13:56:49.505 ThaliTest[2793:7956167] multipeer session: start timer: 0x16604cd0
2016-01-28 13:56:49.505 ThaliTest[2793:7956167] server session: connect
2016-01-28 13:56:49.505 ThaliTest[2793:7956167] server session: stateChange:0->1 1453985810907.4112
2016-01-28 13:56:49.510 ThaliTest[2793:7956167] server: accepting invitation 1453985810907.4112
,2016-01-28 13:56:50.045 ThaliTest[2793:7956412] jxcore: connect 1453985806000.4112.rKeQtQ==
2016-01-28 13:56:50.046 ThaliTest[2793:7956412] client: connect: unreachable 1453985806000.4112.rKeQtQ==
2016-01-28 13:56:50.046 ThaliTest[2793:7956412] jxcore: connect: fail: Peer unreachable
,2016-01-28 13:56:52.131 ThaliTest[2793:7957395] client session: connected
2016-01-28 13:56:52.131 ThaliTest[2793:7957395] client session: stateChange:1->2 1453985810907.4112.shXuLA==
,2016-01-28 13:56:52.136 ThaliTest[2793:7957401] client session: fireConnectCallback: 1453985810907.4112.shXuLA==
2016-01-28 13:56:52.136 ThaliTest[2793:7957401] jxcore: connect: success
ok 88 Should be able to connect without error

,ok 89 Port should be within range

,2016-01-28 13:56:52.138 ThaliTest[2793:7956412] jxcore: connect 1453985810907.4112.shXuLA==
2016-01-28 13:56:52.138 ThaliTest[2793:7956412] client: already connect(ing/ed) to 1453985810907.4112.shXuLA==
2016-01-28 13:56:52.138 ThaliTest[2793:7956412] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

,2016-01-28 13:56:52.140 ThaliTest[2793:7956412] jxcore: disconnect
2016-01-28 13:56:52.140 ThaliTest[2793:7956412] client session: disconnectFromPeer: 1453985810907.4112.shXuLA==
2016-01-28 13:56:52.140 ThaliTest[2793:7956412] client session: disconnect,
2016-01-28 13:56:52.140 ThaliTest[2793:7956412] client session: stateChange:2->0 1453985810907.4112.shXuLA==
,2016-01-28 13:56:52.195 ThaliTest[2793:7957434] server session: connected
2016-01-28 13:56:52.195 ThaliTest[2793:7957434] server session: stateChange:1->2 1453985810907.4112
,2016-01-28 13:56:52.198 ThaliTest[2793:7956167] server relay: socket disconnected
2016-01-28 13:56:52.199 ThaliTest[2793:7956167] server relay: 0x15e192a0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-28 13:56:52.203 ThaliTest[2793:7956412] jxcore: disconnect: success
ok 91 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-28 13:56:52.256 ThaliTest[2793:7957395] server session: not connected 1453985810907.4112
,calling stopBroadcasting

,2016-01-28 13:56:52.532 ThaliTest[2793:7956412] jxcore: stopBroadcasting
2016-01-28 13:56:52.532 ThaliTest[2793:7956412] THEMultipeerSession stopping peer
2016-01-28 13:56:52.532 ThaliTest[2793:7956412] multipeer session: stop timer
2016-01-28 13:56:52.,532 ThaliTest[2793:7956412] server session: disconnect
2016-01-28 13:56:52.533 ThaliTest[2793:7956412] server session: stateChange:2->0 1453985810907.4112
2016-01-28 13:56:52.533 ThaliTest[2793:7956412] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-28 13:56:53.101 ThaliTest[2793:7956412] jxcore: startBroadcasting
,2016-01-28 13:56:53.103 ThaliTest[2793:7956412] server: starting 1453985813100.2793.qdPuCw==
2016-01-28 13:56:53.104 ThaliTest[2793:7956412] multipeer session: start timer: 0x1664b1f0
2016-01-28 13:56:53.104 ThaliTest[2793:7956412] THEMultipeerSession initialized peer 1453985813100.2793
,2016-01-28 13:56:53.107 ThaliTest[2793:7956412] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-01-28 13:56:54.337 ThaliTest[2793:7956167] client: found peer: 1453985816152.4112.vSyajA==
2016-01-28 13:56:54.338 ThaliTest[2793:7956412] jxcore: connect 1453985816152.4112.vSyajA==
2016-01-28 13:56:54.338 ThaliTest[2793:7956412] client session: co,nnect
2016-01-28 13:56:54.338 ThaliTest[2793:7956412] client session: stateChange:0->1 1453985816152.4112.vSyajA==
,2016-01-28 13:56:54.762 ThaliTest[2793:7956167] multipeer session: reset timer
2016-01-28 13:56:54.762 ThaliTest[2793:7956167] multipeer session: stop timer
2016-01-28 13:56:54.762 ThaliTest[2793:7956167] multipeer session: start timer: 0x1664b1f0
2016-,01-28 13:56:54.762 ThaliTest[2793:7956167] server session: connect
2016-01-28 13:56:54.762 ThaliTest[2793:7956167] server session: stateChange:0->1 1453985816152.4112
2016-01-28 13:56:54.768 ThaliTest[2793:7956167] server: accepting invitation 1453985816152.4112
,2016-01-28 13:56:57.507 ThaliTest[2793:7957400] client session: connected
2016-01-28 13:56:57.507 ThaliTest[2793:7957400] client session: stateChange:1->2 1453985816152.4112.vSyajA==
2016-01-28 13:56:57.508 ThaliTest[2793:7957397] server session: connected
,2016-01-28 13:56:57.508 ThaliTest[2793:7957397] server session: stateChange:1->2 1453985816152.4112
,2016-01-28 13:56:57.511 ThaliTest[2793:7957400] client session: fireConnectCallback: 1453985816152.4112.vSyajA==
2016-01-28 13:56:57.511 ThaliTest[2793:7957400] jxcore: connect: success
ok 93 Should be able to connect without error

ok 94 Port should b,e within range

2016-01-28 13:56:57.513 ThaliTest[2793:7956167] server relay: socket disconnected
2016-01-28 13:56:57.513 ThaliTest[2793:7956167] server relay: 0x16602eb0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refuse,d" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
2016-01-28 13:56:57.513 ThaliTest[2793:7956412] jxcore: disconnect
,2016-01-28 13:56:57.513 ThaliTest[2793:7956412] client session: disconnectFromPeer: 1453985816152.4112.vSyajA==
2016-01-28 13:56:57.513 ThaliTest[2793:7956412] client session: disconnect
2016-01-28 13:56:57.513 ThaliTest[2793:7956412] client session: sta,teChange:2->0 1453985816152.4112.vSyajA==
,2016-01-28 13:56:57.576 ThaliTest[2793:7956412] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error

,2016-01-28 13:56:57.578 ThaliTest[2793:7956412] jxcore: disconnect
2016-01-28 13:56:57.578 ThaliTest[2793:7956412] jxcore: disconnect: fail
,ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-28 13:56:57.596 ThaliTest[2793:7957401] server session: not connected 1453985816152.4112
,calling stopBroadcasting

,2016-01-28 13:56:58.866 ThaliTest[2793:7956412] jxcore: stopBroadcasting
2016-01-28 13:56:58.866 ThaliTest[2793:7956412] THEMultipeerSession stopping peer
2016-01-28 13:56:58.866 ThaliTest[2793:7956412] multipeer session: stop timer
2016-01-28 13:56:58.,867 ThaliTest[2793:7956412] server session: disconnect
2016-01-28 13:56:58.867 ThaliTest[2793:7956412] server session: stateChange:2->0 1453985816152.4112
2016-01-28 13:56:58.867 ThaliTest[2793:7956412] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 65353

,2016-01-28 13:56:59.496 ThaliTest[2793:7956412] jxcore: startBroadcasting
,2016-01-28 13:56:59.499 ThaliTest[2793:7956412] server: starting 1453985819496.2793.cX8SPA==
,2016-01-28 13:56:59.501 ThaliTest[2793:7956412] multipeer session: start timer: 0x16638e90
,2016-01-28 13:56:59.505 ThaliTest[2793:7956412] THEMultipeerSession initialized peer 1453985819496.2793
,2016-01-28 13:56:59.506 ThaliTest[2793:7956412] jxcore: startBroadcasting: success
,ok 97 Should be able to call startBroadcasting without error

,2016-01-28 13:57:00.132 ThaliTest[2793:7956167] client: found peer: 1453985822406.4112.ZpquvA==
2016-01-28 13:57:00.133 ThaliTest[2793:7956412] jxcore: connect 1453985822406.4112.ZpquvA==
,2016-01-28 13:57:00.133 ThaliTest[2793:7956412] client session: connect
2016-01-28 13:57:00.133 ThaliTest[2793:7956412] client session: stateChange:0->1 1453985822406.4112.ZpquvA==
,2016-01-28 13:57:01.099 ThaliTest[2793:7956167] multipeer session: reset timer
2016-01-28 13:57:01.099 ThaliTest[2793:7956167] multipeer session: stop timer
2016-01-28 13:57:01.099 ThaliTest[2793:7956167] multipeer session: start timer: 0x16638e90
2016-,01-28 13:57:01.099 ThaliTest[2793:7956167] server session: connect
2016-01-28 13:57:01.099 ThaliTest[2793:7956167] server session: stateChange:0->1 1453985822406.4112
2016-01-28 13:57:01.103 ThaliTest[2793:7956167] server: accepting invitation 1453985822406.4112
,2016-01-28 13:57:03.036 ThaliTest[2793:7957395] client session: connected
2016-01-28 13:57:03.036 ThaliTest[2793:7957395] client session: stateChange:1->2 1453985822406.4112.ZpquvA==
2016-01-28 13:57:03.038 ThaliTest[2793:7957395] client session: fireCon,nectCallback: 1453985822406.4112.ZpquvA==
2016-01-28 13:57:03.038 ThaliTest[2793:7957395] jxcore: connect: success
ok 98 Should be able to connect without error

ok 99 Port should be within range

,2016-01-28 13:57:03.041 ThaliTest[2793:7956167] client: relay established
2016-01-28 13:57:03.041 ThaliTest[2793:7956167] client: new accepted socket: 0x166049b0
,data in 14235

,data in 25185

,data in 26280

,data in 36135

,data in 54750

,data in 60225

,data in 79935

,data in 84315

,data in 102930

,data in 113880

,data in 116070

,data in 127020

,data in 131072

,ok 100 the test messages should be equal

,2016-01-28 13:57:03.513 ThaliTest[2793:7956412] jxcore: disconnect
2016-01-28 13:57:03.513 ThaliTest[2793:7956412] client session: disconnectFromPeer: 1453985822406.4112.ZpquvA==
2016-01-28 13:57:03.513 ThaliTest[2793:7956412] client session: disconnect,
2016-01-28 13:57:03.514 ThaliTest[2793:7956412] client session: stateChange:2->0 1453985822406.4112.ZpquvA==
,2016-01-28 13:57:03.519 ThaliTest[2793:7956412] jxcore: disconnect: success
,ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-28 13:57:03.601 ThaliTest[2793:7957401] server session: connected
2016-01-28 13:57:03.602 ThaliTest[2793:7957401] server session: stateChange:1->2 1453985822406.4112
,2016-01-28 13:57:03.607 ThaliTest[2793:7956167] server relay: connected (to port: 65353)
,2016-01-28 13:57:04.280 ThaliTest[2793:7957400] server session: not connected 1453985822406.4112
,calling stopBroadcasting

2016-01-28 13:57:04.581 ThaliTest[2793:7956412] jxcore: stopBroadcasting
2016-01-28 13:57:04.582 ThaliTest[2793:7956412] THEMultipeerSession stopping peer
2016-01-28 13:57:04.582 ThaliTest[2793:7956412] multipeer session: stop timer
2016-01-28 13:57:04.582 ThaliTest[2793:7956412] server session: disconnect
2016-01-28 13:57:04.582 ThaliTest[2793:7956412] server session: stateChange:2->0 1453985822406.4112
,2016-01-28 13:57:04.586 ThaliTest[2793:7956412] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 65359

2016-01-28 13:57:05.107 ThaliTest[2793:7956412] jxcore: startBroadcasting
,2016-01-28 13:57:05.110 ThaliTest[2793:7956412] server: starting 1453985825107.2793.GJZaDQ==
2016-01-28 13:57:05.110 ThaliTest[2793:7956412] multipeer session: start timer: 0x15c03480
2016-01-28 13:57:05.110 ThaliTest[2793:7956412] THEMultipeerSession initialized peer 1453985825107.2793
2016-01-28 13:57:05.111 ThaliTest[2793:7956412] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-01-28 13:57:06.324 ThaliTest[2793:7956167] multipeer session: reset timer
2016-01-28 13:57:06.324 ThaliTest[2793:7956167] multipeer session: stop timer
2016-01-28 13:57:06.324 ThaliTest[2793:7956167] multipeer session: start timer: 0x15c03480
2016-01-28 13:57:06.324 ThaliTest[2793:7956167] server session: connect
2016-01-28 13:57:06.325 ThaliTest[2793:7956167] server session: stateChange:0->1 1453985828139.4112
,2016-01-28 13:57:06.329 ThaliTest[2793:7956167] server: accepting invitation 1453985828139.4112
,2016-01-28 13:57:06.381 ThaliTest[2793:7956167] client: found peer: 1453985828139.4112.qquF1Q==
[{"peerIdentifier":"1453985828139.4112.qquF1Q==","peerName":"(null)","peerAvailable":true}]

2016-01-28 13:57:06.382 ThaliTest[2793:7956412] jxcore: connect 1453985828139.4112.qquF1Q==
2016-01-28 13:57:06.382 ThaliTest[2793:7956412] client session: connect
2016-01-28 13:57:06.382 ThaliTest[2793:7956412] client session: stateChange:0->1 1453985828139.4112.qquF1Q==
,2016-01-28 13:57:08.777 ThaliTest[2793:7957401] client session: connected
2016-01-28 13:57:08.777 ThaliTest[2793:7957401] client session: stateChange:1->2 1453985828139.4112.qquF1Q==
,2016-01-28 13:57:08.781 ThaliTest[2793:7957395] client session: fireConnectCallback: 1453985828139.4112.qquF1Q==
,2016-01-28 13:57:08.782 ThaliTest[2793:7957395] jxcore: connect: success
,2016-01-28 13:57:08.785 ThaliTest[2793:7957401] server session: connected
2016-01-28 13:57:08.785 ThaliTest[2793:7957401] server session: stateChange:1->2 1453985828139.4112
ok 103 Should be able to connect without error

,ok 104 Port should be within range

,ok 105 First connect should succeed

,2016-01-28 13:57:08.803 ThaliTest[2793:7956167] client: relay established
2016-01-28 13:57:08.803 ThaliTest[2793:7956167] client: new accepted socket: 0x15d6f530
,2016-01-28 13:57:08.804 ThaliTest[2793:7956167] server relay: connected (to port: 65359)
,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-01-28 13:57:08.922 ThaliTest[2793:7956167] client: socket closed
2016-01-28 13:57:08.923 ThaliTest[2793:7956167] client relay: socket disconnected
2016-01-28 13:57:08.923 ThaliTest[2793:7956167] client relay: 0x15d6f530 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-28 13:57:08.923 ThaliTest[2793:7956167] client session: socket closed: 1453985828139.4112.qquF1Q==
2016-01-28 ,13:57:08.923 ThaliTest[2793:7956167] client session: onLinkFailure: 1453985828139.4112.qquF1Q==
2016-01-28 13:57:08.923 ThaliTest[2793:7956167] client session: disconnect
2016-01-28 13:57:08.923 ThaliTest[2793:7956167] client session: stateChange:2->0 14,53985828139.4112.qquF1Q==
,2016-01-28 13:57:08.986 ThaliTest[2793:7956167] client session: fireConnectionErrorEvent: 1453985828139.4112.qquF1Q==
,2016-01-28 13:57:08.987 ThaliTest[2793:7956412] jxcore: connect 1453985828139.4112.qquF1Q==
2016-01-28 13:57:08.988 ThaliTest[2793:7956412] client session: connect
,2016-01-28 13:57:08.988 ThaliTest[2793:7956412] client session: stateChange:0->1 1453985828139.4112.qquF1Q==
,2016-01-28 13:57:09.041 ThaliTest[2793:7957402] server session: not connected 1453985828139.4112
,2016-01-28 13:57:09.166 ThaliTest[2793:7956167] multipeer session: reset timer
2016-01-28 13:57:09.167 ThaliTest[2793:7956167] multipeer session: stop timer
2016-01-28 13:57:09.167 ThaliTest[2793:7956167] multipeer session: start timer: 0x15c03480
2016-01-28 13:57:09.168 ThaliTest[2793:7956167] server: disconnecting to refresh session (1453985828139.4112)
2016-01-28 13:57:09.168 ThaliTest[2793:7956167] server session: disconnect
2016-01-28 13:57:09.168 ThaliTest[2793:7956167] server session: stateChang,e:2->0 1453985828139.4112
,2016-01-28 13:57:09.173 ThaliTest[2793:7956167] server session: connect
2016-01-28 13:57:09.173 ThaliTest[2793:7956167] server session: stateChange:0->1 1453985828139.4112
2016-01-28 13:57:09.178 ThaliTest[2793:7956167] server: accepting invitation 1453985828139.4112
,2016-01-28 13:57:11.657 ThaliTest[2793:7957395] client session: connected
2016-01-28 13:57:11.657 ThaliTest[2793:7957395] client session: stateChange:1->2 1453985828139.4112.qquF1Q==
,2016-01-28 13:57:11.662 ThaliTest[2793:7957395] client session: fireConnectCallback: 1453985828139.4112.qquF1Q==
,2016-01-28 13:57:11.666 ThaliTest[2793:7957395] jxcore: connect: success
,ok 108 Should be able to connect without error

ok 109 Port should be within range

ok 110 Second connect should succeed

,2016-01-28 13:57:11.734 ThaliTest[2793:7957400] server session: connected
2016-01-28 13:57:11.734 ThaliTest[2793:7957400] server session: stateChange:1->2 1453985828139.4112
,2016-01-28 13:57:11.743 ThaliTest[2793:7956167] server relay: connected (to port: 65359)
,2016-01-28 13:57:11.825 ThaliTest[2793:7956167] client: relay established
2016-01-28 13:57:11.825 ThaliTest[2793:7956167] client: new accepted socket: 0x166472d0
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-01-28 13:57:11.883 ThaliTest[2793:7956167] client: socket closed
2016-01-28 13:57:11.883 ThaliTest[2793:7956167] client relay: socket disconnected
2016-01-28 13:57:11.883 ThaliTest[2793:7956167] client relay: 0x166472d0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-28 13:57:11.884 ThaliTest[2793:7956167] client session: socket closed: 1453985828139.4112.qquF1Q==
2016-01-28 ,13:57:11.884 ThaliTest[2793:7956167] client session: onLinkFailure: 1453985828139.4112.qquF1Q==
2016-01-28 13:57:11.884 ThaliTest[2793:7956167] client session: disconnect
,2016-01-28 13:57:11.884 ThaliTest[2793:7956167] client session: stateChange:2->0 1453985828139.4112.qquF1Q==
,2016-01-28 13:57:11.887 ThaliTest[2793:7956167] client session: fireConnectionErrorEvent: 1453985828139.4112.qquF1Q==
,2016-01-28 13:57:11.913 ThaliTest[2793:7957395] server session: not connected 1453985828139.4112
,calling stopBroadcasting

,2016-01-28 13:57:11.918 ThaliTest[2793:7956412] jxcore: stopBroadcasting
,2016-01-28 13:57:11.918 ThaliTest[2793:7956412] THEMultipeerSession stopping peer
,2016-01-28 13:57:11.919 ThaliTest[2793:7956412] multipeer session: stop timer
,2016-01-28 13:57:11.919 ThaliTest[2793:7956412] server session: disconnect
,2016-01-28 13:57:11.929 ThaliTest[2793:7956412] server session: stateChange:2->0 1453985828139.4112
,2016-01-28 13:57:12.259 ThaliTest[2793:7956412] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/C33C27D9-B0ED-4082-80A5-5B6E9DF1B263/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-01-28 13:57:12.587 ThaliTest[2793:7956412] jxcore: startBroadcasting
,2016-01-28 13:57:12.589 ThaliTest[2793:7956412] server: starting XA-z6oLuveEaSVM6G2JelA.1hhDBA==
,2016-01-28 13:57:12.590 ThaliTest[2793:7956412] multipeer session: start timer: 0x15c65170
,2016-01-28 13:57:12.597 ThaliTest[2793:7956412] THEMultipeerSession initialized peer XA-z6oLuveEaSVM6G2JelA
,2016-01-28 13:57:12.599 ThaliTest[2793:7956412] jxcore: startBroadcasting: success
,ok 114 started event should occur in right order

,Now in TRM stop

State of this._isStarted: true

,ok 115 stopping event should occur in right order

,About to call stopBroadcasting
,
,2016-01-28 13:57:12.602 ThaliTest[2793:7956412] jxcore: stopBroadcasting
,2016-01-28 13:57:12.603 ThaliTest[2793:7956412] THEMultipeerSession stopping peer
,2016-01-28 13:57:12.603 ThaliTest[2793:7956412] multipeer session: stop timer
,2016-01-28 13:57:12.606 ThaliTest[2793:7956412] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,ok 116 stopped event should occur in right order

,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/C33C27D9-B0ED-4082-80A5-5B6E9DF1B263/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-28 13:57:13.144 ThaliTest[2793:7956412] jxcore: startBroadcasting
,2016-01-28 13:57:13.146 ThaliTest[2793:7956412] server: starting XA-z6oLuveEaSVM6G2JelA.qgZeww==
,2016-01-28 13:57:13.150 ThaliTest[2793:7956412] multipeer session: start timer: 0x16652ff0
,2016-01-28 13:57:13.153 ThaliTest[2793:7956412] THEMultipeerSession initialized peer XA-z6oLuveEaSVM6G2JelA
,2016-01-28 13:57:13.154 ThaliTest[2793:7956412] jxcore: startBroadcasting: success
,ok 117 getDeviceIdentity should not return an error

,ok 118 deviceName should not be null

,Now in TRM stop
,
State of this._isStarted: true

,About to call stopBroadcasting
,
,2016-01-28 13:57:13.157 ThaliTest[2793:7956412] jxcore: stopBroadcasting
,2016-01-28 13:57:13.158 ThaliTest[2793:7956412] THEMultipeerSession stopping peer
,2016-01-28 13:57:13.158 ThaliTest[2793:7956412] multipeer session: stop timer
,2016-01-28 13:57:13.161 ThaliTest[2793:7956412] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/C33C27D9-B0ED-4082-80A5-5B6E9DF1B263/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-28 13:57:16.124 ThaliTest[2793:7956412] jxcore: startBroadcasting
,2016-01-28 13:57:16.127 ThaliTest[2793:7956412] server: starting XA-z6oLuveEaSVM6G2JelA.E1pQ0g==
,2016-01-28 13:57:16.128 ThaliTest[2793:7956412] multipeer session: start timer: 0x1792b7b0
,2016-01-28 13:57:16.132 ThaliTest[2793:7956412] THEMultipeerSession initialized peer XA-z6oLuveEaSVM6G2JelA
,2016-01-28 13:57:16.133 ThaliTest[2793:7956412] jxcore: startBroadcasting: success
,ok 119 getDeviceIdentity should not return an error
,
,ok 120 deviceName should not be null

,2016-01-28 13:57:16.833 ThaliTest[2793:7956167] client: found peer: 8vk05J_k2lTBa3VjxkGkbg.i3zmOg==
,2016-01-28 13:57:21.748 ThaliTest[2793:7956412] jxcore: connect 8vk05J_k2lTBa3VjxkGkbg.i3zmOg==
,2016-01-28 13:57:21.750 ThaliTest[2793:7956412] client session: connect
,2016-01-28 13:57:21.750 ThaliTest[2793:7956412] client session: stateChange:0->1 8vk05J_k2lTBa3VjxkGkbg.i3zmOg==
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-01-28 13:57:22.012 ThaliTest[2793:7956167] multipeer session: reset timer
2016-01-28 13:57:22.012 ThaliTest[2793:7956167] multipeer session: stop timer
2016-01-28 13:57:22.012 ThaliTest[2793:7956167] multipeer session: start timer: 0x1792b7b0
2016-,01-28 13:57:22.012 ThaliTest[2793:7956167] server session: connect
2016-01-28 13:57:22.012 ThaliTest[2793:7956167] server session: stateChange:0->1 8vk05J_k2lTBa3VjxkGkbg
,2016-01-28 13:57:22.018 ThaliTest[2793:7956167] server: accepting invitation 8vk05J_k2lTBa3VjxkGkbg
,2016-01-28 13:57:24.629 ThaliTest[2793:7957397] client session: connected
2016-01-28 13:57:24.631 ThaliTest[2793:7957397] client session: stateChange:1->2 8vk05J_k2lTBa3VjxkGkbg.i3zmOg==
,2016-01-28 13:57:24.637 ThaliTest[2793:7957400] client session: fireConnectCallback: 8vk05J_k2lTBa3VjxkGkbg.i3zmOg==
2016-01-28 13:57:24.640 ThaliTest[2793:7957400] jxcore: connect: success
,2016-01-28 13:57:24.643 ThaliTest[2793:7957400] server session: connected
2016-01-28 13:57:24.643 ThaliTest[2793:7957400] server session: stateChange:1->2 8vk05J_k2lTBa3VjxkGkbg
,2016-01-28 13:57:24.647 ThaliTest[2793:7956167] client: relay established
2016-01-28 13:57:24.647 ThaliTest[2793:7956167] client: new accepted socket: 0x15b05b20
,2016-01-28 13:57:24.681 ThaliTest[2793:7956167] server relay: connected (to port: 65374)
,server bridge: new client socket

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

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket
,
,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed
,
,client bridge: new client socket

,Possibly unhandled Error. ETIMEDOUT
onError@/private/var/mobile/Containers/Bundle/Application/76456340-4BB6-4EF7-A533-76785ADFD1DF/ThaliTest.app/www/jxcore/node_modules/pouchdb/lib/deps/ajax.js:66:18
ajax/<@/private/var/mobile/Containers/Bundle/Application/76456340-4BB6-4EF7-A533-76785ADFD1DF/ThaliTest.app/www/jxcore/node_modules/pouchdb/lib/deps/ajax.js:108:1
Request.prototype.init/self.callback@/private/var/mobile/Containers/Bundle/Application/76456340-4BB6-4EF7-A533-76785ADFD1DF/ThaliTest.app/www/jxco,re/node_modules/pouchdb/node_modules/request/request.js:123:7
emit@events.js:82:1
Request.prototype.start/self.timeoutTimer<@/private/var/mobile/Containers/Bundle/Application/76456340-4BB6-4EF7-A533-76785ADFD1DF/ThaliTest.app/www/jxcore/node_modules/pouchdb/node_modules/request/request.js:590:7
$9@timers.js:120:1


,client bridge: socket closed

,client bridge: socket closed

,ok 123 1st change of remote doc should contain remote id

,ok 124 Can update remote doc without error

null

{ ok: true,
  id: 'b99b1ff9-2572-4fd5-88a2-945b52723124',
  rev: '2-1b1b1fd6fcc4119cb2039037c8836960' }

client bridge: new client socket

,ok 125 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

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

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed
,
client bridge: socket closed
,
,ok 126 Local changes occur in strict order

,ok 127 2nd change of local doc should contain remote id

,# setup

,client bridge: new client socket

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

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

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

,2016-01-28 13:57:50.715 ThaliTest[2793:7956412] jxcore: stopBroadcasting
2016-01-28 13:57:50.715 ThaliTest[2793:7956412] THEMultipeerSession stopping peer
,2016-01-28 13:57:50.716 ThaliTest[2793:7956412] multipeer session: stop timer
2016-01-28 13:57:50.716 ThaliTest[2793:7956412] client session: disconnect
2016-01-28 13:57:50.716 ThaliTest[2793:7956412] client session: stateChange:2->0 8vk05J_k2lTBa3VjxkGkbg.i3zmOg==
,2016-01-28 13:57:50.721 ThaliTest[2793:7956412] server session: disconnect
2016-01-28 13:57:50.723 ThaliTest[2793:7956412] server session: stateChange:2->0 8vk05J_k2lTBa3VjxkGkbg
,2016-01-28 13:57:50.733 ThaliTest[2793:7956412] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,mux server bridge listener closed

,client bridge: socket closed

,server bridge: socket closed

,# teardown

,ok 128 host address should match

ok 129 port should match

,ok 130 peer should be available

,ok 131 peer should be unavailable

,# setup

,# #startUpdateAdvertisingAndListening should use different USN after every invocation

,# teardown

,ok 132 when receiving the first byebye, the second USN should not be set yet

,ok 133 USN should have changed from the first one

,ok 134 when receiving the second byebye, the first USN should be already set

,# setup

,# messages with invalid location or USN should be ignored

,# teardown

,WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000

,ok 135 should not have emitted with invalid port

,WARN thaliWifiInfrastructure Received an invalid USN value: 

,ok 136 should not have emitted with invalid USN

,# setup

,# verify that Thali-specific messages are filtered correctly

,# teardown

,ok 137 irrelevant messages should be ignored

,ok 138 relevant messages should not be ignored

ok 139 messages from this device should be ignored

# setup

,# #start should fail if called twice in a row

,# teardown

,ok 140 specific error should be received

# setup

,# #startUpdateAdvertisingAndListening should fail invalid router has been passed

,# teardown

,ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string

ok 141 specific error should be received

# setup

,# #startUpdateAdvertisingAndListening should fail if router server starting fails

,# teardown

,ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE

ok 142 specific error expected

# setup

,# #startUpdateAdvertisingAndListening should start hosting given router object

,# teardown

,ok 143 server should respond with code 200

,# setup

,# #stop can be called multiple times in a row

,# teardown

,ok 144 should be in stopped state

,ok 145 should still be in stopped state

,# setup

,# #startListeningForAdvertisements can be called multiple times in a row

,# teardown

,ok 146 should be in listening state

,ok 147 should still be in listening state

,# setup

,# #stopListeningForAdvertisements can be called multiple times in a row

,# teardown

,ok 148 should not be in listening state

,ok 149 should still not be in listening state

,# setup

,# #stopAdvertisingAndListening can be called multiple times in a row

,# teardown

,ok 150 should not be in advertising state

ok 151 should still not be in advertising state

# setup

,# functions are run from a queue in the right order

,# teardown

,ok 152 call order must match

,Tests Complete

,Total: 0	Passed: 0	Failed: 0

,****TEST TOOK:  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
