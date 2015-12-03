#### Test 5065027835b6ad9_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027835b6ad9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/1921705B-E888-428F-AF77-AA6207A4B408/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/1921705B-E888-428F-AF77-AA6207A4B408/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027835b6ad9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027835b6ad9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/159E09CE-DF9B-4BC1-81B4-1F5C80383D6E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60260"
,(lldb)     command script import "/tmp/1921705B-E888-428F-AF77-AA6207A4B408/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 12:02:54.776 ThaliTest[2443:2288455] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2985C67B-D0EF-4BE7-8122-6A567F8982AD/Library/Cookies/Cookies.binarycookies
,2015-12-03 12:02:55.198 ThaliTest[2443:2288455] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 12:02:55.199 ThaliTest[2443:2288455] Multi-tasking -> Device: YES, App: YES
,2015-12-03 12:02:55.208 ThaliTest[2443:2288455] Unlimited access to network resources
,2015-12-03 12:02:55.216 ThaliTest[2443:2288455] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 12:02:58.794 ThaliTest[2443:2288455] Resetting plugins due to page load.
,2015-12-03 12:02:59.246 ThaliTest[2443:2288455] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/159E09CE-DF9B-4BC1-81B4-1F5C80383D6E/ThaliTest.app/www/index.html
,2015-12-03 12:02:59.401 ThaliTest[2443:2288455] JXcore Cordova plugin initializing
2015-12-03 12:02:59.403 ThaliTest[2443:2288568] JXcore instance initializing
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
,2015-12-03 12:04:02.491 ThaliTest[2443:2288568] jxcore: startBroadcasting
,2015-12-03 12:04:02.504 ThaliTest[2443:2288568] server: starting Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:04:02.505 ThaliTest[2443:2288568] multipeer session: start timer: 0x1a24abe0
2015-12-03 12:04:02.506 ThaliTest[2443:2288568] THEMultipeerSessi,on initialized peer Apple-Iphone5s-1_PT7153
2015-12-03 12:04:02.509 ThaliTest[2443:2288568] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-03 12:04:02.968 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5-1_PT2098.2PCWSw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2098.2PCWSw==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5-1_PT209,8.2PCWSw==, peerAvailable: true
weAreDoneNow
done, now sending data to server
CoordinatorConnector-debug: sendData
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT7153","time":490,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5-1_PT2098.2PCWSw==","peerAvailable":true,"time":488}]}
,peersList : 100% : 488 ms, 99% : 488 ms, 95 : 488 ms, 90% : 488 ms.
,Result count 1, range 488 ms to  488 ms.
,2015-12-03 12:04:03.031 ThaliTest[2443:2288455] client: found peer: Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:04.693 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.n7uNOA==
,CoordinatorConnector-debug: stop:undefined
,stop tests now !
stop current!
testFindPeers stopped
2015-12-03 12:04:05.394 ThaliTest[2443:2288568] jxcore: stopBroadcasting
,2015-12-03 12:04:05.394 ThaliTest[2443:2288568] THEMultipeerSession stopping peer
,2015-12-03 12:04:05.395 ThaliTest[2443:2288568] multipeer session: stop timer
,2015-12-03 12:04:05.396 ThaliTest[2443:2288568] jxcore: stopBroadcasting: success
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
,serverPort is 50116
,2015-12-03 12:04:05.468 ThaliTest[2443:2288568] jxcore: startBroadcasting
,2015-12-03 12:04:05.469 ThaliTest[2443:2288568] server: starting Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:04:05.470 ThaliTest[2443:2288568] multipeer session: start timer: 0x165b5fa0
,2015-12-03 12:04:05.470 ThaliTest[2443:2288568] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT7153
,2015-12-03 12:04:05.470 ThaliTest[2443:2288568] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-03T11:04:05.472Z SendDataTCPServer.js: TCP/IP server is bound to port: 50116
,2015-12-03 12:04:05.480 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.n7uNOA==
2015-12-03 12:04:05.481 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:04:05.481 ThaliTest[2443:2288455] clien,t: found peer: Apple-Iphone5-1_PT2098.2PCWSw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.n7uNOA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
device[1]: Apple-Iphone6-1_PT8234.n7uNOA==
2015-12-03T11:04:05.484Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8234.n7uNOA==
2015-12-03T11:04:05.484Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8234.n7uNOA==
,2015-12-03T11:04:05.484Z SendDataConnector.js: do connect now
2015-12-03 12:04:05.484 ThaliTest[2443:2288568] jxcore: connect Apple-Iphone6-1_PT8234.n7uNOA==
,2015-12-03 12:04:05.485 ThaliTest[2443:2288568] client session: connect
2015-12-03 12:04:05.485 ThaliTest[2443:2288568] client session: stateChange:0->1 Apple-Iphone6-1_PT8234.n7uNOA==
,2015-12-03 12:04:05.486 ThaliTest[2443:2288455] client: found peer: Apple-IpadAir2-1_PT7777.VxBn0g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.3coM6g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2098.2PCWSw==","peerName":"(null)",,"peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7777.VxBn0g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 12:04:05.623 ThaliTest[2443:2288455] client: lost peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:04:05.623 ThaliTest[2443:2288455] client session: onPeerLost: Apple-Iphone5s-1_PT7153.3coM6g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.3coM6g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 12:04:05.658 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 12:04:06.315 ThaliTest[2443:2288455] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7777.O0xngQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 12:04:06.366 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2098.P4cq9w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 12:04:07.724 ThaliTest[2443:2288455] client: lost peer: Apple-Iphone6-1_PT8234.n7uNOA==
2015-12-03 12:04:07.725 ThaliTest[2443:2288455] client session: onPeerLost: Apple-Iphone6-1_PT8234.n7uNOA==
2015-12-03 12:04:07.725 ThaliTest[2443:2288455], client session: onLinkFailure: Apple-Iphone6-1_PT8234.n7uNOA==
2015-12-03 12:04:07.726 ThaliTest[2443:2288455] client session: disconnect
2015-12-03 12:04:07.726 ThaliTest[2443:2288455] client session: stateChange:1->0 Apple-Iphone6-1_PT8234.n7uNOA==
2,015-12-03 12:04:07.727 ThaliTest[2443:2288455] client session: fireConnectCallback: Apple-Iphone6-1_PT8234.n7uNOA==
2015-12-03 12:04:07.728 ThaliTest[2443:2288455] jxcore: connect: fail: Peer disconnected
,2015-12-03T11:04:07.729Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T11:04:07.730Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-03T11:04:07.731Z SendDataConnector.js: tryAgain afer: 5000 ms.,
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.n7uNOA==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:04:09.276 ThaliTest[2443:2288455] client: lost peer: Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:09.276 ThaliTest[2443:2288455] client session: onPeerLost: Apple-IpadAir2-1_PT7777.VxBn0g==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-IpadAir2-1_PT7777.VxBn0g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 12:04:09.675 ThaliTest[2443:2288455] client: lost peer: Apple-Iphone5-1_PT2098.2PCWSw==
2015-12-03 12:04:09.676 ThaliTest[2443:2288455] client session: onPeerLost: Apple-Iphone5-1_PT2098.2PCWSw==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone5-1_PT2098.2PCWSw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03T11:04:12.737Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8234.n7uNOA==
,2015-12-03T11:04:12.738Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8234.n7uNOA==
,2015-12-03 12:04:15.921 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.3coM6g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,2015-12-03 12:04:17.751 ThaliTest[2443:2288568] jxcore: disconnect
2015-12-03 12:04:17.752 ThaliTest[2443:2288568] jxcore: disconnect: fail
2015-12-03T11:04:17.753Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8234.n7uNO,A==
2015-12-03T11:04:17.754Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT8234.n7uNOA== with availability status: true
2015-12-03T11:04:17.754Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8234.n7uNOA==
2,015-12-03T11:04:17.755Z SendDataConnector.js: do connect now
2015-12-03 12:04:17.756 ThaliTest[2443:2288568] jxcore: connect Apple-Iphone6-1_PT8234.n7uNOA==
2015-12-03 12:04:17.756 ThaliTest[2443:2288568] client: connect: unreachable Apple-Iphone6-1_PT82,34.n7uNOA==
2015-12-03 12:04:17.757 ThaliTest[2443:2288568] jxcore: connect: fail: Peer unreachable
,2015-12-03T11:04:17.758Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-03T11:04:17.758Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-03T11:04:17.759Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:04:22.762Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8234.n7uNOA==
,2015-12-03T11:04:22.763Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8234.n7uNOA==
,2015-12-03 12:04:27.764 ThaliTest[2443:2288568] jxcore: disconnect
2015-12-03 12:04:27.765 ThaliTest[2443:2288568] jxcore: disconnect: fail
2015-12-03T11:04:27.766Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8234.n7uNO,A==
2015-12-03T11:04:27.766Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT8234.n7uNOA== with availability status: true
2015-12-03T11:04:27.767Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8234.n7uNOA==
,2015-12-03T11:04:27.767Z SendDataConnector.js: do connect now
2015-12-03 12:04:27.768 ThaliTest[2443:2288568] jxcore: connect Apple-Iphone6-1_PT8234.n7uNOA==
,2015-12-03 12:04:27.769 ThaliTest[2443:2288568] client: connect: unreachable Apple-Iphone6-1_PT8234.n7uNOA==
,2015-12-03 12:04:27.769 ThaliTest[2443:2288568] jxcore: connect: fail: Peer unreachable
,2015-12-03T11:04:27.770Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-03T11:04:27.772Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-03T11:04:27.772Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:04:32.784Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8234.n7uNOA==
,2015-12-03T11:04:32.785Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8234.n7uNOA==
,2015-12-03 12:04:35.471 ThaliTest[2443:2288455] multipeer session: restart
,2015-12-03 12:04:35.497 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:04:35.499 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:04:35.500 ThaliTest[2443:2288455] clien,t: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:04:35.501 ThaliTest[2443:2288455] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:04:37.791 ThaliTest[2443:2288568] jxcore: disconnect
2015-12-03 12:04:37.792 ThaliTest[2443:2288568] jxcore: disconnect: fail
2015-12-03T11:04:37.793Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8234.n7uNO,A==
2015-12-03T11:04:37.793Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT8234.n7uNOA== with availability status: true
,2015-12-03T11:04:37.793Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8234.n7uNOA==
2015-12-03T11:04:37.794Z SendDataConnector.js: do connect now
2015-12-03 12:04:37.794 ThaliTest[2443:2288568] jxcore: connect Apple-Iphone6-1_PT8234,.n7uNOA==
,2015-12-03 12:04:37.795 ThaliTest[2443:2288568] client: connect: unreachable Apple-Iphone6-1_PT8234.n7uNOA==
,2015-12-03 12:04:37.797 ThaliTest[2443:2288568] jxcore: connect: fail: Peer unreachable
,2015-12-03T11:04:37.798Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-03T11:04:37.799Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-03T11:04:37.799Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:04:42.806Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8234.n7uNOA==
,2015-12-03T11:04:42.807Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8234.n7uNOA==
,2015-12-03 12:04:47.817 ThaliTest[2443:2288568] jxcore: disconnect
2015-12-03 12:04:47.818 ThaliTest[2443:2288568] jxcore: disconnect: fail
2015-12-03T11:04:47.819Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8234.n7uNO,A==
2015-12-03T11:04:47.820Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT8234.n7uNOA== with availability status: true
2015-12-03T11:04:47.820Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8234.n7uNOA==
,2015-12-03T11:04:47.821Z SendDataConnector.js: do connect now
,2015-12-03 12:04:47.822 ThaliTest[2443:2288568] jxcore: connect Apple-Iphone6-1_PT8234.n7uNOA==
,2015-12-03 12:04:47.823 ThaliTest[2443:2288568] client: connect: unreachable Apple-Iphone6-1_PT8234.n7uNOA==
,2015-12-03 12:04:47.824 ThaliTest[2443:2288568] jxcore: connect: fail: Peer unreachable
2015-12-03T11:04:47.825Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-03T11:04:47.825Z SendDataConnector.js: CLIENT Can not Connect: P,eer unreachable
oneRoundDownNow
oneRoundDownNow:2
,2015-12-03T11:04:47.828Z SendDataConnector.js: CLIENT Stop now
,2015-12-03 12:04:47.829 ThaliTest[2443:2288568] jxcore: disconnect
2015-12-03 12:04:47.829 ThaliTest[2443:2288568] jxcore: disconnect: fail
2015-12-03T11:04:47.830Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8234.n7uNO,A==
,---- round done--------
,device[2]: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03T11:04:47.833Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03T11:04:47.834Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03T11:04:47.834Z SendDataConnector.js: do connect now
,2015-12-03 12:04:47.835 ThaliTest[2443:2288568] jxcore: connect Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:04:47.836 ThaliTest[2443:2288568] client session: connect
2015-12-03 12:04:47.837 ThaliTest[2443:2288568] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:04:48.093 ThaliTest[2443:2288455] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:04:48.093 ThaliTest[2443:2288455] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 12:04:48.164 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 12:04:52.881 ThaliTest[2443:2288455] multipeer session: reset timer
2015-12-03 12:04:52.881 ThaliTest[2443:2288455] multipeer session: stop timer
2015-12-03 12:04:52.882 ThaliTest[2443:2288455] multipeer session: start timer: 0x165b5fa0
2015-,12-03 12:04:52.883 ThaliTest[2443:2288455] server session: connect
2015-12-03 12:04:52.883 ThaliTest[2443:2288455] server session: stateChange:0->1 Apple-IpadAir2-1_PT7777
,2015-12-03 12:04:52.892 ThaliTest[2443:2288455] server: accepting invitation Apple-IpadAir2-1_PT7777
,2015-12-03 12:04:55.501 ThaliTest[2443:2288746] server session: connected
2015-12-03 12:04:55.502 ThaliTest[2443:2288746] server session: stateChange:1->2 Apple-IpadAir2-1_PT7777
,2015-12-03 12:04:55.525 ThaliTest[2443:2288455] server relay: connected (to port: 50116)
,2015-12-03T11:04:55.532Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:04:55.746Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-03T11:04:55.762Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-03T11:04:55.778Z SendDataTCPServer.js: TCP/IP server has received 54608 bytes of data
,2015-12-03T11:04:55.797Z SendDataTCPServer.js: TCP/IP server has received 80888 bytes of data
,2015-12-03T11:04:55.816Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 12:04:55.867 ThaliTest[2443:2288746] server session: not connected Apple-IpadAir2-1_PT7777
,2015-12-03 12:05:20.844 ThaliTest[2443:2288878] client session: not connected Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:05:20.845 ThaliTest[2443:2288878] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:05:20.845 ThaliTe,st[2443:2288878] client session: disconnect
2015-12-03 12:05:20.846 ThaliTest[2443:2288878] client session: stateChange:1->0 Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:05:20.846 ThaliTest[2443:2288878] client session: fireConnectCallback: Apple-Iphon,e5s-1_PT7153.3coM6g==
2015-12-03 12:05:20.847 ThaliTest[2443:2288878] jxcore: connect: fail: Peer disconnected
,2015-12-03T11:05:20.849Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T11:05:20.850Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-03T11:05:20.851Z SendDataConnector.js: tryAgain afer: 5000 ms.,
,2015-12-03 12:05:22.883 ThaliTest[2443:2288455] multipeer session: restart
,2015-12-03 12:05:22.903 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:05:22.906 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:05:22.907 ThaliTest[2443:2288455] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:05:22.913 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,2015-12-03T11:05:25.853Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03T11:05:25.854Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:05:30.866 ThaliTest[2443:2288568] jxcore: disconnect
2015-12-03 12:05:30.867 ThaliTest[2443:2288568] jxcore: disconnect: fail
2015-12-03T11:05:30.868Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.3coM,6g==
2015-12-03T11:05:30.868Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT7153.3coM6g== with availability status: true
2015-12-03T11:05:30.869Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.3coM6g==,
,2015-12-03T11:05:30.870Z SendDataConnector.js: do connect now
2015-12-03 12:05:30.871 ThaliTest[2443:2288568] jxcore: connect Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:05:30.872 ThaliTest[2443:2288568] client session: connect
,2015-12-03 12:05:30.872 ThaliTest[2443:2288568] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:05:52.884 ThaliTest[2443:2288455] multipeer session: restart
,2015-12-03 12:05:52.916 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:05:52.918 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:05:52.919 ThaliTest[2443:2288455] clien,t: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:05:52.920 ThaliTest[2443:2288455] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:06:03.881 ThaliTest[2443:2288927] client session: not connected Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:06:03.882 ThaliTest[2443:2288927] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:06:03.882 ThaliTe,st[2443:2288927] client session: disconnect
2015-12-03 12:06:03.883 ThaliTest[2443:2288927] client session: stateChange:1->0 Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:06:03.884 ThaliTest[2443:2288927] client session: fireConnectCallback: Apple-Iphon,e5s-1_PT7153.3coM6g==
2015-12-03 12:06:03.884 ThaliTest[2443:2288927] jxcore: connect: fail: Peer disconnected
,2015-12-03T11:06:03.886Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T11:06:03.887Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-03T11:06:03.887Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:06:08.899Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03T11:06:08.900Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:13.912 ThaliTest[2443:2288568] jxcore: disconnect
2015-12-03 12:06:13.912 ThaliTest[2443:2288568] jxcore: disconnect: fail
2015-12-03T11:06:13.913Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.3coM,6g==
2015-12-03T11:06:13.914Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT7153.3coM6g== with availability status: true
,2015-12-03T11:06:13.914Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03T11:06:13.914Z SendDataConnector.js: do connect now
,2015-12-03 12:06:13.915 ThaliTest[2443:2288568] jxcore: connect Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:13.917 ThaliTest[2443:2288568] client session: connect
,2015-12-03 12:06:13.918 ThaliTest[2443:2288568] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:22.884 ThaliTest[2443:2288455] multipeer session: restart
,2015-12-03 12:06:22.920 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:06:22.921 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:06:22.922 ThaliTest[2443:2288455] clien,t: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:06:22.923 ThaliTest[2443:2288455] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:06:46.922 ThaliTest[2443:2289030] client session: not connected Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:06:46.923 ThaliTest[2443:2289030] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:06:46.923 ThaliTe,st[2443:2289030] client session: disconnect
2015-12-03 12:06:46.924 ThaliTest[2443:2289030] client session: stateChange:1->0 Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:06:46.925 ThaliTest[2443:2289030] client session: fireConnectCallback: Apple-Iphon,e5s-1_PT7153.3coM6g==
2015-12-03 12:06:46.925 ThaliTest[2443:2289030] jxcore: connect: fail: Peer disconnected
,2015-12-03T11:06:46.927Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T11:06:46.928Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-03T11:06:46.928Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:06:51.941Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03T11:06:51.942Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:52.883 ThaliTest[2443:2288455] multipeer session: restart
,2015-12-03 12:06:52.905 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:06:52.906 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:06:52.909 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:06:52.910 ThaliTest[2443:2288455] clien,t: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:06:56.953 ThaliTest[2443:2288568] jxcore: disconnect
2015-12-03 12:06:56.954 ThaliTest[2443:2288568] jxcore: disconnect: fail
2015-12-03T11:06:56.955Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.3coM,6g==
2015-12-03T11:06:56.955Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT7153.3coM6g== with availability status: true
,2015-12-03T11:06:56.956Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03T11:06:56.956Z SendDataConnector.js: do connect now
,2015-12-03 12:06:56.957 ThaliTest[2443:2288568] jxcore: connect Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:56.958 ThaliTest[2443:2288568] client session: connect
2015-12-03 12:06:56.959 ThaliTest[2443:2288568] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:07:03.452 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:07:22.883 ThaliTest[2443:2288455] multipeer session: restart
,2015-12-03 12:07:22.906 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:07:22.911 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,2015-12-03 12:07:22.913 ThaliTest[2443:2288455] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:07:22.914 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:07:29.967 ThaliTest[2443:2289102] client session: not connected Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:07:29.968 ThaliTest[2443:2289102] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:07:29.969 ThaliTe,st[2443:2289102] client session: disconnect
2015-12-03 12:07:29.969 ThaliTest[2443:2289102] client session: stateChange:1->0 Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:07:29.970 ThaliTest[2443:2289102] client session: fireConnectCallback: Apple-Iphon,e5s-1_PT7153.3coM6g==
2015-12-03 12:07:29.970 ThaliTest[2443:2289102] jxcore: connect: fail: Peer disconnected
,2015-12-03T11:07:29.972Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T11:07:29.973Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-03T11:07:29.973Z SendDataConnector.js: tryAgain afer: 5000 ms.,
,2015-12-03 12:07:33.722 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03T11:07:34.978Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03T11:07:34.979Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:07:39.988 ThaliTest[2443:2288568] jxcore: disconnect
2015-12-03 12:07:39.990 ThaliTest[2443:2288568] jxcore: disconnect: fail
2015-12-03T11:07:39.990Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.3coM,6g==
2015-12-03T11:07:39.991Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT7153.3coM6g== with availability status: true
,2015-12-03T11:07:39.991Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03T11:07:39.991Z SendDataConnector.js: do connect now
2015-12-03 12:07:39.992 ThaliTest[2443:2288568] jxcore: connect Apple-Iphone5s-1_PT71,53.3coM6g==
,2015-12-03 12:07:39.993 ThaliTest[2443:2288568] client session: connect
,2015-12-03 12:07:39.994 ThaliTest[2443:2288568] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:07:52.883 ThaliTest[2443:2288455] multipeer session: restart
,2015-12-03 12:07:52.913 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:07:52.917 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:07:52.917 ThaliTest[2443:2288455] clien,t: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:07:52.918 ThaliTest[2443:2288455] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:08:01.504 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:08:03.601 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:08:12.167 ThaliTest[2443:2288455] multipeer session: reset timer
2015-12-03 12:08:12.168 ThaliTest[2443:2288455] multipeer session: stop timer
2015-12-03 12:08:12.169 ThaliTest[2443:2288455] multipeer session: start timer: 0x165b5fa0
2015-,12-03 12:08:12.170 ThaliTest[2443:2288455] server session: connect
2015-12-03 12:08:12.170 ThaliTest[2443:2288455] server session: stateChange:0->1 Apple-Iphone5-1_PT2098
,2015-12-03 12:08:12.178 ThaliTest[2443:2288455] server: accepting invitation Apple-Iphone5-1_PT2098
,2015-12-03 12:08:12.316 ThaliTest[2443:2288455] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:08:12.316 ThaliTest[2443:2288455] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 12:08:12.512 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-12-03 12:08:13.002 ThaliTest[2443:2289209] client session: not connected Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:08:13.003 ThaliTest[2443:2289209] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:08:13.004 ThaliTe,st[2443:2289209] client session: disconnect
2015-12-03 12:08:13.005 ThaliTest[2443:2289209] client session: stateChange:1->0 Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:08:13.005 ThaliTest[2443:2289209] client session: fireConnectCallback: Apple-Iphon,e5s-1_PT7153.3coM6g==
2015-12-03 12:08:13.006 ThaliTest[2443:2289209] jxcore: connect: fail: Peer disconnected
,2015-12-03T11:08:13.008Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T11:08:13.008Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
oneRoundDownNow
oneRoundDownNow:2
,2015-12-03T11:08:13.010Z SendDataConnector.js: CLIENT Stop now
,2015-12-03 12:08:13.011 ThaliTest[2443:2288568] jxcore: disconnect
2015-12-03 12:08:13.012 ThaliTest[2443:2288568] jxcore: disconnect: fail
2015-12-03T11:08:13.012Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.3coM6g==
---- round done--------
device[3]: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03T11:08:13.014Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03T11:08:13.015Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03T11:08:13.015Z SendDataConnector.js: do connect now
,2015-12-03 12:08:13.016 ThaliTest[2443:2288568] jxcore: connect Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:08:13.017 ThaliTest[2443:2288568] client session: connect
2015-12-03 12:08:13.018 ThaliTest[2443:2288568] client session: stateChange:0->1 Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:08:13.595 ThaliTest[2443:2288455] multipeer session: reset timer
2015-12-03 12:08:13.595 ThaliTest[2443:2288455] multipeer session: stop timer
2015-12-03 12:08:13.596 ThaliTest[2443:2288455] multipeer session: start timer: 0x165b5fa0
2015-,12-03 12:08:13.597 ThaliTest[2443:2288455] server session: connect
2015-12-03 12:08:13.597 ThaliTest[2443:2288455] server session: stateChange:0->1 Apple-Iphone6-1_PT8234
,2015-12-03 12:08:13.617 ThaliTest[2443:2288455] server: accepting invitation Apple-Iphone6-1_PT8234
,2015-12-03 12:08:14.624 ThaliTest[2443:2289207] server session: connected
2015-12-03 12:08:14.625 ThaliTest[2443:2289207] server session: stateChange:1->2 Apple-Iphone5-1_PT2098
,2015-12-03 12:08:14.631 ThaliTest[2443:2288455] server relay: connected (to port: 50116)
2015-12-03T11:08:14.634Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:08:15.149Z SendDataTCPServer.js: TCP/IP server has received 7936 bytes of data
,2015-12-03T11:08:15.167Z SendDataTCPServer.js: TCP/IP server has received 20832 bytes of data
,2015-12-03T11:08:15.183Z SendDataTCPServer.js: TCP/IP server has received 30752 bytes of data
,2015-12-03T11:08:15.201Z SendDataTCPServer.js: TCP/IP server has received 40672 bytes of data
,2015-12-03T11:08:15.217Z SendDataTCPServer.js: TCP/IP server has received 55552 bytes of data
,2015-12-03T11:08:15.237Z SendDataTCPServer.js: TCP/IP server has received 67456 bytes of data
,2015-12-03T11:08:15.250Z SendDataTCPServer.js: TCP/IP server has received 86304 bytes of data
,2015-12-03T11:08:15.264Z SendDataTCPServer.js: TCP/IP server has received 96224 bytes of data
,2015-12-03T11:08:15.278Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 12:08:15.860 ThaliTest[2443:2289207] client session: connected
2015-12-03 12:08:15.861 ThaliTest[2443:2289162] server session: connected
2015-12-03 12:08:15.861 ThaliTest[2443:2289207] client session: stateChange:1->2 Apple-Iphone6-1_PT8234.+H,w2qA==
2015-12-03 12:08:15.862 ThaliTest[2443:2289162] server session: stateChange:1->2 Apple-Iphone6-1_PT8234
,2015-12-03 12:08:15.871 ThaliTest[2443:2289162] client session: fireConnectCallback: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:08:15.872 ThaliTest[2443:2289162] jxcore: connect: success
2015-12-03T11:08:15.875Z SendDataTCPServer.js: TCP/IP server con,nected
2015-12-03T11:08:15.876Z SendDataConnector.js: CLIENT connected to 50146, error: null
2015-12-03T11:08:15.876Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:08:15.882 ThaliTest[2443:2288455] client: relay established
2015-12-03 12:08:15.882 ThaliTest[2443:2288455] client: new accepted socket: 0x1a3e5c80
2015-12-03 12:08:15.884 ThaliTest[2443:2288455] server relay: connected (to port: 50116)
,2015-12-03T11:08:15.898Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T11:08:16.199Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-03T11:08:16.208Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-03T11:08:16.221Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03T11:08:16.222Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-03T11:08:16.222Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,oneRoundDownNow:2
,2015-12-03T11:08:16.223Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T11:08:16.223Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 12:08:16.224 ThaliTest[2443:2288568] jxcore: disconnect
,2015-12-03 12:08:16.225 ThaliTest[2443:2288568] client session: disconnectFromPeer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:08:16.225 ThaliTest[2443:2288568] client session: disconnect
,2015-12-03 12:08:16.226 ThaliTest[2443:2288568] client session: stateChange:2->0 Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:08:16.285 ThaliTest[2443:2288568] jxcore: disconnect: success
,2015-12-03T11:08:16.286Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8234.+Hw2qA==
---- round done--------
,device[4]: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03T11:08:16.287Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03T11:08:16.287Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03T11:08:16.288Z SendDataConnector.js: do connect now
,2015-12-03 12:08:16.288 ThaliTest[2443:2288568] jxcore: connect Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:08:16.289 ThaliTest[2443:2288568] client session: connect
,2015-12-03 12:08:16.290 ThaliTest[2443:2288568] client session: stateChange:0->1 Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:08:19.405 ThaliTest[2443:2289168] client session: connected
2015-12-03 12:08:19.405 ThaliTest[2443:2289168] client session: stateChange:1->2 Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:08:19.413 ThaliTest[2443:2289162] client session: fireConnectCallback: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:08:19.414 ThaliTest[2443:2289162] jxcore: connect: success
2015-12-03T11:08:19.415Z SendDataConnector.js: CLIENT connected to 50150, error: null
,2015-12-03T11:08:19.416Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:08:19.419 ThaliTest[2443:2288455] client: relay established
2015-12-03 12:08:19.420 ThaliTest[2443:2288455] client: new accepted socket: 0x1a3e76b0
,2015-12-03T11:08:19.430Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T11:08:19.707Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-03T11:08:19.719Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03 12:08:25.284 ThaliTest[2443:2289162] server session: not connected Apple-Iphone5-1_PT2098
,2015-12-03 12:08:26.278 ThaliTest[2443:2289162] server session: not connected Apple-Iphone6-1_PT8234
,2015-12-03T11:08:29.720Z SendDataConnector.js: Receiving data timeout now
2015-12-03T11:08:29.721Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:08:29.722Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:08:29.722Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:08:29.723Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 12:08:29.726 ThaliTest[2443:2288455] client: socket closed
2015-12-03 12:08:29.726 ThaliTest[2443:2288455] client relay: socket disconnected
2015-12-03 12:08:29.727 ThaliTest[2443:2288455] client relay: 0x1a3e76b0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1a21fa20 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 12:08:29.728 ThaliTest[2443:2288455] client session: socket closed: Apple-IpadAir2-1_PT7777.O0xng,Q==
2015-12-03 12:08:29.728 ThaliTest[2443:2288455] client session: onLinkFailure: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:08:29.729 ThaliTest[2443:2288455] client session: disconnect
2015-12-03 12:08:29.729 ThaliTest[2443:2288455] client session,: stateChange:2->0 Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:08:29.731 ThaliTest[2443:2288455] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03T11:08:34.735Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03T11:08:34.736Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:08:35.753 ThaliTest[2443:2288455] multipeer session: reset timer
2015-12-03 12:08:35.754 ThaliTest[2443:2288455] multipeer session: stop timer
2015-12-03 12:08:35.755 ThaliTest[2443:2288455] multipeer session: start timer: 0x165b5fa0
2015-,12-03 12:08:35.756 ThaliTest[2443:2288455] server: disconnecting to refresh session (Apple-Iphone5-1_PT2098)
2015-12-03 12:08:35.757 ThaliTest[2443:2288455] server session: disconnect
2015-12-03 12:08:35.757 ThaliTest[2443:2288455] server session: stateChange:2->0 Apple-Iphone5-1_PT2098
,2015-12-03T11:08:35.764Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 12:08:35.764 ThaliTest[2443:2288455] server session: connect
2015-12-03 12:08:35.765 ThaliTest[2443:2288455] server session: stateChange:0->1 Apple-Iphone5-1_PT2098
,2015-12-03 12:08:35.775 ThaliTest[2443:2288455] server: accepting invitation Apple-Iphone5-1_PT2098
,2015-12-03 12:08:36.766 ThaliTest[2443:2288455] multipeer session: reset timer
2015-12-03 12:08:36.768 ThaliTest[2443:2288455] multipeer session: stop timer
2015-12-03 12:08:36.768 ThaliTest[2443:2288455] multipeer session: start timer: 0x165b5fa0
2015-,12-03 12:08:36.769 ThaliTest[2443:2288455] server: disconnecting to refresh session (Apple-Iphone6-1_PT8234)
2015-12-03 12:08:36.770 ThaliTest[2443:2288455] server session: disconnect
2015-12-03 12:08:36.770 ThaliTest[2443:2288455] server session: stateC,hange:2->0 Apple-Iphone6-1_PT8234
2015-12-03 12:08:36.774 ThaliTest[2443:2288455] server session: connect
2015-12-03 12:08:36.775 ThaliTest[2443:2288455] server session: stateChange:0->1 Apple-Iphone6-1_PT8234
2015-12-03T11:08:36.780Z SendDataTCPServer.,js: TCP/IP server is ended
,2015-12-03 12:08:36.795 ThaliTest[2443:2288455] server: accepting invitation Apple-Iphone6-1_PT8234
,2015-12-03 12:08:38.221 ThaliTest[2443:2289267] server session: connected
2015-12-03 12:08:38.222 ThaliTest[2443:2289267] server session: stateChange:1->2 Apple-Iphone5-1_PT2098
,2015-12-03 12:08:38.229 ThaliTest[2443:2288455] server relay: connected (to port: 50116)
,2015-12-03T11:08:38.238Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:08:38.330Z SendDataTCPServer.js: TCP/IP server has received 8928 bytes of data
,2015-12-03T11:08:38.343Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 12:08:38.983 ThaliTest[2443:2289254] server session: connected
2015-12-03 12:08:38.984 ThaliTest[2443:2289254] server session: stateChange:1->2 Apple-Iphone6-1_PT8234
,2015-12-03 12:08:38.991 ThaliTest[2443:2288455] server relay: connected (to port: 50116)
2015-12-03T11:08:38.994Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:08:39.080Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-03T11:08:39.096Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 12:08:39.744 ThaliTest[2443:2288568] jxcore: disconnect
2015-12-03 12:08:39.745 ThaliTest[2443:2288568] jxcore: disconnect: fail
2015-12-03T11:08:39.745Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7777.O0xn,gQ==
2015-12-03T11:08:39.746Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT7777.O0xngQ== with availability status: true
,2015-12-03T11:08:39.747Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03T11:08:39.747Z SendDataConnector.js: do connect now
,2015-12-03 12:08:39.748 ThaliTest[2443:2288568] jxcore: connect Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:08:39.749 ThaliTest[2443:2288568] client session: connect
2015-12-03 12:08:39.750 ThaliTest[2443:2288568] client session: stateChange:0->1 Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:08:42.424 ThaliTest[2443:2289254] client session: connected
2015-12-03 12:08:42.424 ThaliTest[2443:2289254] client session: stateChange:1->2 Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:08:42.431 ThaliTest[2443:2289253] client session: fireConnectCallback: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:08:42.432 ThaliTest[2443:2289253] jxcore: connect: success
2015-12-03T11:08:42.433Z SendDataConnector.js: CLIENT connected, to 50155, error: null
,2015-12-03T11:08:42.434Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:08:42.439 ThaliTest[2443:2288455] client: relay established
2015-12-03 12:08:42.440 ThaliTest[2443:2288455] client: new accepted socket: 0x1a3e7a20
,2015-12-03T11:08:42.450Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 12:08:46.635 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:08:48.322 ThaliTest[2443:2289168] server session: not connected Apple-Iphone5-1_PT2098
,2015-12-03 12:08:49.202 ThaliTest[2443:2289168] server session: not connected Apple-Iphone6-1_PT8234
,2015-12-03 12:08:52.503 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03T11:08:52.520Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T11:08:52.520Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:08:52.521Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:08:52.522Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:08:52.523Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 12:08:52.524 ThaliTest[2443:2288455] client: socket closed
2015-12-03 12:08:52.525 ThaliTest[2443:2288455] client relay: socket disconnected
2015-12-03 12:08:52.526 ThaliTest[2443:2288455] client relay: 0x1a3e7a20 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1a3bcbd0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 12:08:52.526 ThaliTest[2443:2288455] client session: socket closed: Apple-IpadAir2-1_PT7777.O0xng,Q==
2015-12-03 12:08:52.527 ThaliTest[2443:2288455] client session: onLinkFailure: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:08:52.528 ThaliTest[2443:2288455] client session: disconnect
2015-12-03 12:08:52.528 ThaliTest[2443:2288455] client session,: stateChange:2->0 Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:08:52.530 ThaliTest[2443:2288455] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03T11:08:57.527Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03T11:08:57.527Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:08:58.695 ThaliTest[2443:2288455] multipeer session: reset timer
2015-12-03 12:08:58.696 ThaliTest[2443:2288455] multipeer session: stop timer
2015-12-03 12:08:58.696 ThaliTest[2443:2288455] multipeer session: start timer: 0x165b5fa0
2015-,12-03 12:08:58.697 ThaliTest[2443:2288455] server: disconnecting to refresh session (Apple-Iphone5-1_PT2098)
2015-12-03 12:08:58.697 ThaliTest[2443:2288455] server session: disconnect
2015-12-03 12:08:58.698 ThaliTest[2443:2288455] server session: stateC,hange:2->0 Apple-Iphone5-1_PT2098
2015-12-03 12:08:58.703 ThaliTest[2443:2288455] server session: connect
2015-12-03 12:08:58.704 ThaliTest[2443:2288455] server session: stateChange:0->1 Apple-Iphone5-1_PT2098
,2015-12-03T11:08:58.719Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 12:08:58.726 ThaliTest[2443:2288455] server: accepting invitation Apple-Iphone5-1_PT2098
,2015-12-03 12:08:59.283 ThaliTest[2443:2288455] multipeer session: reset timer
2015-12-03 12:08:59.284 ThaliTest[2443:2288455] multipeer session: stop timer
2015-12-03 12:08:59.285 ThaliTest[2443:2288455] multipeer session: start timer: 0x165b5fa0
2015-,12-03 12:08:59.285 ThaliTest[2443:2288455] server: disconnecting to refresh session (Apple-Iphone6-1_PT8234)
2015-12-03 12:08:59.286 ThaliTest[2443:2288455] server session: disconnect
2015-12-03 12:08:59.286 ThaliTest[2443:2288455] server session: stateC,hange:2->0 Apple-Iphone6-1_PT8234
2015-12-03 12:08:59.290 ThaliTest[2443:2288455] server session: connect
2015-12-03T11:08:59.292Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 12:08:59.291 ThaliTest[2443:2288455] server session: stateChange:0,->1 Apple-Iphone6-1_PT8234
,2015-12-03 12:08:59.311 ThaliTest[2443:2288455] server: accepting invitation Apple-Iphone6-1_PT8234
,2015-12-03 12:09:00.908 ThaliTest[2443:2289299] server session: connected
2015-12-03 12:09:00.909 ThaliTest[2443:2289299] server session: stateChange:1->2 Apple-Iphone5-1_PT2098
,2015-12-03 12:09:00.915 ThaliTest[2443:2288455] server relay: connected (to port: 50116)
2015-12-03T11:09:00.922Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:09:01.050Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 12:09:01.572 ThaliTest[2443:2289299] server session: connected
2015-12-03 12:09:01.573 ThaliTest[2443:2289299] server session: stateChange:1->2 Apple-Iphone6-1_PT8234
,2015-12-03 12:09:01.579 ThaliTest[2443:2288455] server relay: connected (to port: 50116)
2015-12-03T11:09:01.582Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:09:01.673Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-03T11:09:01.688Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 12:09:02.532 ThaliTest[2443:2288568] jxcore: disconnect
2015-12-03 12:09:02.533 ThaliTest[2443:2288568] jxcore: disconnect: fail
2015-12-03T11:09:02.534Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7777.O0xn,gQ==
2015-12-03T11:09:02.534Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT7777.O0xngQ== with availability status: true
2015-12-03T11:09:02.534Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7777.O0xngQ==,
,2015-12-03T11:09:02.535Z SendDataConnector.js: do connect now
2015-12-03 12:09:02.536 ThaliTest[2443:2288568] jxcore: connect Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:09:02.537 ThaliTest[2443:2288568] client session: connect
,2015-12-03 12:09:02.537 ThaliTest[2443:2288568] client session: stateChange:0->1 Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:09:05.530 ThaliTest[2443:2289299] client session: connected
2015-12-03 12:09:05.531 ThaliTest[2443:2289299] client session: stateChange:1->2 Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:09:05.538 ThaliTest[2443:2289299] client session: fireConnectCallback: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:09:05.539 ThaliTest[2443:2289299] jxcore: connect: success
2015-12-03T11:09:05.541Z SendDataConnector.js: CLIENT connected to 50160, error: null
,2015-12-03T11:09:05.542Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:09:05.547 ThaliTest[2443:2288455] client: relay established
2015-12-03 12:09:05.548 ThaliTest[2443:2288455] client: new accepted socket: 0x1a3e9760
,2015-12-03T11:09:05.560Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 12:09:11.232 ThaliTest[2443:2289299] server session: not connected Apple-Iphone5-1_PT2098
,2015-12-03 12:09:11.740 ThaliTest[2443:2289253] server session: not connected Apple-Iphone6-1_PT8234
,2015-12-03T11:09:15.633Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T11:09:15.634Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:09:15.634Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:09:15.635Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:09:15.636Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 12:09:15.637 ThaliTest[2443:2288455] client: socket closed
2015-12-03 12:09:15.638 ThaliTest[2443:2288455] client relay: socket disconnected
2015-12-03 12:09:15.639 ThaliTest[2443:2288455] client relay: 0x1a3e9760 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1a3e8510 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 12:09:15.639 ThaliTest[2443:2288455] client session: socket closed: Apple-IpadAir2-1_PT7777.O0xng,Q==
2015-12-03 12:09:15.640 ThaliTest[2443:2288455] client session: onLinkFailure: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:09:15.640 ThaliTest[2443:2288455] client session: disconnect
2015-12-03 12:09:15.641 ThaliTest[2443:2288455] client session,: stateChange:2->0 Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:09:15.642 ThaliTest[2443:2288455] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:09:18.571 ThaliTest[2443:2288455] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:09:18.572 ThaliTest[2443:2288455] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,2015-12-03T11:09:20.644Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03T11:09:20.644Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:09:21.216 ThaliTest[2443:2288455] multipeer session: reset timer
2015-12-03 12:09:21.217 ThaliTest[2443:2288455] multipeer session: stop timer
2015-12-03 12:09:21.217 ThaliTest[2443:2288455] multipeer session: start timer: 0x165b5fa0
2015-,12-03 12:09:21.218 ThaliTest[2443:2288455] server: disconnecting to refresh session (Apple-Iphone5-1_PT2098)
2015-12-03 12:09:21.219 ThaliTest[2443:2288455] server session: disconnect
2015-12-03 12:09:21.220 ThaliTest[2443:2288455] server session: stateC,hange:2->0 Apple-Iphone5-1_PT2098
2015-12-03T11:09:21.226Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 12:09:21.285 ThaliTest[2443:2288455] server session: connect
2015-12-03 12:09:21.285 ThaliTest[2443:2288455] server session: stateChange:0->1 Apple-Iphone5-1_PT2098
,2015-12-03 12:09:21.292 ThaliTest[2443:2288455] server: accepting invitation Apple-Iphone5-1_PT2098
,2015-12-03 12:09:21.801 ThaliTest[2443:2288455] multipeer session: reset timer
2015-12-03 12:09:21.802 ThaliTest[2443:2288455] multipeer session: stop timer
2015-12-03 12:09:21.803 ThaliTest[2443:2288455] multipeer session: start timer: 0x165b5fa0
2015-,12-03 12:09:21.804 ThaliTest[2443:2288455] server: disconnecting to refresh session (Apple-Iphone6-1_PT8234)
2015-12-03 12:09:21.804 ThaliTest[2443:2288455] server session: disconnect
2015-12-03 12:09:21.805 ThaliTest[2443:2288455] server session: stateC,hange:2->0 Apple-Iphone6-1_PT8234
2015-12-03 12:09:21.808 ThaliTest[2443:2288455] server session: connect
2015-12-03 12:09:21.808 ThaliTest[2443:2288455] server session: stateChange:0->1 Apple-Iphone6-1_PT8234
,2015-12-03T11:09:21.819Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 12:09:21.830 ThaliTest[2443:2288455] server: accepting invitation Apple-Iphone6-1_PT8234
,2015-12-03 12:09:23.447 ThaliTest[2443:2289375] server session: connected
2015-12-03 12:09:23.447 ThaliTest[2443:2289375] server session: stateChange:1->2 Apple-Iphone5-1_PT2098
,2015-12-03 12:09:23.454 ThaliTest[2443:2288455] server relay: connected (to port: 50116)
,2015-12-03T11:09:23.458Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:09:23.590Z SendDataTCPServer.js: TCP/IP server has received 9920 bytes of data
,2015-12-03T11:09:23.604Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 12:09:24.008 ThaliTest[2443:2289354] server session: connected
2015-12-03 12:09:24.009 ThaliTest[2443:2289354] server session: stateChange:1->2 Apple-Iphone6-1_PT8234
,2015-12-03 12:09:24.014 ThaliTest[2443:2288455] server relay: connected (to port: 50116)
2015-12-03T11:09:24.017Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:09:24.121Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 12:09:25.653 ThaliTest[2443:2288568] jxcore: disconnect
2015-12-03 12:09:25.654 ThaliTest[2443:2288568] jxcore: disconnect: fail
2015-12-03T11:09:25.655Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7777.O0xn,gQ==
2015-12-03T11:09:25.655Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT7777.O0xngQ== with availability status: true
,2015-12-03T11:09:25.656Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03T11:09:25.656Z SendDataConnector.js: do connect now
,2015-12-03 12:09:25.657 ThaliTest[2443:2288568] jxcore: connect Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:09:25.658 ThaliTest[2443:2288568] client session: connect
2015-12-03 12:09:25.659 ThaliTest[2443:2288568] client session: stateChange:0->1 Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:09:25.916 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 12:09:28.631 ThaliTest[2443:2289375] client session: connected
2015-12-03 12:09:28.632 ThaliTest[2443:2289375] client session: stateChange:1->2 Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:09:28.639 ThaliTest[2443:2289299] client session: fireConnectCallback: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:09:28.639 ThaliTest[2443:2289299] jxcore: connect: success
2015-12-03T11:09:28.641Z SendDataConnector.js: CLIENT connected to 50165, error: null
,2015-12-03T11:09:28.641Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:09:28.645 ThaliTest[2443:2288455] client: relay established
2015-12-03 12:09:28.646 ThaliTest[2443:2288455] client: new accepted socket: 0x1a223680
,2015-12-03T11:09:28.657Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 12:09:33.755 ThaliTest[2443:2289299] server session: not connected Apple-Iphone5-1_PT2098
,2015-12-03 12:09:34.279 ThaliTest[2443:2289375] server session: not connected Apple-Iphone6-1_PT8234
,2015-12-03T11:09:38.713Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T11:09:38.714Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:09:38.714Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:09:38.715Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:09:38.716Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 12:09:38.718 ThaliTest[2443:2288455] client: socket closed
2015-12-03 12:09:38.718 ThaliTest[2443:2288455] client relay: socket disconnected
2015-12-03 12:09:38.719 ThaliTest[2443:2288455] client relay: 0x1a223680 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1a3e5c50 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 12:09:38.720 ThaliTest[2443:2288455] client session: socket closed: Apple-IpadAir2-1_PT7777.O0xng,Q==
2015-12-03 12:09:38.720 ThaliTest[2443:2288455] client session: onLinkFailure: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:09:38.720 ThaliTest[2443:2288455] client session: disconnect
2015-12-03 12:09:38.721 ThaliTest[2443:2288455] client session,: stateChange:2->0 Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:09:38.724 ThaliTest[2443:2288455] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03T11:09:43.717Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03T11:09:43.718Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:09:43.760 ThaliTest[2443:2288455] multipeer session: reset timer
2015-12-03 12:09:43.761 ThaliTest[2443:2288455] multipeer session: stop timer
2015-12-03 12:09:43.762 ThaliTest[2443:2288455] multipeer session: start timer: 0x165b5fa0
2015-,12-03 12:09:43.762 ThaliTest[2443:2288455] server: disconnecting to refresh session (Apple-Iphone5-1_PT2098)
2015-12-03 12:09:43.763 ThaliTest[2443:2288455] server session: disconnect
2015-12-03 12:09:43.763 ThaliTest[2443:2288455] server session: stateC,hange:2->0 Apple-Iphone5-1_PT2098
2015-12-03 12:09:43.768 ThaliTest[2443:2288455] server session: connect
2015-12-03 12:09:43.769 ThaliTest[2443:2288455] server session: stateChange:0->1 Apple-Iphone5-1_PT2098
2015-12-03T11:09:43.772Z SendDataTCPServer.,js: TCP/IP server is ended
,2015-12-03 12:09:43.793 ThaliTest[2443:2288455] server: accepting invitation Apple-Iphone5-1_PT2098
,2015-12-03 12:09:44.261 ThaliTest[2443:2288455] multipeer session: reset timer
2015-12-03 12:09:44.261 ThaliTest[2443:2288455] multipeer session: stop timer
2015-12-03 12:09:44.262 ThaliTest[2443:2288455] multipeer session: start timer: 0x165b5fa0
2015-,12-03 12:09:44.263 ThaliTest[2443:2288455] server: disconnecting to refresh session (Apple-Iphone6-1_PT8234)
2015-12-03 12:09:44.263 ThaliTest[2443:2288455] server session: disconnect
2015-12-03 12:09:44.264 ThaliTest[2443:2288455] server session: stateC,hange:2->0 Apple-Iphone6-1_PT8234
2015-12-03 12:09:44.268 ThaliTest[2443:2288455] server session: connect
2015-12-03 12:09:44.268 ThaliTest[2443:2288455] server session: stateChange:0->1 Apple-Iphone6-1_PT8234
,2015-12-03T11:09:44.281Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 12:09:44.288 ThaliTest[2443:2288455] server: accepting invitation Apple-Iphone6-1_PT8234
,2015-12-03 12:09:45.425 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:09:46.349 ThaliTest[2443:2289375] server session: connected
2015-12-03 12:09:46.350 ThaliTest[2443:2289375] server session: stateChange:1->2 Apple-Iphone5-1_PT2098
,2015-12-03 12:09:46.365 ThaliTest[2443:2288455] server relay: connected (to port: 50116)
,2015-12-03T11:09:46.376Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03 12:09:46.461 ThaliTest[2443:2289299] server session: connected
,2015-12-03 12:09:46.463 ThaliTest[2443:2289299] server session: stateChange:1->2 Apple-Iphone6-1_PT8234
,2015-12-03 12:09:46.470 ThaliTest[2443:2288455] server relay: connected (to port: 50116)
,2015-12-03T11:09:46.480Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:09:46.520Z SendDataTCPServer.js: TCP/IP server has received 1984 bytes of data
,2015-12-03T11:09:46.535Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T11:09:46.562Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-03T11:09:46.576Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 12:09:48.565 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:09:48.724 ThaliTest[2443:2288568] jxcore: disconnect
2015-12-03 12:09:48.725 ThaliTest[2443:2288568] jxcore: disconnect: fail
2015-12-03T11:09:48.726Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7777.O0xn,gQ==
2015-12-03T11:09:48.726Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT7777.O0xngQ== with availability status: true
,2015-12-03T11:09:48.727Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03T11:09:48.727Z SendDataConnector.js: do connect now
,2015-12-03 12:09:48.728 ThaliTest[2443:2288568] jxcore: connect Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:09:48.729 ThaliTest[2443:2288568] client session: connect
,2015-12-03 12:09:48.730 ThaliTest[2443:2288568] client session: stateChange:0->1 Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:09:51.783 ThaliTest[2443:2289375] client session: connected
2015-12-03 12:09:51.783 ThaliTest[2443:2289375] client session: stateChange:1->2 Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:09:51.808 ThaliTest[2443:2289299] client session: fireConnectCallback: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:09:51.808 ThaliTest[2443:2289299] jxcore: connect: success
2015-12-03T11:09:51.810Z SendDataConnector.js: CLIENT connected, to 50170, error: null
2015-12-03T11:09:51.810Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:09:51.813 ThaliTest[2443:2288455] client: relay established
,2015-12-03 12:09:51.814 ThaliTest[2443:2288455] client: new accepted socket: 0x1a3ef4b0
,2015-12-03T11:09:51.826Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 12:09:56.462 ThaliTest[2443:2289354] server session: not connected Apple-Iphone5-1_PT2098
,2015-12-03 12:09:56.836 ThaliTest[2443:2289354] server session: not connected Apple-Iphone6-1_PT8234
,2015-12-03T11:10:01.895Z SendDataConnector.js: Receiving data timeout now
2015-12-03T11:10:01.895Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:10:01.896Z SendDataConnector.js: CLIENT closeClientSocket
,oneRoundDownNow
,oneRoundDownNow:2
,2015-12-03T11:10:01.898Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T11:10:01.898Z SendDataConnector.js: Stop data retrieving timer
,2015-12-03T11:10:01.900Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 12:10:01.901 ThaliTest[2443:2288568] jxcore: disconnect
2015-12-03 12:10:01.901 ThaliTest[2443:2288568] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:10:01.902 ThaliTest[2443:2288568] client session: discon,nect
2015-12-03 12:10:01.903 ThaliTest[2443:2288568] client session: stateChange:2->0 Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:10:01.906 ThaliTest[2443:2288568] jxcore: disconnect: success
2015-12-03T11:10:01.907Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7777.O0xngQ==
---- round done--------
weAreDoneNow, resultArray.length: 4
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
  startTime: Thu Dec 03 2015 12:10:,01 GMT+0100 (CET),
  endTime: Thu Dec 03 2015 12:10:01 GMT+0100 (CET),
  endReason: '',
  dataTimerId: null,
  disconnecting: true }
,done, now sending data to server
CoordinatorConnector-debug: sendData
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT7153","time":356448,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT8234.n7uNOA==","time":42343,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple,-Iphone5s-1_PT7153.3coM6g==","time":205176,"result":"Peer disconnected","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone6-1_PT8234.+Hw2qA==","time":3207,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100,000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT7777.O0xngQ==","time":105610,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000}]}
,sendList : 100% : 3207 ms, 99% : 3207 ms, 95 : 3207 ms, 90% : 3207 ms.
Result count 1, range 3207 ms to  3207 ms.
,sendList failed peers count : 3 [75 %]
,- Peer ID : Apple-Iphone6-1_PT8234.n7uNOA==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT7153.3coM6g==, Tried : 5
,- Peer ID : Apple-IpadAir2-1_PT7777.O0xngQ==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-12-03T11:10:01.945Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T11:10:01.945Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:10:01.946Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 12:10:14.264 ThaliTest[2443:2288455] multipeer session: restart
,2015-12-03 12:10:14.290 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:10:14.293 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:10:14.294 ThaliTest[2443:2288455] client,: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:10:14.295 ThaliTest[2443:2288455] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:10:44.264 ThaliTest[2443:2288455] multipeer session: restart
,2015-12-03 12:10:44.287 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:10:44.288 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:10:44.294 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:10:44.297 ThaliTest[2443:2288455] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:11:14.264 ThaliTest[2443:2288455] multipeer session: restart
,2015-12-03 12:11:14.290 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:11:14.291 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:11:14.292 ThaliTest[2443:2288455] clien,t: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,2015-12-03 12:11:14.294 ThaliTest[2443:2288455] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,CoordinatorConnector-debug: disconnect:transport close
,2015-12-03 12:11:44.264 ThaliTest[2443:2288455] multipeer session: restart
,2015-12-03 12:11:44.292 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:11:44.293 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:11:44.296 ThaliTest[2443:2288455] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:11:44.298 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
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
,2015-12-03 12:12:14.263 ThaliTest[2443:2288455] multipeer session: restart
,2015-12-03 12:12:14.286 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:12:14.288 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:12:14.290 ThaliTest[2443:2288455] clien,t: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:12:14.749 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:12:34.068 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:12:36.165 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:12:44.262 ThaliTest[2443:2288455] multipeer session: restart
,2015-12-03 12:12:44.283 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:12:44.284 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:12:44.286 ThaliTest[2443:2288455] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:12:44.694 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
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
,2015-12-03 12:13:14.263 ThaliTest[2443:2288455] multipeer session: restart
,2015-12-03 12:13:14.287 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:13:14.288 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:13:14.290 ThaliTest[2443:2288455] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:13:14.577 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
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
,2015-12-03 12:13:37.492 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:13:44.263 ThaliTest[2443:2288455] multipeer session: restart
,2015-12-03 12:13:44.285 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:13:44.287 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:13:44.288 ThaliTest[2443:2288455] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:13:44.447 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:14:04.223 ThaliTest[2443:2288455] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:14:04.224 ThaliTest[2443:2288455] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
2015-12-03 12:14:04.227 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","pe,erName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:14:14.263 ThaliTest[2443:2288455] multipeer session: restart
,2015-12-03 12:14:14.287 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:14:14.288 ThaliTest[2443:2288455] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:14:14.289 ThaliTest[2443:2288455] clien,t: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:14:14.848 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:14:36.199 ThaliTest[2443:2288455] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:14:44.263 ThaliTest[2443:2288455] multipeer session: restart
2015-12-03 12:14:44.270 ThaliTest[2443:2288455] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Fi,rst throw call stack:
(0x2a8a745f 0x3876ac8b 0x2a7c4c53 0x2c829d95 0x2a3c4297 0x2a3c3b11 0x2a33d693 0x2a86dfbf 0x2a86d3cf 0x2a86ba35 0x2a7b93b1 0x2a7b91c3 0x31da6201 0x2de2343d 0xeb5e3 0x38cf6aaf)
libc++abi.dylib: terminating with uncaught exception of t,ype NSException
,Process 2443 stopped
* thread #1: tid = 0x22eb47, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x38dc0df0 <+8>:  blo    0x38dc0e08                ; <+32>
    0x38dc0df4 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x38dc0df8 <+16>: ldr    r12, [pc, r12]
    0x38dc0dfc <+20>: b      0x38dc0e04                ; <+28>
,* thread #1: tid = 0x22eb47, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
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
    frame #13: 0x000eb5e2 ThaliTest`main + 50

```
