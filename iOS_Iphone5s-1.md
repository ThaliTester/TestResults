#### Test 50650278e3ff7c2_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278e3ff7c2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/57C5561F-1CF2-4909-B733-6CF7783E811F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/57C5561F-1CF2-4909-B733-6CF7783E811F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278e3ff7c2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278e3ff7c2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8E913DEC-1859-4093-B71A-C45D2F584FB2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55107"
,(lldb)     command script import "/tmp/57C5561F-1CF2-4909-B733-6CF7783E811F/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-14 14:37:00.641 ThaliTest[912:1150329] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/530BEF31-259D-43B8-A6BA-FA8598393FC5/Library/Cookies/Cookies.binarycookies
,2015-12-14 14:37:00.973 ThaliTest[912:1150329] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-14 14:37:00.974 ThaliTest[912:1150329] Multi-tasking -> Device: YES, App: YES
,2015-12-14 14:37:00.978 ThaliTest[912:1150329] Unlimited access to network resources
,2015-12-14 14:37:00.988 ThaliTest[912:1150329] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-14 14:37:09.320 ThaliTest[912:1150329] Resetting plugins due to page load.
,2015-12-14 14:37:11.902 ThaliTest[912:1150329] Finished load of: file:///var/mobile/Containers/Bundle/Application/8E913DEC-1859-4093-B71A-C45D2F584FB2/ThaliTest.app/www/index.html
,2015-12-14 14:37:12.106 ThaliTest[912:1150329] JXcore Cordova plugin initializing
,2015-12-14 14:37:12.107 ThaliTest[912:1150723] JXcore instance initializing
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
,2015-12-14 14:37:13.499 ThaliTest[912:1150329] THREAD WARNING: ['JXcore'] took '97.571045' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-14 14:44:00.727 ThaliTest[912:1150723] jxcore: startBroadcasting
,2015-12-14 14:44:00.750 ThaliTest[912:1150723] server: starting Apple-Iphone5s-1_PT4136.I4GUOQ==
2015-12-14 14:44:00.752 ThaliTest[912:1150723] multipeer session: start timer: 0x16ba8df0
2015-12-14 14:44:00.753 ThaliTest[912:1150723] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT4136
,2015-12-14 14:44:00.760 ThaliTest[912:1150723] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-14 14:44:01.405 ThaliTest[912:1150329] client: found peer: Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:01.406 ThaliTest[912:1150329] client: found peer: Apple-Iphone6-1_PT4340.mBVNng==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone,5-1_PT3867.cSCWVA==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5-1_PT3867.cSCWVA==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,teardown
,testFindPeers stopped
2015-12-14 14:44:02.183 ThaliTest[912:1150723] jxcore: stopBroadcasting
,2015-12-14 14:44:02.184 ThaliTest[912:1150723] THEMultipeerSession stopping peer
,2015-12-14 14:44:02.184 ThaliTest[912:1150723] multipeer session: stop timer
,2015-12-14 14:44:02.186 ThaliTest[912:1150723] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 57498
,2015-12-14 14:44:02.289 ThaliTest[912:1150723] jxcore: startBroadcasting
,2015-12-14 14:44:02.294 ThaliTest[912:1150723] server: starting Apple-Iphone5s-1_PT4136.aZvv+w==
2015-12-14 14:44:02.295 ThaliTest[912:1150723] multipeer session: start timer: 0x16c95400
2015-12-14 14:44:02.296 ThaliTest[912:1150723] THEMultipeerSession ,initialized peer Apple-Iphone5s-1_PT4136
2015-12-14 14:44:02.296 ThaliTest[912:1150723] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
,2015-12-14T13:44:02.304Z SendDataTCPServer.js: TCP/IP server is bound to port: 57498
,2015-12-14 14:44:02.322 ThaliTest[912:1150329] client: found peer: Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:02.323 ThaliTest[912:1150329] client: found peer: Apple-Iphone6-1_PT4340.mBVNng==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone,5-1_PT3867.cSCWVA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14T13:44:02.327Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT,3867.cSCWVA==
2015-12-14T13:44:02.328Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14T13:44:02.328Z SendDataConnector.js: do connect now
,2015-12-14 14:44:02.329 ThaliTest[912:1150723] jxcore: connect Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:02.330 ThaliTest[912:1150723] client session: connect
2015-12-14 14:44:02.330 ThaliTest[912:1150723] client session: stateChange:0->1 Apple-Iphone5-1_PT3867.cSCWVA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4340.mBVNng==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 14:44:03.370 ThaliTest[912:1150329] client: lost peer: Apple-Iphone6-1_PT4340.mBVNng==
2015-12-14 14:44:03.371 ThaliTest[912:1150329] client session: onPeerLost: Apple-Iphone6-1_PT4340.mBVNng==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT4340.mBVNng==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-14 14:44:03.447 ThaliTest[912:1150329] client: lost peer: Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:03.448 ThaliTest[912:1150329] client session: onPeerLost: Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:03.448 ThaliTest[912:1150329] cl,ient session: onLinkFailure: Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:03.448 ThaliTest[912:1150329] client session: disconnect
2015-12-14 14:44:03.449 ThaliTest[912:1150329] client session: stateChange:1->0 Apple-Iphone5-1_PT3867.cSCWVA==
2015-1,2-14 14:44:03.450 ThaliTest[912:1150329] client session: fireConnectCallback: Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:03.450 ThaliTest[912:1150329] jxcore: connect: fail: Peer disconnected
2015-12-14T13:44:03.451Z SendDataConnector.js: CLIENT co,nnected to 0, error: Peer disconnected
2015-12-14T13:44:03.452Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-14T13:44:03.453Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ipho,ne5-1_PT3867.cSCWVA==","peerName":"(null)","peerAvailable":false}]
,2015-12-14 14:44:04.023 ThaliTest[912:1150329] client: found peer: Apple-Iphone5-1_PT3867.0mupng==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT3867.0mupng==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 14:44:04.117 ThaliTest[912:1150329] client: found peer: Apple-IpadAir2-1_PT6041.byADbw==
2015-12-14 14:44:04.118 ThaliTest[912:1150329] client: found peer: Apple-Iphone6-1_PT4340.nJo87Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6041.byADbw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4340.nJo87Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14T13:44:08.459Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14T13:44:08.460Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14 14:44:13.463 ThaliTest[912:1150723] jxcore: disconnect
2015-12-14 14:44:13.463 ThaliTest[912:1150723] jxcore: disconnect: fail
2015-12-14T13:44:13.464Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3867.cSCWVA=,=
2015-12-14T13:44:13.464Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT3867.cSCWVA== with availability status: true
,2015-12-14T13:44:13.465Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14T13:44:13.465Z SendDataConnector.js: do connect now
,2015-12-14 14:44:13.467 ThaliTest[912:1150723] jxcore: connect Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14 14:44:13.468 ThaliTest[912:1150723] client: connect: unreachable Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14 14:44:13.468 ThaliTest[912:1150723] jxcore: connect: fail: Peer unreachable
,2015-12-14T13:44:13.470Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T13:44:13.470Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T13:44:13.470Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T13:44:18.479Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14T13:44:18.480Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14 14:44:23.485 ThaliTest[912:1150723] jxcore: disconnect
2015-12-14 14:44:23.486 ThaliTest[912:1150723] jxcore: disconnect: fail
2015-12-14T13:44:23.486Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3867.cSCWVA=,=
2015-12-14T13:44:23.487Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT3867.cSCWVA== with availability status: true
2015-12-14T13:44:23.487Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT3867.cSCWVA==
201,5-12-14T13:44:23.488Z SendDataConnector.js: do connect now
2015-12-14 14:44:23.488 ThaliTest[912:1150723] jxcore: connect Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:23.489 ThaliTest[912:1150723] client: connect: unreachable Apple-Iphone5-1_PT3867.c,SCWVA==
2015-12-14 14:44:23.489 ThaliTest[912:1150723] jxcore: connect: fail: Peer unreachable
2015-12-14T13:44:23.490Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T13:44:23.490Z SendDataConnector.js: CLIENT Can not Co,nnect: Peer unreachable
2015-12-14T13:44:23.492Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T13:44:28.496Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14T13:44:28.496Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14 14:44:32.297 ThaliTest[912:1150329] multipeer session: restart
,2015-12-14 14:44:32.358 ThaliTest[912:1150329] client: found peer: Apple-IpadAir2-1_PT6041.byADbw==
2015-12-14 14:44:32.359 ThaliTest[912:1150329] client: found peer: Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:44:32.359 ThaliTest[912:1150329] client: ,found peer: Apple-Iphone5-1_PT3867.0mupng==
,2015-12-14 14:44:33.500 ThaliTest[912:1150723] jxcore: disconnect
2015-12-14 14:44:33.501 ThaliTest[912:1150723] jxcore: disconnect: fail
2015-12-14T13:44:33.501Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3867.cSCWVA=,=
2015-12-14T13:44:33.502Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT3867.cSCWVA== with availability status: true
2015-12-14T13:44:33.502Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14T13:44:33.502Z SendDataConnector.js: do connect now
2015-12-14 14:44:33.503 ThaliTest[912:1150723] jxcore: connect Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14 14:44:33.504 ThaliTest[912:1150723] client: connect: unreachable Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:33.505 ThaliTest[912:1150723] jxcore: connect: fail: Peer unreachable
,2015-12-14T13:44:33.505Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T13:44:33.506Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T13:44:33.507Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T13:44:38.512Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14T13:44:38.513Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14 14:44:43.519 ThaliTest[912:1150723] jxcore: disconnect
2015-12-14 14:44:43.520 ThaliTest[912:1150723] jxcore: disconnect: fail
2015-12-14T13:44:43.520Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3867.cSCWVA=,=
2015-12-14T13:44:43.521Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT3867.cSCWVA== with availability status: true
2015-12-14T13:44:43.521Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14T13:44:43.521Z SendDataConnector.js: do connect now
2015-12-14 14:44:43.522 ThaliTest[912:1150723] jxcore: connect Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14 14:44:43.523 ThaliTest[912:1150723] client: connect: unreachable Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14 14:44:43.524 ThaliTest[912:1150723] jxcore: connect: fail: Peer unreachable
,2015-12-14T13:44:43.524Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T13:44:43.525Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
2015-12-14T13:44:43.527Z SendDataConnector.js: CLIENT Stop now
,2015-12-14 14:44:43.528 ThaliTest[912:1150723] jxcore: disconnect
,2015-12-14 14:44:43.529 ThaliTest[912:1150723] jxcore: disconnect: fail
,2015-12-14T13:44:43.531Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3867.cSCWVA==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1_PT3867.0mupng==
,2015-12-14T13:44:43.534Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT3867.0mupng==
,2015-12-14T13:44:43.535Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT3867.0mupng==
,2015-12-14T13:44:43.535Z SendDataConnector.js: do connect now
,2015-12-14 14:44:43.537 ThaliTest[912:1150723] jxcore: connect Apple-Iphone5-1_PT3867.0mupng==
2015-12-14 14:44:43.537 ThaliTest[912:1150723] client session: connect
2015-12-14 14:44:43.538 ThaliTest[912:1150723] client session: stateChange:0->1 Apple-Iphone5-1_PT3867.0mupng==
,2015-12-14 14:44:46.970 ThaliTest[912:1151646] client session: connected
2015-12-14 14:44:46.970 ThaliTest[912:1151646] client session: stateChange:1->2 Apple-Iphone5-1_PT3867.0mupng==
,2015-12-14 14:44:47.038 ThaliTest[912:1151661] client session: fireConnectCallback: Apple-Iphone5-1_PT3867.0mupng==
2015-12-14 14:44:47.039 ThaliTest[912:1151661] jxcore: connect: success
2015-12-14T13:44:47.040Z SendDataConnector.js: CLIENT connected to, 57503, error: null
2015-12-14T13:44:47.041Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 14:44:47.045 ThaliTest[912:1150329] client: relay established
2015-12-14 14:44:47.045 ThaliTest[912:1150329] client: new accepted socket: 0x156ac6a0
,2015-12-14T13:44:47.062Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T13:44:47.499Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T13:44:47.499Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T13:44:47.500Z SendDataConnector.js: CLIENT Stop now
2015-12-14T13:44:47.500Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 14:44:47.501 ThaliTest[912:1150723] jxcore: disconnect
2015-12-14 14:44:47.501 ThaliTest[912:1150723] client session: disconnectFromPeer: Apple-Iphone5-1_PT3867.0mupng==
2015-12-14 14:44:47.502 ThaliTest[912:1150723] client session: disconnect
2015-12-14 14:44:47.502 ThaliTest[912:1150723] client session: stateChange:2->0 Apple-Iphone5-1_PT3867.0mupng==
,2015-12-14 14:44:47.507 ThaliTest[912:1150723] jxcore: disconnect: success
2015-12-14T13:44:47.507Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3867.0mupng==
---- round done--------
startWithNextDevice
device[3]: Apple-IpadAir2-1_PT6041.byADbw==
2015-12-14T13:44:47.507Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6041.byADbw==
2015-12-14T13:44:47.508Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6041.byADbw==
2015-12-14T13:,44:47.508Z SendDataConnector.js: do connect now
2015-12-14 14:44:47.508 ThaliTest[912:1150723] jxcore: connect Apple-IpadAir2-1_PT6041.byADbw==
2015-12-14 14:44:47.508 ThaliTest[912:1150723] client session: connect
2015-12-14 14:44:47.508 ThaliTest[912:,1150723] client session: stateChange:0->1 Apple-IpadAir2-1_PT6041.byADbw==
,2015-12-14 14:44:50.671 ThaliTest[912:1151631] client session: connected
,2015-12-14 14:44:50.671 ThaliTest[912:1151631] client session: stateChange:1->2 Apple-IpadAir2-1_PT6041.byADbw==
,2015-12-14 14:44:50.695 ThaliTest[912:1151648] client session: fireConnectCallback: Apple-IpadAir2-1_PT6041.byADbw==
2015-12-14 14:44:50.696 ThaliTest[912:1151648] jxcore: connect: success
,2015-12-14T13:44:50.699Z SendDataConnector.js: CLIENT connected to 57506, error: null
,2015-12-14T13:44:50.700Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 14:44:50.704 ThaliTest[912:1150329] client: relay established
2015-12-14 14:44:50.704 ThaliTest[912:1150329] client: new accepted socket: 0x16c9cf60
,2015-12-14T13:44:50.717Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T13:44:51.166Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-14T13:44:51.192Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T13:44:51.193Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-14T13:44:51.193Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T13:44:51.193Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 14:44:51.194 ThaliTest[912:1150723] jxcore: disconnect
2015-12-14 14:44:51.194 ThaliTest[912:1150723] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6041.byADbw==
2015-12-14 14:44:51.194 ThaliTest[912:1150723] client session: disconnect
2015-12-14 14:44:51.195 ThaliTest[912:1150723] client session: stateChange:2->0 Apple-IpadAir2-1_PT6041.byADbw==
,2015-12-14 14:44:51.200 ThaliTest[912:1150723] jxcore: disconnect: success
2015-12-14T13:44:51.200Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6041.byADbw==
---- round done--------
startWithNextDevice
device[4]: App,le-Iphone6-1_PT4340.nJo87Q==
2015-12-14T13:44:51.201Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14T13:44:51.201Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14T13:44,:51.201Z SendDataConnector.js: do connect now
2015-12-14 14:44:51.202 ThaliTest[912:1150723] jxcore: connect Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:44:51.202 ThaliTest[912:1150723] client session: connect
2015-12-14 14:44:51.202 ThaliTest[912:1150723] client session: stateChange:0->1 Apple-Iphone6-1_PT4340.nJo87Q==
,2015-12-14 14:44:51.406 ThaliTest[912:1150329] multipeer session: reset timer
2015-12-14 14:44:51.406 ThaliTest[912:1150329] multipeer session: stop timer
2015-12-14 14:44:51.406 ThaliTest[912:1150329] multipeer session: start timer: 0x16c95400
,2015-12-14 14:44:51.407 ThaliTest[912:1150329] server session: connect
2015-12-14 14:44:51.409 ThaliTest[912:1150329] server session: stateChange:0->1 Apple-Iphone6-1_PT4340
,2015-12-14 14:44:51.418 ThaliTest[912:1150329] server: accepting invitation Apple-Iphone6-1_PT4340
,2015-12-14 14:44:54.005 ThaliTest[912:1151688] client session: connected
2015-12-14 14:44:54.006 ThaliTest[912:1151688] client session: stateChange:1->2 Apple-Iphone6-1_PT4340.nJo87Q==
,2015-12-14 14:44:54.245 ThaliTest[912:1151646] client session: fireConnectCallback: Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:44:54.246 ThaliTest[912:1151646] jxcore: connect: success
2015-12-14T13:44:54.247Z SendDataConnector.js: CLIENT connected to, 57509, error: null
2015-12-14T13:44:54.249Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 14:44:54.253 ThaliTest[912:1150329] client: relay established
2015-12-14 14:44:54.254 ThaliTest[912:1150329] client: new accepted socket: 0x16ca3560
,2015-12-14T13:44:54.266Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14 14:44:54.374 ThaliTest[912:1151688] server session: connected
2015-12-14 14:44:54.374 ThaliTest[912:1151688] server session: stateChange:1->2 Apple-Iphone6-1_PT4340
,2015-12-14 14:44:54.492 ThaliTest[912:1150329] server relay: connected (to port: 57498)
,2015-12-14T13:44:54.589Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T13:44:54.763Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-14T13:44:54.777Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-14T13:44:54.790Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-14T13:44:54.804Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-14T13:44:54.830Z SendDataTCPServer.js: TCP/IP server has received 89648 bytes of data
,2015-12-14T13:44:54.847Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14T13:44:54.864Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-14T13:44:55.287Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-14T13:44:55.343Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T13:44:55.344Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T13:44:55.346Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T13:44:55.348Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 14:44:55.352 ThaliTest[912:1150723] jxcore: disconnect
2015-12-14 14:44:55.353 ThaliTest[912:1150723] client session: disconnectFromPeer: Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:44:55.353 ThaliTest[912:1150723] client session: disconnect,
2015-12-14 14:44:55.354 ThaliTest[912:1150723] client session: stateChange:2->0 Apple-Iphone6-1_PT4340.nJo87Q==
,2015-12-14 14:44:55.369 ThaliTest[912:1150723] jxcore: disconnect: success
2015-12-14T13:44:55.374Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4340.nJo87Q==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
,2015-12-14T13:44:55.386Z SendDataConnector.js: CLIENT Stop now
2015-12-14T13:44:55.386Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 14:44:55.424 ThaliTest[912:1151631] server session: not connected Apple-Iphone6-1_PT4340
,2015-12-14 14:44:56.649 ThaliTest[912:1150329] multipeer session: reset timer
2015-12-14 14:44:56.649 ThaliTest[912:1150329] multipeer session: stop timer
2015-12-14 14:44:56.650 ThaliTest[912:1150329] multipeer session: start timer: 0x16c95400
2015-12-,14 14:44:56.650 ThaliTest[912:1150329] server session: connect
2015-12-14 14:44:56.650 ThaliTest[912:1150329] server session: stateChange:0->1 Apple-IpadAir2-1_PT6041
,2015-12-14 14:44:56.662 ThaliTest[912:1150329] server: accepting invitation Apple-IpadAir2-1_PT6041
,2015-12-14 14:44:59.548 ThaliTest[912:1151661] server session: connected
2015-12-14 14:44:59.548 ThaliTest[912:1151661] server session: stateChange:1->2 Apple-IpadAir2-1_PT6041
,2015-12-14 14:44:59.578 ThaliTest[912:1150329] server relay: connected (to port: 57498)
,2015-12-14T13:44:59.587Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T13:45:00.024Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-14T13:45:00.043Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-14T13:45:00.059Z SendDataTCPServer.js: TCP/IP server has received 65558 bytes of data
,2015-12-14T13:45:00.074Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-14T13:45:00.088Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 14:45:00.133 ThaliTest[912:1151646] server session: not connected Apple-IpadAir2-1_PT6041
,2015-12-14 14:45:26.651 ThaliTest[912:1150329] multipeer session: restart
,2015-12-14 14:45:26.725 ThaliTest[912:1150329] client: found peer: Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:45:26.725 ThaliTest[912:1150329] client: found peer: Apple-IpadAir2-1_PT6041.byADbw==
2015-12-14 14:45:26.726 ThaliTest[912:1150329] client: ,found peer: Apple-Iphone5-1_PT3867.0mupng==
,2015-12-14 14:45:39.558 ThaliTest[912:1150329] multipeer session: reset timer
2015-12-14 14:45:39.558 ThaliTest[912:1150329] multipeer session: stop timer
2015-12-14 14:45:39.558 ThaliTest[912:1150329] multipeer session: start timer: 0x16c95400
,2015-12-14 14:45:39.560 ThaliTest[912:1150329] server session: connect
2015-12-14 14:45:39.561 ThaliTest[912:1150329] server session: stateChange:0->1 Apple-Iphone5-1_PT3867
,2015-12-14 14:45:39.570 ThaliTest[912:1150329] server: accepting invitation Apple-Iphone5-1_PT3867
,2015-12-14 14:45:42.506 ThaliTest[912:1151740] server session: connected
2015-12-14 14:45:42.507 ThaliTest[912:1151740] server session: stateChange:1->2 Apple-Iphone5-1_PT3867
,2015-12-14 14:45:42.535 ThaliTest[912:1150329] server relay: connected (to port: 57498)
,2015-12-14T13:45:42.545Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T13:45:43.030Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-14T13:45:43.044Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-14T13:45:43.061Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-14T13:45:43.087Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-14T13:45:43.103Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-14T13:45:43.120Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-14T13:45:43.135Z SendDataTCPServer.js: TCP/IP server has received 69938 bytes of data
,2015-12-14T13:45:43.150Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-14T13:45:43.166Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-14T13:45:43.182Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 14:45:43.290 ThaliTest[912:1151796] server session: not connected Apple-Iphone5-1_PT3867
,teardown
testSendData stopped
2015-12-14 14:45:43.927 ThaliTest[912:1150723] jxcore: stopBroadcasting
,2015-12-14 14:45:43.927 ThaliTest[912:1150723] THEMultipeerSession stopping peer
2015-12-14 14:45:43.928 ThaliTest[912:1150723] multipeer session: stop timer
2015-12-14 14:45:43.929 ThaliTest[912:1150723] server session: disconnect
2015-12-14 14:45:43.929 ThaliTest[912:1150723] server session: stateChange:2->0 Apple-Iphone5-1_PT3867
,2015-12-14 14:45:43.938 ThaliTest[912:1150723] server session: disconnect
,2015-12-14 14:45:43.939 ThaliTest[912:1150723] server session: stateChange:2->0 Apple-IpadAir2-1_PT6041
,2015-12-14 14:45:43.949 ThaliTest[912:1150723] server session: disconnect
2015-12-14 14:45:43.949 ThaliTest[912:1150723] server session: stateChange:2->0 Apple-Iphone6-1_PT4340
,2015-12-14 14:45:43.962 ThaliTest[912:1150723] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-14T13:45:44.014Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T13:45:44.038Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T13:45:44.041Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T13:45:44.043Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
