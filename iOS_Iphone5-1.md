#### Test 506502782b2305a_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502782b2305a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B738CA30-1F46-41EA-8FCF-EE9B57EBFEC9/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/B738CA30-1F46-41EA-8FCF-EE9B57EBFEC9/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502782b2305a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502782b2305a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/4013F296-2AF2-4227-8C30-A2F26E9CE568/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60120"
,(lldb)     command script import "/tmp/B738CA30-1F46-41EA-8FCF-EE9B57EBFEC9/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 01:42:08.595 ThaliTest[1177:60b] Apache Cordova native platform version 3.9.2 is starting.
2015-12-03 01:42:08.598 ThaliTest[1177:60b] Multi-tasking -> Device: YES, App: YES
,2015-12-03 01:42:08.606 ThaliTest[1177:60b] Unlimited access to network resources
,2015-12-03 01:42:08.614 ThaliTest[1177:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 01:42:19.315 ThaliTest[1177:60b] Resetting plugins due to page load.
,2015-12-03 01:42:20.190 ThaliTest[1177:60b] Finished load of: file:///var/mobile/Applications/4013F296-2AF2-4227-8C30-A2F26E9CE568/ThaliTest.app/www/index.html
,2015-12-03 01:42:20.368 ThaliTest[1177:60b] JXcore Cordova plugin initializing
,2015-12-03 01:42:20.370 ThaliTest[1177:6707] JXcore instance initializing
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
  addressList: [] }
testFindPeers created [object Object]
serverPort is 8876
,2015-12-03 01:42:23.128 ThaliTest[1177:6707] jxcore: startBroadcasting
,2015-12-03 01:42:23.136 ThaliTest[1177:6707] server: starting Apple-Iphone5-1_PT8796./19b4A==
,2015-12-03 01:42:23.138 ThaliTest[1177:6707] multipeer session: start timer: 0x1b328340
2015-12-03 01:42:23.139 ThaliTest[1177:6707] THEMultipeerSession initialized peer Apple-Iphone5-1_PT8796
2015-12-03 01:42:23.139 ThaliTest[1177:6707] jxcore: startBro,adcasting: success
,StartBroadcasting started ok
,2015-12-03 01:42:23.596 ThaliTest[1177:60b] client: found peer: Apple-Iphone6-1_PT2613.bcJOyQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.bcJOyQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT2613.bcJOyQ==, peerAvailable: true
weAreDoneNow
,done, now sending data to server
,CoordinatorConnector-debug: sendData
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT8796","time":472,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1_PT2613.bcJOyQ==","peerAvailable":true,"time":471}]}
,peersList : 100% : 471 ms, 99% : 471 ms, 95 : 471 ms, 90% : 471 ms.
Result count 1, range 471 ms to  471 ms.
,2015-12-03 01:42:23.607 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.8qCfew==
,CoordinatorConnector-debug: stop:undefined
,stop tests now !
stop current!
testFindPeers stopped
2015-12-03 01:42:24.145 ThaliTest[1177:6707] jxcore: stopBroadcasting
,2015-12-03 01:42:24.146 ThaliTest[1177:6707] THEMultipeerSession stopping peer
2015-12-03 01:42:24.146 ThaliTest[1177:6707] multipeer session: stop timer
,2015-12-03 01:42:24.147 ThaliTest[1177:6707] jxcore: stopBroadcasting: success
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
  addressLis,t: [] }
testSendData created [object Object], bt-address length : 0
,check server
serverPort is 61650
,2015-12-03 01:42:24.200 ThaliTest[1177:6707] jxcore: startBroadcasting
,2015-12-03 01:42:24.204 ThaliTest[1177:6707] server: starting Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:42:24.204 ThaliTest[1177:6707] multipeer session: start timer: 0x1b28f1c0
2015-12-03 01:42:24.205 ThaliTest[1177:6707] THEMultipeerSession initialized peer Apple-Iphone5-1_PT8796
2015-12-03 01:42:24.206 ThaliTest[1177:6707] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-03T00:42:24.209Z SendDataTCPServer.js: TCP/IP server is bound to port: 61650
,2015-12-03 01:42:24.216 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.8qCfew==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.8qCfew==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
2015-12-03 01:42:24.219 ThaliTest[1177:60b] client: found peer: Apple-Iphone6-1_PT2613.bcJOyQ==,
device[1]: Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03T00:42:24.220Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03T00:42:24.221Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.8qCfew==,
2015-12-03T00:42:24.221Z SendDataConnector.js: do connect now
2015-12-03 01:42:24.221 ThaliTest[1177:60b] client: found peer: Apple-Iphone5-1_PT8796./19b4A==
,2015-12-03 01:42:24.223 ThaliTest[1177:6707] jxcore: connect Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03 01:42:24.224 ThaliTest[1177:6707] client session: connect
2015-12-03 01:42:24.225 ThaliTest[1177:6707] client session: stateChange:0->1 Apple-Iphone5s-1_PT5704.8qCfew==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.bcJOyQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8796./19b4A==","peerName":"(null)",,"peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 01:42:25.355 ThaliTest[1177:60b] client: lost peer: Apple-Iphone5-1_PT8796./19b4A==
2015-12-03 01:42:25.356 ThaliTest[1177:60b] client session: onPeerLost: Apple-Iphone5-1_PT8796./19b4A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8796./19b4A==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 01:42:25.359 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 01:42:25.365 ThaliTest[1177:60b] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 01:42:26.404 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7682.INb6UQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 01:42:27.662 ThaliTest[1177:60b] client: lost peer: Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03 01:42:27.663 ThaliTest[1177:60b] client session: onPeerLost: Apple-Iphone6-1_PT2613.bcJOyQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.bcJOyQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 01:42:31.760 ThaliTest[1177:60b] client: lost peer: Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03 01:42:31.762 ThaliTest[1177:60b] client session: onPeerLost: Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:42:31.763 ThaliTest[1177:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03 01:42:31.764 ThaliTest[1177:60b] client session: disconnect
,2015-12-03 01:42:31.765 ThaliTest[1177:60b] client session: stateChange:1->0 Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:42:31.880 ThaliTest[1177:60b] client session: fireConnectCallback: Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:42:31.881 ThaliTest[1177:60b] jxcore: connect: fail: Peer disconnected
,2015-12-03T00:42:31.884Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-12-03T00:42:31.884Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-03T00:42:31.885Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.8qCfew==","peerName":"(null)","peerAvailable":false}]
,2015-12-03T00:42:36.894Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03T00:42:36.895Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:42:41.898 ThaliTest[1177:6707] jxcore: disconnect
,2015-12-03 01:42:41.900 ThaliTest[1177:6707] jxcore: disconnect: fail
2015-12-03T00:42:41.902Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03T00:42:41.902Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT5704.8qCfew== with availability status: true
2015-12-03T00:42:41.902Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03T00:42:41.903Z SendDataConnector.js: do connect now
,2015-12-03 01:42:41.903 ThaliTest[1177:6707] jxcore: connect Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:42:41.904 ThaliTest[1177:6707] client: connect: unreachable Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:42:41.904 ThaliTest[1177:6707] jxcore: connect: fail: Peer unreachable
2015-12-03T00:42:41.905Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-03T00:42:41.905Z SendDataConnector.js: CLIENT Can not Connect: Peer, unreachable
,2015-12-03T00:42:41.906Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:42:46.912Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03T00:42:46.912Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:42:51.923 ThaliTest[1177:6707] jxcore: disconnect
,2015-12-03 01:42:51.925 ThaliTest[1177:6707] jxcore: disconnect: fail
2015-12-03T00:42:51.926Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03T00:42:51.927Z SendDataConnector.js: Connect (retry cou,nt 2) to peer Apple-Iphone5s-1_PT5704.8qCfew== with availability status: true
2015-12-03T00:42:51.927Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03T00:42:51.927Z SendDataConnector.js: do connect now
,2015-12-03 01:42:51.928 ThaliTest[1177:6707] jxcore: connect Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:42:51.928 ThaliTest[1177:6707] client: connect: unreachable Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:42:51.929 ThaliTest[1177:6707] jxcore: connect: fail: Peer unreachable
2015-12-03T00:42:51.930Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-03T00:42:51.930Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-03T00:42:51.930Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03 01:42:54.206 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:42:54.217 ThaliTest[1177:60b] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:42:54.219 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:42:54.219 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03T00:42:56.933Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03T00:42:56.933Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:43:01.935 ThaliTest[1177:6707] jxcore: disconnect
,2015-12-03 01:43:01.937 ThaliTest[1177:6707] jxcore: disconnect: fail
2015-12-03T00:43:01.938Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03T00:43:01.939Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT5704.8qCfew== with availability status: true
2015-12-03T00:43:01.939Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03T00:43:01.939Z SendDataConnector.js: do connect now
,2015-12-03 01:43:01.940 ThaliTest[1177:6707] jxcore: connect Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:43:01.940 ThaliTest[1177:6707] client: connect: unreachable Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:43:01.941 ThaliTest[1177:6707] jxcore: connect: fail: Peer unreachable
2015-12-03T00:43:01.942Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-03T00:43:01.942Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-03T00:43:01.942Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03 01:43:03.801 ThaliTest[1177:60b] client: lost peer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:43:03.802 ThaliTest[1177:60b] client session: onPeerLost: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:43:03.804 ThaliTest[1177:60b] client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ipho,ne6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
2015-12-03 01:43:03.805 ThaliTest[1177:60b] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03T00:43:06.949Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03T00:43:06.950Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:43:07.326 ThaliTest[1177:60b] multipeer session: reset timer
2015-12-03 01:43:07.328 ThaliTest[1177:60b] multipeer session: stop timer
2015-12-03 01:43:07.329 ThaliTest[1177:60b] multipeer session: start timer: 0x1b28f1c0
,2015-12-03 01:43:07.329 ThaliTest[1177:60b] server session: connect
2015-12-03 01:43:07.330 ThaliTest[1177:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT5704
,2015-12-03 01:43:07.334 ThaliTest[1177:60b] server: accepting invitation Apple-Iphone5s-1_PT5704
,2015-12-03 01:43:07.891 ThaliTest[1177:60b] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 01:43:07.949 ThaliTest[1177:60b] multipeer session: reset timer
,2015-12-03 01:43:07.950 ThaliTest[1177:60b] multipeer session: stop timer
,2015-12-03 01:43:07.951 ThaliTest[1177:60b] multipeer session: start timer: 0x1b28f1c0
,2015-12-03 01:43:07.952 ThaliTest[1177:60b] server session: connect
,2015-12-03 01:43:07.952 ThaliTest[1177:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT7682
,2015-12-03 01:43:07.956 ThaliTest[1177:60b] server: accepting invitation Apple-IpadAir2-1_PT7682
,2015-12-03 01:43:08.012 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 01:43:09.873 ThaliTest[1177:8307] server session: connected
,2015-12-03 01:43:09.875 ThaliTest[1177:8307] server session: stateChange:1->2 Apple-Iphone5s-1_PT5704
,2015-12-03 01:43:09.911 ThaliTest[1177:60b] server relay: connected (to port: 61650)
,2015-12-03T00:43:09.916Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03 01:43:10.072 ThaliTest[1177:60b] multipeer session: reset timer
,2015-12-03 01:43:10.073 ThaliTest[1177:60b] multipeer session: stop timer
2015-12-03 01:43:10.074 ThaliTest[1177:60b] multipeer session: start timer: 0x1b28f1c0
,2015-12-03 01:43:10.075 ThaliTest[1177:60b] server session: connect
2015-12-03 01:43:10.076 ThaliTest[1177:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT2613
,2015-12-03 01:43:10.079 ThaliTest[1177:60b] server: accepting invitation Apple-Iphone6-1_PT2613
,2015-12-03T00:43:10.206Z SendDataTCPServer.js: TCP/IP server has received 12998 bytes of data
,2015-12-03T00:43:10.220Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-03T00:43:10.237Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 01:43:10.268 ThaliTest[1177:9a1b] server session: not connected Apple-Iphone5s-1_PT5704
2015-12-03 01:43:10.270 ThaliTest[1177:9a1b] server session: connected
,2015-12-03 01:43:10.271 ThaliTest[1177:9a1b] server session: stateChange:1->2 Apple-IpadAir2-1_PT7682
,2015-12-03T00:43:10.274Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03 01:43:10.274 ThaliTest[1177:60b] server relay: connected (to port: 61650)
,2015-12-03T00:43:10.508Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-03T00:43:10.522Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-03T00:43:10.537Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 01:43:10.562 ThaliTest[1177:8307] server session: not connected Apple-IpadAir2-1_PT7682
,2015-12-03 01:43:11.955 ThaliTest[1177:6707] jxcore: disconnect
,2015-12-03 01:43:11.956 ThaliTest[1177:6707] jxcore: disconnect: fail
2015-12-03T00:43:11.958Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03T00:43:11.959Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT5704.8qCfew== with availability status: true
2015-12-03T00:43:11.959Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.8qCfew==
2015,-12-03T00:43:11.959Z SendDataConnector.js: do connect now
,2015-12-03 01:43:11.959 ThaliTest[1177:6707] jxcore: connect Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:43:11.960 ThaliTest[1177:6707] client: connect: unreachable Apple-Iphone5s-1_PT5704.8qCfew==
,2015-12-03 01:43:11.961 ThaliTest[1177:6707] jxcore: connect: fail: Peer unreachable
2015-12-03T00:43:11.961Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-03T00:43:11.962Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
oneRoundDownNow:2
,2015-12-03T00:43:11.963Z SendDataConnector.js: CLIENT Stop now
,2015-12-03 01:43:11.963 ThaliTest[1177:6707] jxcore: disconnect
,2015-12-03 01:43:11.964 ThaliTest[1177:6707] jxcore: disconnect: fail
2015-12-03T00:43:11.965Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.8qCfew==
,---- round done--------
,device[2]: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:43:11.966Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:43:11.966Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03T00:43:11.966Z SendDataConnector.js: do connect now
,2015-12-03 01:43:11.967 ThaliTest[1177:6707] jxcore: connect Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:43:11.967 ThaliTest[1177:6707] client session: connect
,2015-12-03 01:43:11.968 ThaliTest[1177:6707] client session: stateChange:0->1 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:43:12.624 ThaliTest[1177:4e0b] server session: connected
2015-12-03 01:43:12.625 ThaliTest[1177:4e0b] server session: stateChange:1->2 Apple-Iphone6-1_PT2613
,2015-12-03 01:43:12.629 ThaliTest[1177:60b] server relay: connected (to port: 61650)
,2015-12-03T00:43:12.637Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:43:13.113Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-03T00:43:13.126Z SendDataTCPServer.js: TCP/IP server has received 47896 bytes of data
,2015-12-03T00:43:13.143Z SendDataTCPServer.js: TCP/IP server has received 89364 bytes of data
,2015-12-03T00:43:13.156Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 01:43:14.754 ThaliTest[1177:9a1b] client session: connected
,2015-12-03 01:43:14.755 ThaliTest[1177:9a1b] client session: stateChange:1->2 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:43:14.763 ThaliTest[1177:4e0b] client session: fireConnectCallback: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:43:14.763 ThaliTest[1177:4e0b] jxcore: connect: success
,2015-12-03T00:43:14.765Z SendDataConnector.js: CLIENT connected to 61659, error: null
2015-12-03T00:43:14.765Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:43:14.766 ThaliTest[1177:60b] client: relay established
,2015-12-03 01:43:14.767 ThaliTest[1177:60b] client: new accepted socket: 0x1b2be290
,2015-12-03T00:43:14.780Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T00:43:15.321Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-03T00:43:15.345Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-03T00:43:15.391Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-03T00:43:15.404Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-03T00:43:15.417Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03 01:43:23.173 ThaliTest[1177:4e0b] server session: not connected Apple-Iphone6-1_PT2613
,2015-12-03T00:43:25.421Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:43:25.421Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:43:25.423Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:43:25.424Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:43:25.424Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:43:25.425 ThaliTest[1177:60b] client: socket closed
,2015-12-03 01:43:25.426 ThaliTest[1177:60b] client relay: socket disconnected
,2015-12-03 01:43:25.427 ThaliTest[1177:60b] client relay: 0x1b2be290 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b2c18f0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 01:43:25.427 ThaliTest[1177:60b] client session: socket closed: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:43:25.428 ThaliTest[1177:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:43:25.428 ThaliTest[1177:60b] client session: disconnect
,2015-12-03 01:43:25.429 ThaliTest[1177:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:43:25.431 ThaliTest[1177:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:43:30.428Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:43:30.428Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:43:33.511 ThaliTest[1177:60b] multipeer session: reset timer
2015-12-03 01:43:33.512 ThaliTest[1177:60b] multipeer session: stop timer
2015-12-03 01:43:33.512 ThaliTest[1177:60b] multipeer session: start timer: 0x1b28f1c0
,2015-12-03 01:43:33.513 ThaliTest[1177:60b] server: disconnecting to refresh session (Apple-Iphone6-1_PT2613)
2015-12-03 01:43:33.514 ThaliTest[1177:60b] server session: disconnect
2015-12-03 01:43:33.514 ThaliTest[1177:60b] server session: stateChange:2->0 Apple-Iphone6-1_PT2613
,2015-12-03 01:43:33.517 ThaliTest[1177:60b] server session: connect
,2015-12-03 01:43:33.518 ThaliTest[1177:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT2613
,2015-12-03 01:43:33.521 ThaliTest[1177:60b] server: accepting invitation Apple-Iphone6-1_PT2613
,2015-12-03T00:43:33.528Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 01:43:35.432 ThaliTest[1177:6707] jxcore: disconnect
,2015-12-03 01:43:35.433 ThaliTest[1177:6707] jxcore: disconnect: fail
2015-12-03T00:43:35.435Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:43:35.435Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT5704.2nX0ig== with availability status: true
2015-12-03T00:43:35.436Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03T00:43:35.436Z SendDataConnector.js: do connect now
,2015-12-03 01:43:35.436 ThaliTest[1177:6707] jxcore: connect Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:43:35.437 ThaliTest[1177:6707] client session: connect
,2015-12-03 01:43:35.438 ThaliTest[1177:6707] client session: stateChange:0->1 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:43:35.781 ThaliTest[1177:8307] server session: connected
2015-12-03 01:43:35.783 ThaliTest[1177:8307] server session: stateChange:1->2 Apple-Iphone6-1_PT2613
,2015-12-03 01:43:35.786 ThaliTest[1177:60b] server relay: connected (to port: 61650)
,2015-12-03T00:43:35.795Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:43:35.886Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 01:43:38.239 ThaliTest[1177:4e0b] client session: connected
,2015-12-03 01:43:38.241 ThaliTest[1177:4e0b] client session: stateChange:1->2 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:43:38.260 ThaliTest[1177:4e0b] client session: fireConnectCallback: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:43:38.261 ThaliTest[1177:4e0b] jxcore: connect: success
,2015-12-03T00:43:38.262Z SendDataConnector.js: CLIENT connected to 61665, error: null
,2015-12-03T00:43:38.263Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:43:38.264 ThaliTest[1177:60b] client: relay established
,2015-12-03 01:43:38.264 ThaliTest[1177:60b] client: new accepted socket: 0x1b366e40
,2015-12-03T00:43:38.277Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 01:43:46.075 ThaliTest[1177:b007] server session: not connected Apple-Iphone6-1_PT2613
,2015-12-03T00:43:48.331Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:43:48.332Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:43:48.332Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:43:48.333Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:43:48.334Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:43:48.335 ThaliTest[1177:60b] client: socket closed
2015-12-03 01:43:48.336 ThaliTest[1177:60b] client relay: socket disconnected
,2015-12-03 01:43:48.337 ThaliTest[1177:60b] client relay: 0x1b366e40 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b2b2250 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 01:43:48.338 ThaliTest[1177:60b] client session: socket closed: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:43:48.338 ThaliTest[1177:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:43:48.339 ThaliTest[1177:60b] client session: disconnect
,2015-12-03 01:43:48.339 ThaliTest[1177:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:43:48.341 ThaliTest[1177:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:43:53.336Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:43:53.337Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:43:56.035 ThaliTest[1177:60b] multipeer session: reset timer
2015-12-03 01:43:56.037 ThaliTest[1177:60b] multipeer session: stop timer
2015-12-03 01:43:56.037 ThaliTest[1177:60b] multipeer session: start timer: 0x1b28f1c0
,2015-12-03 01:43:56.038 ThaliTest[1177:60b] server: disconnecting to refresh session (Apple-Iphone6-1_PT2613)
2015-12-03 01:43:56.039 ThaliTest[1177:60b] server session: disconnect
,2015-12-03 01:43:56.039 ThaliTest[1177:60b] server session: stateChange:2->0 Apple-Iphone6-1_PT2613
,2015-12-03 01:43:56.042 ThaliTest[1177:60b] server session: connect
,2015-12-03 01:43:56.042 ThaliTest[1177:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT2613
,2015-12-03T00:43:56.046Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 01:43:56.047 ThaliTest[1177:60b] server: accepting invitation Apple-Iphone6-1_PT2613
,2015-12-03 01:43:58.170 ThaliTest[1177:b007] server session: connected
2015-12-03 01:43:58.172 ThaliTest[1177:b007] server session: stateChange:1->2 Apple-Iphone6-1_PT2613
,2015-12-03 01:43:58.175 ThaliTest[1177:60b] server relay: connected (to port: 61650)
,2015-12-03T00:43:58.181Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03 01:43:58.348 ThaliTest[1177:6707] jxcore: disconnect
,2015-12-03 01:43:58.350 ThaliTest[1177:6707] jxcore: disconnect: fail
2015-12-03T00:43:58.351Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:43:58.352Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT5704.2nX0ig== with availability status: true
2015-12-03T00:43:58.352Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
2015,-12-03T00:43:58.352Z SendDataConnector.js: do connect now
,2015-12-03 01:43:58.353 ThaliTest[1177:6707] jxcore: connect Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:43:58.354 ThaliTest[1177:6707] client session: connect
,2015-12-03 01:43:58.354 ThaliTest[1177:6707] client session: stateChange:0->1 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:43:58.403Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 01:44:00.947 ThaliTest[1177:9423] client session: connected
2015-12-03 01:44:00.949 ThaliTest[1177:9423] client session: stateChange:1->2 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:44:01.085 ThaliTest[1177:b007] client session: fireConnectCallback: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:44:01.087 ThaliTest[1177:b007] jxcore: connect: success
,2015-12-03T00:44:01.089Z SendDataConnector.js: CLIENT connected to 61670, error: null
,2015-12-03T00:44:01.089Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:44:01.090 ThaliTest[1177:60b] client: relay established
,2015-12-03 01:44:01.092 ThaliTest[1177:60b] client: new accepted socket: 0x1b2c7270
,2015-12-03T00:44:01.102Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 01:44:08.283 ThaliTest[1177:b007] server session: not connected Apple-Iphone6-1_PT2613
,2015-12-03T00:44:11.160Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:44:11.161Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T00:44:11.162Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:44:11.162Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-12-03T00:44:11.163Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:44:11.164 ThaliTest[1177:60b] client: socket closed
,2015-12-03 01:44:11.165 ThaliTest[1177:60b] client relay: socket disconnected
,2015-12-03 01:44:11.165 ThaliTest[1177:60b] client relay: 0x1b2c7270 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b2bb830 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 01:44:11.166 ThaliTest[1177:60b] client session: socket closed: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:44:11.167 ThaliTest[1177:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:44:11.167 ThaliTest[1177:60b] client session: disconnect
,2015-12-03 01:44:11.168 ThaliTest[1177:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:44:11.169 ThaliTest[1177:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:44:16.169Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:44:16.169Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:44:18.579 ThaliTest[1177:60b] multipeer session: reset timer
2015-12-03 01:44:18.580 ThaliTest[1177:60b] multipeer session: stop timer
,2015-12-03 01:44:18.581 ThaliTest[1177:60b] multipeer session: start timer: 0x1b28f1c0
2015-12-03 01:44:18.581 ThaliTest[1177:60b] server: disconnecting to refresh session (Apple-Iphone6-1_PT2613)
,2015-12-03 01:44:18.582 ThaliTest[1177:60b] server session: disconnect
,2015-12-03 01:44:18.583 ThaliTest[1177:60b] server session: stateChange:2->0 Apple-Iphone6-1_PT2613
,2015-12-03 01:44:18.585 ThaliTest[1177:60b] server session: connect
,2015-12-03T00:44:18.587Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 01:44:18.586 ThaliTest[1177:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT2613
,2015-12-03 01:44:18.590 ThaliTest[1177:60b] server: accepting invitation Apple-Iphone6-1_PT2613
,2015-12-03 01:44:20.713 ThaliTest[1177:b007] server session: connected
2015-12-03 01:44:20.716 ThaliTest[1177:b007] server session: stateChange:1->2 Apple-Iphone6-1_PT2613
,2015-12-03T00:44:20.720Z SendDataTCPServer.js: TCP/IP server connected
2015-12-03 01:44:20.720 ThaliTest[1177:60b] server relay: connected (to port: 61650)
,2015-12-03T00:44:20.820Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 01:44:21.175 ThaliTest[1177:6707] jxcore: disconnect
,2015-12-03 01:44:21.177 ThaliTest[1177:6707] jxcore: disconnect: fail
2015-12-03T00:44:21.178Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:44:21.179Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT5704.2nX0ig== with availability status: true
2015-12-03T00:44:21.179Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:44:21.179Z SendDataConnector.js: do connect now
,2015-12-03 01:44:21.180 ThaliTest[1177:6707] jxcore: connect Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:44:21.181 ThaliTest[1177:6707] client session: connect
,2015-12-03 01:44:21.181 ThaliTest[1177:6707] client session: stateChange:0->1 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:44:23.834 ThaliTest[1177:b007] client session: connected
2015-12-03 01:44:23.836 ThaliTest[1177:b007] client session: stateChange:1->2 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:44:23.843 ThaliTest[1177:b007] client session: fireConnectCallback: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:44:23.845 ThaliTest[1177:b007] jxcore: connect: success
,2015-12-03T00:44:23.846Z SendDataConnector.js: CLIENT connected to 61675, error: null
2015-12-03T00:44:23.846Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:44:23.848 ThaliTest[1177:60b] client: relay established
,2015-12-03 01:44:23.848 ThaliTest[1177:60b] client: new accepted socket: 0x1b36bc30
,2015-12-03T00:44:23.861Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T00:44:33.925Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:44:33.926Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:44:33.926Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:44:33.927Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:44:33.928Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:44:33.929 ThaliTest[1177:60b] client: socket closed
2015-12-03 01:44:33.930 ThaliTest[1177:60b] client relay: socket disconnected
2015-12-03 01:44:33.931 ThaliTest[1177:60b] client relay: 0x1b36bc30 disconnected with error Error Domain=GCDA,syncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b373780 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 01:44:33.931 ThaliTest[1177:60b] client session: socket closed: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:44:33.932 ThaliTest[1177:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:44:33.932 ThaliTest[1177,:60b] client session: disconnect
2015-12-03 01:44:33.933 ThaliTest[1177:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:44:33.935 ThaliTest[1177:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:44:36.430 ThaliTest[1177:2223] server session: not connected Apple-Iphone6-1_PT2613
,2015-12-03T00:44:38.928Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:44:38.929Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:44:41.114 ThaliTest[1177:60b] multipeer session: reset timer
2015-12-03 01:44:41.116 ThaliTest[1177:60b] multipeer session: stop timer
,2015-12-03 01:44:41.117 ThaliTest[1177:60b] multipeer session: start timer: 0x1b28f1c0
2015-12-03 01:44:41.117 ThaliTest[1177:60b] server: disconnecting to refresh session (Apple-Iphone6-1_PT2613)
,2015-12-03 01:44:41.118 ThaliTest[1177:60b] server session: disconnect
2015-12-03 01:44:41.119 ThaliTest[1177:60b] server session: stateChange:2->0 Apple-Iphone6-1_PT2613
,2015-12-03 01:44:41.121 ThaliTest[1177:60b] server session: connect
,2015-12-03 01:44:41.121 ThaliTest[1177:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT2613
,2015-12-03 01:44:41.126 ThaliTest[1177:60b] server: accepting invitation Apple-Iphone6-1_PT2613
,2015-12-03T00:44:41.131Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 01:44:43.291 ThaliTest[1177:b007] server session: connected
2015-12-03 01:44:43.292 ThaliTest[1177:b007] server session: stateChange:1->2 Apple-Iphone6-1_PT2613
,2015-12-03 01:44:43.298 ThaliTest[1177:60b] server relay: connected (to port: 61650)
,2015-12-03T00:44:43.308Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:44:43.398Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 01:44:43.931 ThaliTest[1177:6707] jxcore: disconnect
,2015-12-03 01:44:43.932 ThaliTest[1177:6707] jxcore: disconnect: fail
2015-12-03T00:44:43.934Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:44:43.935Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT5704.2nX0ig== with availability status: true
2015-12-03T00:44:43.935Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:44:43.935Z SendDataConnector.js: do connect now
,2015-12-03 01:44:43.935 ThaliTest[1177:6707] jxcore: connect Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:44:43.936 ThaliTest[1177:6707] client session: connect
,2015-12-03 01:44:43.937 ThaliTest[1177:6707] client session: stateChange:0->1 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:44:46.494 ThaliTest[1177:a11b] client session: connected
,2015-12-03 01:44:46.495 ThaliTest[1177:a11b] client session: stateChange:1->2 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:44:46.504 ThaliTest[1177:a11b] client session: fireConnectCallback: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:44:46.505 ThaliTest[1177:a11b] jxcore: connect: success
,2015-12-03T00:44:46.506Z SendDataConnector.js: CLIENT connected to 61681, error: null
2015-12-03T00:44:46.507Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:44:46.508 ThaliTest[1177:60b] client: relay established
,2015-12-03 01:44:46.509 ThaliTest[1177:60b] client: new accepted socket: 0x1b2d1ac0
,2015-12-03T00:44:46.521Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T00:44:56.584Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:44:56.585Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:44:56.586Z SendDataConnector.js: CLIENT closeClientSocket
,oneRoundDownNow
oneRoundDownNow:2
,2015-12-03T00:44:56.587Z SendDataConnector.js: CLIENT Stop now
2015-12-03T00:44:56.587Z SendDataConnector.js: Stop data retrieving timer
,2015-12-03T00:44:56.588Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 01:44:56.588 ThaliTest[1177:6707] jxcore: disconnect
2015-12-03 01:44:56.589 ThaliTest[1177:6707] client session: disconnectFromPeer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:44:56.590 ThaliTest[1177:6707] client session: disconnect
,2015-12-03 01:44:56.590 ThaliTest[1177:6707] client session: stateChange:2->0 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:44:56.593 ThaliTest[1177:6707] jxcore: disconnect: success
2015-12-03T00:44:56.594Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.2nX0ig==
---- round done--------
,device[3]: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03T00:44:56.596Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:44:56.596Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03T00:44:56.597Z SendDataConnector.js: do connect now
,2015-12-03 01:44:56.597 ThaliTest[1177:6707] jxcore: connect Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:44:56.598 ThaliTest[1177:6707] client session: connect
,2015-12-03 01:44:56.599 ThaliTest[1177:6707] client session: stateChange:0->1 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:44:56.604Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:44:58.984 ThaliTest[1177:a11b] server session: not connected Apple-Iphone6-1_PT2613
,2015-12-03 01:44:59.473 ThaliTest[1177:b937] client session: connected
,2015-12-03 01:44:59.475 ThaliTest[1177:b937] client session: stateChange:1->2 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:44:59.478 ThaliTest[1177:b937] client session: fireConnectCallback: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:44:59.479 ThaliTest[1177:b937] jxcore: connect: success
,2015-12-03T00:44:59.480Z SendDataConnector.js: CLIENT connected to 61685, error: null
2015-12-03T00:44:59.481Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:44:59.483 ThaliTest[1177:60b] client: relay established
,2015-12-03 01:44:59.484 ThaliTest[1177:60b] client: new accepted socket: 0x1b2d7200
,2015-12-03T00:44:59.493Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T00:45:00.014Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-03T00:45:00.027Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-03T00:45:00.040Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-03T00:45:00.053Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-03T00:45:00.070Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-03T00:45:00.083Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03 01:45:00.562 ThaliTest[1177:60b] client: lost peer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:45:00.563 ThaliTest[1177:60b] client session: onPeerLost: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:45:00.565 ThaliTest[1177:60b] client session: onLinkFailure: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:45:00.566 ThaliTest[1177:60b] client session: disconnect
,2015-12-03 01:45:00.566 ThaliTest[1177:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:45:00.568 ThaliTest[1177:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT2613.ais2pw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 01:45:01.752 ThaliTest[1177:60b] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":true}]
,2015-12-03T00:45:10.085Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:45:10.086Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T00:45:10.086Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:45:10.087Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:45:10.087Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:45:11.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03T00:45:15.092Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:45:15.092Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03T00:45:15.092Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 01:45:20.103 ThaliTest[1177:6707] jxcore: disconnect
,2015-12-03 01:45:20.105 ThaliTest[1177:6707] jxcore: disconnect: fail
2015-12-03T00:45:20.107Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:45:20.107Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT2613.ais2pw== with availability status: true
2015-12-03T00:45:20.107Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:45:20.108Z SendDataConnector.js: do connect now
,2015-12-03 01:45:20.108 ThaliTest[1177:6707] jxcore: connect Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:45:20.109 ThaliTest[1177:6707] client session: connect
,2015-12-03 01:45:20.109 ThaliTest[1177:6707] client session: stateChange:0->1 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:45:23.055 ThaliTest[1177:b00b] client session: connected
2015-12-03 01:45:23.057 ThaliTest[1177:b00b] client session: stateChange:1->2 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:45:23.060 ThaliTest[1177:b00b] client session: fireConnectCallback: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:45:23.061 ThaliTest[1177:b00b] jxcore: connect: success
,2015-12-03T00:45:23.062Z SendDataConnector.js: CLIENT connected to 61690, error: null
,2015-12-03T00:45:23.062Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:45:23.064 ThaliTest[1177:60b] client: relay established
2015-12-03 01:45:23.065 ThaliTest[1177:60b] client: new accepted socket: 0x1b2dd670
,2015-12-03T00:45:23.076Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T00:45:33.133Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:45:33.133Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:45:33.134Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:45:33.135Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:45:33.136Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:45:33.137 ThaliTest[1177:60b] client: socket closed
2015-12-03 01:45:33.138 ThaliTest[1177:60b] client relay: socket disconnected
2015-12-03 01:45:33.138 ThaliTest[1177:60b] client relay: 0x1b2dd670 disconnected with error Error Domain=GCDA,syncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b382770 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 01:45:33.139 ThaliTest[1177:60b] client session: socket closed: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:45:33.140 ThaliTest[1177:60b] client session: onLinkFailure: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:45:33.140 ThaliTest[1177:60b] client session: disconnect
2015-12-03 01:45:33.141 ThaliTest[1177:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:45:33.143 ThaliTest[1177:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:45:38.146Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:45:38.146Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:45:41.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:45:41.128 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:45:41.129 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:45:41.129 ThaliTest[1177:60b] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:45:43.155 ThaliTest[1177:6707] jxcore: disconnect
,2015-12-03 01:45:43.157 ThaliTest[1177:6707] jxcore: disconnect: fail
2015-12-03T00:45:43.158Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03T00:45:43.159Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT2613.ais2pw== with availability status: true
,2015-12-03T00:45:43.159Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03T00:45:43.159Z SendDataConnector.js: do connect now
,2015-12-03 01:45:43.159 ThaliTest[1177:6707] jxcore: connect Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:45:43.160 ThaliTest[1177:6707] client session: connect
,2015-12-03 01:45:43.161 ThaliTest[1177:6707] client session: stateChange:0->1 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:45:46.649 ThaliTest[1177:bc0f] client session: connected
2015-12-03 01:45:46.651 ThaliTest[1177:bc0f] client session: stateChange:1->2 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:45:46.654 ThaliTest[1177:bc0f] client session: fireConnectCallback: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:45:46.655 ThaliTest[1177:bc0f] jxcore: connect: success
,2015-12-03T00:45:46.657Z SendDataConnector.js: CLIENT connected to 61695, error: null
,2015-12-03T00:45:46.657Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:45:46.658 ThaliTest[1177:60b] client: relay established
,2015-12-03 01:45:46.660 ThaliTest[1177:60b] client: new accepted socket: 0x1b3885a0
,2015-12-03T00:45:46.671Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T00:45:56.731Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:45:56.731Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T00:45:56.732Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:45:56.732Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-12-03T00:45:56.733Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:45:56.734 ThaliTest[1177:60b] client: socket closed
2015-12-03 01:45:56.735 ThaliTest[1177:60b] client relay: socket disconnected
,2015-12-03 01:45:56.736 ThaliTest[1177:60b] client relay: 0x1b3885a0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b3709c0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03, 01:45:56.736 ThaliTest[1177:60b] client session: socket closed: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:45:56.737 ThaliTest[1177:60b] client session: onLinkFailure: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:45:56.737 ThaliTest[1177:60b] client session: disconnect
,2015-12-03 01:45:56.738 ThaliTest[1177:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:45:56.740 ThaliTest[1177:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:46:01.738Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:46:01.738Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:46:06.749 ThaliTest[1177:6707] jxcore: disconnect
,2015-12-03 01:46:06.751 ThaliTest[1177:6707] jxcore: disconnect: fail
2015-12-03T00:46:06.752Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:46:06.753Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT2613.ais2pw== with availability status: true
2015-12-03T00:46:06.753Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03T00:46:06.753Z SendDataConnector.js: do connect now
,2015-12-03 01:46:06.753 ThaliTest[1177:6707] jxcore: connect Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:46:06.754 ThaliTest[1177:6707] client session: connect
,2015-12-03 01:46:06.755 ThaliTest[1177:6707] client session: stateChange:0->1 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:46:09.738 ThaliTest[1177:b243] client session: connected
2015-12-03 01:46:09.739 ThaliTest[1177:b243] client session: stateChange:1->2 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:46:09.743 ThaliTest[1177:b243] client session: fireConnectCallback: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:46:09.744 ThaliTest[1177:b243] jxcore: connect: success
,2015-12-03T00:46:09.745Z SendDataConnector.js: CLIENT connected to 61700, error: null
2015-12-03T00:46:09.745Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:46:09.748 ThaliTest[1177:60b] client: relay established
,2015-12-03 01:46:09.749 ThaliTest[1177:60b] client: new accepted socket: 0x1b387200
,2015-12-03T00:46:09.759Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 01:46:11.117 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03T00:46:19.820Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:46:19.821Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:46:19.821Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:46:19.822Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:46:19.823Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:46:19.824 ThaliTest[1177:60b] client: socket closed
2015-12-03 01:46:19.825 ThaliTest[1177:60b] client relay: socket disconnected
,2015-12-03 01:46:19.825 ThaliTest[1177:60b] client relay: 0x1b387200 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b2edbe0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 01:46:19.826 ThaliTest[1177:60b] client session: socket closed: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:46:19.827 ThaliTest[1177:60b] client session: onLinkFailure: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:46:19.827 ThaliTest[1177:60b] client session: disconnect
,2015-12-03 01:46:19.828 ThaliTest[1177:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:46:19.829 ThaliTest[1177:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:46:24.823Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:46:24.824Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:46:29.833 ThaliTest[1177:6707] jxcore: disconnect
2015-12-03 01:46:29.834 ThaliTest[1177:6707] jxcore: disconnect: fail
,2015-12-03T00:46:29.835Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03T00:46:29.836Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT2613.ais2pw== with availability status: ,true
2015-12-03T00:46:29.836Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03T00:46:29.836Z SendDataConnector.js: do connect now
,2015-12-03 01:46:29.837 ThaliTest[1177:6707] jxcore: connect Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:46:29.837 ThaliTest[1177:6707] client session: connect
,2015-12-03 01:46:29.838 ThaliTest[1177:6707] client session: stateChange:0->1 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:46:32.779 ThaliTest[1177:7513] client session: connected
,2015-12-03 01:46:32.781 ThaliTest[1177:7513] client session: stateChange:1->2 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:46:32.784 ThaliTest[1177:7513] client session: fireConnectCallback: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:46:32.785 ThaliTest[1177:7513] jxcore: connect: success
,2015-12-03T00:46:32.786Z SendDataConnector.js: CLIENT connected to 61705, error: null
2015-12-03T00:46:32.786Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:46:32.788 ThaliTest[1177:60b] client: relay established
2015-12-03 01:46:32.789 ThaliTest[1177:60b] client: new accepted socket: 0x1b2f1ff0
,2015-12-03T00:46:32.800Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 01:46:41.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:46:41.128 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:46:41.129 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:46:41.131 ThaliTest[1177:60b] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:46:42.859Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:46:42.860Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T00:46:42.860Z SendDataConnector.js: CLIENT closeClientSocket
,oneRoundDownNow
oneRoundDownNow:2
,2015-12-03T00:46:42.861Z SendDataConnector.js: CLIENT Stop now
2015-12-03T00:46:42.862Z SendDataConnector.js: Stop data retrieving timer
,2015-12-03T00:46:42.862Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 01:46:42.863 ThaliTest[1177:6707] jxcore: disconnect
,2015-12-03 01:46:42.864 ThaliTest[1177:6707] client session: disconnectFromPeer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:46:42.864 ThaliTest[1177:6707] client session: disconnect
,2015-12-03 01:46:42.865 ThaliTest[1177:6707] client session: stateChange:2->0 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:46:42.867 ThaliTest[1177:6707] jxcore: disconnect: success
2015-12-03T00:46:42.867Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2613.ais2pw==
---- round done--------
device[4]: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03T00:46:42.869Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03T00:46:42.870Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03T00:46:42.870Z SendDataConnector.js: do connect now
,2015-12-03 01:46:42.871 ThaliTest[1177:6707] jxcore: connect Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:46:42.872 ThaliTest[1177:6707] client session: connect
,2015-12-03 01:46:42.872 ThaliTest[1177:6707] client session: stateChange:0->1 Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03T00:46:42.876Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:46:45.880 ThaliTest[1177:b643] client session: connected
,2015-12-03 01:46:45.882 ThaliTest[1177:b643] client session: stateChange:1->2 Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:46:45.903 ThaliTest[1177:b643] client session: fireConnectCallback: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:46:45.904 ThaliTest[1177:b643] jxcore: connect: success
,2015-12-03T00:46:45.905Z SendDataConnector.js: CLIENT connected to 61709, error: null
,2015-12-03T00:46:45.905Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:46:45.906 ThaliTest[1177:60b] client: relay established
,2015-12-03 01:46:45.908 ThaliTest[1177:60b] client: new accepted socket: 0x1b396ec0
,2015-12-03T00:46:45.918Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T00:46:46.425Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-03T00:46:46.559Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-03T00:46:46.571Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-03T00:46:46.607Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-03T00:46:46.607Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
oneRoundDownNow:2
,2015-12-03T00:46:46.609Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T00:46:46.609Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 01:46:46.610 ThaliTest[1177:6707] jxcore: disconnect
,2015-12-03 01:46:46.611 ThaliTest[1177:6707] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:46:46.611 ThaliTest[1177:6707] client session: disconnect
,2015-12-03 01:46:46.612 ThaliTest[1177:6707] client session: stateChange:2->0 Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:46:46.615 ThaliTest[1177:6707] jxcore: disconnect: success
2015-12-03T00:46:46.616Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7682.INb6UQ==
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
        reading: true,
        slab_0x15583e80: null },
     _readableState: 
      { highWaterMark: 16384,
        buffer: [],
        length: 0,
        pipes: null,
        pipesCount: 0,
        flowing: false,
   ,     ended: false,
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
,  startTime: Thu Dec 03 2015 01:46:46 GMT+0100 (CET),
  endTime: Thu Dec 03 2015 01:46:46 GMT+0100 (CET),
  endReason: '',
  dataTimerId: null,
  disconnecting: false }
done, now sending data to server
CoordinatorConnector-debug: sendData
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT8796","time":262425,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT5704.8qCfew==","time":47742,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple,-Iphone5s-1_PT5704.2nX0ig==","time":104621,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name":"Apple-Iphone6-1_PT2613.ais2pw==","time":106265,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"data,Amount":100000,"dataReceived":90000},{"name":"Apple-IpadAir2-1_PT7682.INb6UQ==","time":3739,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
sendList : 100% : 3739 ms, 99% : 3739 ms, 95 : 3739 ms, 90% : 3739 ms.
R,esult count 1, range 3739 ms to  3739 ms.
sendList failed peers count : 3 [75 %]
- Peer ID : Apple-Iphone5s-1_PT5704.8qCfew==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT5704.2nX0ig==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT2613.ais2pw==, Tried : 5
sen,dList never tried peers count : 0 [0 %]
2015-12-03T00:46:46.635Z SendDataConnector.js: CLIENT Stop now
2015-12-03T00:46:46.635Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 01:47:03.118 ThaliTest[1177:60b] client: lost peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:47:03.120 ThaliTest[1177:60b] client session: onPeerLost: Apple-Iphone6-1_PT2613.ais2pw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 01:47:03.168 ThaliTest[1177:60b] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 01:47:11.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:47:41.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:47:41.129 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:47:41.130 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:47:41.448 ThaliTest[1177:60b] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:47:46.722 ThaliTest[1177:60b] client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:47:46.724 ThaliTest[1177:60b] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 01:47:51.527 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 01:48:09.260 ThaliTest[1177:60b] client: lost peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:48:09.262 ThaliTest[1177:60b] client session: onPeerLost: Apple-Iphone6-1_PT2613.ais2pw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 01:48:11.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:48:11.127 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:48:11.128 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:48:11.454 ThaliTest[1177:60b] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 01:48:16.601 ThaliTest[1177:60b] client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:48:16.602 ThaliTest[1177:60b] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 01:48:21.792 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: disconnect:transport close
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:48:32.909 ThaliTest[1177:60b] client: lost peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:48:32.911 ThaliTest[1177:60b] client session: onPeerLost: Apple-Iphone6-1_PT2613.ais2pw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 01:48:32.932 ThaliTest[1177:60b] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 01:48:35.097 ThaliTest[1177:60b] client: lost peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:48:35.098 ThaliTest[1177:60b] client session: onPeerLost: Apple-Iphone6-1_PT2613.ais2pw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 01:48:35.948 ThaliTest[1177:60b] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:48:41.118 ThaliTest[1177:60b] multipeer session: restart
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
,2015-12-03 01:49:11.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:49:11.129 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:49:11.130 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:49:11.132 ThaliTest[1177:60b] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:49:16.879 ThaliTest[1177:60b] client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:49:16.881 ThaliTest[1177:60b] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:49:21.547 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:49:41.118 ThaliTest[1177:60b] multipeer session: restart
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
,2015-12-03 01:50:11.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:50:11.128 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:50:11.130 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:50:11.435 ThaliTest[1177:60b] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:50:16.636 ThaliTest[1177:60b] client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:50:16.637 ThaliTest[1177:60b] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:50:21.493 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:50:32.261 ThaliTest[1177:60b] client: lost peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:50:32.262 ThaliTest[1177:60b] client session: onPeerLost: Apple-Iphone6-1_PT2613.ais2pw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:50:41.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:50:41.128 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:50:41.130 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
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
,2015-12-03 01:51:11.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:51:11.128 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:51:11.130 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:51:41.118 ThaliTest[1177:60b] multipeer session: restart
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
,2015-12-03 01:52:11.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:52:11.128 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:52:11.129 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:52:16.671 ThaliTest[1177:60b] client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:52:16.672 ThaliTest[1177:60b] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:52:21.469 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:52:41.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:52:41.128 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:52:41.130 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:52:46.592 ThaliTest[1177:60b] client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:52:46.593 ThaliTest[1177:60b] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:52:51.348 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:53:11.118 ThaliTest[1177:60b] multipeer session: restart
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
,2015-12-03 01:53:41.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:53:41.129 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:53:41.130 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
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
,2015-12-03 01:54:10.332 ThaliTest[1177:60b] client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:54:10.334 ThaliTest[1177:60b] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:54:11.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:54:11.127 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:54:11.507 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
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
,2015-12-03 01:54:41.118 ThaliTest[1177:60b] multipeer session: restart
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:55:11.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:55:11.128 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:55:11.130 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
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
,2015-12-03 01:55:41.118 ThaliTest[1177:60b] multipeer session: restart
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
,2015-12-03 01:56:11.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:56:11.127 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:56:11.533 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
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
,2015-12-03 01:56:41.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:56:41.128 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:56:41.130 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:56:46.804 ThaliTest[1177:60b] client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:56:46.806 ThaliTest[1177:60b] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:56:51.310 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:57:11.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:57:11.128 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
2015-12-03 01:57:11.130 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:57:16.644 ThaliTest[1177:60b] client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:57:16.645 ThaliTest[1177:60b] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:57:38.087 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:57:41.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:57:41.128 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:57:42.245 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:57:46.900 ThaliTest[1177:60b] client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:57:46.901 ThaliTest[1177:60b] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:57:51.566 ThaliTest[1177:60b] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:58:10.913 ThaliTest[1177:60b] client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:58:10.914 ThaliTest[1177:60b] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 01:58:11.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:58:11.127 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
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
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,",_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:58:41.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:58:41.129 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
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
,2015-12-03 01:59:11.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:59:11.127 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:59:41.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 01:59:41.128 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
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
,2015-12-03 02:00:11.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 02:00:11.128 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
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
,2015-12-03 02:00:41.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 02:00:41.128 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 02:01:11.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 02:01:11.128 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
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
,2015-12-03 02:01:41.118 ThaliTest[1177:60b] multipeer session: restart
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,",_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 02:02:11.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 02:02:11.128 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
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
,2015-12-03 02:02:41.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 02:02:41.128 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
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
,2015-12-03 02:03:11.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 02:03:11.128 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
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
,2015-12-03 02:03:41.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 02:03:41.128 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
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
,2015-12-03 02:04:11.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 02:04:11.128 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
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
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 02:04:41.118 ThaliTest[1177:60b] multipeer session: restart
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
,2015-12-03 02:05:11.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 02:05:11.127 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
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
,2015-12-03 02:05:41.118 ThaliTest[1177:60b] multipeer session: restart
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
,2015-12-03 02:06:11.118 ThaliTest[1177:60b] multipeer session: restart
,2015-12-03 02:06:11.128 ThaliTest[1177:60b] client: found peer: Apple-IpadAir2-1_PT7682.INb6UQ==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}

```
