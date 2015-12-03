#### Test 52383621712b264_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52383621712b264/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/7E2C8E4B-543E-41AD-B2FE-8BA0CF4B2688/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/7E2C8E4B-543E-41AD-B2FE-8BA0CF4B2688/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52383621712b264/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52383621712b264/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F5C14C66-D626-4F92-8663-722B9A8996BA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60521"
,(lldb)     command script import "/tmp/7E2C8E4B-543E-41AD-B2FE-8BA0CF4B2688/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 15:38:40.365 ThaliTest[1908:2992968] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E130771D-91EB-45AC-9347-A892D581DC82/Library/Cookies/Cookies.binarycookies
,2015-12-03 15:38:40.650 ThaliTest[1908:2992968] Apache Cordova native platform version 3.9.2 is starting.
2015-12-03 15:38:40.651 ThaliTest[1908:2992968] Multi-tasking -> Device: YES, App: YES
,2015-12-03 15:38:40.657 ThaliTest[1908:2992968] Unlimited access to network resources
,2015-12-03 15:38:40.663 ThaliTest[1908:2992968] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 15:38:44.846 ThaliTest[1908:2992968] Resetting plugins due to page load.
,2015-12-03 15:38:46.121 ThaliTest[1908:2992968] Finished load of: file:///var/mobile/Containers/Bundle/Application/F5C14C66-D626-4F92-8663-722B9A8996BA/ThaliTest.app/www/index.html
,2015-12-03 15:38:46.266 ThaliTest[1908:2992968] JXcore Cordova plugin initializing
,2015-12-03 15:38:46.267 ThaliTest[1908:2993141] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Radios toggled
,my name is : Apple-IpadAir2-1_PT6724
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
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 50949
,2015-12-03 15:45:49.037 ThaliTest[1908:2993141] jxcore: startBroadcasting
,2015-12-03 15:45:49.044 ThaliTest[1908:2993141] server: starting Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03 15:45:49.044 ThaliTest[1908:2993141] multipeer session: start timer: 0x1805c070
2015-12-03 15:45:49.044 ThaliTest[1908:2993141] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT6724
2015-12-03 15:45:49.044 ThaliTest[1908:2993141] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-03T14:45:49.045Z SendDataTCPServer.js: TCP/IP server is bound to port: 50949
,2015-12-03 15:45:49.624 ThaliTest[1908:2992968] client: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1068.V8ys1g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03T14:45:49.628Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03T14:45:49.628Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03T14:45:49.628Z SendDataConnector.js: do connect now
,2015-12-03 15:45:49.628 ThaliTest[1908:2993141] jxcore: connect Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:45:49.629 ThaliTest[1908:2993141] client session: connect
2015-12-03 15:45:49.629 ThaliTest[1908:2993141] client session: stateChange:0->1 Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:45:50.265 ThaliTest[1908:2992968] client: found peer: Apple-Iphone5-1_PT4165.Uz5DSQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4165.Uz5DSQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 15:45:52.390 ThaliTest[1908:2993885] client session: connected
2015-12-03 15:45:52.390 ThaliTest[1908:2993885] client session: stateChange:1->2 Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:45:52.792 ThaliTest[1908:2992968] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT2374.Xv/DEA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 15:45:53.151 ThaliTest[1908:2993889] client session: fireConnectCallback: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:45:53.151 ThaliTest[1908:2993889] jxcore: connect: success
2015-12-03T14:45:53.152Z SendDataConnector.js: CLIENT connected to 50952, error: null
2015-12-03T14:45:53.152Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:45:53.153 ThaliTest[1908:2992968] client: relay established
2015-12-03 15:45:53.153 ThaliTest[1908:2992968] client: new accepted socket: 0x18062890
,2015-12-03T14:45:53.166Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T14:45:53.451Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-03T14:45:53.464Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-03T14:45:53.465Z SendDataConnector.js: got all data for this round
,2015-12-03T14:45:53.466Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:45:53.467Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 15:45:53.467 ThaliTest[1908:2993141] jxcore: disconnect
2015-12-03 15:45:53.468 ThaliTest[1908:2993141] client session: disconnectFromPeer: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:45:53.468 ThaliTest[1908:2993141] client session: disconnect
2015-12-03 15:45:53.468 ThaliTest[1908:2993141] client session: stateChange:2->0 Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:45:53.472 ThaliTest[1908:2993141] jxcore: disconnect: success
2015-12-03T14:45:53.472Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1068.V8ys1g==
---- round done--------
device[2]: Apple-Iphone5-1_PT4165.U,z5DSQ==
2015-12-03T14:45:53.473Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT4165.Uz5DSQ==
2015-12-03T14:45:53.473Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT4165.Uz5DSQ==
2015-12-03T14:45:53.473Z SendDataConn,ector.js: do connect now
,2015-12-03 15:45:53.474 ThaliTest[1908:2993141] jxcore: connect Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03 15:45:53.475 ThaliTest[1908:2993141] client session: connect
2015-12-03 15:45:53.475 ThaliTest[1908:2993141] client session: stateChange:0->1 Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03 15:45:53.792 ThaliTest[1908:2992968] multipeer session: reset timer
2015-12-03 15:45:53.792 ThaliTest[1908:2992968] multipeer session: stop timer
2015-12-03 15:45:53.792 ThaliTest[1908:2992968] multipeer session: start timer: 0x1805c070
2015-,12-03 15:45:53.792 ThaliTest[1908:2992968] server session: connect
2015-12-03 15:45:53.792 ThaliTest[1908:2992968] server session: stateChange:0->1 Apple-Iphone5-1_PT4165
,2015-12-03 15:45:53.794 ThaliTest[1908:2992968] server: accepting invitation Apple-Iphone5-1_PT4165
,2015-12-03 15:45:55.826 ThaliTest[1908:2992968] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 15:45:56.426 ThaliTest[1908:2993893] client session: connected
2015-12-03 15:45:56.427 ThaliTest[1908:2993893] client session: stateChange:1->2 Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03 15:45:56.485 ThaliTest[1908:2993885] client session: fireConnectCallback: Apple-Iphone5-1_PT4165.Uz5DSQ==
2015-12-03 15:45:56.485 ThaliTest[1908:2993885] jxcore: connect: success
2015-12-03T14:45:56.485Z SendDataConnector.js: CLIENT connected to 50955, error: null
,2015-12-03T14:45:56.486Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:45:56.488 ThaliTest[1908:2993885] server session: connected
,2015-12-03 15:45:56.488 ThaliTest[1908:2992968] client: relay established
2015-12-03 15:45:56.489 ThaliTest[1908:2993885] server session: stateChange:1->2 Apple-Iphone5-1_PT4165
,2015-12-03 15:45:56.489 ThaliTest[1908:2992968] client: new accepted socket: 0x16d1b990
,2015-12-03 15:45:56.495 ThaliTest[1908:2992968] server relay: connected (to port: 50949)
,2015-12-03T14:45:56.500Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:45:56.500Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T14:45:57.074Z SendDataTCPServer.js: TCP/IP server has received 4960 bytes of data
,2015-12-03T14:45:57.087Z SendDataTCPServer.js: TCP/IP server has received 21824 bytes of data
,2015-12-03T14:45:57.408Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-03T14:45:57.408Z SendDataConnector.js: got all data for this round
,2015-12-03T14:45:57.409Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:45:57.409Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 15:45:57.409 ThaliTest[1908:2993141] jxcore: disconnect
2015-12-03 15:45:57.410 ThaliTest[1908:2993141] client session: disconnectFromPeer: Apple-Iphone5-1_PT4165.Uz5DSQ==
2015-12-03 15:45:57.410 ThaliTest[1908:2993141] client session: disconnect
2015-12-03 15:45:57.410 ThaliTest[1908:2993141] client session: stateChange:2->0 Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03 15:45:57.417 ThaliTest[1908:2993141] jxcore: disconnect: success
,2015-12-03T14:45:57.418Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT4165.Uz5DSQ==
---- round done--------
device[3]: Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03T14:45:57.420Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03T14:45:57.420Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03T14:45:57.420Z SendDataConnector.js: do connect now
,2015-12-03 15:45:57.421 ThaliTest[1908:2993141] jxcore: connect Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03 15:45:57.421 ThaliTest[1908:2993141] client session: connect
2015-12-03 15:45:57.422 ThaliTest[1908:2993141] client session: stateChange:0->1 Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03T14:45:57.439Z SendDataTCPServer.js: TCP/IP server has received 84320 bytes of data
,2015-12-03T14:45:57.502Z SendDataTCPServer.js: TCP/IP server has received 96224 bytes of data
,2015-12-03T14:45:57.527Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 15:45:57.544 ThaliTest[1908:2993930] server session: not connected Apple-Iphone5-1_PT4165
,2015-12-03 15:46:00.031 ThaliTest[1908:2993893] client session: connected
2015-12-03 15:46:00.032 ThaliTest[1908:2993893] client session: stateChange:1->2 Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:46:00.164 ThaliTest[1908:2993883] client session: fireConnectCallback: Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03 15:46:00.164 ThaliTest[1908:2993883] jxcore: connect: success
2015-12-03T14:46:00.165Z SendDataConnector.js: CLIENT connected to 50960, error: null
,2015-12-03T14:46:00.165Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:46:00.166 ThaliTest[1908:2992968] client: relay established
2015-12-03 15:46:00.167 ThaliTest[1908:2992968] client: new accepted socket: 0x14fce6f0
,2015-12-03T14:46:00.179Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T14:46:00.588Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-03T14:46:00.601Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-03T14:46:00.614Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-03T14:46:00.627Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-03T14:46:00.713Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-03T14:46:00.714Z SendDataConnector.js: got all data for this round
,2015-12-03T14:46:00.715Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:46:00.715Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 15:46:00.715 ThaliTest[1908:2993141] jxcore: disconnect
2015-12-03 15:46:00.715 ThaliTest[1908:2993141] client session: disconnectFromPeer: Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03 15:46:00.715 ThaliTest[1908:2993141] client session: disconnect
2015-12-03 15:46:00.716 ThaliTest[1908:2993141] client session: stateChange:2->0 Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:46:00.720 ThaliTest[1908:2993141] jxcore: disconnect: success
2015-12-03T14:46:00.720Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT2374.Xv/DEA==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT6724","time":11688,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT1068.V8ys1g==","time":3837,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT4165.Uz5DSQ==","time":3935,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT2374.Xv/DEA==","time":3294,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
sendList : 100% : 3935 ms, 99% : 3935 ms, 95 : 3935 ms, 90% : 3935 ms.
Result count 3, range 3294 ms to  3935 ms.
,sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-12-03T14:46:00.726Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:46:00.726Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 15:46:23.793 ThaliTest[1908:2992968] multipeer session: restart
,2015-12-03 15:46:23.806 ThaliTest[1908:2992968] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03 15:46:23.806 ThaliTest[1908:2992968] client: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:46:23.806 ThaliTest[1908:2992968] client: found peer: Apple-Iphone5-1_PT4165.Uz5DSQ==
2015-12-03 15:46:23.806 ThaliTest[1908:2992968] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:46:53.793 ThaliTest[1908:2992968] multipeer session: restart
,2015-12-03 15:46:53.806 ThaliTest[1908:2992968] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03 15:46:53.806 ThaliTest[1908:2992968] client: found peer: Apple-Iphone5-1_PT4165.Uz5DSQ==
2015-12-03 15:46:53.806 ThaliTest[1908:2992968] client: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:46:53.806 ThaliTest[1908:2992968] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:47:23.793 ThaliTest[1908:2992968] multipeer session: restart
,2015-12-03 15:47:23.805 ThaliTest[1908:2992968] client: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:47:23.805 ThaliTest[1908:2992968] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03 15:47:23.806 ThaliTest[1908:2992968] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:47:23.806 ThaliTest[1908:2992968] client: found peer: Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03 15:47:46.689 ThaliTest[1908:2992968] multipeer session: reset timer
,2015-12-03 15:47:46.689 ThaliTest[1908:2992968] multipeer session: stop timer
2015-12-03 15:47:46.689 ThaliTest[1908:2992968] multipeer session: start timer: 0x1805c070
2015-12-03 15:47:46.690 ThaliTest[1908:2992968] server session: connect
2015-12-03 15:47:46.690 ThaliTest[1908:2992968] server session: stateChange:0->1 Apple-Iphone5s-1_PT2374
,2015-12-03 15:47:46.692 ThaliTest[1908:2992968] server: accepting invitation Apple-Iphone5s-1_PT2374
,2015-12-03 15:47:49.217 ThaliTest[1908:2994173] server session: connected
2015-12-03 15:47:49.217 ThaliTest[1908:2994173] server session: stateChange:1->2 Apple-Iphone5s-1_PT2374
,2015-12-03 15:47:49.233 ThaliTest[1908:2992968] server relay: connected (to port: 50949)
,2015-12-03T14:47:49.235Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:47:49.581Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-03T14:47:49.595Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 15:47:49.618 ThaliTest[1908:2994170] server session: not connected Apple-Iphone5s-1_PT2374
,2015-12-03 15:48:16.691 ThaliTest[1908:2992968] multipeer session: restart
,2015-12-03 15:48:16.702 ThaliTest[1908:2992968] client: found peer: Apple-Iphone5-1_PT4165.Uz5DSQ==
2015-12-03 15:48:16.702 ThaliTest[1908:2992968] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:48:16.872 ThaliTest[1908:2992968] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03 15:48:16.872 ThaliTest[1908:2992968] client: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:48:27.492 ThaliTest[1908:2992968] client: lost peer: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:48:27.492 ThaliTest[1908:2992968] client session: onPeerLost: Apple-Iphone6-1_PT1068.V8ys1g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1068.V8ys1g==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 15:48:29.090 ThaliTest[1908:2992968] client: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1068.V8ys1g==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 15:48:46.691 ThaliTest[1908:2992968] multipeer session: restart
,2015-12-03 15:48:46.702 ThaliTest[1908:2992968] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03 15:48:46.703 ThaliTest[1908:2992968] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:48:46.703 ThaliTest[1908:2992968] client: found peer: Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03 15:48:46.777 ThaliTest[1908:2992968] client: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:49:16.691 ThaliTest[1908:2992968] multipeer session: restart
,2015-12-03 15:49:16.703 ThaliTest[1908:2992968] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03 15:49:16.703 ThaliTest[1908:2992968] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:49:16.704 ThaliTest[1908:2992968] client: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:49:17.333 ThaliTest[1908:2992968] client: found peer: Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03 15:49:40.359 ThaliTest[1908:2992968] client: lost peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03 15:49:40.359 ThaliTest[1908:2992968] client session: onPeerLost: Apple-Iphone5s-1_PT2374.Xv/DEA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT2374.Xv/DEA==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 15:49:46.591 ThaliTest[1908:2992968] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT2374.Xv/DEA==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 15:49:46.691 ThaliTest[1908:2992968] multipeer session: restart
,2015-12-03 15:49:46.703 ThaliTest[1908:2992968] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:49:46.703 ThaliTest[1908:2992968] client: found peer: Apple-Iphone5-1_PT4165.Uz5DSQ==
2015-12-03 15:49:46.703 ThaliTest[1908:2992968] client: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:49:46.704 ThaliTest[1908:2992968] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:49:59.122 ThaliTest[1908:2992968] multipeer session: reset timer
2015-12-03 15:49:59.122 ThaliTest[1908:2992968] multipeer session: stop timer
2015-12-03 15:49:59.123 ThaliTest[1908:2992968] multipeer session: start timer: 0x1805c070
2015-12-03 15:49:59.123 ThaliTest[1908:2992968] server session: connect
2015-12-03 15:49:59.123 ThaliTest[1908:2992968] server session: stateChange:0->1 Apple-Iphone6-1_PT1068
,2015-12-03 15:49:59.126 ThaliTest[1908:2992968] server: accepting invitation Apple-Iphone6-1_PT1068
,2015-12-03 15:50:01.375 ThaliTest[1908:2994497] server session: connected
2015-12-03 15:50:01.375 ThaliTest[1908:2994497] server session: stateChange:1->2 Apple-Iphone6-1_PT1068
,2015-12-03 15:50:01.377 ThaliTest[1908:2992968] server relay: connected (to port: 50949)
,2015-12-03T14:50:01.379Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:50:01.663Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-03T14:50:01.674Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-03T14:50:01.688Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 15:50:01.706 ThaliTest[1908:2994497] server session: not connected Apple-Iphone6-1_PT1068
,DBG, CoordinatorConnector command called
command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
,testSendData stopped
,2015-12-03 15:50:06.639 ThaliTest[1908:2993141] jxcore: stopBroadcasting
2015-12-03 15:50:06.639 ThaliTest[1908:2993141] THEMultipeerSession stopping peer
2015-12-03 15:50:06.639 ThaliTest[1908:2993141] multipeer session: stop timer
2015-12-03 15:50:06.639 ThaliTest[1908:2993141] server session: disconnect
2015-12-03 15:50:06.639 ThaliTest[1908:2993141] server session: stateChange:2->0 Apple-Iphone6-1_PT1068
,2015-12-03 15:50:06.642 ThaliTest[1908:2993141] server session: disconnect
2015-12-03 15:50:06.642 ThaliTest[1908:2993141] server session: stateChange:2->0 Apple-Iphone5-1_PT4165
,2015-12-03 15:50:06.651 ThaliTest[1908:2993141] server session: disconnect
2015-12-03 15:50:06.651 ThaliTest[1908:2993141] server session: stateChange:2->0 Apple-Iphone5s-1_PT2374
,2015-12-03 15:50:06.721 ThaliTest[1908:2993141] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-03T14:50:06.736Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03T14:50:06.737Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03T14:50:06.737Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03T14:50:06.737Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT2374.Xv/DEA==\",\"time\":3294,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone6-1_PT1068.V8ys1g==\",\"time\":3837,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-Iphone5-1_PT4165.Uz5DSQ==\",\"time\":3935,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
