#### Test 52320939cae1769_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52320939cae1769/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/48E7929B-99DA-44B8-A4A9-D712FF59792E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/48E7929B-99DA-44B8-A4A9-D712FF59792E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52320939cae1769/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52320939cae1769/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5782E56D-D7D8-4343-94BB-D7C1E16774DF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58812"
,(lldb)     command script import "/tmp/48E7929B-99DA-44B8-A4A9-D712FF59792E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-01 23:01:28.654 ThaliTest[2348:2009149] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/548B5505-8C0F-48E0-BBDF-DE76C3B60513/Library/Cookies/Cookies.binarycookies
,2015-12-01 23:01:29.025 ThaliTest[2348:2009149] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-01 23:01:29.026 ThaliTest[2348:2009149] Multi-tasking -> Device: YES, App: YES
,2015-12-01 23:01:29.034 ThaliTest[2348:2009149] Unlimited access to network resources
,2015-12-01 23:01:29.040 ThaliTest[2348:2009149] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-01 23:01:32.572 ThaliTest[2348:2009149] Resetting plugins due to page load.
,2015-12-01 23:01:32.903 ThaliTest[2348:2009149] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/5782E56D-D7D8-4343-94BB-D7C1E16774DF/ThaliTest.app/www/index.html
,2015-12-01 23:01:33.025 ThaliTest[2348:2009149] JXcore Cordova plugin initializing
2015-12-01 23:01:33.026 ThaliTest[2348:2009415] JXcore instance initializing
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
,my name is : Apple-Iphone6-1_PT8318
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 64139
,2015-12-01 23:08:17.655 ThaliTest[2348:2009415] jxcore: startBroadcasting
,2015-12-01 23:08:17.667 ThaliTest[2348:2009415] server: starting Apple-Iphone6-1_PT8318.eAU97Q==
,2015-12-01 23:08:17.668 ThaliTest[2348:2009415] multipeer session: start timer: 0x1c74f1b0
2015-12-01 23:08:17.669 ThaliTest[2348:2009415] THEMultipeerSession initialized peer Apple-Iphone6-1_PT8318
2015-12-01 23:08:17.670 ThaliTest[2348:2009415] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-01T22:08:17.673Z SendDataTCPServer.js: TCP/IP server is bound to port: 64139
,2015-12-01 23:08:18.106 ThaliTest[2348:2009149] client: found peer: Apple-Iphone5-1_PT2043.ooMPSg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2043.ooMPSg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5-1_PT2043.ooMPSg==
,2015-12-01T22:08:18.112Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2043.ooMPSg==
,2015-12-01T22:08:18.112Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2043.ooMPSg==
,2015-12-01T22:08:18.112Z SendDataConnector.js: do connect now
,2015-12-01 23:08:18.114 ThaliTest[2348:2009415] jxcore: connect Apple-Iphone5-1_PT2043.ooMPSg==
2015-12-01 23:08:18.115 ThaliTest[2348:2009415] client session: connect
2015-12-01 23:08:18.115 ThaliTest[2348:2009415] client session: stateChange:0->1 Apple-Iphone5-1_PT2043.ooMPSg==
,2015-12-01 23:08:18.380 ThaliTest[2348:2009149] multipeer session: reset timer
2015-12-01 23:08:18.381 ThaliTest[2348:2009149] multipeer session: stop timer
2015-12-01 23:08:18.381 ThaliTest[2348:2009149] multipeer session: start timer: 0x1c74f1b0
2015-12-01 23:08:18.381 ThaliTest[2348:2009149] server session: connect
2015-12-01 23:08:18.381 ThaliTest[2348:2009149] server session: stateChange:0->1 Apple-Iphone5-1_PT2043
,2015-12-01 23:08:18.384 ThaliTest[2348:2009149] server: accepting invitation Apple-Iphone5-1_PT2043
,2015-12-01 23:08:19.110 ThaliTest[2348:2009149] client: found peer: Apple-IpadAir2-1_PT2654.X9QXJA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2654.X9QXJA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-01 23:08:20.226 ThaliTest[2348:2009149] multipeer session: reset timer
2015-12-01 23:08:20.227 ThaliTest[2348:2009149] multipeer session: stop timer
2015-12-01 23:08:20.228 ThaliTest[2348:2009149] multipeer session: start timer: 0x1c74f1b0
2015-,12-01 23:08:20.228 ThaliTest[2348:2009149] server session: connect
2015-12-01 23:08:20.229 ThaliTest[2348:2009149] server session: stateChange:0->1 Apple-Iphone5s-1_PT9471
,2015-12-01 23:08:20.237 ThaliTest[2348:2009149] server: accepting invitation Apple-Iphone5s-1_PT9471
,2015-12-01 23:08:20.636 ThaliTest[2348:2009982] server session: connected
2015-12-01 23:08:20.638 ThaliTest[2348:2009982] server session: stateChange:1->2 Apple-Iphone5-1_PT2043
2015-12-01 23:08:20.639 ThaliTest[2348:2009149] client: found peer: Apple-Ip,hone5s-1_PT9471.ZBmsZA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9471.ZBmsZA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-01 23:08:20.650 ThaliTest[2348:2009149] server relay: connected (to port: 64139)
,2015-12-01T22:08:20.657Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T22:08:21.216Z SendDataTCPServer.js: TCP/IP server has received 11904 bytes of data
,2015-12-01T22:08:21.233Z SendDataTCPServer.js: TCP/IP server has received 27776 bytes of data
,2015-12-01T22:08:21.249Z SendDataTCPServer.js: TCP/IP server has received 40672 bytes of data
,2015-12-01T22:08:21.264Z SendDataTCPServer.js: TCP/IP server has received 50592 bytes of data
,2015-12-01T22:08:21.278Z SendDataTCPServer.js: TCP/IP server has received 59520 bytes of data
,2015-12-01T22:08:21.291Z SendDataTCPServer.js: TCP/IP server has received 70432 bytes of data
,2015-12-01T22:08:21.305Z SendDataTCPServer.js: TCP/IP server has received 81344 bytes of data
,2015-12-01T22:08:21.317Z SendDataTCPServer.js: TCP/IP server has received 96224 bytes of data
,2015-12-01T22:08:21.328Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01 23:08:21.349 ThaliTest[2348:2009983] server session: not connected Apple-Iphone5-1_PT2043
,2015-12-01 23:08:21.370 ThaliTest[2348:2009985] client session: connected
2015-12-01 23:08:21.371 ThaliTest[2348:2009985] client session: stateChange:1->2 Apple-Iphone5-1_PT2043.ooMPSg==
,2015-12-01 23:08:21.381 ThaliTest[2348:2009974] client session: fireConnectCallback: Apple-Iphone5-1_PT2043.ooMPSg==
2015-12-01 23:08:21.382 ThaliTest[2348:2009974] jxcore: connect: success
,2015-12-01T22:08:21.384Z SendDataConnector.js: CLIENT connected to 64143, error: null
2015-12-01T22:08:21.384Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 23:08:21.388 ThaliTest[2348:2009149] client: relay established
2015-12-01 23:08:21.388 ThaliTest[2348:2009149] client: new accepted socket: 0x1c7688f0
,2015-12-01T22:08:21.401Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01 23:08:21.453 ThaliTest[2348:2009149] multipeer session: reset timer
2015-12-01 23:08:21.454 ThaliTest[2348:2009149] multipeer session: stop timer
2015-12-01 23:08:21.454 ThaliTest[2348:2009149] multipeer session: start timer: 0x1c74f1b0
2015-,12-01 23:08:21.455 ThaliTest[2348:2009149] server session: connect
2015-12-01 23:08:21.455 ThaliTest[2348:2009149] server session: stateChange:0->1 Apple-IpadAir2-1_PT2654
,2015-12-01 23:08:21.467 ThaliTest[2348:2009149] server: accepting invitation Apple-IpadAir2-1_PT2654
,2015-12-01T22:08:22.372Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-01T22:08:22.386Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-01T22:08:22.387Z SendDataConnector.js: got all data for this round
,2015-12-01T22:08:22.389Z SendDataConnector.js: CLIENT Stop now
,2015-12-01T22:08:22.391Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 23:08:22.393 ThaliTest[2348:2009415] jxcore: disconnect
2015-12-01 23:08:22.394 ThaliTest[2348:2009415] client session: disconnectFromPeer: Apple-Iphone5-1_PT2043.ooMPSg==
2015-12-01 23:08:22.394 ThaliTest[2348:2009415] client session: disconn,ect
2015-12-01 23:08:22.395 ThaliTest[2348:2009415] client session: stateChange:2->0 Apple-Iphone5-1_PT2043.ooMPSg==
,2015-12-01 23:08:22.398 ThaliTest[2348:2009415] jxcore: disconnect: success
2015-12-01T22:08:22.402Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2043.ooMPSg==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT2654.X9QXJA==
2015-12-01T22:08:22.405Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2654.X9QXJA==
2015-12-01T22:08:22.406Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2654.X9QXJA==
2015-12-01T22:08:22.406Z SendDataConnector.js: do connect now
,2015-12-01 23:08:22.407 ThaliTest[2348:2009415] jxcore: connect Apple-IpadAir2-1_PT2654.X9QXJA==
2015-12-01 23:08:22.408 ThaliTest[2348:2009415] client session: connect
2015-12-01 23:08:22.408 ThaliTest[2348:2009415] client session: stateChange:0->1 Appl,e-IpadAir2-1_PT2654.X9QXJA==
,2015-12-01 23:08:22.809 ThaliTest[2348:2009982] server session: connected
2015-12-01 23:08:22.809 ThaliTest[2348:2009982] server session: stateChange:1->2 Apple-Iphone5s-1_PT9471
,2015-12-01 23:08:22.821 ThaliTest[2348:2009149] server relay: connected (to port: 64139)
,2015-12-01T22:08:22.826Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T22:08:23.301Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-01T22:08:23.319Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-01T22:08:23.335Z SendDataTCPServer.js: TCP/IP server has received 63226 bytes of data
,2015-12-01T22:08:23.354Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-01T22:08:23.370Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01 23:08:23.953 ThaliTest[2348:2009983] server session: connected
2015-12-01 23:08:23.953 ThaliTest[2348:2009983] server session: stateChange:1->2 Apple-IpadAir2-1_PT2654
,2015-12-01 23:08:23.973 ThaliTest[2348:2009149] server relay: connected (to port: 64139)
,2015-12-01T22:08:23.982Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T22:08:24.346Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-01T22:08:24.358Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-01T22:08:24.373Z SendDataTCPServer.js: TCP/IP server has received 30518 bytes of data
,2015-12-01T22:08:24.391Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-01T22:08:24.407Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-01T22:08:24.423Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01 23:08:25.449 ThaliTest[2348:2009985] client session: connected
2015-12-01 23:08:25.450 ThaliTest[2348:2009985] client session: stateChange:1->2 Apple-IpadAir2-1_PT2654.X9QXJA==
,2015-12-01 23:08:25.459 ThaliTest[2348:2009985] client session: fireConnectCallback: Apple-IpadAir2-1_PT2654.X9QXJA==
2015-12-01 23:08:25.460 ThaliTest[2348:2009985] jxcore: connect: success
,2015-12-01T22:08:25.461Z SendDataConnector.js: CLIENT connected to 64148, error: null
,2015-12-01T22:08:25.462Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 23:08:25.466 ThaliTest[2348:2009149] client: relay established
2015-12-01 23:08:25.466 ThaliTest[2348:2009149] client: new accepted socket: 0x1c775560
,2015-12-01T22:08:25.477Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T22:08:25.936Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-01 23:08:33.635 ThaliTest[2348:2009974] server session: not connected Apple-Iphone5s-1_PT9471
,2015-12-01 23:08:34.471 ThaliTest[2348:2009985] server session: not connected Apple-IpadAir2-1_PT2654

```
