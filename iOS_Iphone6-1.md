#### Test 519863404492c11_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/519863404492c11/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/CBD09195-DE2A-45FA-B2A1-3E94DDFC9F7D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/CBD09195-DE2A-45FA-B2A1-3E94DDFC9F7D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/519863404492c11/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/519863404492c11/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EEF4491C-AE5D-4988-B4BC-6A086A100BB2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49620"
,(lldb)     command script import "/tmp/CBD09195-DE2A-45FA-B2A1-3E94DDFC9F7D/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-07 07:47:09.494 ThaliTest[353:102433] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C3F43259-FD18-4442-9005-ED4FF795F7CF/Library/Cookies/Cookies.binarycookies
,2015-12-07 07:47:09.972 ThaliTest[353:102433] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-07 07:47:09.973 ThaliTest[353:102433] Multi-tasking -> Device: YES, App: YES
,2015-12-07 07:47:09.983 ThaliTest[353:102433] Unlimited access to network resources
,2015-12-07 07:47:09.997 ThaliTest[353:102433] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 07:47:19.178 ThaliTest[353:102433] Resetting plugins due to page load.
,2015-12-07 07:47:23.031 ThaliTest[353:102433] Finished load of: file:///var/mobile/Containers/Bundle/Application/EEF4491C-AE5D-4988-B4BC-6A086A100BB2/ThaliTest.app/www/index.html
,2015-12-07 07:47:23.228 ThaliTest[353:102433] JXcore Cordova plugin initializing
,2015-12-07 07:47:23.229 ThaliTest[353:102641] JXcore instance initializing
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
,Radios toggled
,my name is : Apple-Iphone6-1_PT7482
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 49981
,2015-12-07 07:54:46.984 ThaliTest[353:102641] jxcore: startBroadcasting
,2015-12-07 07:54:47.008 ThaliTest[353:102641] server: starting Apple-Iphone6-1_PT7482.CDxPNA==
,2015-12-07 07:54:47.013 ThaliTest[353:102641] multipeer session: start timer: 0x1778bb10
2015-12-07 07:54:47.013 ThaliTest[353:102641] THEMultipeerSession initialized peer Apple-Iphone6-1_PT7482
2015-12-07 07:54:47.014 ThaliTest[353:102641] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-07T06:54:47.016Z SendDataTCPServer.js: TCP/IP server is bound to port: 49981
,2015-12-07 07:54:49.201 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7843.gS16eg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07T06:54:49.207Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07T06:54:49.208Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07T06:54:49.208Z SendDataConnector.js: do connect now
,2015-12-07 07:54:49.209 ThaliTest[353:102641] jxcore: connect Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 07:54:49.210 ThaliTest[353:102641] client session: connect
2015-12-07 07:54:49.210 ThaliTest[353:102641] client session: stateChange:0->1 Apple-Ipho,ne5s-1_PT7843.gS16eg==
,2015-12-07 07:54:49.513 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1974.yVUIQA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
,2015-12-07 07:54:50.035 ThaliTest[353:102433] multipeer session: reset timer
2015-12-07 07:54:50.035 ThaliTest[353:102433] multipeer session: stop timer
2015-12-07 07:54:50.035 ThaliTest[353:102433] multipeer session: start timer: 0x1778bb10
,2015-12-07 07:54:50.038 ThaliTest[353:102433] server session: connect
2015-12-07 07:54:50.038 ThaliTest[353:102433] server session: stateChange:0->1 Apple-Iphone5-1_PT1974
2015-12-07 07:54:50.046 ThaliTest[353:102433] server: accepting invitation Apple-Iphone5-1_PT1974
,2015-12-07 07:54:50.243 ThaliTest[353:102433] multipeer session: reset timer
2015-12-07 07:54:50.244 ThaliTest[353:102433] multipeer session: stop timer
2015-12-07 07:54:50.244 ThaliTest[353:102433] multipeer session: start timer: 0x1778bb10
2015-12-07 ,07:54:50.244 ThaliTest[353:102433] server session: connect
2015-12-07 07:54:50.244 ThaliTest[353:102433] server session: stateChange:0->1 Apple-Iphone5s-1_PT7843
,2015-12-07 07:54:50.258 ThaliTest[353:102433] server: accepting invitation Apple-Iphone5s-1_PT7843
,2015-12-07 07:54:53.312 ThaliTest[353:103377] server session: connected
2015-12-07 07:54:53.312 ThaliTest[353:103377] server session: stateChange:1->2 Apple-Iphone5-1_PT1974
,2015-12-07 07:54:53.329 ThaliTest[353:102433] server relay: connected (to port: 49981)
2015-12-07T06:54:53.331Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-07 07:54:53.776 ThaliTest[353:103331] client session: connected
2015-12-07 07:54:53.776 ThaliTest[353:103331] client session: stateChange:1->2 Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 07:54:53.824 ThaliTest[353:103377] client session: fireConnectCallback: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 07:54:53.824 ThaliTest[353:103377] jxcore: connect: success
,2015-12-07T06:54:53.827Z SendDataConnector.js: CLIENT connected to 49985, error: null
,2015-12-07T06:54:53.828Z SendDataConnector.js: CLIENT starting client 
,2015-12-07 07:54:53.835 ThaliTest[353:102433] client: relay established
2015-12-07 07:54:53.835 ThaliTest[353:102433] client: new accepted socket: 0x1779e840
,2015-12-07T06:54:53.850Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07T06:54:54.183Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-07T06:54:54.348Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-07T06:54:54.361Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-07T06:54:54.362Z SendDataConnector.js: got all data for this round
,2015-12-07T06:54:54.363Z SendDataConnector.js: CLIENT Stop now
,2015-12-07T06:54:54.363Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 07:54:54.364 ThaliTest[353:102641] jxcore: disconnect
,2015-12-07 07:54:54.365 ThaliTest[353:102641] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 07:54:54.365 ThaliTest[353:102641] client session: disconnect
,2015-12-07 07:54:54.366 ThaliTest[353:102641] client session: stateChange:2->0 Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 07:54:54.432 ThaliTest[353:102641] jxcore: disconnect: success
,2015-12-07T06:54:54.433Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7843.gS16eg==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07T06:54:54.435Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07T06:54:54.435Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07T06:54:54.435Z SendDataConnector.js: do connect now
,2015-12-07 07:54:54.436 ThaliTest[353:102641] jxcore: connect Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 07:54:54.436 ThaliTest[353:102641] client session: connect
,2015-12-07 07:54:54.437 ThaliTest[353:102641] client session: stateChange:0->1 Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07T06:54:54.549Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07 07:54:54.819 ThaliTest[353:103329] server session: not connected Apple-Iphone5-1_PT1974
,2015-12-07 07:54:55.285 ThaliTest[353:103331] server session: connected
2015-12-07 07:54:55.294 ThaliTest[353:103331] server session: stateChange:1->2 Apple-Iphone5s-1_PT7843
,2015-12-07 07:54:55.305 ThaliTest[353:102433] server relay: connected (to port: 49981)
,2015-12-07T06:54:55.317Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-07 07:54:55.493 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT12.Gapeow==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-07T06:54:55.790Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-07T06:54:55.816Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-07T06:54:55.867Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07 07:54:56.481 ThaliTest[353:103377] server session: not connected Apple-Iphone5s-1_PT7843
,2015-12-07 07:54:57.033 ThaliTest[353:102433] multipeer session: reset timer
2015-12-07 07:54:57.034 ThaliTest[353:102433] multipeer session: stop timer
2015-12-07 07:54:57.034 ThaliTest[353:102433] multipeer session: start timer: 0x1778bb10
2015-12-07 07:54:57.034 ThaliTest[353:102433] server session: connect
2015-12-07 07:54:57.034 ThaliTest[353:102433] server session: stateChange:0->1 Apple-IpadAir2-1_PT12
,2015-12-07 07:54:57.041 ThaliTest[353:102433] server: accepting invitation Apple-IpadAir2-1_PT12
,2015-12-07 07:54:57.955 ThaliTest[353:103331] client session: connected
,2015-12-07 07:54:57.955 ThaliTest[353:103331] client session: stateChange:1->2 Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 07:54:57.958 ThaliTest[353:103331] client session: fireConnectCallback: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 07:54:57.958 ThaliTest[353:103331] jxcore: connect: success
2015-12-07T06:54:57.959Z SendDataConnector.js: CLIENT connected to 49989, error: null
,2015-12-07T06:54:57.960Z SendDataConnector.js: CLIENT starting client 
2015-12-07 07:54:57.963 ThaliTest[353:102433] client: relay established
2015-12-07 07:54:57.963 ThaliTest[353:102433] client: new accepted socket: 0x17650980
,2015-12-07T06:54:57.975Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07T06:54:58.461Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-07T06:54:58.487Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-07T06:54:58.488Z SendDataConnector.js: got all data for this round
,2015-12-07T06:54:58.488Z SendDataConnector.js: CLIENT Stop now
,2015-12-07T06:54:58.489Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 07:54:58.490 ThaliTest[353:102641] jxcore: disconnect
,2015-12-07 07:54:58.491 ThaliTest[353:102641] client session: disconnectFromPeer: Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 07:54:58.491 ThaliTest[353:102641] client session: disconnect
,2015-12-07 07:54:58.492 ThaliTest[353:102641] client session: stateChange:2->0 Apple-Iphone5-1_PT1974.yVUIQA==
,2015-12-07 07:54:58.561 ThaliTest[353:102641] jxcore: disconnect: success
,2015-12-07T06:54:58.561Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT1974.yVUIQA==
,---- round done--------
,device[3]: Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07T06:54:58.563Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07T06:54:58.564Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07T06:54:58.565Z SendDataConnector.js: do connect now
,2015-12-07 07:54:58.565 ThaliTest[353:102641] jxcore: connect Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07 07:54:58.567 ThaliTest[353:102641] client session: connect
,2015-12-07 07:54:58.568 ThaliTest[353:102641] client session: stateChange:0->1 Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07 07:55:00.028 ThaliTest[353:103331] server session: connected
2015-12-07 07:55:00.028 ThaliTest[353:103331] server session: stateChange:1->2 Apple-IpadAir2-1_PT12
,2015-12-07 07:55:00.042 ThaliTest[353:102433] server relay: connected (to port: 49981)
,2015-12-07T06:55:00.049Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-07T06:55:00.515Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-07T06:55:00.529Z SendDataTCPServer.js: TCP/IP server has received 39278 bytes of data
,2015-12-07T06:55:00.546Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-07T06:55:00.560Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-07T06:55:00.575Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-07T06:55:00.589Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07 07:55:00.612 ThaliTest[353:103377] server session: not connected Apple-IpadAir2-1_PT12
,2015-12-07 07:55:02.924 ThaliTest[353:103393] client session: connected
2015-12-07 07:55:02.925 ThaliTest[353:103393] client session: stateChange:1->2 Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07 07:55:03.147 ThaliTest[353:103377] client session: fireConnectCallback: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 07:55:03.150 ThaliTest[353:103377] jxcore: connect: success
2015-12-07T06:55:03.151Z SendDataConnector.js: CLIENT connected to 49,994, error: null
,2015-12-07T06:55:03.152Z SendDataConnector.js: CLIENT starting client 
,2015-12-07 07:55:03.158 ThaliTest[353:102433] client: relay established
2015-12-07 07:55:03.158 ThaliTest[353:102433] client: new accepted socket: 0x15e42930
,2015-12-07T06:55:03.170Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07T06:55:03.444Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-07T06:55:03.652Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-07T06:55:03.664Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-07T06:55:03.664Z SendDataConnector.js: got all data for this round
,2015-12-07T06:55:03.665Z SendDataConnector.js: CLIENT Stop now
2015-12-07T06:55:03.665Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 07:55:03.665 ThaliTest[353:102641] jxcore: disconnect
2015-12-07 07:55:03.665 ThaliTest[353:102641] client session: disconnectFromPeer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 07:55:03.665 ThaliTest[353:102641] client session: disconnect
20,15-12-07 07:55:03.666 ThaliTest[353:102641] client session: stateChange:2->0 Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07 07:55:03.670 ThaliTest[353:102641] jxcore: disconnect: success
2015-12-07T06:55:03.670Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT12.Gapeow==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-Iphone6-1_PT7482","time":16703,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT7843.gS16eg==","time":5154,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT1974.yVUIQA==","time":4053,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT12.Gapeow==","time":5100,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
sendList : 100% : 5154 ms, 99% : 5154 ms, 95 : 5154 ms, 90% : 5154 ms.
Result count 3, range 4053 ms to  5154 ms.
,sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-12-07T06:55:03.674Z SendDataConnector.js: CLIENT Stop now
2015-12-07T06:55:03.675Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 07:55:27.035 ThaliTest[353:102433] multipeer session: restart
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
,2015-12-07 07:55:57.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 07:55:57.080 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 07:55:57.080 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 07:55:57.080 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 07:56:27.035 ThaliTest[353:102433] multipeer session: restart
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
,2015-12-07 07:56:57.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 07:56:57.077 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 07:56:57.078 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 07:56:57.078 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 07:57:27.035 ThaliTest[353:102433] multipeer session: restart
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
,2015-12-07 07:57:57.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 07:57:57.074 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 07:57:57.077 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 07:57:57.077 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 07:58:27.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 07:58:27.080 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 07:58:27.081 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 07:58:27.081 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 07:58:57.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 07:58:57.073 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 07:58:57.075 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 07:58:57.075 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
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
,2015-12-07 07:59:27.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 07:59:27.076 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 07:59:27.077 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 07:59:27.077 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
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
,2015-12-07 07:59:57.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 07:59:57.078 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 07:59:57.078 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 07:59:57.079 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
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
,2015-12-07 08:00:27.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 08:00:27.075 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:00:27.076 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:00:27.076 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
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
,2015-12-07 08:00:57.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 08:00:57.078 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:00:57.078 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:00:57.079 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 08:01:27.034 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 08:01:27.077 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:01:27.078 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 08:01:27.078 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 08:01:57.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 08:01:57.074 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:01:57.075 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:01:57.075 ThaliTest[353:102433] client: foun,d peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-07 08:02:27.035 ThaliTest[353:102433] multipeer session: restart
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
,2015-12-07 08:02:57.034 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 08:02:57.077 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:02:57.077 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:02:57.078 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
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
,2015-12-07 08:03:27.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 08:03:27.078 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:03:27.079 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 08:03:27.079 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
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
,2015-12-07 08:03:57.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 08:03:57.079 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:03:57.080 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:03:57.080 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 08:04:27.035 ThaliTest[353:102433] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
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
Error type "connect_error" when connecting to the test server
,2015-12-07 08:04:57.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 08:04:57.077 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:04:57.078 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:04:57.078 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
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
,2015-12-07 08:05:27.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 08:05:27.079 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:05:27.080 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:05:27.080 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:05:57.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 08:05:57.076 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
,2015-12-07 08:05:57.077 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:05:57.078 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 08:06:27.035 ThaliTest[353:102433] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
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
,2015-12-07 08:06:57.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 08:06:57.076 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:06:57.078 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:06:57.079 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 08:07:27.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 08:07:27.082 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:07:27.082 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:07:27.083 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
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
,2015-12-07 08:07:57.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 08:07:57.077 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:07:57.077 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 08:07:57.077 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
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
,2015-12-07 08:08:27.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 08:08:27.076 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:08:27.077 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:08:27.080 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
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
,2015-12-07 08:08:57.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 08:08:57.079 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:08:57.079 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:08:57.080 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 08:09:27.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 08:09:27.079 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:09:27.080 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:09:27.080 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
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
,2015-12-07 08:09:57.035 ThaliTest[353:102433] multipeer session: restart
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
,2015-12-07 08:10:27.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 08:10:27.077 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:10:27.077 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:10:27.078 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
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
,2015-12-07 08:10:57.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 08:10:57.075 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,2015-12-07 08:10:57.078 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:10:57.078 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 08:11:27.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 08:11:27.079 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:11:27.079 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:11:27.080 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 08:11:57.035 ThaliTest[353:102433] multipeer session: restart
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
,2015-12-07 08:12:27.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 08:12:27.077 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:12:27.077 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:12:27.077 ThaliTest[353:102433] client: fou,nd peer: Apple-IpadAir2-1_PT12.Gapeow==
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
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 08:12:57.035 ThaliTest[353:102433] multipeer session: restart
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
,2015-12-07 08:13:27.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 08:13:27.078 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:13:27.079 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
2015-12-07 08:13:27.079 ThaliTest[353:102433] client: foun,d peer: Apple-Iphone5-1_PT1974.yVUIQA==
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
,2015-12-07 08:13:57.035 ThaliTest[353:102433] multipeer session: restart
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
,2015-12-07 08:14:27.035 ThaliTest[353:102433] multipeer session: restart
,2015-12-07 08:14:27.075 ThaliTest[353:102433] client: found peer: Apple-Iphone5-1_PT1974.yVUIQA==
2015-12-07 08:14:27.076 ThaliTest[353:102433] client: found peer: Apple-IpadAir2-1_PT12.Gapeow==
2015-12-07 08:14:27.076 ThaliTest[353:102433] client: found peer: Apple-Iphone5s-1_PT7843.gS16eg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server

```
