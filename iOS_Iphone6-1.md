#### Test 51986340a77003b_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51986340a77003b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F064B3F9-E209-4273-92C9-311788D9A85A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F064B3F9-E209-4273-92C9-311788D9A85A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51986340a77003b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51986340a77003b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9F165FE9-782C-46C7-AA00-0CCBC73D64FC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57919"
,(lldb)     command script import "/tmp/F064B3F9-E209-4273-92C9-311788D9A85A/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-30 10:46:27.860 ThaliTest[2146:1837108] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/99C0FE1F-CB5F-42CC-B271-BDA495CC881D/Library/Cookies/Cookies.binarycookies
,2015-11-30 10:46:28.263 ThaliTest[2146:1837108] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-30 10:46:28.264 ThaliTest[2146:1837108] Multi-tasking -> Device: YES, App: YES
,2015-11-30 10:46:28.272 ThaliTest[2146:1837108] Unlimited access to network resources
,2015-11-30 10:46:28.278 ThaliTest[2146:1837108] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-30 10:46:31.975 ThaliTest[2146:1837108] Resetting plugins due to page load.
,2015-11-30 10:46:32.323 ThaliTest[2146:1837108] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/9F165FE9-782C-46C7-AA00-0CCBC73D64FC/ThaliTest.app/www/index.html
,2015-11-30 10:46:32.448 ThaliTest[2146:1837108] JXcore Cordova plugin initializing
,2015-11-30 10:46:32.449 ThaliTest[2146:1837252] JXcore instance initializing
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
,my name is : Apple-Iphone6-1_PT7971
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
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":50000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":50000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 63457
,2015-11-30 10:53:32.216 ThaliTest[2146:1837252] jxcore: startBroadcasting
,2015-11-30 10:53:32.227 ThaliTest[2146:1837252] server: starting Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:53:32.229 ThaliTest[2146:1837252] multipeer session: start timer: 0x1b5aa120
2015-11-30 10:53:32.229 ThaliTest[2146:1837252] THEMultipeerSession initialized peer Apple-Iphone6-1_PT7971
2015-11-30 10:53:32.230 ThaliTest[2146:1837252] jxcore: startBroadcasting: success
,StartBroadcasting started ok
2015-11-30T09:53:32.238Z SendDataTCPServer.js: TCP/IP server is bound to port: 63457
,2015-11-30 10:53:32.500 ThaliTest[2146:1837108] client: found peer: Apple-Iphone5s-1_PT9746.l6NbbA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9746.l6NbbA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT9746.l6NbbA==
2015-11-30T09:53:32.503Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT9746.l6NbbA==
,2015-11-30T09:53:32.503Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9746.l6NbbA==
2015-11-30T09:53:32.503Z SendDataConnector.js: do connect now
,2015-11-30 10:53:32.504 ThaliTest[2146:1837252] jxcore: connect Apple-Iphone5s-1_PT9746.l6NbbA==
2015-11-30 10:53:32.504 ThaliTest[2146:1837252] client session: connect
2015-11-30 10:53:32.504 ThaliTest[2146:1837252] client session: stateChange:0->1 Apple-Iphone5s-1_PT9746.l6NbbA==
,2015-11-30 10:53:32.900 ThaliTest[2146:1837108] multipeer session: reset timer
2015-11-30 10:53:32.900 ThaliTest[2146:1837108] multipeer session: stop timer
2015-11-30 10:53:32.901 ThaliTest[2146:1837108] multipeer session: start timer: 0x1b5aa120
2015-11-30 10:53:32.902 ThaliTest[2146:1837108] server session: connect
2015-11-30 10:53:32.902 ThaliTest[2146:1837108] server session: stateChange:0->1 Apple-IpadAir2-1_PT7551
,2015-11-30 10:53:32.909 ThaliTest[2146:1837108] server: accepting invitation Apple-IpadAir2-1_PT7551
,2015-11-30 10:53:33.089 ThaliTest[2146:1837108] multipeer session: reset timer
2015-11-30 10:53:33.089 ThaliTest[2146:1837108] multipeer session: stop timer
2015-11-30 10:53:33.089 ThaliTest[2146:1837108] multipeer session: start timer: 0x1b5aa120
2015-11-30 10:53:33.090 ThaliTest[2146:1837108] server session: connect
2015-11-30 10:53:33.090 ThaliTest[2146:1837108] server session: stateChange:0->1 Apple-Iphone5-1_PT2135
,2015-11-30 10:53:33.093 ThaliTest[2146:1837108] server: accepting invitation Apple-Iphone5-1_PT2135
,2015-11-30 10:53:33.873 ThaliTest[2146:1837108] multipeer session: reset timer
2015-11-30 10:53:33.874 ThaliTest[2146:1837108] multipeer session: stop timer
2015-11-30 10:53:33.874 ThaliTest[2146:1837108] multipeer session: start timer: 0x1b5aa120
2015-11-30 10:53:33.874 ThaliTest[2146:1837108] server session: connect
2015-11-30 10:53:33.874 ThaliTest[2146:1837108] server session: stateChange:0->1 Apple-Iphone5s-1_PT9746
,2015-11-30 10:53:33.877 ThaliTest[2146:1837108] server: accepting invitation Apple-Iphone5s-1_PT9746
,2015-11-30 10:53:34.197 ThaliTest[2146:1837108] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7551.0H/lSg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
2015-11-30 10:53:34.201 ThaliTest[2146:1837108] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2135.SJMPng==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Availab,le: true
,2015-11-30 10:53:35.000 ThaliTest[2146:1837819] client session: connected
2015-11-30 10:53:35.001 ThaliTest[2146:1837819] client session: stateChange:1->2 Apple-Iphone5s-1_PT9746.l6NbbA==
,2015-11-30 10:53:35.012 ThaliTest[2146:1837830] client session: fireConnectCallback: Apple-Iphone5s-1_PT9746.l6NbbA==
2015-11-30 10:53:35.013 ThaliTest[2146:1837830] jxcore: connect: success
,2015-11-30T09:53:35.018Z SendDataConnector.js: CLIENT connected to 63460, error: null
,2015-11-30T09:53:35.019Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 10:53:35.025 ThaliTest[2146:1837108] client: relay established
2015-11-30 10:53:35.025 ThaliTest[2146:1837108] client: new accepted socket: 0x1b113230
,2015-11-30T09:53:35.038Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-30 10:53:35.249 ThaliTest[2146:1837819] server session: connected
2015-11-30 10:53:35.250 ThaliTest[2146:1837819] server session: stateChange:1->2 Apple-Iphone5-1_PT2135
,2015-11-30 10:53:35.260 ThaliTest[2146:1837108] server relay: connected (to port: 63457)
,2015-11-30T09:53:35.316Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30T09:53:35.442Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-30 10:53:35.494 ThaliTest[2146:1837864] server session: connected
2015-11-30 10:53:35.494 ThaliTest[2146:1837864] server session: stateChange:1->2 Apple-IpadAir2-1_PT7551
,2015-11-30 10:53:35.508 ThaliTest[2146:1837108] server relay: connected (to port: 63457)
,2015-11-30T09:53:35.517Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-30T09:53:35.517Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30T09:53:35.530Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-30T09:53:35.531Z SendDataConnector.js: got all data for this round
,2015-11-30T09:53:35.532Z SendDataConnector.js: CLIENT Stop now
2015-11-30T09:53:35.532Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-30 10:53:35.533 ThaliTest[2146:1837252] jxcore: disconnect
2015-11-30 10:53:35.533 ThaliTest[2146:1837252] cli,ent session: disconnectFromPeer: Apple-Iphone5s-1_PT9746.l6NbbA==
2015-11-30 10:53:35.533 ThaliTest[2146:1837252] client session: disconnect
2015-11-30 10:53:35.533 ThaliTest[2146:1837252] client session: stateChange:2->0 Apple-Iphone5s-1_PT9746.l6NbbA==
,2015-11-30 10:53:35.535 ThaliTest[2146:1837252] jxcore: disconnect: success
2015-11-30T09:53:35.536Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9746.l6NbbA==
---- round done--------
,device[2]: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30T09:53:35.537Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7551.0H/lSg==
2015-11-30T09:53:35.538Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7551.0H/lSg==
2015-11-30T09:53:35.538Z SendDataConnector.js: do connect now
,2015-11-30 10:53:35.538 ThaliTest[2146:1837252] jxcore: connect Apple-IpadAir2-1_PT7551.0H/lSg==
2015-11-30 10:53:35.539 ThaliTest[2146:1837252] client session: connect
2015-11-30 10:53:35.539 ThaliTest[2146:1837252] client session: stateChange:0->1 Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30T09:53:35.772Z SendDataTCPServer.js: TCP/IP server has received 16864 bytes of data
,2015-11-30T09:53:35.786Z SendDataTCPServer.js: TCP/IP server has received 36704 bytes of data
,2015-11-30T09:53:35.800Z SendDataTCPServer.js: TCP/IP server has received 62496 bytes of data
,2015-11-30T09:53:35.812Z SendDataTCPServer.js: TCP/IP server has received 80352 bytes of data
,2015-11-30T09:53:35.825Z SendDataTCPServer.js: TCP/IP server has received 83328 bytes of data
,2015-11-30T09:53:35.979Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-11-30T09:53:35.992Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
2015-11-30T09:53:35.995Z SendDataTCPServer.js: TCP/IP server has received 94240 bytes of data
,2015-11-30T09:53:36.008Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-30 10:53:36.041 ThaliTest[2146:1837841] server session: connected
2015-11-30 10:53:36.042 ThaliTest[2146:1837841] server session: stateChange:1->2 Apple-Iphone5s-1_PT9746
,2015-11-30 10:53:36.056 ThaliTest[2146:1837108] server relay: connected (to port: 63457)
2015-11-30T09:53:36.057Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30T09:53:36.146Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-30T09:53:36.486Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-11-30T09:53:36.502Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-11-30T09:53:36.518Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-11-30T09:53:36.536Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-30 10:53:36.565 ThaliTest[2146:1837864] server session: not connected Apple-Iphone5s-1_PT9746
,2015-11-30 10:53:39.176 ThaliTest[2146:1837830] client session: connected
,2015-11-30 10:53:39.177 ThaliTest[2146:1837830] client session: stateChange:1->2 Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 10:53:39.508 ThaliTest[2146:1837841] client session: fireConnectCallback: Apple-IpadAir2-1_PT7551.0H/lSg==
2015-11-30 10:53:39.509 ThaliTest[2146:1837841] jxcore: connect: success
2015-11-30T09:53:39.510Z SendDataConnector.js: CLIENT connected, to 63466, error: null
2015-11-30T09:53:39.511Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 10:53:39.515 ThaliTest[2146:1837108] client: relay established
2015-11-30 10:53:39.516 ThaliTest[2146:1837108] client: new accepted socket: 0x1b5cff70
,2015-11-30T09:53:39.528Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-30T09:53:40.034Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-30T09:53:40.045Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-30T09:53:40.071Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-30T09:53:40.071Z SendDataConnector.js: got all data for this round
,2015-11-30T09:53:40.072Z SendDataConnector.js: CLIENT Stop now
2015-11-30T09:53:40.072Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-30 10:53:40.073 ThaliTest[2146:1837252] jxcore: disconnect
,2015-11-30 10:53:40.073 ThaliTest[2146:1837252] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7551.0H/lSg==
2015-11-30 10:53:40.073 ThaliTest[2146:1837252] client session: disconnect
2015-11-30 10:53:40.073 ThaliTest[2146:1837252] client session: stateChange:2->0 Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 10:53:40.076 ThaliTest[2146:1837252] jxcore: disconnect: success
2015-11-30T09:53:40.076Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7551.0H/lSg==
---- round done--------
,device[3]: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30T09:53:40.079Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2135.SJMPng==
2015-11-30T09:53:40.079Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2135.SJMPng==
2015-11-30T09:53:40.079Z SendDataConnector.js: do connect now
,2015-11-30 10:53:40.079 ThaliTest[2146:1837252] jxcore: connect Apple-Iphone5-1_PT2135.SJMPng==
2015-11-30 10:53:40.080 ThaliTest[2146:1837252] client session: connect
2015-11-30 10:53:40.080 ThaliTest[2146:1837252] client session: stateChange:0->1 Apple,-Iphone5-1_PT2135.SJMPng==
,2015-11-30 10:53:43.411 ThaliTest[2146:1837825] client session: connected
2015-11-30 10:53:43.411 ThaliTest[2146:1837825] client session: stateChange:1->2 Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 10:53:43.421 ThaliTest[2146:1837819] client session: fireConnectCallback: Apple-Iphone5-1_PT2135.SJMPng==
2015-11-30 10:53:43.422 ThaliTest[2146:1837819] jxcore: connect: success
2015-11-30T09:53:43.423Z SendDataConnector.js: CLIENT connected to 63472, error: null
,2015-11-30T09:53:43.424Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 10:53:43.427 ThaliTest[2146:1837108] client: relay established
2015-11-30 10:53:43.428 ThaliTest[2146:1837108] client: new accepted socket: 0x16d90960
,2015-11-30T09:53:43.439Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-30T09:53:43.877Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-30T09:53:43.889Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-30T09:53:44.251Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-30T09:53:44.252Z SendDataConnector.js: got all data for this round
,2015-11-30T09:53:44.253Z SendDataConnector.js: CLIENT Stop now
2015-11-30T09:53:44.254Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 10:53:44.255 ThaliTest[2146:1837252] jxcore: disconnect
2015-11-30 10:53:44.255 ThaliTest[2146:1837252] client session: disconnectFromPeer: Apple-Iphone5-1_PT2135.SJMPng==
2015-11-30 10:53:44.256 ThaliTest[2146:1837252] client session: disconn,ect
2015-11-30 10:53:44.257 ThaliTest[2146:1837252] client session: stateChange:2->0 Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 10:53:44.259 ThaliTest[2146:1837252] jxcore: disconnect: success
2015-11-30T09:53:44.260Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2135.SJMPng==
---- round done--------
weAreDoneNow , resultArray.length: ,3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT7971","time":12070,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT9746.l6NbbA==","time":3028,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1,_PT7551.0H/lSg==","time":4534,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT2135.SJMPng==","time":4173,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 4534 ms, 99% : 4534 ms, 95 : 4534 ms, 90% : 4534 ms.
,Result count 3, range 3028 ms to  4534 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-11-30T09:53:44.279Z SendDataConnector.js: CLIENT Stop now
,2015-11-30T09:53:44.279Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 10:54:03.875 ThaliTest[2146:1837108] multipeer session: restart
,2015-11-30 10:54:03.897 ThaliTest[2146:1837108] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
2015-11-30 10:54:03.898 ThaliTest[2146:1837108] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
2015-11-30 10:54:03.899 ThaliTest[2146:1837108] client: found peer: Apple-Iphone5s-1_PT9746.l6NbbA==
,2015-11-30 10:54:26.156 ThaliTest[2146:1837825] server session: not connected Apple-IpadAir2-1_PT7551
,2015-11-30 10:54:26.170 ThaliTest[2146:1837825] server session: not connected Apple-Iphone5-1_PT2135
,2015-11-30 10:54:33.875 ThaliTest[2146:1837108] multipeer session: restart
,2015-11-30 10:54:33.893 ThaliTest[2146:1837108] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
2015-11-30 10:54:33.895 ThaliTest[2146:1837108] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 10:54:36.178 ThaliTest[2146:1837108] multipeer session: reset timer
2015-11-30 10:54:36.179 ThaliTest[2146:1837108] multipeer session: stop timer
2015-11-30 10:54:36.180 ThaliTest[2146:1837108] multipeer session: start timer: 0x1b5aa120
2015-,11-30 10:54:36.181 ThaliTest[2146:1837108] server: disconnecting to refresh session (Apple-Iphone5-1_PT2135)
2015-11-30 10:54:36.181 ThaliTest[2146:1837108] server session: disconnect
2015-11-30 10:54:36.182 ThaliTest[2146:1837108] server session: stateC,hange:2->0 Apple-Iphone5-1_PT2135
2015-11-30 10:54:36.186 ThaliTest[2146:1837108] server session: connect
2015-11-30 10:54:36.188 ThaliTest[2146:1837108] server session: stateChange:0->1 Apple-Iphone5-1_PT2135
,2015-11-30T09:54:36.199Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-30 10:54:36.204 ThaliTest[2146:1837108] server: accepting invitation Apple-Iphone5-1_PT2135
,2015-11-30 10:54:38.377 ThaliTest[2146:1837964] server session: connected
2015-11-30 10:54:38.378 ThaliTest[2146:1837964] server session: stateChange:1->2 Apple-Iphone5-1_PT2135
,2015-11-30 10:54:38.388 ThaliTest[2146:1837108] server relay: connected (to port: 63457)
2015-11-30T09:54:38.390Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30T09:54:38.541Z SendDataTCPServer.js: TCP/IP server has received 8928 bytes of data
,2015-11-30T09:54:38.560Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-30 10:55:06.182 ThaliTest[2146:1837108] multipeer session: restart
2015-11-30 10:55:06.187 ThaliTest[2146:1837108] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Fi,rst throw call stack:
(0x26e2efef 0x35798c8b 0x26d4aaa3 0x28e09d85 0x26932607 0x26931e81 0x268ab3d3 0x26df4faf 0x26df43bf 0x26df2a25 0x26d3f201 0x26d3f013 0x2e7ca201 0x2a50ba09 0xe35e3 0x35d4aaaf)
libc++abi.dylib: terminating with uncaught exception of t,ype NSException
,* thread #1: tid = 0x1c0834, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
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
    frame #13: 0x000e35e2 ThaliTest`main + 50

```
