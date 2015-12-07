#### Test 51986340afa1391_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51986340afa1391/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/56B47036-BF34-4573-BC0D-A8A13E5FBC97/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/56B47036-BF34-4573-BC0D-A8A13E5FBC97/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51986340afa1391/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51986340afa1391/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7ECA8748-311A-4CEB-AAB9-394D8A5367FB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49793"
,(lldb)     command script import "/tmp/56B47036-BF34-4573-BC0D-A8A13E5FBC97/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-07 11:06:56.303 ThaliTest[321:112528] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3C35188A-3458-43FF-9FFD-A66B543B5ED6/Library/Cookies/Cookies.binarycookies
,2015-12-07 11:06:56.316 ThaliTest[321:112528] <CATransformLayer: 0x17e71110> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-07 11:06:56.317 ThaliTest[321:112528] <CATransformLayer: 0x17e76170> - changing property ma,sksToBounds in transform-only layer, will have no effect
2015-12-07 11:06:56.317 ThaliTest[321:112528] <CATransformLayer: 0x17e772c0> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-07 11:06:56.606 ThaliTest[321:112528] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-07 11:06:56.606 ThaliTest[321:112528] Multi-tasking -> Device: YES, App: YES
,2015-12-07 11:06:56.614 ThaliTest[321:112528] Unlimited access to network resources
,2015-12-07 11:06:56.620 ThaliTest[321:112528] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 11:07:05.444 ThaliTest[321:112528] Resetting plugins due to page load.
,2015-12-07 11:07:08.732 ThaliTest[321:112528] Finished load of: file:///var/mobile/Containers/Bundle/Application/7ECA8748-311A-4CEB-AAB9-394D8A5367FB/ThaliTest.app/www/index.html
,2015-12-07 11:07:08.874 ThaliTest[321:112528] JXcore Cordova plugin initializing
,2015-12-07 11:07:08.875 ThaliTest[321:112800] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-IpadAir2-1_PT5016
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 50078
,2015-12-07 11:14:11.039 ThaliTest[321:112800] jxcore: startBroadcasting
,2015-12-07 11:14:11.051 ThaliTest[321:112800] server: starting Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:14:11.052 ThaliTest[321:112800] multipeer session: start timer: 0x1b8aa5c0
,2015-12-07 11:14:11.053 ThaliTest[321:112800] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT5016
,2015-12-07 11:14:11.054 ThaliTest[321:112800] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-07T10:14:11.059Z SendDataTCPServer.js: TCP/IP server is bound to port: 50078
,2015-12-07 11:14:12.369 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:14:12.372 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6748.+3JG2Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07T10:14:12.377Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07T10:14:12.379Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07T10:14:12.379Z SendDataConnector.js: do connect now
,2015-12-07 11:14:12.380 ThaliTest[321:112800] jxcore: connect Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:14:12.381 ThaliTest[321:112800] client session: connect
,2015-12-07 11:14:12.381 ThaliTest[321:112800] client session: stateChange:0->1 Apple-Iphone6-1_PT6748.+3JG2Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6457.6Oi+cQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-07 11:14:12.535 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT94.0IbCHA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-07 11:14:12.955 ThaliTest[321:112528] multipeer session: reset timer
2015-12-07 11:14:12.955 ThaliTest[321:112528] multipeer session: stop timer
2015-12-07 11:14:12.955 ThaliTest[321:112528] multipeer session: start timer: 0x1b8aa5c0
,2015-12-07 11:14:12.956 ThaliTest[321:112528] server session: connect
2015-12-07 11:14:12.956 ThaliTest[321:112528] server session: stateChange:0->1 Apple-Iphone6-1_PT6748
,2015-12-07 11:14:12.962 ThaliTest[321:112528] server: accepting invitation Apple-Iphone6-1_PT6748
,2015-12-07 11:14:13.143 ThaliTest[321:112528] multipeer session: reset timer
2015-12-07 11:14:13.144 ThaliTest[321:112528] multipeer session: stop timer
2015-12-07 11:14:13.144 ThaliTest[321:112528] multipeer session: start timer: 0x1b8aa5c0
2015-12-07 11:14:13.144 ThaliTest[321:112528] server session: connect
,2015-12-07 11:14:13.144 ThaliTest[321:112528] server session: stateChange:0->1 Apple-Iphone5-1_PT94
,2015-12-07 11:14:13.146 ThaliTest[321:112528] server: accepting invitation Apple-Iphone5-1_PT94
,2015-12-07 11:14:13.207 ThaliTest[321:112528] multipeer session: reset timer
2015-12-07 11:14:13.207 ThaliTest[321:112528] multipeer session: stop timer
,2015-12-07 11:14:13.207 ThaliTest[321:112528] multipeer session: start timer: 0x1b8aa5c0
2015-12-07 11:14:13.207 ThaliTest[321:112528] server session: connect
,2015-12-07 11:14:13.207 ThaliTest[321:112528] server session: stateChange:0->1 Apple-Iphone5s-1_PT6457
,2015-12-07 11:14:13.209 ThaliTest[321:112528] server: accepting invitation Apple-Iphone5s-1_PT6457
,2015-12-07 11:14:14.019 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7843.gS16eg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-07 11:14:15.534 ThaliTest[321:113472] client session: connected
2015-12-07 11:14:15.535 ThaliTest[321:113472] client session: stateChange:1->2 Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:14:15.538 ThaliTest[321:113465] server session: connected
2015-12-07 11:14:15.538 ThaliTest[321:113465] server session: stateChange:1->2 Apple-Iphone6-1_PT6748
,2015-12-07 11:14:15.542 ThaliTest[321:113472] client session: fireConnectCallback: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:14:15.542 ThaliTest[321:113472] jxcore: connect: success
,2015-12-07T10:14:15.544Z SendDataConnector.js: CLIENT connected to 50081, error: null
,2015-12-07T10:14:15.544Z SendDataConnector.js: CLIENT starting client 
,2015-12-07 11:14:15.546 ThaliTest[321:112528] server relay: connected (to port: 50078)
2015-12-07 11:14:15.547 ThaliTest[321:112528] client: relay established
2015-12-07 11:14:15.548 ThaliTest[321:112528] client: new accepted socket: 0x1b8b6230
,2015-12-07T10:14:15.564Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-07T10:14:15.565Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07 11:14:15.691 ThaliTest[321:113465] server session: connected
2015-12-07 11:14:15.691 ThaliTest[321:113465] server session: stateChange:1->2 Apple-Iphone5-1_PT94
,2015-12-07 11:14:15.706 ThaliTest[321:112528] server relay: connected (to port: 50078)
,2015-12-07T10:14:15.786Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-07T10:14:15.956Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-07T10:14:15.971Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07T10:14:16.025Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-07T10:14:16.038Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-07 11:14:16.083 ThaliTest[321:113472] server session: not connected Apple-Iphone6-1_PT6748
,2015-12-07 11:14:16.153 ThaliTest[321:113473] server session: connected
2015-12-07 11:14:16.154 ThaliTest[321:113473] server session: stateChange:1->2 Apple-Iphone5s-1_PT6457
,2015-12-07 11:14:16.158 ThaliTest[321:112528] server relay: connected (to port: 50078)
,2015-12-07T10:14:16.161Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-07T10:14:16.224Z SendDataTCPServer.js: TCP/IP server has received 2048 bytes of data
,2015-12-07T10:14:16.240Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-07T10:14:16.479Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-07T10:14:16.479Z SendDataConnector.js: got all data for this round
,2015-12-07T10:14:16.483Z SendDataConnector.js: CLIENT Stop now
,2015-12-07T10:14:16.483Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 11:14:16.487 ThaliTest[321:112800] jxcore: disconnect
2015-12-07 11:14:16.487 ThaliTest[321:112800] client session: disconnectFromPeer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:14:16.488 ThaliTest[321:112800] client session: disconnect
,2015-12-07 11:14:16.489 ThaliTest[321:112800] client session: stateChange:2->0 Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:14:16.502 ThaliTest[321:112800] jxcore: disconnect: success
2015-12-07T10:14:16.502Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6748.+3JG2Q==
,---- round done--------
,device[2]: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07T10:14:16.506Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07T10:14:16.506Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07T10:14:16.506Z SendDataConnector.js: do connect now
2015-12-07 11:14:16.507 ThaliTest[321:112800] jxcore: connect Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:14:16.507 ThaliTest[321:112800] client session: connect
2015-12-07 11:14:16.508 ThaliTest[321:112800] client session: stateChange:0->1 Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07T10:14:16.534Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-07T10:14:16.563Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-07T10:14:16.587Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-07T10:14:16.601Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-07T10:14:16.613Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07T10:14:16.640Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-07T10:14:16.653Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-07T10:14:16.667Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-07T10:14:16.691Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-07T10:14:16.716Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-07T10:14:16.730Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07 11:14:17.066 ThaliTest[321:113464] server session: not connected Apple-Iphone5s-1_PT6457
,2015-12-07 11:14:18.322 ThaliTest[321:113464] server session: not connected Apple-Iphone5-1_PT94
,2015-12-07 11:14:19.184 ThaliTest[321:113517] client session: connected
2015-12-07 11:14:19.184 ThaliTest[321:113517] client session: stateChange:1->2 Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:14:19.193 ThaliTest[321:113464] client session: fireConnectCallback: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:14:19.193 ThaliTest[321:113464] jxcore: connect: success
,2015-12-07T10:14:19.194Z SendDataConnector.js: CLIENT connected to 50087, error: null
,2015-12-07T10:14:19.195Z SendDataConnector.js: CLIENT starting client 
,2015-12-07 11:14:19.198 ThaliTest[321:112528] client: relay established
2015-12-07 11:14:19.199 ThaliTest[321:112528] client: new accepted socket: 0x19f458c0
,2015-12-07T10:14:19.211Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07T10:14:19.681Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-07T10:14:19.707Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-07T10:14:19.746Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-07T10:14:19.758Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-07T10:14:19.783Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-07T10:14:19.809Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-07T10:14:19.810Z SendDataConnector.js: got all data for this round
,2015-12-07T10:14:19.813Z SendDataConnector.js: CLIENT Stop now
2015-12-07T10:14:19.813Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 11:14:19.814 ThaliTest[321:112800] jxcore: disconnect
,2015-12-07 11:14:19.815 ThaliTest[321:112800] client session: disconnectFromPeer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:14:19.815 ThaliTest[321:112800] client session: disconnect
,2015-12-07 11:14:19.816 ThaliTest[321:112800] client session: stateChange:2->0 Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:14:19.829 ThaliTest[321:112800] jxcore: disconnect: success
2015-12-07T10:14:19.829Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6457.6Oi+cQ==
---- round done--------
device[3]: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07T10:14:19.832Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07T10:14:19.832Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07T10:14:19.832Z SendDataConnector.js: do ,connect now
2015-12-07 11:14:19.833 ThaliTest[321:112800] jxcore: connect Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:14:19.833 ThaliTest[321:112800] client session: connect
2015-12-07 11:14:19.833 ThaliTest[321:112800] client session: stateChange:0->1 Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:14:23.389 ThaliTest[321:113465] client session: connected
2015-12-07 11:14:23.389 ThaliTest[321:113465] client session: stateChange:1->2 Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:14:23.478 ThaliTest[321:113465] client session: fireConnectCallback: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:14:23.478 ThaliTest[321:113465] jxcore: connect: success
,2015-12-07T10:14:23.480Z SendDataConnector.js: CLIENT connected to 50090, error: null
,2015-12-07T10:14:23.480Z SendDataConnector.js: CLIENT starting client 
,2015-12-07 11:14:23.483 ThaliTest[321:112528] client: relay established
2015-12-07 11:14:23.483 ThaliTest[321:112528] client: new accepted socket: 0x1b8af7a0
,2015-12-07T10:14:23.497Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07T10:14:24.349Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-07T10:14:24.363Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-07T10:14:25.258Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-07T10:14:25.259Z SendDataConnector.js: got all data for this round
,2015-12-07T10:14:25.261Z SendDataConnector.js: CLIENT Stop now
,2015-12-07T10:14:25.262Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 11:14:25.264 ThaliTest[321:112800] jxcore: disconnect
,2015-12-07 11:14:25.264 ThaliTest[321:112800] client session: disconnectFromPeer: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:14:25.265 ThaliTest[321:112800] client session: disconnect
,2015-12-07 11:14:25.265 ThaliTest[321:112800] client session: stateChange:2->0 Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:14:25.337 ThaliTest[321:112800] jxcore: disconnect: success
2015-12-07T10:14:25.338Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT94.0IbCHA==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT5016","time":14316,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT6748.+3JG2Q==","time":4103,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1,_PT6457.6Oi+cQ==","time":3304,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT94.0IbCHA==","time":5428,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 5428 ms, 99% : 5428 ms, 95 : 5428 ms, 90% : 5428 ms.
,Result count 3, range 3304 ms to  5428 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-07T10:14:25.348Z SendDataConnector.js: CLIENT Stop now
,2015-12-07T10:14:25.348Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 11:14:43.209 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:14:43.239 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:14:43.248 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:14:43.248 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:15:13.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:15:13.246 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:15:13.246 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:15:13.247 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,2015-12-07 11:15:36.934 ThaliTest[321:112528] client: lost peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:15:36.934 ThaliTest[321:112528] client session: onPeerLost: Apple-Iphone5s-1_PT6457.6Oi+cQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6457.6Oi+cQ==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:15:43.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:15:43.243 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:15:43.243 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6457.6Oi+cQ==","peerName":"(null)","peerAvailable":true}]
2015-12-07 11:15:43.246 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,2015-12-07 11:16:07.406 ThaliTest[321:112528] client: lost peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:16:07.407 ThaliTest[321:112528] client session: onPeerLost: Apple-Iphone5-1_PT94.0IbCHA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT94.0IbCHA==","peerName":"(null)","peerAvailable":false}]
,2015-12-07 11:16:09.088 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT94.0IbCHA==","peerName":"(null)","peerAvailable":true}]
,2015-12-07 11:16:13.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:16:13.246 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:16:13.246 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:16:13.247 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:16:13.485 ThaliTest[321:112528] client: lost peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:16:13.485 ThaliTest[321:112528] client session: onPeerLost: Apple-Iphone6-1_PT6748.+3JG2Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6748.+3JG2Q==","peerName":"(null)","peerAvailable":false}]
,2015-12-07 11:16:15.091 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6748.+3JG2Q==","peerName":"(null)","peerAvailable":true}]
,2015-12-07 11:16:43.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:16:43.245 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:16:43.246 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:16:43.246 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:17:13.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:17:13.247 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:17:13.247 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:17:13.248 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:17:43.209 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:17:43.248 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:17:43.249 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:17:43.249 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-07 11:18:13.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:18:13.245 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:18:13.245 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:18:13.246 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:18:43.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:18:43.248 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:18:43.248 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:18:43.249 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-07 11:19:13.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:19:13.247 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:19:13.247 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:19:13.248 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:19:28.171 ThaliTest[321:112528] client: lost peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:19:28.171 ThaliTest[321:112528] client session: onPeerLost: Apple-Iphone5-1_PT94.0IbCHA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT94.0IbCHA==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:19:41.678 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT94.0IbCHA==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:19:43.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:19:43.245 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:19:43.245 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:19:43.246 ThaliTest[321:112528] client: found ,peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:20:06.452 ThaliTest[321:112528] client: lost peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:20:06.453 ThaliTest[321:112528] client session: onPeerLost: Apple-Iphone5-1_PT94.0IbCHA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT94.0IbCHA==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:20:07.913 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT94.0IbCHA==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-07 11:20:13.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:20:13.245 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:20:13.248 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:20:13.249 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
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
,2015-12-07 11:20:43.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:20:43.238 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:20:43.239 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:20:48.578 ThaliTest[321:112528] client: lost peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:20:48.578 ThaliTest[321:112528] client session: onPeerLost: Apple-Iphone6-1_PT6748.+3JG2Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6748.+3JG2Q==","peerName":"(null)","peerAvailable":false}]
,2015-12-07 11:20:48.980 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6748.+3JG2Q==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-07 11:21:13.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:21:13.245 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:21:13.246 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:21:13.247 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:21:43.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:21:43.245 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:21:43.246 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:21:43.246 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:22:13.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:22:13.245 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:22:13.245 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:22:13.246 ThaliTest[321:112528] client: found ,peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
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
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:22:43.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:22:43.245 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:22:43.247 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:22:43.248 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,2015-12-07 11:23:13.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:23:13.246 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:23:13.247 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:23:13.248 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:23:43.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:23:43.247 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:23:43.248 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:23:45.637 ThaliTest[321:112528] client: lost peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:23:45.638 ThaliTest[321:112528] client session: onPeerLost: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6457.6Oi+cQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-07 11:23:45.640 ThaliTest[321:112528] client: lost peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:23:45.641 ThaliTest[321:112528] client session: onPeerLost: Apple-Iphone5-1_PT94.0IbCHA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT94.0IbCHA==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:23:50.320 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT94.0IbCHA==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:23:55.746 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:23:58.573 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6457.6Oi+cQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:24:13.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:24:13.248 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:24:13.248 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:24:13.250 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:24:43.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:24:43.242 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:24:43.243 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:24:43.244 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:25:05.367 ThaliTest[321:112528] client: lost peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:25:05.367 ThaliTest[321:112528] client session: onPeerLost: Apple-Iphone5-1_PT94.0IbCHA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT94.0IbCHA==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:25:11.410 ThaliTest[321:112528] client: lost peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:25:11.410 ThaliTest[321:112528] client session: onPeerLost: Apple-Iphone5s-1_PT6457.6Oi+cQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6457.6Oi+cQ==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:25:13.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:25:13.238 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:25:13.238 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:25:13.240 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT94.0IbCHA==","peerName":"(null)","peerAvailable":true}]
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6457.6Oi+cQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:25:43.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:25:43.240 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:25:43.240 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:25:43.242 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,2015-12-07 11:26:13.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:26:13.246 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:26:13.246 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:26:13.247 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:26:34.754 ThaliTest[321:112528] client: lost peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:26:34.755 ThaliTest[321:112528] client session: onPeerLost: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6457.6Oi+cQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-07 11:26:34.997 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6457.6Oi+cQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:26:43.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:26:43.245 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:26:43.246 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:26:43.246 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,2015-12-07 11:27:13.209 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:27:13.240 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:27:21.109 ThaliTest[321:112528] client: lost peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:27:21.110 ThaliTest[321:112528] client session: onPeerLost: Apple-Iphone6-1_PT6748.+3JG2Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6748.+3JG2Q==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-07 11:27:22.734 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6748.+3JG2Q==","peerName":"(null)","peerAvailable":true}]
,2015-12-07 11:27:24.301 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:27:27.522 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:27:43.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:27:43.246 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:27:43.247 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:27:43.247 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,2015-12-07 11:28:13.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:28:13.244 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:28:13.244 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:28:13.245 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:28:43.208 ThaliTest[321:112528] multipeer session: restart
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
,2015-12-07 11:29:13.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:29:13.239 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:29:13.239 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:29:13.239 ThaliTest[321:112528] client: found ,peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:29:43.208 ThaliTest[321:112528] multipeer session: restart
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
,2015-12-07 11:30:13.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:30:13.236 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:30:13.236 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:30:13.237 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:30:43.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:30:43.235 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:30:43.236 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:30:43.236 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,2015-12-07 11:31:13.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:31:13.237 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:31:13.238 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:31:13.238 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:31:43.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:31:43.238 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:31:43.238 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:31:43.238 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
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
,2015-12-07 11:32:13.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:32:13.238 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:32:13.238 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:32:13.238 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:32:43.208 ThaliTest[321:112528] multipeer session: restart
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
,2015-12-07 11:33:13.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:33:13.235 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:33:13.235 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:33:13.236 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:33:43.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:33:43.233 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:33:43.233 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:33:43.234 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
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
,2015-12-07 11:34:13.208 ThaliTest[321:112528] multipeer session: restart
,2015-12-07 11:34:13.236 ThaliTest[321:112528] client: found peer: Apple-Iphone5s-1_PT6457.6Oi+cQ==
2015-12-07 11:34:13.237 ThaliTest[321:112528] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:34:13.237 ThaliTest[321:112528] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server

```
