#### Test 5319156460e1811_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5319156460e1811/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/6781D7B0-221F-4A29-8156-36892474E096/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/6781D7B0-221F-4A29-8156-36892474E096/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5319156460e1811/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5319156460e1811/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/82551414-A65B-4D64-829E-5F4034D5A24F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52740"
,(lldb)     command script import "/tmp/6781D7B0-221F-4A29-8156-36892474E096/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-10 00:12:39.886 ThaliTest[638:487400] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B18F093C-7EDC-4875-8BC0-AF4FF5EB1C63/Library/Cookies/Cookies.binarycookies
,2015-12-10 00:12:40.257 ThaliTest[638:487400] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 00:12:40.258 ThaliTest[638:487400] Multi-tasking -> Device: YES, App: YES
,2015-12-10 00:12:40.266 ThaliTest[638:487400] Unlimited access to network resources
,2015-12-10 00:12:40.276 ThaliTest[638:487400] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 00:12:49.441 ThaliTest[638:487400] Resetting plugins due to page load.
,2015-12-10 00:12:53.419 ThaliTest[638:487400] Finished load of: file:///var/mobile/Containers/Bundle/Application/82551414-A65B-4D64-829E-5F4034D5A24F/ThaliTest.app/www/index.html
,2015-12-10 00:12:53.625 ThaliTest[638:487400] JXcore Cordova plugin initializing
,2015-12-10 00:12:53.627 ThaliTest[638:487633] JXcore instance initializing
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
,my name is : Apple-Iphone5s-1_PT1537
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
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 53883
,2015-12-10 00:19:37.531 ThaliTest[638:487633] jxcore: startBroadcasting
,2015-12-10 00:19:37.555 ThaliTest[638:487633] server: starting Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:19:37.558 ThaliTest[638:487633] multipeer session: start timer: 0x17de07d0
,2015-12-10 00:19:37.581 ThaliTest[638:487633] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT1537
,2015-12-10 00:19:37.585 ThaliTest[638:487633] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-09T23:19:37.589Z SendDataTCPServer.js: TCP/IP server is bound to port: 53883
,2015-12-10 00:19:38.148 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5811.hStH7w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-09T23:19:38.158Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-09T23:19:38.159Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-09T23:19:38.160Z SendDataConnector.js: do connect now
,2015-12-10 00:19:38.162 ThaliTest[638:487633] jxcore: connect Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:19:38.162 ThaliTest[638:487633] client session: connect
2015-12-10 00:19:38.163 ThaliTest[638:487633] client session: stateChange:0->1 Apple-Iphon,e6-1_PT5811.hStH7w==
,2015-12-10 00:19:39.178 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6044.nbqPWA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-10 00:19:41.175 ThaliTest[638:487400] multipeer session: reset timer
2015-12-10 00:19:41.175 ThaliTest[638:487400] multipeer session: stop timer
2015-12-10 00:19:41.176 ThaliTest[638:487400] multipeer session: start timer: 0x17de07d0
2015-12-10 ,00:19:41.176 ThaliTest[638:487400] server session: connect
2015-12-10 00:19:41.176 ThaliTest[638:487400] server session: stateChange:0->1 Apple-Iphone6-1_PT5811
,2015-12-10 00:19:41.188 ThaliTest[638:487400] server: accepting invitation Apple-Iphone6-1_PT5811
,2015-12-10 00:19:41.971 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9815.s7QXZQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-10 00:19:42.368 ThaliTest[638:488519] client session: connected
2015-12-10 00:19:42.369 ThaliTest[638:488519] client session: stateChange:1->2 Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:19:42.376 ThaliTest[638:488519] client session: fireConnectCallback: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:19:42.377 ThaliTest[638:488519] jxcore: connect: success
2015-12-09T23:19:42.379Z SendDataConnector.js: CLIENT connected to 5,3886, error: null
2015-12-09T23:19:42.379Z SendDataConnector.js: CLIENT starting client 
,2015-12-10 00:19:42.384 ThaliTest[638:487400] client: relay established
2015-12-10 00:19:42.384 ThaliTest[638:487400] client: new accepted socket: 0x17df26a0
,2015-12-09T23:19:42.400Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-09T23:19:42.784Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-09T23:19:42.810Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-09T23:19:42.823Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-09T23:19:42.836Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-09T23:19:42.836Z SendDataConnector.js: got all data for this round
,2015-12-09T23:19:42.838Z SendDataConnector.js: CLIENT Stop now
2015-12-09T23:19:42.838Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-10 00:19:42.839 ThaliTest[638:487633] jxcore: disconnect
2015-12-10 00:19:42.839 ThaliTest[638:487633] client session: disconnectFromPeer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:19:42.839 ThaliTest[638:487633] client session: disconnect
2015-12-10 00:19:42.840 ThaliTest[638:487633] client session: stateChange:2->0 Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:19:42.852 ThaliTest[638:487633] jxcore: disconnect: success
,2015-12-09T23:19:42.858Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT5811.hStH7w==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-09T23:19:42.862Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-09T23:19:42.863Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-09T23:19:42.865Z SendDataConnector.js: do connect now
,2015-12-10 00:19:42.865 ThaliTest[638:487633] jxcore: connect Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-10 00:19:42.867 ThaliTest[638:487633] client session: connect
,2015-12-10 00:19:42.868 ThaliTest[638:487633] client session: stateChange:0->1 Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-10 00:19:44.496 ThaliTest[638:488509] server session: connected
2015-12-10 00:19:44.496 ThaliTest[638:488509] server session: stateChange:1->2 Apple-Iphone6-1_PT5811
,2015-12-10 00:19:44.515 ThaliTest[638:487400] server relay: connected (to port: 53883)
,2015-12-09T23:19:44.526Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09T23:19:44.856Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-09T23:19:44.872Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-09T23:19:44.928Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-09T23:19:44.951Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-09T23:19:44.983Z SendDataTCPServer.js: TCP/IP server has received 76508 bytes of data
,2015-12-09T23:19:45.005Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-10 00:19:46.164 ThaliTest[638:488519] client session: connected
,2015-12-10 00:19:46.165 ThaliTest[638:488519] client session: stateChange:1->2 Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-10 00:19:46.426 ThaliTest[638:488508] client session: fireConnectCallback: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:19:46.426 ThaliTest[638:488508] jxcore: connect: success
2015-12-09T23:19:46.427Z SendDataConnector.js: CLIENT connected to ,53890, error: null
2015-12-09T23:19:46.428Z SendDataConnector.js: CLIENT starting client 
,2015-12-10 00:19:46.433 ThaliTest[638:487400] client: relay established
2015-12-10 00:19:46.433 ThaliTest[638:487400] client: new accepted socket: 0x17d0fd20
,2015-12-09T23:19:46.446Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-09T23:19:47.018Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-09T23:19:47.042Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-09T23:19:47.042Z SendDataConnector.js: got all data for this round
,2015-12-09T23:19:47.043Z SendDataConnector.js: CLIENT Stop now
,2015-12-09T23:19:47.044Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-10 00:19:47.045 ThaliTest[638:487633] jxcore: disconnect
,2015-12-10 00:19:47.046 ThaliTest[638:487633] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-10 00:19:47.047 ThaliTest[638:487633] client session: disconnect
,2015-12-10 00:19:47.048 ThaliTest[638:487633] client session: stateChange:2->0 Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-10 00:19:47.124 ThaliTest[638:487633] jxcore: disconnect: success
,2015-12-09T23:19:47.125Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6044.nbqPWA==
,---- round done--------
,device[3]: Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-09T23:19:47.128Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-09T23:19:47.129Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-09T23:19:47.129Z SendDataConnector.js: do connect now
,2015-12-10 00:19:47.130 ThaliTest[638:487633] jxcore: connect Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-10 00:19:47.131 ThaliTest[638:487633] client session: connect
,2015-12-10 00:19:47.132 ThaliTest[638:487633] client session: stateChange:0->1 Apple-Iphone5-1_PT9815.s7QXZQ==
,appEnteredForeground wasn't registered
,2015-12-10 00:19:56.055 ThaliTest[638:488509] server session: not connected Apple-Iphone6-1_PT5811
,2015-12-10 00:19:59.075 ThaliTest[638:488509] client session: connected
2015-12-10 00:19:59.076 ThaliTest[638:488509] client session: stateChange:1->2 Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-10 00:19:59.126 ThaliTest[638:488519] client session: fireConnectCallback: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:19:59.126 ThaliTest[638:488519] jxcore: connect: success
2015-12-09T23:19:59.128Z SendDataConnector.js: CLIENT connected to 53896, error: null
2015-12-09T23:19:59.128Z SendDataConnector.js: CLIENT starting client 
,2015-12-10 00:19:59.134 ThaliTest[638:487400] client: relay established
2015-12-10 00:19:59.135 ThaliTest[638:487400] client: new accepted socket: 0x17bd3580
,2015-12-09T23:19:59.147Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-09T23:19:59.592Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-09T23:19:59.592Z SendDataConnector.js: got all data for this round
,2015-12-09T23:19:59.593Z SendDataConnector.js: CLIENT Stop now
2015-12-09T23:19:59.593Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-10 00:19:59.593 ThaliTest[638:487633] jxcore: disconnect
2015-12-10 00:19:59.594 ThaliTest[638:487633] client session: disconnectFromPeer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:19:59.594 ThaliTest[638:487633] client session: disconnect
2,015-12-10 00:19:59.594 ThaliTest[638:487633] client session: stateChange:2->0 Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-10 00:19:59.601 ThaliTest[638:487633] jxcore: disconnect: success
2015-12-09T23:19:59.601Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9815.s7QXZQ==
,---- round done--------
weAreDoneNow , resultArray.length: 3
done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT1537","time":22096,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT5811.hStH7w==","time":4678,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT6044.nbqPWA==","time":4180,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT9815.s7QXZQ==","time":12463,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100,000}]}
sendList : 100% : 12463 ms, 99% : 12463 ms, 95 : 12463 ms, 90% : 12463 ms.
Result count 3, range 4180 ms to  12463 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-12-09T23:19:59.608Z SendDataConnector.js: CLIENT Stop now
2015-12-09T23:19:59.608Z SendDataConnector.js: CLIENT closeClientSocket
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,2015-12-10 00:20:09.022 ThaliTest[638:487400] multipeer session: reset timer
2015-12-10 00:20:09.022 ThaliTest[638:487400] multipeer session: stop timer
2015-12-10 00:20:09.023 ThaliTest[638:487400] multipeer session: start timer: 0x17de07d0
2015-12-10 ,00:20:09.023 ThaliTest[638:487400] server session: connect
2015-12-10 00:20:09.024 ThaliTest[638:487400] server session: stateChange:0->1 Apple-IpadAir2-1_PT6044
,2015-12-10 00:20:09.035 ThaliTest[638:487400] server: accepting invitation Apple-IpadAir2-1_PT6044
,2015-12-10 00:20:11.656 ThaliTest[638:488509] server session: connected
2015-12-10 00:20:11.656 ThaliTest[638:488509] server session: stateChange:1->2 Apple-IpadAir2-1_PT6044
,2015-12-09T23:20:12.100Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-10 00:20:12.106 ThaliTest[638:487400] server relay: connected (to port: 53883)
,2015-12-09T23:20:12.121Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-09T23:20:12.138Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-09T23:20:12.155Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-09T23:20:12.184Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-09T23:20:12.198Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-09T23:20:12.624Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-10 00:20:12.763 ThaliTest[638:488775] server session: not connected Apple-IpadAir2-1_PT6044
,2015-12-10 00:20:39.024 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:21:09.024 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:21:09.076 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:21:09.077 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:21:09.401 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:21:14.547 ThaliTest[638:487400] multipeer session: reset timer
2015-12-10 00:21:14.547 ThaliTest[638:487400] multipeer session: stop timer
2015-12-10 00:21:14.548 ThaliTest[638:487400] multipeer session: start timer: 0x17de07d0
2015-12-10 ,00:21:14.548 ThaliTest[638:487400] server session: connect
,2015-12-10 00:21:14.549 ThaliTest[638:487400] server session: stateChange:0->1 Apple-Iphone5-1_PT9815
,2015-12-10 00:21:14.561 ThaliTest[638:487400] server: accepting invitation Apple-Iphone5-1_PT9815
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:21:17.274 ThaliTest[638:488987] server session: connected
2015-12-10 00:21:17.276 ThaliTest[638:488987] server session: stateChange:1->2 Apple-Iphone5-1_PT9815
,2015-12-10 00:21:17.284 ThaliTest[638:487400] server relay: connected (to port: 53883)
,2015-12-09T23:21:17.294Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09T23:21:17.978Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-09T23:21:19.402Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-09T23:21:19.797Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-09T23:21:19.949Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-10 00:21:20.487 ThaliTest[638:488986] server session: not connected Apple-Iphone5-1_PT9815
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
,2015-12-10 00:21:44.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:21:44.597 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:21:44.604 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-10 00:21:46.534 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:22:14.549 ThaliTest[638:487400] multipeer session: restart
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
,2015-12-10 00:22:44.548 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:22:44.600 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:22:44.601 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:22:44.602 ThaliTest[638:487400] client: foun,d peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:23:14.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:23:14.604 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:23:14.604 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:23:17.828 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-10 00:23:44.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:23:44.598 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:23:44.599 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:23:44.601 ThaliTest[638:487400] client: fou,nd peer: Apple-Iphone5-1_PT9815.s7QXZQ==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:24:14.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:24:14.605 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:24:14.606 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:24:14.607 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
,2015-12-10 00:24:44.549 ThaliTest[638:487400] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:25:14.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:25:14.604 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:25:14.605 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:25:14.606 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
,2015-12-10 00:25:44.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:25:44.602 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:25:44.603 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:25:44.603 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:26:14.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:26:14.602 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:26:14.603 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:26:14.604 ThaliTest[638:487400] client: fou,nd peer: Apple-Iphone5-1_PT9815.s7QXZQ==
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
,2015-12-10 00:26:44.549 ThaliTest[638:487400] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:27:14.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:27:14.601 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:27:14.602 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:27:14.602 ThaliTest[638:487400] client: fou,nd peer: Apple-Iphone6-1_PT5811.hStH7w==
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
,2015-12-10 00:27:44.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:27:44.607 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:27:44.608 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-10 00:27:44.609 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:28:14.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:28:14.604 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:28:14.605 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:28:14.605 ThaliTest[638:487400] client: fou,nd peer: Apple-Iphone6-1_PT5811.hStH7w==
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
,2015-12-10 00:28:44.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:28:44.603 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:28:44.603 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:28:44.604 ThaliTest[638:487400] client: fou,nd peer: Apple-Iphone5-1_PT9815.s7QXZQ==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:29:14.549 ThaliTest[638:487400] multipeer session: restart
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
,2015-12-10 00:29:44.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:29:44.596 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:29:44.602 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:29:44.608 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:30:14.549 ThaliTest[638:487400] multipeer session: restart
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
,2015-12-10 00:30:44.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:30:44.602 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:30:44.606 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:30:44.611 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:31:14.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:31:14.601 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:31:14.601 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:31:14.602 ThaliTest[638:487400] client: foun,d peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
,2015-12-10 00:31:44.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:31:44.750 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:31:44.751 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:31:44.751 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:32:14.549 ThaliTest[638:487400] multipeer session: restart
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
,2015-12-10 00:32:44.548 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:32:44.592 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:32:44.593 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:32:44.593 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:33:14.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:33:14.621 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:33:14.622 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:33:14.622 ThaliTest[638:487400] client: fou,nd peer: Apple-Iphone5-1_PT9815.s7QXZQ==
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
,2015-12-10 00:33:44.549 ThaliTest[638:487400] multipeer session: restart
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
,2015-12-10 00:34:14.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:34:14.602 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:34:14.602 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:34:14.603 ThaliTest[638:487400] client: fou,nd peer: Apple-Iphone5-1_PT9815.s7QXZQ==
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
,2015-12-10 00:34:44.548 ThaliTest[638:487400] multipeer session: restart
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
,2015-12-10 00:35:14.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:35:14.598 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:35:14.599 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-10 00:35:14.608 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
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
,2015-12-10 00:35:44.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:35:44.600 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:35:44.601 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:35:44.601 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
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
,2015-12-10 00:36:14.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:36:14.606 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:36:14.606 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:36:14.607 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
,2015-12-10 00:36:44.549 ThaliTest[638:487400] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
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
,2015-12-10 00:37:14.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:37:14.603 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:37:14.604 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:37:14.605 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:37:44.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:37:44.602 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:37:44.603 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:37:44.603 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
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
,2015-12-10 00:38:14.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:38:14.607 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:38:14.608 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:38:14.608 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
,2015-12-10 00:38:44.549 ThaliTest[638:487400] multipeer session: restart
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
,2015-12-10 00:39:14.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:39:14.608 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:39:14.609 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:39:14.609 ThaliTest[638:487400] client: fou,nd peer: Apple-Iphone5-1_PT9815.s7QXZQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:39:44.549 ThaliTest[638:487400] multipeer session: restart
,2015-12-10 00:39:44.615 ThaliTest[638:487400] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:39:44.616 ThaliTest[638:487400] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:39:44.616 ThaliTest[638:487400] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server

```
