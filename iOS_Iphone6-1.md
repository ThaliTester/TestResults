#### Test 50650278d0426ce_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278d0426ce/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/B25173E3-2E5A-44E3-8A12-94BBF7E98AEE/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/B25173E3-2E5A-44E3-8A12-94BBF7E98AEE/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278d0426ce/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278d0426ce/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/212E7018-35F0-4348-B7BB-ECC8CC181105/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52438"
,(lldb)     command script import "/tmp/B25173E3-2E5A-44E3-8A12-94BBF7E98AEE/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-09 18:11:07.670 ThaliTest[606:450721] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D64E9E7A-E293-4DB8-986D-896A3089D9A4/Library/Cookies/Cookies.binarycookies
,2015-12-09 18:11:08.081 ThaliTest[606:450721] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-09 18:11:08.082 ThaliTest[606:450721] Multi-tasking -> Device: YES, App: YES
,2015-12-09 18:11:08.091 ThaliTest[606:450721] Unlimited access to network resources
,2015-12-09 18:11:08.102 ThaliTest[606:450721] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-09 18:11:17.077 ThaliTest[606:450721] Resetting plugins due to page load.
,2015-12-09 18:11:20.379 ThaliTest[606:450721] Finished load of: file:///var/mobile/Containers/Bundle/Application/212E7018-35F0-4348-B7BB-ECC8CC181105/ThaliTest.app/www/index.html
,2015-12-09 18:11:20.560 ThaliTest[606:450721] JXcore Cordova plugin initializing
,2015-12-09 18:11:20.561 ThaliTest[606:450944] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
,2015-12-09 18:18:05.589 ThaliTest[606:450944] jxcore: startBroadcasting
,2015-12-09 18:18:05.603 ThaliTest[606:450944] server: starting 1449681485588.606.qMeV8g==
,2015-12-09 18:18:05.605 ThaliTest[606:450944] multipeer session: start timer: 0x18742940
,2015-12-09 18:18:05.606 ThaliTest[606:450944] THEMultipeerSession initialized peer 1449681485588.606
2015-12-09 18:18:05.607 ThaliTest[606:450944] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
,2015-12-09 18:18:05.610 ThaliTest[606:450944] jxcore: stopBroadcasting
2015-12-09 18:18:05.610 ThaliTest[606:450944] THEMultipeerSession stopping peer
2015-12-09 18:18:05.610 ThaliTest[606:450944] multipeer session: stop timer
2015-12-09 18:18:05.611 Th,aliTest[606:450944] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2015-12-09 18:18:05.613 ThaliTest[606:450944] jxcore: startBroadcasting
,2015-12-09 18:18:05.618 ThaliTest[606:450944] server: starting 1449681485613.606.3PEl2A==
2015-12-09 18:18:05.619 ThaliTest[606:450944] multipeer session: start timer: 0x187404b0
2015-12-09 18:18:05.619 ThaliTest[606:450944] THEMultipeerSession initialized peer 1449681485613.606
2015-12-09 18:18:05.620 ThaliTest[606:450944] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
,2015-12-09 18:18:05.631 ThaliTest[606:450944] jxcore: stopBroadcasting
2015-12-09 18:18:05.632 ThaliTest[606:450944] THEMultipeerSession stopping peer
2015-12-09 18:18:05.632 ThaliTest[606:450944] multipeer session: stop timer
2015-12-09 18:18:05.632 ThaliTest[606:450944] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
,2015-12-09 18:18:05.635 ThaliTest[606:450944] jxcore: startBroadcasting
,2015-12-09 18:18:05.645 ThaliTest[606:450944] server: starting 1449681485635.606.Q1RnHQ==
2015-12-09 18:18:05.646 ThaliTest[606:450944] multipeer session: start timer: 0x1a18b9b0
2015-12-09 18:18:05.646 ThaliTest[606:450944] THEMultipeerSession initialized peer 1449681485635.606
2015-12-09 18:18:05.647 ThaliTest[606:450944] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2015-12-09 18:18:05.650 ThaliTest[606:450944] jxcore: stopBroadcasting
2015-12-09 18:18:05.651 ThaliTest[606:450944] THEMultipeerSession stopping peer
2015-12-09 18:18:05.651 ThaliTest[606:450944] multipeer session: stop timer
2015-12-09 18:18:05.652 Th,aliTest[606:450944] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error
2015-12-09 18:18:05.653 ThaliTest[606:450944] jxcore: startBroadcasting
2015-12-09 18:18:05.658 ThaliTest[606:450944] server: starting 1449,681485653.606.hpejVw==
,2015-12-09 18:18:05.663 ThaliTest[606:450944] multipeer session: start timer: 0x1873db20
2015-12-09 18:18:05.663 ThaliTest[606:450944] THEMultipeerSession initialized peer 1449681485653.606
2015-12-09 18:18:05.663 ThaliTest[606:450944] jxcore: startBroad,casting: success
ok 51 Should be able to call startBroadcasting without error
2015-12-09 18:18:05.666 ThaliTest[606:450944] jxcore: stopBroadcasting
2015-12-09 18:18:05.666 ThaliTest[606:450944] THEMultipeerSession stopping peer
,2015-12-09 18:18:05.667 ThaliTest[606:450944] multipeer session: stop timer
,2015-12-09 18:18:05.674 ThaliTest[606:450944] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
,2015-12-09 18:18:05.682 ThaliTest[606:450944] jxcore: startBroadcasting
,2015-12-09 18:18:05.689 ThaliTest[606:450944] server: starting 1449681485681.606.zCgGVw==
2015-12-09 18:18:05.690 ThaliTest[606:450944] multipeer session: start timer: 0x1873d510
2015-12-09 18:18:05.690 ThaliTest[606:450944] THEMultipeerSession initializ,ed peer 1449681485681.606
2015-12-09 18:18:05.690 ThaliTest[606:450944] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
,2015-12-09 18:18:05.692 ThaliTest[606:450944] jxcore: stopBroadcasting
,2015-12-09 18:18:05.697 ThaliTest[606:450944] THEMultipeerSession stopping peer
,2015-12-09 18:18:05.698 ThaliTest[606:450944] multipeer session: stop timer
,2015-12-09 18:18:05.704 ThaliTest[606:450944] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2015-12-09 18:18:05.708 ThaliTest[606:450944] jxcore: startBroadcasting
,2015-12-09 18:18:05.711 ThaliTest[606:450944] server: starting 1449681485707.606.Jsmr0A==
,2015-12-09 18:18:05.713 ThaliTest[606:450944] multipeer session: start timer: 0x1873f8f0
,2015-12-09 18:18:05.718 ThaliTest[606:450944] THEMultipeerSession initialized peer 1449681485707.606
,2015-12-09 18:18:05.719 ThaliTest[606:450944] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2015-12-09 18:18:05.722 ThaliTest[606:450944] jxcore: stopBroadcasting
,2015-12-09 18:18:05.722 ThaliTest[606:450944] THEMultipeerSession stopping peer
,2015-12-09 18:18:05.723 ThaliTest[606:450944] multipeer session: stop timer
,2015-12-09 18:18:05.725 ThaliTest[606:450944] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2015-12-09 18:18:05.730 ThaliTest[606:450944] jxcore: startBroadcasting
,2015-12-09 18:18:05.732 ThaliTest[606:450944] server: starting 1449681485729.606.kduzPQ==
,2015-12-09 18:18:05.736 ThaliTest[606:450944] multipeer session: start timer: 0x18741ef0
,2015-12-09 18:18:05.737 ThaliTest[606:450944] THEMultipeerSession initialized peer 1449681485729.606
,2015-12-09 18:18:05.739 ThaliTest[606:450944] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2015-12-09 18:18:05.743 ThaliTest[606:450944] jxcore: stopBroadcasting
,2015-12-09 18:18:05.744 ThaliTest[606:450944] THEMultipeerSession stopping peer
,2015-12-09 18:18:05.745 ThaliTest[606:450944] multipeer session: stop timer
,2015-12-09 18:18:05.746 ThaliTest[606:450944] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2015-12-09 18:18:05.752 ThaliTest[606:450944] jxcore: startBroadcasting
,2015-12-09 18:18:05.754 ThaliTest[606:450944] server: starting 1449681485751.606.ERGAOQ==
,2015-12-09 18:18:05.756 ThaliTest[606:450944] multipeer session: start timer: 0x1873c650
,2015-12-09 18:18:05.758 ThaliTest[606:450944] THEMultipeerSession initialized peer 1449681485751.606
,2015-12-09 18:18:05.759 ThaliTest[606:450944] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2015-12-09 18:18:05.764 ThaliTest[606:450944] jxcore: stopBroadcasting
,2015-12-09 18:18:05.764 ThaliTest[606:450944] THEMultipeerSession stopping peer
,2015-12-09 18:18:05.765 ThaliTest[606:450944] multipeer session: stop timer
,2015-12-09 18:18:05.767 ThaliTest[606:450944] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2015-12-09 18:18:05.774 ThaliTest[606:450944] jxcore: startBroadcasting
,2015-12-09 18:18:05.776 ThaliTest[606:450944] server: starting 1449681485773.606.w1o9Sg==
,2015-12-09 18:18:05.778 ThaliTest[606:450944] multipeer session: start timer: 0x1a18ae00
,2015-12-09 18:18:05.780 ThaliTest[606:450944] THEMultipeerSession initialized peer 1449681485773.606
,2015-12-09 18:18:05.781 ThaliTest[606:450944] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2015-12-09 18:18:05.787 ThaliTest[606:450944] jxcore: stopBroadcasting
,2015-12-09 18:18:05.788 ThaliTest[606:450944] THEMultipeerSession stopping peer
,2015-12-09 18:18:05.789 ThaliTest[606:450944] multipeer session: stop timer
,2015-12-09 18:18:05.792 ThaliTest[606:450944] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2015-12-09 18:18:05.795 ThaliTest[606:450944] jxcore: startBroadcasting
,2015-12-09 18:18:05.797 ThaliTest[606:450944] server: starting 1449681485794.606.tohKtQ==
,2015-12-09 18:18:05.799 ThaliTest[606:450944] multipeer session: start timer: 0x1873cde0
,2015-12-09 18:18:05.800 ThaliTest[606:450944] THEMultipeerSession initialized peer 1449681485794.606
,2015-12-09 18:18:05.802 ThaliTest[606:450944] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2015-12-09 18:18:05.805 ThaliTest[606:450944] jxcore: stopBroadcasting
,2015-12-09 18:18:05.805 ThaliTest[606:450944] THEMultipeerSession stopping peer
,2015-12-09 18:18:05.806 ThaliTest[606:450944] multipeer session: stop timer
,2015-12-09 18:18:05.809 ThaliTest[606:450944] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2015-12-09 18:18:06.134 ThaliTest[606:450944] jxcore: startBroadcasting
,2015-12-09 18:18:06.138 ThaliTest[606:450944] server: starting 1449681486134.606.fR7CzA==
2015-12-09 18:18:06.138 ThaliTest[606:450944] multipeer session: start timer: 0x187393b0
2015-12-09 18:18:06.139 ThaliTest[606:450944] THEMultipeerSession initializ,ed peer 1449681486134.606
2015-12-09 18:18:06.139 ThaliTest[606:450944] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2015-12-09 18:18:06.141 ThaliTest[606:450944] jxcore: startBroadcasting
2015-12-09 1,8:18:06.142 ThaliTest[606:450944] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
,2015-12-09 18:18:06.144 ThaliTest[606:450944] jxcore: stopBroadcasting
2015-12-09 18:18:06.144 ThaliTest[606:450944] THEMultipeerSession stopping peer
2015-12-09 18:18:06.145 ThaliTest[606:450944] multipeer session: stop timer
,2015-12-09 18:18:06.146 ThaliTest[606:450944] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2015-12-09 18:18:06.610 ThaliTest[606:450944] jxcore: startBroadcasting
,2015-12-09 18:18:06.613 ThaliTest[606:450944] server: starting 1449681486609.606.y/HqTA==
2015-12-09 18:18:06.614 ThaliTest[606:450944] multipeer session: start timer: 0x18738dd0
2015-12-09 18:18:06.614 ThaliTest[606:450944] THEMultipeerSession initializ,ed peer 1449681486609.606
2015-12-09 18:18:06.614 ThaliTest[606:450944] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2015-12-09 18:18:06.617 ThaliTest[606:450944] jxcore: connect foobar
2015-12-09 18:1,8:06.618 ThaliTest[606:450944] client: unknown peer foobar
2015-12-09 18:18:06.618 ThaliTest[606:450944] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
,2015-12-09 18:18:06.621 ThaliTest[606:450944] jxcore: stopBroadcasting
2015-12-09 18:18:06.622 ThaliTest[606:450944] THEMultipeerSession stopping peer
2015-12-09 18:18:06.622 ThaliTest[606:450944] multipeer session: stop timer
2015-12-09 18:18:06.623 ThaliTest[606:450944] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2015-12-09 18:18:08.003 ThaliTest[606:450944] jxcore: startBroadcasting
,2015-12-09 18:18:08.007 ThaliTest[606:450944] server: starting 1449681488002.606.0bj1HA==
2015-12-09 18:18:08.008 ThaliTest[606:450944] multipeer session: start timer: 0x18735210
2015-12-09 18:18:08.008 ThaliTest[606:450944] THEMultipeerSession initializ,ed peer 1449681488002.606
2015-12-09 18:18:08.009 ThaliTest[606:450944] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2015-12-09 18:18:08.011 ThaliTest[606:450944] jxcore: disconnect
2015-12-09 18:18:08,.012 ThaliTest[606:450944] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
2015-12-09 18:18:08.014 ThaliTest[606:450944] jxcore: stopBroadcasting
2015-12-09 18:18:08.014 ThaliTest[606:450944] THEMultipeerSession stopping pe,er
2015-12-09 18:18:08.014 ThaliTest[606:450944] multipeer session: stop timer
2015-12-09 18:18:08.015 ThaliTest[606:450944] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2015-12-09 18:18:08.544 ThaliTest[606:450944] jxcore: startBroadcasting
,2015-12-09 18:18:08.547 ThaliTest[606:450944] server: starting 1449681488543.606.lSOQGw==
2015-12-09 18:18:08.548 ThaliTest[606:450944] multipeer session: start timer: 0x18731870
2015-12-09 18:18:08.548 ThaliTest[606:450944] THEMultipeerSession initialized peer 1449681488543.606
2015-12-09 18:18:08.548 ThaliTest[606:450944] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2015-12-09 18:18:09.789 ThaliTest[606:450721] client: found peer: 1449681488543.531.rFYftA==
2015-12-09 18:18:09.792 ThaliTest[606:450944] jxcore: connect 1449681488543.531.rFYftA==
2015-12-09 18:18:09.792 ThaliTest[606:450944] client session: connect
2015-12-09 18:18:09.793 ThaliTest[606:450944] client session: stateChange:0->1 1449681488543.531.rFYftA==
,2015-12-09 18:18:10.064 ThaliTest[606:450721] multipeer session: reset timer
2015-12-09 18:18:10.064 ThaliTest[606:450721] multipeer session: stop timer
2015-12-09 18:18:10.064 ThaliTest[606:450721] multipeer session: start timer: 0x18731870
2015-12-09 ,18:18:10.065 ThaliTest[606:450721] server session: connect
2015-12-09 18:18:10.065 ThaliTest[606:450721] server session: stateChange:0->1 1449681488543.531
,2015-12-09 18:18:10.073 ThaliTest[606:450721] server: accepting invitation 1449681488543.531
,2015-12-09 18:18:12.642 ThaliTest[606:451619] client session: connected
2015-12-09 18:18:12.642 ThaliTest[606:451619] client session: stateChange:1->2 1449681488543.531.rFYftA==
2015-12-09 18:18:12.647 ThaliTest[606:451619] client session: fireConnectCal,lback: 1449681488543.531.rFYftA==
2015-12-09 18:18:12.647 ThaliTest[606:451619] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2015-12-09 18:18:12.654 ThaliTest[606:450944] jxcore: disconnect
2015-12-09 18:18:12.654 ThaliTest[606:450944] client session: disconnectFromPeer: 1449681488543.531.rFYftA==
2015-12-09 18:18:12.654 ThaliTest[606:450944] client session: disconnect
2015-12-09 18:18:12.655 ThaliTest[606:450944] client session: stateChange:2->0 1449681488543.531.rFYftA==
,2015-12-09 18:18:12.666 ThaliTest[606:450944] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2015-12-09 18:18:12.951 ThaliTest[606:451588] server session: connected
2015-12-09 18:18:12.951 ThaliTest[606:451588] server session: stateChange:1->2 1449681488543.531
,2015-12-09 18:18:12.957 ThaliTest[606:450721] server relay: socket disconnected
2015-12-09 18:18:12.958 ThaliTest[606:450721] server relay: 0x1a1a1e40 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-09 18:18:13.005 ThaliTest[606:451619] server session: not connected 1449681488543.531
,calling stopBroadcasting
,2015-12-09 18:18:13.396 ThaliTest[606:450944] jxcore: stopBroadcasting
2015-12-09 18:18:13.397 ThaliTest[606:450944] THEMultipeerSession stopping peer
2015-12-09 18:18:13.397 ThaliTest[606:450944] multipeer session: stop timer
2015-12-09 18:18:13.397 Th,aliTest[606:450944] server session: disconnect
2015-12-09 18:18:13.398 ThaliTest[606:450944] server session: stateChange:2->0 1449681488543.531
2015-12-09 18:18:13.400 ThaliTest[606:450944] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2015-12-09 18:18:13.983 ThaliTest[606:450944] jxcore: startBroadcasting
,2015-12-09 18:18:13.986 ThaliTest[606:450944] server: starting 1449681493982.606.AnURMA==
2015-12-09 18:18:13.987 ThaliTest[606:450944] multipeer session: start timer: 0x1a18c120
2015-12-09 18:18:13.987 ThaliTest[606:450944] THEMultipeerSession initializ,ed peer 1449681493982.606
2015-12-09 18:18:13.988 ThaliTest[606:450944] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2015-12-09 18:18:15.027 ThaliTest[606:450721] client: found peer: 1449681494000.531.OKyvGw==
2015-12-09 18:18:15.029 ThaliTest[606:450944] jxcore: connect 1449681494000.531.OKyvGw==
2015-12-09 18:18:15.029 ThaliTest[606:450944] client session: connect
,2015-12-09 18:18:15.029 ThaliTest[606:450944] client session: stateChange:0->1 1449681494000.531.OKyvGw==
,2015-12-09 18:18:15.361 ThaliTest[606:450721] multipeer session: reset timer
2015-12-09 18:18:15.361 ThaliTest[606:450721] multipeer session: stop timer
2015-12-09 18:18:15.362 ThaliTest[606:450721] multipeer session: start timer: 0x1a18c120
,2015-12-09 18:18:15.363 ThaliTest[606:450721] server session: connect
2015-12-09 18:18:15.364 ThaliTest[606:450721] server session: stateChange:0->1 1449681494000.531
,2015-12-09 18:18:15.373 ThaliTest[606:450721] server: accepting invitation 1449681494000.531
,2015-12-09 18:18:17.922 ThaliTest[606:451588] client session: connected
2015-12-09 18:18:17.923 ThaliTest[606:451588] client session: stateChange:1->2 1449681494000.531.OKyvGw==
,2015-12-09 18:18:17.982 ThaliTest[606:451619] client session: fireConnectCallback: 1449681494000.531.OKyvGw==
2015-12-09 18:18:17.983 ThaliTest[606:451619] jxcore: connect: success
ok 79 Should be able to connect without error
,ok 80 Port should be within range
,2015-12-09 18:18:17.988 ThaliTest[606:450944] jxcore: connect 1449681494000.531.OKyvGw==
,2015-12-09 18:18:17.989 ThaliTest[606:450944] client: already connect(ing/ed) to 1449681494000.531.OKyvGw==
,2015-12-09 18:18:17.990 ThaliTest[606:450944] jxcore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect
,2015-12-09 18:18:17.993 ThaliTest[606:450944] jxcore: disconnect
2015-12-09 18:18:17.994 ThaliTest[606:450944] client session: disconnectFromPeer: 1449681494000.531.OKyvGw==
2015-12-09 18:18:17.994 ThaliTest[606:450944] client session: disconnect
2015-12-09 18:18:17.994 ThaliTest[606:450944] client session: stateChange:2->0 1449681494000.531.OKyvGw==
,2015-12-09 18:18:18.010 ThaliTest[606:450944] jxcore: disconnect: success
,ok 82 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,2015-12-09 18:18:18.316 ThaliTest[606:451588] server session: connected
2015-12-09 18:18:18.317 ThaliTest[606:451588] server session: stateChange:1->2 1449681494000.531
,2015-12-09 18:18:18.375 ThaliTest[606:450721] server relay: socket disconnected
2015-12-09 18:18:18.376 ThaliTest[606:450721] server relay: 0x18723a10 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-09 18:18:18.440 ThaliTest[606:451611] server session: not connected 1449681494000.531
,calling stopBroadcasting
,2015-12-09 18:18:18.672 ThaliTest[606:450944] jxcore: stopBroadcasting
2015-12-09 18:18:18.672 ThaliTest[606:450944] THEMultipeerSession stopping peer
2015-12-09 18:18:18.673 ThaliTest[606:450944] multipeer session: stop timer
2015-12-09 18:18:18.673 Th,aliTest[606:450944] server session: disconnect
2015-12-09 18:18:18.673 ThaliTest[606:450944] server session: stateChange:2->0 1449681494000.531
2015-12-09 18:18:18.674 ThaliTest[606:450944] jxcore: stopBroadcasting: success
stopBroadcasting returned und,efined
# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2015-12-09 18:18:19.727 ThaliTest[606:450944] jxcore: startBroadcasting
,2015-12-09 18:18:19.731 ThaliTest[606:450944] server: starting 1449681499727.606.KecAYQ==
2015-12-09 18:18:19.732 ThaliTest[606:450944] multipeer session: start timer: 0x1a1a8c10
2015-12-09 18:18:19.733 ThaliTest[606:450944] THEMultipeerSession initializ,ed peer 1449681499727.606
2015-12-09 18:18:19.733 ThaliTest[606:450944] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2015-12-09 18:18:20.922 ThaliTest[606:450721] multipeer session: reset timer
2015-12-09 18:18:20.922 ThaliTest[606:450721] multipeer session: stop timer
2015-12-09 18:18:20.922 ThaliTest[606:450721] multipeer session: start timer: 0x1a1a8c10
2015-12-09 18:18:20.923 ThaliTest[606:450721] server session: connect
2015-12-09 18:18:20.923 ThaliTest[606:450721] server session: stateChange:0->1 1449681499739.531
,2015-12-09 18:18:20.933 ThaliTest[606:450721] server: accepting invitation 1449681499739.531
,2015-12-09 18:18:20.935 ThaliTest[606:450721] client: found peer: 1449681499739.531.rdp//A==
,2015-12-09 18:18:20.937 ThaliTest[606:450944] jxcore: connect 1449681499739.531.rdp//A==
2015-12-09 18:18:20.938 ThaliTest[606:450944] client session: connect
,2015-12-09 18:18:20.948 ThaliTest[606:450944] client session: stateChange:0->1 1449681499739.531.rdp//A==
,2015-12-09 18:18:22.659 ThaliTest[606:450721] client: found peer: 1449681488543.531.rFYftA==
2015-12-09 18:18:22.661 ThaliTest[606:450944] jxcore: connect 1449681488543.531.rFYftA==
2015-12-09 18:18:22.661 ThaliTest[606:450944] client session: connect
2015-12-09 18:18:22.662 ThaliTest[606:450944] client session: stateChange:0->1 1449681488543.531.rFYftA==
,2015-12-09 18:18:24.134 ThaliTest[606:451588] client session: connected
2015-12-09 18:18:24.134 ThaliTest[606:451588] client session: stateChange:1->2 1449681499739.531.rdp//A==
2015-12-09 18:18:24.136 ThaliTest[606:451588] client session: fireConnectCallback: 1449681499739.531.rdp//A==
2015-12-09 18:18:24.136 ThaliTest[606:451588] jxcore: connect: success
ok 84 Should be able to connect without error
ok 85 Port should be within range
,2015-12-09 18:18:24.142 ThaliTest[606:450944] jxcore: disconnect
2015-12-09 18:18:24.142 ThaliTest[606:450944] client session: disconnectFromPeer: 1449681499739.531.rdp//A==
2015-12-09 18:18:24.142 ThaliTest[606:450944] client session: disconnect
2015-1,2-09 18:18:24.143 ThaliTest[606:450944] client session: stateChange:2->0 1449681499739.531.rdp//A==
,2015-12-09 18:18:24.150 ThaliTest[606:450944] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
2015-12-09 18:18:24.151 ThaliTest[606:450944] jxcore: disconnect
2015-12-09 18:18:24.153 ThaliTest[606:450944] jxcore: disconnect: fail
,ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,2015-12-09 18:18:24.269 ThaliTest[606:451588] server session: connected
2015-12-09 18:18:24.269 ThaliTest[606:451588] server session: stateChange:1->2 1449681499739.531
,2015-12-09 18:18:24.272 ThaliTest[606:450721] server relay: socket disconnected
,2015-12-09 18:18:24.272 ThaliTest[606:450721] server relay: 0x1871e1a0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-09 18:18:24.403 ThaliTest[606:451619] server session: not connected 1449681499739.531
,calling stopBroadcasting
,2015-12-09 18:18:24.897 ThaliTest[606:450944] jxcore: stopBroadcasting
2015-12-09 18:18:24.897 ThaliTest[606:450944] THEMultipeerSession stopping peer
2015-12-09 18:18:24.898 ThaliTest[606:450944] multipeer session: stop timer
2015-12-09 18:18:24.898 Th,aliTest[606:450944] client session: disconnect
2015-12-09 18:18:24.898 ThaliTest[606:450944] client session: stateChange:1->0 1449681488543.531.rFYftA==
2015-12-09 18:18:24.899 ThaliTest[606:450944] server session: disconnect
2015-12-09 18:18:24.899 Tha,liTest[606:450944] server session: stateChange:2->0 1449681499739.531
2015-12-09 18:18:24.901 ThaliTest[606:450944] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter handles socket disconnect correctly
,# teardown
,2015-12-09 18:18:25.362 ThaliTest[606:450944] jxcore: startBroadcasting
,2015-12-09 18:18:25.366 ThaliTest[606:450944] server: starting 1449681505361.606.vRLobg==
2015-12-09 18:18:25.367 ThaliTest[606:450944] multipeer session: start timer: 0x18727b70
2015-12-09 18:18:25.367 ThaliTest[606:450944] THEMultipeerSession initializ,ed peer 1449681505361.606
2015-12-09 18:18:25.367 ThaliTest[606:450944] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
echo server started
,2015-12-09 18:18:26.147 ThaliTest[606:450721] client: found peer: 1449681499739.531.rdp//A==
[{"peerIdentifier":"1449681499739.531.rdp//A==","peerName":"(null)","peerAvailable":true}]
,2015-12-09 18:18:26.150 ThaliTest[606:450944] jxcore: connect 1449681499739.531.rdp//A==
,2015-12-09 18:18:26.151 ThaliTest[606:450944] client session: connect
,2015-12-09 18:18:26.151 ThaliTest[606:450944] client session: stateChange:0->1 1449681499739.531.rdp//A==
,2015-12-09 18:18:27.229 ThaliTest[606:450721] client: found peer: 1449681505361.531.djsk5A==
[{"peerIdentifier":"1449681505361.531.djsk5A==","peerName":"(null)","peerAvailable":true}]
2015-12-09 18:18:27.231 ThaliTest[606:450944] jxcore: connect 14496815,05361.531.djsk5A==
2015-12-09 18:18:27.232 ThaliTest[606:450944] client session: connect
,2015-12-09 18:18:27.232 ThaliTest[606:450944] client session: stateChange:0->1 1449681505361.531.djsk5A==
,2015-12-09 18:18:28.029 ThaliTest[606:450721] multipeer session: reset timer
2015-12-09 18:18:28.029 ThaliTest[606:450721] multipeer session: stop timer
2015-12-09 18:18:28.030 ThaliTest[606:450721] multipeer session: start timer: 0x18727b70
2015-12-09 18:18:28.030 ThaliTest[606:450721] server session: connect
2015-12-09 18:18:28.030 ThaliTest[606:450721] server session: stateChange:0->1 1449681505361.531
,2015-12-09 18:18:28.062 ThaliTest[606:450721] server: accepting invitation 1449681505361.531
,2015-12-09 18:18:30.690 ThaliTest[606:451588] client session: connected
2015-12-09 18:18:30.690 ThaliTest[606:451588] client session: stateChange:1->2 1449681505361.531.djsk5A==
,2015-12-09 18:18:30.753 ThaliTest[606:451618] client session: fireConnectCallback: 1449681505361.531.djsk5A==
2015-12-09 18:18:30.754 ThaliTest[606:451618] jxcore: connect: success
,ok 89 Should be able to connect without error
,ok 90 Port should be within range
,ok 91 First connect should succeed
,2015-12-09 18:18:30.814 ThaliTest[606:450721] client: relay established
2015-12-09 18:18:30.814 ThaliTest[606:450721] client: new accepted socket: 0x1a1b1740
,ok 92 the test messages should be equal
,ok 93 First send should succeed
,2015-12-09 18:18:30.960 ThaliTest[606:450721] client: socket closed
2015-12-09 18:18:30.961 ThaliTest[606:450721] client relay: socket disconnected
2015-12-09 18:18:30.961 ThaliTest[606:450721] client relay: 0x1a1b1740 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-09 18:18:30.962 ThaliTest[606:450721] client session: socket closed: 1449681505361.531.djsk5A==
2015-12-09 18:18:30.,962 ThaliTest[606:450721] client session: onLinkFailure: 1449681505361.531.djsk5A==
2015-12-09 18:18:30.962 ThaliTest[606:450721] client session: disconnect
2015-12-09 18:18:30.962 ThaliTest[606:450721] client session: stateChange:2->0 1449681505361.531.,djsk5A==
,2015-12-09 18:18:30.981 ThaliTest[606:450721] client session: fireConnectionErrorEvent: 1449681505361.531.djsk5A==
2015-12-09 18:18:30.984 ThaliTest[606:450944] jxcore: connect 1449681505361.531.djsk5A==
2015-12-09 18:18:30.985 ThaliTest[606:450944] client session: connect
2015-12-09 18:18:30.985 ThaliTest[606:450944] client session: stateChange:0->1 1449681505361.531.djsk5A==
,2015-12-09 18:18:31.274 ThaliTest[606:451618] server session: connected
2015-12-09 18:18:31.274 ThaliTest[606:451618] server session: stateChange:1->2 1449681505361.531
,2015-12-09 18:18:31.346 ThaliTest[606:450721] server relay: connected (to port: 5001)
,2015-12-09 18:18:31.540 ThaliTest[606:451588] server session: not connected 1449681505361.531
,2015-12-09 18:18:31.566 ThaliTest[606:450721] multipeer session: reset timer
2015-12-09 18:18:31.567 ThaliTest[606:450721] multipeer session: stop timer
2015-12-09 18:18:31.567 ThaliTest[606:450721] multipeer session: start timer: 0x18727b70
2015-12-09 ,18:18:31.567 ThaliTest[606:450721] server: disconnecting to refresh session (1449681505361.531)
2015-12-09 18:18:31.568 ThaliTest[606:450721] server session: disconnect
2015-12-09 18:18:31.568 ThaliTest[606:450721] server session: stateChange:2->0 144968,1505361.531
,2015-12-09 18:18:31.573 ThaliTest[606:450721] server session: connect
2015-12-09 18:18:31.573 ThaliTest[606:450721] server session: stateChange:0->1 1449681505361.531
,2015-12-09 18:18:31.586 ThaliTest[606:450721] server: accepting invitation 1449681505361.531
,2015-12-09 18:18:33.363 ThaliTest[606:451619] client session: connected
,2015-12-09 18:18:33.364 ThaliTest[606:451619] client session: stateChange:1->2 1449681505361.531.djsk5A==
,2015-12-09 18:18:33.737 ThaliTest[606:451609] client session: fireConnectCallback: 1449681505361.531.djsk5A==
2015-12-09 18:18:33.737 ThaliTest[606:451609] jxcore: connect: success
,ok 94 Should be able to connect without error
ok 95 Port should be within range
ok 96 Second connect should succeed
,2015-12-09 18:18:33.775 ThaliTest[606:450721] client: relay established
2015-12-09 18:18:33.775 ThaliTest[606:450721] client: new accepted socket: 0x1a1b18b0
,2015-12-09 18:18:34.347 ThaliTest[606:451609] server session: connected
2015-12-09 18:18:34.347 ThaliTest[606:451609] server session: stateChange:1->2 1449681505361.531
,2015-12-09 18:18:34.635 ThaliTest[606:450721] server relay: connected (to port: 5001)
,2015-12-09 18:18:34.768 ThaliTest[606:451609] server session: not connected 1449681505361.531
,ok 97 the test messages should be equal
,ok 98 Second send should succeed
,# setup
,2015-12-09 18:18:35.747 ThaliTest[606:450721] client: socket closed
2015-12-09 18:18:35.747 ThaliTest[606:450721] client relay: socket disconnected
2015-12-09 18:18:35.748 ThaliTest[606:450721] client relay: 0x1a1b18b0 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-09 18:18:35.748 ThaliTest[606:450721] client session: socket closed: 1449681505361.531.djsk5A==
2015-12-09 18:18:35.,748 ThaliTest[606:450721] client session: onLinkFailure: 1449681505361.531.djsk5A==
2015-12-09 18:18:35.748 ThaliTest[606:450721] client session: disconnect
2015-12-09 18:18:35.749 ThaliTest[606:450721] client session: stateChange:2->0 1449681505361.531.djsk5A==
,2015-12-09 18:18:35.767 ThaliTest[606:450721] client session: fireConnectionErrorEvent: 1449681505361.531.djsk5A==
,calling stopBroadcasting
,2015-12-09 18:18:35.951 ThaliTest[606:450944] jxcore: stopBroadcasting
2015-12-09 18:18:35.951 ThaliTest[606:450944] THEMultipeerSession stopping peer
2015-12-09 18:18:35.951 ThaliTest[606:450944] multipeer session: stop timer
2015-12-09 18:18:35.952 Th,aliTest[606:450944] client session: disconnect
2015-12-09 18:18:35.952 ThaliTest[606:450944] client session: stateChange:1->0 1449681499739.531.rdp//A==
2015-12-09 18:18:35.953 ThaliTest[606:450944] server session: disconnect
2015-12-09 18:18:35.953 Tha,liTest[606:450944] server session: stateChange:2->0 1449681505361.531
,2015-12-09 18:18:36.437 ThaliTest[606:450944] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/D64E9E7A-E293-4DB8-986D-896A3089D9A4/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 99 starting event should occur in right order
,2015-12-09 18:18:37.100 ThaliTest[606:450944] jxcore: startBroadcasting
,2015-12-09 18:18:37.101 ThaliTest[606:450944] server: starting QOtdJPhG4NHuDWMRi7TX5g.KBRJdA==
2015-12-09 18:18:37.101 ThaliTest[606:450944] multipeer session: start timer: 0x1a1b29b0
2015-12-09 18:18:37.101 ThaliTest[606:450944] THEMultipeerSession initialized peer QOtdJPhG4NHuDWMRi7TX5g
2015-12-09 18:18:37.101 ThaliTest[606:450944] jxcore: startBroadcasting: success
ok 100 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
ok 101 stopping event should occur in ,right order
About to call stopBroadcasting
2015-12-09 18:18:37.103 ThaliTest[606:450944] jxcore: stopBroadcasting
2015-12-09 18:18:37.103 ThaliTest[606:450944] THEMultipeerSession stopping peer
2015-12-09 18:18:37.103 ThaliTest[606:450944] multipeer se,ssion: stop timer
2015-12-09 18:18:37.103 ThaliTest[606:450944] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
,ok 102 stopped event should occur in right order
,mux server bridge listener closed
# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/D64E9E7A-E293-4DB8-986D-896A3089D9A4/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,",failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2015-12-09 18:18:38.012 ThaliTest[606:450944] jxcore: startBroadcasting
,2015-12-09 18:18:38.016 ThaliTest[606:450944] server: starting QOtdJPhG4NHuDWMRi7TX5g.PfNOHw==
2015-12-09 18:18:38.016 ThaliTest[606:450944] multipeer session: start timer: 0x18709170
2015-12-09 18:18:38.017 ThaliTest[606:450944] THEMultipeerSession init,ialized peer QOtdJPhG4NHuDWMRi7TX5g
2015-12-09 18:18:38.017 ThaliTest[606:450944] jxcore: startBroadcasting: success
ok 103 getDeviceIdentity should not return an error
ok 104 deviceName should not be null
,Now in TRM stop
,State of this._isStarted: true
,About to call stopBroadcasting
,2015-12-09 18:18:38.035 ThaliTest[606:450944] jxcore: stopBroadcasting
,2015-12-09 18:18:38.036 ThaliTest[606:450944] THEMultipeerSession stopping peer
,2015-12-09 18:18:38.038 ThaliTest[606:450944] multipeer session: stop timer
,2015-12-09 18:18:38.045 ThaliTest[606:450944] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,mux server bridge listener closed
,Tests Complete

```
