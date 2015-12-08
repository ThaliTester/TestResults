#### Test 52971095c7b67a5_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52971095c7b67a5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/49AF1184-17D6-4E16-88E6-2D86ABC1DB23/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/49AF1184-17D6-4E16-88E6-2D86ABC1DB23/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52971095c7b67a5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52971095c7b67a5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CAFD139C-9462-4218-B421-55E54D8561BE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50644"
,(lldb)     command script import "/tmp/49AF1184-17D6-4E16-88E6-2D86ABC1DB23/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-08 13:06:27.752 ThaliTest[460:268959] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8AD293F0-9C8B-4076-A380-1E92B678D5D8/Library/Cookies/Cookies.binarycookies
,2015-12-08 13:06:28.181 ThaliTest[460:268959] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-08 13:06:28.183 ThaliTest[460:268959] Multi-tasking -> Device: YES, App: YES
,2015-12-08 13:06:28.194 ThaliTest[460:268959] Unlimited access to network resources
,2015-12-08 13:06:28.207 ThaliTest[460:268959] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-08 13:06:37.128 ThaliTest[460:268959] Resetting plugins due to page load.
,2015-12-08 13:06:40.327 ThaliTest[460:268959] Finished load of: file:///var/mobile/Containers/Bundle/Application/CAFD139C-9462-4218-B421-55E54D8561BE/ThaliTest.app/www/index.html
,2015-12-08 13:06:40.510 ThaliTest[460:268959] JXcore Cordova plugin initializing
,2015-12-08 13:06:40.511 ThaliTest[460:269181] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone6-1_PT4714
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 51184
,2015-12-08 13:13:06.455 ThaliTest[460:269181] jxcore: startBroadcasting
,2015-12-08 13:13:06.472 ThaliTest[460:269181] server: starting Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:13:06.474 ThaliTest[460:269181] multipeer session: start timer: 0x17f72390
,2015-12-08 13:13:06.476 ThaliTest[460:269181] THEMultipeerSession initialized peer Apple-Iphone6-1_PT4714
,2015-12-08 13:13:06.477 ThaliTest[460:269181] jxcore: startBroadcasting: success
,StartBroadcasting started ok
2015-12-08T12:13:06.482Z SendDataTCPServer.js: TCP/IP server is bound to port: 51184
,2015-12-08 13:13:08.423 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:13:08.424 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s,-1_PT8639.zsASLQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
device[1]: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08T12:13:08.429Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8639.zsASLQ==
2015-,12-08T12:13:08.430Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08T12:13:08.430Z SendDataConnector.js: do connect now
2015-12-08 13:13:08.431 ThaliTest[460:269181] jxcore: connect Apple-Iphone5s-1_PT8639.zsAS,LQ==
2015-12-08 13:13:08.431 ThaliTest[460:269181] client session: connect
2015-12-08 13:13:08.432 ThaliTest[460:269181] client session: stateChange:0->1 Apple-Iphone5s-1_PT8639.zsASLQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT785.mqQzsA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-08 13:13:10.059 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT3979.Fg9L1g==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-08 13:13:12.427 ThaliTest[460:269795] client session: connected
2015-12-08 13:13:12.427 ThaliTest[460:269795] client session: stateChange:1->2 Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:13:12.438 ThaliTest[460:269795] client session: fireConnectCallback: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:13:12.438 ThaliTest[460:269795] jxcore: connect: success
,2015-12-08T12:13:12.441Z SendDataConnector.js: CLIENT connected to 51187, error: null
2015-12-08T12:13:12.442Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 13:13:12.448 ThaliTest[460:268959] client: relay established
2015-12-08 13:13:12.450 ThaliTest[460:268959] client: new accepted socket: 0x17c5a370
,2015-12-08T12:13:12.461Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T12:13:13.145Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-08T12:13:13.161Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-08T12:13:13.162Z SendDataConnector.js: got all data for this round
,2015-12-08T12:13:13.164Z SendDataConnector.js: CLIENT Stop now
2015-12-08T12:13:13.165Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 13:13:13.167 ThaliTest[460:269181] jxcore: disconnect
2015-12-08 13:13:13.168 ThaliTest[460:269181] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:13:13.168 ThaliTest[460:269181] client session: disconnect
,2015-12-08 13:13:13.169 ThaliTest[460:269181] client session: stateChange:2->0 Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:13:13.188 ThaliTest[460:269181] jxcore: disconnect: success
,2015-12-08T12:13:13.190Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8639.zsASLQ==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08T12:13:13.217Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08T12:13:13.220Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08T12:13:13.221Z SendDataConnector.js: do connect now
,2015-12-08 13:13:13.222 ThaliTest[460:269181] jxcore: connect Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:13:13.224 ThaliTest[460:269181] client session: connect
,2015-12-08 13:13:13.226 ThaliTest[460:269181] client session: stateChange:0->1 Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:13:13.345 ThaliTest[460:268959] multipeer session: reset timer
2015-12-08 13:13:13.345 ThaliTest[460:268959] multipeer session: stop timer
2015-12-08 13:13:13.345 ThaliTest[460:268959] multipeer session: start timer: 0x17f72390
2015-12-08 13:13:13.346 ThaliTest[460:268959] server session: connect
2015-12-08 13:13:13.346 ThaliTest[460:268959] server session: stateChange:0->1 Apple-Iphone5s-1_PT8639
,2015-12-08 13:13:13.356 ThaliTest[460:268959] server: accepting invitation Apple-Iphone5s-1_PT8639
,2015-12-08 13:13:15.840 ThaliTest[460:268959] multipeer session: reset timer
2015-12-08 13:13:15.841 ThaliTest[460:268959] multipeer session: stop timer
2015-12-08 13:13:15.841 ThaliTest[460:268959] multipeer session: start timer: 0x17f72390
2015-12-08 ,13:13:15.841 ThaliTest[460:268959] server session: connect
2015-12-08 13:13:15.841 ThaliTest[460:268959] server session: stateChange:0->1 Apple-Iphone5-1_PT785
,2015-12-08 13:13:15.854 ThaliTest[460:268959] server: accepting invitation Apple-Iphone5-1_PT785
,2015-12-08 13:13:16.559 ThaliTest[460:269794] server session: connected
2015-12-08 13:13:16.559 ThaliTest[460:269794] server session: stateChange:1->2 Apple-Iphone5s-1_PT8639
,2015-12-08 13:13:18.459 ThaliTest[460:269796] client session: connected
2015-12-08 13:13:18.460 ThaliTest[460:269796] client session: stateChange:1->2 Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:13:18.466 ThaliTest[460:269796] client session: fireConnectCallback: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:13:18.467 ThaliTest[460:269796] jxcore: connect: success
2015-12-08T12:13:18.468Z SendDataConnector.js: CLIENT connected to 51190, error: null
2015-12-08T12:13:18.468Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 13:13:18.472 ThaliTest[460:268959] client: relay established
2015-12-08 13:13:18.473 ThaliTest[460:268959] client: new accepted socket: 0x17c47820
,2015-12-08T12:13:18.485Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T12:13:19.181Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-08 13:13:19.439 ThaliTest[460:268959] server relay: connected (to port: 51184)
,2015-12-08T12:13:19.447Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08T12:13:19.450Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-08T12:13:19.450Z SendDataConnector.js: got all data for this round
,2015-12-08T12:13:19.452Z SendDataConnector.js: CLIENT Stop now
2015-12-08T12:13:19.452Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 13:13:19.454 ThaliTest[460:269181] jxcore: disconnect
2015-12-08 13:13:19.454 ThaliTest[460:269181] client session: disconnectFromPeer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:13:19.455 ThaliTest[460:269181] client session: disconnect
2015-12-08 13:13:19.455 ThaliTest[460:269181] client session: stateChange:2->0 Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:13:19.591 ThaliTest[460:269181] jxcore: disconnect: success
,2015-12-08T12:13:19.593Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT785.mqQzsA==
,---- round done--------
,device[3]: Apple-IpadAir2-1_PT3979.Fg9L1g==
,2015-12-08T12:13:19.597Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT3979.Fg9L1g==
,2015-12-08T12:13:19.597Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT3979.Fg9L1g==
,2015-12-08T12:13:19.598Z SendDataConnector.js: do connect now
,2015-12-08 13:13:19.599 ThaliTest[460:269181] jxcore: connect Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:13:19.599 ThaliTest[460:269181] client session: connect
2015-12-08 13:13:19.600 ThaliTest[460:269181] client session: stateChange:0->1 Apple-Ipad,Air2-1_PT3979.Fg9L1g==
,2015-12-08T12:13:19.626Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-08T12:13:19.642Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 13:13:19.726 ThaliTest[460:269796] server session: connected
2015-12-08 13:13:19.727 ThaliTest[460:269796] server session: stateChange:1->2 Apple-Iphone5-1_PT785
,2015-12-08 13:13:19.989 ThaliTest[460:268959] server relay: connected (to port: 51184)
,2015-12-08T12:13:19.998Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08 13:13:20.025 ThaliTest[460:269794] server session: not connected Apple-Iphone5s-1_PT8639
,2015-12-08T12:13:20.270Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-08T12:13:20.511Z SendDataTCPServer.js: TCP/IP server has received 35952 bytes of data
,2015-12-08T12:13:20.529Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-08T12:13:20.545Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-08T12:13:20.559Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-08T12:13:20.574Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 13:13:20.661 ThaliTest[460:269794] server session: not connected Apple-Iphone5-1_PT785
,2015-12-08 13:13:23.882 ThaliTest[460:269804] client session: connected
2015-12-08 13:13:23.884 ThaliTest[460:269804] client session: stateChange:1->2 Apple-IpadAir2-1_PT3979.Fg9L1g==
,2015-12-08 13:13:24.138 ThaliTest[460:269805] client session: fireConnectCallback: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:13:24.138 ThaliTest[460:269805] jxcore: connect: success
2015-12-08T12:13:24.140Z SendDataConnector.js: CLIENT connected to ,51195, error: null
2015-12-08T12:13:24.140Z SendDataConnector.js: CLIENT starting client 
2015-12-08 13:13:24.144 ThaliTest[460:268959] client: relay established
2015-12-08 13:13:24.144 ThaliTest[460:268959] client: new accepted socket: 0x17f752c0
,2015-12-08T12:13:24.156Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T12:13:24.480Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-08T12:13:24.604Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-08T12:13:24.617Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-08T12:13:24.617Z SendDataConnector.js: got all data for this round
,2015-12-08T12:13:24.618Z SendDataConnector.js: CLIENT Stop now
2015-12-08T12:13:24.618Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 13:13:24.618 ThaliTest[460:269181] jxcore: disconnect
2015-12-08 13:13:24.618 ThaliTest[460:269181] client session: disconnectFromPeer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:13:24.619 ThaliTest[460:269181] client session: disconnect
2015-12-08 13:13:24.619 ThaliTest[460:269181] client session: stateChange:2->0 Apple-IpadAir2-1_PT3979.Fg9L1g==
,2015-12-08 13:13:24.624 ThaliTest[460:269181] jxcore: disconnect: success
2015-12-08T12:13:24.624Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT3979.Fg9L1g==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-Iphone6-1_PT4714","time":18187,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT8639.zsASLQ==","time":4733,"result":"OK","connections":1,"doneR,ounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT785.mqQzsA==","time":6231,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT3979.Fg9L1g==","time":5020,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
sendList : 100% : 6231 ms, 99% : 6231 ms, 95 : 6231 ms, 90% : 6231 ms.
,Result count 3, range 4733 ms to  6231 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-12-08T12:13:24.630Z SendDataConnector.js: CLIENT Stop now
2015-12-08T12:13:24.630Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 13:13:45.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:13:45.883 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,2015-12-08 13:13:45.894 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:13:45.896 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:14:15.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:14:15.882 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,2015-12-08 13:14:15.890 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:14:23.465 ThaliTest[460:268959] client: lost peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:14:23.465 ThaliTest[460:268959] client session: onPeerLost: Apple-Iphone5-1_PT785.mqQzsA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iph,one5-1_PT785.mqQzsA==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:14:45.842 ThaliTest[460:268959] multipeer session: restart
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
,2015-12-08 13:15:15.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:15:15.880 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:15:15.883 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:15:15.883 ThaliTest[460:268959] client: foun,d peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT785.mqQzsA==","peerName":"(null)","peerAvailable":true}]
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
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:15:45.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:15:45.884 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:15:45.884 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:15:45.884 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
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
,2015-12-08 13:16:15.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:16:15.882 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:16:15.882 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:16:21.673 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:16:45.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:16:45.881 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:16:45.882 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:16:45.882 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
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
,2015-12-08 13:17:15.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:17:15.883 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:17:15.883 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:17:15.884 ThaliTest[460:268959] client: fo,und peer: Apple-Iphone5-1_PT785.mqQzsA==
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
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:17:45.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:17:45.882 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:17:45.882 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:17:45.884 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:18:15.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:18:15.883 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:18:15.884 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:18:15.886 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:18:45.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:18:45.880 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:18:45.884 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:18:45.884 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
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
,2015-12-08 13:19:15.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:19:15.881 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:19:15.882 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:19:15.883 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:19:45.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:19:45.883 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:19:45.884 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:19:45.888 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:20:15.842 ThaliTest[460:268959] multipeer session: restart
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
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:20:45.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:20:45.881 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:20:45.882 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:20:45.883 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:21:15.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:21:15.881 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:21:15.884 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:21:15.884 ThaliTest[460:268959] client: foun,d peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:21:45.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:21:45.881 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:21:45.881 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:21:45.881 ThaliTest[460:268959] client: fo,und peer: Apple-Iphone5-1_PT785.mqQzsA==
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
,2015-12-08 13:22:15.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:22:15.884 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:22:15.884 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:22:15.892 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:22:45.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:22:45.882 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:22:45.882 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:22:45.884 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:23:15.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:23:15.886 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:23:15.886 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:23:15.888 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:23:45.842 ThaliTest[460:268959] multipeer session: restart
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
,2015-12-08 13:24:15.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:24:15.881 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:24:15.882 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:24:16.558 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:24:45.842 ThaliTest[460:268959] multipeer session: restart
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
,2015-12-08 13:25:15.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:25:15.880 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:25:15.881 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:25:15.881 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
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
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:25:45.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:25:45.889 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:25:45.891 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:25:45.892 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:26:15.842 ThaliTest[460:268959] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 13:26:45.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:26:45.886 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:26:45.886 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:26:45.886 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:27:15.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:27:15.879 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:27:15.880 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:27:15.882 ThaliTest[460:268959] client: foun,d peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-08 13:27:45.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:27:45.879 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:27:45.880 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:27:45.880 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:28:15.842 ThaliTest[460:268959] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 13:28:45.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:28:45.880 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:28:45.880 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:28:45.885 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:29:00.758 ThaliTest[460:268959] client: lost peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:29:00.759 ThaliTest[460:268959] client session: onPeerLost: Apple-IpadAir2-1_PT3979.Fg9L1g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT3979.Fg9L1g==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:29:05.432 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT3979.Fg9L1g==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:29:15.842 ThaliTest[460:268959] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 13:29:45.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:29:45.879 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:29:45.880 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:29:45.880 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:30:15.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:30:15.879 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:30:15.879 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:30:15.879 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-08 13:30:45.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:30:45.880 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:30:45.880 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:30:46.666 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:31:15.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:31:15.880 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:31:15.880 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:31:16.029 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 13:31:45.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:31:45.878 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:31:45.879 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:31:45.881 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:32:15.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:32:15.882 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:32:15.883 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:32:15.884 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 13:32:45.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:32:45.878 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:32:45.879 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:32:46.208 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:33:15.842 ThaliTest[460:268959] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-08 13:33:45.842 ThaliTest[460:268959] multipeer session: restart
,2015-12-08 13:33:45.876 ThaliTest[460:268959] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:33:45.877 ThaliTest[460:268959] client: found peer: Apple-Iphone5s-1_PT8639.zsASLQ==
2015-12-08 13:33:45.877 ThaliTest[460:268959] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server

```
