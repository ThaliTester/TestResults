#### Test 581356550b07fff_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/581356550b07fff/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/9872C297-232F-47A4-8318-5A7669881033/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/9872C297-232F-47A4-8318-5A7669881033/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/581356550b07fff/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/581356550b07fff/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/19044A95-A351-439A-B283-FB9EAE9A4B0F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52007"
,(lldb)     command script import "/tmp/9872C297-232F-47A4-8318-5A7669881033/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-08 17:51:32.953 ThaliTest[1482:2818717] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/77943CA1-704E-458A-BAC7-E2B22588792C/Library/Cookies/Cookies.binarycookies
,2016-02-08 17:51:33.406 ThaliTest[1482:2818717] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-08 17:51:33.408 ThaliTest[1482:2818717] Multi-tasking -> Device: YES, App: YES
,2016-02-08 17:51:33.419 ThaliTest[1482:2818717] Unlimited access to network resources
,2016-02-08 17:51:33.433 ThaliTest[1482:2818717] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-08 17:51:43.619 ThaliTest[1482:2818717] Resetting plugins due to page load.
,2016-02-08 17:51:47.107 ThaliTest[1482:2818717] Finished load of: file:///var/mobile/Containers/Bundle/Application/19044A95-A351-439A-B283-FB9EAE9A4B0F/ThaliTest.app/www/index.html
,2016-02-08 17:51:47.294 ThaliTest[1482:2818717] JXcore Cordova plugin initializing
2016-02-08 17:51:47.296 ThaliTest[1482:2819086] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19044A95-A351-439A-B283-FB9EAE9A4B0F/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19044A95-A351-439A-B283-FB9EAE9A4B0F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19044A95-A351-439A-B283-FB9EAE9A4B0F/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19044A95-A351-439A-B283-FB9EAE9A4B0F/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19044A95-A351-439A-B283-FB9EAE9A4B0F/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19044A95-A351-439A-B283-FB9EAE9A4B0F/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19044A95-A351-439A-B283-FB9EAE9A4B0F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19044A95-A351-439A-B283-FB9EAE9A4B0F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

ok 20 should not throw

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

# setup

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

,2016-02-08 17:56:56.668 ThaliTest[1482:2819086] jxcore: startBroadcasting
,2016-02-08 17:56:56.683 ThaliTest[1482:2819086] server: starting 1454950616668.1482.8RWcPg==
,2016-02-08 17:56:56.684 ThaliTest[1482:2819086] multipeer session: start timer: 0x18bb8a60
,2016-02-08 17:56:56.685 ThaliTest[1482:2819086] THEMultipeerSession initialized peer 1454950616668.1482
2016-02-08 17:56:56.686 ThaliTest[1482:2819086] jxcore: startBroadcasting: success
,ok 54 Should be able to call startBroadcasting without error

,2016-02-08 17:56:56.690 ThaliTest[1482:2819086] jxcore: stopBroadcasting
2016-02-08 17:56:56.691 ThaliTest[1482:2819086] THEMultipeerSession stopping peer
2016-02-08 17:56:56.691 ThaliTest[1482:2819086] multipeer session: stop timer
2016-02-08 17:56:56.,692 ThaliTest[1482:2819086] jxcore: stopBroadcasting: success
ok 55 Should be able to call stopBroadcasting without error

2016-02-08 17:56:56.694 ThaliTest[1482:2819086] jxcore: startBroadcasting
2016-02-08 17:56:56.698 ThaliTest[1482:2819086] server:, starting 1454950616694.1482./XMYOg==
2016-02-08 17:56:56.699 ThaliTest[1482:2819086] multipeer session: start timer: 0x18bbc2a0
2016-02-08 17:56:56.699 ThaliTest[1482:2819086] THEMultipeerSession initialized peer 1454950616694.1482
2016-02-08 17:56:56.,700 ThaliTest[1482:2819086] jxcore: startBroadcasting: success
ok 56 Should be able to call startBroadcasting without error

,2016-02-08 17:56:56.702 ThaliTest[1482:2819086] jxcore: stopBroadcasting
,2016-02-08 17:56:56.706 ThaliTest[1482:2819086] THEMultipeerSession stopping peer
2016-02-08 17:56:56.706 ThaliTest[1482:2819086] multipeer session: stop timer
2016-02-08 17:56:56.707 ThaliTest[1482:2819086] jxcore: stopBroadcasting: success
ok 57 Shoul,d be able to call stopBroadcasting without error

2016-02-08 17:56:56.709 ThaliTest[1482:2819086] jxcore: startBroadcasting
,2016-02-08 17:56:56.718 ThaliTest[1482:2819086] server: starting 1454950616708.1482.uOGDug==
2016-02-08 17:56:56.719 ThaliTest[1482:2819086] multipeer session: start timer: 0x17a63e40
2016-02-08 17:56:56.719 ThaliTest[1482:2819086] THEMultipeerSession in,itialized peer 1454950616708.1482
2016-02-08 17:56:56.719 ThaliTest[1482:2819086] jxcore: startBroadcasting: success
ok 58 Should be able to call startBroadcasting without error

,2016-02-08 17:56:56.722 ThaliTest[1482:2819086] jxcore: stopBroadcasting
2016-02-08 17:56:56.728 ThaliTest[1482:2819086] THEMultipeerSession stopping peer
2016-02-08 17:56:56.729 ThaliTest[1482:2819086] multipeer session: stop timer
,2016-02-08 17:56:56.729 ThaliTest[1482:2819086] jxcore: stopBroadcasting: success
ok 59 Should be able to call stopBroadcasting without error

2016-02-08 17:56:56.736 ThaliTest[1482:2819086] jxcore: startBroadcasting
,2016-02-08 17:56:56.743 ThaliTest[1482:2819086] server: starting 1454950616735.1482.L/ykqA==
2016-02-08 17:56:56.746 ThaliTest[1482:2819086] multipeer session: start timer: 0x17a647d0
2016-02-08 17:56:56.747 ThaliTest[1482:2819086] THEMultipeerSession in,itialized peer 1454950616735.1482
2016-02-08 17:56:56.747 ThaliTest[1482:2819086] jxcore: startBroadcasting: success
,ok 60 Should be able to call startBroadcasting without error
,
,2016-02-08 17:56:56.763 ThaliTest[1482:2819086] jxcore: stopBroadcasting
,2016-02-08 17:56:56.764 ThaliTest[1482:2819086] THEMultipeerSession stopping peer
,2016-02-08 17:56:56.765 ThaliTest[1482:2819086] multipeer session: stop timer
,2016-02-08 17:56:56.768 ThaliTest[1482:2819086] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error

,2016-02-08 17:56:56.773 ThaliTest[1482:2819086] jxcore: startBroadcasting
,2016-02-08 17:56:56.776 ThaliTest[1482:2819086] server: starting 1454950616773.1482.qKdV1A==
,2016-02-08 17:56:56.777 ThaliTest[1482:2819086] multipeer session: start timer: 0x18bbda80
,2016-02-08 17:56:56.781 ThaliTest[1482:2819086] THEMultipeerSession initialized peer 1454950616773.1482
,2016-02-08 17:56:56.783 ThaliTest[1482:2819086] jxcore: startBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error

,2016-02-08 17:56:56.786 ThaliTest[1482:2819086] jxcore: stopBroadcasting
,2016-02-08 17:56:56.787 ThaliTest[1482:2819086] THEMultipeerSession stopping peer
,2016-02-08 17:56:56.788 ThaliTest[1482:2819086] multipeer session: stop timer
,2016-02-08 17:56:56.789 ThaliTest[1482:2819086] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error
,
,2016-02-08 17:56:56.795 ThaliTest[1482:2819086] jxcore: startBroadcasting
,2016-02-08 17:56:56.798 ThaliTest[1482:2819086] server: starting 1454950616794.1482.edEtIQ==
,2016-02-08 17:56:56.800 ThaliTest[1482:2819086] multipeer session: start timer: 0x18bbd7e0
,2016-02-08 17:56:56.805 ThaliTest[1482:2819086] THEMultipeerSession initialized peer 1454950616794.1482
,2016-02-08 17:56:56.807 ThaliTest[1482:2819086] jxcore: startBroadcasting: success
,ok 64 Should be able to call startBroadcasting without error

,2016-02-08 17:56:56.810 ThaliTest[1482:2819086] jxcore: stopBroadcasting
,2016-02-08 17:56:56.811 ThaliTest[1482:2819086] THEMultipeerSession stopping peer
,2016-02-08 17:56:56.811 ThaliTest[1482:2819086] multipeer session: stop timer
,2016-02-08 17:56:56.814 ThaliTest[1482:2819086] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error

,2016-02-08 17:56:56.818 ThaliTest[1482:2819086] jxcore: startBroadcasting
,2016-02-08 17:56:56.821 ThaliTest[1482:2819086] server: starting 1454950616818.1482.dv0pfg==
,2016-02-08 17:56:56.822 ThaliTest[1482:2819086] multipeer session: start timer: 0x17a64910
,2016-02-08 17:56:56.827 ThaliTest[1482:2819086] THEMultipeerSession initialized peer 1454950616818.1482
,2016-02-08 17:56:56.829 ThaliTest[1482:2819086] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error

,2016-02-08 17:56:56.832 ThaliTest[1482:2819086] jxcore: stopBroadcasting
,2016-02-08 17:56:56.833 ThaliTest[1482:2819086] THEMultipeerSession stopping peer
,2016-02-08 17:56:56.834 ThaliTest[1482:2819086] multipeer session: stop timer
,2016-02-08 17:56:56.836 ThaliTest[1482:2819086] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,2016-02-08 17:56:56.841 ThaliTest[1482:2819086] jxcore: startBroadcasting
,2016-02-08 17:56:56.843 ThaliTest[1482:2819086] server: starting 1454950616840.1482.7Bv/AA==
,2016-02-08 17:56:56.844 ThaliTest[1482:2819086] multipeer session: start timer: 0x18bbf770
,2016-02-08 17:56:56.847 ThaliTest[1482:2819086] THEMultipeerSession initialized peer 1454950616840.1482
2016-02-08 17:56:56.848 ThaliTest[1482:2819086] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error
,
,2016-02-08 17:56:56.853 ThaliTest[1482:2819086] jxcore: stopBroadcasting
,2016-02-08 17:56:56.854 ThaliTest[1482:2819086] THEMultipeerSession stopping peer
,2016-02-08 17:56:56.855 ThaliTest[1482:2819086] multipeer session: stop timer
,2016-02-08 17:56:56.857 ThaliTest[1482:2819086] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-02-08 17:56:56.862 ThaliTest[1482:2819086] jxcore: startBroadcasting
,2016-02-08 17:56:56.865 ThaliTest[1482:2819086] server: starting 1454950616861.1482.c91fcg==
,2016-02-08 17:56:56.867 ThaliTest[1482:2819086] multipeer session: start timer: 0x18bc0240
,2016-02-08 17:56:56.871 ThaliTest[1482:2819086] THEMultipeerSession initialized peer 1454950616861.1482
,2016-02-08 17:56:56.872 ThaliTest[1482:2819086] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-02-08 17:56:56.874 ThaliTest[1482:2819086] jxcore: stopBroadcasting
,2016-02-08 17:56:56.875 ThaliTest[1482:2819086] THEMultipeerSession stopping peer
,2016-02-08 17:56:56.876 ThaliTest[1482:2819086] multipeer session: stop timer
,2016-02-08 17:56:56.878 ThaliTest[1482:2819086] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

,2016-02-08 17:56:56.880 ThaliTest[1482:2819086] jxcore: startBroadcasting
,2016-02-08 17:56:56.883 ThaliTest[1482:2819086] server: starting 1454950616880.1482.4fXHBw==
,2016-02-08 17:56:56.884 ThaliTest[1482:2819086] multipeer session: start timer: 0x17a975d0
2016-02-08 17:56:56.886 ThaliTest[1482:2819086] THEMultipeerSession initialized peer 1454950616880.1482
,2016-02-08 17:56:56.889 ThaliTest[1482:2819086] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-02-08 17:56:56.890 ThaliTest[1482:2819086] jxcore: stopBroadcasting
,2016-02-08 17:56:56.891 ThaliTest[1482:2819086] THEMultipeerSession stopping peer
,2016-02-08 17:56:56.891 ThaliTest[1482:2819086] multipeer session: stop timer
,2016-02-08 17:56:56.893 ThaliTest[1482:2819086] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-08 17:56:57.549 ThaliTest[1482:2819086] jxcore: startBroadcasting
,2016-02-08 17:56:57.552 ThaliTest[1482:2819086] server: starting 1454950617548.1482.3aM6nQ==
2016-02-08 17:56:57.553 ThaliTest[1482:2819086] multipeer session: start timer: 0x18bc2e10
2016-02-08 17:56:57.554 ThaliTest[1482:2819086] THEMultipeerSession in,itialized peer 1454950617548.1482
2016-02-08 17:56:57.554 ThaliTest[1482:2819086] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

2016-02-08 17:56:57.556 ThaliTest[1482:2819086] jxcore: startBroadcasting,
2016-02-08 17:56:57.557 ThaliTest[1482:2819086] jxcore: startBroadcasting: failure
ok 75 Cannot call startBroadcasting twice

2016-02-08 17:56:57.560 ThaliTest[1482:2819086] jxcore: stopBroadcasting
2016-02-08 17:56:57.560 ThaliTest[1482:2819086] THE,MultipeerSession stopping peer
2016-02-08 17:56:57.560 ThaliTest[1482:2819086] multipeer session: stop timer
2016-02-08 17:56:57.561 ThaliTest[1482:2819086] jxcore: stopBroadcasting: success
ok 76 Should be able to call stopBroadcasting without error
,
,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-08 17:56:58.066 ThaliTest[1482:2819086] jxcore: startBroadcasting
,2016-02-08 17:56:58.070 ThaliTest[1482:2819086] server: starting 1454950618066.1482.C3strw==
2016-02-08 17:56:58.071 ThaliTest[1482:2819086] multipeer session: start timer: 0x17a9b600
2016-02-08 17:56:58.071 ThaliTest[1482:2819086] THEMultipeerSession in,itialized peer 1454950618066.1482
2016-02-08 17:56:58.072 ThaliTest[1482:2819086] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-02-08 17:56:58.074 ThaliTest[1482:2819086] jxcore: connect foobar
2,016-02-08 17:56:58.075 ThaliTest[1482:2819086] client: unknown peer foobar
2016-02-08 17:56:58.075 ThaliTest[1482:2819086] jxcore: connect: fail: Unknown peer
,ok 78 Should not connect to a bad peer

,2016-02-08 17:56:58.080 ThaliTest[1482:2819086] jxcore: stopBroadcasting
2016-02-08 17:56:58.080 ThaliTest[1482:2819086] THEMultipeerSession stopping peer
2016-02-08 17:56:58.081 ThaliTest[1482:2819086] multipeer session: stop timer
2016-02-08 17:56:58.,081 ThaliTest[1482:2819086] jxcore: stopBroadcasting: success
ok 79 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-08 17:56:59.054 ThaliTest[1482:2819086] jxcore: startBroadcasting
,2016-02-08 17:56:59.058 ThaliTest[1482:2819086] server: starting 1454950619054.1482.Km5Hug==
2016-02-08 17:56:59.059 ThaliTest[1482:2819086] multipeer session: start timer: 0x17b28ce0
,2016-02-08 17:56:59.059 ThaliTest[1482:2819086] THEMultipeerSession initialized peer 1454950619054.1482
,2016-02-08 17:56:59.071 ThaliTest[1482:2819086] jxcore: startBroadcasting: success
,ok 80 Should be able to call startBroadcasting without error

,2016-02-08 17:56:59.075 ThaliTest[1482:2819086] jxcore: disconnect
,2016-02-08 17:56:59.077 ThaliTest[1482:2819086] jxcore: disconnect: fail
,ok 81 Disconnect should fail to a non-existant peer 

,2016-02-08 17:56:59.082 ThaliTest[1482:2819086] jxcore: stopBroadcasting
,2016-02-08 17:56:59.084 ThaliTest[1482:2819086] THEMultipeerSession stopping peer
,2016-02-08 17:56:59.085 ThaliTest[1482:2819086] multipeer session: stop timer
,2016-02-08 17:56:59.088 ThaliTest[1482:2819086] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-08 17:56:59.566 ThaliTest[1482:2819086] jxcore: startBroadcasting
,2016-02-08 17:56:59.569 ThaliTest[1482:2819086] server: starting 1454950619565.1482.VpSvQQ==
2016-02-08 17:56:59.570 ThaliTest[1482:2819086] multipeer session: start timer: 0x18bcd260
2016-02-08 17:56:59.571 ThaliTest[1482:2819086] THEMultipeerSession in,itialized peer 1454950619565.1482
2016-02-08 17:56:59.571 ThaliTest[1482:2819086] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-02-08 17:57:01.402 ThaliTest[1482:2818717] client: found peer: 1454950619855.919.SaL/Jw==
2016-02-08 17:57:01.404 ThaliTest[1482:2819086] jxcore: connect 1454950619855.919.SaL/Jw==
2016-02-08 17:57:01.404 ThaliTest[1482:2819086] client session: conn,ect
2016-02-08 17:57:01.405 ThaliTest[1482:2819086] client session: stateChange:0->1 1454950619855.919.SaL/Jw==
,2016-02-08 17:57:02.634 ThaliTest[1482:2818717] multipeer session: reset timer
2016-02-08 17:57:02.634 ThaliTest[1482:2818717] multipeer session: stop timer
2016-02-08 17:57:02.634 ThaliTest[1482:2818717] multipeer session: start timer: 0x18bcd260
2016-,02-08 17:57:02.635 ThaliTest[1482:2818717] server session: connect
2016-02-08 17:57:02.635 ThaliTest[1482:2818717] server session: stateChange:0->1 1454950619855.919
,2016-02-08 17:57:02.643 ThaliTest[1482:2818717] server: accepting invitation 1454950619855.919
,2016-02-08 17:57:05.199 ThaliTest[1482:2819650] server session: connected
2016-02-08 17:57:05.199 ThaliTest[1482:2819650] server session: stateChange:1->2 1454950619855.919
,2016-02-08 17:57:05.340 ThaliTest[1482:2819643] server session: not connected 1454950619855.919
,2016-02-08 17:57:05.343 ThaliTest[1482:2818717] server relay: socket disconnected
2016-02-08 17:57:05.344 ThaliTest[1482:2818717] server relay: 0x18bbb370 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-08 17:57:05.617 ThaliTest[1482:2819650] client session: connected
2016-02-08 17:57:05.617 ThaliTest[1482:2819650] client session: stateChange:1->2 1454950619855.919.SaL/Jw==
,2016-02-08 17:57:05.664 ThaliTest[1482:2819643] client session: fireConnectCallback: 1454950619855.919.SaL/Jw==
2016-02-08 17:57:05.664 ThaliTest[1482:2819643] jxcore: connect: success
,ok 84 Should be able to connect without error

ok 85 Port should be within range

,2016-02-08 17:57:05.669 ThaliTest[1482:2819086] jxcore: disconnect
2016-02-08 17:57:05.670 ThaliTest[1482:2819086] client session: disconnectFromPeer: 1454950619855.919.SaL/Jw==
2016-02-08 17:57:05.670 ThaliTest[1482:2819086] client session: disconnect
,2016-02-08 17:57:05.671 ThaliTest[1482:2819086] client session: stateChange:2->0 1454950619855.919.SaL/Jw==
,2016-02-08 17:57:05.684 ThaliTest[1482:2819086] jxcore: disconnect: success
ok 86 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-08 17:57:06.318 ThaliTest[1482:2819086] jxcore: stopBroadcasting
2016-02-08 17:57:06.318 ThaliTest[1482:2819086] THEMultipeerSession stopping peer
2016-02-08 17:57:06.319 ThaliTest[1482:2819086] multipeer session: stop timer
2016-02-08 17:57:06.,319 ThaliTest[1482:2819086] server session: disconnect
2016-02-08 17:57:06.319 ThaliTest[1482:2819086] server session: stateChange:2->0 1454950619855.919
2016-02-08 17:57:06.320 ThaliTest[1482:2819086] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-08 17:57:06.471 ThaliTest[1482:2819086] jxcore: startBroadcasting
,2016-02-08 17:57:06.475 ThaliTest[1482:2819086] server: starting 1454950626470.1482.JNUGZg==
,2016-02-08 17:57:06.478 ThaliTest[1482:2819086] multipeer session: start timer: 0x18bd1a80
,2016-02-08 17:57:06.485 ThaliTest[1482:2819086] THEMultipeerSession initialized peer 1454950626470.1482
,2016-02-08 17:57:06.488 ThaliTest[1482:2819086] jxcore: startBroadcasting: success
,ok 87 Should be able to call startBroadcasting without error

,2016-02-08 17:57:07.458 ThaliTest[1482:2818717] client: found peer: 1454950619855.919.SaL/Jw==
2016-02-08 17:57:07.459 ThaliTest[1482:2819086] jxcore: connect 1454950619855.919.SaL/Jw==
2016-02-08 17:57:07.460 ThaliTest[1482:2819086] client session: conn,ect
2016-02-08 17:57:07.460 ThaliTest[1482:2819086] client session: stateChange:0->1 1454950619855.919.SaL/Jw==
,2016-02-08 17:57:07.668 ThaliTest[1482:2818717] client: lost peer: 1454950619855.919.SaL/Jw==
2016-02-08 17:57:07.668 ThaliTest[1482:2818717] client session: onPeerLost: 1454950619855.919.SaL/Jw==
2016-02-08 17:57:07.668 ThaliTest[1482:2818717] client se,ssion: onLinkFailure: 1454950619855.919.SaL/Jw==
2016-02-08 17:57:07.669 ThaliTest[1482:2818717] client session: disconnect
2016-02-08 17:57:07.669 ThaliTest[1482:2818717] client session: stateChange:1->0 1454950619855.919.SaL/Jw==
2016-02-08 17:57:07.6,69 ThaliTest[1482:2818717] client session: fireConnectCallback: 1454950619855.919.SaL/Jw==
2016-02-08 17:57:07.670 ThaliTest[1482:2818717] jxcore: connect: fail: Peer disconnected
,2016-02-08 17:57:07.688 ThaliTest[1482:2818717] client: found peer: 1454950626746.919.9GyzhA==
2016-02-08 17:57:07.693 ThaliTest[1482:2819086] jxcore: connect 1454950626746.919.9GyzhA==
2016-02-08 17:57:07.693 ThaliTest[1482:2819086] client session: connect
2016-02-08 17:57:07.694 ThaliTest[1482:2819086] client session: stateChange:0->1 1454950626746.919.9GyzhA==
,2016-02-08 17:57:07.731 ThaliTest[1482:2818717] multipeer session: reset timer
2016-02-08 17:57:07.731 ThaliTest[1482:2818717] multipeer session: stop timer
2016-02-08 17:57:07.732 ThaliTest[1482:2818717] multipeer session: start timer: 0x18bd1a80
2016-02-08 17:57:07.732 ThaliTest[1482:2818717] server session: connect
2016-02-08 17:57:07.732 ThaliTest[1482:2818717] server session: stateChange:0->1 1454950626746.919
,2016-02-08 17:57:07.748 ThaliTest[1482:2818717] server: accepting invitation 1454950626746.919
,2016-02-08 17:57:08.678 ThaliTest[1482:2819086] jxcore: connect 1454950619855.919.SaL/Jw==
2016-02-08 17:57:08.679 ThaliTest[1482:2819086] client: connect: unreachable 1454950619855.919.SaL/Jw==
2016-02-08 17:57:08.679 ThaliTest[1482:2819086] jxcore: connect: fail: Peer unreachable
,2016-02-08 17:57:10.450 ThaliTest[1482:2819650] client session: connected
,2016-02-08 17:57:10.450 ThaliTest[1482:2819650] client session: stateChange:1->2 1454950626746.919.9GyzhA==
,2016-02-08 17:57:10.460 ThaliTest[1482:2819650] server session: connected
,2016-02-08 17:57:10.460 ThaliTest[1482:2819650] server session: stateChange:1->2 1454950626746.919
,2016-02-08 17:57:10.477 ThaliTest[1482:2819650] client session: fireConnectCallback: 1454950626746.919.9GyzhA==
,2016-02-08 17:57:10.479 ThaliTest[1482:2819650] jxcore: connect: success
,ok 88 Should be able to connect without error

,ok 89 Port should be within range

,2016-02-08 17:57:10.485 ThaliTest[1482:2819086] jxcore: connect 1454950626746.919.9GyzhA==
,2016-02-08 17:57:10.486 ThaliTest[1482:2819086] client: already connect(ing/ed) to 1454950626746.919.9GyzhA==
,2016-02-08 17:57:10.488 ThaliTest[1482:2819086] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

,2016-02-08 17:57:10.493 ThaliTest[1482:2819086] jxcore: disconnect
,2016-02-08 17:57:10.494 ThaliTest[1482:2819086] client session: disconnectFromPeer: 1454950626746.919.9GyzhA==
,2016-02-08 17:57:10.496 ThaliTest[1482:2819086] client session: disconnect
,2016-02-08 17:57:10.497 ThaliTest[1482:2819086] client session: stateChange:2->0 1454950626746.919.9GyzhA==
,2016-02-08 17:57:10.518 ThaliTest[1482:2818717] server relay: socket disconnected
,2016-02-08 17:57:10.519 ThaliTest[1482:2818717] server relay: 0x17bf0910 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection ,refused} 
,2016-02-08 17:57:10.528 ThaliTest[1482:2819086] jxcore: disconnect: success
,ok 91 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-08 17:57:10.657 ThaliTest[1482:2819086] jxcore: stopBroadcasting
,2016-02-08 17:57:10.657 ThaliTest[1482:2819086] THEMultipeerSession stopping peer
,2016-02-08 17:57:10.658 ThaliTest[1482:2819086] multipeer session: stop timer
,2016-02-08 17:57:10.661 ThaliTest[1482:2819086] server session: disconnect
,2016-02-08 17:57:10.662 ThaliTest[1482:2819086] server session: stateChange:2->0 1454950626746.919
,2016-02-08 17:57:10.755 ThaliTest[1482:2819086] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-08 17:57:11.694 ThaliTest[1482:2819086] jxcore: startBroadcasting
,2016-02-08 17:57:11.698 ThaliTest[1482:2819086] server: starting 1454950631694.1482.2LX/7A==
2016-02-08 17:57:11.698 ThaliTest[1482:2819086] multipeer session: start timer: 0x17c9b840
2016-02-08 17:57:11.699 ThaliTest[1482:2819086] THEMultipeerSession in,itialized peer 1454950631694.1482
2016-02-08 17:57:11.699 ThaliTest[1482:2819086] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-08 17:57:12.898 ThaliTest[1482:2818717] client: found peer: 1454950631889.919.NlWxwg==
2016-02-08 17:57:12.899 ThaliTest[1482:2819086] jxcore: connect 1454950631889.919.NlWxwg==
2016-02-08 17:57:12.899 ThaliTest[1482:2819086] client session: connect
2016-02-08 17:57:12.900 ThaliTest[1482:2819086] client session: stateChange:0->1 1454950631889.919.NlWxwg==
,2016-02-08 17:57:13.056 ThaliTest[1482:2818717] multipeer session: reset timer
2016-02-08 17:57:13.057 ThaliTest[1482:2818717] multipeer session: stop timer
2016-02-08 17:57:13.057 ThaliTest[1482:2818717] multipeer session: start timer: 0x17c9b840
2016-,02-08 17:57:13.058 ThaliTest[1482:2818717] server session: connect
2016-02-08 17:57:13.058 ThaliTest[1482:2818717] server session: stateChange:0->1 1454950631889.919
,2016-02-08 17:57:13.068 ThaliTest[1482:2818717] server: accepting invitation 1454950631889.919
,2016-02-08 17:57:15.671 ThaliTest[1482:2819651] server session: connected
2016-02-08 17:57:15.671 ThaliTest[1482:2819651] server session: stateChange:1->2 1454950631889.919
,2016-02-08 17:57:15.688 ThaliTest[1482:2818717] server relay: socket disconnected
2016-02-08 17:57:15.689 ThaliTest[1482:2818717] server relay: 0x17c9fc40 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-08 17:57:15.715 ThaliTest[1482:2819643] server session: not connected 1454950631889.919
,2016-02-08 17:57:15.975 ThaliTest[1482:2819643] client session: connected
2016-02-08 17:57:15.976 ThaliTest[1482:2819643] client session: stateChange:1->2 1454950631889.919.NlWxwg==
,2016-02-08 17:57:16.006 ThaliTest[1482:2819697] client session: fireConnectCallback: 1454950631889.919.NlWxwg==
2016-02-08 17:57:16.007 ThaliTest[1482:2819697] jxcore: connect: success
,ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-08 17:57:16.011 ThaliTest[1482:2819086] jxcore: disconnect
,2016-02-08 17:57:16.013 ThaliTest[1482:2819086] client session: disconnectFromPeer: 1454950631889.919.NlWxwg==
,2016-02-08 17:57:16.014 ThaliTest[1482:2819086] client session: disconnect
,2016-02-08 17:57:16.015 ThaliTest[1482:2819086] client session: stateChange:2->0 1454950631889.919.NlWxwg==
,2016-02-08 17:57:16.026 ThaliTest[1482:2819086] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error

,2016-02-08 17:57:16.030 ThaliTest[1482:2819086] jxcore: disconnect
,2016-02-08 17:57:16.031 ThaliTest[1482:2819086] jxcore: disconnect: fail
,ok 96 Disconnect should fail 

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-08 17:57:16.418 ThaliTest[1482:2819086] jxcore: stopBroadcasting
2016-02-08 17:57:16.419 ThaliTest[1482:2819086] THEMultipeerSession stopping peer
2016-02-08 17:57:16.419 ThaliTest[1482:2819086] multipeer session: stop timer
2016-02-08 17:57:16.,420 ThaliTest[1482:2819086] server session: disconnect
2016-02-08 17:57:16.420 ThaliTest[1482:2819086] server session: stateChange:2->0 1454950631889.919
,2016-02-08 17:57:16.422 ThaliTest[1482:2819086] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 58359

,2016-02-08 17:57:18.025 ThaliTest[1482:2819086] jxcore: startBroadcasting
,2016-02-08 17:57:18.027 ThaliTest[1482:2819086] server: starting 1454950638025.1482.nOGF8A==
2016-02-08 17:57:18.027 ThaliTest[1482:2819086] multipeer session: start timer: 0x17c88300
2016-02-08 17:57:18.027 ThaliTest[1482:2819086] THEMultipeerSession initialized peer 1454950638025.1482
2016-02-08 17:57:18.027 ThaliTest[1482:2819086] jxcore: startBroadcasting: success
ok 97 Should be able to call startBroadcasting without error

,2016-02-08 17:57:19.209 ThaliTest[1482:2818717] client: found peer: 1454950638175.919.9EiIoQ==
2016-02-08 17:57:19.211 ThaliTest[1482:2819086] jxcore: connect 1454950638175.919.9EiIoQ==
2016-02-08 17:57:19.212 ThaliTest[1482:2819086] client session: conn,ect
2016-02-08 17:57:19.212 ThaliTest[1482:2819086] client session: stateChange:0->1 1454950638175.919.9EiIoQ==
,2016-02-08 17:57:19.683 ThaliTest[1482:2818717] multipeer session: reset timer
2016-02-08 17:57:19.683 ThaliTest[1482:2818717] multipeer session: stop timer
2016-02-08 17:57:19.684 ThaliTest[1482:2818717] multipeer session: start timer: 0x17c88300
,2016-02-08 17:57:19.684 ThaliTest[1482:2818717] server session: connect
2016-02-08 17:57:19.685 ThaliTest[1482:2818717] server session: stateChange:0->1 1454950638175.919
,2016-02-08 17:57:19.695 ThaliTest[1482:2818717] server: accepting invitation 1454950638175.919
,2016-02-08 17:57:22.226 ThaliTest[1482:2819697] client session: connected
,2016-02-08 17:57:22.227 ThaliTest[1482:2819697] client session: stateChange:1->2 1454950638175.919.9EiIoQ==
,2016-02-08 17:57:22.236 ThaliTest[1482:2819697] server session: connected
,2016-02-08 17:57:22.236 ThaliTest[1482:2819697] server session: stateChange:1->2 1454950638175.919
,2016-02-08 17:57:22.279 ThaliTest[1482:2819697] client session: fireConnectCallback: 1454950638175.919.9EiIoQ==
,2016-02-08 17:57:22.280 ThaliTest[1482:2818717] server relay: connected (to port: 58359)
,2016-02-08 17:57:22.281 ThaliTest[1482:2819697] jxcore: connect: success
,ok 98 Should be able to connect without error

,ok 99 Port should be within range
,
,2016-02-08 17:57:22.312 ThaliTest[1482:2818717] client: relay established
2016-02-08 17:57:22.312 ThaliTest[1482:2818717] client: new accepted socket: 0x1796f6e0
,data in 3285

,data in 5475

,data in 12045

,data in 38325

,data in 60225

,data in 125761

data in 131072

,ok 100 the test messages should be equal

,2016-02-08 17:57:23.190 ThaliTest[1482:2819086] jxcore: disconnect
,2016-02-08 17:57:23.191 ThaliTest[1482:2819086] client session: disconnectFromPeer: 1454950638175.919.9EiIoQ==
,2016-02-08 17:57:23.191 ThaliTest[1482:2819086] client session: disconnect
,2016-02-08 17:57:23.192 ThaliTest[1482:2819086] client session: stateChange:2->0 1454950638175.919.9EiIoQ==
,2016-02-08 17:57:23.258 ThaliTest[1482:2819086] jxcore: disconnect: success
,ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-08 17:57:23.680 ThaliTest[1482:2819086] jxcore: stopBroadcasting
2016-02-08 17:57:23.681 ThaliTest[1482:2819086] THEMultipeerSession stopping peer
2016-02-08 17:57:23.681 ThaliTest[1482:2819086] multipeer session: stop timer
2016-02-08 17:57:23.,682 ThaliTest[1482:2819086] server session: disconnect
2016-02-08 17:57:23.682 ThaliTest[1482:2819086] server session: stateChange:2->0 1454950638175.919
,2016-02-08 17:57:23.801 ThaliTest[1482:2819086] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 58365

,2016-02-08 17:57:25.668 ThaliTest[1482:2819086] jxcore: startBroadcasting
,2016-02-08 17:57:25.672 ThaliTest[1482:2819086] server: starting 1454950645667.1482.mZpgYA==
2016-02-08 17:57:25.672 ThaliTest[1482:2819086] multipeer session: start timer: 0x17c88130
,2016-02-08 17:57:25.673 ThaliTest[1482:2819086] THEMultipeerSession initialized peer 1454950645667.1482
2016-02-08 17:57:25.675 ThaliTest[1482:2819086] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-02-08 17:57:25.971 ThaliTest[1482:2818717] client: found peer: 1454950645083.919.WulMow==
[{"peerIdentifier":"1454950645083.919.WulMow==","peerName":"(null)","peerAvailable":true}]

,2016-02-08 17:57:25.973 ThaliTest[1482:2819086] jxcore: connect 1454950645083.919.WulMow==
,2016-02-08 17:57:25.974 ThaliTest[1482:2819086] client session: connect
,2016-02-08 17:57:25.975 ThaliTest[1482:2819086] client session: stateChange:0->1 1454950645083.919.WulMow==
,2016-02-08 17:57:26.604 ThaliTest[1482:2818717] multipeer session: reset timer
2016-02-08 17:57:26.605 ThaliTest[1482:2818717] multipeer session: stop timer
2016-02-08 17:57:26.605 ThaliTest[1482:2818717] multipeer session: start timer: 0x17c88130
2016-02-08 17:57:26.605 ThaliTest[1482:2818717] server session: connect
,2016-02-08 17:57:26.606 ThaliTest[1482:2818717] server session: stateChange:0->1 1454950645083.919
,2016-02-08 17:57:26.617 ThaliTest[1482:2818717] server: accepting invitation 1454950645083.919
,2016-02-08 17:57:28.606 ThaliTest[1482:2819643] client session: connected
2016-02-08 17:57:28.607 ThaliTest[1482:2819643] client session: stateChange:1->2 1454950645083.919.WulMow==
,2016-02-08 17:57:28.637 ThaliTest[1482:2819651] client session: fireConnectCallback: 1454950645083.919.WulMow==
2016-02-08 17:57:28.637 ThaliTest[1482:2819651] jxcore: connect: success
ok 103 Should be able to connect without error
,
,ok 104 Port should be within range

,ok 105 First connect should succeed

,2016-02-08 17:57:28.699 ThaliTest[1482:2818717] client: relay established
2016-02-08 17:57:28.701 ThaliTest[1482:2818717] client: new accepted socket: 0x1796e300
,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-02-08 17:57:28.771 ThaliTest[1482:2818717] client: socket closed
2016-02-08 17:57:28.771 ThaliTest[1482:2818717] client relay: socket disconnected
2016-02-08 17:57:28.772 ThaliTest[1482:2818717] client relay: 0x1796e300 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-08 17:57:28.772 ThaliTest[1482:2818717] client session: socket closed: 1454950645083.919.WulMow==
2016-02-08 1,7:57:28.772 ThaliTest[1482:2818717] client session: onLinkFailure: 1454950645083.919.WulMow==
2016-02-08 17:57:28.772 ThaliTest[1482:2818717] client session: disconnect
2016-02-08 17:57:28.773 ThaliTest[1482:2818717] client session: stateChange:2->0 1454950645083.919.WulMow==
,2016-02-08 17:57:28.786 ThaliTest[1482:2818717] client session: fireConnectionErrorEvent: 1454950645083.919.WulMow==
2016-02-08 17:57:28.790 ThaliTest[1482:2819086] jxcore: connect 1454950645083.919.WulMow==
2016-02-08 17:57:28.790 ThaliTest[1482:2819086] client session: connect
2016-02-08 17:57:28.790 ThaliTest[1482:2819086] client session: stateChange:0->1 1454950645083.919.WulMow==
,2016-02-08 17:57:29.126 ThaliTest[1482:2819647] server session: connected
2016-02-08 17:57:29.126 ThaliTest[1482:2819647] server session: stateChange:1->2 1454950645083.919
,2016-02-08 17:57:29.169 ThaliTest[1482:2818717] server relay: connected (to port: 58365)
,2016-02-08 17:57:29.336 ThaliTest[1482:2819647] server session: not connected 1454950645083.919
,2016-02-08 17:57:29.384 ThaliTest[1482:2818717] multipeer session: reset timer
2016-02-08 17:57:29.385 ThaliTest[1482:2818717] multipeer session: stop timer
2016-02-08 17:57:29.385 ThaliTest[1482:2818717] multipeer session: start timer: 0x17c88130
,2016-02-08 17:57:29.386 ThaliTest[1482:2818717] server: disconnecting to refresh session (1454950645083.919)
2016-02-08 17:57:29.387 ThaliTest[1482:2818717] server session: disconnect
2016-02-08 17:57:29.387 ThaliTest[1482:2818717] server session: stateC,hange:2->0 1454950645083.919
,2016-02-08 17:57:29.392 ThaliTest[1482:2818717] server session: connect
2016-02-08 17:57:29.392 ThaliTest[1482:2818717] server session: stateChange:0->1 1454950645083.919
,2016-02-08 17:57:29.408 ThaliTest[1482:2818717] server: accepting invitation 1454950645083.919
,2016-02-08 17:57:31.395 ThaliTest[1482:2819643] client session: connected
2016-02-08 17:57:31.396 ThaliTest[1482:2819643] client session: stateChange:1->2 1454950645083.919.WulMow==
,2016-02-08 17:57:31.412 ThaliTest[1482:2819651] client session: fireConnectCallback: 1454950645083.919.WulMow==
2016-02-08 17:57:31.413 ThaliTest[1482:2819651] jxcore: connect: success
ok 108 Should be able to connect without error

ok 109 Port should be within range

ok 110 Second connect should succeed

,2016-02-08 17:57:31.442 ThaliTest[1482:2818717] client: relay established
2016-02-08 17:57:31.443 ThaliTest[1482:2818717] client: new accepted socket: 0x1796e300
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-02-08 17:57:31.513 ThaliTest[1482:2818717] client: socket closed
2016-02-08 17:57:31.514 ThaliTest[1482:2818717] client relay: socket disconnected
2016-02-08 17:57:31.514 ThaliTest[1482:2818717] client relay: 0x1796e300 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-08 17:57:31.515 ThaliTest[1482:2818717] client session: socket closed: 1454950645083.919.WulMow==
2016-02-08 1,7:57:31.515 ThaliTest[1482:2818717] client session: onLinkFailure: 1454950645083.919.WulMow==
2016-02-08 17:57:31.515 ThaliTest[1482:2818717] client session: disconnect
2016-02-08 17:57:31.515 ThaliTest[1482:2818717] client session: stateChange:2->0 1454950645083.919.WulMow==
,2016-02-08 17:57:31.523 ThaliTest[1482:2818717] client session: fireConnectionErrorEvent: 1454950645083.919.WulMow==
,2016-02-08 17:57:31.926 ThaliTest[1482:2819697] server session: connected
2016-02-08 17:57:31.926 ThaliTest[1482:2819697] server session: stateChange:1->2 1454950645083.919
,2016-02-08 17:57:31.943 ThaliTest[1482:2818717] server relay: connected (to port: 58365)
,2016-02-08 17:57:32.063 ThaliTest[1482:2819647] server session: not connected 1454950645083.919
,calling stopBroadcasting

,2016-02-08 17:57:33.148 ThaliTest[1482:2819086] jxcore: stopBroadcasting
2016-02-08 17:57:33.148 ThaliTest[1482:2819086] THEMultipeerSession stopping peer
2016-02-08 17:57:33.148 ThaliTest[1482:2819086] multipeer session: stop timer
2016-02-08 17:57:33.,149 ThaliTest[1482:2819086] server session: disconnect
2016-02-08 17:57:33.149 ThaliTest[1482:2819086] server session: stateChange:2->0 1454950645083.919
2016-02-08 17:57:33.154 ThaliTest[1482:2819086] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/77943CA1-704E-458A-BAC7-E2B22588792C/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-02-08 17:57:33.635 ThaliTest[1482:2819086] jxcore: startBroadcasting
,2016-02-08 17:57:33.636 ThaliTest[1482:2819086] server: starting jU_ckbs6yVKCZOTnccdusw.TKXSWQ==
2016-02-08 17:57:33.637 ThaliTest[1482:2819086] multipeer session: start timer: 0x17d81e30
2016-02-08 17:57:33.637 ThaliTest[1482:2819086] THEMultipeerSession initialized peer jU_ckbs6yVKCZOTnccdusw
,2016-02-08 17:57:33.638 ThaliTest[1482:2819086] jxcore: startBroadcasting: success
ok 114 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 115 stopping event should occur in right order

About to call stopBroadcasting

2016-02-08 17:57:33.640 ThaliTest[1482:2819086] jxcore: stopBroadcasting
2016-02-08 17:57:33.640 ThaliTest[1482:2819086] THEMultipeerSession stopping peer
2016-02-08 17:57:33.640 ThaliTest[1482:2819086] multipeer session: stop timer
2016-02-08 17:57:33.640 ThaliTest[1482:2819086] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

ok 116 stopped event should occur in right order

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/77943CA1-704E-458A-BAC7-E2B22588792C/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-08 17:57:33.820 ThaliTest[1482:2819086] jxcore: startBroadcasting
,2016-02-08 17:57:33.822 ThaliTest[1482:2819086] server: starting jU_ckbs6yVKCZOTnccdusw.NjCt1A==
2016-02-08 17:57:33.822 ThaliTest[1482:2819086] multipeer session: start timer: 0x17c88a00
2016-02-08 17:57:33.823 ThaliTest[1482:2819086] THEMultipeerSession initialized peer jU_ckbs6yVKCZOTnccdusw
2016-02-08 17:57:33.823 ThaliTest[1482:2819086] jxcore: startBroadcasting: success
ok 117 getDeviceIdentity should not return an error

ok 118 deviceName should not be null

Now in TRM stop

State of this._,isStarted: true

About to call stopBroadcasting

2016-02-08 17:57:33.824 ThaliTest[1482:2819086] jxcore: stopBroadcasting
2016-02-08 17:57:33.824 ThaliTest[1482:2819086] THEMultipeerSession stopping peer
2016-02-08 17:57:33.825 ThaliTest[1482:2819086] multipeer session: stop timer
2016-02-08 17:57:33.825 ThaliTest[1482:2819086] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/77943CA1-704E-458A-BAC7-E2B22588792C/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-08 17:57:35.834 ThaliTest[1482:2819086] jxcore: startBroadcasting
,2016-02-08 17:57:35.836 ThaliTest[1482:2819086] server: starting jU_ckbs6yVKCZOTnccdusw.ol1x1Q==
2016-02-08 17:57:35.836 ThaliTest[1482:2819086] multipeer session: start timer: 0x17d9bc70
2016-02-08 17:57:35.836 ThaliTest[1482:2819086] THEMultipeerSession initialized peer jU_ckbs6yVKCZOTnccdusw
,2016-02-08 17:57:35.837 ThaliTest[1482:2819086] jxcore: startBroadcasting: success
ok 119 getDeviceIdentity should not return an error

ok 120 deviceName should not be null

,2016-02-08 17:57:36.423 ThaliTest[1482:2818717] client: found peer: 1454950645083.919.WulMow==
,2016-02-08 17:57:40.409 ThaliTest[1482:2818717] client: found peer: RwJLtZ5s_sJcUxQ5zha7Ng.rcLn1Q==
,2016-02-08 17:57:40.434 ThaliTest[1482:2819086] jxcore: connect 1454950645083.919.WulMow==
2016-02-08 17:57:40.434 ThaliTest[1482:2819086] client session: connect
2016-02-08 17:57:40.434 ThaliTest[1482:2819086] client session: stateChange:0->1 1454950645083.919.WulMow==
,2016-02-08 17:57:40.439 ThaliTest[1482:2819086] jxcore: connect RwJLtZ5s_sJcUxQ5zha7Ng.rcLn1Q==
2016-02-08 17:57:40.439 ThaliTest[1482:2819086] client session: connect
2016-02-08 17:57:40.439 ThaliTest[1482:2819086] client session: stateChange:0->1 RwJLt,Z5s_sJcUxQ5zha7Ng.rcLn1Q==
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-02-08 17:57:40.597 ThaliTest[1482:2818717] multipeer session: reset timer
2016-02-08 17:57:40.597 ThaliTest[1482:2818717] multipeer session: stop timer
2016-02-08 17:57:40.597 ThaliTest[1482:2818717] multipeer session: start timer: 0x17d9bc70
2016-02-08 17:57:40.597 ThaliTest[1482:2818717] server session: connect
2016-02-08 17:57:40.597 ThaliTest[1482:2818717] server session: stateChange:0->1 RwJLtZ5s_sJcUxQ5zha7Ng
,2016-02-08 17:57:40.601 ThaliTest[1482:2818717] server: accepting invitation RwJLtZ5s_sJcUxQ5zha7Ng
,2016-02-08 17:57:43.116 ThaliTest[1482:2819709] server session: connected
2016-02-08 17:57:43.117 ThaliTest[1482:2819709] server session: stateChange:1->2 RwJLtZ5s_sJcUxQ5zha7Ng
,server bridge: new client socket

2016-02-08 17:57:43.127 ThaliTest[1482:2818717] server relay: connected (to port: 58381)
,2016-02-08 17:57:44.609 ThaliTest[1482:2818717] client: lost peer: 1454950645083.919.WulMow==
2016-02-08 17:57:44.610 ThaliTest[1482:2818717] client session: onPeerLost: 1454950645083.919.WulMow==
,2016-02-08 17:57:44.610 ThaliTest[1482:2818717] client session: onLinkFailure: 1454950645083.919.WulMow==
2016-02-08 17:57:44.610 ThaliTest[1482:2818717] client session: disconnect
2016-02-08 17:57:44.610 ThaliTest[1482:2818717] client session: stateChange:1->0 1454950645083.919.WulMow==
,2016-02-08 17:57:44.615 ThaliTest[1482:2818717] client session: fireConnectCallback: 1454950645083.919.WulMow==
,2016-02-08 17:57:44.616 ThaliTest[1482:2818717] jxcore: connect: fail: Peer disconnected
,Connect error with error: Error: Peer disconnected

,2016-02-08 17:57:44.675 ThaliTest[1482:2819086] jxcore: disconnect
,2016-02-08 17:57:44.676 ThaliTest[1482:2819086] jxcore: disconnect: fail
,Disconnect error with error: Error: Not connected to specified peer

peerIdentifier not available 1454950645083.919.WulMow==
,
,2016-02-08 17:57:46.340 ThaliTest[1482:2819651] client session: connected
2016-02-08 17:57:46.340 ThaliTest[1482:2819651] client session: stateChange:1->2 RwJLtZ5s_sJcUxQ5zha7Ng.rcLn1Q==
,2016-02-08 17:57:46.381 ThaliTest[1482:2819697] client session: fireConnectCallback: RwJLtZ5s_sJcUxQ5zha7Ng.rcLn1Q==
2016-02-08 17:57:46.382 ThaliTest[1482:2819697] jxcore: connect: success
,2016-02-08 17:57:46.390 ThaliTest[1482:2818717] client: relay established
2016-02-08 17:57:46.391 ThaliTest[1482:2818717] client: new accepted socket: 0x1797c410
,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,ok 123 1st change of remote doc should contain remote id

,client bridge: new client socket

,ok 124 Can update remote doc without error

null

,{ ok: true,
  id: '733d5549-1274-4043-b531-99465afb3f87',
  rev: '2-7afd15df1bc246db0a7765201c39ea02' }

,ok 125 Remote changes occur in strict order

,client bridge: socket closed

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
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,Uncaught Promise Rejection: {"status":400}

,Trace: { [Error: ETIMEDOUT] status: 400 }
    at $3.prototype.trace@console.js:139:8
    at @/private/var/mobile/Containers/Bundle/Application/19044A95-A351-439A-B283-FB9EAE9A4B0F/ThaliTest.app/www/jxcore/lib/thali-tape.js:39:3
    at emit@events.js:98:,1
    at handlers.reject/<@/private/var/mobile/Containers/Bundle/Application/19044A95-A351-439A-B283-FB9EAE9A4B0F/ThaliTest.app/www/jxcore/node_modules/lie/lib/index.js:128:11
    at nextTick@/private/var/mobile/Containers/Bundle/Application/19044A95-A35,1-439A-B283-FB9EAE9A4B0F/ThaliTest.app/www/jxcore/node_modules/lie/node_modules/immediate/lib/index.js:61:7
    at $0a@node.js:917:1

,****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****


```
