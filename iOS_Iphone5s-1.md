#### Test 534296758dfd01f_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/534296758dfd01f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/1D184993-9A8A-475E-9E58-A7AE9213FB0B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/1D184993-9A8A-475E-9E58-A7AE9213FB0B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/534296758dfd01f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/534296758dfd01f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CEBEA437-8F08-488F-BCBA-16E943279903/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54408"
,(lldb)     command script import "/tmp/1D184993-9A8A-475E-9E58-A7AE9213FB0B/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-11 20:05:54.873 ThaliTest[811:753242] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4C300CB4-41D5-4E0F-87D4-4EA55E8A3B12/Library/Cookies/Cookies.binarycookies
,2015-12-11 20:05:55.332 ThaliTest[811:753242] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-11 20:05:55.334 ThaliTest[811:753242] Multi-tasking -> Device: YES, App: YES
,2015-12-11 20:05:55.344 ThaliTest[811:753242] Unlimited access to network resources
,2015-12-11 20:05:55.360 ThaliTest[811:753242] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-11 20:06:05.226 ThaliTest[811:753242] Resetting plugins due to page load.
,2015-12-11 20:06:09.287 ThaliTest[811:753242] Finished load of: file:///var/mobile/Containers/Bundle/Application/CEBEA437-8F08-488F-BCBA-16E943279903/ThaliTest.app/www/index.html
,2015-12-11 20:06:09.510 ThaliTest[811:753242] JXcore Cordova plugin initializing
,2015-12-11 20:06:09.512 ThaliTest[811:753451] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone5s-1_PT5466
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 57045
,2015-12-11 20:12:38.861 ThaliTest[811:753451] jxcore: startBroadcasting
,2015-12-11 20:12:38.884 ThaliTest[811:753451] server: starting Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:12:38.885 ThaliTest[811:753451] multipeer session: start timer: 0x15dd0a20
2015-12-11 20:12:38.886 ThaliTest[811:753451] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT5466
2015-12-11 20:12:38.887 ThaliTest[811:753451] jxcore: star,tBroadcasting: success
StartBroadcasting started ok
,2015-12-11T19:12:38.891Z SendDataTCPServer.js: TCP/IP server is bound to port: 57045
,2015-12-11 20:12:39.697 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT818.I3iT5Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
device[1]: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11T19:12:39.709Z SendDataConnector.js: Start ,called with peer Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11T19:12:39.710Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11T19:12:39.712Z SendDataConnector.js: do connect now
2015-12-11 20:12:39.713 ThaliTest[811:753451] jxcore: connect Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:12:39.714 ThaliTest[811:753451] client session: connect
2015-12-11 20:12:39.714 Tha,liTest[811:753451] client session: stateChange:0->1 Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:12:41.179 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3759.Czrh3A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 20:12:43.501 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4192.mhrLvw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 20:12:43.523 ThaliTest[811:753242] multipeer session: reset timer
2015-12-11 20:12:43.524 ThaliTest[811:753242] multipeer session: stop timer
2015-12-11 20:12:43.524 ThaliTest[811:753242] multipeer session: start timer: 0x15dd0a20
2015-12-11 ,20:12:43.524 ThaliTest[811:753242] server session: connect
2015-12-11 20:12:43.525 ThaliTest[811:753242] server session: stateChange:0->1 Apple-IpadAir2-1_PT818
,2015-12-11 20:12:43.538 ThaliTest[811:753242] server: accepting invitation Apple-IpadAir2-1_PT818
,2015-12-11 20:12:43.866 ThaliTest[811:753242] multipeer session: reset timer
2015-12-11 20:12:43.867 ThaliTest[811:753242] multipeer session: stop timer
2015-12-11 20:12:43.867 ThaliTest[811:753242] multipeer session: start timer: 0x15dd0a20
2015-12-11 ,20:12:43.867 ThaliTest[811:753242] server session: connect
2015-12-11 20:12:43.867 ThaliTest[811:753242] server session: stateChange:0->1 Apple-Iphone6-1_PT3759
,2015-12-11 20:12:43.875 ThaliTest[811:753242] server: accepting invitation Apple-Iphone6-1_PT3759
,2015-12-11 20:12:44.530 ThaliTest[811:754145] client session: connected
2015-12-11 20:12:44.532 ThaliTest[811:754145] client session: stateChange:1->2 Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:12:44.538 ThaliTest[811:754145] client session: fireConnectCallback: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:12:44.538 ThaliTest[811:754145] jxcore: connect: success
,2015-12-11T19:12:44.541Z SendDataConnector.js: CLIENT connected to 57048, error: null
,2015-12-11T19:12:44.541Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 20:12:44.548 ThaliTest[811:753242] client: relay established
,2015-12-11 20:12:44.550 ThaliTest[811:753242] client: new accepted socket: 0x14685460
,2015-12-11T19:12:44.559Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T19:12:44.892Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-11T19:12:44.915Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-11T19:12:44.916Z SendDataConnector.js: got all data for this round
,2015-12-11T19:12:44.917Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T19:12:44.917Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 20:12:44.920 ThaliTest[811:753451] jxcore: disconnect
,2015-12-11 20:12:44.920 ThaliTest[811:753451] client session: disconnectFromPeer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:12:44.921 ThaliTest[811:753451] client session: disconnect
,2015-12-11 20:12:44.922 ThaliTest[811:753451] client session: stateChange:2->0 Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:12:44.998 ThaliTest[811:753451] jxcore: disconnect: success
,2015-12-11T19:12:44.999Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT818.I3iT5Q==
,---- round done--------
,device[2]: Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11T19:12:45.002Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11T19:12:45.002Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11T19:12:45.002Z SendDataConnector.js: do connect now
,2015-12-11 20:12:45.003 ThaliTest[811:753451] jxcore: connect Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:12:45.004 ThaliTest[811:753451] client session: connect
,2015-12-11 20:12:45.005 ThaliTest[811:753451] client session: stateChange:0->1 Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:12:46.629 ThaliTest[811:754137] server session: connected
,2015-12-11 20:12:46.630 ThaliTest[811:754137] server session: stateChange:1->2 Apple-Iphone6-1_PT3759
,2015-12-11 20:12:46.685 ThaliTest[811:753242] server relay: connected (to port: 57045)
,2015-12-11T19:12:46.695Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T19:12:47.020Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-11T19:12:47.035Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-11T19:12:47.056Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-11T19:12:47.075Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
2015-12-11T19:12:47.091Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-11T19:12:47.106Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 20:12:47.145 ThaliTest[811:754147] server session: not connected Apple-Iphone6-1_PT3759
,2015-12-11 20:12:48.174 ThaliTest[811:754147] client session: connected
2015-12-11 20:12:48.174 ThaliTest[811:754147] client session: stateChange:1->2 Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:12:48.186 ThaliTest[811:754147] client session: fireConne,ctCallback: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:12:48.186 ThaliTest[811:754147] jxcore: connect: success
2015-12-11T19:12:48.188Z SendDataConnector.js: CLIENT connected to 57052, error: null
2015-12-11T19:12:48.189Z SendDataConnector.js: CLIEN,T starting client 
,2015-12-11 20:12:48.194 ThaliTest[811:753242] client: relay established
2015-12-11 20:12:48.194 ThaliTest[811:753242] client: new accepted socket: 0x15ddd1d0
,2015-12-11T19:12:48.205Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T19:12:48.539Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-11T19:12:48.639Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-11T19:12:48.654Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-11T19:12:48.654Z SendDataConnector.js: got all data for this round
,2015-12-11T19:12:48.655Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T19:12:48.656Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 20:12:48.657 ThaliTest[811:753451] jxcore: disconnect
,2015-12-11 20:12:48.658 ThaliTest[811:753451] client session: disconnectFromPeer: Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:12:48.659 ThaliTest[811:753451] client session: disconnect
,2015-12-11 20:12:48.660 ThaliTest[811:753451] client session: stateChange:2->0 Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:12:48.733 ThaliTest[811:753451] jxcore: disconnect: success
,2015-12-11T19:12:48.734Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3759.Czrh3A==
,---- round done--------
,device[3]: Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11T19:12:48.736Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11T19:12:48.736Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11T19:12:48.737Z SendDataConnector.js: do connect now
,2015-12-11 20:12:48.737 ThaliTest[811:753451] jxcore: connect Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:12:48.738 ThaliTest[811:753451] client session: connect
,2015-12-11 20:12:48.740 ThaliTest[811:753451] client session: stateChange:0->1 Apple-Iphone5-1_PT4192.mhrLvw==
,appEnteredForeground wasn't registered
,2015-12-11 20:12:52.325 ThaliTest[811:754136] client session: connected
2015-12-11 20:12:52.326 ThaliTest[811:754136] client session: stateChange:1->2 Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:12:52.331 ThaliTest[811:754136] client session: fireConnectCallback: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:12:52.332 ThaliTest[811:754136] jxcore: connect: success
,2015-12-11T19:12:52.333Z SendDataConnector.js: CLIENT connected to 57055, error: null
2015-12-11T19:12:52.334Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 20:12:52.337 ThaliTest[811:753242] client: relay established
2015-12-11 20:12:52.338 ThaliTest[811:753242] client: new accepted socket: 0x1458c900
,2015-12-11T19:12:52.349Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T19:12:52.775Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-11T19:12:52.789Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-11T19:12:52.852Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-11T19:12:52.905Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-11T19:12:52.906Z SendDataConnector.js: got all data for this round
,2015-12-11T19:12:52.908Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T19:12:52.910Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 20:12:52.912 ThaliTest[811:753451] jxcore: disconnect
,2015-12-11 20:12:52.915 ThaliTest[811:753451] client session: disconnectFromPeer: Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:12:52.917 ThaliTest[811:753451] client session: disconnect
,2015-12-11 20:12:52.919 ThaliTest[811:753451] client session: stateChange:2->0 Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:12:53.010 ThaliTest[811:753451] jxcore: disconnect: success
,2015-12-11T19:12:53.012Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT4192.mhrLvw==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT5466","time":14174,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT818.I3iT5Q==","time":5207,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_,PT3759.Czrh3A==","time":3653,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT4192.mhrLvw==","time":4171,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 5207 ms, 99% : 5207 ms, 95 : 5207 ms, 90% : 5207 ms.
,Result count 3, range 3653 ms to  5207 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-11T19:12:53.037Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T19:12:53.038Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 20:12:53.848 ThaliTest[811:754137] server session: not connected Apple-IpadAir2-1_PT818
,2015-12-11 20:13:13.868 ThaliTest[811:753242] multipeer session: restart
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:13:43.868 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:13:43.910 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:13:44.206 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:13:44.223 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
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
,2015-12-11 20:14:13.868 ThaliTest[811:753242] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
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
,2015-12-11 20:14:43.868 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:14:43.917 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:14:43.920 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:14:43.933 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,2015-12-11 20:15:13.868 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:15:13.921 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:15:13.921 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:15:14.240 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
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
,2015-12-11 20:15:40.491 ThaliTest[811:753242] multipeer session: reset timer
2015-12-11 20:15:40.491 ThaliTest[811:753242] multipeer session: stop timer
2015-12-11 20:15:40.492 ThaliTest[811:753242] multipeer session: start timer: 0x15dd0a20
2015-12-11 ,20:15:40.492 ThaliTest[811:753242] server session: connect
2015-12-11 20:15:40.493 ThaliTest[811:753242] server session: stateChange:0->1 Apple-Iphone5-1_PT4192
,2015-12-11 20:15:40.504 ThaliTest[811:753242] server: accepting invitation Apple-Iphone5-1_PT4192
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:15:43.030 ThaliTest[811:754673] server session: connected
,2015-12-11 20:15:43.031 ThaliTest[811:754673] server session: stateChange:1->2 Apple-Iphone5-1_PT4192
,2015-12-11 20:15:43.044 ThaliTest[811:753242] server relay: connected (to port: 57045)
,2015-12-11T19:15:43.054Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T19:15:43.618Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-11T19:15:43.638Z SendDataTCPServer.js: TCP/IP server has received 39136 bytes of data
,2015-12-11T19:15:43.659Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-11T19:15:43.677Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-11T19:15:43.697Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-11T19:15:43.712Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 20:15:43.757 ThaliTest[811:754766] server session: not connected Apple-Iphone5-1_PT4192
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
,2015-12-11 20:16:10.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:16:10.543 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:16:10.544 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:16:15.027 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:16:40.494 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:16:40.545 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:16:40.546 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:16:40.672 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,2015-12-11 20:17:10.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:17:10.566 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:17:10.566 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:17:10.586 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,2015-12-11 20:17:22.551 ThaliTest[811:753242] client: lost peer: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:17:22.551 ThaliTest[811:753242] client session: onPeerLost: Apple-Iphone6-1_PT3759.Czrh3A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3759.Czrh3A==","peerName":"(null)","peerAvailable":false}]
,2015-12-11 20:17:23.564 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3759.Czrh3A==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:17:40.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:17:40.545 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:17:40.546 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:17:40.553 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,2015-12-11 20:18:10.494 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:18:10.571 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:18:10.572 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:18:10.765 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
,appEnteringBackground wasn't registered
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_timeout called
,Error type "connect_timeout" when connecting to the test server
,appEnteredForeground wasn't registered
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:18:40.493 ThaliTest[811:753242] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:18:42.270 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:18:42.271 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:18:42.798 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,2015-12-11 20:19:10.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:19:10.563 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:19:10.565 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:19:11.134 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:19:40.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:19:40.551 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:19:40.551 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:19:40.934 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,2015-12-11 20:20:10.493 ThaliTest[811:753242] multipeer session: restart
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:20:40.494 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:20:40.544 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:20:40.545 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:20:40.734 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,2015-12-11 20:21:10.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:21:10.547 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:21:10.550 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:21:10.599 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:21:40.493 ThaliTest[811:753242] multipeer session: restart
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
,2015-12-11 20:22:10.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:22:10.545 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:22:10.546 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:22:10.877 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:22:40.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:22:40.542 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:22:40.543 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:22:40.748 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,2015-12-11 20:23:10.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:23:10.551 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:23:10.552 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:23:11.264 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:23:40.493 ThaliTest[811:753242] multipeer session: restart
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
,2015-12-11 20:24:10.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:24:10.551 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:24:10.552 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:24:10.876 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:24:40.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:24:40.548 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:24:40.548 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:24:40.760 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,2015-12-11 20:25:10.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:25:10.546 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:25:10.546 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:25:10.721 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:25:40.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:25:40.545 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:25:40.546 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:25:41.127 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,2015-12-11 20:26:10.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:26:10.552 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:26:10.553 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:26:10.930 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:26:40.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:26:40.541 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:26:40.541 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:26:40.839 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,2015-12-11 20:27:10.493 ThaliTest[811:753242] multipeer session: restart
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:27:40.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:27:40.544 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:27:40.545 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:27:40.614 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,2015-12-11 20:28:10.493 ThaliTest[811:753242] multipeer session: restart
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:28:40.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:28:40.551 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:28:40.551 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:28:40.881 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,2015-12-11 20:29:10.497 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:29:10.552 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:29:10.553 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:29:10.754 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:29:40.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:29:40.551 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:29:40.551 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:29:41.236 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,2015-12-11 20:30:10.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:30:10.551 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:30:10.552 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:30:10.952 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:30:40.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:30:40.551 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:30:40.551 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:30:40.971 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,2015-12-11 20:31:10.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:31:10.541 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:31:10.541 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:31:10.630 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:31:40.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:31:40.564 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:31:40.565 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:31:40.579 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,2015-12-11 20:32:10.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:32:10.550 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:32:10.551 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:32:11.040 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:32:40.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:32:40.534 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
2015-12-11 20:32:40.536 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:32:40.841 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,2015-12-11 20:33:10.493 ThaliTest[811:753242] multipeer session: restart
,2015-12-11 20:33:10.535 ThaliTest[811:753242] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:33:10.536 ThaliTest[811:753242] client: found peer: Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:33:10.748 ThaliTest[811:753242] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server

```
