#### Test 55431344148e3f8_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55431344148e3f8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/E951193F-5859-4FE1-BD15-4583ED2D8F2B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/E951193F-5859-4FE1-BD15-4583ED2D8F2B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55431344148e3f8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55431344148e3f8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/552BA688-2769-4FA0-99B8-5679F4DA3F2F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49984"
,(lldb)     command script import "/tmp/E951193F-5859-4FE1-BD15-4583ED2D8F2B/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 10:46:48.654 ThaliTest[1488:3211216] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/16956D27-9127-49A0-B328-57C50E9E655C/Library/Cookies/Cookies.binarycookies
,2016-01-08 10:46:49.016 ThaliTest[1488:3211216] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 10:46:49.017 ThaliTest[1488:3211216] Multi-tasking -> Device: YES, App: YES
,2016-01-08 10:46:49.027 ThaliTest[1488:3211216] Unlimited access to network resources
,2016-01-08 10:46:49.038 ThaliTest[1488:3211216] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 10:46:57.998 ThaliTest[1488:3211216] Resetting plugins due to page load.
,2016-01-08 10:47:01.401 ThaliTest[1488:3211216] Finished load of: file:///var/mobile/Containers/Bundle/Application/552BA688-2769-4FA0-99B8-5679F4DA3F2F/ThaliTest.app/www/index.html
,2016-01-08 10:47:01.561 ThaliTest[1488:3211216] JXcore Cordova plugin initializing
,2016-01-08 10:47:01.562 ThaliTest[1488:3211425] JXcore instance initializing
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
,2016-01-08 10:47:02.758 ThaliTest[1488:3211216] THREAD WARNING: ['JXcore'] took '73.156738' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-08 10:51:34.242 ThaliTest[1488:3211425] jxcore: startBroadcasting
,2016-01-08 10:51:34.261 ThaliTest[1488:3211425] server: starting Apple-Iphone6-1.hx3ANw==
,2016-01-08 10:51:34.262 ThaliTest[1488:3211425] multipeer session: start timer: 0x194535a0
2016-01-08 10:51:34.263 ThaliTest[1488:3211425] THEMultipeerSession initialized peer Apple-Iphone6-1
,2016-01-08 10:51:34.265 ThaliTest[1488:3211425] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-08 10:51:35.482 ThaliTest[1488:3211216] client: found peer: Apple-Iphone5s-1.1B6pGw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.1B6pGw==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5s-1.1B6pGw==, peerAvailable: true
weAreDoneNow
,done, now sending data to server
,2016-01-08 10:51:35.492 ThaliTest[1488:3211216] client: found peer: Apple-IpadAir2-1.TL+VGA==
,2016-01-08 10:51:35.891 ThaliTest[1488:3211216] client: found peer: Apple-Iphone5-1.rHC9Aw==
,teardown
,testFindPeers stopped
2016-01-08 10:51:36.124 ThaliTest[1488:3211425] jxcore: stopBroadcasting
,2016-01-08 10:51:36.124 ThaliTest[1488:3211425] THEMultipeerSession stopping peer
,2016-01-08 10:51:36.125 ThaliTest[1488:3211425] multipeer session: stop timer
2016-01-08 10:51:36.126 ThaliTest[1488:3211425] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 64347
,2016-01-08 10:51:36.284 ThaliTest[1488:3211425] jxcore: startBroadcasting
,2016-01-08 10:51:36.291 ThaliTest[1488:3211425] server: starting Apple-Iphone6-1.0EeFvA==
2016-01-08 10:51:36.291 ThaliTest[1488:3211425] multipeer session: start timer: 0x1945e120
2016-01-08 10:51:36.292 ThaliTest[1488:3211425] THEMultipeerSession initi,alized peer Apple-Iphone6-1
2016-01-08 10:51:36.292 ThaliTest[1488:3211425] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
2016-01-08T09:51:36.296Z SendDataTCPServer.js: TCP/IP server is bound to port: 64347
,2016-01-08 10:51:37.263 ThaliTest[1488:3211216] client: found peer: Apple-Iphone5s-1.1B6pGw==
2016-01-08 10:51:37.264 ThaliTest[1488:3211216] client: found peer: Apple-IpadAir2-1.TL+VGA==
2016-01-08 10:51:37.264 ThaliTest[1488:3211216] client: found peer,: Apple-Iphone5-1.rHC9Aw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.1B6pGw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone5s-1.1B6pGw==
2016-01-08T09:51:37.270Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.1B6pGw==
2016-01-08T09:51:37.271Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.1B6pGw==
2016-01-08T09:51:37.271Z SendDataConnector.js: do connect now
,2016-01-08 10:51:37.274 ThaliTest[1488:3211425] jxcore: connect Apple-Iphone5s-1.1B6pGw==
2016-01-08 10:51:37.275 ThaliTest[1488:3211425] client session: connect
2016-01-08 10:51:37.276 ThaliTest[1488:3211216] client: found peer: Apple-Iphone5-1.AdDQ5g==,
2016-01-08 10:51:37.276 ThaliTest[1488:3211425] client session: stateChange:0->1 Apple-Iphone5s-1.1B6pGw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.TL+VGA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.rHC9Aw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.AdDQ5g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 10:51:37.982 ThaliTest[1488:3211216] client: lost peer: Apple-Iphone5s-1.1B6pGw==
,2016-01-08 10:51:37.983 ThaliTest[1488:3211216] client session: onPeerLost: Apple-Iphone5s-1.1B6pGw==
2016-01-08 10:51:37.985 ThaliTest[1488:3211216] client session: onLinkFailure: Apple-Iphone5s-1.1B6pGw==
2016-01-08 10:51:37.985 ThaliTest[1488:3211216], client session: disconnect
2016-01-08 10:51:37.986 ThaliTest[1488:3211216] client session: stateChange:1->0 Apple-Iphone5s-1.1B6pGw==
2016-01-08 10:51:37.986 ThaliTest[1488:3211216] client session: fireConnectCallback: Apple-Iphone5s-1.1B6pGw==
,2016-01-08 10:51:37.987 ThaliTest[1488:3211216] jxcore: connect: fail: Peer disconnected
,2016-01-08 10:51:37.989 ThaliTest[1488:3211216] client: lost peer: Apple-IpadAir2-1.TL+VGA==
2016-01-08 10:51:37.991 ThaliTest[1488:3211216] client session: onPeerLost: Apple-IpadAir2-1.TL+VGA==
2016-01-08T09:51:37.991Z SendDataConnector.js: CLIENT conne,cted to 0, error: Peer disconnected
2016-01-08 10:51:37.991 ThaliTest[1488:3211216] client: found peer: Apple-IpadAir2-1.7azU7Q==
2016-01-08T09:51:37.992Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-08T09:51:37.992Z SendDataC,onnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.1B6pGw==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.TL+VGA==","peerName":"(null)","peerAvaila,ble":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.7azU7Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 10:51:38.119 ThaliTest[1488:3211216] client: found peer: Apple-Iphone5s-1.KjG2gw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.KjG2gw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08T09:51:43.002Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.1B6pGw==
,2016-01-08T09:51:43.003Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.1B6pGw==
,2016-01-08 10:51:43.438 ThaliTest[1488:3211216] client: lost peer: Apple-Iphone5-1.rHC9Aw==
2016-01-08 10:51:43.439 ThaliTest[1488:3211216] client session: onPeerLost: Apple-Iphone5-1.rHC9Aw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.rHC9Aw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08 10:51:48.014 ThaliTest[1488:3211425] jxcore: disconnect
2016-01-08 10:51:48.014 ThaliTest[1488:3211425] jxcore: disconnect: fail
2016-01-08T09:51:48.015Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.1B6pGw==
2,016-01-08T09:51:48.016Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1.1B6pGw== with availability status: true
2016-01-08T09:51:48.016Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.1B6pGw==
,2016-01-08T09:51:48.016Z SendDataConnector.js: do connect now
,2016-01-08 10:51:48.018 ThaliTest[1488:3211425] jxcore: connect Apple-Iphone5s-1.1B6pGw==
2016-01-08 10:51:48.018 ThaliTest[1488:3211425] client: connect: unreachable Apple-Iphone5s-1.1B6pGw==
2016-01-08 10:51:48.019 ThaliTest[1488:3211425] jxcore: conne,ct: fail: Peer unreachable
2016-01-08T09:51:48.019Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T09:51:48.019Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T09:51:48.020Z SendDataConnector.j,s: tryAgain afer: 5000 ms.
,2016-01-08T09:51:53.030Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.1B6pGw==
,2016-01-08T09:51:53.031Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.1B6pGw==
,2016-01-08 10:51:58.036 ThaliTest[1488:3211425] jxcore: disconnect
2016-01-08 10:51:58.037 ThaliTest[1488:3211425] jxcore: disconnect: fail
2016-01-08T09:51:58.037Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.1B6pGw==
2,016-01-08T09:51:58.038Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1.1B6pGw== with availability status: true
2016-01-08T09:51:58.038Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.1B6pGw==
2016-01-08T09:51:58,.038Z SendDataConnector.js: do connect now
,2016-01-08 10:51:58.041 ThaliTest[1488:3211425] jxcore: connect Apple-Iphone5s-1.1B6pGw==
2016-01-08 10:51:58.041 ThaliTest[1488:3211425] client: connect: unreachable Apple-Iphone5s-1.1B6pGw==
2016-01-08 10:51:58.042 ThaliTest[1488:3211425] jxcore: conne,ct: fail: Peer unreachable
2016-01-08T09:51:58.042Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T09:51:58.042Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T09:51:58.043Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T09:52:03.048Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.1B6pGw==
,2016-01-08T09:52:03.049Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.1B6pGw==
,2016-01-08 10:52:06.293 ThaliTest[1488:3211216] multipeer session: restart
,2016-01-08 10:52:06.340 ThaliTest[1488:3211216] client: found peer: Apple-Iphone5-1.AdDQ5g==
2016-01-08 10:52:06.340 ThaliTest[1488:3211216] client: found peer: Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:52:06.341 ThaliTest[1488:3211216] client: found peer: Apple-Iphone5s-1.KjG2gw==
,2016-01-08 10:52:08.062 ThaliTest[1488:3211425] jxcore: disconnect
2016-01-08 10:52:08.062 ThaliTest[1488:3211425] jxcore: disconnect: fail
2016-01-08T09:52:08.063Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.1B6pGw==
2,016-01-08T09:52:08.063Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1.1B6pGw== with availability status: true
2016-01-08T09:52:08.063Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.1B6pGw==
,2016-01-08T09:52:08.064Z SendDataConnector.js: do connect now
2016-01-08 10:52:08.064 ThaliTest[1488:3211425] jxcore: connect Apple-Iphone5s-1.1B6pGw==
,2016-01-08 10:52:08.065 ThaliTest[1488:3211425] client: connect: unreachable Apple-Iphone5s-1.1B6pGw==
,2016-01-08 10:52:08.066 ThaliTest[1488:3211425] jxcore: connect: fail: Peer unreachable
,2016-01-08T09:52:08.066Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T09:52:08.067Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T09:52:08.067Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T09:52:13.072Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.1B6pGw==
,2016-01-08T09:52:13.072Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.1B6pGw==
,2016-01-08 10:52:18.081 ThaliTest[1488:3211425] jxcore: disconnect
2016-01-08 10:52:18.081 ThaliTest[1488:3211425] jxcore: disconnect: fail
2016-01-08T09:52:18.082Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.1B6pGw==
2,016-01-08T09:52:18.082Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1.1B6pGw== with availability status: true
2016-01-08T09:52:18.083Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.1B6pGw==
2016-01-08T09:52:18,.083Z SendDataConnector.js: do connect now
,2016-01-08 10:52:18.084 ThaliTest[1488:3211425] jxcore: connect Apple-Iphone5s-1.1B6pGw==
2016-01-08 10:52:18.085 ThaliTest[1488:3211425] client: connect: unreachable Apple-Iphone5s-1.1B6pGw==
2016-01-08 10:52:18.085 ThaliTest[1488:3211425] jxcore: conne,ct: fail: Peer unreachable
2016-01-08T09:52:18.086Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T09:52:18.087Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2016-01-08T09:52:18.089Z SendDataConnector.js: CLIENT Stop now
,2016-01-08 10:52:18.090 ThaliTest[1488:3211425] jxcore: disconnect
2016-01-08 10:52:18.091 ThaliTest[1488:3211425] jxcore: disconnect: fail
2016-01-08T09:52:18.091Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.1B6pGw==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1.AdDQ5g==
,2016-01-08T09:52:18.095Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.AdDQ5g==
,2016-01-08T09:52:18.095Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.AdDQ5g==
,2016-01-08T09:52:18.096Z SendDataConnector.js: do connect now
,2016-01-08 10:52:18.097 ThaliTest[1488:3211425] jxcore: connect Apple-Iphone5-1.AdDQ5g==
2016-01-08 10:52:18.097 ThaliTest[1488:3211425] client session: connect
2016-01-08 10:52:18.097 ThaliTest[1488:3211425] client session: stateChange:0->1 Apple-Iphone,5-1.AdDQ5g==
,2016-01-08 10:52:21.959 ThaliTest[1488:3212227] client session: connected
2016-01-08 10:52:21.962 ThaliTest[1488:3212227] client session: stateChange:1->2 Apple-Iphone5-1.AdDQ5g==
,2016-01-08 10:52:22.469 ThaliTest[1488:3212259] client session: fireConnectCallback: Apple-Iphone5-1.AdDQ5g==
2016-01-08 10:52:22.470 ThaliTest[1488:3212259] jxcore: connect: success
2016-01-08T09:52:22.472Z SendDataConnector.js: CLIENT connected to 6435,2, error: null
2016-01-08T09:52:22.473Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 10:52:22.476 ThaliTest[1488:3211216] client: relay established
2016-01-08 10:52:22.477 ThaliTest[1488:3211216] client: new accepted socket: 0x19466300
,2016-01-08T09:52:22.493Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T09:52:23.029Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-08T09:52:23.065Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-08T09:52:23.125Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-08T09:52:23.530Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T09:52:23.531Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T09:52:23.532Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T09:52:23.533Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 10:52:23.535 ThaliTest[1488:3211425] jxcore: disconnect
2016-01-08 10:52:23.536 ThaliTest[1488:3211425] client session: disconnectFromPeer: Apple-Iphone5-1.AdDQ5g==
2016-01-08 10:52:23.536 ThaliTest[1488:3211425] client session: disconnect
20,16-01-08 10:52:23.536 ThaliTest[1488:3211425] client session: stateChange:2->0 Apple-Iphone5-1.AdDQ5g==
,2016-01-08 10:52:23.551 ThaliTest[1488:3211425] jxcore: disconnect: success
2016-01-08T09:52:23.552Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.AdDQ5g==
---- round done--------
startWithNextDevice
device[3]: Apple-Ipad,Air2-1.7azU7Q==
2016-01-08T09:52:23.553Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.7azU7Q==
2016-01-08T09:52:23.554Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.7azU7Q==
2016-01-08T09:52:23.554Z SendDataConnecto,r.js: do connect now
2016-01-08 10:52:23.554 ThaliTest[1488:3211425] jxcore: connect Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:52:23.555 ThaliTest[1488:3211425] client session: connect
2016-01-08 10:52:23.555 ThaliTest[1488:3211425] client session: stateChange:0->1 Apple-IpadAir2-1.7azU7Q==
,2016-01-08 10:52:27.359 ThaliTest[1488:3212297] client session: connected
2016-01-08 10:52:27.359 ThaliTest[1488:3212297] client session: stateChange:1->2 Apple-IpadAir2-1.7azU7Q==
,2016-01-08 10:52:27.986 ThaliTest[1488:3212259] client session: fireConnectCallback: Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:52:27.987 ThaliTest[1488:3212259] jxcore: connect: success
2016-01-08T09:52:27.988Z SendDataConnector.js: CLIENT connected to 64355, error: null
2016-01-08T09:52:27.989Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 10:52:27.993 ThaliTest[1488:3211216] client: relay established
2016-01-08 10:52:27.993 ThaliTest[1488:3211216] client: new accepted socket: 0x19474960
,2016-01-08T09:52:28.006Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T09:52:28.547Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-08T09:52:28.560Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-08T09:52:28.598Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-08T09:52:28.610Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-08T09:52:28.611Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-08T09:52:28.611Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T09:52:28.611Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 10:52:28.612 ThaliTest[1488:3211425] jxcore: disconnect
2016-01-08 10:52:28.612 ThaliTest[1488:3211425] client session: disconnectFromPeer: Apple-IpadAir2-1.7azU7Q==
2016-01-08 10:52:28.612 ThaliTest[1488:3211425] client session: disconnect
2016-01-08 10:52:28.612 ThaliTest[1488:3211425] client session: stateChange:2->0 Apple-IpadAir2-1.7azU7Q==
,2016-01-08 10:52:28.617 ThaliTest[1488:3211425] jxcore: disconnect: success
2016-01-08T09:52:28.617Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.7azU7Q==
---- round done--------
startWithNextDevice
device[4]: Apple-Iph,one5s-1.KjG2gw==
2016-01-08T09:52:28.618Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.KjG2gw==
2016-01-08T09:52:28.618Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.KjG2gw==
2016-01-08T09:52:28.618Z SendDataConnector.js: do connect now
,2016-01-08 10:52:28.618 ThaliTest[1488:3211425] jxcore: connect Apple-Iphone5s-1.KjG2gw==
2016-01-08 10:52:28.619 ThaliTest[1488:3211425] client session: connect
2016-01-08 10:52:28.619 ThaliTest[1488:3211425] client session: stateChange:0->1 Apple-Iphone5s-1.KjG2gw==
,2016-01-08 10:52:31.642 ThaliTest[1488:3212297] client session: connected
2016-01-08 10:52:31.642 ThaliTest[1488:3212297] client session: stateChange:1->2 Apple-Iphone5s-1.KjG2gw==
,2016-01-08 10:52:31.679 ThaliTest[1488:3212227] client session: fireConnectCallback: Apple-Iphone5s-1.KjG2gw==
2016-01-08 10:52:31.680 ThaliTest[1488:3212227] jxcore: connect: success
2016-01-08T09:52:31.681Z SendDataConnector.js: CLIENT connected to 64358, error: null
2016-01-08T09:52:31.681Z SendDataConnector.js: CLIENT starting client 
2016-01-08 10:52:31.684 ThaliTest[1488:3211216] client: relay established
,2016-01-08 10:52:31.684 ThaliTest[1488:3211216] client: new accepted socket: 0x193e2460
,2016-01-08T09:52:31.697Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T09:52:32.235Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-08T09:52:32.248Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-08T09:52:32.309Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-08T09:52:32.373Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-08T09:52:32.373Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-08T09:52:32.373Z SendDataConnector.js: CLIENT Stop now
2016-01-08T09:52:32.374Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 10:52:32.374 ThaliTest[1488:3211425] jxcore: disconnect
2016-01-08 10:52:32.374 ThaliTest[1488:3211425] client session: disconnectFromPeer: Apple-Iphone5s-1.KjG2gw==
2016-01-08 10:52:32.374 ThaliTest[1488:3211425] client session: disconnect
2016-01-08 10:52:32.374 ThaliTest[1488:3211425] client session: stateChange:2->0 Apple-Iphone5s-1.KjG2gw==
,2016-01-08 10:52:32.378 ThaliTest[1488:3211425] jxcore: disconnect: success
2016-01-08T09:52:32.379Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.KjG2gw==
---- round done--------
startWithNextDevice
,weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
,2016-01-08T09:52:32.391Z SendDataConnector.js: CLIENT Stop now
2016-01-08T09:52:32.391Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 10:52:33.486 ThaliTest[1488:3211216] multipeer session: reset timer
2016-01-08 10:52:33.487 ThaliTest[1488:3211216] multipeer session: stop timer
2016-01-08 10:52:33.487 ThaliTest[1488:3211216] multipeer session: start timer: 0x1945e120
2016-,01-08 10:52:33.487 ThaliTest[1488:3211216] server session: connect
2016-01-08 10:52:33.488 ThaliTest[1488:3211216] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-08 10:52:33.497 ThaliTest[1488:3211216] server: accepting invitation Apple-IpadAir2-1
,2016-01-08 10:52:36.704 ThaliTest[1488:3212259] server session: connected
,2016-01-08 10:52:36.705 ThaliTest[1488:3212259] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-08 10:52:36.761 ThaliTest[1488:3211216] server relay: connected (to port: 64347)
,2016-01-08T09:52:36.769Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T09:52:37.213Z SendDataTCPServer.js: TCP/IP server has received 4238 bytes of data
,2016-01-08T09:52:37.228Z SendDataTCPServer.js: TCP/IP server has received 15259 bytes of data
,2016-01-08T09:52:37.247Z SendDataTCPServer.js: TCP/IP server has received 28328 bytes of data
,2016-01-08T09:52:37.261Z SendDataTCPServer.js: TCP/IP server has received 51465 bytes of data
,2016-01-08T09:52:37.280Z SendDataTCPServer.js: TCP/IP server has received 53655 bytes of data
,2016-01-08T09:52:37.295Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2016-01-08T09:52:37.311Z SendDataTCPServer.js: TCP/IP server has received 75555 bytes of data
,2016-01-08T09:52:37.324Z SendDataTCPServer.js: TCP/IP server has received 86505 bytes of data
,2016-01-08T09:52:37.338Z SendDataTCPServer.js: TCP/IP server has received 88695 bytes of data
,2016-01-08T09:52:37.351Z SendDataTCPServer.js: TCP/IP server has received 95194 bytes of data
,2016-01-08T09:52:37.366Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 10:52:37.479 ThaliTest[1488:3212227] server session: not connected Apple-IpadAir2-1
,2016-01-08 10:53:03.489 ThaliTest[1488:3211216] multipeer session: restart
,2016-01-08 10:53:03.531 ThaliTest[1488:3211216] client: found peer: Apple-Iphone5s-1.KjG2gw==
2016-01-08 10:53:03.532 ThaliTest[1488:3211216] client: found peer: Apple-Iphone5-1.AdDQ5g==
2016-01-08 10:53:03.532 ThaliTest[1488:3211216] client: found peer: Apple-IpadAir2-1.7azU7Q==
,2016-01-08 10:53:08.826 ThaliTest[1488:3211216] multipeer session: reset timer
2016-01-08 10:53:08.826 ThaliTest[1488:3211216] multipeer session: stop timer
2016-01-08 10:53:08.827 ThaliTest[1488:3211216] multipeer session: start timer: 0x1945e120
2016-01-08 10:53:08.827 ThaliTest[1488:3211216] server session: connect
2016-01-08 10:53:08.827 ThaliTest[1488:3211216] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-08 10:53:08.837 ThaliTest[1488:3211216] server: accepting invitation Apple-Iphone5-1
,2016-01-08 10:53:11.481 ThaliTest[1488:3212380] server session: connected
2016-01-08 10:53:11.483 ThaliTest[1488:3212380] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-08 10:53:11.491 ThaliTest[1488:3211216] server relay: connected (to port: 64347)
,2016-01-08T09:53:11.494Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T09:53:12.534Z SendDataTCPServer.js: TCP/IP server has received 5475 bytes of data
,2016-01-08T09:53:12.549Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2016-01-08T09:53:12.804Z SendDataTCPServer.js: TCP/IP server has received 16354 bytes of data
,2016-01-08T09:53:12.820Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2016-01-08T09:53:12.838Z SendDataTCPServer.js: TCP/IP server has received 63084 bytes of data
,2016-01-08T09:53:12.853Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2016-01-08T09:53:12.876Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2016-01-08T09:53:12.926Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2016-01-08T09:53:12.944Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2016-01-08T09:53:12.958Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 10:53:12.995 ThaliTest[1488:3211216] multipeer session: reset timer
2016-01-08 10:53:12.996 ThaliTest[1488:3211216] multipeer session: stop timer
2016-01-08 10:53:12.996 ThaliTest[1488:3211216] multipeer session: start timer: 0x1945e120
,2016-01-08 10:53:12.997 ThaliTest[1488:3211216] server session: connect
,2016-01-08 10:53:12.997 ThaliTest[1488:3211216] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-08 10:53:13.008 ThaliTest[1488:3211216] server: accepting invitation Apple-Iphone5s-1
,2016-01-08 10:53:13.252 ThaliTest[1488:3212259] server session: not connected Apple-Iphone5-1
,2016-01-08 10:53:15.489 ThaliTest[1488:3212259] server session: connected
2016-01-08 10:53:15.490 ThaliTest[1488:3212259] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-08T09:53:15.544Z SendDataTCPServer.js: TCP/IP server connected
2016-01-08 10:53:15.545 ThaliTest[1488:3211216] server relay: connected (to port: 64347)
,2016-01-08T09:53:16.010Z SendDataTCPServer.js: TCP/IP server has received 12045 bytes of data
,2016-01-08T09:53:16.024Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2016-01-08T09:53:16.037Z SendDataTCPServer.js: TCP/IP server has received 29565 bytes of data
,2016-01-08T09:53:16.052Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2016-01-08T09:53:16.066Z SendDataTCPServer.js: TCP/IP server has received 49275 bytes of data
,2016-01-08T09:53:16.081Z SendDataTCPServer.js: TCP/IP server has received 55845 bytes of data
,2016-01-08T09:53:16.095Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2016-01-08T09:53:16.110Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2016-01-08T09:53:16.138Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2016-01-08T09:53:16.151Z SendDataTCPServer.js: TCP/IP server has received 97455 bytes of data
,2016-01-08T09:53:16.167Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 10:53:16.208 ThaliTest[1488:3212370] server session: not connected Apple-Iphone5s-1
,teardown
,testSendData stopped
,2016-01-08 10:53:34.883 ThaliTest[1488:3211425] jxcore: stopBroadcasting
2016-01-08 10:53:34.884 ThaliTest[1488:3211425] THEMultipeerSession stopping peer
2016-01-08 10:53:34.884 ThaliTest[1488:3211425] multipeer session: stop timer
2016-01-08 10:53:34.,885 ThaliTest[1488:3211425] server session: disconnect
2016-01-08 10:53:34.885 ThaliTest[1488:3211425] server session: stateChange:2->0 Apple-Iphone5s-1
,2016-01-08 10:53:34.896 ThaliTest[1488:3211425] server session: disconnect
2016-01-08 10:53:34.897 ThaliTest[1488:3211425] server session: stateChange:2->0 Apple-IpadAir2-1
,2016-01-08 10:53:34.967 ThaliTest[1488:3211425] server session: disconnect
2016-01-08 10:53:34.968 ThaliTest[1488:3211425] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-08 10:53:34.972 ThaliTest[1488:3211425] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-08T09:53:34.989Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-08T09:53:34.990Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-08T09:53:34.992Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-08T09:53:34.993Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
