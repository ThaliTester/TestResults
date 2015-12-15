#### Test 50650278cb112b9_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278cb112b9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/040351F8-1960-439B-AAE5-716C49292690/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/040351F8-1960-439B-AAE5-716C49292690/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278cb112b9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278cb112b9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4774DD09-CC15-49E5-B855-2E00F8C7C3F0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56122"
,(lldb)     command script import "/tmp/040351F8-1960-439B-AAE5-716C49292690/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-15 04:19:09.429 ThaliTest[841:1359983] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/364C904C-ACF2-4F38-B865-11A4B5C20FEB/Library/Cookies/Cookies.binarycookies
,2015-12-15 04:19:09.930 ThaliTest[841:1359983] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-15 04:19:09.932 ThaliTest[841:1359983] Multi-tasking -> Device: YES, App: YES
,2015-12-15 04:19:09.937 ThaliTest[841:1359983] Unlimited access to network resources
,2015-12-15 04:19:09.951 ThaliTest[841:1359983] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-15 04:19:19.457 ThaliTest[841:1359983] Resetting plugins due to page load.
,2015-12-15 04:19:22.770 ThaliTest[841:1359983] Finished load of: file:///var/mobile/Containers/Bundle/Application/4774DD09-CC15-49E5-B855-2E00F8C7C3F0/ThaliTest.app/www/index.html
,2015-12-15 04:19:22.976 ThaliTest[841:1359983] JXcore Cordova plugin initializing
,2015-12-15 04:19:22.978 ThaliTest[841:1360343] JXcore instance initializing
Initializing JXcore engine
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
,2015-12-15 04:19:25.407 ThaliTest[841:1359983] THREAD WARNING: ['JXcore'] took '153.062256' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-15 04:25:44.638 ThaliTest[841:1360343] jxcore: startBroadcasting
,2015-12-15 04:25:44.649 ThaliTest[841:1360343] server: starting Apple-Iphone5-1_PT9128.mlJOKQ==
,2015-12-15 04:25:44.650 ThaliTest[841:1360343] multipeer session: start timer: 0x19a04690
,2015-12-15 04:25:44.651 ThaliTest[841:1360343] THEMultipeerSession initialized peer Apple-Iphone5-1_PT9128
,2015-12-15 04:25:44.651 ThaliTest[841:1360343] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-15 04:25:45.871 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.S9LZPw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.S9LZPw==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone6-1_PT1123,.S9LZPw==, peerAvailable: true
,weAreDoneNow
done, now sending data to server
,teardown
,testFindPeers stopped
2015-12-15 04:25:46.880 ThaliTest[841:1360343] jxcore: stopBroadcasting
,2015-12-15 04:25:46.881 ThaliTest[841:1360343] THEMultipeerSession stopping peer
2015-12-15 04:25:46.881 ThaliTest[841:1360343] multipeer session: stop timer
2015-12-15 04:25:46.882 ThaliTest[841:1360343] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 59724
,2015-12-15 04:25:46.941 ThaliTest[841:1360343] jxcore: startBroadcasting
,2015-12-15 04:25:46.945 ThaliTest[841:1360343] server: starting Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:25:46.950 ThaliTest[841:1360343] multipeer session: start timer: 0x19b61db0
,2015-12-15 04:25:46.957 ThaliTest[841:1360343] THEMultipeerSession initialized peer Apple-Iphone5-1_PT9128
,2015-12-15 04:25:46.958 ThaliTest[841:1360343] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2015-12-15T03:25:46.963Z SendDataTCPServer.js: TCP/IP server is bound to port: 59724
,2015-12-15 04:25:47.968 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.uhofxg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tru,e
startWithNextDevice
device[1]: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15T03:25:47.972Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15T03:25:47.972Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15T03:25:47.973Z SendDataConnector.js: do connect now
,2015-12-15 04:25:47.973 ThaliTest[841:1360343] jxcore: connect Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:25:47.974 ThaliTest[841:1360343] client session: connect
2015-12-15 04:25:47.974 ThaliTest[841:1360343] client session: stateChange:0->1 Apple-Ip,hone6-1_PT1123.uhofxg==
,2015-12-15 04:25:48.106 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7023.h41t3A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 04:25:48.168 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9749.OdNUWQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 04:25:51.384 ThaliTest[841:1361047] client session: connected
2015-12-15 04:25:51.384 ThaliTest[841:1361047] client session: stateChange:1->2 Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:25:51.425 ThaliTest[841:1361045] client session: fireConnectCallback: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:25:51.426 ThaliTest[841:1361045] jxcore: connect: success
2015-12-15T03:25:51.427Z SendDataConnector.js: CLIENT connected to, 59727, error: null
2015-12-15T03:25:51.427Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 04:25:51.429 ThaliTest[841:1359983] client: relay established
2015-12-15 04:25:51.429 ThaliTest[841:1359983] client: new accepted socket: 0x19c82360
,2015-12-15T03:25:51.445Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T03:25:52.165Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-15T03:25:52.204Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-15T03:25:52.231Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T03:25:52.232Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-15T03:25:52.234Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T03:25:52.235Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 04:25:52.236 ThaliTest[841:1360343] jxcore: disconnect
2015-12-15 04:25:52.236 ThaliTest[841:1360343] client session: disconnectFromPeer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:25:52.236 ThaliTest[841:1360343] client session: disconnect,
2015-12-15 04:25:52.237 ThaliTest[841:1360343] client session: stateChange:2->0 Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:25:52.245 ThaliTest[841:1360343] jxcore: disconnect: success
2015-12-15T03:25:52.245Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1123.uhofxg==
---- round done--------
startWithNextDevice
device[2]: Appl,e-IpadAir2-1_PT7023.h41t3A==
2015-12-15T03:25:52.246Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15T03:25:52.246Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15T03:,25:52.247Z SendDataConnector.js: do connect now
2015-12-15 04:25:52.247 ThaliTest[841:1360343] jxcore: connect Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:25:52.247 ThaliTest[841:1360343] client session: connect
2015-12-15 04:25:52.248 ThaliTest[841:,1360343] client session: stateChange:0->1 Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:25:55.836 ThaliTest[841:1361047] client session: connected
2015-12-15 04:25:55.836 ThaliTest[841:1361047] client session: stateChange:1->2 Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:25:55.864 ThaliTest[841:1361042] client session: fireConnectCallback: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:25:55.864 ThaliTest[841:1361042] jxcore: connect: success
2015-12-15T03:25:55.865Z SendDataConnector.js: CLIENT connected t,o 59730, error: null
2015-12-15T03:25:55.865Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 04:25:55.867 ThaliTest[841:1359983] client: relay established
2015-12-15 04:25:55.868 ThaliTest[841:1359983] client: new accepted socket: 0x19c8b650
,2015-12-15T03:25:55.880Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T03:25:56.425Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-15T03:25:56.476Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T03:25:56.477Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-15T03:25:56.479Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T03:25:56.479Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 04:25:56.480 ThaliTest[841:1360343] jxcore: disconnect
2015-12-15 04:25:56.481 ThaliTest[841:1360343] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:25:56.481 ThaliTest[841:1360343] client session: disconnec,t
2015-12-15 04:25:56.481 ThaliTest[841:1360343] client session: stateChange:2->0 Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:25:56.490 ThaliTest[841:1360343] jxcore: disconnect: success
2015-12-15T03:25:56.490Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7023.h41t3A==
---- round done--------
startWithNextDevice
device[3]: App,le-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15T03:25:56.491Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15T03:25:56.492Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15T03,:25:56.492Z SendDataConnector.js: do connect now
2015-12-15 04:25:56.492 ThaliTest[841:1360343] jxcore: connect Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:25:56.492 ThaliTest[841:1360343] client session: connect
2015-12-15 04:25:56.493 ThaliTest[841,:1360343] client session: stateChange:0->1 Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:26:02.721 ThaliTest[841:1361042] client session: connected
2015-12-15 04:26:02.721 ThaliTest[841:1361042] client session: stateChange:1->2 Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:26:02.775 ThaliTest[841:1361047] client session: fireConnectCallback: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:26:02.775 ThaliTest[841:1361047] jxcore: connect: success
2015-12-15T03:26:02.776Z SendDataConnector.js: CLIENT connected t,o 59733, error: null
2015-12-15T03:26:02.776Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 04:26:02.779 ThaliTest[841:1359983] client: relay established
2015-12-15 04:26:02.780 ThaliTest[841:1359983] client: new accepted socket: 0x19c80f80
,2015-12-15T03:26:02.791Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T03:26:03.361Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-15T03:26:03.461Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-15T03:26:03.699Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-15T03:26:03.726Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T03:26:03.726Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-15T03:26:03.728Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T03:26:03.729Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 04:26:03.730 ThaliTest[841:1360343] jxcore: disconnect
2015-12-15 04:26:03.730 ThaliTest[841:1360343] client session: disconnectFromPeer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:26:03.730 ThaliTest[841:1360343] client session: disconnec,t
2015-12-15 04:26:03.730 ThaliTest[841:1360343] client session: stateChange:2->0 Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:26:03.740 ThaliTest[841:1360343] jxcore: disconnect: success
2015-12-15T03:26:03.740Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9749.OdNUWQ==
---- round done--------
startWithNextDevice
,2015-12-15 04:26:16.958 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:26:31.844 ThaliTest[841:1359983] multipeer session: reset timer
2015-12-15 04:26:31.844 ThaliTest[841:1359983] multipeer session: stop timer
2015-12-15 04:26:31.844 ThaliTest[841:1359983] multipeer session: start timer: 0x19b61db0
2015-12-,15 04:26:31.844 ThaliTest[841:1359983] server session: connect
,2015-12-15 04:26:31.845 ThaliTest[841:1359983] server session: stateChange:0->1 Apple-IpadAir2-1_PT7023
,2015-12-15 04:26:31.851 ThaliTest[841:1359983] server: accepting invitation Apple-IpadAir2-1_PT7023
,2015-12-15 04:26:34.455 ThaliTest[841:1361290] server session: connected
2015-12-15 04:26:34.455 ThaliTest[841:1361290] server session: stateChange:1->2 Apple-IpadAir2-1_PT7023
,2015-12-15 04:26:34.474 ThaliTest[841:1359983] server relay: connected (to port: 59724)
,2015-12-15T03:26:34.486Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15 04:26:34.670 ThaliTest[841:1359983] multipeer session: reset timer
2015-12-15 04:26:34.670 ThaliTest[841:1359983] multipeer session: stop timer
2015-12-15 04:26:34.670 ThaliTest[841:1359983] multipeer session: start timer: 0x19b61db0
2015-12-,15 04:26:34.671 ThaliTest[841:1359983] server session: connect
2015-12-15 04:26:34.671 ThaliTest[841:1359983] server session: stateChange:0->1 Apple-Iphone6-1_PT1123
,2015-12-15 04:26:34.677 ThaliTest[841:1359983] server: accepting invitation Apple-Iphone6-1_PT1123
,2015-12-15T03:26:34.729Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-15T03:26:34.761Z SendDataTCPServer.js: TCP/IP server has received 50228 bytes of data
,2015-12-15T03:26:34.777Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-15T03:26:34.830Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-15T03:26:34.844Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 04:26:35.139 ThaliTest[841:1361292] server session: not connected Apple-IpadAir2-1_PT7023
,2015-12-15 04:26:36.698 ThaliTest[841:1359983] multipeer session: reset timer
2015-12-15 04:26:36.698 ThaliTest[841:1359983] multipeer session: stop timer
2015-12-15 04:26:36.699 ThaliTest[841:1359983] multipeer session: start timer: 0x19b61db0
2015-12-,15 04:26:36.699 ThaliTest[841:1359983] server session: connect
2015-12-15 04:26:36.699 ThaliTest[841:1359983] server session: stateChange:0->1 Apple-Iphone5s-1_PT9749
2015-12-15 04:26:36.704 ThaliTest[841:1359983] server: accepting invitation Apple-Iphon,e5s-1_PT9749
,2015-12-15 04:26:37.314 ThaliTest[841:1361291] server session: connected
2015-12-15 04:26:37.314 ThaliTest[841:1361291] server session: stateChange:1->2 Apple-Iphone6-1_PT1123
,2015-12-15T03:26:37.333Z SendDataTCPServer.js: TCP/IP server connected
2015-12-15 04:26:37.334 ThaliTest[841:1359983] server relay: connected (to port: 59724)
,2015-12-15T03:26:37.598Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-15T03:26:37.614Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-15T03:26:37.628Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-15T03:26:37.643Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-15T03:26:37.658Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 04:26:37.713 ThaliTest[841:1361291] server session: not connected Apple-Iphone6-1_PT1123
,2015-12-15 04:26:39.627 ThaliTest[841:1361291] server session: connected
2015-12-15 04:26:39.627 ThaliTest[841:1361291] server session: stateChange:1->2 Apple-Iphone5s-1_PT9749
,2015-12-15 04:26:39.656 ThaliTest[841:1359983] server relay: connected (to port: 59724)
2015-12-15T03:26:39.658Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T03:26:40.101Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-15T03:26:40.118Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-15T03:26:40.135Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-15T03:26:40.150Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 04:26:40.235 ThaliTest[841:1361292] server session: not connected Apple-Iphone5s-1_PT9749
,2015-12-15 04:27:06.699 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:27:06.731 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:27:06.732 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:27:06.732 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:27:36.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:28:06.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:28:06.778 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:28:07.655 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:28:07.655 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:28:36.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:28:36.731 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:28:36.731 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:28:36.732 ThaliTest[841:1359983] client:, found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:29:06.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:29:06.732 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:29:07.537 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:29:07.537 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:29:36.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:29:37.813 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:29:37.813 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:29:42.677 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:30:06.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:30:06.731 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:30:06.731 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:30:07.343 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,Connected to the server!
,2015-12-15 04:30:36.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:30:36.732 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:30:36.732 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:30:37.577 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:31:06.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:31:06.731 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:31:06.735 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:31:08.020 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:31:36.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:31:36.967 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:31:36.968 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:31:36.968 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:32:06.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:32:36.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:32:36.729 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:32:36.730 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:32:36.730 ThaliTest[841:1359983] client: ,found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:33:06.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:33:06.731 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:33:06.731 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:33:06.731 ThaliTest[841:1359983] client:, found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:33:24.350 ThaliTest[841:1359983] client: lost peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:33:24.351 ThaliTest[841:1359983] client session: onPeerLost: Apple-Iphone5s-1_PT9749.OdNUWQ==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone5s-1_PT9749.OdNUWQ==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-15 04:33:31.725 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9749.OdNUWQ==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-15 04:33:36.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:33:36.737 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:33:36.738 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:33:45.345 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:34:06.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:34:06.733 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:34:06.733 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:34:07.681 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:34:36.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:34:36.733 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:34:36.734 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:34:37.651 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:35:06.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:35:06.732 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:35:06.732 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:35:06.737 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:35:36.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:35:36.731 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:35:36.731 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:35:36.734 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:35:48.025 ThaliTest[841:1359983] client: lost peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:35:48.025 ThaliTest[841:1359983] client session: onPeerLost: Apple-Iphone6-1_PT1123.uhofxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.uhofxg==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-15 04:36:06.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:36:06.729 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:36:06.731 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:36:09.585 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.uhofxg==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-15 04:36:36.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:36:36.731 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:36:37.646 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:36:37.648 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:37:06.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:37:06.730 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:37:07.550 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:37:07.550 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:37:25.480 ThaliTest[841:1359983] client: lost peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:37:25.482 ThaliTest[841:1359983] client session: onPeerLost: Apple-Iphone6-1_PT1123.uhofxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.uhofxg==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-15 04:37:36.504 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.uhofxg==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-15 04:37:36.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:38:06.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:38:06.730 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:38:06.730 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:38:36.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:38:36.730 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:38:36.731 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:39:06.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:39:06.727 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:39:07.668 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:39:09.386 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:39:09.387 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:39:33.112 ThaliTest[841:1359983] client: lost peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:39:33.113 ThaliTest[841:1359983] client session: onPeerLost: Apple-Iphone6-1_PT1123.uhofxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.uhofxg==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-15 04:39:36.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:39:36.727 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:39:36.730 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:40:06.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:40:06.726 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:40:06.728 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:40:18.689 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.uhofxg==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-15 04:40:36.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:40:36.731 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:40:36.733 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:40:36.734 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:41:04.425 ThaliTest[841:1359983] client: lost peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:41:04.426 ThaliTest[841:1359983] client session: onPeerLost: Apple-Iphone6-1_PT1123.uhofxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT1123.uhofxg==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-15 04:41:06.206 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.uhofxg==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-15 04:41:06.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:41:06.730 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:41:06.731 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:41:06.733 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:41:28.155 ThaliTest[841:1359983] client: lost peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:41:28.155 ThaliTest[841:1359983] client session: onPeerLost: Apple-Iphone6-1_PT1123.uhofxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT1123.uhofxg==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-15 04:41:36.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:42:06.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:42:06.729 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:42:06.729 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:42:10.822 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.uhofxg==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-15T03:42:26.967Z SendDataConnector.js: CLIENT Stop now
,2015-12-15 04:42:36.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:42:36.731 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:42:36.732 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:42:36.736 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:42:40.477 ThaliTest[841:1359983] client: lost peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:42:40.477 ThaliTest[841:1359983] client session: onPeerLost: Apple-Iphone6-1_PT1123.uhofxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.uhofxg==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-15 04:43:06.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:43:06.726 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:43:06.742 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:43:36.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:43:36.727 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:43:37.689 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:43:47.659 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.uhofxg==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-15 04:43:47.662 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:44:06.278 ThaliTest[841:1359983] client: lost peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:44:06.278 ThaliTest[841:1359983] client session: onPeerLost: Apple-Iphone6-1_PT1123.uhofxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.uhofxg==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-15 04:44:06.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:44:06.724 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:44:06.729 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:44:36.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:45:06.700 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:45:06.726 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:45:06.727 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:45:11.632 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.uhofxg==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-15 04:45:36.699 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:45:36.728 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:45:37.659 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:45:37.660 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:46:06.630 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:46:06.660 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:46:07.647 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:46:07.650 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:46:36.630 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:46:36.660 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:46:36.661 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:46:37.350 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:47:06.630 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:47:06.658 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:47:06.660 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:47:06.661 ThaliTest[841:1359983] client:, found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:47:11.228 ThaliTest[841:1359983] client: lost peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:47:11.228 ThaliTest[841:1359983] client session: onPeerLost: Apple-Iphone6-1_PT1123.uhofxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.uhofxg==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-15 04:47:24.272 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.uhofxg==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-15 04:47:36.630 ThaliTest[841:1359983] multipeer session: restart
,2015-12-15 04:47:36.662 ThaliTest[841:1359983] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:47:36.662 ThaliTest[841:1359983] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:47:36.667 ThaliTest[841:1359983] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==

```
