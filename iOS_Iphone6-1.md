#### Test 5753124374916c2_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5753124374916c2/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/C585B81C-FD38-467E-B4CF-573F7F536897/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/C585B81C-FD38-467E-B4CF-573F7F536897/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5753124374916c2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5753124374916c2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7B968E6F-9BC2-411A-83A7-6D86C39C43EA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50685"
,(lldb)     command script import "/tmp/C585B81C-FD38-467E-B4CF-573F7F536897/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-05 15:13:25.028 ThaliTest[1292:2351844] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/87282291-8B33-4D07-9F72-2AF9A256DB7A/Library/Cookies/Cookies.binarycookies
,2016-02-05 15:13:25.310 ThaliTest[1292:2351844] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-05 15:13:25.311 ThaliTest[1292:2351844] Multi-tasking -> Device: YES, App: YES
,2016-02-05 15:13:25.315 ThaliTest[1292:2351844] Unlimited access to network resources
,2016-02-05 15:13:25.322 ThaliTest[1292:2351844] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-05 15:13:34.861 ThaliTest[1292:2351844] Resetting plugins due to page load.
,2016-02-05 15:13:38.716 ThaliTest[1292:2351844] Finished load of: file:///var/mobile/Containers/Bundle/Application/7B968E6F-9BC2-411A-83A7-6D86C39C43EA/ThaliTest.app/www/index.html
,2016-02-05 15:13:38.906 ThaliTest[1292:2351844] JXcore Cordova plugin initializing
,2016-02-05 15:13:39.013 ThaliTest[1292:2352275] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7B968E6F-9BC2-411A-83A7-6D86C39C43EA/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7B968E6F-9BC2-411A-83A7-6D86C39C43EA/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7B968E6F-9BC2-411A-83A7-6D86C39C43EA/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7B968E6F-9BC2-411A-83A7-6D86C39C43EA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7B968E6F-9BC2-411A-83A7-6D86C39C43EA/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,appEnteringBackground wasn't registered

,TAP version 13

,# setup

,got: setup_multiplex can send data

ack: setup_multiplex can send data_ok

,# multiplex can send data

,# teardown

,ok 1 String should be length:200

,# setup

,# enqueue and run in order

,got: setup_enqueue and run in order

ack: setup_enqueue and run in order_ok

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

,got: setup_basic

,ack: setup_basic_ok

,# teardown

,ok 11 sane

,# setup

,# another

,got: setup_another

ack: setup_another_ok

,# teardown

,ok 12 sane

,# setup

,# Can call start/stopListeningForAdvertisements

,got: setup_Can call start/stopListeningForAdvertisements

,ack: setup_Can call start/stopListeningForAdvertisements_ok

,# teardown

,2016-02-05 15:18:10.876 ThaliTest[1292:2352275] jxcore: startListeningForAdvertisements
,2016-02-05 15:18:10.879 ThaliTest[1292:2352275] multipeer manager: start client restart timer: 0x16ecfd70
2016-02-05 15:18:10.880 ThaliTest[1292:2352275] jxcore: startListeningForAdvertisements: success
,ok 13 Can call startListeningForAdvertisements without error

,2016-02-05 15:18:10.882 ThaliTest[1292:2352275] jxcore: stopListeningForAdvertisements
,2016-02-05 15:18:10.883 ThaliTest[1292:2352275] multipeer manager: stop client timer
,2016-02-05 15:18:10.884 ThaliTest[1292:2352275] jxcore: stopListeningForAdvertisements: success
,ok 14 Can call stopListeningForAdvertisements without error

# setup

,discoveryAdvertisingStateUpdate wasn't registered

discoveryAdvertisingStateUpdate wasn't registered

,2016-02-05 15:18:11.128 ThaliTest[1292:2352275] jxcore: stopListeningForAdvertisements
,2016-02-05 15:18:11.128 ThaliTest[1292:2352275] jxcore: stopListeningForAdvertisements: success
,ok 15 Should be able to call stopListeningForAdvertisments in teardown

2016-02-05 15:18:11.131 ThaliTest[1292:2352275] jxcore: stopAdvertisingAndListening
2016-02-05 15:18:11.131 ThaliTest[1292:2352275] THEMultipeerManager stopping peer
2016-02-05 15:,18:11.131 ThaliTest[1292:2352275] jxcore: stopAdvertisingAndListening: success
ok 16 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startListeningForAdvertisements twice is an error

,discoveryAdvertisingStateUpdate wasn't registered

,got: setup_Calling startListeningForAdvertisements twice is an error

,ack: setup_Calling startListeningForAdvertisements twice is an error_ok

,# teardown

,2016-02-05 15:18:11.285 ThaliTest[1292:2352275] jxcore: startListeningForAdvertisements
2016-02-05 15:18:11.286 ThaliTest[1292:2352275] multipeer manager: start client restart timer: 0x16ecfd70
2016-02-05 15:18:11.286 ThaliTest[1292:2352275] jxcore: star,tListeningForAdvertisements: success
ok 17 Can call startListeningForAdvertisements without error

2016-02-05 15:18:11.288 ThaliTest[1292:2352275] jxcore: startListeningForAdvertisements
2016-02-05 15:18:11.288 ThaliTest[1292:2352275] jxcore: startList,eningForAdvertisements: failure
ok 18 Calling start twice is an error

,ok 19 Error must be "Call Stop!"

,# setup

,discoveryAdvertisingStateUpdate wasn't registered

discoveryAdvertisingStateUpdate wasn't registered

,2016-02-05 15:18:11.643 ThaliTest[1292:2352275] jxcore: stopListeningForAdvertisements
2016-02-05 15:18:11.643 ThaliTest[1292:2352275] multipeer manager: stop client timer
2016-02-05 15:18:11.644 ThaliTest[1292:2352275] jxcore: stopListeningForAdvertisem,ents: success
ok 20 Should be able to call stopListeningForAdvertisments in teardown

2016-02-05 15:18:11.645 ThaliTest[1292:2352275] jxcore: stopAdvertisingAndListening
2016-02-05 15:18:11.646 ThaliTest[1292:2352275] THEMultipeerManager stopping peer,
2016-02-05 15:18:11.646 ThaliTest[1292:2352275] jxcore: stopAdvertisingAndListening: success
ok 21 Should be able to call stopAdvertisingAndListening in teardown

,# Can call start/stopUpdateAdvertisingAndListening

,discoveryAdvertisingStateUpdate wasn't registered

,got: setup_Can call start/stopUpdateAdvertisingAndListening

,ack: setup_Can call start/stopUpdateAdvertisingAndListening_ok

,# teardown

,2016-02-05 15:18:11.862 ThaliTest[1292:2352275] jxcore: startUpdateAdvertisingAndListening
2016-02-05 15:18:11.863 ThaliTest[1292:2352275] server: starting 500454C9-5940-429C-B7E2-E6139CA81B63:1
2016-02-05 15:18:11.864 ThaliTest[1292:2352275] multipeer m,anager: start client restart timer: 0x16ecfd70
2016-02-05 15:18:11.864 ThaliTest[1292:2352275] THEMultipeerManager initialized peer 500454C9-5940-429C-B7E2-E6139CA81B63:1
2016-02-05 15:18:11.864 ThaliTest[1292:2352275] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 22 Can call startUpdateAdvertisingAndListening without error

2016-02-05 15:18:11.867 ThaliTest[1292:2352275] jxcore: stopAdvertisingAndListening
2016-02-05 15:18:11.868 ThaliTest[1292:2352275] THEMultipeerManager stopping peer
201,6-02-05 15:18:11.868 ThaliTest[1292:2352275] multipeer manager: stop client timer
2016-02-05 15:18:11.869 ThaliTest[1292:2352275] jxcore: stopAdvertisingAndListening: success
ok 23 Can call stopAdvertisingAndListening without error

,# setup

,2016-02-05 15:18:12.390 ThaliTest[1292:2352275] jxcore: stopListeningForAdvertisements
,2016-02-05 15:18:12.391 ThaliTest[1292:2352275] jxcore: stopListeningForAdvertisements: success
,ok 24 Should be able to call stopListeningForAdvertisments in teardown

2016-02-05 15:18:12.393 ThaliTest[1292:2352275] jxcore: stopAdvertisingAndListening
2016-02-05 15:18:12.393 ThaliTest[1292:2352275] THEMultipeerManager stopping peer
2016-02-05 15:,18:12.393 ThaliTest[1292:2352275] jxcore: stopAdvertisingAndListening: success
ok 25 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startUpdateAdvertisingAndListening twice is NOT and error

,discoveryAdvertisingStateUpdate wasn't registered

,got: setup_Calling startUpdateAdvertisingAndListening twice is NOT and error

ack: setup_Calling startUpdateAdvertisingAndListening twice is NOT and error_ok

,# teardown

,2016-02-05 15:18:13.237 ThaliTest[1292:2352275] jxcore: startUpdateAdvertisingAndListening
2016-02-05 15:18:13.238 ThaliTest[1292:2352275] server: starting 500454C9-5940-429C-B7E2-E6139CA81B63:2
2016-02-05 15:18:13.239 ThaliTest[1292:2352275] multipeer m,anager: start client restart timer: 0x16ecfd70
2016-02-05 15:18:13.239 ThaliTest[1292:2352275] THEMultipeerManager initialized peer 500454C9-5940-429C-B7E2-E6139CA81B63:2
2016-02-05 15:18:13.240 ThaliTest[1292:2352275] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 26 Can call startUpdateAdvertisingAndListening without error

,2016-02-05 15:18:13.244 ThaliTest[1292:2352275] jxcore: startUpdateAdvertisingAndListening
2016-02-05 15:18:13.244 ThaliTest[1292:2352275] THEMultipeerManager stopping peer
2016-02-05 15:18:13.245 ThaliTest[1292:2352275] multipeer manager: stop client ti,mer
2016-02-05 15:18:13.245 ThaliTest[1292:2352275] server: starting 500454C9-5940-429C-B7E2-E6139CA81B63:3
2016-02-05 15:18:13.246 ThaliTest[1292:2352275] multipeer manager: start client restart timer: 0x16ecfd70
2016-02-05 15:18:13.246 ThaliTest[1292:,2352275] THEMultipeerManager initialized peer 500454C9-5940-429C-B7E2-E6139CA81B63:3
2016-02-05 15:18:13.246 ThaliTest[1292:2352275] jxcore: startUpdateAdvertisingAndListening: success
ok 27 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-02-05 15:18:13.350 ThaliTest[1292:2352275] jxcore: stopListeningForAdvertisements
2016-02-05 15:18:13.350 ThaliTest[1292:2352275] jxcore: stopListeningForAdvertisements: success
ok 28 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-05 15:18:13.352 ThaliTest[1292:2352275] jxcore: stopAdvertisingAndListening
2016-02-05 15:18:13.352 ThaliTest[1292:2352275] THEMultipeerManager stopping peer
,2016-02-05 15:18:13.353 ThaliTest[1292:2352275] multipeer manager: stop client timer
2016-02-05 15:18:13.353 ThaliTest[1292:2352275] jxcore: stopAdvertisingAndListening: success
,ok 29 Should be able to call stopAdvertisingAndListening in teardown

# peerAvailabilityChange is called

,discoveryAdvertisingStateUpdate wasn't registered

,got: setup_peerAvailabilityChange is called

ack: setup_peerAvailabilityChange is called_ok

,# teardown

,2016-02-05 15:18:13.769 ThaliTest[1292:2352275] jxcore: startUpdateAdvertisingAndListening
2016-02-05 15:18:13.770 ThaliTest[1292:2352275] server: starting 500454C9-5940-429C-B7E2-E6139CA81B63:4
2016-02-05 15:18:13.771 ThaliTest[1292:2352275] multipeer m,anager: start client restart timer: 0x16ecfd70
2016-02-05 15:18:13.772 ThaliTest[1292:2352275] THEMultipeerManager initialized peer 500454C9-5940-429C-B7E2-E6139CA81B63:4
2016-02-05 15:18:13.772 ThaliTest[1292:2352275] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 30 Can call startUpdateAdvertisingAndListeningwithout error

2016-02-05 15:18:13.774 ThaliTest[1292:2352275] jxcore: startListeningForAdvertisements
,2016-02-05 15:18:13.778 ThaliTest[1292:2352275] multipeer manager: stop client timer
2016-02-05 15:18:13.779 ThaliTest[1292:2352275] multipeer manager: start client restart timer: 0x16ecfd70
2016-02-05 15:18:13.780 ThaliTest[1292:2352275] jxcore: startLi,steningForAdvertisements: success
ok 31 Can call startListeningForAdvertisements without error

discoveryAdvertisingStateUpdate wasn't registered

,2016-02-05 15:18:15.043 ThaliTest[1292:2351844] client: found new peer: 104EA696-8B16-4F69-9896-C2A337571063:4
,ok 32 peers must be an array

ok 33 peers must not be zero-length

,ok 34 peer must have peerIdentifier

ok 35 peerIdentifier must be a string

,ok 36 peer must have peerAvailable

,ok 37 peer must have pleaseConnect

,# setup

,2016-02-05 15:18:17.863 ThaliTest[1292:2351844] client: lost peer: 104EA696-8B16-4F69-9896-C2A337571063
2016-02-05 15:18:17.863 ThaliTest[1292:2351844] client session: onPeerLost: 104EA696-8B16-4F69-9896-C2A337571063
,2016-02-05 15:18:18.542 ThaliTest[1292:2352275] jxcore: stopListeningForAdvertisements
2016-02-05 15:18:18.543 ThaliTest[1292:2352275] jxcore: stopListeningForAdvertisements: success
ok 38 Should be able to call stopListeningForAdvertisments in teardown,

,2016-02-05 15:18:18.544 ThaliTest[1292:2352275] jxcore: stopAdvertisingAndListening
2016-02-05 15:18:18.545 ThaliTest[1292:2352275] THEMultipeerManager stopping peer
2016-02-05 15:18:18.545 ThaliTest[1292:2352275] multipeer manager: stop client timer
,2016-02-05 15:18:18.546 ThaliTest[1292:2352275] jxcore: stopAdvertisingAndListening: success
,ok 39 Should be able to call stopAdvertisingAndListening in teardown

# Can connect to a remote peer

,discoveryAdvertisingStateUpdate wasn't registered

,got: setup_Can connect to a remote peer

ack: setup_Can connect to a remote peer_ok

,# teardown

,2016-02-05 15:18:18.960 ThaliTest[1292:2352275] jxcore: startUpdateAdvertisingAndListening
2016-02-05 15:18:18.960 ThaliTest[1292:2352275] server: starting 500454C9-5940-429C-B7E2-E6139CA81B63:5
2016-02-05 15:18:18.961 ThaliTest[1292:2352275] multipeer m,anager: start client restart timer: 0x16ecfd70
2016-02-05 15:18:18.962 ThaliTest[1292:2352275] THEMultipeerManager initialized peer 500454C9-5940-429C-B7E2-E6139CA81B63:5
2016-02-05 15:18:18.962 ThaliTest[1292:2352275] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 40 Can call startUpdateAdvertisingAndListening without error

,2016-02-05 15:18:18.965 ThaliTest[1292:2352275] jxcore: startListeningForAdvertisements
2016-02-05 15:18:18.966 ThaliTest[1292:2352275] multipeer manager: stop client timer
2016-02-05 15:18:18.966 ThaliTest[1292:2352275] multipeer manager: start client r,estart timer: 0x16ecfd70
2016-02-05 15:18:18.967 ThaliTest[1292:2352275] jxcore: startListeningForAdvertisements: success
ok 41 Can call startListeningForAdvertisements without error

,discoveryAdvertisingStateUpdate wasn't registered

,2016-02-05 15:18:20.424 ThaliTest[1292:2351844] multipeer session: reset timer
2016-02-05 15:18:20.425 ThaliTest[1292:2351844] server: rejecting invitation from 104EA696-8B16-4F69-9896-C2A337571063 due to previous generation (500454C9-5940-429C-B7E2-E6139CA81B63:5 != 500454C9-5940-429C-B7E2-E6139CA81B63:4)
,2016-02-05 15:18:21.288 ThaliTest[1292:2351844] client: found new peer: 104EA696-8B16-4F69-9896-C2A337571063:5
2016-02-05 15:18:21.291 ThaliTest[1292:2352275] jxcore: connect 104EA696-8B16-4F69-9896-C2A337571063:5
2016-02-05 15:18:21.291 ThaliTest[1292:2352275] client session: connect
,2016-02-05 15:18:21.292 ThaliTest[1292:2352275] client session: stateChange:0->1 104EA696-8B16-4F69-9896-C2A337571063:5
,2016-02-05 15:18:24.228 ThaliTest[1292:2352849] client session: connected
2016-02-05 15:18:24.228 ThaliTest[1292:2352849] client session: stateChange:1->2 104EA696-8B16-4F69-9896-C2A337571063:5
,2016-02-05 15:18:24.294 ThaliTest[1292:2352855] client session: fireConnectCallback: 104EA696-8B16-4F69-9896-C2A337571063
2016-02-05 15:18:24.294 ThaliTest[1292:2352855] jxcore: connect: success
,{ clientPort: 0, serverPort: 0, listeningPort: 57206 }

,ok 42 Connection must have listeningPort

,ok 43 listeningPort must be a number

,ok 44 Connection must have clientPort

,ok 45 clientPort must be null

,ok 46 Connection must have serverPort

,ok 47 serverPort must be null

,# setup

,2016-02-05 15:18:26.061 ThaliTest[1292:2352855] client session: not connected 104EA696-8B16-4F69-9896-C2A337571063:5
2016-02-05 15:18:26.061 ThaliTest[1292:2352855] client session: onLinkFailure: 104EA696-8B16-4F69-9896-C2A337571063
2016-02-05 15:18:26.0,62 ThaliTest[1292:2352855] client session: disconnect
2016-02-05 15:18:26.062 ThaliTest[1292:2352855] client session: stateChange:2->0 104EA696-8B16-4F69-9896-C2A337571063:5
,2016-02-05 15:18:26.424 ThaliTest[1292:2352275] jxcore: stopListeningForAdvertisements
,2016-02-05 15:18:26.425 ThaliTest[1292:2352275] jxcore: stopListeningForAdvertisements: success
,ok 48 Should be able to call stopListeningForAdvertisments in teardown

2016-02-05 15:18:26.427 ThaliTest[1292:2352275] jxcore: stopAdvertisingAndListening
2016-02-05 15:18:26.428 ThaliTest[1292:2352275] THEMultipeerManager stopping peer
2016-02-05 15:,18:26.428 ThaliTest[1292:2352275] multipeer manager: stop client timer
2016-02-05 15:18:26.429 ThaliTest[1292:2352275] jxcore: stopAdvertisingAndListening: success
ok 49 Should be able to call stopAdvertisingAndListening in teardown

,# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,discoveryAdvertisingStateUpdate wasn't registered

,got: setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,ack: setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted_ok

,# teardown

,ok 50 host address should match

,ok 51 port should match

,ok 52 peer should be available

,ok 53 peer should be unavailable

,# setup

,# #startUpdateAdvertisingAndListening should use different USN after every invocation

,got: setup_#startUpdateAdvertisingAndListening should use different USN after every invocation

,ack: setup_#startUpdateAdvertisingAndListening should use different USN after every invocation_ok

,# teardown

,ok 54 when receiving the first byebye, the second USN should not be set yet

,ok 55 USN should have changed from the first one

,ok 56 when receiving the second byebye, the first USN should be already set

,# setup

,# messages with invalid location or USN should be ignored

,got: setup_messages with invalid location or USN should be ignored

,ack: setup_messages with invalid location or USN should be ignored_ok

,# teardown

,WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000

,ok 57 should not have emitted with invalid port

,WARN thaliWifiInfrastructure Received an invalid USN value: 

,ok 58 should not have emitted with invalid USN

,# setup

,# verify that Thali-specific messages are filtered correctly

,got: setup_verify that Thali-specific messages are filtered correctly

ack: setup_verify that Thali-specific messages are filtered correctly_ok

,# teardown

,ok 59 irrelevant messages should be ignored

,ok 60 relevant messages should not be ignored

,ok 61 messages from this device should be ignored

,# setup

,# #start should fail if called twice in a row

,got: setup_#start should fail if called twice in a row

,ack: setup_#start should fail if called twice in a row_ok

,# teardown

,ok 62 specific error should be received

,# setup

,# #startUpdateAdvertisingAndListening should fail invalid router has been passed

,got: setup_#startUpdateAdvertisingAndListening should fail invalid router has been passed

,ack: setup_#startUpdateAdvertisingAndListening should fail invalid router has been passed_ok

,# teardown

,ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string

,ok 63 specific error should be received

,# setup

,# #startUpdateAdvertisingAndListening should fail if router server starting fails

,got: setup_#startUpdateAdvertisingAndListening should fail if router server starting fails

,ack: setup_#startUpdateAdvertisingAndListening should fail if router server starting fails_ok

,# teardown

,ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE

,ok 64 specific error expected

,# setup

,# #startUpdateAdvertisingAndListening should start hosting given router object

,got: setup_#startUpdateAdvertisingAndListening should start hosting given router object

,ack: setup_#startUpdateAdvertisingAndListening should start hosting given router object_ok

,# teardown

,ok 65 server should respond with code 200

,# setup

,# #stop can be called multiple times in a row

,got: setup_#stop can be called multiple times in a row

,ack: setup_#stop can be called multiple times in a row_ok
,
,# teardown

,ok 66 should be in stopped state

,ok 67 should still be in stopped state

,# setup

,# #startListeningForAdvertisements can be called multiple times in a row

,got: setup_#startListeningForAdvertisements can be called multiple times in a row

,ack: setup_#startListeningForAdvertisements can be called multiple times in a row_ok

,# teardown

,ok 68 should be in listening state

,ok 69 should still be in listening state

,# setup

,# #stopListeningForAdvertisements can be called multiple times in a row

,got: setup_#stopListeningForAdvertisements can be called multiple times in a row

,ack: setup_#stopListeningForAdvertisements can be called multiple times in a row_ok

,# teardown

,ok 70 should not be in listening state

,ok 71 should still not be in listening state

,# setup

,# #stopAdvertisingAndListening can be called multiple times in a row

,got: setup_#stopAdvertisingAndListening can be called multiple times in a row

,ack: setup_#stopAdvertisingAndListening can be called multiple times in a row_ok

,# teardown

,ok 72 should not be in advertising state

,ok 73 should still not be in advertising state

,# setup

,# functions are run from a queue in the right order

,got: setup_functions are run from a queue in the right order

,ack: setup_functions are run from a queue in the right order_ok

,# teardown

,ok 74 call order must match

,Tests Complete

,Total: 0	Passed: 0	Failed: 0

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
