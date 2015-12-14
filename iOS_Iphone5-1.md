#### Test 50650278b2f31ec_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278b2f31ec/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/9A2FCD42-65F8-45AB-BA54-625D464B2131/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/9A2FCD42-65F8-45AB-BA54-625D464B2131/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278b2f31ec/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278b2f31ec/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/75528C1B-2F58-4704-A3D9-74365004A2AF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55209"
,(lldb)     command script import "/tmp/9A2FCD42-65F8-45AB-BA54-625D464B2131/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-14 15:35:48.270 ThaliTest[753:1265802] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CEAE8833-F5A3-454F-AAB2-157886647591/Library/Cookies/Cookies.binarycookies
,2015-12-14 15:35:48.409 ThaliTest[753:1265802] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-14 15:35:48.411 ThaliTest[753:1265802] Multi-tasking -> Device: YES, App: YES
,2015-12-14 15:35:48.418 ThaliTest[753:1265802] Unlimited access to network resources
,2015-12-14 15:35:48.433 ThaliTest[753:1265802] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-14 15:35:58.701 ThaliTest[753:1265802] Resetting plugins due to page load.
,2015-12-14 15:36:02.885 ThaliTest[753:1265802] Finished load of: file:///var/mobile/Containers/Bundle/Application/75528C1B-2F58-4704-A3D9-74365004A2AF/ThaliTest.app/www/index.html
,2015-12-14 15:36:03.089 ThaliTest[753:1265802] JXcore Cordova plugin initializing
,2015-12-14 15:36:03.092 ThaliTest[753:1265983] JXcore instance initializing
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
,2015-12-14 15:36:05.520 ThaliTest[753:1265802] THREAD WARNING: ['JXcore'] took '155.116943' ms. Plugin should use a background thread.
,appEnteredForeground wasn't registered
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-14 15:42:00.696 ThaliTest[753:1265983] jxcore: startBroadcasting
,2015-12-14 15:42:00.706 ThaliTest[753:1265983] server: starting Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:00.708 ThaliTest[753:1265983] multipeer session: start timer: 0x1b203a70
2015-12-14 15:42:00.708 ThaliTest[753:1265983] THEMultipeerSession initialized peer Apple-Iphone5-1_PT9827
2015-12-14 15:42:00.709 ThaliTest[753:1265983] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-14 15:42:01.986 ThaliTest[753:1265802] client: found peer: Apple-IpadAir2-1_PT4459.Sbdxaw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4459.Sbdxaw==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1_PT4459.Sbdxaw==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-14 15:42:02.442 ThaliTest[753:1265802] client: found peer: Apple-Iphone6-1_PT9995.u0gQiQ==
,teardown
,testFindPeers stopped
2015-12-14 15:42:02.798 ThaliTest[753:1265983] jxcore: stopBroadcasting
,2015-12-14 15:42:02.798 ThaliTest[753:1265983] THEMultipeerSession stopping peer
2015-12-14 15:42:02.798 ThaliTest[753:1265983] multipeer session: stop timer
,2015-12-14 15:42:02.799 ThaliTest[753:1265983] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 58032
,2015-12-14 15:42:02.865 ThaliTest[753:1265983] jxcore: startBroadcasting
,2015-12-14 15:42:02.869 ThaliTest[753:1265983] server: starting Apple-Iphone5-1_PT9827.8xg46g==
2015-12-14 15:42:02.870 ThaliTest[753:1265983] multipeer session: start timer: 0x1b399360
2015-12-14 15:42:02.870 ThaliTest[753:1265983] THEMultipeerSession i,nitialized peer Apple-Iphone5-1_PT9827
2015-12-14 15:42:02.870 ThaliTest[753:1265983] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2015-12-14T14:42:02.873Z SendDataTCPServer.js: TCP/IP server is bound to port: 58032
,2015-12-14 15:42:02.892 ThaliTest[753:1265802] client: found peer: Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:02.893 ThaliTest[753:1265802] client: found peer: Apple-IpadAir2-1_PT4459.Sbdxaw==
2015-12-14 15:42:02.893 ThaliTest[753:1265802] client: ,found peer: Apple-Iphone6-1_PT9995.u0gQiQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9827.emG9ZA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone5-1_PT98,27.emG9ZA==
2015-12-14T14:42:02.898Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14T14:42:02.902Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14T14:42:02.902Z SendData,Connector.js: do connect now
2015-12-14 15:42:02.903 ThaliTest[753:1265983] jxcore: connect Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14 15:42:02.904 ThaliTest[753:1265983] client session: connect
2015-12-14 15:42:02.911 ThaliTest[753:1265983] client session: stateChange:0->1 Apple-Iphone5-1_PT9827.emG9ZA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4459.Sbdxaw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9995.u0gQiQ==","peerName":"(null)",,"peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 15:42:03.955 ThaliTest[753:1265802] client: lost peer: Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:03.956 ThaliTest[753:1265802] client session: onPeerLost: Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:03.956 ThaliTest[753:1265802] cl,ient session: onLinkFailure: Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:03.956 ThaliTest[753:1265802] client session: disconnect
2015-12-14 15:42:03.956 ThaliTest[753:1265802] client session: stateChange:1->0 Apple-Iphone5-1_PT9827.emG9ZA==
2015-1,2-14 15:42:03.957 ThaliTest[753:1265802] client session: fireConnectCallback: Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:03.957 ThaliTest[753:1265802] jxcore: connect: fail: Peer disconnected
2015-12-14T14:42:03.958Z SendDataConnector.js: CLIENT co,nnected to 0, error: Peer disconnected
2015-12-14T14:42:03.958Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-14T14:42:03.959Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ipho,ne5-1_PT9827.emG9ZA==","peerName":"(null)","peerAvailable":false}]
,2015-12-14 15:42:03.972 ThaliTest[753:1265802] client: found peer: Apple-Iphone6-1_PT9995.Xv3OoQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9995.Xv3OoQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 15:42:04.553 ThaliTest[753:1265802] client: lost peer: Apple-Iphone6-1_PT9995.u0gQiQ==
2015-12-14 15:42:04.553 ThaliTest[753:1265802] client session: onPeerLost: Apple-Iphone6-1_PT9995.u0gQiQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT9995.u0gQiQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
2015-12-14 15:42:04.554 ThaliTest[753:1265802] client: found peer: Apple-IpadAir2-1_PT4459.LRQ+wA==
peerAvailabilityChanged [{"peerIdentifier":,"Apple-IpadAir2-1_PT4459.LRQ+wA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-14 15:42:04.722 ThaliTest[753:1265802] client: found peer: Apple-Iphone5s-1_PT2942.N5Uy6w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT2942.N5Uy6w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 15:42:07.027 ThaliTest[753:1265802] client: lost peer: Apple-IpadAir2-1_PT4459.Sbdxaw==
2015-12-14 15:42:07.027 ThaliTest[753:1265802] client session: onPeerLost: Apple-IpadAir2-1_PT4459.Sbdxaw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4459.Sbdxaw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-14T14:42:08.959Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14T14:42:08.960Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14 15:42:13.969 ThaliTest[753:1265983] jxcore: disconnect
2015-12-14 15:42:13.970 ThaliTest[753:1265983] jxcore: disconnect: fail
2015-12-14T14:42:13.970Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14T14:42:13.972Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT9827.emG9ZA== with availability status: true
,2015-12-14T14:42:13.973Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14T14:42:13.973Z SendDataConnector.js: do connect now
,2015-12-14 15:42:13.973 ThaliTest[753:1265983] jxcore: connect Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:13.974 ThaliTest[753:1265983] client: connect: unreachable Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14 15:42:13.974 ThaliTest[753:1265983] jxcore: connect: fail: Peer unreachable
2015-12-14T14:42:13.974Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T14:42:13.975Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T14:42:13.975Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T14:42:18.978Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14T14:42:18.978Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14 15:42:23.990 ThaliTest[753:1265983] jxcore: disconnect
2015-12-14 15:42:23.991 ThaliTest[753:1265983] jxcore: disconnect: fail
2015-12-14T14:42:23.991Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9827.emG9ZA=,=
2015-12-14T14:42:23.992Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT9827.emG9ZA== with availability status: true
2015-12-14T14:42:23.992Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14T14:42:23.993Z SendDataConnector.js: do connect now
,2015-12-14 15:42:23.993 ThaliTest[753:1265983] jxcore: connect Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:23.994 ThaliTest[753:1265983] client: connect: unreachable Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:23.994 ThaliTest[753:1265983] jxcore: connect: fail: Peer unreachable
,2015-12-14T14:42:23.995Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T14:42:23.995Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T14:42:23.995Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T14:42:29.007Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14T14:42:29.007Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14 15:42:32.871 ThaliTest[753:1265802] multipeer session: restart
,2015-12-14 15:42:34.014 ThaliTest[753:1265983] jxcore: disconnect
2015-12-14 15:42:34.014 ThaliTest[753:1265983] jxcore: disconnect: fail
2015-12-14T14:42:34.015Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9827.emG9ZA=,=
2015-12-14T14:42:34.016Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT9827.emG9ZA== with availability status: true
2015-12-14T14:42:34.016Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9827.emG9ZA==
201,5-12-14T14:42:34.016Z SendDataConnector.js: do connect now
,2015-12-14 15:42:34.017 ThaliTest[753:1265983] jxcore: connect Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:34.017 ThaliTest[753:1265983] client: connect: unreachable Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:34.018 ThaliTest[753:1265983] jxcore: connect: fail: Peer unreachable
,2015-12-14T14:42:34.018Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T14:42:34.019Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T14:42:34.019Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T14:42:39.029Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14T14:42:39.030Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14 15:42:44.040 ThaliTest[753:1265983] jxcore: disconnect
2015-12-14 15:42:44.040 ThaliTest[753:1265983] jxcore: disconnect: fail
2015-12-14T14:42:44.041Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9827.emG9ZA=,=
2015-12-14T14:42:44.041Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT9827.emG9ZA== with availability status: true
2015-12-14T14:42:44.042Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9827.emG9ZA==
201,5-12-14T14:42:44.042Z SendDataConnector.js: do connect now
,2015-12-14 15:42:44.043 ThaliTest[753:1265983] jxcore: connect Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:44.043 ThaliTest[753:1265983] client: connect: unreachable Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:44.044 ThaliTest[753:1265983] jxco,re: connect: fail: Peer unreachable
,2015-12-14T14:42:44.044Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T14:42:44.044Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
2015-12-14T14:42:44.046Z SendDataConnector.js: CLIENT Stop now
2015-12-14 15:42:44.046 ThaliTest[753:1265983] jxcore: disconnect
2015-12-14 15:42:44.047 ThaliTest[753:1265983] jxcore: disconnect: fail
2015-12-14T14:42:44.047Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9827.emG9ZA==
---- round done--------
,startWithNextDevice
device[2]: Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14T14:42:44.049Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14T14:42:44.049Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14T14:42:44.050Z SendDataConnector.js: do connect now
,2015-12-14 15:42:44.050 ThaliTest[753:1265983] jxcore: connect Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14 15:42:44.050 ThaliTest[753:1265983] client session: connect
,2015-12-14 15:42:44.051 ThaliTest[753:1265983] client session: stateChange:0->1 Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14 15:42:44.058 ThaliTest[753:1265802] client: lost peer: Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14 15:42:44.058 ThaliTest[753:1265802] client session: onPeerLost: Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14 15:42:44.059 ThaliTest[753:1265802] cl,ient session: onLinkFailure: Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14 15:42:44.059 ThaliTest[753:1265802] client session: disconnect
2015-12-14 15:42:44.059 ThaliTest[753:1265802] client session: stateChange:1->0 Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-1,2-14 15:42:44.059 ThaliTest[753:1265802] client session: fireConnectCallback: Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14 15:42:44.060 ThaliTest[753:1265802] jxcore: connect: fail: Peer disconnected
2015-12-14T14:42:44.061Z SendDataConnector.js: CLIENT co,nnected to 0, error: Peer disconnected
2015-12-14T14:42:44.061Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-14T14:42:44.061Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ipho,ne6-1_PT9995.Xv3OoQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-14 15:42:48.535 ThaliTest[753:1265802] multipeer session: reset timer
2015-12-14 15:42:48.536 ThaliTest[753:1265802] multipeer session: stop timer
2015-12-14 15:42:48.536 ThaliTest[753:1265802] multipeer session: start timer: 0x1b399360
2015-12-14 15:42:48.537 ThaliTest[753:1265802] server session: connect
2015-12-14 15:42:48.537 ThaliTest[753:1265802] server session: stateChange:0->1 Apple-Iphone6-1_PT9995
,2015-12-14 15:42:48.545 ThaliTest[753:1265802] server: accepting invitation Apple-Iphone6-1_PT9995
,2015-12-14 15:42:48.598 ThaliTest[753:1265802] multipeer session: reset timer
2015-12-14 15:42:48.598 ThaliTest[753:1265802] multipeer session: stop timer
2015-12-14 15:42:48.599 ThaliTest[753:1265802] multipeer session: start timer: 0x1b399360
2015-12-,14 15:42:48.599 ThaliTest[753:1265802] server session: connect
2015-12-14 15:42:48.599 ThaliTest[753:1265802] server session: stateChange:0->1 Apple-IpadAir2-1_PT4459
2015-12-14 15:42:48.608 ThaliTest[753:1265802] server: accepting invitation Apple-IpadAir2-1_PT4459
,2015-12-14 15:42:48.737 ThaliTest[753:1265802] multipeer session: reset timer
2015-12-14 15:42:48.737 ThaliTest[753:1265802] multipeer session: stop timer
2015-12-14 15:42:48.737 ThaliTest[753:1265802] multipeer session: start timer: 0x1b399360
2015-12-14 15:42:48.737 ThaliTest[753:1265802] server session: connect
2015-12-14 15:42:48.737 ThaliTest[753:1265802] server session: stateChange:0->1 Apple-Iphone5s-1_PT2942
,2015-12-14 15:42:48.745 ThaliTest[753:1265802] server: accepting invitation Apple-Iphone5s-1_PT2942
,2015-12-14T14:42:49.069Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14T14:42:49.069Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14 15:42:52.147 ThaliTest[753:1266799] server session: connected
2015-12-14 15:42:52.147 ThaliTest[753:1266799] server session: stateChange:1->2 Apple-Iphone6-1_PT9995
,2015-12-14 15:42:52.189 ThaliTest[753:1265802] server relay: connected (to port: 58032)
,2015-12-14T14:42:52.198Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14 15:42:52.404 ThaliTest[753:1266812] server session: connected
2015-12-14 15:42:52.404 ThaliTest[753:1266812] server session: stateChange:1->2 Apple-Iphone5s-1_PT2942
,2015-12-14 15:42:52.408 ThaliTest[753:1265802] server relay: connected (to port: 58032)
,2015-12-14T14:42:52.421Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T14:42:52.451Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-14T14:42:52.466Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-14T14:42:52.483Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-14T14:42:52.499Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-14T14:42:52.513Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 15:42:52.523 ThaliTest[753:1266799] server session: connected
,2015-12-14 15:42:52.523 ThaliTest[753:1266799] server session: stateChange:1->2 Apple-IpadAir2-1_PT4459
,2015-12-14T14:42:52.540Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14 15:42:52.540 ThaliTest[753:1265802] server relay: connected (to port: 58032)
,2015-12-14 15:42:52.553 ThaliTest[753:1266813] server session: not connected Apple-Iphone6-1_PT9995
,2015-12-14T14:42:52.739Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-14T14:42:52.766Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-14T14:42:52.799Z SendDataTCPServer.js: TCP/IP server has received 25996 bytes of data
,2015-12-14T14:42:52.814Z SendDataTCPServer.js: TCP/IP server has received 62658 bytes of data
,2015-12-14T14:42:52.829Z SendDataTCPServer.js: TCP/IP server has received 87316 bytes of data
,2015-12-14T14:42:52.845Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14T14:42:52.926Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-14 15:42:52.946 ThaliTest[753:1266813] server session: not connected Apple-IpadAir2-1_PT4459
2015-12-14T14:42:52.949Z SendDataTCPServer.js: TCP/IP server has received 42948 bytes of data
,2015-12-14T14:42:52.965Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-14T14:42:52.980Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 15:42:53.121 ThaliTest[753:1266813] server session: not connected Apple-Iphone5s-1_PT2942
,2015-12-14 15:42:54.071 ThaliTest[753:1265983] jxcore: disconnect
2015-12-14 15:42:54.072 ThaliTest[753:1265983] jxcore: disconnect: fail
2015-12-14T14:42:54.072Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9995.Xv3OoQ=,=
2015-12-14T14:42:54.073Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT9995.Xv3OoQ== with availability status: true
2015-12-14T14:42:54.073Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14T14:42:54.073Z SendDataConnector.js: do connect now
,2015-12-14 15:42:54.075 ThaliTest[753:1265983] jxcore: connect Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14 15:42:54.075 ThaliTest[753:1265983] client: connect: unreachable Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14 15:42:54.076 ThaliTest[753:1265983] jxcore: connect: fail: Peer unreachable
,2015-12-14T14:42:54.077Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T14:42:54.078Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T14:42:54.078Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T14:42:59.079Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14T14:42:59.079Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14 15:43:04.085 ThaliTest[753:1265983] jxcore: disconnect
2015-12-14 15:43:04.085 ThaliTest[753:1265983] jxcore: disconnect: fail
2015-12-14T14:43:04.086Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9995.Xv3OoQ=,=
2015-12-14T14:43:04.087Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT9995.Xv3OoQ== with availability status: true
2015-12-14T14:43:04.087Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14T14:43:04.087Z SendDataConnector.js: do connect now
,2015-12-14 15:43:04.088 ThaliTest[753:1265983] jxcore: connect Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14 15:43:04.088 ThaliTest[753:1265983] client: connect: unreachable Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14 15:43:04.089 ThaliTest[753:1265983] jxco,re: connect: fail: Peer unreachable
2015-12-14T14:43:04.089Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T14:43:04.090Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T14:43:04.090Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T14:43:09.095Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14T14:43:09.095Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14 15:43:14.106 ThaliTest[753:1265983] jxcore: disconnect
2015-12-14 15:43:14.107 ThaliTest[753:1265983] jxcore: disconnect: fail
2015-12-14T14:43:14.107Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9995.Xv3OoQ=,=
2015-12-14T14:43:14.108Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT9995.Xv3OoQ== with availability status: true
2015-12-14T14:43:14.108Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14T14:43:14.109Z SendDataConnector.js: do connect now
,2015-12-14 15:43:14.110 ThaliTest[753:1265983] jxcore: connect Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14 15:43:14.110 ThaliTest[753:1265983] client: connect: unreachable Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14 15:43:14.110 ThaliTest[753:1265983] jxco,re: connect: fail: Peer unreachable
,2015-12-14T14:43:14.111Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T14:43:14.111Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T14:43:14.111Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14 15:43:18.738 ThaliTest[753:1265802] multipeer session: restart
,2015-12-14 15:43:18.769 ThaliTest[753:1265802] client: found peer: Apple-IpadAir2-1_PT4459.LRQ+wA==
2015-12-14 15:43:18.769 ThaliTest[753:1265802] client: found peer: Apple-Iphone6-1_PT9995.Xv3OoQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphon,e6-1_PT9995.Xv3OoQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-14 15:43:18.777 ThaliTest[753:1265802] client: found peer: Apple-Iphone5s-1_PT2942.N5Uy6w==
,2015-12-14T14:43:19.114Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14T14:43:19.115Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14 15:43:24.117 ThaliTest[753:1265983] jxcore: disconnect
2015-12-14 15:43:24.117 ThaliTest[753:1265983] jxcore: disconnect: fail
2015-12-14T14:43:24.118Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9995.Xv3OoQ=,=
2015-12-14T14:43:24.120Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT9995.Xv3OoQ== with availability status: true
2015-12-14T14:43:24.120Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9995.Xv3OoQ==
201,5-12-14T14:43:24.120Z SendDataConnector.js: do connect now
2015-12-14 15:43:24.120 ThaliTest[753:1265983] jxcore: connect Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14 15:43:24.121 ThaliTest[753:1265983] client session: connect
2015-12-14 15:43:24.121 Thal,iTest[753:1265983] client session: stateChange:0->1 Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14 15:43:27.793 ThaliTest[753:1266948] client session: connected
2015-12-14 15:43:27.793 ThaliTest[753:1266948] client session: stateChange:1->2 Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14 15:43:27.847 ThaliTest[753:1266949] client session: fireConnectCallback: Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14 15:43:27.847 ThaliTest[753:1266949] jxcore: connect: success
2015-12-14T14:43:27.848Z SendDataConnector.js: CLIENT connected to, 58043, error: null
2015-12-14T14:43:27.848Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 15:43:27.851 ThaliTest[753:1265802] client: relay established
,2015-12-14 15:43:27.852 ThaliTest[753:1265802] client: new accepted socket: 0x1b428cb0
,2015-12-14T14:43:27.866Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T14:43:28.439Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-14T14:43:28.453Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-14T14:43:28.500Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T14:43:28.501Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-14T14:43:28.501Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T14:43:28.502Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 15:43:28.503 ThaliTest[753:1265983] jxcore: disconnect
2015-12-14 15:43:28.503 ThaliTest[753:1265983] client session: disconnectFromPeer: Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14 15:43:28.504 ThaliTest[753:1265983] client session: disconnect
2015-12-14 15:43:28.504 ThaliTest[753:1265983] client session: stateChange:2->0 Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14 15:43:28.513 ThaliTest[753:1265983] jxcore: disconnect: success
2015-12-14T14:43:28.514Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9995.Xv3OoQ==
---- round done--------
startWithNextDevice
device[3]: Appl,e-IpadAir2-1_PT4459.LRQ+wA==
2015-12-14T14:43:28.515Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT4459.LRQ+wA==
2015-12-14T14:43:28.515Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT4459.LRQ+wA==
2015-12-14T14:,43:28.515Z SendDataConnector.js: do connect now
2015-12-14 15:43:28.516 ThaliTest[753:1265983] jxcore: connect Apple-IpadAir2-1_PT4459.LRQ+wA==
2015-12-14 15:43:28.518 ThaliTest[753:1265983] client session: connect
2015-12-14 15:43:28.518 ThaliTest[753:1265983] client session: stateChange:0->1 Apple-IpadAir2-1_PT4459.LRQ+wA==
,2015-12-14 15:43:31.781 ThaliTest[753:1266918] client session: connected
2015-12-14 15:43:31.781 ThaliTest[753:1266918] client session: stateChange:1->2 Apple-IpadAir2-1_PT4459.LRQ+wA==
,2015-12-14 15:43:31.843 ThaliTest[753:1266919] client session: fireConnectCallback: Apple-IpadAir2-1_PT4459.LRQ+wA==
2015-12-14 15:43:31.843 ThaliTest[753:1266919] jxcore: connect: success
2015-12-14T14:43:31.844Z SendDataConnector.js: CLIENT connected to 58046, error: null
2015-12-14T14:43:31.844Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 15:43:31.847 ThaliTest[753:1265802] client: relay established
,2015-12-14 15:43:31.848 ThaliTest[753:1265802] client: new accepted socket: 0x1b3b39f0
,2015-12-14T14:43:31.860Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T14:43:32.382Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-14T14:43:32.399Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-14T14:43:32.415Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T14:43:32.417Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T14:43:32.419Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T14:43:32.419Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 15:43:32.420 ThaliTest[753:1265983] jxcore: disconnect
,2015-12-14 15:43:32.420 ThaliTest[753:1265983] client session: disconnectFromPeer: Apple-IpadAir2-1_PT4459.LRQ+wA==
,2015-12-14 15:43:32.421 ThaliTest[753:1265983] client session: disconnect
,2015-12-14 15:43:32.422 ThaliTest[753:1265983] client session: stateChange:2->0 Apple-IpadAir2-1_PT4459.LRQ+wA==
,2015-12-14 15:43:32.507 ThaliTest[753:1265983] jxcore: disconnect: success
2015-12-14T14:43:32.508Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT4459.LRQ+wA==
---- round done--------
startWithNextDevice
,device[4]: Apple-Iphone5s-1_PT2942.N5Uy6w==
2015-12-14T14:43:32.510Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT2942.N5Uy6w==
2015-12-14T14:43:32.510Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT2942.N5Uy6w==,
2015-12-14T14:43:32.511Z SendDataConnector.js: do connect now
,2015-12-14 15:43:32.511 ThaliTest[753:1265983] jxcore: connect Apple-Iphone5s-1_PT2942.N5Uy6w==
2015-12-14 15:43:32.512 ThaliTest[753:1265983] client session: connect
2015-12-14 15:43:32.512 ThaliTest[753:1265983] client session: stateChange:0->1 Apple-I,phone5s-1_PT2942.N5Uy6w==
,2015-12-14 15:43:35.679 ThaliTest[753:1266949] client session: connected
,2015-12-14 15:43:35.679 ThaliTest[753:1266949] client session: stateChange:1->2 Apple-Iphone5s-1_PT2942.N5Uy6w==
,2015-12-14 15:43:35.683 ThaliTest[753:1266949] client session: fireConnectCallback: Apple-Iphone5s-1_PT2942.N5Uy6w==
2015-12-14 15:43:35.683 ThaliTest[753:1266949] jxcore: connect: success
,2015-12-14T14:43:35.684Z SendDataConnector.js: CLIENT connected to 58049, error: null
,2015-12-14T14:43:35.684Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 15:43:35.686 ThaliTest[753:1265802] client: relay established
,2015-12-14 15:43:35.686 ThaliTest[753:1265802] client: new accepted socket: 0x1b41f040
,2015-12-14T14:43:35.700Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T14:43:36.244Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-14T14:43:36.296Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-14T14:43:36.310Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T14:43:36.311Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T14:43:36.312Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T14:43:36.313Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 15:43:36.314 ThaliTest[753:1265983] jxcore: disconnect
2015-12-14 15:43:36.314 ThaliTest[753:1265983] client session: disconnectFromPeer: Apple-Iphone5s-1_PT2942.N5Uy6w==
2015-12-14 15:43:36.314 ThaliTest[753:1265983] client session: disconnec,t
2015-12-14 15:43:36.315 ThaliTest[753:1265983] client session: stateChange:2->0 Apple-Iphone5s-1_PT2942.N5Uy6w==
,2015-12-14 15:43:36.324 ThaliTest[753:1265983] jxcore: disconnect: success
2015-12-14T14:43:36.324Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT2942.N5Uy6w==
---- round done--------
startWithNextDevice
weAreDoneNow, ,resultArray.length: 4
sendReportNow
done, now sending data to server
2015-12-14T14:43:36.329Z SendDataConnector.js: CLIENT Stop now
2015-12-14T14:43:36.329Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
2015-12-14 15:43:37.070 ThaliTest[753:1265983] jxcore: stopBroadcasting
,2015-12-14 15:43:37.071 ThaliTest[753:1265983] THEMultipeerSession stopping peer
,2015-12-14 15:43:37.071 ThaliTest[753:1265983] multipeer session: stop timer
,2015-12-14 15:43:37.072 ThaliTest[753:1265983] server session: disconnect
,2015-12-14 15:43:37.072 ThaliTest[753:1265983] server session: stateChange:2->0 Apple-Iphone6-1_PT9995
,2015-12-14 15:43:37.137 ThaliTest[753:1265983] server session: disconnect
2015-12-14 15:43:37.138 ThaliTest[753:1265983] server session: stateChange:2->0 Apple-IpadAir2-1_PT4459
,2015-12-14 15:43:37.143 ThaliTest[753:1265983] server session: disconnect
2015-12-14 15:43:37.143 ThaliTest[753:1265983] server session: stateChange:2->0 Apple-Iphone5s-1_PT2942
,2015-12-14 15:43:37.149 ThaliTest[753:1265983] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-14T14:43:37.165Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T14:43:37.169Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T14:43:37.170Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T14:43:37.170Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
