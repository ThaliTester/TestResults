#### Test 5590220275263c8_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5590220275263c8/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/28F731D9-ABF8-4B6D-A707-93DCE05F2AE2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/28F731D9-ABF8-4B6D-A707-93DCE05F2AE2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5590220275263c8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5590220275263c8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54970"
,(lldb)     command script import "/tmp/28F731D9-ABF8-4B6D-A707-93DCE05F2AE2/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-13 15:31:18.873 ThaliTest[1937:4116916] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1DEAE62F-589F-4D59-88CE-CF2ECFBF7C4B/Library/Cookies/Cookies.binarycookies
,2016-01-13 15:31:19.104 ThaliTest[1937:4116916] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-13 15:31:19.104 ThaliTest[1937:4116916] Multi-tasking -> Device: YES, App: YES
,2016-01-13 15:31:19.111 ThaliTest[1937:4116916] Unlimited access to network resources
,2016-01-13 15:31:19.116 ThaliTest[1937:4116916] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-13 15:31:23.237 ThaliTest[1937:4116916] Resetting plugins due to page load.
,2016-01-13 15:31:24.669 ThaliTest[1937:4116916] Finished load of: file:///var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/index.html
,2016-01-13 15:31:24.803 ThaliTest[1937:4116916] JXcore Cordova plugin initializing
,2016-01-13 15:31:24.804 ThaliTest[1937:4117095] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-IpadAir2-1
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
ok 28 should be equal
,# setup
,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,# teardown
,ok 29 should be equal
,ok 30 should be equal
ok 31 should be equal
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
,2016-01-13 15:37:45.247 ThaliTest[1937:4117095] jxcore: startBroadcasting
,2016-01-13 15:37:45.253 ThaliTest[1937:4117095] server: starting 1452695865247.1937.U1Fu3A==
2016-01-13 15:37:45.254 ThaliTest[1937:4117095] multipeer session: start timer: 0x1651b690
,2016-01-13 15:37:45.254 ThaliTest[1937:4117095] THEMultipeerSession initialized peer 1452695865247.1937
2016-01-13 15:37:45.254 ThaliTest[1937:4117095] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
2016-01-13 15:37:45.256 ThaliTest[1937:4117095] jxcore: stopBroadcasting
2016-01-13 15:37:45.256 ThaliTest[1937:4117095] THEMultipeerSession stopping peer
2016-01-13 15:37:45.256 ThaliTest[1937:4117095] multipeer session: stop timer
2016-01-13 15:37:45.256 ThaliTest[1937:4117095] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-13 15:37:45.257 ThaliTest[1937:4117095] jxcore: startBroadcasting
,2016-01-13 15:37:45.260 ThaliTest[1937:4117095] server: starting 1452695865256.1937.cppFnw==
,2016-01-13 15:37:45.260 ThaliTest[1937:4117095] multipeer session: start timer: 0x1651b690
2016-01-13 15:37:45.262 ThaliTest[1937:4117095] THEMultipeerSession initialized peer 1452695865256.1937
2016-01-13 15:37:45.262 ThaliTest[1937:4117095] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-13 15:37:45.262 ThaliTest[1937:4117095] jxcore: stopBroadcasting
2016-01-13 15:37:45.263 ThaliTest[1937:4117095] THEMultipeerSession stopping peer
2016-01-13 1,5:37:45.263 ThaliTest[1937:4117095] multipeer session: stop timer
2016-01-13 15:37:45.263 ThaliTest[1937:4117095] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
2016-01-13 15:37:45.263 ThaliTest[1937:4117095] jxcore: startBroadcasting
,2016-01-13 15:37:45.265 ThaliTest[1937:4117095] server: starting 1452695865263.1937.fNPdgg==
2016-01-13 15:37:45.265 ThaliTest[1937:4117095] multipeer session: start timer: 0x1a0796b0
2016-01-13 15:37:45.265 ThaliTest[1937:4117095] THEMultipeerSession initialized peer 1452695865263.1937
2016-01-13 15:37:45.265 ThaliTest[1937:4117095] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2016-01-13 15:37:45.266 ThaliTest[1937:4117095] jxcore: stopBroadcasting
2,016-01-13 15:37:45.266 ThaliTest[1937:4117095] THEMultipeerSession stopping peer
2016-01-13 15:37:45.266 ThaliTest[1937:4117095] multipeer session: stop timer
2016-01-13 15:37:45.266 ThaliTest[1937:4117095] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error
2016-01-13 15:37:45.267 ThaliTest[1937:4117095] jxcore: startBroadcasting
,2016-01-13 15:37:45.270 ThaliTest[1937:4117095] server: starting 1452695865267.1937.s/+5mA==
2016-01-13 15:37:45.271 ThaliTest[1937:4117095] multipeer session: start timer: 0x1855b7c0
2016-01-13 15:37:45.271 ThaliTest[1937:4117095] THEMultipeerSession initialized peer 1452695865267.1937
2016-01-13 15:37:45.271 ThaliTest[1937:4117095] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2016-01-13 15:37:45.272 ThaliTest[1937:4117095] jxcore: stopBroadcasting
2,016-01-13 15:37:45.272 ThaliTest[1937:4117095] THEMultipeerSession stopping peer
2016-01-13 15:37:45.272 ThaliTest[1937:4117095] multipeer session: stop timer
2016-01-13 15:37:45.272 ThaliTest[1937:4117095] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
2016-01-13 15:37:45.273 ThaliTest[1937:4117095] jxcore: startBroadcasting
,2016-01-13 15:37:45.276 ThaliTest[1937:4117095] server: starting 1452695865273.1937.cx/PLg==
2016-01-13 15:37:45.276 ThaliTest[1937:4117095] multipeer session: start timer: 0x184813a0
2016-01-13 15:37:45.276 ThaliTest[1937:4117095] THEMultipeerSession in,itialized peer 1452695865273.1937
2016-01-13 15:37:45.276 ThaliTest[1937:4117095] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2016-01-13 15:37:45.277 ThaliTest[1937:4117095] jxcore: stopBroadcasting
2016-01-13 15:37:45.277 ThaliTest[1937:4117095] THEMultipeerSession stopping peer
2016-01-13 15:37:45.277 ThaliTest[1937:4117095] multipeer session: stop timer
2016-01-13 15:37:45.277 ThaliTest[1937:4117095] jxcore: stopBroadcasting: success
ok 54 Should be able to call stopBroadcasting without error
2016-01-13 15:37:45.278 ThaliTest[1937:4117095] jxcore: startBroadcasting
,2016-01-13 15:37:45.281 ThaliTest[1937:4117095] server: starting 1452695865278.1937.VijQ+w==
2016-01-13 15:37:45.281 ThaliTest[1937:4117095] multipeer session: start timer: 0x18753350
2016-01-13 15:37:45.281 ThaliTest[1937:4117095] THEMultipeerSession in,itialized peer 1452695865278.1937
2016-01-13 15:37:45.282 ThaliTest[1937:4117095] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error
2016-01-13 15:37:45.282 ThaliTest[1937:4117095] jxcore: stopBroadcasting
2016-01-13 15:37:45.282 ThaliTest[1937:4117095] THEMultipeerSession stopping peer
2016-01-13 15:37:45.282 ThaliTest[1937:4117095] multipeer session: stop timer
,2016-01-13 15:37:45.282 ThaliTest[1937:4117095] jxcore: stopBroadcasting: success
ok 56 Should be able to call stopBroadcasting without error
2016-01-13 15:37:45.284 ThaliTest[1937:4117095] jxcore: startBroadcasting
,2016-01-13 15:37:45.287 ThaliTest[1937:4117095] server: starting 1452695865284.1937.8h+mSA==
,2016-01-13 15:37:45.289 ThaliTest[1937:4117095] multipeer session: start timer: 0x1677d360
2016-01-13 15:37:45.289 ThaliTest[1937:4117095] THEMultipeerSession initialized peer 1452695865284.1937
2016-01-13 15:37:45.289 ThaliTest[1937:4117095] jxcore: startBroadcasting: success
ok 57 Should be able to call startBroadcasting without error
2016-01-13 15:37:45.290 ThaliTest[1937:4117095] jxcore: stopBroadcasting
2016-01-13 15:37:45.290 ThaliTest[1937:4117095] THEMultipeerSession stopping peer
2016-01-13 1,5:37:45.290 ThaliTest[1937:4117095] multipeer session: stop timer
2016-01-13 15:37:45.290 ThaliTest[1937:4117095] jxcore: stopBroadcasting: success
ok 58 Should be able to call stopBroadcasting without error
2016-01-13 15:37:45.291 ThaliTest[1937:4117095] jxcore: startBroadcasting
,2016-01-13 15:37:45.292 ThaliTest[1937:4117095] server: starting 1452695865290.1937.sU7V7Q==
2016-01-13 15:37:45.292 ThaliTest[1937:4117095] multipeer session: start timer: 0x167d50e0
2016-01-13 15:37:45.292 ThaliTest[1937:4117095] THEMultipeerSession initialized peer 1452695865290.1937
2016-01-13 15:37:45.292 ThaliTest[1937:4117095] jxcore: startBroadcasting: success
ok 59 Should be able to call startBroadcasting without error
2016-01-13 15:37:45.293 ThaliTest[1937:4117095] jxcore: stopBroadcasting
2,016-01-13 15:37:45.293 ThaliTest[1937:4117095] THEMultipeerSession stopping peer
2016-01-13 15:37:45.293 ThaliTest[1937:4117095] multipeer session: stop timer
2016-01-13 15:37:45.293 ThaliTest[1937:4117095] jxcore: stopBroadcasting: success
ok 60 Should be able to call stopBroadcasting without error
,2016-01-13 15:37:45.294 ThaliTest[1937:4117095] jxcore: startBroadcasting
,2016-01-13 15:37:45.297 ThaliTest[1937:4117095] server: starting 1452695865294.1937.Osb35w==
2016-01-13 15:37:45.297 ThaliTest[1937:4117095] multipeer session: start timer: 0x1822ad80
2016-01-13 15:37:45.298 ThaliTest[1937:4117095] THEMultipeerSession initialized peer 1452695865294.1937
2016-01-13 15:37:45.298 ThaliTest[1937:4117095] jxcore: startBroadcasting: success
ok 61 Should be able to call startBroadcasting without error
2016-01-13 15:37:45.298 ThaliTest[1937:4117095] jxcore: stopBroadcasting
2016-01-13 15:37:45.298 ThaliTest[1937:4117095] THEMultipeerSession stopping peer
,2016-01-13 15:37:45.298 ThaliTest[1937:4117095] multipeer session: stop timer
2016-01-13 15:37:45.301 ThaliTest[1937:4117095] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
2016-01-13 15:37:45.302 ThaliTest[1937:4117095] jxcore: startBroadcasting
,2016-01-13 15:37:45.304 ThaliTest[1937:4117095] server: starting 1452695865301.1937.WeAhZg==
2016-01-13 15:37:45.304 ThaliTest[1937:4117095] multipeer session: start timer: 0x187a90f0
2016-01-13 15:37:45.305 ThaliTest[1937:4117095] THEMultipeerSession in,itialized peer 1452695865301.1937
2016-01-13 15:37:45.305 ThaliTest[1937:4117095] jxcore: startBroadcasting: success
ok 63 Should be able to call startBroadcasting without error
2016-01-13 15:37:45.305 ThaliTest[1937:4117095] jxcore: stopBroadcasting
2016-01-13 15:37:45.305 ThaliTest[1937:4117095] THEMultipeerSession stopping peer
2016-01-13 15:37:45.305 ThaliTest[1937:4117095] multipeer session: stop timer
2016-01-13 15:37:45.306 ThaliTest[1937:4117095] jxcore: stopBroadcasting: success
ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-13 15:37:48.977 ThaliTest[1937:4117095] jxcore: startBroadcasting
,2016-01-13 15:37:48.978 ThaliTest[1937:4117095] server: starting 1452695868976.1937.ucU4rg==
2016-01-13 15:37:48.978 ThaliTest[1937:4117095] multipeer session: start timer: 0x1862a010
2016-01-13 15:37:48.978 ThaliTest[1937:4117095] THEMultipeerSession initialized peer 1452695868976.1937
2016-01-13 15:37:48.978 ThaliTest[1937:4117095] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-13 15:37:48.979 ThaliTest[1937:4117095] jxcore: startBroadcasting
2016-01-13 15:37:48.979 ThaliTest[1937:4117095] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
2016-01-13 15:37:48.980 ThaliTest[1937:4117095] jxcore: stopBroadcasting
2016-01-13 15:37:48.980 ThaliTest[1937:4117095] THEMultipeerSession stopping peer
2016-01-13 15:37:48.980 ThaliTest[1937:4117095] multipee,r session: stop timer
2016-01-13 15:37:48.980 ThaliTest[1937:4117095] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-13 15:37:50.326 ThaliTest[1937:4117095] jxcore: startBroadcasting
,2016-01-13 15:37:50.327 ThaliTest[1937:4117095] server: starting 1452695870325.1937.ZibnRw==
2016-01-13 15:37:50.327 ThaliTest[1937:4117095] multipeer session: start timer: 0x1827f600
2016-01-13 15:37:50.327 ThaliTest[1937:4117095] THEMultipeerSession initialized peer 1452695870325.1937
,2016-01-13 15:37:50.327 ThaliTest[1937:4117095] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-13 15:37:50.328 ThaliTest[1937:4117095] jxcore: connect foobar
2016-01-13 15:37:50.328 ThaliTest[1937:4117095] client: unknown peer foobar
2016-01-13 15:37:50.328 ThaliTest[1937:4117095] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
,2016-01-13 15:37:50.329 ThaliTest[1937:4117095] jxcore: stopBroadcasting
2016-01-13 15:37:50.329 ThaliTest[1937:4117095] THEMultipeerSession stopping peer
2016-01-13 15:37:50.329 ThaliTest[1937:4117095] multipeer session: stop timer
2016-01-13 15:37:50.,330 ThaliTest[1937:4117095] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-13 15:37:52.018 ThaliTest[1937:4117095] jxcore: startBroadcasting
,2016-01-13 15:37:52.019 ThaliTest[1937:4117095] server: starting 1452695872018.1937.Ea6lQg==
2016-01-13 15:37:52.019 ThaliTest[1937:4117095] multipeer session: start timer: 0x182a3630
2016-01-13 15:37:52.019 ThaliTest[1937:4117095] THEMultipeerSession initialized peer 1452695872018.1937
,2016-01-13 15:37:52.021 ThaliTest[1937:4117095] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-13 15:37:52.022 ThaliTest[1937:4117095] jxcore: disconnect
2016-01-13 15:37:52.022 ThaliTest[1937:4117095] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 
,2016-01-13 15:37:52.023 ThaliTest[1937:4117095] jxcore: stopBroadcasting
,2016-01-13 15:37:52.023 ThaliTest[1937:4117095] THEMultipeerSession stopping peer
2016-01-13 15:37:52.023 ThaliTest[1937:4117095] multipeer session: stop timer
,2016-01-13 15:37:52.023 ThaliTest[1937:4117095] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-13 15:37:53.445 ThaliTest[1937:4117095] jxcore: startBroadcasting
,2016-01-13 15:37:53.446 ThaliTest[1937:4117095] server: starting 1452695873445.1937.9y2Uag==
2016-01-13 15:37:53.447 ThaliTest[1937:4117095] multipeer session: start timer: 0x18302790
2016-01-13 15:37:53.447 ThaliTest[1937:4117095] THEMultipeerSession initialized peer 1452695873445.1937
2016-01-13 15:37:53.447 ThaliTest[1937:4117095] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-13 15:37:54.696 ThaliTest[1937:4116916] client: found peer: 1452695872259.1869.zesqHQ==
2016-01-13 15:37:54.697 ThaliTest[1937:4117095] jxcore: connect 1452695872259.1869.zesqHQ==
2016-01-13 15:37:54.697 ThaliTest[1937:4117095] client session: connect
2016-01-13 15:37:54.697 ThaliTest[1937:4117095] client session: stateChange:0->1 1452695872259.1869.zesqHQ==
,2016-01-13 15:37:55.000 ThaliTest[1937:4116916] multipeer session: reset timer
2016-01-13 15:37:55.000 ThaliTest[1937:4116916] multipeer session: stop timer
2016-01-13 15:37:55.000 ThaliTest[1937:4116916] multipeer session: start timer: 0x18302790
2016-01-13 15:37:55.000 ThaliTest[1937:4116916] server session: connect
2016-01-13 15:37:55.000 ThaliTest[1937:4116916] server session: stateChange:0->1 1452695872259.1869
2016-01-13 15:37:55.002 ThaliTest[1937:4116916] server: accepting invitation 1452695872259.1869
,2016-01-13 15:37:58.895 ThaliTest[1937:4117761] client session: connected
2016-01-13 15:37:58.895 ThaliTest[1937:4117761] client session: stateChange:1->2 1452695872259.1869.zesqHQ==
,2016-01-13 15:37:58.933 ThaliTest[1937:4117784] client session: fireConnectCallback: 1452695872259.1869.zesqHQ==
2016-01-13 15:37:58.933 ThaliTest[1937:4117784] jxcore: connect: success
ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2016-01-13 15:37:58.935 ThaliTest[1937:4117095] jxcore: disconnect
2016-01-13 15:37:58.935 ThaliTest[1937:4117095] client session: disconnectFromPeer: 1452695872259.1869.zesqHQ==
2016-01-13 15:37:58.935 ThaliTest[1937:4117095] client session: disconnect
2016-01-13 15:37:58.935 ThaliTest[1937:4117095] client session: stateChange:2->0 1452695872259.1869.zesqHQ==
,2016-01-13 15:37:58.938 ThaliTest[1937:4117095] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-13 15:37:58.954 ThaliTest[1937:4117760] server session: connected
,2016-01-13 15:37:58.954 ThaliTest[1937:4117760] server session: stateChange:1->2 1452695872259.1869
,2016-01-13 15:37:59.011 ThaliTest[1937:4116916] server relay: socket disconnected
2016-01-13 15:37:59.011 ThaliTest[1937:4116916] server relay: 0x16755e00 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-13 15:37:59.013 ThaliTest[1937:4117760] server session: not connected 1452695872259.1869
,calling stopBroadcasting
,2016-01-13 15:37:59.278 ThaliTest[1937:4117095] jxcore: stopBroadcasting
2016-01-13 15:37:59.278 ThaliTest[1937:4117095] THEMultipeerSession stopping peer
2016-01-13 15:37:59.278 ThaliTest[1937:4117095] multipeer session: stop timer
2016-01-13 15:37:59.279 ThaliTest[1937:4117095] server session: disconnect
2016-01-13 15:37:59.279 ThaliTest[1937:4117095] server session: stateChange:2->0 1452695872259.1869
2016-01-13 15:37:59.279 ThaliTest[1937:4117095] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-13 15:38:00.833 ThaliTest[1937:4117095] jxcore: startBroadcasting
,2016-01-13 15:38:00.834 ThaliTest[1937:4117095] server: starting 1452695880833.1937.bzvYvA==
,2016-01-13 15:38:00.835 ThaliTest[1937:4117095] multipeer session: start timer: 0x18216fd0
2016-01-13 15:38:00.835 ThaliTest[1937:4117095] THEMultipeerSession initialized peer 1452695880833.1937
2016-01-13 15:38:00.835 ThaliTest[1937:4117095] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-13 15:38:02.028 ThaliTest[1937:4116916] client: found peer: 1452695879675.1869.eHGJAQ==
,2016-01-13 15:38:02.029 ThaliTest[1937:4117095] jxcore: connect 1452695879675.1869.eHGJAQ==
,2016-01-13 15:38:02.031 ThaliTest[1937:4117095] client session: connect
2016-01-13 15:38:02.031 ThaliTest[1937:4117095] client session: stateChange:0->1 1452695879675.1869.eHGJAQ==
,2016-01-13 15:38:02.041 ThaliTest[1937:4116916] multipeer session: reset timer
2016-01-13 15:38:02.041 ThaliTest[1937:4116916] multipeer session: stop timer
2016-01-13 15:38:02.041 ThaliTest[1937:4116916] multipeer session: start timer: 0x18216fd0
2016-01-13 15:38:02.041 ThaliTest[1937:4116916] server session: connect
2016-01-13 15:38:02.041 ThaliTest[1937:4116916] server session: stateChange:0->1 1452695879675.1869
2016-01-13 15:38:02.043 ThaliTest[1937:4116916] server: accepting invitation 1452695879675.1869
,2016-01-13 15:38:05.743 ThaliTest[1937:4117782] client session: connected
2016-01-13 15:38:05.743 ThaliTest[1937:4117782] client session: stateChange:1->2 1452695879675.1869.eHGJAQ==
,2016-01-13 15:38:05.768 ThaliTest[1937:4117760] client session: fireConnectCallback: 1452695879675.1869.eHGJAQ==
2016-01-13 15:38:05.768 ThaliTest[1937:4117760] jxcore: connect: success
ok 79 Should be able to connect without error
,ok 80 Port should be within range
,2016-01-13 15:38:05.770 ThaliTest[1937:4117095] jxcore: connect 1452695879675.1869.eHGJAQ==
2016-01-13 15:38:05.770 ThaliTest[1937:4117095] client: already connect(ing/ed) to 1452695879675.1869.eHGJAQ==
2016-01-13 15:38:05.770 ThaliTest[1937:4117095] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
2016-01-13 15:38:05.771 ThaliTest[1937:4117095] jxcore: disconnect
,2016-01-13 15:38:05.771 ThaliTest[1937:4117095] client session: disconnectFromPeer: 1452695879675.1869.eHGJAQ==
,2016-01-13 15:38:05.771 ThaliTest[1937:4117095] client session: disconnect
2016-01-13 15:38:05.771 ThaliTest[1937:4117095] client session: stateChange:2->0 1452695879675.1869.eHGJAQ==
,2016-01-13 15:38:05.775 ThaliTest[1937:4117095] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-13 15:38:05.904 ThaliTest[1937:4117760] server session: connected
2016-01-13 15:38:05.904 ThaliTest[1937:4117760] server session: stateChange:1->2 1452695879675.1869
,2016-01-13 15:38:05.963 ThaliTest[1937:4116916] server relay: socket disconnected
2016-01-13 15:38:05.963 ThaliTest[1937:4116916] server relay: 0x16613b30 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-13 15:38:05.966 ThaliTest[1937:4117760] server session: not connected 1452695879675.1869
,calling stopBroadcasting
,2016-01-13 15:38:07.597 ThaliTest[1937:4117095] jxcore: stopBroadcasting
2016-01-13 15:38:07.597 ThaliTest[1937:4117095] THEMultipeerSession stopping peer
2016-01-13 15:38:07.597 ThaliTest[1937:4117095] multipeer session: stop timer
2016-01-13 15:38:07.598 ThaliTest[1937:4117095] server session: disconnect
2016-01-13 15:38:07.598 ThaliTest[1937:4117095] server session: stateChange:2->0 1452695879675.1869
,2016-01-13 15:38:07.601 ThaliTest[1937:4117095] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-13 15:38:09.138 ThaliTest[1937:4117095] jxcore: startBroadcasting
,2016-01-13 15:38:09.139 ThaliTest[1937:4117095] server: starting 1452695889138.1937.jCak2w==
,2016-01-13 15:38:09.139 ThaliTest[1937:4117095] multipeer session: start timer: 0x18265b20
2016-01-13 15:38:09.140 ThaliTest[1937:4117095] THEMultipeerSession initialized peer 1452695889138.1937
,2016-01-13 15:38:09.140 ThaliTest[1937:4117095] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error
,2016-01-13 15:38:10.410 ThaliTest[1937:4116916] client: found peer: 1452695887956.1869.qlJofQ==
,2016-01-13 15:38:10.410 ThaliTest[1937:4117095] jxcore: connect 1452695887956.1869.qlJofQ==
2016-01-13 15:38:10.411 ThaliTest[1937:4117095] client session: connect
2016-01-13 15:38:10.411 ThaliTest[1937:4117095] client session: stateChange:0->1 1452695887956.1869.qlJofQ==
,2016-01-13 15:38:10.444 ThaliTest[1937:4116916] multipeer session: reset timer
,2016-01-13 15:38:10.444 ThaliTest[1937:4116916] multipeer session: stop timer
2016-01-13 15:38:10.444 ThaliTest[1937:4116916] multipeer session: start timer: 0x18265b20
2016-01-13 15:38:10.444 ThaliTest[1937:4116916] server session: connect
,2016-01-13 15:38:10.444 ThaliTest[1937:4116916] server session: stateChange:0->1 1452695887956.1869
,2016-01-13 15:38:10.446 ThaliTest[1937:4116916] server: accepting invitation 1452695887956.1869
,2016-01-13 15:38:14.280 ThaliTest[1937:4117782] client session: connected
2016-01-13 15:38:14.280 ThaliTest[1937:4117782] client session: stateChange:1->2 1452695887956.1869.qlJofQ==
2016-01-13 15:38:14.281 ThaliTest[1937:4117782] client session: fireConnectCallback: 1452695887956.1869.qlJofQ==
2016-01-13 15:38:14.281 ThaliTest[1937:4117782] jxcore: connect: success
,ok 84 Should be able to connect without error
ok 85 Port should be within range
,2016-01-13 15:38:14.283 ThaliTest[1937:4117095] jxcore: disconnect
2016-01-13 15:38:14.283 ThaliTest[1937:4117095] client session: disconnectFromPeer: 1452695887956.1869.qlJofQ==
2016-01-13 15:38:14.283 ThaliTest[1937:4117095] client session: disconnect,
2016-01-13 15:38:14.283 ThaliTest[1937:4117095] client session: stateChange:2->0 1452695887956.1869.qlJofQ==
,2016-01-13 15:38:14.349 ThaliTest[1937:4117095] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error
,2016-01-13 15:38:14.350 ThaliTest[1937:4117095] jxcore: disconnect
2016-01-13 15:38:14.350 ThaliTest[1937:4117095] jxcore: disconnect: fail
ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,2016-01-13 15:38:14.353 ThaliTest[1937:4117761] server session: connected
2016-01-13 15:38:14.354 ThaliTest[1937:4117761] server session: stateChange:1->2 1452695887956.1869
,2016-01-13 15:38:14.355 ThaliTest[1937:4116916] server relay: socket disconnected
2016-01-13 15:38:14.356 ThaliTest[1937:4116916] server relay: 0x16755d90 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,# setup
,2016-01-13 15:38:14.376 ThaliTest[1937:4117747] server session: not connected 1452695887956.1869
,calling stopBroadcasting
2016-01-13 15:38:14.488 ThaliTest[1937:4117095] jxcore: stopBroadcasting
2016-01-13 15:38:14.488 ThaliTest[1937:4117095] THEMultipeerSession stopping peer
,2016-01-13 15:38:14.488 ThaliTest[1937:4117095] multipeer session: stop timer
,2016-01-13 15:38:14.488 ThaliTest[1937:4117095] server session: disconnect
2016-01-13 15:38:14.489 ThaliTest[1937:4117095] server session: stateChange:2->0 1452695887956.1869
,2016-01-13 15:38:14.489 ThaliTest[1937:4117095] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can connect and send data
,# teardown
,2016-01-13 15:38:16.061 ThaliTest[1937:4117095] jxcore: startBroadcasting
,2016-01-13 15:38:16.063 ThaliTest[1937:4117095] server: starting 1452695896061.1937.ws+hIg==
2016-01-13 15:38:16.063 ThaliTest[1937:4117095] multipeer session: start timer: 0x18653890
2016-01-13 15:38:16.063 ThaliTest[1937:4117095] THEMultipeerSession in,itialized peer 1452695896061.1937
2016-01-13 15:38:16.063 ThaliTest[1937:4117095] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
echo server started
,2016-01-13 15:38:17.361 ThaliTest[1937:4116916] multipeer session: reset timer
2016-01-13 15:38:17.362 ThaliTest[1937:4116916] multipeer session: stop timer
2016-01-13 15:38:17.362 ThaliTest[1937:4116916] multipeer session: start timer: 0x18653890
2016-01-13 15:38:17.362 ThaliTest[1937:4116916] server session: connect
2016-01-13 15:38:17.362 ThaliTest[1937:4116916] server session: stateChange:0->1 1452695895159.1869
2016-01-13 15:38:17.364 ThaliTest[1937:4116916] server: accepting invitation 1452695895159.1869
,2016-01-13 15:38:17.368 ThaliTest[1937:4116916] client: found peer: 1452695895159.1869.zT4upg==
2016-01-13 15:38:17.368 ThaliTest[1937:4117095] jxcore: connect 1452695895159.1869.zT4upg==
2016-01-13 15:38:17.368 ThaliTest[1937:4117095] client session: connect
2016-01-13 15:38:17.368 ThaliTest[1937:4117095] client session: stateChange:0->1 1452695895159.1869.zT4upg==
,2016-01-13 15:38:20.899 ThaliTest[1937:4117761] server session: connected
2016-01-13 15:38:20.899 ThaliTest[1937:4117761] server session: stateChange:1->2 1452695895159.1869
,2016-01-13 15:38:20.902 ThaliTest[1937:4116916] server relay: connected (to port: 5001)
,2016-01-13 15:38:21.166 ThaliTest[1937:4117784] client session: connected
2016-01-13 15:38:21.166 ThaliTest[1937:4117784] client session: stateChange:1->2 1452695895159.1869.zT4upg==
,2016-01-13 15:38:21.167 ThaliTest[1937:4117784] client session: fireConnectCallback: 1452695895159.1869.zT4upg==
2016-01-13 15:38:21.167 ThaliTest[1937:4117784] jxcore: connect: success
,ok 89 Should be able to connect without error
,ok 90 Port should be within range
,2016-01-13 15:38:21.170 ThaliTest[1937:4116916] client: relay established
2016-01-13 15:38:21.170 ThaliTest[1937:4116916] client: new accepted socket: 0x1823d230
,2016-01-13 15:38:21.234 ThaliTest[1937:4117784] server session: not connected 1452695895159.1869
,data in 1095
,data in 13140
,data in 14235
,data in 21900
,data in 25114
,data in 43800
,data in 62415
,data in 74460
,data in 82125
,data in 89790
,data in 91980
,data in 111619
,data in 131072
,ok 91 the test messages should be equal
,2016-01-13 15:38:21.503 ThaliTest[1937:4117095] jxcore: disconnect
,2016-01-13 15:38:21.503 ThaliTest[1937:4117095] client session: disconnectFromPeer: 1452695895159.1869.zT4upg==
2016-01-13 15:38:21.503 ThaliTest[1937:4117095] client session: disconnect
2016-01-13 15:38:21.503 ThaliTest[1937:4117095] client session: stateChange:2->0 1452695895159.1869.zT4upg==
,2016-01-13 15:38:21.564 ThaliTest[1937:4117095] jxcore: disconnect: success
,ok 92 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
2016-01-13 15:38:21.830 ThaliTest[1937:4117095] jxcore: stopBroadcasting
2016-01-13 15:38:21.830 ThaliTest[1937:4117095] THEMultipeerSession stopping peer
2016-01-13 15:38:21.830 ThaliTest[1937:4117095] multipeer session: stop timer
,2016-01-13 15:38:21.831 ThaliTest[1937:4117095] server session: disconnect
2016-01-13 15:38:21.831 ThaliTest[1937:4117095] server session: stateChange:2->0 1452695895159.1869
,2016-01-13 15:38:21.834 ThaliTest[1937:4117095] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,2016-01-13 15:38:22.879 ThaliTest[1937:4117095] jxcore: startBroadcasting
,2016-01-13 15:38:22.880 ThaliTest[1937:4117095] server: starting 1452695902879.1937.NZLWVA==
2016-01-13 15:38:22.881 ThaliTest[1937:4117095] multipeer session: start timer: 0x184f73d0
2016-01-13 15:38:22.881 ThaliTest[1937:4117095] THEMultipeerSession in,itialized peer 1452695902879.1937
2016-01-13 15:38:22.881 ThaliTest[1937:4117095] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error
,2016-01-13 15:38:22.883 ThaliTest[1937:4117095] Error!: listen EADDRINUSE
Stack:[{"_fileName":"net.js","_functionName":"errnoException","_lineNumber":"835","_columnNumber":"11","_msg":"    at errnoException@net.js:835:11"},{"_fileName":"net.js","_function,Name":"Server.prototype._listen2","_lineNumber":"974","_columnNumber":"14","_msg":"    at Server.prototype._listen2@net.js:974:14"},{"_fileName":"net.js","_functionName":"listen","_lineNumber":"995","_columnNumber":"5","_msg":"    at listen@net.js:995:5"},{"_fileName":"net.js","_functionName":"Server.prototype.listen","_lineNumber":"1068","_columnNumber":"5","_msg":"    at Server.prototype.listen@net.js:1068:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC,22CB/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"","_lineNumber":"241","_columnNumber":"3","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/bv_te,sts/testThaliNativeLayer.js:241:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"declareTest/</<","_lineNumber":"78","_columnNumber":"7","_,msg":"    at declareTest/</<@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/lib/thali-tape.js:78:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CD,B6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"on","_lineNumber":"63","_columnNumber":"5","_msg":"    at on@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC,8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:63:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules,/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socke,t.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"263","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/j,xcore/node_modules/socket.io-client/lib/socket.js:263:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.pro,totype.onpacket","_lineNumber":"221","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:22,1:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_,columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/pri,vate/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":,"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/v,ar/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"333","_columnNumber":"3","_msg":"    at Manager,.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/EC2474,68-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Cont,ainers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B,0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/pr,ivate/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Conta,iners/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.js","_functionName":"Decoder.prototype.add","_lineNumber":"247","_columnNumber":"7","_msg":"    at Deco,der.prototype.add@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.js:247:7"},{"_fileName":"/private/var/mobile/Containers/Bund,le/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondata","_lineNumber":"323","_columnNumber":"3","_msg":"    at Manager.prototype.ondata@/private/v,ar/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:323:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/,ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore,/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bund,le/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/EC24746,8-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onPacket","_lineNumber":"441","_columnNumber":"9","_msg":"    at Socket.prototype.onPacket@/,private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:441:9"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application,/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.setTransport/<","_lineNumber":"258","_columnNumber":"5","_msg":"    at Socket.protot,ype.setTransport/<@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:258:5"},{"_fileName":"/private/var/mobile/Container,s/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNum,ber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.,js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js","_functionName":"Transport.prototype.onPa,cket","_lineNumber":"143","_columnNumber":"3","_msg":"    at Transport.prototype.onPacket@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-c,lient/lib/transport.js:143:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js","_functionName":"Tr,ansport.prototype.onData","_lineNumber":"135","_columnNumber":"3","_msg":"    at Transport.prototype.onData@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_m,odules/engine.io-client/lib/transport.js:135:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transports/websoc,ket.js","_functionName":"WS.prototype.addEventListeners/this.ws.onmessage","_lineNumber":"127","_columnNumber":"5","_msg":"    at WS.prototype.addEventListeners/this.ws.onmessage@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB,6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transports/websocket.js:127:5"}]
Uncaught Exception: Error: listen EADDRINUSE
,[ { _fileName: 'net.js',
    _functionName: 'errnoException',
    _lineNumber: '835',
    _columnNumber: '11',
    _msg: '    at errnoException@net.js:835:11' },
  { _fileName: 'net.js',
    _functionName: 'Server.prototype._listen2',
    _lineNumbe,r: '974',
    _columnNumber: '14',
    _msg: '    at Server.prototype._listen2@net.js:974:14' },
  { _fileName: 'net.js',
    _functionName: 'listen',
    _lineNumber: '995',
    _columnNumber: '5',
    _msg: '    at listen@net.js:995:5' },
  { _fi,leName: 'net.js',
    _functionName: 'Server.prototype.listen',
    _lineNumber: '1068',
    _columnNumber: '5',
    _msg: '    at Server.prototype.listen@net.js:1068:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/EC247468-06F,A-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: '',
    _lineNumber: '241',
    _columnNumber: '3',
    _msg: '    at @/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB,6B0FC22CB/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:241:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/lib/thali-tape.js',
    _functionName: 'declareT,est/</<',
    _lineNumber: '78',
    _columnNumber: '7',
    _msg: '    at declareTest/</<@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/lib/thali-tape.js:78:7' },
  { _fileName: '/priva,te/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'on',
    _lineNumber: '63',
    _columnNumber: '5',
  ,  _msg: '    at on@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:63:5' },
  { _fileName: '/private/var/mobile/Container,s/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '131',
    _columnNumber: '7',
    ,_msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7' },
  { _fileName: '/private/v,ar/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.onevent',
    _lineNumber: '263',
    _columnNumber: '5',
    _msg:, '    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/A,pplication/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.onpacket',
    _lineNumber: '221',
    _columnNumber: '7',
    _msg: '    at Socket.prototype.on,packet@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-48,05-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21',
    _columnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mo,bile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4,805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '131',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit,@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Applicat,ion/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js',
    _functionName: 'Manager.prototype.ondecoded',
    _lineNumber: '333',
    _columnNumber: '3',
    _msg: '    at Manager.prototype.ondec,oded@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-480,5-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21',
    _columnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mob,ile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-48,05-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '134',
    _columnNumber: '7',
    _msg: ',    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:7' },
  ,{ _fileName: '/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.js',
    _functionName: 'Decoder.prototype.add',
    _lineNumb,er: '247',
    _columnNumber: '7',
    _msg: '    at Decoder.prototype.add@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.j,s:247:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js',
    _functionName: 'Manager.prototype.ondata',
    _lineNumber: '3,23',
    _columnNumber: '3',
    _msg: '    at Manager.prototype.ondata@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:323:3' },
  { _fileName:, '/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21',
    _col,umnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
  { _fileName,: '/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.,emit',
    _lineNumber: '134',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/en,gine.io-client/node_modules/component-emitter/index.js:134:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.onPacket',
    _lineNumber: '441',
    _columnNumber: '9',
    _msg: '    at Socket.prototype.onPacket@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.a,pp/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:441:9' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client,/node_modules/engine.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.setTransport/<',
    _lineNumber: '258',
    _columnNumber: '5',
    _msg: '    at Socket.prototype.setTransport/<@/private/var/mobile/Containers/Bundle/Application/EC2,47468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:258:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest,.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '134',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@,/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js',
    _functionName: 'Transport.prototype.onPacket',
    _lineNumber: '143',
    ,_columnNumber: '3',
    _msg: '    at Transport.prototype.onPacket@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js:143:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js',
    _functionName: 'Transport.protot,ype.onData',
    _lineNumber: '135',
    _columnNumber: '3',
    _msg: '    at Transport.prototype.onData@/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_,modules/engine.io-client/lib/transport.js:135:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/EC247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transports/,websocket.js',
    _functionName: 'WS.prototype.addEventListeners/this.ws.onmessage',
    _lineNumber: '127',
    _columnNumber: '5',
    _msg: '    at WS.prototype.addEventListeners/this.ws.onmessage@/private/var/mobile/Containers/Bundle/Application/E,C247468-06FA-4805-AC8F-CDB6B0FC22CB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transports/websocket.js:127:5' },
  toString: [Function] ]
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
