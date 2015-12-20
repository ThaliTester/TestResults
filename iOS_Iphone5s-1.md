#### Test 506502785b2d2b2_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502785b2d2b2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/46EB0C62-5938-42B5-9A4E-E8356F4A743E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/46EB0C62-5938-42B5-9A4E-E8356F4A743E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502785b2d2b2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502785b2d2b2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A7B3FB06-5CE6-414B-8918-30F2C0F9B4F8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60902"
,(lldb)     command script import "/tmp/46EB0C62-5938-42B5-9A4E-E8356F4A743E/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-20 03:39:42.454 ThaliTest[594:554235] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4E674E91-2544-4AA2-99BF-7ABB03EE8D91/Library/Cookies/Cookies.binarycookies
,2015-12-20 03:39:42.913 ThaliTest[594:554235] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-20 03:39:42.915 ThaliTest[594:554235] Multi-tasking -> Device: YES, App: YES
,2015-12-20 03:39:42.925 ThaliTest[594:554235] Unlimited access to network resources
,2015-12-20 03:39:42.941 ThaliTest[594:554235] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-20 03:39:52.043 ThaliTest[594:554235] Resetting plugins due to page load.
,2015-12-20 03:39:55.584 ThaliTest[594:554235] Finished load of: file:///var/mobile/Containers/Bundle/Application/A7B3FB06-5CE6-414B-8918-30F2C0F9B4F8/ThaliTest.app/www/index.html
,2015-12-20 03:39:55.784 ThaliTest[594:554235] JXcore Cordova plugin initializing
,2015-12-20 03:39:55.786 ThaliTest[594:554587] JXcore instance initializing
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
,2015-12-20 03:39:57.122 ThaliTest[594:554235] THREAD WARNING: ['JXcore'] took '90.741943' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 52930
,2015-12-20 03:44:42.759 ThaliTest[594:554587] jxcore: startBroadcasting
,2015-12-20 03:44:42.773 ThaliTest[594:554587] server: starting Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:44:42.776 ThaliTest[594:554587] multipeer session: start timer: 0x1944e670
2015-12-20 03:44:42.777 ThaliTest[594:554587] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT7946
2015-12-20 03:44:42.778 ThaliTest[594:554587] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
,2015-12-20T02:44:42.781Z SendDataTCPServer.js: TCP/IP server is bound to port: 52930
,2015-12-20 03:44:44.036 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1975.nu3zFw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20T02:44:44.047Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20T02:44:44.048Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20T02:44:44.049Z SendDataConnector.js: do connect now
,2015-12-20 03:44:44.050 ThaliTest[594:554587] jxcore: connect Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:44:44.051 ThaliTest[594:554587] client session: connect
2015-12-20 03:44:44.051 ThaliTest[594:554587] client session: stateChange:0->1 Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:44:44.630 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT27.Ee1r/w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-20 03:44:44.735 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5083.BRI7qQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-20 03:44:49.070 ThaliTest[594:555138] client session: connected
2015-12-20 03:44:49.071 ThaliTest[594:555138] client session: stateChange:1->2 Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:44:49.139 ThaliTest[594:555129] client session: fireConnectCallback: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:44:49.140 ThaliTest[594:555129] jxcore: connect: success
,2015-12-20T02:44:49.142Z SendDataConnector.js: CLIENT connected to 52933, error: null
,2015-12-20T02:44:49.143Z SendDataConnector.js: CLIENT starting client 
,2015-12-20 03:44:49.147 ThaliTest[594:554235] client: relay established
2015-12-20 03:44:49.148 ThaliTest[594:554235] client: new accepted socket: 0x19458600
,2015-12-20T02:44:49.160Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-20T02:44:49.653Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-20T02:44:49.666Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-20T02:44:49.680Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-20T02:44:49.680Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-20T02:44:49.681Z SendDataConnector.js: CLIENT Stop now
2015-12-20T02:44:49.681Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-20 03:44:49.682 ThaliTest[594:554587] jxcore: disconnect
,2015-12-20 03:44:49.683 ThaliTest[594:554587] client session: disconnectFromPeer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:44:49.683 ThaliTest[594:554587] client session: disconnect
,2015-12-20 03:44:49.684 ThaliTest[594:554587] client session: stateChange:2->0 Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:44:49.752 ThaliTest[594:554587] jxcore: disconnect: success
,2015-12-20T02:44:49.753Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT1975.nu3zFw==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20T02:44:49.754Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20T02:44:49.755Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20T02:44:49.755Z SendDataConnector.js: do connect now
,2015-12-20 03:44:49.755 ThaliTest[594:554587] jxcore: connect Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:44:49.756 ThaliTest[594:554587] client session: connect
,2015-12-20 03:44:49.757 ThaliTest[594:554587] client session: stateChange:0->1 Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:44:51.900 ThaliTest[594:554235] multipeer session: reset timer
2015-12-20 03:44:51.901 ThaliTest[594:554235] multipeer session: stop timer
2015-12-20 03:44:51.901 ThaliTest[594:554235] multipeer session: start timer: 0x1944e670
2015-12-20 ,03:44:51.901 ThaliTest[594:554235] server session: connect
2015-12-20 03:44:51.902 ThaliTest[594:554235] server session: stateChange:0->1 Apple-Iphone6-1_PT27
,2015-12-20 03:44:51.915 ThaliTest[594:554235] server: accepting invitation Apple-Iphone6-1_PT27
,2015-12-20 03:44:51.954 ThaliTest[594:554235] multipeer session: reset timer
,2015-12-20 03:44:51.954 ThaliTest[594:554235] multipeer session: stop timer
,2015-12-20 03:44:51.956 ThaliTest[594:554235] multipeer session: start timer: 0x1944e670
,2015-12-20 03:44:51.957 ThaliTest[594:554235] server session: connect
,2015-12-20 03:44:51.959 ThaliTest[594:554235] server session: stateChange:0->1 Apple-Iphone5-1_PT1975
,2015-12-20 03:44:51.985 ThaliTest[594:554235] server: accepting invitation Apple-Iphone5-1_PT1975
,2015-12-20 03:44:52.396 ThaliTest[594:554235] multipeer session: reset timer
2015-12-20 03:44:52.396 ThaliTest[594:554235] multipeer session: stop timer
2015-12-20 03:44:52.396 ThaliTest[594:554235] multipeer session: start timer: 0x1944e670
2015-12-20 03:44:52.396 ThaliTest[594:554235] server session: connect
2015-12-20 03:44:52.396 ThaliTest[594:554235] server session: stateChange:0->1 Apple-IpadAir2-1_PT5083
2015-12-20 03:44:52.400 ThaliTest[594:554235] server: accepting invitation Apple-IpadAir2-1_PT5083
,2015-12-20 03:44:54.314 ThaliTest[594:555129] client session: connected
2015-12-20 03:44:54.315 ThaliTest[594:555129] client session: stateChange:1->2 Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:44:54.376 ThaliTest[594:555138] client session: fireConnectCallback: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:44:54.377 ThaliTest[594:555138] jxcore: connect: success
2015-12-20T02:44:54.378Z SendDataConnector.js: CLIENT connected to 52936, error: null
2015-12-20T02:44:54.379Z SendDataConnector.js: CLIENT starting client 
,2015-12-20 03:44:54.384 ThaliTest[594:554235] client: relay established
2015-12-20 03:44:54.384 ThaliTest[594:554235] client: new accepted socket: 0x194568c0
,2015-12-20T02:44:54.396Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-20T02:44:54.893Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-20T02:44:54.907Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-20T02:44:54.907Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-20T02:44:54.908Z SendDataConnector.js: CLIENT Stop now
,2015-12-20T02:44:54.908Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-20 03:44:54.909 ThaliTest[594:554587] jxcore: disconnect
2015-12-20 03:44:54.909 ThaliTest[594:554587] client session: disconnectFromPeer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:44:54.909 ThaliTest[594:554587] client session: disconnect
2015-12-20 03:44:54.909 ThaliTest[594:554587] client session: stateChange:2->0 Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:44:54.917 ThaliTest[594:554587] jxcore: disconnect: success
2015-12-20T02:44:54.918Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT27.Ee1r/w==
---- round done--------
startWithNextDevice
device[3]: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20T02:44:54.921Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20T02:44:54.921Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20T02:44:,54.921Z SendDataConnector.js: do connect now
,2015-12-20 03:44:54.921 ThaliTest[594:554587] jxcore: connect Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:44:54.924 ThaliTest[594:554587] client session: connect
2015-12-20 03:44:54.925 ThaliTest[594:554587] client session: stateChange:0->1 Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:44:55.044 ThaliTest[594:555130] server session: connected
2015-12-20 03:44:55.044 ThaliTest[594:555130] server session: stateChange:1->2 Apple-Iphone5-1_PT1975
,2015-12-20 03:44:55.109 ThaliTest[594:555133] server session: connected
,2015-12-20 03:44:55.109 ThaliTest[594:555133] server session: stateChange:1->2 Apple-Iphone6-1_PT27
,2015-12-20 03:44:55.120 ThaliTest[594:554235] server relay: connected (to port: 52930)
,2015-12-20T02:44:55.123Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-20 03:44:55.363 ThaliTest[594:554235] server relay: connected (to port: 52930)
,2015-12-20T02:44:55.367Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-20 03:44:55.534 ThaliTest[594:555138] server session: connected
2015-12-20 03:44:55.535 ThaliTest[594:555138] server session: stateChange:1->2 Apple-IpadAir2-1_PT5083
,2015-12-20 03:44:55.646 ThaliTest[594:554235] server relay: connected (to port: 52930)
,2015-12-20T02:44:55.656Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-20T02:44:55.887Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-20T02:44:55.910Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
2015-12-20T02:44:55.954Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
2015-12-20T02:44:55.970Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
2015-12-20T02:44:55.971Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
2015-12-20T02:44:55.971Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-20T02:44:56.086Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
2015-12-20T02:44:56.087Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-20T02:44:56.099Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-20 03:44:56.155 ThaliTest[594:555130] server session: not connected Apple-Iphone6-1_PT27
,2015-12-20 03:44:56.170 ThaliTest[594:555130] server session: not connected Apple-IpadAir2-1_PT5083
,2015-12-20 03:44:56.203 ThaliTest[594:555130] server session: not connected Apple-Iphone5-1_PT1975
,2015-12-20 03:44:58.571 ThaliTest[594:555180] client session: connected
2015-12-20 03:44:58.571 ThaliTest[594:555180] client session: stateChange:1->2 Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:44:58.599 ThaliTest[594:555129] client session: fireConnectCallback: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:44:58.599 ThaliTest[594:555129] jxcore: connect: success
2015-12-20T02:44:58.600Z SendDataConnector.js: CLIENT connected to 52942, error: null
2015-12-20T02:44:58.601Z SendDataConnector.js: CLIENT starting client 
,2015-12-20 03:44:58.605 ThaliTest[594:554235] client: relay established
2015-12-20 03:44:58.606 ThaliTest[594:554235] client: new accepted socket: 0x19379900
,2015-12-20T02:44:58.617Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-20T02:44:59.029Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-20T02:44:59.055Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-20T02:44:59.081Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-20T02:44:59.081Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-20T02:44:59.082Z SendDataConnector.js: CLIENT Stop now
2015-12-20T02:44:59.082Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-20 03:44:59.083 ThaliTest[594:554587] jxcore: disconnect
2015-12-20 03:44:59.083 ThaliTest[594:554587] client session: disconnectFromPeer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:44:59.083 ThaliTest[594:554587] client session: disconnect
,2015-12-20 03:44:59.083 ThaliTest[594:554587] client session: stateChange:2->0 Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:44:59.151 ThaliTest[594:554587] jxcore: disconnect: success
2015-12-20T02:44:59.151Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5083.BRI7qQ==
---- round done--------
startWithNextDevice
,2015-12-20 03:45:22.397 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:45:52.397 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:45:52.511 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:45:52.512 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:45:52.512 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:46:22.397 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:46:22.449 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:46:22.449 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:46:22.452 ThaliTest[594:554235] client: found ,peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:46:52.397 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:46:52.458 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:46:52.459 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:46:52.460 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:47:22.397 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:47:23.337 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:47:23.337 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:47:23.338 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:47:52.397 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:47:52.456 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:47:52.456 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:47:52.457 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:48:22.397 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:48:22.454 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:48:22.454 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:48:22.457 ThaliTest[594:554235] client: found ,peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:48:52.397 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:48:52.657 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:48:52.657 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:48:52.658 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:49:22.397 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:49:23.347 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:49:23.348 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:49:23.348 ThaliTest[594:554235] client: found ,peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:49:52.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:49:52.449 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:49:52.449 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:49:52.450 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:50:22.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:50:22.451 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:50:22.451 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:50:22.455 ThaliTest[594:554235] client: found ,peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:50:52.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:51:22.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:51:22.449 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:51:22.450 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:51:22.451 ThaliTest[594:554235] client: fou,nd peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:51:52.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:51:52.447 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:51:52.447 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:51:52.448 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:52:22.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:52:22.604 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:52:22.604 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:52:22.605 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:52:52.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:52:52.446 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:52:52.446 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:52:52.447 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:53:22.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:53:52.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:53:53.089 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:53:53.089 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:53:53.092 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:54:22.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:54:52.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:54:52.749 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:54:52.749 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:54:52.749 ThaliTest[594:554235] client: found ,peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:55:22.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:55:22.448 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:55:22.449 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:55:22.451 ThaliTest[594:554235] client: found ,peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:55:52.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:55:52.442 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:55:52.443 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:55:52.501 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:56:22.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:56:22.446 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:56:22.446 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:56:22.447 ThaliTest[594:554235] client: found ,peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:56:52.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:56:52.448 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:56:52.448 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:56:52.449 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:57:22.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:57:22.658 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:57:22.658 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:57:22.659 ThaliTest[594:554235] client: found, peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:57:52.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:57:52.468 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:57:52.469 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:57:52.472 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:58:22.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:58:22.447 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:58:22.448 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:58:22.450 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:58:52.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:58:52.447 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:58:52.448 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:58:52.452 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:59:22.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 03:59:22.458 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:59:22.458 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:59:22.459 ThaliTest[594:554235] client: found, peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:59:52.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 04:00:22.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 04:00:22.446 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:00:22.447 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 04:00:22.457 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 04:00:52.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 04:00:53.363 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 04:00:53.364 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:00:53.364 ThaliTest[594:554235] client: found ,peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 04:01:22.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 04:01:22.448 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:01:22.448 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 04:01:22.449 ThaliTest[594:554235] client: found ,peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-20T03:01:22.785Z SendDataConnector.js: CLIENT Stop now
,2015-12-20 04:01:52.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 04:01:52.447 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:01:52.448 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 04:01:52.450 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 04:02:22.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 04:02:22.478 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:02:22.479 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 04:02:22.479 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 04:02:52.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 04:02:52.452 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 04:02:52.452 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 04:02:52.453 ThaliTest[594:554235] client: found, peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 04:03:22.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 04:03:22.447 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 04:03:22.448 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 04:03:22.448 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 04:03:52.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 04:03:52.624 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 04:03:52.625 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 04:03:52.625 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 04:04:22.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 04:04:22.448 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:04:22.448 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 04:04:22.449 ThaliTest[594:554235] client: fou,nd peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 04:04:44.043 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.xRGq6Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT27.xRGq6Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
,2015-12-20 04:04:45.152 ThaliTest[594:554235] client: lost peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 04:04:45.152 ThaliTest[594:554235] client session: onPeerLost: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 04:04:45.153 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.ybzVtw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5083.BRI7qQ==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5083.ybzVtw==","peerName":"(null)","peerAvailable,":true}]
Found peer : (null), Available: true
startWithNextDevice
,2015-12-20 04:04:48.094 ThaliTest[594:554235] client: lost peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 04:04:48.094 ThaliTest[594:554235] client session: onPeerLost: Apple-Iphone6-1_PT27.Ee1r/w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphon,e6-1_PT27.Ee1r/w==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-20 04:04:52.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 04:04:52.449 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:04:52.450 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.xRGq6Q==
2015-12-20 04:04:52.453 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.ybzVtw==
,2015-12-20 04:05:22.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 04:05:22.444 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.xRGq6Q==
2015-12-20 04:05:22.445 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 04:05:22.456 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.ybzVtw==
,2015-12-20 04:05:52.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 04:05:52.444 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.xRGq6Q==
2015-12-20 04:05:52.445 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:05:52.447 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.ybzVtw==
,2015-12-20 04:06:22.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 04:06:22.448 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:06:22.449 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.xRGq6Q==
2015-12-20 04:06:22.450 ThaliTest[594:554235] client: found ,peer: Apple-IpadAir2-1_PT5083.ybzVtw==
,2015-12-20 04:06:52.392 ThaliTest[594:554235] multipeer session: restart
,2015-12-20 04:06:52.451 ThaliTest[594:554235] client: found peer: Apple-IpadAir2-1_PT5083.ybzVtw==
2015-12-20 04:06:52.452 ThaliTest[594:554235] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:06:52.452 ThaliTest[594:554235] client: found peer: Apple-Iphone6-1_PT27.xRGq6Q==

```
