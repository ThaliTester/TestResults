#### Test 50650278161ce7f_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278161ce7f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/8DDCDDAA-A62C-41B9-A9B0-EAF7FF5EBC66/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8DDCDDAA-A62C-41B9-A9B0-EAF7FF5EBC66/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278161ce7f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278161ce7f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D8885242-2C7B-4181-993F-F6BBEB1166C9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60637"
,(lldb)     command script import "/tmp/8DDCDDAA-A62C-41B9-A9B0-EAF7FF5EBC66/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-19 02:30:04.228 ThaliTest[538:419448] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/49682113-ABA1-456E-88C8-75914457715D/Library/Cookies/Cookies.binarycookies
,2015-12-19 02:30:04.614 ThaliTest[538:419448] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-19 02:30:04.616 ThaliTest[538:419448] Multi-tasking -> Device: YES, App: YES
,2015-12-19 02:30:04.625 ThaliTest[538:419448] Unlimited access to network resources
,2015-12-19 02:30:04.639 ThaliTest[538:419448] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-19 02:30:13.500 ThaliTest[538:419448] Resetting plugins due to page load.
,2015-12-19 02:30:16.592 ThaliTest[538:419448] Finished load of: file:///var/mobile/Containers/Bundle/Application/D8885242-2C7B-4181-993F-F6BBEB1166C9/ThaliTest.app/www/index.html
,2015-12-19 02:30:16.867 ThaliTest[538:419448] JXcore Cordova plugin initializing
2015-12-19 02:30:16.870 ThaliTest[538:419759] JXcore instance initializing
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
,2015-12-19 02:30:18.197 ThaliTest[538:419448] THREAD WARNING: ['JXcore'] took '89.630127' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
serverPort is 52508
,2015-12-19 02:35:00.940 ThaliTest[538:419759] jxcore: startBroadcasting
,2015-12-19 02:35:00.957 ThaliTest[538:419759] server: starting Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:35:00.958 ThaliTest[538:419759] multipeer session: start timer: 0x17c5a6f0
,2015-12-19 02:35:00.959 ThaliTest[538:419759] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT9396
2015-12-19 02:35:00.959 ThaliTest[538:419759] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2015-12-19T01:35:00.962Z SendDataTCPServer.js: TCP/IP server is bound to port: 52508
,2015-12-19 02:35:02.137 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3166.5e8qRw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
,device[1]: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19T01:35:02.143Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19T01:35:02.144Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19T01:35:02.145Z SendDataConnector.js: do connect now
,2015-12-19 02:35:02.147 ThaliTest[538:419759] jxcore: connect Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:35:02.148 ThaliTest[538:419759] client session: connect
2015-12-19 02:35:02.148 ThaliTest[538:419759] client session: stateChange:0->1 Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:35:02.360 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:35:02.360 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5,-1_PT9897.wDmYaQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4132.HrCdVA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-19 02:35:05.347 ThaliTest[538:420214] client session: connected
2015-12-19 02:35:05.347 ThaliTest[538:420214] client session: stateChange:1->2 Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:35:05.358 ThaliTest[538:420214] client session: fireConnectCallback: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:35:05.359 ThaliTest[538:420214] jxcore: connect: success
2015-12-19T01:35:05.361Z SendDataConnector.js: CLIENT connected to 5,2511, error: null
2015-12-19T01:35:05.362Z SendDataConnector.js: CLIENT starting client 
,2015-12-19 02:35:05.367 ThaliTest[538:419448] client: relay established
2015-12-19 02:35:05.367 ThaliTest[538:419448] client: new accepted socket: 0x17c671e0
,2015-12-19T01:35:05.384Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19T01:35:05.868Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-19T01:35:05.928Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-19T01:35:05.928Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-19T01:35:05.929Z SendDataConnector.js: CLIENT Stop now
2015-12-19T01:35:05.929Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-19 02:35:05.930 ThaliTest[538:419759] jxcore: disconnect
,2015-12-19 02:35:05.931 ThaliTest[538:419759] client session: disconnectFromPeer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:35:05.932 ThaliTest[538:419759] client session: disconnect
,2015-12-19 02:35:05.932 ThaliTest[538:419759] client session: stateChange:2->0 Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:35:06.001 ThaliTest[538:419759] jxcore: disconnect: success
2015-12-19T01:35:06.001Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3166.5e8qRw==
---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19T01:35:06.003Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19T01:35:06.003Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19T01:35:06.004Z SendDataConnector.js: do connect now
,2015-12-19 02:35:06.004 ThaliTest[538:419759] jxcore: connect Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:35:06.004 ThaliTest[538:419759] client session: connect
2015-12-19 02:35:06.004 ThaliTest[538:419759] client session: stateChange:0->1 Apple-Iphon,e5-1_PT9897.wDmYaQ==
,2015-12-19 02:35:06.461 ThaliTest[538:419448] multipeer session: reset timer
2015-12-19 02:35:06.461 ThaliTest[538:419448] multipeer session: stop timer
2015-12-19 02:35:06.462 ThaliTest[538:419448] multipeer session: start timer: 0x17c5a6f0
,2015-12-19 02:35:06.463 ThaliTest[538:419448] server session: connect
2015-12-19 02:35:06.464 ThaliTest[538:419448] server session: stateChange:0->1 Apple-Iphone6-1_PT3166
,2015-12-19 02:35:06.474 ThaliTest[538:419448] server: accepting invitation Apple-Iphone6-1_PT3166
,2015-12-19 02:35:07.382 ThaliTest[538:419448] multipeer session: reset timer
2015-12-19 02:35:07.382 ThaliTest[538:419448] multipeer session: stop timer
2015-12-19 02:35:07.382 ThaliTest[538:419448] multipeer session: start timer: 0x17c5a6f0
2015-12-19 ,02:35:07.383 ThaliTest[538:419448] server session: connect
2015-12-19 02:35:07.383 ThaliTest[538:419448] server session: stateChange:0->1 Apple-IpadAir2-1_PT4132
,2015-12-19 02:35:07.395 ThaliTest[538:419448] server: accepting invitation Apple-IpadAir2-1_PT4132
,2015-12-19 02:35:09.024 ThaliTest[538:420235] client session: connected
2015-12-19 02:35:09.025 ThaliTest[538:420235] client session: stateChange:1->2 Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:35:09.028 ThaliTest[538:420235] client session: fireConnectCallback: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:35:09.032 ThaliTest[538:420235] jxcore: connect: success
2015-12-19T01:35:09.033Z SendDataConnector.js: CLIENT connected to 5,2514, error: null
2015-12-19T01:35:09.033Z SendDataConnector.js: CLIENT starting client 
2015-12-19 02:35:09.037 ThaliTest[538:419448] client: relay established
2015-12-19 02:35:09.038 ThaliTest[538:419448] client: new accepted socket: 0x17bf71e0
,2015-12-19T01:35:09.050Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19T01:35:09.411Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-19T01:35:09.531Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-19T01:35:09.532Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2015-12-19T01:35:09.532Z SendDataConnector.js: CLIENT Stop now
,2015-12-19T01:35:09.532Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-19 02:35:09.533 ThaliTest[538:419759] jxcore: disconnect
,2015-12-19 02:35:09.534 ThaliTest[538:419759] client session: disconnectFromPeer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:35:09.535 ThaliTest[538:419759] client session: disconnect
,2015-12-19 02:35:09.535 ThaliTest[538:419759] client session: stateChange:2->0 Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:35:09.539 ThaliTest[538:420213] server session: connected
2015-12-19 02:35:09.539 ThaliTest[538:420213] server session: stateChange:1->2 Apple-Iphone6-1_PT3166
,2015-12-19 02:35:09.585 ThaliTest[538:419448] server relay: connected (to port: 52508)
,2015-12-19 02:35:09.605 ThaliTest[538:419759] jxcore: disconnect: success
,2015-12-19T01:35:09.605Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9897.wDmYaQ==
---- round done--------
,startWithNextDevice
,device[3]: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19T01:35:09.607Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19T01:35:09.607Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19T01:35:09.607Z SendDataConnector.js: do connect now
,2015-12-19 02:35:09.608 ThaliTest[538:419759] jxcore: connect Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:35:09.608 ThaliTest[538:419759] client session: connect
,2015-12-19 02:35:09.609 ThaliTest[538:419759] client session: stateChange:0->1 Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19T01:35:09.628Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-19T01:35:10.008Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-19T01:35:10.037Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-19T01:35:10.127Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19 02:35:10.143 ThaliTest[538:420213] server session: connected
2015-12-19 02:35:10.143 ThaliTest[538:420213] server session: stateChange:1->2 Apple-IpadAir2-1_PT4132
,2015-12-19 02:35:10.148 ThaliTest[538:419448] server relay: connected (to port: 52508)
,2015-12-19T01:35:10.158Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-19 02:35:10.242 ThaliTest[538:420214] server session: not connected Apple-Iphone6-1_PT3166
,2015-12-19T01:35:10.473Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-19T01:35:10.494Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
2015-12-19T01:35:10.511Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-19T01:35:10.532Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-19T01:35:10.548Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-19T01:35:10.587Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-19T01:35:10.601Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19 02:35:10.666 ThaliTest[538:420285] server session: not connected Apple-IpadAir2-1_PT4132
,2015-12-19 02:35:10.790 ThaliTest[538:419448] multipeer session: reset timer
2015-12-19 02:35:10.790 ThaliTest[538:419448] multipeer session: stop timer
2015-12-19 02:35:10.790 ThaliTest[538:419448] multipeer session: start timer: 0x17c5a6f0
,2015-12-19 02:35:10.791 ThaliTest[538:419448] server session: connect
2015-12-19 02:35:10.791 ThaliTest[538:419448] server session: stateChange:0->1 Apple-Iphone5-1_PT9897
,2015-12-19 02:35:10.803 ThaliTest[538:419448] server: accepting invitation Apple-Iphone5-1_PT9897
,2015-12-19 02:35:12.813 ThaliTest[538:420286] client session: connected
2015-12-19 02:35:12.818 ThaliTest[538:420286] client session: stateChange:1->2 Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:35:12.822 ThaliTest[538:420286] client session: fireConn,ectCallback: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:35:12.822 ThaliTest[538:420286] jxcore: connect: success
2015-12-19T01:35:12.823Z SendDataConnector.js: CLIENT connected to 52519, error: null
2015-12-19T01:35:12.824Z SendDataConnector.js: CLIENT starting client 
,2015-12-19 02:35:12.829 ThaliTest[538:419448] client: relay established
2015-12-19 02:35:12.830 ThaliTest[538:419448] client: new accepted socket: 0x17c77d90
,2015-12-19T01:35:12.844Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19T01:35:13.141Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-19T01:35:13.204Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-19T01:35:13.205Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-19T01:35:13.205Z SendDataConnector.js: CLIENT Stop now
2015-12-19T01:35:13.205Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-19 02:35:13.206 ThaliTest[538:419759] jxcore: disconnect
,2015-12-19 02:35:13.206 ThaliTest[538:419759] client session: disconnectFromPeer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:35:13.207 ThaliTest[538:419759] client session: disconnect
,2015-12-19 02:35:13.208 ThaliTest[538:419759] client session: stateChange:2->0 Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:35:13.274 ThaliTest[538:419759] jxcore: disconnect: success
,2015-12-19T01:35:13.275Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT4132.HrCdVA==
,---- round done--------
,startWithNextDevice
,2015-12-19 02:35:13.739 ThaliTest[538:420235] server session: connected
2015-12-19 02:35:13.740 ThaliTest[538:420235] server session: stateChange:1->2 Apple-Iphone5-1_PT9897
,2015-12-19 02:35:13.746 ThaliTest[538:419448] server relay: connected (to port: 52508)
,2015-12-19T01:35:13.757Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-19T01:35:14.382Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-19T01:35:14.401Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-19T01:35:14.421Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-19T01:35:14.440Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-19T01:35:14.458Z SendDataTCPServer.js: TCP/IP server has received 89364 bytes of data
,2015-12-19T01:35:14.473Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19 02:35:14.713 ThaliTest[538:420286] server session: not connected Apple-Iphone5-1_PT9897
,2015-12-19 02:35:40.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:35:40.860 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:35:40.860 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:35:40.862 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:36:10.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:36:10.921 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:36:10.921 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:36:11.903 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:36:40.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:37:10.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:37:10.848 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:37:10.856 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:37:10.856 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:37:40.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:37:40.856 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:37:40.857 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:37:40.859 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,Connected to the server!
,2015-12-19 02:38:10.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:38:40.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:38:40.856 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:38:40.857 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:38:40.859 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:39:10.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:39:10.852 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:39:10.862 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:39:10.864 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:39:40.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:39:40.849 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:39:40.850 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:39:40.852 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:40:10.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:40:10.845 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:40:10.846 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:40:10.846 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:40:40.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:40:40.858 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:40:40.859 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:40:40.860 ThaliTest[538:419448] client: fou,nd peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:41:10.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:41:10.846 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:41:10.854 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:41:11.764 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:41:40.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:42:10.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:42:10.851 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:42:10.852 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:42:10.853 ThaliTest[538:419448] client: foun,d peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:42:40.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:42:40.854 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:42:40.855 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:42:40.858 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:43:10.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:43:10.851 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:43:10.852 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:43:10.863 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:43:40.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:43:40.854 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:43:40.855 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:43:40.857 ThaliTest[538:419448] client: foun,d peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:44:10.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:44:40.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:44:40.848 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:44:40.849 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:44:40.851 ThaliTest[538:419448] client: foun,d peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:45:10.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:45:10.871 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:45:10.872 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:45:10.887 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:45:40.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:46:10.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:46:10.845 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:46:10.855 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:46:10.856 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:46:40.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:46:40.850 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:46:40.851 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:46:40.854 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:47:10.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:47:40.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:47:40.824 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:47:40.826 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:47:41.742 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:48:10.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:48:10.857 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:48:10.857 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:48:11.785 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:48:40.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:49:10.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:49:10.851 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:49:10.851 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:49:10.863 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:49:40.792 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:49:40.849 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:49:40.851 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:49:41.848 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:50:10.763 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:50:10.827 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:50:10.832 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:50:10.833 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:50:40.762 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:51:10.763 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:51:10.823 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:51:10.824 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:51:10.827 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:51:40.763 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:51:40.846 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:51:40.849 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-19T01:51:40.947Z SendDataConnector.js: CLIENT Stop now
,2015-12-19 02:51:41.787 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:52:10.763 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:52:10.829 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:52:10.831 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:52:11.728 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:52:40.763 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:52:40.823 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:52:40.825 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:52:40.826 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:53:10.763 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:53:10.822 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:53:10.823 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:53:10.825 ThaliTest[538:419448] client: foun,d peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:53:40.763 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:54:10.763 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:54:10.833 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:54:10.843 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:54:10.843 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:54:40.763 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:54:40.824 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:54:40.825 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:54:41.791 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:55:02.115 ThaliTest[538:419448] client: lost peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:55:02.115 ThaliTest[538:419448] client session: onPeerLost: Apple-IpadAir2-1_PT4132.HrCdVA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4132.HrCdVA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-19 02:55:02.611 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.TB3Mww==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4132.TB3Mww==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
startWithNextDevice
,2015-12-19 02:55:02.655 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.6hHfhA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3166.6hHfhA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
,2015-12-19 02:55:10.465 ThaliTest[538:419448] client: lost peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:55:10.465 ThaliTest[538:419448] client session: onPeerLost: Apple-Iphone6-1_PT3166.5e8qRw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3166.5e8qRw==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-19 02:55:10.763 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:55:10.831 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:55:10.832 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.6hHfhA==
2015-12-19 02:55:10.837 ThaliTest[538:419448] client: foun,d peer: Apple-IpadAir2-1_PT4132.TB3Mww==
,2015-12-19 02:55:40.763 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:55:40.821 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:55:40.822 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.TB3Mww==
2015-12-19 02:55:40.823 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.6hHfhA==
,2015-12-19 02:56:10.763 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:56:10.840 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.6hHfhA==
2015-12-19 02:56:10.841 ThaliTest[538:419448] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:56:10.850 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.TB3Mww==
,2015-12-19 02:56:40.763 ThaliTest[538:419448] multipeer session: restart
,2015-12-19 02:56:40.832 ThaliTest[538:419448] client: found peer: Apple-IpadAir2-1_PT4132.TB3Mww==
2015-12-19 02:56:40.833 ThaliTest[538:419448] client: found peer: Apple-Iphone6-1_PT3166.6hHfhA==
2015-12-19 02:56:40.833 ThaliTest[538:419448] client: fou,nd peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:57:10.763 ThaliTest[538:419448] multipeer session: restart

```
