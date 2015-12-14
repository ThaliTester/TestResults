#### Test 506502788f5bfb2_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502788f5bfb2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/22B04403-B15D-4875-8C62-3BBF65668D2C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/22B04403-B15D-4875-8C62-3BBF65668D2C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502788f5bfb2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502788f5bfb2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/172BBF99-E68D-4C55-83D8-049BEF2377E2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55831"
,(lldb)     command script import "/tmp/22B04403-B15D-4875-8C62-3BBF65668D2C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-14 21:16:09.215 ThaliTest[984:1198267] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3EEA83F9-E2E4-43E6-B31C-6CD86CC93987/Library/Cookies/Cookies.binarycookies
,2015-12-14 21:16:09.613 ThaliTest[984:1198267] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-14 21:16:09.614 ThaliTest[984:1198267] Multi-tasking -> Device: YES, App: YES
,2015-12-14 21:16:09.624 ThaliTest[984:1198267] Unlimited access to network resources
,2015-12-14 21:16:09.636 ThaliTest[984:1198267] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-14 21:16:18.679 ThaliTest[984:1198267] Resetting plugins due to page load.
,2015-12-14 21:16:22.416 ThaliTest[984:1198267] Finished load of: file:///var/mobile/Containers/Bundle/Application/172BBF99-E68D-4C55-83D8-049BEF2377E2/ThaliTest.app/www/index.html
,2015-12-14 21:16:22.647 ThaliTest[984:1198267] JXcore Cordova plugin initializing
,2015-12-14 21:16:22.648 ThaliTest[984:1198485] JXcore instance initializing
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
,2015-12-14 21:16:23.952 ThaliTest[984:1198267] THREAD WARNING: ['JXcore'] took '83.890869' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-14 21:21:36.874 ThaliTest[984:1198485] jxcore: startBroadcasting
,2015-12-14 21:21:36.897 ThaliTest[984:1198485] server: starting Apple-Iphone5s-1_PT5395.Gkqfnw==
,2015-12-14 21:21:36.900 ThaliTest[984:1198485] multipeer session: start timer: 0x15c0bb50
,2015-12-14 21:21:36.923 ThaliTest[984:1198485] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT5395
,2015-12-14 21:21:36.925 ThaliTest[984:1198485] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-14 21:21:37.736 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14 21:21:37.738 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.GaMN6Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadA,ir2-1_PT1173.P6/fMg==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1_PT1173.P6/fMg==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,teardown
,testFindPeers stopped
,2015-12-14 21:21:38.091 ThaliTest[984:1198485] jxcore: stopBroadcasting
2015-12-14 21:21:38.092 ThaliTest[984:1198485] THEMultipeerSession stopping peer
2015-12-14 21:21:38.092 ThaliTest[984:1198485] multipeer session: stop timer
2015-12-14 21:21:38.093 ThaliTest[984:1198485] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 58387
,2015-12-14 21:21:38.226 ThaliTest[984:1198485] jxcore: startBroadcasting
,2015-12-14 21:21:38.229 ThaliTest[984:1198485] server: starting Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:21:38.230 ThaliTest[984:1198485] multipeer session: start timer: 0x15b96440
2015-12-14 21:21:38.230 ThaliTest[984:1198485] THEMultipeerSession ,initialized peer Apple-Iphone5s-1_PT5395
2015-12-14 21:21:38.230 ThaliTest[984:1198485] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
,2015-12-14T20:21:38.233Z SendDataTCPServer.js: TCP/IP server is bound to port: 58387
,2015-12-14 21:21:39.249 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14 21:21:39.250 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.GaMN6Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadA,ir2-1_PT1173.P6/fMg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14T20:21:39.256Z SendDataConnector.js: Start called with peer Apple-IpadAir2-,1_PT1173.P6/fMg==
2015-12-14T20:21:39.257Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14T20:21:39.258Z SendDataConnector.js: do connect now
,2015-12-14 21:21:39.259 ThaliTest[984:1198485] jxcore: connect Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14 21:21:39.261 ThaliTest[984:1198485] client session: connect
2015-12-14 21:21:39.262 ThaliTest[984:1198485] client session: stateChange:0->1 Apple-I,padAir2-1_PT1173.P6/fMg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4966.GaMN6Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 21:21:39.846 ThaliTest[984:1198267] client: lost peer: Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14 21:21:39.848 ThaliTest[984:1198267] client session: onPeerLost: Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14 21:21:39.850 ThaliTest[984:1198267] client session: onLinkFailure: Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14 21:21:39.850 ThaliTest[9,84:1198267] client session: disconnect
2015-12-14 21:21:39.850 ThaliTest[984:1198267] client session: stateChange:1->0 Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14 21:21:39.851 ThaliTest[984:1198267] client session: fireConnectCallback: Apple-IpadAir2-1_P,T1173.P6/fMg==
2015-12-14 21:21:39.851 ThaliTest[984:1198267] jxcore: connect: fail: Peer disconnected
2015-12-14 21:21:39.852 ThaliTest[984:1198267] client: lost peer: Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14 21:21:39.852 ThaliTest[984:1198267] clien,t session: onPeerLost: Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14T20:21:39.854Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-14T20:21:39.855Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-14T20:,2015-12-14 21:21:39.854 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
21:39.856Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1173.P6/fMg==","peerName":"(null)",,"peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4966.GaMN6Q==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5632.ug/,nGg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 21:21:39.984 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4966.0C8RjA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-14 21:21:40.341 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1173.b8TW0A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14T20:21:44.868Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14T20:21:44.869Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14 21:21:49.872 ThaliTest[984:1198485] jxcore: disconnect
2015-12-14 21:21:49.872 ThaliTest[984:1198485] jxcore: disconnect: fail
2015-12-14T20:21:49.873Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1173.P6/fMg,==
2015-12-14T20:21:49.874Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT1173.P6/fMg== with availability status: true
,2015-12-14T20:21:49.874Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14T20:21:49.874Z SendDataConnector.js: do connect now
,2015-12-14 21:21:49.875 ThaliTest[984:1198485] jxcore: connect Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14 21:21:49.876 ThaliTest[984:1198485] client: connect: unreachable Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14 21:21:49.877 ThaliTest[984:1198485] jxcore: connect: fail: Peer unreachable
,2015-12-14T20:21:49.878Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T20:21:49.879Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T20:21:49.879Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T20:21:54.886Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14T20:21:54.887Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14 21:21:59.896 ThaliTest[984:1198485] jxcore: disconnect
2015-12-14 21:21:59.896 ThaliTest[984:1198485] jxcore: disconnect: fail
2015-12-14T20:21:59.897Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1173.P6/fMg,==
2015-12-14T20:21:59.897Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT1173.P6/fMg== with availability status: true
2015-12-14T20:21:59.898Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14T20:21:59.898Z SendDataConnector.js: do connect now
,2015-12-14 21:21:59.899 ThaliTest[984:1198485] jxcore: connect Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14 21:21:59.900 ThaliTest[984:1198485] client: connect: unreachable Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14 21:21:59.901 ThaliTest[984:1198485] jxcore: connect: fail: Peer unreachable
,2015-12-14T20:21:59.901Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T20:21:59.903Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T20:21:59.904Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T20:22:04.911Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14T20:22:04.911Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14 21:22:08.231 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:22:09.922 ThaliTest[984:1198485] jxcore: disconnect
2015-12-14 21:22:09.923 ThaliTest[984:1198485] jxcore: disconnect: fail
2015-12-14T20:22:09.924Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1173.P6/fMg,==
2015-12-14T20:22:09.924Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT1173.P6/fMg== with availability status: true
2015-12-14T20:22:09.924Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14T20:22:09.925Z SendDataConnector.js: do connect now
2015-12-14 21:22:09.926 ThaliTest[984:1198485] jxcore: connect Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14 21:22:09.927 ThaliTest[984:1198485] client: connect: unreachable Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14 21:22:09.927 ThaliTest[984:1198485] jxcore: connect: fail: Peer unreachable
,2015-12-14T20:22:09.928Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T20:22:09.929Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T20:22:09.929Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T20:22:14.940Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14T20:22:14.940Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14 21:22:19.942 ThaliTest[984:1198485] jxcore: disconnect
2015-12-14 21:22:19.943 ThaliTest[984:1198485] jxcore: disconnect: fail
2015-12-14T20:22:19.943Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1173.P6/fMg,==
2015-12-14T20:22:19.944Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT1173.P6/fMg== with availability status: true
2015-12-14T20:22:19.944Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14T20:22:19.944Z SendDataConnector.js: do connect now
2015-12-14 21:22:19.946 ThaliTest[984:1198485] jxcore: connect Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14 21:22:19.946 ThaliTest[984:1198485] client: connect: unreachable Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14 21:22:19.947 ThaliTest[984:1198485] jxcore: connect: fail: Peer unreachable
,2015-12-14T20:22:19.948Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T20:22:19.949Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
2015-12-14T20:22:19.951Z SendDataConnector.js: CLIENT Stop now
,2015-12-14 21:22:19.952 ThaliTest[984:1198485] jxcore: disconnect
2015-12-14 21:22:19.953 ThaliTest[984:1198485] jxcore: disconnect: fail
,2015-12-14T20:22:19.954Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1173.P6/fMg==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14T20:22:19.958Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14T20:22:19.959Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14T20:22:19.960Z SendDataConnector.js: do connect now
,2015-12-14 21:22:19.961 ThaliTest[984:1198485] jxcore: connect Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:22:19.962 ThaliTest[984:1198485] client session: connect
2015-12-14 21:22:19.962 ThaliTest[984:1198485] client session: stateChange:0->1 Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:22:19.975 ThaliTest[984:1198267] client: lost peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:22:19.976 ThaliTest[984:1198267] client session: onPeerLost: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:22:19.976 ThaliTest[984:1198267] cl,ient session: onLinkFailure: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:22:19.976 ThaliTest[984:1198267] client session: disconnect
2015-12-14 21:22:19.976 ThaliTest[984:1198267] client session: stateChange:1->0 Apple-Iphone5-1_PT5632.ug/nGg==
2015-1,2-14 21:22:19.977 ThaliTest[984:1198267] client session: fireConnectCallback: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:22:19.977 ThaliTest[984:1198267] jxcore: connect: fail: Peer disconnected
2015-12-14T20:22:19.979Z SendDataConnector.js: CLIENT co,nnected to 0, error: Peer disconnected
2015-12-14T20:22:19.980Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-14T20:22:19.985Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5632.ug/nGg==","peerName":"(null)","peerAvailable":false}]
,2015-12-14 21:22:23.544 ThaliTest[984:1198267] multipeer session: reset timer
2015-12-14 21:22:23.544 ThaliTest[984:1198267] multipeer session: stop timer
2015-12-14 21:22:23.545 ThaliTest[984:1198267] multipeer session: start timer: 0x15b96440
2015-12-,14 21:22:23.545 ThaliTest[984:1198267] server session: connect
2015-12-14 21:22:23.546 ThaliTest[984:1198267] server session: stateChange:0->1 Apple-IpadAir2-1_PT1173
,2015-12-14 21:22:23.560 ThaliTest[984:1198267] server: accepting invitation Apple-IpadAir2-1_PT1173
,2015-12-14T20:22:24.993Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14T20:22:24.993Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:22:26.172 ThaliTest[984:1198267] multipeer session: reset timer
2015-12-14 21:22:26.172 ThaliTest[984:1198267] multipeer session: stop timer
2015-12-14 21:22:26.173 ThaliTest[984:1198267] multipeer session: start timer: 0x15b96440
2015-12-,14 21:22:26.173 ThaliTest[984:1198267] server session: connect
2015-12-14 21:22:26.174 ThaliTest[984:1198267] server session: stateChange:0->1 Apple-Iphone6-1_PT4966
,2015-12-14 21:22:26.185 ThaliTest[984:1198267] server: accepting invitation Apple-Iphone6-1_PT4966
,2015-12-14 21:22:26.564 ThaliTest[984:1199218] server session: connected
2015-12-14 21:22:26.564 ThaliTest[984:1199218] server session: stateChange:1->2 Apple-IpadAir2-1_PT1173
,2015-12-14 21:22:26.570 ThaliTest[984:1198267] server relay: connected (to port: 58387)
,2015-12-14T20:22:26.577Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T20:22:27.040Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-14T20:22:27.058Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-14T20:22:27.073Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-14T20:22:27.091Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-14T20:22:27.107Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 21:22:27.191 ThaliTest[984:1199075] server session: not connected Apple-IpadAir2-1_PT1173
,2015-12-14 21:22:28.731 ThaliTest[984:1198267] multipeer session: reset timer
2015-12-14 21:22:28.733 ThaliTest[984:1198267] multipeer session: stop timer
,2015-12-14 21:22:28.733 ThaliTest[984:1198267] multipeer session: start timer: 0x15b96440
,2015-12-14 21:22:28.735 ThaliTest[984:1198267] server session: connect
,2015-12-14 21:22:28.736 ThaliTest[984:1198267] server session: stateChange:0->1 Apple-Iphone5-1_PT5632
2015-12-14 21:22:28.735 ThaliTest[984:1199074] server session: connected
2015-12-14 21:22:28.738 ThaliTest[984:1199074] server session: stateChange:1->2 Apple-Iphone6-1_PT4966
,2015-12-14 21:22:28.751 ThaliTest[984:1198267] server: accepting invitation Apple-Iphone5-1_PT5632
,2015-12-14 21:22:28.821 ThaliTest[984:1198267] server relay: connected (to port: 58387)
,2015-12-14T20:22:28.834Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T20:22:29.137Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-14T20:22:29.163Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-14T20:22:29.182Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-14T20:22:29.196Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 21:22:29.352 ThaliTest[984:1199074] server session: not connected Apple-Iphone6-1_PT4966
,2015-12-14 21:22:29.997 ThaliTest[984:1198485] jxcore: disconnect
2015-12-14 21:22:29.998 ThaliTest[984:1198485] jxcore: disconnect: fail
2015-12-14T20:22:29.998Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5632.ug/nGg=,=
2015-12-14T20:22:29.999Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT5632.ug/nGg== with availability status: true
2015-12-14T20:22:29.999Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14T20:22:29.999Z SendDataConnector.js: do connect now
,2015-12-14 21:22:30.000 ThaliTest[984:1198485] jxcore: connect Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:22:30.001 ThaliTest[984:1198485] client: connect: unreachable Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:22:30.001 ThaliTest[984:1198485] jxco,re: connect: fail: Peer unreachable
,2015-12-14T20:22:30.002Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T20:22:30.002Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T20:22:30.003Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14 21:22:31.821 ThaliTest[984:1199218] server session: connected
2015-12-14 21:22:31.823 ThaliTest[984:1199218] server session: stateChange:1->2 Apple-Iphone5-1_PT5632
,2015-12-14 21:22:31.832 ThaliTest[984:1198267] server relay: connected (to port: 58387)
2015-12-14T20:22:31.835Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T20:22:32.400Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-14T20:22:32.415Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-14T20:22:32.436Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-14T20:22:32.453Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-14T20:22:32.475Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-14T20:22:32.489Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 21:22:32.579 ThaliTest[984:1199074] server session: not connected Apple-Iphone5-1_PT5632
,2015-12-14T20:22:35.011Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14T20:22:35.012Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:22:40.025 ThaliTest[984:1198485] jxcore: disconnect
2015-12-14 21:22:40.026 ThaliTest[984:1198485] jxcore: disconnect: fail
2015-12-14T20:22:40.026Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5632.ug/nGg=,=
2015-12-14T20:22:40.027Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT5632.ug/nGg== with availability status: true
2015-12-14T20:22:40.027Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5632.ug/nGg==
201,5-12-14T20:22:40.027Z SendDataConnector.js: do connect now
,2015-12-14 21:22:40.028 ThaliTest[984:1198485] jxcore: connect Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:22:40.029 ThaliTest[984:1198485] client: connect: unreachable Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:22:40.030 ThaliTest[984:1198485] jxcore: connect: fail: Peer unreachable
2015-12-14T20:22:40.032Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T20:22:40.032Z SendDataConnector.js: CLIENT Can not Connect: Pe,er unreachable
2015-12-14T20:22:40.032Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T20:22:45.036Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14T20:22:45.037Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:22:50.040 ThaliTest[984:1198485] jxcore: disconnect
2015-12-14 21:22:50.040 ThaliTest[984:1198485] jxcore: disconnect: fail
2015-12-14T20:22:50.041Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5632.ug/nGg=,=
2015-12-14T20:22:50.041Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT5632.ug/nGg== with availability status: true
2015-12-14T20:22:50.042Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5632.ug/nGg==
201,5-12-14T20:22:50.043Z SendDataConnector.js: do connect now
,2015-12-14 21:22:50.043 ThaliTest[984:1198485] jxcore: connect Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:22:50.044 ThaliTest[984:1198485] client: connect: unreachable Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:22:50.045 ThaliTest[984:1198485] jxco,re: connect: fail: Peer unreachable
2015-12-14T20:22:50.046Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T20:22:50.046Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T20:22:50.046Z SendDataCo,nnector.js: tryAgain afer: 5000 ms.
,2015-12-14T20:22:55.049Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14T20:22:55.049Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:22:58.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:22:58.777 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:22:58.781 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone,5-1_PT5632.ug/nGg==","peerName":"(null)","peerAvailable":true}]
2015-12-14 21:22:58.785 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:23:00.056 ThaliTest[984:1198485] jxcore: disconnect
2015-12-14 21:23:00.057 ThaliTest[984:1198485] jxcore: disconnect: fail
2015-12-14T20:23:00.058Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5632.ug/nGg=,=
2015-12-14T20:23:00.058Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT5632.ug/nGg== with availability status: true
2015-12-14T20:23:00.059Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14T20:23:00.059Z SendDataConnector.js: do connect now
2015-12-14 21:23:00.060 ThaliTest[984:1198485] jxcore: connect Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:23:00.061 ThaliTest[984:1198485] client session: connect
,2015-12-14 21:23:00.061 ThaliTest[984:1198485] client session: stateChange:0->1 Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:23:03.217 ThaliTest[984:1199512] client session: connected
2015-12-14 21:23:03.220 ThaliTest[984:1199512] client session: stateChange:1->2 Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:23:03.237 ThaliTest[984:1199513] client session: fireConnectCallback: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:23:03.238 ThaliTest[984:1199513] jxcore: connect: success
,2015-12-14T20:23:03.242Z SendDataConnector.js: CLIENT connected to 58405, error: null
2015-12-14T20:23:03.243Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 21:23:03.248 ThaliTest[984:1198267] client: relay established
2015-12-14 21:23:03.248 ThaliTest[984:1198267] client: new accepted socket: 0x15bb6660
,2015-12-14T20:23:03.262Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T20:23:03.792Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-14T20:23:03.830Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T20:23:03.830Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T20:23:03.831Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T20:23:03.831Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 21:23:03.832 ThaliTest[984:1198485] jxcore: disconnect
,2015-12-14 21:23:03.833 ThaliTest[984:1198485] client session: disconnectFromPeer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:23:03.833 ThaliTest[984:1198485] client session: disconnect
,2015-12-14 21:23:03.834 ThaliTest[984:1198485] client session: stateChange:2->0 Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:23:03.902 ThaliTest[984:1198485] jxcore: disconnect: success
2015-12-14T20:23:03.902Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5632.ug/nGg==
---- round done--------
startWithNextDevice
,device[3]: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14T20:23:03.903Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14T20:23:03.903Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14T20:23:03.903Z SendDataConnector.js: do connect now
,2015-12-14 21:23:03.904 ThaliTest[984:1198485] jxcore: connect Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:23:03.904 ThaliTest[984:1198485] client session: connect
2015-12-14 21:23:03.904 ThaliTest[984:1198485] client session: stateChange:0->1 Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:23:07.966 ThaliTest[984:1199513] client session: connected
2015-12-14 21:23:07.966 ThaliTest[984:1199513] client session: stateChange:1->2 Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:23:08.083 ThaliTest[984:1199514] client session: fireConnectCallback: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:23:08.083 ThaliTest[984:1199514] jxcore: connect: success
,2015-12-14T20:23:08.084Z SendDataConnector.js: CLIENT connected to 58408, error: null
,2015-12-14T20:23:08.085Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 21:23:08.089 ThaliTest[984:1198267] client: relay established
2015-12-14 21:23:08.090 ThaliTest[984:1198267] client: new accepted socket: 0x15baf790
,2015-12-14T20:23:08.103Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T20:23:08.531Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-14T20:23:08.544Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-14T20:23:09.011Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T20:23:09.012Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T20:23:09.014Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T20:23:09.014Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 21:23:09.016 ThaliTest[984:1198485] jxcore: disconnect
2015-12-14 21:23:09.016 ThaliTest[984:1198485] client session: disconnectFromPeer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:23:09.017 ThaliTest[984:1198485] client session: disconnect,
2015-12-14 21:23:09.017 ThaliTest[984:1198485] client session: stateChange:2->0 Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:23:09.110 ThaliTest[984:1198485] jxcore: disconnect: success
,2015-12-14T20:23:09.112Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4966.0C8RjA==
,---- round done--------
,startWithNextDevice
,device[4]: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14T20:23:09.115Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14T20:23:09.116Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14T20:23:09.117Z SendDataConnector.js: do connect now
,2015-12-14 21:23:09.118 ThaliTest[984:1198485] jxcore: connect Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:23:09.120 ThaliTest[984:1198485] client session: connect
,2015-12-14 21:23:09.121 ThaliTest[984:1198485] client session: stateChange:0->1 Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:23:12.480 ThaliTest[984:1199516] client session: connected
2015-12-14 21:23:12.481 ThaliTest[984:1199516] client session: stateChange:1->2 Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:23:12.496 ThaliTest[984:1199514] client session: fireConnectCallback: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:23:12.496 ThaliTest[984:1199514] jxcore: connect: success
2015-12-14T20:23:12.498Z SendDataConnector.js: CLIENT connected to 58411, error: null
2015-12-14T20:23:12.498Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 21:23:12.502 ThaliTest[984:1198267] client: relay established
2015-12-14 21:23:12.502 ThaliTest[984:1198267] client: new accepted socket: 0x15bb1950
,2015-12-14T20:23:12.518Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T20:23:12.860Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-14T20:23:13.388Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T20:23:13.388Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2015-12-14T20:23:13.389Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T20:23:13.389Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 21:23:13.390 ThaliTest[984:1198485] jxcore: disconnect
2015-12-14 21:23:13.391 ThaliTest[984:1198485] client session: disconnectFromPeer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:23:13.391 ThaliTest[984:1198485] client session: disconnect
2015-12-14 21:23:13.391 ThaliTest[984:1198485] client session: stateChange:2->0 Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:23:13.400 ThaliTest[984:1198485] jxcore: disconnect: success
2015-12-14T20:23:13.401Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1173.b8TW0A==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
2015-12-14T20:23:13.405Z SendDataConnector.js: CLIENT Stop now
2015-12-14T20:23:13.405Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 21:23:28.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:23:28.787 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:23:28.787 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:23:28.789 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
serverPort is 8876
,2015-12-14 21:23:31.060 ThaliTest[984:1198485] jxcore: startBroadcasting
2015-12-14 21:23:31.060 ThaliTest[984:1198485] jxcore: startBroadcasting: failure
weAreDoneNow
,done, now sending data to server
,done, now sending data to server
,2015-12-14 21:23:58.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:23:58.790 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:23:58.790 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:23:58.801 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:24:28.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:24:28.779 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:24:28.780 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:24:28.781 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:24:58.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:24:58.792 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:24:58.797 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:24:58.797 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:25:28.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:25:58.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:25:58.788 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:25:58.789 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:25:58.789 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:26:28.735 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:26:28.787 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:26:28.787 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:26:28.788 ThaliTest[984:1198267] client: f,ound peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:26:58.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:26:58.805 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:26:58.806 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:26:58.806 ThaliTest[984:1198267] client: ,found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:27:25.720 ThaliTest[984:1198267] client: lost peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:27:25.720 ThaliTest[984:1198267] client session: onPeerLost: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:27:28.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:27:28.780 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:27:28.787 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:27:29.279 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:27:58.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:27:58.788 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:27:58.788 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:27:59.119 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:28:28.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:28:58.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:28:58.786 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:28:58.787 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:28:58.790 ThaliTest[984:1198267] client: f,ound peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:29:28.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:29:58.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:29:58.786 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:29:58.787 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:29:58.789 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:30:28.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:30:58.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:30:58.792 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:30:58.792 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:30:58.793 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:31:28.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:31:58.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:31:58.781 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:31:58.786 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:31:58.787 ThaliTest[984:1198267] client: ,found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:32:28.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:32:28.788 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:32:28.788 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:32:28.791 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:32:58.735 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:32:58.788 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:32:58.792 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:32:58.792 ThaliTest[984:1198267] client: f,ound peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:33:28.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:33:28.790 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:33:28.791 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:33:28.791 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:33:58.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:33:58.790 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:33:58.790 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:33:58.793 ThaliTest[984:1198267] client: f,ound peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:34:28.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:34:28.790 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:34:28.791 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:34:28.793 ThaliTest[984:1198267] client: f,ound peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:34:58.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:34:58.789 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:34:58.790 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:34:58.800 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:35:23.702 ThaliTest[984:1198267] client: lost peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:35:23.702 ThaliTest[984:1198267] client session: onPeerLost: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:35:25.950 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:35:28.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:35:28.792 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:35:28.793 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:35:28.793 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:35:58.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:36:28.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:36:28.792 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:36:28.793 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:36:28.794 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:36:58.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:36:58.796 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:36:58.796 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:36:58.797 ThaliTest[984:1198267] client: ,found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:37:28.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:37:58.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:37:58.791 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:37:58.792 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:37:58.795 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:38:28.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:38:58.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:38:58.786 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:38:58.787 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:38:58.787 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:39:28.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:39:28.783 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:39:28.784 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:39:28.785 ThaliTest[984:1198267] client: ,found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:39:58.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:39:58.791 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:39:58.791 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:39:58.802 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,timeout now
,2015-12-14 21:40:28.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:40:28.789 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:40:28.789 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:40:28.791 ThaliTest[984:1198267] client: f,ound peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:40:58.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:40:58.789 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:40:58.789 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:40:58.790 ThaliTest[984:1198267] client: ,found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:41:28.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:41:58.735 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:41:58.789 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:41:58.790 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:41:59.077 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:42:28.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:42:58.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:42:58.786 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:42:58.787 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:42:58.797 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:43:28.736 ThaliTest[984:1198267] multipeer session: restart
,2015-12-14 21:43:28.791 ThaliTest[984:1198267] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:43:28.792 ThaliTest[984:1198267] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:43:28.795 ThaliTest[984:1198267] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==

```
