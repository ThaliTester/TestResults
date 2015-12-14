#### Test 50650278b2f31ec_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278b2f31ec/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/5A06355B-4BEF-479A-9E31-03E0A772DA1B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/5A06355B-4BEF-479A-9E31-03E0A772DA1B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278b2f31ec/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278b2f31ec/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EE4C848A-14B5-41B0-99E7-3F597051E003/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55245"
,(lldb)     command script import "/tmp/5A06355B-4BEF-479A-9E31-03E0A772DA1B/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-14 15:37:16.353 ThaliTest[1010:1131680] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B39BC134-0926-4D06-9C66-4752F2D3E2FA/Library/Cookies/Cookies.binarycookies
,2015-12-14 15:37:16.370 ThaliTest[1010:1131680] <CATransformLayer: 0x15d5e560> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-14 15:37:16.371 ThaliTest[1010:1131680] <CATransformLayer: 0x15d601b0> - changing propert,y masksToBounds in transform-only layer, will have no effect
2015-12-14 15:37:16.372 ThaliTest[1010:1131680] <CATransformLayer: 0x15d61320> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-14 15:37:16.665 ThaliTest[1010:1131680] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-14 15:37:16.666 ThaliTest[1010:1131680] Multi-tasking -> Device: YES, App: YES
,2015-12-14 15:37:16.673 ThaliTest[1010:1131680] Unlimited access to network resources
,2015-12-14 15:37:16.679 ThaliTest[1010:1131680] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-14 15:37:25.445 ThaliTest[1010:1131680] Resetting plugins due to page load.
,2015-12-14 15:37:28.785 ThaliTest[1010:1131680] Finished load of: file:///var/mobile/Containers/Bundle/Application/EE4C848A-14B5-41B0-99E7-3F597051E003/ThaliTest.app/www/index.html
,2015-12-14 15:37:28.927 ThaliTest[1010:1131680] JXcore Cordova plugin initializing
,2015-12-14 15:37:28.928 ThaliTest[1010:1131937] JXcore instance initializing
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
,2015-12-14 15:37:29.946 ThaliTest[1010:1131680] THREAD WARNING: ['JXcore'] took '83.821045' ms. Plugin should use a background thread.
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-14 15:42:01.857 ThaliTest[1010:1131937] jxcore: startBroadcasting
,2015-12-14 15:42:01.873 ThaliTest[1010:1131937] server: starting Apple-IpadAir2-1_PT4459.Sbdxaw==
,2015-12-14 15:42:01.876 ThaliTest[1010:1131937] multipeer session: start timer: 0x17e52390
2015-12-14 15:42:01.877 ThaliTest[1010:1131937] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT4459
,2015-12-14 15:42:01.879 ThaliTest[1010:1131937] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-14 15:42:02.907 ThaliTest[1010:1131680] client: found peer: Apple-Iphone6-1_PT9995.u0gQiQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9995.u0gQiQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT9995.u0gQiQ==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-14 15:42:02.970 ThaliTest[1010:1131680] client: found peer: Apple-Iphone5-1_PT9827.emG9ZA==
,teardown
,testFindPeers stopped
,2015-12-14 15:42:03.774 ThaliTest[1010:1131937] jxcore: stopBroadcasting
,2015-12-14 15:42:03.774 ThaliTest[1010:1131937] THEMultipeerSession stopping peer
,2015-12-14 15:42:03.775 ThaliTest[1010:1131937] multipeer session: stop timer
,2015-12-14 15:42:03.776 ThaliTest[1010:1131937] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 57026
,2015-12-14 15:42:03.838 ThaliTest[1010:1131937] jxcore: startBroadcasting
,2015-12-14 15:42:03.841 ThaliTest[1010:1131937] server: starting Apple-IpadAir2-1_PT4459.LRQ+wA==
2015-12-14 15:42:03.842 ThaliTest[1010:1131937] multipeer session: start timer: 0x15fd6360
2015-12-14 15:42:03.843 ThaliTest[1010:1131937] THEMultipeerSessi,on initialized peer Apple-IpadAir2-1_PT4459
2015-12-14 15:42:03.843 ThaliTest[1010:1131937] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
,2015-12-14T14:42:03.848Z SendDataTCPServer.js: TCP/IP server is bound to port: 57026
,2015-12-14 15:42:04.813 ThaliTest[1010:1131680] client: found peer: Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:04.814 ThaliTest[1010:1131680] client: found peer: Apple-Iphone6-1_PT9995.u0gQiQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9827.emG9ZA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14T14:42:04.819Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14T14:42:04.820Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14T14:42:04.820Z SendDataConnector.js: do connect now
,2015-12-14 15:42:04.822 ThaliTest[1010:1131937] jxcore: connect Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14 15:42:04.822 ThaliTest[1010:1131937] client session: connect
,2015-12-14 15:42:04.823 ThaliTest[1010:1131937] client session: stateChange:0->1 Apple-Iphone5-1_PT9827.emG9ZA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9995.u0gQiQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-14 15:42:04.950 ThaliTest[1010:1131680] client: lost peer: Apple-Iphone6-1_PT9995.u0gQiQ==
,2015-12-14 15:42:04.950 ThaliTest[1010:1131680] client session: onPeerLost: Apple-Iphone6-1_PT9995.u0gQiQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9995.u0gQiQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-14 15:42:05.059 ThaliTest[1010:1131680] client: found peer: Apple-Iphone6-1_PT9995.Xv3OoQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9995.Xv3OoQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 15:42:05.671 ThaliTest[1010:1131680] client: lost peer: Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:05.671 ThaliTest[1010:1131680] client session: onPeerLost: Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:05.671 ThaliTest[1010:1131680] client session: onLinkFailure: Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:05.671 ThaliTest[1010:1131680] client session: disconnect
2015-12-14 15:42:05.672 ThaliTest[1010:1131680] client session: stateChange:1->0 Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14 15:42:05.672 ThaliTest[1010:1131680] client session: fireConnectCallback: Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:05.673 ThaliTest[1010:1131680] jxcore: connect: fail: Peer disconnected
,2015-12-14T14:42:05.675Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-12-14T14:42:05.675Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-14T14:42:05.677Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9827.emG9ZA==","peerName":"(null)","peerAvailable":false}]
,2015-12-14 15:42:05.701 ThaliTest[1010:1131680] client: found peer: Apple-Iphone5-1_PT9827.8xg46g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9827.8xg46g==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-14 15:42:06.564 ThaliTest[1010:1131680] client: found peer: Apple-Iphone5s-1_PT2942.N5Uy6w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT2942.N5Uy6w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14T14:42:10.679Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14T14:42:10.680Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14 15:42:15.694 ThaliTest[1010:1131937] jxcore: disconnect
,2015-12-14 15:42:15.694 ThaliTest[1010:1131937] jxcore: disconnect: fail
,2015-12-14T14:42:15.696Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14T14:42:15.696Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT9827.emG9ZA== with availability status: true
,2015-12-14T14:42:15.696Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14T14:42:15.697Z SendDataConnector.js: do connect now
,2015-12-14 15:42:15.699 ThaliTest[1010:1131937] jxcore: connect Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14 15:42:15.699 ThaliTest[1010:1131937] client: connect: unreachable Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14 15:42:15.700 ThaliTest[1010:1131937] jxcore: connect: fail: Peer unreachable
,2015-12-14T14:42:15.701Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T14:42:15.701Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T14:42:15.702Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T14:42:20.705Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14T14:42:20.706Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14 15:42:25.706 ThaliTest[1010:1131937] jxcore: disconnect
,2015-12-14 15:42:25.707 ThaliTest[1010:1131937] jxcore: disconnect: fail
,2015-12-14T14:42:25.708Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14T14:42:25.709Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT9827.emG9ZA== with availability status: true
,2015-12-14T14:42:25.709Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14T14:42:25.710Z SendDataConnector.js: do connect now
,2015-12-14 15:42:25.711 ThaliTest[1010:1131937] jxcore: connect Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14 15:42:25.712 ThaliTest[1010:1131937] client: connect: unreachable Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14 15:42:25.713 ThaliTest[1010:1131937] jxcore: connect: fail: Peer unreachable
,2015-12-14T14:42:25.713Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T14:42:25.714Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T14:42:25.715Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T14:42:30.727Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14T14:42:30.728Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14 15:42:33.844 ThaliTest[1010:1131680] multipeer session: restart
,2015-12-14 15:42:33.874 ThaliTest[1010:1131680] client: found peer: Apple-Iphone5s-1_PT2942.N5Uy6w==
2015-12-14 15:42:33.874 ThaliTest[1010:1131680] client: found peer: Apple-Iphone5-1_PT9827.8xg46g==
2015-12-14 15:42:33.874 ThaliTest[1010:1131680] clien,t: found peer: Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14 15:42:35.740 ThaliTest[1010:1131937] jxcore: disconnect
2015-12-14 15:42:35.741 ThaliTest[1010:1131937] jxcore: disconnect: fail
,2015-12-14T14:42:35.742Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14T14:42:35.742Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT9827.emG9ZA== with availability status: true
,2015-12-14T14:42:35.742Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14T14:42:35.743Z SendDataConnector.js: do connect now
,2015-12-14 15:42:35.744 ThaliTest[1010:1131937] jxcore: connect Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:35.745 ThaliTest[1010:1131937] client: connect: unreachable Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14 15:42:35.745 ThaliTest[1010:1131937] jxcore: connect: fail: Peer unreachable
,2015-12-14T14:42:35.746Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T14:42:35.747Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T14:42:35.747Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T14:42:40.756Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14T14:42:40.756Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14 15:42:45.618 ThaliTest[1010:1131680] multipeer session: reset timer
,2015-12-14 15:42:45.619 ThaliTest[1010:1131680] multipeer session: stop timer
,2015-12-14 15:42:45.619 ThaliTest[1010:1131680] multipeer session: start timer: 0x15fd6360
,2015-12-14 15:42:45.619 ThaliTest[1010:1131680] server session: connect
2015-12-14 15:42:45.620 ThaliTest[1010:1131680] server session: stateChange:0->1 Apple-Iphone6-1_PT9995
,2015-12-14 15:42:45.626 ThaliTest[1010:1131680] server: accepting invitation Apple-Iphone6-1_PT9995
,2015-12-14 15:42:45.768 ThaliTest[1010:1131937] jxcore: disconnect
2015-12-14 15:42:45.769 ThaliTest[1010:1131937] jxcore: disconnect: fail
2015-12-14T14:42:45.769Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9827.emG9Z,A==
2015-12-14T14:42:45.770Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT9827.emG9ZA== with availability status: true
2015-12-14T14:42:45.770Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9827.emG9ZA==
2,015-12-14T14:42:45.770Z SendDataConnector.js: do connect now
2015-12-14 15:42:45.770 ThaliTest[1010:1131937] jxcore: connect Apple-Iphone5-1_PT9827.emG9ZA==
,2015-12-14 15:42:45.771 ThaliTest[1010:1131937] client: connect: unreachable Apple-Iphone5-1_PT9827.emG9ZA==
2015-12-14 15:42:45.772 ThaliTest[1010:1131937] jxcore: connect: fail: Peer unreachable
2015-12-14T14:42:45.772Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T14:42:45.772Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2015-12-14T14:42:45.774Z SendDataConnector.js: CLIENT Stop now
,2015-12-14 15:42:45.775 ThaliTest[1010:1131937] jxcore: disconnect
2015-12-14 15:42:45.775 ThaliTest[1010:1131937] jxcore: disconnect: fail
2015-12-14T14:42:45.775Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9827.emG9ZA==
---- round done--------
startWithNextDevice
,device[2]: Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14T14:42:45.778Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14T14:42:45.778Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14T14:42:45.779Z SendDataConnector.js: do connect now
,2015-12-14 15:42:45.779 ThaliTest[1010:1131937] jxcore: connect Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14 15:42:45.780 ThaliTest[1010:1131937] client session: connect
2015-12-14 15:42:45.780 ThaliTest[1010:1131937] client session: stateChange:0->1 Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14 15:42:48.709 ThaliTest[1010:1132879] client session: connected
2015-12-14 15:42:48.709 ThaliTest[1010:1132879] client session: stateChange:1->2 Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14 15:42:48.710 ThaliTest[1010:1132877] server session: connected
,2015-12-14 15:42:48.710 ThaliTest[1010:1132877] server session: stateChange:1->2 Apple-Iphone6-1_PT9995
,2015-12-14 15:42:48.803 ThaliTest[1010:1132877] client session: fireConnectCallback: Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14 15:42:48.804 ThaliTest[1010:1132877] jxcore: connect: success
,2015-12-14 15:42:48.808 ThaliTest[1010:1131680] server relay: connected (to port: 57026)
2015-12-14T14:42:48.808Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T14:42:48.811Z SendDataConnector.js: CLIENT connected to 57031, error: null
,2015-12-14T14:42:48.812Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 15:42:48.816 ThaliTest[1010:1131680] client: relay established
2015-12-14 15:42:48.816 ThaliTest[1010:1131680] client: new accepted socket: 0x17e6a340
,2015-12-14T14:42:48.833Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T14:42:49.082Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-14T14:42:49.145Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-14T14:42:49.156Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-14T14:42:49.194Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14T14:42:49.195Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-14T14:42:49.208Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T14:42:49.209Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T14:42:49.209Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T14:42:49.209Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 15:42:49.210 ThaliTest[1010:1131937] jxcore: disconnect
,2015-12-14 15:42:49.210 ThaliTest[1010:1131937] client session: disconnectFromPeer: Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14 15:42:49.210 ThaliTest[1010:1131937] client session: disconnect
2015-12-14 15:42:49.211 ThaliTest[1010:1131937] client session: stateChange:2->0 Apple-Iphone6-1_PT9995.Xv3OoQ==
,2015-12-14 15:42:49.213 ThaliTest[1010:1131937] jxcore: disconnect: success
2015-12-14T14:42:49.214Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9995.Xv3OoQ==
---- round done--------
,startWithNextDevice
device[3]: Apple-Iphone5-1_PT9827.8xg46g==
2015-12-14T14:42:49.215Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9827.8xg46g==
2015-12-14T14:42:49.215Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9827.8xg46g==
2015-12-14T14:42:49.215Z SendDataConnector.js: do connect now
2015-12-14 15:42:49.215 ThaliTest[1010:1131937] jxcore: connect Apple-Iphone5-1_PT9827.8xg46g==
,2015-12-14 15:42:49.215 ThaliTest[1010:1131937] client session: connect
2015-12-14 15:42:49.215 ThaliTest[1010:1131937] client session: stateChange:0->1 Apple-Iphone5-1_PT9827.8xg46g==
,2015-12-14 15:42:49.257 ThaliTest[1010:1132876] server session: not connected Apple-Iphone6-1_PT9995
,2015-12-14 15:42:53.713 ThaliTest[1010:1132876] client session: connected
,2015-12-14 15:42:53.714 ThaliTest[1010:1132876] client session: stateChange:1->2 Apple-Iphone5-1_PT9827.8xg46g==
,2015-12-14 15:42:53.719 ThaliTest[1010:1132876] client session: fireConnectCallback: Apple-Iphone5-1_PT9827.8xg46g==
2015-12-14 15:42:53.719 ThaliTest[1010:1132876] jxcore: connect: success
,2015-12-14T14:42:53.722Z SendDataConnector.js: CLIENT connected to 57035, error: null
,2015-12-14T14:42:53.722Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 15:42:53.725 ThaliTest[1010:1131680] client: relay established
2015-12-14 15:42:53.725 ThaliTest[1010:1131680] client: new accepted socket: 0x17e6fc10
,2015-12-14T14:42:53.740Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T14:42:54.014Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-14T14:42:54.037Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-14T14:42:54.050Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T14:42:54.051Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T14:42:54.051Z SendDataConnector.js: CLIENT Stop now
2015-12-14T14:42:54.051Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 15:42:54.052 ThaliTest[1010:1131937] jxcore: disconnect
,2015-12-14 15:42:54.052 ThaliTest[1010:1131937] client session: disconnectFromPeer: Apple-Iphone5-1_PT9827.8xg46g==
2015-12-14 15:42:54.052 ThaliTest[1010:1131937] client session: disconnect
,2015-12-14 15:42:54.052 ThaliTest[1010:1131937] client session: stateChange:2->0 Apple-Iphone5-1_PT9827.8xg46g==
,2015-12-14 15:42:54.055 ThaliTest[1010:1131937] jxcore: disconnect: success
2015-12-14T14:42:54.055Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9827.8xg46g==
---- round done--------
startWithNextDevice
device[4]: App,le-Iphone5s-1_PT2942.N5Uy6w==
2015-12-14T14:42:54.056Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT2942.N5Uy6w==
2015-12-14T14:42:54.056Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT2942.N5Uy6w==
2015-12-14T14:42:54.056Z SendDataConnector.js: do connect now
2015-12-14 15:42:54.056 ThaliTest[1010:1131937] jxcore: connect Apple-Iphone5s-1_PT2942.N5Uy6w==
2015-12-14 15:42:54.056 ThaliTest[1010:1131937] client session: connect
2015-12-14 15:42:54.056 ThaliTest[1,010:1131937] client session: stateChange:0->1 Apple-Iphone5s-1_PT2942.N5Uy6w==
,2015-12-14 15:42:54.319 ThaliTest[1010:1131680] multipeer session: reset timer
2015-12-14 15:42:54.319 ThaliTest[1010:1131680] multipeer session: stop timer
2015-12-14 15:42:54.319 ThaliTest[1010:1131680] multipeer session: start timer: 0x15fd6360
2015-12-14 15:42:54.319 ThaliTest[1010:1131680] server session: connect
,2015-12-14 15:42:54.320 ThaliTest[1010:1131680] server session: stateChange:0->1 Apple-Iphone5s-1_PT2942
,2015-12-14 15:42:54.323 ThaliTest[1010:1131680] server: accepting invitation Apple-Iphone5s-1_PT2942
,2015-12-14 15:42:57.174 ThaliTest[1010:1132879] client session: connected
2015-12-14 15:42:57.174 ThaliTest[1010:1132879] client session: stateChange:1->2 Apple-Iphone5s-1_PT2942.N5Uy6w==
,2015-12-14 15:42:57.179 ThaliTest[1010:1132877] client session: fireConnectCallback: Apple-Iphone5s-1_PT2942.N5Uy6w==
2015-12-14 15:42:57.179 ThaliTest[1010:1132877] jxcore: connect: success
,2015-12-14T14:42:57.181Z SendDataConnector.js: CLIENT connected to 57038, error: null
,2015-12-14T14:42:57.182Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 15:42:57.184 ThaliTest[1010:1131680] client: relay established
2015-12-14 15:42:57.185 ThaliTest[1010:1131680] client: new accepted socket: 0x17e70890
,2015-12-14T14:42:57.198Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T14:42:57.515Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-14 15:42:57.523 ThaliTest[1010:1132879] server session: connected
,2015-12-14 15:42:57.524 ThaliTest[1010:1132879] server session: stateChange:1->2 Apple-Iphone5s-1_PT2942
,2015-12-14T14:42:57.527Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-14 15:42:57.543 ThaliTest[1010:1131680] server relay: connected (to port: 57026)
,2015-12-14T14:42:57.552Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-14T14:42:57.553Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T14:42:57.587Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-14T14:42:57.645Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T14:42:57.645Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-14T14:42:57.645Z SendDataConnector.js: CLIENT Stop now
2015-12-14T14:42:57.646Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 15:42:57.646 ThaliTest[1010:1131937] jxcore: disconnect
2015-12-14 15:42:57.646 ThaliTest[1010:1131937] client session: disconnectFromPeer: Apple-Iphone5s-1_PT2942.N5Uy6w==
,2015-12-14 15:42:57.646 ThaliTest[1010:1131937] client session: disconnect
,2015-12-14 15:42:57.646 ThaliTest[1010:1131937] client session: stateChange:2->0 Apple-Iphone5s-1_PT2942.N5Uy6w==
,2015-12-14 15:42:57.650 ThaliTest[1010:1131937] jxcore: disconnect: success
2015-12-14T14:42:57.650Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT2942.N5Uy6w==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
,sendReportNow
done, now sending data to server
,2015-12-14T14:42:57.653Z SendDataConnector.js: CLIENT Stop now
2015-12-14T14:42:57.653Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14T14:42:57.852Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-14T14:42:57.865Z SendDataTCPServer.js: TCP/IP server has received 56656 bytes of data
,2015-12-14T14:42:57.882Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 15:42:57.937 ThaliTest[1010:1132924] server session: not connected Apple-Iphone5s-1_PT2942
,2015-12-14 15:43:24.321 ThaliTest[1010:1131680] multipeer session: restart
,2015-12-14 15:43:24.350 ThaliTest[1010:1131680] client: found peer: Apple-Iphone6-1_PT9995.Xv3OoQ==
2015-12-14 15:43:24.350 ThaliTest[1010:1131680] client: found peer: Apple-Iphone5-1_PT9827.8xg46g==
2015-12-14 15:43:24.351 ThaliTest[1010:1131680] client: found peer: Apple-Iphone5s-1_PT2942.N5Uy6w==
,2015-12-14 15:43:29.988 ThaliTest[1010:1131680] multipeer session: reset timer
2015-12-14 15:43:29.989 ThaliTest[1010:1131680] multipeer session: stop timer
2015-12-14 15:43:29.989 ThaliTest[1010:1131680] multipeer session: start timer: 0x15fd6360
,2015-12-14 15:43:29.989 ThaliTest[1010:1131680] server session: connect
2015-12-14 15:43:29.990 ThaliTest[1010:1131680] server session: stateChange:0->1 Apple-Iphone5-1_PT9827
,2015-12-14 15:43:29.996 ThaliTest[1010:1131680] server: accepting invitation Apple-Iphone5-1_PT9827
,2015-12-14 15:43:32.975 ThaliTest[1010:1132943] server session: connected
2015-12-14 15:43:32.976 ThaliTest[1010:1132943] server session: stateChange:1->2 Apple-Iphone5-1_PT9827
,2015-12-14 15:43:32.981 ThaliTest[1010:1131680] server relay: connected (to port: 57026)
,2015-12-14T14:43:32.991Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T14:43:33.551Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-14T14:43:33.567Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-14T14:43:33.586Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-14T14:43:33.603Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 15:43:33.644 ThaliTest[1010:1132943] server session: not connected Apple-Iphone5-1_PT9827
,teardown
,testSendData stopped
,2015-12-14 15:43:38.060 ThaliTest[1010:1131937] jxcore: stopBroadcasting
,2015-12-14 15:43:38.060 ThaliTest[1010:1131937] THEMultipeerSession stopping peer
,2015-12-14 15:43:38.061 ThaliTest[1010:1131937] multipeer session: stop timer
,2015-12-14 15:43:38.064 ThaliTest[1010:1131937] server session: disconnect
2015-12-14 15:43:38.064 ThaliTest[1010:1131937] server session: stateChange:2->0 Apple-Iphone6-1_PT9995
,2015-12-14 15:43:38.077 ThaliTest[1010:1131937] server session: disconnect
2015-12-14 15:43:38.077 ThaliTest[1010:1131937] server session: stateChange:2->0 Apple-Iphone5s-1_PT2942
,2015-12-14 15:43:38.085 ThaliTest[1010:1131937] server session: disconnect
2015-12-14 15:43:38.086 ThaliTest[1010:1131937] server session: stateChange:2->0 Apple-Iphone5-1_PT9827
,2015-12-14 15:43:38.096 ThaliTest[1010:1131937] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-14T14:43:38.115Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T14:43:38.117Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T14:43:38.118Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T14:43:38.120Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
