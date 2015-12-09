#### Test 50650278b28a87a_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278b28a87a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/C8612973-5B3C-4C72-85B1-FAC6575BB324/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/C8612973-5B3C-4C72-85B1-FAC6575BB324/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278b28a87a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278b28a87a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/03342D68-F4C3-4B29-B460-CAB32D2208FB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52141"
,(lldb)     command script import "/tmp/C8612973-5B3C-4C72-85B1-FAC6575BB324/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-09 15:25:27.604 ThaliTest[591:432379] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0040F38D-2E63-467D-A175-FF9361A382AE/Library/Cookies/Cookies.binarycookies
,2015-12-09 15:25:28.014 ThaliTest[591:432379] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-09 15:25:28.015 ThaliTest[591:432379] Multi-tasking -> Device: YES, App: YES
,2015-12-09 15:25:28.026 ThaliTest[591:432379] Unlimited access to network resources
,2015-12-09 15:25:28.042 ThaliTest[591:432379] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-09 15:25:37.219 ThaliTest[591:432379] Resetting plugins due to page load.
,2015-12-09 15:25:40.365 ThaliTest[591:432379] Finished load of: file:///var/mobile/Containers/Bundle/Application/03342D68-F4C3-4B29-B460-CAB32D2208FB/ThaliTest.app/www/index.html
,2015-12-09 15:25:40.573 ThaliTest[591:432379] JXcore Cordova plugin initializing
,2015-12-09 15:25:40.574 ThaliTest[591:432598] JXcore instance initializing
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
,2015-12-09 15:25:41.867 ThaliTest[591:432379] THREAD WARNING: ['JXcore'] took '89.975830' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-09 15:30:42.475 ThaliTest[591:432598] jxcore: startBroadcasting
,2015-12-09 15:30:42.494 ThaliTest[591:432598] server: starting Apple-Iphone5s-1_PT3959.Sz9P+A==
2015-12-09 15:30:42.495 ThaliTest[591:432598] multipeer session: start timer: 0x18c97210
,2015-12-09 15:30:42.496 ThaliTest[591:432598] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT3959
2015-12-09 15:30:42.496 ThaliTest[591:432598] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-09 15:30:44.384 ThaliTest[591:432379] client: found peer: Apple-Iphone5-1_PT9641.ucdqLA==
2015-12-09 15:30:44.385 ThaliTest[591:432379] client: found peer: Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:44.386 ThaliTest[591:432379] client: fou,nd peer: Apple-Iphone6-1_PT7748.MiTYRw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9641.ucdqLA==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5-1_PT9641.ucdqLA==, peerAvailable: true
weAreDoneNow
done, now se,nding data to server
,teardown
,testFindPeers stopped
,2015-12-09 15:30:45.073 ThaliTest[591:432598] jxcore: stopBroadcasting
2015-12-09 15:30:45.074 ThaliTest[591:432598] THEMultipeerSession stopping peer
2015-12-09 15:30:45.074 ThaliTest[591:432598] multipeer session: stop timer
2015-12-09 15:30:45.075 ThaliTest[591:432598] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"servertimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 52816
,2015-12-09 15:30:45.164 ThaliTest[591:432598] jxcore: startBroadcasting
,2015-12-09 15:30:45.167 ThaliTest[591:432598] server: starting Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:30:45.167 ThaliTest[591:432598] multipeer session: start timer: 0x18bcf790
2015-12-09 15:30:45.168 ThaliTest[591:432598] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT3959
2015-12-09 15:30:45.169 ThaliTest[591:432598] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
,2015-12-09T14:30:45.174Z SendDataTCPServer.js: TCP/IP server is bound to port: 52816
,2015-12-09 15:30:45.193 ThaliTest[591:432379] client: found peer: Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:45.193 ThaliTest[591:432379] client: found peer: Apple-Iphone5-1_PT9641.ucdqLA==
2015-12-09 15:30:45.195 ThaliTest[591:432379] client: found peer: Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09 15:30:45.195 ThaliTest[591:432379] client: found peer: Apple-Iphone6-1_PT7748.MiTYRw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9197.sabYWA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09T14:30:45.203Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09T14:30:45.203Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09T14:30:45.204Z SendDataConnector.js: do connect now
,2015-12-09 15:30:45.205 ThaliTest[591:432598] jxcore: connect Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:30:45.205 ThaliTest[591:432598] client session: connect
,2015-12-09 15:30:45.206 ThaliTest[591:432598] client session: stateChange:0->1 Apple-IpadAir2-1_PT9197.sabYWA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9641.ucdqLA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3959.Sz9P+A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7748.MiTYRw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-09 15:30:46.206 ThaliTest[591:432379] client: lost peer: Apple-Iphone5s-1_PT3959.Sz9P+A==
2015-12-09 15:30:46.207 ThaliTest[591:432379] client session: onPeerLost: Apple-Iphone5s-1_PT3959.Sz9P+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3959.Sz9P+A==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-09 15:30:46.283 ThaliTest[591:432379] client: lost peer: Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:46.284 ThaliTest[591:432379] client session: onPeerLost: Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:46.284 ThaliTest[591:432379] cli,ent session: onLinkFailure: Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:46.284 ThaliTest[591:432379] client session: disconnect
2015-12-09 15:30:46.285 ThaliTest[591:432379] client session: stateChange:1->0 Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:30:46.287 ThaliTest[591:432379] client session: fireConnectCallback: Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:46.288 ThaliTest[591:432379] jxcore: connect: fail: Peer disconnected
2015-12-09 15:30:46.289 ThaliTest[591:432379] clien,t: lost peer: Apple-Iphone6-1_PT7748.MiTYRw==
2015-12-09 15:30:46.289 ThaliTest[591:432379] client session: onPeerLost: Apple-Iphone6-1_PT7748.MiTYRw==
2015-12-09T14:30:46.291Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-1,2-09T14:30:46.291Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-09T14:30:46.292Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9197.sabYWA==","peerName":"(null)","p,eerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7748.MiTYRw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-09 15:30:46.313 ThaliTest[591:432379] client: lost peer: Apple-Iphone5-1_PT9641.ucdqLA==
2015-12-09 15:30:46.313 ThaliTest[591:432379] client session: onPeerLost: Apple-Iphone5-1_PT9641.ucdqLA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone5-1_PT9641.ucdqLA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-09 15:30:46.467 ThaliTest[591:432379] client: found peer: Apple-Iphone6-1_PT7748.7slvbQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7748.7slvbQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
2015-12-09 15:30:46.470 ThaliTest[591:432379] client: found peer: Apple-IpadAir2-1_PT9197.46F2bw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9197.46F2bw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-09 15:30:46.670 ThaliTest[591:432379] client: found peer: Apple-Iphone5-1_PT9641.4z6eyA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9641.4z6eyA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-09T14:30:51.298Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09T14:30:51.299Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:30:56.307 ThaliTest[591:432598] jxcore: disconnect
2015-12-09 15:30:56.307 ThaliTest[591:432598] jxcore: disconnect: fail
2015-12-09T14:30:56.308Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9197.sabYWA==,
2015-12-09T14:30:56.309Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT9197.sabYWA== with availability status: true
2015-12-09T14:30:56.309Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09T14:30:56.309Z SendDataConnector.js: do connect now
,2015-12-09 15:30:56.310 ThaliTest[591:432598] jxcore: connect Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:30:56.312 ThaliTest[591:432598] client: connect: unreachable Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:30:56.313 ThaliTest[591:432598] jxcore: connect: fail: Peer unreachable
,2015-12-09T14:30:56.314Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-09T14:30:56.315Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-09T14:30:56.315Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-09T14:31:01.321Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09T14:31:01.322Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:31:06.328 ThaliTest[591:432598] jxcore: disconnect
2015-12-09 15:31:06.329 ThaliTest[591:432598] jxcore: disconnect: fail
2015-12-09T14:31:06.329Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9197.sabYWA==,
2015-12-09T14:31:06.330Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT9197.sabYWA== with availability status: true
2015-12-09T14:31:06.330Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9197.sabYWA==
20,15-12-09T14:31:06.330Z SendDataConnector.js: do connect now
,2015-12-09 15:31:06.331 ThaliTest[591:432598] jxcore: connect Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:31:06.332 ThaliTest[591:432598] client: connect: unreachable Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:31:06.333 ThaliTest[591:432598] jxcore: connect: fail: Peer unreachable
,2015-12-09T14:31:06.334Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-09T14:31:06.335Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-09T14:31:06.335Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-09T14:31:11.346Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09T14:31:11.347Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:31:15.169 ThaliTest[591:432379] multipeer session: restart
,2015-12-09 15:31:15.226 ThaliTest[591:432379] client: found peer: Apple-Iphone6-1_PT7748.7slvbQ==
2015-12-09 15:31:15.230 ThaliTest[591:432379] client: found peer: Apple-IpadAir2-1_PT9197.46F2bw==
2015-12-09 15:31:15.231 ThaliTest[591:432379] client: fou,nd peer: Apple-Iphone5-1_PT9641.4z6eyA==
,2015-12-09 15:31:16.350 ThaliTest[591:432598] jxcore: disconnect
2015-12-09 15:31:16.350 ThaliTest[591:432598] jxcore: disconnect: fail
2015-12-09T14:31:16.351Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9197.sabYWA==,
2015-12-09T14:31:16.351Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT9197.sabYWA== with availability status: true
2015-12-09T14:31:16.352Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9197.sabYWA==
20,15-12-09T14:31:16.352Z SendDataConnector.js: do connect now
,2015-12-09 15:31:16.353 ThaliTest[591:432598] jxcore: connect Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:31:16.354 ThaliTest[591:432598] client: connect: unreachable Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:31:16.354 ThaliTest[591:432598] jxcor,e: connect: fail: Peer unreachable
,2015-12-09T14:31:16.355Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-09T14:31:16.356Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-09T14:31:16.357Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-09T14:31:21.360Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09T14:31:21.361Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:31:26.363 ThaliTest[591:432598] jxcore: disconnect
2015-12-09 15:31:26.363 ThaliTest[591:432598] jxcore: disconnect: fail
2015-12-09T14:31:26.364Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9197.sabYWA==,
2015-12-09T14:31:26.364Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT9197.sabYWA== with availability status: true
2015-12-09T14:31:26.365Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09T14:31:26.365Z SendDataConnector.js: do connect now
2015-12-09 15:31:26.366 ThaliTest[591:432598] jxcore: connect Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:31:26.367 ThaliTest[591:432598] client: connect: unreachable Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:31:26.368 ThaliTest[591:432598] jxcore: connect: fail: Peer unreachable
2015-12-09T14:31:26.369Z SendDataConnector.js: CLIENT connec,ted to 0, error: Peer unreachable
2015-12-09T14:31:26.369Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2015-12-09T14:31:26.372Z SendDataConnector.js: CLIENT Stop now
,2015-12-09 15:31:26.374 ThaliTest[591:432598] jxcore: disconnect
,2015-12-09 15:31:26.375 ThaliTest[591:432598] jxcore: disconnect: fail
2015-12-09T14:31:26.376Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9197.sabYWA==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone6-1_PT7748.7slvbQ==
,2015-12-09T14:31:26.380Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7748.7slvbQ==
,2015-12-09T14:31:26.380Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7748.7slvbQ==
,2015-12-09T14:31:26.381Z SendDataConnector.js: do connect now
,2015-12-09 15:31:26.382 ThaliTest[591:432598] jxcore: connect Apple-Iphone6-1_PT7748.7slvbQ==
2015-12-09 15:31:26.383 ThaliTest[591:432598] client session: connect
2015-12-09 15:31:26.383 ThaliTest[591:432598] client session: stateChange:0->1 Apple-Iphon,e6-1_PT7748.7slvbQ==
,2015-12-09 15:31:26.768 ThaliTest[591:432379] multipeer session: reset timer
2015-12-09 15:31:26.768 ThaliTest[591:432379] multipeer session: stop timer
2015-12-09 15:31:26.769 ThaliTest[591:432379] multipeer session: start timer: 0x18bcf790
2015-12-09 15:31:26.769 ThaliTest[591:432379] server session: connect
2015-12-09 15:31:26.770 ThaliTest[591:432379] server session: stateChange:0->1 Apple-IpadAir2-1_PT9197
,2015-12-09 15:31:26.781 ThaliTest[591:432379] server: accepting invitation Apple-IpadAir2-1_PT9197
,2015-12-09 15:31:29.847 ThaliTest[591:433218] server session: connected
2015-12-09 15:31:29.847 ThaliTest[591:433218] server session: stateChange:1->2 Apple-IpadAir2-1_PT9197
,2015-12-09 15:31:29.858 ThaliTest[591:432379] server relay: connected (to port: 52816)
,2015-12-09T14:31:29.869Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09T14:31:30.398Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-09T14:31:30.417Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-09T14:31:30.433Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-09T14:31:30.449Z SendDataTCPServer.js: TCP/IP server has received 86808 bytes of data
,2015-12-09T14:31:30.470Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-09 15:31:30.557 ThaliTest[591:433235] client session: connected
2015-12-09 15:31:30.557 ThaliTest[591:433235] client session: stateChange:1->2 Apple-Iphone6-1_PT7748.7slvbQ==
,2015-12-09 15:31:30.818 ThaliTest[591:433214] client session: fireConnectCallback: Apple-Iphone6-1_PT7748.7slvbQ==
2015-12-09 15:31:30.818 ThaliTest[591:433214] jxcore: connect: success
2015-12-09T14:31:30.821Z SendDataConnector.js: CLIENT connected to 52822, error: null
2015-12-09T14:31:30.821Z SendDataConnector.js: CLIENT starting client 
,2015-12-09 15:31:30.826 ThaliTest[591:432379] client: relay established
2015-12-09 15:31:30.826 ThaliTest[591:432379] client: new accepted socket: 0x18be32f0
,2015-12-09T14:31:30.842Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-09T14:31:31.395Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-09T14:31:31.406Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-09T14:31:31.420Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-09T14:31:31.420Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-09T14:31:31.421Z SendDataConnector.js: CLIENT Stop now
2015-12-09T14:31:31.421Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-09 15:31:31.422 ThaliTest[591:432598] jxcore: disconnect
2015-12-09 15:31:31.422 ThaliTest[591:432598] client session: disconnectFromPeer: Apple-Iphone6-1_PT7748.7slvbQ==
2015-12-09 15:31:31.423 ThaliTest[591:432598] client session: disconnect
2,015-12-09 15:31:31.423 ThaliTest[591:432598] client session: stateChange:2->0 Apple-Iphone6-1_PT7748.7slvbQ==
,2015-12-09 15:31:31.428 ThaliTest[591:432598] jxcore: disconnect: success
2015-12-09T14:31:31.429Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7748.7slvbQ==
---- round done--------
startWithNextDevice
device[3]: Apple,-IpadAir2-1_PT9197.46F2bw==
2015-12-09T14:31:31.429Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT9197.46F2bw==
2015-12-09T14:31:31.430Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9197.46F2bw==
2015-12-09T14:31:31.430Z SendDataConnector.js: do connect now
,2015-12-09 15:31:31.432 ThaliTest[591:432598] jxcore: connect Apple-IpadAir2-1_PT9197.46F2bw==
2015-12-09 15:31:31.433 ThaliTest[591:432598] client session: connect
2015-12-09 15:31:31.433 ThaliTest[591:432598] client session: stateChange:0->1 Apple-IpadAir2-1_PT9197.46F2bw==
,2015-12-09 15:31:34.704 ThaliTest[591:433235] client session: connected
2015-12-09 15:31:34.704 ThaliTest[591:433235] client session: stateChange:1->2 Apple-IpadAir2-1_PT9197.46F2bw==
,2015-12-09 15:31:34.714 ThaliTest[591:433235] client session: fireConnectCallback: Apple-IpadAir2-1_PT9197.46F2bw==
2015-12-09 15:31:34.715 ThaliTest[591:433235] jxcore: connect: success
2015-12-09T14:31:34.716Z SendDataConnector.js: CLIENT connected to ,52825, error: null
2015-12-09T14:31:34.716Z SendDataConnector.js: CLIENT starting client 
,2015-12-09 15:31:34.721 ThaliTest[591:432379] client: relay established
2015-12-09 15:31:34.721 ThaliTest[591:432379] client: new accepted socket: 0x18caf750
,2015-12-09T14:31:34.735Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-09T14:31:35.058Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-09T14:31:35.071Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-09T14:31:35.107Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-09T14:31:35.108Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-09T14:31:35.108Z SendDataConnector.js: CLIENT Stop now
2015-12-09T14:31:35.109Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-09 15:31:35.109 ThaliTest[591:432598] jxcore: disconnect
2015-12-09 15:31:35.109 ThaliTest[591:432598] client session: disconnectFromPeer: Apple-IpadAir2-1_PT9197.46F2bw==
2015-12-09 15:31:35.109 ThaliTest[591:432598] client session: disconnect
2015-12-09 15:31:35.110 ThaliTest[591:432598] client session: stateChange:2->0 Apple-IpadAir2-1_PT9197.46F2bw==
,2015-12-09 15:31:35.114 ThaliTest[591:432598] jxcore: disconnect: success
2015-12-09T14:31:35.116Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9197.46F2bw==
---- round done--------
startWithNextDevice
,device[4]: Apple-Iphone5-1_PT9641.4z6eyA==
2015-12-09T14:31:35.117Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9641.4z6eyA==
2015-12-09T14:31:35.117Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9641.4z6eyA==
20,15-12-09T14:31:35.117Z SendDataConnector.js: do connect now
2015-12-09 15:31:35.117 ThaliTest[591:432598] jxcore: connect Apple-Iphone5-1_PT9641.4z6eyA==
2015-12-09 15:31:35.117 ThaliTest[591:432598] client session: connect
2015-12-09 15:31:35.117 ThaliTest[591:432598] client session: stateChange:0->1 Apple-Iphone5-1_PT9641.4z6eyA==
,2015-12-09 15:31:38.753 ThaliTest[591:433218] client session: connected
2015-12-09 15:31:38.753 ThaliTest[591:433218] client session: stateChange:1->2 Apple-Iphone5-1_PT9641.4z6eyA==
,2015-12-09 15:31:38.764 ThaliTest[591:433218] client session: fireConnectCallback: Apple-Iphone5-1_PT9641.4z6eyA==
2015-12-09 15:31:38.765 ThaliTest[591:433218] jxcore: connect: success
2015-12-09T14:31:38.766Z SendDataConnector.js: CLIENT connected to 52828, error: null
2015-12-09T14:31:38.766Z SendDataConnector.js: CLIENT starting client 
,2015-12-09 15:31:38.771 ThaliTest[591:432379] client: relay established
2015-12-09 15:31:38.771 ThaliTest[591:432379] client: new accepted socket: 0x18bdc470
,2015-12-09T14:31:38.784Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-09T14:31:39.150Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-09T14:31:39.337Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-09T14:31:39.338Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-09T14:31:39.338Z SendDataConnector.js: CLIENT Stop now
2015-12-09T14:31:39.338Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-09 15:31:39.339 ThaliTest[591:432598] jxcore: disconnect
2015-12-09 15:31:39.339 ThaliTest[591:432598] client session: disconnectFromPeer: Apple-Iphone5-1_PT9641.4z6eyA==
2015-12-09 15:31:39.339 ThaliTest[591:432598] client session: disconnect
2015-12-09 15:31:39.339 ThaliTest[591:432598] client session: stateChange:2->0 Apple-Iphone5-1_PT9641.4z6eyA==
,2015-12-09 15:31:39.347 ThaliTest[591:432598] jxcore: disconnect: success
2015-12-09T14:31:39.348Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9641.4z6eyA==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
,2015-12-09T14:31:39.351Z SendDataConnector.js: CLIENT Stop now
2015-12-09T14:31:39.351Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-09 15:31:41.546 ThaliTest[591:433235] server session: not connected Apple-IpadAir2-1_PT9197
,2015-12-09 15:31:56.770 ThaliTest[591:432379] multipeer session: restart
,2015-12-09 15:31:56.832 ThaliTest[591:432379] client: found peer: Apple-Iphone6-1_PT7748.7slvbQ==
2015-12-09 15:31:56.832 ThaliTest[591:432379] client: found peer: Apple-IpadAir2-1_PT9197.46F2bw==
,2015-12-09 15:31:56.833 ThaliTest[591:432379] client: found peer: Apple-Iphone5-1_PT9641.4z6eyA==
,2015-12-09 15:32:07.189 ThaliTest[591:432379] multipeer session: reset timer
2015-12-09 15:32:07.189 ThaliTest[591:432379] multipeer session: stop timer
2015-12-09 15:32:07.190 ThaliTest[591:432379] multipeer session: start timer: 0x18bcf790
2015-12-09 ,15:32:07.190 ThaliTest[591:432379] server session: connect
2015-12-09 15:32:07.191 ThaliTest[591:432379] server session: stateChange:0->1 Apple-Iphone6-1_PT7748
,2015-12-09 15:32:07.203 ThaliTest[591:432379] server: accepting invitation Apple-Iphone6-1_PT7748
,2015-12-09 15:32:07.510 ThaliTest[591:432379] multipeer session: reset timer
2015-12-09 15:32:07.511 ThaliTest[591:432379] multipeer session: stop timer
2015-12-09 15:32:07.511 ThaliTest[591:432379] multipeer session: start timer: 0x18bcf790
2015-12-09 15:32:07.511 ThaliTest[591:432379] server session: connect
2015-12-09 15:32:07.512 ThaliTest[591:432379] server session: stateChange:0->1 Apple-Iphone5-1_PT9641
2015-12-09 15:32:07.517 ThaliTest[591:432379] server: accepting invitation Apple-Iphone5-1_PT9641
,2015-12-09 15:32:10.442 ThaliTest[591:433327] server session: connected
2015-12-09 15:32:10.442 ThaliTest[591:433327] server session: stateChange:1->2 Apple-Iphone5-1_PT9641
,2015-12-09 15:32:10.448 ThaliTest[591:432379] server relay: connected (to port: 52816)
2015-12-09T14:32:10.458Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09 15:32:10.673 ThaliTest[591:433327] server session: connected
2015-12-09 15:32:10.673 ThaliTest[591:433327] server session: stateChange:1->2 Apple-Iphone6-1_PT7748
,2015-12-09 15:32:10.692 ThaliTest[591:432379] server relay: connected (to port: 52816)
,2015-12-09T14:32:10.700Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09T14:32:10.976Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-09T14:32:10.992Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-09T14:32:11.008Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-09T14:32:11.189Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-09T14:32:11.209Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-09T14:32:11.219Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-09T14:32:11.242Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-09T14:32:11.245Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-09T14:32:11.280Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-09T14:32:11.299Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-09T14:32:11.302Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-09T14:32:11.315Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-09 15:32:11.447 ThaliTest[591:433324] server session: not connected Apple-Iphone5-1_PT9641
,2015-12-09 15:32:22.448 ThaliTest[591:433445] server session: not connected Apple-Iphone6-1_PT7748
,appEnteredForeground wasn't registered
,teardown
,testSendData stopped
,2015-12-09 15:32:28.356 ThaliTest[591:432598] jxcore: stopBroadcasting
2015-12-09 15:32:28.356 ThaliTest[591:432598] THEMultipeerSession stopping peer
2015-12-09 15:32:28.356 ThaliTest[591:432598] multipeer session: stop timer
2015-12-09 15:32:28.357 Th,aliTest[591:432598] server session: disconnect
2015-12-09 15:32:28.357 ThaliTest[591:432598] server session: stateChange:2->0 Apple-IpadAir2-1_PT9197
2015-12-09 15:32:28.363 ThaliTest[591:432598] server session: disconnect
2015-12-09 15:32:28.363 ThaliT,est[591:432598] server session: stateChange:2->0 Apple-Iphone6-1_PT7748
,2015-12-09 15:32:28.369 ThaliTest[591:432598] server session: disconnect
2015-12-09 15:32:28.369 ThaliTest[591:432598] server session: stateChange:2->0 Apple-Iphone5-1_PT9641
,2015-12-09 15:32:28.388 ThaliTest[591:432598] jxcore: stopBroadcasting: success
StopBroadcasting went ok
2015-12-09T14:32:28.391Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-09T14:32:28.392Z SendDataTCPServer.js: TCP/IP server is ended
2015-12,-09T14:32:28.393Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-09T14:32:28.393Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
