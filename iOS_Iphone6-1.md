#### Test 50650278161ce7f_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278161ce7f/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/5934387E-CDD2-41A6-B540-CCCE1B349056/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/5934387E-CDD2-41A6-B540-CCCE1B349056/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278161ce7f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278161ce7f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6B406A73-4F19-4253-B055-4BCE1D2E873D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60635"
,(lldb)     command script import "/tmp/5934387E-CDD2-41A6-B540-CCCE1B349056/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-19 02:30:00.208 ThaliTest[509:424140] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F7F6B459-8031-4D79-9AE1-7E70EDA08FA3/Library/Cookies/Cookies.binarycookies
,2015-12-19 02:30:00.508 ThaliTest[509:424140] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-19 02:30:00.509 ThaliTest[509:424140] Multi-tasking -> Device: YES, App: YES
,2015-12-19 02:30:00.518 ThaliTest[509:424140] Unlimited access to network resources
,2015-12-19 02:30:00.526 ThaliTest[509:424140] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-19 02:30:09.186 ThaliTest[509:424140] Resetting plugins due to page load.
,2015-12-19 02:30:12.274 ThaliTest[509:424140] Finished load of: file:///var/mobile/Containers/Bundle/Application/6B406A73-4F19-4253-B055-4BCE1D2E873D/ThaliTest.app/www/index.html
,2015-12-19 02:30:12.291 ThaliTest[509:424140] JXcore Cordova plugin initializing
,2015-12-19 02:30:12.293 ThaliTest[509:424450] JXcore instance initializing
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
,2015-12-19 02:30:13.478 ThaliTest[509:424140] THREAD WARNING: ['JXcore'] took '83.129150' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
serverPort is 53747
,2015-12-19 02:35:01.045 ThaliTest[509:424450] jxcore: startBroadcasting
,2015-12-19 02:35:01.061 ThaliTest[509:424450] server: starting Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:35:01.063 ThaliTest[509:424450] multipeer session: start timer: 0x15604410
,2015-12-19 02:35:01.065 ThaliTest[509:424450] THEMultipeerSession initialized peer Apple-Iphone6-1_PT3166
2015-12-19 02:35:01.066 ThaliTest[509:424450] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
,2015-12-19T01:35:01.074Z SendDataTCPServer.js: TCP/IP server is bound to port: 53747
,2015-12-19 02:35:02.206 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4132.HrCdVA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
startWithNextDevice
,device[1]: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19T01:35:02.211Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19T01:35:02.212Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT4132.HrCdVA==,
2015-12-19T01:35:02.213Z SendDataConnector.js: do connect now
,2015-12-19 02:35:02.214 ThaliTest[509:424450] jxcore: connect Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:35:02.214 ThaliTest[509:424450] client session: connect
2015-12-19 02:35:02.216 ThaliTest[509:424450] client session: stateChange:0->1 Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:35:02.432 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9396.+XAJIw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-19 02:35:02.473 ThaliTest[509:424140] multipeer session: reset timer
2015-12-19 02:35:02.473 ThaliTest[509:424140] multipeer session: stop timer
2015-12-19 02:35:02.474 ThaliTest[509:424140] multipeer session: start timer: 0x15604410
2015-12-19 ,02:35:02.474 ThaliTest[509:424140] server session: connect
2015-12-19 02:35:02.474 ThaliTest[509:424140] server session: stateChange:0->1 Apple-Iphone5-1_PT9897
2015-12-19 02:35:02.482 ThaliTest[509:424140] server: accepting invitation Apple-Iphone5-1_PT9897
,2015-12-19 02:35:02.534 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9897.wDmYaQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-19 02:35:02.596 ThaliTest[509:424140] multipeer session: reset timer
,2015-12-19 02:35:02.597 ThaliTest[509:424140] multipeer session: stop timer
,2015-12-19 02:35:02.597 ThaliTest[509:424140] multipeer session: start timer: 0x15604410
,2015-12-19 02:35:02.598 ThaliTest[509:424140] server session: connect
,2015-12-19 02:35:02.598 ThaliTest[509:424140] server session: stateChange:0->1 Apple-Iphone5s-1_PT9396
,2015-12-19 02:35:02.605 ThaliTest[509:424140] server: accepting invitation Apple-Iphone5s-1_PT9396
,2015-12-19 02:35:05.298 ThaliTest[509:424959] server session: connected
2015-12-19 02:35:05.298 ThaliTest[509:424959] server session: stateChange:1->2 Apple-Iphone5s-1_PT9396
,2015-12-19 02:35:05.369 ThaliTest[509:424975] client session: connected
2015-12-19 02:35:05.369 ThaliTest[509:424975] client session: stateChange:1->2 Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:35:05.423 ThaliTest[509:424975] client session: fireConnectCallback: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:35:05.423 ThaliTest[509:424975] jxcore: connect: success
2015-12-19T01:35:05.426Z SendDataTCPServer.js: TCP/IP server connec,ted
2015-12-19T01:35:05.429Z SendDataConnector.js: CLIENT connected to 53750, error: null
2015-12-19T01:35:05.430Z SendDataConnector.js: CLIENT starting client 
,2015-12-19 02:35:05.433 ThaliTest[509:424140] server relay: connected (to port: 53747)
2015-12-19 02:35:05.435 ThaliTest[509:424140] client: relay established
2015-12-19 02:35:05.436 ThaliTest[509:424140] client: new accepted socket: 0x16c24dc0
,2015-12-19T01:35:05.452Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19 02:35:05.556 ThaliTest[509:424975] server session: connected
,2015-12-19 02:35:05.556 ThaliTest[509:424975] server session: stateChange:1->2 Apple-Iphone5-1_PT9897
,2015-12-19 02:35:05.609 ThaliTest[509:424140] server relay: connected (to port: 53747)
,2015-12-19T01:35:05.735Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-19T01:35:05.871Z SendDataTCPServer.js: TCP/IP server has received 47246 bytes of data
,2015-12-19T01:35:05.886Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19 02:35:06.002 ThaliTest[509:424960] server session: not connected Apple-Iphone5s-1_PT9396
,2015-12-19T01:35:06.082Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-19T01:35:06.083Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-19T01:35:06.084Z SendDataConnector.js: CLIENT Stop now
,2015-12-19T01:35:06.084Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-19 02:35:06.085 ThaliTest[509:424450] jxcore: disconnect
2015-12-19 02:35:06.086 ThaliTest[509:424450] client session: disconnectFromPeer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:35:06.086 ThaliTest[509:424450] client session: disconnect
2015-12-19 02:35:06.086 ThaliTest[509:424450] client session: stateChange:2->0 Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:35:06.092 ThaliTest[509:424450] jxcore: disconnect: success
2015-12-19T01:35:06.094Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT4132.HrCdVA==
---- round done--------
startWithNextDevice
device[2]: Appl,e-Iphone5s-1_PT9396.+XAJIw==
2015-12-19T01:35:06.095Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19T01:35:06.095Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19T01:,35:06.095Z SendDataConnector.js: do connect now
2015-12-19 02:35:06.096 ThaliTest[509:424450] jxcore: connect Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:35:06.096 ThaliTest[509:424450] client session: connect
2015-12-19 02:35:06.096 ThaliTest[509:42,4450] client session: stateChange:0->1 Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19T01:35:06.217Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-19T01:35:06.238Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-19T01:35:06.268Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-19T01:35:06.281Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19 02:35:06.666 ThaliTest[509:424960] server session: not connected Apple-Iphone5-1_PT9897
,2015-12-19 02:35:09.551 ThaliTest[509:424959] client session: connected
2015-12-19 02:35:09.552 ThaliTest[509:424959] client session: stateChange:1->2 Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:35:09.581 ThaliTest[509:424965] client session: fireConnectCallback: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:35:09.581 ThaliTest[509:424965] jxcore: connect: success
2015-12-19T01:35:09.582Z SendDataConnector.js: CLIENT connected to 53755, error: null
,2015-12-19T01:35:09.583Z SendDataConnector.js: CLIENT starting client 
,2015-12-19 02:35:09.587 ThaliTest[509:424140] client: relay established
2015-12-19 02:35:09.587 ThaliTest[509:424140] client: new accepted socket: 0x16bd4710
,2015-12-19T01:35:09.600Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19T01:35:10.063Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-19T01:35:10.076Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-19T01:35:10.211Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-19T01:35:10.212Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-19T01:35:10.213Z SendDataConnector.js: CLIENT Stop now
,2015-12-19T01:35:10.213Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-19 02:35:10.214 ThaliTest[509:424450] jxcore: disconnect
2015-12-19 02:35:10.215 ThaliTest[509:424450] client session: disconnectFromPeer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:35:10.215 ThaliTest[509:424450] client session: disconnect
,2015-12-19 02:35:10.215 ThaliTest[509:424450] client session: stateChange:2->0 Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:35:10.223 ThaliTest[509:424450] jxcore: disconnect: success
2015-12-19T01:35:10.224Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9396.+XAJIw==
---- round done--------
startWithNextDevice
device[3]: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19T01:35:10.224Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19T01:35:10.225Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19T01:35:,10.225Z SendDataConnector.js: do connect now
2015-12-19 02:35:10.225 ThaliTest[509:424450] jxcore: connect Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:35:10.225 ThaliTest[509:424450] client session: connect
2015-12-19 02:35:10.225 ThaliTest[509:424450] client session: stateChange:0->1 Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:35:10.794 ThaliTest[509:424140] multipeer session: reset timer
2015-12-19 02:35:10.794 ThaliTest[509:424140] multipeer session: stop timer
2015-12-19 02:35:10.794 ThaliTest[509:424140] multipeer session: start timer: 0x15604410
2015-12-19 ,02:35:10.795 ThaliTest[509:424140] server session: connect
2015-12-19 02:35:10.795 ThaliTest[509:424140] server session: stateChange:0->1 Apple-IpadAir2-1_PT4132
2015-12-19 02:35:10.800 ThaliTest[509:424140] server: accepting invitation Apple-IpadAir2-1_PT4132
,2015-12-19 02:35:13.186 ThaliTest[509:424975] client session: connected
2015-12-19 02:35:13.187 ThaliTest[509:424975] client session: stateChange:1->2 Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:35:13.197 ThaliTest[509:424959] client session: fireConnectCallback: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:35:13.198 ThaliTest[509:424959] jxcore: connect: success
2015-12-19T01:35:13.199Z SendDataConnector.js: CLIENT connected to 5,3758, error: null
2015-12-19T01:35:13.199Z SendDataConnector.js: CLIENT starting client 
,2015-12-19 02:35:13.203 ThaliTest[509:424140] client: relay established
2015-12-19 02:35:13.204 ThaliTest[509:424140] client: new accepted socket: 0x16bcdc50
,2015-12-19T01:35:13.213Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19 02:35:13.407 ThaliTest[509:424959] server session: connected
,2015-12-19 02:35:13.407 ThaliTest[509:424959] server session: stateChange:1->2 Apple-IpadAir2-1_PT4132
,2015-12-19 02:35:13.411 ThaliTest[509:424140] server relay: connected (to port: 53747)
,2015-12-19T01:35:13.460Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-19T01:35:13.627Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-19T01:35:13.652Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-19T01:35:13.675Z SendDataTCPServer.js: TCP/IP server has received 57852 bytes of data
,2015-12-19T01:35:13.677Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-19T01:35:13.677Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2015-12-19T01:35:13.679Z SendDataConnector.js: CLIENT Stop now
2015-12-19T01:35:13.679Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-19 02:35:13.680 ThaliTest[509:424450] jxcore: disconnect
2015-12-19 02:35:13.680 ThaliTest[509:424450] client session: disconnectFromPeer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:35:13.680 ThaliTest[509:424450] client session: disconnect
2015-12-19 02:35:13.681 ThaliTest[509:424450] client session: stateChange:2->0 Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:35:13.687 ThaliTest[509:424450] jxcore: disconnect: success
2015-12-19T01:35:13.687Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9897.wDmYaQ==
---- round done--------
startWithNextDevice
,2015-12-19T01:35:13.701Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19 02:35:13.749 ThaliTest[509:424960] server session: not connected Apple-IpadAir2-1_PT4132
,2015-12-19 02:35:40.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:36:10.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:36:10.832 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:36:10.833 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:36:11.916 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:36:40.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:37:10.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:37:10.829 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:37:10.830 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:37:10.830 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:37:40.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:37:40.836 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:37:40.837 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:37:40.837 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:38:10.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:38:10.835 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:38:10.836 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:38:11.835 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:38:40.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:38:40.836 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:38:40.838 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:38:40.839 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:39:10.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:39:10.837 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:39:10.838 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:39:10.838 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:39:40.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:39:40.835 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:39:40.836 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:39:40.837 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:40:10.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:40:10.836 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:40:10.836 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:40:10.838 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:40:40.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:40:40.837 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:40:40.838 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:40:40.839 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:41:10.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:41:10.839 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:41:10.840 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:41:11.781 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:41:40.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:41:40.835 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:41:40.835 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:41:41.781 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,appEnteredForeground wasn't registered
,2015-12-19 02:42:10.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:42:40.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:42:40.828 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:42:40.830 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:42:40.830 ThaliTest[509:424140] client: fou,nd peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:43:10.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:43:40.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:43:40.832 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:43:40.833 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:43:40.833 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,appEnteringBackground wasn't registered
,Connected to the server!
,2015-12-19 02:44:10.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:44:10.834 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:44:10.834 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:44:10.837 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:44:40.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:45:10.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:45:10.834 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:45:10.835 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:45:10.840 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:45:40.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:45:40.840 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:45:40.840 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:45:40.840 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:46:10.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:46:10.837 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:46:10.838 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:46:10.838 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:46:40.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:46:40.835 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:46:40.836 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:46:40.840 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:47:10.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:47:40.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:47:40.832 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:47:40.833 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:47:41.767 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:48:10.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:48:10.834 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:48:10.835 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:48:11.755 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:48:40.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:48:40.837 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:48:40.838 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:48:40.838 ThaliTest[509:424140] client: fo,und peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:49:10.796 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:49:10.834 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:49:10.835 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:49:10.836 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:49:40.795 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:49:40.834 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:49:40.835 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:49:40.840 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:50:10.743 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:50:10.783 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:50:10.784 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:50:10.787 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:50:40.743 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:50:40.781 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:50:40.781 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:50:40.784 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:51:10.743 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:51:10.783 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:51:10.784 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:51:10.785 ThaliTest[509:424140] client: fou,nd peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,appEnteredForeground wasn't registered
,2015-12-19 02:51:16.227 ThaliTest[509:424140] client: lost peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:51:16.228 ThaliTest[509:424140] client session: onPeerLost: Apple-Iphone5-1_PT9897.wDmYaQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone5-1_PT9897.wDmYaQ==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-19 02:51:17.758 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9897.wDmYaQ==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,appEnteringBackground wasn't registered
,2015-12-19 02:51:40.743 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:51:40.781 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:51:40.785 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:51:40.785 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-19T01:51:41.030Z SendDataConnector.js: CLIENT Stop now
,2015-12-19 02:52:10.743 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:52:10.787 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:52:11.723 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:52:11.724 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:52:40.743 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:52:40.780 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:52:40.781 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:52:40.783 ThaliTest[509:424140] client: fo,und peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:53:10.743 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:53:10.784 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:53:10.784 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:53:10.785 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:53:40.743 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:53:40.781 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:53:40.781 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:53:40.782 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:54:10.743 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:54:40.743 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:54:40.780 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:54:41.751 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:54:41.752 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,teardown
,testSendData stopped
,2015-12-19 02:55:01.441 ThaliTest[509:424450] jxcore: stopBroadcasting
2015-12-19 02:55:01.441 ThaliTest[509:424450] THEMultipeerSession stopping peer
2015-12-19 02:55:01.442 ThaliTest[509:424450] multipeer session: stop timer
2015-12-19 02:55:01.442 Th,aliTest[509:424450] server session: disconnect
2015-12-19 02:55:01.442 ThaliTest[509:424450] server session: stateChange:2->0 Apple-IpadAir2-1_PT4132
2015-12-19 02:55:01.450 ThaliTest[509:424450] server session: disconnect
2015-12-19 02:55:01.450 ThaliT,est[509:424450] server session: stateChange:2->0 Apple-Iphone5-1_PT9897
2015-12-19 02:55:01.457 ThaliTest[509:424450] server session: disconnect
,2015-12-19 02:55:01.457 ThaliTest[509:424450] server session: stateChange:2->0 Apple-Iphone5s-1_PT9396
,2015-12-19 02:55:01.473 ThaliTest[509:424450] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-19T01:55:01.499Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-19T01:55:01.503Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-19T01:55:01.505Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-19T01:55:01.507Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-19 02:55:01.543 ThaliTest[509:424450] jxcore: startBroadcasting
,2015-12-19 02:55:01.549 ThaliTest[509:424450] server: starting Apple-Iphone6-1_PT3166.6hHfhA==
,2015-12-19 02:55:01.552 ThaliTest[509:424450] multipeer session: start timer: 0x16bd8eb0
,2015-12-19 02:55:01.559 ThaliTest[509:424450] THEMultipeerSession initialized peer Apple-Iphone6-1_PT3166
,2015-12-19 02:55:01.560 ThaliTest[509:424450] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-19 02:55:02.021 ThaliTest[509:424140] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:55:02.021 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6,-1_PT3166.5e8qRw==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone6-1_PT3166.5e8qRw==, peerAvailable: true
weAreDoneNow
done, now sending data to server
2015-12-19 02:55:02.027 ThaliTest[509:424140] client: found peer: Apple-Iphon,e5-1_PT9897.wDmYaQ==
,2015-12-19 02:55:02.605 ThaliTest[509:424140] client: lost peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:55:02.605 ThaliTest[509:424140] client session: onPeerLost: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:55:02.606 ThaliTest[509:424140] clien,t: found peer: Apple-IpadAir2-1_PT4132.TB3Mww==
,2015-12-19 02:55:31.560 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:55:31.597 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:55:31.598 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.TB3Mww==
2015-12-19 02:55:31.598 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:56:01.560 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:56:01.602 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:56:01.602 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.TB3Mww==
2015-12-19 02:56:01.603 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:56:31.560 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:57:01.560 ThaliTest[509:424140] multipeer session: restart
,2015-12-19 02:57:01.599 ThaliTest[509:424140] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:57:01.601 ThaliTest[509:424140] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:57:01.602 ThaliTest[509:424140] client: found peer: Apple-IpadAir2-1_PT4132.TB3Mww==

```
