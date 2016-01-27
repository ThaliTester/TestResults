#### Test 57321924b5e4f25_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/57321924b5e4f25/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/E36719D4-DCBB-484B-B3BD-CC2F0D54A1A2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E36719D4-DCBB-484B-B3BD-CC2F0D54A1A2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/57321924b5e4f25/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/57321924b5e4f25/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61524"
,(lldb)     command script import "/tmp/E36719D4-DCBB-484B-B3BD-CC2F0D54A1A2/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-27 08:28:56.030 ThaliTest[2688:7628106] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8D512A21-56DC-4047-94D6-7C69BDEF0C36/Library/Cookies/Cookies.binarycookies
,2016-01-27 08:28:56.325 ThaliTest[2688:7628106] Apache Cordova native platform version 3.9.2 is starting.
2016-01-27 08:28:56.326 ThaliTest[2688:7628106] Multi-tasking -> Device: YES, App: YES
,2016-01-27 08:28:56.333 ThaliTest[2688:7628106] Unlimited access to network resources
,2016-01-27 08:28:56.342 ThaliTest[2688:7628106] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-27 08:29:01.025 ThaliTest[2688:7628106] Resetting plugins due to page load.
,2016-01-27 08:29:02.707 ThaliTest[2688:7628106] Finished load of: file:///var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/index.html
,2016-01-27 08:29:02.918 ThaliTest[2688:7628106] JXcore Cordova plugin initializing
2016-01-27 08:29:02.919 ThaliTest[2688:7628399] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

ok 7 secondPromise testValue

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

ok 15 (unnamed assert)

ok 16 should be equal

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

ok 36 should be equal

ok 37 should be equal

,# setup

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

,# setup

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

,# setup

,# #connect should call Mobile("Connect") and handle an error

,# teardown

,ok 48 should be equal

,ok 49 should be equal

# setup

,# should call Mobile("Disconnect") without an error

,# teardown

,ok 50 should be equal

ok 51 should be equal

,# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 52 should be equal

,ok 53 should be equal

# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-01-27 08:33:19.156 ThaliTest[2688:7628399] jxcore: startBroadcasting
,2016-01-27 08:33:19.165 ThaliTest[2688:7628399] server: starting 1453879999156.2688.w6MMiQ==
2016-01-27 08:33:19.166 ThaliTest[2688:7628399] multipeer session: start timer: 0x1b8c2ff0
2016-01-27 08:33:19.166 ThaliTest[2688:7628399] THEMultipeerSession initialized peer 1453879999156.2688
2016-01-27 08:33:19.166 ThaliTest[2688:7628399] jxcore: startBroadcasting: success
ok 54 Should be able to call startBroadcasting without error

2016-01-27 08:33:19.167 ThaliTest[2688:7628399] jxcore: stopBroadcasting
,2016-01-27 08:33:19.167 ThaliTest[2688:7628399] THEMultipeerSession stopping peer
2016-01-27 08:33:19.171 ThaliTest[2688:7628399] multipeer session: stop timer
2016-01-27 08:33:19.172 ThaliTest[2688:7628399] jxcore: stopBroadcasting: success
ok 55 Shoul,d be able to call stopBroadcasting without error

2016-01-27 08:33:19.173 ThaliTest[2688:7628399] jxcore: startBroadcasting
,2016-01-27 08:33:19.181 ThaliTest[2688:7628399] server: starting 1453879999172.2688.WVdluA==
2016-01-27 08:33:19.181 ThaliTest[2688:7628399] multipeer session: start timer: 0x197ba960
2016-01-27 08:33:19.182 ThaliTest[2688:7628399] THEMultipeerSession initialized peer 1453879999172.2688
2016-01-27 08:33:19.184 ThaliTest[2688:7628399] jxcore: startBroadcasting: success
ok 56 Should be able to call startBroadcasting without error

,2016-01-27 08:33:19.185 ThaliTest[2688:7628399] jxcore: stopBroadcasting
2016-01-27 08:33:19.189 ThaliTest[2688:7628399] THEMultipeerSession stopping peer
2016-01-27 08:33:19.190 ThaliTest[2688:7628399] multipeer session: stop timer
,2016-01-27 08:33:19.190 ThaliTest[2688:7628399] jxcore: stopBroadcasting: success
ok 57 Should be able to call stopBroadcasting without error

2016-01-27 08:33:19.194 ThaliTest[2688:7628399] jxcore: startBroadcasting
,2016-01-27 08:33:19.200 ThaliTest[2688:7628399] server: starting 1453879999193.2688.t8y/uQ==
2016-01-27 08:33:19.200 ThaliTest[2688:7628399] multipeer session: start timer: 0x1b8c5880
2016-01-27 08:33:19.200 ThaliTest[2688:7628399] THEMultipeerSession in,itialized peer 1453879999193.2688
2016-01-27 08:33:19.200 ThaliTest[2688:7628399] jxcore: startBroadcasting: success
ok 58 Should be able to call startBroadcasting without error

2016-01-27 08:33:19.201 ThaliTest[2688:7628399] jxcore: stopBroadcasting,
,2016-01-27 08:33:19.202 ThaliTest[2688:7628399] THEMultipeerSession stopping peer
2016-01-27 08:33:19.207 ThaliTest[2688:7628399] multipeer session: stop timer
2016-01-27 08:33:19.207 ThaliTest[2688:7628399] jxcore: stopBroadcasting: success
ok 59 Shoul,d be able to call stopBroadcasting without error

2016-01-27 08:33:19.208 ThaliTest[2688:7628399] jxcore: startBroadcasting
,2016-01-27 08:33:19.214 ThaliTest[2688:7628399] server: starting 1453879999208.2688.1BE4Ww==
2016-01-27 08:33:19.215 ThaliTest[2688:7628399] multipeer session: start timer: 0x197bcfb0
2016-01-27 08:33:19.215 ThaliTest[2688:7628399] THEMultipeerSession in,itialized peer 1453879999208.2688
2016-01-27 08:33:19.215 ThaliTest[2688:7628399] jxcore: startBroadcasting: success
ok 60 Should be able to call startBroadcasting without error

2016-01-27 08:33:19.216 ThaliTest[2688:7628399] jxcore: stopBroadcasting
2016-01-27 08:33:19.216 ThaliTest[2688:7628399] THEMultipeerSession stopping peer
2016-01-27 08:33:19.216 ThaliTest[2688:7628399] multipeer session: stop timer
2016-01-27 08:33:19.217 ThaliTest[2688:7628399] jxcore: stopBroadcasting: success
ok 61 Should be able to call stopBroadcasting without error

2016-01-27 08:33:19.218 ThaliTest[2688:7628399] jxcore: startBroadcasting
2016-01-27 08:33:19.222 ThaliTest[2688:7628399] server: starting 1453879999217.2688.xo2SOQ==
2016-01-27 08:33:19.222 ThaliTest[,2688:7628399] multipeer session: start timer: 0x197bd2a0
,2016-01-27 08:33:19.236 ThaliTest[2688:7628399] THEMultipeerSession initialized peer 1453879999217.2688
,2016-01-27 08:33:19.237 ThaliTest[2688:7628399] jxcore: startBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error
,
,2016-01-27 08:33:19.240 ThaliTest[2688:7628399] jxcore: stopBroadcasting
,2016-01-27 08:33:19.240 ThaliTest[2688:7628399] THEMultipeerSession stopping peer
,2016-01-27 08:33:19.241 ThaliTest[2688:7628399] multipeer session: stop timer
,2016-01-27 08:33:19.242 ThaliTest[2688:7628399] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error

,2016-01-27 08:33:19.247 ThaliTest[2688:7628399] jxcore: startBroadcasting
,2016-01-27 08:33:19.249 ThaliTest[2688:7628399] server: starting 1453879999246.2688.0PhQMw==
,2016-01-27 08:33:19.250 ThaliTest[2688:7628399] multipeer session: start timer: 0x1b8c4b90
2016-01-27 08:33:19.254 ThaliTest[2688:7628399] THEMultipeerSession initialized peer 1453879999246.2688
2016-01-27 08:33:19.254 ThaliTest[2688:7628399] jxcore: startBroadcasting: success
,ok 64 Should be able to call startBroadcasting without error

,2016-01-27 08:33:19.257 ThaliTest[2688:7628399] jxcore: stopBroadcasting
,2016-01-27 08:33:19.258 ThaliTest[2688:7628399] THEMultipeerSession stopping peer
,2016-01-27 08:33:19.258 ThaliTest[2688:7628399] multipeer session: stop timer
,2016-01-27 08:33:19.261 ThaliTest[2688:7628399] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error

,2016-01-27 08:33:19.264 ThaliTest[2688:7628399] jxcore: startBroadcasting
,2016-01-27 08:33:19.266 ThaliTest[2688:7628399] server: starting 1453879999263.2688.o+FNCg==
,2016-01-27 08:33:19.268 ThaliTest[2688:7628399] multipeer session: start timer: 0x1b8c70d0
,2016-01-27 08:33:19.272 ThaliTest[2688:7628399] THEMultipeerSession initialized peer 1453879999263.2688
,2016-01-27 08:33:19.273 ThaliTest[2688:7628399] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error

,2016-01-27 08:33:19.275 ThaliTest[2688:7628399] jxcore: stopBroadcasting
,2016-01-27 08:33:19.276 ThaliTest[2688:7628399] THEMultipeerSession stopping peer
,2016-01-27 08:33:19.277 ThaliTest[2688:7628399] multipeer session: stop timer
,2016-01-27 08:33:19.278 ThaliTest[2688:7628399] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,2016-01-27 08:33:19.282 ThaliTest[2688:7628399] jxcore: startBroadcasting
,2016-01-27 08:33:19.284 ThaliTest[2688:7628399] server: starting 1453879999281.2688.6YGQjA==
,2016-01-27 08:33:19.286 ThaliTest[2688:7628399] multipeer session: start timer: 0x1b8c79b0
,2016-01-27 08:33:19.290 ThaliTest[2688:7628399] THEMultipeerSession initialized peer 1453879999281.2688
,2016-01-27 08:33:19.292 ThaliTest[2688:7628399] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-01-27 08:33:19.294 ThaliTest[2688:7628399] jxcore: stopBroadcasting
,2016-01-27 08:33:19.294 ThaliTest[2688:7628399] THEMultipeerSession stopping peer
,2016-01-27 08:33:19.295 ThaliTest[2688:7628399] multipeer session: stop timer
,2016-01-27 08:33:19.297 ThaliTest[2688:7628399] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-01-27 08:33:19.300 ThaliTest[2688:7628399] jxcore: startBroadcasting
,2016-01-27 08:33:19.303 ThaliTest[2688:7628399] server: starting 1453879999300.2688.68/Sdg==
,2016-01-27 08:33:19.305 ThaliTest[2688:7628399] multipeer session: start timer: 0x197bd060
,2016-01-27 08:33:19.310 ThaliTest[2688:7628399] THEMultipeerSession initialized peer 1453879999300.2688
,2016-01-27 08:33:19.311 ThaliTest[2688:7628399] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-01-27 08:33:19.313 ThaliTest[2688:7628399] jxcore: stopBroadcasting
,2016-01-27 08:33:19.314 ThaliTest[2688:7628399] THEMultipeerSession stopping peer
,2016-01-27 08:33:19.314 ThaliTest[2688:7628399] multipeer session: stop timer
,2016-01-27 08:33:19.316 ThaliTest[2688:7628399] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

,2016-01-27 08:33:19.319 ThaliTest[2688:7628399] jxcore: startBroadcasting
,2016-01-27 08:33:19.321 ThaliTest[2688:7628399] server: starting 1453879999319.2688.lzf3dw==
,2016-01-27 08:33:19.323 ThaliTest[2688:7628399] multipeer session: start timer: 0x1b8c8af0
,2016-01-27 08:33:19.328 ThaliTest[2688:7628399] THEMultipeerSession initialized peer 1453879999319.2688
2016-01-27 08:33:19.328 ThaliTest[2688:7628399] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-01-27 08:33:19.330 ThaliTest[2688:7628399] jxcore: stopBroadcasting
,2016-01-27 08:33:19.331 ThaliTest[2688:7628399] THEMultipeerSession stopping peer
,2016-01-27 08:33:19.332 ThaliTest[2688:7628399] multipeer session: stop timer
,2016-01-27 08:33:19.334 ThaliTest[2688:7628399] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-27 08:33:20.020 ThaliTest[2688:7628399] jxcore: startBroadcasting
,2016-01-27 08:33:20.022 ThaliTest[2688:7628399] server: starting 1453880000020.2688.NBmjwQ==
2016-01-27 08:33:20.023 ThaliTest[2688:7628399] multipeer session: start timer: 0x197c1130
2016-01-27 08:33:20.023 ThaliTest[2688:7628399] THEMultipeerSession initialized peer 1453880000020.2688
,2016-01-27 08:33:20.026 ThaliTest[2688:7628399] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

2016-01-27 08:33:20.027 ThaliTest[2688:7628399] jxcore: startBroadcasting
2016-01-27 08:33:20.027 ThaliTest,[2688:7628399] jxcore: startBroadcasting: failure
ok 75 Cannot call startBroadcasting twice

2016-01-27 08:33:20.029 ThaliTest[2688:7628399] jxcore: stopBroadcasting
2016-01-27 08:33:20.029 ThaliTest[2688:7628399] THEMultipeerSession stopping peer
2016-01-27 08:33:20.029 ThaliTest[2688:7628399] multipeer session: stop timer
2016-01-27 08:33:20.029 ThaliTest[2688:7628399] jxcore: stopBroadcasting: success
ok 76 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-27 08:33:22.142 ThaliTest[2688:7628399] jxcore: startBroadcasting
,2016-01-27 08:33:22.144 ThaliTest[2688:7628399] server: starting 1453880002142.2688.hm3XLg==
2016-01-27 08:33:22.144 ThaliTest[2688:7628399] multipeer session: start timer: 0x197c6180
2016-01-27 08:33:22.144 ThaliTest[2688:7628399] THEMultipeerSession initialized peer 1453880002142.2688
2016-01-27 08:33:22.145 ThaliTest[2688:7628399] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-01-27 08:33:22.145 ThaliTest[2688:7628399] jxcore: connect foobar
2,016-01-27 08:33:22.146 ThaliTest[2688:7628399] client: unknown peer foobar
2016-01-27 08:33:22.146 ThaliTest[2688:7628399] jxcore: connect: fail: Unknown peer
,ok 78 Should not connect to a bad peer

2016-01-27 08:33:22.148 ThaliTest[2688:7628399] jxcore: stopBroadcasting
2016-01-27 08:33:22.148 ThaliTest[2688:7628399] THEMultipeerSession stopping peer
2016-01-27 08:33:22.148 ThaliTest[2688:7628399] multipeer, session: stop timer
2016-01-27 08:33:22.149 ThaliTest[2688:7628399] jxcore: stopBroadcasting: success
ok 79 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-27 08:33:22.507 ThaliTest[2688:7628399] jxcore: startBroadcasting
,2016-01-27 08:33:22.509 ThaliTest[2688:7628399] server: starting 1453880002507.2688.Jq/0oA==
2016-01-27 08:33:22.510 ThaliTest[2688:7628399] multipeer session: start timer: 0x1b8cdc30
2016-01-27 08:33:22.510 ThaliTest[2688:7628399] THEMultipeerSession in,itialized peer 1453880002507.2688
2016-01-27 08:33:22.510 ThaliTest[2688:7628399] jxcore: startBroadcasting: success
ok 80 Should be able to call startBroadcasting without error

2016-01-27 08:33:22.511 ThaliTest[2688:7628399] jxcore: disconnect
2016-,01-27 08:33:22.511 ThaliTest[2688:7628399] jxcore: disconnect: fail
,ok 81 Disconnect should fail to a non-existant peer 

2016-01-27 08:33:22.514 ThaliTest[2688:7628399] jxcore: stopBroadcasting
2016-01-27 08:33:22.514 ThaliTest[2688:7628399] THEMultipeerSession stopping peer
2016-01-27 08:33:22.514 ThaliTest[2688:7628,399] multipeer session: stop timer
2016-01-27 08:33:22.515 ThaliTest[2688:7628399] jxcore: stopBroadcasting: success
ok 82 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-27 08:33:23.008 ThaliTest[2688:7628399] jxcore: startBroadcasting
,2016-01-27 08:33:23.010 ThaliTest[2688:7628399] server: starting 1453880003008.2688.Ek/XhA==
2016-01-27 08:33:23.010 ThaliTest[2688:7628399] multipeer session: start timer: 0x197cc800
2016-01-27 08:33:23.010 ThaliTest[2688:7628399] THEMultipeerSession initialized peer 1453880003008.2688
2016-01-27 08:33:23.010 ThaliTest[2688:7628399] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-27 08:33:23.968 ThaliTest[2688:7628106] client: found peer: 1453880004056.3183.QThslw==
2016-01-27 08:33:23.969 ThaliTest[2688:7628399] jxcore: connect 1453880004056.3183.QThslw==
2016-01-27 08:33:23.969 ThaliTest[2688:7628399] client session: connect
2016-01-27 08:33:23.970 ThaliTest[2688:7628399] client session: stateChange:0->1 1453880004056.3183.QThslw==
,2016-01-27 08:33:24.510 ThaliTest[2688:7628106] multipeer session: reset timer
2016-01-27 08:33:24.510 ThaliTest[2688:7628106] multipeer session: stop timer
2016-01-27 08:33:24.510 ThaliTest[2688:7628106] multipeer session: start timer: 0x197cc800
2016-01-27 08:33:24.511 ThaliTest[2688:7628106] server session: connect
2016-01-27 08:33:24.511 ThaliTest[2688:7628106] server session: stateChange:0->1 1453880004056.3183
,2016-01-27 08:33:24.517 ThaliTest[2688:7628106] server: accepting invitation 1453880004056.3183
,2016-01-27 08:33:26.798 ThaliTest[2688:7629171] server session: connected
,2016-01-27 08:33:26.798 ThaliTest[2688:7629171] server session: stateChange:1->2 1453880004056.3183
,2016-01-27 08:33:26.803 ThaliTest[2688:7628106] server relay: socket disconnected
2016-01-27 08:33:26.803 ThaliTest[2688:7628106] server relay: 0x1b8d4500 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-27 08:33:26.934 ThaliTest[2688:7629170] server session: not connected 1453880004056.3183
,2016-01-27 08:33:27.061 ThaliTest[2688:7629168] client session: connected
2016-01-27 08:33:27.062 ThaliTest[2688:7629168] client session: stateChange:1->2 1453880004056.3183.QThslw==
,2016-01-27 08:33:27.065 ThaliTest[2688:7629168] client session: fireConnectCallback: 1453880004056.3183.QThslw==
2016-01-27 08:33:27.065 ThaliTest[2688:7629168] jxcore: connect: success
ok 84 Should be able to connect without error

,ok 85 Port should be within range

,2016-01-27 08:33:27.067 ThaliTest[2688:7628399] jxcore: disconnect
2016-01-27 08:33:27.067 ThaliTest[2688:7628399] client session: disconnectFromPeer: 1453880004056.3183.QThslw==
2016-01-27 08:33:27.067 ThaliTest[2688:7628399] client session: disconnect
2016-01-27 08:33:27.068 ThaliTest[2688:7628399] client session: stateChange:2->0 1453880004056.3183.QThslw==
,2016-01-27 08:33:27.131 ThaliTest[2688:7628399] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-27 08:33:27.387 ThaliTest[2688:7628399] jxcore: stopBroadcasting
2016-01-27 08:33:27.388 ThaliTest[2688:7628399] THEMultipeerSession stopping peer
2016-01-27 08:33:27.388 ThaliTest[2688:7628399] multipeer session: stop timer
2016-01-27 08:33:27.388 ThaliTest[2688:7628399] server session: disconnect
2016-01-27 08:33:27.388 ThaliTest[2688:7628399] server session: stateChange:2->0 1453880004056.3183
2016-01-27 08:33:27.389 ThaliTest[2688:7628399] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-27 08:33:27.957 ThaliTest[2688:7628399] jxcore: startBroadcasting
,2016-01-27 08:33:27.960 ThaliTest[2688:7628399] server: starting 1453880007957.2688.CgYDVQ==
2016-01-27 08:33:27.960 ThaliTest[2688:7628399] multipeer session: start timer: 0x1b8da940
2016-01-27 08:33:27.960 ThaliTest[2688:7628399] THEMultipeerSession initialized peer 1453880007957.2688
2016-01-27 08:33:27.961 ThaliTest[2688:7628399] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-01-27 08:33:29.224 ThaliTest[2688:7628106] client: found peer: 1453880009033.3183.xw7pIw==
2016-01-27 08:33:29.225 ThaliTest[2688:7628399] jxcore: connect 1453880009033.3183.xw7pIw==
2016-01-27 08:33:29.225 ThaliTest[2688:7628399] client session: co,nnect
2016-01-27 08:33:29.225 ThaliTest[2688:7628399] client session: stateChange:0->1 1453880009033.3183.xw7pIw==
,2016-01-27 08:33:29.675 ThaliTest[2688:7628106] multipeer session: reset timer
2016-01-27 08:33:29.675 ThaliTest[2688:7628106] multipeer session: stop timer
2016-01-27 08:33:29.675 ThaliTest[2688:7628106] multipeer session: start timer: 0x1b8da940
2016-01-27 08:33:29.675 ThaliTest[2688:7628106] server session: connect
2016-01-27 08:33:29.675 ThaliTest[2688:7628106] server session: stateChange:0->1 1453880009033.3183
,2016-01-27 08:33:29.680 ThaliTest[2688:7628106] server: accepting invitation 1453880009033.3183
,2016-01-27 08:33:32.033 ThaliTest[2688:7629171] server session: connected
2016-01-27 08:33:32.033 ThaliTest[2688:7629171] server session: stateChange:1->2 1453880009033.3183
,2016-01-27 08:33:32.040 ThaliTest[2688:7629167] client session: connected
2016-01-27 08:33:32.040 ThaliTest[2688:7629167] client session: stateChange:1->2 1453880009033.3183.xw7pIw==
,2016-01-27 08:33:32.047 ThaliTest[2688:7628106] server relay: socket disconnected
,2016-01-27 08:33:32.048 ThaliTest[2688:7628106] server relay: 0x17688400 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-27 08:33:32.051 ThaliTest[2688:7629167] client session: fireConnectCallback: 1453880009033.3183.xw7pIw==
2016-01-27 08:33:32.051 ThaliTest[2688:7629167] jxcore: connect: success
,ok 88 Should be able to connect without error

,ok 89 Port should be within range

,2016-01-27 08:33:32.054 ThaliTest[2688:7628399] jxcore: connect 1453880009033.3183.xw7pIw==
2016-01-27 08:33:32.055 ThaliTest[2688:7628399] client: already connect(ing/ed) to 1453880009033.3183.xw7pIw==
2016-01-27 08:33:32.055 ThaliTest[2688:7628399] jxc,ore: connect: fail: Aleady connecting
ok 90 Should fail on double connect

2016-01-27 08:33:32.056 ThaliTest[2688:7628399] jxcore: disconnect
2016-01-27 08:33:32.056 ThaliTest[2688:7628399] client session: disconnectFromPeer: 1453880009033.3183.xw7pIw=,=
2016-01-27 08:33:32.056 ThaliTest[2688:7628399] client session: disconnect
2016-01-27 08:33:32.056 ThaliTest[2688:7628399] client session: stateChange:2->0 1453880009033.3183.xw7pIw==
,2016-01-27 08:33:32.072 ThaliTest[2688:7629172] server session: not connected 1453880009033.3183
,2016-01-27 08:33:32.126 ThaliTest[2688:7628399] jxcore: disconnect: success
,ok 91 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-27 08:33:32.155 ThaliTest[2688:7628399] jxcore: stopBroadcasting
,2016-01-27 08:33:32.155 ThaliTest[2688:7628399] THEMultipeerSession stopping peer
,2016-01-27 08:33:32.156 ThaliTest[2688:7628399] multipeer session: stop timer
,2016-01-27 08:33:32.157 ThaliTest[2688:7628399] server session: disconnect
,2016-01-27 08:33:32.158 ThaliTest[2688:7628399] server session: stateChange:2->0 1453880009033.3183
,2016-01-27 08:33:32.160 ThaliTest[2688:7628399] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,
,# teardown

,2016-01-27 08:33:32.638 ThaliTest[2688:7628399] jxcore: startBroadcasting
,2016-01-27 08:33:32.640 ThaliTest[2688:7628399] server: starting 1453880012638.2688.ZPC0Yg==
2016-01-27 08:33:32.640 ThaliTest[2688:7628399] multipeer session: start timer: 0x1765d940
2016-01-27 08:33:32.640 ThaliTest[2688:7628399] THEMultipeerSession in,itialized peer 1453880012638.2688
2016-01-27 08:33:32.640 ThaliTest[2688:7628399] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-01-27 08:33:33.408 ThaliTest[2688:7628106] client: found peer: 1453880013676.3183.rPNufw==
2016-01-27 08:33:33.409 ThaliTest[2688:7628399] jxcore: connect 1453880013676.3183.rPNufw==
2016-01-27 08:33:33.409 ThaliTest[2688:7628399] client session: co,nnect
2016-01-27 08:33:33.409 ThaliTest[2688:7628399] client session: stateChange:0->1 1453880013676.3183.rPNufw==
,2016-01-27 08:33:33.881 ThaliTest[2688:7628106] multipeer session: reset timer
2016-01-27 08:33:33.881 ThaliTest[2688:7628106] multipeer session: stop timer
2016-01-27 08:33:33.882 ThaliTest[2688:7628106] multipeer session: start timer: 0x1765d940
2016-01-27 08:33:33.882 ThaliTest[2688:7628106] server session: connect
2016-01-27 08:33:33.882 ThaliTest[2688:7628106] server session: stateChange:0->1 1453880013676.3183
2016-01-27 08:33:33.887 ThaliTest[2688:7628106] server: accepting invitation 1453880013676.3183
,2016-01-27 08:33:36.420 ThaliTest[2688:7629171] client session: connected
2016-01-27 08:33:36.421 ThaliTest[2688:7629171] client session: stateChange:1->2 1453880013676.3183.rPNufw==
2016-01-27 08:33:36.418 ThaliTest[2688:7629167] server session: connect,ed
,2016-01-27 08:33:36.421 ThaliTest[2688:7629167] server session: stateChange:1->2 1453880013676.3183
2016-01-27 08:33:36.427 ThaliTest[2688:7629171] client session: fireConnectCallback: 1453880013676.3183.rPNufw==
,2016-01-27 08:33:36.427 ThaliTest[2688:7629171] jxcore: connect: success
ok 93 Should be able to connect without error

ok 94 Port should be within range

2016-01-27 08:33:36.432 ThaliTest[2688:7628399] jxcore: disconnect
2016-01-27 08:33:36.432 ThaliTest[2688:7628399] client session: disconnectFromPeer: 1453880013676.3183.rPNufw==
2016-01-27 08:33:36.432 ThaliTest[2688:7628399] client session: disconnect
2016-01-27 08:33:36.432 ThaliTest[2688:7628399] client session: stateChange:2->0 1453880013676.,3183.rPNufw==
,2016-01-27 08:33:36.436 ThaliTest[2688:7628106] server relay: socket disconnected
2016-01-27 08:33:36.437 ThaliTest[2688:7628106] server relay: 0x197d8130 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-27 08:33:36.444 ThaliTest[2688:7628399] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

2016-01-27 08:33:36.445 ThaliTest[2688:7628399] jxcore: disconnect
2016-01-27 08:33:36.445 ThaliTest[2688:7628399] jxcore: disconnect: fail
ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-27 08:33:36.474 ThaliTest[2688:7629252] server session: not connected 1453880013676.3183
,calling stopBroadcasting

2016-01-27 08:33:36.907 ThaliTest[2688:7628399] jxcore: stopBroadcasting
2016-01-27 08:33:36.907 ThaliTest[2688:7628399] THEMultipeerSession stopping peer
,2016-01-27 08:33:36.908 ThaliTest[2688:7628399] multipeer session: stop timer
2016-01-27 08:33:36.908 ThaliTest[2688:7628399] server session: disconnect
,2016-01-27 08:33:36.908 ThaliTest[2688:7628399] server session: stateChange:2->0 1453880013676.3183
2016-01-27 08:33:36.909 ThaliTest[2688:7628399] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 64602

,2016-01-27 08:33:38.839 ThaliTest[2688:7628399] jxcore: startBroadcasting
,2016-01-27 08:33:38.849 ThaliTest[2688:7628399] server: starting 1453880018838.2688.8mHVeA==
,2016-01-27 08:33:38.850 ThaliTest[2688:7628399] multipeer session: start timer: 0x1b8c58c0
,2016-01-27 08:33:38.854 ThaliTest[2688:7628399] THEMultipeerSession initialized peer 1453880018838.2688
,2016-01-27 08:33:38.858 ThaliTest[2688:7628399] jxcore: startBroadcasting: success
2016-01-27 08:33:38.859 ThaliTest[2688:7628106] client: found peer: 1453880013676.3183.rPNufw==
ok 97 Should be able to call startBroadcasting without error

,2016-01-27 08:33:38.862 ThaliTest[2688:7628399] jxcore: connect 1453880013676.3183.rPNufw==
,2016-01-27 08:33:38.863 ThaliTest[2688:7628399] client session: connect
,2016-01-27 08:33:38.864 ThaliTest[2688:7628399] client session: stateChange:0->1 1453880013676.3183.rPNufw==
,2016-01-27 08:33:40.096 ThaliTest[2688:7628106] client: lost peer: 1453880013676.3183.rPNufw==
2016-01-27 08:33:40.096 ThaliTest[2688:7628106] client session: onPeerLost: 1453880013676.3183.rPNufw==
2016-01-27 08:33:40.097 ThaliTest[2688:7628106] client session: onLinkFailure: 1453880013676.3183.rPNufw==
2016-01-27 08:33:40.097 ThaliTest[2688:7628106] client session: disconnect
2016-01-27 08:33:40.097 ThaliTest[2688:7628106] client session: stateChange:1->0 1453880013676.3183.rPNufw==
2016-01-27 08:33:,40.097 ThaliTest[2688:7628106] client session: fireConnectCallback: 1453880013676.3183.rPNufw==
2016-01-27 08:33:40.097 ThaliTest[2688:7628106] jxcore: connect: fail: Peer disconnected
2016-01-27 08:33:40.098 ThaliTest[2688:7628106] client: found peer: 1,453880019553.3183.US4PAw==
2016-01-27 08:33:40.099 ThaliTest[2688:7628399] jxcore: connect 1453880019553.3183.US4PAw==
2016-01-27 08:33:40.099 ThaliTest[2688:7628399] client session: connect
2016-01-27 08:33:40.100 ThaliTest[2688:7628399] client session,: stateChange:0->1 1453880019553.3183.US4PAw==
,2016-01-27 08:33:40.238 ThaliTest[2688:7628106] multipeer session: reset timer
2016-01-27 08:33:40.238 ThaliTest[2688:7628106] multipeer session: stop timer
2016-01-27 08:33:40.238 ThaliTest[2688:7628106] multipeer session: start timer: 0x1b8c58c0
,2016-01-27 08:33:40.238 ThaliTest[2688:7628106] server session: connect
2016-01-27 08:33:40.241 ThaliTest[2688:7628106] server session: stateChange:0->1 1453880019553.3183
,2016-01-27 08:33:40.247 ThaliTest[2688:7628106] server: accepting invitation 1453880019553.3183
,2016-01-27 08:33:41.104 ThaliTest[2688:7628399] jxcore: connect 1453880013676.3183.rPNufw==
2016-01-27 08:33:41.104 ThaliTest[2688:7628399] client: connect: unreachable 1453880013676.3183.rPNufw==
2016-01-27 08:33:41.104 ThaliTest[2688:7628399] jxcore: c,onnect: fail: Peer unreachable
,2016-01-27 08:33:42.723 ThaliTest[2688:7629167] client session: connected
2016-01-27 08:33:42.723 ThaliTest[2688:7629167] client session: stateChange:1->2 1453880019553.3183.US4PAw==
,2016-01-27 08:33:42.731 ThaliTest[2688:7629167] client session: fireConnectCallback: 1453880019553.3183.US4PAw==
2016-01-27 08:33:42.732 ThaliTest[2688:7629167] jxcore: connect: success
ok 98 Should be able to connect without error

ok 99 Port should be within range

,2016-01-27 08:33:42.737 ThaliTest[2688:7628106] client: relay established
2016-01-27 08:33:42.737 ThaliTest[2688:7628106] client: new accepted socket: 0x1977cbb0
,2016-01-27 08:33:42.744 ThaliTest[2688:7629167] server session: connected
2016-01-27 08:33:42.744 ThaliTest[2688:7629167] server session: stateChange:1->2 1453880019553.3183
,2016-01-27 08:33:42.812 ThaliTest[2688:7628106] server relay: connected (to port: 64602)
,data in 5475

,data in 20805

,data in 27304

,data in 37230

,data in 44895

,data in 56940

,data in 60225

,data in 67890

,data in 73365

,data in 81030

,data in 85410

,data in 91980

,data in 100740

,data in 106215

,data in 118260

,data in 125925

,data in 131072

,ok 100 the test messages should be equal

,2016-01-27 08:33:43.479 ThaliTest[2688:7628399] jxcore: disconnect
2016-01-27 08:33:43.479 ThaliTest[2688:7628399] client session: disconnectFromPeer: 1453880019553.3183.US4PAw==
2016-01-27 08:33:43.480 ThaliTest[2688:7628399] client session: disconnect
2016-01-27 08:33:43.480 ThaliTest[2688:7628399] client session: stateChange:2->0 1453880019553.3183.US4PAw==
,2016-01-27 08:33:43.486 ThaliTest[2688:7628399] jxcore: disconnect: success
ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-27 08:33:43.810 ThaliTest[2688:7629168] server session: not connected 1453880019553.3183
,calling stopBroadcasting

2016-01-27 08:33:44.174 ThaliTest[2688:7628399] jxcore: stopBroadcasting
2016-01-27 08:33:44.174 ThaliTest[2688:7628399] THEMultipeerSession stopping peer
2016-01-27 08:33:44.174 ThaliTest[2688:7628399] multipeer session: stop, timer
2016-01-27 08:33:44.175 ThaliTest[2688:7628399] server session: disconnect
2016-01-27 08:33:44.175 ThaliTest[2688:7628399] server session: stateChange:2->0 1453880019553.3183
,2016-01-27 08:33:44.178 ThaliTest[2688:7628399] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 64609

,2016-01-27 08:33:45.246 ThaliTest[2688:7628399] jxcore: startBroadcasting
,2016-01-27 08:33:45.248 ThaliTest[2688:7628399] server: starting 1453880025246.2688.urxjdw==
,2016-01-27 08:33:45.248 ThaliTest[2688:7628399] multipeer session: start timer: 0x197d86a0
,2016-01-27 08:33:45.249 ThaliTest[2688:7628399] THEMultipeerSession initialized peer 1453880025246.2688
2016-01-27 08:33:45.249 ThaliTest[2688:7628399] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-01-27 08:33:46.403 ThaliTest[2688:7628106] client: found peer: 1453880026274.3183.HGmA8A==
[{"peerIdentifier":"1453880026274.3183.HGmA8A==","peerName":"(null)","peerAvailable":true}]

,2016-01-27 08:33:46.405 ThaliTest[2688:7628399] jxcore: connect 1453880026274.3183.HGmA8A==
2016-01-27 08:33:46.405 ThaliTest[2688:7628399] client session: connect
2016-01-27 08:33:46.405 ThaliTest[2688:7628399] client session: stateChange:0->1 1453880026274.3183.HGmA8A==
,2016-01-27 08:33:47.434 ThaliTest[2688:7628106] multipeer session: reset timer
2016-01-27 08:33:47.434 ThaliTest[2688:7628106] multipeer session: stop timer
2016-01-27 08:33:47.434 ThaliTest[2688:7628106] multipeer session: start timer: 0x197d86a0
2016-,01-27 08:33:47.434 ThaliTest[2688:7628106] server session: connect
2016-01-27 08:33:47.435 ThaliTest[2688:7628106] server session: stateChange:0->1 1453880026274.3183
2016-01-27 08:33:47.439 ThaliTest[2688:7628106] server: accepting invitation 1453880026,274.3183
,2016-01-27 08:33:48.892 ThaliTest[2688:7629168] client session: connected
2016-01-27 08:33:48.892 ThaliTest[2688:7629168] client session: stateChange:1->2 1453880026274.3183.HGmA8A==
,2016-01-27 08:33:48.914 ThaliTest[2688:7629170] client session: fireConnectCallback: 1453880026274.3183.HGmA8A==
2016-01-27 08:33:48.914 ThaliTest[2688:7629170] jxcore: connect: success
,ok 103 Should be able to connect without error

,ok 104 Port should be within range

,ok 105 First connect should succeed

,2016-01-27 08:33:48.928 ThaliTest[2688:7628106] client: relay established
2016-01-27 08:33:48.928 ThaliTest[2688:7628106] client: new accepted socket: 0x1977cbb0
,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-01-27 08:33:49.016 ThaliTest[2688:7628106] client: socket closed
2016-01-27 08:33:49.017 ThaliTest[2688:7628106] client relay: socket disconnected
2016-01-27 08:33:49.017 ThaliTest[2688:7628106] client relay: 0x1977cbb0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-27 08:33:49.017 ThaliTest[2688:7628106] client session: socket closed: 1453880026274.3183.HGmA8A==
2016-01-27 ,08:33:49.017 ThaliTest[2688:7628106] client session: onLinkFailure: 1453880026274.3183.HGmA8A==
2016-01-27 08:33:49.017 ThaliTest[2688:7628106] client session: disconnect
2016-01-27 08:33:49.017 ThaliTest[2688:7628106] client session: stateChange:2->0 14,53880026274.3183.HGmA8A==
,2016-01-27 08:33:49.024 ThaliTest[2688:7628106] client session: fireConnectionErrorEvent: 1453880026274.3183.HGmA8A==
2016-01-27 08:33:49.025 ThaliTest[2688:7628399] jxcore: connect 1453880026274.3183.HGmA8A==
2016-01-27 08:33:49.026 ThaliTest[2688:76283,99] client session: connect
2016-01-27 08:33:49.026 ThaliTest[2688:7628399] client session: stateChange:0->1 1453880026274.3183.HGmA8A==
,2016-01-27 08:33:49.859 ThaliTest[2688:7629170] server session: connected
2016-01-27 08:33:49.860 ThaliTest[2688:7629170] server session: stateChange:1->2 1453880026274.3183
,2016-01-27 08:33:49.867 ThaliTest[2688:7628106] server relay: connected (to port: 64609)
,2016-01-27 08:33:50.215 ThaliTest[2688:7629170] server session: not connected 1453880026274.3183
,2016-01-27 08:33:51.258 ThaliTest[2688:7628106] multipeer session: reset timer
2016-01-27 08:33:51.258 ThaliTest[2688:7628106] multipeer session: stop timer
2016-01-27 08:33:51.258 ThaliTest[2688:7628106] multipeer session: start timer: 0x197d86a0
2016-01-27 08:33:51.258 ThaliTest[2688:7628106] server: disconnecting to refresh session (1453880026274.3183)
2016-01-27 08:33:51.258 ThaliTest[2688:7628106] server session: disconnect
2016-01-27 08:33:51.258 ThaliTest[2688:7628106] server session: stateChange:2->0 1453880026274.3183
,2016-01-27 08:33:51.262 ThaliTest[2688:7628106] server session: connect
2016-01-27 08:33:51.262 ThaliTest[2688:7628106] server session: stateChange:0->1 1453880026274.3183
,2016-01-27 08:33:51.267 ThaliTest[2688:7628106] server: accepting invitation 1453880026274.3183
,2016-01-27 08:33:51.436 ThaliTest[2688:7629247] client session: connected
,2016-01-27 08:33:51.436 ThaliTest[2688:7629247] client session: stateChange:1->2 1453880026274.3183.HGmA8A==
,2016-01-27 08:33:51.475 ThaliTest[2688:7629247] client session: fireConnectCallback: 1453880026274.3183.HGmA8A==
2016-01-27 08:33:51.475 ThaliTest[2688:7629247] jxcore: connect: success
,ok 108 Should be able to connect without error

,ok 109 Port should be within range

,ok 110 Second connect should succeed

,2016-01-27 08:33:51.490 ThaliTest[2688:7628106] client: relay established
2016-01-27 08:33:51.490 ThaliTest[2688:7628106] client: new accepted socket: 0x18b0dcd0
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-01-27 08:33:51.581 ThaliTest[2688:7628106] client: socket closed
2016-01-27 08:33:51.581 ThaliTest[2688:7628106] client relay: socket disconnected
2016-01-27 08:33:51.581 ThaliTest[2688:7628106] client relay: 0x18b0dcd0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-27 08:33:51.581 ThaliTest[2688:7628106] client session: socket closed: 1453880026274.3183.HGmA8A==
2016-01-27 ,08:33:51.581 ThaliTest[2688:7628106] client session: onLinkFailure: 1453880026274.3183.HGmA8A==
2016-01-27 08:33:51.581 ThaliTest[2688:7628106] client session: disconnect
2016-01-27 08:33:51.581 ThaliTest[2688:7628106] client session: stateChange:2->0 1453880026274.3183.HGmA8A==
,2016-01-27 08:33:51.586 ThaliTest[2688:7628106] client session: fireConnectionErrorEvent: 1453880026274.3183.HGmA8A==
,2016-01-27 08:33:53.598 ThaliTest[2688:7629252] server session: connected
2016-01-27 08:33:53.599 ThaliTest[2688:7629252] server session: stateChange:1->2 1453880026274.3183
,2016-01-27 08:33:53.654 ThaliTest[2688:7628106] server relay: connected (to port: 64609)
,2016-01-27 08:33:53.759 ThaliTest[2688:7629252] server session: not connected 1453880026274.3183
,calling stopBroadcasting

,2016-01-27 08:33:54.155 ThaliTest[2688:7628399] jxcore: stopBroadcasting
2016-01-27 08:33:54.155 ThaliTest[2688:7628399] THEMultipeerSession stopping peer
2016-01-27 08:33:54.155 ThaliTest[2688:7628399] multipeer session: stop timer
2016-01-27 08:33:54.156 ThaliTest[2688:7628399] server session: disconnect
2016-01-27 08:33:54.156 ThaliTest[2688:7628399] server session: stateChange:2->0 1453880026274.3183
,2016-01-27 08:33:54.159 ThaliTest[2688:7628399] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/8D512A21-56DC-4047-94D6-7C69BDEF0C36/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-01-27 08:33:55.648 ThaliTest[2688:7628399] jxcore: startBroadcasting
,2016-01-27 08:33:55.650 ThaliTest[2688:7628399] server: starting 9XwvBGLtp95yQVbibKCgjA.z0dDgw==
2016-01-27 08:33:55.651 ThaliTest[2688:7628399] multipeer session: start timer: 0x1977ce00
2016-01-27 08:33:55.651 ThaliTest[2688:7628399] THEMultipeerSession initialized peer 9XwvBGLtp95yQVbibKCgjA
2016-01-27 08:33:55.651 ThaliTest[2688:7628399] jxcore: startBroadcasting: success
ok 114 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 115 stopping event sh,ould occur in right order

About to call stopBroadcasting

2016-01-27 08:33:55.652 ThaliTest[2688:7628399] jxcore: stopBroadcasting
2016-01-27 08:33:55.653 ThaliTest[2688:7628399] THEMultipeerSession stopping peer
,2016-01-27 08:33:55.653 ThaliTest[2688:7628399] multipeer session: stop timer
2016-01-27 08:33:55.657 ThaliTest[2688:7628399] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

ok 116 stopped event should occur in right order

mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/8D512A21-56DC-4047-94D6-7C69BDEF0C36/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-27 08:33:56.877 ThaliTest[2688:7628399] jxcore: startBroadcasting
,2016-01-27 08:33:56.879 ThaliTest[2688:7628399] server: starting 9XwvBGLtp95yQVbibKCgjA.E/KzPg==
2016-01-27 08:33:56.880 ThaliTest[2688:7628399] multipeer session: start timer: 0x19467950
2016-01-27 08:33:56.880 ThaliTest[2688:7628399] THEMultipeerSession initialized peer 9XwvBGLtp95yQVbibKCgjA
2016-01-27 08:33:56.880 ThaliTest[2688:7628399] jxcore: startBroadcasting: success
ok 117 getDeviceIdentity should not return an error

ok 118 deviceName should not be null

Now in TRM stop

State of this._,isStarted: true

About to call stopBroadcasting

2016-01-27 08:33:56.882 ThaliTest[2688:7628399] jxcore: stopBroadcasting
2016-01-27 08:33:56.882 ThaliTest[2688:7628399] THEMultipeerSession stopping peer
,2016-01-27 08:33:56.882 ThaliTest[2688:7628399] multipeer session: stop timer
2016-01-27 08:33:56.886 ThaliTest[2688:7628399] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/8D512A21-56DC-4047-94D6-7C69BDEF0C36/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-27 08:34:01.674 ThaliTest[2688:7628399] jxcore: startBroadcasting
,2016-01-27 08:34:01.676 ThaliTest[2688:7628399] server: starting 9XwvBGLtp95yQVbibKCgjA.xSu9ag==
,2016-01-27 08:34:01.678 ThaliTest[2688:7628399] multipeer session: start timer: 0x18b51310
,2016-01-27 08:34:01.682 ThaliTest[2688:7628399] THEMultipeerSession initialized peer 9XwvBGLtp95yQVbibKCgjA
,2016-01-27 08:34:01.683 ThaliTest[2688:7628399] jxcore: startBroadcasting: success
,ok 119 getDeviceIdentity should not return an error

,ok 120 deviceName should not be null

,2016-01-27 08:34:02.114 ThaliTest[2688:7628106] client: found peer: HLQyXwiCWbGpHCzR88ORyQ.TdpHJg==
,2016-01-27 08:34:07.488 ThaliTest[2688:7628106] multipeer session: reset timer
2016-01-27 08:34:07.488 ThaliTest[2688:7628106] multipeer session: stop timer
2016-01-27 08:34:07.488 ThaliTest[2688:7628106] multipeer session: start timer: 0x18b51310
,2016-01-27 08:34:07.489 ThaliTest[2688:7628106] server session: connect
2016-01-27 08:34:07.489 ThaliTest[2688:7628106] server session: stateChange:0->1 HLQyXwiCWbGpHCzR88ORyQ
,2016-01-27 08:34:07.494 ThaliTest[2688:7628106] server: accepting invitation HLQyXwiCWbGpHCzR88ORyQ
,2016-01-27 08:34:07.504 ThaliTest[2688:7628399] jxcore: connect HLQyXwiCWbGpHCzR88ORyQ.TdpHJg==
,2016-01-27 08:34:07.507 ThaliTest[2688:7628399] client session: connect
,2016-01-27 08:34:07.508 ThaliTest[2688:7628399] client session: stateChange:0->1 HLQyXwiCWbGpHCzR88ORyQ.TdpHJg==
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-01-27 08:34:09.983 ThaliTest[2688:7629170] server session: connected
2016-01-27 08:34:09.983 ThaliTest[2688:7629170] server session: stateChange:1->2 HLQyXwiCWbGpHCzR88ORyQ
,2016-01-27 08:34:10.041 ThaliTest[2688:7628106] server relay: connected (to port: 64624)
,server bridge: new client socket

,2016-01-27 08:34:10.163 ThaliTest[2688:7629368] client session: connected
2016-01-27 08:34:10.163 ThaliTest[2688:7629368] client session: stateChange:1->2 HLQyXwiCWbGpHCzR88ORyQ.TdpHJg==
,2016-01-27 08:34:10.173 ThaliTest[2688:7629168] client session: fireConnectCallback: HLQyXwiCWbGpHCzR88ORyQ.TdpHJg==
2016-01-27 08:34:10.173 ThaliTest[2688:7629168] jxcore: connect: success
,2016-01-27 08:34:10.180 ThaliTest[2688:7628106] client: relay established
2016-01-27 08:34:10.180 ThaliTest[2688:7628106] client: new accepted socket: 0x18d16f10
,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket
,
,ok 123 1st change of remote doc should contain remote id

,ok 124 Can update remote doc without error

,null

,{ ok: true,
  id: '3b51e013-13fb-4e9a-9550-1a0b22386c57',
  rev: '2-0fb00d6fc332411e6f72db32baa00de7' }

,ok 125 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed
,
,client bridge: new client socket
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
,
,client bridge: socket closed
,
,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed
,
,ok 126 Local changes occur in strict order

ok 127 2nd change of local doc should contain remote id

,client bridge: new client socket

,# setup

,client bridge: new client socket

,Now in TRM stop

,State of this._isStarted: true

About to call stopBroadcasting

,2016-01-27 08:34:29.286 ThaliTest[2688:7628399] jxcore: stopBroadcasting
,2016-01-27 08:34:29.286 ThaliTest[2688:7628399] THEMultipeerSession stopping peer
,2016-01-27 08:34:29.287 ThaliTest[2688:7628399] multipeer session: stop timer
,2016-01-27 08:34:29.288 ThaliTest[2688:7628399] client session: disconnect
,2016-01-27 08:34:29.290 ThaliTest[2688:7628399] client session: stateChange:2->0 HLQyXwiCWbGpHCzR88ORyQ.TdpHJg==
,2016-01-27 08:34:29.358 ThaliTest[2688:7628399] server session: disconnect
,2016-01-27 08:34:29.364 ThaliTest[2688:7628399] server session: stateChange:2->0 HLQyXwiCWbGpHCzR88ORyQ
,2016-01-27 08:34:29.375 ThaliTest[2688:7628399] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,# #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

client bridge: socket closed
,
,server bridge: socket closed

,client bridge: socket closed
,
,2016-01-27 08:34:29.469 ThaliTest[2688:7628399] Error!: stream.push() after EOF
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/,node_modules/readable-stream/lib/_stream_readable.js","_functionName":"readableAddChunk","_lineNumber":"187","_columnNumber":"15","_msg":"    at readableAddChunk@/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTe,st.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js:187:15"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_mod,ules/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js","_functionName":"Readable.prototype.push","_lineNumber":"165","_columnNumber":"10","_msg":"    at Readable.prototype.push@/private/var/mobile/Containers/Bundle/Applicat,ion/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js:165:10"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41,F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js","_functionName":"Multiplex.prototype._send","_lineNumber":"197","_columnNumber":"13","_msg":"    at Multiplex.prototype._send@/private/var/mobile/Containers/Bundle/,Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js:197:13"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxc,ore/node_modules/thali/node_modules/multiplex/index.js","_functionName":"Channel.prototype._open","_lineNumber":"109","_columnNumber":"3","_msg":"    at Channel.prototype._open@/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D,2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js:109:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multip,lex/index.js","_functionName":"Channel.prototype.open","_lineNumber":"117","_columnNumber":"38","_msg":"    at Channel.prototype.open@/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modul,es/thali/node_modules/multiplex/index.js:117:38"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js","_functionName":"Multiplex.p,rototype._addChannel","_lineNumber":"215","_columnNumber":"3","_msg":"    at Multiplex.prototype._addChannel@/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/mul,tiplex/index.js:215:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js","_functionName":"Multiplex.prototype.createStream","_l,ineNumber":"165","_columnNumber":"10","_msg":"    at Multiplex.prototype.createStream@/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js:165:10",},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/tcpmultiplex.js","_functionName":"muxClientBridge/server<","_lineNumber":"73","_columnNumber":"24","_msg":"  ,  at muxClientBridge/server<@/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/tcpmultiplex.js:73:24"},{"_fileName":"events.js","_functionName":"emit","_lineNumber":"82","_col,umnNumber":"1","_msg":"    at emit@events.js:82:1"},{"_fileName":"net.js","_functionName":"$0f","_lineNumber":"1145","_columnNumber":"1","_msg":"    at $0f@net.js:1145:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B,41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js","_functionName":"unknown","_lineNumber":"187","_columnNumber":"15","_msg":""}]
Uncaught Exception: Error: stream.push() after EOF

,[ { _fileName: '/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js',
    _functionName: 'readableAddChunk',
    _lineNumber: '187',
    _columnNumber: '15',
    _msg: '    at readableAddChunk@/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js:187:15' },
,  { _fileName: '/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js',
    _functionName: 'Readable.p,rototype.push',
    _lineNumber: '165',
    _columnNumber: '10',
    _msg: '    at Readable.prototype.push@/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/mu,ltiplex/node_modules/readable-stream/lib/_stream_readable.js:165:10' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js',
 ,   _functionName: 'Multiplex.prototype._send',
    _lineNumber: '197',
    _columnNumber: '13',
    _msg: '    at Multiplex.prototype._send@/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/n,ode_modules/thali/node_modules/multiplex/index.js:197:13' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js',
    _functio,nName: 'Channel.prototype._open',
    _lineNumber: '109',
    _columnNumber: '3',
    _msg: '    at Channel.prototype._open@/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thal,i/node_modules/multiplex/index.js:109:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js',
    _functionName: 'Channel.p,rototype.open',
    _lineNumber: '117',
    _columnNumber: '38',
    _msg: '    at Channel.prototype.open@/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/mul,tiplex/index.js:117:38' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js',
    _functionName: 'Multiplex.prototype._addCh,annel',
    _lineNumber: '215',
    _columnNumber: '3',
    _msg: '    at Multiplex.prototype._addChannel@/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/mul,tiplex/index.js:215:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js',
    _functionName: 'Multiplex.prototype.createS,tream',
    _lineNumber: '165',
    _columnNumber: '10',
    _msg: '    at Multiplex.prototype.createStream@/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/m,ultiplex/index.js:165:10' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/tcpmultiplex.js',
    _functionName: 'muxClientBridge/server<',
    _lineNumb,er: '73',
    _columnNumber: '24',
    _msg: '    at muxC,lientBridge/server<@/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modules/thali/tcpmultiplex.js:73:24' },
  { _fileName: 'events.js',
    _functionName: 'emit',
    _lineNumber: '82',
,    _columnNumber: '1',
,    _msg: '    at emit@events.js:82:1' },
  { _fileName: 'net.js',
,    _functionName: '$0f',
    _lineNumber: '1145',
    _columnNumber: '1',
    _msg: '    at $0f@net.js:1145:1' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/258C3B86-B1A5-4A21-B41F-2620D2B7AB42/ThaliTest.app/www/jxcore/node_modu,les/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js',
    _functionName: 'unknown',
    _lineNumber: '187',
    _columnNumber: '15',
    _msg: '' },
  toString: [Function] ]

****TEST TOOK:  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****


```
