#### Test 50650278d0426ce_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278d0426ce/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/7B5BDE5C-0F0E-4CAF-8D61-405A2344EA58/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/7B5BDE5C-0F0E-4CAF-8D61-405A2344EA58/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278d0426ce/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278d0426ce/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1B7DBF28-3345-447A-8CE8-B8B1A86DF096/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52400"
,(lldb)     command script import "/tmp/7B5BDE5C-0F0E-4CAF-8D61-405A2344EA58/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-09 18:09:40.454 ThaliTest[531:516005] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9C7C8890-0B0F-4027-AE8C-E2543CC3946E/Library/Cookies/Cookies.binarycookies
,2015-12-09 18:09:40.583 ThaliTest[531:516005] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-09 18:09:40.585 ThaliTest[531:516005] Multi-tasking -> Device: YES, App: YES
,2015-12-09 18:09:40.592 ThaliTest[531:516005] Unlimited access to network resources
,2015-12-09 18:09:40.606 ThaliTest[531:516005] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-09 18:09:51.047 ThaliTest[531:516005] Resetting plugins due to page load.
,2015-12-09 18:09:55.216 ThaliTest[531:516005] Finished load of: file:///var/mobile/Containers/Bundle/Application/1B7DBF28-3345-447A-8CE8-B8B1A86DF096/ThaliTest.app/www/index.html
,2015-12-09 18:09:55.429 ThaliTest[531:516005] JXcore Cordova plugin initializing
,2015-12-09 18:09:55.431 ThaliTest[531:516179] JXcore instance initializing
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
,2015-12-09 18:18:05.605 ThaliTest[531:516179] jxcore: startBroadcasting
,2015-12-09 18:18:05.614 ThaliTest[531:516179] server: starting 1449681485604.531.FkvQXQ==
,2015-12-09 18:18:05.615 ThaliTest[531:516179] multipeer session: start timer: 0x1d8118e0
,2015-12-09 18:18:05.616 ThaliTest[531:516179] THEMultipeerSession initialized peer 1449681485604.531
,2015-12-09 18:18:05.616 ThaliTest[531:516179] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
2015-12-09 18:18:05.618 ThaliTest[531:516179] jxcore: stopBroadcasting
2015-12-09 18:18:05.618 ThaliTest[531:516179] THEMultipeerSession stopping peer
2015-12-09 18:18:05.619 ThaliTest[531:516,179] multipeer session: stop timer
2015-12-09 18:18:05.619 ThaliTest[531:516179] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2015-12-09 18:18:05.621 ThaliTest[531:516179] jxcore: startBroadcasting
,2015-12-09 18:18:05.625 ThaliTest[531:516179] server: starting 1449681485620.531.d7EGQA==
2015-12-09 18:18:05.625 ThaliTest[531:516179] multipeer session: start timer: 0x1a7f6e00
2015-12-09 18:18:05.626 ThaliTest[531:516179] THEMultipeerSession initializ,ed peer 1449681485620.531
2015-12-09 18:18:05.627 ThaliTest[531:516179] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2015-12-09 18:18:05.628 ThaliTest[531:516179] jxcore: stopBroadcasting
2015-12-09 18,:18:05.628 ThaliTest[531:516179] THEMultipeerSession stopping peer
2015-12-09 18:18:05.628 ThaliTest[531:516179] multipeer session: stop timer
2015-12-09 18:18:05.629 ThaliTest[531:516179] jxcore: stopBroadcasting: success
ok 48 Should be able to call s,topBroadcasting without error
2015-12-09 18:18:05.630 ThaliTest[531:516179] jxcore: startBroadcasting
,2015-12-09 18:18:05.635 ThaliTest[531:516179] server: starting 1449681485630.531.3zpLEw==
2015-12-09 18:18:05.635 ThaliTest[531:516179] multipeer session: start timer: 0x1a7f8b10
2015-12-09 18:18:05.635 ThaliTest[531:516179] THEMultipeerSession initializ,ed peer 1449681485630.531
2015-12-09 18:18:05.636 ThaliTest[531:516179] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2015-12-09 18:18:05.637 ThaliTest[531:516179] jxcore: stopBroadcasting
2015-12-09 18,:18:05.637 ThaliTest[531:516179] THEMultipeerSession stopping peer
2015-12-09 18:18:05.637 ThaliTest[531:516179] multipeer session: stop timer
2015-12-09 18:18:05.638 ThaliTest[531:516179] jxcore: stopBroadcasting: success
ok 50 Should be able to call s,topBroadcasting without error
2015-12-09 18:18:05.639 ThaliTest[531:516179] jxcore: startBroadcasting
,2015-12-09 18:18:05.677 ThaliTest[531:516179] server: starting 1449681485639.531.K1yilw==
,2015-12-09 18:18:05.690 ThaliTest[531:516179] multipeer session: start timer: 0x1d80d220
,2015-12-09 18:18:05.695 ThaliTest[531:516179] THEMultipeerSession initialized peer 1449681485639.531
,2015-12-09 18:18:05.696 ThaliTest[531:516179] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2015-12-09 18:18:05.702 ThaliTest[531:516179] jxcore: stopBroadcasting
,2015-12-09 18:18:05.703 ThaliTest[531:516179] THEMultipeerSession stopping peer
,2015-12-09 18:18:05.706 ThaliTest[531:516179] multipeer session: stop timer
,2015-12-09 18:18:05.707 ThaliTest[531:516179] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2015-12-09 18:18:05.718 ThaliTest[531:516179] jxcore: startBroadcasting
,2015-12-09 18:18:05.721 ThaliTest[531:516179] server: starting 1449681485717.531.m5fvTw==
,2015-12-09 18:18:05.723 ThaliTest[531:516179] multipeer session: start timer: 0x1a7fbd50
,2015-12-09 18:18:05.730 ThaliTest[531:516179] THEMultipeerSession initialized peer 1449681485717.531
,2015-12-09 18:18:05.731 ThaliTest[531:516179] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2015-12-09 18:18:05.733 ThaliTest[531:516179] jxcore: stopBroadcasting
,2015-12-09 18:18:05.734 ThaliTest[531:516179] THEMultipeerSession stopping peer
,2015-12-09 18:18:05.735 ThaliTest[531:516179] multipeer session: stop timer
,2015-12-09 18:18:05.736 ThaliTest[531:516179] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2015-12-09 18:18:05.742 ThaliTest[531:516179] jxcore: startBroadcasting
,2015-12-09 18:18:05.745 ThaliTest[531:516179] server: starting 1449681485742.531.WbP/gg==
,2015-12-09 18:18:05.748 ThaliTest[531:516179] multipeer session: start timer: 0x1d8109b0
2015-12-09 18:18:05.752 ThaliTest[531:516179] THEMultipeerSession initialized peer 1449681485742.531
,2015-12-09 18:18:05.754 ThaliTest[531:516179] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2015-12-09 18:18:05.757 ThaliTest[531:516179] jxcore: stopBroadcasting
,2015-12-09 18:18:05.758 ThaliTest[531:516179] THEMultipeerSession stopping peer
,2015-12-09 18:18:05.759 ThaliTest[531:516179] multipeer session: stop timer
,2015-12-09 18:18:05.764 ThaliTest[531:516179] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2015-12-09 18:18:05.767 ThaliTest[531:516179] jxcore: startBroadcasting
,2015-12-09 18:18:05.770 ThaliTest[531:516179] server: starting 1449681485766.531.db1F/w==
,2015-12-09 18:18:05.772 ThaliTest[531:516179] multipeer session: start timer: 0x1d80fe90
,2015-12-09 18:18:05.779 ThaliTest[531:516179] THEMultipeerSession initialized peer 1449681485766.531
,2015-12-09 18:18:05.780 ThaliTest[531:516179] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2015-12-09 18:18:05.782 ThaliTest[531:516179] jxcore: stopBroadcasting
,2015-12-09 18:18:05.783 ThaliTest[531:516179] THEMultipeerSession stopping peer
,2015-12-09 18:18:05.784 ThaliTest[531:516179] multipeer session: stop timer
,2015-12-09 18:18:05.789 ThaliTest[531:516179] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2015-12-09 18:18:05.791 ThaliTest[531:516179] jxcore: startBroadcasting
,2015-12-09 18:18:05.794 ThaliTest[531:516179] server: starting 1449681485791.531.Z9NVBg==
,2015-12-09 18:18:05.801 ThaliTest[531:516179] multipeer session: start timer: 0x1d8104a0
,2015-12-09 18:18:05.803 ThaliTest[531:516179] THEMultipeerSession initialized peer 1449681485791.531
,2015-12-09 18:18:05.804 ThaliTest[531:516179] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2015-12-09 18:18:05.807 ThaliTest[531:516179] jxcore: stopBroadcasting
,2015-12-09 18:18:05.807 ThaliTest[531:516179] THEMultipeerSession stopping peer
,2015-12-09 18:18:05.809 ThaliTest[531:516179] multipeer session: stop timer
,2015-12-09 18:18:05.815 ThaliTest[531:516179] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2015-12-09 18:18:05.818 ThaliTest[531:516179] jxcore: startBroadcasting
,2015-12-09 18:18:05.821 ThaliTest[531:516179] server: starting 1449681485817.531./WaukA==
,2015-12-09 18:18:05.822 ThaliTest[531:516179] multipeer session: start timer: 0x1d8104a0
,2015-12-09 18:18:05.825 ThaliTest[531:516179] THEMultipeerSession initialized peer 1449681485817.531
,2015-12-09 18:18:05.831 ThaliTest[531:516179] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2015-12-09 18:18:05.833 ThaliTest[531:516179] jxcore: stopBroadcasting
,2015-12-09 18:18:05.834 ThaliTest[531:516179] THEMultipeerSession stopping peer
,2015-12-09 18:18:05.835 ThaliTest[531:516179] multipeer session: stop timer
,2015-12-09 18:18:05.837 ThaliTest[531:516179] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2015-12-09 18:18:05.841 ThaliTest[531:516179] jxcore: startBroadcasting
,2015-12-09 18:18:05.843 ThaliTest[531:516179] server: starting 1449681485840.531.H5qQsA==
,2015-12-09 18:18:05.845 ThaliTest[531:516179] multipeer session: start timer: 0x1a716510
,2015-12-09 18:18:05.850 ThaliTest[531:516179] THEMultipeerSession initialized peer 1449681485840.531
,2015-12-09 18:18:05.852 ThaliTest[531:516179] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2015-12-09 18:18:05.854 ThaliTest[531:516179] jxcore: stopBroadcasting
,2015-12-09 18:18:05.855 ThaliTest[531:516179] THEMultipeerSession stopping peer
,2015-12-09 18:18:05.856 ThaliTest[531:516179] multipeer session: stop timer
,2015-12-09 18:18:05.859 ThaliTest[531:516179] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2015-12-09 18:18:06.140 ThaliTest[531:516179] jxcore: startBroadcasting
,2015-12-09 18:18:06.143 ThaliTest[531:516179] server: starting 1449681486140.531.yFyE8A==
2015-12-09 18:18:06.144 ThaliTest[531:516179] multipeer session: start timer: 0x1d80a9c0
2015-12-09 18:18:06.144 ThaliTest[531:516179] THEMultipeerSession initializ,ed peer 1449681486140.531
2015-12-09 18:18:06.144 ThaliTest[531:516179] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2015-12-09 18:18:06.146 ThaliTest[531:516179] jxcore: startBroadcasting
2015-12-09 18:18:06.146 ThaliTest[531:516179] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
2015-12-09 18:18:06.147 ThaliTest[531:516179] jxcore: stopBroadcasting
2015-12-09 18:18:06.148 ThaliTest[531:516179] THEMultipeerSession stopping peer
2015-12-09 18:18:06.148 ThaliTest[531:516179] multipeer session: stop timer
,2015-12-09 18:18:06.148 ThaliTest[531:516179] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2015-12-09 18:18:06.622 ThaliTest[531:516179] jxcore: startBroadcasting
,2015-12-09 18:18:06.625 ThaliTest[531:516179] server: starting 1449681486622.531.QF5glg==
2015-12-09 18:18:06.625 ThaliTest[531:516179] multipeer session: start timer: 0x1d808550
2015-12-09 18:18:06.626 ThaliTest[531:516179] THEMultipeerSession initializ,ed peer 1449681486622.531
2015-12-09 18:18:06.626 ThaliTest[531:516179] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2015-12-09 18:18:06.627 ThaliTest[531:516179] jxcore: connect foobar
2015-12-09 18:1,8:06.628 ThaliTest[531:516179] client: unknown peer foobar
2015-12-09 18:18:06.628 ThaliTest[531:516179] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
,2015-12-09 18:18:06.630 ThaliTest[531:516179] jxcore: stopBroadcasting
2015-12-09 18:18:06.630 ThaliTest[531:516179] THEMultipeerSession stopping peer
2015-12-09 18:18:06.630 ThaliTest[531:516179] multipeer session: stop timer
2015-12-09 18:18:06.630 ThaliTest[531:516179] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2015-12-09 18:18:08.035 ThaliTest[531:516179] jxcore: startBroadcasting
,2015-12-09 18:18:08.038 ThaliTest[531:516179] server: starting 1449681488035.531.iAzD0g==
2015-12-09 18:18:08.039 ThaliTest[531:516179] multipeer session: start timer: 0x1d809c40
2015-12-09 18:18:08.039 ThaliTest[531:516179] THEMultipeerSession initialized peer 1449681488035.531
2015-12-09 18:18:08.039 ThaliTest[531:516179] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2015-12-09 18:18:08.040 ThaliTest[531:516179] jxcore: disconnect
2015-12-09 18:18:08,.041 ThaliTest[531:516179] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
2015-12-09 18:18:08.042 ThaliTest[531:516179] jxcore: stopBroadcasting
2015-12-09 18:18:08.042 ThaliTest[531:516179] THEMultipeerSession stopping pe,er
2015-12-09 18:18:08.042 ThaliTest[531:516179] multipeer session: stop timer
2015-12-09 18:18:08.043 ThaliTest[531:516179] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2015-12-09 18:18:08.543 ThaliTest[531:516179] jxcore: startBroadcasting
,2015-12-09 18:18:08.546 ThaliTest[531:516179] server: starting 1449681488543.531.rFYftA==
2015-12-09 18:18:08.546 ThaliTest[531:516179] multipeer session: start timer: 0x1d803bf0
2015-12-09 18:18:08.547 ThaliTest[531:516179] THEMultipeerSession initializ,ed peer 1449681488543.531
2015-12-09 18:18:08.547 ThaliTest[531:516179] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2015-12-09 18:18:09.886 ThaliTest[531:516005] client: found peer: 1449681488543.606.lSOQGw==
2015-12-09 18:18:09.887 ThaliTest[531:516179] jxcore: connect 1449681488543.606.lSOQGw==
2015-12-09 18:18:09.888 ThaliTest[531:516179] client session: connect
2,015-12-09 18:18:09.888 ThaliTest[531:516179] client session: stateChange:0->1 1449681488543.606.lSOQGw==
,2015-12-09 18:18:09.937 ThaliTest[531:516005] multipeer session: reset timer
2015-12-09 18:18:09.938 ThaliTest[531:516005] multipeer session: stop timer
2015-12-09 18:18:09.938 ThaliTest[531:516005] multipeer session: start timer: 0x1d803bf0
2015-12-09 ,18:18:09.938 ThaliTest[531:516005] server session: connect
2015-12-09 18:18:09.939 ThaliTest[531:516005] server session: stateChange:0->1 1449681488543.606
2015-12-09 18:18:09.948 ThaliTest[531:516005] server: accepting invitation 1449681488543.606
,2015-12-09 18:18:12.642 ThaliTest[531:517067] server session: connected
2015-12-09 18:18:12.642 ThaliTest[531:517067] server session: stateChange:1->2 1449681488543.606
,2015-12-09 18:18:12.666 ThaliTest[531:516005] server relay: socket disconnected
2015-12-09 18:18:12.666 ThaliTest[531:516005] server relay: 0x1d800d10 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-09 18:18:12.696 ThaliTest[531:517069] server session: not connected 1449681488543.606
,2015-12-09 18:18:12.954 ThaliTest[531:517067] client session: connected
2015-12-09 18:18:12.954 ThaliTest[531:517067] client session: stateChange:1->2 1449681488543.606.lSOQGw==
,2015-12-09 18:18:12.972 ThaliTest[531:517069] client session: fireConnectCallback: 1449681488543.606.lSOQGw==
2015-12-09 18:18:12.972 ThaliTest[531:517069] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2015-12-09 18:18:12.976 ThaliTest[531:516179] jxcore: disconnect
,2015-12-09 18:18:12.976 ThaliTest[531:516179] client session: disconnectFromPeer: 1449681488543.606.lSOQGw==
,2015-12-09 18:18:12.977 ThaliTest[531:516179] client session: disconnect
,2015-12-09 18:18:12.977 ThaliTest[531:516179] client session: stateChange:2->0 1449681488543.606.lSOQGw==
,2015-12-09 18:18:12.988 ThaliTest[531:516179] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2015-12-09 18:18:13.410 ThaliTest[531:516179] jxcore: stopBroadcasting
2015-12-09 18:18:13.410 ThaliTest[531:516179] THEMultipeerSession stopping peer
2015-12-09 18:18:13.411 ThaliTest[531:516179] multipeer session: stop timer
2015-12-09 18:18:13.411 Th,aliTest[531:516179] server session: disconnect
2015-12-09 18:18:13.412 ThaliTest[531:516179] server session: stateChange:2->0 1449681488543.606
2015-12-09 18:18:13.412 ThaliTest[531:516179] jxcore: stopBroadcasting: success
stopBroadcasting returned und,efined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2015-12-09 18:18:14.001 ThaliTest[531:516179] jxcore: startBroadcasting
,2015-12-09 18:18:14.004 ThaliTest[531:516179] server: starting 1449681494000.531.OKyvGw==
2015-12-09 18:18:14.005 ThaliTest[531:516179] multipeer session: start timer: 0x15d4d480
2015-12-09 18:18:14.005 ThaliTest[531:516179] THEMultipeerSession initializ,ed peer 1449681494000.531
2015-12-09 18:18:14.005 ThaliTest[531:516179] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2015-12-09 18:18:15.173 ThaliTest[531:516005] multipeer session: reset timer
2015-12-09 18:18:15.173 ThaliTest[531:516005] multipeer session: stop timer
2015-12-09 18:18:15.173 ThaliTest[531:516005] multipeer session: start timer: 0x15d4d480
2015-12-09 18:18:15.173 ThaliTest[531:516005] server session: connect
2015-12-09 18:18:15.173 ThaliTest[531:516005] server session: stateChange:0->1 1449681493982.606
,2015-12-09 18:18:15.180 ThaliTest[531:516005] server: accepting invitation 1449681493982.606
,2015-12-09 18:18:15.181 ThaliTest[531:516005] client: found peer: 1449681493982.606.AnURMA==
,2015-12-09 18:18:15.182 ThaliTest[531:516179] jxcore: connect 1449681493982.606.AnURMA==
2015-12-09 18:18:15.183 ThaliTest[531:516179] client session: connect
,2015-12-09 18:18:15.183 ThaliTest[531:516179] client session: stateChange:0->1 1449681493982.606.AnURMA==
,2015-12-09 18:18:17.938 ThaliTest[531:517068] server session: connected
2015-12-09 18:18:17.938 ThaliTest[531:517068] server session: stateChange:1->2 1449681493982.606
,2015-12-09 18:18:17.992 ThaliTest[531:516005] server relay: socket disconnected
2015-12-09 18:18:17.993 ThaliTest[531:516005] server relay: 0x1d923340 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocaliz,edFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-09 18:18:18.053 ThaliTest[531:517066] server session: not connected 1449681493982.606
,2015-12-09 18:18:18.330 ThaliTest[531:517067] client session: connected
2015-12-09 18:18:18.330 ThaliTest[531:517067] client session: stateChange:1->2 1449681493982.606.AnURMA==
,2015-12-09 18:18:18.381 ThaliTest[531:517068] client session: fireConnectCallback: 1449681493982.606.AnURMA==
2015-12-09 18:18:18.382 ThaliTest[531:517068] jxcore: connect: success
ok 79 Should be able to connect without error
,ok 80 Port should be within range
2015-12-09 18:18:18.385 ThaliTest[531:516179] jxcore: connect 1449681493982.606.AnURMA==
2015-12-09 18:18:18.386 ThaliTest[531:516179] client: already connect(ing/ed) to 1449681493982.606.AnURMA==
2015-12-09 18:18:18.386 ThaliTest[531:516179] jxcore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect
2015-12-09 18:18:18.388 ThaliTest[531:516179] jxcore: disconnect
2015-12-09 18:18:18.388 ThaliTest[531:516179] client session: disconnectFromPeer: 1449681493982.606.AnURMA==
2015-12-09 18:18:18.388 ThaliTest[531:51617,9] client session: disconnect
2015-12-09 18:18:18.388 ThaliTest[531:516179] client session: stateChange:2->0 1449681493982.606.AnURMA==
,2015-12-09 18:18:18.400 ThaliTest[531:516179] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2015-12-09 18:18:18.685 ThaliTest[531:516179] jxcore: stopBroadcasting
2015-12-09 18:18:18.686 ThaliTest[531:516179] THEMultipeerSession stopping peer
2015-12-09 18:18:18.687 ThaliTest[531:516179] multipeer session: stop timer
2015-12-09 18:18:18.687 ThaliTest[531:516179] server session: disconnect
2015-12-09 18:18:18.687 ThaliTest[531:516179] server session: stateChange:2->0 1449681493982.606
2015-12-09 18:18:18.688 ThaliTest[531:516179] jxcore: stopBroadcasting: success
stopBroadcasting returned und,efined
# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2015-12-09 18:18:19.739 ThaliTest[531:516179] jxcore: startBroadcasting
,2015-12-09 18:18:19.742 ThaliTest[531:516179] server: starting 1449681499739.531.rdp//A==
2015-12-09 18:18:19.742 ThaliTest[531:516179] multipeer session: start timer: 0x1a709b50
2015-12-09 18:18:19.743 ThaliTest[531:516179] THEMultipeerSession initialized peer 1449681499739.531
2015-12-09 18:18:19.743 ThaliTest[531:516179] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2015-12-09 18:18:19.824 ThaliTest[531:516005] client: found peer: 1449681493982.606.AnURMA==
2015-12-09 18:18:19.826 ThaliTest[531:516179] jxcore: connect 1449681493982.606.AnURMA==
2015-12-09 18:18:19.826 ThaliTest[531:516179] client session: connect
2,015-12-09 18:18:19.826 ThaliTest[531:516179] client session: stateChange:0->1 1449681493982.606.AnURMA==
,2015-12-09 18:18:20.817 ThaliTest[531:516005] client: found peer: 1449681499727.606.KecAYQ==
2015-12-09 18:18:20.819 ThaliTest[531:516179] jxcore: connect 1449681499727.606.KecAYQ==
,2015-12-09 18:18:20.819 ThaliTest[531:516179] client session: connect
2015-12-09 18:18:20.821 ThaliTest[531:516179] client session: stateChange:0->1 1449681499727.606.KecAYQ==
,2015-12-09 18:18:21.038 ThaliTest[531:516005] multipeer session: reset timer
2015-12-09 18:18:21.038 ThaliTest[531:516005] multipeer session: stop timer
2015-12-09 18:18:21.038 ThaliTest[531:516005] multipeer session: start timer: 0x1a709b50
,2015-12-09 18:18:21.039 ThaliTest[531:516005] server session: connect
2015-12-09 18:18:21.040 ThaliTest[531:516005] server session: stateChange:0->1 1449681499727.606
,2015-12-09 18:18:21.046 ThaliTest[531:516005] server: accepting invitation 1449681499727.606
,2015-12-09 18:18:21.871 ThaliTest[531:516005] client: lost peer: 1449681493982.606.AnURMA==
2015-12-09 18:18:21.872 ThaliTest[531:516005] client session: onPeerLost: 1449681493982.606.AnURMA==
2015-12-09 18:18:21.872 ThaliTest[531:516005] client session:, onLinkFailure: 1449681493982.606.AnURMA==
2015-12-09 18:18:21.872 ThaliTest[531:516005] client session: disconnect
2015-12-09 18:18:21.872 ThaliTest[531:516005] client session: stateChange:1->0 1449681493982.606.AnURMA==
2015-12-09 18:18:21.873 ThaliTe,st[531:516005] client session: fireConnectCallback: 1449681493982.606.AnURMA==
2015-12-09 18:18:21.874 ThaliTest[531:516005] jxcore: connect: fail: Peer disconnected
,2015-12-09 18:18:22.875 ThaliTest[531:516179] jxcore: connect 1449681493982.606.AnURMA==
2015-12-09 18:18:22.876 ThaliTest[531:516179] client: connect: unreachable 1449681493982.606.AnURMA==
2015-12-09 18:18:22.876 ThaliTest[531:516179] jxcore: connect: fail: Peer unreachable
,2015-12-09 18:18:24.133 ThaliTest[531:517046] server session: connected
,2015-12-09 18:18:24.134 ThaliTest[531:517046] server session: stateChange:1->2 1449681499727.606
,2015-12-09 18:18:24.154 ThaliTest[531:516005] server relay: socket disconnected
,2015-12-09 18:18:24.155 ThaliTest[531:516005] server relay: 0x1d927af0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-09 18:18:24.182 ThaliTest[531:517046] server session: not connected 1449681499727.606
,2015-12-09 18:18:24.222 ThaliTest[531:517046] client session: connected
,2015-12-09 18:18:24.222 ThaliTest[531:517046] client session: stateChange:1->2 1449681499727.606.KecAYQ==
,2015-12-09 18:18:24.327 ThaliTest[531:517069] client session: fireConnectCallback: 1449681499727.606.KecAYQ==
2015-12-09 18:18:24.328 ThaliTest[531:517069] jxcore: connect: success
ok 84 Should be able to connect without error
ok 85 Port should be withi,n range
2015-12-09 18:18:24.330 ThaliTest[531:516179] jxcore: disconnect
,2015-12-09 18:18:24.330 ThaliTest[531:516179] client session: disconnectFromPeer: 1449681499727.606.KecAYQ==
2015-12-09 18:18:24.331 ThaliTest[531:516179] client session: disconnect
2015-12-09 18:18:24.331 ThaliTest[531:516179] client session: stateChange:2->0 1449681499727.606.KecAYQ==
,2015-12-09 18:18:24.343 ThaliTest[531:516179] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
2015-12-09 18:18:24.346 ThaliTest[531:516179] jxcore: disconnect
,2015-12-09 18:18:24.346 ThaliTest[531:516179] jxcore: disconnect: fail
ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2015-12-09 18:18:24.925 ThaliTest[531:516179] jxcore: stopBroadcasting
2015-12-09 18:18:24.926 ThaliTest[531:516179] THEMultipeerSession stopping peer
2015-12-09 18:18:24.926 ThaliTest[531:516179] multipeer session: stop timer
2015-12-09 18:18:24.927 Th,aliTest[531:516179] server session: disconnect
2015-12-09 18:18:24.927 ThaliTest[531:516179] server session: stateChange:2->0 1449681499727.606
2015-12-09 18:18:24.928 ThaliTest[531:516179] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,2015-12-09 18:18:25.361 ThaliTest[531:516179] jxcore: startBroadcasting
,2015-12-09 18:18:25.364 ThaliTest[531:516179] server: starting 1449681505361.531.djsk5A==
2015-12-09 18:18:25.364 ThaliTest[531:516179] multipeer session: start timer: 0x1d91aac0
2015-12-09 18:18:25.365 ThaliTest[531:516179] THEMultipeerSession initialized peer 1449681505361.531
2015-12-09 18:18:25.365 ThaliTest[531:516179] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
,echo server started
,2015-12-09 18:18:26.102 ThaliTest[531:516005] client: found peer: 1449681499727.606.KecAYQ==
[{"peerIdentifier":"1449681499727.606.KecAYQ==","peerName":"(null)","peerAvailable":true}]
2015-12-09 18:18:26.104 ThaliTest[531:516179] jxcore: connect 14496814,99727.606.KecAYQ==
2015-12-09 18:18:26.104 ThaliTest[531:516179] client session: connect
2015-12-09 18:18:26.105 ThaliTest[531:516179] client session: stateChange:0->1 1449681499727.606.KecAYQ==
,2015-12-09 18:18:27.219 ThaliTest[531:516005] client: found peer: 1449681505361.606.vRLobg==
[{"peerIdentifier":"1449681505361.606.vRLobg==","peerName":"(null)","peerAvailable":true}]
2015-12-09 18:18:27.220 ThaliTest[531:516179] jxcore: connect 1449681505361.606.vRLobg==
,2015-12-09 18:18:27.220 ThaliTest[531:516179] client session: connect
,2015-12-09 18:18:27.221 ThaliTest[531:516179] client session: stateChange:0->1 1449681505361.606.vRLobg==
,2015-12-09 18:18:27.638 ThaliTest[531:516005] multipeer session: reset timer
2015-12-09 18:18:27.638 ThaliTest[531:516005] multipeer session: stop timer
2015-12-09 18:18:27.638 ThaliTest[531:516005] multipeer session: start timer: 0x1d91aac0
,2015-12-09 18:18:27.639 ThaliTest[531:516005] server session: connect
2015-12-09 18:18:27.640 ThaliTest[531:516005] server session: stateChange:0->1 1449681505361.606
,2015-12-09 18:18:27.648 ThaliTest[531:516005] server: accepting invitation 1449681505361.606
,2015-12-09 18:18:30.707 ThaliTest[531:517066] server session: connected
2015-12-09 18:18:30.708 ThaliTest[531:517066] server session: stateChange:1->2 1449681505361.606
,2015-12-09 18:18:30.724 ThaliTest[531:516005] server relay: connected (to port: 5001)
,2015-12-09 18:18:31.025 ThaliTest[531:517066] server session: not connected 1449681505361.606
,2015-12-09 18:18:31.160 ThaliTest[531:516005] multipeer session: reset timer
2015-12-09 18:18:31.160 ThaliTest[531:516005] multipeer session: stop timer
2015-12-09 18:18:31.161 ThaliTest[531:516005] multipeer session: start timer: 0x1d91aac0
2015-12-09 ,18:18:31.161 ThaliTest[531:516005] server: disconnecting to refresh session (1449681505361.606)
2015-12-09 18:18:31.161 ThaliTest[531:516005] server session: disconnect
2015-12-09 18:18:31.161 ThaliTest[531:516005] server session: stateChange:2->0 144968,1505361.606
2015-12-09 18:18:31.164 ThaliTest[531:516005] server session: connect
,2015-12-09 18:18:31.164 ThaliTest[531:516005] server session: stateChange:0->1 1449681505361.606
,2015-12-09 18:18:31.183 ThaliTest[531:516005] server: accepting invitation 1449681505361.606
,2015-12-09 18:18:31.297 ThaliTest[531:517046] client session: connected
2015-12-09 18:18:31.299 ThaliTest[531:517046] client session: stateChange:1->2 1449681505361.606.vRLobg==
2015-12-09 18:18:31.304 ThaliTest[531:517046] client session: fireConnectCallback: 1449681505361.606.vRLobg==
2015-12-09 18:18:31.304 ThaliTest[531:517046] jxcore: connect: success
,ok 89 Should be able to connect without error
,ok 90 Port should be within range
ok 91 First connect should succeed
,2015-12-09 18:18:31.342 ThaliTest[531:516005] client: relay established
2015-12-09 18:18:31.343 ThaliTest[531:516005] client: new accepted socket: 0x1d92ca10
,ok 92 the test messages should be equal
ok 93 First send should succeed
,2015-12-09 18:18:31.463 ThaliTest[531:516005] client: socket closed
2015-12-09 18:18:31.464 ThaliTest[531:516005] client relay: socket disconnected
2015-12-09 18:18:31.464 ThaliTest[531:516005] client relay: 0x1d92ca10 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-09 18:18:31.464 ThaliTest[531:516005] client session: socket closed: 1449681505361.606.vRLobg==
2015-12-09 18:18:31.464 ThaliTest[531:516005] client session: onLinkFailure: 1449681505361.606.vRLobg==
2015-12-09 18:18:31.464 ThaliTest[531:516005] client session: disconnect
2015-12-09 18:18:31.465 ThaliTest[531:516005] client session: stateChange:2->0 1449681505361.606.vRLobg==
2015-12-09 18:18:31.482 ThaliTest[531:516005] client session: fireConnectionErrorEvent: 1449681505361.606.vRLobg==
,2015-12-09 18:18:31.484 ThaliTest[531:516179] jxcore: connect 1449681505361.606.vRLobg==
2015-12-09 18:18:31.492 ThaliTest[531:516179] client session: connect
2015-12-09 18:18:31.492 ThaliTest[531:516179] client session: stateChange:0->1 1449681505361.606.vRLobg==
,2015-12-09 18:18:33.429 ThaliTest[531:517069] server session: connected
,2015-12-09 18:18:33.429 ThaliTest[531:517069] server session: stateChange:1->2 1449681505361.606
,2015-12-09 18:18:33.817 ThaliTest[531:516005] server relay: connected (to port: 5001)
,2015-12-09 18:18:34.633 ThaliTest[531:517068] client session: connected
2015-12-09 18:18:34.634 ThaliTest[531:517068] client session: stateChange:1->2 1449681505361.606.vRLobg==
,2015-12-09 18:18:34.663 ThaliTest[531:517069] client session: fireConnectCallback: 1449681505361.606.vRLobg==
2015-12-09 18:18:34.664 ThaliTest[531:517069] jxcore: connect: success
ok 94 Should be able to connect without error
ok 95 Port should be withi,n range
ok 96 Second connect should succeed
,2015-12-09 18:18:34.689 ThaliTest[531:516005] client: relay established
2015-12-09 18:18:34.690 ThaliTest[531:516005] client: new accepted socket: 0x1da29d30
,ok 97 the test messages should be equal
ok 98 Second send should succeed
,# setup
,2015-12-09 18:18:34.747 ThaliTest[531:516005] client: socket closed
2015-12-09 18:18:34.748 ThaliTest[531:516005] client relay: socket disconnected
2015-12-09 18:18:34.749 ThaliTest[531:516005] client relay: 0x1da29d30 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-09 18:18:34.749 ThaliTest[531:516005] client session: socket closed: 1449681505361.606.vRLobg==
2015-12-09 18:18:34.,749 ThaliTest[531:516005] client session: onLinkFailure: 1449681505361.606.vRLobg==
2015-12-09 18:18:34.749 ThaliTest[531:516005] client session: disconnect
2015-12-09 18:18:34.749 ThaliTest[531:516005] client session: stateChange:2->0 1449681505361.606.,vRLobg==
,2015-12-09 18:18:34.757 ThaliTest[531:516005] client session: fireConnectionErrorEvent: 1449681505361.606.vRLobg==
,2015-12-09 18:18:35.802 ThaliTest[531:517068] server session: not connected 1449681505361.606
,calling stopBroadcasting
,2015-12-09 18:18:35.947 ThaliTest[531:516179] jxcore: stopBroadcasting
2015-12-09 18:18:35.947 ThaliTest[531:516179] THEMultipeerSession stopping peer
2015-12-09 18:18:35.948 ThaliTest[531:516179] multipeer session: stop timer
2015-12-09 18:18:35.948 Th,aliTest[531:516179] client session: disconnect
2015-12-09 18:18:35.948 ThaliTest[531:516179] client session: stateChange:1->0 1449681499727.606.KecAYQ==
2015-12-09 18:18:35.949 ThaliTest[531:516179] server session: disconnect
2015-12-09 18:18:35.949 ThaliTest[531:516179] server session: stateChange:2->0 1449681505361.606
,2015-12-09 18:18:35.958 ThaliTest[531:516179] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/9C7C8890-0B0F-4027-AE8C-E2543CC3946E/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 99 starting event should occur in right order
,2015-12-09 18:18:37.092 ThaliTest[531:516179] jxcore: startBroadcasting
,2015-12-09 18:18:37.095 ThaliTest[531:516179] server: starting 5xZdCrYo5RTB-9aEIK5P-A.sIeohQ==
2015-12-09 18:18:37.095 ThaliTest[531:516179] multipeer session: start timer: 0x1d93ce90
2015-12-09 18:18:37.096 ThaliTest[531:516179] THEMultipeerSession init,ialized peer 5xZdCrYo5RTB-9aEIK5P-A
2015-12-09 18:18:37.096 ThaliTest[531:516179] jxcore: startBroadcasting: success
ok 100 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
,ok 101 stopping event should occur in right order
About to call stopBroadcasting
2015-12-09 18:18:37.102 ThaliTest[531:516179] jxcore: stopBroadcasting
,2015-12-09 18:18:37.102 ThaliTest[531:516179] THEMultipeerSession stopping peer
2015-12-09 18:18:37.102 ThaliTest[531:516179] multipeer session: stop timer
,2015-12-09 18:18:37.103 ThaliTest[531:516179] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
ok 102 stopped event should occur in right order
mux server bridge listener closed
,# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/9C7C8890-0B0F-4027-AE8C-E2543CC3946E/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,",failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2015-12-09 18:18:38.004 ThaliTest[531:516179] jxcore: startBroadcasting
,2015-12-09 18:18:38.006 ThaliTest[531:516179] server: starting 5xZdCrYo5RTB-9aEIK5P-A.UQFpQw==
2015-12-09 18:18:38.006 ThaliTest[531:516179] multipeer session: start timer: 0x1d92fbf0
2015-12-09 18:18:38.006 ThaliTest[531:516179] THEMultipeerSession init,ialized peer 5xZdCrYo5RTB-9aEIK5P-A
2015-12-09 18:18:38.007 ThaliTest[531:516179] jxcore: startBroadcasting: success
ok 103 getDeviceIdentity should not return an error
ok 104 deviceName should not be null
Now in TRM stop
State of this._isStarted: tru,e
About to call stopBroadcasting
2015-12-09 18:18:38.010 ThaliTest[531:516179] jxcore: stopBroadcasting
2015-12-09 18:18:38.010 ThaliTest[531:516179] THEMultipeerSession stopping peer
2015-12-09 18:18:38.010 ThaliTest[531:516179] multipeer session: sto,p timer
2015-12-09 18:18:38.010 ThaliTest[531:516179] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
,mux server bridge listener closed
Tests Complete

```
