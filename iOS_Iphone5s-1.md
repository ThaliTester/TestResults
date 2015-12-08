#### Test 52971095ef317fc_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52971095ef317fc/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/47C259A9-34D0-4333-8DDE-2D642E395E9B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/47C259A9-34D0-4333-8DDE-2D642E395E9B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52971095ef317fc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52971095ef317fc/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AE7156D9-D4B0-484E-980D-48F6DE7284A7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51182"
,(lldb)     command script import "/tmp/47C259A9-34D0-4333-8DDE-2D642E395E9B/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-08 17:07:37.057 ThaliTest[492:297357] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E3C630B1-1AEE-4E34-9986-8DD22BB5A7BE/Library/Cookies/Cookies.binarycookies
,2015-12-08 17:07:37.451 ThaliTest[492:297357] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-08 17:07:37.452 ThaliTest[492:297357] Multi-tasking -> Device: YES, App: YES
,2015-12-08 17:07:37.462 ThaliTest[492:297357] Unlimited access to network resources
,2015-12-08 17:07:37.474 ThaliTest[492:297357] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-08 17:07:46.999 ThaliTest[492:297357] Resetting plugins due to page load.
,2015-12-08 17:07:50.971 ThaliTest[492:297357] Finished load of: file:///var/mobile/Containers/Bundle/Application/AE7156D9-D4B0-484E-980D-48F6DE7284A7/ThaliTest.app/www/index.html
,2015-12-08 17:07:51.200 ThaliTest[492:297357] JXcore Cordova plugin initializing
,2015-12-08 17:07:51.202 ThaliTest[492:297568] JXcore instance initializing
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
,my name is : Apple-Iphone5s-1_PT7186
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 51825
,2015-12-08 17:14:45.218 ThaliTest[492:297568] jxcore: startBroadcasting
,2015-12-08 17:14:45.235 ThaliTest[492:297568] server: starting Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:14:45.237 ThaliTest[492:297568] multipeer session: start timer: 0x15f52470
2015-12-08 17:14:45.238 ThaliTest[492:297568] THEMultipeerSession ini,tialized peer Apple-Iphone5s-1_PT7186
2015-12-08 17:14:45.239 ThaliTest[492:297568] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-08T16:14:45.243Z SendDataTCPServer.js: TCP/IP server is bound to port: 51825
,2015-12-08 17:14:45.809 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7651.u5AQgA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-08 17:14:45.818 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
device[1]: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08T16:14:45.820Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08T16:14:45.821Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08T16:14:45.830Z SendDataConnector.js: do connect now
,2015-12-08 17:14:45.832 ThaliTest[492:297568] jxcore: connect Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08 17:14:45.834 ThaliTest[492:297568] client session: connect
,2015-12-08 17:14:45.838 ThaliTest[492:297568] client session: stateChange:0->1 Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08 17:14:45.858 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8010.swwphA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4957.VBxUsw==","peerName":"(null)",,"peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-08 17:14:50.101 ThaliTest[492:298418] client session: connected
2015-12-08 17:14:50.101 ThaliTest[492:298418] client session: stateChange:1->2 Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08 17:14:50.120 ThaliTest[492:298419] client session: fireConnectCallback: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:14:50.121 ThaliTest[492:298419] jxcore: connect: success
2015-12-08T16:14:50.123Z SendDataConnector.js: CLIENT connected to 51828, error: null
,2015-12-08T16:14:50.123Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 17:14:50.130 ThaliTest[492:297357] client: relay established
2015-12-08 17:14:50.131 ThaliTest[492:297357] client: new accepted socket: 0x15f5b380
,2015-12-08T16:14:50.146Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T16:14:50.469Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-08T16:14:50.507Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-08T16:14:50.701Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-08T16:14:50.701Z SendDataConnector.js: got all data for this round
,2015-12-08T16:14:50.703Z SendDataConnector.js: CLIENT Stop now
2015-12-08T16:14:50.703Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:14:50.704 ThaliTest[492:297568] jxcore: disconnect
2015-12-08 17:14:50.704 ThaliTest[492:297568] client session: disconnectFromPeer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:14:50.704 ThaliTest[492:297568] client session: disconnect
2015-12-08 17:14:50.704 ThaliTest[492:297568] client session: stateChange:2->0 Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08 17:14:50.712 ThaliTest[492:297568] jxcore: disconnect: success
2015-12-08T16:14:50.712Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7651.u5AQgA==
---- round done--------
device[2]: Apple-Iphone5-1_PT8010.sww,phA==
2015-12-08T16:14:50.714Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT8010.swwphA==
2015-12-08T16:14:50.714Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT8010.swwphA==
2015-12-08T16:14:50.714Z SendDataConnector.js: do connect now
,2015-12-08 17:14:50.715 ThaliTest[492:297568] jxcore: connect Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:14:50.716 ThaliTest[492:297568] client session: connect
2015-12-08 17:14:50.716 ThaliTest[492:297568] client session: stateChange:0->1 Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:14:52.062 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT785.mqQzsA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-08 17:14:54.365 ThaliTest[492:297357] multipeer session: reset timer
2015-12-08 17:14:54.366 ThaliTest[492:297357] multipeer session: stop timer
2015-12-08 17:14:54.366 ThaliTest[492:297357] multipeer session: start timer: 0x15f52470
2015-12-08 ,17:14:54.366 ThaliTest[492:297357] server session: connect
2015-12-08 17:14:54.367 ThaliTest[492:297357] server session: stateChange:0->1 Apple-Iphone6-1_PT7651
,2015-12-08 17:14:54.379 ThaliTest[492:297357] server: accepting invitation Apple-Iphone6-1_PT7651
,2015-12-08 17:14:55.270 ThaliTest[492:297357] client: lost peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 17:14:55.270 ThaliTest[492:297357] client session: onPeerLost: Apple-Iphone5-1_PT785.mqQzsA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT785.mqQzsA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-08 17:14:55.694 ThaliTest[492:298419] client session: connected
,2015-12-08 17:14:55.694 ThaliTest[492:298419] client session: stateChange:1->2 Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:14:55.768 ThaliTest[492:298466] client session: fireConnectCallback: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:14:55.768 ThaliTest[492:298466] jxcore: connect: success
2015-12-08T16:14:55.770Z SendDataConnector.js: CLIENT connected to 5,1831, error: null
2015-12-08T16:14:55.770Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 17:14:55.774 ThaliTest[492:297357] client: relay established
2015-12-08 17:14:55.775 ThaliTest[492:297357] client: new accepted socket: 0x15f64620
,2015-12-08T16:14:55.788Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T16:14:56.744Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-08T16:14:56.756Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-08T16:14:56.796Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-08T16:14:56.797Z SendDataConnector.js: got all data for this round
,2015-12-08T16:14:56.799Z SendDataConnector.js: CLIENT Stop now
2015-12-08T16:14:56.799Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:14:56.800 ThaliTest[492:297568] jxcore: disconnect
2015-12-08 17:14:56.802 ThaliTest[492:297568] client session: disconnectFromPeer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:14:56.803 ThaliTest[492:297568] client session: disconnect
2,015-12-08 17:14:56.803 ThaliTest[492:297568] client session: stateChange:2->0 Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:14:56.868 ThaliTest[492:297357] multipeer session: reset timer
2015-12-08 17:14:56.868 ThaliTest[492:297357] multipeer session: stop timer
,2015-12-08 17:14:56.869 ThaliTest[492:297357] multipeer session: start timer: 0x15f52470
,2015-12-08 17:14:56.870 ThaliTest[492:297357] server session: connect
2015-12-08 17:14:56.871 ThaliTest[492:297357] server session: stateChange:0->1 Apple-IpadAir2-1_PT4957
,2015-12-08 17:14:56.882 ThaliTest[492:297357] server: accepting invitation Apple-IpadAir2-1_PT4957
,2015-12-08 17:14:56.947 ThaliTest[492:297568] jxcore: disconnect: success
2015-12-08T16:14:56.947Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT8010.swwphA==
---- round done--------
device[3]: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08T16:14:56.950Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08T16:14:56.950Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08T16:14:56.950Z SendDataCon,nector.js: do connect now
2015-12-08 17:14:56.951 ThaliTest[492:297568] jxcore: connect Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:14:56.952 ThaliTest[492:297568] client session: connect
2015-12-08 17:14:56.952 ThaliTest[492:297568] client session: stateChange:0->1 Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:14:57.329 ThaliTest[492:297357] multipeer session: reset timer
2015-12-08 17:14:57.330 ThaliTest[492:297357] multipeer session: stop timer
2015-12-08 17:14:57.331 ThaliTest[492:297357] multipeer session: start timer: 0x15f52470
2015-12-08 ,17:14:57.331 ThaliTest[492:297357] server session: connect
2015-12-08 17:14:57.331 ThaliTest[492:297357] server session: stateChange:0->1 Apple-Iphone5-1_PT8010
,2015-12-08 17:14:57.342 ThaliTest[492:297357] server: accepting invitation Apple-Iphone5-1_PT8010
,2015-12-08 17:14:57.394 ThaliTest[492:298428] server session: connected
2015-12-08 17:14:57.394 ThaliTest[492:298428] server session: stateChange:1->2 Apple-Iphone6-1_PT7651
,2015-12-08T16:14:57.462Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08 17:14:57.467 ThaliTest[492:297357] server relay: connected (to port: 51825)
,2015-12-08T16:14:57.784Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-08T16:14:57.799Z SendDataTCPServer.js: TCP/IP server has received 47186 bytes of data
,2015-12-08T16:14:57.812Z SendDataTCPServer.js: TCP/IP server has received 82794 bytes of data
,2015-12-08T16:14:57.825Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 17:14:57.915 ThaliTest[492:298419] server session: not connected Apple-Iphone6-1_PT7651
,2015-12-08 17:15:00.025 ThaliTest[492:298418] server session: connected
2015-12-08 17:15:00.025 ThaliTest[492:298418] server session: stateChange:1->2 Apple-IpadAir2-1_PT4957
,2015-12-08 17:15:00.071 ThaliTest[492:297357] server relay: connected (to port: 51825)
,2015-12-08T16:15:00.082Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08T16:15:00.406Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-08T16:15:00.421Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-08T16:15:00.441Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-08T16:15:00.463Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-08T16:15:00.484Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-08T16:15:00.506Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-08T16:15:00.522Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 17:15:00.547 ThaliTest[492:298419] client session: connected
,2015-12-08 17:15:00.547 ThaliTest[492:298419] client session: stateChange:1->2 Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:15:00.594 ThaliTest[492:298418] server session: not connected Apple-IpadAir2-1_PT4957
,2015-12-08 17:15:00.606 ThaliTest[492:298528] server session: connected
,2015-12-08 17:15:00.606 ThaliTest[492:298528] server session: stateChange:1->2 Apple-Iphone5-1_PT8010
,2015-12-08 17:15:00.672 ThaliTest[492:297357] server relay: connected (to port: 51825)
2015-12-08T16:15:00.677Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08 17:15:00.978 ThaliTest[492:298418] client session: fireConnectCallback: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:15:00.979 ThaliTest[492:298418] jxcore: connect: success
2015-12-08T16:15:00.981Z SendDataConnector.js: CLIENT connected to 51837, error: null
2015-12-08T16:15:00.982Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 17:15:00.987 ThaliTest[492:297357] client: relay established
2015-12-08 17:15:00.989 ThaliTest[492:297357] client: new accepted socket: 0x15f50950
,2015-12-08T16:15:00.999Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T16:15:01.520Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-08T16:15:01.531Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-08T16:15:01.551Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-08T16:15:01.554Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-08T16:15:01.582Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-08T16:15:01.598Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-08T16:15:01.662Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-08T16:15:01.677Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-08T16:15:01.677Z SendDataConnector.js: got all data for this round
,2015-12-08T16:15:01.678Z SendDataConnector.js: CLIENT Stop now
,2015-12-08T16:15:01.679Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:15:01.680 ThaliTest[492:297568] jxcore: disconnect
,2015-12-08 17:15:01.681 ThaliTest[492:297568] client session: disconnectFromPeer: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:15:01.682 ThaliTest[492:297568] client session: disconnect
,2015-12-08 17:15:01.683 ThaliTest[492:297568] client session: stateChange:2->0 Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:15:01.762 ThaliTest[492:297568] jxcore: disconnect: success
,2015-12-08T16:15:01.763Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT4957.VBxUsw==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT7186","time":16567,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT7651.u5AQgA==","time":4882,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_,PT8010.swwphA==","time":6084,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT4957.VBxUsw==","time":4727,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 6084 ms, 99% : 6084 ms, 95 : 6084 ms, 90% : 6084 ms.
,Result count 3, range 4727 ms to  6084 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-08T16:15:01.781Z SendDataConnector.js: CLIENT Stop now
,2015-12-08T16:15:01.782Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:15:02.054 ThaliTest[492:298484] server session: not connected Apple-Iphone5-1_PT8010
,2015-12-08 17:15:23.806 ThaliTest[492:297357] client: lost peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:15:23.807 ThaliTest[492:297357] client session: onPeerLost: Apple-Iphone6-1_PT7651.u5AQgA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT7651.u5AQgA==","peerName":"(null)","peerAvailable":false}]
,2015-12-08 17:15:27.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:15:27.381 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:15:27.381 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:15:29.993 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7651.u5AQgA==","peerName":"(null)","peerAvailable":true}]
,2015-12-08 17:15:57.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:15:57.398 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:15:57.399 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:15:57.400 ThaliTest[492:297357] client: fou,nd peer: Apple-Iphone6-1_PT7651.u5AQgA==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 17:16:27.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:16:27.391 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:16:27.392 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:16:27.392 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:16:43.661 ThaliTest[492:297357] client: lost peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:16:43.662 ThaliTest[492:297357] client session: onPeerLost: Apple-Iphone6-1_PT7651.u5AQgA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT7651.u5AQgA==","peerName":"(null)","peerAvailable":false}]
,2015-12-08 17:16:44.736 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7651.u5AQgA==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:16:57.331 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:16:57.387 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:16:57.388 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:17:06.673 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
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
,2015-12-08 17:17:27.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:17:27.394 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:17:27.401 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:17:27.402 ThaliTest[492:297357] client: fou,nd peer: Apple-Iphone6-1_PT7651.u5AQgA==
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
,2015-12-08 17:17:57.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:17:57.396 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:17:57.397 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:17:57.408 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 17:18:27.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:18:27.395 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:18:27.396 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:18:27.401 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
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
,2015-12-08 17:18:57.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:18:57.390 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:18:57.391 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:18:57.392 ThaliTest[492:297357] client: fou,nd peer: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:18:57.868 ThaliTest[492:297357] client: lost peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:18:57.868 ThaliTest[492:297357] client session: onPeerLost: Apple-Iphone5-1_PT8010.swwphA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8010.swwphA==","peerName":"(null)","peerAvailable":false}]
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
,2015-12-08 17:19:27.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:19:27.410 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:19:27.411 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8010.swwphA==","peerName":"(null)","peerAvailable":true}]
,2015-12-08 17:19:27.425 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
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
,2015-12-08 17:19:57.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:19:57.388 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:19:57.411 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:19:57.413 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
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
,2015-12-08 17:20:27.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:20:27.394 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:20:27.395 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
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
,2015-12-08 17:20:57.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:20:57.398 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:20:57.402 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08 17:20:57.403 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
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
,2015-12-08 17:21:27.332 ThaliTest[492:297357] multipeer session: restart
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
,2015-12-08 17:21:57.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:21:57.380 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:21:57.380 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:21:57.383 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
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
,2015-12-08 17:22:27.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:22:27.396 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:22:27.396 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:22:27.399 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
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
,2015-12-08 17:22:57.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:22:57.388 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:22:57.389 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:22:57.390 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
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
,2015-12-08 17:23:27.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:23:28.002 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:23:28.003 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:23:28.003 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
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
,2015-12-08 17:23:57.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:23:57.391 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:23:57.391 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:23:57.394 ThaliTest[492:297357] client: fou,nd peer: Apple-Iphone6-1_PT7651.u5AQgA==
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
,2015-12-08 17:24:27.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:24:27.394 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:24:27.395 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:24:27.395 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
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
,2015-12-08 17:24:57.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:24:57.393 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:24:57.394 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:24:57.406 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
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
,2015-12-08 17:25:27.332 ThaliTest[492:297357] multipeer session: restart
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
,2015-12-08 17:25:57.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:25:57.381 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:25:57.382 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:25:57.385 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
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
,2015-12-08 17:26:27.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:26:27.387 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:26:27.391 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:26:27.391 ThaliTest[492:297357] client: foun,d peer: Apple-IpadAir2-1_PT4957.VBxUsw==
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
,2015-12-08 17:26:57.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:26:57.390 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:26:57.391 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:26:57.399 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
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
,2015-12-08 17:27:27.331 ThaliTest[492:297357] multipeer session: restart
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
,2015-12-08 17:27:57.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:27:57.386 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:27:57.387 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:27:57.390 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
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
,2015-12-08 17:28:27.332 ThaliTest[492:297357] multipeer session: restart
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
,2015-12-08 17:28:57.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:28:57.385 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:28:57.386 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:28:57.397 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
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
,2015-12-08 17:29:27.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:29:27.391 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:29:27.391 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:29:27.392 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
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
,2015-12-08 17:29:57.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:29:57.389 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:29:57.390 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:29:57.390 ThaliTest[492:297357] client: fou,nd peer: Apple-Iphone6-1_PT7651.u5AQgA==
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
,2015-12-08 17:30:27.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:30:27.384 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:30:27.385 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:30:27.387 ThaliTest[492:297357] client: fou,nd peer: Apple-Iphone6-1_PT7651.u5AQgA==
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
,2015-12-08 17:30:57.332 ThaliTest[492:297357] multipeer session: restart
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
,2015-12-08 17:31:27.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:31:27.379 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:31:27.379 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:31:27.386 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
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
,2015-12-08 17:31:57.332 ThaliTest[492:297357] multipeer session: restart
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
,2015-12-08 17:32:27.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:32:27.387 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:32:27.395 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:32:27.396 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
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
,2015-12-08 17:32:57.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:32:58.266 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:32:58.266 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
2015-12-08 17:32:58.267 ThaliTest[492:297357] client: foun,d peer: Apple-IpadAir2-1_PT4957.VBxUsw==
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
,2015-12-08 17:33:27.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:33:27.387 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:33:27.388 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:33:27.388 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
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
,2015-12-08 17:33:57.332 ThaliTest[492:297357] multipeer session: restart
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
,2015-12-08 17:34:27.332 ThaliTest[492:297357] multipeer session: restart
,2015-12-08 17:34:27.372 ThaliTest[492:297357] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:34:27.375 ThaliTest[492:297357] client: found peer: Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08 17:34:28.195 ThaliTest[492:297357] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
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
,2015-12-08 17:34:57.332 ThaliTest[492:297357] multipeer session: restart

```
