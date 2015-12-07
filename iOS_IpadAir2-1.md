#### Test 5065027860d2bae_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027860d2bae/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/84B7EB9C-4557-48C1-BC71-14AE775BA71E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/84B7EB9C-4557-48C1-BC71-14AE775BA71E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027860d2bae/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027860d2bae/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FF01275C-18A2-4BDF-BA14-1E2528A9D071/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50338"
,(lldb)     command script import "/tmp/84B7EB9C-4557-48C1-BC71-14AE775BA71E/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-07 18:47:03.420 ThaliTest[383:160504] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3E9960A1-0E1E-43AE-BD1F-927F296E19F1/Library/Cookies/Cookies.binarycookies
,2015-12-07 18:47:03.433 ThaliTest[383:160504] <CATransformLayer: 0x17e66e10> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-07 18:47:03.434 ThaliTest[383:160504] <CATransformLayer: 0x17e6ab90> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-07 18:47:03.434 ThaliTest[383:160504] <CATransformLayer: 0x17e6bd00> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-07 18:47:03.724 ThaliTest[383:160504] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-07 18:47:03.725 ThaliTest[383:160504] Multi-tasking -> Device: YES, App: YES
,2015-12-07 18:47:03.733 ThaliTest[383:160504] Unlimited access to network resources
,2015-12-07 18:47:03.739 ThaliTest[383:160504] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 18:47:12.490 ThaliTest[383:160504] Resetting plugins due to page load.
,2015-12-07 18:47:15.588 ThaliTest[383:160504] Finished load of: file:///var/mobile/Containers/Bundle/Application/FF01275C-18A2-4BDF-BA14-1E2528A9D071/ThaliTest.app/www/index.html
,2015-12-07 18:47:15.729 ThaliTest[383:160504] JXcore Cordova plugin initializing
,2015-12-07 18:47:15.730 ThaliTest[383:160759] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
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
,ok 44 should be equal
,# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2015-12-07 18:47:37.868 ThaliTest[383:160759] jxcore: startBroadcasting
,2015-12-07 18:47:38.153 ThaliTest[383:160759] server: starting 1449510457867.383.St8nTw==
,2015-12-07 18:47:38.154 ThaliTest[383:160759] multipeer session: start timer: 0x1b1f8ef0
2015-12-07 18:47:38.155 ThaliTest[383:160759] THEMultipeerSession initialized peer 1449510457867.383
2015-12-07 18:47:38.156 ThaliTest[383:160759] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
,2015-12-07 18:47:38.166 ThaliTest[383:160759] jxcore: stopBroadcasting
,2015-12-07 18:47:38.166 ThaliTest[383:160759] THEMultipeerSession stopping peer
,2015-12-07 18:47:38.167 ThaliTest[383:160759] multipeer session: stop timer
,2015-12-07 18:47:38.170 ThaliTest[383:160759] jxcore: stopBroadcasting: success
,ok 46 Should be able to call stopBroadcasting without error
,2015-12-07 18:47:38.176 ThaliTest[383:160759] jxcore: startBroadcasting
,2015-12-07 18:47:38.180 ThaliTest[383:160759] server: starting 1449510458176.383.q7f6xA==
,2015-12-07 18:47:38.182 ThaliTest[383:160759] multipeer session: start timer: 0x19be9d90
,2015-12-07 18:47:38.190 ThaliTest[383:160759] THEMultipeerSession initialized peer 1449510458176.383
,2015-12-07 18:47:38.192 ThaliTest[383:160759] jxcore: startBroadcasting: success
,ok 47 Should be able to call startBroadcasting without error
,2015-12-07 18:47:38.197 ThaliTest[383:160759] jxcore: stopBroadcasting
,2015-12-07 18:47:38.197 ThaliTest[383:160759] THEMultipeerSession stopping peer
,2015-12-07 18:47:38.198 ThaliTest[383:160759] multipeer session: stop timer
,2015-12-07 18:47:38.200 ThaliTest[383:160759] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
,2015-12-07 18:47:38.205 ThaliTest[383:160759] jxcore: startBroadcasting
,2015-12-07 18:47:38.209 ThaliTest[383:160759] server: starting 1449510458205.383.iOTbQw==
,2015-12-07 18:47:38.210 ThaliTest[383:160759] multipeer session: start timer: 0x19bcfc10
,2015-12-07 18:47:38.216 ThaliTest[383:160759] THEMultipeerSession initialized peer 1449510458205.383
,2015-12-07 18:47:38.217 ThaliTest[383:160759] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2015-12-07 18:47:38.222 ThaliTest[383:160759] jxcore: stopBroadcasting
,2015-12-07 18:47:38.223 ThaliTest[383:160759] THEMultipeerSession stopping peer
,2015-12-07 18:47:38.225 ThaliTest[383:160759] multipeer session: stop timer
,2015-12-07 18:47:38.227 ThaliTest[383:160759] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2015-12-07 18:47:38.231 ThaliTest[383:160759] jxcore: startBroadcasting
,2015-12-07 18:47:38.233 ThaliTest[383:160759] server: starting 1449510458231.383.zNdhKg==
,2015-12-07 18:47:38.235 ThaliTest[383:160759] multipeer session: start timer: 0x17d201d0
,2015-12-07 18:47:38.239 ThaliTest[383:160759] THEMultipeerSession initialized peer 1449510458231.383
,2015-12-07 18:47:38.240 ThaliTest[383:160759] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2015-12-07 18:47:38.241 ThaliTest[383:160759] jxcore: stopBroadcasting
,2015-12-07 18:47:38.242 ThaliTest[383:160759] THEMultipeerSession stopping peer
,2015-12-07 18:47:38.242 ThaliTest[383:160759] multipeer session: stop timer
,2015-12-07 18:47:38.244 ThaliTest[383:160759] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2015-12-07 18:47:38.246 ThaliTest[383:160759] jxcore: startBroadcasting
,2015-12-07 18:47:38.248 ThaliTest[383:160759] server: starting 1449510458246.383.rsaB5A==
,2015-12-07 18:47:38.249 ThaliTest[383:160759] multipeer session: start timer: 0x17d2b630
,2015-12-07 18:47:38.252 ThaliTest[383:160759] THEMultipeerSession initialized peer 1449510458246.383
,2015-12-07 18:47:38.253 ThaliTest[383:160759] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2015-12-07 18:47:38.254 ThaliTest[383:160759] jxcore: stopBroadcasting
,2015-12-07 18:47:38.255 ThaliTest[383:160759] THEMultipeerSession stopping peer
,2015-12-07 18:47:38.255 ThaliTest[383:160759] multipeer session: stop timer
,2015-12-07 18:47:38.256 ThaliTest[383:160759] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2015-12-07 18:47:38.259 ThaliTest[383:160759] jxcore: startBroadcasting
,2015-12-07 18:47:38.260 ThaliTest[383:160759] server: starting 1449510458258.383.ZSl6Ng==
,2015-12-07 18:47:38.261 ThaliTest[383:160759] multipeer session: start timer: 0x17d20270
,2015-12-07 18:47:38.264 ThaliTest[383:160759] THEMultipeerSession initialized peer 1449510458258.383
,2015-12-07 18:47:38.264 ThaliTest[383:160759] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2015-12-07 18:47:38.265 ThaliTest[383:160759] jxcore: stopBroadcasting
,2015-12-07 18:47:38.265 ThaliTest[383:160759] THEMultipeerSession stopping peer
,2015-12-07 18:47:38.266 ThaliTest[383:160759] multipeer session: stop timer
,2015-12-07 18:47:38.267 ThaliTest[383:160759] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2015-12-07 18:47:38.269 ThaliTest[383:160759] jxcore: startBroadcasting
,2015-12-07 18:47:38.270 ThaliTest[383:160759] server: starting 1449510458268.383.Cw2p4w==
,2015-12-07 18:47:38.271 ThaliTest[383:160759] multipeer session: start timer: 0x17d45cf0
,2015-12-07 18:47:38.274 ThaliTest[383:160759] THEMultipeerSession initialized peer 1449510458268.383
,2015-12-07 18:47:38.274 ThaliTest[383:160759] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2015-12-07 18:47:38.275 ThaliTest[383:160759] jxcore: stopBroadcasting
,2015-12-07 18:47:38.276 ThaliTest[383:160759] THEMultipeerSession stopping peer
,2015-12-07 18:47:38.276 ThaliTest[383:160759] multipeer session: stop timer
,2015-12-07 18:47:38.277 ThaliTest[383:160759] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2015-12-07 18:47:38.279 ThaliTest[383:160759] jxcore: startBroadcasting
,2015-12-07 18:47:38.280 ThaliTest[383:160759] server: starting 1449510458278.383.9M0kiQ==
,2015-12-07 18:47:38.280 ThaliTest[383:160759] multipeer session: start timer: 0x19bcecc0
,2015-12-07 18:47:38.283 ThaliTest[383:160759] THEMultipeerSession initialized peer 1449510458278.383
,2015-12-07 18:47:38.283 ThaliTest[383:160759] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2015-12-07 18:47:38.284 ThaliTest[383:160759] jxcore: stopBroadcasting
,2015-12-07 18:47:38.284 ThaliTest[383:160759] THEMultipeerSession stopping peer
,2015-12-07 18:47:38.284 ThaliTest[383:160759] multipeer session: stop timer
,2015-12-07 18:47:38.286 ThaliTest[383:160759] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2015-12-07 18:47:38.287 ThaliTest[383:160759] jxcore: startBroadcasting
,2015-12-07 18:47:38.289 ThaliTest[383:160759] server: starting 1449510458287.383.VS0DKg==
,2015-12-07 18:47:38.289 ThaliTest[383:160759] multipeer session: start timer: 0x1b14af80
,2015-12-07 18:47:38.290 ThaliTest[383:160759] THEMultipeerSession initialized peer 1449510458287.383
,2015-12-07 18:47:38.291 ThaliTest[383:160759] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2015-12-07 18:47:38.293 ThaliTest[383:160759] jxcore: stopBroadcasting
2015-12-07 18:47:38.293 ThaliTest[383:160759] THEMultipeerSession stopping peer
,2015-12-07 18:47:38.293 ThaliTest[383:160759] multipeer session: stop timer
,2015-12-07 18:47:38.294 ThaliTest[383:160759] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2015-12-07 18:47:38.295 ThaliTest[383:160759] jxcore: startBroadcasting
,2015-12-07 18:47:38.297 ThaliTest[383:160759] server: starting 1449510458295.383.APMBag==
,2015-12-07 18:47:38.297 ThaliTest[383:160759] multipeer session: start timer: 0x1b149a10
,2015-12-07 18:47:38.298 ThaliTest[383:160759] THEMultipeerSession initialized peer 1449510458295.383
,2015-12-07 18:47:38.299 ThaliTest[383:160759] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2015-12-07 18:47:38.300 ThaliTest[383:160759] jxcore: stopBroadcasting
,2015-12-07 18:47:38.301 ThaliTest[383:160759] THEMultipeerSession stopping peer
,2015-12-07 18:47:38.301 ThaliTest[383:160759] multipeer session: stop timer
,2015-12-07 18:47:38.302 ThaliTest[383:160759] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2015-12-07 18:47:39.015 ThaliTest[383:160759] jxcore: startBroadcasting
,2015-12-07 18:47:39.018 ThaliTest[383:160759] server: starting 1449510459015.383.1eIZSg==
2015-12-07 18:47:39.019 ThaliTest[383:160759] multipeer session: start timer: 0x1b1fa610
,2015-12-07 18:47:39.020 ThaliTest[383:160759] THEMultipeerSession initialized peer 1449510459015.383
2015-12-07 18:47:39.021 ThaliTest[383:160759] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
,2015-12-07 18:47:39.023 ThaliTest[383:160759] jxcore: startBroadcasting
2015-12-07 18:47:39.024 ThaliTest[383:160759] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
2015-12-07 18:47:39.026 ThaliTest[383:160759] jxcore: stop,Broadcasting
2015-12-07 18:47:39.026 ThaliTest[383:160759] THEMultipeerSession stopping peer
2015-12-07 18:47:39.027 ThaliTest[383:160759] multipeer session: stop timer
2015-12-07 18:47:39.027 ThaliTest[383:160759] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2015-12-07 18:47:42.095 ThaliTest[383:160759] jxcore: startBroadcasting
,2015-12-07 18:47:42.097 ThaliTest[383:160759] server: starting 1449510462094.383.QmMGLg==
2015-12-07 18:47:42.098 ThaliTest[383:160759] multipeer session: start timer: 0x1b146960
2015-12-07 18:47:42.098 ThaliTest[383:160759] THEMultipeerSession initialized peer 1449510462094.383
2015-12-07 18:47:42.098 ThaliTest[383:160759] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error
2015-12-07 18:47:42.100 ThaliTest[383:160759] jxcore: connect foobar
2015-12-07 18:47:42.101 ThaliTest[383:160759] client: unknown peer foobar
,2015-12-07 18:47:42.101 ThaliTest[383:160759] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
,2015-12-07 18:47:42.103 ThaliTest[383:160759] jxcore: stopBroadcasting
2015-12-07 18:47:42.104 ThaliTest[383:160759] THEMultipeerSession stopping peer
2015-12-07 18:47:42.104 ThaliTest[383:160759] multipeer session: stop timer
,2015-12-07 18:47:42.105 ThaliTest[383:160759] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2015-12-07 18:47:44.570 ThaliTest[383:160759] jxcore: startBroadcasting
,2015-12-07 18:47:44.573 ThaliTest[383:160759] server: starting 1449510464569.383.h65qRw==
,2015-12-07 18:47:44.574 ThaliTest[383:160759] multipeer session: start timer: 0x19bdc060
,2015-12-07 18:47:44.575 ThaliTest[383:160759] THEMultipeerSession initialized peer 1449510464569.383
,2015-12-07 18:47:44.575 ThaliTest[383:160759] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2015-12-07 18:47:44.578 ThaliTest[383:160759] jxcore: disconnect
,2015-12-07 18:47:44.579 ThaliTest[383:160759] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 
2015-12-07 18:47:44.583 ThaliTest[383:160759] jxcore: stopBroadcasting
2015-12-07 18:47:44.583 ThaliTest[383:160759] THEMultipeerSession stopping peer
2015-12-07 18:47:44.584 ThaliTest[383:160759] multipeer session: stop timer
2015-12-07 18:47:44.585 ThaliTest[383:160759] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2015-12-07 18:47:49.411 ThaliTest[383:160759] jxcore: startBroadcasting
,2015-12-07 18:47:49.414 ThaliTest[383:160759] server: starting 1449510469411.383.Wmi/Ew==
,2015-12-07 18:47:49.415 ThaliTest[383:160759] multipeer session: start timer: 0x19e575b0
2015-12-07 18:47:49.416 ThaliTest[383:160759] THEMultipeerSession initialized peer 1449510469411.383
2015-12-07 18:47:49.416 ThaliTest[383:160759] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error
,2015-12-07 18:47:50.559 ThaliTest[383:160504] client: found peer: 1449510468363.408.sJcxPg==
,2015-12-07 18:47:50.562 ThaliTest[383:160504] client: found peer: 1449510468488.416.gJkiTg==
,2015-12-07 18:47:50.563 ThaliTest[383:160759] jxcore: connect 1449510468363.408.sJcxPg==
2015-12-07 18:47:50.563 ThaliTest[383:160759] client session: connect
2015-12-07 18:47:50.564 ThaliTest[383:160759] client session: stateChange:0->1 1449510468363.408.sJcxPg==
,2015-12-07 18:47:50.572 ThaliTest[383:160759] jxcore: connect 1449510468488.416.gJkiTg==
2015-12-07 18:47:50.573 ThaliTest[383:160759] client session: connect
,2015-12-07 18:47:50.574 ThaliTest[383:160759] client session: stateChange:0->1 1449510468488.416.gJkiTg==
,2015-12-07 18:47:51.314 ThaliTest[383:160504] multipeer session: reset timer
2015-12-07 18:47:51.314 ThaliTest[383:160504] multipeer session: stop timer
2015-12-07 18:47:51.315 ThaliTest[383:160504] multipeer session: start timer: 0x19e575b0
2015-12-07 18:47:51.315 ThaliTest[383:160504] server session: connect
2015-12-07 18:47:51.315 ThaliTest[383:160504] server session: stateChange:0->1 1449510468488.416
,2015-12-07 18:47:51.322 ThaliTest[383:160504] server: accepting invitation 1449510468488.416
,2015-12-07 18:47:51.465 ThaliTest[383:160504] multipeer session: reset timer
2015-12-07 18:47:51.465 ThaliTest[383:160504] multipeer session: stop timer
2015-12-07 18:47:51.465 ThaliTest[383:160504] multipeer session: start timer: 0x19e575b0
2015-12-07 18:47:51.465 ThaliTest[383:160504] server session: connect
2015-12-07 18:47:51.465 ThaliTest[383:160504] server session: stateChange:0->1 1449510468363.408
2015-12-07 18:47:51.467 ThaliTest[383:160504] server: accepting invitation 1449510468363.408
,2015-12-07 18:47:51.793 ThaliTest[383:160504] multipeer session: reset timer
2015-12-07 18:47:51.793 ThaliTest[383:160504] multipeer session: stop timer
2015-12-07 18:47:51.793 ThaliTest[383:160504] multipeer session: start timer: 0x19e575b0
2015-12-07 18:47:51.793 ThaliTest[383:160504] server session: connect
2015-12-07 18:47:51.793 ThaliTest[383:160504] server session: stateChange:0->1 1449510468177.375
,2015-12-07 18:47:51.797 ThaliTest[383:160504] server: accepting invitation 1449510468177.375
,2015-12-07 18:47:52.866 ThaliTest[383:160504] client: found peer: 1449510468177.375.Xvfalg==
,2015-12-07 18:47:52.868 ThaliTest[383:160759] jxcore: connect 1449510468177.375.Xvfalg==
2015-12-07 18:47:52.868 ThaliTest[383:160759] client session: connect
2015-12-07 18:47:52.868 ThaliTest[383:160759] client session: stateChange:0->1 1449510468177.375.Xvfalg==
,2015-12-07 18:47:53.869 ThaliTest[383:160812] server session: connected
,2015-12-07 18:47:53.869 ThaliTest[383:160812] server session: stateChange:1->2 1449510468488.416
,2015-12-07 18:47:53.874 ThaliTest[383:160504] server relay: socket disconnected
2015-12-07 18:47:53.875 ThaliTest[383:160504] server relay: 0x1b13c9e0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocaliz,edFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:47:53.937 ThaliTest[383:160801] server session: not connected 1449510468488.416
,2015-12-07 18:47:54.369 ThaliTest[383:160869] server session: connected
2015-12-07 18:47:54.369 ThaliTest[383:160869] server session: stateChange:1->2 1449510468363.408
,2015-12-07 18:47:54.376 ThaliTest[383:160504] server relay: socket disconnected
2015-12-07 18:47:54.376 ThaliTest[383:160504] server relay: 0x19bf2e30 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocaliz,edFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:47:54.441 ThaliTest[383:160894] client session: connected
,2015-12-07 18:47:54.441 ThaliTest[383:160894] client session: stateChange:1->2 1449510468488.416.gJkiTg==
,2015-12-07 18:47:54.474 ThaliTest[383:160814] client session: fireConnectCallback: 1449510468488.416.gJkiTg==
,2015-12-07 18:47:54.474 ThaliTest[383:160814] jxcore: connect: success
ok 75 Should be able to connect without error
ok 76 Port should be within range
,2015-12-07 18:47:54.481 ThaliTest[383:160759] jxcore: disconnect
2015-12-07 18:47:54.481 ThaliTest[383:160759] client session: disconnectFromPeer: 1449510468488.416.gJkiTg==
2015-12-07 18:47:54.482 ThaliTest[383:160759] client session: disconnect
2015-12-07 18:47:54.482 ThaliTest[383:160759] client session: stateChange:2->0 1449510468488.416.gJkiTg==
,2015-12-07 18:47:54.493 ThaliTest[383:160882] client session: connected
2015-12-07 18:47:54.495 ThaliTest[383:160882] client session: stateChange:1->2 1449510468363.408.sJcxPg==
,2015-12-07 18:47:54.499 ThaliTest[383:160759] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,2015-12-07 18:47:54.501 ThaliTest[383:160882] client session: fireConnectCallback: 1449510468363.408.sJcxPg==
2015-12-07 18:47:54.502 ThaliTest[383:160882] jxcore: connect: success
# setup
ok 78 Should be able to connect without error
,ok 79 Port should be within range
2015-12-07 18:47:54.506 ThaliTest[383:160759] jxcore: disconnect
2015-12-07 18:47:54.506 ThaliTest[383:160759] client session: disconnectFromPeer: 1449510468363.408.sJcxPg==
2015-12-07 18:47:54.507 ThaliTest[383:160759], client session: disconnect
2015-12-07 18:47:54.507 ThaliTest[383:160759] client session: stateChange:2->0 1449510468363.408.sJcxPg==
2015-12-07 18:47:54.507 ThaliTest[383:160882] server session: not connected 1449510468363.408
,2015-12-07 18:47:54.575 ThaliTest[383:160759] jxcore: disconnect: success
,ok 80 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,not ok 81 .end() called twice
  ---
,    operator: fail
  ...
,2015-12-07 18:47:54.865 ThaliTest[383:160814] server session: connected
,2015-12-07 18:47:54.865 ThaliTest[383:160814] server session: stateChange:1->2 1449510468177.375
,2015-12-07 18:47:54.873 ThaliTest[383:160504] server relay: socket disconnected
2015-12-07 18:47:54.874 ThaliTest[383:160504] server relay: 0x1b1407b0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:47:54.910 ThaliTest[383:160814] server session: not connected 1449510468177.375
,calling stopBroadcasting
,2015-12-07 18:47:55.111 ThaliTest[383:160759] jxcore: stopBroadcasting
,2015-12-07 18:47:55.111 ThaliTest[383:160759] THEMultipeerSession stopping peer
,2015-12-07 18:47:55.112 ThaliTest[383:160759] multipeer session: stop timer
,2015-12-07 18:47:55.113 ThaliTest[383:160759] client session: disconnect
,2015-12-07 18:47:55.113 ThaliTest[383:160759] client session: stateChange:1->0 1449510468177.375.Xvfalg==
,2015-12-07 18:47:55.121 ThaliTest[383:160759] server session: disconnect
2015-12-07 18:47:55.121 ThaliTest[383:160759] server session: stateChange:2->0 1449510468488.416
,2015-12-07 18:47:55.124 ThaliTest[383:160759] server session: disconnect
2015-12-07 18:47:55.124 ThaliTest[383:160759] server session: stateChange:2->0 1449510468177.375
,2015-12-07 18:47:55.127 ThaliTest[383:160759] server session: disconnect
2015-12-07 18:47:55.128 ThaliTest[383:160759] server session: stateChange:2->0 1449510468363.408
,2015-12-07 18:47:55.134 ThaliTest[383:160759] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2015-12-07 18:47:56.527 ThaliTest[383:160759] jxcore: startBroadcasting
,2015-12-07 18:47:56.530 ThaliTest[383:160759] server: starting 1449510476527.383.t1iPAw==
,2015-12-07 18:47:56.532 ThaliTest[383:160759] multipeer session: start timer: 0x19bfba20
2015-12-07 18:47:56.533 ThaliTest[383:160759] THEMultipeerSession initialized peer 1449510476527.383
2015-12-07 18:47:56.533 ThaliTest[383:160759] jxcore: startBroadcasting: success
,ok 82 Should be able to call startBroadcasting without error
,2015-12-07 18:47:57.447 ThaliTest[383:160504] client: found peer: 1449510475496.408.7GdpBQ==
2015-12-07 18:47:57.448 ThaliTest[383:160504] client: found peer: 1449510475581.416.zFnyqQ==
2015-12-07 18:47:57.449 ThaliTest[383:160759] jxcore: connect 1449510475496.408.7GdpBQ==
2015-12-07 18:47:57.449 ThaliTest[383:160759] client session: connect
2015-12-07 18:47:57.450 ThaliTest[383:160759] client session: stateChange:0->1 1449510475496.408.7GdpBQ==
,2015-12-07 18:47:57.458 ThaliTest[383:160759] jxcore: connect 1449510475581.416.zFnyqQ==
2015-12-07 18:47:57.459 ThaliTest[383:160759] client session: connect
2015-12-07 18:47:57.459 ThaliTest[383:160759] client session: stateChange:0->1 1449510475581.41,6.zFnyqQ==
,2015-12-07 18:47:58.231 ThaliTest[383:160504] multipeer session: reset timer
2015-12-07 18:47:58.232 ThaliTest[383:160504] multipeer session: stop timer
,2015-12-07 18:47:58.232 ThaliTest[383:160504] multipeer session: start timer: 0x19bfba20
,2015-12-07 18:47:58.232 ThaliTest[383:160504] server session: connect
2015-12-07 18:47:58.233 ThaliTest[383:160504] server session: stateChange:0->1 1449510475496.408
,2015-12-07 18:47:58.239 ThaliTest[383:160504] server: accepting invitation 1449510475496.408
,2015-12-07 18:47:58.278 ThaliTest[383:160504] multipeer session: reset timer
2015-12-07 18:47:58.278 ThaliTest[383:160504] multipeer session: stop timer
2015-12-07 18:47:58.278 ThaliTest[383:160504] multipeer session: start timer: 0x19bfba20
2015-12-07 18:47:58.278 ThaliTest[383:160504] server session: connect
2015-12-07 18:47:58.278 ThaliTest[383:160504] server session: stateChange:0->1 1449510475581.416
,2015-12-07 18:47:58.281 ThaliTest[383:160504] server: accepting invitation 1449510475581.416
,2015-12-07 18:47:58.421 ThaliTest[383:160504] multipeer session: reset timer
2015-12-07 18:47:58.421 ThaliTest[383:160504] multipeer session: stop timer
,2015-12-07 18:47:58.421 ThaliTest[383:160504] multipeer session: start timer: 0x19bfba20
2015-12-07 18:47:58.422 ThaliTest[383:160504] server session: connect
,2015-12-07 18:47:58.422 ThaliTest[383:160504] server session: stateChange:0->1 1449510476485.375
,2015-12-07 18:47:58.432 ThaliTest[383:160504] server: accepting invitation 1449510476485.375
,2015-12-07 18:47:58.748 ThaliTest[383:160504] client: found peer: 1449510476485.375./zzCMA==
2015-12-07 18:47:58.751 ThaliTest[383:160759] jxcore: connect 1449510476485.375./zzCMA==
2015-12-07 18:47:58.751 ThaliTest[383:160759] client session: connect
2015-12-07 18:47:58.752 ThaliTest[383:160759] client session: stateChange:0->1 1449510476485.375./zzCMA==
,2015-12-07 18:48:01.288 ThaliTest[383:160907] client session: connected
2015-12-07 18:48:01.288 ThaliTest[383:160907] client session: stateChange:1->2 1449510475581.416.zFnyqQ==
,2015-12-07 18:48:01.296 ThaliTest[383:160801] client session: fireConnectCallback: 1449510475581.416.zFnyqQ==
2015-12-07 18:48:01.296 ThaliTest[383:160801] jxcore: connect: success
,ok 83 Should be able to connect without error
ok 84 Port should be within range
,2015-12-07 18:48:01.298 ThaliTest[383:160759] jxcore: connect 1449510475581.416.zFnyqQ==
,2015-12-07 18:48:01.298 ThaliTest[383:160759] client: already connect(ing/ed) to 1449510475581.416.zFnyqQ==
2015-12-07 18:48:01.298 ThaliTest[383:160759] jxcore: connect: fail: Aleady connecting
,ok 85 Should fail on double connect
2015-12-07 18:48:01.299 ThaliTest[383:160759] jxcore: disconnect
2015-12-07 18:48:01.299 ThaliTest[383:160759] client session: disconnectFromPeer: 1449510475581.416.zFnyqQ==
,2015-12-07 18:48:01.300 ThaliTest[383:160759] client session: disconnect
2015-12-07 18:48:01.300 ThaliTest[383:160759] client session: stateChange:2->0 1449510475581.416.zFnyqQ==
,2015-12-07 18:48:01.303 ThaliTest[383:160759] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2015-12-07 18:48:01.417 ThaliTest[383:160801] server session: connected
2015-12-07 18:48:01.417 ThaliTest[383:160801] server session: stateChange:1->2 1449510475581.416
,2015-12-07 18:48:01.419 ThaliTest[383:160504] server relay: socket disconnected
2015-12-07 18:48:01.419 ThaliTest[383:160504] server relay: 0x17d65040 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:48:01.451 ThaliTest[383:160907] server session: not connected 1449510475581.416
,2015-12-07 18:48:01.488 ThaliTest[383:160801] server session: connected
2015-12-07 18:48:01.488 ThaliTest[383:160801] server session: stateChange:1->2 1449510475496.408
,2015-12-07 18:48:01.490 ThaliTest[383:160504] server relay: socket disconnected
,2015-12-07 18:48:01.491 ThaliTest[383:160504] server relay: 0x1b129ea0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:48:01.563 ThaliTest[383:160906] server session: not connected 1449510475496.408
,2015-12-07 18:48:01.753 ThaliTest[383:160907] client session: connected
,2015-12-07 18:48:01.754 ThaliTest[383:160907] client session: stateChange:1->2 1449510475496.408.7GdpBQ==
,2015-12-07 18:48:01.758 ThaliTest[383:160907] client session: fireConnectCallback: 1449510475496.408.7GdpBQ==
2015-12-07 18:48:01.759 ThaliTest[383:160907] jxcore: connect: success
,ok 87 Should be able to connect without error
,ok 88 Port should be within range
,2015-12-07 18:48:01.763 ThaliTest[383:160759] jxcore: connect 1449510475496.408.7GdpBQ==
,2015-12-07 18:48:01.763 ThaliTest[383:160759] client: already connect(ing/ed) to 1449510475496.408.7GdpBQ==
,2015-12-07 18:48:01.764 ThaliTest[383:160759] jxcore: connect: fail: Aleady connecting
,ok 89 Should fail on double connect
,2015-12-07 18:48:01.766 ThaliTest[383:160759] jxcore: disconnect
,2015-12-07 18:48:01.767 ThaliTest[383:160759] client session: disconnectFromPeer: 1449510475496.408.7GdpBQ==
,2015-12-07 18:48:01.767 ThaliTest[383:160759] client session: disconnect
,2015-12-07 18:48:01.768 ThaliTest[383:160759] client session: stateChange:2->0 1449510475496.408.7GdpBQ==
,2015-12-07 18:48:01.835 ThaliTest[383:160759] jxcore: disconnect: success
,ok 90 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,not ok 91 .end() called twice
,  ---
,    operator: fail
,  ...
,calling stopBroadcasting
,2015-12-07 18:48:02.480 ThaliTest[383:160759] jxcore: stopBroadcasting
,2015-12-07 18:48:02.481 ThaliTest[383:160759] THEMultipeerSession stopping peer
,2015-12-07 18:48:02.481 ThaliTest[383:160759] multipeer session: stop timer
2015-12-07 18:48:02.482 ThaliTest[383:160759] client session: disconnect
2015-12-07 18:48:02.482 ThaliTest[383:160759] client session: stateChange:1->0 1449510476485.375./zzCMA==
,2015-12-07 18:48:02.487 ThaliTest[383:160759] server session: disconnect
2015-12-07 18:48:02.491 ThaliTest[383:160759] server session: stateChange:1->0 1449510476485.375
,2015-12-07 18:48:02.572 ThaliTest[383:160759] server session: disconnect
,2015-12-07 18:48:02.573 ThaliTest[383:160759] server session: stateChange:2->0 1449510475496.408
,2015-12-07 18:48:03.115 ThaliTest[383:160759] server session: disconnect
2015-12-07 18:48:03.115 ThaliTest[383:160759] server session: stateChange:2->0 1449510475581.416
,2015-12-07 18:48:03.117 ThaliTest[383:160759] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2015-12-07 18:48:11.347 ThaliTest[383:160759] jxcore: startBroadcasting
,2015-12-07 18:48:11.351 ThaliTest[383:160759] server: starting 1449510491347.383.nrOfbw==
,2015-12-07 18:48:11.352 ThaliTest[383:160759] multipeer session: start timer: 0x19beb690
,2015-12-07 18:48:11.352 ThaliTest[383:160759] THEMultipeerSession initialized peer 1449510491347.383
2015-12-07 18:48:11.353 ThaliTest[383:160759] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error
,2015-12-07 18:48:11.442 ThaliTest[383:160504] client: found peer: 1449510489175.408.1RR9xA==
,2015-12-07 18:48:11.443 ThaliTest[383:160759] jxcore: connect 1449510489175.408.1RR9xA==
2015-12-07 18:48:11.444 ThaliTest[383:160759] client session: connect
2015-12-07 18:48:11.444 ThaliTest[383:160759] client session: stateChange:0->1 1449510489175.40,8.1RR9xA==
,2015-12-07 18:48:11.675 ThaliTest[383:160504] client: found peer: 1449510489481.375.tffILg==
,2015-12-07 18:48:11.677 ThaliTest[383:160759] jxcore: connect 1449510489481.375.tffILg==
2015-12-07 18:48:11.678 ThaliTest[383:160759] client session: connect
2015-12-07 18:48:11.678 ThaliTest[383:160759] client session: stateChange:0->1 1449510489481.37,5.tffILg==
,2015-12-07 18:48:12.896 ThaliTest[383:160504] client: found peer: 1449510491053.416.ZCqZnQ==
,2015-12-07 18:48:12.897 ThaliTest[383:160759] jxcore: connect 1449510491053.416.ZCqZnQ==
,2015-12-07 18:48:12.898 ThaliTest[383:160759] client session: connect
,2015-12-07 18:48:12.899 ThaliTest[383:160759] client session: stateChange:0->1 1449510491053.416.ZCqZnQ==
,2015-12-07 18:48:12.999 ThaliTest[383:160504] multipeer session: reset timer
2015-12-07 18:48:12.999 ThaliTest[383:160504] multipeer session: stop timer
2015-12-07 18:48:12.999 ThaliTest[383:160504] multipeer session: start timer: 0x19beb690
2015-12-07 ,18:48:13.000 ThaliTest[383:160504] server session: connect
2015-12-07 18:48:13.000 ThaliTest[383:160504] server session: stateChange:0->1 1449510489175.408
,2015-12-07 18:48:13.006 ThaliTest[383:160504] server: accepting invitation 1449510489175.408
,2015-12-07 18:48:13.207 ThaliTest[383:160504] multipeer session: reset timer
2015-12-07 18:48:13.207 ThaliTest[383:160504] multipeer session: stop timer
,2015-12-07 18:48:13.207 ThaliTest[383:160504] multipeer session: start timer: 0x19beb690
2015-12-07 18:48:13.207 ThaliTest[383:160504] server session: connect
2015-12-07 18:48:13.208 ThaliTest[383:160504] server session: stateChange:0->1 1449510491053.416
,2015-12-07 18:48:13.210 ThaliTest[383:160504] server: accepting invitation 1449510491053.416
,2015-12-07 18:48:13.602 ThaliTest[383:160504] multipeer session: reset timer
2015-12-07 18:48:13.602 ThaliTest[383:160504] multipeer session: stop timer
2015-12-07 18:48:13.602 ThaliTest[383:160504] multipeer session: start timer: 0x19beb690
2015-12-07 ,18:48:13.602 ThaliTest[383:160504] server session: connect
2015-12-07 18:48:13.602 ThaliTest[383:160504] server session: stateChange:0->1 1449510489481.375
,2015-12-07 18:48:13.605 ThaliTest[383:160504] server: accepting invitation 1449510489481.375
,2015-12-07 18:48:14.553 ThaliTest[383:160812] client session: connected
2015-12-07 18:48:14.553 ThaliTest[383:160812] client session: stateChange:1->2 1449510489175.408.1RR9xA==
,2015-12-07 18:48:14.589 ThaliTest[383:160981] client session: fireConnectCallback: 1449510489175.408.1RR9xA==
,2015-12-07 18:48:14.590 ThaliTest[383:160981] jxcore: connect: success
,ok 93 Should be able to connect without error
,ok 94 Port should be within range
,2015-12-07 18:48:14.595 ThaliTest[383:160759] jxcore: disconnect
,2015-12-07 18:48:14.595 ThaliTest[383:160759] client session: disconnectFromPeer: 1449510489175.408.1RR9xA==
,2015-12-07 18:48:14.596 ThaliTest[383:160759] client session: disconnect
,2015-12-07 18:48:14.597 ThaliTest[383:160759] client session: stateChange:2->0 1449510489175.408.1RR9xA==
,2015-12-07 18:48:14.606 ThaliTest[383:160759] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error
2015-12-07 18:48:14.608 ThaliTest[383:160759] jxcore: disconnect
2015-12-07 18:48:14.608 ThaliTest[383:160759] jxcore: disconnect: fail
ok 96 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,2015-12-07 18:48:15.910 ThaliTest[383:160907] server session: connected
2015-12-07 18:48:15.911 ThaliTest[383:160907] server session: stateChange:1->2 1449510489175.408
,2015-12-07 18:48:15.959 ThaliTest[383:160504] server relay: socket disconnected
2015-12-07 18:48:15.960 ThaliTest[383:160504] server relay: 0x1b142410 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:48:15.991 ThaliTest[383:160905] server session: not connected 1449510489175.408
,2015-12-07 18:48:16.164 ThaliTest[383:160812] client session: connected
2015-12-07 18:48:16.165 ThaliTest[383:160812] client session: stateChange:1->2 1449510489481.375.tffILg==
,2015-12-07 18:48:16.194 ThaliTest[383:160812] client session: fireConnectCallback: 1449510489481.375.tffILg==
,2015-12-07 18:48:16.195 ThaliTest[383:160812] jxcore: connect: success
,ok 97 Should be able to connect without error
,ok 98 Port should be within range
,2015-12-07 18:48:16.199 ThaliTest[383:160759] jxcore: disconnect
,2015-12-07 18:48:16.200 ThaliTest[383:160759] client session: disconnectFromPeer: 1449510489481.375.tffILg==
,2015-12-07 18:48:16.200 ThaliTest[383:160759] client session: disconnect
,2015-12-07 18:48:16.201 ThaliTest[383:160759] client session: stateChange:2->0 1449510489481.375.tffILg==
,2015-12-07 18:48:16.240 ThaliTest[383:160907] server session: connected
2015-12-07 18:48:16.241 ThaliTest[383:160907] server session: stateChange:1->2 1449510491053.416
,2015-12-07 18:48:16.276 ThaliTest[383:160504] server relay: socket disconnected
,2015-12-07 18:48:16.276 ThaliTest[383:160504] server relay: 0x19be8ff0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:48:16.307 ThaliTest[383:160759] jxcore: disconnect: success
,ok 99 Should be able to disconnect without error
,2015-12-07 18:48:16.309 ThaliTest[383:160759] jxcore: disconnect
,2015-12-07 18:48:16.309 ThaliTest[383:160759] jxcore: disconnect: fail
,ok 100 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,not ok 101 .end() called twice
,  ---
,    operator: fail
,  ...
,2015-12-07 18:48:16.326 ThaliTest[383:160907] client session: connected
2015-12-07 18:48:16.326 ThaliTest[383:160907] client session: stateChange:1->2 1449510491053.416.ZCqZnQ==
,2015-12-07 18:48:16.355 ThaliTest[383:160907] server session: not connected 1449510491053.416
,2015-12-07 18:48:16.360 ThaliTest[383:160801] client session: fireConnectCallback: 1449510491053.416.ZCqZnQ==
,2015-12-07 18:48:16.360 ThaliTest[383:160801] jxcore: connect: success
,ok 102 Should be able to connect without error
,ok 103 Port should be within range
,2015-12-07 18:48:16.363 ThaliTest[383:160759] jxcore: disconnect
,2015-12-07 18:48:16.363 ThaliTest[383:160759] client session: disconnectFromPeer: 1449510491053.416.ZCqZnQ==
,2015-12-07 18:48:16.364 ThaliTest[383:160759] client session: disconnect
,2015-12-07 18:48:16.364 ThaliTest[383:160759] client session: stateChange:2->0 1449510491053.416.ZCqZnQ==
,2015-12-07 18:48:16.364 ThaliTest[383:160801] server session: connected
2015-12-07 18:48:16.364 ThaliTest[383:160801] server session: stateChange:1->2 1449510489481.375
,2015-12-07 18:48:16.369 ThaliTest[383:160759] jxcore: disconnect: success
ok 104 Should be able to disconnect without error
,2015-12-07 18:48:16.369 ThaliTest[383:160759] jxcore: disconnect
,2015-12-07 18:48:16.371 ThaliTest[383:160759] jxcore: disconnect: fail
,ok 105 Disconnect should fail 
setting stopBroadcasting callback and ending test.
not ok 106 .end() called twice
  ---
    operator: fail
  ...
,2015-12-07 18:48:16.383 ThaliTest[383:160504] server relay: socket disconnected
,2015-12-07 18:48:16.384 ThaliTest[383:160504] server relay: 0x19bee650 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,calling stopBroadcasting
,2015-12-07 18:48:16.603 ThaliTest[383:160759] jxcore: stopBroadcasting
,2015-12-07 18:48:16.604 ThaliTest[383:160759] THEMultipeerSession stopping peer
,2015-12-07 18:48:16.604 ThaliTest[383:160759] multipeer session: stop timer
,2015-12-07 18:48:16.605 ThaliTest[383:160759] server session: disconnect
,2015-12-07 18:48:16.606 ThaliTest[383:160759] server session: stateChange:2->0 1449510489175.408
,2015-12-07 18:48:16.607 ThaliTest[383:160759] server session: disconnect
,2015-12-07 18:48:16.608 ThaliTest[383:160759] server session: stateChange:2->0 1449510489481.375
,2015-12-07 18:48:16.631 ThaliTest[383:160759] server session: disconnect
2015-12-07 18:48:16.632 ThaliTest[383:160759] server session: stateChange:2->0 1449510491053.416
,2015-12-07 18:48:16.635 ThaliTest[383:160759] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,2015-12-07 18:48:26.003 ThaliTest[383:160759] jxcore: startBroadcasting
,2015-12-07 18:48:26.006 ThaliTest[383:160759] server: starting 1449510506003.383.i2Azhg==
,2015-12-07 18:48:26.007 ThaliTest[383:160759] multipeer session: start timer: 0x1b12ba40
2015-12-07 18:48:26.008 ThaliTest[383:160759] THEMultipeerSession initialized peer 1449510506003.383
2015-12-07 18:48:26.008 ThaliTest[383:160759] jxcore: startBroadcasting: success
,ok 107 Should be able to call startBroadcasting without error
,echo server started
,2015-12-07 18:48:28.202 ThaliTest[383:160504] client: found peer: 1449510506165.416.wWLXyQ==
,[{"peerIdentifier":"1449510506165.416.wWLXyQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-07 18:48:28.206 ThaliTest[383:160759] jxcore: connect 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:28.207 ThaliTest[383:160759] client session: connect
,2015-12-07 18:48:28.207 ThaliTest[383:160759] client session: stateChange:0->1 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:28.363 ThaliTest[383:160504] multipeer session: reset timer
2015-12-07 18:48:28.364 ThaliTest[383:160504] multipeer session: stop timer
2015-12-07 18:48:28.364 ThaliTest[383:160504] multipeer session: start timer: 0x1b12ba40
2015-12-07 18:48:28.364 ThaliTest[383:160504] server session: connect
,2015-12-07 18:48:28.365 ThaliTest[383:160504] server session: stateChange:0->1 1449510506999.375
,2015-12-07 18:48:28.371 ThaliTest[383:160504] server: accepting invitation 1449510506999.375
,2015-12-07 18:48:28.926 ThaliTest[383:160504] multipeer session: reset timer
2015-12-07 18:48:28.927 ThaliTest[383:160504] multipeer session: stop timer
,2015-12-07 18:48:28.927 ThaliTest[383:160504] multipeer session: start timer: 0x1b12ba40
2015-12-07 18:48:28.927 ThaliTest[383:160504] server session: connect
,2015-12-07 18:48:28.927 ThaliTest[383:160504] server session: stateChange:0->1 1449510506165.416
,2015-12-07 18:48:28.931 ThaliTest[383:160504] server: accepting invitation 1449510506165.416
,2015-12-07 18:48:29.059 ThaliTest[383:160504] client: found peer: 1449510506999.375.Lduuig==
[{"peerIdentifier":"1449510506999.375.Lduuig==","peerName":"(null)","peerAvailable":true}]
,2015-12-07 18:48:29.060 ThaliTest[383:160759] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:29.060 ThaliTest[383:160759] client session: connect
2015-12-07 18:48:29.061 ThaliTest[383:160759] client session: stateChange:0->1 1449510506999.375.Lduuig==
,2015-12-07 18:48:29.387 ThaliTest[383:160504] multipeer session: reset timer
2015-12-07 18:48:29.387 ThaliTest[383:160504] multipeer session: stop timer
2015-12-07 18:48:29.387 ThaliTest[383:160504] multipeer session: start timer: 0x1b12ba40
2015-12-07 18:48:29.388 ThaliTest[383:160504] server session: connect
,2015-12-07 18:48:29.388 ThaliTest[383:160504] server session: stateChange:0->1 1449510507109.408
,2015-12-07 18:48:29.395 ThaliTest[383:160504] server: accepting invitation 1449510507109.408
,2015-12-07 18:48:30.345 ThaliTest[383:160504] client: found peer: 1449510507109.408.rby7cA==
,[{"peerIdentifier":"1449510507109.408.rby7cA==","peerName":"(null)","peerAvailable":true}]
,2015-12-07 18:48:30.347 ThaliTest[383:160759] jxcore: connect 1449510507109.408.rby7cA==
,2015-12-07 18:48:30.348 ThaliTest[383:160759] client session: connect
,2015-12-07 18:48:30.349 ThaliTest[383:160759] client session: stateChange:0->1 1449510507109.408.rby7cA==
,2015-12-07 18:48:30.832 ThaliTest[383:160979] client session: connected
2015-12-07 18:48:30.832 ThaliTest[383:160979] client session: stateChange:1->2 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:30.857 ThaliTest[383:160980] client session: fireConnectCallback: 1449510506165.416.wWLXyQ==
2015-12-07 18:48:30.857 ThaliTest[383:160980] jxcore: connect: success
,ok 108 Should be able to connect without error
,ok 109 Port should be within range
,ok 110 First connect should succeed
,2015-12-07 18:48:30.873 ThaliTest[383:160504] client: relay established
2015-12-07 18:48:30.873 ThaliTest[383:160504] client: new accepted socket: 0x19eaabf0
,ok 111 the test messages should be equal
,ok 112 First send should succeed
,2015-12-07 18:48:30.937 ThaliTest[383:160504] client: socket closed
2015-12-07 18:48:30.937 ThaliTest[383:160504] client relay: socket disconnected
,2015-12-07 18:48:30.937 ThaliTest[383:160504] client relay: 0x19eaabf0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-07 18:48:30,.937 ThaliTest[383:160504] client session: socket closed: 1449510506165.416.wWLXyQ==
2015-12-07 18:48:30.937 ThaliTest[383:160504] client session: onLinkFailure: 1449510506165.416.wWLXyQ==
2015-12-07 18:48:30.938 ThaliTest[383:160504] client session: disconnect
2015-12-07 18:48:30.938 ThaliTest[383:160504] client session: stateChange:2->0 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:30.942 ThaliTest[383:160504] client session: fireConnectionErrorEvent: 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:30.944 ThaliTest[383:160759] jxcore: connect 1449510506165.416.wWLXyQ==
2015-12-07 18:48:30.944 ThaliTest[383:160759] client session: connect
2015-12-07 18:48:30.944 ThaliTest[383:160759] client session: stateChange:0->1 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:31.039 ThaliTest[383:160801] server session: connected
2015-12-07 18:48:31.039 ThaliTest[383:160801] server session: stateChange:1->2 1449510506999.375
,2015-12-07 18:48:31.441 ThaliTest[383:160504] server relay: connected (to port: 5001)
,2015-12-07 18:48:31.522 ThaliTest[383:160801] server session: not connected 1449510506999.375
,2015-12-07 18:48:31.571 ThaliTest[383:160504] multipeer session: reset timer
2015-12-07 18:48:31.571 ThaliTest[383:160504] multipeer session: stop timer
,2015-12-07 18:48:31.571 ThaliTest[383:160504] multipeer session: start timer: 0x1b12ba40
2015-12-07 18:48:31.571 ThaliTest[383:160504] server: disconnecting to refresh session (1449510506999.375)
2015-12-07 18:48:31.571 ThaliTest[383:160504] server session: disconnect
2015-12-07 18:48:31.571 ThaliTest[383:160504] server session: stateChange:2->0 1449510506999.375
,2015-12-07 18:48:31.573 ThaliTest[383:160504] server session: connect
2015-12-07 18:48:31.573 ThaliTest[383:160504] server session: stateChange:0->1 1449510506999.375
,2015-12-07 18:48:31.576 ThaliTest[383:160504] server: accepting invitation 1449510506999.375
,2015-12-07 18:48:31.663 ThaliTest[383:160979] server session: connected
2015-12-07 18:48:31.663 ThaliTest[383:160979] server session: stateChange:1->2 1449510506165.416
,2015-12-07 18:48:31.681 ThaliTest[383:160504] server relay: connected (to port: 5001)
,2015-12-07 18:48:31.933 ThaliTest[383:160801] server session: not connected 1449510506165.416
,2015-12-07 18:48:31.961 ThaliTest[383:160504] multipeer session: reset timer
2015-12-07 18:48:31.961 ThaliTest[383:160504] multipeer session: stop timer
2015-12-07 18:48:31.961 ThaliTest[383:160504] multipeer session: start timer: 0x1b12ba40
,2015-12-07 18:48:31.962 ThaliTest[383:160504] server: disconnecting to refresh session (1449510506165.416)
,2015-12-07 18:48:31.962 ThaliTest[383:160504] server session: disconnect
,2015-12-07 18:48:31.962 ThaliTest[383:160504] server session: stateChange:2->0 1449510506165.416
,2015-12-07 18:48:32.188 ThaliTest[383:160504] server session: connect
2015-12-07 18:48:32.188 ThaliTest[383:160504] server session: stateChange:0->1 1449510506165.416
,2015-12-07 18:48:32.196 ThaliTest[383:160504] server: accepting invitation 1449510506165.416
,2015-12-07 18:48:32.937 ThaliTest[383:160801] server session: connected
,2015-12-07 18:48:32.937 ThaliTest[383:160801] server session: stateChange:1->2 1449510507109.408
,2015-12-07 18:48:32.954 ThaliTest[383:160504] server relay: connected (to port: 5001)
,2015-12-07 18:48:32.990 ThaliTest[383:161059] client session: connected
2015-12-07 18:48:32.991 ThaliTest[383:161059] client session: stateChange:1->2 1449510506999.375.Lduuig==
,2015-12-07 18:48:32.994 ThaliTest[383:161059] client session: fireConnectCallback: 1449510506999.375.Lduuig==
2015-12-07 18:48:32.995 ThaliTest[383:161059] jxcore: connect: success
,ok 113 Should be able to connect without error
,ok 114 Port should be within range
ok 115 First connect should succeed
,2015-12-07 18:48:33.023 ThaliTest[383:160504] client: relay established
2015-12-07 18:48:33.023 ThaliTest[383:160504] client: new accepted socket: 0x19b42300
,ok 116 the test messages should be equal
ok 117 First send should succeed
,2015-12-07 18:48:33.141 ThaliTest[383:160504] client: socket closed
2015-12-07 18:48:33.142 ThaliTest[383:160504] client relay: socket disconnected
,2015-12-07 18:48:33.142 ThaliTest[383:160504] client relay: 0x19b42300 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-07 18:48:33.143 ThaliTest[383:160504] client session: socket closed: 1449510506999.375.Lduuig==
,2015-12-07 18:48:33.143 ThaliTest[383:160504] client session: onLinkFailure: 1449510506999.375.Lduuig==
2015-12-07 18:48:33.143 ThaliTest[383:160504] client session: disconnect
2015-12-07 18:48:33.143 ThaliTest[383:160504] client session: stateChange:2->,0 1449510506999.375.Lduuig==
,2015-12-07 18:48:33.153 ThaliTest[383:160504] client session: fireConnectionErrorEvent: 1449510506999.375.Lduuig==
,2015-12-07 18:48:33.156 ThaliTest[383:160759] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:33.157 ThaliTest[383:160759] client session: connect
,2015-12-07 18:48:33.158 ThaliTest[383:160759] client session: stateChange:0->1 1449510506999.375.Lduuig==
,2015-12-07 18:48:33.168 ThaliTest[383:160759] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:33.168 ThaliTest[383:160759] client: already connect(ing/ed) to 1449510506999.375.Lduuig==
2015-12-07 18:48:33.169 ThaliTest[383:160759] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:33.211 ThaliTest[383:161036] server session: not connected 1449510507109.408
,2015-12-07 18:48:33.449 ThaliTest[383:161036] client session: connected
2015-12-07 18:48:33.449 ThaliTest[383:161036] client session: stateChange:1->2 1449510507109.408.rby7cA==
,2015-12-07 18:48:33.457 ThaliTest[383:161059] client session: fireConnectCallback: 1449510507109.408.rby7cA==
2015-12-07 18:48:33.457 ThaliTest[383:161059] jxcore: connect: success
,ok 118 Should be able to connect without error
ok 119 Port should be within range
2015-12-07 18:48:33.462 ThaliTest[383:160504] multipeer session: reset timer
2015-12-07 18:48:33.462 ThaliTest[383:160504] multipeer session: stop timer
ok 120 First conn,ect should succeed
2015-12-07 18:48:33.462 ThaliTest[383:160504] multipeer session: start timer: 0x1b12ba40
2015-12-07 18:48:33.463 ThaliTest[383:160504] server: disconnecting to refresh session (1449510507109.408)
2015-12-07 18:48:33.463 ThaliTest[383:,160504] server session: disconnect
2015-12-07 18:48:33.463 ThaliTest[383:160504] server session: stateChange:2->0 1449510507109.408
,2015-12-07 18:48:33.468 ThaliTest[383:160504] server session: connect
2015-12-07 18:48:33.468 ThaliTest[383:160504] server session: stateChange:0->1 1449510507109.408
,2015-12-07 18:48:33.476 ThaliTest[383:160504] server: accepting invitation 1449510507109.408
,2015-12-07 18:48:33.490 ThaliTest[383:160504] client: relay established
2015-12-07 18:48:33.491 ThaliTest[383:160504] client: new accepted socket: 0x1b133230
,ok 121 the test messages should be equal
,ok 122 First send should succeed
,2015-12-07 18:48:33.528 ThaliTest[383:160504] client: socket closed
2015-12-07 18:48:33.528 ThaliTest[383:160504] client relay: socket disconnected
2015-12-07 18:48:33.528 ThaliTest[383:160504] client relay: 0x1b133230 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-07 18:48:33.529 ThaliTest[383:160504] client session: socket closed: 1449510507109.408.rby7cA==
2015-12-07 18:48:33.529 ThaliTest[383:160504] client session: onLinkFailure: 1449510507109.408.rby7cA==
2015-12-07 18:48:33.529 ThaliTest[383:160504] client session: disconnect
2015-12-07 18:48:33.529 ThaliTest[383:160504] client session: stateChange:2->0 1449510507109.408.,rby7cA==
,2015-12-07 18:48:33.532 ThaliTest[383:160504] client session: fireConnectionErrorEvent: 1449510507109.408.rby7cA==
,2015-12-07 18:48:33.534 ThaliTest[383:160759] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:33.535 ThaliTest[383:160759] client session: connect
2015-12-07 18:48:33.535 ThaliTest[383:160759] client session: stateChange:0->1 1449510507109.408.rby7cA==
,2015-12-07 18:48:33.696 ThaliTest[383:160979] client session: connected
2015-12-07 18:48:33.696 ThaliTest[383:160979] client session: stateChange:1->2 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:33.697 ThaliTest[383:161093] client session: fireConnectCallback: 1449510506165.416.wWLXyQ==
2015-12-07 18:48:33.697 ThaliTest[383:161093] jxcore: connect: success
,2015-12-07 18:48:33.979 ThaliTest[383:160759] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:33.979 ThaliTest[383:160759] client: already connect(ing/ed) to 1449510507109.408.rby7cA==
2015-12-07 18:48:33.979 ThaliTest[383:160759] jxcore: connect: fail: Aleady connecting
2015-12-07 18:48:33.980 ThaliTest[383:160759] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:33.980 ThaliTest[383:160759] client: already connect(ing/ed) to 1449510507109.408.rby7cA==
2015-12-07 18:48:33.980 ThaliTest[383:160759] jxcore: connect: fail: Aleady connecting
,ok 123 Should be able to connect without error
,ok 124 Port should be within range
,ok 125 Second connect should succeed
,2015-12-07 18:48:33.993 ThaliTest[383:160504] client: relay established
2015-12-07 18:48:33.993 ThaliTest[383:160504] client: new accepted socket: 0x1b11bb60
,2015-12-07 18:48:34.174 ThaliTest[383:160759] jxcore: connect 1449510506999.375.Lduuig==
,2015-12-07 18:48:34.175 ThaliTest[383:160759] client: already connect(ing/ed) to 1449510506999.375.Lduuig==
,2015-12-07 18:48:34.175 ThaliTest[383:160759] jxcore: connect: fail: Aleady connecting
,ok 126 the test messages should be equal
,ok 127 Second send should succeed
,# setup
,2015-12-07 18:48:34.198 ThaliTest[383:160504] client: socket closed
,2015-12-07 18:48:34.198 ThaliTest[383:160504] client relay: socket disconnected
,2015-12-07 18:48:34.198 ThaliTest[383:160504] client relay: 0x1b11bb60 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-07 18:48:34.199 ThaliTest[383:160504] client session: socket closed: 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:34.199 ThaliTest[383:160504] client session: onLinkFailure: 1449510506165.416.wWLXyQ==
2015-12-07 18:48:34.199 ThaliTest[383:160504] client session: disconnect
,2015-12-07 18:48:34.200 ThaliTest[383:160504] client session: stateChange:2->0 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:34.210 ThaliTest[383:160504] client session: fireConnectionErrorEvent: 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:34.366 ThaliTest[383:160980] server session: connected
2015-12-07 18:48:34.366 ThaliTest[383:160980] server session: stateChange:1->2 1449510506999.375
,2015-12-07 18:48:34.372 ThaliTest[383:160504] server relay: connected (to port: 5001)
,2015-12-07 18:48:34.703 ThaliTest[383:161059] server session: connected
2015-12-07 18:48:34.703 ThaliTest[383:161059] server session: stateChange:1->2 1449510506165.416
,2015-12-07 18:48:34.720 ThaliTest[383:160504] server relay: connected (to port: 5001)
,2015-12-07 18:48:34.986 ThaliTest[383:160759] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:34.987 ThaliTest[383:160759] client: already connect(ing/ed) to 1449510507109.408.rby7cA==
,2015-12-07 18:48:34.988 ThaliTest[383:160759] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:34.989 ThaliTest[383:160759] jxcore: connect 1449510507109.408.rby7cA==
,2015-12-07 18:48:34.990 ThaliTest[383:160759] client: already connect(ing/ed) to 1449510507109.408.rby7cA==
,2015-12-07 18:48:34.990 ThaliTest[383:160759] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:35.021 ThaliTest[383:161059] server session: not connected 1449510506165.416
,2015-12-07 18:48:35.188 ThaliTest[383:160759] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:35.188 ThaliTest[383:160759] client: already connect(ing/ed) to 1449510506999.375.Lduuig==
2015-12-07 18:48:35.189 ThaliTest[383:160759] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:35.285 ThaliTest[383:161058] server session: not connected 1449510506999.375
,2015-12-07 18:48:35.995 ThaliTest[383:160759] jxcore: connect 1449510507109.408.rby7cA==
,2015-12-07 18:48:35.996 ThaliTest[383:160759] client: already connect(ing/ed) to 1449510507109.408.rby7cA==
2015-12-07 18:48:35.996 ThaliTest[383:160759] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:35.998 ThaliTest[383:160759] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:35.998 ThaliTest[383:160759] client: already connect(ing/ed) to 1449510507109.408.rby7cA==
2015-12-07 18:48:35.998 ThaliTest[383:160759] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:36.191 ThaliTest[383:160759] jxcore: connect 1449510506999.375.Lduuig==
,2015-12-07 18:48:36.192 ThaliTest[383:160759] client: already connect(ing/ed) to 1449510506999.375.Lduuig==
,2015-12-07 18:48:36.192 ThaliTest[383:160759] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:36.210 ThaliTest[383:161058] client session: connected
,2015-12-07 18:48:36.211 ThaliTest[383:161058] client session: stateChange:1->2 1449510506999.375.Lduuig==
,2015-12-07 18:48:36.218 ThaliTest[383:161059] server session: connected
,2015-12-07 18:48:36.220 ThaliTest[383:161059] server session: stateChange:1->2 1449510507109.408
,2015-12-07 18:48:36.222 ThaliTest[383:161058] client session: fireConnectCallback: 1449510506999.375.Lduuig==
2015-12-07 18:48:36.222 ThaliTest[383:161058] jxcore: connect: success
,ok 128 Should be able to connect without error
,ok 129 Port should be within range
,ok 130 Second connect should succeed
,2015-12-07 18:48:36.248 ThaliTest[383:160504] client: relay established
2015-12-07 18:48:36.249 ThaliTest[383:160504] client: new accepted socket: 0x1b129510
,2015-12-07 18:48:36.261 ThaliTest[383:160504] server relay: connected (to port: 5001)
,ok 131 the test messages should be equal
,ok 132 Second send should succeed
,not ok 133 .end() called twice
,  ---
,    operator: fail
,  ...
,2015-12-07 18:48:36.348 ThaliTest[383:160504] client: socket closed
2015-12-07 18:48:36.348 ThaliTest[383:160504] client relay: socket disconnected
,2015-12-07 18:48:36.349 ThaliTest[383:160504] client relay: 0x1b129510 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-07 18:48:36.349 ThaliTest[383:160504] client session: socket closed: 1449510506999.375.Lduuig==
,2015-12-07 18:48:36.349 ThaliTest[383:160504] client session: onLinkFailure: 1449510506999.375.Lduuig==
2015-12-07 18:48:36.350 ThaliTest[383:160504] client session: disconnect
,2015-12-07 18:48:36.350 ThaliTest[383:160504] client session: stateChange:2->0 1449510506999.375.Lduuig==
,2015-12-07 18:48:36.359 ThaliTest[383:160504] client session: fireConnectionErrorEvent: 1449510506999.375.Lduuig==
,2015-12-07 18:48:36.595 ThaliTest[383:161058] server session: not connected 1449510507109.408
,2015-12-07 18:48:37.004 ThaliTest[383:160759] jxcore: connect 1449510507109.408.rby7cA==
,2015-12-07 18:48:37.005 ThaliTest[383:160759] client: already connect(ing/ed) to 1449510507109.408.rby7cA==
,2015-12-07 18:48:37.005 ThaliTest[383:160759] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:37.007 ThaliTest[383:160759] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:37.008 ThaliTest[383:160759] client: already connect(ing/ed) to 1449510507109.408.rby7cA==
2015-12-07 18:48:37.008 ThaliTest[383:160759] jxcore: con,nect: fail: Aleady connecting
,calling stopBroadcasting
,2015-12-07 18:48:37.142 ThaliTest[383:160759] jxcore: stopBroadcasting
,2015-12-07 18:48:37.142 ThaliTest[383:160759] THEMultipeerSession stopping peer
,2015-12-07 18:48:37.143 ThaliTest[383:160759] multipeer session: stop timer
,2015-12-07 18:48:37.143 ThaliTest[383:160759] client session: disconnect
2015-12-07 18:48:37.144 ThaliTest[383:160759] client session: stateChange:1->0 1449510507109.408.rby7cA==
,2015-12-07 18:48:37.153 ThaliTest[383:160759] server session: disconnect
2015-12-07 18:48:37.153 ThaliTest[383:160759] server session: stateChange:2->0 1449510506999.375
,2015-12-07 18:48:37.161 ThaliTest[383:160759] server session: disconnect
2015-12-07 18:48:37.162 ThaliTest[383:160759] server session: stateChange:2->0 1449510506165.416
,2015-12-07 18:48:37.174 ThaliTest[383:160759] server session: disconnect
2015-12-07 18:48:37.175 ThaliTest[383:160759] server session: stateChange:2->0 1449510507109.408
,2015-12-07 18:48:37.185 ThaliTest[383:160759] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliReplicationManager can call start without error
,2015-12-07 18:48:37.201 ThaliTest[383:160759] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:37.201 ThaliTest[383:160759] Communications not enabled
,2015-12-07 18:48:37.202 ThaliTest[383:160759] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:38.011 ThaliTest[383:160759] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:38.011 ThaliTest[383:160759] Communications not enabled
,2015-12-07 18:48:38.011 ThaliTest[383:160759] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:38.013 ThaliTest[383:160759] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:38.014 ThaliTest[383:160759] Communications not enabled
2015-12-07 18:48:38.014 ThaliTest[383:160759] jxcore: connect: fail: app: Not initialised
,# teardown
,2015-12-07 18:48:38.213 ThaliTest[383:160759] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:38.214 ThaliTest[383:160759] Communications not enabled
,2015-12-07 18:48:38.214 ThaliTest[383:160759] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:39.024 ThaliTest[383:160759] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:39.025 ThaliTest[383:160759] Communications not enabled
,2015-12-07 18:48:39.025 ThaliTest[383:160759] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:39.027 ThaliTest[383:160759] jxcore: connect 1449510507109.408.rby7cA==
,2015-12-07 18:48:39.028 ThaliTest[383:160759] Communications not enabled
,2015-12-07 18:48:39.028 ThaliTest[383:160759] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:39.216 ThaliTest[383:160759] jxcore: connect 1449510506999.375.Lduuig==
,2015-12-07 18:48:39.217 ThaliTest[383:160759] Communications not enabled
,2015-12-07 18:48:39.217 ThaliTest[383:160759] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:40.033 ThaliTest[383:160759] jxcore: connect 1449510507109.408.rby7cA==
,2015-12-07 18:48:40.033 ThaliTest[383:160759] Communications not enabled
,2015-12-07 18:48:40.034 ThaliTest[383:160759] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:40.036 ThaliTest[383:160759] jxcore: connect 1449510507109.408.rby7cA==
,2015-12-07 18:48:40.036 ThaliTest[383:160759] Communications not enabled
2015-12-07 18:48:40.036 ThaliTest[383:160759] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:40.224 ThaliTest[383:160759] jxcore: connect 1449510506999.375.Lduuig==
,2015-12-07 18:48:40.225 ThaliTest[383:160759] Communications not enabled
,2015-12-07 18:48:40.225 ThaliTest[383:160759] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:41.040 ThaliTest[383:160759] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:41.041 ThaliTest[383:160759] Communications not enabled
,2015-12-07 18:48:41.041 ThaliTest[383:160759] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:41.043 ThaliTest[383:160759] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:41.043 ThaliTest[383:160759] Communications not enabled
,2015-12-07 18:48:41.044 ThaliTest[383:160759] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:41.230 ThaliTest[383:160759] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:41.231 ThaliTest[383:160759] Communications not enabled
,2015-12-07 18:48:41.231 ThaliTest[383:160759] jxcore: connect: fail: app: Not initialised
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/3E9960A1-0E1E-43AE-BD1F-927F296E19F1/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 134 starting event should occur in right order
,2015-12-07 18:48:41.824 ThaliTest[383:160759] jxcore: startBroadcasting
,2015-12-07 18:48:41.826 ThaliTest[383:160759] server: starting LvPO_qZC-PBObxHMANGJuw.Bkw2xg==
,2015-12-07 18:48:41.827 ThaliTest[383:160759] multipeer session: start timer: 0x1b133230
,2015-12-07 18:48:41.827 ThaliTest[383:160759] THEMultipeerSession initialized peer LvPO_qZC-PBObxHMANGJuw
2015-12-07 18:48:41.828 ThaliTest[383:160759] jxcore: startBroadcasting: success
ok 135 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
,ok 136 stopping event should occur in right order
About to call stopBroadcasting
,2015-12-07 18:48:41.831 ThaliTest[383:160759] jxcore: stopBroadcasting
,2015-12-07 18:48:41.831 ThaliTest[383:160759] THEMultipeerSession stopping peer
,2015-12-07 18:48:41.832 ThaliTest[383:160759] multipeer session: stop timer
,2015-12-07 18:48:41.832 ThaliTest[383:160759] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,ok 137 stopped event should occur in right order
,mux server bridge listener closed
,# setup
,2015-12-07 18:48:42.055 ThaliTest[383:160759] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:42.055 ThaliTest[383:160759] Communications not enabled
,2015-12-07 18:48:42.056 ThaliTest[383:160759] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:42.057 ThaliTest[383:160759] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:42.058 ThaliTest[383:160759] Communications not enabled
,2015-12-07 18:48:42.058 ThaliTest[383:160759] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:42.236 ThaliTest[383:160759] jxcore: connect 1449510506999.375.Lduuig==
,2015-12-07 18:48:42.236 ThaliTest[383:160759] Communications not enabled
,2015-12-07 18:48:42.237 ThaliTest[383:160759] jxcore: connect: fail: app: Not initialised
,# ThaliReplicationManager receives identity
,2015-12-07 18:48:43.069 ThaliTest[383:160759] jxcore: connect 1449510507109.408.rby7cA==
,2015-12-07 18:48:43.069 ThaliTest[383:160759] Communications not enabled
2015-12-07 18:48:43.070 ThaliTest[383:160759] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:43.071 ThaliTest[383:160759] jxcore: connect 1449510507109.408.rby7cA==
,2015-12-07 18:48:43.071 ThaliTest[383:160759] Communications not enabled
,2015-12-07 18:48:43.072 ThaliTest[383:160759] jxcore: connect: fail: app: Not initialised
,not ok 138 Second connect should succeed
  ---
,    operator: ok
,    expected: true
,    actual:   false
,  ...
,2015-12-07 18:48:43.283 ThaliTest[383:160759] Error!: connect EADDRNOTAVAIL
Stack:[{"_fileName":"net.js","_functionName":"errnoException","_lineNumber":"835","_columnNumber":"11","_msg":"    at errnoException@net.js:835:11"},{"_fileName":"net.js","_functi,onName":"connect","_lineNumber":"707","_columnNumber":"19","_msg":"    at connect@net.js:707:19"},{"_fileName":"net.js","_functionName":"Socket.prototype.connect","_lineNumber":"756","_columnNumber":"5","_msg":"    at Socket.prototype.connect@net.js:756:5"},{"_fileName":"net.js","_functionName":"exports.createConnection","_lineNumber":"72","_columnNumber":"10","_msg":"    at exports.createConnection@net.js:72:10"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/FF01275C-18A2-4BDF-BA14-1E2528,A9D071/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"sendData","_lineNumber":"277","_columnNumber":"24","_msg":"    at sendData@/private/var/mobile/Containers/Bundle/Application/FF01275C-18A2-4BDF-BA14-1E2528A9D071/ThaliTest.a,pp/www/jxcore/bv_tests/testThaliNativeLayer.js:277:24"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/FF01275C-18A2-4BDF-BA14-1E2528A9D071/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"","_lineNumber":"325",",_columnNumber":"17","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/FF01275C-18A2-4BDF-BA14-1E2528A9D071/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:325:17"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/FF,01275C-18A2-4BDF-BA14-1E2528A9D071/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"connectWithRetry/connectToPeer","_lineNumber":"251","_columnNumber":"9","_msg":"    at connectWithRetry/connectToPeer@/private/var/mobile/Contain,ers/Bundle/Application/FF01275C-18A2-4BDF-BA14-1E2528A9D071/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:251:9"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/FF01275C-18A2-4BDF-BA14-1E2528A9D071/ThaliTest.app/www/jxcore/bv_t,ests/testThaliNativeLayer.js","_functionName":"connectWithRetry/connectToPeer/</<","_lineNumber":"260","_columnNumber":"45","_msg":"    at connectWithRetry/connectToPeer/</<@/private/var/mobile/Containers/Bundle/Application/FF01275C-18A2-4BDF-BA14-1E2528A9,D071/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:260:45"},{"_fileName":"timers.js","_functionName":"listOnTimeout","_lineNumber":"112","_columnNumber":"9","_msg":"    at listOnTimeout@timers.js:112:9"},{"_fileName":"net.js","_functionName":"u,nknown","_lineNumber":835,"_columnNumber":10,"_msg":"    at "}]
Uncaught Exception: Error: connect EADDRNOTAVAIL
,[ { _fileName: 'net.js',
    _functionName: 'errnoException',
    _lineNumber: '835',
    _columnNumber: '11',
    _msg: '    at errnoException@net.js:835:11' },
  { _fileName: 'net.js',
    _functionName: 'connect',
    _lineNumber: '707',
    _co,lumnNumber: '19',
    _msg: '    at connect@net.js:707:19' },
  { _fileName: 'net.js',
    _functionName: 'Socket.prototype.connect',
    _lineNumber: '756',
    _columnNumber: '5',
    _msg: '    at Socket.prototype.connect@net.js:756:5' },
  { _fi,leName: 'net.js',
    _functionName: 'exports.createConnection',
    _lineNumber: '72',
    _columnNumber: '10',
    _msg: '    at exports.createConnection@net.js:72:10' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/FF01275C-18A,2-4BDF-BA14-1E2528A9D071/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: 'sendData',
    _lineNumber: '277',
    _columnNumber: '24',
    _msg: '    at sendData@/private/var/mobile/Containers/Bundle/Application/FF01275C-18A2-4BDF-BA14-1E2528A9D071/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:277:24' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/FF01275C-18A2-4BDF-BA14-1E2528A9D071/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.j,s',
    _functionName: '',
    _lineNumber: '325',
    _columnNumber: '17',
    _msg: '    at @/private/var/mobile/Containers/Bundle/Application/FF01275C-18A2-4BDF-BA14-1E2528A9D071/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:325:17' },
,  { _fileName: '/private/var/mobile/Containers/Bundle/Application/FF01275C-18A2-4BDF-BA14-1E2528A9D071/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: 'connectWithRetry/connectToPeer',
    _lineNumber: '251',
    _columnNu,mber: '9',
    _msg: '    at connectWithRetry/connectToPeer@/private/var/mobile/Containers/Bundle/Application/FF01275C-18A2-4BDF-BA14-1E2528A9D071/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:251:9' },
  { _fileName: '/private/var/mobile/Con,tainers/Bundle/Application/FF01275C-18A2-4BDF-BA14-1E2528A9D071/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: 'connectWithRetry/connectToPeer/</<',
    _lineNumber: '260',
    _columnNumber: '45',
    _msg: '    at conn,ectWithRetry/connectToPeer/</<@/private/var/mobile/Containers/Bundle/Application/FF01275C-18A2-4BDF-BA14-1E2528A9D071/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:260:45' },
  { _fileName: 'timers.js',
    _functionName: 'listOnTimeout',
  ,  _lineNumber: '112',
    _columnNumber: '9',
    _msg: '    at listOnTimeout@timers.js:112:9' },
  { _fileName: 'net.js',
    _functionName: 'unknown',
    _lineNumber: 835,
    _columnNumber: 10,
    _msg: '    at ' },
  toString: [Function] ]
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
