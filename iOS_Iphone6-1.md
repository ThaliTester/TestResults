#### Test 54312298af2c956_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/54312298af2c956/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/6F280EF1-4801-4656-9FFB-9405ED0A211D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/6F280EF1-4801-4656-9FFB-9405ED0A211D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/54312298af2c956/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/54312298af2c956/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B8877785-E65F-48A1-8FF6-DF904D02A200/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62395"
,(lldb)     command script import "/tmp/6F280EF1-4801-4656-9FFB-9405ED0A211D/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-23 03:06:33.809 ThaliTest[772:961697] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A5C69073-70E5-4FEE-B748-C6A4C0E54665/Library/Cookies/Cookies.binarycookies
,2015-12-23 03:06:34.177 ThaliTest[772:961697] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-23 03:06:34.178 ThaliTest[772:961697] Multi-tasking -> Device: YES, App: YES
,2015-12-23 03:06:34.187 ThaliTest[772:961697] Unlimited access to network resources
,2015-12-23 03:06:34.198 ThaliTest[772:961697] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-23 03:06:43.293 ThaliTest[772:961697] Resetting plugins due to page load.
,2015-12-23 03:06:46.884 ThaliTest[772:961697] Finished load of: file:///var/mobile/Containers/Bundle/Application/B8877785-E65F-48A1-8FF6-DF904D02A200/ThaliTest.app/www/index.html
,2015-12-23 03:06:47.119 ThaliTest[772:961697] JXcore Cordova plugin initializing
2015-12-23 03:06:47.122 ThaliTest[772:961920] JXcore instance initializing
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
,found test : ./testSendData2.js
,2015-12-23 03:06:48.205 ThaliTest[772:961697] THREAD WARNING: ['JXcore'] took '82.891113' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-23 03:11:59.947 ThaliTest[772:961920] jxcore: startBroadcasting
,2015-12-23 03:11:59.965 ThaliTest[772:961920] server: starting Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:11:59.966 ThaliTest[772:961920] multipeer session: start timer: 0x17b86ce0
2015-12-23 03:11:59.967 ThaliTest[772:961920] THEMultipeerSession init,ialized peer Apple-Iphone6-1_PT6053
2015-12-23 03:11:59.967 ThaliTest[772:961920] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-23 03:12:01.101 ThaliTest[772:961697] client: found peer: Apple-IpadAir2-1_PT8230.LvlR6w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8230.LvlR6w==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1_PT8230.LvlR6w==, peerAvailable: true
,weAreDoneNow
done, now sending data to server
,2015-12-23 03:12:01.204 ThaliTest[772:961697] client: found peer: Apple-Iphone5-1_PT4216.O2WEzg==
,2015-12-23 03:12:02.107 ThaliTest[772:961697] client: found peer: Apple-Iphone5s-1_PT4021.JWtqWw==
,teardown
,testFindPeers stopped
,2015-12-23 03:12:02.381 ThaliTest[772:961920] jxcore: stopBroadcasting
2015-12-23 03:12:02.383 ThaliTest[772:961920] THEMultipeerSession stopping peer
2015-12-23 03:12:02.383 ThaliTest[772:961920] multipeer session: stop timer
2015-12-23 03:12:02.384 Th,aliTest[772:961920] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,check server
,serverPort is 56527
,2015-12-23 03:12:02.452 ThaliTest[772:961920] jxcore: startBroadcasting
,2015-12-23 03:12:02.455 ThaliTest[772:961920] server: starting Apple-Iphone6-1_PT6053.vUErSg==
2015-12-23 03:12:02.456 ThaliTest[772:961920] multipeer session: start timer: 0x17b92f30
2015-12-23 03:12:02.457 ThaliTest[772:961920] THEMultipeerSession init,ialized peer Apple-Iphone6-1_PT6053
2015-12-23 03:12:02.457 ThaliTest[772:961920] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
,2015-12-23T02:12:02.463Z SendDataTCPServer.js: TCP/IP server is bound to port: 56527
,2015-12-23 03:12:02.942 ThaliTest[772:961697] client: found peer: Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:02.942 ThaliTest[772:961697] client: found peer: Apple-Iphone5s-1_PT4021.JWtqWw==
2015-12-23 03:12:02.942 ThaliTest[772:961697] client: fou,nd peer: Apple-Iphone5-1_PT4216.O2WEzg==
2015-12-23 03:12:02.943 ThaliTest[772:961697] client: found peer: Apple-IpadAir2-1_PT8230.LvlR6w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6053.eofveg==","peerName":"(null)","peerAvailable":t,rue}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone6-1_PT6053.eofveg==
2015-12-23T02:12:02.947Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:02.949Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:02.949Z SendDataConnector.js: do connect now
,2015-12-23 03:12:02.951 ThaliTest[772:961920] jxcore: connect Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:02.951 ThaliTest[772:961920] client session: connect
2015-12-23 03:12:02.952 ThaliTest[772:961920] client session: stateChange:0->1 Apple-Iphone6-1_PT6053.eofveg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4021.JWtqWw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4216.O2WEzg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8230.LvlR6w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-23 03:12:03.517 ThaliTest[772:961697] client: lost peer: Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:03.517 ThaliTest[772:961697] client session: onPeerLost: Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:03.518 ThaliTest[772:961697] clien,t session: onLinkFailure: Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:03.518 ThaliTest[772:961697] client session: disconnect
2015-12-23 03:12:03.518 ThaliTest[772:961697] client session: stateChange:1->0 Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 ,03:12:03.519 ThaliTest[772:961697] client session: fireConnectCallback: Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:03.519 ThaliTest[772:961697] jxcore: connect: fail: Peer disconnected
2015-12-23T02:12:03.521Z SendDataConnector.js: CLIENT connected, to 0, error: Peer disconnected
2015-12-23T02:12:03.522Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-23T02:12:03.522Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_P,T6053.eofveg==","peerName":"(null)","peerAvailable":false}]
,2015-12-23 03:12:03.708 ThaliTest[772:961697] client: lost peer: Apple-Iphone5s-1_PT4021.JWtqWw==
2015-12-23 03:12:03.709 ThaliTest[772:961697] client session: onPeerLost: Apple-Iphone5s-1_PT4021.JWtqWw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4021.JWtqWw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-23 03:12:03.794 ThaliTest[772:961697] client: lost peer: Apple-IpadAir2-1_PT8230.LvlR6w==
2015-12-23 03:12:03.794 ThaliTest[772:961697] client session: onPeerLost: Apple-IpadAir2-1_PT8230.LvlR6w==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-IpadAir2-1_PT8230.LvlR6w==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-23 03:12:04.189 ThaliTest[772:961697] client: lost peer: Apple-Iphone5-1_PT4216.O2WEzg==
2015-12-23 03:12:04.189 ThaliTest[772:961697] client session: onPeerLost: Apple-Iphone5-1_PT4216.O2WEzg==
2015-12-23 03:12:04.190 ThaliTest[772:961697] clien,t: found peer: Apple-IpadAir2-1_PT8230.FlW6Iw==
2015-12-23 03:12:04.190 ThaliTest[772:961697] client: found peer: Apple-Iphone5s-1_PT4021.SE3R7g==
2015-12-23 03:12:04.191 ThaliTest[772:961697] client: found peer: Apple-Iphone5-1_PT4216.OABFDg==
peerAvai,labilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4216.O2WEzg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8230.FlW6Iw==","peerName":"(null)","peer,Available":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4021.SE3R7g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifi,er":"Apple-Iphone5-1_PT4216.OABFDg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-23 03:12:04.289 ThaliTest[772:961697] multipeer session: reset timer
2015-12-23 03:12:04.289 ThaliTest[772:961697] multipeer session: stop timer
2015-12-23 03:12:04.289 ThaliTest[772:961697] multipeer session: start timer: 0x17b92f30
2015-12-23 ,03:12:04.290 ThaliTest[772:961697] server session: connect
2015-12-23 03:12:04.290 ThaliTest[772:961697] server session: stateChange:0->1 Apple-Iphone5-1_PT4216
,2015-12-23 03:12:04.299 ThaliTest[772:961697] server: accepting invitation Apple-Iphone5-1_PT4216
,2015-12-23 03:12:06.907 ThaliTest[772:962447] server session: connected
2015-12-23 03:12:06.907 ThaliTest[772:962447] server session: stateChange:1->2 Apple-Iphone5-1_PT4216
,2015-12-23 03:12:06.939 ThaliTest[772:961697] server relay: connected (to port: 56527)
,2015-12-23T02:12:06.948Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-23T02:12:07.439Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-23T02:12:07.453Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-23T02:12:07.468Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-23T02:12:07.497Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-23T02:12:07.512Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-23T02:12:07.527Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-23T02:12:07.544Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-23T02:12:07.558Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-23 03:12:07.612 ThaliTest[772:962459] server session: not connected Apple-Iphone5-1_PT4216
,2015-12-23T02:12:08.536Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:08.537Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:13.543 ThaliTest[772:961920] jxcore: disconnect
2015-12-23 03:12:13.543 ThaliTest[772:961920] jxcore: disconnect: fail
2015-12-23T02:12:13.544Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.eofveg==,
2015-12-23T02:12:13.544Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT6053.eofveg== with availability status: true
2015-12-23T02:12:13.545Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:13.545Z SendDataConnector.js: do connect now
,2015-12-23 03:12:13.547 ThaliTest[772:961920] jxcore: connect Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:13.548 ThaliTest[772:961920] client: connect: unreachable Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:13.548 ThaliTest[772:961920] jxcore:, connect: fail: Peer unreachable
2015-12-23T02:12:13.549Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-23T02:12:13.549Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-23T02:12:13.549Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-23T02:12:18.553Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:18.553Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:23.565 ThaliTest[772:961920] jxcore: disconnect
2015-12-23 03:12:23.566 ThaliTest[772:961920] jxcore: disconnect: fail
2015-12-23T02:12:23.566Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.eofveg==,
2015-12-23T02:12:23.567Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT6053.eofveg== with availability status: true
2015-12-23T02:12:23.567Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.eofveg==
2015-12-23T02:12:23.567Z SendDataConnector.js: do connect now
,2015-12-23 03:12:23.568 ThaliTest[772:961920] jxcore: connect Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:23.569 ThaliTest[772:961920] client: connect: unreachable Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:23.570 ThaliTest[772:961920] jxcore: connect: fail: Peer unreachable
2015-12-23T02:12:23.571Z SendDataConnector.js: CLIENT connect,ed to 0, error: Peer unreachable
2015-12-23T02:12:23.571Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-23T02:12:23.571Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-23T02:12:28.583Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:28.584Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:33.588 ThaliTest[772:961920] jxcore: disconnect
2015-12-23 03:12:33.589 ThaliTest[772:961920] jxcore: disconnect: fail
2015-12-23T02:12:33.589Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.eofveg==,
2015-12-23T02:12:33.589Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT6053.eofveg== with availability status: true
2015-12-23T02:12:33.590Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.eofveg==
2015-,12-23T02:12:33.590Z SendDataConnector.js: do connect now
,2015-12-23 03:12:33.591 ThaliTest[772:961920] jxcore: connect Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:33.591 ThaliTest[772:961920] client: connect: unreachable Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:33.593 ThaliTest[772:961920] jxcore: connect: fail: Peer unreachable
2015-12-23T02:12:33.593Z SendDataConnector.js: CLIENT connect,ed to 0, error: Peer unreachable
2015-12-23T02:12:33.594Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-23T02:12:33.594Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-23 03:12:34.291 ThaliTest[772:961697] multipeer session: restart
,2015-12-23 03:12:35.091 ThaliTest[772:961697] client: found peer: Apple-IpadAir2-1_PT8230.FlW6Iw==
,2015-12-23 03:12:35.096 ThaliTest[772:961697] client: found peer: Apple-Iphone5s-1_PT4021.SE3R7g==
2015-12-23 03:12:35.098 ThaliTest[772:961697] client: found peer: Apple-Iphone5-1_PT4216.OABFDg==
,2015-12-23T02:12:38.602Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:38.602Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:43.606 ThaliTest[772:961920] jxcore: disconnect
2015-12-23 03:12:43.607 ThaliTest[772:961920] jxcore: disconnect: fail
2015-12-23T02:12:43.607Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.eofveg==,
2015-12-23T02:12:43.608Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT6053.eofveg== with availability status: true
2015-12-23T02:12:43.608Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:43.608Z SendDataConnector.js: do connect now
,2015-12-23 03:12:43.609 ThaliTest[772:961920] jxcore: connect Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:43.611 ThaliTest[772:961920] client: connect: unreachable Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:43.611 ThaliTest[772:961920] jxcore:, connect: fail: Peer unreachable
2015-12-23T02:12:43.611Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-23T02:12:43.612Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2015-12-23T02:12:43.614Z SendDataConnector.js: CLIENT Stop now
,2015-12-23 03:12:43.615 ThaliTest[772:961920] jxcore: disconnect
2015-12-23 03:12:43.616 ThaliTest[772:961920] jxcore: disconnect: fail
2015-12-23T02:12:43.616Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.eofveg==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-IpadAir2-1_PT8230.FlW6Iw==
,2015-12-23T02:12:43.621Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT8230.FlW6Iw==
,2015-12-23T02:12:43.622Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8230.FlW6Iw==
,2015-12-23T02:12:43.622Z SendDataConnector.js: do connect now
,2015-12-23 03:12:43.623 ThaliTest[772:961920] jxcore: connect Apple-IpadAir2-1_PT8230.FlW6Iw==
2015-12-23 03:12:43.624 ThaliTest[772:961920] client session: connect
2015-12-23 03:12:43.624 ThaliTest[772:961920] client session: stateChange:0->1 Apple-IpadAir2-1_PT8230.FlW6Iw==
,2015-12-23 03:12:45.700 ThaliTest[772:961697] multipeer session: reset timer
2015-12-23 03:12:45.701 ThaliTest[772:961697] multipeer session: stop timer
2015-12-23 03:12:45.701 ThaliTest[772:961697] multipeer session: start timer: 0x17b92f30
,2015-12-23 03:12:45.702 ThaliTest[772:961697] server session: connect
2015-12-23 03:12:45.702 ThaliTest[772:961697] server session: stateChange:0->1 Apple-Iphone5s-1_PT4021
,2015-12-23 03:12:45.712 ThaliTest[772:961697] server: accepting invitation Apple-Iphone5s-1_PT4021
,2015-12-23 03:12:47.153 ThaliTest[772:962529] client session: connected
2015-12-23 03:12:47.154 ThaliTest[772:962529] client session: stateChange:1->2 Apple-IpadAir2-1_PT8230.FlW6Iw==
,2015-12-23 03:12:47.169 ThaliTest[772:962540] client session: fireConnectCallback: Apple-IpadAir2-1_PT8230.FlW6Iw==
2015-12-23 03:12:47.169 ThaliTest[772:962540] jxcore: connect: success
2015-12-23T02:12:47.170Z SendDataConnector.js: CLIENT connected to ,56535, error: null
2015-12-23T02:12:47.171Z SendDataConnector.js: CLIENT starting client 
2015-12-23 03:12:47.174 ThaliTest[772:961697] client: relay established
2015-12-23 03:12:47.174 ThaliTest[772:961697] client: new accepted socket: 0x17bac570
,2015-12-23T02:12:47.191Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-23T02:12:47.727Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-23T02:12:47.727Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-23T02:12:47.728Z SendDataConnector.js: CLIENT Stop now
,2015-12-23T02:12:47.728Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-23 03:12:47.729 ThaliTest[772:961920] jxcore: disconnect
2015-12-23 03:12:47.729 ThaliTest[772:961920] client session: disconnectFromPeer: Apple-IpadAir2-1_PT8230.FlW6Iw==
2015-12-23 03:12:47.729 ThaliTest[772:961920] client session: disconnect
,2015-12-23 03:12:47.729 ThaliTest[772:961920] client session: stateChange:2->0 Apple-IpadAir2-1_PT8230.FlW6Iw==
,2015-12-23 03:12:47.735 ThaliTest[772:961920] jxcore: disconnect: success
2015-12-23T02:12:47.735Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8230.FlW6Iw==
---- round done--------
startWithNextDevice
device[3]: Appl,e-Iphone5s-1_PT4021.SE3R7g==
2015-12-23T02:12:47.736Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4021.SE3R7g==
2015-12-23T02:12:47.736Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4021.SE3R7g==
2015-12-23T02:12:47.736Z SendDataConnector.js: do connect now
2015-12-23 03:12:47.736 ThaliTest[772:961920] jxcore: connect Apple-Iphone5s-1_PT4021.SE3R7g==
2015-12-23 03:12:47.736 ThaliTest[772:961920] client session: connect
2015-12-23 03:12:47.736 ThaliTest[772:96,1920] client session: stateChange:0->1 Apple-Iphone5s-1_PT4021.SE3R7g==
,2015-12-23 03:12:48.977 ThaliTest[772:962529] server session: connected
2015-12-23 03:12:48.977 ThaliTest[772:962529] server session: stateChange:1->2 Apple-Iphone5s-1_PT4021
,2015-12-23 03:12:48.983 ThaliTest[772:961697] server relay: connected (to port: 56527)
,2015-12-23T02:12:48.994Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-23T02:12:49.834Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-23T02:12:49.848Z SendDataTCPServer.js: TCP/IP server has received 54324 bytes of data
,2015-12-23T02:12:49.867Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-23T02:12:49.894Z SendDataTCPServer.js: TCP/IP server has received 78698 bytes of data
,2015-12-23T02:12:49.908Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-23 03:12:50.026 ThaliTest[772:962540] server session: not connected Apple-Iphone5s-1_PT4021
,2015-12-23 03:12:50.884 ThaliTest[772:962540] client session: connected
2015-12-23 03:12:50.884 ThaliTest[772:962540] client session: stateChange:1->2 Apple-Iphone5s-1_PT4021.SE3R7g==
,2015-12-23 03:12:50.931 ThaliTest[772:962525] client session: fireConnectCallback: Apple-Iphone5s-1_PT4021.SE3R7g==
2015-12-23 03:12:50.932 ThaliTest[772:962525] jxcore: connect: success
2015-12-23T02:12:50.934Z SendDataConnector.js: CLIENT connected to ,56539, error: null
2015-12-23T02:12:50.934Z SendDataConnector.js: CLIENT starting client 
,2015-12-23 03:12:50.939 ThaliTest[772:961697] client: relay established
2015-12-23 03:12:50.940 ThaliTest[772:961697] client: new accepted socket: 0x17c4dd20
,2015-12-23T02:12:50.951Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-23T02:12:51.401Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-23T02:12:51.414Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-23T02:12:51.460Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-23T02:12:51.460Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-23T02:12:51.461Z SendDataConnector.js: CLIENT Stop now
,2015-12-23T02:12:51.461Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-23 03:12:51.462 ThaliTest[772:961920] jxcore: disconnect
2015-12-23 03:12:51.462 ThaliTest[772:961920] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4021.SE3R7g==
2015-12-23 03:12:51.462 ThaliTest[772:961920] client session: disconnect
2015-12-23 03:12:51.462 ThaliTest[772:961920] client session: stateChange:2->0 Apple-Iphone5s-1_PT4021.SE3R7g==
,2015-12-23 03:12:51.468 ThaliTest[772:961920] jxcore: disconnect: success
2015-12-23T02:12:51.468Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4021.SE3R7g==
---- round done--------
startWithNextDevice
device[4]: Apple-Iphone5-1_PT4216.OABFDg==
,2015-12-23T02:12:51.469Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT4216.OABFDg==
2015-12-23T02:12:51.469Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT4216.OABFDg==
2015-12-23T02:12:51.469Z SendDataConnector.js: do connect now
2015-12-23 03:12:51.470 ThaliTest[772:961920] jxcore: connect Apple-Iphone5-1_PT4216.OABFDg==
2015-12-23 03:12:51.470 ThaliTest[772:961920] client session: connect
2015-12-23 03:12:51.470 ThaliTest[772:961920] client session: stateChange:0->1 Apple-Iphone5-1_PT4216.OABFDg==
,2015-12-23 03:12:52.688 ThaliTest[772:961697] multipeer session: reset timer
2015-12-23 03:12:52.688 ThaliTest[772:961697] multipeer session: stop timer
,2015-12-23 03:12:52.689 ThaliTest[772:961697] multipeer session: start timer: 0x17b92f30
,2015-12-23 03:12:52.689 ThaliTest[772:961697] server session: connect
,2015-12-23 03:12:52.690 ThaliTest[772:961697] server session: stateChange:0->1 Apple-IpadAir2-1_PT8230
,2015-12-23 03:12:52.701 ThaliTest[772:961697] server: accepting invitation Apple-IpadAir2-1_PT8230
,2015-12-23 03:12:55.004 ThaliTest[772:962539] client session: connected
2015-12-23 03:12:55.004 ThaliTest[772:962539] client session: stateChange:1->2 Apple-Iphone5-1_PT4216.OABFDg==
,2015-12-23 03:12:55.032 ThaliTest[772:962540] client session: fireConnectCallback: Apple-Iphone5-1_PT4216.OABFDg==
2015-12-23 03:12:55.032 ThaliTest[772:962540] jxcore: connect: success
2015-12-23T02:12:55.033Z SendDataConnector.js: CLIENT connected to 56542, error: null
2015-12-23T02:12:55.034Z SendDataConnector.js: CLIENT starting client 
,2015-12-23 03:12:55.037 ThaliTest[772:961697] client: relay established
2015-12-23 03:12:55.038 ThaliTest[772:961697] client: new accepted socket: 0x17ba40c0
,2015-12-23T02:12:55.051Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-23T02:12:55.590Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-23T02:12:55.590Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-23T02:12:55.590Z SendDataConnector.js: CLIENT Stop now
,2015-12-23T02:12:55.591Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-23 03:12:55.591 ThaliTest[772:961920] jxcore: disconnect
2015-12-23 03:12:55.592 ThaliTest[772:961920] client session: disconnectFromPeer: Apple-Iphone5-1_PT4216.OABFDg==
,2015-12-23 03:12:55.592 ThaliTest[772:961920] client session: disconnect
,2015-12-23 03:12:55.593 ThaliTest[772:961920] client session: stateChange:2->0 Apple-Iphone5-1_PT4216.OABFDg==
,2015-12-23 03:12:55.654 ThaliTest[772:961920] jxcore: disconnect: success
,2015-12-23T02:12:55.655Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT4216.OABFDg==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2015-12-23T02:12:55.658Z SendDataConnector.js: CLIENT Stop now
2015-12-23T02:12:55.659Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-23 03:12:55.720 ThaliTest[772:962540] server session: connected
2015-12-23 03:12:55.720 ThaliTest[772:962540] server session: stateChange:1->2 Apple-IpadAir2-1_PT8230
,2015-12-23 03:12:55.783 ThaliTest[772:961697] server relay: connected (to port: 56527)
,2015-12-23T02:12:55.788Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-23T02:12:56.051Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-23T02:12:56.066Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-23T02:12:56.082Z SendDataTCPServer.js: TCP/IP server has received 78698 bytes of data
,2015-12-23T02:12:56.105Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-23 03:12:56.147 ThaliTest[772:962529] server session: not connected Apple-IpadAir2-1_PT8230
,teardown
,testSendData stopped
,2015-12-23 03:12:58.519 ThaliTest[772:961920] jxcore: stopBroadcasting
,2015-12-23 03:12:58.520 ThaliTest[772:961920] THEMultipeerSession stopping peer
2015-12-23 03:12:58.520 ThaliTest[772:961920] multipeer session: stop timer
2015-12-23 03:12:58.521 ThaliTest[772:961920] server session: disconnect
2015-12-23 03:12:58.521 ThaliTest[772:961920] server session: stateChange:2->0 Apple-Iphone5-1_PT4216
,2015-12-23 03:12:58.529 ThaliTest[772:961920] server session: disconnect
2015-12-23 03:12:58.529 ThaliTest[772:961920] server session: stateChange:2->0 Apple-Iphone5s-1_PT4021
,2015-12-23 03:12:58.536 ThaliTest[772:961920] server session: disconnect
2015-12-23 03:12:58.541 ThaliTest[772:961920] server session: stateChange:2->0 Apple-IpadAir2-1_PT8230
,2015-12-23 03:12:58.884 ThaliTest[772:961920] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-23T02:12:58.901Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-23T02:12:58.903Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-23T02:12:58.905Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-23T02:12:58.906Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
