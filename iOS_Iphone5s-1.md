#### Test 5615109370bee58_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5615109370bee58/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/95760018-29BD-4883-A2D4-2ED84929EFCD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/95760018-29BD-4883-A2D4-2ED84929EFCD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5615109370bee58/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5615109370bee58/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/34A7DEBB-073B-4A50-92CF-EB3BDDF1612A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57916"
,(lldb)     command script import "/tmp/95760018-29BD-4883-A2D4-2ED84929EFCD/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-18 15:16:53.581 ThaliTest[2188:5392357] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/63F6CE40-2A81-45D0-86FA-D09135BB61C3/Library/Cookies/Cookies.binarycookies
,2016-01-18 15:16:53.885 ThaliTest[2188:5392357] Apache Cordova native platform version 3.9.2 is starting.
2016-01-18 15:16:53.886 ThaliTest[2188:5392357] Multi-tasking -> Device: YES, App: YES
,2016-01-18 15:16:53.894 ThaliTest[2188:5392357] Unlimited access to network resources
,2016-01-18 15:16:53.904 ThaliTest[2188:5392357] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-18 15:16:58.521 ThaliTest[2188:5392357] Resetting plugins due to page load.
,2016-01-18 15:16:59.999 ThaliTest[2188:5392357] Finished load of: file:///var/mobile/Containers/Bundle/Application/34A7DEBB-073B-4A50-92CF-EB3BDDF1612A/ThaliTest.app/www/index.html
,2016-01-18 15:17:00.217 ThaliTest[2188:5392357] JXcore Cordova plugin initializing
2016-01-18 15:17:00.218 ThaliTest[2188:5392527] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34A7DEBB-073B-4A50-92CF-EB3BDDF1612A/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34A7DEBB-073B-4A50-92CF-EB3BDDF1612A/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34A7DEBB-073B-4A50-92CF-EB3BDDF1612A/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34A7DEBB-073B-4A50-92CF-EB3BDDF1612A/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34A7DEBB-073B-4A50-92CF-EB3BDDF1612A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34A7DEBB-073B-4A50-92CF-EB3BDDF1612A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34A7DEBB-073B-4A50-92CF-EB3BDDF1612A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
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
,2016-01-18 15:20:01.652 ThaliTest[2188:5392527] jxcore: startBroadcasting
,2016-01-18 15:20:01.660 ThaliTest[2188:5392527] server: starting 1453126801652.2188.GPbDQQ==
,2016-01-18 15:20:01.660 ThaliTest[2188:5392527] multipeer session: start timer: 0x1856d400
,2016-01-18 15:20:01.661 ThaliTest[2188:5392527] THEMultipeerSession initialized peer 1453126801652.2188
2016-01-18 15:20:01.661 ThaliTest[2188:5392527] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
,2016-01-18 15:20:01.662 ThaliTest[2188:5392527] jxcore: stopBroadcasting
2016-01-18 15:20:01.663 ThaliTest[2188:5392527] THEMultipeerSession stopping peer
2016-01-18 15:20:01.663 ThaliTest[2188:5392527] multipeer session: stop timer
2016-01-18 15:20:01.663 ThaliTest[2188:5392527] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-18 15:20:01.665 ThaliTest[2188:5392527] jxcore: startBroadcasting
,2016-01-18 15:20:01.669 ThaliTest[2188:5392527] server: starting 1453126801665.2188.BgRO5Q==
2016-01-18 15:20:01.672 ThaliTest[2188:5392527] multipeer session: start timer: 0x1844ac60
,2016-01-18 15:20:01.673 ThaliTest[2188:5392527] THEMultipeerSession initialized peer 1453126801665.2188
2016-01-18 15:20:01.673 ThaliTest[2188:5392527] jxcore: startBroadcasting: success
,ok 47 Should be able to call startBroadcasting without error
2016-01-18 15:20:01.675 ThaliTest[2188:5392527] jxcore: stopBroadcasting
,2016-01-18 15:20:01.676 ThaliTest[2188:5392527] THEMultipeerSession stopping peer
2016-01-18 15:20:01.677 ThaliTest[2188:5392527] multipeer session: stop timer
,2016-01-18 15:20:01.679 ThaliTest[2188:5392527] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
,2016-01-18 15:20:01.680 ThaliTest[2188:5392527] jxcore: startBroadcasting
,2016-01-18 15:20:01.684 ThaliTest[2188:5392527] server: starting 1453126801680.2188.w7efXg==
2016-01-18 15:20:01.685 ThaliTest[2188:5392527] multipeer session: start timer: 0x1843f660
,2016-01-18 15:20:01.685 ThaliTest[2188:5392527] THEMultipeerSession initialized peer 1453126801680.2188
2016-01-18 15:20:01.687 ThaliTest[2188:5392527] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2016-01-18 15:20:01.689 ThaliTest[2188:5392527] jxcore: stopBroadcasting
2016-01-18 15:20:01.689 ThaliTest[2188:5392527] THEMultipeerSession stopping peer
2016-01-18 15:20:01.689 ThaliTest[2188:5392527] multipeer session: stop timer
2016-01-18 15:20:01.,690 ThaliTest[2188:5392527] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error
2016-01-18 15:20:01.691 ThaliTest[2188:5392527] jxcore: startBroadcasting
2016-01-18 15:20:01.695 ThaliTest[2188:5392527] server: starting 1453126801691.2188.fIUwww==
2016-01-18 15:20:01.695 ThaliTest[2188:5392527] multipeer session: start timer: 0x1844f110
2016-01-18 15:20:01.695 ThaliTest[2188:5392527] THEMultipeerSession initialized peer 1453126801691.2188
2016-01-18 15:20:01.69,5 ThaliTest[2188:5392527] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
,2016-01-18 15:20:01.697 ThaliTest[2188:5392527] jxcore: stopBroadcasting
2016-01-18 15:20:01.697 ThaliTest[2188:5392527] THEMultipeerSession stopping peer
2016-01-18 15:20:01.698 ThaliTest[2188:5392527] multipeer session: stop timer
,2016-01-18 15:20:01.699 ThaliTest[2188:5392527] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
,2016-01-18 15:20:01.700 ThaliTest[2188:5392527] jxcore: startBroadcasting
,2016-01-18 15:20:01.705 ThaliTest[2188:5392527] server: starting 1453126801699.2188.qztA+Q==
,2016-01-18 15:20:01.708 ThaliTest[2188:5392527] multipeer session: start timer: 0x18441c10
,2016-01-18 15:20:01.709 ThaliTest[2188:5392527] THEMultipeerSession initialized peer 1453126801699.2188
,2016-01-18 15:20:01.711 ThaliTest[2188:5392527] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2016-01-18 15:20:01.714 ThaliTest[2188:5392527] jxcore: stopBroadcasting
,2016-01-18 15:20:01.715 ThaliTest[2188:5392527] THEMultipeerSession stopping peer
,2016-01-18 15:20:01.715 ThaliTest[2188:5392527] multipeer session: stop timer
,2016-01-18 15:20:01.717 ThaliTest[2188:5392527] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-18 15:20:01.720 ThaliTest[2188:5392527] jxcore: startBroadcasting
,2016-01-18 15:20:01.729 ThaliTest[2188:5392527] server: starting 1453126801719.2188.89jmsQ==
,2016-01-18 15:20:01.732 ThaliTest[2188:5392527] multipeer session: start timer: 0x18574500
,2016-01-18 15:20:01.734 ThaliTest[2188:5392527] THEMultipeerSession initialized peer 1453126801719.2188
,2016-01-18 15:20:01.737 ThaliTest[2188:5392527] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-18 15:20:01.740 ThaliTest[2188:5392527] jxcore: stopBroadcasting
,2016-01-18 15:20:01.740 ThaliTest[2188:5392527] THEMultipeerSession stopping peer
,2016-01-18 15:20:01.741 ThaliTest[2188:5392527] multipeer session: stop timer
,2016-01-18 15:20:01.743 ThaliTest[2188:5392527] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-18 15:20:01.746 ThaliTest[2188:5392527] jxcore: startBroadcasting
,2016-01-18 15:20:01.748 ThaliTest[2188:5392527] server: starting 1453126801745.2188.gZVulQ==
,2016-01-18 15:20:01.749 ThaliTest[2188:5392527] multipeer session: start timer: 0x185774b0
,2016-01-18 15:20:01.753 ThaliTest[2188:5392527] THEMultipeerSession initialized peer 1453126801745.2188
,2016-01-18 15:20:01.755 ThaliTest[2188:5392527] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-18 15:20:01.758 ThaliTest[2188:5392527] jxcore: stopBroadcasting
,2016-01-18 15:20:01.758 ThaliTest[2188:5392527] THEMultipeerSession stopping peer
,2016-01-18 15:20:01.759 ThaliTest[2188:5392527] multipeer session: stop timer
,2016-01-18 15:20:01.762 ThaliTest[2188:5392527] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-18 15:20:01.764 ThaliTest[2188:5392527] jxcore: startBroadcasting
,2016-01-18 15:20:01.767 ThaliTest[2188:5392527] server: starting 1453126801764.2188.eHlXSw==
,2016-01-18 15:20:01.768 ThaliTest[2188:5392527] multipeer session: start timer: 0x1844bc50
,2016-01-18 15:20:01.771 ThaliTest[2188:5392527] THEMultipeerSession initialized peer 1453126801764.2188
,2016-01-18 15:20:01.773 ThaliTest[2188:5392527] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-18 15:20:01.777 ThaliTest[2188:5392527] jxcore: stopBroadcasting
,2016-01-18 15:20:01.777 ThaliTest[2188:5392527] THEMultipeerSession stopping peer
,2016-01-18 15:20:01.778 ThaliTest[2188:5392527] multipeer session: stop timer
,2016-01-18 15:20:01.779 ThaliTest[2188:5392527] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-18 15:20:01.784 ThaliTest[2188:5392527] jxcore: startBroadcasting
,2016-01-18 15:20:01.786 ThaliTest[2188:5392527] server: starting 1453126801783.2188.UBUdGw==
,2016-01-18 15:20:01.787 ThaliTest[2188:5392527] multipeer session: start timer: 0x18577e70
,2016-01-18 15:20:01.792 ThaliTest[2188:5392527] THEMultipeerSession initialized peer 1453126801783.2188
,2016-01-18 15:20:01.794 ThaliTest[2188:5392527] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-18 15:20:01.796 ThaliTest[2188:5392527] jxcore: stopBroadcasting
,2016-01-18 15:20:01.796 ThaliTest[2188:5392527] THEMultipeerSession stopping peer
,2016-01-18 15:20:01.797 ThaliTest[2188:5392527] multipeer session: stop timer
,2016-01-18 15:20:01.798 ThaliTest[2188:5392527] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-18 15:20:01.802 ThaliTest[2188:5392527] jxcore: startBroadcasting
,2016-01-18 15:20:01.805 ThaliTest[2188:5392527] server: starting 1453126801802.2188.OBKfiQ==
,2016-01-18 15:20:01.807 ThaliTest[2188:5392527] multipeer session: start timer: 0x18450f20
,2016-01-18 15:20:01.808 ThaliTest[2188:5392527] THEMultipeerSession initialized peer 1453126801802.2188
,2016-01-18 15:20:01.812 ThaliTest[2188:5392527] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-18 15:20:01.814 ThaliTest[2188:5392527] jxcore: stopBroadcasting
,2016-01-18 15:20:01.814 ThaliTest[2188:5392527] THEMultipeerSession stopping peer
,2016-01-18 15:20:01.815 ThaliTest[2188:5392527] multipeer session: stop timer
,2016-01-18 15:20:01.816 ThaliTest[2188:5392527] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-18 15:20:02.015 ThaliTest[2188:5392527] jxcore: startBroadcasting
,2016-01-18 15:20:02.017 ThaliTest[2188:5392527] server: starting 1453126802015.2188.14cZfA==
,2016-01-18 15:20:02.021 ThaliTest[2188:5392527] multipeer session: start timer: 0x18457b80
,2016-01-18 15:20:02.024 ThaliTest[2188:5392527] THEMultipeerSession initialized peer 1453126802015.2188
,2016-01-18 15:20:02.025 ThaliTest[2188:5392527] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
,2016-01-18 15:20:02.027 ThaliTest[2188:5392527] jxcore: startBroadcasting
,2016-01-18 15:20:02.027 ThaliTest[2188:5392527] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
,2016-01-18 15:20:02.029 ThaliTest[2188:5392527] jxcore: stopBroadcasting
,2016-01-18 15:20:02.030 ThaliTest[2188:5392527] THEMultipeerSession stopping peer
,2016-01-18 15:20:02.030 ThaliTest[2188:5392527] multipeer session: stop timer
,2016-01-18 15:20:02.033 ThaliTest[2188:5392527] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-18 15:20:05.041 ThaliTest[2188:5392527] jxcore: startBroadcasting
,2016-01-18 15:20:05.044 ThaliTest[2188:5392527] server: starting 1453126805041.2188.xnTfLA==
2016-01-18 15:20:05.044 ThaliTest[2188:5392527] multipeer session: start timer: 0x1857b640
2016-01-18 15:20:05.044 ThaliTest[2188:5392527] THEMultipeerSession in,itialized peer 1453126805041.2188
2016-01-18 15:20:05.044 ThaliTest[2188:5392527] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-18 15:20:05.045 ThaliTest[2188:5392527] jxcore: connect foobar
201,6-01-18 15:20:05.046 ThaliTest[2188:5392527] client: unknown peer foobar
,2016-01-18 15:20:05.046 ThaliTest[2188:5392527] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
2016-01-18 15:20:05.052 ThaliTest[2188:5392527] jxcore: stopBroadcasting
2016-01-18 15:20:05.053 ThaliTest[2188:5392527] THEMultipeerSession stopping peer
2016-01-18 15:20:05.053 ThaliTest[2188:5392527] multipeer session: stop timer
,2016-01-18 15:20:05.053 ThaliTest[2188:5392527] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-18 15:20:05.246 ThaliTest[2188:5392527] jxcore: startBroadcasting
,2016-01-18 15:20:05.247 ThaliTest[2188:5392527] server: starting 1453126805245.2188.2XuzgQ==
2016-01-18 15:20:05.248 ThaliTest[2188:5392527] multipeer session: start timer: 0x185fa3f0
2016-01-18 15:20:05.248 ThaliTest[2188:5392527] THEMultipeerSession in,itialized peer 1453126805245.2188
2016-01-18 15:20:05.248 ThaliTest[2188:5392527] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-18 15:20:05.249 ThaliTest[2188:5392527] jxcore: disconnect
2016-01-18 15:20:05.250 ThaliTest[2188:5392527] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 
2016-01-18 15:20:05.251 ThaliTest[2188:5392527] jxcore: stopBroadcasting
2016-01-18 15:20:05.260 ThaliTest[2188:5392527] THEMultipeerSession stopping peer
2016-01-18 15:20:05.260 ThaliTest[2188:5392527] multipeer session: stop timer
2016-01-18 15:20:05.261 ThaliTest[2188:5392527] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-18 15:20:05.702 ThaliTest[2188:5392527] jxcore: startBroadcasting
,2016-01-18 15:20:05.704 ThaliTest[2188:5392527] server: starting 1453126805701.2188.JqByZA==
2016-01-18 15:20:05.704 ThaliTest[2188:5392527] multipeer session: start timer: 0x185f1b10
2016-01-18 15:20:05.704 ThaliTest[2188:5392527] THEMultipeerSession in,itialized peer 1453126805701.2188
2016-01-18 15:20:05.705 ThaliTest[2188:5392527] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-18 15:20:06.958 ThaliTest[2188:5392357] client: found peer: 1453126807908.2276.hk1ulw==
,2016-01-18 15:20:06.960 ThaliTest[2188:5392527] jxcore: connect 1453126807908.2276.hk1ulw==
2016-01-18 15:20:06.960 ThaliTest[2188:5392527] client session: connect
2016-01-18 15:20:06.960 ThaliTest[2188:5392527] client session: stateChange:0->1 1453126807908.2276.hk1ulw==
,2016-01-18 15:20:07.090 ThaliTest[2188:5392357] multipeer session: reset timer
2016-01-18 15:20:07.090 ThaliTest[2188:5392357] multipeer session: stop timer
2016-01-18 15:20:07.090 ThaliTest[2188:5392357] multipeer session: start timer: 0x185f1b10
2016-,01-18 15:20:07.091 ThaliTest[2188:5392357] server session: connect
2016-01-18 15:20:07.091 ThaliTest[2188:5392357] server session: stateChange:0->1 1453126807908.2276
,2016-01-18 15:20:07.096 ThaliTest[2188:5392357] server: accepting invitation 1453126807908.2276
,2016-01-18 15:20:11.209 ThaliTest[2188:5393048] server session: connected
2016-01-18 15:20:11.209 ThaliTest[2188:5393048] server session: stateChange:1->2 1453126807908.2276
2016-01-18 15:20:11.211 ThaliTest[2188:5393047] client session: connected
2016-,01-18 15:20:11.211 ThaliTest[2188:5393047] client session: stateChange:1->2 1453126807908.2276.hk1ulw==
,2016-01-18 15:20:11.229 ThaliTest[2188:5393048] client session: fireConnectCallback: 1453126807908.2276.hk1ulw==
2016-01-18 15:20:11.229 ThaliTest[2188:5393048] jxcore: connect: success
ok 75 Should be able to connect without error
ok 76 Port should be within range
,2016-01-18 15:20:11.231 ThaliTest[2188:5392527] jxcore: disconnect
2016-01-18 15:20:11.234 ThaliTest[2188:5392527] client session: disconnectFromPeer: 1453126807908.2276.hk1ulw==
2016-01-18 15:20:11.234 ThaliTest[2188:5392527] client session: disconnect
2016-01-18 15:20:11.234 ThaliTest[2188:5392527] client session: stateChange:2->0 1453126807908.2276.hk1ulw==
,2016-01-18 15:20:11.242 ThaliTest[2188:5392357] server relay: socket disconnected
2016-01-18 15:20:11.245 ThaliTest[2188:5392357] server relay: 0x185f05e0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-18 15:20:11.247 ThaliTest[2188:5392527] jxcore: disconnect: success
,ok 77 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-18 15:20:11.604 ThaliTest[2188:5392527] jxcore: stopBroadcasting
2016-01-18 15:20:11.604 ThaliTest[2188:5392527] THEMultipeerSession stopping peer
2016-01-18 15:20:11.605 ThaliTest[2188:5392527] multipeer session: stop timer
2016-01-18 15:20:11.605 ThaliTest[2188:5392527] server session: disconnect
2016-01-18 15:20:11.605 ThaliTest[2188:5392527] server session: stateChange:2->0 1453126807908.2276
,2016-01-18 15:20:11.613 ThaliTest[2188:5392527] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-18 15:20:13.402 ThaliTest[2188:5392527] jxcore: startBroadcasting
,2016-01-18 15:20:13.404 ThaliTest[2188:5392527] server: starting 1453126813402.2188.j6gUNw==
2016-01-18 15:20:13.405 ThaliTest[2188:5392527] multipeer session: start timer: 0x185d8ff0
2016-01-18 15:20:13.405 ThaliTest[2188:5392527] THEMultipeerSession initialized peer 1453126813402.2188
2016-01-18 15:20:13.405 ThaliTest[2188:5392527] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-18 15:20:14.817 ThaliTest[2188:5392357] client: found peer: 1453126815788.2276.TbYE7g==
2016-01-18 15:20:14.818 ThaliTest[2188:5392527] jxcore: connect 1453126815788.2276.TbYE7g==
2016-01-18 15:20:14.818 ThaliTest[2188:5392527] client session: connect
2016-01-18 15:20:14.818 ThaliTest[2188:5392527] client session: stateChange:0->1 1453126815788.2276.TbYE7g==
,2016-01-18 15:20:14.897 ThaliTest[2188:5392357] multipeer session: reset timer
2016-01-18 15:20:14.897 ThaliTest[2188:5392357] multipeer session: stop timer
2016-01-18 15:20:14.897 ThaliTest[2188:5392357] multipeer session: start timer: 0x185d8ff0
2016-01-18 15:20:14.897 ThaliTest[2188:5392357] server session: connect
,2016-01-18 15:20:14.897 ThaliTest[2188:5392357] server session: stateChange:0->1 1453126815788.2276
2016-01-18 15:20:14.905 ThaliTest[2188:5392357] server: accepting invitation 1453126815788.2276
,2016-01-18 15:20:19.013 ThaliTest[2188:5393063] server session: connected
2016-01-18 15:20:19.013 ThaliTest[2188:5393063] server session: stateChange:1->2 1453126815788.2276
,2016-01-18 15:20:19.016 ThaliTest[2188:5392357] server relay: socket disconnected
2016-01-18 15:20:19.017 ThaliTest[2188:5392357] server relay: 0x18476890 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-18 15:20:19.043 ThaliTest[2188:5393047] server session: not connected 1453126815788.2276
,2016-01-18 15:20:19.210 ThaliTest[2188:5393047] client session: connected
2016-01-18 15:20:19.210 ThaliTest[2188:5393047] client session: stateChange:1->2 1453126815788.2276.TbYE7g==
2016-01-18 15:20:19.212 ThaliTest[2188:5393047] client session: fireConnectCallback: 1453126815788.2276.TbYE7g==
2016-01-18 15:20:19.212 ThaliTest[2188:5393047] jxcore: connect: success
ok 79 Should be able to connect without error
ok 80 Port should be within range
,2016-01-18 15:20:19.214 ThaliTest[2188:5392527] jxcore: connect 1453126815788.2276.TbYE7g==
2016-01-18 15:20:19.214 ThaliTest[2188:5392527] client: already connect(ing/ed) to 1453126815788.2276.TbYE7g==
2016-01-18 15:20:19.214 ThaliTest[2188:5392527] jxc,ore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect
2016-01-18 15:20:19.216 ThaliTest[2188:5392527] jxcore: disconnect
2016-01-18 15:20:19.216 ThaliTest[2188:5392527] client session: disconnectFromPeer: 1453126815788.2276.TbYE7g==
2016-01-18 15:20:19.216 ThaliTest[2188:5392527] client session: disconnect
2016-01-18 15:20:19.216 ThaliTest[2188:5392527] client session: stateChange:2->0 1453126815788.2276.TbYE7g==
,2016-01-18 15:20:19.221 ThaliTest[2188:5392527] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-18 15:20:19.867 ThaliTest[2188:5392527] jxcore: stopBroadcasting
2016-01-18 15:20:19.868 ThaliTest[2188:5392527] THEMultipeerSession stopping peer
2016-01-18 15:20:19.868 ThaliTest[2188:5392527] multipeer session: stop timer
2016-01-18 15:20:19.868 ThaliTest[2188:5392527] server session: disconnect
2016-01-18 15:20:19.868 ThaliTest[2188:5392527] server session: stateChange:2->0 1453126815788.2276
,2016-01-18 15:20:20.821 ThaliTest[2188:5392527] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-18 15:20:21.387 ThaliTest[2188:5392527] jxcore: startBroadcasting
,2016-01-18 15:20:21.389 ThaliTest[2188:5392527] server: starting 1453126821387.2188.6r0KPA==
2016-01-18 15:20:21.390 ThaliTest[2188:5392527] multipeer session: start timer: 0x18470160
2016-01-18 15:20:21.390 ThaliTest[2188:5392527] THEMultipeerSession initialized peer 1453126821387.2188
2016-01-18 15:20:21.390 ThaliTest[2188:5392527] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-18 15:20:22.684 ThaliTest[2188:5392357] multipeer session: reset timer
2016-01-18 15:20:22.684 ThaliTest[2188:5392357] multipeer session: stop timer
2016-01-18 15:20:22.685 ThaliTest[2188:5392357] multipeer session: start timer: 0x18470160
,2016-01-18 15:20:22.685 ThaliTest[2188:5392357] server session: connect
2016-01-18 15:20:22.686 ThaliTest[2188:5392357] server session: stateChange:0->1 1453126823986.2276
,2016-01-18 15:20:22.690 ThaliTest[2188:5392357] server: accepting invitation 1453126823986.2276
,2016-01-18 15:20:22.776 ThaliTest[2188:5392357] client: found peer: 1453126823986.2276.WdZ+jg==
2016-01-18 15:20:22.777 ThaliTest[2188:5392527] jxcore: connect 1453126823986.2276.WdZ+jg==
2016-01-18 15:20:22.777 ThaliTest[2188:5392527] client session: co,nnect
2016-01-18 15:20:22.778 ThaliTest[2188:5392527] client session: stateChange:0->1 1453126823986.2276.WdZ+jg==
,2016-01-18 15:20:26.622 ThaliTest[2188:5393047] server session: connected
2016-01-18 15:20:26.622 ThaliTest[2188:5393047] server session: stateChange:1->2 1453126823986.2276
,2016-01-18 15:20:26.647 ThaliTest[2188:5392357] server relay: socket disconnected
2016-01-18 15:20:26.647 ThaliTest[2188:5392357] server relay: 0x1844da90 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-18 15:20:26.651 ThaliTest[2188:5393047] server session: not connected 1453126823986.2276
,2016-01-18 15:20:26.950 ThaliTest[2188:5393047] client session: connected
2016-01-18 15:20:26.951 ThaliTest[2188:5393047] client session: stateChange:1->2 1453126823986.2276.WdZ+jg==
,2016-01-18 15:20:26.983 ThaliTest[2188:5393063] client session: fireConnectCallback: 1453126823986.2276.WdZ+jg==
2016-01-18 15:20:26.983 ThaliTest[2188:5393063] jxcore: connect: success
,ok 84 Should be able to connect without error
,ok 85 Port should be within range
,2016-01-18 15:20:26.986 ThaliTest[2188:5392527] jxcore: disconnect
2016-01-18 15:20:26.986 ThaliTest[2188:5392527] client session: disconnectFromPeer: 1453126823986.2276.WdZ+jg==
2016-01-18 15:20:26.986 ThaliTest[2188:5392527] client session: disconnect
2016-01-18 15:20:26.986 ThaliTest[2188:5392527] client session: stateChange:2->0 1453126823986.2276.WdZ+jg==
,2016-01-18 15:20:26.991 ThaliTest[2188:5392527] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
2016-01-18 15:20:26.992 ThaliTest[2188:5392527] jxcore: disconnect
2016-01-18 15:20:26.992 ThaliTest[2188:5392527] jxcore: disconnect: fail
ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-18 15:20:27.203 ThaliTest[2188:5392527] jxcore: stopBroadcasting
2016-01-18 15:20:27.204 ThaliTest[2188:5392527] THEMultipeerSession stopping peer
2016-01-18 15:20:27.204 ThaliTest[2188:5392527] multipeer session: stop timer
2016-01-18 15:20:27.,204 ThaliTest[2188:5392527] server session: disconnect
2016-01-18 15:20:27.204 ThaliTest[2188:5392527] server session: stateChange:2->0 1453126823986.2276
,2016-01-18 15:20:27.208 ThaliTest[2188:5392527] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,# ThaliEmitter can connect and send data
,# teardown
,echo server started on port: 61542
,2016-01-18 15:20:27.901 ThaliTest[2188:5392527] jxcore: startBroadcasting
,2016-01-18 15:20:27.905 ThaliTest[2188:5392527] server: starting 1453126827901.2188.Ro391g==
2016-01-18 15:20:27.905 ThaliTest[2188:5392527] multipeer session: start timer: 0x18473f20
2016-01-18 15:20:27.905 ThaliTest[2188:5392527] THEMultipeerSession initialized peer 1453126827901.2188
2016-01-18 15:20:27.905 ThaliTest[2188:5392527] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
,2016-01-18 15:20:28.905 ThaliTest[2188:5392357] client: found peer: 1453126829951.2276.pN9r8g==
2016-01-18 15:20:28.906 ThaliTest[2188:5392527] jxcore: connect 1453126829951.2276.pN9r8g==
,2016-01-18 15:20:28.906 ThaliTest[2188:5392527] client session: connect
,2016-01-18 15:20:28.907 ThaliTest[2188:5392527] client session: stateChange:0->1 1453126829951.2276.pN9r8g==
,2016-01-18 15:20:29.038 ThaliTest[2188:5392357] multipeer session: reset timer
2016-01-18 15:20:29.038 ThaliTest[2188:5392357] multipeer session: stop timer
2016-01-18 15:20:29.038 ThaliTest[2188:5392357] multipeer session: start timer: 0x18473f20
2016-,01-18 15:20:29.038 ThaliTest[2188:5392357] server session: connect
2016-01-18 15:20:29.038 ThaliTest[2188:5392357] server session: stateChange:0->1 1453126829951.2276
2016-01-18 15:20:29.042 ThaliTest[2188:5392357] server: accepting invitation 1453126829951.2276
,2016-01-18 15:20:33.171 ThaliTest[2188:5393047] server session: connected
2016-01-18 15:20:33.171 ThaliTest[2188:5393047] server session: stateChange:1->2 1453126829951.2276
,2016-01-18 15:20:33.176 ThaliTest[2188:5393047] client session: connected
2016-01-18 15:20:33.176 ThaliTest[2188:5393047] client session: stateChange:1->2 1453126829951.2276.pN9r8g==
,2016-01-18 15:20:33.179 ThaliTest[2188:5392357] server relay: connected (to port: 61542)
2016-01-18 15:20:33.181 ThaliTest[2188:5393047] client session: fireConnectCallback: 1453126829951.2276.pN9r8g==
2016-01-18 15:20:33.182 ThaliTest[2188:5393047] jxcore: connect: success
ok 89 Should be able to connect without error
ok 90 Port should be within range
,2016-01-18 15:20:33.188 ThaliTest[2188:5392357] client: relay established
,2016-01-18 15:20:33.188 ThaliTest[2188:5392357] client: new accepted socket: 0x1859d520
,data in 3285
,data in 5475
,data in 14235
,data in 32779
,data in 42350
,data in 73294
,data in 74389
,data in 75555
,data in 81030
,data in 91980
,data in 94170
,data in 111690
,data in 131072
,ok 91 the test messages should be equal
,2016-01-18 15:20:34.172 ThaliTest[2188:5392527] jxcore: disconnect
2016-01-18 15:20:34.172 ThaliTest[2188:5392527] client session: disconnectFromPeer: 1453126829951.2276.pN9r8g==
2016-01-18 15:20:34.172 ThaliTest[2188:5392527] client session: disconnect,
2016-01-18 15:20:34.172 ThaliTest[2188:5392527] client session: stateChange:2->0 1453126829951.2276.pN9r8g==
,2016-01-18 15:20:34.178 ThaliTest[2188:5392527] jxcore: disconnect: success
ok 92 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
# setup
,2016-01-18 15:20:34.485 ThaliTest[2188:5393047] server session: not connected 1453126829951.2276
,calling stopBroadcasting
,2016-01-18 15:20:34.748 ThaliTest[2188:5392527] jxcore: stopBroadcasting
2016-01-18 15:20:34.748 ThaliTest[2188:5392527] THEMultipeerSession stopping peer
2016-01-18 15:20:34.748 ThaliTest[2188:5392527] multipeer session: stop timer
2016-01-18 15:20:34.749 ThaliTest[2188:5392527] server session: disconnect
2016-01-18 15:20:34.749 ThaliTest[2188:5392527] server session: stateChange:2->0 1453126829951.2276
,2016-01-18 15:20:34.845 ThaliTest[2188:5392527] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,echo server started on port: 61548
2016-01-18 15:20:35.661 ThaliTest[2188:5392527] jxcore: startBroadcasting
,2016-01-18 15:20:35.663 ThaliTest[2188:5392527] server: starting 1453126835660.2188.0MBBkA==
2016-01-18 15:20:35.664 ThaliTest[2188:5392527] multipeer session: start timer: 0x18470500
2016-01-18 15:20:35.664 ThaliTest[2188:5392527] THEMultipeerSession initialized peer 1453126835660.2188
2016-01-18 15:20:35.664 ThaliTest[2188:5392527] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error
,2016-01-18 15:20:35.868 ThaliTest[2188:5392357] client: found peer: 1453126829951.2276.pN9r8g==
[{"peerIdentifier":"1453126829951.2276.pN9r8g==","peerName":"(null)","peerAvailable":true}]
2016-01-18 15:20:35.870 ThaliTest[2188:5392527] jxcore: connect 14,53126829951.2276.pN9r8g==
2016-01-18 15:20:35.870 ThaliTest[2188:5392527] client session: connect
2016-01-18 15:20:35.870 ThaliTest[2188:5392527] client session: stateChange:0->1 1453126829951.2276.pN9r8g==
,2016-01-18 15:20:36.840 ThaliTest[2188:5392357] multipeer session: reset timer
2016-01-18 15:20:36.840 ThaliTest[2188:5392357] multipeer session: stop timer
2016-01-18 15:20:36.840 ThaliTest[2188:5392357] multipeer session: start timer: 0x18470500
2016-01-18 15:20:36.840 ThaliTest[2188:5392357] server session: connect
2016-01-18 15:20:36.840 ThaliTest[2188:5392357] server session: stateChange:0->1 1453126837889.2276
,2016-01-18 15:20:36.845 ThaliTest[2188:5392357] server: accepting invitation 1453126837889.2276
,2016-01-18 15:20:36.851 ThaliTest[2188:5392357] client: found peer: 1453126837889.2276.dyZ4xw==
[{"peerIdentifier":"1453126837889.2276.dyZ4xw==","peerName":"(null)","peerAvailable":true}]
2016-01-18 15:20:36.852 ThaliTest[2188:5392527] jxcore: connect 1453126837889.2276.dyZ4xw==
2016-01-18 15:20:36.852 ThaliTest[2188:5392527] client session: connect
2016-01-18 15:20:36.852 ThaliTest[2188:5392527] client session: stateChange:0->1 1453126837889.2276.dyZ4xw==
,2016-01-18 15:20:37.852 ThaliTest[2188:5392357] client: lost peer: 1453126829951.2276.pN9r8g==
2016-01-18 15:20:37.853 ThaliTest[2188:5392357] client session: onPeerLost: 1453126829951.2276.pN9r8g==
2016-01-18 15:20:37.853 ThaliTest[2188:5392357] client ,session: onLinkFailure: 1453126829951.2276.pN9r8g==
2016-01-18 15:20:37.853 ThaliTest[2188:5392357] client session: disconnect
2016-01-18 15:20:37.853 ThaliTest[2188:5392357] client session: stateChange:1->0 1453126829951.2276.pN9r8g==
2016-01-18 15:20:,37.853 ThaliTest[2188:5392357] client session: fireConnectCallback: 1453126829951.2276.pN9r8g==
2016-01-18 15:20:37.854 ThaliTest[2188:5392357] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1453126829951.2276.pN9r8g==","peerName":"(null)","peerAvailable":false}]
,2016-01-18 15:20:38.856 ThaliTest[2188:5392527] jxcore: connect 1453126829951.2276.pN9r8g==
2016-01-18 15:20:38.856 ThaliTest[2188:5392527] client: connect: unreachable 1453126829951.2276.pN9r8g==
2016-01-18 15:20:38.856 ThaliTest[2188:5392527] jxcore: connect: fail: Peer unreachable
,2016-01-18 15:20:41.033 ThaliTest[2188:5393151] server session: connected
2016-01-18 15:20:41.033 ThaliTest[2188:5393151] server session: stateChange:1->2 1453126837889.2276
,2016-01-18 15:20:41.036 ThaliTest[2188:5392357] server relay: connected (to port: 61548)
,2016-01-18 15:20:41.207 ThaliTest[2188:5393145] server session: not connected 1453126837889.2276
,2016-01-18 15:20:41.278 ThaliTest[2188:5393064] client session: connected
,2016-01-18 15:20:41.278 ThaliTest[2188:5393064] client session: stateChange:1->2 1453126837889.2276.dyZ4xw==
2016-01-18 15:20:41.282 ThaliTest[2188:5393064] client session: fireConnectCallback: 1453126837889.2276.dyZ4xw==
2016-01-18 15:20:41.282 ThaliTes,t[2188:5393064] jxcore: connect: success
ok 94 Should be able to connect without error
ok 95 Port should be within range
ok 96 First connect should succeed
,2016-01-18 15:20:41.300 ThaliTest[2188:5392357] client: relay established
2016-01-18 15:20:41.300 ThaliTest[2188:5392357] client: new accepted socket: 0x185beb80
,ok 97 the test messages should be equal
ok 98 First send should succeed
,2016-01-18 15:20:41.350 ThaliTest[2188:5392357] client: socket closed
2016-01-18 15:20:41.350 ThaliTest[2188:5392357] client relay: socket disconnected
2016-01-18 15:20:41.351 ThaliTest[2188:5392357] client relay: 0x185beb80 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-18 15:20:41.351 ThaliTest[2188:5392357] client session: socket closed: 1453126837889.2276.dyZ4xw==
2016-01-18 15:20:41.351 ThaliTest[2188:5392357] client session: onLinkFailure: 1453126837889.2276.dyZ4xw==
2016-01-18 15:20:41.351 ThaliTest[2188:5392357] client session: disconnect
2016-01-18 15:20:41.351 ThaliTest[2188:5392357] client session: stateChange:2->0 1453126837889.2276.dyZ4xw==
2016-01-18 15:20:41.358 ThaliTest[2188:5392357] client session: fireConnectionErrorEvent: 1453126837889.2276.dyZ4xw==
,2016-01-18 15:20:41.361 ThaliTest[2188:5392527] jxcore: connect 1453126837889.2276.dyZ4xw==
,2016-01-18 15:20:41.366 ThaliTest[2188:5392527] client session: connect
2016-01-18 15:20:41.370 ThaliTest[2188:5392357] multipeer session: reset timer
,2016-01-18 15:20:41.370 ThaliTest[2188:5392357] multipeer session: stop timer
2016-01-18 15:20:41.371 ThaliTest[2188:5392357] multipeer session: start timer: 0x18470500
2016-01-18 15:20:41.371 ThaliTest[2188:5392357] server: disconnecting to refresh sess,ion (1453126837889.2276)
2016-01-18 15:20:41.371 ThaliTest[2188:5392357] server session: disconnect
2016-01-18 15:20:41.371 ThaliTest[2188:5392357] server session: stateChange:2->0 1453126837889.2276
2016-01-18 15:20:41.368 ThaliTest[2188:5392527] client session: stateChange:0->1 1453126837889.2276.dyZ4xw==
,2016-01-18 15:20:41.374 ThaliTest[2188:5392357] server session: connect
2016-01-18 15:20:41.374 ThaliTest[2188:5392357] server session: stateChange:0->1 1453126837889.2276
,2016-01-18 15:20:41.380 ThaliTest[2188:5392357] server: accepting invitation 1453126837889.2276
,2016-01-18 15:20:45.933 ThaliTest[2188:5393064] server session: connected
2016-01-18 15:20:45.933 ThaliTest[2188:5393064] server session: stateChange:1->2 1453126837889.2276
,2016-01-18 15:20:45.938 ThaliTest[2188:5392357] server relay: connected (to port: 61548)
,2016-01-18 15:20:46.053 ThaliTest[2188:5393064] server session: not connected 1453126837889.2276
,2016-01-18 15:20:46.072 ThaliTest[2188:5393047] client session: connected
2016-01-18 15:20:46.072 ThaliTest[2188:5393047] client session: stateChange:1->2 1453126837889.2276.dyZ4xw==
2016-01-18 15:20:46.075 ThaliTest[2188:5393047] client session: fireConnectCallback: 1453126837889.2276.dyZ4xw==
2016-01-18 15:20:46.075 ThaliTest[2188:5393047] jxcore: connect: success
ok 99 Should be able to connect without error
ok 100 Port should be within range
ok 101 Second connect should succeed
,2016-01-18 15:20:46.089 ThaliTest[2188:5392357] client: relay established
2016-01-18 15:20:46.090 ThaliTest[2188:5392357] client: new accepted socket: 0x184c8ed0
,ok 102 the test messages should be equal
,ok 103 Second send should succeed
,# setup
,2016-01-18 15:20:46.221 ThaliTest[2188:5392357] client: socket closed
2016-01-18 15:20:46.221 ThaliTest[2188:5392357] client relay: socket disconnected
2016-01-18 15:20:46.221 ThaliTest[2188:5392357] client relay: 0x184c8ed0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-18 15:20:46.221 ThaliTest[2188:5392357] client session: socket closed: 1453126837889.2276.dyZ4xw==
2016-01-18 ,15:20:46.221 ThaliTest[2188:5392357] client session: onLinkFailure: 1453126837889.2276.dyZ4xw==
2016-01-18 15:20:46.221 ThaliTest[2188:5392357] client session: disconnect
2016-01-18 15:20:46.221 ThaliTest[2188:5392357] client session: stateChange:2->0 1453126837889.2276.dyZ4xw==
,2016-01-18 15:20:46.226 ThaliTest[2188:5392357] client session: fireConnectionErrorEvent: 1453126837889.2276.dyZ4xw==
,calling stopBroadcasting
,2016-01-18 15:20:46.613 ThaliTest[2188:5392527] jxcore: stopBroadcasting
2016-01-18 15:20:46.613 ThaliTest[2188:5392527] THEMultipeerSession stopping peer
2016-01-18 15:20:46.613 ThaliTest[2188:5392527] multipeer session: stop timer
2016-01-18 15:20:46.,613 ThaliTest[2188:5392527] server session: disconnect
2016-01-18 15:20:46.614 ThaliTest[2188:5392527] server session: stateChange:2->0 1453126837889.2276
,2016-01-18 15:20:46.621 ThaliTest[2188:5392527] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/63F6CE40-2A81-45D0-86FA-D09135BB61C3/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 104 starting event should occur in right order
,2016-01-18 15:20:46.802 ThaliTest[2188:5392527] jxcore: startBroadcasting
,2016-01-18 15:20:46.804 ThaliTest[2188:5392527] server: starting zMpmdU7aW1fPi1IEYKNtPg.FwXGOg==
2016-01-18 15:20:46.804 ThaliTest[2188:5392527] multipeer session: start timer: 0x184c2950
2016-01-18 15:20:46.804 ThaliTest[2188:5392527] THEMultipeerSessio,n initialized peer zMpmdU7aW1fPi1IEYKNtPg
2016-01-18 15:20:46.804 ThaliTest[2188:5392527] jxcore: startBroadcasting: success
ok 105 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
,ok 106 stopping event should occur in right order
About to call stopBroadcasting
2016-01-18 15:20:46.807 ThaliTest[2188:5392527] jxcore: stopBroadcasting
2016-01-18 15:20:46.807 ThaliTest[2188:5392527] THEMultipeerSession stopping peer
2016-01-18 15:20,:46.808 ThaliTest[2188:5392527] multipeer session: stop timer
,2016-01-18 15:20:46.808 ThaliTest[2188:5392527] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
ok 107 stopped event should occur in right order
,mux server bridge listener closed
,# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/63F6CE40-2A81-45D0-86FA-D09135BB61C3/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-18 15:20:47.565 ThaliTest[2188:5392527] jxcore: startBroadcasting
,2016-01-18 15:20:47.567 ThaliTest[2188:5392527] server: starting zMpmdU7aW1fPi1IEYKNtPg.eme/bw==
2016-01-18 15:20:47.568 ThaliTest[2188:5392527] multipeer session: start timer: 0x1858b1e0
2016-01-18 15:20:47.568 ThaliTest[2188:5392527] THEMultipeerSession initialized peer zMpmdU7aW1fPi1IEYKNtPg
2016-01-18 15:20:47.568 ThaliTest[2188:5392527] jxcore: startBroadcasting: success
ok 108 getDeviceIdentity should not return an error
ok 109 deviceName should not be null
Now in TRM stop
State of this._isStar,ted: true
About to call stopBroadcasting
2016-01-18 15:20:47.570 ThaliTest[2188:5392527] jxcore: stopBroadcasting
2016-01-18 15:20:47.570 ThaliTest[2188:5392527] THEMultipeerSession stopping peer
,2016-01-18 15:20:47.570 ThaliTest[2188:5392527] multipeer session: stop timer
2016-01-18 15:20:47.574 ThaliTest[2188:5392527] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
mux server bridge listener closed
# setup
,# ThaliReplicationManager replicates database
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/63F6CE40-2A81-45D0-86FA-D09135BB61C3/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-18 15:20:50.327 ThaliTest[2188:5392527] jxcore: startBroadcasting
,2016-01-18 15:20:50.329 ThaliTest[2188:5392527] server: starting zMpmdU7aW1fPi1IEYKNtPg.tqUl5g==
,2016-01-18 15:20:50.333 ThaliTest[2188:5392527] multipeer session: start timer: 0x1a1e1b70
,2016-01-18 15:20:50.335 ThaliTest[2188:5392527] THEMultipeerSession initialized peer zMpmdU7aW1fPi1IEYKNtPg
,2016-01-18 15:20:50.336 ThaliTest[2188:5392527] jxcore: startBroadcasting: success
,ok 110 getDeviceIdentity should not return an error
,ok 111 deviceName should not be null
,2016-01-18 15:20:51.993 ThaliTest[2188:5392357] client: found peer: MTKjIr_Wsl-Cvu9WXlF3Sg.cC8YmQ==
,2016-01-18 15:20:56.116 ThaliTest[2188:5392527] jxcore: connect MTKjIr_Wsl-Cvu9WXlF3Sg.cC8YmQ==
2016-01-18 15:20:56.117 ThaliTest[2188:5392527] client session: connect
,2016-01-18 15:20:56.118 ThaliTest[2188:5392527] client session: stateChange:0->1 MTKjIr_Wsl-Cvu9WXlF3Sg.cC8YmQ==
,2016-01-18 15:20:56.168 ThaliTest[2188:5392357] multipeer session: reset timer
2016-01-18 15:20:56.168 ThaliTest[2188:5392357] multipeer session: stop timer
2016-01-18 15:20:56.169 ThaliTest[2188:5392357] multipeer session: start timer: 0x1a1e1b70
2016-01-18 15:20:56.169 ThaliTest[2188:5392357] server session: connect
2016-01-18 15:20:56.169 ThaliTest[2188:5392357] server session: stateChange:0->1 MTKjIr_Wsl-Cvu9WXlF3Sg
,2016-01-18 15:20:56.179 ThaliTest[2188:5392357] server: accepting invitation MTKjIr_Wsl-Cvu9WXlF3Sg
,ok 112 Should be able to put doc without error
,ok 113 1st change of local doc should contain local id
,2016-01-18 15:21:00.068 ThaliTest[2188:5393284] client session: connected
2016-01-18 15:21:00.068 ThaliTest[2188:5393284] client session: stateChange:1->2 MTKjIr_Wsl-Cvu9WXlF3Sg.cC8YmQ==
,2016-01-18 15:21:00.073 ThaliTest[2188:5393284] server session: connected
2016-01-18 15:21:00.073 ThaliTest[2188:5393284] server session: stateChange:1->2 MTKjIr_Wsl-Cvu9WXlF3Sg
,2016-01-18 15:21:00.083 ThaliTest[2188:5393145] client session: fireConnectCallback: MTKjIr_Wsl-Cvu9WXlF3Sg.cC8YmQ==
2016-01-18 15:21:00.085 ThaliTest[2188:5393145] jxcore: connect: success
2016-01-18 15:21:00.085 ThaliTest[2188:5392357] server relay: connected (to port: 61564)
server bridge: new client socket
,2016-01-18 15:21:00.096 ThaliTest[2188:5392357] client: relay established
2016-01-18 15:21:00.097 ThaliTest[2188:5392357] client: new accepted socket: 0x16e58c90
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: socket closed
,ok 114 1st change of remote doc should contain remote id
,client bridge: new client socket
,ok 115 Can update remote doc without error
,null
,{ ok: true,
  id: 'eaa446bb-855d-47ee-ac44-942df7374704',
  rev: '2-53531edfdd47576eed4300ae73c4a7e8' }
,client bridge: new client socket
,ok 116 Remote changes occur in strict order
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
client bridge: socket closed
,client bridge: new client socket
,ok 117 Local changes occur in strict order
,ok 118 2nd change of local doc should contain remote id
,# setup
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,2016-01-18 15:21:19.719 ThaliTest[2188:5393064] server session: not connected MTKjIr_Wsl-Cvu9WXlF3Sg
,2016-01-18 15:21:19.739 ThaliTest[2188:5393284] client session: not connected MTKjIr_Wsl-Cvu9WXlF3Sg.cC8YmQ==
2016-01-18 15:21:19.739 ThaliTest[2188:5393284] client session: onLinkFailure: MTKjIr_Wsl-Cvu9WXlF3Sg.cC8YmQ==
2016-01-18 15:21:19.739 ThaliTest[2188:5393284] client session: disconnect
2016-01-18 15:21:19.739 ThaliTest[2188:5393284] client session: stateChange:2->0 MTKjIr_Wsl-Cvu9WXlF3Sg.cC8YmQ==
,2016-01-18 15:21:19.743 ThaliTest[2188:5393284] client session: fireConnectionErrorEvent: MTKjIr_Wsl-Cvu9WXlF3Sg.cC8YmQ==
,Now in TRM stop
State of this._isStarted: true
,About to call stopBroadcasting
,2016-01-18 15:21:19.789 ThaliTest[2188:5392527] jxcore: stopBroadcasting
,2016-01-18 15:21:19.789 ThaliTest[2188:5392527] THEMultipeerSession stopping peer
,2016-01-18 15:21:19.790 ThaliTest[2188:5392527] multipeer session: stop timer
,2016-01-18 15:21:19.791 ThaliTest[2188:5392527] server session: disconnect
,2016-01-18 15:21:19.794 ThaliTest[2188:5392527] server session: stateChange:2->0 MTKjIr_Wsl-Cvu9WXlF3Sg
,2016-01-18 15:21:19.802 ThaliTest[2188:5392527] jxcore: stopBroadcasting: success
,Process 2188 stopped
* thread #17: tid = 0x524b84, 0x33e93ae6 libobjc.A.dylib`objc_msgSend + 6, queue = 'com.apple.MCSession.syncQueue', stop reason = EXC_BAD_ACCESS (code=1, address=0x8185c220)
    frame #0: 0x33e93ae6 libobjc.A.dylib`objc_msgSend + 6
libobjc.A.dylib`objc_msgSend:
->  0x33e93ae6 <+6>:  ldrh.w r12, [r9, #0xc]
    0x33e93aea <+10>: ldr.w  r9, [r9, #0x8]
    0x33e93aee <+14>: and.w  r12, r12, r1
    0x33e93af2 <+18>: add.w  r9, r9, r12, lsl #3
,* thread #17: tid = 0x524b84, 0x33e93ae6 libobjc.A.dylib`objc_msgSend + 6, queue = 'com.apple.MCSession.syncQueue', stop reason = EXC_BAD_ACCESS (code=1, address=0x8185c220)
  * frame #0: 0x33e93ae6 libobjc.A.dylib`objc_msgSend + 6
    frame #1: 0x24a4285e MultipeerConnectivity`<redacted> + 1334
    frame #2: 0x345be72a libdispatch.dylib`<redacted> + 2042
    frame #3: 0x345add6e libdispatch.dylib`<redacted> + 738
    frame #4: 0x345b5b5c libdispatch.dylib`<redacted> + 592
    frame #5: 0x345aef86 libdispatch.dylib`<redacted> + 282
    frame #6: 0x345b737c libdispatch.dylib`<redacted> + 400
    frame #7: 0x345b71ea libdispatch.dylib`<redacted> + 94
    frame #8: 0x34740e0c libsystem_pthread.dylib`_pthread_wqthread + 1024
    frame #9: 0x347409fc libsystem_pthread.dylib`start_wqthread + 8

```
