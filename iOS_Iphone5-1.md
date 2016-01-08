#### Test 55431344148e3f8_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55431344148e3f8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/4C20B001-2F29-4EF5-8AF9-F120AC5669B2/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/4C20B001-2F29-4EF5-8AF9-F120AC5669B2/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55431344148e3f8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55431344148e3f8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2DA7998B-EEB3-44F4-9B0A-3273631243B5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49949"
,(lldb)     command script import "/tmp/4C20B001-2F29-4EF5-8AF9-F120AC5669B2/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 10:45:21.182 ThaliTest[1075:3550176] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1110584E-003C-4F81-B734-E1A391421A6F/Library/Cookies/Cookies.binarycookies
,2016-01-08 10:45:21.695 ThaliTest[1075:3550176] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 10:45:21.696 ThaliTest[1075:3550176] Multi-tasking -> Device: YES, App: YES
,2016-01-08 10:45:21.703 ThaliTest[1075:3550176] Unlimited access to network resources
,2016-01-08 10:45:21.713 ThaliTest[1075:3550176] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 10:45:32.455 ThaliTest[1075:3550176] Resetting plugins due to page load.
,2016-01-08 10:45:35.995 ThaliTest[1075:3550176] Finished load of: file:///var/mobile/Containers/Bundle/Application/2DA7998B-EEB3-44F4-9B0A-3273631243B5/ThaliTest.app/www/index.html
,2016-01-08 10:45:36.210 ThaliTest[1075:3550176] JXcore Cordova plugin initializing
,2016-01-08 10:45:36.212 ThaliTest[1075:3550364] JXcore instance initializing
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
,2016-01-08 10:45:38.912 ThaliTest[1075:3550176] THREAD WARNING: ['JXcore'] took '156.929199' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-08 10:51:34.265 ThaliTest[1075:3550364] jxcore: startBroadcasting
,2016-01-08 10:51:34.276 ThaliTest[1075:3550364] server: starting Apple-Iphone5-1.rHC9Aw==
2016-01-08 10:51:34.278 ThaliTest[1075:3550364] multipeer session: start timer: 0x1da195b0
2016-01-08 10:51:34.278 ThaliTest[1075:3550364] THEMultipeerSession initi,alized peer Apple-Iphone5-1
2016-01-08 10:51:34.279 ThaliTest[1075:3550364] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-08 10:51:35.432 ThaliTest[1075:3550176] client: found peer: Apple-Iphone5s-1.1B6pGw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.1B6pGw==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5s-1.1B6pGw==, peerAvailable: true
,2016-01-08 10:51:35.435 ThaliTest[1075:3550176] client: found peer: Apple-Iphone6-1.hx3ANw==
,weAreDoneNow
done, now sending data to server
,2016-01-08 10:51:35.820 ThaliTest[1075:3550176] client: found peer: Apple-IpadAir2-1.TL+VGA==
,teardown
,testFindPeers stopped
,2016-01-08 10:51:36.188 ThaliTest[1075:3550364] jxcore: stopBroadcasting
2016-01-08 10:51:36.189 ThaliTest[1075:3550364] THEMultipeerSession stopping peer
2016-01-08 10:51:36.189 ThaliTest[1075:3550364] multipeer session: stop timer
2016-01-08 10:51:36.189 ThaliTest[1075:3550364] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 65354
,2016-01-08 10:51:36.227 ThaliTest[1075:3550364] jxcore: startBroadcasting
,2016-01-08 10:51:36.230 ThaliTest[1075:3550364] server: starting Apple-Iphone5-1.AdDQ5g==
2016-01-08 10:51:36.233 ThaliTest[1075:3550364] multipeer session: start timer: 0x1db15530
2016-01-08 10:51:36.234 ThaliTest[1075:3550364] THEMultipeerSession initi,alized peer Apple-Iphone5-1
2016-01-08 10:51:36.234 ThaliTest[1075:3550364] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
,2016-01-08T09:51:36.243Z SendDataTCPServer.js: TCP/IP server is bound to port: 65354
,2016-01-08 10:51:36.279 ThaliTest[1075:3550176] client: found peer: Apple-Iphone6-1.hx3ANw==
2016-01-08 10:51:36.279 ThaliTest[1075:3550176] client: found peer: Apple-Iphone5s-1.1B6pGw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.hx3ANw=,=","peerName":"(null)","peerAvailable":true}]
2016-01-08 10:51:36.281 ThaliTest[1075:3550176] client: found peer: Apple-IpadAir2-1.TL+VGA==
Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone6-1.hx3ANw==
,2016-01-08T09:51:36.290Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.hx3ANw==
,2016-01-08T09:51:36.291Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.hx3ANw==
,2016-01-08T09:51:36.291Z SendDataConnector.js: do connect now
,2016-01-08 10:51:36.292 ThaliTest[1075:3550364] jxcore: connect Apple-Iphone6-1.hx3ANw==
,2016-01-08 10:51:36.294 ThaliTest[1075:3550364] client session: connect
,2016-01-08 10:51:36.295 ThaliTest[1075:3550364] client session: stateChange:0->1 Apple-Iphone6-1.hx3ANw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.1B6pGw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.TL+VGA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-08 10:51:37.436 ThaliTest[1075:3550176] client: lost peer: Apple-Iphone6-1.hx3ANw==
2016-01-08 10:51:37.436 ThaliTest[1075:3550176] client session: onPeerLost: Apple-Iphone6-1.hx3ANw==
2016-01-08 10:51:37.436 ThaliTest[1075:3550176] client sessio,n: onLinkFailure: Apple-Iphone6-1.hx3ANw==
2016-01-08 10:51:37.437 ThaliTest[1075:3550176] client session: disconnect
2016-01-08 10:51:37.437 ThaliTest[1075:3550176] client session: stateChange:1->0 Apple-Iphone6-1.hx3ANw==
2016-01-08 10:51:37.438 Thali,Test[1075:3550176] client session: fireConnectCallback: Apple-Iphone6-1.hx3ANw==
2016-01-08 10:51:37.438 ThaliTest[1075:3550176] jxcore: connect: fail: Peer disconnected
2016-01-08T09:51:37.439Z SendDataConnector.js: CLIENT connected to 0, error: Peer di,sconnected
2016-01-08T09:51:37.439Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-08T09:51:37.440Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.hx3ANw==","peerName":",(null)","peerAvailable":false}]
,2016-01-08 10:51:37.993 ThaliTest[1075:3550176] client: lost peer: Apple-Iphone5s-1.1B6pGw==
2016-01-08 10:51:37.994 ThaliTest[1075:3550176] client session: onPeerLost: Apple-Iphone5s-1.1B6pGw==
2016-01-08 10:51:37.994 ThaliTest[1075:3550176] client: los,t peer: Apple-IpadAir2-1.TL+VGA==
2016-01-08 10:51:37.994 ThaliTest[1075:3550176] client session: onPeerLost: Apple-IpadAir2-1.TL+VGA==
2016-01-08 10:51:37.994 ThaliTest[1075:3550176] client: found peer: Apple-IpadAir2-1.7azU7Q==
peerAvailabilityChanged, [{"peerIdentifier":"Apple-Iphone5s-1.1B6pGw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.TL+VGA==","peerName":"(null)","peerAvailable":false}]
Found pe,er : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.7azU7Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 10:51:38.006 ThaliTest[1075:3550176] client: found peer: Apple-Iphone5s-1.KjG2gw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.KjG2gw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 10:51:38.158 ThaliTest[1075:3550176] client: found peer: Apple-Iphone6-1.0EeFvA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.0EeFvA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-08T09:51:42.452Z SendDataConnector.js: re-try now : Apple-Iphone6-1.hx3ANw==
,2016-01-08T09:51:42.453Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.hx3ANw==
,2016-01-08 10:51:47.463 ThaliTest[1075:3550364] jxcore: disconnect
2016-01-08 10:51:47.464 ThaliTest[1075:3550364] jxcore: disconnect: fail
2016-01-08T09:51:47.464Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.hx3ANw==
20,16-01-08T09:51:47.465Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1.hx3ANw== with availability status: true
2016-01-08T09:51:47.465Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.hx3ANw==
2016-01-08T09:51:47.465Z SendDataConnector.js: do connect now
,2016-01-08 10:51:47.466 ThaliTest[1075:3550364] jxcore: connect Apple-Iphone6-1.hx3ANw==
2016-01-08 10:51:47.467 ThaliTest[1075:3550364] client: connect: unreachable Apple-Iphone6-1.hx3ANw==
2016-01-08 10:51:47.467 ThaliTest[1075:3550364] jxcore: connect,: fail: Peer unreachable
,2016-01-08T09:51:47.467Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T09:51:47.468Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T09:51:47.469Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T09:51:52.480Z SendDataConnector.js: re-try now : Apple-Iphone6-1.hx3ANw==
,2016-01-08T09:51:52.480Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.hx3ANw==
,2016-01-08 10:51:57.490 ThaliTest[1075:3550364] jxcore: disconnect
2016-01-08 10:51:57.491 ThaliTest[1075:3550364] jxcore: disconnect: fail
2016-01-08T09:51:57.491Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.hx3ANw==
20,16-01-08T09:51:57.492Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1.hx3ANw== with availability status: true
2016-01-08T09:51:57.492Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.hx3ANw==
2016-01-08T09:51:57.493Z SendDataConnector.js: do connect now
,2016-01-08 10:51:57.494 ThaliTest[1075:3550364] jxcore: connect Apple-Iphone6-1.hx3ANw==
2016-01-08 10:51:57.494 ThaliTest[1075:3550364] client: connect: unreachable Apple-Iphone6-1.hx3ANw==
2016-01-08 10:51:57.494 ThaliTest[1075:3550364] jxcore: connect,: fail: Peer unreachable
2016-01-08T09:51:57.495Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-08T09:51:57.495Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T09:51:57.496Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T09:52:02.502Z SendDataConnector.js: re-try now : Apple-Iphone6-1.hx3ANw==
,2016-01-08T09:52:02.502Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.hx3ANw==
,2016-01-08 10:52:06.235 ThaliTest[1075:3550176] multipeer session: restart
,2016-01-08 10:52:07.511 ThaliTest[1075:3550364] jxcore: disconnect
2016-01-08 10:52:07.511 ThaliTest[1075:3550364] jxcore: disconnect: fail
2016-01-08T09:52:07.512Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.hx3ANw==
20,16-01-08T09:52:07.512Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1.hx3ANw== with availability status: true
2016-01-08T09:52:07.512Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.hx3ANw==
2016-01-08T09:52:07.513Z SendDataConnector.js: do connect now
,2016-01-08 10:52:07.514 ThaliTest[1075:3550364] jxcore: connect Apple-Iphone6-1.hx3ANw==
2016-01-08 10:52:07.514 ThaliTest[1075:3550364] client: connect: unreachable Apple-Iphone6-1.hx3ANw==
2016-01-08 10:52:07.514 ThaliTest[1075:3550364] jxcore: connect,: fail: Peer unreachable
2016-01-08T09:52:07.515Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-08T09:52:07.515Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T09:52:07.515Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T09:52:12.528Z SendDataConnector.js: re-try now : Apple-Iphone6-1.hx3ANw==
,2016-01-08T09:52:12.528Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.hx3ANw==
,2016-01-08 10:52:17.534 ThaliTest[1075:3550364] jxcore: disconnect
2016-01-08 10:52:17.534 ThaliTest[1075:3550364] jxcore: disconnect: fail
2016-01-08T09:52:17.535Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.hx3ANw==
20,16-01-08T09:52:17.535Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1.hx3ANw== with availability status: true
2016-01-08T09:52:17.536Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.hx3ANw==
2016-01-08T09:52:17.53,6Z SendDataConnector.js: do connect now
,2016-01-08 10:52:17.537 ThaliTest[1075:3550364] jxcore: connect Apple-Iphone6-1.hx3ANw==
2016-01-08 10:52:17.537 ThaliTest[1075:3550364] client: connect: unreachable Apple-Iphone6-1.hx3ANw==
2016-01-08 10:52:17.538 ThaliTest[1075:3550364] jxcore: connect: fail: Peer unreachable
,2016-01-08T09:52:17.538Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T09:52:17.538Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2016-01-08T09:52:17.540Z SendDataConnector.js: CLIENT Stop now
2016-01-08 10:52:17.540 ThaliTest[1075:3550364] jxcore: disconnect
2016-01-08 10:52:17.541 ThaliTest[1075:3550364] jxcore: disconnect: fail
2016-01-08T09:52:17.541Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.hx3ANw==
---- round done--------
startWithNextDevice
,device[2]: Apple-IpadAir2-1.7azU7Q==
2016-01-08T09:52:17.542Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.7azU7Q==
2016-01-08T09:52:17.542Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.7azU7Q==
2016-01-08T09:52:17.542Z SendDataConnector.js: do connect now
,2016-01-08 10:52:17.543 ThaliTest[1075:3550364] jxcore: connect Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:52:17.544 ThaliTest[1075:3550364] client session: connect
2016-01-08 10:52:17.544 ThaliTest[1075:3550364] client session: stateChange:0->1 Apple-IpadAir2-1.7azU7Q==
,2016-01-08 10:52:17.552 ThaliTest[1075:3550176] client: lost peer: Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:52:17.552 ThaliTest[1075:3550176] client session: onPeerLost: Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:52:17.552 ThaliTest[1075:3550176] client sess,ion: onLinkFailure: Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:52:17.552 ThaliTest[1075:3550176] client session: disconnect
2016-01-08 10:52:17.552 ThaliTest[1075:3550176] client session: stateChange:1->0 Apple-IpadAir2-1.7azU7Q==
,2016-01-08 10:52:17.606 ThaliTest[1075:3550176] client session: fireConnectCallback: Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:52:17.607 ThaliTest[1075:3550176] jxcore: connect: fail: Peer disconnected
2016-01-08T09:52:17.608Z SendDataConnector.js: CLIENT ,connected to 0, error: Peer disconnected
2016-01-08T09:52:17.608Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-08T09:52:17.609Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ip,adAir2-1.7azU7Q==","peerName":"(null)","peerAvailable":false}]
,2016-01-08 10:52:18.864 ThaliTest[1075:3550176] multipeer session: reset timer
2016-01-08 10:52:18.864 ThaliTest[1075:3550176] multipeer session: stop timer
2016-01-08 10:52:18.864 ThaliTest[1075:3550176] multipeer session: start timer: 0x1db15530
2016-,01-08 10:52:18.864 ThaliTest[1075:3550176] server session: connect
2016-01-08 10:52:18.865 ThaliTest[1075:3550176] server session: stateChange:0->1 Apple-Iphone6-1
,2016-01-08 10:52:18.870 ThaliTest[1075:3550176] server: accepting invitation Apple-Iphone6-1
,2016-01-08 10:52:21.950 ThaliTest[1075:3551304] server session: connected
2016-01-08 10:52:21.950 ThaliTest[1075:3551304] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-08 10:52:22.013 ThaliTest[1075:3550176] server relay: connected (to port: 65354)
,2016-01-08T09:52:22.018Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T09:52:22.617Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.7azU7Q==
,2016-01-08T09:52:22.618Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.7azU7Q==
,2016-01-08T09:52:22.997Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2016-01-08T09:52:23.012Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2016-01-08T09:52:23.028Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2016-01-08T09:52:23.045Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2016-01-08T09:52:23.060Z SendDataTCPServer.js: TCP/IP server has received 56869 bytes of data
,2016-01-08T09:52:23.074Z SendDataTCPServer.js: TCP/IP server has received 80888 bytes of data
,2016-01-08T09:52:23.089Z SendDataTCPServer.js: TCP/IP server has received 86505 bytes of data
,2016-01-08T09:52:23.514Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 10:52:23.582 ThaliTest[1075:3551280] server session: not connected Apple-Iphone6-1
,2016-01-08 10:52:23.677 ThaliTest[1075:3550176] multipeer session: reset timer
2016-01-08 10:52:23.677 ThaliTest[1075:3550176] multipeer session: stop timer
2016-01-08 10:52:23.678 ThaliTest[1075:3550176] multipeer session: start timer: 0x1db15530
2016-,01-08 10:52:23.678 ThaliTest[1075:3550176] server session: connect
2016-01-08 10:52:23.678 ThaliTest[1075:3550176] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-08 10:52:23.685 ThaliTest[1075:3550176] server: accepting invitation Apple-IpadAir2-1
,2016-01-08 10:52:27.264 ThaliTest[1075:3551278] server session: connected
2016-01-08 10:52:27.264 ThaliTest[1075:3551278] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-08 10:52:27.626 ThaliTest[1075:3550364] jxcore: disconnect
2016-01-08 10:52:27.627 ThaliTest[1075:3550364] jxcore: disconnect: fail
2016-01-08T09:52:27.627Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.7azU7Q==
2,016-01-08T09:52:27.628Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1.7azU7Q== with availability status: true
2016-01-08T09:52:27.628Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.7azU7Q==
2016-01-08T09:52:27,.629Z SendDataConnector.js: do connect now
,2016-01-08 10:52:27.629 ThaliTest[1075:3550364] jxcore: connect Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:52:27.630 ThaliTest[1075:3550364] client: connect: unreachable Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:52:27.630 ThaliTest[1075:3550364] jxcore: connect: fail: Peer unreachable
,2016-01-08T09:52:27.631Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T09:52:27.631Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-08T09:52:27.631Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08 10:52:28.231 ThaliTest[1075:3550176] server relay: connected (to port: 65354)
,2016-01-08T09:52:28.238Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T09:52:28.252Z SendDataTCPServer.js: TCP/IP server has received 5475 bytes of data
,2016-01-08T09:52:28.266Z SendDataTCPServer.js: TCP/IP server has received 14235 bytes of data
,2016-01-08T09:52:28.307Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2016-01-08T09:52:28.321Z SendDataTCPServer.js: TCP/IP server has received 45919 bytes of data
,2016-01-08T09:52:28.337Z SendDataTCPServer.js: TCP/IP server has received 63439 bytes of data
,2016-01-08T09:52:28.351Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2016-01-08T09:52:28.365Z SendDataTCPServer.js: TCP/IP server has received 75555 bytes of data
,2016-01-08T09:52:28.404Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2016-01-08T09:52:28.422Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2016-01-08T09:52:28.434Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 10:52:28.960 ThaliTest[1075:3551278] server session: not connected Apple-IpadAir2-1
,2016-01-08T09:52:32.634Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.7azU7Q==
,2016-01-08T09:52:32.635Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.7azU7Q==
,2016-01-08 10:52:37.637 ThaliTest[1075:3550364] jxcore: disconnect
2016-01-08 10:52:37.637 ThaliTest[1075:3550364] jxcore: disconnect: fail
2016-01-08T09:52:37.638Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.7azU7Q==
2,016-01-08T09:52:37.638Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1.7azU7Q== with availability status: true
2016-01-08T09:52:37.639Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.7azU7Q==
2016-01-08T09:52:37.639Z SendDataConnector.js: do connect now
,2016-01-08 10:52:37.640 ThaliTest[1075:3550364] jxcore: connect Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:52:37.641 ThaliTest[1075:3550364] client: connect: unreachable Apple-IpadAir2-1.7azU7Q==
,2016-01-08 10:52:37.641 ThaliTest[1075:3550364] jxcore: connect: fail: Peer unreachable
,2016-01-08T09:52:37.642Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-08T09:52:37.643Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T09:52:37.643Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T09:52:42.644Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.7azU7Q==
,2016-01-08T09:52:42.645Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.7azU7Q==
,2016-01-08 10:52:47.649 ThaliTest[1075:3550364] jxcore: disconnect
2016-01-08 10:52:47.650 ThaliTest[1075:3550364] jxcore: disconnect: fail
2016-01-08T09:52:47.650Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.7azU7Q==
2,016-01-08T09:52:47.651Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1.7azU7Q== with availability status: true
2016-01-08T09:52:47.651Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.7azU7Q==
2016-01-08T09:52:47,.651Z SendDataConnector.js: do connect now
,2016-01-08 10:52:47.652 ThaliTest[1075:3550364] jxcore: connect Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:52:47.653 ThaliTest[1075:3550364] client: connect: unreachable Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:52:47.653 ThaliTest[1075:3550364] jxcore: conne,ct: fail: Peer unreachable
,2016-01-08T09:52:47.653Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T09:52:47.654Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T09:52:47.654Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T09:52:52.665Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.7azU7Q==
,2016-01-08T09:52:52.666Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.7azU7Q==
,2016-01-08 10:52:53.679 ThaliTest[1075:3550176] multipeer session: restart
,2016-01-08 10:52:53.711 ThaliTest[1075:3550176] client: found peer: Apple-Iphone6-1.0EeFvA==
2016-01-08 10:52:53.711 ThaliTest[1075:3550176] client: found peer: Apple-Iphone5s-1.KjG2gw==
2016-01-08 10:52:53.712 ThaliTest[1075:3550176] client: found peer:, Apple-IpadAir2-1.7azU7Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.7azU7Q==","peerName":"(null)","peerAvailable":true}]
,2016-01-08 10:52:57.674 ThaliTest[1075:3550364] jxcore: disconnect
2016-01-08 10:52:57.674 ThaliTest[1075:3550364] jxcore: disconnect: fail
2016-01-08T09:52:57.675Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.7azU7Q==
2016-01-08T09:52:57.676Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1.7azU7Q== with availability status: true
,2016-01-08T09:52:57.677Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.7azU7Q==
2016-01-08T09:52:57.677Z SendDataConnector.js: do connect now
2016-01-08 10:52:57.678 ThaliTest[1075:3550364] jxcore: connect Apple-IpadAir2-1.7azU7Q==
,2016-01-08 10:52:57.678 ThaliTest[1075:3550364] client session: connect
2016-01-08 10:52:57.678 ThaliTest[1075:3550364] client session: stateChange:0->1 Apple-IpadAir2-1.7azU7Q==
,2016-01-08 10:53:01.530 ThaliTest[1075:3551407] client session: connected
2016-01-08 10:53:01.530 ThaliTest[1075:3551407] client session: stateChange:1->2 Apple-IpadAir2-1.7azU7Q==
,2016-01-08 10:53:02.302 ThaliTest[1075:3551408] client session: fireConnectCallback: Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:53:02.302 ThaliTest[1075:3551408] jxcore: connect: success
2016-01-08T09:53:02.303Z SendDataConnector.js: CLIENT connected to 65362, error: null
,2016-01-08T09:53:02.304Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 10:53:02.307 ThaliTest[1075:3550176] client: relay established
2016-01-08 10:53:02.307 ThaliTest[1075:3550176] client: new accepted socket: 0x1dc363d0
,2016-01-08T09:53:02.320Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T09:53:03.432Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-08T09:53:03.495Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-08T09:53:03.557Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T09:53:03.558Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T09:53:03.560Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T09:53:03.560Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 10:53:03.562 ThaliTest[1075:3550364] jxcore: disconnect
,2016-01-08 10:53:03.563 ThaliTest[1075:3550364] client session: disconnectFromPeer: Apple-IpadAir2-1.7azU7Q==
,2016-01-08 10:53:03.563 ThaliTest[1075:3550364] client session: disconnect
,2016-01-08 10:53:03.564 ThaliTest[1075:3550364] client session: stateChange:2->0 Apple-IpadAir2-1.7azU7Q==
,2016-01-08 10:53:03.637 ThaliTest[1075:3550364] jxcore: disconnect: success
,2016-01-08T09:53:03.638Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.7azU7Q==
,---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone5s-1.KjG2gw==
,2016-01-08T09:53:03.641Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.KjG2gw==
,2016-01-08T09:53:03.641Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.KjG2gw==
,2016-01-08T09:53:03.642Z SendDataConnector.js: do connect now
,2016-01-08 10:53:03.642 ThaliTest[1075:3550364] jxcore: connect Apple-Iphone5s-1.KjG2gw==
,2016-01-08 10:53:03.643 ThaliTest[1075:3550364] client session: connect
,2016-01-08 10:53:03.644 ThaliTest[1075:3550364] client session: stateChange:0->1 Apple-Iphone5s-1.KjG2gw==
,2016-01-08 10:53:07.090 ThaliTest[1075:3551407] client session: connected
,2016-01-08 10:53:07.090 ThaliTest[1075:3551407] client session: stateChange:1->2 Apple-Iphone5s-1.KjG2gw==
,2016-01-08 10:53:07.154 ThaliTest[1075:3551408] client session: fireConnectCallback: Apple-Iphone5s-1.KjG2gw==
2016-01-08 10:53:07.154 ThaliTest[1075:3551408] jxcore: connect: success
2016-01-08T09:53:07.154Z SendDataConnector.js: CLIENT connected to 653,65, error: null
2016-01-08T09:53:07.155Z SendDataConnector.js: CLIENT starting client 
2016-01-08 10:53:07.157 ThaliTest[1075:3550176] client: relay established
2016-01-08 10:53:07.157 ThaliTest[1075:3550176] client: new accepted socket: 0x1dd38020
,2016-01-08T09:53:07.170Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T09:53:08.204Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-08T09:53:08.256Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-08T09:53:08.282Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-08T09:53:08.308Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-08T09:53:08.333Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-08T09:53:08.334Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-08T09:53:08.335Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T09:53:08.335Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 10:53:08.336 ThaliTest[1075:3550364] jxcore: disconnect
,2016-01-08 10:53:08.336 ThaliTest[1075:3550364] client session: disconnectFromPeer: Apple-Iphone5s-1.KjG2gw==
,2016-01-08 10:53:08.337 ThaliTest[1075:3550364] client session: disconnect
,2016-01-08 10:53:08.338 ThaliTest[1075:3550364] client session: stateChange:2->0 Apple-Iphone5s-1.KjG2gw==
,2016-01-08 10:53:08.349 ThaliTest[1075:3550364] jxcore: disconnect: success
,2016-01-08T09:53:08.357Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.KjG2gw==
,---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone6-1.0EeFvA==
,2016-01-08T09:53:08.361Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.0EeFvA==
,2016-01-08T09:53:08.361Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.0EeFvA==
,2016-01-08T09:53:08.362Z SendDataConnector.js: do connect now
,2016-01-08 10:53:08.363 ThaliTest[1075:3550364] jxcore: connect Apple-Iphone6-1.0EeFvA==
,2016-01-08 10:53:08.363 ThaliTest[1075:3550364] client session: connect
,2016-01-08 10:53:08.365 ThaliTest[1075:3550364] client session: stateChange:0->1 Apple-Iphone6-1.0EeFvA==
,2016-01-08 10:53:11.451 ThaliTest[1075:3551407] client session: connected
2016-01-08 10:53:11.451 ThaliTest[1075:3551407] client session: stateChange:1->2 Apple-Iphone6-1.0EeFvA==
,2016-01-08 10:53:11.490 ThaliTest[1075:3551447] client session: fireConnectCallback: Apple-Iphone6-1.0EeFvA==
2016-01-08 10:53:11.490 ThaliTest[1075:3551447] jxcore: connect: success
2016-01-08T09:53:11.491Z SendDataConnector.js: CLIENT connected to 65368, error: null
2016-01-08T09:53:11.492Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 10:53:11.494 ThaliTest[1075:3550176] client: relay established
2016-01-08 10:53:11.494 ThaliTest[1075:3550176] client: new accepted socket: 0x1dc36290
,2016-01-08T09:53:11.507Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T09:53:12.792Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-08T09:53:12.944Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-08T09:53:12.971Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-08T09:53:13.183Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T09:53:13.184Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T09:53:13.186Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T09:53:13.186Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 10:53:13.187 ThaliTest[1075:3550364] jxcore: disconnect
2016-01-08 10:53:13.187 ThaliTest[1075:3550364] client session: disconnectFromPeer: Apple-Iphone6-1.0EeFvA==
2016-01-08 10:53:13.188 ThaliTest[1075:3550364] client session: disconnect
2016-01-08 10:53:13.188 ThaliTest[1075:3550364] client session: stateChange:2->0 Apple-Iphone6-1.0EeFvA==
,2016-01-08 10:53:13.197 ThaliTest[1075:3550364] jxcore: disconnect: success
2016-01-08T09:53:13.197Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.0EeFvA==
---- round done--------
startWithNextDevice
weAreDoneNow, resultA,rray.length: 4
sendReportNow
done, now sending data to server
,2016-01-08T09:53:13.219Z SendDataConnector.js: CLIENT Stop now
2016-01-08T09:53:13.220Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 10:53:23.679 ThaliTest[1075:3550176] multipeer session: restart
,2016-01-08 10:53:23.711 ThaliTest[1075:3550176] client: found peer: Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:53:23.712 ThaliTest[1075:3550176] client: found peer: Apple-Iphone6-1.0EeFvA==
2016-01-08 10:53:23.712 ThaliTest[1075:3550176] client: found peer: Apple-Iphone5s-1.KjG2gw==
,teardown
,testSendData stopped
,2016-01-08 10:53:34.140 ThaliTest[1075:3550364] jxcore: stopBroadcasting
2016-01-08 10:53:34.141 ThaliTest[1075:3550364] THEMultipeerSession stopping peer
2016-01-08 10:53:34.141 ThaliTest[1075:3550364] multipeer session: stop timer
2016-01-08 10:53:34.,142 ThaliTest[1075:3550364] server session: disconnect
2016-01-08 10:53:34.142 ThaliTest[1075:3550364] server session: stateChange:2->0 Apple-Iphone6-1
2016-01-08 10:53:34.145 ThaliTest[1075:3550364] server session: disconnect
2016-01-08 10:53:34.146 ThaliTest[1075:3550364] server session: stateChange:2->0 Apple-IpadAir2-1
,2016-01-08 10:53:34.150 ThaliTest[1075:3550364] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-08T09:53:34.170Z SendDataTCPServer.js: TCP/IP server is ended
2016-01-08T09:53:34.171Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-08T09:53:34.172Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
