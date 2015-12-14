#### Test 506502788f5bfb2_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502788f5bfb2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/275921EC-B973-4302-BEC6-E715779D502C/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/275921EC-B973-4302-BEC6-E715779D502C/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502788f5bfb2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502788f5bfb2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/66D82EAA-C55C-41E5-A57B-C68FED0243FB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55803"
,(lldb)     command script import "/tmp/275921EC-B973-4302-BEC6-E715779D502C/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-14 21:14:39.120 ThaliTest[808:1310629] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E41411D6-AB7E-4592-9C95-0300780DC180/Library/Cookies/Cookies.binarycookies
,2015-12-14 21:14:39.257 ThaliTest[808:1310629] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-14 21:14:39.258 ThaliTest[808:1310629] Multi-tasking -> Device: YES, App: YES
,2015-12-14 21:14:39.266 ThaliTest[808:1310629] Unlimited access to network resources
,2015-12-14 21:14:39.280 ThaliTest[808:1310629] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-14 21:14:50.168 ThaliTest[808:1310629] Resetting plugins due to page load.
,2015-12-14 21:14:54.399 ThaliTest[808:1310629] Finished load of: file:///var/mobile/Containers/Bundle/Application/66D82EAA-C55C-41E5-A57B-C68FED0243FB/ThaliTest.app/www/index.html
,2015-12-14 21:14:54.605 ThaliTest[808:1310629] JXcore Cordova plugin initializing
,2015-12-14 21:14:54.606 ThaliTest[808:1310812] JXcore instance initializing
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
,2015-12-14 21:14:57.033 ThaliTest[808:1310629] THREAD WARNING: ['JXcore'] took '157.549072' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-14 21:21:34.060 ThaliTest[808:1310812] jxcore: startBroadcasting
,2015-12-14 21:21:34.074 ThaliTest[808:1310812] server: starting Apple-Iphone5-1_PT5632.KnhjEg==
,2015-12-14 21:21:34.081 ThaliTest[808:1310812] multipeer session: start timer: 0x1d21d4c0
,2015-12-14 21:21:34.090 ThaliTest[808:1310812] THEMultipeerSession initialized peer Apple-Iphone5-1_PT5632
,2015-12-14 21:21:34.091 ThaliTest[808:1310812] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-14 21:21:35.293 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.P6/fMg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1173.P6/fMg==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1_PT1,173.P6/fMg==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,2015-12-14 21:21:35.869 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.GaMN6Q==
,teardown
,testFindPeers stopped
,2015-12-14 21:21:38.103 ThaliTest[808:1310812] jxcore: stopBroadcasting
2015-12-14 21:21:38.104 ThaliTest[808:1310812] THEMultipeerSession stopping peer
2015-12-14 21:21:38.104 ThaliTest[808:1310812] multipeer session: stop timer
2015-12-14 21:21:38.104 ThaliTest[808:1310812] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 58864
,2015-12-14 21:21:38.266 ThaliTest[808:1310812] jxcore: startBroadcasting
,2015-12-14 21:21:38.268 ThaliTest[808:1310812] server: starting Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:21:38.269 ThaliTest[808:1310812] multipeer session: start timer: 0x1d2147c0
2015-12-14 21:21:38.269 ThaliTest[808:1310812] THEMultipeerSession i,nitialized peer Apple-Iphone5-1_PT5632
2015-12-14 21:21:38.270 ThaliTest[808:1310812] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2015-12-14T20:21:38.272Z SendDataTCPServer.js: TCP/IP server is bound to port: 58864
,2015-12-14 21:21:39.233 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14 21:21:39.233 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.GaMN6Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadA,ir2-1_PT1173.P6/fMg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14T20:21:39.235Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14T20:21:39.236Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14T20:21:39.236Z SendDataConnector.js: do connect now
2015-12-14 21:21:39.237 ThaliTest[808:1310812] jxcore: connect Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14 21:21:39.237 ThaliTest[808:1310812] client session: connect
2015-12-14 21:21:39.238 ThaliTest[808:1310812] client session: stateChange:0->1 Apple-IpadAir2-1_PT1173.P6/fMg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4966.GaMN6Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 21:21:39.926 ThaliTest[808:1310629] client: lost peer: Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14 21:21:39.926 ThaliTest[808:1310629] client session: onPeerLost: Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14 21:21:39.926 ThaliTest[808:1310629] cl,ient: lost peer: Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14 21:21:39.927 ThaliTest[808:1310629] client session: onPeerLost: Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14 21:21:39.927 ThaliTest[808:1310629] client session: onLinkFailure: Apple-IpadAir2-1_P,T1173.P6/fMg==
2015-12-14 21:21:39.927 ThaliTest[808:1310629] client session: disconnect
2015-12-14 21:21:39.927 ThaliTest[808:1310629] client session: stateChange:1->0 Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14 21:21:39.928 ThaliTest[808:1310629] clie,nt session: fireConnectCallback: Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14 21:21:39.928 ThaliTest[808:1310629] jxcore: connect: fail: Peer disconnected
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4966.GaMN6Q==","peerName":"(null)","p,e,erAvailable":false}]
Found peer : (null), Available: false
2015-12-14T20:21:39.933Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-14T20:21:39.933Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-14T20:21:39.934Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1173.P6/fMg==","peerName":"(null)","peerAvailable":false}]
,2015-12-14 21:21:39.942 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4966.0C8RjA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 21:21:40.339 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:21:40.340 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ipad,Air2-1_PT1173.b8TW0A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5395.sHfmmA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14T20:21:44.938Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14T20:21:44.939Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14 21:21:49.947 ThaliTest[808:1310812] jxcore: disconnect
2015-12-14 21:21:49.949 ThaliTest[808:1310812] jxcore: disconnect: fail
2015-12-14T20:21:49.949Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1173.P6/fMg,==
2015-12-14T20:21:49.950Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT1173.P6/fMg== with availability status: true
2015-12-14T20:21:49.950Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14T20:21:49.950Z SendDataConnector.js: do connect now
,2015-12-14 21:21:49.951 ThaliTest[808:1310812] jxcore: connect Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14 21:21:49.953 ThaliTest[808:1310812] client: connect: unreachable Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14 21:21:49.953 ThaliTest[808:1310812] jx,core: connect: fail: Peer unreachable
2015-12-14T20:21:49.953Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T20:21:49.953Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T20:21:49.954Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T20:21:54.960Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14T20:21:54.961Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14 21:21:59.969 ThaliTest[808:1310812] jxcore: disconnect
2015-12-14 21:21:59.970 ThaliTest[808:1310812] jxcore: disconnect: fail
2015-12-14T20:21:59.971Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1173.P6/fMg,==
2015-12-14T20:21:59.971Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT1173.P6/fMg== with availability status: true
2015-12-14T20:21:59.972Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14T20:21:59.972Z SendDataConnector.js: do connect now
,2015-12-14 21:21:59.973 ThaliTest[808:1310812] jxcore: connect Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14 21:21:59.973 ThaliTest[808:1310812] client: connect: unreachable Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14 21:21:59.974 ThaliTest[808:1310812] jx,core: connect: fail: Peer unreachable
,2015-12-14T20:21:59.974Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T20:21:59.975Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T20:21:59.975Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T20:22:04.979Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14T20:22:04.980Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14 21:22:08.270 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:22:08.308 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:22:08.308 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:22:08.309 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:22:09.985 ThaliTest[808:1310812] jxcore: disconnect
2015-12-14 21:22:09.985 ThaliTest[808:1310812] jxcore: disconnect: fail
2015-12-14T20:22:09.986Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1173.P6/fMg,==
2015-12-14T20:22:09.986Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT1173.P6/fMg== with availability status: true
2015-12-14T20:22:09.987Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14T20:22:09.987Z SendDataConnector.js: do connect now
2015-12-14 21:22:09.988 ThaliTest[808:1310812] jxcore: connect Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14 21:22:09.988 ThaliTest[808:1310812] client: connect: unreachable Apple-IpadAir2-1_PT1,173.P6/fMg==
2015-12-14 21:22:09.989 ThaliTest[808:1310812] jxcore: connect: fail: Peer unreachable
,2015-12-14T20:22:09.989Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T20:22:09.989Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T20:22:09.990Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T20:22:15.002Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14T20:22:15.003Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14 21:22:20.014 ThaliTest[808:1310812] jxcore: disconnect
2015-12-14 21:22:20.015 ThaliTest[808:1310812] jxcore: disconnect: fail
2015-12-14T20:22:20.015Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1173.P6/fMg,==
2015-12-14T20:22:20.016Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT1173.P6/fMg== with availability status: true
2015-12-14T20:22:20.016Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14T20:22:20.016Z SendDataConnector.js: do connect now
,2015-12-14 21:22:20.017 ThaliTest[808:1310812] jxcore: connect Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14 21:22:20.017 ThaliTest[808:1310812] client: connect: unreachable Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14 21:22:20.017 ThaliTest[808:1310812] jxcore: connect: fail: Peer unreachable
,2015-12-14T20:22:20.018Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T20:22:20.018Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2015-12-14T20:22:20.020Z SendDataConnector.js: CLIENT Stop now
2015-12-14 21:22:20.020 ThaliTest[808:1310812] jxcore: disconnect
2015-12-14 21:22:20.021 ThaliTest[808:1310812] jxcore: disconnect: fail
2015-12-14T20:22:20.021Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1173.P6/fMg==
---- round done--------
startWithNextDevice
,device[2]: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14T20:22:20.022Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14T20:22:20.022Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14T20:22:20.023Z SendDataConnector.js: do connect now
,2015-12-14 21:22:20.023 ThaliTest[808:1310812] jxcore: connect Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:22:20.024 ThaliTest[808:1310812] client session: connect
2015-12-14 21:22:20.024 ThaliTest[808:1310812] client session: stateChange:0->1 Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:22:22.947 ThaliTest[808:1311634] client session: connected
,2015-12-14 21:22:22.947 ThaliTest[808:1311634] client session: stateChange:1->2 Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:22:22.962 ThaliTest[808:1311632] client session: fireConnectCallback: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:22:22.962 ThaliTest[808:1311632] jxcore: connect: success
2015-12-14T20:22:22.963Z SendDataConnector.js: CLIENT connected to, 58881, error: null
2015-12-14T20:22:22.963Z SendDataConnector.js: CLIENT starting client 
2015-12-14 21:22:22.966 ThaliTest[808:1310629] client: relay established
2015-12-14 21:22:22.966 ThaliTest[808:1310629] client: new accepted socket: 0x1d207330
,2015-12-14T20:22:22.978Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14 21:22:23.150 ThaliTest[808:1310629] multipeer session: reset timer
2015-12-14 21:22:23.150 ThaliTest[808:1310629] multipeer session: stop timer
2015-12-14 21:22:23.150 ThaliTest[808:1310629] multipeer session: start timer: 0x1d2147c0
2015-12-,14 21:22:23.150 ThaliTest[808:1310629] server session: connect
2015-12-14 21:22:23.150 ThaliTest[808:1310629] server session: stateChange:0->1 Apple-Iphone6-1_PT4966
2015-12-14 21:22:23.156 ThaliTest[808:1310629] server: accepting invitation Apple-Iphone,6-1_PT4966
,2015-12-14T20:22:23.937Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-14T20:22:24.013Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T20:22:24.014Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T20:22:24.016Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T20:22:24.016Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 21:22:24.018 ThaliTest[808:1310812] jxcore: disconnect
2015-12-14 21:22:24.018 ThaliTest[808:1310812] client session: disconnectFromPeer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:22:24.018 ThaliTest[808:1310812] client session: disconnect
2015-12-14 21:22:24.018 ThaliTest[808:1310812] client session: stateChange:2->0 Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:22:24.026 ThaliTest[808:1310812] jxcore: disconnect: success
2015-12-14T20:22:24.027Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4966.0C8RjA==
---- round done--------
startWithNextDevice
device[3]: Appl,e-IpadAir2-1_PT1173.b8TW0A==
2015-12-14T20:22:24.027Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14T20:22:24.028Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14T20:,22:24.028Z SendDataConnector.js: do connect now
2015-12-14 21:22:24.028 ThaliTest[808:1310812] jxcore: connect Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:22:24.028 ThaliTest[808:1310812] client session: connect
2015-12-14 21:22:24.029 ThaliTest[808:,1310812] client session: stateChange:0->1 Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:22:25.634 ThaliTest[808:1311633] server session: connected
2015-12-14 21:22:25.635 ThaliTest[808:1311633] server session: stateChange:1->2 Apple-Iphone6-1_PT4966
,2015-12-14 21:22:25.701 ThaliTest[808:1310629] server relay: connected (to port: 58864)
2015-12-14T20:22:25.702Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T20:22:26.029Z SendDataTCPServer.js: TCP/IP server has received 8476 bytes of data
,2015-12-14T20:22:26.044Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-14T20:22:26.060Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-14T20:22:26.075Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 21:22:26.126 ThaliTest[808:1311920] server session: not connected Apple-Iphone6-1_PT4966
,2015-12-14 21:22:27.609 ThaliTest[808:1310629] multipeer session: reset timer
2015-12-14 21:22:27.609 ThaliTest[808:1310629] multipeer session: stop timer
2015-12-14 21:22:27.609 ThaliTest[808:1310629] multipeer session: start timer: 0x1d2147c0
2015-12-14 21:22:27.610 ThaliTest[808:1310629] server session: connect
2015-12-14 21:22:27.610 ThaliTest[808:1310629] server session: stateChange:0->1 Apple-IpadAir2-1_PT1173
,2015-12-14 21:22:27.618 ThaliTest[808:1310629] server: accepting invitation Apple-IpadAir2-1_PT1173
,2015-12-14 21:22:27.673 ThaliTest[808:1311631] client session: connected
2015-12-14 21:22:27.673 ThaliTest[808:1311631] client session: stateChange:1->2 Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:22:27.689 ThaliTest[808:1311633] client session: fireConnectCallback: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:22:27.689 ThaliTest[808:1311633] jxcore: connect: success
2015-12-14T20:22:27.691Z SendDataConnector.js: CLIENT connected to 58886, error: null
,2015-12-14T20:22:27.693Z SendDataConnector.js: CLIENT starting client 
2015-12-14 21:22:27.696 ThaliTest[808:1310629] client: relay established
2015-12-14 21:22:27.697 ThaliTest[808:1310629] client: new accepted socket: 0x1d47e5c0
,2015-12-14T20:22:27.709Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T20:22:28.338Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-14T20:22:28.389Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T20:22:28.389Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T20:22:28.392Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T20:22:28.393Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 21:22:28.395 ThaliTest[808:1310812] jxcore: disconnect
,2015-12-14 21:22:28.396 ThaliTest[808:1310812] client session: disconnectFromPeer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:22:28.397 ThaliTest[808:1310812] client session: disconnect
,2015-12-14 21:22:28.398 ThaliTest[808:1310812] client session: stateChange:2->0 Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:22:28.481 ThaliTest[808:1310812] jxcore: disconnect: success
,2015-12-14T20:22:28.483Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1173.b8TW0A==
---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14T20:22:28.485Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14T20:22:28.485Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14T20:22:28.486Z SendDataConnector.js: do connect now
,2015-12-14 21:22:28.486 ThaliTest[808:1310812] jxcore: connect Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:22:28.487 ThaliTest[808:1310812] client session: connect
,2015-12-14 21:22:28.488 ThaliTest[808:1310812] client session: stateChange:0->1 Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:22:30.556 ThaliTest[808:1311632] server session: connected
2015-12-14 21:22:30.556 ThaliTest[808:1311632] server session: stateChange:1->2 Apple-IpadAir2-1_PT1173
,2015-12-14 21:22:30.566 ThaliTest[808:1310629] server relay: connected (to port: 58864)
,2015-12-14T20:22:30.571Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T20:22:30.846Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-14T20:22:30.874Z SendDataTCPServer.js: TCP/IP server has received 25854 bytes of data
,2015-12-14T20:22:30.891Z SendDataTCPServer.js: TCP/IP server has received 62658 bytes of data
,2015-12-14T20:22:30.909Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 21:22:30.950 ThaliTest[808:1311632] server session: not connected Apple-IpadAir2-1_PT1173
,2015-12-14 21:22:31.859 ThaliTest[808:1311633] client session: connected
2015-12-14 21:22:31.859 ThaliTest[808:1311633] client session: stateChange:1->2 Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:22:31.881 ThaliTest[808:1311633] client session: fireConnectCallback: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:22:31.882 ThaliTest[808:1311633] jxcore: connect: success
2015-12-14T20:22:31.882Z SendDataConnector.js: CLIENT connected to 58890, error: null
2015-12-14T20:22:31.883Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 21:22:31.885 ThaliTest[808:1310629] client: relay established
2015-12-14 21:22:31.885 ThaliTest[808:1310629] client: new accepted socket: 0x1d48bbc0
,2015-12-14T20:22:31.898Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T20:22:32.512Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-14T20:22:32.527Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-14T20:22:32.542Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-14T20:22:32.571Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T20:22:32.572Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T20:22:32.573Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T20:22:32.574Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 21:22:32.575 ThaliTest[808:1310812] jxcore: disconnect
2015-12-14 21:22:32.575 ThaliTest[808:1310812] client session: disconnectFromPeer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:22:32.575 ThaliTest[808:1310812] client session: disconnec,t
2015-12-14 21:22:32.575 ThaliTest[808:1310812] client session: stateChange:2->0 Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:22:32.583 ThaliTest[808:1310812] jxcore: disconnect: success
2015-12-14T20:22:32.585Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5395.sHfmmA==
---- round done--------
startWithNextDevice
weAreDoneNow, ,resultArray.length: 4
sendReportNow
done, now sending data to server
,2015-12-14T20:22:32.591Z SendDataConnector.js: CLIENT Stop now
2015-12-14T20:22:32.591Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 21:22:57.611 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:22:57.649 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:22:57.650 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:22:57.650 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:23:00.303 ThaliTest[808:1310629] multipeer session: reset timer
2015-12-14 21:23:00.303 ThaliTest[808:1310629] multipeer session: stop timer
2015-12-14 21:23:00.303 ThaliTest[808:1310629] multipeer session: start timer: 0x1d2147c0
,2015-12-14 21:23:00.304 ThaliTest[808:1310629] server session: connect
2015-12-14 21:23:00.304 ThaliTest[808:1310629] server session: stateChange:0->1 Apple-Iphone5s-1_PT5395
,2015-12-14 21:23:00.310 ThaliTest[808:1310629] server: accepting invitation Apple-Iphone5s-1_PT5395
,2015-12-14 21:23:03.260 ThaliTest[808:1312067] server session: connected
,2015-12-14 21:23:03.261 ThaliTest[808:1312067] server session: stateChange:1->2 Apple-Iphone5s-1_PT5395
,2015-12-14 21:23:03.292 ThaliTest[808:1310629] server relay: connected (to port: 58864)
,2015-12-14T20:23:03.304Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T20:23:03.780Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-14T20:23:03.821Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-14T20:23:03.838Z SendDataTCPServer.js: TCP/IP server has received 54608 bytes of data
,2015-12-14T20:23:03.855Z SendDataTCPServer.js: TCP/IP server has received 85126 bytes of data
,2015-12-14T20:23:03.872Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 21:23:03.913 ThaliTest[808:1312085] server session: not connected Apple-Iphone5s-1_PT5395
,2015-12-14 21:23:30.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:23:30.342 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:23:30.343 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:23:30.960 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
serverPort is 8876
2015-12-14 21:23:31.571 ThaliTest[808:1310812] jxcore: startBroadcasting
,2015-12-14 21:23:31.572 ThaliTest[808:1310812] jxcore: startBroadcasting: failure
,weAreDoneNow
done, now sending data to server
,done, now sending data to server
,2015-12-14 21:24:00.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:24:00.342 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:24:00.343 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:24:00.344 ThaliTest[808:1310629] client: ,found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:24:30.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:25:00.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:25:00.327 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:25:00.329 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:25:00.330 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:25:30.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:25:30.333 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:25:30.335 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:25:30.816 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:26:00.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:26:00.337 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:26:00.337 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:26:00.343 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:26:30.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:27:00.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:27:00.335 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:27:00.335 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:27:00.898 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:27:30.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:27:30.334 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:27:30.953 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:27:30.953 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:28:00.304 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:28:00.335 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:28:00.675 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:28:01.218 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:28:30.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:28:30.335 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:28:31.015 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:28:31.780 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:29:00.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:29:30.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:29:30.336 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:29:30.336 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:29:30.336 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:30:00.304 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:30:30.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:30:30.335 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:30:30.338 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:30:31.058 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:31:00.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:31:00.337 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:31:00.337 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:31:00.856 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:31:30.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:31:30.337 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:31:30.337 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:31:30.842 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:32:00.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:32:00.331 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:32:00.332 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:32:01.172 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:32:30.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:33:00.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:33:00.335 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:33:00.335 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:33:00.900 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:33:30.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:33:30.334 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:33:30.334 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:33:30.708 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:34:00.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:34:00.338 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:34:00.338 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:34:01.081 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:34:30.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:34:31.055 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:34:31.058 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:34:31.059 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:35:00.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:35:00.338 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:35:00.338 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:35:00.811 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:35:30.304 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:35:30.336 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:35:30.336 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:35:30.751 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:36:00.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:36:00.335 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:36:00.335 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:36:01.127 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:36:30.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:36:30.335 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:36:30.335 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:36:30.337 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:37:00.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:37:00.338 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:37:00.338 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:37:01.094 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:37:30.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:37:30.335 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:37:30.336 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:37:30.911 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:38:00.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:38:00.335 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:38:00.336 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:38:00.884 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:38:30.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:38:30.336 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:38:30.336 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:38:31.252 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:39:00.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:39:00.337 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:39:00.338 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:39:01.233 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:39:30.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:39:30.336 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:39:30.336 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:39:30.995 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:40:00.305 ThaliTest[808:1310629] multipeer session: restart
,timeout now
,2015-12-14 21:40:30.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:40:30.333 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:40:30.334 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:40:31.321 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:41:00.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:41:00.337 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:41:00.337 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:41:01.110 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:41:30.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:41:30.336 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:41:30.336 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:41:30.339 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:42:00.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:42:30.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:42:30.334 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:42:30.336 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:42:42.726 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:43:00.305 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:43:30.304 ThaliTest[808:1310629] multipeer session: restart
,2015-12-14 21:43:30.331 ThaliTest[808:1310629] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:43:30.882 ThaliTest[808:1310629] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:43:30.882 ThaliTest[808:1310629] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==

```
