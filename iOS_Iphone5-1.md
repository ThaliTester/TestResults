#### Test 5065027835b6ad9_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027835b6ad9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/68E2AF1B-7A4F-4824-8006-9991859FC772/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/68E2AF1B-7A4F-4824-8006-9991859FC772/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027835b6ad9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027835b6ad9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/D87DCE4E-9353-40E4-9B88-5F331912B26A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60258"
,(lldb)     command script import "/tmp/68E2AF1B-7A4F-4824-8006-9991859FC772/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 12:03:47.305 ThaliTest[1196:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 12:03:47.309 ThaliTest[1196:60b] Multi-tasking -> Device: YES, App: YES
,2015-12-03 12:03:47.315 ThaliTest[1196:60b] Unlimited access to network resources
,2015-12-03 12:03:47.324 ThaliTest[1196:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.app,le.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 12:03:58.125 ThaliTest[1196:60b] Resetting plugins due to page load.
,2015-12-03 12:03:58.991 ThaliTest[1196:60b] Finished load of: file:///var/mobile/Applications/D87DCE4E-9353-40E4-9B88-5F331912B26A/ThaliTest.app/www/index.html
,2015-12-03 12:03:59.168 ThaliTest[1196:60b] JXcore Cordova plugin initializing
,2015-12-03 12:03:59.171 ThaliTest[1196:6907] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
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
serverPort is 8876
,2015-12-03 12:04:02.557 ThaliTest[1196:6907] jxcore: startBroadcasting
,2015-12-03 12:04:02.565 ThaliTest[1196:6907] server: starting Apple-Iphone5-1_PT2098.2PCWSw==
,2015-12-03 12:04:02.566 ThaliTest[1196:6907] multipeer session: start timer: 0x1c342390
,2015-12-03 12:04:02.568 ThaliTest[1196:6907] THEMultipeerSession initialized peer Apple-Iphone5-1_PT2098
,2015-12-03 12:04:02.570 ThaliTest[1196:6907] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-03 12:04:03.779 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.VxBn0g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7777.VxBn0g==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-IpadAir2-1_PT7777.VxBn0g==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,CoordinatorConnector-debug: sendData
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT2098","time":1226,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-IpadAir2-1_PT7777.VxBn0g==","peerAvailable":true,"time":1225}]}
,peersList : 100% : 1225 ms, 99% : 1225 ms, 95 : 1225 ms, 90% : 1225 ms.
Result count 1, range 1225 ms to  1225 ms.
,2015-12-03 12:04:04.214 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:04:05.986 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.n7uNOA==
,CoordinatorConnector-debug: stop:undefined
,stop tests now !
stop current!
,testFindPeers stopped
2015-12-03 12:04:06.749 ThaliTest[1196:6907] jxcore: stopBroadcasting
,2015-12-03 12:04:06.749 ThaliTest[1196:6907] THEMultipeerSession stopping peer
,2015-12-03 12:04:06.750 ThaliTest[1196:6907] multipeer session: stop timer
,2015-12-03 12:04:06.751 ThaliTest[1196:6907] jxcore: stopBroadcasting: success
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
,serverPort is 62554
,2015-12-03 12:04:06.805 ThaliTest[1196:6907] jxcore: startBroadcasting
,2015-12-03 12:04:06.809 ThaliTest[1196:6907] server: starting Apple-Iphone5-1_PT2098.P4cq9w==
,2015-12-03 12:04:06.810 ThaliTest[1196:6907] multipeer session: start timer: 0x1c34ba70
2015-12-03 12:04:06.812 ThaliTest[1196:6907] THEMultipeerSession initialized peer Apple-Iphone5-1_PT2098
2015-12-03 12:04:06.813 ThaliTest[1196:6907] jxcore: startBro,adcasting: success
StartBroadcasting started ok
,2015-12-03T11:04:06.815Z SendDataTCPServer.js: TCP/IP server is bound to port: 62554
,2015-12-03 12:04:06.823 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:06.824 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1,_PT7777.VxBn0g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
2015-12-03 12:04:06.825 ThaliTest[1196:60b] client: found peer: Apple-Iphone5-1_PT2098.2PCWSw==
2015-12-03 12:04:06.826 ThaliTest[1196:60b] client: found p,eer: Apple-Iphone6-1_PT8234.n7uNOA==
device[1]: Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03T11:04:06.827Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03T11:04:06.828Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03T11:04:06.828Z SendDataConnector.js: do connect now
2015-12-03 12:04:06.829 ThaliTest[1196:6907] jxcore: connect Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:06.830 ThaliTest[1196:6907] client session: connect
,2015-12-03 12:04:06.833 ThaliTest[1196:6907] client session: stateChange:0->1 Apple-IpadAir2-1_PT7777.VxBn0g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.3coM6g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2098.2PCWSw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.n7uNOA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-03 12:04:07.862 ThaliTest[1196:60b] client: lost peer: Apple-Iphone5-1_PT2098.2PCWSw==
2015-12-03 12:04:07.862 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone5-1_PT2098.2PCWSw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2098.2PCWSw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 12:04:07.923 ThaliTest[1196:60b] client: lost peer: Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:07.924 ThaliTest[1196:60b] client session: onPeerLost: Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:07.925 ThaliTest[1196:60b] client session: onLinkFailure: Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:07.925 ThaliTest[1196:60b] client session: disconnect
2015-12-03 12:04:07.926 ThaliTest[1196:60b] client session: stateChange:1->0 Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:07.927 ThaliTest[1196:60b] client session: fireConnectCallback: Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:07.927 ThaliTest[1196:60b] jxcore: connect: fail: Peer disconnected
,2015-12-03T11:04:07.928Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-12-03T11:04:07.929Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-03T11:04:07.929Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7777.VxBn0g==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:04:07.992 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:04:07.994 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 12:04:08.002 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7777.O0xngQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 12:04:09.597 ThaliTest[1196:60b] client: lost peer: Apple-Iphone6-1_PT8234.n7uNOA==
,2015-12-03 12:04:09.598 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone6-1_PT8234.n7uNOA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.n7uNOA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 12:04:11.592 ThaliTest[1196:60b] client: lost peer: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:04:11.594 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone5s-1_PT7153.3coM6g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.3coM6g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03T11:04:12.936Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03T11:04:12.937Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:17.413 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.3coM6g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 12:04:17.948 ThaliTest[1196:6907] jxcore: disconnect
,2015-12-03 12:04:17.949 ThaliTest[1196:6907] jxcore: disconnect: fail
2015-12-03T11:04:17.951Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03T11:04:17.951Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT7777.VxBn0g== with availability status: true
,2015-12-03T11:04:17.952Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03T11:04:17.952Z SendDataConnector.js: do connect now
,2015-12-03 12:04:17.952 ThaliTest[1196:6907] jxcore: connect Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:17.953 ThaliTest[1196:6907] client: connect: unreachable Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:17.954 ThaliTest[1196:6907] jxcore: connect: fail: Peer unreachable
2015-12-03T11:04:17.954Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-03T11:04:17.955Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-03T11:04:17.955Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:04:22.961Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03T11:04:22.962Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:27.970 ThaliTest[1196:6907] jxcore: disconnect
,2015-12-03 12:04:27.972 ThaliTest[1196:6907] jxcore: disconnect: fail
2015-12-03T11:04:27.973Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03T11:04:27.974Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT7777.VxBn0g== with availability status: true
,2015-12-03T11:04:27.974Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03T11:04:27.974Z SendDataConnector.js: do connect now
,2015-12-03 12:04:27.975 ThaliTest[1196:6907] jxcore: connect Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:27.976 ThaliTest[1196:6907] client: connect: unreachable Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:27.976 ThaliTest[1196:6907] jxcore: connect: fail: Peer unreachable
2015-12-03T11:04:27.977Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-03T11:04:27.977Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-03T11:04:27.977Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:04:32.985Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03T11:04:32.986Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:36.813 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:04:37.996 ThaliTest[1196:6907] jxcore: disconnect
,2015-12-03 12:04:37.997 ThaliTest[1196:6907] jxcore: disconnect: fail
,2015-12-03T11:04:37.999Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03T11:04:37.999Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT7777.VxBn0g== with availability status: true
2015-12-03T11:04:38.000Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03T11:04:38.000Z SendDataConnector.js: do connect now
,2015-12-03 12:04:38.000 ThaliTest[1196:6907] jxcore: connect Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:38.001 ThaliTest[1196:6907] client: connect: unreachable Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:38.002 ThaliTest[1196:6907] jxcore: connect: fail: Peer unreachable
2015-12-03T11:04:38.002Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-03T11:04:38.003Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-03T11:04:38.003Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:04:43.011Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03T11:04:43.011Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:48.023 ThaliTest[1196:6907] jxcore: disconnect
,2015-12-03 12:04:48.024 ThaliTest[1196:6907] jxcore: disconnect: fail
2015-12-03T11:04:48.026Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03T11:04:48.027Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT7777.VxBn0g== with availability status: true
2015-12-03T11:04:48.027Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
2015,-12-03T11:04:48.027Z SendDataConnector.js: do connect now
,2015-12-03 12:04:48.027 ThaliTest[1196:6907] jxcore: connect Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:48.028 ThaliTest[1196:6907] client: connect: unreachable Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:48.029 ThaliTest[1196:6907] jxcore: connect: fail: Peer unreachable
,2015-12-03T11:04:48.029Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-03T11:04:48.030Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
oneRoundDownNow:2
,2015-12-03T11:04:48.031Z SendDataConnector.js: CLIENT Stop now
,2015-12-03 12:04:48.031 ThaliTest[1196:6907] jxcore: disconnect
,2015-12-03 12:04:48.032 ThaliTest[1196:6907] jxcore: disconnect: fail
2015-12-03T11:04:48.032Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,---- round done--------
,device[2]: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03T11:04:48.034Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03T11:04:48.034Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03T11:04:48.034Z SendDataConnector.js: do connect now
,2015-12-03 12:04:48.034 ThaliTest[1196:6907] jxcore: connect Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:04:48.035 ThaliTest[1196:6907] client session: connect
,2015-12-03 12:04:48.035 ThaliTest[1196:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:04:49.055 ThaliTest[1196:60b] multipeer session: reset timer
2015-12-03 12:04:49.056 ThaliTest[1196:60b] multipeer session: stop timer
,2015-12-03 12:04:49.058 ThaliTest[1196:60b] multipeer session: start timer: 0x1c34ba70
,2015-12-03 12:04:49.058 ThaliTest[1196:60b] server session: connect
,2015-12-03 12:04:49.059 ThaliTest[1196:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT7777
,2015-12-03 12:04:49.062 ThaliTest[1196:60b] server: accepting invitation Apple-IpadAir2-1_PT7777
,2015-12-03 12:04:51.491 ThaliTest[1196:6307] server session: connected
,2015-12-03 12:04:51.492 ThaliTest[1196:6307] server session: stateChange:1->2 Apple-IpadAir2-1_PT7777
,2015-12-03 12:04:51.546 ThaliTest[1196:60b] server relay: connected (to port: 62554)
,2015-12-03T11:04:51.553Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:04:51.756Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-03T11:04:51.770Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-03T11:04:51.784Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 12:04:51.842 ThaliTest[1196:8a0b] server session: not connected Apple-IpadAir2-1_PT7777
,2015-12-03 12:05:19.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:05:19.070 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:05:19.072 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:05:19.073 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:05:19.074 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:05:21.030 ThaliTest[1196:8a0f] client session: not connected Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:05:21.031 ThaliTest[1196:8a0f] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:05:21.032 ThaliTest[1196:8a0f] client session: disconnect
,2015-12-03 12:05:21.033 ThaliTest[1196:8a0f] client session: stateChange:1->0 Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:05:21.034 ThaliTest[1196:8a0f] client session: fireConnectCallback: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:05:21.035 ThaliTest[1196:8a0f] jxcore: connect: fail: Peer disconnected
,2015-12-03T11:05:21.036Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T11:05:21.036Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-03T11:05:21.036Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:05:26.036Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03T11:05:26.037Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:05:31.041 ThaliTest[1196:6907] jxcore: disconnect
,2015-12-03 12:05:31.042 ThaliTest[1196:6907] jxcore: disconnect: fail
2015-12-03T11:05:31.043Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03T11:05:31.044Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT7153.3coM6g== with availability status: true
,2015-12-03T11:05:31.044Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03T11:05:31.044Z SendDataConnector.js: do connect now
,2015-12-03 12:05:31.045 ThaliTest[1196:6907] jxcore: connect Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:05:31.046 ThaliTest[1196:6907] client session: connect
,2015-12-03 12:05:31.046 ThaliTest[1196:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:05:32.838 ThaliTest[1196:60b] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:05:32.839 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 12:05:32.920 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 12:05:49.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:06:04.026 ThaliTest[1196:8c17] client session: not connected Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:04.027 ThaliTest[1196:8c17] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:06:04.029 ThaliTest[1196:8c17] client session: disconnect
,2015-12-03 12:06:04.030 ThaliTest[1196:8c17] client session: stateChange:1->0 Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:04.030 ThaliTest[1196:8c17] client session: fireConnectCallback: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:04.031 ThaliTest[1196:8c17] jxcore: connect: fail: Peer disconnected
,2015-12-03T11:06:04.032Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T11:06:04.033Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-03T11:06:04.033Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:06:09.039Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03T11:06:09.039Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:14.048 ThaliTest[1196:6907] jxcore: disconnect
2015-12-03 12:06:14.050 ThaliTest[1196:6907] jxcore: disconnect: fail
2015-12-03T11:06:14.051Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03T11:06:14.052Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT7153.3coM6g== with availability status: true
2015-12-03T11:06:14.052Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03T11:06:14.052Z SendDataConnector.js: do connect now
,2015-12-03 12:06:14.052 ThaliTest[1196:6907] jxcore: connect Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:06:14.053 ThaliTest[1196:6907] client session: connect
,2015-12-03 12:06:14.054 ThaliTest[1196:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:19.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:06:19.070 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:06:19.072 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:06:19.073 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:19.074 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:06:32.641 ThaliTest[1196:60b] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:06:32.643 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 12:06:32.646 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-03 12:06:35.316 ThaliTest[1196:60b] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:06:35.317 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 12:06:35.789 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 12:06:47.053 ThaliTest[1196:8523] client session: not connected Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:06:47.054 ThaliTest[1196:8523] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:47.055 ThaliTest[1196:8523] client session: disconnect
2015-12-03 12:06:47.057 ThaliTest[1196:8523] client session: stateChange:1->0 Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:47.057 ThaliTest[1196:8523] client session: fireConnectCallback: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:47.058 ThaliTest[1196:8523] jxcore: connect: fail: Peer disconnected
,2015-12-03T11:06:47.059Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T11:06:47.059Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-03T11:06:47.060Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03 12:06:49.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:06:49.074 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:06:49.075 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:06:49.077 ThaliTest[1196:60b] client: found pe,er: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:49.079 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03T11:06:52.064Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03T11:06:52.065Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:57.076 ThaliTest[1196:6907] jxcore: disconnect
,2015-12-03 12:06:57.078 ThaliTest[1196:6907] jxcore: disconnect: fail
2015-12-03T11:06:57.079Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03T11:06:57.080Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT7153.3coM6g== with availability status: true
,2015-12-03T11:06:57.080Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03T11:06:57.080Z SendDataConnector.js: do connect now
,2015-12-03 12:06:57.080 ThaliTest[1196:6907] jxcore: connect Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:57.082 ThaliTest[1196:6907] client session: connect
,2015-12-03 12:06:57.082 ThaliTest[1196:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:07:19.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:07:19.070 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:07:19.072 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:07:19.365 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:07:19.368 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:07:30.080 ThaliTest[1196:8527] client session: not connected Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:07:30.082 ThaliTest[1196:8527] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:07:30.083 ThaliTest[1196:8527] client session: disconnect
2015-12-03 12:07:30.084 ThaliTest[1196:8527] client session: stateChange:1->0 Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:07:30.085 ThaliTest[1196:8527] client session: fireConnectCallback: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:07:30.085 ThaliTest[1196:8527] jxcore: connect: fail: Peer disconnected
,2015-12-03T11:07:30.088Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-12-03T11:07:30.088Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-03T11:07:30.088Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:07:35.094Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03T11:07:35.095Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:07:40.103 ThaliTest[1196:6907] jxcore: disconnect
,2015-12-03 12:07:40.104 ThaliTest[1196:6907] jxcore: disconnect: fail
2015-12-03T11:07:40.106Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03T11:07:40.106Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT7153.3coM6g== with availability status: true
,2015-12-03T11:07:40.106Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03T11:07:40.107Z SendDataConnector.js: do connect now
,2015-12-03 12:07:40.107 ThaliTest[1196:6907] jxcore: connect Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:07:40.108 ThaliTest[1196:6907] client session: connect
,2015-12-03 12:07:40.109 ThaliTest[1196:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:07:49.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:07:49.071 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:07:49.072 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:07:49.073 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:07:49.074 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:08:02.752 ThaliTest[1196:60b] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:08:02.753 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 12:08:02.802 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 12:08:09.142 ThaliTest[1196:60b] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:08:09.143 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 12:08:13.085 ThaliTest[1196:872b] client session: not connected Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:08:13.086 ThaliTest[1196:872b] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:08:13.088 ThaliTest[1196:872b] client session: disconnect
,2015-12-03 12:08:13.089 ThaliTest[1196:872b] client session: stateChange:1->0 Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:08:13.090 ThaliTest[1196:872b] client session: fireConnectCallback: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:08:13.090 ThaliTest[1196:872b] jxcore: connect: fail: Peer disconnected
2015-12-03T11:08:13.091Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T11:08:13.091Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,oneRoundDownNow
,oneRoundDownNow:2
,2015-12-03T11:08:13.093Z SendDataConnector.js: CLIENT Stop now
,2015-12-03 12:08:13.094 ThaliTest[1196:6907] jxcore: disconnect
,2015-12-03 12:08:13.094 ThaliTest[1196:6907] jxcore: disconnect: fail
2015-12-03T11:08:13.095Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.3coM6g==
,---- round done--------
device[3]: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:08:13.096Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03T11:08:13.096Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:08:13.096Z SendDataConnector.js: do connect now
,2015-12-03 12:08:13.096 ThaliTest[1196:6907] jxcore: connect Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:08:13.097 ThaliTest[1196:6907] client session: connect
,2015-12-03 12:08:13.098 ThaliTest[1196:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:08:13.428 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 12:08:15.919 ThaliTest[1196:632b] client session: connected
,2015-12-03 12:08:15.921 ThaliTest[1196:632b] client session: stateChange:1->2 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:08:15.932 ThaliTest[1196:882f] client session: fireConnectCallback: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:08:15.933 ThaliTest[1196:882f] jxcore: connect: success
,2015-12-03T11:08:15.934Z SendDataConnector.js: CLIENT connected to 62581, error: null
,2015-12-03T11:08:15.935Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:08:15.936 ThaliTest[1196:60b] client: relay established
,2015-12-03 12:08:15.937 ThaliTest[1196:60b] client: new accepted socket: 0x1c2d5650
,2015-12-03T11:08:15.950Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T11:08:16.484Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-03T11:08:16.497Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-03T11:08:16.510Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-03T11:08:16.533Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-03T11:08:16.556Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03 12:08:19.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:08:19.070 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:08:19.072 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:08:19.073 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:08:19.074 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03T11:08:26.562Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T11:08:26.563Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:08:26.565Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T11:08:26.565Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:08:26.566Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 12:08:26.567 ThaliTest[1196:60b] client: socket closed
,2015-12-03 12:08:26.568 ThaliTest[1196:60b] client relay: socket disconnected
,2015-12-03 12:08:26.568 ThaliTest[1196:60b] client relay: 0x1c2d5650 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1c2d7f80 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 12:08:26.569 ThaliTest[1196:60b] client session: socket closed: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:08:26.570 ThaliTest[1196:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:08:26.570 ThaliTest[1196:60b] client session: disconnect
,2015-12-03 12:08:26.571 ThaliTest[1196:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:08:26.572 ThaliTest[1196:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:08:31.565Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:08:31.566Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:08:36.575 ThaliTest[1196:6907] jxcore: disconnect
2015-12-03 12:08:36.577 ThaliTest[1196:6907] jxcore: disconnect: fail
,2015-12-03T11:08:36.578Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03T11:08:36.579Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT7153.jAFxCw== with availability status,: true
2015-12-03T11:08:36.579Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03T11:08:36.579Z SendDataConnector.js: do connect now
,2015-12-03 12:08:36.579 ThaliTest[1196:6907] jxcore: connect Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:08:36.580 ThaliTest[1196:6907] client session: connect
,2015-12-03 12:08:36.581 ThaliTest[1196:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:08:39.505 ThaliTest[1196:8f27] client session: connected
,2015-12-03 12:08:39.506 ThaliTest[1196:8f27] client session: stateChange:1->2 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:08:39.529 ThaliTest[1196:8f27] client session: fireConnectCallback: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:08:39.530 ThaliTest[1196:8f27] jxcore: connect: success
,2015-12-03T11:08:39.531Z SendDataConnector.js: CLIENT connected to 62591, error: null
2015-12-03T11:08:39.532Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:08:39.533 ThaliTest[1196:60b] client: relay established
2015-12-03 12:08:39.534 ThaliTest[1196:60b] client: new accepted socket: 0x1c3a0b10
,2015-12-03T11:08:39.545Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 12:08:49.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03T11:08:49.605Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T11:08:49.606Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T11:08:49.606Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:08:49.607Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:08:49.607Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 12:08:49.609 ThaliTest[1196:60b] client: socket closed
,2015-12-03 12:08:49.610 ThaliTest[1196:60b] client relay: socket disconnected
,2015-12-03 12:08:49.610 ThaliTest[1196:60b] client relay: 0x1c3a0b10 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1c3a2c40 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 12:08:49.611 ThaliTest[1196:60b] client session: socket closed: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:08:49.612 ThaliTest[1196:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:08:49.612 ThaliTest[1196:60b] client session: disconnect
,2015-12-03 12:08:49.613 ThaliTest[1196:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:08:49.614 ThaliTest[1196:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:08:54.608Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:08:54.609Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:08:59.611 ThaliTest[1196:6907] jxcore: disconnect
2015-12-03 12:08:59.612 ThaliTest[1196:6907] jxcore: disconnect: fail
,2015-12-03T11:08:59.614Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03T11:08:59.614Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT7153.jAFxCw== with availability status,: true
2015-12-03T11:08:59.615Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03T11:08:59.615Z SendDataConnector.js: do connect now
,2015-12-03 12:08:59.615 ThaliTest[1196:6907] jxcore: connect Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:08:59.616 ThaliTest[1196:6907] client session: connect
,2015-12-03 12:08:59.616 ThaliTest[1196:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:02.204 ThaliTest[1196:a01b] client session: connected
,2015-12-03 12:09:02.205 ThaliTest[1196:a01b] client session: stateChange:1->2 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:02.215 ThaliTest[1196:a01b] client session: fireConnectCallback: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:02.216 ThaliTest[1196:a01b] jxcore: connect: success
2015-12-03T11:09:02.217Z SendDataConnector.js: CLIENT connected to 62601, error: null
,2015-12-03T11:09:02.217Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:09:02.220 ThaliTest[1196:60b] client: relay established
,2015-12-03 12:09:02.220 ThaliTest[1196:60b] client: new accepted socket: 0x1c3a8000
,2015-12-03T11:09:02.231Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T11:09:12.283Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T11:09:12.283Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:09:12.284Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:09:12.285Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-12-03T11:09:12.286Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 12:09:12.287 ThaliTest[1196:60b] client: socket closed
,2015-12-03 12:09:12.288 ThaliTest[1196:60b] client relay: socket disconnected
,2015-12-03 12:09:12.288 ThaliTest[1196:60b] client relay: 0x1c3a8000 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1c2e11e0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 12:09:12.289 ThaliTest[1196:60b] client session: socket closed: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:09:12.290 ThaliTest[1196:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:12.291 ThaliTest[1196:60b] client session: disconnect
,2015-12-03 12:09:12.291 ThaliTest[1196:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:12.293 ThaliTest[1196:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:09:17.293Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:09:17.294Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:19.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:09:19.810 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:09:19.811 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:09:19.812 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:09:19.813 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:09:22.301 ThaliTest[1196:6907] jxcore: disconnect
,2015-12-03 12:09:22.302 ThaliTest[1196:6907] jxcore: disconnect: fail
2015-12-03T11:09:22.304Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:09:22.305Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT7153.jAFxCw== with availability status: true
2015-12-03T11:09:22.305Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03T11:09:22.305Z SendDataConnector.js: do connect now
,2015-12-03 12:09:22.305 ThaliTest[1196:6907] jxcore: connect Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:22.306 ThaliTest[1196:6907] client session: connect
,2015-12-03 12:09:22.307 ThaliTest[1196:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:24.744 ThaliTest[1196:6337] client session: connected
,2015-12-03 12:09:24.746 ThaliTest[1196:6337] client session: stateChange:1->2 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:24.753 ThaliTest[1196:882f] client session: fireConnectCallback: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:24.755 ThaliTest[1196:882f] jxcore: connect: success
2015-12-03T11:09:24.756Z SendDataConnector.js: CLIENT connected to 62612, error: null
,2015-12-03T11:09:24.756Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:09:24.757 ThaliTest[1196:60b] client: relay established
,2015-12-03 12:09:24.758 ThaliTest[1196:60b] client: new accepted socket: 0x1c2e4770
,2015-12-03T11:09:24.770Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T11:09:34.827Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T11:09:34.828Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:09:34.828Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:09:34.829Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:09:34.830Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 12:09:34.831 ThaliTest[1196:60b] client: socket closed
2015-12-03 12:09:34.832 ThaliTest[1196:60b] client relay: socket disconnected
,2015-12-03 12:09:34.832 ThaliTest[1196:60b] client relay: 0x1c2e4770 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1c2e6900 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 12:09:34.833 ThaliTest[1196:60b] client session: socket closed: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:34.834 ThaliTest[1196:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:34.834 ThaliTest[1196:60b] client session: disconnect
,2015-12-03 12:09:34.835 ThaliTest[1196:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:34.836 ThaliTest[1196:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:09:39.838Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:09:39.839Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:44.845 ThaliTest[1196:6907] jxcore: disconnect
2015-12-03 12:09:44.846 ThaliTest[1196:6907] jxcore: disconnect: fail
2015-12-03T11:09:44.847Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:09:44.848Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT7153.jAFxCw== with availability status: true
2015-12-03T11:09:44.848Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.jAFxCw==
2015,-12-03T11:09:44.848Z SendDataConnector.js: do connect now
,2015-12-03 12:09:44.849 ThaliTest[1196:6907] jxcore: connect Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:09:44.849 ThaliTest[1196:6907] client session: connect
,2015-12-03 12:09:44.850 ThaliTest[1196:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:47.646 ThaliTest[1196:873f] client session: connected
,2015-12-03 12:09:47.648 ThaliTest[1196:873f] client session: stateChange:1->2 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:47.677 ThaliTest[1196:ae33] client session: fireConnectCallback: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:09:47.678 ThaliTest[1196:ae33] jxcore: connect: success
,2015-12-03T11:09:47.679Z SendDataConnector.js: CLIENT connected to 62621, error: null
2015-12-03T11:09:47.679Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:09:47.681 ThaliTest[1196:60b] client: relay established
,2015-12-03 12:09:47.682 ThaliTest[1196:60b] client: new accepted socket: 0x1c3b10f0
,2015-12-03T11:09:47.692Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 12:09:49.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:09:49.822 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:09:49.824 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:09:49.825 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:50.263 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03T11:09:57.750Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T11:09:57.750Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:09:57.751Z SendDataConnector.js: CLIENT closeClientSocket
,oneRoundDownNow
oneRoundDownNow:2
,2015-12-03T11:09:57.753Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T11:09:57.753Z SendDataConnector.js: Stop data retrieving timer
2015-12-03T11:09:57.754Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 12:09:57.754 ThaliTest[1196:6907] jxcore: disconnect
,2015-12-03 12:09:57.755 ThaliTest[1196:6907] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:57.756 ThaliTest[1196:6907] client session: disconnect
,2015-12-03 12:09:57.756 ThaliTest[1196:6907] client session: stateChange:2->0 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:09:57.758 ThaliTest[1196:6907] jxcore: disconnect: success
2015-12-03T11:09:57.761Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.jAFxCw==
,---- round done--------
device[4]: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03T11:09:57.762Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03T11:09:57.762Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03T11:09:57.762Z SendDataConnector.js: do connect now
,2015-12-03 12:09:57.763 ThaliTest[1196:6907] jxcore: connect Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:09:57.764 ThaliTest[1196:6907] client session: connect
,2015-12-03 12:09:57.764 ThaliTest[1196:6907] client session: stateChange:0->1 Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03T11:09:57.768Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 12:10:01.799 ThaliTest[1196:ae33] client session: connected
2015-12-03 12:10:01.800 ThaliTest[1196:ae33] client session: stateChange:1->2 Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:10:01.807 ThaliTest[1196:853f] client session: fireConnectCallback: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:10:01.809 ThaliTest[1196:853f] jxcore: connect: success
,2015-12-03T11:10:01.810Z SendDataConnector.js: CLIENT connected to 62626, error: null
,2015-12-03T11:10:01.811Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:10:01.812 ThaliTest[1196:60b] client: relay established
,2015-12-03 12:10:01.813 ThaliTest[1196:60b] client: new accepted socket: 0x1c2ea0f0
,2015-12-03T11:10:01.824Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T11:10:02.343Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-03T11:10:02.357Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-03T11:10:02.369Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-03T11:10:02.393Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-03T11:10:02.406Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-03T11:10:02.597Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03T11:10:12.601Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T11:10:12.602Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T11:10:12.602Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:10:12.603Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-12-03T11:10:12.603Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 12:10:12.605 ThaliTest[1196:60b] client: socket closed
2015-12-03 12:10:12.606 ThaliTest[1196:60b] client relay: socket disconnected
,2015-12-03 12:10:12.607 ThaliTest[1196:60b] client relay: 0x1c2ea0f0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1c3b3090 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 12:10:12.607 ThaliTest[1196:60b] client session: socket closed: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:10:12.608 ThaliTest[1196:60b] client session: onLinkFailure: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:10:12.608 ThaliTest[1196:60b] client session: disconnect
,2015-12-03 12:10:12.609 ThaliTest[1196:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:10:12.611 ThaliTest[1196:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03T11:10:17.604Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03T11:10:17.604Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:10:19.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:10:19.071 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:10:19.072 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:10:19.073 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:10:19.174 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:10:22.608 ThaliTest[1196:6907] jxcore: disconnect
2015-12-03 12:10:22.609 ThaliTest[1196:6907] jxcore: disconnect: fail
,2015-12-03T11:10:22.611Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03T11:10:22.611Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT8234.+Hw2qA== with availability status: ,true
2015-12-03T11:10:22.612Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03T11:10:22.612Z SendDataConnector.js: do connect now
,2015-12-03 12:10:22.612 ThaliTest[1196:6907] jxcore: connect Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:10:22.613 ThaliTest[1196:6907] client session: connect
,2015-12-03 12:10:22.614 ThaliTest[1196:6907] client session: stateChange:0->1 Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:10:22.900 ThaliTest[1196:60b] client: lost peer: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:10:22.901 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone5s-1_PT7153.3coM6g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.3coM6g==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:10:26.065 ThaliTest[1196:8543] client session: connected
2015-12-03 12:10:26.066 ThaliTest[1196:8543] client session: stateChange:1->2 Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:10:26.073 ThaliTest[1196:8543] client session: fireConnectCallback: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:10:26.074 ThaliTest[1196:8543] jxcore: connect: success
,2015-12-03T11:10:26.076Z SendDataConnector.js: CLIENT connected to 62632, error: null
,2015-12-03T11:10:26.076Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:10:26.078 ThaliTest[1196:60b] client: relay established
2015-12-03 12:10:26.078 ThaliTest[1196:60b] client: new accepted socket: 0x1c2f9260
,2015-12-03T11:10:26.091Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T11:10:36.149Z SendDataConnector.js: Receiving data timeout now
2015-12-03T11:10:36.150Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:10:36.151Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T11:10:36.151Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-12-03T11:10:36.152Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 12:10:36.153 ThaliTest[1196:60b] client: socket closed
2015-12-03 12:10:36.154 ThaliTest[1196:60b] client relay: socket disconnected
2015-12-03 12:10:36.155 ThaliTest[1196:60b] client relay: 0x1c2f9260 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1c3bd710 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 12:10:36.156 ThaliTest[1196:60b] client session: socket closed: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:10:36.156 ThaliTest[1196:60b] client session: onLinkFailure: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:10:36.157 ThaliTest[1196:60b] client session: disconnect
2015-12-03 12:10:36.157 ThaliTest[1196:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:10:36.159 ThaliTest[1196:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03T11:10:41.158Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03T11:10:41.158Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:10:46.169 ThaliTest[1196:6907] jxcore: disconnect
2015-12-03 12:10:46.170 ThaliTest[1196:6907] jxcore: disconnect: fail
2015-12-03T11:10:46.171Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03T11:10:46.172Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT8234.+Hw2qA== with availability status: true
2015-12-03T11:10:46.172Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03T11:10:46.172Z SendDataConnector.js: do connect now
,2015-12-03 12:10:46.173 ThaliTest[1196:6907] jxcore: connect Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:10:46.173 ThaliTest[1196:6907] client session: connect
,2015-12-03 12:10:46.174 ThaliTest[1196:6907] client session: stateChange:0->1 Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:10:49.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:10:49.071 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:10:49.071 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:10:49.073 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:10:49.499 ThaliTest[1196:8f4f] client session: connected
,2015-12-03 12:10:49.500 ThaliTest[1196:8f4f] client session: stateChange:1->2 Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:10:49.509 ThaliTest[1196:8f4f] client session: fireConnectCallback: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:10:49.510 ThaliTest[1196:8f4f] jxcore: connect: success
,2015-12-03T11:10:49.511Z SendDataConnector.js: CLIENT connected to 62637, error: null
2015-12-03T11:10:49.511Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:10:49.513 ThaliTest[1196:60b] client: relay established
,2015-12-03 12:10:49.513 ThaliTest[1196:60b] client: new accepted socket: 0x1c2f62b0
,2015-12-03T11:10:49.526Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T11:10:59.579Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T11:10:59.579Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T11:10:59.580Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:10:59.580Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:10:59.581Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 12:10:59.583 ThaliTest[1196:60b] client: socket closed
2015-12-03 12:10:59.583 ThaliTest[1196:60b] client relay: socket disconnected
2015-12-03 12:10:59.584 ThaliTest[1196:60b] client relay: 0x1c2f62b0 disconnected with error Error Domain=GCDA,syncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1c3c72f0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 12:10:59.585 ThaliTest[1196:60b] client session: socket closed: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:10:59.585 ThaliTest[1196:60b] client session: onLinkFailure: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:10:59.586 ThaliTest[1196:6,0b] client session: disconnect
2015-12-03 12:10:59.587 ThaliTest[1196:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:10:59.588 ThaliTest[1196:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03T11:11:04.581Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03T11:11:04.581Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:11:09.584 ThaliTest[1196:6907] jxcore: disconnect
,2015-12-03 12:11:09.586 ThaliTest[1196:6907] jxcore: disconnect: fail
2015-12-03T11:11:09.587Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03T11:11:09.588Z SendDataConnector.js: Connect (retry coun,t 3) to peer Apple-Iphone6-1_PT8234.+Hw2qA== with availability status: true
2015-12-03T11:11:09.588Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03T11:11:09.589Z SendDataConnector.js: do connect now
,2015-12-03 12:11:09.589 ThaliTest[1196:6907] jxcore: connect Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:11:09.590 ThaliTest[1196:6907] client session: connect
,2015-12-03 12:11:09.590 ThaliTest[1196:6907] client session: stateChange:0->1 Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:11:12.238 ThaliTest[1196:8753] client session: connected
,2015-12-03 12:11:12.239 ThaliTest[1196:8753] client session: stateChange:1->2 Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:11:12.247 ThaliTest[1196:8753] client session: fireConnectCallback: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:11:12.248 ThaliTest[1196:8753] jxcore: connect: success
,2015-12-03T11:11:12.249Z SendDataConnector.js: CLIENT connected to 62641, error: null
2015-12-03T11:11:12.249Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:11:12.251 ThaliTest[1196:60b] client: relay established
2015-12-03 12:11:12.252 ThaliTest[1196:60b] client: new accepted socket: 0x1c3c2630
,2015-12-03T11:11:12.263Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 12:11:18.283 ThaliTest[1196:60b] client: lost peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:11:18.284 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:11:19.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03T11:11:22.325Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T11:11:22.326Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:11:22.327Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T11:11:22.327Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:11:22.328Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 12:11:22.329 ThaliTest[1196:60b] client: socket closed
,2015-12-03 12:11:22.330 ThaliTest[1196:60b] client relay: socket disconnected
,2015-12-03 12:11:22.331 ThaliTest[1196:60b] client relay: 0x1c3c2630 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1c3c4e30 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 12:11:22.331 ThaliTest[1196:60b] client session: socket closed: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:11:22.332 ThaliTest[1196:60b] client session: onLinkFailure: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:11:22.333 ThaliTest[1196:60b] client session: disconnect
,2015-12-03 12:11:22.333 ThaliTest[1196:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:11:22.335 ThaliTest[1196:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03T11:11:27.334Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03T11:11:27.335Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:11:32.345 ThaliTest[1196:6907] jxcore: disconnect
,2015-12-03 12:11:32.347 ThaliTest[1196:6907] jxcore: disconnect: fail
2015-12-03T11:11:32.348Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03T11:11:32.349Z SendDataConnector.js: Connect (retry coun,t 4) to peer Apple-Iphone6-1_PT8234.+Hw2qA== with availability status: true
2015-12-03T11:11:32.349Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03T11:11:32.349Z SendDataConnector.js: do connect now
2015-12-03 12:11:32.350 ThaliTest[1196:6907] jxcore: connect Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:11:32.350 ThaliTest[1196:6907] client session: connect
,2015-12-03 12:11:32.351 ThaliTest[1196:6907] client session: stateChange:0->1 Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:11:34.959 ThaliTest[1196:8f73] client session: connected
2015-12-03 12:11:34.960 ThaliTest[1196:8f73] client session: stateChange:1->2 Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:11:34.967 ThaliTest[1196:8f73] client session: fireConnectCallback: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:11:34.969 ThaliTest[1196:8f73] jxcore: connect: success
,2015-12-03T11:11:34.970Z SendDataConnector.js: CLIENT connected to 62647, error: null
,2015-12-03T11:11:34.970Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:11:34.971 ThaliTest[1196:60b] client: relay established
2015-12-03 12:11:34.972 ThaliTest[1196:60b] client: new accepted socket: 0x1c20da30
,2015-12-03T11:11:34.984Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T11:11:45.046Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T11:11:45.047Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T11:11:45.047Z SendDataConnector.js: CLIENT closeClientSocket
,oneRoundDownNow
oneRoundDownNow:2
2015-12-03T11:11:45.048Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T11:11:45.049Z SendDataConnector.js: Stop data retrieving timer
2015-12-03T11:11:45.049Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 12:11:45.050 ThaliTest[1196:6907] jxcore: disconnect
2015-12-03 12:11:45.050 ThaliTest[1196:6907] client session: disconnectFromPeer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:11:45.051 ThaliTest[1196:6907] client session: disconnect
,2015-12-03 12:11:45.052 ThaliTest[1196:6907] client session: stateChange:2->0 Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:11:45.055 ThaliTest[1196:6907] jxcore: disconnect: success
2015-12-03T11:11:45.055Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8234.+Hw2qA==
,---- round done--------
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
  startTime: Thu Dec 03 2015 12:11:,45 GMT+0100 (CET),
  endTime: Thu Dec 03 2015 12:11:45 GMT+0100 (CET),
  endReason: '',
  dataTimerId: null,
  disconnecting: true }
done, now sending data to server
CoordinatorConnector-debug: sendData
-- RESULT DATA {"name:":"Apple-Iphone5-1_PT209,8","time":458262,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT7777.VxBn0g==","time":41202,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5s-1_PT7153.3coM6g==","time":205059,"re,sult":"Peer disconnected","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5s-1_PT7153.jAFxCw==","time":104657,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name,":"Apple-Iphone6-1_PT8234.+Hw2qA==","time":107286,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000}]}
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Results list d,oes not contain any items
sendList failed peers count : 4 [100 %]
- Peer ID : Apple-IpadAir2-1_PT7777.VxBn0g==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT7153.3coM6g==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT7153.jAFxCw==, Tried : 5
- Peer ID : Apple,-Iphone6-1_PT8234.+Hw2qA==, Tried : 5
sendList never tried peers count : 0 [0 %]
2015-12-03T11:11:45.076Z SendDataConnector.js: CLIENT Stop now
2015-12-03T11:11:45.076Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T11:11:45.077Z SendDataCon,nector.js: ----------------- closeClientSocket
,CoordinatorConnector-debug: disconnect:transport close
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:11:49.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:11:49.069 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:11:49.071 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:11:49.072 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:11:54.667 ThaliTest[1196:60b] client: lost peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:11:54.669 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone5s-1_PT7153.jAFxCw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:11:56.585 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:12:11.832 ThaliTest[1196:60b] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:12:11.834 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:12:16.501 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:12:19.059 ThaliTest[1196:60b] multipeer session: restart
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
,2015-12-03 12:12:49.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:12:49.072 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:12:49.073 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:12:49.073 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:13:11.721 ThaliTest[1196:60b] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:13:11.723 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:13:16.440 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 12:13:19.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:13:19.070 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:13:19.071 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:13:19.491 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:13:37.797 ThaliTest[1196:60b] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:13:37.799 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:13:38.796 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:13:41.991 ThaliTest[1196:60b] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:13:41.992 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:13:46.659 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 12:13:49.059 ThaliTest[1196:60b] multipeer session: restart
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
,2015-12-03 12:14:19.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:14:19.071 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:14:19.071 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:14:19.072 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:14:24.631 ThaliTest[1196:60b] client: lost peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:14:24.633 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone5s-1_PT7153.jAFxCw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:14:29.640 ThaliTest[1196:60b] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:14:37.578 ThaliTest[1196:60b] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:14:37.579 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:14:38.732 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:14:48.592 ThaliTest[1196:60b] client: lost peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:14:48.594 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone5s-1_PT7153.jAFxCw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:14:49.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:14:49.068 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:14:49.071 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
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
,2015-12-03 12:15:12.149 ThaliTest[1196:60b] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:15:12.150 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,",_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protoco,lVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:15:16.453 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 12:15:19.059 ThaliTest[1196:60b] multipeer session: restart
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
,2015-12-03 12:15:49.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:15:49.070 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:15:49.071 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:16:07.711 ThaliTest[1196:60b] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:16:07.712 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:16:16.574 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 12:16:19.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:16:19.069 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:16:19.070 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:16:41.782 ThaliTest[1196:60b] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:16:41.784 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:16:46.582 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:16:49.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:16:49.070 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:16:49.071 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:17:11.841 ThaliTest[1196:60b] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:17:11.842 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:17:16.851 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:17:19.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:17:19.069 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:17:19.071 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:17:41.669 ThaliTest[1196:60b] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:17:41.670 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:17:46.730 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:17:49.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:17:49.070 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:17:49.071 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:18:05.550 ThaliTest[1196:60b] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:18:05.552 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:18:05.600 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:18:19.059 ThaliTest[1196:60b] multipeer session: restart
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,",_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protoco,lVersion":13,"binaryType":"arraybuffer"}}}}
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
,2015-12-03 12:18:49.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:18:49.069 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:18:49.070 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:19:11.695 ThaliTest[1196:60b] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:19:11.696 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:19:16.362 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:19:19.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:19:19.069 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,2015-12-03 12:19:19.070 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:19:35.346 ThaliTest[1196:60b] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:19:35.347 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:19:37.462 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:19:41.707 ThaliTest[1196:60b] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:19:41.708 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:19:46.764 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 12:19:49.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:19:49.068 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
2015-12-03 12:19:49.070 ThaliTest[1196:60b] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
{"type":"connect_error","data":{"type":"TransportError","description":{"code":",ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},,"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:20:05.062 ThaliTest[1196:60b] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:20:05.063 ThaliTest[1196:60b] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:20:19.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:20:19.069 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
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
,2015-12-03 12:20:49.059 ThaliTest[1196:60b] multipeer session: restart
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
,2015-12-03 12:21:19.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:21:19.069 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
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
,2015-12-03 12:21:49.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:21:49.069 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
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
,2015-12-03 12:22:19.059 ThaliTest[1196:60b] multipeer session: restart
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
,2015-12-03 12:22:49.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:22:49.068 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
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
,2015-12-03 12:23:19.059 ThaliTest[1196:60b] multipeer session: restart
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
,2015-12-03 12:23:49.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:23:49.068 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
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
,2015-12-03 12:24:19.059 ThaliTest[1196:60b] multipeer session: restart
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
,2015-12-03 12:24:49.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:24:49.818 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
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
,2015-12-03 12:25:19.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:25:19.068 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
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
,2015-12-03 12:25:49.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:25:49.069 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
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
,2015-12-03 12:26:19.059 ThaliTest[1196:60b] multipeer session: restart
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,",_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protoco,lVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:26:19.070 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
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
,2015-12-03 12:26:49.059 ThaliTest[1196:60b] multipeer session: restart
,2015-12-03 12:26:49.069 ThaliTest[1196:60b] client: found peer: Apple-IpadAir2-1_PT7777.O0xngQ==
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
,2015-12-03 12:27:19.059 ThaliTest[1196:60b] multipeer session: restart
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

```
