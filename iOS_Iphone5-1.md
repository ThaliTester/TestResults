#### Test 56151093b6ab50f_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56151093b6ab50f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/7B5855A3-6C18-4009-BBD2-202FC37C4CC0/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/7B5855A3-6C18-4009-BBD2-202FC37C4CC0/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/56151093b6ab50f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56151093b6ab50f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/875DFDCB-B68F-49AB-9033-C46C56FE0786/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57611"
,(lldb)     command script import "/tmp/7B5855A3-6C18-4009-BBD2-202FC37C4CC0/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-18 08:33:14.681 ThaliTest[1536:5034518] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C797C31C-DE24-45E3-BA78-2A7DC002DBE9/Library/Cookies/Cookies.binarycookies
,2016-01-18 08:33:14.791 ThaliTest[1536:5034518] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-18 08:33:14.793 ThaliTest[1536:5034518] Multi-tasking -> Device: YES, App: YES
,2016-01-18 08:33:14.798 ThaliTest[1536:5034518] Unlimited access to network resources
,2016-01-18 08:33:14.810 ThaliTest[1536:5034518] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-18 08:33:20.864 ThaliTest[1536:5034518] Resetting plugins due to page load.
,2016-01-18 08:33:23.110 ThaliTest[1536:5034518] Finished load of: file:///var/mobile/Containers/Bundle/Application/875DFDCB-B68F-49AB-9033-C46C56FE0786/ThaliTest.app/www/index.html
,2016-01-18 08:33:23.124 ThaliTest[1536:5034518] JXcore Cordova plugin initializing
2016-01-18 08:33:23.125 ThaliTest[1536:5034843] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/875DFDCB-B68F-49AB-9033-C46C56FE0786/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/875DFDCB-B68F-49AB-9033-C46C56FE0786/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/875DFDCB-B68F-49AB-9033-C46C56FE0786/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/875DFDCB-B68F-49AB-9033-C46C56FE0786/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/875DFDCB-B68F-49AB-9033-C46C56FE0786/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/875DFDCB-B68F-49AB-9033-C46C56FE0786/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/875DFDCB-B68F-49AB-9033-C46C56FE0786/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test app app.js loaded
,appEnteringBackground wasn't registered
,TAP version 13
,# setup
,# multiplex can send data
,# teardown
,ok 1 String should be length:200
# setup
,# basic
,# teardown
,ok 2 sane
,# setup
,# another
,# teardown
,ok 3 sane
# setup
,# successfully create a new pkcs12 file and return hash value
,# teardown
,ok 4 should be equal
,ok 5 null
,ok 6 (unnamed assert)
,ok 7 should be equal
ok 8 should not throw
# setup
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
ok 18 should be equal
# setup
,# #init should register the networkChanged event
,# teardown
,ok 19 should be equal
,# setup
,# #startBroadcasting should throw on null device name
,# teardown
,ok 20 should throw
# setup
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
# setup
,# #startBroadcasting should throw on negative port
,# teardown
,ok 24 should throw
# setup
,# #startBroadcasting should throw on too large port
,# teardown
,ok 25 should throw
# setup
,# #startBroadcasting should call Mobile("StartBroadcasting") without an error
,# teardown
,ok 26 should be equal
ok 27 should be equal
ok 28 should be equal
# setup
,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,# teardown
,ok 29 should be equal
ok 30 should be equal
ok 31 should be equal
# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error
,# teardown
,ok 32 should be equal
ok 33 should be equal
# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,# teardown
,ok 34 should be equal
ok 35 should be equal
# setup
,# #connect should call Mobile("Connect") with a port and without an error
,# teardown
,ok 36 should be equal
ok 37 should be equal
ok 38 should be equal
# setup
,# #connect should call Mobile("Connect") and handle an error
,# teardown
,ok 39 should be equal
ok 40 should be equal
# setup
,# should call Mobile("Disconnect") without an error
,# teardown
,ok 41 should be equal
ok 42 should be equal
# setup
,# should call Mobile("Disconnect") and handle an error
,# teardown
,ok 43 should be equal
ok 44 should be equal
# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2016-01-18 08:39:19.978 ThaliTest[1536:5034843] jxcore: startBroadcasting
,2016-01-18 08:39:19.988 ThaliTest[1536:5034843] server: starting 1453102759977.1536.CGw46g==
2016-01-18 08:39:19.988 ThaliTest[1536:5034843] multipeer session: start timer: 0x18cf5550
2016-01-18 08:39:19.989 ThaliTest[1536:5034843] THEMultipeerSession initialized peer 1453102759977.1536
2016-01-18 08:39:19.989 ThaliTest[1536:5034843] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2016-01-18 08:39:19.990 ThaliTest[1536:5034843] jxcore: stopBroadcasting
,2016-01-18 08:39:19.991 ThaliTest[1536:5034843] THEMultipeerSession stopping peer
2016-01-18 08:39:19.995 ThaliTest[1536:5034843] multipeer session: stop timer
2016-01-18 08:39:19.996 ThaliTest[1536:5034843] jxcore: stopBroadcasting: success
ok 46 Shoul,d be able to call stopBroadcasting without error
2016-01-18 08:39:19.997 ThaliTest[1536:5034843] jxcore: startBroadcasting
,2016-01-18 08:39:20.011 ThaliTest[1536:5034843] server: starting 1453102759997.1536.Qw++SA==
2016-01-18 08:39:20.012 ThaliTest[1536:5034843] multipeer session: start timer: 0x18cf43d0
2016-01-18 08:39:20.012 ThaliTest[1536:5034843] THEMultipeerSession in,itialized peer 1453102759997.1536
2016-01-18 08:39:20.012 ThaliTest[1536:5034843] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-18 08:39:20.013 ThaliTest[1536:5034843] jxcore: stopBroadcasting
2,016-01-18 08:39:20.014 ThaliTest[1536:5034843] THEMultipeerSession stopping peer
,2016-01-18 08:39:20.014 ThaliTest[1536:5034843] multipeer session: stop timer
,2016-01-18 08:39:20.020 ThaliTest[1536:5034843] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
2016-01-18 08:39:20.023 ThaliTest[1536:5034843] jxcore: startBroadcasting
,2016-01-18 08:39:20.030 ThaliTest[1536:5034843] server: starting 1453102760022.1536.Cd7VEQ==
2016-01-18 08:39:20.030 ThaliTest[1536:5034843] multipeer session: start timer: 0x18cf4dd0
2016-01-18 08:39:20.031 ThaliTest[1536:5034843] THEMultipeerSession initialized peer 1453102760022.1536
2016-01-18 08:39:20.031 ThaliTest[1536:5034843] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
,2016-01-18 08:39:20.033 ThaliTest[1536:5034843] jxcore: stopBroadcasting
,2016-01-18 08:39:20.041 ThaliTest[1536:5034843] THEMultipeerSession stopping peer
2016-01-18 08:39:20.048 ThaliTest[1536:5034843] multipeer session: stop timer
2016-01-18 08:39:20.049 ThaliTest[1536:5034843] jxcore: stopBroadcasting: success
ok 50 Shoul,d be able to call stopBroadcasting without error
2016-01-18 08:39:20.050 ThaliTest[1536:5034843] jxcore: startBroadcasting
,2016-01-18 08:39:20.058 ThaliTest[1536:5034843] server: starting 1453102760050.1536.t0R7mg==
2016-01-18 08:39:20.059 ThaliTest[1536:5034843] multipeer session: start timer: 0x18ce8490
2016-01-18 08:39:20.059 ThaliTest[1536:5034843] THEMultipeerSession in,itialized peer 1453102760050.1536
2016-01-18 08:39:20.059 ThaliTest[1536:5034843] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2016-01-18 08:39:20.061 ThaliTest[1536:5034843] jxcore: stopBroadcasting
2,016-01-18 08:39:20.061 ThaliTest[1536:5034843] THEMultipeerSession stopping peer
2016-01-18 08:39:20.061 ThaliTest[1536:5034843] multipeer session: stop timer
2016-01-18 08:39:20.062 ThaliTest[1536:5034843] jxcore: stopBroadcasting: success
ok 52 Should, be able to call stopBroadcasting without error
2016-01-18 08:39:20.063 ThaliTest[1536:5034843] jxcore: startBroadcasting
2016-01-18 08:39:20.067 ThaliTest[1536:5034843] server: starting 1453102760063.1536.QJD3zg==
2016-01-18 08:39:20.067 ThaliTest[153,6,:5034843] multipeer session: start timer: 0x18d62930
,2016-01-18 08:39:20.071 ThaliTest[1536:5034843] THEMultipeerSession initialized peer 1453102760063.1536
2016-01-18 08:39:20.078 ThaliTest[1536:5034843] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2016-,01-18 08:39:20.080 ThaliTest[1536:5034843] jxcore: stopBroadcasting
2016-01-18 08:39:20.080 ThaliTest[1536:5034843] THEMultipeerSession stopping peer
2016-01-18 08:39:20.080 ThaliTest[1536:5034843] multipeer session: stop timer
2016-01-18 08:39:20.081 T,haliTest[1536:5034843] jxcore: stopBroadcasting: success
ok 54 Should be able to call stopBroadcasting without error
,2016-01-18 08:39:20.082 ThaliTest[1536:5034843] jxcore: startBroadcasting
,2016-01-18 08:39:20.093 ThaliTest[1536:5034843] server: starting 1453102760082.1536.rGKXKA==
,2016-01-18 08:39:20.101 ThaliTest[1536:5034843] multipeer session: start timer: 0x18d5e440
,2016-01-18 08:39:20.104 ThaliTest[1536:5034843] THEMultipeerSession initialized peer 1453102760082.1536
,2016-01-18 08:39:20.108 ThaliTest[1536:5034843] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-18 08:39:20.132 ThaliTest[1536:5034843] jxcore: stopBroadcasting
,2016-01-18 08:39:20.133 ThaliTest[1536:5034843] THEMultipeerSession stopping peer
,2016-01-18 08:39:20.134 ThaliTest[1536:5034843] multipeer session: stop timer
,2016-01-18 08:39:20.136 ThaliTest[1536:5034843] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-18 08:39:20.141 ThaliTest[1536:5034843] jxcore: startBroadcasting
,2016-01-18 08:39:20.145 ThaliTest[1536:5034843] server: starting 1453102760141.1536.40QOXQ==
,2016-01-18 08:39:20.147 ThaliTest[1536:5034843] multipeer session: start timer: 0x18cea8f0
,2016-01-18 08:39:20.148 ThaliTest[1536:5034843] THEMultipeerSession initialized peer 1453102760141.1536
,2016-01-18 08:39:20.156 ThaliTest[1536:5034843] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-18 08:39:20.161 ThaliTest[1536:5034843] jxcore: stopBroadcasting
,2016-01-18 08:39:20.162 ThaliTest[1536:5034843] THEMultipeerSession stopping peer
,2016-01-18 08:39:20.163 ThaliTest[1536:5034843] multipeer session: stop timer
,2016-01-18 08:39:20.164 ThaliTest[1536:5034843] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-18 08:39:20.171 ThaliTest[1536:5034843] jxcore: startBroadcasting
,2016-01-18 08:39:20.175 ThaliTest[1536:5034843] server: starting 1453102760171.1536.x1Hb7g==
,2016-01-18 08:39:20.178 ThaliTest[1536:5034843] multipeer session: start timer: 0x18d629c0
,2016-01-18 08:39:20.182 ThaliTest[1536:5034843] THEMultipeerSession initialized peer 1453102760171.1536
,2016-01-18 08:39:20.183 ThaliTest[1536:5034843] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-18 08:39:20.191 ThaliTest[1536:5034843] jxcore: stopBroadcasting
,2016-01-18 08:39:20.192 ThaliTest[1536:5034843] THEMultipeerSession stopping peer
,2016-01-18 08:39:20.195 ThaliTest[1536:5034843] multipeer session: stop timer
,2016-01-18 08:39:20.197 ThaliTest[1536:5034843] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-18 08:39:20.203 ThaliTest[1536:5034843] jxcore: startBroadcasting
,2016-01-18 08:39:20.207 ThaliTest[1536:5034843] server: starting 1453102760203.1536.wBSO9A==
,2016-01-18 08:39:20.209 ThaliTest[1536:5034843] multipeer session: start timer: 0x18ce7410
,2016-01-18 08:39:20.212 ThaliTest[1536:5034843] THEMultipeerSession initialized peer 1453102760203.1536
,2016-01-18 08:39:20.218 ThaliTest[1536:5034843] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-18 08:39:20.221 ThaliTest[1536:5034843] jxcore: stopBroadcasting
,2016-01-18 08:39:20.221 ThaliTest[1536:5034843] THEMultipeerSession stopping peer
,2016-01-18 08:39:20.222 ThaliTest[1536:5034843] multipeer session: stop timer
,2016-01-18 08:39:20.223 ThaliTest[1536:5034843] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-18 08:39:20.229 ThaliTest[1536:5034843] jxcore: startBroadcasting
,2016-01-18 08:39:20.231 ThaliTest[1536:5034843] server: starting 1453102760228.1536.eYZIYg==
,2016-01-18 08:39:20.232 ThaliTest[1536:5034843] multipeer session: start timer: 0x18ce7df0
,2016-01-18 08:39:20.234 ThaliTest[1536:5034843] THEMultipeerSession initialized peer 1453102760228.1536
,2016-01-18 08:39:20.236 ThaliTest[1536:5034843] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-18 08:39:20.243 ThaliTest[1536:5034843] jxcore: stopBroadcasting
,2016-01-18 08:39:20.244 ThaliTest[1536:5034843] THEMultipeerSession stopping peer
,2016-01-18 08:39:20.245 ThaliTest[1536:5034843] multipeer session: stop timer
,2016-01-18 08:39:20.246 ThaliTest[1536:5034843] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-18 08:39:20.390 ThaliTest[1536:5034843] jxcore: startBroadcasting
,2016-01-18 08:39:20.393 ThaliTest[1536:5034843] server: starting 1453102760389.1536.Xc8z0g==
2016-01-18 08:39:20.393 ThaliTest[1536:5034843] multipeer session: start timer: 0x1456ff20
2016-01-18 08:39:20.393 ThaliTest[1536:5034843] THEMultipeerSession in,itialized peer 1453102760389.1536
2016-01-18 08:39:20.394 ThaliTest[1536:5034843] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-18 08:39:20.395 ThaliTest[1536:5034843] jxcore: startBroadcasting
,2016-01-18 08:39:20.395 ThaliTest[1536:5034843] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
2016-01-18 08:39:20.396 ThaliTest[1536:5034843] jxcore: stopBroadcasting
2016-01-18 08:39:20.399 ThaliTest[1536:5034843] THEMult,ipeerSession stopping peer
2016-01-18 08:39:20.399 ThaliTest[1536:5034843] multipeer session: stop timer
2016-01-18 08:39:20.399 ThaliTest[1536:5034843] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-18 08:39:21.953 ThaliTest[1536:5034843] jxcore: startBroadcasting
,2016-01-18 08:39:21.955 ThaliTest[1536:5034843] server: starting 1453102761953.1536.jMd79g==
2016-01-18 08:39:21.956 ThaliTest[1536:5034843] multipeer session: start timer: 0x18d504d0
2016-01-18 08:39:21.956 ThaliTest[1536:5034843] THEMultipeerSession initialized peer 1453102761953.1536
2016-01-18 08:39:21.956 ThaliTest[1536:5034843] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-18 08:39:21.958 ThaliTest[1536:5034843] jxcore: connect foobar
201,6-01-18 08:39:21.958 ThaliTest[1536:5034843] client: unknown peer foobar
,2016-01-18 08:39:21.958 ThaliTest[1536:5034843] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
2016-01-18 08:39:21.964 ThaliTest[1536:5034843] jxcore: stopBroadcasting
2016-01-18 08:39:21.964 ThaliTest[1536:5034843] THEMultip,eerSession stopping peer
2016-01-18 08:39:21.964 ThaliTest[1536:5034843] multipeer session: stop timer
2016-01-18 08:39:21.964 ThaliTest[1536:5034843] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
# setup,
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-18 08:39:25.174 ThaliTest[1536:5034843] jxcore: startBroadcasting
,2016-01-18 08:39:25.177 ThaliTest[1536:5034843] server: starting 1453102765174.1536.CQPICQ==
2016-01-18 08:39:25.178 ThaliTest[1536:5034843] multipeer session: start timer: 0x18cd34f0
2016-01-18 08:39:25.178 ThaliTest[1536:5034843] THEMultipeerSession in,itialized peer 1453102765174.1536
2016-01-18 08:39:25.178 ThaliTest[1536:5034843] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-18 08:39:25.179 ThaliTest[1536:5034843] jxcore: disconnect
2016-01,-18 08:39:25.180 ThaliTest[1536:5034843] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
,2016-01-18 08:39:25.181 ThaliTest[1536:5034843] jxcore: stopBroadcasting
2016-01-18 08:39:25.187 ThaliTest[1536:5034843] THEMultipeerSession stopping peer
2016-01-18 08:39:25.187 ThaliTest[1536:5034843] multipeer session: stop timer
2016-01-18 08:39:25.187 ThaliTest[1536:5034843] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-18 08:39:27.563 ThaliTest[1536:5034843] jxcore: startBroadcasting
,2016-01-18 08:39:27.566 ThaliTest[1536:5034843] server: starting 1453102767563.1536.tib1Mw==
2016-01-18 08:39:27.566 ThaliTest[1536:5034843] multipeer session: start timer: 0x18d47940
2016-01-18 08:39:27.566 ThaliTest[1536:5034843] THEMultipeerSession in,itialized peer 1453102767563.1536
2016-01-18 08:39:27.566 ThaliTest[1536:5034843] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-18 08:39:34.528 ThaliTest[1536:5034518] client: found peer: 1453102767567.2181.gvG8Vg==
2016-01-18 08:39:34.529 ThaliTest[1536:5034843] jxcore: connect 1453102767567.2181.gvG8Vg==
2016-01-18 08:39:34.529 ThaliTest[1536:5034843] client session: co,nnect
2016-01-18 08:39:34.530 ThaliTest[1536:5034843] client session: stateChange:0->1 1453102767567.2181.gvG8Vg==
,2016-01-18 08:39:35.708 ThaliTest[1536:5034518] multipeer session: reset timer
2016-01-18 08:39:35.709 ThaliTest[1536:5034518] multipeer session: stop timer
2016-01-18 08:39:35.709 ThaliTest[1536:5034518] multipeer session: start timer: 0x18d47940
2016-,01-18 08:39:35.709 ThaliTest[1536:5034518] server session: connect
,2016-01-18 08:39:35.709 ThaliTest[1536:5034518] server session: stateChange:0->1 1453102767567.2181
,2016-01-18 08:39:35.716 ThaliTest[1536:5034518] server: accepting invitation 1453102767567.2181
,2016-01-18 08:39:38.325 ThaliTest[1536:5035568] server session: connected
2016-01-18 08:39:38.325 ThaliTest[1536:5035568] server session: stateChange:1->2 1453102767567.2181
,2016-01-18 08:39:38.332 ThaliTest[1536:5034518] server relay: socket disconnected
2016-01-18 08:39:38.332 ThaliTest[1536:5034518] server relay: 0x18d3ec70 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-18 08:39:38.588 ThaliTest[1536:5035568] server session: not connected 1453102767567.2181
,2016-01-18 08:39:38.705 ThaliTest[1536:5035570] client session: connected
,2016-01-18 08:39:38.705 ThaliTest[1536:5035570] client session: stateChange:1->2 1453102767567.2181.gvG8Vg==
,2016-01-18 08:39:38.714 ThaliTest[1536:5035570] client session: fireConnectCallback: 1453102767567.2181.gvG8Vg==
,2016-01-18 08:39:38.715 ThaliTest[1536:5035570] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2016-01-18 08:39:38.720 ThaliTest[1536:5034843] jxcore: disconnect
,2016-01-18 08:39:38.721 ThaliTest[1536:5034843] client session: disconnectFromPeer: 1453102767567.2181.gvG8Vg==
,2016-01-18 08:39:38.721 ThaliTest[1536:5034843] client session: disconnect
,2016-01-18 08:39:38.721 ThaliTest[1536:5034843] client session: stateChange:2->0 1453102767567.2181.gvG8Vg==
,2016-01-18 08:39:38.730 ThaliTest[1536:5034843] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
2016-01-18 08:39:40.613 ThaliTest[1536:5034843] jxcore: stopBroadcasting
2016-01-18 08:39:40.613 ThaliTest[1536:5034843] THEMultipeerSession stopping peer
2016-01-18 08:39:40.613 ThaliTest[1536:5034843] multipeer session: stop t,imer
2016-01-18 08:39:40.614 ThaliTest[1536:5034843] server session: disconnect
2016-01-18 08:39:40.614 ThaliTest[1536:5034843] server session: stateChange:2->0 1453102767567.2181
,2016-01-18 08:39:41.530 ThaliTest[1536:5034843] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-18 08:40:18.199 ThaliTest[1536:5034843] jxcore: startBroadcasting
,2016-01-18 08:40:18.201 ThaliTest[1536:5034843] server: starting 1453102818198.1536.g1dlEA==
2016-01-18 08:40:18.202 ThaliTest[1536:5034843] multipeer session: start timer: 0x18cbc5c0
2016-01-18 08:40:18.202 ThaliTest[1536:5034843] THEMultipeerSession initialized peer 1453102818198.1536
2016-01-18 08:40:18.202 ThaliTest[1536:5034843] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-18 08:40:48.203 ThaliTest[1536:5034518] multipeer session: restart
,2016-01-18 08:41:04.768 ThaliTest[1536:5034518] multipeer session: reset timer
2016-01-18 08:41:04.769 ThaliTest[1536:5034518] multipeer session: stop timer
2016-01-18 08:41:04.769 ThaliTest[1536:5034518] multipeer session: start timer: 0x18cbc5c0
2016-,01-18 08:41:04.769 ThaliTest[1536:5034518] server session: connect
2016-01-18 08:41:04.769 ThaliTest[1536:5034518] server session: stateChange:0->1 1453102825800.2181
2016-01-18 08:41:04.775 ThaliTest[1536:5034518] server: accepting invitation 1453102825800.2181
,2016-01-18 08:41:07.405 ThaliTest[1536:5035783] server session: connected
2016-01-18 08:41:07.407 ThaliTest[1536:5035783] server session: stateChange:1->2 1453102825800.2181
,2016-01-18 08:41:07.414 ThaliTest[1536:5034518] server relay: socket disconnected
2016-01-18 08:41:07.415 ThaliTest[1536:5034518] server relay: 0x18cbafa0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-18 08:41:07.441 ThaliTest[1536:5035802] server session: not connected 1453102825800.2181
,2016-01-18 08:41:34.770 ThaliTest[1536:5034518] multipeer session: restart
,2016-01-18 08:41:34.794 ThaliTest[1536:5034518] client: found peer: 1453102825800.2181.3XRr+A==
2016-01-18 08:41:34.795 ThaliTest[1536:5034843] jxcore: connect 1453102825800.2181.3XRr+A==
2016-01-18 08:41:34.795 ThaliTest[1536:5034843] client session: connect
2016-01-18 08:41:34.795 ThaliTest[1536:5034843] client session: stateChange:0->1 1453102825800.2181.3XRr+A==
,2016-01-18 08:41:38.310 ThaliTest[1536:5035864] client session: connected
2016-01-18 08:41:38.313 ThaliTest[1536:5035864] client session: stateChange:1->2 1453102825800.2181.3XRr+A==
2016-01-18 08:41:38.315 ThaliTest[1536:5035864] client session: fireCon,nectCallback: 1453102825800.2181.3XRr+A==
2016-01-18 08:41:38.315 ThaliTest[1536:5035864] jxcore: connect: success
ok 79 Should be able to connect without error
ok 80 Port should be within range
2016-01-18 08:41:38.317 ThaliTest[1536:5034843] jxcore: c,onnect 1453102825800.2181.3XRr+A==
2016-01-18 08:41:38.318 ThaliTest[1536:5034843] client: already connect(ing/ed) to 1453102825800.2181.3XRr+A==
2016-01-18 08:41:38.318 ThaliTest[1536:5034843] jxcore: connect: fail: Aleady connecting
ok 81 Should fail ,on double connect
2016-01-18 08:41:38.319 ThaliTest[1536:5034843] jxcore: disconnect
2016-01-18 08:41:38.319 ThaliTest[1536:5034843] client session: disconnectFromPeer: 1453102825800.2181.3XRr+A==
2016-01-18 08:41:38.319 ThaliTest[1536:5034843] client ,session: disconnect
,2016-01-18 08:41:38.322 ThaliTest[1536:5034843] client session: stateChange:2->0 1453102825800.2181.3XRr+A==
,2016-01-18 08:41:38.393 ThaliTest[1536:5034843] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-18 08:42:04.769 ThaliTest[1536:5034518] multipeer session: restart
,2016-01-18 08:42:04.797 ThaliTest[1536:5034518] client: found peer: 1453102825800.2181.3XRr+A==
,2016-01-18 08:42:34.770 ThaliTest[1536:5034518] multipeer session: restart
,2016-01-18 08:42:34.795 ThaliTest[1536:5034518] client: found peer: 1453102825800.2181.3XRr+A==
,2016-01-18 08:43:04.770 ThaliTest[1536:5034518] multipeer session: restart
,2016-01-18 08:43:04.796 ThaliTest[1536:5034518] client: found peer: 1453102825800.2181.3XRr+A==
,2016-01-18 08:43:13.107 ThaliTest[1536:5034518] client: lost peer: 1453102825800.2181.3XRr+A==
2016-01-18 08:43:13.107 ThaliTest[1536:5034518] client session: onPeerLost: 1453102825800.2181.3XRr+A==
,2016-01-18 08:43:34.770 ThaliTest[1536:5034518] multipeer session: restart
,2016-01-18 08:44:04.770 ThaliTest[1536:5034518] multipeer session: restart
,2016-01-18 08:44:31.771 ThaliTest[1536:5034518] client: found peer: 1453102825800.2181.3XRr+A==
,2016-01-18 08:44:34.770 ThaliTest[1536:5034518] multipeer session: restart
,2016-01-18 08:45:04.770 ThaliTest[1536:5034518] multipeer session: restart
,2016-01-18 08:45:04.792 ThaliTest[1536:5034518] client: found peer: 1453102825800.2181.3XRr+A==
,2016-01-18 08:45:34.770 ThaliTest[1536:5034518] multipeer session: restart
,2016-01-18 08:46:04.770 ThaliTest[1536:5034518] multipeer session: restart
,2016-01-18 08:46:04.793 ThaliTest[1536:5034518] client: found peer: 1453102825800.2181.3XRr+A==
,2016-01-18 08:46:34.770 ThaliTest[1536:5034518] multipeer session: restart
,2016-01-18 08:46:34.790 ThaliTest[1536:5034518] client: found peer: 1453102825800.2181.3XRr+A==
,2016-01-18 08:47:04.770 ThaliTest[1536:5034518] multipeer session: restart
,2016-01-18 08:47:34.770 ThaliTest[1536:5034518] multipeer session: restart
,2016-01-18 08:47:34.793 ThaliTest[1536:5034518] client: found peer: 1453102825800.2181.3XRr+A==
,2016-01-18 08:48:04.770 ThaliTest[1536:5034518] multipeer session: restart
,2016-01-18 08:48:04.786 ThaliTest[1536:5034518] client: found peer: 1453102825800.2181.3XRr+A==
,2016-01-18 08:48:34.770 ThaliTest[1536:5034518] multipeer session: restart
,2016-01-18 08:48:34.806 ThaliTest[1536:5034518] client: found peer: 1453102825800.2181.3XRr+A==
,2016-01-18 08:49:04.770 ThaliTest[1536:5034518] multipeer session: restart
,2016-01-18 08:49:04.995 ThaliTest[1536:5034518] client: found peer: 1453102825800.2181.3XRr+A==
,2016-01-18 08:49:34.698 ThaliTest[1536:5034518] multipeer session: restart
,2016-01-18 08:49:34.729 ThaliTest[1536:5034518] client: found peer: 1453102825800.2181.3XRr+A==
,2016-01-18 08:50:04.698 ThaliTest[1536:5034518] multipeer session: restart
,2016-01-18 08:50:04.998 ThaliTest[1536:5034518] client: found peer: 1453102825800.2181.3XRr+A==
,2016-01-18 08:50:34.698 ThaliTest[1536:5034518] multipeer session: restart
,2016-01-18 08:50:34.920 ThaliTest[1536:5034518] client: found peer: 1453102825800.2181.3XRr+A==
,2016-01-18 08:51:04.698 ThaliTest[1536:5034518] multipeer session: restart
,2016-01-18 08:51:04.720 ThaliTest[1536:5034518] client: found peer: 1453102825800.2181.3XRr+A==

```
