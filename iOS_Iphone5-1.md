#### Test 558877588826def_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/558877588826def/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/1BAFBE9E-4884-408A-98C5-747B6BDC7F68/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/1BAFBE9E-4884-408A-98C5-747B6BDC7F68/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/558877588826def/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/558877588826def/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54670"
,(lldb)     command script import "/tmp/1BAFBE9E-4884-408A-98C5-747B6BDC7F68/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-13 13:34:35.589 ThaliTest[1331:4335194] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B6ABAAC7-6219-4F76-8AF8-A3D26185B34C/Library/Cookies/Cookies.binarycookies
,2016-01-13 13:34:35.709 ThaliTest[1331:4335194] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-13 13:34:35.711 ThaliTest[1331:4335194] Multi-tasking -> Device: YES, App: YES
,2016-01-13 13:34:35.715 ThaliTest[1331:4335194] Unlimited access to network resources
,2016-01-13 13:34:35.727 ThaliTest[1331:4335194] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-13 13:34:41.758 ThaliTest[1331:4335194] Resetting plugins due to page load.
,2016-01-13 13:34:43.809 ThaliTest[1331:4335194] Finished load of: file:///var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/index.html
,2016-01-13 13:34:44.007 ThaliTest[1331:4335194] JXcore Cordova plugin initializing
2016-01-13 13:34:44.011 ThaliTest[1331:4335328] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
JXcore engine is started
,My device name is: Apple-Iphone5-1
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
# setup
,# another
,# teardown
,ok 3 sane
# setup
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
,ok 13 should be equal
,# setup
,# failed to extract public key because of corrupt pkcs12 file
,# teardown
,ok 14 should be equal
# setup
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
# setup
,# #startBroadcasting should throw on NaN port
,# teardown
,ok 23 should throw
,# setup
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
,# setup
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
# setup
,# should call Mobile("Disconnect") without an error
,# teardown
,ok 41 should be equal
,ok 42 should be equal
# setup
,# should call Mobile("Disconnect") and handle an error
,# teardown
,ok 43 should be equal
ok 44 should be equal
# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2016-01-13 13:41:19.534 ThaliTest[1331:4335328] jxcore: startBroadcasting
,2016-01-13 13:41:19.545 ThaliTest[1331:4335328] server: starting 1452688879534.1331.FjLMzg==
2016-01-13 13:41:19.545 ThaliTest[1331:4335328] multipeer session: start timer: 0x1ab39350
2016-01-13 13:41:19.546 ThaliTest[1331:4335328] THEMultipeerSession in,itialized peer 1452688879534.1331
2016-01-13 13:41:19.546 ThaliTest[1331:4335328] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2016-01-13 13:41:19.547 ThaliTest[1331:4335328] jxcore: stopBroadcasting
,2016-01-13 13:41:19.547 ThaliTest[1331:4335328] THEMultipeerSession stopping peer
2016-01-13 13:41:19.552 ThaliTest[1331:4335328] multipeer session: stop timer
2016-01-13 13:41:19.552 ThaliTest[1331:4335328] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-13 13:41:19.553 ThaliTest[1331:4335328] jxcore: startBroadcasting
2016-01-13 13:41:19.556 ThaliTest[1331:4335328] server: starting 1452688879553.1331.AieGmg==
2016-01-13 13:41:19.557 ThaliTest[133,1:4335328] multipeer session: start timer: 0x1adbbc20
,2016-01-13 13:41:19.557 ThaliTest[1331:4335328] THEMultipeerSession initialized peer 1452688879553.1331
2016-01-13 13:41:19.564 ThaliTest[1331:4335328] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-,01-13 13:41:19.566 ThaliTest[1331:4335328] jxcore: stopBroadcasting
2016-01-13 13:41:19.566 ThaliTest[1331:4335328] THEMultipeerSession stopping peer
2016-01-13 13:41:19.566 ThaliTest[1331:4335328] multipeer session: stop timer
2016-01-13 13:41:19.566 T,haliTest[1331:4335328] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
,2016-01-13 13:41:19.567 ThaliTest[1331:4335328] jxcore: startBroadcasting
,2016-01-13 13:41:19.589 ThaliTest[1331:4335328] server: starting 1452688879567.1331.iy2Bjw==
,2016-01-13 13:41:19.596 ThaliTest[1331:4335328] multipeer session: start timer: 0x14e9d0e0
,2016-01-13 13:41:19.598 ThaliTest[1331:4335328] THEMultipeerSession initialized peer 1452688879567.1331
,2016-01-13 13:41:19.599 ThaliTest[1331:4335328] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2016-01-13 13:41:19.602 ThaliTest[1331:4335328] jxcore: stopBroadcasting
,2016-01-13 13:41:19.604 ThaliTest[1331:4335328] THEMultipeerSession stopping peer
,2016-01-13 13:41:19.605 ThaliTest[1331:4335328] multipeer session: stop timer
,2016-01-13 13:41:19.609 ThaliTest[1331:4335328] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2016-01-13 13:41:19.613 ThaliTest[1331:4335328] jxcore: startBroadcasting
,2016-01-13 13:41:19.617 ThaliTest[1331:4335328] server: starting 1452688879612.1331.F+UbFA==
,2016-01-13 13:41:19.622 ThaliTest[1331:4335328] multipeer session: start timer: 0x14d06480
,2016-01-13 13:41:19.624 ThaliTest[1331:4335328] THEMultipeerSession initialized peer 1452688879612.1331
,2016-01-13 13:41:19.626 ThaliTest[1331:4335328] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2016-01-13 13:41:19.629 ThaliTest[1331:4335328] jxcore: stopBroadcasting
,2016-01-13 13:41:19.631 ThaliTest[1331:4335328] THEMultipeerSession stopping peer
,2016-01-13 13:41:19.632 ThaliTest[1331:4335328] multipeer session: stop timer
,2016-01-13 13:41:19.642 ThaliTest[1331:4335328] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2016-01-13 13:41:19.648 ThaliTest[1331:4335328] jxcore: startBroadcasting
,2016-01-13 13:41:19.652 ThaliTest[1331:4335328] server: starting 1452688879647.1331.y52MFA==
,2016-01-13 13:41:19.660 ThaliTest[1331:4335328] multipeer session: start timer: 0x14e96d90
,2016-01-13 13:41:19.661 ThaliTest[1331:4335328] THEMultipeerSession initialized peer 1452688879647.1331
,2016-01-13 13:41:19.663 ThaliTest[1331:4335328] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2016-01-13 13:41:19.666 ThaliTest[1331:4335328] jxcore: stopBroadcasting
,2016-01-13 13:41:19.668 ThaliTest[1331:4335328] THEMultipeerSession stopping peer
,2016-01-13 13:41:19.669 ThaliTest[1331:4335328] multipeer session: stop timer
,2016-01-13 13:41:19.674 ThaliTest[1331:4335328] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-13 13:41:19.677 ThaliTest[1331:4335328] jxcore: startBroadcasting
,2016-01-13 13:41:19.682 ThaliTest[1331:4335328] server: starting 1452688879677.1331.Tr14Yw==
,2016-01-13 13:41:19.685 ThaliTest[1331:4335328] multipeer session: start timer: 0x1aa667f0
,2016-01-13 13:41:19.691 ThaliTest[1331:4335328] THEMultipeerSession initialized peer 1452688879677.1331
,2016-01-13 13:41:19.692 ThaliTest[1331:4335328] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-13 13:41:19.695 ThaliTest[1331:4335328] jxcore: stopBroadcasting
,2016-01-13 13:41:19.697 ThaliTest[1331:4335328] THEMultipeerSession stopping peer
,2016-01-13 13:41:19.698 ThaliTest[1331:4335328] multipeer session: stop timer
,2016-01-13 13:41:19.700 ThaliTest[1331:4335328] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-13 13:41:19.706 ThaliTest[1331:4335328] jxcore: startBroadcasting
,2016-01-13 13:41:19.708 ThaliTest[1331:4335328] server: starting 1452688879705.1331.CKbiAg==
,2016-01-13 13:41:19.709 ThaliTest[1331:4335328] multipeer session: start timer: 0x1abc8ee0
,2016-01-13 13:41:19.712 ThaliTest[1331:4335328] THEMultipeerSession initialized peer 1452688879705.1331
,2016-01-13 13:41:19.715 ThaliTest[1331:4335328] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-13 13:41:19.721 ThaliTest[1331:4335328] jxcore: stopBroadcasting
,2016-01-13 13:41:19.721 ThaliTest[1331:4335328] THEMultipeerSession stopping peer
,2016-01-13 13:41:19.723 ThaliTest[1331:4335328] multipeer session: stop timer
,2016-01-13 13:41:19.724 ThaliTest[1331:4335328] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-13 13:41:19.730 ThaliTest[1331:4335328] jxcore: startBroadcasting
,2016-01-13 13:41:19.733 ThaliTest[1331:4335328] server: starting 1452688879729.1331.u5GO2g==
,2016-01-13 13:41:19.734 ThaliTest[1331:4335328] multipeer session: start timer: 0x1ab971d0
,2016-01-13 13:41:19.735 ThaliTest[1331:4335328] THEMultipeerSession initialized peer 1452688879729.1331
,2016-01-13 13:41:19.739 ThaliTest[1331:4335328] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-13 13:41:19.746 ThaliTest[1331:4335328] jxcore: stopBroadcasting
,2016-01-13 13:41:19.747 ThaliTest[1331:4335328] THEMultipeerSession stopping peer
,2016-01-13 13:41:19.748 ThaliTest[1331:4335328] multipeer session: stop timer
,2016-01-13 13:41:19.748 ThaliTest[1331:4335328] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-13 13:41:19.755 ThaliTest[1331:4335328] jxcore: startBroadcasting
,2016-01-13 13:41:19.759 ThaliTest[1331:4335328] server: starting 1452688879755.1331.dTGE9A==
,2016-01-13 13:41:19.760 ThaliTest[1331:4335328] multipeer session: start timer: 0x14d22310
,2016-01-13 13:41:19.769 ThaliTest[1331:4335328] THEMultipeerSession initialized peer 1452688879755.1331
,2016-01-13 13:41:19.770 ThaliTest[1331:4335328] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-13 13:41:19.772 ThaliTest[1331:4335328] jxcore: stopBroadcasting
,2016-01-13 13:41:19.773 ThaliTest[1331:4335328] THEMultipeerSession stopping peer
,2016-01-13 13:41:19.774 ThaliTest[1331:4335328] multipeer session: stop timer
,2016-01-13 13:41:19.775 ThaliTest[1331:4335328] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-13 13:41:19.781 ThaliTest[1331:4335328] jxcore: startBroadcasting
,2016-01-13 13:41:19.784 ThaliTest[1331:4335328] server: starting 1452688879780.1331.paFWyQ==
,2016-01-13 13:41:19.785 ThaliTest[1331:4335328] multipeer session: start timer: 0x1acf6c80
,2016-01-13 13:41:19.789 ThaliTest[1331:4335328] THEMultipeerSession initialized peer 1452688879780.1331
,2016-01-13 13:41:19.793 ThaliTest[1331:4335328] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-13 13:41:19.798 ThaliTest[1331:4335328] jxcore: stopBroadcasting
,2016-01-13 13:41:19.798 ThaliTest[1331:4335328] THEMultipeerSession stopping peer
,2016-01-13 13:41:19.799 ThaliTest[1331:4335328] multipeer session: stop timer
,2016-01-13 13:41:19.800 ThaliTest[1331:4335328] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-13 13:41:19.876 ThaliTest[1331:4335328] jxcore: startBroadcasting
,2016-01-13 13:41:19.878 ThaliTest[1331:4335328] server: starting 1452688879875.1331.Hm7HwA==
,2016-01-13 13:41:19.881 ThaliTest[1331:4335328] multipeer session: start timer: 0x14e425e0
,2016-01-13 13:41:19.883 ThaliTest[1331:4335328] THEMultipeerSession initialized peer 1452688879875.1331
,2016-01-13 13:41:19.888 ThaliTest[1331:4335328] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
,2016-01-13 13:41:19.891 ThaliTest[1331:4335328] jxcore: startBroadcasting
,2016-01-13 13:41:19.892 ThaliTest[1331:4335328] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
,2016-01-13 13:41:19.894 ThaliTest[1331:4335328] jxcore: stopBroadcasting
,2016-01-13 13:41:19.895 ThaliTest[1331:4335328] THEMultipeerSession stopping peer
,2016-01-13 13:41:19.896 ThaliTest[1331:4335328] multipeer session: stop timer
,2016-01-13 13:41:19.900 ThaliTest[1331:4335328] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-13 13:41:19.954 ThaliTest[1331:4335328] jxcore: startBroadcasting
,2016-01-13 13:41:19.957 ThaliTest[1331:4335328] server: starting 1452688879954.1331.trdOvg==
2016-01-13 13:41:19.957 ThaliTest[1331:4335328] multipeer session: start timer: 0x14e23930
2016-01-13 13:41:19.958 ThaliTest[1331:4335328] THEMultipeerSession in,itialized peer 1452688879954.1331
2016-01-13 13:41:19.958 ThaliTest[1331:4335328] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-13 13:41:19.959 ThaliTest[1331:4335328] jxcore: connect foobar
2016-01-13 13:41:19.959 ThaliTest[1331:4335328] client: unknown peer foobar
,2016-01-13 13:41:19.960 ThaliTest[1331:4335328] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
2016-01-13 13:41:19.965 ThaliTest[1331:4335328] jxcore: stopBroadcasting
2016-01-13 13:41:19.965 ThaliTest[1331:4335328] THEMultip,eerSession stopping peer
2016-01-13 13:41:19.965 ThaliTest[1331:4335328] multipeer session: stop timer
2016-01-13 13:41:19.966 ThaliTest[1331:4335328] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-13 13:41:20.346 ThaliTest[1331:4335328] jxcore: startBroadcasting
,2016-01-13 13:41:20.349 ThaliTest[1331:4335328] server: starting 1452688880346.1331.oQnAFg==
2016-01-13 13:41:20.350 ThaliTest[1331:4335328] multipeer session: start timer: 0x14dda700
2016-01-13 13:41:20.350 ThaliTest[1331:4335328] THEMultipeerSession in,itialized peer 1452688880346.1331
2016-01-13 13:41:20.350 ThaliTest[1331:4335328] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error
2016-01-13 13:41:20.356 ThaliTest[1331:4335328] jxcore: disconnect
2016-01-13 13:41:20.356 ThaliTest[1331:4335328] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer ,
2016-01-13 13:41:20.357 ThaliTest[1331:4335328] jxcore: stopBroadcasting
2016-01-13 13:41:20.358 ThaliTest[1331:4335328] THEMultipeerSession stopping peer
2016-01-13 13:41:20.358 ThaliTest[1331:4335328] multipeer session: stop timer
2016-01-13 13:41:2,0.358 ThaliTest[1331:4335328] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-13 13:41:20.414 ThaliTest[1331:4335328] jxcore: startBroadcasting
,2016-01-13 13:41:20.418 ThaliTest[1331:4335328] server: starting 1452688880414.1331.qzx3AA==
2016-01-13 13:41:20.418 ThaliTest[1331:4335328] multipeer session: start timer: 0x14ed9880
2016-01-13 13:41:20.418 ThaliTest[1331:4335328] THEMultipeerSession initialized peer 1452688880414.1331
2016-01-13 13:41:20.419 ThaliTest[1331:4335328] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-13 13:41:21.623 ThaliTest[1331:4335194] client: found peer: 1452688880454.1861.e0r2aw==
2016-01-13 13:41:21.624 ThaliTest[1331:4335328] jxcore: connect 1452688880454.1861.e0r2aw==
2016-01-13 13:41:21.624 ThaliTest[1331:4335328] client session: connect
2016-01-13 13:41:21.625 ThaliTest[1331:4335328] client session: stateChange:0->1 1452688880454.1861.e0r2aw==
,2016-01-13 13:41:21.882 ThaliTest[1331:4335194] multipeer session: reset timer
2016-01-13 13:41:21.882 ThaliTest[1331:4335194] multipeer session: stop timer
,2016-01-13 13:41:21.882 ThaliTest[1331:4335194] multipeer session: start timer: 0x14ed9880
,2016-01-13 13:41:21.883 ThaliTest[1331:4335194] server session: connect
2016-01-13 13:41:21.883 ThaliTest[1331:4335194] server session: stateChange:0->1 1452688880454.1861
,2016-01-13 13:41:21.888 ThaliTest[1331:4335194] server: accepting invitation 1452688880454.1861
,2016-01-13 13:41:24.382 ThaliTest[1331:4335973] client session: connected
2016-01-13 13:41:24.382 ThaliTest[1331:4335973] client session: stateChange:1->2 1452688880454.1861.e0r2aw==
,2016-01-13 13:41:24.386 ThaliTest[1331:4335973] client session: fireConnectCallback: 1452688880454.1861.e0r2aw==
2016-01-13 13:41:24.387 ThaliTest[1331:4335973] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2016-01-13 13:41:24.390 ThaliTest[1331:4335328] jxcore: disconnect
,2016-01-13 13:41:24.390 ThaliTest[1331:4335328] client session: disconnectFromPeer: 1452688880454.1861.e0r2aw==
,2016-01-13 13:41:24.391 ThaliTest[1331:4335328] client session: disconnect
,2016-01-13 13:41:24.391 ThaliTest[1331:4335328] client session: stateChange:2->0 1452688880454.1861.e0r2aw==
,2016-01-13 13:41:24.462 ThaliTest[1331:4335328] jxcore: disconnect: success
,ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-13 13:41:24.576 ThaliTest[1331:4335976] server session: connected
2016-01-13 13:41:24.576 ThaliTest[1331:4335976] server session: stateChange:1->2 1452688880454.1861
,2016-01-13 13:41:24.581 ThaliTest[1331:4335194] server relay: socket disconnected
,2016-01-13 13:41:24.582 ThaliTest[1331:4335194] server relay: 0x14e3d8c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-13 13:41:24.643 ThaliTest[1331:4335969] server session: not connected 1452688880454.1861
,calling stopBroadcasting
,2016-01-13 13:41:25.775 ThaliTest[1331:4335328] jxcore: stopBroadcasting
,2016-01-13 13:41:25.776 ThaliTest[1331:4335328] THEMultipeerSession stopping peer
2016-01-13 13:41:25.776 ThaliTest[1331:4335328] multipeer session: stop timer
2016-01-13 13:41:25.776 ThaliTest[1331:4335328] server session: disconnect
2016-01-13 13:41:25.777 ThaliTest[1331:4335328] server session: stateChange:2->0 1452688880454.1861
,2016-01-13 13:41:26.298 ThaliTest[1331:4335328] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-13 13:41:39.381 ThaliTest[1331:4335328] jxcore: startBroadcasting
,2016-01-13 13:41:39.390 ThaliTest[1331:4335328] server: starting 1452688899381.1331./bap5Q==
2016-01-13 13:41:39.391 ThaliTest[1331:4335328] multipeer session: start timer: 0x1ac08b80
2016-01-13 13:41:39.391 ThaliTest[1331:4335328] THEMultipeerSession initialized peer 1452688899381.1331
2016-01-13 13:41:39.391 ThaliTest[1331:4335328] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-13 13:41:45.864 ThaliTest[1331:4335194] multipeer session: reset timer
2016-01-13 13:41:45.865 ThaliTest[1331:4335194] multipeer session: stop timer
2016-01-13 13:41:45.865 ThaliTest[1331:4335194] multipeer session: start timer: 0x1ac08b80
2016-,01-13 13:41:45.866 ThaliTest[1331:4335194] server session: connect
2016-01-13 13:41:45.866 ThaliTest[1331:4335194] server session: stateChange:0->1 1452688905648.1861
2016-01-13 13:41:45.871 ThaliTest[1331:4335194] server: accepting invitation 1452688905648.1861
,2016-01-13 13:41:46.800 ThaliTest[1331:4335194] client: found peer: 1452688905648.1861.kf6ylw==
2016-01-13 13:41:46.801 ThaliTest[1331:4335328] jxcore: connect 1452688905648.1861.kf6ylw==
2016-01-13 13:41:46.801 ThaliTest[1331:4335328] client session: co,nnect
2016-01-13 13:41:46.802 ThaliTest[1331:4335328] client session: stateChange:0->1 1452688905648.1861.kf6ylw==
,2016-01-13 13:41:48.236 ThaliTest[1331:4336053] server session: connected
2016-01-13 13:41:48.237 ThaliTest[1331:4336053] server session: stateChange:1->2 1452688905648.1861
,2016-01-13 13:41:48.437 ThaliTest[1331:4335194] server relay: socket disconnected
2016-01-13 13:41:48.437 ThaliTest[1331:4335194] server relay: 0x1ae1d250 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-13 13:41:49.079 ThaliTest[1331:4336052] server session: not connected 1452688905648.1861
,2016-01-13 13:41:49.542 ThaliTest[1331:4336052] client session: connected
2016-01-13 13:41:49.542 ThaliTest[1331:4336052] client session: stateChange:1->2 1452688905648.1861.kf6ylw==
,2016-01-13 13:41:49.553 ThaliTest[1331:4336071] client session: fireConnectCallback: 1452688905648.1861.kf6ylw==
2016-01-13 13:41:49.553 ThaliTest[1331:4336071] jxcore: connect: success
ok 79 Should be able to connect without error
,ok 80 Port should be within range
,2016-01-13 13:41:49.556 ThaliTest[1331:4335328] jxcore: connect 1452688905648.1861.kf6ylw==
2016-01-13 13:41:49.556 ThaliTest[1331:4335328] client: already connect(ing/ed) to 1452688905648.1861.kf6ylw==
2016-01-13 13:41:49.556 ThaliTest[1331:4335328] jxc,ore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect
,2016-01-13 13:41:49.558 ThaliTest[1331:4335328] jxcore: disconnect
2016-01-13 13:41:49.558 ThaliTest[1331:4335328] client session: disconnectFromPeer: 1452688905648.1861.kf6ylw==
2016-01-13 13:41:49.559 ThaliTest[1331:4335328] client session: disconnect,
2016-01-13 13:41:49.559 ThaliTest[1331:4335328] client session: stateChange:2->0 1452688905648.1861.kf6ylw==
,2016-01-13 13:41:49.566 ThaliTest[1331:4335328] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
2016-01-13 13:41:49.864 ThaliTest[1331:4335328] jxcore: stopBroadcasting
2016-01-13 13:41:49.864 ThaliTest[1331:4335328] THEMultipeerSession stopping peer
,2016-01-13 13:41:49.864 ThaliTest[1331:4335328] multipeer session: stop timer
2016-01-13 13:41:49.865 ThaliTest[1331:4335328] server session: disconnect
2016-01-13 13:41:49.865 ThaliTest[1331:4335328] server session: stateChange:2->0 1452688905648.1861
2016-01-13 13:41:49.866 ThaliTest[1331:4335328] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-13 13:43:16.089 ThaliTest[1331:4335328] jxcore: startBroadcasting
,2016-01-13 13:43:16.092 ThaliTest[1331:4335328] server: starting 1452688996089.1331.OFrDkg==
2016-01-13 13:43:16.092 ThaliTest[1331:4335328] multipeer session: start timer: 0x1ab69820
2016-01-13 13:43:16.092 ThaliTest[1331:4335328] THEMultipeerSession initialized peer 1452688996089.1331
2016-01-13 13:43:16.093 ThaliTest[1331:4335328] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-13 13:43:32.473 ThaliTest[1331:4335194] client: found peer: 1452688995902.1861.X0lQsw==
2016-01-13 13:43:32.474 ThaliTest[1331:4335328] jxcore: connect 1452688995902.1861.X0lQsw==
2016-01-13 13:43:32.474 ThaliTest[1331:4335328] client session: connect
2016-01-13 13:43:32.475 ThaliTest[1331:4335328] client session: stateChange:0->1 1452688995902.1861.X0lQsw==
,2016-01-13 13:43:33.903 ThaliTest[1331:4335194] multipeer session: reset timer
2016-01-13 13:43:33.904 ThaliTest[1331:4335194] multipeer session: stop timer
2016-01-13 13:43:33.904 ThaliTest[1331:4335194] multipeer session: start timer: 0x1ab69820
2016-,01-13 13:43:33.904 ThaliTest[1331:4335194] server session: connect
2016-01-13 13:43:33.904 ThaliTest[1331:4335194] server session: stateChange:0->1 1452688995902.1861
2016-01-13 13:43:33.910 ThaliTest[1331:4335194] server: accepting invitation 1452688995902.1861
,2016-01-13 13:43:36.734 ThaliTest[1331:4336310] client session: connected
2016-01-13 13:43:36.734 ThaliTest[1331:4336310] client session: stateChange:1->2 1452688995902.1861.X0lQsw==
2016-01-13 13:43:36.738 ThaliTest[1331:4336298] client session: fireCon,nectCallback: 1452688995902.1861.X0lQsw==
2016-01-13 13:43:36.739 ThaliTest[1331:4336298] jxcore: connect: success
ok 84 Should be able to connect without error
ok 85 Port should be within range
,2016-01-13 13:43:36.741 ThaliTest[1331:4335328] jxcore: disconnect
2016-01-13 13:43:36.742 ThaliTest[1331:4335328] client session: disconnectFromPeer: 1452688995902.1861.X0lQsw==
2016-01-13 13:43:36.742 ThaliTest[1331:4335328] client session: disconnect
2016-01-13 13:43:36.742 ThaliTest[1331:4335328] client session: stateChange:2->0 1452688995902.1861.X0lQsw==
,2016-01-13 13:43:36.796 ThaliTest[1331:4336288] server session: connected
2016-01-13 13:43:36.796 ThaliTest[1331:4336288] server session: stateChange:1->2 1452688995902.1861
,2016-01-13 13:43:36.818 ThaliTest[1331:4335328] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error
,2016-01-13 13:43:36.819 ThaliTest[1331:4335328] jxcore: disconnect
,2016-01-13 13:43:36.820 ThaliTest[1331:4335328] jxcore: disconnect: fail
,ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-13 13:43:36.888 ThaliTest[1331:4336288] server session: not connected 1452688995902.1861
,calling stopBroadcasting
,2016-01-13 13:43:36.990 ThaliTest[1331:4335328] jxcore: stopBroadcasting
,2016-01-13 13:43:36.990 ThaliTest[1331:4335328] THEMultipeerSession stopping peer
,2016-01-13 13:43:36.990 ThaliTest[1331:4335328] multipeer session: stop timer
,2016-01-13 13:43:36.996 ThaliTest[1331:4335328] server session: disconnect
,2016-01-13 13:43:37.001 ThaliTest[1331:4335328] server session: stateChange:2->0 1452688995902.1861
,2016-01-13 13:43:38.454 ThaliTest[1331:4335328] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can connect and send data
,# teardown
,2016-01-13 13:43:55.985 ThaliTest[1331:4335328] jxcore: startBroadcasting
,2016-01-13 13:43:55.988 ThaliTest[1331:4335328] server: starting 1452689035985.1331.AR1oLw==
2016-01-13 13:43:55.989 ThaliTest[1331:4335328] multipeer session: start timer: 0x1acd3b50
2016-01-13 13:43:55.989 ThaliTest[1331:4335328] THEMultipeerSession initialized peer 1452689035985.1331
2016-01-13 13:43:55.989 ThaliTest[1331:4335328] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
echo server started
,2016-01-13 13:43:56.003 ThaliTest[1331:4335194] client: found peer: 1452689034828.1861.+q8KNQ==
2016-01-13 13:43:56.004 ThaliTest[1331:4335328] jxcore: connect 1452689034828.1861.+q8KNQ==
2016-01-13 13:43:56.004 ThaliTest[1331:4335328] client session: connect
2016-01-13 13:43:56.004 ThaliTest[1331:4335328] client session: stateChange:0->1 1452689034828.1861.+q8KNQ==
,2016-01-13 13:43:57.041 ThaliTest[1331:4335194] multipeer session: reset timer
2016-01-13 13:43:57.041 ThaliTest[1331:4335194] multipeer session: stop timer
2016-01-13 13:43:57.041 ThaliTest[1331:4335194] multipeer session: start timer: 0x1acd3b50
2016-01-13 13:43:57.041 ThaliTest[1331:4335194] server session: connect
2016-01-13 13:43:57.041 ThaliTest[1331:4335194] server session: stateChange:0->1 1452689034828.1861
,2016-01-13 13:43:57.049 ThaliTest[1331:4335194] server: accepting invitation 1452689034828.1861
,2016-01-13 13:43:59.211 ThaliTest[1331:4336350] client session: connected
2016-01-13 13:43:59.212 ThaliTest[1331:4336350] client session: stateChange:1->2 1452689034828.1861.+q8KNQ==
2016-01-13 13:43:59.214 ThaliTest[1331:4336350] client session: fireCon,nectCallback: 1452689034828.1861.+q8KNQ==
2016-01-13 13:43:59.214 ThaliTest[1331:4336350] jxcore: connect: success
ok 89 Should be able to connect without error
ok 90 Port should be within range
2016-01-13 13:43:59.219 ThaliTest[1331:4335194] client: relay established
2016-01-13 13:43:59.219 ThaliTest[1331:4335194] client: new accepted socket: 0x14d24c70
,data in 4380
,data in 9855
,data in 15330
,data in 38325
,data in 45706
,data in 59130
,data in 79864
,data in 93075
,data in 98550
,data in 107310
,data in 122640
,data in 131072
ok 91 the test messages should be equal
2016-01-13 13:43:59.723 ThaliTest[1331:4335328] jxcore: disconnect
2016-01-13 13:43:59.724 ThaliTest[1331:4335328] client session: disconnectFromPeer: 1452689034828.1861.+q8KNQ==
2016-01-13 13:43:59.724 ThaliTest[1331:4335328] client session: disconnect
2016-01-13 13:43:59.724 ThaliTest[1331:4335328] client session: stateChange:2->0 1452689034828.1861.+q8KNQ==
,2016-01-13 13:43:59.755 ThaliTest[1331:4335328] jxcore: disconnect: success
ok 92 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
# setup
,2016-01-13 13:43:59.797 ThaliTest[1331:4336350] server session: connected
2016-01-13 13:43:59.797 ThaliTest[1331:4336350] server session: stateChange:1->2 1452689034828.1861
,2016-01-13 13:43:59.852 ThaliTest[1331:4335194] server relay: connected (to port: 5001)
,2016-01-13 13:44:00.377 ThaliTest[1331:4336349] server session: not connected 1452689034828.1861
,calling stopBroadcasting
2016-01-13 13:44:01.980 ThaliTest[1331:4335328] jxcore: stopBroadcasting
2016-01-13 13:44:01.980 ThaliTest[1331:4335328] THEMultipeerSession stopping peer
2016-01-13 13:44:01.980 ThaliTest[1331:4335328] multipeer session: stop t,imer
2016-01-13 13:44:01.980 ThaliTest[1331:4335328] server session: disconnect
2016-01-13 13:44:01.981 ThaliTest[1331:4335328] server session: stateChange:2->0 1452689034828.1861
,2016-01-13 13:44:01.986 ThaliTest[1331:4335328] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter handles socket disconnect correctly
,# teardown
,2016-01-13 13:44:04.769 ThaliTest[1331:4335328] jxcore: startBroadcasting
,2016-01-13 13:44:04.772 ThaliTest[1331:4335328] server: starting 1452689044769.1331.4fQBHQ==
2016-01-13 13:44:04.773 ThaliTest[1331:4335328] multipeer session: start timer: 0x1a97c5e0
2016-01-13 13:44:04.773 ThaliTest[1331:4335328] THEMultipeerSession in,itialized peer 1452689044769.1331
2016-01-13 13:44:04.773 ThaliTest[1331:4335328] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error
2016-01-13 13:44:04.777 ThaliTest[1331:4335328] Error!: listen EADDRINUSE
,Stack:[{"_fileName":"net.js","_functionName":"errnoException","_lineNumber":"835","_columnNumber":"11","_msg":"    at errnoException@net.js:835:11"},{"_fileName":"net.js","_functionName":"Server.prototype._listen2","_lineNumber":"974","_columnNumber":"14",,"_msg":"    at Server.prototype._listen2@net.js:974:14"},{"_fileName":"net.js","_functionName":"listen","_lineNumber":"995","_columnNumber":"5","_msg":"    at listen@net.js:995:5"},{"_fileName":"net.js","_functionName":"Server.prototype.listen","_lineNumbe,r":"1068","_columnNumber":"5","_msg":"    at Server.prototype.listen@net.js:1068:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionN,ame":"","_lineNumber":"241","_columnNumber":"3","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:241:3"},{"_fileName":"/private/var/mobile/Conta,iners/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"declareTest/</<","_lineNumber":"78","_columnNumber":"7","_msg":"    at declareTest/</<@/private/var/mobile/Containers/Bundle/Applicat,ion/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/lib/thali-tape.js:78:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modu,les/component-emitter/index.js","_functionName":"on","_lineNumber":"63","_columnNumber":"5","_msg":"    at on@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node,_modules/component-emitter/index.js:63:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":,"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_module,s/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lin,eNumber":"263","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5"},{"_fileName":"/pr,ivate/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"221","_columnNumber":"7","_msg":"    at Soc,ket.prototype.onpacket@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/CF72E,20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Cont,ainers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38,BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bu,ndle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE2,0/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"333","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/CF72,E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket,.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app,/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/,socket.io-parser/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38,BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/,www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.js","_functionName":"Decoder.prototype.add","_lineNumber":"247","_columnNumber":"7","_msg":"    at Decoder.prototype.add@/private/var/mobile/Containers/Bundle/Application/CF72E20A,-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.js:247:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore,/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondata","_lineNumber":"323","_columnNumber":"3","_msg":"    at Manager.prototype.ondata@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE2,0,/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:323:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/componen,t-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.,io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/co,mponent-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore,/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.i,o-client/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onPacket","_lineNumber":"441","_columnNumber":"9","_msg":"    at Socket.prototype.onPacket@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A,38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:441:9"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/,socket.io-client/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.setTransport/<","_lineNumber":"258","_columnNumber":"5","_msg":"    at Socket.prototype.setTransport/<@/private/var/mobile/Containers/Bundle/Application/CF72E20,A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:258:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/,jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Container,s/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/C,F72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js","_functionName":"Transport.prototype.onPacket","_lineNumber":"143","_columnNumber":"3","_msg":"    at Transport.proto,type.onPacket@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js:143:3"},{"_fileName":"/private/var/mobile/Containers/,Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js","_functionName":"Transport.prototype.onData","_lineNumber":"135","_columnNumber":"3","_msg":"    ,at Transport.prototype.onData@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js:135:3"},{"_fileName":"/private/var/mo,bile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transports/websocket.js","_functionName":"WS.prototype.addEventListeners/this.ws.onmessage","_l,ineNumber":"127","_columnNumber":"5","_msg":"    at WS.prototype.addEventListeners/this.ws.onmessage@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/,engine.io-client/lib/transports/websocket.js:127:5"}]
,Uncaught Exception: Error: listen EADDRINUSE
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
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F,0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: '',
    _lineNumber: '241',
    _columnNumber: '3',
    _msg: '    at @/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A,38BB7FE20/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:241:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/lib/thali-tape.js',
    _functionName: 'declareT,est/</<',
    _lineNumber: '78',
    _columnNumber: '7',
    _msg: '    at declareTest/</<@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/lib/thali-tape.js:78:7' },
  { _fileName: '/priva,te/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'on',
    _lineNumber: '63',
    _columnNumber: '5',
  ,  _msg: '    at on@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:63:5' },
  { _fileName: '/private/var/mobile/Container,s/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '131',
    _columnNumber: '7',
    ,_msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7' },
  { _fileName: '/private/v,ar/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.onevent',
    _lineNumber: '263',
    _columnNumber: '5',
    _msg:, '    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/,A,pplication/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.onpacket',
    _lineNumber: '221',
    _columnNumber: '7',
    _msg: '    at Socket.prototype.on,packet@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4F,A7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21',
    _columnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mo,bile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4,FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '131',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit,@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Applicat,ion/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js',
    _functionName: 'Manager.prototype.ondecoded',
    _lineNumber: '333',
    _columnNumber: '3',
    _msg: '    at Manager.prototype.ondec,oded@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4F,A7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21',
    _columnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mo,bile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4,FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '134',
    _columnNumber: '7',
    _msg: ,'    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:7' },
  ,{ _fileName: '/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.js',
    _functionName: 'Decoder.prototype.add',
    _lineNumb,er: '247',
    _columnNumber: '7',
    _msg: '    at Decoder.prototype.add@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.j,s:247:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js',
    _functionName: 'Manager.prototype.ondata',
    _lineNumber: '3,23',
    _columnNumber: '3',
    _msg: '    at Manager.prototype.ondata@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:323:3' },
  { _fileName,: '/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21',
    _co,lumnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
  { _fileNam,e: '/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype,.emit',
    _lineNumber: '134',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/e,ngine.io-client/node_modules/component-emitter/index.js:134:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/l,ib/socket.js',
    _functionName: 'Socket.prototype.onPacket',
    _lineNumber: '441',
    _columnNumber: '9',
    _msg: '    at Socket.prototype.onPacket@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.,app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:441:9' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-clien,t/node_modules/engine.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.setTransport/<',
    _lineNumber: '258',
    _columnNumber: '5',
    _msg: '    at Socket.prototype.setTransport/<@/private/var/mobile/Containers/Bundle/Application/CF,72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:258:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTes,t.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '134',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit,@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7' },
  { _fileName: '/private/var/mob,ile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js',
    _functionName: 'Transport.prototype.onPacket',
    _lineNumber: '143',
   , _columnNumber: '3',
    _msg: '    at Transport.prototype.onPacket@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.j,s:143:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js',
    _functionName: 'Transport.proto,type.onData',
    _lineNumber: '135',
    _columnNumber: '3',
    _msg: '    at Transport.prototype.onData@/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node,_modules/engine.io-client/lib/transport.js:135:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transports,/websocket.js',
    _functionName: 'WS.prototype.addEventListeners/this.ws.onmessage',
    _lineNumber: '127',
    _columnNumber: '5',
    _msg: '    at WS.prototype.addEventListeners/this.ws.onmessage@/private/var/mobile/Containers/Bundle/Application/,CF72E20A-53F0-4FA7-90BC-F8A38BB7FE20/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transports/websocket.js:127:5' },
  toString: [Function] ]
****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
