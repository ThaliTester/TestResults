#### Test 5753124305d96c2_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5753124305d96c2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/F8BC79B0-95BF-41E6-BF5E-7BAD9E2C396D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F8BC79B0-95BF-41E6-BF5E-7BAD9E2C396D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5753124305d96c2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5753124305d96c2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/14B9B6A7-5899-49E2-B1ED-BF8D2EE8AACB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64609"
,(lldb)     command script import "/tmp/F8BC79B0-95BF-41E6-BF5E-7BAD9E2C396D/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-02 15:13:58.806 ThaliTest[1032:1887945] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3C33AF42-9A14-4E1B-97F2-D837E84885C6/Library/Cookies/Cookies.binarycookies
,2016-02-02 15:13:59.222 ThaliTest[1032:1887945] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-02 15:13:59.224 ThaliTest[1032:1887945] Multi-tasking -> Device: YES, App: YES
,2016-02-02 15:13:59.233 ThaliTest[1032:1887945] Unlimited access to network resources
,2016-02-02 15:13:59.248 ThaliTest[1032:1887945] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-02 15:14:09.123 ThaliTest[1032:1887945] Resetting plugins due to page load.
,2016-02-02 15:14:12.735 ThaliTest[1032:1887945] Finished load of: file:///var/mobile/Containers/Bundle/Application/14B9B6A7-5899-49E2-B1ED-BF8D2EE8AACB/ThaliTest.app/www/index.html
,2016-02-02 15:14:12.927 ThaliTest[1032:1887945] JXcore Cordova plugin initializing
,2016-02-02 15:14:13.043 ThaliTest[1032:1888217] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14B9B6A7-5899-49E2-B1ED-BF8D2EE8AACB/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14B9B6A7-5899-49E2-B1ED-BF8D2EE8AACB/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14B9B6A7-5899-49E2-B1ED-BF8D2EE8AACB/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14B9B6A7-5899-49E2-B1ED-BF8D2EE8AACB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14B9B6A7-5899-49E2-B1ED-BF8D2EE8AACB/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,appEnteringBackground wasn't registered

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

,# Can call start/stopListeningForAdvertisements

,# teardown

,2016-02-02 15:18:58.836 ThaliTest[1032:1888217] jxcore: startListeningForAdvertisements
,2016-02-02 15:18:58.839 ThaliTest[1032:1888217] multipeer manager: start client restart timer: 0x16d51920
,2016-02-02 15:18:58.840 ThaliTest[1032:1888217] jxcore: startListeningForAdvertisements: success
,ok 13 Can call startListeningForAdvertisements without error

2016-02-02 15:18:58.844 ThaliTest[1032:1888217] jxcore: stopListeningForAdvertisements
2016-02-02 15:18:58.844 ThaliTest[1032:1888217] multipeer manager: stop client timer
2016-02-02 15:18:5,8.845 ThaliTest[1032:1888217] jxcore: stopListeningForAdvertisements: success
ok 14 Can call stopListeningForAdvertisements without error

,# setup

,2016-02-02 15:18:58.871 ThaliTest[1032:1888217] jxcore: stopListeningForAdvertisements
2016-02-02 15:18:58.871 ThaliTest[1032:1888217] jxcore: stopListeningForAdvertisements: success
ok 15 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 15:18:58.873 ThaliTest[1032:1888217] jxcore: stopAdvertisingAndListening
2016-02-02 15:18:58.874 ThaliTest[1032:1888217] THEMultipeerManager stopping peer
2016-02-02 15:18:58.874 ThaliTest[1032:1888217] jxcore: stopAdvertisingAndListening: success
ok 16 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startListeningForAdvertisements twice is an error

,# teardown

,2016-02-02 15:18:59.140 ThaliTest[1032:1888217] jxcore: startListeningForAdvertisements
2016-02-02 15:18:59.141 ThaliTest[1032:1888217] multipeer manager: start client restart timer: 0x16d51920
2016-02-02 15:18:59.142 ThaliTest[1032:1888217] jxcore: star,tListeningForAdvertisements: success
ok 17 Can call startListeningForAdvertisements without error

,2016-02-02 15:18:59.143 ThaliTest[1032:1888217] jxcore: startListeningForAdvertisements
2016-02-02 15:18:59.145 ThaliTest[1032:1888217] jxcore: startListeningForAdvertisements: failure
ok 18 Calling start twice is an error

ok 19 Error must be "Call Stop!"

,# setup

,2016-02-02 15:18:59.195 ThaliTest[1032:1888217] jxcore: stopListeningForAdvertisements
2016-02-02 15:18:59.196 ThaliTest[1032:1888217] multipeer manager: stop client timer
2016-02-02 15:18:59.196 ThaliTest[1032:1888217] jxcore: stopListeningForAdvertisem,ents: success
ok 20 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 15:18:59.198 ThaliTest[1032:1888217] jxcore: stopAdvertisingAndListening
,2016-02-02 15:18:59.198 ThaliTest[1032:1888217] THEMultipeerManager stopping peer
,2016-02-02 15:18:59.200 ThaliTest[1032:1888217] jxcore: stopAdvertisingAndListening: success
ok 21 Should be able to call stopAdvertisingAndListening in teardown

,# Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-02-02 15:18:59.653 ThaliTest[1032:1888217] jxcore: startUpdateAdvertisingAndListening
2016-02-02 15:18:59.654 ThaliTest[1032:1888217] server: starting 7F1BD6F8-FEEC-4B96-88ED-620CB1F8FC36:1
2016-02-02 15:18:59.655 ThaliTest[1032:1888217] multipeer m,anager: start client restart timer: 0x16d51920
2016-02-02 15:18:59.655 ThaliTest[1032:1888217] THEMultipeerManager initialized peer 7F1BD6F8-FEEC-4B96-88ED-620CB1F8FC36:1
2016-02-02 15:18:59.655 ThaliTest[1032:1888217] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 22 Can call startUpdateAdvertisingAndListening without error

,2016-02-02 15:18:59.659 ThaliTest[1032:1888217] jxcore: stopAdvertisingAndListening
2016-02-02 15:18:59.659 ThaliTest[1032:1888217] THEMultipeerManager stopping peer
2016-02-02 15:18:59.661 ThaliTest[1032:1888217] multipeer manager: stop client timer
20,16-02-02 15:18:59.661 ThaliTest[1032:1888217] jxcore: stopAdvertisingAndListening: success
ok 23 Can call stopAdvertisingAndListening without error

,# setup

,2016-02-02 15:18:59.739 ThaliTest[1032:1888217] jxcore: stopListeningForAdvertisements
2016-02-02 15:18:59.739 ThaliTest[1032:1888217] jxcore: stopListeningForAdvertisements: success
ok 24 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 15:18:59.741 ThaliTest[1032:1888217] jxcore: stopAdvertisingAndListening
2016-02-02 15:18:59.742 ThaliTest[1032:1888217] THEMultipeerManager stopping peer
2016-02-02 15:18:59.742 ThaliTest[1032:1888217] jxcore: stopAdvertisingAndListening: success
ok 25 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startUpdateAdvertisingAndListening twice is NOT and error

,# teardown

,2016-02-02 15:18:59.847 ThaliTest[1032:1888217] jxcore: startUpdateAdvertisingAndListening
2016-02-02 15:18:59.847 ThaliTest[1032:1888217] server: starting 7F1BD6F8-FEEC-4B96-88ED-620CB1F8FC36:2
2016-02-02 15:18:59.848 ThaliTest[1032:1888217] multipeer m,anager: start client restart timer: 0x16d51920
2016-02-02 15:18:59.848 ThaliTest[1032:1888217] THEMultipeerManager initialized peer 7F1BD6F8-FEEC-4B96-88ED-620CB1F8FC36:2
2016-02-02 15:18:59.849 ThaliTest[1032:1888217] jxcore: startUpdateAdvertisingAndListening: success
ok 26 Can call startUpdateAdvertisingAndListening without error

,2016-02-02 15:18:59.850 ThaliTest[1032:1888217] jxcore: startUpdateAdvertisingAndListening
2016-02-02 15:18:59.851 ThaliTest[1032:1888217] THEMultipeerManager stopping peer
,2016-02-02 15:18:59.852 ThaliTest[1032:1888217] multipeer manager: stop client timer
,2016-02-02 15:18:59.853 ThaliTest[1032:1888217] server: starting 7F1BD6F8-FEEC-4B96-88ED-620CB1F8FC36:3
,2016-02-02 15:18:59.854 ThaliTest[1032:1888217] multipeer manager: start client restart timer: 0x16d51920
2016-02-02 15:18:59.855 ThaliTest[1032:1888217] THEMultipeerManager initialized peer 7F1BD6F8-FEEC-4B96-88ED-620CB1F8FC36:3
2016-02-02 15:18:59.855 ,ThaliTest[1032:1888217] jxcore: startUpdateAdvertisingAndListening: success
ok 27 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-02-02 15:19:00.164 ThaliTest[1032:1888217] jxcore: stopListeningForAdvertisements
2016-02-02 15:19:00.164 ThaliTest[1032:1888217] jxcore: stopListeningForAdvertisements: success
ok 28 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 15:19:00.166 ThaliTest[1032:1888217] jxcore: stopAdvertisingAndListening
2016-02-02 15:19:00.166 ThaliTest[1032:1888217] THEMultipeerManager stopping peer
2016-02-02 15:19:00.167 ThaliTest[1032:1888217] multipeer manager: stop client timer
2016-02-02 15:19:00.167 ThaliTest[1032:1888217] jxcore: stopAdvertisingAndListening: success
ok 29 Should be able to call stopAdvertisingAndListening in teardown

,# peerAvailabilityChange is called

,# teardown

,2016-02-02 15:19:00.250 ThaliTest[1032:1888217] jxcore: startUpdateAdvertisingAndListening
2016-02-02 15:19:00.250 ThaliTest[1032:1888217] server: starting 7F1BD6F8-FEEC-4B96-88ED-620CB1F8FC36:4
2016-02-02 15:19:00.251 ThaliTest[1032:1888217] multipeer m,anager: start client restart timer: 0x16d51920
2016-02-02 15:19:00.251 ThaliTest[1032:1888217] THEMultipeerManager initialized peer 7F1BD6F8-FEEC-4B96-88ED-620CB1F8FC36:4
2016-02-02 15:19:00.252 ThaliTest[1032:1888217] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 30 Can call startUpdateAdvertisingAndListeningwithout error

,2016-02-02 15:19:00.253 ThaliTest[1032:1888217] jxcore: startListeningForAdvertisements
2016-02-02 15:19:00.254 ThaliTest[1032:1888217] multipeer manager: stop client timer
,2016-02-02 15:19:00.255 ThaliTest[1032:1888217] multipeer manager: start client restart timer: 0x16d51920
2016-02-02 15:19:00.256 ThaliTest[1032:1888217] jxcore: startListeningForAdvertisements: success
ok 31 Can call startListeningForAdvertisements without error

,2016-02-02 15:19:01.505 ThaliTest[1032:1887945] client: found new peer: AB1DBB37-C9D2-4DDF-B12C-8DB0EF52EC85:4
ok 32 peers must be an array

,ok 33 peers must not be zero-length

ok 34 peer must have peerIdentifier

,ok 35 peerIdentifier must be a string

,ok 36 peer must have peerAvailable

,ok 37 peer must have pleaseConnect

,# setup

,2016-02-02 15:19:01.747 ThaliTest[1032:1888217] jxcore: stopListeningForAdvertisements
2016-02-02 15:19:01.747 ThaliTest[1032:1888217] jxcore: stopListeningForAdvertisements: success
ok 38 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 15:19:01.749 ThaliTest[1032:1888217] jxcore: stopAdvertisingAndListening
2016-02-02 15:19:01.749 ThaliTest[1032:1888217] THEMultipeerManager stopping peer
2016-02-02 15:19:01.750 ThaliTest[1032:1888217] multipeer manager: stop client timer
2016-02-02 15:19:01.751 ThaliTest[1032:1888217] jxcore: stopAdvertisingAndListening: success
ok 39 Should be able to call stopAdvertisingAndListening in teardown

,# Can connect to a remote peer

,# teardown

,2016-02-02 15:19:01.806 ThaliTest[1032:1888217] jxcore: startUpdateAdvertisingAndListening
,2016-02-02 15:19:01.808 ThaliTest[1032:1888217] server: starting 7F1BD6F8-FEEC-4B96-88ED-620CB1F8FC36:5
,2016-02-02 15:19:01.810 ThaliTest[1032:1888217] multipeer manager: start client restart timer: 0x16d51920
,2016-02-02 15:19:01.817 ThaliTest[1032:1888217] THEMultipeerManager initialized peer 7F1BD6F8-FEEC-4B96-88ED-620CB1F8FC36:5
,2016-02-02 15:19:01.820 ThaliTest[1032:1888217] jxcore: startUpdateAdvertisingAndListening: success
,ok 40 Can call startUpdateAdvertisingAndListening without error

,2016-02-02 15:19:01.824 ThaliTest[1032:1888217] jxcore: startListeningForAdvertisements
,2016-02-02 15:19:01.825 ThaliTest[1032:1888217] multipeer manager: stop client timer
,2016-02-02 15:19:01.831 ThaliTest[1032:1888217] multipeer manager: start client restart timer: 0x16d51920
2016-02-02 15:19:01.835 ThaliTest[1032:1888217] jxcore: startListeningForAdvertisements: success
,ok 41 Can call startListeningForAdvertisements without error

,2016-02-02 15:19:01.846 ThaliTest[1032:1887945] client: found new peer: AB1DBB37-C9D2-4DDF-B12C-8DB0EF52EC85:4
,2016-02-02 15:19:01.852 ThaliTest[1032:1888217] jxcore: connect AB1DBB37-C9D2-4DDF-B12C-8DB0EF52EC85:4
,2016-02-02 15:19:01.853 ThaliTest[1032:1888217] client: server will connect
,2016-02-02 15:19:01.855 ThaliTest[1032:1888217] client session: reverseConnect
,2016-02-02 15:19:01.856 ThaliTest[1032:1888217] client session: stateChange:0->1 AB1DBB37-C9D2-4DDF-B12C-8DB0EF52EC85:4
,2016-02-02 15:19:02.722 ThaliTest[1032:1887945] multipeer session: reset timer
2016-02-02 15:19:02.722 ThaliTest[1032:1887945] server: rejecting invitation from AB1DBB37-C9D2-4DDF-B12C-8DB0EF52EC85 due to previous generation (7F1BD6F8-FEEC-4B96-88ED-620CB1F8FC36:5 != 7F1BD6F8-FEEC-4B96-88ED-620CB1F8FC36:4)
,2016-02-02 15:19:03.092 ThaliTest[1032:1888901] client session: not connected AB1DBB37-C9D2-4DDF-B12C-8DB0EF52EC85:4
2016-02-02 15:19:03.093 ThaliTest[1032:1888901] client session: onLinkFailure: AB1DBB37-C9D2-4DDF-B12C-8DB0EF52EC85
2016-02-02 15:19:03.0,93 ThaliTest[1032:1888901] client session: disconnect
2016-02-02 15:19:03.093 ThaliTest[1032:1888901] client session: stateChange:1->0 AB1DBB37-C9D2-4DDF-B12C-8DB0EF52EC85:4
,2016-02-02 15:19:03.096 ThaliTest[1032:1888901] client session: no connect callabck (server initiated)
,appEnteredForeground wasn't registered


```
