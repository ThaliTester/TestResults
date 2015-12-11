#### Test 50650278f6345ef_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278f6345ef/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/A4B7DEFB-AD26-4B73-8574-C565BC0C66AC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A4B7DEFB-AD26-4B73-8574-C565BC0C66AC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278f6345ef/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278f6345ef/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9A0279E9-EAB7-4D2E-870D-812489E887F5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54164"
,(lldb)     command script import "/tmp/A4B7DEFB-AD26-4B73-8574-C565BC0C66AC/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-11 13:12:24.513 ThaliTest[774:710604] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B976BEBC-509C-4816-91F5-9D76F1FE796C/Library/Cookies/Cookies.binarycookies
,2015-12-11 13:12:24.879 ThaliTest[774:710604] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-11 13:12:24.880 ThaliTest[774:710604] Multi-tasking -> Device: YES, App: YES
,2015-12-11 13:12:24.889 ThaliTest[774:710604] Unlimited access to network resources
,2015-12-11 13:12:24.900 ThaliTest[774:710604] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-11 13:12:33.620 ThaliTest[774:710604] Resetting plugins due to page load.
,2015-12-11 13:12:36.972 ThaliTest[774:710604] Finished load of: file:///var/mobile/Containers/Bundle/Application/9A0279E9-EAB7-4D2E-870D-812489E887F5/ThaliTest.app/www/index.html
,2015-12-11 13:12:37.161 ThaliTest[774:710604] JXcore Cordova plugin initializing
,2015-12-11 13:12:37.162 ThaliTest[774:710803] JXcore instance initializing
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
,2015-12-11 13:12:38.228 ThaliTest[774:710604] THREAD WARNING: ['JXcore'] took '79.403809' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-11 13:17:50.547 ThaliTest[774:710803] jxcore: startBroadcasting
,2015-12-11 13:17:50.565 ThaliTest[774:710803] server: starting Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:17:50.567 ThaliTest[774:710803] multipeer session: start timer: 0x183a0580
2015-12-11 13:17:50.568 ThaliTest[774:710803] THEMultipeerSession initialized peer Apple-Iphone6-1_PT7734
2015-12-11 13:17:50.569 ThaliTest[774:710803] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-11 13:17:51.770 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.QAAa6w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8639.QAAa6w==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-IpadAir2-1_PT8639.QAAa6w==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,teardown
,testFindPeers stopped
,2015-12-11 13:17:53.194 ThaliTest[774:710803] jxcore: stopBroadcasting
2015-12-11 13:17:53.194 ThaliTest[774:710803] THEMultipeerSession stopping peer
2015-12-11 13:17:53.194 ThaliTest[774:710803] multipeer session: stop timer
2015-12-11 13:17:53.195 Th,aliTest[774:710803] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 56670
,2015-12-11 13:17:53.262 ThaliTest[774:710803] jxcore: startBroadcasting
,2015-12-11 13:17:53.268 ThaliTest[774:710803] server: starting Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:17:53.269 ThaliTest[774:710803] multipeer session: start timer: 0x183a7930
2015-12-11 13:17:53.270 ThaliTest[774:710803] THEMultipeerSession init,ialized peer Apple-Iphone6-1_PT7734
2015-12-11 13:17:53.270 ThaliTest[774:710803] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
2015-12-11T12:17:53.276Z SendDataTCPServer.js: TCP/IP server is bound to port: 56670
,2015-12-11 13:17:54.235 ThaliTest[774:710604] client: found peer: Apple-Iphone6-1_PT7734.5CC0vg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7734.5CC0vg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone6-1_PT7734.5CC0vg==
2015-12-11T12:17:54.241Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7734.5CC0vg==
2015-12-11T12:17:54.242Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7734.5CC0vg==
20,15-12-11T12:17:54.242Z SendDataConnector.js: do connect now
,2015-12-11 13:17:54.243 ThaliTest[774:710803] jxcore: connect Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:17:54.244 ThaliTest[774:710803] client session: connect
,2015-12-11 13:17:54.245 ThaliTest[774:710803] client session: stateChange:0->1 Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:17:54.326 ThaliTest[774:710604] client: lost peer: Apple-Iphone6-1_PT7734.5CC0vg==
2015-12-11 13:17:54.326 ThaliTest[774:710604] client session: onPeerLost: Apple-Iphone6-1_PT7734.5CC0vg==
2015-12-11 13:17:54.327 ThaliTest[774:710604] clien,t session: onLinkFailure: Apple-Iphone6-1_PT7734.5CC0vg==
2015-12-11 13:17:54.327 ThaliTest[774:710604] client session: disconnect
2015-12-11 13:17:54.327 ThaliTest[774:710604] client session: stateChange:1->0 Apple-Iphone6-1_PT7734.5CC0vg==
2015-12-11 ,13:17:54.328 ThaliTest[774:710604] client session: fireConnectCallback: Apple-Iphone6-1_PT7734.5CC0vg==
2015-12-11 13:17:54.328 ThaliTest[774:710604] jxcore: connect: fail: Peer disconnected
2015-12-11 13:17:54.329 ThaliTest[774:710604] client: found pee,r: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11T12:17:54.330Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-11T12:17:54.331Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-11T12:17:54.331Z SendData,Connector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7734.5CC0vg==","peerName":"(null)","peerAvailable":false}]
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1055.SsV7MA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-11 13:17:55.190 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8639.AH2xbQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 13:17:55.589 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6904.Jd0UjA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-11 13:17:58.932 ThaliTest[774:710604] multipeer session: reset timer
2015-12-11 13:17:58.933 ThaliTest[774:710604] multipeer session: stop timer
,2015-12-11 13:17:58.933 ThaliTest[774:710604] multipeer session: start timer: 0x183a7930
2015-12-11 13:17:58.935 ThaliTest[774:710604] server session: connect
2015-12-11 13:17:58.935 ThaliTest[774:710604] server session: stateChange:0->1 Apple-Iphone5-1_PT6904
,2015-12-11 13:17:58.945 ThaliTest[774:710604] server: accepting invitation Apple-Iphone5-1_PT6904
,2015-12-11T12:17:59.338Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11T12:17:59.340Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:18:01.647 ThaliTest[774:711302] server session: connected
2015-12-11 13:18:01.648 ThaliTest[774:711302] server session: stateChange:1->2 Apple-Iphone5-1_PT6904
,2015-12-11 13:18:01.691 ThaliTest[774:710604] server relay: connected (to port: 56670)
,2015-12-11T12:18:01.699Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T12:18:02.195Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-11T12:18:02.208Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-11T12:18:02.226Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-11T12:18:02.476Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 13:18:02.565 ThaliTest[774:711293] server session: not connected Apple-Iphone5-1_PT6904
,2015-12-11 13:18:04.343 ThaliTest[774:710803] jxcore: disconnect
2015-12-11 13:18:04.344 ThaliTest[774:710803] jxcore: disconnect: fail
2015-12-11T12:18:04.345Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7734.5CC0vg==,
2015-12-11T12:18:04.345Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT7734.5CC0vg== with availability status: true
2015-12-11T12:18:04.345Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11T12:18:04.346Z SendDataConnector.js: do connect now
,2015-12-11 13:18:04.347 ThaliTest[774:710803] jxcore: connect Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:18:04.348 ThaliTest[774:710803] client: connect: unreachable Apple-Iphone6-1_PT7734.5CC0vg==
2015-12-11 13:18:04.348 ThaliTest[774:710803] jxcore: connect: fail: Peer unreachable
2015-12-11T12:18:04.349Z SendDataConnector.js: CLIENT connect,ed to 0, error: Peer unreachable
2015-12-11T12:18:04.349Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-11T12:18:04.349Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T12:18:09.352Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11T12:18:09.352Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:18:14.361 ThaliTest[774:710803] jxcore: disconnect
,2015-12-11 13:18:14.362 ThaliTest[774:710803] jxcore: disconnect: fail
2015-12-11T12:18:14.362Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7734.5CC0vg==
2015-12-11T12:18:14.363Z SendDataConnector.js: Connect (retry cou,nt 2) to peer Apple-Iphone6-1_PT7734.5CC0vg== with availability status: true
2015-12-11T12:18:14.363Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7734.5CC0vg==
2015-12-11T12:18:14.363Z SendDataConnector.js: do connect now
,2015-12-11 13:18:14.365 ThaliTest[774:710803] jxcore: connect Apple-Iphone6-1_PT7734.5CC0vg==
2015-12-11 13:18:14.365 ThaliTest[774:710803] client: connect: unreachable Apple-Iphone6-1_PT7734.5CC0vg==
2015-12-11 13:18:14.366 ThaliTest[774:710803] jxcore:, connect: fail: Peer unreachable
2015-12-11T12:18:14.366Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-11T12:18:14.366Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-11T12:18:14.367Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T12:18:19.369Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11T12:18:19.370Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:18:24.382 ThaliTest[774:710803] jxcore: disconnect
2015-12-11 13:18:24.382 ThaliTest[774:710803] jxcore: disconnect: fail
2015-12-11T12:18:24.383Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7734.5CC0vg==,
2015-12-11T12:18:24.383Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT7734.5CC0vg== with availability status: true
2015-12-11T12:18:24.383Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7734.5CC0vg==
2015-12-11T12:18:24.384Z SendDataConnector.js: do connect now
,2015-12-11 13:18:24.385 ThaliTest[774:710803] jxcore: connect Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:18:24.386 ThaliTest[774:710803] client: connect: unreachable Apple-Iphone6-1_PT7734.5CC0vg==
2015-12-11 13:18:24.386 ThaliTest[774:710803] jxcore: connect: fail: Peer unreachable
2015-12-11T12:18:24.387Z SendDataConnector.js: CLIENT connect,ed to 0, error: Peer unreachable
2015-12-11T12:18:24.387Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-11T12:18:24.387Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11 13:18:28.936 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:18:28.978 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:18:28.978 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:18:28.979 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11T12:18:29.397Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11T12:18:29.398Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:18:34.409 ThaliTest[774:710803] jxcore: disconnect
,2015-12-11 13:18:34.410 ThaliTest[774:710803] jxcore: disconnect: fail
2015-12-11T12:18:34.410Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7734.5CC0vg==
2015-12-11T12:18:34.411Z SendDataConnector.js: Connect (retry cou,nt 4) to peer Apple-Iphone6-1_PT7734.5CC0vg== with availability status: true
2015-12-11T12:18:34.411Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11T12:18:34.411Z SendDataConnector.js: do connect now
,2015-12-11 13:18:34.413 ThaliTest[774:710803] jxcore: connect Apple-Iphone6-1_PT7734.5CC0vg==
2015-12-11 13:18:34.414 ThaliTest[774:710803] client: connect: unreachable Apple-Iphone6-1_PT7734.5CC0vg==
2015-12-11 13:18:34.414 ThaliTest[774:710803] jxcore:, connect: fail: Peer unreachable
2015-12-11T12:18:34.414Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-11T12:18:34.415Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2015-12-11T12:18:34.417Z SendDataConnector.js: CLIENT Stop now
,2015-12-11 13:18:34.418 ThaliTest[774:710803] jxcore: disconnect
2015-12-11 13:18:34.419 ThaliTest[774:710803] jxcore: disconnect: fail
2015-12-11T12:18:34.419Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7734.5CC0vg==,
---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11T12:18:34.422Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11T12:18:34.423Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11T12:18:34.424Z SendDataConnector.js: do connect now
,2015-12-11 13:18:34.425 ThaliTest[774:710803] jxcore: connect Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:18:34.425 ThaliTest[774:710803] client session: connect
2015-12-11 13:18:34.426 ThaliTest[774:710803] client session: stateChange:0->1 Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:18:35.346 ThaliTest[774:710604] multipeer session: reset timer
2015-12-11 13:18:35.347 ThaliTest[774:710604] multipeer session: stop timer
2015-12-11 13:18:35.347 ThaliTest[774:710604] multipeer session: start timer: 0x183a7930
2015-12-11 ,13:18:35.347 ThaliTest[774:710604] server session: connect
2015-12-11 13:18:35.348 ThaliTest[774:710604] server session: stateChange:0->1 Apple-Iphone5s-1_PT1055
,2015-12-11 13:18:35.358 ThaliTest[774:710604] server: accepting invitation Apple-Iphone5s-1_PT1055
,2015-12-11 13:18:40.405 ThaliTest[774:711399] client session: connected
2015-12-11 13:18:40.405 ThaliTest[774:711399] client session: stateChange:1->2 Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:18:40.429 ThaliTest[774:711406] client session: fireConnectCallback: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:18:40.429 ThaliTest[774:711406] jxcore: connect: success
2015-12-11T12:18:40.431Z SendDataConnector.js: CLIENT connected to 56678, error: null
2015-12-11T12:18:40.431Z SendDataConnector.js: CLIENT starting client 
2015-12-11 13:18:40.435 ThaliTest[774:710604] client: relay established
2015-12-11 13:18:40.435 ThaliTest[774:710604] client: new accepted socket: 0x1843f230
,2015-12-11T12:18:40.450Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T12:18:40.880Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-11T12:18:40.894Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-11T12:18:40.907Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-11T12:18:40.907Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-11T12:18:40.908Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T12:18:40.908Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 13:18:40.910 ThaliTest[774:710803] jxcore: disconnect
2015-12-11 13:18:40.910 ThaliTest[774:710803] client session: disconnectFromPeer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:18:40.910 ThaliTest[774:710803] client session: disconnect
2015-12-11 13:18:40.910 ThaliTest[774:710803] client session: stateChange:2->0 Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:18:40.917 ThaliTest[774:710803] jxcore: disconnect: success
2015-12-11T12:18:40.917Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1055.SsV7MA==
---- round done--------
startWithNextDevice
device[3]: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11T12:18:40.918Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11T12:18:40.918Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11T12:18:40.918Z SendDataConnector.js: do connect now
2015-12-11 13:18:40.919 ThaliTest[774:710803] jxcore: connect Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:18:40.919 ThaliTest[774:710803] client session: connect
2015-12-11 13:18:40.919 ThaliTest[774:71,0803] client session: stateChange:0->1 Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:18:42.016 ThaliTest[774:710604] multipeer session: reset timer
2015-12-11 13:18:42.017 ThaliTest[774:710604] multipeer session: stop timer
2015-12-11 13:18:42.017 ThaliTest[774:710604] multipeer session: start timer: 0x183a7930
,2015-12-11 13:18:42.018 ThaliTest[774:710604] server session: connect
2015-12-11 13:18:42.018 ThaliTest[774:710604] server session: stateChange:0->1 Apple-IpadAir2-1_PT8639
,2015-12-11 13:18:42.027 ThaliTest[774:710604] server: accepting invitation Apple-IpadAir2-1_PT8639
,2015-12-11 13:18:43.419 ThaliTest[774:711408] client session: connected
2015-12-11 13:18:43.420 ThaliTest[774:711408] client session: stateChange:1->2 Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:18:43.424 ThaliTest[774:711408] client session: fireConn,ectCallback: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:18:43.424 ThaliTest[774:711408] jxcore: connect: success
2015-12-11T12:18:43.426Z SendDataConnector.js: CLIENT connected to 56681, error: null
,2015-12-11T12:18:43.426Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 13:18:43.432 ThaliTest[774:710604] client: relay established
2015-12-11 13:18:43.433 ThaliTest[774:710604] client: new accepted socket: 0x183bb6a0
,2015-12-11T12:18:43.445Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11 13:18:43.576 ThaliTest[774:711407] server session: connected
2015-12-11 13:18:43.576 ThaliTest[774:711407] server session: stateChange:1->2 Apple-Iphone5s-1_PT1055
,2015-12-11 13:18:43.598 ThaliTest[774:710604] server relay: connected (to port: 56670)
,2015-12-11T12:18:43.714Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T12:18:43.777Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-11T12:18:43.839Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-11T12:18:43.839Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2015-12-11T12:18:43.840Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T12:18:43.840Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 13:18:43.840 ThaliTest[774:710803] jxcore: disconnect
2015-12-11 13:18:43.841 ThaliTest[774:710803] client session: disconnectFromPeer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:18:43.841 ThaliTest[774:710803] client session: disconnect
,2015-12-11 13:18:43.842 ThaliTest[774:710803] client session: stateChange:2->0 Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:18:43.909 ThaliTest[774:710803] jxcore: disconnect: success
,2015-12-11T12:18:43.910Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8639.AH2xbQ==
,---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11T12:18:43.914Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11T12:18:43.916Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11T12:18:43.916Z SendDataConnector.js: do connect now
,2015-12-11 13:18:43.916 ThaliTest[774:710803] jxcore: connect Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:18:43.917 ThaliTest[774:710803] client session: connect
,2015-12-11 13:18:43.917 ThaliTest[774:710803] client session: stateChange:0->1 Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11T12:18:43.934Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 13:18:43.967 ThaliTest[774:711406] server session: not connected Apple-Iphone5s-1_PT1055
,2015-12-11 13:18:44.429 ThaliTest[774:711407] server session: connected
,2015-12-11 13:18:44.430 ThaliTest[774:711407] server session: stateChange:1->2 Apple-IpadAir2-1_PT8639
,2015-12-11 13:18:44.434 ThaliTest[774:710604] server relay: connected (to port: 56670)
,2015-12-11T12:18:44.441Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T12:18:44.676Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-11T12:18:44.693Z SendDataTCPServer.js: TCP/IP server has received 56656 bytes of data
,2015-12-11T12:18:44.711Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-11T12:18:44.726Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 13:18:44.758 ThaliTest[774:711406] server session: not connected Apple-IpadAir2-1_PT8639
,2015-12-11 13:18:46.539 ThaliTest[774:711408] client session: connected
2015-12-11 13:18:46.540 ThaliTest[774:711408] client session: stateChange:1->2 Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:18:46.555 ThaliTest[774:711406] client session: fireConnectCallback: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:18:46.556 ThaliTest[774:711406] jxcore: connect: success
2015-12-11T12:18:46.557Z SendDataConnector.js: CLIENT connected to 5,6686, error: null
2015-12-11T12:18:46.557Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 13:18:46.560 ThaliTest[774:710604] client: relay established
2015-12-11 13:18:46.561 ThaliTest[774:710604] client: new accepted socket: 0x183b9f10
,2015-12-11T12:18:46.573Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T12:18:46.838Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-11T12:18:46.864Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-11T12:18:46.913Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-11T12:18:46.926Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-11T12:18:46.926Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-11T12:18:46.926Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T12:18:46.926Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 13:18:46.927 ThaliTest[774:710803] jxcore: disconnect
2015-12-11 13:18:46.927 ThaliTest[774:710803] client session: disconnectFromPeer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:18:46.927 ThaliTest[774:710803] client session: disconnect
,2015-12-11 13:18:46.928 ThaliTest[774:710803] client session: stateChange:2->0 Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:18:46.991 ThaliTest[774:710803] jxcore: disconnect: success
,2015-12-11T12:18:46.992Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6904.Jd0UjA==
,---- round done--------
startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2015-12-11T12:18:46.996Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T12:18:46.996Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 13:19:12.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:19:12.063 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:19:12.064 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:19:12.070 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:19:42.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:20:12.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:20:12.055 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:20:12.055 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:20:12.056 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:20:42.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:21:12.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:21:12.057 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:21:12.058 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:21:12.058 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:21:42.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:21:42.054 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:21:42.058 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:21:42.059 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:22:12.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:22:42.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:22:42.053 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:22:42.060 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:22:42.060 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:23:12.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:23:12.054 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:23:12.054 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:23:12.059 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:23:42.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:23:42.059 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:23:42.060 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:23:42.060 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:24:12.018 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:24:42.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:24:42.052 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:24:42.058 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:24:42.059 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:25:12.018 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:25:12.056 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:25:12.057 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:25:12.060 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:25:42.018 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:25:42.053 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:25:42.059 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:25:42.059 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:26:12.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:26:12.054 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:26:12.062 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:26:12.062 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:26:42.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:26:42.055 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:26:42.055 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:26:42.057 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:27:12.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:27:42.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:27:42.053 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:27:42.054 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:27:42.059 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:28:12.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:28:12.056 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:28:12.056 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:28:12.057 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:28:42.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:29:12.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:29:12.053 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:29:12.053 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:29:12.058 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:29:42.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:29:42.054 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:29:42.056 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:29:42.057 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:30:12.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:30:12.056 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:30:12.056 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:30:12.057 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:30:42.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:30:42.057 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:30:42.057 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:30:42.059 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:31:12.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:31:12.057 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:31:12.058 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:31:12.060 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:31:42.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:32:12.018 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:32:12.053 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:32:12.059 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:32:12.059 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:32:42.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:32:42.054 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:32:42.057 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:32:42.058 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:33:12.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:33:42.019 ThaliTest[774:710604] multipeer session: restart
,2015-12-11 13:33:42.053 ThaliTest[774:710604] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:33:42.053 ThaliTest[774:710604] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:33:42.054 ThaliTest[774:710604] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:34:12.018 ThaliTest[774:710604] multipeer session: restart
,teardown
,testSendData stopped
,2015-12-11 13:34:35.098 ThaliTest[774:710803] jxcore: stopBroadcasting
,2015-12-11 13:34:35.099 ThaliTest[774:710803] THEMultipeerSession stopping peer
,2015-12-11 13:34:35.100 ThaliTest[774:710803] multipeer session: stop timer
2015-12-11 13:34:35.101 ThaliTest[774:710803] server session: disconnect
2015-12-11 13:34:35.101 ThaliTest[774:710803] server session: stateChange:2->0 Apple-Iphone5-1_PT6904
,2015-12-11 13:34:35.108 ThaliTest[774:710803] server session: disconnect
2015-12-11 13:34:35.108 ThaliTest[774:710803] server session: stateChange:2->0 Apple-Iphone5s-1_PT1055
2015-12-11 13:34:35.113 ThaliTest[774:710803] server session: disconnect
2015-12-11 13:34:35.114 ThaliTest[774:710803] server session: stateChange:2->0 Apple-IpadAir2-1_PT8639
,2015-12-11 13:34:35.124 ThaliTest[774:710803] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-11T12:34:35.146Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-11T12:34:35.148Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-11T12:34:35.150Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-11T12:34:35.150Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
