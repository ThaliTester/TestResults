#### Test 519863409bc5c94_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/519863409bc5c94/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CD7DDDBD-9862-4D64-898D-6FF5044300F4/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/CD7DDDBD-9862-4D64-898D-6FF5044300F4/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/519863409bc5c94/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/519863409bc5c94/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/EBCC888A-EF4E-4C4E-B684-E1C61D97EB4B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58053"
,(lldb)     command script import "/tmp/CD7DDDBD-9862-4D64-898D-6FF5044300F4/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-30 11:50:13.988 ThaliTest[995:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-30 11:50:13.992 ThaliTest[995:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-30 11:50:13.998 ThaliTest[995:60b] Unlimited access to network resources
,2015-11-30 11:50:14.006 ThaliTest[995:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.appl,e.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-30 11:50:24.779 ThaliTest[995:60b] Resetting plugins due to page load.
,2015-11-30 11:50:25.652 ThaliTest[995:60b] Finished load of: file:///var/mobile/Applications/EBCC888A-EF4E-4C4E-B684-E1C61D97EB4B/ThaliTest.app/www/index.html
,2015-11-30 11:50:25.838 ThaliTest[995:60b] JXcore Cordova plugin initializing
,2015-11-30 11:50:25.840 ThaliTest[995:6807] JXcore instance initializing
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
,my name is : Apple-Iphone5-1_PT2455
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
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":50000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":50000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 55597
,2015-11-30 11:55:59.990 ThaliTest[995:6807] jxcore: startBroadcasting
,2015-11-30 11:56:00.000 ThaliTest[995:6807] server: starting Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30 11:56:00.005 ThaliTest[995:6807] multipeer session: start timer: 0x1af43770
2015-11-30 11:56:00.006 ThaliTest[995:6807] THEMultipeerSession initialize,d peer Apple-Iphone5-1_PT2455
2015-11-30 11:56:00.007 ThaliTest[995:6807] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-30T10:56:00.010Z SendDataTCPServer.js: TCP/IP server is bound to port: 55597
,2015-11-30 11:56:00.512 ThaliTest[995:60b] client: found peer: Apple-Iphone5s-1_PT7955.qINS9Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7955.qINS9Q==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30T10:56:00.517Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30T10:56:00.517Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30T10:56:00.517Z SendDataConnector.js: do connect now
,2015-11-30 11:56:00.518 ThaliTest[995:6807] jxcore: connect Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:56:00.518 ThaliTest[995:6807] client session: connect
,2015-11-30 11:56:00.519 ThaliTest[995:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:56:01.212 ThaliTest[995:60b] client: found peer: Apple-IpadAir2-1_PT4872.+CDkQA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4872.+CDkQA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-30 11:56:01.368 ThaliTest[995:60b] multipeer session: reset timer
,2015-11-30 11:56:01.369 ThaliTest[995:60b] multipeer session: stop timer
2015-11-30 11:56:01.371 ThaliTest[995:60b] multipeer session: start timer: 0x1af43770
,2015-11-30 11:56:01.372 ThaliTest[995:60b] server session: connect
,2015-11-30 11:56:01.372 ThaliTest[995:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT7955
,2015-11-30 11:56:01.376 ThaliTest[995:60b] server: accepting invitation Apple-Iphone5s-1_PT7955
,2015-11-30 11:56:03.108 ThaliTest[995:6223] client session: connected
2015-11-30 11:56:03.109 ThaliTest[995:6223] client session: stateChange:1->2 Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:56:03.119 ThaliTest[995:7a0b] client session: fireConnectCallback: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:56:03.120 ThaliTest[995:7a0b] jxcore: connect: success
,2015-11-30T10:56:03.122Z SendDataConnector.js: CLIENT connected to 55600, error: null
2015-11-30T10:56:03.122Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 11:56:03.123 ThaliTest[995:60b] client: relay established
,2015-11-30 11:56:03.124 ThaliTest[995:60b] client: new accepted socket: 0x1ae5c470
,2015-11-30T10:56:03.138Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-30 11:56:03.159 ThaliTest[995:60b] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7389.2i+JNA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-30 11:56:03.650 ThaliTest[995:7a0b] server session: connected
,2015-11-30 11:56:03.651 ThaliTest[995:7a0b] server session: stateChange:1->2 Apple-Iphone5s-1_PT7955
,2015-11-30T10:56:03.661Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-30 11:56:03.670 ThaliTest[995:60b] server relay: connected (to port: 55597)
,2015-11-30T10:56:03.684Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-30T10:56:03.686Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30T10:56:03.699Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-30T10:56:04.144Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-11-30T10:56:04.157Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-11-30T10:56:04.173Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-11-30T10:56:04.184Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-11-30T10:56:04.199Z SendDataTCPServer.js: TCP/IP server has received 80462 bytes of data
,2015-11-30T10:56:04.202Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-30T10:56:04.214Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-30T10:56:04.217Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-30T10:56:04.217Z SendDataConnector.js: got all data for this round
,2015-11-30T10:56:04.219Z SendDataConnector.js: CLIENT Stop now
2015-11-30T10:56:04.219Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 11:56:04.220 ThaliTest[995:6807] jxcore: disconnect
2015-11-30 11:56:04.221 ThaliTest[995:6807] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:56:04.221 ThaliTest[995:6807] client session: disconnect
2015-1,1-30 11:56:04.222 ThaliTest[995:6807] client session: stateChange:2->0 Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:56:04.226 ThaliTest[995:6807] jxcore: disconnect: success
,2015-11-30T10:56:04.230Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7955.qINS9Q==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30T10:56:04.234Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30T10:56:04.234Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT4872.+CDkQA==
2015-11-30T10:56:04.234Z SendDataConnector.js: do connect now
,2015-11-30 11:56:04.235 ThaliTest[995:6807] jxcore: connect Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 11:56:04.236 ThaliTest[995:6807] client session: connect
,2015-11-30 11:56:04.237 ThaliTest[995:6807] client session: stateChange:0->1 Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 11:56:04.259 ThaliTest[995:6223] server session: not connected Apple-Iphone5s-1_PT7955
,2015-11-30 11:56:04.340 ThaliTest[995:60b] multipeer session: reset timer
,2015-11-30 11:56:04.341 ThaliTest[995:60b] multipeer session: stop timer
,2015-11-30 11:56:04.342 ThaliTest[995:60b] multipeer session: start timer: 0x1af43770
,2015-11-30 11:56:04.343 ThaliTest[995:60b] server session: connect
,2015-11-30 11:56:04.344 ThaliTest[995:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT4872
,2015-11-30 11:56:04.770 ThaliTest[995:60b] server: accepting invitation Apple-IpadAir2-1_PT4872
,2015-11-30 11:56:04.789 ThaliTest[995:60b] multipeer session: reset timer
,2015-11-30 11:56:04.791 ThaliTest[995:60b] multipeer session: stop timer
,2015-11-30 11:56:04.792 ThaliTest[995:60b] multipeer session: start timer: 0x1af43770
,2015-11-30 11:56:04.793 ThaliTest[995:60b] server session: connect
,2015-11-30 11:56:04.794 ThaliTest[995:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT7389
,2015-11-30 11:56:04.798 ThaliTest[995:60b] server: accepting invitation Apple-Iphone6-1_PT7389
,2015-11-30 11:56:06.963 ThaliTest[995:2217] server session: connected
,2015-11-30 11:56:06.964 ThaliTest[995:2217] server session: stateChange:1->2 Apple-Iphone6-1_PT7389
,2015-11-30 11:56:07.011 ThaliTest[995:60b] server relay: connected (to port: 55597)
2015-11-30 11:56:07.011 ThaliTest[995:b003] client session: connected
,2015-11-30 11:56:07.012 ThaliTest[995:b003] client session: stateChange:1->2 Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30T10:56:07.020Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30 11:56:07.291 ThaliTest[995:b003] client session: fireConnectCallback: Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 11:56:07.293 ThaliTest[995:b003] jxcore: connect: success
,2015-11-30T10:56:07.294Z SendDataConnector.js: CLIENT connected to 55606, error: null
2015-11-30T10:56:07.294Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 11:56:07.295 ThaliTest[995:60b] client: relay established
2015-11-30 11:56:07.296 ThaliTest[995:60b] client: new accepted socket: 0x1ae75870
,2015-11-30T10:56:07.309Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-30 11:56:07.421 ThaliTest[995:b003] server session: connected
2015-11-30 11:56:07.422 ThaliTest[995:b003] server session: stateChange:1->2 Apple-IpadAir2-1_PT4872
,2015-11-30 11:56:07.857 ThaliTest[995:60b] server relay: connected (to port: 55597)
,2015-11-30T10:56:07.897Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-30T10:56:07.901Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30T10:56:07.902Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-30 11:56:08.388 ThaliTest[995:b003] server session: not connected Apple-Iphone6-1_PT7389
,2015-11-30T10:56:08.445Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
2015-11-30T10:56:08.446Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-30T10:56:08.458Z SendDataTCPServer.js: TCP/IP server has received 12998 bytes of data
2015-11-30T10:56:08.459Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-30T10:56:08.471Z SendDataTCPServer.js: TCP/IP server has received 39136 bytes of data
2015-11-30T10:56:08.475Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-30T10:56:08.487Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-11-30T10:56:08.501Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-30T10:56:08.539Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-30 11:56:08.847 ThaliTest[995:770f] server session: not connected Apple-IpadAir2-1_PT4872
,2015-11-30T10:56:08.851Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-30T10:56:08.851Z SendDataConnector.js: got all data for this round
,2015-11-30T10:56:08.852Z SendDataConnector.js: CLIENT Stop now
2015-11-30T10:56:08.852Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 11:56:08.853 ThaliTest[995:6807] jxcore: disconnect
,2015-11-30 11:56:08.854 ThaliTest[995:6807] client session: disconnectFromPeer: Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 11:56:08.855 ThaliTest[995:6807] client session: disconnect
2015-11-30 11:56:08.855 ThaliTest[995:6807] client session: stateChange:2->0 Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 11:56:08.857 ThaliTest[995:6807] jxcore: disconnect: success
,2015-11-30T10:56:08.861Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT4872.+CDkQA==
---- round done--------
,device[3]: Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30T10:56:08.862Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30T10:56:08.862Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30T10:56:08.862Z SendDataConnector.js: do connect now
,2015-11-30 11:56:08.863 ThaliTest[995:6807] jxcore: connect Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30 11:56:08.864 ThaliTest[995:6807] client session: connect
,2015-11-30 11:56:08.864 ThaliTest[995:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:56:11.170 ThaliTest[995:6223] client session: connected
,2015-11-30 11:56:11.172 ThaliTest[995:6223] client session: stateChange:1->2 Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:56:11.187 ThaliTest[995:7a0b] client session: fireConnectCallback: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:56:11.187 ThaliTest[995:7a0b] jxcore: connect: success
,2015-11-30T10:56:11.188Z SendDataConnector.js: CLIENT connected to 55610, error: null
,2015-11-30T10:56:11.189Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 11:56:11.190 ThaliTest[995:60b] client: relay established
,2015-11-30 11:56:11.191 ThaliTest[995:60b] client: new accepted socket: 0x1ab20c10
,2015-11-30T10:56:11.202Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-30T10:56:12.068Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-30T10:56:12.137Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-30 11:56:34.794 ThaliTest[995:60b] multipeer session: restart
,2015-11-30T10:57:02.144Z SendDataConnector.js: Receiving data timeout now
,2015-11-30T10:57:02.144Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30T10:57:02.145Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30T10:57:02.146Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-30T10:57:02.147Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-30 11:57:02.148 ThaliTest[995:60b] client: socket closed
2015-11-30 11:57:02.149 ThaliTest[995:60b] client relay: socket disconnected
2015-11-30 11:57:02.149 ThaliTest[995:60b] client relay: 0x1ab20c10 disconnected with error Error Domain=GCDAsyn,cSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x14e86c00 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-30 11:57:02.150 ThaliTest[995:60b] client session: socket closed: Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30 11:57:02.150 ThaliTest[995:60b] client session: onLinkFailure: Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30 11:57:02.151 ThaliTest[995:60b], client session: disconnect
2015-11-30 11:57:02.152 ThaliTest[995:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:57:02.153 ThaliTest[995:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:57:04.794 ThaliTest[995:60b] multipeer session: restart
,2015-11-30 11:57:04.803 ThaliTest[995:60b] client: found peer: Apple-IpadAir2-1_PT4872.+CDkQA==
2015-11-30 11:57:04.805 ThaliTest[995:60b] client: found peer: Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:57:04.806 ThaliTest[995:60b] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30T10:57:07.153Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30T10:57:07.154Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:57:12.155 ThaliTest[995:6807] jxcore: disconnect
2015-11-30 11:57:12.156 ThaliTest[995:6807] jxcore: disconnect: fail
,2015-11-30T10:57:12.158Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30T10:57:12.159Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT7389.2i+JNA== with availability status: ,true
2015-11-30T10:57:12.159Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30T10:57:12.159Z SendDataConnector.js: do connect now
,2015-11-30 11:57:12.159 ThaliTest[995:6807] jxcore: connect Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:57:12.160 ThaliTest[995:6807] client session: connect
,2015-11-30 11:57:12.161 ThaliTest[995:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:57:14.552 ThaliTest[995:7717] client session: connected
,2015-11-30 11:57:14.553 ThaliTest[995:7717] client session: stateChange:1->2 Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:57:14.561 ThaliTest[995:7717] client session: fireConnectCallback: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:57:14.562 ThaliTest[995:7717] jxcore: connect: success
,2015-11-30T10:57:14.563Z SendDataConnector.js: CLIENT connected to 55617, error: null
,2015-11-30T10:57:14.563Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 11:57:14.565 ThaliTest[995:60b] client: relay established
,2015-11-30 11:57:14.566 ThaliTest[995:60b] client: new accepted socket: 0x1ab16b40
,2015-11-30T10:57:14.577Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-30 11:57:17.566 ThaliTest[995:60b] client: lost peer: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:57:17.568 ThaliTest[995:60b] client session: onPeerLost: Apple-Iphone5s-1_PT7955.qINS9Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7955.qINS9Q==","peerName":"(null)","peerAvailable":false}]
,2015-11-30 11:57:17.992 ThaliTest[995:60b] client: lost peer: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:57:17.993 ThaliTest[995:60b] client session: onPeerLost: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:57:17.994 ThaliTest[995:60b] client session: onLinkFailure: Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30 11:57:17.995 ThaliTest[995:60b] client session: disconnect
,2015-11-30 11:57:17.996 ThaliTest[995:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:57:18.383 ThaliTest[995:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT7389.2i+JNA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7389.2i+JNA==","peerName":"(null)","peerAvailable":false}]
,2015-11-30 11:57:18.567 ThaliTest[995:60b] client: found peer: Apple-Iphone5s-1_PT7955.qINS9Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7955.qINS9Q==","peerName":"(null)","peerAvailable":true}]
,2015-11-30 11:57:19.086 ThaliTest[995:60b] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7389.2i+JNA==","peerName":"(null)","peerAvailable":true}]
,2015-11-30 11:57:21.759 ThaliTest[995:60b] client: lost peer: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:57:21.760 ThaliTest[995:60b] client session: onPeerLost: Apple-Iphone5s-1_PT7955.qINS9Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7955.qINS9Q==","peerName":"(null)","peerAvailable":false}]
,2015-11-30 11:57:23.282 ThaliTest[995:60b] client: found peer: Apple-Iphone5s-1_PT7955.qINS9Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7955.qINS9Q==","peerName":"(null)","peerAvailable":true}]
,2015-11-30 11:57:34.794 ThaliTest[995:60b] multipeer session: restart
,2015-11-30T10:58:04.634Z SendDataConnector.js: Receiving data timeout now
,2015-11-30T10:58:04.634Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-30T10:58:04.635Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30T10:58:04.636Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-30T10:58:04.636Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-30 11:58:04.793 ThaliTest[995:60b] multipeer session: restart
,2015-11-30 11:58:04.803 ThaliTest[995:60b] client: found peer: Apple-IpadAir2-1_PT4872.+CDkQA==
2015-11-30 11:58:04.804 ThaliTest[995:60b] client: found peer: Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:58:04.849 ThaliTest[995:60b] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30T10:58:09.645Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30T10:58:09.645Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30T10:58:09.646Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 11:58:14.651 ThaliTest[995:6807] jxcore: disconnect
2015-11-30 11:58:14.652 ThaliTest[995:6807] jxcore: disconnect: fail
2015-11-30T10:58:14.654Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30T10:58:14.654Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT7389.2i+JNA== with availability status: true
2015-11-30T10:58:14.655Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30T10:58:14.655Z SendDataConnector.js: do connect now
,2015-11-30 11:58:14.655 ThaliTest[995:6807] jxcore: connect Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:58:14.656 ThaliTest[995:6807] client session: connect
,2015-11-30 11:58:14.657 ThaliTest[995:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:58:17.280 ThaliTest[995:791f] client session: connected
,2015-11-30 11:58:17.282 ThaliTest[995:791f] client session: stateChange:1->2 Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:58:17.683 ThaliTest[995:791f] client session: fireConnectCallback: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:58:17.685 ThaliTest[995:791f] jxcore: connect: success
,2015-11-30T10:58:17.686Z SendDataConnector.js: CLIENT connected to 55623, error: null
2015-11-30T10:58:17.687Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 11:58:17.688 ThaliTest[995:60b] client: relay established
2015-11-30 11:58:17.688 ThaliTest[995:60b] client: new accepted socket: 0x14e6ca30
,2015-11-30T10:58:17.699Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-30 11:58:19.321 ThaliTest[995:60b] client: lost peer: Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:58:19.323 ThaliTest[995:60b] client session: onPeerLost: Apple-Iphone5s-1_PT7955.qINS9Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7955.qINS9Q==","peerName":"(null)","peerAvailable":false}]
,2015-11-30 11:58:34.794 ThaliTest[995:60b] multipeer session: restart
,2015-11-30 11:58:34.804 ThaliTest[995:60b] client: found peer: Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 11:58:34.805 ThaliTest[995:60b] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:58:47.623 ThaliTest[995:60b] client: lost peer: Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30 11:58:47.624 ThaliTest[995:60b] client session: onPeerLost: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:58:47.625 ThaliTest[995:60b] client session: onLinkFailure: Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30 11:58:47.626 ThaliTest[995:60b] client session: disconnect
2015-11-30 11:58:47.627 ThaliTest[995:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:58:47.628 ThaliTest[995:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT7389.2i+JNA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7389.2i+JNA==","peerName":"(null)","peerAvailable":false}]
,2015-11-30 11:58:47.674 ThaliTest[995:60b] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7389.2i+JNA==","peerName":"(null)","peerAvailable":true}]
,2015-11-30 11:58:54.013 ThaliTest[995:60b] client: lost peer: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:58:54.015 ThaliTest[995:60b] client session: onPeerLost: Apple-Iphone6-1_PT7389.2i+JNA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7389.2i+JNA==","peerName":"(null)","peerAvailable":false}]
,2015-11-30 11:58:58.724 ThaliTest[995:60b] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7389.2i+JNA==","peerName":"(null)","peerAvailable":true}]
,2015-11-30 11:59:04.794 ThaliTest[995:60b] multipeer session: restart
,2015-11-30 11:59:04.803 ThaliTest[995:60b] client: found peer: Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 11:59:04.805 ThaliTest[995:60b] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30T10:59:07.753Z SendDataConnector.js: Receiving data timeout now
,2015-11-30T10:59:07.753Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-30T10:59:07.753Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-30T10:59:07.754Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-30T10:59:07.754Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-30T10:59:12.760Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30T10:59:12.760Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30T10:59:12.760Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 11:59:17.768 ThaliTest[995:6807] jxcore: disconnect
,2015-11-30 11:59:17.770 ThaliTest[995:6807] jxcore: disconnect: fail
2015-11-30T10:59:17.771Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30T10:59:17.772Z SendDataConnector.js: Connect (retry count, 3) to peer Apple-Iphone6-1_PT7389.2i+JNA== with availability status: true
,2015-11-30T10:59:17.772Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30T10:59:17.772Z SendDataConnector.js: do connect now
,2015-11-30 11:59:17.773 ThaliTest[995:6807] jxcore: connect Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:59:17.773 ThaliTest[995:6807] client session: connect
,2015-11-30 11:59:17.774 ThaliTest[995:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:59:20.341 ThaliTest[995:222b] client session: connected
,2015-11-30 11:59:20.343 ThaliTest[995:222b] client session: stateChange:1->2 Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:59:20.351 ThaliTest[995:222b] client session: fireConnectCallback: Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30 11:59:20.352 ThaliTest[995:222b] jxcore: connect: success
,2015-11-30T10:59:20.353Z SendDataConnector.js: CLIENT connected to 55630, error: null
2015-11-30T10:59:20.353Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 11:59:20.355 ThaliTest[995:60b] client: relay established
2015-11-30 11:59:20.356 ThaliTest[995:60b] client: new accepted socket: 0x1ab25af0
,2015-11-30T10:59:20.367Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-30 11:59:34.794 ThaliTest[995:60b] multipeer session: restart
,2015-11-30 12:00:04.794 ThaliTest[995:60b] multipeer session: restart
,2015-11-30 12:00:04.803 ThaliTest[995:60b] client: found peer: Apple-IpadAir2-1_PT4872.+CDkQA==
2015-11-30 12:00:04.804 ThaliTest[995:60b] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30T11:00:10.429Z SendDataConnector.js: Receiving data timeout now
,2015-11-30T11:00:10.430Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-30T11:00:10.430Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30T11:00:10.431Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-11-30T11:00:10.431Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-30 12:00:10.432 ThaliTest[995:60b] client: socket closed
2015-11-30 12:00:10.433 ThaliTest[995:60b] client relay: socket disconnected
,2015-11-30 12:00:10.434 ThaliTest[995:60b] client relay: 0x1ab25af0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1a9a8870 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-30 12:00:10.435 ThaliTest[995:60b] client session: socket closed: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 12:00:10.435 ThaliTest[995:60b] client session: onLinkFailure: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 12:00:10.436 ThaliTest[995:60b] client session: disconnect
,2015-11-30 12:00:10.437 ThaliTest[995:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 12:00:10.438 ThaliTest[995:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30T11:00:15.438Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30T11:00:15.439Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 12:00:20.442 ThaliTest[995:6807] jxcore: disconnect
2015-11-30 12:00:20.444 ThaliTest[995:6807] jxcore: disconnect: fail
2015-11-30T11:00:20.445Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30T11:00:20.446Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT7389.2i+JNA== with availability status: true
2015-11-30T11:00:20.446Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30T11:00:20.446Z SendDataConnector.js: do connect now
,2015-11-30 12:00:20.446 ThaliTest[995:6807] jxcore: connect Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 12:00:20.447 ThaliTest[995:6807] client session: connect
,2015-11-30 12:00:20.448 ThaliTest[995:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 12:00:23.273 ThaliTest[995:9f1b] client session: connected
2015-11-30 12:00:23.274 ThaliTest[995:9f1b] client session: stateChange:1->2 Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 12:00:23.279 ThaliTest[995:7837] client session: fireConnectCallback: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 12:00:23.280 ThaliTest[995:7837] jxcore: connect: success
2015-11-30T11:00:23.281Z SendDataConnector.js: CLIENT connected to 55637, error: null
2015-11-30T11:00:23.281Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 12:00:23.283 ThaliTest[995:60b] client: relay established
,2015-11-30 12:00:23.283 ThaliTest[995:60b] client: new accepted socket: 0x1ab31c80
,2015-11-30T11:00:23.296Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-30 12:00:27.315 ThaliTest[995:60b] client: lost peer: Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30 12:00:27.317 ThaliTest[995:60b] client session: onPeerLost: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 12:00:27.318 ThaliTest[995:60b] client session: onLinkFailure: Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30 12:00:27.319 ThaliTest[995:60b] client session: disconnect
,2015-11-30 12:00:27.319 ThaliTest[995:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 12:00:27.321 ThaliTest[995:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT7389.2i+JNA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7389.2i+JNA==","peerName":"(null)","peerAvailable":false}]
,2015-11-30 12:00:34.794 ThaliTest[995:60b] multipeer session: restart
,2015-11-30 12:00:34.803 ThaliTest[995:60b] client: found peer: Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 12:00:35.268 ThaliTest[995:60b] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7389.2i+JNA==","peerName":"(null)","peerAvailable":true}]
,2015-11-30 12:01:04.794 ThaliTest[995:60b] multipeer session: restart
,2015-11-30 12:01:04.804 ThaliTest[995:60b] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 12:01:05.673 ThaliTest[995:60b] client: found peer: Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30T11:01:13.354Z SendDataConnector.js: Receiving data timeout now
,2015-11-30T11:01:13.355Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-30T11:01:13.355Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30T11:01:13.357Z SendDataConnector.js: CLIENT Stop now
2015-11-30T11:01:13.357Z SendDataConnector.js: Stop data retrieving timer
2015-11-30T11:01:13.358Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 12:01:13.358 ThaliTest[995:6807] jxcore: disconnect
,2015-11-30 12:01:13.359 ThaliTest[995:6807] jxcore: disconnect: fail
2015-11-30T11:01:13.360Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7389.2i+JNA==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-Iphone5-1_PT2455","time":313381,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT7955.qINS9Q==","time":3701,"result":"OK","connections":1,"done,Rounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT4872.+CDkQA==","time":4617,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT7389.2i+JNA==","time":304494,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000}]}
,sendList : 100% : 4617 ms, 99% : 4617 ms, 95 : 4617 ms, 90% : 4617 ms.
Result count 2, range 3701 ms to  4617 ms.
,sendList failed peers count : 1 [33.333333333333336 %]
,- Peer ID : Apple-Iphone6-1_PT7389.2i+JNA==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-11-30T11:01:13.368Z SendDataConnector.js: CLIENT Stop now
2015-11-30T11:01:13.368Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30T11:01:13.370Z SendDataConnector.js: ----------------- closeClientSocket
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-30 12:01:13.742 ThaliTest[995:6807] jxcore: stopBroadcasting
,2015-11-30 12:01:13.742 ThaliTest[995:6807] THEMultipeerSession stopping peer
,2015-11-30 12:01:13.743 ThaliTest[995:6807] multipeer session: stop timer
,2015-11-30 12:01:13.744 ThaliTest[995:6807] server session: disconnect
,2015-11-30 12:01:13.746 ThaliTest[995:6807] server session: stateChange:2->0 Apple-IpadAir2-1_PT4872
,2015-11-30 12:01:14.543 ThaliTest[995:6807] server session: disconnect
,2015-11-30 12:01:14.544 ThaliTest[995:6807] server session: stateChange:2->0 Apple-Iphone5s-1_PT7955
,2015-11-30 12:01:14.546 ThaliTest[995:6807] server session: disconnect
,2015-11-30 12:01:14.548 ThaliTest[995:6807] server session: stateChange:2->0 Apple-Iphone6-1_PT7389
,2015-11-30 12:01:14.550 ThaliTest[995:6807] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-11-30T11:01:14.568Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-30T11:01:14.570Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-30T11:01:14.571Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-30T11:01:14.571Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT7955.qINS9Q==\",\"time\":3701,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-IpadAir2-1_PT4872.+CDkQA==\",\"time\":4617,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone6-1_PT7389.2i+JNA==\",\"time\":304494,,\"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000}],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called

```
