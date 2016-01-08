#### Test 55431344148e3f8_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55431344148e3f8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/489220EE-A895-45CB-9CF8-AD71A7FD09F2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/489220EE-A895-45CB-9CF8-AD71A7FD09F2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/55431344148e3f8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55431344148e3f8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3CEF7D0D-3518-4B40-92FC-80D35577EABC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49986"
,(lldb)     command script import "/tmp/489220EE-A895-45CB-9CF8-AD71A7FD09F2/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 10:46:52.277 ThaliTest[1480:3175304] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2770F476-AC50-4417-A0BB-3E9830949F89/Library/Cookies/Cookies.binarycookies
,2016-01-08 10:46:52.678 ThaliTest[1480:3175304] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 10:46:52.679 ThaliTest[1480:3175304] Multi-tasking -> Device: YES, App: YES
,2016-01-08 10:46:52.688 ThaliTest[1480:3175304] Unlimited access to network resources
,2016-01-08 10:46:52.701 ThaliTest[1480:3175304] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 10:47:01.375 ThaliTest[1480:3175304] Resetting plugins due to page load.
,2016-01-08 10:47:05.398 ThaliTest[1480:3175304] Finished load of: file:///var/mobile/Containers/Bundle/Application/3CEF7D0D-3518-4B40-92FC-80D35577EABC/ThaliTest.app/www/index.html
,2016-01-08 10:47:05.604 ThaliTest[1480:3175304] JXcore Cordova plugin initializing
2016-01-08 10:47:05.605 ThaliTest[1480:3175528] JXcore instance initializing
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
,2016-01-08 10:47:07.090 ThaliTest[1480:3175304] THREAD WARNING: ['JXcore'] took '91.414795' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-08 10:51:34.127 ThaliTest[1480:3175528] jxcore: startBroadcasting
,2016-01-08 10:51:34.147 ThaliTest[1480:3175528] server: starting Apple-Iphone5s-1.1B6pGw==
2016-01-08 10:51:34.149 ThaliTest[1480:3175528] multipeer session: start timer: 0x183f2710
2016-01-08 10:51:34.149 ThaliTest[1480:3175528] THEMultipeerSession init,ialized peer Apple-Iphone5s-1
2016-01-08 10:51:34.150 ThaliTest[1480:3175528] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-08 10:51:35.470 ThaliTest[1480:3175304] client: found peer: Apple-Iphone6-1.hx3ANw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.hx3ANw==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1.hx3ANw==, peerAvailable: true
,weAreDoneNow
done, now sending data to server
,2016-01-08 10:51:35.789 ThaliTest[1480:3175304] client: found peer: Apple-Iphone5-1.rHC9Aw==
,2016-01-08 10:51:35.795 ThaliTest[1480:3175304] client: found peer: Apple-IpadAir2-1.TL+VGA==
,teardown
,testFindPeers stopped
,2016-01-08 10:51:36.175 ThaliTest[1480:3175528] jxcore: stopBroadcasting
2016-01-08 10:51:36.176 ThaliTest[1480:3175528] THEMultipeerSession stopping peer
2016-01-08 10:51:36.177 ThaliTest[1480:3175528] multipeer session: stop timer
2016-01-08 10:51:36.,177 ThaliTest[1480:3175528] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 56517
,2016-01-08 10:51:36.241 ThaliTest[1480:3175528] jxcore: startBroadcasting
,2016-01-08 10:51:36.270 ThaliTest[1480:3175528] server: starting Apple-Iphone5s-1.KjG2gw==
,2016-01-08 10:51:36.287 ThaliTest[1480:3175528] multipeer session: start timer: 0x18371590
,2016-01-08 10:51:36.292 ThaliTest[1480:3175528] THEMultipeerSession initialized peer Apple-Iphone5s-1
,2016-01-08 10:51:36.296 ThaliTest[1480:3175528] jxcore: startBroadcasting: success
,2016-01-08 10:51:36.303 ThaliTest[1480:3175304] client: found peer: Apple-Iphone6-1.hx3ANw==
StartBroadcasting started ok
null
2016-01-08T09:51:36.307Z SendDataTCPServer.js: TCP/IP server is bound to port: 56517
2016-01-08 10:51:36.307 ThaliTest[1480:3175304] client: found peer: Apple-IpadAir2-1.TL+VGA==
2016-01-08 10:51:36.308 ThaliTest[1480:3175304] client: found peer: Apple-Iphone5-1.rHC9Aw==
,2016-01-08 10:51:36.313 ThaliTest[1480:3175304] client: found peer: Apple-Iphone5s-1.1B6pGw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.hx3ANw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone6-1.hx3ANw==
,2016-01-08T09:51:36.321Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.hx3ANw==
2016-01-08T09:51:36.321Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.hx3ANw==
2016-01-08T09:51:36.322Z SendDataConnector.js: do connect now
,2016-01-08 10:51:36.322 ThaliTest[1480:3175528] jxcore: connect Apple-Iphone6-1.hx3ANw==
2016-01-08 10:51:36.323 ThaliTest[1480:3175528] client session: connect
2016-01-08 10:51:36.323 ThaliTest[1480:3175528] client session: stateChange:0->1 Apple-Iphone6-1.hx3ANw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.TL+VGA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.rHC9Aw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.1B6pGw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-08 10:51:37.382 ThaliTest[1480:3175304] client: lost peer: Apple-Iphone6-1.hx3ANw==
2016-01-08 10:51:37.382 ThaliTest[1480:3175304] client session: onPeerLost: Apple-Iphone6-1.hx3ANw==
2016-01-08 10:51:37.383 ThaliTest[1480:3175304] client sessio,n: onLinkFailure: Apple-Iphone6-1.hx3ANw==
2016-01-08 10:51:37.384 ThaliTest[1480:3175304] client session: disconnect
2016-01-08 10:51:37.384 ThaliTest[1480:3175304] client session: stateChange:1->0 Apple-Iphone6-1.hx3ANw==
2016-01-08 10:51:37.385 Thali,Test[1480:3175304] client session: fireConnectCallback: Apple-Iphone6-1.hx3ANw==
2016-01-08 10:51:37.385 ThaliTest[1480:3175304] jxcore: connect: fail: Peer disconnected
2016-01-08T09:51:37.387Z SendDataConnector.js: CLIENT connected to 0, error: Peer di,sconnected
2016-01-08T09:51:37.387Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-08T09:51:37.388Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.hx3ANw==","peerName":"(null)","peerAvailable":false}]
,2016-01-08 10:51:37.443 ThaliTest[1480:3175304] client: lost peer: Apple-Iphone5s-1.1B6pGw==
2016-01-08 10:51:37.444 ThaliTest[1480:3175304] client session: onPeerLost: Apple-Iphone5s-1.1B6pGw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.1B6pGw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08 10:51:37.600 ThaliTest[1480:3175304] client: found peer: Apple-Iphone5-1.AdDQ5g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.AdDQ5g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 10:51:37.990 ThaliTest[1480:3175304] client: lost peer: Apple-IpadAir2-1.TL+VGA==
2016-01-08 10:51:37.991 ThaliTest[1480:3175304] client session: onPeerLost: Apple-IpadAir2-1.TL+VGA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-,1.TL+VGA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
2016-01-08 10:51:37.995 ThaliTest[1480:3175304] client: found peer: Apple-IpadAir2-1.7azU7Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.7azU,7Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 10:51:38.453 ThaliTest[1480:3175304] client: found peer: Apple-Iphone6-1.0EeFvA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.0EeFvA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08T09:51:42.391Z SendDataConnector.js: re-try now : Apple-Iphone6-1.hx3ANw==
,2016-01-08T09:51:42.392Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.hx3ANw==
,2016-01-08 10:51:43.065 ThaliTest[1480:3175304] client: lost peer: Apple-Iphone5-1.rHC9Aw==
2016-01-08 10:51:43.065 ThaliTest[1480:3175304] client session: onPeerLost: Apple-Iphone5-1.rHC9Aw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.r,HC9Aw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08 10:51:47.398 ThaliTest[1480:3175528] jxcore: disconnect
2016-01-08 10:51:47.399 ThaliTest[1480:3175528] jxcore: disconnect: fail
2016-01-08T09:51:47.399Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.hx3ANw==
20,16-01-08T09:51:47.400Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1.hx3ANw== with availability status: true
2016-01-08T09:51:47.400Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.hx3ANw==
2016-01-08T09:51:47.401Z SendDataConnector.js: do connect now
,2016-01-08 10:51:47.401 ThaliTest[1480:3175528] jxcore: connect Apple-Iphone6-1.hx3ANw==
2016-01-08 10:51:47.402 ThaliTest[1480:3175528] client: connect: unreachable Apple-Iphone6-1.hx3ANw==
2016-01-08 10:51:47.402 ThaliTest[1480:3175528] jxcore: connect,: fail: Peer unreachable
2016-01-08T09:51:47.403Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-08T09:51:47.404Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T09:51:47.405Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T09:51:52.406Z SendDataConnector.js: re-try now : Apple-Iphone6-1.hx3ANw==
,2016-01-08T09:51:52.407Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.hx3ANw==
,2016-01-08 10:51:57.415 ThaliTest[1480:3175528] jxcore: disconnect
2016-01-08 10:51:57.416 ThaliTest[1480:3175528] jxcore: disconnect: fail
2016-01-08T09:51:57.416Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.hx3ANw==
20,16-01-08T09:51:57.417Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1.hx3ANw== with availability status: true
2016-01-08T09:51:57.417Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.hx3ANw==
,2016-01-08T09:51:57.418Z SendDataConnector.js: do connect now
,2016-01-08 10:51:57.419 ThaliTest[1480:3175528] jxcore: connect Apple-Iphone6-1.hx3ANw==
,2016-01-08 10:51:57.420 ThaliTest[1480:3175528] client: connect: unreachable Apple-Iphone6-1.hx3ANw==
2016-01-08 10:51:57.420 ThaliTest[1480:3175528] jxcore: connect: fail: Peer unreachable
2016-01-08T09:51:57.421Z SendDataConnector.js: CLIENT connected ,to 0, error: Peer unreachable
2016-01-08T09:51:57.422Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T09:51:57.422Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T09:52:02.429Z SendDataConnector.js: re-try now : Apple-Iphone6-1.hx3ANw==
,2016-01-08T09:52:02.430Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.hx3ANw==
,2016-01-08 10:52:06.292 ThaliTest[1480:3175304] multipeer session: restart
,2016-01-08 10:52:07.435 ThaliTest[1480:3175528] jxcore: disconnect
2016-01-08 10:52:07.436 ThaliTest[1480:3175528] jxcore: disconnect: fail
2016-01-08T09:52:07.437Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.hx3ANw==
20,16-01-08T09:52:07.438Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1.hx3ANw== with availability status: true
2016-01-08T09:52:07.438Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.hx3ANw==
2016-01-08T09:52:07.43,8Z SendDataConnector.js: do connect now
,2016-01-08 10:52:07.439 ThaliTest[1480:3175528] jxcore: connect Apple-Iphone6-1.hx3ANw==
2016-01-08 10:52:07.440 ThaliTest[1480:3175528] client: connect: unreachable Apple-Iphone6-1.hx3ANw==
2016-01-08 10:52:07.440 ThaliTest[1480:3175528] jxcore: connect: fail: Peer unreachable
,2016-01-08T09:52:07.442Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T09:52:07.443Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T09:52:07.444Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T09:52:12.450Z SendDataConnector.js: re-try now : Apple-Iphone6-1.hx3ANw==
,2016-01-08T09:52:12.452Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.hx3ANw==
,2016-01-08 10:52:17.456 ThaliTest[1480:3175528] jxcore: disconnect
2016-01-08 10:52:17.457 ThaliTest[1480:3175528] jxcore: disconnect: fail
2016-01-08T09:52:17.458Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.hx3ANw==
20,16-01-08T09:52:17.459Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1.hx3ANw== with availability status: true
2016-01-08T09:52:17.460Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.hx3ANw==
,2016-01-08T09:52:17.461Z SendDataConnector.js: do connect now
,2016-01-08 10:52:17.462 ThaliTest[1480:3175528] jxcore: connect Apple-Iphone6-1.hx3ANw==
,2016-01-08 10:52:17.464 ThaliTest[1480:3175528] client: connect: unreachable Apple-Iphone6-1.hx3ANw==
2016-01-08 10:52:17.464 ThaliTest[1480:3175528] jxcore: connect: fail: Peer unreachable
2016-01-08T09:52:17.465Z SendDataConnector.js: CLIENT connected ,to 0, error: Peer unreachable
2016-01-08T09:52:17.465Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
2016-01-08T09:52:17.468Z SendDataConnector.js: CLIENT Stop now
,2016-01-08 10:52:17.470 ThaliTest[1480:3175528] jxcore: disconnect
2016-01-08 10:52:17.471 ThaliTest[1480:3175528] jxcore: disconnect: fail
2016-01-08T09:52:17.471Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.hx3ANw==
,---- round done--------
startWithNextDevice
,device[2]: Apple-Iphone5-1.AdDQ5g==
,2016-01-08T09:52:17.475Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.AdDQ5g==
,2016-01-08T09:52:17.475Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.AdDQ5g==
,2016-01-08T09:52:17.476Z SendDataConnector.js: do connect now
,2016-01-08 10:52:17.477 ThaliTest[1480:3175528] jxcore: connect Apple-Iphone5-1.AdDQ5g==
2016-01-08 10:52:17.478 ThaliTest[1480:3175528] client session: connect
2016-01-08 10:52:17.478 ThaliTest[1480:3175528] client session: stateChange:0->1 Apple-Iphone5-1.AdDQ5g==
,2016-01-08 10:52:17.493 ThaliTest[1480:3175304] client: lost peer: Apple-Iphone5-1.AdDQ5g==
2016-01-08 10:52:17.494 ThaliTest[1480:3175304] client session: onPeerLost: Apple-Iphone5-1.AdDQ5g==
2016-01-08 10:52:17.494 ThaliTest[1480:3175304] client sessio,n: onLinkFailure: Apple-Iphone5-1.AdDQ5g==
2016-01-08 10:52:17.494 ThaliTest[1480:3175304] client session: disconnect
2016-01-08 10:52:17.495 ThaliTest[1480:3175304] client session: stateChange:1->0 Apple-Iphone5-1.AdDQ5g==
,2016-01-08 10:52:17.549 ThaliTest[1480:3175304] client session: fireConnectCallback: Apple-Iphone5-1.AdDQ5g==
2016-01-08 10:52:17.550 ThaliTest[1480:3175304] jxcore: connect: fail: Peer disconnected
2016-01-08T09:52:17.551Z SendDataConnector.js: CLIENT c,onnected to 0, error: Peer disconnected
2016-01-08T09:52:17.551Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-08T09:52:17.552Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.AdDQ5g==","peerName":"(null)","peerAvailable":false}]
,2016-01-08T09:52:22.552Z SendDataConnector.js: re-try now : Apple-Iphone5-1.AdDQ5g==
,2016-01-08T09:52:22.553Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.AdDQ5g==
,2016-01-08 10:52:27.563 ThaliTest[1480:3175528] jxcore: disconnect
2016-01-08 10:52:27.563 ThaliTest[1480:3175528] jxcore: disconnect: fail
2016-01-08T09:52:27.564Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.AdDQ5g==
20,16-01-08T09:52:27.565Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1.AdDQ5g== with availability status: true
2016-01-08T09:52:27.565Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.AdDQ5g==
2016-01-08T09:52:27.56,5Z SendDataConnector.js: do connect now
,2016-01-08 10:52:27.566 ThaliTest[1480:3175528] jxcore: connect Apple-Iphone5-1.AdDQ5g==
2016-01-08 10:52:27.566 ThaliTest[1480:3175528] client: connect: unreachable Apple-Iphone5-1.AdDQ5g==
2016-01-08 10:52:27.567 ThaliTest[1480:3175528] jxcore: connect: fail: Peer unreachable
,2016-01-08T09:52:27.568Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T09:52:27.569Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T09:52:27.569Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08 10:52:28.794 ThaliTest[1480:3175304] multipeer session: reset timer
2016-01-08 10:52:28.796 ThaliTest[1480:3175304] multipeer session: stop timer
2016-01-08 10:52:28.796 ThaliTest[1480:3175304] multipeer session: start timer: 0x18371590
2016-,01-08 10:52:28.797 ThaliTest[1480:3175304] server session: connect
2016-01-08 10:52:28.797 ThaliTest[1480:3175304] server session: stateChange:0->1 Apple-Iphone6-1
,2016-01-08 10:52:28.807 ThaliTest[1480:3175304] server: accepting invitation Apple-Iphone6-1
,2016-01-08 10:52:29.446 ThaliTest[1480:3175304] multipeer session: reset timer
2016-01-08 10:52:29.446 ThaliTest[1480:3175304] multipeer session: stop timer
2016-01-08 10:52:29.447 ThaliTest[1480:3175304] multipeer session: start timer: 0x18371590
2016-,01-08 10:52:29.447 ThaliTest[1480:3175304] server session: connect
2016-01-08 10:52:29.448 ThaliTest[1480:3175304] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-08 10:52:29.460 ThaliTest[1480:3175304] server: accepting invitation Apple-IpadAir2-1
,2016-01-08 10:52:31.623 ThaliTest[1480:3176095] server session: connected
2016-01-08 10:52:31.624 ThaliTest[1480:3176095] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-08 10:52:31.634 ThaliTest[1480:3175304] server relay: connected (to port: 56517)
,2016-01-08T09:52:31.644Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T09:52:32.134Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2016-01-08T09:52:32.156Z SendDataTCPServer.js: TCP/IP server has received 12045 bytes of data
,2016-01-08T09:52:32.176Z SendDataTCPServer.js: TCP/IP server has received 22995 bytes of data
,2016-01-08T09:52:32.196Z SendDataTCPServer.js: TCP/IP server has received 38325 bytes of data
,2016-01-08T09:52:32.218Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2016-01-08T09:52:32.233Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2016-01-08T09:52:32.248Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2016-01-08T09:52:32.269Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2016-01-08T09:52:32.284Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2016-01-08T09:52:32.299Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 10:52:32.400 ThaliTest[1480:3176091] server session: not connected Apple-Iphone6-1
,2016-01-08T09:52:32.572Z SendDataConnector.js: re-try now : Apple-Iphone5-1.AdDQ5g==
,2016-01-08T09:52:32.573Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.AdDQ5g==
,2016-01-08 10:52:32.675 ThaliTest[1480:3176091] server session: connected
2016-01-08 10:52:32.675 ThaliTest[1480:3176091] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-08 10:52:32.688 ThaliTest[1480:3175304] server relay: connected (to port: 56517)
,2016-01-08T09:52:32.700Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T09:52:33.127Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2016-01-08T09:52:33.142Z SendDataTCPServer.js: TCP/IP server has received 12045 bytes of data
,2016-01-08T09:52:33.163Z SendDataTCPServer.js: TCP/IP server has received 25185 bytes of data
,2016-01-08T09:52:33.179Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2016-01-08T09:52:33.197Z SendDataTCPServer.js: TCP/IP server has received 40515 bytes of data
,2016-01-08T09:52:33.211Z SendDataTCPServer.js: TCP/IP server has received 53655 bytes of data
,2016-01-08T09:52:33.228Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2016-01-08T09:52:33.244Z SendDataTCPServer.js: TCP/IP server has received 86292 bytes of data
,2016-01-08T09:52:33.258Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 10:52:33.367 ThaliTest[1480:3176113] server session: not connected Apple-IpadAir2-1
,2016-01-08 10:52:37.584 ThaliTest[1480:3175528] jxcore: disconnect
2016-01-08 10:52:37.585 ThaliTest[1480:3175528] jxcore: disconnect: fail
2016-01-08T09:52:37.586Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.AdDQ5g==
20,16-01-08T09:52:37.586Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1.AdDQ5g== with availability status: true
2016-01-08T09:52:37.586Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.AdDQ5g==
2016-01-08T09:52:37.58,7Z SendDataConnector.js: do connect now
2016-01-08 10:52:37.587 ThaliTest[1480:3175528] jxcore: connect Apple-Iphone5-1.AdDQ5g==
,2016-01-08 10:52:37.588 ThaliTest[1480:3175528] client: connect: unreachable Apple-Iphone5-1.AdDQ5g==
,2016-01-08 10:52:37.589 ThaliTest[1480:3175528] jxcore: connect: fail: Peer unreachable
,2016-01-08T09:52:37.590Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T09:52:37.591Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T09:52:37.591Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T09:52:42.598Z SendDataConnector.js: re-try now : Apple-Iphone5-1.AdDQ5g==
,2016-01-08T09:52:42.599Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.AdDQ5g==
,2016-01-08 10:52:47.601 ThaliTest[1480:3175528] jxcore: disconnect
2016-01-08 10:52:47.602 ThaliTest[1480:3175528] jxcore: disconnect: fail
2016-01-08T09:52:47.602Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.AdDQ5g==
20,16-01-08T09:52:47.603Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1.AdDQ5g== with availability status: true
2016-01-08T09:52:47.603Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.AdDQ5g==
2016-01-08T09:52:47.603Z SendDataConnector.js: do connect now
,2016-01-08 10:52:47.604 ThaliTest[1480:3175528] jxcore: connect Apple-Iphone5-1.AdDQ5g==
,2016-01-08 10:52:47.605 ThaliTest[1480:3175528] client: connect: unreachable Apple-Iphone5-1.AdDQ5g==
,2016-01-08 10:52:47.606 ThaliTest[1480:3175528] jxcore: connect: fail: Peer unreachable
,2016-01-08T09:52:47.607Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T09:52:47.608Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T09:52:47.608Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T09:52:52.609Z SendDataConnector.js: re-try now : Apple-Iphone5-1.AdDQ5g==
,2016-01-08T09:52:52.610Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.AdDQ5g==
,2016-01-08 10:52:57.617 ThaliTest[1480:3175528] jxcore: disconnect
2016-01-08 10:52:57.618 ThaliTest[1480:3175528] jxcore: disconnect: fail
2016-01-08T09:52:57.618Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.AdDQ5g==
20,16-01-08T09:52:57.619Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1.AdDQ5g== with availability status: true
2016-01-08T09:52:57.619Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.AdDQ5g==
2016-01-08T09:52:57.61,9Z SendDataConnector.js: do connect now
,2016-01-08 10:52:57.620 ThaliTest[1480:3175528] jxcore: connect Apple-Iphone5-1.AdDQ5g==
2016-01-08 10:52:57.621 ThaliTest[1480:3175528] client: connect: unreachable Apple-Iphone5-1.AdDQ5g==
2016-01-08 10:52:57.622 ThaliTest[1480:3175528] jxcore: connect,: fail: Peer unreachable
2016-01-08T09:52:57.623Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T09:52:57.623Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
2016-01-08T09:52:57.624Z Send,DataConnector.js: CLIENT Stop now
,2016-01-08 10:52:57.624 ThaliTest[1480:3175528] jxcore: disconnect
2016-01-08 10:52:57.625 ThaliTest[1480:3175528] jxcore: disconnect: fail
2016-01-08T09:52:57.625Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.AdDQ5g==
,---- round done--------
startWithNextDevice
,device[3]: Apple-IpadAir2-1.7azU7Q==
2016-01-08T09:52:57.628Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.7azU7Q==
2016-01-08T09:52:57.629Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.7azU7Q==
2016-01-08T09:52:57.,629Z SendDataConnector.js: do connect now
,2016-01-08 10:52:57.629 ThaliTest[1480:3175528] jxcore: connect Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:52:57.630 ThaliTest[1480:3175528] client session: connect
,2016-01-08 10:52:57.631 ThaliTest[1480:3175528] client session: stateChange:0->1 Apple-IpadAir2-1.7azU7Q==
,2016-01-08 10:52:57.644 ThaliTest[1480:3175304] client: lost peer: Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:52:57.644 ThaliTest[1480:3175304] client session: onPeerLost: Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:52:57.644 ThaliTest[1480:3175304] client sess,ion: onLinkFailure: Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:52:57.645 ThaliTest[1480:3175304] client session: disconnect
2016-01-08 10:52:57.645 ThaliTest[1480:3175304] client session: stateChange:1->0 Apple-IpadAir2-1.7azU7Q==
,2016-01-08 10:52:57.702 ThaliTest[1480:3175304] client session: fireConnectCallback: Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:52:57.702 ThaliTest[1480:3175304] jxcore: connect: fail: Peer disconnected
2016-01-08T09:52:57.703Z SendDataConnector.js: CLIENT ,connected to 0, error: Peer disconnected
2016-01-08T09:52:57.703Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-08T09:52:57.704Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ip,adAir2-1.7azU7Q==","peerName":"(null)","peerAvailable":false}]
,2016-01-08 10:52:59.448 ThaliTest[1480:3175304] multipeer session: restart
,2016-01-08 10:52:59.499 ThaliTest[1480:3175304] client: found peer: Apple-Iphone5-1.AdDQ5g==
2016-01-08 10:52:59.500 ThaliTest[1480:3175304] client: found peer: Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:52:59.501 ThaliTest[1480:3175304] client: found peer:, Apple-Iphone6-1.0EeFvA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.AdDQ5g==","peerName":"(null)","peerAvailable":true}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.7azU7Q==","peerName":"(null)","peerAvailable":true}]
,2016-01-08T09:53:02.705Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.7azU7Q==
,2016-01-08T09:53:02.706Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.7azU7Q==
,2016-01-08 10:53:04.051 ThaliTest[1480:3175304] multipeer session: reset timer
2016-01-08 10:53:04.051 ThaliTest[1480:3175304] multipeer session: stop timer
2016-01-08 10:53:04.051 ThaliTest[1480:3175304] multipeer session: start timer: 0x18371590
2016-,01-08 10:53:04.052 ThaliTest[1480:3175304] server session: connect
2016-01-08 10:53:04.052 ThaliTest[1480:3175304] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-08 10:53:04.063 ThaliTest[1480:3175304] server: accepting invitation Apple-Iphone5-1
,2016-01-08 10:53:07.072 ThaliTest[1480:3176170] server session: connected
,2016-01-08 10:53:07.074 ThaliTest[1480:3176170] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-08 10:53:07.081 ThaliTest[1480:3175304] server relay: connected (to port: 56517)
,2016-01-08T09:53:07.088Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08 10:53:07.716 ThaliTest[1480:3175528] jxcore: disconnect
2016-01-08 10:53:07.717 ThaliTest[1480:3175528] jxcore: disconnect: fail
2016-01-08T09:53:07.717Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.7azU7Q==
2,016-01-08T09:53:07.718Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1.7azU7Q== with availability status: true
2016-01-08T09:53:07.718Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.7azU7Q==
,2016-01-08T09:53:07.718Z SendDataConnector.js: do connect now
,2016-01-08 10:53:07.722 ThaliTest[1480:3175528] jxcore: connect Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:53:07.722 ThaliTest[1480:3175528] client session: connect
2016-01-08 10:53:07.723 ThaliTest[1480:3175528] client session: stateChange:0->1 Apple-IpadAir2-1.7azU7Q==
,2016-01-08T09:53:08.135Z SendDataTCPServer.js: TCP/IP server has received 14235 bytes of data
,2016-01-08T09:53:08.177Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2016-01-08T09:53:08.194Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2016-01-08T09:53:08.210Z SendDataTCPServer.js: TCP/IP server has received 44895 bytes of data
,2016-01-08T09:53:08.224Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2016-01-08T09:53:08.255Z SendDataTCPServer.js: TCP/IP server has received 64605 bytes of data
,2016-01-08T09:53:08.269Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2016-01-08T09:53:08.282Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2016-01-08T09:53:08.295Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 10:53:08.335 ThaliTest[1480:3176172] server session: not connected Apple-Iphone5-1
,2016-01-08 10:53:11.390 ThaliTest[1480:3176172] client session: connected
2016-01-08 10:53:11.390 ThaliTest[1480:3176172] client session: stateChange:1->2 Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:53:11.394 ThaliTest[1480:3176172] client session: fireConne,ctCallback: Apple-IpadAir2-1.7azU7Q==
,2016-01-08 10:53:11.394 ThaliTest[1480:3176172] jxcore: connect: success
,2016-01-08T09:53:11.396Z SendDataConnector.js: CLIENT connected to 56526, error: null
2016-01-08T09:53:11.397Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 10:53:11.404 ThaliTest[1480:3175304] client: relay established
2016-01-08 10:53:11.404 ThaliTest[1480:3175304] client: new accepted socket: 0x1835e1a0
,2016-01-08T09:53:11.420Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T09:53:12.034Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-08T09:53:12.047Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-08T09:53:12.233Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-08T09:53:12.373Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T09:53:12.374Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T09:53:12.376Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T09:53:12.376Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 10:53:12.379 ThaliTest[1480:3175528] jxcore: disconnect
,2016-01-08 10:53:12.381 ThaliTest[1480:3175528] client session: disconnectFromPeer: Apple-IpadAir2-1.7azU7Q==
,2016-01-08 10:53:12.383 ThaliTest[1480:3175528] client session: disconnect
,2016-01-08 10:53:12.384 ThaliTest[1480:3175528] client session: stateChange:2->0 Apple-IpadAir2-1.7azU7Q==
,2016-01-08 10:53:12.469 ThaliTest[1480:3175528] jxcore: disconnect: success
,2016-01-08T09:53:12.471Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.7azU7Q==
,---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone6-1.0EeFvA==
,2016-01-08T09:53:12.475Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.0EeFvA==
,2016-01-08T09:53:12.475Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.0EeFvA==
,2016-01-08T09:53:12.476Z SendDataConnector.js: do connect now
,2016-01-08 10:53:12.477 ThaliTest[1480:3175528] jxcore: connect Apple-Iphone6-1.0EeFvA==
,2016-01-08 10:53:12.479 ThaliTest[1480:3175528] client session: connect
,2016-01-08 10:53:12.480 ThaliTest[1480:3175528] client session: stateChange:0->1 Apple-Iphone6-1.0EeFvA==
,2016-01-08 10:53:15.480 ThaliTest[1480:3176114] client session: connected
2016-01-08 10:53:15.480 ThaliTest[1480:3176114] client session: stateChange:1->2 Apple-Iphone6-1.0EeFvA==
,2016-01-08 10:53:15.487 ThaliTest[1480:3176114] client session: fireConnectCallback: Apple-Iphone6-1.0EeFvA==
2016-01-08 10:53:15.488 ThaliTest[1480:3176114] jxcore: connect: success
2016-01-08T09:53:15.489Z SendDataConnector.js: CLIENT connected to 56529, error: null
2016-01-08T09:53:15.490Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 10:53:15.494 ThaliTest[1480:3175304] client: relay established
,2016-01-08 10:53:15.496 ThaliTest[1480:3175304] client: new accepted socket: 0x184e7e60
,2016-01-08T09:53:15.507Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T09:53:16.044Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-08T09:53:16.093Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-08T09:53:16.109Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-08T09:53:16.133Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-08T09:53:16.134Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T09:53:16.134Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T09:53:16.135Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 10:53:16.135 ThaliTest[1480:3175528] jxcore: disconnect
,2016-01-08 10:53:16.136 ThaliTest[1480:3175528] client session: disconnectFromPeer: Apple-Iphone6-1.0EeFvA==
,2016-01-08 10:53:16.137 ThaliTest[1480:3175528] client session: disconnect
,2016-01-08 10:53:16.137 ThaliTest[1480:3175528] client session: stateChange:2->0 Apple-Iphone6-1.0EeFvA==
,2016-01-08 10:53:16.204 ThaliTest[1480:3175528] jxcore: disconnect: success
,2016-01-08T09:53:16.205Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.0EeFvA==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-08T09:53:16.222Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T09:53:16.222Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 10:53:34.053 ThaliTest[1480:3175304] multipeer session: restart
,teardown
,testSendData stopped
,2016-01-08 10:53:34.836 ThaliTest[1480:3175528] jxcore: stopBroadcasting
2016-01-08 10:53:34.837 ThaliTest[1480:3175528] THEMultipeerSession stopping peer
2016-01-08 10:53:34.837 ThaliTest[1480:3175528] multipeer session: stop timer
2016-01-08 10:53:34.,837 ThaliTest[1480:3175528] server session: disconnect
2016-01-08 10:53:34.838 ThaliTest[1480:3175528] server session: stateChange:2->0 Apple-Iphone6-1
2016-01-08 10:53:34.844 ThaliTest[1480:3175528] server session: disconnect
2016-01-08 10:53:34.845 Th,aliTest[1480:3175528] server session: stateChange:2->0 Apple-IpadAir2-1
2016-01-08 10:53:34.853 ThaliTest[1480:3175528] server session: disconnect
2016-01-08 10:53:34.854 ThaliTest[1480:3175528] server session: stateChange:2->0 Apple-Iphone5-1
2016-01-0,8 10:53:34.863 ThaliTest[1480:3175528] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2016-01-08T09:53:34.904Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-08T09:53:34.906Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-08T09:53:34.908Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-08T09:53:34.911Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
