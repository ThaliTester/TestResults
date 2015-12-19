#### Test 50650278161ce7f_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278161ce7f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/104E88A1-991C-4F5A-B402-9755760B2078/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/104E88A1-991C-4F5A-B402-9755760B2078/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278161ce7f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278161ce7f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AD8B8619-F221-417B-81C1-C84958F6BFF0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60601"
,(lldb)     command script import "/tmp/104E88A1-991C-4F5A-B402-9755760B2078/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-19 02:28:41.553 ThaliTest[460:495966] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A3BFF9B5-C2E0-4B5E-975B-2FA2DE4E0D09/Library/Cookies/Cookies.binarycookies
,2015-12-19 02:28:41.683 ThaliTest[460:495966] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-19 02:28:41.685 ThaliTest[460:495966] Multi-tasking -> Device: YES, App: YES
,2015-12-19 02:28:41.692 ThaliTest[460:495966] Unlimited access to network resources
,2015-12-19 02:28:41.703 ThaliTest[460:495966] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-19 02:28:51.933 ThaliTest[460:495966] Resetting plugins due to page load.
,2015-12-19 02:28:56.025 ThaliTest[460:495966] Finished load of: file:///var/mobile/Containers/Bundle/Application/AD8B8619-F221-417B-81C1-C84958F6BFF0/ThaliTest.app/www/index.html
,2015-12-19 02:28:56.242 ThaliTest[460:495966] JXcore Cordova plugin initializing
2015-12-19 02:28:56.244 ThaliTest[460:496147] JXcore instance initializing
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
,2015-12-19 02:28:58.687 ThaliTest[460:495966] THREAD WARNING: ['JXcore'] took '153.304199' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 53938
,2015-12-19 02:35:01.102 ThaliTest[460:496147] jxcore: startBroadcasting
,2015-12-19 02:35:01.113 ThaliTest[460:496147] server: starting Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:35:01.113 ThaliTest[460:496147] multipeer session: start timer: 0x1ca184c0
2015-12-19 02:35:01.115 ThaliTest[460:496147] THEMultipeerSession initialized peer Apple-Iphone5-1_PT9897
2015-12-19 02:35:01.115 ThaliTest[460:496147] jxcore: start,Broadcasting: success
StartBroadcasting started ok
null
2015-12-19T01:35:01.118Z SendDataTCPServer.js: TCP/IP server is bound to port: 53938
,2015-12-19 02:35:02.164 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3166.5e8qRw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19T01:35:02.168Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19T01:35:02.169Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19T01:35:02.169Z SendDataConnector.js: do connect now
2015-12-19 02:35:02.170 ThaliTest[460:496147] jxcore: connect Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:35:02.170 ThaliTest[460:496147] client session: connect
2015-12-19 02:35:02.171 ThaliTest[460:496147] client session: stateChange:0->1 Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:35:02.292 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4132.HrCdVA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-19 02:35:02.431 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9396.+XAJIw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-19 02:35:02.897 ThaliTest[460:495966] multipeer session: reset timer
2015-12-19 02:35:02.897 ThaliTest[460:495966] multipeer session: stop timer
2015-12-19 02:35:02.897 ThaliTest[460:495966] multipeer session: start timer: 0x1ca184c0
2015-12-19 ,02:35:02.897 ThaliTest[460:495966] server session: connect
2015-12-19 02:35:02.898 ThaliTest[460:495966] server session: stateChange:0->1 Apple-IpadAir2-1_PT4132
2015-12-19 02:35:02.909 ThaliTest[460:495966] server: accepting invitation Apple-IpadAir2-1_PT4132
,2015-12-19 02:35:05.578 ThaliTest[460:496791] client session: connected
2015-12-19 02:35:05.578 ThaliTest[460:496791] client session: stateChange:1->2 Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:35:05.650 ThaliTest[460:496790] client session: fireConnectCallback: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:35:05.650 ThaliTest[460:496790] jxcore: connect: success
2015-12-19T01:35:05.652Z SendDataConnector.js: CLIENT connected to 53941, error: null
2015-12-19T01:35:05.652Z SendDataConnector.js: CLIENT starting client 
,2015-12-19 02:35:05.657 ThaliTest[460:495966] client: relay established
2015-12-19 02:35:05.657 ThaliTest[460:495966] client: new accepted socket: 0x1cbdf480
,2015-12-19T01:35:05.669Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19 02:35:05.713 ThaliTest[460:496791] server session: connected
2015-12-19 02:35:05.713 ThaliTest[460:496791] server session: stateChange:1->2 Apple-IpadAir2-1_PT4132
,2015-12-19 02:35:05.747 ThaliTest[460:495966] server relay: connected (to port: 53938)
,2015-12-19T01:35:06.215Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-19T01:35:06.228Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19 02:35:06.264 ThaliTest[460:496810] server session: not connected Apple-IpadAir2-1_PT4132
,2015-12-19T01:35:06.308Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-19 02:35:06.432 ThaliTest[460:495966] multipeer session: reset timer
,2015-12-19 02:35:06.432 ThaliTest[460:495966] multipeer session: stop timer
2015-12-19 02:35:06.433 ThaliTest[460:495966] multipeer session: start timer: 0x1ca184c0
,2015-12-19 02:35:06.433 ThaliTest[460:495966] server session: connect
,2015-12-19 02:35:06.433 ThaliTest[460:495966] server session: stateChange:0->1 Apple-Iphone5s-1_PT9396
,2015-12-19 02:35:06.441 ThaliTest[460:495966] server: accepting invitation Apple-Iphone5s-1_PT9396
,2015-12-19T01:35:06.626Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-19T01:35:06.627Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2015-12-19T01:35:06.628Z SendDataConnector.js: CLIENT Stop now
2015-12-19T01:35:0,6.629Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-19 02:35:06.629 ThaliTest[460:496147] jxcore: disconnect
2015-12-19 02:35:06.630 ThaliTest[460:496147] client session: disconnectFromPeer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:35:06.,630 ThaliTest[460:496147] client session: disconnect
2015-12-19 02:35:06.630 ThaliTest[460:496147] client session: stateChange:2->0 Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:35:06.642 ThaliTest[460:496147] jxcore: disconnect: success
2015-12-19T01:35:06.644Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3166.5e8qRw==
---- round done--------
startWithNextDevice
device[2]: Apple,-IpadAir2-1_PT4132.HrCdVA==
2015-12-19T01:35:06.646Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19T01:35:06.646Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19T01:3,5:06.646Z SendDataConnector.js: do connect now
2015-12-19 02:35:06.647 ThaliTest[460:496147] jxcore: connect Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:35:06.647 ThaliTest[460:496147] client session: connect
2015-12-19 02:35:06.649 ThaliTest[460:496147] client session: stateChange:0->1 Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:35:09.050 ThaliTest[460:496810] server session: connected
2015-12-19 02:35:09.050 ThaliTest[460:496810] server session: stateChange:1->2 Apple-Iphone5s-1_PT9396
,2015-12-19 02:35:09.116 ThaliTest[460:495966] server relay: connected (to port: 53938)
,2015-12-19T01:35:09.125Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-19 02:35:09.381 ThaliTest[460:496790] client session: connected
2015-12-19 02:35:09.381 ThaliTest[460:496790] client session: stateChange:1->2 Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19T01:35:09.405Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-19T01:35:09.522Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-19T01:35:09.541Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19 02:35:09.613 ThaliTest[460:496860] server session: not connected Apple-Iphone5s-1_PT9396
,2015-12-19 02:35:09.837 ThaliTest[460:496860] client session: fireConnectCallback: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:35:09.837 ThaliTest[460:496860] jxcore: connect: success
2015-12-19T01:35:09.837Z SendDataConnector.js: CLIENT connected to ,53946, error: null
2015-12-19T01:35:09.838Z SendDataConnector.js: CLIENT starting client 
2015-12-19 02:35:09.839 ThaliTest[460:495966] client: relay established
2015-12-19 02:35:09.840 ThaliTest[460:495966] client: new accepted socket: 0x1cbf1fa0
,2015-12-19T01:35:09.852Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19 02:35:10.419 ThaliTest[460:495966] multipeer session: reset timer
2015-12-19 02:35:10.419 ThaliTest[460:495966] multipeer session: stop timer
2015-12-19 02:35:10.420 ThaliTest[460:495966] multipeer session: start timer: 0x1ca184c0
2015-12-19 02:35:10.420 ThaliTest[460:495966] server session: connect
2015-12-19 02:35:10.422 ThaliTest[460:495966] server session: stateChange:0->1 Apple-Iphone6-1_PT3166
,2015-12-19 02:35:10.429 ThaliTest[460:495966] server: accepting invitation Apple-Iphone6-1_PT3166
,2015-12-19T01:35:10.507Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-19T01:35:10.620Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-19T01:35:10.621Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2015-12-19T01:35:10.621Z SendDataConnector.js: CLIENT Stop now
2015-12-19T01:35:1,0.621Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-19 02:35:10.622 ThaliTest[460:496147] jxcore: disconnect
2015-12-19 02:35:10.626 ThaliTest[460:496147] client session: disconnectFromPeer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:35:10,.627 ThaliTest[460:496147] client session: disconnect
2015-12-19 02:35:10.627 ThaliTest[460:496147] client session: stateChange:2->0 Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:35:10.648 ThaliTest[460:496147] jxcore: disconnect: success
2015-12-19T01:35:10.648Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT4132.HrCdVA==
---- round done--------
startWithNextDevice
device[3]: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19T01:35:10.650Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19T01:35:10.650Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19T01:,35:10.650Z SendDataConnector.js: do connect now
2015-12-19 02:35:10.651 ThaliTest[460:496147] jxcore: connect Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:35:10.651 ThaliTest[460:496147] client session: connect
2015-12-19 02:35:10.654 ThaliTest[460:496147] client session: stateChange:0->1 Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:35:13.208 ThaliTest[460:496860] server session: connected
2015-12-19 02:35:13.208 ThaliTest[460:496860] server session: stateChange:1->2 Apple-Iphone6-1_PT3166
,2015-12-19 02:35:13.229 ThaliTest[460:495966] server relay: connected (to port: 53938)
,2015-12-19T01:35:13.240Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-19T01:35:13.501Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-19T01:35:13.517Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-19T01:35:13.534Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-19T01:35:13.550Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19 02:35:13.710 ThaliTest[460:496809] client session: connected
2015-12-19 02:35:13.711 ThaliTest[460:496809] client session: stateChange:1->2 Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:35:13.768 ThaliTest[460:496790] server session: not connected Apple-Iphone6-1_PT3166
,2015-12-19 02:35:13.910 ThaliTest[460:496791] client session: fireConnectCallback: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:35:13.910 ThaliTest[460:496791] jxcore: connect: success
2015-12-19T01:35:13.910Z SendDataConnector.js: CLIENT connected to ,53950, error: null
2015-12-19T01:35:13.911Z SendDataConnector.js: CLIENT starting client 
2015-12-19 02:35:13.912 ThaliTest[460:495966] client: relay established
2015-12-19 02:35:13.913 ThaliTest[460:495966] client: new accepted socket: 0x1ca01c70
,2015-12-19T01:35:13.924Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19T01:35:14.635Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-19T01:35:14.685Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-19T01:35:14.686Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-19T01:35:14.687Z SendDataConnector.js: CLIENT Stop now
,2015-12-19T01:35:14.688Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-19 02:35:14.689 ThaliTest[460:496147] jxcore: disconnect
2015-12-19 02:35:14.689 ThaliTest[460:496147] client session: disconnectFromPeer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:35:14.689 ThaliTest[460:496147] client session: disconnect
,2015-12-19 02:35:14.689 ThaliTest[460:496147] client session: stateChange:2->0 Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:35:14.699 ThaliTest[460:496147] jxcore: disconnect: success
2015-12-19T01:35:14.701Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9396.+XAJIw==
---- round done--------
startWithNextDevice
,2015-12-19 02:35:40.421 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:35:40.454 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:35:40.454 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:35:40.459 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,appEnteredForeground wasn't registered
,2015-12-19 02:36:10.016 ThaliTest[460:495966] client: lost peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:36:10.016 ThaliTest[460:495966] client session: onPeerLost: Apple-IpadAir2-1_PT4132.HrCdVA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4132.HrCdVA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-19 02:36:10.420 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:36:10.896 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4132.HrCdVA==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-19 02:36:11.958 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:36:11.958 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:36:40.421 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:36:40.458 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:36:40.459 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:36:43.849 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,appEnteringBackground wasn't registered
,2015-12-19 02:37:10.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:37:10.377 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:37:10.377 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:37:10.576 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:37:40.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:37:40.376 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:37:40.377 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:37:40.379 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:38:10.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:38:10.377 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:38:10.378 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:38:10.380 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,appEnteredForeground wasn't registered
,2015-12-19 02:38:40.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:38:40.443 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:38:40.445 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:38:40.445 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:39:10.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:39:10.379 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:39:10.379 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:39:10.380 ThaliTest[460:495966] client: fou,nd peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:39:40.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:39:40.377 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:39:40.377 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:39:40.379 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:40:10.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:40:40.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:40:40.375 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:40:40.375 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:40:40.377 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:41:10.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:41:10.373 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:41:10.377 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:41:10.380 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:41:40.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:42:10.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:42:10.374 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:42:10.375 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:42:10.375 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:42:40.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:42:40.374 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:42:40.374 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:42:40.375 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:43:10.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:43:10.375 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:43:10.376 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:43:10.376 ThaliTest[460:495966] client: fou,nd peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:43:40.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:44:10.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:44:10.371 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:44:10.372 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:44:10.376 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:44:40.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:45:10.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:45:10.374 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:45:10.374 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:45:10.375 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:45:40.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:45:40.375 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:45:40.375 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:45:40.375 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:46:10.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:46:10.372 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:46:10.373 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:46:10.377 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:46:40.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:46:40.373 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:46:40.378 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:46:40.378 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:47:10.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:47:10.374 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:47:10.374 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:47:10.379 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:47:40.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:48:10.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:48:10.370 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:48:10.371 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:48:10.373 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:48:40.343 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:48:40.372 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:48:40.374 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:48:40.374 ThaliTest[460:495966] client: fou,nd peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:49:10.343 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:49:40.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:49:40.374 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:49:40.375 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:49:40.377 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:50:10.344 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:50:10.373 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:50:10.374 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:50:10.376 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:50:40.328 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:50:40.359 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:50:40.360 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:50:40.360 ThaliTest[460:495966] client: fo,und peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:51:10.328 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:51:10.358 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:51:10.358 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:51:10.364 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:51:40.328 ThaliTest[460:495966] multipeer session: restart
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-19T01:51:41.034Z SendDataConnector.js: CLIENT Stop now
,2015-12-19 02:52:10.328 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:52:10.357 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:52:10.357 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:52:10.360 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:52:40.328 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:52:40.357 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:52:40.359 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:52:40.359 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:53:10.328 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:53:40.328 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:53:40.356 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:53:40.359 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:53:40.360 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:54:10.328 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:54:40.328 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:54:40.358 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:54:40.358 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:54:40.363 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:55:02.105 ThaliTest[460:495966] client: lost peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:55:02.105 ThaliTest[460:495966] client session: onPeerLost: Apple-IpadAir2-1_PT4132.HrCdVA==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-IpadAir2-1_PT4132.HrCdVA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-19 02:55:02.597 ThaliTest[460:495966] client: lost peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:55:02.598 ThaliTest[460:495966] client session: onPeerLost: Apple-Iphone6-1_PT3166.5e8qRw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT3166.5e8qRw==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-19 02:55:02.600 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.TB3Mww==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4132.TB3Mww==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
,2015-12-19 02:55:02.640 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.6hHfhA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3166.6hHfhA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
,2015-12-19 02:55:10.328 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:55:40.328 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:55:40.358 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.TB3Mww==
2015-12-19 02:55:40.358 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:55:40.359 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.6hHfhA==
,2015-12-19 02:56:10.328 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:56:10.358 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:56:10.358 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.TB3Mww==
2015-12-19 02:56:10.360 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.6hHfhA==
,2015-12-19 02:56:40.328 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:56:40.357 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.TB3Mww==
2015-12-19 02:56:40.358 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:56:40.364 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.6hHfhA==
,2015-12-19 02:57:10.328 ThaliTest[460:495966] multipeer session: restart
,2015-12-19 02:57:10.356 ThaliTest[460:495966] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:57:10.358 ThaliTest[460:495966] client: found peer: Apple-IpadAir2-1_PT4132.TB3Mww==
2015-12-19 02:57:10.359 ThaliTest[460:495966] client: found peer: Apple-Iphone6-1_PT3166.6hHfhA==

```
