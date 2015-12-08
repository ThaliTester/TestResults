#### Test 52971095ef317fc_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52971095ef317fc/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/09DF1178-5537-4214-BA25-A58A0724DAA3/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/09DF1178-5537-4214-BA25-A58A0724DAA3/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52971095ef317fc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52971095ef317fc/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BC05DB38-F490-4B44-8768-6B1C31CFC45A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51143"
,(lldb)     command script import "/tmp/09DF1178-5537-4214-BA25-A58A0724DAA3/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-08 17:06:12.511 ThaliTest[429:344261] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1E98C2FF-FF8B-450E-B672-8629CFA820BF/Library/Cookies/Cookies.binarycookies
,2015-12-08 17:06:13.059 ThaliTest[429:344261] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-08 17:06:13.060 ThaliTest[429:344261] Multi-tasking -> Device: YES, App: YES
,2015-12-08 17:06:13.067 ThaliTest[429:344261] Unlimited access to network resources
,2015-12-08 17:06:13.078 ThaliTest[429:344261] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-08 17:06:23.525 ThaliTest[429:344261] Resetting plugins due to page load.
,2015-12-08 17:06:27.118 ThaliTest[429:344261] Finished load of: file:///var/mobile/Containers/Bundle/Application/BC05DB38-F490-4B44-8768-6B1C31CFC45A/ThaliTest.app/www/index.html
,2015-12-08 17:06:27.327 ThaliTest[429:344261] JXcore Cordova plugin initializing
,2015-12-08 17:06:27.329 ThaliTest[429:344467] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone5-1_PT8010
,attempting to connect to test coordinator
,check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 52319
2015-12-08 17:14:44.118 ThaliTest[429:344467] jxcore: startBroadcasting
,2015-12-08 17:14:44.129 ThaliTest[429:344467] server: starting Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:14:44.130 ThaliTest[429:344467] multipeer session: start timer: 0x1c696150
2015-12-08 17:14:44.131 ThaliTest[429:344467] THEMultipeerSession init,ialized peer Apple-Iphone5-1_PT8010
2015-12-08 17:14:44.131 ThaliTest[429:344467] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-08T16:14:44.133Z SendDataTCPServer.js: TCP/IP server is bound to port: 52319
,2015-12-08 17:14:45.196 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7651.u5AQgA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08T16:14:45.200Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08T16:14:45.201Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7651.u5AQgA==
20,15-12-08T16:14:45.201Z SendDataConnector.js: do connect now
2015-12-08 17:14:45.201 ThaliTest[429:344467] jxcore: connect Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:14:45.202 ThaliTest[429:344467] client session: connect
2015-12-08 17:14:45.202 Thali,Test[429:344467] client session: stateChange:0->1 Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08 17:14:45.821 ThaliTest[429:344261] multipeer session: reset timer
2015-12-08 17:14:45.821 ThaliTest[429:344261] multipeer session: stop timer
2015-12-08 17:14:45.821 ThaliTest[429:344261] multipeer session: start timer: 0x1c696150
2015-12-08 ,17:14:45.821 ThaliTest[429:344261] server session: connect
2015-12-08 17:14:45.821 ThaliTest[429:344261] server session: stateChange:0->1 Apple-Iphone6-1_PT7651
,2015-12-08 17:14:45.828 ThaliTest[429:344261] server: accepting invitation Apple-Iphone6-1_PT7651
,2015-12-08 17:14:45.947 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4957.VBxUsw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-08 17:14:46.910 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7186.b/2OUQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-08 17:14:49.628 ThaliTest[429:345363] server session: connected
,2015-12-08 17:14:49.628 ThaliTest[429:345363] server session: stateChange:1->2 Apple-Iphone6-1_PT7651
,2015-12-08 17:14:49.687 ThaliTest[429:344261] server relay: connected (to port: 52319)
,2015-12-08T16:14:49.693Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08T16:14:49.982Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-08 17:14:50.176 ThaliTest[429:345357] client session: connected
2015-12-08 17:14:50.176 ThaliTest[429:345357] client session: stateChange:1->2 Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08T16:14:50.192Z SendDataTCPServer.js: TCP/IP server has received 45198 bytes of data
,2015-12-08 17:14:50.197 ThaliTest[429:345363] client session: fireConnectCallback: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:14:50.200 ThaliTest[429:345363] jxcore: connect: success
2015-12-08T16:14:50.201Z SendDataTCPServer.js: TCP/IP server has rec,eived 100000 bytes of data
2015-12-08T16:14:50.205Z SendDataConnector.js: CLIENT connected to 52323, error: null
2015-12-08T16:14:50.206Z SendDataConnector.js: CLIENT starting client 
2015-12-08 17:14:50.210 ThaliTest[429:344261] client: relay establish,ed
2015-12-08 17:14:50.210 ThaliTest[429:344261] client: new accepted socket: 0x1c789ba0
,2015-12-08T16:14:50.224Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08 17:14:50.447 ThaliTest[429:345361] server session: not connected Apple-Iphone6-1_PT7651
,2015-12-08T16:14:51.035Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-08T16:14:51.099Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-08T16:14:51.099Z SendDataConnector.js: got all data for this round
,2015-12-08T16:14:51.101Z SendDataConnector.js: CLIENT Stop now
2015-12-08T16:14:51.101Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:14:51.103 ThaliTest[429:344467] jxcore: disconnect
2015-12-08 17:14:51.104 ThaliTest[429:344467] client session: disconnectFromPeer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:14:51.104 ThaliTest[429:344467] client session: disconnect
2015-12-08 17:14:51.105 ThaliTest[429:344467] client session: stateChange:2->0 Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08 17:14:51.118 ThaliTest[429:344467] jxcore: disconnect: success
2015-12-08T16:14:51.118Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7651.u5AQgA==
---- round done--------
device[2]: Apple-IpadAir2-1_PT4957.VB,xUsw==
2015-12-08T16:14:51.120Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08T16:14:51.122Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08T16:14:51.123Z SendDataCon,nector.js: do connect now
,2015-12-08 17:14:51.123 ThaliTest[429:344467] jxcore: connect Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:14:51.127 ThaliTest[429:344467] client session: connect
2015-12-08 17:14:51.127 ThaliTest[429:344467] client session: stateChange:0->1 Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:14:51.763 ThaliTest[429:344261] multipeer session: reset timer
2015-12-08 17:14:51.763 ThaliTest[429:344261] multipeer session: stop timer
2015-12-08 17:14:51.764 ThaliTest[429:344261] multipeer session: start timer: 0x1c696150
2015-12-08 17:14:51.764 ThaliTest[429:344261] server session: connect
2015-12-08 17:14:51.764 ThaliTest[429:344261] server session: stateChange:0->1 Apple-Iphone5s-1_PT7186
,2015-12-08 17:14:51.770 ThaliTest[429:344261] server: accepting invitation Apple-Iphone5s-1_PT7186
,2015-12-08 17:14:52.010 ThaliTest[429:344261] multipeer session: reset timer
2015-12-08 17:14:52.010 ThaliTest[429:344261] multipeer session: stop timer
2015-12-08 17:14:52.010 ThaliTest[429:344261] multipeer session: start timer: 0x1c696150
2015-12-08 17:14:52.011 ThaliTest[429:344261] server session: connect
2015-12-08 17:14:52.011 ThaliTest[429:344261] server session: stateChange:0->1 Apple-IpadAir2-1_PT4957
,2015-12-08 17:14:52.020 ThaliTest[429:344261] server: accepting invitation Apple-IpadAir2-1_PT4957
,2015-12-08 17:14:54.670 ThaliTest[429:345357] client session: connected
2015-12-08 17:14:54.670 ThaliTest[429:345357] client session: stateChange:1->2 Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:14:54.673 ThaliTest[429:345357] client session: fireConnectCallback: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:14:54.673 ThaliTest[429:345357] jxcore: connect: success
2015-12-08T16:14:54.674Z SendDataConnector.js: CLIENT connected to 52326, error: null
2015-12-08T16:14:54.674Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 17:14:54.676 ThaliTest[429:344261] client: relay established
2015-12-08 17:14:54.677 ThaliTest[429:344261] client: new accepted socket: 0x1c792bb0
,2015-12-08T16:14:54.689Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08 17:14:55.175 ThaliTest[429:345361] server session: connected
2015-12-08 17:14:55.175 ThaliTest[429:345361] server session: stateChange:1->2 Apple-IpadAir2-1_PT4957
,2015-12-08 17:14:55.186 ThaliTest[429:344261] server relay: connected (to port: 52319)
,2015-12-08T16:14:55.286Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08T16:14:55.696Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-08 17:14:55.701 ThaliTest[429:345361] server session: connected
2015-12-08 17:14:55.702 ThaliTest[429:345361] server session: stateChange:1->2 Apple-Iphone5s-1_PT7186
,2015-12-08T16:14:55.714Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-08T16:14:55.753Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-08T16:14:55.766Z SendDataTCPServer.js: TCP/IP server has received 87458 bytes of data
,2015-12-08T16:14:55.768Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-08T16:14:55.769Z SendDataConnector.js: got all data for this round
2015-12-08T16:14:55.771Z SendDataConnector.js: CLIENT Stop now
2015-12-08T16:14:55.771Z SendDataCo,nnector.js: CLIENT closeClientSocket
,2015-12-08 17:14:55.771 ThaliTest[429:344467] jxcore: disconnect
2015-12-08 17:14:55.773 ThaliTest[429:344467] client session: disconnectFromPeer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:14:55.773 ThaliTest[429:344467] client session: disconnect
,2015-12-08 17:14:55.773 ThaliTest[429:344467] client session: stateChange:2->0 Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:14:55.788 ThaliTest[429:344467] jxcore: disconnect: success
2015-12-08T16:14:55.789Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT4957.VBxUsw==
---- round done--------
device[3]: Apple-Iphone5s-1_PT7186.b,/2OUQ==
2015-12-08T16:14:55.791Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08T16:14:55.792Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08T16:14:55.792Z SendDataCo,nnector.js: do connect now
,2015-12-08 17:14:55.792 ThaliTest[429:344467] jxcore: connect Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:14:55.798 ThaliTest[429:344467] client session: connect
,2015-12-08 17:14:55.806 ThaliTest[429:344467] client session: stateChange:0->1 Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08T16:14:55.846Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 17:14:55.915 ThaliTest[429:344261] server relay: connected (to port: 52319)
,2015-12-08T16:14:55.927Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08T16:14:56.484Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-08T16:14:56.515Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-08T16:14:56.533Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-08T16:14:56.549Z SendDataTCPServer.js: TCP/IP server has received 83078 bytes of data
,2015-12-08 17:14:56.558 ThaliTest[429:345361] server session: not connected Apple-IpadAir2-1_PT4957
,2015-12-08T16:14:56.564Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 17:14:56.916 ThaliTest[429:345361] server session: not connected Apple-Iphone5s-1_PT7186
,2015-12-08 17:15:00.610 ThaliTest[429:345389] client session: connected
2015-12-08 17:15:00.611 ThaliTest[429:345389] client session: stateChange:1->2 Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:15:01.023 ThaliTest[429:345365] client session: fireConnectCallback: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:15:01.023 ThaliTest[429:345365] jxcore: connect: success
2015-12-08T16:15:01.024Z SendDataConnector.js: CLIENT connected to 52331, error: null
2015-12-08T16:15:01.024Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 17:15:01.026 ThaliTest[429:344261] client: relay established
2015-12-08 17:15:01.027 ThaliTest[429:344261] client: new accepted socket: 0x1c2c8230
,2015-12-08T16:15:01.040Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T16:15:01.662Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-08T16:15:01.677Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-08T16:15:01.678Z SendDataConnector.js: got all data for this round
,2015-12-08T16:15:01.679Z SendDataConnector.js: CLIENT Stop now
2015-12-08T16:15:01.680Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:15:01.680 ThaliTest[429:344467] jxcore: disconnect
2015-12-08 17:15:01.681 ThaliTest[429:344467] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:15:01.682 ThaliTest[429:344467] client session: disconnect
2015-12-08 17:15:01.682 ThaliTest[429:344467] client session: stateChange:2->0 Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:15:01.691 ThaliTest[429:344467] jxcore: disconnect: success
2015-12-08T16:15:01.692Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7186.b/2OUQ==
---- round done--------
weAreDoneNow , resultArray.length: 3,
done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-Iphone5-1_PT8010","time":17583,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT7651.u5AQgA==","time":5900,"result":"OK","connections":1,"done,Rounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT4957.VBxUsw==","time":4647,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT7186.b/2OUQ==","time":5886,"resu,lt":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 5900 ms, 99% : 5900 ms, 95 : 5900 ms, 90% : 5900 ms.
Result count 3, range 4647 ms to  5900 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-12-08T16:15:01.700Z SendDataConnector.js: CLIENT Stop now
,2015-12-08T16:15:01.701Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:15:22.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:15:22.246 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:15:22.249 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:15:22.249 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:15:52.011 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:15:52.053 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:15:52.053 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:15:52.053 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 17:16:22.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:16:22.048 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:16:22.057 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:16:22.058 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 17:16:52.011 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:16:52.050 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:16:52.051 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:16:52.086 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 17:17:22.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:17:22.048 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:17:22.048 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:17:52.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:17:52.050 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:17:52.052 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:17:52.054 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:18:22.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:18:22.048 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:18:22.048 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:18:22.057 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:18:52.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:18:52.048 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:18:52.055 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:18:52.056 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:19:22.012 ThaliTest[429:344261] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 17:19:52.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:19:52.045 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:19:52.047 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:19:52.047 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 17:20:22.012 ThaliTest[429:344261] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:20:52.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:20:52.043 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:20:52.044 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:20:52.044 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 17:21:22.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:21:22.047 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:21:22.047 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:21:22.048 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:21:52.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:21:52.046 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:21:52.047 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:21:52.047 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:22:22.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:22:22.044 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:22:22.044 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:22:22.046 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:22:52.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:22:52.043 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:22:52.043 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:22:52.044 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 17:23:22.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:23:22.038 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:23:22.038 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:23:22.039 ThaliTest[429:344261] client: fou,nd peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:23:52.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:23:52.042 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:23:52.042 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:23:52.044 ThaliTest[429:344261] client: fou,nd peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:24:22.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:24:22.042 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:24:22.042 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:24:22.042 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:24:52.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:24:52.041 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:24:52.042 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:24:52.042 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:25:22.012 ThaliTest[429:344261] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 17:25:52.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:25:52.042 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:25:52.043 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:25:52.044 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:26:22.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:26:22.116 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:26:22.116 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:26:22.116 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-08 17:26:52.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:26:52.044 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:26:52.045 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:26:52.045 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:27:22.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:27:52.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:27:52.042 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:27:52.042 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:27:52.042 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:28:22.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:28:22.042 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:28:22.042 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08 17:28:22.048 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:28:52.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:28:52.047 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:28:52.047 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:28:52.049 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:29:22.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:29:22.045 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:29:22.046 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:29:22.510 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:29:52.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:29:52.041 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08 17:29:52.047 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:29:52.048 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:30:22.011 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:30:22.044 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:30:22.044 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:30:22.046 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-08 17:30:52.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:30:52.043 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:30:52.044 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08 17:30:52.049 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-08 17:31:22.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:31:22.041 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:31:22.042 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:31:22.044 ThaliTest[429:344261] client: fou,nd peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:31:52.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:31:52.042 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:31:52.042 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:31:52.049 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:32:22.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:32:22.043 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08 17:32:22.047 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:32:22.048 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-08 17:32:52.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:32:52.044 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:32:52.045 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:32:52.048 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:33:22.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:33:22.040 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08 17:33:22.047 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:33:22.047 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:33:52.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:34:22.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:34:22.747 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:34:28.796 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:34:28.810 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-08 17:34:52.012 ThaliTest[429:344261] multipeer session: restart
,2015-12-08 17:34:52.043 ThaliTest[429:344261] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:34:52.043 ThaliTest[429:344261] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:34:52.348 ThaliTest[429:344261] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==

```
