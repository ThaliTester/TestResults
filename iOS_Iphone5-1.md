#### Test 513350283842813_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/513350283842813/build_ios/ThaliTest.app
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
,(lldb) command source -s 0 '/tmp/3517D42B-CA14-4B14-969E-EFEA12628CF6/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/3517D42B-CA14-4B14-969E-EFEA12628CF6/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/513350283842813/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/513350283842813/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/217D3751-542A-4C9D-901F-F4374CF47BC9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55195"
,(lldb)     command script import "/tmp/3517D42B-CA14-4B14-969E-EFEA12628CF6/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-25 10:19:40.330 ThaliTest[755:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-25 10:19:40.334 ThaliTest[755:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-25 10:19:40.340 ThaliTest[755:60b] Unlimited access to network resources
,2015-11-25 10:19:40.348 ThaliTest[755:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.appl,e.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-25 10:19:51.149 ThaliTest[755:60b] Resetting plugins due to page load.
,2015-11-25 10:19:52.027 ThaliTest[755:60b] Finished load of: file:///var/mobile/Applications/217D3751-542A-4C9D-901F-F4374CF47BC9/ThaliTest.app/www/index.html
,2015-11-25 10:19:52.205 ThaliTest[755:60b] JXcore Cordova plugin initializing
,2015-11-25 10:19:52.208 ThaliTest[755:6807] JXcore instance initializing
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
,Radios toggled
,my name is : Apple-Iphone5-1_PT138
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
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 63801
,2015-11-25 10:26:51.670 ThaliTest[755:6807] jxcore: startBroadcasting
,2015-11-25 10:26:51.680 ThaliTest[755:6807] server: starting Apple-Iphone5-1_PT138.uokMhA==
2015-11-25 10:26:51.682 ThaliTest[755:6807] multipeer session: start timer: 0x1c7b68d0
2015-11-25 10:26:51.682 ThaliTest[755:6807] THEMultipeerSession initialized, peer Apple-Iphone5-1_PT138
,2015-11-25 10:26:51.683 ThaliTest[755:6807] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-25T09:26:51.686Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-25 10:26:52.074 ThaliTest[755:60b] client: found peer: Apple-Iphone6-1_PT8682.g043PA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8682.g043PA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT8682.g043PA==
2015-11-25T09:26:52.079Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25T09:26:52.080Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8682.g043PA==
2015-11-25T09:26:52.080Z SendDataConnector.js: do connect now
,2015-11-25 10:26:52.080 ThaliTest[755:6807] jxcore: connect Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25 10:26:52.081 ThaliTest[755:6807] client session: connect
,2015-11-25 10:26:52.082 ThaliTest[755:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25 10:26:52.287 ThaliTest[755:60b] client: found peer: Apple-Iphone5s-1_PT1341.lrEeog==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1341.lrEeog==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-25 10:26:52.867 ThaliTest[755:60b] client: found peer: Apple-IpadAir2-1_PT7460.CVEGJA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7460.CVEGJA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-25 10:26:54.626 ThaliTest[755:631b] client session: connected
2015-11-25 10:26:54.628 ThaliTest[755:631b] client session: stateChange:1->2 Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25 10:26:54.632 ThaliTest[755:631b] client session: fireConnectCallback: Apple-Iphone6-1_PT8682.g043PA==
2015-11-25 10:26:54.633 ThaliTest[755:631b] jxcore: connect: success
,2015-11-25T09:26:54.634Z SendDataConnector.js: CLIENT connected to 63804, error: null
2015-11-25T09:26:54.635Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 10:26:54.636 ThaliTest[755:60b] client: relay established
2015-11-25 10:26:54.637 ThaliTest[755:60b] client: new accepted socket: 0x1c6d1f40
,2015-11-25T09:26:54.650Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T09:26:54.867Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-25T09:26:54.880Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-25T09:26:54.894Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-25T09:26:54.907Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-25T09:26:54.932Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T09:26:54.933Z SendDataConnector.js: got all data for this round
,2015-11-25T09:26:54.935Z SendDataConnector.js: CLIENT Stop now
2015-11-25T09:26:54.935Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 10:26:54.936 ThaliTest[755:6807] jxcore: disconnect
,2015-11-25 10:26:54.937 ThaliTest[755:6807] client session: disconnectFromPeer: Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25 10:26:54.938 ThaliTest[755:6807] client session: disconnect
,2015-11-25 10:26:54.938 ThaliTest[755:6807] client session: stateChange:2->0 Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25 10:26:54.941 ThaliTest[755:6807] jxcore: disconnect: success
2015-11-25T09:26:54.942Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8682.g043PA==
---- round done--------
,device[2]: Apple-Iphone5s-1_PT1341.lrEeog==
2015-11-25T09:26:54.944Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT1341.lrEeog==
,2015-11-25T09:26:54.945Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1341.lrEeog==
2015-11-25T09:26:54.945Z SendDataConnector.js: do connect now
,2015-11-25 10:26:54.945 ThaliTest[755:6807] jxcore: connect Apple-Iphone5s-1_PT1341.lrEeog==
,2015-11-25 10:26:54.946 ThaliTest[755:6807] client session: connect
,2015-11-25 10:26:54.947 ThaliTest[755:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT1341.lrEeog==
,2015-11-25 10:26:57.616 ThaliTest[755:7c07] client session: connected
2015-11-25 10:26:57.618 ThaliTest[755:7c07] client session: stateChange:1->2 Apple-Iphone5s-1_PT1341.lrEeog==
,2015-11-25 10:26:57.621 ThaliTest[755:7c07] client session: fireConnectCallback: Apple-Iphone5s-1_PT1341.lrEeog==
,2015-11-25 10:26:57.622 ThaliTest[755:7c07] jxcore: connect: success
,2015-11-25T09:26:57.624Z SendDataConnector.js: CLIENT connected to 63807, error: null
2015-11-25T09:26:57.624Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 10:26:57.626 ThaliTest[755:60b] client: relay established
,2015-11-25 10:26:57.628 ThaliTest[755:60b] client: new accepted socket: 0x1c6cb320
,2015-11-25T09:26:57.637Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T09:26:58.188Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-25T09:27:00.246Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-25T09:27:00.259Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-25T09:27:00.260Z SendDataConnector.js: got all data for this round
,2015-11-25T09:27:00.261Z SendDataConnector.js: CLIENT Stop now
2015-11-25T09:27:00.261Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 10:27:00.262 ThaliTest[755:6807] jxcore: disconnect
,2015-11-25 10:27:00.264 ThaliTest[755:6807] client session: disconnectFromPeer: Apple-Iphone5s-1_PT1341.lrEeog==
2015-11-25 10:27:00.265 ThaliTest[755:6807] client session: disconnect
2015-11-25 10:27:00.266 ThaliTest[755:6807] client session: stateChange:2->0 Apple-Iphone5s-1_PT1341.lrEeog==
,2015-11-25 10:27:00.269 ThaliTest[755:6807] jxcore: disconnect: success
,2015-11-25T09:27:00.271Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1341.lrEeog==
,---- round done--------
,device[3]: Apple-IpadAir2-1_PT7460.CVEGJA==
2015-11-25T09:27:00.275Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7460.CVEGJA==
2015-11-25T09:27:00.275Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7460.CVEGJA==
2015-11-25T09:27:00.275Z SendDataConnector.js: do connect now
,2015-11-25 10:27:00.275 ThaliTest[755:6807] jxcore: connect Apple-IpadAir2-1_PT7460.CVEGJA==
2015-11-25 10:27:00.276 ThaliTest[755:6807] client session: connect
,2015-11-25 10:27:00.277 ThaliTest[755:6807] client session: stateChange:0->1 Apple-IpadAir2-1_PT7460.CVEGJA==
,2015-11-25 10:27:00.728 ThaliTest[755:60b] multipeer session: reset timer
,2015-11-25 10:27:00.729 ThaliTest[755:60b] multipeer session: stop timer
,2015-11-25 10:27:00.730 ThaliTest[755:60b] multipeer session: start timer: 0x1c7b68d0
,2015-11-25 10:27:00.730 ThaliTest[755:60b] server session: connect
,2015-11-25 10:27:00.731 ThaliTest[755:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT1341
,2015-11-25 10:27:00.734 ThaliTest[755:60b] server: accepting invitation Apple-Iphone5s-1_PT1341
,2015-11-25 10:27:02.027 ThaliTest[755:60b] multipeer session: reset timer
,2015-11-25 10:27:02.028 ThaliTest[755:60b] multipeer session: stop timer
,2015-11-25 10:27:02.029 ThaliTest[755:60b] multipeer session: start timer: 0x1c7b68d0
,2015-11-25 10:27:02.030 ThaliTest[755:60b] server session: connect
,2015-11-25 10:27:02.031 ThaliTest[755:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT8682
,2015-11-25 10:27:02.034 ThaliTest[755:60b] server: accepting invitation Apple-Iphone6-1_PT8682
,2015-11-25 10:27:02.883 ThaliTest[755:60b] multipeer session: reset timer
,2015-11-25 10:27:02.884 ThaliTest[755:60b] multipeer session: stop timer
,2015-11-25 10:27:02.885 ThaliTest[755:60b] multipeer session: start timer: 0x1c7b68d0
,2015-11-25 10:27:02.886 ThaliTest[755:60b] server session: connect
,2015-11-25 10:27:02.886 ThaliTest[755:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT7460
,2015-11-25 10:27:02.890 ThaliTest[755:60b] server: accepting invitation Apple-IpadAir2-1_PT7460
,2015-11-25 10:27:02.954 ThaliTest[755:7c07] server session: connected
2015-11-25 10:27:02.956 ThaliTest[755:7c07] server session: stateChange:1->2 Apple-Iphone5s-1_PT1341
,2015-11-25 10:27:02.960 ThaliTest[755:60b] server relay: connected (to port: 63801)
,2015-11-25T09:27:02.971Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T09:27:03.087Z SendDataTCPServer.js: TCP/IP server has received 34898 bytes of data
,2015-11-25T09:27:03.101Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-11-25T09:27:03.114Z SendDataTCPServer.js: TCP/IP server has received 98408 bytes of data
,2015-11-25T09:27:03.126Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 10:27:03.327 ThaliTest[755:771b] server session: not connected Apple-Iphone5s-1_PT1341
,2015-11-25 10:27:04.207 ThaliTest[755:7c07] server session: connected
2015-11-25 10:27:04.210 ThaliTest[755:7c07] server session: stateChange:1->2 Apple-Iphone6-1_PT8682
,2015-11-25 10:27:04.213 ThaliTest[755:60b] server relay: connected (to port: 63801)
,2015-11-25T09:27:04.220Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T09:27:04.332Z SendDataTCPServer.js: TCP/IP server has received 21616 bytes of data
,2015-11-25T09:27:04.347Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-11-25T09:27:04.361Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-11-25T09:27:04.454Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 10:27:04.509 ThaliTest[755:771b] server session: not connected Apple-Iphone6-1_PT8682
,2015-11-25 10:27:05.442 ThaliTest[755:8503] client session: connected
2015-11-25 10:27:05.444 ThaliTest[755:8503] client session: stateChange:1->2 Apple-IpadAir2-1_PT7460.CVEGJA==
2015-11-25 10:27:05.446 ThaliTest[755:8503] client session: fireConnectCallback: Apple-IpadAir2-1_PT7460.CVEGJA==
2015-11-25 10:27:05.446 ThaliTest[755:8503] jxcore: connect: success
,2015-11-25T09:27:05.449Z SendDataConnector.js: CLIENT connected to 63812, error: null
,2015-11-25T09:27:05.449Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 10:27:05.452 ThaliTest[755:60b] client: relay established
,2015-11-25 10:27:05.452 ThaliTest[755:60b] client: new accepted socket: 0x1c7e2c70
,2015-11-25T09:27:05.462Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25 10:27:05.509 ThaliTest[755:8503] server session: connected
2015-11-25 10:27:05.510 ThaliTest[755:8503] server session: stateChange:1->2 Apple-IpadAir2-1_PT7460
,2015-11-25 10:27:05.518 ThaliTest[755:60b] server relay: connected (to port: 63801)
,2015-11-25T09:27:05.607Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T09:27:05.763Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-11-25T09:27:05.775Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-11-25T09:27:05.788Z SendDataTCPServer.js: TCP/IP server has received 48038 bytes of data
,2015-11-25T09:27:05.801Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-11-25T09:27:05.827Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25T09:27:06.337Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-25 10:27:06.504 ThaliTest[755:8503] server session: not connected Apple-IpadAir2-1_PT7460
,2015-11-25T09:27:06.838Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-25T09:27:06.906Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T09:27:06.907Z SendDataConnector.js: got all data for this round
,2015-11-25T09:27:06.909Z SendDataConnector.js: CLIENT Stop now
2015-11-25T09:27:06.909Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 10:27:06.910 ThaliTest[755:6807] jxcore: disconnect
,2015-11-25 10:27:06.911 ThaliTest[755:6807] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7460.CVEGJA==
,2015-11-25 10:27:06.911 ThaliTest[755:6807] client session: disconnect
,2015-11-25 10:27:06.912 ThaliTest[755:6807] client session: stateChange:2->0 Apple-IpadAir2-1_PT7460.CVEGJA==
,2015-11-25 10:27:06.914 ThaliTest[755:6807] jxcore: disconnect: success
2015-11-25T09:27:06.916Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7460.CVEGJA==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT138","time":15259,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT8682.g043PA==","time":2854,"result":"OK","connections":1},{"name":"Apple-Iphone5s-1_PT1341.lrEeog==","time":5315,"result":"OK","connections":1,},{"name":"Apple-IpadAir2-1_PT7460.CVEGJA==","time":6632,"result":"OK","connections":1}]}
sendList : 100% : 6632 ms, 99% : 6632 ms, 95 : 6632 ms, 90% : 6632 ms.
Result count 3, range 2854 ms to  6632 ms.
sendList failed peers count : 0 [0 %]
sendList n,ever tried peers count : 0 [0 %]
2015-11-25T09:27:06.923Z SendDataConnector.js: CLIENT Stop now
2015-11-25T09:27:06.923Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-25 10:27:07.330 ThaliTest[755:6807] jxcore: stopBroadcasting
,2015-11-25 10:27:07.331 ThaliTest[755:6807] THEMultipeerSession stopping peer
,2015-11-25 10:27:07.332 ThaliTest[755:6807] multipeer session: stop timer
,2015-11-25 10:27:07.333 ThaliTest[755:6807] server session: disconnect
2015-11-25 10:27:07.335 ThaliTest[755:6807] server session: stateChange:2->0 Apple-IpadAir2-1_PT7460
,2015-11-25 10:27:07.339 ThaliTest[755:6807] server session: disconnect
,2015-11-25 10:27:07.342 ThaliTest[755:6807] server session: stateChange:2->0 Apple-Iphone5s-1_PT1341
,2015-11-25 10:27:07.347 ThaliTest[755:6807] server session: disconnect
2015-11-25 10:27:07.349 ThaliTest[755:6807] server session: stateChange:2->0 Apple-Iphone6-1_PT8682
,2015-11-25 10:27:07.354 ThaliTest[755:6807] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-11-25T09:27:07.373Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T09:27:07.373Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T09:27:07.374Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T09:27:07.374Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT8682.g043PA==\",\"time\":2854,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT1341.lrEeog==\",\"time\":5315,\",result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7460.CVEGJA==\",\"time\":6632,\"result\":\"OK\",\"connections\":1}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT138.uokMh,A==\",\"time\":2613,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8682.g043PA==\",\"time\":2752,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8682.g043PA==\",\"time\":2854,\"result\":\"OK\",\"connections\":1},{\"na,me\":\"Apple-Iphone5-1_PT138.uokMhA==\",\"time\":3651,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT1341.lrEeog==\",\"time\":3735,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7460.CVEGJA==\",\"time\":3861,\"resu,lt\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT1341.lrEeog==\",\"time\":4218,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT138.uokMhA==\",\"time\":4473,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT,1341.lrEeog==\",\"time\":5315,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7460.CVEGJA==\",\"time\":6177,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8682.g043PA==\",\"time\":6202,\"result\":\"OK\",\"connections,\":1},{\"name\":\"Apple-IpadAir2-1_PT7460.CVEGJA==\",\"time\":6632,\"result\":\"OK\",\"connections\":1}]}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
Coordi
```
