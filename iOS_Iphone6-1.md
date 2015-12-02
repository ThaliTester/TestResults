#### Test 5227736558f1fb0_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5227736558f1fb0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/68AA9CCE-7800-4D4A-920F-C11CE8DE906E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/68AA9CCE-7800-4D4A-920F-C11CE8DE906E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5227736558f1fb0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5227736558f1fb0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E3926824-8C49-4C36-A298-8F38CBBD3471/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59552"
,(lldb)     command script import "/tmp/68AA9CCE-7800-4D4A-920F-C11CE8DE906E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-02 18:05:59.075 ThaliTest[2450:2100890] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/873F1386-6B33-420F-BF09-A00BCE1FA66D/Library/Cookies/Cookies.binarycookies
,2015-12-02 18:05:59.466 ThaliTest[2450:2100890] Apache Cordova native platform version 3.9.2 is starting.
2015-12-02 18:05:59.467 ThaliTest[2450:2100890] Multi-tasking -> Device: YES, App: YES
,2015-12-02 18:05:59.475 ThaliTest[2450:2100890] Unlimited access to network resources
,2015-12-02 18:05:59.481 ThaliTest[2450:2100890] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-02 18:06:02.974 ThaliTest[2450:2100890] Resetting plugins due to page load.
,2015-12-02 18:06:03.359 ThaliTest[2450:2100890] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/E3926824-8C49-4C36-A298-8F38CBBD3471/ThaliTest.app/www/index.html
,2015-12-02 18:06:03.486 ThaliTest[2450:2100890] JXcore Cordova plugin initializing
,2015-12-02 18:06:03.488 ThaliTest[2450:2101017] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Radios toggled
,my name is : Apple-Iphone6-1_PT5992
,attempting to connect to test coordinator
check test folder
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
,serverPort is 65119
,2015-12-02 18:12:37.773 ThaliTest[2450:2101017] jxcore: startBroadcasting
,2015-12-02 18:12:37.785 ThaliTest[2450:2101017] server: starting Apple-Iphone6-1_PT5992.nsQaaA==
,2015-12-02 18:12:37.786 ThaliTest[2450:2101017] multipeer session: start timer: 0x19d612f0
,2015-12-02 18:12:37.787 ThaliTest[2450:2101017] THEMultipeerSession initialized peer Apple-Iphone6-1_PT5992
2015-12-02 18:12:37.788 ThaliTest[2450:2101017] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-02T17:12:37.789Z SendDataTCPServer.js: TCP/IP server is bound to port: 65119
,2015-12-02 18:12:38.235 ThaliTest[2450:2100890] multipeer session: reset timer
2015-12-02 18:12:38.236 ThaliTest[2450:2100890] multipeer session: stop timer
2015-12-02 18:12:38.236 ThaliTest[2450:2100890] multipeer session: start timer: 0x19d612f0
,2015-12-02 18:12:38.236 ThaliTest[2450:2100890] server session: connect
2015-12-02 18:12:38.237 ThaliTest[2450:2100890] server session: stateChange:0->1 Apple-Iphone5-1_PT9787
,2015-12-02 18:12:38.241 ThaliTest[2450:2100890] server: accepting invitation Apple-Iphone5-1_PT9787
,2015-12-02 18:12:38.480 ThaliTest[2450:2100890] multipeer session: reset timer
2015-12-02 18:12:38.481 ThaliTest[2450:2100890] multipeer session: stop timer
2015-12-02 18:12:38.482 ThaliTest[2450:2100890] multipeer session: start timer: 0x19d612f0
2015-,12-02 18:12:38.482 ThaliTest[2450:2100890] server session: connect
2015-12-02 18:12:38.483 ThaliTest[2450:2100890] server session: stateChange:0->1 Apple-IpadAir2-1_PT2754
,2015-12-02 18:12:38.493 ThaliTest[2450:2100890] server: accepting invitation Apple-IpadAir2-1_PT2754
,2015-12-02 18:12:38.861 ThaliTest[2450:2100890] client: found peer: Apple-Iphone5-1_PT9787.rFc5Bg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9787.rFc5Bg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5-1_PT9787.rFc5Bg==
2015-12-02T17:12:38.867Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9787.rFc5Bg==
2015-12-02T17:12:38.868Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9787.rFc5Bg==
20,15-12-02T17:12:38.868Z SendDataConnector.js: do connect now
,2015-12-02 18:12:38.869 ThaliTest[2450:2101017] jxcore: connect Apple-Iphone5-1_PT9787.rFc5Bg==
,2015-12-02 18:12:38.869 ThaliTest[2450:2101017] client session: connect
,2015-12-02 18:12:38.870 ThaliTest[2450:2101017] client session: stateChange:0->1 Apple-Iphone5-1_PT9787.rFc5Bg==
,2015-12-02 18:12:39.069 ThaliTest[2450:2100890] client: found peer: Apple-IpadAir2-1_PT2754.fr+caQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2754.fr+caQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-02 18:12:40.466 ThaliTest[2450:2101548] server session: connected
2015-12-02 18:12:40.466 ThaliTest[2450:2101548] server session: stateChange:1->2 Apple-Iphone5-1_PT9787
,2015-12-02 18:12:40.487 ThaliTest[2450:2100890] server relay: connected (to port: 65119)
,2015-12-02T17:12:40.499Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02 18:12:41.083 ThaliTest[2450:2101540] server session: connected
2015-12-02 18:12:41.084 ThaliTest[2450:2101540] server session: stateChange:1->2 Apple-IpadAir2-1_PT2754
,2015-12-02 18:12:41.089 ThaliTest[2450:2100890] server relay: connected (to port: 65119)
,2015-12-02T17:12:41.096Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02 18:12:41.181 ThaliTest[2450:2101548] client session: connected
2015-12-02 18:12:41.182 ThaliTest[2450:2101548] client session: stateChange:1->2 Apple-Iphone5-1_PT9787.rFc5Bg==
,2015-12-02 18:12:41.223 ThaliTest[2450:2101540] client session: fireConnectCallback: Apple-Iphone5-1_PT9787.rFc5Bg==
2015-12-02 18:12:41.224 ThaliTest[2450:2101540] jxcore: connect: success
,2015-12-02T17:12:41.225Z SendDataConnector.js: CLIENT connected to 65124, error: null
,2015-12-02T17:12:41.226Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 18:12:41.230 ThaliTest[2450:2100890] client: relay established
2015-12-02 18:12:41.230 ThaliTest[2450:2100890] client: new accepted socket: 0x19d78f30
,2015-12-02T17:12:41.246Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T17:12:41.533Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02T17:12:41.548Z SendDataTCPServer.js: TCP/IP server has received 3968 bytes of data
,2015-12-02T17:12:41.561Z SendDataTCPServer.js: TCP/IP server has received 11904 bytes of data
,2015-12-02T17:12:41.574Z SendDataTCPServer.js: TCP/IP server has received 26784 bytes of data
,2015-12-02T17:12:41.587Z SendDataTCPServer.js: TCP/IP server has received 51584 bytes of data
,2015-12-02T17:12:41.588Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-02 18:12:41.595 ThaliTest[2450:2101546] server session: not connected Apple-IpadAir2-1_PT2754
,2015-12-02T17:12:41.599Z SendDataTCPServer.js: TCP/IP server has received 62496 bytes of data
2015-12-02T17:12:41.600Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-02T17:12:41.613Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-02T17:12:41.613Z SendDataConnector.js: got all data for this round
,2015-12-02T17:12:41.615Z SendDataConnector.js: CLIENT Stop now
2015-12-02T17:12:41.615Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 18:12:41.615 ThaliTest[2450:2101017] jxcore: disconnect
,2015-12-02 18:12:41.616 ThaliTest[2450:2101017] client session: disconnectFromPeer: Apple-Iphone5-1_PT9787.rFc5Bg==
2015-12-02 18:12:41.616 ThaliTest[2450:2101017] client session: disconnect
2015-12-02 18:12:41.617 ThaliTest[2450:2101017] client session:, stateChange:2->0 Apple-Iphone5-1_PT9787.rFc5Bg==
2015-12-02 18:12:41.621 ThaliTest[2450:2101017] jxcore: disconnect: success
,2015-12-02T17:12:41.623Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9787.rFc5Bg==
---- round done--------
,device[2]: Apple-IpadAir2-1_PT2754.fr+caQ==
2015-12-02T17:12:41.624Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2754.fr+caQ==
2015-12-02T17:12:41.625Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2754.fr+caQ==,
2015-12-02T17:12:41.625Z SendDataConnector.js: do connect now
2015-12-02 18:12:41.625 ThaliTest[2450:2101017] jxcore: connect Apple-IpadAir2-1_PT2754.fr+caQ==
2015-12-02 18:12:41.625 ThaliTest[2450:2101017] client session: connect
2015-12-02 18:12:41.6,25 ThaliTest[2450:2101017] client session: stateChange:0->1 Apple-IpadAir2-1_PT2754.fr+caQ==
,2015-12-02T17:12:41.643Z SendDataTCPServer.js: TCP/IP server has received 91264 bytes of data
,2015-12-02T17:12:41.658Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 18:12:41.758 ThaliTest[2450:2101548] server session: not connected Apple-Iphone5-1_PT9787
,2015-12-02 18:12:41.928 ThaliTest[2450:2100890] client: found peer: Apple-Iphone5s-1_PT367.AiGtHw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT367.AiGtHw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-02 18:12:45.694 ThaliTest[2450:2101561] client session: connected
2015-12-02 18:12:45.695 ThaliTest[2450:2101561] client session: stateChange:1->2 Apple-IpadAir2-1_PT2754.fr+caQ==
2015-12-02 18:12:45.697 ThaliTest[2450:2101561] client session: fi,reConnectCallback: Apple-IpadAir2-1_PT2754.fr+caQ==
2015-12-02 18:12:45.698 ThaliTest[2450:2101561] jxcore: connect: success
2015-12-02T17:12:45.699Z SendDataConnector.js: CLIENT connected to 65127, error: null
2015-12-02T17:12:45.699Z SendDataConnector,.js: CLIENT starting client 
,2015-12-02 18:12:45.703 ThaliTest[2450:2100890] client: relay established
2015-12-02 18:12:45.704 ThaliTest[2450:2100890] client: new accepted socket: 0x19e3f110
,2015-12-02T17:12:45.716Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T17:12:46.164Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-02T17:12:46.201Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-02T17:12:46.215Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-02T17:12:46.215Z SendDataConnector.js: got all data for this round
,2015-12-02T17:12:46.216Z SendDataConnector.js: CLIENT Stop now
,2015-12-02T17:12:46.216Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 18:12:46.217 ThaliTest[2450:2101017] jxcore: disconnect
,2015-12-02 18:12:46.218 ThaliTest[2450:2101017] client session: disconnectFromPeer: Apple-IpadAir2-1_PT2754.fr+caQ==
,2015-12-02 18:12:46.218 ThaliTest[2450:2101017] client session: disconnect
,2015-12-02 18:12:46.219 ThaliTest[2450:2101017] client session: stateChange:2->0 Apple-IpadAir2-1_PT2754.fr+caQ==
,2015-12-02 18:12:46.277 ThaliTest[2450:2101017] jxcore: disconnect: success
2015-12-02T17:12:46.278Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2754.fr+caQ==
,---- round done--------
,device[3]: Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02T17:12:46.278Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02T17:12:46.279Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT367.AiGtHw==
20,15-12-02T17:12:46.279Z SendDataConnector.js: do connect now
,2015-12-02 18:12:46.279 ThaliTest[2450:2101017] jxcore: connect Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02 18:12:46.279 ThaliTest[2450:2101017] client session: connect
,2015-12-02 18:12:46.279 ThaliTest[2450:2101017] client session: stateChange:0->1 Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02 18:12:48.942 ThaliTest[2450:2101561] client session: connected
2015-12-02 18:12:48.943 ThaliTest[2450:2101561] client session: stateChange:1->2 Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02 18:12:48.961 ThaliTest[2450:2101561] client session: fireConnectCallback: Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02 18:12:48.962 ThaliTest[2450:2101561] jxcore: connect: success
2015-12-02T17:12:48.963Z SendDataConnector.js: CLIENT connected ,to 65131, error: null
,2015-12-02T17:12:48.963Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 18:12:48.967 ThaliTest[2450:2100890] client: relay established
2015-12-02 18:12:48.968 ThaliTest[2450:2100890] client: new accepted socket: 0x19d632d0
,2015-12-02T17:12:48.978Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T17:12:49.320Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-02T17:12:49.333Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-02T17:12:49.345Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-02T17:12:49.357Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-02T17:12:49.370Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-02T17:12:49.370Z SendDataConnector.js: got all data for this round
,2015-12-02T17:12:49.371Z SendDataConnector.js: CLIENT Stop now
,2015-12-02T17:12:49.371Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 18:12:49.372 ThaliTest[2450:2101017] jxcore: disconnect
,2015-12-02 18:12:49.373 ThaliTest[2450:2101017] client session: disconnectFromPeer: Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02 18:12:49.373 ThaliTest[2450:2101017] client session: disconnect
,2015-12-02 18:12:49.374 ThaliTest[2450:2101017] client session: stateChange:2->0 Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02 18:12:49.429 ThaliTest[2450:2101017] jxcore: disconnect: success
2015-12-02T17:12:49.429Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT367.AiGtHw==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT5992","time":11673,"result":"OK","sendList":[{"name":"Apple-Iphone5-1_PT9787.rFc5Bg==","time":2747,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_,PT2754.fr+caQ==","time":4590,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT367.AiGtHw==","time":3092,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":10000,0}]}
,sendList : 100% : 4590 ms, 99% : 4590 ms, 95 : 4590 ms, 90% : 4590 ms.
Result count 3, range 2747 ms to  4590 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-02T17:12:49.434Z SendDataConnector.js: CLIENT Stop now
,2015-12-02T17:12:49.434Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 18:12:54.098 ThaliTest[2450:2100890] multipeer session: reset timer
2015-12-02 18:12:54.099 ThaliTest[2450:2100890] multipeer session: stop timer
2015-12-02 18:12:54.099 ThaliTest[2450:2100890] multipeer session: start timer: 0x19d612f0
2015-,12-02 18:12:54.100 ThaliTest[2450:2100890] server session: connect
2015-12-02 18:12:54.100 ThaliTest[2450:2100890] server session: stateChange:0->1 Apple-Iphone5s-1_PT367
,2015-12-02 18:12:54.110 ThaliTest[2450:2100890] server: accepting invitation Apple-Iphone5s-1_PT367
,2015-12-02 18:12:56.668 ThaliTest[2450:2101546] server session: connected
2015-12-02 18:12:56.669 ThaliTest[2450:2101546] server session: stateChange:1->2 Apple-Iphone5s-1_PT367
,2015-12-02 18:12:56.684 ThaliTest[2450:2100890] server relay: connected (to port: 65119)
,2015-12-02T17:12:56.690Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T17:12:56.978Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-02T17:12:56.992Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-02T17:12:57.046Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-02T17:12:57.063Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 18:12:57.093 ThaliTest[2450:2101546] server session: not connected Apple-Iphone5s-1_PT367
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-12-02 18:12:57.621 ThaliTest[2450:2101017] jxcore: stopBroadcasting
,2015-12-02 18:12:57.623 ThaliTest[2450:2101017] THEMultipeerSession stopping peer
,2015-12-02 18:12:57.623 ThaliTest[2450:2101017] multipeer session: stop timer
,2015-12-02 18:12:57.625 ThaliTest[2450:2101017] server session: disconnect
2015-12-02 18:12:57.625 ThaliTest[2450:2101017] server session: stateChange:2->0 Apple-Iphone5-1_PT9787
,2015-12-02 18:12:57.633 ThaliTest[2450:2101017] server session: disconnect
2015-12-02 18:12:57.634 ThaliTest[2450:2101017] server session: stateChange:2->0 Apple-Iphone5s-1_PT367
,2015-12-02 18:12:57.638 ThaliTest[2450:2101017] server session: disconnect
2015-12-02 18:12:57.639 ThaliTest[2450:2101017] server session: stateChange:2->0 Apple-IpadAir2-1_PT2754
,2015-12-02 18:12:57.644 ThaliTest[2450:2101017] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-02T17:12:57.667Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02T17:12:57.669Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02T17:12:57.670Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-02T17:12:57.671Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT9787.rFc5Bg==\",\"time\":2747,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone5s-1_PT367.AiGtHw==\",\"time\":3092,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-IpadAir2-1_PT2754.fr+caQ==\",\"time\":4590,\"result\":\"OK\",\"connections\":1,,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called

```
