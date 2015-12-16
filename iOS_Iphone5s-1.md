#### Test 50650278b44f053_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278b44f053/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/76983424-3EB0-41A1-A378-2181474CD4D5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/76983424-3EB0-41A1-A378-2181474CD4D5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278b44f053/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278b44f053/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A3DB8886-D135-4F20-963D-EE4129B8959F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58803"
,(lldb)     command script import "/tmp/76983424-3EB0-41A1-A378-2181474CD4D5/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-16 18:41:23.523 ThaliTest[305:115607] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E2009ED5-4165-4D93-BDFB-D2B0AABC0CAA/Library/Cookies/Cookies.binarycookies
,2015-12-16 18:41:23.954 ThaliTest[305:115607] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 18:41:23.955 ThaliTest[305:115607] Multi-tasking -> Device: YES, App: YES
,2015-12-16 18:41:23.964 ThaliTest[305:115607] Unlimited access to network resources
,2015-12-16 18:41:23.978 ThaliTest[305:115607] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 18:41:33.593 ThaliTest[305:115607] Resetting plugins due to page load.
,2015-12-16 18:41:37.383 ThaliTest[305:115607] Finished load of: file:///var/mobile/Containers/Bundle/Application/A3DB8886-D135-4F20-963D-EE4129B8959F/ThaliTest.app/www/index.html
,2015-12-16 18:41:37.583 ThaliTest[305:115607] JXcore Cordova plugin initializing
,2015-12-16 18:41:37.585 ThaliTest[305:115830] JXcore instance initializing
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
,2015-12-16 18:41:38.907 ThaliTest[305:115607] THREAD WARNING: ['JXcore'] took '92.847900' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-16 18:46:35.622 ThaliTest[305:115830] jxcore: startBroadcasting
,2015-12-16 18:46:35.642 ThaliTest[305:115830] server: starting Apple-Iphone5s-1_PT6682.COlI2w==
2015-12-16 18:46:35.643 ThaliTest[305:115830] multipeer session: start timer: 0x18c77150
2015-12-16 18:46:35.644 ThaliTest[305:115830] THEMultipeerSession ini,tialized peer Apple-Iphone5s-1_PT6682
2015-12-16 18:46:35.644 ThaliTest[305:115830] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-16 18:46:36.175 ThaliTest[305:115607] client: found peer: Apple-Iphone5-1_PT6761.ad6Xvw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6761.ad6Xvw==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5-1_PT6761.ad6Xvw==, peerAvailable: true
weAreDoneNow
,done, now sending data to server
,2015-12-16 18:46:36.312 ThaliTest[305:115607] client: found peer: Apple-Iphone6-1_PT3143.XZF93A==
2015-12-16 18:46:36.312 ThaliTest[305:115607] client: found peer: Apple-IpadAir2-1_PT5378.xtukLA==
,teardown
,testFindPeers stopped
,2015-12-16 18:46:36.579 ThaliTest[305:115830] jxcore: stopBroadcasting
,2015-12-16 18:46:36.579 ThaliTest[305:115830] THEMultipeerSession stopping peer
2015-12-16 18:46:36.580 ThaliTest[305:115830] multipeer session: stop timer
,2015-12-16 18:46:36.586 ThaliTest[305:115830] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 50111
,2015-12-16 18:46:36.685 ThaliTest[305:115830] jxcore: startBroadcasting
,2015-12-16 18:46:36.691 ThaliTest[305:115830] server: starting Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16 18:46:36.694 ThaliTest[305:115830] multipeer session: start timer: 0x18c854e0
,2015-12-16 18:46:36.700 ThaliTest[305:115830] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT6682
,2015-12-16 18:46:36.701 ThaliTest[305:115830] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2015-12-16T17:46:36.707Z SendDataTCPServer.js: TCP/IP server is bound to port: 50111
,2015-12-16 18:46:37.700 ThaliTest[305:115607] client: found peer: Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:46:37.701 ThaliTest[305:115607] client: found peer: Apple-Iphone6-1_PT3143.XZF93A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir,2-1_PT5378.xtukLA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16T17:46:37.708Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:46:37.710Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16T17:46:37.711Z SendDataConnector.js: do connect now
,2015-12-16 18:46:37.713 ThaliTest[305:115830] jxcore: connect Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:46:37.718 ThaliTest[305:115830] client session: connect
,2015-12-16 18:46:37.719 ThaliTest[305:115830] client session: stateChange:0->1 Apple-IpadAir2-1_PT5378.xtukLA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3143.XZF93A==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-16 18:46:37.915 ThaliTest[305:115607] client: lost peer: Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:46:37.915 ThaliTest[305:115607] client session: onPeerLost: Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:46:37.916 ThaliTest[305:115607] cli,ent session: onLinkFailure: Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:46:37.916 ThaliTest[305:115607] client session: disconnect
2015-12-16 18:46:37.916 ThaliTest[305:115607] client session: stateChange:1->0 Apple-IpadAir2-1_PT5378.xtukLA==
2015-12,-16 18:46:37.917 ThaliTest[305:115607] client session: fireConnectCallback: Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:46:37.917 ThaliTest[305:115607] jxcore: connect: fail: Peer disconnected
2015-12-16T17:46:37.919Z SendDataConnector.js: CLIENT conn,ected to 0, error: Peer disconnected
2015-12-16T17:46:37.919Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-16T17:46:37.920Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAi,r2-1_PT5378.xtukLA==","peerName":"(null)","peerAvailable":false}]
,2015-12-16 18:46:37.948 ThaliTest[305:115607] client: lost peer: Apple-Iphone6-1_PT3143.XZF93A==
2015-12-16 18:46:37.948 ThaliTest[305:115607] client session: onPeerLost: Apple-Iphone6-1_PT3143.XZF93A==
2015-12-16 18:46:37.950 ThaliTest[305:115607] clien,t: found peer: Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:46:37.951 ThaliTest[305:115607] client: found peer: Apple-Iphone6-1_PT3143.YUb0wA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3143.XZF93A==","peerName":"(null)","peerAvailab,le":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6761.1E6mhw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone6-1_PT3143.YUb0wA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-16 18:46:38.325 ThaliTest[305:115607] client: found peer: Apple-IpadAir2-1_PT5378.J91vGA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5378.J91vGA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-16T17:46:42.930Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:46:42.931Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:46:47.944 ThaliTest[305:115830] jxcore: disconnect
2015-12-16 18:46:47.945 ThaliTest[305:115830] jxcore: disconnect: fail
2015-12-16T17:46:47.945Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5378.xtukLA==,
2015-12-16T17:46:47.946Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT5378.xtukLA== with availability status: true
,2015-12-16T17:46:47.946Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16T17:46:47.947Z SendDataConnector.js: do connect now
,2015-12-16 18:46:47.948 ThaliTest[305:115830] jxcore: connect Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:46:47.949 ThaliTest[305:115830] client: connect: unreachable Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:46:47.949 ThaliTest[305:115830] jxcore: connect: fail: Peer unreachable
2015-12-16T17:46:47.950Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T17:46:47.951Z SendDataConnector.js: CLIENT Can not Connect: Pee,r unreachable
2015-12-16T17:46:47.951Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T17:46:52.954Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:46:52.955Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:46:57.957 ThaliTest[305:115830] jxcore: disconnect
2015-12-16 18:46:57.958 ThaliTest[305:115830] jxcore: disconnect: fail
2015-12-16T17:46:57.958Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5378.xtukLA==,
2015-12-16T17:46:57.959Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT5378.xtukLA== with availability status: true
2015-12-16T17:46:57.959Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5378.xtukLA==
20,15-12-16T17:46:57.959Z SendDataConnector.js: do connect now
,2015-12-16 18:46:57.960 ThaliTest[305:115830] jxcore: connect Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:46:57.961 ThaliTest[305:115830] client: connect: unreachable Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:46:57.961 ThaliTest[305:115830] jxcore: connect: fail: Peer unreachable
,2015-12-16T17:46:57.963Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-16T17:46:57.964Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T17:46:57.964Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T17:47:02.969Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:47:02.970Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:47:06.701 ThaliTest[305:115607] multipeer session: restart
,2015-12-16 18:47:07.979 ThaliTest[305:115830] jxcore: disconnect
2015-12-16 18:47:07.980 ThaliTest[305:115830] jxcore: disconnect: fail
2015-12-16T17:47:07.980Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5378.xtukLA==,
2015-12-16T17:47:07.981Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT5378.xtukLA== with availability status: true
2015-12-16T17:47:07.981Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:47:07.981Z SendDataConnector.js: do connect now
2015-12-16 18:47:07.982 ThaliTest[305:115830] jxcore: connect Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:47:07.983 ThaliTest[305:115830] client: connect: unreachable Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:47:07.984 ThaliTest[305:115830] jxcore: connect: fail: Peer unreachable
,2015-12-16T17:47:07.985Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T17:47:07.986Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T17:47:07.986Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T17:47:12.992Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:47:12.992Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:47:17.998 ThaliTest[305:115830] jxcore: disconnect
2015-12-16 18:47:17.999 ThaliTest[305:115830] jxcore: disconnect: fail
2015-12-16T17:47:17.999Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5378.xtukLA==,
2015-12-16T17:47:18.000Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT5378.xtukLA== with availability status: true
2015-12-16T17:47:18.000Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:47:18.001Z SendDataConnector.js: do connect now
2015-12-16 18:47:18.001 ThaliTest[305:115830] jxcore: connect Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:47:18.002 ThaliTest[305:115830] client: connect: unreachable Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:47:18.003 ThaliTest[305:115830] jxcore: connect: fail: Peer unreachable
,2015-12-16T17:47:18.004Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T17:47:18.005Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2015-12-16T17:47:18.007Z SendDataConnector.js: CLIENT Stop now
,2015-12-16 18:47:18.009 ThaliTest[305:115830] jxcore: disconnect
2015-12-16 18:47:18.009 ThaliTest[305:115830] jxcore: disconnect: fail
,2015-12-16T17:47:18.017Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5378.xtukLA==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16T17:47:18.022Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16T17:47:18.022Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16T17:47:18.023Z SendDataConnector.js: do connect now
,2015-12-16 18:47:18.024 ThaliTest[305:115830] jxcore: connect Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:47:18.025 ThaliTest[305:115830] client session: connect
2015-12-16 18:47:18.025 ThaliTest[305:115830] client session: stateChange:0->1 Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:47:18.038 ThaliTest[305:115607] client: lost peer: Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:47:18.038 ThaliTest[305:115607] client session: onPeerLost: Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:47:18.039 ThaliTest[305:115607] clien,t session: onLinkFailure: Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:47:18.039 ThaliTest[305:115607] client session: disconnect
2015-12-16 18:47:18.039 ThaliTest[305:115607] client session: stateChange:1->0 Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 ,18:47:18.040 ThaliTest[305:115607] client session: fireConnectCallback: Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:47:18.040 ThaliTest[305:115607] jxcore: connect: fail: Peer disconnected
2015-12-16T17:47:18.042Z SendDataConnector.js: CLIENT connected, to 0, error: Peer disconnected
2015-12-16T17:47:18.042Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-16T17:47:18.042Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_P,T6761.1E6mhw==","peerName":"(null)","peerAvailable":false}]
,2015-12-16 18:47:18.277 ThaliTest[305:115607] multipeer session: reset timer
2015-12-16 18:47:18.277 ThaliTest[305:115607] multipeer session: stop timer
2015-12-16 18:47:18.277 ThaliTest[305:115607] multipeer session: start timer: 0x18c854e0
2015-12-16 ,18:47:18.278 ThaliTest[305:115607] server session: connect
2015-12-16 18:47:18.278 ThaliTest[305:115607] server session: stateChange:0->1 Apple-IpadAir2-1_PT5378
,2015-12-16 18:47:18.289 ThaliTest[305:115607] server: accepting invitation Apple-IpadAir2-1_PT5378
,2015-12-16 18:47:21.087 ThaliTest[305:116395] server session: connected
2015-12-16 18:47:21.087 ThaliTest[305:116395] server session: stateChange:1->2 Apple-IpadAir2-1_PT5378
,2015-12-16 18:47:21.124 ThaliTest[305:115607] server relay: connected (to port: 50111)
2015-12-16T17:47:21.125Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-16T17:47:21.393Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-16T17:47:21.409Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-16T17:47:21.427Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-16T17:47:21.445Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-16T17:47:21.466Z SendDataTCPServer.js: TCP/IP server has received 78414 bytes of data
,2015-12-16T17:47:21.482Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16 18:47:21.559 ThaliTest[305:116395] server session: not connected Apple-IpadAir2-1_PT5378
,2015-12-16T17:47:23.049Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16T17:47:23.050Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:47:28.061 ThaliTest[305:115830] jxcore: disconnect
2015-12-16 18:47:28.061 ThaliTest[305:115830] jxcore: disconnect: fail
2015-12-16T17:47:28.062Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6761.1E6mhw==,
2015-12-16T17:47:28.062Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT6761.1E6mhw== with availability status: true
2015-12-16T17:47:28.063Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16T17:47:28.063Z SendDataConnector.js: do connect now
2015-12-16 18:47:28.064 ThaliTest[305:115830] jxcore: connect Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:47:28.065 ThaliTest[305:115830] client: connect: unreachable Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:47:28.065 ThaliTest[305:115830] jxcore: connect: fail: Peer unreachable
,2015-12-16T17:47:28.067Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T17:47:28.068Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T17:47:28.068Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T17:47:33.073Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16T17:47:33.073Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:47:38.077 ThaliTest[305:115830] jxcore: disconnect
2015-12-16 18:47:38.077 ThaliTest[305:115830] jxcore: disconnect: fail
2015-12-16T17:47:38.078Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6761.1E6mhw==,
2015-12-16T17:47:38.078Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT6761.1E6mhw== with availability status: true
2015-12-16T17:47:38.079Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6761.1E6mhw==
2015-,12-16T17:47:38.079Z SendDataConnector.js: do connect now
,2015-12-16 18:47:38.080 ThaliTest[305:115830] jxcore: connect Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:47:38.081 ThaliTest[305:115830] client: connect: unreachable Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:47:38.081 ThaliTest[305:115830] jxcore:, connect: fail: Peer unreachable
2015-12-16T17:47:38.082Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T17:47:38.082Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T17:47:38.083Z SendDataConne,ctor.js: tryAgain afer: 5000 ms.
,2015-12-16T17:47:43.084Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16T17:47:43.085Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:47:45.128 ThaliTest[305:115607] multipeer session: reset timer
2015-12-16 18:47:45.129 ThaliTest[305:115607] multipeer session: stop timer
2015-12-16 18:47:45.129 ThaliTest[305:115607] multipeer session: start timer: 0x18c854e0
,2015-12-16 18:47:45.131 ThaliTest[305:115607] server session: connect
,2015-12-16 18:47:45.133 ThaliTest[305:115607] server session: stateChange:0->1 Apple-Iphone5-1_PT6761
,2015-12-16 18:47:45.144 ThaliTest[305:115607] server: accepting invitation Apple-Iphone5-1_PT6761
,2015-12-16 18:47:48.093 ThaliTest[305:115830] jxcore: disconnect
2015-12-16 18:47:48.094 ThaliTest[305:115830] jxcore: disconnect: fail
2015-12-16T17:47:48.094Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6761.1E6mhw==,
2015-12-16T17:47:48.095Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT6761.1E6mhw== with availability status: true
2015-12-16T17:47:48.095Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16T17:47:48.095Z SendDataConnector.js: do connect now
2015-12-16 18:47:48.096 ThaliTest[305:115830] jxcore: connect Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:47:48.097 ThaliTest[305:115830] client: connect: unreachable Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:47:48.098 ThaliTest[305:115830] jxcore: connect: fail: Peer unreachable
,2015-12-16T17:47:48.100Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-16T17:47:48.101Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-16T17:47:48.102Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16 18:47:48.155 ThaliTest[305:116548] server session: connected
,2015-12-16 18:47:48.156 ThaliTest[305:116548] server session: stateChange:1->2 Apple-Iphone5-1_PT6761
,2015-12-16 18:47:48.175 ThaliTest[305:115607] server relay: connected (to port: 50111)
,2015-12-16T17:47:48.187Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-16T17:47:48.749Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-16T17:47:48.768Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-16T17:47:48.788Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-16T17:47:48.805Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-16T17:47:48.820Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16 18:47:49.187 ThaliTest[305:116548] server session: not connected Apple-Iphone5-1_PT6761
,2015-12-16T17:47:53.106Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16T17:47:53.107Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:47:58.114 ThaliTest[305:115830] jxcore: disconnect
2015-12-16 18:47:58.114 ThaliTest[305:115830] jxcore: disconnect: fail
2015-12-16T17:47:58.115Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6761.1E6mhw==,
2015-12-16T17:47:58.115Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT6761.1E6mhw== with availability status: true
2015-12-16T17:47:58.116Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16T17:47:58.116Z SendDataConnector.js: do connect now
2015-12-16 18:47:58.117 ThaliTest[305:115830] jxcore: connect Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:47:58.118 ThaliTest[305:115830] client: connect: unreachable Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:47:58.119 ThaliTest[305:115830] jxcore: connect: fail: Peer unreachable
,2015-12-16T17:47:58.120Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T17:47:58.120Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
2015-12-16T17:47:58.121Z SendDataConnector.js: CLIENT S,top now
2015-12-16 18:47:58.122 ThaliTest[305:115830] jxcore: disconnect
2015-12-16 18:47:58.123 ThaliTest[305:115830] jxcore: disconnect: fail
2015-12-16T17:47:58.123Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6761.,1E6mhw==
---- round done--------
startWithNextDevice
,device[3]: Apple-Iphone6-1_PT3143.YUb0wA==
2015-12-16T17:47:58.126Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16T17:47:58.126Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16T17:47:58.127Z SendDataConnector.js: do connect now
,2015-12-16 18:47:58.129 ThaliTest[305:115830] jxcore: connect Apple-Iphone6-1_PT3143.YUb0wA==
2015-12-16 18:47:58.129 ThaliTest[305:115830] client session: connect
2015-12-16 18:47:58.130 ThaliTest[305:115830] client session: stateChange:0->1 Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:47:58.144 ThaliTest[305:115607] client: lost peer: Apple-Iphone6-1_PT3143.YUb0wA==
2015-12-16 18:47:58.144 ThaliTest[305:115607] client session: onPeerLost: Apple-Iphone6-1_PT3143.YUb0wA==
2015-12-16 18:47:58.145 ThaliTest[305:115607] clien,t session: onLinkFailure: Apple-Iphone6-1_PT3143.YUb0wA==
2015-12-16 18:47:58.145 ThaliTest[305:115607] client session: disconnect
2015-12-16 18:47:58.145 ThaliTest[305:115607] client session: stateChange:1->0 Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:47:58.200 ThaliTest[305:115607] client session: fireConnectCallback: Apple-Iphone6-1_PT3143.YUb0wA==
2015-12-16 18:47:58.200 ThaliTest[305:115607] jxcore: connect: fail: Peer disconnected
2015-12-16T17:47:58.201Z SendDataConnector.js: CLIEN,T connected to 0, error: Peer disconnected
2015-12-16T17:47:58.202Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-16T17:47:58.202Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3143.YUb0wA==","peerName":"(null)","peerAvailable":false}]
,2015-12-16T17:48:03.205Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16T17:48:03.205Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:48:08.218 ThaliTest[305:115830] jxcore: disconnect
2015-12-16 18:48:08.218 ThaliTest[305:115830] jxcore: disconnect: fail
2015-12-16T17:48:08.219Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3143.YUb0wA==,
2015-12-16T17:48:08.219Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT3143.YUb0wA== with availability status: true
2015-12-16T17:48:08.220Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3143.YUb0wA==
2015-,12-16T17:48:08.220Z SendDataConnector.js: do connect now
,2015-12-16 18:48:08.221 ThaliTest[305:115830] jxcore: connect Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:48:08.222 ThaliTest[305:115830] client: connect: unreachable Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:48:08.223 ThaliTest[305:115830] jxcore: connect: fail: Peer unreachable
,2015-12-16T17:48:08.224Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T17:48:08.225Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T17:48:08.225Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16 18:48:09.222 ThaliTest[305:115607] multipeer session: reset timer
2015-12-16 18:48:09.222 ThaliTest[305:115607] multipeer session: stop timer
2015-12-16 18:48:09.222 ThaliTest[305:115607] multipeer session: start timer: 0x18c854e0
2015-12-16 ,18:48:09.223 ThaliTest[305:115607] server session: connect
2015-12-16 18:48:09.223 ThaliTest[305:115607] server session: stateChange:0->1 Apple-Iphone6-1_PT3143
2015-12-16 18:48:09.233 ThaliTest[305:115607] server: accepting invitation Apple-Iphone6-1_PT3143
,2015-12-16 18:48:11.783 ThaliTest[305:116548] server session: connected
2015-12-16 18:48:11.784 ThaliTest[305:116548] server session: stateChange:1->2 Apple-Iphone6-1_PT3143
,2015-12-16 18:48:11.805 ThaliTest[305:115607] server relay: connected (to port: 50111)
,2015-12-16T17:48:11.813Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-16T17:48:12.065Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-16T17:48:12.079Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-16T17:48:12.099Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-16T17:48:12.116Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-16T17:48:12.132Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-16T17:48:12.146Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-16T17:48:12.161Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-16T17:48:12.261Z SendDataTCPServer.js: TCP/IP server has received 98610 bytes of data
,2015-12-16T17:48:12.278Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16 18:48:12.307 ThaliTest[305:116547] server session: not connected Apple-Iphone6-1_PT3143
,2015-12-16T17:48:13.228Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16T17:48:13.229Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:48:18.239 ThaliTest[305:115830] jxcore: disconnect
2015-12-16 18:48:18.239 ThaliTest[305:115830] jxcore: disconnect: fail
2015-12-16T17:48:18.240Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3143.YUb0wA==,
2015-12-16T17:48:18.240Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT3143.YUb0wA== with availability status: true
2015-12-16T17:48:18.241Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16T17:48:18.241Z SendDataConnector.js: do connect now
2015-12-16 18:48:18.242 ThaliTest[305:115830] jxcore: connect Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:48:18.243 ThaliTest[305:115830] client: connect: unreachable Apple-Iphone6-1_PT3143.YUb0wA==
2015-12-16 18:48:18.243 ThaliTest[305:115830] jxcore: connect: fail: Peer unreachable
,2015-12-16T17:48:18.244Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T17:48:18.245Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T17:48:18.245Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T17:48:23.251Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16T17:48:23.252Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:48:28.264 ThaliTest[305:115830] jxcore: disconnect
2015-12-16 18:48:28.265 ThaliTest[305:115830] jxcore: disconnect: fail
2015-12-16T17:48:28.265Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3143.YUb0wA==,
2015-12-16T17:48:28.266Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT3143.YUb0wA== with availability status: true
2015-12-16T17:48:28.266Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16T17:48:28.266Z SendDataConnector.js: do connect now
2015-12-16 18:48:28.267 ThaliTest[305:115830] jxcore: connect Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:48:28.268 ThaliTest[305:115830] client: connect: unreachable Apple-Iphone6-1_PT3143.YUb0wA==
2015-12-16 18:48:28.269 ThaliTest[305:115830] jxcore: connect: fail: Peer unreachable
2015-12-16T17:48:28.269Z SendDataConnector.js: CLIENT connect,ed to 0, error: Peer unreachable
2015-12-16T17:48:28.270Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T17:48:28.270Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T17:48:33.273Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16T17:48:33.274Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:48:38.281 ThaliTest[305:115830] jxcore: disconnect
2015-12-16 18:48:38.282 ThaliTest[305:115830] jxcore: disconnect: fail
2015-12-16T17:48:38.282Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3143.YUb0wA==,
2015-12-16T17:48:38.283Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT3143.YUb0wA== with availability status: true
2015-12-16T17:48:38.283Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16T17:48:38.283Z SendDataConnector.js: do connect now
2015-12-16 18:48:38.284 ThaliTest[305:115830] jxcore: connect Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:48:38.285 ThaliTest[305:115830] client: connect: unreachable Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:48:38.285 ThaliTest[305:115830] jxcore: connect: fail: Peer unreachable
,2015-12-16T17:48:38.287Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T17:48:38.287Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
2015-12-16T17:48:38.288Z SendDataConnector.js: CLIENT S,top now
2015-12-16 18:48:38.289 ThaliTest[305:115830] jxcore: disconnect
2015-12-16 18:48:38.289 ThaliTest[305:115830] jxcore: disconnect: fail
2015-12-16T17:48:38.290Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3143.,YUb0wA==
---- round done--------
startWithNextDevice
device[4]: Apple-IpadAir2-1_PT5378.J91vGA==
2015-12-16T17:48:38.291Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16T17:48:38.292Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5378.J91vGA==
2015-12-16T17:48:38.293Z SendDataConnector.js: do connect now
,2015-12-16 18:48:38.294 ThaliTest[305:115830] jxcore: connect Apple-IpadAir2-1_PT5378.J91vGA==
2015-12-16 18:48:38.295 ThaliTest[305:115830] client session: connect
2015-12-16 18:48:38.295 ThaliTest[305:115830] client session: stateChange:0->1 Apple-Ipad,Air2-1_PT5378.J91vGA==
,2015-12-16 18:48:38.311 ThaliTest[305:115607] client: lost peer: Apple-IpadAir2-1_PT5378.J91vGA==
2015-12-16 18:48:38.312 ThaliTest[305:115607] client session: onPeerLost: Apple-IpadAir2-1_PT5378.J91vGA==
2015-12-16 18:48:38.312 ThaliTest[305:115607] cli,ent session: onLinkFailure: Apple-IpadAir2-1_PT5378.J91vGA==
2015-12-16 18:48:38.312 ThaliTest[305:115607] client session: disconnect
2015-12-16 18:48:38.312 ThaliTest[305:115607] client session: stateChange:1->0 Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16 18:48:38.367 ThaliTest[305:115607] client session: fireConnectCallback: Apple-IpadAir2-1_PT5378.J91vGA==
2015-12-16 18:48:38.368 ThaliTest[305:115607] jxcore: connect: fail: Peer disconnected
2015-12-16T17:48:38.369Z SendDataConnector.js: CLIE,NT connected to 0, error: Peer disconnected
2015-12-16T17:48:38.369Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-16T17:48:38.369Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple,-IpadAir2-1_PT5378.J91vGA==","peerName":"(null)","peerAvailable":false}]
,2015-12-16 18:48:39.224 ThaliTest[305:115607] multipeer session: restart
,2015-12-16 18:48:39.276 ThaliTest[305:115607] client: found peer: Apple-Iphone6-1_PT3143.YUb0wA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3143.YUb0wA==","peerName":"(null)","peerAvailable":true}]
2015-12-16 18:48:39.281 ThaliTest[30,5:115607] client: found peer: Apple-IpadAir2-1_PT5378.J91vGA==
2015-12-16 18:48:39.282 ThaliTest[305:115607] client: found peer: Apple-Iphone5-1_PT6761.1E6mhw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5378.J91vGA==","peerName":"(nu,ll)","peerAvailable":true}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6761.1E6mhw==","peerName":"(null)","peerAvailable":true}]
,2015-12-16T17:48:43.381Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16T17:48:43.381Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16 18:48:48.383 ThaliTest[305:115830] jxcore: disconnect
2015-12-16 18:48:48.384 ThaliTest[305:115830] jxcore: disconnect: fail
2015-12-16T17:48:48.384Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5378.J91vGA==,
2015-12-16T17:48:48.385Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT5378.J91vGA== with availability status: true
2015-12-16T17:48:48.385Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5378.J91vGA==
20,15-12-16T17:48:48.385Z SendDataConnector.js: do connect now
,2015-12-16 18:48:48.386 ThaliTest[305:115830] jxcore: connect Apple-IpadAir2-1_PT5378.J91vGA==
2015-12-16 18:48:48.387 ThaliTest[305:115830] client session: connect
,2015-12-16 18:48:48.388 ThaliTest[305:115830] client session: stateChange:0->1 Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16 18:48:54.226 ThaliTest[305:116721] client session: connected
,2015-12-16 18:48:54.227 ThaliTest[305:116721] client session: stateChange:1->2 Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16 18:48:54.250 ThaliTest[305:116748] client session: fireConnectCallback: Apple-IpadAir2-1_PT5378.J91vGA==
2015-12-16 18:48:54.250 ThaliTest[305:116748] jxcore: connect: success
2015-12-16T17:48:54.252Z SendDataConnector.js: CLIENT connected to ,50121, error: null
2015-12-16T17:48:54.253Z SendDataConnector.js: CLIENT starting client 
,2015-12-16 18:48:54.257 ThaliTest[305:115607] client: relay established
2015-12-16 18:48:54.257 ThaliTest[305:115607] client: new accepted socket: 0x18c99360
,2015-12-16T17:48:54.274Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16T17:48:54.674Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-16T17:48:54.687Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-16T17:48:54.699Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-16T17:48:54.713Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-16T17:48:54.713Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-16T17:48:54.714Z SendDataConnector.js: CLIENT Stop now
,2015-12-16T17:48:54.714Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 18:48:54.715 ThaliTest[305:115830] jxcore: disconnect
2015-12-16 18:48:54.715 ThaliTest[305:115830] client session: disconnectFromPeer: Apple-IpadAir2-1_PT5378.J91vGA==
2015-12-16 18:48:54.715 ThaliTest[305:115830] client session: disconnect
2015-12-16 18:48:54.716 ThaliTest[305:115830] client session: stateChange:2->0 Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16 18:48:54.723 ThaliTest[305:115830] jxcore: disconnect: success
2015-12-16T17:48:54.725Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5378.J91vGA==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
,sendReportNow
done, now sending data to server
,2015-12-16T17:48:54.731Z SendDataConnector.js: CLIENT Stop now
2015-12-16T17:48:54.731Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 18:48:56.785 ThaliTest[305:115607] client: lost peer: Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:48:56.786 ThaliTest[305:115607] client session: onPeerLost: Apple-Iphone5-1_PT6761.1E6mhw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone5-1_PT6761.1E6mhw==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,teardown
,testSendData stopped
,2015-12-16 18:48:58.668 ThaliTest[305:115830] jxcore: stopBroadcasting
2015-12-16 18:48:58.669 ThaliTest[305:115830] THEMultipeerSession stopping peer
2015-12-16 18:48:58.670 ThaliTest[305:115830] multipeer session: stop timer
2015-12-16 18:48:58.670 Th,aliTest[305:115830] server session: disconnect
2015-12-16 18:48:58.671 ThaliTest[305:115830] server session: stateChange:2->0 Apple-IpadAir2-1_PT5378
,2015-12-16 18:48:58.684 ThaliTest[305:115830] server session: disconnect
2015-12-16 18:48:58.685 ThaliTest[305:115830] server session: stateChange:2->0 Apple-Iphone5-1_PT6761
,2015-12-16 18:48:58.794 ThaliTest[305:115830] server session: disconnect
,2015-12-16 18:48:58.795 ThaliTest[305:115830] server session: stateChange:2->0 Apple-Iphone6-1_PT3143
,2015-12-16 18:48:58.866 ThaliTest[305:115830] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-16T17:48:58.884Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-16T17:48:58.886Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-16T17:48:58.888Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-16T17:48:58.889Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
