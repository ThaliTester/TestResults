#### Test 51790364c93db41_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51790364c93db41/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/BBB52C3A-A6EE-46F6-AB9B-8B82C56EAC43/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/BBB52C3A-A6EE-46F6-AB9B-8B82C56EAC43/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/51790364c93db41/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51790364c93db41/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8B3D6AD3-2F4B-41FF-A9B7-E6449A65D5D8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55623"
,(lldb)     command script import "/tmp/BBB52C3A-A6EE-46F6-AB9B-8B82C56EAC43/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-11-25 14:26:18.385 ThaliTest[1679:1305817] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/67FECD32-224F-4868-941C-5E88AA2D5BB5/Library/Cookies/Cookies.binarycookies
,2015-11-25 14:26:18.765 ThaliTest[1679:1305817] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-25 14:26:18.766 ThaliTest[1679:1305817] Multi-tasking -> Device: YES, App: YES
,2015-11-25 14:26:18.774 ThaliTest[1679:1305817] Unlimited access to network resources
,2015-11-25 14:26:18.780 ThaliTest[1679:1305817] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-25 14:26:22.325 ThaliTest[1679:1305817] Resetting plugins due to page load.
,2015-11-25 14:26:22.665 ThaliTest[1679:1305817] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/8B3D6AD3-2F4B-41FF-A9B7-E6449A65D5D8/ThaliTest.app/www/index.html
,2015-11-25 14:26:22.788 ThaliTest[1679:1305817] JXcore Cordova plugin initializing
,2015-11-25 14:26:22.789 ThaliTest[1679:1305955] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
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
,my name is : Apple-Iphone6-1_PT8475
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 61902
,2015-11-25 14:32:34.976 ThaliTest[1679:1305955] jxcore: startBroadcasting
,2015-11-25 14:32:34.987 ThaliTest[1679:1305955] server: starting Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:32:34.988 ThaliTest[1679:1305955] multipeer session: start timer: 0x1c584180
2015-11-25 14:32:34.989 ThaliTest[1679:1305955] THEMultipeerSession initialized peer Apple-Iphone6-1_PT8475
2015-11-25 14:32:34.989 ThaliTest[1679:1305955] jxcore:, startBroadcasting: success
StartBroadcasting started ok
2015-11-25T13:32:34.992Z SendDataTCPServer.js: TCP/IP server is bound to port: 61902
,2015-11-25 14:32:35.409 ThaliTest[1679:1305817] client: found peer: Apple-Iphone5s-1_PT8640.H39DFw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8640.H39DFw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT8640.H39DFw==
2015-11-25T13:32:35.412Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8640.H39DFw==
2015-11-25T13:32:35.413Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8640.H39DFw==
2015-11-25T13:32:35.413Z SendDataConnector.js: do connect now
,2015-11-25 14:32:35.413 ThaliTest[1679:1305955] jxcore: connect Apple-Iphone5s-1_PT8640.H39DFw==
2015-11-25 14:32:35.414 ThaliTest[1679:1305955] client session: connect
2015-11-25 14:32:35.414 ThaliTest[1679:1305955] client session: stateChange:0->1 Apple-Iphone5s-1_PT8640.H39DFw==
,2015-11-25 14:32:35.652 ThaliTest[1679:1305817] multipeer session: reset timer
2015-11-25 14:32:35.653 ThaliTest[1679:1305817] multipeer session: stop timer
2015-11-25 14:32:35.653 ThaliTest[1679:1305817] multipeer session: start timer: 0x1c584180
2015-,11-25 14:32:35.656 ThaliTest[1679:1305817] server session: connect
2015-11-25 14:32:35.656 ThaliTest[1679:1305817] server session: stateChange:0->1 Apple-Iphone5-1_PT6254
,2015-11-25 14:32:35.674 ThaliTest[1679:1305817] server: accepting invitation Apple-Iphone5-1_PT6254
,2015-11-25 14:32:36.264 ThaliTest[1679:1305817] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1710.FkeXvQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,2015-11-25 14:32:36.397 ThaliTest[1679:1305817] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6254.8TiZaA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-25 14:32:37.952 ThaliTest[1679:1306521] client session: connected
2015-11-25 14:32:37.953 ThaliTest[1679:1306521] client session: stateChange:1->2 Apple-Iphone5s-1_PT8640.H39DFw==
,2015-11-25 14:32:37.967 ThaliTest[1679:1306515] client session: fireConnectCallback: Apple-Iphone5s-1_PT8640.H39DFw==
2015-11-25 14:32:37.968 ThaliTest[1679:1306515] jxcore: connect: success
2015-11-25T13:32:37.970Z SendDataConnector.js: CLIENT connected to 61905, error: null
,2015-11-25T13:32:37.971Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 14:32:37.975 ThaliTest[1679:1305817] client: relay established
,2015-11-25 14:32:37.976 ThaliTest[1679:1305817] client: new accepted socket: 0x17e65790
,2015-11-25T13:32:37.987Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T13:32:38.100Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-25T13:32:38.113Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-25T13:32:38.151Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-25T13:32:38.152Z SendDataConnector.js: got all data for this round
,2015-11-25T13:32:38.153Z SendDataConnector.js: CLIENT Stop now
2015-11-25T13:32:38.153Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-25 14:32:38.153 ThaliTest[1679:1305955] jxcore: disconnect
2015-11-25 14:32:38.154 ThaliTest[1679:1305955] cli,ent session: disconnectFromPeer: Apple-Iphone5s-1_PT8640.H39DFw==
2015-11-25 14:32:38.154 ThaliTest[1679:1305955] client session: disconnect
2015-11-25 14:32:38.154 ThaliTest[1679:1305955] client session: stateChange:2->0 Apple-Iphone5s-1_PT8640.H39DFw==,
2015-11-25 14:32:38.155 ThaliTest[1679:1305955] jxcore: disconnect: success
2015-11-25T13:32:38.155Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8640.H39DFw==
---- round done--------
,device[2]: Apple-IpadAir2-1_PT1710.FkeXvQ==
2015-11-25T13:32:38.156Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1710.FkeXvQ==
2015-11-25T13:32:38.157Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1710.FkeXvQ==
2015-11-25T13:32:38.157Z SendDataConnector.js: do connect now
2015-11-25 14:32:38.157 ThaliTest[1679:1305955] jxcore: connect Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:32:38.158 ThaliTest[1679:1305955] client session: connect
,2015-11-25 14:32:38.159 ThaliTest[1679:1305955] client session: stateChange:0->1 Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:32:38.343 ThaliTest[1679:1306509] server session: connected
2015-11-25 14:32:38.343 ThaliTest[1679:1306509] server session: stateChange:1->2 Apple-Iphone5-1_PT6254
,2015-11-25 14:32:38.347 ThaliTest[1679:1305817] server relay: connected (to port: 61902)
,2015-11-25T13:32:38.354Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T13:32:38.501Z SendDataTCPServer.js: TCP/IP server has received 6944 bytes of data
,2015-11-25T13:32:38.513Z SendDataTCPServer.js: TCP/IP server has received 28768 bytes of data
,2015-11-25T13:32:38.527Z SendDataTCPServer.js: TCP/IP server has received 49600 bytes of data
,2015-11-25T13:32:38.540Z SendDataTCPServer.js: TCP/IP server has received 65472 bytes of data
,2015-11-25T13:32:38.554Z SendDataTCPServer.js: TCP/IP server has received 83328 bytes of data
,2015-11-25T13:32:38.577Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 14:32:38.593 ThaliTest[1679:1306519] server session: not connected Apple-Iphone5-1_PT6254
,2015-11-25 14:32:40.003 ThaliTest[1679:1305817] multipeer session: reset timer
2015-11-25 14:32:40.004 ThaliTest[1679:1305817] multipeer session: stop timer
2015-11-25 14:32:40.004 ThaliTest[1679:1305817] multipeer session: start timer: 0x1c584180
2015-,11-25 14:32:40.005 ThaliTest[1679:1305817] server session: connect
2015-11-25 14:32:40.005 ThaliTest[1679:1305817] server session: stateChange:0->1 Apple-IpadAir2-1_PT1710
,2015-11-25 14:32:40.016 ThaliTest[1679:1305817] server: accepting invitation Apple-IpadAir2-1_PT1710
,2015-11-25 14:32:42.238 ThaliTest[1679:1306521] server session: connected
2015-11-25 14:32:42.238 ThaliTest[1679:1306521] server session: stateChange:1->2 Apple-IpadAir2-1_PT1710
,2015-11-25 14:32:42.247 ThaliTest[1679:1305817] server relay: connected (to port: 61902)
2015-11-25T13:32:42.253Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T13:32:42.648Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-11-25T13:32:42.666Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 14:32:42.694 ThaliTest[1679:1306519] server session: not connected Apple-IpadAir2-1_PT1710
,2015-11-25 14:32:44.236 ThaliTest[1679:1306509] client session: connected
,2015-11-25 14:32:44.237 ThaliTest[1679:1306509] client session: stateChange:1->2 Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:32:44.245 ThaliTest[1679:1306534] client session: fireConnectCallback: Apple-IpadAir2-1_PT1710.FkeXvQ==
2015-11-25 14:32:44.246 ThaliTest[1679:1306534] jxcore: connect: success
2015-11-25T13:32:44.247Z SendDataConnector.js: CLIENT connected, to 61910, error: null
,2015-11-25T13:32:44.247Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 14:32:44.251 ThaliTest[1679:1305817] client: relay established
2015-11-25 14:32:44.251 ThaliTest[1679:1305817] client: new accepted socket: 0x1c58eec0
,2015-11-25T13:32:44.264Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T13:32:44.369Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-25T13:32:44.382Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T13:32:44.382Z SendDataConnector.js: got all data for this round
,2015-11-25T13:32:44.383Z SendDataConnector.js: CLIENT Stop now
2015-11-25T13:32:44.383Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-25 14:32:44.383 ThaliTest[1679:1305955] jxcore: disconnect
2015-11-25 14:32:44.383 ThaliTest[1679:1305955] client session: disconnectFromPeer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:32:44.383 ThaliTest[1679:1305955] client session: disconnect
2015-11-25 14:32:44.384 ThaliTest[1679:1305955] client session: stateChange:2->0 Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:32:44.385 ThaliTest[1679:1305955] jxcore: disconnect: success
2015-11-25T13:32:44.385Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1710.FkeXvQ==
---- round done--------
device[3]: Apple-Iphone5-1_PT6254.,8TiZaA==
2015-11-25T13:32:44.386Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25T13:32:44.386Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25T13:32:44.386Z SendDataCon,nector.js: do connect now
2015-11-25 14:32:44.387 ThaliTest[1679:1305955] jxcore: connect Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25 14:32:44.387 ThaliTest[1679:1305955] client session: connect
2015-11-25 14:32:44.387 ThaliTest[1679:1305955] client sess,ion: stateChange:0->1 Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:32:48.315 ThaliTest[1679:1306521] client session: connected
2015-11-25 14:32:48.316 ThaliTest[1679:1306521] client session: stateChange:1->2 Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:32:48.321 ThaliTest[1679:1306521] client session: fireConnectCallback: Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25 14:32:48.321 ThaliTest[1679:1306521] jxcore: connect: success
,2015-11-25T13:32:48.323Z SendDataConnector.js: CLIENT connected to 61913, error: null
2015-11-25T13:32:48.323Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 14:32:48.327 ThaliTest[1679:1305817] client: relay established
2015-11-25 14:32:48.328 ThaliTest[1679:1305817] client: new accepted socket: 0x1c66c030
,2015-11-25T13:32:48.339Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T13:32:48.458Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-25T13:32:48.471Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-25T13:32:48.484Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-25T13:32:48.484Z SendDataConnector.js: got all data for this round
,2015-11-25T13:32:48.484Z SendDataConnector.js: CLIENT Stop now
2015-11-25T13:32:48.485Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-25 14:32:48.485 ThaliTest[1679:1305955] jxcore: disconnect
,2015-11-25 14:32:48.485 ThaliTest[1679:1305955] client session: disconnectFromPeer: Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25 14:32:48.485 ThaliTest[1679:1305955] client session: disconnect
,2015-11-25 14:32:48.486 ThaliTest[1679:1305955] client session: stateChange:2->0 Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25 14:32:48.487 ThaliTest[1679:1305955] jxcore: disconnect: success
2015-11-25T13:32:48.487Z SendDataConnector.js: Mobile.Disconnect(,) callback with peer Apple-Iphone5-1_PT6254.8TiZaA==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT8475","time":13530,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT8640.H39DFw==","time":2739,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT1710.FkeXvQ==","time":6225,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT6254.8TiZaA==","time":4098,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 6225 ms, 99% : 6225 ms, 95 : 6225 ms, 90% : 6225 ms.
,Result count 3, range 2739 ms to  6225 ms.
sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-11-25T13:32:48.493Z SendDataConnector.js: CLIENT Stop now
2015-11-25T13:32:48.493Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 14:33:10.004 ThaliTest[1679:1305817] multipeer session: restart
,2015-11-25 14:33:10.024 ThaliTest[1679:1305817] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25 14:33:10.026 ThaliTest[1679:1305817] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
2015-11-25 14:33:10.028 ThaliTest[1679:1305817] clien,t: found peer: Apple-Iphone5s-1_PT8640.H39DFw==
,2015-11-25 14:33:13.968 ThaliTest[1679:1305817] client: lost peer: Apple-Iphone5s-1_PT8640.H39DFw==
2015-11-25 14:33:13.968 ThaliTest[1679:1305817] client session: onPeerLost: Apple-Iphone5s-1_PT8640.H39DFw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8640.H39DFw==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 14:33:14.985 ThaliTest[1679:1305817] client: found peer: Apple-Iphone5s-1_PT8640.H39DFw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8640.H39DFw==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 14:33:40.004 ThaliTest[1679:1305817] multipeer session: restart
,2015-11-25 14:33:40.019 ThaliTest[1679:1305817] client: found peer: Apple-Iphone5s-1_PT8640.H39DFw==
2015-11-25 14:33:40.020 ThaliTest[1679:1305817] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25 14:33:40.022 ThaliTest[1679:1305817] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:33:43.811 ThaliTest[1679:1305817] client: found peer: Apple-Iphone5s-1_PT8640.H39DFw==
,2015-11-25 14:34:10.004 ThaliTest[1679:1305817] multipeer session: restart
,2015-11-25 14:34:10.049 ThaliTest[1679:1305817] client: found peer: Apple-Iphone5s-1_PT8640.H39DFw==
,2015-11-25 14:34:10.052 ThaliTest[1679:1305817] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25 14:34:10.053 ThaliTest[1679:1305817] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:34:40.004 ThaliTest[1679:1305817] multipeer session: restart
,2015-11-25 14:34:40.023 ThaliTest[1679:1305817] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25 14:34:40.025 ThaliTest[1679:1305817] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:34:40.073 ThaliTest[1679:1305817] client: found peer: Apple-Iphone5s-1_PT8640.H39DFw==
,2015-11-25 14:34:41.075 ThaliTest[1679:1305817] client: lost peer: Apple-Iphone5s-1_PT8640.H39DFw==
2015-11-25 14:34:41.075 ThaliTest[1679:1305817] client session: onPeerLost: Apple-Iphone5s-1_PT8640.H39DFw==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT8640.H39DFw==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 14:35:10.004 ThaliTest[1679:1305817] multipeer session: restart
,2015-11-25 14:35:10.021 ThaliTest[1679:1305817] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25 14:35:10.023 ThaliTest[1679:1305817] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:35:40.004 ThaliTest[1679:1305817] multipeer session: restart
,2015-11-25 14:35:40.021 ThaliTest[1679:1305817] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25 14:35:40.022 ThaliTest[1679:1305817] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:36:10.002 ThaliTest[1679:1305817] multipeer session: restart
,2015-11-25 14:36:10.017 ThaliTest[1679:1305817] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25 14:36:10.019 ThaliTest[1679:1305817] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:36:40.002 ThaliTest[1679:1305817] multipeer session: restart
,2015-11-25 14:36:40.016 ThaliTest[1679:1305817] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:36:40.018 ThaliTest[1679:1305817] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:37:10.002 ThaliTest[1679:1305817] multipeer session: restart
,2015-11-25 14:37:10.019 ThaliTest[1679:1305817] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25 14:37:10.020 ThaliTest[1679:1305817] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:37:40.002 ThaliTest[1679:1305817] multipeer session: restart
,2015-11-25 14:37:40.016 ThaliTest[1679:1305817] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25 14:37:40.017 ThaliTest[1679:1305817] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:38:10.001 ThaliTest[1679:1305817] multipeer session: restart
,2015-11-25 14:38:10.015 ThaliTest[1679:1305817] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25 14:38:10.017 ThaliTest[1679:1305817] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:38:39.996 ThaliTest[1679:1305817] multipeer session: restart
,2015-11-25 14:38:40.011 ThaliTest[1679:1305817] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:38:40.013 ThaliTest[1679:1305817] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:39:09.996 ThaliTest[1679:1305817] multipeer session: restart
,2015-11-25 14:39:10.012 ThaliTest[1679:1305817] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25 14:39:10.014 ThaliTest[1679:1305817] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:39:39.996 ThaliTest[1679:1305817] multipeer session: restart
2015-11-25 14:39:40.002 ThaliTest[1679:1305817] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Fi,rst throw call stack:
(0x26e2efef 0x35798c8b 0x26d4aaa3 0x28e09d85 0x26932607 0x26931e81 0x268ab3d3 0x26df4faf 0x26df43bf 0x26df2a25 0x26d3f201 0x26d3f013 0x2e7ca201 0x2a50ba09 0xe45e3 0x35d4aaaf)
libc++abi.dylib: terminating with uncaught exception of type NSException
,Process 1679 stopped
* thread #1: tid = 0x13ecd9, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x35e14df0 <+8>:  blo    0x35e14e08                ; <+32>
    0x35e14df4 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x35e14df8 <+16>: ldr    r12, [pc, r12]
    0x35e14dfc <+20>: b      0x35e14e04                ; <+28>
,* thread #1: tid = 0x13ecd9, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
  * frame #0: 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x35e93cc6 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x35db0908 libsystem_c.dylib`abort + 76
    frame #3: 0x350a79c8 libc++abi.dylib`<redacted> + 88
    frame #4: 0x350c1670 libc++abi.dylib`<redacted> + 268
    frame #5: 0x35798f24 libobjc.A.dylib`<redacted> + 192
    frame #6: 0x350bede2 libc++abi.dylib`<redacted> + 78
    frame #7: 0x350be8ae libc++abi.dylib`__cxa_rethrow + 102
    frame #8: 0x35798dd2 libobjc.A.dylib`objc_exception_rethrow + 42
    frame #9: 0x26d3f29c CoreFoundation`CFRunLoopRunSpecific + 632
    frame #10: 0x26d3f012 CoreFoundation`CFRunLoopRunInMode + 106
    frame #11: 0x2e7ca200 GraphicsServices`GSEventRunModal + 136
    frame #12: 0x2a50ba08 UIKit`UIApplicationMain + 1440
    frame #13: 0x000e45e2 ThaliTest`main + 50

```
