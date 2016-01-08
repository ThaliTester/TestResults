#### Test 549702613245198_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/549702613245198/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/DA51CB28-41DA-4692-942A-55F5213ACD86/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/DA51CB28-41DA-4692-942A-55F5213ACD86/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/549702613245198/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/549702613245198/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/85D00BE6-E293-4C1F-87C6-05533ACFD66E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51272"
,(lldb)     command script import "/tmp/DA51CB28-41DA-4692-942A-55F5213ACD86/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 21:06:51.599 ThaliTest[1583:3248298] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D1EC81A7-B116-40A4-A5D1-A1841D53FC0A/Library/Cookies/Cookies.binarycookies
,2016-01-08 21:06:52.005 ThaliTest[1583:3248298] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 21:06:52.007 ThaliTest[1583:3248298] Multi-tasking -> Device: YES, App: YES
,2016-01-08 21:06:52.015 ThaliTest[1583:3248298] Unlimited access to network resources
,2016-01-08 21:06:52.028 ThaliTest[1583:3248298] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 21:07:01.344 ThaliTest[1583:3248298] Resetting plugins due to page load.
,2016-01-08 21:07:05.366 ThaliTest[1583:3248298] Finished load of: file:///var/mobile/Containers/Bundle/Application/85D00BE6-E293-4C1F-87C6-05533ACFD66E/ThaliTest.app/www/index.html
,2016-01-08 21:07:05.588 ThaliTest[1583:3248298] JXcore Cordova plugin initializing
,2016-01-08 21:07:05.590 ThaliTest[1583:3248518] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
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
ok 13 should be equal
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
,2016-01-08 21:11:37.409 ThaliTest[1583:3248518] jxcore: startBroadcasting
,2016-01-08 21:11:37.425 ThaliTest[1583:3248518] server: starting 1452283897408.1583.FCD29A==
,2016-01-08 21:11:37.426 ThaliTest[1583:3248518] multipeer session: start timer: 0x1875ba70
,2016-01-08 21:11:37.428 ThaliTest[1583:3248518] THEMultipeerSession initialized peer 1452283897408.1583
2016-01-08 21:11:37.428 ThaliTest[1583:3248518] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2016-,01-08 21:11:37.431 ThaliTest[1583:3248518] jxcore: stopBroadcasting
2016-01-08 21:11:37.431 ThaliTest[1583:3248518] THEMultipeerSession stopping peer
2016-01-08 21:11:37.432 ThaliTest[1583:3248518] multipeer session: stop timer
,2016-01-08 21:11:37.436 ThaliTest[1583:3248518] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-08 21:11:37.439 ThaliTest[1583:3248518] jxcore: startBroadcasting
,2016-01-08 21:11:37.446 ThaliTest[1583:3248518] server: starting 1452283897438.1583.GiDXeQ==
2016-01-08 21:11:37.447 ThaliTest[1583:3248518] multipeer session: start timer: 0x187346a0
2016-01-08 21:11:37.448 ThaliTest[1583:3248518] THEMultipeerSession in,itialized peer 1452283897438.1583
2016-01-08 21:11:37.449 ThaliTest[1583:3248518] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-08 21:11:37.452 ThaliTest[1583:3248518] jxcore: stopBroadcasting
2,016-01-08 21:11:37.453 ThaliTest[1583:3248518] THEMultipeerSession stopping peer
2016-01-08 21:11:37.453 ThaliTest[1583:3248518] multipeer session: stop timer
2016-01-08 21:11:37.453 ThaliTest[1583:3248518] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
,2016-01-08 21:11:37.455 ThaliTest[1583:3248518] jxcore: startBroadcasting
,2016-01-08 21:11:37.488 ThaliTest[1583:3248518] server: starting 1452283897455.1583.F4CXvg==
,2016-01-08 21:11:37.494 ThaliTest[1583:3248518] multipeer session: start timer: 0x187335a0
,2016-01-08 21:11:37.505 ThaliTest[1583:3248518] THEMultipeerSession initialized peer 1452283897455.1583
,2016-01-08 21:11:37.509 ThaliTest[1583:3248518] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2016-01-08 21:11:37.515 ThaliTest[1583:3248518] jxcore: stopBroadcasting
,2016-01-08 21:11:37.516 ThaliTest[1583:3248518] THEMultipeerSession stopping peer
,2016-01-08 21:11:37.517 ThaliTest[1583:3248518] multipeer session: stop timer
,2016-01-08 21:11:37.522 ThaliTest[1583:3248518] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2016-01-08 21:11:37.527 ThaliTest[1583:3248518] jxcore: startBroadcasting
,2016-01-08 21:11:37.531 ThaliTest[1583:3248518] server: starting 1452283897526.1583.4yf6eg==
,2016-01-08 21:11:37.537 ThaliTest[1583:3248518] multipeer session: start timer: 0x18133bc0
,2016-01-08 21:11:37.542 ThaliTest[1583:3248518] THEMultipeerSession initialized peer 1452283897526.1583
,2016-01-08 21:11:37.544 ThaliTest[1583:3248518] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2016-01-08 21:11:37.547 ThaliTest[1583:3248518] jxcore: stopBroadcasting
,2016-01-08 21:11:37.548 ThaliTest[1583:3248518] THEMultipeerSession stopping peer
,2016-01-08 21:11:37.550 ThaliTest[1583:3248518] multipeer session: stop timer
,2016-01-08 21:11:37.556 ThaliTest[1583:3248518] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2016-01-08 21:11:37.560 ThaliTest[1583:3248518] jxcore: startBroadcasting
,2016-01-08 21:11:37.564 ThaliTest[1583:3248518] server: starting 1452283897559.1583./Y47gg==
,2016-01-08 21:11:37.568 ThaliTest[1583:3248518] multipeer session: start timer: 0x1842eac0
,2016-01-08 21:11:37.577 ThaliTest[1583:3248518] THEMultipeerSession initialized peer 1452283897559.1583
,2016-01-08 21:11:37.578 ThaliTest[1583:3248518] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2016-01-08 21:11:37.582 ThaliTest[1583:3248518] jxcore: stopBroadcasting
,2016-01-08 21:11:37.583 ThaliTest[1583:3248518] THEMultipeerSession stopping peer
,2016-01-08 21:11:37.585 ThaliTest[1583:3248518] multipeer session: stop timer
,2016-01-08 21:11:37.590 ThaliTest[1583:3248518] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-08 21:11:37.595 ThaliTest[1583:3248518] jxcore: startBroadcasting
,2016-01-08 21:11:37.600 ThaliTest[1583:3248518] server: starting 1452283897594.1583.yp/xkw==
,2016-01-08 21:11:37.603 ThaliTest[1583:3248518] multipeer session: start timer: 0x183bc260
,2016-01-08 21:11:37.611 ThaliTest[1583:3248518] THEMultipeerSession initialized peer 1452283897594.1583
,2016-01-08 21:11:37.613 ThaliTest[1583:3248518] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-08 21:11:37.615 ThaliTest[1583:3248518] jxcore: stopBroadcasting
,2016-01-08 21:11:37.616 ThaliTest[1583:3248518] THEMultipeerSession stopping peer
,2016-01-08 21:11:37.617 ThaliTest[1583:3248518] multipeer session: stop timer
,2016-01-08 21:11:37.621 ThaliTest[1583:3248518] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-08 21:11:37.624 ThaliTest[1583:3248518] jxcore: startBroadcasting
,2016-01-08 21:11:37.627 ThaliTest[1583:3248518] server: starting 1452283897623.1583.1zebHA==
,2016-01-08 21:11:37.629 ThaliTest[1583:3248518] multipeer session: start timer: 0x18737180
,2016-01-08 21:11:37.636 ThaliTest[1583:3248518] THEMultipeerSession initialized peer 1452283897623.1583
,2016-01-08 21:11:37.638 ThaliTest[1583:3248518] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-08 21:11:37.640 ThaliTest[1583:3248518] jxcore: stopBroadcasting
,2016-01-08 21:11:37.641 ThaliTest[1583:3248518] THEMultipeerSession stopping peer
,2016-01-08 21:11:37.642 ThaliTest[1583:3248518] multipeer session: stop timer
,2016-01-08 21:11:37.647 ThaliTest[1583:3248518] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-08 21:11:37.649 ThaliTest[1583:3248518] jxcore: startBroadcasting
,2016-01-08 21:11:37.653 ThaliTest[1583:3248518] server: starting 1452283897649.1583.bY9HJw==
,2016-01-08 21:11:37.655 ThaliTest[1583:3248518] multipeer session: start timer: 0x18738840
,2016-01-08 21:11:37.661 ThaliTest[1583:3248518] THEMultipeerSession initialized peer 1452283897649.1583
,2016-01-08 21:11:37.662 ThaliTest[1583:3248518] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-08 21:11:37.665 ThaliTest[1583:3248518] jxcore: stopBroadcasting
,2016-01-08 21:11:37.665 ThaliTest[1583:3248518] THEMultipeerSession stopping peer
,2016-01-08 21:11:37.667 ThaliTest[1583:3248518] multipeer session: stop timer
,2016-01-08 21:11:37.669 ThaliTest[1583:3248518] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-08 21:11:37.674 ThaliTest[1583:3248518] jxcore: startBroadcasting
,2016-01-08 21:11:37.677 ThaliTest[1583:3248518] server: starting 1452283897673.1583.C/FIyQ==
,2016-01-08 21:11:37.679 ThaliTest[1583:3248518] multipeer session: start timer: 0x183da1a0
,2016-01-08 21:11:37.685 ThaliTest[1583:3248518] THEMultipeerSession initialized peer 1452283897673.1583
,2016-01-08 21:11:37.686 ThaliTest[1583:3248518] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-08 21:11:37.689 ThaliTest[1583:3248518] jxcore: stopBroadcasting
,2016-01-08 21:11:37.689 ThaliTest[1583:3248518] THEMultipeerSession stopping peer
,2016-01-08 21:11:37.690 ThaliTest[1583:3248518] multipeer session: stop timer
,2016-01-08 21:11:37.695 ThaliTest[1583:3248518] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-08 21:11:37.698 ThaliTest[1583:3248518] jxcore: startBroadcasting
,2016-01-08 21:11:37.701 ThaliTest[1583:3248518] server: starting 1452283897697.1583.p2TnWA==
,2016-01-08 21:11:37.702 ThaliTest[1583:3248518] multipeer session: start timer: 0x18739a30
,2016-01-08 21:11:37.707 ThaliTest[1583:3248518] THEMultipeerSession initialized peer 1452283897697.1583
,2016-01-08 21:11:37.711 ThaliTest[1583:3248518] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-08 21:11:37.713 ThaliTest[1583:3248518] jxcore: stopBroadcasting
,2016-01-08 21:11:37.714 ThaliTest[1583:3248518] THEMultipeerSession stopping peer
,2016-01-08 21:11:37.714 ThaliTest[1583:3248518] multipeer session: stop timer
,2016-01-08 21:11:37.715 ThaliTest[1583:3248518] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-08 21:11:37.787 ThaliTest[1583:3248518] jxcore: startBroadcasting
,2016-01-08 21:11:37.790 ThaliTest[1583:3248518] server: starting 1452283897787.1583.gaPKgg==
,2016-01-08 21:11:37.791 ThaliTest[1583:3248518] multipeer session: start timer: 0x187342b0
,2016-01-08 21:11:37.793 ThaliTest[1583:3248518] THEMultipeerSession initialized peer 1452283897787.1583
,2016-01-08 21:11:37.795 ThaliTest[1583:3248518] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
,2016-01-08 21:11:37.800 ThaliTest[1583:3248518] jxcore: startBroadcasting
,2016-01-08 21:11:37.801 ThaliTest[1583:3248518] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
,2016-01-08 21:11:37.804 ThaliTest[1583:3248518] jxcore: stopBroadcasting
,2016-01-08 21:11:37.805 ThaliTest[1583:3248518] THEMultipeerSession stopping peer
,2016-01-08 21:11:37.806 ThaliTest[1583:3248518] multipeer session: stop timer
,2016-01-08 21:11:37.807 ThaliTest[1583:3248518] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-08 21:11:38.384 ThaliTest[1583:3248518] jxcore: startBroadcasting
,2016-01-08 21:11:38.388 ThaliTest[1583:3248518] server: starting 1452283898384.1583.lgO1Cw==
2016-01-08 21:11:38.389 ThaliTest[1583:3248518] multipeer session: start timer: 0x1873cb70
2016-01-08 21:11:38.390 ThaliTest[1583:3248518] THEMultipeerSession in,itialized peer 1452283898384.1583
2016-01-08 21:11:38.390 ThaliTest[1583:3248518] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-08 21:11:38.393 ThaliTest[1583:3248518] jxcore: connect foobar
201,6-01-08 21:11:38.394 ThaliTest[1583:3248518] client: unknown peer foobar
2016-01-08 21:11:38.394 ThaliTest[1583:3248518] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
,2016-01-08 21:11:38.397 ThaliTest[1583:3248518] jxcore: stopBroadcasting
2016-01-08 21:11:38.398 ThaliTest[1583:3248518] THEMultipeerSession stopping peer
2016-01-08 21:11:38.398 ThaliTest[1583:3248518] multipeer session: stop timer
,2016-01-08 21:11:38.402 ThaliTest[1583:3248518] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-08 21:11:43.000 ThaliTest[1583:3248518] jxcore: startBroadcasting
,2016-01-08 21:11:43.004 ThaliTest[1583:3248518] server: starting 1452283902999.1583.Yd8DRw==
2016-01-08 21:11:43.005 ThaliTest[1583:3248518] multipeer session: start timer: 0x1844a460
2016-01-08 21:11:43.005 ThaliTest[1583:3248518] THEMultipeerSession in,itialized peer 1452283902999.1583
2016-01-08 21:11:43.005 ThaliTest[1583:3248518] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-08 21:11:43.008 ThaliTest[1583:3248518] jxcore: disconnect
2016-01,-08 21:11:43.008 ThaliTest[1583:3248518] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 
2016-01-08 21:11:43.012 ThaliTest[1583:3248518] jxcore: stopBroadcasting
,2016-01-08 21:11:43.013 ThaliTest[1583:3248518] THEMultipeerSession stopping peer
,2016-01-08 21:11:43.014 ThaliTest[1583:3248518] multipeer session: stop timer
,2016-01-08 21:11:43.015 ThaliTest[1583:3248518] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-08 21:11:46.937 ThaliTest[1583:3248518] jxcore: startBroadcasting
,2016-01-08 21:11:46.941 ThaliTest[1583:3248518] server: starting 1452283906937.1583.c4YI7w==
2016-01-08 21:11:46.942 ThaliTest[1583:3248518] multipeer session: start timer: 0x187412e0
2016-01-08 21:11:46.942 ThaliTest[1583:3248518] THEMultipeerSession in,itialized peer 1452283906937.1583
2016-01-08 21:11:46.943 ThaliTest[1583:3248518] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-08 21:11:47.720 ThaliTest[1583:3248298] client: found peer: 1452283904549.1143.idzy+w==
2016-01-08 21:11:47.727 ThaliTest[1583:3248518] jxcore: connect 1452283904549.1143.idzy+w==
2016-01-08 21:11:47.728 ThaliTest[1583:3248518] client session: co,nnect
2016-01-08 21:11:47.729 ThaliTest[1583:3248518] client session: stateChange:0->1 1452283904549.1143.idzy+w==
,2016-01-08 21:11:49.669 ThaliTest[1583:3248298] multipeer session: reset timer
2016-01-08 21:11:49.670 ThaliTest[1583:3248298] multipeer session: stop timer
2016-01-08 21:11:49.670 ThaliTest[1583:3248298] multipeer session: start timer: 0x187412e0
2016-,01-08 21:11:49.670 ThaliTest[1583:3248298] server session: connect
2016-01-08 21:11:49.671 ThaliTest[1583:3248298] server session: stateChange:0->1 1452283904549.1143
,2016-01-08 21:11:49.690 ThaliTest[1583:3248298] server: accepting invitation 1452283904549.1143
,2016-01-08 21:11:51.190 ThaliTest[1583:3249050] client session: connected
2016-01-08 21:11:51.197 ThaliTest[1583:3249050] client session: stateChange:1->2 1452283904549.1143.idzy+w==
,2016-01-08 21:11:51.202 ThaliTest[1583:3249050] client session: fireConnectCallback: 1452283904549.1143.idzy+w==
2016-01-08 21:11:51.204 ThaliTest[1583:3249050] jxcore: connect: success
ok 75 Should be able to connect without error
ok 76 Port should be within range
,2016-01-08 21:11:51.209 ThaliTest[1583:3248518] jxcore: disconnect
2016-01-08 21:11:51.209 ThaliTest[1583:3248518] client session: disconnectFromPeer: 1452283904549.1143.idzy+w==
2016-01-08 21:11:51.210 ThaliTest[1583:3248518] client session: disconnect
,2016-01-08 21:11:51.210 ThaliTest[1583:3248518] client session: stateChange:2->0 1452283904549.1143.idzy+w==
,2016-01-08 21:11:51.292 ThaliTest[1583:3248518] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-08 21:11:52.826 ThaliTest[1583:3248998] server session: connected
2016-01-08 21:11:52.827 ThaliTest[1583:3248998] server session: stateChange:1->2 1452283904549.1143
,2016-01-08 21:11:52.866 ThaliTest[1583:3248298] server relay: socket disconnected
2016-01-08 21:11:52.867 ThaliTest[1583:3248298] server relay: 0x16e65a70 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-08 21:11:53.381 ThaliTest[1583:3248994] server session: not connected 1452283904549.1143
,calling stopBroadcasting
2016-01-08 21:11:53.562 ThaliTest[1583:3248518] jxcore: stopBroadcasting
2016-01-08 21:11:53.562 ThaliTest[1583:3248518] THEMultipeerSession stopping peer
2016-01-08 21:11:53.563 ThaliTest[1583:3248518] multipeer session: stop timer
2016-01-08 21:11:53.563 ThaliTest[1583:3248518] server session: disconnect
,2016-01-08 21:11:53.564 ThaliTest[1583:3248518] server session: stateChange:2->0 1452283904549.1143
,2016-01-08 21:11:53.572 ThaliTest[1583:3248518] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-08 21:11:55.134 ThaliTest[1583:3248518] jxcore: startBroadcasting
,2016-01-08 21:11:55.138 ThaliTest[1583:3248518] server: starting 1452283915133.1583.8Fd4dQ==
2016-01-08 21:11:55.139 ThaliTest[1583:3248518] multipeer session: start timer: 0x18741870
,2016-01-08 21:11:55.139 ThaliTest[1583:3248518] THEMultipeerSession initialized peer 1452283915133.1583
2016-01-08 21:11:55.142 ThaliTest[1583:3248518] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-08 21:11:55.159 ThaliTest[1583:3248298] client: found peer: 1452283904549.1143.idzy+w==
2016-01-08 21:11:55.161 ThaliTest[1583:3248518] jxcore: connect 1452283904549.1143.idzy+w==
2016-01-08 21:11:55.162 ThaliTest[1583:3248518] client session: co,nnect
2016-01-08 21:11:55.163 ThaliTest[1583:3248518] client session: stateChange:0->1 1452283904549.1143.idzy+w==
,2016-01-08 21:11:56.220 ThaliTest[1583:3248298] client: found peer: 1452283915096.1143.NiABgw==
2016-01-08 21:11:56.222 ThaliTest[1583:3248518] jxcore: connect 1452283915096.1143.NiABgw==
2016-01-08 21:11:56.223 ThaliTest[1583:3248518] client session: connect
,2016-01-08 21:11:56.224 ThaliTest[1583:3248518] client session: stateChange:0->1 1452283915096.1143.NiABgw==
,2016-01-08 21:11:56.363 ThaliTest[1583:3248298] multipeer session: reset timer
2016-01-08 21:11:56.363 ThaliTest[1583:3248298] multipeer session: stop timer
2016-01-08 21:11:56.364 ThaliTest[1583:3248298] multipeer session: start timer: 0x18741870
,2016-01-08 21:11:56.365 ThaliTest[1583:3248298] server session: connect
2016-01-08 21:11:56.366 ThaliTest[1583:3248298] server session: stateChange:0->1 1452283915096.1143
2016-01-08 21:11:56.375 ThaliTest[1583:3248298] server: accepting invitation 1452283915096.1143
,2016-01-08 21:11:59.115 ThaliTest[1583:3249050] server session: connected
2016-01-08 21:11:59.116 ThaliTest[1583:3249050] server session: stateChange:1->2 1452283915096.1143
,2016-01-08 21:11:59.729 ThaliTest[1583:3249000] server session: not connected 1452283915096.1143
2016-01-08 21:11:59.729 ThaliTest[1583:3248298] server relay: socket disconnected
2016-01-08 21:11:59.729 ThaliTest[1583:3248298] server relay: 0x1874d7b0 di,sconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-08 21:11:59.932 ThaliTest[1583:3248994] client session: connected
2016-01-08 21:11:59.932 ThaliTest[1583:3248994] client session: stateChange:1->2 1452283915096.1143.NiABgw==
,2016-01-08 21:11:59.986 ThaliTest[1583:3249000] client session: fireConnectCallback: 1452283915096.1143.NiABgw==
2016-01-08 21:11:59.987 ThaliTest[1583:3249000] jxcore: connect: success
,ok 79 Should be able to connect without error
,ok 80 Port should be within range
,2016-01-08 21:11:59.992 ThaliTest[1583:3248518] jxcore: connect 1452283915096.1143.NiABgw==
2016-01-08 21:11:59.992 ThaliTest[1583:3248518] client: already connect(ing/ed) to 1452283915096.1143.NiABgw==
2016-01-08 21:11:59.993 ThaliTest[1583:3248518] jxc,ore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect
,2016-01-08 21:11:59.996 ThaliTest[1583:3248518] jxcore: disconnect
,2016-01-08 21:11:59.997 ThaliTest[1583:3248518] client session: disconnectFromPeer: 1452283915096.1143.NiABgw==
,2016-01-08 21:11:59.998 ThaliTest[1583:3248518] client session: disconnect
,2016-01-08 21:11:59.998 ThaliTest[1583:3248518] client session: stateChange:2->0 1452283915096.1143.NiABgw==
,2016-01-08 21:12:00.031 ThaliTest[1583:3248518] jxcore: disconnect: success
,ok 82 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,2016-01-08 21:12:00.303 ThaliTest[1583:3248298] client: lost peer: 1452283904549.1143.idzy+w==
2016-01-08 21:12:00.303 ThaliTest[1583:3248298] client session: onPeerLost: 1452283904549.1143.idzy+w==
2016-01-08 21:12:00.303 ThaliTest[1583:3248298] client ,session: onLinkFailure: 1452283904549.1143.idzy+w==
2016-01-08 21:12:00.303 ThaliTest[1583:3248298] client session: disconnect
2016-01-08 21:12:00.304 ThaliTest[1583:3248298] client session: stateChange:1->0 1452283904549.1143.idzy+w==
2016-01-08 21:12:,00.304 ThaliTest[1583:3248298] client session: fireConnectCallback: 1452283904549.1143.idzy+w==
2016-01-08 21:12:00.305 ThaliTest[1583:3248298] jxcore: connect: fail: Peer disconnected
,calling stopBroadcasting
,2016-01-08 21:12:00.810 ThaliTest[1583:3248518] jxcore: stopBroadcasting
2016-01-08 21:12:00.811 ThaliTest[1583:3248518] THEMultipeerSession stopping peer
2016-01-08 21:12:00.811 ThaliTest[1583:3248518] multipeer session: stop timer
2016-01-08 21:12:00.,812 ThaliTest[1583:3248518] server session: disconnect
2016-01-08 21:12:00.812 ThaliTest[1583:3248518] server session: stateChange:2->0 1452283915096.1143
2016-01-08 21:12:00.813 ThaliTest[1583:3248518] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-08 21:12:01.712 ThaliTest[1583:3248518] jxcore: startBroadcasting
,2016-01-08 21:12:01.717 ThaliTest[1583:3248518] server: starting 1452283921712.1583.tyrCBw==
2016-01-08 21:12:01.718 ThaliTest[1583:3248518] multipeer session: start timer: 0x16ddf780
2016-01-08 21:12:01.718 ThaliTest[1583:3248518] THEMultipeerSession in,itialized peer 1452283921712.1583
2016-01-08 21:12:01.719 ThaliTest[1583:3248518] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-08 21:12:03.067 ThaliTest[1583:3248298] client: found peer: 1452283921683.1143.ytsBKQ==
,2016-01-08 21:12:03.070 ThaliTest[1583:3248518] jxcore: connect 1452283921683.1143.ytsBKQ==
2016-01-08 21:12:03.070 ThaliTest[1583:3248518] client session: connect
2016-01-08 21:12:03.071 ThaliTest[1583:3248518] client session: stateChange:0->1 1452283921683.1143.ytsBKQ==
,2016-01-08 21:12:03.308 ThaliTest[1583:3248298] multipeer session: reset timer
2016-01-08 21:12:03.309 ThaliTest[1583:3248298] multipeer session: stop timer
2016-01-08 21:12:03.310 ThaliTest[1583:3248298] multipeer session: start timer: 0x16ddf780
2016-,01-08 21:12:03.310 ThaliTest[1583:3248298] server session: connect
2016-01-08 21:12:03.310 ThaliTest[1583:3248298] server session: stateChange:0->1 1452283921683.1143
,2016-01-08 21:12:03.322 ThaliTest[1583:3248298] server: accepting invitation 1452283921683.1143
,2016-01-08 21:12:05.802 ThaliTest[1583:3249069] client session: connected
2016-01-08 21:12:05.803 ThaliTest[1583:3249069] client session: stateChange:1->2 1452283921683.1143.ytsBKQ==
,2016-01-08 21:12:05.854 ThaliTest[1583:3249070] client session: fireConnectCallback: 1452283921683.1143.ytsBKQ==
2016-01-08 21:12:05.855 ThaliTest[1583:3249070] jxcore: connect: success
ok 84 Should be able to connect without error
,ok 85 Port should be within range
,2016-01-08 21:12:05.865 ThaliTest[1583:3248518] jxcore: disconnect
2016-01-08 21:12:05.872 ThaliTest[1583:3248518] client session: disconnectFromPeer: 1452283921683.1143.ytsBKQ==
2016-01-08 21:12:05.872 ThaliTest[1583:3248518] client session: disconnect,
2016-01-08 21:12:05.872 ThaliTest[1583:3248518] client session: stateChange:2->0 1452283921683.1143.ytsBKQ==
,2016-01-08 21:12:05.897 ThaliTest[1583:3248518] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
2016-01-08 21:12:05.900 ThaliTest[1583:3248518] jxcore: disconnect
2016-01-08 21:12:05.900 ThaliTest[1583:3248518] jxcore: disco,nnect: fail
ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-08 21:12:05.957 ThaliTest[1583:3248994] server session: connected
,2016-01-08 21:12:05.958 ThaliTest[1583:3248994] server session: stateChange:1->2 1452283921683.1143
,2016-01-08 21:12:05.963 ThaliTest[1583:3248298] server relay: socket disconnected
,2016-01-08 21:12:05.963 ThaliTest[1583:3248298] server relay: 0x16e07750 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection ,refused} 
,2016-01-08 21:12:06.052 ThaliTest[1583:3248998] server session: not connected 1452283921683.1143
,calling stopBroadcasting
,2016-01-08 21:12:06.122 ThaliTest[1583:3248518] jxcore: stopBroadcasting
2016-01-08 21:12:06.122 ThaliTest[1583:3248518] THEMultipeerSession stopping peer
2016-01-08 21:12:06.123 ThaliTest[1583:3248518] multipeer session: stop timer
2016-01-08 21:12:06.,123 ThaliTest[1583:3248518] server session: disconnect
2016-01-08 21:12:06.123 ThaliTest[1583:3248518] server session: stateChange:2->0 1452283921683.1143
2016-01-08 21:12:06.125 ThaliTest[1583:3248518] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,2016-01-08 21:12:07.188 ThaliTest[1583:3248518] jxcore: startBroadcasting
,2016-01-08 21:12:07.194 ThaliTest[1583:3248518] server: starting 1452283927186.1583.wH5YQA==
2016-01-08 21:12:07.195 ThaliTest[1583:3248518] multipeer session: start timer: 0x1874e5f0
2016-01-08 21:12:07.195 ThaliTest[1583:3248518] THEMultipeerSession in,itialized peer 1452283927186.1583
2016-01-08 21:12:07.196 ThaliTest[1583:3248518] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
echo server started
,2016-01-08 21:12:07.277 ThaliTest[1583:3248298] client: found peer: 1452283921683.1143.ytsBKQ==
[{"peerIdentifier":"1452283921683.1143.ytsBKQ==","peerName":"(null)","peerAvailable":true}]
,2016-01-08 21:12:07.282 ThaliTest[1583:3248518] jxcore: connect 1452283921683.1143.ytsBKQ==
2016-01-08 21:12:07.283 ThaliTest[1583:3248518] client session: connect
2016-01-08 21:12:07.283 ThaliTest[1583:3248518] client session: stateChange:0->1 1452283921683.1143.ytsBKQ==
,2016-01-08 21:12:08.352 ThaliTest[1583:3248298] client: found peer: 1452283927168.1143.u1xFpA==
[{"peerIdentifier":"1452283927168.1143.u1xFpA==","peerName":"(null)","peerAvailable":true}]
2016-01-08 21:12:08.355 ThaliTest[1583:3248518] jxcore: connect 1452283927168.1143.u1xFpA==
,2016-01-08 21:12:08.355 ThaliTest[1583:3248518] client session: connect
2016-01-08 21:12:08.356 ThaliTest[1583:3248518] client session: stateChange:0->1 1452283927168.1143.u1xFpA==
,2016-01-08 21:12:08.540 ThaliTest[1583:3248298] multipeer session: reset timer
2016-01-08 21:12:08.541 ThaliTest[1583:3248298] multipeer session: stop timer
2016-01-08 21:12:08.541 ThaliTest[1583:3248298] multipeer session: start timer: 0x1874e5f0
2016-,01-08 21:12:08.541 ThaliTest[1583:3248298] server session: connect
2016-01-08 21:12:08.542 ThaliTest[1583:3248298] server session: stateChange:0->1 1452283927168.1143
,2016-01-08 21:12:08.554 ThaliTest[1583:3248298] server: accepting invitation 1452283927168.1143
,2016-01-08 21:12:09.353 ThaliTest[1583:3248298] client: lost peer: 1452283921683.1143.ytsBKQ==
2016-01-08 21:12:09.353 ThaliTest[1583:3248298] client session: onPeerLost: 1452283921683.1143.ytsBKQ==
2016-01-08 21:12:09.353 ThaliTest[1583:3248298] client ,session: onLinkFailure: 1452283921683.1143.ytsBKQ==
2016-01-08 21:12:09.354 ThaliTest[1583:3248298] client session: disconnect
2016-01-08 21:12:09.354 ThaliTest[1583:3248298] client session: stateChange:1->0 1452283921683.1143.ytsBKQ==
2016-01-08 21:12:,09.355 ThaliTest[1583:3248298] client session: fireConnectCallback: 1452283921683.1143.ytsBKQ==
2016-01-08 21:12:09.355 ThaliTest[1583:3248298] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1452283921683.1143.ytsBKQ==","peerName":"(null)",,"peerAvailable":false}]
,2016-01-08 21:12:10.361 ThaliTest[1583:3248518] jxcore: connect 1452283921683.1143.ytsBKQ==
2016-01-08 21:12:10.362 ThaliTest[1583:3248518] client: connect: unreachable 1452283921683.1143.ytsBKQ==
2016-01-08 21:12:10.362 ThaliTest[1583:3248518] jxcore: c,onnect: fail: Peer unreachable
,2016-01-08 21:12:11.097 ThaliTest[1583:3249069] client session: connected
2016-01-08 21:12:11.098 ThaliTest[1583:3249069] client session: stateChange:1->2 1452283927168.1143.u1xFpA==
,2016-01-08 21:12:11.186 ThaliTest[1583:3249069] client session: fireConnectCallback: 1452283927168.1143.u1xFpA==
2016-01-08 21:12:11.186 ThaliTest[1583:3249069] jxcore: connect: success
,ok 89 Should be able to connect without error
,ok 90 Port should be within range
,ok 91 First connect should succeed
,2016-01-08 21:12:11.237 ThaliTest[1583:3249069] server session: connected
,2016-01-08 21:12:11.238 ThaliTest[1583:3249069] server session: stateChange:1->2 1452283927168.1143
,2016-01-08 21:12:11.263 ThaliTest[1583:3248298] server relay: connected (to port: 5001)
,2016-01-08 21:12:11.273 ThaliTest[1583:3248298] client: relay established
2016-01-08 21:12:11.273 ThaliTest[1583:3248298] client: new accepted socket: 0x187232c0
,ok 92 the test messages should be equal
ok 93 First send should succeed
,2016-01-08 21:12:11.436 ThaliTest[1583:3248994] server session: not connected 1452283927168.1143
,2016-01-08 21:12:11.447 ThaliTest[1583:3248298] client: socket closed
,2016-01-08 21:12:11.448 ThaliTest[1583:3248298] client relay: socket disconnected
2016-01-08 21:12:11.448 ThaliTest[1583:3248298] client relay: 0x187232c0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer", UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-01-08 21:12:11.449 ThaliTest[1583:3248298] client session: socket closed: 1452283927168.1143.u1xFpA==
2016-01-08 21:12:11.449 ThaliTest[1583:3248298] client session: onLinkFailure: 1452283927168.1143.u1xFpA==
2016-01-08 21:12:11.449 ThaliTest[1583:3,248298] client session: disconnect
2016-01-08 21:12:11.450 ThaliTest[1583:3248298] client session: stateChange:2->0 1452283927168.1143.u1xFpA==
,2016-01-08 21:12:11.464 ThaliTest[1583:3248298] client session: fireConnectionErrorEvent: 1452283927168.1143.u1xFpA==
,2016-01-08 21:12:11.469 ThaliTest[1583:3248518] jxcore: connect 1452283927168.1143.u1xFpA==
,2016-01-08 21:12:11.470 ThaliTest[1583:3248518] client session: connect
,2016-01-08 21:12:11.488 ThaliTest[1583:3248518] client session: stateChange:0->1 1452283927168.1143.u1xFpA==
,2016-01-08 21:12:11.569 ThaliTest[1583:3248298] multipeer session: reset timer
,2016-01-08 21:12:11.569 ThaliTest[1583:3248298] multipeer session: stop timer
,2016-01-08 21:12:11.570 ThaliTest[1583:3248298] multipeer session: start timer: 0x1874e5f0
,2016-01-08 21:12:11.570 ThaliTest[1583:3248298] server: disconnecting to refresh session (1452283927168.1143)
,2016-01-08 21:12:11.571 ThaliTest[1583:3248298] server session: disconnect
,2016-01-08 21:12:11.571 ThaliTest[1583:3248298] server session: stateChange:2->0 1452283927168.1143
,2016-01-08 21:12:11.639 ThaliTest[1583:3248298] server session: connect
,2016-01-08 21:12:11.639 ThaliTest[1583:3248298] server session: stateChange:0->1 1452283927168.1143
,2016-01-08 21:12:11.648 ThaliTest[1583:3248298] server: accepting invitation 1452283927168.1143
,2016-01-08 21:12:14.243 ThaliTest[1583:3248994] client session: connected
,2016-01-08 21:12:14.244 ThaliTest[1583:3248994] client session: stateChange:1->2 1452283927168.1143.u1xFpA==
,2016-01-08 21:12:14.283 ThaliTest[1583:3249069] client session: fireConnectCallback: 1452283927168.1143.u1xFpA==
2016-01-08 21:12:14.283 ThaliTest[1583:3249069] jxcore: connect: success
ok 94 Should be able to connect without error
,ok 95 Port should be within range
,ok 96 Second connect should succeed
,2016-01-08 21:12:14.324 ThaliTest[1583:3248998] server session: connected
,2016-01-08 21:12:14.323 ThaliTest[1583:3248298] client: relay established
2016-01-08 21:12:14.326 ThaliTest[1583:3248298] client: new accepted socket: 0x1874f4c0
2016-01-08 21:12:14.325 ThaliTest[1583:3248998] server session: stateChange:1->2 1452283927168.1143
,2016-01-08 21:12:14.385 ThaliTest[1583:3248298] server relay: connected (to port: 5001)
,ok 97 the test messages should be equal
,ok 98 Second send should succeed
,# setup
,2016-01-08 21:12:14.417 ThaliTest[1583:3248298] client: socket closed
2016-01-08 21:12:14.418 ThaliTest[1583:3248298] client relay: socket disconnected
2016-01-08 21:12:14.418 ThaliTest[1583:3248298] client relay: 0x1874f4c0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-08 21:12:14.418 ThaliTest[1583:3248298] client session: socket closed: 1452283927168.1143.u1xFpA==
2016-01-08 ,21:12:14.419 ThaliTest[1583:3248298] client session: onLinkFailure: 1452283927168.1143.u1xFpA==
2016-01-08 21:12:14.419 ThaliTest[1583:3248298] client session: disconnect
2016-01-08 21:12:14.419 ThaliTest[1583:3248298] client session: stateChange:2->0 14,52283927168.1143.u1xFpA==
,2016-01-08 21:12:14.434 ThaliTest[1583:3248298] client session: fireConnectionErrorEvent: 1452283927168.1143.u1xFpA==
,2016-01-08 21:12:14.575 ThaliTest[1583:3248994] server session: not connected 1452283927168.1143
,calling stopBroadcasting
,2016-01-08 21:12:15.036 ThaliTest[1583:3248518] jxcore: stopBroadcasting
2016-01-08 21:12:15.037 ThaliTest[1583:3248518] THEMultipeerSession stopping peer
2016-01-08 21:12:15.037 ThaliTest[1583:3248518] multipeer session: stop timer
2016-01-08 21:12:15.,038 ThaliTest[1583:3248518] server session: disconnect
2016-01-08 21:12:15.038 ThaliTest[1583:3248518] server session: stateChange:2->0 1452283927168.1143
,2016-01-08 21:12:15.048 ThaliTest[1583:3248518] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/D1EC81A7-B116-40A4-A5D1-A1841D53FC0A/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,",failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 99 starting event should occur in right order
,2016-01-08 21:12:16.676 ThaliTest[1583:3248518] jxcore: startBroadcasting
,2016-01-08 21:12:16.677 ThaliTest[1583:3248518] server: starting 9U3fzfiEvIMbWI4VeorgMQ.nWIRAA==
2016-01-08 21:12:16.678 ThaliTest[1583:3248518] multipeer session: start timer: 0x1a126bd0
2016-01-08 21:12:16.678 ThaliTest[1583:3248518] THEMultipeerSession initialized peer 9U3fzfiEvIMbWI4VeorgMQ
2016-01-08 21:12:16.678 ThaliTest[1583:3248518] jxcore: startBroadcasting: success
ok 100 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
ok 101 stopping event should o,ccur in right order
About to call stopBroadcasting
2016-01-08 21:12:16.680 ThaliTest[1583:3248518] jxcore: stopBroadcasting
2016-01-08 21:12:16.680 ThaliTest[1583:3248518] THEMultipeerSession stopping peer
2016-01-08 21:12:16.680 ThaliTest[1583:3248518] multipeer session: stop timer
2016-01-08 21:12:16.681 ThaliTest[1583:3248518] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
,ok 102 stopped event should occur in right order
,mux server bridge listener closed
# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/D1EC81A7-B116-40A4-A5D1-A1841D53FC0A/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-08 21:12:17.103 ThaliTest[1583:3248518] jxcore: startBroadcasting
,2016-01-08 21:12:17.107 ThaliTest[1583:3248518] server: starting 9U3fzfiEvIMbWI4VeorgMQ.ZBdHfA==
2016-01-08 21:12:17.108 ThaliTest[1583:3248518] multipeer session: start timer: 0x1845f800
2016-01-08 21:12:17.108 ThaliTest[1583:3248518] THEMultipeerSession initialized peer 9U3fzfiEvIMbWI4VeorgMQ
2016-01-08 21:12:17.109 ThaliTest[1583:3248518] jxcore: startBroadcasting: success
ok 103 getDeviceIdentity should not return an error
ok 104 deviceName should not be null
Now in TRM stop
State of this._isStar,ted: true
About to call stopBroadcasting
2016-01-08 21:12:17.112 ThaliTest[1583:3248518] jxcore: stopBroadcasting
,2016-01-08 21:12:17.112 ThaliTest[1583:3248518] THEMultipeerSession stopping peer
2016-01-08 21:12:17.112 ThaliTest[1583:3248518] multipeer session: stop timer
2016-01-08 21:12:17.113 ThaliTest[1583:3248518] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
,mux server bridge listener closed
Tests Complete
,Total: 0	Passed: 0	Failed: 0
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
