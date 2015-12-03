#### Test 5065027835b6ad9_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027835b6ad9/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/7F6B3542-324A-44EF-9F15-41A420458698/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/7F6B3542-324A-44EF-9F15-41A420458698/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027835b6ad9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027835b6ad9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F8B429B7-510C-4A50-894C-34308698DCBB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60254"
,(lldb)     command script import "/tmp/7F6B3542-324A-44EF-9F15-41A420458698/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-03 12:02:04.641 ThaliTest[1887:2965777] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D305A3E9-D0DE-452E-8AAD-213DB8EE6FB8/Library/Cookies/Cookies.binarycookies
,2015-12-03 12:02:04.931 ThaliTest[1887:2965777] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 12:02:04.932 ThaliTest[1887:2965777] Multi-tasking -> Device: YES, App: YES
,2015-12-03 12:02:04.938 ThaliTest[1887:2965777] Unlimited access to network resources
,2015-12-03 12:02:04.944 ThaliTest[1887:2965777] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 12:02:09.132 ThaliTest[1887:2965777] Resetting plugins due to page load.
,2015-12-03 12:02:10.598 ThaliTest[1887:2965777] Finished load of: file:///var/mobile/Containers/Bundle/Application/F8B429B7-510C-4A50-894C-34308698DCBB/ThaliTest.app/www/index.html
,2015-12-03 12:02:10.747 ThaliTest[1887:2965777] JXcore Cordova plugin initializing
,2015-12-03 12:02:10.748 ThaliTest[1887:2965947] JXcore instance initializing
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
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-03 12:04:03.614 ThaliTest[1887:2965947] jxcore: startBroadcasting
,2015-12-03 12:04:03.621 ThaliTest[1887:2965947] server: starting Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:03.621 ThaliTest[1887:2965947] multipeer session: start timer: 0x86a44f0
2015-12-03 12:04:03.621 ThaliTest[1887:2965947] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT7777
2015-12-03 12:04:03.621 ThaliTest[1887:2965947] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-03 12:04:07.285 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.2PCWSw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2098.2PCWSw==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5-1_PT2098.2PCWSw==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,CoordinatorConnector-debug: sendData
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT7777","time":3675,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5-1_PT2098.2PCWSw==","peerAvailable":true,"time":3674}]}
,peersList : 100% : 3674 ms, 99% : 3674 ms, 95 : 3674 ms, 90% : 3674 ms.
,Result count 1, range 3674 ms to  3674 ms.
,2015-12-03 12:04:07.305 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:04:07.413 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.n7uNOA==
,CoordinatorConnector-debug: stop:undefined
,stop tests now !
stop current!
,testFindPeers stopped
2015-12-03 12:04:07.552 ThaliTest[1887:2965947] jxcore: stopBroadcasting
,2015-12-03 12:04:07.552 ThaliTest[1887:2965947] THEMultipeerSession stopping peer
,2015-12-03 12:04:07.552 ThaliTest[1887:2965947] multipeer session: stop timer
2015-12-03 12:04:07.553 ThaliTest[1887:2965947] jxcore: stopBroadcasting: success
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
serverPort is 50419
,2015-12-03 12:04:07.600 ThaliTest[1887:2965947] jxcore: startBroadcasting
,2015-12-03 12:04:07.601 ThaliTest[1887:2965947] server: starting Apple-IpadAir2-1_PT7777.O0xngQ==
2015-12-03 12:04:07.601 ThaliTest[1887:2965947] multipeer session: start timer: 0xa45a80
2015-12-03 12:04:07.601 ThaliTest[1887:2965947] THEMultipeerSession, initialized peer Apple-IpadAir2-1_PT7777
2015-12-03 12:04:07.601 ThaliTest[1887:2965947] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-03T11:04:07.603Z SendDataTCPServer.js: TCP/IP server is bound to port: 50419
,2015-12-03 12:04:08.073 ThaliTest[1887:2965777] client: found peer: Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:08.073 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:04:08.073 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.2PCWSw==
,2015-12-03 12:04:08.075 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.n7uNOA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7777.VxBn0g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03T11:04:08.077Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03T11:04:08.077Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03T11:04:08.078Z SendDataConnector.js: do connect now
,2015-12-03 12:04:08.078 ThaliTest[1887:2965947] jxcore: connect Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:08.078 ThaliTest[1887:2965947] client session: connect
2015-12-03 12:04:08.079 ThaliTest[1887:2965947] client session: stateChange:0->1 Apple-IpadAir2-1_PT7777.VxBn0g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.3coM6g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2098.2PCWSw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.n7uNOA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 12:04:08.742 ThaliTest[1887:2965777] client: lost peer: Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:08.742 ThaliTest[1887:2965777] client session: onPeerLost: Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:08.742 ThaliTest[1887:2965777] client session: onLinkFailure: Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:08.742 ThaliTest[1887:2965777] client session: disconnect
2015-12-03 12:04:08.742 ThaliTest[1887:2965777] client session: stateChange:1->0 Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:08.743 ThaliTest[1887:2965777] client session: fireConnectCallback: Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:08.743 ThaliTest[1887:2965777] jxcore: connect: fail: Peer disconnected
,2015-12-03T11:04:08.744Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T11:04:08.744Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-03T11:04:08.744Z SendDataConnector.js: tryAgain afer: 5000 ms.,
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7777.VxBn0g==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:04:08.880 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2098.P4cq9w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 12:04:08.968 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:04:08.968 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 12:04:10.457 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone6-1_PT8234.n7uNOA==
2015-12-03 12:04:10.457 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone6-1_PT8234.n7uNOA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.n7uNOA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 12:04:11.013 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone5-1_PT2098.2PCWSw==
2015-12-03 12:04:11.014 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone5-1_PT2098.2PCWSw==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone5-1_PT2098.2PCWSw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 12:04:12.685 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:04:12.685 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone5s-1_PT7153.3coM6g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.3coM6g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03T11:04:13.756Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03T11:04:13.756Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:18.364 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.3coM6g==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-03 12:04:18.763 ThaliTest[1887:2965947] jxcore: disconnect
2015-12-03 12:04:18.763 ThaliTest[1887:2965947] jxcore: disconnect: fail
2015-12-03T11:04:18.764Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03T11:04:18.764Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT7777.VxBn0g== with availability status: true
2015-12-03T11:04:18.764Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03T11:04:18.764Z SendDataConnector.js: do connect now
,2015-12-03 12:04:18.764 ThaliTest[1887:2965947] jxcore: connect Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:18.765 ThaliTest[1887:2965947] client: connect: unreachable Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:18.765 ThaliTest[1887:2965947] jxcore: connect: fail: Peer unreachable
2015-12-03T11:04:18.765Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-03T11:04:18.765Z SendDataConnector.js: CLIENT Can not Connect: P,eer unreachable
2015-12-03T11:04:18.765Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:04:23.769Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03T11:04:23.769Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:28.772 ThaliTest[1887:2965947] jxcore: disconnect
2015-12-03 12:04:28.772 ThaliTest[1887:2965947] jxcore: disconnect: fail
,2015-12-03T11:04:28.772Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03T11:04:28.772Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT7777.VxBn0g== with availability status: true
2015-12-03T11:04:28.773Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03T11:04:28.773Z SendDataConnector.js: do connect now
2015-12-03 12:04:28.773 ThaliTest[1887:2965947] jxcore: connect Apple-IpadAir,2-1_PT7777.VxBn0g==
2015-12-03 12:04:28.773 ThaliTest[1887:2965947] client: connect: unreachable Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:28.773 ThaliTest[1887:2965947] jxcore: connect: fail: Peer unreachable
,2015-12-03T11:04:28.773Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-03T11:04:28.774Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-03T11:04:28.774Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:04:33.777Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03T11:04:33.777Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:37.603 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:04:37.616 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:04:37.616 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:04:37.617 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:04:37.617 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:04:38.779 ThaliTest[1887:2965947] jxcore: disconnect
2015-12-03 12:04:38.779 ThaliTest[1887:2965947] jxcore: disconnect: fail
,2015-12-03T11:04:38.780Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03T11:04:38.780Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT7777.VxBn0g== with availability status,: true
2015-12-03T11:04:38.780Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03T11:04:38.780Z SendDataConnector.js: do connect now
2015-12-03 12:04:38.780 ThaliTest[1887:2965947] jxcore: connect Apple-IpadAir,2-1_PT7777.VxBn0g==
2015-12-03 12:04:38.780 ThaliTest[1887:2965947] client: connect: unreachable Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:38.780 ThaliTest[1887:2965947] jxcore: connect: fail: Peer unreachable
2015-12-03T11:04:38.780Z SendDataCo,nnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-03T11:04:38.781Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-03T11:04:38.781Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T11:04:43.784Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03T11:04:43.784Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:45.059 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:04:45.059 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone5s-1_PT7153.3coM6g==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT7153.3coM6g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 12:04:46.626 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:04:46.626 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 12:04:48.794 ThaliTest[1887:2965947] jxcore: disconnect
2015-12-03 12:04:48.794 ThaliTest[1887:2965947] jxcore: disconnect: fail
2015-12-03T11:04:48.794Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03T11:04:48.795Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT7777.VxBn0g== with availability status: true
2015-12-03T11:04:48.795Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03T11:04:48.795Z SendDataConnector.js: do connect now
2015-12-03 12:04:48.795 ThaliTest[1887:2965947] jxcore: connect Apple-IpadAir2-1_PT7777.VxBn0g==
,2015-12-03 12:04:48.796 ThaliTest[1887:2965947] client: connect: unreachable Apple-IpadAir2-1_PT7777.VxBn0g==
2015-12-03 12:04:48.796 ThaliTest[1887:2965947] jxcore: connect: fail: Peer unreachable
2015-12-03T11:04:48.796Z SendDataConnector.js: CLIENT co,nnected to 0, error: Peer unreachable
2015-12-03T11:04:48.796Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,oneRoundDownNow:2
,2015-12-03T11:04:48.797Z SendDataConnector.js: CLIENT Stop now
,2015-12-03 12:04:48.798 ThaliTest[1887:2965947] jxcore: disconnect
2015-12-03 12:04:48.798 ThaliTest[1887:2965947] jxcore: disconnect: fail
2015-12-03T11:04:48.798Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7777.VxBn0g==
---- round done--------
,device[2]: Apple-Iphone5-1_PT2098.P4cq9w==
,2015-12-03T11:04:48.799Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03T11:04:48.800Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2098.P4cq9w==
,2015-12-03T11:04:48.800Z SendDataConnector.js: do connect now
,2015-12-03 12:04:48.800 ThaliTest[1887:2965947] jxcore: connect Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:04:48.801 ThaliTest[1887:2965947] client session: connect
2015-12-03 12:04:48.801 ThaliTest[1887:2965947] client session: stateChange:0->1 Apple-Iphone5-1_PT2098.P4cq9w==
,2015-12-03 12:04:49.334 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-03 12:04:52.393 ThaliTest[1887:2966285] client session: connected
2015-12-03 12:04:52.393 ThaliTest[1887:2966285] client session: stateChange:1->2 Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:04:52.394 ThaliTest[1887:2966285] client session: fir,eConnectCallback: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:04:52.394 ThaliTest[1887:2966285] jxcore: connect: success
2015-12-03T11:04:52.395Z SendDataConnector.js: CLIENT connected to 50426, error: null
2015-12-03T11:04:52.395Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:04:52.396 ThaliTest[1887:2965777] client: relay established
2015-12-03 12:04:52.396 ThaliTest[1887:2965777] client: new accepted socket: 0x86bd8d0
,2015-12-03T11:04:52.410Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T11:04:52.660Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-03T11:04:52.674Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-03T11:04:52.674Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,oneRoundDownNow:2
,2015-12-03T11:04:52.675Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T11:04:52.675Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 12:04:52.676 ThaliTest[1887:2965947] jxcore: disconnect
,2015-12-03 12:04:52.677 ThaliTest[1887:2965947] client session: disconnectFromPeer: Apple-Iphone5-1_PT2098.P4cq9w==
,2015-12-03 12:04:52.677 ThaliTest[1887:2965947] client session: disconnect
,2015-12-03 12:04:52.678 ThaliTest[1887:2965947] client session: stateChange:2->0 Apple-Iphone5-1_PT2098.P4cq9w==
,2015-12-03 12:04:52.746 ThaliTest[1887:2965947] jxcore: disconnect: success
,2015-12-03T11:04:52.746Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2098.P4cq9w==
,---- round done--------
,device[3]: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:04:52.748Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:04:52.748Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03T11:04:52.748Z SendDataConnector.js: do connect now
,2015-12-03 12:04:52.749 ThaliTest[1887:2965947] jxcore: connect Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:04:52.749 ThaliTest[1887:2965947] client session: connect
,2015-12-03 12:04:52.750 ThaliTest[1887:2965947] client session: stateChange:0->1 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:04:57.658 ThaliTest[1887:2966284] client session: connected
2015-12-03 12:04:57.659 ThaliTest[1887:2966284] client session: stateChange:1->2 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:04:57.676 ThaliTest[1887:2966285] client session: fireConnectCallback: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:04:57.677 ThaliTest[1887:2966285] jxcore: connect: success
2015-12-03T11:04:57.677Z SendDataConnector.js: CLIENT connected to 50430, error: null
2015-12-03T11:04:57.677Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:04:57.678 ThaliTest[1887:2965777] client: relay established
2015-12-03 12:04:57.678 ThaliTest[1887:2965777] client: new accepted socket: 0x86bd9e0
,2015-12-03T11:04:57.691Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T11:04:57.916Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-03T11:04:57.929Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-03T11:04:57.978Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03T11:04:57.992Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-03T11:04:57.992Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,oneRoundDownNow:2
,2015-12-03T11:04:57.993Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T11:04:57.993Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 12:04:57.994 ThaliTest[1887:2965947] jxcore: disconnect
,2015-12-03 12:04:57.994 ThaliTest[1887:2965947] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:04:57.994 ThaliTest[1887:2965947] client session: disconnect
2015-12-03 12:04:57.994 ThaliTest[1887:2965947] client session: stateChange:2->0 Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:04:57.998 ThaliTest[1887:2965947] jxcore: disconnect: success
2015-12-03T11:04:57.999Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7153.jAFxCw==
---- round done--------
device[4]: Apple-Iphone6-1_PT8234.,+Hw2qA==
2015-12-03T11:04:57.999Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03T11:04:57.999Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03T11:04:57.999Z SendDataConnector.js: do connect now
2015-12-03 12:04:57.999 ThaliTest[1887:2965947] jxcore: connect Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:04:58.000 ThaliTest[1887:2965947] client session: connect
2015-12-03 12:04:58.000 ThaliTest[1887:2965947] client sess,ion: stateChange:0->1 Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:05:03.150 ThaliTest[1887:2966284] client session: connected
2015-12-03 12:05:03.150 ThaliTest[1887:2966284] client session: stateChange:1->2 Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:05:03.153 ThaliTest[1887:2966344] client session: fireConnectCallback: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:05:03.153 ThaliTest[1887:2966344] jxcore: connect: success
2015-12-03T11:05:03.154Z SendDataConnector.js: CLIENT connected to 50434, error: null
2015-12-03T11:05:03.154Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 12:05:03.155 ThaliTest[1887:2965777] client: relay established
2015-12-03 12:05:03.155 ThaliTest[1887:2965777] client: new accepted socket: 0x86bdbf0
,2015-12-03T11:05:03.168Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T11:05:03.389Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-03T11:05:03.415Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-03T11:05:03.428Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-03T11:05:03.441Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-03T11:05:03.454Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-03T11:05:03.454Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,oneRoundDownNow:2
,2015-12-03T11:05:03.455Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T11:05:03.455Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 12:05:03.456 ThaliTest[1887:2965947] jxcore: disconnect
,2015-12-03 12:05:03.456 ThaliTest[1887:2965947] client session: disconnectFromPeer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:05:03.456 ThaliTest[1887:2965947] client session: disconnect
2015-12-03 12:05:03.456 ThaliTest[1887:2965947] client session: stateChange:2->0 Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:05:03.459 ThaliTest[1887:2965947] jxcore: disconnect: success
2015-12-03T11:05:03.460Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8234.+Hw2qA==
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
        slab_0xa50970: null },
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
        defa,ultEncoding: 'utf8',
        ranOut: false,
        awaitDrain: 0,
        readingMore: false,
        decoder: null,
        encoding: null },
     readable: true,
     domain: null,
     _events: 
      { end: [Object],
        finish: [Functio,n: onSocketFinish],
        _socketEnd: [Function: onSocketEnd],
        data: [Function],
        readable: [Function],
        error: [Function] },
     _maxListeners: 10,
     _writableState: 
      { highWaterMark: 16384,
        objectMode: fa,lse,
        needDrain: false,
        ending: true,
        ended: true,
        finished: true,
        decodeStrings: false,
        defaultEncoding: 'utf8',
        length: 0,
        writing: false,
        sync: false,
        bufferProcess,ing: false,
        onwrite: [Function],
        writecb: null,
        writelen: 0,
        buffer: [],
        errorEmitted: false },
     writable: false,
     allowHalfOpen: false,
     onend: null,
     destroyed: false,
     bytesRead: 30,,
     _bytesDispatched: 50000,
     _pendingData: null,
     _pendingEncoding: '',
     __ec_int: true,
     ___timerId: 1,
     pipe: [Function],
     addListener: [Function: addListener],
     on: [Function: addListener],
     pause: [Function],,
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
 , startTime: Thu Dec 03 2015 12:05:03 GMT+0100 (CET),
  endTime: Thu Dec 03 2015 12:05:03 GMT+0100 (CET),
  endReason: '',
  dataTimerId: null }
done, now sending data to server
,CoordinatorConnector-debug: sendData
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT7777","time":55866,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT7777.VxBn0g==","time":40720,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5-1_PT2098.P4cq9w==","time":3875,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT7153.jAFxCw==","time":5245,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataRec,eived":100000},{"name":"Apple-Iphone6-1_PT8234.+Hw2qA==","time":5456,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
sendList : 100% : 5456 ms, 99% : 5456 ms, 95 : 5456 ms, 90% : 5456 ms.
Result count 3, range 3875 ms to  5456 ms.
,sendList failed peers count : 1 [25 %]
,- Peer ID : Apple-IpadAir2-1_PT7777.VxBn0g==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-12-03T11:05:03.471Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T11:05:03.472Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 12:05:07.603 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:05:07.615 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:05:07.615 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:05:07.615 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:05:08.636 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.3coM6g==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-03 12:05:33.702 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:05:33.702 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:05:33.778 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 12:05:37.603 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:05:37.615 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:05:37.615 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:05:37.615 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:05:37.616 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:06:06.752 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:06:06.752 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone5s-1_PT7153.3coM6g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.3coM6g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 12:06:07.603 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:06:07.614 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:06:07.614 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:06:08.025 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:06:08.409 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.3coM6g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 12:06:37.603 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:06:37.615 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:06:37.615 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:06:37.615 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:06:38.299 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:07:07.603 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:07:07.613 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:07:07.613 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:07:07.614 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
,2015-12-03 12:07:07.764 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,2015-12-03 12:07:32.669 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:07:32.669 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone5s-1_PT7153.3coM6g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.3coM6g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 12:07:37.603 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:08:07.603 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:08:07.613 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:08:07.613 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:08:07.613 ThaliTest[1887:2965777] clien,t: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:08:07.613 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.3coM6g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 12:08:19.032 ThaliTest[1887:2965777] multipeer session: reset timer
2015-12-03 12:08:19.032 ThaliTest[1887:2965777] multipeer session: stop timer
2015-12-03 12:08:19.033 ThaliTest[1887:2965777] multipeer session: start timer: 0xa45a80
2015-12-03 12:08:19.033 ThaliTest[1887:2965777] server session: connect
2015-12-03 12:08:19.033 ThaliTest[1887:2965777] server session: stateChange:0->1 Apple-Iphone5s-1_PT7153
,2015-12-03 12:08:19.035 ThaliTest[1887:2965777] server: accepting invitation Apple-Iphone5s-1_PT7153
,2015-12-03 12:08:21.565 ThaliTest[1887:2966794] server session: connected
2015-12-03 12:08:21.566 ThaliTest[1887:2966794] server session: stateChange:1->2 Apple-Iphone5s-1_PT7153
,2015-12-03 12:08:21.569 ThaliTest[1887:2965777] server relay: connected (to port: 50419)
,2015-12-03T11:08:21.572Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:08:21.852Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-03T11:08:21.866Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-03T11:08:21.880Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 12:08:31.966 ThaliTest[1887:2966810] server session: not connected Apple-Iphone5s-1_PT7153
,2015-12-03 12:08:42.061 ThaliTest[1887:2965777] multipeer session: reset timer
2015-12-03 12:08:42.062 ThaliTest[1887:2965777] multipeer session: stop timer
2015-12-03 12:08:42.062 ThaliTest[1887:2965777] multipeer session: start timer: 0xa45a80
2015-12,-03 12:08:42.062 ThaliTest[1887:2965777] server: disconnecting to refresh session (Apple-Iphone5s-1_PT7153)
2015-12-03 12:08:42.062 ThaliTest[1887:2965777] server session: disconnect
,2015-12-03 12:08:42.062 ThaliTest[1887:2965777] server session: stateChange:2->0 Apple-Iphone5s-1_PT7153
,2015-12-03 12:08:42.064 ThaliTest[1887:2965777] server session: connect
2015-12-03 12:08:42.064 ThaliTest[1887:2965777] server session: stateChange:0->1 Apple-Iphone5s-1_PT7153
,2015-12-03T11:08:42.067Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 12:08:42.068 ThaliTest[1887:2965777] server: accepting invitation Apple-Iphone5s-1_PT7153
,2015-12-03 12:08:44.585 ThaliTest[1887:2966853] server session: connected
2015-12-03 12:08:44.585 ThaliTest[1887:2966853] server session: stateChange:1->2 Apple-Iphone5s-1_PT7153
,2015-12-03 12:08:44.630 ThaliTest[1887:2965777] server relay: connected (to port: 50419)
,2015-12-03T11:08:44.637Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:08:44.676Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-03T11:08:44.689Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 12:08:54.695 ThaliTest[1887:2966864] server session: not connected Apple-Iphone5s-1_PT7153
,2015-12-03 12:09:05.126 ThaliTest[1887:2965777] multipeer session: reset timer
2015-12-03 12:09:05.126 ThaliTest[1887:2965777] multipeer session: stop timer
2015-12-03 12:09:05.126 ThaliTest[1887:2965777] multipeer session: start timer: 0xa45a80
2015-12,-03 12:09:05.126 ThaliTest[1887:2965777] server: disconnecting to refresh session (Apple-Iphone5s-1_PT7153)
2015-12-03 12:09:05.126 ThaliTest[1887:2965777] server session: disconnect
2015-12-03 12:09:05.127 ThaliTest[1887:2965777] server session: stateChange:2->0 Apple-Iphone5s-1_PT7153
,2015-12-03 12:09:05.128 ThaliTest[1887:2965777] server session: connect
2015-12-03 12:09:05.128 ThaliTest[1887:2965777] server session: stateChange:0->1 Apple-Iphone5s-1_PT7153
2015-12-03T11:09:05.129Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 12:09:05.132 ThaliTest[1887:2965777] server: accepting invitation Apple-Iphone5s-1_PT7153
,2015-12-03 12:09:07.692 ThaliTest[1887:2966911] server session: connected
2015-12-03 12:09:07.693 ThaliTest[1887:2966911] server session: stateChange:1->2 Apple-Iphone5s-1_PT7153
,2015-12-03 12:09:07.747 ThaliTest[1887:2965777] server relay: connected (to port: 50419)
,2015-12-03T11:09:07.752Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:09:07.814Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 12:09:18.094 ThaliTest[1887:2966911] server session: not connected Apple-Iphone5s-1_PT7153
,2015-12-03 12:09:20.768 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:09:20.768 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:09:28.097 ThaliTest[1887:2965777] multipeer session: reset timer
2015-12-03 12:09:28.097 ThaliTest[1887:2965777] multipeer session: stop timer
2015-12-03 12:09:28.097 ThaliTest[1887:2965777] multipeer session: start timer: 0xa45a80
2015-12,-03 12:09:28.097 ThaliTest[1887:2965777] server: disconnecting to refresh session (Apple-Iphone5s-1_PT7153)
2015-12-03 12:09:28.097 ThaliTest[1887:2965777] server session: disconnect
2015-12-03 12:09:28.097 ThaliTest[1887:2965777] server session: stateChange:2->0 Apple-Iphone5s-1_PT7153
,2015-12-03 12:09:28.098 ThaliTest[1887:2965777] server session: connect
2015-12-03 12:09:28.099 ThaliTest[1887:2965777] server session: stateChange:0->1 Apple-Iphone5s-1_PT7153
,2015-12-03 12:09:28.102 ThaliTest[1887:2965777] server: accepting invitation Apple-Iphone5s-1_PT7153
,2015-12-03T11:09:28.104Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 12:09:29.753 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 12:09:30.794 ThaliTest[1887:2966958] server session: connected
2015-12-03 12:09:30.794 ThaliTest[1887:2966958] server session: stateChange:1->2 Apple-Iphone5s-1_PT7153
,2015-12-03 12:09:30.797 ThaliTest[1887:2965777] server relay: connected (to port: 50419)
,2015-12-03T11:09:30.800Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:09:30.873Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 12:09:41.158 ThaliTest[1887:2966958] server session: not connected Apple-Iphone5s-1_PT7153
,2015-12-03 12:09:51.575 ThaliTest[1887:2965777] multipeer session: reset timer
,2015-12-03 12:09:51.575 ThaliTest[1887:2965777] multipeer session: stop timer
2015-12-03 12:09:51.575 ThaliTest[1887:2965777] multipeer session: start timer: 0xa45a80
2015-12-03 12:09:51.575 ThaliTest[1887:2965777] server: disconnecting to refresh sessio,n (Apple-Iphone5s-1_PT7153)
2015-12-03 12:09:51.575 ThaliTest[1887:2965777] server session: disconnect
2015-12-03 12:09:51.575 ThaliTest[1887:2965777] server session: stateChange:2->0 Apple-Iphone5s-1_PT7153
,2015-12-03T11:09:51.578Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 12:09:51.629 ThaliTest[1887:2965777] server session: connect
2015-12-03 12:09:51.629 ThaliTest[1887:2965777] server session: stateChange:0->1 Apple-Iphone5s-1_PT7153
2015-12-03 12:09:51.631 ThaliTest[1887:2965777] server: accepting invitation Apple-Iphone5s-1_PT7153
,2015-12-03 12:09:53.946 ThaliTest[1887:2967024] server session: connected
,2015-12-03 12:09:53.947 ThaliTest[1887:2967024] server session: stateChange:1->2 Apple-Iphone5s-1_PT7153
,2015-12-03 12:09:53.949 ThaliTest[1887:2965777] server relay: connected (to port: 50419)
,2015-12-03T11:09:53.953Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:09:54.051Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 12:09:59.117 ThaliTest[1887:2965777] multipeer session: reset timer
2015-12-03 12:09:59.117 ThaliTest[1887:2965777] multipeer session: stop timer
,2015-12-03 12:09:59.117 ThaliTest[1887:2965777] multipeer session: start timer: 0xa45a80
2015-12-03 12:09:59.118 ThaliTest[1887:2965777] server session: connect
2015-12-03 12:09:59.118 ThaliTest[1887:2965777] server session: stateChange:0->1 Apple-Iphone6-1_PT8234
,2015-12-03 12:09:59.120 ThaliTest[1887:2965777] server: accepting invitation Apple-Iphone6-1_PT8234
,2015-12-03 12:10:01.689 ThaliTest[1887:2967024] server session: connected
2015-12-03 12:10:01.689 ThaliTest[1887:2967024] server session: stateChange:1->2 Apple-Iphone6-1_PT8234
,2015-12-03 12:10:01.692 ThaliTest[1887:2965777] server relay: connected (to port: 50419)
,2015-12-03T11:10:01.704Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T11:10:01.962Z SendDataTCPServer.js: TCP/IP server has received 65558 bytes of data
,2015-12-03T11:10:01.977Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 12:10:01.995 ThaliTest[1887:2967025] server session: not connected Apple-Iphone6-1_PT8234
,2015-12-03 12:10:04.220 ThaliTest[1887:2967025] server session: not connected Apple-Iphone5s-1_PT7153
,2015-12-03 12:10:24.293 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone5s-1_PT7153.3coM6g==
2015-12-03 12:10:24.294 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone5s-1_PT7153.3coM6g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.3coM6g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 12:10:29.118 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:10:29.127 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,2015-12-03 12:10:29.435 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:10:31.096 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:10:55.644 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:10:55.644 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:10:59.119 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:10:59.128 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:10:59.128 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:10:59.459 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 12:11:29.119 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:11:29.130 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:11:29.130 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:11:29.130 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,CoordinatorConnector-debug: disconnect:transport close
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:11:59.119 ThaliTest[1887:2965777] multipeer session: restart
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:12:29.118 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:12:29.126 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:12:29.127 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:12:30.551 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:12:36.205 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:12:36.205 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:12:36.229 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:12:42.572 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:12:42.573 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:12:47.431 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:12:59.119 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:12:59.131 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:12:59.131 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:12:59.131 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:13:08.351 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:13:08.351 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:13:09.776 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:13:25.557 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:13:25.557 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:13:29.119 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:13:29.129 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:13:29.129 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:13:30.425 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:13:51.762 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone5s-1_PT7153.jAFxCw==
2015-12-03 12:13:51.762 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:13:59.118 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:13:59.128 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:13:59.128 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,2015-12-03 12:14:00.130 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:14:06.443 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:14:06.443 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:14:08.484 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 12:14:12.728 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:14:12.728 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:14:29.118 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:14:29.126 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,2015-12-03 12:14:29.578 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:14:30.048 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:14:51.421 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone5s-1_PT7153.jAFxCw==
,2015-12-03 12:14:51.421 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone5s-1_PT7153.jAFxCw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7153.jAFxCw==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:14:59.118 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:14:59.127 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:14:59.589 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:15:29.118 ThaliTest[1887:2965777] multipeer session: restart
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:15:59.119 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:15:59.127 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,2015-12-03 12:15:59.294 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:16:29.118 ThaliTest[1887:2965777] multipeer session: restart
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:16:59.118 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:16:59.127 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:16:59.127 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:17:08.852 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:17:08.852 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:17:09.455 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:17:12.704 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:17:12.704 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:17:14.655 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:17:29.119 ThaliTest[1887:2965777] multipeer session: restart
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:17:59.119 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:17:59.127 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
2015-12-03 12:17:59.127 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:18:06.414 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:18:06.414 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 12:18:06.458 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:18:29.118 ThaliTest[1887:2965777] multipeer session: restart
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:18:59.119 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:18:59.127 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,2015-12-03 12:18:59.536 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:19:12.559 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:19:12.560 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:19:18.794 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:19:29.119 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:19:29.126 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,2015-12-03 12:19:29.127 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:19:42.571 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:19:42.572 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:19:59.119 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:19:59.126 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,2015-12-03 12:19:59.364 ThaliTest[1887:2965777] client: found peer: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:20:06.026 ThaliTest[1887:2965777] client: lost peer: Apple-Iphone6-1_PT8234.+Hw2qA==
2015-12-03 12:20:06.026 ThaliTest[1887:2965777] client session: onPeerLost: Apple-Iphone6-1_PT8234.+Hw2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8234.+Hw2qA==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:20:29.119 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:20:29.126 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:20:59.118 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:20:59.125 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:21:29.119 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:21:29.439 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:21:59.118 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:21:59.843 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:22:29.119 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:22:29.126 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:22:59.119 ThaliTest[1887:2965777] multipeer session: restart
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:23:29.119 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:23:29.126 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:23:59.119 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:23:59.385 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:24:29.119 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:24:29.126 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:24:59.119 ThaliTest[1887:2965777] multipeer session: restart
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:25:29.119 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:25:29.530 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:25:59.119 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:25:59.126 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:26:29.118 ThaliTest[1887:2965777] multipeer session: restart
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:26:29.322 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:26:59.119 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:26:59.126 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 12:27:29.119 ThaliTest[1887:2965777] multipeer session: restart
,2015-12-03 12:27:29.126 ThaliTest[1887:2965777] client: found peer: Apple-Iphone5-1_PT2098.P4cq9w==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}

```
