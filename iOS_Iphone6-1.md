#### Test 55742142a5c2fdb_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55742142a5c2fdb/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/E730E269-05A7-457E-A4BB-835ABAF94147/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/E730E269-05A7-457E-A4BB-835ABAF94147/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55742142a5c2fdb/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55742142a5c2fdb/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1592CE94-9531-4FF2-A100-3765757DDE61/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53495"
,(lldb)     command script import "/tmp/E730E269-05A7-457E-A4BB-835ABAF94147/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-12 13:14:20.106 ThaliTest[1806:3805913] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/086AC99D-7459-4051-87D9-276BDE0248E0/Library/Cookies/Cookies.binarycookies
,2016-01-12 13:14:20.348 ThaliTest[1806:3805913] Apache Cordova native platform version 3.9.2 is starting.
2016-01-12 13:14:20.349 ThaliTest[1806:3805913] Multi-tasking -> Device: YES, App: YES
,2016-01-12 13:14:20.356 ThaliTest[1806:3805913] Unlimited access to network resources
,2016-01-12 13:14:20.362 ThaliTest[1806:3805913] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-12 13:14:24.522 ThaliTest[1806:3805913] Resetting plugins due to page load.
,2016-01-12 13:14:25.769 ThaliTest[1806:3805913] Finished load of: file:///var/mobile/Containers/Bundle/Application/1592CE94-9531-4FF2-A100-3765757DDE61/ThaliTest.app/www/index.html
,2016-01-12 13:14:25.929 ThaliTest[1806:3805913] JXcore Cordova plugin initializing
,2016-01-12 13:14:25.931 ThaliTest[1806:3806073] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
check test folder
found test : ./testFindPeers.js
,found test : ./testSendData.js
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
serverPort is 8876
2016-01-12 13:19:30.659 ThaliTest[1806:3806073] jxcore: startBroadcasting
,2016-01-12 13:19:30.667 ThaliTest[1806:3806073] server: starting Apple-Iphone6-1.vdOTuw==
2016-01-12 13:19:30.668 ThaliTest[1806:3806073] multipeer session: start timer: 0x16495750
2016-01-12 13:19:30.668 ThaliTest[1806:3806073] THEMultipeerSession initialized peer Apple-Iphone6-1
2016-01-12 13:19:30.668 ThaliTest[1806:3806073] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-12 13:19:31.810 ThaliTest[1806:3805913] client: found peer: Apple-Iphone5-1.IBb4nw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.IBb4nw==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5-1.IBb4nw==, peerAvailable: true
,weAreDoneNow
done, now sending data to server
,2016-01-12 13:19:32.262 ThaliTest[1806:3805913] client: found peer: Apple-Iphone5s-1.+FhoNw==
,2016-01-12 13:19:32.584 ThaliTest[1806:3805913] client: found peer: Apple-IpadAir2-1.hA+i5Q==
teardown
testFindPeers stopped
2016-01-12 13:19:32.587 ThaliTest[1806:3806073] jxcore: stopBroadcasting
2016-01-12 13:19:32.587 ThaliTest[1806:3806073] THEMul,tipeerSession stopping peer
2016-01-12 13:19:32.587 ThaliTest[1806:3806073] multipeer session: stop timer
2016-01-12 13:19:32.587 ThaliTest[1806:3806073] jxcore: stopBroadcasting: success
StopBroadcasting went ok
--- start :testSendData.js---
testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
daya100000
check server
serverPort is 50360
2,016-01-12 13:19:32.593 ThaliTest[1806:3806073] jxcore: startBroadcasting
2016-01-12 13:19:32.597 ThaliTest[1806:3806073] server: starting Apple-Iphone6-1.56+AEA==
2016-01-12 13:19:32.597 ThaliTest[1806:3806073] multipeer session: start timer: 0x164a7ed0,
,2016-01-12 13:19:32.603 ThaliTest[1806:3806073] THEMultipeerSession initialized peer Apple-Iphone6-1
2016-01-12 13:19:32.615 ThaliTest[1806:3806073] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
2016-01-12 13:19:32.620 ThaliTest[1806:3805913] client: found peer: Apple-Iphone6-1.vdOTuw==
2016-01-12T12:19:32.620Z SendDataTCPServer.js: TCP/IP server is bound to port: 50360
2016-01-12 13:19:32.621 ThaliTest[1806:3805913] client: found peer: Apple-Iphone5-1.IBb4nw==
2016-01-12 13:19:32.621 ThaliTest[1806:3805913] client: found peer: Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:19:32.621 ThaliTest[1806:3805913] client: found peer: Apple-IpadAir2-1.hA+i5Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.hA+i5Q==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-IpadAir2-1.hA+i5Q==
,2016-01-12T12:19:32.627Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.hA+i5Q==
,2016-01-12T12:19:32.628Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.hA+i5Q==
,2016-01-12T12:19:32.628Z SendDataConnector.js: do connect now
,2016-01-12 13:19:32.628 ThaliTest[1806:3806073] jxcore: connect Apple-IpadAir2-1.hA+i5Q==
,2016-01-12 13:19:32.629 ThaliTest[1806:3806073] client session: connect
,2016-01-12 13:19:32.629 ThaliTest[1806:3806073] client session: stateChange:0->1 Apple-IpadAir2-1.hA+i5Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.vdOTuw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.IBb4nw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.+FhoNw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.hA+i5Q==","peerName":"(null)","peerAvailable":true}]
,2016-01-12 13:19:33.851 ThaliTest[1806:3805913] client: lost peer: Apple-Iphone6-1.vdOTuw==
2016-01-12 13:19:33.851 ThaliTest[1806:3805913] client session: onPeerLost: Apple-Iphone6-1.vdOTuw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.vdOTuw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-12 13:19:34.393 ThaliTest[1806:3805913] client: lost peer: Apple-Iphone5-1.IBb4nw==
2016-01-12 13:19:34.393 ThaliTest[1806:3805913] client session: onPeerLost: Apple-Iphone5-1.IBb4nw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.I,Bb4nw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
2016-01-12 13:19:34.396 ThaliTest[1806:3805913] client: lost peer: Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:19:34.396 ThaliTest[1806:3805913] client session: onPee,rLost: Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:19:34.396 ThaliTest[1806:3805913] client: lost peer: Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:19:34.396 ThaliTest[1806:3805913] client session: onPeerLost: Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:19:34.396 T,haliTest[1806:3805913] client session: onLinkFailure: Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:19:34.396 ThaliTest[1806:3805913] client session: disconnect
2016-01-12 13:19:34.396 ThaliTest[1806:3805913] client session: stateChange:1->0 Apple-IpadAir2-1.,hA+i5Q==
2016-01-12 13:19:34.398 ThaliTest[1806:3805913] client session: fireConnectCallback: Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:19:34.398 ThaliTest[1806:3805913] jxcore: connect: fail: Peer disconnected
2016-01-12 13:19:34.399 ThaliTest[1806:3805913] client: found peer: Apple-Iphone5-1.mOZnMg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.+FhoNw==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
2016-01-12T12:19:34.400Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2016-01-12T12:19:34.400Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-12T12:19:34.401Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.hA+i5Q==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.mOZnMg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-12 13:19:34.523 ThaliTest[1806:3805913] client: found peer: Apple-IpadAir2-1.WKZK+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.WKZK+A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
2016-01-,12 13:19:34.524 ThaliTest[1806:3805913] client: found peer: Apple-Iphone5s-1.8kws4w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.8kws4w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-12T12:19:39.410Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:19:39.411Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.hA+i5Q==
,2016-01-12 13:19:44.412 ThaliTest[1806:3806073] jxcore: disconnect
2016-01-12 13:19:44.412 ThaliTest[1806:3806073] jxcore: disconnect: fail
2016-01-12T12:19:44.413Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:19:44.413Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1.hA+i5Q== with availability status: true
2016-01-12T12:19:44.413Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:19:44.413Z SendDataConnector.js: do connect now
,2016-01-12 13:19:44.413 ThaliTest[1806:3806073] jxcore: connect Apple-IpadAir2-1.hA+i5Q==
,2016-01-12 13:19:44.414 ThaliTest[1806:3806073] client: connect: unreachable Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:19:44.414 ThaliTest[1806:3806073] jxcore: connect: fail: Peer unreachable
2016-01-12T12:19:44.414Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-12T12:19:44.414Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-12T12:19:44.414Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-12T12:19:49.415Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:19:49.416Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.hA+i5Q==
,2016-01-12 13:19:54.420 ThaliTest[1806:3806073] jxcore: disconnect
2016-01-12 13:19:54.420 ThaliTest[1806:3806073] jxcore: disconnect: fail
2016-01-12T12:19:54.420Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:19:54.421Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1.hA+i5Q== with availability status: true
2016-01-12T12:19:54.421Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:19:54,.421Z SendDataConnector.js: do connect now
2016-01-12 13:19:54.421 ThaliTest[1806:3806073] jxcore: connect Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:19:54.421 ThaliTest[1806:3806073] client: connect: unreachable Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:19:54.421 ThaliTest[1806:3806073] jxcore: connect: fail: Peer unreachable
2016-01-12T12:19:54.421Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-12T12:19:54.421Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-12T12:19:54.421Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-12T12:19:59.425Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:19:59.425Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.hA+i5Q==
,2016-01-12 13:20:02.603 ThaliTest[1806:3805913] multipeer session: restart
,2016-01-12 13:20:02.622 ThaliTest[1806:3805913] client: found peer: Apple-Iphone5-1.mOZnMg==
2016-01-12 13:20:02.622 ThaliTest[1806:3805913] client: found peer: Apple-Iphone5s-1.8kws4w==
2016-01-12 13:20:02.622 ThaliTest[1806:3805913] client: found peer: Apple-IpadAir2-1.WKZK+A==
,2016-01-12 13:20:04.433 ThaliTest[1806:3806073] jxcore: disconnect
2016-01-12 13:20:04.433 ThaliTest[1806:3806073] jxcore: disconnect: fail
2016-01-12T12:20:04.434Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:20:04.434Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1.hA+i5Q== with availability status: true
2016-01-12T12:20:04.434Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:20:04.434Z SendDataConnector.js: do connect now
2016-01-12 13:20:04.434 ThaliTest[1806:3806073] jxcore: connect Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:20:04.434 ThaliTest[1806:3806073] client: connect: unreachable Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:20:,04.434 ThaliTest[1806:3806073] jxcore: connect: fail: Peer unreachable
2016-01-12T12:20:04.434Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-12T12:20:04.434Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-12T12:20:04.434Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-12T12:20:09.443Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:20:09.443Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.hA+i5Q==
,2016-01-12 13:20:14.451 ThaliTest[1806:3806073] jxcore: disconnect
2016-01-12 13:20:14.451 ThaliTest[1806:3806073] jxcore: disconnect: fail
2016-01-12T12:20:14.452Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.hA+i5Q==
2,016-01-12T12:20:14.452Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1.hA+i5Q== with availability status: true
2016-01-12T12:20:14.452Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:20:14,.452Z SendDataConnector.js: do connect now
2016-01-12 13:20:14.452 ThaliTest[1806:3806073] jxcore: connect Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:20:14.452 ThaliTest[1806:3806073] client: connect: unreachable Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:20:14.452 ThaliTest[1806:3806073] jxcore: connect: fail: Peer unreachable
,2016-01-12T12:20:14.453Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-12T12:20:14.453Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
2016-01-12T12:20:14.454Z SendDataConnector.js: CLIENT S,top now
2016-01-12 13:20:14.454 ThaliTest[1806:3806073] jxcore: disconnect
2016-01-12 13:20:14.454 ThaliTest[1806:3806073] jxcore: disconnect: fail
2016-01-12T12:20:14.454Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.hA+i5Q==
---- round done--------
startWithNextDevice
device[2]: Apple-Iphone5-1.mOZnMg==
2016-01-12T12:20:14.455Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.mOZnMg==
2016-01-12T12:20:14.455Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.mOZnMg==
2016-01-12T12:20:14.455Z SendDataConnector.js: do connect now
2016-01-12 13:20:14.455 ThaliTest[1806:3806073] jxcore: connect Apple-Iphone5-1.mOZnMg==
2016-01-12 13:20:14.455 ThaliTest[1806:3806073] client session: connect,
2016-01-12 13:20:14.457 ThaliTest[1806:3806073] client session: stateChange:0->1 Apple-Iphone5-1.mOZnMg==
,2016-01-12 13:20:18.011 ThaliTest[1806:3806673] client session: connected
2016-01-12 13:20:18.011 ThaliTest[1806:3806673] client session: stateChange:1->2 Apple-Iphone5-1.mOZnMg==
,2016-01-12 13:20:18.039 ThaliTest[1806:3806677] client session: fireConnectCallback: Apple-Iphone5-1.mOZnMg==
2016-01-12 13:20:18.039 ThaliTest[1806:3806677] jxcore: connect: success
2016-01-12T12:20:18.039Z SendDataConnector.js: CLIENT connected to 50364, error: null
2016-01-12T12:20:18.039Z SendDataConnector.js: CLIENT starting client 
,2016-01-12 13:20:18.041 ThaliTest[1806:3805913] client: relay established
2016-01-12 13:20:18.041 ThaliTest[1806:3805913] client: new accepted socket: 0x163da6a0
,2016-01-12T12:20:18.054Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-12T12:20:18.526Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-12T12:20:18.539Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-12 13:20:19.120 ThaliTest[1806:3805913] multipeer session: reset timer
2016-01-12 13:20:19.120 ThaliTest[1806:3805913] multipeer session: stop timer
2016-01-12 13:20:19.120 ThaliTest[1806:3805913] multipeer session: start timer: 0x164a7ed0
2016-,01-12 13:20:19.120 ThaliTest[1806:3805913] server session: connect
2016-01-12 13:20:19.121 ThaliTest[1806:3805913] server session: stateChange:0->1 Apple-IpadAir2-1
2016-01-12 13:20:19.124 ThaliTest[1806:3805913] server: accepting invitation Apple-IpadAi,r2-1
,2016-01-12T12:20:19.585Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-12T12:20:19.585Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-12T12:20:19.586Z SendDataConnector.js: CLIENT Stop now
,2016-01-12T12:20:19.586Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-12 13:20:19.587 ThaliTest[1806:3806073] jxcore: disconnect
2016-01-12 13:20:19.587 ThaliTest[1806:3806073] client session: disconnectFromPeer: Apple-Iphone5-1.mOZnMg==
2016-01-12 13:20:19.587 ThaliTest[1806:3806073] client session: disconnect
2016-01-12 13:20:19.587 ThaliTest[1806:3806073] client session: stateChange:2->0 Apple-Iphone5-1.mOZnMg==
,2016-01-12 13:20:19.593 ThaliTest[1806:3806073] jxcore: disconnect: success
2016-01-12T12:20:19.593Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.mOZnMg==
,---- round done--------
startWithNextDevice
device[3]: Apple-IpadAir2-1.WKZK+A==
2016-01-12T12:20:19.594Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.WKZK+A==
2016-01-12T12:20:19.594Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.WKZK+A==
2016-01-12T12:20:19.594Z SendDataConnector.js: do connect now
2016-01-12 13:20:19.595 ThaliTest[1806:3806073] jxcore: connect Apple-IpadAir2-1.WKZK+A==
2016-01-12 13:20:19.595 ThaliTest[1806:3806073] client session: connect
2016-01-12 13:20:19.595 ThaliTest[1806:3806073] client session: stateChange:0->1 Apple-IpadAir2-1.WKZK+A==
,2016-01-12 13:20:20.561 ThaliTest[1806:3805913] multipeer session: reset timer
2016-01-12 13:20:20.562 ThaliTest[1806:3805913] multipeer session: stop timer
2016-01-12 13:20:20.562 ThaliTest[1806:3805913] multipeer session: start timer: 0x164a7ed0
2016-,01-12 13:20:20.562 ThaliTest[1806:3805913] server session: connect
2016-01-12 13:20:20.562 ThaliTest[1806:3805913] server session: stateChange:0->1 Apple-Iphone5-1
2016-01-12 13:20:20.565 ThaliTest[1806:3805913] server: accepting invitation Apple-Iphone5-1
,2016-01-12 13:20:22.129 ThaliTest[1806:3805913] multipeer session: reset timer
2016-01-12 13:20:22.130 ThaliTest[1806:3805913] multipeer session: stop timer
2016-01-12 13:20:22.130 ThaliTest[1806:3805913] multipeer session: start timer: 0x164a7ed0
,2016-01-12 13:20:22.130 ThaliTest[1806:3805913] server session: connect
2016-01-12 13:20:22.130 ThaliTest[1806:3805913] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-12 13:20:22.133 ThaliTest[1806:3805913] server: accepting invitation Apple-Iphone5s-1
,2016-01-12 13:20:22.660 ThaliTest[1806:3806691] server session: connected
2016-01-12 13:20:22.661 ThaliTest[1806:3806691] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-12 13:20:22.715 ThaliTest[1806:3805913] server relay: connected (to port: 50360)
,2016-01-12T12:20:22.718Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-12T12:20:23.112Z SendDataTCPServer.js: TCP/IP server has received 7665 bytes of data
,2016-01-12T12:20:23.125Z SendDataTCPServer.js: TCP/IP server has received 42705 bytes of data
,2016-01-12T12:20:23.139Z SendDataTCPServer.js: TCP/IP server has received 64605 bytes of data
,2016-01-12T12:20:23.183Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2016-01-12T12:20:23.195Z SendDataTCPServer.js: TCP/IP server has received 82125 bytes of data
,2016-01-12T12:20:23.245Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2016-01-12 13:20:23.251 ThaliTest[1806:3806691] client session: connected
,2016-01-12 13:20:23.252 ThaliTest[1806:3806691] client session: stateChange:1->2 Apple-IpadAir2-1.WKZK+A==
,2016-01-12 13:20:23.255 ThaliTest[1806:3806673] server session: connected
2016-01-12 13:20:23.255 ThaliTest[1806:3806673] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-12T12:20:23.257Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-12 13:20:23.258 ThaliTest[1806:3806691] client session: fireConnectCallback: Apple-IpadAir2-1.WKZK+A==
,2016-01-12 13:20:23.258 ThaliTest[1806:3806691] jxcore: connect: success
,2016-01-12T12:20:23.260Z SendDataConnector.js: CLIENT connected to 50368, error: null
2016-01-12T12:20:23.260Z SendDataConnector.js: CLIENT starting client 
,2016-01-12 13:20:23.261 ThaliTest[1806:3805913] client: relay established
2016-01-12 13:20:23.261 ThaliTest[1806:3805913] client: new accepted socket: 0x164c7f50
,2016-01-12T12:20:23.272Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-12 13:20:23.303 ThaliTest[1806:3805913] server relay: connected (to port: 50360)
,2016-01-12 13:20:23.315 ThaliTest[1806:3806677] server session: not connected Apple-IpadAir2-1
,2016-01-12T12:20:23.704Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-12T12:20:23.779Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-12T12:20:23.837Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-12T12:20:23.837Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2016-01-12T12:20:23.838Z SendDataConnector.js: CLIENT Stop now
,2016-01-12T12:20:23.838Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-12 13:20:23.838 ThaliTest[1806:3806073] jxcore: disconnect
,2016-01-12 13:20:23.839 ThaliTest[1806:3806073] client session: disconnectFromPeer: Apple-IpadAir2-1.WKZK+A==
,2016-01-12 13:20:23.839 ThaliTest[1806:3806073] client session: disconnect
,2016-01-12 13:20:23.839 ThaliTest[1806:3806073] client session: stateChange:2->0 Apple-IpadAir2-1.WKZK+A==
,2016-01-12 13:20:23.846 ThaliTest[1806:3806073] jxcore: disconnect: success
,2016-01-12T12:20:23.847Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.WKZK+A==
,---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone5s-1.8kws4w==
2016-01-12T12:20:23.850Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.8kws4w==
,2016-01-12T12:20:23.850Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.8kws4w==
,2016-01-12T12:20:23.851Z SendDataConnector.js: do connect now
,2016-01-12 13:20:23.851 ThaliTest[1806:3806073] jxcore: connect Apple-Iphone5s-1.8kws4w==
,2016-01-12 13:20:23.851 ThaliTest[1806:3806073] client session: connect
,2016-01-12 13:20:23.852 ThaliTest[1806:3806073] client session: stateChange:0->1 Apple-Iphone5s-1.8kws4w==
,2016-01-12T12:20:24.691Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2016-01-12 13:20:24.695 ThaliTest[1806:3806673] server session: connected
2016-01-12 13:20:24.695 ThaliTest[1806:3806673] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-12 13:20:24.696 ThaliTest[1806:3805913] server relay: connected (to port: 50360)
,2016-01-12T12:20:24.705Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2016-01-12T12:20:24.705Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-12T12:20:24.752Z SendDataTCPServer.js: TCP/IP server has received 51465 bytes of data
,2016-01-12T12:20:24.764Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2016-01-12T12:20:24.819Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2016-01-12T12:20:24.831Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2016-01-12T12:20:24.877Z SendDataTCPServer.js: TCP/IP server has received 88695 bytes of data
,2016-01-12T12:20:24.889Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-12 13:20:25.207 ThaliTest[1806:3806692] server session: not connected Apple-Iphone5-1
,2016-01-12T12:20:25.335Z SendDataTCPServer.js: TCP/IP server has received 5475 bytes of data
,2016-01-12T12:20:25.348Z SendDataTCPServer.js: TCP/IP server has received 44895 bytes of data
,2016-01-12T12:20:25.362Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2016-01-12T12:20:25.421Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2016-01-12T12:20:25.434Z SendDataTCPServer.js: TCP/IP server has received 99432 bytes of data
,2016-01-12T12:20:25.448Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-12 13:20:25.737 ThaliTest[1806:3806692] server session: not connected Apple-Iphone5s-1
,2016-01-12 13:20:26.452 ThaliTest[1806:3806692] client session: connected
2016-01-12 13:20:26.453 ThaliTest[1806:3806692] client session: stateChange:1->2 Apple-Iphone5s-1.8kws4w==
2016-01-12 13:20:26.455 ThaliTest[1806:3806673] client session: fireConnectCallback: Apple-Iphone5s-1.8kws4w==
2016-01-12 13:20:26.455 ThaliTest[1806:3806673] jxcore: connect: success
2016-01-12T12:20:26.456Z SendDataConnector.js: CLIENT connected to 50373, error: null
2016-01-12T12:20:26.456Z SendDataConnector.js: CLIENT starting client 
,2016-01-12 13:20:26.457 ThaliTest[1806:3805913] client: relay established
2016-01-12 13:20:26.458 ThaliTest[1806:3805913] client: new accepted socket: 0x164c80a0
,2016-01-12T12:20:26.470Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-12T12:20:26.991Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-12T12:20:27.040Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-12T12:20:27.146Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-12T12:20:27.159Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-12T12:20:27.160Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-12T12:20:27.160Z SendDataConnector.js: CLIENT Stop now
2016-01-12T12:20:27.160Z SendDataConnector.js: CLIENT closeClientSocket
2016-01-12 13:20:27.160 ThaliTest[1806:3806073] jxcore: disconnect
2016-01-12 13:20:27.160 ThaliTest[1806:3806073] client session: disconnectFromPeer: Apple-Iphone5s-1.8kws4w==
2016-01-12 13:20:27.160 ThaliTest[1806:3806073] client session: disconnect
,2016-01-12 13:20:27.161 ThaliTest[1806:3806073] client session: stateChange:2->0 Apple-Iphone5s-1.8kws4w==
,2016-01-12 13:20:27.170 ThaliTest[1806:3806073] jxcore: disconnect: success
2016-01-12T12:20:27.170Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.8kws4w==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
,2016-01-12T12:20:27.184Z SendDataConnector.js: CLIENT Stop now
2016-01-12T12:20:27.184Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
testSendData stopped
2016-01-12 13:20:29.342 ThaliTest[1806:3806073] jxcore: stopBroadcasting
2016-01-12 13:20:29.342 ThaliTest[1806:3806073] THEMultipeerSession stopping peer
2016-01-12 13:20:29.342 ThaliTest[1806:3806073] multipeer session: stop timer
2016-01-12 13:20:29.342 ThaliTest[1806:3806073] server session: disconnect
2016-01-12 13:20:29.343 ThaliTest[1806:3806073] server session: stateChange:2->0 Apple-Iphone5s-1
2016-01-12 13:20:29.345 ThaliTest[1806:3806073] server session: disconnect
2016-01-12 13:20:29.345 ThaliTest[1806:3806073] server session: stateChange:2->0 Apple-IpadAir2-1
2016-01-12 13:20:29.346 ThaliTest[1806:3806073] server session: disconnect
2016-01-12 13:20:29.346 ThaliTest[1806:3806073] server session: stateChang,e:2->0 Apple-Iphone5-1
,2016-01-12 13:20:29.350 ThaliTest[1806:3806073] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-12T12:20:29.364Z SendDataTCPServer.js: TCP/IP server is ended
2016-01-12T12:20:29.364Z SendDataTCPServer.js: TCP/IP server is ended
2016-01-12T12:20:29.364Z SendDataTCPServer.js: TCP/IP server is ended
2016-01-12T12:20:29.365Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
