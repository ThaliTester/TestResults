#### Test 51986340afa1391_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51986340afa1391/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/18C8F24C-21D2-448A-99BE-44B507AEF2F9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/18C8F24C-21D2-448A-99BE-44B507AEF2F9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51986340afa1391/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51986340afa1391/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/35B710C3-1CDF-4C1A-83A7-9C7B1FF6E19C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49817"
,(lldb)     command script import "/tmp/18C8F24C-21D2-448A-99BE-44B507AEF2F9/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-07 11:06:55.171 ThaliTest[348:123522] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B7245198-C686-40BD-AEA3-A51AC8D5E88B/Library/Cookies/Cookies.binarycookies
,2015-12-07 11:06:55.530 ThaliTest[348:123522] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-07 11:06:55.531 ThaliTest[348:123522] Multi-tasking -> Device: YES, App: YES
,2015-12-07 11:06:55.539 ThaliTest[348:123522] Unlimited access to network resources
,2015-12-07 11:06:55.552 ThaliTest[348:123522] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 11:07:05.075 ThaliTest[348:123522] Resetting plugins due to page load.
,2015-12-07 11:07:08.039 ThaliTest[348:123522] Finished load of: file:///var/mobile/Containers/Bundle/Application/35B710C3-1CDF-4C1A-83A7-9C7B1FF6E19C/ThaliTest.app/www/index.html
,2015-12-07 11:07:08.252 ThaliTest[348:123522] JXcore Cordova plugin initializing
,2015-12-07 11:07:08.254 ThaliTest[348:123860] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone5s-1_PT6457
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 50511
,2015-12-07 11:14:10.419 ThaliTest[348:123860] jxcore: startBroadcasting
,2015-12-07 11:14:10.440 ThaliTest[348:123860] server: starting Apple-Iphone5s-1_PT6457.6Oi+cQ==
,2015-12-07 11:14:10.442 ThaliTest[348:123860] multipeer session: start timer: 0x196ebb60
,2015-12-07 11:14:10.458 ThaliTest[348:123860] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT6457
,2015-12-07 11:14:10.462 ThaliTest[348:123860] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-07T10:14:10.466Z SendDataTCPServer.js: TCP/IP server is bound to port: 50511
,2015-12-07 11:14:11.101 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5016.vGdGUg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07T10:14:11.110Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07T10:14:11.111Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07T10:14:11.111Z SendDataConnector.js: do connect now
,2015-12-07 11:14:11.112 ThaliTest[348:123860] jxcore: connect Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:14:11.113 ThaliTest[348:123860] client session: connect
,2015-12-07 11:14:11.115 ThaliTest[348:123860] client session: stateChange:0->1 Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:14:11.576 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6748.+3JG2Q==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-07 11:14:11.603 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT94.0IbCHA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-07 11:14:15.322 ThaliTest[348:124667] client session: connected
2015-12-07 11:14:15.322 ThaliTest[348:124667] client session: stateChange:1->2 Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:14:15.398 ThaliTest[348:124658] client session: fireConnectCallback: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:14:15.398 ThaliTest[348:124658] jxcore: connect: success
,2015-12-07T10:14:15.401Z SendDataConnector.js: CLIENT connected to 50514, error: null
2015-12-07T10:14:15.402Z SendDataConnector.js: CLIENT starting client 
,2015-12-07 11:14:15.421 ThaliTest[348:123522] client: relay established
,2015-12-07 11:14:15.421 ThaliTest[348:123522] client: new accepted socket: 0x196f7c90
,2015-12-07T10:14:15.427Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07 11:14:15.454 ThaliTest[348:123522] multipeer session: reset timer
2015-12-07 11:14:15.454 ThaliTest[348:123522] multipeer session: stop timer
,2015-12-07 11:14:15.455 ThaliTest[348:123522] multipeer session: start timer: 0x196ebb60
2015-12-07 11:14:15.455 ThaliTest[348:123522] server session: connect
,2015-12-07 11:14:15.455 ThaliTest[348:123522] server session: stateChange:0->1 Apple-Iphone6-1_PT6748
,2015-12-07 11:14:15.469 ThaliTest[348:123522] server: accepting invitation Apple-Iphone6-1_PT6748
,2015-12-07 11:14:15.823 ThaliTest[348:123522] multipeer session: reset timer
2015-12-07 11:14:15.823 ThaliTest[348:123522] multipeer session: stop timer
2015-12-07 11:14:15.824 ThaliTest[348:123522] multipeer session: start timer: 0x196ebb60
,2015-12-07 11:14:15.824 ThaliTest[348:123522] server session: connect
2015-12-07 11:14:15.825 ThaliTest[348:123522] server session: stateChange:0->1 Apple-IpadAir2-1_PT5016
,2015-12-07 11:14:15.831 ThaliTest[348:123522] server: accepting invitation Apple-IpadAir2-1_PT5016
,2015-12-07T10:14:15.847Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-07T10:14:15.875Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-07T10:14:15.900Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-07T10:14:15.953Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-07T10:14:15.968Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-07T10:14:15.968Z SendDataConnector.js: got all data for this round
,2015-12-07T10:14:15.970Z SendDataConnector.js: CLIENT Stop now
2015-12-07T10:14:15.970Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 11:14:15.971 ThaliTest[348:123860] jxcore: disconnect
,2015-12-07 11:14:15.973 ThaliTest[348:123860] client session: disconnectFromPeer: Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:14:15.974 ThaliTest[348:123860] client session: disconnect
,2015-12-07 11:14:15.974 ThaliTest[348:123860] client session: stateChange:2->0 Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:14:15.985 ThaliTest[348:123860] jxcore: disconnect: success
,2015-12-07T10:14:15.989Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5016.vGdGUg==
,---- round done--------
,device[2]: Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07T10:14:15.991Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07T10:14:15.992Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07T10:14:15.992Z SendDataConnector.js: do connect now
,2015-12-07 11:14:15.993 ThaliTest[348:123860] jxcore: connect Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:14:15.994 ThaliTest[348:123860] client session: connect
,2015-12-07 11:14:15.995 ThaliTest[348:123860] client session: stateChange:0->1 Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:14:18.109 ThaliTest[348:124720] server session: connected
2015-12-07 11:14:18.109 ThaliTest[348:124720] server session: stateChange:1->2 Apple-Iphone6-1_PT6748
,2015-12-07T10:14:18.405Z SendDataTCPServer.js: TCP/IP server connected
2015-12-07 11:14:18.406 ThaliTest[348:123522] server relay: connected (to port: 50511)
2015-12-07 11:14:18.409 ThaliTest[348:124659] server session: connected
,2015-12-07 11:14:18.409 ThaliTest[348:124659] server session: stateChange:1->2 Apple-IpadAir2-1_PT5016
,2015-12-07 11:14:18.439 ThaliTest[348:123522] server relay: connected (to port: 50511)
,2015-12-07T10:14:18.448Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-07T10:14:18.848Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-07T10:14:18.863Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-07T10:14:18.881Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-07T10:14:18.900Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-07T10:14:18.903Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-07T10:14:18.947Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-07T10:14:18.954Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07T10:14:18.973Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-07T10:14:18.990Z SendDataTCPServer.js: TCP/IP server has received 96218 bytes of data
,2015-12-07T10:14:19.006Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07 11:14:19.030 ThaliTest[348:124720] server session: not connected Apple-Iphone6-1_PT6748
,2015-12-07 11:14:19.082 ThaliTest[348:124658] server session: not connected Apple-IpadAir2-1_PT5016
,2015-12-07 11:14:19.405 ThaliTest[348:124658] client session: connected
2015-12-07 11:14:19.408 ThaliTest[348:124658] client session: stateChange:1->2 Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:14:19.442 ThaliTest[348:124659] client session: fireConnectCallback: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:14:19.442 ThaliTest[348:124659] jxcore: connect: success
2015-12-07T10:14:19.444Z SendDataConnector.js: CLIENT connected to 5,0519, error: null
2015-12-07T10:14:19.444Z SendDataConnector.js: CLIENT starting client 
,2015-12-07 11:14:19.450 ThaliTest[348:123522] client: relay established
2015-12-07 11:14:19.451 ThaliTest[348:123522] client: new accepted socket: 0x196746e0
,2015-12-07T10:14:19.462Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07T10:14:19.933Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-07T10:14:19.979Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-07T10:14:20.014Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-07T10:14:20.014Z SendDataConnector.js: got all data for this round
,2015-12-07T10:14:20.015Z SendDataConnector.js: CLIENT Stop now
2015-12-07T10:14:20.015Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 11:14:20.016 ThaliTest[348:123860] jxcore: disconnect
2015-12-07 11:14:20.016 ThaliTest[348:123860] client session: disconnectFromPeer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:14:20.017 ThaliTest[348:123860] client session: disconnect
2015-12-07 11:14:20.017 ThaliTest[348:123860] client session: stateChange:2->0 Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:14:20.023 ThaliTest[348:123860] jxcore: disconnect: success
2015-12-07T10:14:20.023Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6748.+3JG2Q==
---- round done--------
device[3]: Apple-Iphone5-1_PT94.0IbCH,A==
2015-12-07T10:14:20.024Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07T10:14:20.024Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07T10:14:20.024Z SendDataConnector.js: do connect now
2015-12-07 11:14:20.025 ThaliTest[348:123860] jxcore: connect Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:14:20.025 ThaliTest[348:123860] client session: connect
2015-12-07 11:14:20.027 ThaliTest[348:123860] client session: stateChange:0->1 Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:14:22.733 ThaliTest[348:123522] multipeer session: reset timer
2015-12-07 11:14:22.733 ThaliTest[348:123522] multipeer session: stop timer
2015-12-07 11:14:22.733 ThaliTest[348:123522] multipeer session: start timer: 0x196ebb60
2015-12-07 ,11:14:22.734 ThaliTest[348:123522] server session: connect
2015-12-07 11:14:22.735 ThaliTest[348:123522] server session: stateChange:0->1 Apple-Iphone5-1_PT94
,2015-12-07 11:14:22.747 ThaliTest[348:123522] server: accepting invitation Apple-Iphone5-1_PT94
,2015-12-07 11:14:24.294 ThaliTest[348:124668] client session: connected
,2015-12-07 11:14:24.295 ThaliTest[348:124668] client session: stateChange:1->2 Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:14:24.317 ThaliTest[348:124668] client session: fireConnectCallback: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:14:24.317 ThaliTest[348:124668] jxcore: connect: success
2015-12-07T10:14:24.318Z SendDataConnector.js: CLIENT connected to 505,22, error: null
2015-12-07T10:14:24.319Z SendDataConnector.js: CLIENT starting client 
,2015-12-07 11:14:24.324 ThaliTest[348:123522] client: relay established
2015-12-07 11:14:24.324 ThaliTest[348:123522] client: new accepted socket: 0x196e4900
,2015-12-07T10:14:24.335Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-07T10:14:24.877Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-07T10:14:24.890Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-07T10:14:25.137Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-07T10:14:25.154Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-07T10:14:25.154Z SendDataConnector.js: got all data for this round
,2015-12-07T10:14:25.157Z SendDataConnector.js: CLIENT Stop now
,2015-12-07T10:14:25.158Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 11:14:25.160 ThaliTest[348:123860] jxcore: disconnect
,2015-12-07 11:14:25.162 ThaliTest[348:123860] client session: disconnectFromPeer: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:14:25.163 ThaliTest[348:123860] client session: disconnect
,2015-12-07 11:14:25.165 ThaliTest[348:123860] client session: stateChange:2->0 Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:14:25.279 ThaliTest[348:123860] jxcore: disconnect: success
,2015-12-07T10:14:25.281Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT94.0IbCHA==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT6457","time":14887,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT5016.vGdGUg==","time":4859,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1,_PT6748.+3JG2Q==","time":4022,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT94.0IbCHA==","time":5131,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 5131 ms, 99% : 5131 ms, 95 : 5131 ms, 90% : 5131 ms.
,Result count 3, range 4022 ms to  5131 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-07T10:14:25.303Z SendDataConnector.js: CLIENT Stop now
,2015-12-07T10:14:25.304Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-07 11:14:26.796 ThaliTest[348:124668] server session: connected
2015-12-07 11:14:26.797 ThaliTest[348:124668] server session: stateChange:1->2 Apple-Iphone5-1_PT94
,2015-12-07 11:14:26.844 ThaliTest[348:123522] server relay: connected (to port: 50511)
,2015-12-07T10:14:26.853Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-07T10:14:27.351Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-07T10:14:27.368Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-07T10:14:27.385Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-07T10:14:27.831Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-07T10:14:27.846Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-07T10:14:27.887Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-07T10:14:27.902Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-07T10:14:28.415Z SendDataTCPServer.js: TCP/IP server has received 80320 bytes of data
,2015-12-07T10:14:28.432Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-07 11:14:34.184 ThaliTest[348:124659] server session: not connected Apple-Iphone5-1_PT94
,2015-12-07 11:14:52.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:15:22.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:15:22.793 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:15:22.794 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:15:23.637 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:15:52.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:15:52.797 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:15:52.801 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:15:52.803 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:16:22.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:16:22.796 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:16:22.797 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:16:23.461 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
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
,2015-12-07 11:16:52.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:16:52.795 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:16:52.796 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:16:52.796 ThaliTest[348:123522] client: found, peer: Apple-Iphone6-1_PT6748.+3JG2Q==
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
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-07 11:17:22.734 ThaliTest[348:123522] multipeer session: restart
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
,2015-12-07 11:17:52.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:17:52.793 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:17:52.794 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:17:52.795 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
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
,2015-12-07 11:18:22.735 ThaliTest[348:123522] multipeer session: restart
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
,2015-12-07 11:18:52.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:18:52.780 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:18:52.780 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:18:52.781 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
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
,2015-12-07 11:19:22.734 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:19:22.778 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:19:22.781 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:19:22.784 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
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
,2015-12-07 11:19:52.735 ThaliTest[348:123522] multipeer session: restart
DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-07 11:19:52.799 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:19:52.802 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:19:52.804 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
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
,2015-12-07 11:20:22.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:20:22.792 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:20:22.794 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:20:22.795 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,2015-12-07 11:20:52.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:20:52.797 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:20:52.798 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:20:52.799 ThaliTest[348:123522] client: found, peer: Apple-Iphone6-1_PT6748.+3JG2Q==
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
,2015-12-07 11:21:22.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:21:22.796 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:21:22.796 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:21:22.797 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
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
,2015-12-07 11:21:52.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:21:52.798 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:21:52.799 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:21:52.799 ThaliTest[348:123522] client: found, peer: Apple-Iphone6-1_PT6748.+3JG2Q==
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
,2015-12-07 11:22:22.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:22:22.793 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:22:22.795 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:22:22.795 ThaliTest[348:123522] client: fou,nd peer: Apple-Iphone5-1_PT94.0IbCHA==
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
,2015-12-07 11:22:52.734 ThaliTest[348:123522] multipeer session: restart
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
,2015-12-07 11:23:22.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:23:22.794 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:23:22.795 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:23:22.795 ThaliTest[348:123522] client: found, peer: Apple-Iphone6-1_PT6748.+3JG2Q==
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
,2015-12-07 11:23:52.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:23:52.803 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:23:52.804 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:23:52.804 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
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
,2015-12-07 11:24:22.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:24:22.795 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:24:22.795 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:24:22.799 ThaliTest[348:123522] client: fou,nd peer: Apple-Iphone5-1_PT94.0IbCHA==
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
,2015-12-07 11:24:52.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:24:52.798 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:24:52.799 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
,2015-12-07 11:24:53.270 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
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
,2015-12-07 11:25:22.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:25:22.794 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:25:22.795 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:25:22.796 ThaliTest[348:123522] client: found, peer: Apple-Iphone6-1_PT6748.+3JG2Q==
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
,2015-12-07 11:25:52.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:25:52.795 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:25:52.796 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:25:52.942 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,2015-12-07 11:26:22.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:26:22.798 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:26:22.799 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:26:22.800 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,2015-12-07 11:26:52.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:26:52.793 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:26:52.794 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:26:53.750 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,2015-12-07 11:27:22.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:27:22.788 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:27:22.789 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:27:23.099 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,2015-12-07 11:27:52.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:27:52.796 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:27:52.797 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:27:52.797 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
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
,2015-12-07 11:28:22.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:28:22.802 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:28:22.803 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:28:22.803 ThaliTest[348:123522] client: fou,nd peer: Apple-Iphone5-1_PT94.0IbCHA==
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
,2015-12-07 11:28:52.734 ThaliTest[348:123522] multipeer session: restart
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
,2015-12-07 11:29:22.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:29:22.794 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:29:22.795 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:29:22.796 ThaliTest[348:123522] client: found ,peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,2015-12-07 11:29:52.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:29:52.789 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:29:52.790 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:29:52.790 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
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
,2015-12-07 11:30:22.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:30:22.795 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:30:22.795 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:30:22.797 ThaliTest[348:123522] client: found, peer: Apple-Iphone6-1_PT6748.+3JG2Q==
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
,2015-12-07 11:30:52.735 ThaliTest[348:123522] multipeer session: restart
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
,2015-12-07 11:31:22.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:31:22.793 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:31:22.794 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
2015-12-07 11:31:22.795 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
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
,2015-12-07 11:31:52.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:31:52.801 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:31:52.802 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:31:52.805 ThaliTest[348:123522] client: found ,peer: Apple-IpadAir2-1_PT5016.vGdGUg==
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
,2015-12-07 11:32:22.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:32:22.783 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:32:22.783 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:32:22.784 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
DBG, CoordinatorConnector connect_timeout called
,Error type "connect_timeout" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-07 11:32:52.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:32:52.795 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:32:52.796 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:32:52.796 ThaliTest[348:123522] client: found ,peer: Apple-IpadAir2-1_PT5016.vGdGUg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-07 11:33:22.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:33:22.790 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:33:22.791 ThaliTest[348:123522] client: found peer: Apple-IpadAir2-1_PT5016.vGdGUg==
,2015-12-07 11:33:22.793 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 11:33:52.735 ThaliTest[348:123522] multipeer session: restart
,2015-12-07 11:33:52.790 ThaliTest[348:123522] client: found peer: Apple-Iphone6-1_PT6748.+3JG2Q==
2015-12-07 11:33:52.791 ThaliTest[348:123522] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
2015-12-07 11:33:52.795 ThaliTest[348:123522] client: found ,peer: Apple-IpadAir2-1_PT5016.vGdGUg==

```
