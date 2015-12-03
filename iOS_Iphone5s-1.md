#### Test 52383621712b264_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52383621712b264/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/0CE7FD9F-50C6-48C8-B040-4ACA76DDB20F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0CE7FD9F-50C6-48C8-B040-4ACA76DDB20F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52383621712b264/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52383621712b264/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9692CF0A-8641-4B78-938B-8418FA1E5C84/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60536"
,(lldb)     command script import "/tmp/0CE7FD9F-50C6-48C8-B040-4ACA76DDB20F/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 15:39:30.385 ThaliTest[2472:2307850] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/44C45C71-970A-437B-BF82-04977124AD4A/Library/Cookies/Cookies.binarycookies
,2015-12-03 15:39:30.816 ThaliTest[2472:2307850] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 15:39:30.817 ThaliTest[2472:2307850] Multi-tasking -> Device: YES, App: YES
,2015-12-03 15:39:30.826 ThaliTest[2472:2307850] Unlimited access to network resources
,2015-12-03 15:39:30.836 ThaliTest[2472:2307850] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 15:39:34.777 ThaliTest[2472:2307850] Resetting plugins due to page load.
,2015-12-03 15:39:35.253 ThaliTest[2472:2307850] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/9692CF0A-8641-4B78-938B-8418FA1E5C84/ThaliTest.app/www/index.html
,2015-12-03 15:39:35.410 ThaliTest[2472:2307850] JXcore Cordova plugin initializing
2015-12-03 15:39:35.411 ThaliTest[2472:2307958] JXcore instance initializing
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
,my name is : Apple-Iphone5s-1_PT2374
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 50479
,2015-12-03 15:45:49.631 ThaliTest[2472:2307958] jxcore: startBroadcasting
,2015-12-03 15:45:49.643 ThaliTest[2472:2307958] server: starting Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:45:49.645 ThaliTest[2472:2307958] multipeer session: start timer: 0x18d96010
2015-12-03 15:45:49.646 ThaliTest[2472:2307958] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT2374
2015-12-03 15:45:49.646 ThaliTest[2472:2307958] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-03T14:45:49.651Z SendDataTCPServer.js: TCP/IP server is bound to port: 50479
,2015-12-03 15:45:49.870 ThaliTest[2472:2307850] client: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1068.V8ys1g==","peerName":"(null)","peerAvailable":true}]
2015-12-03 15:45:49.874 ThaliTest[2472:2307850] client: found peer: Apple-Iphone5-1_PT4165.Uz5DSQ==
Found peer : (null), Available: true
device[1]: Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03T14:45:49.879Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03T14:45:49.880Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03T14:45:49.880Z SendDataConnector.js: do connect now
,2015-12-03 15:45:49.880 ThaliTest[2472:2307958] jxcore: connect Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:45:49.881 ThaliTest[2472:2307958] client session: connect
2015-12-03 15:45:49.881 ThaliTest[2472:2307958] client session: stateChange:0->1 Apple-Iphone6-1_PT1068.V8ys1g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4165.Uz5DSQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 15:45:49.958 ThaliTest[2472:2307850] client: found peer: Apple-IpadAir2-1_PT6724.bsoISg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6724.bsoISg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 15:45:53.470 ThaliTest[2472:2307850] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 15:45:53.574 ThaliTest[2472:2308491] client session: connected
2015-12-03 15:45:53.574 ThaliTest[2472:2308491] client session: stateChange:1->2 Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:45:53.579 ThaliTest[2472:2308491] client session: fireConnectCallback: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:45:53.580 ThaliTest[2472:2308491] jxcore: connect: success
,2015-12-03T14:45:53.582Z SendDataConnector.js: CLIENT connected to 50482, error: null
2015-12-03T14:45:53.583Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:45:53.588 ThaliTest[2472:2307850] client: relay established
2015-12-03 15:45:53.589 ThaliTest[2472:2307850] client: new accepted socket: 0x18c0fe70
,2015-12-03T14:45:53.605Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T14:45:54.015Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-03T14:45:54.028Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-03T14:45:54.041Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-03T14:45:54.054Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-03T14:45:54.067Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03 15:45:55.283 ThaliTest[2472:2307850] multipeer session: reset timer
2015-12-03 15:45:55.283 ThaliTest[2472:2307850] multipeer session: stop timer
2015-12-03 15:45:55.284 ThaliTest[2472:2307850] multipeer session: start timer: 0x18d96010
2015-,12-03 15:45:55.284 ThaliTest[2472:2307850] server session: connect
2015-12-03 15:45:55.285 ThaliTest[2472:2307850] server session: stateChange:0->1 Apple-IpadAir2-1_PT6724
,2015-12-03 15:45:55.297 ThaliTest[2472:2307850] server: accepting invitation Apple-IpadAir2-1_PT6724
,2015-12-03 15:45:55.633 ThaliTest[2472:2307850] multipeer session: reset timer
2015-12-03 15:45:55.634 ThaliTest[2472:2307850] multipeer session: stop timer
2015-12-03 15:45:55.634 ThaliTest[2472:2307850] multipeer session: start timer: 0x18d96010
2015-,12-03 15:45:55.635 ThaliTest[2472:2307850] server session: connect
2015-12-03 15:45:55.636 ThaliTest[2472:2307850] server session: stateChange:0->1 Apple-Iphone5-1_PT4165
,2015-12-03 15:45:55.648 ThaliTest[2472:2307850] server: accepting invitation Apple-Iphone5-1_PT4165
,2015-12-03 15:45:57.690 ThaliTest[2472:2308481] server session: connected
2015-12-03 15:45:57.691 ThaliTest[2472:2308481] server session: stateChange:1->2 Apple-IpadAir2-1_PT6724
,2015-12-03 15:45:57.696 ThaliTest[2472:2307850] server relay: connected (to port: 50479)
,2015-12-03T14:45:57.704Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03 15:45:57.819 ThaliTest[2472:2308486] server session: connected
2015-12-03 15:45:57.819 ThaliTest[2472:2308486] server session: stateChange:1->2 Apple-Iphone5-1_PT4165
,2015-12-03T14:45:57.828Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03 15:45:57.830 ThaliTest[2472:2307850] server relay: connected (to port: 50479)
,2015-12-03T14:45:58.195Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-03T14:45:58.210Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-03T14:45:58.227Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-03T14:45:58.246Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-03T14:45:58.264Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-03T14:45:58.282Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 15:45:58.381 ThaliTest[2472:2308516] server session: not connected Apple-IpadAir2-1_PT6724
,2015-12-03T14:45:58.416Z SendDataTCPServer.js: TCP/IP server has received 6944 bytes of data
,2015-12-03T14:45:58.465Z SendDataTCPServer.js: TCP/IP server has received 36704 bytes of data
,2015-12-03T14:45:58.725Z SendDataTCPServer.js: TCP/IP server has received 40672 bytes of data
,2015-12-03T14:45:58.744Z SendDataTCPServer.js: TCP/IP server has received 49600 bytes of data
,2015-12-03T14:45:58.759Z SendDataTCPServer.js: TCP/IP server has received 70432 bytes of data
,2015-12-03T14:45:58.779Z SendDataTCPServer.js: TCP/IP server has received 77376 bytes of data
,2015-12-03T14:45:58.866Z SendDataTCPServer.js: TCP/IP server has received 81344 bytes of data
,2015-12-03T14:45:58.886Z SendDataTCPServer.js: TCP/IP server has received 91264 bytes of data
,2015-12-03T14:45:58.900Z SendDataTCPServer.js: TCP/IP server has received 97216 bytes of data
,2015-12-03T14:45:58.914Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03T14:46:04.072Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:46:04.073Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:46:04.077Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T14:46:04.077Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:46:04.078Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:46:04.080 ThaliTest[2472:2307850] client: socket closed
2015-12-03 15:46:04.081 ThaliTest[2472:2307850] client relay: socket disconnected
2015-12-03 15:46:04.081 ThaliTest[2472:2307850] client relay: 0x18c0fe70 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x18db36f0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:46:04.082 ThaliTest[2472:2307850] client session: socket closed: Apple-Iphone6-1_PT1068.V8ys1g,==
2015-12-03 15:46:04.083 ThaliTest[2472:2307850] client session: onLinkFailure: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:46:04.083 ThaliTest[2472:2307850] client session: disconnect
2015-12-03 15:46:04.084 ThaliTest[2472:2307850] client session: ,stateChange:2->0 Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:46:04.086 ThaliTest[2472:2307850] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03T14:46:09.089Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03T14:46:09.090Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:46:09.190 ThaliTest[2472:2308490] server session: not connected Apple-Iphone5-1_PT4165
,2015-12-03 15:46:14.095 ThaliTest[2472:2307958] jxcore: disconnect
2015-12-03 15:46:14.096 ThaliTest[2472:2307958] jxcore: disconnect: fail
2015-12-03T14:46:14.097Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1068.V8ys1,g==
2015-12-03T14:46:14.097Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT1068.V8ys1g== with availability status: true
,2015-12-03T14:46:14.098Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03T14:46:14.098Z SendDataConnector.js: do connect now
,2015-12-03 15:46:14.099 ThaliTest[2472:2307958] jxcore: connect Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:46:14.100 ThaliTest[2472:2307958] client session: connect
,2015-12-03 15:46:14.100 ThaliTest[2472:2307958] client session: stateChange:0->1 Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:46:16.695 ThaliTest[2472:2308516] client session: connected
2015-12-03 15:46:16.696 ThaliTest[2472:2308516] client session: stateChange:1->2 Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:46:16.701 ThaliTest[2472:2308516] client session: fireConnectCallback: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:46:16.702 ThaliTest[2472:2308516] jxcore: connect: success
2015-12-03T14:46:16.703Z SendDataConnector.js: CLIENT connected ,to 50488, error: null
,2015-12-03T14:46:16.704Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:46:16.708 ThaliTest[2472:2307850] client: relay established
2015-12-03 15:46:16.709 ThaliTest[2472:2307850] client: new accepted socket: 0x18dae7c0
,2015-12-03T14:46:16.721Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:46:19.703 ThaliTest[2472:2307850] multipeer session: reset timer
2015-12-03 15:46:19.704 ThaliTest[2472:2307850] multipeer session: stop timer
2015-12-03 15:46:19.704 ThaliTest[2472:2307850] multipeer session: start timer: 0x18d96010
2015-,12-03 15:46:19.705 ThaliTest[2472:2307850] server: disconnecting to refresh session (Apple-Iphone5-1_PT4165)
2015-12-03 15:46:19.706 ThaliTest[2472:2307850] server session: disconnect
2015-12-03 15:46:19.706 ThaliTest[2472:2307850] server session: stateC,hange:2->0 Apple-Iphone5-1_PT4165
2015-12-03 15:46:19.709 ThaliTest[2472:2307850] server session: connect
2015-12-03 15:46:19.710 ThaliTest[2472:2307850] server session: stateChange:0->1 Apple-Iphone5-1_PT4165
2015-12-03T14:46:19.713Z SendDataTCPServer.,js: TCP/IP server is ended
,2015-12-03 15:46:19.732 ThaliTest[2472:2307850] server: accepting invitation Apple-Iphone5-1_PT4165
,2015-12-03 15:46:21.929 ThaliTest[2472:2308486] server session: connected
2015-12-03 15:46:21.930 ThaliTest[2472:2308486] server session: stateChange:1->2 Apple-Iphone5-1_PT4165
,2015-12-03 15:46:21.939 ThaliTest[2472:2307850] server relay: connected (to port: 50479)
2015-12-03T14:46:21.942Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:46:22.035Z SendDataTCPServer.js: TCP/IP server has received 6944 bytes of data
,2015-12-03T14:46:22.049Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T14:46:26.776Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:46:26.777Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:46:26.778Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:46:26.778Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:46:26.779Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:46:26.781 ThaliTest[2472:2307850] client: socket closed
2015-12-03 15:46:26.781 ThaliTest[2472:2307850] client relay: socket disconnected
2015-12-03 15:46:26.782 ThaliTest[2472:2307850] client relay: 0x18dae7c0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x18d9c380 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:46:26.783 ThaliTest[2472:2307850] client session: socket closed: Apple-Iphone6-1_PT1068.V8ys1g,==
2015-12-03 15:46:26.783 ThaliTest[2472:2307850] client session: onLinkFailure: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:46:26.784 ThaliTest[2472:2307850] client session: disconnect
2015-12-03 15:46:26.784 ThaliTest[2472:2307850] client session: ,stateChange:2->0 Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:46:26.786 ThaliTest[2472:2307850] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03T14:46:31.785Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03T14:46:31.786Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:46:32.255 ThaliTest[2472:2308490] server session: not connected Apple-Iphone5-1_PT4165
,2015-12-03 15:46:36.791 ThaliTest[2472:2307958] jxcore: disconnect
2015-12-03 15:46:36.792 ThaliTest[2472:2307958] jxcore: disconnect: fail
2015-12-03T14:46:36.793Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1068.V8ys1,g==
2015-12-03T14:46:36.793Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT1068.V8ys1g== with availability status: true
,2015-12-03T14:46:36.794Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03T14:46:36.794Z SendDataConnector.js: do connect now
,2015-12-03 15:46:36.795 ThaliTest[2472:2307958] jxcore: connect Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:46:36.796 ThaliTest[2472:2307958] client session: connect
2015-12-03 15:46:36.797 ThaliTest[2472:2307958] client session: stateChange:0->1 Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:46:39.273 ThaliTest[2472:2308516] client session: connected
2015-12-03 15:46:39.274 ThaliTest[2472:2308516] client session: stateChange:1->2 Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:46:39.279 ThaliTest[2472:2308516] client session: fireConnectCallback: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:46:39.279 ThaliTest[2472:2308516] jxcore: connect: success
2015-12-03T14:46:39.281Z SendDataConnector.js: CLIENT connected ,to 50493, error: null
2015-12-03T14:46:39.281Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:46:39.286 ThaliTest[2472:2307850] client: relay established
2015-12-03 15:46:39.286 ThaliTest[2472:2307850] client: new accepted socket: 0x18d9d930
,2015-12-03T14:46:39.297Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:46:42.761 ThaliTest[2472:2307850] multipeer session: reset timer
2015-12-03 15:46:42.762 ThaliTest[2472:2307850] multipeer session: stop timer
2015-12-03 15:46:42.763 ThaliTest[2472:2307850] multipeer session: start timer: 0x18d96010
2015-,12-03 15:46:42.764 ThaliTest[2472:2307850] server: disconnecting to refresh session (Apple-Iphone5-1_PT4165)
2015-12-03 15:46:42.764 ThaliTest[2472:2307850] server session: disconnect
2015-12-03 15:46:42.764 ThaliTest[2472:2307850] server session: stateC,hange:2->0 Apple-Iphone5-1_PT4165
2015-12-03 15:46:42.770 ThaliTest[2472:2307850] server session: connect
2015-12-03 15:46:42.770 ThaliTest[2472:2307850] server session: stateChange:0->1 Apple-Iphone5-1_PT4165
,2015-12-03T14:46:42.783Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 15:46:42.790 ThaliTest[2472:2307850] server: accepting invitation Apple-Iphone5-1_PT4165
,2015-12-03 15:46:45.045 ThaliTest[2472:2308516] server session: connected
,2015-12-03 15:46:45.046 ThaliTest[2472:2308516] server session: stateChange:1->2 Apple-Iphone5-1_PT4165
,2015-12-03 15:46:45.052 ThaliTest[2472:2307850] server relay: connected (to port: 50479)
,2015-12-03T14:46:45.061Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:46:45.372Z SendDataTCPServer.js: TCP/IP server has received 6944 bytes of data
,2015-12-03T14:46:45.387Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T14:46:49.359Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:46:49.359Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:46:49.360Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:46:49.361Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:46:49.362Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:46:49.363 ThaliTest[2472:2307850] client: socket closed
2015-12-03 15:46:49.366 ThaliTest[2472:2307850] client relay: socket disconnected
2015-12-03 15:46:49.367 ThaliTest[2472:2307850] client relay: 0x18d9d930 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x18db4a80 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:46:49.367 ThaliTest[2472:2307850] client session: socket closed: Apple-Iphone6-1_PT1068.V8ys1g,==
2015-12-03 15:46:49.368 ThaliTest[2472:2307850] client session: onLinkFailure: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:46:49.368 ThaliTest[2472:2307850] client session: disconnect
2015-12-03 15:46:49.369 ThaliTest[2472:2307850] client session: ,stateChange:2->0 Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:46:49.371 ThaliTest[2472:2307850] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03T14:46:54.365Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03T14:46:54.366Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:46:55.319 ThaliTest[2472:2308490] server session: not connected Apple-Iphone5-1_PT4165
,2015-12-03 15:46:59.372 ThaliTest[2472:2307958] jxcore: disconnect
2015-12-03 15:46:59.374 ThaliTest[2472:2307958] jxcore: disconnect: fail
,2015-12-03T14:46:59.375Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03T14:46:59.376Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT1068.V8ys1g== with availability status: true
,2015-12-03T14:46:59.377Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03T14:46:59.377Z SendDataConnector.js: do connect now
,2015-12-03 15:46:59.378 ThaliTest[2472:2307958] jxcore: connect Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:46:59.379 ThaliTest[2472:2307958] client session: connect
2015-12-03 15:46:59.380 ThaliTest[2472:2307958] client session: stateChange:0->1 Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:47:01.796 ThaliTest[2472:2308627] client session: connected
2015-12-03 15:47:01.797 ThaliTest[2472:2308627] client session: stateChange:1->2 Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:47:01.803 ThaliTest[2472:2308627] client session: fireConnectCallback: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:47:01.804 ThaliTest[2472:2308627] jxcore: connect: success
2015-12-03T14:47:01.805Z SendDataConnector.js: CLIENT connected ,to 50497, error: null
2015-12-03T14:47:01.806Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:47:01.810 ThaliTest[2472:2307850] client: relay established
2015-12-03 15:47:01.810 ThaliTest[2472:2307850] client: new accepted socket: 0x18e20e60
,2015-12-03T14:47:01.821Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:47:05.825 ThaliTest[2472:2307850] multipeer session: reset timer
2015-12-03 15:47:05.826 ThaliTest[2472:2307850] multipeer session: stop timer
2015-12-03 15:47:05.826 ThaliTest[2472:2307850] multipeer session: start timer: 0x18d96010
2015-,12-03 15:47:05.827 ThaliTest[2472:2307850] server: disconnecting to refresh session (Apple-Iphone5-1_PT4165)
2015-12-03 15:47:05.827 ThaliTest[2472:2307850] server session: disconnect
2015-12-03 15:47:05.828 ThaliTest[2472:2307850] server session: stateC,hange:2->0 Apple-Iphone5-1_PT4165
2015-12-03 15:47:05.832 ThaliTest[2472:2307850] server session: connect
2015-12-03 15:47:05.832 ThaliTest[2472:2307850] server session: stateChange:0->1 Apple-Iphone5-1_PT4165
,2015-12-03T14:47:05.846Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 15:47:05.853 ThaliTest[2472:2307850] server: accepting invitation Apple-Iphone5-1_PT4165
,2015-12-03 15:47:08.106 ThaliTest[2472:2308627] server session: connected
2015-12-03 15:47:08.107 ThaliTest[2472:2308627] server session: stateChange:1->2 Apple-Iphone5-1_PT4165
,2015-12-03T14:47:08.114Z SendDataTCPServer.js: TCP/IP server connected
2015-12-03 15:47:08.115 ThaliTest[2472:2307850] server relay: connected (to port: 50479)
,2015-12-03T14:47:08.436Z SendDataTCPServer.js: TCP/IP server has received 9920 bytes of data
,2015-12-03T14:47:08.450Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T14:47:11.877Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:47:11.878Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:47:11.878Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:47:11.879Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:47:11.880Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:47:11.881 ThaliTest[2472:2307850] client: socket closed
2015-12-03 15:47:11.882 ThaliTest[2472:2307850] client relay: socket disconnected
2015-12-03 15:47:11.882 ThaliTest[2472:2307850] client relay: 0x18e20e60 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x18c0a8a0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:47:11.883 ThaliTest[2472:2307850] client session: socket closed: Apple-Iphone6-1_PT1068.V8ys1g,==
2015-12-03 15:47:11.884 ThaliTest[2472:2307850] client session: onLinkFailure: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:47:11.884 ThaliTest[2472:2307850] client session: disconnect
2015-12-03 15:47:11.885 ThaliTest[2472:2307850] client session: ,stateChange:2->0 Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:47:11.887 ThaliTest[2472:2307850] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03T14:47:16.886Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03T14:47:16.887Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:47:18.402 ThaliTest[2472:2308628] server session: not connected Apple-Iphone5-1_PT4165
,2015-12-03 15:47:21.896 ThaliTest[2472:2307958] jxcore: disconnect
2015-12-03 15:47:21.897 ThaliTest[2472:2307958] jxcore: disconnect: fail
2015-12-03T14:47:21.898Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1068.V8ys1,g==
2015-12-03T14:47:21.899Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT1068.V8ys1g== with availability status: true
,2015-12-03T14:47:21.899Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03T14:47:21.899Z SendDataConnector.js: do connect now
,2015-12-03 15:47:21.901 ThaliTest[2472:2307958] jxcore: connect Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:47:21.902 ThaliTest[2472:2307958] client session: connect
2015-12-03 15:47:21.902 ThaliTest[2472:2307958] client session: stateChange:0->1 Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:47:24.368 ThaliTest[2472:2308490] client session: connected
2015-12-03 15:47:24.369 ThaliTest[2472:2308490] client session: stateChange:1->2 Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:47:24.377 ThaliTest[2472:2308490] client session: fireConnectCallback: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:47:24.378 ThaliTest[2472:2308490] jxcore: connect: success
2015-12-03T14:47:24.381Z SendDataConnector.js: CLIENT connected to 50501, error: null
,2015-12-03T14:47:24.381Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:47:24.385 ThaliTest[2472:2307850] client: relay established
2015-12-03 15:47:24.386 ThaliTest[2472:2307850] client: new accepted socket: 0x18e28460
,2015-12-03T14:47:24.397Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:47:28.887 ThaliTest[2472:2307850] multipeer session: reset timer
2015-12-03 15:47:28.888 ThaliTest[2472:2307850] multipeer session: stop timer
2015-12-03 15:47:28.888 ThaliTest[2472:2307850] multipeer session: start timer: 0x18d96010
2015-,12-03 15:47:28.889 ThaliTest[2472:2307850] server: disconnecting to refresh session (Apple-Iphone5-1_PT4165)
2015-12-03 15:47:28.890 ThaliTest[2472:2307850] server session: disconnect
2015-12-03 15:47:28.890 ThaliTest[2472:2307850] server session: stateC,hange:2->0 Apple-Iphone5-1_PT4165
2015-12-03 15:47:28.893 ThaliTest[2472:2307850] server session: connect
2015-12-03T14:47:28.899Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 15:47:28.894 ThaliTest[2472:2307850] server session: stateChange:0,->1 Apple-Iphone5-1_PT4165
,2015-12-03 15:47:28.915 ThaliTest[2472:2307850] server: accepting invitation Apple-Iphone5-1_PT4165
,2015-12-03 15:47:31.157 ThaliTest[2472:2308490] server session: connected
2015-12-03 15:47:31.158 ThaliTest[2472:2308490] server session: stateChange:1->2 Apple-Iphone5-1_PT4165
,2015-12-03 15:47:31.165 ThaliTest[2472:2307850] server relay: connected (to port: 50479)
2015-12-03T14:47:31.165Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:47:31.500Z SendDataTCPServer.js: TCP/IP server has received 9920 bytes of data
,2015-12-03T14:47:31.514Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T14:47:34.525Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:47:34.526Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:47:34.527Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:47:34.530Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:47:34.531Z SendDataConnector.js: Stop data retrieving timer
2015-12-03T14:47:34.531Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 15:47:34.532 ThaliTest[2472:2307958] jxcore: disconnect
,2015-12-03 15:47:34.534 ThaliTest[2472:2307958] client session: disconnectFromPeer: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:47:34.535 ThaliTest[2472:2307958] client session: disconnect
2015-12-03 15:47:34.535 ThaliTest[2472:2307958] client session: stateChange:2->0 Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:47:34.597 ThaliTest[2472:2307958] jxcore: disconnect: success
,2015-12-03T14:47:34.599Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1068.V8ys1g==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03T14:47:34.607Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03T14:47:34.609Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03T14:47:34.610Z SendDataConnector.js: do connect now
,2015-12-03 15:47:34.613 ThaliTest[2472:2307958] jxcore: connect Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03 15:47:34.615 ThaliTest[2472:2307958] client session: connect
,2015-12-03 15:47:34.616 ThaliTest[2472:2307958] client session: stateChange:0->1 Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03T14:47:34.622Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:47:41.252 ThaliTest[2472:2308490] server session: not connected Apple-Iphone5-1_PT4165
,2015-12-03 15:47:42.548 ThaliTest[2472:2308516] client session: connected
2015-12-03 15:47:42.548 ThaliTest[2472:2308516] client session: stateChange:1->2 Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03 15:47:42.556 ThaliTest[2472:2308516] client session: fireConnectCallback: Apple-Iphone5-1_PT4165.Uz5DSQ==
2015-12-03 15:47:42.556 ThaliTest[2472:2308516] jxcore: connect: success
2015-12-03T14:47:42.557Z SendDataConnector.js: CLIENT connected to 50505, error: null
,2015-12-03T14:47:42.558Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:47:42.563 ThaliTest[2472:2307850] client: relay established
2015-12-03 15:47:42.563 ThaliTest[2472:2307850] client: new accepted socket: 0x18da8300
,2015-12-03T14:47:42.575Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T14:47:42.897Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-03T14:47:42.922Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-03T14:47:42.934Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-03T14:47:42.934Z SendDataConnector.js: got all data for this round
,2015-12-03T14:47:42.935Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:47:42.935Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03 15:47:42.935 ThaliTest[2472:2307958] jxcore: disconnect
,2015-12-03 15:47:42.935 ThaliTest[2472:2307958] client session: disconnectFromPeer: Apple-Iphone5-1_PT4165.Uz5DSQ==
2015-12-03 15:47:42.936 ThaliTest[2472:2307958] client session: disconnect
2015-12-03 15:47:42.936 ThaliTest[2472:2307958] client session: stateChange:2->0 Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03 15:47:42.938 ThaliTest[2472:2307958] jxcore: disconnect: success
2015-12-03T14:47:42.940Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT4165.Uz5DSQ==
---- round done--------
device[3]: Apple-IpadAir2-1_PT6724.bsoISg==
2015-12-03T14:47:42.941Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03T14:47:42.941Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03T14:47:42.941Z SendDataConnector.js: do connect now
,2015-12-03 15:47:42.941 ThaliTest[2472:2307958] jxcore: connect Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03 15:47:42.942 ThaliTest[2472:2307958] client session: connect
2015-12-03 15:47:42.942 ThaliTest[2472:2307958] client session: stateChange:0->1 Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03 15:47:46.861 ThaliTest[2472:2308516] client session: connected
2015-12-03 15:47:46.862 ThaliTest[2472:2308516] client session: stateChange:1->2 Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03 15:47:46.865 ThaliTest[2472:2308516] client session: fireConnectCallback: Apple-IpadAir2-1_PT6724.bsoISg==
2015-12-03 15:47:46.866 ThaliTest[2472:2308516] jxcore: connect: success
,2015-12-03T14:47:46.869Z SendDataConnector.js: CLIENT connected to 50508, error: null
2015-12-03T14:47:46.869Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:47:46.877 ThaliTest[2472:2307850] client: relay established
2015-12-03 15:47:46.878 ThaliTest[2472:2307850] client: new accepted socket: 0x18a81c50
,2015-12-03T14:47:46.889Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T14:47:47.236Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-03T14:47:47.249Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-03T14:47:47.249Z SendDataConnector.js: got all data for this round
,2015-12-03T14:47:47.250Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:47:47.250Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03 15:47:47.250 ThaliTest[2472:2307958] jxcore: disconnect
2015-12-03 15:47:47.250 ThaliTest[2472:2307958] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6724.bsoISg==
2015-12-03 15:47:47.251 ThaliTest[2472:2307958] client session: disconnect
2015-12-03 15:47:47.251 ThaliTest[2472:2307958] client session: stateChange:2->0 Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03 15:47:47.252 ThaliTest[2472:2307958] jxcore: disconnect: success
2015-12-03T14:47:47.253Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6724.bsoISg==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT2374","time":117641,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT1068.V8ys1g==","time":104649,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name":"Appl,e-Iphone5-1_PT4165.Uz5DSQ==","time":8325,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT6724.bsoISg==","time":4308,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataRe,ceived":100000}]}
sendList : 100% : 8325 ms, 99% : 8325 ms, 95 : 8325 ms, 90% : 8325 ms.
Result count 2, range 4308 ms to  8325 ms.
,sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone6-1_PT1068.V8ys1g==, Tried : 5
sendList never tried peers count : 0 [0 %]
2015-12-03T14:47:47.259Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:47:47.260Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 15:47:58.890 ThaliTest[2472:2307850] multipeer session: restart
,2015-12-03 15:47:58.978 ThaliTest[2472:2307850] client: found peer: Apple-IpadAir2-1_PT6724.bsoISg==
2015-12-03 15:47:58.979 ThaliTest[2472:2307850] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:47:58.980 ThaliTest[2472:2307850] clien,t: found peer: Apple-Iphone5-1_PT4165.Uz5DSQ==
2015-12-03 15:47:58.981 ThaliTest[2472:2307850] client: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:48:26.521 ThaliTest[2472:2307850] client: lost peer: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:48:26.521 ThaliTest[2472:2307850] client session: onPeerLost: Apple-Iphone6-1_PT1068.V8ys1g==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT1068.V8ys1g==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 15:48:28.095 ThaliTest[2472:2307850] client: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1068.V8ys1g==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 15:48:28.890 ThaliTest[2472:2307850] multipeer session: restart
,2015-12-03 15:48:28.911 ThaliTest[2472:2307850] client: found peer: Apple-IpadAir2-1_PT6724.bsoISg==
2015-12-03 15:48:28.913 ThaliTest[2472:2307850] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:48:28.913 ThaliTest[2472:2307850] clien,t: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:48:28.915 ThaliTest[2472:2307850] client: found peer: Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03 15:48:56.400 ThaliTest[2472:2307850] client: lost peer: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:48:56.400 ThaliTest[2472:2307850] client session: onPeerLost: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:48:56.401 ThaliTest[2472:2307850], client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1068.V8ys1g==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 15:48:56.410 ThaliTest[2472:2307850] client: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1068.V8ys1g==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 15:48:58.889 ThaliTest[2472:2307850] multipeer session: restart
,2015-12-03 15:48:58.916 ThaliTest[2472:2307850] client: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:48:58.917 ThaliTest[2472:2307850] client: found peer: Apple-IpadAir2-1_PT6724.bsoISg==
2015-12-03 15:48:58.918 ThaliTest[2472:2307850] clien,t: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:48:58.919 ThaliTest[2472:2307850] client: found peer: Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03 15:49:28.888 ThaliTest[2472:2307850] multipeer session: restart
,2015-12-03 15:49:28.918 ThaliTest[2472:2307850] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:49:28.919 ThaliTest[2472:2307850] client: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:49:28.921 ThaliTest[2472:2307850] client: found peer: Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03 15:49:28.922 ThaliTest[2472:2307850] client: found peer: Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03 15:49:33.637 ThaliTest[2472:2307850] client: lost peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:49:33.638 ThaliTest[2472:2307850] client session: onPeerLost: Apple-Iphone6-1_PT7057.4CFLyQ==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 15:49:34.138 ThaliTest[2472:2307850] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-03 15:49:58.197 ThaliTest[2472:2307850] client: lost peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:49:58.197 ThaliTest[2472:2307850] client session: onPeerLost: Apple-Iphone6-1_PT7057.4CFLyQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 15:49:58.888 ThaliTest[2472:2307850] multipeer session: restart
,2015-12-03 15:49:59.005 ThaliTest[2472:2307850] client: found peer: Apple-IpadAir2-1_PT6724.bsoISg==
2015-12-03 15:49:59.006 ThaliTest[2472:2307850] client: found peer: Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03 15:49:59.246 ThaliTest[2472:2307850] client: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:50:00.411 ThaliTest[2472:2307850] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,DBG, CoordinatorConnector command called
command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
,testSendData stopped
,2015-12-03 15:50:04.416 ThaliTest[2472:2307958] jxcore: stopBroadcasting
2015-12-03 15:50:04.417 ThaliTest[2472:2307958] THEMultipeerSession stopping peer
2015-12-03 15:50:04.417 ThaliTest[2472:2307958] multipeer session: stop timer
2015-12-03 15:50:04.,418 ThaliTest[2472:2307958] server session: disconnect
2015-12-03 15:50:04.419 ThaliTest[2472:2307958] server session: stateChange:2->0 Apple-Iphone5-1_PT4165
2015-12-03 15:50:04.429 ThaliTest[2472:2307958] server session: disconnect
2015-12-03 15:50:04,.430 ThaliTest[2472:2307958] server session: stateChange:2->0 Apple-IpadAir2-1_PT6724
,2015-12-03 15:50:04.436 ThaliTest[2472:2307958] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-03T14:50:04.455Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03T14:50:04.457Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03T14:50:04.458Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-IpadAir2-1_PT6724.bsoISg==\",\"time\":4308,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone5-1_PT4165.Uz5DSQ==\",\"time\":8325,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone6-1_PT1068.V8ys1g==\",\"time\":104649,\,"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000}],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called

```
