#### Test 56449660bb41d23_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56449660bb41d23/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/46E6E6C7-4CD1-4B04-92C7-4F6E699F910A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/46E6E6C7-4CD1-4B04-92C7-4F6E699F910A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/56449660bb41d23/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56449660bb41d23/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DBE80E2B-8D43-4642-BF2F-1E9D49EFDA90/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59614"
,(lldb)     command script import "/tmp/46E6E6C7-4CD1-4B04-92C7-4F6E699F910A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-21 16:41:22.611 ThaliTest[2403:6182978] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0171BE5E-EE77-4F81-9459-25554D0916CE/Library/Cookies/Cookies.binarycookies
,2016-01-21 16:41:22.943 ThaliTest[2403:6182978] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-21 16:41:22.944 ThaliTest[2403:6182978] Multi-tasking -> Device: YES, App: YES
,2016-01-21 16:41:22.953 ThaliTest[2403:6182978] Unlimited access to network resources
,2016-01-21 16:41:22.965 ThaliTest[2403:6182978] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-21 16:41:27.796 ThaliTest[2403:6182978] Resetting plugins due to page load.
,2016-01-21 16:41:29.561 ThaliTest[2403:6182978] Finished load of: file:///var/mobile/Containers/Bundle/Application/DBE80E2B-8D43-4642-BF2F-1E9D49EFDA90/ThaliTest.app/www/index.html
,2016-01-21 16:41:29.813 ThaliTest[2403:6182978] JXcore Cordova plugin initializing
2016-01-21 16:41:29.816 ThaliTest[2403:6183259] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DBE80E2B-8D43-4642-BF2F-1E9D49EFDA90/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DBE80E2B-8D43-4642-BF2F-1E9D49EFDA90/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DBE80E2B-8D43-4642-BF2F-1E9D49EFDA90/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DBE80E2B-8D43-4642-BF2F-1E9D49EFDA90/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DBE80E2B-8D43-4642-BF2F-1E9D49EFDA90/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DBE80E2B-8D43-4642-BF2F-1E9D49EFDA90/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DBE80E2B-8D43-4642-BF2F-1E9D49EFDA90/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,# teardown

,ok 1 String should be length:200

,# setup
,
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

# setup

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

ok 37 should be equal

,ok 38 should be equal

,# setup

,# #connect should call Mobile("Connect") and handle an error

,# teardown

,ok 39 should be equal

ok 40 should be equal

,# setup

,# should call Mobile("Disconnect") without an error

,# teardown

,ok 41 should be equal

ok 42 should be equal

# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 43 should be equal

ok 44 should be equal

# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-01-21 16:44:24.608 ThaliTest[2403:6183259] jxcore: startBroadcasting
,2016-01-21 16:44:24.617 ThaliTest[2403:6183259] server: starting 1453391064608.2403.OJsVLQ==
2016-01-21 16:44:24.617 ThaliTest[2403:6183259] multipeer session: start timer: 0x19763500
2016-01-21 16:44:24.617 ThaliTest[2403:6183259] THEMultipeerSession in,itialized peer 1453391064608.2403
2016-01-21 16:44:24.618 ThaliTest[2403:6183259] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error

2016-01-21 16:44:24.619 ThaliTest[2403:6183259] jxcore: stopBroadcasting
2016-01-21 16:44:24.619 ThaliTest[2403:6183259] THEMultipeerSession stopping peer
2016-01-21 16:44:24.619 ThaliTest[2403:6183259] multipeer session: stop timer
2016-01-21 16:44:24.619 ThaliTest[2403:6183259] jxcore: stopBroadcasting: success
ok 46 Shou,ld be able to call stopBroadcasting without error

2016-01-21 16:44:24.620 ThaliTest[2403:6183259] jxcore: startBroadcasting
2016-01-21 16:44:24.622 ThaliTest[2403:6183259] server: starting 1453391064620.2403.Gn0kZQ==
,2016-01-21 16:44:24.624 ThaliTest[2403:6183259] multipeer session: start timer: 0x193d9a30
,2016-01-21 16:44:24.631 ThaliTest[2403:6183259] THEMultipeerSession initialized peer 1453391064620.2403
,2016-01-21 16:44:24.632 ThaliTest[2403:6183259] jxcore: startBroadcasting: success
,ok 47 Should be able to call startBroadcasting without error
,
,2016-01-21 16:44:24.635 ThaliTest[2403:6183259] jxcore: stopBroadcasting
,2016-01-21 16:44:24.636 ThaliTest[2403:6183259] THEMultipeerSession stopping peer
,2016-01-21 16:44:24.637 ThaliTest[2403:6183259] multipeer session: stop timer
,2016-01-21 16:44:24.640 ThaliTest[2403:6183259] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
,
,2016-01-21 16:44:24.643 ThaliTest[2403:6183259] jxcore: startBroadcasting
,2016-01-21 16:44:24.645 ThaliTest[2403:6183259] server: starting 1453391064642.2403.vQtmLw==
,2016-01-21 16:44:24.649 ThaliTest[2403:6183259] multipeer session: start timer: 0x1a53ee00
,2016-01-21 16:44:24.651 ThaliTest[2403:6183259] THEMultipeerSession initialized peer 1453391064642.2403
,2016-01-21 16:44:24.652 ThaliTest[2403:6183259] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,
,2016-01-21 16:44:24.654 ThaliTest[2403:6183259] jxcore: stopBroadcasting
,2016-01-21 16:44:24.655 ThaliTest[2403:6183259] THEMultipeerSession stopping peer
,2016-01-21 16:44:24.656 ThaliTest[2403:6183259] multipeer session: stop timer
,2016-01-21 16:44:24.659 ThaliTest[2403:6183259] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error

,2016-01-21 16:44:24.661 ThaliTest[2403:6183259] jxcore: startBroadcasting
,2016-01-21 16:44:24.664 ThaliTest[2403:6183259] server: starting 1453391064661.2403.yTO2fw==
,2016-01-21 16:44:24.668 ThaliTest[2403:6183259] multipeer session: start timer: 0x1a53eea0
,2016-01-21 16:44:24.669 ThaliTest[2403:6183259] THEMultipeerSession initialized peer 1453391064661.2403
,2016-01-21 16:44:24.670 ThaliTest[2403:6183259] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error

,2016-01-21 16:44:24.672 ThaliTest[2403:6183259] jxcore: stopBroadcasting
,2016-01-21 16:44:24.673 ThaliTest[2403:6183259] THEMultipeerSession stopping peer
,2016-01-21 16:44:24.674 ThaliTest[2403:6183259] multipeer session: stop timer
,2016-01-21 16:44:24.676 ThaliTest[2403:6183259] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error

,2016-01-21 16:44:24.680 ThaliTest[2403:6183259] jxcore: startBroadcasting
,2016-01-21 16:44:24.689 ThaliTest[2403:6183259] server: starting 1453391064680.2403.F1MfXA==
,2016-01-21 16:44:24.692 ThaliTest[2403:6183259] multipeer session: start timer: 0x1936fb40
,2016-01-21 16:44:24.697 ThaliTest[2403:6183259] THEMultipeerSession initialized peer 1453391064680.2403
,2016-01-21 16:44:24.697 ThaliTest[2403:6183259] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,
,2016-01-21 16:44:24.700 ThaliTest[2403:6183259] jxcore: stopBroadcasting
,2016-01-21 16:44:24.701 ThaliTest[2403:6183259] THEMultipeerSession stopping peer
,2016-01-21 16:44:24.702 ThaliTest[2403:6183259] multipeer session: stop timer
,2016-01-21 16:44:24.706 ThaliTest[2403:6183259] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error

,2016-01-21 16:44:24.708 ThaliTest[2403:6183259] jxcore: startBroadcasting
,2016-01-21 16:44:24.711 ThaliTest[2403:6183259] server: starting 1453391064708.2403.3nTtxw==
,2016-01-21 16:44:24.715 ThaliTest[2403:6183259] multipeer session: start timer: 0x1936fb40
,2016-01-21 16:44:24.719 ThaliTest[2403:6183259] THEMultipeerSession initialized peer 1453391064708.2403
,2016-01-21 16:44:24.720 ThaliTest[2403:6183259] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,
,2016-01-21 16:44:24.722 ThaliTest[2403:6183259] jxcore: stopBroadcasting
,2016-01-21 16:44:24.724 ThaliTest[2403:6183259] THEMultipeerSession stopping peer
,2016-01-21 16:44:24.724 ThaliTest[2403:6183259] multipeer session: stop timer
,2016-01-21 16:44:24.728 ThaliTest[2403:6183259] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error

,2016-01-21 16:44:24.730 ThaliTest[2403:6183259] jxcore: startBroadcasting
,2016-01-21 16:44:24.733 ThaliTest[2403:6183259] server: starting 1453391064730.2403.hPzKuw==
,2016-01-21 16:44:24.737 ThaliTest[2403:6183259] multipeer session: start timer: 0x1a1aef00
,2016-01-21 16:44:24.741 ThaliTest[2403:6183259] THEMultipeerSession initialized peer 1453391064730.2403
,2016-01-21 16:44:24.742 ThaliTest[2403:6183259] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,
,2016-01-21 16:44:24.744 ThaliTest[2403:6183259] jxcore: stopBroadcasting
,2016-01-21 16:44:24.745 ThaliTest[2403:6183259] THEMultipeerSession stopping peer
,2016-01-21 16:44:24.746 ThaliTest[2403:6183259] multipeer session: stop timer
,2016-01-21 16:44:24.749 ThaliTest[2403:6183259] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error

,2016-01-21 16:44:24.751 ThaliTest[2403:6183259] jxcore: startBroadcasting
,2016-01-21 16:44:24.753 ThaliTest[2403:6183259] server: starting 1453391064751.2403.Xq0HGQ==
,2016-01-21 16:44:24.755 ThaliTest[2403:6183259] multipeer session: start timer: 0x1a541890
,2016-01-21 16:44:24.757 ThaliTest[2403:6183259] THEMultipeerSession initialized peer 1453391064751.2403
,2016-01-21 16:44:24.760 ThaliTest[2403:6183259] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error

,2016-01-21 16:44:24.762 ThaliTest[2403:6183259] jxcore: stopBroadcasting
,2016-01-21 16:44:24.762 ThaliTest[2403:6183259] THEMultipeerSession stopping peer
,2016-01-21 16:44:24.763 ThaliTest[2403:6183259] multipeer session: stop timer
,2016-01-21 16:44:24.764 ThaliTest[2403:6183259] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error

,2016-01-21 16:44:24.768 ThaliTest[2403:6183259] jxcore: startBroadcasting
,2016-01-21 16:44:24.770 ThaliTest[2403:6183259] server: starting 1453391064767.2403.uNU/nA==
,2016-01-21 16:44:24.771 ThaliTest[2403:6183259] multipeer session: start timer: 0x1a542260
,2016-01-21 16:44:24.773 ThaliTest[2403:6183259] THEMultipeerSession initialized peer 1453391064767.2403
2016-01-21 16:44:24.776 ThaliTest[2403:6183259] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error

,2016-01-21 16:44:24.778 ThaliTest[2403:6183259] jxcore: stopBroadcasting
,2016-01-21 16:44:24.778 ThaliTest[2403:6183259] THEMultipeerSession stopping peer
,2016-01-21 16:44:24.779 ThaliTest[2403:6183259] multipeer session: stop timer
,2016-01-21 16:44:24.780 ThaliTest[2403:6183259] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error

,2016-01-21 16:44:24.784 ThaliTest[2403:6183259] jxcore: startBroadcasting
,2016-01-21 16:44:24.787 ThaliTest[2403:6183259] server: starting 1453391064784.2403.vNqeRQ==
,2016-01-21 16:44:24.789 ThaliTest[2403:6183259] multipeer session: start timer: 0x1a133d10
,2016-01-21 16:44:24.791 ThaliTest[2403:6183259] THEMultipeerSession initialized peer 1453391064784.2403
,2016-01-21 16:44:24.796 ThaliTest[2403:6183259] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,
,2016-01-21 16:44:24.798 ThaliTest[2403:6183259] jxcore: stopBroadcasting
,2016-01-21 16:44:24.798 ThaliTest[2403:6183259] THEMultipeerSession stopping peer
,2016-01-21 16:44:24.799 ThaliTest[2403:6183259] multipeer session: stop timer
,2016-01-21 16:44:24.800 ThaliTest[2403:6183259] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,
,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-21 16:44:24.981 ThaliTest[2403:6183259] jxcore: startBroadcasting
,2016-01-21 16:44:24.983 ThaliTest[2403:6183259] server: starting 1453391064980.2403.EIhxTQ==
,2016-01-21 16:44:24.984 ThaliTest[2403:6183259] multipeer session: start timer: 0x19576c50
,2016-01-21 16:44:24.988 ThaliTest[2403:6183259] THEMultipeerSession initialized peer 1453391064980.2403
,2016-01-21 16:44:24.989 ThaliTest[2403:6183259] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error

,2016-01-21 16:44:24.991 ThaliTest[2403:6183259] jxcore: startBroadcasting
,2016-01-21 16:44:24.991 ThaliTest[2403:6183259] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice

,2016-01-21 16:44:24.994 ThaliTest[2403:6183259] jxcore: stopBroadcasting
,2016-01-21 16:44:24.994 ThaliTest[2403:6183259] THEMultipeerSession stopping peer
,2016-01-21 16:44:24.995 ThaliTest[2403:6183259] multipeer session: stop timer
,2016-01-21 16:44:24.996 ThaliTest[2403:6183259] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,
,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-21 16:44:25.412 ThaliTest[2403:6183259] jxcore: startBroadcasting
,2016-01-21 16:44:25.414 ThaliTest[2403:6183259] server: starting 1453391065412.2403.Q7B1wg==
2016-01-21 16:44:25.414 ThaliTest[2403:6183259] multipeer session: start timer: 0x19781100
2016-01-21 16:44:25.414 ThaliTest[2403:6183259] THEMultipeerSession initialized peer 1453391065412.2403
2016-01-21 16:44:25.414 ThaliTest[2403:6183259] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error

2016-01-21 16:44:25.416 ThaliTest[2403:6183259] jxcore: connect foobar
2,016-01-21 16:44:25.416 ThaliTest[2403:6183259] client: unknown peer foobar
2016-01-21 16:44:25.416 ThaliTest[2403:6183259] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer

,2016-01-21 16:44:25.418 ThaliTest[2403:6183259] jxcore: stopBroadcasting
2016-01-21 16:44:25.419 ThaliTest[2403:6183259] THEMultipeerSession stopping peer
2016-01-21 16:44:25.419 ThaliTest[2403:6183259] multipeer session: stop timer
2016-01-21 16:44:25.419 ThaliTest[2403:6183259] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-21 16:44:26.141 ThaliTest[2403:6183259] jxcore: startBroadcasting
,2016-01-21 16:44:26.144 ThaliTest[2403:6183259] server: starting 1453391066141.2403.bb7pyw==
2016-01-21 16:44:26.144 ThaliTest[2403:6183259] multipeer session: start timer: 0x19713970
2016-01-21 16:44:26.144 ThaliTest[2403:6183259] THEMultipeerSession initialized peer 1453391066141.2403
2016-01-21 16:44:26.144 ThaliTest[2403:6183259] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error

2016-01-21 16:44:26.146 ThaliTest[2403:6183259] jxcore: disconnect
2016-01-21 16:44:26.146 ThaliTest[2403:6183259] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 

,2016-01-21 16:44:26.147 ThaliTest[2403:6183259] jxcore: stopBroadcasting
2016-01-21 16:44:26.151 ThaliTest[2403:6183259] THEMultipeerSession stopping peer
2016-01-21 16:44:26.151 ThaliTest[2403:6183259] multipeer session: stop timer
2016-01-21 16:44:26.,151 ThaliTest[2403:6183259] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-21 16:44:27.059 ThaliTest[2403:6183259] jxcore: startBroadcasting
,2016-01-21 16:44:27.062 ThaliTest[2403:6183259] server: starting 1453391067059.2403.nY8DCQ==
2016-01-21 16:44:27.062 ThaliTest[2403:6183259] multipeer session: start timer: 0x1a50e1e0
2016-01-21 16:44:27.062 ThaliTest[2403:6183259] THEMultipeerSession initialized peer 1453391067059.2403
2016-01-21 16:44:27.064 ThaliTest[2403:6183259] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error

,2016-01-21 16:44:28.716 ThaliTest[2403:6182978] client: found peer: 1453391069808.2494.3U3gzw==
2016-01-21 16:44:28.717 ThaliTest[2403:6183259] jxcore: connect 1453391069808.2494.3U3gzw==
2016-01-21 16:44:28.718 ThaliTest[2403:6183259] client session: connect
2016-01-21 16:44:28.718 ThaliTest[2403:6183259] client session: stateChange:0->1 1453391069808.2494.3U3gzw==
,2016-01-21 16:44:28.805 ThaliTest[2403:6182978] multipeer session: reset timer
2016-01-21 16:44:28.805 ThaliTest[2403:6182978] multipeer session: stop timer
2016-01-21 16:44:28.805 ThaliTest[2403:6182978] multipeer session: start timer: 0x1a50e1e0
2016-,01-21 16:44:28.805 ThaliTest[2403:6182978] server session: connect
2016-01-21 16:44:28.805 ThaliTest[2403:6182978] server session: stateChange:0->1 1453391069808.2494
2016-01-21 16:44:28.810 ThaliTest[2403:6182978] server: accepting invitation 1453391069808.2494
,2016-01-21 16:44:31.864 ThaliTest[2403:6184948] server session: connected
2016-01-21 16:44:31.864 ThaliTest[2403:6184948] server session: stateChange:1->2 1453391069808.2494
,2016-01-21 16:44:31.958 ThaliTest[2403:6184947] server session: not connected 1453391069808.2494
,2016-01-21 16:44:32.444 ThaliTest[2403:6184947] client session: connected
2016-01-21 16:44:32.444 ThaliTest[2403:6184947] client session: stateChange:1->2 1453391069808.2494.3U3gzw==
,2016-01-21 16:44:32.773 ThaliTest[2403:6184944] client session: fireConnectCallback: 1453391069808.2494.3U3gzw==
2016-01-21 16:44:32.773 ThaliTest[2403:6184944] jxcore: connect: success
ok 75 Should be able to connect without error

ok 76 Port should be within range

,2016-01-21 16:44:32.775 ThaliTest[2403:6183259] jxcore: disconnect
2016-01-21 16:44:32.778 ThaliTest[2403:6183259] client session: disconnectFromPeer: 1453391069808.2494.3U3gzw==
2016-01-21 16:44:32.778 ThaliTest[2403:6183259] client session: disconnect,
2016-01-21 16:44:32.778 ThaliTest[2403:6183259] client session: stateChange:2->0 1453391069808.2494.3U3gzw==
,2016-01-21 16:44:32.786 ThaliTest[2403:6183259] jxcore: disconnect: success
ok 77 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-21 16:44:33.364 ThaliTest[2403:6183259] jxcore: stopBroadcasting
2016-01-21 16:44:33.364 ThaliTest[2403:6183259] THEMultipeerSession stopping peer
2016-01-21 16:44:33.365 ThaliTest[2403:6183259] multipeer session: stop timer
2016-01-21 16:44:33.365 ThaliTest[2403:6183259] server session: disconnect
2016-01-21 16:44:33.365 ThaliTest[2403:6183259] server session: stateChange:2->0 1453391069808.2494
,2016-01-21 16:44:33.729 ThaliTest[2403:6183259] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-21 16:44:33.919 ThaliTest[2403:6183259] jxcore: startBroadcasting
,2016-01-21 16:44:33.921 ThaliTest[2403:6183259] server: starting 1453391073919.2403.16iqqw==
2016-01-21 16:44:33.922 ThaliTest[2403:6183259] multipeer session: start timer: 0x1a5116f0
2016-01-21 16:44:33.922 ThaliTest[2403:6183259] THEMultipeerSession initialized peer 1453391073919.2403
2016-01-21 16:44:33.922 ThaliTest[2403:6183259] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error

,2016-01-21 16:44:35.067 ThaliTest[2403:6182978] client: found peer: 1453391076695.2494.eT/2Zw==
,2016-01-21 16:44:35.067 ThaliTest[2403:6183259] jxcore: connect 1453391076695.2494.eT/2Zw==
2016-01-21 16:44:35.068 ThaliTest[2403:6183259] client session: connect
2016-01-21 16:44:35.068 ThaliTest[2403:6183259] client session: stateChange:0->1 145339107,6695.2494.eT/2Zw==
,2016-01-21 16:44:35.144 ThaliTest[2403:6182978] multipeer session: reset timer
2016-01-21 16:44:35.144 ThaliTest[2403:6182978] multipeer session: stop timer
2016-01-21 16:44:35.145 ThaliTest[2403:6182978] multipeer session: start timer: 0x1a5116f0
2016-01-21 16:44:35.145 ThaliTest[2403:6182978] server session: connect
,2016-01-21 16:44:35.145 ThaliTest[2403:6182978] server session: stateChange:0->1 1453391076695.2494
2016-01-21 16:44:35.149 ThaliTest[2403:6182978] server: accepting invitation 1453391076695.2494
,2016-01-21 16:44:37.737 ThaliTest[2403:6184944] server session: connected
2016-01-21 16:44:37.737 ThaliTest[2403:6184944] server session: stateChange:1->2 1453391076695.2494
,2016-01-21 16:44:37.740 ThaliTest[2403:6182978] server relay: socket disconnected
2016-01-21 16:44:37.740 ThaliTest[2403:6182978] server relay: 0x1a188d10 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-21 16:44:37.762 ThaliTest[2403:6184948] server session: not connected 1453391076695.2494
,2016-01-21 16:44:37.808 ThaliTest[2403:6184944] client session: connected
2016-01-21 16:44:37.808 ThaliTest[2403:6184944] client session: stateChange:1->2 1453391076695.2494.eT/2Zw==
,2016-01-21 16:44:37.811 ThaliTest[2403:6184944] client session: fireConnectCallback: 1453391076695.2494.eT/2Zw==
2016-01-21 16:44:37.811 ThaliTest[2403:6184944] jxcore: connect: success
ok 79 Should be able to connect without error

,ok 80 Port should be within range

,2016-01-21 16:44:37.813 ThaliTest[2403:6183259] jxcore: connect 1453391076695.2494.eT/2Zw==
2016-01-21 16:44:37.814 ThaliTest[2403:6183259] client: already connect(ing/ed) to 1453391076695.2494.eT/2Zw==
2016-01-21 16:44:37.814 ThaliTest[2403:6183259] jxcore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect

2016-01-21 16:44:37.816 ThaliTest[2403:6183259] jxcore: disconnect
2016-01-21 16:44:37.816 ThaliTest[2403:6183259] client session: disconnectFromPeer: 1453391076695.2494.eT/2Zw==
2016-01-21 16:44:37.816 ThaliTest[2403:6183259] client session: disconnect
,2016-01-21 16:44:37.816 ThaliTest[2403:6183259] client session: stateChange:2->0 1453391076695.2494.eT/2Zw==
,2016-01-21 16:44:37.820 ThaliTest[2403:6183259] jxcore: disconnect: success
ok 82 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-21 16:44:38.096 ThaliTest[2403:6183259] jxcore: stopBroadcasting
2016-01-21 16:44:38.096 ThaliTest[2403:6183259] THEMultipeerSession stopping peer
2016-01-21 16:44:38.096 ThaliTest[2403:6183259] multipeer session: stop timer
2016-01-21 16:44:38.,096 ThaliTest[2403:6183259] server session: disconnect
2016-01-21 16:44:38.097 ThaliTest[2403:6183259] server session: stateChange:2->0 1453391076695.2494
2016-01-21 16:44:38.097 ThaliTest[2403:6183259] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-21 16:44:38.169 ThaliTest[2403:6183259] jxcore: startBroadcasting
,2016-01-21 16:44:38.170 ThaliTest[2403:6183259] server: starting 1453391078168.2403.Fxajfg==
2016-01-21 16:44:38.170 ThaliTest[2403:6183259] multipeer session: start timer: 0x1a72e960
2016-01-21 16:44:38.171 ThaliTest[2403:6183259] THEMultipeerSession initialized peer 1453391078168.2403
2016-01-21 16:44:38.171 ThaliTest[2403:6183259] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-21 16:44:38.179 ThaliTest[2403:6182978] client: found peer: 1453391073919.2403.16iqqw==
2016-01-21 16:44:38.180 ThaliTest[2403:6183259] jxcore: connect 1453391073919.2403.16iqqw==
2016-01-21 16:44:38.180 ThaliTest[2403:6183259] client session: co,nnect
2016-01-21 16:44:38.180 ThaliTest[2403:6183259] client session: stateChange:0->1 1453391073919.2403.16iqqw==
,2016-01-21 16:44:38.182 ThaliTest[2403:6182978] client: found peer: 1453391076695.2494.eT/2Zw==
,2016-01-21 16:44:38.293 ThaliTest[2403:6183259] jxcore: connect 1453391076695.2494.eT/2Zw==
2016-01-21 16:44:38.293 ThaliTest[2403:6183259] client session: connect
2016-01-21 16:44:38.293 ThaliTest[2403:6183259] client session: stateChange:0->1 1453391076695.2494.eT/2Zw==
,2016-01-21 16:44:39.307 ThaliTest[2403:6182978] client: lost peer: 1453391073919.2403.16iqqw==
2016-01-21 16:44:39.307 ThaliTest[2403:6182978] client session: onPeerLost: 1453391073919.2403.16iqqw==
2016-01-21 16:44:39.307 ThaliTest[2403:6182978] client ,session: onLinkFailure: 1453391073919.2403.16iqqw==
2016-01-21 16:44:39.307 ThaliTest[2403:6182978] client session: disconnect
2016-01-21 16:44:39.307 ThaliTest[2403:6182978] client session: stateChange:1->0 1453391073919.2403.16iqqw==
2016-01-21 16:44:39.308 ThaliTest[2403:6182978] client session: fireConnectCallback: 1453391073919.2403.16iqqw==
2016-01-21 16:44:39.308 ThaliTest[2403:6182978] jxcore: connect: fail: Peer disconnected
2016-01-21 16:44:39.309 ThaliTest[2403:6182978] client: lost peer: 14,53391076695.2494.eT/2Zw==
2016-01-21 16:44:39.309 ThaliTest[2403:6182978] client session: onPeerLost: 1453391076695.2494.eT/2Zw==
2016-01-21 16:44:39.309 ThaliTest[2403:6182978] client session: onLinkFailure: 1453391076695.2494.eT/2Zw==
2016-01-21 16:44,:39.309 ThaliTest[2403:6182978] client session: disconnect
2016-01-21 16:44:39.309 ThaliTest[2403:6182978] client session: stateChange:1->0 1453391076695.2494.eT/2Zw==
2016-01-21 16:44:39.310 ThaliTest[2403:6182978] client session: fireConnectCallback: 1,453391076695.2494.eT/2Zw==
2016-01-21 16:44:39.310 ThaliTest[2403:6182978] jxcore: connect: fail: Peer disconnected
,2016-01-21 16:44:39.337 ThaliTest[2403:6182978] multipeer session: reset timer
2016-01-21 16:44:39.337 ThaliTest[2403:6182978] multipeer session: stop timer
2016-01-21 16:44:39.337 ThaliTest[2403:6182978] multipeer session: start timer: 0x1a72e960
,2016-01-21 16:44:39.337 ThaliTest[2403:6182978] server session: connect
2016-01-21 16:44:39.338 ThaliTest[2403:6182978] server session: stateChange:0->1 1453391081351.2494
,2016-01-21 16:44:39.343 ThaliTest[2403:6182978] server: accepting invitation 1453391081351.2494
,2016-01-21 16:44:39.526 ThaliTest[2403:6182978] client: found peer: 1453391081351.2494.qPjuwg==
2016-01-21 16:44:39.526 ThaliTest[2403:6183259] jxcore: connect 1453391081351.2494.qPjuwg==
,2016-01-21 16:44:39.527 ThaliTest[2403:6183259] client session: connect
,2016-01-21 16:44:39.527 ThaliTest[2403:6183259] client session: stateChange:0->1 1453391081351.2494.qPjuwg==
,2016-01-21 16:44:40.318 ThaliTest[2403:6183259] jxcore: connect 1453391073919.2403.16iqqw==
,2016-01-21 16:44:40.318 ThaliTest[2403:6183259] client: connect: unreachable 1453391073919.2403.16iqqw==
2016-01-21 16:44:40.319 ThaliTest[2403:6183259] jxcore: connect: fail: Peer unreachable
,2016-01-21 16:44:40.319 ThaliTest[2403:6183259] jxcore: connect 1453391076695.2494.eT/2Zw==
2016-01-21 16:44:40.320 ThaliTest[2403:6183259] client: connect: unreachable 1453391076695.2494.eT/2Zw==
,2016-01-21 16:44:40.320 ThaliTest[2403:6183259] jxcore: connect: fail: Peer unreachable
,2016-01-21 16:44:41.737 ThaliTest[2403:6184942] server session: connected
2016-01-21 16:44:41.737 ThaliTest[2403:6184942] server session: stateChange:1->2 1453391081351.2494
,2016-01-21 16:44:41.743 ThaliTest[2403:6182978] server relay: socket disconnected
2016-01-21 16:44:41.743 ThaliTest[2403:6182978] server relay: 0x1a1d18a0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-21 16:44:41.752 ThaliTest[2403:6184949] server session: not connected 1453391081351.2494
,2016-01-21 16:44:42.278 ThaliTest[2403:6184949] client session: connected
2016-01-21 16:44:42.278 ThaliTest[2403:6184949] client session: stateChange:1->2 1453391081351.2494.qPjuwg==
,2016-01-21 16:44:42.287 ThaliTest[2403:6184944] client session: fireConnectCallback: 1453391081351.2494.qPjuwg==
2016-01-21 16:44:42.288 ThaliTest[2403:6184944] jxcore: connect: success
ok 84 Should be able to connect without error

,ok 85 Port should be within range

,2016-01-21 16:44:42.290 ThaliTest[2403:6183259] jxcore: disconnect
2016-01-21 16:44:42.290 ThaliTest[2403:6183259] client session: disconnectFromPeer: 1453391081351.2494.qPjuwg==
2016-01-21 16:44:42.290 ThaliTest[2403:6183259] client session: disconnect,
2016-01-21 16:44:42.290 ThaliTest[2403:6183259] client session: stateChange:2->0 1453391081351.2494.qPjuwg==
,2016-01-21 16:44:42.296 ThaliTest[2403:6183259] jxcore: disconnect: success
ok 86 Should be able to disconnect without error

2016-01-21 16:44:42.297 ThaliTest[2403:6183259] jxcore: disconnect
2016-01-21 16:44:42.298 ThaliTest[2403:6183259] jxcore: disconnect: fail
ok 87 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup
,
,calling stopBroadcasting

,2016-01-21 16:44:42.341 ThaliTest[2403:6183259] jxcore: stopBroadcasting
,2016-01-21 16:44:42.341 ThaliTest[2403:6183259] THEMultipeerSession stopping peer
,2016-01-21 16:44:42.342 ThaliTest[2403:6183259] multipeer session: stop timer
,2016-01-21 16:44:42.343 ThaliTest[2403:6183259] server session: disconnect
,2016-01-21 16:44:42.344 ThaliTest[2403:6183259] server session: stateChange:2->0 1453391081351.2494
,2016-01-21 16:44:42.405 ThaliTest[2403:6183259] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 62969

,2016-01-21 16:44:43.449 ThaliTest[2403:6183259] jxcore: startBroadcasting
,2016-01-21 16:44:43.451 ThaliTest[2403:6183259] server: starting 1453391083448.2403.7XEqsg==
,2016-01-21 16:44:43.453 ThaliTest[2403:6183259] multipeer session: start timer: 0x1a71cc10
,2016-01-21 16:44:43.457 ThaliTest[2403:6183259] THEMultipeerSession initialized peer 1453391083448.2403
,2016-01-21 16:44:43.458 ThaliTest[2403:6183259] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error

,2016-01-21 16:44:44.138 ThaliTest[2403:6182978] client: found peer: 1453391086060.2494.ByQIxQ==
2016-01-21 16:44:44.138 ThaliTest[2403:6183259] jxcore: connect 1453391086060.2494.ByQIxQ==
2016-01-21 16:44:44.139 ThaliTest[2403:6183259] client session: connect
2016-01-21 16:44:44.139 ThaliTest[2403:6183259] client session: stateChange:0->1 1453391086060.2494.ByQIxQ==
,2016-01-21 16:44:44.576 ThaliTest[2403:6182978] multipeer session: reset timer
2016-01-21 16:44:44.576 ThaliTest[2403:6182978] multipeer session: stop timer
2016-01-21 16:44:44.576 ThaliTest[2403:6182978] multipeer session: start timer: 0x1a71cc10
2016-01-21 16:44:44.577 ThaliTest[2403:6182978] server session: connect
2016-01-21 16:44:44.577 ThaliTest[2403:6182978] server session: stateChange:0->1 1453391086060.2494
,2016-01-21 16:44:44.581 ThaliTest[2403:6182978] server: accepting invitation 1453391086060.2494
,2016-01-21 16:44:47.069 ThaliTest[2403:6184944] client session: connected
2016-01-21 16:44:47.069 ThaliTest[2403:6184944] client session: stateChange:1->2 1453391086060.2494.ByQIxQ==
,2016-01-21 16:44:47.073 ThaliTest[2403:6184944] client session: fireConnectCallback: 1453391086060.2494.ByQIxQ==
2016-01-21 16:44:47.073 ThaliTest[2403:6184944] jxcore: connect: success
ok 89 Should be able to connect without error

,ok 90 Port should be within range

,2016-01-21 16:44:47.076 ThaliTest[2403:6182978] client: relay established
2016-01-21 16:44:47.076 ThaliTest[2403:6182978] client: new accepted socket: 0x197d7f10
,2016-01-21 16:44:47.126 ThaliTest[2403:6184942] server session: connected
,2016-01-21 16:44:47.127 ThaliTest[2403:6184942] server session: stateChange:1->2 1453391086060.2494
,2016-01-21 16:44:47.157 ThaliTest[2403:6182978] server relay: connected (to port: 62969)
,data in 5475

,data in 12927

,data in 13140

,data in 25185

,data in 29565

,data in 30660

,data in 40515

,data in 65700

,data in 71175

,data in 72270

,data in 74460

,data in 78840

,data in 83220

,data in 89790

,data in 94170

,data in 105120

,data in 114975

,data in 123664

,data in 131072

,ok 91 the test messages should be equal

,2016-01-21 16:44:47.745 ThaliTest[2403:6183259] jxcore: disconnect
2016-01-21 16:44:47.745 ThaliTest[2403:6183259] client session: disconnectFromPeer: 1453391086060.2494.ByQIxQ==
2016-01-21 16:44:47.745 ThaliTest[2403:6183259] client session: disconnect
2016-01-21 16:44:47.745 ThaliTest[2403:6183259] client session: stateChange:2->0 1453391086060.2494.ByQIxQ==
,2016-01-21 16:44:47.752 ThaliTest[2403:6183259] jxcore: disconnect: success
ok 92 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup
,
,2016-01-21 16:44:47.896 ThaliTest[2403:6184949] server session: not connected 1453391086060.2494
,calling stopBroadcasting

,2016-01-21 16:44:48.167 ThaliTest[2403:6183259] jxcore: stopBroadcasting
2016-01-21 16:44:48.167 ThaliTest[2403:6183259] THEMultipeerSession stopping peer
2016-01-21 16:44:48.167 ThaliTest[2403:6183259] multipeer session: stop timer
2016-01-21 16:44:48.,167 ThaliTest[2403:6183259] server session: disconnect
2016-01-21 16:44:48.167 ThaliTest[2403:6183259] server session: stateChange:2->0 1453391086060.2494
,2016-01-21 16:44:48.883 ThaliTest[2403:6183259] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 62975

,2016-01-21 16:44:51.783 ThaliTest[2403:6183259] jxcore: startBroadcasting
,2016-01-21 16:44:51.785 ThaliTest[2403:6183259] server: starting 1453391091783.2403.hlBK9w==
2016-01-21 16:44:51.785 ThaliTest[2403:6183259] multipeer session: start timer: 0x1a71da50
2016-01-21 16:44:51.785 ThaliTest[2403:6183259] THEMultipeerSession initialized peer 1453391091783.2403
,2016-01-21 16:44:51.787 ThaliTest[2403:6183259] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error

,2016-01-21 16:44:52.960 ThaliTest[2403:6182978] client: found peer: 1453391094828.2494.wCjumA==
[{"peerIdentifier":"1453391094828.2494.wCjumA==","peerName":"(null)","peerAvailable":true}]

2016-01-21 16:44:52.961 ThaliTest[2403:6183259] jxcore: connect ,1453391094828.2494.wCjumA==
2016-01-21 16:44:52.961 ThaliTest[2403:6183259] client session: connect
2016-01-21 16:44:52.962 ThaliTest[2403:6183259] client session: stateChange:0->1 1453391094828.2494.wCjumA==
,2016-01-21 16:44:53.038 ThaliTest[2403:6182978] multipeer session: reset timer
2016-01-21 16:44:53.038 ThaliTest[2403:6182978] multipeer session: stop timer
2016-01-21 16:44:53.038 ThaliTest[2403:6182978] multipeer session: start timer: 0x1a71da50
2016-01-21 16:44:53.039 ThaliTest[2403:6182978] server session: connect
2016-01-21 16:44:53.039 ThaliTest[2403:6182978] server session: stateChange:0->1 1453391094828.2494
,2016-01-21 16:44:53.045 ThaliTest[2403:6182978] server: accepting invitation 1453391094828.2494
,2016-01-21 16:44:55.674 ThaliTest[2403:6184949] server session: connected
2016-01-21 16:44:55.674 ThaliTest[2403:6184949] server session: stateChange:1->2 1453391094828.2494
,2016-01-21 16:44:55.683 ThaliTest[2403:6182978] server relay: connected (to port: 62975)
,2016-01-21 16:44:55.734 ThaliTest[2403:6184948] client session: connected
2016-01-21 16:44:55.734 ThaliTest[2403:6184948] client session: stateChange:1->2 1453391094828.2494.wCjumA==
,2016-01-21 16:44:55.780 ThaliTest[2403:6184949] client session: fireConnectCallback: 1453391094828.2494.wCjumA==
2016-01-21 16:44:55.781 ThaliTest[2403:6184949] jxcore: connect: success
,ok 94 Should be able to connect without error

ok 95 Port should be within range

ok 96 First connect should succeed

,2016-01-21 16:44:55.788 ThaliTest[2403:6184948] server session: not connected 1453391094828.2494
,2016-01-21 16:44:55.796 ThaliTest[2403:6182978] client: relay established
,2016-01-21 16:44:55.797 ThaliTest[2403:6182978] client: new accepted socket: 0x1a72dcb0
,2016-01-21 16:44:55.846 ThaliTest[2403:6182978] multipeer session: reset timer
2016-01-21 16:44:55.846 ThaliTest[2403:6182978] multipeer session: stop timer
,2016-01-21 16:44:55.846 ThaliTest[2403:6182978] multipeer session: start timer: 0x1a71da50
2016-01-21 16:44:55.846 ThaliTest[2403:6182978] server: disconnecting to refresh session (1453391094828.2494)
2016-01-21 16:44:55.847 ThaliTest[2403:6182978] server session: disconnect
,2016-01-21 16:44:55.847 ThaliTest[2403:6182978] server session: stateChange:2->0 1453391094828.2494
,2016-01-21 16:44:55.849 ThaliTest[2403:6182978] server session: connect
,2016-01-21 16:44:55.849 ThaliTest[2403:6182978] server session: stateChange:0->1 1453391094828.2494
,2016-01-21 16:44:55.857 ThaliTest[2403:6182978] server: accepting invitation 1453391094828.2494
,ok 97 the test messages should be equal

ok 98 First send should succeed

,2016-01-21 16:44:55.906 ThaliTest[2403:6182978] client: socket closed
2016-01-21 16:44:55.906 ThaliTest[2403:6182978] client relay: socket disconnected
2016-01-21 16:44:55.906 ThaliTest[2403:6182978] client relay: 0x1a72dcb0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-21 16:44:55.906 ThaliTest[2403:6182978] client session: socket closed: 1453391094828.2494.wCjumA==
2016-01-21 16:44:55.906 ThaliTest[2403:6182978] client session: onLinkFailure: 1453391094828.2494.wCjumA==
2016-01-21 16:44:55.906 ThaliTest[2403:6182978] client session: disconnect
2016-01-21 16:44:55.906 ThaliTest[2403:6182978] client session: stateChange:2->0 14,53391094828.2494.wCjumA==
,2016-01-21 16:44:55.917 ThaliTest[2403:6182978] client session: fireConnectionErrorEvent: 1453391094828.2494.wCjumA==
,2016-01-21 16:44:55.919 ThaliTest[2403:6183259] jxcore: connect 1453391094828.2494.wCjumA==
,2016-01-21 16:44:55.921 ThaliTest[2403:6183259] client session: connect
,2016-01-21 16:44:55.922 ThaliTest[2403:6183259] client session: stateChange:0->1 1453391094828.2494.wCjumA==
,2016-01-21 16:44:58.272 ThaliTest[2403:6184942] server session: connected
,2016-01-21 16:44:58.272 ThaliTest[2403:6184942] server session: stateChange:1->2 1453391094828.2494
,2016-01-21 16:44:58.337 ThaliTest[2403:6182978] server relay: connected (to port: 62975)
,2016-01-21 16:44:58.429 ThaliTest[2403:6184948] server session: not connected 1453391094828.2494
,2016-01-21 16:44:58.731 ThaliTest[2403:6184948] client session: connected
2016-01-21 16:44:58.731 ThaliTest[2403:6184948] client session: stateChange:1->2 1453391094828.2494.wCjumA==
,2016-01-21 16:44:58.785 ThaliTest[2403:6185064] client session: fireConnectCallback: 1453391094828.2494.wCjumA==
2016-01-21 16:44:58.786 ThaliTest[2403:6185064] jxcore: connect: success
ok 99 Should be able to connect without error

,ok 100 Port should be within range

,ok 101 Second connect should succeed

,2016-01-21 16:44:58.800 ThaliTest[2403:6182978] client: relay established
2016-01-21 16:44:58.800 ThaliTest[2403:6182978] client: new accepted socket: 0x1a16d420
,ok 102 the test messages should be equal

,ok 103 Second send should succeed

,# setup

,2016-01-21 16:44:58.889 ThaliTest[2403:6182978] client: socket closed
2016-01-21 16:44:58.889 ThaliTest[2403:6182978] client relay: socket disconnected
2016-01-21 16:44:58.889 ThaliTest[2403:6182978] client relay: 0x1a16d420 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-21 16:44:58.889 ThaliTest[2403:6182978] client session: socket closed: 1453391094828.2494.wCjumA==
2016-01-21 ,16:44:58.889 ThaliTest[2403:6182978] client session: onLinkFailure: 1453391094828.2494.wCjumA==
2016-01-21 16:44:58.889 ThaliTest[2403:6182978] client session: disconnect
2016-01-21 16:44:58.889 ThaliTest[2403:6182978] client session: stateChange:2->0 1453391094828.2494.wCjumA==
,2016-01-21 16:44:58.894 ThaliTest[2403:6182978] client session: fireConnectionErrorEvent: 1453391094828.2494.wCjumA==
,calling stopBroadcasting

2016-01-21 16:44:59.064 ThaliTest[2403:6183259] jxcore: stopBroadcasting
,2016-01-21 16:44:59.064 ThaliTest[2403:6183259] THEMultipeerSession stopping peer
,2016-01-21 16:44:59.065 ThaliTest[2403:6183259] multipeer session: stop timer
,2016-01-21 16:44:59.067 ThaliTest[2403:6183259] server session: disconnect
,2016-01-21 16:44:59.067 ThaliTest[2403:6183259] server session: stateChange:2->0 1453391094828.2494
,2016-01-21 16:45:00.090 ThaliTest[2403:6183259] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/0171BE5E-EE77-4F81-9459-25554D0916CE/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 104 starting event should occur in right order

,2016-01-21 16:45:00.514 ThaliTest[2403:6183259] jxcore: startBroadcasting
,2016-01-21 16:45:00.516 ThaliTest[2403:6183259] server: starting TQJolC_lnHeSmLHZWAv11A.lYR6DQ==
2016-01-21 16:45:00.516 ThaliTest[2403:6183259] multipeer session: start timer: 0x1a14d270
2016-01-21 16:45:00.517 ThaliTest[2403:6183259] THEMultipeerSessio,n initialized peer TQJolC_lnHeSmLHZWAv11A
2016-01-21 16:45:00.517 ThaliTest[2403:6183259] jxcore: startBroadcasting: success
ok 105 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 106 stopping event should occur in right order

About to call stopBroadcasting

,2016-01-21 16:45:00.519 ThaliTest[2403:6183259] jxcore: stopBroadcasting
2016-01-21 16:45:00.519 ThaliTest[2403:6183259] THEMultipeerSession stopping peer
2016-01-21 16:45:00.519 ThaliTest[2403:6183259] multipeer session: stop timer
,2016-01-21 16:45:00.520 ThaliTest[2403:6183259] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

ok 107 stopped event should occur in right order

,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/0171BE5E-EE77-4F81-9459-25554D0916CE/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-21 16:45:00.674 ThaliTest[2403:6183259] jxcore: startBroadcasting
,2016-01-21 16:45:00.676 ThaliTest[2403:6183259] server: starting TQJolC_lnHeSmLHZWAv11A.YPOQvQ==
2016-01-21 16:45:00.676 ThaliTest[2403:6183259] multipeer session: start timer: 0x1a106b60
2016-01-21 16:45:00.677 ThaliTest[2403:6183259] THEMultipeerSessio,n initialized peer TQJolC_lnHeSmLHZWAv11A
2016-01-21 16:45:00.677 ThaliTest[2403:6183259] jxcore: startBroadcasting: success
ok 108 getDeviceIdentity should not return an error

ok 109 deviceName should not be null

Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

,2016-01-21 16:45:00.679 ThaliTest[2403:6183259] jxcore: stopBroadcasting
2016-01-21 16:45:00.679 ThaliTest[2403:6183259] THEMultipeerSession stopping peer
2016-01-21 16:45:00.679 ThaliTest[2403:6183259] multipeer session: stop timer
,2016-01-21 16:45:00.680 ThaliTest[2403:6183259] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/0171BE5E-EE77-4F81-9459-25554D0916CE/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-21 16:45:05.218 ThaliTest[2403:6183259] jxcore: startBroadcasting
,2016-01-21 16:45:05.221 ThaliTest[2403:6183259] server: starting TQJolC_lnHeSmLHZWAv11A.VOttFA==
,2016-01-21 16:45:05.225 ThaliTest[2403:6183259] multipeer session: start timer: 0x1b01bba0
,2016-01-21 16:45:05.227 ThaliTest[2403:6183259] THEMultipeerSession initialized peer TQJolC_lnHeSmLHZWAv11A
2016-01-21 16:45:05.228 ThaliTest[2403:6183259] jxcore: startBroadcasting: success
2016-01-21 16:45:05.228 ThaliTest[2403:6182978] client: found peer: mxHO5WH3PpjIB3-1m_VHKw.faqMqg==
ok 110 getDeviceIdentity should not return an error

ok 111 deviceName should not be null

,2016-01-21 16:45:10.729 ThaliTest[2403:6182978] multipeer session: reset timer
2016-01-21 16:45:10.729 ThaliTest[2403:6182978] multipeer session: stop timer
2016-01-21 16:45:10.729 ThaliTest[2403:6182978] multipeer session: start timer: 0x1b01bba0
2016-01-21 16:45:10.730 ThaliTest[2403:6182978] server session: connect
2016-01-21 16:45:10.730 ThaliTest[2403:6182978] server session: stateChange:0->1 mxHO5WH3PpjIB3-1m_VHKw
,2016-01-21 16:45:10.735 ThaliTest[2403:6182978] server: accepting invitation mxHO5WH3PpjIB3-1m_VHKw
,2016-01-21 16:45:10.782 ThaliTest[2403:6183259] jxcore: connect mxHO5WH3PpjIB3-1m_VHKw.faqMqg==
,2016-01-21 16:45:10.787 ThaliTest[2403:6183259] client session: connect
,2016-01-21 16:45:10.788 ThaliTest[2403:6183259] client session: stateChange:0->1 mxHO5WH3PpjIB3-1m_VHKw.faqMqg==
,ok 112 Should be able to put doc without error
,
,ok 113 1st change of local doc should contain local id

,2016-01-21 16:45:13.447 ThaliTest[2403:6185064] server session: connected
2016-01-21 16:45:13.448 ThaliTest[2403:6185064] server session: stateChange:1->2 mxHO5WH3PpjIB3-1m_VHKw
,2016-01-21 16:45:13.450 ThaliTest[2403:6182978] server relay: connected (to port: 62990)
server bridge: new client socket

,2016-01-21 16:45:13.626 ThaliTest[2403:6185064] client session: connected
2016-01-21 16:45:13.626 ThaliTest[2403:6185064] client session: stateChange:1->2 mxHO5WH3PpjIB3-1m_VHKw.faqMqg==
2016-01-21 16:45:13.628 ThaliTest[2403:6185064] client session: fir,eConnectCallback: mxHO5WH3PpjIB3-1m_VHKw.faqMqg==
2016-01-21 16:45:13.628 ThaliTest[2403:6185064] jxcore: connect: success
,2016-01-21 16:45:13.631 ThaliTest[2403:6182978] client: relay established
2016-01-21 16:45:13.632 ThaliTest[2403:6182978] client: new accepted socket: 0x19638970
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

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket
,
,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

client bridge: new client socket

,ok 114 1st change of remote doc should contain remote id

,ok 115 Can update remote doc without error
,
,null

,{ ok: true,
  id: 'd516be8b-0544-4adb-86dd-aca83ccf87d9',
  rev: '2-0526a1ef18acaebf16d2b5005f9bb024' }

,ok 116 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket
,
,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket
,
,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,ok 117 Local changes occur in strict order

,ok 118 2nd change of local doc should contain remote id
,
,# setup

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,Now in TRM stop

State of this._isStarted: true

,About to call stopBroadcasting

,2016-01-21 16:45:30.038 ThaliTest[2403:6183259] jxcore: stopBroadcasting
,2016-01-21 16:45:30.039 ThaliTest[2403:6183259] THEMultipeerSession stopping peer
,2016-01-21 16:45:30.040 ThaliTest[2403:6183259] multipeer session: stop timer
,2016-01-21 16:45:30.040 ThaliTest[2403:6183259] client session: disconnect
,2016-01-21 16:45:30.042 ThaliTest[2403:6183259] client session: stateChange:2->0 mxHO5WH3PpjIB3-1m_VHKw.faqMqg==
,2016-01-21 16:45:30.055 ThaliTest[2403:6183259] server session: disconnect
,2016-01-21 16:45:30.057 ThaliTest[2403:6183259] server session: stateChange:2->0 mxHO5WH3PpjIB3-1m_VHKw
,2016-01-21 16:45:30.068 ThaliTest[2403:6183259] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,# #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

,mux server bridge listener closed

,client bridge: socket closed

server bridge: socket closed

,# teardown

,ok 119 host address should match

ok 120 port should match

,# setup

,# #startUpdateAdvertisingAndListening should use different USN after every invocation

,# teardown

,ok 121 USN should have changed from the first one

# setup

,# verify that Thali-specific messages are filtered correctly

,# teardown

,ok 122 irrelevant messages should be ignored

ok 123 relevant messages should not be ignored

ok 124 messages from this device should be ignored

,# setup

,# #start should fail if called twice in a row

,# teardown

,ok 125 specific error should be received

# setup

,# #startUpdateAdvertisingAndListening should fail invalid router has been passed

,# teardown

,ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string

ok 126 specific error should be received

# setup

,# #startUpdateAdvertisingAndListening should start hosting given router object

,# teardown

,ok 127 server should respond with code 200

,# setup

,# #stop can be called multiple times in a row

,# teardown

,ok 128 should be in stopped state

ok 129 should still be in stopped state

Tests Complete

,Total: 0	Passed: 0	Failed: 0

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
