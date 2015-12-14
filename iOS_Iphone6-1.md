#### Test 50650278b2f31ec_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278b2f31ec/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/66E828CC-3C92-4188-9F51-DB20FDCA5158/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/66E828CC-3C92-4188-9F51-DB20FDCA5158/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278b2f31ec/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278b2f31ec/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DA890F05-2C2B-459A-A1B1-4295D6EDB71D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55247"
,(lldb)     command script import "/tmp/66E828CC-3C92-4188-9F51-DB20FDCA5158/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-14 15:37:15.188 ThaliTest[899:1159920] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/812F8557-1714-4CE1-B410-A24BD8EF4540/Library/Cookies/Cookies.binarycookies
,2015-12-14 15:37:15.555 ThaliTest[899:1159920] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-14 15:37:15.556 ThaliTest[899:1159920] Multi-tasking -> Device: YES, App: YES
,2015-12-14 15:37:15.565 ThaliTest[899:1159920] Unlimited access to network resources
,2015-12-14 15:37:15.578 ThaliTest[899:1159920] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-14 15:37:24.516 ThaliTest[899:1159920] Resetting plugins due to page load.
,2015-12-14 15:37:28.261 ThaliTest[899:1159920] Finished load of: file:///var/mobile/Containers/Bundle/Application/DA890F05-2C2B-459A-A1B1-4295D6EDB71D/ThaliTest.app/www/index.html
,2015-12-14 15:37:28.445 ThaliTest[899:1159920] JXcore Cordova plugin initializing
,2015-12-14 15:37:28.447 ThaliTest[899:1160120] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-14 15:37:29.514 ThaliTest[899:1159920] THREAD WARNING: ['JXcore'] took '78.847168' ms. Plugin should use a background thread.
,appEnteredForeground wasn't registered
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-14 15:42:00.660 ThaliTest[899:1160120] jxcore: startBroadcasting
,2015-12-14 15:42:00.676 ThaliTest[899:1160120] server: starting Apple-Iphone6-1_PT9995.u0gQiQ==
,2015-12-14 15:42:00.680 ThaliTest[899:1160120] multipeer session: start timer: 0x18c42390
2015-12-14 15:42:00.681 ThaliTest[899:1160120] THEMultipeerSession initialized peer Apple-Iphone6-1_PT9995
2015-12-14 15:42:00.682 ThaliTest[899:1160120] jxcore: st,artBroadcasting: success
StartBroadcasting started ok
,2015-12-14 15:42:02.291 ThaliTest[899:1159920] client: found peer: Apple-IpadAir2-1_PT4459.Sbdxaw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4459.Sbdxaw==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1_PT4459.Sbdxaw==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,2015-12-14 15:42:02.407 ThaliTest[899:1159920] client: found peer: Apple-Iphone5-1_PT9827.emG9ZA==
,teardown
,testFindPeers stopped
,2015-12-14 15:42:02.566 ThaliTest[899:1160120] jxcore: stopBroadcasting
2015-12-14 15:42:02.568 ThaliTest[899:1160120] THEMultipeerSession stopping peer
2015-12-14 15:42:02.568 ThaliTest[899:1160120] multipeer session: stop timer
2015-12-14 15:42:02.568, ThaliTest[899:1160120] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
serverPort is 57439
,2015-12-14 15:42:02.632 ThaliTest[899:1160120] jxcore: startBroadcasting
,2015-12-14 15:42:02.636 ThaliTest[899:1160120] server: starting Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14 15:42:02.637 ThaliTest[899:1160120] multipeer session: start timer: 0x18b698b0
2015-12-14 15:42:02.637 ThaliTest[899:1160120] THEMultipeerSession i,nitialized peer Apple-Iphone6-1_PT9995
2015-12-14 15:42:02.638 ThaliTest[899:1160120] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2015-12-14T14:42:02.642Z SendDataTCPServer.js: TCP/IP server is bound to port: 57439
,2015-12-14 15:42:02.667 ThaliTest[899:1159920] client: found peer: Apple-Iphone6-1_PT9995.u0gQiQ==
2015-12-14 15:42:02.667 ThaliTest[899:1159920] client: found peer: Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:02.668 ThaliTest[899:1159920] client: f,ound peer: Apple-IpadAir2-1_PT4459.Sbdxaw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9995.u0gQiQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone6-1_PT9995.u0gQiQ==
,2015-12-14T14:42:02.671Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT9995.u0gQiQ==
,2015-12-14T14:42:02.672Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9995.u0gQiQ==
,2015-12-14T14:42:02.672Z SendDataConnector.js: do connect now
2015-12-14 15:42:02.673 ThaliTest[899:1160120] jxcore: connect Apple-Iphone6-1_PT9995.u0gQiQ==
2015-12-14 15:42:02.674 ThaliTest[899:1160120] client session: connect
2015-12-14 15:42:02.674 ThaliTest[899:1160120] client session: stateChange:0->1 Apple-Iphone6-1_PT9995.u0gQiQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9827.emG9ZA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4459.Sbdxaw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 15:42:03.796 ThaliTest[899:1159920] client: lost peer: Apple-Iphone6-1_PT9995.u0gQiQ==
2015-12-14 15:42:03.796 ThaliTest[899:1159920] client session: onPeerLost: Apple-Iphone6-1_PT9995.u0gQiQ==
2015-12-14 15:42:03.796 ThaliTest[899:1159920] cl,ient session: onLinkFailure: Apple-Iphone6-1_PT9995.u0gQiQ==
2015-12-14 15:42:03.796 ThaliTest[899:1159920] client session: disconnect
2015-12-14 15:42:03.797 ThaliTest[899:1159920] client session: stateChange:1->0 Apple-Iphone6-1_PT9995.u0gQiQ==
,2015-12-14 15:42:03.799 ThaliTest[899:1159920] client session: fireConnectCallback: Apple-Iphone6-1_PT9995.u0gQiQ==
2015-12-14 15:42:03.799 ThaliTest[899:1159920] jxcore: connect: fail: Peer disconnected
2015-12-14 15:42:03.800 ThaliTest[899:1159920] cli,ent: lost peer: Apple-IpadAir2-1_PT4459.Sbdxaw==
2015-12-14 15:42:03.800 ThaliTest[899:1159920] client session: onPeerLost: Apple-IpadAir2-1_PT4459.Sbdxaw==
2015-12-14T14:42:03.801Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2,015-12-14T14:42:03.802Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-14T14:42:03.802Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9995.u0gQiQ==","peerName":"(null),","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4459.Sbdxaw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-14 15:42:04.421 ThaliTest[899:1159920] client: found peer: Apple-IpadAir2-1_PT4459.LRQ+wA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4459.LRQ+wA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 15:42:05.550 ThaliTest[899:1159920] client: found peer: Apple-Iphone5-1_PT9827.8xg46g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9827.8xg46g==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-14 15:42:06.622 ThaliTest[899:1159920] client: lost peer: Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:06.622 ThaliTest[899:1159920] client session: onPeerLost: Apple-Iphone5-1_PT9827.emG9ZA==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5-1_PT9827.emG9ZA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-14 15:42:07.579 ThaliTest[899:1159920] client: found peer: Apple-Iphone5s-1_PT2942.N5Uy6w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT2942.N5Uy6w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14T14:42:08.811Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT9995.u0gQiQ==
,2015-12-14T14:42:08.812Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT9995.u0gQiQ==
,2015-12-14 15:42:13.824 ThaliTest[899:1160120] jxcore: disconnect
2015-12-14 15:42:13.825 ThaliTest[899:1160120] jxcore: disconnect: fail
2015-12-14T14:42:13.825Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9995.u0gQiQ=,=
2015-12-14T14:42:13.826Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT9995.u0gQiQ== with availability status: true
2015-12-14T14:42:13.826Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9995.u0gQiQ==
,2015-12-14T14:42:13.826Z SendDataConnector.js: do connect now
,2015-12-14 15:42:13.827 ThaliTest[899:1160120] jxcore: connect Apple-Iphone6-1_PT9995.u0gQiQ==
2015-12-14 15:42:13.828 ThaliTest[899:1160120] client: connect: unreachable Apple-Iphone6-1_PT9995.u0gQiQ==
2015-12-14 15:42:13.829 ThaliTest[899:1160120] jxco,re: connect: fail: Peer unreachable
2015-12-14T14:42:13.829Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T14:42:13.829Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T14:42:13.830Z SendDataCo,nnector.js: tryAgain afer: 5000 ms.
,2015-12-14T14:42:18.835Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT9995.u0gQiQ==
,2015-12-14T14:42:18.836Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT9995.u0gQiQ==
,2015-12-14 15:42:23.837 ThaliTest[899:1160120] jxcore: disconnect
2015-12-14 15:42:23.838 ThaliTest[899:1160120] jxcore: disconnect: fail
2015-12-14T14:42:23.838Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9995.u0gQiQ=,=
2015-12-14T14:42:23.839Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT9995.u0gQiQ== with availability status: true
2015-12-14T14:42:23.839Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9995.u0gQiQ==
201,5-12-14T14:42:23.839Z SendDataConnector.js: do connect now
,2015-12-14 15:42:23.841 ThaliTest[899:1160120] jxcore: connect Apple-Iphone6-1_PT9995.u0gQiQ==
2015-12-14 15:42:23.842 ThaliTest[899:1160120] client: connect: unreachable Apple-Iphone6-1_PT9995.u0gQiQ==
,2015-12-14 15:42:23.843 ThaliTest[899:1160120] jxcore: connect: fail: Peer unreachable
,2015-12-14T14:42:23.844Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T14:42:23.845Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T14:42:23.845Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T14:42:28.858Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT9995.u0gQiQ==
,2015-12-14T14:42:28.858Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT9995.u0gQiQ==
,2015-12-14 15:42:32.639 ThaliTest[899:1159920] multipeer session: restart
,2015-12-14 15:42:32.681 ThaliTest[899:1159920] client: found peer: Apple-Iphone5-1_PT9827.8xg46g==
2015-12-14 15:42:32.683 ThaliTest[899:1159920] client: found peer: Apple-IpadAir2-1_PT4459.LRQ+wA==
2015-12-14 15:42:32.683 ThaliTest[899:1159920] client: found peer: Apple-Iphone5s-1_PT2942.N5Uy6w==
,2015-12-14 15:42:33.864 ThaliTest[899:1160120] jxcore: disconnect
2015-12-14 15:42:33.865 ThaliTest[899:1160120] jxcore: disconnect: fail
2015-12-14T14:42:33.865Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9995.u0gQiQ=,=
2015-12-14T14:42:33.866Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT9995.u0gQiQ== with availability status: true
2015-12-14T14:42:33.866Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9995.u0gQiQ==
,2015-12-14T14:42:33.866Z SendDataConnector.js: do connect now
,2015-12-14 15:42:33.867 ThaliTest[899:1160120] jxcore: connect Apple-Iphone6-1_PT9995.u0gQiQ==
2015-12-14 15:42:33.869 ThaliTest[899:1160120] client: connect: unreachable Apple-Iphone6-1_PT9995.u0gQiQ==
2015-12-14 15:42:33.870 ThaliTest[899:1160120] jxco,re: connect: fail: Peer unreachable
2015-12-14T14:42:33.870Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T14:42:33.870Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T14:42:33.871Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T14:42:38.878Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT9995.u0gQiQ==
,2015-12-14T14:42:38.879Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT9995.u0gQiQ==
,2015-12-14 15:42:43.888 ThaliTest[899:1160120] jxcore: disconnect
2015-12-14 15:42:43.888 ThaliTest[899:1160120] jxcore: disconnect: fail
2015-12-14T14:42:43.889Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9995.u0gQiQ=,=
2015-12-14T14:42:43.889Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT9995.u0gQiQ== with availability status: true
2015-12-14T14:42:43.889Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9995.u0gQiQ==
201,5-12-14T14:42:43.890Z SendDataConnector.js: do connect now
,2015-12-14 15:42:43.890 ThaliTest[899:1160120] jxcore: connect Apple-Iphone6-1_PT9995.u0gQiQ==
,2015-12-14 15:42:43.891 ThaliTest[899:1160120] client: connect: unreachable Apple-Iphone6-1_PT9995.u0gQiQ==
2015-12-14 15:42:43.892 ThaliTest[899:1160120] jxcore: connect: fail: Peer unreachable
2015-12-14T14:42:43.893Z SendDataConnector.js: CLIENT conne,cted to 0, error: Peer unreachable
2015-12-14T14:42:43.893Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2015-12-14T14:42:43.895Z SendDataConnector.js: CLIENT Stop now
,2015-12-14 15:42:43.896 ThaliTest[899:1160120] jxcore: disconnect
2015-12-14 15:42:43.897 ThaliTest[899:1160120] jxcore: disconnect: fail
2015-12-14T14:42:43.897Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9995.u0gQiQ==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-IpadAir2-1_PT4459.LRQ+wA==
,2015-12-14T14:42:43.901Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT4459.LRQ+wA==
,2015-12-14T14:42:43.901Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT4459.LRQ+wA==
,2015-12-14T14:42:43.902Z SendDataConnector.js: do connect now
,2015-12-14 15:42:43.903 ThaliTest[899:1160120] jxcore: connect Apple-IpadAir2-1_PT4459.LRQ+wA==
2015-12-14 15:42:43.904 ThaliTest[899:1160120] client session: connect
2015-12-14 15:42:43.904 ThaliTest[899:1160120] client session: stateChange:0->1 Apple-I,padAir2-1_PT4459.LRQ+wA==
,2015-12-14 15:42:44.379 ThaliTest[899:1159920] multipeer session: reset timer
2015-12-14 15:42:44.379 ThaliTest[899:1159920] multipeer session: stop timer
2015-12-14 15:42:44.380 ThaliTest[899:1159920] multipeer session: start timer: 0x18b698b0
,2015-12-14 15:42:44.380 ThaliTest[899:1159920] server session: connect
2015-12-14 15:42:44.381 ThaliTest[899:1159920] server session: stateChange:0->1 Apple-Iphone5s-1_PT2942
,2015-12-14 15:42:44.391 ThaliTest[899:1159920] server: accepting invitation Apple-Iphone5s-1_PT2942
,2015-12-14 15:42:44.729 ThaliTest[899:1159920] multipeer session: reset timer
2015-12-14 15:42:44.729 ThaliTest[899:1159920] multipeer session: stop timer
2015-12-14 15:42:44.729 ThaliTest[899:1159920] multipeer session: start timer: 0x18b698b0
2015-12-,14 15:42:44.729 ThaliTest[899:1159920] server session: connect
2015-12-14 15:42:44.730 ThaliTest[899:1159920] server session: stateChange:0->1 Apple-IpadAir2-1_PT4459
,2015-12-14 15:42:44.733 ThaliTest[899:1159920] server: accepting invitation Apple-IpadAir2-1_PT4459
,2015-12-14 15:42:47.541 ThaliTest[899:1160760] client session: connected
,2015-12-14 15:42:47.542 ThaliTest[899:1160738] server session: connected
,2015-12-14 15:42:47.543 ThaliTest[899:1160760] client session: stateChange:1->2 Apple-IpadAir2-1_PT4459.LRQ+wA==
,2015-12-14 15:42:47.545 ThaliTest[899:1160738] server session: stateChange:1->2 Apple-IpadAir2-1_PT4459
,2015-12-14 15:42:47.558 ThaliTest[899:1160760] client session: fireConnectCallback: Apple-IpadAir2-1_PT4459.LRQ+wA==
2015-12-14 15:42:47.558 ThaliTest[899:1160760] jxcore: connect: success
,2015-12-14T14:42:47.562Z SendDataTCPServer.js: TCP/IP server connected
2015-12-14 15:42:47.563 ThaliTest[899:1159920] server relay: connected (to port: 57439)
2015-12-14T14:42:47.564Z SendDataConnector.js: CLIENT connected to 57446, error: null
2015-12-,14T14:42:47.565Z SendDataConnector.js: CLIENT starting client 
2015-12-14 15:42:47.570 ThaliTest[899:1159920] client: relay established
,2015-12-14 15:42:47.570 ThaliTest[899:1159920] client: new accepted socket: 0x18b82880
,2015-12-14T14:42:47.585Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T14:42:47.901Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-14T14:42:47.914Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-14T14:42:47.940Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14T14:42:47.945Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-14 15:42:48.003 ThaliTest[899:1160741] server session: connected
2015-12-14 15:42:48.004 ThaliTest[899:1160741] server session: stateChange:1->2 Apple-Iphone5s-1_PT2942
,2015-12-14 15:42:48.006 ThaliTest[899:1159920] server relay: connected (to port: 57439)
,2015-12-14T14:42:48.007Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-14T14:42:48.021Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T14:42:48.021Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-14T14:42:48.021Z SendDataConnector.js: CLIENT Stop now
2015-12-14T14:42:48.022Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 15:42:48.022 ThaliTest[899:1160120] jxcore: disconnect
2015-12-14 15:42:48.023 ThaliTest[899:1160120] client session: disconnectFromPeer: Apple-IpadAir2-1_PT4459.LRQ+wA==
,2015-12-14 15:42:48.023 ThaliTest[899:1160120] client session: disconnect
,2015-12-14 15:42:48.023 ThaliTest[899:1160120] client session: stateChange:2->0 Apple-IpadAir2-1_PT4459.LRQ+wA==
,2015-12-14 15:42:48.061 ThaliTest[899:1160709] server session: not connected Apple-IpadAir2-1_PT4459
,2015-12-14 15:42:48.088 ThaliTest[899:1160120] jxcore: disconnect: success
,2015-12-14T14:42:48.089Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT4459.LRQ+wA==
---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone5-1_PT9827.8xg46g==
,2015-12-14T14:42:48.090Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9827.8xg46g==
,2015-12-14T14:42:48.090Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9827.8xg46g==
,2015-12-14T14:42:48.090Z SendDataConnector.js: do connect now
,2015-12-14 15:42:48.091 ThaliTest[899:1160120] jxcore: connect Apple-Iphone5-1_PT9827.8xg46g==
,2015-12-14 15:42:48.091 ThaliTest[899:1160120] client session: connect
,2015-12-14 15:42:48.092 ThaliTest[899:1160120] client session: stateChange:0->1 Apple-Iphone5-1_PT9827.8xg46g==
,2015-12-14T14:42:48.099Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T14:42:48.407Z SendDataTCPServer.js: TCP/IP server has received 28186 bytes of data
,2015-12-14T14:42:48.423Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-14T14:42:48.444Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-14T14:42:48.487Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 15:42:48.561 ThaliTest[899:1160738] server session: not connected Apple-Iphone5s-1_PT2942
,2015-12-14 15:42:52.156 ThaliTest[899:1160738] client session: connected
2015-12-14 15:42:52.158 ThaliTest[899:1160738] client session: stateChange:1->2 Apple-Iphone5-1_PT9827.8xg46g==
2015-12-14 15:42:52.162 ThaliTest[899:1160738] client session: fireCo,nnectCallback: Apple-Iphone5-1_PT9827.8xg46g==
2015-12-14 15:42:52.162 ThaliTest[899:1160738] jxcore: connect: success
2015-12-14T14:42:52.164Z SendDataConnector.js: CLIENT connected to 57451, error: null
2015-12-14T14:42:52.164Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 15:42:52.169 ThaliTest[899:1159920] client: relay established
2015-12-14 15:42:52.169 ThaliTest[899:1159920] client: new accepted socket: 0x18c673a0
,2015-12-14T14:42:52.182Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T14:42:52.463Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-14T14:42:52.487Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-14T14:42:52.500Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-14T14:42:52.514Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T14:42:52.514Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T14:42:52.515Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T14:42:52.515Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 15:42:52.516 ThaliTest[899:1160120] jxcore: disconnect
,2015-12-14 15:42:52.516 ThaliTest[899:1160120] client session: disconnectFromPeer: Apple-Iphone5-1_PT9827.8xg46g==
,2015-12-14 15:42:52.517 ThaliTest[899:1160120] client session: disconnect
,2015-12-14 15:42:52.517 ThaliTest[899:1160120] client session: stateChange:2->0 Apple-Iphone5-1_PT9827.8xg46g==
,2015-12-14 15:42:52.583 ThaliTest[899:1160120] jxcore: disconnect: success
,2015-12-14T14:42:52.584Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9827.8xg46g==
,---- round done--------
startWithNextDevice
,device[4]: Apple-Iphone5s-1_PT2942.N5Uy6w==
,2015-12-14T14:42:52.585Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT2942.N5Uy6w==
,2015-12-14T14:42:52.585Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT2942.N5Uy6w==
,2015-12-14T14:42:52.585Z SendDataConnector.js: do connect now
,2015-12-14 15:42:52.586 ThaliTest[899:1160120] jxcore: connect Apple-Iphone5s-1_PT2942.N5Uy6w==
,2015-12-14 15:42:52.586 ThaliTest[899:1160120] client session: connect
,2015-12-14 15:42:52.587 ThaliTest[899:1160120] client session: stateChange:0->1 Apple-Iphone5s-1_PT2942.N5Uy6w==
,2015-12-14 15:42:55.417 ThaliTest[899:1160709] client session: connected
2015-12-14 15:42:55.417 ThaliTest[899:1160709] client session: stateChange:1->2 Apple-Iphone5s-1_PT2942.N5Uy6w==
,2015-12-14 15:42:55.448 ThaliTest[899:1160760] client session: fireConnectCallback: Apple-Iphone5s-1_PT2942.N5Uy6w==
2015-12-14 15:42:55.448 ThaliTest[899:1160760] jxcore: connect: success
2015-12-14T14:42:55.449Z SendDataConnector.js: CLIENT connected t,o 57454, error: null
2015-12-14T14:42:55.450Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 15:42:55.453 ThaliTest[899:1159920] client: relay established
2015-12-14 15:42:55.454 ThaliTest[899:1159920] client: new accepted socket: 0x18b79d90
,2015-12-14T14:42:55.464Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T14:42:55.767Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-14T14:42:55.792Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-14T14:42:55.804Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-14T14:42:55.829Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T14:42:55.830Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2015-12-14T14:42:55.830Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T14:42:55.830Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 15:42:55.831 ThaliTest[899:1160120] jxcore: disconnect
2015-12-14 15:42:55.831 ThaliTest[899:1160120] client session: disconnectFromPeer: Apple-Iphone5s-1_PT2942.N5Uy6w==
2015-12-14 15:42:55.831 ThaliTest[899:1160120] client session: disconnect
2015-12-14 15:42:55.831 ThaliTest[899:1160120] client session: stateChange:2->0 Apple-Iphone5s-1_PT2942.N5Uy6w==
,2015-12-14 15:42:55.835 ThaliTest[899:1160120] jxcore: disconnect: success
2015-12-14T14:42:55.835Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT2942.N5Uy6w==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
,sendReportNow
done, now sending data to server
2015-12-14T14:42:55.839Z SendDataConnector.js: CLIENT Stop now
2015-12-14T14:42:55.839Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 15:43:14.731 ThaliTest[899:1159920] multipeer session: restart
,2015-12-14 15:43:14.772 ThaliTest[899:1159920] client: found peer: Apple-Iphone5-1_PT9827.8xg46g==
2015-12-14 15:43:14.773 ThaliTest[899:1159920] client: found peer: Apple-Iphone5s-1_PT2942.N5Uy6w==
2015-12-14 15:43:14.774 ThaliTest[899:1159920] client: found peer: Apple-IpadAir2-1_PT4459.LRQ+wA==
,2015-12-14 15:43:24.569 ThaliTest[899:1159920] multipeer session: reset timer
2015-12-14 15:43:24.570 ThaliTest[899:1159920] multipeer session: stop timer
2015-12-14 15:43:24.570 ThaliTest[899:1159920] multipeer session: start timer: 0x18b698b0
2015-12-,14 15:43:24.570 ThaliTest[899:1159920] server session: connect
2015-12-14 15:43:24.571 ThaliTest[899:1159920] server session: stateChange:0->1 Apple-Iphone5-1_PT9827
,2015-12-14 15:43:24.580 ThaliTest[899:1159920] server: accepting invitation Apple-Iphone5-1_PT9827
,2015-12-14 15:43:27.802 ThaliTest[899:1160827] server session: connected
2015-12-14 15:43:27.804 ThaliTest[899:1160827] server session: stateChange:1->2 Apple-Iphone5-1_PT9827
,2015-12-14 15:43:27.809 ThaliTest[899:1159920] server relay: connected (to port: 57439)
2015-12-14T14:43:27.816Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T14:43:28.357Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-14T14:43:28.369Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-14T14:43:28.384Z SendDataTCPServer.js: TCP/IP server has received 45706 bytes of data
,2015-12-14T14:43:28.401Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-14T14:43:28.429Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-14T14:43:28.446Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 15:43:28.548 ThaliTest[899:1160826] server session: not connected Apple-Iphone5-1_PT9827
,2015-12-14 15:43:38.236 ThaliTest[899:1159920] client: lost peer: Apple-IpadAir2-1_PT4459.LRQ+wA==
2015-12-14 15:43:38.237 ThaliTest[899:1159920] client session: onPeerLost: Apple-IpadAir2-1_PT4459.LRQ+wA==
peerAvailabilityChanged [{"peerIdentifier":"App,le-IpadAir2-1_PT4459.LRQ+wA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,teardown
,testSendData stopped
2015-12-14 15:43:39.422 ThaliTest[899:1160120] jxcore: stopBroadcasting
,2015-12-14 15:43:39.423 ThaliTest[899:1160120] THEMultipeerSession stopping peer
2015-12-14 15:43:39.424 ThaliTest[899:1160120] multipeer session: stop timer
2015-12-14 15:43:39.425 ThaliTest[899:1160120] server session: disconnect
2015-12-14 15:43:39.4,26 ThaliTest[899:1160120] server session: stateChange:2->0 Apple-Iphone5-1_PT9827
,2015-12-14 15:43:39.436 ThaliTest[899:1160120] server session: disconnect
2015-12-14 15:43:39.437 ThaliTest[899:1160120] server session: stateChange:2->0 Apple-Iphone5s-1_PT2942
,2015-12-14 15:43:39.506 ThaliTest[899:1160120] server session: disconnect
2015-12-14 15:43:39.507 ThaliTest[899:1160120] server session: stateChange:2->0 Apple-IpadAir2-1_PT4459
,2015-12-14 15:43:39.574 ThaliTest[899:1160120] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-14T14:43:39.592Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T14:43:39.594Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T14:43:39.596Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T14:43:39.597Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
