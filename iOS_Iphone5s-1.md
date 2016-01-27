#### Test 568182540458528_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/568182540458528/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/931944B6-0911-4634-BFE3-40B7B35DFAA7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/931944B6-0911-4634-BFE3-40B7B35DFAA7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/568182540458528/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/568182540458528/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8BF802C3-F47A-4C14-AF90-38701F025B78/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61361"
,(lldb)     command script import "/tmp/931944B6-0911-4634-BFE3-40B7B35DFAA7/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-27 02:08:36.510 ThaliTest[2663:7557670] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0F3E56A8-0252-45C3-8A31-E6F738282100/Library/Cookies/Cookies.binarycookies
,2016-01-27 02:08:36.790 ThaliTest[2663:7557670] Apache Cordova native platform version 3.9.2 is starting.
2016-01-27 02:08:36.791 ThaliTest[2663:7557670] Multi-tasking -> Device: YES, App: YES
,2016-01-27 02:08:36.798 ThaliTest[2663:7557670] Unlimited access to network resources
,2016-01-27 02:08:36.806 ThaliTest[2663:7557670] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-27 02:08:41.251 ThaliTest[2663:7557670] Resetting plugins due to page load.
,2016-01-27 02:08:42.694 ThaliTest[2663:7557670] Finished load of: file:///var/mobile/Containers/Bundle/Application/8BF802C3-F47A-4C14-AF90-38701F025B78/ThaliTest.app/www/index.html
,2016-01-27 02:08:42.898 ThaliTest[2663:7557670] JXcore Cordova plugin initializing
2016-01-27 02:08:42.899 ThaliTest[2663:7557827] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8BF802C3-F47A-4C14-AF90-38701F025B78/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8BF802C3-F47A-4C14-AF90-38701F025B78/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8BF802C3-F47A-4C14-AF90-38701F025B78/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8BF802C3-F47A-4C14-AF90-38701F025B78/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8BF802C3-F47A-4C14-AF90-38701F025B78/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8BF802C3-F47A-4C14-AF90-38701F025B78/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8BF802C3-F47A-4C14-AF90-38701F025B78/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8BF802C3-F47A-4C14-AF90-38701F025B78/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,# setup

,# basic

,# teardown

,ok 11 sane

# setup

,# another

,# teardown

,ok 12 sane

# setup

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

ok 22 should be equal

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

# setup

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

# setup

,# #startBroadcasting should throw on too large port

,# teardown

,ok 34 should throw

# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,# teardown

,ok 35 should be equal

ok 36 should be equal

ok 37 should be equal

# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,# teardown

,ok 38 should be equal

ok 39 should be equal

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

# setup

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

# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 52 should be equal

ok 53 should be equal

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-01-27 02:13:18.193 ThaliTest[2663:7557827] jxcore: startBroadcasting
,2016-01-27 02:13:18.201 ThaliTest[2663:7557827] server: starting 1453857198193.2663.bBnm1Q==
,2016-01-27 02:13:18.202 ThaliTest[2663:7557827] multipeer session: start timer: 0x16655300
2016-01-27 02:13:18.202 ThaliTest[2663:7557827] THEMultipeerSession initialized peer 1453857198193.2663
2016-01-27 02:13:18.203 ThaliTest[2663:7557827] jxcore: sta,rtBroadcasting: success
ok 54 Should be able to call startBroadcasting without error

2016-01-27 02:13:18.204 ThaliTest[2663:7557827] jxcore: stopBroadcasting
2016-01-27 02:13:18.204 ThaliTest[2663:7557827] THEMultipeerSession stopping peer
2016-01-27 02:13:18.205 ThaliTest[2663:7557827] multipeer session: stop timer
2016-01-27 02:13:18.205 ThaliTest[2663:7557827] jxcore: stopBroadcasting: success
ok 55 Should be able to call stopBroadcasting without error

,2016-01-27 02:13:18.206 ThaliTest[2663:7557827] jxcore: startBroadcasting
,2016-01-27 02:13:18.211 ThaliTest[2663:7557827] server: starting 1453857198205.2663.0K3clA==
,2016-01-27 02:13:18.213 ThaliTest[2663:7557827] multipeer session: start timer: 0x159c8060
2016-01-27 02:13:18.214 ThaliTest[2663:7557827] THEMultipeerSession initialized peer 1453857198205.2663
2016-01-27 02:13:18.214 ThaliTest[2663:7557827] jxcore: sta,rtBroadcasting: success
ok 56 Should be able to call startBroadcasting without error

2016-01-27 02:13:18.215 ThaliTest[2663:7557827] jxcore: stopBroadcasting
2016-01-27 02:13:18.215 ThaliTest[2663:7557827] THEMultipeerSession stopping peer
2016-01-27, 02:13:18.215 ThaliTest[2663:7557827] multipeer session: stop timer
2016-01-27 02:13:18.215 ThaliTest[2663:7557827] jxcore: stopBroadcasting: success
ok 57 Should be able to call stopBroadcasting without error

2016-01-27 02:13:18.216 ThaliTest[2663:75,57827] jxcore: startBroadcasting
,2016-01-27 02:13:18.220 ThaliTest[2663:7557827] server: starting 1453857198216.2663.ETFSAA==
2016-01-27 02:13:18.220 ThaliTest[2663:7557827] multipeer session: start timer: 0x159c8060
2016-01-27 02:13:18.220 ThaliTest[2663:7557827] THEMultipeerSession in,itialized peer 1453857198216.2663
2016-01-27 02:13:18.220 ThaliTest[2663:7557827] jxcore: startBroadcasting: success
ok 58 Should be able to call startBroadcasting without error

2016-01-27 02:13:18.221 ThaliTest[2663:7557827] jxcore: stopBroadcasting,
2016-01-27 02:13:18.222 ThaliTest[2663:7557827] THEMultipeerSession stopping peer
2016-01-27 02:13:18.222 ThaliTest[2663:7557827] multipeer session: stop timer
2016-01-27 02:13:18.222 ThaliTest[2663:7557827] jxcore: stopBroadcasting: success
ok 59 Shou,ld be able to call stopBroadcasting without error

2016-01-27 02:13:18.223 ThaliTest[2663:7557827] jxcore: startBroadcasting
,2016-01-27 02:13:18.226 ThaliTest[2663:7557827] server: starting 1453857198223.2663.Q1KSAw==
2016-01-27 02:13:18.227 ThaliTest[2663:7557827] multipeer session: start timer: 0x16659810
2016-01-27 02:13:18.227 ThaliTest[2663:7557827] THEMultipeerSession in,itialized peer 1453857198223.2663
2016-01-27 02:13:18.230 ThaliTest[2663:7557827] jxcore: startBroadcasting: success
ok 60 Should be able to call startBroadcasting without error

,2016-01-27 02:13:18.231 ThaliTest[2663:7557827] jxcore: stopBroadcasting
2016-01-27 02:13:18.231 ThaliTest[2663:7557827] THEMultipeerSession stopping peer
2016-01-27 02:13:18.231 ThaliTest[2663:7557827] multipeer session: stop timer
2016-01-27 02:13:18.232 ThaliTest[2663:7557827] jxcore: stopBroadcasting: success
ok 61 Should be able to call stopBroadcasting without error

2016-01-27 02:13:18.233 ThaliTest[2663:7557827] jxcore: startBroadcasting
,2016-01-27 02:13:18.238 ThaliTest[2663:7557827] server: starting 1453857198232.2663.TRi36A==
2016-01-27 02:13:18.240 ThaliTest[2663:7557827] multipeer session: start timer: 0x15fb7810
2016-01-27 02:13:18.242 ThaliTest[2663:7557827] THEMultipeerSession in,itialized peer 1453857198232.2663
2016-01-27 02:13:18.242 ThaliTest[2663:7557827] jxcore: startBroadcasting: success
ok 62 Should be able to call startBroadcasting without error

,2016-01-27 02:13:18.243 ThaliTest[2663:7557827] jxcore: stopBroadcasting
2016-01-27 02:13:18.243 ThaliTest[2663:7557827] THEMultipeerSession stopping peer
,2016-01-27 02:13:18.244 ThaliTest[2663:7557827] multipeer session: stop timer
,2016-01-27 02:13:18.244 ThaliTest[2663:7557827] jxcore: stopBroadcasting: success
ok 63 Should be able to call stopBroadcasting without error

2016-01-27 02:13:18.246 ThaliTest[2663:7557827] jxcore: startBroadcasting
,2016-01-27 02:13:18.249 ThaliTest[2663:7557827] server: starting 1453857198245.2663.olWrIQ==
2016-01-27 02:13:18.250 ThaliTest[2663:7557827] multipeer session: start timer: 0x16236e00
2016-01-27 02:13:18.250 ThaliTest[2663:7557827] THEMultipeerSession initialized peer 1453857198245.2663
2016-01-27 02:13:18.250 ThaliTest[2663:7557827] jxcore: startBroadcasting: success
ok 64 Should be able to call startBroadcasting without error

2016-01-27 02:13:18.251 ThaliTest[2663:7557827] jxcore: stopBroadcasting
2016-01-27 02:13:18.252 ThaliTest[2663:7557827] THEMultipeerSession stopping peer
2016-01-27 02:13:18.252 ThaliTest[2663:7557827] multipeer session: stop timer
2016-01-27 02:13:18.252 ThaliTest[2663:7557827] jxcore: stopBroadcasting: success
ok 65 Shou,ld be able to call stopBroadcasting without error

2016-01-27 02:13:18.253 ThaliTest[2663:7557827] jxcore: startBroadcasting
,2016-01-27 02:13:18.256 ThaliTest[2663:7557827] server: starting 1453857198253.2663.O2Xp2w==
2016-01-27 02:13:18.258 ThaliTest[2663:7557827] multipeer session: start timer: 0x1665be60
2016-01-27 02:13:18.258 ThaliTest[2663:7557827] THEMultipeerSession initialized peer 1453857198253.2663
2016-01-27 02:13:18.258 ThaliTest[2663:7557827] jxcore: startBroadcasting: success
ok 66 Should be able to call startBroadcasting without error

,2016-01-27 02:13:18.261 ThaliTest[2663:7557827] jxcore: stopBroadcasting
2016-01-27 02:13:18.269 ThaliTest[2663:7557827] THEMultipeerSession stopping peer
2016-01-27 02:13:18.269 ThaliTest[2663:7557827] multipeer session: stop timer
2016-01-27 02:13:18.269 ThaliTest[2663:7557827] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error

2016-01-27 02:13:18.270 ThaliTest[2663:7557827] jxcore: startBroadcasting
,2016-01-27 02:13:18.276 ThaliTest[2663:7557827] server: starting 1453857198270.2663.ENlqww==
,2016-01-27 02:13:18.279 ThaliTest[2663:7557827] multipeer session: start timer: 0x162372e0
,2016-01-27 02:13:18.282 ThaliTest[2663:7557827] THEMultipeerSession initialized peer 1453857198270.2663
,2016-01-27 02:13:18.284 ThaliTest[2663:7557827] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-01-27 02:13:18.286 ThaliTest[2663:7557827] jxcore: stopBroadcasting
,2016-01-27 02:13:18.287 ThaliTest[2663:7557827] THEMultipeerSession stopping peer
,2016-01-27 02:13:18.288 ThaliTest[2663:7557827] multipeer session: stop timer
,2016-01-27 02:13:18.291 ThaliTest[2663:7557827] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-01-27 02:13:18.293 ThaliTest[2663:7557827] jxcore: startBroadcasting
,2016-01-27 02:13:18.296 ThaliTest[2663:7557827] server: starting 1453857198293.2663.IcVdLw==
,2016-01-27 02:13:18.297 ThaliTest[2663:7557827] multipeer session: start timer: 0x1597c430
,2016-01-27 02:13:18.299 ThaliTest[2663:7557827] THEMultipeerSession initialized peer 1453857198293.2663
,2016-01-27 02:13:18.302 ThaliTest[2663:7557827] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-01-27 02:13:18.305 ThaliTest[2663:7557827] jxcore: stopBroadcasting
,2016-01-27 02:13:18.306 ThaliTest[2663:7557827] THEMultipeerSession stopping peer
,2016-01-27 02:13:18.306 ThaliTest[2663:7557827] multipeer session: stop timer
,2016-01-27 02:13:18.308 ThaliTest[2663:7557827] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

,2016-01-27 02:13:18.311 ThaliTest[2663:7557827] jxcore: startBroadcasting
,2016-01-27 02:13:18.313 ThaliTest[2663:7557827] server: starting 1453857198311.2663.423Ocw==
,2016-01-27 02:13:18.316 ThaliTest[2663:7557827] multipeer session: start timer: 0x1665be60
,2016-01-27 02:13:18.318 ThaliTest[2663:7557827] THEMultipeerSession initialized peer 1453857198311.2663
,2016-01-27 02:13:18.320 ThaliTest[2663:7557827] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error
,
,2016-01-27 02:13:18.323 ThaliTest[2663:7557827] jxcore: stopBroadcasting
,2016-01-27 02:13:18.324 ThaliTest[2663:7557827] THEMultipeerSession stopping peer
,2016-01-27 02:13:18.325 ThaliTest[2663:7557827] multipeer session: stop timer
,2016-01-27 02:13:18.328 ThaliTest[2663:7557827] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-27 02:13:18.674 ThaliTest[2663:7557827] jxcore: startBroadcasting
,2016-01-27 02:13:18.676 ThaliTest[2663:7557827] server: starting 1453857198674.2663.h/9YhA==
2016-01-27 02:13:18.676 ThaliTest[2663:7557827] multipeer session: start timer: 0x1665ca40
2016-01-27 02:13:18.676 ThaliTest[2663:7557827] THEMultipeerSession initialized peer 1453857198674.2663
2016-01-27 02:13:18.676 ThaliTest[2663:7557827] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

2016-01-27 02:13:18.678 ThaliTest[2663:7557827] jxcore: startBroadcasting
,2016-01-27 02:13:18.678 ThaliTest[2663:7557827] jxcore: startBroadcasting: failure
,ok 75 Cannot call startBroadcasting twice

2016-01-27 02:13:18.680 ThaliTest[2663:7557827] jxcore: stopBroadcasting
2016-01-27 02:13:18.681 ThaliTest[2663:7557827] THEMultipeerSession stopping peer
2016-01-27 02:13:18.681 ThaliTest[2663:7557827] multipeer session: stop timer
2016-01-27 02:13:18.681 ThaliTest[2663:7557827] jxcore: stopBroadcasting: success
ok 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-27 02:13:21.554 ThaliTest[2663:7557827] jxcore: startBroadcasting
,2016-01-27 02:13:21.555 ThaliTest[2663:7557827] server: starting 1453857201553.2663.aKi8aQ==
2016-01-27 02:13:21.556 ThaliTest[2663:7557827] multipeer session: start timer: 0x16660dc0
2016-01-27 02:13:21.556 ThaliTest[2663:7557827] THEMultipeerSession initialized peer 1453857201553.2663
,2016-01-27 02:13:21.558 ThaliTest[2663:7557827] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-01-27 02:13:21.559 ThaliTest[2663:7557827] jxcore: connect foobar
2016-01-27 02:13:21.559 ThaliTest[26,63:7557827] client: unknown peer foobar
2016-01-27 02:13:21.559 ThaliTest[2663:7557827] jxcore: connect: fail: Unknown peer
,ok 78 Should not connect to a bad peer

2016-01-27 02:13:21.561 ThaliTest[2663:7557827] jxcore: stopBroadcasting
2016-01-27 02:13:21.561 ThaliTest[2663:7557827] THEMultipeerSession stopping peer
2016-01-27 02:13:21.562 ThaliTest[2663:7557827] multipeer session: stop timer
2016-01-27 02:13:21.562 ThaliTest[2663:7557827] jxcore: stopBroadcasting: success
ok 79 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-27 02:13:21.673 ThaliTest[2663:7557827] jxcore: startBroadcasting
,2016-01-27 02:13:21.675 ThaliTest[2663:7557827] server: starting 1453857201673.2663.CRRiNQ==
2016-01-27 02:13:21.675 ThaliTest[2663:7557827] multipeer session: start timer: 0x15f2e3a0
2016-01-27 02:13:21.675 ThaliTest[2663:7557827] THEMultipeerSession initialized peer 1453857201673.2663
2016-01-27 02:13:21.675 ThaliTest[2663:7557827] jxcore: startBroadcasting: success
ok 80 Should be able to call startBroadcasting without error

2016-01-27 02:13:21.676 ThaliTest[2663:7557827] jxcore: disconnect
2016-01-27 02:13:21.677 ThaliTest[2663:7557827] jxcore: disconnect: fail
ok 81 Disconnect should fail to a non-existant peer 

,2016-01-27 02:13:21.678 ThaliTest[2663:7557827] jxcore: stopBroadcasting
2016-01-27 02:13:21.678 ThaliTest[2663:7557827] THEMultipeerSession stopping peer
2016-01-27 02:13:21.679 ThaliTest[2663:7557827] multipeer session: stop timer
,2016-01-27 02:13:21.683 ThaliTest[2663:7557827] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-27 02:13:21.832 ThaliTest[2663:7557827] jxcore: startBroadcasting
,2016-01-27 02:13:21.834 ThaliTest[2663:7557827] server: starting 1453857201832.2663.u2wqlg==
2016-01-27 02:13:21.834 ThaliTest[2663:7557827] multipeer session: start timer: 0x16667890
2016-01-27 02:13:21.835 ThaliTest[2663:7557827] THEMultipeerSession initialized peer 1453857201832.2663
2016-01-27 02:13:21.835 ThaliTest[2663:7557827] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-27 02:13:23.351 ThaliTest[2663:7557670] client: found peer: 1453857202776.2999.647KgA==
2016-01-27 02:13:23.353 ThaliTest[2663:7557827] jxcore: connect 1453857202776.2999.647KgA==
2016-01-27 02:13:23.353 ThaliTest[2663:7557827] client session: co,nnect
2016-01-27 02:13:23.353 ThaliTest[2663:7557827] client session: stateChange:0->1 1453857202776.2999.647KgA==
,2016-01-27 02:13:23.453 ThaliTest[2663:7557670] multipeer session: reset timer
2016-01-27 02:13:23.454 ThaliTest[2663:7557670] multipeer session: stop timer
2016-01-27 02:13:23.454 ThaliTest[2663:7557670] multipeer session: start timer: 0x16667890
2016-01-27 02:13:23.454 ThaliTest[2663:7557670] server session: connect
,2016-01-27 02:13:23.454 ThaliTest[2663:7557670] server session: stateChange:0->1 1453857202776.2999
,2016-01-27 02:13:23.462 ThaliTest[2663:7557670] server: accepting invitation 1453857202776.2999
,2016-01-27 02:13:25.783 ThaliTest[2663:7558834] client session: connected
2016-01-27 02:13:25.783 ThaliTest[2663:7558834] client session: stateChange:1->2 1453857202776.2999.647KgA==
,2016-01-27 02:13:25.825 ThaliTest[2663:7558838] client session: fireConnectCallback: 1453857202776.2999.647KgA==
2016-01-27 02:13:25.825 ThaliTest[2663:7558838] jxcore: connect: success
ok 84 Should be able to connect without error

ok 85 Port should be within range

,2016-01-27 02:13:25.827 ThaliTest[2663:7557827] jxcore: disconnect
2016-01-27 02:13:25.827 ThaliTest[2663:7557827] client session: disconnectFromPeer: 1453857202776.2999.647KgA==
2016-01-27 02:13:25.827 ThaliTest[2663:7557827] client session: disconnect
2016-01-27 02:13:25.827 ThaliTest[2663:7557827] client session: stateChange:2->0 1453857202776.2999.647KgA==
,2016-01-27 02:13:25.832 ThaliTest[2663:7557827] jxcore: disconnect: success
ok 86 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-27 02:13:25.909 ThaliTest[2663:7558838] server session: connected
,2016-01-27 02:13:25.909 ThaliTest[2663:7558838] server session: stateChange:1->2 1453857202776.2999
2016-01-27 02:13:25.917 ThaliTest[2663:7557670] server relay: socket disconnected
,2016-01-27 02:13:25.917 ThaliTest[2663:7557670] server relay: 0x15f56860 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-27 02:13:25.937 ThaliTest[2663:7558830] server session: not connected 1453857202776.2999
,calling stopBroadcasting

2016-01-27 02:13:26.443 ThaliTest[2663:7557827] jxcore: stopBroadcasting
2016-01-27 02:13:26.444 ThaliTest[2663:7557827] THEMultipeerSession stopping peer
2016-01-27 02:13:26.444 ThaliTest[2663:7557827] multipeer session: stop timer
2016-01-27 02:13:26.444 ThaliTest[2663:7557827] server session: disconnect
2016-01-27 02:13:26.444 ThaliTest[2663:7557827] server session: stateChange:2->0 1453857202776.2999
,2016-01-27 02:13:26.445 ThaliTest[2663:7557827] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-27 02:13:27.583 ThaliTest[2663:7557827] jxcore: startBroadcasting
,2016-01-27 02:13:27.586 ThaliTest[2663:7557827] server: starting 1453857207583.2663.YIoGXQ==
2016-01-27 02:13:27.587 ThaliTest[2663:7557827] multipeer session: start timer: 0x1666afe0
2016-01-27 02:13:27.587 ThaliTest[2663:7557827] THEMultipeerSession initialized peer 1453857207583.2663
2016-01-27 02:13:27.587 ThaliTest[2663:7557827] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-01-27 02:13:28.724 ThaliTest[2663:7557670] multipeer session: reset timer
2016-01-27 02:13:28.724 ThaliTest[2663:7557670] multipeer session: stop timer
2016-01-27 02:13:28.724 ThaliTest[2663:7557670] multipeer session: start timer: 0x1666afe0
2016-01-27 02:13:28.725 ThaliTest[2663:7557670] server session: connect
2016-01-27 02:13:28.725 ThaliTest[2663:7557670] server session: stateChange:0->1 1453857208256.2999
,2016-01-27 02:13:28.730 ThaliTest[2663:7557670] server: accepting invitation 1453857208256.2999
2016-01-27 02:13:28.731 ThaliTest[2663:7557670] client: found peer: 1453857208256.2999.US3igQ==
,2016-01-27 02:13:28.735 ThaliTest[2663:7557827] jxcore: connect 1453857208256.2999.US3igQ==
2016-01-27 02:13:28.756 ThaliTest[2663:7557827] client session: connect
2016-01-27 02:13:28.757 ThaliTest[2663:7557827] client session: stateChange:0->1 1453857208256.2999.US3igQ==
,2016-01-27 02:13:31.156 ThaliTest[2663:7558834] server session: connected
2016-01-27 02:13:31.156 ThaliTest[2663:7558834] server session: stateChange:1->2 1453857208256.2999
,2016-01-27 02:13:31.164 ThaliTest[2663:7557670] server relay: socket disconnected
,2016-01-27 02:13:31.164 ThaliTest[2663:7557670] server relay: 0x16657d10 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-27 02:13:31.175 ThaliTest[2663:7558840] server session: not connected 1453857208256.2999
,2016-01-27 02:13:31.291 ThaliTest[2663:7558840] client session: connected
2016-01-27 02:13:31.291 ThaliTest[2663:7558840] client session: stateChange:1->2 1453857208256.2999.US3igQ==
,2016-01-27 02:13:31.332 ThaliTest[2663:7558838] client session: fireConnectCallback: 1453857208256.2999.US3igQ==
2016-01-27 02:13:31.332 ThaliTest[2663:7558838] jxcore: connect: success
ok 88 Should be able to connect without error

ok 89 Port should be within range

2016-01-27 02:13:31.333 ThaliTest[2663:7557827] jxcore: connect 1453857208256.2999.US3igQ==
2016-01-27 02:13:31.334 ThaliTest[2663:7557827] client: already connect(ing/ed) to 1453857208256.2999.US3igQ==
2016-01-27 02:13:31.334 ThaliTest[2663:7557827] jxcore: connect: fail: Aleady connecting
ok 90 Should fail on double connect

,2016-01-27 02:13:31.335 ThaliTest[2663:7557827] jxcore: disconnect
2016-01-27 02:13:31.338 ThaliTest[2663:7557827] client session: disconnectFromPeer: 1453857208256.2999.US3igQ==
2016-01-27 02:13:31.338 ThaliTest[2663:7557827] client session: disconnect,
2016-01-27 02:13:31.338 ThaliTest[2663:7557827] client session: stateChange:2->0 1453857208256.2999.US3igQ==
,2016-01-27 02:13:31.346 ThaliTest[2663:7557827] jxcore: disconnect: success
ok 91 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

2016-01-27 02:13:31.679 ThaliTest[2663:7557827] jxcore: stopBroadcasting
2016-01-27 02:13:31.679 ThaliTest[2663:7557827] THEMultipeerSession stopping peer
2016-01-27 02:13:31.680 ThaliTest[2663:7557827] multipeer session: stop, timer
2016-01-27 02:13:31.680 ThaliTest[2663:7557827] server session: disconnect
2016-01-27 02:13:31.680 ThaliTest[2663:7557827] server session: stateChange:2->0 1453857208256.2999
,2016-01-27 02:13:31.681 ThaliTest[2663:7557827] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-27 02:13:32.209 ThaliTest[2663:7557827] jxcore: startBroadcasting
,2016-01-27 02:13:32.211 ThaliTest[2663:7557827] server: starting 1453857212209.2663.FU+7eQ==
2016-01-27 02:13:32.211 ThaliTest[2663:7557827] multipeer session: start timer: 0x15f8a2c0
2016-01-27 02:13:32.211 ThaliTest[2663:7557827] THEMultipeerSession initialized peer 1453857212209.2663
2016-01-27 02:13:32.211 ThaliTest[2663:7557827] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-01-27 02:13:32.931 ThaliTest[2663:7557670] client: found peer: 1453857212742.2999.cY6xGw==
2016-01-27 02:13:32.933 ThaliTest[2663:7557827] jxcore: connect 1453857212742.2999.cY6xGw==
2016-01-27 02:13:32.933 ThaliTest[2663:7557827] client session: connect
2016-01-27 02:13:32.933 ThaliTest[2663:7557827] client session: stateChange:0->1 1453857212742.2999.cY6xGw==
,2016-01-27 02:13:33.378 ThaliTest[2663:7557670] multipeer session: reset timer
2016-01-27 02:13:33.378 ThaliTest[2663:7557670] multipeer session: stop timer
2016-01-27 02:13:33.378 ThaliTest[2663:7557670] multipeer session: start timer: 0x15f8a2c0
2016-01-27 02:13:33.378 ThaliTest[2663:7557670] server session: connect
2016-01-27 02:13:33.378 ThaliTest[2663:7557670] server session: stateChange:0->1 1453857212742.2999
,2016-01-27 02:13:33.382 ThaliTest[2663:7557670] server: accepting invitation 1453857212742.2999
,2016-01-27 02:13:35.481 ThaliTest[2663:7558840] client session: connected
,2016-01-27 02:13:35.481 ThaliTest[2663:7558840] client session: stateChange:1->2 1453857212742.2999.cY6xGw==
,2016-01-27 02:13:35.503 ThaliTest[2663:7558838] client session: fireConnectCallback: 1453857212742.2999.cY6xGw==
2016-01-27 02:13:35.503 ThaliTest[2663:7558838] jxcore: connect: success
ok 93 Should be able to connect without error

ok 94 Port should be within range

,2016-01-27 02:13:35.505 ThaliTest[2663:7557827] jxcore: disconnect
2016-01-27 02:13:35.505 ThaliTest[2663:7557827] client session: disconnectFromPeer: 1453857212742.2999.cY6xGw==
2016-01-27 02:13:35.505 ThaliTest[2663:7557827] client session: disconnect
2016-01-27 02:13:35.505 ThaliTest[2663:7557827] client session: stateChange:2->0 1453857212742.2999.cY6xGw==
,2016-01-27 02:13:35.570 ThaliTest[2663:7557827] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error

,2016-01-27 02:13:35.571 ThaliTest[2663:7557827] jxcore: disconnect
2016-01-27 02:13:35.571 ThaliTest[2663:7557827] jxcore: disconnect: fail
,ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-27 02:13:35.743 ThaliTest[2663:7558834] server session: connected
2016-01-27 02:13:35.743 ThaliTest[2663:7558834] server session: stateChange:1->2 1453857212742.2999
,2016-01-27 02:13:35.756 ThaliTest[2663:7557670] server relay: socket disconnected
2016-01-27 02:13:35.756 ThaliTest[2663:7557670] server relay: 0x163065a0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-27 02:13:35.786 ThaliTest[2663:7558838] server session: not connected 1453857212742.2999
,calling stopBroadcasting

,2016-01-27 02:13:35.880 ThaliTest[2663:7557827] jxcore: stopBroadcasting
2016-01-27 02:13:35.880 ThaliTest[2663:7557827] THEMultipeerSession stopping peer
2016-01-27 02:13:35.880 ThaliTest[2663:7557827] multipeer session: stop timer
2016-01-27 02:13:35.,880 ThaliTest[2663:7557827] server session: disconnect
2016-01-27 02:13:35.880 ThaliTest[2663:7557827] server session: stateChange:2->0 1453857212742.2999
2016-01-27 02:13:35.881 ThaliTest[2663:7557827] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 64372

,2016-01-27 02:13:37.562 ThaliTest[2663:7557827] jxcore: startBroadcasting
,2016-01-27 02:13:37.564 ThaliTest[2663:7557827] server: starting 1453857217561.2663.akxSTg==
2016-01-27 02:13:37.564 ThaliTest[2663:7557827] multipeer session: start timer: 0x15d16cc0
2016-01-27 02:13:37.565 ThaliTest[2663:7557827] THEMultipeerSession in,itialized peer 1453857217561.2663
2016-01-27 02:13:37.565 ThaliTest[2663:7557827] jxcore: startBroadcasting: success
ok 97 Should be able to call startBroadcasting without error

,2016-01-27 02:13:37.577 ThaliTest[2663:7557670] client: found peer: 1453857212742.2999.cY6xGw==
2016-01-27 02:13:37.578 ThaliTest[2663:7557827] jxcore: connect 1453857212742.2999.cY6xGw==
2016-01-27 02:13:37.578 ThaliTest[2663:7557827] client session: co,nnect
2016-01-27 02:13:37.579 ThaliTest[2663:7557827] client session: stateChange:0->1 1453857212742.2999.cY6xGw==
,2016-01-27 02:13:38.946 ThaliTest[2663:7557670] multipeer session: reset timer
2016-01-27 02:13:38.946 ThaliTest[2663:7557670] multipeer session: stop timer
2016-01-27 02:13:38.946 ThaliTest[2663:7557670] multipeer session: start timer: 0x15d16cc0
2016-01-27 02:13:38.946 ThaliTest[2663:7557670] server session: connect
2016-01-27 02:13:38.946 ThaliTest[2663:7557670] server session: stateChange:0->1 1453857218072.2999
,2016-01-27 02:13:38.950 ThaliTest[2663:7557670] server: accepting invitation 1453857218072.2999
,2016-01-27 02:13:39.111 ThaliTest[2663:7557670] client: lost peer: 1453857212742.2999.cY6xGw==
2016-01-27 02:13:39.111 ThaliTest[2663:7557670] client session: onPeerLost: 1453857212742.2999.cY6xGw==
2016-01-27 02:13:39.111 ThaliTest[2663:7557670] client ,session: onLinkFailure: 1453857212742.2999.cY6xGw==
2016-01-27 02:13:39.111 ThaliTest[2663:7557670] client session: disconnect
2016-01-27 02:13:39.111 ThaliTest[2663:7557670] client session: stateChange:1->0 1453857212742.2999.cY6xGw==
,2016-01-27 02:13:39.112 ThaliTest[2663:7557670] client session: fireConnectCallback: 1453857212742.2999.cY6xGw==
2016-01-27 02:13:39.112 ThaliTest[2663:7557670] jxcore: connect: fail: Peer disconnected
2016-01-27 02:13:39.113 ThaliTest[2663:7557670] clie,nt: found peer: 1453857218072.2999.0tixUw==
2016-01-27 02:13:39.115 ThaliTest[2663:7557827] jxcore: connect 1453857218072.2999.0tixUw==
2016-01-27 02:13:39.115 ThaliTest[2663:7557827] client session: connect
2016-01-27 02:13:39.115 ThaliTest[2663:7557827] client session: stateChange:0->1 1453857218072.2999.0tixUw==
,2016-01-27 02:13:40.121 ThaliTest[2663:7557827] jxcore: connect 1453857212742.2999.cY6xGw==
2016-01-27 02:13:40.121 ThaliTest[2663:7557827] client: connect: unreachable 1453857212742.2999.cY6xGw==
2016-01-27 02:13:40.122 ThaliTest[2663:7557827] jxcore: connect: fail: Peer unreachable
,2016-01-27 02:13:41.270 ThaliTest[2663:7558830] server session: connected
2016-01-27 02:13:41.271 ThaliTest[2663:7558830] server session: stateChange:1->2 1453857218072.2999
,2016-01-27 02:13:41.274 ThaliTest[2663:7557670] server relay: connected (to port: 64372)
,2016-01-27 02:13:41.486 ThaliTest[2663:7558830] client session: connected
,2016-01-27 02:13:41.486 ThaliTest[2663:7558830] client session: stateChange:1->2 1453857218072.2999.0tixUw==
,2016-01-27 02:13:41.497 ThaliTest[2663:7558830] client session: fireConnectCallback: 1453857218072.2999.0tixUw==
2016-01-27 02:13:41.497 ThaliTest[2663:7558830] jxcore: connect: success
,ok 98 Should be able to connect without error

,ok 99 Port should be within range

,2016-01-27 02:13:41.502 ThaliTest[2663:7557670] client: relay established
,2016-01-27 02:13:41.503 ThaliTest[2663:7557670] client: new accepted socket: 0x15d44610
,2016-01-27 02:13:41.587 ThaliTest[2663:7558830] server session: not connected 1453857218072.2999
,data in 47104

,data in 55845

,data in 68985

,data in 79935

,data in 99645

,data in 131072

,ok 100 the test messages should be equal

,2016-01-27 02:13:41.711 ThaliTest[2663:7557827] jxcore: disconnect
,2016-01-27 02:13:41.711 ThaliTest[2663:7557827] client session: disconnectFromPeer: 1453857218072.2999.0tixUw==
,2016-01-27 02:13:41.712 ThaliTest[2663:7557827] client session: disconnect
,2016-01-27 02:13:41.712 ThaliTest[2663:7557827] client session: stateChange:2->0 1453857218072.2999.0tixUw==
,2016-01-27 02:13:41.717 ThaliTest[2663:7557827] jxcore: disconnect: success
,ok 101 Should be able to disconnect without error
,
,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-27 02:13:42.169 ThaliTest[2663:7557827] jxcore: stopBroadcasting
2016-01-27 02:13:42.169 ThaliTest[2663:7557827] THEMultipeerSession stopping peer
2016-01-27 02:13:42.169 ThaliTest[2663:7557827] multipeer session: stop timer
2016-01-27 02:13:42.,169 ThaliTest[2663:7557827] server session: disconnect
2016-01-27 02:13:42.169 ThaliTest[2663:7557827] server session: stateChange:2->0 1453857218072.2999
,2016-01-27 02:13:43.072 ThaliTest[2663:7557827] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 64379

,2016-01-27 02:13:43.604 ThaliTest[2663:7557827] jxcore: startBroadcasting
,2016-01-27 02:13:43.606 ThaliTest[2663:7557827] server: starting 1453857223604.2663.qQMTwQ==
2016-01-27 02:13:43.607 ThaliTest[2663:7557827] multipeer session: start timer: 0x15d45090
2016-01-27 02:13:43.607 ThaliTest[2663:7557827] THEMultipeerSession in,itialized peer 1453857223604.2663
2016-01-27 02:13:43.607 ThaliTest[2663:7557827] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-01-27 02:13:44.461 ThaliTest[2663:7557670] client: found peer: 1453857224278.2999.fHgzCg==
[{"peerIdentifier":"1453857224278.2999.fHgzCg==","peerName":"(null)","peerAvailable":true}]

2016-01-27 02:13:44.462 ThaliTest[2663:7557827] jxcore: connect ,1453857224278.2999.fHgzCg==
2016-01-27 02:13:44.462 ThaliTest[2663:7557827] client session: connect
2016-01-27 02:13:44.462 ThaliTest[2663:7557827] client session: stateChange:0->1 1453857224278.2999.fHgzCg==
,2016-01-27 02:13:45.107 ThaliTest[2663:7557670] multipeer session: reset timer
2016-01-27 02:13:45.107 ThaliTest[2663:7557670] multipeer session: stop timer
2016-01-27 02:13:45.108 ThaliTest[2663:7557670] multipeer session: start timer: 0x15d45090
2016-01-27 02:13:45.108 ThaliTest[2663:7557670] server session: connect
2016-01-27 02:13:45.108 ThaliTest[2663:7557670] server session: stateChange:0->1 1453857224278.2999
,2016-01-27 02:13:45.115 ThaliTest[2663:7557670] server: accepting invitation 1453857224278.2999
,2016-01-27 02:13:47.526 ThaliTest[2663:7558830] server session: connected
2016-01-27 02:13:47.526 ThaliTest[2663:7558830] server session: stateChange:1->2 1453857224278.2999
,2016-01-27 02:13:47.531 ThaliTest[2663:7558834] client session: connected
2016-01-27 02:13:47.532 ThaliTest[2663:7558834] client session: stateChange:1->2 1453857224278.2999.fHgzCg==
,2016-01-27 02:13:47.541 ThaliTest[2663:7557670] server relay: connected (to port: 64379)
,2016-01-27 02:13:47.559 ThaliTest[2663:7558835] client session: fireConnectCallback: 1453857224278.2999.fHgzCg==
2016-01-27 02:13:47.559 ThaliTest[2663:7558835] jxcore: connect: success
ok 103 Should be able to connect without error

,ok 104 Port should be within range

,ok 105 First connect should succeed

,2016-01-27 02:13:47.573 ThaliTest[2663:7557670] client: relay established
2016-01-27 02:13:47.573 ThaliTest[2663:7557670] client: new accepted socket: 0x163f9220
,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-01-27 02:13:47.648 ThaliTest[2663:7558977] server session: not connected 1453857224278.2999
,2016-01-27 02:13:47.653 ThaliTest[2663:7557670] client: socket closed
2016-01-27 02:13:47.653 ThaliTest[2663:7557670] client relay: socket disconnected
2016-01-27 02:13:47.653 ThaliTest[2663:7557670] client relay: 0x163f9220 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-27 02:13:47.653 ThaliTest[2663:7557670] client session: socket closed: 1453857224278.2999.fHgzCg==
2016-01-27 02:13:47.653 ThaliTest[2663:7557670] client session: onLinkFailure: 1453857224278.2999.fHgzCg==
2016-01-27 02:13:47.653 ThaliTest[2663:7557670] client session: disconnect
2016-01-27 02:13:47.653 ThaliTest[2663:7557670] client session: stateChange:2->0 1453857224278.2999.fHgzCg==
,2016-01-27 02:13:47.659 ThaliTest[2663:7557670] client session: fireConnectionErrorEvent: 1453857224278.2999.fHgzCg==
,2016-01-27 02:13:47.662 ThaliTest[2663:7557827] jxcore: connect 1453857224278.2999.fHgzCg==
2016-01-27 02:13:47.663 ThaliTest[2663:7557827] client session: connect
2016-01-27 02:13:47.664 ThaliTest[2663:7557827] client session: stateChange:0->1 1453857224278.2999.fHgzCg==
,2016-01-27 02:13:47.670 ThaliTest[2663:7557670] multipeer session: reset timer
2016-01-27 02:13:47.670 ThaliTest[2663:7557670] multipeer session: stop timer
2016-01-27 02:13:47.670 ThaliTest[2663:7557670] multipeer session: start timer: 0x15d45090
2016-,01-27 02:13:47.670 ThaliTest[2663:7557670] server: disconnecting to refresh session (1453857224278.2999)
2016-01-27 02:13:47.670 ThaliTest[2663:7557670] server session: disconnect
2016-01-27 02:13:47.670 ThaliTest[2663:7557670] server session: stateChange:2->0 1453857224278.2999
,2016-01-27 02:13:47.675 ThaliTest[2663:7557670] server session: connect
,2016-01-27 02:13:47.675 ThaliTest[2663:7557670] server session: stateChange:0->1 1453857224278.2999
2016-01-27 02:13:47.680 ThaliTest[2663:7557670] server: accepting invitation 1453857224278.2999
,2016-01-27 02:13:50.086 ThaliTest[2663:7558835] server session: connected
2016-01-27 02:13:50.086 ThaliTest[2663:7558835] server session: stateChange:1->2 1453857224278.2999
,2016-01-27 02:13:50.094 ThaliTest[2663:7557670] server relay: connected (to port: 64379)
,2016-01-27 02:13:50.181 ThaliTest[2663:7558985] server session: not connected 1453857224278.2999
,2016-01-27 02:13:50.287 ThaliTest[2663:7558985] client session: connected
,2016-01-27 02:13:50.287 ThaliTest[2663:7558985] client session: stateChange:1->2 1453857224278.2999.fHgzCg==
,2016-01-27 02:13:50.294 ThaliTest[2663:7558840] client session: fireConnectCallback: 1453857224278.2999.fHgzCg==
2016-01-27 02:13:50.294 ThaliTest[2663:7558840] jxcore: connect: success
ok 108 Should be able to connect without error

ok 109 Port should, be within range

ok 110 Second connect should succeed

,2016-01-27 02:13:50.307 ThaliTest[2663:7557670] client: relay established
,2016-01-27 02:13:50.308 ThaliTest[2663:7557670] client: new accepted socket: 0x15dc6f60
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-01-27 02:13:50.359 ThaliTest[2663:7557670] client: socket closed
2016-01-27 02:13:50.360 ThaliTest[2663:7557670] client relay: socket disconnected
2016-01-27 02:13:50.360 ThaliTest[2663:7557670] client relay: 0x15dc6f60 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-27 02:13:50.360 ThaliTest[2663:7557670] client session: socket closed: 1453857224278.2999.fHgzCg==
2016-01-27 02:13:50.360 ThaliTest[2663:7557670] client session: onLinkFailure: 1453857224278.2999.fHgzCg==
2016-01-27 02:13:50.360 ThaliTest[2663:7557670] client session: disconnect
2016-01-27 02:13:50.360 ThaliTest[2663:7557670] client session: stateChange:2->0 14,53857224278.2999.fHgzCg==
,2016-01-27 02:13:50.366 ThaliTest[2663:7557670] client session: fireConnectionErrorEvent: 1453857224278.2999.fHgzCg==
,calling stopBroadcasting

,2016-01-27 02:13:50.591 ThaliTest[2663:7557827] jxcore: stopBroadcasting
2016-01-27 02:13:50.591 ThaliTest[2663:7557827] THEMultipeerSession stopping peer
2016-01-27 02:13:50.591 ThaliTest[2663:7557827] multipeer session: stop timer
2016-01-27 02:13:50.,592 ThaliTest[2663:7557827] server session: disconnect
2016-01-27 02:13:50.592 ThaliTest[2663:7557827] server session: stateChange:2->0 1453857224278.2999
,2016-01-27 02:13:50.598 ThaliTest[2663:7557827] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/0F3E56A8-0252-45C3-8A31-E6F738282100/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-01-27 02:13:51.219 ThaliTest[2663:7557827] jxcore: startBroadcasting
,2016-01-27 02:13:51.220 ThaliTest[2663:7557827] server: starting K8bnHAzhbDwdDVvV28g_Uw.3H8AIQ==
2016-01-27 02:13:51.221 ThaliTest[2663:7557827] multipeer session: start timer: 0x163f4380
2016-01-27 02:13:51.221 ThaliTest[2663:7557827] THEMultipeerSessio,n initialized peer K8bnHAzhbDwdDVvV28g_Uw
2016-01-27 02:13:51.221 ThaliTest[2663:7557827] jxcore: startBroadcasting: success
ok 114 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 115 stopping event should occur in right order

About to call stopBroadcasting

2016-01-27 02:13:51.223 ThaliTest[2663:7557827] jxcore: stopBroadcasting
2016-01-27 02:13:51.223 ThaliTest[2663:7557827] THEMultipeerSession stopping peer
2016-01-27 02:13:51.223 ThaliTest[26,63:7557827] multipeer session: stop timer
2016-01-27 02:13:51.223 ThaliTest[2663:7557827] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,ok 116 stopped event should occur in right order

mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/0F3E56A8-0252-45C3-8A31-E6F738282100/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-27 02:13:51.634 ThaliTest[2663:7557827] jxcore: startBroadcasting
,2016-01-27 02:13:51.636 ThaliTest[2663:7557827] server: starting K8bnHAzhbDwdDVvV28g_Uw.x+1yzA==
2016-01-27 02:13:51.636 ThaliTest[2663:7557827] multipeer session: start timer: 0x15b3ffa0
2016-01-27 02:13:51.637 ThaliTest[2663:7557827] THEMultipeerSession initialized peer K8bnHAzhbDwdDVvV28g_Uw
2016-01-27 02:13:51.637 ThaliTest[2663:7557827] jxcore: startBroadcasting: success
ok 117 getDeviceIdentity should not return an error

ok 118 deviceName should not be null

Now in TRM stop

State of this._,isStarted: true

About to call stopBroadcasting

2016-01-27 02:13:51.638 ThaliTest[2663:7557827] jxcore: stopBroadcasting
2016-01-27 02:13:51.639 ThaliTest[2663:7557827] THEMultipeerSession stopping peer
2016-01-27 02:13:51.639 ThaliTest[2663:7557827] multipeer session: stop timer
2016-01-27 02:13:51.639 ThaliTest[2663:7557827] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/0F3E56A8-0252-45C3-8A31-E6F738282100/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-27 02:13:55.337 ThaliTest[2663:7557827] jxcore: startBroadcasting
,2016-01-27 02:13:55.339 ThaliTest[2663:7557827] server: starting K8bnHAzhbDwdDVvV28g_Uw.K+L3Xw==
,2016-01-27 02:13:55.341 ThaliTest[2663:7557827] multipeer session: start timer: 0x166e34b0
,2016-01-27 02:13:55.346 ThaliTest[2663:7557827] THEMultipeerSession initialized peer K8bnHAzhbDwdDVvV28g_Uw
,2016-01-27 02:13:55.347 ThaliTest[2663:7557827] jxcore: startBroadcasting: success
,ok 119 getDeviceIdentity should not return an error

,ok 120 deviceName should not be null

,2016-01-27 02:13:55.502 ThaliTest[2663:7557670] client: found peer: EprTNOFbJ45Lbb90mJwazA.wPmZ9g==
,2016-01-27 02:14:00.977 ThaliTest[2663:7557827] jxcore: connect EprTNOFbJ45Lbb90mJwazA.wPmZ9g==
,2016-01-27 02:14:00.979 ThaliTest[2663:7557827] client session: connect
,2016-01-27 02:14:00.980 ThaliTest[2663:7557827] client session: stateChange:0->1 EprTNOFbJ45Lbb90mJwazA.wPmZ9g==
,ok 121 Should be able to put doc without error

,2016-01-27 02:14:01.168 ThaliTest[2663:7557670] multipeer session: reset timer
2016-01-27 02:14:01.168 ThaliTest[2663:7557670] multipeer session: stop timer
2016-01-27 02:14:01.169 ThaliTest[2663:7557670] multipeer session: start timer: 0x166e34b0
2016-01-27 02:14:01.169 ThaliTest[2663:7557670] server session: connect
2016-01-27 02:14:01.169 ThaliTest[2663:7557670] server session: stateChange:0->1 EprTNOFbJ45Lbb90mJwazA
,2016-01-27 02:14:01.175 ThaliTest[2663:7557670] server: accepting invitation EprTNOFbJ45Lbb90mJwazA
,ok 122 1st change of local doc should contain local id
,
,2016-01-27 02:14:03.566 ThaliTest[2663:7558985] server session: connected
2016-01-27 02:14:03.567 ThaliTest[2663:7558985] server session: stateChange:1->2 EprTNOFbJ45Lbb90mJwazA
,2016-01-27 02:14:03.569 ThaliTest[2663:7557670] server relay: connected (to port: 64394)
,server bridge: new client socket

,2016-01-27 02:14:04.370 ThaliTest[2663:7559051] client session: connected
2016-01-27 02:14:04.370 ThaliTest[2663:7559051] client session: stateChange:1->2 EprTNOFbJ45Lbb90mJwazA.wPmZ9g==
2016-01-27 02:14:04.373 ThaliTest[2663:7559051] client session: fireConnectCallback: EprTNOFbJ45Lbb90mJwazA.wPmZ9g==
2016-01-27 02:14:04.373 ThaliTest[2663:7559051] jxcore: connect: success
,2016-01-27 02:14:04.380 ThaliTest[2663:7557670] client: relay established
2016-01-27 02:14:04.380 ThaliTest[2663:7557670] client: new accepted socket: 0x14540ca0
,client bridge: new client socket

client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket
,
,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed
,
,client bridge: socket closed
,
,client bridge: socket closed
,
,ok 123 1st change of remote doc should contain remote id

,client bridge: new client socket

,ok 124 Can update remote doc without error

,null

,{ ok: true,
  id: 'ca7e8ace-fb83-4a3f-b20b-34e6d665e926',
  rev: '2-97a9927bcaba14cb5cf0c46ca5b953cf' }

,client bridge: new client socket

,ok 125 Remote changes occur in strict order

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
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket
,
,ok 126 Local changes occur in strict order

,ok 127 2nd change of local doc should contain remote id

,# setup

,client bridge: new client socket

,client bridge: new client socket
,
,Now in TRM stop

State of this._isStarted: true

,About to call stopBroadcasting

,2016-01-27 02:14:25.209 ThaliTest[2663:7557827] jxcore: stopBroadcasting
,2016-01-27 02:14:25.210 ThaliTest[2663:7557827] THEMultipeerSession stopping peer
,2016-01-27 02:14:25.212 ThaliTest[2663:7557827] multipeer session: stop timer
,2016-01-27 02:14:25.212 ThaliTest[2663:7557827] client session: disconnect
,2016-01-27 02:14:25.213 ThaliTest[2663:7557827] client session: stateChange:2->0 EprTNOFbJ45Lbb90mJwazA.wPmZ9g==
,2016-01-27 02:14:25.269 ThaliTest[2663:7558977] server session: not connected EprTNOFbJ45Lbb90mJwazA
,2016-01-27 02:14:25.286 ThaliTest[2663:7557827] server session: disconnect
,2016-01-27 02:14:25.287 ThaliTest[2663:7557827] server session: stateChange:2->0 EprTNOFbJ45Lbb90mJwazA
,2016-01-27 02:14:25.290 ThaliTest[2663:7557827] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,2016-01-27 02:14:25.322 ThaliTest[2663:7557827] Error!: connect ECONNRESET
Stack:[{"_fileName":"net.js","_functionName":"$c","_lineNumber":"837","_columnNumber":"7","_msg":"    at $c@net.js:837:7"},{"_fileName":"net.js","_functionName":"$09","_lineNumber",:"829","_columnNumber":"13","_msg":"    at $09@net.js:829:13"},{"_fileName":"net.js","_functionName":"unknown","_lineNumber":"837","_columnNumber":"7","_msg":""}]
Uncaught Exception: Error: connect ECONNRESET

,[ { _fileName: 'net.js',
    _functionName: '$c',
    _lineNumber: '837',
,    _columnNumber: '7',
    _msg: '    at $c@net.js:837:7' },
  { _fileName: 'net.js',
    _functionName: '$09',
    _lineNumber: '829',
    _columnNumber: '13',
    _msg: '    at $09@net.js:829:13' },
  { _fileName: 'net.js',
    _functionName: 'u,nknown',
    _lineNumber: '837',
    _columnNumber: '7',
    _msg: '' },
  toString: [Function] ]

,****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****


```
