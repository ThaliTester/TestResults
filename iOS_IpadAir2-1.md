#### Test 5753124305d96c2_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5753124305d96c2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/FD496B6D-802E-43CB-BEEC-61A671E9E289/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/FD496B6D-802E-43CB-BEEC-61A671E9E289/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5753124305d96c2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5753124305d96c2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9CDBB946-334F-4D34-A38F-8D8D478F3C87/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64602"
,(lldb)     command script import "/tmp/FD496B6D-802E-43CB-BEEC-61A671E9E289/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-02 15:13:58.185 ThaliTest[484:694183] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2C37B86B-C7CE-4E45-B32E-59AF6734207B/Library/Cookies/Cookies.binarycookies
,2016-02-02 15:13:58.579 ThaliTest[484:694183] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-02 15:13:58.580 ThaliTest[484:694183] Multi-tasking -> Device: YES, App: YES
,2016-02-02 15:13:58.589 ThaliTest[484:694183] Unlimited access to network resources
,2016-02-02 15:13:58.598 ThaliTest[484:694183] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-02 15:14:08.880 ThaliTest[484:694183] Resetting plugins due to page load.
,2016-02-02 15:14:12.641 ThaliTest[484:694183] Finished load of: file:///var/mobile/Containers/Bundle/Application/9CDBB946-334F-4D34-A38F-8D8D478F3C87/ThaliTest.app/www/index.html
,2016-02-02 15:14:12.800 ThaliTest[484:694183] JXcore Cordova plugin initializing
,2016-02-02 15:14:12.801 ThaliTest[484:694416] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CDBB946-334F-4D34-A38F-8D8D478F3C87/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CDBB946-334F-4D34-A38F-8D8D478F3C87/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CDBB946-334F-4D34-A38F-8D8D478F3C87/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CDBB946-334F-4D34-A38F-8D8D478F3C87/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CDBB946-334F-4D34-A38F-8D8D478F3C87/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,2016-02-02 15:18:58.904 ThaliTest[484:694416] jxcore: startListeningForAdvertisements
,2016-02-02 15:18:58.906 ThaliTest[484:694416] multipeer manager: start client restart timer: 0x17df4bd0
,2016-02-02 15:18:58.907 ThaliTest[484:694416] jxcore: startListeningForAdvertisements: success
,ok 13 Can call startListeningForAdvertisements without error

2016-02-02 15:18:58.911 ThaliTest[484:694416] jxcore: stopListeningForAdvertisements
,2016-02-02 15:18:58.913 ThaliTest[484:694416] multipeer manager: stop client timer
2016-02-02 15:18:58.914 ThaliTest[484:694416] jxcore: stopListeningForAdvertisements: success
,ok 14 Can call stopListeningForAdvertisements without error

,# setup

,2016-02-02 15:18:59.158 ThaliTest[484:694416] jxcore: stopListeningForAdvertisements
,2016-02-02 15:18:59.159 ThaliTest[484:694416] jxcore: stopListeningForAdvertisements: success
,ok 15 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 15:18:59.161 ThaliTest[484:694416] jxcore: stopAdvertisingAndListening
,2016-02-02 15:18:59.162 ThaliTest[484:694416] THEMultipeerManager stopping peer
,2016-02-02 15:18:59.162 ThaliTest[484:694416] jxcore: stopAdvertisingAndListening: success
,ok 16 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startListeningForAdvertisements twice is an error

,# teardown

,2016-02-02 15:18:59.341 ThaliTest[484:694416] jxcore: startListeningForAdvertisements
,2016-02-02 15:18:59.342 ThaliTest[484:694416] multipeer manager: start client restart timer: 0x17df4bd0
,2016-02-02 15:18:59.343 ThaliTest[484:694416] jxcore: startListeningForAdvertisements: success
,ok 17 Can call startListeningForAdvertisements without error

,2016-02-02 15:18:59.346 ThaliTest[484:694416] jxcore: startListeningForAdvertisements
,2016-02-02 15:18:59.347 ThaliTest[484:694416] jxcore: startListeningForAdvertisements: failure
,ok 18 Calling start twice is an error

,ok 19 Error must be "Call Stop!"

,# setup

,2016-02-02 15:18:59.397 ThaliTest[484:694416] jxcore: stopListeningForAdvertisements
,2016-02-02 15:18:59.398 ThaliTest[484:694416] multipeer manager: stop client timer
2016-02-02 15:18:59.399 ThaliTest[484:694416] jxcore: stopListeningForAdvertisements: success
,ok 20 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 15:18:59.402 ThaliTest[484:694416] jxcore: stopAdvertisingAndListening
,2016-02-02 15:18:59.403 ThaliTest[484:694416] THEMultipeerManager stopping peer
,2016-02-02 15:18:59.403 ThaliTest[484:694416] jxcore: stopAdvertisingAndListening: success
,ok 21 Should be able to call stopAdvertisingAndListening in teardown

,# Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-02-02 15:18:59.834 ThaliTest[484:694416] jxcore: startUpdateAdvertisingAndListening
,2016-02-02 15:18:59.835 ThaliTest[484:694416] server: starting AB1DBB37-C9D2-4DDF-B12C-8DB0EF52EC85:1
,2016-02-02 15:18:59.836 ThaliTest[484:694416] multipeer manager: start client restart timer: 0x17df4bd0
2016-02-02 15:18:59.836 ThaliTest[484:694416] THEMultipeerManager initialized peer AB1DBB37-C9D2-4DDF-B12C-8DB0EF52EC85:1
,2016-02-02 15:18:59.837 ThaliTest[484:694416] jxcore: startUpdateAdvertisingAndListening: success
ok 22 Can call startUpdateAdvertisingAndListening without error

,2016-02-02 15:18:59.840 ThaliTest[484:694416] jxcore: stopAdvertisingAndListening
,2016-02-02 15:18:59.840 ThaliTest[484:694416] THEMultipeerManager stopping peer
2016-02-02 15:18:59.841 ThaliTest[484:694416] multipeer manager: stop client timer
2016-02-02 15:18:59.841 ThaliTest[484:694416] jxcore: stopAdvertisingAndListening: success
ok 23 Can call stopAdvertisingAndListening without error

,# setup

,2016-02-02 15:18:59.917 ThaliTest[484:694416] jxcore: stopListeningForAdvertisements
2016-02-02 15:18:59.918 ThaliTest[484:694416] jxcore: stopListeningForAdvertisements: success
,ok 24 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 15:18:59.920 ThaliTest[484:694416] jxcore: stopAdvertisingAndListening
,2016-02-02 15:18:59.921 ThaliTest[484:694416] THEMultipeerManager stopping peer
,2016-02-02 15:18:59.921 ThaliTest[484:694416] jxcore: stopAdvertisingAndListening: success
,ok 25 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startUpdateAdvertisingAndListening twice is NOT and error

,# teardown

,2016-02-02 15:19:00.041 ThaliTest[484:694416] jxcore: startUpdateAdvertisingAndListening
,2016-02-02 15:19:00.041 ThaliTest[484:694416] server: starting AB1DBB37-C9D2-4DDF-B12C-8DB0EF52EC85:2
,2016-02-02 15:19:00.043 ThaliTest[484:694416] multipeer manager: start client restart timer: 0x17df4bd0
,2016-02-02 15:19:00.043 ThaliTest[484:694416] THEMultipeerManager initialized peer AB1DBB37-C9D2-4DDF-B12C-8DB0EF52EC85:2
,2016-02-02 15:19:00.044 ThaliTest[484:694416] jxcore: startUpdateAdvertisingAndListening: success
,ok 26 Can call startUpdateAdvertisingAndListening without error

2016-02-02 15:19:00.046 ThaliTest[484:694416] jxcore: startUpdateAdvertisingAndListening
,2016-02-02 15:19:00.047 ThaliTest[484:694416] THEMultipeerManager stopping peer
,2016-02-02 15:19:00.048 ThaliTest[484:694416] multipeer manager: stop client timer
,2016-02-02 15:19:00.048 ThaliTest[484:694416] server: starting AB1DBB37-C9D2-4DDF-B12C-8DB0EF52EC85:3
2016-02-02 15:19:00.049 ThaliTest[484:694416] multipeer manager: start client restart timer: 0x17df4bd0
,2016-02-02 15:19:00.052 ThaliTest[484:694416] THEMultipeerManager initialized peer AB1DBB37-C9D2-4DDF-B12C-8DB0EF52EC85:3
2016-02-02 15:19:00.053 ThaliTest[484:694416] jxcore: startUpdateAdvertisingAndListening: success
ok 27 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-02-02 15:19:00.361 ThaliTest[484:694416] jxcore: stopListeningForAdvertisements
,2016-02-02 15:19:00.362 ThaliTest[484:694416] jxcore: stopListeningForAdvertisements: success
,ok 28 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 15:19:00.365 ThaliTest[484:694416] jxcore: stopAdvertisingAndListening
2016-02-02 15:19:00.365 ThaliTest[484:694416] THEMultipeerManager stopping peer
,2016-02-02 15:19:00.366 ThaliTest[484:694416] multipeer manager: stop client timer
2016-02-02 15:19:00.366 ThaliTest[484:694416] jxcore: stopAdvertisingAndListening: success
,ok 29 Should be able to call stopAdvertisingAndListening in teardown

,# peerAvailabilityChange is called

,# teardown

,2016-02-02 15:19:00.437 ThaliTest[484:694416] jxcore: startUpdateAdvertisingAndListening
,2016-02-02 15:19:00.437 ThaliTest[484:694416] server: starting AB1DBB37-C9D2-4DDF-B12C-8DB0EF52EC85:4
,2016-02-02 15:19:00.439 ThaliTest[484:694416] multipeer manager: start client restart timer: 0x17df4bd0
2016-02-02 15:19:00.439 ThaliTest[484:694416] THEMultipeerManager initialized peer AB1DBB37-C9D2-4DDF-B12C-8DB0EF52EC85:4
2016-02-02 15:19:00.439 Thal,iTest[484:694416] jxcore: startUpdateAdvertisingAndListening: success
ok 30 Can call startUpdateAdvertisingAndListeningwithout error

,2016-02-02 15:19:00.441 ThaliTest[484:694416] jxcore: startListeningForAdvertisements
2016-02-02 15:19:00.441 ThaliTest[484:694416] multipeer manager: stop client timer
,2016-02-02 15:19:00.443 ThaliTest[484:694416] multipeer manager: start client restart timer: 0x17df4bd0
,2016-02-02 15:19:00.443 ThaliTest[484:694416] jxcore: startListeningForAdvertisements: success
,ok 31 Can call startListeningForAdvertisements without error

,2016-02-02 15:19:01.707 ThaliTest[484:694183] client: found new peer: 7F1BD6F8-FEEC-4B96-88ED-620CB1F8FC36:4
,ok 32 peers must be an array

,ok 33 peers must not be zero-length

,ok 34 peer must have peerIdentifier

,ok 35 peerIdentifier must be a string

,ok 36 peer must have peerAvailable

,ok 37 peer must have pleaseConnect

,# setup

,2016-02-02 15:19:01.945 ThaliTest[484:694416] jxcore: stopListeningForAdvertisements
,2016-02-02 15:19:01.946 ThaliTest[484:694416] jxcore: stopListeningForAdvertisements: success
,ok 38 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 15:19:01.949 ThaliTest[484:694416] jxcore: stopAdvertisingAndListening
2016-02-02 15:19:01.949 ThaliTest[484:694416] THEMultipeerManager stopping peer
,2016-02-02 15:19:01.950 ThaliTest[484:694416] multipeer manager: stop client timer
2016-02-02 15:19:01.950 ThaliTest[484:694416] jxcore: stopAdvertisingAndListening: success
,ok 39 Should be able to call stopAdvertisingAndListening in teardown

,# Can connect to a remote peer

,# teardown

,2016-02-02 15:19:02.013 ThaliTest[484:694416] jxcore: startUpdateAdvertisingAndListening
,2016-02-02 15:19:02.014 ThaliTest[484:694416] server: starting AB1DBB37-C9D2-4DDF-B12C-8DB0EF52EC85:5
,2016-02-02 15:19:02.017 ThaliTest[484:694416] multipeer manager: start client restart timer: 0x17df4bd0
,2016-02-02 15:19:02.024 ThaliTest[484:694416] THEMultipeerManager initialized peer AB1DBB37-C9D2-4DDF-B12C-8DB0EF52EC85:5
,2016-02-02 15:19:02.028 ThaliTest[484:694416] jxcore: startUpdateAdvertisingAndListening: success
,2016-02-02 15:19:02.030 ThaliTest[484:694183] client: found new peer: 7F1BD6F8-FEEC-4B96-88ED-620CB1F8FC36:4
,ok 40 Can call startUpdateAdvertisingAndListening without error
,
,2016-02-02 15:19:02.035 ThaliTest[484:694416] jxcore: startListeningForAdvertisements
,2016-02-02 15:19:02.039 ThaliTest[484:694416] multipeer manager: stop client timer
,2016-02-02 15:19:02.043 ThaliTest[484:694416] multipeer manager: start client restart timer: 0x17df4bd0
,2016-02-02 15:19:02.045 ThaliTest[484:694416] jxcore: startListeningForAdvertisements: success
,2016-02-02 15:19:02.052 ThaliTest[484:694183] client: found new peer: 7F1BD6F8-FEEC-4B96-88ED-620CB1F8FC36:4
,ok 41 Can call startListeningForAdvertisements without error

,2016-02-02 15:19:02.057 ThaliTest[484:694416] jxcore: connect 7F1BD6F8-FEEC-4B96-88ED-620CB1F8FC36:4
,2016-02-02 15:19:02.058 ThaliTest[484:694416] client session: connect
,2016-02-02 15:19:02.059 ThaliTest[484:694416] client session: stateChange:0->1 7F1BD6F8-FEEC-4B96-88ED-620CB1F8FC36:4
,2016-02-02 15:19:02.934 ThaliTest[484:694895] client session: not connected 7F1BD6F8-FEEC-4B96-88ED-620CB1F8FC36:4
2016-02-02 15:19:02.935 ThaliTest[484:694895] client session: onLinkFailure: 7F1BD6F8-FEEC-4B96-88ED-620CB1F8FC36
,2016-02-02 15:19:02.935 ThaliTest[484:694895] client session: disconnect
,2016-02-02 15:19:02.936 ThaliTest[484:694895] client session: stateChange:1->0 7F1BD6F8-FEEC-4B96-88ED-620CB1F8FC36:4
,2016-02-02 15:19:02.937 ThaliTest[484:694895] client session: fireConnectCallback: 7F1BD6F8-FEEC-4B96-88ED-620CB1F8FC36
2016-02-02 15:19:02.937 ThaliTest[484:694895] jxcore: connect: fail: Peer disconnected
,2016-02-02 15:19:03.283 ThaliTest[484:694183] multipeer session: reset timer
,2016-02-02 15:19:03.284 ThaliTest[484:694183] server: rejecting invitation from 7F1BD6F8-FEEC-4B96-88ED-620CB1F8FC36 due to previous generation (AB1DBB37-C9D2-4DDF-B12C-8DB0EF52EC85:5 != AB1DBB37-C9D2-4DDF-B12C-8DB0EF52EC85:4)
,appEnteredForeground wasn't registered

,appEnteringBackground wasn't registered


```
