#### Test 506502782ddd83f_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502782ddd83f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/8CB719CB-E232-4E41-86D0-21796C042907/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8CB719CB-E232-4E41-86D0-21796C042907/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502782ddd83f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502782ddd83f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6A8E500D-99B9-46E8-AEF5-7B87B2EA8121/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56418"
,(lldb)     command script import "/tmp/8CB719CB-E232-4E41-86D0-21796C042907/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-15 05:41:40.249 ThaliTest[1100:1263381] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C178B1AB-EF34-4DF8-9059-AAF4364C2E8C/Library/Cookies/Cookies.binarycookies
,2015-12-15 05:41:40.639 ThaliTest[1100:1263381] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-15 05:41:40.640 ThaliTest[1100:1263381] Multi-tasking -> Device: YES, App: YES
,2015-12-15 05:41:40.649 ThaliTest[1100:1263381] Unlimited access to network resources
,2015-12-15 05:41:40.663 ThaliTest[1100:1263381] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-15 05:41:49.630 ThaliTest[1100:1263381] Resetting plugins due to page load.
,2015-12-15 05:41:53.353 ThaliTest[1100:1263381] Finished load of: file:///var/mobile/Containers/Bundle/Application/6A8E500D-99B9-46E8-AEF5-7B87B2EA8121/ThaliTest.app/www/index.html
,2015-12-15 05:41:53.566 ThaliTest[1100:1263381] JXcore Cordova plugin initializing
2015-12-15 05:41:53.567 ThaliTest[1100:1263602] JXcore instance initializing
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
,2015-12-15 05:41:54.870 ThaliTest[1100:1263381] THREAD WARNING: ['JXcore'] took '83.684814' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-15 05:46:57.918 ThaliTest[1100:1263602] jxcore: startBroadcasting
,2015-12-15 05:46:57.941 ThaliTest[1100:1263602] server: starting Apple-Iphone5s-1_PT4162.k8tRvA==
,2015-12-15 05:46:57.942 ThaliTest[1100:1263602] multipeer session: start timer: 0x1747a0d0
2015-12-15 05:46:57.943 ThaliTest[1100:1263602] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT4162
2015-12-15 05:46:57.944 ThaliTest[1100:1263602] jxcore,: startBroadcasting: success
StartBroadcasting started ok
,2015-12-15 05:46:58.511 ThaliTest[1100:1263381] client: found peer: Apple-Iphone5-1_PT356.zzR6Ww==
2015-12-15 05:46:58.513 ThaliTest[1100:1263381] client: found peer: Apple-IpadAir2-1_PT2678.RP+Etw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ipho,ne5-1_PT356.zzR6Ww==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5-1_PT356.zzR6Ww==, peerAvailable: true
,weAreDoneNow
done, now sending data to server
,2015-12-15 05:46:58.572 ThaliTest[1100:1263381] client: found peer: Apple-Iphone6-1_PT7824.Q97KpQ==
,teardown
,testFindPeers stopped
,2015-12-15 05:46:58.869 ThaliTest[1100:1263602] jxcore: stopBroadcasting
2015-12-15 05:46:58.869 ThaliTest[1100:1263602] THEMultipeerSession stopping peer
2015-12-15 05:46:58.870 ThaliTest[1100:1263602] multipeer session: stop timer
2015-12-15 05:46:58.,871 ThaliTest[1100:1263602] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
serverPort is 59696
,2015-12-15 05:46:58.942 ThaliTest[1100:1263602] jxcore: startBroadcasting
,2015-12-15 05:46:58.947 ThaliTest[1100:1263602] server: starting Apple-Iphone5s-1_PT4162.hYB3TQ==
2015-12-15 05:46:58.948 ThaliTest[1100:1263602] multipeer session: start timer: 0x17481be0
2015-12-15 05:46:58.949 ThaliTest[1100:1263602] THEMultipeerSessi,on initialized peer Apple-Iphone5s-1_PT4162
2015-12-15 05:46:58.949 ThaliTest[1100:1263602] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
,2015-12-15T04:46:58.955Z SendDataTCPServer.js: TCP/IP server is bound to port: 59696
,2015-12-15 05:46:58.982 ThaliTest[1100:1263381] client: found peer: Apple-IpadAir2-1_PT2678.RP+Etw==
2015-12-15 05:46:58.983 ThaliTest[1100:1263381] client: found peer: Apple-Iphone5-1_PT356.zzR6Ww==
2015-12-15 05:46:58.984 ThaliTest[1100:1263381] client,: found peer: Apple-Iphone6-1_PT7824.Q97KpQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2678.RP+Etw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-IpadAir2-1_PT2678.RP+Etw==
2015-12-15T04:46:58.990Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2678.RP+Etw==
2015-12-15T04:46:58.991Z SendDataConnector.js: doConnect called with peer Apple-IpadAi,r2-1_PT2678.RP+Etw==
2015-12-15T04:46:58.991Z SendDataConnector.js: do connect now
2015-12-15 05:46:58.992 ThaliTest[1100:1263602] jxcore: connect Apple-IpadAir2-1_PT2678.RP+Etw==
2015-12-15 05:46:58.992 ThaliTest[1100:1263602] client session: connect
,2015-12-15 05:46:58.993 ThaliTest[1100:1263602] client session: stateChange:0->1 Apple-IpadAir2-1_PT2678.RP+Etw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT356.zzR6Ww==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7824.Q97KpQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 05:47:00.708 ThaliTest[1100:1263381] client: lost peer: Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15 05:47:00.708 ThaliTest[1100:1263381] client session: onPeerLost: Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15 05:47:00.709 ThaliTest[1100:1263381], client: found peer: Apple-Iphone5-1_PT356.aa89HA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7824.Q97KpQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT356.aa89HA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 05:47:01.036 ThaliTest[1100:1263381] client: lost peer: Apple-Iphone5-1_PT356.zzR6Ww==
2015-12-15 05:47:01.037 ThaliTest[1100:1263381] client session: onPeerLost: Apple-Iphone5-1_PT356.zzR6Ww==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT356.zzR6Ww==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-15 05:47:01.052 ThaliTest[1100:1263381] client: lost peer: Apple-IpadAir2-1_PT2678.RP+Etw==
2015-12-15 05:47:01.052 ThaliTest[1100:1263381] client session: onPeerLost: Apple-IpadAir2-1_PT2678.RP+Etw==
2015-12-15 05:47:01.053 ThaliTest[1100:126338,1] client session: onLinkFailure: Apple-IpadAir2-1_PT2678.RP+Etw==
2015-12-15 05:47:01.053 ThaliTest[1100:1263381] client session: disconnect
2015-12-15 05:47:01.054 ThaliTest[1100:1263381] client session: stateChange:1->0 Apple-IpadAir2-1_PT2678.RP+Etw=,=
2015-12-15 05:47:01.055 ThaliTest[1100:1263381] client session: fireConnectCallback: Apple-IpadAir2-1_PT2678.RP+Etw==
2015-12-15 05:47:01.055 ThaliTest[1100:1263381] jxcore: connect: fail: Peer disconnected
2015-12-15T04:47:01.056Z SendDataConnector.j,s: CLIENT connected to 0, error: Peer disconnected
2015-12-15T04:47:01.057Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-15T04:47:01.058Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier",:"Apple-IpadAir2-1_PT2678.RP+Etw==","peerName":"(null)","peerAvailable":false}]
,2015-12-15 05:47:01.066 ThaliTest[1100:1263381] client: found peer: Apple-IpadAir2-1_PT2678.ad0lIQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2678.ad0lIQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 05:47:01.084 ThaliTest[1100:1263381] client: found peer: Apple-Iphone6-1_PT7824.jNC0Kw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7824.jNC0Kw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-15T04:47:06.062Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15T04:47:06.063Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:11.073 ThaliTest[1100:1263602] jxcore: disconnect
2015-12-15 05:47:11.073 ThaliTest[1100:1263602] jxcore: disconnect: fail
2015-12-15T04:47:11.074Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2678.RP+E,tw==
2015-12-15T04:47:11.075Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT2678.RP+Etw== with availability status: true
2015-12-15T04:47:11.075Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15T04:47:11.075Z SendDataConnector.js: do connect now
2015-12-15 05:47:11.076 ThaliTest[1100:1263602] jxcore: connect Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:11.077 ThaliTest[1100:1263602] client: connect: unreachable Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:11.078 ThaliTest[1100:1263602] jxcore: connect: fail: Peer unreachable
,2015-12-15T04:47:11.079Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:47:11.080Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T04:47:11.080Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:47:16.087Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15T04:47:16.088Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:21.096 ThaliTest[1100:1263602] jxcore: disconnect
2015-12-15 05:47:21.096 ThaliTest[1100:1263602] jxcore: disconnect: fail
2015-12-15T04:47:21.097Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2678.RP+E,tw==
2015-12-15T04:47:21.098Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT2678.RP+Etw== with availability status: true
2015-12-15T04:47:21.098Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2678.RP+Etw==,
2015-12-15T04:47:21.098Z SendDataConnector.js: do connect now
,2015-12-15 05:47:21.099 ThaliTest[1100:1263602] jxcore: connect Apple-IpadAir2-1_PT2678.RP+Etw==
2015-12-15 05:47:21.100 ThaliTest[1100:1263602] client: connect: unreachable Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:21.100 ThaliTest[1100:1263602] jxcore: connect: fail: Peer unreachable
,2015-12-15T04:47:21.101Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:47:21.103Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T04:47:21.103Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:47:26.104Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15T04:47:26.105Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:28.950 ThaliTest[1100:1263381] multipeer session: restart
,2015-12-15 05:47:31.111 ThaliTest[1100:1263602] jxcore: disconnect
2015-12-15 05:47:31.112 ThaliTest[1100:1263602] jxcore: disconnect: fail
2015-12-15T04:47:31.113Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2678.RP+E,tw==
2015-12-15T04:47:31.113Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT2678.RP+Etw== with availability status: true
2015-12-15T04:47:31.113Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15T04:47:31.114Z SendDataConnector.js: do connect now
2015-12-15 05:47:31.115 ThaliTest[1100:1263602] jxcore: connect Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:31.115 ThaliTest[1100:1263602] client: connect: unreachable Apple-IpadAir2-1_PT2678.RP+Etw==
2015-12-15 05:47:31.116 ThaliTest[1100:1263602] jxcore: connect: fail: Peer unreachable
2015-12-15T04:47:31.117Z SendDataConnector.js: CLIENT co,nnected to 0, error: Peer unreachable
2015-12-15T04:47:31.117Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T04:47:31.118Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:47:36.126Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15T04:47:36.126Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:41.131 ThaliTest[1100:1263602] jxcore: disconnect
2015-12-15 05:47:41.132 ThaliTest[1100:1263602] jxcore: disconnect: fail
2015-12-15T04:47:41.132Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2678.RP+E,tw==
2015-12-15T04:47:41.133Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT2678.RP+Etw== with availability status: true
2015-12-15T04:47:41.133Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15T04:47:41.133Z SendDataConnector.js: do connect now
2015-12-15 05:47:41.134 ThaliTest[1100:1263602] jxcore: connect Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:41.135 ThaliTest[1100:1263602] client: connect: unreachable Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:41.136 ThaliTest[1100:1263602] jxcore: connect: fail: Peer unreachable
,2015-12-15T04:47:41.137Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-15T04:47:41.137Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2015-12-15T04:47:41.140Z SendDataConnector.js: CLIENT Stop now
,2015-12-15 05:47:41.141 ThaliTest[1100:1263602] jxcore: disconnect
2015-12-15 05:47:41.142 ThaliTest[1100:1263602] jxcore: disconnect: fail
2015-12-15T04:47:41.143Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2678.RP+Etw==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15T04:47:41.146Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15T04:47:41.147Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15T04:47:41.148Z SendDataConnector.js: do connect now
,2015-12-15 05:47:41.149 ThaliTest[1100:1263602] jxcore: connect Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:47:41.149 ThaliTest[1100:1263602] client session: connect
2015-12-15 05:47:41.150 ThaliTest[1100:1263602] client session: stateChange:0->1 Apple-,Iphone5-1_PT356.aa89HA==
,2015-12-15 05:47:41.163 ThaliTest[1100:1263381] client: lost peer: Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:47:41.163 ThaliTest[1100:1263381] client session: onPeerLost: Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:47:41.164 ThaliTest[1100:1263381] c,lient session: onLinkFailure: Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:47:41.164 ThaliTest[1100:1263381] client session: disconnect
2015-12-15 05:47:41.164 ThaliTest[1100:1263381] client session: stateChange:1->0 Apple-Iphone5-1_PT356.aa89HA==
2015-,12-15 05:47:41.165 ThaliTest[1100:1263381] client session: fireConnectCallback: Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:47:41.165 ThaliTest[1100:1263381] jxcore: connect: fail: Peer disconnected
2015-12-15T04:47:41.167Z SendDataConnector.js: CLIENT ,connected to 0, error: Peer disconnected
2015-12-15T04:47:41.167Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-15T04:47:41.168Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ip,hone5-1_PT356.aa89HA==","peerName":"(null)","peerAvailable":false}]
,2015-12-15 05:47:41.709 ThaliTest[1100:1263381] multipeer session: reset timer
2015-12-15 05:47:41.709 ThaliTest[1100:1263381] multipeer session: stop timer
2015-12-15 05:47:41.710 ThaliTest[1100:1263381] multipeer session: start timer: 0x17481be0
,2015-12-15 05:47:41.710 ThaliTest[1100:1263381] server session: connect
,2015-12-15 05:47:41.712 ThaliTest[1100:1263381] server session: stateChange:0->1 Apple-IpadAir2-1_PT2678
,2015-12-15 05:47:41.723 ThaliTest[1100:1263381] server: accepting invitation Apple-IpadAir2-1_PT2678
,2015-12-15 05:47:44.297 ThaliTest[1100:1264942] server session: connected
2015-12-15 05:47:44.297 ThaliTest[1100:1264942] server session: stateChange:1->2 Apple-IpadAir2-1_PT2678
,2015-12-15 05:47:44.349 ThaliTest[1100:1263381] server relay: connected (to port: 59696)
2015-12-15T04:47:44.351Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T04:47:44.606Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-15T04:47:44.624Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-15T04:47:44.669Z SendDataTCPServer.js: TCP/IP server has received 49802 bytes of data
,2015-12-15T04:47:44.686Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-15T04:47:44.704Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-15T04:47:44.721Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 05:47:44.785 ThaliTest[1100:1264941] server session: not connected Apple-IpadAir2-1_PT2678
,2015-12-15T04:47:46.176Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15T04:47:46.177Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:47:49.511 ThaliTest[1100:1263381] multipeer session: reset timer
2015-12-15 05:47:49.511 ThaliTest[1100:1263381] multipeer session: stop timer
2015-12-15 05:47:49.512 ThaliTest[1100:1263381] multipeer session: start timer: 0x17481be0
2015-,12-15 05:47:49.512 ThaliTest[1100:1263381] server session: connect
2015-12-15 05:47:49.512 ThaliTest[1100:1263381] server session: stateChange:0->1 Apple-Iphone5-1_PT356
,2015-12-15 05:47:49.523 ThaliTest[1100:1263381] server: accepting invitation Apple-Iphone5-1_PT356
,2015-12-15 05:47:51.187 ThaliTest[1100:1263602] jxcore: disconnect
2015-12-15 05:47:51.187 ThaliTest[1100:1263602] jxcore: disconnect: fail
2015-12-15T04:47:51.188Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT356.aa89HA,==
2015-12-15T04:47:51.188Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT356.aa89HA== with availability status: true
2015-12-15T04:47:51.189Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15T04:47:51.189Z SendDataConnector.js: do connect now
2015-12-15 05:47:51.190 ThaliTest[1100:1263602] jxcore: connect Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:47:51.191 ThaliTest[1100:1263602] client: connect: unreachable Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:47:51.192 ThaliTest[1100:1263602] jxcore: connect: fail: Peer unreachable
2015-12-15T04:47:51.193Z SendDataConnector.js: CLIENT conn,ected to 0, error: Peer unreachable
2015-12-15T04:47:51.193Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T04:47:51.193Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15 05:47:52.198 ThaliTest[1100:1264941] server session: connected
2015-12-15 05:47:52.199 ThaliTest[1100:1264941] server session: stateChange:1->2 Apple-Iphone5-1_PT356
,2015-12-15 05:47:52.233 ThaliTest[1100:1263381] server relay: connected (to port: 59696)
,2015-12-15T04:47:52.243Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T04:47:52.730Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-15T04:47:52.744Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-15T04:47:52.771Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-15T04:47:52.985Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-15T04:47:53.004Z SendDataTCPServer.js: TCP/IP server has received 40900 bytes of data
,2015-12-15T04:47:53.023Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-15T04:47:53.041Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-15T04:47:53.060Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 05:47:53.122 ThaliTest[1100:1264939] server session: not connected Apple-Iphone5-1_PT356
,2015-12-15T04:47:56.201Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15T04:47:56.201Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:48:01.210 ThaliTest[1100:1263602] jxcore: disconnect
2015-12-15 05:48:01.211 ThaliTest[1100:1263602] jxcore: disconnect: fail
,2015-12-15T04:48:01.212Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT356.aa89HA==
2015-12-15T04:48:01.213Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT356.aa89HA== with availability status: true
,2015-12-15T04:48:01.213Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15T04:48:01.214Z SendDataConnector.js: do connect now
,2015-12-15 05:48:01.215 ThaliTest[1100:1263602] jxcore: connect Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:48:01.216 ThaliTest[1100:1263602] client: connect: unreachable Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:48:01.216 ThaliTest[1100:1263602] jxc,ore: connect: fail: Peer unreachable
2015-12-15T04:48:01.217Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:48:01.217Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T04:48:01.218Z SendDataC,onnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:48:06.223Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15T04:48:06.224Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:48:11.226 ThaliTest[1100:1263602] jxcore: disconnect
2015-12-15 05:48:11.227 ThaliTest[1100:1263602] jxcore: disconnect: fail
2015-12-15T04:48:11.227Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT356.aa89HA,==
2015-12-15T04:48:11.228Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT356.aa89HA== with availability status: true
2015-12-15T04:48:11.228Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT356.aa89HA==
2015,-12-15T04:48:11.228Z SendDataConnector.js: do connect now
,2015-12-15 05:48:11.229 ThaliTest[1100:1263602] jxcore: connect Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:48:11.230 ThaliTest[1100:1263602] client: connect: unreachable Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:48:11.231 ThaliTest[1100:1263602] jxcore: connect: fail: Peer unreachable
2015-12-15T04:48:11.233Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:48:11.233Z SendDataConnector.js: CLIENT Can not Connect: P,eer unreachable
2015-12-15T04:48:11.233Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:48:16.238Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15T04:48:16.239Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:48:19.513 ThaliTest[1100:1263381] multipeer session: restart
,2015-12-15 05:48:19.562 ThaliTest[1100:1263381] client: found peer: Apple-Iphone5-1_PT356.aa89HA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT356.aa89HA==","peerName":"(null)","peerAvailable":true}]
2015-12-15 05:48:19.566 ThaliTest[1100:1263381] client: found peer: Apple-Iphone6-1_PT7824.jNC0Kw==
,2015-12-15 05:48:19.574 ThaliTest[1100:1263381] client: found peer: Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15 05:48:21.240 ThaliTest[1100:1263602] jxcore: disconnect
2015-12-15 05:48:21.241 ThaliTest[1100:1263602] jxcore: disconnect: fail
2015-12-15T04:48:21.241Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT356.aa89HA,==
2015-12-15T04:48:21.241Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT356.aa89HA== with availability status: true
2015-12-15T04:48:21.242Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15T04:48:21.242Z SendDataConnector.js: do connect now
,2015-12-15 05:48:21.243 ThaliTest[1100:1263602] jxcore: connect Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:48:21.244 ThaliTest[1100:1263602] client session: connect
2015-12-15 05:48:21.244 ThaliTest[1100:1263602] client session: stateChange:0->1 Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:48:24.242 ThaliTest[1100:1265041] client session: connected
2015-12-15 05:48:24.242 ThaliTest[1100:1265041] client session: stateChange:1->2 Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:48:24.269 ThaliTest[1100:1265067] client session: fireConnectCallback: Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:48:24.269 ThaliTest[1100:1265067] jxcore: connect: success
,2015-12-15T04:48:24.270Z SendDataConnector.js: CLIENT connected to 59703, error: null
2015-12-15T04:48:24.271Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 05:48:24.275 ThaliTest[1100:1263381] client: relay established
2015-12-15 05:48:24.277 ThaliTest[1100:1263381] client: new accepted socket: 0x17494490
,2015-12-15T04:48:24.293Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T04:48:24.699Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-15T04:48:24.723Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-15T04:48:24.723Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-15T04:48:24.724Z SendDataConnector.js: CLIENT Stop now
2015-12-15T04:48:24.724Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:48:24.725 ThaliTest[1100:1263602] jxcore: disconnect
,2015-12-15 05:48:24.726 ThaliTest[1100:1263602] client session: disconnectFromPeer: Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:48:24.728 ThaliTest[1100:1263602] client session: disconnect
,2015-12-15 05:48:24.728 ThaliTest[1100:1263602] client session: stateChange:2->0 Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:48:24.792 ThaliTest[1100:1263602] jxcore: disconnect: success
,2015-12-15T04:48:24.793Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT356.aa89HA==
---- round done--------
,startWithNextDevice
,device[3]: Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15T04:48:24.794Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15T04:48:24.795Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15T04:48:24.795Z SendDataConnector.js: do connect now
,2015-12-15 05:48:24.795 ThaliTest[1100:1263602] jxcore: connect Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15 05:48:24.796 ThaliTest[1100:1263602] client session: connect
,2015-12-15 05:48:24.796 ThaliTest[1100:1263602] client session: stateChange:0->1 Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15 05:48:24.897 ThaliTest[1100:1263381] multipeer session: reset timer
2015-12-15 05:48:24.897 ThaliTest[1100:1263381] multipeer session: stop timer
2015-12-15 05:48:24.897 ThaliTest[1100:1263381] multipeer session: start timer: 0x17481be0
2015-12-15 05:48:24.897 ThaliTest[1100:1263381] server session: connect
2015-12-15 05:48:24.897 ThaliTest[1100:1263381] server session: stateChange:0->1 Apple-Iphone6-1_PT7824
,2015-12-15 05:48:24.901 ThaliTest[1100:1263381] server: accepting invitation Apple-Iphone6-1_PT7824
,2015-12-15 05:48:27.410 ThaliTest[1100:1265067] server session: connected
2015-12-15 05:48:27.411 ThaliTest[1100:1265067] server session: stateChange:1->2 Apple-Iphone6-1_PT7824
,2015-12-15 05:48:27.475 ThaliTest[1100:1263381] server relay: connected (to port: 59696)
,2015-12-15T04:48:27.483Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T04:48:27.721Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-15 05:48:27.783 ThaliTest[1100:1265043] client session: connected
2015-12-15 05:48:27.783 ThaliTest[1100:1265043] client session: stateChange:1->2 Apple-IpadAir2-1_PT2678.ad0lIQ==
2015-12-15T04:48:27.794Z SendDataTCPServer.js: TCP/IP server has received 10808 bytes of data
,2015-12-15T04:48:27.813Z SendDataTCPServer.js: TCP/IP server has received 32566 bytes of data
,2015-12-15T04:48:27.837Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-15T04:48:27.854Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-15 05:48:27.867 ThaliTest[1100:1265068] client session: fireConnectCallback: Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15T04:48:27.871Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 05:48:27.869 ThaliTest[1100:1265068] jxcore: connect: success
,2015-12-15T04:48:27.873Z SendDataConnector.js: CLIENT connected to 59707, error: null
2015-12-15T04:48:27.873Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 05:48:27.876 ThaliTest[1100:1263381] client: relay established
2015-12-15 05:48:27.877 ThaliTest[1100:1263381] client: new accepted socket: 0x173e4cb0
,2015-12-15T04:48:27.889Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15 05:48:27.970 ThaliTest[1100:1265042] server session: not connected Apple-Iphone6-1_PT7824
,2015-12-15T04:48:28.280Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-15T04:48:28.427Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-15T04:48:28.454Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-15T04:48:28.454Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-15T04:48:28.455Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T04:48:28.455Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:48:28.455 ThaliTest[1100:1263602] jxcore: disconnect
,2015-12-15 05:48:28.456 ThaliTest[1100:1263602] client session: disconnectFromPeer: Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15 05:48:28.457 ThaliTest[1100:1263602] client session: disconnect
,2015-12-15 05:48:28.457 ThaliTest[1100:1263602] client session: stateChange:2->0 Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15 05:48:28.526 ThaliTest[1100:1263602] jxcore: disconnect: success
,2015-12-15T04:48:28.528Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2678.ad0lIQ==
---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone6-1_PT7824.jNC0Kw==
,2015-12-15T04:48:28.529Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7824.jNC0Kw==
,2015-12-15T04:48:28.529Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7824.jNC0Kw==
,2015-12-15T04:48:28.530Z SendDataConnector.js: do connect now
,2015-12-15 05:48:28.530 ThaliTest[1100:1263602] jxcore: connect Apple-Iphone6-1_PT7824.jNC0Kw==
,2015-12-15 05:48:28.531 ThaliTest[1100:1263602] client session: connect
,2015-12-15 05:48:28.532 ThaliTest[1100:1263602] client session: stateChange:0->1 Apple-Iphone6-1_PT7824.jNC0Kw==
,2015-12-15 05:48:31.245 ThaliTest[1100:1265042] client session: connected
2015-12-15 05:48:31.245 ThaliTest[1100:1265042] client session: stateChange:1->2 Apple-Iphone6-1_PT7824.jNC0Kw==
,2015-12-15 05:48:31.312 ThaliTest[1100:1265068] client session: fireConnectCallback: Apple-Iphone6-1_PT7824.jNC0Kw==
2015-12-15 05:48:31.313 ThaliTest[1100:1265068] jxcore: connect: success
2015-12-15T04:48:31.314Z SendDataConnector.js: CLIENT connected ,to 59710, error: null
2015-12-15T04:48:31.314Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 05:48:31.319 ThaliTest[1100:1263381] client: relay established
2015-12-15 05:48:31.319 ThaliTest[1100:1263381] client: new accepted socket: 0x174a27c0
,2015-12-15T04:48:31.333Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T04:48:31.703Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-15T04:48:31.729Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-15T04:48:31.729Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2015-12-15T04:48:31.730Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T04:48:31.730Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:48:31.730 ThaliTest[1100:1263602] jxcore: disconnect
2015-12-15 05:48:31.731 ThaliTest[1100:1263602] client session: disconnectFromPeer: Apple-Iphone6-1_PT7824.jNC0Kw==
2015-12-15 05:48:31.731 ThaliTest[1100:1263602] client session: disconnect
2015-12-15 05:48:31.731 ThaliTest[1100:1263602] client session: stateChange:2->0 Apple-Iphone6-1_PT7824.jNC0Kw==
,2015-12-15 05:48:31.736 ThaliTest[1100:1263602] jxcore: disconnect: success
2015-12-15T04:48:31.736Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7824.jNC0Kw==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
2015-12-15T04:48:31.739Z SendDataConnector.js: CLIENT Stop now
2015-12-15T04:48:31.740Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
,2015-12-15 05:48:33.266 ThaliTest[1100:1263602] jxcore: stopBroadcasting
,2015-12-15 05:48:33.267 ThaliTest[1100:1263602] THEMultipeerSession stopping peer
,2015-12-15 05:48:33.268 ThaliTest[1100:1263602] multipeer session: stop timer
,2015-12-15 05:48:33.269 ThaliTest[1100:1263602] server session: disconnect
2015-12-15 05:48:33.270 ThaliTest[1100:1263602] server session: stateChange:2->0 Apple-Iphone6-1_PT7824
,2015-12-15 05:48:33.280 ThaliTest[1100:1263602] server session: disconnect
2015-12-15 05:48:33.281 ThaliTest[1100:1263602] server session: stateChange:2->0 Apple-IpadAir2-1_PT2678
,2015-12-15 05:48:33.292 ThaliTest[1100:1263602] server session: disconnect
2015-12-15 05:48:33.292 ThaliTest[1100:1263602] server session: stateChange:2->0 Apple-Iphone5-1_PT356
,2015-12-15 05:48:33.311 ThaliTest[1100:1263602] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-15T04:48:33.344Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-15T04:48:33.361Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-15T04:48:33.364Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-15T04:48:33.366Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
