#### Test 51986340afa1391_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51986340afa1391/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/35853715-4768-4488-8D41-DD6B1AB315E1/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/35853715-4768-4488-8D41-DD6B1AB315E1/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51986340afa1391/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51986340afa1391/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2806F4DC-64AB-433E-A741-FAC3C2456D54/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49778"
,(lldb)     command script import "/tmp/35853715-4768-4488-8D41-DD6B1AB315E1/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-07 11:05:34.384 ThaliTest[340:147318] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D91D1039-AB3D-4F21-8E54-C30E49DF07B9/Library/Cookies/Cookies.binarycookies
,2015-12-07 11:05:34.889 ThaliTest[340:147318] Apache Cordova native platform version 3.9.2 is starting.
2015-12-07 11:05:34.890 ThaliTest[340:147318] Multi-tasking -> Device: YES, App: YES
,2015-12-07 11:05:34.896 ThaliTest[340:147318] Unlimited access to network resources
,2015-12-07 11:05:34.911 ThaliTest[340:147318] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 11:05:45.466 ThaliTest[340:147318] Resetting plugins due to page load.
,2015-12-07 11:05:49.057 ThaliTest[340:147318] Finished load of: file:///var/mobile/Containers/Bundle/Application/2806F4DC-64AB-433E-A741-FAC3C2456D54/ThaliTest.app/www/index.html
,2015-12-07 11:05:49.273 ThaliTest[340:147318] JXcore Cordova plugin initializing
,2015-12-07 11:05:49.275 ThaliTest[340:147609] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
,my name is : Apple-Iphone5-1_PT94
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
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 51013
,2015-12-07 11:14:10.317 ThaliTest[340:147609] jxcore: startBroadcasting
,2015-12-07 11:14:10.330 ThaliTest[340:147609] server: starting Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:14:10.331 ThaliTest[340:147609] multipeer session: start timer: 0x1cf84a10
2015-12-07 11:14:10.332 ThaliTest[340:147609] THEMultipeerSession initia,lized peer Apple-Iphone5-1_PT94
2015-12-07 11:14:10.332 ThaliTest[340:147609] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-07T10:14:10.337Z SendDataTCPServer.js: TCP/IP server is bound to port: 51013
,2015-12-07 11:14:11.045 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5016.vGdGUg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07T10:14:11.049Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07T10:14:11.049Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5016.vGdGUg==,
2015-12-07T10:14:11.050Z SendDataConnector.js: do connect now
2015-12-07 11:14:11.050 ThaliTest[340:147609] jxcore: connect Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:14:11.051 ThaliTest[340:147609] client session: connect
,2015-12-07 11:14:11.051 ThaliTest[340:147609] client session: stateChange:0->1 Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:14:11.514 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6748.+3JG2Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
2015-12-07 11:14:11.516 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6457.6Oi+cQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,2015-12-07 11:14:13.345 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT7482.CDxPNA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7482.CDxPNA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-07 11:14:14.826 ThaliTest[340:148607] client session: connected
2015-12-07 11:14:14.827 ThaliTest[340:148607] client session: stateChange:1->2 Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:14:14.831 ThaliTest[340:148607] client session: fireConnectCallback: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:14:14.831 ThaliTest[340:148607] jxcore: connect: success
2015-12-07T10:14:14.832Z SendDataConnector.js: CLIENT connected to 51016, error: null
2015-12-07T10:14:14.832Z SendDataConnector.js: CLIENT starting client 
,2015-12-07 11:14:14.835 ThaliTest[340:147318] client: relay established
2015-12-07 11:14:14.836 ThaliTest[340:147318] client: new accepted socket: 0x1ce7c750
,2015-12-07T10:14:14.852Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07T10:14:15.667Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-07T10:14:15.681Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-07T10:14:15.720Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-07T10:14:15.736Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-07T10:14:17.314Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-07T10:14:17.314Z SendDataConnector.js: got all data for this round
,2015-12-07T10:14:17.317Z SendDataConnector.js: CLIENT Stop now
2015-12-07T10:14:17.317Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 11:14:17.319 ThaliTest[340:147609] jxcore: disconnect
2015-12-07 11:14:17.319 ThaliTest[340:147609] client session: disconnectFromPeer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:14:17.320 ThaliTest[340:147609] client session: disconnect
,2015-12-07 11:14:17.320 ThaliTest[340:147609] client session: stateChange:2->0 Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:14:17.327 ThaliTest[340:147609] jxcore: disconnect: success
2015-12-07T10:14:17.330Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5016.vGdGUg==
---- round done--------
device[2]: Apple-Iphone6-1_PT6748.+3,JG2Q==
2015-12-07T10:14:17.332Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07T10:14:17.332Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07T10:14:17.333Z SendDataConnector.js: do connect now
,2015-12-07 11:14:17.333 ThaliTest[340:147609] jxcore: connect Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:14:17.334 ThaliTest[340:147609] client session: connect
2015-12-07 11:14:17.335 ThaliTest[340:147609] client session: stateChange:0->1 Apple-Iphon,e6-1_PT6748.+3JG2Q==
,2015-12-07 11:14:19.030 ThaliTest[340:147318] multipeer session: reset timer
2015-12-07 11:14:19.031 ThaliTest[340:147318] multipeer session: stop timer
2015-12-07 11:14:19.031 ThaliTest[340:147318] multipeer session: start timer: 0x1cf84a10
2015-12-07 ,11:14:19.031 ThaliTest[340:147318] server session: connect
2015-12-07 11:14:19.032 ThaliTest[340:147318] server session: stateChange:0->1 Apple-IpadAir2-1_PT5016
2015-12-07 11:14:19.038 ThaliTest[340:147318] server: accepting invitation Apple-IpadAir2-1_PT5016
,2015-12-07 11:14:19.058 ThaliTest[340:147318] multipeer session: reset timer
2015-12-07 11:14:19.058 ThaliTest[340:147318] multipeer session: stop timer
2015-12-07 11:14:19.058 ThaliTest[340:147318] multipeer session: start timer: 0x1cf84a10
2015-12-07 ,11:14:19.059 ThaliTest[340:147318] server session: connect
2015-12-07 11:14:19.059 ThaliTest[340:147318] server session: stateChange:0->1 Apple-Iphone6-1_PT6748
2015-12-07 11:14:19.075 ThaliTest[340:147318] server: accepting invitation Apple-Iphone6-1_PT6748
,2015-12-07 11:14:20.062 ThaliTest[340:147318] multipeer session: reset timer
2015-12-07 11:14:20.062 ThaliTest[340:147318] multipeer session: stop timer
2015-12-07 11:14:20.062 ThaliTest[340:147318] multipeer session: start timer: 0x1cf84a10
2015-12-07 11:14:20.062 ThaliTest[340:147318] server session: connect
2015-12-07 11:14:20.062 ThaliTest[340:147318] server session: stateChange:0->1 Apple-Iphone5s-1_PT6457
,2015-12-07 11:14:20.069 ThaliTest[340:147318] server: accepting invitation Apple-Iphone5s-1_PT6457
,2015-12-07 11:14:21.004 ThaliTest[340:148606] client session: connected
,2015-12-07 11:14:21.007 ThaliTest[340:148606] client session: stateChange:1->2 Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:14:21.010 ThaliTest[340:148606] client session: fireConnectCallback: Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:14:21.011 ThaliTest[340:148606] jxcore: connect: success
,2015-12-07T10:14:21.013Z SendDataConnector.js: CLIENT connected to 51019, error: null
,2015-12-07T10:14:21.014Z SendDataConnector.js: CLIENT starting client 
,2015-12-07 11:14:21.016 ThaliTest[340:147318] client: relay established
,2015-12-07 11:14:21.017 ThaliTest[340:147318] client: new accepted socket: 0x1cea10e0
,2015-12-07T10:14:21.029Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07T10:14:21.982Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-07T10:14:22.009Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-07T10:14:22.009Z SendDataConnector.js: got all data for this round
,2015-12-07T10:14:22.012Z SendDataConnector.js: CLIENT Stop now
2015-12-07T10:14:22.012Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 11:14:22.013 ThaliTest[340:147609] jxcore: disconnect
2015-12-07 11:14:22.014 ThaliTest[340:147609] client session: disconnectFromPeer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:14:22.015 ThaliTest[340:147609] client session: disconnect
,2015-12-07 11:14:22.015 ThaliTest[340:147609] client session: stateChange:2->0 Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:14:22.024 ThaliTest[340:147609] jxcore: disconnect: success
2015-12-07T10:14:22.024Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6748.+3JG2Q==
---- round done--------
device[3]: Apple-Iphone5s-1_PT6457.6O,i+cQ==
2015-12-07T10:14:22.027Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07T10:14:22.027Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07T10:14:22.027Z SendDataConnector.js: do connect now
,2015-12-07 11:14:22.027 ThaliTest[340:147609] jxcore: connect Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:14:22.032 ThaliTest[340:147609] client session: connect
,2015-12-07 11:14:22.033 ThaliTest[340:147609] client session: stateChange:0->1 Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:14:22.524 ThaliTest[340:148605] server session: connected
,2015-12-07 11:14:22.525 ThaliTest[340:148605] server session: stateChange:1->2 Apple-IpadAir2-1_PT5016
,2015-12-07 11:14:22.536 ThaliTest[340:147318] server relay: connected (to port: 51013)
,2015-12-07T10:14:22.539Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-07 11:14:22.601 ThaliTest[340:148605] server session: connected
2015-12-07 11:14:22.601 ThaliTest[340:148605] server session: stateChange:1->2 Apple-Iphone6-1_PT6748
,2015-12-07 11:14:22.605 ThaliTest[340:147318] server relay: connected (to port: 51013)
,2015-12-07T10:14:22.616Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-07T10:14:22.940Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-07T10:14:22.953Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-07T10:14:23.016Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-07T10:14:23.028Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-07T10:14:23.074Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-07T10:14:23.091Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-07T10:14:23.142Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-07T10:14:23.155Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
2015-12-07T10:14:23.157Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-07T10:14:23.171Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-07T10:14:23.184Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-07T10:14:23.213Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-07T10:14:23.226Z SendDataTCPServer.js: TCP/IP server has received 69796 bytes of data
2015-12-07T10:14:23.227Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-07T10:14:23.242Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-07T10:14:23.528Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-07T10:14:23.543Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-07T10:14:23.557Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07T10:14:24.078Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-07 11:14:24.199 ThaliTest[340:148605] server session: connected
2015-12-07 11:14:24.199 ThaliTest[340:148605] server session: stateChange:1->2 Apple-Iphone5s-1_PT6457
,2015-12-07 11:14:24.252 ThaliTest[340:147318] server relay: connected (to port: 51013)
,2015-12-07T10:14:24.254Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-07 11:14:24.523 ThaliTest[340:148607] server session: not connected Apple-IpadAir2-1_PT5016
,2015-12-07T10:14:24.566Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-07T10:14:24.579Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-07T10:14:24.594Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-07T10:14:24.609Z SendDataTCPServer.js: TCP/IP server has received 39136 bytes of data
,2015-12-07T10:14:24.625Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-07T10:14:24.642Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-07T10:14:24.656Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07T10:14:25.032Z SendDataTCPServer.js: TCP/IP server has received 74318 bytes of data
,2015-12-07T10:14:25.046Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07 11:14:25.167 ThaliTest[340:148605] server session: not connected Apple-Iphone6-1_PT6748
,2015-12-07 11:14:25.426 ThaliTest[340:148607] server session: not connected Apple-Iphone5s-1_PT6457
,2015-12-07 11:14:26.701 ThaliTest[340:148607] client session: connected
2015-12-07 11:14:26.702 ThaliTest[340:148607] client session: stateChange:1->2 Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:14:26.731 ThaliTest[340:148603] client session: fireConnectCallback: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:14:26.731 ThaliTest[340:148603] jxcore: connect: success
2015-12-07T10:14:26.732Z SendDataConnector.js: CLIENT connected to ,51025, error: null
2015-12-07T10:14:26.732Z SendDataConnector.js: CLIENT starting client 
2015-12-07 11:14:26.734 ThaliTest[340:147318] client: relay established
2015-12-07 11:14:26.734 ThaliTest[340:147318] client: new accepted socket: 0x1ce80a30
,2015-12-07T10:14:26.747Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07T10:14:27.307Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-07T10:14:27.770Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-07T10:14:27.858Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-07T10:14:31.919Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-07T10:14:31.920Z SendDataConnector.js: got all data for this round
,2015-12-07T10:14:31.921Z SendDataConnector.js: CLIENT Stop now
2015-12-07T10:14:31.921Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-07 11:14:31.922 ThaliTest[340:147609] jxcore: disconnect
,2015-12-07 11:14:31.922 ThaliTest[340:147609] client session: disconnectFromPeer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:14:31.922 ThaliTest[340:147609] client session: disconnect
,2015-12-07 11:14:31.923 ThaliTest[340:147609] client session: stateChange:2->0 Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:14:31.934 ThaliTest[340:147609] jxcore: disconnect: success
2015-12-07T10:14:31.934Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6457.6Oi+cQ==
---- round done--------
weAreDoneNow , resultArray.length: 3,
done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-Iphone5-1_PT94","time":21629,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT5016.vGdGUg==","time":6267,"result":"OK","connections":1,"doneR,ounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT6748.+3JG2Q==","time":4678,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT6457.6Oi+cQ==","time":9893,"result,":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
sendList : 100% : 9893 ms, 99% : 9893 ms, 95 : 9893 ms, 90% : 9893 ms.
Result count 3, range 4678 ms to  9893 ms.
sendList failed peers count : 0 [0 %]
sendList never tr,ied peers count : 0 [0 %]
2015-12-07T10:14:31.951Z SendDataConnector.js: CLIENT Stop now
2015-12-07T10:14:31.951Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 11:14:37.925 ThaliTest[340:147318] client: lost peer: Apple-Iphone6-1_PT7482.CDxPNA==
2015-12-07 11:14:37.925 ThaliTest[340:147318] client session: onPeerLost: Apple-Iphone6-1_PT7482.CDxPNA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT7482.CDxPNA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-07 11:14:50.063 ThaliTest[340:147318] multipeer session: restart
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-07 11:15:20.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:15:20.466 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:15:20.466 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:15:20.526 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:15:50.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:15:50.100 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:15:50.101 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:15:50.912 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-07 11:16:20.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:16:20.201 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:16:20.201 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:16:20.201 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
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
,2015-12-07 11:16:50.063 ThaliTest[340:147318] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-07 11:17:20.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:17:20.384 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:17:20.385 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:17:20.385 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,2015-12-07 11:17:50.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:17:50.338 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:17:50.342 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:17:50.342 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 11:18:20.063 ThaliTest[340:147318] multipeer session: restart
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
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-07 11:18:50.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:18:50.505 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:18:50.506 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:18:50.506 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 11:19:20.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:19:20.422 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:19:20.423 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:19:20.561 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
Error type "connect_error" when connecting to the test server
,2015-12-07 11:19:50.063 ThaliTest[340:147318] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
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
,2015-12-07 11:20:20.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:20:20.100 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:20:20.206 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:20:20.252 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
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
,2015-12-07 11:20:50.062 ThaliTest[340:147318] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-07 11:20:50.107 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:20:50.594 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:20:50.621 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
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
,2015-12-07 11:21:20.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:21:20.100 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:21:20.101 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 11:21:20.382 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
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
,2015-12-07 11:21:50.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:21:50.100 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:21:50.100 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:21:50.101 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,2015-12-07 11:22:20.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:22:20.101 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:22:20.101 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:22:20.102 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:22:50.063 ThaliTest[340:147318] multipeer session: restart
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
,2015-12-07 11:23:20.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:23:20.098 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:23:20.099 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 11:23:21.025 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:23:50.063 ThaliTest[340:147318] multipeer session: restart
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
Error type "connect_error" when connecting to the test server
,2015-12-07 11:24:20.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:24:20.095 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:24:20.095 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 11:24:21.243 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-07 11:24:50.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:24:50.098 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:24:50.677 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:24:50.678 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,2015-12-07 11:25:20.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:25:20.297 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:25:20.298 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:25:20.298 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleW,iFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
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
,2015-12-07 11:25:50.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:25:50.101 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:25:50.101 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:25:50.266 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:26:20.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:26:20.605 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 11:26:21.051 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:26:21.052 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,2015-12-07 11:26:50.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:26:50.099 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:26:50.515 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:26:50.516 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,2015-12-07 11:27:20.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:27:20.093 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:27:20.097 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:27:20.871 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:27:50.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:27:50.170 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:27:50.171 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:27:50.171 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
Error type "connect_error" when connecting to the test server
,2015-12-07 11:28:20.063 ThaliTest[340:147318] multipeer session: restart
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:28:50.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:28:50.458 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:28:50.458 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:28:50.458 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,2015-12-07 11:29:20.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:29:20.300 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:29:20.300 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:29:20.301 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:29:50.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:29:50.276 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:29:50.279 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:29:50.279 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-07 11:30:20.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:30:20.098 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:30:20.099 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:30:20.563 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
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
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:30:50.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:30:50.098 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:30:50.098 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:30:50.099 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:31:20.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:31:20.098 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:31:20.099 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:31:20.104 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:31:50.063 ThaliTest[340:147318] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:32:20.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:32:20.095 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:32:20.096 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:32:20.097 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:32:50.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:32:50.410 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:32:50.411 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:32:50.412 ThaliTest[340:147318] client: fou,nd peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:33:20.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:33:20.095 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:33:20.098 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:33:20.101 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
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
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-07 11:33:50.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:33:50.175 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:33:50.177 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:33:50.178 ThaliTest[340:147318] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,2015-12-07 11:34:20.063 ThaliTest[340:147318] multipeer session: restart
,2015-12-07 11:34:20.506 ThaliTest[340:147318] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:34:20.507 ThaliTest[340:147318] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:34:20.507 ThaliTest[340:147318] client: fou,nd peer: Apple-IpadAir2-1_PT5016.vGdGUg==

```
