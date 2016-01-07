#### Test 5531115118861c0_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5531115118861c0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/63CED15E-54C0-4188-88FF-0D0F80EEBD11/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/63CED15E-54C0-4188-88FF-0D0F80EEBD11/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5531115118861c0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5531115118861c0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B3971457-8915-4118-91D9-6447F132230A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49609"
,(lldb)     command script import "/tmp/63CED15E-54C0-4188-88FF-0D0F80EEBD11/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-07 10:42:33.133 ThaliTest[1421:3035052] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FD30B820-4042-47D7-8CB0-C8AF4B1DAE1E/Library/Cookies/Cookies.binarycookies
,2016-01-07 10:42:33.526 ThaliTest[1421:3035052] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-07 10:42:33.527 ThaliTest[1421:3035052] Multi-tasking -> Device: YES, App: YES
,2016-01-07 10:42:33.537 ThaliTest[1421:3035052] Unlimited access to network resources
,2016-01-07 10:42:33.550 ThaliTest[1421:3035052] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-07 10:42:42.748 ThaliTest[1421:3035052] Resetting plugins due to page load.
,2016-01-07 10:42:46.248 ThaliTest[1421:3035052] Finished load of: file:///var/mobile/Containers/Bundle/Application/B3971457-8915-4118-91D9-6447F132230A/ThaliTest.app/www/index.html
,2016-01-07 10:42:46.445 ThaliTest[1421:3035052] JXcore Cordova plugin initializing
2016-01-07 10:42:46.446 ThaliTest[1421:3035379] JXcore instance initializing
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
,2016-01-07 10:42:47.754 ThaliTest[1421:3035052] THREAD WARNING: ['JXcore'] took '88.027832' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-07 10:47:32.466 ThaliTest[1421:3035379] jxcore: startBroadcasting
,2016-01-07 10:47:32.485 ThaliTest[1421:3035379] server: starting Apple-Iphone5s-1.kmefAg==
2016-01-07 10:47:32.487 ThaliTest[1421:3035379] multipeer session: start timer: 0x17c8ca60
2016-01-07 10:47:32.488 ThaliTest[1421:3035379] THEMultipeerSession initialized peer Apple-Iphone5s-1
,2016-01-07 10:47:32.491 ThaliTest[1421:3035379] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-07 10:47:33.111 ThaliTest[1421:3035052] client: found peer: Apple-IpadAir2-1.1I3u2A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.1I3u2A==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1.1I3u2A==, peerAv,ailable: true
weAreDoneNow
,done, now sending data to server
2016-01-07 10:47:33.122 ThaliTest[1421:3035052] client: found peer: Apple-Iphone5-1.kLcgag==
,2016-01-07 10:47:33.125 ThaliTest[1421:3035052] client: found peer: Apple-Iphone6-1.W/Fi/g==
,teardown
,testFindPeers stopped
2016-01-07 10:47:33.295 ThaliTest[1421:3035379] jxcore: stopBroadcasting
,2016-01-07 10:47:33.295 ThaliTest[1421:3035379] THEMultipeerSession stopping peer
,2016-01-07 10:47:33.296 ThaliTest[1421:3035379] multipeer session: stop timer
,2016-01-07 10:47:33.298 ThaliTest[1421:3035379] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 56232
,2016-01-07 10:47:33.349 ThaliTest[1421:3035379] jxcore: startBroadcasting
,2016-01-07 10:47:33.356 ThaliTest[1421:3035379] server: starting Apple-Iphone5s-1.Waegsg==
2016-01-07 10:47:33.358 ThaliTest[1421:3035379] multipeer session: start timer: 0x17c9b760
2016-01-07 10:47:33.359 ThaliTest[1421:3035379] THEMultipeerSession init,ialized peer Apple-Iphone5s-1
2016-01-07 10:47:33.360 ThaliTest[1421:3035379] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2016-01-07T09:47:33.365Z SendDataTCPServer.js: TCP/IP server is bound to port: 56232
,2016-01-07 10:47:33.386 ThaliTest[1421:3035052] client: found peer: Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:47:33.386 ThaliTest[1421:3035052] client: found peer: Apple-Iphone6-1.W/Fi/g==
2016-01-07 10:47:33.386 ThaliTest[1421:3035052] client: found peer: Apple-Iphone5-1.kLcgag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.1I3u2A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-IpadAir2-1.1I3u2A==
2016-01-07T09:47:,33.389Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.1I3u2A==
2016-01-07T09:47:33.390Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.1I3u2A==
2016-01-07T09:47:33.390Z SendDataConnector.js: do connect now
2016-01-07 1,0:47:33.390 ThaliTest[1421:3035379] jxcore: connect Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:47:33.391 ThaliTest[1421:3035379] client session: connect
2016-01-07 10:47:33.391 ThaliTest[1421:3035379] client session: stateChange:0->1 Apple-IpadAir2-1.1I3u2A,==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.W/Fi/g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.kLcgag==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-07 10:47:34.624 ThaliTest[1421:3035052] client: found peer: Apple-IpadAir2-1.CdHxkA==
2016-01-07 10:47:34.625 ThaliTest[1421:3035052] client: found peer: Apple-Iphone6-1.Uf4Y7g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.CdHxkA,==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.Uf4Y7g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-07 10:47:35.614 ThaliTest[1421:3035052] client: lost peer: Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:47:35.614 ThaliTest[1421:3035052] client session: onPeerLost: Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:47:35.614 ThaliTest[1421:3035052] client sess,ion: onLinkFailure: Apple-IpadAir2-1.1I3u2A==
,2016-01-07 10:47:35.615 ThaliTest[1421:3035052] client session: disconnect
,2016-01-07 10:47:35.618 ThaliTest[1421:3035052] client session: stateChange:1->0 Apple-IpadAir2-1.1I3u2A==
,2016-01-07 10:47:35.621 ThaliTest[1421:3035052] client session: fireConnectCallback: Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:47:35.621 ThaliTest[1421:3035052] jxcore: connect: fail: Peer disconnected
2016-01-07 10:47:35.622 ThaliTest[1421:3035052] client,: lost peer: Apple-Iphone6-1.W/Fi/g==
2016-01-07 10:47:35.622 ThaliTest[1421:3035052] client session: onPeerLost: Apple-Iphone6-1.W/Fi/g==
2016-01-07 10:47:35.622 ThaliTest[1421:3035052] client: found peer: Apple-Iphone5-1.XzilZw==
2016-01-07T09:47:35.6,24Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2016-01-07T09:47:35.624Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-07T09:47:35.625Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityCha,nged [{"peerIdentifier":"Apple-IpadAir2-1.1I3u2A==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.W/Fi/g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.XzilZw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-07 10:47:37.249 ThaliTest[1421:3035052] client: lost peer: Apple-Iphone5-1.kLcgag==
2016-01-07 10:47:37.249 ThaliTest[1421:3035052] client session: onPeerLost: Apple-Iphone5-1.kLcgag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.k,Lcgag==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-07T09:47:40.629Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.1I3u2A==
,2016-01-07T09:47:40.631Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.1I3u2A==
,2016-01-07 10:47:45.639 ThaliTest[1421:3035379] jxcore: disconnect
2016-01-07 10:47:45.640 ThaliTest[1421:3035379] jxcore: disconnect: fail
2016-01-07T09:47:45.640Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.1I3u2A==
2,016-01-07T09:47:45.641Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1.1I3u2A== with availability status: true
2016-01-07T09:47:45.641Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.1I3u2A==
,2016-01-07T09:47:45.642Z SendDataConnector.js: do connect now
2016-01-07 10:47:45.642 ThaliTest[1421:3035379] jxcore: connect Apple-IpadAir2-1.1I3u2A==
,2016-01-07 10:47:45.643 ThaliTest[1421:3035379] client: connect: unreachable Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:47:45.644 ThaliTest[1421:3035379] jxcore: connect: fail: Peer unreachable
,2016-01-07T09:47:45.645Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-07T09:47:45.646Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-07T09:47:45.646Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T09:47:50.659Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.1I3u2A==
,2016-01-07T09:47:50.660Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.1I3u2A==
,2016-01-07 10:47:55.662 ThaliTest[1421:3035379] jxcore: disconnect
2016-01-07 10:47:55.663 ThaliTest[1421:3035379] jxcore: disconnect: fail
2016-01-07T09:47:55.663Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.1I3u2A==
2,016-01-07T09:47:55.664Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1.1I3u2A== with availability status: true
2016-01-07T09:47:55.664Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.1I3u2A==
2016-01-07T09:47:55,.664Z SendDataConnector.js: do connect now
,2016-01-07 10:47:55.666 ThaliTest[1421:3035379] jxcore: connect Apple-IpadAir2-1.1I3u2A==
,2016-01-07 10:47:55.666 ThaliTest[1421:3035379] client: connect: unreachable Apple-IpadAir2-1.1I3u2A==
,2016-01-07 10:47:55.668 ThaliTest[1421:3035379] jxcore: connect: fail: Peer unreachable
,2016-01-07T09:47:55.668Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-07T09:47:55.669Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-07T09:47:55.669Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T09:48:00.674Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.1I3u2A==
,2016-01-07T09:48:00.675Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.1I3u2A==
,2016-01-07 10:48:03.361 ThaliTest[1421:3035052] multipeer session: restart
,2016-01-07 10:48:03.422 ThaliTest[1421:3035052] client: found peer: Apple-Iphone6-1.Uf4Y7g==
2016-01-07 10:48:03.422 ThaliTest[1421:3035052] client: found peer: Apple-IpadAir2-1.CdHxkA==
2016-01-07 10:48:03.423 ThaliTest[1421:3035052] client: found peer:, Apple-Iphone5-1.XzilZw==
,2016-01-07 10:48:05.686 ThaliTest[1421:3035379] jxcore: disconnect
2016-01-07 10:48:05.686 ThaliTest[1421:3035379] jxcore: disconnect: fail
2016-01-07T09:48:05.687Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.1I3u2A==
2,016-01-07T09:48:05.687Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1.1I3u2A== with availability status: true
2016-01-07T09:48:05.688Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.1I3u2A==
2016-01-07T09:48:05,.688Z SendDataConnector.js: do connect now
,2016-01-07 10:48:05.688 ThaliTest[1421:3035379] jxcore: connect Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:48:05.689 ThaliTest[1421:3035379] client: connect: unreachable Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:48:05.689 ThaliTest[1421:3035379] jxcore: conne,ct: fail: Peer unreachable
2016-01-07T09:48:05.690Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-07T09:48:05.690Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-07T09:48:05.690Z SendDataConnector.j,s: tryAgain afer: 5000 ms.
,2016-01-07T09:48:10.693Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.1I3u2A==
,2016-01-07T09:48:10.700Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.1I3u2A==
,2016-01-07 10:48:15.711 ThaliTest[1421:3035379] jxcore: disconnect
2016-01-07 10:48:15.712 ThaliTest[1421:3035379] jxcore: disconnect: fail
2016-01-07T09:48:15.712Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.1I3u2A==
2,016-01-07T09:48:15.713Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1.1I3u2A== with availability status: true
2016-01-07T09:48:15.713Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.1I3u2A==
,2016-01-07T09:48:15.713Z SendDataConnector.js: do connect now
2016-01-07 10:48:15.714 ThaliTest[1421:3035379] jxcore: connect Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:48:15.715 ThaliTest[1421:3035379] client: connect: unreachable Apple-IpadAir2-1.1I3u2A==
,2016-01-07 10:48:15.716 ThaliTest[1421:3035379] jxcore: connect: fail: Peer unreachable
2016-01-07T09:48:15.716Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-07T09:48:15.717Z SendDataConnector.js: CLIENT Can not Connect: P,eer unreachable
oneRoundDownNow
,2016-01-07T09:48:15.719Z SendDataConnector.js: CLIENT Stop now
,2016-01-07 10:48:15.720 ThaliTest[1421:3035379] jxcore: disconnect
2016-01-07 10:48:15.721 ThaliTest[1421:3035379] jxcore: disconnect: fail
,2016-01-07T09:48:15.723Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.1I3u2A==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-IpadAir2-1.CdHxkA==
,2016-01-07T09:48:15.726Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.CdHxkA==
,2016-01-07T09:48:15.727Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.CdHxkA==
,2016-01-07T09:48:15.728Z SendDataConnector.js: do connect now
,2016-01-07 10:48:15.729 ThaliTest[1421:3035379] jxcore: connect Apple-IpadAir2-1.CdHxkA==
2016-01-07 10:48:15.730 ThaliTest[1421:3035379] client session: connect
2016-01-07 10:48:15.730 ThaliTest[1421:3035379] client session: stateChange:0->1 Apple-IpadAir2-1.CdHxkA==
,2016-01-07 10:48:27.356 ThaliTest[1421:3035052] client: lost peer: Apple-IpadAir2-1.CdHxkA==
2016-01-07 10:48:27.358 ThaliTest[1421:3035052] client session: onPeerLost: Apple-IpadAir2-1.CdHxkA==
2016-01-07 10:48:27.358 ThaliTest[1421:3035052] client sess,ion: onLinkFailure: Apple-IpadAir2-1.CdHxkA==
2016-01-07 10:48:27.358 ThaliTest[1421:3035052] client session: disconnect
2016-01-07 10:48:27.359 ThaliTest[1421:3035052] client session: stateChange:1->0 Apple-IpadAir2-1.CdHxkA==
2016-01-07 10:48:27.359 T,haliTest[1421:3035052] client session: fireConnectCallback: Apple-IpadAir2-1.CdHxkA==
,2016-01-07 10:48:27.359 ThaliTest[1421:3035052] jxcore: connect: fail: Peer disconnected
2016-01-07 10:48:27.363 ThaliTest[1421:3035052] client: lost peer: Apple-Iphone6-1.Uf4Y7g==
2016-01-07 10:48:27.363 ThaliTest[1421:3035052] client session: onPeerLos,t: Apple-Iphone6-1.Uf4Y7g==
2016-01-07 10:48:27.364 ThaliTest[1421:3035052] client: lost peer: Apple-Iphone5-1.XzilZw==
2016-01-07 10:48:27.364 ThaliTest[1421:3035052] client session: onPeerLost: Apple-Iphone5-1.XzilZw==
2016-01-07T09:48:27.365Z SendDat,aConnector.js: CLIENT connected to 0, error: Peer disconnected
2016-01-07T09:48:27.366Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-07T09:48:27.366Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"pee,rIdentifier":"Apple-IpadAir2-1.CdHxkA==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.Uf4Y7g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailability,Changed [{"peerIdentifier":"Apple-Iphone5-1.XzilZw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-07 10:48:30.114 ThaliTest[1421:3035052] client: found peer: Apple-IpadAir2-1.CdHxkA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.CdHxkA==","peerName":"(null)","peerAvailable":true}]
,2016-01-07 10:48:30.235 ThaliTest[1421:3035052] client: found peer: Apple-Iphone5-1.XzilZw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.XzilZw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-07 10:48:30.656 ThaliTest[1421:3035052] multipeer session: reset timer
2016-01-07 10:48:30.656 ThaliTest[1421:3035052] multipeer session: stop timer
2016-01-07 10:48:30.657 ThaliTest[1421:3035052] multipeer session: start timer: 0x17c9b760
2016-,01-07 10:48:30.657 ThaliTest[1421:3035052] server session: connect
2016-01-07 10:48:30.658 ThaliTest[1421:3035052] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-07 10:48:30.670 ThaliTest[1421:3035052] server: accepting invitation Apple-IpadAir2-1
,2016-01-07 10:48:31.683 ThaliTest[1421:3035052] client: found peer: Apple-Iphone6-1.Uf4Y7g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.Uf4Y7g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-07T09:48:32.377Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.CdHxkA==
2016-01-07T09:48:32.377Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.CdHxkA==
,2016-01-07 10:48:36.002 ThaliTest[1421:3035052] multipeer session: reset timer
2016-01-07 10:48:36.003 ThaliTest[1421:3035052] multipeer session: stop timer
2016-01-07 10:48:36.003 ThaliTest[1421:3035052] multipeer session: start timer: 0x17c9b760
2016-,01-07 10:48:36.003 ThaliTest[1421:3035052] server session: connect
2016-01-07 10:48:36.004 ThaliTest[1421:3035052] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-07 10:48:36.015 ThaliTest[1421:3035052] server: accepting invitation Apple-Iphone5-1
,2016-01-07 10:48:37.385 ThaliTest[1421:3035379] jxcore: disconnect
2016-01-07 10:48:37.385 ThaliTest[1421:3035379] jxcore: disconnect: fail
2016-01-07T09:48:37.386Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.CdHxkA==
2,016-01-07T09:48:37.386Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1.CdHxkA== with availability status: true
2016-01-07T09:48:37.387Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.CdHxkA==
2016-01-07T09:48:37.387Z SendDataConnector.js: do connect now
,2016-01-07 10:48:37.388 ThaliTest[1421:3035379] jxcore: connect Apple-IpadAir2-1.CdHxkA==
,2016-01-07 10:48:37.389 ThaliTest[1421:3035379] client session: connect
,2016-01-07 10:48:37.390 ThaliTest[1421:3035379] client session: stateChange:0->1 Apple-IpadAir2-1.CdHxkA==
,2016-01-07 10:48:39.085 ThaliTest[1421:3036300] server session: connected
2016-01-07 10:48:39.085 ThaliTest[1421:3036300] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-07 10:48:39.097 ThaliTest[1421:3035052] server relay: connected (to port: 56232)
,2016-01-07T09:48:39.108Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-07 10:48:39.280 ThaliTest[1421:3035052] multipeer session: reset timer
2016-01-07 10:48:39.281 ThaliTest[1421:3035052] multipeer session: stop timer
2016-01-07 10:48:39.281 ThaliTest[1421:3035052] multipeer session: start timer: 0x17c9b760
2016-,01-07 10:48:39.282 ThaliTest[1421:3035052] server: disconnecting to refresh session (Apple-IpadAir2-1)
2016-01-07 10:48:39.282 ThaliTest[1421:3035052] server session: disconnect
2016-01-07 10:48:39.282 ThaliTest[1421:3035052] server session: stateChange:,1->0 Apple-IpadAir2-1
,2016-01-07 10:48:39.290 ThaliTest[1421:3035052] server session: connect
,2016-01-07 10:48:39.290 ThaliTest[1421:3035052] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-07 10:48:39.308 ThaliTest[1421:3035052] server: accepting invitation Apple-IpadAir2-1
,2016-01-07T09:48:40.142Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2016-01-07T09:48:40.170Z SendDataTCPServer.js: TCP/IP server has received 14235 bytes of data
,2016-01-07T09:48:40.201Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2016-01-07T09:48:40.215Z SendDataTCPServer.js: TCP/IP server has received 33945 bytes of data
2016-01-07T09:48:40.234Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2016-01-07T09:48:40.250Z SendDataTCPServer.js: TCP/IP server has received 60225 bytes of data
,2016-01-07T09:48:40.266Z SendDataTCPServer.js: TCP/IP server has received 68985 bytes of data
,2016-01-07T09:48:40.282Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2016-01-07T09:48:40.298Z SendDataTCPServer.js: TCP/IP server has received 77745 bytes of data
,2016-01-07T09:48:40.312Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2016-01-07T09:48:40.361Z SendDataTCPServer.js: TCP/IP server has received 84315 bytes of data
,2016-01-07T09:48:40.378Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2016-01-07T09:48:40.391Z SendDataTCPServer.js: TCP/IP server has received 88695 bytes of data
,2016-01-07T09:48:40.654Z SendDataTCPServer.js: TCP/IP server has received 89719 bytes of data
,2016-01-07T09:48:40.674Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2016-01-07T09:48:40.733Z SendDataTCPServer.js: TCP/IP server has received 97455 bytes of data
,2016-01-07T09:48:40.747Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-07 10:48:41.133 ThaliTest[1421:3036300] server session: not connected Apple-Iphone5-1
,2016-01-07 10:48:41.248 ThaliTest[1421:3036300] client session: connected
2016-01-07 10:48:41.248 ThaliTest[1421:3036300] client session: stateChange:1->2 Apple-IpadAir2-1.CdHxkA==
,2016-01-07 10:48:41.279 ThaliTest[1421:3036241] client session: fireConnectCallback: Apple-IpadAir2-1.CdHxkA==
2016-01-07 10:48:41.280 ThaliTest[1421:3036241] jxcore: connect: success
2016-01-07T09:48:41.281Z SendDataConnector.js: CLIENT connected to 56242, error: null
2016-01-07T09:48:41.281Z SendDataConnector.js: CLIENT starting client 
,2016-01-07 10:48:41.288 ThaliTest[1421:3035052] client: relay established
2016-01-07 10:48:41.288 ThaliTest[1421:3035052] client: new accepted socket: 0x17bea350
,2016-01-07T09:48:41.304Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-07T09:48:41.818Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-07T09:48:41.831Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-07T09:48:41.845Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-07T09:48:41.858Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-07T09:48:41.858Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-07T09:48:41.859Z SendDataConnector.js: CLIENT Stop now
,2016-01-07T09:48:41.859Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-07 10:48:41.860 ThaliTest[1421:3035379] jxcore: disconnect
,2016-01-07 10:48:41.861 ThaliTest[1421:3035379] client session: disconnectFromPeer: Apple-IpadAir2-1.CdHxkA==
,2016-01-07 10:48:41.862 ThaliTest[1421:3035379] client session: disconnect
,2016-01-07 10:48:41.862 ThaliTest[1421:3035379] client session: stateChange:2->0 Apple-IpadAir2-1.CdHxkA==
,2016-01-07 10:48:41.931 ThaliTest[1421:3035379] jxcore: disconnect: success
,2016-01-07T09:48:41.931Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.CdHxkA==
,---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone6-1.Uf4Y7g==
,2016-01-07T09:48:41.932Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.Uf4Y7g==
,2016-01-07T09:48:41.933Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.Uf4Y7g==
,2016-01-07T09:48:41.933Z SendDataConnector.js: do connect now
,2016-01-07 10:48:41.933 ThaliTest[1421:3035379] jxcore: connect Apple-Iphone6-1.Uf4Y7g==
,2016-01-07 10:48:41.934 ThaliTest[1421:3035379] client session: connect
,2016-01-07 10:48:41.935 ThaliTest[1421:3035379] client session: stateChange:0->1 Apple-Iphone6-1.Uf4Y7g==
,2016-01-07 10:48:43.275 ThaliTest[1421:3036185] server session: connected
2016-01-07 10:48:43.275 ThaliTest[1421:3036185] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-07 10:48:43.340 ThaliTest[1421:3035052] server relay: connected (to port: 56232)
,2016-01-07T09:48:43.348Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-07T09:48:43.804Z SendDataTCPServer.js: TCP/IP server has received 1095 bytes of data
,2016-01-07T09:48:43.819Z SendDataTCPServer.js: TCP/IP server has received 12045 bytes of data
,2016-01-07T09:48:43.836Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2016-01-07T09:48:43.853Z SendDataTCPServer.js: TCP/IP server has received 29565 bytes of data
,2016-01-07T09:48:43.871Z SendDataTCPServer.js: TCP/IP server has received 36135 bytes of data
,2016-01-07T09:48:43.888Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2016-01-07T09:48:43.904Z SendDataTCPServer.js: TCP/IP server has received 71175 bytes of data
,2016-01-07T09:48:43.933Z SendDataTCPServer.js: TCP/IP server has received 75555 bytes of data
,2016-01-07T09:48:43.948Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2016-01-07T09:48:43.963Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2016-01-07T09:48:43.998Z SendDataTCPServer.js: TCP/IP server has received 93075 bytes of data
,2016-01-07T09:48:44.014Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-07 10:48:44.326 ThaliTest[1421:3036223] server session: not connected Apple-IpadAir2-1
,2016-01-07 10:48:44.868 ThaliTest[1421:3036185] client session: connected
2016-01-07 10:48:44.872 ThaliTest[1421:3036185] client session: stateChange:1->2 Apple-Iphone6-1.Uf4Y7g==
,2016-01-07 10:48:44.877 ThaliTest[1421:3036185] client session: fireConnectCallback: Apple-Iphone6-1.Uf4Y7g==
2016-01-07 10:48:44.878 ThaliTest[1421:3036185] jxcore: connect: success
,2016-01-07T09:48:44.880Z SendDataConnector.js: CLIENT connected to 56246, error: null
2016-01-07T09:48:44.881Z SendDataConnector.js: CLIENT starting client 
,2016-01-07 10:48:44.885 ThaliTest[1421:3035052] client: relay established
2016-01-07 10:48:44.885 ThaliTest[1421:3035052] client: new accepted socket: 0x17ca5910
,2016-01-07T09:48:44.896Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-07T09:48:45.436Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-07T09:48:45.566Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-07T09:48:45.580Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-07T09:48:45.629Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-07T09:48:45.629Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-07T09:48:45.629Z SendDataConnector.js: CLIENT Stop now
,2016-01-07T09:48:45.630Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-07 10:48:45.630 ThaliTest[1421:3035379] jxcore: disconnect
2016-01-07 10:48:45.631 ThaliTest[1421:3035379] client session: disconnectFromPeer: Apple-Iphone6-1.Uf4Y7g==
2016-01-07 10:48:45.631 ThaliTest[1421:3035379] client session: disconnect
2016-01-07 10:48:45.631 ThaliTest[1421:3035379] client session: stateChange:2->0 Apple-Iphone6-1.Uf4Y7g==
,2016-01-07 10:48:45.697 ThaliTest[1421:3035379] jxcore: disconnect: success
2016-01-07T09:48:45.697Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.Uf4Y7g==
---- round done--------
startWithNextDevice
,device[4]: Apple-Iphone5-1.XzilZw==
2016-01-07T09:48:45.698Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.XzilZw==
,2016-01-07T09:48:45.698Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.XzilZw==
,2016-01-07T09:48:45.699Z SendDataConnector.js: do connect now
,2016-01-07 10:48:45.699 ThaliTest[1421:3035379] jxcore: connect Apple-Iphone5-1.XzilZw==
2016-01-07 10:48:45.700 ThaliTest[1421:3035379] client session: connect
2016-01-07 10:48:45.700 ThaliTest[1421:3035379] client session: stateChange:0->1 Apple-Iphone5-1.XzilZw==
,2016-01-07 10:48:48.681 ThaliTest[1421:3036241] client session: connected
2016-01-07 10:48:48.681 ThaliTest[1421:3036241] client session: stateChange:1->2 Apple-Iphone5-1.XzilZw==
,2016-01-07 10:48:48.689 ThaliTest[1421:3036241] client session: fireConnectCallback: Apple-Iphone5-1.XzilZw==
2016-01-07 10:48:48.689 ThaliTest[1421:3036241] jxcore: connect: success
,2016-01-07T09:48:48.691Z SendDataConnector.js: CLIENT connected to 56249, error: null
,2016-01-07T09:48:48.692Z SendDataConnector.js: CLIENT starting client 
,2016-01-07 10:48:48.695 ThaliTest[1421:3035052] client: relay established
2016-01-07 10:48:48.696 ThaliTest[1421:3035052] client: new accepted socket: 0x17be84f0
,2016-01-07T09:48:48.707Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-07T09:48:49.217Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-07T09:48:49.236Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-07T09:48:49.261Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-07T09:48:49.299Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-07T09:48:49.325Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-07T09:48:49.325Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-07T09:48:49.326Z SendDataConnector.js: CLIENT Stop now
2016-01-07T09:48:49.326Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-07 10:48:49.327 ThaliTest[1421:3035379] jxcore: disconnect
,2016-01-07 10:48:49.327 ThaliTest[1421:3035379] client session: disconnectFromPeer: Apple-Iphone5-1.XzilZw==
,2016-01-07 10:48:49.328 ThaliTest[1421:3035379] client session: disconnect
,2016-01-07 10:48:49.329 ThaliTest[1421:3035379] client session: stateChange:2->0 Apple-Iphone5-1.XzilZw==
,2016-01-07 10:48:49.397 ThaliTest[1421:3035379] jxcore: disconnect: success
,2016-01-07T09:48:49.398Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.XzilZw==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-07T09:48:49.413Z SendDataConnector.js: CLIENT Stop now
2016-01-07T09:48:49.413Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-07 10:49:09.283 ThaliTest[1421:3035052] multipeer session: restart
,teardown
,testSendData stopped
2016-01-07 10:49:13.475 ThaliTest[1421:3035379] jxcore: stopBroadcasting
,2016-01-07 10:49:13.475 ThaliTest[1421:3035379] THEMultipeerSession stopping peer
,2016-01-07 10:49:13.476 ThaliTest[1421:3035379] multipeer session: stop timer
,2016-01-07 10:49:13.477 ThaliTest[1421:3035379] server session: disconnect
2016-01-07 10:49:13.478 ThaliTest[1421:3035379] server session: stateChange:2->0 Apple-IpadAir2-1
,2016-01-07 10:49:13.487 ThaliTest[1421:3035379] server session: disconnect
2016-01-07 10:49:13.488 ThaliTest[1421:3035379] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-07 10:49:13.521 ThaliTest[1421:3035379] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-07T09:49:13.541Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-07T09:49:13.543Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-07T09:49:13.548Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
