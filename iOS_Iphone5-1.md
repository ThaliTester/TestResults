#### Test 506502787a45a3c_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502787a45a3c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/9D757EF2-C7CF-44A7-9BF5-5F9611860B97/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/9D757EF2-C7CF-44A7-9BF5-5F9611860B97/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502787a45a3c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502787a45a3c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/1B90F707-4E61-4952-94B9-6B09945751C2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56544"
,(lldb)     command script import "/tmp/9D757EF2-C7CF-44A7-9BF5-5F9611860B97/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-27 02:07:36.191 ThaliTest[867:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-27 02:07:36.195 ThaliTest[867:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-27 02:07:36.202 ThaliTest[867:60b] Unlimited access to network resources
,2015-11-27 02:07:36.208 ThaliTest[867:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.appl,e.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-27 02:07:46.884 ThaliTest[867:60b] Resetting plugins due to page load.
,2015-11-27 02:07:47.757 ThaliTest[867:60b] Finished load of: file:///var/mobile/Applications/1B90F707-4E61-4952-94B9-6B09945751C2/ThaliTest.app/www/index.html
,2015-11-27 02:07:47.935 ThaliTest[867:60b] JXcore Cordova plugin initializing
,2015-11-27 02:07:47.937 ThaliTest[867:6907] JXcore instance initializing
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
Radios toggled
,Test app app.js loaded
,CoordinatorConnector-debug: connect:undefined
,CoordinatorConnector-debug: schedule:["multiplex can send data","basic","another","successfully create a new pkcs12 file and return hash value","successfully read a previous pkcs12 file and return hash value","failed to extract public key because of corrup,t pkcs12 file","failed to get mobile documents path","#init should register the peerAvailabilityChanged event","#init should register the networkChanged event","#startBroadcasting should throw on null device name","#startBroadcasting should throw on empty ,string device name","#startBroadcasting should throw on non-number port","#startBroadcasting should throw on NaN port","#startBroadcasting should throw on negative port","#startBroadcasting should throw on too large port","#startBroadcasting should call Mo,bile(\"StartBroadcasting\") without an error","#startBroadcasting should call Mobile(\"StartBroadcasting\") and handle an error","#stopBroadcasting should call Mobile(\"StopBroadcasting\") without an error","#stopBroadcasting should call Mobile(\"StopBroad,casting\") and handle an error","#connect should call Mobile(\"Connect\") with a port and without an error","#connect should call Mobile(\"Connect\") and handle an error","should call Mobile(\"Disconnect\") without an error","should call Mobile(\"Disconnect\") and handle an error"]
,TAP version 13
,# setup
,# multiplex can send data
,CoordinatorConnector-debug: setup:multiplex can send data
,# teardown
,CoordinatorConnector-debug: start_test:multiplex can send data
,ok 1 String should be length:200
,# setup
,CoordinatorConnector-debug: teardown:multiplex can send data
,# basic
,CoordinatorConnector-debug: setup:basic
,# teardown
,CoordinatorConnector-debug: start_test:basic
ok 2 sane
,# setup
,CoordinatorConnector-debug: teardown:basic
,# another
,CoordinatorConnector-debug: setup:another
,# teardown
,CoordinatorConnector-debug: start_test:another
,ok 3 sane
,# setup
,CoordinatorConnector-debug: teardown:another
,# successfully create a new pkcs12 file and return hash value
,CoordinatorConnector-debug: setup:successfully create a new pkcs12 file and return hash value
,# teardown
,CoordinatorConnector-debug: start_test:successfully create a new pkcs12 file and return hash value
,ok 4 should be equal
,ok 5 null
,ok 6 (unnamed assert)
,ok 7 should be equal
,ok 8 should not throw
,# setup
,CoordinatorConnector-debug: teardown:successfully create a new pkcs12 file and return hash value
,# successfully read a previous pkcs12 file and return hash value
,CoordinatorConnector-debug: setup:successfully read a previous pkcs12 file and return hash value
,# teardown
,CoordinatorConnector-debug: start_test:successfully read a previous pkcs12 file and return hash value
,ok 9 (unnamed assert)
,ok 10 (unnamed assert)
,ok 11 should not throw
,ok 12 should be equal
,ok 13 should be equal
,# setup
,CoordinatorConnector-debug: teardown:successfully read a previous pkcs12 file and return hash value
,# failed to extract public key because of corrupt pkcs12 file
,CoordinatorConnector-debug: setup:failed to extract public key because of corrupt pkcs12 file
,# teardown
,CoordinatorConnector-debug: start_test:failed to extract public key because of corrupt pkcs12 file
,ok 14 should be equal
,# setup
,CoordinatorConnector-debug: teardown:failed to extract public key because of corrupt pkcs12 file
,# failed to get mobile documents path
,CoordinatorConnector-debug: setup:failed to get mobile documents path
,# teardown
,CoordinatorConnector-debug: start_test:failed to get mobile documents path
,ok 15 should be equal
,# setup
,CoordinatorConnector-debug: teardown:failed to get mobile documents path
,# #init should register the peerAvailabilityChanged event
,CoordinatorConnector-debug: setup:#init should register the peerAvailabilityChanged event
,# teardown
,CoordinatorConnector-debug: start_test:#init should register the peerAvailabilityChanged event
,ok 16 should be equal
,ok 17 should be equal
,ok 18 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#init should register the peerAvailabilityChanged event
,# #init should register the networkChanged event
,CoordinatorConnector-debug: setup:#init should register the networkChanged event
,# teardown
,CoordinatorConnector-debug: start_test:#init should register the networkChanged event
,ok 19 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#init should register the networkChanged event
,# #startBroadcasting should throw on null device name
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on null device name
,# teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on null device name
,ok 20 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on null device name
,# #startBroadcasting should throw on empty string device name
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on empty string device name
,# teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on empty string device name
,ok 21 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on empty string device name
,# #startBroadcasting should throw on non-number port
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on non-number port
,# teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on non-number port
,ok 22 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on non-number port
,# #startBroadcasting should throw on NaN port
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on NaN port
,# teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on NaN port
,ok 23 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on NaN port
,# #startBroadcasting should throw on negative port
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on negative port
,# teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on negative port
,ok 24 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on negative port
,# #startBroadcasting should throw on too large port
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on too large port
,# teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on too large port
,ok 25 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on too large port
,# #startBroadcasting should call Mobile("StartBroadcasting") without an error
,CoordinatorConnector-debug: setup:#startBroadcasting should call Mobile("StartBroadcasting") without an error
,# teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should call Mobile("StartBroadcasting") without an error
,ok 26 should be equal
,ok 27 should be equal
,ok 28 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should call Mobile("StartBroadcasting") without an error
,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,CoordinatorConnector-debug: setup:#startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,# teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,ok 29 should be equal
,ok 30 should be equal
,ok 31 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error
,CoordinatorConnector-debug: setup:#stopBroadcasting should call Mobile("StopBroadcasting") without an error
,# teardown
,CoordinatorConnector-debug: start_test:#stopBroadcasting should call Mobile("StopBroadcasting") without an error
,ok 32 should be equal
,ok 33 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#stopBroadcasting should call Mobile("StopBroadcasting") without an error
,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,CoordinatorConnector-debug: setup:#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,# teardown
,CoordinatorConnector-debug: start_test:#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,ok 34 should be equal
,ok 35 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,# #connect should call Mobile("Connect") with a port and without an error
,CoordinatorConnector-debug: setup:#connect should call Mobile("Connect") with a port and without an error
,# teardown
,CoordinatorConnector-debug: start_test:#connect should call Mobile("Connect") with a port and without an error
,ok 36 should be equal
,ok 37 should be equal
,ok 38 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#connect should call Mobile("Connect") with a port and without an error
,# #connect should call Mobile("Connect") and handle an error
,CoordinatorConnector-debug: setup:#connect should call Mobile("Connect") and handle an error
,# teardown
,CoordinatorConnector-debug: start_test:#connect should call Mobile("Connect") and handle an error
,ok 39 should be equal
,ok 40 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#connect should call Mobile("Connect") and handle an error
,# should call Mobile("Disconnect") without an error
,CoordinatorConnector-debug: setup:should call Mobile("Disconnect") without an error
,# teardown
,CoordinatorConnector-debug: start_test:should call Mobile("Disconnect") without an error
,ok 41 should be equal
,ok 42 should be equal
,# setup
,CoordinatorConnector-debug: teardown:should call Mobile("Disconnect") without an error
,# should call Mobile("Disconnect") and handle an error
,CoordinatorConnector-debug: setup:should call Mobile("Disconnect") and handle an error
,# teardown
,CoordinatorConnector-debug: start_test:should call Mobile("Disconnect") and handle an error
ok 43 should be equal
ok 44 should be equal
,Total: 0	Passed: 0	Failed: 0
Toggling radios to false
,2015-11-27 02:08:05.030 ThaliTest[867:6907] Error!: Mobile.toggleBluetooth is not a function
Stack:[{"_fileName":"/private/var/mobile/Applications/1B90F707-4E61-4952-94B9-6B09945751C2/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName":"exports.tog,gleBluetooth","_lineNumber":"32","_columnNumber":"3","_msg":"    at exports.toggleBluetooth@/private/var/mobile/Applications/1B90F707-4E61-4952-94B9-6B09945751C2/ThaliTest.app/www/jxcore/lib/testUtils.js:32:3"},{"_fileName":"/private/var/mobile/Application,s/1B90F707-4E61-4952-94B9-6B09945751C2/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName":"exports.toggleRadios","_lineNumber":"15","_columnNumber":"3","_msg":"    at exports.toggleRadios@/private/var/mobile/Applications/1B90F707-4E61-4952-94B9-6B0,9945751C2/ThaliTest.app/www/jxcore/lib/testUtils.js:15:3"},{"_fileName":"/private/var/mobile/Applications/1B90F707-4E61-4952-94B9-6B09945751C2/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"createStream/<","_lineNumber":"184","_columnNumber":,"5","_msg":"    at createStream/<@/private/var/mobile/Applications/1B90F707-4E61-4952-94B9-6B09945751C2/ThaliTest.app/www/jxcore/lib/thali-tape.js:184:5"},{"_fileName":"events.js","_functionName":"emit","_lineNumber":"98","_columnNumber":"7","_msg":"    at, emit@events.js:98:7"},{"_fileName":"/private/var/mobile/Applications/1B90F707-4E61-4952-94B9-6B09945751C2/ThaliTest.app/www/jxcore/node_modules/tape/node_modules/through/index.js","_functionName":"drain","_lineNumber":"34","_columnNumber":"16","_msg":"   , at drain@/private/var/mobile/Applications/1B90F707-4E61-4952-94B9-6B09945751C2/ThaliTest.app/www/jxcore/node_modules/tape/node_modules/through/index.js:34:16"},{"_fileName":"/private/var/mobile/Applications/1B90F707-4E61-4952-94B9-6B09945751C2/ThaliTest.a,pp/www/jxcore/node_modules/tape/node_modules/through/index.js","_functionName":"through/stream.push","_lineNumber":"45","_columnNumber":"5","_msg":"    at through/stream.push@/private/var/mobile/Applications/1B90F707-4E61-4952-94B9-6B09945751C2/ThaliTest.a,pp/www/jxcore/node_modules/tape/node_modules/through/index.js:45:5"},{"_fileName":"/private/var/mobile/Applications/1B90F707-4E61-4952-94B9-6B09945751C2/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js","_functionName":"Results.prototype.createStr,eam/<","_lineNumber":"59","_columnNumber":"39","_msg":"    at Results.prototype.createStream/<@/private/var/mobile/Applications/1B90F707-4E61-4952-94B9-6B09945751C2/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:59:39"},{"_fileName":"events.js",,"_functionName":"emit","_lineNumber":"79","_columnNumber":"9","_msg":"    at emit@events.js:79:9"},{"_fileName":"/private/var/mobile/Applications/1B90F707-4E61-4952-94B9-6B09945751C2/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js","_functionName,":"next","_lineNumber":"73","_columnNumber":"9","_msg":"    at next@/private/var/mobile/Applications/1B90F707-4E61-4952-94B9-6B09945751C2/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:73:9"}]
Uncaught Exception: TypeError: Mobile.toggleBluetoo,th is not a function
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
