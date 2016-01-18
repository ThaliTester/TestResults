#### Test 5635717154d1b6f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5635717154d1b6f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D19D613B-A085-4C75-8462-6726A88CA2E0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D19D613B-A085-4C75-8462-6726A88CA2E0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5635717154d1b6f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5635717154d1b6f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0E616089-A7EB-408D-883B-5DF63450B780/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58051"
,(lldb)     command script import "/tmp/D19D613B-A085-4C75-8462-6726A88CA2E0/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-18 16:53:51.595 ThaliTest[2288:4915580] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/08A1DA0B-2C4E-4EC8-873C-16553E0C36DC/Library/Cookies/Cookies.binarycookies
,2016-01-18 16:53:51.822 ThaliTest[2288:4915580] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-18 16:53:51.823 ThaliTest[2288:4915580] Multi-tasking -> Device: YES, App: YES
,2016-01-18 16:53:51.829 ThaliTest[2288:4915580] Unlimited access to network resources
,2016-01-18 16:53:51.835 ThaliTest[2288:4915580] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-18 16:53:55.727 ThaliTest[2288:4915580] Resetting plugins due to page load.
,2016-01-18 16:53:57.093 ThaliTest[2288:4915580] Finished load of: file:///var/mobile/Containers/Bundle/Application/0E616089-A7EB-408D-883B-5DF63450B780/ThaliTest.app/www/index.html
,2016-01-18 16:53:57.234 ThaliTest[2288:4915580] JXcore Cordova plugin initializing
,2016-01-18 16:53:57.235 ThaliTest[2288:4915753] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E616089-A7EB-408D-883B-5DF63450B780/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E616089-A7EB-408D-883B-5DF63450B780/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E616089-A7EB-408D-883B-5DF63450B780/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E616089-A7EB-408D-883B-5DF63450B780/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E616089-A7EB-408D-883B-5DF63450B780/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E616089-A7EB-408D-883B-5DF63450B780/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E616089-A7EB-408D-883B-5DF63450B780/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
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
ok 33 should be equal
,# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,# teardown
,ok 34 should be equal
,ok 35 should be equal
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
ok 44 should be equal
,# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2016-01-18 16:59:22.260 ThaliTest[2288:4915753] jxcore: startBroadcasting
,2016-01-18 16:59:22.266 ThaliTest[2288:4915753] server: starting 1453132762260.2288.FSxg5w==
2016-01-18 16:59:22.266 ThaliTest[2288:4915753] multipeer session: start timer: 0x185b40f0
,2016-01-18 16:59:22.266 ThaliTest[2288:4915753] THEMultipeerSession initialized peer 1453132762260.2288
2016-01-18 16:59:22.267 ThaliTest[2288:4915753] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2016-01-18 16:59:22.268 ThaliTest[2288:4915753] jxcore: stopBroadcasting
2016-01-18 16:59:22.268 ThaliTest[2288:4915753] THEMultipeerSession stopping peer
,2016-01-18 16:59:22.268 ThaliTest[2288:4915753] multipeer session: stop timer
2016-01-18 16:59:22.268 ThaliTest[2288:4915753] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-18 16:59:22.269 ThaliTest[2288:4915753] jxcore: startBroadcasting
,2016-01-18 16:59:22.271 ThaliTest[2288:4915753] server: starting 1453132762269.2288.r7/16A==
2016-01-18 16:59:22.271 ThaliTest[2288:4915753] multipeer session: start timer: 0x167f4a60
2016-01-18 16:59:22.271 ThaliTest[2288:4915753] THEMultipeerSession initialized peer 1453132762269.2288
2016-01-18 16:59:22.272 ThaliTest[2288:4915753] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-18 16:59:22.273 ThaliTest[2288:4915753] jxcore: stopBroadcasting
2016-01-18 16:59:22.273 ThaliTest[2288:4915753] THEMultipeerSession stopping peer
2016-01-18 16:59:22.273 ThaliTest[2288:4915753] multipeer session: stop timer
,2016-01-18 16:59:22.276 ThaliTest[2288:4915753] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
2016-01-18 16:59:22.278 ThaliTest[2288:4915753] jxcore: startBroadcasting
,2016-01-18 16:59:22.279 ThaliTest[2288:4915753] server: starting 1453132762277.2288.0XKhHA==
2016-01-18 16:59:22.279 ThaliTest[2288:4915753] multipeer session: start timer: 0x185b0380
2016-01-18 16:59:22.280 ThaliTest[2288:4915753] THEMultipeerSession in,itialized peer 1453132762277.2288
2016-01-18 16:59:22.280 ThaliTest[2288:4915753] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2016-01-18 16:59:22.281 ThaliTest[2288:4915753] jxcore: stopBroadcasting
2016-01-18 16:59:22.281 ThaliTest[2288:4915753] THEMultipeerSession stopping peer
2016-01-18 16:59:22.281 ThaliTest[2288:4915753] multipeer session: stop timer
2016-01-18 16:59:22.281 ThaliTest[2288:4915753] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error
2016-01-18 16:59:22.281 ThaliTest[2288:4915753] jxcore: startBroadcasting
,2016-01-18 16:59:22.285 ThaliTest[2288:4915753] server: starting 1453132762281.2288.ohIaTg==
,2016-01-18 16:59:22.286 ThaliTest[2288:4915753] multipeer session: start timer: 0x167f2490
,2016-01-18 16:59:22.287 ThaliTest[2288:4915753] THEMultipeerSession initialized peer 1453132762281.2288
,2016-01-18 16:59:22.287 ThaliTest[2288:4915753] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2016-01-18 16:59:22.288 ThaliTest[2288:4915753] jxcore: stopBroadcasting
,2016-01-18 16:59:22.289 ThaliTest[2288:4915753] THEMultipeerSession stopping peer
2016-01-18 16:59:22.289 ThaliTest[2288:4915753] multipeer session: stop timer
,2016-01-18 16:59:22.290 ThaliTest[2288:4915753] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2016-01-18 16:59:22.291 ThaliTest[2288:4915753] jxcore: startBroadcasting
,2016-01-18 16:59:22.293 ThaliTest[2288:4915753] server: starting 1453132762291.2288.vwAMuw==
,2016-01-18 16:59:22.293 ThaliTest[2288:4915753] multipeer session: start timer: 0x1844a960
,2016-01-18 16:59:22.295 ThaliTest[2288:4915753] THEMultipeerSession initialized peer 1453132762291.2288
,2016-01-18 16:59:22.295 ThaliTest[2288:4915753] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2016-01-18 16:59:22.296 ThaliTest[2288:4915753] jxcore: stopBroadcasting
,2016-01-18 16:59:22.296 ThaliTest[2288:4915753] THEMultipeerSession stopping peer
,2016-01-18 16:59:22.296 ThaliTest[2288:4915753] multipeer session: stop timer
,2016-01-18 16:59:22.297 ThaliTest[2288:4915753] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-18 16:59:22.299 ThaliTest[2288:4915753] jxcore: startBroadcasting
,2016-01-18 16:59:22.300 ThaliTest[2288:4915753] server: starting 1453132762298.2288.KQuwUA==
,2016-01-18 16:59:22.300 ThaliTest[2288:4915753] multipeer session: start timer: 0x185b2df0
,2016-01-18 16:59:22.302 ThaliTest[2288:4915753] THEMultipeerSession initialized peer 1453132762298.2288
,2016-01-18 16:59:22.302 ThaliTest[2288:4915753] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-18 16:59:22.303 ThaliTest[2288:4915753] jxcore: stopBroadcasting
,2016-01-18 16:59:22.304 ThaliTest[2288:4915753] THEMultipeerSession stopping peer
,2016-01-18 16:59:22.304 ThaliTest[2288:4915753] multipeer session: stop timer
,2016-01-18 16:59:22.304 ThaliTest[2288:4915753] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-18 16:59:22.306 ThaliTest[2288:4915753] jxcore: startBroadcasting
,2016-01-18 16:59:22.308 ThaliTest[2288:4915753] server: starting 1453132762306.2288.gBIpZA==
,2016-01-18 16:59:22.308 ThaliTest[2288:4915753] multipeer session: start timer: 0x18448570
,2016-01-18 16:59:22.310 ThaliTest[2288:4915753] THEMultipeerSession initialized peer 1453132762306.2288
,2016-01-18 16:59:22.311 ThaliTest[2288:4915753] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-18 16:59:22.312 ThaliTest[2288:4915753] jxcore: stopBroadcasting
,2016-01-18 16:59:22.312 ThaliTest[2288:4915753] THEMultipeerSession stopping peer
,2016-01-18 16:59:22.312 ThaliTest[2288:4915753] multipeer session: stop timer
,2016-01-18 16:59:22.313 ThaliTest[2288:4915753] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-18 16:59:22.314 ThaliTest[2288:4915753] jxcore: startBroadcasting
,2016-01-18 16:59:22.315 ThaliTest[2288:4915753] server: starting 1453132762314.2288.vady3A==
,2016-01-18 16:59:22.316 ThaliTest[2288:4915753] multipeer session: start timer: 0x185af4b0
,2016-01-18 16:59:22.317 ThaliTest[2288:4915753] THEMultipeerSession initialized peer 1453132762314.2288
,2016-01-18 16:59:22.318 ThaliTest[2288:4915753] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-18 16:59:22.319 ThaliTest[2288:4915753] jxcore: stopBroadcasting
,2016-01-18 16:59:22.319 ThaliTest[2288:4915753] THEMultipeerSession stopping peer
,2016-01-18 16:59:22.320 ThaliTest[2288:4915753] multipeer session: stop timer
,2016-01-18 16:59:22.320 ThaliTest[2288:4915753] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-18 16:59:22.322 ThaliTest[2288:4915753] jxcore: startBroadcasting
,2016-01-18 16:59:22.323 ThaliTest[2288:4915753] server: starting 1453132762322.2288.FkmiYA==
,2016-01-18 16:59:22.324 ThaliTest[2288:4915753] multipeer session: start timer: 0x167efec0
,2016-01-18 16:59:22.326 ThaliTest[2288:4915753] THEMultipeerSession initialized peer 1453132762322.2288
,2016-01-18 16:59:22.326 ThaliTest[2288:4915753] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-18 16:59:22.327 ThaliTest[2288:4915753] jxcore: stopBroadcasting
,2016-01-18 16:59:22.327 ThaliTest[2288:4915753] THEMultipeerSession stopping peer
,2016-01-18 16:59:22.327 ThaliTest[2288:4915753] multipeer session: stop timer
,2016-01-18 16:59:22.328 ThaliTest[2288:4915753] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-18 16:59:22.330 ThaliTest[2288:4915753] jxcore: startBroadcasting
,2016-01-18 16:59:22.331 ThaliTest[2288:4915753] server: starting 1453132762329.2288.RccHEw==
,2016-01-18 16:59:22.331 ThaliTest[2288:4915753] multipeer session: start timer: 0x167dc150
,2016-01-18 16:59:22.332 ThaliTest[2288:4915753] THEMultipeerSession initialized peer 1453132762329.2288
,2016-01-18 16:59:22.334 ThaliTest[2288:4915753] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-18 16:59:22.335 ThaliTest[2288:4915753] jxcore: stopBroadcasting
,2016-01-18 16:59:22.335 ThaliTest[2288:4915753] THEMultipeerSession stopping peer
,2016-01-18 16:59:22.335 ThaliTest[2288:4915753] multipeer session: stop timer
,2016-01-18 16:59:22.336 ThaliTest[2288:4915753] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-18 16:59:23.092 ThaliTest[2288:4915753] jxcore: startBroadcasting
,2016-01-18 16:59:23.093 ThaliTest[2288:4915753] server: starting 1453132763092.2288.7LqgyA==
2016-01-18 16:59:23.093 ThaliTest[2288:4915753] multipeer session: start timer: 0x184f9340
2016-01-18 16:59:23.093 ThaliTest[2288:4915753] THEMultipeerSession initialized peer 1453132763092.2288
2016-01-18 16:59:23.094 ThaliTest[2288:4915753] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-18 16:59:23.094 ThaliTest[2288:4915753] jxcore: startBroadcasting
2016-01-18 16:59:23.094 ThaliTest[2288:4915753] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
2016-01-18 16:59:23.095 ThaliTest[2288:4915753] jxcore: stopBroadcasting
2016-01-18 16:59:23.096 ThaliTest[2288:4915753] THEMultipeerSession stopping peer
2016-01-18 16:59:23.096 ThaliTest[2288:4915753] multipeer session: stop timer
2016-01-18 16:59:23.096 ThaliTest[2288:4915753] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-18 16:59:23.210 ThaliTest[2288:4915753] jxcore: startBroadcasting
,2016-01-18 16:59:23.211 ThaliTest[2288:4915753] server: starting 1453132763210.2288.GPKFAA==
2016-01-18 16:59:23.211 ThaliTest[2288:4915753] multipeer session: start timer: 0x184f6c30
2016-01-18 16:59:23.211 ThaliTest[2288:4915753] THEMultipeerSession initialized peer 1453132763210.2288
,2016-01-18 16:59:23.212 ThaliTest[2288:4915753] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
,2016-01-18 16:59:23.214 ThaliTest[2288:4915753] jxcore: connect foobar
2016-01-18 16:59:23.214 ThaliTest[2288:4915753] client: unknown peer foobar
2016-01-18 16:59:23.214 ThaliTest[2288:4915753] jxcore: connect: fail: Unknown peer
ok 69 Should not conne,ct to a bad peer
2016-01-18 16:59:23.215 ThaliTest[2288:4915753] jxcore: stopBroadcasting
2016-01-18 16:59:23.215 ThaliTest[2288:4915753] THEMultipeerSession stopping peer
2016-01-18 16:59:23.215 ThaliTest[2288:4915753] multipeer session: stop timer
20,16-01-18 16:59:23.215 ThaliTest[2288:4915753] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-18 16:59:23.271 ThaliTest[2288:4915753] jxcore: startBroadcasting
,2016-01-18 16:59:23.272 ThaliTest[2288:4915753] server: starting 1453132763271.2288.3obljQ==
2016-01-18 16:59:23.272 ThaliTest[2288:4915753] multipeer session: start timer: 0x167dccc0
2016-01-18 16:59:23.273 ThaliTest[2288:4915753] THEMultipeerSession in,itialized peer 1453132763271.2288
2016-01-18 16:59:23.273 ThaliTest[2288:4915753] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-18 16:59:23.274 ThaliTest[2288:4915753] jxcore: disconnect
2016-01-18 16:59:23.274 ThaliTest[2288:4915753] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 
,2016-01-18 16:59:23.274 ThaliTest[2288:4915753] jxcore: stopBroadcasting
2016-01-18 16:59:23.275 ThaliTest[2288:4915753] THEMultipeerSession stopping peer
2016-01-18 16:59:23.275 ThaliTest[2288:4915753] multipeer session: stop timer
2016-01-18 16:59:23.275 ThaliTest[2288:4915753] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-18 16:59:23.621 ThaliTest[2288:4915753] jxcore: startBroadcasting
,2016-01-18 16:59:23.622 ThaliTest[2288:4915753] server: starting 1453132763621.2288.QMQnBw==
2016-01-18 16:59:23.622 ThaliTest[2288:4915753] multipeer session: start timer: 0x184f5600
2016-01-18 16:59:23.622 ThaliTest[2288:4915753] THEMultipeerSession initialized peer 1453132763621.2288
2016-01-18 16:59:23.622 ThaliTest[2288:4915753] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-18 16:59:24.894 ThaliTest[2288:4915580] client: found peer: 1453132761605.2234.zN5HjQ==
,2016-01-18 16:59:24.895 ThaliTest[2288:4915753] jxcore: connect 1453132761605.2234.zN5HjQ==
2016-01-18 16:59:24.895 ThaliTest[2288:4915753] client session: connect
2016-01-18 16:59:24.895 ThaliTest[2288:4915753] client session: stateChange:0->1 1453132761605.2234.zN5HjQ==
,2016-01-18 16:59:25.000 ThaliTest[2288:4915580] multipeer session: reset timer
2016-01-18 16:59:25.000 ThaliTest[2288:4915580] multipeer session: stop timer
2016-01-18 16:59:25.000 ThaliTest[2288:4915580] multipeer session: start timer: 0x184f5600
2016-01-18 16:59:25.001 ThaliTest[2288:4915580] server session: connect
2016-01-18 16:59:25.001 ThaliTest[2288:4915580] server session: stateChange:0->1 1453132761605.2234
,2016-01-18 16:59:25.003 ThaliTest[2288:4915580] server: accepting invitation 1453132761605.2234
,2016-01-18 16:59:29.136 ThaliTest[2288:4916358] client session: connected
2016-01-18 16:59:29.136 ThaliTest[2288:4916358] client session: stateChange:1->2 1453132761605.2234.zN5HjQ==
2016-01-18 16:59:29.138 ThaliTest[2288:4916358] client session: fireConnectCallback: 1453132761605.2234.zN5HjQ==
2016-01-18 16:59:29.138 ThaliTest[2288:4916358] jxcore: connect: success
,ok 75 Should be able to connect without error
ok 76 Port should be within range
2016-01-18 16:59:29.139 ThaliTest[2288:4915753] jxcore: disconnect
2016-01-18 16:59:29.139 ThaliTest[2288:4915753] client session: disconnectFromPeer: 1453132761605.2234.zN5HjQ==
2016-01-18 16:59:29.139 ThaliTest[2288:4915753] client session: disconnect
2016-01-18 16:59:29.139 ThaliTest[2288:4915753] client session: stateChange:2->0 1453132761605.2234.zN5HjQ==
,2016-01-18 16:59:29.200 ThaliTest[2288:4915753] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-18 16:59:29.261 ThaliTest[2288:4916363] server session: connected
,2016-01-18 16:59:29.261 ThaliTest[2288:4916363] server session: stateChange:1->2 1453132761605.2234
,2016-01-18 16:59:29.264 ThaliTest[2288:4915580] server relay: socket disconnected
2016-01-18 16:59:29.264 ThaliTest[2288:4915580] server relay: 0x1858fa80 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-18 16:59:29.295 ThaliTest[2288:4916364] server session: not connected 1453132761605.2234
,calling stopBroadcasting
2016-01-18 16:59:29.457 ThaliTest[2288:4915753] jxcore: stopBroadcasting
2016-01-18 16:59:29.457 ThaliTest[2288:4915753] THEMultipeerSession stopping peer
2016-01-18 16:59:29.457 ThaliTest[2288:4915753] multipeer session: stop timer
2016-01-18 16:59:29.457 ThaliTest[2288:4915753] server session: disconnect
2016-01-18 16:59:29.457 ThaliTest[2288:4915753] server session: stateChange:2->0 1453132761605.2234
,2016-01-18 16:59:29.459 ThaliTest[2288:4915753] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-18 16:59:29.979 ThaliTest[2288:4915753] jxcore: startBroadcasting
,2016-01-18 16:59:29.980 ThaliTest[2288:4915753] server: starting 1453132769979.2288.pRS7Rg==
2016-01-18 16:59:29.980 ThaliTest[2288:4915753] multipeer session: start timer: 0x184f2020
2016-01-18 16:59:29.980 ThaliTest[2288:4915753] THEMultipeerSession initialized peer 1453132769979.2288
2016-01-18 16:59:29.981 ThaliTest[2288:4915753] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-18 16:59:31.221 ThaliTest[2288:4915580] client: found peer: 1453132767965.2234.EvrA9A==
2016-01-18 16:59:31.221 ThaliTest[2288:4915753] jxcore: connect 1453132767965.2234.EvrA9A==
2016-01-18 16:59:31.221 ThaliTest[2288:4915753] client session: connect
2016-01-18 16:59:31.221 ThaliTest[2288:4915753] client session: stateChange:0->1 1453132767965.2234.EvrA9A==
,2016-01-18 16:59:31.622 ThaliTest[2288:4915580] multipeer session: reset timer
2016-01-18 16:59:31.622 ThaliTest[2288:4915580] multipeer session: stop timer
2016-01-18 16:59:31.623 ThaliTest[2288:4915580] multipeer session: start timer: 0x184f2020
2016-01-18 16:59:31.623 ThaliTest[2288:4915580] server session: connect
2016-01-18 16:59:31.623 ThaliTest[2288:4915580] server session: stateChange:0->1 1453132767965.2234
,2016-01-18 16:59:31.626 ThaliTest[2288:4915580] server: accepting invitation 1453132767965.2234
,2016-01-18 16:59:35.298 ThaliTest[2288:4916360] client session: connected
2016-01-18 16:59:35.298 ThaliTest[2288:4916360] client session: stateChange:1->2 1453132767965.2234.EvrA9A==
,2016-01-18 16:59:35.349 ThaliTest[2288:4916360] client session: fireConnectCallback: 1453132767965.2234.EvrA9A==
2016-01-18 16:59:35.349 ThaliTest[2288:4916360] jxcore: connect: success
,ok 79 Should be able to connect without error
ok 80 Port should be within range
,2016-01-18 16:59:35.350 ThaliTest[2288:4915753] jxcore: connect 1453132767965.2234.EvrA9A==
2016-01-18 16:59:35.350 ThaliTest[2288:4915753] client: already connect(ing/ed) to 1453132767965.2234.EvrA9A==
2016-01-18 16:59:35.351 ThaliTest[2288:4915753] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
,2016-01-18 16:59:35.351 ThaliTest[2288:4915753] jxcore: disconnect
2016-01-18 16:59:35.351 ThaliTest[2288:4915753] client session: disconnectFromPeer: 1453132767965.2234.EvrA9A==
2016-01-18 16:59:35.351 ThaliTest[2288:4915753] client session: disconnect,
,2016-01-18 16:59:35.351 ThaliTest[2288:4915753] client session: stateChange:2->0 1453132767965.2234.EvrA9A==
,2016-01-18 16:59:35.356 ThaliTest[2288:4915753] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-18 16:59:35.626 ThaliTest[2288:4916360] server session: connected
2016-01-18 16:59:35.626 ThaliTest[2288:4916360] server session: stateChange:1->2 1453132767965.2234
,2016-01-18 16:59:35.627 ThaliTest[2288:4915580] server relay: socket disconnected
2016-01-18 16:59:35.627 ThaliTest[2288:4915580] server relay: 0x18586df0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-18 16:59:35.692 ThaliTest[2288:4916358] server session: not connected 1453132767965.2234
,calling stopBroadcasting
,2016-01-18 16:59:36.832 ThaliTest[2288:4915753] jxcore: stopBroadcasting
2016-01-18 16:59:36.832 ThaliTest[2288:4915753] THEMultipeerSession stopping peer
2016-01-18 16:59:36.832 ThaliTest[2288:4915753] multipeer session: stop timer
2016-01-18 16:59:36.832 ThaliTest[2288:4915753] server session: disconnect
2016-01-18 16:59:36.833 ThaliTest[2288:4915753] server session: stateChange:2->0 1453132767965.2234
,2016-01-18 16:59:36.834 ThaliTest[2288:4915753] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-18 16:59:39.006 ThaliTest[2288:4915753] jxcore: startBroadcasting
,2016-01-18 16:59:39.007 ThaliTest[2288:4915753] server: starting 1453132779006.2288.yAkOuA==
2016-01-18 16:59:39.008 ThaliTest[2288:4915753] multipeer session: start timer: 0x167c74e0
2016-01-18 16:59:39.008 ThaliTest[2288:4915753] THEMultipeerSession initialized peer 1453132779006.2288
2016-01-18 16:59:39.008 ThaliTest[2288:4915753] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-18 16:59:39.744 ThaliTest[2288:4915580] client: found peer: 1453132776967.2234.KfmYXw==
,2016-01-18 16:59:39.746 ThaliTest[2288:4915753] jxcore: connect 1453132776967.2234.KfmYXw==
2016-01-18 16:59:39.746 ThaliTest[2288:4915753] client session: connect
2016-01-18 16:59:39.746 ThaliTest[2288:4915753] client session: stateChange:0->1 1453132776967.2234.KfmYXw==
,2016-01-18 16:59:42.229 ThaliTest[2288:4915580] multipeer session: reset timer
2016-01-18 16:59:42.229 ThaliTest[2288:4915580] multipeer session: stop timer
2016-01-18 16:59:42.229 ThaliTest[2288:4915580] multipeer session: start timer: 0x167c74e0
2016-01-18 16:59:42.229 ThaliTest[2288:4915580] server session: connect
2016-01-18 16:59:42.229 ThaliTest[2288:4915580] server session: stateChange:0->1 1453132776967.2234
2016-01-18 16:59:42.231 ThaliTest[2288:4915580] server: accepting invitation 1453132776967.2234
,2016-01-18 16:59:43.810 ThaliTest[2288:4916360] client session: connected
2016-01-18 16:59:43.811 ThaliTest[2288:4916360] client session: stateChange:1->2 1453132776967.2234.KfmYXw==
,2016-01-18 16:59:43.812 ThaliTest[2288:4916360] client session: fireConnectCallback: 1453132776967.2234.KfmYXw==
2016-01-18 16:59:43.812 ThaliTest[2288:4916360] jxcore: connect: success
ok 84 Should be able to connect without error
,ok 85 Port should be within range
,2016-01-18 16:59:43.813 ThaliTest[2288:4915753] jxcore: disconnect
2016-01-18 16:59:43.814 ThaliTest[2288:4915753] client session: disconnectFromPeer: 1453132776967.2234.KfmYXw==
2016-01-18 16:59:43.814 ThaliTest[2288:4915753] client session: disconnect
2016-01-18 16:59:43.814 ThaliTest[2288:4915753] client session: stateChange:2->0 1453132776967.2234.KfmYXw==
,2016-01-18 16:59:43.875 ThaliTest[2288:4915753] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
,2016-01-18 16:59:43.876 ThaliTest[2288:4915753] jxcore: disconnect
2016-01-18 16:59:43.876 ThaliTest[2288:4915753] jxcore: disconnect: fail
ok 87 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,# setup
,2016-01-18 16:59:45.570 ThaliTest[2288:4916364] server session: connected
2016-01-18 16:59:45.571 ThaliTest[2288:4916364] server session: stateChange:1->2 1453132776967.2234
,2016-01-18 16:59:45.572 ThaliTest[2288:4915580] server relay: socket disconnected
2016-01-18 16:59:45.572 ThaliTest[2288:4915580] server relay: 0x1858a860 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-18 16:59:45.637 ThaliTest[2288:4916360] server session: not connected 1453132776967.2234
,calling stopBroadcasting
,2016-01-18 16:59:45.783 ThaliTest[2288:4915753] jxcore: stopBroadcasting
,2016-01-18 16:59:45.783 ThaliTest[2288:4915753] THEMultipeerSession stopping peer
,2016-01-18 16:59:45.783 ThaliTest[2288:4915753] multipeer session: stop timer
,2016-01-18 16:59:45.784 ThaliTest[2288:4915753] server session: disconnect
,2016-01-18 16:59:45.785 ThaliTest[2288:4915753] server session: stateChange:2->0 1453132776967.2234
,2016-01-18 16:59:45.937 ThaliTest[2288:4915753] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can connect and send data
,# teardown
,echo server started on port: 54100
,2016-01-18 16:59:47.216 ThaliTest[2288:4915753] jxcore: startBroadcasting
,2016-01-18 16:59:47.218 ThaliTest[2288:4915753] server: starting 1453132787216.2288.Wqfi3Q==
2016-01-18 16:59:47.218 ThaliTest[2288:4915753] multipeer session: start timer: 0x18586790
2016-01-18 16:59:47.218 ThaliTest[2288:4915753] THEMultipeerSession initialized peer 1453132787216.2288
2016-01-18 16:59:47.218 ThaliTest[2288:4915753] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
,2016-01-18 16:59:48.990 ThaliTest[2288:4915580] multipeer session: reset timer
2016-01-18 16:59:48.991 ThaliTest[2288:4915580] multipeer session: stop timer
2016-01-18 16:59:48.991 ThaliTest[2288:4915580] multipeer session: start timer: 0x18586790
2016-01-18 16:59:48.991 ThaliTest[2288:4915580] server session: connect
2016-01-18 16:59:48.991 ThaliTest[2288:4915580] server session: stateChange:0->1 1453132786004.2234
,2016-01-18 16:59:48.993 ThaliTest[2288:4915580] server: accepting invitation 1453132786004.2234
,2016-01-18 16:59:49.127 ThaliTest[2288:4915580] client: found peer: 1453132786004.2234.Z6nxng==
,2016-01-18 16:59:49.127 ThaliTest[2288:4915753] jxcore: connect 1453132786004.2234.Z6nxng==
2016-01-18 16:59:49.128 ThaliTest[2288:4915753] client session: connect
2016-01-18 16:59:49.128 ThaliTest[2288:4915753] client session: stateChange:0->1 1453132786004.2234.Z6nxng==
,2016-01-18 16:59:52.922 ThaliTest[2288:4916360] client session: connected
2016-01-18 16:59:52.923 ThaliTest[2288:4916360] client session: stateChange:1->2 1453132786004.2234.Z6nxng==
,2016-01-18 16:59:52.978 ThaliTest[2288:4916360] client session: fireConnectCallback: 1453132786004.2234.Z6nxng==
2016-01-18 16:59:52.978 ThaliTest[2288:4916360] jxcore: connect: success
,ok 89 Should be able to connect without error
ok 90 Port should be within range
,2016-01-18 16:59:52.980 ThaliTest[2288:4915580] client: relay established
2016-01-18 16:59:52.981 ThaliTest[2288:4915580] client: new accepted socket: 0x18579210
,2016-01-18 16:59:52.987 ThaliTest[2288:4916362] server session: connected
2016-01-18 16:59:52.987 ThaliTest[2288:4916362] server session: stateChange:1->2 1453132786004.2234
,2016-01-18 16:59:53.042 ThaliTest[2288:4915580] server relay: connected (to port: 54100)
,data in 17520
,data in 43800
,data in 51465
,data in 69867
,data in 76650
,data in 77745
,data in 131072
,ok 91 the test messages should be equal
,2016-01-18 16:59:54.173 ThaliTest[2288:4915753] jxcore: disconnect
2016-01-18 16:59:54.173 ThaliTest[2288:4915753] client session: disconnectFromPeer: 1453132786004.2234.Z6nxng==
2016-01-18 16:59:54.173 ThaliTest[2288:4915753] client session: disconnect,
2016-01-18 16:59:54.173 ThaliTest[2288:4915753] client session: stateChange:2->0 1453132786004.2234.Z6nxng==
,2016-01-18 16:59:54.176 ThaliTest[2288:4915753] jxcore: disconnect: success
ok 92 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
# setup
,2016-01-18 16:59:54.548 ThaliTest[2288:4916362] server session: not connected 1453132786004.2234
,calling stopBroadcasting
,2016-01-18 16:59:56.665 ThaliTest[2288:4915753] jxcore: stopBroadcasting
2016-01-18 16:59:56.665 ThaliTest[2288:4915753] THEMultipeerSession stopping peer
2016-01-18 16:59:56.665 ThaliTest[2288:4915753] multipeer session: stop timer
2016-01-18 16:59:56.,665 ThaliTest[2288:4915753] server session: disconnect
2016-01-18 16:59:56.665 ThaliTest[2288:4915753] server session: stateChange:2->0 1453132786004.2234
2016-01-18 16:59:56.667 ThaliTest[2288:4915753] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,echo server started on port: 54106
,2016-01-18 16:59:59.222 ThaliTest[2288:4915753] jxcore: startBroadcasting
,2016-01-18 16:59:59.224 ThaliTest[2288:4915753] server: starting 1453132799222.2288.nlY6Iw==
2016-01-18 16:59:59.224 ThaliTest[2288:4915753] multipeer session: start timer: 0x167b5c00
2016-01-18 16:59:59.224 ThaliTest[2288:4915753] THEMultipeerSession initialized peer 1453132799222.2288
2016-01-18 16:59:59.224 ThaliTest[2288:4915753] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error
,2016-01-18 16:59:59.228 ThaliTest[2288:4915580] client: found peer: 1453132786004.2234.Z6nxng==
,[{"peerIdentifier":"1453132786004.2234.Z6nxng==","peerName":"(null)","peerAvailable":true}]
,2016-01-18 16:59:59.229 ThaliTest[2288:4915753] jxcore: connect 1453132786004.2234.Z6nxng==
2016-01-18 16:59:59.229 ThaliTest[2288:4915753] client session: connect
2016-01-18 16:59:59.229 ThaliTest[2288:4915753] client session: stateChange:0->1 1453132786004.2234.Z6nxng==
,2016-01-18 17:00:00.620 ThaliTest[2288:4915580] client: lost peer: 1453132786004.2234.Z6nxng==
2016-01-18 17:00:00.620 ThaliTest[2288:4915580] client session: onPeerLost: 1453132786004.2234.Z6nxng==
2016-01-18 17:00:00.620 ThaliTest[2288:4915580] client ,session: onLinkFailure: 1453132786004.2234.Z6nxng==
2016-01-18 17:00:00.620 ThaliTest[2288:4915580] client session: disconnect
2016-01-18 17:00:00.621 ThaliTest[2288:4915580] client session: stateChange:1->0 1453132786004.2234.Z6nxng==
2016-01-18 17:00:00.621 ThaliTest[2288:4915580] client session: fireConnectCallback: 1453132786004.2234.Z6nxng==
2016-01-18 17:00:00.621 ThaliTest[2288:4915580] jxcore: connect: fail: Peer disconnected
2016-01-18 17:00:00.621 ThaliTest[2288:4915580] client: found peer: 1453132797207.2234.jwEahg==
,[{"peerIdentifier":"1453132786004.2234.Z6nxng==","peerName":"(null)","peerAvailable":false}]
[{"peerIdentifier":"1453132797207.2234.jwEahg==","peerName":"(null)","peerAvailable":true}]
2016-01-18 17:00:00.622 ThaliTest[2288:4915753] jxcore: connect 14531,32797207.2234.jwEahg==
2016-01-18 17:00:00.622 ThaliTest[2288:4915753] client session: connect
2016-01-18 17:00:00.622 ThaliTest[2288:4915753] client session: stateChange:0->1 1453132797207.2234.jwEahg==
,2016-01-18 17:00:00.838 ThaliTest[2288:4915580] multipeer session: reset timer
2016-01-18 17:00:00.838 ThaliTest[2288:4915580] multipeer session: stop timer
2016-01-18 17:00:00.838 ThaliTest[2288:4915580] multipeer session: start timer: 0x167b5c00
2016-01-18 17:00:00.838 ThaliTest[2288:4915580] server session: connect
2016-01-18 17:00:00.838 ThaliTest[2288:4915580] server session: stateChange:0->1 1453132797207.2234
2016-01-18 17:00:00.841 ThaliTest[2288:4915580] server: accepting invitation 1453132797207.2234
,2016-01-18 17:00:01.627 ThaliTest[2288:4915753] jxcore: connect 1453132786004.2234.Z6nxng==
2016-01-18 17:00:01.627 ThaliTest[2288:4915753] client: connect: unreachable 1453132786004.2234.Z6nxng==
2016-01-18 17:00:01.627 ThaliTest[2288:4915753] jxcore: connect: fail: Peer unreachable
,2016-01-18 17:00:04.834 ThaliTest[2288:4916362] client session: connected
2016-01-18 17:00:04.834 ThaliTest[2288:4916362] client session: stateChange:1->2 1453132797207.2234.jwEahg==
,2016-01-18 17:00:04.837 ThaliTest[2288:4916360] server session: connected
2016-01-18 17:00:04.837 ThaliTest[2288:4916360] server session: stateChange:1->2 1453132797207.2234
,2016-01-18 17:00:04.841 ThaliTest[2288:4916362] client session: fireConnectCallback: 1453132797207.2234.jwEahg==
2016-01-18 17:00:04.841 ThaliTest[2288:4916362] jxcore: connect: success
ok 94 Should be able to connect without error
,ok 95 Port should be within range
,ok 96 First connect should succeed
,2016-01-18 17:00:04.852 ThaliTest[2288:4915580] client: relay established
2016-01-18 17:00:04.852 ThaliTest[2288:4915580] client: new accepted socket: 0x1856dc70
2016-01-18 17:00:04.852 ThaliTest[2288:4915580] server relay: connected (to port: 54106)
,2016-01-18 17:00:04.968 ThaliTest[2288:4916372] server session: not connected 1453132797207.2234
,ok 97 the test messages should be equal
ok 98 First send should succeed
,2016-01-18 17:00:04.978 ThaliTest[2288:4915580] multipeer session: reset timer
2016-01-18 17:00:04.978 ThaliTest[2288:4915580] multipeer session: stop timer
2016-01-18 17:00:04.978 ThaliTest[2288:4915580] multipeer session: start timer: 0x167b5c00
2016-01-18 17:00:04.978 ThaliTest[2288:4915580] server: disconnecting to refresh session (1453132797207.2234)
2016-01-18 17:00:04.978 ThaliTest[2288:4915580] server session: disconnect
2016-01-18 17:00:04.978 ThaliTest[2288:4915580] server session: stateChange:2->0 1453132797207.2234
,2016-01-18 17:00:04.980 ThaliTest[2288:4915580] server session: connect
2016-01-18 17:00:04.980 ThaliTest[2288:4915580] server session: stateChange:0->1 1453132797207.2234
,2016-01-18 17:00:04.983 ThaliTest[2288:4915580] server: accepting invitation 1453132797207.2234
,2016-01-18 17:00:04.987 ThaliTest[2288:4915580] client: socket closed
2016-01-18 17:00:04.987 ThaliTest[2288:4915580] client relay: socket disconnected
2016-01-18 17:00:04.987 ThaliTest[2288:4915580] client relay: 0x1856dc70 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-18 17:00:04.987 ThaliTest[2288:4915580] client session: socket closed: 1453132797207.2234.jwEahg==
2016-01-18 ,17:00:04.987 ThaliTest[2288:4915580] client session: onLinkFailure: 1453132797207.2234.jwEahg==
2016-01-18 17:00:04.987 ThaliTest[2288:4915580] client session: disconnect
2016-01-18 17:00:04.987 ThaliTest[2288:4915580] client session: stateChange:2->0 14,53132797207.2234.jwEahg==
,2016-01-18 17:00:04.991 ThaliTest[2288:4915580] client session: fireConnectionErrorEvent: 1453132797207.2234.jwEahg==
2016-01-18 17:00:04.992 ThaliTest[2288:4915753] jxcore: connect 1453132797207.2234.jwEahg==
2016-01-18 17:00:04.992 ThaliTest[2288:4915753] client session: connect
2016-01-18 17:00:04.992 ThaliTest[2288:4915753] client session: stateChange:0->1 1453132797207.2234.jwEahg==
,2016-01-18 17:00:08.667 ThaliTest[2288:4916362] server session: connected
2016-01-18 17:00:08.667 ThaliTest[2288:4916362] server session: stateChange:1->2 1453132797207.2234
,2016-01-18 17:00:08.837 ThaliTest[2288:4915580] server relay: connected (to port: 54106)
,2016-01-18 17:00:09.162 ThaliTest[2288:4916372] client session: connected
2016-01-18 17:00:09.162 ThaliTest[2288:4916372] client session: stateChange:1->2 1453132797207.2234.jwEahg==
,2016-01-18 17:00:09.169 ThaliTest[2288:4916364] client session: fireConnectCallback: 1453132797207.2234.jwEahg==
2016-01-18 17:00:09.170 ThaliTest[2288:4916364] jxcore: connect: success
,ok 99 Should be able to connect without error
,ok 100 Port should be within range
,ok 101 Second connect should succeed
,2016-01-18 17:00:09.179 ThaliTest[2288:4915580] client: relay established
2016-01-18 17:00:09.179 ThaliTest[2288:4915580] client: new accepted socket: 0x18561b20
,2016-01-18 17:00:09.225 ThaliTest[2288:4916360] server session: not connected 1453132797207.2234
,ok 102 the test messages should be equal
,ok 103 Second send should succeed
,# setup
,2016-01-18 17:00:09.256 ThaliTest[2288:4915580] client: socket closed
2016-01-18 17:00:09.256 ThaliTest[2288:4915580] client relay: socket disconnected
2016-01-18 17:00:09.256 ThaliTest[2288:4915580] client relay: 0x18561b20 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-18 17:00:09.257 ThaliTest[2288:4915580] client session: socket closed: 1453132797207.2234.jwEahg==
,2016-01-18 17:00:09.257 ThaliTest[2288:4915580] client session: onLinkFailure: 1453132797207.2234.jwEahg==
2016-01-18 17:00:09.257 ThaliTest[2288:4915580] client session: disconnect
2016-01-18 17:00:09.257 ThaliTest[2288:4915580] client session: stateCha,nge:2->0 1453132797207.2234.jwEahg==
,2016-01-18 17:00:09.261 ThaliTest[2288:4915580] client session: fireConnectionErrorEvent: 1453132797207.2234.jwEahg==
,calling stopBroadcasting
,2016-01-18 17:00:09.822 ThaliTest[2288:4915753] jxcore: stopBroadcasting
2016-01-18 17:00:09.822 ThaliTest[2288:4915753] THEMultipeerSession stopping peer
2016-01-18 17:00:09.822 ThaliTest[2288:4915753] multipeer session: stop timer
2016-01-18 17:00:09.822 ThaliTest[2288:4915753] server session: disconnect
2016-01-18 17:00:09.822 ThaliTest[2288:4915753] server session: stateChange:2->0 1453132797207.2234
,2016-01-18 17:00:10.493 ThaliTest[2288:4915753] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/08A1DA0B-2C4E-4EC8-873C-16553E0C36DC/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 104 starting event should occur in right order
,2016-01-18 17:00:11.053 ThaliTest[2288:4915753] jxcore: startBroadcasting
,2016-01-18 17:00:11.054 ThaliTest[2288:4915753] server: starting yCstZ4Sd0RTetg_9toXX5w.W9yK1Q==
2016-01-18 17:00:11.054 ThaliTest[2288:4915753] multipeer session: start timer: 0x167b20a0
2016-01-18 17:00:11.054 ThaliTest[2288:4915753] THEMultipeerSessio,n initialized peer yCstZ4Sd0RTetg_9toXX5w
2016-01-18 17:00:11.054 ThaliTest[2288:4915753] jxcore: startBroadcasting: success
ok 105 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
,ok 106 stopping event should occur in right order
,About to call stopBroadcasting
,2016-01-18 17:00:11.056 ThaliTest[2288:4915753] jxcore: stopBroadcasting
2016-01-18 17:00:11.056 ThaliTest[2288:4915753] THEMultipeerSession stopping peer
2016-01-18 17:00:11.056 ThaliTest[2288:4915753] multipeer session: stop timer
2016-01-18 17:00:11.056 ThaliTest[2288:4915753] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
ok 107 stopped event should occur in right order
,mux server bridge listener closed
,# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/08A1DA0B-2C4E-4EC8-873C-16553E0C36DC/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-18 17:00:16.774 ThaliTest[2288:4915753] jxcore: startBroadcasting
,2016-01-18 17:00:16.775 ThaliTest[2288:4915753] server: starting yCstZ4Sd0RTetg_9toXX5w.M3XF4g==
2016-01-18 17:00:16.775 ThaliTest[2288:4915753] multipeer session: start timer: 0x18553270
2016-01-18 17:00:16.776 ThaliTest[2288:4915753] THEMultipeerSession initialized peer yCstZ4Sd0RTetg_9toXX5w
2016-01-18 17:00:16.776 ThaliTest[2288:4915753] jxcore: startBroadcasting: success
ok 108 getDeviceIdentity should not return an error
ok 109 deviceName should not be null
Now in TRM stop
State of this._isStar,ted: true
About to call stopBroadcasting
2016-01-18 17:00:16.777 ThaliTest[2288:4915753] jxcore: stopBroadcasting
2016-01-18 17:00:16.777 ThaliTest[2288:4915753] THEMultipeerSession stopping peer
2016-01-18 17:00:16.777 ThaliTest[2288:4915753] multipeer session: stop timer
2016-01-18 17:00:16.777 ThaliTest[2288:4915753] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
,mux server bridge listener closed
# setup
,# ThaliReplicationManager replicates database
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/08A1DA0B-2C4E-4EC8-873C-16553E0C36DC/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-18 17:00:18.890 ThaliTest[2288:4915753] jxcore: startBroadcasting
,2016-01-18 17:00:18.891 ThaliTest[2288:4915753] server: starting yCstZ4Sd0RTetg_9toXX5w.0pWsNA==
2016-01-18 17:00:18.892 ThaliTest[2288:4915753] multipeer session: start timer: 0x18704eb0
2016-01-18 17:00:18.892 ThaliTest[2288:4915753] THEMultipeerSession initialized peer yCstZ4Sd0RTetg_9toXX5w
2016-01-18 17:00:18.892 ThaliTest[2288:4915753] jxcore: startBroadcasting: success
ok 110 getDeviceIdentity should not return an error
,ok 111 deviceName should not be null
,2016-01-18 17:00:19.909 ThaliTest[2288:4915580] client: found peer: eZmb8BwK0mIYuCnydkHhJA.5GIvug==
,2016-01-18 17:00:22.907 ThaliTest[2288:4915753] jxcore: connect eZmb8BwK0mIYuCnydkHhJA.5GIvug==
,2016-01-18 17:00:22.907 ThaliTest[2288:4915753] client session: connect
,2016-01-18 17:00:22.908 ThaliTest[2288:4915753] client session: stateChange:0->1 eZmb8BwK0mIYuCnydkHhJA.5GIvug==
,ok 112 Should be able to put doc without error
,ok 113 1st change of local doc should contain local id
,2016-01-18 17:00:23.647 ThaliTest[2288:4915580] multipeer session: reset timer
2016-01-18 17:00:23.647 ThaliTest[2288:4915580] multipeer session: stop timer
,2016-01-18 17:00:23.647 ThaliTest[2288:4915580] multipeer session: start timer: 0x18704eb0
,2016-01-18 17:00:23.647 ThaliTest[2288:4915580] server session: connect
2016-01-18 17:00:23.647 ThaliTest[2288:4915580] server session: stateChange:0->1 eZmb8BwK0mIYuCnydkHhJA
,2016-01-18 17:00:23.649 ThaliTest[2288:4915580] server: accepting invitation eZmb8BwK0mIYuCnydkHhJA
,2016-01-18 17:00:27.818 ThaliTest[2288:4916372] client session: connected
2016-01-18 17:00:27.818 ThaliTest[2288:4916372] client session: stateChange:1->2 eZmb8BwK0mIYuCnydkHhJA.5GIvug==
,2016-01-18 17:00:27.833 ThaliTest[2288:4916362] client session: fireConnectCallback: eZmb8BwK0mIYuCnydkHhJA.5GIvug==
2016-01-18 17:00:27.833 ThaliTest[2288:4916362] jxcore: connect: success
,2016-01-18 17:00:27.837 ThaliTest[2288:4915580] client: relay established
2016-01-18 17:00:27.837 ThaliTest[2288:4915580] client: new accepted socket: 0x1a0f0f50
,client bridge: new client socket
,client bridge: new client socket
,2016-01-18 17:00:27.904 ThaliTest[2288:4916613] server session: connected
2016-01-18 17:00:27.904 ThaliTest[2288:4916613] server session: stateChange:1->2 eZmb8BwK0mIYuCnydkHhJA
,2016-01-18 17:00:27.909 ThaliTest[2288:4915580] server relay: connected (to port: 54123)
,server bridge: new client socket
,client bridge: socket closed
client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
client bridge: socket closed
client bridge: socket closed
client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,ok 114 1st change of remote doc should contain remote id
,ok 115 Can update remote doc without error
,null
,{ ok: true,
  id: '83682866-f022-4561-afa3-69bc10bace71',
  rev: '2-7b6503ef6391c898dd252f1e27c1c604' }
,client bridge: new client socket
,ok 116 Remote changes occur in strict order
,client bridge: socket closed
client bridge: socket closed
client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,2016-01-18 17:00:53.648 ThaliTest[2288:4915580] multipeer session: restart
,2016-01-18 17:00:53.657 ThaliTest[2288:4915580] client: found peer: eZmb8BwK0mIYuCnydkHhJA.5GIvug==
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,2016-01-18 17:01:23.648 ThaliTest[2288:4915580] multipeer session: restart
,2016-01-18 17:01:23.658 ThaliTest[2288:4915580] client: found peer: eZmb8BwK0mIYuCnydkHhJA.5GIvug==
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,2016-01-18 17:01:53.648 ThaliTest[2288:4915580] multipeer session: restart
,2016-01-18 17:01:53.654 ThaliTest[2288:4915580] client: found peer: eZmb8BwK0mIYuCnydkHhJA.5GIvug==
,client bridge: new client socket
,ok 117 Local changes occur in strict order
ok 118 2nd change of local doc should contain remote id
,# setup
,Now in TRM stop
State of this._isStarted: true
About to call stopBroadcasting
,2016-01-18 17:01:59.982 ThaliTest[2288:4915753] jxcore: stopBroadcasting
2016-01-18 17:01:59.982 ThaliTest[2288:4915753] THEMultipeerSession stopping peer
2016-01-18 17:01:59.982 ThaliTest[2288:4915753] multipeer session: stop timer
2016-01-18 17:01:59.983 ThaliTest[2288:4915753] client session: disconnect
2016-01-18 17:01:59.983 ThaliTest[2288:4915753] client session: stateChange:2->0 eZmb8BwK0mIYuCnydkHhJA.5GIvug==
,2016-01-18 17:01:59.986 ThaliTest[2288:4915753] server session: disconnect
2016-01-18 17:01:59.986 ThaliTest[2288:4915753] server session: stateChange:2->0 eZmb8BwK0mIYuCnydkHhJA
,2016-01-18 17:01:59.994 ThaliTest[2288:4915753] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
,mux server bridge listener closed
,server bridge: socket closed
,# #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
,# teardown
,ok 119 should be equal
,# setup
,# #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation
,# teardown
client bridge: socket closed
,ok 120 should not be equal
,# setup
,# verify that Thali-specific messages are filtered correctly

```
