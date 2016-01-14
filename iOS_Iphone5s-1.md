#### Test 55613145c131883_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55613145c131883/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/308CDE52-8ED7-4638-9B3D-ABE4475DC17A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/308CDE52-8ED7-4638-9B3D-ABE4475DC17A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55613145c131883/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55613145c131883/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55702"
,(lldb)     command script import "/tmp/308CDE52-8ED7-4638-9B3D-ABE4475DC17A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-14 13:15:50.144 ThaliTest[1926:4434544] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/447A4ED7-621D-4445-B9DC-E8693DE76528/Library/Cookies/Cookies.binarycookies
,2016-01-14 13:15:50.402 ThaliTest[1926:4434544] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-14 13:15:50.403 ThaliTest[1926:4434544] Multi-tasking -> Device: YES, App: YES
,2016-01-14 13:15:50.410 ThaliTest[1926:4434544] Unlimited access to network resources
,2016-01-14 13:15:50.420 ThaliTest[1926:4434544] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-14 13:15:54.354 ThaliTest[1926:4434544] Resetting plugins due to page load.
,2016-01-14 13:15:55.603 ThaliTest[1926:4434544] Finished load of: file:///var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/index.html
,2016-01-14 13:15:55.789 ThaliTest[1926:4434544] JXcore Cordova plugin initializing
,2016-01-14 13:15:55.791 ThaliTest[1926:4434715] JXcore instance initializing
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
ok 35 should be equal
,# setup
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
,2016-01-14 13:21:17.819 ThaliTest[1926:4434715] jxcore: startBroadcasting
,2016-01-14 13:21:17.826 ThaliTest[1926:4434715] server: starting 1452774077819.1926.GiyqYg==
,2016-01-14 13:21:17.827 ThaliTest[1926:4434715] multipeer session: start timer: 0x163818e0
2016-01-14 13:21:17.827 ThaliTest[1926:4434715] THEMultipeerSession initialized peer 1452774077819.1926
2016-01-14 13:21:17.828 ThaliTest[1926:4434715] jxcore: sta,rtBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2016-01-14 13:21:17.829 ThaliTest[1926:4434715] jxcore: stopBroadcasting
2016-01-14 13:21:17.829 ThaliTest[1926:4434715] THEMultipeerSession stopping peer
2016-01-14 1,3:21:17.829 ThaliTest[1926:4434715] multipeer session: stop timer
2016-01-14 13:21:17.830 ThaliTest[1926:4434715] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
,2016-01-14 13:21:17.831 ThaliTest[1926:4434715] jxcore: startBroadcasting
,2016-01-14 13:21:17.838 ThaliTest[1926:4434715] server: starting 1452774077831.1926.dLHevw==
2016-01-14 13:21:17.838 ThaliTest[1926:4434715] multipeer session: start timer: 0x14d0ab50
2016-01-14 13:21:17.838 ThaliTest[1926:4434715] THEMultipeerSession in,itialized peer 1452774077831.1926
2016-01-14 13:21:17.839 ThaliTest[1926:4434715] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
,2016-01-14 13:21:17.840 ThaliTest[1926:4434715] jxcore: stopBroadcasting
,2016-01-14 13:21:17.840 ThaliTest[1926:4434715] THEMultipeerSession stopping peer
,2016-01-14 13:21:17.841 ThaliTest[1926:4434715] multipeer session: stop timer
2016-01-14 13:21:17.841 ThaliTest[1926:4434715] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
,2016-01-14 13:21:17.842 ThaliTest[1926:4434715] jxcore: startBroadcasting
,2016-01-14 13:21:17.846 ThaliTest[1926:4434715] server: starting 1452774077842.1926.lqrRcw==
2016-01-14 13:21:17.847 ThaliTest[1926:4434715] multipeer session: start timer: 0x16558e50
2016-01-14 13:21:17.847 ThaliTest[1926:4434715] THEMultipeerSession in,itialized peer 1452774077842.1926
2016-01-14 13:21:17.847 ThaliTest[1926:4434715] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2016-01-14 13:21:17.848 ThaliTest[1926:4434715] jxcore: stopBroadcasting
2,016-01-14 13:21:17.848 ThaliTest[1926:4434715] THEMultipeerSession stopping peer
2016-01-14 13:21:17.848 ThaliTest[1926:4434715] multipeer session: stop timer
2016-01-14 13:21:17.849 ThaliTest[1926:4434715] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2016-01-14 13:21:17.858 ThaliTest[1926:4434715] jxcore: startBroadcasting
,2016-01-14 13:21:17.862 ThaliTest[1926:4434715] server: starting 1452774077855.1926.aM/M8Q==
,2016-01-14 13:21:17.865 ThaliTest[1926:4434715] multipeer session: start timer: 0x14d18ed0
,2016-01-14 13:21:17.866 ThaliTest[1926:4434715] THEMultipeerSession initialized peer 1452774077855.1926
,2016-01-14 13:21:17.866 ThaliTest[1926:4434715] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2016-01-14 13:21:17.868 ThaliTest[1926:4434715] jxcore: stopBroadcasting
,2016-01-14 13:21:17.869 ThaliTest[1926:4434715] THEMultipeerSession stopping peer
,2016-01-14 13:21:17.869 ThaliTest[1926:4434715] multipeer session: stop timer
,2016-01-14 13:21:17.871 ThaliTest[1926:4434715] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2016-01-14 13:21:17.874 ThaliTest[1926:4434715] jxcore: startBroadcasting
,2016-01-14 13:21:17.876 ThaliTest[1926:4434715] server: starting 1452774077873.1926.Nhae0g==
,2016-01-14 13:21:17.877 ThaliTest[1926:4434715] multipeer session: start timer: 0x161d4890
,2016-01-14 13:21:17.880 ThaliTest[1926:4434715] THEMultipeerSession initialized peer 1452774077873.1926
,2016-01-14 13:21:17.881 ThaliTest[1926:4434715] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2016-01-14 13:21:17.883 ThaliTest[1926:4434715] jxcore: stopBroadcasting
,2016-01-14 13:21:17.883 ThaliTest[1926:4434715] THEMultipeerSession stopping peer
,2016-01-14 13:21:17.884 ThaliTest[1926:4434715] multipeer session: stop timer
,2016-01-14 13:21:17.887 ThaliTest[1926:4434715] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-14 13:21:17.889 ThaliTest[1926:4434715] jxcore: startBroadcasting
,2016-01-14 13:21:17.891 ThaliTest[1926:4434715] server: starting 1452774077888.1926.jJ3qbA==
,2016-01-14 13:21:17.896 ThaliTest[1926:4434715] multipeer session: start timer: 0x16271e90
,2016-01-14 13:21:17.902 ThaliTest[1926:4434715] THEMultipeerSession initialized peer 1452774077888.1926
,2016-01-14 13:21:17.903 ThaliTest[1926:4434715] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-14 13:21:17.905 ThaliTest[1926:4434715] jxcore: stopBroadcasting
,2016-01-14 13:21:17.906 ThaliTest[1926:4434715] THEMultipeerSession stopping peer
,2016-01-14 13:21:17.906 ThaliTest[1926:4434715] multipeer session: stop timer
,2016-01-14 13:21:17.907 ThaliTest[1926:4434715] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-14 13:21:17.911 ThaliTest[1926:4434715] jxcore: startBroadcasting
,2016-01-14 13:21:17.913 ThaliTest[1926:4434715] server: starting 1452774077910.1926.hPIl+g==
,2016-01-14 13:21:17.914 ThaliTest[1926:4434715] multipeer session: start timer: 0x161ad640
,2016-01-14 13:21:17.916 ThaliTest[1926:4434715] THEMultipeerSession initialized peer 1452774077910.1926
,2016-01-14 13:21:17.918 ThaliTest[1926:4434715] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-14 13:21:17.920 ThaliTest[1926:4434715] jxcore: stopBroadcasting
,2016-01-14 13:21:17.920 ThaliTest[1926:4434715] THEMultipeerSession stopping peer
,2016-01-14 13:21:17.921 ThaliTest[1926:4434715] multipeer session: stop timer
,2016-01-14 13:21:17.923 ThaliTest[1926:4434715] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-14 13:21:17.925 ThaliTest[1926:4434715] jxcore: startBroadcasting
,2016-01-14 13:21:17.928 ThaliTest[1926:4434715] server: starting 1452774077925.1926.tHmfLQ==
,2016-01-14 13:21:17.930 ThaliTest[1926:4434715] multipeer session: start timer: 0x16577b70
,2016-01-14 13:21:17.932 ThaliTest[1926:4434715] THEMultipeerSession initialized peer 1452774077925.1926
,2016-01-14 13:21:17.932 ThaliTest[1926:4434715] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-14 13:21:17.934 ThaliTest[1926:4434715] jxcore: stopBroadcasting
,2016-01-14 13:21:17.934 ThaliTest[1926:4434715] THEMultipeerSession stopping peer
,2016-01-14 13:21:17.935 ThaliTest[1926:4434715] multipeer session: stop timer
,2016-01-14 13:21:17.938 ThaliTest[1926:4434715] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-14 13:21:17.940 ThaliTest[1926:4434715] jxcore: startBroadcasting
,2016-01-14 13:21:17.942 ThaliTest[1926:4434715] server: starting 1452774077939.1926.venROg==
,2016-01-14 13:21:17.943 ThaliTest[1926:4434715] multipeer session: start timer: 0x14e27340
,2016-01-14 13:21:17.946 ThaliTest[1926:4434715] THEMultipeerSession initialized peer 1452774077939.1926
,2016-01-14 13:21:17.947 ThaliTest[1926:4434715] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-14 13:21:17.948 ThaliTest[1926:4434715] jxcore: stopBroadcasting
,2016-01-14 13:21:17.949 ThaliTest[1926:4434715] THEMultipeerSession stopping peer
,2016-01-14 13:21:17.949 ThaliTest[1926:4434715] multipeer session: stop timer
,2016-01-14 13:21:17.950 ThaliTest[1926:4434715] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-14 13:21:17.954 ThaliTest[1926:4434715] jxcore: startBroadcasting
,2016-01-14 13:21:17.956 ThaliTest[1926:4434715] server: starting 1452774077953.1926.UBCKpw==
,2016-01-14 13:21:17.957 ThaliTest[1926:4434715] multipeer session: start timer: 0x14ef6ec0
,2016-01-14 13:21:17.960 ThaliTest[1926:4434715] THEMultipeerSession initialized peer 1452774077953.1926
,2016-01-14 13:21:17.960 ThaliTest[1926:4434715] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-14 13:21:17.962 ThaliTest[1926:4434715] jxcore: stopBroadcasting
,2016-01-14 13:21:17.963 ThaliTest[1926:4434715] THEMultipeerSession stopping peer
,2016-01-14 13:21:17.963 ThaliTest[1926:4434715] multipeer session: stop timer
,2016-01-14 13:21:17.967 ThaliTest[1926:4434715] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-14 13:21:18.172 ThaliTest[1926:4434715] jxcore: startBroadcasting
,2016-01-14 13:21:18.174 ThaliTest[1926:4434715] server: starting 1452774078172.1926.+MSxvg==
2016-01-14 13:21:18.174 ThaliTest[1926:4434715] multipeer session: start timer: 0x160f4950
2016-01-14 13:21:18.174 ThaliTest[1926:4434715] THEMultipeerSession in,itialized peer 1452774078172.1926
2016-01-14 13:21:18.175 ThaliTest[1926:4434715] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
,2016-01-14 13:21:18.176 ThaliTest[1926:4434715] jxcore: startBroadcasting
2016-01-14 13:21:18.176 ThaliTest[1926:4434715] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
2016-01-14 13:21:18.177 ThaliTest[1926:4434715] jxcore,: stopBroadcasting
2016-01-14 13:21:18.177 ThaliTest[1926:4434715] THEMultipeerSession stopping peer
2016-01-14 13:21:18.177 ThaliTest[1926:4434715] multipeer session: stop timer
2016-01-14 13:21:18.178 ThaliTest[1926:4434715] jxcore: stopBroadcasting: ,success
ok 67 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-14 13:21:18.283 ThaliTest[1926:4434715] jxcore: startBroadcasting
,2016-01-14 13:21:18.286 ThaliTest[1926:4434715] server: starting 1452774078283.1926.3tMhUw==
2016-01-14 13:21:18.286 ThaliTest[1926:4434715] multipeer session: start timer: 0x1659c290
2016-01-14 13:21:18.286 ThaliTest[1926:4434715] THEMultipeerSession in,itialized peer 1452774078283.1926
2016-01-14 13:21:18.286 ThaliTest[1926:4434715] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-14 13:21:18.288 ThaliTest[1926:4434715] jxcore: connect foobar
201,6-01-14 13:21:18.288 ThaliTest[1926:4434715] client: unknown peer foobar
2016-01-14 13:21:18.288 ThaliTest[1926:4434715] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
2016-01-14 13:21:18.289 ThaliTest[1926:4434715] jxcore: s,topBroadcasting
2016-01-14 13:21:18.289 ThaliTest[1926:4434715] THEMultipeerSession stopping peer
2016-01-14 13:21:18.290 ThaliTest[1926:4434715] multipeer session: stop timer
2016-01-14 13:21:18.290 ThaliTest[1926:4434715] jxcore: stopBroadcasting: suc,cess
ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-14 13:21:18.613 ThaliTest[1926:4434715] jxcore: startBroadcasting
,2016-01-14 13:21:18.615 ThaliTest[1926:4434715] server: starting 1452774078612.1926.ttwUJw==
2016-01-14 13:21:18.615 ThaliTest[1926:4434715] multipeer session: start timer: 0x1606e790
2016-01-14 13:21:18.616 ThaliTest[1926:4434715] THEMultipeerSession in,itialized peer 1452774078612.1926
2016-01-14 13:21:18.616 ThaliTest[1926:4434715] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-14 13:21:18.617 ThaliTest[1926:4434715] jxcore: disconnect
2016-01,-14 13:21:18.617 ThaliTest[1926:4434715] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
,2016-01-14 13:21:18.618 ThaliTest[1926:4434715] jxcore: stopBroadcasting
2016-01-14 13:21:18.621 ThaliTest[1926:4434715] THEMultipeerSession stopping peer
2016-01-14 13:21:18.621 ThaliTest[1926:4434715] multipeer session: stop timer
2016-01-14 13:21:18.621 ThaliTest[1926:4434715] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-14 13:21:18.706 ThaliTest[1926:4434715] jxcore: startBroadcasting
,2016-01-14 13:21:18.709 ThaliTest[1926:4434715] server: starting 1452774078706.1926.oQcqEw==
2016-01-14 13:21:18.709 ThaliTest[1926:4434715] multipeer session: start timer: 0x1670ede0
2016-01-14 13:21:18.709 ThaliTest[1926:4434715] THEMultipeerSession in,itialized peer 1452774078706.1926
2016-01-14 13:21:18.709 ThaliTest[1926:4434715] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-14 13:21:19.572 ThaliTest[1926:4434544] client: found peer: 1452774078676.1942.iyAIIw==
2016-01-14 13:21:19.573 ThaliTest[1926:4434715] jxcore: connect 1452774078676.1942.iyAIIw==
2016-01-14 13:21:19.573 ThaliTest[1926:4434715] client session: connect
2016-01-14 13:21:19.574 ThaliTest[1926:4434715] client session: stateChange:0->1 1452774078676.1942.iyAIIw==
,2016-01-14 13:21:20.083 ThaliTest[1926:4434544] multipeer session: reset timer
,2016-01-14 13:21:20.084 ThaliTest[1926:4434544] multipeer session: stop timer
,2016-01-14 13:21:20.084 ThaliTest[1926:4434544] multipeer session: start timer: 0x1670ede0
,2016-01-14 13:21:20.085 ThaliTest[1926:4434544] server session: connect
,2016-01-14 13:21:20.086 ThaliTest[1926:4434544] server session: stateChange:0->1 1452774078676.1942
,2016-01-14 13:21:20.091 ThaliTest[1926:4434544] server: accepting invitation 1452774078676.1942
,2016-01-14 13:21:22.482 ThaliTest[1926:4435581] client session: connected
2016-01-14 13:21:22.482 ThaliTest[1926:4435581] client session: stateChange:1->2 1452774078676.1942.iyAIIw==
,2016-01-14 13:21:22.531 ThaliTest[1926:4435584] client session: fireConnectCallback: 1452774078676.1942.iyAIIw==
2016-01-14 13:21:22.531 ThaliTest[1926:4435584] jxcore: connect: success
ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2016-01-14 13:21:22.534 ThaliTest[1926:4434715] jxcore: disconnect
,2016-01-14 13:21:22.537 ThaliTest[1926:4434715] client session: disconnectFromPeer: 1452774078676.1942.iyAIIw==
2016-01-14 13:21:22.538 ThaliTest[1926:4434715] client session: disconnect
2016-01-14 13:21:22.539 ThaliTest[1926:4434715] client session: stateChange:2->0 1452774078676.1942.iyAIIw==
,2016-01-14 13:21:22.604 ThaliTest[1926:4434715] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,2016-01-14 13:21:22.609 ThaliTest[1926:4435583] server session: connected
2016-01-14 13:21:22.609 ThaliTest[1926:4435583] server session: stateChange:1->2 1452774078676.1942
,# setup
,2016-01-14 13:21:22.661 ThaliTest[1926:4434544] server relay: socket disconnected
2016-01-14 13:21:22.662 ThaliTest[1926:4434544] server relay: 0x16324840 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-14 13:21:22.719 ThaliTest[1926:4435583] server session: not connected 1452774078676.1942
,calling stopBroadcasting
2016-01-14 13:21:22.971 ThaliTest[1926:4434715] jxcore: stopBroadcasting
2016-01-14 13:21:22.971 ThaliTest[1926:4434715] THEMultipeerSession stopping peer
2016-01-14 13:21:22.971 ThaliTest[1926:4434715] multipeer session: stop timer
2016-01-14 13:21:22.971 ThaliTest[1926:4434715] server session: disconnect
2016-01-14 13:21:22.971 ThaliTest[1926:4434715] server session: stateChange:2->0 1452774078676.1942
,2016-01-14 13:21:22.972 ThaliTest[1926:4434715] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-14 13:21:23.543 ThaliTest[1926:4434715] jxcore: startBroadcasting
,2016-01-14 13:21:23.546 ThaliTest[1926:4434715] server: starting 1452774083543.1926.t0VUWA==
2016-01-14 13:21:23.546 ThaliTest[1926:4434715] multipeer session: start timer: 0x16725210
2016-01-14 13:21:23.546 ThaliTest[1926:4434715] THEMultipeerSession in,itialized peer 1452774083543.1926
2016-01-14 13:21:23.546 ThaliTest[1926:4434715] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-14 13:21:24.740 ThaliTest[1926:4434544] client: found peer: 1452774083497.1942.IjCRHg==
2016-01-14 13:21:24.741 ThaliTest[1926:4434715] jxcore: connect 1452774083497.1942.IjCRHg==
2016-01-14 13:21:24.741 ThaliTest[1926:4434715] client session: connect
2016-01-14 13:21:24.741 ThaliTest[1926:4434715] client session: stateChange:0->1 1452774083497.1942.IjCRHg==
,2016-01-14 13:21:24.961 ThaliTest[1926:4434544] multipeer session: reset timer
2016-01-14 13:21:24.961 ThaliTest[1926:4434544] multipeer session: stop timer
2016-01-14 13:21:24.962 ThaliTest[1926:4434544] multipeer session: start timer: 0x16725210
2016-01-14 13:21:24.962 ThaliTest[1926:4434544] server session: connect
2016-01-14 13:21:24.962 ThaliTest[1926:4434544] server session: stateChange:0->1 1452774083497.1942
2016-01-14 13:21:24.967 ThaliTest[1926:4434544] server: accepting invitation 1452774083497.1942
,2016-01-14 13:21:27.392 ThaliTest[1926:4435584] client session: connected
2016-01-14 13:21:27.392 ThaliTest[1926:4435584] client session: stateChange:1->2 1452774083497.1942.IjCRHg==
,2016-01-14 13:21:27.397 ThaliTest[1926:4435584] server session: connected
2016-01-14 13:21:27.397 ThaliTest[1926:4435584] server session: stateChange:1->2 1452774083497.1942
,2016-01-14 13:21:27.408 ThaliTest[1926:4435581] client session: fireConnectCallback: 1452774083497.1942.IjCRHg==
2016-01-14 13:21:27.410 ThaliTest[1926:4435581] jxcore: connect: success
ok 79 Should be able to connect without error
ok 80 Port should be within range
2016-01-14 13:21:27.412 ThaliTest[1926:4434715] jxcore: connect 1452774083497.1942.IjCRHg==
2016-01-14 13:21:27.412 ThaliTest[1926:4434715] client: already connect(ing/ed) to 1452774083497.1942.IjCRHg==
2016-01-14 13:21:27.412 ThaliTest[192,6:4434715] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
2016-01-14 13:21:27.413 ThaliTest[1926:4434715] jxcore: disconnect
2016-01-14 13:21:27.413 ThaliTest[1926:4434715] client session: disconnectFromPeer: 1452774083497.,1942.IjCRHg==
2016-01-14 13:21:27.413 ThaliTest[1926:4434715] client session: disconnect
2016-01-14 13:21:27.413 ThaliTest[1926:4434715] client session: stateChange:2->0 1452774083497.1942.IjCRHg==
,2016-01-14 13:21:27.414 ThaliTest[1926:4434544] server relay: socket disconnected
2016-01-14 13:21:27.415 ThaliTest[1926:4434544] server relay: 0x163d93f0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-14 13:21:27.486 ThaliTest[1926:4434715] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,2016-01-14 13:21:27.493 ThaliTest[1926:4435583] server session: not connected 1452774083497.1942
,# setup
,calling stopBroadcasting
2016-01-14 13:21:27.723 ThaliTest[1926:4434715] jxcore: stopBroadcasting
2016-01-14 13:21:27.723 ThaliTest[1926:4434715] THEMultipeerSession stopping peer
,2016-01-14 13:21:27.723 ThaliTest[1926:4434715] multipeer session: stop timer
2016-01-14 13:21:27.725 ThaliTest[1926:4434715] server session: disconnect
2016-01-14 13:21:27.725 ThaliTest[1926:4434715] server session: stateChange:2->0 1452774083497.1942
,2016-01-14 13:21:27.726 ThaliTest[1926:4434715] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-14 13:21:28.712 ThaliTest[1926:4434715] jxcore: startBroadcasting
,2016-01-14 13:21:28.714 ThaliTest[1926:4434715] server: starting 1452774088711.1926.MvUH+A==
2016-01-14 13:21:28.714 ThaliTest[1926:4434715] multipeer session: start timer: 0x1606fb70
2016-01-14 13:21:28.714 ThaliTest[1926:4434715] THEMultipeerSession in,itialized peer 1452774088711.1926
2016-01-14 13:21:28.714 ThaliTest[1926:4434715] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-14 13:21:29.954 ThaliTest[1926:4434544] client: found peer: 1452774088687.1942.fBt/ww==
,2016-01-14 13:21:29.955 ThaliTest[1926:4434715] jxcore: connect 1452774088687.1942.fBt/ww==
2016-01-14 13:21:29.956 ThaliTest[1926:4434715] client session: connect
2016-01-14 13:21:29.956 ThaliTest[1926:4434715] client session: stateChange:0->1 1452774088687.1942.fBt/ww==
,2016-01-14 13:21:30.074 ThaliTest[1926:4434544] multipeer session: reset timer
2016-01-14 13:21:30.075 ThaliTest[1926:4434544] multipeer session: stop timer
2016-01-14 13:21:30.075 ThaliTest[1926:4434544] multipeer session: start timer: 0x1606fb70
2016-01-14 13:21:30.075 ThaliTest[1926:4434544] server session: connect
2016-01-14 13:21:30.075 ThaliTest[1926:4434544] server session: stateChange:0->1 1452774088687.1942
,2016-01-14 13:21:30.078 ThaliTest[1926:4434544] server: accepting invitation 1452774088687.1942
,2016-01-14 13:21:32.436 ThaliTest[1926:4435579] client session: connected
2016-01-14 13:21:32.437 ThaliTest[1926:4435579] client session: stateChange:1->2 1452774088687.1942.fBt/ww==
,2016-01-14 13:21:32.504 ThaliTest[1926:4435659] client session: fireConnectCallback: 1452774088687.1942.fBt/ww==
2016-01-14 13:21:32.504 ThaliTest[1926:4435659] jxcore: connect: success
,ok 84 Should be able to connect without error
,ok 85 Port should be within range
,2016-01-14 13:21:32.506 ThaliTest[1926:4434715] jxcore: disconnect
2016-01-14 13:21:32.507 ThaliTest[1926:4434715] client session: disconnectFromPeer: 1452774088687.1942.fBt/ww==
2016-01-14 13:21:32.507 ThaliTest[1926:4434715] client session: disconnect,
2016-01-14 13:21:32.507 ThaliTest[1926:4434715] client session: stateChange:2->0 1452774088687.1942.fBt/ww==
,2016-01-14 13:21:32.511 ThaliTest[1926:4434715] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error
2016-01-14 13:21:32.516 ThaliTest[1926:4434715] jxcore: disconnect
2016-01-14 13:21:32.516 ThaliTest[1926:4434715] jxcore: disconnect: fail
ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,2016-01-14 13:21:32.525 ThaliTest[1926:4435584] server session: connected
2016-01-14 13:21:32.525 ThaliTest[1926:4435584] server session: stateChange:1->2 1452774088687.1942
,# setup
,2016-01-14 13:21:32.630 ThaliTest[1926:4435579] server session: not connected 1452774088687.1942
,2016-01-14 13:21:32.631 ThaliTest[1926:4434544] server relay: socket disconnected
2016-01-14 13:21:32.632 ThaliTest[1926:4434544] server relay: 0x16729900 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,calling stopBroadcasting
,2016-01-14 13:21:33.949 ThaliTest[1926:4434715] jxcore: stopBroadcasting
2016-01-14 13:21:33.949 ThaliTest[1926:4434715] THEMultipeerSession stopping peer
2016-01-14 13:21:33.949 ThaliTest[1926:4434715] multipeer session: stop timer
2016-01-14 13:21:33.,950 ThaliTest[1926:4434715] server session: disconnect
2016-01-14 13:21:33.950 ThaliTest[1926:4434715] server session: stateChange:2->0 1452774088687.1942
,2016-01-14 13:21:33.950 ThaliTest[1926:4434715] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can connect and send data
,# teardown
,2016-01-14 13:21:38.130 ThaliTest[1926:4434715] jxcore: startBroadcasting
,2016-01-14 13:21:38.133 ThaliTest[1926:4434715] server: starting 1452774098130.1926.8Qn3rg==
2016-01-14 13:21:38.134 ThaliTest[1926:4434715] multipeer session: start timer: 0x16053fd0
2016-01-14 13:21:38.134 ThaliTest[1926:4434715] THEMultipeerSession in,itialized peer 1452774098130.1926
2016-01-14 13:21:38.134 ThaliTest[1926:4434715] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
echo server started
,2016-01-14 13:21:38.984 ThaliTest[1926:4434544] client: found peer: 1452774098065.1942.O2+QVg==
2016-01-14 13:21:38.984 ThaliTest[1926:4434715] jxcore: connect 1452774098065.1942.O2+QVg==
2016-01-14 13:21:38.985 ThaliTest[1926:4434715] client session: co,nnect
2016-01-14 13:21:38.985 ThaliTest[1926:4434715] client session: stateChange:0->1 1452774098065.1942.O2+QVg==
,2016-01-14 13:21:39.897 ThaliTest[1926:4434544] multipeer session: reset timer
2016-01-14 13:21:39.897 ThaliTest[1926:4434544] multipeer session: stop timer
2016-01-14 13:21:39.898 ThaliTest[1926:4434544] multipeer session: start timer: 0x16053fd0
2016-,01-14 13:21:39.898 ThaliTest[1926:4434544] server session: connect
2016-01-14 13:21:39.898 ThaliTest[1926:4434544] server session: stateChange:0->1 1452774098065.1942
2016-01-14 13:21:39.901 ThaliTest[1926:4434544] server: accepting invitation 1452774098065.1942
,2016-01-14 13:21:42.660 ThaliTest[1926:4435584] client session: connected
2016-01-14 13:21:42.660 ThaliTest[1926:4435584] client session: stateChange:1->2 1452774098065.1942.O2+QVg==
,2016-01-14 13:21:42.662 ThaliTest[1926:4435583] server session: connected
,2016-01-14 13:21:42.662 ThaliTest[1926:4435583] server session: stateChange:1->2 1452774098065.1942
,2016-01-14 13:21:42.664 ThaliTest[1926:4435584] client session: fireConnectCallback: 1452774098065.1942.O2+QVg==
2016-01-14 13:21:42.664 ThaliTest[1926:4435584] jxcore: connect: success
ok 89 Should be able to connect without error
,ok 90 Port should be within range
,2016-01-14 13:21:42.667 ThaliTest[1926:4434544] server relay: connected (to port: 5001)
2016-01-14 13:21:42.668 ThaliTest[1926:4434544] client: relay established
2016-01-14 13:21:42.669 ThaliTest[1926:4434544] client: new accepted socket: 0x160cd370
,data in 17520
,data in 29565
,data in 52560
,data in 71175
,data in 74460
,data in 82125
,data in 85410
,data in 131072
,ok 91 the test messages should be equal
,2016-01-14 13:21:43.601 ThaliTest[1926:4434715] jxcore: disconnect
2016-01-14 13:21:43.601 ThaliTest[1926:4434715] client session: disconnectFromPeer: 1452774098065.1942.O2+QVg==
2016-01-14 13:21:43.601 ThaliTest[1926:4434715] client session: disconnect
2016-01-14 13:21:43.601 ThaliTest[1926:4434715] client session: stateChange:2->0 1452774098065.1942.O2+QVg==
,2016-01-14 13:21:43.607 ThaliTest[1926:4434715] jxcore: disconnect: success
ok 92 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
# setup
,2016-01-14 13:21:43.632 ThaliTest[1926:4435584] server session: not connected 1452774098065.1942
,calling stopBroadcasting
,2016-01-14 13:21:43.908 ThaliTest[1926:4434715] jxcore: stopBroadcasting
2016-01-14 13:21:43.909 ThaliTest[1926:4434715] THEMultipeerSession stopping peer
2016-01-14 13:21:43.909 ThaliTest[1926:4434715] multipeer session: stop timer
2016-01-14 13:21:43.909 ThaliTest[1926:4434715] server session: disconnect
2016-01-14 13:21:43.909 ThaliTest[1926:4434715] server session: stateChange:2->0 1452774098065.1942
,2016-01-14 13:21:43.915 ThaliTest[1926:4434715] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,2016-01-14 13:22:02.894 ThaliTest[1926:4434715] jxcore: startBroadcasting
,2016-01-14 13:22:02.905 ThaliTest[1926:4434715] server: starting 1452774122894.1926.4Z86SQ==
2016-01-14 13:22:02.905 ThaliTest[1926:4434715] multipeer session: start timer: 0x16716b90
2016-01-14 13:22:02.905 ThaliTest[1926:4434715] THEMultipeerSession in,itialized peer 1452774122894.1926
2016-01-14 13:22:02.905 ThaliTest[1926:4434715] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error
2016-01-14 13:22:02.908 ThaliTest[1926:4434715] Error!: listen EADDRINUSE
,Stack:[{"_fileName":"net.js","_functionName":"errnoException","_lineNumber":"835","_columnNumber":"11","_msg":"    at errnoException@net.js:835:11"},{"_fileName":"net.js","_functionName":"Server.prototype._listen2","_lineNumber":"974","_columnNumber":"14",,"_msg":"    at Server.prototype._listen2@net.js:974:14"},{"_fileName":"net.js","_functionName":"listen","_lineNumber":"995","_columnNumber":"5","_msg":"    at listen@net.js:995:5"},{"_fileName":"net.js","_functionName":"Server.prototype.listen","_lineNumbe,r":"1068","_columnNumber":"5","_msg":"    at Server.prototype.listen@net.js:1068:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionN,ame":"","_lineNumber":"241","_columnNumber":"3","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:241:3"},{"_fileName":"/private/var/mobile/Conta,iners/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"declareTest/</<","_lineNumber":"78","_columnNumber":"7","_msg":"    at declareTest/</<@/private/var/mobile/Containers/Bundle/Applicat,ion/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/lib/thali-tape.js:78:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modu,les/component-emitter/index.js","_functionName":"on","_lineNumber":"63","_columnNumber":"5","_msg":"    at on@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node,_modules/component-emitter/index.js:63:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":,"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_module,s/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lin,eNumber":"263","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5"},{"_fileName":"/pr,ivate/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"221","_columnNumber":"7","_msg":"    at Soc,ket.prototype.onpacket@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/81FAE,E87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Cont,ainers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D2,17C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bu,ndle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC,7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"333","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/81FA,EE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket,.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app,/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/,socket.io-parser/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D2,17C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/,www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.js","_functionName":"Decoder.prototype.add","_lineNumber":"247","_columnNumber":"7","_msg":"    at Decoder.prototype.add@/private/var/mobile/Containers/Bundle/Application/81FAEE87,-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.js:247:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore,/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondata","_lineNumber":"323","_columnNumber":"3","_msg":"    at Manager.prototype.ondata@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7,/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:323:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/componen,t-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.,io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/co,mponent-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore,/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.i,o-client/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onPacket","_lineNumber":"441","_columnNumber":"9","_msg":"    at Socket.prototype.onPacket@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9,D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:441:9"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/,socket.io-client/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.setTransport/<","_lineNumber":"258","_columnNumber":"5","_msg":"    at Socket.prototype.setTransport/<@/private/var/mobile/Containers/Bundle/Application/81FAEE8,7-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:258:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/,jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Container,s/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/8,1FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js","_functionName":"Transport.prototype.onPacket","_lineNumber":"143","_columnNumber":"3","_msg":"    at Transport.proto,type.onPacket@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js:143:3"},{"_fileName":"/private/var/mobile/Containers/,Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js","_functionName":"Transport.prototype.onData","_lineNumber":"135","_columnNumber":"3","_msg":"    ,at Transport.prototype.onData@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js:135:3"},{"_fileName":"/private/var/mo,bile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transports/websocket.js","_functionName":"WS.prototype.addEventListeners/this.ws.onmessage",,"_lineNumber":"127","_columnNumber":"5","_msg":"    at WS.prototype.addEventListeners/this.ws.onmessage@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modul,es/engine.io-client/lib/transports/websocket.js:127:5"}]
Uncaught Exception: Error: listen EADDRINUSE
,[ { _fileName: 'net.js',
    _functionName: 'errnoException',
    _lineNumber: '835',
    _columnNumber: '11',
    _msg: '    at errnoException@net.js:835:11' },
  { _fileName: 'net.js',
    _functionName: 'Server.prototype._listen2',
    _lineNumbe,r: '974',
    _columnNumber: '14',
    _msg: '    at Server.prototype._listen2@net.js:974:14' },
  { _fileName: 'net.js',
    _functionName: 'listen',
    _lineNumber: '995',
    _columnNumber: '5',
    _msg: '    at listen@net.js:995:5' },
  { _fi,leName: 'net.js',
    _functionName: 'Server.prototype.listen',
    _lineNumber: '1068',
    _columnNumber: '5',
    _msg: '    at Server.prototype.listen@net.js:1068:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C,3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: '',
    _lineNumber: '241',
    _columnNumber: '3',
    _msg: '    at @/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9,D217C8DC7/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:241:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/lib/thali-tape.js',
    _functionName: 'declareT,est/</<',
    _lineNumber: '78',
    _columnNumber: '7',
    _msg: '    at declareTest/</<@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/lib/thali-tape.js:78:7' },
  { _fileName: '/priva,te/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'on',
    _lineNumber: '63',
    _columnNumber: '5',
  ,  _msg: '    at on@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:63:5' },
  { _fileName: '/private/var/mobile/Container,s/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '131',
    _columnNumber: '7',
    ,_msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7' },
  { _fileName: '/private/v,ar/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.onevent',
    _lineNumber: '263',
    _columnNumber: '5',
    _msg:, '    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/A,pplication/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.onpacket',
    _lineNumber: '221',
    _columnNumber: '7',
    _msg: '    at Socket.prototype.on,packet@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-46,1C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21',
    _columnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mo,bile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-4,61C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '131',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit,@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Applicat,ion/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js',
    _functionName: 'Manager.prototype.ondecoded',
    _lineNumber: '333',
    _columnNumber: '3',
    _msg: '    at Manager.prototype.ondec,oded@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461,C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21',
    _columnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mob,ile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-46,1C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '134',
    _columnNumber: '7',
    _msg: ',    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:7' },
  {, _fileName: '/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.js',
    _functionName: 'Decoder.prototype.add',
    _lineNumbe,r: '247',
    _columnNumber: '7',
    _msg: '    at Decoder.prototype.add@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.js,:247:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js',
    _functionName: 'Manager.prototype.ondata',
    _lineNumber: '32,3',
    _columnNumber: '3',
    _msg: '    at Manager.prototype.ondata@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:323:3' },
  { _fileName: ,'/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21',
    _colu,mnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
  { _fileName:, '/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.e,mit',
    _lineNumber: '134',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/eng,ine.io-client/node_modules/component-emitter/index.js:134:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib,/socket.js',
    _functionName: 'Socket.prototype.onPacket',
    _lineNumber: '441',
    _columnNumber: '9',
    _msg: '    at Socket.prototype.onPacket@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.ap,p/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:441:9' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/,node_modules/engine.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.setTransport/<',
    _lineNumber: '258',
    _columnNumber: '5',
    _msg: '    at Socket.prototype.setTransport/<@/private/var/mobile/Containers/Bundle/Application/81FA,EE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:258:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.,app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '134',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/,private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7' },
  { _fileName: '/private/var/mobil,e/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js',
    _functionName: 'Transport.prototype.onPacket',
    _lineNumber: '143',
    _,columnNumber: '3',
    _msg: '    at Transport.prototype.onPacket@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js:,143:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js',
    _functionName: 'Transport.prototy,pe.onData',
    _lineNumber: '135',
    _columnNumber: '3',
    _msg: '    at Transport.prototype.onData@/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_m,odules/engine.io-client/lib/transport.js:135:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/81FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transports/w,ebsocket.js',
    _functionName: 'WS.prototype.addEventListeners/this.ws.onmessage',
    _lineNumber: '127',
    _columnNumber: '5',
    _msg: '    at WS.prototype.addEventListeners/this.ws.onmessage@/private/var/mobile/Containers/Bundle/Application/81,FAEE87-F8C3-461C-A925-5D9D217C8DC7/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transports/websocket.js:127:5' },
  toString: [Function] ]
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
