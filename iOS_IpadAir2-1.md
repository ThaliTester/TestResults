#### Test 50650278cb112b9_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278cb112b9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/15821DE9-AFE9-4BC6-935A-0FE021811598/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/15821DE9-AFE9-4BC6-935A-0FE021811598/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278cb112b9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278cb112b9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AB74C495-E973-4534-B29F-78CAF6A91BAE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56160"
,(lldb)     command script import "/tmp/15821DE9-AFE9-4BC6-935A-0FE021811598/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-15 04:20:34.024 ThaliTest[1127:1220486] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/05A1C231-A9CB-4AA0-BA09-87AE77CEB71E/Library/Cookies/Cookies.binarycookies
,2015-12-15 04:20:34.390 ThaliTest[1127:1220486] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-15 04:20:34.391 ThaliTest[1127:1220486] Multi-tasking -> Device: YES, App: YES
,2015-12-15 04:20:34.400 ThaliTest[1127:1220486] Unlimited access to network resources
,2015-12-15 04:20:34.408 ThaliTest[1127:1220486] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-15 04:20:43.386 ThaliTest[1127:1220486] Resetting plugins due to page load.
,2015-12-15 04:20:46.834 ThaliTest[1127:1220486] Finished load of: file:///var/mobile/Containers/Bundle/Application/AB74C495-E973-4534-B29F-78CAF6A91BAE/ThaliTest.app/www/index.html
,2015-12-15 04:20:47.020 ThaliTest[1127:1220486] JXcore Cordova plugin initializing
,2015-12-15 04:20:47.020 ThaliTest[1127:1220706] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-15 04:20:47.987 ThaliTest[1127:1220486] THREAD WARNING: ['JXcore'] took '69.427979' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-15 04:25:46.829 ThaliTest[1127:1220706] jxcore: startBroadcasting
,2015-12-15 04:25:46.847 ThaliTest[1127:1220706] server: starting Apple-IpadAir2-1_PT7023.MnyDhQ==
,2015-12-15 04:25:46.849 ThaliTest[1127:1220706] multipeer session: start timer: 0x16458ee0
,2015-12-15 04:25:46.849 ThaliTest[1127:1220706] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT7023
2015-12-15 04:25:46.850 ThaliTest[1127:1220706] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-15 04:25:47.879 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.S9LZPw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.S9LZPw==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT1123.S9LZPw==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,teardown
,testFindPeers stopped
,2015-12-15 04:25:48.307 ThaliTest[1127:1220706] jxcore: stopBroadcasting
,2015-12-15 04:25:48.308 ThaliTest[1127:1220706] THEMultipeerSession stopping peer
,2015-12-15 04:25:48.309 ThaliTest[1127:1220706] multipeer session: stop timer
,2015-12-15 04:25:48.310 ThaliTest[1127:1220706] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 58302
,2015-12-15 04:25:48.374 ThaliTest[1127:1220706] jxcore: startBroadcasting
,2015-12-15 04:25:48.378 ThaliTest[1127:1220706] server: starting Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:25:48.379 ThaliTest[1127:1220706] multipeer session: start timer: 0x1478aa20
2015-12-15 04:25:48.380 ThaliTest[1127:1220706] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT7023
,2015-12-15 04:25:48.380 ThaliTest[1127:1220706] jxcore: startBroadcasting: success
,StartBroadcasting started ok
null
,2015-12-15T03:25:48.385Z SendDataTCPServer.js: TCP/IP server is bound to port: 58302
,2015-12-15 04:25:48.392 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:25:48.393 ThaliTest[1127:1220486] client: found peer: Apple-IpadAir2-1_PT7023.MnyDhQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.S9LZPw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:25:48.397Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:25:48.397Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:25:48.398Z SendDataConnector.js: do connect now
,2015-12-15 04:25:48.399 ThaliTest[1127:1220706] jxcore: connect Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:25:48.399 ThaliTest[1127:1220706] client session: connect
,2015-12-15 04:25:48.400 ThaliTest[1127:1220706] client session: stateChange:0->1 Apple-Iphone6-1_PT1123.S9LZPw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7023.MnyDhQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-15 04:25:48.422 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.mlJOKQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9128.mlJOKQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 04:25:49.530 ThaliTest[1127:1220486] client: lost peer: Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:25:49.530 ThaliTest[1127:1220486] client session: onPeerLost: Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:25:49.531 ThaliTest[1127:1220486] client session: onLinkFailure: Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:25:49.531 ThaliTest[1127:1220486] client session: disconnect
,2015-12-15 04:25:49.531 ThaliTest[1127:1220486] client session: stateChange:1->0 Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:25:49.532 ThaliTest[1127:1220486] client session: fireConnectCallback: Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:25:49.533 ThaliTest[1127:1220486] jxcore: connect: fail: Peer disconnected
,2015-12-15 04:25:49.533 ThaliTest[1127:1220486] client: lost peer: Apple-IpadAir2-1_PT7023.MnyDhQ==
2015-12-15 04:25:49.534 ThaliTest[1127:1220486] client session: onPeerLost: Apple-IpadAir2-1_PT7023.MnyDhQ==
2015-12-15T03:25:49.535Z SendDataConnector.js,: CLIENT connected to 0, error: Peer disconnected
2015-12-15T03:25:49.535Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-15T03:25:49.536Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.S9LZPw==","peerName":"(null)","peerAvailable":false}]
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7023.MnyDhQ==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2015-12-15 04:25:49.926 ThaliTest[1127:1220486] client: lost peer: Apple-Iphone5-1_PT9128.mlJOKQ==
2015-12-15 04:25:49.926 ThaliTest[1127:1220486] client session: onPeerLost: Apple-Iphone5-1_PT9128.mlJOKQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9128.mlJOKQ==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2015-12-15 04:25:50.030 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.uhofxg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 04:25:50.133 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9128.H9FQ7Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 04:25:50.173 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9749.OdNUWQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 04:25:54.361 ThaliTest[1127:1220486] multipeer session: reset timer
2015-12-15 04:25:54.362 ThaliTest[1127:1220486] multipeer session: stop timer
2015-12-15 04:25:54.364 ThaliTest[1127:1220486] multipeer session: start timer: 0x1478aa20
,2015-12-15 04:25:54.365 ThaliTest[1127:1220486] server session: connect
2015-12-15 04:25:54.365 ThaliTest[1127:1220486] server session: stateChange:0->1 Apple-Iphone5-1_PT9128
,2015-12-15 04:25:54.372 ThaliTest[1127:1220486] server: accepting invitation Apple-Iphone5-1_PT9128
,2015-12-15T03:25:54.540Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:25:54.541Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:25:57.844 ThaliTest[1127:1221259] server session: connected
2015-12-15 04:25:57.845 ThaliTest[1127:1221259] server session: stateChange:1->2 Apple-Iphone5-1_PT9128
,2015-12-15 04:25:57.854 ThaliTest[1127:1220486] server relay: connected (to port: 58302)
,2015-12-15T03:25:57.864Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T03:25:58.369Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-15T03:25:58.421Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-15T03:25:58.436Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-15T03:25:58.452Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-15T03:25:58.493Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 04:25:58.631 ThaliTest[1127:1221259] server session: not connected Apple-Iphone5-1_PT9128
,2015-12-15 04:25:59.549 ThaliTest[1127:1220706] jxcore: disconnect
,2015-12-15 04:25:59.550 ThaliTest[1127:1220706] jxcore: disconnect: fail
,2015-12-15T03:25:59.551Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:25:59.551Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT1123.S9LZPw== with availability status: true
,2015-12-15T03:25:59.552Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:25:59.553Z SendDataConnector.js: do connect now
,2015-12-15 04:25:59.554 ThaliTest[1127:1220706] jxcore: connect Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:25:59.554 ThaliTest[1127:1220706] client: connect: unreachable Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:25:59.555 ThaliTest[1127:1220706] jxcore: connect: fail: Peer unreachable
,2015-12-15T03:25:59.555Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-15T03:25:59.556Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-15T03:25:59.557Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T03:26:04.558Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:26:04.558Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:26:09.566 ThaliTest[1127:1220706] jxcore: disconnect
,2015-12-15 04:26:09.567 ThaliTest[1127:1220706] jxcore: disconnect: fail
,2015-12-15T03:26:09.567Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:26:09.568Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT1123.S9LZPw== with availability status: true
,2015-12-15T03:26:09.569Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:26:09.569Z SendDataConnector.js: do connect now
,2015-12-15 04:26:09.570 ThaliTest[1127:1220706] jxcore: connect Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:26:09.571 ThaliTest[1127:1220706] client: connect: unreachable Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:26:09.571 ThaliTest[1127:1220706] jxcore: connect: fail: Peer unreachable
,2015-12-15T03:26:09.572Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-15T03:26:09.573Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-15T03:26:09.573Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T03:26:14.587Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:26:14.587Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:26:19.593 ThaliTest[1127:1220706] jxcore: disconnect
,2015-12-15 04:26:19.594 ThaliTest[1127:1220706] jxcore: disconnect: fail
,2015-12-15T03:26:19.595Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:26:19.596Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT1123.S9LZPw== with availability status: true
,2015-12-15T03:26:19.596Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:26:19.597Z SendDataConnector.js: do connect now
,2015-12-15 04:26:19.598 ThaliTest[1127:1220706] jxcore: connect Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:26:19.599 ThaliTest[1127:1220706] client: connect: unreachable Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:26:19.599 ThaliTest[1127:1220706] jxcore: connect: fail: Peer unreachable
,2015-12-15T03:26:19.601Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-15T03:26:19.601Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-15T03:26:19.601Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15 04:26:24.366 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:26:24.395 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:26:24.395 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:26:24.396 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15T03:26:24.611Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:26:24.612Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:26:29.623 ThaliTest[1127:1220706] jxcore: disconnect
,2015-12-15 04:26:29.624 ThaliTest[1127:1220706] jxcore: disconnect: fail
,2015-12-15T03:26:29.624Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:26:29.625Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT1123.S9LZPw== with availability status: true
,2015-12-15T03:26:29.626Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:26:29.626Z SendDataConnector.js: do connect now
,2015-12-15 04:26:29.627 ThaliTest[1127:1220706] jxcore: connect Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:26:29.628 ThaliTest[1127:1220706] client: connect: unreachable Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:26:29.628 ThaliTest[1127:1220706] jxcore: connect: fail: Peer unreachable
,2015-12-15T03:26:29.629Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-15T03:26:29.630Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2015-12-15T03:26:29.632Z SendDataConnector.js: CLIENT Stop now
,2015-12-15 04:26:29.633 ThaliTest[1127:1220706] jxcore: disconnect
,2015-12-15 04:26:29.633 ThaliTest[1127:1220706] jxcore: disconnect: fail
,2015-12-15T03:26:29.634Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1123.S9LZPw==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15T03:26:29.637Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15T03:26:29.638Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15T03:26:29.638Z SendDataConnector.js: do connect now
,2015-12-15 04:26:29.640 ThaliTest[1127:1220706] jxcore: connect Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:26:29.640 ThaliTest[1127:1220706] client session: connect
,2015-12-15 04:26:29.641 ThaliTest[1127:1220706] client session: stateChange:0->1 Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:26:29.933 ThaliTest[1127:1220486] multipeer session: reset timer
2015-12-15 04:26:29.933 ThaliTest[1127:1220486] multipeer session: stop timer
2015-12-15 04:26:29.933 ThaliTest[1127:1220486] multipeer session: start timer: 0x1478aa20
2015-12-15 04:26:29.934 ThaliTest[1127:1220486] server session: connect
,2015-12-15 04:26:29.934 ThaliTest[1127:1220486] server session: stateChange:0->1 Apple-Iphone6-1_PT1123
,2015-12-15 04:26:29.941 ThaliTest[1127:1220486] server: accepting invitation Apple-Iphone6-1_PT1123
,2015-12-15 04:26:32.610 ThaliTest[1127:1221386] client session: connected
,2015-12-15 04:26:32.610 ThaliTest[1127:1221386] client session: stateChange:1->2 Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:26:32.619 ThaliTest[1127:1221372] server session: connected
,2015-12-15 04:26:32.619 ThaliTest[1127:1221372] server session: stateChange:1->2 Apple-Iphone6-1_PT1123
,2015-12-15 04:26:32.673 ThaliTest[1127:1221386] client session: fireConnectCallback: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:26:32.673 ThaliTest[1127:1221386] jxcore: connect: success
,2015-12-15T03:26:32.675Z SendDataConnector.js: CLIENT connected to 58309, error: null
,2015-12-15T03:26:32.675Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 04:26:32.678 ThaliTest[1127:1220486] client: relay established
2015-12-15 04:26:32.678 ThaliTest[1127:1220486] client: new accepted socket: 0x1646b4b0
,2015-12-15T03:26:32.694Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15 04:26:32.744 ThaliTest[1127:1220486] server relay: connected (to port: 58302)
,2015-12-15T03:26:32.962Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T03:26:32.997Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-15T03:26:33.010Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-15T03:26:33.062Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-15T03:26:33.075Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-15T03:26:33.200Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 04:26:33.258 ThaliTest[1127:1221386] server session: not connected Apple-Iphone6-1_PT1123
,2015-12-15T03:26:33.264Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-15T03:26:33.327Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T03:26:33.327Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-15T03:26:33.328Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T03:26:33.328Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 04:26:33.329 ThaliTest[1127:1220706] jxcore: disconnect
,2015-12-15 04:26:33.330 ThaliTest[1127:1220706] client session: disconnectFromPeer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:26:33.330 ThaliTest[1127:1220706] client session: disconnect
2015-12-15 04:26:33.330 ThaliTest[1127:1220706] client session: stateChange:2->0 Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:26:33.335 ThaliTest[1127:1220706] jxcore: disconnect: success
2015-12-15T03:26:33.335Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1123.uhofxg==
---- round done--------
startWithNextDevice
device[3]: App,le-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15T03:26:33.336Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15T03:26:33.336Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15T03:26,:33.336Z SendDataConnector.js: do connect now
2015-12-15 04:26:33.337 ThaliTest[1127:1220706] jxcore: connect Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:26:33.337 ThaliTest[1127:1220706] client session: connect
2015-12-15 04:26:33.337 ThaliTest[1127:,1220706] client session: stateChange:0->1 Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:26:34.777 ThaliTest[1127:1220486] multipeer session: reset timer
2015-12-15 04:26:34.778 ThaliTest[1127:1220486] multipeer session: stop timer
2015-12-15 04:26:34.778 ThaliTest[1127:1220486] multipeer session: start timer: 0x1478aa20
,2015-12-15 04:26:34.778 ThaliTest[1127:1220486] server session: connect
2015-12-15 04:26:34.779 ThaliTest[1127:1220486] server session: stateChange:0->1 Apple-Iphone5s-1_PT9749
,2015-12-15 04:26:34.786 ThaliTest[1127:1220486] server: accepting invitation Apple-Iphone5s-1_PT9749
,2015-12-15 04:26:36.464 ThaliTest[1127:1221385] client session: connected
,2015-12-15 04:26:36.465 ThaliTest[1127:1221385] client session: stateChange:1->2 Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:26:36.469 ThaliTest[1127:1221385] client session: fireConnectCallback: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:26:36.470 ThaliTest[1127:1221385] jxcore: connect: success
,2015-12-15T03:26:36.472Z SendDataConnector.js: CLIENT connected to 58313, error: null
,2015-12-15T03:26:36.473Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 04:26:36.476 ThaliTest[1127:1220486] client: relay established
2015-12-15 04:26:36.476 ThaliTest[1127:1220486] client: new accepted socket: 0x16475c60
,2015-12-15T03:26:36.490Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T03:26:37.116Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T03:26:37.117Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-15T03:26:37.118Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T03:26:37.118Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 04:26:37.119 ThaliTest[1127:1220706] jxcore: disconnect
,2015-12-15 04:26:37.120 ThaliTest[1127:1220706] client session: disconnectFromPeer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:26:37.120 ThaliTest[1127:1220706] client session: disconnect
,2015-12-15 04:26:37.120 ThaliTest[1127:1220706] client session: stateChange:2->0 Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:26:37.127 ThaliTest[1127:1220706] jxcore: disconnect: success
,2015-12-15T03:26:37.128Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9128.H9FQ7Q==
---- round done--------
startWithNextDevice
,device[4]: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15T03:26:37.132Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15T03:26:37.132Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9749.OdNUWQ==,
2015-12-15T03:26:37.132Z SendDataConnector.js: do connect now
2015-12-15 04:26:37.133 ThaliTest[1127:1220706] jxcore: connect Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:26:37.133 ThaliTest[1127:1220706] client session: connect
,2015-12-15 04:26:37.134 ThaliTest[1127:1220706] client session: stateChange:0->1 Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:26:37.598 ThaliTest[1127:1221383] server session: connected
2015-12-15 04:26:37.598 ThaliTest[1127:1221383] server session: stateChange:1->2 Apple-Iphone5s-1_PT9749
,2015-12-15 04:26:37.654 ThaliTest[1127:1220486] server relay: connected (to port: 58302)
,2015-12-15T03:26:37.661Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T03:26:37.986Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-15T03:26:38.004Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-15T03:26:38.020Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-15T03:26:38.046Z SendDataTCPServer.js: TCP/IP server has received 85126 bytes of data
,2015-12-15T03:26:38.061Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 04:26:38.140 ThaliTest[1127:1221372] server session: not connected Apple-Iphone5s-1_PT9749
,2015-12-15 04:26:40.604 ThaliTest[1127:1221382] client session: connected
2015-12-15 04:26:40.604 ThaliTest[1127:1221382] client session: stateChange:1->2 Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:26:40.646 ThaliTest[1127:1221382] client session: fireConnectCallback: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:26:40.647 ThaliTest[1127:1221382] jxcore: connect: success
,2015-12-15T03:26:40.649Z SendDataConnector.js: CLIENT connected to 58317, error: null
,2015-12-15T03:26:40.649Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 04:26:40.653 ThaliTest[1127:1220486] client: relay established
,2015-12-15 04:26:40.653 ThaliTest[1127:1220486] client: new accepted socket: 0x1654a150
,2015-12-15T03:26:40.666Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T03:26:41.583Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-15T03:26:41.598Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-15T03:26:41.613Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T03:26:41.614Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-15T03:26:41.615Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T03:26:41.615Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 04:26:41.617 ThaliTest[1127:1220706] jxcore: disconnect
,2015-12-15 04:26:41.617 ThaliTest[1127:1220706] client session: disconnectFromPeer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:26:41.618 ThaliTest[1127:1220706] client session: disconnect
,2015-12-15 04:26:41.618 ThaliTest[1127:1220706] client session: stateChange:2->0 Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:26:41.628 ThaliTest[1127:1220706] jxcore: disconnect: success
2015-12-15T03:26:41.628Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9749.OdNUWQ==
---- round done--------
startWithNextDevice
weAreDoneNow,, resultArray.length: 4
sendReportNow
done, now sending data to server
,2015-12-15T03:26:41.637Z SendDataConnector.js: CLIENT Stop now
2015-12-15T03:26:41.637Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 04:27:04.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:27:04.809 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:27:04.809 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:27:04.809 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:27:34.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:27:34.811 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:27:34.811 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:27:34.812 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:28:04.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:28:04.808 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:28:04.808 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:28:04.809 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:28:34.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:28:34.808 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:28:34.809 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:28:34.809 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,Connected to the server!
,2015-12-15 04:29:04.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:29:04.813 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:29:04.813 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:29:04.813 ThaliTest[1127:1220486] client,: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:29:34.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:29:34.808 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:29:34.808 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:29:44.088 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:29:44.089 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:30:04.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:30:05.434 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:30:05.435 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:30:05.437 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:30:34.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:30:34.807 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:30:34.808 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:30:34.809 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:31:04.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:31:04.807 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:31:04.807 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:31:04.809 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:31:34.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:31:34.812 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:31:34.812 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:31:34.812 ThaliTest[1127:1220486] clien,t: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:32:04.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:32:04.810 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:32:04.811 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:32:04.811 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:32:34.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:32:34.807 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:32:34.808 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:32:34.809 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:33:04.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:33:04.807 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:33:04.808 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:33:04.810 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:33:23.893 ThaliTest[1127:1220486] client: lost peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:33:23.894 ThaliTest[1127:1220486] client session: onPeerLost: Apple-Iphone5s-1_PT9749.OdNUWQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9749.OdNUWQ==","peerName":"(null)","peerAvailable":false}]
,startWithNextDevice
,2015-12-15 04:33:34.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:33:34.805 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:33:34.805 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:33:48.840 ThaliTest[1127:1220486] client: lost peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:33:48.841 ThaliTest[1127:1220486] client session: onPeerLost: Apple-Iphone5-1_PT9128.H9FQ7Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9128.H9FQ7Q==","peerName":"(null)","peerAvailable":false}]
,startWithNextDevice
,2015-12-15 04:33:50.461 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9128.H9FQ7Q==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-15 04:33:50.535 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9749.OdNUWQ==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-15 04:34:04.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:34:04.812 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:34:04.812 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:34:04.813 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:34:34.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:34:35.438 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:34:35.439 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:34:35.439 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:35:04.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:35:04.807 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:35:04.808 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:35:04.808 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:35:34.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:35:34.808 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:35:34.808 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:35:34.808 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:36:04.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:36:04.809 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:36:04.809 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:36:04.810 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:36:34.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:36:34.810 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:36:34.811 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:36:34.811 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:37:04.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:37:04.807 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:37:04.807 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:37:04.810 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:37:34.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:37:34.809 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:37:34.810 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:37:34.811 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:38:04.780 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:38:04.807 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:38:04.808 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:38:04.808 ThaliTest[1127:1220486] client,: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:38:34.765 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:38:35.660 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:38:35.660 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:38:35.660 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:39:04.765 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:39:34.765 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:39:35.429 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:39:35.429 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:39:35.429 ThaliTest[1127:1220486] clien,t: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:40:04.765 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:40:04.794 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:40:04.794 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:40:04.797 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:40:34.765 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:40:34.790 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:40:34.791 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:40:34.792 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:41:04.765 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:41:04.791 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:41:04.791 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:41:04.791 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:41:34.765 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:41:35.384 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:41:35.384 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:41:35.384 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:42:04.765 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:42:04.788 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:42:04.788 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:42:06.424 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:42:34.765 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:42:34.791 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:42:34.792 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:42:34.793 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:43:04.765 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:43:04.790 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:43:04.790 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:43:04.791 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:43:34.765 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:43:34.789 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:43:34.790 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:43:34.790 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:44:04.765 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:44:04.789 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:44:04.791 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:44:04.791 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:44:34.765 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:45:04.765 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:45:04.788 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:45:04.789 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:45:04.790 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:45:34.765 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:45:34.791 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:45:34.791 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:45:34.792 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:46:04.765 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:46:05.530 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:46:05.530 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:46:05.531 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:46:34.765 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:46:34.792 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:46:34.792 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:46:34.792 ThaliTest[1127:1220486] client,: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:47:04.765 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:47:04.791 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:47:04.792 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:47:04.792 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:47:34.765 ThaliTest[1127:1220486] multipeer session: restart
,2015-12-15 04:47:34.789 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:47:34.790 ThaliTest[1127:1220486] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:47:34.791 ThaliTest[1127:1220486] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==

```
