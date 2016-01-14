#### Test 55613145b105d0b_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55613145b105d0b/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/7D0EF636-261C-490A-9A52-9022EF2C4765/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/7D0EF636-261C-490A-9A52-9022EF2C4765/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55613145b105d0b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55613145b105d0b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5922C57B-9236-4FC9-80D7-CE3DBB2B821D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55387"
,(lldb)     command script import "/tmp/7D0EF636-261C-490A-9A52-9022EF2C4765/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-14 10:30:18.158 ThaliTest[1929:4068644] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/ADA8F7F1-9C59-40D7-85B2-B1C29B68761A/Library/Cookies/Cookies.binarycookies
,2016-01-14 10:30:18.410 ThaliTest[1929:4068644] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-14 10:30:18.411 ThaliTest[1929:4068644] Multi-tasking -> Device: YES, App: YES
,2016-01-14 10:30:18.418 ThaliTest[1929:4068644] Unlimited access to network resources
,2016-01-14 10:30:18.425 ThaliTest[1929:4068644] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-14 10:30:22.645 ThaliTest[1929:4068644] Resetting plugins due to page load.
,2016-01-14 10:30:24.121 ThaliTest[1929:4068644] Finished load of: file:///var/mobile/Containers/Bundle/Application/5922C57B-9236-4FC9-80D7-CE3DBB2B821D/ThaliTest.app/www/index.html
,2016-01-14 10:30:24.279 ThaliTest[1929:4068644] JXcore Cordova plugin initializing
,2016-01-14 10:30:24.280 ThaliTest[1929:4068789] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone6-1
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
,# setup
,# successfully create a new pkcs12 file and return hash value
,# teardown
,ok 4 should be equal
,ok 5 null
ok 6 (unnamed assert)
ok 7 should be equal
ok 8 should not throw
# setup
,# successfully read a previous pkcs12 file and return hash value
,# teardown
,ok 9 (unnamed assert)
,ok 10 (unnamed assert)
,ok 11 should not throw
,ok 12 should be equal
ok 13 should be equal
# setup
,# failed to extract public key because of corrupt pkcs12 file
,# teardown
,ok 14 should be equal
,# setup
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
,ok 33 should be equal
# setup
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
,ok 40 should be equal
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
,2016-01-14 10:35:58.725 ThaliTest[1929:4068789] jxcore: startBroadcasting
,2016-01-14 10:35:58.731 ThaliTest[1929:4068789] server: starting 1452764158724.1929.Qljy4A==
2016-01-14 10:35:58.731 ThaliTest[1929:4068789] multipeer session: start timer: 0x15ba2850
2016-01-14 10:35:58.731 ThaliTest[1929:4068789] THEMultipeerSession in,itialized peer 1452764158724.1929
2016-01-14 10:35:58.731 ThaliTest[1929:4068789] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2016-01-14 10:35:58.733 ThaliTest[1929:4068789] jxcore: stopBroadcasting
,2016-01-14 10:35:58.733 ThaliTest[1929:4068789] THEMultipeerSession stopping peer
2016-01-14 10:35:58.734 ThaliTest[1929:4068789] multipeer session: stop timer
2016-01-14 10:35:58.734 ThaliTest[1929:4068789] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-14 10:35:58.735 ThaliTest[1929:4068789] jxcore: startBroadcasting
,2016-01-14 10:35:58.742 ThaliTest[1929:4068789] server: starting 1452764158735.1929.m34DMw==
,2016-01-14 10:35:58.743 ThaliTest[1929:4068789] multipeer session: start timer: 0x15ac1900
2016-01-14 10:35:58.745 ThaliTest[1929:4068789] THEMultipeerSession initialized peer 1452764158735.1929
2016-01-14 10:35:58.745 ThaliTest[1929:4068789] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-14 10:35:58.746 ThaliTest[1929:4068789] jxcore: stopBroadcasting
2016-01-14 10:35:58.746 ThaliTest[1929:4068789] THEMultipeerSession stopping peer
2016-01-14 10:35:58.746 ThaliTest[1929:4068789] multipeer session: stop timer
,2016-01-14 10:35:58.746 ThaliTest[1929:4068789] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
2016-01-14 10:35:58.749 ThaliTest[1929:4068789] jxcore: startBroadcasting
,2016-01-14 10:35:58.752 ThaliTest[1929:4068789] server: starting 1452764158749.1929.83FcUw==
2016-01-14 10:35:58.752 ThaliTest[1929:4068789] multipeer session: start timer: 0x1593d6b0
2016-01-14 10:35:58.752 ThaliTest[1929:4068789] THEMultipeerSession initialized peer 1452764158749.1929
2016-01-14 10:35:58.752 ThaliTest[1929:4068789] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2016-01-14 10:35:58.753 ThaliTest[1929:4068789] jxcore: stopBroadcasting
,2016-01-14 10:35:58.753 ThaliTest[1929:4068789] THEMultipeerSession stopping peer
2016-01-14 10:35:58.756 ThaliTest[1929:4068789] multipeer session: stop timer
2016-01-14 10:35:58.757 ThaliTest[1929:4068789] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error
2016-01-14 10:35:58.757 ThaliTest[1929:4068789] jxcore: startBroadcasting
,2016-01-14 10:35:58.761 ThaliTest[1929:4068789] server: starting 1452764158757.1929.87gzeA==
2016-01-14 10:35:58.761 ThaliTest[1929:4068789] multipeer session: start timer: 0x15ae3220
,2016-01-14 10:35:58.761 ThaliTest[1929:4068789] THEMultipeerSession initialized peer 1452764158757.1929
2016-01-14 10:35:58.764 ThaliTest[1929:4068789] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2016-01-14 10:35:58.765 ThaliTest[1929:4068789] jxcore: stopBroadcasting
,2016-01-14 10:35:58.767 ThaliTest[1929:4068789] THEMultipeerSession stopping peer
2016-01-14 10:35:58.770 ThaliTest[1929:4068789] multipeer session: stop timer
2016-01-14 10:35:58.770 ThaliTest[1929:4068789] jxcore: stopBroadcasting: success
ok 52 Shoul,d be able to call stopBroadcasting without error
,2016-01-14 10:35:58.771 ThaliTest[1929:4068789] jxcore: startBroadcasting
,2016-01-14 10:35:58.777 ThaliTest[1929:4068789] server: starting 1452764158770.1929.V2CpHA==
,2016-01-14 10:35:58.778 ThaliTest[1929:4068789] multipeer session: start timer: 0x15ae3220
,2016-01-14 10:35:58.781 ThaliTest[1929:4068789] THEMultipeerSession initialized peer 1452764158770.1929
,2016-01-14 10:35:58.781 ThaliTest[1929:4068789] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2016-01-14 10:35:58.782 ThaliTest[1929:4068789] jxcore: stopBroadcasting
,2016-01-14 10:35:58.783 ThaliTest[1929:4068789] THEMultipeerSession stopping peer
,2016-01-14 10:35:58.783 ThaliTest[1929:4068789] multipeer session: stop timer
,2016-01-14 10:35:58.784 ThaliTest[1929:4068789] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-14 10:35:58.786 ThaliTest[1929:4068789] jxcore: startBroadcasting
,2016-01-14 10:35:58.788 ThaliTest[1929:4068789] server: starting 1452764158786.1929.IoJr9g==
,2016-01-14 10:35:58.789 ThaliTest[1929:4068789] multipeer session: start timer: 0x15a441b0
2016-01-14 10:35:58.792 ThaliTest[1929:4068789] THEMultipeerSession initialized peer 1452764158786.1929
,2016-01-14 10:35:58.792 ThaliTest[1929:4068789] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-14 10:35:58.793 ThaliTest[1929:4068789] jxcore: stopBroadcasting
,2016-01-14 10:35:58.794 ThaliTest[1929:4068789] THEMultipeerSession stopping peer
,2016-01-14 10:35:58.794 ThaliTest[1929:4068789] multipeer session: stop timer
,2016-01-14 10:35:58.795 ThaliTest[1929:4068789] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-14 10:35:58.796 ThaliTest[1929:4068789] jxcore: startBroadcasting
,2016-01-14 10:35:58.799 ThaliTest[1929:4068789] server: starting 1452764158795.1929.dAl/HA==
,2016-01-14 10:35:58.800 ThaliTest[1929:4068789] multipeer session: start timer: 0x15f7f310
,2016-01-14 10:35:58.803 ThaliTest[1929:4068789] THEMultipeerSession initialized peer 1452764158795.1929
,2016-01-14 10:35:58.803 ThaliTest[1929:4068789] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-14 10:35:58.804 ThaliTest[1929:4068789] jxcore: stopBroadcasting
,2016-01-14 10:35:58.804 ThaliTest[1929:4068789] THEMultipeerSession stopping peer
,2016-01-14 10:35:58.805 ThaliTest[1929:4068789] multipeer session: stop timer
,2016-01-14 10:35:58.808 ThaliTest[1929:4068789] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-14 10:35:58.809 ThaliTest[1929:4068789] jxcore: startBroadcasting
,2016-01-14 10:35:58.810 ThaliTest[1929:4068789] server: starting 1452764158809.1929.acJuCQ==
,2016-01-14 10:35:58.812 ThaliTest[1929:4068789] multipeer session: start timer: 0x15e5d970
2016-01-14 10:35:58.814 ThaliTest[1929:4068789] THEMultipeerSession initialized peer 1452764158809.1929
,2016-01-14 10:35:58.815 ThaliTest[1929:4068789] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-14 10:35:58.816 ThaliTest[1929:4068789] jxcore: stopBroadcasting
,2016-01-14 10:35:58.816 ThaliTest[1929:4068789] THEMultipeerSession stopping peer
,2016-01-14 10:35:58.817 ThaliTest[1929:4068789] multipeer session: stop timer
,2016-01-14 10:35:58.818 ThaliTest[1929:4068789] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-14 10:35:58.820 ThaliTest[1929:4068789] jxcore: startBroadcasting
,2016-01-14 10:35:58.821 ThaliTest[1929:4068789] server: starting 1452764158820.1929.9DA+7w==
,2016-01-14 10:35:58.822 ThaliTest[1929:4068789] multipeer session: start timer: 0x15e5d970
,2016-01-14 10:35:58.825 ThaliTest[1929:4068789] THEMultipeerSession initialized peer 1452764158820.1929
,2016-01-14 10:35:58.825 ThaliTest[1929:4068789] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-14 10:35:58.827 ThaliTest[1929:4068789] jxcore: stopBroadcasting
,2016-01-14 10:35:58.827 ThaliTest[1929:4068789] THEMultipeerSession stopping peer
,2016-01-14 10:35:58.827 ThaliTest[1929:4068789] multipeer session: stop timer
,2016-01-14 10:35:58.829 ThaliTest[1929:4068789] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-14 10:35:58.830 ThaliTest[1929:4068789] jxcore: startBroadcasting
,2016-01-14 10:35:58.832 ThaliTest[1929:4068789] server: starting 1452764158830.1929.FM+Q8Q==
,2016-01-14 10:35:58.833 ThaliTest[1929:4068789] multipeer session: start timer: 0x1785e620
,2016-01-14 10:35:58.835 ThaliTest[1929:4068789] THEMultipeerSession initialized peer 1452764158830.1929
,2016-01-14 10:35:58.835 ThaliTest[1929:4068789] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-14 10:35:58.836 ThaliTest[1929:4068789] jxcore: stopBroadcasting
,2016-01-14 10:35:58.837 ThaliTest[1929:4068789] THEMultipeerSession stopping peer
,2016-01-14 10:35:58.837 ThaliTest[1929:4068789] multipeer session: stop timer
,2016-01-14 10:35:58.840 ThaliTest[1929:4068789] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-14 10:35:59.017 ThaliTest[1929:4068789] jxcore: startBroadcasting
,2016-01-14 10:35:59.018 ThaliTest[1929:4068789] server: starting 1452764159017.1929.PRAHLA==
2016-01-14 10:35:59.018 ThaliTest[1929:4068789] multipeer session: start timer: 0x15d4cda0
2016-01-14 10:35:59.019 ThaliTest[1929:4068789] THEMultipeerSession initialized peer 1452764159017.1929
2016-01-14 10:35:59.019 ThaliTest[1929:4068789] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-14 10:35:59.020 ThaliTest[1929:4068789] jxcore: startBroadcasting
,2016-01-14 10:35:59.020 ThaliTest[1929:4068789] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
,2016-01-14 10:35:59.021 ThaliTest[1929:4068789] jxcore: stopBroadcasting
2016-01-14 10:35:59.021 ThaliTest[1929:4068789] THEMultipeerSession stopping peer
2016-01-14 10:35:59.021 ThaliTest[1929:4068789] multipeer session: stop timer
,2016-01-14 10:35:59.021 ThaliTest[1929:4068789] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-14 10:35:59.089 ThaliTest[1929:4068789] jxcore: startBroadcasting
,2016-01-14 10:35:59.090 ThaliTest[1929:4068789] server: starting 1452764159088.1929.YumtaQ==
,2016-01-14 10:35:59.091 ThaliTest[1929:4068789] multipeer session: start timer: 0x15abbe40
,2016-01-14 10:35:59.094 ThaliTest[1929:4068789] THEMultipeerSession initialized peer 1452764159088.1929
,2016-01-14 10:35:59.094 ThaliTest[1929:4068789] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error
,2016-01-14 10:35:59.096 ThaliTest[1929:4068789] jxcore: connect foobar
,2016-01-14 10:35:59.096 ThaliTest[1929:4068789] client: unknown peer foobar
,2016-01-14 10:35:59.097 ThaliTest[1929:4068789] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
,2016-01-14 10:35:59.098 ThaliTest[1929:4068789] jxcore: stopBroadcasting
,2016-01-14 10:35:59.098 ThaliTest[1929:4068789] THEMultipeerSession stopping peer
,2016-01-14 10:35:59.098 ThaliTest[1929:4068789] multipeer session: stop timer
,2016-01-14 10:35:59.099 ThaliTest[1929:4068789] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-14 10:35:59.146 ThaliTest[1929:4068789] jxcore: startBroadcasting
,2016-01-14 10:35:59.147 ThaliTest[1929:4068789] server: starting 1452764159146.1929.5iUtKQ==
,2016-01-14 10:35:59.148 ThaliTest[1929:4068789] multipeer session: start timer: 0x15ef1430
2016-01-14 10:35:59.151 ThaliTest[1929:4068789] THEMultipeerSession initialized peer 1452764159146.1929
,2016-01-14 10:35:59.151 ThaliTest[1929:4068789] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error
,2016-01-14 10:35:59.153 ThaliTest[1929:4068789] jxcore: disconnect
,2016-01-14 10:35:59.153 ThaliTest[1929:4068789] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 
,2016-01-14 10:35:59.154 ThaliTest[1929:4068789] jxcore: stopBroadcasting
,2016-01-14 10:35:59.155 ThaliTest[1929:4068789] THEMultipeerSession stopping peer
,2016-01-14 10:35:59.155 ThaliTest[1929:4068789] multipeer session: stop timer
,2016-01-14 10:35:59.156 ThaliTest[1929:4068789] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-14 10:35:59.517 ThaliTest[1929:4068789] jxcore: startBroadcasting
,2016-01-14 10:35:59.519 ThaliTest[1929:4068789] server: starting 1452764159517.1929.GoKB6w==
2016-01-14 10:35:59.519 ThaliTest[1929:4068789] multipeer session: start timer: 0x15a8e9e0
2016-01-14 10:35:59.519 ThaliTest[1929:4068789] THEMultipeerSession initialized peer 1452764159517.1929
2016-01-14 10:35:59.519 ThaliTest[1929:4068789] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-14 10:36:00.366 ThaliTest[1929:4068644] client: found peer: 1452764159536.1914.fKIvag==
2016-01-14 10:36:00.367 ThaliTest[1929:4068789] jxcore: connect 1452764159536.1914.fKIvag==
2016-01-14 10:36:00.367 ThaliTest[1929:4068789] client session: co,nnect
2016-01-14 10:36:00.367 ThaliTest[1929:4068789] client session: stateChange:0->1 1452764159536.1914.fKIvag==
,2016-01-14 10:36:00.741 ThaliTest[1929:4068644] multipeer session: reset timer
2016-01-14 10:36:00.741 ThaliTest[1929:4068644] multipeer session: stop timer
2016-01-14 10:36:00.741 ThaliTest[1929:4068644] multipeer session: start timer: 0x15a8e9e0
2016-01-14 10:36:00.742 ThaliTest[1929:4068644] server session: connect
2016-01-14 10:36:00.742 ThaliTest[1929:4068644] server session: stateChange:0->1 1452764159536.1914
2016-01-14 10:36:00.748 ThaliTest[1929:4068644] server: accepting invitation 1452764159536.1914
,2016-01-14 10:36:03.037 ThaliTest[1929:4069344] client session: connected
2016-01-14 10:36:03.037 ThaliTest[1929:4069344] client session: stateChange:1->2 1452764159536.1914.fKIvag==
,2016-01-14 10:36:03.079 ThaliTest[1929:4069349] client session: fireConnectCallback: 1452764159536.1914.fKIvag==
2016-01-14 10:36:03.079 ThaliTest[1929:4069349] jxcore: connect: success
ok 75 Should be able to connect without error
ok 76 Port should be within range
,2016-01-14 10:36:03.081 ThaliTest[1929:4068789] jxcore: disconnect
2016-01-14 10:36:03.083 ThaliTest[1929:4068789] client session: disconnectFromPeer: 1452764159536.1914.fKIvag==
2016-01-14 10:36:03.083 ThaliTest[1929:4068789] client session: disconnect
2016-01-14 10:36:03.083 ThaliTest[1929:4068789] client session: stateChange:2->0 1452764159536.1914.fKIvag==
,2016-01-14 10:36:03.151 ThaliTest[1929:4068789] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-14 10:36:03.234 ThaliTest[1929:4069349] server session: connected
2016-01-14 10:36:03.235 ThaliTest[1929:4069349] server session: stateChange:1->2 1452764159536.1914
,2016-01-14 10:36:03.240 ThaliTest[1929:4068644] server relay: socket disconnected
2016-01-14 10:36:03.240 ThaliTest[1929:4068644] server relay: 0x178bd160 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-14 10:36:03.303 ThaliTest[1929:4069347] server session: not connected 1452764159536.1914
,calling stopBroadcasting
,2016-01-14 10:36:06.029 ThaliTest[1929:4068789] jxcore: stopBroadcasting
2016-01-14 10:36:06.030 ThaliTest[1929:4068789] THEMultipeerSession stopping peer
2016-01-14 10:36:06.030 ThaliTest[1929:4068789] multipeer session: stop timer
2016-01-14 10:36:06.,030 ThaliTest[1929:4068789] server session: disconnect
2016-01-14 10:36:06.030 ThaliTest[1929:4068789] server session: stateChange:2->0 1452764159536.1914
,2016-01-14 10:36:06.031 ThaliTest[1929:4068789] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-14 10:36:35.482 ThaliTest[1929:4068789] jxcore: startBroadcasting
,2016-01-14 10:36:35.485 ThaliTest[1929:4068789] server: starting 1452764195482.1929.S3Tdjw==
2016-01-14 10:36:35.485 ThaliTest[1929:4068789] multipeer session: start timer: 0x159c71d0
2016-01-14 10:36:35.485 ThaliTest[1929:4068789] THEMultipeerSession initialized peer 1452764195482.1929
2016-01-14 10:36:35.485 ThaliTest[1929:4068789] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-14 10:37:05.486 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:37:35.486 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:37:35.495 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:37:35.496 ThaliTest[1929:4068789] jxcore: connect 1452764198371.1914.JdST9g==
2016-01-14 10:37:35.497 ThaliTest[1929:4068789] client session: connect
2016-01-14 10:37:35.497 ThaliTest[1929:4068789] client session: stateChange:0->1 145276419,8371.1914.JdST9g==
,appEnteredForeground wasn't registered
,2016-01-14 10:37:38.195 ThaliTest[1929:4069594] client session: connected
2016-01-14 10:37:38.195 ThaliTest[1929:4069594] client session: stateChange:1->2 1452764198371.1914.JdST9g==
2016-01-14 10:37:38.196 ThaliTest[1929:4069594] client session: fireCon,nectCallback: 1452764198371.1914.JdST9g==
2016-01-14 10:37:38.196 ThaliTest[1929:4069594] jxcore: connect: success
ok 79 Should be able to connect without error
,ok 80 Port should be within range
,2016-01-14 10:37:38.198 ThaliTest[1929:4068789] jxcore: connect 1452764198371.1914.JdST9g==
2016-01-14 10:37:38.198 ThaliTest[1929:4068789] client: already connect(ing/ed) to 1452764198371.1914.JdST9g==
2016-01-14 10:37:38.199 ThaliTest[1929:4068789] jxcore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect
,2016-01-14 10:37:38.200 ThaliTest[1929:4068789] jxcore: disconnect
2016-01-14 10:37:38.200 ThaliTest[1929:4068789] client session: disconnectFromPeer: 1452764198371.1914.JdST9g==
2016-01-14 10:37:38.200 ThaliTest[1929:4068789] client session: disconnect,
2016-01-14 10:37:38.200 ThaliTest[1929:4068789] client session: stateChange:2->0 1452764198371.1914.JdST9g==
,2016-01-14 10:37:38.205 ThaliTest[1929:4068789] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-14 10:37:40.220 ThaliTest[1929:4068644] multipeer session: reset timer
2016-01-14 10:37:40.220 ThaliTest[1929:4068644] multipeer session: stop timer
2016-01-14 10:37:40.220 ThaliTest[1929:4068644] multipeer session: start timer: 0x159c71d0
2016-01-14 10:37:40.220 ThaliTest[1929:4068644] server session: connect
2016-01-14 10:37:40.220 ThaliTest[1929:4068644] server session: stateChange:0->1 1452764198371.1914
,2016-01-14 10:37:40.224 ThaliTest[1929:4068644] server: accepting invitation 1452764198371.1914
,2016-01-14 10:37:42.462 ThaliTest[1929:4069594] server session: connected
2016-01-14 10:37:42.462 ThaliTest[1929:4069594] server session: stateChange:1->2 1452764198371.1914
,2016-01-14 10:37:42.464 ThaliTest[1929:4068644] server relay: socket disconnected
2016-01-14 10:37:42.465 ThaliTest[1929:4068644] server relay: 0x15b12b90 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-14 10:37:42.782 ThaliTest[1929:4069650] server session: not connected 1452764198371.1914
,2016-01-14 10:38:10.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:38:10.230 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,2016-01-14 10:38:40.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:39:10.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:39:38.160 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:39:40.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:40:10.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:40:10.233 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:40:40.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:41:10.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:41:10.230 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:41:40.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:42:10.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:42:10.233 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:42:38.342 ThaliTest[1929:4068644] client: lost peer: 1452764198371.1914.JdST9g==
2016-01-14 10:42:38.342 ThaliTest[1929:4068644] client session: onPeerLost: 1452764198371.1914.JdST9g==
,2016-01-14 10:42:40.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:42:42.822 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:43:10.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:43:10.232 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:43:40.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:43:40.231 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:44:10.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:44:10.234 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:44:40.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:44:40.263 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:45:10.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:45:10.232 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:45:40.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:45:40.233 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:46:10.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:46:10.230 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:46:40.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:46:40.233 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:47:10.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:47:10.235 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:47:40.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:47:40.230 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:48:10.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:48:10.234 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:48:40.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:49:10.221 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:49:10.234 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:49:40.172 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:49:40.183 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:50:10.172 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:50:40.172 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:50:40.180 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:51:10.172 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:51:10.180 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:51:40.172 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:51:40.184 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:52:10.171 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:52:10.179 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:52:40.172 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:52:40.199 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:53:10.172 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:53:40.172 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:53:40.184 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:54:10.172 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:54:40.172 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:54:40.184 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:55:10.172 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:55:10.185 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:55:40.172 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:55:40.181 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:56:10.172 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:56:10.183 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:56:40.172 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:56:40.183 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:57:10.172 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:57:10.183 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==
,2016-01-14 10:57:40.171 ThaliTest[1929:4068644] multipeer session: restart
,2016-01-14 10:57:40.181 ThaliTest[1929:4068644] client: found peer: 1452764198371.1914.JdST9g==

```
