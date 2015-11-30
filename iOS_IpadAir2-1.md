#### Test 51986340a77003b_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51986340a77003b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/E45AFA93-BEFE-40C3-BDFB-423261A02D38/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/E45AFA93-BEFE-40C3-BDFB-423261A02D38/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51986340a77003b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51986340a77003b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9793B5F2-3110-4D1C-80E6-17BE606DBE9B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57889"
,(lldb)     command script import "/tmp/E45AFA93-BEFE-40C3-BDFB-423261A02D38/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-30 10:45:37.710 ThaliTest[1618:2477091] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CB1E01B3-306B-4DEC-A1BB-1BE1F00C8D1B/Library/Cookies/Cookies.binarycookies
,2015-11-30 10:45:37.996 ThaliTest[1618:2477091] Apache Cordova native platform version 3.9.2 is starting.
2015-11-30 10:45:37.996 ThaliTest[1618:2477091] Multi-tasking -> Device: YES, App: YES
,2015-11-30 10:45:38.002 ThaliTest[1618:2477091] Unlimited access to network resources
,2015-11-30 10:45:38.008 ThaliTest[1618:2477091] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-30 10:45:42.256 ThaliTest[1618:2477091] Resetting plugins due to page load.
,2015-11-30 10:45:43.550 ThaliTest[1618:2477091] Finished load of: file:///var/mobile/Containers/Bundle/Application/9793B5F2-3110-4D1C-80E6-17BE606DBE9B/ThaliTest.app/www/index.html
,2015-11-30 10:45:43.695 ThaliTest[1618:2477091] JXcore Cordova plugin initializing
,2015-11-30 10:45:43.696 ThaliTest[1618:2477321] JXcore instance initializing
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
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Radios toggled
,my name is : Apple-IpadAir2-1_PT7551
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
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
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
serverPort is 63399
2015-11-30 10:53:33.296 ThaliTest[1618:2477321] jxcore: startBroadcasting
,2015-11-30 10:53:33.302 ThaliTest[1618:2477321] server: starting Apple-IpadAir2-1_PT7551.0H/lSg==
2015-11-30 10:53:33.303 ThaliTest[1618:2477321] multipeer session: start timer: 0x156dbbe0
,2015-11-30 10:53:33.303 ThaliTest[1618:2477321] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT7551
2015-11-30 10:53:33.303 ThaliTest[1618:2477321] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-11-30T09:53:33.305Z SendDataTCPServer.js: TCP/IP server is bound to port: 63399
,2015-11-30 10:53:33.922 ThaliTest[1618:2477091] client: found peer: Apple-Iphone6-1_PT7971.JDbK/w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7971.JDbK/w==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:53:33.926Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:53:33.926Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:53:33.926Z SendDataConnector.js: do connect now
2015-11-30 10:53:33.926 ThaliTest[1618:2477321] jxcore: connect Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:53:33.926 ThaliTest[1618:2477321] client session: connect
2015-11-30 10:53:33.927 ThaliTest[1618:2477321] client session: stateChange:0->1 Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:53:33.997 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5s-1_PT9746.l6NbbA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9746.l6NbbA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-30 10:53:34.911 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2135.SJMPng==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-30 10:53:36.605 ThaliTest[1618:2478166] client session: connected
2015-11-30 10:53:36.605 ThaliTest[1618:2478166] client session: stateChange:1->2 Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:53:36.618 ThaliTest[1618:2478164] client session: fireConnectCallback: Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30 10:53:36.619 ThaliTest[1618:2478164] jxcore: connect: success
,2015-11-30T09:53:36.619Z SendDataConnector.js: CLIENT connected to 63402, error: null
2015-11-30T09:53:36.619Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 10:53:36.620 ThaliTest[1618:2477091] client: relay established
2015-11-30 10:53:36.621 ThaliTest[1618:2477091] client: new accepted socket: 0x1760cb60
,2015-11-30T09:53:36.634Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-30 10:53:37.069 ThaliTest[1618:2477091] multipeer session: reset timer
2015-11-30 10:53:37.069 ThaliTest[1618:2477091] multipeer session: stop timer
2015-11-30 10:53:37.069 ThaliTest[1618:2477091] multipeer session: start timer: 0x156dbbe0
,2015-11-30 10:53:37.069 ThaliTest[1618:2477091] server session: connect
2015-11-30 10:53:37.070 ThaliTest[1618:2477091] server session: stateChange:0->1 Apple-Iphone6-1_PT7971
,2015-11-30 10:53:37.073 ThaliTest[1618:2477091] server: accepting invitation Apple-Iphone6-1_PT7971
,2015-11-30T09:53:37.090Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-30T09:53:37.101Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-30T09:53:37.114Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-30 10:53:38.193 ThaliTest[1618:2477091] multipeer session: reset timer
2015-11-30 10:53:38.194 ThaliTest[1618:2477091] multipeer session: stop timer
2015-11-30 10:53:38.194 ThaliTest[1618:2477091] multipeer session: start timer: 0x156dbbe0
2015-11-30 10:53:38.194 ThaliTest[1618:2477091] server session: connect
2015-11-30 10:53:38.194 ThaliTest[1618:2477091] server session: stateChange:0->1 Apple-Iphone5s-1_PT9746
,2015-11-30 10:53:38.197 ThaliTest[1618:2477091] server: accepting invitation Apple-Iphone5s-1_PT9746
,2015-11-30 10:53:40.400 ThaliTest[1618:2478170] server session: connected
2015-11-30 10:53:40.400 ThaliTest[1618:2478170] server session: stateChange:1->2 Apple-Iphone6-1_PT7971
,2015-11-30 10:53:40.402 ThaliTest[1618:2477091] server relay: connected (to port: 63399)
,2015-11-30T09:53:40.410Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30 10:53:40.875 ThaliTest[1618:2478173] server session: connected
2015-11-30 10:53:40.875 ThaliTest[1618:2478173] server session: stateChange:1->2 Apple-Iphone5s-1_PT9746
,2015-11-30 10:53:40.877 ThaliTest[1618:2477091] server relay: connected (to port: 63399)
2015-11-30T09:53:40.877Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30T09:53:40.926Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-11-30T09:53:41.141Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-11-30T09:53:41.154Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-30T09:53:41.215Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-11-30 10:53:41.233 ThaliTest[1618:2478164] server session: not connected Apple-Iphone6-1_PT7971
,2015-11-30T09:53:41.275Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-11-30T09:53:41.289Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-11-30T09:53:41.364Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-11-30T09:53:41.399Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-11-30T09:53:41.413Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-30 10:53:41.735 ThaliTest[1618:2478207] server session: not connected Apple-Iphone5s-1_PT9746
,2015-11-30 10:54:08.194 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 10:54:08.206 ThaliTest[1618:2477091] client: found peer: Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30 10:54:08.206 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5s-1_PT9746.l6NbbA==
2015-11-30 10:54:08.206 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30T09:54:27.122Z SendDataConnector.js: Receiving data timeout now
2015-11-30T09:54:27.122Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30T09:54:27.123Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30T09:54:27.124Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-30T09:54:27.124Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-30 10:54:27.125 ThaliTest[1618:2477091] client: socket closed
2015-11-30 10:54:27.125 ThaliTest[1618:2477091] client relay: socket disconnected
2015-11-30 10:54:27.125 ThaliTest[1618:2477091] client relay: 0x1760cb60 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-11-30 10:54:27.125 ThaliTest[1618:2477091] client session: socket closed: Apple-Iphone6-1_PT7971.JDbK/w==
2015-11,-30 10:54:27.125 ThaliTest[1618:2477091] client session: onLinkFailure: Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30 10:54:27.125 ThaliTest[1618:2477091] client session: disconnect
2015-11-30 10:54:27.125 ThaliTest[1618:2477091] client session: stateChange:2->0 Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:54:27.128 ThaliTest[1618:2477091] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30T09:54:32.129Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:54:32.130Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:54:37.141 ThaliTest[1618:2477321] jxcore: disconnect
2015-11-30 10:54:37.142 ThaliTest[1618:2477321] jxcore: disconnect: fail
,2015-11-30T09:54:37.142Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:54:37.142Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT7971.JDbK/w== with availability status: ,true
,2015-11-30T09:54:37.142Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:54:37.143Z SendDataConnector.js: do connect now
,2015-11-30 10:54:37.143 ThaliTest[1618:2477321] jxcore: connect Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:54:37.143 ThaliTest[1618:2477321] client session: connect
,2015-11-30 10:54:37.143 ThaliTest[1618:2477321] client session: stateChange:0->1 Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:54:37.304 ThaliTest[1618:2477091] client: lost peer: Apple-Iphone5s-1_PT9746.l6NbbA==
2015-11-30 10:54:37.305 ThaliTest[1618:2477091] client session: onPeerLost: Apple-Iphone5s-1_PT9746.l6NbbA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9746.l6NbbA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-30 10:54:38.194 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 10:54:38.206 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
2015-11-30 10:54:38.206 ThaliTest[1618:2477091] client: found peer: Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:55:08.194 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 10:55:08.204 ThaliTest[1618:2477091] client: found peer: Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30 10:55:08.205 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 10:55:09.441 ThaliTest[1618:2477091] client: lost peer: Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30 10:55:09.441 ThaliTest[1618:2477091] client session: onPeerLost: Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30 10:55:09.441 ThaliTest[1618:2477091], client session: onLinkFailure: Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30 10:55:09.441 ThaliTest[1618:2477091] client session: disconnect
2015-11-30 10:55:09.441 ThaliTest[1618:2477091] client session: stateChange:1->0 Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30 10:55:09.441 ThaliTest[1618:2477091] client session: fireConnectCallback: Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30 10:55:09.441 ThaliTest[1618:2477091] jxcore: connect: fail: Peer disconnected
,2015-11-30T09:55:09.442Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-30T09:55:09.443Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-30T09:55:09.443Z SendDataConnector.js: tryAgain afer: 5000 ms.,
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7971.JDbK/w==","peerName":"(null)","peerAvailable":false}]
,2015-11-30T09:55:14.443Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:55:14.444Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:55:19.451 ThaliTest[1618:2477321] jxcore: disconnect
2015-11-30 10:55:19.451 ThaliTest[1618:2477321] jxcore: disconnect: fail
2015-11-30T09:55:19.451Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7971.JDbK/,w==
2015-11-30T09:55:19.451Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT7971.JDbK/w== with availability status: true
2015-11-30T09:55:19.451Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:55:19.451Z SendDataConnector.js: do connect now
2015-11-30 10:55:19.451 ThaliTest[1618:2477321] jxcore: connect Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:55:19.452 ThaliTest[1618:2477321] client: connect: unreachable Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30 10:55:19.452 ThaliTest[1618:2477321] jxcore: connect: fail: Peer unreachable
,2015-11-30T09:55:19.452Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-11-30T09:55:19.452Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-11-30T09:55:19.452Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-30T09:55:24.460Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:55:24.460Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:55:29.461 ThaliTest[1618:2477321] jxcore: disconnect
2015-11-30 10:55:29.461 ThaliTest[1618:2477321] jxcore: disconnect: fail
2015-11-30T09:55:29.461Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7971.JDbK/,w==
2015-11-30T09:55:29.461Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT7971.JDbK/w== with availability status: true
2015-11-30T09:55:29.461Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7971.JDbK/w==
2,015-11-30T09:55:29.461Z SendDataConnector.js: do connect now
2015-11-30 10:55:29.461 ThaliTest[1618:2477321] jxcore: connect Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30 10:55:29.462 ThaliTest[1618:2477321] client: connect: unreachable Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:55:29.462 ThaliTest[1618:2477321] jxcore: connect: fail: Peer unreachable
2015-11-30T09:55:29.462Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-11-30T09:55:29.462Z SendDataConnector.js: CLIENT Can not Connect: P,eer unreachable
2015-11-30T09:55:29.462Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-30T09:55:34.467Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30T09:55:34.467Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:55:38.194 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 10:55:38.776 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 10:55:39.469 ThaliTest[1618:2477321] jxcore: disconnect
2015-11-30 10:55:39.469 ThaliTest[1618:2477321] jxcore: disconnect: fail
2015-11-30T09:55:39.469Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:55:39.469Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT7971.JDbK/w== with availability status: true
2015-11-30T09:55:39.469Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:55:39.469Z SendDataConnector.js: do connect now
2015-11-30 10:55:39.470 ThaliTest[1618:2477321] jxcore: connect Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:55:39.470 ThaliTest[1618:2477321] client: connect: unreachable Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30 10:55:39.470 ThaliTest[1618:2477321] jxcore: connect: fail: Peer unreachable
2015-11-30T09:55:39.470Z SendDataConnector.js: CLIENT con,nected to 0, error: Peer unreachable
2015-11-30T09:55:39.470Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-11-30T09:55:39.471Z SendDataConnector.js: CLIENT Stop now
,2015-11-30T09:55:39.472Z SendDataConnector.js: Stop data retrieving timer
,2015-11-30 10:55:39.472 ThaliTest[1618:2477321] jxcore: disconnect
2015-11-30 10:55:39.473 ThaliTest[1618:2477321] jxcore: disconnect: fail
2015-11-30T09:55:39.473Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7971.JDbK/,w==
---- round done--------
,device[2]: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30T09:55:39.474Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2135.SJMPng==
2015-11-30T09:55:39.474Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30T09:55:39.474Z SendDataConnector.js: do connect now
,2015-11-30 10:55:39.475 ThaliTest[1618:2477321] jxcore: connect Apple-Iphone5-1_PT2135.SJMPng==
2015-11-30 10:55:39.475 ThaliTest[1618:2477321] client session: connect
,2015-11-30 10:55:39.475 ThaliTest[1618:2477321] client session: stateChange:0->1 Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 10:55:42.815 ThaliTest[1618:2478477] client session: connected
2015-11-30 10:55:42.815 ThaliTest[1618:2478477] client session: stateChange:1->2 Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 10:55:42.877 ThaliTest[1618:2478475] client session: fireConnectCallback: Apple-Iphone5-1_PT2135.SJMPng==
2015-11-30 10:55:42.877 ThaliTest[1618:2478475] jxcore: connect: success
,2015-11-30T09:55:42.878Z SendDataConnector.js: CLIENT connected to 63413, error: null
2015-11-30T09:55:42.878Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 10:55:42.879 ThaliTest[1618:2477091] client: relay established
2015-11-30 10:55:42.879 ThaliTest[1618:2477091] client: new accepted socket: 0x1902c810
,2015-11-30T09:55:42.892Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-30T09:55:43.150Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-30T09:55:43.163Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-30T09:55:43.174Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-30T09:55:43.174Z SendDataConnector.js: got all data for this round
,2015-11-30T09:55:43.175Z SendDataConnector.js: CLIENT Stop now
,2015-11-30T09:55:43.175Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 10:55:43.176 ThaliTest[1618:2477321] jxcore: disconnect
2015-11-30 10:55:43.176 ThaliTest[1618:2477321] client session: disconnectFromPeer: Apple-Iphone5-1_PT2135.SJMPng==
2015-11-30 10:55:43.176 ThaliTest[1618:2477321] client session: disconnect
2015-11-30 10:55:43.176 ThaliTest[1618:2477321] client session: stateChange:2->0 Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 10:55:43.181 ThaliTest[1618:2477321] jxcore: disconnect: success
2015-11-30T09:55:43.181Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2135.SJMPng==
---- round done--------
,2015-11-30 10:56:08.194 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 10:56:08.203 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 10:56:38.194 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 10:56:38.203 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 10:57:08.194 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 10:57:08.205 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 10:57:38.194 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 10:57:39.652 ThaliTest[1618:2477091] multipeer session: reset timer
2015-11-30 10:57:39.652 ThaliTest[1618:2477091] multipeer session: stop timer
2015-11-30 10:57:39.652 ThaliTest[1618:2477091] multipeer session: start timer: 0x156dbbe0
2015-,11-30 10:57:39.652 ThaliTest[1618:2477091] server session: connect
2015-11-30 10:57:39.652 ThaliTest[1618:2477091] server session: stateChange:0->1 Apple-Iphone5-1_PT2135
,2015-11-30 10:57:39.656 ThaliTest[1618:2477091] server: accepting invitation Apple-Iphone5-1_PT2135
,2015-11-30 10:57:42.391 ThaliTest[1618:2478736] server session: connected
2015-11-30 10:57:42.391 ThaliTest[1618:2478736] server session: stateChange:1->2 Apple-Iphone5-1_PT2135
,2015-11-30 10:57:42.401 ThaliTest[1618:2477091] server relay: connected (to port: 63399)
,2015-11-30T09:57:42.408Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30T09:57:42.969Z SendDataTCPServer.js: TCP/IP server has received 5952 bytes of data
,2015-11-30T09:57:42.994Z SendDataTCPServer.js: TCP/IP server has received 29760 bytes of data
,2015-11-30T09:57:43.044Z SendDataTCPServer.js: TCP/IP server has received 46624 bytes of data
,2015-11-30T09:57:43.057Z SendDataTCPServer.js: TCP/IP server has received 72416 bytes of data
,2015-11-30T09:57:43.118Z SendDataTCPServer.js: TCP/IP server has received 95232 bytes of data
,2015-11-30 10:57:43.239 ThaliTest[1618:2478761] server session: not connected Apple-Iphone5-1_PT2135
,2015-11-30T09:57:43.241Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-30 10:58:09.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 10:58:09.660 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 10:58:39.654 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 10:58:39.662 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 10:59:09.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 10:59:09.865 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 10:59:39.654 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 10:59:39.660 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:00:09.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:00:39.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:00:39.661 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:01:09.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:01:09.962 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:01:39.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:01:39.660 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:02:09.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:02:09.661 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:02:39.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:02:39.662 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:03:09.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:03:09.960 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:03:39.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:03:39.662 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:04:09.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:04:09.661 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:04:39.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:04:39.662 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:05:09.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:05:09.663 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:05:39.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:06:09.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:06:09.660 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:06:39.654 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:06:39.661 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:07:09.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:07:09.660 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:07:39.654 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:07:39.661 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:08:09.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:08:09.694 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:08:39.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:08:39.661 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:09:09.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:09:09.660 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:09:39.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:09:39.852 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:10:09.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:10:09.660 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,timeout now
,dun
,weAreDoneNow , resultArray.length: 2
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT7551","time":1000023,"result":"TIMEOUT","sendList":[{"name":"Apple-Iphone6-1_PT7971.JDbK/w==","time":125545,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name":"Apple-Iphone5-1_PT2135.SJMPng==","time":3701,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 3701 ms, 99% : 3701 ms, 95 : 3701 ms, 90% : 3701 ms.
,Result count 1, range 3701 ms to  3701 ms.
sendList failed peers count : 1 [50 %]
- Peer ID : Apple-Iphone6-1_PT7971.JDbK/w==, Tried : 5
sendList never tried peers count : 0 [0 %]
2015-11-30T10:10:13.319Z SendDataConnector.js: CLIENT Stop now
,2015-11-30 11:10:39.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:10:41.311 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:11:09.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:11:09.662 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:11:39.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:11:39.661 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:12:09.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:12:09.823 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 11:12:39.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:13:09.653 ThaliTest[1618:2477091] multipeer session: restart
,2015-11-30 11:13:09.661 ThaliTest[1618:2477091] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==

```
