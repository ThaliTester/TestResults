#### Test 5357450766a890e_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5357450766a890e/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/0577D2F2-13E7-4710-AE64-B80F8B3B0E03/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/0577D2F2-13E7-4710-AE64-B80F8B3B0E03/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5357450766a890e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5357450766a890e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D03B1A3B-68F4-4D77-B320-05ED2F129342/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55387"
,(lldb)     command script import "/tmp/0577D2F2-13E7-4710-AE64-B80F8B3B0E03/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-14 16:17:20.355 ThaliTest[1028:1138243] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D834E11D-9815-4755-9C46-C584B52FA257/Library/Cookies/Cookies.binarycookies
,2015-12-14 16:17:20.730 ThaliTest[1028:1138243] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-14 16:17:20.731 ThaliTest[1028:1138243] Multi-tasking -> Device: YES, App: YES
,2015-12-14 16:17:20.740 ThaliTest[1028:1138243] Unlimited access to network resources
,2015-12-14 16:17:20.749 ThaliTest[1028:1138243] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-14 16:17:30.360 ThaliTest[1028:1138243] Resetting plugins due to page load.
,2015-12-14 16:17:34.086 ThaliTest[1028:1138243] Finished load of: file:///var/mobile/Containers/Bundle/Application/D03B1A3B-68F4-4D77-B320-05ED2F129342/ThaliTest.app/www/index.html
,2015-12-14 16:17:34.259 ThaliTest[1028:1138243] JXcore Cordova plugin initializing
,2015-12-14 16:17:34.259 ThaliTest[1028:1138507] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-IpadAir2-1_PT6360
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 57197
,2015-12-14 16:24:09.192 ThaliTest[1028:1138507] jxcore: startBroadcasting
,2015-12-14 16:24:09.211 ThaliTest[1028:1138507] server: starting Apple-IpadAir2-1_PT6360.8G12NA==
,2015-12-14 16:24:09.213 ThaliTest[1028:1138507] multipeer session: start timer: 0x14ec3050
,2015-12-14 16:24:09.214 ThaliTest[1028:1138507] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT6360
,2015-12-14 16:24:09.215 ThaliTest[1028:1138507] jxcore: startBroadcasting: success
,StartBroadcasting started ok
2015-12-14T15:24:09.219Z SendDataTCPServer.js: TCP/IP server is bound to port: 57197
,2015-12-14 16:24:10.424 ThaliTest[1028:1138243] multipeer session: reset timer
2015-12-14 16:24:10.424 ThaliTest[1028:1138243] multipeer session: stop timer
,2015-12-14 16:24:10.425 ThaliTest[1028:1138243] multipeer session: start timer: 0x14ec3050
,2015-12-14 16:24:10.426 ThaliTest[1028:1138243] server session: connect
,2015-12-14 16:24:10.426 ThaliTest[1028:1138243] server session: stateChange:0->1 Apple-Iphone6-1_PT9718
,2015-12-14 16:24:10.433 ThaliTest[1028:1138243] server: accepting invitation Apple-Iphone6-1_PT9718
,2015-12-14 16:24:10.471 ThaliTest[1028:1138243] client: found peer: Apple-Iphone6-1_PT9718.G9NStw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9718.G9NStw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT9718.G9NStw==
2015-12-14T15:24:10.477Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT9718.G9NStw==
2015-12-14T15:24:10.478Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9718.G9NStw==
20,15-12-14T15:24:10.478Z SendDataConnector.js: do connect now
2015-12-14 16:24:10.479 ThaliTest[1028:1138507] jxcore: connect Apple-Iphone6-1_PT9718.G9NStw==
2015-12-14 16:24:10.480 ThaliTest[1028:1138507] client session: connect
2015-12-14 16:24:10.480 T,haliTest[1028:1138507] client session: stateChange:0->1 Apple-Iphone6-1_PT9718.G9NStw==
,2015-12-14 16:24:10.506 ThaliTest[1028:1138243] client: found peer: Apple-Iphone5-1_PT949.UkLT5Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT949.UkLT5Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
,2015-12-14 16:24:10.969 ThaliTest[1028:1138243] multipeer session: reset timer
2015-12-14 16:24:10.969 ThaliTest[1028:1138243] multipeer session: stop timer
2015-12-14 16:24:10.969 ThaliTest[1028:1138243] multipeer session: start timer: 0x14ec3050
2015-12-14 16:24:10.969 ThaliTest[1028:1138243] server session: connect
2015-12-14 16:24:10.969 ThaliTest[1028:1138243] server session: stateChange:0->1 Apple-Iphone5-1_PT949
,2015-12-14 16:24:10.972 ThaliTest[1028:1138243] server: accepting invitation Apple-Iphone5-1_PT949
,2015-12-14 16:24:13.462 ThaliTest[1028:1138243] client: found peer: Apple-Iphone5s-1_PT3702.8+Ivtg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3702.8+Ivtg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 16:24:13.588 ThaliTest[1028:1139233] server session: connected
2015-12-14 16:24:13.589 ThaliTest[1028:1139233] server session: stateChange:1->2 Apple-Iphone6-1_PT9718
,2015-12-14T15:24:13.600Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14 16:24:13.602 ThaliTest[1028:1138243] server relay: connected (to port: 57197)
,2015-12-14 16:24:13.726 ThaliTest[1028:1139233] server session: connected
2015-12-14 16:24:13.726 ThaliTest[1028:1139233] server session: stateChange:1->2 Apple-Iphone5-1_PT949
,2015-12-14 16:24:13.746 ThaliTest[1028:1138243] server relay: connected (to port: 57197)
,2015-12-14T15:24:13.754Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14 16:24:13.848 ThaliTest[1028:1139233] client session: connected
2015-12-14 16:24:13.848 ThaliTest[1028:1139233] client session: stateChange:1->2 Apple-Iphone6-1_PT9718.G9NStw==
,2015-12-14 16:24:13.852 ThaliTest[1028:1139233] client session: fireConnectCallback: Apple-Iphone6-1_PT9718.G9NStw==
2015-12-14 16:24:13.853 ThaliTest[1028:1139233] jxcore: connect: success
,2015-12-14T15:24:13.855Z SendDataConnector.js: CLIENT connected to 57202, error: null
,2015-12-14T15:24:13.855Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 16:24:13.858 ThaliTest[1028:1138243] client: relay established
2015-12-14 16:24:13.858 ThaliTest[1028:1138243] client: new accepted socket: 0x16f42b50
,2015-12-14T15:24:13.874Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T15:24:14.143Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14T15:24:14.245Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-14 16:24:14.306 ThaliTest[1028:1139223] server session: not connected Apple-Iphone6-1_PT9718
,2015-12-14T15:24:14.307Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T15:24:14.307Z SendDataConnector.js: got all data for this round
,2015-12-14T15:24:14.308Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T15:24:14.308Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 16:24:14.309 ThaliTest[1028:1138507] jxcore: disconnect
,2015-12-14 16:24:14.310 ThaliTest[1028:1138507] client session: disconnectFromPeer: Apple-Iphone6-1_PT9718.G9NStw==
2015-12-14 16:24:14.310 ThaliTest[1028:1138507] client session: disconnect
,2015-12-14 16:24:14.310 ThaliTest[1028:1138507] client session: stateChange:2->0 Apple-Iphone6-1_PT9718.G9NStw==
,2015-12-14 16:24:14.315 ThaliTest[1028:1138507] jxcore: disconnect: success
,2015-12-14T15:24:14.316Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9718.G9NStw==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT949.UkLT5Q==
,2015-12-14T15:24:14.319Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT949.UkLT5Q==
,2015-12-14T15:24:14.319Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT949.UkLT5Q==
,2015-12-14T15:24:14.319Z SendDataConnector.js: do connect now
,2015-12-14 16:24:14.319 ThaliTest[1028:1138507] jxcore: connect Apple-Iphone5-1_PT949.UkLT5Q==
,2015-12-14 16:24:14.319 ThaliTest[1028:1138507] client session: connect
,2015-12-14 16:24:14.320 ThaliTest[1028:1138507] client session: stateChange:0->1 Apple-Iphone5-1_PT949.UkLT5Q==
,2015-12-14T15:24:14.435Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-14T15:24:14.449Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-14T15:24:14.498Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-14T15:24:14.512Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 16:24:14.631 ThaliTest[1028:1139223] server session: not connected Apple-Iphone5-1_PT949
,2015-12-14 16:24:17.708 ThaliTest[1028:1139223] client session: connected
2015-12-14 16:24:17.708 ThaliTest[1028:1139223] client session: stateChange:1->2 Apple-Iphone5-1_PT949.UkLT5Q==
,2015-12-14 16:24:17.712 ThaliTest[1028:1139223] client session: fireConnectCallback: Apple-Iphone5-1_PT949.UkLT5Q==
2015-12-14 16:24:17.713 ThaliTest[1028:1139223] jxcore: connect: success
,2015-12-14T15:24:17.714Z SendDataConnector.js: CLIENT connected to 57205, error: null
,2015-12-14T15:24:17.715Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 16:24:17.719 ThaliTest[1028:1138243] client: relay established
2015-12-14 16:24:17.719 ThaliTest[1028:1138243] client: new accepted socket: 0x16eb4aa0
,2015-12-14T15:24:17.732Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T15:24:18.171Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-14T15:24:18.196Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-14T15:24:18.209Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T15:24:18.209Z SendDataConnector.js: got all data for this round
,2015-12-14T15:24:18.210Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T15:24:18.210Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 16:24:18.211 ThaliTest[1028:1138507] jxcore: disconnect
,2015-12-14 16:24:18.211 ThaliTest[1028:1138507] client session: disconnectFromPeer: Apple-Iphone5-1_PT949.UkLT5Q==
,2015-12-14 16:24:18.211 ThaliTest[1028:1138507] client session: disconnect
2015-12-14 16:24:18.211 ThaliTest[1028:1138507] client session: stateChange:2->0 Apple-Iphone5-1_PT949.UkLT5Q==
,2015-12-14 16:24:18.272 ThaliTest[1028:1138507] jxcore: disconnect: success
,2015-12-14T15:24:18.273Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT949.UkLT5Q==
---- round done--------
,device[3]: Apple-Iphone5s-1_PT3702.8+Ivtg==
,2015-12-14T15:24:18.274Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT3702.8+Ivtg==
,2015-12-14T15:24:18.274Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT3702.8+Ivtg==
2015-12-14T15:24:18.274Z SendDataConnector.js: do connect now
,2015-12-14 16:24:18.274 ThaliTest[1028:1138507] jxcore: connect Apple-Iphone5s-1_PT3702.8+Ivtg==
,2015-12-14 16:24:18.275 ThaliTest[1028:1138507] client session: connect
,2015-12-14 16:24:18.275 ThaliTest[1028:1138507] client session: stateChange:0->1 Apple-Iphone5s-1_PT3702.8+Ivtg==
,2015-12-14 16:24:19.682 ThaliTest[1028:1138243] multipeer session: reset timer
2015-12-14 16:24:19.683 ThaliTest[1028:1138243] multipeer session: stop timer
2015-12-14 16:24:19.683 ThaliTest[1028:1138243] multipeer session: start timer: 0x14ec3050
,2015-12-14 16:24:19.683 ThaliTest[1028:1138243] server session: connect
2015-12-14 16:24:19.684 ThaliTest[1028:1138243] server session: stateChange:0->1 Apple-Iphone5s-1_PT3702
,2015-12-14 16:24:19.690 ThaliTest[1028:1138243] server: accepting invitation Apple-Iphone5s-1_PT3702
,2015-12-14 16:24:21.906 ThaliTest[1028:1139234] client session: connected
2015-12-14 16:24:21.907 ThaliTest[1028:1139234] client session: stateChange:1->2 Apple-Iphone5s-1_PT3702.8+Ivtg==
,2015-12-14 16:24:21.910 ThaliTest[1028:1139234] client session: fireConnectCallback: Apple-Iphone5s-1_PT3702.8+Ivtg==
,2015-12-14 16:24:21.910 ThaliTest[1028:1139234] jxcore: connect: success
,2015-12-14T15:24:21.912Z SendDataConnector.js: CLIENT connected to 57208, error: null
2015-12-14T15:24:21.912Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 16:24:21.914 ThaliTest[1028:1138243] client: relay established
,2015-12-14 16:24:21.915 ThaliTest[1028:1138243] client: new accepted socket: 0x16f378d0
,2015-12-14T15:24:21.928Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T15:24:22.300Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-14T15:24:22.433Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-14T15:24:22.497Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T15:24:22.497Z SendDataConnector.js: got all data for this round
,2015-12-14T15:24:22.497Z SendDataConnector.js: CLIENT Stop now
2015-12-14T15:24:22.498Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-14 16:24:22.498 ThaliTest[1028:1138507] jxcore: disconnect
2015-12-14 16:24:22.498 ThaliTest[1028:1138507] cli,ent session: disconnectFromPeer: Apple-Iphone5s-1_PT3702.8+Ivtg==
2015-12-14 16:24:22.498 ThaliTest[1028:1138507] client session: disconnect
2015-12-14 16:24:22.498 ThaliTest[1028:1138507] client session: stateChange:2->0 Apple-Iphone5s-1_PT3702.8+Ivtg==
,2015-12-14 16:24:22.539 ThaliTest[1028:1139283] server session: connected
2015-12-14 16:24:22.539 ThaliTest[1028:1139283] server session: stateChange:1->2 Apple-Iphone5s-1_PT3702
,2015-12-14 16:24:22.555 ThaliTest[1028:1138243] server relay: connected (to port: 57197)
,2015-12-14 16:24:22.559 ThaliTest[1028:1138507] jxcore: disconnect: success
,2015-12-14T15:24:22.560Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT3702.8+Ivtg==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT6360","time":13384,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT9718.G9NStw==","time":3830,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT949.UkLT5Q==","time":3891,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT3702.8+Ivtg==","time":4223,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 4223 ms, 99% : 4223 ms, 95 : 4223 ms, 90% : 4223 ms.
,Result count 3, range 3830 ms to  4223 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-14T15:24:22.567Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T15:24:22.567Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14T15:24:22.582Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T15:24:22.888Z SendDataTCPServer.js: TCP/IP server has received 12856 bytes of data
,2015-12-14T15:24:22.903Z SendDataTCPServer.js: TCP/IP server has received 54466 bytes of data
,2015-12-14T15:24:22.919Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-14T15:24:22.932Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-14T15:24:22.945Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-14T15:24:22.962Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 16:24:23.092 ThaliTest[1028:1139233] server session: not connected Apple-Iphone5s-1_PT3702
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
,stop current!
,testSendData stopped
,2015-12-14 16:24:24.752 ThaliTest[1028:1138507] jxcore: stopBroadcasting
,2015-12-14 16:24:24.753 ThaliTest[1028:1138507] THEMultipeerSession stopping peer
2015-12-14 16:24:24.754 ThaliTest[1028:1138507] multipeer session: stop timer
,2015-12-14 16:24:24.754 ThaliTest[1028:1138507] server session: disconnect
2015-12-14 16:24:24.755 ThaliTest[1028:1138507] server session: stateChange:2->0 Apple-Iphone5-1_PT949
,2015-12-14 16:24:24.833 ThaliTest[1028:1138507] server session: disconnect
,2015-12-14 16:24:24.835 ThaliTest[1028:1138507] server session: stateChange:2->0 Apple-Iphone5s-1_PT3702
,2015-12-14 16:24:25.733 ThaliTest[1028:1138507] server session: disconnect
2015-12-14 16:24:25.734 ThaliTest[1028:1138507] server session: stateChange:2->0 Apple-Iphone6-1_PT9718
,2015-12-14 16:24:25.738 ThaliTest[1028:1138507] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-14T15:24:25.756Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T15:24:25.757Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T15:24:25.759Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T15:24:25.760Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT9718.G9NStw==\",\"time\":3830,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone5-1_PT949.UkLT5Q==\",\"time\":3891,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-Iphone5s-1_PT3702.8+Ivtg==\",\"time\":4223,\"result\":\"OK\",\"connections\":1,,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
