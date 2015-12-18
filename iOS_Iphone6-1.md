#### Test 539786633aa3ea0_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/539786633aa3ea0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/8127E593-4B7B-4B07-AA27-1BFF681C6F86/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/8127E593-4B7B-4B07-AA27-1BFF681C6F86/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/539786633aa3ea0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/539786633aa3ea0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/42134838-BA5B-40AD-B4A6-7951961109F4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60063"
,(lldb)     command script import "/tmp/8127E593-4B7B-4B07-AA27-1BFF681C6F86/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-18 14:26:34.457 ThaliTest[430:349908] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/44A1F200-2B87-4BBE-903F-27EE6FB8CC97/Library/Cookies/Cookies.binarycookies
,2015-12-18 14:26:34.872 ThaliTest[430:349908] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-18 14:26:34.874 ThaliTest[430:349908] Multi-tasking -> Device: YES, App: YES
,2015-12-18 14:26:34.885 ThaliTest[430:349908] Unlimited access to network resources
,2015-12-18 14:26:34.898 ThaliTest[430:349908] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-18 14:26:43.922 ThaliTest[430:349908] Resetting plugins due to page load.
,2015-12-18 14:26:47.648 ThaliTest[430:349908] Finished load of: file:///var/mobile/Containers/Bundle/Application/42134838-BA5B-40AD-B4A6-7951961109F4/ThaliTest.app/www/index.html
,2015-12-18 14:26:47.834 ThaliTest[430:349908] JXcore Cordova plugin initializing
,2015-12-18 14:26:47.835 ThaliTest[430:350106] JXcore instance initializing
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
,my name is : Apple-Iphone6-1_PT5907
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
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
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
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":20000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 52409
,2015-12-18 14:39:32.374 ThaliTest[430:350106] jxcore: startBroadcasting
,2015-12-18 14:39:32.394 ThaliTest[430:350106] server: starting Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:39:32.396 ThaliTest[430:350106] multipeer session: start timer: 0x176f0570
2015-12-18 14:39:32.396 ThaliTest[430:350106] THEMultipeerSession initialized peer Apple-Iphone6-1_PT5907
2015-12-18 14:39:32.397 ThaliTest[430:350106] jxcore: start,Broadcasting: success
StartBroadcasting started ok
2015-12-18T13:39:32.400Z SendDataTCPServer.js: TCP/IP server is bound to port: 52409
,2015-12-18 14:39:33.431 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4577.+7TbDw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18T13:39:33.438Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18T13:39:33.439Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18T13:39:33.440Z SendDataConnector.js: do connect now
,2015-12-18 14:39:33.441 ThaliTest[430:350106] jxcore: connect Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:39:33.442 ThaliTest[430:350106] client session: connect
2015-12-18 14:39:33.442 ThaliTest[430:350106] client session: stateChange:0->1 Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:39:33.694 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6006.TYpyOQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
2015-12-18 14:39:33.701 ThaliTest[430:349908] multipeer session: reset timer
2015-12-18 14:39:33.701 ThaliTest[430:349908] multipeer session: stop timer
2015-12-18 14:39:33.702 ThaliTest[430:349908] multipeer session: start timer: 0x176f0570
,2015-12-18 14:39:33.702 ThaliTest[430:349908] server session: connect
2015-12-18 14:39:33.705 ThaliTest[430:349908] server session: stateChange:0->1 Apple-IpadAir2-1_PT4577
2015-12-18 14:39:33.714 ThaliTest[430:349908] server: accepting invitation Apple-IpadAir2-1_PT4577
,2015-12-18 14:39:36.528 ThaliTest[430:351362] client session: connected
2015-12-18 14:39:36.529 ThaliTest[430:351362] client session: stateChange:1->2 Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:39:36.550 ThaliTest[430:351363] server session: connected
2015-12-18 14:39:36.550 ThaliTest[430:351363] server session: stateChange:1->2 Apple-IpadAir2-1_PT4577
,2015-12-18 14:39:36.577 ThaliTest[430:351362] client session: fireConnectCallback: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:39:36.578 ThaliTest[430:351362] jxcore: connect: success
2015-12-18T13:39:36.579Z SendDataConnector.js: CLIENT connected to 52412, error: null
,2015-12-18T13:39:36.580Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 14:39:36.584 ThaliTest[430:349908] client: relay established
2015-12-18 14:39:36.585 ThaliTest[430:349908] client: new accepted socket: 0x17631d20
,2015-12-18T13:39:36.604Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18 14:39:36.614 ThaliTest[430:349908] server relay: connected (to port: 52409)
,2015-12-18T13:39:36.915Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T13:39:36.928Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-18T13:39:36.956Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-18T13:39:36.970Z SendDataTCPServer.js: TCP/IP server has received 65274 bytes of data
,2015-12-18T13:39:36.984Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18T13:39:36.986Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T13:39:36.987Z SendDataConnector.js: got all data for this round
,2015-12-18T13:39:36.987Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T13:39:36.988Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 14:39:36.989 ThaliTest[430:350106] jxcore: disconnect
,2015-12-18 14:39:36.990 ThaliTest[430:350106] client session: disconnectFromPeer: Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:39:36.991 ThaliTest[430:350106] client session: disconnect
,2015-12-18 14:39:36.992 ThaliTest[430:350106] client session: stateChange:2->0 Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:39:36.997 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:39:37.000 ThaliTest[430:350106] jxcore: disconnect: success
2015-12-18T13:39:37.000Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT4577.+7TbDw==
---- round done--------
device[2]: Apple-Iphone5-1_PT6006.TY,pyOQ==
2015-12-18T13:39:37.001Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18T13:39:37.001Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18T13:39:37.001Z SendDataConnector.js: do connect now
2015-12-18 14:39:37.002 ThaliTest[430:350106] jxcore: connect Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:39:37.002 ThaliTest[430:350106] client session: connect
2015-12-18 14:39:37.002 ThaliTest[430:350106] client session: stateChange:0->1 Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:39:37.019 ThaliTest[430:351373] server session: not connected Apple-IpadAir2-1_PT4577
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4569.cwXFvg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-18 14:39:40.076 ThaliTest[430:351364] client session: connected
,2015-12-18 14:39:40.076 ThaliTest[430:351364] client session: stateChange:1->2 Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:39:40.142 ThaliTest[430:351372] client session: fireConnectCallback: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:39:40.143 ThaliTest[430:351372] jxcore: connect: success
2015-12-18T13:39:40.144Z SendDataConnector.js: CLIENT connected to 5,2416, error: null
2015-12-18T13:39:40.145Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 14:39:40.149 ThaliTest[430:349908] client: relay established
2015-12-18 14:39:40.149 ThaliTest[430:349908] client: new accepted socket: 0x176ecaa0
,2015-12-18T13:39:40.161Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T13:39:40.661Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-18T13:39:40.718Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T13:39:40.719Z SendDataConnector.js: got all data for this round
,2015-12-18T13:39:40.720Z SendDataConnector.js: CLIENT Stop now
2015-12-18T13:39:40.720Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 14:39:40.720 ThaliTest[430:350106] jxcore: disconnect
,2015-12-18 14:39:40.721 ThaliTest[430:350106] client session: disconnectFromPeer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:39:40.722 ThaliTest[430:350106] client session: disconnect
2015-12-18 14:39:40.722 ThaliTest[430:350106] client session: stateChange:2->0 Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:39:40.729 ThaliTest[430:350106] jxcore: disconnect: success
2015-12-18T13:39:40.730Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6006.TYpyOQ==
---- round done--------
device[3]: Apple-Iphone5s-1_PT4569.cw,XFvg==
2015-12-18T13:39:40.731Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18T13:39:40.732Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18T13:39:40.732Z SendDataConnector.js: do connect now
,2015-12-18 14:39:40.732 ThaliTest[430:350106] jxcore: connect Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:39:40.733 ThaliTest[430:350106] client session: connect
2015-12-18 14:39:40.733 ThaliTest[430:350106] client session: stateChange:0->1 Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:39:43.475 ThaliTest[430:351362] client session: connected
2015-12-18 14:39:43.475 ThaliTest[430:351362] client session: stateChange:1->2 Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:39:43.490 ThaliTest[430:351416] client session: fireConnectCallback: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:39:43.491 ThaliTest[430:351416] jxcore: connect: success
2015-12-18T13:39:43.492Z SendDataConnector.js: CLIENT connected to 52419, error: null
2015-12-18T13:39:43.492Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 14:39:43.497 ThaliTest[430:349908] client: relay established
2015-12-18 14:39:43.497 ThaliTest[430:349908] client: new accepted socket: 0x176f7920
,2015-12-18T13:39:43.509Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T13:39:43.821Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-18T13:39:43.847Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18 14:39:43.847 ThaliTest[430:349908] multipeer session: reset timer
2015-12-18 14:39:43.847 ThaliTest[430:349908] multipeer session: stop timer
2015-12-18T13:39:43.847Z SendDataConnector.js: got all data for this round
2015-12-18 14:39:43.847 ThaliTest[430:349908] multipeer session: start timer: 0x176f0570
2015-12-18 14:39:43.848 ThaliTest[430:349908] server session: connect
2015-12-18 14:39:43.848 ThaliTest[430:349908] server session: stateChange:0->1 Apple-Iphone5s-1_PT4569
,2015-12-18T13:39:43.848Z SendDataConnector.js: CLIENT Stop now
2015-12-18T13:39:43.850Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 14:39:43.852 ThaliTest[430:349908] server: accepting invitation Apple-Iphone5s-1_PT4569
2015-12-18 14:39:43.851 ThaliTest[430:350106] jxcore: disconnect
,2015-12-18 14:39:43.853 ThaliTest[430:350106] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:39:43.860 ThaliTest[430:350106] client session: disconnect
,2015-12-18 14:39:43.879 ThaliTest[430:350106] client session: stateChange:2->0 Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:39:43.968 ThaliTest[430:350106] jxcore: disconnect: success
2015-12-18T13:39:43.969Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4569.cwXFvg==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT5907","time":11613,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT4577.+7TbDw==","time":3548,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_,PT6006.TYpyOQ==","time":3718,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT4569.cwXFvg==","time":3115,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 3718 ms, 99% : 3718 ms, 95 : 3718 ms, 90% : 3718 ms.
,Result count 3, range 3115 ms to  3718 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-18T13:39:43.973Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T13:39:43.974Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 14:39:46.410 ThaliTest[430:351362] server session: connected
2015-12-18 14:39:46.414 ThaliTest[430:351362] server session: stateChange:1->2 Apple-Iphone5s-1_PT4569
,2015-12-18 14:39:46.432 ThaliTest[430:349908] server relay: connected (to port: 52409)
2015-12-18T13:39:46.435Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T13:39:46.887Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-18T13:39:46.904Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-18T13:39:46.921Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-18T13:39:46.948Z SendDataTCPServer.js: TCP/IP server has received 82794 bytes of data
,2015-12-18T13:39:46.963Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 14:39:47.019 ThaliTest[430:351416] server session: not connected Apple-Iphone5s-1_PT4569
,2015-12-18 14:40:13.849 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:40:13.893 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:40:14.217 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:40:33.266 ThaliTest[430:349908] multipeer session: reset timer
2015-12-18 14:40:33.266 ThaliTest[430:349908] multipeer session: stop timer
2015-12-18 14:40:33.267 ThaliTest[430:349908] multipeer session: start timer: 0x176f0570
2015-12-18 ,14:40:33.267 ThaliTest[430:349908] server session: connect
2015-12-18 14:40:33.267 ThaliTest[430:349908] server session: stateChange:0->1 Apple-Iphone5-1_PT6006
2015-12-18 14:40:33.275 ThaliTest[430:349908] server: accepting invitation Apple-Iphone5-1_PT,6006
,2015-12-18 14:40:35.913 ThaliTest[430:351569] server session: connected
2015-12-18 14:40:35.913 ThaliTest[430:351569] server session: stateChange:1->2 Apple-Iphone5-1_PT6006
,2015-12-18 14:40:35.951 ThaliTest[430:349908] server relay: connected (to port: 52409)
2015-12-18T13:40:35.952Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T13:40:36.705Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-18T13:40:36.720Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 14:40:37.253 ThaliTest[430:351579] server session: not connected Apple-Iphone5-1_PT6006
,2015-12-18 14:41:03.268 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:41:03.316 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:41:03.317 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:41:03.317 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:41:33.268 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:41:33.315 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:41:33.316 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:41:33.317 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:42:03.268 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:42:33.268 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:42:33.305 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:42:33.305 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:42:33.308 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:43:03.268 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:43:03.310 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:43:03.310 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:43:03.311 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:43:33.268 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:43:33.309 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:43:33.310 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:43:33.311 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:44:03.268 ThaliTest[430:349908] multipeer session: restart
,appEnteredForeground wasn't registered
,2015-12-18 14:44:33.268 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:44:33.307 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:44:33.309 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:44:33.310 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,appEnteringBackground wasn't registered
,2015-12-18 14:45:03.268 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:45:03.313 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:45:03.313 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:45:03.313 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:45:33.268 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:45:33.310 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:45:33.311 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:45:33.313 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:46:03.268 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:46:33.268 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:46:33.312 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:46:33.312 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:46:33.313 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:47:03.268 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:47:03.311 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:47:03.312 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:47:03.312 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:47:33.268 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:47:33.311 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:47:33.311 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:47:33.312 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:48:03.268 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:48:03.310 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:48:03.311 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:48:03.312 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:48:33.268 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:48:33.312 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:48:33.312 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:48:33.312 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:49:03.268 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:49:03.307 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:49:03.307 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:49:03.309 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:49:33.268 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:49:33.307 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:49:33.307 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:49:33.308 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:50:03.218 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:50:03.255 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:50:03.260 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:50:03.261 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:50:33.217 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:51:03.217 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:51:03.253 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:51:03.257 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:51:03.257 ThaliTest[430:349908] client: fo,und peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:51:33.218 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:51:33.258 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:51:33.260 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:51:33.261 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:52:03.218 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:52:03.254 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:52:03.257 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:52:03.259 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:52:33.218 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:52:33.256 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:52:33.256 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:52:33.259 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:53:03.218 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:53:03.257 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:53:03.257 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:53:03.257 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:53:33.218 ThaliTest[430:349908] multipeer session: restart
,2015-12-18 14:53:33.256 ThaliTest[430:349908] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:53:33.258 ThaliTest[430:349908] client: found peer: Apple-Iphone5s-1_PT4569.cwXFvg==
2015-12-18 14:53:33.258 ThaliTest[430:349908] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==

```
