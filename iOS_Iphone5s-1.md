#### Test 55902202f27eba5_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55902202f27eba5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/2C70E554-4A10-48A7-B592-6A92BB92CFE3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/2C70E554-4A10-48A7-B592-6A92BB92CFE3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55902202f27eba5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55902202f27eba5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5EB40B57-386C-4F9C-A99B-35D8FB7512E4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55106"
,(lldb)     command script import "/tmp/2C70E554-4A10-48A7-B592-6A92BB92CFE3/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-13 16:34:00.444 ThaliTest[1878:4237666] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9D4786C7-E520-4EA6-9046-53DC5154DF74/Library/Cookies/Cookies.binarycookies
,2016-01-13 16:34:00.714 ThaliTest[1878:4237666] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-13 16:34:00.715 ThaliTest[1878:4237666] Multi-tasking -> Device: YES, App: YES
,2016-01-13 16:34:00.722 ThaliTest[1878:4237666] Unlimited access to network resources
,2016-01-13 16:34:00.731 ThaliTest[1878:4237666] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-13 16:34:05.087 ThaliTest[1878:4237666] Resetting plugins due to page load.
,2016-01-13 16:34:06.467 ThaliTest[1878:4237666] Finished load of: file:///var/mobile/Containers/Bundle/Application/5EB40B57-386C-4F9C-A99B-35D8FB7512E4/ThaliTest.app/www/index.html
,2016-01-13 16:34:06.663 ThaliTest[1878:4237666] JXcore Cordova plugin initializing
2016-01-13 16:34:06.666 ThaliTest[1878:4237824] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,My device name is: Apple-Iphone5s-1
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
ok 11 should not throw
,ok 12 should be equal
ok 13 should be equal
,# setup
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
# setup
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
ok 28 should be equal
# setup
,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,# teardown
,ok 29 should be equal
ok 30 should be equal
ok 31 should be equal
,# setup
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
,ok 40 should be equal
,# setup
,# should call Mobile("Disconnect") without an error
,# teardown
,ok 41 should be equal
,ok 42 should be equal
# setup
,# should call Mobile("Disconnect") and handle an error
,# teardown
,ok 43 should be equal
ok 44 should be equal
,# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2016-01-13 16:40:36.570 ThaliTest[1878:4237824] jxcore: startBroadcasting
,2016-01-13 16:40:36.578 ThaliTest[1878:4237824] server: starting 1452699636570.1878.qYjIpQ==
2016-01-13 16:40:36.578 ThaliTest[1878:4237824] multipeer session: start timer: 0x17e90640
2016-01-13 16:40:36.579 ThaliTest[1878:4237824] THEMultipeerSession in,itialized peer 1452699636570.1878
2016-01-13 16:40:36.579 ThaliTest[1878:4237824] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2016-01-13 16:40:36.580 ThaliTest[1878:4237824] jxcore: stopBroadcasting
,2016-01-13 16:40:36.580 ThaliTest[1878:4237824] THEMultipeerSession stopping peer
2016-01-13 16:40:36.584 ThaliTest[1878:4237824] multipeer session: stop timer
2016-01-13 16:40:36.585 ThaliTest[1878:4237824] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-13 16:40:36.586 ThaliTest[1878:4237824] jxcore: startBroadcasting
,2016-01-13 16:40:36.591 ThaliTest[1878:4237824] server: starting 1452699636586.1878.ftERzg==
2016-01-13 16:40:36.591 ThaliTest[1878:4237824] multipeer session: start timer: 0x179dc030
,2016-01-13 16:40:36.594 ThaliTest[1878:4237824] THEMultipeerSession initialized peer 1452699636586.1878
,2016-01-13 16:40:36.601 ThaliTest[1878:4237824] jxcore: startBroadcasting: success
,ok 47 Should be able to call startBroadcasting without error
,2016-01-13 16:40:36.603 ThaliTest[1878:4237824] jxcore: stopBroadcasting
,2016-01-13 16:40:36.603 ThaliTest[1878:4237824] THEMultipeerSession stopping peer
,2016-01-13 16:40:36.604 ThaliTest[1878:4237824] multipeer session: stop timer
,2016-01-13 16:40:36.607 ThaliTest[1878:4237824] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
,2016-01-13 16:40:36.610 ThaliTest[1878:4237824] jxcore: startBroadcasting
,2016-01-13 16:40:36.613 ThaliTest[1878:4237824] server: starting 1452699636610.1878.+5cGvw==
,2016-01-13 16:40:36.615 ThaliTest[1878:4237824] multipeer session: start timer: 0x17d15a50
,2016-01-13 16:40:36.618 ThaliTest[1878:4237824] THEMultipeerSession initialized peer 1452699636610.1878
,2016-01-13 16:40:36.619 ThaliTest[1878:4237824] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2016-01-13 16:40:36.622 ThaliTest[1878:4237824] jxcore: stopBroadcasting
,2016-01-13 16:40:36.622 ThaliTest[1878:4237824] THEMultipeerSession stopping peer
,2016-01-13 16:40:36.623 ThaliTest[1878:4237824] multipeer session: stop timer
,2016-01-13 16:40:36.627 ThaliTest[1878:4237824] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2016-01-13 16:40:36.629 ThaliTest[1878:4237824] jxcore: startBroadcasting
,2016-01-13 16:40:36.632 ThaliTest[1878:4237824] server: starting 1452699636629.1878.VfSXcw==
,2016-01-13 16:40:36.636 ThaliTest[1878:4237824] multipeer session: start timer: 0x17cf01c0
2016-01-13 16:40:36.637 ThaliTest[1878:4237824] THEMultipeerSession initialized peer 1452699636629.1878
2016-01-13 16:40:36.637 ThaliTest[1878:4237824] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2016-01-13 16:40:36.639 ThaliTest[1878:4237824] jxcore: stopBroadcasting
,2016-01-13 16:40:36.640 ThaliTest[1878:4237824] THEMultipeerSession stopping peer
,2016-01-13 16:40:36.641 ThaliTest[1878:4237824] multipeer session: stop timer
,2016-01-13 16:40:36.644 ThaliTest[1878:4237824] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2016-01-13 16:40:36.646 ThaliTest[1878:4237824] jxcore: startBroadcasting
,2016-01-13 16:40:36.649 ThaliTest[1878:4237824] server: starting 1452699636646.1878.AY+fKg==
,2016-01-13 16:40:36.652 ThaliTest[1878:4237824] multipeer session: start timer: 0x17ac0df0
,2016-01-13 16:40:36.661 ThaliTest[1878:4237824] THEMultipeerSession initialized peer 1452699636646.1878
,2016-01-13 16:40:36.662 ThaliTest[1878:4237824] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2016-01-13 16:40:36.666 ThaliTest[1878:4237824] jxcore: stopBroadcasting
,2016-01-13 16:40:36.667 ThaliTest[1878:4237824] THEMultipeerSession stopping peer
,2016-01-13 16:40:36.668 ThaliTest[1878:4237824] multipeer session: stop timer
,2016-01-13 16:40:36.669 ThaliTest[1878:4237824] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-13 16:40:36.674 ThaliTest[1878:4237824] jxcore: startBroadcasting
,2016-01-13 16:40:36.677 ThaliTest[1878:4237824] server: starting 1452699636674.1878.gLHQ9A==
,2016-01-13 16:40:36.679 ThaliTest[1878:4237824] multipeer session: start timer: 0x17be9d10
,2016-01-13 16:40:36.683 ThaliTest[1878:4237824] THEMultipeerSession initialized peer 1452699636674.1878
,2016-01-13 16:40:36.684 ThaliTest[1878:4237824] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-13 16:40:36.687 ThaliTest[1878:4237824] jxcore: stopBroadcasting
,2016-01-13 16:40:36.687 ThaliTest[1878:4237824] THEMultipeerSession stopping peer
,2016-01-13 16:40:36.688 ThaliTest[1878:4237824] multipeer session: stop timer
,2016-01-13 16:40:36.694 ThaliTest[1878:4237824] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-13 16:40:36.696 ThaliTest[1878:4237824] jxcore: startBroadcasting
,2016-01-13 16:40:36.699 ThaliTest[1878:4237824] server: starting 1452699636696.1878.vKhWaQ==
,2016-01-13 16:40:36.701 ThaliTest[1878:4237824] multipeer session: start timer: 0x166979a0
,2016-01-13 16:40:36.705 ThaliTest[1878:4237824] THEMultipeerSession initialized peer 1452699636696.1878
,2016-01-13 16:40:36.707 ThaliTest[1878:4237824] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-13 16:40:36.709 ThaliTest[1878:4237824] jxcore: stopBroadcasting
,2016-01-13 16:40:36.709 ThaliTest[1878:4237824] THEMultipeerSession stopping peer
,2016-01-13 16:40:36.710 ThaliTest[1878:4237824] multipeer session: stop timer
,2016-01-13 16:40:36.711 ThaliTest[1878:4237824] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-13 16:40:36.716 ThaliTest[1878:4237824] jxcore: startBroadcasting
,2016-01-13 16:40:36.718 ThaliTest[1878:4237824] server: starting 1452699636716.1878.Cn2p3w==
,2016-01-13 16:40:36.720 ThaliTest[1878:4237824] multipeer session: start timer: 0x17a36500
,2016-01-13 16:40:36.724 ThaliTest[1878:4237824] THEMultipeerSession initialized peer 1452699636716.1878
,2016-01-13 16:40:36.725 ThaliTest[1878:4237824] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-13 16:40:36.727 ThaliTest[1878:4237824] jxcore: stopBroadcasting
,2016-01-13 16:40:36.727 ThaliTest[1878:4237824] THEMultipeerSession stopping peer
,2016-01-13 16:40:36.728 ThaliTest[1878:4237824] multipeer session: stop timer
,2016-01-13 16:40:36.731 ThaliTest[1878:4237824] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-13 16:40:36.733 ThaliTest[1878:4237824] jxcore: startBroadcasting
,2016-01-13 16:40:36.735 ThaliTest[1878:4237824] server: starting 1452699636733.1878.rMC6NQ==
,2016-01-13 16:40:36.737 ThaliTest[1878:4237824] multipeer session: start timer: 0x17a60f40
,2016-01-13 16:40:36.740 ThaliTest[1878:4237824] THEMultipeerSession initialized peer 1452699636733.1878
,2016-01-13 16:40:36.741 ThaliTest[1878:4237824] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-13 16:40:36.744 ThaliTest[1878:4237824] jxcore: stopBroadcasting
,2016-01-13 16:40:36.744 ThaliTest[1878:4237824] THEMultipeerSession stopping peer
,2016-01-13 16:40:36.745 ThaliTest[1878:4237824] multipeer session: stop timer
,2016-01-13 16:40:36.746 ThaliTest[1878:4237824] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-13 16:40:36.750 ThaliTest[1878:4237824] jxcore: startBroadcasting
,2016-01-13 16:40:36.752 ThaliTest[1878:4237824] server: starting 1452699636749.1878.Ee1t8Q==
,2016-01-13 16:40:36.753 ThaliTest[1878:4237824] multipeer session: start timer: 0x17c035b0
,2016-01-13 16:40:36.755 ThaliTest[1878:4237824] THEMultipeerSession initialized peer 1452699636749.1878
,2016-01-13 16:40:36.757 ThaliTest[1878:4237824] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-13 16:40:36.760 ThaliTest[1878:4237824] jxcore: stopBroadcasting
,2016-01-13 16:40:36.761 ThaliTest[1878:4237824] THEMultipeerSession stopping peer
,2016-01-13 16:40:36.762 ThaliTest[1878:4237824] multipeer session: stop timer
,2016-01-13 16:40:36.764 ThaliTest[1878:4237824] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-13 16:40:39.865 ThaliTest[1878:4237824] jxcore: startBroadcasting
,2016-01-13 16:40:39.868 ThaliTest[1878:4237824] server: starting 1452699639865.1878.NRFvzA==
2016-01-13 16:40:39.868 ThaliTest[1878:4237824] multipeer session: start timer: 0x179a8900
2016-01-13 16:40:39.868 ThaliTest[1878:4237824] THEMultipeerSession initialized peer 1452699639865.1878
2016-01-13 16:40:39.868 ThaliTest[1878:4237824] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-13 16:40:39.869 ThaliTest[1878:4237824] jxcore: startBroadcasting
,2016-01-13 16:40:39.870 ThaliTest[1878:4237824] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
,2016-01-13 16:40:39.870 ThaliTest[1878:4237824] jxcore: stopBroadcasting
2016-01-13 16:40:39.873 ThaliTest[1878:4237824] THEMultipeerSession stopping peer
2016-01-13 16:40:39.874 ThaliTest[1878:4237824] multipeer session: stop timer
,2016-01-13 16:40:39.874 ThaliTest[1878:4237824] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-13 16:40:44.538 ThaliTest[1878:4237824] jxcore: startBroadcasting
,2016-01-13 16:40:44.542 ThaliTest[1878:4237824] server: starting 1452699644538.1878.4ZnJxA==
2016-01-13 16:40:44.542 ThaliTest[1878:4237824] multipeer session: start timer: 0x17c62a80
2016-01-13 16:40:44.543 ThaliTest[1878:4237824] THEMultipeerSession initialized peer 1452699644538.1878
2016-01-13 16:40:44.543 ThaliTest[1878:4237824] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-13 16:40:44.544 ThaliTest[1878:4237824] jxcore: connect foobar
2016-01-13 16:40:44.544 ThaliTest[1878:4237824] client: unknown peer foobar
,2016-01-13 16:40:44.544 ThaliTest[1878:4237824] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
2016-01-13 16:40:44.549 ThaliTest[1878:4237824] jxcore: stopBroadcasting
2016-01-13 16:40:44.549 ThaliTest[1878:4237824] THEMultipeerSession stopping peer
2016-01-13 16:40:44.549 ThaliTest[1878:4237824] multipeer session: stop timer
2016-01-13 16:40:44.549 ThaliTest[1878:4237824] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-13 16:40:48.619 ThaliTest[1878:4237824] jxcore: startBroadcasting
,2016-01-13 16:40:48.622 ThaliTest[1878:4237824] server: starting 1452699648619.1878.92M4Nw==
2016-01-13 16:40:48.622 ThaliTest[1878:4237824] multipeer session: start timer: 0x17dbbcd0
2016-01-13 16:40:48.623 ThaliTest[1878:4237824] THEMultipeerSession initialized peer 1452699648619.1878
2016-01-13 16:40:48.623 ThaliTest[1878:4237824] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-13 16:40:48.624 ThaliTest[1878:4237824] jxcore: disconnect
2016-01,-13 16:40:48.624 ThaliTest[1878:4237824] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
,2016-01-13 16:40:48.625 ThaliTest[1878:4237824] jxcore: stopBroadcasting
2016-01-13 16:40:48.628 ThaliTest[1878:4237824] THEMultipeerSession stopping peer
2016-01-13 16:40:48.628 ThaliTest[1878:4237824] multipeer session: stop timer
2016-01-13 16:40:48.629 ThaliTest[1878:4237824] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-13 16:40:51.463 ThaliTest[1878:4237824] jxcore: startBroadcasting
,2016-01-13 16:40:51.466 ThaliTest[1878:4237824] server: starting 1452699651463.1878.xtBYyw==
2016-01-13 16:40:51.466 ThaliTest[1878:4237824] multipeer session: start timer: 0x17d31f80
2016-01-13 16:40:51.466 ThaliTest[1878:4237824] THEMultipeerSession initialized peer 1452699651463.1878
2016-01-13 16:40:51.466 ThaliTest[1878:4237824] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-13 16:40:53.558 ThaliTest[1878:4237666] multipeer session: reset timer
2016-01-13 16:40:53.558 ThaliTest[1878:4237666] multipeer session: stop timer
2016-01-13 16:40:53.558 ThaliTest[1878:4237666] multipeer session: start timer: 0x17d31f80
2016-01-13 16:40:53.558 ThaliTest[1878:4237666] server session: connect
2016-01-13 16:40:53.558 ThaliTest[1878:4237666] server session: stateChange:0->1 1452699652928.1952
2016-01-13 16:40:53.563 ThaliTest[1878:4237666] server: accepting invitation 1452699652928.1952
,2016-01-13 16:40:53.585 ThaliTest[1878:4237666] client: found peer: 1452699652928.1952.Evgw/g==
2016-01-13 16:40:53.597 ThaliTest[1878:4237824] jxcore: connect 1452699652928.1952.Evgw/g==
2016-01-13 16:40:53.597 ThaliTest[1878:4237824] client session: connect
2016-01-13 16:40:53.597 ThaliTest[1878:4237824] client session: stateChange:0->1 1452699652928.1952.Evgw/g==
,2016-01-13 16:40:57.424 ThaliTest[1878:4239734] server session: connected
2016-01-13 16:40:57.424 ThaliTest[1878:4239734] server session: stateChange:1->2 1452699652928.1952
,2016-01-13 16:40:57.428 ThaliTest[1878:4237666] server relay: socket disconnected
2016-01-13 16:40:57.429 ThaliTest[1878:4237666] server relay: 0x198346d0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-13 16:40:57.466 ThaliTest[1878:4239811] server session: not connected 1452699652928.1952
,2016-01-13 16:40:57.749 ThaliTest[1878:4239734] client session: connected
2016-01-13 16:40:57.749 ThaliTest[1878:4239734] client session: stateChange:1->2 1452699652928.1952.Evgw/g==
2016-01-13 16:40:57.751 ThaliTest[1878:4239734] client session: fireConnectCallback: 1452699652928.1952.Evgw/g==
2016-01-13 16:40:57.751 ThaliTest[1878:4239734] jxcore: connect: success
ok 75 Should be able to connect without error
ok 76 Port should be within range
,2016-01-13 16:40:57.753 ThaliTest[1878:4237824] jxcore: disconnect
2016-01-13 16:40:57.756 ThaliTest[1878:4237824] client session: disconnectFromPeer: 1452699652928.1952.Evgw/g==
2016-01-13 16:40:57.756 ThaliTest[1878:4237824] client session: disconnect,
2016-01-13 16:40:57.756 ThaliTest[1878:4237824] client session: stateChange:2->0 1452699652928.1952.Evgw/g==
,2016-01-13 16:40:57.827 ThaliTest[1878:4237824] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
2016-01-13 16:40:58.862 ThaliTest[1878:4237824] jxcore: stopBroadcasting
2016-01-13 16:40:58.863 ThaliTest[1878:4237824] THEMultipeerSession stopping peer
2016-01-13 16:40:58.863 ThaliTest[1878:4237824] multipeer session: stop timer
2016-01-13 16:40:58.863 ThaliTest[1878:4237824] server session: disconnect
2016-01-13 16:40:58.863 ThaliTest[1878:4237824] server session: stateChange:2->0 1452699652928.1952
,2016-01-13 16:40:58.863 ThaliTest[1878:4237824] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-13 16:41:01.014 ThaliTest[1878:4237824] jxcore: startBroadcasting
,2016-01-13 16:41:01.016 ThaliTest[1878:4237824] server: starting 1452699661014.1878.m1Wf4Q==
2016-01-13 16:41:01.016 ThaliTest[1878:4237824] multipeer session: start timer: 0x1981cb60
2016-01-13 16:41:01.016 ThaliTest[1878:4237824] THEMultipeerSession initialized peer 1452699661014.1878
2016-01-13 16:41:01.016 ThaliTest[1878:4237824] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-13 16:41:02.137 ThaliTest[1878:4237666] client: found peer: 1452699662261.1952.lqAjwg==
2016-01-13 16:41:02.138 ThaliTest[1878:4237824] jxcore: connect 1452699662261.1952.lqAjwg==
2016-01-13 16:41:02.138 ThaliTest[1878:4237824] client session: co,nnect
2016-01-13 16:41:02.138 ThaliTest[1878:4237824] client session: stateChange:0->1 1452699662261.1952.lqAjwg==
,2016-01-13 16:41:02.207 ThaliTest[1878:4237666] multipeer session: reset timer
2016-01-13 16:41:02.207 ThaliTest[1878:4237666] multipeer session: stop timer
2016-01-13 16:41:02.208 ThaliTest[1878:4237666] multipeer session: start timer: 0x1981cb60
2016-01-13 16:41:02.208 ThaliTest[1878:4237666] server session: connect
2016-01-13 16:41:02.208 ThaliTest[1878:4237666] server session: stateChange:0->1 1452699662261.1952
,2016-01-13 16:41:02.212 ThaliTest[1878:4237666] server: accepting invitation 1452699662261.1952
,2016-01-13 16:41:06.001 ThaliTest[1878:4239817] server session: connected
2016-01-13 16:41:06.001 ThaliTest[1878:4239817] server session: stateChange:1->2 1452699662261.1952
,2016-01-13 16:41:06.006 ThaliTest[1878:4239817] client session: connected
2016-01-13 16:41:06.006 ThaliTest[1878:4239817] client session: stateChange:1->2 1452699662261.1952.lqAjwg==
,2016-01-13 16:41:06.014 ThaliTest[1878:4237666] server relay: socket disconnected
,2016-01-13 16:41:06.018 ThaliTest[1878:4237666] server relay: 0x17c56450 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-13 16:41:06.066 ThaliTest[1878:4239735] client session: fireConnectCallback: 1452699662261.1952.lqAjwg==
,2016-01-13 16:41:06.067 ThaliTest[1878:4239735] jxcore: connect: success
,ok 79 Should be able to connect without error
,ok 80 Port should be within range
,2016-01-13 16:41:06.070 ThaliTest[1878:4237824] jxcore: connect 1452699662261.1952.lqAjwg==
,2016-01-13 16:41:06.071 ThaliTest[1878:4237824] client: already connect(ing/ed) to 1452699662261.1952.lqAjwg==
,2016-01-13 16:41:06.071 ThaliTest[1878:4237824] jxcore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect
,2016-01-13 16:41:06.072 ThaliTest[1878:4237824] jxcore: disconnect
,2016-01-13 16:41:06.073 ThaliTest[1878:4237824] client session: disconnectFromPeer: 1452699662261.1952.lqAjwg==
,2016-01-13 16:41:06.073 ThaliTest[1878:4237824] client session: disconnect
,2016-01-13 16:41:06.074 ThaliTest[1878:4237824] client session: stateChange:2->0 1452699662261.1952.lqAjwg==
,2016-01-13 16:41:06.079 ThaliTest[1878:4239734] server session: not connected 1452699662261.1952
,2016-01-13 16:41:06.084 ThaliTest[1878:4237824] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-13 16:41:06.210 ThaliTest[1878:4237824] jxcore: stopBroadcasting
2016-01-13 16:41:06.210 ThaliTest[1878:4237824] THEMultipeerSession stopping peer
2016-01-13 16:41:06.210 ThaliTest[1878:4237824] multipeer session: stop timer
,2016-01-13 16:41:06.211 ThaliTest[1878:4237824] server session: disconnect
,2016-01-13 16:41:06.211 ThaliTest[1878:4237824] server session: stateChange:2->0 1452699662261.1952
,2016-01-13 16:41:06.214 ThaliTest[1878:4237824] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-13 16:41:08.119 ThaliTest[1878:4237824] jxcore: startBroadcasting
,2016-01-13 16:41:08.121 ThaliTest[1878:4237824] server: starting 1452699668119.1878.SPfBqA==
2016-01-13 16:41:08.122 ThaliTest[1878:4237824] multipeer session: start timer: 0x17b62e10
2016-01-13 16:41:08.122 ThaliTest[1878:4237824] THEMultipeerSession in,itialized peer 1452699668119.1878
2016-01-13 16:41:08.122 ThaliTest[1878:4237824] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-13 16:41:09.105 ThaliTest[1878:4237666] client: found peer: 1452699669369.1952.brRIHQ==
2016-01-13 16:41:09.106 ThaliTest[1878:4237824] jxcore: connect 1452699669369.1952.brRIHQ==
2016-01-13 16:41:09.106 ThaliTest[1878:4237824] client session: co,nnect
2016-01-13 16:41:09.106 ThaliTest[1878:4237824] client session: stateChange:0->1 1452699669369.1952.brRIHQ==
,2016-01-13 16:41:09.926 ThaliTest[1878:4237666] multipeer session: reset timer
2016-01-13 16:41:09.926 ThaliTest[1878:4237666] multipeer session: stop timer
2016-01-13 16:41:09.926 ThaliTest[1878:4237666] multipeer session: start timer: 0x17b62e10
2016-01-13 16:41:09.926 ThaliTest[1878:4237666] server session: connect
2016-01-13 16:41:09.926 ThaliTest[1878:4237666] server session: stateChange:0->1 1452699669369.1952
,2016-01-13 16:41:09.931 ThaliTest[1878:4237666] server: accepting invitation 1452699669369.1952
,2016-01-13 16:41:13.212 ThaliTest[1878:4239811] client session: connected
2016-01-13 16:41:13.212 ThaliTest[1878:4239811] client session: stateChange:1->2 1452699669369.1952.brRIHQ==
,2016-01-13 16:41:13.663 ThaliTest[1878:4239856] server session: connected
2016-01-13 16:41:13.663 ThaliTest[1878:4239856] server session: stateChange:1->2 1452699669369.1952
,2016-01-13 16:41:13.673 ThaliTest[1878:4237666] server relay: socket disconnected
2016-01-13 16:41:13.673 ThaliTest[1878:4237666] server relay: 0x16523620 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-13 16:41:13.988 ThaliTest[1878:4239856] client session: fireConnectCallback: 1452699669369.1952.brRIHQ==
2016-01-13 16:41:13.988 ThaliTest[1878:4239856] jxcore: connect: success
,ok 84 Should be able to connect without error
,ok 85 Port should be within range
,2016-01-13 16:41:13.990 ThaliTest[1878:4237824] jxcore: disconnect
2016-01-13 16:41:13.990 ThaliTest[1878:4237824] client session: disconnectFromPeer: 1452699669369.1952.brRIHQ==
2016-01-13 16:41:13.991 ThaliTest[1878:4237824] client session: disconnect
2016-01-13 16:41:13.991 ThaliTest[1878:4237824] client session: stateChange:2->0 1452699669369.1952.brRIHQ==
,2016-01-13 16:41:13.995 ThaliTest[1878:4237824] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
2016-01-13 16:41:13.996 ThaliTest[1878:4237824] jxcore: disconnect
,2016-01-13 16:41:13.997 ThaliTest[1878:4237824] jxcore: disconnect: fail
ok 87 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-13 16:41:14.063 ThaliTest[1878:4237824] jxcore: stopBroadcasting
2016-01-13 16:41:14.063 ThaliTest[1878:4237824] THEMultipeerSession stopping peer
2016-01-13 16:41:14.063 ThaliTest[1878:4237824] multipeer session: stop timer
2016-01-13 16:41:14.,063 ThaliTest[1878:4237824] server session: disconnect
2016-01-13 16:41:14.063 ThaliTest[1878:4237824] server session: stateChange:2->0 1452699669369.1952
,2016-01-13 16:41:14.069 ThaliTest[1878:4237824] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can connect and send data
,# teardown
,2016-01-13 16:41:15.723 ThaliTest[1878:4237824] jxcore: startBroadcasting
,2016-01-13 16:41:15.726 ThaliTest[1878:4237824] server: starting 1452699675723.1878.N5o+8Q==
,2016-01-13 16:41:15.730 ThaliTest[1878:4237824] multipeer session: start timer: 0x198da310
,2016-01-13 16:41:15.733 ThaliTest[1878:4237666] client: found peer: 1452699669369.1952.brRIHQ==
2016-01-13 16:41:15.732 ThaliTest[1878:4237824] THEMultipeerSession initialized peer 1452699675723.1878
,2016-01-13 16:41:15.733 ThaliTest[1878:4237824] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error
,echo server started
,2016-01-13 16:41:15.739 ThaliTest[1878:4237824] jxcore: connect 1452699669369.1952.brRIHQ==
,2016-01-13 16:41:15.740 ThaliTest[1878:4237824] client session: connect
,2016-01-13 16:41:15.741 ThaliTest[1878:4237824] client session: stateChange:0->1 1452699669369.1952.brRIHQ==
,2016-01-13 16:41:17.402 ThaliTest[1878:4237666] client: lost peer: 1452699669369.1952.brRIHQ==
2016-01-13 16:41:17.402 ThaliTest[1878:4237666] client session: onPeerLost: 1452699669369.1952.brRIHQ==
2016-01-13 16:41:17.402 ThaliTest[1878:4237666] client session: onLinkFailure: 1452699669369.1952.brRIHQ==
2016-01-13 16:41:17.402 ThaliTest[1878:4237666] client session: disconnect
2016-01-13 16:41:17.402 ThaliTest[1878:4237666] client session: stateChange:1->0 1452699669369.1952.brRIHQ==
2016-01-13 16:41:,17.402 ThaliTest[1878:4237666] client session: fireConnectCallback: 1452699669369.1952.brRIHQ==
2016-01-13 16:41:17.403 ThaliTest[1878:4237666] jxcore: connect: fail: Peer disconnected
2016-01-13 16:41:17.403 ThaliTest[1878:4237666] client: found peer: 1,452699676868.1952.Alnprw==
2016-01-13 16:41:17.404 ThaliTest[1878:4237824] jxcore: connect 1452699676868.1952.Alnprw==
2016-01-13 16:41:17.404 ThaliTest[1878:4237824] client session: connect
2016-01-13 16:41:17.404 ThaliTest[1878:4237824] client session: stateChange:0->1 1452699676868.1952.Alnprw==
,2016-01-13 16:41:17.536 ThaliTest[1878:4237666] multipeer session: reset timer
2016-01-13 16:41:17.536 ThaliTest[1878:4237666] multipeer session: stop timer
2016-01-13 16:41:17.536 ThaliTest[1878:4237666] multipeer session: start timer: 0x198da310
2016-01-13 16:41:17.536 ThaliTest[1878:4237666] server session: connect
2016-01-13 16:41:17.536 ThaliTest[1878:4237666] server session: stateChange:0->1 1452699676868.1952
,2016-01-13 16:41:17.541 ThaliTest[1878:4237666] server: accepting invitation 1452699676868.1952
,2016-01-13 16:41:18.404 ThaliTest[1878:4237824] jxcore: connect 1452699669369.1952.brRIHQ==
2016-01-13 16:41:18.405 ThaliTest[1878:4237824] client: connect: unreachable 1452699669369.1952.brRIHQ==
2016-01-13 16:41:18.405 ThaliTest[1878:4237824] jxcore: connect: fail: Peer unreachable
,2016-01-13 16:41:21.344 ThaliTest[1878:4239811] client session: connected
2016-01-13 16:41:21.344 ThaliTest[1878:4239811] client session: stateChange:1->2 1452699676868.1952.Alnprw==
,2016-01-13 16:41:21.391 ThaliTest[1878:4239735] client session: fireConnectCallback: 1452699676868.1952.Alnprw==
2016-01-13 16:41:21.393 ThaliTest[1878:4239735] jxcore: connect: success
ok 89 Should be able to connect without error
ok 90 Port should be within range
,2016-01-13 16:41:21.397 ThaliTest[1878:4237666] client: relay established
2016-01-13 16:41:21.397 ThaliTest[1878:4237666] client: new accepted socket: 0x17b172b0
,2016-01-13 16:41:21.405 ThaliTest[1878:4239811] server session: connected
2016-01-13 16:41:21.405 ThaliTest[1878:4239811] server session: stateChange:1->2 1452699676868.1952
,2016-01-13 16:41:21.408 ThaliTest[1878:4237666] server relay: connected (to port: 5001)
,data in 2190
,data in 6570
,data in 31755
,data in 32850
,data in 35040
,data in 40515
,data in 63510
,data in 73365
,data in 77745
,data in 84315
,data in 97455
,data in 101835
,data in 102930
,data in 107239
,data in 131072
,ok 91 the test messages should be equal
,2016-01-13 16:41:22.133 ThaliTest[1878:4237824] jxcore: disconnect
,2016-01-13 16:41:22.134 ThaliTest[1878:4237824] client session: disconnectFromPeer: 1452699676868.1952.Alnprw==
,2016-01-13 16:41:22.134 ThaliTest[1878:4237824] client session: disconnect
,2016-01-13 16:41:22.134 ThaliTest[1878:4237824] client session: stateChange:2->0 1452699676868.1952.Alnprw==
,2016-01-13 16:41:22.175 ThaliTest[1878:4239811] server session: not connected 1452699676868.1952
,2016-01-13 16:41:22.208 ThaliTest[1878:4237824] jxcore: disconnect: success
,ok 92 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-13 16:41:22.456 ThaliTest[1878:4237824] jxcore: stopBroadcasting
2016-01-13 16:41:22.457 ThaliTest[1878:4237824] THEMultipeerSession stopping peer
2016-01-13 16:41:22.457 ThaliTest[1878:4237824] multipeer session: stop timer
2016-01-13 16:41:22.457 ThaliTest[1878:4237824] server session: disconnect
2016-01-13 16:41:22.457 ThaliTest[1878:4237824] server session: stateChange:2->0 1452699676868.1952
,2016-01-13 16:41:23.048 ThaliTest[1878:4237824] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter handles socket disconnect correctly
,# teardown
,2016-01-13 16:41:24.127 ThaliTest[1878:4237824] jxcore: startBroadcasting
,2016-01-13 16:41:24.130 ThaliTest[1878:4237824] server: starting 1452699684127.1878.EUikBA==
2016-01-13 16:41:24.130 ThaliTest[1878:4237824] multipeer session: start timer: 0x16629bd0
2016-01-13 16:41:24.130 ThaliTest[1878:4237824] THEMultipeerSession in,itialized peer 1452699684127.1878
2016-01-13 16:41:24.130 ThaliTest[1878:4237824] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error
echo server started
,2016-01-13 16:41:25.308 ThaliTest[1878:4237666] multipeer session: reset timer
2016-01-13 16:41:25.309 ThaliTest[1878:4237666] multipeer session: stop timer
2016-01-13 16:41:25.309 ThaliTest[1878:4237666] multipeer session: start timer: 0x16629bd0
2016-,01-13 16:41:25.309 ThaliTest[1878:4237666] server session: connect
2016-01-13 16:41:25.309 ThaliTest[1878:4237666] server session: stateChange:0->1 1452699685356.1952
,2016-01-13 16:41:25.313 ThaliTest[1878:4237666] server: accepting invitation 1452699685356.1952
,2016-01-13 16:41:25.391 ThaliTest[1878:4237666] client: found peer: 1452699685356.1952.wdtcsw==
[{"peerIdentifier":"1452699685356.1952.wdtcsw==","peerName":"(null)","peerAvailable":true}]
2016-01-13 16:41:25.393 ThaliTest[1878:4237824] jxcore: connect 1452699685356.1952.wdtcsw==
2016-01-13 16:41:25.393 ThaliTest[1878:4237824] client session: connect
,2016-01-13 16:41:25.393 ThaliTest[1878:4237824] client session: stateChange:0->1 1452699685356.1952.wdtcsw==
,2016-01-13 16:41:29.195 ThaliTest[1878:4239734] server session: connected
2016-01-13 16:41:29.195 ThaliTest[1878:4239734] server session: stateChange:1->2 1452699685356.1952
,2016-01-13 16:41:29.198 ThaliTest[1878:4237666] server relay: connected (to port: 5001)
,2016-01-13 16:41:29.287 ThaliTest[1878:4239860] server session: not connected 1452699685356.1952
,2016-01-13 16:41:29.309 ThaliTest[1878:4239735] client session: connected
2016-01-13 16:41:29.310 ThaliTest[1878:4239735] client session: stateChange:1->2 1452699685356.1952.wdtcsw==
,2016-01-13 16:41:29.313 ThaliTest[1878:4239735] client session: fireConnectCallback: 1452699685356.1952.wdtcsw==
2016-01-13 16:41:29.313 ThaliTest[1878:4239735] jxcore: connect: success
,ok 94 Should be able to connect without error
ok 95 Port should be within range
,ok 96 First connect should succeed
,2016-01-13 16:41:29.325 ThaliTest[1878:4237666] multipeer session: reset timer
2016-01-13 16:41:29.326 ThaliTest[1878:4237666] multipeer session: stop timer
2016-01-13 16:41:29.326 ThaliTest[1878:4237666] multipeer session: start timer: 0x16629bd0
2016-01-13 16:41:29.326 ThaliTest[1878:4237666] server: disconnecting to refresh session (1452699685356.1952)
2016-01-13 16:41:29.326 ThaliTest[1878:4237666] server session: disconnect
2016-01-13 16:41:29.326 ThaliTest[1878:4237666] server session: stateChang,e:2->0 1452699685356.1952
2016-01-13 16:41:29.329 ThaliTest[1878:4237666] server session: connect
2016-01-13 16:41:29.330 ThaliTest[1878:4237666] server session: stateChange:0->1 1452699685356.1952
,2016-01-13 16:41:29.338 ThaliTest[1878:4237666] server: accepting invitation 1452699685356.1952
2016-01-13 16:41:29.338 ThaliTest[1878:4237666] client: relay established
2016-01-13 16:41:29.338 ThaliTest[1878:4237666] client: new accepted socket: 0x17fec5d0
,ok 97 the test messages should be equal
,ok 98 First send should succeed
,2016-01-13 16:41:29.410 ThaliTest[1878:4237666] client: socket closed
2016-01-13 16:41:29.411 ThaliTest[1878:4237666] client relay: socket disconnected
,2016-01-13 16:41:29.411 ThaliTest[1878:4237666] client relay: 0x17fec5d0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-01-13 16:41:29.411 ThaliTest[1878:4237666] client session: socket closed: 1452699685356.1952.wdtcsw==
,2016-01-13 16:41:29.412 ThaliTest[1878:4237666] client session: onLinkFailure: 1452699685356.1952.wdtcsw==
2016-01-13 16:41:29.412 ThaliTest[1878:4237666] client session: disconnect
,2016-01-13 16:41:29.412 ThaliTest[1878:4237666] client session: stateChange:2->0 1452699685356.1952.wdtcsw==
,2016-01-13 16:41:29.419 ThaliTest[1878:4237666] client session: fireConnectionErrorEvent: 1452699685356.1952.wdtcsw==
,2016-01-13 16:41:29.421 ThaliTest[1878:4237824] jxcore: connect 1452699685356.1952.wdtcsw==
,2016-01-13 16:41:29.421 ThaliTest[1878:4237824] client session: connect
,2016-01-13 16:41:29.422 ThaliTest[1878:4237824] client session: stateChange:0->1 1452699685356.1952.wdtcsw==
,ThaliTest(1878,0x409ab000) malloc: *** error for object 0x17ad2a54: incorrect checksum for freed object - object was probably modified after being freed.
*** set a breakpoint in malloc_error_break to debug
,Process 1878 stopped
* thread #17: tid = 0x40b1f4, 0x346a3c84 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.MCNearbyServiceBrowser.syncQueue', stop reason = signal SIGABRT
    frame #0: 0x346a3c84 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x346a3c84 <+8>:  blo    0x346a3c9c                ; <+32>
    0x346a3c88 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x346a3c8c <+16>: ldr    r12, [pc, r12]
    0x346a3c90 <+20>: b      0x346a3c98                ; <+28>
,* thread #17: tid = 0x40b1f4, 0x346a3c84 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.MCNearbyServiceBrowser.syncQueue', stop reason = signal SIGABRT
  * frame #0: 0x346a3c84 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x34743b46 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x3463bf40 libsystem_c.dylib`abort + 108
    frame #3: 0x346d40f8 libsystem_malloc.dylib`<redacted> + 364
    frame #4: 0x346d4114 libsystem_malloc.dylib`<redacted> + 28
    frame #5: 0x346cbc0e libsystem_malloc.dylib`<redacted> + 202
    frame #6: 0x346ca996 libsystem_malloc.dylib`<redacted> + 218
    frame #7: 0x346ca888 libsystem_malloc.dylib`malloc_zone_malloc + 88
    frame #8: 0x22500a20 CoreFoundation`<redacted> + 860
    frame #9: 0x2244acb2 CoreFoundation`CFStringAppend + 466
    frame #10: 0x2247e1ce CoreFoundation`<redacted> + 1226
    frame #11: 0x24a72d0c MultipeerConnectivity`<redacted> + 120
    frame #12: 0x24a7315e MultipeerConnectivity`<redacted> + 638
    frame #13: 0x24a74aaa MultipeerConnectivity`<redacted> + 90
    frame #14: 0x345abe2e libdispatch.dylib`<redacted> + 10
    frame #15: 0x345b5fee libdispatch.dylib`<redacted> + 1762
    frame #16: 0x345aef86 libdispatch.dylib`<redacted> + 282
    frame #17: 0x345b737c libdispatch.dylib`<redacted> + 400
    frame #18: 0x345b71ea libdispatch.dylib`<redacted> + 94
    frame #19: 0x34740e0c libsystem_pthread.dylib`_pthread_wqthread + 1024
    frame #20: 0x347409fc libsystem_pthread.dylib`start_wqthread + 8

```
