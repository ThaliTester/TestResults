#### Test 575312438097721_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/575312438097721/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/C0E58682-D619-499A-9D38-048816A18E27/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/C0E58682-D619-499A-9D38-048816A18E27/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/575312438097721/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/575312438097721/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D267CAE5-576A-4A8F-AB32-74F95D58A4A2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64762"
,(lldb)     command script import "/tmp/C0E58682-D619-499A-9D38-048816A18E27/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-02 17:13:27.463 ThaliTest[1045:1901261] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7480E716-AD4A-4EDF-97C0-42F935F09181/Library/Cookies/Cookies.binarycookies
,2016-02-02 17:13:27.818 ThaliTest[1045:1901261] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-02 17:13:27.819 ThaliTest[1045:1901261] Multi-tasking -> Device: YES, App: YES
,2016-02-02 17:13:27.829 ThaliTest[1045:1901261] Unlimited access to network resources
,2016-02-02 17:13:27.840 ThaliTest[1045:1901261] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-02 17:13:37.497 ThaliTest[1045:1901261] Resetting plugins due to page load.
,2016-02-02 17:13:40.947 ThaliTest[1045:1901261] Finished load of: file:///var/mobile/Containers/Bundle/Application/D267CAE5-576A-4A8F-AB32-74F95D58A4A2/ThaliTest.app/www/index.html
,2016-02-02 17:13:41.128 ThaliTest[1045:1901261] JXcore Cordova plugin initializing
,2016-02-02 17:13:41.241 ThaliTest[1045:1901585] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D267CAE5-576A-4A8F-AB32-74F95D58A4A2/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D267CAE5-576A-4A8F-AB32-74F95D58A4A2/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D267CAE5-576A-4A8F-AB32-74F95D58A4A2/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D267CAE5-576A-4A8F-AB32-74F95D58A4A2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D267CAE5-576A-4A8F-AB32-74F95D58A4A2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,2016-02-02 17:18:09.962 ThaliTest[1045:1901585] jxcore: startListeningForAdvertisements
,2016-02-02 17:18:09.965 ThaliTest[1045:1901585] multipeer manager: start client restart timer: 0x156b5770
2016-02-02 17:18:09.966 ThaliTest[1045:1901585] jxcore: startListeningForAdvertisements: success
ok 13 Can call startListeningForAdvertisements without error

,2016-02-02 17:18:09.968 ThaliTest[1045:1901585] jxcore: stopListeningForAdvertisements
2016-02-02 17:18:09.969 ThaliTest[1045:1901585] multipeer manager: stop client timer
2016-02-02 17:18:09.969 ThaliTest[1045:1901585] jxcore: stopListeningForAdvertisements: success
ok 14 Can call stopListeningForAdvertisements without error

,# setup

,2016-02-02 17:18:10.044 ThaliTest[1045:1901585] jxcore: stopListeningForAdvertisements
,2016-02-02 17:18:10.045 ThaliTest[1045:1901585] jxcore: stopListeningForAdvertisements: success
,ok 15 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 17:18:10.048 ThaliTest[1045:1901585] jxcore: stopAdvertisingAndListening
,2016-02-02 17:18:10.050 ThaliTest[1045:1901585] THEMultipeerManager stopping peer
,2016-02-02 17:18:10.051 ThaliTest[1045:1901585] jxcore: stopAdvertisingAndListening: success
,ok 16 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startListeningForAdvertisements twice is an error

,# teardown

,2016-02-02 17:18:10.319 ThaliTest[1045:1901585] jxcore: startListeningForAdvertisements
,2016-02-02 17:18:10.321 ThaliTest[1045:1901585] multipeer manager: start client restart timer: 0x156b5770
,2016-02-02 17:18:10.324 ThaliTest[1045:1901585] jxcore: startListeningForAdvertisements: success
,ok 17 Can call startListeningForAdvertisements without error

,2016-02-02 17:18:10.329 ThaliTest[1045:1901585] jxcore: startListeningForAdvertisements
,2016-02-02 17:18:10.331 ThaliTest[1045:1901585] jxcore: startListeningForAdvertisements: failure
,ok 18 Calling start twice is an error

,ok 19 Error must be "Call Stop!"

,# setup

,2016-02-02 17:18:10.456 ThaliTest[1045:1901585] jxcore: stopListeningForAdvertisements
2016-02-02 17:18:10.456 ThaliTest[1045:1901585] multipeer manager: stop client timer
2016-02-02 17:18:10.457 ThaliTest[1045:1901585] jxcore: stopListeningForAdvertisements: success
ok 20 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 17:18:10.459 ThaliTest[1045:1901585] jxcore: stopAdvertisingAndListening
2016-02-02 17:18:10.459 ThaliTest[1045:1901585] THEMultipeerManager stopping peer
2016-02-02 17:18:10.459 ThaliTest[1045:1901585] jxcore: stopAdvertisingAndListening: success
,ok 21 Should be able to call stopAdvertisingAndListening in teardown

,# Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-02-02 17:18:10.869 ThaliTest[1045:1901585] jxcore: startUpdateAdvertisingAndListening
2016-02-02 17:18:10.870 ThaliTest[1045:1901585] server: starting CC82672F-8CE5-4BAD-9985-B96C116558BE:1
2016-02-02 17:18:10.870 ThaliTest[1045:1901585] multipeer m,anager: start client restart timer: 0x156b5770
2016-02-02 17:18:10.871 ThaliTest[1045:1901585] THEMultipeerManager initialized peer CC82672F-8CE5-4BAD-9985-B96C116558BE:1
2016-02-02 17:18:10.871 ThaliTest[1045:1901585] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 22 Can call startUpdateAdvertisingAndListening without error

2016-02-02 17:18:10.874 ThaliTest[1045:1901585] jxcore: stopAdvertisingAndListening
2016-02-02 17:18:10.874 ThaliTest[1045:1901585] THEMultipeerManager stopping peer
201,6-02-02 17:18:10.875 ThaliTest[1045:1901585] multipeer manager: stop client timer
2016-02-02 17:18:10.875 ThaliTest[1045:1901585] jxcore: stopAdvertisingAndListening: success
ok 23 Can call stopAdvertisingAndListening without error

,# setup

,2016-02-02 17:18:11.403 ThaliTest[1045:1901585] jxcore: stopListeningForAdvertisements
2016-02-02 17:18:11.404 ThaliTest[1045:1901585] jxcore: stopListeningForAdvertisements: success
ok 24 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 17:18:11.405 ThaliTest[1045:1901585] jxcore: stopAdvertisingAndListening
,2016-02-02 17:18:11.406 ThaliTest[1045:1901585] THEMultipeerManager stopping peer
,2016-02-02 17:18:11.407 ThaliTest[1045:1901585] jxcore: stopAdvertisingAndListening: success
ok 25 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startUpdateAdvertisingAndListening twice is NOT and error

,# teardown

,2016-02-02 17:18:11.964 ThaliTest[1045:1901585] jxcore: startUpdateAdvertisingAndListening
2016-02-02 17:18:11.964 ThaliTest[1045:1901585] server: starting CC82672F-8CE5-4BAD-9985-B96C116558BE:2
2016-02-02 17:18:11.965 ThaliTest[1045:1901585] multipeer m,anager: start client restart timer: 0x156b5770
2016-02-02 17:18:11.966 ThaliTest[1045:1901585] THEMultipeerManager initialized peer CC82672F-8CE5-4BAD-9985-B96C116558BE:2
2016-02-02 17:18:11.966 ThaliTest[1045:1901585] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 26 Can call startUpdateAdvertisingAndListening without error

2016-02-02 17:18:11.968 ThaliTest[1045:1901585] jxcore: startUpdateAdvertisingAndListening
2016-02-02 17:18:11.968 ThaliTest[1045:1901585] THEMultipeerManager stopping pe,er
2016-02-02 17:18:11.968 ThaliTest[1045:1901585] multipeer manager: stop client timer
2016-02-02 17:18:11.969 ThaliTest[1045:1901585] server: starting CC82672F-8CE5-4BAD-9985-B96C116558BE:3
2016-02-02 17:18:11.969 ThaliTest[1045:1901585] multipeer man,ager: start client restart timer: 0x156b5770
2016-02-02 17:18:11.975 ThaliTest[1045:1901585] THEMultipeerManager initialized peer CC82672F-8CE5-4BAD-9985-B96C116558BE:3
2016-02-02 17:18:11.976 ThaliTest[1045:1901585] jxcore: startUpdateAdvertisingAndListening: success
ok 27 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-02-02 17:18:12.023 ThaliTest[1045:1901585] jxcore: stopListeningForAdvertisements
2016-02-02 17:18:12.023 ThaliTest[1045:1901585] jxcore: stopListeningForAdvertisements: success
ok 28 Should be able to call stopListeningForAdvertisments in teardown,

,2016-02-02 17:18:12.025 ThaliTest[1045:1901585] jxcore: stopAdvertisingAndListening
2016-02-02 17:18:12.025 ThaliTest[1045:1901585] THEMultipeerManager stopping peer
2016-02-02 17:18:12.026 ThaliTest[1045:1901585] multipeer manager: stop client timer
20,16-02-02 17:18:12.026 ThaliTest[1045:1901585] jxcore: stopAdvertisingAndListening: success
ok 29 Should be able to call stopAdvertisingAndListening in teardown

,# peerAvailabilityChange is called

,# teardown

,2016-02-02 17:18:12.362 ThaliTest[1045:1901585] jxcore: startUpdateAdvertisingAndListening
2016-02-02 17:18:12.362 ThaliTest[1045:1901585] server: starting CC82672F-8CE5-4BAD-9985-B96C116558BE:4
2016-02-02 17:18:12.363 ThaliTest[1045:1901585] multipeer m,anager: start client restart timer: 0x156b5770
2016-02-02 17:18:12.363 ThaliTest[1045:1901585] THEMultipeerManager initialized peer CC82672F-8CE5-4BAD-9985-B96C116558BE:4
2016-02-02 17:18:12.364 ThaliTest[1045:1901585] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 30 Can call startUpdateAdvertisingAndListeningwithout error

2016-02-02 17:18:12.365 ThaliTest[1045:1901585] jxcore: startListeningForAdvertisements
2016-02-02 17:18:12.366 ThaliTest[1045:1901585] multipeer manager: stop client time,r
2016-02-02 17:18:12.366 ThaliTest[1045:1901585] multipeer manager: start client restart timer: 0x156b5770
2016-02-02 17:18:12.367 ThaliTest[1045:1901585] jxcore: startListeningForAdvertisements: success
ok 31 Can call startListeningForAdvertisements w,ithout error

,2016-02-02 17:18:13.162 ThaliTest[1045:1901261] client: found new peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:4
ok 32 peers must be an array

ok 33 peers must not be zero-length

,ok 34 peer must have peerIdentifier

,ok 35 peerIdentifier must be a string

ok 36 peer must have peerAvailable

ok 37 peer must have pleaseConnect

,# setup

,2016-02-02 17:18:13.872 ThaliTest[1045:1901585] jxcore: stopListeningForAdvertisements
2016-02-02 17:18:13.873 ThaliTest[1045:1901585] jxcore: stopListeningForAdvertisements: success
ok 38 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 17:18:13.875 ThaliTest[1045:1901585] jxcore: stopAdvertisingAndListening
,2016-02-02 17:18:13.875 ThaliTest[1045:1901585] THEMultipeerManager stopping peer
2016-02-02 17:18:13.877 ThaliTest[1045:1901585] multipeer manager: stop client timer
2016-02-02 17:18:13.877 ThaliTest[1045:1901585] jxcore: stopAdvertisingAndListening: success
ok 39 Should be able to call stopAdvertisingAndListening in teardown

,# Can connect to a remote peer

,# teardown

,2016-02-02 17:18:14.887 ThaliTest[1045:1901585] jxcore: startUpdateAdvertisingAndListening
2016-02-02 17:18:14.888 ThaliTest[1045:1901585] server: starting CC82672F-8CE5-4BAD-9985-B96C116558BE:5
2016-02-02 17:18:14.889 ThaliTest[1045:1901585] multipeer m,anager: start client restart timer: 0x156b5770
2016-02-02 17:18:14.889 ThaliTest[1045:1901585] THEMultipeerManager initialized peer CC82672F-8CE5-4BAD-9985-B96C116558BE:5
2016-02-02 17:18:14.890 ThaliTest[1045:1901585] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 40 Can call startUpdateAdvertisingAndListening without error

2016-02-02 17:18:14.891 ThaliTest[1045:1901585] jxcore: startListeningForAdvertisements
2016-02-02 17:18:14.892 ThaliTest[1045:1901585] multipeer manager: stop client tim,er
2016-02-02 17:18:14.892 ThaliTest[1045:1901585] multipeer manager: start client restart timer: 0x156b5770
2016-02-02 17:18:14.893 ThaliTest[1045:1901585] jxcore: startListeningForAdvertisements: success
ok 41 Can call startListeningForAdvertisements ,without error

,2016-02-02 17:18:15.009 ThaliTest[1045:1901261] client: found new peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:4
2016-02-02 17:18:15.011 ThaliTest[1045:1901585] jxcore: connect 7548CBFA-E4A4-4015-A6EA-FADE5525928F:4
2016-02-02 17:18:15.012 ThaliTest[1045:1901585] client session: connect
2016-02-02 17:18:15.012 ThaliTest[1045:1901585] client session: stateChange:0->1 7548CBFA-E4A4-4015-A6EA-FADE5525928F:4
,2016-02-02 17:18:15.918 ThaliTest[1045:1902098] client session: not connected 7548CBFA-E4A4-4015-A6EA-FADE5525928F:4
2016-02-02 17:18:15.919 ThaliTest[1045:1902098] client session: onLinkFailure: 7548CBFA-E4A4-4015-A6EA-FADE5525928F
2016-02-02 17:18:15.920 ThaliTest[1045:1902098] client session: disconnect
2016-02-02 17:18:15.920 ThaliTest[1045:1902098] client session: stateChange:1->0 7548CBFA-E4A4-4015-A6EA-FADE5525928F:4
,2016-02-02 17:18:15.922 ThaliTest[1045:1902098] client session: fireConnectCallback: 7548CBFA-E4A4-4015-A6EA-FADE5525928F
,2016-02-02 17:18:15.923 ThaliTest[1045:1902098] jxcore: connect: fail: Peer disconnected
,2016-02-02 17:18:15.971 ThaliTest[1045:1901261] multipeer session: reset timer
2016-02-02 17:18:15.972 ThaliTest[1045:1901261] server: rejecting invitation from 7548CBFA-E4A4-4015-A6EA-FADE5525928F due to previous generation (CC82672F-8CE5-4BAD-9985-B96C116558BE:5 != CC82672F-8CE5-4BAD-9985-B96C116558BE:4)
,2016-02-02 17:18:34.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:18:34.914 ThaliTest[1045:1901261] client: found updated peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
2016-02-02 17:18:34.916 ThaliTest[1045:1901585] jxcore: connect 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
2016-02-02 17:18:34.917 ThaliTest[1045:1901585] client session: connect
2016-02-02 17:18:34.917 ThaliTest[1045:1901585] client session: stateChange:0->1 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:18:35.964 ThaliTest[1045:1901261] multipeer session: reset timer
2016-02-02 17:18:35.965 ThaliTest[1045:1901261] server: disconnecting to refresh session (7548CBFA-E4A4-4015-A6EA-FADE5525928F)
2016-02-02 17:18:35.966 ThaliTest[1045:1901261] server: rejecting invitation for lexical ordering 7548CBFA-E4A4-4015-A6EA-FADE5525928F
,2016-02-02 17:18:35.968 ThaliTest[1045:1901585] jxcore: connect 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
2016-02-02 17:18:35.972 ThaliTest[1045:1901585] client: already connect(ing/ed) to 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
2016-02-02 17:18:35.974 ThaliTest[1045:1901585] jxcore: connect: fail: Aleady connecting
,2016-02-02 17:18:38.661 ThaliTest[1045:1902165] client session: connected
2016-02-02 17:18:38.661 ThaliTest[1045:1902165] client session: stateChange:1->2 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:18:38.666 ThaliTest[1045:1902165] client session: fireConnectCallback: 7548CBFA-E4A4-4015-A6EA-FADE5525928F
,2016-02-02 17:18:38.666 ThaliTest[1045:1902165] jxcore: connect: success
,{ clientPort: 0, serverPort: 0, listeningPort: 55330 }

,ok 42 Connection must have listeningPort

,ok 43 listeningPort must be a number

,ok 44 Connection must have clientPort

,ok 45 clientPort must be null

,ok 46 Connection must have serverPort

,ok 47 serverPort must be null

,# setup

,2016-02-02 17:18:54.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:18:54.911 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:19:14.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:19:14.912 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:19:34.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:19:49.583 ThaliTest[1045:1902336] client session: not connected 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
2016-02-02 17:19:49.583 ThaliTest[1045:1902336] client session: onLinkFailure: 7548CBFA-E4A4-4015-A6EA-FADE5525928F
2016-02-02 17:19:49.5,84 ThaliTest[1045:1902336] client session: disconnect
2016-02-02 17:19:49.584 ThaliTest[1045:1902336] client session: stateChange:2->0 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:19:54.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:19:54.910 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,appEnteredForeground wasn't registered

,2016-02-02 17:20:14.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:20:14.913 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,appEnteringBackground wasn't registered

,2016-02-02 17:20:34.893 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:20:34.911 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:20:54.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:20:54.919 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:21:14.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:21:14.912 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:21:34.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:21:34.912 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:21:54.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:21:54.911 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,appEnteredForeground wasn't registered

,2016-02-02 17:22:14.893 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:22:34.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:22:34.905 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,appEnteringBackground wasn't registered

,2016-02-02 17:22:54.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:22:54.906 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:23:14.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:23:14.906 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:23:34.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:23:34.905 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:23:54.893 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:23:54.905 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:24:14.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:24:14.904 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,appEnteredForeground wasn't registered

,2016-02-02 17:24:34.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:24:34.906 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,appEnteringBackground wasn't registered

,2016-02-02 17:24:54.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:24:54.907 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:25:14.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:25:14.907 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:25:34.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:25:34.906 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:25:54.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:25:54.906 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:26:14.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:26:14.907 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:26:34.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:26:34.907 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:26:54.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:26:54.906 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,appEnteredForeground wasn't registered

,2016-02-02 17:27:14.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:27:14.906 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:27:34.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:27:34.906 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:27:54.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:27:54.906 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:28:14.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:28:14.906 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:28:34.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:28:34.906 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:28:54.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:28:54.907 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:29:14.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:29:14.906 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:29:34.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:29:34.906 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:29:54.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:29:54.907 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:30:14.893 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:30:34.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:30:34.906 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:30:54.894 ThaliTest[1045:1901261] multipeer manager: restart client
,2016-02-02 17:30:54.906 ThaliTest[1045:1901261] client: found existing peer: 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5

```
