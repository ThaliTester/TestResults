#### Test 52971095c7b67a5_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52971095c7b67a5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/41EF02BA-AF65-4B4E-86DF-42D494A459AB/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/41EF02BA-AF65-4B4E-86DF-42D494A459AB/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/52971095c7b67a5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52971095c7b67a5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3605BE6D-1382-4B05-8AA5-AF38BD77003D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50607"
,(lldb)     command script import "/tmp/41EF02BA-AF65-4B4E-86DF-42D494A459AB/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-08 13:05:06.259 ThaliTest[402:314551] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A9BB984A-394D-4EE6-B6D9-E94BC3C5D3A1/Library/Cookies/Cookies.binarycookies
,2015-12-08 13:05:06.769 ThaliTest[402:314551] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-08 13:05:06.771 ThaliTest[402:314551] Multi-tasking -> Device: YES, App: YES
,2015-12-08 13:05:06.778 ThaliTest[402:314551] Unlimited access to network resources
,2015-12-08 13:05:06.788 ThaliTest[402:314551] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-08 13:05:17.572 ThaliTest[402:314551] Resetting plugins due to page load.
,2015-12-08 13:05:21.210 ThaliTest[402:314551] Finished load of: file:///var/mobile/Containers/Bundle/Application/3605BE6D-1382-4B05-8AA5-AF38BD77003D/ThaliTest.app/www/index.html
,2015-12-08 13:05:21.422 ThaliTest[402:314551] JXcore Cordova plugin initializing
,2015-12-08 13:05:21.423 ThaliTest[402:314740] JXcore instance initializing
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
,my name is : Apple-Iphone5-1_PT785
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
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 51815
,2015-12-08 13:12:59.886 ThaliTest[402:314740] jxcore: startBroadcasting
,2015-12-08 13:12:59.897 ThaliTest[402:314740] server: starting Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:12:59.898 ThaliTest[402:314740] multipeer session: start timer: 0x1c71c200
2015-12-08 13:12:59.899 ThaliTest[402:314740] THEMultipeerSession initialized peer Apple-Iphone5-1_PT785
,2015-12-08 13:12:59.899 ThaliTest[402:314740] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-08T12:12:59.902Z SendDataTCPServer.js: TCP/IP server is bound to port: 51815
,2015-12-08 13:13:01.138 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT3979.Fg9L1g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08T12:13:01.143Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08T12:13:01.144Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT3979.Fg9L1g==
,2015-12-08T12:13:01.144Z SendDataConnector.js: do connect now
,2015-12-08 13:13:01.145 ThaliTest[402:314740] jxcore: connect Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:13:01.146 ThaliTest[402:314740] client session: connect
2015-12-08 13:13:01.146 ThaliTest[402:314740] client session: stateChange:0->1 Apple-IpadAir2-1_PT3979.Fg9L1g==
,2015-12-08 13:13:04.688 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8639.zsASLQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-08 13:13:06.242 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4714.SIFsmA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
,2015-12-08 13:13:06.616 ThaliTest[402:315522] client session: connected
2015-12-08 13:13:06.616 ThaliTest[402:315522] client session: stateChange:1->2 Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:13:06.621 ThaliTest[402:315522] client session: fireConn,ectCallback: Apple-IpadAir2-1_PT3979.Fg9L1g==
,2015-12-08 13:13:06.621 ThaliTest[402:315522] jxcore: connect: success
,2015-12-08T12:13:06.623Z SendDataConnector.js: CLIENT connected to 51818, error: null
2015-12-08T12:13:06.623Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 13:13:06.625 ThaliTest[402:314551] client: relay established
2015-12-08 13:13:06.626 ThaliTest[402:314551] client: new accepted socket: 0x1c58eb00
,2015-12-08T12:13:06.641Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08 13:13:06.661 ThaliTest[402:314551] multipeer session: reset timer
,2015-12-08 13:13:06.662 ThaliTest[402:314551] multipeer session: stop timer
2015-12-08 13:13:06.662 ThaliTest[402:314551] multipeer session: start timer: 0x1c71c200
2015-12-08 13:13:06.663 ThaliTest[402:314551] server session: connect
,2015-12-08 13:13:06.663 ThaliTest[402:314551] server session: stateChange:0->1 Apple-IpadAir2-1_PT3979
,2015-12-08 13:13:06.673 ThaliTest[402:314551] server: accepting invitation Apple-IpadAir2-1_PT3979
,2015-12-08 13:13:06.817 ThaliTest[402:314551] multipeer session: reset timer
,2015-12-08 13:13:06.817 ThaliTest[402:314551] multipeer session: stop timer
2015-12-08 13:13:06.817 ThaliTest[402:314551] multipeer session: start timer: 0x1c71c200
,2015-12-08 13:13:06.818 ThaliTest[402:314551] server session: connect
,2015-12-08 13:13:06.818 ThaliTest[402:314551] server session: stateChange:0->1 Apple-Iphone5s-1_PT8639
,2015-12-08 13:13:06.832 ThaliTest[402:314551] server: accepting invitation Apple-Iphone5s-1_PT8639
,2015-12-08T12:13:07.341Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-08T12:13:07.363Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-08T12:13:07.378Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-08T12:13:07.379Z SendDataConnector.js: got all data for this round
,2015-12-08T12:13:07.382Z SendDataConnector.js: CLIENT Stop now
,2015-12-08T12:13:07.384Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 13:13:07.385 ThaliTest[402:314740] jxcore: disconnect
,2015-12-08 13:13:07.388 ThaliTest[402:314740] client session: disconnectFromPeer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,2015-12-08 13:13:07.390 ThaliTest[402:314740] client session: disconnect
,2015-12-08 13:13:07.391 ThaliTest[402:314740] client session: stateChange:2->0 Apple-IpadAir2-1_PT3979.Fg9L1g==
,2015-12-08 13:13:07.515 ThaliTest[402:314740] jxcore: disconnect: success
2015-12-08T12:13:07.525Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT3979.Fg9L1g==
---- round done--------
device[2]: Apple-Iphone5s-1_PT8639.z,sASLQ==
2015-12-08T12:13:07.527Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08T12:13:07.527Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08T12:13:07.527Z SendDataCo,nnector.js: do connect now
2015-12-08 13:13:07.528 ThaliTest[402:314740] jxcore: connect Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:13:07.528 ThaliTest[402:314740] client session: connect
2015-12-08 13:13:07.528 ThaliTest[402:314740] client session: stateChange:0->1 Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:13:10.534 ThaliTest[402:315525] server session: connected
2015-12-08 13:13:10.534 ThaliTest[402:315525] server session: stateChange:1->2 Apple-Iphone5s-1_PT8639
,2015-12-08 13:13:10.920 ThaliTest[402:314551] server relay: connected (to port: 51815)
,2015-12-08T12:13:10.924Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08T12:13:11.318Z SendDataTCPServer.js: TCP/IP server has received 21474 bytes of data
,2015-12-08T12:13:11.333Z SendDataTCPServer.js: TCP/IP server has received 48038 bytes of data
,2015-12-08T12:13:11.348Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-08T12:13:11.450Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-08T12:13:11.513Z SendDataTCPServer.js: TCP/IP server has received 78698 bytes of data
,2015-12-08T12:13:11.527Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 13:13:11.921 ThaliTest[402:315554] server session: not connected Apple-Iphone5s-1_PT8639
,2015-12-08 13:13:12.363 ThaliTest[402:314551] multipeer session: reset timer
2015-12-08 13:13:12.363 ThaliTest[402:314551] multipeer session: stop timer
2015-12-08 13:13:12.364 ThaliTest[402:314551] multipeer session: start timer: 0x1c71c200
2015-12-08 13:13:12.364 ThaliTest[402:314551] server session: connect
2015-12-08 13:13:12.364 ThaliTest[402:314551] server session: stateChange:0->1 Apple-Iphone6-1_PT4714
,2015-12-08 13:13:12.370 ThaliTest[402:314551] server: accepting invitation Apple-Iphone6-1_PT4714
,2015-12-08 13:13:13.008 ThaliTest[402:315554] client session: connected
2015-12-08 13:13:13.008 ThaliTest[402:315554] client session: stateChange:1->2 Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:13:13.080 ThaliTest[402:315529] client session: fireConnectCallback: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:13:13.080 ThaliTest[402:315529] jxcore: connect: success
2015-12-08T12:13:13.081Z SendDataConnector.js: CLIENT connected to 51822, error: null
2015-12-08T12:13:13.081Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 13:13:13.084 ThaliTest[402:314551] client: relay established
2015-12-08 13:13:13.084 ThaliTest[402:314551] client: new accepted socket: 0x1c5a38c0
,2015-12-08T12:13:13.097Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T12:13:13.936Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-08T12:13:14.125Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-08T12:13:14.140Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-08T12:13:14.140Z SendDataConnector.js: got all data for this round
,2015-12-08T12:13:14.142Z SendDataConnector.js: CLIENT Stop now
2015-12-08T12:13:14.142Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 13:13:14.143 ThaliTest[402:314740] jxcore: disconnect
2015-12-08 13:13:14.143 ThaliTest[402:314740] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:13:14.143 ThaliTest[402:314740] client session: disconnect
2015-12-08 13:13:14.144 ThaliTest[402:314740] client session: stateChange:2->0 Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:13:14.154 ThaliTest[402:314740] jxcore: disconnect: success
2015-12-08T12:13:14.155Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8639.zsASLQ==
---- round done--------
device[3]: Apple-Iphone6-1_PT4714.SI,FsmA==
2015-12-08T12:13:14.158Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08T12:13:14.158Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08T12:13:14.158Z SendDataConne,ctor.js: do connect now
2015-12-08 13:13:14.159 ThaliTest[402:314740] jxcore: connect Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:13:14.160 ThaliTest[402:314740] client session: connect
2015-12-08 13:13:14.165 ThaliTest[402:314740] client session: stateChange:0->1 Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:13:16.825 ThaliTest[402:315554] server session: connected
2015-12-08 13:13:16.825 ThaliTest[402:315554] server session: stateChange:1->2 Apple-Iphone6-1_PT4714
,2015-12-08 13:13:17.609 ThaliTest[402:314551] server relay: connected (to port: 51815)
,2015-12-08T12:13:17.615Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08T12:13:17.666Z SendDataTCPServer.js: TCP/IP server has received 6428 bytes of data
,2015-12-08T12:13:17.679Z SendDataTCPServer.js: TCP/IP server has received 30376 bytes of data
,2015-12-08T12:13:17.696Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-08T12:13:17.736Z SendDataTCPServer.js: TCP/IP server has received 61178 bytes of data
,2015-12-08T12:13:17.752Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 13:13:17.772 ThaliTest[402:315554] server session: not connected Apple-IpadAir2-1_PT3979
,2015-12-08 13:13:18.186 ThaliTest[402:315527] server session: not connected Apple-Iphone6-1_PT4714
,2015-12-08 13:13:18.396 ThaliTest[402:315554] client session: connected
2015-12-08 13:13:18.396 ThaliTest[402:315554] client session: stateChange:1->2 Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:13:18.437 ThaliTest[402:315522] client session: fireConnectCallback: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:13:18.437 ThaliTest[402:315522] jxcore: connect: success
2015-12-08T12:13:18.438Z SendDataConnector.js: CLIENT connected to 51826, error: null
2015-12-08T12:13:18.438Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 13:13:18.441 ThaliTest[402:314551] client: relay established
2015-12-08 13:13:18.441 ThaliTest[402:314551] client: new accepted socket: 0x1c71eb10
,2015-12-08T12:13:18.454Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T12:13:19.244Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-08T12:13:19.271Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-08T12:13:19.285Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-08T12:13:19.286Z SendDataConnector.js: got all data for this round
,2015-12-08T12:13:19.288Z SendDataConnector.js: CLIENT Stop now
2015-12-08T12:13:19.288Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 13:13:19.289 ThaliTest[402:314740] jxcore: disconnect
2015-12-08 13:13:19.289 ThaliTest[402:314740] client session: disconnectFromPeer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:13:19.289 ThaliTest[402:314740] client session: disconnect
2015-12-08 13:13:19.290 ThaliTest[402:314740] client session: stateChange:2->0 Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:13:19.300 ThaliTest[402:314740] jxcore: disconnect: success
2015-12-08T12:13:19.300Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4714.SIFsmA==
---- round done--------
weAreDoneNow , resultArray.length: 3,
done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-Iphone5-1_PT785","time":19425,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT3979.Fg9L1g==","time":6236,"result":"OK","connections":1,"doneR,ounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT8639.zsASLQ==","time":6614,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT4714.SIFsmA==","time":5128,"result,":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 6614 ms, 99% : 6614 ms, 95 : 6614 ms, 90% : 6614 ms.
Result count 3, range 5128 ms to  6614 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-12-08T12:13:19.309Z SendDataConnector.js: CLIENT Sto,p now
2015-12-08T12:13:19.309Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 13:13:28.708 ThaliTest[402:314551] multipeer session: reset timer
,2015-12-08 13:13:28.708 ThaliTest[402:314551] multipeer session: stop timer
2015-12-08 13:13:28.708 ThaliTest[402:314551] multipeer session: start timer: 0x1c71c200
2015-12-08 13:13:28.708 ThaliTest[402:314551] server: disconnecting to refresh session (Apple-IpadAir2-1_PT3979)
2015-12-08 13:13:28.708 ThaliTest[402:314551] server session: disconnect
,2015-12-08 13:13:28.709 ThaliTest[402:314551] server session: stateChange:1->0 Apple-IpadAir2-1_PT3979
,2015-12-08 13:13:28.773 ThaliTest[402:314551] server session: connect
,2015-12-08 13:13:28.774 ThaliTest[402:314551] server session: stateChange:0->1 Apple-IpadAir2-1_PT3979
,2015-12-08 13:13:28.783 ThaliTest[402:314551] server: accepting invitation Apple-IpadAir2-1_PT3979
,2015-12-08 13:13:36.484 ThaliTest[402:315522] server session: connected
,2015-12-08 13:13:36.485 ThaliTest[402:315522] server session: stateChange:1->2 Apple-IpadAir2-1_PT3979
,2015-12-08 13:13:36.502 ThaliTest[402:314551] server relay: connected (to port: 51815)
,2015-12-08T12:13:36.511Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08T12:13:37.083Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-08T12:13:37.110Z SendDataTCPServer.js: TCP/IP server has received 29950 bytes of data
,2015-12-08T12:13:37.125Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 13:13:37.177 ThaliTest[402:315525] server session: not connected Apple-IpadAir2-1_PT3979
,2015-12-08 13:13:58.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:13:58.746 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,2015-12-08 13:13:58.756 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:13:58.757 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:14:28.709 ThaliTest[402:314551] multipeer session: restart
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:14:58.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:14:58.742 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:14:58.742 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,2015-12-08 13:14:58.748 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 13:15:28.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:15:28.745 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:15:28.745 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:15:28.745 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:15:58.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:15:58.745 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:15:58.746 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:16:20.367 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:16:28.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:16:28.742 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:16:28.745 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:16:35.722 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:16:58.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:16:58.743 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:16:58.744 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:16:58.749 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:17:28.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:17:28.741 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:17:28.742 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,2015-12-08 13:17:29.086 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:17:58.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:17:58.745 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:17:58.746 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:17:58.748 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 13:18:28.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:18:28.746 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:18:28.746 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:18:29.135 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:18:58.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:18:58.746 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:18:58.746 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:18:58.747 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:19:28.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:19:28.746 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:19:28.746 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:19:28.748 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:19:58.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:19:58.746 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:19:58.747 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:19:58.749 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:20:28.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:20:28.742 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:20:28.743 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:20:28.744 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:20:58.709 ThaliTest[402:314551] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
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
,2015-12-08 13:21:28.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:21:28.745 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:21:28.746 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:21:28.747 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 13:21:58.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:21:58.743 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:21:58.743 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:21:58.744 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
Error type "connect_error" when connecting to the test server
,2015-12-08 13:22:28.709 ThaliTest[402:314551] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:22:58.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:22:58.742 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:22:58.742 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:22:58.742 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 13:23:28.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:23:28.741 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:23:28.742 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:23:29.130 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 13:23:58.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:23:58.743 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:23:58.743 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:23:58.744 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:24:28.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:24:28.744 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:24:28.744 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:24:28.747 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:24:58.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:24:58.741 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:24:58.741 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:24:58.745 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:25:28.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:25:28.745 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:25:28.745 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:25:28.746 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:25:58.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:25:58.744 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:25:58.744 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:25:58.750 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
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
,2015-12-08 13:26:28.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:26:28.743 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:26:28.743 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:26:28.747 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 13:26:58.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:26:58.740 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:26:58.742 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:26:58.742 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:27:28.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:27:28.744 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:27:28.747 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:27:28.748 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:27:58.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:27:58.740 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:27:58.740 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:27:58.743 ThaliTest[402:314551] client: fou,nd peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:28:28.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:28:28.743 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:28:28.746 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:28:28.747 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:28:58.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:28:58.743 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:28:58.743 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:28:58.745 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:29:28.709 ThaliTest[402:314551] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 13:29:58.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:29:58.739 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:29:58.740 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:29:58.741 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
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
,2015-12-08 13:30:28.709 ThaliTest[402:314551] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:30:29.232 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:30:29.232 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:30:29.234 ThaliTest[402:314551] client: fou,nd peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 13:30:58.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:30:58.743 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:30:58.743 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:30:58.743 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:31:28.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:31:28.739 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:31:28.740 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:31:28.740 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:31:58.709 ThaliTest[402:314551] multipeer session: restart
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
,2015-12-08 13:32:28.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:32:28.741 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:32:28.741 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:32:28.743 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:32:58.709 ThaliTest[402:314551] multipeer session: restart
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
,2015-12-08 13:33:28.709 ThaliTest[402:314551] multipeer session: restart
,2015-12-08 13:33:28.739 ThaliTest[402:314551] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:33:28.740 ThaliTest[402:314551] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:33:28.741 ThaliTest[402:314551] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment

```
