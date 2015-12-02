#### Test 51986340441e256_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51986340441e256/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/DEF20A3F-5FF3-441C-8366-674933571651/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/DEF20A3F-5FF3-441C-8366-674933571651/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51986340441e256/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51986340441e256/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/19EA5FBA-F482-4405-8AE8-EAA64A1365A0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59785"
,(lldb)     command script import "/tmp/DEF20A3F-5FF3-441C-8366-674933571651/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-02 18:56:41.526 ThaliTest[1125:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-02 18:56:41.529 ThaliTest[1125:60b] Multi-tasking -> Device: YES, App: YES
,2015-12-02 18:56:41.538 ThaliTest[1125:60b] Unlimited access to network resources
,2015-12-02 18:56:41.543 ThaliTest[1125:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.app,le.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-02 18:56:52.404 ThaliTest[1125:60b] Resetting plugins due to page load.
,2015-12-02 18:56:53.240 ThaliTest[1125:60b] Finished load of: file:///var/mobile/Applications/19EA5FBA-F482-4405-8AE8-EAA64A1365A0/ThaliTest.app/www/index.html
,2015-12-02 18:56:53.422 ThaliTest[1125:60b] JXcore Cordova plugin initializing
,2015-12-02 18:56:53.424 ThaliTest[1125:6807] JXcore instance initializing
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
Radios toggled
,my name is : Apple-Iphone5-1_PT1792
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 60263
,2015-12-02 19:01:51.029 ThaliTest[1125:6807] jxcore: startBroadcasting
,2015-12-02 19:01:51.042 ThaliTest[1125:6807] server: starting Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:01:51.044 ThaliTest[1125:6807] multipeer session: start timer: 0x1cd33160
,2015-12-02 19:01:51.053 ThaliTest[1125:6807] THEMultipeerSession initialized peer Apple-Iphone5-1_PT1792
,2015-12-02 19:01:51.055 ThaliTest[1125:6807] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-02T18:01:51.059Z SendDataTCPServer.js: TCP/IP server is bound to port: 60263
,2015-12-02 19:01:51.867 ThaliTest[1125:60b] client: found peer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3324.ZgTNhQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT3324.ZgTNhQ==
2015-12-02T18:01:51.871Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02T18:01:51.872Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02T18:01:51.873Z SendDataConnector.js: do connect now
,2015-12-02 19:01:51.873 ThaliTest[1125:6807] jxcore: connect Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02 19:01:51.874 ThaliTest[1125:6807] client session: connect
,2015-12-02 19:01:51.874 ThaliTest[1125:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02 19:01:52.230 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8086.XWQOsA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-02 19:01:53.749 ThaliTest[1125:60b] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-02 19:01:54.287 ThaliTest[1125:8303] client session: connected
,2015-12-02 19:01:54.289 ThaliTest[1125:8303] client session: stateChange:1->2 Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02 19:01:54.301 ThaliTest[1125:223] client session: fireConnectCallback: Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02 19:01:54.302 ThaliTest[1125:223] jxcore: connect: success
,2015-12-02T18:01:54.304Z SendDataConnector.js: CLIENT connected to 60266, error: null
,2015-12-02T18:01:54.304Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 19:01:54.306 ThaliTest[1125:60b] client: relay established
2015-12-02 19:01:54.306 ThaliTest[1125:60b] client: new accepted socket: 0x1ce8b940
,2015-12-02T18:01:54.319Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T18:01:54.877Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-02T18:01:54.892Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-02T18:01:54.906Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-02T18:01:54.918Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-02T18:01:54.931Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-02T18:01:54.955Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-02T18:01:54.968Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-02T18:01:54.981Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-02T18:01:54.994Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-02T18:01:54.994Z SendDataConnector.js: got all data for this round
,2015-12-02T18:01:54.996Z SendDataConnector.js: CLIENT Stop now
2015-12-02T18:01:54.997Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 19:01:54.998 ThaliTest[1125:6807] jxcore: disconnect
,2015-12-02 19:01:54.998 ThaliTest[1125:6807] client session: disconnectFromPeer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02 19:01:54.999 ThaliTest[1125:6807] client session: disconnect
,2015-12-02 19:01:55.000 ThaliTest[1125:6807] client session: stateChange:2->0 Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02 19:01:55.003 ThaliTest[1125:6807] jxcore: disconnect: success
2015-12-02T18:01:55.003Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT3324.ZgTNhQ==
---- round done--------
device[2]: Apple-IpadAir2-1_PT8086.XWQOsA==
2015-12-02T18:01:55.005Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02T18:01:55.006Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8086.XWQOsA==
2015-12-02T18:01:55.007Z SendDataConnector.js: do connect now
,2015-12-02 19:01:55.007 ThaliTest[1125:6807] jxcore: connect Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:01:55.008 ThaliTest[1125:6807] client session: connect
,2015-12-02 19:01:55.009 ThaliTest[1125:6807] client session: stateChange:0->1 Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:01:57.175 ThaliTest[1125:60b] multipeer session: reset timer
,2015-12-02 19:01:57.177 ThaliTest[1125:60b] multipeer session: stop timer
,2015-12-02 19:01:57.178 ThaliTest[1125:60b] multipeer session: start timer: 0x1cd33160
,2015-12-02 19:01:57.178 ThaliTest[1125:60b] server session: connect
,2015-12-02 19:01:57.179 ThaliTest[1125:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT8086
,2015-12-02 19:01:57.183 ThaliTest[1125:60b] server: accepting invitation Apple-IpadAir2-1_PT8086
,2015-12-02 19:01:58.075 ThaliTest[1125:7b03] client session: connected
,2015-12-02 19:01:58.077 ThaliTest[1125:7b03] client session: stateChange:1->2 Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:01:58.094 ThaliTest[1125:7b03] client session: fireConnectCallback: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:01:58.095 ThaliTest[1125:7b03] jxcore: connect: success
,2015-12-02T18:01:58.096Z SendDataConnector.js: CLIENT connected to 60269, error: null
,2015-12-02T18:01:58.096Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 19:01:58.098 ThaliTest[1125:60b] client: relay established
,2015-12-02 19:01:58.099 ThaliTest[1125:60b] client: new accepted socket: 0x1ce99810
,2015-12-02T18:01:58.110Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T18:01:58.636Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-02T18:01:58.760Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-02T18:01:58.785Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-02T18:01:58.798Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-02T18:01:59.099Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-02T18:01:59.100Z SendDataConnector.js: got all data for this round
,2015-12-02T18:01:59.101Z SendDataConnector.js: CLIENT Stop now
2015-12-02T18:01:59.101Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 19:01:59.102 ThaliTest[1125:6807] jxcore: disconnect
,2015-12-02 19:01:59.103 ThaliTest[1125:6807] client session: disconnectFromPeer: Apple-IpadAir2-1_PT8086.XWQOsA==
2015-12-02 19:01:59.104 ThaliTest[1125:6807] client session: disconnect
,2015-12-02 19:01:59.104 ThaliTest[1125:6807] client session: stateChange:2->0 Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:01:59.108 ThaliTest[1125:6807] jxcore: disconnect: success
,2015-12-02T18:01:59.110Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8086.XWQOsA==
,---- round done--------
,device[3]: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02T18:01:59.111Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02T18:01:59.113Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02T18:01:59.113Z SendDataConnector.js: do connect now
,2015-12-02 19:01:59.113 ThaliTest[1125:6807] jxcore: connect Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02 19:01:59.114 ThaliTest[1125:6807] client session: connect
,2015-12-02 19:01:59.115 ThaliTest[1125:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:01:59.603 ThaliTest[1125:60b] multipeer session: reset timer
2015-12-02 19:01:59.604 ThaliTest[1125:60b] multipeer session: stop timer
2015-12-02 19:01:59.605 ThaliTest[1125:60b] multipeer session: start timer: 0x1cd33160
,2015-12-02 19:01:59.605 ThaliTest[1125:60b] server session: connect
,2015-12-02 19:01:59.606 ThaliTest[1125:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT8308
,2015-12-02 19:01:59.794 ThaliTest[1125:1617] server session: connected
,2015-12-02 19:01:59.795 ThaliTest[1125:1617] server session: stateChange:1->2 Apple-IpadAir2-1_PT8086
,2015-12-02T18:01:59.808Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02 19:01:59.816 ThaliTest[1125:60b] server: accepting invitation Apple-Iphone6-1_PT8308
,2015-12-02 19:01:59.817 ThaliTest[1125:60b] server relay: connected (to port: 60263)
,2015-12-02T18:02:00.105Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-02T18:02:00.121Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-02T18:02:00.142Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-02T18:02:00.158Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 19:02:00.190 ThaliTest[1125:223] server session: not connected Apple-IpadAir2-1_PT8086
,2015-12-02 19:02:01.334 ThaliTest[1125:223] client session: connected
,2015-12-02 19:02:01.336 ThaliTest[1125:223] client session: stateChange:1->2 Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:02:01.339 ThaliTest[1125:223] client session: fireConnectCallback: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:02:01.340 ThaliTest[1125:223] jxcore: connect: success
,2015-12-02T18:02:01.341Z SendDataConnector.js: CLIENT connected to 60273, error: null
,2015-12-02T18:02:01.341Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 19:02:01.343 ThaliTest[1125:60b] client: relay established
2015-12-02 19:02:01.346 ThaliTest[1125:60b] client: new accepted socket: 0x1cea01b0
,2015-12-02T18:02:01.355Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T18:02:01.936Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-02T18:02:02.234Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-02T18:02:02.248Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-02T18:02:02.272Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-02T18:02:02.273Z SendDataConnector.js: got all data for this round
,2015-12-02T18:02:02.275Z SendDataConnector.js: CLIENT Stop now
2015-12-02T18:02:02.275Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 19:02:02.276 ThaliTest[1125:6807] jxcore: disconnect
,2015-12-02 19:02:02.277 ThaliTest[1125:6807] client session: disconnectFromPeer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:02:02.278 ThaliTest[1125:6807] client session: disconnect
,2015-12-02 19:02:02.279 ThaliTest[1125:6807] client session: stateChange:2->0 Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:02:02.281 ThaliTest[1125:6807] jxcore: disconnect: success
2015-12-02T18:02:02.282Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:02:02.283 ThaliTest[1125:7b03] server session: connected
---- round done--------
2015-12-02 19:02:02.284 ThaliTest[1125:7b03] server session: stateChange:1->2 Apple-Iphone6-1_PT8308
weAreDoneNow , resultArray.length: 3
done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT1792","time":11265,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT3324.ZgTNhQ==","time":3123,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1,_PT8086.XWQOsA==","time":4095,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT8308.Z3UjCg==","time":3160,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":1000,00}]}
sendList : 100% : 4095 ms, 99% : 4095 ms, 95 : 4095 ms, 90% : 4095 ms.
Result count 3, range 3123 ms to  4095 ms.
,sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-12-02T18:02:02.295Z SendDataConnector.js: CLIENT Stop now
2015-12-02T18:02:02.295Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 19:02:02.305 ThaliTest[1125:60b] server relay: connected (to port: 60263)
,2015-12-02T18:02:02.310Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T18:02:02.738Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-02T18:02:02.751Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-02T18:02:02.765Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-02T18:02:02.778Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-02T18:02:02.791Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-02T18:02:02.903Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 19:02:02.937 ThaliTest[1125:a00b] server session: not connected Apple-Iphone6-1_PT8308
,2015-12-02 19:02:28.351 ThaliTest[1125:60b] client: lost peer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
2015-12-02 19:02:28.352 ThaliTest[1125:60b] client session: onPeerLost: Apple-Iphone5s-1_PT3324.ZgTNhQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3324.ZgTNhQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:02:28.400 ThaliTest[1125:60b] client: found peer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3324.ZgTNhQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-02 19:02:29.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:02:59.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:03:00.359 ThaliTest[1125:60b] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02 19:03:00.360 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:03:00.373 ThaliTest[1125:60b] client: found peer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02 19:03:03.610 ThaliTest[1125:60b] client: lost peer: Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02 19:03:03.611 ThaliTest[1125:60b] client session: onPeerLost: Apple-Iphone6-1_PT8308.Z3UjCg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:03:04.519 ThaliTest[1125:60b] client: lost peer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02 19:03:04.521 ThaliTest[1125:60b] client session: onPeerLost: Apple-Iphone5s-1_PT3324.ZgTNhQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3324.ZgTNhQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:03:06.145 ThaliTest[1125:60b] client: found peer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3324.ZgTNhQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-02 19:03:06.223 ThaliTest[1125:60b] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":true}]
,2015-12-02 19:03:29.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:03:30.794 ThaliTest[1125:60b] client: found peer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02 19:03:30.886 ThaliTest[1125:60b] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:03:32.411 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,2015-12-02 19:03:58.640 ThaliTest[1125:60b] client: lost peer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02 19:03:58.641 ThaliTest[1125:60b] client session: onPeerLost: Apple-Iphone5s-1_PT3324.ZgTNhQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3324.ZgTNhQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:03:59.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:03:59.739 ThaliTest[1125:60b] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:03:59.782 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:04:09.807 ThaliTest[1125:60b] client: lost peer: Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02 19:04:09.809 ThaliTest[1125:60b] client session: onPeerLost: Apple-Iphone6-1_PT8308.Z3UjCg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:04:14.808 ThaliTest[1125:60b] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":true}]
,2015-12-02 19:04:29.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:04:59.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:04:59.617 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
2015-12-02 19:04:59.617 ThaliTest[1125:60b] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:05:09.918 ThaliTest[1125:60b] client: lost peer: Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02 19:05:09.920 ThaliTest[1125:60b] client session: onPeerLost: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:05:10.394 ThaliTest[1125:60b] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":true}]
,2015-12-02 19:05:29.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:05:29.617 ThaliTest[1125:60b] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:05:29.817 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:05:39.822 ThaliTest[1125:60b] client: lost peer: Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02 19:05:39.823 ThaliTest[1125:60b] client session: onPeerLost: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:05:44.990 ThaliTest[1125:60b] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":true}]
,2015-12-02 19:05:59.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:05:59.617 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
2015-12-02 19:05:59.618 ThaliTest[1125:60b] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:06:29.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:06:29.616 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:06:29.617 ThaliTest[1125:60b] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:06:33.689 ThaliTest[1125:60b] client: lost peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:06:33.690 ThaliTest[1125:60b] client session: onPeerLost: Apple-Iphone6-1_PT8308.Z3UjCg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:06:35.834 ThaliTest[1125:60b] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":true}]
,2015-12-02 19:06:39.695 ThaliTest[1125:60b] client: lost peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:06:39.696 ThaliTest[1125:60b] client session: onPeerLost: Apple-Iphone6-1_PT8308.Z3UjCg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:06:45.794 ThaliTest[1125:60b] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":true}]
,2015-12-02 19:06:59.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:07:29.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:07:29.618 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:07:29.619 ThaliTest[1125:60b] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-02 19:07:59.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:07:59.617 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:07:59.619 ThaliTest[1125:60b] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:08:09.844 ThaliTest[1125:60b] client: lost peer: Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02 19:08:09.845 ThaliTest[1125:60b] client session: onPeerLost: Apple-Iphone6-1_PT8308.Z3UjCg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:08:14.902 ThaliTest[1125:60b] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":true}]
,2015-12-02 19:08:29.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:08:59.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:08:59.615 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:09:00.641 ThaliTest[1125:60b] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:09:09.994 ThaliTest[1125:60b] client: lost peer: Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02 19:09:09.995 ThaliTest[1125:60b] client session: onPeerLost: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:09:14.658 ThaliTest[1125:60b] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":true}]
,2015-12-02 19:09:29.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:09:29.616 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:09:31.060 ThaliTest[1125:60b] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:09:36.201 ThaliTest[1125:60b] client: lost peer: Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02 19:09:36.203 ThaliTest[1125:60b] client session: onPeerLost: Apple-Iphone6-1_PT8308.Z3UjCg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:09:36.834 ThaliTest[1125:60b] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":true}]
,2015-12-02 19:09:59.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:09:59.617 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
2015-12-02 19:09:59.618 ThaliTest[1125:60b] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:10:03.025 ThaliTest[1125:60b] client: lost peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:10:03.026 ThaliTest[1125:60b] client session: onPeerLost: Apple-Iphone6-1_PT8308.Z3UjCg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:10:29.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:10:29.616 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:10:34.317 ThaliTest[1125:60b] client: lost peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:10:34.318 ThaliTest[1125:60b] client session: onPeerLost: Apple-IpadAir2-1_PT8086.XWQOsA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8086.XWQOsA==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:10:35.445 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8086.XWQOsA==","peerName":"(null)","peerAvailable":true}]
,2015-12-02 19:10:59.605 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:10:59.614 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:11:29.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:11:59.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:12:00.376 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:12:29.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:12:29.615 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:12:59.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:12:59.615 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:13:13.453 ThaliTest[1125:60b] client: lost peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:13:13.454 ThaliTest[1125:60b] client session: onPeerLost: Apple-IpadAir2-1_PT8086.XWQOsA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8086.XWQOsA==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:13:17.380 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8086.XWQOsA==","peerName":"(null)","peerAvailable":true}]
,2015-12-02 19:13:29.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:13:59.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:13:59.616 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:14:29.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:14:29.615 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:14:59.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:14:59.616 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:15:29.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:15:29.616 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:15:59.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:15:59.616 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:16:29.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:16:29.615 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:16:59.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:17:29.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:17:29.616 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:17:59.605 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:17:59.615 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:18:29.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:18:29.615 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:18:59.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:19:29.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:19:29.617 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:19:59.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:20:29.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:20:29.615 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:20:59.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:20:59.617 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:21:29.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:21:29.617 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:21:59.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:22:29.606 ThaliTest[1125:60b] multipeer session: restart
,2015-12-02 19:22:29.616 ThaliTest[1125:60b] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
stop tests now !
stop current!
testSendData stopped
,2015-12-02 19:22:51.045 ThaliTest[1125:6807] jxcore: stopBroadcasting
2015-12-02 19:22:51.046 ThaliTest[1125:6807] THEMultipeerSession stopping peer
2015-12-02 19:22:51.046 ThaliTest[1125:6807] multipeer session: stop timer
2015-12-02 19:22:51.047 ThaliTest[1125:6807] server session: disconnect
2015-12-02 19:22:51.047 ThaliTest[1125:6807] server session: stateChange:2->0 Apple-Iphone6-1_PT8308
,2015-12-02 19:22:51.053 ThaliTest[1125:6807] server session: disconnect
,2015-12-02 19:22:51.055 ThaliTest[1125:6807] server session: stateChange:2->0 Apple-IpadAir2-1_PT8086
,2015-12-02 19:22:51.060 ThaliTest[1125:6807] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-02T18:22:51.075Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-02T18:22:51.075Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-02T18:22:51.076Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT3324.ZgTNhQ==\",\"time\":3123,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone6-1_PT8308.Z3UjCg==\",\"time\":3160,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-IpadAir2-1_PT8086.XWQOsA==\",\"time\":4095,\"result\":\"OK\",\"connections\":,1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":3,"addressList":[]}
****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called

```
