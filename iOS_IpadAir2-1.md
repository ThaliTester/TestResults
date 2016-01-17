#### Test 56151093914d164_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56151093914d164/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/461605F1-ED85-4ADD-AFD1-80D37E80567E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/461605F1-ED85-4ADD-AFD1-80D37E80567E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/56151093914d164/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56151093914d164/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4D711845-BADF-40AE-AD31-DF13729D84EF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57291"
,(lldb)     command script import "/tmp/461605F1-ED85-4ADD-AFD1-80D37E80567E/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-17 16:01:01.352 ThaliTest[2208:4753876] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/14233146-4A79-4300-8E48-FAC5F17AB5D5/Library/Cookies/Cookies.binarycookies
,2016-01-17 16:01:01.580 ThaliTest[2208:4753876] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-17 16:01:01.581 ThaliTest[2208:4753876] Multi-tasking -> Device: YES, App: YES
,2016-01-17 16:01:01.587 ThaliTest[2208:4753876] Unlimited access to network resources
,2016-01-17 16:01:01.593 ThaliTest[2208:4753876] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-17 16:01:05.739 ThaliTest[2208:4753876] Resetting plugins due to page load.
,2016-01-17 16:01:07.232 ThaliTest[2208:4753876] Finished load of: file:///var/mobile/Containers/Bundle/Application/4D711845-BADF-40AE-AD31-DF13729D84EF/ThaliTest.app/www/index.html
,2016-01-17 16:01:07.371 ThaliTest[2208:4753876] JXcore Cordova plugin initializing
,2016-01-17 16:01:07.372 ThaliTest[2208:4754062] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4D711845-BADF-40AE-AD31-DF13729D84EF/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4D711845-BADF-40AE-AD31-DF13729D84EF/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4D711845-BADF-40AE-AD31-DF13729D84EF/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4D711845-BADF-40AE-AD31-DF13729D84EF/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4D711845-BADF-40AE-AD31-DF13729D84EF/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4D711845-BADF-40AE-AD31-DF13729D84EF/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4D711845-BADF-40AE-AD31-DF13729D84EF/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
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
,# setup
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
,# setup
,# successfully read a previous pkcs12 file and return hash value
,# teardown
,ok 9 (unnamed assert)
,ok 10 (unnamed assert)
,ok 11 should not throw
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
,ok 27 should be equal
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
,ok 33 should be equal
,# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,# teardown
,ok 34 should be equal
,ok 35 should be equal
,# setup
,# #connect should call Mobile("Connect") with a port and without an error
,# teardown
,ok 36 should be equal
ok 37 should be equal
,ok 38 should be equal
,# setup
,# #connect should call Mobile("Connect") and handle an error
,# teardown
,ok 39 should be equal
,ok 40 should be equal
,# setup
,# should call Mobile("Disconnect") without an error
,# teardown
,ok 41 should be equal
,ok 42 should be equal
,# setup
,# should call Mobile("Disconnect") and handle an error
,# teardown
,ok 43 should be equal
,ok 44 should be equal
,# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2016-01-17 16:06:33.165 ThaliTest[2208:4754062] jxcore: startBroadcasting
,2016-01-17 16:06:33.171 ThaliTest[2208:4754062] server: starting 1453043193165.2208.NZaNKQ==
2016-01-17 16:06:33.171 ThaliTest[2208:4754062] multipeer session: start timer: 0x18dca350
,2016-01-17 16:06:33.171 ThaliTest[2208:4754062] THEMultipeerSession initialized peer 1453043193165.2208
2016-01-17 16:06:33.171 ThaliTest[2208:4754062] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
2016-01-17 16:06:33.173 ThaliTest[2208:4754062] jxcore: stopBroadcasting
2016-01-17 16:06:33.173 ThaliTest[2208:4754062] THEMultipeerSession stopping peer
2016-01-17 16:06:33.173 ThaliTest[220,8:4754062] multipeer session: stop timer
2016-01-17 16:06:33.173 ThaliTest[2208:4754062] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-17 16:06:33.174 ThaliTest[2208:4754062] jxcore: startBroadcasting
,2016-01-17 16:06:33.176 ThaliTest[2208:4754062] server: starting 1453043193174.2208.0wruPQ==
2016-01-17 16:06:33.177 ThaliTest[2208:4754062] multipeer session: start timer: 0x18dca350
2016-01-17 16:06:33.177 ThaliTest[2208:4754062] THEMultipeerSession in,itialized peer 1453043193174.2208
2016-01-17 16:06:33.177 ThaliTest[2208:4754062] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-17 16:06:33.178 ThaliTest[2208:4754062] jxcore: stopBroadcasting
2,016-01-17 16:06:33.178 ThaliTest[2208:4754062] THEMultipeerSession stopping peer
2016-01-17 16:06:33.178 ThaliTest[2208:4754062] multipeer session: stop timer
2016-01-17 16:06:33.178 ThaliTest[2208:4754062] jxcore: stopBroadcasting: success
ok 48 Should, be able to call stopBroadcasting without error
2016-01-17 16:06:33.178 ThaliTest[2208:4754062] jxcore: startBroadcasting
,2016-01-17 16:06:33.181 ThaliTest[2208:4754062] server: starting 1453043193178.2208.PeV+pA==
2016-01-17 16:06:33.181 ThaliTest[2208:4754062] multipeer session: start timer: 0x16fec7b0
2016-01-17 16:06:33.181 ThaliTest[2208:4754062] THEMultipeerSession in,itialized peer 1453043193178.2208
2016-01-17 16:06:33.181 ThaliTest[2208:4754062] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2016-01-17 16:06:33.182 ThaliTest[2208:4754062] jxcore: stopBroadcasting
2,016-01-17 16:06:33.182 ThaliTest[2208:4754062] THEMultipeerSession stopping peer
2016-01-17 16:06:33.182 ThaliTest[2208:4754062] multipeer session: stop timer
2016-01-17 16:06:33.182 ThaliTest[2208:4754062] jxcore: stopBroadcasting: success
ok 50 Should, be able to call stopBroadcasting without error
2016-01-17 16:06:33.182 ThaliTest[2208:4754062] jxcore: startBroadcasting
2016-01-17 16:06:33.184 ThaliTest[2208:4754062] server: starting 1453043193182.2208.6VqAww==
,2016-01-17 16:06:33.185 ThaliTest[2208:4754062] multipeer session: start timer: 0x16fec7b0
2016-01-17 16:06:33.185 ThaliTest[2208:4754062] THEMultipeerSession initialized peer 1453043193182.2208
2016-01-17 16:06:33.185 ThaliTest[2208:4754062] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2016-01-17 16:06:33.187 ThaliTest[2208:4754062] jxcore: stopBroadcasting
,2016-01-17 16:06:33.187 ThaliTest[2208:4754062] THEMultipeerSession stopping peer
2016-01-17 16:06:33.187 ThaliTest[2208:4754062] multipeer session: stop timer
2016-01-17 16:06:33.188 ThaliTest[2208:4754062] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
2016-01-17 16:06:33.188 ThaliTest[2208:4754062] jxcore: startBroadcasting
,2016-01-17 16:06:33.192 ThaliTest[2208:4754062] server: starting 1453043193188.2208.aXjL4g==
2016-01-17 16:06:33.192 ThaliTest[2208:4754062] multipeer session: start timer: 0x18f56f80
2016-01-17 16:06:33.192 ThaliTest[2208:4754062] THEMultipeerSession in,itialized peer 1453043193188.2208
2016-01-17 16:06:33.193 ThaliTest[2208:4754062] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2016-01-17 16:06:33.194 ThaliTest[2208:4754062] jxcore: stopBroadcasting
2,016-01-17 16:06:33.194 ThaliTest[2208:4754062] THEMultipeerSession stopping peer
2016-01-17 16:06:33.194 ThaliTest[2208:4754062] multipeer session: stop timer
2016-01-17 16:06:33.195 ThaliTest[2208:4754062] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-17 16:06:33.195 ThaliTest[2208:4754062] jxcore: startBroadcasting
,2016-01-17 16:06:33.197 ThaliTest[2208:4754062] server: starting 1453043193195.2208.I99hkA==
2016-01-17 16:06:33.197 ThaliTest[2208:4754062] multipeer session: start timer: 0x18dce1b0
2016-01-17 16:06:33.198 ThaliTest[2208:4754062] THEMultipeerSession initialized peer 1453043193195.2208
2016-01-17 16:06:33.198 ThaliTest[2208:4754062] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error
,2016-01-17 16:06:33.199 ThaliTest[2208:4754062] jxcore: stopBroadcasting
2016-01-17 16:06:33.200 ThaliTest[2208:4754062] THEMultipeerSession stopping peer
2016-01-17 16:06:33.200 ThaliTest[2208:4754062] multipeer session: stop timer
2016-01-17 16:06:33.200 ThaliTest[2208:4754062] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
2016-01-17 16:06:33.201 ThaliTest[2208:4754062] jxcore: startBroadcasting
,2016-01-17 16:06:33.203 ThaliTest[2208:4754062] server: starting 1453043193201.2208.hFtIhA==
2016-01-17 16:06:33.203 ThaliTest[2208:4754062] multipeer session: start timer: 0x16feb710
2016-01-17 16:06:33.203 ThaliTest[2208:4754062] THEMultipeerSession initialized peer 1453043193201.2208
2016-01-17 16:06:33.203 ThaliTest[2208:4754062] jxcore: startBroadcasting: success
ok 57 Should be able to call startBroadcasting without error
2016-01-17 16:06:33.204 ThaliTest[2208:4754062] jxcore: stopBroadcasting
2,016-01-17 16:06:33.204 ThaliTest[2208:4754062] THEMultipeerSession stopping peer
2016-01-17 16:06:33.204 ThaliTest[2208:4754062] multipeer session: stop timer
2016-01-17 16:06:33.204 ThaliTest[2208:4754062] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-17 16:06:33.205 ThaliTest[2208:4754062] jxcore: startBroadcasting
,2016-01-17 16:06:33.208 ThaliTest[2208:4754062] server: starting 1453043193205.2208.WEqsGw==
2016-01-17 16:06:33.208 ThaliTest[2208:4754062] multipeer session: start timer: 0x18ffa060
2016-01-17 16:06:33.209 ThaliTest[2208:4754062] THEMultipeerSession in,itialized peer 1453043193205.2208
2016-01-17 16:06:33.209 ThaliTest[2208:4754062] jxcore: startBroadcasting: success
ok 59 Should be able to call startBroadcasting without error
2016-01-17 16:06:33.209 ThaliTest[2208:4754062] jxcore: stopBroadcasting
2,016-01-17 16:06:33.210 ThaliTest[2208:4754062] THEMultipeerSession stopping peer
2016-01-17 16:06:33.210 ThaliTest[2208:4754062] multipeer session: stop timer
,2016-01-17 16:06:33.210 ThaliTest[2208:4754062] jxcore: stopBroadcasting: success
ok 60 Should be able to call stopBroadcasting without error
2016-01-17 16:06:33.212 ThaliTest[2208:4754062] jxcore: startBroadcasting
,2016-01-17 16:06:33.214 ThaliTest[2208:4754062] server: starting 1453043193212.2208.N9PbXA==
2016-01-17 16:06:33.215 ThaliTest[2208:4754062] multipeer session: start timer: 0x18ffb890
2016-01-17 16:06:33.215 ThaliTest[2208:4754062] THEMultipeerSession in,itialized peer 1453043193212.2208
2016-01-17 16:06:33.215 ThaliTest[2208:4754062] jxcore: startBroadcasting: success
ok 61 Should be able to call startBroadcasting without error
2016-01-17 16:06:33.216 ThaliTest[2208:4754062] jxcore: stopBroadcasting
2016-01-17 16:06:33.216 ThaliTest[2208:4754062] THEMultipeerSession stopping peer
2016-01-17 16:06:33.216 ThaliTest[2208:4754062] multipeer session: stop timer
,2016-01-17 16:06:33.216 ThaliTest[2208:4754062] jxcore: stopBroadcasting: success
ok 62 Should be able to call stopBroadcasting without error
2016-01-17 16:06:33.217 ThaliTest[2208:4754062] jxcore: startBroadcasting
2016-01-17 16:06:33.218 ThaliTest[220,8:4754062] server: starting 1453043193217.2208.9j48Bg==
2016-01-17 16:06:33.218 ThaliTest[2208:4754062] multipeer session: start timer: 0x18ff9aa0
2016-01-17 16:06:33.219 ThaliTest[2208:4754062] THEMultipeerSession initialized peer 1453043193217.2208
20,16-01-17 16:06:33.219 ThaliTest[2208:4754062] jxcore: startBroadcasting: success
ok 63 Should be able to call startBroadcasting without error
2016-01-17 16:06:33.219 ThaliTest[2208:4754062] jxcore: stopBroadcasting
2016-01-17 16:06:33.219 ThaliTest[2208,:4754062] THEMultipeerSession stopping peer
2016-01-17 16:06:33.219 ThaliTest[2208:4754062] multipeer session: stop timer
2016-01-17 16:06:33.219 ThaliTest[2208:4754062] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-17 16:06:33.467 ThaliTest[2208:4754062] jxcore: startBroadcasting
,2016-01-17 16:06:33.468 ThaliTest[2208:4754062] server: starting 1453043193466.2208.2YT8tQ==
2016-01-17 16:06:33.468 ThaliTest[2208:4754062] multipeer session: start timer: 0x18dd0e20
2016-01-17 16:06:33.468 ThaliTest[2208:4754062] THEMultipeerSession initialized peer 1453043193466.2208
,2016-01-17 16:06:33.469 ThaliTest[2208:4754062] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-17 16:06:33.470 ThaliTest[2208:4754062] jxcore: startBroadcasting
2016-01-17 16:06:33.470 ThaliTest[2208:4754062] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
,2016-01-17 16:06:33.471 ThaliTest[2208:4754062] jxcore: stopBroadcasting
2016-01-17 16:06:33.471 ThaliTest[2208:4754062] THEMultipeerSession stopping peer
2016-01-17 16:06:33.471 ThaliTest[2208:4754062] multipeer session: stop timer
,2016-01-17 16:06:33.471 ThaliTest[2208:4754062] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-17 16:06:33.542 ThaliTest[2208:4754062] jxcore: startBroadcasting
,2016-01-17 16:06:33.543 ThaliTest[2208:4754062] server: starting 1453043193541.2208.BHX5ng==
2016-01-17 16:06:33.543 ThaliTest[2208:4754062] multipeer session: start timer: 0x16fe5230
2016-01-17 16:06:33.543 ThaliTest[2208:4754062] THEMultipeerSession initialized peer 1453043193541.2208
2016-01-17 16:06:33.543 ThaliTest[2208:4754062] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-17 16:06:33.544 ThaliTest[2208:4754062] jxcore: connect foobar
,2016-01-17 16:06:33.544 ThaliTest[2208:4754062] client: unknown peer foobar
2016-01-17 16:06:33.544 ThaliTest[2208:4754062] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
2016-01-17 16:06:33.545 ThaliTest[2208:4754062] jxcore,: stopBroadcasting
2016-01-17 16:06:33.545 ThaliTest[2208:4754062] THEMultipeerSession stopping peer
2016-01-17 16:06:33.545 ThaliTest[2208:4754062] multipeer session: stop timer
2016-01-17 16:06:33.545 ThaliTest[2208:4754062] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-17 16:06:33.624 ThaliTest[2208:4754062] jxcore: startBroadcasting
,2016-01-17 16:06:33.625 ThaliTest[2208:4754062] server: starting 1453043193624.2208.XuZzjw==
2016-01-17 16:06:33.625 ThaliTest[2208:4754062] multipeer session: start timer: 0x18ddfb70
2016-01-17 16:06:33.625 ThaliTest[2208:4754062] THEMultipeerSession in,itialized peer 1453043193624.2208
2016-01-17 16:06:33.625 ThaliTest[2208:4754062] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-17 16:06:33.626 ThaliTest[2208:4754062] jxcore: disconnect
,2016-01-17 16:06:33.627 ThaliTest[2208:4754062] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
,2016-01-17 16:06:33.627 ThaliTest[2208:4754062] jxcore: stopBroadcasting
2016-01-17 16:06:33.627 ThaliTest[2208:4754062] THEMultipeerSession stopping peer
2016-01-17 16:06:33.628 ThaliTest[2208:4754062] multipeer session: stop timer
2016-01-17 16:06:33.628 ThaliTest[2208:4754062] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-17 16:06:33.965 ThaliTest[2208:4754062] jxcore: startBroadcasting
,2016-01-17 16:06:33.966 ThaliTest[2208:4754062] server: starting 1453043193965.2208.NPzgDQ==
2016-01-17 16:06:33.966 ThaliTest[2208:4754062] multipeer session: start timer: 0x18ff11f0
2016-01-17 16:06:33.966 ThaliTest[2208:4754062] THEMultipeerSession initialized peer 1453043193965.2208
2016-01-17 16:06:33.966 ThaliTest[2208:4754062] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-17 16:06:35.237 ThaliTest[2208:4753876] client: found peer: 1453043193437.2103.a7RiGw==
,2016-01-17 16:06:35.238 ThaliTest[2208:4754062] jxcore: connect 1453043193437.2103.a7RiGw==
2016-01-17 16:06:35.238 ThaliTest[2208:4754062] client session: connect
2016-01-17 16:06:35.238 ThaliTest[2208:4754062] client session: stateChange:0->1 1453043193437.2103.a7RiGw==
,2016-01-17 16:06:35.436 ThaliTest[2208:4753876] multipeer session: reset timer
2016-01-17 16:06:35.436 ThaliTest[2208:4753876] multipeer session: stop timer
2016-01-17 16:06:35.436 ThaliTest[2208:4753876] multipeer session: start timer: 0x18ff11f0
2016-01-17 16:06:35.437 ThaliTest[2208:4753876] server session: connect
2016-01-17 16:06:35.437 ThaliTest[2208:4753876] server session: stateChange:0->1 1453043193437.2103
,2016-01-17 16:06:35.439 ThaliTest[2208:4753876] server: accepting invitation 1453043193437.2103
,2016-01-17 16:06:39.118 ThaliTest[2208:4755769] client session: connected
2016-01-17 16:06:39.118 ThaliTest[2208:4755769] client session: stateChange:1->2 1453043193437.2103.a7RiGw==
,2016-01-17 16:06:39.137 ThaliTest[2208:4755781] client session: fireConnectCallback: 1453043193437.2103.a7RiGw==
2016-01-17 16:06:39.138 ThaliTest[2208:4755781] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2016-01-17 16:06:39.139 ThaliTest[2208:4754062] jxcore: disconnect
2016-01-17 16:06:39.139 ThaliTest[2208:4754062] client session: disconnectFromPeer: 1453043193437.2103.a7RiGw==
2016-01-17 16:06:39.139 ThaliTest[2208:4754062] client session: disconnect
2016-01-17 16:06:39.139 ThaliTest[2208:4754062] client session: stateChange:2->0 1453043193437.2103.a7RiGw==
,2016-01-17 16:06:39.197 ThaliTest[2208:4754062] jxcore: disconnect: success
,ok 77 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,2016-01-17 16:06:39.381 ThaliTest[2208:4755781] server session: connected
2016-01-17 16:06:39.381 ThaliTest[2208:4755781] server session: stateChange:1->2 1453043193437.2103
,2016-01-17 16:06:39.382 ThaliTest[2208:4753876] server relay: socket disconnected
2016-01-17 16:06:39.382 ThaliTest[2208:4753876] server relay: 0x18fe1570 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-17 16:06:40.174 ThaliTest[2208:4755772] server session: not connected 1453043193437.2103
,calling stopBroadcasting
,2016-01-17 16:06:40.356 ThaliTest[2208:4754062] jxcore: stopBroadcasting
2016-01-17 16:06:40.356 ThaliTest[2208:4754062] THEMultipeerSession stopping peer
2016-01-17 16:06:40.356 ThaliTest[2208:4754062] multipeer session: stop timer
2016-01-17 16:06:40.356 ThaliTest[2208:4754062] server session: disconnect
2016-01-17 16:06:40.356 ThaliTest[2208:4754062] server session: stateChange:2->0 1453043193437.2103
2016-01-17 16:06:40.356 ThaliTest[2208:4754062] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-17 16:06:41.233 ThaliTest[2208:4754062] jxcore: startBroadcasting
,2016-01-17 16:06:41.234 ThaliTest[2208:4754062] server: starting 1453043201233.2208.WN97Sw==
2016-01-17 16:06:41.234 ThaliTest[2208:4754062] multipeer session: start timer: 0x18de24f0
2016-01-17 16:06:41.234 ThaliTest[2208:4754062] THEMultipeerSession initialized peer 1453043201233.2208
2016-01-17 16:06:41.234 ThaliTest[2208:4754062] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-17 16:06:42.216 ThaliTest[2208:4753876] client: found peer: 1453043200722.2103.c0vTZA==
,2016-01-17 16:06:42.217 ThaliTest[2208:4754062] jxcore: connect 1453043200722.2103.c0vTZA==
2016-01-17 16:06:42.217 ThaliTest[2208:4754062] client session: connect
2016-01-17 16:06:42.217 ThaliTest[2208:4754062] client session: stateChange:0->1 1453043200722.2103.c0vTZA==
,2016-01-17 16:06:42.378 ThaliTest[2208:4753876] multipeer session: reset timer
2016-01-17 16:06:42.378 ThaliTest[2208:4753876] multipeer session: stop timer
2016-01-17 16:06:42.378 ThaliTest[2208:4753876] multipeer session: start timer: 0x18de24f0
2016-01-17 16:06:42.379 ThaliTest[2208:4753876] server session: connect
2016-01-17 16:06:42.379 ThaliTest[2208:4753876] server session: stateChange:0->1 1453043200722.2103
,2016-01-17 16:06:42.381 ThaliTest[2208:4753876] server: accepting invitation 1453043200722.2103
,2016-01-17 16:06:46.314 ThaliTest[2208:4755772] client session: connected
2016-01-17 16:06:46.314 ThaliTest[2208:4755772] client session: stateChange:1->2 1453043200722.2103.c0vTZA==
,2016-01-17 16:06:46.318 ThaliTest[2208:4755781] client session: fireConnectCallback: 1453043200722.2103.c0vTZA==
2016-01-17 16:06:46.318 ThaliTest[2208:4755781] jxcore: connect: success
ok 79 Should be able to connect without error
ok 80 Port should be within range
,2016-01-17 16:06:46.319 ThaliTest[2208:4754062] jxcore: connect 1453043200722.2103.c0vTZA==
2016-01-17 16:06:46.319 ThaliTest[2208:4754062] client: already connect(ing/ed) to 1453043200722.2103.c0vTZA==
2016-01-17 16:06:46.319 ThaliTest[2208:4754062] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
2016-01-17 16:06:46.320 ThaliTest[2208:4754062] jxcore: disconnect
2016-01-17 16:06:46.320 ThaliTest[2208:4754062] client session: disconnectFromPeer: 1453043200722.2103.c0vTZA==
2016-01-17 16:06:46.320 ThaliTest[2208:4754062] client session: disconnect
2016-01-17 16:06:46.320 ThaliTest[2208:4754062] client session: stateChange:2->0 1453043200722.2103.c0vTZA==
,2016-01-17 16:06:46.324 ThaliTest[2208:4754062] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-17 16:06:46.380 ThaliTest[2208:4755772] server session: connected
,2016-01-17 16:06:46.380 ThaliTest[2208:4755772] server session: stateChange:1->2 1453043200722.2103
,2016-01-17 16:06:46.382 ThaliTest[2208:4753876] server relay: socket disconnected
,2016-01-17 16:06:46.382 ThaliTest[2208:4753876] server relay: 0x18ddde20 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-17 16:06:46.409 ThaliTest[2208:4755781] server session: not connected 1453043200722.2103
,calling stopBroadcasting
,2016-01-17 16:06:46.700 ThaliTest[2208:4754062] jxcore: stopBroadcasting
2016-01-17 16:06:46.700 ThaliTest[2208:4754062] THEMultipeerSession stopping peer
,2016-01-17 16:06:46.700 ThaliTest[2208:4754062] multipeer session: stop timer
,2016-01-17 16:06:46.700 ThaliTest[2208:4754062] server session: disconnect
2016-01-17 16:06:46.702 ThaliTest[2208:4754062] server session: stateChange:2->0 1453043200722.2103
,2016-01-17 16:06:46.703 ThaliTest[2208:4754062] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-17 16:06:48.118 ThaliTest[2208:4754062] jxcore: startBroadcasting
,2016-01-17 16:06:48.119 ThaliTest[2208:4754062] server: starting 1453043208118.2208.Zx3ckA==
2016-01-17 16:06:48.120 ThaliTest[2208:4754062] multipeer session: start timer: 0x16fd2680
2016-01-17 16:06:48.120 ThaliTest[2208:4754062] THEMultipeerSession initialized peer 1453043208118.2208
2016-01-17 16:06:48.120 ThaliTest[2208:4754062] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-17 16:06:49.913 ThaliTest[2208:4753876] client: found peer: 1453043208033.2103.DZrl4w==
2016-01-17 16:06:49.913 ThaliTest[2208:4754062] jxcore: connect 1453043208033.2103.DZrl4w==
2016-01-17 16:06:49.914 ThaliTest[2208:4754062] client session: connect
2016-01-17 16:06:49.914 ThaliTest[2208:4754062] client session: stateChange:0->1 1453043208033.2103.DZrl4w==
,2016-01-17 16:06:49.981 ThaliTest[2208:4753876] multipeer session: reset timer
2016-01-17 16:06:49.981 ThaliTest[2208:4753876] multipeer session: stop timer
2016-01-17 16:06:49.982 ThaliTest[2208:4753876] multipeer session: start timer: 0x16fd2680
2016-,01-17 16:06:49.982 ThaliTest[2208:4753876] server session: connect
2016-01-17 16:06:49.982 ThaliTest[2208:4753876] server session: stateChange:0->1 1453043208033.2103
,2016-01-17 16:06:49.984 ThaliTest[2208:4753876] server: accepting invitation 1453043208033.2103
,2016-01-17 16:06:53.918 ThaliTest[2208:4755781] client session: connected
2016-01-17 16:06:53.918 ThaliTest[2208:4755781] client session: stateChange:1->2 1453043208033.2103.DZrl4w==
,2016-01-17 16:06:53.920 ThaliTest[2208:4755781] client session: fireConnectCallback: 1453043208033.2103.DZrl4w==
2016-01-17 16:06:53.920 ThaliTest[2208:4755781] jxcore: connect: success
,ok 84 Should be able to connect without error
,ok 85 Port should be within range
,2016-01-17 16:06:53.921 ThaliTest[2208:4754062] jxcore: disconnect
,2016-01-17 16:06:53.921 ThaliTest[2208:4754062] client session: disconnectFromPeer: 1453043208033.2103.DZrl4w==
2016-01-17 16:06:53.921 ThaliTest[2208:4754062] client session: disconnect
2016-01-17 16:06:53.921 ThaliTest[2208:4754062] client session: stateChange:2->0 1453043208033.2103.DZrl4w==
,2016-01-17 16:06:53.979 ThaliTest[2208:4754062] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error
,2016-01-17 16:06:53.980 ThaliTest[2208:4754062] jxcore: disconnect
,2016-01-17 16:06:53.980 ThaliTest[2208:4754062] jxcore: disconnect: fail
,ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-17 16:06:54.118 ThaliTest[2208:4755767] server session: connected
,2016-01-17 16:06:54.118 ThaliTest[2208:4755767] server session: stateChange:1->2 1453043208033.2103
,2016-01-17 16:06:54.120 ThaliTest[2208:4753876] server relay: socket disconnected
,2016-01-17 16:06:54.121 ThaliTest[2208:4753876] server relay: 0x16f22c00 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection ,refused} 
,2016-01-17 16:06:54.176 ThaliTest[2208:4755767] server session: not connected 1453043208033.2103
,calling stopBroadcasting
2016-01-17 16:06:54.583 ThaliTest[2208:4754062] jxcore: stopBroadcasting
2016-01-17 16:06:54.583 ThaliTest[2208:4754062] THEMultipeerSession stopping peer
2016-01-17 16:06:54.583 ThaliTest[2208:4754062] multipeer session: stop timer
,2016-01-17 16:06:54.583 ThaliTest[2208:4754062] server session: disconnect
2016-01-17 16:06:54.583 ThaliTest[2208:4754062] server session: stateChange:2->0 1453043208033.2103
2016-01-17 16:06:54.584 ThaliTest[2208:4754062] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can connect and send data
,# teardown
,echo server started on port: 53188
,2016-01-17 16:06:55.490 ThaliTest[2208:4754062] jxcore: startBroadcasting
,2016-01-17 16:06:55.491 ThaliTest[2208:4754062] server: starting 1453043215490.2208.qThMYw==
2016-01-17 16:06:55.491 ThaliTest[2208:4754062] multipeer session: start timer: 0x18fdf810
2016-01-17 16:06:55.491 ThaliTest[2208:4754062] THEMultipeerSession initialized peer 1453043215490.2208
2016-01-17 16:06:55.491 ThaliTest[2208:4754062] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
,2016-01-17 16:06:56.864 ThaliTest[2208:4753876] client: found peer: 1453043215124.2103.Q2LLJA==
2016-01-17 16:06:56.865 ThaliTest[2208:4754062] jxcore: connect 1453043215124.2103.Q2LLJA==
2016-01-17 16:06:56.865 ThaliTest[2208:4754062] client session: connect
2016-01-17 16:06:56.865 ThaliTest[2208:4754062] client session: stateChange:0->1 1453043215124.2103.Q2LLJA==
,2016-01-17 16:06:56.872 ThaliTest[2208:4753876] multipeer session: reset timer
2016-01-17 16:06:56.873 ThaliTest[2208:4753876] multipeer session: stop timer
2016-01-17 16:06:56.873 ThaliTest[2208:4753876] multipeer session: start timer: 0x18fdf810
2016-01-17 16:06:56.873 ThaliTest[2208:4753876] server session: connect
2016-01-17 16:06:56.873 ThaliTest[2208:4753876] server session: stateChange:0->1 1453043215124.2103
,2016-01-17 16:06:56.875 ThaliTest[2208:4753876] server: accepting invitation 1453043215124.2103
,2016-01-17 16:07:00.975 ThaliTest[2208:4755772] client session: connected
2016-01-17 16:07:00.975 ThaliTest[2208:4755772] client session: stateChange:1->2 1453043215124.2103.Q2LLJA==
,2016-01-17 16:07:00.988 ThaliTest[2208:4755857] server session: connected
2016-01-17 16:07:00.988 ThaliTest[2208:4755857] server session: stateChange:1->2 1453043215124.2103
,2016-01-17 16:07:00.992 ThaliTest[2208:4755781] client session: fireConnectCallback: 1453043215124.2103.Q2LLJA==
2016-01-17 16:07:00.992 ThaliTest[2208:4755781] jxcore: connect: success
ok 89 Should be able to connect without error
,ok 90 Port should be within range
,2016-01-17 16:07:00.994 ThaliTest[2208:4753876] client: relay established
2016-01-17 16:07:00.995 ThaliTest[2208:4753876] client: new accepted socket: 0x18fdbc60
,2016-01-17 16:07:01.034 ThaliTest[2208:4753876] server relay: connected (to port: 53188)
,data in 2190
,data in 6570
,data in 8760
,data in 14235
,data in 15330
,data in 18615
,data in 19710
,data in 20805
,data in 25114
,data in 38325
,data in 39450
,data in 42735
,data in 43830
,data in 56970
,data in 74490
,data in 81060
,data in 84345
,data in 90915
,data in 95295
,data in 96390
,data in 97485
,data in 113910
,data in 120450
,data in 125925
,data in 131072
,ok 91 the test messages should be equal
,2016-01-17 16:07:02.013 ThaliTest[2208:4754062] jxcore: disconnect
,2016-01-17 16:07:02.014 ThaliTest[2208:4754062] client session: disconnectFromPeer: 1453043215124.2103.Q2LLJA==
,2016-01-17 16:07:02.014 ThaliTest[2208:4754062] client session: disconnect
,2016-01-17 16:07:02.014 ThaliTest[2208:4754062] client session: stateChange:2->0 1453043215124.2103.Q2LLJA==
,2016-01-17 16:07:02.017 ThaliTest[2208:4754062] jxcore: disconnect: success
,ok 92 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-17 16:07:02.105 ThaliTest[2208:4755772] server session: not connected 1453043215124.2103
,calling stopBroadcasting
,2016-01-17 16:07:02.982 ThaliTest[2208:4754062] jxcore: stopBroadcasting
2016-01-17 16:07:02.983 ThaliTest[2208:4754062] THEMultipeerSession stopping peer
2016-01-17 16:07:02.983 ThaliTest[2208:4754062] multipeer session: stop timer
2016-01-17 16:07:02.983 ThaliTest[2208:4754062] server session: disconnect
2016-01-17 16:07:02.983 ThaliTest[2208:4754062] server session: stateChange:2->0 1453043215124.2103
,2016-01-17 16:07:02.987 ThaliTest[2208:4754062] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,echo server started on port: 53194
,2016-01-17 16:07:06.498 ThaliTest[2208:4754062] jxcore: startBroadcasting
,2016-01-17 16:07:06.499 ThaliTest[2208:4754062] server: starting 1453043226498.2208.4X1ntA==
2016-01-17 16:07:06.500 ThaliTest[2208:4754062] multipeer session: start timer: 0x16ff9fb0
2016-01-17 16:07:06.500 ThaliTest[2208:4754062] THEMultipeerSession initialized peer 1453043226498.2208
2016-01-17 16:07:06.500 ThaliTest[2208:4754062] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error
,2016-01-17 16:07:07.734 ThaliTest[2208:4753876] client: found peer: 1453043225845.2103.il9MVA==
,[{"peerIdentifier":"1453043225845.2103.il9MVA==","peerName":"(null)","peerAvailable":true}]
,2016-01-17 16:07:07.736 ThaliTest[2208:4754062] jxcore: connect 1453043225845.2103.il9MVA==
2016-01-17 16:07:07.736 ThaliTest[2208:4754062] client session: connect
2016-01-17 16:07:07.736 ThaliTest[2208:4754062] client session: stateChange:0->1 1453043225845.2103.il9MVA==
,2016-01-17 16:07:07.833 ThaliTest[2208:4753876] multipeer session: reset timer
2016-01-17 16:07:07.834 ThaliTest[2208:4753876] multipeer session: stop timer
,2016-01-17 16:07:07.834 ThaliTest[2208:4753876] multipeer session: start timer: 0x16ff9fb0
2016-01-17 16:07:07.834 ThaliTest[2208:4753876] server session: connect
2016-01-17 16:07:07.834 ThaliTest[2208:4753876] server session: stateChange:0->1 1453043225845.2103
,2016-01-17 16:07:07.836 ThaliTest[2208:4753876] server: accepting invitation 1453043225845.2103
,2016-01-17 16:07:11.936 ThaliTest[2208:4755777] client session: connected
,2016-01-17 16:07:11.937 ThaliTest[2208:4755777] client session: stateChange:1->2 1453043225845.2103.il9MVA==
,2016-01-17 16:07:11.938 ThaliTest[2208:4755772] server session: connected
2016-01-17 16:07:11.938 ThaliTest[2208:4755772] server session: stateChange:1->2 1453043225845.2103
,2016-01-17 16:07:11.939 ThaliTest[2208:4755777] client session: fireConnectCallback: 1453043225845.2103.il9MVA==
2016-01-17 16:07:11.940 ThaliTest[2208:4755777] jxcore: connect: success
,ok 94 Should be able to connect without error
,ok 95 Port should be within range
,ok 96 First connect should succeed
2016-01-17 16:07:11.942 ThaliTest[2208:4753876] server relay: connected (to port: 53194)
,2016-01-17 16:07:11.950 ThaliTest[2208:4753876] client: relay established
2016-01-17 16:07:11.951 ThaliTest[2208:4753876] client: new accepted socket: 0x18d3dae0
,ok 97 the test messages should be equal
ok 98 First send should succeed
,2016-01-17 16:07:12.014 ThaliTest[2208:4753876] client: socket closed
2016-01-17 16:07:12.014 ThaliTest[2208:4753876] client relay: socket disconnected
,2016-01-17 16:07:12.014 ThaliTest[2208:4753876] client relay: 0x18d3dae0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-01-17 16:07:12.014 ThaliTest[2208:4753876] client session: socket closed: 1453043225845.2103.il9MVA==
2016-01-17 16:07:12.015 ThaliTest[2208:4753876] client session: onLinkFailure: 1453043225845.2103.il9MVA==
,2016-01-17 16:07:12.015 ThaliTest[2208:4753876] client session: disconnect
2016-01-17 16:07:12.015 ThaliTest[2208:4753876] client session: stateChange:2->0 1453043225845.2103.il9MVA==
,2016-01-17 16:07:12.017 ThaliTest[2208:4753876] client session: fireConnectionErrorEvent: 1453043225845.2103.il9MVA==
2016-01-17 16:07:12.018 ThaliTest[2208:4754062] jxcore: connect 1453043225845.2103.il9MVA==
,2016-01-17 16:07:12.018 ThaliTest[2208:4754062] client session: connect
2016-01-17 16:07:12.019 ThaliTest[2208:4754062] client session: stateChange:0->1 1453043225845.2103.il9MVA==
,2016-01-17 16:07:12.061 ThaliTest[2208:4755781] server session: not connected 1453043225845.2103
,2016-01-17 16:07:12.126 ThaliTest[2208:4753876] multipeer session: reset timer
2016-01-17 16:07:12.126 ThaliTest[2208:4753876] multipeer session: stop timer
2016-01-17 16:07:12.126 ThaliTest[2208:4753876] multipeer session: start timer: 0x16ff9fb0
2016-,01-17 16:07:12.126 ThaliTest[2208:4753876] server: disconnecting to refresh session (1453043225845.2103)
2016-01-17 16:07:12.126 ThaliTest[2208:4753876] server session: disconnect
2016-01-17 16:07:12.126 ThaliTest[2208:4753876] server session: stateChange:2->0 1453043225845.2103
,2016-01-17 16:07:12.128 ThaliTest[2208:4753876] server session: connect
2016-01-17 16:07:12.128 ThaliTest[2208:4753876] server session: stateChange:0->1 1453043225845.2103
,2016-01-17 16:07:12.130 ThaliTest[2208:4753876] server: accepting invitation 1453043225845.2103
,2016-01-17 16:07:16.262 ThaliTest[2208:4755769] client session: connected
2016-01-17 16:07:16.262 ThaliTest[2208:4755769] client session: stateChange:1->2 1453043225845.2103.il9MVA==
,2016-01-17 16:07:16.266 ThaliTest[2208:4755777] client session: fireConnectCallback: 1453043225845.2103.il9MVA==
2016-01-17 16:07:16.266 ThaliTest[2208:4755777] jxcore: connect: success
,ok 99 Should be able to connect without error
,ok 100 Port should be within range
,ok 101 Second connect should succeed
,2016-01-17 16:07:16.276 ThaliTest[2208:4753876] client: relay established
2016-01-17 16:07:16.276 ThaliTest[2208:4753876] client: new accepted socket: 0x18fd0d70
,ok 102 the test messages should be equal
,ok 103 Second send should succeed
,# setup
,2016-01-17 16:07:16.350 ThaliTest[2208:4753876] client: socket closed
2016-01-17 16:07:16.350 ThaliTest[2208:4753876] client relay: socket disconnected
,2016-01-17 16:07:16.350 ThaliTest[2208:4753876] client relay: 0x18fd0d70 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-17 16:07:,16.350 ThaliTest[2208:4753876] client session: socket closed: 1453043225845.2103.il9MVA==
2016-01-17 16:07:16.350 ThaliTest[2208:4753876] client session: onLinkFailure: 1453043225845.2103.il9MVA==
,2016-01-17 16:07:16.350 ThaliTest[2208:4753876] client session: disconnect
2016-01-17 16:07:16.350 ThaliTest[2208:4753876] client session: stateChange:2->0 1453043225845.2103.il9MVA==
,2016-01-17 16:07:16.354 ThaliTest[2208:4753876] client session: fireConnectionErrorEvent: 1453043225845.2103.il9MVA==
,2016-01-17 16:07:16.356 ThaliTest[2208:4755857] server session: connected
2016-01-17 16:07:16.356 ThaliTest[2208:4755857] server session: stateChange:1->2 1453043225845.2103
,2016-01-17 16:07:16.359 ThaliTest[2208:4753876] server relay: connected (to port: 53194)
,2016-01-17 16:07:16.503 ThaliTest[2208:4755769] server session: not connected 1453043225845.2103
,calling stopBroadcasting
,2016-01-17 16:07:16.534 ThaliTest[2208:4754062] jxcore: stopBroadcasting
2016-01-17 16:07:16.534 ThaliTest[2208:4754062] THEMultipeerSession stopping peer
,2016-01-17 16:07:16.534 ThaliTest[2208:4754062] multipeer session: stop timer
,2016-01-17 16:07:16.535 ThaliTest[2208:4754062] server session: disconnect
,2016-01-17 16:07:16.535 ThaliTest[2208:4754062] server session: stateChange:2->0 1453043225845.2103
,2016-01-17 16:07:16.837 ThaliTest[2208:4754062] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/14233146-4A79-4300-8E48-FAC5F17AB5D5/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 104 starting event should occur in right order
,2016-01-17 16:07:17.175 ThaliTest[2208:4754062] jxcore: startBroadcasting
,2016-01-17 16:07:17.176 ThaliTest[2208:4754062] server: starting QE75ym5qNZcpaCgt1-Eowg.WirZZA==
2016-01-17 16:07:17.176 ThaliTest[2208:4754062] multipeer session: start timer: 0x16fa3680
2016-01-17 16:07:17.176 ThaliTest[2208:4754062] THEMultipeerSession initialized peer QE75ym5qNZcpaCgt1-Eowg
2016-01-17 16:07:17.176 ThaliTest[2208:4754062] jxcore: startBroadcasting: success
ok 105 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
ok 106 stopping event should o,ccur in right order
About to call stopBroadcasting
2016-01-17 16:07:17.178 ThaliTest[2208:4754062] jxcore: stopBroadcasting
2016-01-17 16:07:17.178 ThaliTest[2208:4754062] THEMultipeerSession stopping peer
2016-01-17 16:07:17.178 ThaliTest[2208:4754062,] multipeer session: stop timer
2016-01-17 16:07:17.178 ThaliTest[2208:4754062] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
,ok 107 stopped event should occur in right order
mux server bridge listener closed
,# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/14233146-4A79-4300-8E48-FAC5F17AB5D5/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-17 16:07:17.533 ThaliTest[2208:4754062] jxcore: startBroadcasting
,2016-01-17 16:07:17.534 ThaliTest[2208:4754062] server: starting QE75ym5qNZcpaCgt1-Eowg.qFhXdw==
2016-01-17 16:07:17.535 ThaliTest[2208:4754062] multipeer session: start timer: 0x16fbb780
2016-01-17 16:07:17.535 ThaliTest[2208:4754062] THEMultipeerSession initialized peer QE75ym5qNZcpaCgt1-Eowg
2016-01-17 16:07:17.535 ThaliTest[2208:4754062] jxcore: startBroadcasting: success
,ok 108 getDeviceIdentity should not return an error
ok 109 deviceName should not be null
Now in TRM stop
State of this._isStarted: true
About to call stopBroadcasting
2016-01-17 16:07:17.537 ThaliTest[2208:4754062] jxcore: stopBroadcasting
2016-01-17 16:07:17.537 ThaliTest[2208:4754062] THEMultipeerSession stopping peer
2016-01-17 16:07:17.537 ThaliTest[2208:4754062] multipeer session: stop timer
2016-01-17 16:07:17.537 ThaliTest[2208:4754062] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
,mux server bridge listener closed
# setup
,# ThaliReplicationManager replicates database
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/14233146-4A79-4300-8E48-FAC5F17AB5D5/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-17 16:07:18.718 ThaliTest[2208:4754062] jxcore: startBroadcasting
,2016-01-17 16:07:18.719 ThaliTest[2208:4754062] server: starting QE75ym5qNZcpaCgt1-Eowg.ldax6Q==
2016-01-17 16:07:18.720 ThaliTest[2208:4754062] multipeer session: start timer: 0x18ef76d0
2016-01-17 16:07:18.720 ThaliTest[2208:4754062] THEMultipeerSession initialized peer QE75ym5qNZcpaCgt1-Eowg
2016-01-17 16:07:18.720 ThaliTest[2208:4754062] jxcore: startBroadcasting: success
ok 110 getDeviceIdentity should not return an error
ok 111 deviceName should not be null
,2016-01-17 16:07:20.332 ThaliTest[2208:4753876] client: found peer: HUkdoSUWUyMCz2U4yXOTzA.3sdKDA==
,2016-01-17 16:07:22.767 ThaliTest[2208:4754062] jxcore: connect HUkdoSUWUyMCz2U4yXOTzA.3sdKDA==
2016-01-17 16:07:22.767 ThaliTest[2208:4754062] client session: connect
2016-01-17 16:07:22.767 ThaliTest[2208:4754062] client session: stateChange:0->1 HUkdoSUWUyMCz2U4yXOTzA.3sdKDA==
,ok 112 Should be able to put doc without error
,ok 113 1st change of local doc should contain local id
,2016-01-17 16:07:24.718 ThaliTest[2208:4753876] multipeer session: reset timer
2016-01-17 16:07:24.718 ThaliTest[2208:4753876] multipeer session: stop timer
2016-01-17 16:07:24.718 ThaliTest[2208:4753876] multipeer session: start timer: 0x18ef76d0
2016-01-17 16:07:24.718 ThaliTest[2208:4753876] server session: connect
2016-01-17 16:07:24.718 ThaliTest[2208:4753876] server session: stateChange:0->1 HUkdoSUWUyMCz2U4yXOTzA
2016-01-17 16:07:24.721 ThaliTest[2208:4753876] server: accepting invitation HUkdoSUWUyMCz2U4yXOTzA
,2016-01-17 16:07:28.714 ThaliTest[2208:4755955] server session: connected
2016-01-17 16:07:28.714 ThaliTest[2208:4755955] server session: stateChange:1->2 HUkdoSUWUyMCz2U4yXOTzA
,2016-01-17 16:07:28.771 ThaliTest[2208:4753876] server relay: connected (to port: 53209)
,server bridge: new client socket
,2016-01-17 16:07:28.783 ThaliTest[2208:4755858] client session: connected
2016-01-17 16:07:28.783 ThaliTest[2208:4755858] client session: stateChange:1->2 HUkdoSUWUyMCz2U4yXOTzA.3sdKDA==
,2016-01-17 16:07:28.970 ThaliTest[2208:4755857] client session: fireConnectCallback: HUkdoSUWUyMCz2U4yXOTzA.3sdKDA==
2016-01-17 16:07:28.970 ThaliTest[2208:4755857] jxcore: connect: success
,2016-01-17 16:07:28.972 ThaliTest[2208:4753876] client: relay established
2016-01-17 16:07:28.972 ThaliTest[2208:4753876] client: new accepted socket: 0x1a896470
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
client bridge: new client socket
,client bridge: socket closed
client bridge: socket closed
,client bridge: socket closed
,ok 114 1st change of remote doc should contain remote id
,client bridge: new client socket
,ok 115 Can update remote doc without error
,null
,{ ok: true,
  id: 'fc139c43-16fb-4c89-a1f6-ae19186b1b1f',
  rev: '2-cf956746933de9a80270b057e6ffaa34' }
,client bridge: new client socket
,ok 116 Remote changes occur in strict order
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
,ok 117 Local changes occur in strict order
ok 118 2nd change of local doc should contain remote id
,# setup
,client bridge: new client socket
,Now in TRM stop
State of this._isStarted: true
About to call stopBroadcasting
,2016-01-17 16:07:49.022 ThaliTest[2208:4754062] jxcore: stopBroadcasting
2016-01-17 16:07:49.022 ThaliTest[2208:4754062] THEMultipeerSession stopping peer
2016-01-17 16:07:49.022 ThaliTest[2208:4754062] multipeer session: stop timer
2016-01-17 16:07:49.022 ThaliTest[2208:4754062] client session: disconnect
2016-01-17 16:07:49.023 ThaliTest[2208:4754062] client session: stateChange:2->0 HUkdoSUWUyMCz2U4yXOTzA.3sdKDA==
,2016-01-17 16:07:49.025 ThaliTest[2208:4754062] server session: disconnect
2016-01-17 16:07:49.025 ThaliTest[2208:4754062] server session: stateChange:2->0 HUkdoSUWUyMCz2U4yXOTzA
,2016-01-17 16:07:49.090 ThaliTest[2208:4754062] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,# #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
,client bridge: socket closed
,mux server bridge listener closed
,2016-01-17 16:07:49.127 ThaliTest[2208:4754062] Error!: connect ECONNREFUSED
Stack:[{"_fileName":"net.js","_functionName":"errnoException","_lineNumber":"835","_columnNumber":"11","_msg":"    at errnoException@net.js:835:11"},{"_fileName":"net.js","_funct,ionName":"afterConnect","_lineNumber":"827","_columnNumber":"19","_msg":"    at afterConnect@net.js:827:19"},{"_fileName":"net.js","_functionName":"unknown","_lineNumber":835,"_columnNumber":10,"_msg":"    at "}]
,Uncaught Exception: Error: connect ECONNREFUSED
,[ { _fileName: 'net.js',
    _functionName: 'errnoException',
    _lineNumber: '835',
    _columnNumber: '11',
    _msg: '    at errnoException@net.js:835:11' },
  { _fileName: 'net.js',
    _functionName: 'afterConnect',
    _lineNumber: '827',
  ,  _columnNumber: '19',
    _msg: '    at afterConnect@net.js:827:19' },
  { _fileName: 'net.js',
    _functionName: 'unknown',
    _lineNumber: 835,
    _columnNumber: 10,
    _msg: '    at ' },
  toString: [Function] ]
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
