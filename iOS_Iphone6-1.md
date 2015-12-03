#### Test 506502782b2305a_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502782b2305a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/7398BA76-3188-4862-A7A5-A1F9131457B5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/7398BA76-3188-4862-A7A5-A1F9131457B5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502782b2305a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502782b2305a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6D08A23E-007E-4BBB-AB13-16DBBF4FE609/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60118"
,(lldb)     command script import "/tmp/7398BA76-3188-4862-A7A5-A1F9131457B5/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 01:41:11.398 ThaliTest[2542:2144700] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BE682887-28F2-4E3D-8071-678A730B1984/Library/Cookies/Cookies.binarycookies
,2015-12-03 01:41:11.799 ThaliTest[2542:2144700] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 01:41:11.801 ThaliTest[2542:2144700] Multi-tasking -> Device: YES, App: YES
,2015-12-03 01:41:11.810 ThaliTest[2542:2144700] Unlimited access to network resources
,2015-12-03 01:41:11.817 ThaliTest[2542:2144700] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 01:41:15.574 ThaliTest[2542:2144700] Resetting plugins due to page load.
,2015-12-03 01:41:15.952 ThaliTest[2542:2144700] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/6D08A23E-007E-4BBB-AB13-16DBBF4FE609/ThaliTest.app/www/index.html
,2015-12-03 01:41:16.077 ThaliTest[2542:2144700] JXcore Cordova plugin initializing
2015-12-03 01:41:16.077 ThaliTest[2542:2144842] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,Test app app.js loaded
,CoordinatorConnector-debug: connect:undefined
Coordinator is now connected to the server!
,CoordinatorConnector-debug: start:[object Object]
,{ testName: 'testFindPeers.js',
  testData: 
   { servertimeout: 1200000,
     timeout: 1000000,
     rounds: 1,
     dataTimeout: 10000,
     dataAmount: 100000,
     conReTryTimeout: 5000,
     conReTryCount: 5,
     peerCount: 4 },
  addressList: [] }
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-03 01:42:22.588 ThaliTest[2542:2144842] jxcore: startBroadcasting
,2015-12-03 01:42:22.602 ThaliTest[2542:2144842] server: starting Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:42:22.603 ThaliTest[2542:2144842] multipeer session: start timer: 0x191a07e0
2015-12-03 01:42:22.604 ThaliTest[2542:2144842] THEMultipeerSessio,n initialized peer Apple-Iphone6-1_PT2613
,2015-12-03 01:42:22.605 ThaliTest[2542:2144842] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-03 01:42:23.046 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.8qCfew==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.8qCfew==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5s-1_PT5704.8qCfew==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,CoordinatorConnector-debug: sendData
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT2613","time":465,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5s-1_PT5704.8qCfew==","peerAvailable":true,"time":462}]}
,peersList : 100% : 462 ms, 99% : 462 ms, 95 : 462 ms, 90% : 462 ms.
,Result count 1, range 462 ms to  462 ms.
,CoordinatorConnector-debug: stop:undefined
,stop tests now !
stop current!
testFindPeers stopped
2015-12-03 01:42:23.592 ThaliTest[2542:2144842] jxcore: stopBroadcasting
,2015-12-03 01:42:23.592 ThaliTest[2542:2144842] THEMultipeerSession stopping peer
,2015-12-03 01:42:23.593 ThaliTest[2542:2144842] multipeer session: stop timer
2015-12-03 01:42:23.594 ThaliTest[2542:2144842] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,CoordinatorConnector-debug: start:[object Object]
,{ testName: 'testSendData.js',
  testData: 
   { servertimeout: 1200000,
     timeout: 1000000,
     rounds: 1,
     dataTimeout: 10000,
     dataAmount: 100000,
     conReTryTimeout: 5000,
     conReTryCount: 5,
     peerCount: 4 },
  addressList: [] }
,testSendData created [object Object], bt-address length : 0
,check server
,serverPort is 49784
,2015-12-03 01:42:24.148 ThaliTest[2542:2144842] jxcore: startBroadcasting
,2015-12-03 01:42:24.151 ThaliTest[2542:2144842] server: starting Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:42:24.152 ThaliTest[2542:2144842] multipeer session: start timer: 0x192c4a90
2015-12-03 01:42:24.153 ThaliTest[2542:2144842] THEMultipeerSessio,n initialized peer Apple-Iphone6-1_PT2613
2015-12-03 01:42:24.154 ThaliTest[2542:2144842] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-03T00:42:24.156Z SendDataTCPServer.js: TCP/IP server is bound to port: 49784
,2015-12-03 01:42:24.224 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.8qCfew==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.8qCfew==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03T00:42:24.226Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03T00:42:24.227Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03T00:42:24.227Z SendDataConnector.js: do connect now
,2015-12-03 01:42:24.227 ThaliTest[2542:2144842] jxcore: connect Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:42:24.228 ThaliTest[2542:2144842] client session: connect
,2015-12-03 01:42:24.228 ThaliTest[2542:2144842] client session: stateChange:0->1 Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:42:24.335 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8796.xJ9gmA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 01:42:24.503 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,2015-12-03 01:42:24.560 ThaliTest[2542:2144700] client: found peer: Apple-Iphone6-1_PT2613.bcJOyQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.bcJOyQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 01:42:25.841 ThaliTest[2542:2144700] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7682.INb6UQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,2015-12-03 01:42:26.372 ThaliTest[2542:2144700] client: lost peer: Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:42:26.373 ThaliTest[2542:2144700] client session: onPeerLost: Apple-Iphone6-1_PT2613.bcJOyQ==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT2613.bcJOyQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 01:42:28.371 ThaliTest[2542:2144700] client: lost peer: Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03 01:42:28.372 ThaliTest[2542:2144700] client session: onPeerLost: Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03 01:42:28.372 ThaliTest[2542:214470,0] client session: onLinkFailure: Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03 01:42:28.373 ThaliTest[2542:2144700] client session: disconnect
2015-12-03 01:42:28.373 ThaliTest[2542:2144700] client session: stateChange:1->0 Apple-Iphone5s-1_PT5704.8qCfew=,=
2015-12-03 01:42:28.374 ThaliTest[2542:2144700] client session: fireConnectCallback: Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03 01:42:28.374 ThaliTest[2542:2144700] jxcore: connect: fail: Peer disconnected
,2015-12-03T00:42:28.376Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T00:42:28.377Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-03T00:42:28.378Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.8qCfew==","peerName":"(null)","peerAvailable":false}]
,2015-12-03T00:42:33.387Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03T00:42:33.388Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:42:38.392 ThaliTest[2542:2144842] jxcore: disconnect
2015-12-03 01:42:38.393 ThaliTest[2542:2144842] jxcore: disconnect: fail
2015-12-03T00:42:38.393Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03T00:42:38.394Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT5704.8qCfew== with availability status: true
2015-12-03T00:42:38.394Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.8qCfew==
2015,-12-03T00:42:38.395Z SendDataConnector.js: do connect now
,2015-12-03 01:42:38.396 ThaliTest[2542:2144842] jxcore: connect Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03 01:42:38.397 ThaliTest[2542:2144842] client: connect: unreachable Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03 01:42:38.397 ThaliTest[2542:2144842], jxcore: connect: fail: Peer unreachable
2015-12-03T00:42:38.398Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-03T00:42:38.398Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-03T00:42:38.398Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:42:43.400Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03T00:42:43.400Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:42:48.403 ThaliTest[2542:2144842] jxcore: disconnect
2015-12-03 01:42:48.404 ThaliTest[2542:2144842] jxcore: disconnect: fail
2015-12-03T00:42:48.404Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.8qCf,ew==
2015-12-03T00:42:48.405Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT5704.8qCfew== with availability status: true
2015-12-03T00:42:48.405Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.8qCfew==,
,2015-12-03T00:42:48.405Z SendDataConnector.js: do connect now
2015-12-03 01:42:48.406 ThaliTest[2542:2144842] jxcore: connect Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:42:48.407 ThaliTest[2542:2144842] client: connect: unreachable Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03 01:42:48.408 ThaliTest[2542:2144842] jxcore: connect: fail: Peer unreachable
2015-12-03T00:42:48.409Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-03T00:42:48.409Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-03T00:42:48.409Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:42:53.412Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03T00:42:53.412Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:42:54.154 ThaliTest[2542:2144700] multipeer session: restart
,2015-12-03 01:42:54.172 ThaliTest[2542:2144700] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:42:54.172 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:42:54.176 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:42:58.422 ThaliTest[2542:2144842] jxcore: disconnect
2015-12-03 01:42:58.423 ThaliTest[2542:2144842] jxcore: disconnect: fail
2015-12-03T00:42:58.424Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.8qCf,ew==
2015-12-03T00:42:58.424Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT5704.8qCfew== with availability status: true
2015-12-03T00:42:58.425Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.8qCfew==,
,2015-12-03T00:42:58.425Z SendDataConnector.js: do connect now
,2015-12-03 01:42:58.426 ThaliTest[2542:2144842] jxcore: connect Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:42:58.427 ThaliTest[2542:2144842] client: connect: unreachable Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03 01:42:58.428 ThaliTest[2542:2144842] jxcore: connect: fail: Peer unreachable
2015-12-03T00:42:58.428Z SendDataConnector.js: CLIENT co,nnected to 0, error: Peer unreachable
2015-12-03T00:42:58.429Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-03T00:42:58.429Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:43:03.438Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03T00:43:03.439Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:43:07.378 ThaliTest[2542:2144700] client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:43:07.379 ThaliTest[2542:2144700] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 01:43:07.789 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 01:43:08.446 ThaliTest[2542:2144842] jxcore: disconnect
2015-12-03 01:43:08.447 ThaliTest[2542:2144842] jxcore: disconnect: fail
2015-12-03T00:43:08.447Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.8qCf,ew==
2015-12-03T00:43:08.448Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT5704.8qCfew== with availability status: true
,2015-12-03T00:43:08.448Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03T00:43:08.448Z SendDataConnector.js: do connect now
,2015-12-03 01:43:08.449 ThaliTest[2542:2144842] jxcore: connect Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03 01:43:08.450 ThaliTest[2542:2144842] client: connect: unreachable Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03 01:43:08.451 ThaliTest[2542:2144842], jxcore: connect: fail: Peer unreachable
2015-12-03T00:43:08.452Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-03T00:43:08.452Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,oneRoundDownNow:2
,2015-12-03T00:43:08.455Z SendDataConnector.js: CLIENT Stop now
,2015-12-03 01:43:08.455 ThaliTest[2542:2144842] jxcore: disconnect
,2015-12-03 01:43:08.456 ThaliTest[2542:2144842] jxcore: disconnect: fail
2015-12-03T00:43:08.458Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.8qCfew==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03T00:43:08.460Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03T00:43:08.461Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03T00:43:08.461Z SendDataConnector.js: do connect now
,2015-12-03 01:43:08.462 ThaliTest[2542:2144842] jxcore: connect Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:43:08.463 ThaliTest[2542:2144842] client session: connect
2015-12-03 01:43:08.464 ThaliTest[2542:2144842] client session: stateChange:0->1 Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:43:10.156 ThaliTest[2542:2144700] multipeer session: reset timer
2015-12-03 01:43:10.156 ThaliTest[2542:2144700] multipeer session: stop timer
2015-12-03 01:43:10.157 ThaliTest[2542:2144700] multipeer session: start timer: 0x192c4a90
2015-12-03 01:43:10.157 ThaliTest[2542:2144700] server session: connect
2015-12-03 01:43:10.157 ThaliTest[2542:2144700] server session: stateChange:0->1 Apple-IpadAir2-1_PT7682
,2015-12-03 01:43:10.161 ThaliTest[2542:2144700] server: accepting invitation Apple-IpadAir2-1_PT7682
,2015-12-03 01:43:10.181 ThaliTest[2542:2144700] multipeer session: reset timer
2015-12-03 01:43:10.181 ThaliTest[2542:2144700] multipeer session: stop timer
2015-12-03 01:43:10.181 ThaliTest[2542:2144700] multipeer session: start timer: 0x192c4a90
2015-,12-03 01:43:10.181 ThaliTest[2542:2144700] server session: connect
2015-12-03 01:43:10.181 ThaliTest[2542:2144700] server session: stateChange:0->1 Apple-Iphone5s-1_PT5704
,2015-12-03 01:43:10.184 ThaliTest[2542:2144700] server: accepting invitation Apple-Iphone5s-1_PT5704
,2015-12-03 01:43:12.043 ThaliTest[2542:2145105] client session: connected
2015-12-03 01:43:12.043 ThaliTest[2542:2145105] client session: stateChange:1->2 Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:43:12.079 ThaliTest[2542:2145081] client session: fireConnectCallback: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:43:12.080 ThaliTest[2542:2145081] jxcore: connect: success
2015-12-03T00:43:12.081Z SendDataConnector.js: CLIENT connected to 49789, error: null
,2015-12-03T00:43:12.081Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:43:12.085 ThaliTest[2542:2144700] client: relay established
2015-12-03 01:43:12.086 ThaliTest[2542:2144700] client: new accepted socket: 0x192daeb0
,2015-12-03T00:43:12.100Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03 01:43:12.560 ThaliTest[2542:2145105] server session: connected
2015-12-03 01:43:12.560 ThaliTest[2542:2145105] server session: stateChange:1->2 Apple-IpadAir2-1_PT7682
,2015-12-03T00:43:12.562Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-03 01:43:12.566 ThaliTest[2542:2144700] server relay: connected (to port: 49784)
,2015-12-03T00:43:12.575Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03 01:43:12.578 ThaliTest[2542:2145089] server session: connected
2015-12-03 01:43:12.579 ThaliTest[2542:2145089] server session: stateChange:1->2 Apple-Iphone5s-1_PT5704
,2015-12-03T00:43:12.586Z SendDataTCPServer.js: TCP/IP server connected
2015-12-03T00:43:12.587Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03 01:43:12.587 ThaliTest[2542:2144700] server relay: connected (to port: 49784)
,2015-12-03T00:43:12.785Z SendDataTCPServer.js: TCP/IP server has received 12714 bytes of data
,2015-12-03T00:43:12.799Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-03T00:43:12.815Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-03T00:43:12.828Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-03T00:43:12.843Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03T00:43:12.869Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-03T00:43:12.884Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-03T00:43:13.085Z SendDataTCPServer.js: TCP/IP server has received 99806 bytes of data
,2015-12-03T00:43:13.103Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 01:43:13.123 ThaliTest[2542:2145105] server session: not connected Apple-Iphone5s-1_PT5704
,2015-12-03T00:43:22.588Z SendDataConnector.js: Receiving data timeout now
2015-12-03T00:43:22.588Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:43:22.590Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:43:22.591Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:43:22.592Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:43:22.593 ThaliTest[2542:2144700] client: socket closed
2015-12-03 01:43:22.594 ThaliTest[2542:2144700] client relay: socket disconnected
2015-12-03 01:43:22.595 ThaliTest[2542:2144700] client relay: 0x192daeb0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x191b4e70 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 01:43:22.595 ThaliTest[2542:2144700] client session: socket closed: Apple-Iphone5-1_PT8796.xJ9gmA,==
2015-12-03 01:43:22.596 ThaliTest[2542:2144700] client session: onLinkFailure: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:43:22.596 ThaliTest[2542:2144700] client session: disconnect
2015-12-03 01:43:22.597 ThaliTest[2542:2144700] client session: ,stateChange:2->0 Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:43:22.599 ThaliTest[2542:2144700] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:43:22.970 ThaliTest[2542:2145080] server session: not connected Apple-IpadAir2-1_PT7682
,2015-12-03T00:43:27.595Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03T00:43:27.595Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:43:32.601 ThaliTest[2542:2144842] jxcore: disconnect
2015-12-03 01:43:32.602 ThaliTest[2542:2144842] jxcore: disconnect: fail
2015-12-03T00:43:32.603Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03T00:43:32.604Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT8796.xJ9gmA== with availability status: true
2015-12-03T00:43:32.604Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03T00:43:32.604Z SendDataConnector.js: do connect now
,2015-12-03 01:43:32.605 ThaliTest[2542:2144842] jxcore: connect Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:43:32.606 ThaliTest[2542:2144842] client session: connect
2015-12-03 01:43:32.607 ThaliTest[2542:2144842] client session: stateChange:0->1 Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:43:34.613 ThaliTest[2542:2144700] multipeer session: reset timer
2015-12-03 01:43:34.614 ThaliTest[2542:2144700] multipeer session: stop timer
2015-12-03 01:43:34.614 ThaliTest[2542:2144700] multipeer session: start timer: 0x192c4a90
2015-,12-03 01:43:34.615 ThaliTest[2542:2144700] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7682)
2015-12-03 01:43:34.615 ThaliTest[2542:2144700] server session: disconnect
2015-12-03 01:43:34.616 ThaliTest[2542:2144700] server session: state,Change:2->0 Apple-IpadAir2-1_PT7682
2015-12-03 01:43:34.619 ThaliTest[2542:2144700] server session: connect
2015-12-03 01:43:34.620 ThaliTest[2542:2144700] server session: stateChange:0->1 Apple-IpadAir2-1_PT7682
,2015-12-03T00:43:34.631Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 01:43:34.637 ThaliTest[2542:2144700] server: accepting invitation Apple-IpadAir2-1_PT7682
,2015-12-03 01:43:35.214 ThaliTest[2542:2145145] client session: connected
2015-12-03 01:43:35.215 ThaliTest[2542:2145145] client session: stateChange:1->2 Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:43:35.223 ThaliTest[2542:2145146] client session: fireConnectCallback: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:43:35.224 ThaliTest[2542:2145146] jxcore: connect: success
2015-12-03T00:43:35.225Z SendDataConnector.js: CLIENT connected ,to 49793, error: null
2015-12-03T00:43:35.225Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:43:35.229 ThaliTest[2542:2144700] client: relay established
2015-12-03 01:43:35.229 ThaliTest[2542:2144700] client: new accepted socket: 0x192e2de0
,2015-12-03T00:43:35.242Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 01:43:36.933 ThaliTest[2542:2145146] server session: connected
2015-12-03 01:43:36.934 ThaliTest[2542:2145146] server session: stateChange:1->2 Apple-IpadAir2-1_PT7682
,2015-12-03T00:43:36.942Z SendDataTCPServer.js: TCP/IP server connected
2015-12-03 01:43:36.943 ThaliTest[2542:2144700] server relay: connected (to port: 49784)
,2015-12-03T00:43:36.979Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-03T00:43:36.994Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T00:43:45.306Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:43:45.306Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:43:45.307Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:43:45.307Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:43:45.308Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:43:45.310 ThaliTest[2542:2144700] client: socket closed
2015-12-03 01:43:45.310 ThaliTest[2542:2144700] client relay: socket disconnected
2015-12-03 01:43:45.311 ThaliTest[2542:2144700] client relay: 0x192e2de0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x191b4650 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 01:43:45.311 ThaliTest[2542:2144700] client session: socket closed: Apple-Iphone5-1_PT8796.xJ9gmA,==
2015-12-03 01:43:45.312 ThaliTest[2542:2144700] client session: onLinkFailure: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:43:45.312 ThaliTest[2542:2144700] client session: disconnect
2015-12-03 01:43:45.313 ThaliTest[2542:2144700] client session: ,stateChange:2->0 Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:43:45.315 ThaliTest[2542:2144700] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:43:47.084 ThaliTest[2542:2145147] server session: not connected Apple-IpadAir2-1_PT7682
,2015-12-03T00:43:50.313Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03T00:43:50.313Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:43:55.326 ThaliTest[2542:2144842] jxcore: disconnect
2015-12-03 01:43:55.327 ThaliTest[2542:2144842] jxcore: disconnect: fail
2015-12-03T00:43:55.327Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT8796.xJ9gm,A==
2015-12-03T00:43:55.328Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT8796.xJ9gmA== with availability status: true
2015-12-03T00:43:55.328Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03T00:43:55.328Z SendDataConnector.js: do connect now
,2015-12-03 01:43:55.329 ThaliTest[2542:2144842] jxcore: connect Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:43:55.330 ThaliTest[2542:2144842] client session: connect
2015-12-03 01:43:55.331 ThaliTest[2542:2144842] client session: stateChange:0->1 Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:43:57.602 ThaliTest[2542:2145190] client session: connected
2015-12-03 01:43:57.603 ThaliTest[2542:2145190] client session: stateChange:1->2 Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:43:57.612 ThaliTest[2542:2145147] client session: fireConnectCallback: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:43:57.612 ThaliTest[2542:2145147] jxcore: connect: success
2015-12-03T00:43:57.613Z SendDataConnector.js: CLIENT connected to 49796, error: null
2015-12-03T00:43:57.614Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:43:57.617 ThaliTest[2542:2144700] client: relay established
2015-12-03 01:43:57.618 ThaliTest[2542:2144700] client: new accepted socket: 0x192e7260
,2015-12-03T00:43:57.631Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 01:43:57.930 ThaliTest[2542:2144700] multipeer session: reset timer
2015-12-03 01:43:57.930 ThaliTest[2542:2144700] multipeer session: stop timer
2015-12-03 01:43:57.930 ThaliTest[2542:2144700] multipeer session: start timer: 0x192c4a90
2015-,12-03 01:43:57.931 ThaliTest[2542:2144700] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7682)
2015-12-03 01:43:57.931 ThaliTest[2542:2144700] server session: disconnect
2015-12-03 01:43:57.931 ThaliTest[2542:2144700] server session: stateChange:2->0 Apple-IpadAir2-1_PT7682
,2015-12-03T00:43:57.940Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 01:43:57.986 ThaliTest[2542:2144700] server session: connect
2015-12-03 01:43:57.986 ThaliTest[2542:2144700] server session: stateChange:0->1 Apple-IpadAir2-1_PT7682
,2015-12-03 01:43:57.989 ThaliTest[2542:2144700] server: accepting invitation Apple-IpadAir2-1_PT7682
,2015-12-03 01:44:00.303 ThaliTest[2542:2145190] server session: connected
2015-12-03 01:44:00.303 ThaliTest[2542:2145190] server session: stateChange:1->2 Apple-IpadAir2-1_PT7682
,2015-12-03 01:44:00.305 ThaliTest[2542:2144700] server relay: connected (to port: 49784)
,2015-12-03T00:44:00.309Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:44:00.360Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T00:44:07.701Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:44:07.702Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:44:07.703Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:44:07.703Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:44:07.704Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:44:07.705 ThaliTest[2542:2144700] client: socket closed
2015-12-03 01:44:07.706 ThaliTest[2542:2144700] client relay: socket disconnected
2015-12-03 01:44:07.707 ThaliTest[2542:2144700] client relay: 0x192e7260 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x192df9b0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 01:44:07.707 ThaliTest[2542:2144700] client session: socket closed: Apple-Iphone5-1_PT8796.xJ9gmA,==
2015-12-03 01:44:07.708 ThaliTest[2542:2144700] client session: onLinkFailure: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:44:07.708 ThaliTest[2542:2144700] client session: disconnect
2015-12-03 01:44:07.709 ThaliTest[2542:2144700] client session: ,stateChange:2->0 Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:44:07.711 ThaliTest[2542:2144700] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:44:10.670 ThaliTest[2542:2145147] server session: not connected Apple-IpadAir2-1_PT7682
,2015-12-03T00:44:12.710Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03T00:44:12.711Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:44:17.723 ThaliTest[2542:2144842] jxcore: disconnect
2015-12-03 01:44:17.724 ThaliTest[2542:2144842] jxcore: disconnect: fail
2015-12-03T00:44:17.725Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03T00:44:17.725Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT8796.xJ9gmA== with availability status: true
2015-12-03T00:44:17.726Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03T00:44:17.726Z SendDataConnector.js: do connect now
,2015-12-03 01:44:17.727 ThaliTest[2542:2144842] jxcore: connect Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:44:17.728 ThaliTest[2542:2144842] client session: connect
2015-12-03 01:44:17.728 ThaliTest[2542:2144842] client session: stateChange:0->1 Apple,-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:44:20.145 ThaliTest[2542:2145147] client session: connected
2015-12-03 01:44:20.146 ThaliTest[2542:2145147] client session: stateChange:1->2 Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:44:20.155 ThaliTest[2542:2145221] client session: fireConnectCallback: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:44:20.156 ThaliTest[2542:2145221] jxcore: connect: success
2015-12-03T00:44:20.157Z SendDataConnector.js: CLIENT connected to 49799, error: null
2015-12-03T00:44:20.158Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:44:20.161 ThaliTest[2542:2144700] client: relay established
2015-12-03 01:44:20.162 ThaliTest[2542:2144700] client: new accepted socket: 0x192e8920
,2015-12-03T00:44:20.175Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 01:44:20.772 ThaliTest[2542:2144700] multipeer session: reset timer
2015-12-03 01:44:20.773 ThaliTest[2542:2144700] multipeer session: stop timer
2015-12-03 01:44:20.774 ThaliTest[2542:2144700] multipeer session: start timer: 0x192c4a90
2015-,12-03 01:44:20.775 ThaliTest[2542:2144700] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7682)
2015-12-03 01:44:20.775 ThaliTest[2542:2144700] server session: disconnect
2015-12-03 01:44:20.776 ThaliTest[2542:2144700] server session: state,Change:2->0 Apple-IpadAir2-1_PT7682
2015-12-03T00:44:20.782Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 01:44:20.783 ThaliTest[2542:2144700] server session: connect
2015-12-03 01:44:20.784 ThaliTest[2542:2144700] server session: stateChange,:0->1 Apple-IpadAir2-1_PT7682
,2015-12-03 01:44:20.802 ThaliTest[2542:2144700] server: accepting invitation Apple-IpadAir2-1_PT7682
,2015-12-03 01:44:23.152 ThaliTest[2542:2145222] server session: connected
2015-12-03 01:44:23.153 ThaliTest[2542:2145222] server session: stateChange:1->2 Apple-IpadAir2-1_PT7682
,2015-12-03 01:44:23.160 ThaliTest[2542:2144700] server relay: connected (to port: 49784)
,2015-12-03T00:44:23.170Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:44:23.207Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T00:44:30.246Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:44:30.246Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:44:30.247Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:44:30.248Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:44:30.248Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:44:30.250 ThaliTest[2542:2144700] client: socket closed
2015-12-03 01:44:30.251 ThaliTest[2542:2144700] client relay: socket disconnected
2015-12-03 01:44:30.251 ThaliTest[2542:2144700] client relay: 0x192e8920 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x191b4650 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 01:44:30.252 ThaliTest[2542:2144700] client session: socket closed: Apple-Iphone5-1_PT8796.xJ9gmA,==
2015-12-03 01:44:30.252 ThaliTest[2542:2144700] client session: onLinkFailure: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:44:30.253 ThaliTest[2542:2144700] client session: disconnect
2015-12-03 01:44:30.253 ThaliTest[2542:2144700] client session: ,stateChange:2->0 Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:44:30.257 ThaliTest[2542:2144700] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:44:33.210 ThaliTest[2542:2145221] server session: not connected Apple-IpadAir2-1_PT7682
,2015-12-03T00:44:35.258Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03T00:44:35.259Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:44:40.268 ThaliTest[2542:2144842] jxcore: disconnect
2015-12-03 01:44:40.269 ThaliTest[2542:2144842] jxcore: disconnect: fail
2015-12-03T00:44:40.269Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT8796.xJ9gm,A==
2015-12-03T00:44:40.270Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT8796.xJ9gmA== with availability status: true
2015-12-03T00:44:40.270Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03T00:44:40.270Z SendDataConnector.js: do connect now
2015-12-03 01:44:40.271 ThaliTest[2542:2144842] jxcore: connect Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:44:40.272 ThaliTest[2542:2144842] client session: connect
2015-12-03 01:44:40.273 ThaliTest[2542:2144842] client session: stateChange:0->1 Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:44:42.724 ThaliTest[2542:2145269] client session: connected
2015-12-03 01:44:42.724 ThaliTest[2542:2145269] client session: stateChange:1->2 Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:44:42.733 ThaliTest[2542:2145273] client session: fireConnectCallback: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:44:42.734 ThaliTest[2542:2145273] jxcore: connect: success
2015-12-03T00:44:42.735Z SendDataConnector.js: CLIENT connected to 49802, error: null
2015-12-03T00:44:42.735Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:44:42.739 ThaliTest[2542:2144700] client: relay established
2015-12-03 01:44:42.740 ThaliTest[2542:2144700] client: new accepted socket: 0x191cf240
,2015-12-03T00:44:42.752Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 01:44:50.775 ThaliTest[2542:2144700] multipeer session: restart
,2015-12-03 01:44:50.795 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:44:50.796 ThaliTest[2542:2144700] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:44:50.797 ThaliTest[2542:2144700] clie,nt: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03T00:44:52.820Z SendDataConnector.js: Receiving data timeout now
2015-12-03T00:44:52.820Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:44:52.821Z SendDataConnector.js: CLIENT closeClientSocket
,oneRoundDownNow
,oneRoundDownNow:2
,2015-12-03T00:44:52.823Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T00:44:52.823Z SendDataConnector.js: Stop data retrieving timer
,2015-12-03T00:44:52.824Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 01:44:52.825 ThaliTest[2542:2144842] jxcore: disconnect
2015-12-03 01:44:52.825 ThaliTest[2542:2144842] client session: disconnectFromPeer: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:44:52.826 ThaliTest[2542:2144842] client session: disconn,ect
2015-12-03 01:44:52.826 ThaliTest[2542:2144842] client session: stateChange:2->0 Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:44:52.830 ThaliTest[2542:2144842] jxcore: disconnect: success
,2015-12-03T00:44:52.832Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT8796.xJ9gmA==
---- round done--------
,device[3]: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:44:52.835Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:44:52.836Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:44:52.836Z SendDataConnector.js: do connect now
,2015-12-03 01:44:52.837 ThaliTest[2542:2144842] jxcore: connect Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:44:52.838 ThaliTest[2542:2144842] client session: connect
2015-12-03 01:44:52.838 ThaliTest[2542:2144842] client session: stateChange:0->1 Appl,e-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:44:52.844Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:44:55.598 ThaliTest[2542:2145288] client session: connected
2015-12-03 01:44:55.599 ThaliTest[2542:2145288] client session: stateChange:1->2 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:44:55.610 ThaliTest[2542:2145288] client session: fireConnectCallback: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:44:55.611 ThaliTest[2542:2145288] jxcore: connect: success
2015-12-03T00:44:55.612Z SendDataConnector.js: CLIENT connected to 49808, error: null
2015-12-03T00:44:55.612Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:44:55.616 ThaliTest[2542:2144700] client: relay established
2015-12-03 01:44:55.617 ThaliTest[2542:2144700] client: new accepted socket: 0x191d4680
,2015-12-03T00:44:55.629Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T00:44:55.913Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-03T00:44:55.926Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-03T00:44:55.951Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03 01:44:56.473 ThaliTest[2542:2144700] multipeer session: reset timer
2015-12-03 01:44:56.474 ThaliTest[2542:2144700] multipeer session: stop timer
2015-12-03 01:44:56.475 ThaliTest[2542:2144700] multipeer session: start timer: 0x192c4a90
2015-,12-03 01:44:56.475 ThaliTest[2542:2144700] server session: connect
2015-12-03 01:44:56.476 ThaliTest[2542:2144700] server session: stateChange:0->1 Apple-Iphone5-1_PT8796
,2015-12-03 01:44:56.485 ThaliTest[2542:2144700] server: accepting invitation Apple-Iphone5-1_PT8796
,2015-12-03 01:44:58.905 ThaliTest[2542:2145273] server session: connected
2015-12-03 01:44:58.906 ThaliTest[2542:2145273] server session: stateChange:1->2 Apple-Iphone5-1_PT8796
,2015-12-03 01:44:58.917 ThaliTest[2542:2144700] server relay: connected (to port: 49784)
2015-12-03T00:44:58.921Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:44:59.415Z SendDataTCPServer.js: TCP/IP server has received 9920 bytes of data
,2015-12-03T00:44:59.429Z SendDataTCPServer.js: TCP/IP server has received 15872 bytes of data
,2015-12-03T00:44:59.448Z SendDataTCPServer.js: TCP/IP server has received 33728 bytes of data
,2015-12-03T00:44:59.461Z SendDataTCPServer.js: TCP/IP server has received 46624 bytes of data
,2015-12-03T00:44:59.476Z SendDataTCPServer.js: TCP/IP server has received 60512 bytes of data
,2015-12-03T00:44:59.492Z SendDataTCPServer.js: TCP/IP server has received 77376 bytes of data
,2015-12-03T00:44:59.505Z SendDataTCPServer.js: TCP/IP server has received 90272 bytes of data
,2015-12-03T00:44:59.520Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 01:45:00.008 ThaliTest[2542:2145289] server session: not connected Apple-Iphone5-1_PT8796
,2015-12-03T00:45:05.954Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:45:05.954Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T00:45:05.955Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:45:05.955Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:45:05.956Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:45:05.958 ThaliTest[2542:2144700] client: socket closed
2015-12-03 01:45:05.958 ThaliTest[2542:2144700] client relay: socket disconnected
2015-12-03 01:45:05.959 ThaliTest[2542:2144700] client relay: 0x191d4680 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x192de700 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 01:45:05.960 ThaliTest[2542:2144700] client session: socket closed: Apple-Iphone5s-1_PT5704.2nX0i,g==
2015-12-03 01:45:05.960 ThaliTest[2542:2144700] client session: onLinkFailure: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:45:05.961 ThaliTest[2542:2144700] client session: disconnect
2015-12-03 01:45:05.961 ThaliTest[2542:2144700] client session,: stateChange:2->0 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:05.963 ThaliTest[2542:2144700] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:45:10.967Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:45:10.967Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:15.970 ThaliTest[2542:2144842] jxcore: disconnect
2015-12-03 01:45:15.971 ThaliTest[2542:2144842] jxcore: disconnect: fail
2015-12-03T00:45:15.972Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.2nX0,ig==
2015-12-03T00:45:15.972Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT5704.2nX0ig== with availability status: true
,2015-12-03T00:45:15.973Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03T00:45:15.973Z SendDataConnector.js: do connect now
,2015-12-03 01:45:15.974 ThaliTest[2542:2144842] jxcore: connect Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:45:15.975 ThaliTest[2542:2144842] client session: connect
2015-12-03 01:45:15.975 ThaliTest[2542:2144842] client session: stateChange:0->1 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:18.905 ThaliTest[2542:2145288] client session: connected
2015-12-03 01:45:18.906 ThaliTest[2542:2145288] client session: stateChange:1->2 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:18.914 ThaliTest[2542:2145287] client session: fireConnectCallback: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:45:18.915 ThaliTest[2542:2145287] jxcore: connect: success
2015-12-03T00:45:18.916Z SendDataConnector.js: CLIENT connected, to 49814, error: null
2015-12-03T00:45:18.917Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:45:18.920 ThaliTest[2542:2144700] client: relay established
2015-12-03 01:45:18.921 ThaliTest[2542:2144700] client: new accepted socket: 0x192ec090
,2015-12-03T00:45:18.933Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 01:45:19.913 ThaliTest[2542:2144700] multipeer session: reset timer
2015-12-03 01:45:19.914 ThaliTest[2542:2144700] multipeer session: stop timer
2015-12-03 01:45:19.915 ThaliTest[2542:2144700] multipeer session: start timer: 0x192c4a90
2015-,12-03 01:45:19.915 ThaliTest[2542:2144700] server: disconnecting to refresh session (Apple-Iphone5-1_PT8796)
2015-12-03 01:45:19.916 ThaliTest[2542:2144700] server session: disconnect
2015-12-03 01:45:19.916 ThaliTest[2542:2144700] server session: stateC,hange:2->0 Apple-Iphone5-1_PT8796
2015-12-03 01:45:19.920 ThaliTest[2542:2144700] server session: connect
2015-12-03 01:45:19.920 ThaliTest[2542:2144700] server session: stateChange:0->1 Apple-Iphone5-1_PT8796
2015-12-03T00:45:19.926Z SendDataTCPServer.,js: TCP/IP server is ended
,2015-12-03 01:45:19.937 ThaliTest[2542:2144700] server: accepting invitation Apple-Iphone5-1_PT8796
,2015-12-03 01:45:22.488 ThaliTest[2542:2145342] server session: connected
2015-12-03 01:45:22.488 ThaliTest[2542:2145342] server session: stateChange:1->2 Apple-Iphone5-1_PT8796
,2015-12-03T00:45:22.498Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03 01:45:22.499 ThaliTest[2542:2144700] server relay: connected (to port: 49784)
,2015-12-03T00:45:22.661Z SendDataTCPServer.js: TCP/IP server has received 2976 bytes of data
,2015-12-03T00:45:22.676Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T00:45:29.004Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:45:29.005Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:45:29.005Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:45:29.006Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:45:29.007Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:45:29.008 ThaliTest[2542:2144700] client: socket closed
2015-12-03 01:45:29.009 ThaliTest[2542:2144700] client relay: socket disconnected
2015-12-03 01:45:29.009 ThaliTest[2542:2144700] client relay: 0x192ec090 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x192dda70 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 01:45:29.010 ThaliTest[2542:2144700] client session: socket closed: Apple-Iphone5s-1_PT5704.2nX0i,g==
2015-12-03 01:45:29.011 ThaliTest[2542:2144700] client session: onLinkFailure: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:45:29.011 ThaliTest[2542:2144700] client session: disconnect
2015-12-03 01:45:29.011 ThaliTest[2542:2144700] client session,: stateChange:2->0 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:29.013 ThaliTest[2542:2144700] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:32.582 ThaliTest[2542:2145340] server session: not connected Apple-Iphone5-1_PT8796
,2015-12-03T00:45:34.015Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:45:34.015Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:39.025 ThaliTest[2542:2144842] jxcore: disconnect
2015-12-03 01:45:39.025 ThaliTest[2542:2144842] jxcore: disconnect: fail
2015-12-03T00:45:39.026Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.2nX0,ig==
2015-12-03T00:45:39.027Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT5704.2nX0ig== with availability status: true
,2015-12-03T00:45:39.027Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03T00:45:39.027Z SendDataConnector.js: do connect now
,2015-12-03 01:45:39.028 ThaliTest[2542:2144842] jxcore: connect Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:39.029 ThaliTest[2542:2144842] client session: connect
2015-12-03 01:45:39.030 ThaliTest[2542:2144842] client session: stateChange:0->1 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:41.537 ThaliTest[2542:2145340] client session: connected
2015-12-03 01:45:41.537 ThaliTest[2542:2145340] client session: stateChange:1->2 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:41.545 ThaliTest[2542:2145287] client session: fireConnectCallback: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:45:41.547 ThaliTest[2542:2145287] jxcore: connect: success
2015-12-03T00:45:41.548Z SendDataConnector.js: CLIENT connected to 49820, error: null
2015-12-03T00:45:41.549Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:45:41.552 ThaliTest[2542:2144700] client: relay established
2015-12-03 01:45:41.553 ThaliTest[2542:2144700] client: new accepted socket: 0x192ee140
,2015-12-03T00:45:41.565Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 01:45:43.407 ThaliTest[2542:2144700] multipeer session: reset timer
2015-12-03 01:45:43.408 ThaliTest[2542:2144700] multipeer session: stop timer
2015-12-03 01:45:43.409 ThaliTest[2542:2144700] multipeer session: start timer: 0x192c4a90
2015-,12-03 01:45:43.410 ThaliTest[2542:2144700] server: disconnecting to refresh session (Apple-Iphone5-1_PT8796)
2015-12-03 01:45:43.410 ThaliTest[2542:2144700] server session: disconnect
2015-12-03 01:45:43.411 ThaliTest[2542:2144700] server session: stateChange:2->0 Apple-Iphone5-1_PT8796
,2015-12-03 01:45:43.415 ThaliTest[2542:2144700] server session: connect
2015-12-03 01:45:43.415 ThaliTest[2542:2144700] server session: stateChange:0->1 Apple-Iphone5-1_PT8796
,2015-12-03T00:45:43.421Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 01:45:43.424 ThaliTest[2542:2144700] server: accepting invitation Apple-Iphone5-1_PT8796
,2015-12-03 01:45:46.080 ThaliTest[2542:2145287] server session: connected
2015-12-03 01:45:46.080 ThaliTest[2542:2145287] server session: stateChange:1->2 Apple-Iphone5-1_PT8796
,2015-12-03 01:45:46.093 ThaliTest[2542:2144700] server relay: connected (to port: 49784)
,2015-12-03T00:45:46.103Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:45:46.249Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T00:45:51.636Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:45:51.637Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:45:51.638Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:45:51.638Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:45:51.639Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:45:51.640 ThaliTest[2542:2144700] client: socket closed
2015-12-03 01:45:51.641 ThaliTest[2542:2144700] client relay: socket disconnected
2015-12-03 01:45:51.641 ThaliTest[2542:2144700] client relay: 0x192ee140 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x192c5330 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 01:45:51.642 ThaliTest[2542:2144700] client session: socket closed: Apple-Iphone5s-1_PT5704.2nX0i,g==
2015-12-03 01:45:51.643 ThaliTest[2542:2144700] client session: onLinkFailure: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:45:51.643 ThaliTest[2542:2144700] client session: disconnect
2015-12-03 01:45:51.643 ThaliTest[2542:2144700] client session,: stateChange:2->0 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:51.645 ThaliTest[2542:2144700] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:56.187 ThaliTest[2542:2145340] server session: not connected Apple-Iphone5-1_PT8796
,2015-12-03T00:45:56.643Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:45:56.643Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:46:01.650 ThaliTest[2542:2144842] jxcore: disconnect
2015-12-03 01:46:01.651 ThaliTest[2542:2144842] jxcore: disconnect: fail
2015-12-03T00:46:01.652Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.2nX0,ig==
2015-12-03T00:46:01.652Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT5704.2nX0ig== with availability status: true
2015-12-03T00:46:01.653Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.2nX0ig==,
,2015-12-03T00:46:01.653Z SendDataConnector.js: do connect now
,2015-12-03 01:46:01.654 ThaliTest[2542:2144842] jxcore: connect Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:46:01.655 ThaliTest[2542:2144842] client session: connect
2015-12-03 01:46:01.655 ThaliTest[2542:2144842] client session: stateChange:0->1 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:46:04.357 ThaliTest[2542:2145287] client session: connected
2015-12-03 01:46:04.358 ThaliTest[2542:2145287] client session: stateChange:1->2 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:46:04.367 ThaliTest[2542:2145423] client session: fireConnectCallback: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:46:04.368 ThaliTest[2542:2145423] jxcore: connect: success
2015-12-03T00:46:04.369Z SendDataConnector.js: CLIENT connected, to 49826, error: null
2015-12-03T00:46:04.369Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:46:04.373 ThaliTest[2542:2144700] client: relay established
2015-12-03 01:46:04.374 ThaliTest[2542:2144700] client: new accepted socket: 0x192da6b0
,2015-12-03T00:46:04.386Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 01:46:06.907 ThaliTest[2542:2144700] multipeer session: reset timer
2015-12-03 01:46:06.908 ThaliTest[2542:2144700] multipeer session: stop timer
2015-12-03 01:46:06.908 ThaliTest[2542:2144700] multipeer session: start timer: 0x192c4a90
2015-,12-03 01:46:06.909 ThaliTest[2542:2144700] server: disconnecting to refresh session (Apple-Iphone5-1_PT8796)
2015-12-03 01:46:06.910 ThaliTest[2542:2144700] server session: disconnect
2015-12-03 01:46:06.910 ThaliTest[2542:2144700] server session: stateC,hange:2->0 Apple-Iphone5-1_PT8796
2015-12-03 01:46:06.913 ThaliTest[2542:2144700] server session: connect
2015-12-03 01:46:06.913 ThaliTest[2542:2144700] server session: stateChange:0->1 Apple-Iphone5-1_PT8796
2015-12-03T00:46:06.918Z SendDataTCPServer.,js: TCP/IP server is ended
,2015-12-03 01:46:06.925 ThaliTest[2542:2144700] server: accepting invitation Apple-Iphone5-1_PT8796
,2015-12-03 01:46:09.168 ThaliTest[2542:2145433] server session: connected
2015-12-03 01:46:09.168 ThaliTest[2542:2145433] server session: stateChange:1->2 Apple-Iphone5-1_PT8796
,2015-12-03T00:46:09.179Z SendDataTCPServer.js: TCP/IP server connected
2015-12-03 01:46:09.179 ThaliTest[2542:2144700] server relay: connected (to port: 49784)
,2015-12-03T00:46:09.264Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T00:46:14.456Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:46:14.456Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:46:14.457Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:46:14.458Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:46:14.459Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:46:14.460 ThaliTest[2542:2144700] client: socket closed
2015-12-03 01:46:14.461 ThaliTest[2542:2144700] client relay: socket disconnected
2015-12-03 01:46:14.462 ThaliTest[2542:2144700] client relay: 0x192da6b0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x191d9330 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 01:46:14.463 ThaliTest[2542:2144700] client session: socket closed: Apple-Iphone5s-1_PT5704.2nX0i,g==
2015-12-03 01:46:14.463 ThaliTest[2542:2144700] client session: onLinkFailure: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:46:14.463 ThaliTest[2542:2144700] client session: disconnect
2015-12-03 01:46:14.464 ThaliTest[2542:2144700] client session,: stateChange:2->0 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:46:14.466 ThaliTest[2542:2144700] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:46:19.267 ThaliTest[2542:2145340] server session: not connected Apple-Iphone5-1_PT8796
,2015-12-03T00:46:19.459Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:46:19.460Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:46:24.464 ThaliTest[2542:2144842] jxcore: disconnect
2015-12-03 01:46:24.464 ThaliTest[2542:2144842] jxcore: disconnect: fail
2015-12-03T00:46:24.465Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.2nX0,ig==
2015-12-03T00:46:24.466Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT5704.2nX0ig== with availability status: true
,2015-12-03T00:46:24.466Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03T00:46:24.466Z SendDataConnector.js: do connect now
,2015-12-03 01:46:24.467 ThaliTest[2542:2144842] jxcore: connect Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:46:24.468 ThaliTest[2542:2144842] client session: connect
2015-12-03 01:46:24.469 ThaliTest[2542:2144842] client session: stateChange:0->1 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:46:27.151 ThaliTest[2542:2145340] client session: connected
2015-12-03 01:46:27.152 ThaliTest[2542:2145340] client session: stateChange:1->2 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:46:27.160 ThaliTest[2542:2145340] client session: fireConnectCallback: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:46:27.161 ThaliTest[2542:2145340] jxcore: connect: success
2015-12-03T00:46:27.162Z SendDataConnector.js: CLIENT connected, to 49832, error: null
,2015-12-03T00:46:27.163Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:46:27.167 ThaliTest[2542:2144700] client: relay established
2015-12-03 01:46:27.167 ThaliTest[2542:2144700] client: new accepted socket: 0x192f34e0
,2015-12-03T00:46:27.179Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 01:46:29.632 ThaliTest[2542:2144700] multipeer session: reset timer
2015-12-03 01:46:29.632 ThaliTest[2542:2144700] multipeer session: stop timer
2015-12-03 01:46:29.633 ThaliTest[2542:2144700] multipeer session: start timer: 0x192c4a90
2015-,12-03 01:46:29.634 ThaliTest[2542:2144700] server: disconnecting to refresh session (Apple-Iphone5-1_PT8796)
2015-12-03 01:46:29.634 ThaliTest[2542:2144700] server session: disconnect
2015-12-03 01:46:29.635 ThaliTest[2542:2144700] server session: stateC,hange:2->0 Apple-Iphone5-1_PT8796
2015-12-03 01:46:29.638 ThaliTest[2542:2144700] server session: connect
2015-12-03 01:46:29.639 ThaliTest[2542:2144700] server session: stateChange:0->1 Apple-Iphone5-1_PT8796
2015-12-03T00:46:29.645Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 01:46:29.656 ThaliTest[2542:2144700] server: accepting invitation Apple-Iphone5-1_PT8796
,2015-12-03 01:46:32.209 ThaliTest[2542:2145473] server session: connected
2015-12-03 01:46:32.209 ThaliTest[2542:2145473] server session: stateChange:1->2 Apple-Iphone5-1_PT8796
,2015-12-03 01:46:32.219 ThaliTest[2542:2144700] server relay: connected (to port: 49784)
,2015-12-03T00:46:32.225Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:46:32.374Z SendDataTCPServer.js: TCP/IP server has received 3968 bytes of data
,2015-12-03T00:46:32.388Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T00:46:37.254Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:46:37.256Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:46:37.256Z SendDataConnector.js: CLIENT closeClientSocket
oneRoundDownNow
,oneRoundDownNow:2
,2015-12-03T00:46:37.258Z SendDataConnector.js: CLIENT Stop now
2015-12-03T00:46:37.258Z SendDataConnector.js: Stop data retrieving timer
,2015-12-03T00:46:37.259Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 01:46:37.260 ThaliTest[2542:2144842] jxcore: disconnect
2015-12-03 01:46:37.260 ThaliTest[2542:2144842] client session: disconnectFromPeer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:46:37.261 ThaliTest[2542:2144842] client session: disconnect
2015-12-03 01:46:37.261 ThaliTest[2542:2144842] client session: stateChange:2->0 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:46:37.266 ThaliTest[2542:2144842] jxcore: disconnect: success
,2015-12-03T00:46:37.267Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.2nX0ig==
---- round done--------
device[4]: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03T00:46:37.269Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03T00:46:37.270Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03T00:46:37.270Z SendDataConnector.js: do connect now
,2015-12-03 01:46:37.271 ThaliTest[2542:2144842] jxcore: connect Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:46:37.272 ThaliTest[2542:2144842] client session: connect
2015-12-03 01:46:37.273 ThaliTest[2542:2144842] client session: stateChange:0->1 Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03T00:46:37.280Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:46:40.042 ThaliTest[2542:2145473] client session: connected
2015-12-03 01:46:40.043 ThaliTest[2542:2145473] client session: stateChange:1->2 Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:46:40.045 ThaliTest[2542:2145473] client session: fireConnectCallback: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:46:40.045 ThaliTest[2542:2145473] jxcore: connect: success
,2015-12-03T00:46:40.047Z SendDataConnector.js: CLIENT connected to 49836, error: null
2015-12-03T00:46:40.048Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:46:40.051 ThaliTest[2542:2144700] client: relay established
2015-12-03 01:46:40.051 ThaliTest[2542:2144700] client: new accepted socket: 0x191e8340
,2015-12-03T00:46:40.063Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T00:46:40.325Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-03T00:46:40.359Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03 01:46:42.302 ThaliTest[2542:2145439] server session: not connected Apple-Iphone5-1_PT8796
,2015-12-03T00:46:50.370Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:46:50.371Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:46:50.372Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:46:50.372Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:46:50.373Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:46:50.374 ThaliTest[2542:2144700] client: socket closed
2015-12-03 01:46:50.375 ThaliTest[2542:2144700] client relay: socket disconnected
2015-12-03 01:46:50.376 ThaliTest[2542:2144700] client relay: 0x191e8340 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x192f12a0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 01:46:50.377 ThaliTest[2542:2144700] client session: socket closed: Apple-IpadAir2-1_PT7682.INb6U,Q==
2015-12-03 01:46:50.377 ThaliTest[2542:2144700] client session: onLinkFailure: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:46:50.378 ThaliTest[2542:2144700] client session: disconnect
2015-12-03 01:46:50.378 ThaliTest[2542:2144700] client session,: stateChange:2->0 Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:46:50.381 ThaliTest[2542:2144700] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03T00:46:55.379Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03T00:46:55.380Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:46:59.635 ThaliTest[2542:2144700] multipeer session: restart
,2015-12-03 01:46:59.650 ThaliTest[2542:2144700] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:46:59.652 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:46:59.653 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:47:00.388 ThaliTest[2542:2144842] jxcore: disconnect
2015-12-03 01:47:00.389 ThaliTest[2542:2144842] jxcore: disconnect: fail
2015-12-03T00:47:00.389Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7682.INb6,UQ==
2015-12-03T00:47:00.389Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT7682.INb6UQ== with availability status: true
2015-12-03T00:47:00.389Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03T00:47:00.389Z SendDataConnector.js: do connect now
2015-12-03 01:47:00.390 ThaliTest[2542:2144842] jxcore: connect Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:47:00.390 ThaliTest[2542:2144842] client session: connect
2015-12-03 01:47:00.390 ThaliTest[2542:2144842] client session: stateChange:0->1 Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:47:03.336 ThaliTest[2542:2145509] client session: connected
2015-12-03 01:47:03.337 ThaliTest[2542:2145509] client session: stateChange:1->2 Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:47:03.340 ThaliTest[2542:2145509] client session: fi,reConnectCallback: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:47:03.340 ThaliTest[2542:2145509] jxcore: connect: success
2015-12-03T00:47:03.342Z SendDataConnector.js: CLIENT connected to 49840, error: null
2015-12-03T00:47:03.343Z SendDataConnector,.js: CLIENT starting client 
,2015-12-03 01:47:03.347 ThaliTest[2542:2144700] client: relay established
2015-12-03 01:47:03.348 ThaliTest[2542:2144700] client: new accepted socket: 0x191e7030
,2015-12-03T00:47:03.360Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 01:47:12.031 ThaliTest[2542:2144700] client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:47:12.032 ThaliTest[2542:2144700] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
2015-12-03 01:47:12.034 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==,","peerName":"(null)","peerAvailable":true}]
,2015-12-03T00:47:13.429Z SendDataConnector.js: Receiving data timeout now
2015-12-03T00:47:13.429Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:47:13.430Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:47:13.431Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:47:13.431Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:47:13.433 ThaliTest[2542:2144700] client: socket closed
2015-12-03 01:47:13.434 ThaliTest[2542:2144700] client relay: socket disconnected
2015-12-03 01:47:13.434 ThaliTest[2542:2144700] client relay: 0x191e7030 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x192c5800 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 01:47:13.435 ThaliTest[2542:2144700] client session: socket closed: Apple-IpadAir2-1_PT7682.INb6U,Q==
2015-12-03 01:47:13.435 ThaliTest[2542:2144700] client session: onLinkFailure: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:47:13.436 ThaliTest[2542:2144700] client session: disconnect
2015-12-03 01:47:13.436 ThaliTest[2542:2144700] client session,: stateChange:2->0 Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:47:13.439 ThaliTest[2542:2144700] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03T00:47:18.443Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03T00:47:18.444Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:47:20.943 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:47:23.446 ThaliTest[2542:2144842] jxcore: disconnect
2015-12-03 01:47:23.447 ThaliTest[2542:2144842] jxcore: disconnect: fail
2015-12-03T00:47:23.447Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7682.INb6,UQ==
2015-12-03T00:47:23.448Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT7682.INb6UQ== with availability status: true
2015-12-03T00:47:23.448Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03T00:47:23.448Z SendDataConnector.js: do connect now
,2015-12-03 01:47:23.449 ThaliTest[2542:2144842] jxcore: connect Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:47:23.450 ThaliTest[2542:2144842] client session: connect
2015-12-03 01:47:23.451 ThaliTest[2542:2144842] client session: stateChange:0->1 Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:47:26.429 ThaliTest[2542:2145567] client session: connected
2015-12-03 01:47:26.430 ThaliTest[2542:2145567] client session: stateChange:1->2 Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:47:26.431 ThaliTest[2542:2145567] client session: fi,reConnectCallback: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:47:26.432 ThaliTest[2542:2145567] jxcore: connect: success
2015-12-03T00:47:26.433Z SendDataConnector.js: CLIENT connected to 49843, error: null
2015-12-03T00:47:26.434Z SendDataConnector,.js: CLIENT starting client 
,2015-12-03 01:47:26.437 ThaliTest[2542:2144700] client: relay established
2015-12-03 01:47:26.438 ThaliTest[2542:2144700] client: new accepted socket: 0x192e7870
,2015-12-03T00:47:26.450Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 01:47:29.635 ThaliTest[2542:2144700] multipeer session: restart
,2015-12-03 01:47:29.653 ThaliTest[2542:2144700] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:47:29.655 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:47:29.657 ThaliTest[2542:2144700] clie,nt: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03T00:47:36.524Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:47:36.524Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:47:36.525Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:47:36.526Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:47:36.526Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:47:36.528 ThaliTest[2542:2144700] client: socket closed
2015-12-03 01:47:36.528 ThaliTest[2542:2144700] client relay: socket disconnected
2015-12-03 01:47:36.529 ThaliTest[2542:2144700] client relay: 0x192e7870 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x192e3f00 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 01:47:36.529 ThaliTest[2542:2144700] client session: socket closed: Apple-IpadAir2-1_PT7682.INb6U,Q==
2015-12-03 01:47:36.530 ThaliTest[2542:2144700] client session: onLinkFailure: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:47:36.530 ThaliTest[2542:2144700] client session: disconnect
2015-12-03 01:47:36.531 ThaliTest[2542:2144700] client session: stateChange:2->0 Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:47:36.534 ThaliTest[2542:2144700] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:47:41.525 ThaliTest[2542:2144700] client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:47:41.525 ThaliTest[2542:2144700] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
,2015-12-03T00:47:41.540Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03T00:47:41.540Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:47:41.910 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 01:47:46.543 ThaliTest[2542:2144842] jxcore: disconnect
2015-12-03 01:47:46.544 ThaliTest[2542:2144842] jxcore: disconnect: fail
2015-12-03T00:47:46.544Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7682.INb6,UQ==
2015-12-03T00:47:46.545Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT7682.INb6UQ== with availability status: true
2015-12-03T00:47:46.545Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7682.INb6UQ==,
,2015-12-03T00:47:46.545Z SendDataConnector.js: do connect now
,2015-12-03 01:47:46.546 ThaliTest[2542:2144842] jxcore: connect Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:47:46.547 ThaliTest[2542:2144842] client session: connect
,2015-12-03 01:47:46.548 ThaliTest[2542:2144842] client session: stateChange:0->1 Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:47:47.178 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:47:49.507 ThaliTest[2542:2145614] client session: connected
2015-12-03 01:47:49.508 ThaliTest[2542:2145614] client session: stateChange:1->2 Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:47:49.510 ThaliTest[2542:2145614] client session: fireConnectCallback: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:47:49.511 ThaliTest[2542:2145614] jxcore: connect: success
2015-12-03T00:47:49.512Z SendDataConnector.js: CLIENT connected to 49847, error: null
,2015-12-03T00:47:49.513Z SendDataConnector.js: CLIENT starting client 
2015-12-03 01:47:49.516 ThaliTest[2542:2144700] client: relay established
2015-12-03 01:47:49.517 ThaliTest[2542:2144700] client: new accepted socket: 0x191ec750
,2015-12-03T00:47:49.529Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T00:47:59.602Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:47:59.602Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:47:59.603Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:47:59.604Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:47:59.605Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:47:59.606 ThaliTest[2542:2144700] client: socket closed
2015-12-03 01:47:59.607 ThaliTest[2542:2144700] client relay: socket disconnected
2015-12-03 01:47:59.607 ThaliTest[2542:2144700] client relay: 0x191ec750 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x192e31c0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 01:47:59.608 ThaliTest[2542:2144700] client session: socket closed: Apple-IpadAir2-1_PT7682.INb6U,Q==
2015-12-03 01:47:59.608 ThaliTest[2542:2144700] client session: onLinkFailure: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:47:59.609 ThaliTest[2542:2144700] client session: disconnect
2015-12-03 01:47:59.609 ThaliTest[2542:2144700] client session,: stateChange:2->0 Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:47:59.612 ThaliTest[2542:2144700] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:47:59.635 ThaliTest[2542:2144700] multipeer session: restart
,2015-12-03 01:47:59.650 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:47:59.651 ThaliTest[2542:2144700] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:47:59.654 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03T00:48:04.610Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03T00:48:04.610Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:48:09.613 ThaliTest[2542:2144842] jxcore: disconnect
2015-12-03 01:48:09.613 ThaliTest[2542:2144842] jxcore: disconnect: fail
2015-12-03T00:48:09.614Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7682.INb6,UQ==
2015-12-03T00:48:09.615Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT7682.INb6UQ== with availability status: true
,2015-12-03T00:48:09.615Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03T00:48:09.615Z SendDataConnector.js: do connect now
,2015-12-03 01:48:09.616 ThaliTest[2542:2144842] jxcore: connect Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:48:09.617 ThaliTest[2542:2144842] client session: connect
2015-12-03 01:48:09.618 ThaliTest[2542:2144842] client session: stateChange:0->1 Appl,e-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:48:11.276 ThaliTest[2542:2144700] client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:48:11.277 ThaliTest[2542:2144700] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 01:48:11.805 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 01:48:12.317 ThaliTest[2542:2145645] client session: connected
2015-12-03 01:48:12.318 ThaliTest[2542:2145645] client session: stateChange:1->2 Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:48:12.323 ThaliTest[2542:2145653] client session: fireConnectCallback: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:48:12.324 ThaliTest[2542:2145653] jxcore: connect: success
2015-12-03T00:48:12.325Z SendDataConnector.js: CLIENT connected to 49851, error: null
2015-12-03T00:48:12.325Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:48:12.328 ThaliTest[2542:2144700] client: relay established
2015-12-03 01:48:12.329 ThaliTest[2542:2144700] client: new accepted socket: 0x191eefd0
,2015-12-03T00:48:12.340Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 01:48:21.223 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:48:22.416Z SendDataConnector.js: Receiving data timeout now
2015-12-03T00:48:22.416Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:48:22.417Z SendDataConnector.js: CLIENT closeClientSocket
,oneRoundDownNow
,oneRoundDownNow:2
,2015-12-03T00:48:22.419Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T00:48:22.419Z SendDataConnector.js: Stop data retrieving timer
,2015-12-03T00:48:22.419Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 01:48:22.420 ThaliTest[2542:2144842] jxcore: disconnect
2015-12-03 01:48:22.421 ThaliTest[2542:2144842] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:48:22.422 ThaliTest[2542:2144842] client session: disconnect
2015-12-03 01:48:22.422 ThaliTest[2542:2144842] client session: stateChange:2->0 Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:48:22.425 ThaliTest[2542:2144842] jxcore: disconnect: success
2015-12-03T00:48:22.425Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7682.INb6UQ==
---- round done--------
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,{ roundsToDo: 1,
  doneRounds: 1,
  toSendDataAmount: 100000,
  reTryTimeout: 5000,
  reTryMaxCount: 5,
  dataTimeOut: 10000,
  clientSocket: 
   { _connecting: false,
     _handle: 
      { writeQueueSize: 0,
        owner: [Circular],
        ,onread: [Function: onread],
        reading: true },
     _readableState: 
      { highWaterMark: 16384,
        buffer: [],
        length: 0,
        pipes: null,
        pipesCount: 0,
        flowing: false,
        ended: false,
        endE,mitted: false,
        reading: true,
        calledRead: true,
        sync: false,
        needReadable: true,
        emittedReadable: false,
        readableListening: false,
        objectMode: false,
        defaultEncoding: 'utf8',
        ,ranOut: false,
        awaitDrain: 0,
        readingMore: false,
        decoder: null,
        encoding: null },
     readable: true,
     domain: null,
     _events: 
      { end: [Object],
        finish: [Function: onSocketFinish],
        _,socketEnd: [Function: onSocketEnd],
        data: [Function],
        readable: [Function],
        error: [Function] },
     _maxListeners: 10,
     _writableState: 
      { highWaterMark: 16384,
        objectMode: false,
        needDrain: false,,
        ending: true,
        ended: true,
        finished: true,
        decodeStrings: false,
        defaultEncoding: 'utf8',
        length: 0,
        writing: false,
        sync: false,
        bufferProcessing: false,
        onwrite: ,[Function],
        writecb: null,
        writelen: 0,
        buffer: [],
        errorEmitted: false },
     writable: false,
     allowHalfOpen: false,
     onend: null,
     destroyed: false,
     bytesRead: 0,
     _bytesDispatched: 5000,
,     _pendingData: null,
     _pendingEncoding: '',
     __ec_int: true,
     ___timerId: 1,
     pipe: [Function],
     addListener: [Function: addListener],
     on: [Function: addListener],
     pause: [Function],
     resume: [Function],
     ,read: [Function],
     _consuming: true },
  reTryTimer: null,
  receivedCounter: 90000,
  tryRounds: 0,
  resultArray: [],
  connectionCount: 0,
  _events: { done: [Function], debug: [Function] },
  peer: null,
  startTime: Thu Dec 03 2015 01:48:,22 GMT+0100 (CET),
  endTime: Thu Dec 03 2015 01:48:22 GMT+0100 (CET),
  endReason: '',
  dataTimerId: null,
  disconnecting: true }
done, now sending data to server
CoordinatorConnector-debug: sendData
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT2613","time":358298,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT5704.8qCfew==","time":44228,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple,-Iphone5-1_PT8796.xJ9gmA==","time":104361,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name":"Apple-Iphone5s-1_PT5704.2nX0ig==","time":104422,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"data,Amount":100000,"dataReceived":90000},{"name":"Apple-IpadAir2-1_PT7682.INb6UQ==","time":105148,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000}]}
,sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Results list does not contain any items
,sendList failed peers count : 4 [100 %]
,- Peer ID : Apple-Iphone5s-1_PT5704.8qCfew==, Tried : 5
,- Peer ID : Apple-Iphone5-1_PT8796.xJ9gmA==, Tried : 5
,- Peer ID : Apple-Iphone5s-1_PT5704.2nX0ig==, Tried : 5
,- Peer ID : Apple-IpadAir2-1_PT7682.INb6UQ==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-12-03T00:48:22.461Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T00:48:22.462Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:48:22.463Z SendDataConnector.js: ----------------- closeClientSocket
,CoordinatorConnector-debug: disconnect:transport close
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:48:29.633 ThaliTest[2542:2144700] multipeer session: restart
,2015-12-03 01:48:29.652 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:48:29.653 ThaliTest[2542:2144700] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:48:29.654 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:48:59.632 ThaliTest[2542:2144700] multipeer session: restart
,2015-12-03 01:48:59.650 ThaliTest[2542:2144700] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:48:59.652 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:48:59.654 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:49:09.970 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:49:20.975 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:49:29.633 ThaliTest[2542:2144700] multipeer session: restart
,2015-12-03 01:49:29.650 ThaliTest[2542:2144700] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:49:29.651 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:49:29.651 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:49:59.633 ThaliTest[2542:2144700] multipeer session: restart
,2015-12-03 01:49:59.652 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:49:59.654 ThaliTest[2542:2144700] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:49:59.654 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:50:09.724 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:50:20.922 ThaliTest[2542:2144700] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:50:29.632 ThaliTest[2542:2144700] multipeer session: restart
2015-12-03 01:50:29.639 ThaliTest[2542:2144700] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Fi,rst throw call stack:
(0x26e2efef 0x35798c8b 0x26d4aaa3 0x28e09d85 0x26932607 0x26931e81 0x268ab3d3 0x26df4faf 0x26df43bf 0x26df2a25 0x26d3f201 0x26d3f013 0x2e7ca201 0x2a50ba09 0x135e3 0x35d4aaaf)
libc++abi.dylib: terminating with uncaught exception of type NSException
,* thread #1: tid = 0x20b9bc, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
  * frame #0: 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x35e93cc6 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x35db0908 libsystem_c.dylib`abort + 76
    frame #3: 0x350a79c8 libc++abi.dylib`<redacted> + 88
    frame #4: 0x350c1670 libc++abi.dylib`<redacted> + 268
    frame #5: 0x35798f24 libobjc.A.dylib`<redacted> + 192
    frame #6: 0x350bede2 libc++abi.dylib`<redacted> + 78
    frame #7: 0x350be8ae libc++abi.dylib`__cxa_rethrow + 102
    frame #8: 0x35798dd2 libobjc.A.dylib`objc_exception_rethrow + 42
    frame #9: 0x26d3f29c CoreFoundation`CFRunLoopRunSpecific + 632
    frame #10: 0x26d3f012 CoreFoundation`CFRunLoopRunInMode + 106
    frame #11: 0x2e7ca200 GraphicsServices`GSEventRunModal + 136
    frame #12: 0x2a50ba08 UIKit`UIApplicationMain + 1440
    frame #13: 0x000135e2 ThaliTest`main + 50

```
