#### Test 584164489c56086_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/584164489c56086/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/705B5316-FCC4-4C41-AF17-07C71B8042E2/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/705B5316-FCC4-4C41-AF17-07C71B8042E2/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/584164489c56086/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/584164489c56086/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A29BD389-B36A-4CCC-B63C-4126EA8BE32E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52746"
,(lldb)     command script import "/tmp/705B5316-FCC4-4C41-AF17-07C71B8042E2/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 10:18:53.909 ThaliTest[1582:2930534] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E60A4EBB-DF2F-459A-AB72-E2A61C1D71AA/Library/Cookies/Cookies.binarycookies
,2016-02-09 10:18:54.460 ThaliTest[1582:2930534] Apache Cordova native platform version 4.0.1 is starting.
,2016-02-09 10:18:54.462 ThaliTest[1582:2930534] Multi-tasking -> Device: YES, App: YES
,2016-02-09 10:18:54.489 ThaliTest[1582:2930534] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 10:18:56.539 ThaliTest[1582:2930534] Using UIWebView
,2016-02-09 10:18:56.552 ThaliTest[1582:2930534] [CDVTimer][handleopenurl] 0.416994ms
,2016-02-09 10:18:56.560 ThaliTest[1582:2930534] [CDVTimer][intentandnavigationfilter] 8.002043ms
2016-02-09 10:18:56.561 ThaliTest[1582:2930534] [CDVTimer][gesturehandler] 0.373006ms
2016-02-09 10:18:56.562 ThaliTest[1582:2930534] [CDVTimer][TotalPluginS,tartup] 10.556996ms
,2016-02-09 10:19:04.550 ThaliTest[1582:2930534] Resetting plugins due to page load.
,2016-02-09 10:19:07.444 ThaliTest[1582:2930534] Finished load of: file:///var/mobile/Containers/Bundle/Application/A29BD389-B36A-4CCC-B63C-4126EA8BE32E/ThaliTest.app/www/index.html
,2016-02-09 10:19:07.681 ThaliTest[1582:2930534] JXcore Cordova plugin initializing
2016-02-09 10:19:07.684 ThaliTest[1582:2930855] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A29BD389-B36A-4CCC-B63C-4126EA8BE32E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A29BD389-B36A-4CCC-B63C-4126EA8BE32E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A29BD389-B36A-4CCC-B63C-4126EA8BE32E/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A29BD389-B36A-4CCC-B63C-4126EA8BE32E/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A29BD389-B36A-4CCC-B63C-4126EA8BE32E/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A29BD389-B36A-4CCC-B63C-4126EA8BE32E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A29BD389-B36A-4CCC-B63C-4126EA8BE32E/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A29BD389-B36A-4CCC-B63C-4126EA8BE32E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A29BD389-B36A-4CCC-B63C-4126EA8BE32E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,ok 7 secondPromise testValue

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

,ok 15 (unnamed assert)

,ok 16 should be equal

,ok 17 should not throw

# setup

,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 18 (unnamed assert)

,ok 19 (unnamed assert)

,ok 20 should not throw

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

,ok 26 should be equal

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

,# setup

,# #startBroadcasting should throw on too large port

,# teardown

,ok 34 should throw

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,# teardown

,ok 35 should be equal

,ok 36 should be equal

,ok 37 should be equal

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,# teardown

,ok 38 should be equal

,ok 39 should be equal

,ok 40 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,# teardown

,ok 41 should be equal

,ok 42 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,# teardown

,ok 43 should be equal

,ok 44 should be equal

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,# teardown

,ok 45 should be equal

,ok 46 should be equal

,ok 47 should be equal

,# setup

,# #connect should call Mobile("Connect") and handle an error

,# teardown

,ok 48 should be equal

,ok 49 should be equal

,# setup

,# should call Mobile("Disconnect") without an error

,# teardown

,ok 50 should be equal

,ok 51 should be equal

,# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 52 should be equal

,ok 53 should be equal

,# setup

,# #start should fail if called twice in a row

,# teardown

,ok 54 specific error should be received

,# setup

,# #startListeningForAdvertisements should fail if start not called

,# teardown

,ok 55 specific error should be returned

,# setup

,# should be able to call #stopListeningForAdvertisements many times

,# teardown

,ok 56 error should be null

,ok 57 error should be null

,# setup

,# should be able to call #startListeningForAdvertisements many times

,# teardown

,ok 58 error should be null

,ok 59 error should be null

,# setup

,# should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,ok 60 error should be null

,ok 61 error should be null

,# setup

,# #startUpdateAdvertisingAndListening should fail if start not called

,# teardown

,ok 62 specific error should be returned

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-02-09 10:23:45.163 ThaliTest[1582:2930855] jxcore: startBroadcasting
,2016-02-09 10:23:45.178 ThaliTest[1582:2930855] server: starting 1455009825162.1582.wRrN9g==
,2016-02-09 10:23:45.179 ThaliTest[1582:2930855] multipeer session: start timer: 0x17658d50
2016-02-09 10:23:45.180 ThaliTest[1582:2930855] THEMultipeerSession initialized peer 1455009825162.1582
2016-02-09 10:23:45.180 ThaliTest[1582:2930855] jxcore: sta,rtBroadcasting: success
ok 63 Should be able to call startBroadcasting without error

2016-02-09 10:23:45.184 ThaliTest[1582:2930855] jxcore: stopBroadcasting
2016-02-09 10:23:45.184 ThaliTest[1582:2930855] THEMultipeerSession stopping peer
2016-02-09, 10:23:45.185 ThaliTest[1582:2930855] multipeer session: stop timer
2016-02-09 10:23:45.185 ThaliTest[1582:2930855] jxcore: stopBroadcasting: success
ok 64 Should be able to call stopBroadcasting without error

2016-02-09 10:23:45.187 ThaliTest[1582:2930855] jxcore: startBroadcasting
,2016-02-09 10:23:45.192 ThaliTest[1582:2930855] server: starting 1455009825186.1582.X4aVhQ==
,2016-02-09 10:23:45.194 ThaliTest[1582:2930855] multipeer session: start timer: 0x1765c7b0
2016-02-09 10:23:45.195 ThaliTest[1582:2930855] THEMultipeerSession initialized peer 1455009825186.1582
2016-02-09 10:23:45.196 ThaliTest[1582:2930855] jxcore: sta,rtBroadcasting: success
ok 65 Should be able to call startBroadcasting without error

2016-02-09 10:23:45.198 ThaliTest[1582:2930855] jxcore: stopBroadcasting
2016-02-09 10:23:45.199 ThaliTest[1582:2930855] THEMultipeerSession stopping peer
2016-02-09, 10:23:45.199 ThaliTest[1582:2930855] multipeer session: stop timer
2016-02-09 10:23:45.199 ThaliTest[1582:2930855] jxcore: stopBroadcasting: success
ok 66 Should be able to call stopBroadcasting without error

2016-02-09 10:23:45.201 ThaliTest[1582:2930855] jxcore: startBroadcasting
,2016-02-09 10:23:45.223 ThaliTest[1582:2930855] server: starting 1455009825201.1582.n+xpqA==
,2016-02-09 10:23:45.229 ThaliTest[1582:2930855] multipeer session: start timer: 0x167f19f0
,2016-02-09 10:23:45.237 ThaliTest[1582:2930855] THEMultipeerSession initialized peer 1455009825201.1582
,2016-02-09 10:23:45.238 ThaliTest[1582:2930855] jxcore: startBroadcasting: success
,ok 67 Should be able to call startBroadcasting without error

,2016-02-09 10:23:45.242 ThaliTest[1582:2930855] jxcore: stopBroadcasting
,2016-02-09 10:23:45.243 ThaliTest[1582:2930855] THEMultipeerSession stopping peer
,2016-02-09 10:23:45.244 ThaliTest[1582:2930855] multipeer session: stop timer
,2016-02-09 10:23:45.249 ThaliTest[1582:2930855] jxcore: stopBroadcasting: success
,ok 68 Should be able to call stopBroadcasting without error

,2016-02-09 10:23:45.253 ThaliTest[1582:2930855] jxcore: startBroadcasting
,2016-02-09 10:23:45.256 ThaliTest[1582:2930855] server: starting 1455009825252.1582.QkGnpQ==
,2016-02-09 10:23:45.262 ThaliTest[1582:2930855] multipeer session: start timer: 0x167f2540
,2016-02-09 10:23:45.265 ThaliTest[1582:2930855] THEMultipeerSession initialized peer 1455009825252.1582
,2016-02-09 10:23:45.266 ThaliTest[1582:2930855] jxcore: startBroadcasting: success
,ok 69 Should be able to call startBroadcasting without error

,2016-02-09 10:23:45.268 ThaliTest[1582:2930855] jxcore: stopBroadcasting
,2016-02-09 10:23:45.269 ThaliTest[1582:2930855] THEMultipeerSession stopping peer
,2016-02-09 10:23:45.270 ThaliTest[1582:2930855] multipeer session: stop timer
,2016-02-09 10:23:45.271 ThaliTest[1582:2930855] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error

,2016-02-09 10:23:45.276 ThaliTest[1582:2930855] jxcore: startBroadcasting
,2016-02-09 10:23:45.279 ThaliTest[1582:2930855] server: starting 1455009825276.1582.dNh79A==
,2016-02-09 10:23:45.283 ThaliTest[1582:2930855] multipeer session: start timer: 0x1765dd50
,2016-02-09 10:23:45.285 ThaliTest[1582:2930855] THEMultipeerSession initialized peer 1455009825276.1582
,2016-02-09 10:23:45.288 ThaliTest[1582:2930855] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error

,2016-02-09 10:23:45.290 ThaliTest[1582:2930855] jxcore: stopBroadcasting
,2016-02-09 10:23:45.291 ThaliTest[1582:2930855] THEMultipeerSession stopping peer
,2016-02-09 10:23:45.292 ThaliTest[1582:2930855] multipeer session: stop timer
,2016-02-09 10:23:45.296 ThaliTest[1582:2930855] jxcore: stopBroadcasting: success
,ok 72 Should be able to call stopBroadcasting without error

,2016-02-09 10:23:45.299 ThaliTest[1582:2930855] jxcore: startBroadcasting
,2016-02-09 10:23:45.301 ThaliTest[1582:2930855] server: starting 1455009825298.1582.OwHW8g==
,2016-02-09 10:23:45.304 ThaliTest[1582:2930855] multipeer session: start timer: 0x167543c0
,2016-02-09 10:23:45.308 ThaliTest[1582:2930855] THEMultipeerSession initialized peer 1455009825298.1582
,2016-02-09 10:23:45.310 ThaliTest[1582:2930855] jxcore: startBroadcasting: success
,ok 73 Should be able to call startBroadcasting without error

,2016-02-09 10:23:45.312 ThaliTest[1582:2930855] jxcore: stopBroadcasting
,2016-02-09 10:23:45.312 ThaliTest[1582:2930855] THEMultipeerSession stopping peer
,2016-02-09 10:23:45.314 ThaliTest[1582:2930855] multipeer session: stop timer
,2016-02-09 10:23:45.316 ThaliTest[1582:2930855] jxcore: stopBroadcasting: success
,ok 74 Should be able to call stopBroadcasting without error

,2016-02-09 10:23:45.320 ThaliTest[1582:2930855] jxcore: startBroadcasting
,2016-02-09 10:23:45.323 ThaliTest[1582:2930855] server: starting 1455009825320.1582.AuaGsg==
,2016-02-09 10:23:45.325 ThaliTest[1582:2930855] multipeer session: start timer: 0x167549c0
,2016-02-09 10:23:45.331 ThaliTest[1582:2930855] THEMultipeerSession initialized peer 1455009825320.1582
,2016-02-09 10:23:45.332 ThaliTest[1582:2930855] jxcore: startBroadcasting: success
,ok 75 Should be able to call startBroadcasting without error

,2016-02-09 10:23:45.334 ThaliTest[1582:2930855] jxcore: stopBroadcasting
,2016-02-09 10:23:45.335 ThaliTest[1582:2930855] THEMultipeerSession stopping peer
,2016-02-09 10:23:45.336 ThaliTest[1582:2930855] multipeer session: stop timer
,2016-02-09 10:23:45.337 ThaliTest[1582:2930855] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error
,
,2016-02-09 10:23:45.342 ThaliTest[1582:2930855] jxcore: startBroadcasting
,2016-02-09 10:23:45.344 ThaliTest[1582:2930855] server: starting 1455009825341.1582.AdeC1Q==
,2016-02-09 10:23:45.346 ThaliTest[1582:2930855] multipeer session: start timer: 0x16754f70
,2016-02-09 10:23:45.349 ThaliTest[1582:2930855] THEMultipeerSession initialized peer 1455009825341.1582
,2016-02-09 10:23:45.351 ThaliTest[1582:2930855] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

,2016-02-09 10:23:45.355 ThaliTest[1582:2930855] jxcore: stopBroadcasting
,2016-02-09 10:23:45.355 ThaliTest[1582:2930855] THEMultipeerSession stopping peer
,2016-02-09 10:23:45.356 ThaliTest[1582:2930855] multipeer session: stop timer
,2016-02-09 10:23:45.358 ThaliTest[1582:2930855] jxcore: stopBroadcasting: success
,ok 78 Should be able to call stopBroadcasting without error

,2016-02-09 10:23:45.361 ThaliTest[1582:2930855] jxcore: startBroadcasting
,2016-02-09 10:23:45.364 ThaliTest[1582:2930855] server: starting 1455009825361.1582.IQhdag==
,2016-02-09 10:23:45.365 ThaliTest[1582:2930855] multipeer session: start timer: 0x1765ef20
,2016-02-09 10:23:45.367 ThaliTest[1582:2930855] THEMultipeerSession initialized peer 1455009825361.1582
,2016-02-09 10:23:45.370 ThaliTest[1582:2930855] jxcore: startBroadcasting: success
,ok 79 Should be able to call startBroadcasting without error

,2016-02-09 10:23:45.372 ThaliTest[1582:2930855] jxcore: stopBroadcasting
,2016-02-09 10:23:45.373 ThaliTest[1582:2930855] THEMultipeerSession stopping peer
,2016-02-09 10:23:45.373 ThaliTest[1582:2930855] multipeer session: stop timer
,2016-02-09 10:23:45.374 ThaliTest[1582:2930855] jxcore: stopBroadcasting: success
,ok 80 Should be able to call stopBroadcasting without error

,2016-02-09 10:23:45.378 ThaliTest[1582:2930855] jxcore: startBroadcasting
,2016-02-09 10:23:45.380 ThaliTest[1582:2930855] server: starting 1455009825378.1582.kL2uoQ==
,2016-02-09 10:23:45.381 ThaliTest[1582:2930855] multipeer session: start timer: 0x16755c70
,2016-02-09 10:23:45.382 ThaliTest[1582:2930855] THEMultipeerSession initialized peer 1455009825378.1582
,2016-02-09 10:23:45.385 ThaliTest[1582:2930855] jxcore: startBroadcasting: success
,ok 81 Should be able to call startBroadcasting without error

,2016-02-09 10:23:45.388 ThaliTest[1582:2930855] jxcore: stopBroadcasting
,2016-02-09 10:23:45.389 ThaliTest[1582:2930855] THEMultipeerSession stopping peer
,2016-02-09 10:23:45.389 ThaliTest[1582:2930855] multipeer session: stop timer
,2016-02-09 10:23:45.392 ThaliTest[1582:2930855] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-09 10:23:45.562 ThaliTest[1582:2930855] jxcore: startBroadcasting
,2016-02-09 10:23:45.566 ThaliTest[1582:2930855] server: starting 1455009825561.1582.4B/+cw==
,2016-02-09 10:23:45.569 ThaliTest[1582:2930855] multipeer session: start timer: 0x16758550
,2016-02-09 10:23:45.577 ThaliTest[1582:2930855] THEMultipeerSession initialized peer 1455009825561.1582
,2016-02-09 10:23:45.578 ThaliTest[1582:2930855] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error

,2016-02-09 10:23:45.582 ThaliTest[1582:2930855] jxcore: startBroadcasting
,2016-02-09 10:23:45.584 ThaliTest[1582:2930855] jxcore: startBroadcasting: failure
,ok 84 Cannot call startBroadcasting twice

,2016-02-09 10:23:45.589 ThaliTest[1582:2930855] jxcore: stopBroadcasting
,2016-02-09 10:23:45.590 ThaliTest[1582:2930855] THEMultipeerSession stopping peer
,2016-02-09 10:23:45.592 ThaliTest[1582:2930855] multipeer session: stop timer
,2016-02-09 10:23:45.597 ThaliTest[1582:2930855] jxcore: stopBroadcasting: success
,ok 85 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-09 10:23:46.105 ThaliTest[1582:2930855] jxcore: startBroadcasting
,2016-02-09 10:23:46.109 ThaliTest[1582:2930855] server: starting 1455009826105.1582.NfMuMg==
2016-02-09 10:23:46.110 ThaliTest[1582:2930855] multipeer session: start timer: 0x176642e0
2016-02-09 10:23:46.110 ThaliTest[1582:2930855] THEMultipeerSession in,itialized peer 1455009826105.1582
2016-02-09 10:23:46.110 ThaliTest[1582:2930855] jxcore: startBroadcasting: success
ok 86 Should be able to call startBroadcasting without error

2016-02-09 10:23:46.113 ThaliTest[1582:2930855] jxcore: connect foobar
2,016-02-09 10:23:46.113 ThaliTest[1582:2930855] client: unknown peer foobar
2016-02-09 10:23:46.114 ThaliTest[1582:2930855] jxcore: connect: fail: Unknown peer
,ok 87 Should not connect to a bad peer

2016-02-09 10:23:46.119 ThaliTest[1582:2930855] jxcore: stopBroadcasting
2016-02-09 10:23:46.120 ThaliTest[1582:2930855] THEMultipeerSession stopping peer
2016-02-09 10:23:46.120 ThaliTest[1582:2930855] multipeer, session: stop timer
2016-02-09 10:23:46.120 ThaliTest[1582:2930855] jxcore: stopBroadcasting: success
ok 88 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-09 10:23:46.569 ThaliTest[1582:2930855] jxcore: startBroadcasting
,2016-02-09 10:23:46.573 ThaliTest[1582:2930855] server: starting 1455009826569.1582.FZy3iQ==
2016-02-09 10:23:46.574 ThaliTest[1582:2930855] multipeer session: start timer: 0x1670dfc0
2016-02-09 10:23:46.574 ThaliTest[1582:2930855] THEMultipeerSession in,itialized peer 1455009826569.1582
2016-02-09 10:23:46.575 ThaliTest[1582:2930855] jxcore: startBroadcasting: success
ok 89 Should be able to call startBroadcasting without error

,2016-02-09 10:23:46.577 ThaliTest[1582:2930855] jxcore: disconnect
,2016-02-09 10:23:46.578 ThaliTest[1582:2930855] jxcore: disconnect: fail
,ok 90 Disconnect should fail to a non-existant peer 

2016-02-09 10:23:46.582 ThaliTest[1582:2930855] jxcore: stopBroadcasting
2016-02-09 10:23:46.583 ThaliTest[1582:2930855] THEMultipeerSession stopping peer
2016-02-09 10:23:46.583 ThaliTest[1582:2930,855] multipeer session: stop timer
2016-02-09 10:23:46.583 ThaliTest[1582:2930855] jxcore: stopBroadcasting: success
ok 91 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-09 10:23:47.083 ThaliTest[1582:2930855] jxcore: startBroadcasting
,2016-02-09 10:23:47.087 ThaliTest[1582:2930855] server: starting 1455009827083.1582.o+ApXQ==
2016-02-09 10:23:47.087 ThaliTest[1582:2930855] multipeer session: start timer: 0x170837a0
2016-02-09 10:23:47.088 ThaliTest[1582:2930855] THEMultipeerSession in,itialized peer 1455009827083.1582
2016-02-09 10:23:47.088 ThaliTest[1582:2930855] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-09 10:23:47.895 ThaliTest[1582:2930534] client: found peer: 1455009828331.1052.2k96ig==
2016-02-09 10:23:47.898 ThaliTest[1582:2930855] jxcore: connect 1455009828331.1052.2k96ig==
2016-02-09 10:23:47.899 ThaliTest[1582:2930855] client session: co,nnect
2016-02-09 10:23:47.900 ThaliTest[1582:2930855] client session: stateChange:0->1 1455009828331.1052.2k96ig==
,2016-02-09 10:23:48.554 ThaliTest[1582:2930534] multipeer session: reset timer
2016-02-09 10:23:48.554 ThaliTest[1582:2930534] multipeer session: stop timer
2016-02-09 10:23:48.554 ThaliTest[1582:2930534] multipeer session: start timer: 0x170837a0
2016-,02-09 10:23:48.555 ThaliTest[1582:2930534] server session: connect
2016-02-09 10:23:48.555 ThaliTest[1582:2930534] server session: stateChange:0->1 1455009828331.1052
,2016-02-09 10:23:48.564 ThaliTest[1582:2930534] server: accepting invitation 1455009828331.1052
,2016-02-09 10:23:50.922 ThaliTest[1582:2931349] client session: connected
2016-02-09 10:23:50.922 ThaliTest[1582:2931349] client session: stateChange:1->2 1455009828331.1052.2k96ig==
,2016-02-09 10:23:50.941 ThaliTest[1582:2931343] client session: fireConnectCallback: 1455009828331.1052.2k96ig==
2016-02-09 10:23:50.942 ThaliTest[1582:2931343] jxcore: connect: success
,ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-09 10:23:50.947 ThaliTest[1582:2930855] jxcore: disconnect
2016-02-09 10:23:50.948 ThaliTest[1582:2930855] client session: disconnectFromPeer: 1455009828331.1052.2k96ig==
2016-02-09 10:23:50.948 ThaliTest[1582:2930855] client session: disconnect,
,2016-02-09 10:23:50.949 ThaliTest[1582:2930855] client session: stateChange:2->0 1455009828331.1052.2k96ig==
,2016-02-09 10:23:50.961 ThaliTest[1582:2930855] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 10:23:51.050 ThaliTest[1582:2931348] server session: connected
,2016-02-09 10:23:51.051 ThaliTest[1582:2931348] server session: stateChange:1->2 1455009828331.1052
,2016-02-09 10:23:51.065 ThaliTest[1582:2930534] server relay: socket disconnected
,2016-02-09 10:23:51.065 ThaliTest[1582:2930534] server relay: 0x17035920 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 10:23:51.106 ThaliTest[1582:2931349] server session: not connected 1455009828331.1052
,calling stopBroadcasting

,2016-02-09 10:23:51.312 ThaliTest[1582:2930855] jxcore: stopBroadcasting
2016-02-09 10:23:51.313 ThaliTest[1582:2930855] THEMultipeerSession stopping peer
2016-02-09 10:23:51.313 ThaliTest[1582:2930855] multipeer session: stop timer
2016-02-09 10:23:51.,314 ThaliTest[1582:2930855] server session: disconnect
2016-02-09 10:23:51.314 ThaliTest[1582:2930855] server session: stateChange:2->0 1455009828331.1052
2016-02-09 10:23:51.315 ThaliTest[1582:2930855] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-09 10:23:51.387 ThaliTest[1582:2930855] jxcore: startBroadcasting
,2016-02-09 10:23:51.391 ThaliTest[1582:2930855] server: starting 1455009831386.1582.irKX/A==
,2016-02-09 10:23:51.394 ThaliTest[1582:2930855] multipeer session: start timer: 0x16271970
,2016-02-09 10:23:51.400 ThaliTest[1582:2930855] THEMultipeerSession initialized peer 1455009831386.1582
,2016-02-09 10:23:51.405 ThaliTest[1582:2930534] client: found peer: 1455009828331.1052.2k96ig==
,2016-02-09 10:23:51.408 ThaliTest[1582:2930855] jxcore: startBroadcasting: success
,ok 96 Should be able to call startBroadcasting without error

,2016-02-09 10:23:51.411 ThaliTest[1582:2930534] client: found peer: 1455009827083.1582.o+ApXQ==
,2016-02-09 10:23:51.414 ThaliTest[1582:2930855] jxcore: connect 1455009828331.1052.2k96ig==
,2016-02-09 10:23:51.416 ThaliTest[1582:2930855] client session: connect
,2016-02-09 10:23:51.417 ThaliTest[1582:2930855] client session: stateChange:0->1 1455009828331.1052.2k96ig==
,2016-02-09 10:23:51.675 ThaliTest[1582:2930855] jxcore: connect 1455009827083.1582.o+ApXQ==
2016-02-09 10:23:51.676 ThaliTest[1582:2930855] client session: connect
2016-02-09 10:23:51.676 ThaliTest[1582:2930855] client session: stateChange:0->1 1455009827083.1582.o+ApXQ==
,2016-02-09 10:23:52.461 ThaliTest[1582:2930534] client: lost peer: 1455009827083.1582.o+ApXQ==
2016-02-09 10:23:52.461 ThaliTest[1582:2930534] client session: onPeerLost: 1455009827083.1582.o+ApXQ==
2016-02-09 10:23:52.462 ThaliTest[1582:2930534] client ,session: onLinkFailure: 1455009827083.1582.o+ApXQ==
2016-02-09 10:23:52.462 ThaliTest[1582:2930534] client session: disconnect
2016-02-09 10:23:52.462 ThaliTest[1582:2930534] client session: stateChange:1->0 1455009827083.1582.o+ApXQ==
2016-02-09 10:23:,52.463 ThaliTest[1582:2930534] client session: fireConnectCallback: 1455009827083.1582.o+ApXQ==
2016-02-09 10:23:52.463 ThaliTest[1582:2930534] jxcore: connect: fail: Peer disconnected
,2016-02-09 10:23:52.484 ThaliTest[1582:2930534] client: found peer: 1455009832668.1052.O/6BBA==
,2016-02-09 10:23:52.487 ThaliTest[1582:2930855] jxcore: connect 1455009832668.1052.O/6BBA==
2016-02-09 10:23:52.487 ThaliTest[1582:2930855] client session: connect
2016-02-09 10:23:52.488 ThaliTest[1582:2930855] client session: stateChange:0->1 145500983,2668.1052.O/6BBA==
,2016-02-09 10:23:52.612 ThaliTest[1582:2930534] multipeer session: reset timer
2016-02-09 10:23:52.612 ThaliTest[1582:2930534] multipeer session: stop timer
2016-02-09 10:23:52.612 ThaliTest[1582:2930534] multipeer session: start timer: 0x16271970
2016-,02-09 10:23:52.613 ThaliTest[1582:2930534] server session: connect
2016-02-09 10:23:52.613 ThaliTest[1582:2930534] server session: stateChange:0->1 1455009832668.1052
2016-02-09 10:23:52.622 ThaliTest[1582:2930534] server: accepting invitation 1455009832668.1052
,2016-02-09 10:23:53.474 ThaliTest[1582:2930855] jxcore: connect 1455009827083.1582.o+ApXQ==
2016-02-09 10:23:53.475 ThaliTest[1582:2930855] client: connect: unreachable 1455009827083.1582.o+ApXQ==
2016-02-09 10:23:53.475 ThaliTest[1582:2930855] jxcore: connect: fail: Peer unreachable
,2016-02-09 10:23:55.039 ThaliTest[1582:2931347] client session: connected
,2016-02-09 10:23:55.039 ThaliTest[1582:2931347] client session: stateChange:1->2 1455009832668.1052.O/6BBA==
,2016-02-09 10:23:55.050 ThaliTest[1582:2931347] client session: fireConnectCallback: 1455009832668.1052.O/6BBA==
2016-02-09 10:23:55.050 ThaliTest[1582:2931347] jxcore: connect: success
,ok 97 Should be able to connect without error

,ok 98 Port should be within range

,2016-02-09 10:23:55.054 ThaliTest[1582:2930855] jxcore: connect 1455009832668.1052.O/6BBA==
,2016-02-09 10:23:55.055 ThaliTest[1582:2930855] client: already connect(ing/ed) to 1455009832668.1052.O/6BBA==
,2016-02-09 10:23:55.056 ThaliTest[1582:2930855] jxcore: connect: fail: Aleady connecting
,ok 99 Should fail on double connect

,2016-02-09 10:23:55.058 ThaliTest[1582:2930855] jxcore: disconnect
,2016-02-09 10:23:55.058 ThaliTest[1582:2930855] client session: disconnectFromPeer: 1455009832668.1052.O/6BBA==
,2016-02-09 10:23:55.059 ThaliTest[1582:2930855] client session: disconnect
,2016-02-09 10:23:55.059 ThaliTest[1582:2930855] client session: stateChange:2->0 1455009832668.1052.O/6BBA==
,2016-02-09 10:23:55.068 ThaliTest[1582:2930855] jxcore: disconnect: success
,ok 100 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 10:23:55.238 ThaliTest[1582:2931347] server session: connected
2016-02-09 10:23:55.238 ThaliTest[1582:2931347] server session: stateChange:1->2 1455009832668.1052
,2016-02-09 10:23:55.252 ThaliTest[1582:2930534] server relay: socket disconnected
2016-02-09 10:23:55.253 ThaliTest[1582:2930534] server relay: 0x176761c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 10:23:55.298 ThaliTest[1582:2931345] server session: not connected 1455009832668.1052
,calling stopBroadcasting

,2016-02-09 10:23:55.512 ThaliTest[1582:2930855] jxcore: stopBroadcasting
2016-02-09 10:23:55.512 ThaliTest[1582:2930855] THEMultipeerSession stopping peer
2016-02-09 10:23:55.512 ThaliTest[1582:2930855] multipeer session: stop timer
2016-02-09 10:23:55.,513 ThaliTest[1582:2930855] client session: disconnect
2016-02-09 10:23:55.513 ThaliTest[1582:2930855] client session: stateChange:1->0 1455009828331.1052.2k96ig==
2016-02-09 10:23:55.514 ThaliTest[1582:2930855] server session: disconnect
2016-02-09 10:,23:55.514 ThaliTest[1582:2930855] server session: stateChange:2->0 1455009832668.1052
2016-02-09 10:23:55.515 ThaliTest[1582:2930855] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-09 10:23:55.583 ThaliTest[1582:2930855] jxcore: startBroadcasting
,2016-02-09 10:23:55.585 ThaliTest[1582:2930855] server: starting 1455009835583.1582.JwZBEg==
,2016-02-09 10:23:55.586 ThaliTest[1582:2930855] multipeer session: start timer: 0x17677580
2016-02-09 10:23:55.586 ThaliTest[1582:2930855] THEMultipeerSession initialized peer 1455009835583.1582
2016-02-09 10:23:55.586 ThaliTest[1582:2930855] jxcore: startBroadcasting: success
ok 101 Should be able to call startBroadcasting without error

,2016-02-09 10:23:56.582 ThaliTest[1582:2930534] client: found peer: 1455009832668.1052.O/6BBA==
2016-02-09 10:23:56.583 ThaliTest[1582:2930855] jxcore: connect 1455009832668.1052.O/6BBA==
2016-02-09 10:23:56.584 ThaliTest[1582:2930855] client session: connect
2016-02-09 10:23:56.584 ThaliTest[1582:2930855] client session: stateChange:0->1 1455009832668.1052.O/6BBA==
,2016-02-09 10:23:57.297 ThaliTest[1582:2930534] client: found peer: 1455009836849.1052.KWL4Rg==
2016-02-09 10:23:57.298 ThaliTest[1582:2930855] jxcore: connect 1455009836849.1052.KWL4Rg==
2016-02-09 10:23:57.299 ThaliTest[1582:2930855] client session: co,nnect
2016-02-09 10:23:57.299 ThaliTest[1582:2930855] client session: stateChange:0->1 1455009836849.1052.KWL4Rg==
,2016-02-09 10:23:57.605 ThaliTest[1582:2930534] multipeer session: reset timer
2016-02-09 10:23:57.605 ThaliTest[1582:2930534] multipeer session: stop timer
2016-02-09 10:23:57.605 ThaliTest[1582:2930534] multipeer session: start timer: 0x17677580
,2016-02-09 10:23:57.606 ThaliTest[1582:2930534] server session: connect
2016-02-09 10:23:57.607 ThaliTest[1582:2930534] server session: stateChange:0->1 1455009836849.1052
2016-02-09 10:23:57.616 ThaliTest[1582:2930534] server: accepting invitation 1455009836849.1052
,2016-02-09 10:24:03.181 ThaliTest[1582:2931343] client session: connected
2016-02-09 10:24:03.181 ThaliTest[1582:2931343] client session: stateChange:1->2 1455009836849.1052.KWL4Rg==
,2016-02-09 10:24:03.192 ThaliTest[1582:2931348] client session: fireConnectCallback: 1455009836849.1052.KWL4Rg==
2016-02-09 10:24:03.192 ThaliTest[1582:2931348] jxcore: connect: success
ok 102 Should be able to connect without error

ok 103 Port should, be within range

2016-02-09 10:24:03.196 ThaliTest[1582:2930855] jxcore: disconnect
2016-02-09 10:24:03.196 ThaliTest[1582:2930855] client session: disconnectFromPeer: 1455009836849.1052.KWL4Rg==
2016-02-09 10:24:03.197 ThaliTest[1582:2930855] client ,session: disconnect
2016-02-09 10:24:03.197 ThaliTest[1582:2930855] client session: stateChange:2->0 1455009836849.1052.KWL4Rg==
,2016-02-09 10:24:03.213 ThaliTest[1582:2931343] server session: connected
2016-02-09 10:24:03.214 ThaliTest[1582:2931343] server session: stateChange:1->2 1455009836849.1052
,2016-02-09 10:24:03.225 ThaliTest[1582:2930534] server relay: socket disconnected
,2016-02-09 10:24:03.226 ThaliTest[1582:2930534] server relay: 0x172f6380 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 10:24:03.306 ThaliTest[1582:2930855] jxcore: disconnect: success
ok 104 Should be able to disconnect without error

,2016-02-09 10:24:03.309 ThaliTest[1582:2930855] jxcore: disconnect
2016-02-09 10:24:03.309 ThaliTest[1582:2930855] jxcore: disconnect: fail
,ok 105 Disconnect should fail 

,setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 10:24:03.801 ThaliTest[1582:2931347] server session: not connected 1455009836849.1052
,calling stopBroadcasting

,2016-02-09 10:24:04.770 ThaliTest[1582:2930855] jxcore: stopBroadcasting
2016-02-09 10:24:04.770 ThaliTest[1582:2930855] THEMultipeerSession stopping peer
2016-02-09 10:24:04.771 ThaliTest[1582:2930855] multipeer session: stop timer
2016-02-09 10:24:04.,771 ThaliTest[1582:2930855] client session: disconnect
2016-02-09 10:24:04.771 ThaliTest[1582:2930855] client session: stateChange:1->0 1455009832668.1052.O/6BBA==
2016-02-09 10:24:04.772 ThaliTest[1582:2930855] server session: disconnect
2016-02-09 10:,24:04.773 ThaliTest[1582:2930855] server session: stateChange:2->0 1455009836849.1052
2016-02-09 10:24:04.774 ThaliTest[1582:2930855] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 59337

,2016-02-09 10:24:05.488 ThaliTest[1582:2930855] jxcore: startBroadcasting
,2016-02-09 10:24:05.490 ThaliTest[1582:2930855] server: starting 1455009845488.1582.fZwK3w==
2016-02-09 10:24:05.490 ThaliTest[1582:2930855] multipeer session: start timer: 0x17083740
2016-02-09 10:24:05.491 ThaliTest[1582:2930855] THEMultipeerSession in,itialized peer 1455009845488.1582
2016-02-09 10:24:05.491 ThaliTest[1582:2930855] jxcore: startBroadcasting: success
ok 106 Should be able to call startBroadcasting without error

,2016-02-09 10:24:06.241 ThaliTest[1582:2930534] client: found peer: 1455009846703.1052.4yoxhg==
2016-02-09 10:24:06.243 ThaliTest[1582:2930855] jxcore: connect 1455009846703.1052.4yoxhg==
2016-02-09 10:24:06.243 ThaliTest[1582:2930855] client session: co,nnect
2016-02-09 10:24:06.243 ThaliTest[1582:2930855] client session: stateChange:0->1 1455009846703.1052.4yoxhg==
,2016-02-09 10:24:07.199 ThaliTest[1582:2930534] multipeer session: reset timer
2016-02-09 10:24:07.199 ThaliTest[1582:2930534] multipeer session: stop timer
2016-02-09 10:24:07.200 ThaliTest[1582:2930534] multipeer session: start timer: 0x17083740
2016-,02-09 10:24:07.200 ThaliTest[1582:2930534] server session: connect
2016-02-09 10:24:07.201 ThaliTest[1582:2930534] server session: stateChange:0->1 1455009846703.1052
,2016-02-09 10:24:07.213 ThaliTest[1582:2930534] server: accepting invitation 1455009846703.1052
,2016-02-09 10:24:11.632 ThaliTest[1582:2931348] server session: connected
,2016-02-09 10:24:11.633 ThaliTest[1582:2931348] server session: stateChange:1->2 1455009846703.1052
,2016-02-09 10:24:11.679 ThaliTest[1582:2931343] client session: connected
2016-02-09 10:24:11.680 ThaliTest[1582:2931343] client session: stateChange:1->2 1455009846703.1052.4yoxhg==
,2016-02-09 10:24:12.197 ThaliTest[1582:2930534] server relay: connected (to port: 59337)
,2016-02-09 10:24:12.356 ThaliTest[1582:2931348] client session: fireConnectCallback: 1455009846703.1052.4yoxhg==
2016-02-09 10:24:12.356 ThaliTest[1582:2931348] jxcore: connect: success
ok 107 Should be able to connect without error

,ok 108 Port should be within range

,2016-02-09 10:24:12.364 ThaliTest[1582:2930534] client: relay established
2016-02-09 10:24:12.364 ThaliTest[1582:2930534] client: new accepted socket: 0x17387a70
,data in 1095

,data in 2190

,data in 3285

,data in 4380

,data in 5475

,data in 6570

,data in 7665

,data in 8760

,data in 9855

,data in 10950

,data in 12045

,data in 13140

,2016-02-09 10:24:37.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:24:40.853 ThaliTest[1582:2931347] server session: not connected 1455009846703.1052
,data in 15330

,data in 16425

,data in 17520

,data in 18615

,data in 19710

,data in 20805

,data in 21900

,data in 33945

,data in 35040

,data in 49376

,data in 66795

,data in 83220

,data in 84315

,data in 85410

,data in 86505

,data in 87600

,data in 88695

,data in 89790

,data in 90885

,data in 91980

,data in 93075

,data in 94170

,data in 95265

,data in 96289

,data in 96360

,data in 97455

,data in 98550

,data in 99645

,data in 100740

,data in 101835

,data in 102930

,data in 104025

,data in 105120

,data in 106215

,data in 107310

,data in 108405

,data in 109500

,data in 110595

,data in 111690

,data in 112785

,data in 113880

,data in 114975

,data in 116070

,data in 117165

,data in 118260

,data in 119355

,data in 120450

,data in 121545

,data in 122640

,data in 123735

,data in 124759
,
,data in 124830

,data in 125925

,data in 127020

,data in 128115

,data in 129210

,data in 130305

,data in 131072

,ok 109 the test messages should be equal

,2016-02-09 10:24:57.768 ThaliTest[1582:2930855] jxcore: disconnect
2016-02-09 10:24:57.768 ThaliTest[1582:2930855] client session: disconnectFromPeer: 1455009846703.1052.4yoxhg==
2016-02-09 10:24:57.769 ThaliTest[1582:2930855] client session: disconnect,
2016-02-09 10:24:57.769 ThaliTest[1582:2930855] client session: stateChange:2->0 1455009846703.1052.4yoxhg==
,2016-02-09 10:24:57.778 ThaliTest[1582:2930855] jxcore: disconnect: success
ok 110 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

# setup

,2016-02-09 10:25:07.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:25:07.231 ThaliTest[1582:2930534] client: found peer: 1455009846703.1052.4yoxhg==
,2016-02-09 10:25:37.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:25:37.236 ThaliTest[1582:2930534] client: found peer: 1455009846703.1052.4yoxhg==
,2016-02-09 10:26:07.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:26:07.234 ThaliTest[1582:2930534] client: found peer: 1455009846703.1052.4yoxhg==
,2016-02-09 10:26:37.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:26:37.233 ThaliTest[1582:2930534] client: found peer: 1455009846703.1052.4yoxhg==
,2016-02-09 10:27:07.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:27:07.232 ThaliTest[1582:2930534] client: found peer: 1455009846703.1052.4yoxhg==
,2016-02-09 10:27:37.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:27:37.230 ThaliTest[1582:2930534] client: found peer: 1455009846703.1052.4yoxhg==
,2016-02-09 10:28:07.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:28:07.233 ThaliTest[1582:2930534] client: found peer: 1455009846703.1052.4yoxhg==
,2016-02-09 10:28:37.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:29:07.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:29:07.231 ThaliTest[1582:2930534] client: found peer: 1455009846703.1052.4yoxhg==
,2016-02-09 10:29:37.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:29:37.233 ThaliTest[1582:2930534] client: found peer: 1455009846703.1052.4yoxhg==
,appEnteredForeground wasn't registered

,2016-02-09 10:30:07.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:30:07.232 ThaliTest[1582:2930534] client: found peer: 1455009846703.1052.4yoxhg==
,appEnteringBackground wasn't registered

,2016-02-09 10:30:37.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:30:37.233 ThaliTest[1582:2930534] client: found peer: 1455009846703.1052.4yoxhg==
,2016-02-09 10:31:07.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:31:07.232 ThaliTest[1582:2930534] client: found peer: 1455009846703.1052.4yoxhg==
,2016-02-09 10:31:37.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:32:07.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:32:07.231 ThaliTest[1582:2930534] client: found peer: 1455009846703.1052.4yoxhg==
,2016-02-09 10:32:37.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:33:07.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:33:07.231 ThaliTest[1582:2930534] client: found peer: 1455009846703.1052.4yoxhg==
,2016-02-09 10:33:37.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:33:37.234 ThaliTest[1582:2930534] client: found peer: 1455009846703.1052.4yoxhg==
,2016-02-09 10:34:07.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:34:07.234 ThaliTest[1582:2930534] client: found peer: 1455009846703.1052.4yoxhg==
,2016-02-09 10:34:37.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:34:37.233 ThaliTest[1582:2930534] client: found peer: 1455009846703.1052.4yoxhg==
,2016-02-09 10:35:07.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:35:07.231 ThaliTest[1582:2930534] client: found peer: 1455009846703.1052.4yoxhg==
,2016-02-09 10:35:37.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:35:37.233 ThaliTest[1582:2930534] client: found peer: 1455009846703.1052.4yoxhg==
,2016-02-09 10:36:07.201 ThaliTest[1582:2930534] multipeer session: restart
,2016-02-09 10:36:07.234 ThaliTest[1582:2930534] client: found peer: 1455009846703.1052.4yoxhg==
,2016-02-09 10:36:37.201 ThaliTest[1582:2930534] multipeer session: restart

```
