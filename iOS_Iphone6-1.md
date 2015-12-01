#### Test 522773652a05488_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/522773652a05488/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/61D4EE6E-28F7-4CBD-9867-D501C723B04F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/61D4EE6E-28F7-4CBD-9867-D501C723B04F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/522773652a05488/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/522773652a05488/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2ED7A22D-BBB2-475E-90D3-C920266BD277/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58616"
,(lldb)     command script import "/tmp/61D4EE6E-28F7-4CBD-9867-D501C723B04F/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-01 17:20:18.616 ThaliTest[2284:1980675] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7D76A5B6-FE44-4C8B-8853-90E25E00F5EC/Library/Cookies/Cookies.binarycookies
,2015-12-01 17:20:19.008 ThaliTest[2284:1980675] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-01 17:20:19.009 ThaliTest[2284:1980675] Multi-tasking -> Device: YES, App: YES
,2015-12-01 17:20:19.017 ThaliTest[2284:1980675] Unlimited access to network resources
,2015-12-01 17:20:19.023 ThaliTest[2284:1980675] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-01 17:20:22.955 ThaliTest[2284:1980675] Resetting plugins due to page load.
,2015-12-01 17:20:23.351 ThaliTest[2284:1980675] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/2ED7A22D-BBB2-475E-90D3-C920266BD277/ThaliTest.app/www/index.html
,2015-12-01 17:20:23.476 ThaliTest[2284:1980675] JXcore Cordova plugin initializing
2015-12-01 17:20:23.477 ThaliTest[2284:1980813] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone6-1_PT8196
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
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 63977
,2015-12-01 17:26:55.991 ThaliTest[2284:1980813] jxcore: startBroadcasting
,2015-12-01 17:26:56.002 ThaliTest[2284:1980813] server: starting Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:26:56.003 ThaliTest[2284:1980813] multipeer session: start timer: 0x19dabb30
2015-12-01 17:26:56.003 ThaliTest[2284:1980813] THEMultipeerSession initialized peer Apple-Iphone6-1_PT8196
2015-12-01 17:26:56.003 ThaliTest[2284:1980813] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-01T16:26:56.005Z SendDataTCPServer.js: TCP/IP server is bound to port: 63977
,2015-12-01 17:26:56.293 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01T16:26:56.296Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01T16:26:56.296Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01T16:26:56.296Z SendDataConnector.js: do connect now
2015-12-01 17:26:56.297 ThaliTest[2284:1980813] jxcore: connect Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:26:56.297 ThaliTest[2284:1980813] client session: connect
,2015-12-01 17:26:56.297 ThaliTest[2284:1980813] client session: stateChange:0->1 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:26:57.135 ThaliTest[2284:1980675] multipeer session: reset timer
2015-12-01 17:26:57.136 ThaliTest[2284:1980675] multipeer session: stop timer
2015-12-01 17:26:57.136 ThaliTest[2284:1980675] multipeer session: start timer: 0x19dabb30
2015-,12-01 17:26:57.137 ThaliTest[2284:1980675] server session: connect
2015-12-01 17:26:57.137 ThaliTest[2284:1980675] server session: stateChange:0->1 Apple-IpadAir2-1_PT7863
,2015-12-01 17:26:57.149 ThaliTest[2284:1980675] server: accepting invitation Apple-IpadAir2-1_PT7863
2015-12-01 17:26:57.153 ThaliTest[2284:1980675] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ip,adAir2-1_PT7863.GmxszQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-01 17:26:57.191 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6379.NUteEA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-01 17:26:57.724 ThaliTest[2284:1980675] multipeer session: reset timer
2015-12-01 17:26:57.724 ThaliTest[2284:1980675] multipeer session: stop timer
2015-12-01 17:26:57.724 ThaliTest[2284:1980675] multipeer session: start timer: 0x19dabb30
2015-,12-01 17:26:57.724 ThaliTest[2284:1980675] server session: connect
2015-12-01 17:26:57.724 ThaliTest[2284:1980675] server session: stateChange:0->1 Apple-Iphone5s-1_PT4380
,2015-12-01 17:26:57.727 ThaliTest[2284:1980675] server: accepting invitation Apple-Iphone5s-1_PT4380
,2015-12-01 17:26:58.897 ThaliTest[2284:1981386] client session: connected
2015-12-01 17:26:58.898 ThaliTest[2284:1981386] client session: stateChange:1->2 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:26:58.904 ThaliTest[2284:1981364] client session: fireConnectCallback: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:26:58.905 ThaliTest[2284:1981364] jxcore: connect: success
,2015-12-01T16:26:58.908Z SendDataConnector.js: CLIENT connected to 63980, error: null
,2015-12-01T16:26:58.908Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 17:26:58.912 ThaliTest[2284:1980675] client: relay established
2015-12-01 17:26:58.912 ThaliTest[2284:1980675] client: new accepted socket: 0x19dba980
,2015-12-01T16:26:58.927Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T16:26:59.254Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-01T16:26:59.267Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-01T16:26:59.278Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-01T16:26:59.303Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-01 17:26:59.593 ThaliTest[2284:1981386] server session: connected
2015-12-01 17:26:59.594 ThaliTest[2284:1981386] server session: stateChange:1->2 Apple-IpadAir2-1_PT7863
,2015-12-01 17:26:59.908 ThaliTest[2284:1981386] server session: connected
2015-12-01 17:26:59.909 ThaliTest[2284:1981386] server session: stateChange:1->2 Apple-Iphone5s-1_PT4380
,2015-12-01 17:26:59.915 ThaliTest[2284:1980675] server relay: connected (to port: 63977)
2015-12-01T16:26:59.918Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01 17:26:59.990 ThaliTest[2284:1980675] server relay: connected (to port: 63977)
,2015-12-01T16:27:00.005Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T16:27:00.023Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-01T16:27:00.037Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-01T16:27:00.050Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01 17:27:00.220 ThaliTest[2284:1981364] server session: not connected Apple-IpadAir2-1_PT7863
,2015-12-01T16:27:00.232Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-01T16:27:00.247Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01 17:27:00.263 ThaliTest[2284:1981361] server session: not connected Apple-Iphone5s-1_PT4380
,2015-12-01T16:27:09.304Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T16:27:09.304Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T16:27:09.306Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01T16:27:09.307Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-01T16:27:09.308Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 17:27:09.310 ThaliTest[2284:1980675] client: socket closed
2015-12-01 17:27:09.310 ThaliTest[2284:1980675] client relay: socket disconnected
2015-12-01 17:27:09.311 ThaliTest[2284:1980675] client relay: 0x19dba980 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19dacd30 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-01 17:27:09.311 ThaliTest[2284:1980675] client session: socket closed: Apple-Iphone5s-1_PT4380.ZyAdc,Q==
2015-12-01 17:27:09.312 ThaliTest[2284:1980675] client session: onLinkFailure: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:27:09.312 ThaliTest[2284:1980675] client session: disconnect
2015-12-01 17:27:09.313 ThaliTest[2284:1980675] client session,: stateChange:2->0 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:09.315 ThaliTest[2284:1980675] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:27:14.309Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:27:14.309Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:19.318 ThaliTest[2284:1980813] jxcore: disconnect
2015-12-01 17:27:19.319 ThaliTest[2284:1980813] jxcore: disconnect: fail
2015-12-01T16:27:19.319Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:27:19.320Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT4380.ZyAdcQ== with availability status: true
,2015-12-01T16:27:19.321Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:27:19.322Z SendDataConnector.js: do connect now
,2015-12-01 17:27:19.323 ThaliTest[2284:1980813] jxcore: connect Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:27:19.323 ThaliTest[2284:1980813] client session: connect
2015-12-01 17:27:19.324 ThaliTest[2284:1980813] client session: stateChange:0->1 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:22.163 ThaliTest[2284:1981410] client session: connected
2015-12-01 17:27:22.164 ThaliTest[2284:1981410] client session: stateChange:1->2 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:22.168 ThaliTest[2284:1981410] client session: fireConnectCallback: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:27:22.169 ThaliTest[2284:1981410] jxcore: connect: success
2015-12-01T16:27:22.171Z SendDataConnector.js: CLIENT connected to 63986, error: null
2015-12-01T16:27:22.172Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 17:27:22.176 ThaliTest[2284:1980675] client: relay established
2015-12-01 17:27:22.176 ThaliTest[2284:1980675] client: new accepted socket: 0x199f9430
,2015-12-01T16:27:22.187Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-01 17:27:27.726 ThaliTest[2284:1980675] multipeer session: restart
,2015-12-01 17:27:27.740 ThaliTest[2284:1980675] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:27:27.742 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:27:27.744 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:27:32.262Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T16:27:32.263Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T16:27:32.263Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T16:27:32.264Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-01T16:27:32.265Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 17:27:32.266 ThaliTest[2284:1980675] client: socket closed
2015-12-01 17:27:32.267 ThaliTest[2284:1980675] client relay: socket disconnected
2015-12-01 17:27:32.267 ThaliTest[2284:1980675] client relay: 0x199f9430 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19dc1020 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-01 17:27:32.268 ThaliTest[2284:1980675] client session: socket closed: Apple-Iphone5s-1_PT4380.ZyAdc,Q==
2015-12-01 17:27:32.268 ThaliTest[2284:1980675] client session: onLinkFailure: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:27:32.269 ThaliTest[2284:1980675] client session: disconnect
2015-12-01 17:27:32.269 ThaliTest[2284:1980675] client session,: stateChange:2->0 Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:27:32.271 ThaliTest[2284:1980675] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:27:37.273Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:27:37.274Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:42.283 ThaliTest[2284:1980813] jxcore: disconnect
2015-12-01 17:27:42.284 ThaliTest[2284:1980813] jxcore: disconnect: fail
2015-12-01T16:27:42.285Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4380.ZyAd,cQ==
2015-12-01T16:27:42.285Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT4380.ZyAdcQ== with availability status: true
2015-12-01T16:27:42.286Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:27:42.286Z SendDataConnector.js: do connect now
2015-12-01 17:27:42.286 ThaliTest[2284:1980813] jxcore: connect Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:42.287 ThaliTest[2284:1980813] client session: connect
,2015-12-01 17:27:42.288 ThaliTest[2284:1980813] client session: stateChange:0->1 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:44.971 ThaliTest[2284:1981410] client session: connected
,2015-12-01 17:27:44.973 ThaliTest[2284:1981410] client session: stateChange:1->2 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:44.976 ThaliTest[2284:1981410] client session: fireConnectCallback: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:44.977 ThaliTest[2284:1981410] jxcore: connect: success
,2015-12-01T16:27:44.980Z SendDataConnector.js: CLIENT connected to 63991, error: null
,2015-12-01T16:27:44.981Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 17:27:44.984 ThaliTest[2284:1980675] client: relay established
2015-12-01 17:27:44.984 ThaliTest[2284:1980675] client: new accepted socket: 0x19db8930
,2015-12-01T16:27:44.997Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-01T16:27:55.066Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T16:27:55.067Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T16:27:55.067Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T16:27:55.068Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-01T16:27:55.069Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 17:27:55.070 ThaliTest[2284:1980675] client: socket closed
2015-12-01 17:27:55.071 ThaliTest[2284:1980675] client relay: socket disconnected
2015-12-01 17:27:55.072 ThaliTest[2284:1980675] client relay: 0x19db8930 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19dba2e0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-01 17:27:55.072 ThaliTest[2284:1980675] client session: socket closed: Apple-Iphone5s-1_PT4380.ZyAdc,Q==
2015-12-01 17:27:55.073 ThaliTest[2284:1980675] client session: onLinkFailure: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:27:55.073 ThaliTest[2284:1980675] client session: disconnect
2015-12-01 17:27:55.073 ThaliTest[2284:1980675] client session,: stateChange:2->0 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:55.076 ThaliTest[2284:1980675] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:57.726 ThaliTest[2284:1980675] multipeer session: restart
,2015-12-01 17:27:57.748 ThaliTest[2284:1980675] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:27:57.749 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:27:57.750 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:28:00.078Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01T16:28:00.078Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:05.092 ThaliTest[2284:1980813] jxcore: disconnect
2015-12-01 17:28:05.093 ThaliTest[2284:1980813] jxcore: disconnect: fail
2015-12-01T16:28:05.093Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4380.ZyAd,cQ==
2015-12-01T16:28:05.094Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT4380.ZyAdcQ== with availability status: true
2015-12-01T16:28:05.094Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==,
,2015-12-01T16:28:05.094Z SendDataConnector.js: do connect now
,2015-12-01 17:28:05.095 ThaliTest[2284:1980813] jxcore: connect Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:05.096 ThaliTest[2284:1980813] client session: connect
2015-12-01 17:28:05.097 ThaliTest[2284:1980813] client session: stateChange:0->1 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:08.468 ThaliTest[2284:1981460] client session: connected
2015-12-01 17:28:08.469 ThaliTest[2284:1981460] client session: stateChange:1->2 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:08.476 ThaliTest[2284:1981410] client session: fireConnectCallback: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:28:08.476 ThaliTest[2284:1981410] jxcore: connect: success
2015-12-01T16:28:08.477Z SendDataConnector.js: CLIENT connected to 63996, error: null
2015-12-01T16:28:08.477Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 17:28:08.478 ThaliTest[2284:1980675] client: relay established
2015-12-01 17:28:08.479 ThaliTest[2284:1980675] client: new accepted socket: 0x199f34e0
,2015-12-01T16:28:08.491Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-01T16:28:18.567Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T16:28:18.568Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T16:28:18.568Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T16:28:18.569Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-12-01T16:28:18.570Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 17:28:18.577 ThaliTest[2284:1980675] client: socket closed
,2015-12-01 17:28:18.579 ThaliTest[2284:1980675] client relay: socket disconnected
,2015-12-01 17:28:18.580 ThaliTest[2284:1980675] client relay: 0x199f34e0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x156532b0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-1,2-01 17:28:18.581 ThaliTest[2284:1980675] client session: socket closed: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:28:18.582 ThaliTest[2284:1980675] client session: onLinkFailure: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:18.583 ThaliTest[2284:1980675] client session: disconnect
2015-12-01 17:28:18.584 ThaliTest[2284:1980675] client session: stateChange:2->0 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:18.586 ThaliTest[2284:1980675] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:28:23.573Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01T16:28:23.573Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:27.726 ThaliTest[2284:1980675] multipeer session: restart
,2015-12-01 17:28:27.742 ThaliTest[2284:1980675] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:28:27.743 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:28:27.744 ThaliTest[2284:1980675] clien,t: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:28.577 ThaliTest[2284:1980813] jxcore: disconnect
,2015-12-01 17:28:28.578 ThaliTest[2284:1980813] jxcore: disconnect: fail
2015-12-01T16:28:28.579Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:28:28.581Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT4380.ZyAdcQ== with availability status: true
,2015-12-01T16:28:28.581Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01T16:28:28.581Z SendDataConnector.js: do connect now
,2015-12-01 17:28:28.582 ThaliTest[2284:1980813] jxcore: connect Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:28:28.583 ThaliTest[2284:1980813] client session: connect
2015-12-01 17:28:28.584 ThaliTest[2284:1980813] client session: stateChange:0->1 Appl,e-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:31.365 ThaliTest[2284:1981538] client session: connected
2015-12-01 17:28:31.366 ThaliTest[2284:1981538] client session: stateChange:1->2 Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:28:31.369 ThaliTest[2284:1981538] client session: fi,reConnectCallback: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:28:31.370 ThaliTest[2284:1981538] jxcore: connect: success
2015-12-01T16:28:31.371Z SendDataConnector.js: CLIENT connected to 64001, error: null
2015-12-01T16:28:31.372Z SendDataConnector,.js: CLIENT starting client 
,2015-12-01 17:28:31.377 ThaliTest[2284:1980675] client: relay established
2015-12-01 17:28:31.378 ThaliTest[2284:1980675] client: new accepted socket: 0x19d31a20
,2015-12-01T16:28:31.390Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-01T16:28:41.429Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T16:28:41.430Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T16:28:41.431Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T16:28:41.434Z SendDataConnector.js: CLIENT Stop now
2015-12-01T16:28:41.434Z SendDataConnector.js: Stop data retrieving timer
2015-12-01T16:28:41.435Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 17:28:41.436 ThaliTest[2284:1980813] jxcore: disconnect
,2015-12-01 17:28:41.437 ThaliTest[2284:1980813] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:28:41.438 ThaliTest[2284:1980813] client session: disconnect
2015-12-01 17:28:41.439 ThaliTest[2284:1980813] client session,: stateChange:2->0 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:41.442 ThaliTest[2284:1980813] jxcore: disconnect: success
2015-12-01T16:28:41.443Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
---- round done--------
,device[2]: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01T16:28:41.447Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01T16:28:41.447Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01T16:28:41.448Z SendDataConnector.js: do connect now
,2015-12-01 17:28:41.450 ThaliTest[2284:1980813] jxcore: connect Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:28:41.451 ThaliTest[2284:1980813] client session: connect
2015-12-01 17:28:41.451 ThaliTest[2284:1980813] client session: stateChange:0->1 Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01T16:28:41.459Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 17:28:42.616 ThaliTest[2284:1980675] multipeer session: reset timer
2015-12-01 17:28:42.617 ThaliTest[2284:1980675] multipeer session: stop timer
2015-12-01 17:28:42.618 ThaliTest[2284:1980675] multipeer session: start timer: 0x19dabb30
2015-,12-01 17:28:42.618 ThaliTest[2284:1980675] server session: connect
2015-12-01 17:28:42.619 ThaliTest[2284:1980675] server session: stateChange:0->1 Apple-Iphone5-1_PT6379
,2015-12-01 17:28:42.629 ThaliTest[2284:1980675] server: accepting invitation Apple-Iphone5-1_PT6379
,2015-12-01 17:28:44.630 ThaliTest[2284:1981539] client session: connected
2015-12-01 17:28:44.631 ThaliTest[2284:1981539] client session: stateChange:1->2 Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:28:44.647 ThaliTest[2284:1981538] client session: fireConnectCallback: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:28:44.647 ThaliTest[2284:1981538] jxcore: connect: success
2015-12-01T16:28:44.648Z SendDataConnector.js: CLIENT connected, to 64004, error: null
2015-12-01T16:28:44.649Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 17:28:44.653 ThaliTest[2284:1980675] client: relay established
2015-12-01 17:28:44.654 ThaliTest[2284:1980675] client: new accepted socket: 0x199f1180
,2015-12-01T16:28:44.665Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T16:28:45.091Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-01 17:28:45.109 ThaliTest[2284:1981535] server session: connected
2015-12-01 17:28:45.110 ThaliTest[2284:1981535] server session: stateChange:1->2 Apple-Iphone5-1_PT6379
,2015-12-01 17:28:45.118 ThaliTest[2284:1980675] server relay: connected (to port: 63977)
,2015-12-01T16:28:45.129Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T16:28:45.531Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-01T16:28:45.532Z SendDataConnector.js: got all data for this round
,2015-12-01T16:28:45.534Z SendDataConnector.js: CLIENT Stop now
2015-12-01T16:28:45.534Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 17:28:45.535 ThaliTest[2284:1980813] jxcore: disconnect
2015-12-01 17:28:45.536 ThaliTest[2284:1980813] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:28:45.537 ThaliTest[2284:1980813] client session: discon,nect
2015-12-01 17:28:45.538 ThaliTest[2284:1980813] client session: stateChange:2->0 Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:28:45.540 ThaliTest[2284:1980813] jxcore: disconnect: success
,2015-12-01T16:28:45.544Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7863.GmxszQ==
---- round done--------
,device[3]: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01T16:28:45.547Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01T16:28:45.547Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6379.NUteEA==
20,15-12-01T16:28:45.548Z SendDataConnector.js: do connect now
,2015-12-01 17:28:45.548 ThaliTest[2284:1980813] jxcore: connect Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:28:45.550 ThaliTest[2284:1980813] client session: connect
2015-12-01 17:28:45.550 ThaliTest[2284:1980813] client session: stateChange:0->1 Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01T16:28:45.702Z SendDataTCPServer.js: TCP/IP server has received 21824 bytes of data
,2015-12-01T16:28:45.715Z SendDataTCPServer.js: TCP/IP server has received 64480 bytes of data
,2015-12-01T16:28:45.729Z SendDataTCPServer.js: TCP/IP server has received 67456 bytes of data
,2015-12-01T16:28:45.741Z SendDataTCPServer.js: TCP/IP server has received 77376 bytes of data
,2015-12-01T16:28:45.753Z SendDataTCPServer.js: TCP/IP server has received 80352 bytes of data
,2015-12-01T16:28:46.183Z SendDataTCPServer.js: TCP/IP server has received 89280 bytes of data
,2015-12-01T16:28:46.196Z SendDataTCPServer.js: TCP/IP server has received 97216 bytes of data
,2015-12-01T16:28:46.212Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01 17:28:46.237 ThaliTest[2284:1981535] server session: not connected Apple-Iphone5-1_PT6379
,2015-12-01 17:28:48.262 ThaliTest[2284:1981536] client session: connected
2015-12-01 17:28:48.262 ThaliTest[2284:1981536] client session: stateChange:1->2 Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:28:48.301 ThaliTest[2284:1981538] client session: fireConnectCallback: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:28:48.301 ThaliTest[2284:1981538] jxcore: connect: success
2015-12-01T16:28:48.302Z SendDataConnector.js: CLIENT connected to 64008, error: null
2015-12-01T16:28:48.303Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 17:28:48.306 ThaliTest[2284:1980675] client: relay established
2015-12-01 17:28:48.307 ThaliTest[2284:1980675] client: new accepted socket: 0x19ad4720
,2015-12-01T16:28:48.319Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T16:28:55.992Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-01T16:28:55.993Z SendDataConnector.js: got all data for this round
,2015-12-01T16:28:55.995Z SendDataConnector.js: CLIENT Stop now
2015-12-01T16:28:55.995Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01 17:28:55.996 ThaliTest[2284:1980813] jxcore: disconnect
,2015-12-01 17:28:55.997 ThaliTest[2284:1980813] client session: disconnectFromPeer: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:28:55.997 ThaliTest[2284:1980813] client session: disconnect
2015-12-01 17:28:55.999 ThaliTest[2284:1980813] client session:, stateChange:2->0 Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:28:56.002 ThaliTest[2284:1980813] jxcore: disconnect: success
2015-12-01T16:28:56.003Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6379.NUteEA==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT8196","time":120031,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","time":105136,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name":"Appl,e-IpadAir2-1_PT7863.GmxszQ==","time":4086,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT6379.NUteEA==","time":10447,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataR,eceived":100000}]}
,sendList : 100% : 10447 ms, 99% : 10447 ms, 95 : 10447 ms, 90% : 10447 ms.
,Result count 2, range 4086 ms to  10447 ms.
,sendList failed peers count : 1 [33.333333333333336 %]
,- Peer ID : Apple-Iphone5s-1_PT4380.ZyAdcQ==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-12-01T16:28:56.018Z SendDataConnector.js: CLIENT Stop now
,2015-12-01T16:28:56.018Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-01 17:29:12.619 ThaliTest[2284:1980675] multipeer session: restart
,2015-12-01 17:29:12.738 ThaliTest[2284:1980675] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:29:12.740 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:29:12.785 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:29:34.250 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:29:42.618 ThaliTest[2284:1980675] multipeer session: restart
,2015-12-01 17:29:42.635 ThaliTest[2284:1980675] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:29:42.637 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:29:43.159 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:30:04.130 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:30:12.615 ThaliTest[2284:1980675] multipeer session: restart
,2015-12-01 17:30:12.632 ThaliTest[2284:1980675] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:30:12.634 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:30:13.053 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:30:42.615 ThaliTest[2284:1980675] multipeer session: restart
,2015-12-01 17:30:42.631 ThaliTest[2284:1980675] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:30:42.634 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:30:43.053 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:31:03.352 ThaliTest[2284:1980675] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:31:03.353 ThaliTest[2284:1980675] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:31:04.402 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:31:12.615 ThaliTest[2284:1980675] multipeer session: restart
,2015-12-01 17:31:12.631 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:31:12.632 ThaliTest[2284:1980675] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:31:12.939 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:31:34.280 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:31:42.615 ThaliTest[2284:1980675] multipeer session: restart
,2015-12-01 17:31:42.632 ThaliTest[2284:1980675] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:31:42.633 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:31:42.822 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:32:04.186 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:32:12.615 ThaliTest[2284:1980675] multipeer session: restart
,2015-12-01 17:32:12.630 ThaliTest[2284:1980675] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:32:12.631 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:32:14.117 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:32:34.095 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:32:42.613 ThaliTest[2284:1980675] multipeer session: restart
,2015-12-01 17:32:42.630 ThaliTest[2284:1980675] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:32:42.631 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:32:46.095 ThaliTest[2284:1980675] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:33:12.613 ThaliTest[2284:1980675] multipeer session: restart
2015-12-01 17:33:12.618 ThaliTest[2284:1980675] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Fi,rst throw call stack:
(0x26e2efef 0x35798c8b 0x26d4aaa3 0x28e09d85 0x26932607 0x26931e81 0x268ab3d3 0x26df4faf 0x26df43bf 0x26df2a25 0x26d3f201 0x26d3f013 0x2e7ca201 0x2a50ba09 0x4c5e3 0x35d4aaaf)
libc++abi.dylib: terminating with uncaught exception of t,ype NSException
,Process 2284 stopped
* thread #1: tid = 0x1e3903, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x35e14df0 <+8>:  blo    0x35e14e08                ; <+32>
    0x35e14df4 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x35e14df8 <+16>: ldr    r12, [pc, r12]
    0x35e14dfc <+20>: b      0x35e14e04                ; <+28>
,* thread #1: tid = 0x1e3903, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
  * frame #0: 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x35e93cc6 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x35db0908 libsystem_c.dylib`abort + 76
    frame #3: 0x350a79c8 libc++abi.dylib`<redacted> + 88
    frame #4: 0x350c1670 libc++abi.dylib`<redacted> + 268
    frame #5: 0x35798f24 libobjc.A.dylib`<redacted> + 192
    frame #6: 0x350bede2 libc++abi.dylib`<redacted> + 78
    frame #7: 0x350be8ae libc++abi.dylib`__cxa_rethrow + 102
    frame #8: 0x35798dd2 libobjc.A.dylib`objc_exception_rethrow + 42
    frame #9: 0x26d3f29c CoreFoundation`CFRunLoopRunSpecific + 632
    frame #10: 0x26d3f012 CoreFoundation`CFRunLoopRunInMode + 106
    frame #11: 0x2e7ca200 GraphicsServices`GSEventRunModal + 136
    frame #12: 0x2a50ba08 UIKit`UIApplicationMain + 1440
    frame #13: 0x0004c5e2 ThaliTest`main + 50

```
