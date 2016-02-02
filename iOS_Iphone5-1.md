#### Test 575312435db8e90_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/575312435db8e90/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/37C5DDFD-7598-414D-A8CA-AF5C26D020BE/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/37C5DDFD-7598-414D-A8CA-AF5C26D020BE/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/575312435db8e90/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/575312435db8e90/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/01BC5A93-DEA1-4366-A8BA-4A11886744F9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63925"
,(lldb)     command script import "/tmp/37C5DDFD-7598-414D-A8CA-AF5C26D020BE/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-02 12:22:31.105 ThaliTest[2255:7436290] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/158D2F72-0120-4888-AD90-6E4C720B2F78/Library/Cookies/Cookies.binarycookies
,2016-02-02 12:22:31.222 ThaliTest[2255:7436290] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-02 12:22:31.224 ThaliTest[2255:7436290] Multi-tasking -> Device: YES, App: YES
,2016-02-02 12:22:31.229 ThaliTest[2255:7436290] Unlimited access to network resources
,2016-02-02 12:22:31.241 ThaliTest[2255:7436290] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-02 12:22:38.012 ThaliTest[2255:7436290] Resetting plugins due to page load.
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,2016-02-02 12:22:40.452 ThaliTest[2255:7436290] Finished load of: file:///var/mobile/Containers/Bundle/Application/01BC5A93-DEA1-4366-A8BA-4A11886744F9/ThaliTest.app/www/index.html
,2016-02-02 12:22:40.696 ThaliTest[2255:7436290] JXcore Cordova plugin initializing
,2016-02-02 12:22:40.815 ThaliTest[2255:7436811] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/01BC5A93-DEA1-4366-A8BA-4A11886744F9/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/01BC5A93-DEA1-4366-A8BA-4A11886744F9/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/01BC5A93-DEA1-4366-A8BA-4A11886744F9/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/01BC5A93-DEA1-4366-A8BA-4A11886744F9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/01BC5A93-DEA1-4366-A8BA-4A11886744F9/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,
,Test app app.js loaded

,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,TAP version 13

,# setup

,# multiplex can send data

,# teardown

,ok 1 String should be length:200

,# setup

,# enqueue and run in order

,# teardown

,ok 2 firstPromise setTimeout

ok 3 firstPromise result

,ok 4 firstPromise testValue

,ok 5 secondPromise setTimeout

ok 6 secondPromise result

ok 7 secondPromise testValue

ok 8 thirdPromise in promise

ok 9 thirdPromise result

ok 10 thirdPromise testValue

# setup

,# basic

,# teardown

,ok 11 sane

# setup

,# another

,# teardown

,ok 12 sane

# setup

,# Can call start/stopListeningForAdvertisements

,# teardown

,2016-02-02 12:28:17.307 ThaliTest[2255:7436811] jxcore: startListeningForAdvertisements
,2016-02-02 12:28:17.310 ThaliTest[2255:7436811] multipeer manager: start client restart timer: 0x176ecec0
2016-02-02 12:28:17.311 ThaliTest[2255:7436811] jxcore: startListeningForAdvertisements: success
ok 13 Can call startListeningForAdvertisements with,out error

2016-02-02 12:28:17.312 ThaliTest[2255:7436811] jxcore: stopListeningForAdvertisements
2016-02-02 12:28:17.313 ThaliTest[2255:7436811] multipeer manager: stop client timer
2016-02-02 12:28:17.313 ThaliTest[2255:7436811] jxcore: stopListening,ForAdvertisements: success
ok 14 Can call stopListeningForAdvertisements without error

# setup

,2016-02-02 12:28:17.343 ThaliTest[2255:7436811] jxcore: stopListeningForAdvertisements
,2016-02-02 12:28:17.345 ThaliTest[2255:7436811] jxcore: stopListeningForAdvertisements: success
,ok 15 Should be able to call stopListeningForAdvertisments in teardown
,
,2016-02-02 12:28:17.348 ThaliTest[2255:7436811] jxcore: stopAdvertisingAndListening
,2016-02-02 12:28:17.350 ThaliTest[2255:7436811] THEMultipeerManager stopping peer
,2016-02-02 12:28:17.351 ThaliTest[2255:7436811] jxcore: stopAdvertisingAndListening: success
,ok 16 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startListeningForAdvertisements twice is an error

,# teardown

,2016-02-02 12:28:17.393 ThaliTest[2255:7436811] jxcore: startListeningForAdvertisements
,2016-02-02 12:28:17.394 ThaliTest[2255:7436811] multipeer manager: start client restart timer: 0x176ecec0
,2016-02-02 12:28:17.400 ThaliTest[2255:7436811] jxcore: startListeningForAdvertisements: success
,ok 17 Can call startListeningForAdvertisements without error

,2016-02-02 12:28:17.402 ThaliTest[2255:7436811] jxcore: startListeningForAdvertisements
,2016-02-02 12:28:17.403 ThaliTest[2255:7436811] jxcore: startListeningForAdvertisements: failure
,ok 18 Calling start twice is an error

,ok 19 Error must be "Call Stop!"

,# setup

,2016-02-02 12:28:17.591 ThaliTest[2255:7436811] jxcore: stopListeningForAdvertisements
2016-02-02 12:28:17.591 ThaliTest[2255:7436811] multipeer manager: stop client timer
2016-02-02 12:28:17.591 ThaliTest[2255:7436811] jxcore: stopListeningForAdvertisem,ents: success
ok 20 Should be able to call stopListeningForAdvertisments in teardown

2016-02-02 12:28:17.592 ThaliTest[2255:7436811] jxcore: stopAdvertisingAndListening
2016-02-02 12:28:17.592 ThaliTest[2255:7436811] THEMultipeerManager stopping peer,
2016-02-02 12:28:17.592 ThaliTest[2255:7436811] jxcore: stopAdvertisingAndListening: success
ok 21 Should be able to call stopAdvertisingAndListening in teardown

,# Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-02-02 12:28:17.638 ThaliTest[2255:7436811] jxcore: startUpdateAdvertisingAndListening
2016-02-02 12:28:17.638 ThaliTest[2255:7436811] server: starting 23463C64-D12A-4472-B5F9-52B63D6A8BDA:1
2016-02-02 12:28:17.639 ThaliTest[2255:7436811] multipeer m,anager: start client restart timer: 0x176ecec0
2016-02-02 12:28:17.639 ThaliTest[2255:7436811] THEMultipeerManager initialized peer 23463C64-D12A-4472-B5F9-52B63D6A8BDA:1
2016-02-02 12:28:17.639 ThaliTest[2255:7436811] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 22 Can call startUpdateAdvertisingAndListening without error

2016-02-02 12:28:17.640 ThaliTest[2255:7436811] jxcore: stopAdvertisingAndListening
2016-02-02 12:28:17.641 ThaliTest[2255:7436811] THEMultipeerManager stopping peer
,2016-02-02 12:28:17.641 ThaliTest[2255:7436811] multipeer manager: stop client timer
2016-02-02 12:28:17.649 ThaliTest[2255:7436811] jxcore: stopAdvertisingAndListening: success
ok 23 Can call stopAdvertisingAndListening without error

# setup

,2016-02-02 12:28:17.685 ThaliTest[2255:7436811] jxcore: stopListeningForAdvertisements
2016-02-02 12:28:17.686 ThaliTest[2255:7436811] jxcore: stopListeningForAdvertisements: success
ok 24 Should be able to call stopListeningForAdvertisments in teardown,

2016-02-02 12:28:17.687 ThaliTest[2255:7436811] jxcore: stopAdvertisingAndListening
2016-02-02 12:28:17.687 ThaliTest[2255:7436811] THEMultipeerManager stopping peer
2016-02-02 12:28:17.687 ThaliTest[2255:7436811] jxcore: stopAdvertisingAndListening: ,success
ok 25 Should be able to call stopAdvertisingAndListening in teardown

# Calling startUpdateAdvertisingAndListening twice is NOT and error

,# teardown

,2016-02-02 12:28:23.753 ThaliTest[2255:7436811] jxcore: startUpdateAdvertisingAndListening
2016-02-02 12:28:23.753 ThaliTest[2255:7436811] server: starting 23463C64-D12A-4472-B5F9-52B63D6A8BDA:2
2016-02-02 12:28:23.754 ThaliTest[2255:7436811] multipeer m,anager: start client restart timer: 0x176ecec0
2016-02-02 12:28:23.754 ThaliTest[2255:7436811] THEMultipeerManager initialized peer 23463C64-D12A-4472-B5F9-52B63D6A8BDA:2
2016-02-02 12:28:23.754 ThaliTest[2255:7436811] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 26 Can call startUpdateAdvertisingAndListening without error

2016-02-02 12:28:23.755 ThaliTest[2255:7436811] jxcore: startUpdateAdvertisingAndListening
2016-02-02 12:28:23.755 ThaliTest[2255:7436811] THEMultipeerManager stopping peer
,2016-02-02 12:28:23.756 ThaliTest[2255:7436811] multipeer manager: stop client timer
2016-02-02 12:28:23.762 ThaliTest[2255:7436811] server: starting 23463C64-D12A-4472-B5F9-52B63D6A8BDA:3
2016-02-02 12:28:23.763 ThaliTest[2255:7436811] multipeer manager,: start client restart timer: 0x176ecec0
2016-02-02 12:28:23.763 ThaliTest[2255:7436811] THEMultipeerManager initialized peer 23463C64-D12A-4472-B5F9-52B63D6A8BDA:3
,2016-02-02 12:28:23.763 ThaliTest[2255:7436811] jxcore: startUpdateAdvertisingAndListening: success
,ok 27 Can call startUpdateAdvertisingAndListening twice without error

,# setup
,
,2016-02-02 12:28:31.487 ThaliTest[2255:7436811] jxcore: stopListeningForAdvertisements
2016-02-02 12:28:31.488 ThaliTest[2255:7436811] jxcore: stopListeningForAdvertisements: success
ok 28 Should be able to call stopListeningForAdvertisments in teardown,

2016-02-02 12:28:31.489 ThaliTest[2255:7436811] jxcore: stopAdvertisingAndListening
2016-02-02 12:28:31.489 ThaliTest[2255:7436811] THEMultipeerManager stopping peer
2016-02-02 12:28:31.489 ThaliTest[2255:7436811] multipeer manager: stop client timer,
2016-02-02 12:28:31.489 ThaliTest[2255:7436811] jxcore: stopAdvertisingAndListening: success
ok 29 Should be able to call stopAdvertisingAndListening in teardown

# peerAvailabilityChange is called

,# teardown

,2016-02-02 12:28:39.725 ThaliTest[2255:7436811] jxcore: startUpdateAdvertisingAndListening
2016-02-02 12:28:39.725 ThaliTest[2255:7436811] server: starting 23463C64-D12A-4472-B5F9-52B63D6A8BDA:4
2016-02-02 12:28:39.725 ThaliTest[2255:7436811] multipeer m,anager: start client restart timer: 0x176ecec0
2016-02-02 12:28:39.725 ThaliTest[2255:7436811] THEMultipeerManager initialized peer 23463C64-D12A-4472-B5F9-52B63D6A8BDA:4
2016-02-02 12:28:39.726 ThaliTest[2255:7436811] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 30 Can call startUpdateAdvertisingAndListeningwithout error

2016-02-02 12:28:39.727 ThaliTest[2255:7436811] jxcore: startListeningForAdvertisements
2016-02-02 12:28:39.727 ThaliTest[2255:7436811] multipeer manager: stop client time,r
2016-02-02 12:28:39.727 ThaliTest[2255:7436811] multipeer manager: start client restart timer: 0x176ecec0
2016-02-02 12:28:39.727 ThaliTest[2255:7436811] jxcore: startListeningForAdvertisements: success
ok 31 Can call startListeningForAdvertisements w,ithout error

,2016-02-02 12:28:39.751 ThaliTest[2255:7436290] client: found new peer: 486A7E46-8E93-4E50-8992-47F882FEA360:4
ok 32 peers must be an array

ok 33 peers must not be zero-length

ok 34 peer must have peerIdentifier

ok 35 peerIdentifier must be a str,ing

ok 36 peer must have peerAvailable

ok 37 peer must have pleaseConnect

,# setup

,2016-02-02 12:28:42.890 ThaliTest[2255:7436290] client: lost peer: 486A7E46-8E93-4E50-8992-47F882FEA360
2016-02-02 12:28:42.892 ThaliTest[2255:7436290] client session: onPeerLost: 486A7E46-8E93-4E50-8992-47F882FEA360
,2016-02-02 12:28:44.955 ThaliTest[2255:7436811] jxcore: stopListeningForAdvertisements
2016-02-02 12:28:44.955 ThaliTest[2255:7436811] jxcore: stopListeningForAdvertisements: success
ok 38 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 12:28:44.956 ThaliTest[2255:7436811] jxcore: stopAdvertisingAndListening
2016-02-02 12:28:44.957 ThaliTest[2255:7436811] THEMultipeerManager stopping peer
2016-02-02 12:28:44.957 ThaliTest[2255:7436811] multipeer manager: stop client timer
20,16-02-02 12:28:44.957 ThaliTest[2255:7436811] jxcore: stopAdvertisingAndListening: success
ok 39 Should be able to call stopAdvertisingAndListening in teardown

# Can connect to a remote peer

,# teardown

,2016-02-02 12:28:46.082 ThaliTest[2255:7436811] jxcore: startUpdateAdvertisingAndListening
2016-02-02 12:28:46.082 ThaliTest[2255:7436811] server: starting 23463C64-D12A-4472-B5F9-52B63D6A8BDA:5
2016-02-02 12:28:46.082 ThaliTest[2255:7436811] multipeer m,anager: start client restart timer: 0x176ecec0
2016-02-02 12:28:46.083 ThaliTest[2255:7436811] THEMultipeerManager initialized peer 23463C64-D12A-4472-B5F9-52B63D6A8BDA:5
2016-02-02 12:28:46.083 ThaliTest[2255:7436811] jxcore: startUpdateAdvertisingAndListening: success
ok 40 Can call startUpdateAdvertisingAndListening without error

,2016-02-02 12:28:46.084 ThaliTest[2255:7436811] jxcore: startListeningForAdvertisements
2016-02-02 12:28:46.084 ThaliTest[2255:7436811] multipeer manager: stop client timer
2016-02-02 12:28:46.085 ThaliTest[2255:7436811] multipeer manager: start client r,estart timer: 0x176ecec0
2016-02-02 12:28:46.085 ThaliTest[2255:7436811] jxcore: startListeningForAdvertisements: success
,ok 41 Can call startListeningForAdvertisements without error

,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,2016-02-02 12:28:49.121 ThaliTest[2255:7436290] client: found new peer: 486A7E46-8E93-4E50-8992-47F882FEA360:5
2016-02-02 12:28:49.122 ThaliTest[2255:7436811] jxcore: connect 486A7E46-8E93-4E50-8992-47F882FEA360:5
2016-02-02 12:28:49.122 ThaliTest[2255:7,436811] client: server will connect
2016-02-02 12:28:49.122 ThaliTest[2255:7436811] client session: reverseConnect
2016-02-02 12:28:49.123 ThaliTest[2255:7436811] client session: stateChange:0->1 486A7E46-8E93-4E50-8992-47F882FEA360:5
,2016-02-02 12:28:49.175 ThaliTest[2255:7436290] multipeer session: reset timer
2016-02-02 12:28:49.175 ThaliTest[2255:7436290] server: rejecting invitation from 486A7E46-8E93-4E50-8992-47F882FEA360 due to previous generation (23463C64-D12A-4472-B5F9-52B63D6A8BDA:5 != 23463C64-D12A-4472-B5F9-52B63D6A8BDA:4)
,2016-02-02 12:28:49.324 ThaliTest[2255:7437821] client session: not connected 486A7E46-8E93-4E50-8992-47F882FEA360:5
2016-02-02 12:28:49.324 ThaliTest[2255:7437821] client session: onLinkFailure: 486A7E46-8E93-4E50-8992-47F882FEA360
2016-02-02 12:28:49.3,24 ThaliTest[2255:7437821] client session: disconnect
2016-02-02 12:28:49.324 ThaliTest[2255:7437821] client session: stateChange:1->0 486A7E46-8E93-4E50-8992-47F882FEA360:5
2016-02-02 12:28:49.325 ThaliTest[2255:7437821] client session: no connect calla,bck (server initiated)
,2016-02-02 12:28:49.366 ThaliTest[2255:7436290] multipeer session: reset timer
,2016-02-02 12:28:49.366 ThaliTest[2255:7436290] server: disconnecting to refresh session (486A7E46-8E93-4E50-8992-47F882FEA360)
2016-02-02 12:28:49.366 ThaliTest[2255:7436290] server session: connect
,2016-02-02 12:28:49.367 ThaliTest[2255:7436290] server session: stateChange:0->1 486A7E46-8E93-4E50-8992-47F882FEA360:5
,2016-02-02 12:28:49.373 ThaliTest[2255:7436290] server: accepting invitation 486A7E46-8E93-4E50-8992-47F882FEA360
,2016-02-02 12:28:52.403 ThaliTest[2255:7437821] server session: connected
,2016-02-02 12:28:52.403 ThaliTest[2255:7437821] server session: stateChange:1->2 486A7E46-8E93-4E50-8992-47F882FEA360:5
,2016-02-02 12:28:52.410 ThaliTest[2255:7436290] server relay: socket disconnected
2016-02-02 12:28:52.410 ThaliTest[2255:7436290] server relay: 0x1d9d3730 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,2016-02-02 12:37:48.937 ThaliTest[2255:7440433] server session: not connected 486A7E46-8E93-4E50-8992-47F882FEA360:5

```
