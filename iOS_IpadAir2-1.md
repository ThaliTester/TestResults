#### Test 552541413820a6d_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/552541413820a6d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/AC39B851-A87F-4D74-9734-9140D73F04EE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/AC39B851-A87F-4D74-9734-9140D73F04EE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/552541413820a6d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/552541413820a6d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/80B0F30E-0220-41E7-8CEC-A8EDE2462D53/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49297"
,(lldb)     command script import "/tmp/AC39B851-A87F-4D74-9734-9140D73F04EE/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-06 20:50:27.529 ThaliTest[1408:3064757] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C5900BEC-9D11-47B6-A464-3EF9397C86AC/Library/Cookies/Cookies.binarycookies
,2016-01-06 20:50:27.915 ThaliTest[1408:3064757] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-06 20:50:27.916 ThaliTest[1408:3064757] Multi-tasking -> Device: YES, App: YES
,2016-01-06 20:50:27.925 ThaliTest[1408:3064757] Unlimited access to network resources
,2016-01-06 20:50:27.933 ThaliTest[1408:3064757] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-06 20:50:37.449 ThaliTest[1408:3064757] Resetting plugins due to page load.
,2016-01-06 20:50:40.904 ThaliTest[1408:3064757] Finished load of: file:///var/mobile/Containers/Bundle/Application/80B0F30E-0220-41E7-8CEC-A8EDE2462D53/ThaliTest.app/www/index.html
,2016-01-06 20:50:41.068 ThaliTest[1408:3064757] JXcore Cordova plugin initializing
2016-01-06 20:50:41.069 ThaliTest[1408:3065057] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2016-01-06 20:50:42.046 ThaliTest[1408:3064757] THREAD WARNING: ['JXcore'] took '70.100098' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-06 20:57:04.241 ThaliTest[1408:3065057] jxcore: startBroadcasting
,2016-01-06 20:57:04.257 ThaliTest[1408:3065057] server: starting Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06 20:57:04.258 ThaliTest[1408:3065057] multipeer session: start timer: 0x19c7dfc0
,2016-01-06 20:57:04.260 ThaliTest[1408:3065057] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT6789
,2016-01-06 20:57:04.262 ThaliTest[1408:3065057] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2016-01-06 20:57:05.290 ThaliTest[1408:3064757] client: found peer: Apple-Iphone6-1_PT9564.cvfn7A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9564.cvfn7A==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT9564.cvfn7A==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2016-01-06 20:57:05.646 ThaliTest[1408:3064757] client: found peer: Apple-Iphone5s-1_PT1776.pROaFQ==
,2016-01-06 20:57:05.910 ThaliTest[1408:3064757] client: found peer: Apple-Iphone5-1_PT2360.KoeEnA==
,teardown
,testFindPeers stopped
,2016-01-06 20:57:13.010 ThaliTest[1408:3065057] jxcore: stopBroadcasting
,2016-01-06 20:57:13.010 ThaliTest[1408:3065057] THEMultipeerSession stopping peer
,2016-01-06 20:57:13.011 ThaliTest[1408:3065057] multipeer session: stop timer
,2016-01-06 20:57:13.012 ThaliTest[1408:3065057] jxcore: stopBroadcasting: success
StopBroadcasting went ok
--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 64111
,2016-01-06 20:57:13.040 ThaliTest[1408:3065057] jxcore: startBroadcasting
,2016-01-06 20:57:13.044 ThaliTest[1408:3065057] server: starting Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06 20:57:13.045 ThaliTest[1408:3065057] multipeer session: start timer: 0x17fb6f50
,2016-01-06 20:57:13.045 ThaliTest[1408:3065057] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT6789
,2016-01-06 20:57:13.047 ThaliTest[1408:3065057] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2016-01-06T19:57:13.053Z SendDataTCPServer.js: TCP/IP server is bound to port: 64111
,2016-01-06 20:57:13.072 ThaliTest[1408:3064757] client: found peer: Apple-IpadAir2-1_PT6789.T0JZzA==
2016-01-06 20:57:13.073 ThaliTest[1408:3064757] client: found peer: Apple-Iphone6-1_PT9564.cvfn7A==
2016-01-06 20:57:13.074 ThaliTest[1408:3064757] clien,t: found peer: Apple-Iphone5s-1_PT1776.pROaFQ==
2016-01-06 20:57:13.074 ThaliTest[1408:3064757] client: found peer: Apple-Iphone5-1_PT2360.KoeEnA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6789.T0JZzA==","peerName":"(null)","peerAva,ilable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-IpadAir2-1_PT6789.T0JZzA==
2016-01-06T19:57:13.077Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6789.T0JZzA==
2016-01-06T19:57:13.078Z SendDat,aConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6789.T0JZzA==
2016-01-06T19:57:13.078Z SendDataConnector.js: do connect now
2016-01-06 20:57:13.079 ThaliTest[1408:3065057] jxcore: connect Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06 20:57:13.079 ThaliTest[1408:3065057] client session: connect
2016-01-06 20:57:13.080 ThaliTest[1408:3065057] client session: stateChange:0->1 Apple-IpadAir2-1_PT6789.T0JZzA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9564.cvfn7A==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1776.pROaFQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2360.KoeEnA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-06 20:57:14.336 ThaliTest[1408:3064757] client: lost peer: Apple-Iphone5s-1_PT1776.pROaFQ==
2016-01-06 20:57:14.336 ThaliTest[1408:3064757] client session: onPeerLost: Apple-Iphone5s-1_PT1776.pROaFQ==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT1776.pROaFQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-06 20:57:14.359 ThaliTest[1408:3064757] client: lost peer: Apple-IpadAir2-1_PT6789.T0JZzA==
2016-01-06 20:57:14.360 ThaliTest[1408:3064757] client session: onPeerLost: Apple-IpadAir2-1_PT6789.T0JZzA==
2016-01-06 20:57:14.360 ThaliTest[1408:306475,7] client session: onLinkFailure: Apple-IpadAir2-1_PT6789.T0JZzA==
2016-01-06 20:57:14.360 ThaliTest[1408:3064757] client session: disconnect
2016-01-06 20:57:14.360 ThaliTest[1408:3064757] client session: stateChange:1->0 Apple-IpadAir2-1_PT6789.T0JZzA=,=
2016-01-06 20:57:14.361 ThaliTest[1408:3064757] client session: fireConnectCallback: Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06 20:57:14.361 ThaliTest[1408:3064757] jxcore: connect: fail: Peer disconnected
,2016-01-06T19:57:14.364Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2016-01-06T19:57:14.365Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2016-01-06T19:57:14.366Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6789.T0JZzA==","peerName":"(null)","peerAvailable":false}]
,2016-01-06 20:57:14.720 ThaliTest[1408:3064757] client: found peer: Apple-Iphone6-1_PT9564.iuO8Uw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9564.iuO8Uw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-06 20:57:14.729 ThaliTest[1408:3064757] client: found peer: Apple-Iphone5s-1_PT1776.mp8cwQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1776.mp8cwQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-06 20:57:17.823 ThaliTest[1408:3064757] client: lost peer: Apple-Iphone5-1_PT2360.KoeEnA==
2016-01-06 20:57:17.823 ThaliTest[1408:3064757] client session: onPeerLost: Apple-Iphone5-1_PT2360.KoeEnA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2360.KoeEnA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-06 20:57:18.875 ThaliTest[1408:3064757] client: lost peer: Apple-Iphone6-1_PT9564.cvfn7A==
2016-01-06 20:57:18.875 ThaliTest[1408:3064757] client session: onPeerLost: Apple-Iphone6-1_PT9564.cvfn7A==
,2016-01-06 20:57:18.876 ThaliTest[1408:3064757] client: found peer: Apple-Iphone5-1_PT2360.wZr66g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9564.cvfn7A==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2360.wZr66g==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-06T19:57:19.376Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06T19:57:19.377Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06 20:57:20.564 ThaliTest[1408:3064757] multipeer session: reset timer
2016-01-06 20:57:20.565 ThaliTest[1408:3064757] multipeer session: stop timer
2016-01-06 20:57:20.565 ThaliTest[1408:3064757] multipeer session: start timer: 0x17fb6f50
2016-01-06 20:57:20.565 ThaliTest[1408:3064757] server session: connect
2016-01-06 20:57:20.566 ThaliTest[1408:3064757] server session: stateChange:0->1 Apple-Iphone5-1_PT2360
,2016-01-06 20:57:20.573 ThaliTest[1408:3064757] server: accepting invitation Apple-Iphone5-1_PT2360
,2016-01-06 20:57:23.701 ThaliTest[1408:3066748] server session: connected
2016-01-06 20:57:23.701 ThaliTest[1408:3066748] server session: stateChange:1->2 Apple-Iphone5-1_PT2360
,2016-01-06 20:57:24.162 ThaliTest[1408:3064757] server relay: connected (to port: 64111)
,2016-01-06T19:57:24.165Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-06T19:57:24.220Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2016-01-06T19:57:24.234Z SendDataTCPServer.js: TCP/IP server has received 30518 bytes of data
,2016-01-06T19:57:24.250Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2016-01-06T19:57:24.266Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2016-01-06T19:57:24.283Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-06 20:57:24.386 ThaliTest[1408:3065057] jxcore: disconnect
,2016-01-06 20:57:24.387 ThaliTest[1408:3065057] jxcore: disconnect: fail
,2016-01-06T19:57:24.389Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06T19:57:24.389Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT6789.T0JZzA== with availability status: true
,2016-01-06T19:57:24.390Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06T19:57:24.390Z SendDataConnector.js: do connect now
,2016-01-06 20:57:24.392 ThaliTest[1408:3065057] jxcore: connect Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06 20:57:24.392 ThaliTest[1408:3065057] client: connect: unreachable Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06 20:57:24.393 ThaliTest[1408:3065057] jxcore: connect: fail: Peer unreachable
,2016-01-06T19:57:24.394Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-06T19:57:24.395Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-06T19:57:24.396Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-06 20:57:24.488 ThaliTest[1408:3066750] server session: not connected Apple-Iphone5-1_PT2360
,2016-01-06T19:57:29.401Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6789.T0JZzA==
2016-01-06T19:57:29.401Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06 20:57:34.407 ThaliTest[1408:3065057] jxcore: disconnect
,2016-01-06 20:57:34.408 ThaliTest[1408:3065057] jxcore: disconnect: fail
,2016-01-06T19:57:34.409Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06T19:57:34.409Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT6789.T0JZzA== with availability status: true
,2016-01-06T19:57:34.410Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06T19:57:34.411Z SendDataConnector.js: do connect now
,2016-01-06 20:57:34.412 ThaliTest[1408:3065057] jxcore: connect Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06 20:57:34.412 ThaliTest[1408:3065057] client: connect: unreachable Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06 20:57:34.413 ThaliTest[1408:3065057] jxcore: connect: fail: Peer unreachable
,2016-01-06T19:57:34.413Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-06T19:57:34.414Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-06T19:57:34.414Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-06T19:57:39.415Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06T19:57:39.416Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06 20:57:44.421 ThaliTest[1408:3065057] jxcore: disconnect
,2016-01-06 20:57:44.422 ThaliTest[1408:3065057] jxcore: disconnect: fail
,2016-01-06T19:57:44.423Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6789.T0JZzA==
2016-01-06T19:57:44.424Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT6789.T0JZzA== with availability status,: true
2016-01-06T19:57:44.424Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6789.T0JZzA==
2016-01-06T19:57:44.424Z SendDataConnector.js: do connect now
,2016-01-06 20:57:44.425 ThaliTest[1408:3065057] jxcore: connect Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06 20:57:44.426 ThaliTest[1408:3065057] client: connect: unreachable Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06 20:57:44.426 ThaliTest[1408:3065057] jxcore: connect: fail: Peer unreachable
,2016-01-06T19:57:44.427Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-06T19:57:44.427Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-06T19:57:44.427Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-06T19:57:49.432Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06T19:57:49.433Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06 20:57:50.567 ThaliTest[1408:3064757] multipeer session: restart
,2016-01-06 20:57:50.594 ThaliTest[1408:3064757] client: found peer: Apple-Iphone5s-1_PT1776.mp8cwQ==
2016-01-06 20:57:50.594 ThaliTest[1408:3064757] client: found peer: Apple-Iphone5-1_PT2360.wZr66g==
2016-01-06 20:57:50.595 ThaliTest[1408:3064757] client: found peer: Apple-Iphone6-1_PT9564.iuO8Uw==
,2016-01-06 20:57:54.435 ThaliTest[1408:3065057] jxcore: disconnect
,2016-01-06 20:57:54.436 ThaliTest[1408:3065057] jxcore: disconnect: fail
,2016-01-06T19:57:54.436Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06T19:57:54.437Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT6789.T0JZzA== with availability status: true
,2016-01-06T19:57:54.438Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06T19:57:54.439Z SendDataConnector.js: do connect now
,2016-01-06 20:57:54.440 ThaliTest[1408:3065057] jxcore: connect Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06 20:57:54.440 ThaliTest[1408:3065057] client: connect: unreachable Apple-IpadAir2-1_PT6789.T0JZzA==
,2016-01-06 20:57:54.441 ThaliTest[1408:3065057] jxcore: connect: fail: Peer unreachable
,2016-01-06T19:57:54.442Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-06T19:57:54.442Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2016-01-06T19:57:54.445Z SendDataConnector.js: CLIENT Stop now
,2016-01-06 20:57:54.446 ThaliTest[1408:3065057] jxcore: disconnect
2016-01-06 20:57:54.446 ThaliTest[1408:3065057] jxcore: disconnect: fail
,2016-01-06T19:57:54.447Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6789.T0JZzA==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone6-1_PT9564.iuO8Uw==
,2016-01-06T19:57:54.450Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT9564.iuO8Uw==
,2016-01-06T19:57:54.451Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9564.iuO8Uw==
,2016-01-06T19:57:54.451Z SendDataConnector.js: do connect now
,2016-01-06 20:57:54.452 ThaliTest[1408:3065057] jxcore: connect Apple-Iphone6-1_PT9564.iuO8Uw==
2016-01-06 20:57:54.453 ThaliTest[1408:3065057] client session: connect
,2016-01-06 20:57:54.454 ThaliTest[1408:3065057] client session: stateChange:0->1 Apple-Iphone6-1_PT9564.iuO8Uw==
,2016-01-06 20:57:58.287 ThaliTest[1408:3066874] client session: connected
,2016-01-06 20:57:58.288 ThaliTest[1408:3066874] client session: stateChange:1->2 Apple-Iphone6-1_PT9564.iuO8Uw==
,2016-01-06 20:57:58.306 ThaliTest[1408:3066873] client session: fireConnectCallback: Apple-Iphone6-1_PT9564.iuO8Uw==
2016-01-06 20:57:58.306 ThaliTest[1408:3066873] jxcore: connect: success
,2016-01-06T19:57:58.307Z SendDataConnector.js: CLIENT connected to 64119, error: null
,2016-01-06T19:57:58.308Z SendDataConnector.js: CLIENT starting client 
,2016-01-06 20:57:58.311 ThaliTest[1408:3064757] client: relay established
2016-01-06 20:57:58.312 ThaliTest[1408:3064757] client: new accepted socket: 0x19d4f910
,2016-01-06T19:57:58.329Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-06T19:57:58.609Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-06T19:57:58.622Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-06T19:57:58.622Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-06T19:57:58.623Z SendDataConnector.js: CLIENT Stop now
,2016-01-06T19:57:58.623Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-06 20:57:58.623 ThaliTest[1408:3065057] jxcore: disconnect
,2016-01-06 20:57:58.624 ThaliTest[1408:3065057] client session: disconnectFromPeer: Apple-Iphone6-1_PT9564.iuO8Uw==
,2016-01-06 20:57:58.624 ThaliTest[1408:3065057] client session: disconnect
,2016-01-06 20:57:58.624 ThaliTest[1408:3065057] client session: stateChange:2->0 Apple-Iphone6-1_PT9564.iuO8Uw==
,2016-01-06 20:57:58.627 ThaliTest[1408:3065057] jxcore: disconnect: success
2016-01-06T19:57:58.627Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9564.iuO8Uw==
---- round done--------
startWithNextDevice
device[3]: App,le-Iphone5s-1_PT1776.mp8cwQ==
2016-01-06T19:57:58.628Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT1776.mp8cwQ==
2016-01-06T19:57:58.628Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1776.mp8cwQ==
2016-01-06T19:57:58.628Z SendDataConnector.js: do connect now
,2016-01-06 20:57:58.628 ThaliTest[1408:3065057] jxcore: connect Apple-Iphone5s-1_PT1776.mp8cwQ==
2016-01-06 20:57:58.628 ThaliTest[1408:3065057] client session: connect
2016-01-06 20:57:58.628 ThaliTest[1408:3065057] client session: stateChange:0->1 Apple-Iphone5s-1_PT1776.mp8cwQ==
,2016-01-06 20:58:01.511 ThaliTest[1408:3064757] multipeer session: reset timer
2016-01-06 20:58:01.511 ThaliTest[1408:3064757] multipeer session: stop timer
,2016-01-06 20:58:01.511 ThaliTest[1408:3064757] multipeer session: start timer: 0x17fb6f50
2016-01-06 20:58:01.512 ThaliTest[1408:3064757] server session: connect
2016-01-06 20:58:01.512 ThaliTest[1408:3064757] server session: stateChange:0->1 Apple-Iphone5s-1_PT1776
,2016-01-06 20:58:01.519 ThaliTest[1408:3064757] server: accepting invitation Apple-Iphone5s-1_PT1776
,2016-01-06 20:58:01.582 ThaliTest[1408:3066911] client session: connected
2016-01-06 20:58:01.583 ThaliTest[1408:3066911] client session: stateChange:1->2 Apple-Iphone5s-1_PT1776.mp8cwQ==
,2016-01-06 20:58:01.595 ThaliTest[1408:3066873] client session: fireConnectCallback: Apple-Iphone5s-1_PT1776.mp8cwQ==
2016-01-06 20:58:01.596 ThaliTest[1408:3066873] jxcore: connect: success
,2016-01-06T19:58:01.597Z SendDataConnector.js: CLIENT connected to 64122, error: null
2016-01-06T19:58:01.598Z SendDataConnector.js: CLIENT starting client 
,2016-01-06 20:58:01.600 ThaliTest[1408:3064757] client: relay established
2016-01-06 20:58:01.600 ThaliTest[1408:3064757] client: new accepted socket: 0x19d62950
,2016-01-06T19:58:01.613Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-06T19:58:01.933Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-06T19:58:01.947Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-06T19:58:01.959Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-06T19:58:01.972Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-06T19:58:01.996Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-06T19:58:02.009Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-06T19:58:02.009Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-06T19:58:02.010Z SendDataConnector.js: CLIENT Stop now
2016-01-06T19:58:02.010Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-06 20:58:02.010 ThaliTest[1408:3065057] jxcore: disconnect
,2016-01-06 20:58:02.010 ThaliTest[1408:3065057] client session: disconnectFromPeer: Apple-Iphone5s-1_PT1776.mp8cwQ==
,2016-01-06 20:58:02.011 ThaliTest[1408:3065057] client session: disconnect
2016-01-06 20:58:02.011 ThaliTest[1408:3065057] client session: stateChange:2->0 Apple-Iphone5s-1_PT1776.mp8cwQ==
,2016-01-06 20:58:02.014 ThaliTest[1408:3065057] jxcore: disconnect: success
2016-01-06T19:58:02.014Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1776.mp8cwQ==
---- round done--------
startWithNextDevice
device[4]: Ap,ple-Iphone5-1_PT2360.wZr66g==
2016-01-06T19:58:02.015Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2360.wZr66g==
2016-01-06T19:58:02.015Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2360.wZr66g==
2016-01-06T19:58:02.015Z SendDataConnector.js: do connect now
2016-01-06 20:58:02.015 ThaliTest[1408:3065057] jxcore: connect Apple-Iphone5-1_PT2360.wZr66g==
2016-01-06 20:58:02.015 ThaliTest[1408:3065057] client session: connect
2016-01-06 20:58:02.015 ThaliTest[1408:3065057] client session: stateChange:0->1 Apple-Iphone5-1_PT2360.wZr66g==
,2016-01-06 20:58:04.559 ThaliTest[1408:3066874] server session: connected
2016-01-06 20:58:04.560 ThaliTest[1408:3066874] server session: stateChange:1->2 Apple-Iphone5s-1_PT1776
,2016-01-06 20:58:04.585 ThaliTest[1408:3064757] server relay: connected (to port: 64111)
,2016-01-06T19:58:04.590Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-06T19:58:05.052Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2016-01-06T19:58:05.067Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2016-01-06T19:58:05.083Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-06 20:58:05.118 ThaliTest[1408:3066874] server session: not connected Apple-Iphone5s-1_PT1776
,2016-01-06 20:58:05.671 ThaliTest[1408:3066877] client session: connected
2016-01-06 20:58:05.671 ThaliTest[1408:3066877] client session: stateChange:1->2 Apple-Iphone5-1_PT2360.wZr66g==
,2016-01-06 20:58:05.685 ThaliTest[1408:3066874] client session: fireConnectCallback: Apple-Iphone5-1_PT2360.wZr66g==
2016-01-06 20:58:05.686 ThaliTest[1408:3066874] jxcore: connect: success
,2016-01-06T19:58:05.687Z SendDataConnector.js: CLIENT connected to 64126, error: null
,2016-01-06T19:58:05.688Z SendDataConnector.js: CLIENT starting client 
,2016-01-06 20:58:05.691 ThaliTest[1408:3064757] client: relay established
,2016-01-06 20:58:05.691 ThaliTest[1408:3064757] client: new accepted socket: 0x19d641b0
,2016-01-06T19:58:05.705Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-06T19:58:06.126Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-06T19:58:06.139Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-06T19:58:06.152Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-06T19:58:06.165Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-06T19:58:06.166Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-06T19:58:06.166Z SendDataConnector.js: CLIENT Stop now
2016-01-06T19:58:06.166Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-06 20:58:06.167 ThaliTest[1408:3065057] jxcore: disconnect
,2016-01-06 20:58:06.167 ThaliTest[1408:3065057] client session: disconnectFromPeer: Apple-Iphone5-1_PT2360.wZr66g==
,2016-01-06 20:58:06.167 ThaliTest[1408:3065057] client session: disconnect
,2016-01-06 20:58:06.167 ThaliTest[1408:3065057] client session: stateChange:2->0 Apple-Iphone5-1_PT2360.wZr66g==
,2016-01-06 20:58:06.170 ThaliTest[1408:3065057] jxcore: disconnect: success
2016-01-06T19:58:06.170Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2360.wZr66g==
,---- round done--------
startWithNextDevice
,weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
,2016-01-06T19:58:06.181Z SendDataConnector.js: CLIENT Stop now
2016-01-06T19:58:06.181Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-06 20:58:31.513 ThaliTest[1408:3064757] multipeer session: restart
,2016-01-06 20:58:31.540 ThaliTest[1408:3064757] client: found peer: Apple-Iphone6-1_PT9564.iuO8Uw==
,2016-01-06 20:58:32.323 ThaliTest[1408:3064757] client: found peer: Apple-Iphone5s-1_PT1776.mp8cwQ==
2016-01-06 20:58:32.324 ThaliTest[1408:3064757] client: found peer: Apple-Iphone5-1_PT2360.wZr66g==
,2016-01-06 20:58:35.099 ThaliTest[1408:3064757] multipeer session: reset timer
,2016-01-06 20:58:35.099 ThaliTest[1408:3064757] multipeer session: stop timer
,2016-01-06 20:58:35.099 ThaliTest[1408:3064757] multipeer session: start timer: 0x17fb6f50
,2016-01-06 20:58:35.100 ThaliTest[1408:3064757] server session: connect
,2016-01-06 20:58:35.101 ThaliTest[1408:3064757] server session: stateChange:0->1 Apple-Iphone6-1_PT9564
,2016-01-06 20:58:35.107 ThaliTest[1408:3064757] server: accepting invitation Apple-Iphone6-1_PT9564
,2016-01-06 20:58:38.214 ThaliTest[1408:3066977] server session: connected
2016-01-06 20:58:38.214 ThaliTest[1408:3066977] server session: stateChange:1->2 Apple-Iphone6-1_PT9564
,2016-01-06 20:58:38.233 ThaliTest[1408:3064757] server relay: connected (to port: 64111)
,2016-01-06T19:58:38.240Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-06T19:58:38.516Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2016-01-06T19:58:38.530Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2016-01-06T19:58:38.596Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2016-01-06T19:58:38.610Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2016-01-06T19:58:38.664Z SendDataTCPServer.js: TCP/IP server has received 58846 bytes of data
,2016-01-06T19:58:38.678Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-06 20:58:38.715 ThaliTest[1408:3066977] server session: not connected Apple-Iphone6-1_PT9564
,2016-01-06 20:59:05.101 ThaliTest[1408:3064757] multipeer session: restart
,2016-01-06 20:59:05.428 ThaliTest[1408:3064757] client: found peer: Apple-Iphone5s-1_PT1776.mp8cwQ==
2016-01-06 20:59:05.428 ThaliTest[1408:3064757] client: found peer: Apple-Iphone6-1_PT9564.iuO8Uw==
,teardown
,testSendData stopped
,2016-01-06 20:59:05.605 ThaliTest[1408:3065057] jxcore: stopBroadcasting
2016-01-06 20:59:05.605 ThaliTest[1408:3065057] THEMultipeerSession stopping peer
,2016-01-06 20:59:05.605 ThaliTest[1408:3065057] multipeer session: stop timer
,2016-01-06 20:59:05.607 ThaliTest[1408:3065057] server session: disconnect
2016-01-06 20:59:05.607 ThaliTest[1408:3065057] server session: stateChange:2->0 Apple-Iphone5-1_PT2360
,2016-01-06 20:59:05.613 ThaliTest[1408:3065057] server session: disconnect
2016-01-06 20:59:05.614 ThaliTest[1408:3065057] server session: stateChange:2->0 Apple-Iphone5s-1_PT1776
,2016-01-06 20:59:05.674 ThaliTest[1408:3065057] server session: disconnect
2016-01-06 20:59:05.674 ThaliTest[1408:3065057] server session: stateChange:2->0 Apple-Iphone6-1_PT9564
,2016-01-06 20:59:05.678 ThaliTest[1408:3065057] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
