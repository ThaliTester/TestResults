#### Test 5133502802397d9_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5133502802397d9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/3A310894-A8AE-433D-ABE9-01F4D5589C19/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/3A310894-A8AE-433D-ABE9-01F4D5589C19/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5133502802397d9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5133502802397d9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5F096305-C303-4D7A-B342-31BC2C19C627/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54799"
,(lldb)     command script import "/tmp/3A310894-A8AE-433D-ABE9-01F4D5589C19/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-24 17:02:55.145 ThaliTest[1227:1598027] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0ABF2166-A7D7-41D4-AAD1-306F4891FFB7/Library/Cookies/Cookies.binarycookies
,2015-11-24 17:02:55.447 ThaliTest[1227:1598027] Apache Cordova native platform version 3.9.2 is starting.
2015-11-24 17:02:55.447 ThaliTest[1227:1598027] Multi-tasking -> Device: YES, App: YES
,2015-11-24 17:02:55.453 ThaliTest[1227:1598027] Unlimited access to network resources
,2015-11-24 17:02:55.459 ThaliTest[1227:1598027] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-24 17:02:59.628 ThaliTest[1227:1598027] Resetting plugins due to page load.
,2015-11-24 17:03:01.113 ThaliTest[1227:1598027] Finished load of: file:///var/mobile/Containers/Bundle/Application/5F096305-C303-4D7A-B342-31BC2C19C627/ThaliTest.app/www/index.html
,2015-11-24 17:03:01.254 ThaliTest[1227:1598027] JXcore Cordova plugin initializing
,2015-11-24 17:03:01.255 ThaliTest[1227:1598232] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-IpadAir2-1_PT7208
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
,DBG, CoordinatorConnector connect_error called
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
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
serverPort is 61017
,2015-11-24 17:10:26.286 ThaliTest[1227:1598232] jxcore: startBroadcasting
,2015-11-24 17:10:26.292 ThaliTest[1227:1598232] server: starting Apple-IpadAir2-1_PT7208.gEcfnw==
2015-11-24 17:10:26.293 ThaliTest[1227:1598232] multipeer session: start timer: 0x90c04c0
,2015-11-24 17:10:26.293 ThaliTest[1227:1598232] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT7208
2015-11-24 17:10:26.293 ThaliTest[1227:1598232] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-11-24T16:10:26.294Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-24 17:10:26.859 ThaliTest[1227:1598027] client: found peer: Apple-Iphone6-1_PT1630.4rgQcA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1630.4rgQcA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT1630.4rgQcA==
2015-11-24T16:10:26.861Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT1630.4rgQcA==
,2015-11-24T16:10:26.862Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1630.4rgQcA==
,2015-11-24T16:10:26.862Z SendDataConnector.js: do connect now
,2015-11-24 17:10:26.862 ThaliTest[1227:1598232] jxcore: connect Apple-Iphone6-1_PT1630.4rgQcA==
,2015-11-24 17:10:26.863 ThaliTest[1227:1598232] client session: connect
2015-11-24 17:10:26.863 ThaliTest[1227:1598232] client session: stateChange:0->1 Apple-Iphone6-1_PT1630.4rgQcA==
,2015-11-24 17:10:27.409 ThaliTest[1227:1598027] client: found peer: Apple-Iphone5s-1_PT8445.HcGyQA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8445.HcGyQA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-24 17:10:28.129 ThaliTest[1227:1598027] client: found peer: Apple-Iphone5-1_PT7498.cV5UxA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT7498.cV5UxA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-11-24 17:10:30.162 ThaliTest[1227:1598962] client session: connected
2015-11-24 17:10:30.162 ThaliTest[1227:1598962] client session: stateChange:1->2 Apple-Iphone6-1_PT1630.4rgQcA==
,2015-11-24 17:10:30.164 ThaliTest[1227:1598962] client session: fireConnectCallback: Apple-Iphone6-1_PT1630.4rgQcA==
2015-11-24 17:10:30.164 ThaliTest[1227:1598962] jxcore: connect: success
2015-11-24T16:10:30.165Z SendDataConnector.js: CLIENT connected to 61020, error: null
2015-11-24T16:10:30.165Z SendDataConnector.js: CLIENT starting client 
,2015-11-24 17:10:30.166 ThaliTest[1227:1598027] client: relay established
2015-11-24 17:10:30.166 ThaliTest[1227:1598027] client: new accepted socket: 0x90c4830
,2015-11-24T16:10:30.179Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-24T16:10:30.244Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-24T16:10:30.257Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-24T16:10:30.257Z SendDataConnector.js: got all data for this round
,2015-11-24T16:10:30.258Z SendDataConnector.js: CLIENT Stop now
,2015-11-24T16:10:30.259Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-24 17:10:30.260 ThaliTest[1227:1598232] jxcore: disconnect
2015-11-24 17:10:30.260 ThaliTest[1227:1598232] client session: disconnectFromPeer: Apple-Iphone6-1_PT1630.4rgQcA==
2015-11-24 17:10:30.260 ThaliTest[1227:1598232] client session: disconn,ect
2015-11-24 17:10:30.260 ThaliTest[1227:1598232] client session: stateChange:2->0 Apple-Iphone6-1_PT1630.4rgQcA==
,2015-11-24 17:10:30.264 ThaliTest[1227:1598232] jxcore: disconnect: success
2015-11-24T16:10:30.265Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1630.4rgQcA==
---- round done--------
,device[2]: Apple-Iphone5s-1_PT8445.HcGyQA==
2015-11-24T16:10:30.267Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8445.HcGyQA==
2015-11-24T16:10:30.267Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8445.HcGyQA==
2015-11-24T16:10:30.267Z SendDataConnector.js: do connect now
2015-11-24 17:10:30.267 ThaliTest[1227:1598232] jxcore: connect Apple-Iphone5s-1_PT8445.HcGyQA==
,2015-11-24 17:10:30.267 ThaliTest[1227:1598232] client session: connect
2015-11-24 17:10:30.268 ThaliTest[1227:1598232] client session: stateChange:0->1 Apple-Iphone5s-1_PT8445.HcGyQA==
,2015-11-24 17:10:30.652 ThaliTest[1227:1598027] multipeer session: reset timer
2015-11-24 17:10:30.652 ThaliTest[1227:1598027] multipeer session: stop timer
2015-11-24 17:10:30.652 ThaliTest[1227:1598027] multipeer session: start timer: 0x90c04c0
2015-1,1-24 17:10:30.652 ThaliTest[1227:1598027] server session: connect
2015-11-24 17:10:30.652 ThaliTest[1227:1598027] server session: stateChange:0->1 Apple-Iphone5s-1_PT8445
2015-11-24 17:10:30.654 ThaliTest[1227:1598027] server: accepting invitation Apple-Iphone5s-1_PT8445
,2015-11-24 17:10:30.771 ThaliTest[1227:1598027] multipeer session: reset timer
2015-11-24 17:10:30.771 ThaliTest[1227:1598027] multipeer session: stop timer
2015-11-24 17:10:30.771 ThaliTest[1227:1598027] multipeer session: start timer: 0x90c04c0
2015-11-24 17:10:30.771 ThaliTest[1227:1598027] server session: connect
2015-11-24 17:10:30.771 ThaliTest[1227:1598027] server session: stateChange:0->1 Apple-Iphone6-1_PT1630
2015-11-24 17:10:30.774 ThaliTest[1227:1598027] server: accepting invitation Apple-Iphone6-1_PT1630
,2015-11-24 17:10:33.868 ThaliTest[1227:1599000] server session: connected
2015-11-24 17:10:33.868 ThaliTest[1227:1599000] server session: stateChange:1->2 Apple-Iphone6-1_PT1630
,2015-11-24 17:10:33.872 ThaliTest[1227:1598027] server relay: connected (to port: 61017)
,2015-11-24T16:10:33.877Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-24T16:10:34.140Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-11-24T16:10:34.154Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-24 17:10:34.395 ThaliTest[1227:1598961] client session: connected
2015-11-24 17:10:34.396 ThaliTest[1227:1598961] client session: stateChange:1->2 Apple-Iphone5s-1_PT8445.HcGyQA==
,2015-11-24 17:10:34.399 ThaliTest[1227:1598962] server session: not connected Apple-Iphone6-1_PT1630
2015-11-24 17:10:34.401 ThaliTest[1227:1598955] server session: connected
2015-11-24 17:10:34.401 ThaliTest[1227:1598955] server session: stateChange:1->2 Apple-Iphone5s-1_PT8445
2015-11-24 17:10:34.401 ThaliTest[1227:1598961] client session: fireConnectCallback: Apple-Iphone5s-1_PT8445.HcGyQA==
2015-11-24 17:10:34.401 ThaliTest[1227:1598961] jxcore: connect: success
,2015-11-24T16:10:34.403Z SendDataConnector.js: CLIENT connected to 61025, error: null
2015-11-24T16:10:34.403Z SendDataConnector.js: CLIENT starting client 
,2015-11-24 17:10:34.404 ThaliTest[1227:1598027] client: relay established
2015-11-24 17:10:34.404 ThaliTest[1227:1598027] client: new accepted socket: 0x5633820
,2015-11-24 17:10:34.406 ThaliTest[1227:1598027] server relay: connected (to port: 61017)
,2015-11-24T16:10:34.416Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-24T16:10:34.417Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-24T16:10:34.974Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-11-24 17:10:35.192 ThaliTest[1227:1598027] multipeer session: reset timer
,2015-11-24 17:10:35.192 ThaliTest[1227:1598027] multipeer session: stop timer
2015-11-24 17:10:35.192 ThaliTest[1227:1598027] multipeer session: start timer: 0x90c04c0
2015-11-24 17:10:35.192 ThaliTest[1227:1598027] server session: connect
2015-11-24 17:10:35.192 ThaliTest[1227:1598027] server session: stateChange:0->1 Apple-Iphone5-1_PT7498
,2015-11-24 17:10:35.195 ThaliTest[1227:1598027] server: accepting invitation Apple-Iphone5-1_PT7498
,2015-11-24T16:10:35.222Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-11-24T16:10:35.237Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-24T16:10:35.238Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-24T16:10:35.252Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-24 17:10:35.472 ThaliTest[1227:1599000] server session: not connected Apple-Iphone5s-1_PT8445
,2015-11-24T16:10:35.476Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-24T16:10:35.477Z SendDataConnector.js: got all data for this round
,2015-11-24T16:10:35.478Z SendDataConnector.js: CLIENT Stop now
2015-11-24T16:10:35.478Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-24 17:10:35.478 ThaliTest[1227:1598232] jxcore: disconnect
2015-11-24 17:10:35.479 ThaliTest[1227:1598232] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8445.HcGyQA==
2015-11-24 17:10:35.479 ThaliTest[1227:1598232] client session: disconnect
2015-11-24 17:10:35.479 ThaliTest[1227:1598232] client session: stateChange:2->0 Apple-Iphone5s-1_PT8445.HcGyQA==
,2015-11-24 17:10:35.483 ThaliTest[1227:1598232] jxcore: disconnect: success
2015-11-24T16:10:35.484Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8445.HcGyQA==
---- round done--------
device[3]: Apple-Iphone5-1_PT7498.cV5UxA==
2015-11-24T16:10:35.484Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT7498.cV5UxA==
2015-11-24T16:10:35.484Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT7498.cV5UxA==
2015-11-24T16:10:35.485Z SendDataConnector.js: do connect now
2015-11-24 17:10:35.485 ThaliTest[1227:1598232] jxcore: connect Apple-Iphone5-1_PT7498.cV5UxA==
2015-11-24 17:10:35.485 ThaliTest[1227:1598232] client session: connect
,2015-11-24 17:10:35.485 ThaliTest[1227:1598232] client session: stateChange:0->1 Apple-Iphone5-1_PT7498.cV5UxA==
,2015-11-24 17:10:40.425 ThaliTest[1227:1598999] server session: connected
2015-11-24 17:10:40.425 ThaliTest[1227:1598999] server session: stateChange:1->2 Apple-Iphone5-1_PT7498
,2015-11-24 17:10:40.427 ThaliTest[1227:1598027] server relay: connected (to port: 61017)
,2015-11-24T16:10:40.433Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-24 17:10:40.438 ThaliTest[1227:1598961] client session: connected
2015-11-24 17:10:40.439 ThaliTest[1227:1598961] client session: stateChange:1->2 Apple-Iphone5-1_PT7498.cV5UxA==
,2015-11-24 17:10:40.703 ThaliTest[1227:1598999] client session: fireConnectCallback: Apple-Iphone5-1_PT7498.cV5UxA==
2015-11-24 17:10:40.703 ThaliTest[1227:1598999] jxcore: connect: success
,2015-11-24T16:10:40.704Z SendDataConnector.js: CLIENT connected to 61030, error: null
2015-11-24T16:10:40.704Z SendDataConnector.js: CLIENT starting client 
,2015-11-24 17:10:40.705 ThaliTest[1227:1598027] client: relay established
2015-11-24 17:10:40.705 ThaliTest[1227:1598027] client: new accepted socket: 0x5647550
,2015-11-24T16:10:40.719Z SendDataTCPServer.js: TCP/IP server has received 5952 bytes of data
2015-11-24T16:10:40.719Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-24T16:10:40.776Z SendDataTCPServer.js: TCP/IP server has received 6944 bytes of data
,2015-11-24T16:10:41.010Z SendDataTCPServer.js: TCP/IP server has received 16864 bytes of data
,2015-11-24T16:10:41.023Z SendDataTCPServer.js: TCP/IP server has received 28768 bytes of data
,2015-11-24T16:10:41.046Z SendDataTCPServer.js: TCP/IP server has received 29760 bytes of data
,2015-11-24T16:10:41.071Z SendDataTCPServer.js: TCP/IP server has received 30752 bytes of data
,2015-11-24T16:10:41.097Z SendDataTCPServer.js: TCP/IP server has received 44640 bytes of data
,2015-11-24T16:10:41.108Z SendDataTCPServer.js: TCP/IP server has received 58528 bytes of data
,2015-11-24T16:10:41.134Z SendDataTCPServer.js: TCP/IP server has received 59520 bytes of data
,2015-11-24T16:10:41.149Z SendDataTCPServer.js: TCP/IP server has received 62496 bytes of data
,2015-11-24T16:10:41.610Z SendDataTCPServer.js: TCP/IP server has received 65472 bytes of data
,2015-11-24T16:10:41.636Z SendDataTCPServer.js: TCP/IP server has received 66464 bytes of data
,2015-11-24T16:10:41.649Z SendDataTCPServer.js: TCP/IP server has received 67456 bytes of data
,2015-11-24T16:10:41.662Z SendDataTCPServer.js: TCP/IP server has received 73408 bytes of data
,2015-11-24T16:10:41.675Z SendDataTCPServer.js: TCP/IP server has received 84320 bytes of data
,2015-11-24T16:10:41.688Z SendDataTCPServer.js: TCP/IP server has received 86304 bytes of data
,2015-11-24T16:10:41.738Z SendDataTCPServer.js: TCP/IP server has received 92256 bytes of data
,2015-11-24T16:10:42.002Z SendDataTCPServer.js: TCP/IP server has received 97216 bytes of data
,2015-11-24T16:10:42.015Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-24 17:10:42.188 ThaliTest[1227:1598962] server session: not connected Apple-Iphone5-1_PT7498
,2015-11-24T16:10:42.195Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-24T16:10:42.208Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-24T16:10:42.517Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-24T16:10:42.530Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-24T16:10:42.531Z SendDataConnector.js: got all data for this round
,2015-11-24T16:10:42.531Z SendDataConnector.js: CLIENT Stop now
2015-11-24T16:10:42.531Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-24 17:10:42.532 ThaliTest[1227:1598232] jxcore: disconnect
2015-11-24 17:10:42.532 ThaliTest[1227:1598232] client session: disconnectFromPeer: Apple-Iphone5-1_PT7498.cV5UxA==
2015-11-24 17:10:42.532 ThaliTest[1227:1598232] client session: disconnect
2015-11-24 17:10:42.532 ThaliTest[1227:1598232] client session: stateChange:2->0 Apple-Iphone5-1_PT7498.cV5UxA==
,2015-11-24 17:10:42.537 ThaliTest[1227:1598232] jxcore: disconnect: success
2015-11-24T16:10:42.537Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT7498.cV5UxA==
---- round done--------
weAreDoneNow , resultArray.length: ,3
done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT7208","time":16256,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT1630.4rgQcA==","time":3397,"result":"OK","connections":1},{"name":"Apple-Iphone5s-1_PT8445.HcGyQA==","time":5210,"result":"OK","connections",:1},{"name":"Apple-Iphone5-1_PT7498.cV5UxA==","time":7047,"result":"OK","connections":1}]}
sendList : 100% : 7047 ms, 99% : 7047 ms, 95 : 7047 ms, 90% : 7047 ms.
Result count 3, range 3397 ms to  7047 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-11-24T16:10:42.541Z SendDataConnector.js: CLIENT Stop now
2015-11-24T16:10:42.541Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector command called
command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-24 17:10:43.566 ThaliTest[1227:1598232] jxcore: stopBroadcasting
2015-11-24 17:10:43.566 ThaliTest[1227:1598232] THEMultipeerSession stopping peer
2015-11-24 17:10:43.566 ThaliTest[1227:1598232] multipeer session: stop timer
2015-11-24 17:10:43.566 ThaliTest[1227:1598232] server session: disconnect
2015-11-24 17:10:43.567 ThaliTest[1227:1598232] server session: stateChange:2->0 Apple-Iphone5-1_PT7498
,2015-11-24 17:10:43.571 ThaliTest[1227:1598232] server session: disconnect
2015-11-24 17:10:43.571 ThaliTest[1227:1598232] server session: stateChange:2->0 Apple-Iphone5s-1_PT8445
,2015-11-24 17:10:43.576 ThaliTest[1227:1598232] server session: disconnect
2015-11-24 17:10:43.576 ThaliTest[1227:1598232] server session: stateChange:2->0 Apple-Iphone6-1_PT1630
,2015-11-24 17:10:43.581 ThaliTest[1227:1598232] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-11-24T16:10:43.597Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-24T16:10:43.597Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-24T16:10:43.597Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-24T16:10:43.598Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT1630.4rgQcA==\",\"time\":3397,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT8445.HcGyQA==\",\"time\":5210,\",result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT7498.cV5UxA==\",\"time\":7047,\"result\":\"OK\",\"connections\":1}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT1630.4rgQc,A==\",\"time\":2721,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT8445.HcGyQA==\",\"time\":2803,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT7498.cV5UxA==\",\"time\":2871,\"result\":\"OK\",\"connections\":1},{\"n,ame\":\"Apple-Iphone6-1_PT1630.4rgQcA==\",\"time\":2935,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT8445.HcGyQA==\",\"time\":3022,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT1630.4rgQcA==\",\"time\":3397,\"res,ult\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT7498.cV5UxA==\",\"time\":3428,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7208.gEcfnw==\",\"time\":4431,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_,PT8445.HcGyQA==\",\"time\":5210,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7208.gEcfnw==\",\"time\":5907,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT7498.cV5UxA==\",\"time\":7047,\"result\":\"OK\",\"connectio,ns\":1},{\"name\":\"Apple-IpadAir2-1_PT7208.gEcfnw==\",\"time\":9136,\"result\":\"OK\",\"connections\":1}]}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called

```
