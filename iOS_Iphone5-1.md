#### Test 58380500c26a9ef_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58380500c26a9ef/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/9DAB37C2-D45E-4D30-886B-FE21B4C08EAF/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/9DAB37C2-D45E-4D30-886B-FE21B4C08EAF/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58380500c26a9ef/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58380500c26a9ef/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FFAB23EE-20E0-4465-9EB0-99F7C0DDF5B6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52425"
,(lldb)     command script import "/tmp/9DAB37C2-D45E-4D30-886B-FE21B4C08EAF/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 03:04:16.173 ThaliTest[2780:8559818] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4B38A6C3-FBED-41B3-888D-397D7F9E4601/Library/Cookies/Cookies.binarycookies
,2016-02-09 03:04:16.741 ThaliTest[2780:8559818] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-09 03:04:16.742 ThaliTest[2780:8559818] Multi-tasking -> Device: YES, App: YES
,2016-02-09 03:04:16.749 ThaliTest[2780:8559818] Unlimited access to network resources
,2016-02-09 03:04:16.759 ThaliTest[2780:8559818] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 03:04:29.672 ThaliTest[2780:8559818] Resetting plugins due to page load.
,2016-02-09 03:04:33.592 ThaliTest[2780:8559818] Finished load of: file:///var/mobile/Containers/Bundle/Application/FFAB23EE-20E0-4465-9EB0-99F7C0DDF5B6/ThaliTest.app/www/index.html
,2016-02-09 03:04:33.803 ThaliTest[2780:8559818] JXcore Cordova plugin initializing
2016-02-09 03:04:33.804 ThaliTest[2780:8560360] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFAB23EE-20E0-4465-9EB0-99F7C0DDF5B6/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFAB23EE-20E0-4465-9EB0-99F7C0DDF5B6/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFAB23EE-20E0-4465-9EB0-99F7C0DDF5B6/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFAB23EE-20E0-4465-9EB0-99F7C0DDF5B6/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFAB23EE-20E0-4465-9EB0-99F7C0DDF5B6/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFAB23EE-20E0-4465-9EB0-99F7C0DDF5B6/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFAB23EE-20E0-4465-9EB0-99F7C0DDF5B6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFAB23EE-20E0-4465-9EB0-99F7C0DDF5B6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFAB23EE-20E0-4465-9EB0-99F7C0DDF5B6/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,# setup

,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 18 (unnamed assert)

,ok 19 (unnamed assert)

,ok 20 should not throw

,ok 21 should be equal

,ok 22 should be equal

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

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-02-09 03:15:33.587 ThaliTest[2780:8560360] jxcore: startBroadcasting
,2016-02-09 03:15:33.596 ThaliTest[2780:8560360] server: starting 1454984133587.2780.FbFhkw==
,2016-02-09 03:15:33.597 ThaliTest[2780:8560360] multipeer session: start timer: 0x1b6478d0
,2016-02-09 03:15:33.598 ThaliTest[2780:8560360] THEMultipeerSession initialized peer 1454984133587.2780
,2016-02-09 03:15:33.598 ThaliTest[2780:8560360] jxcore: startBroadcasting: success
,ok 54 Should be able to call startBroadcasting without error

2016-02-09 03:15:33.600 ThaliTest[2780:8560360] jxcore: stopBroadcasting
2016-02-09 03:15:33.601 ThaliTest[2780:8560360] THEMultipeerSession stopping peer
,2016-02-09 03:15:33.601 ThaliTest[2780:8560360] multipeer session: stop timer
,2016-02-09 03:15:33.602 ThaliTest[2780:8560360] jxcore: stopBroadcasting: success
ok 55 Should be able to call stopBroadcasting without error

2016-02-09 03:15:33.605 ThaliTest[2780:8560360] jxcore: startBroadcasting
,2016-02-09 03:15:33.613 ThaliTest[2780:8560360] server: starting 1454984133605.2780.QqKhEQ==
2016-02-09 03:15:33.614 ThaliTest[2780:8560360] multipeer session: start timer: 0x1b36d730
2016-02-09 03:15:33.614 ThaliTest[2780:8560360] THEMultipeerSession in,itialized peer 1454984133605.2780
2016-02-09 03:15:33.614 ThaliTest[2780:8560360] jxcore: startBroadcasting: success
ok 56 Should be able to call startBroadcasting without error

2016-02-09 03:15:33.616 ThaliTest[2780:8560360] jxcore: stopBroadcasting,
2016-02-09 03:15:33.616 ThaliTest[2780:8560360] THEMultipeerSession stopping peer
2016-02-09 03:15:33.617 ThaliTest[2780:8560360] multipeer session: stop timer
2016-02-09 03:15:33.617 ThaliTest[2780:8560360] jxcore: stopBroadcasting: success
ok 57 Should be able to call stopBroadcasting without error

,2016-02-09 03:15:33.619 ThaliTest[2780:8560360] jxcore: startBroadcasting
,2016-02-09 03:15:33.632 ThaliTest[2780:8560360] server: starting 1454984133618.2780.Nqr4Fw==
,2016-02-09 03:15:33.635 ThaliTest[2780:8560360] multipeer session: start timer: 0x1b36b7f0
,2016-02-09 03:15:33.638 ThaliTest[2780:8560360] THEMultipeerSession initialized peer 1454984133618.2780
,2016-02-09 03:15:33.639 ThaliTest[2780:8560360] jxcore: startBroadcasting: success
,ok 58 Should be able to call startBroadcasting without error

,2016-02-09 03:15:33.641 ThaliTest[2780:8560360] jxcore: stopBroadcasting
,2016-02-09 03:15:33.642 ThaliTest[2780:8560360] THEMultipeerSession stopping peer
,2016-02-09 03:15:33.643 ThaliTest[2780:8560360] multipeer session: stop timer
,2016-02-09 03:15:33.647 ThaliTest[2780:8560360] jxcore: stopBroadcasting: success
,ok 59 Should be able to call stopBroadcasting without error

,2016-02-09 03:15:33.649 ThaliTest[2780:8560360] jxcore: startBroadcasting
,2016-02-09 03:15:33.652 ThaliTest[2780:8560360] server: starting 1454984133648.2780.rpUDpw==
,2016-02-09 03:15:33.655 ThaliTest[2780:8560360] multipeer session: start timer: 0x1b644f10
,2016-02-09 03:15:33.659 ThaliTest[2780:8560360] THEMultipeerSession initialized peer 1454984133648.2780
,2016-02-09 03:15:33.660 ThaliTest[2780:8560360] jxcore: startBroadcasting: success
,ok 60 Should be able to call startBroadcasting without error

,2016-02-09 03:15:33.663 ThaliTest[2780:8560360] jxcore: stopBroadcasting
,2016-02-09 03:15:33.664 ThaliTest[2780:8560360] THEMultipeerSession stopping peer
,2016-02-09 03:15:33.668 ThaliTest[2780:8560360] multipeer session: stop timer
,2016-02-09 03:15:33.684 ThaliTest[2780:8560360] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error

,2016-02-09 03:15:33.687 ThaliTest[2780:8560360] jxcore: startBroadcasting
,2016-02-09 03:15:33.690 ThaliTest[2780:8560360] server: starting 1454984133686.2780.fnxUJQ==
,2016-02-09 03:15:33.693 ThaliTest[2780:8560360] multipeer session: start timer: 0x1c1cf010
,2016-02-09 03:15:33.701 ThaliTest[2780:8560360] THEMultipeerSession initialized peer 1454984133686.2780
,2016-02-09 03:15:33.702 ThaliTest[2780:8560360] jxcore: startBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error

,2016-02-09 03:15:33.705 ThaliTest[2780:8560360] jxcore: stopBroadcasting
,2016-02-09 03:15:33.706 ThaliTest[2780:8560360] THEMultipeerSession stopping peer
,2016-02-09 03:15:33.707 ThaliTest[2780:8560360] multipeer session: stop timer
,2016-02-09 03:15:33.708 ThaliTest[2780:8560360] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error

,2016-02-09 03:15:33.714 ThaliTest[2780:8560360] jxcore: startBroadcasting
,2016-02-09 03:15:33.717 ThaliTest[2780:8560360] server: starting 1454984133714.2780.LYtdkg==
,2016-02-09 03:15:33.719 ThaliTest[2780:8560360] multipeer session: start timer: 0x1b36e1f0
,2016-02-09 03:15:33.726 ThaliTest[2780:8560360] THEMultipeerSession initialized peer 1454984133714.2780
,2016-02-09 03:15:33.727 ThaliTest[2780:8560360] jxcore: startBroadcasting: success
,ok 64 Should be able to call startBroadcasting without error

,2016-02-09 03:15:33.729 ThaliTest[2780:8560360] jxcore: stopBroadcasting
,2016-02-09 03:15:33.730 ThaliTest[2780:8560360] THEMultipeerSession stopping peer
,2016-02-09 03:15:33.731 ThaliTest[2780:8560360] multipeer session: stop timer
,2016-02-09 03:15:33.732 ThaliTest[2780:8560360] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error

,2016-02-09 03:15:33.739 ThaliTest[2780:8560360] jxcore: startBroadcasting
,2016-02-09 03:15:33.742 ThaliTest[2780:8560360] server: starting 1454984133738.2780.luBoYA==
,2016-02-09 03:15:33.743 ThaliTest[2780:8560360] multipeer session: start timer: 0x1b30dbf0
,2016-02-09 03:15:33.752 ThaliTest[2780:8560360] THEMultipeerSession initialized peer 1454984133738.2780
,2016-02-09 03:15:33.753 ThaliTest[2780:8560360] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error

,2016-02-09 03:15:33.755 ThaliTest[2780:8560360] jxcore: stopBroadcasting
,2016-02-09 03:15:33.756 ThaliTest[2780:8560360] THEMultipeerSession stopping peer
,2016-02-09 03:15:33.757 ThaliTest[2780:8560360] multipeer session: stop timer
,2016-02-09 03:15:33.761 ThaliTest[2780:8560360] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,2016-02-09 03:15:33.763 ThaliTest[2780:8560360] jxcore: startBroadcasting
,2016-02-09 03:15:33.766 ThaliTest[2780:8560360] server: starting 1454984133763.2780.Eqi2fA==
,2016-02-09 03:15:33.769 ThaliTest[2780:8560360] multipeer session: start timer: 0x1b35e930
,2016-02-09 03:15:33.772 ThaliTest[2780:8560360] THEMultipeerSession initialized peer 1454984133763.2780
,2016-02-09 03:15:33.777 ThaliTest[2780:8560360] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-02-09 03:15:33.779 ThaliTest[2780:8560360] jxcore: stopBroadcasting
,2016-02-09 03:15:33.780 ThaliTest[2780:8560360] THEMultipeerSession stopping peer
,2016-02-09 03:15:33.780 ThaliTest[2780:8560360] multipeer session: stop timer
,2016-02-09 03:15:33.783 ThaliTest[2780:8560360] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-02-09 03:15:33.788 ThaliTest[2780:8560360] jxcore: startBroadcasting
,2016-02-09 03:15:33.791 ThaliTest[2780:8560360] server: starting 1454984133787.2780.0FU9iQ==
,2016-02-09 03:15:33.794 ThaliTest[2780:8560360] multipeer session: start timer: 0x1c1cfd00
,2016-02-09 03:15:33.797 ThaliTest[2780:8560360] THEMultipeerSession initialized peer 1454984133787.2780
,2016-02-09 03:15:33.802 ThaliTest[2780:8560360] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-02-09 03:15:33.805 ThaliTest[2780:8560360] jxcore: stopBroadcasting
,2016-02-09 03:15:33.805 ThaliTest[2780:8560360] THEMultipeerSession stopping peer
,2016-02-09 03:15:33.806 ThaliTest[2780:8560360] multipeer session: stop timer
,2016-02-09 03:15:33.809 ThaliTest[2780:8560360] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

,2016-02-09 03:15:33.812 ThaliTest[2780:8560360] jxcore: startBroadcasting
,2016-02-09 03:15:33.815 ThaliTest[2780:8560360] server: starting 1454984133811.2780.ivwk1A==
,2016-02-09 03:15:33.817 ThaliTest[2780:8560360] multipeer session: start timer: 0x1c1cdda0
,2016-02-09 03:15:33.820 ThaliTest[2780:8560360] THEMultipeerSession initialized peer 1454984133811.2780
,2016-02-09 03:15:33.823 ThaliTest[2780:8560360] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-02-09 03:15:33.827 ThaliTest[2780:8560360] jxcore: stopBroadcasting
,2016-02-09 03:15:33.828 ThaliTest[2780:8560360] THEMultipeerSession stopping peer
,2016-02-09 03:15:33.828 ThaliTest[2780:8560360] multipeer session: stop timer
,2016-02-09 03:15:33.833 ThaliTest[2780:8560360] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-09 03:15:36.690 ThaliTest[2780:8560360] jxcore: startBroadcasting
,2016-02-09 03:15:36.692 ThaliTest[2780:8560360] server: starting 1454984136689.2780.KcZkmw==
2016-02-09 03:15:36.692 ThaliTest[2780:8560360] multipeer session: start timer: 0x1c144670
2016-02-09 03:15:36.693 ThaliTest[2780:8560360] THEMultipeerSession in,itialized peer 1454984136689.2780
2016-02-09 03:15:36.693 ThaliTest[2780:8560360] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

2016-02-09 03:15:36.694 ThaliTest[2780:8560360] jxcore: startBroadcasting
2016-02-09 03:15:36.695 ThaliTest[2780:8560360] jxcore: startBroadcasting: failure
,ok 75 Cannot call startBroadcasting twice

2016-02-09 03:15:36.696 ThaliTest[2780:8560360] jxcore: stopBroadcasting
2016-02-09 03:15:36.696 ThaliTest[2780:8560360] THEMultipeerSession stopping peer
2016-02-09 03:15:36.697 ThaliTest[2780:8560360] multipeer session: stop timer
,2016-02-09 03:15:36.697 ThaliTest[2780:8560360] jxcore: stopBroadcasting: success
ok 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-09 03:15:37.131 ThaliTest[2780:8560360] jxcore: startBroadcasting
,2016-02-09 03:15:37.133 ThaliTest[2780:8560360] server: starting 1454984137130.2780.To9UtQ==
2016-02-09 03:15:37.134 ThaliTest[2780:8560360] multipeer session: start timer: 0x1c12ed10
,2016-02-09 03:15:37.134 ThaliTest[2780:8560360] THEMultipeerSession initialized peer 1454984137130.2780
2016-02-09 03:15:37.136 ThaliTest[2780:8560360] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

,2016-02-09 03:15:37.138 ThaliTest[2780:8560360] jxcore: connect foobar
2016-02-09 03:15:37.138 ThaliTest[2780:8560360] client: unknown peer foobar
2016-02-09 03:15:37.138 ThaliTest[2780:8560360] jxcore: connect: fail: Unknown peer
ok 78 Should not conne,ct to a bad peer

2016-02-09 03:15:37.140 ThaliTest[2780:8560360] jxcore: stopBroadcasting
2016-02-09 03:15:37.140 ThaliTest[2780:8560360] THEMultipeerSession stopping peer
2016-02-09 03:15:37.140 ThaliTest[2780:8560360] multipeer session: stop timer
,2016-02-09 03:15:37.141 ThaliTest[2780:8560360] jxcore: stopBroadcasting: success
ok 79 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-09 03:15:49.572 ThaliTest[2780:8560360] jxcore: startBroadcasting
,2016-02-09 03:15:49.575 ThaliTest[2780:8560360] server: starting 1454984149572.2780.HpSjzQ==
2016-02-09 03:15:49.575 ThaliTest[2780:8560360] multipeer session: start timer: 0x1c125980
2016-02-09 03:15:49.575 ThaliTest[2780:8560360] THEMultipeerSession in,itialized peer 1454984149572.2780
2016-02-09 03:15:49.576 ThaliTest[2780:8560360] jxcore: startBroadcasting: success
ok 80 Should be able to call startBroadcasting without error

2016-02-09 03:15:49.577 ThaliTest[2780:8560360] jxcore: disconnect
2016-,02-09 03:15:49.577 ThaliTest[2780:8560360] jxcore: disconnect: fail
ok 81 Disconnect should fail to a non-existant peer 

2016-02-09 03:15:49.579 ThaliTest[2780:8560360] jxcore: stopBroadcasting
2016-02-09 03:15:49.579 ThaliTest[2780:8560360] THEMultip,eerSession stopping peer
2016-02-09 03:15:49.579 ThaliTest[2780:8560360] multipeer session: stop timer
2016-02-09 03:15:49.580 ThaliTest[2780:8560360] jxcore: stopBroadcasting: success
ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-09 03:15:57.965 ThaliTest[2780:8560360] jxcore: startBroadcasting
,2016-02-09 03:15:57.967 ThaliTest[2780:8560360] server: starting 1454984157964.2780.GTHaNg==
2016-02-09 03:15:57.968 ThaliTest[2780:8560360] multipeer session: start timer: 0x1c126e90
2016-02-09 03:15:57.968 ThaliTest[2780:8560360] THEMultipeerSession initialized peer 1454984157964.2780
2016-02-09 03:15:57.968 ThaliTest[2780:8560360] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-02-09 03:15:59.526 ThaliTest[2780:8559818] client: found peer: 1454984158810.993.0Qovaw==
2016-02-09 03:15:59.527 ThaliTest[2780:8560360] jxcore: connect 1454984158810.993.0Qovaw==
2016-02-09 03:15:59.528 ThaliTest[2780:8560360] client session: connect
2016-02-09 03:15:59.528 ThaliTest[2780:8560360] client session: stateChange:0->1 1454984158810.993.0Qovaw==
,2016-02-09 03:16:00.248 ThaliTest[2780:8559818] multipeer session: reset timer
2016-02-09 03:16:00.249 ThaliTest[2780:8559818] multipeer session: stop timer
2016-02-09 03:16:00.249 ThaliTest[2780:8559818] multipeer session: start timer: 0x1c126e90
2016-02-09 03:16:00.250 ThaliTest[2780:8559818] server session: connect
2016-02-09 03:16:00.250 ThaliTest[2780:8559818] server session: stateChange:0->1 1454984158810.993
,2016-02-09 03:16:00.261 ThaliTest[2780:8559818] server: accepting invitation 1454984158810.993
,2016-02-09 03:16:02.751 ThaliTest[2780:8561599] client session: connected
2016-02-09 03:16:02.752 ThaliTest[2780:8561599] client session: stateChange:1->2 1454984158810.993.0Qovaw==
,2016-02-09 03:16:02.757 ThaliTest[2780:8561599] client session: fireConnectCallback: 1454984158810.993.0Qovaw==
2016-02-09 03:16:02.757 ThaliTest[2780:8561599] jxcore: connect: success
ok 84 Should be able to connect without error

ok 85 Port should be within range

,2016-02-09 03:16:02.761 ThaliTest[2780:8560360] jxcore: disconnect
2016-02-09 03:16:02.761 ThaliTest[2780:8560360] client session: disconnectFromPeer: 1454984158810.993.0Qovaw==
2016-02-09 03:16:02.761 ThaliTest[2780:8560360] client session: disconnect
,2016-02-09 03:16:02.762 ThaliTest[2780:8560360] client session: stateChange:2->0 1454984158810.993.0Qovaw==
,2016-02-09 03:16:02.773 ThaliTest[2780:8560360] jxcore: disconnect: success
ok 86 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 03:16:02.948 ThaliTest[2780:8561641] server session: connected
2016-02-09 03:16:02.948 ThaliTest[2780:8561641] server session: stateChange:1->2 1454984158810.993
,2016-02-09 03:16:02.972 ThaliTest[2780:8559818] server relay: socket disconnected
2016-02-09 03:16:02.972 ThaliTest[2780:8559818] server relay: 0x1c2ba4a0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 03:16:03.197 ThaliTest[2780:8561598] server session: not connected 1454984158810.993
,calling stopBroadcasting

,2016-02-09 03:16:05.098 ThaliTest[2780:8560360] jxcore: stopBroadcasting
2016-02-09 03:16:05.099 ThaliTest[2780:8560360] THEMultipeerSession stopping peer
2016-02-09 03:16:05.099 ThaliTest[2780:8560360] multipeer session: stop timer
2016-02-09 03:16:05.,100 ThaliTest[2780:8560360] server session: disconnect
2016-02-09 03:16:05.100 ThaliTest[2780:8560360] server session: stateChange:2->0 1454984158810.993
,2016-02-09 03:16:05.102 ThaliTest[2780:8560360] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-09 03:16:09.718 ThaliTest[2780:8560360] jxcore: startBroadcasting
,2016-02-09 03:16:09.721 ThaliTest[2780:8560360] server: starting 1454984169717.2780.fHQHxA==
2016-02-09 03:16:09.721 ThaliTest[2780:8560360] multipeer session: start timer: 0x1b1bf7c0
2016-02-09 03:16:09.722 ThaliTest[2780:8560360] THEMultipeerSession initialized peer 1454984169717.2780
2016-02-09 03:16:09.722 ThaliTest[2780:8560360] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-02-09 03:16:11.067 ThaliTest[2780:8559818] client: found peer: 1454984171169.993.I1lJBA==
2016-02-09 03:16:11.069 ThaliTest[2780:8560360] jxcore: connect 1454984171169.993.I1lJBA==
2016-02-09 03:16:11.069 ThaliTest[2780:8560360] client session: connect
,2016-02-09 03:16:11.070 ThaliTest[2780:8560360] client session: stateChange:0->1 1454984171169.993.I1lJBA==
,2016-02-09 03:16:11.205 ThaliTest[2780:8559818] multipeer session: reset timer
2016-02-09 03:16:11.205 ThaliTest[2780:8559818] multipeer session: stop timer
2016-02-09 03:16:11.205 ThaliTest[2780:8559818] multipeer session: start timer: 0x1b1bf7c0
,2016-02-09 03:16:11.206 ThaliTest[2780:8559818] server session: connect
2016-02-09 03:16:11.206 ThaliTest[2780:8559818] server session: stateChange:0->1 1454984171169.993
,2016-02-09 03:16:11.213 ThaliTest[2780:8559818] server: accepting invitation 1454984171169.993
,2016-02-09 03:16:13.951 ThaliTest[2780:8561682] server session: connected
2016-02-09 03:16:13.951 ThaliTest[2780:8561682] server session: stateChange:1->2 1454984171169.993
,2016-02-09 03:16:14.156 ThaliTest[2780:8559818] server relay: socket disconnected
2016-02-09 03:16:14.156 ThaliTest[2780:8559818] server relay: 0x1b149fb0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 03:16:14.206 ThaliTest[2780:8561599] server session: not connected 1454984171169.993
,2016-02-09 03:16:14.263 ThaliTest[2780:8561599] client session: connected
2016-02-09 03:16:14.263 ThaliTest[2780:8561599] client session: stateChange:1->2 1454984171169.993.I1lJBA==
,2016-02-09 03:16:14.277 ThaliTest[2780:8561598] client session: fireConnectCallback: 1454984171169.993.I1lJBA==
,2016-02-09 03:16:14.278 ThaliTest[2780:8561598] jxcore: connect: success
,ok 88 Should be able to connect without error

,ok 89 Port should be within range

,2016-02-09 03:16:14.281 ThaliTest[2780:8560360] jxcore: connect 1454984171169.993.I1lJBA==
,2016-02-09 03:16:14.281 ThaliTest[2780:8560360] client: already connect(ing/ed) to 1454984171169.993.I1lJBA==
,2016-02-09 03:16:14.281 ThaliTest[2780:8560360] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

,2016-02-09 03:16:14.283 ThaliTest[2780:8560360] jxcore: disconnect
,2016-02-09 03:16:14.284 ThaliTest[2780:8560360] client session: disconnectFromPeer: 1454984171169.993.I1lJBA==
,2016-02-09 03:16:14.284 ThaliTest[2780:8560360] client session: disconnect
,2016-02-09 03:16:14.284 ThaliTest[2780:8560360] client session: stateChange:2->0 1454984171169.993.I1lJBA==
,2016-02-09 03:16:14.296 ThaliTest[2780:8560360] jxcore: disconnect: success
,ok 91 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 03:16:14.677 ThaliTest[2780:8560360] jxcore: stopBroadcasting
2016-02-09 03:16:14.678 ThaliTest[2780:8560360] THEMultipeerSession stopping peer
2016-02-09 03:16:14.678 ThaliTest[2780:8560360] multipeer session: stop timer
2016-02-09 03:16:14.,678 ThaliTest[2780:8560360] server session: disconnect
2016-02-09 03:16:14.679 ThaliTest[2780:8560360] server session: stateChange:2->0 1454984171169.993
2016-02-09 03:16:14.679 ThaliTest[2780:8560360] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-09 03:16:19.661 ThaliTest[2780:8560360] jxcore: startBroadcasting
,2016-02-09 03:16:19.664 ThaliTest[2780:8560360] server: starting 1454984179661.2780.DfruYA==
2016-02-09 03:16:19.664 ThaliTest[2780:8560360] multipeer session: start timer: 0x1c37b420
2016-02-09 03:16:19.665 ThaliTest[2780:8560360] THEMultipeerSession initialized peer 1454984179661.2780
2016-02-09 03:16:19.665 ThaliTest[2780:8560360] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-09 03:16:19.980 ThaliTest[2780:8559818] client: found peer: 1454984180185.993.dEZ3qg==
2016-02-09 03:16:19.981 ThaliTest[2780:8560360] jxcore: connect 1454984180185.993.dEZ3qg==
2016-02-09 03:16:19.981 ThaliTest[2780:8560360] client session: conn,ect
2016-02-09 03:16:19.981 ThaliTest[2780:8560360] client session: stateChange:0->1 1454984180185.993.dEZ3qg==
,2016-02-09 03:16:21.219 ThaliTest[2780:8559818] multipeer session: reset timer
2016-02-09 03:16:21.219 ThaliTest[2780:8559818] multipeer session: stop timer
2016-02-09 03:16:21.219 ThaliTest[2780:8559818] multipeer session: start timer: 0x1c37b420
2016-,02-09 03:16:21.220 ThaliTest[2780:8559818] server session: connect
2016-02-09 03:16:21.220 ThaliTest[2780:8559818] server session: stateChange:0->1 1454984180185.993
,2016-02-09 03:16:21.226 ThaliTest[2780:8559818] server: accepting invitation 1454984180185.993
,2016-02-09 03:16:22.860 ThaliTest[2780:8561641] client session: connected
2016-02-09 03:16:22.860 ThaliTest[2780:8561641] client session: stateChange:1->2 1454984180185.993.dEZ3qg==
,2016-02-09 03:16:22.921 ThaliTest[2780:8561682] client session: fireConnectCallback: 1454984180185.993.dEZ3qg==
2016-02-09 03:16:22.921 ThaliTest[2780:8561682] jxcore: connect: success
ok 93 Should be able to connect without error

ok 94 Port should be, within range

2016-02-09 03:16:22.923 ThaliTest[2780:8560360] jxcore: disconnect
2016-02-09 03:16:22.923 ThaliTest[2780:8560360] client session: disconnectFromPeer: 1454984180185.993.dEZ3qg==
2016-02-09 03:16:22.923 ThaliTest[2780:8560360] client sess,ion: disconnect
2016-02-09 03:16:22.924 ThaliTest[2780:8560360] client session: stateChange:2->0 1454984180185.993.dEZ3qg==
,2016-02-09 03:16:22.932 ThaliTest[2780:8560360] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

2016-02-09 03:16:22.933 ThaliTest[2780:8560360] jxcore: disconnect
2016-02-09 03:16:22.934 ThaliTest[2780:8560360] jxcore: dis,connect: fail
ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 03:16:23.847 ThaliTest[2780:8561682] server session: connected
2016-02-09 03:16:23.847 ThaliTest[2780:8561682] server session: stateChange:1->2 1454984180185.993
,2016-02-09 03:16:23.911 ThaliTest[2780:8561641] server session: not connected 1454984180185.993
,2016-02-09 03:16:23.913 ThaliTest[2780:8559818] server relay: socket disconnected
2016-02-09 03:16:23.913 ThaliTest[2780:8559818] server relay: 0x156690f0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,calling stopBroadcasting

,2016-02-09 03:16:24.041 ThaliTest[2780:8560360] jxcore: stopBroadcasting
2016-02-09 03:16:24.042 ThaliTest[2780:8560360] THEMultipeerSession stopping peer
2016-02-09 03:16:24.042 ThaliTest[2780:8560360] multipeer session: stop timer
2016-02-09 03:16:24.,042 ThaliTest[2780:8560360] server session: disconnect
2016-02-09 03:16:24.042 ThaliTest[2780:8560360] server session: stateChange:2->0 1454984180185.993
2016-02-09 03:16:24.043 ThaliTest[2780:8560360] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 49675

,2016-02-09 03:16:27.348 ThaliTest[2780:8560360] jxcore: startBroadcasting
,2016-02-09 03:16:27.350 ThaliTest[2780:8560360] server: starting 1454984187348.2780.zlzeIw==
2016-02-09 03:16:27.351 ThaliTest[2780:8560360] multipeer session: start timer: 0x1c4788e0
2016-02-09 03:16:27.351 ThaliTest[2780:8560360] THEMultipeerSession initialized peer 1454984187348.2780
2016-02-09 03:16:27.351 ThaliTest[2780:8560360] jxcore: startBroadcasting: success
ok 97 Should be able to call startBroadcasting without error

,2016-02-09 03:16:28.581 ThaliTest[2780:8559818] client: found peer: 1454984187458.993.aoLPtw==
2016-02-09 03:16:28.583 ThaliTest[2780:8560360] jxcore: connect 1454984187458.993.aoLPtw==
2016-02-09 03:16:28.584 ThaliTest[2780:8560360] client session: connect
,2016-02-09 03:16:28.584 ThaliTest[2780:8560360] client session: stateChange:0->1 1454984187458.993.aoLPtw==
,2016-02-09 03:16:28.687 ThaliTest[2780:8559818] multipeer session: reset timer
2016-02-09 03:16:28.687 ThaliTest[2780:8559818] multipeer session: stop timer
2016-02-09 03:16:28.688 ThaliTest[2780:8559818] multipeer session: start timer: 0x1c4788e0
,2016-02-09 03:16:28.688 ThaliTest[2780:8559818] server session: connect
2016-02-09 03:16:28.690 ThaliTest[2780:8559818] server session: stateChange:0->1 1454984187458.993
,2016-02-09 03:16:28.695 ThaliTest[2780:8559818] server: accepting invitation 1454984187458.993
,2016-02-09 03:16:31.303 ThaliTest[2780:8561598] server session: connected
2016-02-09 03:16:31.303 ThaliTest[2780:8561598] server session: stateChange:1->2 1454984187458.993
,2016-02-09 03:16:31.310 ThaliTest[2780:8559818] server relay: connected (to port: 49675)
,2016-02-09 03:16:32.997 ThaliTest[2780:8561621] client session: connected
,2016-02-09 03:16:32.997 ThaliTest[2780:8561621] client session: stateChange:1->2 1454984187458.993.aoLPtw==
,2016-02-09 03:16:33.002 ThaliTest[2780:8561621] client session: fireConnectCallback: 1454984187458.993.aoLPtw==
2016-02-09 03:16:33.002 ThaliTest[2780:8561621] jxcore: connect: success
ok 98 Should be able to connect without error

ok 99 Port should be within range

,2016-02-09 03:16:33.007 ThaliTest[2780:8559818] client: relay established
2016-02-09 03:16:33.008 ThaliTest[2780:8559818] client: new accepted socket: 0x1b6b3b00
,data in 5475

,data in 39420

,data in 43516

,data in 75555

,data in 98083

,data in 109500

,data in 131072

ok 100 the test messages should be equal
,
,2016-02-09 03:16:34.588 ThaliTest[2780:8560360] jxcore: disconnect
,2016-02-09 03:16:34.591 ThaliTest[2780:8560360] client session: disconnectFromPeer: 1454984187458.993.aoLPtw==
,2016-02-09 03:16:34.599 ThaliTest[2780:8560360] client session: disconnect
,2016-02-09 03:16:34.601 ThaliTest[2780:8560360] client session: stateChange:2->0 1454984187458.993.aoLPtw==
,2016-02-09 03:16:34.621 ThaliTest[2780:8560360] jxcore: disconnect: success
,ok 101 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 03:16:54.626 ThaliTest[2780:8561621] server session: not connected 1454984187458.993
,calling stopBroadcasting

,2016-02-09 03:16:54.961 ThaliTest[2780:8560360] jxcore: stopBroadcasting
2016-02-09 03:16:54.961 ThaliTest[2780:8560360] THEMultipeerSession stopping peer
2016-02-09 03:16:54.962 ThaliTest[2780:8560360] multipeer session: stop timer
2016-02-09 03:16:54.962 ThaliTest[2780:8560360] server session: disconnect
2016-02-09 03:16:54.962 ThaliTest[2780:8560360] server session: stateChange:2->0 1454984187458.993
,2016-02-09 03:16:54.967 ThaliTest[2780:8560360] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 49681

,2016-02-09 03:16:58.180 ThaliTest[2780:8560360] jxcore: startBroadcasting
,2016-02-09 03:16:58.182 ThaliTest[2780:8560360] server: starting 1454984218180.2780.KE6AwQ==
2016-02-09 03:16:58.183 ThaliTest[2780:8560360] multipeer session: start timer: 0x1c140b50
2016-02-09 03:16:58.183 ThaliTest[2780:8560360] THEMultipeerSession in,itialized peer 1454984218180.2780
2016-02-09 03:16:58.183 ThaliTest[2780:8560360] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-02-09 03:16:58.879 ThaliTest[2780:8559818] client: found peer: 1454984217855.993.Tw9Hdw==
[{"peerIdentifier":"1454984217855.993.Tw9Hdw==","peerName":"(null)","peerAvailable":true}]

2016-02-09 03:16:58.881 ThaliTest[2780:8560360] jxcore: connect 14,54984217855.993.Tw9Hdw==
2016-02-09 03:16:58.881 ThaliTest[2780:8560360] client session: connect
2016-02-09 03:16:58.881 ThaliTest[2780:8560360] client session: stateChange:0->1 1454984217855.993.Tw9Hdw==
,2016-02-09 03:16:59.487 ThaliTest[2780:8559818] multipeer session: reset timer
2016-02-09 03:16:59.487 ThaliTest[2780:8559818] multipeer session: stop timer
2016-02-09 03:16:59.488 ThaliTest[2780:8559818] multipeer session: start timer: 0x1c140b50
2016-02-09 03:16:59.488 ThaliTest[2780:8559818] server session: connect
,2016-02-09 03:16:59.488 ThaliTest[2780:8559818] server session: stateChange:0->1 1454984217855.993
,2016-02-09 03:16:59.495 ThaliTest[2780:8559818] server: accepting invitation 1454984217855.993
,2016-02-09 03:17:00.944 ThaliTest[2780:8561815] client session: connected
2016-02-09 03:17:00.944 ThaliTest[2780:8561815] client session: stateChange:1->2 1454984217855.993.Tw9Hdw==
2016-02-09 03:17:00.946 ThaliTest[2780:8561815] client session: fireConn,ectCallback: 1454984217855.993.Tw9Hdw==
2016-02-09 03:17:00.946 ThaliTest[2780:8561815] jxcore: connect: success
ok 103 Should be able to connect without error

ok 104 Port should be within range

ok 105 First connect should succeed

,2016-02-09 03:17:00.986 ThaliTest[2780:8559818] client: relay established
2016-02-09 03:17:00.987 ThaliTest[2780:8559818] client: new accepted socket: 0x1561a070
,2016-02-09 03:17:01.012 ThaliTest[2780:8561813] server session: connected
2016-02-09 03:17:01.012 ThaliTest[2780:8561813] server session: stateChange:1->2 1454984217855.993
,2016-02-09 03:17:01.081 ThaliTest[2780:8559818] server relay: connected (to port: 49681)
,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-02-09 03:17:01.676 ThaliTest[2780:8559818] client: socket closed
2016-02-09 03:17:01.676 ThaliTest[2780:8559818] client relay: socket disconnected
2016-02-09 03:17:01.677 ThaliTest[2780:8559818] client relay: 0x1561a070 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 03:17:01.677 ThaliTest[2780:8559818] client session: socket closed: 1454984217855.993.Tw9Hdw==
2016-02-09 0,3:17:01.678 ThaliTest[2780:8559818] client session: onLinkFailure: 1454984217855.993.Tw9Hdw==
2016-02-09 03:17:01.678 ThaliTest[2780:8559818] client session: disconnect
2016-02-09 03:17:01.678 ThaliTest[2780:8559818] client session: stateChange:2->0 1454,984217855.993.Tw9Hdw==
,2016-02-09 03:17:01.691 ThaliTest[2780:8559818] client session: fireConnectionErrorEvent: 1454984217855.993.Tw9Hdw==
,2016-02-09 03:17:01.696 ThaliTest[2780:8560360] jxcore: connect 1454984217855.993.Tw9Hdw==
2016-02-09 03:17:01.700 ThaliTest[2780:8560360] client session: connect
2016-02-09 03:17:01.700 ThaliTest[2780:8560360] client session: stateChange:0->1 1454984217,855.993.Tw9Hdw==
,2016-02-09 03:17:01.888 ThaliTest[2780:8561598] server session: not connected 1454984217855.993
,2016-02-09 03:17:01.973 ThaliTest[2780:8559818] multipeer session: reset timer
2016-02-09 03:17:01.973 ThaliTest[2780:8559818] multipeer session: stop timer
2016-02-09 03:17:01.974 ThaliTest[2780:8559818] multipeer session: start timer: 0x1c140b50
2016-,02-09 03:17:01.974 ThaliTest[2780:8559818] server: disconnecting to refresh session (1454984217855.993)
2016-02-09 03:17:01.974 ThaliTest[2780:8559818] server session: disconnect
2016-02-09 03:17:01.974 ThaliTest[2780:8559818] server session: stateChange:2->0 1454984217855.993
,2016-02-09 03:17:01.978 ThaliTest[2780:8559818] server session: connect
2016-02-09 03:17:01.978 ThaliTest[2780:8559818] server session: stateChange:0->1 1454984217855.993
,2016-02-09 03:17:01.986 ThaliTest[2780:8559818] server: accepting invitation 1454984217855.993
,2016-02-09 03:17:04.183 ThaliTest[2780:8561815] server session: connected
2016-02-09 03:17:04.183 ThaliTest[2780:8561815] server session: stateChange:1->2 1454984217855.993
,2016-02-09 03:17:04.775 ThaliTest[2780:8559818] server relay: connected (to port: 49681)
,2016-02-09 03:17:04.796 ThaliTest[2780:8561815] client session: connected
,2016-02-09 03:17:04.797 ThaliTest[2780:8561815] client session: stateChange:1->2 1454984217855.993.Tw9Hdw==
,2016-02-09 03:17:04.800 ThaliTest[2780:8561815] client session: fireConnectCallback: 1454984217855.993.Tw9Hdw==
2016-02-09 03:17:04.800 ThaliTest[2780:8561815] jxcore: connect: success
,ok 108 Should be able to connect without error

,ok 109 Port should be within range

,ok 110 Second connect should succeed

,2016-02-09 03:17:04.827 ThaliTest[2780:8559818] client: relay established
2016-02-09 03:17:04.827 ThaliTest[2780:8559818] client: new accepted socket: 0x155f8630
,ok 111 the test messages should be equal

ok 112 Second send should succeed

,# setup

,2016-02-09 03:17:05.075 ThaliTest[2780:8559818] client: socket closed
2016-02-09 03:17:05.075 ThaliTest[2780:8559818] client relay: socket disconnected
2016-02-09 03:17:05.075 ThaliTest[2780:8559818] client relay: 0x155f8630 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 03:17:05.076 ThaliTest[2780:8559818] client session: socket closed: 1454984217855.993.Tw9Hdw==
2016-02-09 0,3:17:05.076 ThaliTest[2780:8559818] client session: onLinkFailure: 1454984217855.993.Tw9Hdw==
2016-02-09 03:17:05.076 ThaliTest[2780:8559818] client session: disconnect
2016-02-09 03:17:05.076 ThaliTest[2780:8559818] client session: stateChange:2->0 1454984217855.993.Tw9Hdw==
,2016-02-09 03:17:05.087 ThaliTest[2780:8559818] client session: fireConnectionErrorEvent: 1454984217855.993.Tw9Hdw==
,2016-02-09 03:17:05.607 ThaliTest[2780:8561598] server session: not connected 1454984217855.993
,2016-02-09 03:17:23.608 ThaliTest[2780:8559818] client: lost peer: 1454984217855.993.Tw9Hdw==
2016-02-09 03:17:23.609 ThaliTest[2780:8559818] client session: onPeerLost: 1454984217855.993.Tw9Hdw==
[{"peerIdentifier":"1454984217855.993.Tw9Hdw==","peerName":"(null)","peerAvailable":false}]

,calling stopBroadcasting

,2016-02-09 03:17:24.931 ThaliTest[2780:8560360] jxcore: stopBroadcasting
2016-02-09 03:17:24.932 ThaliTest[2780:8560360] THEMultipeerSession stopping peer
2016-02-09 03:17:24.932 ThaliTest[2780:8560360] multipeer session: stop timer
2016-02-09 03:17:24.,933 ThaliTest[2780:8560360] server session: disconnect
2016-02-09 03:17:24.933 ThaliTest[2780:8560360] server session: stateChange:2->0 1454984217855.993
,2016-02-09 03:17:24.939 ThaliTest[2780:8560360] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# #generatePreambleAndBeacons null ECDH for local device

,# teardown

,ok 113 ecdhForLocalDevice cannot be null

,# setup

,# #generatePreambleAndBeacons expiration out of range

,# teardown

,ok 114 secondsUntilExpiration out of range.

,# setup

,# #generatePreambleAndBeacons empty keys to notify

,# teardown

,ok 115 should be equal

,# setup

,# #generatePreambleAndBeacons multiple keys to notify

,# teardown

,ok 116 should be equal

,ok 117 should be equal

,ok 118 should be equal

,ok 119 should be equal

,# setup

,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,# teardown

,ok 120 should throw

,# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,# teardown

,ok 121 Preamble expiration must be a 64 bit integer

,# setup

,# #parseBeacons expiration out of range

,# teardown

,ok 122 Expiration out of range

,# setup

,# #parseBeacons no beacons returns null

,# teardown

,ok 123 should be equal

,# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,# teardown

,ok 124 Malformed encrypted beacon key ID

,# setup

,# #parseBeacons addressBookCallback fails decrypt

,# teardown

,ok 125 should be equal

,# setup

,# #parseBeacons addressBookCallback returns no matches

,# teardown

,ok 126 should be equal

,ok 127 should be equal

,# setup

,# #parseBeacons addressBookCallback returns public key

,# teardown

,ok 128 should be equal

,ok 129 (unnamed assert)

,# setup

,# #parseBeacons with beacons both for and not for the user

,# teardown

,ok 130 (unnamed assert)

,# setup

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/4B38A6C3-FBED-41B3-888D-397D7F9E4601/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 131 starting event should occur in right order

,2016-02-09 03:20:56.592 ThaliTest[2780:8560360] jxcore: startBroadcasting
,2016-02-09 03:20:56.595 ThaliTest[2780:8560360] server: starting bIBi0lXqqRYjUr0x3GWJLQ.quTy6g==
2016-02-09 03:20:56.595 ThaliTest[2780:8560360] multipeer session: start timer: 0x1b260cd0
2016-02-09 03:20:56.596 ThaliTest[2780:8560360] THEMultipeerSessio,n initialized peer bIBi0lXqqRYjUr0x3GWJLQ
2016-02-09 03:20:56.596 ThaliTest[2780:8560360] jxcore: startBroadcasting: success
ok 132 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 133 stopping event should occur in right order

,About to call stopBroadcasting

2016-02-09 03:20:56.599 ThaliTest[2780:8560360] jxcore: stopBroadcasting
,2016-02-09 03:20:56.600 ThaliTest[2780:8560360] THEMultipeerSession stopping peer
,2016-02-09 03:20:56.601 ThaliTest[2780:8560360] multipeer session: stop timer
,2016-02-09 03:20:56.601 ThaliTest[2780:8560360] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

ok 134 stopped event should occur in right order

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/4B38A6C3-FBED-41B3-888D-397D7F9E4601/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 03:21:11.886 ThaliTest[2780:8560360] jxcore: startBroadcasting
,2016-02-09 03:21:11.889 ThaliTest[2780:8560360] server: starting bIBi0lXqqRYjUr0x3GWJLQ.ZPTvSw==
2016-02-09 03:21:11.889 ThaliTest[2780:8560360] multipeer session: start timer: 0x1b457040
2016-02-09 03:21:11.889 ThaliTest[2780:8560360] THEMultipeerSessio,n initialized peer bIBi0lXqqRYjUr0x3GWJLQ
2016-02-09 03:21:11.890 ThaliTest[2780:8560360] jxcore: startBroadcasting: success
ok 135 getDeviceIdentity should not return an error

ok 136 deviceName should not be null

Now in TRM stop

State of this._,isStarted: true

About to call stopBroadcasting

,2016-02-09 03:21:11.892 ThaliTest[2780:8560360] jxcore: stopBroadcasting
2016-02-09 03:21:11.893 ThaliTest[2780:8560360] THEMultipeerSession stopping peer
2016-02-09 03:21:11.893 ThaliTest[2780:8560360] multipeer session: stop timer
2016-02-09 03:21:11.,893 ThaliTest[2780:8560360] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/4B38A6C3-FBED-41B3-888D-397D7F9E4601/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 03:21:20.198 ThaliTest[2780:8560360] jxcore: startBroadcasting
,2016-02-09 03:21:20.200 ThaliTest[2780:8560360] server: starting bIBi0lXqqRYjUr0x3GWJLQ.I7NLfQ==
2016-02-09 03:21:20.201 ThaliTest[2780:8560360] multipeer session: start timer: 0x1c583f30
2016-02-09 03:21:20.201 ThaliTest[2780:8560360] THEMultipeerSessio,n initialized peer bIBi0lXqqRYjUr0x3GWJLQ
2016-02-09 03:21:20.201 ThaliTest[2780:8560360] jxcore: startBroadcasting: success
ok 137 getDeviceIdentity should not return an error

ok 138 deviceName should not be null

,2016-02-09 03:21:20.939 ThaliTest[2780:8559818] client: found peer: Hr93NoKxPbQgmEH4U3bolg.sayvsg==
,2016-02-09 03:21:30.421 ThaliTest[2780:8559818] multipeer session: reset timer
2016-02-09 03:21:30.421 ThaliTest[2780:8559818] multipeer session: stop timer
2016-02-09 03:21:30.422 ThaliTest[2780:8559818] multipeer session: start timer: 0x1c583f30
2016-02-09 03:21:30.422 ThaliTest[2780:8559818] server session: connect
2016-02-09 03:21:30.422 ThaliTest[2780:8559818] server session: stateChange:0->1 Hr93NoKxPbQgmEH4U3bolg
2016-02-09 03:21:30.430 ThaliTest[2780:8559818] server: accepting invitation Hr93NoKxPbQgmEH4U3bolg
,2016-02-09 03:21:30.436 ThaliTest[2780:8560360] jxcore: connect Hr93NoKxPbQgmEH4U3bolg.sayvsg==
2016-02-09 03:21:30.445 ThaliTest[2780:8560360] client session: connect
2016-02-09 03:21:30.445 ThaliTest[2780:8560360] client session: stateChange:0->1 Hr93NoKxPbQgmEH4U3bolg.sayvsg==
,ok 139 Should be able to put doc without error

,ok 140 1st change of local doc should contain local id

,2016-02-09 03:21:33.210 ThaliTest[2780:8562395] server session: connected
2016-02-09 03:21:33.211 ThaliTest[2780:8562395] server session: stateChange:1->2 Hr93NoKxPbQgmEH4U3bolg
,2016-02-09 03:21:33.431 ThaliTest[2780:8559818] server relay: connected (to port: 49702)
,server bridge: new client socket

,2016-02-09 03:21:33.695 ThaliTest[2780:8562395] client session: connected
2016-02-09 03:21:33.696 ThaliTest[2780:8562395] client session: stateChange:1->2 Hr93NoKxPbQgmEH4U3bolg.sayvsg==
,2016-02-09 03:21:34.473 ThaliTest[2780:8562395] client session: fireConnectCallback: Hr93NoKxPbQgmEH4U3bolg.sayvsg==
2016-02-09 03:21:34.473 ThaliTest[2780:8562395] jxcore: connect: success
,2016-02-09 03:21:34.485 ThaliTest[2780:8559818] client: relay established
2016-02-09 03:21:34.485 ThaliTest[2780:8559818] client: new accepted socket: 0x1b7f03f0
,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed
,
,client bridge: socket closed
,
,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,Uncaught Promise Rejection: {"status":400}

,Trace: { [Error: ETIMEDOUT] status: 400 }
    at $3.prototype.trace@console.js:139:8
    at @/private/var/mobile/Containers/Bundle/Application/FFAB23EE-20E0-4465-9EB0-99F7C0DDF5B6/ThaliTest.app/www/jxcore/lib/thali-tape.js:37:3
    at emit@events.js:98:,1
    at handlers.reject/<@/private/var/mobile/Containers/Bundle/Application/FFAB23EE-20E0-4465-9EB0-99F7C0DDF5B6/ThaliTest.app/www/jxcore/node_modules/lie/lib/index.js:128:11
    at nextTick@/private/var/mobile/Containers/Bundle/Application/FFAB23EE-20E,0-4465-9EB0-99F7C0DDF5B6/ThaliTest.app/www/jxcore/node_modules/lie/node_modules/immediate/lib/index.js:61:7
    at $0a@node.js:917:1

****TEST TOOK:  ms ****
,
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****


```
