#### Test 5497026179923a9_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5497026179923a9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/4E8D3BEF-466A-4C8F-829B-C6ADEF440809/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/4E8D3BEF-466A-4C8F-829B-C6ADEF440809/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5497026179923a9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5497026179923a9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AE020429-10B1-46A1-A43A-BC28DEC64EA8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51965"
,(lldb)     command script import "/tmp/4E8D3BEF-466A-4C8F-829B-C6ADEF440809/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-11 11:49:12.544 ThaliTest[1699:3728376] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/56EF9D3A-44B5-45C6-B54A-904DB98D0E39/Library/Cookies/Cookies.binarycookies
,2016-01-11 11:49:12.890 ThaliTest[1699:3728376] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-11 11:49:12.892 ThaliTest[1699:3728376] Multi-tasking -> Device: YES, App: YES
,2016-01-11 11:49:12.900 ThaliTest[1699:3728376] Unlimited access to network resources
,2016-01-11 11:49:12.914 ThaliTest[1699:3728376] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-11 11:49:20.967 ThaliTest[1699:3728376] Resetting plugins due to page load.
,2016-01-11 11:49:23.759 ThaliTest[1699:3728376] Finished load of: file:///var/mobile/Containers/Bundle/Application/AE020429-10B1-46A1-A43A-BC28DEC64EA8/ThaliTest.app/www/index.html
,2016-01-11 11:49:23.948 ThaliTest[1699:3728376] JXcore Cordova plugin initializing
,2016-01-11 11:49:23.949 ThaliTest[1699:3728590] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
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
,# setup
,# successfully create a new pkcs12 file and return hash value
,# teardown
,ok 4 should be equal
,ok 5 null
,ok 6 (unnamed assert)
,ok 7 should be equal
,ok 8 should not throw
,# setup
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
,2016-01-11 11:54:19.780 ThaliTest[1699:3728590] jxcore: startBroadcasting
,2016-01-11 11:54:19.797 ThaliTest[1699:3728590] server: starting 1452509659779.1699.j0/1eA==
,2016-01-11 11:54:19.798 ThaliTest[1699:3728590] multipeer session: start timer: 0x15f6b060
,2016-01-11 11:54:19.799 ThaliTest[1699:3728590] THEMultipeerSession initialized peer 1452509659779.1699
,2016-01-11 11:54:19.800 ThaliTest[1699:3728590] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
,2016-01-11 11:54:19.803 ThaliTest[1699:3728590] jxcore: stopBroadcasting
,2016-01-11 11:54:19.805 ThaliTest[1699:3728590] THEMultipeerSession stopping peer
2016-01-11 11:54:19.806 ThaliTest[1699:3728590] multipeer session: stop timer
2016-01-11 11:54:19.806 ThaliTest[1699:3728590] jxcore: stopBroadcasting: success
ok 46 Shoul,d be able to call stopBroadcasting without error
,2016-01-11 11:54:19.810 ThaliTest[1699:3728590] jxcore: startBroadcasting
,2016-01-11 11:54:19.816 ThaliTest[1699:3728590] server: starting 1452509659809.1699./ZQE0A==
2016-01-11 11:54:19.817 ThaliTest[1699:3728590] multipeer session: start timer: 0x15e99b30
2016-01-11 11:54:19.818 ThaliTest[1699:3728590] THEMultipeerSession in,itialized peer 1452509659809.1699
2016-01-11 11:54:19.818 ThaliTest[1699:3728590] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-11 11:54:19.820 ThaliTest[1699:3728590] jxcore: stopBroadcasting
2,016-01-11 11:54:19.821 ThaliTest[1699:3728590] THEMultipeerSession stopping peer
2016-01-11 11:54:19.821 ThaliTest[1699:3728590] multipeer session: stop timer
2016-01-11 11:54:19.822 ThaliTest[1699:3728590] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
2016-01-11 11:54:19.836 ThaliTest[1699:3728590] jxcore: startBroadcasting
,2016-01-11 11:54:19.852 ThaliTest[1699:3728590] server: starting 1452509659835.1699.kUT+3A==
,2016-01-11 11:54:19.857 ThaliTest[1699:3728590] multipeer session: start timer: 0x15e9b650
2016-01-11 11:54:19.858 ThaliTest[1699:3728590] THEMultipeerSession initialized peer 1452509659835.1699
2016-01-11 11:54:19.858 ThaliTest[1699:3728590] jxcore: sta,rtBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2016-01-11 11:54:19.860 ThaliTest[1699:3728590] jxcore: stopBroadcasting
2016-01-11 11:54:19.861 ThaliTest[1699:3728590] THEMultipeerSession stopping peer
2016-01-11 1,1:54:19.861 ThaliTest[1699:3728590] multipeer session: stop timer
2016-01-11 11:54:19.862 ThaliTest[1699:3728590] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error
2016-01-11 11:54:19.864 ThaliTest[1699:372859,0] jxcore: startBroadcasting
,2016-01-11 11:54:19.876 ThaliTest[1699:3728590] server: starting 1452509659863.1699.+6kPIA==
,2016-01-11 11:54:19.881 ThaliTest[1699:3728590] multipeer session: start timer: 0x15b63870
,2016-01-11 11:54:19.883 ThaliTest[1699:3728590] THEMultipeerSession initialized peer 1452509659863.1699
,2016-01-11 11:54:19.884 ThaliTest[1699:3728590] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2016-01-11 11:54:19.887 ThaliTest[1699:3728590] jxcore: stopBroadcasting
,2016-01-11 11:54:19.887 ThaliTest[1699:3728590] THEMultipeerSession stopping peer
,2016-01-11 11:54:19.888 ThaliTest[1699:3728590] multipeer session: stop timer
,2016-01-11 11:54:19.890 ThaliTest[1699:3728590] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2016-01-11 11:54:19.893 ThaliTest[1699:3728590] jxcore: startBroadcasting
,2016-01-11 11:54:19.896 ThaliTest[1699:3728590] server: starting 1452509659893.1699.plM3Cw==
,2016-01-11 11:54:19.899 ThaliTest[1699:3728590] multipeer session: start timer: 0x17897050
,2016-01-11 11:54:19.901 ThaliTest[1699:3728590] THEMultipeerSession initialized peer 1452509659893.1699
,2016-01-11 11:54:19.902 ThaliTest[1699:3728590] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2016-01-11 11:54:19.905 ThaliTest[1699:3728590] jxcore: stopBroadcasting
,2016-01-11 11:54:19.906 ThaliTest[1699:3728590] THEMultipeerSession stopping peer
,2016-01-11 11:54:19.906 ThaliTest[1699:3728590] multipeer session: stop timer
,2016-01-11 11:54:19.909 ThaliTest[1699:3728590] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-11 11:54:19.912 ThaliTest[1699:3728590] jxcore: startBroadcasting
,2016-01-11 11:54:19.915 ThaliTest[1699:3728590] server: starting 1452509659912.1699.QKYG5Q==
,2016-01-11 11:54:19.916 ThaliTest[1699:3728590] multipeer session: start timer: 0x15b40370
,2016-01-11 11:54:19.917 ThaliTest[1699:3728590] THEMultipeerSession initialized peer 1452509659912.1699
,2016-01-11 11:54:19.918 ThaliTest[1699:3728590] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-11 11:54:19.922 ThaliTest[1699:3728590] jxcore: stopBroadcasting
,2016-01-11 11:54:19.922 ThaliTest[1699:3728590] THEMultipeerSession stopping peer
,2016-01-11 11:54:19.923 ThaliTest[1699:3728590] multipeer session: stop timer
,2016-01-11 11:54:19.924 ThaliTest[1699:3728590] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-11 11:54:19.928 ThaliTest[1699:3728590] jxcore: startBroadcasting
,2016-01-11 11:54:19.931 ThaliTest[1699:3728590] server: starting 1452509659927.1699.gse+/Q==
,2016-01-11 11:54:19.933 ThaliTest[1699:3728590] multipeer session: start timer: 0x15e9acf0
,2016-01-11 11:54:19.937 ThaliTest[1699:3728590] THEMultipeerSession initialized peer 1452509659927.1699
,2016-01-11 11:54:19.938 ThaliTest[1699:3728590] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-11 11:54:19.940 ThaliTest[1699:3728590] jxcore: stopBroadcasting
,2016-01-11 11:54:19.940 ThaliTest[1699:3728590] THEMultipeerSession stopping peer
,2016-01-11 11:54:19.941 ThaliTest[1699:3728590] multipeer session: stop timer
,2016-01-11 11:54:19.945 ThaliTest[1699:3728590] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-11 11:54:19.948 ThaliTest[1699:3728590] jxcore: startBroadcasting
,2016-01-11 11:54:19.952 ThaliTest[1699:3728590] server: starting 1452509659948.1699.c0gDQw==
,2016-01-11 11:54:19.956 ThaliTest[1699:3728590] multipeer session: start timer: 0x15e9acd0
,2016-01-11 11:54:19.958 ThaliTest[1699:3728590] THEMultipeerSession initialized peer 1452509659948.1699
,2016-01-11 11:54:19.959 ThaliTest[1699:3728590] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-11 11:54:19.964 ThaliTest[1699:3728590] jxcore: stopBroadcasting
,2016-01-11 11:54:19.964 ThaliTest[1699:3728590] THEMultipeerSession stopping peer
,2016-01-11 11:54:19.965 ThaliTest[1699:3728590] multipeer session: stop timer
,2016-01-11 11:54:19.969 ThaliTest[1699:3728590] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-11 11:54:19.972 ThaliTest[1699:3728590] jxcore: startBroadcasting
,2016-01-11 11:54:19.976 ThaliTest[1699:3728590] server: starting 1452509659972.1699.j3rEdQ==
,2016-01-11 11:54:19.978 ThaliTest[1699:3728590] multipeer session: start timer: 0x146f9df0
,2016-01-11 11:54:19.983 ThaliTest[1699:3728590] THEMultipeerSession initialized peer 1452509659972.1699
,2016-01-11 11:54:19.993 ThaliTest[1699:3728590] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-11 11:54:20.000 ThaliTest[1699:3728590] jxcore: stopBroadcasting
,2016-01-11 11:54:20.003 ThaliTest[1699:3728590] THEMultipeerSession stopping peer
,2016-01-11 11:54:20.004 ThaliTest[1699:3728590] multipeer session: stop timer
,2016-01-11 11:54:20.006 ThaliTest[1699:3728590] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-11 11:54:20.012 ThaliTest[1699:3728590] jxcore: startBroadcasting
,2016-01-11 11:54:20.015 ThaliTest[1699:3728590] server: starting 1452509660012.1699.tgx45A==
,2016-01-11 11:54:20.016 ThaliTest[1699:3728590] multipeer session: start timer: 0x15e9d620
,2016-01-11 11:54:20.019 ThaliTest[1699:3728590] THEMultipeerSession initialized peer 1452509660012.1699
,2016-01-11 11:54:20.021 ThaliTest[1699:3728590] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-11 11:54:20.025 ThaliTest[1699:3728590] jxcore: stopBroadcasting
,2016-01-11 11:54:20.025 ThaliTest[1699:3728590] THEMultipeerSession stopping peer
,2016-01-11 11:54:20.026 ThaliTest[1699:3728590] multipeer session: stop timer
,2016-01-11 11:54:20.027 ThaliTest[1699:3728590] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-11 11:54:20.399 ThaliTest[1699:3728590] jxcore: startBroadcasting
,2016-01-11 11:54:20.403 ThaliTest[1699:3728590] server: starting 1452509660399.1699.MI0QPQ==
2016-01-11 11:54:20.404 ThaliTest[1699:3728590] multipeer session: start timer: 0x1450d6a0
2016-01-11 11:54:20.405 ThaliTest[1699:3728590] THEMultipeerSession in,itialized peer 1452509660399.1699
2016-01-11 11:54:20.405 ThaliTest[1699:3728590] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-11 11:54:20.408 ThaliTest[1699:3728590] jxcore: startBroadcasting
,2016-01-11 11:54:20.409 ThaliTest[1699:3728590] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
2016-01-11 11:54:20.411 ThaliTest[1699:3728590] jxcore: stopBroadcasting
2016-01-11 11:54:20.411 ThaliTest[1699:3728590] THEMult,ipeerSession stopping peer
2016-01-11 11:54:20.412 ThaliTest[1699:3728590] multipeer session: stop timer
2016-01-11 11:54:20.412 ThaliTest[1699:3728590] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-11 11:54:20.780 ThaliTest[1699:3728590] jxcore: startBroadcasting
,2016-01-11 11:54:20.785 ThaliTest[1699:3728590] server: starting 1452509660779.1699.UKZrKg==
2016-01-11 11:54:20.785 ThaliTest[1699:3728590] multipeer session: start timer: 0x145e6940
2016-01-11 11:54:20.786 ThaliTest[1699:3728590] THEMultipeerSession in,itialized peer 1452509660779.1699
2016-01-11 11:54:20.786 ThaliTest[1699:3728590] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-11 11:54:20.788 ThaliTest[1699:3728590] jxcore: connect foobar
201,6-01-11 11:54:20.789 ThaliTest[1699:3728590] client: unknown peer foobar
,2016-01-11 11:54:20.789 ThaliTest[1699:3728590] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
2016-01-11 11:54:20.806 ThaliTest[1699:3728590] jxcore: stopBroadcasting
2016-01-11 11:54:20.806 ThaliTest[1699:3728590] THEMultip,eerSession stopping peer
2016-01-11 11:54:20.807 ThaliTest[1699:3728590] multipeer session: stop timer
,2016-01-11 11:54:20.807 ThaliTest[1699:3728590] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-11 11:54:21.280 ThaliTest[1699:3728590] jxcore: startBroadcasting
,2016-01-11 11:54:21.283 ThaliTest[1699:3728590] server: starting 1452509661280.1699.qJuePw==
2016-01-11 11:54:21.283 ThaliTest[1699:3728590] multipeer session: start timer: 0x15ea2300
2016-01-11 11:54:21.284 ThaliTest[1699:3728590] THEMultipeerSession in,itialized peer 1452509661280.1699
2016-01-11 11:54:21.284 ThaliTest[1699:3728590] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
,2016-01-11 11:54:21.286 ThaliTest[1699:3728590] jxcore: disconnect
2016-01-11 11:54:21.286 ThaliTest[1699:3728590] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 
2016-01-11 11:54:21.289 ThaliTest[1699:3728590] jxcore: stopBroadcasting
2016-01-11 11:54:21.289 ThaliTest[1699:3728590] THEMultipeerSession stopping peer
2016-01-11 11:54:21.290 ThaliTest[1699:372859,0] multipeer session: stop timer
2016-01-11 11:54:21.290 ThaliTest[1699:3728590] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-11 11:54:21.367 ThaliTest[1699:3728590] jxcore: startBroadcasting
,2016-01-11 11:54:21.369 ThaliTest[1699:3728590] server: starting 1452509661366.1699.C11Mzw==
2016-01-11 11:54:21.370 ThaliTest[1699:3728590] multipeer session: start timer: 0x15cf4890
2016-01-11 11:54:21.370 ThaliTest[1699:3728590] THEMultipeerSession in,itialized peer 1452509661366.1699
2016-01-11 11:54:21.371 ThaliTest[1699:3728590] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-11 11:54:22.636 ThaliTest[1699:3728376] client: found peer: 1452509661382.1220.V/ONYw==
,2016-01-11 11:54:22.638 ThaliTest[1699:3728590] jxcore: connect 1452509661382.1220.V/ONYw==
2016-01-11 11:54:22.638 ThaliTest[1699:3728590] client session: connect
2016-01-11 11:54:22.638 ThaliTest[1699:3728590] client session: stateChange:0->1 1452509661382.1220.V/ONYw==
,2016-01-11 11:54:23.253 ThaliTest[1699:3728376] multipeer session: reset timer
2016-01-11 11:54:23.253 ThaliTest[1699:3728376] multipeer session: stop timer
2016-01-11 11:54:23.253 ThaliTest[1699:3728376] multipeer session: start timer: 0x15cf4890
2016-,01-11 11:54:23.253 ThaliTest[1699:3728376] server session: connect
2016-01-11 11:54:23.254 ThaliTest[1699:3728376] server session: stateChange:0->1 1452509661382.1220
2016-01-11 11:54:23.257 ThaliTest[1699:3728376] server: accepting invitation 1452509661382.1220
,2016-01-11 11:54:25.834 ThaliTest[1699:3729484] server session: connected
2016-01-11 11:54:25.836 ThaliTest[1699:3729484] server session: stateChange:1->2 1452509661382.1220
,2016-01-11 11:54:25.840 ThaliTest[1699:3728376] server relay: socket disconnected
2016-01-11 11:54:25.841 ThaliTest[1699:3728376] server relay: 0x15d36c80 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-11 11:54:25.901 ThaliTest[1699:3729479] client session: connected
,2016-01-11 11:54:25.901 ThaliTest[1699:3729479] client session: stateChange:1->2 1452509661382.1220.V/ONYw==
,2016-01-11 11:54:25.904 ThaliTest[1699:3729484] server session: not connected 1452509661382.1220
,2016-01-11 11:54:25.928 ThaliTest[1699:3729483] client session: fireConnectCallback: 1452509661382.1220.V/ONYw==
2016-01-11 11:54:25.928 ThaliTest[1699:3729483] jxcore: connect: success
ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2016-01-11 11:54:25.931 ThaliTest[1699:3728590] jxcore: disconnect
2016-01-11 11:54:25.931 ThaliTest[1699:3728590] client session: disconnectFromPeer: 1452509661382.1220.V/ONYw==
2016-01-11 11:54:25.932 ThaliTest[1699:3728590] client session: disconnect
2016-01-11 11:54:25.932 ThaliTest[1699:3728590] client session: stateChange:2->0 1452509661382.1220.V/ONYw==
,2016-01-11 11:54:25.993 ThaliTest[1699:3728590] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-11 11:54:26.147 ThaliTest[1699:3728590] jxcore: stopBroadcasting
2016-01-11 11:54:26.147 ThaliTest[1699:3728590] THEMultipeerSession stopping peer
2016-01-11 11:54:26.147 ThaliTest[1699:3728590] multipeer session: stop timer
2016-01-11 11:54:26.,147 ThaliTest[1699:3728590] server session: disconnect
2016-01-11 11:54:26.148 ThaliTest[1699:3728590] server session: stateChange:2->0 1452509661382.1220
2016-01-11 11:54:26.148 ThaliTest[1699:3728590] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-11 11:54:26.476 ThaliTest[1699:3728590] jxcore: startBroadcasting
,2016-01-11 11:54:26.478 ThaliTest[1699:3728590] server: starting 1452509666476.1699.ArKldA==
2016-01-11 11:54:26.478 ThaliTest[1699:3728590] multipeer session: start timer: 0x14612430
2016-01-11 11:54:26.478 ThaliTest[1699:3728590] THEMultipeerSession initialized peer 1452509666476.1699
2016-01-11 11:54:26.479 ThaliTest[1699:3728590] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-11 11:54:27.271 ThaliTest[1699:3728376] client: found peer: 1452509661382.1220.V/ONYw==
2016-01-11 11:54:27.272 ThaliTest[1699:3728590] jxcore: connect 1452509661382.1220.V/ONYw==
2016-01-11 11:54:27.272 ThaliTest[1699:3728590] client session: co,nnect
2016-01-11 11:54:27.272 ThaliTest[1699:3728590] client session: stateChange:0->1 1452509661382.1220.V/ONYw==
,2016-01-11 11:54:27.843 ThaliTest[1699:3728376] client: lost peer: 1452509661382.1220.V/ONYw==
2016-01-11 11:54:27.843 ThaliTest[1699:3728376] client session: onPeerLost: 1452509661382.1220.V/ONYw==
2016-01-11 11:54:27.843 ThaliTest[1699:3728376] client ,session: onLinkFailure: 1452509661382.1220.V/ONYw==
2016-01-11 11:54:27.843 ThaliTest[1699:3728376] client session: disconnect
2016-01-11 11:54:27.843 ThaliTest[1699:3728376] client session: stateChange:1->0 1452509661382.1220.V/ONYw==
2016-01-11 11:54:,27.843 ThaliTest[1699:3728376] client session: fireConnectCallback: 1452509661382.1220.V/ONYw==
2016-01-11 11:54:27.844 ThaliTest[1699:3728376] jxcore: connect: fail: Peer disconnected
2016-01-11 11:54:27.845 ThaliTest[1699:3728376] client: found peer: 1,452509666496.1220./vaZJQ==
2016-01-11 11:54:27.846 ThaliTest[1699:3728590] jxcore: connect 1452509666496.1220./vaZJQ==
2016-01-11 11:54:27.846 ThaliTest[1699:3728590] client session: connect
2016-01-11 11:54:27.846 ThaliTest[1699:3728590] client session,: stateChange:0->1 1452509666496.1220./vaZJQ==
,2016-01-11 11:54:28.030 ThaliTest[1699:3728376] multipeer session: reset timer
2016-01-11 11:54:28.030 ThaliTest[1699:3728376] multipeer session: stop timer
2016-01-11 11:54:28.030 ThaliTest[1699:3728376] multipeer session: start timer: 0x14612430
2016-01-11 11:54:28.030 ThaliTest[1699:3728376] server session: connect
2016-01-11 11:54:28.030 ThaliTest[1699:3728376] server session: stateChange:0->1 1452509666496.1220
2016-01-11 11:54:28.036 ThaliTest[1699:3728376] server: accepting invitation 1452509666496.1220
,2016-01-11 11:54:28.851 ThaliTest[1699:3728590] jxcore: connect 1452509661382.1220.V/ONYw==
2016-01-11 11:54:28.851 ThaliTest[1699:3728590] client: connect: unreachable 1452509661382.1220.V/ONYw==
2016-01-11 11:54:28.851 ThaliTest[1699:3728590] jxcore: connect: fail: Peer unreachable
,2016-01-11 11:54:30.598 ThaliTest[1699:3729484] server session: connected
2016-01-11 11:54:30.598 ThaliTest[1699:3729484] server session: stateChange:1->2 1452509666496.1220
,2016-01-11 11:54:30.666 ThaliTest[1699:3728376] server relay: socket disconnected
2016-01-11 11:54:30.666 ThaliTest[1699:3728376] server relay: 0x15de9ed0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-11 11:54:30.677 ThaliTest[1699:3729481] server session: not connected 1452509666496.1220
,2016-01-11 11:54:30.728 ThaliTest[1699:3729481] client session: connected
2016-01-11 11:54:30.728 ThaliTest[1699:3729481] client session: stateChange:1->2 1452509666496.1220./vaZJQ==
,2016-01-11 11:54:30.738 ThaliTest[1699:3729479] client session: fireConnectCallback: 1452509666496.1220./vaZJQ==
2016-01-11 11:54:30.740 ThaliTest[1699:3729479] jxcore: connect: success
ok 79 Should be able to connect without error
ok 80 Port should be ,within range
2016-01-11 11:54:30.742 ThaliTest[1699:3728590] jxcore: connect 1452509666496.1220./vaZJQ==
2016-01-11 11:54:30.742 ThaliTest[1699:3728590] client: already connect(ing/ed) to 1452509666496.1220./vaZJQ==
2016-01-11 11:54:30.742 ThaliTest[169,9:3728590] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
,2016-01-11 11:54:30.743 ThaliTest[1699:3728590] jxcore: disconnect
2016-01-11 11:54:30.744 ThaliTest[1699:3728590] client session: disconnectFromPeer: 1452509666496.1220./vaZJQ==
2016-01-11 11:54:30.744 ThaliTest[1699:3728590] client session: disconnect
2016-01-11 11:54:30.744 ThaliTest[1699:3728590] client session: stateChange:2->0 1452509666496.1220./vaZJQ==
,2016-01-11 11:54:30.755 ThaliTest[1699:3728590] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
2016-01-11 11:54:30.784 ThaliTest[1699:3728590] jxcore: stopBroadcasting
2016-01-11 11:54:30.784 ThaliTest[1699:3728590] THEMultipeerSession stopping peer
2016-01-11 11:54:30.785 ThaliTest[1699:3728590] multipeer session: stop t,imer
2016-01-11 11:54:30.785 ThaliTest[1699:3728590] server session: disconnect
2016-01-11 11:54:30.785 ThaliTest[1699:3728590] server session: stateChange:2->0 1452509666496.1220
,2016-01-11 11:54:30.785 ThaliTest[1699:3728590] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-11 11:54:32.384 ThaliTest[1699:3728590] jxcore: startBroadcasting
,2016-01-11 11:54:32.386 ThaliTest[1699:3728590] server: starting 1452509672384.1699.WepvLA==
2016-01-11 11:54:32.386 ThaliTest[1699:3728590] multipeer session: start timer: 0x159b67d0
2016-01-11 11:54:32.386 ThaliTest[1699:3728590] THEMultipeerSession in,itialized peer 1452509672384.1699
2016-01-11 11:54:32.387 ThaliTest[1699:3728590] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-11 11:54:33.533 ThaliTest[1699:3728376] client: found peer: 1452509672398.1220.C+LQdg==
2016-01-11 11:54:33.534 ThaliTest[1699:3728590] jxcore: connect 1452509672398.1220.C+LQdg==
2016-01-11 11:54:33.535 ThaliTest[1699:3728590] client session: co,nnect
2016-01-11 11:54:33.535 ThaliTest[1699:3728590] client session: stateChange:0->1 1452509672398.1220.C+LQdg==
,2016-01-11 11:54:33.666 ThaliTest[1699:3728376] multipeer session: reset timer
2016-01-11 11:54:33.666 ThaliTest[1699:3728376] multipeer session: stop timer
,2016-01-11 11:54:33.666 ThaliTest[1699:3728376] multipeer session: start timer: 0x159b67d0
2016-01-11 11:54:33.666 ThaliTest[1699:3728376] server session: connect
2016-01-11 11:54:33.666 ThaliTest[1699:3728376] server session: stateChange:0->1 1452509672398.1220
,2016-01-11 11:54:33.670 ThaliTest[1699:3728376] server: accepting invitation 1452509672398.1220
,2016-01-11 11:54:36.102 ThaliTest[1699:3729484] client session: connected
2016-01-11 11:54:36.102 ThaliTest[1699:3729484] client session: stateChange:1->2 1452509672398.1220.C+LQdg==
,2016-01-11 11:54:36.118 ThaliTest[1699:3729479] client session: fireConnectCallback: 1452509672398.1220.C+LQdg==
2016-01-11 11:54:36.118 ThaliTest[1699:3729479] jxcore: connect: success
ok 84 Should be able to connect without error
,ok 85 Port should be within range
,2016-01-11 11:54:36.120 ThaliTest[1699:3728590] jxcore: disconnect
2016-01-11 11:54:36.120 ThaliTest[1699:3728590] client session: disconnectFromPeer: 1452509672398.1220.C+LQdg==
2016-01-11 11:54:36.120 ThaliTest[1699:3728590] client session: disconnect
2016-01-11 11:54:36.120 ThaliTest[1699:3728590] client session: stateChange:2->0 1452509672398.1220.C+LQdg==
,2016-01-11 11:54:36.124 ThaliTest[1699:3728590] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
2016-01-11 11:54:36.125 ThaliTest[1699:3728590] jxcore: disconnect
2016-01-11 11:54:36.125 ThaliTest[1699:3728590] jxcore: disconnect: fail
ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-11 11:54:36.223 ThaliTest[1699:3729481] server session: connected
2016-01-11 11:54:36.223 ThaliTest[1699:3729481] server session: stateChange:1->2 1452509672398.1220
,2016-01-11 11:54:36.227 ThaliTest[1699:3728376] server relay: socket disconnected
2016-01-11 11:54:36.227 ThaliTest[1699:3728376] server relay: 0x145d2b20 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-11 11:54:36.283 ThaliTest[1699:3729553] server session: not connected 1452509672398.1220
,calling stopBroadcasting
,2016-01-11 11:54:36.622 ThaliTest[1699:3728590] jxcore: stopBroadcasting
2016-01-11 11:54:36.622 ThaliTest[1699:3728590] THEMultipeerSession stopping peer
2016-01-11 11:54:36.622 ThaliTest[1699:3728590] multipeer session: stop timer
2016-01-11 11:54:36.,623 ThaliTest[1699:3728590] server session: disconnect
2016-01-11 11:54:36.623 ThaliTest[1699:3728590] server session: stateChange:2->0 1452509672398.1220
2016-01-11 11:54:36.623 ThaliTest[1699:3728590] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,2016-01-11 11:54:37.139 ThaliTest[1699:3728590] jxcore: startBroadcasting
,2016-01-11 11:54:37.142 ThaliTest[1699:3728590] server: starting 1452509677139.1699.NryW3g==
2016-01-11 11:54:37.142 ThaliTest[1699:3728590] multipeer session: start timer: 0x145ebee0
2016-01-11 11:54:37.142 ThaliTest[1699:3728590] THEMultipeerSession in,itialized peer 1452509677139.1699
2016-01-11 11:54:37.142 ThaliTest[1699:3728590] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
echo server started
,2016-01-11 11:54:37.744 ThaliTest[1699:3728376] client: found peer: 1452509672398.1220.C+LQdg==
[{"peerIdentifier":"1452509672398.1220.C+LQdg==","peerName":"(null)","peerAvailable":true}]
,2016-01-11 11:54:37.746 ThaliTest[1699:3728590] jxcore: connect 1452509672398.1220.C+LQdg==
2016-01-11 11:54:37.747 ThaliTest[1699:3728590] client session: connect
2016-01-11 11:54:37.747 ThaliTest[1699:3728590] client session: stateChange:0->1 1452509672398.1220.C+LQdg==
,2016-01-11 11:54:38.271 ThaliTest[1699:3728376] client: lost peer: 1452509672398.1220.C+LQdg==
2016-01-11 11:54:38.271 ThaliTest[1699:3728376] client session: onPeerLost: 1452509672398.1220.C+LQdg==
2016-01-11 11:54:38.271 ThaliTest[1699:3728376] client ,session: onLinkFailure: 1452509672398.1220.C+LQdg==
2016-01-11 11:54:38.271 ThaliTest[1699:3728376] client session: disconnect
2016-01-11 11:54:38.272 ThaliTest[1699:3728376] client session: stateChange:1->0 1452509672398.1220.C+LQdg==
2016-01-11 11:54:,38.272 ThaliTest[1699:3728376] client session: fireConnectCallback: 1452509672398.1220.C+LQdg==
2016-01-11 11:54:38.272 ThaliTest[1699:3728376] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1452509672398.1220.C+LQdg==","peerName":"(null)","peerAvailable":false}]
,2016-01-11 11:54:38.392 ThaliTest[1699:3728376] multipeer session: reset timer
2016-01-11 11:54:38.392 ThaliTest[1699:3728376] multipeer session: stop timer
2016-01-11 11:54:38.393 ThaliTest[1699:3728376] multipeer session: start timer: 0x145ebee0
2016-,01-11 11:54:38.393 ThaliTest[1699:3728376] server session: connect
2016-01-11 11:54:38.393 ThaliTest[1699:3728376] server session: stateChange:0->1 1452509677154.1220
2016-01-11 11:54:38.396 ThaliTest[1699:3728376] server: accepting invitation 1452509677154.1220
,2016-01-11 11:54:38.404 ThaliTest[1699:3728376] client: found peer: 1452509677154.1220.2HrfNw==
[{"peerIdentifier":"1452509677154.1220.2HrfNw==","peerName":"(null)","peerAvailable":true}]
2016-01-11 11:54:38.405 ThaliTest[1699:3728590] jxcore: connect 14,52509677154.1220.2HrfNw==
2016-01-11 11:54:38.407 ThaliTest[1699:3728590] client session: connect
2016-01-11 11:54:38.407 ThaliTest[1699:3728590] client session: stateChange:0->1 1452509677154.1220.2HrfNw==
,2016-01-11 11:54:39.283 ThaliTest[1699:3728590] jxcore: connect 1452509672398.1220.C+LQdg==
,2016-01-11 11:54:39.283 ThaliTest[1699:3728590] client: connect: unreachable 1452509672398.1220.C+LQdg==
,2016-01-11 11:54:39.283 ThaliTest[1699:3728590] jxcore: connect: fail: Peer unreachable
,2016-01-11 11:54:40.951 ThaliTest[1699:3729481] server session: connected
2016-01-11 11:54:40.951 ThaliTest[1699:3729481] server session: stateChange:1->2 1452509677154.1220
,2016-01-11 11:54:41.069 ThaliTest[1699:3728376] server relay: connected (to port: 5001)
2016-01-11 11:54:41.078 ThaliTest[1699:3729481] client session: connected
,2016-01-11 11:54:41.078 ThaliTest[1699:3729481] client session: stateChange:1->2 1452509677154.1220.2HrfNw==
,2016-01-11 11:54:41.099 ThaliTest[1699:3729481] client session: fireConnectCallback: 1452509677154.1220.2HrfNw==
2016-01-11 11:54:41.100 ThaliTest[1699:3729481] jxcore: connect: success
ok 89 Should be able to connect without error
,ok 90 Port should be within range
,ok 91 First connect should succeed
,2016-01-11 11:54:41.119 ThaliTest[1699:3728376] client: relay established
2016-01-11 11:54:41.119 ThaliTest[1699:3728376] client: new accepted socket: 0x146e5a90
,ok 92 the test messages should be equal
,ok 93 First send should succeed
,2016-01-11 11:54:41.183 ThaliTest[1699:3728376] client: socket closed
,2016-01-11 11:54:41.184 ThaliTest[1699:3728376] client relay: socket disconnected
2016-01-11 11:54:41.184 ThaliTest[1699:3728376] client relay: 0x146e5a90 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-01-11 11:54:41.184 ThaliTest[1699:3728376] client session: socket closed: 1452509677154.1220.2HrfNw==
2016-01-11 11:54:41.184 ThaliTest[1699:3728376] client session: onLinkFailure: 1452509677154.1220.2HrfNw==
2016-01-11 11:54:41.184 ThaliTest[1699:3728376] client session: disconnect
,2016-01-11 11:54:41.184 ThaliTest[1699:3728376] client session: stateChange:2->0 1452509677154.1220.2HrfNw==
,2016-01-11 11:54:41.189 ThaliTest[1699:3728376] client session: fireConnectionErrorEvent: 1452509677154.1220.2HrfNw==
,2016-01-11 11:54:41.196 ThaliTest[1699:3729483] server session: not connected 1452509677154.1220
,2016-01-11 11:54:41.199 ThaliTest[1699:3728590] jxcore: connect 1452509677154.1220.2HrfNw==
,2016-01-11 11:54:41.202 ThaliTest[1699:3728590] client session: connect
,2016-01-11 11:54:41.202 ThaliTest[1699:3728590] client session: stateChange:0->1 1452509677154.1220.2HrfNw==
,2016-01-11 11:54:41.290 ThaliTest[1699:3728376] multipeer session: reset timer
,2016-01-11 11:54:41.290 ThaliTest[1699:3728376] multipeer session: stop timer
2016-01-11 11:54:41.290 ThaliTest[1699:3728376] multipeer session: start timer: 0x145ebee0
,2016-01-11 11:54:41.291 ThaliTest[1699:3728376] server: disconnecting to refresh session (1452509677154.1220)
2016-01-11 11:54:41.291 ThaliTest[1699:3728376] server session: disconnect
,2016-01-11 11:54:41.291 ThaliTest[1699:3728376] server session: stateChange:2->0 1452509677154.1220
,2016-01-11 11:54:41.293 ThaliTest[1699:3728376] server session: connect
,2016-01-11 11:54:41.293 ThaliTest[1699:3728376] server session: stateChange:0->1 1452509677154.1220
,2016-01-11 11:54:41.299 ThaliTest[1699:3728376] server: accepting invitation 1452509677154.1220
,2016-01-11 11:54:43.919 ThaliTest[1699:3729553] server session: connected
2016-01-11 11:54:43.919 ThaliTest[1699:3729553] server session: stateChange:1->2 1452509677154.1220
2016-01-11 11:54:43.920 ThaliTest[1699:3729553] client session: connected
2016-,01-11 11:54:43.920 ThaliTest[1699:3729553] client session: stateChange:1->2 1452509677154.1220.2HrfNw==
,2016-01-11 11:54:43.963 ThaliTest[1699:3728376] server relay: connected (to port: 5001)
,2016-01-11 11:54:44.027 ThaliTest[1699:3729553] client session: fireConnectCallback: 1452509677154.1220.2HrfNw==
2016-01-11 11:54:44.027 ThaliTest[1699:3729553] jxcore: connect: success
ok 94 Should be able to connect without error
ok 95 Port should be ,within range
ok 96 Second connect should succeed
,2016-01-11 11:54:44.039 ThaliTest[1699:3728376] client: relay established
2016-01-11 11:54:44.039 ThaliTest[1699:3728376] client: new accepted socket: 0x15ff5330
,ok 97 the test messages should be equal
ok 98 Second send should succeed
# setup
,2016-01-11 11:54:44.115 ThaliTest[1699:3728376] client: socket closed
2016-01-11 11:54:44.115 ThaliTest[1699:3728376] client relay: socket disconnected
2016-01-11 11:54:44.115 ThaliTest[1699:3728376] client relay: 0x15ff5330 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-11 11:54:44.115 ThaliTest[1699:3728376] client session: socket closed: 1452509677154.1220.2HrfNw==
2016-01-11 ,11:54:44.115 ThaliTest[1699:3728376] client session: onLinkFailure: 1452509677154.1220.2HrfNw==
2016-01-11 11:54:44.115 ThaliTest[1699:3728376] client session: disconnect
2016-01-11 11:54:44.115 ThaliTest[1699:3728376] client session: stateChange:2->0 14,52509677154.1220.2HrfNw==
,2016-01-11 11:54:44.122 ThaliTest[1699:3728376] client session: fireConnectionErrorEvent: 1452509677154.1220.2HrfNw==
,2016-01-11 11:54:44.148 ThaliTest[1699:3729553] server session: not connected 1452509677154.1220
,calling stopBroadcasting
,2016-01-11 11:54:44.424 ThaliTest[1699:3728590] jxcore: stopBroadcasting
2016-01-11 11:54:44.425 ThaliTest[1699:3728590] THEMultipeerSession stopping peer
2016-01-11 11:54:44.425 ThaliTest[1699:3728590] multipeer session: stop timer
2016-01-11 11:54:44.,425 ThaliTest[1699:3728590] server session: disconnect
2016-01-11 11:54:44.425 ThaliTest[1699:3728590] server session: stateChange:2->0 1452509677154.1220
2016-01-11 11:54:44.427 ThaliTest[1699:3728590] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined
,# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/56EF9D3A-44B5-45C6-B54A-904DB98D0E39/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 99 starting event should occur in right order
,2016-01-11 11:54:45.870 ThaliTest[1699:3728590] jxcore: startBroadcasting
,2016-01-11 11:54:45.872 ThaliTest[1699:3728590] server: starting 3q9hNW6L8GZWNOM3oPFK1w.5NaSqw==
2016-01-11 11:54:45.872 ThaliTest[1699:3728590] multipeer session: start timer: 0x15afb2d0
2016-01-11 11:54:45.873 ThaliTest[1699:3728590] THEMultipeerSessio,n initialized peer 3q9hNW6L8GZWNOM3oPFK1w
2016-01-11 11:54:45.873 ThaliTest[1699:3728590] jxcore: startBroadcasting: success
ok 100 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
,ok 101 stopping event should occur in right order
About to call stopBroadcasting
,2016-01-11 11:54:45.875 ThaliTest[1699:3728590] jxcore: stopBroadcasting
2016-01-11 11:54:45.882 ThaliTest[1699:3728590] THEMultipeerSession stopping peer
2016-01-11 11:54:45.882 ThaliTest[1699:3728590] multipeer session: stop timer
2016-01-11 11:54:45.882 ThaliTest[1699:3728590] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
ok 102 stopped event should occur in right order
mux server bridge listener closed
# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/56EF9D3A-44B5-45C6-B54A-904DB98D0E39/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-11 11:54:46.473 ThaliTest[1699:3728590] jxcore: startBroadcasting
,2016-01-11 11:54:46.475 ThaliTest[1699:3728590] server: starting 3q9hNW6L8GZWNOM3oPFK1w.LafFwA==
2016-01-11 11:54:46.475 ThaliTest[1699:3728590] multipeer session: start timer: 0x15aaef70
2016-01-11 11:54:46.476 ThaliTest[1699:3728590] THEMultipeerSessio,n initialized peer 3q9hNW6L8GZWNOM3oPFK1w
2016-01-11 11:54:46.476 ThaliTest[1699:3728590] jxcore: startBroadcasting: success
ok 103 getDeviceIdentity should not return an error
ok 104 deviceName should not be null
Now in TRM stop
State of this._isStarted: true
About to call stopBroadcasting
,2016-01-11 11:54:46.478 ThaliTest[1699:3728590] jxcore: stopBroadcasting
2016-01-11 11:54:46.478 ThaliTest[1699:3728590] THEMultipeerSession stopping peer
2016-01-11 11:54:46.478 ThaliTest[1699:3728590] multipeer session: stop timer
2016-01-11 11:54:46.,478 ThaliTest[1699:3728590] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,mux server bridge listener closed
Tests Complete
,Total: 0	Passed: 0	Failed: 0
****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
