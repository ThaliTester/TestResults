#### Test 51790364a0f6051_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51790364a0f6051/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A5C71D5F-11EA-4D92-82EB-78A7E254CD78/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A5C71D5F-11EA-4D92-82EB-78A7E254CD78/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51790364a0f6051/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51790364a0f6051/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DC115FD4-4594-4F34-9D2A-C90FF715B845/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56141"
,(lldb)     command script import "/tmp/A5C71D5F-11EA-4D92-82EB-78A7E254CD78/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-26 07:48:31.151 ThaliTest[1756:1385349] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BC38BED4-2FE4-4C22-8C75-E0A5D1DBD8F7/Library/Cookies/Cookies.binarycookies
,2015-11-26 07:48:31.554 ThaliTest[1756:1385349] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-26 07:48:31.555 ThaliTest[1756:1385349] Multi-tasking -> Device: YES, App: YES
,2015-11-26 07:48:31.563 ThaliTest[1756:1385349] Unlimited access to network resources
,2015-11-26 07:48:31.569 ThaliTest[1756:1385349] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-26 07:48:35.161 ThaliTest[1756:1385349] Resetting plugins due to page load.
,2015-11-26 07:48:35.502 ThaliTest[1756:1385349] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/DC115FD4-4594-4F34-9D2A-C90FF715B845/ThaliTest.app/www/index.html
,2015-11-26 07:48:35.630 ThaliTest[1756:1385349] JXcore Cordova plugin initializing
2015-11-26 07:48:35.631 ThaliTest[1756:1385474] JXcore instance initializing
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
,my name is : Apple-Iphone6-1_PT8881
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
serverPort is 62189
,2015-11-26 07:55:08.471 ThaliTest[1756:1385474] jxcore: startBroadcasting
,2015-11-26 07:55:08.483 ThaliTest[1756:1385474] server: starting Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:55:08.484 ThaliTest[1756:1385474] multipeer session: start timer: 0x1ae036f0
,2015-11-26 07:55:08.486 ThaliTest[1756:1385474] THEMultipeerSession initialized peer Apple-Iphone6-1_PT8881
2015-11-26 07:55:08.487 ThaliTest[1756:1385474] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-26T06:55:08.488Z SendData,TCPServer.js: TCP/IP server is bound to port: 62189
,2015-11-26 07:55:08.677 ThaliTest[1756:1385349] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2617.KcJttQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT2617.KcJttQ==
2015-11-26T06:55:08.679Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2617.KcJttQ==
2015-11-26T06:55:08.680Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2617.KcJttQ==
2015-11-26T06:55:08.680Z SendDataConnector.js: do connect now
2015-11-26 07:55:08.680 ThaliTest[1756:1385474] jxcore: connect Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 07:55:08.680 ThaliTest[1756:1385474] client session: connect
2015-11-26 07:55:08.681 ThaliTest[1756:1385474] client session: stateChange:0->1 Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 07:55:08.739 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6002.+4nCyw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-26 07:55:08.883 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5s-1_PT6114.M0DCbA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6114.M0DCbA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-26 07:55:11.153 ThaliTest[1756:1386020] client session: connected
,2015-11-26 07:55:11.156 ThaliTest[1756:1386020] client session: stateChange:1->2 Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 07:55:11.162 ThaliTest[1756:1386020] client session: fireConnectCallback: Apple-IpadAir2-1_PT2617.KcJttQ==
2015-11-26 07:55:11.163 ThaliTest[1756:1386020] jxcore: connect: success
,2015-11-26T06:55:11.164Z SendDataConnector.js: CLIENT connected to 62192, error: null
,2015-11-26T06:55:11.165Z SendDataConnector.js: CLIENT starting client 
,2015-11-26 07:55:11.168 ThaliTest[1756:1385349] client: relay established
2015-11-26 07:55:11.169 ThaliTest[1756:1385349] client: new accepted socket: 0x1ae01500
,2015-11-26T06:55:11.183Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-26T06:55:11.530Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-26T06:55:11.530Z SendDataConnector.js: got all data for this round
,2015-11-26T06:55:11.531Z SendDataConnector.js: CLIENT Stop now
2015-11-26T06:55:11.531Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26 07:55:11.532 ThaliTest[1756:1385474] jxcore: disconnect
,2015-11-26 07:55:11.533 ThaliTest[1756:1385474] client session: disconnectFromPeer: Apple-IpadAir2-1_PT2617.KcJttQ==
2015-11-26 07:55:11.533 ThaliTest[1756:1385474] client session: disconnect
2015-11-26 07:55:11.533 ThaliTest[1756:1385474] client session,: stateChange:2->0 Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 07:55:11.534 ThaliTest[1756:1385474] jxcore: disconnect: success
2015-11-26T06:55:11.535Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2617.KcJttQ==
---- round done--------
,device[2]: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26T06:55:11.537Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26T06:55:11.537Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26T06:55:11.537Z SendDataConnector.js: do connect now
,2015-11-26 07:55:11.538 ThaliTest[1756:1385474] jxcore: connect Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:55:11.539 ThaliTest[1756:1385474] client session: connect
2015-11-26 07:55:11.539 ThaliTest[1756:1385474] client session: stateChange:0->1 Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:55:14.831 ThaliTest[1756:1386035] client session: connected
2015-11-26 07:55:14.831 ThaliTest[1756:1386035] client session: stateChange:1->2 Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:55:14.836 ThaliTest[1756:1386019] client session: fireConnectCallback: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:55:14.837 ThaliTest[1756:1386019] jxcore: connect: success
,2015-11-26T06:55:14.838Z SendDataConnector.js: CLIENT connected to 62195, error: null
,2015-11-26T06:55:14.839Z SendDataConnector.js: CLIENT starting client 
,2015-11-26 07:55:14.843 ThaliTest[1756:1385349] client: relay established
2015-11-26 07:55:14.844 ThaliTest[1756:1385349] client: new accepted socket: 0x1aed26a0
,2015-11-26T06:55:14.855Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-26T06:55:15.845Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-26T06:55:15.846Z SendDataConnector.js: got all data for this round
,2015-11-26T06:55:15.847Z SendDataConnector.js: CLIENT Stop now
2015-11-26T06:55:15.848Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26 07:55:15.849 ThaliTest[1756:1385474] jxcore: disconnect
2015-11-26 07:55:15.850 ThaliTest[1756:1385474] client session: disconnectFromPeer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:55:15.850 ThaliTest[1756:1385474] client session: disconn,ect
2015-11-26 07:55:15.851 ThaliTest[1756:1385474] client session: stateChange:2->0 Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:55:15.855 ThaliTest[1756:1385474] jxcore: disconnect: success
2015-11-26T06:55:15.857Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6002.+4nCyw==
---- round done--------
,device[3]: Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26T06:55:15.861Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26T06:55:15.861Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6114.M0DCbA==,
2015-11-26T06:55:15.862Z SendDataConnector.js: do connect now
,2015-11-26 07:55:15.862 ThaliTest[1756:1385474] jxcore: connect Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:55:15.863 ThaliTest[1756:1385474] client session: connect
2015-11-26 07:55:15.864 ThaliTest[1756:1385474] client session: stateChange:0->1 Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:55:16.392 ThaliTest[1756:1385349] multipeer session: reset timer
2015-11-26 07:55:16.392 ThaliTest[1756:1385349] multipeer session: stop timer
2015-11-26 07:55:16.393 ThaliTest[1756:1385349] multipeer session: start timer: 0x1ae036f0
2015-,11-26 07:55:16.393 ThaliTest[1756:1385349] server session: connect
2015-11-26 07:55:16.394 ThaliTest[1756:1385349] server session: stateChange:0->1 Apple-Iphone5-1_PT6002
,2015-11-26 07:55:16.405 ThaliTest[1756:1385349] server: accepting invitation Apple-Iphone5-1_PT6002
,2015-11-26 07:55:18.571 ThaliTest[1756:1386020] server session: connected
2015-11-26 07:55:18.572 ThaliTest[1756:1386020] server session: stateChange:1->2 Apple-Iphone5-1_PT6002
,2015-11-26 07:55:18.577 ThaliTest[1756:1385349] server relay: connected (to port: 62189)
,2015-11-26T06:55:18.587Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-26T06:55:19.077Z SendDataTCPServer.js: TCP/IP server has received 2976 bytes of data
,2015-11-26T06:55:19.092Z SendDataTCPServer.js: TCP/IP server has received 13888 bytes of data
,2015-11-26T06:55:19.108Z SendDataTCPServer.js: TCP/IP server has received 30752 bytes of data
,2015-11-26T06:55:19.123Z SendDataTCPServer.js: TCP/IP server has received 45632 bytes of data
,2015-11-26T06:55:19.138Z SendDataTCPServer.js: TCP/IP server has received 56544 bytes of data
,2015-11-26T06:55:19.152Z SendDataTCPServer.js: TCP/IP server has received 67456 bytes of data
,2015-11-26T06:55:19.165Z SendDataTCPServer.js: TCP/IP server has received 76384 bytes of data
,2015-11-26T06:55:19.176Z SendDataTCPServer.js: TCP/IP server has received 85312 bytes of data
,2015-11-26T06:55:19.189Z SendDataTCPServer.js: TCP/IP server has received 95232 bytes of data
,2015-11-26T06:55:19.202Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-26 07:55:19.517 ThaliTest[1756:1386035] client session: connected
2015-11-26 07:55:19.518 ThaliTest[1756:1386035] client session: stateChange:1->2 Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:55:19.526 ThaliTest[1756:1386016] client session: fireConnectCallback: Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:55:19.527 ThaliTest[1756:1386016] jxcore: connect: success
2015-11-26T06:55:19.528Z SendDataConnector.js: CLIENT connected, to 62200, error: null
,2015-11-26T06:55:19.528Z SendDataConnector.js: CLIENT starting client 
,2015-11-26 07:55:19.532 ThaliTest[1756:1385349] client: relay established
2015-11-26 07:55:19.532 ThaliTest[1756:1385349] client: new accepted socket: 0x1ab92350
,2015-11-26T06:55:19.544Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-26T06:55:20.046Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-26T06:55:20.059Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-26T06:55:20.059Z SendDataConnector.js: got all data for this round
,2015-11-26T06:55:20.060Z SendDataConnector.js: CLIENT Stop now
2015-11-26T06:55:20.060Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-26 07:55:20.060 ThaliTest[1756:1385474] jxcore: disconnect
2015-11-26 07:55:20.061 ThaliTest[1756:1385474] cli,ent session: disconnectFromPeer: Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:55:20.061 ThaliTest[1756:1385474] client session: disconnect
2015-11-26 07:55:20.061 ThaliTest[1756:1385474] client session: stateChange:2->0 Apple-Iphone5s-1_PT6114.M0DCbA==,
2015-11-26 07:55:20.062 ThaliTest[1756:1385474] jxcore: disconnect: success
,2015-11-26T06:55:20.063Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6114.M0DCbA==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT8881","time":11610,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT2617.KcJttQ==","time":2851,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT6002.+4nCyw==","time":4309,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT6114.M0DCbA==","time":4199,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":1000,00}]}
sendList : 100% : 4309 ms, 99% : 4309 ms, 95 : 4309 ms, 90% : 4309 ms.
Result count 3, range 2851 ms to  4309 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-11-26T06:55:20.069Z SendDataConnector.js: CLIENT Stop now
2015-11-26T06:55:20.069Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26 07:55:29.428 ThaliTest[1756:1386009] server session: not connected Apple-Iphone5-1_PT6002
,2015-11-26 07:55:39.565 ThaliTest[1756:1385349] multipeer session: reset timer
2015-11-26 07:55:39.565 ThaliTest[1756:1385349] multipeer session: stop timer
2015-11-26 07:55:39.566 ThaliTest[1756:1385349] multipeer session: start timer: 0x1ae036f0
2015-,11-26 07:55:39.567 ThaliTest[1756:1385349] server: disconnecting to refresh session (Apple-Iphone5-1_PT6002)
2015-11-26 07:55:39.567 ThaliTest[1756:1385349] server session: disconnect
2015-11-26 07:55:39.568 ThaliTest[1756:1385349] server session: stateC,hange:2->0 Apple-Iphone5-1_PT6002
2015-11-26 07:55:39.576 ThaliTest[1756:1385349] server session: connect
2015-11-26 07:55:39.577 ThaliTest[1756:1385349] server session: stateChange:0->1 Apple-Iphone5-1_PT6002
,2015-11-26T06:55:39.587Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-26 07:55:39.593 ThaliTest[1756:1385349] server: accepting invitation Apple-Iphone5-1_PT6002
,2015-11-26 07:55:42.024 ThaliTest[1756:1386092] server session: connected
2015-11-26 07:55:42.025 ThaliTest[1756:1386092] server session: stateChange:1->2 Apple-Iphone5-1_PT6002
,2015-11-26 07:55:42.029 ThaliTest[1756:1385349] server relay: connected (to port: 62189)
,2015-11-26T06:55:42.039Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-26T06:55:42.177Z SendDataTCPServer.js: TCP/IP server has received 5952 bytes of data
,2015-11-26T06:55:42.189Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-26 07:55:52.129 ThaliTest[1756:1386093] server session: not connected Apple-Iphone5-1_PT6002
,2015-11-26 07:56:02.457 ThaliTest[1756:1385349] multipeer session: reset timer
2015-11-26 07:56:02.458 ThaliTest[1756:1385349] multipeer session: stop timer
2015-11-26 07:56:02.459 ThaliTest[1756:1385349] multipeer session: start timer: 0x1ae036f0
2015-,11-26 07:56:02.459 ThaliTest[1756:1385349] server: disconnecting to refresh session (Apple-Iphone5-1_PT6002)
2015-11-26 07:56:02.460 ThaliTest[1756:1385349] server session: disconnect
2015-11-26 07:56:02.460 ThaliTest[1756:1385349] server session: stateC,hange:2->0 Apple-Iphone5-1_PT6002
2015-11-26T06:56:02.464Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-26 07:56:02.525 ThaliTest[1756:1385349] server session: connect
2015-11-26 07:56:02.525 ThaliTest[1756:1385349] server session: stateChange:0->1 Apple-Iphone5-1_PT6002
,2015-11-26 07:56:02.531 ThaliTest[1756:1385349] server: accepting invitation Apple-Iphone5-1_PT6002
,2015-11-26 07:56:03.640 ThaliTest[1756:1385349] client: lost peer: Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:56:03.641 ThaliTest[1756:1385349] client session: onPeerLost: Apple-Iphone5s-1_PT6114.M0DCbA==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT6114.M0DCbA==","peerName":"(null)","peerAvailable":false}]
,2015-11-26 07:56:04.748 ThaliTest[1756:1386097] server session: connected
2015-11-26 07:56:04.749 ThaliTest[1756:1386097] server session: stateChange:1->2 Apple-Iphone5-1_PT6002
,2015-11-26 07:56:04.753 ThaliTest[1756:1385349] server relay: connected (to port: 62189)
2015-11-26T06:56:04.756Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-26T06:56:05.067Z SendDataTCPServer.js: TCP/IP server has received 2976 bytes of data
,2015-11-26T06:56:05.081Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-26 07:56:06.112 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5s-1_PT6114.M0DCbA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6114.M0DCbA==","peerName":"(null)","peerAvailable":true}]
,2015-11-26 07:56:15.022 ThaliTest[1756:1386093] server session: not connected Apple-Iphone5-1_PT6002
,2015-11-26 07:56:25.168 ThaliTest[1756:1385349] multipeer session: reset timer
2015-11-26 07:56:25.169 ThaliTest[1756:1385349] multipeer session: stop timer
2015-11-26 07:56:25.169 ThaliTest[1756:1385349] multipeer session: start timer: 0x1ae036f0
2015-,11-26 07:56:25.170 ThaliTest[1756:1385349] server: disconnecting to refresh session (Apple-Iphone5-1_PT6002)
2015-11-26 07:56:25.170 ThaliTest[1756:1385349] server session: disconnect
2015-11-26 07:56:25.171 ThaliTest[1756:1385349] server session: stateC,hange:2->0 Apple-Iphone5-1_PT6002
2015-11-26 07:56:25.173 ThaliTest[1756:1385349] server session: connect
2015-11-26 07:56:25.175 ThaliTest[1756:1385349] server session: stateChange:0->1 Apple-Iphone5-1_PT6002
,2015-11-26T06:56:25.186Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-26 07:56:25.191 ThaliTest[1756:1385349] server: accepting invitation Apple-Iphone5-1_PT6002
,2015-11-26 07:56:27.614 ThaliTest[1756:1386181] server session: connected
2015-11-26 07:56:27.614 ThaliTest[1756:1386181] server session: stateChange:1->2 Apple-Iphone5-1_PT6002
,2015-11-26 07:56:27.620 ThaliTest[1756:1385349] server relay: connected (to port: 62189)
,2015-11-26T06:56:27.631Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-26T06:56:27.780Z SendDataTCPServer.js: TCP/IP server has received 4960 bytes of data
,2015-11-26T06:56:27.794Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-26 07:56:37.724 ThaliTest[1756:1386143] server session: not connected Apple-Iphone5-1_PT6002
,2015-11-26 07:56:48.059 ThaliTest[1756:1385349] multipeer session: reset timer
2015-11-26 07:56:48.060 ThaliTest[1756:1385349] multipeer session: stop timer
2015-11-26 07:56:48.060 ThaliTest[1756:1385349] multipeer session: start timer: 0x1ae036f0
2015-,11-26 07:56:48.061 ThaliTest[1756:1385349] server: disconnecting to refresh session (Apple-Iphone5-1_PT6002)
2015-11-26 07:56:48.062 ThaliTest[1756:1385349] server session: disconnect
2015-11-26 07:56:48.062 ThaliTest[1756:1385349] server session: stateC,hange:2->0 Apple-Iphone5-1_PT6002
2015-11-26 07:56:48.065 ThaliTest[1756:1385349] server session: connect
2015-11-26 07:56:48.066 ThaliTest[1756:1385349] server session: stateChange:0->1 Apple-Iphone5-1_PT6002
2015-11-26T06:56:48.070Z SendDataTCPServer.,js: TCP/IP server is ended
,2015-11-26 07:56:48.082 ThaliTest[1756:1385349] server: accepting invitation Apple-Iphone5-1_PT6002
,2015-11-26 07:56:51.202 ThaliTest[1756:1386223] server session: connected
,2015-11-26 07:56:51.203 ThaliTest[1756:1386223] server session: stateChange:1->2 Apple-Iphone5-1_PT6002
,2015-11-26 07:56:51.208 ThaliTest[1756:1385349] server relay: connected (to port: 62189)
2015-11-26T06:56:51.210Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-26T06:56:51.371Z SendDataTCPServer.js: TCP/IP server has received 4960 bytes of data
,2015-11-26T06:56:51.385Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-26 07:57:01.296 ThaliTest[1756:1386222] server session: not connected Apple-Iphone5-1_PT6002
,2015-11-26 07:57:11.792 ThaliTest[1756:1385349] client: lost peer: Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:57:11.793 ThaliTest[1756:1385349] client session: onPeerLost: Apple-Iphone5s-1_PT6114.M0DCbA==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT6114.M0DCbA==","peerName":"(null)","peerAvailable":false}]
,2015-11-26 07:57:18.062 ThaliTest[1756:1385349] multipeer session: restart
,2015-11-26 07:57:18.080 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:57:18.081 ThaliTest[1756:1385349] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 07:57:48.060 ThaliTest[1756:1385349] multipeer session: restart
,2015-11-26 07:57:48.075 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:57:48.076 ThaliTest[1756:1385349] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 07:58:03.189 ThaliTest[1756:1385349] multipeer session: reset timer
2015-11-26 07:58:03.189 ThaliTest[1756:1385349] multipeer session: stop timer
2015-11-26 07:58:03.190 ThaliTest[1756:1385349] multipeer session: start timer: 0x1ae036f0
2015-,11-26 07:58:03.190 ThaliTest[1756:1385349] server session: connect
2015-11-26 07:58:03.190 ThaliTest[1756:1385349] server session: stateChange:0->1 Apple-IpadAir2-1_PT2617
,2015-11-26 07:58:03.192 ThaliTest[1756:1385349] server: accepting invitation Apple-IpadAir2-1_PT2617
,2015-11-26 07:58:06.215 ThaliTest[1756:1386359] server session: connected
,2015-11-26 07:58:06.217 ThaliTest[1756:1386359] server session: stateChange:1->2 Apple-IpadAir2-1_PT2617
,2015-11-26 07:58:06.222 ThaliTest[1756:1385349] server relay: connected (to port: 62189)
,2015-11-26T06:58:06.227Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-26T06:58:06.674Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-11-26T06:58:06.688Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-11-26T06:58:06.705Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-11-26T06:58:06.720Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-26 07:58:06.748 ThaliTest[1756:1386350] server session: not connected Apple-IpadAir2-1_PT2617
,2015-11-26 07:58:33.191 ThaliTest[1756:1385349] multipeer session: restart
,2015-11-26 07:58:33.207 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:58:33.209 ThaliTest[1756:1385349] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 07:59:03.191 ThaliTest[1756:1385349] multipeer session: restart
,2015-11-26 07:59:03.207 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:59:03.209 ThaliTest[1756:1385349] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 07:59:33.191 ThaliTest[1756:1385349] multipeer session: restart
,2015-11-26 07:59:33.204 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:59:33.206 ThaliTest[1756:1385349] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:00:03.191 ThaliTest[1756:1385349] multipeer session: restart
,2015-11-26 08:00:03.205 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 08:00:03.208 ThaliTest[1756:1385349] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:00:33.189 ThaliTest[1756:1385349] multipeer session: restart
,2015-11-26 08:00:33.203 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 08:00:33.204 ThaliTest[1756:1385349] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:01:03.189 ThaliTest[1756:1385349] multipeer session: restart
,2015-11-26 08:01:03.203 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:01:03.205 ThaliTest[1756:1385349] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:01:33.189 ThaliTest[1756:1385349] multipeer session: restart
,2015-11-26 08:01:33.204 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 08:01:33.205 ThaliTest[1756:1385349] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:02:03.188 ThaliTest[1756:1385349] multipeer session: restart
,2015-11-26 08:02:03.205 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 08:02:03.208 ThaliTest[1756:1385349] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:02:33.189 ThaliTest[1756:1385349] multipeer session: restart
,2015-11-26 08:02:33.205 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 08:02:33.206 ThaliTest[1756:1385349] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:03:03.189 ThaliTest[1756:1385349] multipeer session: restart
,2015-11-26 08:03:03.205 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 08:03:03.207 ThaliTest[1756:1385349] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:03:33.186 ThaliTest[1756:1385349] multipeer session: restart
,2015-11-26 08:03:33.204 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 08:03:33.206 ThaliTest[1756:1385349] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:04:03.186 ThaliTest[1756:1385349] multipeer session: restart
,2015-11-26 08:04:03.203 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 08:04:03.204 ThaliTest[1756:1385349] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:04:33.186 ThaliTest[1756:1385349] multipeer session: restart
,2015-11-26 08:04:33.202 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 08:04:33.205 ThaliTest[1756:1385349] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:05:03.186 ThaliTest[1756:1385349] multipeer session: restart
,2015-11-26 08:05:03.200 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 08:05:03.202 ThaliTest[1756:1385349] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:05:33.186 ThaliTest[1756:1385349] multipeer session: restart
,2015-11-26 08:05:33.202 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 08:05:33.205 ThaliTest[1756:1385349] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:06:03.184 ThaliTest[1756:1385349] multipeer session: restart
,2015-11-26 08:06:03.200 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:06:03.203 ThaliTest[1756:1385349] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:06:33.184 ThaliTest[1756:1385349] multipeer session: restart
,2015-11-26 08:06:33.200 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 08:06:33.201 ThaliTest[1756:1385349] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:07:03.184 ThaliTest[1756:1385349] multipeer session: restart
,2015-11-26 08:07:03.200 ThaliTest[1756:1385349] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 08:07:03.202 ThaliTest[1756:1385349] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:07:33.184 ThaliTest[1756:1385349] multipeer session: restart
2015-11-26 08:07:33.190 ThaliTest[1756:1385349] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Fi,rst throw call stack:
(0x26e2efef 0x35798c8b 0x26d4aaa3 0x28e09d85 0x26932607 0x26931e81 0x268ab3d3 0x26df4faf 0x26df43bf 0x26df2a25 0x26d3f201 0x26d3f013 0x2e7ca201 0x2a50ba09 0xb95e3 0x35d4aaaf)
libc++abi.dylib: terminating with uncaught exception of type NSException
,Process 1756 stopped
* thread #1: tid = 0x152385, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x35e14df0 <+8>:  blo    0x35e14e08                ; <+32>
    0x35e14df4 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x35e14df8 <+16>: ldr    r12, [pc, r12]
    0x35e14dfc <+20>: b      0x35e14e04                ; <+28>
,* thread #1: tid = 0x152385, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
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
    frame #13: 0x000b95e2 ThaliTest`main + 50

```
