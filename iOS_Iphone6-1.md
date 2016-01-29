#### Test 57531243c766d4e_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/57531243c766d4e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/DB0405EE-E87F-44D0-B994-2F4A0A834153/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/DB0405EE-E87F-44D0-B994-2F4A0A834153/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/57531243c766d4e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/57531243c766d4e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AC8FEACD-2538-4F91-8849-0DA2FF9768DA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63136"
,(lldb)     command script import "/tmp/DB0405EE-E87F-44D0-B994-2F4A0A834153/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-29 18:55:36.605 ThaliTest[763:1310182] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1793D4DC-6964-4FAE-B1BB-7565601D50A0/Library/Cookies/Cookies.binarycookies
,2016-01-29 18:55:37.022 ThaliTest[763:1310182] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-29 18:55:37.023 ThaliTest[763:1310182] Multi-tasking -> Device: YES, App: YES
,2016-01-29 18:55:37.033 ThaliTest[763:1310182] Unlimited access to network resources
,2016-01-29 18:55:37.043 ThaliTest[763:1310182] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-29 18:55:46.593 ThaliTest[763:1310182] Resetting plugins due to page load.
,2016-01-29 18:55:49.880 ThaliTest[763:1310182] Finished load of: file:///var/mobile/Containers/Bundle/Application/AC8FEACD-2538-4F91-8849-0DA2FF9768DA/ThaliTest.app/www/index.html
,2016-01-29 18:55:50.063 ThaliTest[763:1310182] JXcore Cordova plugin initializing
,2016-01-29 18:55:50.164 ThaliTest[763:1310544] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AC8FEACD-2538-4F91-8849-0DA2FF9768DA/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AC8FEACD-2538-4F91-8849-0DA2FF9768DA/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AC8FEACD-2538-4F91-8849-0DA2FF9768DA/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AC8FEACD-2538-4F91-8849-0DA2FF9768DA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AC8FEACD-2538-4F91-8849-0DA2FF9768DA/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,# Can call start/stopListeningForAdvertisements

,# teardown

,2016-01-29 19:00:23.920 ThaliTest[763:1310544] jxcore: startListeningForAdvertisements
,2016-01-29 19:00:23.922 ThaliTest[763:1310544] jxcore: startListeningForAdvertisements: success
,ok 13 Can call startListeningForAdvertisements without error

,2016-01-29 19:00:23.925 ThaliTest[763:1310544] jxcore: stopListeningForAdvertisements
,2016-01-29 19:00:23.926 ThaliTest[763:1310544] jxcore: stopListeningForAdvertisements: success
ok 14 Can call stopListeningForAdvertisements without error

,# setup

,2016-01-29 19:00:23.962 ThaliTest[763:1310544] jxcore: stopListeningForAdvertisements
2016-01-29 19:00:23.962 ThaliTest[763:1310544] jxcore: stopListeningForAdvertisements: success
ok 15 Should be able to call stopListeningForAdvertisments in teardown

,2016-01-29 19:00:23.965 ThaliTest[763:1310544] jxcore: stopAdvertisingAndListening
2016-01-29 19:00:23.965 ThaliTest[763:1310544] THEMultipeerManager stopping peer
2016-01-29 19:00:23.966 ThaliTest[763:1310544] jxcore: stopAdvertisingAndListening: success
ok 16 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startListeningForAdvertisements twice is an error

,# teardown

,2016-01-29 19:00:24.321 ThaliTest[763:1310544] jxcore: startListeningForAdvertisements
2016-01-29 19:00:24.322 ThaliTest[763:1310544] jxcore: startListeningForAdvertisements: success
ok 17 Can call startListeningForAdvertisements without error

,2016-01-29 19:00:24.324 ThaliTest[763:1310544] jxcore: startListeningForAdvertisements
2016-01-29 19:00:24.325 ThaliTest[763:1310544] jxcore: startListeningForAdvertisements: failure
ok 18 Calling start twice is an error

ok 19 Error must be "Call Stop!"

,# setup

,2016-01-29 19:00:24.425 ThaliTest[763:1310544] jxcore: stopListeningForAdvertisements
2016-01-29 19:00:24.426 ThaliTest[763:1310544] jxcore: stopListeningForAdvertisements: success
ok 20 Should be able to call stopListeningForAdvertisments in teardown

,2016-01-29 19:00:24.428 ThaliTest[763:1310544] jxcore: stopAdvertisingAndListening
2016-01-29 19:00:24.429 ThaliTest[763:1310544] THEMultipeerManager stopping peer
2016-01-29 19:00:24.429 ThaliTest[763:1310544] jxcore: stopAdvertisingAndListening: succes,s
ok 21 Should be able to call stopAdvertisingAndListening in teardown

,# Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-01-29 19:00:24.800 ThaliTest[763:1310544] jxcore: startUpdateAdvertisingAndListening
2016-01-29 19:00:24.801 ThaliTest[763:1310544] server: starting 95973D89-2F1E-4F25-8ADD-12CD6B75FDD1:1
2016-01-29 19:00:24.802 ThaliTest[763:1310544] THEMultipeerMa,nager initialized peer 95973D89-2F1E-4F25-8ADD-12CD6B75FDD1:1
2016-01-29 19:00:24.802 ThaliTest[763:1310544] jxcore: startUpdateAdvertisingAndListening: success
ok 22 Can call startUpdateAdvertisingAndListening without error

,2016-01-29 19:00:24.804 ThaliTest[763:1310544] jxcore: stopAdvertisingAndListening
2016-01-29 19:00:24.805 ThaliTest[763:1310544] THEMultipeerManager stopping peer
,2016-01-29 19:00:24.806 ThaliTest[763:1310544] jxcore: stopAdvertisingAndListening: success
,ok 23 Can call stopAdvertisingAndListening without error

,# setup

,2016-01-29 19:00:25.250 ThaliTest[763:1310544] jxcore: stopListeningForAdvertisements
2016-01-29 19:00:25.251 ThaliTest[763:1310544] jxcore: stopListeningForAdvertisements: success
ok 24 Should be able to call stopListeningForAdvertisments in teardown

,2016-01-29 19:00:25.252 ThaliTest[763:1310544] jxcore: stopAdvertisingAndListening
2016-01-29 19:00:25.253 ThaliTest[763:1310544] THEMultipeerManager stopping peer
2016-01-29 19:00:25.253 ThaliTest[763:1310544] jxcore: stopAdvertisingAndListening: success
ok 25 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startUpdateAdvertisingAndListening twice is NOT and error

,# teardown

,2016-01-29 19:00:27.268 ThaliTest[763:1310544] jxcore: startUpdateAdvertisingAndListening
2016-01-29 19:00:27.269 ThaliTest[763:1310544] server: starting 95973D89-2F1E-4F25-8ADD-12CD6B75FDD1:2
2016-01-29 19:00:27.269 ThaliTest[763:1310544] THEMultipeerMa,nager initialized peer 95973D89-2F1E-4F25-8ADD-12CD6B75FDD1:2
2016-01-29 19:00:27.269 ThaliTest[763:1310544] jxcore: startUpdateAdvertisingAndListening: success
ok 26 Can call startUpdateAdvertisingAndListening without error

,2016-01-29 19:00:27.271 ThaliTest[763:1310544] jxcore: startUpdateAdvertisingAndListening
2016-01-29 19:00:27.271 ThaliTest[763:1310544] THEMultipeerManager stopping peer
,2016-01-29 19:00:27.272 ThaliTest[763:1310544] server: starting 95973D89-2F1E-4F25-8ADD-12CD6B75FDD1:3
,2016-01-29 19:00:27.272 ThaliTest[763:1310544] THEMultipeerManager initialized peer 95973D89-2F1E-4F25-8ADD-12CD6B75FDD1:3
2016-01-29 19:00:27.272 ThaliTest[763:1310544] jxcore: startUpdateAdvertisingAndListening: success
ok 27 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-01-29 19:00:27.393 ThaliTest[763:1310544] jxcore: stopListeningForAdvertisements
2016-01-29 19:00:27.393 ThaliTest[763:1310544] jxcore: stopListeningForAdvertisements: success
ok 28 Should be able to call stopListeningForAdvertisments in teardown

,2016-01-29 19:00:27.395 ThaliTest[763:1310544] jxcore: stopAdvertisingAndListening
2016-01-29 19:00:27.395 ThaliTest[763:1310544] THEMultipeerManager stopping peer
2016-01-29 19:00:27.396 ThaliTest[763:1310544] jxcore: stopAdvertisingAndListening: success
ok 29 Should be able to call stopAdvertisingAndListening in teardown

,# peerAvailabilityChange is called

,# teardown

,2016-01-29 19:00:27.829 ThaliTest[763:1310544] jxcore: startUpdateAdvertisingAndListening
2016-01-29 19:00:27.830 ThaliTest[763:1310544] server: starting 95973D89-2F1E-4F25-8ADD-12CD6B75FDD1:4
2016-01-29 19:00:27.830 ThaliTest[763:1310544] THEMultipeerMa,nager initialized peer 95973D89-2F1E-4F25-8ADD-12CD6B75FDD1:4
2016-01-29 19:00:27.831 ThaliTest[763:1310544] jxcore: startUpdateAdvertisingAndListening: success
ok 30 Can call startUpdateAdvertisingAndListeningwithout error

,2016-01-29 19:00:27.833 ThaliTest[763:1310544] jxcore: startListeningForAdvertisements
,2016-01-29 19:00:27.834 ThaliTest[763:1310544] jxcore: startListeningForAdvertisements: success
ok 31 Can call startListeningForAdvertisements without error

,2016-01-29 19:00:28.772 ThaliTest[763:1310182] client: found peer: 770D1EEC-042B-4953-9292-E9415F928032
ok 32 peers must be an array

,ok 33 peers must not be zero-length

,ok 34 peer must have peerIdentifier

,ok 35 peerIdentifier must be a string

,ok 36 peer must have peerAvailable

,ok 37 peer must have pleaseConnect

,# setup

,2016-01-29 19:00:29.939 ThaliTest[763:1310544] jxcore: stopListeningForAdvertisements
2016-01-29 19:00:29.939 ThaliTest[763:1310544] jxcore: stopListeningForAdvertisements: success
ok 38 Should be able to call stopListeningForAdvertisments in teardown

,2016-01-29 19:00:29.941 ThaliTest[763:1310544] jxcore: stopAdvertisingAndListening
2016-01-29 19:00:29.942 ThaliTest[763:1310544] THEMultipeerManager stopping peer
,2016-01-29 19:00:29.943 ThaliTest[763:1310544] jxcore: stopAdvertisingAndListening: success
ok 39 Should be able to call stopAdvertisingAndListening in teardown

,# Can connect to a remote peer

,# teardown

,2016-01-29 19:00:30.025 ThaliTest[763:1310544] jxcore: startUpdateAdvertisingAndListening
2016-01-29 19:00:30.025 ThaliTest[763:1310544] server: starting 95973D89-2F1E-4F25-8ADD-12CD6B75FDD1:5
2016-01-29 19:00:30.026 ThaliTest[763:1310544] THEMultipeerMa,nager initialized peer 95973D89-2F1E-4F25-8ADD-12CD6B75FDD1:5
2016-01-29 19:00:30.026 ThaliTest[763:1310544] jxcore: startUpdateAdvertisingAndListening: success
ok 40 Can call startUpdateAdvertisingAndListening without error

,2016-01-29 19:00:30.028 ThaliTest[763:1310544] jxcore: startListeningForAdvertisements
,2016-01-29 19:00:30.029 ThaliTest[763:1310544] jxcore: startListeningForAdvertisements: success
,ok 41 Can call startListeningForAdvertisements without error

,2016-01-29 19:00:30.050 ThaliTest[763:1310182] client: found peer: 770D1EEC-042B-4953-9292-E9415F928032
2016-01-29 19:00:30.052 ThaliTest[763:1310544] jxcore: connect 770D1EEC-042B-4953-9292-E9415F928032:4
2016-01-29 19:00:30.053 ThaliTest[763:1310544] c,lient session: connect
2016-01-29 19:00:30.054 ThaliTest[763:1310544] client session: stateChange:0->1 770D1EEC-042B-4953-9292-E9415F928032:4
,2016-01-29 19:00:31.013 ThaliTest[763:1311350] client session: not connected 770D1EEC-042B-4953-9292-E9415F928032:4
,2016-01-29 19:00:31.013 ThaliTest[763:1311350] client session: onLinkFailure: 770D1EEC-042B-4953-9292-E9415F928032
2016-01-29 19:00:31.013 ThaliTest[763:1311350] client session: disconnect
2016-01-29 19:00:31.014 ThaliTest[763:1311350] client session: st,ateChange:1->0 770D1EEC-042B-4953-9292-E9415F928032:4
,2016-01-29 19:00:31.016 ThaliTest[763:1311350] client session: fireConnectCallback: 770D1EEC-042B-4953-9292-E9415F928032
2016-01-29 19:00:31.017 ThaliTest[763:1311350] jxcore: connect: fail: Peer disconnected
,2016-01-29 19:00:31.223 ThaliTest[763:1310182] server: rejecting invitation from 770D1EEC-042B-4953-9292-E9415F928032 due to previous generation (95973D89-2F1E-4F25-8ADD-12CD6B75FDD1:5 != 95973D89-2F1E-4F25-8ADD-12CD6B75FDD1:4)
,appEnteredForeground wasn't registered

,appEnteringBackground wasn't registered

,appEnteredForeground wasn't registered

,appEnteringBackground wasn't registered

,appEnteredForeground wasn't registered


```
