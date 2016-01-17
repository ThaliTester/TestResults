#### Test 5615109319b4771_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5615109319b4771/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/5AD87E34-CDE4-48A4-90B0-A12CEC1B7D09/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/5AD87E34-CDE4-48A4-90B0-A12CEC1B7D09/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5615109319b4771/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5615109319b4771/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/42879C1F-2E76-4D85-93EE-1197A04F5340/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57416"
,(lldb)     command script import "/tmp/5AD87E34-CDE4-48A4-90B0-A12CEC1B7D09/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-17 16:31:53.860 ThaliTest[2112:5146895] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5C25A5A2-943F-4E54-88F0-7A8575921DE4/Library/Cookies/Cookies.binarycookies
,2016-01-17 16:31:54.149 ThaliTest[2112:5146895] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-17 16:31:54.150 ThaliTest[2112:5146895] Multi-tasking -> Device: YES, App: YES
,2016-01-17 16:31:54.158 ThaliTest[2112:5146895] Unlimited access to network resources
,2016-01-17 16:31:54.168 ThaliTest[2112:5146895] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-17 16:31:58.526 ThaliTest[2112:5146895] Resetting plugins due to page load.
,2016-01-17 16:31:59.913 ThaliTest[2112:5146895] Finished load of: file:///var/mobile/Containers/Bundle/Application/42879C1F-2E76-4D85-93EE-1197A04F5340/ThaliTest.app/www/index.html
,2016-01-17 16:32:00.117 ThaliTest[2112:5146895] JXcore Cordova plugin initializing
,2016-01-17 16:32:00.119 ThaliTest[2112:5147066] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/42879C1F-2E76-4D85-93EE-1197A04F5340/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/42879C1F-2E76-4D85-93EE-1197A04F5340/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/42879C1F-2E76-4D85-93EE-1197A04F5340/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/42879C1F-2E76-4D85-93EE-1197A04F5340/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/42879C1F-2E76-4D85-93EE-1197A04F5340/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/42879C1F-2E76-4D85-93EE-1197A04F5340/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/42879C1F-2E76-4D85-93EE-1197A04F5340/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test app app.js loaded
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
# setup
,# failed to get mobile documents path
,# teardown
,ok 15 should be equal
,# setup
,# #init should register the peerAvailabilityChanged event
,# teardown
,ok 16 should be equal
ok 17 should be equal
ok 18 should be equal
,# setup
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
# setup
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
ok 42 should be equal
,# setup
,# should call Mobile("Disconnect") and handle an error
,# teardown
,ok 43 should be equal
,ok 44 should be equal
,# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2016-01-17 16:37:19.206 ThaliTest[2112:5147066] jxcore: startBroadcasting
,2016-01-17 16:37:19.214 ThaliTest[2112:5147066] server: starting 1453045039206.2112.25mkcg==
,2016-01-17 16:37:19.214 ThaliTest[2112:5147066] multipeer session: start timer: 0x16757330
2016-01-17 16:37:19.214 ThaliTest[2112:5147066] THEMultipeerSession initialized peer 1453045039206.2112
,2016-01-17 16:37:19.215 ThaliTest[2112:5147066] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
2016-01-17 16:37:19.217 ThaliTest[2112:5147066] jxcore: stopBroadcasting
2016-01-17 16:37:19.217 ThaliTest[2112:5147066] THEMultipeerSession stopping peer
2016-01-17 16:37:19.217 ThaliTest[2112:5147066] multipeer session: stop timer
2016-01-17 16:37:19.217 ThaliTest[2112:5147066] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-17 16:37:19.218 ThaliTest[2112:5147066] jxcore: startBroadcasting
,2016-01-17 16:37:19.225 ThaliTest[2112:5147066] server: starting 1453045039218.2112.nxWq/A==
,2016-01-17 16:37:19.227 ThaliTest[2112:5147066] multipeer session: start timer: 0x167598b0
2016-01-17 16:37:19.227 ThaliTest[2112:5147066] THEMultipeerSession initialized peer 1453045039218.2112
2016-01-17 16:37:19.227 ThaliTest[2112:5147066] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
,2016-01-17 16:37:19.229 ThaliTest[2112:5147066] jxcore: stopBroadcasting
2016-01-17 16:37:19.229 ThaliTest[2112:5147066] THEMultipeerSession stopping peer
2016-01-17 16:37:19.229 ThaliTest[2112:5147066] multipeer session: stop timer
2016-01-17 16:37:19.230 ThaliTest[2112:5147066] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
,2016-01-17 16:37:19.231 ThaliTest[2112:5147066] jxcore: startBroadcasting
,2016-01-17 16:37:19.234 ThaliTest[2112:5147066] server: starting 1453045039230.2112.Z+THcQ==
2016-01-17 16:37:19.235 ThaliTest[2112:5147066] multipeer session: start timer: 0x167598b0
2016-01-17 16:37:19.235 ThaliTest[2112:5147066] THEMultipeerSession in,itialized peer 1453045039230.2112
2016-01-17 16:37:19.235 ThaliTest[2112:5147066] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2016-01-17 16:37:19.237 ThaliTest[2112:5147066] jxcore: stopBroadcasting
2016-01-17 16:37:19.237 ThaliTest[2112:5147066] THEMultipeerSession stopping peer
2016-01-17 16:37:19.237 ThaliTest[2112:5147066] multipeer session: stop timer
2016-01-17 16:37:19.,238 ThaliTest[2112:5147066] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error
2016-01-17 16:37:19.239 ThaliTest[2112:5147066] jxcore: startBroadcasting
,2016-01-17 16:37:19.243 ThaliTest[2112:5147066] server: starting 1453045039239.2112.s66AUw==
2016-01-17 16:37:19.243 ThaliTest[2112:5147066] multipeer session: start timer: 0x14d2f830
2016-01-17 16:37:19.243 ThaliTest[2112:5147066] THEMultipeerSession in,itialized peer 1453045039239.2112
2016-01-17 16:37:19.244 ThaliTest[2112:5147066] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2016-01-17 16:37:19.244 ThaliTest[2112:5147066] jxcore: stopBroadcasting
2,016-01-17 16:37:19.245 ThaliTest[2112:5147066] THEMultipeerSession stopping peer
2016-01-17 16:37:19.245 ThaliTest[2112:5147066] multipeer session: stop timer
2016-01-17 16:37:19.245 ThaliTest[2112:5147066] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
,2016-01-17 16:37:19.247 ThaliTest[2112:5147066] jxcore: startBroadcasting
,2016-01-17 16:37:19.249 ThaliTest[2112:5147066] server: starting 1453045039246.2112.oD9Kjg==
2016-01-17 16:37:19.249 ThaliTest[2112:5147066] multipeer session: start timer: 0x14d34cd0
2016-01-17 16:37:19.249 ThaliTest[2112:5147066] THEMultipeerSession initialized peer 1453045039246.2112
,2016-01-17 16:37:19.252 ThaliTest[2112:5147066] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2016-01-17 16:37:19.254 ThaliTest[2112:5147066] jxcore: stopBroadcasting
2016-01-17 16:37:19.254 ThaliTest[21,12:5147066] THEMultipeerSession stopping peer
,2016-01-17 16:37:19.254 ThaliTest[2112:5147066] multipeer session: stop timer
2016-01-17 16:37:19.255 ThaliTest[2112:5147066] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-17 16:37:19.259 ThaliTest[2112:5147066] jxcore: startBroadcasting
,2016-01-17 16:37:19.262 ThaliTest[2112:5147066] server: starting 1453045039259.2112.N5NnoQ==
,2016-01-17 16:37:19.265 ThaliTest[2112:5147066] multipeer session: start timer: 0x1675c810
,2016-01-17 16:37:19.267 ThaliTest[2112:5147066] THEMultipeerSession initialized peer 1453045039259.2112
,2016-01-17 16:37:19.267 ThaliTest[2112:5147066] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-17 16:37:19.269 ThaliTest[2112:5147066] jxcore: stopBroadcasting
,2016-01-17 16:37:19.270 ThaliTest[2112:5147066] THEMultipeerSession stopping peer
,2016-01-17 16:37:19.270 ThaliTest[2112:5147066] multipeer session: stop timer
,2016-01-17 16:37:19.272 ThaliTest[2112:5147066] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-17 16:37:19.275 ThaliTest[2112:5147066] jxcore: startBroadcasting
,2016-01-17 16:37:19.277 ThaliTest[2112:5147066] server: starting 1453045039275.2112./F2gBw==
,2016-01-17 16:37:19.279 ThaliTest[2112:5147066] multipeer session: start timer: 0x14d3c720
,2016-01-17 16:37:19.280 ThaliTest[2112:5147066] THEMultipeerSession initialized peer 1453045039275.2112
,2016-01-17 16:37:19.281 ThaliTest[2112:5147066] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-17 16:37:19.283 ThaliTest[2112:5147066] jxcore: stopBroadcasting
,2016-01-17 16:37:19.284 ThaliTest[2112:5147066] THEMultipeerSession stopping peer
,2016-01-17 16:37:19.284 ThaliTest[2112:5147066] multipeer session: stop timer
,2016-01-17 16:37:19.286 ThaliTest[2112:5147066] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-17 16:37:19.288 ThaliTest[2112:5147066] jxcore: startBroadcasting
,2016-01-17 16:37:19.291 ThaliTest[2112:5147066] server: starting 1453045039288.2112.pYMrCQ==
,2016-01-17 16:37:19.293 ThaliTest[2112:5147066] multipeer session: start timer: 0x14d3e830
,2016-01-17 16:37:19.294 ThaliTest[2112:5147066] THEMultipeerSession initialized peer 1453045039288.2112
,2016-01-17 16:37:19.295 ThaliTest[2112:5147066] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-17 16:37:19.296 ThaliTest[2112:5147066] jxcore: stopBroadcasting
,2016-01-17 16:37:19.297 ThaliTest[2112:5147066] THEMultipeerSession stopping peer
,2016-01-17 16:37:19.298 ThaliTest[2112:5147066] multipeer session: stop timer
,2016-01-17 16:37:19.299 ThaliTest[2112:5147066] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-17 16:37:19.302 ThaliTest[2112:5147066] jxcore: startBroadcasting
,2016-01-17 16:37:19.304 ThaliTest[2112:5147066] server: starting 1453045039302.2112.EpsDnA==
,2016-01-17 16:37:19.305 ThaliTest[2112:5147066] multipeer session: start timer: 0x14d3f0d0
,2016-01-17 16:37:19.307 ThaliTest[2112:5147066] THEMultipeerSession initialized peer 1453045039302.2112
,2016-01-17 16:37:19.308 ThaliTest[2112:5147066] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-17 16:37:19.310 ThaliTest[2112:5147066] jxcore: stopBroadcasting
,2016-01-17 16:37:19.311 ThaliTest[2112:5147066] THEMultipeerSession stopping peer
,2016-01-17 16:37:19.311 ThaliTest[2112:5147066] multipeer session: stop timer
,2016-01-17 16:37:19.313 ThaliTest[2112:5147066] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-17 16:37:19.316 ThaliTest[2112:5147066] jxcore: startBroadcasting
,2016-01-17 16:37:19.318 ThaliTest[2112:5147066] server: starting 1453045039316.2112.RshZNw==
,2016-01-17 16:37:19.319 ThaliTest[2112:5147066] multipeer session: start timer: 0x14d40750
,2016-01-17 16:37:19.321 ThaliTest[2112:5147066] THEMultipeerSession initialized peer 1453045039316.2112
,2016-01-17 16:37:19.322 ThaliTest[2112:5147066] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-17 16:37:19.324 ThaliTest[2112:5147066] jxcore: stopBroadcasting
,2016-01-17 16:37:19.325 ThaliTest[2112:5147066] THEMultipeerSession stopping peer
,2016-01-17 16:37:19.325 ThaliTest[2112:5147066] multipeer session: stop timer
,2016-01-17 16:37:19.327 ThaliTest[2112:5147066] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-17 16:37:19.595 ThaliTest[2112:5147066] jxcore: startBroadcasting
,2016-01-17 16:37:19.597 ThaliTest[2112:5147066] server: starting 1453045039595.2112.TSXpVg==
2016-01-17 16:37:19.597 ThaliTest[2112:5147066] multipeer session: start timer: 0x16760580
2016-01-17 16:37:19.598 ThaliTest[2112:5147066] THEMultipeerSession in,itialized peer 1453045039595.2112
2016-01-17 16:37:19.598 ThaliTest[2112:5147066] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-17 16:37:19.599 ThaliTest[2112:5147066] jxcore: startBroadcasting
2016-01-17 16:37:19.599 ThaliTest[2112:5147066] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
2016-01-17 16:37:19.601 ThaliTest[2112:5147066] jxcore: stopBroadcasting
2016-01-17 16:37:19.601 ThaliTest[2112:5147066] THEMultipeerSession stopping peer
2016-01-17 16:37:19.601 ThaliTest[2112:5147066] multipeer session: stop timer
2016-01-17 16:37:19.601 ThaliTest[2112:5147066] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-17 16:37:19.661 ThaliTest[2112:5147066] jxcore: startBroadcasting
,2016-01-17 16:37:19.662 ThaliTest[2112:5147066] server: starting 1453045039661.2112.UCpXAg==
2016-01-17 16:37:19.663 ThaliTest[2112:5147066] multipeer session: start timer: 0x16761e60
2016-01-17 16:37:19.663 ThaliTest[2112:5147066] THEMultipeerSession in,itialized peer 1453045039661.2112
2016-01-17 16:37:19.663 ThaliTest[2112:5147066] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-17 16:37:19.664 ThaliTest[2112:5147066] jxcore: connect foobar
,2016-01-17 16:37:19.665 ThaliTest[2112:5147066] client: unknown peer foobar
2016-01-17 16:37:19.665 ThaliTest[2112:5147066] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
2016-01-17 16:37:19.666 ThaliTest[2112:5147066] jxcore,: stopBroadcasting
2016-01-17 16:37:19.666 ThaliTest[2112:5147066] THEMultipeerSession stopping peer
2016-01-17 16:37:19.666 ThaliTest[2112:5147066] multipeer session: stop timer
2016-01-17 16:37:19.667 ThaliTest[2112:5147066] jxcore: stopBroadcasting: ,success
ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-17 16:37:20.087 ThaliTest[2112:5147066] jxcore: startBroadcasting
,2016-01-17 16:37:20.089 ThaliTest[2112:5147066] server: starting 1453045040087.2112.WEfUjw==
2016-01-17 16:37:20.090 ThaliTest[2112:5147066] multipeer session: start timer: 0x14d5b150
2016-01-17 16:37:20.090 ThaliTest[2112:5147066] THEMultipeerSession initialized peer 1453045040087.2112
2016-01-17 16:37:20.090 ThaliTest[2112:5147066] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-17 16:37:20.091 ThaliTest[2112:5147066] jxcore: disconnect
2016-01-17 16:37:20.091 ThaliTest[2112:5147066] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
,2016-01-17 16:37:20.092 ThaliTest[2112:5147066] jxcore: stopBroadcasting
2016-01-17 16:37:20.096 ThaliTest[2112:5147066] THEMultipeerSession stopping peer
2016-01-17 16:37:20.096 ThaliTest[2112:5147066] multipeer session: stop timer
2016-01-17 16:37:20.096 ThaliTest[2112:5147066] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-17 16:37:20.142 ThaliTest[2112:5147066] jxcore: startBroadcasting
,2016-01-17 16:37:20.145 ThaliTest[2112:5147066] server: starting 1453045040142.2112.yMbgNQ==
2016-01-17 16:37:20.145 ThaliTest[2112:5147066] multipeer session: start timer: 0x16763cb0
2016-01-17 16:37:20.146 ThaliTest[2112:5147066] THEMultipeerSession initialized peer 1453045040142.2112
2016-01-17 16:37:20.146 ThaliTest[2112:5147066] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-17 16:37:21.312 ThaliTest[2112:5146895] client: found peer: 1453045040286.1507.MdskSg==
2016-01-17 16:37:21.314 ThaliTest[2112:5147066] jxcore: connect 1453045040286.1507.MdskSg==
,2016-01-17 16:37:21.314 ThaliTest[2112:5147066] client session: connect
,2016-01-17 16:37:21.314 ThaliTest[2112:5147066] client session: stateChange:0->1 1453045040286.1507.MdskSg==
,2016-01-17 16:37:21.523 ThaliTest[2112:5146895] multipeer session: reset timer
2016-01-17 16:37:21.523 ThaliTest[2112:5146895] multipeer session: stop timer
2016-01-17 16:37:21.523 ThaliTest[2112:5146895] multipeer session: start timer: 0x16763cb0
2016-01-17 16:37:21.524 ThaliTest[2112:5146895] server session: connect
2016-01-17 16:37:21.524 ThaliTest[2112:5146895] server session: stateChange:0->1 1453045040286.1507
,2016-01-17 16:37:21.528 ThaliTest[2112:5146895] server: accepting invitation 1453045040286.1507
,2016-01-17 16:37:24.069 ThaliTest[2112:5147867] server session: connected
2016-01-17 16:37:24.069 ThaliTest[2112:5147867] server session: stateChange:1->2 1453045040286.1507
,2016-01-17 16:37:24.076 ThaliTest[2112:5146895] server relay: socket disconnected
2016-01-17 16:37:24.076 ThaliTest[2112:5146895] server relay: 0x167eb580 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-17 16:37:24.133 ThaliTest[2112:5147876] server session: not connected 1453045040286.1507
,2016-01-17 16:37:24.234 ThaliTest[2112:5147867] client session: connected
,2016-01-17 16:37:24.234 ThaliTest[2112:5147867] client session: stateChange:1->2 1453045040286.1507.MdskSg==
2016-01-17 16:37:24.237 ThaliTest[2112:5147867] client session: fireConnectCallback: 1453045040286.1507.MdskSg==
2016-01-17 16:37:24.237 ThaliTes,t[2112:5147867] jxcore: connect: success
ok 75 Should be able to connect without error
ok 76 Port should be within range
,2016-01-17 16:37:24.239 ThaliTest[2112:5147066] jxcore: disconnect
2016-01-17 16:37:24.239 ThaliTest[2112:5147066] client session: disconnectFromPeer: 1453045040286.1507.MdskSg==
2016-01-17 16:37:24.239 ThaliTest[2112:5147066] client session: disconnect
2016-01-17 16:37:24.239 ThaliTest[2112:5147066] client session: stateChange:2->0 1453045040286.1507.MdskSg==
,2016-01-17 16:37:24.306 ThaliTest[2112:5147066] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
2016-01-17 16:37:24.397 ThaliTest[2112:5147066] jxcore: stopBroadcasting
2016-01-17 16:37:24.397 ThaliTest[2112:5147066] THEMultipeerSession stopping peer
2016-01-17 16:37:24.397 ThaliTest[2112:5147066] multipeer session: stop t,imer
2016-01-17 16:37:24.397 ThaliTest[2112:5147066] server session: disconnect
2016-01-17 16:37:24.397 ThaliTest[2112:5147066] server session: stateChange:2->0 1453045040286.1507
,2016-01-17 16:37:24.398 ThaliTest[2112:5147066] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-17 16:37:24.924 ThaliTest[2112:5147066] jxcore: startBroadcasting
,2016-01-17 16:37:24.926 ThaliTest[2112:5147066] server: starting 1453045044924.2112.72qDhg==
2016-01-17 16:37:24.927 ThaliTest[2112:5147066] multipeer session: start timer: 0x167f9b20
2016-01-17 16:37:24.927 ThaliTest[2112:5147066] THEMultipeerSession in,itialized peer 1453045044924.2112
2016-01-17 16:37:24.927 ThaliTest[2112:5147066] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-17 16:37:26.575 ThaliTest[2112:5146895] multipeer session: reset timer
2016-01-17 16:37:26.575 ThaliTest[2112:5146895] multipeer session: stop timer
2016-01-17 16:37:26.576 ThaliTest[2112:5146895] multipeer session: start timer: 0x167f9b20
2016-,01-17 16:37:26.576 ThaliTest[2112:5146895] server session: connect
2016-01-17 16:37:26.577 ThaliTest[2112:5146895] server session: stateChange:0->1 1453045045528.1507
2016-01-17 16:37:26.580 ThaliTest[2112:5146895] server: accepting invitation 1453045045528.1507
,2016-01-17 16:37:26.632 ThaliTest[2112:5146895] client: found peer: 1453045045528.1507.2+89nQ==
2016-01-17 16:37:26.633 ThaliTest[2112:5147066] jxcore: connect 1453045045528.1507.2+89nQ==
2016-01-17 16:37:26.633 ThaliTest[2112:5147066] client session: connect
2016-01-17 16:37:26.633 ThaliTest[2112:5147066] client session: stateChange:0->1 1453045045528.1507.2+89nQ==
,2016-01-17 16:37:29.179 ThaliTest[2112:5147862] server session: connected
2016-01-17 16:37:29.179 ThaliTest[2112:5147862] server session: stateChange:1->2 1453045045528.1507
,2016-01-17 16:37:29.185 ThaliTest[2112:5146895] server relay: socket disconnected
2016-01-17 16:37:29.185 ThaliTest[2112:5146895] server relay: 0x1676b5d0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-17 16:37:29.247 ThaliTest[2112:5147862] server session: not connected 1453045045528.1507
,2016-01-17 16:37:29.318 ThaliTest[2112:5147875] client session: connected
,2016-01-17 16:37:29.318 ThaliTest[2112:5147875] client session: stateChange:1->2 1453045045528.1507.2+89nQ==
2016-01-17 16:37:29.322 ThaliTest[2112:5147875] client session: fireConnectCallback: 1453045045528.1507.2+89nQ==
2016-01-17 16:37:29.322 ThaliTes,t[2112:5147875] jxcore: connect: success
ok 79 Should be able to connect without error
ok 80 Port should be within range
,2016-01-17 16:37:29.323 ThaliTest[2112:5147066] jxcore: connect 1453045045528.1507.2+89nQ==
2016-01-17 16:37:29.324 ThaliTest[2112:5147066] client: already connect(ing/ed) to 1453045045528.1507.2+89nQ==
2016-01-17 16:37:29.324 ThaliTest[2112:5147066] jxc,ore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
2016-01-17 16:37:29.325 ThaliTest[2112:5147066] jxcore: disconnect
2016-01-17 16:37:29.325 ThaliTest[2112:5147066] client session: disconnectFromPeer: 1453045045528.1507.2+89nQ==
2016-01-17 16:37:29.326 ThaliTest[2112:5147066] client session: disconnect
2016-01-17 16:37:29.326 ThaliTest[2112:5147066] client session: stateChange:2->0 1453045045528.1507.2+89nQ==
,2016-01-17 16:37:29.388 ThaliTest[2112:5147066] jxcore: disconnect: success
,ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-17 16:37:29.574 ThaliTest[2112:5147066] jxcore: stopBroadcasting
2016-01-17 16:37:29.575 ThaliTest[2112:5147066] THEMultipeerSession stopping peer
2016-01-17 16:37:29.575 ThaliTest[2112:5147066] multipeer session: stop timer
2016-01-17 16:37:29.,575 ThaliTest[2112:5147066] server session: disconnect
2016-01-17 16:37:29.575 ThaliTest[2112:5147066] server session: stateChange:2->0 1453045045528.1507
2016-01-17 16:37:29.576 ThaliTest[2112:5147066] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-17 16:37:29.621 ThaliTest[2112:5147066] jxcore: startBroadcasting
,2016-01-17 16:37:29.623 ThaliTest[2112:5147066] server: starting 1453045049621.2112.ZaRMOQ==
2016-01-17 16:37:29.623 ThaliTest[2112:5147066] multipeer session: start timer: 0x16332d40
2016-01-17 16:37:29.624 ThaliTest[2112:5147066] THEMultipeerSession initialized peer 1453045049621.2112
2016-01-17 16:37:29.624 ThaliTest[2112:5147066] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-17 16:37:30.472 ThaliTest[2112:5146895] client: found peer: 1453045045528.1507.2+89nQ==
2016-01-17 16:37:30.473 ThaliTest[2112:5146895] client: found peer: 1453045044924.2112.72qDhg==
2016-01-17 16:37:30.474 ThaliTest[2112:5147066] jxcore: connec,t 1453045045528.1507.2+89nQ==
2016-01-17 16:37:30.474 ThaliTest[2112:5147066] client session: connect
2016-01-17 16:37:30.474 ThaliTest[2112:5147066] client session: stateChange:0->1 1453045045528.1507.2+89nQ==
,2016-01-17 16:37:30.482 ThaliTest[2112:5147066] jxcore: connect 1453045044924.2112.72qDhg==
2016-01-17 16:37:30.483 ThaliTest[2112:5147066] client session: connect
2016-01-17 16:37:30.483 ThaliTest[2112:5147066] client session: stateChange:0->1 1453045044924.2112.72qDhg==
,2016-01-17 16:37:30.716 ThaliTest[2112:5146895] client: lost peer: 1453045044924.2112.72qDhg==
2016-01-17 16:37:30.716 ThaliTest[2112:5146895] client session: onPeerLost: 1453045044924.2112.72qDhg==
2016-01-17 16:37:30.716 ThaliTest[2112:5146895] client session: onLinkFailure: 1453045044924.2112.72qDhg==
2016-01-17 16:37:30.716 ThaliTest[2112:5146895] client session: disconnect
2016-01-17 16:37:30.716 ThaliTest[2112:5146895] client session: stateChange:1->0 1453045044924.2112.72qDhg==
2016-01-17 16:37:,30.717 ThaliTest[2112:5146895] client session: fireConnectCallback: 1453045044924.2112.72qDhg==
2016-01-17 16:37:30.717 ThaliTest[2112:5146895] jxcore: connect: fail: Peer disconnected
2016-01-17 16:37:30.717 ThaliTest[2112:5146895] client: lost peer: 1453045045528.1507.2+89nQ==
2016-01-17 16:37:30.717 ThaliTest[2112:5146895] client session: onPeerLost: 1453045045528.1507.2+89nQ==
2016-01-17 16:37:30.717 ThaliTest[2112:5146895] client session: onLinkFailure: 1453045045528.1507.2+89nQ==
2016-01-17 16:37,:30.717 ThaliTest[2112:5146895] client session: disconnect
2016-01-17 16:37:30.718 ThaliTest[2112:5146895] client session: stateChange:1->0 1453045045528.1507.2+89nQ==
,2016-01-17 16:37:30.718 ThaliTest[2112:5146895] client session: fireConnectCallback: 1453045045528.1507.2+89nQ==
2016-01-17 16:37:30.719 ThaliTest[2112:5146895] jxcore: connect: fail: Peer disconnected
,2016-01-17 16:37:30.747 ThaliTest[2112:5146895] client: found peer: 1453045049771.1507.EQpJBg==
,2016-01-17 16:37:30.749 ThaliTest[2112:5147066] jxcore: connect 1453045049771.1507.EQpJBg==
,2016-01-17 16:37:30.751 ThaliTest[2112:5147066] client session: connect
,2016-01-17 16:37:30.751 ThaliTest[2112:5147066] client session: stateChange:0->1 1453045049771.1507.EQpJBg==
,2016-01-17 16:37:31.149 ThaliTest[2112:5146895] multipeer session: reset timer
,2016-01-17 16:37:31.149 ThaliTest[2112:5146895] multipeer session: stop timer
,2016-01-17 16:37:31.149 ThaliTest[2112:5146895] multipeer session: start timer: 0x16332d40
,2016-01-17 16:37:31.150 ThaliTest[2112:5146895] server session: connect
,2016-01-17 16:37:31.151 ThaliTest[2112:5146895] server session: stateChange:0->1 1453045049771.1507
,2016-01-17 16:37:31.159 ThaliTest[2112:5146895] server: accepting invitation 1453045049771.1507
,2016-01-17 16:37:31.724 ThaliTest[2112:5147066] jxcore: connect 1453045044924.2112.72qDhg==
2016-01-17 16:37:31.724 ThaliTest[2112:5147066] client: connect: unreachable 1453045044924.2112.72qDhg==
2016-01-17 16:37:31.724 ThaliTest[2112:5147066] jxcore: c,onnect: fail: Peer unreachable
2016-01-17 16:37:31.724 ThaliTest[2112:5147066] jxcore: connect 1453045045528.1507.2+89nQ==
2016-01-17 16:37:31.724 ThaliTest[2112:5147066] client: connect: unreachable 1453045045528.1507.2+89nQ==
2016-01-17 16:37:31.725 ThaliTest[2112:5147066] jxcore: connect: fail: Peer unreachable
,2016-01-17 16:37:33.245 ThaliTest[2112:5147869] client session: connected
2016-01-17 16:37:33.245 ThaliTest[2112:5147869] client session: stateChange:1->2 1453045049771.1507.EQpJBg==
,2016-01-17 16:37:33.274 ThaliTest[2112:5147867] client session: fireConnectCallback: 1453045049771.1507.EQpJBg==
2016-01-17 16:37:33.274 ThaliTest[2112:5147867] jxcore: connect: success
ok 84 Should be able to connect without error
,ok 85 Port should be within range
,2016-01-17 16:37:33.276 ThaliTest[2112:5147066] jxcore: disconnect
2016-01-17 16:37:33.277 ThaliTest[2112:5147066] client session: disconnectFromPeer: 1453045049771.1507.EQpJBg==
2016-01-17 16:37:33.277 ThaliTest[2112:5147066] client session: disconnect
2016-01-17 16:37:33.277 ThaliTest[2112:5147066] client session: stateChange:2->0 1453045049771.1507.EQpJBg==
,2016-01-17 16:37:33.280 ThaliTest[2112:5147066] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
2016-01-17 16:37:33.282 ThaliTest[2112:5147066] jxcore: disconnect
2016-01-17 16:37:33.282 ThaliTest[2112:5147066] jxcore: disco,nnect: fail
ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-17 16:37:33.640 ThaliTest[2112:5147867] server session: connected
2016-01-17 16:37:33.640 ThaliTest[2112:5147867] server session: stateChange:1->2 1453045049771.1507
,2016-01-17 16:37:33.699 ThaliTest[2112:5146895] server relay: socket disconnected
2016-01-17 16:37:33.700 ThaliTest[2112:5147867] server session: not connected 1453045049771.1507
2016-01-17 16:37:33.700 ThaliTest[2112:5146895] server relay: 0x14d1ce30 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,calling stopBroadcasting
,2016-01-17 16:37:33.765 ThaliTest[2112:5147066] jxcore: stopBroadcasting
2016-01-17 16:37:33.765 ThaliTest[2112:5147066] THEMultipeerSession stopping peer
2016-01-17 16:37:33.765 ThaliTest[2112:5147066] multipeer session: stop timer
2016-01-17 16:37:33.,765 ThaliTest[2112:5147066] server session: disconnect
2016-01-17 16:37:33.765 ThaliTest[2112:5147066] server session: stateChange:2->0 1453045049771.1507
2016-01-17 16:37:33.766 ThaliTest[2112:5147066] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can connect and send data
,# teardown
,echo server started on port: 61070
,2016-01-17 16:37:34.448 ThaliTest[2112:5147066] jxcore: startBroadcasting
,2016-01-17 16:37:34.450 ThaliTest[2112:5147066] server: starting 1453045054447.2112.2KXF3Q==
,2016-01-17 16:37:34.455 ThaliTest[2112:5147066] multipeer session: start timer: 0x167f5280
,2016-01-17 16:37:34.456 ThaliTest[2112:5147066] THEMultipeerSession initialized peer 1453045054447.2112
,2016-01-17 16:37:34.457 ThaliTest[2112:5147066] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error
,2016-01-17 16:37:34.805 ThaliTest[2112:5146895] client: found peer: 1453045049771.1507.EQpJBg==
,2016-01-17 16:37:34.808 ThaliTest[2112:5147066] jxcore: connect 1453045049771.1507.EQpJBg==
,2016-01-17 16:37:34.808 ThaliTest[2112:5147066] client session: connect
,2016-01-17 16:37:34.809 ThaliTest[2112:5147066] client session: stateChange:0->1 1453045049771.1507.EQpJBg==
,2016-01-17 16:37:35.674 ThaliTest[2112:5146895] multipeer session: reset timer
2016-01-17 16:37:35.674 ThaliTest[2112:5146895] multipeer session: stop timer
2016-01-17 16:37:35.674 ThaliTest[2112:5146895] multipeer session: start timer: 0x167f5280
2016-01-17 16:37:35.674 ThaliTest[2112:5146895] server session: connect
2016-01-17 16:37:35.675 ThaliTest[2112:5146895] server session: stateChange:0->1 1453045055659.1507
,2016-01-17 16:37:35.678 ThaliTest[2112:5146895] server: accepting invitation 1453045055659.1507
,2016-01-17 16:37:37.084 ThaliTest[2112:5146895] client: lost peer: 1453045049771.1507.EQpJBg==
2016-01-17 16:37:37.084 ThaliTest[2112:5146895] client session: onPeerLost: 1453045049771.1507.EQpJBg==
2016-01-17 16:37:37.084 ThaliTest[2112:5146895] client ,session: onLinkFailure: 1453045049771.1507.EQpJBg==
2016-01-17 16:37:37.084 ThaliTest[2112:5146895] client session: disconnect
2016-01-17 16:37:37.084 ThaliTest[2112:5146895] client session: stateChange:1->0 1453045049771.1507.EQpJBg==
2016-01-17 16:37:37.084 ThaliTest[2112:5146895] client session: fireConnectCallback: 1453045049771.1507.EQpJBg==
2016-01-17 16:37:37.084 ThaliTest[2112:5146895] jxcore: connect: fail: Peer disconnected
2016-01-17 16:37:37.085 ThaliTest[2112:5146895] client: found peer: 1,453045055659.1507.x6E6kw==
,2016-01-17 16:37:37.086 ThaliTest[2112:5147066] jxcore: connect 1453045055659.1507.x6E6kw==
2016-01-17 16:37:37.088 ThaliTest[2112:5147066] client session: connect
2016-01-17 16:37:37.089 ThaliTest[2112:5147066] client session: stateChange:0->1 1453045055659.1507.x6E6kw==
,2016-01-17 16:37:38.091 ThaliTest[2112:5147066] jxcore: connect 1453045049771.1507.EQpJBg==
,2016-01-17 16:37:38.092 ThaliTest[2112:5147066] client: connect: unreachable 1453045049771.1507.EQpJBg==
2016-01-17 16:37:38.092 ThaliTest[2112:5147066] jxcore: connect: fail: Peer unreachable
,2016-01-17 16:37:38.219 ThaliTest[2112:5147938] server session: connected
2016-01-17 16:37:38.219 ThaliTest[2112:5147938] server session: stateChange:1->2 1453045055659.1507
,2016-01-17 16:37:38.254 ThaliTest[2112:5146895] server relay: connected (to port: 61070)
,2016-01-17 16:37:39.144 ThaliTest[2112:5147876] server session: not connected 1453045055659.1507
,2016-01-17 16:37:40.188 ThaliTest[2112:5147876] client session: connected
,2016-01-17 16:37:40.189 ThaliTest[2112:5147876] client session: stateChange:1->2 1453045055659.1507.x6E6kw==
,2016-01-17 16:37:40.259 ThaliTest[2112:5147867] client session: fireConnectCallback: 1453045055659.1507.x6E6kw==
2016-01-17 16:37:40.259 ThaliTest[2112:5147867] jxcore: connect: success
,ok 89 Should be able to connect without error
,ok 90 Port should be within range
,2016-01-17 16:37:40.262 ThaliTest[2112:5146895] client: relay established
2016-01-17 16:37:40.262 ThaliTest[2112:5146895] client: new accepted socket: 0x16537200
,data in 14235
,data in 16425
,data in 17520
,data in 19710
,data in 42705
,data in 49275
,data in 71175
,data in 72270
,data in 73365
,data in 81030
,data in 96360
,data in 102930
,data in 104025
,data in 120450
,data in 131072
,ok 91 the test messages should be equal
,2016-01-17 16:37:40.792 ThaliTest[2112:5147066] jxcore: disconnect
2016-01-17 16:37:40.792 ThaliTest[2112:5147066] client session: disconnectFromPeer: 1453045055659.1507.x6E6kw==
2016-01-17 16:37:40.793 ThaliTest[2112:5147066] client session: disconnect
2016-01-17 16:37:40.793 ThaliTest[2112:5147066] client session: stateChange:2->0 1453045055659.1507.x6E6kw==
,2016-01-17 16:37:40.798 ThaliTest[2112:5147066] jxcore: disconnect: success
ok 92 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
# setup
,calling stopBroadcasting
,2016-01-17 16:37:41.138 ThaliTest[2112:5147066] jxcore: stopBroadcasting
2016-01-17 16:37:41.138 ThaliTest[2112:5147066] THEMultipeerSession stopping peer
2016-01-17 16:37:41.138 ThaliTest[2112:5147066] multipeer session: stop timer
2016-01-17 16:37:41.138 ThaliTest[2112:5147066] server session: disconnect
2016-01-17 16:37:41.138 ThaliTest[2112:5147066] server session: stateChange:2->0 1453045055659.1507
,2016-01-17 16:37:41.406 ThaliTest[2112:5147066] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,echo server started on port: 61077
,2016-01-17 16:37:41.749 ThaliTest[2112:5147066] jxcore: startBroadcasting
,2016-01-17 16:37:41.751 ThaliTest[2112:5147066] server: starting 1453045061749.2112.brdmwQ==
2016-01-17 16:37:41.752 ThaliTest[2112:5147066] multipeer session: start timer: 0x161c5280
2016-01-17 16:37:41.752 ThaliTest[2112:5147066] THEMultipeerSession initialized peer 1453045061749.2112
2016-01-17 16:37:41.752 ThaliTest[2112:5147066] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error
,2016-01-17 16:37:42.258 ThaliTest[2112:5146895] client: found peer: 1453045055659.1507.x6E6kw==
[{"peerIdentifier":"1453045055659.1507.x6E6kw==","peerName":"(null)","peerAvailable":true}]
,2016-01-17 16:37:42.260 ThaliTest[2112:5147066] jxcore: connect 1453045055659.1507.x6E6kw==
2016-01-17 16:37:42.260 ThaliTest[2112:5147066] client session: connect
2016-01-17 16:37:42.260 ThaliTest[2112:5147066] client session: stateChange:0->1 1453045055659.1507.x6E6kw==
,2016-01-17 16:37:42.899 ThaliTest[2112:5146895] client: lost peer: 1453045055659.1507.x6E6kw==
2016-01-17 16:37:42.899 ThaliTest[2112:5146895] client session: onPeerLost: 1453045055659.1507.x6E6kw==
2016-01-17 16:37:42.899 ThaliTest[2112:5146895] client ,session: onLinkFailure: 1453045055659.1507.x6E6kw==
2016-01-17 16:37:42.899 ThaliTest[2112:5146895] client session: disconnect
2016-01-17 16:37:42.899 ThaliTest[2112:5146895] client session: stateChange:1->0 1453045055659.1507.x6E6kw==
2016-01-17 16:37:,42.900 ThaliTest[2112:5146895] client session: fireConnectCallback: 1453045055659.1507.x6E6kw==
2016-01-17 16:37:42.900 ThaliTest[2112:5146895] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1453045055659.1507.x6E6kw==","peerName":"(null)",,"peerAvailable":false}]
,2016-01-17 16:37:42.943 ThaliTest[2112:5146895] client: found peer: 1453045062104.1507.mk1ICA==
[{"peerIdentifier":"1453045062104.1507.mk1ICA==","peerName":"(null)","peerAvailable":true}]
2016-01-17 16:37:42.944 ThaliTest[2112:5147066] jxcore: connect 14,53045062104.1507.mk1ICA==
2016-01-17 16:37:42.944 ThaliTest[2112:5147066] client session: connect
2016-01-17 16:37:42.944 ThaliTest[2112:5147066] client session: stateChange:0->1 1453045062104.1507.mk1ICA==
,2016-01-17 16:37:43.133 ThaliTest[2112:5146895] multipeer session: reset timer
2016-01-17 16:37:43.134 ThaliTest[2112:5146895] multipeer session: stop timer
2016-01-17 16:37:43.134 ThaliTest[2112:5146895] multipeer session: start timer: 0x161c5280
2016-01-17 16:37:43.134 ThaliTest[2112:5146895] server session: connect
2016-01-17 16:37:43.135 ThaliTest[2112:5146895] server session: stateChange:0->1 1453045062104.1507
2016-01-17 16:37:43.139 ThaliTest[2112:5146895] server: accepting invitation 1453045062104.1507
,2016-01-17 16:37:43.906 ThaliTest[2112:5147066] jxcore: connect 1453045055659.1507.x6E6kw==
2016-01-17 16:37:43.906 ThaliTest[2112:5147066] client: connect: unreachable 1453045055659.1507.x6E6kw==
2016-01-17 16:37:43.906 ThaliTest[2112:5147066] jxcore: connect: fail: Peer unreachable
,2016-01-17 16:37:45.807 ThaliTest[2112:5147869] server session: connected
2016-01-17 16:37:45.807 ThaliTest[2112:5147869] server session: stateChange:1->2 1453045062104.1507
,2016-01-17 16:37:45.822 ThaliTest[2112:5146895] server relay: connected (to port: 61077)
,2016-01-17 16:37:45.828 ThaliTest[2112:5147867] client session: connected
2016-01-17 16:37:45.828 ThaliTest[2112:5147867] client session: stateChange:1->2 1453045062104.1507.mk1ICA==
,2016-01-17 16:37:45.887 ThaliTest[2112:5147869] client session: fireConnectCallback: 1453045062104.1507.mk1ICA==
2016-01-17 16:37:45.888 ThaliTest[2112:5147869] jxcore: connect: success
,ok 94 Should be able to connect without error
,ok 95 Port should be within range
,ok 96 First connect should succeed
,2016-01-17 16:37:45.902 ThaliTest[2112:5146895] client: relay established
,2016-01-17 16:37:45.902 ThaliTest[2112:5146895] client: new accepted socket: 0x1624aeb0
,2016-01-17 16:37:45.950 ThaliTest[2112:5147867] server session: not connected 1453045062104.1507
,ok 97 the test messages should be equal
,ok 98 First send should succeed
,2016-01-17 16:37:46.049 ThaliTest[2112:5146895] client: socket closed
,2016-01-17 16:37:46.050 ThaliTest[2112:5146895] client relay: socket disconnected
2016-01-17 16:37:46.050 ThaliTest[2112:5146895] client relay: 0x1624aeb0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-01-17 16:37:46.050 ThaliTest[2112:5146895] client session: socket closed: 1453045062104.1507.mk1ICA==
2016-01-17 16:37:46.050 ThaliTest[2112:5146895] client session: onLinkFailure: 1453045062104.1507.mk1ICA==
2016-01-17 16:37:46.050 ThaliTest[2112:5,146895] client session: disconnect
2016-01-17 16:37:46.050 ThaliTest[2112:5146895] client session: stateChange:2->0 1453045062104.1507.mk1ICA==
,2016-01-17 16:37:46.057 ThaliTest[2112:5146895] client session: fireConnectionErrorEvent: 1453045062104.1507.mk1ICA==
,2016-01-17 16:37:46.063 ThaliTest[2112:5147066] jxcore: connect 1453045062104.1507.mk1ICA==
,2016-01-17 16:37:46.066 ThaliTest[2112:5147066] client session: connect
,2016-01-17 16:37:46.067 ThaliTest[2112:5147066] client session: stateChange:0->1 1453045062104.1507.mk1ICA==
,2016-01-17 16:37:46.345 ThaliTest[2112:5146895] multipeer session: reset timer
2016-01-17 16:37:46.345 ThaliTest[2112:5146895] multipeer session: stop timer
,2016-01-17 16:37:46.346 ThaliTest[2112:5146895] multipeer session: start timer: 0x161c5280
2016-01-17 16:37:46.346 ThaliTest[2112:5146895] server: disconnecting to refresh session (1453045062104.1507)
,2016-01-17 16:37:46.346 ThaliTest[2112:5146895] server session: disconnect
,2016-01-17 16:37:46.347 ThaliTest[2112:5146895] server session: stateChange:2->0 1453045062104.1507
,2016-01-17 16:37:46.352 ThaliTest[2112:5146895] server session: connect
,2016-01-17 16:37:46.352 ThaliTest[2112:5146895] server session: stateChange:0->1 1453045062104.1507
,2016-01-17 16:37:46.364 ThaliTest[2112:5146895] server: accepting invitation 1453045062104.1507
,2016-01-17 16:37:48.905 ThaliTest[2112:5147876] client session: connected
2016-01-17 16:37:48.905 ThaliTest[2112:5147876] client session: stateChange:1->2 1453045062104.1507.mk1ICA==
,2016-01-17 16:37:48.911 ThaliTest[2112:5147876] server session: connected
,2016-01-17 16:37:48.911 ThaliTest[2112:5147876] server session: stateChange:1->2 1453045062104.1507
,2016-01-17 16:37:48.967 ThaliTest[2112:5147867] client session: fireConnectCallback: 1453045062104.1507.mk1ICA==
2016-01-17 16:37:48.968 ThaliTest[2112:5147867] jxcore: connect: success
ok 99 Should be able to connect without error
,ok 100 Port should be within range
,ok 101 Second connect should succeed
,2016-01-17 16:37:48.973 ThaliTest[2112:5146895] server relay: connected (to port: 61077)
,2016-01-17 16:37:48.984 ThaliTest[2112:5146895] client: relay established
2016-01-17 16:37:48.984 ThaliTest[2112:5146895] client: new accepted socket: 0x16684f60
,ok 102 the test messages should be equal
ok 103 Second send should succeed
,# setup
,2016-01-17 16:37:49.059 ThaliTest[2112:5146895] client: socket closed
2016-01-17 16:37:49.059 ThaliTest[2112:5146895] client relay: socket disconnected
2016-01-17 16:37:49.059 ThaliTest[2112:5146895] client relay: 0x16684f60 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-17 16:37:49.059 ThaliTest[2112:5146895] client session: socket closed: 1453045062104.1507.mk1ICA==
2016-01-17 ,16:37:49.059 ThaliTest[2112:5146895] client session: onLinkFailure: 1453045062104.1507.mk1ICA==
2016-01-17 16:37:49.059 ThaliTest[2112:5146895] client session: disconnect
2016-01-17 16:37:49.060 ThaliTest[2112:5146895] client session: stateChange:2->0 1453045062104.1507.mk1ICA==
,2016-01-17 16:37:49.066 ThaliTest[2112:5146895] client session: fireConnectionErrorEvent: 1453045062104.1507.mk1ICA==
,2016-01-17 16:37:49.096 ThaliTest[2112:5147867] server session: not connected 1453045062104.1507
,calling stopBroadcasting
,2016-01-17 16:37:49.500 ThaliTest[2112:5147066] jxcore: stopBroadcasting
2016-01-17 16:37:49.500 ThaliTest[2112:5147066] THEMultipeerSession stopping peer
2016-01-17 16:37:49.501 ThaliTest[2112:5147066] multipeer session: stop timer
2016-01-17 16:37:49.,501 ThaliTest[2112:5147066] server session: disconnect
2016-01-17 16:37:49.501 ThaliTest[2112:5147066] server session: stateChange:2->0 1453045062104.1507
,2016-01-17 16:37:49.503 ThaliTest[2112:5147066] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/5C25A5A2-943F-4E54-88F0-7A8575921DE4/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 104 starting event should occur in right order
,2016-01-17 16:37:50.216 ThaliTest[2112:5147066] jxcore: startBroadcasting
,2016-01-17 16:37:50.218 ThaliTest[2112:5147066] server: starting wp4bNrcN9Doanl41wQLx1w.wwf/hg==
2016-01-17 16:37:50.218 ThaliTest[2112:5147066] multipeer session: start timer: 0x1624af20
2016-01-17 16:37:50.218 ThaliTest[2112:5147066] THEMultipeerSessio,n initialized peer wp4bNrcN9Doanl41wQLx1w
2016-01-17 16:37:50.218 ThaliTest[2112:5147066] jxcore: startBroadcasting: success
ok 105 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
ok 106 stopping event should occur in right order
About to call stopBroadcasting
,2016-01-17 16:37:50.221 ThaliTest[2112:5147066] jxcore: stopBroadcasting
2016-01-17 16:37:50.221 ThaliTest[2112:5147066] THEMultipeerSession stopping peer
2016-01-17 16:37:50.221 ThaliTest[2112:5147066] multipeer session: stop timer
2016-01-17 16:37:50.230 ThaliTest[2112:5147066] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
ok 107 stopped event should occur in right order
,mux server bridge listener closed
# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/5C25A5A2-943F-4E54-88F0-7A8575921DE4/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-17 16:37:52.229 ThaliTest[2112:5147066] jxcore: startBroadcasting
,2016-01-17 16:37:52.231 ThaliTest[2112:5147066] server: starting wp4bNrcN9Doanl41wQLx1w.pU/G7A==
2016-01-17 16:37:52.231 ThaliTest[2112:5147066] multipeer session: start timer: 0x166a7170
2016-01-17 16:37:52.232 ThaliTest[2112:5147066] THEMultipeerSessio,n initialized peer wp4bNrcN9Doanl41wQLx1w
,2016-01-17 16:37:52.233 ThaliTest[2112:5147066] jxcore: startBroadcasting: success
,ok 108 getDeviceIdentity should not return an error
ok 109 deviceName should not be null
Now in TRM stop
State of this._isStarted: true
About to call stopBroadcasting
2016-01-17 16:37:52.237 ThaliTest[2112:5147066] jxcore: stopBroadcasting
2016-01-17, 16:37:52.237 ThaliTest[2112:5147066] THEMultipeerSession stopping peer
2016-01-17 16:37:52.237 ThaliTest[2112:5147066] multipeer session: stop timer
2016-01-17 16:37:52.237 ThaliTest[2112:5147066] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
,mux server bridge listener closed
,# setup
,# ThaliReplicationManager replicates database
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/5C25A5A2-943F-4E54-88F0-7A8575921DE4/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-17 16:37:54.099 ThaliTest[2112:5147066] jxcore: startBroadcasting
,2016-01-17 16:37:54.101 ThaliTest[2112:5147066] server: starting wp4bNrcN9Doanl41wQLx1w.nD2stg==
,2016-01-17 16:37:54.102 ThaliTest[2112:5147066] multipeer session: start timer: 0x1674f850
,2016-01-17 16:37:54.114 ThaliTest[2112:5147066] THEMultipeerSession initialized peer wp4bNrcN9Doanl41wQLx1w
,2016-01-17 16:37:54.115 ThaliTest[2112:5147066] jxcore: startBroadcasting: success
,ok 110 getDeviceIdentity should not return an error
,ok 111 deviceName should not be null
,2016-01-17 16:37:56.528 ThaliTest[2112:5146895] client: found peer: Ax-Mk3qZgsTZvBn-cUs3fQ.0vW7Ig==
,2016-01-17 16:37:59.522 ThaliTest[2112:5147066] jxcore: connect Ax-Mk3qZgsTZvBn-cUs3fQ.0vW7Ig==
,2016-01-17 16:37:59.524 ThaliTest[2112:5147066] client session: connect
,2016-01-17 16:37:59.524 ThaliTest[2112:5147066] client session: stateChange:0->1 Ax-Mk3qZgsTZvBn-cUs3fQ.0vW7Ig==
,ok 112 Should be able to put doc without error
,ok 113 1st change of local doc should contain local id
,2016-01-17 16:38:06.009 ThaliTest[2112:5146895] multipeer session: reset timer
2016-01-17 16:38:06.009 ThaliTest[2112:5146895] multipeer session: stop timer
2016-01-17 16:38:06.009 ThaliTest[2112:5146895] multipeer session: start timer: 0x1674f850
2016-,01-17 16:38:06.009 ThaliTest[2112:5146895] server session: connect
2016-01-17 16:38:06.009 ThaliTest[2112:5146895] server session: stateChange:0->1 Ax-Mk3qZgsTZvBn-cUs3fQ
,2016-01-17 16:38:06.014 ThaliTest[2112:5146895] server: accepting invitation Ax-Mk3qZgsTZvBn-cUs3fQ
,2016-01-17 16:38:08.625 ThaliTest[2112:5148072] client session: connected
2016-01-17 16:38:08.626 ThaliTest[2112:5148072] client session: stateChange:1->2 Ax-Mk3qZgsTZvBn-cUs3fQ.0vW7Ig==
,2016-01-17 16:38:08.683 ThaliTest[2112:5148088] client session: fireConnectCallback: Ax-Mk3qZgsTZvBn-cUs3fQ.0vW7Ig==
2016-01-17 16:38:08.684 ThaliTest[2112:5148088] jxcore: connect: success
,2016-01-17 16:38:08.691 ThaliTest[2112:5146895] client: relay established
2016-01-17 16:38:08.691 ThaliTest[2112:5146895] client: new accepted socket: 0x16707a30
,client bridge: new client socket
,client bridge: new client socket
,2016-01-17 16:38:08.784 ThaliTest[2112:5148089] server session: connected
,2016-01-17 16:38:08.784 ThaliTest[2112:5148089] server session: stateChange:1->2 Ax-Mk3qZgsTZvBn-cUs3fQ
,2016-01-17 16:38:09.320 ThaliTest[2112:5146895] server relay: connected (to port: 61093)
,server bridge: new client socket
,client bridge: socket closed
client bridge: socket closed
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
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,ok 114 1st change of remote doc should contain remote id
,ok 115 Can update remote doc without error
,null
,{ ok: true,
  id: '700008ce-d154-45ce-8ba4-347126dc57d9',
  rev: '2-98a00cbf68f5d9493af97dc17fca6f2f' }
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
,ok 117 Local changes occur in strict order
,ok 118 2nd change of local doc should contain remote id
,# setup
,Now in TRM stop
,State of this._isStarted: true
About to call stopBroadcasting
,2016-01-17 16:38:29.350 ThaliTest[2112:5147066] jxcore: stopBroadcasting
,2016-01-17 16:38:29.351 ThaliTest[2112:5147066] THEMultipeerSession stopping peer
,2016-01-17 16:38:29.351 ThaliTest[2112:5147066] multipeer session: stop timer
,2016-01-17 16:38:29.352 ThaliTest[2112:5147066] client session: disconnect
,2016-01-17 16:38:29.354 ThaliTest[2112:5147066] client session: stateChange:2->0 Ax-Mk3qZgsTZvBn-cUs3fQ.0vW7Ig==
,2016-01-17 16:38:29.365 ThaliTest[2112:5147066] server session: disconnect
,2016-01-17 16:38:29.372 ThaliTest[2112:5147066] server session: stateChange:2->0 Ax-Mk3qZgsTZvBn-cUs3fQ
,2016-01-17 16:38:29.443 ThaliTest[2112:5147066] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,# #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
client bridge: socket closed
,client bridge: socket closed
,Error in mux client bridge Error: write EPIPE
,mux server bridge listener closed
,syncRetry called when not started
,client bridge: socket closed
,server bridge: socket closed
,# teardown
,ok 119 should be equal
# setup
,# #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation
,# teardown
,ok 120 should not be equal
,# setup
,# verify that Thali-specific messages are filtered correctly
,# teardown
,ok 121 irrelevant messages should be ignored
,ok 122 relevant messages should not be ignored
,ok 123 messages from this device should be ignored
,Tests Complete
,Total: 0	Passed: 0	Failed: 0
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
