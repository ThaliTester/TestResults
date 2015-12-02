#### Test 5227736558f1fb0_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5227736558f1fb0/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/EFA410AA-41F3-4D11-A0BF-1DC772D3AF88/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/EFA410AA-41F3-4D11-A0BF-1DC772D3AF88/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5227736558f1fb0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5227736558f1fb0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/65F76C39-0B13-4DB5-B521-FBC40EC4E75B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59550"
,(lldb)     command script import "/tmp/EFA410AA-41F3-4D11-A0BF-1DC772D3AF88/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-02 18:06:43.789 ThaliTest[1108:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-02 18:06:43.792 ThaliTest[1108:60b] Multi-tasking -> Device: YES, App: YES
,2015-12-02 18:06:43.799 ThaliTest[1108:60b] Unlimited access to network resources
,2015-12-02 18:06:43.806 ThaliTest[1108:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.app,le.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-02 18:06:54.397 ThaliTest[1108:60b] Resetting plugins due to page load.
,2015-12-02 18:06:55.261 ThaliTest[1108:60b] Finished load of: file:///var/mobile/Applications/65F76C39-0B13-4DB5-B521-FBC40EC4E75B/ThaliTest.app/www/index.html
,2015-12-02 18:06:55.443 ThaliTest[1108:60b] JXcore Cordova plugin initializing
,2015-12-02 18:06:55.446 ThaliTest[1108:6707] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
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
,my name is : Apple-Iphone5-1_PT9787
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 60055
,2015-12-02 18:12:37.804 ThaliTest[1108:6707] jxcore: startBroadcasting
,2015-12-02 18:12:37.814 ThaliTest[1108:6707] server: starting Apple-Iphone5-1_PT9787.rFc5Bg==
2015-12-02 18:12:37.817 ThaliTest[1108:6707] multipeer session: start timer: 0x1a6386e0
,2015-12-02 18:12:37.818 ThaliTest[1108:6707] THEMultipeerSession initialized peer Apple-Iphone5-1_PT9787
,2015-12-02 18:12:37.830 ThaliTest[1108:6707] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-02T17:12:37.833Z SendDataTCPServer.js: TCP/IP server is bound to port: 60055
,2015-12-02 18:12:38.029 ThaliTest[1108:60b] client: found peer: Apple-Iphone6-1_PT5992.nsQaaA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5992.nsQaaA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT5992.nsQaaA==
2015-12-02T17:12:38.034Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT5992.nsQaaA==
,2015-12-02T17:12:38.034Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT5992.nsQaaA==
2015-12-02T17:12:38.034Z SendDataConnector.js: do connect now
,2015-12-02 18:12:38.035 ThaliTest[1108:6707] jxcore: connect Apple-Iphone6-1_PT5992.nsQaaA==
,2015-12-02 18:12:38.036 ThaliTest[1108:6707] client session: connect
,2015-12-02 18:12:38.036 ThaliTest[1108:6707] client session: stateChange:0->1 Apple-Iphone6-1_PT5992.nsQaaA==
,2015-12-02 18:12:39.045 ThaliTest[1108:60b] multipeer session: reset timer
,2015-12-02 18:12:39.047 ThaliTest[1108:60b] multipeer session: stop timer
,2015-12-02 18:12:39.048 ThaliTest[1108:60b] multipeer session: start timer: 0x1a6386e0
,2015-12-02 18:12:39.049 ThaliTest[1108:60b] server session: connect
,2015-12-02 18:12:39.049 ThaliTest[1108:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT5992
,2015-12-02 18:12:39.053 ThaliTest[1108:60b] server: accepting invitation Apple-Iphone6-1_PT5992
,2015-12-02 18:12:39.056 ThaliTest[1108:60b] client: found peer: Apple-IpadAir2-1_PT2754.fr+caQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2754.fr+caQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
,2015-12-02 18:12:40.514 ThaliTest[1108:5b33] client session: connected
2015-12-02 18:12:40.517 ThaliTest[1108:5b33] client session: stateChange:1->2 Apple-Iphone6-1_PT5992.nsQaaA==
,2015-12-02 18:12:41.038 ThaliTest[1108:5b33] client session: fireConnectCallback: Apple-Iphone6-1_PT5992.nsQaaA==
2015-12-02 18:12:41.039 ThaliTest[1108:5b33] jxcore: connect: success
,2015-12-02T17:12:41.041Z SendDataConnector.js: CLIENT connected to 60058, error: null
2015-12-02T17:12:41.041Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 18:12:41.042 ThaliTest[1108:60b] client: relay established
2015-12-02 18:12:41.043 ThaliTest[1108:60b] client: new accepted socket: 0x1a6440d0
,2015-12-02T17:12:41.056Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02 18:12:41.263 ThaliTest[1108:5b33] server session: connected
2015-12-02 18:12:41.264 ThaliTest[1108:5b33] server session: stateChange:1->2 Apple-Iphone6-1_PT5992
,2015-12-02 18:12:41.269 ThaliTest[1108:60b] server relay: connected (to port: 60055)
,2015-12-02T17:12:41.556Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T17:12:41.569Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-02T17:12:41.581Z SendDataTCPServer.js: TCP/IP server has received 43658 bytes of data
,2015-12-02T17:12:41.595Z SendDataTCPServer.js: TCP/IP server has received 54608 bytes of data
,2015-12-02T17:12:41.608Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-02T17:12:41.620Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-02T17:12:41.634Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
2015-12-02T17:12:41.637Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-02T17:12:41.650Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02T17:12:41.651Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-02 18:12:41.672 ThaliTest[1108:8103] server session: not connected Apple-Iphone6-1_PT5992
,2015-12-02T17:12:41.699Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-02T17:12:41.790Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-02T17:12:41.790Z SendDataConnector.js: got all data for this round
,2015-12-02T17:12:41.793Z SendDataConnector.js: CLIENT Stop now
,2015-12-02T17:12:41.794Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 18:12:41.796 ThaliTest[1108:6707] jxcore: disconnect
,2015-12-02 18:12:41.797 ThaliTest[1108:6707] client session: disconnectFromPeer: Apple-Iphone6-1_PT5992.nsQaaA==
,2015-12-02 18:12:41.798 ThaliTest[1108:6707] client session: disconnect
,2015-12-02 18:12:41.799 ThaliTest[1108:6707] client session: stateChange:2->0 Apple-Iphone6-1_PT5992.nsQaaA==
,2015-12-02 18:12:42.208 ThaliTest[1108:6707] jxcore: disconnect: success
,2015-12-02T17:12:42.210Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT5992.nsQaaA==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT2754.fr+caQ==
2015-12-02T17:12:42.211Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2754.fr+caQ==
2015-12-02T17:12:42.211Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2754.fr+caQ==,
2015-12-02T17:12:42.211Z SendDataConnector.js: do connect now
,2015-12-02 18:12:42.212 ThaliTest[1108:6707] jxcore: connect Apple-IpadAir2-1_PT2754.fr+caQ==
2015-12-02 18:12:42.213 ThaliTest[1108:6707] client session: connect
2015-12-02 18:12:42.213 ThaliTest[1108:6707] client session: stateChange:0->1 Apple-IpadAir2-1_PT2754.fr+caQ==
,2015-12-02 18:12:42.501 ThaliTest[1108:60b] client: found peer: Apple-Iphone5s-1_PT367.AiGtHw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT367.AiGtHw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-02 18:12:43.036 ThaliTest[1108:60b] multipeer session: reset timer
2015-12-02 18:12:43.037 ThaliTest[1108:60b] multipeer session: stop timer
2015-12-02 18:12:43.037 ThaliTest[1108:60b] multipeer session: start timer: 0x1a6386e0
2015-12-02 18:12:,43.038 ThaliTest[1108:60b] server session: connect
2015-12-02 18:12:43.039 ThaliTest[1108:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT2754
,2015-12-02 18:12:43.044 ThaliTest[1108:60b] server: accepting invitation Apple-IpadAir2-1_PT2754
,2015-12-02 18:12:45.196 ThaliTest[1108:5b33] client session: connected
2015-12-02 18:12:45.197 ThaliTest[1108:5b33] client session: stateChange:1->2 Apple-IpadAir2-1_PT2754.fr+caQ==
,2015-12-02 18:12:45.200 ThaliTest[1108:5b33] client session: fireConnectCallback: Apple-IpadAir2-1_PT2754.fr+caQ==
,2015-12-02 18:12:45.201 ThaliTest[1108:5b33] jxcore: connect: success
,2015-12-02T17:12:45.202Z SendDataConnector.js: CLIENT connected to 60062, error: null
2015-12-02T17:12:45.203Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 18:12:45.204 ThaliTest[1108:60b] client: relay established
,2015-12-02 18:12:45.204 ThaliTest[1108:60b] client: new accepted socket: 0x1a723200
,2015-12-02T17:12:45.217Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02 18:12:45.634 ThaliTest[1108:60b] multipeer session: reset timer
2015-12-02 18:12:45.635 ThaliTest[1108:60b] multipeer session: stop timer
2015-12-02 18:12:45.635 ThaliTest[1108:60b] multipeer session: start timer: 0x1a6386e0
2015-12-02 18:12:,45.636 ThaliTest[1108:60b] server session: connect
2015-12-02 18:12:45.636 ThaliTest[1108:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT367
,2015-12-02 18:12:45.642 ThaliTest[1108:60b] server: accepting invitation Apple-Iphone5s-1_PT367
,2015-12-02T17:12:45.813Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-02T17:12:45.827Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-02T17:12:45.906Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-02 18:12:46.319 ThaliTest[1108:760f] server session: connected
2015-12-02 18:12:46.321 ThaliTest[1108:760f] server session: stateChange:1->2 Apple-IpadAir2-1_PT2754
,2015-12-02 18:12:46.326 ThaliTest[1108:60b] server relay: connected (to port: 60055)
2015-12-02T17:12:46.328Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-02T17:12:46.328Z SendDataConnector.js: got all data for this round
,2015-12-02T17:12:46.330Z SendDataConnector.js: CLIENT Stop now
,2015-12-02T17:12:46.330Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 18:12:46.331 ThaliTest[1108:6707] jxcore: disconnect
,2015-12-02 18:12:46.332 ThaliTest[1108:6707] client session: disconnectFromPeer: Apple-IpadAir2-1_PT2754.fr+caQ==
,2015-12-02 18:12:46.333 ThaliTest[1108:6707] client session: disconnect
,2015-12-02 18:12:46.334 ThaliTest[1108:6707] client session: stateChange:2->0 Apple-IpadAir2-1_PT2754.fr+caQ==
,2015-12-02 18:12:46.340 ThaliTest[1108:6707] jxcore: disconnect: success
2015-12-02T17:12:46.341Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2754.fr+caQ==
---- round done--------
device[3]: Apple-Iphone5s-1_PT367.AiG,tHw==
2015-12-02T17:12:46.342Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02T17:12:46.343Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02T17:12:46.343Z SendDataConnec,tor.js: do connect now
2015-12-02 18:12:46.343 ThaliTest[1108:6707] jxcore: connect Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02 18:12:46.344 ThaliTest[1108:6707] client session: connect
2015-12-02 18:12:46.345 ThaliTest[1108:6707] client session: stateChange:0->1 Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02T17:12:46.355Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T17:12:46.699Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-02T17:12:46.713Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-02T17:12:46.726Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-02T17:12:46.740Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 18:12:46.763 ThaliTest[1108:5b33] server session: not connected Apple-IpadAir2-1_PT2754
,2015-12-02 18:12:49.032 ThaliTest[1108:5b33] client session: connected
2015-12-02 18:12:49.034 ThaliTest[1108:5b33] client session: stateChange:1->2 Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02 18:12:49.036 ThaliTest[1108:5b33] client session: fireConnectCallback: Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02 18:12:49.037 ThaliTest[1108:5b33] jxcore: connect: success
,2015-12-02T17:12:49.038Z SendDataConnector.js: CLIENT connected to 60067, error: null
2015-12-02T17:12:49.038Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 18:12:49.041 ThaliTest[1108:60b] client: relay established
,2015-12-02 18:12:49.042 ThaliTest[1108:60b] client: new accepted socket: 0x1a648190
,2015-12-02T17:12:49.051Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T17:12:49.858Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-02T17:12:49.892Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-02T17:12:49.905Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-02T17:12:50.028Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-02T17:12:50.030Z SendDataConnector.js: got all data for this round
,2015-12-02T17:12:50.031Z SendDataConnector.js: CLIENT Stop now
2015-12-02T17:12:50.032Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 18:12:50.033 ThaliTest[1108:6707] jxcore: disconnect
2015-12-02 18:12:50.033 ThaliTest[1108:6707] client session: disconnectFromPeer: Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02 18:12:50.034 ThaliTest[1108:6707] client session: disconnect
,2015-12-02 18:12:50.035 ThaliTest[1108:6707] client session: stateChange:2->0 Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02 18:12:50.038 ThaliTest[1108:6707] jxcore: disconnect: success
2015-12-02T17:12:50.039Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT367.AiGtHw==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT9787","time":12244,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT5992.nsQaaA==","time":3758,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_,PT2754.fr+caQ==","time":4117,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT367.AiGtHw==","time":3687,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 4117 ms, 99% : 4117 ms, 95 : 4117 ms, 90% : 4117 ms.
Result count 3, range 3687 ms to  4117 ms.
,sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
,2015-12-02T17:12:50.051Z SendDataConnector.js: CLIENT Stop now
2015-12-02T17:12:50.051Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 18:12:53.012 ThaliTest[1108:760f] server session: connected
2015-12-02 18:12:53.014 ThaliTest[1108:760f] server session: stateChange:1->2 Apple-Iphone5s-1_PT367
,2015-12-02 18:12:53.051 ThaliTest[1108:60b] server relay: connected (to port: 60055)
,2015-12-02T17:12:53.060Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T17:12:53.515Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-02T17:12:53.529Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-02T17:12:53.543Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-02T17:12:53.556Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 18:12:53.600 ThaliTest[1108:760f] server session: not connected Apple-Iphone5s-1_PT367
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-12-02 18:12:57.680 ThaliTest[1108:6707] jxcore: stopBroadcasting
2015-12-02 18:12:57.681 ThaliTest[1108:6707] THEMultipeerSession stopping peer
2015-12-02 18:12:57.681 ThaliTest[1108:6707] multipeer session: stop timer
,2015-12-02 18:12:57.682 ThaliTest[1108:6707] server session: disconnect
,2015-12-02 18:12:57.683 ThaliTest[1108:6707] server session: stateChange:2->0 Apple-Iphone6-1_PT5992
,2015-12-02 18:12:57.687 ThaliTest[1108:6707] server session: disconnect
,2015-12-02 18:12:57.687 ThaliTest[1108:6707] server session: stateChange:2->0 Apple-Iphone5s-1_PT367
,2015-12-02 18:12:57.693 ThaliTest[1108:6707] server session: disconnect
,2015-12-02 18:12:57.694 ThaliTest[1108:6707] server session: stateChange:2->0 Apple-IpadAir2-1_PT2754
,2015-12-02 18:12:57.700 ThaliTest[1108:6707] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-02T17:12:57.717Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02T17:12:57.719Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02T17:12:57.719Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02T17:12:57.720Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT367.AiGtHw==\",\"time\":3687,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone6-1_PT5992.nsQaaA==\",\"time\":3758,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-IpadAir2-1_PT2754.fr+caQ==\",\"time\":4117,\"result\":\"OK\",\"connections\":1,,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !

```
