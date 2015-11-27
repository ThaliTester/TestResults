#### Test 51986340bb0815b_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51986340bb0815b/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/FF51CFAF-9A93-42CE-88C7-352D35E7CCC6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/FF51CFAF-9A93-42CE-88C7-352D35E7CCC6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51986340bb0815b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51986340bb0815b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E9D63A16-40D2-4D0D-BF49-DC1E20303732/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56922"
,(lldb)     command script import "/tmp/FF51CFAF-9A93-42CE-88C7-352D35E7CCC6/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-27 13:08:53.130 ThaliTest[1475:2037000] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/66003ACD-566A-469A-84F9-9215DDE8AB66/Library/Cookies/Cookies.binarycookies
,2015-11-27 13:08:53.406 ThaliTest[1475:2037000] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-27 13:08:53.407 ThaliTest[1475:2037000] Multi-tasking -> Device: YES, App: YES
,2015-11-27 13:08:53.412 ThaliTest[1475:2037000] Unlimited access to network resources
,2015-11-27 13:08:53.419 ThaliTest[1475:2037000] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-27 13:08:57.656 ThaliTest[1475:2037000] Resetting plugins due to page load.
,2015-11-27 13:08:58.942 ThaliTest[1475:2037000] Finished load of: file:///var/mobile/Containers/Bundle/Application/E9D63A16-40D2-4D0D-BF49-DC1E20303732/ThaliTest.app/www/index.html
,2015-11-27 13:08:59.091 ThaliTest[1475:2037000] JXcore Cordova plugin initializing
,2015-11-27 13:08:59.092 ThaliTest[1475:2037196] JXcore instance initializing
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
,my name is : Apple-IpadAir2-1_PT3767
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
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 62588
,2015-11-27 13:16:20.854 ThaliTest[1475:2037196] jxcore: startBroadcasting
,2015-11-27 13:16:20.862 ThaliTest[1475:2037196] server: starting Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:16:20.862 ThaliTest[1475:2037196] multipeer session: start timer: 0x16dcdaa0
,2015-11-27 13:16:20.862 ThaliTest[1475:2037196] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT3767
2015-11-27 13:16:20.863 ThaliTest[1475:2037196] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-27T12:16:20.864Z SendDataTCPServer.js: TCP/IP server is bound to port: 62588
,2015-11-27 13:16:21.478 ThaliTest[1475:2037000] client: found peer: Apple-Iphone5s-1_PT8509.17j4Hw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8509.17j4Hw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27T12:16:21.480Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27T12:16:21.481Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27T12:16:21.481Z SendDataConnector.js: do connect now
2015-11-27 13:16:21.481 ThaliTest[1475:2037196] jxcore: connect Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:16:21.482 ThaliTest[1475:2037196] client session: connect
2015-11-27 13:16:21.482 ThaliTest[1475:2037196] client session: stateChange:0->1 Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:16:21.572 ThaliTest[1475:2037000] client: found peer: Apple-Iphone6-1_PT6911.ZjHo2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6911.ZjHo2g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-27 13:16:21.824 ThaliTest[1475:2037000] client: found peer: Apple-Iphone5-1_PT1479.RH8WAQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1479.RH8WAQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-27 13:16:24.224 ThaliTest[1475:2037923] client session: connected
2015-11-27 13:16:24.225 ThaliTest[1475:2037923] client session: stateChange:1->2 Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:16:24.244 ThaliTest[1475:2037925] client session: fireConnectCallback: Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27 13:16:24.244 ThaliTest[1475:2037925] jxcore: connect: success
,2015-11-27T12:16:24.245Z SendDataConnector.js: CLIENT connected to 62591, error: null
,2015-11-27T12:16:24.245Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:16:24.247 ThaliTest[1475:2037000] client: relay established
2015-11-27 13:16:24.247 ThaliTest[1475:2037000] client: new accepted socket: 0x14dcd660
,2015-11-27T12:16:24.260Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-27T12:16:24.735Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-27T12:16:24.735Z SendDataConnector.js: got all data for this round
,2015-11-27T12:16:24.736Z SendDataConnector.js: CLIENT Stop now
,2015-11-27T12:16:24.737Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27 13:16:24.738 ThaliTest[1475:2037196] jxcore: disconnect
2015-11-27 13:16:24.739 ThaliTest[1475:2037196] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27 13:16:24.739 ThaliTest[1475:2037196] client session: disconnect
2015-11-27 13:16:24.739 ThaliTest[1475:2037196] client session: stateChange:2->0 Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:16:24.745 ThaliTest[1475:2037196] jxcore: disconnect: success
,2015-11-27T12:16:24.746Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8509.17j4Hw==
,---- round done--------
device[2]: Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27T12:16:24.747Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27T12:16:24.747Z SendDataConnector.js: doConnect called with peer Apple-Ipho,ne6-1_PT6911.ZjHo2g==
2015-11-27T12:16:24.747Z SendDataConnector.js: do connect now
2015-11-27 13:16:24.748 ThaliTest[1475:2037196] jxcore: connect Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27 13:16:24.748 ThaliTest[1475:2037196] client session: connect
2015-11-27 13:16:24.748 ThaliTest[1475:2037196] client session: stateChange:0->1 Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:16:27.761 ThaliTest[1475:2037936] client session: connected
2015-11-27 13:16:27.761 ThaliTest[1475:2037936] client session: stateChange:1->2 Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:16:27.774 ThaliTest[1475:2037936] client session: fireConnectCallback: Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27 13:16:27.774 ThaliTest[1475:2037936] jxcore: connect: success
,2015-11-27T12:16:27.775Z SendDataConnector.js: CLIENT connected to 62595, error: null
2015-11-27T12:16:27.775Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:16:27.776 ThaliTest[1475:2037000] client: relay established
2015-11-27 13:16:27.776 ThaliTest[1475:2037000] client: new accepted socket: 0x16fb27f0
,2015-11-27T12:16:27.789Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-27T12:16:28.830Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-27T12:16:28.830Z SendDataConnector.js: got all data for this round
,2015-11-27T12:16:28.831Z SendDataConnector.js: CLIENT Stop now
2015-11-27T12:16:28.831Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27 13:16:28.832 ThaliTest[1475:2037196] jxcore: disconnect
2015-11-27 13:16:28.832 ThaliTest[1475:2037196] client session: disconnectFromPeer: Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27 13:16:28.832 ThaliTest[1475:2037196] client session: disconnect
2015-11-27 13:16:28.832 ThaliTest[1475:2037196] client session: stateChange:2->0 Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:16:28.838 ThaliTest[1475:2037196] jxcore: disconnect: success
2015-11-27T12:16:28.839Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6911.ZjHo2g==
---- round done--------
,device[3]: Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27T12:16:28.842Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27T12:16:28.843Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27T12:16:28.843Z SendDataConnector.js: do connect now
2015-11-27 13:16:28.843 ThaliTest[1475:2037196] jxcore: connect Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:16:28.843 ThaliTest[1475:2037196] client session: connect
,2015-11-27 13:16:28.844 ThaliTest[1475:2037196] client session: stateChange:0->1 Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:16:28.969 ThaliTest[1475:2037000] multipeer session: reset timer
2015-11-27 13:16:28.970 ThaliTest[1475:2037000] multipeer session: stop timer
2015-11-27 13:16:28.970 ThaliTest[1475:2037000] multipeer session: start timer: 0x16dcdaa0
2015-11-27 13:16:28.970 ThaliTest[1475:2037000] server session: connect
2015-11-27 13:16:28.970 ThaliTest[1475:2037000] server session: stateChange:0->1 Apple-Iphone6-1_PT6911
2015-11-27 13:16:28.974 ThaliTest[1475:2037000] server: accepting invitation Apple-Iphone6-1_PT6911
,2015-11-27 13:16:31.456 ThaliTest[1475:2037935] client session: connected
2015-11-27 13:16:31.456 ThaliTest[1475:2037935] client session: stateChange:1->2 Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:16:31.512 ThaliTest[1475:2037980] client session: fireConnectCallback: Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:16:31.512 ThaliTest[1475:2037980] jxcore: connect: success
2015-11-27T12:16:31.512Z SendDataConnector.js: CLIENT connected to 62598, error: null
2015-11-27T12:16:31.513Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:16:31.514 ThaliTest[1475:2037000] client: relay established
2015-11-27 13:16:31.514 ThaliTest[1475:2037000] client: new accepted socket: 0x14d105d0
,2015-11-27T12:16:31.527Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-27 13:16:31.581 ThaliTest[1475:2037980] server session: connected
2015-11-27 13:16:31.581 ThaliTest[1475:2037980] server session: stateChange:1->2 Apple-Iphone6-1_PT6911
,2015-11-27 13:16:31.586 ThaliTest[1475:2037000] server relay: connected (to port: 62588)
,2015-11-27T12:16:31.719Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:16:31.856Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-11-27T12:16:31.870Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-11-27T12:16:31.871Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-27T12:16:31.920Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-11-27T12:16:31.934Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-27T12:16:32.090Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-27T12:16:32.385Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-27T12:16:32.385Z SendDataConnector.js: got all data for this round
,2015-11-27T12:16:32.386Z SendDataConnector.js: CLIENT Stop now
2015-11-27T12:16:32.387Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27 13:16:32.387 ThaliTest[1475:2037196] jxcore: disconnect
2015-11-27 13:16:32.387 ThaliTest[1475:2037196] client session: disconnectFromPeer: Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:16:32.387 ThaliTest[1475:2037196] client session: disconnect
2015-11-27 13:16:32.388 ThaliTest[1475:2037196] client session: stateChange:2->0 Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:16:32.392 ThaliTest[1475:2037196] jxcore: disconnect: success
2015-11-27T12:16:32.392Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT1479.RH8WAQ==
---- round done--------
weAreDoneNow , resultArray.length: 3
done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT3767","time":11543,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT8509.17j4Hw==","time":3256,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1,_PT6911.ZjHo2g==","time":4084,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT1479.RH8WAQ==","time":3543,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":1000,00}]}
sendList : 100% : 4084 ms, 99% : 4084 ms, 95 : 4084 ms, 90% : 4084 ms.
Result count 3, range 3256 ms to  4084 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-11-27T12:16:32.397Z SendDataConnector.js: CLIENT Stop now
2015-11-27T12:16:32.397Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27 13:16:42.326 ThaliTest[1475:2037925] server session: not connected Apple-Iphone6-1_PT6911
,2015-11-27 13:16:53.855 ThaliTest[1475:2037000] multipeer session: reset timer
2015-11-27 13:16:53.855 ThaliTest[1475:2037000] multipeer session: stop timer
2015-11-27 13:16:53.855 ThaliTest[1475:2037000] multipeer session: start timer: 0x16dcdaa0
2015-,11-27 13:16:53.855 ThaliTest[1475:2037000] server: disconnecting to refresh session (Apple-Iphone6-1_PT6911)
2015-11-27 13:16:53.855 ThaliTest[1475:2037000] server session: disconnect
2015-11-27 13:16:53.855 ThaliTest[1475:2037000] server session: stateChange:2->0 Apple-Iphone6-1_PT6911
,2015-11-27 13:16:53.857 ThaliTest[1475:2037000] server session: connect
2015-11-27 13:16:53.857 ThaliTest[1475:2037000] server session: stateChange:0->1 Apple-Iphone6-1_PT6911
,2015-11-27T12:16:53.859Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-27 13:16:53.861 ThaliTest[1475:2037000] server: accepting invitation Apple-Iphone6-1_PT6911
,2015-11-27 13:16:56.217 ThaliTest[1475:2038033] server session: connected
2015-11-27 13:16:56.217 ThaliTest[1475:2038033] server session: stateChange:1->2 Apple-Iphone6-1_PT6911
,2015-11-27 13:16:56.218 ThaliTest[1475:2037000] server relay: connected (to port: 62588)
,2015-11-27T12:16:56.228Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:16:56.485Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-27 13:17:06.436 ThaliTest[1475:2038034] server session: not connected Apple-Iphone6-1_PT6911
,2015-11-27 13:17:16.984 ThaliTest[1475:2037000] multipeer session: reset timer
2015-11-27 13:17:16.984 ThaliTest[1475:2037000] multipeer session: stop timer
,2015-11-27 13:17:16.984 ThaliTest[1475:2037000] multipeer session: start timer: 0x16dcdaa0
,2015-11-27 13:17:16.984 ThaliTest[1475:2037000] server: disconnecting to refresh session (Apple-Iphone6-1_PT6911)
2015-11-27 13:17:16.985 ThaliTest[1475:2037000] server session: disconnect
,2015-11-27 13:17:16.985 ThaliTest[1475:2037000] server session: stateChange:2->0 Apple-Iphone6-1_PT6911
,2015-11-27 13:17:16.986 ThaliTest[1475:2037000] server session: connect
2015-11-27 13:17:16.986 ThaliTest[1475:2037000] server session: stateChange:0->1 Apple-Iphone6-1_PT6911
,2015-11-27T12:17:16.989Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-27 13:17:16.991 ThaliTest[1475:2037000] server: accepting invitation Apple-Iphone6-1_PT6911
,2015-11-27 13:17:19.350 ThaliTest[1475:2038114] server session: connected
2015-11-27 13:17:19.350 ThaliTest[1475:2038114] server session: stateChange:1->2 Apple-Iphone6-1_PT6911
,2015-11-27 13:17:19.352 ThaliTest[1475:2037000] server relay: connected (to port: 62588)
,2015-11-27T12:17:19.354Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:17:19.479Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-27 13:17:29.501 ThaliTest[1475:2038110] server session: not connected Apple-Iphone6-1_PT6911
,2015-11-27 13:17:31.285 ThaliTest[1475:2037000] client: lost peer: Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27 13:17:31.285 ThaliTest[1475:2037000] client session: onPeerLost: Apple-Iphone5s-1_PT8509.17j4Hw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8509.17j4Hw==","peerName":"(null)","peerAvailable":false}]
,2015-11-27 13:17:34.345 ThaliTest[1475:2037000] client: found peer: Apple-Iphone5s-1_PT8509.17j4Hw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8509.17j4Hw==","peerName":"(null)","peerAvailable":true}]
,2015-11-27 13:17:40.523 ThaliTest[1475:2037000] multipeer session: reset timer
2015-11-27 13:17:40.523 ThaliTest[1475:2037000] multipeer session: stop timer
2015-11-27 13:17:40.524 ThaliTest[1475:2037000] multipeer session: start timer: 0x16dcdaa0
2015-,11-27 13:17:40.524 ThaliTest[1475:2037000] server: disconnecting to refresh session (Apple-Iphone6-1_PT6911)
2015-11-27 13:17:40.524 ThaliTest[1475:2037000] server session: disconnect
2015-11-27 13:17:40.524 ThaliTest[1475:2037000] server session: stateChange:2->0 Apple-Iphone6-1_PT6911
,2015-11-27 13:17:40.526 ThaliTest[1475:2037000] server session: connect
2015-11-27 13:17:40.526 ThaliTest[1475:2037000] server session: stateChange:0->1 Apple-Iphone6-1_PT6911
,2015-11-27 13:17:40.529 ThaliTest[1475:2037000] server: accepting invitation Apple-Iphone6-1_PT6911
,2015-11-27T12:17:40.535Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-27 13:17:43.264 ThaliTest[1475:2038163] server session: connected
2015-11-27 13:17:43.264 ThaliTest[1475:2038163] server session: stateChange:1->2 Apple-Iphone6-1_PT6911
,2015-11-27 13:17:43.267 ThaliTest[1475:2037000] server relay: connected (to port: 62588)
,2015-11-27T12:17:43.270Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:17:43.583Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-27 13:17:53.612 ThaliTest[1475:2038110] server session: not connected Apple-Iphone6-1_PT6911
,2015-11-27 13:18:02.053 ThaliTest[1475:2037000] client: lost peer: Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27 13:18:02.053 ThaliTest[1475:2037000] client session: onPeerLost: Apple-Iphone5s-1_PT8509.17j4Hw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8509.17j4Hw==","peerName":"(null)","peerAvailable":false}]
,2015-11-27 13:18:03.239 ThaliTest[1475:2037000] client: found peer: Apple-Iphone5s-1_PT8509.17j4Hw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8509.17j4Hw==","peerName":"(null)","peerAvailable":true}]
,2015-11-27 13:18:03.591 ThaliTest[1475:2037000] multipeer session: reset timer
,2015-11-27 13:18:03.592 ThaliTest[1475:2037000] multipeer session: stop timer
,2015-11-27 13:18:03.592 ThaliTest[1475:2037000] multipeer session: start timer: 0x16dcdaa0
2015-11-27 13:18:03.592 ThaliTest[1475:2037000] server: disconnecting to refresh session (Apple-Iphone6-1_PT6911)
2015-11-27 13:18:03.592 ThaliTest[1475:2037000] s,erver session: disconnect
,2015-11-27 13:18:03.592 ThaliTest[1475:2037000] server session: stateChange:2->0 Apple-Iphone6-1_PT6911
,2015-11-27T12:18:03.600Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-27 13:18:03.646 ThaliTest[1475:2037000] server session: connect
2015-11-27 13:18:03.646 ThaliTest[1475:2037000] server session: stateChange:0->1 Apple-Iphone6-1_PT6911
,2015-11-27 13:18:03.649 ThaliTest[1475:2037000] server: accepting invitation Apple-Iphone6-1_PT6911
,2015-11-27 13:18:06.261 ThaliTest[1475:2038210] server session: connected
,2015-11-27 13:18:06.262 ThaliTest[1475:2038210] server session: stateChange:1->2 Apple-Iphone6-1_PT6911
,2015-11-27 13:18:06.264 ThaliTest[1475:2037000] server relay: connected (to port: 62588)
,2015-11-27T12:18:06.266Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:18:06.375Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-27 13:18:08.890 ThaliTest[1475:2037000] multipeer session: reset timer
,2015-11-27 13:18:08.891 ThaliTest[1475:2037000] multipeer session: stop timer
2015-11-27 13:18:08.891 ThaliTest[1475:2037000] multipeer session: start timer: 0x16dcdaa0
2015-11-27 13:18:08.891 ThaliTest[1475:2037000] server session: connect
2015-11-27 13:18:08.891 ThaliTest[1475:2037000] server session: stateChange:0->1 Apple-Iphone5s-1_PT8509
,2015-11-27 13:18:08.893 ThaliTest[1475:2037000] server: accepting invitation Apple-Iphone5s-1_PT8509
,2015-11-27 13:18:11.450 ThaliTest[1475:2038225] server session: connected
2015-11-27 13:18:11.451 ThaliTest[1475:2038225] server session: stateChange:1->2 Apple-Iphone5s-1_PT8509
,2015-11-27 13:18:11.459 ThaliTest[1475:2037000] server relay: connected (to port: 62588)
,2015-11-27T12:18:11.467Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:18:11.732Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-11-27T12:18:11.748Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-27 13:18:11.960 ThaliTest[1475:2038209] server session: not connected Apple-Iphone5s-1_PT8509
,2015-11-27 13:18:16.675 ThaliTest[1475:2038223] server session: not connected Apple-Iphone6-1_PT6911
,2015-11-27 13:18:32.586 ThaliTest[1475:2037000] client: lost peer: Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27 13:18:32.586 ThaliTest[1475:2037000] client session: onPeerLost: Apple-Iphone6-1_PT6911.ZjHo2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6911.ZjHo2g==","peerName":"(null)","peerAvailable":false}]
,2015-11-27 13:18:38.892 ThaliTest[1475:2037000] multipeer session: restart
,2015-11-27 13:18:38.903 ThaliTest[1475:2037000] client: found peer: Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:18:38.904 ThaliTest[1475:2037000] client: found peer: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:18:40.411 ThaliTest[1475:2037000] client: found peer: Apple-Iphone6-1_PT6911.ZjHo2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6911.ZjHo2g==","peerName":"(null)","peerAvailable":true}]
,2015-11-27 13:19:08.892 ThaliTest[1475:2037000] multipeer session: restart
,2015-11-27 13:19:08.903 ThaliTest[1475:2037000] client: found peer: Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:19:08.903 ThaliTest[1475:2037000] client: found peer: Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27 13:19:08.903 ThaliTest[1475:2037000] client: found peer: Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:19:32.734 ThaliTest[1475:2037000] client: lost peer: Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27 13:19:32.734 ThaliTest[1475:2037000] client session: onPeerLost: Apple-Iphone6-1_PT6911.ZjHo2g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6911.ZjHo2g==","peerName":"(null)","peerAvailable":false}]
,2015-11-27 13:19:37.553 ThaliTest[1475:2037000] client: found peer: Apple-Iphone6-1_PT6911.ZjHo2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6911.ZjHo2g==","peerName":"(null)","peerAvailable":true}]
,2015-11-27 13:19:38.892 ThaliTest[1475:2037000] multipeer session: restart
,2015-11-27 13:19:38.903 ThaliTest[1475:2037000] client: found peer: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:19:39.042 ThaliTest[1475:2037000] client: found peer: Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:19:39.656 ThaliTest[1475:2037000] client: found peer: Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:19:53.170 ThaliTest[1475:2037000] multipeer session: reset timer
2015-11-27 13:19:53.171 ThaliTest[1475:2037000] multipeer session: stop timer
2015-11-27 13:19:53.171 ThaliTest[1475:2037000] multipeer session: start timer: 0x16dcdaa0
2015-11-27 13:19:53.171 ThaliTest[1475:2037000] server session: connect
2015-11-27 13:19:53.171 ThaliTest[1475:2037000] server session: stateChange:0->1 Apple-Iphone5-1_PT1479
,2015-11-27 13:19:53.174 ThaliTest[1475:2037000] server: accepting invitation Apple-Iphone5-1_PT1479
,2015-11-27 13:19:55.814 ThaliTest[1475:2038495] server session: connected
2015-11-27 13:19:55.814 ThaliTest[1475:2038495] server session: stateChange:1->2 Apple-Iphone5-1_PT1479
,2015-11-27 13:19:55.822 ThaliTest[1475:2037000] server relay: connected (to port: 62588)
,2015-11-27T12:19:55.824Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:19:56.338Z SendDataTCPServer.js: TCP/IP server has received 3968 bytes of data
,2015-11-27T12:19:56.351Z SendDataTCPServer.js: TCP/IP server has received 23808 bytes of data
,2015-11-27 13:19:56.371 ThaliTest[1475:2037000] client: lost peer: Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27 13:19:56.371 ThaliTest[1475:2037000] client session: onPeerLost: Apple-Iphone6-1_PT6911.ZjHo2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6911.ZjHo2g==","peerName":"(null)","peerAvailable":false}]
,2015-11-27T12:19:56.480Z SendDataTCPServer.js: TCP/IP server has received 57536 bytes of data
,2015-11-27T12:19:56.800Z SendDataTCPServer.js: TCP/IP server has received 79360 bytes of data
,2015-11-27T12:19:56.814Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-27 13:19:56.875 ThaliTest[1475:2038495] server session: not connected Apple-Iphone5-1_PT1479
,DBG, CoordinatorConnector command called
command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
,testSendData stopped
,2015-11-27 13:19:57.233 ThaliTest[1475:2037196] jxcore: stopBroadcasting
2015-11-27 13:19:57.233 ThaliTest[1475:2037196] THEMultipeerSession stopping peer
2015-11-27 13:19:57.233 ThaliTest[1475:2037196] multipeer session: stop timer
2015-11-27 13:19:57.234 ThaliTest[1475:2037196] server session: disconnect
2015-11-27 13:19:57.234 ThaliTest[1475:2037196] server session: stateChange:2->0 Apple-Iphone6-1_PT6911
,2015-11-27 13:19:57.239 ThaliTest[1475:2037196] server session: disconnect
2015-11-27 13:19:57.240 ThaliTest[1475:2037196] server session: stateChange:2->0 Apple-Iphone5s-1_PT8509
,2015-11-27 13:19:57.244 ThaliTest[1475:2037196] server session: disconnect
2015-11-27 13:19:57.244 ThaliTest[1475:2037196] server session: stateChange:2->0 Apple-Iphone5-1_PT1479
,2015-11-27 13:19:57.247 ThaliTest[1475:2037196] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-11-27T12:19:57.262Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-27T12:19:57.262Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-27T12:19:57.263Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-27T12:19:57.263Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT8509.17j4Hw==\",\"time\":3256,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone5-1_PT1479.RH8WAQ==\",\"time\":3543,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-Iphone6-1_PT6911.ZjHo2g==\",\"time\":4084,\"result\":\"OK\",\"connections\":1,,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !

```
