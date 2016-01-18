#### Test 56151093f6e24ff_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56151093f6e24ff/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/744BBEDA-1212-400E-AF36-C1FC6B13D353/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/744BBEDA-1212-400E-AF36-C1FC6B13D353/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/56151093f6e24ff/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56151093f6e24ff/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F3400554-62FA-440C-B8B3-32F9ED7801C4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57798"
,(lldb)     command script import "/tmp/744BBEDA-1212-400E-AF36-C1FC6B13D353/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-18 14:52:06.984 ThaliTest[2206:4651231] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/64F980D5-A0ED-4A05-B3C3-12D1DE6C3FCC/Library/Cookies/Cookies.binarycookies
,2016-01-18 14:52:07.213 ThaliTest[2206:4651231] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-18 14:52:07.214 ThaliTest[2206:4651231] Multi-tasking -> Device: YES, App: YES
,2016-01-18 14:52:07.221 ThaliTest[2206:4651231] Unlimited access to network resources
,2016-01-18 14:52:07.229 ThaliTest[2206:4651231] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-18 14:52:11.099 ThaliTest[2206:4651231] Resetting plugins due to page load.
,2016-01-18 14:52:12.504 ThaliTest[2206:4651231] Finished load of: file:///var/mobile/Containers/Bundle/Application/F3400554-62FA-440C-B8B3-32F9ED7801C4/ThaliTest.app/www/index.html
,2016-01-18 14:52:12.662 ThaliTest[2206:4651231] JXcore Cordova plugin initializing
2016-01-18 14:52:12.664 ThaliTest[2206:4651383] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F3400554-62FA-440C-B8B3-32F9ED7801C4/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F3400554-62FA-440C-B8B3-32F9ED7801C4/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F3400554-62FA-440C-B8B3-32F9ED7801C4/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F3400554-62FA-440C-B8B3-32F9ED7801C4/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F3400554-62FA-440C-B8B3-32F9ED7801C4/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F3400554-62FA-440C-B8B3-32F9ED7801C4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F3400554-62FA-440C-B8B3-32F9ED7801C4/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
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
ok 8 should not throw
# setup
,# successfully read a previous pkcs12 file and return hash value
,# teardown
,ok 9 (unnamed assert)
,ok 10 (unnamed assert)
ok 11 should not throw
,ok 12 should be equal
ok 13 should be equal
# setup
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
,# setup
,# #init should register the networkChanged event
,# teardown
,ok 19 should be equal
,# setup
,# #startBroadcasting should throw on null device name
,# teardown
,ok 20 should throw
# setup
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
# setup
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
,# setup
,# #connect should call Mobile("Connect") and handle an error
,# teardown
,ok 39 should be equal
ok 40 should be equal
# setup
,# should call Mobile("Disconnect") without an error
,# teardown
,ok 41 should be equal
ok 42 should be equal
# setup
,# should call Mobile("Disconnect") and handle an error
,# teardown
,ok 43 should be equal
ok 44 should be equal
,# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2016-01-18 14:57:54.813 ThaliTest[2206:4651383] jxcore: startBroadcasting
,2016-01-18 14:57:54.820 ThaliTest[2206:4651383] server: starting 1453125474813.2206.6x2ivA==
2016-01-18 14:57:54.820 ThaliTest[2206:4651383] multipeer session: start timer: 0x18217750
2016-01-18 14:57:54.820 ThaliTest[2206:4651383] THEMultipeerSession initialized peer 1453125474813.2206
,2016-01-18 14:57:54.823 ThaliTest[2206:4651383] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2016-01-18 14:57:54.824 ThaliTest[2206:4651383] jxcore: stopBroadcasting
,2016-01-18 14:57:54.824 ThaliTest[2206:4651383] THEMultipeerSession stopping peer
2016-01-18 14:57:54.830 ThaliTest[2206:4651383] multipeer session: stop timer
,2016-01-18 14:57:54.833 ThaliTest[2206:4651383] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
,2016-01-18 14:57:54.835 ThaliTest[2206:4651383] jxcore: startBroadcasting
,2016-01-18 14:57:54.838 ThaliTest[2206:4651383] server: starting 1453125474835.2206.Ww816A==
,2016-01-18 14:57:54.841 ThaliTest[2206:4651383] multipeer session: start timer: 0x1864ac50
2016-01-18 14:57:54.842 ThaliTest[2206:4651383] THEMultipeerSession initialized peer 1453125474835.2206
2016-01-18 14:57:54.842 ThaliTest[2206:4651383] jxcore: startBroadcasting: success
,ok 47 Should be able to call startBroadcasting without error
,2016-01-18 14:57:54.845 ThaliTest[2206:4651383] jxcore: stopBroadcasting
,2016-01-18 14:57:54.845 ThaliTest[2206:4651383] THEMultipeerSession stopping peer
,2016-01-18 14:57:54.846 ThaliTest[2206:4651383] multipeer session: stop timer
,2016-01-18 14:57:54.847 ThaliTest[2206:4651383] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
,2016-01-18 14:57:54.853 ThaliTest[2206:4651383] jxcore: startBroadcasting
,2016-01-18 14:57:54.855 ThaliTest[2206:4651383] server: starting 1453125474853.2206.6jzdVg==
,2016-01-18 14:57:54.857 ThaliTest[2206:4651383] multipeer session: start timer: 0x1820af10
,2016-01-18 14:57:54.861 ThaliTest[2206:4651383] THEMultipeerSession initialized peer 1453125474853.2206
,2016-01-18 14:57:54.861 ThaliTest[2206:4651383] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2016-01-18 14:57:54.862 ThaliTest[2206:4651383] jxcore: stopBroadcasting
,2016-01-18 14:57:54.863 ThaliTest[2206:4651383] THEMultipeerSession stopping peer
,2016-01-18 14:57:54.863 ThaliTest[2206:4651383] multipeer session: stop timer
,2016-01-18 14:57:54.864 ThaliTest[2206:4651383] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2016-01-18 14:57:54.866 ThaliTest[2206:4651383] jxcore: startBroadcasting
,2016-01-18 14:57:54.867 ThaliTest[2206:4651383] server: starting 1453125474866.2206.xtPL/A==
,2016-01-18 14:57:54.870 ThaliTest[2206:4651383] multipeer session: start timer: 0x1820a9c0
,2016-01-18 14:57:54.872 ThaliTest[2206:4651383] THEMultipeerSession initialized peer 1453125474866.2206
,2016-01-18 14:57:54.872 ThaliTest[2206:4651383] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2016-01-18 14:57:54.873 ThaliTest[2206:4651383] jxcore: stopBroadcasting
,2016-01-18 14:57:54.873 ThaliTest[2206:4651383] THEMultipeerSession stopping peer
,2016-01-18 14:57:54.873 ThaliTest[2206:4651383] multipeer session: stop timer
,2016-01-18 14:57:54.874 ThaliTest[2206:4651383] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2016-01-18 14:57:54.877 ThaliTest[2206:4651383] jxcore: startBroadcasting
,2016-01-18 14:57:54.878 ThaliTest[2206:4651383] server: starting 1453125474876.2206.8uXYJQ==
,2016-01-18 14:57:54.879 ThaliTest[2206:4651383] multipeer session: start timer: 0x1820b770
2016-01-18 14:57:54.881 ThaliTest[2206:4651383] THEMultipeerSession initialized peer 1453125474876.2206
,2016-01-18 14:57:54.882 ThaliTest[2206:4651383] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2016-01-18 14:57:54.883 ThaliTest[2206:4651383] jxcore: stopBroadcasting
,2016-01-18 14:57:54.884 ThaliTest[2206:4651383] THEMultipeerSession stopping peer
,2016-01-18 14:57:54.884 ThaliTest[2206:4651383] multipeer session: stop timer
,2016-01-18 14:57:54.885 ThaliTest[2206:4651383] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-18 14:57:54.887 ThaliTest[2206:4651383] jxcore: startBroadcasting
,2016-01-18 14:57:54.889 ThaliTest[2206:4651383] server: starting 1453125474887.2206.f0bFnQ==
,2016-01-18 14:57:54.890 ThaliTest[2206:4651383] multipeer session: start timer: 0x1820b770
,2016-01-18 14:57:54.892 ThaliTest[2206:4651383] THEMultipeerSession initialized peer 1453125474887.2206
,2016-01-18 14:57:54.893 ThaliTest[2206:4651383] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-18 14:57:54.894 ThaliTest[2206:4651383] jxcore: stopBroadcasting
,2016-01-18 14:57:54.894 ThaliTest[2206:4651383] THEMultipeerSession stopping peer
,2016-01-18 14:57:54.895 ThaliTest[2206:4651383] multipeer session: stop timer
,2016-01-18 14:57:54.897 ThaliTest[2206:4651383] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-18 14:57:54.898 ThaliTest[2206:4651383] jxcore: startBroadcasting
,2016-01-18 14:57:54.900 ThaliTest[2206:4651383] server: starting 1453125474898.2206.spb6Zg==
,2016-01-18 14:57:54.901 ThaliTest[2206:4651383] multipeer session: start timer: 0x1820b770
,2016-01-18 14:57:54.903 ThaliTest[2206:4651383] THEMultipeerSession initialized peer 1453125474898.2206
,2016-01-18 14:57:54.904 ThaliTest[2206:4651383] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-18 14:57:54.906 ThaliTest[2206:4651383] jxcore: stopBroadcasting
,2016-01-18 14:57:54.906 ThaliTest[2206:4651383] THEMultipeerSession stopping peer
,2016-01-18 14:57:54.906 ThaliTest[2206:4651383] multipeer session: stop timer
,2016-01-18 14:57:54.908 ThaliTest[2206:4651383] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-18 14:57:54.910 ThaliTest[2206:4651383] jxcore: startBroadcasting
,2016-01-18 14:57:54.911 ThaliTest[2206:4651383] server: starting 1453125474909.2206.ueSCJg==
,2016-01-18 14:57:54.912 ThaliTest[2206:4651383] multipeer session: start timer: 0x186e3f60
,2016-01-18 14:57:54.915 ThaliTest[2206:4651383] THEMultipeerSession initialized peer 1453125474909.2206
,2016-01-18 14:57:54.915 ThaliTest[2206:4651383] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-18 14:57:54.917 ThaliTest[2206:4651383] jxcore: stopBroadcasting
,2016-01-18 14:57:54.917 ThaliTest[2206:4651383] THEMultipeerSession stopping peer
,2016-01-18 14:57:54.918 ThaliTest[2206:4651383] multipeer session: stop timer
,2016-01-18 14:57:54.920 ThaliTest[2206:4651383] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-18 14:57:54.921 ThaliTest[2206:4651383] jxcore: startBroadcasting
,2016-01-18 14:57:54.922 ThaliTest[2206:4651383] server: starting 1453125474921.2206.5c3oOQ==
,2016-01-18 14:57:54.924 ThaliTest[2206:4651383] multipeer session: start timer: 0x186e3f60
2016-01-18 14:57:54.926 ThaliTest[2206:4651383] THEMultipeerSession initialized peer 1453125474921.2206
2016-01-18 14:57:54.926 ThaliTest[2206:4651383] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-18 14:57:54.927 ThaliTest[2206:4651383] jxcore: stopBroadcasting
,2016-01-18 14:57:54.928 ThaliTest[2206:4651383] THEMultipeerSession stopping peer
,2016-01-18 14:57:54.928 ThaliTest[2206:4651383] multipeer session: stop timer
,2016-01-18 14:57:54.929 ThaliTest[2206:4651383] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-18 14:57:54.931 ThaliTest[2206:4651383] jxcore: startBroadcasting
,2016-01-18 14:57:54.933 ThaliTest[2206:4651383] server: starting 1453125474931.2206.JCV3ZQ==
,2016-01-18 14:57:54.935 ThaliTest[2206:4651383] multipeer session: start timer: 0x1860e130
,2016-01-18 14:57:54.937 ThaliTest[2206:4651383] THEMultipeerSession initialized peer 1453125474931.2206
,2016-01-18 14:57:54.937 ThaliTest[2206:4651383] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-18 14:57:54.938 ThaliTest[2206:4651383] jxcore: stopBroadcasting
,2016-01-18 14:57:54.939 ThaliTest[2206:4651383] THEMultipeerSession stopping peer
,2016-01-18 14:57:54.939 ThaliTest[2206:4651383] multipeer session: stop timer
,2016-01-18 14:57:54.941 ThaliTest[2206:4651383] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-18 14:57:57.994 ThaliTest[2206:4651383] jxcore: startBroadcasting
,2016-01-18 14:57:57.996 ThaliTest[2206:4651383] server: starting 1453125477994.2206.qzs1Kw==
2016-01-18 14:57:57.996 ThaliTest[2206:4651383] multipeer session: start timer: 0x182fa840
2016-01-18 14:57:57.996 ThaliTest[2206:4651383] THEMultipeerSession in,itialized peer 1453125477994.2206
,2016-01-18 14:57:57.997 ThaliTest[2206:4651383] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-18 14:57:58.003 ThaliTest[2206:4651383] jxcore: startBroadcasting
2016-01-18 14:57:58.003 ThaliTest[2206:4651383] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
2016-01-18 14:57:58.004 ThaliTest[2206:4651383] jxcore: stopBroadcasting
2016-01-18 14:57:58.004 ThaliTest[2206:4651383] THEMultipeerSession stopping peer
2016-01,-18 14:57:58.004 ThaliTest[2206:4651383] multipeer session: stop timer
2016-01-18 14:57:58.004 ThaliTest[2206:4651383] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-18 14:57:59.967 ThaliTest[2206:4651383] jxcore: startBroadcasting
,2016-01-18 14:57:59.969 ThaliTest[2206:4651383] server: starting 1453125479967.2206.lPEC/w==
2016-01-18 14:57:59.970 ThaliTest[2206:4651383] multipeer session: start timer: 0x182f4fe0
2016-01-18 14:57:59.970 ThaliTest[2206:4651383] THEMultipeerSession initialized peer 1453125479967.2206
,2016-01-18 14:57:59.971 ThaliTest[2206:4651383] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-18 14:57:59.972 ThaliTest[2206:4651383] jxcore: connect foobar
2016-01-18 14:57:59.972 ThaliTest[2206,:4651383] client: unknown peer foobar
2016-01-18 14:57:59.973 ThaliTest[2206:4651383] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
2016-01-18 14:57:59.973 ThaliTest[2206:4651383] jxcore: stopBroadcasting
2016-01-18 14:57:59.973 ThaliTest[2206:4651383] THEMultipeerSession stopping peer
2016-01-18 14:57:59.973 ThaliTest[2206:4651383] multipeer session: stop timer
,2016-01-18 14:57:59.974 ThaliTest[2206:4651383] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-18 14:58:03.034 ThaliTest[2206:4651383] jxcore: startBroadcasting
,2016-01-18 14:58:03.036 ThaliTest[2206:4651383] server: starting 1453125483034.2206.WPR5tg==
2016-01-18 14:58:03.036 ThaliTest[2206:4651383] multipeer session: start timer: 0x182e80b0
2016-01-18 14:58:03.036 ThaliTest[2206:4651383] THEMultipeerSession initialized peer 1453125483034.2206
2016-01-18 14:58:03.036 ThaliTest[2206:4651383] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-18 14:58:03.037 ThaliTest[2206:4651383] jxcore: disconnect
2016-01,-18 14:58:03.037 ThaliTest[2206:4651383] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
,2016-01-18 14:58:03.038 ThaliTest[2206:4651383] jxcore: stopBroadcasting
2016-01-18 14:58:03.040 ThaliTest[2206:4651383] THEMultipeerSession stopping peer
2016-01-18 14:58:03.040 ThaliTest[2206:4651383] multipeer session: stop timer
2016-01-18 14:58:03.040 ThaliTest[2206:4651383] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-18 14:58:06.121 ThaliTest[2206:4651383] jxcore: startBroadcasting
,2016-01-18 14:58:06.123 ThaliTest[2206:4651383] server: starting 1453125486121.2206.edWCkA==
2016-01-18 14:58:06.124 ThaliTest[2206:4651383] multipeer session: start timer: 0x181233e0
2016-01-18 14:58:06.124 ThaliTest[2206:4651383] THEMultipeerSession in,itialized peer 1453125486121.2206
2016-01-18 14:58:06.124 ThaliTest[2206:4651383] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-18 14:58:07.151 ThaliTest[2206:4651231] client: found peer: 1453125487971.2265.oxrw5w==
,2016-01-18 14:58:07.152 ThaliTest[2206:4651383] jxcore: connect 1453125487971.2265.oxrw5w==
2016-01-18 14:58:07.152 ThaliTest[2206:4651383] client session: connect
2016-01-18 14:58:07.153 ThaliTest[2206:4651383] client session: stateChange:0->1 1453125487971.2265.oxrw5w==
,2016-01-18 14:58:07.351 ThaliTest[2206:4651231] multipeer session: reset timer
2016-01-18 14:58:07.351 ThaliTest[2206:4651231] multipeer session: stop timer
2016-01-18 14:58:07.352 ThaliTest[2206:4651231] multipeer session: start timer: 0x181233e0
2016-,01-18 14:58:07.352 ThaliTest[2206:4651231] server session: connect
2016-01-18 14:58:07.352 ThaliTest[2206:4651231] server session: stateChange:0->1 1453125487971.2265
,2016-01-18 14:58:07.355 ThaliTest[2206:4651231] server: accepting invitation 1453125487971.2265
,2016-01-18 14:58:11.407 ThaliTest[2206:4651936] client session: connected
2016-01-18 14:58:11.407 ThaliTest[2206:4651936] client session: stateChange:1->2 1453125487971.2265.oxrw5w==
,2016-01-18 14:58:11.409 ThaliTest[2206:4651936] client session: fireConnectCallback: 1453125487971.2265.oxrw5w==
2016-01-18 14:58:11.409 ThaliTest[2206:4651936] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
2016-01-18 14:58:11.411 ThaliTest[2206:4651383] jxcore: disconnect
2016-01-18 14:58:11.411 ThaliTest[2206:4651383] client session: disconnectFromPeer: 1453125487971.2265.oxrw5w==
2016-01-18 14:58:11.411 ThaliTest[2206:4651383] client session: disconnect
2016-01-18 14:58:11.411 ThaliTest[2206:4651383] client session: stateChange:2->0 1453125487971.2265.oxrw5w==
,2016-01-18 14:58:11.473 ThaliTest[2206:4651383] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,2016-01-18 14:58:11.485 ThaliTest[2206:4651995] server session: connected
2016-01-18 14:58:11.485 ThaliTest[2206:4651995] server session: stateChange:1->2 1453125487971.2265
,# setup
,2016-01-18 14:58:11.490 ThaliTest[2206:4651231] server relay: socket disconnected
2016-01-18 14:58:11.490 ThaliTest[2206:4651231] server relay: 0x182d9790 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-18 14:58:11.504 ThaliTest[2206:4651936] server session: not connected 1453125487971.2265
,2016-01-18 14:58:15.023 ThaliTest[2206:4651231] client: lost peer: 1453125487971.2265.oxrw5w==
2016-01-18 14:58:15.023 ThaliTest[2206:4651231] client session: onPeerLost: 1453125487971.2265.oxrw5w==
,calling stopBroadcasting
2016-01-18 14:58:23.823 ThaliTest[2206:4651383] jxcore: stopBroadcasting
2016-01-18 14:58:23.824 ThaliTest[2206:4651383] THEMultipeerSession stopping peer
2016-01-18 14:58:23.824 ThaliTest[2206:4651383] multipeer session: stop timer
2016-01-18 14:58:23.824 ThaliTest[2206:4651383] server session: disconnect
2016-01-18 14:58:23.824 ThaliTest[2206:4651383] server session: stateChange:2->0 1453125487971.2265
,2016-01-18 14:58:23.826 ThaliTest[2206:4651383] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-18 14:58:44.157 ThaliTest[2206:4651383] jxcore: startBroadcasting
,2016-01-18 14:58:44.158 ThaliTest[2206:4651383] server: starting 1453125524156.2206.0Wl3fg==
2016-01-18 14:58:44.158 ThaliTest[2206:4651383] multipeer session: start timer: 0x18694e50
2016-01-18 14:58:44.158 ThaliTest[2206:4651383] THEMultipeerSession initialized peer 1453125524156.2206
2016-01-18 14:58:44.158 ThaliTest[2206:4651383] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-18 14:58:44.164 ThaliTest[2206:4651231] client: found peer: 1453125511158.2265.q5t90Q==
2016-01-18 14:58:44.165 ThaliTest[2206:4651383] jxcore: connect 1453125511158.2265.q5t90Q==
2016-01-18 14:58:44.165 ThaliTest[2206:4651383] client session: connect
2016-01-18 14:58:44.165 ThaliTest[2206:4651383] client session: stateChange:0->1 1453125511158.2265.q5t90Q==
,2016-01-18 14:58:45.347 ThaliTest[2206:4651231] multipeer session: reset timer
2016-01-18 14:58:45.347 ThaliTest[2206:4651231] multipeer session: stop timer
2016-01-18 14:58:45.347 ThaliTest[2206:4651231] multipeer session: start timer: 0x18694e50
2016-01-18 14:58:45.347 ThaliTest[2206:4651231] server session: connect
2016-01-18 14:58:45.347 ThaliTest[2206:4651231] server session: stateChange:0->1 1453125511158.2265
2016-01-18 14:58:45.351 ThaliTest[2206:4651231] server: accepting invitation 1453125511158.2265
,2016-01-18 14:58:47.617 ThaliTest[2206:4652086] client session: connected
2016-01-18 14:58:47.617 ThaliTest[2206:4652086] client session: stateChange:1->2 1453125511158.2265.q5t90Q==
,2016-01-18 14:58:48.028 ThaliTest[2206:4652082] client session: fireConnectCallback: 1453125511158.2265.q5t90Q==
2016-01-18 14:58:48.029 ThaliTest[2206:4652082] jxcore: connect: success
ok 79 Should be able to connect without error
ok 80 Port should be within range
,2016-01-18 14:58:48.030 ThaliTest[2206:4651383] jxcore: connect 1453125511158.2265.q5t90Q==
2016-01-18 14:58:48.030 ThaliTest[2206:4651383] client: already connect(ing/ed) to 1453125511158.2265.q5t90Q==
2016-01-18 14:58:48.031 ThaliTest[2206:4651383] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
,2016-01-18 14:58:48.031 ThaliTest[2206:4651383] jxcore: disconnect
2016-01-18 14:58:48.032 ThaliTest[2206:4651383] client session: disconnectFromPeer: 1453125511158.2265.q5t90Q==
2016-01-18 14:58:48.032 ThaliTest[2206:4651383] client session: disconnect,
2016-01-18 14:58:48.032 ThaliTest[2206:4651383] client session: stateChange:2->0 1453125511158.2265.q5t90Q==
,2016-01-18 14:58:48.035 ThaliTest[2206:4651383] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-18 14:58:48.565 ThaliTest[2206:4652086] server session: connected
2016-01-18 14:58:48.565 ThaliTest[2206:4652086] server session: stateChange:1->2 1453125511158.2265
,2016-01-18 14:58:48.586 ThaliTest[2206:4651231] server relay: socket disconnected
2016-01-18 14:58:48.587 ThaliTest[2206:4651231] server relay: 0x183ae110 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-18 14:58:48.605 ThaliTest[2206:4652070] server session: not connected 1453125511158.2265
,calling stopBroadcasting
,2016-01-18 14:58:49.029 ThaliTest[2206:4651383] jxcore: stopBroadcasting
2016-01-18 14:58:49.029 ThaliTest[2206:4651383] THEMultipeerSession stopping peer
2016-01-18 14:58:49.029 ThaliTest[2206:4651383] multipeer session: stop timer
2016-01-18 14:58:49.029 ThaliTest[2206:4651383] server session: disconnect
2016-01-18 14:58:49.029 ThaliTest[2206:4651383] server session: stateChange:2->0 1453125511158.2265
2016-01-18 14:58:49.030 ThaliTest[2206:4651383] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-18 14:59:09.393 ThaliTest[2206:4651383] jxcore: startBroadcasting
,2016-01-18 14:59:09.395 ThaliTest[2206:4651383] server: starting 1453125549393.2206.4lt+gQ==
2016-01-18 14:59:09.395 ThaliTest[2206:4651383] multipeer session: start timer: 0x186a92e0
2016-01-18 14:59:09.395 ThaliTest[2206:4651383] THEMultipeerSession initialized peer 1453125549393.2206
2016-01-18 14:59:09.395 ThaliTest[2206:4651383] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-18 14:59:09.402 ThaliTest[2206:4651231] client: found peer: 1453125542838.2265.J1/WMw==
2016-01-18 14:59:09.402 ThaliTest[2206:4651383] jxcore: connect 1453125542838.2265.J1/WMw==
2016-01-18 14:59:09.402 ThaliTest[2206:4651383] client session: connect
2016-01-18 14:59:09.402 ThaliTest[2206:4651383] client session: stateChange:0->1 1453125542838.2265.J1/WMw==
,2016-01-18 14:59:10.831 ThaliTest[2206:4651231] multipeer session: reset timer
2016-01-18 14:59:10.831 ThaliTest[2206:4651231] multipeer session: stop timer
2016-01-18 14:59:10.831 ThaliTest[2206:4651231] multipeer session: start timer: 0x186a92e0
2016-01-18 14:59:10.831 ThaliTest[2206:4651231] server session: connect
2016-01-18 14:59:10.831 ThaliTest[2206:4651231] server session: stateChange:0->1 1453125542838.2265
,2016-01-18 14:59:10.834 ThaliTest[2206:4651231] server: accepting invitation 1453125542838.2265
,2016-01-18 14:59:12.807 ThaliTest[2206:4652159] client session: connected
2016-01-18 14:59:12.808 ThaliTest[2206:4652159] client session: stateChange:1->2 1453125542838.2265.J1/WMw==
2016-01-18 14:59:12.809 ThaliTest[2206:4652159] client session: fireCon,nectCallback: 1453125542838.2265.J1/WMw==
2016-01-18 14:59:12.809 ThaliTest[2206:4652159] jxcore: connect: success
ok 84 Should be able to connect without error
ok 85 Port should be within range
,2016-01-18 14:59:12.811 ThaliTest[2206:4651383] jxcore: disconnect
2016-01-18 14:59:12.811 ThaliTest[2206:4651383] client session: disconnectFromPeer: 1453125542838.2265.J1/WMw==
2016-01-18 14:59:12.811 ThaliTest[2206:4651383] client session: disconnect
2016-01-18 14:59:12.811 ThaliTest[2206:4651383] client session: stateChange:2->0 1453125542838.2265.J1/WMw==
,2016-01-18 14:59:12.870 ThaliTest[2206:4651383] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error
,2016-01-18 14:59:12.871 ThaliTest[2206:4651383] jxcore: disconnect
2016-01-18 14:59:12.871 ThaliTest[2206:4651383] jxcore: disconnect: fail
,ok 87 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,# setup
,2016-01-18 14:59:14.303 ThaliTest[2206:4652159] server session: connected
2016-01-18 14:59:14.303 ThaliTest[2206:4652159] server session: stateChange:1->2 1453125542838.2265
,2016-01-18 14:59:14.305 ThaliTest[2206:4651231] server relay: socket disconnected
2016-01-18 14:59:14.305 ThaliTest[2206:4651231] server relay: 0x182b11e0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-18 14:59:14.315 ThaliTest[2206:4652159] server session: not connected 1453125542838.2265
,calling stopBroadcasting
,2016-01-18 14:59:16.696 ThaliTest[2206:4651383] jxcore: stopBroadcasting
2016-01-18 14:59:16.697 ThaliTest[2206:4651383] THEMultipeerSession stopping peer
2016-01-18 14:59:16.697 ThaliTest[2206:4651383] multipeer session: stop timer
2016-01-18 14:59:16.697 ThaliTest[2206:4651383] server session: disconnect
2016-01-18 14:59:16.697 ThaliTest[2206:4651383] server session: stateChange:2->0 1453125542838.2265
2016-01-18 14:59:16.697 ThaliTest[2206:4651383] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined
# ThaliEmitter can connect and send data
,# teardown
,echo server started on port: 53313
,2016-01-18 14:59:26.352 ThaliTest[2206:4651383] jxcore: startBroadcasting
,2016-01-18 14:59:26.355 ThaliTest[2206:4651383] server: starting 1453125566351.2206.HK9+tg==
,2016-01-18 14:59:26.357 ThaliTest[2206:4651383] multipeer session: start timer: 0x183ae790
,2016-01-18 14:59:26.360 ThaliTest[2206:4651383] THEMultipeerSession initialized peer 1453125566351.2206
2016-01-18 14:59:26.361 ThaliTest[2206:4651231] client: found peer: 1453125565287.2265.OitIKQ==
2016-01-18 14:59:26.361 ThaliTest[2206:4651383] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error
,2016-01-18 14:59:26.365 ThaliTest[2206:4651383] jxcore: connect 1453125565287.2265.OitIKQ==
,2016-01-18 14:59:26.366 ThaliTest[2206:4651383] client session: connect
,2016-01-18 14:59:26.366 ThaliTest[2206:4651383] client session: stateChange:0->1 1453125565287.2265.OitIKQ==
,2016-01-18 14:59:27.610 ThaliTest[2206:4651231] multipeer session: reset timer
2016-01-18 14:59:27.610 ThaliTest[2206:4651231] multipeer session: stop timer
2016-01-18 14:59:27.611 ThaliTest[2206:4651231] multipeer session: start timer: 0x183ae790
2016-01-18 14:59:27.611 ThaliTest[2206:4651231] server session: connect
,2016-01-18 14:59:27.611 ThaliTest[2206:4651231] server session: stateChange:0->1 1453125565287.2265
,2016-01-18 14:59:27.615 ThaliTest[2206:4651231] server: accepting invitation 1453125565287.2265
,appEnteredForeground wasn't registered
,2016-01-18 14:59:33.119 ThaliTest[2206:4652165] client session: connected
2016-01-18 14:59:33.119 ThaliTest[2206:4652165] client session: stateChange:1->2 1453125565287.2265.OitIKQ==
,2016-01-18 14:59:33.143 ThaliTest[2206:4652165] client session: fireConnectCallback: 1453125565287.2265.OitIKQ==
2016-01-18 14:59:33.143 ThaliTest[2206:4652165] jxcore: connect: success
ok 89 Should be able to connect without error
,ok 90 Port should be within range
,2016-01-18 14:59:33.146 ThaliTest[2206:4651231] client: relay established
2016-01-18 14:59:33.146 ThaliTest[2206:4651231] client: new accepted socket: 0x16ebab10
,data in 34005
,data in 65700
,data in 70080
,data in 75555
,2016-01-18 14:59:37.050 ThaliTest[2206:4652216] server session: connected
2016-01-18 14:59:37.051 ThaliTest[2206:4652216] server session: stateChange:1->2 1453125565287.2265
,2016-01-18 14:59:37.103 ThaliTest[2206:4651231] server relay: connected (to port: 53313)
,2016-01-18 14:59:37.716 ThaliTest[2206:4652165] server session: not connected 1453125565287.2265
,data in 87600
,data in 99645
,data in 100740
,data in 131072
ok 91 the test messages should be equal
,2016-01-18 14:59:38.886 ThaliTest[2206:4651383] jxcore: disconnect
2016-01-18 14:59:38.886 ThaliTest[2206:4651383] client session: disconnectFromPeer: 1453125565287.2265.OitIKQ==
2016-01-18 14:59:38.887 ThaliTest[2206:4651383] client session: disconnect
2016-01-18 14:59:38.887 ThaliTest[2206:4651383] client session: stateChange:2->0 1453125565287.2265.OitIKQ==
,2016-01-18 14:59:38.892 ThaliTest[2206:4651383] jxcore: disconnect: success
ok 92 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
# setup
,2016-01-18 14:59:57.612 ThaliTest[2206:4651231] multipeer session: restart
,2016-01-18 14:59:57.624 ThaliTest[2206:4651231] client: found peer: 1453125565287.2265.OitIKQ==
,2016-01-18 15:00:27.612 ThaliTest[2206:4651231] multipeer session: restart
,2016-01-18 15:00:27.628 ThaliTest[2206:4651231] client: found peer: 1453125565287.2265.OitIKQ==
,2016-01-18 15:00:57.612 ThaliTest[2206:4651231] multipeer session: restart
,2016-01-18 15:00:57.626 ThaliTest[2206:4651231] client: found peer: 1453125565287.2265.OitIKQ==
,2016-01-18 15:01:27.611 ThaliTest[2206:4651231] multipeer session: restart
,2016-01-18 15:01:27.623 ThaliTest[2206:4651231] client: found peer: 1453125565287.2265.OitIKQ==
,2016-01-18 15:01:57.612 ThaliTest[2206:4651231] multipeer session: restart
,2016-01-18 15:02:27.612 ThaliTest[2206:4651231] multipeer session: restart
,2016-01-18 15:02:57.612 ThaliTest[2206:4651231] multipeer session: restart
,2016-01-18 15:03:27.612 ThaliTest[2206:4651231] multipeer session: restart
,2016-01-18 15:03:57.612 ThaliTest[2206:4651231] multipeer session: restart
,2016-01-18 15:04:27.612 ThaliTest[2206:4651231] multipeer session: restart
,2016-01-18 15:04:57.612 ThaliTest[2206:4651231] multipeer session: restart
,2016-01-18 15:05:27.612 ThaliTest[2206:4651231] multipeer session: restart
,2016-01-18 15:05:57.612 ThaliTest[2206:4651231] multipeer session: restart
,2016-01-18 15:06:27.612 ThaliTest[2206:4651231] multipeer session: restart
,2016-01-18 15:06:57.612 ThaliTest[2206:4651231] multipeer session: restart
,2016-01-18 15:07:27.612 ThaliTest[2206:4651231] multipeer session: restart
,2016-01-18 15:07:57.612 ThaliTest[2206:4651231] multipeer session: restart
,2016-01-18 15:08:27.612 ThaliTest[2206:4651231] multipeer session: restart
,2016-01-18 15:08:57.612 ThaliTest[2206:4651231] multipeer session: restart
,2016-01-18 15:09:27.612 ThaliTest[2206:4651231] multipeer session: restart

```
