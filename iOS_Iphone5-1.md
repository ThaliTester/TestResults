#### Test 51335028c93db41_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51335028c93db41/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/0F099B67-ED28-418F-9F97-E085ED67C053/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/0F099B67-ED28-418F-9F97-E085ED67C053/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51335028c93db41/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51335028c93db41/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/FD21C8DA-5E76-47AC-A7C7-0C870AC1D1FC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55486"
,(lldb)     command script import "/tmp/0F099B67-ED28-418F-9F97-E085ED67C053/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-25 13:45:57.827 ThaliTest[777:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-25 13:45:57.831 ThaliTest[777:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-25 13:45:57.838 ThaliTest[777:60b] Unlimited access to network resources
,2015-11-25 13:45:57.844 ThaliTest[777:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.appl,e.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-25 13:46:08.563 ThaliTest[777:60b] Resetting plugins due to page load.
,2015-11-25 13:46:09.440 ThaliTest[777:60b] Finished load of: file:///var/mobile/Applications/FD21C8DA-5E76-47AC-A7C7-0C870AC1D1FC/ThaliTest.app/www/index.html
,2015-11-25 13:46:09.618 ThaliTest[777:60b] JXcore Cordova plugin initializing
,2015-11-25 13:46:09.620 ThaliTest[777:6907] JXcore instance initializing
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
,my name is : Apple-Iphone5-1_PT9701
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
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 64266
,2015-11-25 13:53:10.253 ThaliTest[777:6907] jxcore: startBroadcasting
,2015-11-25 13:53:10.266 ThaliTest[777:6907] server: starting Apple-Iphone5-1_PT9701.GagVHA==
2015-11-25 13:53:10.270 ThaliTest[777:6907] multipeer session: start timer: 0x1cf8c950
2015-11-25 13:53:10.271 ThaliTest[777:6907] THEMultipeerSession initialize,d peer Apple-Iphone5-1_PT9701
2015-11-25 13:53:10.272 ThaliTest[777:6907] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-11-25T12:53:10.275Z SendDataTCPServer.js: TCP/IP server is bound to port: 64266
,2015-11-25 13:53:10.483 ThaliTest[777:60b] client: found peer: Apple-Iphone6-1_PT8750.Du3EhQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8750.Du3EhQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT8750.Du3EhQ==
2015-11-25T12:53:10.487Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8750.Du3EhQ==
,2015-11-25T12:53:10.488Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8750.Du3EhQ==
2015-11-25T12:53:10.488Z SendDataConnector.js: do connect now
,2015-11-25 13:53:10.488 ThaliTest[777:6907] jxcore: connect Apple-Iphone6-1_PT8750.Du3EhQ==
,2015-11-25 13:53:10.489 ThaliTest[777:6907] client session: connect
,2015-11-25 13:53:10.489 ThaliTest[777:6907] client session: stateChange:0->1 Apple-Iphone6-1_PT8750.Du3EhQ==
,2015-11-25 13:53:10.901 ThaliTest[777:60b] client: found peer: Apple-Iphone5s-1_PT5807.1C0pWw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5807.1C0pWw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-25 13:53:11.250 ThaliTest[777:60b] client: found peer: Apple-IpadAir2-1_PT7357.1lZx3Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7357.1lZx3Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-25 13:53:12.897 ThaliTest[777:7c07] client session: connected
,2015-11-25 13:53:12.898 ThaliTest[777:7c07] client session: stateChange:1->2 Apple-Iphone6-1_PT8750.Du3EhQ==
,2015-11-25 13:53:12.909 ThaliTest[777:7c07] client session: fireConnectCallback: Apple-Iphone6-1_PT8750.Du3EhQ==
,2015-11-25 13:53:12.910 ThaliTest[777:7c07] jxcore: connect: success
,2015-11-25T12:53:12.912Z SendDataConnector.js: CLIENT connected to 64269, error: null
,2015-11-25T12:53:12.912Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 13:53:12.914 ThaliTest[777:60b] client: relay established
,2015-11-25 13:53:12.915 ThaliTest[777:60b] client: new accepted socket: 0x1cef2260
,2015-11-25T12:53:12.925Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T12:53:13.086Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-25T12:53:13.099Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-25T12:53:13.122Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-25T12:53:13.146Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-25T12:53:13.158Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T12:53:13.159Z SendDataConnector.js: got all data for this round
,2015-11-25T12:53:13.162Z SendDataConnector.js: CLIENT Stop now
2015-11-25T12:53:13.162Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 13:53:13.163 ThaliTest[777:6907] jxcore: disconnect
,2015-11-25 13:53:13.164 ThaliTest[777:6907] client session: disconnectFromPeer: Apple-Iphone6-1_PT8750.Du3EhQ==
,2015-11-25 13:53:13.164 ThaliTest[777:6907] client session: disconnect
,2015-11-25 13:53:13.165 ThaliTest[777:6907] client session: stateChange:2->0 Apple-Iphone6-1_PT8750.Du3EhQ==
,2015-11-25 13:53:13.169 ThaliTest[777:6907] jxcore: disconnect: success
2015-11-25T12:53:13.170Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8750.Du3EhQ==
,---- round done--------
,device[2]: Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25T12:53:13.172Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25T12:53:13.172Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25T12:53:13.172Z SendDataConnector.js: do connect now
,2015-11-25 13:53:13.173 ThaliTest[777:6907] jxcore: connect Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25 13:53:13.174 ThaliTest[777:6907] client session: connect
,2015-11-25 13:53:13.175 ThaliTest[777:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25 13:53:15.167 ThaliTest[777:60b] multipeer session: reset timer
2015-11-25 13:53:15.168 ThaliTest[777:60b] multipeer session: stop timer
2015-11-25 13:53:15.169 ThaliTest[777:60b] multipeer session: start timer: 0x1cf8c950
,2015-11-25 13:53:15.169 ThaliTest[777:60b] server session: connect
2015-11-25 13:53:15.170 ThaliTest[777:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT7357
,2015-11-25 13:53:15.173 ThaliTest[777:60b] server: accepting invitation Apple-IpadAir2-1_PT7357
,2015-11-25 13:53:16.179 ThaliTest[777:7913] client session: connected
2015-11-25 13:53:16.180 ThaliTest[777:7913] client session: stateChange:1->2 Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25 13:53:16.184 ThaliTest[777:7913] client session: fireConnectCallback: Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25 13:53:16.185 ThaliTest[777:7913] jxcore: connect: success
,2015-11-25T12:53:16.186Z SendDataConnector.js: CLIENT connected to 64273, error: null
2015-11-25T12:53:16.186Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 13:53:16.187 ThaliTest[777:60b] client: relay established
,2015-11-25 13:53:16.188 ThaliTest[777:60b] client: new accepted socket: 0x1cf9dc00
,2015-11-25T12:53:16.199Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T12:53:16.369Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-25T12:53:16.657Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-25T12:53:16.669Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-25T12:53:16.714Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-25T12:53:16.739Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-25T12:53:16.775Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T12:53:16.777Z SendDataConnector.js: got all data for this round
,2015-11-25T12:53:16.778Z SendDataConnector.js: CLIENT Stop now
2015-11-25T12:53:16.778Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 13:53:16.779 ThaliTest[777:6907] jxcore: disconnect
2015-11-25 13:53:16.779 ThaliTest[777:6907] client session: disconnectFromPeer: Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25 13:53:16.780 ThaliTest[777:6907] client session: disconnect
2015-11-25 13:53:16.781 ThaliTest[777:6907] client session: stateChange:2->0 Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25 13:53:16.784 ThaliTest[777:6907] jxcore: disconnect: success
2015-11-25T12:53:16.788Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5807.1C0pWw==
,---- round done--------
device[3]: Apple-IpadAir2-1_PT7357.1lZx3Q==
2015-11-25T12:53:16.790Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7357.1lZx3Q==
,2015-11-25T12:53:16.790Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7357.1lZx3Q==
2015-11-25T12:53:16.790Z SendDataConnector.js: do connect now
,2015-11-25 13:53:16.791 ThaliTest[777:6907] jxcore: connect Apple-IpadAir2-1_PT7357.1lZx3Q==
2015-11-25 13:53:16.793 ThaliTest[777:6907] client session: connect
,2015-11-25 13:53:16.794 ThaliTest[777:6907] client session: stateChange:0->1 Apple-IpadAir2-1_PT7357.1lZx3Q==
,2015-11-25 13:53:17.176 ThaliTest[777:60b] multipeer session: reset timer
,2015-11-25 13:53:17.177 ThaliTest[777:60b] multipeer session: stop timer
,2015-11-25 13:53:17.178 ThaliTest[777:60b] multipeer session: start timer: 0x1cf8c950
,2015-11-25 13:53:17.179 ThaliTest[777:60b] server session: connect
2015-11-25 13:53:17.179 ThaliTest[777:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT8750
,2015-11-25 13:53:17.521 ThaliTest[777:60b] server: accepting invitation Apple-Iphone6-1_PT8750
,2015-11-25 13:53:18.769 ThaliTest[777:60b] multipeer session: reset timer
,2015-11-25 13:53:18.771 ThaliTest[777:60b] multipeer session: stop timer
2015-11-25 13:53:18.771 ThaliTest[777:60b] multipeer session: start timer: 0x1cf8c950
,2015-11-25 13:53:18.772 ThaliTest[777:60b] server session: connect
,2015-11-25 13:53:18.773 ThaliTest[777:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT5807
,2015-11-25 13:53:18.776 ThaliTest[777:60b] server: accepting invitation Apple-Iphone5s-1_PT5807
,2015-11-25 13:53:18.789 ThaliTest[777:781b] server session: connected
2015-11-25 13:53:18.790 ThaliTest[777:781b] server session: stateChange:1->2 Apple-IpadAir2-1_PT7357
,2015-11-25 13:53:18.814 ThaliTest[777:60b] server relay: connected (to port: 64266)
,2015-11-25T12:53:18.818Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T12:53:19.428Z SendDataTCPServer.js: TCP/IP server has received 18716 bytes of data
,2015-11-25T12:53:19.442Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 13:53:19.841 ThaliTest[777:781b] server session: not connected Apple-IpadAir2-1_PT7357
,2015-11-25 13:53:19.870 ThaliTest[777:7c07] server session: connected
,2015-11-25 13:53:19.871 ThaliTest[777:7c07] server session: stateChange:1->2 Apple-Iphone6-1_PT8750
,2015-11-25 13:53:19.880 ThaliTest[777:60b] server relay: connected (to port: 64266)
,2015-11-25T12:53:19.888Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T12:53:20.001Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-11-25T12:53:20.016Z SendDataTCPServer.js: TCP/IP server has received 36520 bytes of data
,2015-11-25T12:53:20.029Z SendDataTCPServer.js: TCP/IP server has received 67748 bytes of data
,2015-11-25T12:53:20.042Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 13:53:20.053 ThaliTest[777:781b] server session: not connected Apple-Iphone6-1_PT8750
,2015-11-25 13:53:21.009 ThaliTest[777:7913] server session: connected
2015-11-25 13:53:21.011 ThaliTest[777:7913] server session: stateChange:1->2 Apple-Iphone5s-1_PT5807
,2015-11-25 13:53:21.015 ThaliTest[777:60b] server relay: connected (to port: 64266)
,2015-11-25T12:53:21.017Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T12:53:21.118Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-11-25T12:53:21.131Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-11-25T12:53:21.431Z SendDataTCPServer.js: TCP/IP server has received 45848 bytes of data
,2015-11-25T12:53:21.443Z SendDataTCPServer.js: TCP/IP server has received 93520 bytes of data
,2015-11-25T12:53:21.459Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 13:53:21.507 ThaliTest[777:7913] server session: not connected Apple-Iphone5s-1_PT5807
,2015-11-25 13:53:22.455 ThaliTest[777:781b] client session: connected
2015-11-25 13:53:22.457 ThaliTest[777:781b] client session: stateChange:1->2 Apple-IpadAir2-1_PT7357.1lZx3Q==
,2015-11-25 13:53:22.460 ThaliTest[777:781b] client session: fireConnectCallback: Apple-IpadAir2-1_PT7357.1lZx3Q==
2015-11-25 13:53:22.461 ThaliTest[777:781b] jxcore: connect: success
,2015-11-25T12:53:22.462Z SendDataConnector.js: CLIENT connected to 64279, error: null
2015-11-25T12:53:22.462Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 13:53:22.464 ThaliTest[777:60b] client: relay established
,2015-11-25 13:53:22.465 ThaliTest[777:60b] client: new accepted socket: 0x1cfbab70
,2015-11-25T12:53:22.475Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T12:53:22.997Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-25T12:53:23.574Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-25T12:53:23.586Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T12:53:23.586Z SendDataConnector.js: got all data for this round
,2015-11-25T12:53:23.588Z SendDataConnector.js: CLIENT Stop now
2015-11-25T12:53:23.588Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 13:53:23.590 ThaliTest[777:6907] jxcore: disconnect
,2015-11-25 13:53:23.591 ThaliTest[777:6907] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7357.1lZx3Q==
,2015-11-25 13:53:23.591 ThaliTest[777:6907] client session: disconnect
,2015-11-25 13:53:23.592 ThaliTest[777:6907] client session: stateChange:2->0 Apple-IpadAir2-1_PT7357.1lZx3Q==
,2015-11-25 13:53:23.594 ThaliTest[777:6907] jxcore: disconnect: success
2015-11-25T12:53:23.595Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7357.1lZx3Q==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-Iphone5-1_PT9701","time":13354,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT8750.Du3EhQ==","time":2674,"result":"OK","connections":1,"doneRo,unds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT5807.1C0pWw==","time":3605,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT7357.1lZx3Q==","time":6797,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 6797 ms, 99% : 6797 ms, 95 : 6797 ms, 90% : 6797 ms.
,Result count 3, range 2674 ms to  6797 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-11-25T12:53:23.607Z SendDataConnector.js: CLIENT Stop now
,2015-11-25T12:53:23.607Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-25 13:53:24.000 ThaliTest[777:6907] jxcore: stopBroadcasting
,2015-11-25 13:53:24.001 ThaliTest[777:6907] THEMultipeerSession stopping peer
,2015-11-25 13:53:24.002 ThaliTest[777:6907] multipeer session: stop timer
,2015-11-25 13:53:24.002 ThaliTest[777:6907] server session: disconnect
,2015-11-25 13:53:24.003 ThaliTest[777:6907] server session: stateChange:2->0 Apple-IpadAir2-1_PT7357
,2015-11-25 13:53:24.009 ThaliTest[777:6907] server session: disconnect
2015-11-25 13:53:24.010 ThaliTest[777:6907] server session: stateChange:2->0 Apple-Iphone5s-1_PT5807
,2015-11-25 13:53:24.014 ThaliTest[777:6907] server session: disconnect
,2015-11-25 13:53:24.015 ThaliTest[777:6907] server session: stateChange:2->0 Apple-Iphone6-1_PT8750
,2015-11-25 13:53:24.726 ThaliTest[777:6907] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-11-25T12:53:24.742Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T12:53:24.744Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T12:53:24.744Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T12:53:24.745Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT8750.Du3EhQ==\",\"time\":2674,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone5s-1_PT5807.1C0pWw==\",\"time\":3605,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-IpadAir2-1_PT7357.1lZx3Q==\",\"time\":6797,\"result\":\"OK\",\"connections\":,1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called

```
