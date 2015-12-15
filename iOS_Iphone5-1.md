#### Test 50650278ee43ca0_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278ee43ca0/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/39F9CFE6-E215-44F4-B18A-256C3B3E9E42/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/39F9CFE6-E215-44F4-B18A-256C3B3E9E42/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278ee43ca0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278ee43ca0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/01328BDD-0746-4816-B898-9FFFBFDF4164/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56273"
,(lldb)     command script import "/tmp/39F9CFE6-E215-44F4-B18A-256C3B3E9E42/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-15 04:59:56.046 ThaliTest[860:1367876] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/76F50969-9EBD-48BD-A07D-245E15501CDD/Library/Cookies/Cookies.binarycookies
,2015-12-15 04:59:56.169 ThaliTest[860:1367876] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-15 04:59:56.170 ThaliTest[860:1367876] Multi-tasking -> Device: YES, App: YES
,2015-12-15 04:59:56.175 ThaliTest[860:1367876] Unlimited access to network resources
,2015-12-15 04:59:56.187 ThaliTest[860:1367876] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-15 05:00:07.078 ThaliTest[860:1367876] Resetting plugins due to page load.
,2015-12-15 05:00:10.655 ThaliTest[860:1367876] Finished load of: file:///var/mobile/Containers/Bundle/Application/01328BDD-0746-4816-B898-9FFFBFDF4164/ThaliTest.app/www/index.html
,2015-12-15 05:00:10.860 ThaliTest[860:1367876] JXcore Cordova plugin initializing
2015-12-15 05:00:10.862 ThaliTest[860:1368179] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-15 05:00:13.304 ThaliTest[860:1367876] THREAD WARNING: ['JXcore'] took '153.827881' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-15 05:06:32.031 ThaliTest[860:1368179] jxcore: startBroadcasting
,2015-12-15 05:06:32.043 ThaliTest[860:1368179] server: starting Apple-Iphone5-1_PT2557.cLGdMA==
2015-12-15 05:06:32.044 ThaliTest[860:1368179] multipeer session: start timer: 0x1b462250
2015-12-15 05:06:32.044 ThaliTest[860:1368179] THEMultipeerSession initialized peer Apple-Iphone5-1_PT2557
2015-12-15 05:06:32.045 ThaliTest[860:1368179] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-15 05:06:33.053 ThaliTest[860:1367876] client: found peer: Apple-IpadAir2-1_PT1010.7Cf2mQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1010.7Cf2mQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-IpadAir2-1_PT1010.7Cf2mQ==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,2015-12-15 05:06:33.118 ThaliTest[860:1367876] client: found peer: Apple-Iphone6-1_PT9306.6VQMVQ==
,2015-12-15 05:06:33.125 ThaliTest[860:1367876] client: found peer: Apple-Iphone5s-1_PT6308.pQEQSw==
,teardown
,testFindPeers stopped
,2015-12-15 05:06:34.715 ThaliTest[860:1368179] jxcore: stopBroadcasting
2015-12-15 05:06:34.715 ThaliTest[860:1368179] THEMultipeerSession stopping peer
2015-12-15 05:06:34.715 ThaliTest[860:1368179] multipeer session: stop timer
2015-12-15 05:06:34.716 ThaliTest[860:1368179] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 60089
,2015-12-15 05:06:34.784 ThaliTest[860:1368179] jxcore: startBroadcasting
,2015-12-15 05:06:34.788 ThaliTest[860:1368179] server: starting Apple-Iphone5-1_PT2557.fyiFnQ==
,2015-12-15 05:06:34.790 ThaliTest[860:1368179] multipeer session: start timer: 0x1b3a13d0
,2015-12-15 05:06:34.797 ThaliTest[860:1368179] THEMultipeerSession initialized peer Apple-Iphone5-1_PT2557
,2015-12-15 05:06:34.799 ThaliTest[860:1368179] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2015-12-15T04:06:34.803Z SendDataTCPServer.js: TCP/IP server is bound to port: 60089
,2015-12-15 05:06:35.745 ThaliTest[860:1367876] client: found peer: Apple-Iphone5s-1_PT6308.pQEQSw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6308.pQEQSw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: t,rue
2015-12-15 05:06:35.748 ThaliTest[860:1367876] client: found peer: Apple-Iphone6-1_PT9306.6VQMVQ==
2015-12-15 05:06:35.749 ThaliTest[860:1367876] client: found peer: Apple-Iphone5-1_PT2557.cLGdMA==
startWithNextDevice
device[1]: Apple-Iphone5s-1_PT,6308.pQEQSw==
2015-12-15T04:06:35.751Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15T04:06:35.751Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15T04:06:35.752Z Send,DataConnector.js: do connect now
2015-12-15 05:06:35.752 ThaliTest[860:1368179] jxcore: connect Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:35.752 ThaliTest[860:1368179] client session: connect
2015-12-15 05:06:35.753 ThaliTest[860:1368179] client, session: stateChange:0->1 Apple-Iphone5s-1_PT6308.pQEQSw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9306.6VQMVQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2557.cLGdMA==","peerName":"(null)",,"peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 05:06:35.844 ThaliTest[860:1367876] client: lost peer: Apple-Iphone5-1_PT2557.cLGdMA==
2015-12-15 05:06:35.844 ThaliTest[860:1367876] client session: onPeerLost: Apple-Iphone5-1_PT2557.cLGdMA==
2015-12-15 05:06:35.845 ThaliTest[860:1367876] cl,ient: found peer: Apple-Iphone6-1_PT9306.EdsImg==
2015-12-15 05:06:35.845 ThaliTest[860:1367876] client: found peer: Apple-Iphone5s-1_PT6308.z27btQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2557.cLGdMA==","peerName":"(null)","peerAv,ailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9306.EdsImg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifie,r":"Apple-Iphone5s-1_PT6308.z27btQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-15 05:06:36.745 ThaliTest[860:1367876] client: lost peer: Apple-Iphone6-1_PT9306.6VQMVQ==
2015-12-15 05:06:36.745 ThaliTest[860:1367876] client session: onPeerLost: Apple-Iphone6-1_PT9306.6VQMVQ==
2015-12-15 05:06:36.746 ThaliTest[860:1367876] cl,ient: lost peer: Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:36.746 ThaliTest[860:1367876] client session: onPeerLost: Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:36.746 ThaliTest[860:1367876] client session: onLinkFailure: Apple-Iphone5s-1_P,T6308.pQEQSw==
2015-12-15 05:06:36.746 ThaliTest[860:1367876] client session: disconnect
2015-12-15 05:06:36.747 ThaliTest[860:1367876] client session: stateChange:1->0 Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:36.747 ThaliTest[860:1367876] clie,nt session: fireConnectCallback: Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:36.747 ThaliTest[860:1367876] jxcore: connect: fail: Peer disconnected
2015-12-15 05:06:36.748 ThaliTest[860:1367876] client: found peer: Apple-IpadAir2-1_PT1010.g7hIzw==,
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9306.6VQMVQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
2015-12-15T04:06:36.750Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnect,ed
2015-12-15T04:06:36.751Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-15T04:06:36.751Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6308.pQEQSw==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1010.g7hIzw==","peerName":"(null)","peerAvailable":true}]
Found peer ,: (null), Available: true
,2015-12-15T04:06:41.758Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15T04:06:41.759Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15 05:06:46.764 ThaliTest[860:1368179] jxcore: disconnect
2015-12-15 05:06:46.765 ThaliTest[860:1368179] jxcore: disconnect: fail
2015-12-15T04:06:46.765Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6308.pQEQSw,==
2015-12-15T04:06:46.766Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT6308.pQEQSw== with availability status: true
2015-12-15T04:06:46.766Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15T04:06:46.766Z SendDataConnector.js: do connect now
,2015-12-15 05:06:46.768 ThaliTest[860:1368179] jxcore: connect Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:46.768 ThaliTest[860:1368179] client: connect: unreachable Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:46.768 ThaliTest[860:1368179] jx,core: connect: fail: Peer unreachable
,2015-12-15T04:06:46.769Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:06:46.769Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-15T04:06:46.769Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:06:51.772Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15T04:06:51.773Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15 05:06:56.775 ThaliTest[860:1368179] jxcore: disconnect
2015-12-15 05:06:56.776 ThaliTest[860:1368179] jxcore: disconnect: fail
2015-12-15T04:06:56.777Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6308.pQEQSw,==
2015-12-15T04:06:56.777Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT6308.pQEQSw== with availability status: true
2015-12-15T04:06:56.778Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15T04:06:56.778Z SendDataConnector.js: do connect now
,2015-12-15 05:06:56.779 ThaliTest[860:1368179] jxcore: connect Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:56.779 ThaliTest[860:1368179] client: connect: unreachable Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:56.779 ThaliTest[860:1368179] jxcore: connect: fail: Peer unreachable
,2015-12-15T04:06:56.780Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:06:56.780Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-15T04:06:56.780Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:07:01.786Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15T04:07:01.786Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15 05:07:04.798 ThaliTest[860:1367876] multipeer session: restart
,2015-12-15 05:07:04.831 ThaliTest[860:1367876] client: found peer: Apple-Iphone6-1_PT9306.EdsImg==
2015-12-15 05:07:04.831 ThaliTest[860:1367876] client: found peer: Apple-Iphone5s-1_PT6308.z27btQ==
2015-12-15 05:07:04.832 ThaliTest[860:1367876] client: ,found peer: Apple-IpadAir2-1_PT1010.g7hIzw==
,2015-12-15 05:07:06.793 ThaliTest[860:1368179] jxcore: disconnect
2015-12-15 05:07:06.794 ThaliTest[860:1368179] jxcore: disconnect: fail
2015-12-15T04:07:06.795Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6308.pQEQSw,==
2015-12-15T04:07:06.795Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT6308.pQEQSw== with availability status: true
2015-12-15T04:07:06.796Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15T04:07:06.796Z SendDataConnector.js: do connect now
,2015-12-15 05:07:06.797 ThaliTest[860:1368179] jxcore: connect Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:07:06.797 ThaliTest[860:1368179] client: connect: unreachable Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:07:06.797 ThaliTest[860:1368179] jxcore: connect: fail: Peer unreachable
,2015-12-15T04:07:06.798Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:07:06.798Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T04:07:06.798Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:07:11.801Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15T04:07:11.802Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15 05:07:16.804 ThaliTest[860:1368179] jxcore: disconnect
2015-12-15 05:07:16.804 ThaliTest[860:1368179] jxcore: disconnect: fail
2015-12-15T04:07:16.805Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6308.pQEQSw,==
2015-12-15T04:07:16.805Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT6308.pQEQSw== with availability status: true
2015-12-15T04:07:16.805Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15T04:07:16.806Z SendDataConnector.js: do connect now
,2015-12-15 05:07:16.807 ThaliTest[860:1368179] jxcore: connect Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:07:16.807 ThaliTest[860:1368179] client: connect: unreachable Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:07:16.807 ThaliTest[860:1368179] jx,core: connect: fail: Peer unreachable
2015-12-15T04:07:16.808Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:07:16.808Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
2015-12-15T04:07,:16.809Z SendDataConnector.js: CLIENT Stop now
,2015-12-15 05:07:16.810 ThaliTest[860:1368179] jxcore: disconnect
2015-12-15 05:07:16.810 ThaliTest[860:1368179] jxcore: disconnect: fail
2015-12-15T04:07:16.810Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6308.pQEQSw==
---- round done--------
startWithNextDevice
,device[2]: Apple-Iphone6-1_PT9306.EdsImg==
2015-12-15T04:07:16.813Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT9306.EdsImg==
2015-12-15T04:07:16.813Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9306.EdsImg==
,2015-12-15T04:07:16.813Z SendDataConnector.js: do connect now
,2015-12-15 05:07:16.814 ThaliTest[860:1368179] jxcore: connect Apple-Iphone6-1_PT9306.EdsImg==
2015-12-15 05:07:16.814 ThaliTest[860:1368179] client session: connect
,2015-12-15 05:07:16.814 ThaliTest[860:1368179] client session: stateChange:0->1 Apple-Iphone6-1_PT9306.EdsImg==
,2015-12-15 05:07:19.778 ThaliTest[860:1368988] client session: connected
2015-12-15 05:07:19.778 ThaliTest[860:1368988] client session: stateChange:1->2 Apple-Iphone6-1_PT9306.EdsImg==
,2015-12-15 05:07:19.835 ThaliTest[860:1369038] client session: fireConnectCallback: Apple-Iphone6-1_PT9306.EdsImg==
2015-12-15 05:07:19.836 ThaliTest[860:1369038] jxcore: connect: success
2015-12-15T04:07:19.836Z SendDataConnector.js: CLIENT connected to 60093, error: null
2015-12-15T04:07:19.836Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 05:07:19.839 ThaliTest[860:1367876] client: relay established
2015-12-15 05:07:19.839 ThaliTest[860:1367876] client: new accepted socket: 0x1b47cb00
,2015-12-15T04:07:19.855Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T04:07:20.373Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-15T04:07:20.387Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-15T04:07:20.499Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T04:07:20.499Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-15T04:07:20.502Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T04:07:20.502Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:07:20.503 ThaliTest[860:1368179] jxcore: disconnect
2015-12-15 05:07:20.504 ThaliTest[860:1368179] client session: disconnectFromPeer: Apple-Iphone6-1_PT9306.EdsImg==
2015-12-15 05:07:20.504 ThaliTest[860:1368179] client session: disconnect
2015-12-15 05:07:20.504 ThaliTest[860:1368179] client session: stateChange:2->0 Apple-Iphone6-1_PT9306.EdsImg==
,2015-12-15 05:07:20.513 ThaliTest[860:1368179] jxcore: disconnect: success
2015-12-15T04:07:20.514Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9306.EdsImg==
---- round done--------
startWithNextDevice
device[3]: Appl,e-Iphone5s-1_PT6308.z27btQ==
2015-12-15T04:07:20.517Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT6308.z27btQ==
2015-12-15T04:07:20.517Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6308.z27btQ==
2015-12-15T04:,07:20.518Z SendDataConnector.js: do connect now
2015-12-15 05:07:20.518 ThaliTest[860:1368179] jxcore: connect Apple-Iphone5s-1_PT6308.z27btQ==
2015-12-15 05:07:20.518 ThaliTest[860:1368179] client session: connect
2015-12-15 05:07:20.519 ThaliTest[860:1368179] client session: stateChange:0->1 Apple-Iphone5s-1_PT6308.z27btQ==
,2015-12-15 05:07:23.636 ThaliTest[860:1367876] multipeer session: reset timer
,2015-12-15 05:07:23.636 ThaliTest[860:1367876] multipeer session: stop timer
,2015-12-15 05:07:23.637 ThaliTest[860:1367876] multipeer session: start timer: 0x1b3a13d0
,2015-12-15 05:07:23.638 ThaliTest[860:1367876] server session: connect
,2015-12-15 05:07:23.639 ThaliTest[860:1367876] server session: stateChange:0->1 Apple-Iphone6-1_PT9306
,2015-12-15 05:07:23.659 ThaliTest[860:1367876] server: accepting invitation Apple-Iphone6-1_PT9306
,2015-12-15 05:07:23.662 ThaliTest[860:1368977] client session: connected
,2015-12-15 05:07:23.663 ThaliTest[860:1368977] client session: stateChange:1->2 Apple-Iphone5s-1_PT6308.z27btQ==
,2015-12-15 05:07:23.677 ThaliTest[860:1368977] client session: fireConnectCallback: Apple-Iphone5s-1_PT6308.z27btQ==
,2015-12-15 05:07:23.678 ThaliTest[860:1368977] jxcore: connect: success
2015-12-15T04:07:23.680Z SendDataConnector.js: CLIENT connected to 60096, error: null
2015-12-15T04:07:23.681Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 05:07:23.685 ThaliTest[860:1367876] client: relay established
,2015-12-15 05:07:23.688 ThaliTest[860:1367876] client: new accepted socket: 0x1b3be430
,2015-12-15T04:07:23.700Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15 05:07:23.961 ThaliTest[860:1367876] multipeer session: reset timer
,2015-12-15 05:07:23.961 ThaliTest[860:1367876] multipeer session: stop timer
2015-12-15 05:07:23.961 ThaliTest[860:1367876] multipeer session: start timer: 0x1b3a13d0
2015-12-15 05:07:23.961 ThaliTest[860:1367876] server session: connect
,2015-12-15 05:07:23.962 ThaliTest[860:1367876] server session: stateChange:0->1 Apple-Iphone5s-1_PT6308
,2015-12-15 05:07:23.973 ThaliTest[860:1367876] server: accepting invitation Apple-Iphone5s-1_PT6308
,2015-12-15T04:07:24.435Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-15T04:07:24.523Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T04:07:24.523Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-15T04:07:24.525Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T04:07:24.525Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:07:24.526 ThaliTest[860:1368179] jxcore: disconnect
2015-12-15 05:07:24.527 ThaliTest[860:1368179] client session: disconnectFromPeer: Apple-Iphone5s-1_PT6308.z27btQ==
2015-12-15 05:07:24.527 ThaliTest[860:1368179] client session: disconnect
2015-12-15 05:07:24.527 ThaliTest[860:1368179] client session: stateChange:2->0 Apple-Iphone5s-1_PT6308.z27btQ==
,2015-12-15 05:07:24.538 ThaliTest[860:1368179] jxcore: disconnect: success
2015-12-15T04:07:24.538Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6308.z27btQ==
---- round done--------
startWithNextDevice
device[4]: App,le-IpadAir2-1_PT1010.g7hIzw==
2015-12-15T04:07:24.539Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1010.g7hIzw==
2015-12-15T04:07:24.540Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1010.g7hIzw==
2015-12-15T04,:07:24.540Z SendDataConnector.js: do connect now
2015-12-15 05:07:24.540 ThaliTest[860:1368179] jxcore: connect Apple-IpadAir2-1_PT1010.g7hIzw==
2015-12-15 05:07:24.541 ThaliTest[860:1368179] client session: connect
2015-12-15 05:07:24.541 ThaliTest[860,:1368179] client session: stateChange:0->1 Apple-IpadAir2-1_PT1010.g7hIzw==
,2015-12-15 05:07:24.564 ThaliTest[860:1367876] multipeer session: reset timer
,2015-12-15 05:07:24.564 ThaliTest[860:1367876] multipeer session: stop timer
2015-12-15 05:07:24.564 ThaliTest[860:1367876] multipeer session: start timer: 0x1b3a13d0
2015-12-15 05:07:24.565 ThaliTest[860:1367876] server session: connect
2015-12-15 05:0,7:24.565 ThaliTest[860:1367876] server session: stateChange:0->1 Apple-IpadAir2-1_PT1010
,2015-12-15 05:07:24.574 ThaliTest[860:1367876] server: accepting invitation Apple-IpadAir2-1_PT1010
,2015-12-15 05:07:26.361 ThaliTest[860:1368976] server session: connected
,2015-12-15 05:07:26.361 ThaliTest[860:1368976] server session: stateChange:1->2 Apple-Iphone6-1_PT9306
,2015-12-15 05:07:26.388 ThaliTest[860:1367876] server relay: connected (to port: 60089)
,2015-12-15T04:07:26.397Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T04:07:26.688Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 05:07:26.784 ThaliTest[860:1368976] server session: connected
,2015-12-15 05:07:26.784 ThaliTest[860:1368976] server session: stateChange:1->2 Apple-Iphone5s-1_PT6308
,2015-12-15 05:07:26.788 ThaliTest[860:1367876] server relay: connected (to port: 60089)
,2015-12-15T04:07:26.794Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T04:07:27.185Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-15T04:07:27.201Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-15T04:07:27.216Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
2015-12-15T04:07:27.230Z SendDataTCPServer.js: TCP/IP server has received 91838 bytes of data
,2015-12-15T04:07:27.246Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 05:07:27.254 ThaliTest[860:1368977] server session: connected
,2015-12-15 05:07:27.254 ThaliTest[860:1368977] server session: stateChange:1->2 Apple-IpadAir2-1_PT1010
,2015-12-15 05:07:27.266 ThaliTest[860:1367876] server relay: connected (to port: 60089)
,2015-12-15T04:07:27.273Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15 05:07:27.294 ThaliTest[860:1368976] client session: connected
2015-12-15 05:07:27.294 ThaliTest[860:1368976] client session: stateChange:1->2 Apple-IpadAir2-1_PT1010.g7hIzw==
,2015-12-15 05:07:27.296 ThaliTest[860:1368976] client session: fireConnectCallback: Apple-IpadAir2-1_PT1010.g7hIzw==
,2015-12-15 05:07:27.299 ThaliTest[860:1368976] jxcore: connect: success
,2015-12-15T04:07:27.300Z SendDataConnector.js: CLIENT connected to 60102, error: null
2015-12-15T04:07:27.302Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 05:07:27.305 ThaliTest[860:1367876] client: relay established
,2015-12-15 05:07:27.307 ThaliTest[860:1367876] client: new accepted socket: 0x1b3bb880
,2015-12-15 05:07:27.312 ThaliTest[860:1368976] server session: not connected Apple-Iphone5s-1_PT6308
,2015-12-15T04:07:27.317Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T04:07:27.836Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15T04:07:27.866Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-15T04:07:27.904Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-15 05:07:27.935 ThaliTest[860:1368976] server session: not connected Apple-IpadAir2-1_PT1010
,2015-12-15T04:07:27.956Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-15T04:07:27.969Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T04:07:27.970Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-15T04:07:27.972Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T04:07:27.972Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:07:27.973 ThaliTest[860:1368179] jxcore: disconnect
2015-12-15 05:07:27.973 ThaliTest[860:1368179] client session: disconnectFromPeer: Apple-IpadAir2-1_PT1010.g7hIzw==
2015-12-15 05:07:27.974 ThaliTest[860:1368179] client session: disconnect
2015-12-15 05:07:27.974 ThaliTest[860:1368179] client session: stateChange:2->0 Apple-IpadAir2-1_PT1010.g7hIzw==
,2015-12-15 05:07:27.983 ThaliTest[860:1368179] jxcore: disconnect: success
2015-12-15T04:07:27.983Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1010.g7hIzw==
---- round done--------
startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2015-12-15T04:07:27.999Z SendDataConnector.js: CLIENT Stop now
2015-12-15T04:07:28.000Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
,2015-12-15 05:07:29.047 ThaliTest[860:1368179] jxcore: stopBroadcasting
2015-12-15 05:07:29.047 ThaliTest[860:1368179] THEMultipeerSession stopping peer
2015-12-15 05:07:29.047 ThaliTest[860:1368179] multipeer session: stop timer
2015-12-15 05:07:29.048, ThaliTest[860:1368179] server session: disconnect
2015-12-15 05:07:29.048 ThaliTest[860:1368179] server session: stateChange:2->0 Apple-IpadAir2-1_PT1010
,2015-12-15 05:07:29.054 ThaliTest[860:1368179] server session: disconnect
2015-12-15 05:07:29.054 ThaliTest[860:1368179] server session: stateChange:2->0 Apple-Iphone6-1_PT9306
,2015-12-15 05:07:29.309 ThaliTest[860:1368179] server session: disconnect
2015-12-15 05:07:29.309 ThaliTest[860:1368179] server session: stateChange:2->0 Apple-Iphone5s-1_PT6308
,2015-12-15 05:07:29.312 ThaliTest[860:1368179] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-15T04:07:29.327Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-15T04:07:29.329Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-15T04:07:29.330Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-15T04:07:29.330Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
