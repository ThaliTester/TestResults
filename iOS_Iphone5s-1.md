#### Test 50650278f6345ef_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278f6345ef/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/A8FC23C6-0451-43FE-B183-E4A3B67CDD8F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A8FC23C6-0451-43FE-B183-E4A3B67CDD8F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278f6345ef/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278f6345ef/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/309E61A6-9BA1-4725-AEF7-8568E7D68511/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54175"
,(lldb)     command script import "/tmp/A8FC23C6-0451-43FE-B183-E4A3B67CDD8F/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-11 13:12:27.221 ThaliTest[779:710438] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3D1054C0-152A-4D03-9316-B38B8EDF61CC/Library/Cookies/Cookies.binarycookies
,2015-12-11 13:12:27.615 ThaliTest[779:710438] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-11 13:12:27.617 ThaliTest[779:710438] Multi-tasking -> Device: YES, App: YES
,2015-12-11 13:12:27.626 ThaliTest[779:710438] Unlimited access to network resources
,2015-12-11 13:12:27.641 ThaliTest[779:710438] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-11 13:12:36.965 ThaliTest[779:710438] Resetting plugins due to page load.
,2015-12-11 13:12:40.803 ThaliTest[779:710438] Finished load of: file:///var/mobile/Containers/Bundle/Application/309E61A6-9BA1-4725-AEF7-8568E7D68511/ThaliTest.app/www/index.html
,2015-12-11 13:12:41.013 ThaliTest[779:710438] JXcore Cordova plugin initializing
,2015-12-11 13:12:41.014 ThaliTest[779:710642] JXcore instance initializing
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
,2015-12-11 13:12:42.326 ThaliTest[779:710438] THREAD WARNING: ['JXcore'] took '90.171143' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-11 13:17:51.784 ThaliTest[779:710642] jxcore: startBroadcasting
,2015-12-11 13:17:51.805 ThaliTest[779:710642] server: starting Apple-Iphone5s-1_PT1055.12M0ng==
2015-12-11 13:17:51.807 ThaliTest[779:710642] multipeer session: start timer: 0x156e61a0
2015-12-11 13:17:51.808 ThaliTest[779:710642] THEMultipeerSession ini,tialized peer Apple-Iphone5s-1_PT1055
2015-12-11 13:17:51.808 ThaliTest[779:710642] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-11 13:17:52.495 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.k/CT+g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6904.k/CT+g==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5-1_PT6904.k/CT+g==, peerAvailable: true
,weAreDoneNow
done, now sending data to server
,teardown
,testFindPeers stopped
2015-12-11 13:17:52.733 ThaliTest[779:710642] jxcore: stopBroadcasting
,2015-12-11 13:17:52.733 ThaliTest[779:710642] THEMultipeerSession stopping peer
,2015-12-11 13:17:52.734 ThaliTest[779:710642] multipeer session: stop timer
,2015-12-11 13:17:52.735 ThaliTest[779:710642] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 56854
,2015-12-11 13:17:52.831 ThaliTest[779:710642] jxcore: startBroadcasting
,2015-12-11 13:17:52.834 ThaliTest[779:710642] server: starting Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:17:52.836 ThaliTest[779:710642] multipeer session: start timer: 0x156ede20
2015-12-11 13:17:52.848 ThaliTest[779:710642] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT1055
2015-12-11 13:17:52.849 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.k/CT+g==
2015-12-11 13:17:52.849 ThaliTest[779:710642] jxcore: startBroadcasting: success
,StartBroadcasting started ok
null
2015-12-11T12:17:52.853Z SendDataTCPServer.js: TCP/IP server is bound to port: 56854
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6904.k/CT+g==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone5-1_PT6904.k/CT+g==
,2015-12-11T12:17:52.864Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6904.k/CT+g==
,2015-12-11T12:17:52.864Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6904.k/CT+g==
,2015-12-11T12:17:52.865Z SendDataConnector.js: do connect now
,2015-12-11 13:17:52.865 ThaliTest[779:710642] jxcore: connect Apple-Iphone5-1_PT6904.k/CT+g==
2015-12-11 13:17:52.866 ThaliTest[779:710642] client session: connect
2015-12-11 13:17:52.866 ThaliTest[779:710642] client session: stateChange:0->1 Apple-Iphone5-1_PT6904.k/CT+g==
,2015-12-11 13:17:55.141 ThaliTest[779:710438] client: lost peer: Apple-Iphone5-1_PT6904.k/CT+g==
2015-12-11 13:17:55.141 ThaliTest[779:710438] client session: onPeerLost: Apple-Iphone5-1_PT6904.k/CT+g==
2015-12-11 13:17:55.142 ThaliTest[779:710438] clien,t session: onLinkFailure: Apple-Iphone5-1_PT6904.k/CT+g==
2015-12-11 13:17:55.142 ThaliTest[779:710438] client session: disconnect
2015-12-11 13:17:55.142 ThaliTest[779:710438] client session: stateChange:1->0 Apple-Iphone5-1_PT6904.k/CT+g==
2015-12-11 ,13:17:55.149 ThaliTest[779:710438] client session: fireConnectCallback: Apple-Iphone5-1_PT6904.k/CT+g==
2015-12-11 13:17:55.149 ThaliTest[779:710438] jxcore: connect: fail: Peer disconnected
2015-12-11T12:17:55.154Z SendDataConnector.js: CLIENT connected, to 0, error: Peer disconnected
2015-12-11T12:17:55.154Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-11T12:17:55.155Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_P,T6904.k/CT+g==","peerName":"(null)","peerAvailable":false}]
,2015-12-11 13:17:55.183 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7734.oRkpZA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-11 13:17:55.248 ThaliTest[779:710438] multipeer session: reset timer
,2015-12-11 13:17:55.249 ThaliTest[779:710438] multipeer session: stop timer
,2015-12-11 13:17:55.249 ThaliTest[779:710438] multipeer session: start timer: 0x156ede20
,2015-12-11 13:17:55.250 ThaliTest[779:710438] server session: connect
,2015-12-11 13:17:55.250 ThaliTest[779:710438] server session: stateChange:0->1 Apple-Iphone5-1_PT6904
,2015-12-11 13:17:55.265 ThaliTest[779:710438] server: accepting invitation Apple-Iphone5-1_PT6904
,2015-12-11 13:17:55.681 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8639.AH2xbQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 13:17:55.707 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6904.Jd0UjA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 13:17:57.884 ThaliTest[779:711213] server session: connected
2015-12-11 13:17:57.884 ThaliTest[779:711213] server session: stateChange:1->2 Apple-Iphone5-1_PT6904
,2015-12-11 13:17:57.934 ThaliTest[779:710438] server relay: connected (to port: 56854)
,2015-12-11T12:17:57.945Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T12:17:58.474Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-11T12:17:58.494Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-11T12:17:58.515Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-11T12:17:58.538Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-11T12:17:58.558Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-11T12:17:58.573Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 13:17:58.617 ThaliTest[779:711213] server session: not connected Apple-Iphone5-1_PT6904
,2015-12-11T12:18:00.164Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6904.k/CT+g==
,2015-12-11T12:18:00.165Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6904.k/CT+g==
,2015-12-11 13:18:05.174 ThaliTest[779:710642] jxcore: disconnect
2015-12-11 13:18:05.174 ThaliTest[779:710642] jxcore: disconnect: fail
2015-12-11T12:18:05.175Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6904.k/CT+g==,
2015-12-11T12:18:05.175Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT6904.k/CT+g== with availability status: true
2015-12-11T12:18:05.176Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6904.k/CT+g==
,2015-12-11T12:18:05.176Z SendDataConnector.js: do connect now
,2015-12-11 13:18:05.177 ThaliTest[779:710642] jxcore: connect Apple-Iphone5-1_PT6904.k/CT+g==
2015-12-11 13:18:05.179 ThaliTest[779:710642] client: connect: unreachable Apple-Iphone5-1_PT6904.k/CT+g==
2015-12-11 13:18:05.179 ThaliTest[779:710642] jxcore:, connect: fail: Peer unreachable
2015-12-11T12:18:05.180Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-11T12:18:05.180Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-11T12:18:05.180Z SendDataConne,ctor.js: tryAgain afer: 5000 ms.
,2015-12-11T12:18:10.181Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6904.k/CT+g==
,2015-12-11T12:18:10.182Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6904.k/CT+g==
,appEnteredForeground wasn't registered
,2015-12-11 13:18:15.189 ThaliTest[779:710642] jxcore: disconnect
2015-12-11 13:18:15.190 ThaliTest[779:710642] jxcore: disconnect: fail
2015-12-11T12:18:15.190Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6904.k/CT+g==,
2015-12-11T12:18:15.191Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT6904.k/CT+g== with availability status: true
2015-12-11T12:18:15.191Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6904.k/CT+g==
,2015-12-11T12:18:15.191Z SendDataConnector.js: do connect now
2015-12-11 13:18:15.192 ThaliTest[779:710642] jxcore: connect Apple-Iphone5-1_PT6904.k/CT+g==
,2015-12-11 13:18:15.193 ThaliTest[779:710642] client: connect: unreachable Apple-Iphone5-1_PT6904.k/CT+g==
,2015-12-11 13:18:15.193 ThaliTest[779:710642] jxcore: connect: fail: Peer unreachable
,2015-12-11T12:18:15.194Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-11T12:18:15.196Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-11T12:18:15.196Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T12:18:20.203Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6904.k/CT+g==
,2015-12-11T12:18:20.204Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6904.k/CT+g==
,2015-12-11 13:18:25.210 ThaliTest[779:710642] jxcore: disconnect
2015-12-11 13:18:25.210 ThaliTest[779:710642] jxcore: disconnect: fail
2015-12-11T12:18:25.211Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6904.k/CT+g==,
2015-12-11T12:18:25.211Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT6904.k/CT+g== with availability status: true
2015-12-11T12:18:25.212Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6904.k/CT+g==
,2015-12-11T12:18:25.212Z SendDataConnector.js: do connect now
2015-12-11 13:18:25.213 ThaliTest[779:710642] jxcore: connect Apple-Iphone5-1_PT6904.k/CT+g==
,2015-12-11 13:18:25.214 ThaliTest[779:710642] client: connect: unreachable Apple-Iphone5-1_PT6904.k/CT+g==
,2015-12-11 13:18:25.214 ThaliTest[779:710642] jxcore: connect: fail: Peer unreachable
,2015-12-11T12:18:25.215Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-11T12:18:25.216Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-11T12:18:25.217Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11 13:18:25.251 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:18:25.311 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:18:25.312 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:18:25.322 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11T12:18:30.227Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6904.k/CT+g==
,2015-12-11T12:18:30.228Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6904.k/CT+g==
,2015-12-11 13:18:34.636 ThaliTest[779:710438] multipeer session: reset timer
2015-12-11 13:18:34.637 ThaliTest[779:710438] multipeer session: stop timer
,2015-12-11 13:18:34.637 ThaliTest[779:710438] multipeer session: start timer: 0x156ede20
2015-12-11 13:18:34.639 ThaliTest[779:710438] server session: connect
2015-12-11 13:18:34.639 ThaliTest[779:710438] server session: stateChange:0->1 Apple-Iphone6-1_PT7734
,2015-12-11 13:18:34.649 ThaliTest[779:710438] server: accepting invitation Apple-Iphone6-1_PT7734
,2015-12-11 13:18:35.240 ThaliTest[779:710642] jxcore: disconnect
2015-12-11 13:18:35.242 ThaliTest[779:710642] jxcore: disconnect: fail
2015-12-11T12:18:35.246Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6904.k/CT+g==,
2015-12-11T12:18:35.246Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT6904.k/CT+g== with availability status: true
2015-12-11T12:18:35.247Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6904.k/CT+g==
,2015-12-11T12:18:35.247Z SendDataConnector.js: do connect now
,2015-12-11 13:18:35.248 ThaliTest[779:710642] jxcore: connect Apple-Iphone5-1_PT6904.k/CT+g==
,2015-12-11 13:18:35.249 ThaliTest[779:710642] client: connect: unreachable Apple-Iphone5-1_PT6904.k/CT+g==
2015-12-11 13:18:35.250 ThaliTest[779:710642] jxcore: connect: fail: Peer unreachable
2015-12-11T12:18:35.251Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-11T12:18:35.251Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2015-12-11T12:18:35.254Z SendDataConnector.js: CLIENT Stop now
,2015-12-11 13:18:35.256 ThaliTest[779:710642] jxcore: disconnect
2015-12-11 13:18:35.256 ThaliTest[779:710642] jxcore: disconnect: fail
2015-12-11T12:18:35.257Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6904.k/CT+g==,
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11T12:18:35.261Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11T12:18:35.261Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11T12:18:35.262Z SendDataConnector.js: do connect now
,2015-12-11 13:18:35.264 ThaliTest[779:710642] jxcore: connect Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:18:35.265 ThaliTest[779:710642] client session: connect
2015-12-11 13:18:35.265 ThaliTest[779:710642] client session: stateChange:0->1 Apple-Iphon,e6-1_PT7734.oRkpZA==
,2015-12-11 13:18:35.818 ThaliTest[779:710438] multipeer session: reset timer
,2015-12-11 13:18:35.818 ThaliTest[779:710438] multipeer session: stop timer
,2015-12-11 13:18:35.819 ThaliTest[779:710438] multipeer session: start timer: 0x156ede20
,2015-12-11 13:18:35.820 ThaliTest[779:710438] server session: connect
,2015-12-11 13:18:35.821 ThaliTest[779:710438] server session: stateChange:0->1 Apple-IpadAir2-1_PT8639
,2015-12-11 13:18:35.832 ThaliTest[779:710438] server: accepting invitation Apple-IpadAir2-1_PT8639
,2015-12-11 13:18:40.394 ThaliTest[779:711474] server session: connected
,2015-12-11 13:18:40.395 ThaliTest[779:711474] server session: stateChange:1->2 Apple-Iphone6-1_PT7734
,2015-12-11T12:18:40.411Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11 13:18:40.409 ThaliTest[779:710438] server relay: connected (to port: 56854)
,2015-12-11T12:18:40.845Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-11T12:18:40.860Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-11T12:18:40.875Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 13:18:40.913 ThaliTest[779:711475] server session: not connected Apple-Iphone6-1_PT7734
,2015-12-11 13:18:41.429 ThaliTest[779:711475] server session: connected
2015-12-11 13:18:41.429 ThaliTest[779:711475] server session: stateChange:1->2 Apple-IpadAir2-1_PT8639
,2015-12-11 13:18:41.445 ThaliTest[779:710438] server relay: connected (to port: 56854)
,2015-12-11T12:18:41.455Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T12:18:41.727Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-11T12:18:41.747Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-11T12:18:41.769Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-11T12:18:41.790Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-11T12:18:41.816Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-11T12:18:41.831Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 13:18:41.892 ThaliTest[779:711473] server session: not connected Apple-IpadAir2-1_PT8639
,appEnteringBackground wasn't registered
,2015-12-11 13:18:43.571 ThaliTest[779:711473] client session: connected
2015-12-11 13:18:43.571 ThaliTest[779:711473] client session: stateChange:1->2 Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:18:43.577 ThaliTest[779:711473] client session: fireConnectCallback: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:18:43.578 ThaliTest[779:711473] jxcore: connect: success
2015-12-11T12:18:43.580Z SendDataConnector.js: CLIENT connected to 56869, error: null
,2015-12-11T12:18:43.580Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 13:18:43.584 ThaliTest[779:710438] client: relay established
,2015-12-11 13:18:43.585 ThaliTest[779:710438] client: new accepted socket: 0x16bcfaf0
,2015-12-11T12:18:43.599Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T12:18:43.927Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-11T12:18:43.928Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-11T12:18:43.928Z SendDataConnector.js: CLIENT Stop now
2015-12-11T12:18:43.928Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 13:18:43.929 ThaliTest[779:710642] jxcore: disconnect
2015-12-11 13:18:43.930 ThaliTest[779:710642] client session: disconnectFromPeer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:18:43.930 ThaliTest[779:710642] client session: disconnect
2015-12-11 13:18:43.930 ThaliTest[779:710642] client session: stateChange:2->0 Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:18:43.934 ThaliTest[779:710642] jxcore: disconnect: success
2015-12-11T12:18:43.935Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7734.oRkpZA==
---- round done--------
startWithNextDevice
device[3]: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11T12:18:43.935Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11T12:18:43.935Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11T12:1,8:43.935Z SendDataConnector.js: do connect now
2015-12-11 13:18:43.936 ThaliTest[779:710642] jxcore: connect Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:18:43.936 ThaliTest[779:710642] client session: connect
2015-12-11 13:18:43.936 ThaliTest[779:710642] client session: stateChange:0->1 Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:18:46.507 ThaliTest[779:711507] client session: connected
,2015-12-11 13:18:46.507 ThaliTest[779:711507] client session: stateChange:1->2 Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:18:46.517 ThaliTest[779:711507] client session: fireConnectCallback: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:18:46.518 ThaliTest[779:711507] jxcore: connect: success
,2015-12-11T12:18:46.519Z SendDataConnector.js: CLIENT connected to 56873, error: null
2015-12-11T12:18:46.520Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 13:18:46.525 ThaliTest[779:710438] client: relay established
2015-12-11 13:18:46.526 ThaliTest[779:710438] client: new accepted socket: 0x16c0c9c0
,2015-12-11T12:18:46.537Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T12:18:46.996Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-11T12:18:47.009Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-11T12:18:47.009Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-11T12:18:47.010Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T12:18:47.010Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 13:18:47.010 ThaliTest[779:710642] jxcore: disconnect
2015-12-11 13:18:47.011 ThaliTest[779:710642] client session: disconnectFromPeer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:18:47.011 ThaliTest[779:710642] client session: disconnect
2015-12-11 13:18:47.011 ThaliTest[779:710642] client session: stateChange:2->0 Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:18:47.017 ThaliTest[779:710642] jxcore: disconnect: success
2015-12-11T12:18:47.017Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8639.AH2xbQ==
---- round done--------
startWithNextDevice
device[4]: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11T12:18:47.018Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11T12:18:47.018Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11T12:18:,47.018Z SendDataConnector.js: do connect now
2015-12-11 13:18:47.019 ThaliTest[779:710642] jxcore: connect Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:18:47.019 ThaliTest[779:710642] client session: connect
2015-12-11 13:18:47.019 ThaliTest[779:710642] client session: stateChange:0->1 Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:18:49.822 ThaliTest[779:711475] client session: connected
2015-12-11 13:18:49.824 ThaliTest[779:711475] client session: stateChange:1->2 Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:18:49.841 ThaliTest[779:711507] client session: fireConnectCallback: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:18:49.842 ThaliTest[779:711507] jxcore: connect: success
,2015-12-11T12:18:49.844Z SendDataConnector.js: CLIENT connected to 56876, error: null
,2015-12-11T12:18:49.845Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 13:18:49.849 ThaliTest[779:710438] client: relay established
,2015-12-11 13:18:49.850 ThaliTest[779:710438] client: new accepted socket: 0x16c0ec60
,2015-12-11T12:18:49.864Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T12:18:50.171Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-11T12:18:50.182Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-11T12:18:50.195Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-11T12:18:50.207Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-11T12:18:50.207Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-11T12:18:50.208Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T12:18:50.208Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 13:18:50.209 ThaliTest[779:710642] jxcore: disconnect
,2015-12-11 13:18:50.209 ThaliTest[779:710642] client session: disconnectFromPeer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:18:50.210 ThaliTest[779:710642] client session: disconnect
,2015-12-11 13:18:50.210 ThaliTest[779:710642] client session: stateChange:2->0 Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:18:50.279 ThaliTest[779:710642] jxcore: disconnect: success
,2015-12-11T12:18:50.280Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6904.Jd0UjA==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2015-12-11T12:18:50.283Z SendDataConnector.js: CLIENT Stop now
2015-12-11T12:18:50.284Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 13:19:05.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:19:05.878 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:19:05.879 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:19:05.881 ThaliTest[779:710438] client: fou,nd peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:19:35.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:19:35.886 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:19:35.886 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:19:35.887 ThaliTest[779:710438] client: foun,d peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:20:05.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:20:05.881 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:20:05.883 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:20:05.884 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:20:35.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:20:35.882 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:20:35.882 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:20:35.883 ThaliTest[779:710438] client: fou,nd peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:21:05.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:21:35.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:21:35.871 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:21:35.872 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:21:35.875 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:22:05.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:22:35.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:22:35.873 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:22:35.878 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:22:35.879 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:23:05.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:23:05.871 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:23:05.879 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:23:05.882 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:23:35.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:24:05.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:24:05.876 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:24:05.877 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:24:05.881 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:24:35.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:24:35.877 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:24:35.880 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:24:35.880 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:25:05.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:25:35.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:25:35.871 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:25:35.872 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:25:35.873 ThaliTest[779:710438] client: foun,d peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:26:05.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:26:35.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:26:35.870 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:26:35.876 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:26:35.879 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:27:05.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:27:05.880 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:27:05.881 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:27:05.881 ThaliTest[779:710438] client: fou,nd peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:27:35.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:27:35.876 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:27:35.877 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:27:35.877 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:28:05.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:28:05.876 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:28:05.878 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:28:05.883 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:28:35.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:28:35.874 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:28:35.875 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:28:35.875 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:29:05.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:29:05.873 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:29:05.873 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:29:05.884 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:29:35.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:29:35.872 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:29:35.873 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:29:35.873 ThaliTest[779:710438] client: fou,nd peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:30:05.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:30:05.873 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:30:05.873 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:30:05.874 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:30:35.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:30:35.876 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:30:35.877 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:30:35.879 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:31:05.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:31:05.869 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:31:05.873 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:31:05.874 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:31:35.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:32:05.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:32:05.877 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:32:05.877 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:32:05.879 ThaliTest[779:710438] client: foun,d peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:32:35.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:32:35.877 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:32:35.878 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:32:35.878 ThaliTest[779:710438] client: fou,nd peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:33:05.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:33:05.876 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:33:05.877 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:33:05.879 ThaliTest[779:710438] client: fou,nd peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:33:35.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:33:35.874 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:33:35.875 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:33:35.882 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:34:05.821 ThaliTest[779:710438] multipeer session: restart
,2015-12-11 13:34:06.527 ThaliTest[779:710438] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:34:06.527 ThaliTest[779:710438] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:34:06.528 ThaliTest[779:710438] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,teardown
,testSendData stopped
,2015-12-11 13:34:35.137 ThaliTest[779:710642] jxcore: stopBroadcasting
,2015-12-11 13:34:35.137 ThaliTest[779:710642] THEMultipeerSession stopping peer
,2015-12-11 13:34:35.138 ThaliTest[779:710642] multipeer session: stop timer
2015-12-11 13:34:35.139 ThaliTest[779:710642] server session: disconnect
2015-12-11 13:34:35.140 ThaliTest[779:710642] server session: stateChange:2->0 Apple-Iphone5-1_PT6904
,2015-12-11 13:34:35.266 ThaliTest[779:710642] server session: disconnect
,2015-12-11 13:34:35.271 ThaliTest[779:710642] server session: stateChange:2->0 Apple-Iphone6-1_PT7734
,2015-12-11 13:34:35.276 ThaliTest[779:710642] server session: disconnect
2015-12-11 13:34:35.276 ThaliTest[779:710642] server session: stateChange:2->0 Apple-IpadAir2-1_PT8639
,2015-12-11 13:34:35.286 ThaliTest[779:710642] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-11T12:34:35.304Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-11T12:34:35.306Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-11T12:34:35.307Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-11T12:34:35.308Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
