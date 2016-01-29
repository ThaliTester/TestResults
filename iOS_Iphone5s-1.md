#### Test 56818254e6f5c3b_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56818254e6f5c3b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/4924498B-95AC-4BB6-9091-25C4D0580DB5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/4924498B-95AC-4BB6-9091-25C4D0580DB5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/56818254e6f5c3b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56818254e6f5c3b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9EF6EB7B-F71C-4125-BAA3-167AD915CCD7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63000"
,(lldb)     command script import "/tmp/4924498B-95AC-4BB6-9091-25C4D0580DB5/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-29 17:40:29.638 ThaliTest[2936:8269815] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/32982DE2-CA5C-4A27-A7BB-F9DBA2CD7383/Library/Cookies/Cookies.binarycookies
,2016-01-29 17:40:29.925 ThaliTest[2936:8269815] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-29 17:40:29.926 ThaliTest[2936:8269815] Multi-tasking -> Device: YES, App: YES
,2016-01-29 17:40:29.933 ThaliTest[2936:8269815] Unlimited access to network resources
,2016-01-29 17:40:29.942 ThaliTest[2936:8269815] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-29 17:40:34.572 ThaliTest[2936:8269815] Resetting plugins due to page load.
,2016-01-29 17:40:36.032 ThaliTest[2936:8269815] Finished load of: file:///var/mobile/Containers/Bundle/Application/9EF6EB7B-F71C-4125-BAA3-167AD915CCD7/ThaliTest.app/www/index.html
,2016-01-29 17:40:36.245 ThaliTest[2936:8269815] JXcore Cordova plugin initializing
2016-01-29 17:40:36.246 ThaliTest[2936:8270008] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9EF6EB7B-F71C-4125-BAA3-167AD915CCD7/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9EF6EB7B-F71C-4125-BAA3-167AD915CCD7/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9EF6EB7B-F71C-4125-BAA3-167AD915CCD7/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9EF6EB7B-F71C-4125-BAA3-167AD915CCD7/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9EF6EB7B-F71C-4125-BAA3-167AD915CCD7/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9EF6EB7B-F71C-4125-BAA3-167AD915CCD7/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js
,
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9EF6EB7B-F71C-4125-BAA3-167AD915CCD7/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9EF6EB7B-F71C-4125-BAA3-167AD915CCD7/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,# teardown

,ok 1 String should be length:200

# setup

,# enqueue and run in order

,# teardown

,ok 2 firstPromise setTimeout

,ok 3 firstPromise result

ok 4 firstPromise testValue

,ok 5 secondPromise setTimeout

ok 6 secondPromise result

ok 7 secondPromise testValue

ok 8 thirdPromise in promise

ok 9 thirdPromise result

ok 10 thirdPromise testValue

,# setup

,# basic

,# teardown

,ok 11 sane

,# setup

,# another

,# teardown

,ok 12 sane

# setup

,# successfully create a new pkcs12 file and return hash value

,# teardown

,ok 13 should be equal

,ok 14 null

,ok 15 (unnamed assert)

ok 16 should be equal

,ok 17 should not throw

# setup

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

ok 26 should be equal

ok 27 should be equal

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

# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,# teardown

,ok 35 should be equal

ok 36 should be equal

ok 37 should be equal

# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,# teardown

,ok 38 should be equal

,ok 39 should be equal

ok 40 should be equal

# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,# teardown

,ok 41 should be equal

ok 42 should be equal

# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,# teardown

,ok 43 should be equal

,ok 44 should be equal

# setup

,# #connect should call Mobile("Connect") with a port and without an error

,# teardown

,ok 45 should be equal

ok 46 should be equal

,ok 47 should be equal

# setup

,# #connect should call Mobile("Connect") and handle an error

,# teardown

,ok 48 should be equal

ok 49 should be equal

# setup

,# should call Mobile("Disconnect") without an error

,# teardown

,ok 50 should be equal

ok 51 should be equal

# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 52 should be equal

ok 53 should be equal

# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-01-29 17:44:32.668 ThaliTest[2936:8270008] jxcore: startBroadcasting
,2016-01-29 17:44:32.676 ThaliTest[2936:8270008] server: starting 1454085872667.2936.MTaOiQ==
2016-01-29 17:44:32.676 ThaliTest[2936:8270008] multipeer session: start timer: 0x179db910
2016-01-29 17:44:32.677 ThaliTest[2936:8270008] THEMultipeerSession in,itialized peer 1454085872667.2936
2016-01-29 17:44:32.677 ThaliTest[2936:8270008] jxcore: startBroadcasting: success
ok 54 Should be able to call startBroadcasting without error

2016-01-29 17:44:32.678 ThaliTest[2936:8270008] jxcore: stopBroadcasting
2016-01-29 17:44:32.678 ThaliTest[2936:8270008] THEMultipeerSession stopping peer
2016-01-29 17:44:32.678 ThaliTest[2936:8270008] multipeer session: stop timer
2016-01-29 17:44:32.679 ThaliTest[2936:8270008] jxcore: stopBroadcasting: success
ok 55 Shou,ld be able to call stopBroadcasting without error

2016-01-29 17:44:32.679 ThaliTest[2936:8270008] jxcore: startBroadcasting
2016-01-29 17:44:32.681 ThaliTest[2936:8270008] server: starting 1454085872679.2936.Qyhzcw==
,2016-01-29 17:44:32.682 ThaliTest[2936:8270008] multipeer session: start timer: 0x17bd4630
2016-01-29 17:44:32.688 ThaliTest[2936:8270008] THEMultipeerSession initialized peer 1454085872679.2936
2016-01-29 17:44:32.688 ThaliTest[2936:8270008] jxcore: startBroadcasting: success
ok 56 Should be able to call startBroadcasting without error

2016-01-29 17:44:32.689 ThaliTest[2936:8270008] jxcore: stopBroadcasting
,2016-01-29 17:44:32.689 ThaliTest[2936:8270008] THEMultipeerSession stopping peer
2016-01-29 17:44:32.693 ThaliTest[2936:8270008] multipeer session: stop timer
2016-01-29 17:44:32.694 ThaliTest[2936:8270008] jxcore: stopBroadcasting: success
ok 57 Shoul,d be able to call stopBroadcasting without error

2016-01-29 17:44:32.695 ThaliTest[2936:8270008] jxcore: startBroadcasting
,2016-01-29 17:44:32.702 ThaliTest[2936:8270008] server: starting 1454085872694.2936.Rk1P5Q==
,2016-01-29 17:44:32.703 ThaliTest[2936:8270008] multipeer session: start timer: 0x17be4d60
2016-01-29 17:44:32.707 ThaliTest[2936:8270008] THEMultipeerSession initialized peer 1454085872694.2936
2016-01-29 17:44:32.708 ThaliTest[2936:8270008] jxcore: sta,rtBroadcasting: success
ok 58 Should be able to call startBroadcasting without error

2016-01-29 17:44:32.709 ThaliTest[2936:8270008] jxcore: stopBroadcasting
2016-01-29 17:44:32.709 ThaliTest[2936:8270008] THEMultipeerSession stopping peer
2016-01-29 17:44:32.709 ThaliTest[2936:8270008] multipeer session: stop timer
,2016-01-29 17:44:32.709 ThaliTest[2936:8270008] jxcore: stopBroadcasting: success
ok 59 Should be able to call stopBroadcasting without error

2016-01-29 17:44:32.713 ThaliTest[2936:8270008] jxcore: startBroadcasting
,2016-01-29 17:44:32.718 ThaliTest[2936:8270008] server: starting 1454085872713.2936.gqLKTQ==
2016-01-29 17:44:32.718 ThaliTest[2936:8270008] multipeer session: start timer: 0x17be4d60
2016-01-29 17:44:32.718 ThaliTest[2936:8270008] THEMultipeerSession initialized peer 1454085872713.2936
,2016-01-29 17:44:32.718 ThaliTest[2936:8270008] jxcore: startBroadcasting: success
ok 60 Should be able to call startBroadcasting without error

2016-01-29 17:44:32.724 ThaliTest[2936:8270008] jxcore: stopBroadcasting
2016-01-29 17:44:32.724 ThaliTest[,2936:8270008] THEMultipeerSession stopping peer
2016-01-29 17:44:32.725 ThaliTest[2936:8270008] multipeer session: stop timer
2016-01-29 17:44:32.725 ThaliTest[2936:8270008] jxcore: stopBroadcasting: success
ok 61 Should be able to call stopBroadcasting without error

2016-01-29 17:44:32.726 ThaliTest[2936:8270008] jxcore: startBroadcasting
2016-01-29 17:44:32.730 ThaliTest[2936:8270008] server: starting 1454085872725.2936.774zPg==
2016-01-29 17:44:32.730 ThaliTest[2936:8270008] multipeer session: st,art timer: 0x179dcc80
2016-01-29 17:44:32.730 ThaliTest[2936:8270008] THEMultipeerSession initialized peer 1454085872725.2936
2016-01-29 17:44:32.730 ThaliTest[2936:8270008] jxcore: startBroadcasting: success
ok 62 Should be able to call startBroadcasti,ng without error

2016-01-29 17:44:32.734 ThaliTest[2936:8270008] jxcore: stopBroadcasting
2016-01-29 17:44:32.734 ThaliTest[2936:8270008] THEMultipeerSession stopping peer
2016-01-29 17:44:32.734 ThaliTest[2936:8270008] multipeer session: stop timer
,2016-01-29 17:44:32.734 ThaliTest[2936:8270008] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error

,2016-01-29 17:44:32.740 ThaliTest[2936:8270008] jxcore: startBroadcasting
,2016-01-29 17:44:32.751 ThaliTest[2936:8270008] server: starting 1454085872740.2936.VKHl/A==
,2016-01-29 17:44:32.753 ThaliTest[2936:8270008] multipeer session: start timer: 0x17be4d60
,2016-01-29 17:44:32.758 ThaliTest[2936:8270008] THEMultipeerSession initialized peer 1454085872740.2936
,2016-01-29 17:44:32.759 ThaliTest[2936:8270008] jxcore: startBroadcasting: success
,ok 64 Should be able to call startBroadcasting without error

,2016-01-29 17:44:32.761 ThaliTest[2936:8270008] jxcore: stopBroadcasting
,2016-01-29 17:44:32.762 ThaliTest[2936:8270008] THEMultipeerSession stopping peer
,2016-01-29 17:44:32.762 ThaliTest[2936:8270008] multipeer session: stop timer
,2016-01-29 17:44:32.765 ThaliTest[2936:8270008] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error
,
,2016-01-29 17:44:32.768 ThaliTest[2936:8270008] jxcore: startBroadcasting
,2016-01-29 17:44:32.772 ThaliTest[2936:8270008] server: starting 1454085872767.2936.CMR5vg==
,2016-01-29 17:44:32.775 ThaliTest[2936:8270008] multipeer session: start timer: 0x17bd52d0
,2016-01-29 17:44:32.777 ThaliTest[2936:8270008] THEMultipeerSession initialized peer 1454085872767.2936
,2016-01-29 17:44:32.780 ThaliTest[2936:8270008] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error
,
,2016-01-29 17:44:32.783 ThaliTest[2936:8270008] jxcore: stopBroadcasting
,2016-01-29 17:44:32.784 ThaliTest[2936:8270008] THEMultipeerSession stopping peer
,2016-01-29 17:44:32.785 ThaliTest[2936:8270008] multipeer session: stop timer
,2016-01-29 17:44:32.787 ThaliTest[2936:8270008] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,
,2016-01-29 17:44:32.792 ThaliTest[2936:8270008] jxcore: startBroadcasting
,2016-01-29 17:44:32.795 ThaliTest[2936:8270008] server: starting 1454085872792.2936.34iA0g==
,2016-01-29 17:44:32.799 ThaliTest[2936:8270008] multipeer session: start timer: 0x179de740
,2016-01-29 17:44:32.803 ThaliTest[2936:8270008] THEMultipeerSession initialized peer 1454085872792.2936
,2016-01-29 17:44:32.805 ThaliTest[2936:8270008] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-01-29 17:44:32.807 ThaliTest[2936:8270008] jxcore: stopBroadcasting
,2016-01-29 17:44:32.808 ThaliTest[2936:8270008] THEMultipeerSession stopping peer
,2016-01-29 17:44:32.809 ThaliTest[2936:8270008] multipeer session: stop timer
,2016-01-29 17:44:32.811 ThaliTest[2936:8270008] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-01-29 17:44:32.815 ThaliTest[2936:8270008] jxcore: startBroadcasting
,2016-01-29 17:44:32.817 ThaliTest[2936:8270008] server: starting 1454085872814.2936.tvGzSQ==
,2016-01-29 17:44:32.821 ThaliTest[2936:8270008] multipeer session: start timer: 0x179dfb10
,2016-01-29 17:44:32.822 ThaliTest[2936:8270008] THEMultipeerSession initialized peer 1454085872814.2936
,2016-01-29 17:44:32.824 ThaliTest[2936:8270008] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error
,
,2016-01-29 17:44:32.828 ThaliTest[2936:8270008] jxcore: stopBroadcasting
,2016-01-29 17:44:32.829 ThaliTest[2936:8270008] THEMultipeerSession stopping peer
,2016-01-29 17:44:32.830 ThaliTest[2936:8270008] multipeer session: stop timer
,2016-01-29 17:44:32.833 ThaliTest[2936:8270008] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error
,
,2016-01-29 17:44:32.835 ThaliTest[2936:8270008] jxcore: startBroadcasting
,2016-01-29 17:44:32.839 ThaliTest[2936:8270008] server: starting 1454085872835.2936.w1ia3A==
,2016-01-29 17:44:32.840 ThaliTest[2936:8270008] multipeer session: start timer: 0x17e3a1a0
,2016-01-29 17:44:32.846 ThaliTest[2936:8270008] THEMultipeerSession initialized peer 1454085872835.2936
,2016-01-29 17:44:32.847 ThaliTest[2936:8270008] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-01-29 17:44:32.849 ThaliTest[2936:8270008] jxcore: stopBroadcasting
,2016-01-29 17:44:32.850 ThaliTest[2936:8270008] THEMultipeerSession stopping peer
,2016-01-29 17:44:32.851 ThaliTest[2936:8270008] multipeer session: stop timer
,2016-01-29 17:44:32.855 ThaliTest[2936:8270008] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
,
,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-29 17:44:33.591 ThaliTest[2936:8270008] jxcore: startBroadcasting
,2016-01-29 17:44:33.593 ThaliTest[2936:8270008] server: starting 1454085873591.2936.HeYxDg==
2016-01-29 17:44:33.593 ThaliTest[2936:8270008] multipeer session: start timer: 0x179d10c0
2016-01-29 17:44:33.594 ThaliTest[2936:8270008] THEMultipeerSession in,itialized peer 1454085873591.2936
2016-01-29 17:44:33.594 ThaliTest[2936:8270008] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

2016-01-29 17:44:33.595 ThaliTest[2936:8270008] jxcore: startBroadcasting
2016-01-29 17:44:33.595 ThaliTest[2936:8270008] jxcore: startBroadcasting: failure
,ok 75 Cannot call startBroadcasting twice

2016-01-29 17:44:33.597 ThaliTest[2936:8270008] jxcore: stopBroadcasting
2016-01-29 17:44:33.597 ThaliTest[2936:8270008] THEMultipeerSession stopping peer
2016-01-29 17:44:33.597 ThaliTest[2936:8270008] multipeer session: stop timer
2016-01-29 17:44:33.598 ThaliTest[2936:8270008] jxcore: stopBroadcasting: success
ok 76 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-29 17:44:36.620 ThaliTest[2936:8270008] jxcore: startBroadcasting
,2016-01-29 17:44:36.622 ThaliTest[2936:8270008] server: starting 1454085876620.2936.C1Wp9Q==
2016-01-29 17:44:36.623 ThaliTest[2936:8270008] multipeer session: start timer: 0x17a51300
2016-01-29 17:44:36.623 ThaliTest[2936:8270008] THEMultipeerSession in,itialized peer 1454085876620.2936
2016-01-29 17:44:36.623 ThaliTest[2936:8270008] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-01-29 17:44:36.624 ThaliTest[2936:8270008] jxcore: connect foobar
2,016-01-29 17:44:36.624 ThaliTest[2936:8270008] client: unknown peer foobar
2016-01-29 17:44:36.624 ThaliTest[2936:8270008] jxcore: connect: fail: Unknown peer
ok 78 Should not connect to a bad peer

,2016-01-29 17:44:36.626 ThaliTest[2936:8270008] jxcore: stopBroadcasting
2016-01-29 17:44:36.627 ThaliTest[2936:8270008] THEMultipeerSession stopping peer
2016-01-29 17:44:36.627 ThaliTest[2936:8270008] multipeer session: stop timer
2016-01-29 17:44:36.627 ThaliTest[2936:8270008] jxcore: stopBroadcasting: success
ok 79 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-29 17:44:39.941 ThaliTest[2936:8270008] jxcore: startBroadcasting
,2016-01-29 17:44:39.944 ThaliTest[2936:8270008] server: starting 1454085879941.2936.W/IWrw==
2016-01-29 17:44:39.944 ThaliTest[2936:8270008] multipeer session: start timer: 0x18ef1bc0
2016-01-29 17:44:39.944 ThaliTest[2936:8270008] THEMultipeerSession initialized peer 1454085879941.2936
2016-01-29 17:44:39.944 ThaliTest[2936:8270008] jxcore: startBroadcasting: success
ok 80 Should be able to call startBroadcasting without error

2016-01-29 17:44:39.945 ThaliTest[2936:8270008] jxcore: disconnect
2016-01-29 17:44:39.945 ThaliTest[2936:8270008] jxcore: disconnect: fail
ok 81 Disconnect should fail to a non-existant peer 

,2016-01-29 17:44:39.947 ThaliTest[2936:8270008] jxcore: stopBroadcasting
2016-01-29 17:44:39.951 ThaliTest[2936:8270008] THEMultipeerSession stopping peer
2016-01-29 17:44:39.951 ThaliTest[2936:8270008] multipeer session: stop timer
2016-01-29 17:44:39.951 ThaliTest[2936:8270008] jxcore: stopBroadcasting: success
ok 82 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-29 17:44:41.342 ThaliTest[2936:8270008] jxcore: startBroadcasting
,2016-01-29 17:44:41.345 ThaliTest[2936:8270008] server: starting 1454085881342.2936.2DH/dw==
2016-01-29 17:44:41.345 ThaliTest[2936:8270008] multipeer session: start timer: 0x179048f0
2016-01-29 17:44:41.345 ThaliTest[2936:8270008] THEMultipeerSession in,itialized peer 1454085881342.2936
2016-01-29 17:44:41.345 ThaliTest[2936:8270008] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-29 17:44:42.688 ThaliTest[2936:8269815] client: found peer: 1454085881367.2139.Fq/gzg==
2016-01-29 17:44:42.689 ThaliTest[2936:8270008] jxcore: connect 1454085881367.2139.Fq/gzg==
2016-01-29 17:44:42.689 ThaliTest[2936:8270008] client session: connect
2016-01-29 17:44:42.689 ThaliTest[2936:8270008] client session: stateChange:0->1 1454085881367.2139.Fq/gzg==
,2016-01-29 17:44:43.213 ThaliTest[2936:8269815] multipeer session: reset timer
2016-01-29 17:44:43.213 ThaliTest[2936:8269815] multipeer session: stop timer
2016-01-29 17:44:43.213 ThaliTest[2936:8269815] multipeer session: start timer: 0x179048f0
2016-,01-29 17:44:43.214 ThaliTest[2936:8269815] server session: connect
2016-01-29 17:44:43.214 ThaliTest[2936:8269815] server session: stateChange:0->1 1454085881367.2139
2016-01-29 17:44:43.218 ThaliTest[2936:8269815] server: accepting invitation 1454085881367.2139
,2016-01-29 17:44:45.579 ThaliTest[2936:8270791] client session: connected
2016-01-29 17:44:45.579 ThaliTest[2936:8270791] client session: stateChange:1->2 1454085881367.2139.Fq/gzg==
,2016-01-29 17:44:45.601 ThaliTest[2936:8270832] client session: fireConnectCallback: 1454085881367.2139.Fq/gzg==
2016-01-29 17:44:45.601 ThaliTest[2936:8270832] jxcore: connect: success
,ok 84 Should be able to connect without error

ok 85 Port should be within range

,2016-01-29 17:44:45.603 ThaliTest[2936:8270008] jxcore: disconnect
2016-01-29 17:44:45.603 ThaliTest[2936:8270008] client session: disconnectFromPeer: 1454085881367.2139.Fq/gzg==
2016-01-29 17:44:45.603 ThaliTest[2936:8270008] client session: disconnect
2016-01-29 17:44:45.603 ThaliTest[2936:8270008] client session: stateChange:2->0 1454085881367.2139.Fq/gzg==
,2016-01-29 17:44:45.631 ThaliTest[2936:8270785] server session: connected
2016-01-29 17:44:45.631 ThaliTest[2936:8270785] server session: stateChange:1->2 1454085881367.2139
,2016-01-29 17:44:45.669 ThaliTest[2936:8270008] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-29 17:44:45.704 ThaliTest[2936:8270832] server session: not connected 1454085881367.2139
,calling stopBroadcasting

,2016-01-29 17:44:46.639 ThaliTest[2936:8270008] jxcore: stopBroadcasting
2016-01-29 17:44:46.639 ThaliTest[2936:8270008] THEMultipeerSession stopping peer
2016-01-29 17:44:46.639 ThaliTest[2936:8270008] multipeer session: stop timer
2016-01-29 17:44:46.640 ThaliTest[2936:8270008] server session: disconnect
2016-01-29 17:44:46.640 ThaliTest[2936:8270008] server session: stateChange:2->0 1454085881367.2139
,2016-01-29 17:44:47.445 ThaliTest[2936:8270008] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-29 17:44:48.777 ThaliTest[2936:8270008] jxcore: startBroadcasting
,2016-01-29 17:44:48.787 ThaliTest[2936:8270008] server: starting 1454085888777.2936.B5dxuA==
2016-01-29 17:44:48.788 ThaliTest[2936:8270008] multipeer session: start timer: 0x17a01a20
2016-01-29 17:44:48.788 ThaliTest[2936:8270008] THEMultipeerSession initialized peer 1454085888777.2936
2016-01-29 17:44:48.788 ThaliTest[2936:8270008] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-01-29 17:44:49.399 ThaliTest[2936:8269815] client: found peer: 1454085888241.2139.CSRtYw==
2016-01-29 17:44:49.400 ThaliTest[2936:8270008] jxcore: connect 1454085888241.2139.CSRtYw==
2016-01-29 17:44:49.400 ThaliTest[2936:8270008] client session: co,nnect
2016-01-29 17:44:49.400 ThaliTest[2936:8270008] client session: stateChange:0->1 1454085888241.2139.CSRtYw==
,2016-01-29 17:44:49.891 ThaliTest[2936:8269815] multipeer session: reset timer
2016-01-29 17:44:49.891 ThaliTest[2936:8269815] multipeer session: stop timer
2016-01-29 17:44:49.891 ThaliTest[2936:8269815] multipeer session: start timer: 0x17a01a20
2016-,01-29 17:44:49.892 ThaliTest[2936:8269815] server session: connect
2016-01-29 17:44:49.892 ThaliTest[2936:8269815] server session: stateChange:0->1 1454085888241.2139
2016-01-29 17:44:49.896 ThaliTest[2936:8269815] server: accepting invitation 1454085888241.2139
,2016-01-29 17:44:52.022 ThaliTest[2936:8270785] client session: connected
2016-01-29 17:44:52.022 ThaliTest[2936:8270785] client session: stateChange:1->2 1454085888241.2139.CSRtYw==
,2016-01-29 17:44:52.024 ThaliTest[2936:8270785] client session: fireConnectCallback: 1454085888241.2139.CSRtYw==
2016-01-29 17:44:52.024 ThaliTest[2936:8270785] jxcore: connect: success
ok 88 Should be able to connect without error

ok 89 Port should be within range

,2016-01-29 17:44:52.026 ThaliTest[2936:8270008] jxcore: connect 1454085888241.2139.CSRtYw==
2016-01-29 17:44:52.026 ThaliTest[2936:8270008] client: already connect(ing/ed) to 1454085888241.2139.CSRtYw==
2016-01-29 17:44:52.027 ThaliTest[2936:8270008] jxcore: connect: fail: Aleady connecting
ok 90 Should fail on double connect

,2016-01-29 17:44:52.028 ThaliTest[2936:8270008] jxcore: disconnect
2016-01-29 17:44:52.028 ThaliTest[2936:8270008] client session: disconnectFromPeer: 1454085888241.2139.CSRtYw==
2016-01-29 17:44:52.028 ThaliTest[2936:8270008] client session: disconnect
2016-01-29 17:44:52.029 ThaliTest[2936:8270008] client session: stateChange:2->0 1454085888241.2139.CSRtYw==
,2016-01-29 17:44:52.092 ThaliTest[2936:8270008] jxcore: disconnect: success
,ok 91 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-29 17:44:52.391 ThaliTest[2936:8270791] server session: connected
2016-01-29 17:44:52.391 ThaliTest[2936:8270791] server session: stateChange:1->2 1454085888241.2139
,2016-01-29 17:44:52.393 ThaliTest[2936:8269815] server relay: socket disconnected
2016-01-29 17:44:52.394 ThaliTest[2936:8269815] server relay: 0x17d33870 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-29 17:44:52.455 ThaliTest[2936:8270832] server session: not connected 1454085888241.2139
,calling stopBroadcasting

,2016-01-29 17:44:52.466 ThaliTest[2936:8270008] jxcore: stopBroadcasting
2016-01-29 17:44:52.466 ThaliTest[2936:8270008] THEMultipeerSession stopping peer
2016-01-29 17:44:52.466 ThaliTest[2936:8270008] multipeer session: stop timer
2016-01-29 17:44:52.,466 ThaliTest[2936:8270008] server session: disconnect
2016-01-29 17:44:52.466 ThaliTest[2936:8270008] server session: stateChange:2->0 1454085888241.2139
2016-01-29 17:44:52.467 ThaliTest[2936:8270008] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-29 17:44:53.964 ThaliTest[2936:8270008] jxcore: startBroadcasting
,2016-01-29 17:44:53.966 ThaliTest[2936:8270008] server: starting 1454085893964.2936.R5nDuQ==
2016-01-29 17:44:53.966 ThaliTest[2936:8270008] multipeer session: start timer: 0x18d44c10
2016-01-29 17:44:53.966 ThaliTest[2936:8270008] THEMultipeerSession in,itialized peer 1454085893964.2936
2016-01-29 17:44:53.967 ThaliTest[2936:8270008] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-01-29 17:44:55.202 ThaliTest[2936:8269815] client: found peer: 1454085893984.2139.8zyT5Q==
2016-01-29 17:44:55.203 ThaliTest[2936:8270008] jxcore: connect 1454085893984.2139.8zyT5Q==
2016-01-29 17:44:55.204 ThaliTest[2936:8270008] client session: connect
2016-01-29 17:44:55.204 ThaliTest[2936:8270008] client session: stateChange:0->1 1454085893984.2139.8zyT5Q==
,2016-01-29 17:44:55.463 ThaliTest[2936:8269815] multipeer session: reset timer
2016-01-29 17:44:55.464 ThaliTest[2936:8269815] multipeer session: stop timer
2016-01-29 17:44:55.464 ThaliTest[2936:8269815] multipeer session: start timer: 0x18d44c10
2016-01-29 17:44:55.464 ThaliTest[2936:8269815] server session: connect
2016-01-29 17:44:55.464 ThaliTest[2936:8269815] server session: stateChange:0->1 1454085893984.2139
2016-01-29 17:44:55.470 ThaliTest[2936:8269815] server: accepting invitation 1454085893984.2139
,2016-01-29 17:44:57.788 ThaliTest[2936:8270791] client session: connected
2016-01-29 17:44:57.788 ThaliTest[2936:8270791] client session: stateChange:1->2 1454085893984.2139.8zyT5Q==
2016-01-29 17:44:57.789 ThaliTest[2936:8270791] client session: fireCon,nectCallback: 1454085893984.2139.8zyT5Q==
2016-01-29 17:44:57.789 ThaliTest[2936:8270791] jxcore: connect: success
ok 93 Should be able to connect without error

ok 94 Port should be within range

2016-01-29 17:44:57.791 ThaliTest[2936:8270008] jxcore: disconnect
,2016-01-29 17:44:57.791 ThaliTest[2936:8270008] client session: disconnectFromPeer: 1454085893984.2139.8zyT5Q==
,2016-01-29 17:44:57.792 ThaliTest[2936:8270008] client session: disconnect
,2016-01-29 17:44:57.792 ThaliTest[2936:8270008] client session: stateChange:2->0 1454085893984.2139.8zyT5Q==
,2016-01-29 17:44:57.857 ThaliTest[2936:8270008] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

2016-01-29 17:44:57.858 ThaliTest[2936:8270008] jxcore: disconnect
2016-01-29 17:44:57.858 ThaliTest[2936:8270008] jxcore: disconnect: fail
ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-29 17:44:58.095 ThaliTest[2936:8270848] server session: connected
2016-01-29 17:44:58.095 ThaliTest[2936:8270848] server session: stateChange:1->2 1454085893984.2139
,2016-01-29 17:44:58.115 ThaliTest[2936:8269815] server relay: socket disconnected
2016-01-29 17:44:58.115 ThaliTest[2936:8269815] server relay: 0x17f867f0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-29 17:44:58.165 ThaliTest[2936:8270848] server session: not connected 1454085893984.2139
,calling stopBroadcasting

,2016-01-29 17:44:58.674 ThaliTest[2936:8270008] jxcore: stopBroadcasting
2016-01-29 17:44:58.675 ThaliTest[2936:8270008] THEMultipeerSession stopping peer
2016-01-29 17:44:58.675 ThaliTest[2936:8270008] multipeer session: stop timer
2016-01-29 17:44:58.675 ThaliTest[2936:8270008] server session: disconnect
2016-01-29 17:44:58.675 ThaliTest[2936:8270008] server session: stateChange:2->0 1454085893984.2139
,2016-01-29 17:44:58.675 ThaliTest[2936:8270008] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 49687

,2016-01-29 17:45:00.428 ThaliTest[2936:8270008] jxcore: startBroadcasting
,2016-01-29 17:45:00.437 ThaliTest[2936:8270008] server: starting 1454085900428.2936.MW4pdw==
,2016-01-29 17:45:00.439 ThaliTest[2936:8270008] multipeer session: start timer: 0x17e2e7c0
,2016-01-29 17:45:00.445 ThaliTest[2936:8270008] THEMultipeerSession initialized peer 1454085900428.2936
,2016-01-29 17:45:00.446 ThaliTest[2936:8270008] jxcore: startBroadcasting: success
,ok 97 Should be able to call startBroadcasting without error

,2016-01-29 17:45:01.984 ThaliTest[2936:8269815] client: found peer: 1454085900795.2139.ZfgRDw==
2016-01-29 17:45:01.984 ThaliTest[2936:8270008] jxcore: connect 1454085900795.2139.ZfgRDw==
2016-01-29 17:45:01.985 ThaliTest[2936:8270008] client session: connect
2016-01-29 17:45:01.985 ThaliTest[2936:8270008] client session: stateChange:0->1 1454085900795.2139.ZfgRDw==
,2016-01-29 17:45:02.027 ThaliTest[2936:8269815] multipeer session: reset timer
2016-01-29 17:45:02.027 ThaliTest[2936:8269815] multipeer session: stop timer
2016-01-29 17:45:02.027 ThaliTest[2936:8269815] multipeer session: start timer: 0x17e2e7c0
2016-01-29 17:45:02.027 ThaliTest[2936:8269815] server session: connect
2016-01-29 17:45:02.027 ThaliTest[2936:8269815] server session: stateChange:0->1 1454085900795.2139
,2016-01-29 17:45:02.032 ThaliTest[2936:8269815] server: accepting invitation 1454085900795.2139
,2016-01-29 17:45:04.633 ThaliTest[2936:8270785] server session: connected
2016-01-29 17:45:04.633 ThaliTest[2936:8270785] server session: stateChange:1->2 1454085900795.2139
,2016-01-29 17:45:04.773 ThaliTest[2936:8269815] server relay: connected (to port: 49687)
,2016-01-29 17:45:05.043 ThaliTest[2936:8270791] client session: connected
2016-01-29 17:45:05.043 ThaliTest[2936:8270791] client session: stateChange:1->2 1454085900795.2139.ZfgRDw==
,2016-01-29 17:45:05.227 ThaliTest[2936:8270848] client session: fireConnectCallback: 1454085900795.2139.ZfgRDw==
2016-01-29 17:45:05.227 ThaliTest[2936:8270848] jxcore: connect: success
ok 98 Should be able to connect without error

ok 99 Port should b,e within range

,2016-01-29 17:45:05.234 ThaliTest[2936:8269815] client: relay established
,2016-01-29 17:45:05.234 ThaliTest[2936:8269815] client: new accepted socket: 0x17f850d0
,data in 5475

,data in 27233

,data in 30660

,2016-01-29 17:45:05.559 ThaliTest[2936:8270832] server session: not connected 1454085900795.2139
,data in 34756

,data in 68559

,data in 71175

,data in 72270

,data in 94170

,data in 99645

,data in 117165

,data in 131072

,ok 100 the test messages should be equal

,2016-01-29 17:45:05.838 ThaliTest[2936:8270008] jxcore: disconnect
2016-01-29 17:45:05.838 ThaliTest[2936:8270008] client session: disconnectFromPeer: 1454085900795.2139.ZfgRDw==
2016-01-29 17:45:05.838 ThaliTest[2936:8270008] client session: disconnect
2016-01-29 17:45:05.838 ThaliTest[2936:8270008] client session: stateChange:2->0 1454085900795.2139.ZfgRDw==
,2016-01-29 17:45:05.900 ThaliTest[2936:8270008] jxcore: disconnect: success
,ok 101 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-29 17:45:06.024 ThaliTest[2936:8270008] jxcore: stopBroadcasting
2016-01-29 17:45:06.024 ThaliTest[2936:8270008] THEMultipeerSession stopping peer
2016-01-29 17:45:06.024 ThaliTest[2936:8270008] multipeer session: stop timer
2016-01-29 17:45:06.,024 ThaliTest[2936:8270008] server session: disconnect
2016-01-29 17:45:06.024 ThaliTest[2936:8270008] server session: stateChange:2->0 1454085900795.2139
,2016-01-29 17:45:06.029 ThaliTest[2936:8270008] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 49693

2016-01-29 17:45:06.543 ThaliTest[2936:8270008] jxcore: startBroadcasting
,2016-01-29 17:45:06.545 ThaliTest[2936:8270008] server: starting 1454085906543.2936.5mQb3g==
2016-01-29 17:45:06.546 ThaliTest[2936:8270008] multipeer session: start timer: 0x17f87910
2016-01-29 17:45:06.546 ThaliTest[2936:8270008] THEMultipeerSession initialized peer 1454085906543.2936
2016-01-29 17:45:06.546 ThaliTest[2936:8270008] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-01-29 17:45:07.152 ThaliTest[2936:8269815] client: found peer: 1454085900795.2139.ZfgRDw==
[{"peerIdentifier":"1454085900795.2139.ZfgRDw==","peerName":"(null)","peerAvailable":true}]

2016-01-29 17:45:07.154 ThaliTest[2936:8270008] jxcore: connect 1454085900795.2139.ZfgRDw==
2016-01-29 17:45:07.154 ThaliTest[2936:8270008] client session: connect
2016-01-29 17:45:07.154 ThaliTest[2936:8270008] client session: stateChange:0->1 1454085900795.2139.ZfgRDw==
,2016-01-29 17:45:07.811 ThaliTest[2936:8269815] client: found peer: 1454085906574.2139.8tpZOw==
[{"peerIdentifier":"1454085906574.2139.8tpZOw==","peerName":"(null)","peerAvailable":true}]

2016-01-29 17:45:07.812 ThaliTest[2936:8270008] jxcore: connect 1454085906574.2139.8tpZOw==
2016-01-29 17:45:07.812 ThaliTest[2936:8270008] client session: connect
2016-01-29 17:45:07.812 ThaliTest[2936:8270008] client session: stateChange:0->1 1454085906574.2139.8tpZOw==
,2016-01-29 17:45:07.976 ThaliTest[2936:8269815] multipeer session: reset timer
2016-01-29 17:45:07.977 ThaliTest[2936:8269815] multipeer session: stop timer
2016-01-29 17:45:07.977 ThaliTest[2936:8269815] multipeer session: start timer: 0x17f87910
2016-01-29 17:45:07.977 ThaliTest[2936:8269815] server session: connect
2016-01-29 17:45:07.977 ThaliTest[2936:8269815] server session: stateChange:0->1 1454085906574.2139
2016-01-29 17:45:07.980 ThaliTest[2936:8269815] server: accepting invitation 1454085906,574.2139
,2016-01-29 17:45:09.246 ThaliTest[2936:8269815] client: lost peer: 1454085900795.2139.ZfgRDw==
2016-01-29 17:45:09.246 ThaliTest[2936:8269815] client session: onPeerLost: 1454085900795.2139.ZfgRDw==
2016-01-29 17:45:09.247 ThaliTest[2936:8269815] client session: onLinkFailure: 1454085900795.2139.ZfgRDw==
2016-01-29 17:45:09.247 ThaliTest[2936:8269815] client session: disconnect
2016-01-29 17:45:09.247 ThaliTest[2936:8269815] client session: stateChange:1->0 1454085900795.2139.ZfgRDw==
2016-01-29 17:45:,09.247 ThaliTest[2936:8269815] client session: fireConnectCallback: 1454085900795.2139.ZfgRDw==
2016-01-29 17:45:09.247 ThaliTest[2936:8269815] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1454085900795.2139.ZfgRDw==","peerName":"(null)","peerAvailable":false}]

,2016-01-29 17:45:10.260 ThaliTest[2936:8270008] jxcore: connect 1454085900795.2139.ZfgRDw==
2016-01-29 17:45:10.261 ThaliTest[2936:8270008] client: connect: unreachable 1454085900795.2139.ZfgRDw==
2016-01-29 17:45:10.261 ThaliTest[2936:8270008] jxcore: connect: fail: Peer unreachable
,2016-01-29 17:45:10.410 ThaliTest[2936:8270832] server session: connected
2016-01-29 17:45:10.410 ThaliTest[2936:8270832] server session: stateChange:1->2 1454085906574.2139
,2016-01-29 17:45:10.415 ThaliTest[2936:8270832] client session: connected
2016-01-29 17:45:10.415 ThaliTest[2936:8270832] client session: stateChange:1->2 1454085906574.2139.8tpZOw==
,2016-01-29 17:45:10.434 ThaliTest[2936:8269815] server relay: connected (to port: 49693)
,2016-01-29 17:45:10.468 ThaliTest[2936:8270791] client session: fireConnectCallback: 1454085906574.2139.8tpZOw==
2016-01-29 17:45:10.468 ThaliTest[2936:8270791] jxcore: connect: success
,ok 103 Should be able to connect without error

ok 104 Port should be within range

,ok 105 First connect should succeed

,2016-01-29 17:45:10.482 ThaliTest[2936:8269815] client: relay established
2016-01-29 17:45:10.482 ThaliTest[2936:8269815] client: new accepted socket: 0x17ecc480
,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-01-29 17:45:10.568 ThaliTest[2936:8269815] client: socket closed
2016-01-29 17:45:10.568 ThaliTest[2936:8269815] client relay: socket disconnected
2016-01-29 17:45:10.568 ThaliTest[2936:8269815] client relay: 0x17ecc480 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-29 17:45:10.568 ThaliTest[2936:8269815] client session: socket closed: 1454085906574.2139.8tpZOw==
2016-01-29 ,17:45:10.568 ThaliTest[2936:8269815] client session: onLinkFailure: 1454085906574.2139.8tpZOw==
2016-01-29 17:45:10.569 ThaliTest[2936:8269815] client session: disconnect
2016-01-29 17:45:10.569 ThaliTest[2936:8269815] client session: stateChange:2->0 14,54085906574.2139.8tpZOw==
,2016-01-29 17:45:10.573 ThaliTest[2936:8269815] client session: fireConnectionErrorEvent: 1454085906574.2139.8tpZOw==
2016-01-29 17:45:10.575 ThaliTest[2936:8270008] jxcore: connect 1454085906574.2139.8tpZOw==
2016-01-29 17:45:10.575 ThaliTest[2936:82700,08] client session: connect
2016-01-29 17:45:10.575 ThaliTest[2936:8270008] client session: stateChange:0->1 1454085906574.2139.8tpZOw==
,2016-01-29 17:45:10.599 ThaliTest[2936:8270789] server session: not connected 1454085906574.2139
,2016-01-29 17:45:10.727 ThaliTest[2936:8269815] multipeer session: reset timer
2016-01-29 17:45:10.727 ThaliTest[2936:8269815] multipeer session: stop timer
2016-01-29 17:45:10.727 ThaliTest[2936:8269815] multipeer session: start timer: 0x17f87910
2016-,01-29 17:45:10.727 ThaliTest[2936:8269815] server: disconnecting to refresh session (1454085906574.2139)
2016-01-29 17:45:10.727 ThaliTest[2936:8269815] server session: disconnect
2016-01-29 17:45:10.728 ThaliTest[2936:8269815] server session: stateChange:2->0 1454085906574.2139
,2016-01-29 17:45:10.729 ThaliTest[2936:8269815] server session: connect
2016-01-29 17:45:10.730 ThaliTest[2936:8269815] server session: stateChange:0->1 1454085906574.2139
,2016-01-29 17:45:10.735 ThaliTest[2936:8269815] server: accepting invitation 1454085906574.2139
,2016-01-29 17:45:13.295 ThaliTest[2936:8270832] server session: connected
2016-01-29 17:45:13.295 ThaliTest[2936:8270832] server session: stateChange:1->2 1454085906574.2139
,2016-01-29 17:45:13.300 ThaliTest[2936:8270789] client session: connected
2016-01-29 17:45:13.300 ThaliTest[2936:8270789] client session: stateChange:1->2 1454085906574.2139.8tpZOw==
,2016-01-29 17:45:13.367 ThaliTest[2936:8270832] client session: fireConnectCallback: 1454085906574.2139.8tpZOw==
2016-01-29 17:45:13.367 ThaliTest[2936:8270832] jxcore: connect: success
2016-01-29 17:45:13.367 ThaliTest[2936:8269815] server relay: connected (to port: 49693)
ok 108 Should be able to connect without error

ok 109 Port should be within range

ok 110 Second connect should succeed

,2016-01-29 17:45:13.382 ThaliTest[2936:8269815] client: relay established
2016-01-29 17:45:13.383 ThaliTest[2936:8269815] client: new accepted socket: 0x17f924d0
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-01-29 17:45:13.453 ThaliTest[2936:8269815] client: socket closed
2016-01-29 17:45:13.453 ThaliTest[2936:8269815] client relay: socket disconnected
2016-01-29 17:45:13.453 ThaliTest[2936:8269815] client relay: 0x17f924d0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-29 17:45:13.453 ThaliTest[2936:8269815] client session: socket closed: 1454085906574.2139.8tpZOw==
2016-01-29 ,17:45:13.454 ThaliTest[2936:8269815] client session: onLinkFailure: 1454085906574.2139.8tpZOw==
2016-01-29 17:45:13.454 ThaliTest[2936:8269815] client session: disconnect
2016-01-29 17:45:13.454 ThaliTest[2936:8269815] client session: stateChange:2->0 1454085906574.2139.8tpZOw==
,2016-01-29 17:45:13.462 ThaliTest[2936:8269815] client session: fireConnectionErrorEvent: 1454085906574.2139.8tpZOw==
,2016-01-29 17:45:13.491 ThaliTest[2936:8270848] server session: not connected 1454085906574.2139
,calling stopBroadcasting

,2016-01-29 17:45:14.407 ThaliTest[2936:8270008] jxcore: stopBroadcasting
2016-01-29 17:45:14.408 ThaliTest[2936:8270008] THEMultipeerSession stopping peer
2016-01-29 17:45:14.408 ThaliTest[2936:8270008] multipeer session: stop timer
2016-01-29 17:45:14.,408 ThaliTest[2936:8270008] server session: disconnect
2016-01-29 17:45:14.408 ThaliTest[2936:8270008] server session: stateChange:2->0 1454085906574.2139
,2016-01-29 17:45:14.412 ThaliTest[2936:8270008] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown
,
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/32982DE2-CA5C-4A27-A7BB-F9DBA2CD7383/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-01-29 17:45:14.960 ThaliTest[2936:8270008] jxcore: startBroadcasting
,2016-01-29 17:45:14.962 ThaliTest[2936:8270008] server: starting 3FYYZiHqGQblvDtT62oZ0w.xABTRQ==
,2016-01-29 17:45:14.964 ThaliTest[2936:8270008] multipeer session: start timer: 0x16507c80
,2016-01-29 17:45:14.970 ThaliTest[2936:8270008] THEMultipeerSession initialized peer 3FYYZiHqGQblvDtT62oZ0w
,2016-01-29 17:45:14.971 ThaliTest[2936:8270008] jxcore: startBroadcasting: success
,ok 114 started event should occur in right order

Now in TRM stop

,State of this._isStarted: true

,ok 115 stopping event should occur in right order

,About to call stopBroadcasting

,2016-01-29 17:45:14.975 ThaliTest[2936:8270008] jxcore: stopBroadcasting
,2016-01-29 17:45:14.975 ThaliTest[2936:8270008] THEMultipeerSession stopping peer
,2016-01-29 17:45:14.976 ThaliTest[2936:8270008] multipeer session: stop timer
,2016-01-29 17:45:14.977 ThaliTest[2936:8270008] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,ok 116 stopped event should occur in right order

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/32982DE2-CA5C-4A27-A7BB-F9DBA2CD7383/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-29 17:45:15.998 ThaliTest[2936:8270008] jxcore: startBroadcasting
,2016-01-29 17:45:16.000 ThaliTest[2936:8270008] server: starting 3FYYZiHqGQblvDtT62oZ0w.92H/sQ==
2016-01-29 17:45:16.000 ThaliTest[2936:8270008] multipeer session: start timer: 0x17da4e40
2016-01-29 17:45:16.000 ThaliTest[2936:8270008] THEMultipeerSessio,n initialized peer 3FYYZiHqGQblvDtT62oZ0w
2016-01-29 17:45:16.000 ThaliTest[2936:8270008] jxcore: startBroadcasting: success
ok 117 getDeviceIdentity should not return an error

ok 118 deviceName should not be null

Now in TRM stop

State of this._,isStarted: true

About to call stopBroadcasting

2016-01-29 17:45:16.002 ThaliTest[2936:8270008] jxcore: stopBroadcasting
2016-01-29 17:45:16.002 ThaliTest[2936:8270008] THEMultipeerSession stopping peer
2016-01-29 17:45:16.002 ThaliTest[2936:8270008,] multipeer session: stop timer
2016-01-29 17:45:16.002 ThaliTest[2936:8270008] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/32982DE2-CA5C-4A27-A7BB-F9DBA2CD7383/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-29 17:45:18.782 ThaliTest[2936:8270008] jxcore: startBroadcasting
,2016-01-29 17:45:18.785 ThaliTest[2936:8270008] server: starting 3FYYZiHqGQblvDtT62oZ0w.kOsNPw==
2016-01-29 17:45:18.785 ThaliTest[2936:8270008] multipeer session: start timer: 0x17cd53b0
2016-01-29 17:45:18.785 ThaliTest[2936:8270008] THEMultipeerSession initialized peer 3FYYZiHqGQblvDtT62oZ0w
,2016-01-29 17:45:18.787 ThaliTest[2936:8270008] jxcore: startBroadcasting: success
ok 119 getDeviceIdentity should not return an error

ok 120 deviceName should not be null

,2016-01-29 17:45:21.907 ThaliTest[2936:8269815] client: found peer: Uwpyz15uvsEce9PnLtS3SQ.UamVKQ==
,2016-01-29 17:45:24.248 ThaliTest[2936:8270008] jxcore: connect Uwpyz15uvsEce9PnLtS3SQ.UamVKQ==
,2016-01-29 17:45:24.250 ThaliTest[2936:8270008] client session: connect
,2016-01-29 17:45:24.250 ThaliTest[2936:8270008] client session: stateChange:0->1 Uwpyz15uvsEce9PnLtS3SQ.UamVKQ==
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-01-29 17:45:30.948 ThaliTest[2936:8269815] multipeer session: reset timer
2016-01-29 17:45:30.948 ThaliTest[2936:8269815] multipeer session: stop timer
2016-01-29 17:45:30.948 ThaliTest[2936:8269815] multipeer session: start timer: 0x17cd53b0
2016-,01-29 17:45:30.948 ThaliTest[2936:8269815] server session: connect
2016-01-29 17:45:30.948 ThaliTest[2936:8269815] server session: stateChange:0->1 Uwpyz15uvsEce9PnLtS3SQ
2016-01-29 17:45:30.952 ThaliTest[2936:8269815] server: accepting invitation Uwpyz15uvsEce9PnLtS3SQ
,2016-01-29 17:45:33.536 ThaliTest[2936:8270832] server session: connected
2016-01-29 17:45:33.536 ThaliTest[2936:8270832] server session: stateChange:1->2 Uwpyz15uvsEce9PnLtS3SQ
,2016-01-29 17:45:33.563 ThaliTest[2936:8269815] server relay: connected (to port: 49709)
,server bridge: new client socket

,2016-01-29 17:45:33.594 ThaliTest[2936:8271013] client session: connected
,2016-01-29 17:45:33.594 ThaliTest[2936:8271013] client session: stateChange:1->2 Uwpyz15uvsEce9PnLtS3SQ.UamVKQ==
,2016-01-29 17:45:33.607 ThaliTest[2936:8270848] client session: fireConnectCallback: Uwpyz15uvsEce9PnLtS3SQ.UamVKQ==
2016-01-29 17:45:33.607 ThaliTest[2936:8270848] jxcore: connect: success
,2016-01-29 17:45:33.610 ThaliTest[2936:8269815] client: relay established
2016-01-29 17:45:33.610 ThaliTest[2936:8269815] client: new accepted socket: 0x1652e0a0
,client bridge: new client socket

,client bridge: new client socket
,
,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,2016-01-29 17:45:43.899 ThaliTest[2936:8271019] server session: not connected Uwpyz15uvsEce9PnLtS3SQ
,client bridge: socket closed

,client bridge: socket closed

,Possibly unhandled Error. ETIMEDOUT
onError@/private/var/mobile/Containers/Bundle/Application/9EF6EB7B-F71C-4125-BAA3-167AD915CCD7/ThaliTest.app/www/jxcore/node_modules/pouchdb/lib/deps/ajax.js:66:18
ajax/<@/private/var/mobile/Containers/Bundle/Application/9EF6EB7B-F71C-4125-BAA3-167AD915CCD7/ThaliTest.app/www/jxcore/node_modules/pouchdb/lib/deps/ajax.js:108:1
Request.prototype.init/self.callback@/private/var/mobile/Containers/Bundle/Application/9EF6EB7B-F71C-4125-BAA3-167AD915CCD7/ThaliTest.app/www/jxco,re/node_modules/pouchdb/node_modules/request/request.js:123:7
emit@events.js:82:1
Request.prototype.start/self.timeoutTimer<@/private/var/mobile/Containers/Bundle/Application/9EF6EB7B-F71C-4125-BAA3-167AD915CCD7/ThaliTest.app/www/jxcore/node_modules/pouc,hdb/node_modules/request/request.js:590:7
$9@timers.js:120:1


,client bridge: socket closed

,client bridge: new client socket

,2016-01-29 17:45:46.690 ThaliTest[2936:8270791] client session: not connected Uwpyz15uvsEce9PnLtS3SQ.UamVKQ==
2016-01-29 17:45:46.690 ThaliTest[2936:8270791] client session: onLinkFailure: Uwpyz15uvsEce9PnLtS3SQ.UamVKQ==
2016-01-29 17:45:46.690 ThaliTest,[2936:8270791] client session: disconnect
2016-01-29 17:45:46.691 ThaliTest[2936:8270791] client session: stateChange:2->0 Uwpyz15uvsEce9PnLtS3SQ.UamVKQ==
,2016-01-29 17:45:46.795 ThaliTest[2936:8270791] client session: fireConnectionErrorEvent: Uwpyz15uvsEce9PnLtS3SQ.UamVKQ==
,2016-01-29 17:45:46.842 ThaliTest[2936:8269815] client: lost peer: Uwpyz15uvsEce9PnLtS3SQ.UamVKQ==
2016-01-29 17:45:46.844 ThaliTest[2936:8269815] client session: onPeerLost: Uwpyz15uvsEce9PnLtS3SQ.UamVKQ==
2016-01-29 17:45:46.846 ThaliTest[2936:8270008], jxcore: disconnect
2016-01-29 17:45:46.846 ThaliTest[2936:8270008] jxcore: disconnect: fail
Disconnect error with error: Error: Not connected to specified peer

2016-01-29 17:45:46.849 ThaliTest[2936:8270008] jxcore: connect Uwpyz15uvsEce9PnLtS3SQ.UamVKQ==
,2016-01-29 17:45:46.849 ThaliTest[2936:8270008] client: connect: unreachable Uwpyz15uvsEce9PnLtS3SQ.UamVKQ==
,2016-01-29 17:45:46.851 ThaliTest[2936:8270008] jxcore: connect: fail: Peer unreachable
,Connect error with error: Error: Peer unreachable

,2016-01-29 17:45:46.869 ThaliTest[2936:8270008] jxcore: disconnect
,2016-01-29 17:45:46.869 ThaliTest[2936:8270008] jxcore: disconnect: fail
,Disconnect error with error: Error: Not connected to specified peer

peerIdentifier not available Uwpyz15uvsEce9PnLtS3SQ.UamVKQ==
,
,client bridge: socket closed

,client bridge: socket closed

,2016-01-29 17:46:00.949 ThaliTest[2936:8269815] multipeer session: restart
,Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

,2016-01-29 17:46:06.975 ThaliTest[2936:8270008] jxcore: stopBroadcasting
2016-01-29 17:46:06.975 ThaliTest[2936:8270008] THEMultipeerSession stopping peer
2016-01-29 17:46:06.975 ThaliTest[2936:8270008] multipeer session: stop timer
2016-01-29 17:46:06.,976 ThaliTest[2936:8270008] server session: disconnect
2016-01-29 17:46:06.976 ThaliTest[2936:8270008] server session: stateChange:2->0 Uwpyz15uvsEce9PnLtS3SQ
,2016-01-29 17:46:06.985 ThaliTest[2936:8270008] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,server bridge: socket closed


```
