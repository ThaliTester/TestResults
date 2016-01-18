#### Test 56151093b6ab50f_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56151093b6ab50f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A08A163B-1C3F-4A73-B52E-ACB0FEC4012E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A08A163B-1C3F-4A73-B52E-ACB0FEC4012E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/56151093b6ab50f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56151093b6ab50f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EDC2AE91-BF37-4D92-AB38-D5A57EF33016/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57640"
,(lldb)     command script import "/tmp/A08A163B-1C3F-4A73-B52E-ACB0FEC4012E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-18 08:33:43.201 ThaliTest[2181:4611927] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F91BF076-3796-414C-8F71-0052F4737424/Library/Cookies/Cookies.binarycookies
,2016-01-18 08:33:43.439 ThaliTest[2181:4611927] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-18 08:33:43.440 ThaliTest[2181:4611927] Multi-tasking -> Device: YES, App: YES
,2016-01-18 08:33:43.447 ThaliTest[2181:4611927] Unlimited access to network resources
,2016-01-18 08:33:43.455 ThaliTest[2181:4611927] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-18 08:33:47.606 ThaliTest[2181:4611927] Resetting plugins due to page load.
,2016-01-18 08:33:48.982 ThaliTest[2181:4611927] Finished load of: file:///var/mobile/Containers/Bundle/Application/EDC2AE91-BF37-4D92-AB38-D5A57EF33016/ThaliTest.app/www/index.html
,2016-01-18 08:33:49.144 ThaliTest[2181:4611927] JXcore Cordova plugin initializing
,2016-01-18 08:33:49.146 ThaliTest[2181:4612060] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EDC2AE91-BF37-4D92-AB38-D5A57EF33016/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EDC2AE91-BF37-4D92-AB38-D5A57EF33016/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EDC2AE91-BF37-4D92-AB38-D5A57EF33016/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EDC2AE91-BF37-4D92-AB38-D5A57EF33016/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EDC2AE91-BF37-4D92-AB38-D5A57EF33016/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EDC2AE91-BF37-4D92-AB38-D5A57EF33016/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EDC2AE91-BF37-4D92-AB38-D5A57EF33016/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
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
ok 6 (unnamed assert)
,ok 7 should be equal
ok 8 should not throw
# setup
,# successfully read a previous pkcs12 file and return hash value
,# teardown
,ok 9 (unnamed assert)
,ok 10 (unnamed assert)
,ok 11 should not throw
,ok 12 should be equal
ok 13 should be equal
# setup
,# failed to extract public key because of corrupt pkcs12 file
,# teardown
,ok 14 should be equal
,# setup
,# failed to get mobile documents path
,# teardown
,ok 15 should be equal
# setup
,# #init should register the peerAvailabilityChanged event
,# teardown
,ok 16 should be equal
ok 17 should be equal
ok 18 should be equal
# setup
,# #init should register the networkChanged event
,# teardown
,ok 19 should be equal
# setup
,# #startBroadcasting should throw on null device name
,# teardown
,ok 20 should throw
# setup
,# #startBroadcasting should throw on empty string device name
,# teardown
,ok 21 should throw
# setup
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
,# setup
,# should call Mobile("Disconnect") without an error
,# teardown
,ok 41 should be equal
ok 42 should be equal
# setup
,# should call Mobile("Disconnect") and handle an error
,# teardown
,ok 43 should be equal
,ok 44 should be equal
# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2016-01-18 08:39:19.977 ThaliTest[2181:4612060] jxcore: startBroadcasting
,2016-01-18 08:39:19.983 ThaliTest[2181:4612060] server: starting 1453102759977.2181.iyGH+g==
2016-01-18 08:39:19.984 ThaliTest[2181:4612060] multipeer session: start timer: 0x16676d60
2016-01-18 08:39:19.984 ThaliTest[2181:4612060] THEMultipeerSession in,itialized peer 1453102759977.2181
2016-01-18 08:39:19.984 ThaliTest[2181:4612060] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2016-01-18 08:39:19.985 ThaliTest[2181:4612060] jxcore: stopBroadcasting
2016-01-18 08:39:19.985 ThaliTest[2181:4612060] THEMultipeerSession stopping peer
2016-01-18 08:39:19.988 ThaliTest[2181:4612060] multipeer session: stop timer
,2016-01-18 08:39:19.989 ThaliTest[2181:4612060] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-18 08:39:19.989 ThaliTest[2181:4612060] jxcore: startBroadcasting
,2016-01-18 08:39:19.996 ThaliTest[2181:4612060] server: starting 1453102759989.2181.RlIGpg==
2016-01-18 08:39:19.996 ThaliTest[2181:4612060] multipeer session: start timer: 0x16459550
2016-01-18 08:39:19.996 ThaliTest[2181:4612060] THEMultipeerSession initialized peer 1453102759989.2181
2016-01-18 08:39:19.996 ThaliTest[2181:4612060] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
,2016-01-18 08:39:19.997 ThaliTest[2181:4612060] jxcore: stopBroadcasting
2016-01-18 08:39:20.000 ThaliTest[2181:4612060] THEMultipeerSession stopping peer
2016-01-18 08:39:20.001 ThaliTest[2181:4612060] multipeer session: stop timer
2016-01-18 08:39:20.001 ThaliTest[2181:4612060] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
,2016-01-18 08:39:20.001 ThaliTest[2181:4612060] jxcore: startBroadcasting
,2016-01-18 08:39:20.007 ThaliTest[2181:4612060] server: starting 1453102760001.2181.fwFNew==
2016-01-18 08:39:20.008 ThaliTest[2181:4612060] multipeer session: start timer: 0x166710f0
2016-01-18 08:39:20.008 ThaliTest[2181:4612060] THEMultipeerSession initialized peer 1453102760001.2181
2016-01-18 08:39:20.008 ThaliTest[2181:4612060] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2016-01-18 08:39:20.008 ThaliTest[2181:4612060] jxcore: stopBroadcasting
2,016-01-18 08:39:20.008 ThaliTest[2181:4612060] THEMultipeerSession stopping peer
2016-01-18 08:39:20.009 ThaliTest[2181:4612060] multipeer session: stop timer
,2016-01-18 08:39:20.009 ThaliTest[2181:4612060] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error
2016-01-18 08:39:20.012 ThaliTest[2181:4612060] jxcore: startBroadcasting
,2016-01-18 08:39:20.018 ThaliTest[2181:4612060] server: starting 1453102760011.2181.mVgUfw==
2016-01-18 08:39:20.018 ThaliTest[2181:4612060] multipeer session: start timer: 0x1666b490
2016-01-18 08:39:20.018 ThaliTest[2181:4612060] THEMultipeerSession in,itialized peer 1453102760011.2181
2016-01-18 08:39:20.019 ThaliTest[2181:4612060] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2016-01-18 08:39:20.020 ThaliTest[2181:4612060] jxcore: stopBroadcasting
2,016-01-18 08:39:20.020 ThaliTest[2181:4612060] THEMultipeerSession stopping peer
2016-01-18 08:39:20.020 ThaliTest[2181:4612060] multipeer session: stop timer
2016-01-18 08:39:20.020 ThaliTest[2181:4612060] jxcore: stopBroadcasting: success
ok 52 Should, be able to call stopBroadcasting without error
2016-01-18 08:39:20.021 ThaliTest[2181:4612060] jxcore: startBroadcasting
,2016-01-18 08:39:20.025 ThaliTest[2181:4612060] server: starting 1453102760021.2181.rA4yvw==
2016-01-18 08:39:20.025 ThaliTest[2181:4612060] multipeer session: start timer: 0x1666c250
2016-01-18 08:39:20.025 ThaliTest[2181:4612060] THEMultipeerSession initialized peer 1453102760021.2181
2016-01-18 08:39:20.025 ThaliTest[2181:4612060] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2016-01-18 08:39:20.026 ThaliTest[2181:4612060] jxcore: stopBroadcasting
2,016-01-18 08:39:20.026 ThaliTest[2181:4612060] THEMultipeerSession stopping peer
,2016-01-18 08:39:20.026 ThaliTest[2181:4612060] multipeer session: stop timer
,2016-01-18 08:39:20.032 ThaliTest[2181:4612060] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-18 08:39:20.036 ThaliTest[2181:4612060] jxcore: startBroadcasting
,2016-01-18 08:39:20.037 ThaliTest[2181:4612060] server: starting 1453102760035.2181.DdWiew==
,2016-01-18 08:39:20.039 ThaliTest[2181:4612060] multipeer session: start timer: 0x164582f0
,2016-01-18 08:39:20.042 ThaliTest[2181:4612060] THEMultipeerSession initialized peer 1453102760035.2181
,2016-01-18 08:39:20.043 ThaliTest[2181:4612060] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-18 08:39:20.044 ThaliTest[2181:4612060] jxcore: stopBroadcasting
,2016-01-18 08:39:20.045 ThaliTest[2181:4612060] THEMultipeerSession stopping peer
,2016-01-18 08:39:20.045 ThaliTest[2181:4612060] multipeer session: stop timer
,2016-01-18 08:39:20.048 ThaliTest[2181:4612060] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-18 08:39:20.049 ThaliTest[2181:4612060] jxcore: startBroadcasting
,2016-01-18 08:39:20.051 ThaliTest[2181:4612060] server: starting 1453102760049.2181.Z3g1aA==
,2016-01-18 08:39:20.053 ThaliTest[2181:4612060] multipeer session: start timer: 0x16662fd0
,2016-01-18 08:39:20.056 ThaliTest[2181:4612060] THEMultipeerSession initialized peer 1453102760049.2181
,2016-01-18 08:39:20.056 ThaliTest[2181:4612060] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-18 08:39:20.058 ThaliTest[2181:4612060] jxcore: stopBroadcasting
,2016-01-18 08:39:20.058 ThaliTest[2181:4612060] THEMultipeerSession stopping peer
,2016-01-18 08:39:20.059 ThaliTest[2181:4612060] multipeer session: stop timer
,2016-01-18 08:39:20.062 ThaliTest[2181:4612060] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-18 08:39:20.063 ThaliTest[2181:4612060] jxcore: startBroadcasting
,2016-01-18 08:39:20.065 ThaliTest[2181:4612060] server: starting 1453102760063.2181.MsZvHg==
,2016-01-18 08:39:20.067 ThaliTest[2181:4612060] multipeer session: start timer: 0x16662fd0
,2016-01-18 08:39:20.069 ThaliTest[2181:4612060] THEMultipeerSession initialized peer 1453102760063.2181
,2016-01-18 08:39:20.070 ThaliTest[2181:4612060] jxcore: startBroadcasting: success
ok 59 Should be able to call startBroadcasting without error
,2016-01-18 08:39:20.071 ThaliTest[2181:4612060] jxcore: stopBroadcasting
,2016-01-18 08:39:20.072 ThaliTest[2181:4612060] THEMultipeerSession stopping peer
,2016-01-18 08:39:20.073 ThaliTest[2181:4612060] multipeer session: stop timer
,2016-01-18 08:39:20.074 ThaliTest[2181:4612060] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-18 08:39:20.076 ThaliTest[2181:4612060] jxcore: startBroadcasting
,2016-01-18 08:39:20.078 ThaliTest[2181:4612060] server: starting 1453102760076.2181.SpviFw==
,2016-01-18 08:39:20.080 ThaliTest[2181:4612060] multipeer session: start timer: 0x1666db50
,2016-01-18 08:39:20.083 ThaliTest[2181:4612060] THEMultipeerSession initialized peer 1453102760076.2181
,2016-01-18 08:39:20.083 ThaliTest[2181:4612060] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-18 08:39:20.085 ThaliTest[2181:4612060] jxcore: stopBroadcasting
,2016-01-18 08:39:20.085 ThaliTest[2181:4612060] THEMultipeerSession stopping peer
,2016-01-18 08:39:20.086 ThaliTest[2181:4612060] multipeer session: stop timer
,2016-01-18 08:39:20.089 ThaliTest[2181:4612060] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-18 08:39:20.090 ThaliTest[2181:4612060] jxcore: startBroadcasting
,2016-01-18 08:39:20.092 ThaliTest[2181:4612060] server: starting 1453102760090.2181.4/pP+w==
,2016-01-18 08:39:20.093 ThaliTest[2181:4612060] multipeer session: start timer: 0x16458910
,2016-01-18 08:39:20.096 ThaliTest[2181:4612060] THEMultipeerSession initialized peer 1453102760090.2181
,2016-01-18 08:39:20.097 ThaliTest[2181:4612060] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-18 08:39:20.098 ThaliTest[2181:4612060] jxcore: stopBroadcasting
,2016-01-18 08:39:20.099 ThaliTest[2181:4612060] THEMultipeerSession stopping peer
,2016-01-18 08:39:20.100 ThaliTest[2181:4612060] multipeer session: stop timer
,2016-01-18 08:39:20.102 ThaliTest[2181:4612060] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-18 08:39:20.389 ThaliTest[2181:4612060] jxcore: startBroadcasting
,2016-01-18 08:39:20.391 ThaliTest[2181:4612060] server: starting 1453102760389.2181.D312dQ==
2016-01-18 08:39:20.391 ThaliTest[2181:4612060] multipeer session: start timer: 0x16663530
,2016-01-18 08:39:20.391 ThaliTest[2181:4612060] THEMultipeerSession initialized peer 1453102760389.2181
2016-01-18 08:39:20.392 ThaliTest[2181:4612060] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
2016-01-18 08:39:20.393 ThaliTest[2181:4612060] jxcore: startBroadcasting
2016-01-18 08:39:20.393 ThaliTest[2181:4612060] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
2016-01-18 08:39:20.394 ThaliTest[2181:4612060] jxcore: stopBroadcasting
2016-01-18 08:39:20.394 ThaliTest[2181:4612060] THEMultipeerSession stopping peer
2016-01-18 08:39:20.395 ThaliTest[2181:4612060] multipeer session: stop timer
2016-01-18 08:39:20.395 ThaliTest[2181:4612060] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-18 08:39:21.336 ThaliTest[2181:4612060] jxcore: startBroadcasting
,2016-01-18 08:39:21.338 ThaliTest[2181:4612060] server: starting 1453102761336.2181.wCV85Q==
2016-01-18 08:39:21.339 ThaliTest[2181:4612060] multipeer session: start timer: 0x16658030
2016-01-18 08:39:21.339 ThaliTest[2181:4612060] THEMultipeerSession in,itialized peer 1453102761336.2181
2016-01-18 08:39:21.339 ThaliTest[2181:4612060] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-18 08:39:21.340 ThaliTest[2181:4612060] jxcore: connect foobar
201,6-01-18 08:39:21.340 ThaliTest[2181:4612060] client: unknown peer foobar
2016-01-18 08:39:21.340 ThaliTest[2181:4612060] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
2016-01-18 08:39:21.341 ThaliTest[2181:4612060] jxcore: s,topBroadcasting
2016-01-18 08:39:21.341 ThaliTest[2181:4612060] THEMultipeerSession stopping peer
2016-01-18 08:39:21.341 ThaliTest[2181:4612060] multipeer session: stop timer
2016-01-18 08:39:21.341 ThaliTest[2181:4612060] jxcore: stopBroadcasting: suc,cess
ok 70 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-18 08:39:25.502 ThaliTest[2181:4612060] jxcore: startBroadcasting
,2016-01-18 08:39:25.504 ThaliTest[2181:4612060] server: starting 1453102765502.2181.NV/TPQ==
2016-01-18 08:39:25.504 ThaliTest[2181:4612060] multipeer session: start timer: 0x16441930
2016-01-18 08:39:25.505 ThaliTest[2181:4612060] THEMultipeerSession initialized peer 1453102765502.2181
2016-01-18 08:39:25.505 ThaliTest[2181:4612060] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-18 08:39:25.505 ThaliTest[2181:4612060] jxcore: disconnect
2016-01-18 08:39:25.506 ThaliTest[2181:4612060] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
,2016-01-18 08:39:25.506 ThaliTest[2181:4612060] jxcore: stopBroadcasting
2016-01-18 08:39:25.509 ThaliTest[2181:4612060] THEMultipeerSession stopping peer
2016-01-18 08:39:25.510 ThaliTest[2181:4612060] multipeer session: stop timer
2016-01-18 08:39:25.,510 ThaliTest[2181:4612060] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-18 08:39:27.567 ThaliTest[2181:4612060] jxcore: startBroadcasting
,2016-01-18 08:39:27.568 ThaliTest[2181:4612060] server: starting 1453102767567.2181.gvG8Vg==
2016-01-18 08:39:27.568 ThaliTest[2181:4612060] multipeer session: start timer: 0x1643f1b0
2016-01-18 08:39:27.569 ThaliTest[2181:4612060] THEMultipeerSession in,itialized peer 1453102767567.2181
2016-01-18 08:39:27.569 ThaliTest[2181:4612060] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-18 08:39:35.165 ThaliTest[2181:4611927] client: found peer: 1453102767563.1536.tib1Mw==
2016-01-18 08:39:35.165 ThaliTest[2181:4612060] jxcore: connect 1453102767563.1536.tib1Mw==
2016-01-18 08:39:35.166 ThaliTest[2181:4612060] client session: connect
2016-01-18 08:39:35.166 ThaliTest[2181:4612060] client session: stateChange:0->1 1453102767563.1536.tib1Mw==
,2016-01-18 08:39:35.704 ThaliTest[2181:4611927] multipeer session: reset timer
2016-01-18 08:39:35.704 ThaliTest[2181:4611927] multipeer session: stop timer
2016-01-18 08:39:35.704 ThaliTest[2181:4611927] multipeer session: start timer: 0x1643f1b0
2016-,01-18 08:39:35.704 ThaliTest[2181:4611927] server session: connect
2016-01-18 08:39:35.704 ThaliTest[2181:4611927] server session: stateChange:0->1 1453102767563.1536
,2016-01-18 08:39:35.708 ThaliTest[2181:4611927] server: accepting invitation 1453102767563.1536
,2016-01-18 08:39:38.323 ThaliTest[2181:4612609] client session: connected
2016-01-18 08:39:38.323 ThaliTest[2181:4612609] client session: stateChange:1->2 1453102767563.1536.tib1Mw==
,2016-01-18 08:39:38.330 ThaliTest[2181:4612656] client session: fireConnectCallback: 1453102767563.1536.tib1Mw==
2016-01-18 08:39:38.330 ThaliTest[2181:4612656] jxcore: connect: success
,ok 75 Should be able to connect without error
ok 76 Port should be within range
2016-01-18 08:39:38.332 ThaliTest[2181:4612060] jxcore: disconnect
2016-01-18 08:39:38.332 ThaliTest[2181:4612060] client session: disconnectFromPeer: 1453102767563.1536.tib1Mw==
,2016-01-18 08:39:38.332 ThaliTest[2181:4612060] client session: disconnect
2016-01-18 08:39:38.333 ThaliTest[2181:4612060] client session: stateChange:2->0 1453102767563.1536.tib1Mw==
,2016-01-18 08:39:38.337 ThaliTest[2181:4612060] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-18 08:39:38.664 ThaliTest[2181:4612609] server session: connected
2016-01-18 08:39:38.665 ThaliTest[2181:4612609] server session: stateChange:1->2 1453102767563.1536
,2016-01-18 08:39:38.715 ThaliTest[2181:4611927] server relay: socket disconnected
2016-01-18 08:39:38.716 ThaliTest[2181:4611927] server relay: 0x1664cb90 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-18 08:39:38.781 ThaliTest[2181:4612602] server session: not connected 1453102767563.1536
,2016-01-18 08:39:41.860 ThaliTest[2181:4611927] client: lost peer: 1453102767563.1536.tib1Mw==
2016-01-18 08:39:41.860 ThaliTest[2181:4611927] client session: onPeerLost: 1453102767563.1536.tib1Mw==
,calling stopBroadcasting
,2016-01-18 08:39:45.087 ThaliTest[2181:4612060] jxcore: stopBroadcasting
2016-01-18 08:39:45.087 ThaliTest[2181:4612060] THEMultipeerSession stopping peer
2016-01-18 08:39:45.087 ThaliTest[2181:4612060] multipeer session: stop timer
2016-01-18 08:39:45.088 ThaliTest[2181:4612060] server session: disconnect
2016-01-18 08:39:45.088 ThaliTest[2181:4612060] server session: stateChange:2->0 1453102767563.1536
2016-01-18 08:39:45.088 ThaliTest[2181:4612060] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-18 08:40:25.800 ThaliTest[2181:4612060] jxcore: startBroadcasting
,2016-01-18 08:40:25.802 ThaliTest[2181:4612060] server: starting 1453102825800.2181.3XRr+A==
2016-01-18 08:40:25.802 ThaliTest[2181:4612060] multipeer session: start timer: 0x16647360
2016-01-18 08:40:25.802 ThaliTest[2181:4612060] THEMultipeerSession initialized peer 1453102825800.2181
2016-01-18 08:40:25.802 ThaliTest[2181:4612060] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,appEnteredForeground wasn't registered
,2016-01-18 08:40:55.803 ThaliTest[2181:4611927] multipeer session: restart
,2016-01-18 08:41:03.133 ThaliTest[2181:4611927] client: found peer: 1453102818198.1536.g1dlEA==
,2016-01-18 08:41:03.134 ThaliTest[2181:4612060] jxcore: connect 1453102818198.1536.g1dlEA==
2016-01-18 08:41:03.134 ThaliTest[2181:4612060] client session: connect
2016-01-18 08:41:03.135 ThaliTest[2181:4612060] client session: stateChange:0->1 1453102818198.1536.g1dlEA==
,2016-01-18 08:41:07.396 ThaliTest[2181:4613051] client session: connected
2016-01-18 08:41:07.396 ThaliTest[2181:4613051] client session: stateChange:1->2 1453102818198.1536.g1dlEA==
,2016-01-18 08:41:07.411 ThaliTest[2181:4612872] client session: fireConnectCallback: 1453102818198.1536.g1dlEA==
2016-01-18 08:41:07.411 ThaliTest[2181:4612872] jxcore: connect: success
,ok 79 Should be able to connect without error
,ok 80 Port should be within range
,2016-01-18 08:41:07.413 ThaliTest[2181:4612060] jxcore: connect 1453102818198.1536.g1dlEA==
2016-01-18 08:41:07.413 ThaliTest[2181:4612060] client: already connect(ing/ed) to 1453102818198.1536.g1dlEA==
2016-01-18 08:41:07.414 ThaliTest[2181:4612060] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
,2016-01-18 08:41:07.414 ThaliTest[2181:4612060] jxcore: disconnect
2016-01-18 08:41:07.415 ThaliTest[2181:4612060] client session: disconnectFromPeer: 1453102818198.1536.g1dlEA==
2016-01-18 08:41:07.415 ThaliTest[2181:4612060] client session: disconnect,
2016-01-18 08:41:07.415 ThaliTest[2181:4612060] client session: stateChange:2->0 1453102818198.1536.g1dlEA==
,2016-01-18 08:41:07.418 ThaliTest[2181:4612060] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-18 08:41:25.803 ThaliTest[2181:4611927] multipeer session: restart
,2016-01-18 08:41:35.235 ThaliTest[2181:4611927] multipeer session: reset timer
2016-01-18 08:41:35.235 ThaliTest[2181:4611927] multipeer session: stop timer
2016-01-18 08:41:35.235 ThaliTest[2181:4611927] multipeer session: start timer: 0x16647360
2016-,01-18 08:41:35.236 ThaliTest[2181:4611927] server session: connect
2016-01-18 08:41:35.236 ThaliTest[2181:4611927] server session: stateChange:0->1 1453102818198.1536
2016-01-18 08:41:35.239 ThaliTest[2181:4611927] server: accepting invitation 1453102818198.1536
,2016-01-18 08:41:38.305 ThaliTest[2181:4613143] server session: connected
2016-01-18 08:41:38.306 ThaliTest[2181:4613143] server session: stateChange:1->2 1453102818198.1536
,2016-01-18 08:41:38.318 ThaliTest[2181:4611927] server relay: socket disconnected
2016-01-18 08:41:38.318 ThaliTest[2181:4611927] server relay: 0x1662e6a0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-18 08:41:38.365 ThaliTest[2181:4613111] server session: not connected 1453102818198.1536
,2016-01-18 08:42:05.237 ThaliTest[2181:4611927] multipeer session: restart
,2016-01-18 08:42:05.249 ThaliTest[2181:4611927] client: found peer: 1453102818198.1536.g1dlEA==
,2016-01-18 08:42:35.237 ThaliTest[2181:4611927] multipeer session: restart
,2016-01-18 08:42:35.246 ThaliTest[2181:4611927] client: found peer: 1453102818198.1536.g1dlEA==
,2016-01-18 08:43:05.237 ThaliTest[2181:4611927] multipeer session: restart
,2016-01-18 08:43:35.237 ThaliTest[2181:4611927] multipeer session: restart
,2016-01-18 08:44:05.237 ThaliTest[2181:4611927] multipeer session: restart
,2016-01-18 08:44:35.237 ThaliTest[2181:4611927] multipeer session: restart
,2016-01-18 08:44:35.245 ThaliTest[2181:4611927] client: found peer: 1453102818198.1536.g1dlEA==
,2016-01-18 08:45:05.237 ThaliTest[2181:4611927] multipeer session: restart
,2016-01-18 08:45:35.237 ThaliTest[2181:4611927] multipeer session: restart
,2016-01-18 08:45:35.250 ThaliTest[2181:4611927] client: found peer: 1453102818198.1536.g1dlEA==
,2016-01-18 08:46:02.319 ThaliTest[2181:4611927] client: lost peer: 1453102818198.1536.g1dlEA==
2016-01-18 08:46:02.319 ThaliTest[2181:4611927] client session: onPeerLost: 1453102818198.1536.g1dlEA==
,2016-01-18 08:46:05.236 ThaliTest[2181:4611927] multipeer session: restart
,appEnteringBackground wasn't registered
,2016-01-18 08:46:10.891 ThaliTest[2181:4611927] client: found peer: 1453102818198.1536.g1dlEA==
,2016-01-18 08:46:35.237 ThaliTest[2181:4611927] multipeer session: restart
,2016-01-18 08:46:35.248 ThaliTest[2181:4611927] client: found peer: 1453102818198.1536.g1dlEA==
,2016-01-18 08:47:05.237 ThaliTest[2181:4611927] multipeer session: restart
,2016-01-18 08:47:05.249 ThaliTest[2181:4611927] client: found peer: 1453102818198.1536.g1dlEA==
,2016-01-18 08:47:35.237 ThaliTest[2181:4611927] multipeer session: restart
,2016-01-18 08:47:35.249 ThaliTest[2181:4611927] client: found peer: 1453102818198.1536.g1dlEA==
,2016-01-18 08:48:05.237 ThaliTest[2181:4611927] multipeer session: restart
,2016-01-18 08:48:35.237 ThaliTest[2181:4611927] multipeer session: restart
,2016-01-18 08:48:35.246 ThaliTest[2181:4611927] client: found peer: 1453102818198.1536.g1dlEA==
,2016-01-18 08:49:05.237 ThaliTest[2181:4611927] multipeer session: restart
,2016-01-18 08:49:05.249 ThaliTest[2181:4611927] client: found peer: 1453102818198.1536.g1dlEA==
,2016-01-18 08:49:35.194 ThaliTest[2181:4611927] multipeer session: restart
,2016-01-18 08:49:35.204 ThaliTest[2181:4611927] client: found peer: 1453102818198.1536.g1dlEA==
,2016-01-18 08:50:05.189 ThaliTest[2181:4611927] multipeer session: restart
,2016-01-18 08:50:35.189 ThaliTest[2181:4611927] multipeer session: restart
,2016-01-18 08:50:35.202 ThaliTest[2181:4611927] client: found peer: 1453102818198.1536.g1dlEA==
,2016-01-18 08:51:05.189 ThaliTest[2181:4611927] multipeer session: restart

```
