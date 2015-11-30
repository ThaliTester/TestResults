#### Test 51986340a77003b_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51986340a77003b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/BD14E5E2-9060-411B-9D9C-32A204E1D08F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/BD14E5E2-9060-411B-9D9C-32A204E1D08F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51986340a77003b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51986340a77003b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/85CAB6F8-CDCF-491F-8331-625D8547DDFB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57921"
,(lldb)     command script import "/tmp/BD14E5E2-9060-411B-9D9C-32A204E1D08F/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-30 10:46:28.107 ThaliTest[2077:1926661] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D81EC35C-B8D4-40CC-93E8-18C33D5E70C0/Library/Cookies/Cookies.binarycookies
,2015-11-30 10:46:28.531 ThaliTest[2077:1926661] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-30 10:46:28.532 ThaliTest[2077:1926661] Multi-tasking -> Device: YES, App: YES
,2015-11-30 10:46:28.541 ThaliTest[2077:1926661] Unlimited access to network resources
,2015-11-30 10:46:28.549 ThaliTest[2077:1926661] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-30 10:46:32.046 ThaliTest[2077:1926661] Resetting plugins due to page load.
,2015-11-30 10:46:32.418 ThaliTest[2077:1926661] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/85CAB6F8-CDCF-491F-8331-625D8547DDFB/ThaliTest.app/www/index.html
,2015-11-30 10:46:32.619 ThaliTest[2077:1926661] JXcore Cordova plugin initializing
,2015-11-30 10:46:32.620 ThaliTest[2077:1926781] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
Warning: iOS does not support ToggleBluetooth
Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone5s-1_PT9746
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
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":50000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":50000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 63878
,2015-11-30 10:53:32.243 ThaliTest[2077:1926781] jxcore: startBroadcasting
,2015-11-30 10:53:32.256 ThaliTest[2077:1926781] server: starting Apple-Iphone5s-1_PT9746.l6NbbA==
,2015-11-30 10:53:32.258 ThaliTest[2077:1926781] multipeer session: start timer: 0x19647c90
2015-11-30 10:53:32.258 ThaliTest[2077:1926781] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT9746
2015-11-30 10:53:32.259 ThaliTest[2077:1926781] jxcore: startBroadcasting: success
,StartBroadcasting started ok
2015-11-30T09:53:32.263Z SendDataTCPServer.js: TCP/IP server is bound to port: 63878
,2015-11-30 10:53:32.497 ThaliTest[2077:1926661] client: found peer: Apple-Iphone6-1_PT7971.JDbK/w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7971.JDbK/w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,device[1]: Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:53:32.506Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:53:32.507Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30T09:53:32.507Z SendDataConnector.js: do connect now
,2015-11-30 10:53:32.508 ThaliTest[2077:1926781] jxcore: connect Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30 10:53:32.509 ThaliTest[2077:1926781] client session: connect
2015-11-30 10:53:32.510 ThaliTest[2077:1926781] client session: stateChange:0->1 Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:53:32.761 ThaliTest[2077:1926661] multipeer session: reset timer
2015-11-30 10:53:32.761 ThaliTest[2077:1926661] multipeer session: stop timer
2015-11-30 10:53:32.761 ThaliTest[2077:1926661] multipeer session: start timer: 0x19647c90
2015-11-30 10:53:32.761 ThaliTest[2077:1926661] server session: connect
2015-11-30 10:53:32.762 ThaliTest[2077:1926661] server session: stateChange:0->1 Apple-Iphone6-1_PT7971
2015-11-30 10:53:32.766 ThaliTest[2077:1926661] server: accepting invitation Apple-Iphone6-1_PT7971
,2015-11-30 10:53:33.634 ThaliTest[2077:1926661] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
2015-11-30 10:53:33.635 ThaliTest[2077:1926661] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ipa,dAir2-1_PT7551.0H/lSg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2135.SJMPng==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Availab,le: true
,2015-11-30 10:53:35.004 ThaliTest[2077:1927401] server session: connected
2015-11-30 10:53:35.005 ThaliTest[2077:1927401] server session: stateChange:1->2 Apple-Iphone6-1_PT7971
,2015-11-30 10:53:35.015 ThaliTest[2077:1926661] server relay: connected (to port: 63878)
,2015-11-30T09:53:35.027Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30T09:53:35.379Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-11-30T09:53:35.395Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-11-30T09:53:35.415Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-11-30T09:53:35.439Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-11-30T09:53:35.460Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-30 10:53:35.539 ThaliTest[2077:1927413] server session: not connected Apple-Iphone6-1_PT7971
,2015-11-30 10:53:36.044 ThaliTest[2077:1927407] client session: connected
2015-11-30 10:53:36.045 ThaliTest[2077:1927407] client session: stateChange:1->2 Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30 10:53:36.049 ThaliTest[2077:1927407] client session: fir,eConnectCallback: Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30 10:53:36.050 ThaliTest[2077:1927407] jxcore: connect: success
,2015-11-30T09:53:36.054Z SendDataConnector.js: CLIENT connected to 63883, error: null
,2015-11-30T09:53:36.055Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 10:53:36.060 ThaliTest[2077:1926661] client: relay established
2015-11-30 10:53:36.061 ThaliTest[2077:1926661] client: new accepted socket: 0x196610c0
,2015-11-30T09:53:36.076Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-30T09:53:36.510Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-30T09:53:36.525Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-30T09:53:36.540Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-30T09:53:36.553Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-30T09:53:36.553Z SendDataConnector.js: got all data for this round
,2015-11-30T09:53:36.554Z SendDataConnector.js: CLIENT Stop now
,2015-11-30T09:53:36.555Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 10:53:36.556 ThaliTest[2077:1926781] jxcore: disconnect
,2015-11-30 10:53:36.557 ThaliTest[2077:1926781] client session: disconnectFromPeer: Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:53:36.558 ThaliTest[2077:1926781] client session: disconnect
,2015-11-30 10:53:36.559 ThaliTest[2077:1926781] client session: stateChange:2->0 Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:53:36.615 ThaliTest[2077:1926781] jxcore: disconnect: success
,2015-11-30T09:53:36.616Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7971.JDbK/w==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30T09:53:36.619Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30T09:53:36.620Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30T09:53:36.620Z SendDataConnector.js: do connect now
,2015-11-30 10:53:36.620 ThaliTest[2077:1926781] jxcore: connect Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 10:53:36.621 ThaliTest[2077:1926781] client session: connect
,2015-11-30 10:53:36.622 ThaliTest[2077:1926781] client session: stateChange:0->1 Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 10:53:39.752 ThaliTest[2077:1927401] client session: connected
2015-11-30 10:53:39.753 ThaliTest[2077:1927401] client session: stateChange:1->2 Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 10:53:39.777 ThaliTest[2077:1927409] client session: fireConnectCallback: Apple-IpadAir2-1_PT7551.0H/lSg==
2015-11-30 10:53:39.778 ThaliTest[2077:1927409] jxcore: connect: success
2015-11-30T09:53:39.780Z SendDataConnector.js: CLIENT connected to 63886, error: null
,2015-11-30T09:53:39.780Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 10:53:39.786 ThaliTest[2077:1926661] client: relay established
2015-11-30 10:53:39.787 ThaliTest[2077:1926661] client: new accepted socket: 0x1956e1f0
,2015-11-30T09:53:39.800Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-30T09:53:40.138Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-30T09:53:40.195Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-30T09:53:40.306Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-30T09:53:40.332Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-30T09:53:40.332Z SendDataConnector.js: got all data for this round
,2015-11-30T09:53:40.333Z SendDataConnector.js: CLIENT Stop now
2015-11-30T09:53:40.333Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-30 10:53:40.333 ThaliTest[2077:1926781] jxcore: disconnect
2015-11-30 10:53:40.334 ThaliTest[2077:1926781] cli,ent session: disconnectFromPeer: Apple-IpadAir2-1_PT7551.0H/lSg==
2015-11-30 10:53:40.334 ThaliTest[2077:1926781] client session: disconnect
2015-11-30 10:53:40.334 ThaliTest[2077:1926781] client session: stateChange:2->0 Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 10:53:40.335 ThaliTest[2077:1926781] jxcore: disconnect: success
2015-11-30T09:53:40.335Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7551.0H/lSg==
---- round done--------
device[3]: Apple-Iphone5-1_PT2135.,SJMPng==
2015-11-30T09:53:40.336Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2135.SJMPng==
2015-11-30T09:53:40.337Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2135.SJMPng==
2015-11-30T09:53:40.337Z SendDataCon,nector.js: do connect now
2015-11-30 10:53:40.337 ThaliTest[2077:1926781] jxcore: connect Apple-Iphone5-1_PT2135.SJMPng==
2015-11-30 10:53:40.337 ThaliTest[2077:1926781] client session: connect
,2015-11-30 10:53:40.338 ThaliTest[2077:1926781] client session: stateChange:0->1 Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 10:53:43.357 ThaliTest[2077:1927409] client session: connected
2015-11-30 10:53:43.358 ThaliTest[2077:1927409] client session: stateChange:1->2 Apple-Iphone5-1_PT2135.SJMPng==
,2015-11-30 10:53:43.368 ThaliTest[2077:1927409] client session: fireConnectCallback: Apple-Iphone5-1_PT2135.SJMPng==
2015-11-30 10:53:43.370 ThaliTest[2077:1927409] jxcore: connect: success
2015-11-30T09:53:43.372Z SendDataConnector.js: CLIENT connected ,to 63889, error: null
2015-11-30T09:53:43.372Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 10:53:43.376 ThaliTest[2077:1926661] client: relay established
2015-11-30 10:53:43.377 ThaliTest[2077:1926661] client: new accepted socket: 0x1555d840
,2015-11-30T09:53:43.390Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-30T09:53:43.880Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-30T09:53:43.894Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-30 10:54:02.763 ThaliTest[2077:1926661] multipeer session: restart
,2015-11-30 10:54:02.870 ThaliTest[2077:1926661] client: found peer: Apple-Iphone5-1_PT2135.SJMPng==
2015-11-30 10:54:02.872 ThaliTest[2077:1926661] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
2015-11-30 10:54:02.874 ThaliTest[2077:1926661] client: found peer: Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:54:32.762 ThaliTest[2077:1926661] multipeer session: restart
2015-11-30 10:54:32.768 ThaliTest[2077:1926661] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Fi,rst throw call stack:
(0x2a8a745f 0x3876ac8b 0x2a7c4c53 0x2c829d95 0x2a3c4297 0x2a3c3b11 0x2a33d693 0x2a86dfbf 0x2a86d3cf 0x2a86ba35 0x2a7b93b1 0x2a7b91c3 0x31da6201 0x2de2343d 0x445e3 0x38cf6aaf)
libc++abi.dylib: terminating with uncaught exception of t,ype NSException
,* thread #1: tid = 0x1d6605, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
  * frame #0: 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x38e3ecc6 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x38d5c908 libsystem_c.dylib`abort + 76
    frame #3: 0x3808c9c8 libc++abi.dylib`<redacted> + 88
    frame #4: 0x380a6670 libc++abi.dylib`<redacted> + 268
    frame #5: 0x3876af24 libobjc.A.dylib`<redacted> + 192
    frame #6: 0x380a3de2 libc++abi.dylib`<redacted> + 78
    frame #7: 0x380a38ae libc++abi.dylib`__cxa_rethrow + 102
    frame #8: 0x3876add2 libobjc.A.dylib`objc_exception_rethrow + 42
    frame #9: 0x2a7b944c CoreFoundation`CFRunLoopRunSpecific + 632
    frame #10: 0x2a7b91c2 CoreFoundation`CFRunLoopRunInMode + 106
    frame #11: 0x31da6200 GraphicsServices`GSEventRunModal + 136
    frame #12: 0x2de2343c UIKit`UIApplicationMain + 1440
    frame #13: 0x000445e2 ThaliTest`main + 50

```
