#### Test 506502782b2305a_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502782b2305a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2C0F4C4F-6171-4C82-B04E-D0EAB4EF95F9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/2C0F4C4F-6171-4C82-B04E-D0EAB4EF95F9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502782b2305a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502782b2305a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7EB0EAF3-5E14-4E40-A813-7F0B3E5CEAF7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60121"
,(lldb)     command script import "/tmp/2C0F4C4F-6171-4C82-B04E-D0EAB4EF95F9/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 01:41:16.127 ThaliTest[2405:2239989] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F22CCFD8-278C-4737-B49A-858EF688CE5F/Library/Cookies/Cookies.binarycookies
,2015-12-03 01:41:16.559 ThaliTest[2405:2239989] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 01:41:16.561 ThaliTest[2405:2239989] Multi-tasking -> Device: YES, App: YES
,2015-12-03 01:41:16.570 ThaliTest[2405:2239989] Unlimited access to network resources
,2015-12-03 01:41:16.577 ThaliTest[2405:2239989] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 01:41:20.326 ThaliTest[2405:2239989] Resetting plugins due to page load.
,2015-12-03 01:41:20.739 ThaliTest[2405:2239989] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/7EB0EAF3-5E14-4E40-A813-7F0B3E5CEAF7/ThaliTest.app/www/index.html
,2015-12-03 01:41:20.894 ThaliTest[2405:2239989] JXcore Cordova plugin initializing
2015-12-03 01:41:20.895 ThaliTest[2405:2240121] JXcore instance initializing
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
,Coordinator is now connected to the server!
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
  addressLi,st: [] }
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-03 01:42:22.707 ThaliTest[2405:2240121] jxcore: startBroadcasting
,2015-12-03 01:42:22.721 ThaliTest[2405:2240121] server: starting Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03 01:42:22.722 ThaliTest[2405:2240121] multipeer session: start timer: 0x181bdf40
2015-12-03 01:42:22.723 ThaliTest[2405:2240121] THEMultipeerSessi,on initialized peer Apple-Iphone5s-1_PT5704
2015-12-03 01:42:22.724 ThaliTest[2405:2240121] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-03 01:42:22.903 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.bcJOyQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.bcJOyQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT2613.bcJOyQ==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,CoordinatorConnector-debug: sendData
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT5704","time":206,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1_PT2613.bcJOyQ==","peerAvailable":true,"time":204}]}
peersList : 100% : 204 ms, 99% : 204 ms, 95 : 204 ms, 90% : 204 ms.
,Result count 1, range 204 ms to  204 ms.
,2015-12-03 01:42:23.977 ThaliTest[2405:2239989] multipeer session: reset timer
2015-12-03 01:42:23.979 ThaliTest[2405:2239989] multipeer session: stop timer
2015-12-03 01:42:23.980 ThaliTest[2405:2239989] multipeer session: start timer: 0x181bdf40
2015-,12-03 01:42:23.981 ThaliTest[2405:2239989] server session: connect
2015-12-03 01:42:23.982 ThaliTest[2405:2239989] server session: stateChange:0->1 Apple-Iphone5-1_PT8796
,2015-12-03 01:42:23.997 ThaliTest[2405:2239989] server: accepting invitation Apple-Iphone5-1_PT8796
2015-12-03 01:42:24.007 ThaliTest[2405:2239989] client: found peer: Apple-Iphone5-1_PT8796./19b4A==
,CoordinatorConnector-debug: stop:undefined
,stop tests now !
stop current!
testFindPeers stopped
2015-12-03 01:42:24.081 ThaliTest[2405:2240121] jxcore: stopBroadcasting
,2015-12-03 01:42:24.082 ThaliTest[2405:2240121] THEMultipeerSession stopping peer
,2015-12-03 01:42:24.083 ThaliTest[2405:2240121] multipeer session: stop timer
2015-12-03 01:42:24.084 ThaliTest[2405:2240121] server session: disconnect
2015-12-03 01:42:24.085 ThaliTest[2405:2240121] server session: stateChange:1->0 Apple-Iphone5-1_PT87,96
2015-12-03 01:42:24.085 ThaliTest[2405:2240121] jxcore: stopBroadcasting: success
StopBroadcasting went ok
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
,serverPort is 49855
,2015-12-03 01:42:24.144 ThaliTest[2405:2240121] jxcore: startBroadcasting
,2015-12-03 01:42:24.145 ThaliTest[2405:2240121] server: starting Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:42:24.145 ThaliTest[2405:2240121] multipeer session: start timer: 0x14565fe0
2015-12-03 01:42:24.146 ThaliTest[2405:2240121] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT5704
2015-12-03 01:42:24.146 ThaliTest[2405:2240121] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-03T00:42:24.147Z SendDataTCPServer.js: TCP/IP server is bound to port: 49855
,2015-12-03 01:42:24.281 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.bcJOyQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.bcJOyQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03T00:42:24.284Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03T00:42:24.284Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03T00:42:24.284Z SendDataConnector.js: do connect now
,2015-12-03 01:42:24.285 ThaliTest[2405:2240121] jxcore: connect Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:42:24.285 ThaliTest[2405:2240121] client session: connect
2015-12-03 01:42:24.285 ThaliTest[2405:2240121] client session: stateChange:0->1 Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03 01:42:24.398 ThaliTest[2405:2239989] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8796.xJ9gmA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 01:42:24.476 ThaliTest[2405:2239989] client: found peer: Apple-Iphone5s-1_PT5704.8qCfew==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.8qCfew==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 01:42:24.482 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 01:42:25.153 ThaliTest[2405:2239989] client: lost peer: Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03 01:42:25.154 ThaliTest[2405:2239989] client session: onPeerLost: Apple-Iphone5s-1_PT5704.8qCfew==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT5704.8qCfew==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 01:42:25.840 ThaliTest[2405:2239989] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7682.INb6UQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 01:42:26.450 ThaliTest[2405:2239989] client: lost peer: Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:42:26.450 ThaliTest[2405:2239989] client session: onPeerLost: Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:42:26.451 ThaliTest[2405:2239989], client session: onLinkFailure: Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:42:26.451 ThaliTest[2405:2239989] client session: disconnect
2015-12-03 01:42:26.452 ThaliTest[2405:2239989] client session: stateChange:1->0 Apple-Iphone6-1_PT2613.bcJOyQ==
2,015-12-03 01:42:26.452 ThaliTest[2405:2239989] client session: fireConnectCallback: Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:42:26.453 ThaliTest[2405:2239989] jxcore: connect: fail: Peer disconnected
,2015-12-03T00:42:26.455Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T00:42:26.455Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-03T00:42:26.457Z SendDataConnector.js: tryAgain afer: 5000 ms.,
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.bcJOyQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-03T00:42:31.460Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03T00:42:31.461Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03 01:42:36.463 ThaliTest[2405:2240121] jxcore: disconnect
2015-12-03 01:42:36.464 ThaliTest[2405:2240121] jxcore: disconnect: fail
2015-12-03T00:42:36.464Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2613.bcJOy,Q==
2015-12-03T00:42:36.465Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT2613.bcJOyQ== with availability status: true
2015-12-03T00:42:36.465Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2613.bcJOyQ==
2,015-12-03T00:42:36.466Z SendDataConnector.js: do connect now
,2015-12-03 01:42:36.466 ThaliTest[2405:2240121] jxcore: connect Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:42:36.467 ThaliTest[2405:2240121] client: connect: unreachable Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03 01:42:36.468 ThaliTest[2405:2240121] jxcore: connect: fail: Peer unreachable
,2015-12-03T00:42:36.469Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-03T00:42:36.470Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-03T00:42:36.470Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:42:41.478Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03T00:42:41.478Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03 01:42:46.487 ThaliTest[2405:2240121] jxcore: disconnect
2015-12-03 01:42:46.487 ThaliTest[2405:2240121] jxcore: disconnect: fail
2015-12-03T00:42:46.488Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2613.bcJOy,Q==
2015-12-03T00:42:46.489Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT2613.bcJOyQ== with availability status: true
2015-12-03T00:42:46.489Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03T00:42:46.489Z SendDataConnector.js: do connect now
2015-12-03 01:42:46.490 ThaliTest[2405:2240121] jxcore: connect Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03 01:42:46.491 ThaliTest[2405:2240121] client: connect: unreachable Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03 01:42:46.492 ThaliTest[2405:2240121] jxcore: connect: fail: Peer unreachable
2015-12-03T00:42:46.493Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-03T00:42:46.493Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-03T00:42:46.494Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:42:51.499Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03T00:42:51.500Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03 01:42:54.147 ThaliTest[2405:2239989] multipeer session: restart
,2015-12-03 01:42:54.170 ThaliTest[2405:2239989] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:42:54.171 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:42:54.173 ThaliTest[2405:2239989] clien,t: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:42:56.503 ThaliTest[2405:2240121] jxcore: disconnect
2015-12-03 01:42:56.504 ThaliTest[2405:2240121] jxcore: disconnect: fail
2015-12-03T00:42:56.505Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2613.bcJOy,Q==
2015-12-03T00:42:56.505Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT2613.bcJOyQ== with availability status: true
,2015-12-03T00:42:56.506Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03T00:42:56.506Z SendDataConnector.js: do connect now
,2015-12-03 01:42:56.507 ThaliTest[2405:2240121] jxcore: connect Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:42:56.508 ThaliTest[2405:2240121] client: connect: unreachable Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:42:56.508 ThaliTest[2405:2240121] j,xcore: connect: fail: Peer unreachable
2015-12-03T00:42:56.509Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-03T00:42:56.510Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-03T00:42:56.510Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:43:01.519Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03T00:43:01.520Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03 01:43:06.531 ThaliTest[2405:2240121] jxcore: disconnect
2015-12-03 01:43:06.531 ThaliTest[2405:2240121] jxcore: disconnect: fail
2015-12-03T00:43:06.532Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2613.bcJOy,Q==
2015-12-03T00:43:06.533Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT2613.bcJOyQ== with availability status: true
2015-12-03T00:43:06.533Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2613.bcJOyQ==
2,015-12-03T00:43:06.533Z SendDataConnector.js: do connect now
,2015-12-03 01:43:06.534 ThaliTest[2405:2240121] jxcore: connect Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03 01:43:06.535 ThaliTest[2405:2240121] client: connect: unreachable Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:43:06.537 ThaliTest[2405:2240121] jxcore: connect: fail: Peer unreachable
2015-12-03T00:43:06.538Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-03T00:43:06.538Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
oneRoundDownNow:2
,2015-12-03T00:43:06.541Z SendDataConnector.js: CLIENT Stop now
,2015-12-03 01:43:06.542 ThaliTest[2405:2240121] jxcore: disconnect
2015-12-03 01:43:06.543 ThaliTest[2405:2240121] jxcore: disconnect: fail
2015-12-03T00:43:06.544Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2613.bcJOyQ==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03T00:43:06.547Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03T00:43:06.547Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03T00:43:06.548Z SendDataConnector.js: do connect now
,2015-12-03 01:43:06.549 ThaliTest[2405:2240121] jxcore: connect Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:43:06.549 ThaliTest[2405:2240121] client session: connect
2015-12-03 01:43:06.550 ThaliTest[2405:2240121] client session: stateChange:0->1 Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:43:06.747 ThaliTest[2405:2239989] client: lost peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:43:06.748 ThaliTest[2405:2239989] client session: onPeerLost: Apple-Iphone6-1_PT2613.ais2pw==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 01:43:06.862 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 01:43:09.327 ThaliTest[2405:2240364] client session: connected
2015-12-03 01:43:09.328 ThaliTest[2405:2240364] client session: stateChange:1->2 Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:43:09.334 ThaliTest[2405:2240364] client session: fireConnectCallback: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:43:09.335 ThaliTest[2405:2240364] jxcore: connect: success
2015-12-03T00:43:09.337Z SendDataConnector.js: CLIENT connected to 49860, error: null
,2015-12-03T00:43:09.338Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:43:09.342 ThaliTest[2405:2239989] client: relay established
2015-12-03 01:43:09.343 ThaliTest[2405:2239989] client: new accepted socket: 0x1826d710
,2015-12-03T00:43:09.359Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T00:43:09.673Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-03T00:43:09.686Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-03T00:43:09.686Z SendDataConnector.js: got all data for this round
oneRoundDownNow
oneRoundDownNow:2
,2015-12-03T00:43:09.687Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T00:43:09.687Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 01:43:09.688 ThaliTest[2405:2240121] jxcore: disconnect
,2015-12-03 01:43:09.688 ThaliTest[2405:2240121] client session: disconnectFromPeer: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:43:09.689 ThaliTest[2405:2240121] client session: disconnect
,2015-12-03 01:43:09.689 ThaliTest[2405:2240121] client session: stateChange:2->0 Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:43:09.748 ThaliTest[2405:2240121] jxcore: disconnect: success
,2015-12-03T00:43:09.749Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT8796.xJ9gmA==
---- round done--------
,device[3]: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:43:09.750Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:43:09.750Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:43:09.750Z SendDataConnector.js: do connect now
,2015-12-03 01:43:09.751 ThaliTest[2405:2240121] jxcore: connect Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:43:09.751 ThaliTest[2405:2240121] client session: connect
,2015-12-03 01:43:09.752 ThaliTest[2405:2240121] client session: stateChange:0->1 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:43:11.548 ThaliTest[2405:2239989] multipeer session: reset timer
2015-12-03 01:43:11.549 ThaliTest[2405:2239989] multipeer session: stop timer
2015-12-03 01:43:11.550 ThaliTest[2405:2239989] multipeer session: start timer: 0x14565fe0
2015-,12-03 01:43:11.551 ThaliTest[2405:2239989] server session: connect
2015-12-03 01:43:11.551 ThaliTest[2405:2239989] server session: stateChange:0->1 Apple-Iphone5-1_PT8796
,2015-12-03 01:43:11.565 ThaliTest[2405:2239989] server: accepting invitation Apple-Iphone5-1_PT8796
,2015-12-03 01:43:12.582 ThaliTest[2405:2240364] client session: connected
2015-12-03 01:43:12.582 ThaliTest[2405:2240364] client session: stateChange:1->2 Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:43:12.587 ThaliTest[2405:2240364] client session: fir,eConnectCallback: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:43:12.588 ThaliTest[2405:2240364] jxcore: connect: success
,2015-12-03T00:43:12.590Z SendDataConnector.js: CLIENT connected to 49864, error: null
,2015-12-03T00:43:12.591Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:43:12.596 ThaliTest[2405:2239989] client: relay established
2015-12-03 01:43:12.596 ThaliTest[2405:2239989] client: new accepted socket: 0x1826bd10
,2015-12-03T00:43:12.606Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T00:43:13.077Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-03T00:43:13.101Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-03T00:43:13.102Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,oneRoundDownNow:2
2015-12-03T00:43:13.102Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T00:43:13.102Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 01:43:13.103 ThaliTest[2405:2240121] jxcore: disconnect
2015-12-03 01:43:13.103 ThaliTest[2405:2240121] client session: disconnectFromPeer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:43:13.103 ThaliTest[2405:2240121] client session: disconnect
,2015-12-03 01:43:13.103 ThaliTest[2405:2240121] client session: stateChange:2->0 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:43:13.105 ThaliTest[2405:2240121] jxcore: disconnect: success
2015-12-03T00:43:13.105Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2613.ais2pw==
---- round done--------
device[4]: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03T00:43:13.105Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03T00:43:13.106Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03T00:43:13.106Z SendDataConnector.js: do connect now
,2015-12-03 01:43:13.107 ThaliTest[2405:2240121] jxcore: connect Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:43:13.107 ThaliTest[2405:2240121] client session: connect
2015-12-03 01:43:13.107 ThaliTest[2405:2240121] client session: stateChange:0->1 Appl,e-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:43:14.191 ThaliTest[2405:2240375] server session: connected
2015-12-03 01:43:14.191 ThaliTest[2405:2240375] server session: stateChange:1->2 Apple-Iphone5-1_PT8796
,2015-12-03 01:43:14.201 ThaliTest[2405:2239989] server relay: connected (to port: 49855)
2015-12-03T00:43:14.202Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:43:14.720Z SendDataTCPServer.js: TCP/IP server has received 8928 bytes of data
,2015-12-03T00:43:14.736Z SendDataTCPServer.js: TCP/IP server has received 19840 bytes of data
,2015-12-03T00:43:14.750Z SendDataTCPServer.js: TCP/IP server has received 29760 bytes of data
,2015-12-03T00:43:14.767Z SendDataTCPServer.js: TCP/IP server has received 40672 bytes of data
,2015-12-03T00:43:14.788Z SendDataTCPServer.js: TCP/IP server has received 49600 bytes of data
,2015-12-03T00:43:14.809Z SendDataTCPServer.js: TCP/IP server has received 64480 bytes of data
,2015-12-03T00:43:14.824Z SendDataTCPServer.js: TCP/IP server has received 82336 bytes of data
,2015-12-03T00:43:14.839Z SendDataTCPServer.js: TCP/IP server has received 91264 bytes of data
,2015-12-03T00:43:14.854Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 01:43:15.602 ThaliTest[2405:2240364] client session: connected
,2015-12-03 01:43:15.604 ThaliTest[2405:2240364] client session: stateChange:1->2 Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:43:15.607 ThaliTest[2405:2240364] client session: fireConnectCallback: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:43:15.60,8 ThaliTest[2405:2240364] jxcore: connect: success
2015-12-03T00:43:15.610Z SendDataConnector.js: CLIENT connected to 49868, error: null
2015-12-03T00:43:15.611Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:43:15.615 ThaliTest[2405:2239989] client: relay established
2015-12-03 01:43:15.616 ThaliTest[2405:2239989] client: new accepted socket: 0x1827a020
,2015-12-03T00:43:15.628Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T00:43:15.932Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-03T00:43:16.030Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-03T00:43:16.030Z SendDataConnector.js: got all data for this round
oneRoundDownNow
oneRoundDownNow:2
,2015-12-03T00:43:16.031Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T00:43:16.031Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 01:43:16.032 ThaliTest[2405:2240121] jxcore: disconnect
,2015-12-03 01:43:16.032 ThaliTest[2405:2240121] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:43:16.033 ThaliTest[2405:2240121] client session: disconnect
,2015-12-03 01:43:16.033 ThaliTest[2405:2240121] client session: stateChange:2->0 Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:43:16.089 ThaliTest[2405:2240121] jxcore: disconnect: success
,2015-12-03T00:43:16.091Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7682.INb6UQ==
,---- round done--------
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
        reading: true,
        slab_0x14595fc0: null },
     _readableState: 
      { highWaterMark: 16384,
        buffer: [],
        length: 0,
        pipes: null,
        pipesCount: 0,
        flowing: false,
        ended: false,
        endEmitted: false,
        reading: true,
        calledRead: true,
        sync: false,
        needReadable: true,
        emittedReadable: false,
        readableListening: false,
        objectMode: false,
        de,faultEncoding: 'utf8',
        ranOut: false,
        awaitDrain: 0,
        readingMore: false,
        decoder: null,
        encoding: null },
     readable: true,
     domain: null,
     _events: 
      { end: [Object],
        finish: [Funct,ion: onSocketFinish],
        _socketEnd: [Function: onSocketEnd],
        data: [Function],
        readable: [Function],
        error: [Function] },
     _maxListeners: 10,
     _writableState: 
      { highWaterMark: 16384,
        objectMode: ,false,
        needDrain: false,
        ending: true,
        ended: true,
        finished: true,
        decodeStrings: false,
        defaultEncoding: 'utf8',
        length: 0,
        writing: false,
        sync: false,
        bufferProce,ssing: false,
        onwrite: [Function],
        writecb: null,
        writelen: 0,
        buffer: [],
        errorEmitted: false },
     writable: false,
     allowHalfOpen: false,
     onend: null,
     destroyed: false,
     bytesRead: 30,,
     _bytesDispatched: 50000,
     _pendingData: null,
     _pendingEncoding: '',
     __ec_int: true,
     ___timerId: 1,
     pipe: [Function],
     addListener: [Function: addListener],
     on: [Function: addListener],
     pause: [Function],,
     resume: [Function],
     read: [Function],
     _consuming: true },
  reTryTimer: null,
  receivedCounter: 100000,
  tryRounds: 0,
  resultArray: [],
  connectionCount: 0,
  _events: { done: [Function], debug: [Function] },
  peer: null,
,  startTime: Thu Dec 03 2015 01:43:16 GMT+0100 (CET),
  endTime: Thu Dec 03 2015 01:43:16 GMT+0100 (CET),
  endReason: '',
  dataTimerId: null }
done, now sending data to server
CoordinatorConnector-debug: sendData
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT5704","time":51954,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT2613.bcJOyQ==","time":42256,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-,Iphone5-1_PT8796.xJ9gmA==","time":3140,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT2613.ais2pw==","time":3352,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataRecei,ved":100000},{"name":"Apple-IpadAir2-1_PT7682.INb6UQ==","time":2925,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 3352 ms, 99% : 3352 ms, 95 : 3352 ms, 90% : 3352 ms.
,Result count 3, range 2925 ms to  3352 ms.
,sendList failed peers count : 1 [25 %]
,- Peer ID : Apple-Iphone6-1_PT2613.bcJOyQ==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-12-03T00:43:16.105Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T00:43:16.105Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 01:43:25.071 ThaliTest[2405:2240364] server session: not connected Apple-Iphone5-1_PT8796
,2015-12-03 01:43:35.203 ThaliTest[2405:2239989] multipeer session: reset timer
2015-12-03 01:43:35.204 ThaliTest[2405:2239989] multipeer session: stop timer
2015-12-03 01:43:35.204 ThaliTest[2405:2239989] multipeer session: start timer: 0x14565fe0
2015-,12-03 01:43:35.205 ThaliTest[2405:2239989] server: disconnecting to refresh session (Apple-Iphone5-1_PT8796)
2015-12-03 01:43:35.206 ThaliTest[2405:2239989] server session: disconnect
2015-12-03 01:43:35.206 ThaliTest[2405:2239989] server session: stateC,hange:2->0 Apple-Iphone5-1_PT8796
,2015-12-03 01:43:35.212 ThaliTest[2405:2239989] server session: connect
2015-12-03 01:43:35.212 ThaliTest[2405:2239989] server session: stateChange:0->1 Apple-Iphone5-1_PT8796
,2015-12-03T00:43:35.220Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 01:43:35.224 ThaliTest[2405:2239989] server: accepting invitation Apple-Iphone5-1_PT8796
,2015-12-03 01:43:37.676 ThaliTest[2405:2240449] server session: connected
2015-12-03 01:43:37.677 ThaliTest[2405:2240449] server session: stateChange:1->2 Apple-Iphone5-1_PT8796
,2015-12-03 01:43:37.683 ThaliTest[2405:2239989] server relay: connected (to port: 49855)
,2015-12-03T00:43:37.695Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:43:37.856Z SendDataTCPServer.js: TCP/IP server has received 6944 bytes of data
,2015-12-03T00:43:37.870Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 01:43:47.793 ThaliTest[2405:2240448] server session: not connected Apple-Iphone5-1_PT8796
,2015-12-03 01:43:58.161 ThaliTest[2405:2239989] multipeer session: reset timer
2015-12-03 01:43:58.162 ThaliTest[2405:2239989] multipeer session: stop timer
2015-12-03 01:43:58.163 ThaliTest[2405:2239989] multipeer session: start timer: 0x14565fe0
2015-,12-03 01:43:58.163 ThaliTest[2405:2239989] server: disconnecting to refresh session (Apple-Iphone5-1_PT8796)
2015-12-03 01:43:58.164 ThaliTest[2405:2239989] server session: disconnect
2015-12-03 01:43:58.164 ThaliTest[2405:2239989] server session: stateChange:2->0 Apple-Iphone5-1_PT8796
,2015-12-03T00:43:58.179Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 01:43:58.232 ThaliTest[2405:2239989] server session: connect
2015-12-03 01:43:58.233 ThaliTest[2405:2239989] server session: stateChange:0->1 Apple-Iphone5-1_PT8796
,2015-12-03 01:43:58.244 ThaliTest[2405:2239989] server: accepting invitation Apple-Iphone5-1_PT8796
,2015-12-03 01:44:00.384 ThaliTest[2405:2240493] server session: connected
2015-12-03 01:44:00.384 ThaliTest[2405:2240493] server session: stateChange:1->2 Apple-Iphone5-1_PT8796
,2015-12-03 01:44:00.390 ThaliTest[2405:2239989] server relay: connected (to port: 49855)
,2015-12-03T00:44:00.399Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:44:00.744Z SendDataTCPServer.js: TCP/IP server has received 2976 bytes of data
,2015-12-03T00:44:00.794Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 01:44:10.684 ThaliTest[2405:2240495] server session: not connected Apple-Iphone5-1_PT8796
,2015-12-03 01:44:20.729 ThaliTest[2405:2239989] multipeer session: reset timer
2015-12-03 01:44:20.730 ThaliTest[2405:2239989] multipeer session: stop timer
2015-12-03 01:44:20.731 ThaliTest[2405:2239989] multipeer session: start timer: 0x14565fe0
2015-,12-03 01:44:20.731 ThaliTest[2405:2239989] server: disconnecting to refresh session (Apple-Iphone5-1_PT8796)
2015-12-03 01:44:20.732 ThaliTest[2405:2239989] server session: disconnect
2015-12-03 01:44:20.732 ThaliTest[2405:2239989] server session: stateC,hange:2->0 Apple-Iphone5-1_PT8796
2015-12-03 01:44:20.737 ThaliTest[2405:2239989] server session: connect
2015-12-03T00:44:20.738Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 01:44:20.737 ThaliTest[2405:2239989] server session: stateChange:0,->1 Apple-Iphone5-1_PT8796
,2015-12-03 01:44:20.757 ThaliTest[2405:2239989] server: accepting invitation Apple-Iphone5-1_PT8796
,2015-12-03 01:44:23.270 ThaliTest[2405:2240549] server session: connected
2015-12-03 01:44:23.271 ThaliTest[2405:2240549] server session: stateChange:1->2 Apple-Iphone5-1_PT8796
,2015-12-03 01:44:23.278 ThaliTest[2405:2239989] server relay: connected (to port: 49855)
,2015-12-03T00:44:23.286Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:44:23.361Z SendDataTCPServer.js: TCP/IP server has received 4960 bytes of data
,2015-12-03T00:44:23.375Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 01:44:33.385 ThaliTest[2405:2240548] server session: not connected Apple-Iphone5-1_PT8796
,2015-12-03 01:44:43.742 ThaliTest[2405:2239989] multipeer session: reset timer
2015-12-03 01:44:43.743 ThaliTest[2405:2239989] multipeer session: stop timer
2015-12-03 01:44:43.744 ThaliTest[2405:2239989] multipeer session: start timer: 0x14565fe0
2015-,12-03 01:44:43.746 ThaliTest[2405:2239989] server: disconnecting to refresh session (Apple-Iphone5-1_PT8796)
2015-12-03 01:44:43.746 ThaliTest[2405:2239989] server session: disconnect
2015-12-03 01:44:43.747 ThaliTest[2405:2239989] server session: stateC,hange:2->0 Apple-Iphone5-1_PT8796
2015-12-03 01:44:43.751 ThaliTest[2405:2239989] server session: connect
2015-12-03 01:44:43.751 ThaliTest[2405:2239989] server session: stateChange:0->1 Apple-Iphone5-1_PT8796
2015-12-03T00:44:43.761Z SendDataTCPServer.,js: TCP/IP server is ended
,2015-12-03 01:44:43.777 ThaliTest[2405:2239989] server: accepting invitation Apple-Iphone5-1_PT8796
,2015-12-03 01:44:45.929 ThaliTest[2405:2240601] server session: connected
2015-12-03 01:44:45.930 ThaliTest[2405:2240601] server session: stateChange:1->2 Apple-Iphone5-1_PT8796
,2015-12-03 01:44:45.939 ThaliTest[2405:2239989] server relay: connected (to port: 49855)
,2015-12-03T00:44:45.947Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:44:46.023Z SendDataTCPServer.js: TCP/IP server has received 8928 bytes of data
,2015-12-03T00:44:46.037Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 01:44:53.197 ThaliTest[2405:2239989] multipeer session: reset timer
2015-12-03 01:44:53.198 ThaliTest[2405:2239989] multipeer session: stop timer
2015-12-03 01:44:53.199 ThaliTest[2405:2239989] multipeer session: start timer: 0x14565fe0
2015-,12-03 01:44:53.199 ThaliTest[2405:2239989] server session: connect
2015-12-03 01:44:53.200 ThaliTest[2405:2239989] server session: stateChange:0->1 Apple-Iphone6-1_PT2613
,2015-12-03 01:44:53.212 ThaliTest[2405:2239989] server: accepting invitation Apple-Iphone6-1_PT2613
,2015-12-03 01:44:55.600 ThaliTest[2405:2240596] server session: connected
,2015-12-03 01:44:55.603 ThaliTest[2405:2240596] server session: stateChange:1->2 Apple-Iphone6-1_PT2613
,2015-12-03 01:44:55.608 ThaliTest[2405:2239989] server relay: connected (to port: 49855)
,2015-12-03T00:44:55.618Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03 01:44:55.750 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:44:55.877Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-03T00:44:55.895Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-03T00:44:55.915Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-03T00:44:55.934Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-03T00:44:55.952Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 01:44:56.273 ThaliTest[2405:2240593] server session: not connected Apple-Iphone5-1_PT8796
,2015-12-03 01:45:02.053 ThaliTest[2405:2239989] multipeer session: reset timer
2015-12-03 01:45:02.054 ThaliTest[2405:2239989] multipeer session: stop timer
2015-12-03 01:45:02.054 ThaliTest[2405:2239989] multipeer session: start timer: 0x14565fe0
2015-,12-03 01:45:02.055 ThaliTest[2405:2239989] server session: connect
2015-12-03 01:45:02.056 ThaliTest[2405:2239989] server session: stateChange:0->1 Apple-IpadAir2-1_PT7682
,2015-12-03 01:45:02.069 ThaliTest[2405:2239989] server: accepting invitation Apple-IpadAir2-1_PT7682
,2015-12-03 01:45:02.696 ThaliTest[2405:2239989] client: lost peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:45:02.696 ThaliTest[2405:2239989] client session: onPeerLost: Apple-Iphone6-1_PT2613.ais2pw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 01:45:04.297 ThaliTest[2405:2240596] server session: connected
2015-12-03 01:45:04.298 ThaliTest[2405:2240596] server session: stateChange:1->2 Apple-IpadAir2-1_PT7682
,2015-12-03 01:45:04.303 ThaliTest[2405:2239989] server relay: connected (to port: 49855)
,2015-12-03T00:45:04.313Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:45:04.543Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-03T00:45:04.560Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-03T00:45:04.576Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-03T00:45:04.595Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-03T00:45:04.610Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-03T00:45:04.625Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 01:45:04.661 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 01:45:06.233 ThaliTest[2405:2240634] server session: not connected Apple-Iphone6-1_PT2613
,2015-12-03 01:45:14.684 ThaliTest[2405:2240596] server session: not connected Apple-IpadAir2-1_PT7682
,2015-12-03 01:45:16.707 ThaliTest[2405:2239989] multipeer session: reset timer
2015-12-03 01:45:16.708 ThaliTest[2405:2239989] multipeer session: stop timer
2015-12-03 01:45:16.709 ThaliTest[2405:2239989] multipeer session: start timer: 0x14565fe0
2015-,12-03 01:45:16.709 ThaliTest[2405:2239989] server: disconnecting to refresh session (Apple-Iphone6-1_PT2613)
2015-12-03 01:45:16.710 ThaliTest[2405:2239989] server session: disconnect
2015-12-03 01:45:16.710 ThaliTest[2405:2239989] server session: stateChange:2->0 Apple-Iphone6-1_PT2613
,2015-12-03 01:45:16.715 ThaliTest[2405:2239989] server session: connect
2015-12-03 01:45:16.716 ThaliTest[2405:2239989] server session: stateChange:0->1 Apple-Iphone6-1_PT2613
2015-12-03T00:45:16.717Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 01:45:16.727 ThaliTest[2405:2239989] server: accepting invitation Apple-Iphone6-1_PT2613
,2015-12-03 01:45:18.907 ThaliTest[2405:2240664] server session: connected
2015-12-03 01:45:18.907 ThaliTest[2405:2240664] server session: stateChange:1->2 Apple-Iphone6-1_PT2613
,2015-12-03 01:45:18.914 ThaliTest[2405:2239989] server relay: connected (to port: 49855)
2015-12-03T00:45:18.917Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:45:19.005Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-03T00:45:19.017Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 01:45:25.678 ThaliTest[2405:2239989] multipeer session: reset timer
2015-12-03 01:45:25.679 ThaliTest[2405:2239989] multipeer session: stop timer
2015-12-03 01:45:25.679 ThaliTest[2405:2239989] multipeer session: start timer: 0x14565fe0
2015-,12-03 01:45:25.680 ThaliTest[2405:2239989] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7682)
2015-12-03 01:45:25.680 ThaliTest[2405:2239989] server session: disconnect
2015-12-03 01:45:25.681 ThaliTest[2405:2239989] server session: state,Change:2->0 Apple-IpadAir2-1_PT7682
2015-12-03 01:45:25.685 ThaliTest[2405:2239989] server session: connect
2015-12-03 01:45:25.686 ThaliTest[2405:2239989] server session: stateChange:0->1 Apple-IpadAir2-1_PT7682
2015-12-03T00:45:25.688Z SendDataTCPServ,er.js: TCP/IP server is ended
,2015-12-03 01:45:25.707 ThaliTest[2405:2239989] server: accepting invitation Apple-IpadAir2-1_PT7682
,2015-12-03 01:45:28.033 ThaliTest[2405:2240684] server session: connected
2015-12-03 01:45:28.034 ThaliTest[2405:2240684] server session: stateChange:1->2 Apple-IpadAir2-1_PT7682
,2015-12-03 01:45:28.039 ThaliTest[2405:2239989] server relay: connected (to port: 49855)
2015-12-03T00:45:28.043Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:45:28.108Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 01:45:29.294 ThaliTest[2405:2240596] server session: not connected Apple-Iphone6-1_PT2613
,2015-12-03 01:45:38.204 ThaliTest[2405:2240664] server session: not connected Apple-IpadAir2-1_PT7682
,2015-12-03 01:45:39.304 ThaliTest[2405:2239989] multipeer session: reset timer
2015-12-03 01:45:39.305 ThaliTest[2405:2239989] multipeer session: stop timer
2015-12-03 01:45:39.306 ThaliTest[2405:2239989] multipeer session: start timer: 0x14565fe0
2015-,12-03 01:45:39.306 ThaliTest[2405:2239989] server: disconnecting to refresh session (Apple-Iphone6-1_PT2613)
2015-12-03 01:45:39.307 ThaliTest[2405:2239989] server session: disconnect
2015-12-03 01:45:39.308 ThaliTest[2405:2239989] server session: stateC,hange:2->0 Apple-Iphone6-1_PT2613
2015-12-03 01:45:39.311 ThaliTest[2405:2239989] server session: connect
2015-12-03 01:45:39.312 ThaliTest[2405:2239989] server session: stateChange:0->1 Apple-Iphone6-1_PT2613
,2015-12-03T00:45:39.329Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 01:45:39.336 ThaliTest[2405:2239989] server: accepting invitation Apple-Iphone6-1_PT2613
,2015-12-03 01:45:41.537 ThaliTest[2405:2240684] server session: connected
2015-12-03 01:45:41.537 ThaliTest[2405:2240684] server session: stateChange:1->2 Apple-Iphone6-1_PT2613
,2015-12-03 01:45:41.546 ThaliTest[2405:2239989] server relay: connected (to port: 49855)
,2015-12-03T00:45:41.556Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:45:41.645Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 01:45:49.245 ThaliTest[2405:2239989] multipeer session: reset timer
2015-12-03 01:45:49.246 ThaliTest[2405:2239989] multipeer session: stop timer
2015-12-03 01:45:49.247 ThaliTest[2405:2239989] multipeer session: start timer: 0x14565fe0
2015-,12-03 01:45:49.247 ThaliTest[2405:2239989] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7682)
2015-12-03 01:45:49.248 ThaliTest[2405:2239989] server session: disconnect
2015-12-03 01:45:49.248 ThaliTest[2405:2239989] server session: state,Change:2->0 Apple-IpadAir2-1_PT7682
2015-12-03 01:45:49.252 ThaliTest[2405:2239989] server session: connect
2015-12-03 01:45:49.252 ThaliTest[2405:2239989] server session: stateChange:0->1 Apple-IpadAir2-1_PT7682
,2015-12-03T00:45:49.267Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 01:45:49.273 ThaliTest[2405:2239989] server: accepting invitation Apple-IpadAir2-1_PT7682
,2015-12-03 01:45:51.582 ThaliTest[2405:2240707] server session: connected
2015-12-03 01:45:51.583 ThaliTest[2405:2240707] server session: stateChange:1->2 Apple-IpadAir2-1_PT7682
,2015-12-03 01:45:51.591 ThaliTest[2405:2239989] server relay: connected (to port: 49855)
2015-12-03T00:45:51.593Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:45:51.669Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-03T00:45:51.684Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 01:45:51.834 ThaliTest[2405:2240596] server session: not connected Apple-Iphone6-1_PT2613
,2015-12-03 01:46:01.792 ThaliTest[2405:2240684] server session: not connected Apple-IpadAir2-1_PT7682
,2015-12-03 01:46:02.150 ThaliTest[2405:2239989] multipeer session: reset timer
2015-12-03 01:46:02.151 ThaliTest[2405:2239989] multipeer session: stop timer
2015-12-03 01:46:02.152 ThaliTest[2405:2239989] multipeer session: start timer: 0x14565fe0
2015-,12-03 01:46:02.153 ThaliTest[2405:2239989] server: disconnecting to refresh session (Apple-Iphone6-1_PT2613)
2015-12-03 01:46:02.153 ThaliTest[2405:2239989] server session: disconnect
2015-12-03 01:46:02.154 ThaliTest[2405:2239989] server session: stateC,hange:2->0 Apple-Iphone6-1_PT2613
2015-12-03 01:46:02.158 ThaliTest[2405:2239989] server session: connect
2015-12-03 01:46:02.159 ThaliTest[2405:2239989] server session: stateChange:0->1 Apple-Iphone6-1_PT2613
,2015-12-03 01:46:02.168 ThaliTest[2405:2239989] server: accepting invitation Apple-Iphone6-1_PT2613
2015-12-03T00:46:02.170Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 01:46:04.360 ThaliTest[2405:2240744] server session: connected
2015-12-03 01:46:04.361 ThaliTest[2405:2240744] server session: stateChange:1->2 Apple-Iphone6-1_PT2613
,2015-12-03 01:46:04.368 ThaliTest[2405:2239989] server relay: connected (to port: 49855)
,2015-12-03T00:46:04.375Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:46:04.465Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 01:46:12.735 ThaliTest[2405:2239989] multipeer session: reset timer
2015-12-03 01:46:12.736 ThaliTest[2405:2239989] multipeer session: stop timer
2015-12-03 01:46:12.737 ThaliTest[2405:2239989] multipeer session: start timer: 0x14565fe0
2015-,12-03 01:46:12.737 ThaliTest[2405:2239989] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7682)
,2015-12-03 01:46:12.738 ThaliTest[2405:2239989] server session: disconnect
2015-12-03 01:46:12.739 ThaliTest[2405:2239989] server session: stateChange:2->0 Apple-IpadAir2-1_PT7682
,2015-12-03 01:46:12.744 ThaliTest[2405:2239989] server session: connect
2015-12-03 01:46:12.745 ThaliTest[2405:2239989] server session: stateChange:0->1 Apple-IpadAir2-1_PT7682
,2015-12-03T00:46:12.752Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 01:46:12.753 ThaliTest[2405:2239989] server: accepting invitation Apple-IpadAir2-1_PT7682
,2015-12-03 01:46:14.472 ThaliTest[2405:2240707] server session: not connected Apple-Iphone6-1_PT2613
,2015-12-03 01:46:15.032 ThaliTest[2405:2240707] server session: connected
2015-12-03 01:46:15.033 ThaliTest[2405:2240707] server session: stateChange:1->2 Apple-IpadAir2-1_PT7682
2015-12-03 01:46:15.037 ThaliTest[2405:2239989] server relay: connected (to, port: 49855)
,2015-12-03T00:46:15.049Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:46:15.090Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 01:46:24.876 ThaliTest[2405:2239989] multipeer session: reset timer
2015-12-03 01:46:24.877 ThaliTest[2405:2239989] multipeer session: stop timer
2015-12-03 01:46:24.877 ThaliTest[2405:2239989] multipeer session: start timer: 0x14565fe0
2015-,12-03 01:46:24.878 ThaliTest[2405:2239989] server: disconnecting to refresh session (Apple-Iphone6-1_PT2613)
2015-12-03 01:46:24.878 ThaliTest[2405:2239989] server session: disconnect
2015-12-03 01:46:24.880 ThaliTest[2405:2239989] server session: stateC,hange:2->0 Apple-Iphone6-1_PT2613
2015-12-03 01:46:24.884 ThaliTest[2405:2239989] server session: connect
2015-12-03 01:46:24.885 ThaliTest[2405:2239989] server session: stateChange:0->1 Apple-Iphone6-1_PT2613
,2015-12-03T00:46:24.897Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 01:46:24.903 ThaliTest[2405:2239989] server: accepting invitation Apple-Iphone6-1_PT2613
,2015-12-03 01:46:25.381 ThaliTest[2405:2240745] server session: not connected Apple-IpadAir2-1_PT7682
,2015-12-03 01:46:27.154 ThaliTest[2405:2240744] server session: connected
2015-12-03 01:46:27.155 ThaliTest[2405:2240744] server session: stateChange:1->2 Apple-Iphone6-1_PT2613
,2015-12-03 01:46:27.162 ThaliTest[2405:2239989] server relay: connected (to port: 49855)
,2015-12-03T00:46:27.172Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:46:27.262Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-03T00:46:27.274Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 01:46:37.004 ThaliTest[2405:2239989] multipeer session: reset timer
2015-12-03 01:46:37.005 ThaliTest[2405:2239989] multipeer session: stop timer
2015-12-03 01:46:37.006 ThaliTest[2405:2239989] multipeer session: start timer: 0x14565fe0
2015-,12-03 01:46:37.007 ThaliTest[2405:2239989] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7682)
2015-12-03 01:46:37.007 ThaliTest[2405:2239989] server session: disconnect
2015-12-03 01:46:37.008 ThaliTest[2405:2239989] server session: state,Change:2->0 Apple-IpadAir2-1_PT7682
2015-12-03 01:46:37.013 ThaliTest[2405:2239989] server session: connect
2015-12-03 01:46:37.013 ThaliTest[2405:2239989] server session: stateChange:0->1 Apple-IpadAir2-1_PT7682
,2015-12-03T00:46:37.026Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 01:46:37.033 ThaliTest[2405:2239989] server: accepting invitation Apple-IpadAir2-1_PT7682
,2015-12-03 01:46:37.457 ThaliTest[2405:2240776] server session: not connected Apple-Iphone6-1_PT2613
,2015-12-03 01:46:39.378 ThaliTest[2405:2240776] server session: connected
2015-12-03 01:46:39.379 ThaliTest[2405:2240776] server session: stateChange:1->2 Apple-IpadAir2-1_PT7682
,2015-12-03 01:46:39.386 ThaliTest[2405:2239989] server relay: connected (to port: 49855)
,2015-12-03T00:46:39.396Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:46:39.435Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 01:46:49.491 ThaliTest[2405:2240776] server session: not connected Apple-IpadAir2-1_PT7682
,2015-12-03 01:47:02.600 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:47:07.008 ThaliTest[2405:2239989] multipeer session: restart
,2015-12-03 01:47:07.033 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:47:07.036 ThaliTest[2405:2239989] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:47:07.036 ThaliTest[2405:2239989] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:47:31.424 ThaliTest[2405:2239989] client: lost peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:47:31.425 ThaliTest[2405:2239989] client session: onPeerLost: Apple-Iphone6-1_PT2613.ais2pw==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":false}]
2015-12-03 01:47:31.428 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 01:47:34.569 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:47:37.006 ThaliTest[2405:2239989] multipeer session: restart
,2015-12-03 01:47:37.029 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:47:37.032 ThaliTest[2405:2239989] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:47:37.033 ThaliTest[2405:2239989] client,: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:48:01.827 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:48:04.447 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:48:07.006 ThaliTest[2405:2239989] multipeer session: restart
,2015-12-03 01:48:07.031 ThaliTest[2405:2239989] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:48:07.032 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:48:07.033 ThaliTest[2405:2239989] clien,t: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: disconnect:transport close
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:48:32.361 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:48:34.458 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:48:37.007 ThaliTest[2405:2239989] multipeer session: restart
,2015-12-03 01:48:37.031 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:48:37.034 ThaliTest[2405:2239989] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:48:37.035 ThaliTest[2405:2239989] client,: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
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
,2015-12-03 01:49:04.359 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:49:07.006 ThaliTest[2405:2239989] multipeer session: restart
,2015-12-03 01:49:07.029 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:49:07.031 ThaliTest[2405:2239989] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:49:07.033 ThaliTest[2405:2239989] clien,t: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
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
,2015-12-03 01:49:34.604 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:49:37.006 ThaliTest[2405:2239989] multipeer session: restart
,2015-12-03 01:49:37.028 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:49:37.033 ThaliTest[2405:2239989] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:49:37.035 ThaliTest[2405:2239989] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
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
,2015-12-03 01:50:01.349 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:50:04.480 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:50:07.005 ThaliTest[2405:2239989] multipeer session: restart
,2015-12-03 01:50:07.023 ThaliTest[2405:2239989] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:50:07.024 ThaliTest[2405:2239989] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:50:07.024 ThaliTest[2405:2239989] clien,t: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:50:31.735 ThaliTest[2405:2239989] client: lost peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:50:31.735 ThaliTest[2405:2239989] client session: onPeerLost: Apple-Iphone6-1_PT2613.ais2pw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:50:37.005 ThaliTest[2405:2239989] multipeer session: restart
,2015-12-03 01:50:37.028 ThaliTest[2405:2239989] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:50:37.029 ThaliTest[2405:2239989] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
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
,2015-12-03 01:51:07.005 ThaliTest[2405:2239989] multipeer session: restart
,2015-12-03 01:51:07.026 ThaliTest[2405:2239989] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:51:07.029 ThaliTest[2405:2239989] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
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
,2015-12-03 01:51:37.005 ThaliTest[2405:2239989] multipeer session: restart
,2015-12-03 01:51:37.027 ThaliTest[2405:2239989] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:51:37.028 ThaliTest[2405:2239989] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
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
,2015-12-03 01:52:07.005 ThaliTest[2405:2239989] multipeer session: restart
,2015-12-03 01:52:07.029 ThaliTest[2405:2239989] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:52:07.031 ThaliTest[2405:2239989] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
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
,2015-12-03 01:52:37.005 ThaliTest[2405:2239989] multipeer session: restart
,2015-12-03 01:52:37.025 ThaliTest[2405:2239989] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:52:37.027 ThaliTest[2405:2239989] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
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
,2015-12-03 01:53:07.003 ThaliTest[2405:2239989] multipeer session: restart
,2015-12-03 01:53:07.024 ThaliTest[2405:2239989] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:53:07.026 ThaliTest[2405:2239989] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
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
,2015-12-03 01:53:37.003 ThaliTest[2405:2239989] multipeer session: restart
,2015-12-03 01:53:37.026 ThaliTest[2405:2239989] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:53:37.028 ThaliTest[2405:2239989] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,",_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:54:07.003 ThaliTest[2405:2239989] multipeer session: restart
,2015-12-03 01:54:07.024 ThaliTest[2405:2239989] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:54:07.027 ThaliTest[2405:2239989] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
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
,2015-12-03 01:54:37.003 ThaliTest[2405:2239989] multipeer session: restart
,2015-12-03 01:54:37.028 ThaliTest[2405:2239989] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:54:37.031 ThaliTest[2405:2239989] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
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
,2015-12-03 01:55:07.003 ThaliTest[2405:2239989] multipeer session: restart
,2015-12-03 01:55:07.026 ThaliTest[2405:2239989] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:55:07.027 ThaliTest[2405:2239989] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
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
,2015-12-03 01:55:37.002 ThaliTest[2405:2239989] multipeer session: restart
2015-12-03 01:55:37.021 ThaliTest[2405:2239989] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:55:37.023 ThaliTest[2405:2239989] client: found peer: Apple-Ipho,ne5-1_PT8796.xJ9gmA==
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
,2015-12-03 01:56:07.002 ThaliTest[2405:2239989] multipeer session: restart
,2015-12-03 01:56:07.024 ThaliTest[2405:2239989] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:56:07.027 ThaliTest[2405:2239989] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
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
,2015-12-03 01:56:37.002 ThaliTest[2405:2239989] multipeer session: restart
,2015-12-03 01:56:37.023 ThaliTest[2405:2239989] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:56:37.026 ThaliTest[2405:2239989] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
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
,2015-12-03 01:57:07.002 ThaliTest[2405:2239989] multipeer session: restart
,2015-12-03 01:57:07.026 ThaliTest[2405:2239989] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:57:07.027 ThaliTest[2405:2239989] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
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
,2015-12-03 01:57:37.002 ThaliTest[2405:2239989] multipeer session: restart
,2015-12-03 01:57:37.021 ThaliTest[2405:2239989] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:57:37.023 ThaliTest[2405:2239989] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
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
,2015-12-03 01:58:07.002 ThaliTest[2405:2239989] multipeer session: restart
2015-12-03 01:58:07.008 ThaliTest[2405:2239989] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Fi,rst throw call stack:
(0x2a8a745f 0x3876ac8b 0x2a7c4c53 0x2c829d95 0x2a3c4297 0x2a3c3b11 0x2a33d693 0x2a86dfbf 0x2a86d3cf 0x2a86ba35 0x2a7b93b1 0x2a7b91c3 0x31da6201 0x2de2343d 0xad5e3 0x38cf6aaf)
libc++abi.dylib: terminating with uncaught exception of t,ype NSException
,* thread #1: tid = 0x222df5, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
  * frame #0: 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x38e3ecc6 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x38d5c908 libsystem_c.dylib`abort + 76
    frame #3: 0x3808c9c8 libc++abi.dylib`<redacted> + 88
    frame #4: 0x380a6670 libc++abi.dylib`<redacted> + 268
    frame #5: 0x3876af24 libobjc.A.dylib`<redacted> + 192
    frame #6: 0x380a3de2 libc++abi.dylib`<redacted> + 78
    frame #7: 0x380a38ae libc++abi.dylib`__cxa_rethrow + 102
    frame #8: 0x3876add2 libobjc.A.dylib`objc_exception_rethrow + 42
    frame #9: 0x2a7b944c CoreFoundation`CFRunLoopRunSpecific + 632
    frame #10: 0x2a7b91c2 CoreFoundation`CFRunLoopRunInMode + 106
    frame #11: 0x31da6200 GraphicsServices`GSEventRunModal + 136
    frame #12: 0x2de2343c UIKit`UIApplicationMain + 1440
    frame #13: 0x000ad5e2 ThaliTest`main + 50

```
