#### Test 51335028c93db41_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51335028c93db41/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C82E574E-1F1A-4C12-9C49-BD1963CFD06F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/C82E574E-1F1A-4C12-9C49-BD1963CFD06F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51335028c93db41/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51335028c93db41/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1CEF5E24-6FA7-4409-85E9-7B100534D268/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55490"
,(lldb)     command script import "/tmp/C82E574E-1F1A-4C12-9C49-BD1963CFD06F/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-25 13:45:06.296 ThaliTest[1617:1372548] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/70388874-4D96-4D1A-8D60-306EE4858A67/Library/Cookies/Cookies.binarycookies
,2015-11-25 13:45:06.716 ThaliTest[1617:1372548] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-25 13:45:06.717 ThaliTest[1617:1372548] Multi-tasking -> Device: YES, App: YES
,2015-11-25 13:45:06.726 ThaliTest[1617:1372548] Unlimited access to network resources
,2015-11-25 13:45:06.733 ThaliTest[1617:1372548] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-25 13:45:10.204 ThaliTest[1617:1372548] Resetting plugins due to page load.
,2015-11-25 13:45:10.574 ThaliTest[1617:1372548] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/1CEF5E24-6FA7-4409-85E9-7B100534D268/ThaliTest.app/www/index.html
,2015-11-25 13:45:10.727 ThaliTest[1617:1372548] JXcore Cordova plugin initializing
,2015-11-25 13:45:10.728 ThaliTest[1617:1372671] JXcore instance initializing
,Initializing JXcore engine
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
Radios toggled
,my name is : Apple-Iphone5s-1_PT5807
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 62030
,2015-11-25 13:53:10.480 ThaliTest[1617:1372671] jxcore: startBroadcasting
,2015-11-25 13:53:10.492 ThaliTest[1617:1372671] server: starting Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25 13:53:10.493 ThaliTest[1617:1372671] multipeer session: start timer: 0x18d54c50
2015-11-25 13:53:10.494 ThaliTest[1617:1372671] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT5807
2015-11-25 13:53:10.496 ThaliTest[1617:1372671] jxcore,: startBroadcasting: success
StartBroadcasting started ok
,2015-11-25T12:53:10.499Z SendDataTCPServer.js: TCP/IP server is bound to port: 62030
,2015-11-25 13:53:10.952 ThaliTest[1617:1372548] client: found peer: Apple-Iphone6-1_PT8750.Du3EhQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8750.Du3EhQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT8750.Du3EhQ==
2015-11-25T12:53:10.963Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8750.Du3EhQ==
,2015-11-25T12:53:10.964Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8750.Du3EhQ==
,2015-11-25T12:53:10.964Z SendDataConnector.js: do connect now
,2015-11-25 13:53:10.966 ThaliTest[1617:1372671] jxcore: connect Apple-Iphone6-1_PT8750.Du3EhQ==
2015-11-25 13:53:10.967 ThaliTest[1617:1372671] client session: connect
2015-11-25 13:53:10.967 ThaliTest[1617:1372671] client session: stateChange:0->1 Apple,-Iphone6-1_PT8750.Du3EhQ==
,2015-11-25 13:53:11.381 ThaliTest[1617:1372548] multipeer session: reset timer
2015-11-25 13:53:11.382 ThaliTest[1617:1372548] multipeer session: stop timer
2015-11-25 13:53:11.382 ThaliTest[1617:1372548] multipeer session: start timer: 0x18d54c50
2015-,11-25 13:53:11.383 ThaliTest[1617:1372548] server session: connect
2015-11-25 13:53:11.383 ThaliTest[1617:1372548] server session: stateChange:0->1 Apple-Iphone6-1_PT8750
,2015-11-25 13:53:11.397 ThaliTest[1617:1372548] server: accepting invitation Apple-Iphone6-1_PT8750
,2015-11-25 13:53:11.451 ThaliTest[1617:1372548] client: found peer: Apple-IpadAir2-1_PT7357.1lZx3Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7357.1lZx3Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-25 13:53:11.737 ThaliTest[1617:1372548] client: found peer: Apple-Iphone5-1_PT9701.GagVHA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9701.GagVHA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-11-25 13:53:13.412 ThaliTest[1617:1373322] client session: connected
2015-11-25 13:53:13.413 ThaliTest[1617:1373322] client session: stateChange:1->2 Apple-Iphone6-1_PT8750.Du3EhQ==
,2015-11-25 13:53:13.424 ThaliTest[1617:1373322] client session: fireConnectCallback: Apple-Iphone6-1_PT8750.Du3EhQ==
2015-11-25 13:53:13.425 ThaliTest[1617:1373322] jxcore: connect: success
,2015-11-25T12:53:13.428Z SendDataConnector.js: CLIENT connected to 62033, error: null
,2015-11-25T12:53:13.429Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 13:53:13.433 ThaliTest[1617:1372548] client: relay established
2015-11-25 13:53:13.434 ThaliTest[1617:1372548] client: new accepted socket: 0x18d649f0
,2015-11-25T12:53:13.446Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T12:53:13.724Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-25T12:53:13.749Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-25 13:53:13.758 ThaliTest[1617:1372548] multipeer session: reset timer
2015-11-25 13:53:13.758 ThaliTest[1617:1372548] multipeer session: stop timer
2015-11-25 13:53:13.759 ThaliTest[1617:1372548] multipeer session: start timer: 0x18d54c50
2015-11-25 13:53:13.759 ThaliTest[1617:1372548] server session: connect
2015-11-25 13:53:13.759 ThaliTest[1617:1372548] server session: stateChange:0->1 Apple-Iphone5-1_PT9701
2015-11-25T12:53:13.763Z SendDataConnector.js: CLIENT is data received : 70000
201,5-11-25 13:53:13.765 ThaliTest[1617:1372548] server: accepting invitation Apple-Iphone5-1_PT9701
,2015-11-25T12:53:13.775Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-25T12:53:13.776Z SendDataConnector.js: got all data for this round
,2015-11-25T12:53:13.777Z SendDataConnector.js: CLIENT Stop now
2015-11-25T12:53:13.777Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-25 13:53:13.778 ThaliTest[1617:1372671] jxcore: disconnect
,2015-11-25 13:53:13.778 ThaliTest[1617:1372671] client session: disconnectFromPeer: Apple-Iphone6-1_PT8750.Du3EhQ==
2015-11-25 13:53:13.779 ThaliTest[1617:1372671] client session: disconnect
,2015-11-25 13:53:13.779 ThaliTest[1617:1372671] client session: stateChange:2->0 Apple-Iphone6-1_PT8750.Du3EhQ==
,2015-11-25 13:53:13.780 ThaliTest[1617:1372671] jxcore: disconnect: success
2015-11-25T12:53:13.781Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8750.Du3EhQ==
---- round done--------
,device[2]: Apple-IpadAir2-1_PT7357.1lZx3Q==
,2015-11-25T12:53:13.782Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7357.1lZx3Q==
2015-11-25T12:53:13.784Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7357.1lZx3Q==
2015-11-25T12:53:13.784Z SendDataConnector.js: do connect now
,2015-11-25 13:53:13.784 ThaliTest[1617:1372671] jxcore: connect Apple-IpadAir2-1_PT7357.1lZx3Q==
2015-11-25 13:53:13.785 ThaliTest[1617:1372671] client session: connect
2015-11-25 13:53:13.785 ThaliTest[1617:1372671] client session: stateChange:0->1 Apple-IpadAir2-1_PT7357.1lZx3Q==
,2015-11-25 13:53:13.862 ThaliTest[1617:1373318] server session: connected
2015-11-25 13:53:13.862 ThaliTest[1617:1373318] server session: stateChange:1->2 Apple-Iphone6-1_PT8750
,2015-11-25 13:53:13.873 ThaliTest[1617:1372548] server relay: connected (to port: 62030)
,2015-11-25T12:53:13.877Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T12:53:13.965Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-11-25T12:53:13.978Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-11-25T12:53:14.015Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 13:53:14.232 ThaliTest[1617:1373309] server session: not connected Apple-Iphone6-1_PT8750
,2015-11-25 13:53:16.375 ThaliTest[1617:1373318] server session: connected
2015-11-25 13:53:16.376 ThaliTest[1617:1373318] server session: stateChange:1->2 Apple-Iphone5-1_PT9701
,2015-11-25T12:53:16.387Z SendDataTCPServer.js: TCP/IP server connected
2015-11-25 13:53:16.388 ThaliTest[1617:1372548] server relay: connected (to port: 62030)
,2015-11-25T12:53:16.528Z SendDataTCPServer.js: TCP/IP server has received 2976 bytes of data
,2015-11-25T12:53:16.543Z SendDataTCPServer.js: TCP/IP server has received 8928 bytes of data
,2015-11-25T12:53:16.557Z SendDataTCPServer.js: TCP/IP server has received 18848 bytes of data
,2015-11-25T12:53:16.575Z SendDataTCPServer.js: TCP/IP server has received 33728 bytes of data
,2015-11-25T12:53:16.590Z SendDataTCPServer.js: TCP/IP server has received 49600 bytes of data
,2015-11-25T12:53:16.610Z SendDataTCPServer.js: TCP/IP server has received 66464 bytes of data
,2015-11-25T12:53:16.626Z SendDataTCPServer.js: TCP/IP server has received 78368 bytes of data
,2015-11-25T12:53:16.928Z SendDataTCPServer.js: TCP/IP server has received 83328 bytes of data
,2015-11-25T12:53:16.947Z SendDataTCPServer.js: TCP/IP server has received 96224 bytes of data
,2015-11-25T12:53:16.968Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 13:53:17.001 ThaliTest[1617:1373322] server session: not connected Apple-Iphone5-1_PT9701
,2015-11-25 13:53:17.546 ThaliTest[1617:1373318] client session: connected
2015-11-25 13:53:17.548 ThaliTest[1617:1373318] client session: stateChange:1->2 Apple-IpadAir2-1_PT7357.1lZx3Q==
2015-11-25 13:53:17.549 ThaliTest[1617:1373318] client session: fi,reConnectCallback: Apple-IpadAir2-1_PT7357.1lZx3Q==
2015-11-25 13:53:17.550 ThaliTest[1617:1373318] jxcore: connect: success
2015-11-25T12:53:17.551Z SendDataConnector.js: CLIENT connected to 62038, error: null
,2015-11-25T12:53:17.552Z SendDataConnector.js: CLIENT starting client 
2015-11-25 13:53:17.555 ThaliTest[1617:1372548] client: relay established
2015-11-25 13:53:17.556 ThaliTest[1617:1372548] client: new accepted socket: 0x18e577b0
,2015-11-25T12:53:17.568Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T12:53:18.039Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-25T12:53:18.467Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-25T12:53:18.481Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T12:53:18.482Z SendDataConnector.js: got all data for this round
,2015-11-25T12:53:18.485Z SendDataConnector.js: CLIENT Stop now
2015-11-25T12:53:18.485Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-25 13:53:18.486 ThaliTest[1617:1372671] jxcore: disconnect
,2015-11-25 13:53:18.487 ThaliTest[1617:1372671] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7357.1lZx3Q==
,2015-11-25 13:53:18.487 ThaliTest[1617:1372671] client session: disconnect
2015-11-25 13:53:18.488 ThaliTest[1617:1372671] client session: stateChange:2->0 Apple-IpadAir2-1_PT7357.1lZx3Q==
2015-11-25 13:53:18.492 ThaliTest[1617:1372671] jxcore: disconnect: success
,2015-11-25T12:53:18.494Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7357.1lZx3Q==
,---- round done--------
,device[3]: Apple-Iphone5-1_PT9701.GagVHA==
2015-11-25T12:53:18.499Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9701.GagVHA==
2015-11-25T12:53:18.499Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9701.GagVHA==
20,15-11-25T12:53:18.500Z SendDataConnector.js: do connect now
,2015-11-25 13:53:18.500 ThaliTest[1617:1372671] jxcore: connect Apple-Iphone5-1_PT9701.GagVHA==
,2015-11-25 13:53:18.501 ThaliTest[1617:1372671] client session: connect
,2015-11-25 13:53:18.502 ThaliTest[1617:1372671] client session: stateChange:0->1 Apple-Iphone5-1_PT9701.GagVHA==
,2015-11-25 13:53:20.585 ThaliTest[1617:1372548] multipeer session: reset timer
2015-11-25 13:53:20.586 ThaliTest[1617:1372548] multipeer session: stop timer
2015-11-25 13:53:20.587 ThaliTest[1617:1372548] multipeer session: start timer: 0x18d54c50
2015-,11-25 13:53:20.587 ThaliTest[1617:1372548] server session: connect
2015-11-25 13:53:20.588 ThaliTest[1617:1372548] server session: stateChange:0->1 Apple-IpadAir2-1_PT7357
,2015-11-25 13:53:20.605 ThaliTest[1617:1372548] server: accepting invitation Apple-IpadAir2-1_PT7357
,2015-11-25 13:53:21.206 ThaliTest[1617:1373321] client session: connected
2015-11-25 13:53:21.207 ThaliTest[1617:1373321] client session: stateChange:1->2 Apple-Iphone5-1_PT9701.GagVHA==
,2015-11-25 13:53:21.215 ThaliTest[1617:1373321] client session: fireConnectCallback: Apple-Iphone5-1_PT9701.GagVHA==
2015-11-25 13:53:21.217 ThaliTest[1617:1373321] jxcore: connect: success
2015-11-25T12:53:21.220Z SendDataConnector.js: CLIENT connected ,to 62041, error: null
,2015-11-25T12:53:21.220Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 13:53:21.223 ThaliTest[1617:1372548] client: relay established
2015-11-25 13:53:21.224 ThaliTest[1617:1372548] client: new accepted socket: 0x18d72760
,2015-11-25T12:53:21.236Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T12:53:21.332Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-25T12:53:21.619Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-25T12:53:21.678Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T12:53:21.678Z SendDataConnector.js: got all data for this round
,2015-11-25T12:53:21.679Z SendDataConnector.js: CLIENT Stop now
2015-11-25T12:53:21.680Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-25 13:53:21.680 ThaliTest[1617:1372671] jxcore: disconnect
,2015-11-25 13:53:21.681 ThaliTest[1617:1372671] client session: disconnectFromPeer: Apple-Iphone5-1_PT9701.GagVHA==
,2015-11-25 13:53:21.681 ThaliTest[1617:1372671] client session: disconnect
2015-11-25 13:53:21.682 ThaliTest[1617:1372671] client session: stateChange:2->0 Apple-Iphone5-1_PT9701.GagVHA==
,2015-11-25 13:53:21.685 ThaliTest[1617:1372671] jxcore: disconnect: success
,2015-11-25T12:53:21.688Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9701.GagVHA==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT5807","time":11228,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT8750.Du3EhQ==","time":2813,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1,_PT7357.1lZx3Q==","time":4699,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT9701.GagVHA==","time":3180,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 4699 ms, 99% : 4699 ms, 95 : 4699 ms, 90% : 4699 ms.
,Result count 3, range 2813 ms to  4699 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-11-25T12:53:21.699Z SendDataConnector.js: CLIENT Stop now
,2015-11-25T12:53:21.699Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 13:53:23.256 ThaliTest[1617:1373318] server session: connected
2015-11-25 13:53:23.257 ThaliTest[1617:1373318] server session: stateChange:1->2 Apple-IpadAir2-1_PT7357
,2015-11-25 13:53:23.281 ThaliTest[1617:1372548] server relay: connected (to port: 62030)
2015-11-25T12:53:23.283Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T12:53:23.714Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-11-25T12:53:23.728Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-11-25T12:53:23.745Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-11-25T12:53:23.762Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-11-25T12:53:23.778Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-11-25T12:53:23.797Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 13:53:23.815 ThaliTest[1617:1373316] server session: not connected Apple-IpadAir2-1_PT7357
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-25 13:53:24.538 ThaliTest[1617:1372671] jxcore: stopBroadcasting
,2015-11-25 13:53:24.540 ThaliTest[1617:1372671] THEMultipeerSession stopping peer
,2015-11-25 13:53:24.540 ThaliTest[1617:1372671] multipeer session: stop timer
2015-11-25 13:53:24.542 ThaliTest[1617:1372671] server session: disconnect
2015-11-25 13:53:24.542 ThaliTest[1617:1372671] server session: stateChange:2->0 Apple-Iphone5-1_PT97,01
2015-11-25 13:53:24.549 ThaliTest[1617:1372671] server session: disconnect
2015-11-25 13:53:24.550 ThaliTest[1617:1372671] server session: stateChange:2->0 Apple-IpadAir2-1_PT7357
,2015-11-25 13:53:24.556 ThaliTest[1617:1372671] server session: disconnect
2015-11-25 13:53:24.557 ThaliTest[1617:1372671] server session: stateChange:2->0 Apple-Iphone6-1_PT8750
,2015-11-25 13:53:24.564 ThaliTest[1617:1372671] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-11-25T12:53:24.585Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T12:53:24.587Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T12:53:24.590Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T12:53:24.591Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT8750.Du3EhQ==\",\"time\":2813,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone5-1_PT9701.GagVHA==\",\"time\":3180,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-IpadAir2-1_PT7357.1lZx3Q==\",\"time\":4699,\"result\":\"OK\",\"connections\":1,,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received

```
