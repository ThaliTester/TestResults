#### Test 51986340441e256_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51986340441e256/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/29716A74-1DBC-4665-BB82-34855B62B21F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/29716A74-1DBC-4665-BB82-34855B62B21F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51986340441e256/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51986340441e256/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4E06AD27-F661-4919-A082-E9D5BAFD1C8B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59783"
,(lldb)     command script import "/tmp/29716A74-1DBC-4665-BB82-34855B62B21F/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-02 18:55:51.271 ThaliTest[2474:2107138] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/35E1BA0F-81CF-41A7-B661-CD621391343F/Library/Cookies/Cookies.binarycookies
,2015-12-02 18:55:51.648 ThaliTest[2474:2107138] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-02 18:55:51.649 ThaliTest[2474:2107138] Multi-tasking -> Device: YES, App: YES
,2015-12-02 18:55:51.657 ThaliTest[2474:2107138] Unlimited access to network resources
,2015-12-02 18:55:51.663 ThaliTest[2474:2107138] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-02 18:55:55.189 ThaliTest[2474:2107138] Resetting plugins due to page load.
,2015-12-02 18:55:55.550 ThaliTest[2474:2107138] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/4E06AD27-F661-4919-A082-E9D5BAFD1C8B/ThaliTest.app/www/index.html
,2015-12-02 18:55:55.672 ThaliTest[2474:2107138] JXcore Cordova plugin initializing
,2015-12-02 18:55:55.673 ThaliTest[2474:2107271] JXcore instance initializing
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
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone6-1_PT8308
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 65286
,2015-12-02 19:01:52.957 ThaliTest[2474:2107271] jxcore: startBroadcasting
,2015-12-02 19:01:52.969 ThaliTest[2474:2107271] server: starting Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02 19:01:52.970 ThaliTest[2474:2107271] multipeer session: start timer: 0x1aa3c8f0
2015-12-02 19:01:52.971 ThaliTest[2474:2107271] THEMultipeerSessio,n initialized peer Apple-Iphone6-1_PT8308
2015-12-02 19:01:52.972 ThaliTest[2474:2107271] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-02T18:01:52.977Z SendDataTCPServer.js: TCP/IP server is bound to port: 65286
,2015-12-02 19:01:53.163 ThaliTest[2474:2107138] client: found peer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3324.ZgTNhQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT3324.ZgTNhQ==
2015-12-02T18:01:53.166Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT3324.ZgTNhQ==
2015-12-02 19:01:53.166 ThaliTest[2474:2107138] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
2015-12-02T18:01:53.166Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT3324.ZgTNhQ==
2015-12-02T18:01:53.166Z SendDataConnector.js: do connect now
,2015-12-02 19:01:53.167 ThaliTest[2474:2107271] jxcore: connect Apple-Iphone5s-1_PT3324.ZgTNhQ==
2015-12-02 19:01:53.167 ThaliTest[2474:2107271] client session: connect
2015-12-02 19:01:53.167 ThaliTest[2474:2107271] client session: stateChange:0->1 Appl,e-Iphone5s-1_PT3324.ZgTNhQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1792.Nse+hg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-02 19:01:54.272 ThaliTest[2474:2107138] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8086.XWQOsA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-02 19:01:57.756 ThaliTest[2474:2107836] client session: connected
,2015-12-02 19:01:57.757 ThaliTest[2474:2107836] client session: stateChange:1->2 Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02 19:01:57.768 ThaliTest[2474:2107845] client session: fireConnectCallback: Apple-Iphone5s-1_PT3324.ZgTNhQ==
2015-12-02 19:01:57.769 ThaliTest[2474:2107845] jxcore: connect: success
,2015-12-02T18:01:57.771Z SendDataConnector.js: CLIENT connected to 65290, error: null
,2015-12-02T18:01:57.771Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 19:01:57.775 ThaliTest[2474:2107138] client: relay established
2015-12-02 19:01:57.776 ThaliTest[2474:2107138] client: new accepted socket: 0x1ade4230
,2015-12-02T18:01:57.791Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T18:01:58.116Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-02T18:01:58.201Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-02T18:01:58.214Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-02T18:01:58.228Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-02T18:01:58.228Z SendDataConnector.js: got all data for this round
,2015-12-02T18:01:58.230Z SendDataConnector.js: CLIENT Stop now
2015-12-02T18:01:58.230Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 19:01:58.231 ThaliTest[2474:2107271] jxcore: disconnect
2015-12-02 19:01:58.231 ThaliTest[2474:2107271] client session: disconnectFromPeer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
2015-12-02 19:01:58.231 ThaliTest[2474:2107271] client session: disconnect
2015-12-02 19:01:58.232 ThaliTest[2474:2107271] client session: stateChange:2->0 Apple-Iphone5s-1_PT3324.ZgTNhQ==
2015-12-02 19:01:58.233 ThaliTest[2474:2107271] jxcore: disconnect: success
2015-12-02T18:01:58.234Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT3324.ZgTNhQ==
,---- round done--------
device[2]: Apple-Iphone5-1_PT1792.Nse+hg==
2015-12-02T18:01:58.236Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT1792.Nse+hg==
2015-12-02T18:01:58.236Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT1792.Nse+hg==
2015-12-02T18:01:58.236Z SendDataConnector.js: do connect now
2015-12-02 19:01:58.237 ThaliTest[2474:2107271] jxcore: connect Apple-Iphone5-1_PT1792.Nse+hg==
2015-12-02 19:01:58.237 ThaliTest[2474:2107271] client session: connect
,2015-12-02 19:01:58.237 ThaliTest[2474:2107271] client session: stateChange:0->1 Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:01:59.098 ThaliTest[2474:2107138] multipeer session: reset timer
2015-12-02 19:01:59.099 ThaliTest[2474:2107138] multipeer session: stop timer
2015-12-02 19:01:59.100 ThaliTest[2474:2107138] multipeer session: start timer: 0x1aa3c8f0
2015-,12-02 19:01:59.100 ThaliTest[2474:2107138] server session: connect
2015-12-02 19:01:59.101 ThaliTest[2474:2107138] server session: stateChange:0->1 Apple-Iphone5-1_PT1792
,2015-12-02 19:01:59.111 ThaliTest[2474:2107138] server: accepting invitation Apple-Iphone5-1_PT1792
,2015-12-02 19:02:00.659 ThaliTest[2474:2107138] multipeer session: reset timer
2015-12-02 19:02:00.659 ThaliTest[2474:2107138] multipeer session: stop timer
2015-12-02 19:02:00.660 ThaliTest[2474:2107138] multipeer session: start timer: 0x1aa3c8f0
2015-,12-02 19:02:00.660 ThaliTest[2474:2107138] server session: connect
2015-12-02 19:02:00.661 ThaliTest[2474:2107138] server session: stateChange:0->1 Apple-IpadAir2-1_PT8086
,2015-12-02 19:02:00.670 ThaliTest[2474:2107138] server: accepting invitation Apple-IpadAir2-1_PT8086
,2015-12-02 19:02:01.228 ThaliTest[2474:2107838] server session: connected
2015-12-02 19:02:01.229 ThaliTest[2474:2107838] server session: stateChange:1->2 Apple-Iphone5-1_PT1792
,2015-12-02 19:02:01.240 ThaliTest[2474:2107138] server relay: connected (to port: 65286)
,2015-12-02T18:02:01.247Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T18:02:01.787Z SendDataTCPServer.js: TCP/IP server has received 3968 bytes of data
,2015-12-02T18:02:01.803Z SendDataTCPServer.js: TCP/IP server has received 19968 bytes of data
,2015-12-02T18:02:01.821Z SendDataTCPServer.js: TCP/IP server has received 39680 bytes of data
,2015-12-02T18:02:01.837Z SendDataTCPServer.js: TCP/IP server has received 54560 bytes of data
,2015-12-02T18:02:01.850Z SendDataTCPServer.js: TCP/IP server has received 67456 bytes of data
,2015-12-02T18:02:01.865Z SendDataTCPServer.js: TCP/IP server has received 80352 bytes of data
,2015-12-02T18:02:01.880Z SendDataTCPServer.js: TCP/IP server has received 88288 bytes of data
,2015-12-02T18:02:02.146Z SendDataTCPServer.js: TCP/IP server has received 94240 bytes of data
,2015-12-02T18:02:02.160Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 19:02:02.177 ThaliTest[2474:2107838] client session: connected
2015-12-02 19:02:02.177 ThaliTest[2474:2107838] client session: stateChange:1->2 Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:02:02.186 ThaliTest[2474:2107836] client session: fireConnectCallback: Apple-Iphone5-1_PT1792.Nse+hg==
2015-12-02 19:02:02.186 ThaliTest[2474:2107836] jxcore: connect: success
2015-12-02T18:02:02.188Z SendDataConnector.js: CLIENT connected ,to 65294, error: null
2015-12-02T18:02:02.189Z SendDataConnector.js: CLIENT starting client 
2015-12-02 19:02:02.193 ThaliTest[2474:2107138] client: relay established
2015-12-02 19:02:02.193 ThaliTest[2474:2107138] client: new accepted socket: 0x1ad5cba0
,2015-12-02 19:02:02.197 ThaliTest[2474:2107838] server session: not connected Apple-Iphone5-1_PT1792
,2015-12-02T18:02:02.205Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T18:02:02.661Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-02T18:02:02.747Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-02T18:02:02.811Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-02T18:02:02.812Z SendDataConnector.js: got all data for this round
,2015-12-02T18:02:02.813Z SendDataConnector.js: CLIENT Stop now
,2015-12-02T18:02:02.815Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 19:02:02.816 ThaliTest[2474:2107271] jxcore: disconnect
,2015-12-02 19:02:02.817 ThaliTest[2474:2107271] client session: disconnectFromPeer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:02:02.819 ThaliTest[2474:2107271] client session: disconnect
,2015-12-02 19:02:02.821 ThaliTest[2474:2107271] client session: stateChange:2->0 Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:02:02.886 ThaliTest[2474:2107271] jxcore: disconnect: success
2015-12-02T18:02:02.887Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT1792.Nse+hg==
,---- round done--------
,device[3]: Apple-IpadAir2-1_PT8086.XWQOsA==
2015-12-02T18:02:02.889Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02T18:02:02.890Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02T18:02:02.891Z SendDataConnector.js: do connect now
,2015-12-02 19:02:02.892 ThaliTest[2474:2107271] jxcore: connect Apple-IpadAir2-1_PT8086.XWQOsA==
2015-12-02 19:02:02.893 ThaliTest[2474:2107271] client session: connect
2015-12-02 19:02:02.893 ThaliTest[2474:2107271] client session: stateChange:0->1 Appl,e-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:02:03.208 ThaliTest[2474:2107845] server session: connected
2015-12-02 19:02:03.209 ThaliTest[2474:2107845] server session: stateChange:1->2 Apple-IpadAir2-1_PT8086
,2015-12-02 19:02:03.210 ThaliTest[2474:2107138] server relay: connected (to port: 65286)
,2015-12-02T18:02:03.213Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T18:02:03.449Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-02T18:02:03.463Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-02T18:02:03.718Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-02T18:02:03.736Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-02T18:02:03.751Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-02T18:02:03.766Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-02T18:02:03.783Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 19:02:03.853 ThaliTest[2474:2107845] server session: not connected Apple-IpadAir2-1_PT8086
,2015-12-02 19:02:05.897 ThaliTest[2474:2107836] client session: connected
2015-12-02 19:02:05.898 ThaliTest[2474:2107836] client session: stateChange:1->2 Apple-IpadAir2-1_PT8086.XWQOsA==
2015-12-02 19:02:05.900 ThaliTest[2474:2107836] client session: fi,reConnectCallback: Apple-IpadAir2-1_PT8086.XWQOsA==
2015-12-02 19:02:05.900 ThaliTest[2474:2107836] jxcore: connect: success
2015-12-02T18:02:05.901Z SendDataConnector.js: CLIENT connected to 65298, error: null
2015-12-02T18:02:05.902Z SendDataConnector,.js: CLIENT starting client 
,2015-12-02 19:02:05.905 ThaliTest[2474:2107138] client: relay established
2015-12-02 19:02:05.906 ThaliTest[2474:2107138] client: new accepted socket: 0x1ade12c0
,2015-12-02T18:02:05.917Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T18:02:06.316Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-02T18:02:06.330Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-02T18:02:06.330Z SendDataConnector.js: got all data for this round
,2015-12-02T18:02:06.330Z SendDataConnector.js: CLIENT Stop now
2015-12-02T18:02:06.331Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-02 19:02:06.331 ThaliTest[2474:2107271] jxcore: disconnect
2015-12-02 19:02:06.331 ThaliTest[2474:2107271] cli,ent session: disconnectFromPeer: Apple-IpadAir2-1_PT8086.XWQOsA==
2015-12-02 19:02:06.331 ThaliTest[2474:2107271] client session: disconnect
2015-12-02 19:02:06.331 ThaliTest[2474:2107271] client session: stateChange:2->0 Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:02:06.332 ThaliTest[2474:2107271] jxcore: disconnect: success
2015-12-02T18:02:06.333Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8086.XWQOsA==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT8308","time":13394,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT3324.ZgTNhQ==","time":5063,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT1792.Nse+hg==","time":4576,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT8086.XWQOsA==","time":3440,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 5063 ms, 99% : 5063 ms, 95 : 5063 ms, 90% : 5063 ms.
Result count 3, range 3440 ms to  5063 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
2015-12-02T18:02:06.338Z SendDataConnector.js: CLIENT Stop now
,2015-12-02T18:02:06.338Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 19:02:28.297 ThaliTest[2474:2107138] client: found peer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02 19:02:30.661 ThaliTest[2474:2107138] multipeer session: restart
,2015-12-02 19:02:30.680 ThaliTest[2474:2107138] client: found peer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
2015-12-02 19:02:30.683 ThaliTest[2474:2107138] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
2015-12-02 19:02:30.684 ThaliTest[2474:2107138] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:02:37.346 ThaliTest[2474:2107138] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:03:00.659 ThaliTest[2474:2107138] multipeer session: restart
,2015-12-02 19:03:00.777 ThaliTest[2474:2107138] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
2015-12-02 19:03:00.778 ThaliTest[2474:2107138] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:03:00.866 ThaliTest[2474:2107138] client: found peer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02 19:03:04.085 ThaliTest[2474:2107138] client: lost peer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
2015-12-02 19:03:04.086 ThaliTest[2474:2107138] client session: onPeerLost: Apple-Iphone5s-1_PT3324.ZgTNhQ==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT3324.ZgTNhQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:03:06.039 ThaliTest[2474:2107138] client: found peer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3324.ZgTNhQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-02 19:03:30.659 ThaliTest[2474:2107138] multipeer session: restart
,2015-12-02 19:03:30.676 ThaliTest[2474:2107138] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
2015-12-02 19:03:30.678 ThaliTest[2474:2107138] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:03:30.754 ThaliTest[2474:2107138] client: found peer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02 19:03:58.591 ThaliTest[2474:2107138] client: lost peer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
2015-12-02 19:03:58.592 ThaliTest[2474:2107138] client session: onPeerLost: Apple-Iphone5s-1_PT3324.ZgTNhQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3324.ZgTNhQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:04:00.659 ThaliTest[2474:2107138] multipeer session: restart
,2015-12-02 19:04:00.674 ThaliTest[2474:2107138] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
2015-12-02 19:04:00.677 ThaliTest[2474:2107138] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
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
,2015-12-02 19:04:30.659 ThaliTest[2474:2107138] multipeer session: restart
,2015-12-02 19:04:30.674 ThaliTest[2474:2107138] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
2015-12-02 19:04:30.676 ThaliTest[2474:2107138] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
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
,2015-12-02 19:05:00.659 ThaliTest[2474:2107138] multipeer session: restart
,2015-12-02 19:05:00.674 ThaliTest[2474:2107138] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
2015-12-02 19:05:00.676 ThaliTest[2474:2107138] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
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
,2015-12-02 19:05:30.659 ThaliTest[2474:2107138] multipeer session: restart
,2015-12-02 19:05:30.673 ThaliTest[2474:2107138] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
2015-12-02 19:05:30.675 ThaliTest[2474:2107138] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
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
,2015-12-02 19:06:00.657 ThaliTest[2474:2107138] multipeer session: restart
,2015-12-02 19:06:00.671 ThaliTest[2474:2107138] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:06:00.673 ThaliTest[2474:2107138] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
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
,2015-12-02 19:06:30.657 ThaliTest[2474:2107138] multipeer session: restart
,2015-12-02 19:06:30.672 ThaliTest[2474:2107138] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:06:30.673 ThaliTest[2474:2107138] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
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
,2015-12-02 19:07:00.657 ThaliTest[2474:2107138] multipeer session: restart
,2015-12-02 19:07:00.673 ThaliTest[2474:2107138] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
2015-12-02 19:07:00.674 ThaliTest[2474:2107138] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
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
,2015-12-02 19:07:30.657 ThaliTest[2474:2107138] multipeer session: restart
,2015-12-02 19:07:30.671 ThaliTest[2474:2107138] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
2015-12-02 19:07:30.673 ThaliTest[2474:2107138] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
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
,2015-12-02 19:08:00.657 ThaliTest[2474:2107138] multipeer session: restart
,2015-12-02 19:08:00.672 ThaliTest[2474:2107138] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
2015-12-02 19:08:00.673 ThaliTest[2474:2107138] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
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
,2015-12-02 19:08:30.654 ThaliTest[2474:2107138] multipeer session: restart
,2015-12-02 19:08:30.669 ThaliTest[2474:2107138] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:08:30.673 ThaliTest[2474:2107138] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
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
,2015-12-02 19:09:00.654 ThaliTest[2474:2107138] multipeer session: restart
,2015-12-02 19:09:00.671 ThaliTest[2474:2107138] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:09:00.673 ThaliTest[2474:2107138] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
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
,2015-12-02 19:09:30.654 ThaliTest[2474:2107138] multipeer session: restart
,2015-12-02 19:09:30.668 ThaliTest[2474:2107138] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
2015-12-02 19:09:30.669 ThaliTest[2474:2107138] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
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
,2015-12-02 19:10:00.654 ThaliTest[2474:2107138] multipeer session: restart
2015-12-02 19:10:00.660 ThaliTest[2474:2107138] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Fi,rst throw call stack:
(0x26e2efef 0x35798c8b 0x26d4aaa3 0x28e09d85 0x26932607 0x26931e81 0x268ab3d3 0x26df4faf 0x26df43bf 0x26df2a25 0x26d3f201 0x26d3f013 0x2e7ca201 0x2a50ba09 0xb95e3 0x35d4aaaf)
libc++abi.dylib: terminating with uncaught exception of t,ype NSException
,* thread #1: tid = 0x202702, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
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
