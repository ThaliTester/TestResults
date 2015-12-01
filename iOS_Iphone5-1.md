#### Test 52320939cae1769_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52320939cae1769/build_ios/ThaliTest.app
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
,(lldb) command source -s 0 '/tmp/FFF436FE-C585-4208-805F-7A8C0B68E868/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/FFF436FE-C585-4208-805F-7A8C0B68E868/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52320939cae1769/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52320939cae1769/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/66A050B5-F9F4-4D89-98D4-848400D09A20/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58814"
,(lldb)     command script import "/tmp/FFF436FE-C585-4208-805F-7A8C0B68E868/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-01 23:02:23.716 ThaliTest[1056:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-01 23:02:23.719 ThaliTest[1056:60b] Multi-tasking -> Device: YES, App: YES
,2015-12-01 23:02:23.728 ThaliTest[1056:60b] Unlimited access to network resources
,2015-12-01 23:02:23.734 ThaliTest[1056:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.app,le.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-01 23:02:34.447 ThaliTest[1056:60b] Resetting plugins due to page load.
,2015-12-01 23:02:35.316 ThaliTest[1056:60b] Finished load of: file:///var/mobile/Applications/66A050B5-F9F4-4D89-98D4-848400D09A20/ThaliTest.app/www/index.html
,2015-12-01 23:02:35.502 ThaliTest[1056:60b] JXcore Cordova plugin initializing
,2015-12-01 23:02:35.503 ThaliTest[1056:6807] JXcore instance initializing
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
,my name is : Apple-Iphone5-1_PT2043
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
serverPort is 58163
,2015-12-01 23:08:19.136 ThaliTest[1056:6807] jxcore: startBroadcasting
,2015-12-01 23:08:19.147 ThaliTest[1056:6807] server: starting Apple-Iphone5-1_PT2043.ooMPSg==
2015-12-01 23:08:19.149 ThaliTest[1056:6807] multipeer session: start timer: 0x1cde1370
2015-12-01 23:08:19.150 ThaliTest[1056:6807] THEMultipeerSession initialized peer Apple-Iphone5-1_PT2043
,2015-12-01 23:08:19.160 ThaliTest[1056:6807] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-01T22:08:19.164Z SendDataTCPServer.js: TCP/IP server is bound to port: 58163
,2015-12-01 23:08:20.026 ThaliTest[1056:60b] client: found peer: Apple-Iphone6-1_PT8318.eAU97Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8318.eAU97Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
device[1]: Apple-Iphone6-1_PT8318.eAU97Q==
2015-12-01T22:08:20.031Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8318.eAU97Q==
,2015-12-01T22:08:20.032Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8318.eAU97Q==
2015-12-01T22:08:20.032Z SendDataConnector.js: do connect now
,2015-12-01 23:08:20.033 ThaliTest[1056:6807] jxcore: connect Apple-Iphone6-1_PT8318.eAU97Q==
,2015-12-01 23:08:20.034 ThaliTest[1056:6807] client session: connect
,2015-12-01 23:08:20.034 ThaliTest[1056:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT8318.eAU97Q==
,2015-12-01 23:08:20.335 ThaliTest[1056:60b] client: found peer: Apple-IpadAir2-1_PT2654.X9QXJA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2654.X9QXJA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-01 23:08:20.428 ThaliTest[1056:60b] multipeer session: reset timer
,2015-12-01 23:08:20.430 ThaliTest[1056:60b] multipeer session: stop timer
,2015-12-01 23:08:20.431 ThaliTest[1056:60b] multipeer session: start timer: 0x1cde1370
,2015-12-01 23:08:20.432 ThaliTest[1056:60b] server session: connect
,2015-12-01 23:08:20.432 ThaliTest[1056:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT2654
,2015-12-01 23:08:20.435 ThaliTest[1056:60b] server: accepting invitation Apple-IpadAir2-1_PT2654
,2015-12-01 23:08:21.278 ThaliTest[1056:60b] multipeer session: reset timer
,2015-12-01 23:08:21.279 ThaliTest[1056:60b] multipeer session: stop timer
2015-12-01 23:08:21.280 ThaliTest[1056:60b] multipeer session: start timer: 0x1cde1370
,2015-12-01 23:08:21.281 ThaliTest[1056:60b] server session: connect
,2015-12-01 23:08:21.281 ThaliTest[1056:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT8318
,2015-12-01 23:08:21.285 ThaliTest[1056:60b] server: accepting invitation Apple-Iphone6-1_PT8318
,2015-12-01 23:08:22.729 ThaliTest[1056:1443] client session: connected
2015-12-01 23:08:22.730 ThaliTest[1056:60b] client: found peer: Apple-Iphone5s-1_PT9471.ZBmsZA==
2015-12-01 23:08:22.730 ThaliTest[1056:1443] client session: stateChange:1->2 Apple-Ip,hone6-1_PT8318.eAU97Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9471.ZBmsZA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-01 23:08:22.736 ThaliTest[1056:780b] client session: fireConnectCallback: Apple-Iphone6-1_PT8318.eAU97Q==
,2015-12-01 23:08:22.737 ThaliTest[1056:780b] jxcore: connect: success
,2015-12-01T22:08:22.740Z SendDataConnector.js: CLIENT connected to 58166, error: null
,2015-12-01T22:08:22.740Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 23:08:22.741 ThaliTest[1056:60b] client: relay established
2015-12-01 23:08:22.742 ThaliTest[1056:60b] client: new accepted socket: 0x1cdf0e80
,2015-12-01T22:08:22.755Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01 23:08:22.924 ThaliTest[1056:1443] server session: connected
2015-12-01 23:08:22.925 ThaliTest[1056:1443] server session: stateChange:1->2 Apple-IpadAir2-1_PT2654
,2015-12-01 23:08:22.934 ThaliTest[1056:60b] server relay: connected (to port: 58163)
,2015-12-01T22:08:23.265Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T22:08:23.279Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-01T22:08:23.319Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-01T22:08:23.326Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-01T22:08:23.344Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01T22:08:23.345Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-01 23:08:23.354 ThaliTest[1056:760f] server session: not connected Apple-IpadAir2-1_PT2654
,2015-12-01T22:08:23.368Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-01T22:08:23.391Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-01T22:08:23.406Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-01T22:08:23.420Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-01T22:08:23.421Z SendDataConnector.js: got all data for this round
,2015-12-01T22:08:23.423Z SendDataConnector.js: CLIENT Stop now
2015-12-01T22:08:23.424Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 23:08:23.425 ThaliTest[1056:6807] jxcore: disconnect
,2015-12-01 23:08:23.427 ThaliTest[1056:6807] client session: disconnectFromPeer: Apple-Iphone6-1_PT8318.eAU97Q==
,2015-12-01 23:08:23.429 ThaliTest[1056:6807] client session: disconnect
,2015-12-01 23:08:23.431 ThaliTest[1056:6807] client session: stateChange:2->0 Apple-Iphone6-1_PT8318.eAU97Q==
,2015-12-01 23:08:23.463 ThaliTest[1056:780b] server session: connected
,2015-12-01 23:08:23.466 ThaliTest[1056:780b] server session: stateChange:1->2 Apple-Iphone6-1_PT8318
,2015-12-01 23:08:23.469 ThaliTest[1056:60b] server relay: connected (to port: 58163)
,2015-12-01 23:08:24.393 ThaliTest[1056:6807] jxcore: disconnect: success
,2015-12-01T22:08:24.395Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8318.eAU97Q==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT2654.X9QXJA==
2015-12-01T22:08:24.396Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2654.X9QXJA==
2015-12-01T22:08:24.397Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2654.X9QXJA==
2015-12-01T22:08:24.397Z SendDataConnector.js: do connect now
,2015-12-01 23:08:24.397 ThaliTest[1056:6807] jxcore: connect Apple-IpadAir2-1_PT2654.X9QXJA==
,2015-12-01 23:08:24.399 ThaliTest[1056:6807] client session: connect
,2015-12-01 23:08:24.400 ThaliTest[1056:6807] client session: stateChange:0->1 Apple-IpadAir2-1_PT2654.X9QXJA==
,2015-12-01T22:08:24.419Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T22:08:24.432Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01 23:08:24.495 ThaliTest[1056:8103] server session: not connected Apple-Iphone6-1_PT8318
,2015-12-01 23:08:27.545 ThaliTest[1056:8103] client session: connected
,2015-12-01 23:08:27.546 ThaliTest[1056:8103] client session: stateChange:1->2 Apple-IpadAir2-1_PT2654.X9QXJA==
,2015-12-01 23:08:27.554 ThaliTest[1056:8103] client session: fireConnectCallback: Apple-IpadAir2-1_PT2654.X9QXJA==
,2015-12-01 23:08:27.555 ThaliTest[1056:8103] jxcore: connect: success
,2015-12-01T22:08:27.556Z SendDataConnector.js: CLIENT connected to 58171, error: null
2015-12-01T22:08:27.557Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 23:08:27.558 ThaliTest[1056:60b] client: relay established
2015-12-01 23:08:27.559 ThaliTest[1056:60b] client: new accepted socket: 0x1ce3c610
,2015-12-01T22:08:27.570Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T22:08:28.160Z SendDataConnector.js: CLIENT is data received : 90000

```
