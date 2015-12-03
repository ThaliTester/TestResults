#### Test 5065027835b6ad9_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027835b6ad9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/52AAFA6D-F547-4EAA-875F-2A83D3290253/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/52AAFA6D-F547-4EAA-875F-2A83D3290253/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027835b6ad9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027835b6ad9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F5EA7D5A-55C5-487D-9151-7D07EF0EA371/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60256"
,(lldb)     command script import "/tmp/52AAFA6D-F547-4EAA-875F-2A83D3290253/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 12:02:50.843 ThaliTest[2581:2192577] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/33B36920-43D3-4C90-B13E-01DB43AA2203/Library/Cookies/Cookies.binarycookies
,2015-12-03 12:02:51.224 ThaliTest[2581:2192577] Apache Cordova native platform version 3.9.2 is starting.
2015-12-03 12:02:51.225 ThaliTest[2581:2192577] Multi-tasking -> Device: YES, App: YES
,2015-12-03 12:02:51.233 ThaliTest[2581:2192577] Unlimited access to network resources
,2015-12-03 12:02:51.239 ThaliTest[2581:2192577] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 12:02:54.656 ThaliTest[2581:2192577] Resetting plugins due to page load.
,2015-12-03 12:02:55.029 ThaliTest[2581:2192577] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/F5EA7D5A-55C5-487D-9151-7D07EF0EA371/ThaliTest.app/www/index.html
,2015-12-03 12:02:55.150 ThaliTest[2581:2192577] JXcore Cordova plugin initializing
2015-12-03 12:02:55.151 ThaliTest[2581:2192723] JXcore instance initializing
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
,2015-12-03 12:04:04.308 ThaliTest[2581:2192723] jxcore: startBroadcasting
,2015-12-03 12:04:04.320 ThaliTest[2581:2192723] server: starting Apple-Iphone6-1_PT8234.n7uNOA==
2015-12-03 12:04:04.322 ThaliTest[2581:2192723] multipeer session: start timer: 0x192f2b10
,2015-12-03 12:04:04.323 ThaliTest[2581:2192723] THEMultipeerSession initialized peer Apple-Iphone6-1_PT8234
2015-12-03 12:04:04.324 ThaliTest[2581:2192723] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-03 12:04:04.560 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.3coM6g==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5s-1_PT7153.3coM6g==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,CoordinatorConnector-debug: sendData
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT8234","time":256,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5s-1_PT7153.3coM6g==","peerAvailable":true,"time":255}]}
,peersList : 100% : 255 ms, 99% : 255 ms, 95 : 255 ms, 90% : 255 ms.
,Result count 1, range 255 ms to  255 ms.
,2015-12-03 12:04:04.665 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:04.680 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.2PCWSw==
,CoordinatorConnector-debug: stop:undefined
,stop tests now !
stop current!
testFindPeers stopped
,2015-12-03 12:04:05.401 ThaliTest[2581:2192723] jxcore: stopBroadcasting
2015-12-03 12:04:05.401 ThaliTest[2581:2192723] THEMultipeerSession stopping peer
2015-12-03 12:04:05.402 ThaliTest[2581:2192723] multipeer session: stop timer
2015-12-03 12:04:05.,403 ThaliTest[2581:2192723] jxcore: stopBroadcasting: success
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
,serverPort is 49960
,2015-12-03 12:04:05.458 ThaliTest[2581:2192723] jxcore: startBroadcasting
,2015-12-03 12:04:05.459 ThaliTest[2581:2192723] server: starting Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:04:05.459 ThaliTest[2581:2192723] multipeer session: start timer: 0x14eaddf0
2015-12-03 12:04:05.460 ThaliTest[2581:2192723] THEMultipeerSession initialized peer Apple-Iphone6-1_PT8234
2015-12-03 12:04:05.460 ThaliTest[2581:2192723] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-03T11:04:05.461Z SendDataTCPServer.js: TCP/IP server is bound to port: 49960
,2015-12-03 12:04:05.465 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:05.466 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.2PCWSw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7777.VxBn0g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
device[1]: Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03T11:04:05.468Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03T11:04:05.468Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03T11:04:05.468Z SendDataConnector.js: do connect now
,2015-12-03 12:04:05.468 ThaliTest[2581:2192723] jxcore: connect Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:05.469 ThaliTest[2581:2192723] client session: connect
2015-12-03 12:04:05.469 ThaliTest[2581:2192723] client session: stateChange:0->1 Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:05.470 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2098.2PCWSw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.3coM6g==","peerName":"(null)",,"peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 12:04:05.684 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 12:04:06.052 ThaliTest[2581:2192577] client: found peer: Apple-Iphone6-1_PT8234.n7uNOA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.n7uNOA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 12:04:06.322 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7777.O0xngQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,2015-12-03 12:04:06.375 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2098.P4cq9w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 12:04:07.147 ThaliTest[2581:2192577] client: lost peer: Apple-Iphone6-1_PT8234.n7uNOA==
2015-12-03 12:04:07.148 ThaliTest[2581:2192577] client session: onPeerLost: Apple-Iphone6-1_PT8234.n7uNOA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.n7uNOA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 12:04:08.248 ThaliTest[2581:2192577] client: lost peer: Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:08.249 ThaliTest[2581:2192577] client session: onPeerLost: Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:08.250 ThaliTest[2581:219257,7] client session: onLinkFailure: Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:08.250 ThaliTest[2581:2192577] client session: disconnect
2015-12-03 12:04:08.250 ThaliTest[2581:2192577] client session: stateChange:1->0 Apple-IpadAir2-1_PT7777.VxBn0g=,=
2015-12-03 12:04:08.251 ThaliTest[2581:2192577] client session: fireConnectCallback: Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:08.251 ThaliTest[2581:2192577] jxcore: connect: fail: Peer disconnected
,2015-12-03T11:04:08.253Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T11:04:08.254Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-03T11:04:08.255Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7777.VxBn0g==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:04:09.255 ThaliTest[2581:2192577] client: lost peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:04:09.256 ThaliTest[2581:2192577] client session: onPeerLost: Apple-Iphone5s-1_PT7153.3coM6g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.3coM6g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 12:04:11.404 ThaliTest[2581:2192577] client: lost peer: Apple-Iphone5-1_PT2098.2PCWSw==
2015-12-03 12:04:11.405 ThaliTest[2581:2192577] client session: onPeerLost: Apple-Iphone5-1_PT2098.2PCWSw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2098.2PCWSw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03T11:04:13.260Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03T11:04:13.261Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:16.128 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.3coM6g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,2015-12-03 12:04:18.270 ThaliTest[2581:2192723] jxcore: disconnect
2015-12-03 12:04:18.271 ThaliTest[2581:2192723] jxcore: disconnect: fail
2015-12-03T11:04:18.272Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03T11:04:18.272Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT7777.VxBn0g== with availability status: true
,2015-12-03T11:04:18.272Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03T11:04:18.273Z SendDataConnector.js: do connect now
,2015-12-03 12:04:18.274 ThaliTest[2581:2192723] jxcore: connect Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:18.275 ThaliTest[2581:2192723] client: connect: unreachable Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:18.275 ThaliTest[2581:2192723] jxcore: connect: fail: Peer unreachable
2015-12-03T11:04:18.276Z SendDataConnector.js: CLIENT co,nnected to 0, error: Peer unreachable
2015-12-03T11:04:18.276Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-03T11:04:18.276Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:04:23.288Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03T11:04:23.289Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:28.295 ThaliTest[2581:2192723] jxcore: disconnect
2015-12-03 12:04:28.296 ThaliTest[2581:2192723] jxcore: disconnect: fail
2015-12-03T11:04:28.296Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7777.VxBn,0g==
2015-12-03T11:04:28.297Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT7777.VxBn0g== with availability status: true
2015-12-03T11:04:28.297Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7777.VxBn0g==,
2015-12-03T11:04:28.297Z SendDataConnector.js: do connect now
,2015-12-03 12:04:28.298 ThaliTest[2581:2192723] jxcore: connect Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:28.299 ThaliTest[2581:2192723] client: connect: unreachable Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:28.300 ThaliTest[2581:2192723] jxcore: connect: fail: Peer unreachable
2015-12-03T11:04:28.301Z SendDataConnector.js: CLIENT co,nnected to 0, error: Peer unreachable
2015-12-03T11:04:28.301Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-03T11:04:28.302Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:04:33.312Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03T11:04:33.312Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:35.461 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:04:35.481 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:04:35.483 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:04:35.485 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:04:35.486 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:04:38.314 ThaliTest[2581:2192723] jxcore: disconnect
2015-12-03 12:04:38.315 ThaliTest[2581:2192723] jxcore: disconnect: fail
2015-12-03T11:04:38.315Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7777.VxBn,0g==
2015-12-03T11:04:38.316Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT7777.VxBn0g== with availability status: true
,2015-12-03T11:04:38.316Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03T11:04:38.317Z SendDataConnector.js: do connect now
,2015-12-03 12:04:38.317 ThaliTest[2581:2192723] jxcore: connect Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:38.318 ThaliTest[2581:2192723] client: connect: unreachable Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:38.319 ThaliTest[2581:2192723] jxcore: connect: fail: Peer unreachable
2015-12-03T11:04:38.320Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-03T11:04:38.320Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-03T11:04:38.320Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:04:43.326Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03T11:04:43.327Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:43.965 ThaliTest[2581:2192577] client: lost peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:04:43.966 ThaliTest[2581:2192577] client session: onPeerLost: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 12:04:48.328 ThaliTest[2581:2192723] jxcore: disconnect
2015-12-03 12:04:48.329 ThaliTest[2581:2192723] jxcore: disconnect: fail
2015-12-03T11:04:48.330Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7777.VxBn,0g==
2015-12-03T11:04:48.330Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT7777.VxBn0g== with availability status: true
2015-12-03T11:04:48.330Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03T11:04:48.331Z SendDataConnector.js: do connect now
2015-12-03 12:04:48.331 ThaliTest[2581:2192723] jxcore: connect Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:48.332 ThaliTest[2581:2192723] client: connect: unreachable Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:48.333 ThaliTest[2581:2192723] jxcore: connect: fail: Peer unreachable
2015-12-03T11:04:48.334Z SendDataConnector.js: CLIENT co,nnected to 0, error: Peer unreachable
2015-12-03T11:04:48.335Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,oneRoundDownNow:2
,2015-12-03T11:04:48.337Z SendDataConnector.js: CLIENT Stop now
,2015-12-03 12:04:48.338 ThaliTest[2581:2192723] jxcore: disconnect
,2015-12-03 12:04:48.339 ThaliTest[2581:2192723] jxcore: disconnect: fail
2015-12-03T11:04:48.340Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,---- round done--------
,device[2]: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03T11:04:48.343Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03T11:04:48.344Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03T11:04:48.344Z SendDataConnector.js: do connect now
,2015-12-03 12:04:48.345 ThaliTest[2581:2192723] jxcore: connect Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:04:48.346 ThaliTest[2581:2192723] client session: connect
2015-12-03 12:04:48.346 ThaliTest[2581:2192723] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:04:48.766 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 12:04:58.634 ThaliTest[2581:2192577] multipeer session: reset timer
2015-12-03 12:04:58.635 ThaliTest[2581:2192577] multipeer session: stop timer
2015-12-03 12:04:58.636 ThaliTest[2581:2192577] multipeer session: start timer: 0x14eaddf0
2015-,12-03 12:04:58.637 ThaliTest[2581:2192577] server session: connect
2015-12-03 12:04:58.637 ThaliTest[2581:2192577] server session: stateChange:0->1 Apple-IpadAir2-1_PT7777
,2015-12-03 12:04:58.650 ThaliTest[2581:2192577] server: accepting invitation Apple-IpadAir2-1_PT7777
,2015-12-03 12:05:01.001 ThaliTest[2581:2192971] server session: connected
2015-12-03 12:05:01.002 ThaliTest[2581:2192971] server session: stateChange:1->2 Apple-IpadAir2-1_PT7777
,2015-12-03 12:05:01.013 ThaliTest[2581:2192577] server relay: connected (to port: 49960)
,2015-12-03T11:05:01.021Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:05:01.224Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-03T11:05:01.239Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-03T11:05:01.254Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-03T11:05:01.268Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-03T11:05:01.282Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-03T11:05:01.298Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 12:05:01.328 ThaliTest[2581:2192983] server session: not connected Apple-IpadAir2-1_PT7777
,2015-12-03 12:05:21.352 ThaliTest[2581:2192931] client session: not connected Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:05:21.352 ThaliTest[2581:2192931] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:05:21.353 ThaliTe,st[2581:2192931] client session: disconnect
2015-12-03 12:05:21.353 ThaliTest[2581:2192931] client session: stateChange:1->0 Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:05:21.354 ThaliTest[2581:2192931] client session: fireConnectCallback: Apple-Iphon,e5s-1_PT7153.3coM6g==
2015-12-03 12:05:21.354 ThaliTest[2581:2192931] jxcore: connect: fail: Peer disconnected
,2015-12-03T11:05:21.356Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T11:05:21.357Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-03T11:05:21.357Z SendDataConnector.js: tryAgain afer: 5000 ms.,
,2015-12-03T11:05:26.360Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03T11:05:26.361Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:05:28.636 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:05:28.657 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:05:28.658 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:05:28.659 ThaliTest[2581:2192577] clien,t: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:05:28.660 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:05:31.372 ThaliTest[2581:2192723] jxcore: disconnect
2015-12-03 12:05:31.373 ThaliTest[2581:2192723] jxcore: disconnect: fail
2015-12-03T11:05:31.374Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03T11:05:31.374Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT7153.3coM6g== with availability status: true
,2015-12-03T11:05:31.375Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03T11:05:31.375Z SendDataConnector.js: do connect now
,2015-12-03 12:05:31.376 ThaliTest[2581:2192723] jxcore: connect Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:05:31.377 ThaliTest[2581:2192723] client session: connect
2015-12-03 12:05:31.377 ThaliTest[2581:2192723] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:05:55.186 ThaliTest[2581:2192577] client: lost peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:05:55.187 ThaliTest[2581:2192577] client session: onPeerLost: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 12:05:55.713 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,2015-12-03 12:05:58.636 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:05:58.658 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:05:58.659 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,2015-12-03 12:05:58.661 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:05:58.939 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:06:04.382 ThaliTest[2581:2193072] client session: not connected Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:06:04.382 ThaliTest[2581:2193072] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:06:04.383 ThaliTe,st[2581:2193072] client session: disconnect
2015-12-03 12:06:04.383 ThaliTest[2581:2193072] client session: stateChange:1->0 Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:06:04.384 ThaliTest[2581:2193072] client session: fireConnectCallback: Apple-Iphon,e5s-1_PT7153.3coM6g==
2015-12-03 12:06:04.384 ThaliTest[2581:2193072] jxcore: connect: fail: Peer disconnected
,2015-12-03T11:06:04.386Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T11:06:04.386Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-03T11:06:04.387Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:06:09.391Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03T11:06:09.392Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:14.395 ThaliTest[2581:2192723] jxcore: disconnect
2015-12-03 12:06:14.396 ThaliTest[2581:2192723] jxcore: disconnect: fail
2015-12-03T11:06:14.397Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.3coM,6g==
2015-12-03T11:06:14.397Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT7153.3coM6g== with availability status: true
2015-12-03T11:06:14.397Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03T11:06:14.398Z SendDataConnector.js: do connect now
2015-12-03 12:06:14.398 ThaliTest[2581:2192723] jxcore: connect Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:14.399 ThaliTest[2581:2192723] client session: connect
2015-12-03 12:06:14.400 ThaliTest[2581:2192723] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:28.636 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:06:28.656 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:06:28.658 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:28.660 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:06:28.663 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:06:47.407 ThaliTest[2581:2193164] client session: not connected Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:06:47.408 ThaliTest[2581:2193164] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:06:47.409 ThaliTe,st[2581:2193164] client session: disconnect
2015-12-03 12:06:47.409 ThaliTest[2581:2193164] client session: stateChange:1->0 Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:06:47.410 ThaliTest[2581:2193164] client session: fireConnectCallback: Apple-Iphon,e5s-1_PT7153.3coM6g==
2015-12-03 12:06:47.410 ThaliTest[2581:2193164] jxcore: connect: fail: Peer disconnected
,2015-12-03T11:06:47.412Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T11:06:47.413Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-03T11:06:47.413Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:06:52.414Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03T11:06:52.415Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:57.417 ThaliTest[2581:2192723] jxcore: disconnect
2015-12-03 12:06:57.418 ThaliTest[2581:2192723] jxcore: disconnect: fail
2015-12-03T11:06:57.419Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03T11:06:57.419Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT7153.3coM6g== with availability status: true
2015-12-03T11:06:57.419Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.3coM6g==,
2015-12-03T11:06:57.420Z SendDataConnector.js: do connect now
,2015-12-03 12:06:57.420 ThaliTest[2581:2192723] jxcore: connect Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:57.421 ThaliTest[2581:2192723] client session: connect
2015-12-03 12:06:57.422 ThaliTest[2581:2192723] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:58.636 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:06:58.655 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:06:58.658 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:06:58.660 ThaliTest[2581:2192577] clie,nt: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:06:58.661 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:07:28.636 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:07:28.653 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:07:28.655 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:07:28.656 ThaliTest[2581:2192577] clien,t: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:07:29.013 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:07:30.425 ThaliTest[2581:2193260] client session: not connected Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:07:30.426 ThaliTest[2581:2193260] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:07:30.426 ThaliTe,st[2581:2193260] client session: disconnect
2015-12-03 12:07:30.427 ThaliTest[2581:2193260] client session: stateChange:1->0 Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:07:30.427 ThaliTest[2581:2193260] client session: fireConnectCallback: Apple-Iphon,e5s-1_PT7153.3coM6g==
2015-12-03 12:07:30.428 ThaliTest[2581:2193260] jxcore: connect: fail: Peer disconnected
,2015-12-03T11:07:30.429Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T11:07:30.430Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-03T11:07:30.430Z SendDataConnector.js: tryAgain afer: 5000 ms.,
,2015-12-03T11:07:35.432Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03T11:07:35.433Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:07:40.437 ThaliTest[2581:2192723] jxcore: disconnect
2015-12-03 12:07:40.438 ThaliTest[2581:2192723] jxcore: disconnect: fail
2015-12-03T11:07:40.439Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03T11:07:40.439Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT7153.3coM6g== with availability status: true
,2015-12-03T11:07:40.440Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03T11:07:40.440Z SendDataConnector.js: do connect now
,2015-12-03 12:07:40.441 ThaliTest[2581:2192723] jxcore: connect Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:07:40.442 ThaliTest[2581:2192723] client session: connect
2015-12-03 12:07:40.442 ThaliTest[2581:2192723] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:07:58.634 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:07:58.655 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:07:58.656 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:07:58.657 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:07:58.657 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:08:13.447 ThaliTest[2581:2193343] client session: not connected Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:08:13.448 ThaliTest[2581:2193343] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:08:13.449 ThaliTe,st[2581:2193343] client session: disconnect
2015-12-03 12:08:13.449 ThaliTest[2581:2193343] client session: stateChange:1->0 Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:08:13.450 ThaliTest[2581:2193343] client session: fireConnectCallback: Apple-Iphon,e5s-1_PT7153.3coM6g==
2015-12-03 12:08:13.450 ThaliTest[2581:2193343] jxcore: connect: fail: Peer disconnected
,2015-12-03T11:08:13.452Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T11:08:13.452Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
oneRoundDownNow
oneRoundDownNow:2
,2015-12-03T11:08:13.454Z SendDataConnector.js: CLIENT Stop now
,2015-12-03 12:08:13.455 ThaliTest[2581:2192723] jxcore: disconnect
,2015-12-03 12:08:13.457 ThaliTest[2581:2192723] jxcore: disconnect: fail
2015-12-03T11:08:13.458Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.3coM6g==
---- round done--------
,device[3]: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:08:13.460Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:08:13.460Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:08:13.460Z SendDataConnector.js: do connect now
,2015-12-03 12:08:13.462 ThaliTest[2581:2192723] jxcore: connect Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:08:13.462 ThaliTest[2581:2192723] client session: connect
2015-12-03 12:08:13.463 ThaliTest[2581:2192723] client session: stateChange:0->1 Appl,e-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:08:13.604 ThaliTest[2581:2192577] multipeer session: reset timer
2015-12-03 12:08:13.605 ThaliTest[2581:2192577] multipeer session: stop timer
2015-12-03 12:08:13.605 ThaliTest[2581:2192577] multipeer session: start timer: 0x14eaddf0
2015-,12-03 12:08:13.606 ThaliTest[2581:2192577] server session: connect
2015-12-03 12:08:13.606 ThaliTest[2581:2192577] server session: stateChange:0->1 Apple-Iphone5s-1_PT7153
,2015-12-03 12:08:13.619 ThaliTest[2581:2192577] server: accepting invitation Apple-Iphone5s-1_PT7153
,2015-12-03 12:08:15.863 ThaliTest[2581:2193343] client session: connected
2015-12-03 12:08:15.863 ThaliTest[2581:2193347] server session: connected
2015-12-03 12:08:15.864 ThaliTest[2581:2193343] client session: stateChange:1->2 Apple-Iphone5s-1_PT7153.j,AFxCw==
2015-12-03 12:08:15.864 ThaliTest[2581:2193347] server session: stateChange:1->2 Apple-Iphone5s-1_PT7153
,2015-12-03 12:08:15.875 ThaliTest[2581:2193320] client session: fireConnectCallback: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:08:15.876 ThaliTest[2581:2193320] jxcore: connect: success
2015-12-03 12:08:15.877 ThaliTest[2581:2192577] server relay: c,onnected (to port: 49960)
2015-12-03T11:08:15.881Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:08:15.882Z SendDataConnector.js: CLIENT connected to 49978, error: null
,2015-12-03T11:08:15.883Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:08:15.887 ThaliTest[2581:2192577] client: relay established
2015-12-03 12:08:15.887 ThaliTest[2581:2192577] client: new accepted socket: 0x1939c8d0
,2015-12-03T11:08:15.901Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T11:08:16.192Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-03T11:08:16.212Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 12:08:16.255 ThaliTest[2581:2193343] server session: not connected Apple-Iphone5s-1_PT7153
,2015-12-03T11:08:16.255Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-03T11:08:16.268Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03T11:08:26.270Z SendDataConnector.js: Receiving data timeout now
2015-12-03T11:08:26.271Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:08:26.273Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:08:26.273Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:08:26.274Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 12:08:26.276 ThaliTest[2581:2192577] client: socket closed
2015-12-03 12:08:26.276 ThaliTest[2581:2192577] client relay: socket disconnected
2015-12-03 12:08:26.277 ThaliTest[2581:2192577] client relay: 0x1939c8d0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19239ca0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 12:08:26.277 ThaliTest[2581:2192577] client session: socket closed: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:08:26.278 ThaliTest[2581:2192577] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:08:26.278 ThaliTest[2581:2192577] client session: disconnect
2015-12-03 12:08:26.279 ThaliTest[2581:2192577] client session: stateChange:2->0 Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:08:26.280 ThaliTest[2581:2192577] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:08:31.281Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:08:31.282Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:08:36.283 ThaliTest[2581:2192723] jxcore: disconnect
2015-12-03 12:08:36.284 ThaliTest[2581:2192723] jxcore: disconnect: fail
2015-12-03T11:08:36.285Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.jAFx,Cw==
2015-12-03T11:08:36.285Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT7153.jAFxCw== with availability status: true
,2015-12-03T11:08:36.286Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03T11:08:36.286Z SendDataConnector.js: do connect now
,2015-12-03 12:08:36.287 ThaliTest[2581:2192723] jxcore: connect Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:08:36.288 ThaliTest[2581:2192723] client session: connect
2015-12-03 12:08:36.289 ThaliTest[2581:2192723] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:08:38.988 ThaliTest[2581:2193422] client session: connected
2015-12-03 12:08:38.988 ThaliTest[2581:2193422] client session: stateChange:1->2 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:08:38.999 ThaliTest[2581:2193422] client session: fireConnectCallback: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:08:39.000 ThaliTest[2581:2193422] jxcore: connect: success
,2015-12-03T11:08:39.001Z SendDataConnector.js: CLIENT connected to 49982, error: null
,2015-12-03T11:08:39.001Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:08:39.005 ThaliTest[2581:2192577] client: relay established
2015-12-03 12:08:39.006 ThaliTest[2581:2192577] client: new accepted socket: 0x19235a20
,2015-12-03T11:08:39.018Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 12:08:43.607 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:08:43.658 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:08:43.660 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:08:43.660 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:08:43.661 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03T11:08:49.091Z SendDataConnector.js: Receiving data timeout now
2015-12-03T11:08:49.092Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:08:49.093Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:08:49.093Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:08:49.094Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 12:08:49.095 ThaliTest[2581:2192577] client: socket closed
2015-12-03 12:08:49.096 ThaliTest[2581:2192577] client relay: socket disconnected
2015-12-03 12:08:49.097 ThaliTest[2581:2192577] client relay: 0x19235a20 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19242280 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 12:08:49.097 ThaliTest[2581:2192577] client session: socket closed: Apple-Iphone5s-1_PT7153.jAFxC,w==
2015-12-03 12:08:49.098 ThaliTest[2581:2192577] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:08:49.098 ThaliTest[2581:2192577] client session: disconnect
2015-12-03 12:08:49.099 ThaliTest[2581:2192577] client session,: stateChange:2->0 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:08:49.101 ThaliTest[2581:2192577] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:08:54.105Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:08:54.106Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:08:59.114 ThaliTest[2581:2192723] jxcore: disconnect
2015-12-03 12:08:59.115 ThaliTest[2581:2192723] jxcore: disconnect: fail
2015-12-03T11:08:59.115Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.jAFx,Cw==
2015-12-03T11:08:59.116Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT7153.jAFxCw== with availability status: true
2015-12-03T11:08:59.116Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:08:59.116Z SendDataConnector.js: do connect now
2015-12-03 12:08:59.117 ThaliTest[2581:2192723] jxcore: connect Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:08:59.119 ThaliTest[2581:2192723] client session: connect
2015-12-03 12:08:59.119 ThaliTest[2581:2192723] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:01.572 ThaliTest[2581:2193474] client session: connected
2015-12-03 12:09:01.573 ThaliTest[2581:2193474] client session: stateChange:1->2 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:01.581 ThaliTest[2581:2193472] client session: fireConnectCallback: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:09:01.582 ThaliTest[2581:2193472] jxcore: connect: success
2015-12-03T11:09:01.583Z SendDataConnector.js: CLIENT connected, to 49987, error: null
,2015-12-03T11:09:01.584Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:09:01.588 ThaliTest[2581:2192577] client: relay established
2015-12-03 12:09:01.589 ThaliTest[2581:2192577] client: new accepted socket: 0x192370d0
,2015-12-03T11:09:01.599Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T11:09:11.669Z SendDataConnector.js: Receiving data timeout now
2015-12-03T11:09:11.670Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:09:11.671Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:09:11.671Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:09:11.672Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 12:09:11.673 ThaliTest[2581:2192577] client: socket closed
2015-12-03 12:09:11.674 ThaliTest[2581:2192577] client relay: socket disconnected
2015-12-03 12:09:11.675 ThaliTest[2581:2192577] client relay: 0x192370d0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19247d10 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 12:09:11.675 ThaliTest[2581:2192577] client session: socket closed: Apple-Iphone5s-1_PT7153.jAFxC,w==
2015-12-03 12:09:11.676 ThaliTest[2581:2192577] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:09:11.676 ThaliTest[2581:2192577] client session: disconnect
2015-12-03 12:09:11.677 ThaliTest[2581:2192577] client session: stateChange:2->0 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:11.679 ThaliTest[2581:2192577] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:13.602 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:09:13.624 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:09:13.625 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:09:13.626 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,2015-12-03 12:09:13.627 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03T11:09:16.673Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:09:16.674Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:21.677 ThaliTest[2581:2192723] jxcore: disconnect
2015-12-03 12:09:21.678 ThaliTest[2581:2192723] jxcore: disconnect: fail
2015-12-03T11:09:21.679Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.jAFx,Cw==
2015-12-03T11:09:21.679Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT7153.jAFxCw== with availability status: true
2015-12-03T11:09:21.679Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:09:21.680Z SendDataConnector.js: do connect now
2015-12-03 12:09:21.680 ThaliTest[2581:2192723] jxcore: connect Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:21.681 ThaliTest[2581:2192723] client session: connect
2015-12-03 12:09:21.682 ThaliTest[2581:2192723] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:24.009 ThaliTest[2581:2193513] client session: connected
2015-12-03 12:09:24.009 ThaliTest[2581:2193513] client session: stateChange:1->2 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:24.019 ThaliTest[2581:2193472] client session: fireConnectCallback: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:09:24.020 ThaliTest[2581:2193472] jxcore: connect: success
2015-12-03T11:09:24.021Z SendDataConnector.js: CLIENT connected, to 49992, error: null
,2015-12-03T11:09:24.022Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:09:24.025 ThaliTest[2581:2192577] client: relay established
2015-12-03 12:09:24.026 ThaliTest[2581:2192577] client: new accepted socket: 0x1922f7d0
,2015-12-03T11:09:24.038Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T11:09:34.106Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T11:09:34.107Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:09:34.108Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:09:34.108Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:09:34.109Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 12:09:34.110 ThaliTest[2581:2192577] client: socket closed
2015-12-03 12:09:34.111 ThaliTest[2581:2192577] client relay: socket disconnected
2015-12-03 12:09:34.112 ThaliTest[2581:2192577] client relay: 0x1922f7d0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x192396a0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 12:09:34.112 ThaliTest[2581:2192577] client session: socket closed: Apple-Iphone5s-1_PT7153.jAFxC,w==
2015-12-03 12:09:34.113 ThaliTest[2581:2192577] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:09:34.113 ThaliTest[2581:2192577] client session: disconnect
2015-12-03 12:09:34.114 ThaliTest[2581:2192577] client session,: stateChange:2->0 Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:09:34.115 ThaliTest[2581:2192577] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:09:39.112Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03T11:09:39.113Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:43.602 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:09:43.719 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:09:43.720 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:09:43.721 ThaliTest[2581:2192577] clie,nt: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:09:43.723 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:09:44.120 ThaliTest[2581:2192723] jxcore: disconnect
2015-12-03 12:09:44.120 ThaliTest[2581:2192723] jxcore: disconnect: fail
2015-12-03T11:09:44.121Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03T11:09:44.122Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT7153.jAFxCw== with availability status: true
,2015-12-03T11:09:44.122Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03T11:09:44.122Z SendDataConnector.js: do connect now
,2015-12-03 12:09:44.123 ThaliTest[2581:2192723] jxcore: connect Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:09:44.124 ThaliTest[2581:2192723] client session: connect
2015-12-03 12:09:44.125 ThaliTest[2581:2192723] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:46.462 ThaliTest[2581:2193538] client session: connected
2015-12-03 12:09:46.463 ThaliTest[2581:2193538] client session: stateChange:1->2 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:46.474 ThaliTest[2581:2193561] client session: fireConnectCallback: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:09:46.474 ThaliTest[2581:2193561] jxcore: connect: success
2015-12-03T11:09:46.476Z SendDataConnector.js: CLIENT connected to 49997, error: null
2015-12-03T11:09:46.477Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:09:46.480 ThaliTest[2581:2192577] client: relay established
,2015-12-03 12:09:46.481 ThaliTest[2581:2192577] client: new accepted socket: 0x19228ba0
,2015-12-03T11:09:46.492Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T11:09:56.568Z SendDataConnector.js: Receiving data timeout now
2015-12-03T11:09:56.568Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:09:56.569Z SendDataConnector.js: CLIENT closeClientSocket
,oneRoundDownNow
,oneRoundDownNow:2
,2015-12-03T11:09:56.571Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T11:09:56.571Z SendDataConnector.js: Stop data retrieving timer
,2015-12-03T11:09:56.572Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 12:09:56.573 ThaliTest[2581:2192723] jxcore: disconnect
2015-12-03 12:09:56.574 ThaliTest[2581:2192723] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:09:56.574 ThaliTest[2581:2192723] client session: discon,nect
2015-12-03 12:09:56.575 ThaliTest[2581:2192723] client session: stateChange:2->0 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:56.578 ThaliTest[2581:2192723] jxcore: disconnect: success
2015-12-03T11:09:56.579Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.jAFxCw==
,---- round done--------
device[4]: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03T11:09:56.584Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03T11:09:56.584Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03T11:09:56.585Z SendDataConnector.js: do connect now
,2015-12-03 12:09:56.586 ThaliTest[2581:2192723] jxcore: connect Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:09:56.586 ThaliTest[2581:2192723] client session: connect
2015-12-03 12:09:56.587 ThaliTest[2581:2192723] client session: stateChange:0->1 Appl,e-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03T11:09:56.593Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 12:09:58.013 ThaliTest[2581:2192577] multipeer session: reset timer
2015-12-03 12:09:58.014 ThaliTest[2581:2192577] multipeer session: stop timer
2015-12-03 12:09:58.015 ThaliTest[2581:2192577] multipeer session: start timer: 0x14eaddf0
2015-,12-03 12:09:58.015 ThaliTest[2581:2192577] server session: connect
2015-12-03 12:09:58.016 ThaliTest[2581:2192577] server session: stateChange:0->1 Apple-Iphone5-1_PT2098
,2015-12-03 12:09:58.026 ThaliTest[2581:2192577] server: accepting invitation Apple-Iphone5-1_PT2098
,2015-12-03 12:09:59.530 ThaliTest[2581:2193538] client session: connected
2015-12-03 12:09:59.531 ThaliTest[2581:2193538] client session: stateChange:1->2 Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:09:59.538 ThaliTest[2581:2193577] client session: fireConnectCallback: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:09:59.539 ThaliTest[2581:2193577] jxcore: connect: success
,2015-12-03T11:09:59.540Z SendDataConnector.js: CLIENT connected to 50000, error: null
2015-12-03T11:09:59.541Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:09:59.544 ThaliTest[2581:2192577] client: relay established
2015-12-03 12:09:59.544 ThaliTest[2581:2192577] client: new accepted socket: 0x19224740
,2015-12-03T11:09:59.556Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T11:09:59.815Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-03T11:09:59.828Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-03T11:09:59.828Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,oneRoundDownNow:2
,2015-12-03T11:09:59.829Z SendDataConnector.js: CLIENT Stop now
2015-12-03T11:09:59.829Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 12:09:59.829 ThaliTest[2581:2192723] jxcore: disconnect
2015-12-03 12:09:59.829 ThaliTest[2581:2192723] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:09:59.830 ThaliTest[2581:2192723] client session: disconnect
2015-12-03 12:09:59.830 ThaliTest[2581:2192723] client session: stateChange:2->0 Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:09:59.831 ThaliTest[2581:2192723] jxcore: disconnect: success
,2015-12-03T11:09:59.831Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7777.O0xngQ==
---- round done--------
,weAreDoneNow, resultArray.length: 4
sendReportNow
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
        onread: [Function: onread],
        reading: true,
        slab_0x14ed6370: null },
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
        finish: [Function: onSocketFinish],
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
        bufferProcessing: false,
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
     pause: [Function,],
     resume: [Function],
     read: [Function],
     _consuming: true },
  reTryTimer: null,
  receivedCounter: 100000,
  tryRounds: 0,
  resultArray: [],
  connectionCount: 0,
  _events: { done: [Function], debug: [Function] },
  peer: null,,
  startTime: Thu Dec 03 2015 12:09:59 GMT+0100 (CET),
  endTime: Thu Dec 03 2015 12:09:59 GMT+0100 (CET),
  endReason: '',
  dataTimerId: null,
  disconnecting: false }
done, now sending data to server
CoordinatorConnector-debug: sendData
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT8234","time":354382,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT7777.VxBn0g==","time":42868,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple,-Iphone5s-1_PT7153.3coM6g==","time":205110,"result":"Peer disconnected","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5s-1_PT7153.jAFxCw==","time":103111,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"da,taAmount":100000,"dataReceived":90000},{"name":"Apple-IpadAir2-1_PT7777.O0xngQ==","time":3245,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 3245 ms, 99% : 3245 ms, 95 : 3245 ms, 90% : 3245 ms.
,Result count 1, range 3245 ms to  3245 ms.
,sendList failed peers count : 3 [75 %]
,- Peer ID : Apple-IpadAir2-1_PT7777.VxBn0g==, Tried : 5
,- Peer ID : Apple-Iphone5s-1_PT7153.3coM6g==, Tried : 5
,- Peer ID : Apple-Iphone5s-1_PT7153.jAFxCw==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-12-03T11:09:59.842Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T11:09:59.842Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 12:10:00.505 ThaliTest[2581:2193578] server session: connected
2015-12-03 12:10:00.505 ThaliTest[2581:2193578] server session: stateChange:1->2 Apple-Iphone5-1_PT2098
,2015-12-03 12:10:00.510 ThaliTest[2581:2192577] server relay: connected (to port: 49960)
2015-12-03T11:10:00.515Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:10:01.001Z SendDataTCPServer.js: TCP/IP server has received 5952 bytes of data
,2015-12-03T11:10:01.029Z SendDataTCPServer.js: TCP/IP server has received 15872 bytes of data
,2015-12-03T11:10:01.046Z SendDataTCPServer.js: TCP/IP server has received 31744 bytes of data
,2015-12-03T11:10:01.060Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
,2015-12-03T11:10:01.074Z SendDataTCPServer.js: TCP/IP server has received 55552 bytes of data
,2015-12-03T11:10:01.085Z SendDataTCPServer.js: TCP/IP server has received 61504 bytes of data
,2015-12-03T11:10:01.098Z SendDataTCPServer.js: TCP/IP server has received 73408 bytes of data
,2015-12-03T11:10:01.112Z SendDataTCPServer.js: TCP/IP server has received 85312 bytes of data
,2015-12-03T11:10:01.125Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 12:10:11.509 ThaliTest[2581:2193578] server session: not connected Apple-Iphone5-1_PT2098
,2015-12-03 12:10:17.267 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:10:18.847 ThaliTest[2581:2192577] client: lost peer: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:10:18.848 ThaliTest[2581:2192577] client session: onPeerLost: Apple-Iphone5s-1_PT7153.3coM6g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.3coM6g==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:10:22.533 ThaliTest[2581:2192577] multipeer session: reset timer
2015-12-03 12:10:22.534 ThaliTest[2581:2192577] multipeer session: stop timer
2015-12-03 12:10:22.534 ThaliTest[2581:2192577] multipeer session: start timer: 0x14eaddf0
2015-,12-03 12:10:22.535 ThaliTest[2581:2192577] server: disconnecting to refresh session (Apple-Iphone5-1_PT2098)
2015-12-03 12:10:22.535 ThaliTest[2581:2192577] server session: disconnect
2015-12-03 12:10:22.536 ThaliTest[2581:2192577] server session: stateC,hange:2->0 Apple-Iphone5-1_PT2098
2015-12-03 12:10:22.539 ThaliTest[2581:2192577] server session: connect
2015-12-03 12:10:22.539 ThaliTest[2581:2192577] server session: stateChange:0->1 Apple-Iphone5-1_PT2098
2015-12-03T11:10:22.545Z SendDataTCPServer.,js: TCP/IP server is ended
,2015-12-03 12:10:22.556 ThaliTest[2581:2192577] server: accepting invitation Apple-Iphone5-1_PT2098
,2015-12-03 12:10:24.771 ThaliTest[2581:2193623] server session: connected
2015-12-03 12:10:24.771 ThaliTest[2581:2193623] server session: stateChange:1->2 Apple-Iphone5-1_PT2098
,2015-12-03 12:10:24.778 ThaliTest[2581:2192577] server relay: connected (to port: 49960)
,2015-12-03T11:10:24.787Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:10:25.130Z SendDataTCPServer.js: TCP/IP server has received 1984 bytes of data
,2015-12-03T11:10:25.145Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 12:10:35.087 ThaliTest[2581:2193578] server session: not connected Apple-Iphone5-1_PT2098
,2015-12-03 12:10:45.717 ThaliTest[2581:2192577] multipeer session: reset timer
2015-12-03 12:10:45.717 ThaliTest[2581:2192577] multipeer session: stop timer
2015-12-03 12:10:45.718 ThaliTest[2581:2192577] multipeer session: start timer: 0x14eaddf0
2015-,12-03 12:10:45.719 ThaliTest[2581:2192577] server: disconnecting to refresh session (Apple-Iphone5-1_PT2098)
2015-12-03 12:10:45.719 ThaliTest[2581:2192577] server session: disconnect
2015-12-03 12:10:45.720 ThaliTest[2581:2192577] server session: stateC,hange:2->0 Apple-Iphone5-1_PT2098
2015-12-03 12:10:45.722 ThaliTest[2581:2192577] server session: connect
2015-12-03T11:10:45.725Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 12:10:45.723 ThaliTest[2581:2192577] server session: stateChange:0,->1 Apple-Iphone5-1_PT2098
,2015-12-03 12:10:45.740 ThaliTest[2581:2192577] server: accepting invitation Apple-Iphone5-1_PT2098
,2015-12-03 12:10:48.203 ThaliTest[2581:2193667] server session: connected
2015-12-03 12:10:48.204 ThaliTest[2581:2193667] server session: stateChange:1->2 Apple-Iphone5-1_PT2098
,2015-12-03 12:10:48.210 ThaliTest[2581:2192577] server relay: connected (to port: 49960)
,2015-12-03T11:10:48.218Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:10:48.368Z SendDataTCPServer.js: TCP/IP server has received 2976 bytes of data
,2015-12-03T11:10:48.382Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 12:10:48.590 ThaliTest[2581:2192577] client: lost peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:10:48.591 ThaliTest[2581:2192577] client session: onPeerLost: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:10:49.239 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 12:10:57.183 ThaliTest[2581:2192577] client: lost peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:10:57.183 ThaliTest[2581:2192577] client session: onPeerLost: Apple-Iphone5s-1_PT7153.jAFxCw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:10:58.153 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 12:10:58.298 ThaliTest[2581:2193669] server session: not connected Apple-Iphone5-1_PT2098
,2015-12-03 12:11:08.650 ThaliTest[2581:2192577] multipeer session: reset timer
2015-12-03 12:11:08.651 ThaliTest[2581:2192577] multipeer session: stop timer
2015-12-03 12:11:08.651 ThaliTest[2581:2192577] multipeer session: start timer: 0x14eaddf0
2015-,12-03 12:11:08.652 ThaliTest[2581:2192577] server: disconnecting to refresh session (Apple-Iphone5-1_PT2098)
2015-12-03 12:11:08.653 ThaliTest[2581:2192577] server session: disconnect
2015-12-03 12:11:08.653 ThaliTest[2581:2192577] server session: stateC,hange:2->0 Apple-Iphone5-1_PT2098
2015-12-03T11:11:08.660Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 12:11:08.717 ThaliTest[2581:2192577] server session: connect
2015-12-03 12:11:08.718 ThaliTest[2581:2192577] server session: stateChange:0->1 Apple-Iphone5-1_PT2098
,2015-12-03 12:11:08.723 ThaliTest[2581:2192577] server: accepting invitation Apple-Iphone5-1_PT2098
,2015-12-03 12:11:10.942 ThaliTest[2581:2193709] server session: connected
2015-12-03 12:11:10.943 ThaliTest[2581:2193709] server session: stateChange:1->2 Apple-Iphone5-1_PT2098
,2015-12-03 12:11:10.948 ThaliTest[2581:2192577] server relay: connected (to port: 49960)
2015-12-03T11:11:10.953Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:11:11.263Z SendDataTCPServer.js: TCP/IP server has received 5952 bytes of data
,2015-12-03T11:11:11.275Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 12:11:17.020 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:11:19.116 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:11:21.214 ThaliTest[2581:2193708] server session: not connected Apple-Iphone5-1_PT2098
,2015-12-03 12:11:26.995 ThaliTest[2581:2192577] client: lost peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:11:26.996 ThaliTest[2581:2192577] client session: onPeerLost: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:11:28.159 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 12:11:31.325 ThaliTest[2581:2192577] multipeer session: reset timer
2015-12-03 12:11:31.325 ThaliTest[2581:2192577] multipeer session: stop timer
2015-12-03 12:11:31.326 ThaliTest[2581:2192577] multipeer session: start timer: 0x14eaddf0
2015-,12-03 12:11:31.327 ThaliTest[2581:2192577] server: disconnecting to refresh session (Apple-Iphone5-1_PT2098)
2015-12-03 12:11:31.328 ThaliTest[2581:2192577] server session: disconnect
2015-12-03 12:11:31.328 ThaliTest[2581:2192577] server session: stateC,hange:2->0 Apple-Iphone5-1_PT2098
2015-12-03 12:11:31.331 ThaliTest[2581:2192577] server session: connect
2015-12-03T11:11:31.334Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 12:11:31.331 ThaliTest[2581:2192577] server session: stateChange:0,->1 Apple-Iphone5-1_PT2098
,2015-12-03 12:11:31.348 ThaliTest[2581:2192577] server: accepting invitation Apple-Iphone5-1_PT2098
,2015-12-03 12:11:33.663 ThaliTest[2581:2193709] server session: connected
2015-12-03 12:11:33.664 ThaliTest[2581:2193709] server session: stateChange:1->2 Apple-Iphone5-1_PT2098
,2015-12-03 12:11:33.832 ThaliTest[2581:2192577] server relay: connected (to port: 49960)
,2015-12-03T11:11:33.839Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:11:33.854Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 12:11:43.765 ThaliTest[2581:2193741] server session: not connected Apple-Iphone5-1_PT2098
,CoordinatorConnector-debug: disconnect:transport close
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:11:48.996 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:11:55.286 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:12:01.328 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:12:01.348 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:12:01.349 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:12:01.349 ThaliTest[2581:2192577] clien,t: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
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
,2015-12-03 12:12:22.539 ThaliTest[2581:2192577] client: lost peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:12:22.540 ThaliTest[2581:2192577] client session: onPeerLost: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:12:28.308 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 12:12:31.328 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:12:31.346 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:12:31.347 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:12:31.349 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:12:49.276 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:12:57.167 ThaliTest[2581:2192577] client: lost peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:12:57.167 ThaliTest[2581:2192577] client session: onPeerLost: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:12:58.186 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:13:01.328 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:13:01.345 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:13:01.346 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:13:01.348 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:13:18.717 ThaliTest[2581:2192577] client: lost peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:13:18.718 ThaliTest[2581:2192577] client session: onPeerLost: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:13:19.154 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:13:27.081 ThaliTest[2581:2192577] client: lost peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:13:27.082 ThaliTest[2581:2192577] client session: onPeerLost: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:13:28.195 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:13:31.326 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:13:31.343 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:13:31.344 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:13:31.345 ThaliTest[2581:2192577] clien,t: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:13:46.983 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:13:57.432 ThaliTest[2581:2192577] client: lost peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:13:57.433 ThaliTest[2581:2192577] client session: onPeerLost: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:13:58.464 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:14:01.326 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:14:01.344 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:14:01.346 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:14:01.347 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:14:18.933 ThaliTest[2581:2192577] client: lost peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:14:18.933 ThaliTest[2581:2192577] client session: onPeerLost: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:14:19.040 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:14:27.311 ThaliTest[2581:2192577] client: lost peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:14:27.312 ThaliTest[2581:2192577] client session: onPeerLost: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:14:28.339 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:14:31.326 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:14:31.343 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:14:31.343 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:14:31.344 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:14:47.376 ThaliTest[2581:2192577] client: lost peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:14:47.377 ThaliTest[2581:2192577] client session: onPeerLost: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:15:01.325 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:15:01.341 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:15:01.342 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
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
,2015-12-03 12:15:31.326 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:15:31.340 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:15:31.342 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
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
,2015-12-03 12:16:01.326 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:16:01.341 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:16:01.342 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
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
,2015-12-03 12:16:31.324 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:16:31.340 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,2015-12-03 12:16:31.342 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
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
,2015-12-03 12:17:01.324 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:17:01.340 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:17:01.342 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
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
,2015-12-03 12:17:31.324 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:17:31.340 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:17:31.342 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
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
,2015-12-03 12:18:01.324 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:18:01.339 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:18:01.340 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
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
,2015-12-03 12:18:31.323 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:18:31.343 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:18:31.343 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
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
,2015-12-03 12:19:01.324 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:19:01.340 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:19:01.342 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
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
,2015-12-03 12:19:31.322 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:19:31.340 ThaliTest[2581:2192577] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:19:31.341 ThaliTest[2581:2192577] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
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
,2015-12-03 12:20:01.322 ThaliTest[2581:2192577] multipeer session: restart
,2015-12-03 12:20:01.328 ThaliTest[2581:2192577] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** First throw call stack:
(0x26e2efef 0x35798c8b 0x26d4aaa3 0x28e09d85 0x269326,07 0x26931e81 0x268ab3d3 0x26df4faf 0x26df43bf 0x26df2a25 0x26d3f201 0x26d3f013 0x2e7ca201 0x2a50ba09 0xd25e3 0x35d4aaaf)
libc++abi.dylib: terminating with uncaught exception of type NSException
,* thread #1: tid = 0x2174c1, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
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
    frame #13: 0x000d25e2 ThaliTest`main + 50

```
