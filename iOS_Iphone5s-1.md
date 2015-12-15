#### Test 50650278ee43ca0_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278ee43ca0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/0C4D0BC0-2420-443E-9E11-3F6BB4D86DC5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0C4D0BC0-2420-443E-9E11-3F6BB4D86DC5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278ee43ca0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278ee43ca0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/ECF2EF8E-A3CC-4011-8B83-F037BBBAC4F9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56313"
,(lldb)     command script import "/tmp/0C4D0BC0-2420-443E-9E11-3F6BB4D86DC5/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-15 05:01:20.022 ThaliTest[1060:1255828] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/91C44DD3-58C7-4512-8BA2-63866F093EB0/Library/Cookies/Cookies.binarycookies
,2015-12-15 05:01:20.439 ThaliTest[1060:1255828] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-15 05:01:20.440 ThaliTest[1060:1255828] Multi-tasking -> Device: YES, App: YES
,2015-12-15 05:01:20.450 ThaliTest[1060:1255828] Unlimited access to network resources
,2015-12-15 05:01:20.463 ThaliTest[1060:1255828] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-15 05:01:29.635 ThaliTest[1060:1255828] Resetting plugins due to page load.
,2015-12-15 05:01:33.396 ThaliTest[1060:1255828] Finished load of: file:///var/mobile/Containers/Bundle/Application/ECF2EF8E-A3CC-4011-8B83-F037BBBAC4F9/ThaliTest.app/www/index.html
,2015-12-15 05:01:33.611 ThaliTest[1060:1255828] JXcore Cordova plugin initializing
2015-12-15 05:01:33.613 ThaliTest[1060:1256126] JXcore instance initializing
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
,2015-12-15 05:01:34.934 ThaliTest[1060:1255828] THREAD WARNING: ['JXcore'] took '92.864014' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-15 05:06:31.827 ThaliTest[1060:1256126] jxcore: startBroadcasting
,2015-12-15 05:06:31.847 ThaliTest[1060:1256126] server: starting Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15 05:06:31.848 ThaliTest[1060:1256126] multipeer session: start timer: 0x17a46d90
2015-12-15 05:06:31.849 ThaliTest[1060:1256126] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT6308
2015-12-15 05:06:31.849 ThaliTest[1060:1256126] jxcore,: startBroadcasting: success
StartBroadcasting started ok
,2015-12-15 05:06:34.150 ThaliTest[1060:1255828] client: found peer: Apple-Iphone5-1_PT2557.cLGdMA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2557.cLGdMA==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5-1_PT2557.cLGdMA==, peerAvailable: true
,weAreDoneNow
done, now sending data to server
2015-12-15 05:06:34.161 ThaliTest[1060:1255828] client: found peer: Apple-IpadAir2-1_PT1010.7Cf2mQ==
,teardown
,testFindPeers stopped
,2015-12-15 05:06:34.370 ThaliTest[1060:1256126] jxcore: stopBroadcasting
2015-12-15 05:06:34.370 ThaliTest[1060:1256126] THEMultipeerSession stopping peer
2015-12-15 05:06:34.370 ThaliTest[1060:1256126] multipeer session: stop timer
2015-12-15 05:06:34.,371 ThaliTest[1060:1256126] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 59545
,2015-12-15 05:06:34.458 ThaliTest[1060:1256126] jxcore: startBroadcasting
,2015-12-15 05:06:34.461 ThaliTest[1060:1256126] server: starting Apple-Iphone5s-1_PT6308.z27btQ==
2015-12-15 05:06:34.462 ThaliTest[1060:1256126] multipeer session: start timer: 0x17b21630
2015-12-15 05:06:34.463 ThaliTest[1060:1256126] THEMultipeerSessi,on initialized peer Apple-Iphone5s-1_PT6308
2015-12-15 05:06:34.463 ThaliTest[1060:1256126] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2015-12-15T04:06:34.466Z SendDataTCPServer.js: TCP/IP server is bound to port: 59545
,2015-12-15 05:06:34.949 ThaliTest[1060:1255828] client: found peer: Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:34.952 ThaliTest[1060:1255828] client: found peer: Apple-IpadAir2-1_PT1010.7Cf2mQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ip,hone5s-1_PT6308.pQEQSw==","peerName":"(null)","peerAvailable":true}]
2015-12-15 05:06:34.953 ThaliTest[1060:1255828] client: found peer: Apple-Iphone5-1_PT2557.cLGdMA==
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone5s-,1_PT6308.pQEQSw==
2015-12-15T04:06:34.958Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15T04:06:34.959Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15T04:06:34.959Z ,SendDataConnector.js: do connect now
,2015-12-15 05:06:34.960 ThaliTest[1060:1256126] jxcore: connect Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:34.961 ThaliTest[1060:1256126] client session: connect
2015-12-15 05:06:34.962 ThaliTest[1060:1256126] client session: stateChange:0->1 Apple-Iphone5s-1_PT6308.pQEQSw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1010.7Cf2mQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2557.cLGdMA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-15 05:06:35.611 ThaliTest[1060:1255828] client: lost peer: Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:35.611 ThaliTest[1060:1255828] client session: onPeerLost: Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:35.611 ThaliTest[1060:125582,8] client session: onLinkFailure: Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:35.612 ThaliTest[1060:1255828] client session: disconnect
2015-12-15 05:06:35.612 ThaliTest[1060:1255828] client session: stateChange:1->0 Apple-Iphone5s-1_PT6308.pQEQSw=,=
2015-12-15 05:06:35.613 ThaliTest[1060:1255828] client session: fireConnectCallback: Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:35.613 ThaliTest[1060:1255828] jxcore: connect: fail: Peer disconnected
2015-12-15T04:06:35.615Z SendDataConnector.j,s: CLIENT connected to 0, error: Peer disconnected
2015-12-15T04:06:35.615Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-15T04:06:35.616Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier",:"Apple-Iphone5s-1_PT6308.pQEQSw==","peerName":"(null)","peerAvailable":false}]
,2015-12-15 05:06:36.158 ThaliTest[1060:1255828] client: lost peer: Apple-Iphone5-1_PT2557.cLGdMA==
2015-12-15 05:06:36.158 ThaliTest[1060:1255828] client session: onPeerLost: Apple-Iphone5-1_PT2557.cLGdMA==
2015-12-15 05:06:36.159 ThaliTest[1060:1255828], client: found peer: Apple-Iphone6-1_PT9306.EdsImg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2557.cLGdMA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier,":"Apple-Iphone6-1_PT9306.EdsImg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 05:06:36.750 ThaliTest[1060:1255828] client: found peer: Apple-IpadAir2-1_PT1010.g7hIzw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1010.g7hIzw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 05:06:36.818 ThaliTest[1060:1255828] client: lost peer: Apple-IpadAir2-1_PT1010.7Cf2mQ==
2015-12-15 05:06:36.818 ThaliTest[1060:1255828] client session: onPeerLost: Apple-IpadAir2-1_PT1010.7Cf2mQ==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-IpadAir2-1_PT1010.7Cf2mQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-15 05:06:37.231 ThaliTest[1060:1255828] client: found peer: Apple-Iphone5-1_PT2557.fyiFnQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2557.fyiFnQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-15T04:06:40.617Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15T04:06:40.618Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15 05:06:45.621 ThaliTest[1060:1256126] jxcore: disconnect
2015-12-15 05:06:45.622 ThaliTest[1060:1256126] jxcore: disconnect: fail
2015-12-15T04:06:45.622Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6308.pQEQ,Sw==
2015-12-15T04:06:45.623Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT6308.pQEQSw== with availability status: true
,2015-12-15T04:06:45.624Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15T04:06:45.624Z SendDataConnector.js: do connect now
,2015-12-15 05:06:45.625 ThaliTest[1060:1256126] jxcore: connect Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:45.626 ThaliTest[1060:1256126] client: connect: unreachable Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:45.626 ThaliTest[1060:1256126], jxcore: connect: fail: Peer unreachable
2015-12-15T04:06:45.627Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:06:45.627Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T04:06:45.628Z SendD,ataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:06:50.640Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15T04:06:50.640Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15 05:06:55.652 ThaliTest[1060:1256126] jxcore: disconnect
2015-12-15 05:06:55.653 ThaliTest[1060:1256126] jxcore: disconnect: fail
2015-12-15T04:06:55.654Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6308.pQEQ,Sw==
2015-12-15T04:06:55.654Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT6308.pQEQSw== with availability status: true
2015-12-15T04:06:55.655Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15T04:06:55.655Z SendDataConnector.js: do connect now
,2015-12-15 05:06:55.656 ThaliTest[1060:1256126] jxcore: connect Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:55.657 ThaliTest[1060:1256126] client: connect: unreachable Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:55.658 ThaliTest[1060:1256126], jxcore: connect: fail: Peer unreachable
2015-12-15T04:06:55.658Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:06:55.659Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T04:06:55.659Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:07:00.667Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15T04:07:00.667Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15 05:07:04.464 ThaliTest[1060:1255828] multipeer session: restart
,2015-12-15 05:07:04.527 ThaliTest[1060:1255828] client: found peer: Apple-Iphone6-1_PT9306.EdsImg==
,2015-12-15 05:07:04.531 ThaliTest[1060:1255828] client: found peer: Apple-IpadAir2-1_PT1010.g7hIzw==
2015-12-15 05:07:04.534 ThaliTest[1060:1255828] client: found peer: Apple-Iphone5-1_PT2557.fyiFnQ==
,2015-12-15 05:07:05.673 ThaliTest[1060:1256126] jxcore: disconnect
2015-12-15 05:07:05.674 ThaliTest[1060:1256126] jxcore: disconnect: fail
2015-12-15T04:07:05.674Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6308.pQEQ,Sw==
2015-12-15T04:07:05.675Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT6308.pQEQSw== with availability status: true
2015-12-15T04:07:05.675Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15T04:07:05.675Z SendDataConnector.js: do connect now
2015-12-15 05:07:05.676 ThaliTest[1060:1256126] jxcore: connect Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15 05:07:05.677 ThaliTest[1060:1256126] client: connect: unreachable Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15 05:07:05.678 ThaliTest[1060:1256126] jxcore: connect: fail: Peer unreachable
,2015-12-15T04:07:05.679Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:07:05.680Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T04:07:05.680Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:07:10.689Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15T04:07:10.690Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15 05:07:15.702 ThaliTest[1060:1256126] jxcore: disconnect
2015-12-15 05:07:15.702 ThaliTest[1060:1256126] jxcore: disconnect: fail
2015-12-15T04:07:15.703Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6308.pQEQ,Sw==
2015-12-15T04:07:15.704Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT6308.pQEQSw== with availability status: true
2015-12-15T04:07:15.704Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6308.pQEQSw==,
2015-12-15T04:07:15.704Z SendDataConnector.js: do connect now
,2015-12-15 05:07:15.705 ThaliTest[1060:1256126] jxcore: connect Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:07:15.705 ThaliTest[1060:1256126] client: connect: unreachable Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:07:15.706 ThaliTest[1060:1256126], jxcore: connect: fail: Peer unreachable
,2015-12-15T04:07:15.707Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-15T04:07:15.708Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
2015-12-15T04:07:15.711Z SendDataConnector.js: CLIENT Stop now
,2015-12-15 05:07:15.712 ThaliTest[1060:1256126] jxcore: disconnect
,2015-12-15 05:07:15.713 ThaliTest[1060:1256126] jxcore: disconnect: fail
2015-12-15T04:07:15.714Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6308.pQEQSw==
---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone6-1_PT9306.EdsImg==
,2015-12-15T04:07:15.718Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT9306.EdsImg==
,2015-12-15T04:07:15.718Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9306.EdsImg==
,2015-12-15T04:07:15.719Z SendDataConnector.js: do connect now
,2015-12-15 05:07:15.720 ThaliTest[1060:1256126] jxcore: connect Apple-Iphone6-1_PT9306.EdsImg==
2015-12-15 05:07:15.721 ThaliTest[1060:1256126] client session: connect
2015-12-15 05:07:15.721 ThaliTest[1060:1256126] client session: stateChange:0->1 Apple,-Iphone6-1_PT9306.EdsImg==
,2015-12-15 05:07:17.072 ThaliTest[1060:1255828] multipeer session: reset timer
2015-12-15 05:07:17.072 ThaliTest[1060:1255828] multipeer session: stop timer
2015-12-15 05:07:17.072 ThaliTest[1060:1255828] multipeer session: start timer: 0x17b21630
,2015-12-15 05:07:17.074 ThaliTest[1060:1255828] server session: connect
2015-12-15 05:07:17.074 ThaliTest[1060:1255828] server session: stateChange:0->1 Apple-Iphone6-1_PT9306
,2015-12-15 05:07:17.084 ThaliTest[1060:1255828] server: accepting invitation Apple-Iphone6-1_PT9306
,2015-12-15 05:07:19.564 ThaliTest[1060:1256752] client session: connected
2015-12-15 05:07:19.564 ThaliTest[1060:1256752] client session: stateChange:1->2 Apple-Iphone6-1_PT9306.EdsImg==
,2015-12-15 05:07:19.602 ThaliTest[1060:1256745] client session: fireConnectCallback: Apple-Iphone6-1_PT9306.EdsImg==
2015-12-15 05:07:19.602 ThaliTest[1060:1256745] jxcore: connect: success
2015-12-15T04:07:19.603Z SendDataConnector.js: CLIENT connected to 59552, error: null
2015-12-15T04:07:19.604Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 05:07:19.609 ThaliTest[1060:1255828] client: relay established
2015-12-15 05:07:19.612 ThaliTest[1060:1255828] client: new accepted socket: 0x166cb830
,2015-12-15T04:07:19.625Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15 05:07:19.760 ThaliTest[1060:1256745] server session: connected
2015-12-15 05:07:19.761 ThaliTest[1060:1256745] server session: stateChange:1->2 Apple-Iphone6-1_PT9306
,2015-12-15 05:07:19.789 ThaliTest[1060:1255828] server relay: connected (to port: 59545)
,2015-12-15T04:07:19.952Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T04:07:20.117Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-15T04:07:20.142Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-15T04:07:20.167Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-15T04:07:20.173Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T04:07:20.173Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-15T04:07:20.174Z SendDataConnector.js: CLIENT Stop now
2015-12-15T04:07:20.174Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:07:20.175 ThaliTest[1060:1256126] jxcore: disconnect
,2015-12-15 05:07:20.175 ThaliTest[1060:1256126] client session: disconnectFromPeer: Apple-Iphone6-1_PT9306.EdsImg==
,2015-12-15 05:07:20.176 ThaliTest[1060:1256126] client session: disconnect
,2015-12-15 05:07:20.177 ThaliTest[1060:1256126] client session: stateChange:2->0 Apple-Iphone6-1_PT9306.EdsImg==
,2015-12-15 05:07:20.243 ThaliTest[1060:1256126] jxcore: disconnect: success
,2015-12-15T04:07:20.244Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9306.EdsImg==
---- round done--------
,startWithNextDevice
,device[3]: Apple-IpadAir2-1_PT1010.g7hIzw==
,2015-12-15T04:07:20.245Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1010.g7hIzw==
,2015-12-15T04:07:20.245Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1010.g7hIzw==
,2015-12-15T04:07:20.246Z SendDataConnector.js: do connect now
,2015-12-15 05:07:20.246 ThaliTest[1060:1256126] jxcore: connect Apple-IpadAir2-1_PT1010.g7hIzw==
,2015-12-15 05:07:20.247 ThaliTest[1060:1256126] client session: connect
,2015-12-15 05:07:20.247 ThaliTest[1060:1256126] client session: stateChange:0->1 Apple-IpadAir2-1_PT1010.g7hIzw==
,2015-12-15T04:07:20.268Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 05:07:20.835 ThaliTest[1060:1255828] multipeer session: reset timer
2015-12-15 05:07:20.835 ThaliTest[1060:1255828] multipeer session: stop timer
2015-12-15 05:07:20.836 ThaliTest[1060:1255828] multipeer session: start timer: 0x17b21630
2015-,12-15 05:07:20.836 ThaliTest[1060:1255828] server session: connect
2015-12-15 05:07:20.836 ThaliTest[1060:1255828] server session: stateChange:0->1 Apple-Iphone5-1_PT2557
,2015-12-15 05:07:20.847 ThaliTest[1060:1255828] server: accepting invitation Apple-Iphone5-1_PT2557
,2015-12-15 05:07:20.886 ThaliTest[1060:1255828] multipeer session: reset timer
2015-12-15 05:07:20.886 ThaliTest[1060:1255828] multipeer session: stop timer
2015-12-15 05:07:20.887 ThaliTest[1060:1255828] multipeer session: start timer: 0x17b21630
2015-12-15 05:07:20.887 ThaliTest[1060:1255828] server session: connect
2015-12-15 05:07:20.888 ThaliTest[1060:1255828] server session: stateChange:0->1 Apple-IpadAir2-1_PT1010
2015-12-15 05:07:20.900 ThaliTest[1060:1255828] server: accepting invitation Apple-IpadAir2-1_PT1010
,2015-12-15 05:07:23.312 ThaliTest[1060:1256763] client session: connected
2015-12-15 05:07:23.314 ThaliTest[1060:1256763] client session: stateChange:1->2 Apple-IpadAir2-1_PT1010.g7hIzw==
,2015-12-15 05:07:23.320 ThaliTest[1060:1256763] client session: fireConnectCallback: Apple-IpadAir2-1_PT1010.g7hIzw==
2015-12-15 05:07:23.320 ThaliTest[1060:1256763] jxcore: connect: success
2015-12-15T04:07:23.321Z SendDataConnector.js: CLIENT connected, to 59556, error: null
2015-12-15T04:07:23.322Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 05:07:23.327 ThaliTest[1060:1255828] client: relay established
,2015-12-15 05:07:23.328 ThaliTest[1060:1255828] client: new accepted socket: 0x17c6fad0
,2015-12-15T04:07:23.340Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15 05:07:23.496 ThaliTest[1060:1256743] server session: connected
2015-12-15 05:07:23.496 ThaliTest[1060:1256743] server session: stateChange:1->2 Apple-IpadAir2-1_PT1010
,2015-12-15 05:07:23.498 ThaliTest[1060:1255828] server relay: connected (to port: 59545)
,2015-12-15 05:07:23.628 ThaliTest[1060:1256763] server session: connected
2015-12-15 05:07:23.629 ThaliTest[1060:1256763] server session: stateChange:1->2 Apple-Iphone5-1_PT2557
,2015-12-15T04:07:23.655Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15 05:07:23.691 ThaliTest[1060:1255828] server relay: connected (to port: 59545)
,2015-12-15T04:07:23.700Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T04:07:23.761Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-15T04:07:23.790Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15T04:07:23.795Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-15T04:07:23.796Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-15T04:07:23.797Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T04:07:23.797Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:07:23.798 ThaliTest[1060:1256126] jxcore: disconnect
,2015-12-15 05:07:23.798 ThaliTest[1060:1256126] client session: disconnectFromPeer: Apple-IpadAir2-1_PT1010.g7hIzw==
,2015-12-15 05:07:23.799 ThaliTest[1060:1256126] client session: disconnect
,2015-12-15 05:07:23.799 ThaliTest[1060:1256126] client session: stateChange:2->0 Apple-IpadAir2-1_PT1010.g7hIzw==
,2015-12-15 05:07:23.820 ThaliTest[1060:1256752] server session: not connected Apple-IpadAir2-1_PT1010
,2015-12-15 05:07:23.866 ThaliTest[1060:1256126] jxcore: disconnect: success
,2015-12-15T04:07:23.867Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1010.g7hIzw==
---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone5-1_PT2557.fyiFnQ==
,2015-12-15T04:07:23.868Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2557.fyiFnQ==
,2015-12-15T04:07:23.868Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2557.fyiFnQ==
,2015-12-15T04:07:23.868Z SendDataConnector.js: do connect now
,2015-12-15 05:07:23.869 ThaliTest[1060:1256126] jxcore: connect Apple-Iphone5-1_PT2557.fyiFnQ==
,2015-12-15 05:07:23.870 ThaliTest[1060:1256126] client session: connect
,2015-12-15 05:07:23.870 ThaliTest[1060:1256126] client session: stateChange:0->1 Apple-Iphone5-1_PT2557.fyiFnQ==
,2015-12-15T04:07:24.353Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-15T04:07:24.372Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-15T04:07:24.389Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-15T04:07:24.404Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-15T04:07:24.415Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-15T04:07:24.492Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 05:07:24.567 ThaliTest[1060:1256752] server session: not connected Apple-Iphone5-1_PT2557
,2015-12-15 05:07:26.738 ThaliTest[1060:1256752] client session: connected
2015-12-15 05:07:26.738 ThaliTest[1060:1256752] client session: stateChange:1->2 Apple-Iphone5-1_PT2557.fyiFnQ==
,2015-12-15 05:07:26.839 ThaliTest[1060:1256763] client session: fireConnectCallback: Apple-Iphone5-1_PT2557.fyiFnQ==
2015-12-15 05:07:26.840 ThaliTest[1060:1256763] jxcore: connect: success
2015-12-15T04:07:26.841Z SendDataConnector.js: CLIENT connected ,to 59561, error: null
2015-12-15T04:07:26.842Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 05:07:26.846 ThaliTest[1060:1255828] client: relay established
2015-12-15 05:07:26.846 ThaliTest[1060:1255828] client: new accepted socket: 0x17b06d60
,2015-12-15T04:07:26.859Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T04:07:27.234Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-15T04:07:27.258Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T04:07:27.258Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-15T04:07:27.259Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T04:07:27.259Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:07:27.259 ThaliTest[1060:1256126] jxcore: disconnect
,2015-12-15 05:07:27.260 ThaliTest[1060:1256126] client session: disconnectFromPeer: Apple-Iphone5-1_PT2557.fyiFnQ==
,2015-12-15 05:07:27.260 ThaliTest[1060:1256126] client session: disconnect
,2015-12-15 05:07:27.261 ThaliTest[1060:1256126] client session: stateChange:2->0 Apple-Iphone5-1_PT2557.fyiFnQ==
,2015-12-15 05:07:27.328 ThaliTest[1060:1256126] jxcore: disconnect: success
,2015-12-15T04:07:27.329Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2557.fyiFnQ==
---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2015-12-15T04:07:27.333Z SendDataConnector.js: CLIENT Stop now
2015-12-15T04:07:27.333Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
,2015-12-15 05:07:30.152 ThaliTest[1060:1256126] jxcore: stopBroadcasting
,2015-12-15 05:07:30.152 ThaliTest[1060:1256126] THEMultipeerSession stopping peer
,2015-12-15 05:07:30.153 ThaliTest[1060:1256126] multipeer session: stop timer
2015-12-15 05:07:30.155 ThaliTest[1060:1256126] server session: disconnect
2015-12-15 05:07:30.155 ThaliTest[1060:1256126] server session: stateChange:2->0 Apple-IpadAir2-1_PT1010
,2015-12-15 05:07:30.167 ThaliTest[1060:1256126] server session: disconnect
2015-12-15 05:07:30.167 ThaliTest[1060:1256126] server session: stateChange:2->0 Apple-Iphone6-1_PT9306
,2015-12-15 05:07:30.253 ThaliTest[1060:1256126] server session: disconnect
,2015-12-15 05:07:30.257 ThaliTest[1060:1256126] server session: stateChange:2->0 Apple-Iphone5-1_PT2557
,2015-12-15 05:07:31.357 ThaliTest[1060:1256126] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-15T04:07:31.375Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-15T04:07:31.377Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-15T04:07:31.379Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-15T04:07:31.380Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
