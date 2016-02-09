#### Test 58380500306a2c5_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58380500306a2c5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/7D35A2F0-FB0A-4557-9D60-8431D693E8BF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/7D35A2F0-FB0A-4557-9D60-8431D693E8BF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58380500306a2c5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58380500306a2c5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AC2F0BEF-0D2D-494F-9BCF-3E2A6DCB2A1A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54013"
,(lldb)     command script import "/tmp/7D35A2F0-FB0A-4557-9D60-8431D693E8BF/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 23:48:51.798 ThaliTest[1727:3031668] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B5B9A5F6-0FA8-40E6-A143-8E463BBE3367/Library/Cookies/Cookies.binarycookies
,2016-02-09 23:48:52.227 ThaliTest[1727:3031668] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-09 23:48:52.228 ThaliTest[1727:3031668] Multi-tasking -> Device: YES, App: YES
,2016-02-09 23:48:52.238 ThaliTest[1727:3031668] Unlimited access to network resources
,2016-02-09 23:48:52.252 ThaliTest[1727:3031668] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 23:49:01.964 ThaliTest[1727:3031668] Resetting plugins due to page load.
,2016-02-09 23:49:05.434 ThaliTest[1727:3031668] Finished load of: file:///var/mobile/Containers/Bundle/Application/AC2F0BEF-0D2D-494F-9BCF-3E2A6DCB2A1A/ThaliTest.app/www/index.html
,2016-02-09 23:49:05.615 ThaliTest[1727:3031668] JXcore Cordova plugin initializing
2016-02-09 23:49:05.616 ThaliTest[1727:3032014] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AC2F0BEF-0D2D-494F-9BCF-3E2A6DCB2A1A/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AC2F0BEF-0D2D-494F-9BCF-3E2A6DCB2A1A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AC2F0BEF-0D2D-494F-9BCF-3E2A6DCB2A1A/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AC2F0BEF-0D2D-494F-9BCF-3E2A6DCB2A1A/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AC2F0BEF-0D2D-494F-9BCF-3E2A6DCB2A1A/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AC2F0BEF-0D2D-494F-9BCF-3E2A6DCB2A1A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AC2F0BEF-0D2D-494F-9BCF-3E2A6DCB2A1A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AC2F0BEF-0D2D-494F-9BCF-3E2A6DCB2A1A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AC2F0BEF-0D2D-494F-9BCF-3E2A6DCB2A1A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AC2F0BEF-0D2D-494F-9BCF-3E2A6DCB2A1A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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
,
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

# setup

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

ok 49 should be equal

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

,# #start should fail if called twice in a row

,# teardown

,ok 54 specific error should be received

,# setup

,# #startListeningForAdvertisements should fail if start not called

,# teardown

,ok 55 specific error should be returned

,# setup

,# should be able to call #stopListeningForAdvertisements many times

,# teardown

,ok 56 error should be null

,ok 57 error should be null

,# setup

,# should be able to call #startListeningForAdvertisements many times

,# teardown

,ok 58 error should be null

,ok 59 error should be null

,# setup

,# should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,ok 60 error should be null

,ok 61 error should be null

,# setup

,# #startUpdateAdvertisingAndListening should fail if start not called

,# teardown

,ok 62 specific error should be returned

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-02-09 23:53:52.744 ThaliTest[1727:3032014] jxcore: startBroadcasting
,2016-02-09 23:53:52.760 ThaliTest[1727:3032014] server: starting 1455058432743.1727.XSqVCA==
2016-02-09 23:53:52.761 ThaliTest[1727:3032014] multipeer session: start timer: 0x1901b9c0
2016-02-09 23:53:52.762 ThaliTest[1727:3032014] THEMultipeerSession in,itialized peer 1455058432743.1727
2016-02-09 23:53:52.762 ThaliTest[1727:3032014] jxcore: startBroadcasting: success
ok 63 Should be able to call startBroadcasting without error

2016-02-09 23:53:52.765 ThaliTest[1727:3032014] jxcore: stopBroadcasting,
2016-02-09 23:53:52.765 ThaliTest[1727:3032014] THEMultipeerSession stopping peer
,2016-02-09 23:53:52.766 ThaliTest[1727:3032014] multipeer session: stop timer
2016-02-09 23:53:52.769 ThaliTest[1727:3032014] jxcore: stopBroadcasting: success
ok 64 Should be able to call stopBroadcasting without error

,2016-02-09 23:53:52.773 ThaliTest[1727:3032014] jxcore: startBroadcasting
,2016-02-09 23:53:52.784 ThaliTest[1727:3032014] server: starting 1455058432771.1727.eM+pHA==
,2016-02-09 23:53:52.791 ThaliTest[1727:3032014] multipeer session: start timer: 0x191e1fc0
,2016-02-09 23:53:52.794 ThaliTest[1727:3032014] THEMultipeerSession initialized peer 1455058432771.1727
,2016-02-09 23:53:52.797 ThaliTest[1727:3032014] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
,
,2016-02-09 23:53:52.802 ThaliTest[1727:3032014] jxcore: stopBroadcasting
,2016-02-09 23:53:52.804 ThaliTest[1727:3032014] THEMultipeerSession stopping peer
,2016-02-09 23:53:52.807 ThaliTest[1727:3032014] multipeer session: stop timer
,2016-02-09 23:53:52.809 ThaliTest[1727:3032014] jxcore: stopBroadcasting: success
,ok 66 Should be able to call stopBroadcasting without error

,2016-02-09 23:53:52.816 ThaliTest[1727:3032014] jxcore: startBroadcasting
,2016-02-09 23:53:52.820 ThaliTest[1727:3032014] server: starting 1455058432816.1727.2CdlVw==
,2016-02-09 23:53:52.823 ThaliTest[1727:3032014] multipeer session: start timer: 0x191e2360
,2016-02-09 23:53:52.831 ThaliTest[1727:3032014] THEMultipeerSession initialized peer 1455058432816.1727
,2016-02-09 23:53:52.832 ThaliTest[1727:3032014] jxcore: startBroadcasting: success
,ok 67 Should be able to call startBroadcasting without error

,2016-02-09 23:53:52.836 ThaliTest[1727:3032014] jxcore: stopBroadcasting
,2016-02-09 23:53:52.838 ThaliTest[1727:3032014] THEMultipeerSession stopping peer
,2016-02-09 23:53:52.839 ThaliTest[1727:3032014] multipeer session: stop timer
,2016-02-09 23:53:52.842 ThaliTest[1727:3032014] jxcore: stopBroadcasting: success
,ok 68 Should be able to call stopBroadcasting without error

,2016-02-09 23:53:52.848 ThaliTest[1727:3032014] jxcore: startBroadcasting
,2016-02-09 23:53:52.852 ThaliTest[1727:3032014] server: starting 1455058432848.1727.CCOMGg==
,2016-02-09 23:53:52.853 ThaliTest[1727:3032014] multipeer session: start timer: 0x194f34b0
,2016-02-09 23:53:52.859 ThaliTest[1727:3032014] THEMultipeerSession initialized peer 1455058432848.1727
,2016-02-09 23:53:52.859 ThaliTest[1727:3032014] jxcore: startBroadcasting: success
,ok 69 Should be able to call startBroadcasting without error

,2016-02-09 23:53:52.862 ThaliTest[1727:3032014] jxcore: stopBroadcasting
,2016-02-09 23:53:52.863 ThaliTest[1727:3032014] THEMultipeerSession stopping peer
,2016-02-09 23:53:52.863 ThaliTest[1727:3032014] multipeer session: stop timer
,2016-02-09 23:53:52.865 ThaliTest[1727:3032014] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error

,2016-02-09 23:53:52.869 ThaliTest[1727:3032014] jxcore: startBroadcasting
,2016-02-09 23:53:52.872 ThaliTest[1727:3032014] server: starting 1455058432869.1727.Ynj3Gg==
,2016-02-09 23:53:52.874 ThaliTest[1727:3032014] multipeer session: start timer: 0x1914dfd0
,2016-02-09 23:53:52.880 ThaliTest[1727:3032014] THEMultipeerSession initialized peer 1455058432869.1727
,2016-02-09 23:53:52.881 ThaliTest[1727:3032014] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error

,2016-02-09 23:53:52.883 ThaliTest[1727:3032014] jxcore: stopBroadcasting
,2016-02-09 23:53:52.884 ThaliTest[1727:3032014] THEMultipeerSession stopping peer
,2016-02-09 23:53:52.885 ThaliTest[1727:3032014] multipeer session: stop timer
,2016-02-09 23:53:52.887 ThaliTest[1727:3032014] jxcore: stopBroadcasting: success
,ok 72 Should be able to call stopBroadcasting without error

,2016-02-09 23:53:52.892 ThaliTest[1727:3032014] jxcore: startBroadcasting
,2016-02-09 23:53:52.895 ThaliTest[1727:3032014] server: starting 1455058432892.1727.7F3s4w==
,2016-02-09 23:53:52.897 ThaliTest[1727:3032014] multipeer session: start timer: 0x194f3580
,2016-02-09 23:53:52.902 ThaliTest[1727:3032014] THEMultipeerSession initialized peer 1455058432892.1727
,2016-02-09 23:53:52.904 ThaliTest[1727:3032014] jxcore: startBroadcasting: success
,ok 73 Should be able to call startBroadcasting without error

,2016-02-09 23:53:52.906 ThaliTest[1727:3032014] jxcore: stopBroadcasting
,2016-02-09 23:53:52.907 ThaliTest[1727:3032014] THEMultipeerSession stopping peer
,2016-02-09 23:53:52.907 ThaliTest[1727:3032014] multipeer session: stop timer
,2016-02-09 23:53:52.909 ThaliTest[1727:3032014] jxcore: stopBroadcasting: success
,ok 74 Should be able to call stopBroadcasting without error

,2016-02-09 23:53:52.914 ThaliTest[1727:3032014] jxcore: startBroadcasting
,2016-02-09 23:53:52.917 ThaliTest[1727:3032014] server: starting 1455058432914.1727.JpGohA==
,2016-02-09 23:53:52.918 ThaliTest[1727:3032014] multipeer session: start timer: 0x194f30b0
,2016-02-09 23:53:52.920 ThaliTest[1727:3032014] THEMultipeerSession initialized peer 1455058432914.1727
,2016-02-09 23:53:52.925 ThaliTest[1727:3032014] jxcore: startBroadcasting: success
,ok 75 Should be able to call startBroadcasting without error

,2016-02-09 23:53:52.928 ThaliTest[1727:3032014] jxcore: stopBroadcasting
,2016-02-09 23:53:52.929 ThaliTest[1727:3032014] THEMultipeerSession stopping peer
,2016-02-09 23:53:52.929 ThaliTest[1727:3032014] multipeer session: stop timer
,2016-02-09 23:53:52.930 ThaliTest[1727:3032014] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,2016-02-09 23:53:52.936 ThaliTest[1727:3032014] jxcore: startBroadcasting
,2016-02-09 23:53:52.939 ThaliTest[1727:3032014] server: starting 1455058432935.1727.iBfksw==
,2016-02-09 23:53:52.941 ThaliTest[1727:3032014] multipeer session: start timer: 0x194f4980
,2016-02-09 23:53:52.945 ThaliTest[1727:3032014] THEMultipeerSession initialized peer 1455058432935.1727
,2016-02-09 23:53:52.947 ThaliTest[1727:3032014] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

,2016-02-09 23:53:52.950 ThaliTest[1727:3032014] jxcore: stopBroadcasting
,2016-02-09 23:53:52.950 ThaliTest[1727:3032014] THEMultipeerSession stopping peer
,2016-02-09 23:53:52.951 ThaliTest[1727:3032014] multipeer session: stop timer
,2016-02-09 23:53:52.951 ThaliTest[1727:3032014] jxcore: stopBroadcasting: success
,ok 78 Should be able to call stopBroadcasting without error

,2016-02-09 23:53:52.955 ThaliTest[1727:3032014] jxcore: startBroadcasting
,2016-02-09 23:53:52.958 ThaliTest[1727:3032014] server: starting 1455058432955.1727.NhfkoQ==
,2016-02-09 23:53:52.958 ThaliTest[1727:3032014] multipeer session: start timer: 0x194f52d0
,2016-02-09 23:53:52.960 ThaliTest[1727:3032014] THEMultipeerSession initialized peer 1455058432955.1727
,2016-02-09 23:53:52.962 ThaliTest[1727:3032014] jxcore: startBroadcasting: success
,ok 79 Should be able to call startBroadcasting without error

,2016-02-09 23:53:52.965 ThaliTest[1727:3032014] jxcore: stopBroadcasting
,2016-02-09 23:53:52.966 ThaliTest[1727:3032014] THEMultipeerSession stopping peer
,2016-02-09 23:53:52.966 ThaliTest[1727:3032014] multipeer session: stop timer
,2016-02-09 23:53:52.967 ThaliTest[1727:3032014] jxcore: stopBroadcasting: success
,ok 80 Should be able to call stopBroadcasting without error
,
,2016-02-09 23:53:52.971 ThaliTest[1727:3032014] jxcore: startBroadcasting
,2016-02-09 23:53:52.973 ThaliTest[1727:3032014] server: starting 1455058432971.1727.xKcNsA==
,2016-02-09 23:53:52.974 ThaliTest[1727:3032014] multipeer session: start timer: 0x194f61a0
,2016-02-09 23:53:52.977 ThaliTest[1727:3032014] THEMultipeerSession initialized peer 1455058432971.1727
,2016-02-09 23:53:52.978 ThaliTest[1727:3032014] jxcore: startBroadcasting: success
,ok 81 Should be able to call startBroadcasting without error

,2016-02-09 23:53:52.981 ThaliTest[1727:3032014] jxcore: stopBroadcasting
,2016-02-09 23:53:52.982 ThaliTest[1727:3032014] THEMultipeerSession stopping peer
,2016-02-09 23:53:52.982 ThaliTest[1727:3032014] multipeer session: stop timer
,2016-02-09 23:53:52.983 ThaliTest[1727:3032014] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-09 23:53:53.243 ThaliTest[1727:3032014] jxcore: startBroadcasting
,2016-02-09 23:53:53.247 ThaliTest[1727:3032014] server: starting 1455058433242.1727.RGXRxw==
,2016-02-09 23:53:53.250 ThaliTest[1727:3032014] multipeer session: start timer: 0x193c0150
,2016-02-09 23:53:53.258 ThaliTest[1727:3032014] THEMultipeerSession initialized peer 1455058433242.1727
,2016-02-09 23:53:53.259 ThaliTest[1727:3032014] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error

,2016-02-09 23:53:53.264 ThaliTest[1727:3032014] jxcore: startBroadcasting
,2016-02-09 23:53:53.266 ThaliTest[1727:3032014] jxcore: startBroadcasting: failure
,ok 84 Cannot call startBroadcasting twice

,2016-02-09 23:53:53.271 ThaliTest[1727:3032014] jxcore: stopBroadcasting
,2016-02-09 23:53:53.272 ThaliTest[1727:3032014] THEMultipeerSession stopping peer
,2016-02-09 23:53:53.274 ThaliTest[1727:3032014] multipeer session: stop timer
,2016-02-09 23:53:53.280 ThaliTest[1727:3032014] jxcore: stopBroadcasting: success
,ok 85 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-09 23:53:54.611 ThaliTest[1727:3032014] jxcore: startBroadcasting
,2016-02-09 23:53:54.615 ThaliTest[1727:3032014] server: starting 1455058434611.1727.io6khw==
2016-02-09 23:53:54.616 ThaliTest[1727:3032014] multipeer session: start timer: 0x18474060
2016-02-09 23:53:54.616 ThaliTest[1727:3032014] THEMultipeerSession in,itialized peer 1455058434611.1727
2016-02-09 23:53:54.617 ThaliTest[1727:3032014] jxcore: startBroadcasting: success
ok 86 Should be able to call startBroadcasting without error

2016-02-09 23:53:54.619 ThaliTest[1727:3032014] jxcore: connect foobar
2,016-02-09 23:53:54.619 ThaliTest[1727:3032014] client: unknown peer foobar
2016-02-09 23:53:54.620 ThaliTest[1727:3032014] jxcore: connect: fail: Unknown peer
ok 87 Should not connect to a bad peer

,2016-02-09 23:53:54.623 ThaliTest[1727:3032014] jxcore: stopBroadcasting
2016-02-09 23:53:54.623 ThaliTest[1727:3032014] THEMultipeerSession stopping peer
2016-02-09 23:53:54.624 ThaliTest[1727:3032014] multipeer session: stop timer
,2016-02-09 23:53:54.625 ThaliTest[1727:3032014] jxcore: stopBroadcasting: success
,ok 88 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-09 23:54:01.523 ThaliTest[1727:3032014] jxcore: startBroadcasting
,2016-02-09 23:54:01.527 ThaliTest[1727:3032014] server: starting 1455058441522.1727.VqoSpQ==
2016-02-09 23:54:01.528 ThaliTest[1727:3032014] multipeer session: start timer: 0x19461740
2016-02-09 23:54:01.528 ThaliTest[1727:3032014] THEMultipeerSession in,itialized peer 1455058441522.1727
2016-02-09 23:54:01.529 ThaliTest[1727:3032014] jxcore: startBroadcasting: success
ok 89 Should be able to call startBroadcasting without error

,2016-02-09 23:54:01.531 ThaliTest[1727:3032014] jxcore: disconnect
2016-02-09 23:54:01.532 ThaliTest[1727:3032014] jxcore: disconnect: fail
ok 90 Disconnect should fail to a non-existant peer 

2016-02-09 23:54:01.536 ThaliTest[1727:3032014] jxcore: st,opBroadcasting
2016-02-09 23:54:01.536 ThaliTest[1727:3032014] THEMultipeerSession stopping peer
2016-02-09 23:54:01.537 ThaliTest[1727:3032014] multipeer session: stop timer
,2016-02-09 23:54:01.537 ThaliTest[1727:3032014] jxcore: stopBroadcasting: success
ok 91 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-09 23:54:04.753 ThaliTest[1727:3032014] jxcore: startBroadcasting
,2016-02-09 23:54:04.756 ThaliTest[1727:3032014] server: starting 1455058444752.1727.XtjAGw==
2016-02-09 23:54:04.757 ThaliTest[1727:3032014] multipeer session: start timer: 0x184732d0
2016-02-09 23:54:04.757 ThaliTest[1727:3032014] THEMultipeerSession in,itialized peer 1455058444752.1727
2016-02-09 23:54:04.757 ThaliTest[1727:3032014] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-09 23:54:06.083 ThaliTest[1727:3031668] client: found peer: 1455058446871.1230.Aoz4Cg==
,2016-02-09 23:54:06.086 ThaliTest[1727:3032014] jxcore: connect 1455058446871.1230.Aoz4Cg==
2016-02-09 23:54:06.087 ThaliTest[1727:3032014] client session: connect
2016-02-09 23:54:06.088 ThaliTest[1727:3032014] client session: stateChange:0->1 1455058446871.1230.Aoz4Cg==
,2016-02-09 23:54:06.552 ThaliTest[1727:3031668] multipeer session: reset timer
2016-02-09 23:54:06.552 ThaliTest[1727:3031668] multipeer session: stop timer
2016-02-09 23:54:06.552 ThaliTest[1727:3031668] multipeer session: start timer: 0x184732d0
2016-,02-09 23:54:06.553 ThaliTest[1727:3031668] server session: connect
2016-02-09 23:54:06.553 ThaliTest[1727:3031668] server session: stateChange:0->1 1455058446871.1230
,2016-02-09 23:54:06.563 ThaliTest[1727:3031668] server: accepting invitation 1455058446871.1230
,2016-02-09 23:54:08.979 ThaliTest[1727:3032508] client session: connected
2016-02-09 23:54:08.979 ThaliTest[1727:3032508] client session: stateChange:1->2 1455058446871.1230.Aoz4Cg==
,2016-02-09 23:54:09.014 ThaliTest[1727:3032539] client session: fireConnectCallback: 1455058446871.1230.Aoz4Cg==
2016-02-09 23:54:09.015 ThaliTest[1727:3032539] jxcore: connect: success
ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-09 23:54:09.020 ThaliTest[1727:3032014] jxcore: disconnect
2016-02-09 23:54:09.020 ThaliTest[1727:3032014] client session: disconnectFromPeer: 1455058446871.1230.Aoz4Cg==
2016-02-09 23:54:09.021 ThaliTest[1727:3032014] client session: disconnect,
2016-02-09 23:54:09.021 ThaliTest[1727:3032014] client session: stateChange:2->0 1455058446871.1230.Aoz4Cg==
,2016-02-09 23:54:09.032 ThaliTest[1727:3032014] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 23:54:09.118 ThaliTest[1727:3032506] server session: connected
,2016-02-09 23:54:09.119 ThaliTest[1727:3032506] server session: stateChange:1->2 1455058446871.1230
,2016-02-09 23:54:09.143 ThaliTest[1727:3031668] server relay: socket disconnected
,2016-02-09 23:54:09.144 ThaliTest[1727:3031668] server relay: 0x194f1d40 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 23:54:09.162 ThaliTest[1727:3032506] server session: not connected 1455058446871.1230
,calling stopBroadcasting

,2016-02-09 23:54:09.389 ThaliTest[1727:3032014] jxcore: stopBroadcasting
,2016-02-09 23:54:09.390 ThaliTest[1727:3032014] THEMultipeerSession stopping peer
2016-02-09 23:54:09.391 ThaliTest[1727:3032014] multipeer session: stop timer
2016-02-09 23:54:09.391 ThaliTest[1727:3032014] server session: disconnect
,2016-02-09 23:54:09.392 ThaliTest[1727:3032014] server session: stateChange:2->0 1455058446871.1230
2016-02-09 23:54:09.393 ThaliTest[1727:3032014] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-09 23:54:09.482 ThaliTest[1727:3032014] jxcore: startBroadcasting
,2016-02-09 23:54:09.485 ThaliTest[1727:3032014] server: starting 1455058449482.1727.JXtk8g==
,2016-02-09 23:54:09.489 ThaliTest[1727:3032014] multipeer session: start timer: 0x1852ad80
,2016-02-09 23:54:09.494 ThaliTest[1727:3032014] THEMultipeerSession initialized peer 1455058449482.1727
,2016-02-09 23:54:09.498 ThaliTest[1727:3032014] jxcore: startBroadcasting: success
,ok 96 Should be able to call startBroadcasting without error
,2016-02-09 23:54:09.507 ThaliTest[1727:3031668] client: found peer: 1455058444752.1727.XtjAGw==

,2016-02-09 23:54:09.509 ThaliTest[1727:3031668] client: found peer: 1455058446871.1230.Aoz4Cg==
,2016-02-09 23:54:09.516 ThaliTest[1727:3032014] jxcore: connect 1455058444752.1727.XtjAGw==
,2016-02-09 23:54:09.517 ThaliTest[1727:3032014] client session: connect
,2016-02-09 23:54:09.518 ThaliTest[1727:3032014] client session: stateChange:0->1 1455058444752.1727.XtjAGw==
,2016-02-09 23:54:09.728 ThaliTest[1727:3032014] jxcore: connect 1455058446871.1230.Aoz4Cg==
2016-02-09 23:54:09.728 ThaliTest[1727:3032014] client session: connect
2016-02-09 23:54:09.729 ThaliTest[1727:3032014] client session: stateChange:0->1 1455058446871.1230.Aoz4Cg==
,2016-02-09 23:54:10.623 ThaliTest[1727:3031668] client: lost peer: 1455058444752.1727.XtjAGw==
2016-02-09 23:54:10.624 ThaliTest[1727:3031668] client session: onPeerLost: 1455058444752.1727.XtjAGw==
2016-02-09 23:54:10.624 ThaliTest[1727:3031668] client ,session: onLinkFailure: 1455058444752.1727.XtjAGw==
2016-02-09 23:54:10.624 ThaliTest[1727:3031668] client session: disconnect
2016-02-09 23:54:10.624 ThaliTest[1727:3031668] client session: stateChange:1->0 1455058444752.1727.XtjAGw==
2016-02-09 23:54:,10.625 ThaliTest[1727:3031668] client session: fireConnectCallback: 1455058444752.1727.XtjAGw==
2016-02-09 23:54:10.625 ThaliTest[1727:3031668] jxcore: connect: fail: Peer disconnected
,2016-02-09 23:54:10.630 ThaliTest[1727:3031668] client: lost peer: 1455058446871.1230.Aoz4Cg==
2016-02-09 23:54:10.630 ThaliTest[1727:3031668] client session: onPeerLost: 1455058446871.1230.Aoz4Cg==
2016-02-09 23:54:10.630 ThaliTest[1727:3031668] client ,session: onLinkFailure: 1455058446871.1230.Aoz4Cg==
2016-02-09 23:54:10.631 ThaliTest[1727:3031668] client session: disconnect
2016-02-09 23:54:10.631 ThaliTest[1727:3031668] client session: stateChange:1->0 1455058446871.1230.Aoz4Cg==
2016-02-09 23:54:,10.631 ThaliTest[1727:3031668] client session: fireConnectCallback: 1455058446871.1230.Aoz4Cg==
2016-02-09 23:54:10.632 ThaliTest[1727:3031668] jxcore: connect: fail: Peer disconnected
,2016-02-09 23:54:11.074 ThaliTest[1727:3031668] multipeer session: reset timer
2016-02-09 23:54:11.074 ThaliTest[1727:3031668] multipeer session: stop timer
2016-02-09 23:54:11.074 ThaliTest[1727:3031668] multipeer session: start timer: 0x1852ad80
2016-02-09 23:54:11.075 ThaliTest[1727:3031668] server session: connect
2016-02-09 23:54:11.075 ThaliTest[1727:3031668] server session: stateChange:0->1 1455058452278.1230
,2016-02-09 23:54:11.087 ThaliTest[1727:3031668] server: accepting invitation 1455058452278.1230
,2016-02-09 23:54:11.143 ThaliTest[1727:3031668] client: found peer: 1455058452278.1230.xZ+qZQ==
2016-02-09 23:54:11.144 ThaliTest[1727:3032014] jxcore: connect 1455058452278.1230.xZ+qZQ==
2016-02-09 23:54:11.144 ThaliTest[1727:3032014] client session: connect
2016-02-09 23:54:11.145 ThaliTest[1727:3032014] client session: stateChange:0->1 1455058452278.1230.xZ+qZQ==
,2016-02-09 23:54:11.639 ThaliTest[1727:3032014] jxcore: connect 1455058444752.1727.XtjAGw==
,2016-02-09 23:54:11.640 ThaliTest[1727:3032014] client: connect: unreachable 1455058444752.1727.XtjAGw==
2016-02-09 23:54:11.641 ThaliTest[1727:3032014] jxcore: connect: fail: Peer unreachable
2016-02-09 23:54:11.644 ThaliTest[1727:3032014] jxcore: connect 1455058446871.1230.Aoz4Cg==
2016-02-09 23:54:11.644 ThaliTest[1727:3032014] client: connect: unreachable 1455058446871.1230.Aoz4Cg==
2016-02-09 23:54:11.644 ThaliTest[1727:3032014] jxcore: connect: fail: Peer unreachable
,2016-02-09 23:54:13.604 ThaliTest[1727:3032510] server session: connected
,2016-02-09 23:54:13.604 ThaliTest[1727:3032510] server session: stateChange:1->2 1455058452278.1230
,2016-02-09 23:54:13.622 ThaliTest[1727:3031668] server relay: socket disconnected
2016-02-09 23:54:13.623 ThaliTest[1727:3031668] server relay: 0x184c17c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 23:54:13.665 ThaliTest[1727:3032510] server session: not connected 1455058452278.1230
,2016-02-09 23:54:13.797 ThaliTest[1727:3032510] client session: connected
2016-02-09 23:54:13.797 ThaliTest[1727:3032510] client session: stateChange:1->2 1455058452278.1230.xZ+qZQ==
,2016-02-09 23:54:13.811 ThaliTest[1727:3032508] client session: fireConnectCallback: 1455058452278.1230.xZ+qZQ==
2016-02-09 23:54:13.812 ThaliTest[1727:3032508] jxcore: connect: success
,ok 97 Should be able to connect without error

,ok 98 Port should be within range

,2016-02-09 23:54:13.817 ThaliTest[1727:3032014] jxcore: connect 1455058452278.1230.xZ+qZQ==
2016-02-09 23:54:13.818 ThaliTest[1727:3032014] client: already connect(ing/ed) to 1455058452278.1230.xZ+qZQ==
2016-02-09 23:54:13.818 ThaliTest[1727:3032014] jxcore: connect: fail: Aleady connecting
,ok 99 Should fail on double connect

,2016-02-09 23:54:13.822 ThaliTest[1727:3032014] jxcore: disconnect
2016-02-09 23:54:13.822 ThaliTest[1727:3032014] client session: disconnectFromPeer: 1455058452278.1230.xZ+qZQ==
2016-02-09 23:54:13.822 ThaliTest[1727:3032014] client session: disconnect
2016-02-09 23:54:13.823 ThaliTest[1727:3032014] client session: stateChange:2->0 1455058452278.1230.xZ+qZQ==
,2016-02-09 23:54:13.832 ThaliTest[1727:3032014] jxcore: disconnect: success
ok 100 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 23:54:14.103 ThaliTest[1727:3032014] jxcore: stopBroadcasting
2016-02-09 23:54:14.104 ThaliTest[1727:3032014] THEMultipeerSession stopping peer
2016-02-09 23:54:14.104 ThaliTest[1727:3032014] multipeer session: stop timer
2016-02-09 23:54:14.,105 ThaliTest[1727:3032014] server session: disconnect
2016-02-09 23:54:14.105 ThaliTest[1727:3032014] server session: stateChange:2->0 1455058452278.1230
2016-02-09 23:54:14.106 ThaliTest[1727:3032014] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-09 23:54:14.618 ThaliTest[1727:3032014] jxcore: startBroadcasting
,2016-02-09 23:54:14.621 ThaliTest[1727:3032014] server: starting 1455058454617.1727.2diA4Q==
2016-02-09 23:54:14.622 ThaliTest[1727:3032014] multipeer session: start timer: 0x18352f70
2016-02-09 23:54:14.622 ThaliTest[1727:3032014] THEMultipeerSession in,itialized peer 1455058454617.1727
2016-02-09 23:54:14.623 ThaliTest[1727:3032014] jxcore: startBroadcasting: success
ok 101 Should be able to call startBroadcasting without error

,2016-02-09 23:54:15.481 ThaliTest[1727:3031668] client: found peer: 1455058456496.1230.EiakUw==
2016-02-09 23:54:15.483 ThaliTest[1727:3032014] jxcore: connect 1455058456496.1230.EiakUw==
2016-02-09 23:54:15.483 ThaliTest[1727:3032014] client session: connect
2016-02-09 23:54:15.483 ThaliTest[1727:3032014] client session: stateChange:0->1 1455058456496.1230.EiakUw==
,2016-02-09 23:54:16.141 ThaliTest[1727:3031668] multipeer session: reset timer
2016-02-09 23:54:16.142 ThaliTest[1727:3031668] multipeer session: stop timer
2016-02-09 23:54:16.142 ThaliTest[1727:3031668] multipeer session: start timer: 0x18352f70
2016-02-09 23:54:16.143 ThaliTest[1727:3031668] server session: connect
2016-02-09 23:54:16.143 ThaliTest[1727:3031668] server session: stateChange:0->1 1455058456496.1230
2016-02-09 23:54:16.151 ThaliTest[1727:3031668] server: accepting invitation 1455058456496.1230
,2016-02-09 23:54:18.421 ThaliTest[1727:3032510] client session: connected
2016-02-09 23:54:18.421 ThaliTest[1727:3032510] client session: stateChange:1->2 1455058456496.1230.EiakUw==
,2016-02-09 23:54:18.448 ThaliTest[1727:3032506] client session: fireConnectCallback: 1455058456496.1230.EiakUw==
2016-02-09 23:54:18.448 ThaliTest[1727:3032506] jxcore: connect: success
,ok 102 Should be able to connect without error

,ok 103 Port should be within range

,2016-02-09 23:54:18.453 ThaliTest[1727:3032014] jxcore: disconnect
2016-02-09 23:54:18.453 ThaliTest[1727:3032014] client session: disconnectFromPeer: 1455058456496.1230.EiakUw==
2016-02-09 23:54:18.454 ThaliTest[1727:3032014] client session: disconnect,
2016-02-09 23:54:18.454 ThaliTest[1727:3032014] client session: stateChange:2->0 1455058456496.1230.EiakUw==
,2016-02-09 23:54:18.465 ThaliTest[1727:3032014] jxcore: disconnect: success
ok 104 Should be able to disconnect without error

2016-02-09 23:54:18.467 ThaliTest[1727:3032014] jxcore: disconnect
2016-02-09 23:54:18.468 ThaliTest[1727:3032014] jxcore: disconnect: fail
,ok 105 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 23:54:18.582 ThaliTest[1727:3032539] server session: connected
,2016-02-09 23:54:18.582 ThaliTest[1727:3032539] server session: stateChange:1->2 1455058456496.1230
,2016-02-09 23:54:18.595 ThaliTest[1727:3031668] server relay: socket disconnected
,2016-02-09 23:54:18.597 ThaliTest[1727:3031668] server relay: 0x16d1a5e0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 23:54:18.643 ThaliTest[1727:3032541] server session: not connected 1455058456496.1230
,calling stopBroadcasting

,2016-02-09 23:54:18.820 ThaliTest[1727:3032014] jxcore: stopBroadcasting
2016-02-09 23:54:18.820 ThaliTest[1727:3032014] THEMultipeerSession stopping peer
2016-02-09 23:54:18.821 ThaliTest[1727:3032014] multipeer session: stop timer
2016-02-09 23:54:18.,821 ThaliTest[1727:3032014] server session: disconnect
2016-02-09 23:54:18.822 ThaliTest[1727:3032014] server session: stateChange:2->0 1455058456496.1230
,2016-02-09 23:54:18.824 ThaliTest[1727:3032014] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 61115

,2016-02-09 23:54:20.001 ThaliTest[1727:3032014] jxcore: startBroadcasting
,2016-02-09 23:54:20.002 ThaliTest[1727:3032014] server: starting 1455058460000.1727.HGrj8A==
2016-02-09 23:54:20.002 ThaliTest[1727:3032014] multipeer session: start timer: 0x19459490
2016-02-09 23:54:20.003 ThaliTest[1727:3032014] THEMultipeerSession initialized peer 1455058460000.1727
2016-02-09 23:54:20.003 ThaliTest[1727:3032014] jxcore: startBroadcasting: success
ok 106 Should be able to call startBroadcasting without error

,2016-02-09 23:54:21.176 ThaliTest[1727:3031668] client: found peer: 1455058462031.1230.GLlCGQ==
2016-02-09 23:54:21.177 ThaliTest[1727:3032014] jxcore: connect 1455058462031.1230.GLlCGQ==
2016-02-09 23:54:21.178 ThaliTest[1727:3032014] client session: co,nnect
2016-02-09 23:54:21.178 ThaliTest[1727:3032014] client session: stateChange:0->1 1455058462031.1230.GLlCGQ==
,2016-02-09 23:54:21.426 ThaliTest[1727:3031668] multipeer session: reset timer
2016-02-09 23:54:21.426 ThaliTest[1727:3031668] multipeer session: stop timer
2016-02-09 23:54:21.427 ThaliTest[1727:3031668] multipeer session: start timer: 0x19459490
,2016-02-09 23:54:21.428 ThaliTest[1727:3031668] server session: connect
,2016-02-09 23:54:21.433 ThaliTest[1727:3031668] server session: stateChange:0->1 1455058462031.1230
,2016-02-09 23:54:21.446 ThaliTest[1727:3031668] server: accepting invitation 1455058462031.1230
,2016-02-09 23:54:23.874 ThaliTest[1727:3032539] client session: connected
,2016-02-09 23:54:23.874 ThaliTest[1727:3032539] client session: stateChange:1->2 1455058462031.1230.GLlCGQ==
,2016-02-09 23:54:23.897 ThaliTest[1727:3032541] server session: connected
,2016-02-09 23:54:23.897 ThaliTest[1727:3032541] server session: stateChange:1->2 1455058462031.1230
,2016-02-09 23:54:23.903 ThaliTest[1727:3032506] client session: fireConnectCallback: 1455058462031.1230.GLlCGQ==
,2016-02-09 23:54:23.905 ThaliTest[1727:3032506] jxcore: connect: success
,ok 107 Should be able to connect without error

,ok 108 Port should be within range

,2016-02-09 23:54:23.912 ThaliTest[1727:3031668] client: relay established
,2016-02-09 23:54:23.916 ThaliTest[1727:3031668] client: new accepted socket: 0x182f7060
,2016-02-09 23:54:23.934 ThaliTest[1727:3031668] server relay: connected (to port: 61115)
,data in 63510

,data in 69654
,
,data in 97455
,
,data in 107310
,
,data in 113880

,data in 116070

,data in 131072

,ok 109 the test messages should be equal

,2016-02-09 23:54:24.203 ThaliTest[1727:3032014] jxcore: disconnect
2016-02-09 23:54:24.203 ThaliTest[1727:3032014] client session: disconnectFromPeer: 1455058462031.1230.GLlCGQ==
,2016-02-09 23:54:24.203 ThaliTest[1727:3032014] client session: disconnect
,2016-02-09 23:54:24.203 ThaliTest[1727:3032014] client session: stateChange:2->0 1455058462031.1230.GLlCGQ==
,2016-02-09 23:54:24.239 ThaliTest[1727:3032506] server session: not connected 1455058462031.1230
,2016-02-09 23:54:24.268 ThaliTest[1727:3032014] jxcore: disconnect: success
,ok 110 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 23:54:24.579 ThaliTest[1727:3032014] jxcore: stopBroadcasting
2016-02-09 23:54:24.579 ThaliTest[1727:3032014] THEMultipeerSession stopping peer
2016-02-09 23:54:24.580 ThaliTest[1727:3032014] multipeer session: stop timer
2016-02-09 23:54:24.580 ThaliTest[1727:3032014] server session: disconnect
2016-02-09 23:54:24.580 ThaliTest[1727:3032014] server session: stateChange:2->0 1455058462031.1230
,2016-02-09 23:54:24.589 ThaliTest[1727:3032014] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 61121

,2016-02-09 23:54:24.678 ThaliTest[1727:3032014] jxcore: startBroadcasting
,2016-02-09 23:54:24.682 ThaliTest[1727:3032014] server: starting 1455058464677.1727.ccpfIA==
,2016-02-09 23:54:24.685 ThaliTest[1727:3032014] multipeer session: start timer: 0x1917ad90
2016-02-09 23:54:24.698 ThaliTest[1727:3031668] client: found peer: 1455058462031.1230.GLlCGQ==
,2016-02-09 23:54:24.699 ThaliTest[1727:3032014] THEMultipeerSession initialized peer 1455058464677.1727
,2016-02-09 23:54:24.700 ThaliTest[1727:3032014] jxcore: startBroadcasting: success
,ok 111 Should be able to call startBroadcasting without error

,2016-02-09 23:54:24.704 ThaliTest[1727:3031668] client: found peer: 1455058460000.1727.HGrj8A==
,[{"peerIdentifier":"1455058462031.1230.GLlCGQ==","peerName":"(null)","peerAvailable":true}]

,2016-02-09 23:54:24.711 ThaliTest[1727:3032014] jxcore: connect 1455058462031.1230.GLlCGQ==
,2016-02-09 23:54:24.713 ThaliTest[1727:3032014] client session: connect
,2016-02-09 23:54:24.714 ThaliTest[1727:3032014] client session: stateChange:0->1 1455058462031.1230.GLlCGQ==
,[{"peerIdentifier":"1455058460000.1727.HGrj8A==","peerName":"(null)","peerAvailable":true}]
,
,2016-02-09 23:54:24.733 ThaliTest[1727:3032014] jxcore: connect 1455058460000.1727.HGrj8A==
,2016-02-09 23:54:24.739 ThaliTest[1727:3032014] client session: connect
,2016-02-09 23:54:24.741 ThaliTest[1727:3032014] client session: stateChange:0->1 1455058460000.1727.HGrj8A==
,2016-02-09 23:54:25.728 ThaliTest[1727:3031668] client: lost peer: 1455058462031.1230.GLlCGQ==
2016-02-09 23:54:25.729 ThaliTest[1727:3031668] client session: onPeerLost: 1455058462031.1230.GLlCGQ==
2016-02-09 23:54:25.729 ThaliTest[1727:3031668] client ,session: onLinkFailure: 1455058462031.1230.GLlCGQ==
2016-02-09 23:54:25.729 ThaliTest[1727:3031668] client session: disconnect
2016-02-09 23:54:25.729 ThaliTest[1727:3031668] client session: stateChange:1->0 1455058462031.1230.GLlCGQ==
2016-02-09 23:54:,25.730 ThaliTest[1727:3031668] client session: fireConnectCallback: 1455058462031.1230.GLlCGQ==
2016-02-09 23:54:25.730 ThaliTest[1727:3031668] jxcore: connect: fail: Peer disconnected
2016-02-09 23:54:25.731 ThaliTest[1727:3031668] client: lost peer: 14,55058460000.1727.HGrj8A==
2016-02-09 23:54:25.731 ThaliTest[1727:3031668] client session: onPeerLost: 1455058460000.1727.HGrj8A==
2016-02-09 23:54:25.731 ThaliTest[1727:3031668] client session: onLinkFailure: 1455058460000.1727.HGrj8A==
[{"peerIdentifie,r":"1455058462031.1230.GLlCGQ==","peerName":"(null)","peerAvailable":false}]

,2016-02-09 23:54:25.731 ThaliTest[1727:3031668] client session: disconnect
,2016-02-09 23:54:25.736 ThaliTest[1727:3031668] client session: stateChange:1->0 1455058460000.1727.HGrj8A==
2016-02-09 23:54:25.738 ThaliTest[1727:3031668] client session: fireConnectCallback: 1455058460000.1727.HGrj8A==
2016-02-09 23:54:25.738 ThaliTest[1727:3031668] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1455058460000.1727.HGrj8A==","peerName":"(null)","peerAvailable":false}]

,2016-02-09 23:54:25.749 ThaliTest[1727:3031668] client: found peer: 1455058466747.1230.UMClSA==
[{"peerIdentifier":"1455058466747.1230.UMClSA==","peerName":"(null)","peerAvailable":true}]

2016-02-09 23:54:25.751 ThaliTest[1727:3032014] jxcore: connect ,1455058466747.1230.UMClSA==
2016-02-09 23:54:25.752 ThaliTest[1727:3032014] client session: connect
2016-02-09 23:54:25.752 ThaliTest[1727:3032014] client session: stateChange:0->1 1455058466747.1230.UMClSA==
,2016-02-09 23:54:25.908 ThaliTest[1727:3031668] multipeer session: reset timer
,2016-02-09 23:54:25.908 ThaliTest[1727:3031668] multipeer session: stop timer
,2016-02-09 23:54:25.909 ThaliTest[1727:3031668] multipeer session: start timer: 0x1917ad90
,2016-02-09 23:54:25.909 ThaliTest[1727:3031668] server session: connect
,2016-02-09 23:54:25.910 ThaliTest[1727:3031668] server session: stateChange:0->1 1455058466747.1230
,2016-02-09 23:54:25.918 ThaliTest[1727:3031668] server: accepting invitation 1455058466747.1230
,2016-02-09 23:54:26.740 ThaliTest[1727:3032014] jxcore: connect 1455058462031.1230.GLlCGQ==
2016-02-09 23:54:26.741 ThaliTest[1727:3032014] client: connect: unreachable 1455058462031.1230.GLlCGQ==
2016-02-09 23:54:26.741 ThaliTest[1727:3032014] jxcore: connect: fail: Peer unreachable
,2016-02-09 23:54:26.755 ThaliTest[1727:3032014] jxcore: connect 1455058460000.1727.HGrj8A==
2016-02-09 23:54:26.756 ThaliTest[1727:3032014] client: connect: unreachable 1455058460000.1727.HGrj8A==
2016-02-09 23:54:26.756 ThaliTest[1727:3032014] jxcore: c,onnect: fail: Peer unreachable
,2016-02-09 23:54:28.431 ThaliTest[1727:3032508] client session: connected
2016-02-09 23:54:28.432 ThaliTest[1727:3032508] client session: stateChange:1->2 1455058466747.1230.UMClSA==
2016-02-09 23:54:28.435 ThaliTest[1727:3032508] client session: fireCon,nectCallback: 1455058466747.1230.UMClSA==
2016-02-09 23:54:28.436 ThaliTest[1727:3032508] jxcore: connect: success
,ok 112 Should be able to connect without error

ok 113 Port should be within range

ok 114 First connect should succeed

,2016-02-09 23:54:28.497 ThaliTest[1727:3031668] client: relay established
,2016-02-09 23:54:28.497 ThaliTest[1727:3031668] client: new accepted socket: 0x18437690
,ok 115 the test messages should be equal

ok 116 First send should succeed

,2016-02-09 23:54:28.574 ThaliTest[1727:3032539] server session: connected
2016-02-09 23:54:28.574 ThaliTest[1727:3032539] server session: stateChange:1->2 1455058466747.1230
,2016-02-09 23:54:28.582 ThaliTest[1727:3031668] client: socket closed
2016-02-09 23:54:28.582 ThaliTest[1727:3031668] client relay: socket disconnected
2016-02-09 23:54:28.582 ThaliTest[1727:3031668] client relay: 0x18437690 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 23:54:28.583 ThaliTest[1727:3031668] client session: socket closed: 1455058466747.1230.UMClSA==
2016-02-09 ,23:54:28.583 ThaliTest[1727:3031668] client session: onLinkFailure: 1455058466747.1230.UMClSA==
2016-02-09 23:54:28.583 ThaliTest[1727:3031668] client session: disconnect
2016-02-09 23:54:28.583 ThaliTest[1727:3031668] client session: stateChange:2->0 14,55058466747.1230.UMClSA==
,2016-02-09 23:54:28.596 ThaliTest[1727:3031668] client session: fireConnectionErrorEvent: 1455058466747.1230.UMClSA==
2016-02-09 23:54:28.596 ThaliTest[1727:3031668] server relay: connected (to port: 61121)
,2016-02-09 23:54:28.599 ThaliTest[1727:3032014] jxcore: connect 1455058466747.1230.UMClSA==
2016-02-09 23:54:28.607 ThaliTest[1727:3032014] client session: connect
2016-02-09 23:54:28.607 ThaliTest[1727:3032014] client session: stateChange:0->1 1455058466747.1230.UMClSA==
,2016-02-09 23:54:28.768 ThaliTest[1727:3032541] server session: not connected 1455058466747.1230
,2016-02-09 23:54:28.934 ThaliTest[1727:3031668] multipeer session: reset timer
,2016-02-09 23:54:28.934 ThaliTest[1727:3031668] multipeer session: stop timer
,2016-02-09 23:54:28.937 ThaliTest[1727:3031668] multipeer session: start timer: 0x1917ad90
2016-02-09 23:54:28.937 ThaliTest[1727:3031668] server: disconnecting to refresh session (1455058466747.1230)
,2016-02-09 23:54:28.937 ThaliTest[1727:3031668] server session: disconnect
,2016-02-09 23:54:28.939 ThaliTest[1727:3031668] server session: stateChange:2->0 1455058466747.1230
,2016-02-09 23:54:28.945 ThaliTest[1727:3031668] server session: connect
,2016-02-09 23:54:28.946 ThaliTest[1727:3031668] server session: stateChange:0->1 1455058466747.1230
,2016-02-09 23:54:28.983 ThaliTest[1727:3031668] server: accepting invitation 1455058466747.1230
,2016-02-09 23:54:31.393 ThaliTest[1727:3032541] client session: connected
2016-02-09 23:54:31.393 ThaliTest[1727:3032541] client session: stateChange:1->2 1455058466747.1230.UMClSA==
2016-02-09 23:54:31.397 ThaliTest[1727:3032541] client session: fireConnectCallback: 1455058466747.1230.UMClSA==
2016-02-09 23:54:31.397 ThaliTest[1727:3032541] jxcore: connect: success
,ok 117 Should be able to connect without error

ok 118 Port should be within range

,ok 119 Second connect should succeed

,2016-02-09 23:54:31.433 ThaliTest[1727:3031668] client: relay established
2016-02-09 23:54:31.434 ThaliTest[1727:3031668] client: new accepted socket: 0x194ca2d0
,ok 120 the test messages should be equal

,ok 121 Second send should succeed

,2016-02-09 23:54:31.525 ThaliTest[1727:3032510] server session: connected
,2016-02-09 23:54:31.526 ThaliTest[1727:3032510] server session: stateChange:1->2 1455058466747.1230
,# setup

,2016-02-09 23:54:31.546 ThaliTest[1727:3031668] server relay: connected (to port: 61121)
,2016-02-09 23:54:31.550 ThaliTest[1727:3031668] client: socket closed
2016-02-09 23:54:31.550 ThaliTest[1727:3031668] client relay: socket disconnected
2016-02-09 23:54:31.551 ThaliTest[1727:3031668] client relay: 0x194ca2d0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 23:54:31.551 ThaliTest[1727:3031668] client session: socket closed: 1455058466747.1230.UMClSA==
2016-02-09 ,23:54:31.551 ThaliTest[1727:3031668] client session: onLinkFailure: 1455058466747.1230.UMClSA==
2016-02-09 23:54:31.551 ThaliTest[1727:3031668] client session: disconnect
2016-02-09 23:54:31.552 ThaliTest[1727:3031668] client session: stateChange:2->0 1455058466747.1230.UMClSA==
,2016-02-09 23:54:31.567 ThaliTest[1727:3031668] client session: fireConnectionErrorEvent: 1455058466747.1230.UMClSA==
,2016-02-09 23:54:31.783 ThaliTest[1727:3032506] server session: not connected 1455058466747.1230
,calling stopBroadcasting

,2016-02-09 23:54:31.944 ThaliTest[1727:3032014] jxcore: stopBroadcasting
2016-02-09 23:54:31.944 ThaliTest[1727:3032014] THEMultipeerSession stopping peer
2016-02-09 23:54:31.945 ThaliTest[1727:3032014] multipeer session: stop timer
2016-02-09 23:54:31.,945 ThaliTest[1727:3032014] server session: disconnect
2016-02-09 23:54:31.945 ThaliTest[1727:3032014] server session: stateChange:2->0 1455058466747.1230
,2016-02-09 23:54:32.046 ThaliTest[1727:3032014] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# #generatePreambleAndBeacons null ECDH for local device

,# teardown

,ok 122 ecdhForLocalDevice cannot be null

,# setup

,# #generatePreambleAndBeacons expiration out of range lower

,# teardown

,ok 123 secondsUntilExpiration out of range.

,# setup

,# #generatePreambleAndBeacons expiration out of range upper

,# teardown

,ok 124 secondsUntilExpiration out of range.

,# setup

,# #generatePreambleAndBeacons empty keys to notify

,# teardown

,ok 125 should be equal

,# setup

,# #generatePreambleAndBeacons multiple keys to notify

,# teardown

,ok 126 should be equal

,ok 127 should be equal

,ok 128 should be equal

,ok 129 should be equal

,# setup

,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,# teardown

,ok 130 should throw

,# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,# teardown

,ok 131 Preamble expiration must be a 64 bit integer

,# setup

,# #parseBeacons expiration out of range lower

,# teardown

,ok 132 Expiration out of range

,# setup

,# #parseBeacons no beacons returns null

,# teardown

,ok 133 should be equal

,# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,# teardown

,ok 134 Malformed encrypted beacon key ID

,# setup

,# #parseBeacons addressBookCallback fails decrypt

,# teardown

,ok 135 should be equal

,# setup

,# #parseBeacons addressBookCallback returns no matches

,# teardown

,ok 136 should be equal

,ok 137 should be equal

,# setup

,# #parseBeacons addressBookCallback returns public key

,# teardown

,ok 138 should be equal

ok 139 (unnamed assert)

,# setup

,# #parseBeacons with beacons both for and not for the user

,# teardown

,ok 140 (unnamed assert)

,# setup

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/B5B9A5F6-0FA8-40E6-A143-8E463BBE3367/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 141 starting event should occur in right order

,2016-02-09 23:54:44.570 ThaliTest[1727:3032014] jxcore: startBroadcasting
,2016-02-09 23:54:44.572 ThaliTest[1727:3032014] server: starting GsV0h1_bzr1cf6gcdw0n9g.g5oYYA==
2016-02-09 23:54:44.572 ThaliTest[1727:3032014] multipeer session: start timer: 0x18389510
2016-02-09 23:54:44.572 ThaliTest[1727:3032014] THEMultipeerSession initialized peer GsV0h1_bzr1cf6gcdw0n9g
2016-02-09 23:54:44.572 ThaliTest[1727:3032014] jxcore: startBroadcasting: success
ok 142 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 143 stopping event sh,ould occur in right order

About to call stopBroadcasting

2016-02-09 23:54:44.574 ThaliTest[1727:3032014] jxcore: stopBroadcasting
2016-02-09 23:54:44.574 ThaliTest[1727:3032014] THEMultipeerSession stopping peer
2016-02-09 23:54:44.574 ThaliTest[17,27:3032014] multipeer session: stop timer
2016-02-09 23:54:44.574 ThaliTest[1727:3032014] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

ok 144 stopped event should occur in right order

,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/B5B9A5F6-0FA8-40E6-A143-8E463BBE3367/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 23:54:44.862 ThaliTest[1727:3032014] jxcore: startBroadcasting
,2016-02-09 23:54:44.864 ThaliTest[1727:3032014] server: starting GsV0h1_bzr1cf6gcdw0n9g.IuwgIQ==
2016-02-09 23:54:44.865 ThaliTest[1727:3032014] multipeer session: start timer: 0x1826d640
2016-02-09 23:54:44.865 ThaliTest[1727:3032014] THEMultipeerSessio,n initialized peer GsV0h1_bzr1cf6gcdw0n9g
2016-02-09 23:54:44.865 ThaliTest[1727:3032014] jxcore: startBroadcasting: success
ok 145 getDeviceIdentity should not return an error

ok 146 deviceName should not be null

Now in TRM stop

State of this._,isStarted: true

About to call stopBroadcasting

,2016-02-09 23:54:44.867 ThaliTest[1727:3032014] jxcore: stopBroadcasting
2016-02-09 23:54:44.868 ThaliTest[1727:3032014] THEMultipeerSession stopping peer
2016-02-09 23:54:44.868 ThaliTest[1727:3032014] multipeer session: stop timer
,2016-02-09 23:54:44.869 ThaliTest[1727:3032014] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/B5B9A5F6-0FA8-40E6-A143-8E463BBE3367/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 23:54:46.833 ThaliTest[1727:3032014] jxcore: startBroadcasting
,2016-02-09 23:54:46.834 ThaliTest[1727:3032014] server: starting GsV0h1_bzr1cf6gcdw0n9g.uKAEAg==
2016-02-09 23:54:46.834 ThaliTest[1727:3032014] multipeer session: start timer: 0x192cdee0
2016-02-09 23:54:46.834 ThaliTest[1727:3032014] THEMultipeerSession initialized peer GsV0h1_bzr1cf6gcdw0n9g
2016-02-09 23:54:46.835 ThaliTest[1727:3032014] jxcore: startBroadcasting: success
ok 147 getDeviceIdentity should not return an error

ok 148 deviceName should not be null

,2016-02-09 23:54:46.843 ThaliTest[1727:3031668] client: found peer: 1455058466747.1230.UMClSA==
,2016-02-09 23:54:51.299 ThaliTest[1727:3031668] client: found peer: p_29iHlSdwuZDWS9L3mN8Q.dPIBxA==
,2016-02-09 23:54:51.323 ThaliTest[1727:3032014] jxcore: connect 1455058466747.1230.UMClSA==
2016-02-09 23:54:51.323 ThaliTest[1727:3032014] client session: connect
,2016-02-09 23:54:51.324 ThaliTest[1727:3032014] client session: stateChange:0->1 1455058466747.1230.UMClSA==
,2016-02-09 23:54:51.330 ThaliTest[1727:3032014] jxcore: connect p_29iHlSdwuZDWS9L3mN8Q.dPIBxA==
,2016-02-09 23:54:51.332 ThaliTest[1727:3032014] client session: connect
,2016-02-09 23:54:51.334 ThaliTest[1727:3032014] client session: stateChange:0->1 p_29iHlSdwuZDWS9L3mN8Q.dPIBxA==
,2016-02-09 23:54:51.368 ThaliTest[1727:3031668] multipeer session: reset timer
2016-02-09 23:54:51.368 ThaliTest[1727:3031668] multipeer session: stop timer
2016-02-09 23:54:51.368 ThaliTest[1727:3031668] multipeer session: start timer: 0x192cdee0
2016-02-09 23:54:51.368 ThaliTest[1727:3031668] server session: connect
2016-02-09 23:54:51.368 ThaliTest[1727:3031668] server session: stateChange:0->1 p_29iHlSdwuZDWS9L3mN8Q
2016-02-09 23:54:51.372 ThaliTest[1727:3031668] server: accepting invitation p_29iHlSdwuZDWS9L3mN8Q
,ok 149 Should be able to put doc without error

,ok 150 1st change of local doc should contain local id

,2016-02-09 23:54:54.269 ThaliTest[1727:3032541] server session: connected
2016-02-09 23:54:54.270 ThaliTest[1727:3032541] server session: stateChange:1->2 p_29iHlSdwuZDWS9L3mN8Q
,2016-02-09 23:54:54.278 ThaliTest[1727:3032541] client session: connected
2016-02-09 23:54:54.278 ThaliTest[1727:3032541] client session: stateChange:1->2 p_29iHlSdwuZDWS9L3mN8Q.dPIBxA==
,2016-02-09 23:54:54.582 ThaliTest[1727:3032541] client session: fireConnectCallback: p_29iHlSdwuZDWS9L3mN8Q.dPIBxA==
,2016-02-09 23:54:54.583 ThaliTest[1727:3031668] server relay: connected (to port: 61140)
2016-02-09 23:54:54.585 ThaliTest[1727:3032541] jxcore: connect: success
server bridge: new client socket

,2016-02-09 23:54:54.611 ThaliTest[1727:3031668] client: relay established
2016-02-09 23:54:54.612 ThaliTest[1727:3031668] client: new accepted socket: 0x187f8810
,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed
,
,client bridge: new client socket
,
,client bridge: new client socket
,
,client bridge: socket closed

,Uncaught Promise Rejection: {"status":400}

,Trace: { [Error: ETIMEDOUT] status: 400 }
    at $3.prototype.trace@console.js:139:8
    at @/private/var/mobile/Containers/Bundle/Application/AC2F0BEF-0D2D-494F-9BCF-3E2A6DCB2A1A/ThaliTest.app/www/jxcore/lib/thali-tape.js:39:3
    at emit@events.js:98:,1
    at handlers.reject/<@/private/var/mobile/Containers/Bundle/Application/AC2F0BEF-0D2D-494F-9BCF-3E2A6DCB2A1A/ThaliTest.app/www/jxcore/node_modules/lie/lib/index.js:128:11
    at nextTick@/private/var/mobile/Containers/Bundle/Application/AC2F0BEF-0D2,D-494F-9BCF-3E2A6DCB2A1A/ThaliTest.app/www/jxcore/node_modules/lie/node_modules/immediate/lib/index.js:61:7
    at $0a@node.js:917:1

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****


```
