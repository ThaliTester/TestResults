#### Test 52971095c7b67a5_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52971095c7b67a5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/96CE8FF0-2152-43D3-9F71-AFBF299B24B4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/96CE8FF0-2152-43D3-9F71-AFBF299B24B4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52971095c7b67a5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52971095c7b67a5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5324AEA4-8C1A-41C1-8057-18FBCB99CD52/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50642"
,(lldb)     command script import "/tmp/96CE8FF0-2152-43D3-9F71-AFBF299B24B4/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-08 13:06:30.011 ThaliTest[427:260097] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FE95B7FD-4CDD-4B7F-B1B6-9F7340FEFE73/Library/Cookies/Cookies.binarycookies
,2015-12-08 13:06:30.032 ThaliTest[427:260097] <CATransformLayer: 0x16e2ae20> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-08 13:06:30.033 ThaliTest[427:260097] <CATransformLayer: 0x16f235f0> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-08 13:06:30.034 ThaliTest[427:260097] <CATransformLayer: 0x16f26ec0> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-08 13:06:30.382 ThaliTest[427:260097] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-08 13:06:30.382 ThaliTest[427:260097] Multi-tasking -> Device: YES, App: YES
,2015-12-08 13:06:30.390 ThaliTest[427:260097] Unlimited access to network resources
,2015-12-08 13:06:30.396 ThaliTest[427:260097] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-08 13:06:39.215 ThaliTest[427:260097] Resetting plugins due to page load.
,2015-12-08 13:06:42.432 ThaliTest[427:260097] Finished load of: file:///var/mobile/Containers/Bundle/Application/5324AEA4-8C1A-41C1-8057-18FBCB99CD52/ThaliTest.app/www/index.html
,2015-12-08 13:06:42.574 ThaliTest[427:260097] JXcore Cordova plugin initializing
,2015-12-08 13:06:42.574 ThaliTest[427:260360] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
Warning: iOS does not support ToggleBluetooth
Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-IpadAir2-1_PT3979
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 50927
,2015-12-08 13:13:00.370 ThaliTest[427:260360] jxcore: startBroadcasting
,2015-12-08 13:13:00.383 ThaliTest[427:260360] server: starting Apple-IpadAir2-1_PT3979.Fg9L1g==
,2015-12-08 13:13:00.383 ThaliTest[427:260360] multipeer session: start timer: 0x16f02470
,2015-12-08 13:13:00.384 ThaliTest[427:260360] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT3979
2015-12-08 13:13:00.386 ThaliTest[427:260360] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-08T12:13:00.389Z SendDataTCPServer.js: TCP/IP server is bound to port: 50927
,2015-12-08 13:13:02.619 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8639.zsASLQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08T12:13:02.625Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08T12:13:02.626Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08T12:13:02.627Z SendDataConnector.js: do connect now
,2015-12-08 13:13:02.627 ThaliTest[427:260360] jxcore: connect Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:13:02.628 ThaliTest[427:260360] client session: connect
2015-12-08 13:13:02.629 ThaliTest[427:260360] client session: stateChange:0->1 Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:13:02.983 ThaliTest[427:260097] multipeer session: reset timer
2015-12-08 13:13:02.984 ThaliTest[427:260097] multipeer session: stop timer
,2015-12-08 13:13:02.984 ThaliTest[427:260097] multipeer session: start timer: 0x16f02470
,2015-12-08 13:13:02.984 ThaliTest[427:260097] server session: connect
2015-12-08 13:13:02.985 ThaliTest[427:260097] server session: stateChange:0->1 Apple-Iphone5s-1_PT8639
,2015-12-08 13:13:02.992 ThaliTest[427:260097] server: accepting invitation Apple-Iphone5s-1_PT8639
,2015-12-08 13:13:04.265 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT785.mqQzsA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-08 13:13:05.340 ThaliTest[427:260097] multipeer session: reset timer
2015-12-08 13:13:05.340 ThaliTest[427:260097] multipeer session: stop timer
2015-12-08 13:13:05.340 ThaliTest[427:260097] multipeer session: start timer: 0x16f02470
2015-12-08 ,13:13:05.340 ThaliTest[427:260097] server session: connect
2015-12-08 13:13:05.340 ThaliTest[427:260097] server session: stateChange:0->1 Apple-Iphone5-1_PT785
2015-12-08 13:13:05.343 ThaliTest[427:260097] server: accepting invitation Apple-Iphone5-1_PT785
,2015-12-08 13:13:07.081 ThaliTest[427:261022] server session: connected
2015-12-08 13:13:07.082 ThaliTest[427:261022] server session: stateChange:1->2 Apple-Iphone5s-1_PT8639
,2015-12-08 13:13:07.137 ThaliTest[427:260097] server relay: connected (to port: 50927)
,2015-12-08T12:13:07.145Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08T12:13:07.435Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-08T12:13:07.474Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-08T12:13:07.488Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-08T12:13:07.504Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 13:13:07.612 ThaliTest[427:261021] server session: not connected Apple-Iphone5s-1_PT8639
,2015-12-08 13:13:07.931 ThaliTest[427:261021] client session: connected
,2015-12-08 13:13:07.931 ThaliTest[427:261021] client session: stateChange:1->2 Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:13:07.994 ThaliTest[427:261033] client session: fireConnectCallback: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:13:07.994 ThaliTest[427:261033] jxcore: connect: success
,2015-12-08T12:13:07.996Z SendDataConnector.js: CLIENT connected to 50931, error: null
,2015-12-08T12:13:07.997Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 13:13:07.999 ThaliTest[427:260097] client: relay established
2015-12-08 13:13:08.000 ThaliTest[427:260097] client: new accepted socket: 0x18eb2b70
,2015-12-08T12:13:08.016Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T12:13:08.531Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-08T12:13:08.545Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-08T12:13:08.573Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-08T12:13:08.587Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-08 13:13:09.049 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4714.SIFsmA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-08T12:13:09.177Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-08T12:13:09.178Z SendDataConnector.js: got all data for this round
2015-12-08T12:13:09.180Z SendDataConnector.js: CLIENT Stop now
2015-12-08T12:13:09.180Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 13:13:09.182 ThaliTest[427:260360] jxcore: disconnect
2015-12-08 13:13:09.184 ThaliTest[427:260360] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:13:09.184 ThaliTest[427:260360] client session: disconnect
,2015-12-08 13:13:09.185 ThaliTest[427:260360] client session: stateChange:2->0 Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:13:09.259 ThaliTest[427:260360] jxcore: disconnect: success
,2015-12-08T12:13:09.260Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8639.zsASLQ==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08T12:13:09.262Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08T12:13:09.263Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08T12:13:09.263Z SendDataConnector.js: do connect now
,2015-12-08 13:13:09.264 ThaliTest[427:260360] jxcore: connect Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:13:09.265 ThaliTest[427:260360] client session: connect
,2015-12-08 13:13:09.265 ThaliTest[427:260360] client session: stateChange:0->1 Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:13:09.453 ThaliTest[427:261020] server session: connected
,2015-12-08 13:13:09.453 ThaliTest[427:261020] server session: stateChange:1->2 Apple-Iphone5-1_PT785
,2015-12-08 13:13:09.476 ThaliTest[427:260097] server relay: connected (to port: 50927)
,2015-12-08T12:13:09.487Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08T12:13:10.141Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-08T12:13:10.156Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-08T12:13:10.173Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-08T12:13:10.190Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 13:13:10.493 ThaliTest[427:261074] server session: not connected Apple-Iphone5-1_PT785
,2015-12-08 13:13:20.896 ThaliTest[427:261074] client session: not connected Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:13:20.896 ThaliTest[427:261074] client session: onLinkFailure: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:13:20.897 ThaliTest[427:261074] client session: disconnect
,2015-12-08 13:13:20.898 ThaliTest[427:261074] client session: stateChange:1->0 Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:13:20.898 ThaliTest[427:261074] client session: fireConnectCallback: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:13:20.899 ThaliTest[427:261074] jxcore: connect: fail: Peer disconnected
,2015-12-08T12:13:20.901Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-08T12:13:20.901Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-08T12:13:20.902Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-08 13:13:22.275 ThaliTest[427:260097] multipeer session: reset timer
2015-12-08 13:13:22.275 ThaliTest[427:260097] multipeer session: stop timer
,2015-12-08 13:13:22.276 ThaliTest[427:260097] multipeer session: start timer: 0x16f02470
,2015-12-08 13:13:22.276 ThaliTest[427:260097] server session: connect
,2015-12-08 13:13:22.276 ThaliTest[427:260097] server session: stateChange:0->1 Apple-Iphone6-1_PT4714
,2015-12-08 13:13:22.283 ThaliTest[427:260097] server: accepting invitation Apple-Iphone6-1_PT4714
,2015-12-08 13:13:25.248 ThaliTest[427:261021] server session: connected
2015-12-08 13:13:25.249 ThaliTest[427:261021] server session: stateChange:1->2 Apple-Iphone6-1_PT4714
,2015-12-08 13:13:25.429 ThaliTest[427:260097] server relay: connected (to port: 50927)
,2015-12-08T12:13:25.431Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08T12:13:25.904Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08T12:13:25.905Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08T12:13:25.953Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-08T12:13:25.969Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-08T12:13:25.985Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-08T12:13:26.014Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-08T12:13:26.136Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 13:13:26.179 ThaliTest[427:261021] server session: not connected Apple-Iphone6-1_PT4714
,2015-12-08 13:13:30.908 ThaliTest[427:260360] jxcore: disconnect
,2015-12-08 13:13:30.909 ThaliTest[427:260360] jxcore: disconnect: fail
,2015-12-08T12:13:30.910Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08T12:13:30.911Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT785.mqQzsA== with availability status: true
,2015-12-08T12:13:30.911Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08T12:13:30.912Z SendDataConnector.js: do connect now
,2015-12-08 13:13:30.913 ThaliTest[427:260360] jxcore: connect Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:13:30.913 ThaliTest[427:260360] client session: connect
,2015-12-08 13:13:30.914 ThaliTest[427:260360] client session: stateChange:0->1 Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:13:39.326 ThaliTest[427:261021] client session: connected
2015-12-08 13:13:39.327 ThaliTest[427:261021] client session: stateChange:1->2 Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:13:39.348 ThaliTest[427:261112] client session: fireConnectCallback: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:13:39.349 ThaliTest[427:261112] jxcore: connect: success
,2015-12-08T12:13:39.350Z SendDataConnector.js: CLIENT connected to 50937, error: null
,2015-12-08T12:13:39.351Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 13:13:39.353 ThaliTest[427:260097] client: relay established
2015-12-08 13:13:39.354 ThaliTest[427:260097] client: new accepted socket: 0x18f679f0
,2015-12-08T12:13:39.367Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T12:13:39.983Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-08T12:13:39.984Z SendDataConnector.js: got all data for this round
,2015-12-08T12:13:39.985Z SendDataConnector.js: CLIENT Stop now
,2015-12-08T12:13:39.986Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 13:13:39.987 ThaliTest[427:260360] jxcore: disconnect
,2015-12-08 13:13:39.988 ThaliTest[427:260360] client session: disconnectFromPeer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:13:39.988 ThaliTest[427:260360] client session: disconnect
2015-12-08 13:13:39.989 ThaliTest[427:260360] client session: stateChange:2->0 Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:13:40.063 ThaliTest[427:260360] jxcore: disconnect: success
2015-12-08T12:13:40.064Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT785.mqQzsA==
,---- round done--------
,device[3]: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08T12:13:40.067Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08T12:13:40.068Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08T12:13:40.069Z SendDataConnector.js: do connect now
,2015-12-08 13:13:40.070 ThaliTest[427:260360] jxcore: connect Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:13:40.071 ThaliTest[427:260360] client session: connect
2015-12-08 13:13:40.071 ThaliTest[427:260360] client session: stateChange:0->1 Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:13:52.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:13:52.307 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:13:52.307 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:13:52.429 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:14:13.044 ThaliTest[427:261268] client session: not connected Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:14:13.044 ThaliTest[427:261268] client session: onLinkFailure: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:14:13.045 ThaliTest[427:261268] client session: disconnect
2015-12-08 13:14:13.045 ThaliTest[427:261268] client session: stateChange:1->0 Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:14:13.046 ThaliTest[427:261268] client session: fireConnectCallback: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:14:13.047 ThaliTest[427:261268] jxcore: connect: fail: Peer disconnected
,2015-12-08T12:14:13.048Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-08T12:14:13.049Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-08T12:14:13.049Z SendDataConnector.js: tryAgain afer: 5000 ms.,
,2015-12-08T12:14:18.054Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08T12:14:18.055Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:14:22.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:14:22.305 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:14:22.305 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:14:22.305 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:14:23.063 ThaliTest[427:260360] jxcore: disconnect
2015-12-08 13:14:23.064 ThaliTest[427:260360] jxcore: disconnect: fail
,2015-12-08T12:14:23.065Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08T12:14:23.065Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT4714.SIFsmA== with availability status: true
,2015-12-08T12:14:23.066Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08T12:14:23.066Z SendDataConnector.js: do connect now
,2015-12-08 13:14:23.067 ThaliTest[427:260360] jxcore: connect Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:14:23.068 ThaliTest[427:260360] client session: connect
2015-12-08 13:14:23.068 ThaliTest[427:260360] client session: stateChange:0->1 Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:14:52.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:14:52.311 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:14:52.311 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:14:52.311 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:14:56.053 ThaliTest[427:261367] client session: not connected Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:14:56.053 ThaliTest[427:261367] client session: onLinkFailure: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:14:56.054 ThaliTest[427:261367] client session: disconnect
,2015-12-08 13:14:56.054 ThaliTest[427:261367] client session: stateChange:1->0 Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:14:56.056 ThaliTest[427:261367] client session: fireConnectCallback: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:14:56.056 ThaliTest[427:261367] jxcore: connect: fail: Peer disconnected
,2015-12-08T12:14:56.058Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-08T12:14:56.058Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-08T12:14:56.059Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-08T12:15:01.067Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08T12:15:01.067Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:15:06.069 ThaliTest[427:260360] jxcore: disconnect
,2015-12-08 13:15:06.070 ThaliTest[427:260360] jxcore: disconnect: fail
,2015-12-08T12:15:06.072Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08T12:15:06.072Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT4714.SIFsmA== with availability status: ,true
2015-12-08T12:15:06.072Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08T12:15:06.073Z SendDataConnector.js: do connect now
,2015-12-08 13:15:06.074 ThaliTest[427:260360] jxcore: connect Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:15:06.075 ThaliTest[427:260360] client session: connect
,2015-12-08 13:15:06.076 ThaliTest[427:260360] client session: stateChange:0->1 Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:15:19.521 ThaliTest[427:260097] client: lost peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:15:19.521 ThaliTest[427:260097] client session: onPeerLost: Apple-Iphone5s-1_PT8639.zsASLQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8639.zsASLQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-08 13:15:22.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:15:22.302 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:15:22.303 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:15:22.484 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8639.zsASLQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-08 13:15:39.079 ThaliTest[427:261468] client session: not connected Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:15:39.079 ThaliTest[427:261468] client session: onLinkFailure: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:15:39.080 ThaliTest[427:261468] client session: disconnect
,2015-12-08 13:15:39.081 ThaliTest[427:261468] client session: stateChange:1->0 Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:15:39.082 ThaliTest[427:261468] client session: fireConnectCallback: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:15:39.082 ThaliTest[427:261468] jxcore: connect: fail: Peer disconnected
,2015-12-08T12:15:39.083Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-08T12:15:39.084Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-08T12:15:39.084Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-08T12:15:44.096Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08T12:15:44.097Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:15:49.100 ThaliTest[427:260360] jxcore: disconnect
,2015-12-08 13:15:49.101 ThaliTest[427:260360] jxcore: disconnect: fail
,2015-12-08T12:15:49.102Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08T12:15:49.103Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT4714.SIFsmA== with availability status: true
,2015-12-08T12:15:49.103Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08T12:15:49.104Z SendDataConnector.js: do connect now
,2015-12-08 13:15:49.105 ThaliTest[427:260360] jxcore: connect Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:15:49.105 ThaliTest[427:260360] client session: connect
,2015-12-08 13:15:49.107 ThaliTest[427:260360] client session: stateChange:0->1 Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:15:52.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:15:52.305 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:15:52.305 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:15:52.306 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:16:22.109 ThaliTest[427:261717] client session: not connected Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:16:22.109 ThaliTest[427:261717] client session: onLinkFailure: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:16:22.110 ThaliTest[427:261717] client session: disconnect
,2015-12-08 13:16:22.110 ThaliTest[427:261717] client session: stateChange:1->0 Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:16:22.112 ThaliTest[427:261717] client session: fireConnectCallback: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:16:22.112 ThaliTest[427:261717] jxcore: connect: fail: Peer disconnected
,2015-12-08T12:16:22.114Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-12-08T12:16:22.114Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-08T12:16:22.115Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-08 13:16:22.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:16:22.302 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:16:22.302 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:16:22.303 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08T12:16:27.125Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08T12:16:27.126Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4714.SIFsmA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:16:32.139 ThaliTest[427:260360] jxcore: disconnect
,2015-12-08 13:16:32.139 ThaliTest[427:260360] jxcore: disconnect: fail
,2015-12-08T12:16:32.140Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08T12:16:32.141Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT4714.SIFsmA== with availability status: true
,2015-12-08T12:16:32.141Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08T12:16:32.141Z SendDataConnector.js: do connect now
,2015-12-08 13:16:32.142 ThaliTest[427:260360] jxcore: connect Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:16:32.142 ThaliTest[427:260360] client session: connect
2015-12-08 13:16:32.142 ThaliTest[427:260360] client session: stateChange:0->1 Apple-Iphon,e6-1_PT4714.SIFsmA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:16:52.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:16:52.310 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:16:52.310 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:16:52.311 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:17:05.139 ThaliTest[427:261865] client session: not connected Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:17:05.140 ThaliTest[427:261865] client session: onLinkFailure: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:17:05.140 ThaliTest[427:261865] client session: disconnect
,2015-12-08 13:17:05.141 ThaliTest[427:261865] client session: stateChange:1->0 Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:17:05.142 ThaliTest[427:261865] client session: fireConnectCallback: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:17:05.143 ThaliTest[427:261865] jxcore: connect: fail: Peer disconnected
,2015-12-08T12:17:05.144Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-08T12:17:05.144Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-08T12:17:05.145Z SendDataConnector.js: CLIENT Stop now
2015-1,2-08 13:17:05.146 ThaliTest[427:260360] jxcore: disconnect
2015-12-08 13:17:05.147 ThaliTest[427:260360] jxcore: disconnect: fail
2015-12-08T12:17:05.147Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4714.SIFsmA==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT3979","time":244794,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT8639.zsASLQ==","time":6553,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-,1_PT785.mqQzsA==","time":30721,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT4714.SIFsmA==","time":205077,"result":"Peer disconnected","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0}]}
,sendList : 100% : 30721 ms, 99% : 30721 ms, 95 : 30721 ms, 90% : 30721 ms.
,Result count 2, range 6553 ms to  30721 ms.
,sendList failed peers count : 1 [33.333333333333336 %]
,- Peer ID : Apple-Iphone6-1_PT4714.SIFsmA==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-12-08T12:17:05.160Z SendDataConnector.js: CLIENT Stop now
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-08 13:17:22.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:17:22.305 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:17:22.307 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:17:22.307 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:17:52.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:17:52.304 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:17:52.304 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:17:52.304 ThaliTest[427:260097] client: fou,nd peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:18:22.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:18:22.302 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:18:22.302 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:18:22.303 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:18:52.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:18:52.304 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:18:52.307 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:18:52.308 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:19:22.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:19:22.303 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:19:22.304 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:19:22.304 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:19:52.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:19:52.307 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:19:52.307 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:19:52.308 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:20:22.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:20:22.303 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:20:22.303 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:20:22.303 ThaliTest[427:260097] client: fou,nd peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:20:52.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:20:52.305 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:20:52.305 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:20:52.307 ThaliTest[427:260097] client: found, peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:21:22.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:21:22.303 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:21:22.304 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:21:22.306 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-08 13:21:52.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:21:52.302 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:21:52.302 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:21:52.303 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:22:22.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:22:22.305 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:22:22.306 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:22:22.306 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:22:52.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:22:52.303 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:22:52.303 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:22:52.303 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:23:22.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:23:22.303 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:23:22.304 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:23:22.304 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:23:52.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:23:52.305 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:23:52.305 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:23:52.305 ThaliTest[427:260097] client: fou,nd peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:24:22.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:24:23.082 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:24:23.082 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:24:23.085 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:24:52.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:24:52.308 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:24:52.308 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:24:52.309 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:25:22.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:25:22.305 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:25:22.306 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:25:22.307 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:25:52.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:25:52.306 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:25:52.306 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:25:52.307 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:26:22.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:26:22.303 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:26:22.303 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:26:22.303 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:26:52.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:26:52.302 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:26:52.302 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:26:52.303 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-08 13:27:22.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:27:22.302 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:27:22.303 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:27:22.303 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:27:52.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:27:52.302 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:27:52.303 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:27:52.370 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:28:22.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:28:22.302 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:28:22.303 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:28:22.305 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:28:52.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:28:52.302 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:28:52.831 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:28:52.832 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:29:22.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:29:22.302 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:29:22.303 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:29:22.303 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:29:52.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:29:52.304 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:29:52.304 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:29:52.304 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:30:22.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:30:22.303 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:30:22.304 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:30:22.305 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:30:52.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:30:52.302 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:30:52.303 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:30:52.303 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:31:22.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:31:22.304 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:31:22.304 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:31:22.305 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:31:52.276 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:31:52.303 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:31:52.304 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:31:52.304 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:32:22.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:32:52.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:32:52.302 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:32:52.302 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:32:52.303 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:33:22.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:33:22.301 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:33:22.302 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:33:22.302 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:33:52.277 ThaliTest[427:260097] multipeer session: restart
,2015-12-08 13:33:52.300 ThaliTest[427:260097] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:33:52.301 ThaliTest[427:260097] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:33:52.301 ThaliTest[427:260097] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==

```
