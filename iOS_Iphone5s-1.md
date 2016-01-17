#### Test 56151093c886730_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56151093c886730/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/FA470174-9616-4B7C-91A2-400A840309A9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/FA470174-9616-4B7C-91A2-400A840309A9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/56151093c886730/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56151093c886730/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6BCDE975-8DDD-42FF-9BAC-E21A397CF13A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57159"
,(lldb)     command script import "/tmp/FA470174-9616-4B7C-91A2-400A840309A9/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-17 13:37:06.665 ThaliTest[2091:5116475] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B415A37F-137E-4BFC-B9C3-10221DCD3A48/Library/Cookies/Cookies.binarycookies
,2016-01-17 13:37:06.954 ThaliTest[2091:5116475] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-17 13:37:06.955 ThaliTest[2091:5116475] Multi-tasking -> Device: YES, App: YES
,2016-01-17 13:37:06.963 ThaliTest[2091:5116475] Unlimited access to network resources
,2016-01-17 13:37:06.974 ThaliTest[2091:5116475] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-17 13:37:11.250 ThaliTest[2091:5116475] Resetting plugins due to page load.
,2016-01-17 13:37:12.659 ThaliTest[2091:5116475] Finished load of: file:///var/mobile/Containers/Bundle/Application/6BCDE975-8DDD-42FF-9BAC-E21A397CF13A/ThaliTest.app/www/index.html
,2016-01-17 13:37:12.843 ThaliTest[2091:5116475] JXcore Cordova plugin initializing
2016-01-17 13:37:12.845 ThaliTest[2091:5116625] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BCDE975-8DDD-42FF-9BAC-E21A397CF13A/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BCDE975-8DDD-42FF-9BAC-E21A397CF13A/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BCDE975-8DDD-42FF-9BAC-E21A397CF13A/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BCDE975-8DDD-42FF-9BAC-E21A397CF13A/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BCDE975-8DDD-42FF-9BAC-E21A397CF13A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BCDE975-8DDD-42FF-9BAC-E21A397CF13A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BCDE975-8DDD-42FF-9BAC-E21A397CF13A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
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
ok 7 should be equal
,ok 8 should not throw
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
# setup
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
,ok 30 should be equal
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
ok 35 should be equal
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
ok 42 should be equal
,# setup
,# should call Mobile("Disconnect") and handle an error
,# teardown
,ok 43 should be equal
ok 44 should be equal
,# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2016-01-17 13:42:07.168 ThaliTest[2091:5116625] jxcore: startBroadcasting
,2016-01-17 13:42:07.175 ThaliTest[2091:5116625] server: starting 1453034527168.2091.fA2+iw==
,2016-01-17 13:42:07.175 ThaliTest[2091:5116625] multipeer session: start timer: 0x1629b9b0
2016-01-17 13:42:07.175 ThaliTest[2091:5116625] THEMultipeerSession initialized peer 1453034527168.2091
2016-01-17 13:42:07.176 ThaliTest[2091:5116625] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
,2016-01-17 13:42:07.177 ThaliTest[2091:5116625] jxcore: stopBroadcasting
2016-01-17 13:42:07.178 ThaliTest[2091:5116625] THEMultipeerSession stopping peer
2016-01-17 13:42:07.179 ThaliTest[2091:5116625] multipeer session: stop timer
2016-01-17 13:42:07.182 ThaliTest[2091:5116625] jxcore: stopBroadcasting: success
,ok 46 Should be able to call stopBroadcasting without error
2016-01-17 13:42:07.183 ThaliTest[2091:5116625] jxcore: startBroadcasting
,2016-01-17 13:42:07.188 ThaliTest[2091:5116625] server: starting 1453034527183.2091.baaXQQ==
2016-01-17 13:42:07.189 ThaliTest[2091:5116625] multipeer session: start timer: 0x16298e00
2016-01-17 13:42:07.189 ThaliTest[2091:5116625] THEMultipeerSession initialized peer 1453034527183.2091
,2016-01-17 13:42:07.191 ThaliTest[2091:5116625] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-17 13:42:07.192 ThaliTest[2091:5116625] jxcore: stopBroadcasting
2016-01-17 13:42:07.192 ThaliTest[20,91:5116625] THEMultipeerSession stopping peer
2016-01-17 13:42:07.192 ThaliTest[2091:5116625] multipeer session: stop timer
2016-01-17 13:42:07.193 ThaliTest[2091:5116625] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
2016-01-17 13:42:07.194 ThaliTest[2091:5116625] jxcore: startBroadcasting
,2016-01-17 13:42:07.198 ThaliTest[2091:5116625] server: starting 1453034527194.2091.uRmdqQ==
2016-01-17 13:42:07.199 ThaliTest[2091:5116625] multipeer session: start timer: 0x161f1f80
2016-01-17 13:42:07.199 ThaliTest[2091:5116625] THEMultipeerSession in,itialized peer 1453034527194.2091
2016-01-17 13:42:07.199 ThaliTest[2091:5116625] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2016-01-17 13:42:07.200 ThaliTest[2091:5116625] jxcore: stopBroadcasting
2,016-01-17 13:42:07.200 ThaliTest[2091:5116625] THEMultipeerSession stopping peer
2016-01-17 13:42:07.201 ThaliTest[2091:5116625] multipeer session: stop timer
2016-01-17 13:42:07.201 ThaliTest[2091:5116625] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
2016-01-17 13:42:07.202 ThaliTest[2091:5116625] jxcore: startBroadcasting
2016-01-17 13:42:07.204 ThaliTest[2091:5116625] server: starting 1453034527202.2091.ACM+wQ==
2016-01-17 13:42:07.205 Th,aliTest[2091:5116625] multipeer session: start timer: 0x161f7580
2016-01-17 13:42:07.205 ThaliTest[2091:5116625] THEMultipeerSession initialized peer 1453034527202.2091
2016-01-17 13:42:07.205 ThaliTest[2091:5116625] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2016-01-17 13:42:07.206 ThaliTest[2091:5116625] jxcore: stopBroadcasting
2016-01-17 13:42:07.206 ThaliTest[2091:5116625] THEMultipeerSession stopping peer
,2016-01-17 13:42:07.206 ThaliTest[2091:5116625] multipeer session: stop timer
2016-01-17 13:42:07.209 ThaliTest[2091:5116625] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
2016-01-17 13:42:07.211 ThaliTest[2091:5116625] jxcore: startBroadcasting
,2016-01-17 13:42:07.220 ThaliTest[2091:5116625] server: starting 1453034527211.2091.WM6yHA==
2016-01-17 13:42:07.221 ThaliTest[2091:5116625] multipeer session: start timer: 0x161f2920
2016-01-17 13:42:07.221 ThaliTest[2091:5116625] THEMultipeerSession in,itialized peer 1453034527211.2091
2016-01-17 13:42:07.221 ThaliTest[2091:5116625] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
,2016-01-17 13:42:07.223 ThaliTest[2091:5116625] jxcore: stopBroadcasting
2016-01-17 13:42:07.224 ThaliTest[2091:5116625] THEMultipeerSession stopping peer
2016-01-17 13:42:07.224 ThaliTest[2091:5116625] multipeer session: stop timer
2016-01-17 13:42:07.224 ThaliTest[2091:5116625] jxcore: stopBroadcasting: success
ok 54 Should be able to call stopBroadcasting without error
,2016-01-17 13:42:07.226 ThaliTest[2091:5116625] jxcore: startBroadcasting
,2016-01-17 13:42:07.228 ThaliTest[2091:5116625] server: starting 1453034527225.2091.qoPsEw==
2016-01-17 13:42:07.229 ThaliTest[2091:5116625] multipeer session: start timer: 0x161f6c40
2016-01-17 13:42:07.229 ThaliTest[2091:5116625] THEMultipeerSession in,itialized peer 1453034527225.2091
2016-01-17 13:42:07.229 ThaliTest[2091:5116625] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error
2016-01-17 13:42:07.230 ThaliTest[2091:5116625] jxcore: stopBroadcasting
2,016-01-17 13:42:07.230 ThaliTest[2091:5116625] THEMultipeerSession stopping peer
,2016-01-17 13:42:07.230 ThaliTest[2091:5116625] multipeer session: stop timer
2016-01-17 13:42:07.234 ThaliTest[2091:5116625] jxcore: stopBroadcasting: success
ok 56 Should be able to call stopBroadcasting without error
2016-01-17 13:42:07.236 ThaliTest[2091:5116625] jxcore: startBroadcasting
,2016-01-17 13:42:07.239 ThaliTest[2091:5116625] server: starting 1453034527235.2091.6CWabA==
2016-01-17 13:42:07.239 ThaliTest[2091:5116625] multipeer session: start timer: 0x161f7df0
2016-01-17 13:42:07.240 ThaliTest[2091:5116625] THEMultipeerSession in,itialized peer 1453034527235.2091
2016-01-17 13:42:07.240 ThaliTest[2091:5116625] jxcore: startBroadcasting: success
ok 57 Should be able to call startBroadcasting without error
2016-01-17 13:42:07.241 ThaliTest[2091:5116625] jxcore: stopBroadcasting
2,016-01-17 13:42:07.241 ThaliTest[2091:5116625] THEMultipeerSession stopping peer
2016-01-17 13:42:07.241 ThaliTest[2091:5116625] multipeer session: stop timer
2016-01-17 13:42:07.241 ThaliTest[2091:5116625] jxcore: stopBroadcasting: success
ok 58 Should be able to call stopBroadcasting without error
2016-01-17 13:42:07.242 ThaliTest[2091:5116625] jxcore: startBroadcasting
,2016-01-17 13:42:07.248 ThaliTest[2091:5116625] server: starting 1453034527242.2091.OG6FnQ==
2016-01-17 13:42:07.249 ThaliTest[2091:5116625] multipeer session: start timer: 0x161f3610
2016-01-17 13:42:07.249 ThaliTest[2091:5116625] THEMultipeerSession in,itialized peer 1453034527242.2091
2016-01-17 13:42:07.249 ThaliTest[2091:5116625] jxcore: startBroadcasting: success
ok 59 Should be able to call startBroadcasting without error
,2016-01-17 13:42:07.251 ThaliTest[2091:5116625] jxcore: stopBroadcasting
2016-01-17 13:42:07.251 ThaliTest[2091:5116625] THEMultipeerSession stopping peer
2016-01-17 13:42:07.251 ThaliTest[2091:5116625] multipeer session: stop timer
2016-01-17 13:42:07.251 ThaliTest[2091:5116625] jxcore: stopBroadcasting: success
ok 60 Should be able to call stopBroadcasting without error
2016-01-17 13:42:07.252 ThaliTest[2091:5116625] jxcore: startBroadcasting
,2016-01-17 13:42:07.259 ThaliTest[2091:5116625] server: starting 1453034527252.2091.p+Iznw==
2016-01-17 13:42:07.261 ThaliTest[2091:5116625] multipeer session: start timer: 0x161f3e70
2016-01-17 13:42:07.261 ThaliTest[2091:5116625] THEMultipeerSession initialized peer 1453034527252.2091
2016-01-17 13:42:07.261 ThaliTest[2091:5116625] jxcore: startBroadcasting: success
ok 61 Should be able to call startBroadcasting without error
2016-01-17 13:42:07.262 ThaliTest[2091:5116625] jxcore: stopBroadcasting
2,016-01-17 13:42:07.263 ThaliTest[2091:5116625] THEMultipeerSession stopping peer
2016-01-17 13:42:07.263 ThaliTest[2091:5116625] multipeer session: stop timer
2016-01-17 13:42:07.263 ThaliTest[2091:5116625] jxcore: stopBroadcasting: success
ok 62 Should, be able to call stopBroadcasting without error
2016-01-17 13:42:07.264 ThaliTest[2091:5116625] jxcore: startBroadcasting
,2016-01-17 13:42:07.269 ThaliTest[2091:5116625] server: starting 1453034527264.2091.jZOZqg==
2016-01-17 13:42:07.269 ThaliTest[2091:5116625] multipeer session: start timer: 0x161f3210
2016-01-17 13:42:07.269 ThaliTest[2091:5116625] THEMultipeerSession in,itialized peer 1453034527264.2091
2016-01-17 13:42:07.269 ThaliTest[2091:5116625] jxcore: startBroadcasting: success
ok 63 Should be able to call startBroadcasting without error
2016-01-17 13:42:07.271 ThaliTest[2091:5116625] jxcore: stopBroadcasting
2016-01-17 13:42:07.271 ThaliTest[2091:5116625] THEMultipeerSession stopping peer
2016-01-17 13:42:07.271 ThaliTest[2091:5116625] multipeer session: stop timer
2016-01-17 13:42:07.271 ThaliTest[2091:5116625] jxcore: stopBroadcasting: success
ok 64 Should, be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-17 13:42:07.455 ThaliTest[2091:5116625] jxcore: startBroadcasting
,2016-01-17 13:42:07.457 ThaliTest[2091:5116625] server: starting 1453034527455.2091.ZeMr9Q==
,2016-01-17 13:42:07.459 ThaliTest[2091:5116625] multipeer session: start timer: 0x16297a40
,2016-01-17 13:42:07.461 ThaliTest[2091:5116625] THEMultipeerSession initialized peer 1453034527455.2091
,2016-01-17 13:42:07.463 ThaliTest[2091:5116625] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
,2016-01-17 13:42:07.465 ThaliTest[2091:5116625] jxcore: startBroadcasting
,2016-01-17 13:42:07.465 ThaliTest[2091:5116625] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
,2016-01-17 13:42:07.467 ThaliTest[2091:5116625] jxcore: stopBroadcasting
,2016-01-17 13:42:07.467 ThaliTest[2091:5116625] THEMultipeerSession stopping peer
,2016-01-17 13:42:07.468 ThaliTest[2091:5116625] multipeer session: stop timer
,2016-01-17 13:42:07.469 ThaliTest[2091:5116625] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-17 13:42:07.518 ThaliTest[2091:5116625] jxcore: startBroadcasting
,2016-01-17 13:42:07.521 ThaliTest[2091:5116625] server: starting 1453034527518.2091.dwAr/A==
,2016-01-17 13:42:07.522 ThaliTest[2091:5116625] multipeer session: start timer: 0x161ec980
,2016-01-17 13:42:07.526 ThaliTest[2091:5116625] THEMultipeerSession initialized peer 1453034527518.2091
,2016-01-17 13:42:07.527 ThaliTest[2091:5116625] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error
,2016-01-17 13:42:07.529 ThaliTest[2091:5116625] jxcore: connect foobar
,2016-01-17 13:42:07.529 ThaliTest[2091:5116625] client: unknown peer foobar
,2016-01-17 13:42:07.530 ThaliTest[2091:5116625] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
,2016-01-17 13:42:07.532 ThaliTest[2091:5116625] jxcore: stopBroadcasting
,2016-01-17 13:42:07.532 ThaliTest[2091:5116625] THEMultipeerSession stopping peer
,2016-01-17 13:42:07.533 ThaliTest[2091:5116625] multipeer session: stop timer
,2016-01-17 13:42:07.533 ThaliTest[2091:5116625] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-17 13:42:07.586 ThaliTest[2091:5116625] jxcore: startBroadcasting
,2016-01-17 13:42:07.588 ThaliTest[2091:5116625] server: starting 1453034527585.2091.ufc3FA==
,2016-01-17 13:42:07.589 ThaliTest[2091:5116625] multipeer session: start timer: 0x14dd6a70
,2016-01-17 13:42:07.593 ThaliTest[2091:5116625] THEMultipeerSession initialized peer 1453034527585.2091
,2016-01-17 13:42:07.594 ThaliTest[2091:5116625] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error
,2016-01-17 13:42:07.595 ThaliTest[2091:5116625] jxcore: disconnect
,2016-01-17 13:42:07.596 ThaliTest[2091:5116625] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 
,2016-01-17 13:42:07.598 ThaliTest[2091:5116625] jxcore: stopBroadcasting
,2016-01-17 13:42:07.599 ThaliTest[2091:5116625] THEMultipeerSession stopping peer
,2016-01-17 13:42:07.599 ThaliTest[2091:5116625] multipeer session: stop timer
,2016-01-17 13:42:07.601 ThaliTest[2091:5116625] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-17 13:42:07.663 ThaliTest[2091:5116625] jxcore: startBroadcasting
,2016-01-17 13:42:07.665 ThaliTest[2091:5116625] server: starting 1453034527663.2091.H4vJTQ==
,2016-01-17 13:42:07.666 ThaliTest[2091:5116625] multipeer session: start timer: 0x14ddccb0
,2016-01-17 13:42:07.670 ThaliTest[2091:5116625] THEMultipeerSession initialized peer 1453034527663.2091
,2016-01-17 13:42:07.672 ThaliTest[2091:5116625] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error
,2016-01-17 13:42:08.801 ThaliTest[2091:5116475] client: found peer: 1453034527721.2121.CjYwww==
2016-01-17 13:42:08.802 ThaliTest[2091:5116625] jxcore: connect 1453034527721.2121.CjYwww==
2016-01-17 13:42:08.802 ThaliTest[2091:5116625] client session: co,nnect
2016-01-17 13:42:08.802 ThaliTest[2091:5116625] client session: stateChange:0->1 1453034527721.2121.CjYwww==
,2016-01-17 13:42:09.230 ThaliTest[2091:5116475] multipeer session: reset timer
2016-01-17 13:42:09.230 ThaliTest[2091:5116475] multipeer session: stop timer
2016-01-17 13:42:09.230 ThaliTest[2091:5116475] multipeer session: start timer: 0x14ddccb0
2016-,01-17 13:42:09.230 ThaliTest[2091:5116475] server session: connect
2016-01-17 13:42:09.231 ThaliTest[2091:5116475] server session: stateChange:0->1 1453034527721.2121
2016-01-17 13:42:09.234 ThaliTest[2091:5116475] server: accepting invitation 1453034527721.2121
,2016-01-17 13:42:11.743 ThaliTest[2091:5118519] server session: connected
2016-01-17 13:42:11.743 ThaliTest[2091:5118519] server session: stateChange:1->2 1453034527721.2121
,2016-01-17 13:42:11.755 ThaliTest[2091:5118518] client session: connected
2016-01-17 13:42:11.755 ThaliTest[2091:5118518] client session: stateChange:1->2 1453034527721.2121.CjYwww==
,2016-01-17 13:42:11.758 ThaliTest[2091:5116475] server relay: socket disconnected
2016-01-17 13:42:11.758 ThaliTest[2091:5116475] server relay: 0x166b0c90 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-17 13:42:11.814 ThaliTest[2091:5118515] client session: fireConnectCallback: 1453034527721.2121.CjYwww==
2016-01-17 13:42:11.814 ThaliTest[2091:5118515] jxcore: connect: success
ok 75 Should be able to connect without error
ok 76 Port should be within range
,2016-01-17 13:42:11.816 ThaliTest[2091:5116625] jxcore: disconnect
2016-01-17 13:42:11.818 ThaliTest[2091:5116625] client session: disconnectFromPeer: 1453034527721.2121.CjYwww==
2016-01-17 13:42:11.819 ThaliTest[2091:5116625] client session: disconnect
2016-01-17 13:42:11.819 ThaliTest[2091:5116625] client session: stateChange:2->0 1453034527721.2121.CjYwww==
,2016-01-17 13:42:11.823 ThaliTest[2091:5118518] server session: not connected 1453034527721.2121
,2016-01-17 13:42:11.833 ThaliTest[2091:5116625] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-17 13:42:12.313 ThaliTest[2091:5116625] jxcore: stopBroadcasting
2016-01-17 13:42:12.313 ThaliTest[2091:5116625] THEMultipeerSession stopping peer
2016-01-17 13:42:12.313 ThaliTest[2091:5116625] multipeer session: stop timer
2016-01-17 13:42:12.,313 ThaliTest[2091:5116625] server session: disconnect
2016-01-17 13:42:12.314 ThaliTest[2091:5116625] server session: stateChange:2->0 1453034527721.2121
,2016-01-17 13:42:12.316 ThaliTest[2091:5116625] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-17 13:42:23.319 ThaliTest[2091:5116625] jxcore: startBroadcasting
,2016-01-17 13:42:23.321 ThaliTest[2091:5116625] server: starting 1453034543319.2091.H54WmQ==
2016-01-17 13:42:23.321 ThaliTest[2091:5116625] multipeer session: start timer: 0x166b0da0
2016-01-17 13:42:23.321 ThaliTest[2091:5116625] THEMultipeerSession in,itialized peer 1453034543319.2091
2016-01-17 13:42:23.321 ThaliTest[2091:5116625] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-17 13:42:26.228 ThaliTest[2091:5116475] multipeer session: reset timer
2016-01-17 13:42:26.228 ThaliTest[2091:5116475] multipeer session: stop timer
2016-01-17 13:42:26.229 ThaliTest[2091:5116475] multipeer session: start timer: 0x166b0da0
2016-01-17 13:42:26.230 ThaliTest[2091:5116475] server session: connect
2016-01-17 13:42:26.230 ThaliTest[2091:5116475] server session: stateChange:0->1 1453034545,253.2121
,2016-01-17 13:42:26.234 ThaliTest[2091:5116475] server: accepting invitation 1453034545253.2121
,2016-01-17 13:42:26.548 ThaliTest[2091:5116475] client: found peer: 1453034545253.2121.vcInqQ==
,2016-01-17 13:42:26.549 ThaliTest[2091:5116625] jxcore: connect 1453034545253.2121.vcInqQ==
2016-01-17 13:42:26.550 ThaliTest[2091:5116625] client session: connect
2016-01-17 13:42:26.550 ThaliTest[2091:5116625] client session: stateChange:0->1 1453034545253.2121.vcInqQ==
,2016-01-17 13:42:28.787 ThaliTest[2091:5118595] server session: connected
2016-01-17 13:42:28.787 ThaliTest[2091:5118595] server session: stateChange:1->2 1453034545253.2121
,2016-01-17 13:42:28.836 ThaliTest[2091:5116475] server relay: socket disconnected
2016-01-17 13:42:28.836 ThaliTest[2091:5116475] server relay: 0x161ce0e0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-17 13:42:28.905 ThaliTest[2091:5118589] server session: not connected 1453034545253.2121
,2016-01-17 13:42:29.241 ThaliTest[2091:5118570] client session: connected
2016-01-17 13:42:29.242 ThaliTest[2091:5118570] client session: stateChange:1->2 1453034545253.2121.vcInqQ==
2016-01-17 13:42:29.243 ThaliTest[2091:5118570] client session: fireConnectCallback: 1453034545253.2121.vcInqQ==
2016-01-17 13:42:29.243 ThaliTest[2091:5118570] jxcore: connect: success
ok 79 Should be able to connect without error
ok 80 Port should be within range
,2016-01-17 13:42:29.245 ThaliTest[2091:5116625] jxcore: connect 1453034545253.2121.vcInqQ==
2016-01-17 13:42:29.245 ThaliTest[2091:5116625] client: already connect(ing/ed) to 1453034545253.2121.vcInqQ==
2016-01-17 13:42:29.246 ThaliTest[2091:5116625] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
,2016-01-17 13:42:29.247 ThaliTest[2091:5116625] jxcore: disconnect
2016-01-17 13:42:29.247 ThaliTest[2091:5116625] client session: disconnectFromPeer: 1453034545253.2121.vcInqQ==
2016-01-17 13:42:29.247 ThaliTest[2091:5116625] client session: disconnect
2016-01-17 13:42:29.247 ThaliTest[2091:5116625] client session: stateChange:2->0 1453034545253.2121.vcInqQ==
,2016-01-17 13:42:29.311 ThaliTest[2091:5116625] jxcore: disconnect: success
,ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-17 13:42:31.162 ThaliTest[2091:5116625] jxcore: stopBroadcasting
2016-01-17 13:42:31.163 ThaliTest[2091:5116625] THEMultipeerSession stopping peer
2016-01-17 13:42:31.163 ThaliTest[2091:5116625] multipeer session: stop timer
2016-01-17 13:42:31.163 ThaliTest[2091:5116625] server session: disconnect
2016-01-17 13:42:31.163 ThaliTest[2091:5116625] server session: stateChange:2->0 1453034545253.2121
,2016-01-17 13:42:31.165 ThaliTest[2091:5116625] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-17 13:42:44.327 ThaliTest[2091:5116625] jxcore: startBroadcasting
,2016-01-17 13:42:44.330 ThaliTest[2091:5116625] server: starting 1453034564327.2091.5p4ccQ==
2016-01-17 13:42:44.330 ThaliTest[2091:5116625] multipeer session: start timer: 0x161cb6d0
2016-01-17 13:42:44.330 ThaliTest[2091:5116625] THEMultipeerSession initialized peer 1453034564327.2091
2016-01-17 13:42:44.330 ThaliTest[2091:5116625] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-17 13:42:45.684 ThaliTest[2091:5116475] multipeer session: reset timer
2016-01-17 13:42:45.684 ThaliTest[2091:5116475] multipeer session: stop timer
2016-01-17 13:42:45.684 ThaliTest[2091:5116475] multipeer session: start timer: 0x161cb6d0
2016-01-17 13:42:45.684 ThaliTest[2091:5116475] server session: connect
2016-01-17 13:42:45.684 ThaliTest[2091:5116475] server session: stateChange:0->1 1453034565249.2121
2016-01-17 13:42:45.688 ThaliTest[2091:5116475] server: accepting invitation 1453034565249.2121
,2016-01-17 13:42:47.575 ThaliTest[2091:5116475] client: found peer: 1453034565249.2121.UrKUjg==
2016-01-17 13:42:47.576 ThaliTest[2091:5116625] jxcore: connect 1453034565249.2121.UrKUjg==
,2016-01-17 13:42:47.577 ThaliTest[2091:5116625] client session: connect
2016-01-17 13:42:47.577 ThaliTest[2091:5116625] client session: stateChange:0->1 1453034565249.2121.UrKUjg==
,2016-01-17 13:42:48.257 ThaliTest[2091:5118654] server session: connected
2016-01-17 13:42:48.257 ThaliTest[2091:5118654] server session: stateChange:1->2 1453034565249.2121
,2016-01-17 13:42:48.305 ThaliTest[2091:5118589] server session: not connected 1453034565249.2121
,2016-01-17 13:42:48.306 ThaliTest[2091:5116475] server relay: socket disconnected
2016-01-17 13:42:48.306 ThaliTest[2091:5116475] server relay: 0x166aa710 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-17 13:42:50.721 ThaliTest[2091:5118571] client session: connected
2016-01-17 13:42:50.721 ThaliTest[2091:5118571] client session: stateChange:1->2 1453034565249.2121.UrKUjg==
,2016-01-17 13:42:50.731 ThaliTest[2091:5118654] client session: fireConnectCallback: 1453034565249.2121.UrKUjg==
2016-01-17 13:42:50.731 ThaliTest[2091:5118654] jxcore: connect: success
ok 84 Should be able to connect without error
,ok 85 Port should be within range
,2016-01-17 13:42:50.734 ThaliTest[2091:5116625] jxcore: disconnect
2016-01-17 13:42:50.734 ThaliTest[2091:5116625] client session: disconnectFromPeer: 1453034565249.2121.UrKUjg==
2016-01-17 13:42:50.734 ThaliTest[2091:5116625] client session: disconnect
2016-01-17 13:42:50.734 ThaliTest[2091:5116625] client session: stateChange:2->0 1453034565249.2121.UrKUjg==
,2016-01-17 13:42:50.738 ThaliTest[2091:5116625] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
2016-01-17 13:42:50.740 ThaliTest[2091:5116625] jxcore: disconnect
2016-01-17 13:42:50.740 ThaliTest[2091:5116625] jxcore: disconnect: fail
ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-17 13:42:51.628 ThaliTest[2091:5116625] jxcore: stopBroadcasting
2016-01-17 13:42:51.628 ThaliTest[2091:5116625] THEMultipeerSession stopping peer
2016-01-17 13:42:51.628 ThaliTest[2091:5116625] multipeer session: stop timer
2016-01-17 13:42:51.,629 ThaliTest[2091:5116625] server session: disconnect
2016-01-17 13:42:51.629 ThaliTest[2091:5116625] server session: stateChange:2->0 1453034565249.2121
2016-01-17 13:42:51.629 ThaliTest[2091:5116625] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can connect and send data

```
