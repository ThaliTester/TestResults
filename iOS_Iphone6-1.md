#### Test 534296758dfd01f_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/534296758dfd01f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/55343295-C4F8-4829-AD98-152C15931048/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/55343295-C4F8-4829-AD98-152C15931048/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/534296758dfd01f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/534296758dfd01f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/29FD9EA4-9B69-4CCD-8261-693BCA1A5C85/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54406"
,(lldb)     command script import "/tmp/55343295-C4F8-4829-AD98-152C15931048/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-11 20:05:51.152 ThaliTest[794:751994] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/ADAA732B-7D7B-40C7-997E-6DD49E7FBD78/Library/Cookies/Cookies.binarycookies
,2015-12-11 20:05:51.560 ThaliTest[794:751994] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-11 20:05:51.561 ThaliTest[794:751994] Multi-tasking -> Device: YES, App: YES
,2015-12-11 20:05:51.571 ThaliTest[794:751994] Unlimited access to network resources
,2015-12-11 20:05:51.587 ThaliTest[794:751994] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-11 20:06:00.598 ThaliTest[794:751994] Resetting plugins due to page load.
,2015-12-11 20:06:03.277 ThaliTest[794:751994] Finished load of: file:///var/mobile/Containers/Bundle/Application/29FD9EA4-9B69-4CCD-8261-693BCA1A5C85/ThaliTest.app/www/index.html
,2015-12-11 20:06:03.457 ThaliTest[794:751994] JXcore Cordova plugin initializing
,2015-12-11 20:06:03.458 ThaliTest[794:752201] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone6-1_PT3759
,attempting to connect to test coordinator
,check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 56848
,2015-12-11 20:12:37.528 ThaliTest[794:752201] jxcore: startBroadcasting
,2015-12-11 20:12:37.544 ThaliTest[794:752201] server: starting Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:12:37.546 ThaliTest[794:752201] multipeer session: start timer: 0x18cab9b0
2015-12-11 20:12:37.546 ThaliTest[794:752201] THEMultipeerSession init,ialized peer Apple-Iphone6-1_PT3759
2015-12-11 20:12:37.548 ThaliTest[794:752201] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-11T19:12:37.552Z SendDataTCPServer.js: TCP/IP server is bound to port: 56848
,2015-12-11 20:12:39.267 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT818.I3iT5Q==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11T19:12:39.274Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11T19:12:39.275Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT818.I3iT5Q==
20,15-12-11T19:12:39.275Z SendDataConnector.js: do connect now
2015-12-11 20:12:39.276 ThaliTest[794:752201] jxcore: connect Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:12:39.276 ThaliTest[794:752201] client session: connect
2015-12-11 20:12:39.276 Thali,Test[794:752201] client session: stateChange:0->1 Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:12:39.729 ThaliTest[794:751994] multipeer session: reset timer
2015-12-11 20:12:39.729 ThaliTest[794:751994] multipeer session: stop timer
2015-12-11 20:12:39.729 ThaliTest[794:751994] multipeer session: start timer: 0x18cab9b0
2015-12-11 20:12:39.730 ThaliTest[794:751994] server session: connect
2015-12-11 20:12:39.730 ThaliTest[794:751994] server session: stateChange:0->1 Apple-IpadAir2-1_PT818
,2015-12-11 20:12:39.739 ThaliTest[794:751994] server: accepting invitation Apple-IpadAir2-1_PT818
,2015-12-11 20:12:41.814 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5466.2TZtug==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-12-11 20:12:42.408 ThaliTest[794:752851] client session: connected
2015-12-11 20:12:42.408 ThaliTest[794:752851] client session: stateChange:1->2 Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:12:42.412 ThaliTest[794:752851] client session: fireConnectCallback: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:12:42.413 ThaliTest[794:752851] jxcore: connect: success
,2015-12-11T19:12:42.415Z SendDataConnector.js: CLIENT connected to 56851, error: null
,2015-12-11T19:12:42.415Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 20:12:42.421 ThaliTest[794:751994] client: relay established
,2015-12-11 20:12:42.422 ThaliTest[794:751994] client: new accepted socket: 0x18f74ec0
,2015-12-11T19:12:42.435Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11 20:12:42.895 ThaliTest[794:752860] server session: connected
2015-12-11 20:12:42.895 ThaliTest[794:752860] server session: stateChange:1->2 Apple-IpadAir2-1_PT818
,2015-12-11 20:12:42.898 ThaliTest[794:751994] server relay: connected (to port: 56848)
,2015-12-11T19:12:42.900Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-11T19:12:42.903Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T19:12:42.977Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-11T19:12:43.299Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-11T19:12:43.338Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-11T19:12:43.364Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 20:12:43.434 ThaliTest[794:752861] server session: not connected Apple-IpadAir2-1_PT818
,2015-12-11T19:12:43.529Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-11T19:12:43.530Z SendDataConnector.js: got all data for this round
,2015-12-11T19:12:43.533Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T19:12:43.534Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 20:12:43.537 ThaliTest[794:752201] jxcore: disconnect
,2015-12-11 20:12:43.538 ThaliTest[794:752201] client session: disconnectFromPeer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:12:43.539 ThaliTest[794:752201] client session: disconnect
,2015-12-11 20:12:43.541 ThaliTest[794:752201] client session: stateChange:2->0 Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:12:43.567 ThaliTest[794:752201] jxcore: disconnect: success
,2015-12-11T19:12:43.577Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT818.I3iT5Q==
,---- round done--------
,device[2]: Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11T19:12:43.588Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11T19:12:43.589Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11T19:12:43.590Z SendDataConnector.js: do connect now
,2015-12-11 20:12:43.592 ThaliTest[794:752201] jxcore: connect Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:12:43.594 ThaliTest[794:752201] client session: connect
,2015-12-11 20:12:43.595 ThaliTest[794:752201] client session: stateChange:0->1 Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:12:45.140 ThaliTest[794:751994] multipeer session: reset timer
2015-12-11 20:12:45.140 ThaliTest[794:751994] multipeer session: stop timer
2015-12-11 20:12:45.140 ThaliTest[794:751994] multipeer session: start timer: 0x18cab9b0
2015-12-11 ,20:12:45.141 ThaliTest[794:751994] server session: connect
2015-12-11 20:12:45.141 ThaliTest[794:751994] server session: stateChange:0->1 Apple-Iphone5s-1_PT5466
,2015-12-11 20:12:45.149 ThaliTest[794:751994] server: accepting invitation Apple-Iphone5s-1_PT5466
,2015-12-11 20:12:46.644 ThaliTest[794:752860] client session: connected
,2015-12-11 20:12:46.644 ThaliTest[794:752860] client session: stateChange:1->2 Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:12:46.708 ThaliTest[794:752861] client session: fireConnectCallback: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:12:46.709 ThaliTest[794:752861] jxcore: connect: success
2015-12-11T19:12:46.710Z SendDataConnector.js: CLIENT connected to 56855, error: null
,2015-12-11T19:12:46.710Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 20:12:46.714 ThaliTest[794:751994] client: relay established
2015-12-11 20:12:46.714 ThaliTest[794:751994] client: new accepted socket: 0x18cb40d0
,2015-12-11T19:12:46.727Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T19:12:47.098Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-11T19:12:47.122Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-11T19:12:47.122Z SendDataConnector.js: got all data for this round
,2015-12-11T19:12:47.122Z SendDataConnector.js: CLIENT Stop now
2015-12-11T19:12:47.122Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 20:12:47.123 ThaliTest[794:752201] jxcore: disconnect
2015-12-11 20:12:47.123 ThaliTest[794:752201] client session: disconnectFromPeer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:12:47.123 ThaliTest[794:752201] client session: disconnect
,2015-12-11 20:12:47.123 ThaliTest[794:752201] client session: stateChange:2->0 Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:12:47.128 ThaliTest[794:752201] jxcore: disconnect: success
2015-12-11T19:12:47.128Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5466.2TZtug==
---- round done--------
,2015-12-11 20:12:48.172 ThaliTest[794:752860] server session: connected
2015-12-11 20:12:48.174 ThaliTest[794:752860] server session: stateChange:1->2 Apple-Iphone5s-1_PT5466
,2015-12-11 20:12:48.208 ThaliTest[794:751994] server relay: connected (to port: 56848)
2015-12-11T19:12:48.215Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T19:12:48.549Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-11T19:12:48.602Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-11T19:12:48.618Z SendDataTCPServer.js: TCP/IP server has received 50086 bytes of data
,2015-12-11T19:12:48.636Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-11T19:12:48.651Z SendDataTCPServer.js: TCP/IP server has received 82936 bytes of data
,2015-12-11T19:12:48.663Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 20:12:48.726 ThaliTest[794:752851] server session: not connected Apple-Iphone5s-1_PT5466
,2015-12-11 20:12:49.198 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4192.mhrLvw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[3]: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11T19:12:49.203Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11T19:12:49.203Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT4192.mhrLvw==
20,15-12-11T19:12:49.203Z SendDataConnector.js: do connect now
2015-12-11 20:12:49.204 ThaliTest[794:752201] jxcore: connect Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:12:49.205 ThaliTest[794:752201] client session: connect
2015-12-11 20:12:49.205 Thali,Test[794:752201] client session: stateChange:0->1 Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:13:15.141 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:13:22.105 ThaliTest[794:752904] client session: not connected Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:13:22.106 ThaliTest[794:752904] client session: onLinkFailure: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:13:22.106 ThaliTest[794,:752904] client session: disconnect
2015-12-11 20:13:22.106 ThaliTest[794:752904] client session: stateChange:1->0 Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:13:22.107 ThaliTest[794:752904] client session: fireConnectCallback: Apple-Iphone5-1_PT4192.m,hrLvw==
2015-12-11 20:13:22.107 ThaliTest[794:752904] jxcore: connect: fail: Peer disconnected
2015-12-11T19:13:22.109Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-11T19:13:22.109Z SendDataConnector.js: CLIENT Can not C,onnect: Peer disconnected
2015-12-11T19:13:22.110Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T19:13:27.114Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11T19:13:27.115Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:13:32.121 ThaliTest[794:752201] jxcore: disconnect
2015-12-11 20:13:32.122 ThaliTest[794:752201] jxcore: disconnect: fail
2015-12-11T19:13:32.122Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT4192.mhrLvw==,
2015-12-11T19:13:32.123Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT4192.mhrLvw== with availability status: true
2015-12-11T19:13:32.123Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11T19:13:32.123Z SendDataConnector.js: do connect now
,2015-12-11 20:13:32.124 ThaliTest[794:752201] jxcore: connect Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:13:32.125 ThaliTest[794:752201] client session: connect
2015-12-11 20:13:32.126 ThaliTest[794:752201] client session: stateChange:0->1 Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:13:32.136 ThaliTest[794:751994] client: lost peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:13:32.136 ThaliTest[794:751994] client session: onPeerLost: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:13:32.136 ThaliTest[794:751994] clien,t session: onLinkFailure: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:13:32.136 ThaliTest[794:751994] client session: disconnect
2015-12-11 20:13:32.137 ThaliTest[794:751994] client session: stateChange:1->0 Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 ,20:13:32.137 ThaliTest[794:751994] client session: fireConnectCallback: Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:13:32.137 ThaliTest[794:751994] jxcore: connect: fail: Peer disconnected
,2015-12-11T19:13:32.142Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-11T19:13:32.142Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-11T19:13:32.143Z SendDataConnector.js: tryAgain afer: 5000 ms.,
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4192.mhrLvw==","peerName":"(null)","peerAvailable":false}]
,2015-12-11T19:13:37.148Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11T19:13:37.149Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:13:42.154 ThaliTest[794:752201] jxcore: disconnect
2015-12-11 20:13:42.154 ThaliTest[794:752201] jxcore: disconnect: fail
2015-12-11T19:13:42.155Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT4192.mhrLvw==,
2015-12-11T19:13:42.155Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT4192.mhrLvw== with availability status: true
2015-12-11T19:13:42.156Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11T19:13:42.156Z SendDataConnector.js: do connect now
2015-12-11 20:13:42.157 ThaliTest[794:752201] jxcore: connect Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:13:42.158 ThaliTest[794:752201] client: connect: unreachable Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:13:42.158 ThaliTest[794:752201] jxcore: connect: fail: Peer unreachable
2015-12-11T19:13:42.159Z SendDataConnector.js: CLIENT connect,ed to 0, error: Peer unreachable
2015-12-11T19:13:42.159Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-11T19:13:42.159Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11 20:13:45.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:13:45.176 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:13:45.177 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4192.mhrLvw==","peerName":"(null)","peerAvailable":true}]
,2015-12-11 20:13:45.260 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11T19:13:47.166Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11T19:13:47.167Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:13:52.173 ThaliTest[794:752201] jxcore: disconnect
2015-12-11 20:13:52.174 ThaliTest[794:752201] jxcore: disconnect: fail
2015-12-11T19:13:52.174Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT4192.mhrLvw==,
2015-12-11T19:13:52.175Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT4192.mhrLvw== with availability status: true
2015-12-11T19:13:52.175Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11T19:13:52.175Z SendDataConnector.js: do connect now
2015-12-11 20:13:52.176 ThaliTest[794:752201] jxcore: connect Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:13:52.177 ThaliTest[794:752201] client session: connect
2015-12-11 20:13:52.177 ThaliTest[794:752201] client session: stateChange:0->1 Apple-Iphone5-1_PT4192.mhrLvw==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-11 20:14:15.141 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:14:15.991 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:14:15.991 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:14:15.991 ThaliTest[794:751994] client: foun,d peer: Apple-Iphone5s-1_PT5466.2TZtug==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:14:25.175 ThaliTest[794:753248] client session: not connected Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:14:25.175 ThaliTest[794:753248] client session: onLinkFailure: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:14:25.175 ThaliTest[794,:753248] client session: disconnect
2015-12-11 20:14:25.176 ThaliTest[794:753248] client session: stateChange:1->0 Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:14:25.176 ThaliTest[794:753248] client session: fireConnectCallback: Apple-Iphone5-1_PT4192.m,hrLvw==
2015-12-11 20:14:25.177 ThaliTest[794:753248] jxcore: connect: fail: Peer disconnected
2015-12-11T19:14:25.178Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-11T19:14:25.179Z SendDataConnector.js: CLIENT Can not C,onnect: Peer disconnected
2015-12-11T19:14:25.179Z SendDataConnector.js: tryAgain afer: 5000 ms.
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11T19:14:30.189Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11T19:14:30.190Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT4192.mhrLvw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:14:35.197 ThaliTest[794:752201] jxcore: disconnect
2015-12-11 20:14:35.198 ThaliTest[794:752201] jxcore: disconnect: fail
2015-12-11T19:14:35.198Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT4192.mhrLvw==,
2015-12-11T19:14:35.199Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT4192.mhrLvw== with availability status: true
2015-12-11T19:14:35.199Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11T19:14:35.199Z SendDataConnector.js: do connect now
,2015-12-11 20:14:35.201 ThaliTest[794:752201] jxcore: connect Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:14:35.202 ThaliTest[794:752201] client session: connect
2015-12-11 20:14:35.202 ThaliTest[794:752201] client session: stateChange:0->1 Apple-Iphone5-1_PT4192.mhrLvw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:14:45.142 ThaliTest[794:751994] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:15:08.110 ThaliTest[794:753287] client session: not connected Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:15:08.110 ThaliTest[794:753287] client session: onLinkFailure: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:15:08.110 ThaliTest[794,:753287] client session: disconnect
2015-12-11 20:15:08.110 ThaliTest[794:753287] client session: stateChange:1->0 Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:15:08.111 ThaliTest[794:753287] client session: fireConnectCallback: Apple-Iphone5-1_PT4192.m,hrLvw==
2015-12-11 20:15:08.111 ThaliTest[794:753287] jxcore: connect: fail: Peer disconnected
2015-12-11T19:15:08.113Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-11T19:15:08.114Z SendDataConnector.js: CLIENT Can not C,onnect: Peer disconnected
2015-12-11T19:15:08.115Z SendDataConnector.js: CLIENT Stop now
2015-12-11 20:15:08.115 ThaliTest[794:752201] jxcore: disconnect
2015-12-11 20:15:08.116 ThaliTest[794:752201] jxcore: disconnect: fail
2015-12-11T19:15:08.117Z Se,ndDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT4192.mhrLvw==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-Iphone6-1_PT3759","time":150610,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT818.I3iT5Q==","time":4258,"result":"OK","connections":1,"doneR,ounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT5466.2TZtug==","time":3533,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT4192.mhrLvw==","time":138911,"resu,lt":"Peer disconnected","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0}]}
,sendList : 100% : 4258 ms, 99% : 4258 ms, 95 : 4258 ms, 90% : 4258 ms.
,Result count 2, range 3533 ms to  4258 ms.
,sendList failed peers count : 1 [33.333333333333336 %]
,- Peer ID : Apple-Iphone5-1_PT4192.mhrLvw==, Tried : 5
,sendList never tried peers count : 0 [0 %]
2015-12-11T19:15:08.131Z SendDataConnector.js: CLIENT Stop now
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:15:15.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:15:15.174 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:15:15.175 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:15:15.180 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:15:45.142 ThaliTest[794:751994] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:16:15.141 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:16:15.177 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:16:15.177 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:16:15.177 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:16:45.143 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:16:45.184 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:16:45.186 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:16:45.187 ThaliTest[794:751994] client: fou,nd peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:17:15.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:17:15.180 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:17:15.181 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:17:15.181 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:17:45.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:17:45.179 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:17:45.181 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:17:45.182 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:18:15.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:18:15.179 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:18:15.179 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:18:15.185 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:18:45.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:18:45.179 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:18:45.180 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:18:45.181 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:19:15.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:19:15.178 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:19:15.179 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:19:15.179 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:19:45.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:19:45.179 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:19:45.180 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:19:45.180 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:20:15.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:20:15.177 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:20:15.178 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:20:15.181 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:20:45.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:20:45.175 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:20:45.175 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:20:45.176 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:21:15.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:21:15.175 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:21:15.176 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:21:15.176 ThaliTest[794:751994] client: fou,nd peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:21:45.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:21:45.184 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:21:45.184 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:21:45.185 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:22:15.142 ThaliTest[794:751994] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:22:45.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:22:45.180 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:22:45.180 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:22:45.180 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:23:15.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:23:15.178 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:23:15.182 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:23:15.182 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:23:45.142 ThaliTest[794:751994] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:24:15.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:24:15.176 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:24:15.179 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:24:15.179 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:24:45.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:24:45.181 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:24:45.182 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:24:45.183 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:25:15.142 ThaliTest[794:751994] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:25:45.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:25:45.177 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:25:45.177 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:25:45.178 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:26:15.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:26:15.180 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:26:15.180 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:26:15.185 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:26:45.142 ThaliTest[794:751994] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:27:15.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:27:15.179 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:27:15.181 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:27:15.181 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:27:45.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:27:45.180 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:27:45.180 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:27:45.187 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:28:15.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:28:15.180 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:28:15.180 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:28:15.183 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:28:45.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:28:45.176 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:28:45.179 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:28:45.179 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:29:15.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:29:15.179 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:29:15.179 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:29:15.180 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:29:45.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:29:45.178 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:29:45.179 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:29:45.182 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:30:15.142 ThaliTest[794:751994] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:30:45.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:30:45.176 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:30:45.178 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:30:45.179 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:31:15.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:31:15.179 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:31:15.181 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:31:15.181 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:31:45.142 ThaliTest[794:751994] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:32:15.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:32:15.180 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:32:15.181 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:32:15.181 ThaliTest[794:751994] client: fou,nd peer: Apple-Iphone5-1_PT4192.mhrLvw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:32:45.141 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:32:45.179 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:32:45.179 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:32:45.183 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:33:15.142 ThaliTest[794:751994] multipeer session: restart
,2015-12-11 20:33:15.177 ThaliTest[794:751994] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:33:15.180 ThaliTest[794:751994] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:33:15.180 ThaliTest[794:751994] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server

```
