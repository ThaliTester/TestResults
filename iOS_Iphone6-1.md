#### Test 50650278b28a87a_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278b28a87a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/AF83F602-1630-4BBB-80F5-50C8CDCCCFC0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/AF83F602-1630-4BBB-80F5-50C8CDCCCFC0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278b28a87a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278b28a87a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D4011AA2-9095-4465-BFF0-AA37DB27255D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52139"
,(lldb)     command script import "/tmp/AF83F602-1630-4BBB-80F5-50C8CDCCCFC0/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-09 15:25:25.524 ThaliTest[580:432030] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C35EC4A1-6DBF-4BBB-951E-C817F39133D1/Library/Cookies/Cookies.binarycookies
,2015-12-09 15:25:25.898 ThaliTest[580:432030] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-09 15:25:25.900 ThaliTest[580:432030] Multi-tasking -> Device: YES, App: YES
,2015-12-09 15:25:25.909 ThaliTest[580:432030] Unlimited access to network resources
,2015-12-09 15:25:25.920 ThaliTest[580:432030] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-09 15:25:35.060 ThaliTest[580:432030] Resetting plugins due to page load.
,2015-12-09 15:25:38.307 ThaliTest[580:432030] Finished load of: file:///var/mobile/Containers/Bundle/Application/D4011AA2-9095-4465-BFF0-AA37DB27255D/ThaliTest.app/www/index.html
,2015-12-09 15:25:38.490 ThaliTest[580:432030] JXcore Cordova plugin initializing
2015-12-09 15:25:38.492 ThaliTest[580:432243] JXcore instance initializing
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
,2015-12-09 15:25:39.558 ThaliTest[580:432030] THREAD WARNING: ['JXcore'] took '79.803955' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-09 15:30:42.657 ThaliTest[580:432243] jxcore: startBroadcasting
,2015-12-09 15:30:42.673 ThaliTest[580:432243] server: starting Apple-Iphone6-1_PT7748.MiTYRw==
,2015-12-09 15:30:42.675 ThaliTest[580:432243] multipeer session: start timer: 0x193ee660
,2015-12-09 15:30:42.677 ThaliTest[580:432243] THEMultipeerSession initialized peer Apple-Iphone6-1_PT7748
2015-12-09 15:30:42.677 ThaliTest[580:432243] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-09 15:30:43.739 ThaliTest[580:432030] client: found peer: Apple-Iphone5s-1_PT3959.Sz9P+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3959.Sz9P+A==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5s-1_PT39,59.Sz9P+A==, peerAvailable: true
weAreDoneNow
done, now sending data to server
2015-12-09 15:30:43.744 ThaliTest[580:432030] client: found peer: Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:30:44.826 ThaliTest[580:432030] client: found peer: Apple-Iphone5-1_PT9641.ucdqLA==
,teardown
,testFindPeers stopped
,2015-12-09 15:30:45.097 ThaliTest[580:432243] jxcore: stopBroadcasting
2015-12-09 15:30:45.098 ThaliTest[580:432243] THEMultipeerSession stopping peer
,2015-12-09 15:30:45.098 ThaliTest[580:432243] multipeer session: stop timer
,2015-12-09 15:30:45.100 ThaliTest[580:432243] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"servertimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 52629
,2015-12-09 15:30:45.164 ThaliTest[580:432243] jxcore: startBroadcasting
,2015-12-09 15:30:45.168 ThaliTest[580:432243] server: starting Apple-Iphone6-1_PT7748.7slvbQ==
2015-12-09 15:30:45.169 ThaliTest[580:432243] multipeer session: start timer: 0x193f42f0
2015-12-09 15:30:45.169 ThaliTest[580:432243] THEMultipeerSession init,ialized peer Apple-Iphone6-1_PT7748
2015-12-09 15:30:45.169 ThaliTest[580:432243] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2015-12-09T14:30:45.173Z SendDataTCPServer.js: TCP/IP server is bound to port: 52629
,2015-12-09 15:30:45.193 ThaliTest[580:432030] client: found peer: Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:45.194 ThaliTest[580:432030] client: found peer: Apple-Iphone5s-1_PT3959.Sz9P+A==
2015-12-09 15:30:45.194 ThaliTest[580:432030] client: fo,und peer: Apple-Iphone5-1_PT9641.ucdqLA==
2015-12-09 15:30:45.195 ThaliTest[580:432030] client: found peer: Apple-Iphone6-1_PT7748.MiTYRw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9197.sabYWA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09T14:30:45.199Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09T14:30:45.200Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09T14:30:45.200Z SendDataConnector.js: do connect now
2015-12-09 15:30:45.200 ThaliTest[580:432243] jxcore: connect Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:45.201 ThaliTest[580:432243] client session: connect
,2015-12-09 15:30:45.201 ThaliTest[580:432243] client session: stateChange:0->1 Apple-IpadAir2-1_PT9197.sabYWA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3959.Sz9P+A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9641.ucdqLA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7748.MiTYRw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-09 15:30:46.329 ThaliTest[580:432030] client: lost peer: Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:46.330 ThaliTest[580:432030] client session: onPeerLost: Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:46.330 ThaliTest[580:432030] cli,ent session: onLinkFailure: Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:30:46.331 ThaliTest[580:432030] client session: disconnect
,2015-12-09 15:30:46.331 ThaliTest[580:432030] client session: stateChange:1->0 Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:46.333 ThaliTest[580:432030] client session: fireConnectCallback: Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:46.334 Th,aliTest[580:432030] jxcore: connect: fail: Peer disconnected
2015-12-09 15:30:46.334 ThaliTest[580:432030] client: lost peer: Apple-Iphone5s-1_PT3959.Sz9P+A==
2015-12-09 15:30:46.334 ThaliTest[580:432030] client session: onPeerLost: Apple-Iphone5s-1_PT39,59.Sz9P+A==
2015-12-09 15:30:46.335 ThaliTest[580:432030] client: lost peer: Apple-Iphone5-1_PT9641.ucdqLA==
2015-12-09 15:30:46.335 ThaliTest[580:432030] client session: onPeerLost: Apple-Iphone5-1_PT9641.ucdqLA==
2015-12-09 15:30:46.335 ThaliTest[580:,432030] client: lost peer: Apple-Iphone6-1_PT7748.MiTYRw==
2015-12-09 15:30:46.336 ThaliTest[580:432030] client session: onPeerLost: Apple-Iphone6-1_PT7748.MiTYRw==
2015-12-09T14:30:46.337Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconn,ected
2015-12-09T14:30:46.340Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-09T14:30:46.341Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9197.sabYWA==","peerName,":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3959.Sz9P+A==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-,1_PT9641.ucdqLA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7748.MiTYRw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-09 15:30:46.408 ThaliTest[580:432030] client: found peer: Apple-Iphone5s-1_PT3959.ieNWQg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3959.ieNWQg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-09 15:30:46.498 ThaliTest[580:432030] client: found peer: Apple-IpadAir2-1_PT9197.46F2bw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9197.46F2bw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-09 15:30:46.865 ThaliTest[580:432030] client: found peer: Apple-Iphone5-1_PT9641.4z6eyA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9641.4z6eyA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-09T14:30:51.353Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09T14:30:51.354Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:30:56.362 ThaliTest[580:432243] jxcore: disconnect
2015-12-09 15:30:56.363 ThaliTest[580:432243] jxcore: disconnect: fail
2015-12-09T14:30:56.363Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9197.sabYWA==,
2015-12-09T14:30:56.364Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT9197.sabYWA== with availability status: true
2015-12-09T14:30:56.364Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09T14:30:56.364Z SendDataConnector.js: do connect now
,2015-12-09 15:30:56.366 ThaliTest[580:432243] jxcore: connect Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:30:56.367 ThaliTest[580:432243] client: connect: unreachable Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:56.367 ThaliTest[580:432243] jxcore: connect: fail: Peer unreachable
2015-12-09T14:30:56.368Z SendDataConnector.js: CLIENT connec,ted to 0, error: Peer unreachable
2015-12-09T14:30:56.368Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-09T14:30:56.368Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-09T14:31:01.373Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09T14:31:01.374Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:31:06.384 ThaliTest[580:432243] jxcore: disconnect
2015-12-09 15:31:06.385 ThaliTest[580:432243] jxcore: disconnect: fail
2015-12-09T14:31:06.385Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9197.sabYWA==,
2015-12-09T14:31:06.386Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT9197.sabYWA== with availability status: true
2015-12-09T14:31:06.386Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09T14:31:06.387Z SendDataConnector.js: do connect now
,2015-12-09 15:31:06.388 ThaliTest[580:432243] jxcore: connect Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:31:06.390 ThaliTest[580:432243] client: connect: unreachable Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:31:06.390 ThaliTest[580:432243] jxcore: connect: fail: Peer unreachable
2015-12-09T14:31:06.390Z SendDataConnector.js: CLIENT connec,ted to 0, error: Peer unreachable
2015-12-09T14:31:06.391Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-09T14:31:06.391Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-09T14:31:11.394Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09T14:31:11.394Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:31:15.171 ThaliTest[580:432030] multipeer session: restart
,2015-12-09 15:31:16.399 ThaliTest[580:432243] jxcore: disconnect
2015-12-09 15:31:16.400 ThaliTest[580:432243] jxcore: disconnect: fail
2015-12-09T14:31:16.401Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9197.sabYWA==,
2015-12-09T14:31:16.401Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT9197.sabYWA== with availability status: true
2015-12-09T14:31:16.401Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9197.sabYWA==
20,15-12-09T14:31:16.401Z SendDataConnector.js: do connect now
,2015-12-09 15:31:16.402 ThaliTest[580:432243] jxcore: connect Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:31:16.404 ThaliTest[580:432243] client: connect: unreachable Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:31:16.404 ThaliTest[580:432243] jxcore: connect: fail: Peer unreachable
2015-12-09T14:31:16.405Z SendDataConnector.js: CLIENT connec,ted to 0, error: Peer unreachable
2015-12-09T14:31:16.405Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-09T14:31:16.406Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-09T14:31:21.406Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09T14:31:21.407Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:31:26.418 ThaliTest[580:432243] jxcore: disconnect
2015-12-09 15:31:26.418 ThaliTest[580:432243] jxcore: disconnect: fail
2015-12-09T14:31:26.419Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9197.sabYWA==,
2015-12-09T14:31:26.419Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT9197.sabYWA== with availability status: true
2015-12-09T14:31:26.419Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9197.sabYWA==
20,15-12-09T14:31:26.420Z SendDataConnector.js: do connect now
,2015-12-09 15:31:26.420 ThaliTest[580:432243] jxcore: connect Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:31:26.421 ThaliTest[580:432243] client: connect: unreachable Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:31:26.422 ThaliTest[580:432243] jxcore: connect: fail: Peer unreachable
2015-12-09T14:31:26.423Z SendDataConnector.js: CLIENT connec,ted to 0, error: Peer unreachable
2015-12-09T14:31:26.423Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2015-12-09T14:31:26.426Z SendDataConnector.js: CLIENT Stop now
,2015-12-09 15:31:26.427 ThaliTest[580:432243] jxcore: disconnect
2015-12-09 15:31:26.428 ThaliTest[580:432243] jxcore: disconnect: fail
2015-12-09T14:31:26.428Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9197.sabYWA==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09T14:31:26.433Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09T14:31:26.433Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09T14:31:26.434Z SendDataConnector.js: do connect now
,2015-12-09 15:31:26.436 ThaliTest[580:432243] jxcore: connect Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:31:26.436 ThaliTest[580:432243] client session: connect
2015-12-09 15:31:26.436 ThaliTest[580:432243] client session: stateChange:0->1 Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:31:26.449 ThaliTest[580:432030] client: lost peer: Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:31:26.449 ThaliTest[580:432030] client session: onPeerLost: Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:31:26.450 ThaliTest[580:432030] cli,ent session: onLinkFailure: Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:31:26.450 ThaliTest[580:432030] client session: disconnect
2015-12-09 15:31:26.450 ThaliTest[580:432030] client session: stateChange:1->0 Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:31:26.505 ThaliTest[580:432030] client session: fireConnectCallback: Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:31:26.505 ThaliTest[580:432030] jxcore: connect: fail: Peer disconnected
2015-12-09T14:31:26.506Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-09T14:31:26.507Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-09T14:31:26.507Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3959.ieNWQg==","peerName":"(null)","peerAvailable":false}]
,2015-12-09 15:31:26.786 ThaliTest[580:432030] multipeer session: reset timer
2015-12-09 15:31:26.787 ThaliTest[580:432030] multipeer session: stop timer
2015-12-09 15:31:26.787 ThaliTest[580:432030] multipeer session: start timer: 0x193f42f0
2015-12-09 15:31:26.788 ThaliTest[580:432030] server session: connect
2015-12-09 15:31:26.788 ThaliTest[580:432030] server session: stateChange:0->1 Apple-Iphone5s-1_PT3959
,2015-12-09 15:31:26.799 ThaliTest[580:432030] server: accepting invitation Apple-Iphone5s-1_PT3959
,2015-12-09 15:31:30.424 ThaliTest[580:433163] server session: connected
2015-12-09 15:31:30.425 ThaliTest[580:433163] server session: stateChange:1->2 Apple-Iphone5s-1_PT3959
,2015-12-09 15:31:30.602 ThaliTest[580:432030] server relay: connected (to port: 52629)
,2015-12-09T14:31:30.612Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09 15:31:30.744 ThaliTest[580:432030] multipeer session: reset timer
2015-12-09 15:31:30.744 ThaliTest[580:432030] multipeer session: stop timer
2015-12-09 15:31:30.745 ThaliTest[580:432030] multipeer session: start timer: 0x193f42f0
2015-12-09 15:31:30.745 ThaliTest[580:432030] server session: connect
2015-12-09 15:31:30.745 ThaliTest[580:432030] server session: stateChange:0->1 Apple-IpadAir2-1_PT9197
,2015-12-09 15:31:30.755 ThaliTest[580:432030] server: accepting invitation Apple-IpadAir2-1_PT9197
,2015-12-09T14:31:31.387Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-09T14:31:31.404Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-09T14:31:31.422Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-09T14:31:31.435Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-09 15:31:31.511 ThaliTest[580:433165] server session: not connected Apple-Iphone5s-1_PT3959
,2015-12-09T14:31:31.520Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09T14:31:31.521Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:31:33.547 ThaliTest[580:433165] server session: connected
2015-12-09 15:31:33.548 ThaliTest[580:433165] server session: stateChange:1->2 Apple-IpadAir2-1_PT9197
,2015-12-09 15:31:33.588 ThaliTest[580:432030] server relay: connected (to port: 52629)
,2015-12-09T14:31:33.599Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09T14:31:33.803Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-09T14:31:33.815Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-09T14:31:33.833Z SendDataTCPServer.js: TCP/IP server has received 45706 bytes of data
,2015-12-09T14:31:33.849Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-09T14:31:34.004Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-09T14:31:34.017Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-09 15:31:34.071 ThaliTest[580:432833] server session: not connected Apple-IpadAir2-1_PT9197
,2015-12-09 15:31:36.524 ThaliTest[580:432243] jxcore: disconnect
2015-12-09 15:31:36.525 ThaliTest[580:432243] jxcore: disconnect: fail
2015-12-09T14:31:36.525Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT3959.ieNWQg==,
2015-12-09T14:31:36.526Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT3959.ieNWQg== with availability status: true
2015-12-09T14:31:36.526Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09T14:31:36.526Z SendDataConnector.js: do connect now
2015-12-09 15:31:36.527 ThaliTest[580:432243] jxcore: connect Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:31:36.528 ThaliTest[580:432243] client: connect: unreachable Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:31:36.529 ThaliTest[580:432243] jxcore: connect: fail: Peer unreachable
2015-12-09T14:31:36.529Z SendDataConnector.js: CLIENT connec,ted to 0, error: Peer unreachable
2015-12-09T14:31:36.530Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-09T14:31:36.530Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-09T14:31:41.535Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09T14:31:41.536Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:31:46.540 ThaliTest[580:432243] jxcore: disconnect
2015-12-09 15:31:46.541 ThaliTest[580:432243] jxcore: disconnect: fail
2015-12-09T14:31:46.541Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT3959.ieNWQg==,
2015-12-09T14:31:46.541Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT3959.ieNWQg== with availability status: true
2015-12-09T14:31:46.542Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09T14:31:46.542Z SendDataConnector.js: do connect now
2015-12-09 15:31:46.543 ThaliTest[580:432243] jxcore: connect Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:31:46.544 ThaliTest[580:432243] client: connect: unreachable Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:31:46.544 ThaliTest[580:432243] jxcore: connect: fail: Peer unreachable
2015-12-09T14:31:46.545Z SendDataConnector.js: CLIENT connec,ted to 0, error: Peer unreachable
2015-12-09T14:31:46.545Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-09T14:31:46.545Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-09T14:31:51.554Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09T14:31:51.555Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:31:56.564 ThaliTest[580:432243] jxcore: disconnect
2015-12-09 15:31:56.564 ThaliTest[580:432243] jxcore: disconnect: fail
2015-12-09T14:31:56.565Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT3959.ieNWQg==,
2015-12-09T14:31:56.565Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT3959.ieNWQg== with availability status: true
2015-12-09T14:31:56.566Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09T14:31:56.566Z SendDataConnector.js: do connect now
,2015-12-09 15:31:56.567 ThaliTest[580:432243] jxcore: connect Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:31:56.568 ThaliTest[580:432243] client: connect: unreachable Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:31:56.569 ThaliTest[580:432243] jxcore: connect: fail: Peer unreachable
2015-12-09T14:31:56.569Z SendDataConnector.js: CLIENT connec,ted to 0, error: Peer unreachable
2015-12-09T14:31:56.569Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-09T14:31:56.570Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-09 15:32:00.746 ThaliTest[580:432030] multipeer session: restart
,2015-12-09 15:32:00.783 ThaliTest[580:432030] client: found peer: Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:32:00.785 ThaliTest[580:432030] client: found peer: Apple-Iphone5-1_PT9641.4z6eyA==
2015-12-09 15:32:00.786 ThaliTest[580:432030] client: found peer: Apple-IpadAir2-1_PT9197.46F2bw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3959.ieNWQg==","peerName":"(null)","peerAvailable":true}]
,2015-12-09T14:32:01.580Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09T14:32:01.582Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:32:06.585 ThaliTest[580:432243] jxcore: disconnect
2015-12-09 15:32:06.586 ThaliTest[580:432243] jxcore: disconnect: fail
2015-12-09T14:32:06.586Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT3959.ieNWQg==,
2015-12-09T14:32:06.587Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT3959.ieNWQg== with availability status: true
2015-12-09T14:32:06.587Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT3959.ieNWQg==
20,15-12-09T14:32:06.587Z SendDataConnector.js: do connect now
,2015-12-09 15:32:06.588 ThaliTest[580:432243] jxcore: connect Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:32:06.589 ThaliTest[580:432243] client session: connect
2015-12-09 15:32:06.590 ThaliTest[580:432243] client session: stateChange:0->1 Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:32:10.703 ThaliTest[580:433243] client session: connected
2015-12-09 15:32:10.703 ThaliTest[580:433243] client session: stateChange:1->2 Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:32:10.756 ThaliTest[580:433167] client session: fireConnectCallback: Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:32:10.757 ThaliTest[580:433167] jxcore: connect: success
2015-12-09T14:32:10.758Z SendDataConnector.js: CLIENT connected to 52644, error: null
2015-12-09T14:32:10.758Z SendDataConnector.js: CLIENT starting client 
,2015-12-09 15:32:10.761 ThaliTest[580:432030] client: relay established
2015-12-09 15:32:10.762 ThaliTest[580:432030] client: new accepted socket: 0x1936bee0
,2015-12-09T14:32:10.778Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-09T14:32:11.291Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-09T14:32:11.303Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-09T14:32:11.316Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-09T14:32:11.330Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-09T14:32:11.342Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-09T14:32:11.342Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-09T14:32:11.342Z SendDataConnector.js: CLIENT Stop now
,2015-12-09T14:32:11.343Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-09 15:32:11.344 ThaliTest[580:432243] jxcore: disconnect
,2015-12-09 15:32:11.344 ThaliTest[580:432243] client session: disconnectFromPeer: Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:32:11.345 ThaliTest[580:432243] client session: disconnect
,2015-12-09 15:32:11.345 ThaliTest[580:432243] client session: stateChange:2->0 Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:32:11.411 ThaliTest[580:432243] jxcore: disconnect: success
2015-12-09T14:32:11.411Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT3959.ieNWQg==
---- round done--------
startWithNextDevice
device[3]: Apple-IpadAir2-1_PT9197.46F2bw==
,2015-12-09T14:32:11.412Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT9197.46F2bw==
2015-12-09T14:32:11.412Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9197.46F2bw==
,2015-12-09T14:32:11.412Z SendDataConnector.js: do connect now
,2015-12-09 15:32:11.413 ThaliTest[580:432243] jxcore: connect Apple-IpadAir2-1_PT9197.46F2bw==
2015-12-09 15:32:11.413 ThaliTest[580:432243] client session: connect
2015-12-09 15:32:11.413 ThaliTest[580:432243] client session: stateChange:0->1 Apple-IpadAir2-1_PT9197.46F2bw==
,2015-12-09 15:32:11.738 ThaliTest[580:432030] multipeer session: reset timer
2015-12-09 15:32:11.738 ThaliTest[580:432030] multipeer session: stop timer
2015-12-09 15:32:11.739 ThaliTest[580:432030] multipeer session: start timer: 0x193f42f0
2015-12-09 ,15:32:11.739 ThaliTest[580:432030] server session: connect
2015-12-09 15:32:11.739 ThaliTest[580:432030] server session: stateChange:0->1 Apple-Iphone5-1_PT9641
2015-12-09 15:32:11.748 ThaliTest[580:432030] server: accepting invitation Apple-Iphone5-1_PT9641
,2015-12-09 15:32:14.405 ThaliTest[580:433244] client session: connected
2015-12-09 15:32:14.405 ThaliTest[580:433244] client session: stateChange:1->2 Apple-IpadAir2-1_PT9197.46F2bw==
2015-12-09 15:32:14.408 ThaliTest[580:433244] client session: fireConnectCallback: Apple-IpadAir2-1_PT9197.46F2bw==
,2015-12-09 15:32:14.408 ThaliTest[580:433244] jxcore: connect: success
2015-12-09T14:32:14.411Z SendDataConnector.js: CLIENT connected to 52648, error: null
2015-12-09T14:32:14.411Z SendDataConnector.js: CLIENT starting client 
2015-12-09 15:32:14.416 ThaliTest[580:432030] client: relay established
2015-12-09 15:32:14.416 ThaliTest[580:432030] client: new accepted socket: 0x194bcb50
,2015-12-09T14:32:14.428Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-09T14:32:14.691Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-09T14:32:14.717Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-09T14:32:14.741Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-09T14:32:14.742Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-09T14:32:14.742Z SendDataConnector.js: CLIENT Stop now
2015-12-09T14:32:14.742Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-09 15:32:14.743 ThaliTest[580:432243] jxcore: disconnect
,2015-12-09 15:32:14.743 ThaliTest[580:432243] client session: disconnectFromPeer: Apple-IpadAir2-1_PT9197.46F2bw==
,2015-12-09 15:32:14.744 ThaliTest[580:432243] client session: disconnect
,2015-12-09 15:32:14.744 ThaliTest[580:432243] client session: stateChange:2->0 Apple-IpadAir2-1_PT9197.46F2bw==
,2015-12-09 15:32:14.807 ThaliTest[580:432243] jxcore: disconnect: success
,2015-12-09T14:32:14.808Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9197.46F2bw==
---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone5-1_PT9641.4z6eyA==
,2015-12-09T14:32:14.809Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9641.4z6eyA==
,2015-12-09T14:32:14.809Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9641.4z6eyA==
,2015-12-09T14:32:14.809Z SendDataConnector.js: do connect now
,2015-12-09 15:32:14.810 ThaliTest[580:432243] jxcore: connect Apple-Iphone5-1_PT9641.4z6eyA==
,2015-12-09 15:32:14.810 ThaliTest[580:432243] client session: connect
,2015-12-09 15:32:14.811 ThaliTest[580:432243] client session: stateChange:0->1 Apple-Iphone5-1_PT9641.4z6eyA==
,2015-12-09 15:32:19.149 ThaliTest[580:433339] server session: connected
2015-12-09 15:32:19.152 ThaliTest[580:433339] server session: stateChange:1->2 Apple-Iphone5-1_PT9641
,2015-12-09 15:32:19.217 ThaliTest[580:432030] server relay: connected (to port: 52629)
,2015-12-09T14:32:19.225Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09T14:32:19.728Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-09T14:32:19.741Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-09T14:32:19.759Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-09T14:32:19.773Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-09T14:32:19.788Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-09T14:32:19.801Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-09T14:32:19.816Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-09 15:32:19.920 ThaliTest[580:433243] server session: not connected Apple-Iphone5-1_PT9641
,2015-12-09 15:32:21.766 ThaliTest[580:433340] client session: connected
,2015-12-09 15:32:21.766 ThaliTest[580:433340] client session: stateChange:1->2 Apple-Iphone5-1_PT9641.4z6eyA==
,2015-12-09 15:32:21.791 ThaliTest[580:433243] client session: fireConnectCallback: Apple-Iphone5-1_PT9641.4z6eyA==
2015-12-09 15:32:21.791 ThaliTest[580:433243] jxcore: connect: success
2015-12-09T14:32:21.792Z SendDataConnector.js: CLIENT connected to 52652, error: null
2015-12-09T14:32:21.793Z SendDataConnector.js: CLIENT starting client 
,2015-12-09 15:32:21.798 ThaliTest[580:432030] client: relay established
2015-12-09 15:32:21.798 ThaliTest[580:432030] client: new accepted socket: 0x19355d60
,2015-12-09T14:32:21.809Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-09T14:32:22.243Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-09T14:32:22.256Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-09T14:32:22.292Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-09T14:32:22.292Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-09T14:32:22.293Z SendDataConnector.js: CLIENT Stop now
2015-12-09T14:32:22.293Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-09 15:32:22.294 ThaliTest[580:432243] jxcore: disconnect
,2015-12-09 15:32:22.295 ThaliTest[580:432243] client session: disconnectFromPeer: Apple-Iphone5-1_PT9641.4z6eyA==
,2015-12-09 15:32:22.295 ThaliTest[580:432243] client session: disconnect
,2015-12-09 15:32:22.296 ThaliTest[580:432243] client session: stateChange:2->0 Apple-Iphone5-1_PT9641.4z6eyA==
,2015-12-09 15:32:22.368 ThaliTest[580:432243] jxcore: disconnect: success
,2015-12-09T14:32:22.370Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9641.4z6eyA==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2015-12-09T14:32:22.376Z SendDataConnector.js: CLIENT Stop now
2015-12-09T14:32:22.376Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
2015-12-09 15:32:28.000 ThaliTest[580:432243] jxcore: stopBroadcasting
,2015-12-09 15:32:28.000 ThaliTest[580:432243] THEMultipeerSession stopping peer
,2015-12-09 15:32:28.001 ThaliTest[580:432243] multipeer session: stop timer
,2015-12-09 15:32:28.002 ThaliTest[580:432243] server session: disconnect
2015-12-09 15:32:28.003 ThaliTest[580:432243] server session: stateChange:2->0 Apple-Iphone5s-1_PT3959
,2015-12-09 15:32:28.073 ThaliTest[580:432243] server session: disconnect
2015-12-09 15:32:28.073 ThaliTest[580:432243] server session: stateChange:2->0 Apple-IpadAir2-1_PT9197
2015-12-09 15:32:28.076 ThaliTest[580:432243] server session: disconnect
2015-12-09 15:32:28.076 ThaliTest[580:432243] server session: stateChange:2->0 Apple-Iphone5-1_PT9641
,2015-12-09 15:32:28.144 ThaliTest[580:432243] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-09T14:32:28.161Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-09T14:32:28.162Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-09T14:32:28.163Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-09T14:32:28.164Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
