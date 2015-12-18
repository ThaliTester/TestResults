#### Test 539786633aa3ea0_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/539786633aa3ea0/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/9720A959-2741-4CD7-9393-A538D9DDC704/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/9720A959-2741-4CD7-9393-A538D9DDC704/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/539786633aa3ea0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/539786633aa3ea0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/45666A04-8880-4C42-A81A-CE6A83B29D26/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60061"
,(lldb)     command script import "/tmp/9720A959-2741-4CD7-9393-A538D9DDC704/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-18 14:26:32.987 ThaliTest[436:359472] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/08BDC7B1-7A91-46AB-A673-0BD10509372A/Library/Cookies/Cookies.binarycookies
,2015-12-18 14:26:33.410 ThaliTest[436:359472] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-18 14:26:33.411 ThaliTest[436:359472] Multi-tasking -> Device: YES, App: YES
,2015-12-18 14:26:33.419 ThaliTest[436:359472] Unlimited access to network resources
,2015-12-18 14:26:33.428 ThaliTest[436:359472] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-18 14:26:42.324 ThaliTest[436:359472] Resetting plugins due to page load.
,2015-12-18 14:26:45.939 ThaliTest[436:359472] Finished load of: file:///var/mobile/Containers/Bundle/Application/45666A04-8880-4C42-A81A-CE6A83B29D26/ThaliTest.app/www/index.html
,2015-12-18 14:26:46.098 ThaliTest[436:359472] JXcore Cordova plugin initializing
,2015-12-18 14:26:46.099 ThaliTest[436:359688] JXcore instance initializing
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
,my name is : Apple-IpadAir2-1_PT4577
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
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
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
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":20000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 52432
,2015-12-18 14:39:32.609 ThaliTest[436:359688] jxcore: startBroadcasting
,2015-12-18 14:39:32.625 ThaliTest[436:359688] server: starting Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:39:32.626 ThaliTest[436:359688] multipeer session: start timer: 0x19e0ca70
2015-12-18 14:39:32.627 ThaliTest[436:359688] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT4577
2015-12-18 14:39:32.627 ThaliTest[436:359688] jxcore: star,tBroadcasting: success
StartBroadcasting started ok
2015-12-18T13:39:32.630Z SendDataTCPServer.js: TCP/IP server is bound to port: 52432
,2015-12-18 14:39:33.804 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5907.ktOSYA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 14:39:33.811 ThaliTest[436:359472] multipeer session: reset timer
2015-12-18 14:39:33.811 ThaliTest[436:359472] multipeer session: stop timer
device[1]: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:39:33.811 ThaliTest[436:359472] multipeer s,ession: start timer: 0x19e0ca70
2015-12-18 14:39:33.812 ThaliTest[436:359472] server session: connect
2015-12-18T13:39:33.812Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:39:33.812 ThaliTest[436:359472] ser,ver session: stateChange:0->1 Apple-Iphone6-1_PT5907
2015-12-18T13:39:33.813Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18T13:39:33.813Z SendDataConnector.js: do connect now
2015-12-18 14:39:33.814 ThaliTes,t[436:359688] jxcore: connect Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:39:33.815 ThaliTest[436:359688] client session: connect
2015-12-18 14:39:33.815 ThaliTest[436:359688] client session: stateChange:0->1 Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:39:33.820 ThaliTest[436:359472] server: accepting invitation Apple-Iphone6-1_PT5907
,2015-12-18 14:39:34.559 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6006.TYpyOQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-18 14:39:35.660 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4569.cwXFvg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 14:39:36.778 ThaliTest[436:361033] server session: connected
,2015-12-18 14:39:36.778 ThaliTest[436:361033] server session: stateChange:1->2 Apple-Iphone6-1_PT5907
,2015-12-18 14:39:36.787 ThaliTest[436:359472] server relay: connected (to port: 52432)
,2015-12-18T13:39:36.797Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18 14:39:36.832 ThaliTest[436:361028] client session: connected
2015-12-18 14:39:36.832 ThaliTest[436:361028] client session: stateChange:1->2 Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:39:36.836 ThaliTest[436:361028] client session: fireConnectCallback: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:39:36.836 ThaliTest[436:361028] jxcore: connect: success
,2015-12-18T13:39:36.838Z SendDataConnector.js: CLIENT connected to 52436, error: null
,2015-12-18T13:39:36.839Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 14:39:36.841 ThaliTest[436:359472] client: relay established
2015-12-18 14:39:36.842 ThaliTest[436:359472] client: new accepted socket: 0x19e087c0
,2015-12-18T13:39:36.858Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T13:39:37.160Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-18T13:39:37.173Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18T13:39:37.176Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-18T13:39:37.210Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-18T13:39:37.234Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T13:39:37.234Z SendDataConnector.js: got all data for this round
,2015-12-18T13:39:37.235Z SendDataConnector.js: CLIENT Stop now
2015-12-18T13:39:37.235Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 14:39:37.236 ThaliTest[436:359688] jxcore: disconnect
,2015-12-18 14:39:37.236 ThaliTest[436:359688] client session: disconnectFromPeer: Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:39:37.236 ThaliTest[436:359688] client session: disconnect
,2015-12-18 14:39:37.237 ThaliTest[436:359688] client session: stateChange:2->0 Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:39:37.242 ThaliTest[436:359688] jxcore: disconnect: success
,2015-12-18T13:39:37.244Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT5907.ktOSYA==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18T13:39:37.246Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18T13:39:37.246Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18T13:39:37.246Z SendDataConnector.js: do connect now
,2015-12-18 14:39:37.246 ThaliTest[436:359688] jxcore: connect Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:39:37.247 ThaliTest[436:359688] client session: connect
,2015-12-18 14:39:37.247 ThaliTest[436:359688] client session: stateChange:0->1 Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:39:37.260 ThaliTest[436:361033] server session: not connected Apple-Iphone6-1_PT5907
,2015-12-18 14:39:40.304 ThaliTest[436:359472] multipeer session: reset timer
2015-12-18 14:39:40.305 ThaliTest[436:359472] multipeer session: stop timer
2015-12-18 14:39:40.305 ThaliTest[436:359472] multipeer session: start timer: 0x19e0ca70
2015-12-18 ,14:39:40.306 ThaliTest[436:359472] server session: connect
2015-12-18 14:39:40.306 ThaliTest[436:359472] server session: stateChange:0->1 Apple-Iphone5s-1_PT4569
,2015-12-18 14:39:40.312 ThaliTest[436:359472] server: accepting invitation Apple-Iphone5s-1_PT4569
,2015-12-18 14:39:40.445 ThaliTest[436:361026] client session: connected
2015-12-18 14:39:40.445 ThaliTest[436:361026] client session: stateChange:1->2 Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:39:40.451 ThaliTest[436:361033] client session: fireConnectCallback: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:39:40.451 ThaliTest[436:361033] jxcore: connect: success
,2015-12-18T13:39:40.453Z SendDataConnector.js: CLIENT connected to 52439, error: null
,2015-12-18T13:39:40.453Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 14:39:40.455 ThaliTest[436:359472] client: relay established
2015-12-18 14:39:40.456 ThaliTest[436:359472] client: new accepted socket: 0x17d0ece0
,2015-12-18T13:39:40.469Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T13:39:40.859Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-18T13:39:40.872Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-18T13:39:40.911Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-18T13:39:40.923Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T13:39:40.923Z SendDataConnector.js: got all data for this round
,2015-12-18T13:39:40.924Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T13:39:40.924Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 14:39:40.925 ThaliTest[436:359688] jxcore: disconnect
,2015-12-18 14:39:40.925 ThaliTest[436:359688] client session: disconnectFromPeer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:39:40.926 ThaliTest[436:359688] client session: disconnect
,2015-12-18 14:39:40.926 ThaliTest[436:359688] client session: stateChange:2->0 Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:39:40.989 ThaliTest[436:359688] jxcore: disconnect: success
,2015-12-18T13:39:40.990Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6006.TYpyOQ==
,---- round done--------
,device[3]: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18T13:39:40.991Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18T13:39:40.992Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18T13:39:40.992Z SendDataConnector.js: do connect now
,2015-12-18 14:39:40.993 ThaliTest[436:359688] jxcore: connect Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:39:40.993 ThaliTest[436:359688] client session: connect
,2015-12-18 14:39:40.993 ThaliTest[436:359688] client session: stateChange:0->1 Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:39:43.174 ThaliTest[436:361077] server session: connected
2015-12-18 14:39:43.174 ThaliTest[436:361077] server session: stateChange:1->2 Apple-Iphone5s-1_PT4569
,2015-12-18 14:39:43.181 ThaliTest[436:359472] server relay: connected (to port: 52432)
,2015-12-18T13:39:43.188Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T13:39:43.510Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-18T13:39:43.524Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-18T13:39:43.543Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-18T13:39:43.561Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-18T13:39:43.574Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-18T13:39:43.591Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 14:39:43.975 ThaliTest[436:361028] server session: not connected Apple-Iphone5s-1_PT4569
,2015-12-18 14:39:44.085 ThaliTest[436:361028] client session: connected
2015-12-18 14:39:44.086 ThaliTest[436:361028] client session: stateChange:1->2 Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:39:44.090 ThaliTest[436:361028] client session: fireConnectCallback: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:39:44.090 ThaliTest[436:361028] jxcore: connect: success
,2015-12-18T13:39:44.092Z SendDataConnector.js: CLIENT connected to 52443, error: null
2015-12-18T13:39:44.092Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 14:39:44.095 ThaliTest[436:359472] client: relay established
2015-12-18 14:39:44.095 ThaliTest[436:359472] client: new accepted socket: 0x17fdfd90
,2015-12-18T13:39:44.110Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T13:39:44.581Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-18T13:39:44.594Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-18T13:39:44.631Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T13:39:44.631Z SendDataConnector.js: got all data for this round
,2015-12-18T13:39:44.632Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T13:39:44.632Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 14:39:44.632 ThaliTest[436:359688] jxcore: disconnect
,2015-12-18 14:39:44.632 ThaliTest[436:359688] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:39:44.633 ThaliTest[436:359688] client session: disconnect
2015-12-18 14:39:44.633 ThaliTest[436:359688] client session: stateChange:2->0 Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:39:44.637 ThaliTest[436:359688] jxcore: disconnect: success
,2015-12-18T13:39:44.637Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4569.cwXFvg==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT4577","time":12046,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT5907.ktOSYA==","time":3423,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_,PT6006.TYpyOQ==","time":3677,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT4569.cwXFvg==","time":3639,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 3677 ms, 99% : 3677 ms, 95 : 3677 ms, 90% : 3677 ms.
,Result count 3, range 3423 ms to  3677 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-18T13:39:44.643Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T13:39:44.644Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 14:39:56.305 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4751.qR8AbA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4751.qR8AbA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-18 14:40:10.307 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:40:10.346 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:40:10.346 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:40:10.346 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:40:28.372 ThaliTest[436:359472] client: lost peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:40:28.373 ThaliTest[436:359472] client session: onPeerLost: Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:40:28.373 ThaliTest[436:359472] client: lost peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:40:28.373 ThaliTest[436:359472] client session: onPeerLost: Apple-Iphone5-1_PT6006.TYpyOQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5907.ktOSYA==","peerName":"(null)","peerAvailable":false}]
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6006.TYpyOQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-18 14:40:40.307 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:40:40.333 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:40:40.333 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-,1_PT5907.ktOSYA==","peerName":"(null)","peerAvailable":true}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6006.TYpyOQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-18 14:40:40.340 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:40:45.829 ThaliTest[436:359472] client: lost peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:40:45.829 ThaliTest[436:359472] client session: onPeerLost: Apple-Iphone5-1_PT6006.TYpyOQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6006.TYpyOQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-18 14:40:58.341 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6006.TYpyOQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-18 14:41:01.850 ThaliTest[436:359472] client: lost peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:41:01.851 ThaliTest[436:359472] client session: onPeerLost: Apple-Iphone5s-1_PT4569.cwXFvg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4569.cwXFvg==","peerName":"(null)","peerAvailable":false}]
,2015-12-18 14:41:02.753 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4569.cwXFvg==","peerName":"(null)","peerAvailable":true}]
,2015-12-18 14:41:10.307 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:41:10.345 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:41:10.346 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:41:10.347 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:41:40.307 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:41:40.341 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:41:40.342 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:41:56.107 ThaliTest[436:359472] client: lost peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:41:56.108 ThaliTest[436:359472] client session: onPeerLost: Apple-Iphone6-1_PT5907.ktOSYA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5907.ktOSYA==","peerName":"(null)","peerAvailable":false}]
,2015-12-18 14:41:59.278 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5907.ktOSYA==","peerName":"(null)","peerAvailable":true}]
,2015-12-18 14:42:10.307 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:42:10.335 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:42:10.342 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,appEnteredForeground wasn't registered
,2015-12-18 14:42:40.307 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:42:40.340 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:42:40.786 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,appEnteringBackground wasn't registered
,2015-12-18 14:43:10.307 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:43:10.334 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:43:10.340 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:43:40.306 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:43:40.334 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:43:40.869 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:43:40.869 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:43:46.532 ThaliTest[436:359472] client: lost peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:43:46.532 ThaliTest[436:359472] client session: onPeerLost: Apple-Iphone5s-1_PT4569.cwXFvg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4569.cwXFvg==","peerName":"(null)","peerAvailable":false}]
,2015-12-18 14:43:55.365 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4569.cwXFvg==","peerName":"(null)","peerAvailable":true}]
,2015-12-18 14:44:10.307 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:44:10.348 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:44:10.813 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:44:10.814 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:44:33.180 ThaliTest[436:359472] client: lost peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:44:33.181 ThaliTest[436:359472] client session: onPeerLost: Apple-Iphone5s-1_PT4569.cwXFvg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4569.cwXFvg==","peerName":"(null)","peerAvailable":false}]
,2015-12-18 14:44:40.298 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4569.cwXFvg==","peerName":"(null)","peerAvailable":true}]
,2015-12-18 14:44:40.307 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:44:40.340 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:44:40.341 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:45:10.307 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:45:10.341 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:45:10.342 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:45:40.306 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:45:40.337 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:45:40.337 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:46:10.307 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:46:10.366 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:46:10.367 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:46:10.367 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:46:40.307 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:46:40.725 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:46:40.725 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:47:10.307 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:47:10.337 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:47:10.338 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:47:10.345 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:47:40.307 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:47:40.343 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:47:40.343 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:47:40.344 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:48:00.506 ThaliTest[436:359472] client: lost peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:48:00.506 ThaliTest[436:359472] client session: onPeerLost: Apple-Iphone6-1_PT5907.ktOSYA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5907.ktOSYA==","peerName":"(null)","peerAvailable":false}]
,2015-12-18 14:48:04.251 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5907.ktOSYA==","peerName":"(null)","peerAvailable":true}]
,2015-12-18 14:48:10.307 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:48:10.337 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:48:10.341 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:48:40.307 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:48:40.340 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:48:40.340 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:48:40.347 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:49:10.307 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:49:10.333 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:49:10.344 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:49:10.344 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:49:40.307 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:49:40.333 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:49:40.339 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:50:10.295 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:50:10.324 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:50:10.324 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:50:40.292 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:50:40.321 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:50:40.321 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:50:40.851 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:51:10.292 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:51:10.864 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:51:10.864 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:51:11.327 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:51:40.292 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:51:40.322 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:51:40.322 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:51:40.322 ThaliTest[436:359472] client: foun,d peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:52:10.292 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:52:10.321 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:52:10.322 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:52:10.440 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:52:40.292 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:52:40.468 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:52:40.468 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:52:40.468 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:53:10.292 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:53:10.323 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:53:10.324 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:53:10.324 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:53:40.292 ThaliTest[436:359472] multipeer session: restart
,2015-12-18 14:53:40.322 ThaliTest[436:359472] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:53:41.093 ThaliTest[436:359472] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:53:41.093 ThaliTest[436:359472] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==

```
