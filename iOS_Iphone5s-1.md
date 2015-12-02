#### Test 5227736558f1fb0_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5227736558f1fb0/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C4CF57F1-C725-4B45-837E-80E7F6FC1218/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/C4CF57F1-C725-4B45-837E-80E7F6FC1218/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5227736558f1fb0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5227736558f1fb0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8B20400C-C15D-431E-B865-6D38F85BED74/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59554"
,(lldb)     command script import "/tmp/C4CF57F1-C725-4B45-837E-80E7F6FC1218/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-02 18:06:00.675 ThaliTest[2330:2198644] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B884764D-5587-4CB1-9797-7C604E5F9D05/Library/Cookies/Cookies.binarycookies
,2015-12-02 18:06:01.064 ThaliTest[2330:2198644] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-02 18:06:01.066 ThaliTest[2330:2198644] Multi-tasking -> Device: YES, App: YES
,2015-12-02 18:06:01.070 ThaliTest[2330:2198644] Unlimited access to network resources
,2015-12-02 18:06:01.076 ThaliTest[2330:2198644] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-02 18:06:04.389 ThaliTest[2330:2198644] Resetting plugins due to page load.
,2015-12-02 18:06:04.842 ThaliTest[2330:2198644] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/8B20400C-C15D-431E-B865-6D38F85BED74/ThaliTest.app/www/index.html
,2015-12-02 18:06:05.000 ThaliTest[2330:2198644] JXcore Cordova plugin initializing
,2015-12-02 18:06:05.002 ThaliTest[2330:2198759] JXcore instance initializing
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
,my name is : Apple-Iphone5s-1_PT367
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
serverPort is 49316
,2015-12-02 18:12:40.471 ThaliTest[2330:2198759] jxcore: startBroadcasting
,2015-12-02 18:12:40.484 ThaliTest[2330:2198759] server: starting Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02 18:12:40.485 ThaliTest[2330:2198759] multipeer session: start timer: 0x18e59840
,2015-12-02 18:12:40.486 ThaliTest[2330:2198759] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT367
2015-12-02 18:12:40.493 ThaliTest[2330:2198759] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-02T17:12:40.499Z SendDataTCPServer.js: TCP/IP server is bound to port: 49316
,2015-12-02 18:12:40.955 ThaliTest[2330:2198644] client: found peer: Apple-IpadAir2-1_PT2754.fr+caQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2754.fr+caQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT2754.fr+caQ==
2015-12-02T17:12:40.964Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2754.fr+caQ==
2015-12-02T17:12:40.965Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2754.fr+caQ==,
2015-12-02T17:12:40.966Z SendDataConnector.js: do connect now
,2015-12-02 18:12:40.966 ThaliTest[2330:2198759] jxcore: connect Apple-IpadAir2-1_PT2754.fr+caQ==
,2015-12-02 18:12:40.969 ThaliTest[2330:2198759] client session: connect
2015-12-02 18:12:40.969 ThaliTest[2330:2198759] client session: stateChange:0->1 Apple-IpadAir2-1_PT2754.fr+caQ==
,2015-12-02 18:12:40.995 ThaliTest[2330:2198644] client: found peer: Apple-Iphone5-1_PT9787.rFc5Bg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9787.rFc5Bg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-02 18:12:41.876 ThaliTest[2330:2198644] client: found peer: Apple-Iphone6-1_PT5992.nsQaaA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5992.nsQaaA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-02 18:12:44.644 ThaliTest[2330:2199348] client session: connected
2015-12-02 18:12:44.645 ThaliTest[2330:2199348] client session: stateChange:1->2 Apple-IpadAir2-1_PT2754.fr+caQ==
,2015-12-02 18:12:44.650 ThaliTest[2330:2199348] client session: fireConnectCallback: Apple-IpadAir2-1_PT2754.fr+caQ==
2015-12-02 18:12:44.650 ThaliTest[2330:2199348] jxcore: connect: success
,2015-12-02T17:12:44.652Z SendDataConnector.js: CLIENT connected to 49319, error: null
,2015-12-02T17:12:44.653Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 18:12:44.659 ThaliTest[2330:2198644] client: relay established
2015-12-02 18:12:44.659 ThaliTest[2330:2198644] client: new accepted socket: 0x18d71590
,2015-12-02T17:12:44.679Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T17:12:45.093Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-02T17:12:45.106Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-02T17:12:45.132Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-02T17:12:45.145Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-02T17:12:45.145Z SendDataConnector.js: got all data for this round
,2015-12-02T17:12:45.146Z SendDataConnector.js: CLIENT Stop now
2015-12-02T17:12:45.146Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-02 18:12:45.147 ThaliTest[2330:2198759] jxcore: disconnect
,2015-12-02 18:12:45.147 ThaliTest[2330:2198759] client session: disconnectFromPeer: Apple-IpadAir2-1_PT2754.fr+caQ==
,2015-12-02 18:12:45.148 ThaliTest[2330:2198759] client session: disconnect
,2015-12-02 18:12:45.148 ThaliTest[2330:2198759] client session: stateChange:2->0 Apple-IpadAir2-1_PT2754.fr+caQ==
2015-12-02 18:12:45.149 ThaliTest[2330:2198759] jxcore: disconnect: success
2015-12-02T17:12:45.150Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2754.fr+caQ==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT9787.rFc5Bg==
,2015-12-02T17:12:45.153Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9787.rFc5Bg==
,2015-12-02T17:12:45.153Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9787.rFc5Bg==
,2015-12-02T17:12:45.153Z SendDataConnector.js: do connect now
,2015-12-02 18:12:45.154 ThaliTest[2330:2198759] jxcore: connect Apple-Iphone5-1_PT9787.rFc5Bg==
2015-12-02 18:12:45.154 ThaliTest[2330:2198759] client session: connect
2015-12-02 18:12:45.154 ThaliTest[2330:2198759] client session: stateChange:0->1 Apple-Iphone5-1_PT9787.rFc5Bg==
,2015-12-02 18:12:46.741 ThaliTest[2330:2198644] multipeer session: reset timer
2015-12-02 18:12:46.742 ThaliTest[2330:2198644] multipeer session: stop timer
2015-12-02 18:12:46.743 ThaliTest[2330:2198644] multipeer session: start timer: 0x18e59840
2015-,12-02 18:12:46.743 ThaliTest[2330:2198644] server session: connect
2015-12-02 18:12:46.744 ThaliTest[2330:2198644] server session: stateChange:0->1 Apple-Iphone6-1_PT5992
,2015-12-02 18:12:46.757 ThaliTest[2330:2198644] server: accepting invitation Apple-Iphone6-1_PT5992
2015-12-02 18:12:46.762 ThaliTest[2330:2198644] multipeer session: reset timer
2015-12-02 18:12:46.762 ThaliTest[2330:2198644] multipeer session: stop tim,er
2015-12-02 18:12:46.763 ThaliTest[2330:2198644] multipeer session: start timer: 0x18e59840
2015-12-02 18:12:46.763 ThaliTest[2330:2198644] server session: connect
2015-12-02 18:12:46.764 ThaliTest[2330:2198644] server session: stateChange:0->1 Apple-,Iphone5-1_PT9787
2015-12-02 18:12:46.789 ThaliTest[2330:2198644] server: accepting invitation Apple-Iphone5-1_PT9787
,2015-12-02 18:12:47.180 ThaliTest[2330:2198644] multipeer session: reset timer
2015-12-02 18:12:47.181 ThaliTest[2330:2198644] multipeer session: stop timer
2015-12-02 18:12:47.181 ThaliTest[2330:2198644] multipeer session: start timer: 0x18e59840
2015-,12-02 18:12:47.182 ThaliTest[2330:2198644] server session: connect
2015-12-02 18:12:47.182 ThaliTest[2330:2198644] server session: stateChange:0->1 Apple-IpadAir2-1_PT2754
,2015-12-02 18:12:47.190 ThaliTest[2330:2198644] server: accepting invitation Apple-IpadAir2-1_PT2754
,2015-12-02 18:12:48.949 ThaliTest[2330:2199342] server session: connected
2015-12-02 18:12:48.949 ThaliTest[2330:2199342] server session: stateChange:1->2 Apple-Iphone6-1_PT5992
,2015-12-02T17:12:48.958Z SendDataTCPServer.js: TCP/IP server connected
2015-12-02 18:12:48.958 ThaliTest[2330:2198644] server relay: connected (to port: 49316)
,2015-12-02 18:12:48.980 ThaliTest[2330:2199377] server session: connected
2015-12-02 18:12:48.981 ThaliTest[2330:2199377] server session: stateChange:1->2 Apple-Iphone5-1_PT9787
,2015-12-02 18:12:48.993 ThaliTest[2330:2198644] server relay: connected (to port: 49316)
2015-12-02T17:12:48.998Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T17:12:49.273Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-02T17:12:49.290Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-02T17:12:49.313Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-02T17:12:49.330Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-02T17:12:49.346Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-02T17:12:49.361Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 18:12:49.379 ThaliTest[2330:2199342] server session: not connected Apple-Iphone6-1_PT5992
,2015-12-02T17:12:49.491Z SendDataTCPServer.js: TCP/IP server has received 5952 bytes of data
,2015-12-02T17:12:49.506Z SendDataTCPServer.js: TCP/IP server has received 14880 bytes of data
,2015-12-02T17:12:49.525Z SendDataTCPServer.js: TCP/IP server has received 31744 bytes of data
,2015-12-02T17:12:49.541Z SendDataTCPServer.js: TCP/IP server has received 44640 bytes of data
,2015-12-02T17:12:49.557Z SendDataTCPServer.js: TCP/IP server has received 58528 bytes of data
,2015-12-02T17:12:49.572Z SendDataTCPServer.js: TCP/IP server has received 62496 bytes of data
,2015-12-02T17:12:49.798Z SendDataTCPServer.js: TCP/IP server has received 64480 bytes of data
,2015-12-02T17:12:49.815Z SendDataTCPServer.js: TCP/IP server has received 74400 bytes of data
,2015-12-02T17:12:49.833Z SendDataTCPServer.js: TCP/IP server has received 78368 bytes of data
,2015-12-02 18:12:49.866 ThaliTest[2330:2199377] server session: connected
2015-12-02 18:12:49.867 ThaliTest[2330:2199377] server session: stateChange:1->2 Apple-IpadAir2-1_PT2754
,2015-12-02T17:12:49.887Z SendDataTCPServer.js: TCP/IP server has received 92256 bytes of data
,2015-12-02T17:12:49.901Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
2015-12-02 18:12:49.901 ThaliTest[2330:2198644] server relay: connected (to port: 49316)
2015-12-02T17:12:49.902Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02 18:12:49.997 ThaliTest[2330:2199344] server session: not connected Apple-Iphone5-1_PT9787
,2015-12-02T17:12:50.089Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-02T17:12:50.105Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-02T17:12:50.119Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-02T17:12:50.319Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-02T17:12:50.334Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-02T17:12:50.351Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-02T17:12:50.368Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-02T17:12:50.385Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 18:12:50.428 ThaliTest[2330:2199334] server session: not connected Apple-IpadAir2-1_PT2754
,2015-12-02 18:12:52.962 ThaliTest[2330:2199344] client session: connected
2015-12-02 18:12:52.963 ThaliTest[2330:2199344] client session: stateChange:1->2 Apple-Iphone5-1_PT9787.rFc5Bg==
,2015-12-02 18:12:52.982 ThaliTest[2330:2199344] client session: fireConnectCallback: Apple-Iphone5-1_PT9787.rFc5Bg==
2015-12-02 18:12:52.982 ThaliTest[2330:2199344] jxcore: connect: success
2015-12-02T17:12:52.984Z SendDataConnector.js: CLIENT connected to 49325, error: null
,2015-12-02T17:12:52.985Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 18:12:52.988 ThaliTest[2330:2198644] client: relay established
2015-12-02 18:12:52.989 ThaliTest[2330:2198644] client: new accepted socket: 0x18d88780
,2015-12-02T17:12:53.000Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T17:12:53.482Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-02T17:12:53.496Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-02T17:12:53.534Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-02T17:12:53.534Z SendDataConnector.js: got all data for this round
,2015-12-02T17:12:53.535Z SendDataConnector.js: CLIENT Stop now
2015-12-02T17:12:53.535Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-02 18:12:53.535 ThaliTest[2330:2198759] jxcore: disconnect
2015-12-02 18:12:53.535 ThaliTest[2330:2198759] cli,ent session: disconnectFromPeer: Apple-Iphone5-1_PT9787.rFc5Bg==
2015-12-02 18:12:53.536 ThaliTest[2330:2198759] client session: disconnect
2015-12-02 18:12:53.536 ThaliTest[2330:2198759] client session: stateChange:2->0 Apple-Iphone5-1_PT9787.rFc5Bg==
,2015-12-02 18:12:53.537 ThaliTest[2330:2198759] jxcore: disconnect: success
2015-12-02T17:12:53.538Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9787.rFc5Bg==
---- round done--------
,device[3]: Apple-Iphone6-1_PT5992.nsQaaA==
2015-12-02T17:12:53.539Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT5992.nsQaaA==
2015-12-02T17:12:53.539Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT5992.nsQaaA==
20,15-12-02T17:12:53.539Z SendDataConnector.js: do connect now
2015-12-02 18:12:53.540 ThaliTest[2330:2198759] jxcore: connect Apple-Iphone6-1_PT5992.nsQaaA==
,2015-12-02 18:12:53.540 ThaliTest[2330:2198759] client session: connect
2015-12-02 18:12:53.540 ThaliTest[2330:2198759] client session: stateChange:0->1 Apple-Iphone6-1_PT5992.nsQaaA==
,2015-12-02 18:12:56.672 ThaliTest[2330:2199334] client session: connected
2015-12-02 18:12:56.673 ThaliTest[2330:2199334] client session: stateChange:1->2 Apple-Iphone6-1_PT5992.nsQaaA==
,2015-12-02 18:12:56.678 ThaliTest[2330:2199334] client session: fireConnectCallback: Apple-Iphone6-1_PT5992.nsQaaA==
2015-12-02 18:12:56.679 ThaliTest[2330:2199334] jxcore: connect: success
2015-12-02T17:12:56.680Z SendDataConnector.js: CLIENT connected ,to 49329, error: null
2015-12-02T17:12:56.680Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 18:12:56.685 ThaliTest[2330:2198644] client: relay established
2015-12-02 18:12:56.686 ThaliTest[2330:2198644] client: new accepted socket: 0x1882b7a0
,2015-12-02T17:12:56.698Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T17:12:57.008Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-02T17:12:57.021Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-02T17:12:57.072Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-02T17:12:57.083Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-02T17:12:57.083Z SendDataConnector.js: got all data for this round
,2015-12-02T17:12:57.084Z SendDataConnector.js: CLIENT Stop now
2015-12-02T17:12:57.084Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-02 18:12:57.084 ThaliTest[2330:2198759] jxcore: disconnect
2015-12-02 18:12:57.085 ThaliTest[2330:2198759] cli,ent session: disconnectFromPeer: Apple-Iphone6-1_PT5992.nsQaaA==
2015-12-02 18:12:57.085 ThaliTest[2330:2198759] client session: disconnect
2015-12-02 18:12:57.085 ThaliTest[2330:2198759] client session: stateChange:2->0 Apple-Iphone6-1_PT5992.nsQaaA==
,2015-12-02 18:12:57.087 ThaliTest[2330:2198759] jxcore: disconnect: success
2015-12-02T17:12:57.088Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT5992.nsQaaA==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT367","time":16634,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT2754.fr+caQ==","time":4181,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_,PT9787.rFc5Bg==","time":8381,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT5992.nsQaaA==","time":3544,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":10000,0}]}
,sendList : 100% : 8381 ms, 99% : 8381 ms, 95 : 8381 ms, 90% : 8381 ms.
,Result count 3, range 3544 ms to  8381 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-02T17:12:57.093Z SendDataConnector.js: CLIENT Stop now
,2015-12-02T17:12:57.093Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
2015-12-02 18:12:57.678 ThaliTest[2330:2198759] jxcore: stopBroadcasting
2015-12-02 18:12:57.679 ThaliTest[2330:2198759] THEMultipeerSession stopping peer
2015-12-02 18:12:57.681 ThaliTest[2330:21987,59] multipeer session: stop timer
2015-12-02 18:12:57.683 ThaliTest[2330:2198759] server session: disconnect
2015-12-02 18:12:57.684 ThaliTest[2330:2198759] server session: stateChange:2->0 Apple-Iphone6-1_PT5992
,2015-12-02 18:12:57.692 ThaliTest[2330:2198759] server session: disconnect
2015-12-02 18:12:57.693 ThaliTest[2330:2198759] server session: stateChange:2->0 Apple-Iphone5-1_PT9787
,2015-12-02 18:12:57.697 ThaliTest[2330:2198759] server session: disconnect
2015-12-02 18:12:57.698 ThaliTest[2330:2198759] server session: stateChange:2->0 Apple-IpadAir2-1_PT2754
2015-12-02 18:12:57.706 ThaliTest[2330:2198759] jxcore: stopBroadcasting: ,success
,StopBroadcasting went ok
,2015-12-02T17:12:57.731Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-02T17:12:57.733Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02T17:12:57.736Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02T17:12:57.737Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT5992.nsQaaA==\",\"time\":3544,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-IpadAir2-1_PT2754.fr+caQ==\",\"time\":4181,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-Iphone5-1_PT9787.rFc5Bg==\",\"time\":8381,\"result\":\"OK\",\"connections\":1,,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received

```
