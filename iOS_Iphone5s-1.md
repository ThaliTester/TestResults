#### Test 539786639813e59_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/539786639813e59/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/902C2746-480E-4FDA-B796-5F31D7BAF668/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/902C2746-480E-4FDA-B796-5F31D7BAF668/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/539786639813e59/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/539786639813e59/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8F934A1F-45FB-4F94-AA66-FDEFCB9AA188/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59293"
,(lldb)     command script import "/tmp/902C2746-480E-4FDA-B796-5F31D7BAF668/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-17 15:09:28.820 ThaliTest[371:221714] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/24B19169-8812-4AD9-894F-C68D5A2725A4/Library/Cookies/Cookies.binarycookies
,2015-12-17 15:09:29.251 ThaliTest[371:221714] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-17 15:09:29.253 ThaliTest[371:221714] Multi-tasking -> Device: YES, App: YES
,2015-12-17 15:09:29.263 ThaliTest[371:221714] Unlimited access to network resources
,2015-12-17 15:09:29.279 ThaliTest[371:221714] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-17 15:09:38.151 ThaliTest[371:221714] Resetting plugins due to page load.
,2015-12-17 15:09:42.074 ThaliTest[371:221714] Finished load of: file:///var/mobile/Containers/Bundle/Application/8F934A1F-45FB-4F94-AA66-FDEFCB9AA188/ThaliTest.app/www/index.html
,2015-12-17 15:09:42.286 ThaliTest[371:221714] JXcore Cordova plugin initializing
,2015-12-17 15:09:42.287 ThaliTest[371:221926] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Radios toggled
,my name is : Apple-Iphone5s-1_PT1370
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":20000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 50568
,2015-12-17 15:16:43.755 ThaliTest[371:221926] jxcore: startBroadcasting
,2015-12-17 15:16:43.778 ThaliTest[371:221926] server: starting Apple-Iphone5s-1_PT1370.za9tCA==
,2015-12-17 15:16:43.780 ThaliTest[371:221926] multipeer session: start timer: 0x18ce17a0
2015-12-17 15:16:43.781 ThaliTest[371:221926] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT1370
2015-12-17 15:16:43.782 ThaliTest[371:221926] jxcore: star,tBroadcasting: success
,StartBroadcasting started ok
,2015-12-17T14:16:43.786Z SendDataTCPServer.js: TCP/IP server is bound to port: 50568
,2015-12-17 15:16:45.396 ThaliTest[371:221714] client: found peer: Apple-IpadAir2-1_PT1563.8yqJeg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1563.8yqJeg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT1563.8yqJeg==
,2015-12-17T14:16:45.405Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1563.8yqJeg==
2015-12-17T14:16:45.406Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1563.8yqJeg==
2015-12-17T14:16:45.407Z SendDataConnector.j,s: do connect now
2015-12-17 15:16:45.407 ThaliTest[371:221926] jxcore: connect Apple-IpadAir2-1_PT1563.8yqJeg==
,2015-12-17 15:16:45.408 ThaliTest[371:221926] client session: connect
2015-12-17 15:16:45.408 ThaliTest[371:221926] client session: stateChange:0->1 Apple-IpadAir2-1_PT1563.8yqJeg==
,2015-12-17 15:16:46.109 ThaliTest[371:221714] client: found peer: Apple-Iphone5-1_PT5479.4UkRdw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5479.4UkRdw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-17 15:16:46.494 ThaliTest[371:221714] client: found peer: Apple-Iphone6-1_PT1480.8RWX+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1480.8RWX+A==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-17 15:16:50.282 ThaliTest[371:222609] client session: connected
2015-12-17 15:16:50.283 ThaliTest[371:222609] client session: stateChange:1->2 Apple-IpadAir2-1_PT1563.8yqJeg==
,2015-12-17 15:16:50.289 ThaliTest[371:222609] client session: fireConnectCallback: Apple-IpadAir2-1_PT1563.8yqJeg==
2015-12-17 15:16:50.289 ThaliTest[371:222609] jxcore: connect: success
,2015-12-17T14:16:50.291Z SendDataConnector.js: CLIENT connected to 50571, error: null
,2015-12-17T14:16:50.292Z SendDataConnector.js: CLIENT starting client 
,2015-12-17 15:16:50.297 ThaliTest[371:221714] client: relay established
2015-12-17 15:16:50.298 ThaliTest[371:221714] client: new accepted socket: 0x18e0ce20
,2015-12-17T14:16:50.315Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17 15:16:50.577 ThaliTest[371:221714] multipeer session: reset timer
2015-12-17 15:16:50.577 ThaliTest[371:221714] multipeer session: stop timer
2015-12-17 15:16:50.578 ThaliTest[371:221714] multipeer session: start timer: 0x18ce17a0
2015-12-17 ,15:16:50.578 ThaliTest[371:221714] server session: connect
2015-12-17 15:16:50.578 ThaliTest[371:221714] server session: stateChange:0->1 Apple-Iphone6-1_PT1480
2015-12-17 15:16:50.582 ThaliTest[371:221714] server: accepting invitation Apple-Iphone6-1_PT1480
,2015-12-17T14:16:50.843Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-17T14:16:51.339Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-17T14:16:51.340Z SendDataConnector.js: got all data for this round
,2015-12-17T14:16:51.343Z SendDataConnector.js: CLIENT Stop now
2015-12-17T14:16:51.343Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-17 15:16:51.345 ThaliTest[371:221926] jxcore: disconnect
2015-12-17 15:16:51.346 ThaliTest[371:221926] client ,session: disconnectFromPeer: Apple-IpadAir2-1_PT1563.8yqJeg==
2015-12-17 15:16:51.346 ThaliTest[371:221926] client session: disconnect
2015-12-17 15:16:51.347 ThaliTest[371:221926] client session: stateChange:2->0 Apple-IpadAir2-1_PT1563.8yqJeg==
,2015-12-17 15:16:51.453 ThaliTest[371:221926] jxcore: disconnect: success
,2015-12-17T14:16:51.455Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1563.8yqJeg==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17T14:16:51.461Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17T14:16:51.463Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17T14:16:51.464Z SendDataConnector.js: do connect now
,2015-12-17 15:16:51.466 ThaliTest[371:221926] jxcore: connect Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17 15:16:51.469 ThaliTest[371:221926] client session: connect
,2015-12-17 15:16:51.471 ThaliTest[371:221926] client session: stateChange:0->1 Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17 15:16:51.611 ThaliTest[371:221714] multipeer session: reset timer
,2015-12-17 15:16:51.611 ThaliTest[371:221714] multipeer session: stop timer
2015-12-17 15:16:51.612 ThaliTest[371:221714] multipeer session: start timer: 0x18ce17a0
2015-12-17 15:16:51.612 ThaliTest[371:221714] server session: connect
,2015-12-17 15:16:51.612 ThaliTest[371:221714] server session: stateChange:0->1 Apple-IpadAir2-1_PT1563
,2015-12-17 15:16:51.619 ThaliTest[371:221714] server: accepting invitation Apple-IpadAir2-1_PT1563
,2015-12-17 15:16:53.255 ThaliTest[371:222635] server session: connected
,2015-12-17 15:16:53.255 ThaliTest[371:222635] server session: stateChange:1->2 Apple-Iphone6-1_PT1480
,2015-12-17T14:16:53.271Z SendDataTCPServer.js: TCP/IP server connected
2015-12-17 15:16:53.272 ThaliTest[371:221714] server relay: connected (to port: 50568)
,2015-12-17T14:16:53.583Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-17T14:16:53.602Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-17T14:16:53.621Z SendDataTCPServer.js: TCP/IP server has received 43516 bytes of data
,2015-12-17T14:16:53.639Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-17 15:16:53.656 ThaliTest[371:221714] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17T14:16:53.665Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.KeEEhw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-17T14:16:53.683Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-17T14:16:53.698Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17 15:16:53.775 ThaliTest[371:222609] server session: not connected Apple-Iphone6-1_PT1480
,2015-12-17 15:16:54.631 ThaliTest[371:222609] server session: connected
2015-12-17 15:16:54.632 ThaliTest[371:222609] server session: stateChange:1->2 Apple-IpadAir2-1_PT1563
,2015-12-17 15:16:54.680 ThaliTest[371:221714] server relay: connected (to port: 50568)
2015-12-17T14:16:54.689Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-17T14:16:55.013Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-17T14:16:55.027Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-17T14:16:55.044Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-17T14:16:55.071Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-17T14:16:55.087Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-17T14:16:55.103Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-17T14:16:55.119Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-17T14:16:55.134Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-17T14:16:55.154Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-17T14:16:55.167Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17 15:16:56.068 ThaliTest[371:222635] client session: connected
2015-12-17 15:16:56.068 ThaliTest[371:222635] client session: stateChange:1->2 Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17 15:16:56.119 ThaliTest[371:222635] client session: fireConnectCallback: Apple-Iphone5-1_PT5479.4UkRdw==
2015-12-17 15:16:56.120 ThaliTest[371:222635] jxcore: connect: success
,2015-12-17T14:16:56.127Z SendDataConnector.js: CLIENT connected to 50576, error: null
2015-12-17T14:16:56.128Z SendDataConnector.js: CLIENT starting client 
,2015-12-17 15:16:56.135 ThaliTest[371:221714] client: relay established
,2015-12-17 15:16:56.137 ThaliTest[371:221714] client: new accepted socket: 0x18f41c80
,2015-12-17T14:16:56.142Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17 15:16:56.165 ThaliTest[371:222635] server session: not connected Apple-IpadAir2-1_PT1563
,2015-12-17T14:16:56.609Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-17T14:16:56.657Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-17T14:16:56.657Z SendDataConnector.js: got all data for this round
,2015-12-17T14:16:56.658Z SendDataConnector.js: CLIENT Stop now
2015-12-17T14:16:56.658Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 15:16:56.658 ThaliTest[371:221926] jxcore: disconnect
2015-12-17 15:16:56.659 ThaliTest[371:221926] client session: disconnectFromPeer: Apple-Iphone5-1_PT5479.4UkRdw==
2015-12-17 15:16:56.659 ThaliTest[371:221926] client session: disconnect
2015-12-17 15:16:56.659 ThaliTest[371:221926] client session: stateChange:2->0 Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17 15:16:56.667 ThaliTest[371:221926] jxcore: disconnect: success
2015-12-17T14:16:56.667Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5479.4UkRdw==
---- round done--------
device[3]: Apple-Iphone6-1_PT1480.8RW,X+A==
2015-12-17T14:16:56.668Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT1480.8RWX+A==
2015-12-17T14:16:56.668Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1480.8RWX+A==
2015-12-17T14:16:56.668Z SendDataConnector.js: do connect now
2015-12-17 15:16:56.669 ThaliTest[371:221926] jxcore: connect Apple-Iphone6-1_PT1480.8RWX+A==
,2015-12-17 15:16:56.669 ThaliTest[371:221926] client session: connect
2015-12-17 15:16:56.670 ThaliTest[371:221926] client session: stateChange:0->1 Apple-Iphone6-1_PT1480.8RWX+A==
,2015-12-17 15:16:56.839 ThaliTest[371:221714] multipeer session: reset timer
2015-12-17 15:16:56.839 ThaliTest[371:221714] multipeer session: stop timer
2015-12-17 15:16:56.839 ThaliTest[371:221714] multipeer session: start timer: 0x18ce17a0
2015-12-17 15:16:56.839 ThaliTest[371:221714] server session: connect
2015-12-17 15:16:56.839 ThaliTest[371:221714] server session: stateChange:0->1 Apple-Iphone5-1_PT5479
,2015-12-17 15:16:56.844 ThaliTest[371:221714] server: accepting invitation Apple-Iphone5-1_PT5479
,2015-12-17 15:16:59.273 ThaliTest[371:222640] client session: connected
2015-12-17 15:16:59.275 ThaliTest[371:222640] client session: stateChange:1->2 Apple-Iphone6-1_PT1480.8RWX+A==
2015-12-17 15:16:59.279 ThaliTest[371:222640] client session: fireConne,ctCallback: Apple-Iphone6-1_PT1480.8RWX+A==
2015-12-17 15:16:59.279 ThaliTest[371:222640] jxcore: connect: success
2015-12-17T14:16:59.280Z SendDataConnector.js: CLIENT connected to 50579, error: null
2015-12-17T14:16:59.281Z SendDataConnector.js: CLIEN,T starting client 
,2015-12-17 15:16:59.286 ThaliTest[371:221714] client: relay established
2015-12-17 15:16:59.286 ThaliTest[371:221714] client: new accepted socket: 0x18b6d240
,2015-12-17T14:16:59.302Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17T14:16:59.638Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-17T14:16:59.649Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-17T14:16:59.698Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-17T14:16:59.698Z SendDataConnector.js: got all data for this round
,2015-12-17T14:16:59.699Z SendDataConnector.js: CLIENT Stop now
,2015-12-17T14:16:59.700Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 15:16:59.701 ThaliTest[371:221926] jxcore: disconnect
,2015-12-17 15:16:59.701 ThaliTest[371:221926] client session: disconnectFromPeer: Apple-Iphone6-1_PT1480.8RWX+A==
,2015-12-17 15:16:59.702 ThaliTest[371:221926] client session: disconnect
,2015-12-17 15:16:59.703 ThaliTest[371:221926] client session: stateChange:2->0 Apple-Iphone6-1_PT1480.8RWX+A==
,2015-12-17 15:16:59.773 ThaliTest[371:221926] jxcore: disconnect: success
,2015-12-17T14:16:59.774Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1480.8RWX+A==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT1370","time":16040,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT1563.8yqJeg==","time":5935,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1,_PT5479.4UkRdw==","time":5195,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT1480.8RWX+A==","time":3031,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":1000,00}]}
,sendList : 100% : 5935 ms, 99% : 5935 ms, 95 : 5935 ms, 90% : 5935 ms.
,Result count 3, range 3031 ms to  5935 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-17T14:16:59.785Z SendDataConnector.js: CLIENT Stop now
,2015-12-17T14:16:59.785Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 15:16:59.885 ThaliTest[371:222607] server session: connected
2015-12-17 15:16:59.885 ThaliTest[371:222607] server session: stateChange:1->2 Apple-Iphone5-1_PT5479
,2015-12-17 15:16:59.888 ThaliTest[371:221714] server relay: connected (to port: 50568)
2015-12-17T14:16:59.890Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-17T14:17:00.646Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-17T14:17:00.663Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-17T14:17:00.683Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-17T14:17:00.701Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-17T14:17:00.719Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-17T14:17:00.734Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-17T14:17:00.786Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17 15:17:00.943 ThaliTest[371:222708] server session: not connected Apple-Iphone5-1_PT5479
,2015-12-17 15:17:07.251 ThaliTest[371:221714] client: lost peer: Apple-IpadAir2-1_PT1563.8yqJeg==
2015-12-17 15:17:07.251 ThaliTest[371:221714] client session: onPeerLost: Apple-IpadAir2-1_PT1563.8yqJeg==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-IpadAir2-1_PT1563.8yqJeg==","peerName":"(null)","peerAvailable":false}]
,2015-12-17 15:17:08.122 ThaliTest[371:221714] client: lost peer: Apple-Iphone5-1_PT5479.4UkRdw==
2015-12-17 15:17:08.122 ThaliTest[371:221714] client session: onPeerLost: Apple-Iphone5-1_PT5479.4UkRdw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone5-1_PT5479.4UkRdw==","peerName":"(null)","peerAvailable":false}]
,2015-12-17 15:17:15.911 ThaliTest[371:221714] client: lost peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 15:17:15.912 ThaliTest[371:221714] client session: onPeerLost: Apple-Iphone5-1_PT6883.KeEEhw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone5-1_PT6883.KeEEhw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-17 15:17:20.761 ThaliTest[371:221714] client: lost peer: Apple-Iphone6-1_PT1480.8RWX+A==
2015-12-17 15:17:20.762 ThaliTest[371:221714] client session: onPeerLost: Apple-Iphone6-1_PT1480.8RWX+A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1480.8RWX+A==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
,stop current!
,testSendData stopped
,2015-12-17 15:17:23.704 ThaliTest[371:221926] jxcore: stopBroadcasting
2015-12-17 15:17:23.705 ThaliTest[371:221926] THEMultipeerSession stopping peer
2015-12-17 15:17:23.706 ThaliTest[371:221926] multipeer session: stop timer
2015-12-17 15:17:23.706 Th,aliTest[371:221926] server session: disconnect
2015-12-17 15:17:23.707 ThaliTest[371:221926] server session: stateChange:2->0 Apple-IpadAir2-1_PT1563
2015-12-17 15:17:23.714 ThaliTest[371:221926] server session: disconnect
2015-12-17 15:17:23.714 ThaliT,est[371:221926] server session: stateChange:2->0 Apple-Iphone5-1_PT5479
,2015-12-17 15:17:23.834 ThaliTest[371:221926] server session: disconnect
,2015-12-17 15:17:23.836 ThaliTest[371:221926] server session: stateChange:2->0 Apple-Iphone6-1_PT1480
,2015-12-17 15:17:23.907 ThaliTest[371:221926] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-17T14:17:23.925Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-17T14:17:23.927Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-17T14:17:23.929Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-17T14:17:23.930Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT1480.8RWX+A==\",\"time\":3031,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone5-1_PT5479.4UkRdw==\",\"time\":5195,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-IpadAir2-1_PT1563.8yqJeg==\",\"time\":5935,\"result\":\"OK\",\"connections\":1,,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
