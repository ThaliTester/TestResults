#### Test 51790364c93db41_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51790364c93db41/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/760C460E-8FD5-4F80-AD9F-04EAD6A84D23/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/760C460E-8FD5-4F80-AD9F-04EAD6A84D23/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51790364c93db41/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51790364c93db41/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9B75FCCC-EB3F-41D3-A9AB-4E9EA619A6C1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55592"
,(lldb)     command script import "/tmp/760C460E-8FD5-4F80-AD9F-04EAD6A84D23/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-25 14:25:30.397 ThaliTest[1315:1736082] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/33154DE9-7952-4977-B925-59EFF3FB0729/Library/Cookies/Cookies.binarycookies
,2015-11-25 14:25:30.670 ThaliTest[1315:1736082] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-25 14:25:30.671 ThaliTest[1315:1736082] Multi-tasking -> Device: YES, App: YES
,2015-11-25 14:25:30.677 ThaliTest[1315:1736082] Unlimited access to network resources
,2015-11-25 14:25:30.683 ThaliTest[1315:1736082] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-25 14:25:34.867 ThaliTest[1315:1736082] Resetting plugins due to page load.
,2015-11-25 14:25:36.322 ThaliTest[1315:1736082] Finished load of: file:///var/mobile/Containers/Bundle/Application/9B75FCCC-EB3F-41D3-A9AB-4E9EA619A6C1/ThaliTest.app/www/index.html
,2015-11-25 14:25:36.466 ThaliTest[1315:1736082] JXcore Cordova plugin initializing
,2015-11-25 14:25:36.467 ThaliTest[1315:1736256] JXcore instance initializing
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
,my name is : Apple-IpadAir2-1_PT1710
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
,serverPort is 61741
,2015-11-25 14:32:35.896 ThaliTest[1315:1736256] jxcore: startBroadcasting
,2015-11-25 14:32:35.902 ThaliTest[1315:1736256] server: starting Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:32:35.903 ThaliTest[1315:1736256] multipeer session: start timer: 0x166ae9a0
2015-11-25 14:32:35.903 ThaliTest[1315:1736256] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT1710
,2015-11-25 14:32:35.904 ThaliTest[1315:1736256] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-11-25T13:32:35.906Z SendDataTCPServer.js: TCP/IP server is bound to port: 61741
,2015-11-25 14:32:36.071 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5s-1_PT8640.H39DFw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8640.H39DFw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT8640.H39DFw==
2015-11-25T13:32:36.073Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8640.H39DFw==
2015-11-25T13:32:36.073Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8640.H39DFw==
2015-11-25T13:32:36.073Z SendDataConnector.js: do connect now
2015-11-25 14:32:36.074 ThaliTest[1315:1736256] jxcore: connect Apple-Iphone5s-1_PT8640.H39DFw==
2015-11-25 14:32:36.074 ThaliTest[1315:1736256] client session: connect
,2015-11-25 14:32:36.074 ThaliTest[1315:1736256] client session: stateChange:0->1 Apple-Iphone5s-1_PT8640.H39DFw==
,2015-11-25 14:32:36.121 ThaliTest[1315:1736082] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8475.0elZ3A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-25 14:32:37.187 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6254.8TiZaA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-11-25 14:32:39.203 ThaliTest[1315:1737686] client session: connected
2015-11-25 14:32:39.203 ThaliTest[1315:1737686] client session: stateChange:1->2 Apple-Iphone5s-1_PT8640.H39DFw==
,2015-11-25 14:32:39.218 ThaliTest[1315:1737686] client session: fireConnectCallback: Apple-Iphone5s-1_PT8640.H39DFw==
2015-11-25 14:32:39.219 ThaliTest[1315:1737686] jxcore: connect: success
2015-11-25T13:32:39.219Z SendDataConnector.js: CLIENT connected to 61744, error: null
,2015-11-25T13:32:39.220Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 14:32:39.221 ThaliTest[1315:1736082] client: relay established
2015-11-25 14:32:39.221 ThaliTest[1315:1736082] client: new accepted socket: 0x178423c0
,2015-11-25T13:32:39.233Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T13:32:39.662Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-25T13:32:39.699Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-25T13:32:39.712Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-25T13:32:39.771Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-25T13:32:39.783Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-25T13:32:39.783Z SendDataConnector.js: got all data for this round
,2015-11-25T13:32:39.784Z SendDataConnector.js: CLIENT Stop now
2015-11-25T13:32:39.784Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 14:32:39.785 ThaliTest[1315:1736256] jxcore: disconnect
2015-11-25 14:32:39.785 ThaliTest[1315:1736256] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8640.H39DFw==
2015-11-25 14:32:39.785 ThaliTest[1315:1736256] client session: disconnect
2015-11-25 14:32:39.785 ThaliTest[1315:1736256] client session: stateChange:2->0 Apple-Iphone5s-1_PT8640.H39DFw==
,2015-11-25 14:32:39.789 ThaliTest[1315:1736256] jxcore: disconnect: success
2015-11-25T13:32:39.789Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8640.H39DFw==
---- round done--------
device[2]: Apple-Iphone6-1_PT8475.0elZ3A==
2015-11-25T13:32:39.790Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8475.0elZ3A==
2015-11-25T13:32:39.790Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8475.0elZ3A==
2015-11-25T13:32:39.790Z SendDataCon,nector.js: do connect now
,2015-11-25 14:32:39.790 ThaliTest[1315:1736256] jxcore: connect Apple-Iphone6-1_PT8475.0elZ3A==
2015-11-25 14:32:39.793 ThaliTest[1315:1736256] client session: connect
2015-11-25 14:32:39.793 ThaliTest[1315:1736256] client session: stateChange:0->1 Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:32:42.360 ThaliTest[1315:1736082] multipeer session: reset timer
2015-11-25 14:32:42.361 ThaliTest[1315:1736082] multipeer session: stop timer
2015-11-25 14:32:42.361 ThaliTest[1315:1736082] multipeer session: start timer: 0x166ae9a0
2015-11-25 14:32:42.361 ThaliTest[1315:1736082] server session: connect
2015-11-25 14:32:42.361 ThaliTest[1315:1736082] server session: stateChange:0->1 Apple-Iphone6-1_PT8475
,2015-11-25 14:32:42.363 ThaliTest[1315:1736082] server: accepting invitation Apple-Iphone6-1_PT8475
,2015-11-25 14:32:42.967 ThaliTest[1315:1737687] client session: connected
2015-11-25 14:32:42.967 ThaliTest[1315:1737687] client session: stateChange:1->2 Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:32:42.970 ThaliTest[1315:1737687] client session: fireConnectCallback: Apple-Iphone6-1_PT8475.0elZ3A==
2015-11-25 14:32:42.970 ThaliTest[1315:1737687] jxcore: connect: success
2015-11-25T13:32:42.971Z SendDataConnector.js: CLIENT connected to 61748, error: null
2015-11-25T13:32:42.971Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 14:32:42.972 ThaliTest[1315:1736082] client: relay established
2015-11-25 14:32:42.972 ThaliTest[1315:1736082] client: new accepted socket: 0x179812c0
,2015-11-25T13:32:42.985Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T13:32:43.381Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-25T13:32:43.403Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-25T13:32:43.403Z SendDataConnector.js: got all data for this round
,2015-11-25T13:32:43.404Z SendDataConnector.js: CLIENT Stop now
,2015-11-25T13:32:43.404Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 14:32:43.405 ThaliTest[1315:1736256] jxcore: disconnect
2015-11-25 14:32:43.405 ThaliTest[1315:1736256] client session: disconnectFromPeer: Apple-Iphone6-1_PT8475.0elZ3A==
2015-11-25 14:32:43.405 ThaliTest[1315:1736256] client session: disconnect
2015-11-25 14:32:43.405 ThaliTest[1315:1736256] client session: stateChange:2->0 Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:32:43.410 ThaliTest[1315:1736256] jxcore: disconnect: success
2015-11-25T13:32:43.411Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8475.0elZ3A==
---- round done--------
device[3]: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25T13:32:43.412Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25T13:32:43.412Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25T13:32:43.413Z SendDataConnector.js: do connect now
,2015-11-25 14:32:43.413 ThaliTest[1315:1736256] jxcore: connect Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25 14:32:43.413 ThaliTest[1315:1736256] client session: connect
2015-11-25 14:32:43.413 ThaliTest[1315:1736256] client session: stateChange:0->1 Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:32:44.965 ThaliTest[1315:1737682] server session: connected
,2015-11-25 14:32:44.965 ThaliTest[1315:1737682] server session: stateChange:1->2 Apple-Iphone6-1_PT8475
,2015-11-25 14:32:44.969 ThaliTest[1315:1736082] server relay: connected (to port: 61741)
,2015-11-25T13:32:44.980Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T13:32:45.064Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-11-25T13:32:45.078Z SendDataTCPServer.js: TCP/IP server has received 69938 bytes of data
,2015-11-25T13:32:45.094Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 14:32:45.310 ThaliTest[1315:1737682] server session: not connected Apple-Iphone6-1_PT8475
,2015-11-25 14:32:48.519 ThaliTest[1315:1736082] multipeer session: reset timer
2015-11-25 14:32:48.519 ThaliTest[1315:1736082] multipeer session: stop timer
2015-11-25 14:32:48.519 ThaliTest[1315:1736082] multipeer session: start timer: 0x166ae9a0
,2015-11-25 14:32:48.519 ThaliTest[1315:1736082] server session: connect
2015-11-25 14:32:48.519 ThaliTest[1315:1736082] server session: stateChange:0->1 Apple-Iphone5-1_PT6254
,2015-11-25 14:32:48.522 ThaliTest[1315:1736082] server: accepting invitation Apple-Iphone5-1_PT6254
,2015-11-25 14:32:51.120 ThaliTest[1315:1737706] server session: connected
2015-11-25 14:32:51.120 ThaliTest[1315:1737706] server session: stateChange:1->2 Apple-Iphone5-1_PT6254
,2015-11-25 14:32:51.123 ThaliTest[1315:1736082] server relay: connected (to port: 61741)
,2015-11-25T13:32:51.129Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25 14:32:51.204 ThaliTest[1315:1737687] client session: connected
2015-11-25 14:32:51.204 ThaliTest[1315:1737687] client session: stateChange:1->2 Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:32:51.205 ThaliTest[1315:1737686] client session: fireConnectCallback: Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25 14:32:51.206 ThaliTest[1315:1737686] jxcore: connect: success
2015-11-25T13:32:51.207Z SendDataConnector.js: CLIENT connected to 61753, error: null
2015-11-25T13:32:51.207Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 14:32:51.208 ThaliTest[1315:1736082] client: relay established
2015-11-25 14:32:51.208 ThaliTest[1315:1736082] client: new accepted socket: 0x17986f40
,2015-11-25T13:32:51.221Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T13:32:51.797Z SendDataTCPServer.js: TCP/IP server has received 10912 bytes of data
,2015-11-25T13:32:51.811Z SendDataTCPServer.js: TCP/IP server has received 14880 bytes of data
,2015-11-25T13:32:51.823Z SendDataTCPServer.js: TCP/IP server has received 15872 bytes of data
,2015-11-25T13:32:52.126Z SendDataTCPServer.js: TCP/IP server has received 25792 bytes of data
,2015-11-25T13:32:52.139Z SendDataTCPServer.js: TCP/IP server has received 34720 bytes of data
,2015-11-25T13:32:52.152Z SendDataTCPServer.js: TCP/IP server has received 35712 bytes of data
,2015-11-25T13:32:52.201Z SendDataTCPServer.js: TCP/IP server has received 46624 bytes of data
,2015-11-25T13:32:52.214Z SendDataTCPServer.js: TCP/IP server has received 47616 bytes of data
,2015-11-25T13:32:52.263Z SendDataTCPServer.js: TCP/IP server has received 62496 bytes of data
,2015-11-25T13:32:52.264Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-25T13:32:52.290Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T13:32:52.290Z SendDataConnector.js: got all data for this round
,2015-11-25T13:32:52.291Z SendDataConnector.js: CLIENT Stop now
,2015-11-25T13:32:52.291Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 14:32:52.292 ThaliTest[1315:1736256] jxcore: disconnect
2015-11-25 14:32:52.292 ThaliTest[1315:1736256] client session: disconnectFromPeer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:32:52.292 ThaliTest[1315:1736256] client session: disconnect
2015-11-25 14:32:52.292 ThaliTest[1315:1736256] client session: stateChange:2->0 Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:32:52.296 ThaliTest[1315:1736256] jxcore: disconnect: success
2015-11-25T13:32:52.296Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6254.8TiZaA==
---- round done--------
weAreDoneNow , resultArray.length: ,3
done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT1710","time":16405,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT8640.H39DFw==","time":3710,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1,_PT8475.0elZ3A==","time":3613,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT6254.8TiZaA==","time":8878,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 8878 ms, 99% : 8878 ms, 95 : 8878 ms, 90% : 8878 ms.
Result count 3, range 3613 ms to  8878 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-11-25T13:32:52.303Z SendDataConnector.js: CLIENT Stop now
2015-11-25T13:32:52.303Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25T13:32:52.723Z SendDataTCPServer.js: TCP/IP server has received 78368 bytes of data
,2015-11-25T13:32:52.799Z SendDataTCPServer.js: TCP/IP server has received 81344 bytes of data
,2015-11-25T13:32:52.812Z SendDataTCPServer.js: TCP/IP server has received 82336 bytes of data
,2015-11-25T13:32:52.837Z SendDataTCPServer.js: TCP/IP server has received 99200 bytes of data
,2015-11-25T13:32:52.850Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 14:32:52.877 ThaliTest[1315:1737682] server session: not connected Apple-Iphone5-1_PT6254
,2015-11-25 14:33:18.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:33:18.531 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:33:19.452 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5s-1_PT8640.H39DFw==
,2015-11-25 14:33:19.560 ThaliTest[1315:1736082] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:33:48.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:33:48.531 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:33:48.531 ThaliTest[1315:1736082] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
2015-11-25 14:33:48.532 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5s-1_PT8640.H39DFw==
,2015-11-25 14:34:18.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:34:18.533 ThaliTest[1315:1736082] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
2015-11-25 14:34:18.533 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5s-1_PT8640.H39DFw==
,2015-11-25 14:34:19.343 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:34:43.402 ThaliTest[1315:1736082] client: lost peer: Apple-Iphone5s-1_PT8640.H39DFw==
2015-11-25 14:34:43.402 ThaliTest[1315:1736082] client session: onPeerLost: Apple-Iphone5s-1_PT8640.H39DFw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8640.H39DFw==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 14:34:48.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:34:48.529 ThaliTest[1315:1736082] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:34:48.531 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:35:18.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:35:19.118 ThaliTest[1315:1736082] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
2015-11-25 14:35:19.118 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:35:48.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:35:48.530 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25 14:35:48.530 ThaliTest[1315:1736082] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:36:15.695 ThaliTest[1315:1736082] client: lost peer: Apple-Iphone6-1_PT8475.0elZ3A==
2015-11-25 14:36:15.695 ThaliTest[1315:1736082] client session: onPeerLost: Apple-Iphone6-1_PT8475.0elZ3A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8475.0elZ3A==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 14:36:18.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:36:19.766 ThaliTest[1315:1736082] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8475.0elZ3A==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 14:36:24.025 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:36:48.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:36:48.530 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:36:49.137 ThaliTest[1315:1736082] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:37:18.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:37:18.531 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:37:18.535 ThaliTest[1315:1736082] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:37:43.729 ThaliTest[1315:1736082] client: lost peer: Apple-Iphone6-1_PT8475.0elZ3A==
2015-11-25 14:37:43.729 ThaliTest[1315:1736082] client session: onPeerLost: Apple-Iphone6-1_PT8475.0elZ3A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8475.0elZ3A==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 14:37:48.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:37:48.949 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:37:49.050 ThaliTest[1315:1736082] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8475.0elZ3A==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 14:38:18.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:38:48.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:38:48.528 ThaliTest[1315:1736082] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
2015-11-25 14:38:48.528 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:39:18.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:39:18.528 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:39:19.122 ThaliTest[1315:1736082] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:39:48.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:39:48.528 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:40:18.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:40:18.528 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:40:48.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:40:49.260 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:41:18.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:41:18.528 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:41:48.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:41:50.058 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:42:18.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:42:18.528 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:42:48.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:42:48.530 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:43:18.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:43:19.168 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:43:48.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:43:48.528 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:44:18.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:44:18.923 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:44:48.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:44:48.527 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:45:18.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:45:18.527 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:45:48.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:45:49.108 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:46:18.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:46:18.529 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:46:48.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:46:48.837 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:47:18.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:47:18.528 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:47:48.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:47:48.527 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:48:18.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:48:18.996 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:48:48.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:48:48.528 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:49:18.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:49:18.528 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:49:48.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:49:49.154 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:50:18.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:50:18.528 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:50:48.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:51:18.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:51:19.370 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:51:48.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:51:48.528 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:52:18.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:52:19.086 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:52:48.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:52:48.527 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:53:18.520 ThaliTest[1315:1736082] multipeer session: restart
,2015-11-25 14:53:18.528 ThaliTest[1315:1736082] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==

```
