#### Test 50650278b28a87a_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278b28a87a/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/B1F9B372-0042-4E0C-B547-4EBA8CC35DA8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B1F9B372-0042-4E0C-B547-4EBA8CC35DA8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278b28a87a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278b28a87a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0BD45136-18E0-4991-AA92-3E4C49EE5A8A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52137"
,(lldb)     command script import "/tmp/B1F9B372-0042-4E0C-B547-4EBA8CC35DA8/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-09 15:25:27.015 ThaliTest[607:425556] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/91890C5D-DD3A-4D70-814E-D0C275935C1A/Library/Cookies/Cookies.binarycookies
,2015-12-09 15:25:27.028 ThaliTest[607:425556] <CATransformLayer: 0x17e38790> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-09 15:25:27.029 ThaliTest[607:425556] <CATransformLayer: 0x17e3c0d0> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-09 15:25:27.029 ThaliTest[607:425556] <CATransformLayer: 0x17e3d220> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-09 15:25:27.323 ThaliTest[607:425556] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-09 15:25:27.324 ThaliTest[607:425556] Multi-tasking -> Device: YES, App: YES
,2015-12-09 15:25:27.332 ThaliTest[607:425556] Unlimited access to network resources
,2015-12-09 15:25:27.338 ThaliTest[607:425556] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-09 15:25:36.437 ThaliTest[607:425556] Resetting plugins due to page load.
,2015-12-09 15:25:39.462 ThaliTest[607:425556] Finished load of: file:///var/mobile/Containers/Bundle/Application/0BD45136-18E0-4991-AA92-3E4C49EE5A8A/ThaliTest.app/www/index.html
,2015-12-09 15:25:39.603 ThaliTest[607:425556] JXcore Cordova plugin initializing
,2015-12-09 15:25:39.604 ThaliTest[607:425858] JXcore instance initializing
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
,2015-12-09 15:25:40.615 ThaliTest[607:425556] THREAD WARNING: ['JXcore'] took '82.324951' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-09 15:30:43.651 ThaliTest[607:425858] jxcore: startBroadcasting
,2015-12-09 15:30:43.667 ThaliTest[607:425858] server: starting Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:30:43.669 ThaliTest[607:425858] multipeer session: start timer: 0x19b8b2f0
2015-12-09 15:30:43.669 ThaliTest[607:425858] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT9197
,2015-12-09 15:30:43.671 ThaliTest[607:425858] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-09 15:30:44.757 ThaliTest[607:425556] client: found peer: Apple-Iphone5s-1_PT3959.Sz9P+A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3959.Sz9P+A==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5s-1_PT3959.Sz9P+A==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-09 15:30:44.851 ThaliTest[607:425556] client: found peer: Apple-Iphone6-1_PT7748.MiTYRw==
,2015-12-09 15:30:45.353 ThaliTest[607:425556] client: found peer: Apple-Iphone5-1_PT9641.ucdqLA==
,teardown
,testFindPeers stopped
,2015-12-09 15:30:46.115 ThaliTest[607:425858] jxcore: stopBroadcasting
,2015-12-09 15:30:46.115 ThaliTest[607:425858] THEMultipeerSession stopping peer
,2015-12-09 15:30:46.116 ThaliTest[607:425858] multipeer session: stop timer
,2015-12-09 15:30:46.121 ThaliTest[607:425858] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"servertimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 52205
,2015-12-09 15:30:46.184 ThaliTest[607:425858] jxcore: startBroadcasting
,2015-12-09 15:30:46.186 ThaliTest[607:425858] server: starting Apple-IpadAir2-1_PT9197.46F2bw==
,2015-12-09 15:30:46.187 ThaliTest[607:425858] multipeer session: start timer: 0x17de48c0
2015-12-09 15:30:46.187 ThaliTest[607:425858] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT9197
2015-12-09 15:30:46.188 ThaliTest[607:425858] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
,2015-12-09T14:30:46.190Z SendDataTCPServer.js: TCP/IP server is bound to port: 52205
,2015-12-09 15:30:46.201 ThaliTest[607:425556] client: found peer: Apple-Iphone5s-1_PT3959.Sz9P+A==
2015-12-09 15:30:46.201 ThaliTest[607:425556] client: found peer: Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:46.202 ThaliTest[607:425556] client: found peer: Apple-Iphone6-1_PT7748.MiTYRw==
,2015-12-09 15:30:46.204 ThaliTest[607:425556] client: found peer: Apple-Iphone5-1_PT9641.ucdqLA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3959.Sz9P+A==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09T14:30:46.207Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09T14:30:46.207Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09T14:30:46.207Z SendDataConnector.js: do connect now
,2015-12-09 15:30:46.208 ThaliTest[607:425858] jxcore: connect Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09 15:30:46.208 ThaliTest[607:425858] client session: connect
,2015-12-09 15:30:46.209 ThaliTest[607:425858] client session: stateChange:0->1 Apple-Iphone5s-1_PT3959.Sz9P+A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9197.sabYWA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7748.MiTYRw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9641.ucdqLA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-09 15:30:47.366 ThaliTest[607:425556] client: lost peer: Apple-Iphone6-1_PT7748.MiTYRw==
2015-12-09 15:30:47.367 ThaliTest[607:425556] client session: onPeerLost: Apple-Iphone6-1_PT7748.MiTYRw==
2015-12-09 15:30:47.367 ThaliTest[607:425556] clien,t: lost peer: Apple-Iphone5s-1_PT3959.Sz9P+A==
2015-12-09 15:30:47.368 ThaliTest[607:425556] client session: onPeerLost: Apple-Iphone5s-1_PT3959.Sz9P+A==
2015-12-09 15:30:47.368 ThaliTest[607:425556] client session: onLinkFailure: Apple-Iphone5s-1_PT3959,.Sz9P+A==
2015-12-09 15:30:47.368 ThaliTest[607:425556] client session: disconnect
2015-12-09 15:30:47.368 ThaliTest[607:425556] client session: stateChange:1->0 Apple-Iphone5s-1_PT3959.Sz9P+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-,1_PT7748.MiTYRw==","peerName":"(null)","peerAvailable":false}]
2015-12-09 15:30:47.369 ThaliTest[607:425556] client session: fireConnectCallback: Apple-Iphone5s-1_PT3959.Sz9P+A==
Found peer : (null), Available: false
2015-12-09 15:30:47.369 ThaliTest[607:425556] jxcore: connect: fail: Peer disconnected
,2015-12-09 15:30:47.371 ThaliTest[607:425556] client: lost peer: Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:47.371 ThaliTest[607:425556] client session: onPeerLost: Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:47.372 ThaliTest[607:425556] cli,ent: lost peer: Apple-Iphone5-1_PT9641.ucdqLA==
2015-12-09 15:30:47.372 ThaliTest[607:425556] client session: onPeerLost: Apple-Iphone5-1_PT9641.ucdqLA==
,2015-12-09T14:30:47.374Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-12-09T14:30:47.374Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-09T14:30:47.376Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3959.Sz9P+A==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9197.sabYWA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9641.ucdqLA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-09 15:30:47.482 ThaliTest[607:425556] client: found peer: Apple-Iphone5s-1_PT3959.ieNWQg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3959.ieNWQg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-09 15:30:47.596 ThaliTest[607:425556] client: found peer: Apple-Iphone6-1_PT7748.7slvbQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7748.7slvbQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-09 15:30:47.931 ThaliTest[607:425556] client: found peer: Apple-Iphone5-1_PT9641.4z6eyA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9641.4z6eyA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-09T14:30:52.382Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09T14:30:52.383Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09 15:30:57.395 ThaliTest[607:425858] jxcore: disconnect
,2015-12-09 15:30:57.395 ThaliTest[607:425858] jxcore: disconnect: fail
,2015-12-09T14:30:57.397Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09T14:30:57.398Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT3959.Sz9P+A== with availability status: true
,2015-12-09T14:30:57.399Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT3959.Sz9P+A==
2015-12-09T14:30:57.399Z SendDataConnector.js: do connect now
,2015-12-09 15:30:57.401 ThaliTest[607:425858] jxcore: connect Apple-Iphone5s-1_PT3959.Sz9P+A==
2015-12-09 15:30:57.401 ThaliTest[607:425858] client: connect: unreachable Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09 15:30:57.401 ThaliTest[607:425858] jxcore: connect: fail: Peer unreachable
,2015-12-09T14:30:57.402Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-09T14:30:57.403Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-09T14:30:57.403Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-09T14:31:02.407Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09T14:31:02.408Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09 15:31:07.415 ThaliTest[607:425858] jxcore: disconnect
2015-12-09 15:31:07.416 ThaliTest[607:425858] jxcore: disconnect: fail
,2015-12-09T14:31:07.416Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09T14:31:07.417Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT3959.Sz9P+A== with availability status: true
,2015-12-09T14:31:07.418Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09T14:31:07.418Z SendDataConnector.js: do connect now
,2015-12-09 15:31:07.419 ThaliTest[607:425858] jxcore: connect Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09 15:31:07.420 ThaliTest[607:425858] client: connect: unreachable Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09 15:31:07.420 ThaliTest[607:425858] jxcore: connect: fail: Peer unreachable
,2015-12-09T14:31:07.421Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-09T14:31:07.422Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-09T14:31:07.422Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-09T14:31:12.424Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09T14:31:12.425Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09 15:31:16.189 ThaliTest[607:425556] multipeer session: restart
,2015-12-09 15:31:16.219 ThaliTest[607:425556] client: found peer: Apple-Iphone5-1_PT9641.4z6eyA==
2015-12-09 15:31:16.219 ThaliTest[607:425556] client: found peer: Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:31:16.220 ThaliTest[607:425556] client: found peer: Apple-Iphone6-1_PT7748.7slvbQ==
,2015-12-09 15:31:17.431 ThaliTest[607:425858] jxcore: disconnect
,2015-12-09 15:31:17.432 ThaliTest[607:425858] jxcore: disconnect: fail
,2015-12-09T14:31:17.433Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09T14:31:17.433Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT3959.Sz9P+A== with availability status: true
,2015-12-09T14:31:17.434Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09T14:31:17.434Z SendDataConnector.js: do connect now
,2015-12-09 15:31:17.435 ThaliTest[607:425858] jxcore: connect Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09 15:31:17.436 ThaliTest[607:425858] client: connect: unreachable Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09 15:31:17.436 ThaliTest[607:425858] jxcore: connect: fail: Peer unreachable
,2015-12-09T14:31:17.437Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-09T14:31:17.437Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-09T14:31:17.438Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-09T14:31:22.440Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09T14:31:22.441Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09 15:31:27.444 ThaliTest[607:425858] jxcore: disconnect
,2015-12-09 15:31:27.445 ThaliTest[607:425858] jxcore: disconnect: fail
2015-12-09T14:31:27.446Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09T14:31:27.447Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT3959.Sz9P+A== with availability status: true
,2015-12-09T14:31:27.448Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09T14:31:27.448Z SendDataConnector.js: do connect now
,2015-12-09 15:31:27.449 ThaliTest[607:425858] jxcore: connect Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09 15:31:27.450 ThaliTest[607:425858] client: connect: unreachable Apple-Iphone5s-1_PT3959.Sz9P+A==
,2015-12-09 15:31:27.451 ThaliTest[607:425858] jxcore: connect: fail: Peer unreachable
,2015-12-09T14:31:27.451Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-09T14:31:27.452Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2015-12-09T14:31:27.454Z SendDataConnector.js: CLIENT Stop now
,2015-12-09 15:31:27.456 ThaliTest[607:425858] jxcore: disconnect
,2015-12-09 15:31:27.456 ThaliTest[607:425858] jxcore: disconnect: fail
,2015-12-09T14:31:27.457Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT3959.Sz9P+A==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09T14:31:27.460Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09T14:31:27.461Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09T14:31:27.461Z SendDataConnector.js: do connect now
,2015-12-09 15:31:27.463 ThaliTest[607:425858] jxcore: connect Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:31:27.463 ThaliTest[607:425858] client session: connect
,2015-12-09 15:31:27.464 ThaliTest[607:425858] client session: stateChange:0->1 Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:31:30.886 ThaliTest[607:426508] client session: connected
2015-12-09 15:31:30.886 ThaliTest[607:426508] client session: stateChange:1->2 Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:31:30.962 ThaliTest[607:426510] client session: fireConnectCallback: Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:31:30.963 ThaliTest[607:426510] jxcore: connect: success
,2015-12-09T14:31:30.964Z SendDataConnector.js: CLIENT connected to 52210, error: null
,2015-12-09T14:31:30.965Z SendDataConnector.js: CLIENT starting client 
,2015-12-09 15:31:30.968 ThaliTest[607:425556] client: relay established
2015-12-09 15:31:30.968 ThaliTest[607:425556] client: new accepted socket: 0x19b9be50
,2015-12-09T14:31:30.984Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-09T14:31:31.510Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-09T14:31:31.524Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-09T14:31:31.537Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-09T14:31:31.538Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-09T14:31:31.538Z SendDataConnector.js: CLIENT Stop now
,2015-12-09T14:31:31.539Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-09 15:31:31.541 ThaliTest[607:425858] jxcore: disconnect
2015-12-09 15:31:31.541 ThaliTest[607:425858] client session: disconnectFromPeer: Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:31:31.541 ThaliTest[607:425858] client session: disconnect
,2015-12-09 15:31:31.542 ThaliTest[607:425858] client session: stateChange:2->0 Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:31:31.609 ThaliTest[607:425858] jxcore: disconnect: success
2015-12-09T14:31:31.609Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT3959.ieNWQg==
,---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone6-1_PT7748.7slvbQ==
,2015-12-09T14:31:31.611Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7748.7slvbQ==
,2015-12-09T14:31:31.612Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7748.7slvbQ==
,2015-12-09T14:31:31.612Z SendDataConnector.js: do connect now
,2015-12-09 15:31:31.614 ThaliTest[607:425858] jxcore: connect Apple-Iphone6-1_PT7748.7slvbQ==
,2015-12-09 15:31:31.614 ThaliTest[607:425858] client session: connect
,2015-12-09 15:31:31.615 ThaliTest[607:425858] client session: stateChange:0->1 Apple-Iphone6-1_PT7748.7slvbQ==
,2015-12-09 15:31:32.928 ThaliTest[607:425556] multipeer session: reset timer
2015-12-09 15:31:32.928 ThaliTest[607:425556] multipeer session: stop timer
2015-12-09 15:31:32.928 ThaliTest[607:425556] multipeer session: start timer: 0x17de48c0
2015-12-09 ,15:31:32.929 ThaliTest[607:425556] server session: connect
2015-12-09 15:31:32.929 ThaliTest[607:425556] server session: stateChange:0->1 Apple-Iphone5s-1_PT3959
,2015-12-09 15:31:32.937 ThaliTest[607:425556] server: accepting invitation Apple-Iphone5s-1_PT3959
,2015-12-09 15:31:34.561 ThaliTest[607:426571] client session: connected
2015-12-09 15:31:34.561 ThaliTest[607:426571] client session: stateChange:1->2 Apple-Iphone6-1_PT7748.7slvbQ==
,2015-12-09 15:31:34.587 ThaliTest[607:426508] client session: fireConnectCallback: Apple-Iphone6-1_PT7748.7slvbQ==
2015-12-09 15:31:34.587 ThaliTest[607:426508] jxcore: connect: success
,2015-12-09T14:31:34.588Z SendDataConnector.js: CLIENT connected to 52213, error: null
,2015-12-09T14:31:34.589Z SendDataConnector.js: CLIENT starting client 
,2015-12-09 15:31:34.591 ThaliTest[607:425556] client: relay established
2015-12-09 15:31:34.592 ThaliTest[607:425556] client: new accepted socket: 0x17eb0320
,2015-12-09T14:31:34.605Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-09T14:31:34.854Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-09T14:31:34.867Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-09T14:31:34.954Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-09T14:31:35.049Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-09T14:31:35.063Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-09T14:31:35.063Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2015-12-09T14:31:35.064Z SendDataConnector.js: CLIENT Stop now
,2015-12-09T14:31:35.064Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-09 15:31:35.065 ThaliTest[607:425858] jxcore: disconnect
,2015-12-09 15:31:35.065 ThaliTest[607:425858] client session: disconnectFromPeer: Apple-Iphone6-1_PT7748.7slvbQ==
2015-12-09 15:31:35.065 ThaliTest[607:425858] client session: disconnect
2015-12-09 15:31:35.065 ThaliTest[607:425858] client session: stateChange:2->0 Apple-Iphone6-1_PT7748.7slvbQ==
,2015-12-09 15:31:35.070 ThaliTest[607:425858] jxcore: disconnect: success
,2015-12-09T14:31:35.071Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7748.7slvbQ==
,---- round done--------
startWithNextDevice
device[4]: Apple-Iphone5-1_PT9641.4z6eyA==
2015-12-09T14:31:35.073Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9641.4z6eyA==
2015-12-09T14:31:35.073Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9641.4z6eyA==
,2015-12-09T14:31:35.073Z SendDataConnector.js: do connect now
2015-12-09 15:31:35.074 ThaliTest[607:425858] jxcore: connect Apple-Iphone5-1_PT9641.4z6eyA==
,2015-12-09 15:31:35.075 ThaliTest[607:425858] client session: connect
2015-12-09 15:31:35.075 ThaliTest[607:425858] client session: stateChange:0->1 Apple-Iphone5-1_PT9641.4z6eyA==
,2015-12-09 15:31:35.744 ThaliTest[607:426510] server session: connected
2015-12-09 15:31:35.745 ThaliTest[607:426510] server session: stateChange:1->2 Apple-Iphone5s-1_PT3959
,2015-12-09 15:31:35.772 ThaliTest[607:425556] server relay: connected (to port: 52205)
,2015-12-09T14:31:35.779Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09T14:31:36.066Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-09T14:31:36.083Z SendDataTCPServer.js: TCP/IP server has received 61178 bytes of data
,2015-12-09T14:31:36.099Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-09T14:31:36.139Z SendDataTCPServer.js: TCP/IP server has received 96218 bytes of data
,2015-12-09T14:31:36.154Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-09 15:31:36.181 ThaliTest[607:426584] server session: not connected Apple-Iphone5s-1_PT3959
,2015-12-09 15:31:39.150 ThaliTest[607:426584] client session: connected
2015-12-09 15:31:39.150 ThaliTest[607:426584] client session: stateChange:1->2 Apple-Iphone5-1_PT9641.4z6eyA==
,2015-12-09 15:31:39.176 ThaliTest[607:426583] client session: fireConnectCallback: Apple-Iphone5-1_PT9641.4z6eyA==
2015-12-09 15:31:39.176 ThaliTest[607:426583] jxcore: connect: success
,2015-12-09T14:31:39.177Z SendDataConnector.js: CLIENT connected to 52217, error: null
,2015-12-09T14:31:39.178Z SendDataConnector.js: CLIENT starting client 
,2015-12-09 15:31:39.181 ThaliTest[607:425556] client: relay established
2015-12-09 15:31:39.182 ThaliTest[607:425556] client: new accepted socket: 0x19cbc660
,2015-12-09T14:31:39.194Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-09T14:31:39.740Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-09T14:31:39.740Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-09T14:31:39.741Z SendDataConnector.js: CLIENT Stop now
,2015-12-09T14:31:39.742Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-09 15:31:39.743 ThaliTest[607:425858] jxcore: disconnect
,2015-12-09 15:31:39.743 ThaliTest[607:425858] client session: disconnectFromPeer: Apple-Iphone5-1_PT9641.4z6eyA==
2015-12-09 15:31:39.744 ThaliTest[607:425858] client session: disconnect
,2015-12-09 15:31:39.744 ThaliTest[607:425858] client session: stateChange:2->0 Apple-Iphone5-1_PT9641.4z6eyA==
,2015-12-09 15:31:39.755 ThaliTest[607:425858] jxcore: disconnect: success
2015-12-09T14:31:39.756Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9641.4z6eyA==
,---- round done--------
startWithNextDevice
,weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
,2015-12-09T14:31:39.764Z SendDataConnector.js: CLIENT Stop now
2015-12-09T14:31:39.764Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-09 15:32:02.930 ThaliTest[607:425556] multipeer session: restart
,2015-12-09 15:32:03.859 ThaliTest[607:425556] client: found peer: Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:32:03.860 ThaliTest[607:425556] client: found peer: Apple-Iphone6-1_PT7748.7slvbQ==
2015-12-09 15:32:03.860 ThaliTest[607:425556] client: found peer: Apple-Iphone5-1_PT9641.4z6eyA==
,2015-12-09 15:32:12.830 ThaliTest[607:425556] multipeer session: reset timer
,2015-12-09 15:32:12.830 ThaliTest[607:425556] multipeer session: stop timer
2015-12-09 15:32:12.831 ThaliTest[607:425556] multipeer session: start timer: 0x17de48c0
,2015-12-09 15:32:12.831 ThaliTest[607:425556] server session: connect
2015-12-09 15:32:12.832 ThaliTest[607:425556] server session: stateChange:0->1 Apple-Iphone6-1_PT7748
,2015-12-09 15:32:12.839 ThaliTest[607:425556] server: accepting invitation Apple-Iphone6-1_PT7748
,2015-12-09 15:32:15.415 ThaliTest[607:426637] server session: connected
2015-12-09 15:32:15.416 ThaliTest[607:426637] server session: stateChange:1->2 Apple-Iphone6-1_PT7748
,2015-12-09 15:32:15.442 ThaliTest[607:425556] server relay: connected (to port: 52205)
,2015-12-09T14:32:15.449Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09T14:32:15.685Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-09T14:32:15.698Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-09T14:32:15.717Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-09T14:32:15.735Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-09 15:32:15.782 ThaliTest[607:426688] server session: not connected Apple-Iphone6-1_PT7748
,2015-12-09 15:32:21.276 ThaliTest[607:425556] multipeer session: reset timer
2015-12-09 15:32:21.277 ThaliTest[607:425556] multipeer session: stop timer
2015-12-09 15:32:21.277 ThaliTest[607:425556] multipeer session: start timer: 0x17de48c0
2015-12-09 15:32:21.278 ThaliTest[607:425556] server session: connect
2015-12-09 15:32:21.278 ThaliTest[607:425556] server session: stateChange:0->1 Apple-Iphone5-1_PT9641
,2015-12-09 15:32:21.286 ThaliTest[607:425556] server: accepting invitation Apple-Iphone5-1_PT9641
,2015-12-09 15:32:24.313 ThaliTest[607:426677] server session: connected
2015-12-09 15:32:24.314 ThaliTest[607:426677] server session: stateChange:1->2 Apple-Iphone5-1_PT9641
,2015-12-09 15:32:24.343 ThaliTest[607:425556] server relay: connected (to port: 52205)
,2015-12-09T14:32:24.351Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09T14:32:24.872Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-09T14:32:24.889Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-09T14:32:24.905Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-09T14:32:24.920Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-09 15:32:24.974 ThaliTest[607:426677] server session: not connected Apple-Iphone5-1_PT9641
,teardown
,testSendData stopped
,2015-12-09 15:32:29.034 ThaliTest[607:425858] jxcore: stopBroadcasting
2015-12-09 15:32:29.034 ThaliTest[607:425858] THEMultipeerSession stopping peer
,2015-12-09 15:32:29.035 ThaliTest[607:425858] multipeer session: stop timer
,2015-12-09 15:32:29.036 ThaliTest[607:425858] server session: disconnect
2015-12-09 15:32:29.036 ThaliTest[607:425858] server session: stateChange:2->0 Apple-Iphone5s-1_PT3959
,2015-12-09 15:32:29.043 ThaliTest[607:425858] server session: disconnect
2015-12-09 15:32:29.043 ThaliTest[607:425858] server session: stateChange:2->0 Apple-Iphone6-1_PT7748
,2015-12-09 15:32:29.111 ThaliTest[607:425858] server session: disconnect
,2015-12-09 15:32:29.112 ThaliTest[607:425858] server session: stateChange:2->0 Apple-Iphone5-1_PT9641
,2015-12-09 15:32:29.260 ThaliTest[607:425858] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-09T14:32:29.279Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-09T14:32:29.281Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-09T14:32:29.283Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-09T14:32:29.284Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
