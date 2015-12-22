#### Test 543122982543be8_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/543122982543be8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/66E37768-E5BA-4F40-BBA6-67660EBEF1D6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/66E37768-E5BA-4F40-BBA6-67660EBEF1D6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/543122982543be8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/543122982543be8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/ECEE1C6A-77F1-4B97-9283-4AFCD6F53612/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62006"
,(lldb)     command script import "/tmp/66E37768-E5BA-4F40-BBA6-67660EBEF1D6/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-22 01:49:34.963 ThaliTest[711:818912] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/76AAAE00-08A0-46DE-9901-7CA65D5D3257/Library/Cookies/Cookies.binarycookies
,2015-12-22 01:49:35.361 ThaliTest[711:818912] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-22 01:49:35.362 ThaliTest[711:818912] Multi-tasking -> Device: YES, App: YES
,2015-12-22 01:49:35.371 ThaliTest[711:818912] Unlimited access to network resources
,2015-12-22 01:49:35.382 ThaliTest[711:818912] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-22 01:49:44.819 ThaliTest[711:818912] Resetting plugins due to page load.
,2015-12-22 01:49:48.228 ThaliTest[711:818912] Finished load of: file:///var/mobile/Containers/Bundle/Application/ECEE1C6A-77F1-4B97-9283-4AFCD6F53612/ThaliTest.app/www/index.html
,2015-12-22 01:49:48.412 ThaliTest[711:818912] JXcore Cordova plugin initializing
,2015-12-22 01:49:48.413 ThaliTest[711:819121] JXcore instance initializing
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
,found test : ./testSendData2.js
,2015-12-22 01:49:49.516 ThaliTest[711:818912] THREAD WARNING: ['JXcore'] took '83.375000' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-22 01:54:50.084 ThaliTest[711:819121] jxcore: startBroadcasting
,2015-12-22 01:54:50.102 ThaliTest[711:819121] server: starting Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:54:50.103 ThaliTest[711:819121] multipeer session: start timer: 0x15c55ad0
2015-12-22 01:54:50.104 ThaliTest[711:819121] THEMultipeerSession init,ialized peer Apple-Iphone6-1_PT4682
2015-12-22 01:54:50.105 ThaliTest[711:819121] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-22 01:54:51.140 ThaliTest[711:818912] client: found peer: Apple-IpadAir2-1_PT8764.Y1JJAA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8764.Y1JJAA==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1_PT8764.Y1JJAA==, peerAvailable: true
,weAreDoneNow
done, now sending data to server
,2015-12-22 01:54:51.195 ThaliTest[711:818912] client: found peer: Apple-Iphone5-1_PT5195.3svwkg==
,teardown
,testFindPeers stopped
,2015-12-22 01:54:52.517 ThaliTest[711:819121] jxcore: stopBroadcasting
2015-12-22 01:54:52.518 ThaliTest[711:819121] THEMultipeerSession stopping peer
2015-12-22 01:54:52.518 ThaliTest[711:819121] multipeer session: stop timer
2015-12-22 01:54:52.519 Th,aliTest[711:819121] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 55788
2015-12-22 01:54:52.583 ThaliTest[711:819121] jxcore: startBroadcasting
,2015-12-22 01:54:52.591 ThaliTest[711:819121] server: starting Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22 01:54:52.592 ThaliTest[711:819121] multipeer session: start timer: 0x15bd3f20
2015-12-22 01:54:52.593 ThaliTest[711:819121] THEMultipeerSession initialized peer Apple-Iphone6-1_PT4682
2015-12-22 01:54:52.594 ThaliTest[711:819121] jxcore: start,Broadcasting: success
StartBroadcasting started ok
null
2015-12-22T00:54:52.598Z SendDataTCPServer.js: TCP/IP server is bound to port: 55788
,2015-12-22 01:54:52.614 ThaliTest[711:818912] client: found peer: Apple-Iphone5-1_PT5195.3svwkg==
2015-12-22 01:54:52.614 ThaliTest[711:818912] client: found peer: Apple-IpadAir2-1_PT8764.Y1JJAA==
2015-12-22 01:54:52.615 ThaliTest[711:818912] client: fou,nd peer: Apple-Iphone6-1_PT4682.4oKZxQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5195.3svwkg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-Iphone5-1_PT5195.3svwkg==
2015-12-22T00:54:52.620Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT5195.3svwkg==
2015-12-22T00:54:52.620Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5195.3svwkg==
2015-12-22T00:54:52.621Z SendDataConnector.js: do connect now
,2015-12-22 01:54:52.622 ThaliTest[711:819121] jxcore: connect Apple-Iphone5-1_PT5195.3svwkg==
2015-12-22 01:54:52.622 ThaliTest[711:819121] client session: connect
2015-12-22 01:54:52.622 ThaliTest[711:819121] client session: stateChange:0->1 Apple-Iphon,e5-1_PT5195.3svwkg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8764.Y1JJAA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4682.4oKZxQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-22 01:54:53.787 ThaliTest[711:818912] client: lost peer: Apple-Iphone5-1_PT5195.3svwkg==
2015-12-22 01:54:53.787 ThaliTest[711:818912] client session: onPeerLost: Apple-Iphone5-1_PT5195.3svwkg==
2015-12-22 01:54:53.787 ThaliTest[711:818912] clien,t session: onLinkFailure: Apple-Iphone5-1_PT5195.3svwkg==
2015-12-22 01:54:53.788 ThaliTest[711:818912] client session: disconnect
2015-12-22 01:54:53.788 ThaliTest[711:818912] client session: stateChange:1->0 Apple-Iphone5-1_PT5195.3svwkg==
,2015-12-22 01:54:53.790 ThaliTest[711:818912] client session: fireConnectCallback: Apple-Iphone5-1_PT5195.3svwkg==
,2015-12-22 01:54:53.790 ThaliTest[711:818912] jxcore: connect: fail: Peer disconnected
2015-12-22 01:54:53.791 ThaliTest[711:818912] client: lost peer: Apple-IpadAir2-1_PT8764.Y1JJAA==
2015-12-22 01:54:53.792 ThaliTest[711:818912] client session: onPeerL,ost: Apple-IpadAir2-1_PT8764.Y1JJAA==
2015-12-22 01:54:53.792 ThaliTest[711:818912] client: found peer: Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22T00:54:53.793Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-22T00:54:53.7,94Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-22T00:54:53.795Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5195.3svwkg==","peerName":"(null)","peerAvailable":fa,lse}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8764.Y1JJAA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9511.iUx4mA==","peerName,":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-22 01:54:53.901 ThaliTest[711:818912] client: found peer: Apple-IpadAir2-1_PT8764.Ptw77g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8764.Ptw77g==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-22 01:54:54.502 ThaliTest[711:818912] client: lost peer: Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:54:54.502 ThaliTest[711:818912] client session: onPeerLost: Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:54:54.502 ThaliTest[711:818912] clien,t: found peer: Apple-Iphone5-1_PT5195.x5+2Tg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4682.4oKZxQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone5-1_PT5195.x5+2Tg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-22T00:54:58.799Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT5195.3svwkg==
,2015-12-22T00:54:58.799Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT5195.3svwkg==
,2015-12-22 01:55:03.804 ThaliTest[711:819121] jxcore: disconnect
2015-12-22 01:55:03.805 ThaliTest[711:819121] jxcore: disconnect: fail
2015-12-22T00:55:03.805Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5195.3svwkg==
2015-12-22T00:55:03.805Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT5195.3svwkg== with availability status: true
2015-12-22T00:55:03.805Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5195.3svwkg==
2015-12-22T00:55:03.806Z SendDataConnector.js: do connect now
,2015-12-22 01:55:03.806 ThaliTest[711:819121] jxcore: connect Apple-Iphone5-1_PT5195.3svwkg==
2015-12-22 01:55:03.807 ThaliTest[711:819121] client: connect: unreachable Apple-Iphone5-1_PT5195.3svwkg==
2015-12-22 01:55:03.807 ThaliTest[711:819121] jxcore:, connect: fail: Peer unreachable
2015-12-22T00:55:03.807Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-22T00:55:03.807Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-22T00:55:03.807Z SendDataConnector.js: tryAgain afer: 5000 ms.
,appEnteredForeground wasn't registered
,2015-12-22T00:55:08.810Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT5195.3svwkg==
,2015-12-22T00:55:08.811Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT5195.3svwkg==
,2015-12-22 01:55:13.821 ThaliTest[711:819121] jxcore: disconnect
2015-12-22 01:55:13.821 ThaliTest[711:819121] jxcore: disconnect: fail
2015-12-22T00:55:13.822Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5195.3svwkg==,
2015-12-22T00:55:13.822Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT5195.3svwkg== with availability status: true
2015-12-22T00:55:13.823Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5195.3svwkg==
,2015-12-22T00:55:13.823Z SendDataConnector.js: do connect now
2015-12-22 01:55:13.824 ThaliTest[711:819121] jxcore: connect Apple-Iphone5-1_PT5195.3svwkg==
,2015-12-22 01:55:13.825 ThaliTest[711:819121] client: connect: unreachable Apple-Iphone5-1_PT5195.3svwkg==
2015-12-22 01:55:13.825 ThaliTest[711:819121] jxcore: connect: fail: Peer unreachable
2015-12-22T00:55:13.826Z SendDataConnector.js: CLIENT connect,ed to 0, error: Peer unreachable
2015-12-22T00:55:13.826Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-22T00:55:13.826Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-22T00:55:18.837Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT5195.3svwkg==
,2015-12-22T00:55:18.838Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT5195.3svwkg==
,2015-12-22 01:55:22.594 ThaliTest[711:818912] multipeer session: restart
,2015-12-22 01:55:22.638 ThaliTest[711:818912] client: found peer: Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:55:22.639 ThaliTest[711:818912] client: found peer: Apple-Iphone5-1_PT5195.x5+2Tg==
2015-12-22 01:55:22.639 ThaliTest[711:818912] client: fou,nd peer: Apple-IpadAir2-1_PT8764.Ptw77g==
,2015-12-22 01:55:23.849 ThaliTest[711:819121] jxcore: disconnect
2015-12-22 01:55:23.849 ThaliTest[711:819121] jxcore: disconnect: fail
2015-12-22T00:55:23.850Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5195.3svwkg==,
2015-12-22T00:55:23.850Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT5195.3svwkg== with availability status: true
2015-12-22T00:55:23.850Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5195.3svwkg==
,2015-12-22T00:55:23.851Z SendDataConnector.js: do connect now
,2015-12-22 01:55:23.852 ThaliTest[711:819121] jxcore: connect Apple-Iphone5-1_PT5195.3svwkg==
,2015-12-22 01:55:23.853 ThaliTest[711:819121] client: connect: unreachable Apple-Iphone5-1_PT5195.3svwkg==
,2015-12-22 01:55:23.853 ThaliTest[711:819121] jxcore: connect: fail: Peer unreachable
2015-12-22T00:55:23.854Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-22T00:55:23.854Z SendDataConnector.js: CLIENT Can not Connect: Pee,r unreachable
2015-12-22T00:55:23.855Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-22T00:55:28.860Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT5195.3svwkg==
,2015-12-22T00:55:28.861Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT5195.3svwkg==
,2015-12-22 01:55:33.868 ThaliTest[711:819121] jxcore: disconnect
2015-12-22 01:55:33.868 ThaliTest[711:819121] jxcore: disconnect: fail
2015-12-22T00:55:33.869Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5195.3svwkg==,
2015-12-22T00:55:33.869Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT5195.3svwkg== with availability status: true
2015-12-22T00:55:33.869Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5195.3svwkg==
,2015-12-22T00:55:33.870Z SendDataConnector.js: do connect now
2015-12-22 01:55:33.870 ThaliTest[711:819121] jxcore: connect Apple-Iphone5-1_PT5195.3svwkg==
2015-12-22 01:55:33.871 ThaliTest[711:819121] client: connect: unreachable Apple-Iphone5-1_PT5195.,3svwkg==
2015-12-22 01:55:33.871 ThaliTest[711:819121] jxcore: connect: fail: Peer unreachable
2015-12-22T00:55:33.872Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-22T00:55:33.872Z SendDataConnector.js: CLIENT Can not Co,nnect: Peer unreachable
,oneRoundDownNow
,2015-12-22T00:55:33.875Z SendDataConnector.js: CLIENT Stop now
,2015-12-22 01:55:33.876 ThaliTest[711:819121] jxcore: disconnect
2015-12-22 01:55:33.876 ThaliTest[711:819121] jxcore: disconnect: fail
2015-12-22T00:55:33.877Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5195.3svwkg==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5s-1_PT9511.iUx4mA==
,2015-12-22T00:55:33.880Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT9511.iUx4mA==
,2015-12-22T00:55:33.881Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9511.iUx4mA==
,2015-12-22T00:55:33.881Z SendDataConnector.js: do connect now
,2015-12-22 01:55:33.883 ThaliTest[711:819121] jxcore: connect Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:55:33.883 ThaliTest[711:819121] client session: connect
2015-12-22 01:55:33.883 ThaliTest[711:819121] client session: stateChange:0->1 Apple-Ipho,ne5s-1_PT9511.iUx4mA==
,2015-12-22 01:55:52.594 ThaliTest[711:818912] multipeer session: restart
,2015-12-22 01:56:06.884 ThaliTest[711:820121] client session: not connected Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:56:06.885 ThaliTest[711:820121] client session: onLinkFailure: Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:56:06.885 ThaliTest[7,11:820121] client session: disconnect
2015-12-22 01:56:06.885 ThaliTest[711:820121] client session: stateChange:1->0 Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:56:06.886 ThaliTest[711:820121] client session: fireConnectCallback: Apple-Iphone5s-1_PT95,11.iUx4mA==
2015-12-22 01:56:06.886 ThaliTest[711:820121] jxcore: connect: fail: Peer disconnected
2015-12-22T00:56:06.888Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-22T00:56:06.889Z SendDataConnector.js: CLIENT Can n,ot Connect: Peer disconnected
2015-12-22T00:56:06.889Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-22T00:56:11.896Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT9511.iUx4mA==
,2015-12-22T00:56:11.896Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT9511.iUx4mA==
,2015-12-22 01:56:16.909 ThaliTest[711:819121] jxcore: disconnect
2015-12-22 01:56:16.909 ThaliTest[711:819121] jxcore: disconnect: fail
2015-12-22T00:56:16.910Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9511.iUx4mA==,
2015-12-22T00:56:16.910Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT9511.iUx4mA== with availability status: true
2015-12-22T00:56:16.910Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9511.iUx4mA==
20,15-12-22T00:56:16.911Z SendDataConnector.js: do connect now
,2015-12-22 01:56:16.911 ThaliTest[711:819121] jxcore: connect Apple-Iphone5s-1_PT9511.iUx4mA==
,2015-12-22 01:56:16.912 ThaliTest[711:819121] client session: connect
,2015-12-22 01:56:16.913 ThaliTest[711:819121] client session: stateChange:0->1 Apple-Iphone5s-1_PT9511.iUx4mA==
,2015-12-22 01:56:16.924 ThaliTest[711:818912] client: lost peer: Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:56:16.924 ThaliTest[711:818912] client session: onPeerLost: Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:56:16.925 ThaliTest[711:818912] cli,ent session: onLinkFailure: Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:56:16.925 ThaliTest[711:818912] client session: disconnect
2015-12-22 01:56:16.925 ThaliTest[711:818912] client session: stateChange:1->0 Apple-Iphone5s-1_PT9511.iUx4mA==
,2015-12-22 01:56:16.981 ThaliTest[711:818912] client session: fireConnectCallback: Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:56:16.982 ThaliTest[711:818912] jxcore: connect: fail: Peer disconnected
2015-12-22T00:56:16.983Z SendDataConnector.js: CLIE,NT connected to 0, error: Peer disconnected
2015-12-22T00:56:16.983Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-22T00:56:16.983Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9511.iUx4mA==","peerName":"(null)","peerAvailable":false}]
,2015-12-22T00:56:21.993Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22T00:56:21.993Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT9511.iUx4mA==
,2015-12-22 01:56:22.594 ThaliTest[711:818912] multipeer session: restart
,2015-12-22 01:56:22.632 ThaliTest[711:818912] client: found peer: Apple-IpadAir2-1_PT8764.Ptw77g==
2015-12-22 01:56:22.633 ThaliTest[711:818912] client: found peer: Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:56:22.633 ThaliTest[711:818912] client: fo,und peer: Apple-Iphone5-1_PT5195.x5+2Tg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9511.iUx4mA==","peerName":"(null)","peerAvailable":true}]
,Connected to the server!
,2015-12-22 01:56:26.038 ThaliTest[711:818912] multipeer session: reset timer
2015-12-22 01:56:26.039 ThaliTest[711:818912] multipeer session: stop timer
2015-12-22 01:56:26.039 ThaliTest[711:818912] multipeer session: start timer: 0x15bd3f20
2015-12-22 ,01:56:26.039 ThaliTest[711:818912] server session: connect
2015-12-22 01:56:26.040 ThaliTest[711:818912] server session: stateChange:0->1 Apple-IpadAir2-1_PT8764
,2015-12-22 01:56:26.050 ThaliTest[711:818912] server: accepting invitation Apple-IpadAir2-1_PT8764
,2015-12-22 01:56:26.603 ThaliTest[711:818912] multipeer session: reset timer
2015-12-22 01:56:26.605 ThaliTest[711:818912] multipeer session: stop timer
2015-12-22 01:56:26.605 ThaliTest[711:818912] multipeer session: start timer: 0x15bd3f20
2015-12-22 ,01:56:26.606 ThaliTest[711:818912] server session: connect
2015-12-22 01:56:26.606 ThaliTest[711:818912] server session: stateChange:0->1 Apple-Iphone5-1_PT5195
,2015-12-22 01:56:26.615 ThaliTest[711:818912] server: accepting invitation Apple-Iphone5-1_PT5195
,2015-12-22 01:56:27.006 ThaliTest[711:819121] jxcore: disconnect
2015-12-22 01:56:27.007 ThaliTest[711:819121] jxcore: disconnect: fail
2015-12-22T00:56:27.007Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9511.iUx4mA==,
2015-12-22T00:56:27.009Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT9511.iUx4mA== with availability status: true
2015-12-22T00:56:27.010Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22T00:56:27.010Z SendDataConnector.js: do connect now
,2015-12-22 01:56:27.011 ThaliTest[711:819121] jxcore: connect Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:56:27.015 ThaliTest[711:819121] client session: connect
,2015-12-22 01:56:27.016 ThaliTest[711:819121] client session: stateChange:0->1 Apple-Iphone5s-1_PT9511.iUx4mA==
,appEnteringBackground wasn't registered
,2015-12-22 01:56:28.793 ThaliTest[711:820190] server session: connected
2015-12-22 01:56:28.793 ThaliTest[711:820190] server session: stateChange:1->2 Apple-IpadAir2-1_PT8764
2015-12-22 01:56:28.804 ThaliTest[711:818912] server relay: connected (to port: 55788)
,2015-12-22T00:56:28.813Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-22T00:56:29.118Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
2015-12-22T00:56:29.134Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
2015-12-22T00:56:29.151Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-22T00:56:29.169Z SendDataTCPServer.js: TCP/IP server has received 78698 bytes of data
,2015-12-22T00:56:29.183Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-22 01:56:29.198 ThaliTest[711:820195] server session: connected
2015-12-22 01:56:29.198 ThaliTest[711:820195] server session: stateChange:1->2 Apple-Iphone5-1_PT5195
,2015-12-22 01:56:29.215 ThaliTest[711:818912] server relay: connected (to port: 55788)
2015-12-22T00:56:29.222Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-22 01:56:29.225 ThaliTest[711:820334] server session: not connected Apple-IpadAir2-1_PT8764
,2015-12-22T00:56:29.707Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-22 01:56:29.721 ThaliTest[711:820334] client session: connected
2015-12-22 01:56:29.723 ThaliTest[711:820334] client session: stateChange:1->2 Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22T00:56:29.727Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-22T00:56:29.742Z SendDataTCPServer.js: TCP/IP server has received 21616 bytes of data
,2015-12-22T00:56:29.755Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-22 01:56:29.772 ThaliTest[711:820343] client session: fireConnectCallback: Apple-Iphone5s-1_PT9511.iUx4mA==
,2015-12-22T00:56:29.781Z SendDataTCPServer.js: TCP/IP server has received 55520 bytes of data
,2015-12-22 01:56:29.772 ThaliTest[711:820343] jxcore: connect: success
,2015-12-22T00:56:29.786Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-22T00:56:29.789Z SendDataConnector.js: CLIENT connected to 55804, error: null
2015-12-22T00:56:29.790Z SendDataConnector.js: CLIENT starting client 
,2015-12-22 01:56:29.795 ThaliTest[711:818912] client: relay established
2015-12-22 01:56:29.796 ThaliTest[711:818912] client: new accepted socket: 0x15c77950
,2015-12-22T00:56:29.810Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-22 01:56:29.829 ThaliTest[711:820195] server session: not connected Apple-Iphone5-1_PT5195
,2015-12-22T00:56:30.183Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-22T00:56:30.194Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-22T00:56:30.206Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-22T00:56:30.216Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-22T00:56:30.242Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-22T00:56:30.255Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-22T00:56:30.269Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-22T00:56:30.269Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-22T00:56:30.269Z SendDataConnector.js: CLIENT Stop now
,2015-12-22T00:56:30.269Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-22 01:56:30.270 ThaliTest[711:819121] jxcore: disconnect
2015-12-22 01:56:30.270 ThaliTest[711:819121] client session: disconnectFromPeer: Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:56:30.270 ThaliTest[711:819121] client session: disconnect
,2015-12-22 01:56:30.271 ThaliTest[711:819121] client session: stateChange:2->0 Apple-Iphone5s-1_PT9511.iUx4mA==
,2015-12-22 01:56:30.275 ThaliTest[711:819121] jxcore: disconnect: success
2015-12-22T00:56:30.275Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9511.iUx4mA==
---- round done--------
startWithNextDevice
device[3]: Apple-IpadAir2-1_PT8764.Ptw77g==
2015-12-22T00:56:30.276Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT8764.Ptw77g==
2015-12-22T00:56:30.276Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8764.Ptw77g==
2015-12-22T00:56:30.276Z SendDataConnector.js: do connect now
2015-12-22 01:56:30.276 ThaliTest[711:819121] jxcore: connect Apple-IpadAir2-1_PT8764.Ptw77g==
2015-12-22 01:56:30.276 ThaliTest[711:819121] client session: connect
2015-12-22 01:56:30.276 ThaliTest[711:81,9121] client session: stateChange:0->1 Apple-IpadAir2-1_PT8764.Ptw77g==
,timeout now
,weAreDoneNow, resultArray.length: 2
,sendReportNow
,done, now sending data to server
,2015-12-22T00:56:32.613Z SendDataConnector.js: CLIENT Stop now
,2015-12-22 01:56:32.614 ThaliTest[711:819121] jxcore: disconnect
2015-12-22 01:56:32.615 ThaliTest[711:819121] client session: disconnectFromPeer: Apple-IpadAir2-1_PT8764.Ptw77g==
2015-12-22 01:56:32.615 ThaliTest[711:819121] client session: disconnect
2015-12-22 01:56:32.616 ThaliTest[711:819121] client session: stateChange:1->0 Apple-IpadAir2-1_PT8764.Ptw77g==
,2015-12-22 01:56:32.690 ThaliTest[711:819121] client session: fireConnectCallback: Apple-IpadAir2-1_PT8764.Ptw77g==
2015-12-22 01:56:32.690 ThaliTest[711:819121] jxcore: connect: fail: Peer disconnected
2015-12-22T00:56:32.691Z SendDataConnector.js: CLIE,NT connected to 0, error: Peer disconnected
2015-12-22T00:56:32.691Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-22T00:56:32.691Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-12-22 01:56:32.692 ThaliTest[711:819121] jxc,ore: disconnect: success
2015-12-22T00:56:32.692Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8764.Ptw77g==
,2015-12-22T00:56:37.694Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT8764.Ptw77g==
,2015-12-22T00:56:37.695Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT8764.Ptw77g==
,2015-12-22 01:56:38.565 ThaliTest[711:818912] client: lost peer: Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:56:38.565 ThaliTest[711:818912] client session: onPeerLost: Apple-Iphone5s-1_PT9511.iUx4mA==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5s-1_PT9511.iUx4mA==","peerName":"(null)","peerAvailable":false}]
,2015-12-22 01:56:39.160 ThaliTest[711:818912] client: lost peer: Apple-IpadAir2-1_PT8764.Ptw77g==
2015-12-22 01:56:39.160 ThaliTest[711:818912] client session: onPeerLost: Apple-IpadAir2-1_PT8764.Ptw77g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8764.Ptw77g==","peerName":"(null)","peerAvailable":false}]
,2015-12-22 01:56:42.701 ThaliTest[711:819121] jxcore: disconnect
2015-12-22 01:56:42.702 ThaliTest[711:819121] jxcore: disconnect: fail
2015-12-22T00:56:42.702Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8764.Ptw77g==,
2015-12-22T00:56:42.703Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT8764.Ptw77g== with availability status: true
2015-12-22T00:56:42.703Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8764.Ptw77g==
,2015-12-22T00:56:42.703Z SendDataConnector.js: do connect now
,2015-12-22 01:56:42.704 ThaliTest[711:819121] jxcore: connect Apple-IpadAir2-1_PT8764.Ptw77g==
,2015-12-22 01:56:42.705 ThaliTest[711:819121] client: connect: unreachable Apple-IpadAir2-1_PT8764.Ptw77g==
2015-12-22 01:56:42.706 ThaliTest[711:819121] jxcore: connect: fail: Peer unreachable
2015-12-22T00:56:42.707Z SendDataConnector.js: CLIENT connec,ted to 0, error: Peer unreachable
2015-12-22T00:56:42.707Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-22T00:56:42.707Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-22 01:56:43.077 ThaliTest[711:818912] client: lost peer: Apple-Iphone5-1_PT5195.x5+2Tg==
2015-12-22 01:56:43.078 ThaliTest[711:818912] client session: onPeerLost: Apple-Iphone5-1_PT5195.x5+2Tg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5195.x5+2Tg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,teardown
,testSendData stopped
2015-12-22 01:56:46.461 ThaliTest[711:819121] jxcore: stopBroadcasting
2015-12-22 01:56:46.461 ThaliTest[711:819121] THEMultipeerSession stopping peer
2015-12-22 01:56:46.461 ThaliTest[711:819121] multipeer session: stop timer
2015,-12-22 01:56:46.462 ThaliTest[711:819121] server session: disconnect
2015-12-22 01:56:46.462 ThaliTest[711:819121] server session: stateChange:2->0 Apple-Iphone5-1_PT5195
2015-12-22 01:56:46.469 ThaliTest[711:819121] server session: disconnect
2015-12-22 01:56:46.470 ThaliTest[711:819121] server session: stateChange:2->0 Apple-IpadAir2-1_PT8764
,2015-12-22 01:56:46.536 ThaliTest[711:819121] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-22T00:56:46.555Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-22T00:56:46.557Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-22T00:56:46.558Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
