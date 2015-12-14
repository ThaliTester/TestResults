#### Test 50650278b2f31ec_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278b2f31ec/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/14F81039-B3D5-4FAA-8154-76846F4C57F9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/14F81039-B3D5-4FAA-8154-76846F4C57F9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278b2f31ec/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278b2f31ec/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/70351066-07F9-4EDD-93E5-50B00177AE57/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55249"
,(lldb)     command script import "/tmp/14F81039-B3D5-4FAA-8154-76846F4C57F9/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-14 15:37:20.405 ThaliTest[931:1157953] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/55687972-4212-4E32-9188-E9E1B75F257C/Library/Cookies/Cookies.binarycookies
,2015-12-14 15:37:20.833 ThaliTest[931:1157953] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-14 15:37:20.835 ThaliTest[931:1157953] Multi-tasking -> Device: YES, App: YES
,2015-12-14 15:37:20.845 ThaliTest[931:1157953] Unlimited access to network resources
,2015-12-14 15:37:20.861 ThaliTest[931:1157953] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-14 15:37:30.260 ThaliTest[931:1157953] Resetting plugins due to page load.
,2015-12-14 15:37:34.174 ThaliTest[931:1157953] Finished load of: file:///var/mobile/Containers/Bundle/Application/70351066-07F9-4EDD-93E5-50B00177AE57/ThaliTest.app/www/index.html
,2015-12-14 15:37:34.372 ThaliTest[931:1157953] JXcore Cordova plugin initializing
,2015-12-14 15:37:34.374 ThaliTest[931:1158169] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-14 15:37:35.687 ThaliTest[931:1157953] THREAD WARNING: ['JXcore'] took '90.979004' ms. Plugin should use a background thread.
,appEnteredForeground wasn't registered
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-14 15:42:00.446 ThaliTest[931:1158169] jxcore: startBroadcasting
,2015-12-14 15:42:00.465 ThaliTest[931:1158169] server: starting Apple-Iphone5s-1_PT2942.RoZN1g==
,2015-12-14 15:42:00.472 ThaliTest[931:1158169] multipeer session: start timer: 0x19374470
,2015-12-14 15:42:00.482 ThaliTest[931:1158169] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT2942
,2015-12-14 15:42:00.484 ThaliTest[931:1158169] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-14 15:42:02.249 ThaliTest[931:1157953] client: found peer: Apple-IpadAir2-1_PT4459.Sbdxaw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4459.Sbdxaw==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1_PT4459.Sbdxaw==, peerAvailable: true
,weAreDoneNow
done, now sending data to server
,teardown
,testFindPeers stopped
2015-12-14 15:42:02.545 ThaliTest[931:1158169] jxcore: stopBroadcasting
,2015-12-14 15:42:02.545 ThaliTest[931:1158169] THEMultipeerSession stopping peer
2015-12-14 15:42:02.546 ThaliTest[931:1158169] multipeer session: stop timer
2015-12-14 15:42:02.547 ThaliTest[931:1158169] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 57627
,2015-12-14 15:42:02.635 ThaliTest[931:1158169] jxcore: startBroadcasting
,2015-12-14 15:42:02.641 ThaliTest[931:1158169] server: starting Apple-Iphone5s-1_PT2942.N5Uy6w==
,2015-12-14 15:42:02.644 ThaliTest[931:1158169] multipeer session: start timer: 0x19484250
,2015-12-14 15:42:02.649 ThaliTest[931:1158169] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT2942
,2015-12-14 15:42:02.658 ThaliTest[931:1158169] jxcore: startBroadcasting: success
,StartBroadcasting started ok
2015-12-14 15:42:02.663 ThaliTest[931:1157953] client: found peer: Apple-IpadAir2-1_PT4459.Sbdxaw==
null
2015-12-14T14:42:02.665Z SendDataTCPServer.js: TCP/IP server is bound to port: 57627
2015-12-14 15:42:02.666 ThaliTest[931:1157953] client: found peer: Apple-Iphone5s-1_PT2942.RoZN1g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4459.Sbdxaw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-IpadAir2-1_PT4459.Sbdxaw==
,2015-12-14T14:42:02.673Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT4459.Sbdxaw==
,2015-12-14T14:42:02.674Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT4459.Sbdxaw==
,2015-12-14T14:42:02.674Z SendDataConnector.js: do connect now
,2015-12-14 15:42:02.675 ThaliTest[931:1158169] jxcore: connect Apple-IpadAir2-1_PT4459.Sbdxaw==
,2015-12-14 15:42:02.676 ThaliTest[931:1158169] client session: connect
,2015-12-14 15:42:02.677 ThaliTest[931:1158169] client session: stateChange:0->1 Apple-IpadAir2-1_PT4459.Sbdxaw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT2942.RoZN1g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 15:42:02.774 ThaliTest[931:1157953] client: found peer: Apple-Iphone5-1_PT9827.emG9ZA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9827.emG9ZA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 15:42:03.702 ThaliTest[931:1157953] client: lost peer: Apple-IpadAir2-1_PT4459.Sbdxaw==
2015-12-14 15:42:03.702 ThaliTest[931:1157953] client session: onPeerLost: Apple-IpadAir2-1_PT4459.Sbdxaw==
2015-12-14 15:42:03.702 ThaliTest[931:1157953] ,client session: onLinkFailure: Apple-IpadAir2-1_PT4459.Sbdxaw==
2015-12-14 15:42:03.703 ThaliTest[931:1157953] client session: disconnect
2015-12-14 15:42:03.703 ThaliTest[931:1157953] client session: stateChange:1->0 Apple-IpadAir2-1_PT4459.Sbdxaw==
20,15-12-14 15:42:03.704 ThaliTest[931:1157953] client session: fireConnectCallback: Apple-IpadAir2-1_PT4459.Sbdxaw==
2015-12-14 15:42:03.704 ThaliTest[931:1157953] jxcore: connect: fail: Peer disconnected
2015-12-14T14:42:03.706Z SendDataConnector.js: CLIE,NT connected to 0, error: Peer disconnected
2015-12-14T14:42:03.706Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-14T14:42:03.707Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple,-IpadAir2-1_PT4459.Sbdxaw==","peerName":"(null)","peerAvailable":false}]
,2015-12-14 15:42:03.784 ThaliTest[931:1157953] client: lost peer: Apple-Iphone5s-1_PT2942.RoZN1g==
2015-12-14 15:42:03.784 ThaliTest[931:1157953] client session: onPeerLost: Apple-Iphone5s-1_PT2942.RoZN1g==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone5s-1_PT2942.RoZN1g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-14 15:42:03.882 ThaliTest[931:1157953] client: found peer: Apple-Iphone6-1_PT9995.Xv3OoQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9995.Xv3OoQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tru,e
,2015-12-14 15:42:04.428 ThaliTest[931:1157953] client: lost peer: Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:04.429 ThaliTest[931:1157953] client session: onPeerLost: Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:04.431 ThaliTest[931:1157953] cl,ient: found peer: Apple-Iphone5-1_PT9827.8xg46g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9827.emG9ZA==","peerName":"(null)","peerAvailable":false}]
2015-12-14 15:42:04.431 ThaliTest[931:1157953] client: found peer: Apple-IpadAir2-1,_PT4459.LRQ+wA==
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9827.8xg46g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifie,r":"Apple-IpadAir2-1_PT4459.LRQ+wA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14T14:42:08.717Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT4459.Sbdxaw==
,2015-12-14T14:42:08.718Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT4459.Sbdxaw==
,2015-12-14 15:42:13.720 ThaliTest[931:1158169] jxcore: disconnect
2015-12-14 15:42:13.721 ThaliTest[931:1158169] jxcore: disconnect: fail
2015-12-14T14:42:13.722Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT4459.Sbdxaw,==
2015-12-14T14:42:13.722Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT4459.Sbdxaw== with availability status: true
2015-12-14T14:42:13.723Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT4459.Sbdxaw==
2015-12-14T14:42:13.723Z SendDataConnector.js: do connect now
,2015-12-14 15:42:13.724 ThaliTest[931:1158169] jxcore: connect Apple-IpadAir2-1_PT4459.Sbdxaw==
2015-12-14 15:42:13.724 ThaliTest[931:1158169] client: connect: unreachable Apple-IpadAir2-1_PT4459.Sbdxaw==
2015-12-14 15:42:13.725 ThaliTest[931:1158169] jx,core: connect: fail: Peer unreachable
,2015-12-14T14:42:13.726Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T14:42:13.726Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T14:42:13.728Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T14:42:18.734Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT4459.Sbdxaw==
,2015-12-14T14:42:18.734Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT4459.Sbdxaw==
,2015-12-14 15:42:23.743 ThaliTest[931:1158169] jxcore: disconnect
2015-12-14 15:42:23.744 ThaliTest[931:1158169] jxcore: disconnect: fail
2015-12-14T14:42:23.745Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT4459.Sbdxaw,==
2015-12-14T14:42:23.745Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT4459.Sbdxaw== with availability status: true
2015-12-14T14:42:23.745Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT4459.Sbdxaw==
,2015-12-14T14:42:23.746Z SendDataConnector.js: do connect now
,2015-12-14 15:42:23.747 ThaliTest[931:1158169] jxcore: connect Apple-IpadAir2-1_PT4459.Sbdxaw==
2015-12-14 15:42:23.747 ThaliTest[931:1158169] client: connect: unreachable Apple-IpadAir2-1_PT4459.Sbdxaw==
,2015-12-14 15:42:23.748 ThaliTest[931:1158169] jxcore: connect: fail: Peer unreachable
,2015-12-14T14:42:23.749Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T14:42:23.750Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T14:42:23.751Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T14:42:28.754Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT4459.Sbdxaw==
,2015-12-14T14:42:28.754Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT4459.Sbdxaw==
,2015-12-14 15:42:32.649 ThaliTest[931:1157953] multipeer session: restart
,2015-12-14 15:42:32.717 ThaliTest[931:1157953] client: found peer: Apple-Iphone5-1_PT9827.8xg46g==
2015-12-14 15:42:32.717 ThaliTest[931:1157953] client: found peer: Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14 15:42:32.718 ThaliTest[931:1157953] client: found peer: Apple-IpadAir2-1_PT4459.LRQ+wA==
,2015-12-14 15:42:33.759 ThaliTest[931:1158169] jxcore: disconnect
2015-12-14 15:42:33.759 ThaliTest[931:1158169] jxcore: disconnect: fail
2015-12-14T14:42:33.760Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT4459.Sbdxaw,==
2015-12-14T14:42:33.760Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT4459.Sbdxaw== with availability status: true
2015-12-14T14:42:33.760Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT4459.Sbdxaw==
,2015-12-14T14:42:33.761Z SendDataConnector.js: do connect now
2015-12-14 15:42:33.762 ThaliTest[931:1158169] jxcore: connect Apple-IpadAir2-1_PT4459.Sbdxaw==
,2015-12-14 15:42:33.763 ThaliTest[931:1158169] client: connect: unreachable Apple-IpadAir2-1_PT4459.Sbdxaw==
2015-12-14 15:42:33.763 ThaliTest[931:1158169] jxcore: connect: fail: Peer unreachable
,2015-12-14T14:42:33.764Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T14:42:33.765Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T14:42:33.765Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T14:42:38.773Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT4459.Sbdxaw==
,2015-12-14T14:42:38.774Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT4459.Sbdxaw==
,2015-12-14 15:42:43.778 ThaliTest[931:1158169] jxcore: disconnect
2015-12-14 15:42:43.778 ThaliTest[931:1158169] jxcore: disconnect: fail
2015-12-14T14:42:43.779Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT4459.Sbdxaw,==
2015-12-14T14:42:43.779Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT4459.Sbdxaw== with availability status: true
2015-12-14T14:42:43.780Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT4459.Sbdxaw==
,2015-12-14T14:42:43.780Z SendDataConnector.js: do connect now
2015-12-14 15:42:43.781 ThaliTest[931:1158169] jxcore: connect Apple-IpadAir2-1_PT4459.Sbdxaw==
2015-12-14 15:42:43.781 ThaliTest[931:1158169] client: connect: unreachable Apple-IpadAir2-1_PT4,459.Sbdxaw==
,2015-12-14 15:42:43.782 ThaliTest[931:1158169] jxcore: connect: fail: Peer unreachable
,2015-12-14T14:42:43.783Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T14:42:43.784Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2015-12-14T14:42:43.787Z SendDataConnector.js: CLIENT Stop now
,2015-12-14 15:42:43.788 ThaliTest[931:1158169] jxcore: disconnect
2015-12-14 15:42:43.788 ThaliTest[931:1158169] jxcore: disconnect: fail
,2015-12-14T14:42:43.790Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT4459.Sbdxaw==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14T14:42:43.794Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14T14:42:43.794Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14T14:42:43.795Z SendDataConnector.js: do connect now
,2015-12-14 15:42:43.796 ThaliTest[931:1158169] jxcore: connect Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14 15:42:43.797 ThaliTest[931:1158169] client session: connect
2015-12-14 15:42:43.797 ThaliTest[931:1158169] client session: stateChange:0->1 Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14 15:42:47.898 ThaliTest[931:1158854] client session: connected
,2015-12-14 15:42:47.900 ThaliTest[931:1158854] client session: stateChange:1->2 Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14 15:42:48.013 ThaliTest[931:1158926] client session: fireConnectCallback: Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14 15:42:48.013 ThaliTest[931:1158926] jxcore: connect: success
2015-12-14T14:42:48.014Z SendDataConnector.js: CLIENT connected to 57633, error: null
2015-12-14T14:42:48.015Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 15:42:48.019 ThaliTest[931:1157953] client: relay established
2015-12-14 15:42:48.020 ThaliTest[931:1157953] client: new accepted socket: 0x19367f50
,2015-12-14T14:42:48.035Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T14:42:48.414Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-14T14:42:48.478Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T14:42:48.478Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T14:42:48.478Z SendDataConnector.js: CLIENT Stop now
2015-12-14T14:42:48.479Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 15:42:48.480 ThaliTest[931:1158169] jxcore: disconnect
,2015-12-14 15:42:48.480 ThaliTest[931:1158169] client session: disconnectFromPeer: Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14 15:42:48.481 ThaliTest[931:1158169] client session: disconnect
,2015-12-14 15:42:48.481 ThaliTest[931:1158169] client session: stateChange:2->0 Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14 15:42:48.549 ThaliTest[931:1158169] jxcore: disconnect: success
,2015-12-14T14:42:48.550Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9995.Xv3OoQ==
---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone5-1_PT9827.8xg46g==
,2015-12-14T14:42:48.551Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9827.8xg46g==
,2015-12-14T14:42:48.551Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9827.8xg46g==
,2015-12-14T14:42:48.551Z SendDataConnector.js: do connect now
,2015-12-14 15:42:48.552 ThaliTest[931:1158169] jxcore: connect Apple-Iphone5-1_PT9827.8xg46g==
,2015-12-14 15:42:48.552 ThaliTest[931:1158169] client session: connect
,2015-12-14 15:42:48.553 ThaliTest[931:1158169] client session: stateChange:0->1 Apple-Iphone5-1_PT9827.8xg46g==
,2015-12-14 15:42:52.323 ThaliTest[931:1158854] client session: connected
2015-12-14 15:42:52.324 ThaliTest[931:1158854] client session: stateChange:1->2 Apple-Iphone5-1_PT9827.8xg46g==
,2015-12-14 15:42:52.351 ThaliTest[931:1158926] client session: fireConnectCallback: Apple-Iphone5-1_PT9827.8xg46g==
,2015-12-14 15:42:52.352 ThaliTest[931:1158926] jxcore: connect: success
2015-12-14T14:42:52.354Z SendDataConnector.js: CLIENT connected to 57636, error: null
2015-12-14T14:42:52.355Z SendDataConnector.js: CLIENT starting client 
2015-12-14 15:42:52.359 ,ThaliTest[931:1157953] client: relay established
2015-12-14 15:42:52.359 ThaliTest[931:1157953] client: new accepted socket: 0x19351e40
,2015-12-14T14:42:52.371Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14 15:42:52.566 ThaliTest[931:1157953] multipeer session: reset timer
2015-12-14 15:42:52.566 ThaliTest[931:1157953] multipeer session: stop timer
2015-12-14 15:42:52.566 ThaliTest[931:1157953] multipeer session: start timer: 0x19484250
2015-12-14 15:42:52.566 ThaliTest[931:1157953] server session: connect
2015-12-14 15:42:52.566 ThaliTest[931:1157953] server session: stateChange:0->1 Apple-Iphone6-1_PT9995
2015-12-14 15:42:52.572 ThaliTest[931:1157953] server: accepting invitation Apple-Iphone6-1_PT9995
,2015-12-14T14:42:52.738Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-14 15:42:52.889 ThaliTest[931:1157953] multipeer session: reset timer
2015-12-14 15:42:52.889 ThaliTest[931:1157953] multipeer session: stop timer
2015-12-14 15:42:52.889 ThaliTest[931:1157953] multipeer session: start timer: 0x19484250
2015-12-14 15:42:52.889 ThaliTest[931:1157953] server session: connect
2015-12-14 15:42:52.889 ThaliTest[931:1157953] server session: stateChange:0->1 Apple-IpadAir2-1_PT4459
,2015-12-14 15:42:52.894 ThaliTest[931:1157953] server: accepting invitation Apple-IpadAir2-1_PT4459
,2015-12-14T14:42:52.930Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T14:42:52.931Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T14:42:52.932Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T14:42:52.933Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 15:42:52.933 ThaliTest[931:1158169] jxcore: disconnect
,2015-12-14 15:42:52.937 ThaliTest[931:1158169] client session: disconnectFromPeer: Apple-Iphone5-1_PT9827.8xg46g==
,2015-12-14 15:42:52.938 ThaliTest[931:1158169] client session: disconnect
,2015-12-14 15:42:52.939 ThaliTest[931:1158169] client session: stateChange:2->0 Apple-Iphone5-1_PT9827.8xg46g==
,2015-12-14 15:42:53.016 ThaliTest[931:1158169] jxcore: disconnect: success
2015-12-14T14:42:53.016Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9827.8xg46g==
---- round done--------
startWithNextDevice
device[4]: Apple-IpadAir2-1_PT4459.LRQ+wA==
2015-12-14T14:42:53.017Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT4459.LRQ+wA==
2015-12-14T14:42:53.017Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT4459.LRQ+wA==
2015-12-14T14:,42:53.017Z SendDataConnector.js: do connect now
2015-12-14 15:42:53.017 ThaliTest[931:1158169] jxcore: connect Apple-IpadAir2-1_PT4459.LRQ+wA==
2015-12-14 15:42:53.017 ThaliTest[931:1158169] client session: connect
2015-12-14 15:42:53.017 ThaliTest[931:1158169] client session: stateChange:0->1 Apple-IpadAir2-1_PT4459.LRQ+wA==
,2015-12-14 15:42:55.362 ThaliTest[931:1158855] server session: connected
2015-12-14 15:42:55.362 ThaliTest[931:1158855] server session: stateChange:1->2 Apple-Iphone6-1_PT9995
,2015-12-14 15:42:55.432 ThaliTest[931:1157953] server relay: connected (to port: 57627)
,2015-12-14T14:42:55.441Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T14:42:55.665Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-14T14:42:55.684Z SendDataTCPServer.js: TCP/IP server has received 10666 bytes of data
,2015-12-14T14:42:55.700Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-14T14:42:55.717Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-14T14:42:55.737Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-14T14:42:55.755Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 15:42:55.829 ThaliTest[931:1158926] server session: not connected Apple-Iphone6-1_PT9995
,2015-12-14 15:42:55.909 ThaliTest[931:1158855] server session: connected
2015-12-14 15:42:55.909 ThaliTest[931:1158855] server session: stateChange:1->2 Apple-IpadAir2-1_PT4459
,2015-12-14 15:42:55.948 ThaliTest[931:1157953] server relay: connected (to port: 57627)
,2015-12-14T14:42:55.956Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T14:42:56.228Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-14T14:42:56.246Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-14T14:42:56.260Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-14T14:42:56.277Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
2015-12-14 15:42:56.279 ThaliTest[931:1158925] client session: connected
2015-12-14 15:42:56.279 ThaliTest[931:1158925] client session: stateChange:1->2 Apple-I,padAir2-1_PT4459.LRQ+wA==
,2015-12-14T14:42:56.295Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-14 15:42:56.312 ThaliTest[931:1158854] client session: fireConnectCallback: Apple-IpadAir2-1_PT4459.LRQ+wA==
,2015-12-14 15:42:56.315 ThaliTest[931:1158854] jxcore: connect: success
,2015-12-14T14:42:56.319Z SendDataConnector.js: CLIENT connected to 57641, error: null
,2015-12-14T14:42:56.320Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 15:42:56.322 ThaliTest[931:1157953] client: relay established
2015-12-14 15:42:56.323 ThaliTest[931:1157953] client: new accepted socket: 0x1949f240
,2015-12-14T14:42:56.336Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14T14:42:56.339Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14 15:42:56.412 ThaliTest[931:1158855] server session: not connected Apple-IpadAir2-1_PT4459
,2015-12-14T14:42:56.634Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-14T14:42:56.647Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T14:42:56.647Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-14T14:42:56.647Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T14:42:56.647Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 15:42:56.648 ThaliTest[931:1158169] jxcore: disconnect
,2015-12-14 15:42:56.649 ThaliTest[931:1158169] client session: disconnectFromPeer: Apple-IpadAir2-1_PT4459.LRQ+wA==
,2015-12-14 15:42:56.649 ThaliTest[931:1158169] client session: disconnect
,2015-12-14 15:42:56.650 ThaliTest[931:1158169] client session: stateChange:2->0 Apple-IpadAir2-1_PT4459.LRQ+wA==
,2015-12-14 15:42:56.718 ThaliTest[931:1158169] jxcore: disconnect: success
,2015-12-14T14:42:56.718Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT4459.LRQ+wA==
---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2015-12-14T14:42:56.722Z SendDataConnector.js: CLIENT Stop now
2015-12-14T14:42:56.722Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 15:43:22.890 ThaliTest[931:1157953] multipeer session: restart
,2015-12-14 15:43:32.549 ThaliTest[931:1157953] multipeer session: reset timer
2015-12-14 15:43:32.549 ThaliTest[931:1157953] multipeer session: stop timer
2015-12-14 15:43:32.549 ThaliTest[931:1157953] multipeer session: start timer: 0x19484250
,2015-12-14 15:43:32.550 ThaliTest[931:1157953] server session: connect
2015-12-14 15:43:32.550 ThaliTest[931:1157953] server session: stateChange:0->1 Apple-Iphone5-1_PT9827
,2015-12-14 15:43:32.562 ThaliTest[931:1157953] server: accepting invitation Apple-Iphone5-1_PT9827
,2015-12-14 15:43:35.594 ThaliTest[931:1159048] server session: connected
2015-12-14 15:43:35.595 ThaliTest[931:1159048] server session: stateChange:1->2 Apple-Iphone5-1_PT9827
,2015-12-14 15:43:35.653 ThaliTest[931:1157953] server relay: connected (to port: 57627)
2015-12-14T14:43:35.659Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T14:43:36.145Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-14T14:43:36.162Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-14T14:43:36.179Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-14T14:43:36.199Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-14T14:43:36.218Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-14T14:43:36.236Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 15:43:36.286 ThaliTest[931:1159063] server session: not connected Apple-Iphone5-1_PT9827
,teardown
,testSendData stopped
,2015-12-14 15:43:46.855 ThaliTest[931:1158169] jxcore: stopBroadcasting
2015-12-14 15:43:46.856 ThaliTest[931:1158169] THEMultipeerSession stopping peer
2015-12-14 15:43:46.857 ThaliTest[931:1158169] multipeer session: stop timer
2015-12-14 15:43:46.857, ThaliTest[931:1158169] server session: disconnect
2015-12-14 15:43:46.858 ThaliTest[931:1158169] server session: stateChange:2->0 Apple-Iphone6-1_PT9995
,2015-12-14 15:43:46.867 ThaliTest[931:1158169] server session: disconnect
2015-12-14 15:43:46.867 ThaliTest[931:1158169] server session: stateChange:2->0 Apple-IpadAir2-1_PT4459
2015-12-14 15:43:46.875 ThaliTest[931:1158169] server session: disconnect
2,015-12-14 15:43:46.876 ThaliTest[931:1158169] server session: stateChange:2->0 Apple-Iphone5-1_PT9827
,2015-12-14 15:43:46.895 ThaliTest[931:1158169] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-14T14:43:46.921Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T14:43:46.934Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T14:43:46.938Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T14:43:46.942Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
