#### Test 51986340afa1391_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51986340afa1391/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/8CE6B06E-BB39-44B2-8DD4-7800A7108146/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/8CE6B06E-BB39-44B2-8DD4-7800A7108146/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51986340afa1391/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51986340afa1391/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C099A0F9-C207-4368-B93C-3A6E4025BC94/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49797"
,(lldb)     command script import "/tmp/8CE6B06E-BB39-44B2-8DD4-7800A7108146/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-07 11:06:53.958 ThaliTest[369:121823] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C734E0B8-0969-4540-AE9F-7A38748191FA/Library/Cookies/Cookies.binarycookies
,2015-12-07 11:06:54.326 ThaliTest[369:121823] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-07 11:06:54.328 ThaliTest[369:121823] Multi-tasking -> Device: YES, App: YES
,2015-12-07 11:06:54.337 ThaliTest[369:121823] Unlimited access to network resources
,2015-12-07 11:06:54.350 ThaliTest[369:121823] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 11:07:03.153 ThaliTest[369:121823] Resetting plugins due to page load.
,2015-12-07 11:07:06.081 ThaliTest[369:121823] Finished load of: file:///var/mobile/Containers/Bundle/Application/C099A0F9-C207-4368-B93C-3A6E4025BC94/ThaliTest.app/www/index.html
,2015-12-07 11:07:06.276 ThaliTest[369:121823] JXcore Cordova plugin initializing
,2015-12-07 11:07:06.277 ThaliTest[369:122139] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone6-1_PT6748
,attempting to connect to test coordinator
check test folder
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 50385
,2015-12-07 11:14:10.501 ThaliTest[369:122139] jxcore: startBroadcasting
,2015-12-07 11:14:10.522 ThaliTest[369:122139] server: starting Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:14:10.523 ThaliTest[369:122139] multipeer session: start timer: 0x184e0600
2015-12-07 11:14:10.524 ThaliTest[369:122139] THEMultipeerSession initialized peer Apple-Iphone6-1_PT6748
2015-12-07 11:14:10.526 ThaliTest[369:122139] jxcore: start,Broadcasting: success
StartBroadcasting started ok
2015-12-07T10:14:10.529Z SendDataTCPServer.js: TCP/IP server is bound to port: 50385
,2015-12-07 11:14:11.234 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5016.vGdGUg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07T10:14:11.241Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07T10:14:11.242Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07T10:14:11.243Z SendDataConnector.js: do connect now
,2015-12-07 11:14:11.244 ThaliTest[369:122139] jxcore: connect Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:14:11.244 ThaliTest[369:122139] client session: connect
2015-12-07 11:14:11.245 ThaliTest[369:122139] client session: stateChange:0->1 Apple-Ipad,Air2-1_PT5016.vGdGUg==
,2015-12-07 11:14:11.653 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6457.6Oi+cQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-07 11:14:11.821 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT94.0IbCHA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-07 11:14:12.152 ThaliTest[369:121823] multipeer session: reset timer
2015-12-07 11:14:12.152 ThaliTest[369:121823] multipeer session: stop timer
2015-12-07 11:14:12.152 ThaliTest[369:121823] multipeer session: start timer: 0x184e0600
2015-12-07 ,11:14:12.154 ThaliTest[369:121823] server session: connect
,2015-12-07 11:14:12.154 ThaliTest[369:121823] server session: stateChange:0->1 Apple-IpadAir2-1_PT5016
,2015-12-07 11:14:12.167 ThaliTest[369:121823] server: accepting invitation Apple-IpadAir2-1_PT5016
,2015-12-07 11:14:14.850 ThaliTest[369:122855] server session: connected
2015-12-07 11:14:14.850 ThaliTest[369:122855] server session: stateChange:1->2 Apple-IpadAir2-1_PT5016
2015-12-07 11:14:14.852 ThaliTest[369:122863] client session: connected
2015-12-07 11:14:14.852 ThaliTest[369:122863] client session: stateChange:1->2 Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:14:14.912 ThaliTest[369:122854] client session: fireConnectCallback: Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:14:14.913 ThaliTest[369:122854] jxcore: connect: success
,2015-12-07T10:14:14.920Z SendDataTCPServer.js: TCP/IP server connected
2015-12-07 11:14:14.920 ThaliTest[369:121823] server relay: connected (to port: 50385)
2015-12-07T10:14:14.921Z SendDataConnector.js: CLIENT connected to 50388, error: null
2015-12-07T10:14:14.922Z SendDataConnector.js: CLIENT starting client 
,2015-12-07 11:14:14.927 ThaliTest[369:121823] client: relay established
,2015-12-07 11:14:14.928 ThaliTest[369:121823] client: new accepted socket: 0x16d550c0
,2015-12-07T10:14:14.946Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07T10:14:15.299Z SendDataTCPServer.js: TCP/IP server has received 4096 bytes of data
,2015-12-07T10:14:15.313Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-07T10:14:15.360Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07T10:14:15.363Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-07T10:14:15.363Z SendDataConnector.js: got all data for this round
,2015-12-07T10:14:15.364Z SendDataConnector.js: CLIENT Stop now
,2015-12-07T10:14:15.364Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 11:14:15.365 ThaliTest[369:122139] jxcore: disconnect
,2015-12-07 11:14:15.367 ThaliTest[369:122139] client session: disconnectFromPeer: Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:14:15.368 ThaliTest[369:122139] client session: disconnect
,2015-12-07 11:14:15.369 ThaliTest[369:122139] client session: stateChange:2->0 Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:14:15.436 ThaliTest[369:122139] jxcore: disconnect: success
2015-12-07T10:14:15.436Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5016.vGdGUg==
---- round done--------
,device[2]: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07T10:14:15.438Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07T10:14:15.438Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6457.6Oi+cQ==,
2015-12-07T10:14:15.438Z SendDataConnector.js: do connect now
2015-12-07 11:14:15.438 ThaliTest[369:122139] jxcore: connect Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:14:15.438 ThaliTest[369:122139] client session: connect
2015-12-07 11:14:15.438 ThaliTest[369:122139] client session: stateChange:0->1 Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:14:15.906 ThaliTest[369:122863] server session: not connected Apple-IpadAir2-1_PT5016
,2015-12-07 11:14:16.204 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT12.Gapeow==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-07 11:14:16.402 ThaliTest[369:121823] multipeer session: reset timer
2015-12-07 11:14:16.403 ThaliTest[369:121823] multipeer session: stop timer
2015-12-07 11:14:16.403 ThaliTest[369:121823] multipeer session: start timer: 0x184e0600
,2015-12-07 11:14:16.403 ThaliTest[369:121823] server session: connect
2015-12-07 11:14:16.405 ThaliTest[369:121823] server session: stateChange:0->1 Apple-Iphone5s-1_PT6457
,2015-12-07 11:14:16.415 ThaliTest[369:121823] server: accepting invitation Apple-Iphone5s-1_PT6457
,2015-12-07 11:14:18.437 ThaliTest[369:121823] multipeer session: reset timer
2015-12-07 11:14:18.438 ThaliTest[369:121823] multipeer session: stop timer
2015-12-07 11:14:18.438 ThaliTest[369:121823] multipeer session: start timer: 0x184e0600
2015-12-07 ,11:14:18.438 ThaliTest[369:121823] server session: connect
2015-12-07 11:14:18.439 ThaliTest[369:121823] server session: stateChange:0->1 Apple-Iphone5-1_PT94
,2015-12-07 11:14:18.452 ThaliTest[369:121823] server: accepting invitation Apple-Iphone5-1_PT94
,2015-12-07 11:14:18.463 ThaliTest[369:122864] client session: connected
,2015-12-07 11:14:18.473 ThaliTest[369:122864] client session: stateChange:1->2 Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:14:18.488 ThaliTest[369:122864] client session: fireConnectCallback: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:14:18.491 ThaliTest[369:122864] jxcore: connect: success
,2015-12-07T10:14:18.494Z SendDataConnector.js: CLIENT connected to 50392, error: null
2015-12-07T10:14:18.494Z SendDataConnector.js: CLIENT starting client 
,2015-12-07 11:14:18.498 ThaliTest[369:121823] client: relay established
,2015-12-07 11:14:18.499 ThaliTest[369:121823] client: new accepted socket: 0x186e9fb0
,2015-12-07T10:14:18.510Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07T10:14:19.083Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-07T10:14:19.096Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-07T10:14:19.096Z SendDataConnector.js: got all data for this round
,2015-12-07T10:14:19.097Z SendDataConnector.js: CLIENT Stop now
,2015-12-07T10:14:19.098Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 11:14:19.099 ThaliTest[369:122139] jxcore: disconnect
,2015-12-07 11:14:19.100 ThaliTest[369:122139] client session: disconnectFromPeer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:14:19.101 ThaliTest[369:122139] client session: disconnect
,2015-12-07 11:14:19.102 ThaliTest[369:122139] client session: stateChange:2->0 Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:14:19.173 ThaliTest[369:122139] jxcore: disconnect: success
,2015-12-07T10:14:19.175Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6457.6Oi+cQ==
,---- round done--------
,device[3]: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07T10:14:19.177Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07T10:14:19.178Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07T10:14:19.179Z SendDataConnector.js: do connect now
,2015-12-07 11:14:19.180 ThaliTest[369:122139] jxcore: connect Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:14:19.181 ThaliTest[369:122139] client session: connect
,2015-12-07 11:14:19.182 ThaliTest[369:122139] client session: stateChange:0->1 Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:14:19.535 ThaliTest[369:122864] server session: connected
2015-12-07 11:14:19.535 ThaliTest[369:122864] server session: stateChange:1->2 Apple-Iphone5s-1_PT6457
,2015-12-07 11:14:19.542 ThaliTest[369:121823] server relay: connected (to port: 50385)
,2015-12-07T10:14:19.554Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-07T10:14:20.012Z SendDataTCPServer.js: TCP/IP server has received 49234 bytes of data
,2015-12-07T10:14:20.026Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-07T10:14:20.065Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-07T10:14:20.078Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-07T10:14:20.093Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07 11:14:20.151 ThaliTest[369:122855] server session: not connected Apple-Iphone5s-1_PT6457
,2015-12-07 11:14:21.196 ThaliTest[369:122855] server session: connected
2015-12-07 11:14:21.196 ThaliTest[369:122855] server session: stateChange:1->2 Apple-Iphone5-1_PT94
,2015-12-07 11:14:21.255 ThaliTest[369:121823] server relay: connected (to port: 50385)
,2015-12-07T10:14:21.266Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-07T10:14:21.799Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-07T10:14:22.179Z SendDataTCPServer.js: TCP/IP server has received 53390 bytes of data
,2015-12-07T10:14:22.198Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07 11:14:22.722 ThaliTest[369:122864] server session: not connected Apple-Iphone5-1_PT94
,2015-12-07 11:14:22.803 ThaliTest[369:122864] client session: connected
2015-12-07 11:14:22.803 ThaliTest[369:122864] client session: stateChange:1->2 Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:14:22.821 ThaliTest[369:122855] client session: fireConnectCallback: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:14:22.822 ThaliTest[369:122855] jxcore: connect: success
,2015-12-07T10:14:22.823Z SendDataConnector.js: CLIENT connected to 50397, error: null
,2015-12-07T10:14:22.824Z SendDataConnector.js: CLIENT starting client 
,2015-12-07 11:14:22.827 ThaliTest[369:121823] client: relay established
,2015-12-07 11:14:22.828 ThaliTest[369:121823] client: new accepted socket: 0x1832df80
,2015-12-07T10:14:22.840Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07T10:14:23.686Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-07T10:14:23.749Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-07T10:14:24.318Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-07T10:14:25.317Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-07T10:14:25.318Z SendDataConnector.js: got all data for this round
,2015-12-07T10:14:25.320Z SendDataConnector.js: CLIENT Stop now
2015-12-07T10:14:25.320Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 11:14:25.321 ThaliTest[369:122139] jxcore: disconnect
2015-12-07 11:14:25.322 ThaliTest[369:122139] client session: disconnectFromPeer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:14:25.322 ThaliTest[369:122139] client session: disconnect
201,5-12-07 11:14:25.322 ThaliTest[369:122139] client session: stateChange:2->0 Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:14:25.334 ThaliTest[369:122139] jxcore: disconnect: success
2015-12-07T10:14:25.334Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT94.0IbCHA==
---- round done--------
weAreDoneNow , resultArray.length: 3
done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT6748","time":14852,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT5016.vGdGUg==","time":4121,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1,_PT6457.6Oi+cQ==","time":3659,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT94.0IbCHA==","time":6140,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 6140 ms, 99% : 6140 ms, 95 : 6140 ms, 90% : 6140 ms.
Result count 3, range 3659 ms to  6140 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-12-07T10:14:25.347Z SendDataConnector.js: CLIENT Stop now
2015-12-07T10:14:25.347Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 11:14:27.312 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1974.yVUIQA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-07 11:14:30.247 ThaliTest[369:121823] client: lost peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 11:14:30.247 ThaliTest[369:121823] client session: onPeerLost: Apple-IpadAir2-1_PT12.Gapeow==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ipa,dAir2-1_PT12.Gapeow==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-07 11:14:33.344 ThaliTest[369:121823] client: lost peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 11:14:33.344 ThaliTest[369:121823] client session: onPeerLost: Apple-Iphone5-1_PT1974.yVUIQA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1974.yVUIQA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-07 11:14:35.920 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7843.gS16eg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-12-07 11:14:44.144 ThaliTest[369:121823] client: lost peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 11:14:44.145 ThaliTest[369:121823] client session: onPeerLost: Apple-Iphone5s-1_PT7843.gS16eg==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5s-1_PT7843.gS16eg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-07 11:14:48.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:14:48.486 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:14:48.488 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:15:18.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:15:18.491 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:15:18.492 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:15:18.493 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:15:41.935 ThaliTest[369:121823] client: lost peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:15:41.936 ThaliTest[369:121823] client session: onPeerLost: Apple-Iphone5-1_PT94.0IbCHA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT94.0IbCHA==","peerName":"(null)","peerAvailable":false}]
,2015-12-07 11:15:45.630 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT94.0IbCHA==","peerName":"(null)","peerAvailable":true}]
,2015-12-07 11:15:48.439 ThaliTest[369:121823] multipeer session: restart
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:16:18.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:16:18.477 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:16:18.478 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:16:18.483 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:16:48.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:16:48.484 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:16:48.484 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:16:48.484 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:17:18.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:17:19.256 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:17:19.256 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:17:19.256 ThaliTest[369:121823] client: found, peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:17:48.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:17:48.481 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:17:48.482 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:17:48.487 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:18:18.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:18:18.485 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:18:18.486 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:18:18.486 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
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
,2015-12-07 11:18:48.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:18:48.483 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:18:48.484 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:18:48.484 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:19:18.438 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:19:18.478 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:19:18.480 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:19:18.687 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:19:48.439 ThaliTest[369:121823] multipeer session: restart
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
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleW,iFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:20:18.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:20:18.477 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:20:18.478 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:20:18.776 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,2015-12-07 11:20:48.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:20:48.481 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:20:48.484 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:20:48.484 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:21:18.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:21:18.482 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:21:18.483 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:21:18.483 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:21:48.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:21:48.841 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:21:48.841 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:21:48.842 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:22:18.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:22:18.483 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:22:18.484 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:22:18.484 ThaliTest[369:121823] client: found, peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:22:48.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:22:48.481 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:22:48.481 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:22:48.483 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:23:18.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:23:18.482 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:23:18.482 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:23:18.485 ThaliTest[369:121823] client: fo,und peer: Apple-Iphone5-1_PT94.0IbCHA==
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
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:23:48.438 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:23:48.476 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:23:48.478 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:23:48.478 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:24:18.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:24:18.478 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:24:18.478 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:24:18.479 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
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
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:24:48.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:24:48.472 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:24:48.473 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:24:48.477 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:25:18.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:25:18.484 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:25:18.485 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:25:18.496 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,2015-12-07 11:25:48.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:25:48.480 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:25:48.481 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:25:48.945 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 11:26:18.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:26:18.482 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:26:18.483 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:26:18.487 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
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
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:26:48.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:26:48.481 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:26:48.481 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:26:48.487 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 11:27:18.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:27:18.483 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:27:18.483 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:27:18.484 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:27:48.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:27:48.482 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:27:48.482 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:27:48.483 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
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
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-07 11:28:18.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:28:18.490 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:28:18.490 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:28:18.491 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,2015-12-07 11:28:48.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:28:48.481 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:28:48.481 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:28:48.482 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
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
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 11:29:18.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:29:18.477 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:29:18.477 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:29:18.478 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:29:48.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:29:48.482 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:29:48.483 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:29:48.483 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-07 11:30:18.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:30:18.481 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:30:18.481 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:30:18.486 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:30:48.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:30:48.479 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:30:48.479 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:30:48.487 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 11:31:18.439 ThaliTest[369:121823] multipeer session: restart
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
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:31:48.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:31:48.475 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:31:48.475 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:31:48.478 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 11:32:18.439 ThaliTest[369:121823] multipeer session: restart
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
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:32:48.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:32:48.477 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:32:48.478 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:32:48.478 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 11:33:18.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:33:18.479 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:33:18.481 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:33:18.481 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:33:48.439 ThaliTest[369:121823] multipeer session: restart
,2015-12-07 11:33:48.478 ThaliTest[369:121823] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:33:48.478 ThaliTest[369:121823] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:33:48.479 ThaliTest[369:121823] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 11:34:18.439 ThaliTest[369:121823] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server

```
