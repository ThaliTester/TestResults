#### Test 525354860130a71_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/525354860130a71/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/DA6CA989-AA34-4B59-AFFB-04CB30C3E0A2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/DA6CA989-AA34-4B59-AFFB-04CB30C3E0A2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/525354860130a71/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/525354860130a71/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D075FD4D-08EF-4117-880C-B37CE6CFBCF0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61401"
,(lldb)     command script import "/tmp/DA6CA989-AA34-4B59-AFFB-04CB30C3E0A2/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-04 09:42:25.535 ThaliTest[2018:3123457] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FE5B93A6-40EF-42BF-B7C6-BAFE80FFE79B/Library/Cookies/Cookies.binarycookies
,2015-12-04 09:42:25.815 ThaliTest[2018:3123457] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-04 09:42:25.816 ThaliTest[2018:3123457] Multi-tasking -> Device: YES, App: YES
,2015-12-04 09:42:25.822 ThaliTest[2018:3123457] Unlimited access to network resources
,2015-12-04 09:42:25.828 ThaliTest[2018:3123457] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-04 09:42:30.018 ThaliTest[2018:3123457] Resetting plugins due to page load.
,2015-12-04 09:42:31.306 ThaliTest[2018:3123457] Finished load of: file:///var/mobile/Containers/Bundle/Application/D075FD4D-08EF-4117-880C-B37CE6CFBCF0/ThaliTest.app/www/index.html
,2015-12-04 09:42:31.450 ThaliTest[2018:3123457] JXcore Cordova plugin initializing
,2015-12-04 09:42:31.450 ThaliTest[2018:3123639] JXcore instance initializing
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
,my name is : Apple-IpadAir2-1_PT6975
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
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 51875
,2015-12-04 09:49:52.775 ThaliTest[2018:3123639] jxcore: startBroadcasting
,2015-12-04 09:49:52.781 ThaliTest[2018:3123639] server: starting Apple-IpadAir2-1_PT6975.MZRWVw==
,2015-12-04 09:49:52.782 ThaliTest[2018:3123639] multipeer session: start timer: 0x1674ffa0
2015-12-04 09:49:52.782 ThaliTest[2018:3123639] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT6975
2015-12-04 09:49:52.782 ThaliTest[2018:3123639] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-04T08:49:52.783Z SendDataTCPServer.js: TCP/IP server is bound to port: 51875
,2015-12-04 09:49:53.545 ThaliTest[2018:3123457] client: found peer: Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04 09:49:53.545 ThaliTest[2018:3123457] client: found peer: Apple-Iphone5s-1_PT7213.N3FSeg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7135.+FivAg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04T08:49:53.548Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04T08:49:53.548Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04T08:49:53.548Z SendDataConnector.js: do connect now
,2015-12-04 09:49:53.549 ThaliTest[2018:3123639] jxcore: connect Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04 09:49:53.549 ThaliTest[2018:3123639] client session: connect
2015-12-04 09:49:53.549 ThaliTest[2018:3123639] client session: stateChange:0->1 Apple-Iphone6-1_PT7135.+FivAg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7213.N3FSeg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-04 09:49:56.101 ThaliTest[2018:3123457] client: found peer: Apple-Iphone5-1_PT9194.4xGkjQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9194.4xGkjQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-04 09:49:57.034 ThaliTest[2018:3123457] multipeer session: reset timer
2015-12-04 09:49:57.034 ThaliTest[2018:3123457] multipeer session: stop timer
2015-12-04 09:49:57.034 ThaliTest[2018:3123457] multipeer session: start timer: 0x1674ffa0
2015-,12-04 09:49:57.034 ThaliTest[2018:3123457] server session: connect
2015-12-04 09:49:57.035 ThaliTest[2018:3123457] server session: stateChange:0->1 Apple-Iphone6-1_PT7135
,2015-12-04 09:49:57.037 ThaliTest[2018:3123457] server: accepting invitation Apple-Iphone6-1_PT7135
,2015-12-04 09:49:58.572 ThaliTest[2018:3124497] client session: connected
2015-12-04 09:49:58.572 ThaliTest[2018:3124497] client session: stateChange:1->2 Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:49:58.591 ThaliTest[2018:3124497] client session: fireConnectCallback: Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04 09:49:58.591 ThaliTest[2018:3124497] jxcore: connect: success
2015-12-04T08:49:58.592Z SendDataConnector.js: CLIENT connected to 51878, error: null
,2015-12-04T08:49:58.592Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:49:58.593 ThaliTest[2018:3123457] client: relay established
2015-12-04 09:49:58.594 ThaliTest[2018:3123457] client: new accepted socket: 0x165ad200
,2015-12-04T08:49:58.607Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-04T08:49:58.836Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-04T08:49:59.037Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-04T08:49:59.050Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-04T08:49:59.051Z SendDataConnector.js: got all data for this round
,2015-12-04T08:49:59.052Z SendDataConnector.js: CLIENT Stop now
2015-12-04T08:49:59.052Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04 09:49:59.053 ThaliTest[2018:3123639] jxcore: disconnect
2015-12-04 09:49:59.053 ThaliTest[2018:3123639] client session: disconnectFromPeer: Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04 09:49:59.053 ThaliTest[2018:3123639] client session: disconn,ect
2015-12-04 09:49:59.053 ThaliTest[2018:3123639] client session: stateChange:2->0 Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:49:59.060 ThaliTest[2018:3123639] jxcore: disconnect: success
2015-12-04T08:49:59.061Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7135.+FivAg==
,---- round done--------
device[2]: Apple-Iphone5s-1_PT7213.N3FSeg==
2015-12-04T08:49:59.062Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7213.N3FSeg==
2015-12-04T08:49:59.062Z SendDataConnector.js: doConnect called with peer Apple-Ip,hone5s-1_PT7213.N3FSeg==
,2015-12-04T08:49:59.062Z SendDataConnector.js: do connect now
,2015-12-04 09:49:59.064 ThaliTest[2018:3123639] jxcore: connect Apple-Iphone5s-1_PT7213.N3FSeg==
2015-12-04 09:49:59.064 ThaliTest[2018:3123639] client session: connect
2015-12-04 09:49:59.064 ThaliTest[2018:3123639] client session: stateChange:0->1 Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:49:59.613 ThaliTest[2018:3124488] server session: connected
2015-12-04 09:49:59.613 ThaliTest[2018:3124488] server session: stateChange:1->2 Apple-Iphone6-1_PT7135
,2015-12-04 09:49:59.626 ThaliTest[2018:3123457] server relay: connected (to port: 51875)
,2015-12-04T08:49:59.635Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:50:00.088Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-04T08:50:00.100Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-04T08:50:00.114Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-04 09:50:00.143 ThaliTest[2018:3124494] server session: not connected Apple-Iphone6-1_PT7135
,2015-12-04 09:50:03.820 ThaliTest[2018:3124494] client session: connected
2015-12-04 09:50:03.821 ThaliTest[2018:3124494] client session: stateChange:1->2 Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:50:03.823 ThaliTest[2018:3124490] client session: fireConnectCallback: Apple-Iphone5s-1_PT7213.N3FSeg==
2015-12-04 09:50:03.823 ThaliTest[2018:3124490] jxcore: connect: success
,2015-12-04T08:50:03.824Z SendDataConnector.js: CLIENT connected to 51883, error: null
2015-12-04T08:50:03.824Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:50:03.825 ThaliTest[2018:3123457] client: relay established
2015-12-04 09:50:03.826 ThaliTest[2018:3123457] client: new accepted socket: 0x165bb2f0
,2015-12-04T08:50:03.838Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-04T08:50:04.293Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-04T08:50:04.357Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-04T08:50:04.370Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-04T08:50:04.383Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-04T08:50:04.383Z SendDataConnector.js: got all data for this round
,2015-12-04T08:50:04.383Z SendDataConnector.js: CLIENT Stop now
2015-12-04T08:50:04.384Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04 09:50:04.384 ThaliTest[2018:3123639] jxcore: disconnect
2015-12-04 09:50:04.384 ThaliTest[2018:3123639] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7213.N3FSeg==
2015-12-04 09:50:04.384 ThaliTest[2018:3123639] client session: disconnect
2015-12-04 09:50:04.384 ThaliTest[2018:3123639] client session: stateChange:2->0 Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:50:04.390 ThaliTest[2018:3123639] jxcore: disconnect: success
2015-12-04T08:50:04.391Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7213.N3FSeg==
---- round done--------
,device[3]: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04T08:50:04.393Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04T08:50:04.393Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9194.4xGkjQ==
20,15-12-04T08:50:04.393Z SendDataConnector.js: do connect now
2015-12-04 09:50:04.393 ThaliTest[2018:3123639] jxcore: connect Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:50:04.393 ThaliTest[2018:3123639] client session: connect
2015-12-04 09:50:04.393 ThaliTest[2018:3123639] client session: stateChange:0->1 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:07.440 ThaliTest[2018:3124494] client session: connected
2015-12-04 09:50:07.440 ThaliTest[2018:3124494] client session: stateChange:1->2 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:07.478 ThaliTest[2018:3124490] client session: fireConnectCallback: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:50:07.478 ThaliTest[2018:3124490] jxcore: connect: success
2015-12-04T08:50:07.479Z SendDataConnector.js: CLIENT connected to 51886, error: null
,2015-12-04T08:50:07.479Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:50:07.480 ThaliTest[2018:3123457] client: relay established
2015-12-04 09:50:07.480 ThaliTest[2018:3123457] client: new accepted socket: 0x166a79e0
,2015-12-04T08:50:07.493Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-04T08:50:08.001Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-04T08:50:08.015Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-04T08:50:18.023Z SendDataConnector.js: Receiving data timeout now
,2015-12-04T08:50:18.023Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-04T08:50:18.024Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-04T08:50:18.024Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-04T08:50:18.024Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:50:18.025 ThaliTest[2018:3123457] client: socket closed
,2015-12-04 09:50:18.025 ThaliTest[2018:3123457] client relay: socket disconnected
2015-12-04 09:50:18.025 ThaliTest[2018:3123457] client relay: 0x166a79e0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer", UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-04 09:50:18.025 ThaliTest[2018:3123457] client session: socket closed: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:50:18.026 ThaliTest[2018:3123457] client session: onLinkFailure:, Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:50:18.026 ThaliTest[2018:3123457] client session: disconnect
2015-12-04 09:50:18.026 ThaliTest[2018:3123457] client session: stateChange:2->0 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:18.027 ThaliTest[2018:3123457] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04T08:50:23.025Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04T08:50:23.025Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:27.035 ThaliTest[2018:3123457] multipeer session: restart
,2015-12-04 09:50:27.046 ThaliTest[2018:3123457] client: found peer: Apple-Iphone5s-1_PT7213.N3FSeg==
2015-12-04 09:50:27.047 ThaliTest[2018:3123457] client: found peer: Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04 09:50:27.047 ThaliTest[2018:3123457] client: found peer: Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:28.037 ThaliTest[2018:3123639] jxcore: disconnect
2015-12-04 09:50:28.038 ThaliTest[2018:3123639] jxcore: disconnect: fail
2015-12-04T08:50:28.038Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9194.4xGkj,Q==
2015-12-04T08:50:28.038Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT9194.4xGkjQ== with availability status: true
2015-12-04T08:50:28.038Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04T08:50:28.038Z SendDataConnector.js: do connect now
,2015-12-04 09:50:28.039 ThaliTest[2018:3123639] jxcore: connect Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:50:28.039 ThaliTest[2018:3123639] client session: connect
2015-12-04 09:50:28.039 ThaliTest[2018:3123639] client session: stateChange:0->1 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:30.536 ThaliTest[2018:3124593] client session: connected
2015-12-04 09:50:30.536 ThaliTest[2018:3124593] client session: stateChange:1->2 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:30.546 ThaliTest[2018:3124599] client session: fireConnectCallback: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:50:30.546 ThaliTest[2018:3124599] jxcore: connect: success
2015-12-04T08:50:30.546Z SendDataConnector.js: CLIENT connected to 51890, error: null
2015-12-04T08:50:30.546Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:50:30.547 ThaliTest[2018:3123457] client: relay established
2015-12-04 09:50:30.547 ThaliTest[2018:3123457] client: new accepted socket: 0x163f3170
,2015-12-04T08:50:30.560Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-04T08:50:40.588Z SendDataConnector.js: Receiving data timeout now
,2015-12-04T08:50:40.589Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:50:40.589Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-04T08:50:40.589Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-04T08:50:40.589Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:50:40.590 ThaliTest[2018:3123457] client: socket closed
2015-12-04 09:50:40.590 ThaliTest[2018:3123457] client relay: socket disconnected
2015-12-04 09:50:40.590 ThaliTest[2018:3123457] client relay: 0x163f3170 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-04 09:50:40.590 ThaliTest[2018:3123457] client session: socket closed: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:50:40.590 ThaliTest[2018:3123457] client session: onLinkFailure: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:50:40.590 ThaliTest[2018:3123457] client session: disconnect
2015-12-04 09:50:40.590 ThaliTest[2018:3123457] client session: stateChange:2->0 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:40.592 ThaliTest[2018:3123457] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04T08:50:45.601Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04T08:50:45.601Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:50.615 ThaliTest[2018:3123639] jxcore: disconnect
2015-12-04 09:50:50.615 ThaliTest[2018:3123639] jxcore: disconnect: fail
2015-12-04T08:50:50.615Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04T08:50:50.615Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT9194.4xGkjQ== with availability status: true
2015-12-04T08:50:50.615Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9194.4xGkjQ==
2,015-12-04T08:50:50.615Z SendDataConnector.js: do connect now
2015-12-04 09:50:50.616 ThaliTest[2018:3123639] jxcore: connect Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:50.616 ThaliTest[2018:3123639] client session: connect
2015-12-04 09:50:50.616 ThaliTest[2018:3123639] client session: stateChange:0->1 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:53.713 ThaliTest[2018:3124661] client session: connected
2015-12-04 09:50:53.713 ThaliTest[2018:3124661] client session: stateChange:1->2 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:53.754 ThaliTest[2018:3124670] client session: fireConnectCallback: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:50:53.754 ThaliTest[2018:3124670] jxcore: connect: success
2015-12-04T08:50:53.754Z SendDataConnector.js: CLIENT connected to 51892, error: null
,2015-12-04T08:50:53.754Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:50:53.756 ThaliTest[2018:3123457] client: relay established
2015-12-04 09:50:53.756 ThaliTest[2018:3123457] client: new accepted socket: 0x1674e7a0
,2015-12-04T08:50:53.769Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-04 09:50:57.036 ThaliTest[2018:3123457] multipeer session: restart
,2015-12-04 09:50:57.049 ThaliTest[2018:3123457] client: found peer: Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04 09:50:57.049 ThaliTest[2018:3123457] client: found peer: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:50:57.050 ThaliTest[2018:3123457] client: found peer: Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04T08:51:03.798Z SendDataConnector.js: Receiving data timeout now
,2015-12-04T08:51:03.798Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-04T08:51:03.798Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:51:03.799Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-04T08:51:03.799Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:51:03.799 ThaliTest[2018:3123457] client: socket closed
2015-12-04 09:51:03.800 ThaliTest[2018:3123457] client relay: socket disconnected
2015-12-04 09:51:03.800 ThaliTest[2018:3123457] client relay: 0x1674e7a0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-04 09:51:03.800 ThaliTest[2018:3123457] client session: socket closed: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12,-04 09:51:03.800 ThaliTest[2018:3123457] client session: onLinkFailure: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:51:03.800 ThaliTest[2018:3123457] client session: disconnect
2015-12-04 09:51:03.800 ThaliTest[2018:3123457] client session: stateChange:2->0 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:51:03.802 ThaliTest[2018:3123457] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04T08:51:08.810Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04T08:51:08.810Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:51:13.823 ThaliTest[2018:3123639] jxcore: disconnect
2015-12-04 09:51:13.823 ThaliTest[2018:3123639] jxcore: disconnect: fail
2015-12-04T08:51:13.823Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9194.4xGkj,Q==
2015-12-04T08:51:13.823Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT9194.4xGkjQ== with availability status: true
2015-12-04T08:51:13.823Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9194.4xGkjQ==
2,015-12-04T08:51:13.823Z SendDataConnector.js: do connect now
,2015-12-04 09:51:13.824 ThaliTest[2018:3123639] jxcore: connect Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:51:13.824 ThaliTest[2018:3123639] client session: connect
2015-12-04 09:51:13.824 ThaliTest[2018:3123639] client session: stateChange:0->1 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:51:16.694 ThaliTest[2018:3124722] client session: connected
2015-12-04 09:51:16.694 ThaliTest[2018:3124722] client session: stateChange:1->2 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:51:16.751 ThaliTest[2018:3124725] client session: fireConnectCallback: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:51:16.751 ThaliTest[2018:3124725] jxcore: connect: success
2015-12-04T08:51:16.752Z SendDataConnector.js: CLIENT connected to 51896, error: null
,2015-12-04T08:51:16.752Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:51:16.753 ThaliTest[2018:3123457] client: relay established
2015-12-04 09:51:16.753 ThaliTest[2018:3123457] client: new accepted socket: 0x16752430
,2015-12-04T08:51:16.767Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-04T08:51:26.797Z SendDataConnector.js: Receiving data timeout now
2015-12-04T08:51:26.797Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:51:26.798Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:51:26.798Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-04T08:51:26.798Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:51:26.799 ThaliTest[2018:3123457] client: socket closed
,2015-12-04 09:51:26.799 ThaliTest[2018:3123457] client relay: socket disconnected
,2015-12-04 09:51:26.800 ThaliTest[2018:3123457] client relay: 0x16752430 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-04 09:51:26.800 ThaliTest[2018:3123457] client session: socket closed: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:51:26.800 ThaliTest[2018:3123457] client session: onLinkFailure: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:51:26.800 ThaliTes,t[2018:3123457] client session: disconnect
2015-12-04 09:51:26.800 ThaliTest[2018:3123457] client session: stateChange:2->0 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:51:26.802 ThaliTest[2018:3123457] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:51:27.035 ThaliTest[2018:3123457] multipeer session: restart
,2015-12-04 09:51:27.046 ThaliTest[2018:3123457] client: found peer: Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:51:27.047 ThaliTest[2018:3123457] client: found peer: Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04 09:51:27.048 ThaliTest[2018:3123457] client: found peer: Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04T08:51:31.800Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04T08:51:31.801Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:51:36.808 ThaliTest[2018:3123639] jxcore: disconnect
,2015-12-04 09:51:36.808 ThaliTest[2018:3123639] jxcore: disconnect: fail
,2015-12-04T08:51:36.808Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04T08:51:36.809Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT9194.4xGkjQ== with availability status: ,true
2015-12-04T08:51:36.809Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04T08:51:36.809Z SendDataConnector.js: do connect now
,2015-12-04 09:51:36.809 ThaliTest[2018:3123639] jxcore: connect Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:51:36.809 ThaliTest[2018:3123639] client session: connect
,2015-12-04 09:51:36.809 ThaliTest[2018:3123639] client session: stateChange:0->1 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:51:39.695 ThaliTest[2018:3124752] client session: connected
2015-12-04 09:51:39.695 ThaliTest[2018:3124752] client session: stateChange:1->2 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:51:39.733 ThaliTest[2018:3124775] client session: fireConnectCallback: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:51:39.733 ThaliTest[2018:3124775] jxcore: connect: success
2015-12-04T08:51:39.734Z SendDataConnector.js: CLIENT connected to 51900, error: null
2015-12-04T08:51:39.734Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:51:39.735 ThaliTest[2018:3123457] client: relay established
2015-12-04 09:51:39.736 ThaliTest[2018:3123457] client: new accepted socket: 0x14584f50
,2015-12-04T08:51:39.748Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-04 09:51:42.833 ThaliTest[2018:3123457] multipeer session: reset timer
2015-12-04 09:51:42.833 ThaliTest[2018:3123457] multipeer session: stop timer
2015-12-04 09:51:42.833 ThaliTest[2018:3123457] multipeer session: start timer: 0x1674ffa0
2015-12-04 09:51:42.833 ThaliTest[2018:3123457] server session: connect
2015-12-04 09:51:42.833 ThaliTest[2018:3123457] server session: stateChange:0->1 Apple-Iphone5s-1_PT7213
,2015-12-04 09:51:42.835 ThaliTest[2018:3123457] server: accepting invitation Apple-Iphone5s-1_PT7213
,2015-12-04 09:51:45.517 ThaliTest[2018:3124775] server session: connected
2015-12-04 09:51:45.517 ThaliTest[2018:3124775] server session: stateChange:1->2 Apple-Iphone5s-1_PT7213
,2015-12-04 09:51:45.520 ThaliTest[2018:3123457] server relay: connected (to port: 51875)
,2015-12-04T08:51:45.530Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:51:45.923Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-04T08:51:46.058Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-04 09:51:46.112 ThaliTest[2018:3124775] server session: not connected Apple-Iphone5s-1_PT7213
,2015-12-04 09:51:48.108 ThaliTest[2018:3123457] multipeer session: reset timer
2015-12-04 09:51:48.108 ThaliTest[2018:3123457] multipeer session: stop timer
2015-12-04 09:51:48.108 ThaliTest[2018:3123457] multipeer session: start timer: 0x1674ffa0
2015-12-04 09:51:48.108 ThaliTest[2018:3123457] server session: connect
2015-12-04 09:51:48.108 ThaliTest[2018:3123457] server session: stateChange:0->1 Apple-Iphone5-1_PT9194
,2015-12-04 09:51:48.112 ThaliTest[2018:3123457] server: accepting invitation Apple-Iphone5-1_PT9194
,2015-12-04T08:51:49.768Z SendDataConnector.js: Receiving data timeout now
2015-12-04T08:51:49.768Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:51:49.768Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:51:49.769Z SendDataConnector.js: CLIENT Stop now
2015-12-04T08:51:49.769Z SendDataConnector.js: Stop data retrieving timer
2015-12-04T08:51:49.769Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04 09:51:49.770 ThaliTest[2018:3123639] jxcore: disconnect
,2015-12-04 09:51:49.770 ThaliTest[2018:3123639] client session: disconnectFromPeer: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:51:49.770 ThaliTest[2018:3123639] client session: disconnect
2015-12-04 09:51:49.770 ThaliTest[2018:3123639] client session: stateChange:2->0 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:51:49.772 ThaliTest[2018:3123639] jxcore: disconnect: success
2015-12-04T08:51:49.772Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9194.4xGkjQ==
---- round done--------
,weAreDoneNow , resultArray.length: 3
done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT6975","time":117002,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT7135.+FivAg==","time":5503,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-,1_PT7213.N3FSeg==","time":5321,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT9194.4xGkjQ==","time":105375,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000}]}
,sendList : 100% : 5503 ms, 99% : 5503 ms, 95 : 5503 ms, 90% : 5503 ms.
Result count 2, range 5321 ms to  5503 ms.
sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone5-1_PT9194.4xGkjQ==, Tried : 5
sendList never tried peers c,ount : 0 [0 %]
2015-12-04T08:51:49.778Z SendDataConnector.js: CLIENT Stop now
2015-12-04T08:51:49.778Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-04T08:51:49.778Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:51:50.831 ThaliTest[2018:3124790] server session: connected
2015-12-04 09:51:50.831 ThaliTest[2018:3124790] server session: stateChange:1->2 Apple-Iphone5-1_PT9194
,2015-12-04 09:51:50.889 ThaliTest[2018:3123457] server relay: connected (to port: 51875)
,2015-12-04T08:51:50.893Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:51:51.351Z SendDataTCPServer.js: TCP/IP server has received 29760 bytes of data
,2015-12-04T08:51:51.366Z SendDataTCPServer.js: TCP/IP server has received 62496 bytes of data
,2015-12-04T08:51:51.417Z SendDataTCPServer.js: TCP/IP server has received 78432 bytes of data
,2015-12-04T08:51:51.430Z SendDataTCPServer.js: TCP/IP server has received 89280 bytes of data
,2015-12-04T08:51:51.443Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-04 09:51:51.548 ThaliTest[2018:3124791] server session: not connected Apple-Iphone5-1_PT9194
,DBG, CoordinatorConnector command called
command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
,testSendData stopped
,2015-12-04 09:51:51.715 ThaliTest[2018:3123639] jxcore: stopBroadcasting
,2015-12-04 09:51:51.715 ThaliTest[2018:3123639] THEMultipeerSession stopping peer
2015-12-04 09:51:51.716 ThaliTest[2018:3123639] multipeer session: stop timer
2015-12-04 09:51:51.716 ThaliTest[2018:3123639] server session: disconnect
2015-12-04 09:51:51.716 ThaliTest[2018:3123639] server session: stateChange:2->0 Apple-Iphone5s-1_PT7213
,2015-12-04 09:51:51.718 ThaliTest[2018:3123639] server session: disconnect
2015-12-04 09:51:51.718 ThaliTest[2018:3123639] server session: stateChange:2->0 Apple-Iphone5-1_PT9194
,2015-12-04 09:51:51.724 ThaliTest[2018:3123639] server session: disconnect
2015-12-04 09:51:51.725 ThaliTest[2018:3123639] server session: stateChange:2->0 Apple-Iphone6-1_PT7135
,2015-12-04 09:51:51.730 ThaliTest[2018:3123639] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-04T08:51:51.745Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04T08:51:51.746Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04T08:51:51.746Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-04T08:51:51.747Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT7213.N3FSeg==\",\"time\":5321,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone6-1_PT7135.+FivAg==\",\"time\":5503,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone5-1_PT9194.4xGkjQ==\",\"time\":105375,\,"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000}],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !

```
