#### Test 506502782ddd83f_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502782ddd83f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/02B6BD7A-D118-4C61-8B2E-EB324459A54B/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/02B6BD7A-D118-4C61-8B2E-EB324459A54B/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502782ddd83f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502782ddd83f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6938B67F-7C9D-469B-9ADE-CDAACEE5DF31/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56378"
,(lldb)     command script import "/tmp/02B6BD7A-D118-4C61-8B2E-EB324459A54B/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-15 05:40:09.567 ThaliTest[891:1375354] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/931E5F2A-8CAE-414E-BD1D-6A01FADC27EB/Library/Cookies/Cookies.binarycookies
,2015-12-15 05:40:10.067 ThaliTest[891:1375354] Apache Cordova native platform version 3.9.2 is starting.
2015-12-15 05:40:10.069 ThaliTest[891:1375354] Multi-tasking -> Device: YES, App: YES
,2015-12-15 05:40:10.075 ThaliTest[891:1375354] Unlimited access to network resources
,2015-12-15 05:40:10.085 ThaliTest[891:1375354] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-15 05:40:20.534 ThaliTest[891:1375354] Resetting plugins due to page load.
,2015-12-15 05:40:24.141 ThaliTest[891:1375354] Finished load of: file:///var/mobile/Containers/Bundle/Application/6938B67F-7C9D-469B-9ADE-CDAACEE5DF31/ThaliTest.app/www/index.html
,2015-12-15 05:40:24.345 ThaliTest[891:1375354] JXcore Cordova plugin initializing
,2015-12-15 05:40:24.346 ThaliTest[891:1375553] JXcore instance initializing
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
,2015-12-15 05:40:26.776 ThaliTest[891:1375354] THREAD WARNING: ['JXcore'] took '155.060059' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-15 05:46:55.909 ThaliTest[891:1375553] jxcore: startBroadcasting
,2015-12-15 05:46:55.920 ThaliTest[891:1375553] server: starting Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15 05:46:55.921 ThaliTest[891:1375553] multipeer session: start timer: 0x1d41de60
2015-12-15 05:46:55.922 ThaliTest[891:1375553] THEMultipeerSession initialized peer Apple-Iphone5-1_PT356
2015-12-15 05:46:55.922 ThaliTest[891:1375553] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-15 05:46:56.909 ThaliTest[891:1375354] client: found peer: Apple-IpadAir2-1_PT2678.RP+Etw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2678.RP+Etw==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1_PT2678.RP+Etw==, peerAvailable: true
weAreDoneNow
,done, now sending data to server
,2015-12-15 05:46:58.094 ThaliTest[891:1375354] client: found peer: Apple-Iphone6-1_PT7824.Q97KpQ==
,teardown
,testFindPeers stopped
,2015-12-15 05:46:58.948 ThaliTest[891:1375553] jxcore: stopBroadcasting
2015-12-15 05:46:58.948 ThaliTest[891:1375553] THEMultipeerSession stopping peer
2015-12-15 05:46:58.948 ThaliTest[891:1375553] multipeer session: stop timer
2015-12-15 05:46:58.949 ThaliTest[891:1375553] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 60242
,2015-12-15 05:46:59.012 ThaliTest[891:1375553] jxcore: startBroadcasting
,2015-12-15 05:46:59.015 ThaliTest[891:1375553] server: starting Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:46:59.015 ThaliTest[891:1375553] multipeer session: start timer: 0x1d423da0
2015-12-15 05:46:59.016 ThaliTest[891:1375553] THEMultipeerSession in,itialized peer Apple-Iphone5-1_PT356
2015-12-15 05:46:59.016 ThaliTest[891:1375553] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2015-12-15T04:46:59.019Z SendDataTCPServer.js: TCP/IP server is bound to port: 60242
,2015-12-15 05:46:59.486 ThaliTest[891:1375354] client: found peer: Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15 05:46:59.486 ThaliTest[891:1375354] client: found peer: Apple-Iphone5-1_PT356.zzR6Ww==
2015-12-15 05:46:59.486 ThaliTest[891:1375354] client: fo,und peer: Apple-IpadAir2-1_PT2678.RP+Etw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7824.Q97KpQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone6-1_PT782,4.Q97KpQ==
2015-12-15T04:46:59.489Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15T04:46:59.490Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15T04:46:59.490Z SendDataC,onnector.js: do connect now
2015-12-15 05:46:59.491 ThaliTest[891:1375553] jxcore: connect Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15 05:46:59.491 ThaliTest[891:1375553] client session: connect
2015-12-15 05:46:59.491 ThaliTest[891:1375553] client sessi,on: stateChange:0->1 Apple-Iphone6-1_PT7824.Q97KpQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT356.zzR6Ww==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2678.RP+Etw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 05:47:00.755 ThaliTest[891:1375354] client: lost peer: Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15 05:47:00.756 ThaliTest[891:1375354] client session: onPeerLost: Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15 05:47:00.756 ThaliTest[891:1375354] cl,ient session: onLinkFailure: Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15 05:47:00.756 ThaliTest[891:1375354] client session: disconnect
2015-12-15 05:47:00.757 ThaliTest[891:1375354] client session: stateChange:1->0 Apple-Iphone6-1_PT7824.Q97KpQ==
2015-1,2-15 05:47:00.757 ThaliTest[891:1375354] client session: fireConnectCallback: Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15 05:47:00.757 ThaliTest[891:1375354] jxcore: connect: fail: Peer disconnected
,2015-12-15T04:47:00.758Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-15T04:47:00.759Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-15T04:47:00.760Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7824.Q97KpQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-15 05:47:00.856 ThaliTest[891:1375354] client: lost peer: Apple-Iphone5-1_PT356.zzR6Ww==
2015-12-15 05:47:00.857 ThaliTest[891:1375354] client session: onPeerLost: Apple-Iphone5-1_PT356.zzR6Ww==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT356.zzR6Ww==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2015-12-15 05:47:01.041 ThaliTest[891:1375354] client: lost peer: Apple-IpadAir2-1_PT2678.RP+Etw==
2015-12-15 05:47:01.041 ThaliTest[891:1375354] client session: onPeerLost: Apple-IpadAir2-1_PT2678.RP+Etw==
2015-12-15 05:47:01.041 ThaliTest[891:1375354] ,client: found peer: Apple-IpadAir2-1_PT2678.ad0lIQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2678.RP+Etw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifie,r":"Apple-IpadAir2-1_PT2678.ad0lIQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 05:47:01.178 ThaliTest[891:1375354] client: found peer: Apple-Iphone6-1_PT7824.jNC0Kw==
2015-12-15 05:47:01.179 ThaliTest[891:1375354] client: found peer: Apple-Iphone5s-1_PT4162.hYB3TQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphon,e6-1_PT7824.jNC0Kw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4162.hYB3TQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15T04:47:05.761Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7824.Q97KpQ==
,2015-12-15T04:47:05.762Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7824.Q97KpQ==
,2015-12-15 05:47:10.774 ThaliTest[891:1375553] jxcore: disconnect
2015-12-15 05:47:10.775 ThaliTest[891:1375553] jxcore: disconnect: fail
2015-12-15T04:47:10.776Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7824.Q97KpQ=,=
2015-12-15T04:47:10.776Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT7824.Q97KpQ== with availability status: true
2015-12-15T04:47:10.776Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15T04:47:10.777Z SendDataConnector.js: do connect now
,2015-12-15 05:47:10.778 ThaliTest[891:1375553] jxcore: connect Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15 05:47:10.778 ThaliTest[891:1375553] client: connect: unreachable Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15 05:47:10.778 ThaliTest[891:1375553] jxcore: connect: fail: Peer unreachable
,2015-12-15T04:47:10.779Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-15T04:47:10.780Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T04:47:10.780Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:47:15.780Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7824.Q97KpQ==
,2015-12-15T04:47:15.781Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7824.Q97KpQ==
,2015-12-15 05:47:20.792 ThaliTest[891:1375553] jxcore: disconnect
2015-12-15 05:47:20.793 ThaliTest[891:1375553] jxcore: disconnect: fail
2015-12-15T04:47:20.793Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7824.Q97KpQ=,=
2015-12-15T04:47:20.794Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT7824.Q97KpQ== with availability status: true
2015-12-15T04:47:20.794Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15T04:47:20.795Z SendDataConnector.js: do connect now
,2015-12-15 05:47:20.795 ThaliTest[891:1375553] jxcore: connect Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15 05:47:20.796 ThaliTest[891:1375553] client: connect: unreachable Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15 05:47:20.796 ThaliTest[891:1375553] jxco,re: connect: fail: Peer unreachable
,2015-12-15T04:47:20.797Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:47:20.797Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T04:47:20.798Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:47:25.802Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7824.Q97KpQ==
,2015-12-15T04:47:25.803Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7824.Q97KpQ==
,2015-12-15 05:47:29.017 ThaliTest[891:1375354] multipeer session: restart
,2015-12-15 05:47:29.051 ThaliTest[891:1375354] client: found peer: Apple-Iphone6-1_PT7824.jNC0Kw==
2015-12-15 05:47:29.052 ThaliTest[891:1375354] client: found peer: Apple-IpadAir2-1_PT2678.ad0lIQ==
2015-12-15 05:47:29.052 ThaliTest[891:1375354] client: found peer: Apple-Iphone5s-1_PT4162.hYB3TQ==
,2015-12-15 05:47:30.813 ThaliTest[891:1375553] jxcore: disconnect
2015-12-15 05:47:30.814 ThaliTest[891:1375553] jxcore: disconnect: fail
2015-12-15T04:47:30.814Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7824.Q97KpQ=,=
2015-12-15T04:47:30.815Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT7824.Q97KpQ== with availability status: true
2015-12-15T04:47:30.815Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7824.Q97KpQ==
,2015-12-15T04:47:30.815Z SendDataConnector.js: do connect now
2015-12-15 05:47:30.816 ThaliTest[891:1375553] jxcore: connect Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15 05:47:30.816 ThaliTest[891:1375553] client: connect: unreachable Apple-Iphone6-1_PT782,4.Q97KpQ==
2015-12-15 05:47:30.817 ThaliTest[891:1375553] jxcore: connect: fail: Peer unreachable
,2015-12-15T04:47:30.817Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:47:30.817Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-15T04:47:30.818Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:47:35.822Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7824.Q97KpQ==
,2015-12-15T04:47:35.823Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7824.Q97KpQ==
,2015-12-15 05:47:40.832 ThaliTest[891:1375553] jxcore: disconnect
2015-12-15 05:47:40.833 ThaliTest[891:1375553] jxcore: disconnect: fail
2015-12-15T04:47:40.833Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7824.Q97KpQ=,=
2015-12-15T04:47:40.834Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT7824.Q97KpQ== with availability status: true
2015-12-15T04:47:40.834Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7824.Q97KpQ==
,2015-12-15T04:47:40.834Z SendDataConnector.js: do connect now
2015-12-15 05:47:40.835 ThaliTest[891:1375553] jxcore: connect Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15 05:47:40.836 ThaliTest[891:1375553] client: connect: unreachable Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15 05:47:40.836 ThaliTest[891:1375553] jxcore: connect: fail: Peer unreachable
,2015-12-15T04:47:40.836Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:47:40.837Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2015-12-15T04:47:40.839Z SendDataConnector.js: CLIENT Stop now
,2015-12-15 05:47:40.839 ThaliTest[891:1375553] jxcore: disconnect
2015-12-15 05:47:40.839 ThaliTest[891:1375553] jxcore: disconnect: fail
2015-12-15T04:47:40.840Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7824.Q97KpQ=,=
---- round done--------
startWithNextDevice
,device[2]: Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15T04:47:40.842Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15T04:47:40.842Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15T04:47:40.842Z SendDataConnector.js: do connect now
,2015-12-15 05:47:40.843 ThaliTest[891:1375553] jxcore: connect Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15 05:47:40.843 ThaliTest[891:1375553] client session: connect
2015-12-15 05:47:40.844 ThaliTest[891:1375553] client session: stateChange:0->1 Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15 05:47:43.750 ThaliTest[891:1376890] client session: connected
2015-12-15 05:47:43.750 ThaliTest[891:1376890] client session: stateChange:1->2 Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15 05:47:43.768 ThaliTest[891:1376892] client session: fireConnectCallback: Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15 05:47:43.768 ThaliTest[891:1376892] jxcore: connect: success
,2015-12-15T04:47:43.770Z SendDataConnector.js: CLIENT connected to 60246, error: null
,2015-12-15T04:47:43.770Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 05:47:43.773 ThaliTest[891:1375354] client: relay established
2015-12-15 05:47:43.773 ThaliTest[891:1375354] client: new accepted socket: 0x1d431fc0
,2015-12-15T04:47:43.787Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T04:47:44.346Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-15T04:47:44.673Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T04:47:44.674Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-15T04:47:44.675Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T04:47:44.676Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:47:44.678 ThaliTest[891:1375553] jxcore: disconnect
2015-12-15 05:47:44.678 ThaliTest[891:1375553] client session: disconnectFromPeer: Apple-IpadAir2-1_PT2678.ad0lIQ==
2015-12-15 05:47:44.678 ThaliTest[891:1375553] client session: disconnect
2015-12-15 05:47:44.678 ThaliTest[891:1375553] client session: stateChange:2->0 Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15 05:47:44.689 ThaliTest[891:1375553] jxcore: disconnect: success
2015-12-15T04:47:44.692Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2678.ad0lIQ==
---- round done--------
startWithNextDevice
device[3]: App,le-Iphone6-1_PT7824.jNC0Kw==
2015-12-15T04:47:44.693Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7824.jNC0Kw==
2015-12-15T04:47:44.693Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7824.jNC0Kw==
2015-12-15T04:47,:44.693Z SendDataConnector.js: do connect now
2015-12-15 05:47:44.694 ThaliTest[891:1375553] jxcore: connect Apple-Iphone6-1_PT7824.jNC0Kw==
,2015-12-15 05:47:44.694 ThaliTest[891:1375553] client session: connect
2015-12-15 05:47:44.696 ThaliTest[891:1375553] client session: stateChange:0->1 Apple-Iphone6-1_PT7824.jNC0Kw==
,2015-12-15 05:47:48.038 ThaliTest[891:1376904] client session: connected
2015-12-15 05:47:48.038 ThaliTest[891:1376904] client session: stateChange:1->2 Apple-Iphone6-1_PT7824.jNC0Kw==
,2015-12-15 05:47:48.043 ThaliTest[891:1376904] client session: fireConnectCallback: Apple-Iphone6-1_PT7824.jNC0Kw==
2015-12-15 05:47:48.043 ThaliTest[891:1376904] jxcore: connect: success
2015-12-15T04:47:48.044Z SendDataConnector.js: CLIENT connected to, 60249, error: null
2015-12-15T04:47:48.044Z SendDataConnector.js: CLIENT starting client 
2015-12-15 05:47:48.047 ThaliTest[891:1375354] client: relay established
2015-12-15 05:47:48.047 ThaliTest[891:1375354] client: new accepted socket: 0x1d42f390
,2015-12-15T04:47:48.060Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15 05:47:48.454 ThaliTest[891:1375354] multipeer session: reset timer
2015-12-15 05:47:48.455 ThaliTest[891:1375354] multipeer session: stop timer
2015-12-15 05:47:48.455 ThaliTest[891:1375354] multipeer session: start timer: 0x1d423da0
2015-12-,15 05:47:48.456 ThaliTest[891:1375354] server session: connect
2015-12-15 05:47:48.457 ThaliTest[891:1375354] server session: stateChange:0->1 Apple-IpadAir2-1_PT2678
2015-12-15 05:47:48.464 ThaliTest[891:1375354] server: accepting invitation Apple-IpadAir2-1_PT2678
,2015-12-15T04:47:49.305Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T04:47:49.306Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2015-12-15T04:47:49.308Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T04:47:49.308Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:47:49.309 ThaliTest[891:1375553] jxcore: disconnect
2015-12-15 05:47:49.310 ThaliTest[891:1375553] client session: disconnectFromPeer: Apple-Iphone6-1_PT7824.jNC0Kw==
2015-12-15 05:47:49.310 ThaliTest[891:1375553] client session: disconnect,
2015-12-15 05:47:49.310 ThaliTest[891:1375553] client session: stateChange:2->0 Apple-Iphone6-1_PT7824.jNC0Kw==
,2015-12-15 05:47:49.320 ThaliTest[891:1375553] jxcore: disconnect: success
2015-12-15T04:47:49.320Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7824.jNC0Kw==
---- round done--------
startWithNextDevice
device[4]: Appl,e-Iphone5s-1_PT4162.hYB3TQ==
2015-12-15T04:47:49.321Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4162.hYB3TQ==
2015-12-15T04:47:49.321Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4162.hYB3TQ==
2015-12-15T04:,47:49.321Z SendDataConnector.js: do connect now
2015-12-15 05:47:49.322 ThaliTest[891:1375553] jxcore: connect Apple-Iphone5s-1_PT4162.hYB3TQ==
2015-12-15 05:47:49.322 ThaliTest[891:1375553] client session: connect
2015-12-15 05:47:49.322 ThaliTest[891:,1375553] client session: stateChange:0->1 Apple-Iphone5s-1_PT4162.hYB3TQ==
,2015-12-15 05:47:51.156 ThaliTest[891:1376891] server session: connected
2015-12-15 05:47:51.156 ThaliTest[891:1376891] server session: stateChange:1->2 Apple-IpadAir2-1_PT2678
,2015-12-15 05:47:51.174 ThaliTest[891:1375354] server relay: connected (to port: 60242)
,2015-12-15T04:47:51.178Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T04:47:51.423Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-15T04:47:51.439Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-15T04:47:51.455Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-15T04:47:51.469Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-15T04:47:51.484Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 05:47:51.578 ThaliTest[891:1376890] server session: not connected Apple-IpadAir2-1_PT2678
,2015-12-15 05:47:52.200 ThaliTest[891:1376890] client session: connected
2015-12-15 05:47:52.200 ThaliTest[891:1376890] client session: stateChange:1->2 Apple-Iphone5s-1_PT4162.hYB3TQ==
,2015-12-15 05:47:52.220 ThaliTest[891:1376891] client session: fireConnectCallback: Apple-Iphone5s-1_PT4162.hYB3TQ==
2015-12-15 05:47:52.220 ThaliTest[891:1376891] jxcore: connect: success
,2015-12-15T04:47:52.220Z SendDataConnector.js: CLIENT connected to 60253, error: null
2015-12-15T04:47:52.221Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 05:47:52.223 ThaliTest[891:1375354] client: relay established
2015-12-15 05:47:52.224 ThaliTest[891:1375354] client: new accepted socket: 0x1d43c140
,2015-12-15T04:47:52.236Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T04:47:52.769Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-15T04:47:53.041Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-15T04:47:53.053Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-15T04:47:53.080Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T04:47:53.081Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-15T04:47:53.082Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T04:47:53.083Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:47:53.083 ThaliTest[891:1375553] jxcore: disconnect
2015-12-15 05:47:53.084 ThaliTest[891:1375553] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4162.hYB3TQ==
2015-12-15 05:47:53.084 ThaliTest[891:1375553] client session: disconnect
2015-12-15 05:47:53.084 ThaliTest[891:1375553] client session: stateChange:2->0 Apple-Iphone5s-1_PT4162.hYB3TQ==
,2015-12-15 05:47:53.092 ThaliTest[891:1375553] jxcore: disconnect: success
2015-12-15T04:47:53.092Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4162.hYB3TQ==
---- round done--------
startWithNextDevice
weAreDoneNow, ,resultArray.length: 4
sendReportNow
done, now sending data to server
2015-12-15T04:47:53.097Z SendDataConnector.js: CLIENT Stop now
2015-12-15T04:47:53.097Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:48:18.457 ThaliTest[891:1375354] multipeer session: restart
,2015-12-15 05:48:21.482 ThaliTest[891:1375354] multipeer session: reset timer
2015-12-15 05:48:21.483 ThaliTest[891:1375354] multipeer session: stop timer
2015-12-15 05:48:21.483 ThaliTest[891:1375354] multipeer session: start timer: 0x1d423da0
2015-12-,15 05:48:21.483 ThaliTest[891:1375354] server session: connect
2015-12-15 05:48:21.483 ThaliTest[891:1375354] server session: stateChange:0->1 Apple-Iphone6-1_PT7824
,2015-12-15 05:48:21.490 ThaliTest[891:1375354] server: accepting invitation Apple-Iphone6-1_PT7824
,2015-12-15 05:48:21.608 ThaliTest[891:1375354] multipeer session: reset timer
2015-12-15 05:48:21.608 ThaliTest[891:1375354] multipeer session: stop timer
2015-12-15 05:48:21.609 ThaliTest[891:1375354] multipeer session: start timer: 0x1d423da0
2015-12-,15 05:48:21.610 ThaliTest[891:1375354] server session: connect
2015-12-15 05:48:21.610 ThaliTest[891:1375354] server session: stateChange:0->1 Apple-Iphone5s-1_PT4162
2015-12-15 05:48:21.617 ThaliTest[891:1375354] server: accepting invitation Apple-Iphone5s-1_PT4162
,2015-12-15 05:48:24.199 ThaliTest[891:1377035] server session: connected
2015-12-15 05:48:24.200 ThaliTest[891:1377035] server session: stateChange:1->2 Apple-Iphone6-1_PT7824
,2015-12-15 05:48:24.203 ThaliTest[891:1375354] server relay: connected (to port: 60242)
2015-12-15T04:48:24.207Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15 05:48:24.244 ThaliTest[891:1377016] server session: connected
,2015-12-15 05:48:24.244 ThaliTest[891:1377016] server session: stateChange:1->2 Apple-Iphone5s-1_PT4162
,2015-12-15 05:48:24.261 ThaliTest[891:1375354] server relay: connected (to port: 60242)
,2015-12-15T04:48:24.269Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T04:48:24.566Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-15T04:48:24.582Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-15T04:48:24.600Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
2015-12-15T04:48:24.603Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-15T04:48:24.628Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-15T04:48:24.653Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15T04:48:24.654Z SendDataTCPServer.js: TCP/IP server has received 78414 bytes of data
,2015-12-15T04:48:24.673Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-15T04:48:24.700Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 05:48:24.756 ThaliTest[891:1376943] server session: not connected Apple-Iphone5s-1_PT4162
,teardown
,testSendData stopped
,2015-12-15 05:48:33.078 ThaliTest[891:1375553] jxcore: stopBroadcasting
2015-12-15 05:48:33.078 ThaliTest[891:1375553] THEMultipeerSession stopping peer
,2015-12-15 05:48:33.078 ThaliTest[891:1375553] multipeer session: stop timer
,2015-12-15 05:48:33.079 ThaliTest[891:1375553] server session: disconnect
2015-12-15 05:48:33.079 ThaliTest[891:1375553] server session: stateChange:2->0 Apple-Iphone6-1_PT7824
,2015-12-15 05:48:33.086 ThaliTest[891:1375553] server session: disconnect
2015-12-15 05:48:33.088 ThaliTest[891:1375553] server session: stateChange:2->0 Apple-IpadAir2-1_PT2678
,2015-12-15 05:48:33.096 ThaliTest[891:1375553] server session: disconnect
2015-12-15 05:48:33.097 ThaliTest[891:1375553] server session: stateChange:2->0 Apple-Iphone5s-1_PT4162
,2015-12-15 05:48:33.103 ThaliTest[891:1375553] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-15T04:48:33.125Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-15T04:48:33.126Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-15T04:48:33.129Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-15T04:48:33.129Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
