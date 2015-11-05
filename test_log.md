#### Test 49526184cd4fb85 Logs

Status: 
```

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":20,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_49526184cd4fb85/Sub/serverApp/index.js',
  '{"devices":{"android":20,"cancel":1}}' ]

JSON { devices: { android: 20, cancel: 1 } }



android : false
```


#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":20,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_49526184cd4fb85/Sub/serverApp/index.js',
  '{"devices":{"android":20,"cancel":1}}' ]

JSON { devices: { android: 20, cancel: 1 } }


```

###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
Device test finished on W3D7N15428022572 
STOP log received from  03157df360a1882a Test has  SUCCEEDED
Device test finished on 03157df360a1882a 
STOP log received from  30049d9501da2100 Test has  SUCCEEDED
Device test finished on 30049d9501da2100 
Android task is completed 
```

Logcat output:
```
samsung-SM-G920F: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log( 5242): Initializing JXcore engine
W/jxcore-log( 5242): JXcore engine is ready
,W/jxcore-log( 5242): Starting JXcore engine
,W/jxcore-log( 5242): Platform android
W/jxcore-log( 5242): 
W/jxcore-log( 5242): Process ARCH arm
W/jxcore-log( 5242): 
,I/jxcore-log( 5242): JXcore Cordova bridge is ready!
I/jxcore-log( 5242): 
W/jxcore-log( 5242): JXcore engine is started
,E/jxcore-log( 5242): >> samsung-SM-G920F
E/jxcore-log( 5242): 
,I/jxcore-log( 5242): Total memory 2829074432
I/jxcore-log( 5242): 
I/jxcore-log( 5242): Free memory 237600768
I/jxcore-log( 5242): 
I/jxcore-log( 5242): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5242): 
I/jxcore-log( 5242): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5242): 
,I/jxcore-log( 5242): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 5242): 
,I/jxcore-log( 5242): Size 1440 2560
I/jxcore-log( 5242): 
,I/jxcore-log( 5242): Screen Brightness 255
I/jxcore-log( 5242): 
E/jxcore-log( 5242): Dummy Error Log.
E/jxcore-log( 5242): 
,I/jxcore-log( 5242): getBuffer is called!!!!
I/jxcore-log( 5242): 
,I/jxcore-log( 5242): Bluetooth turned on
I/jxcore-log( 5242): 
,I/jxcore-log( 5242): WiFi turned off
I/jxcore-log( 5242): 
,I/jxcore-log( 5242): WiFi turned on
I/jxcore-log( 5242): 
,I/jxcore-log( 5242): No internet connection
I/jxcore-log( 5242): 
,I/jxcore-log( 5242): No internet connection
I/jxcore-log( 5242): 
,I/jxcore-log( 5242): No internet connection
I/jxcore-log( 5242): 
,I/jxcore-log( 5242): No internet connection
I/jxcore-log( 5242): 
,I/jxcore-log( 5242): No internet connection
I/jxcore-log( 5242): 
,I/jxcore-log( 5242): WiFi
I/jxcore-log( 5242): 
,I/jxcore-log( 5242): Response status code was: 200
I/jxcore-log( 5242): 
,I/jxcore-log( 5242): ****TEST TOOK:  11355  ms ****
I/jxcore-log( 5242): 
I/jxcore-log( 5242): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5242): 


samsung-SM-T232: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
W/jxcore-log(12891): Initializing JXcore engine
W/jxcore-log(12891): JXcore engine is ready
W/jxcore-log(12891): Starting JXcore engine
,W/jxcore-log(12891): Platform android
W/jxcore-log(12891): 
W/jxcore-log(12891): Process ARCH arm
W/jxcore-log(12891): 
I/jxcore-log(12891): JXcore Cordova bridge is ready!
I/jxcore-log(12891): 
W/jxcore-log(12891): JXcore engine is started
E/jxcore-log(12891): >> samsung-SM-T232
E/jxcore-log(12891): 
I/jxcore-log(12891): Total memory 1352024064
I/jxcore-log(12891): 
I/jxcore-log(12891): Free memory 220999680
I/jxcore-log(12891): 
I/jxcore-log(12891): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(12891): 
I/jxcore-log(12891): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(12891): 
I/jxcore-log(12891): userPath [ 'www' ]
I/jxcore-log(12891): 
I/jxcore-log(12891): Size 800 1280
I/jxcore-log(12891): 
I/jxcore-log(12891): Screen Brightness 255
I/jxcore-log(12891): 
E/jxcore-log(12891): Dummy Error Log.
E/jxcore-log(12891): 
,I/jxcore-log(12891): getBuffer is called!!!!
I/jxcore-log(12891): 
,I/jxcore-log(12891): Bluetooth turned on
I/jxcore-log(12891): 
I/jxcore-log(12891): WiFi turned off
I/jxcore-log(12891): 
I/jxcore-log(12891): WiFi turned on
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): Timeout in log.js file reached!
I/jxcore-log(12891): 
I/jxcore-log(12891): ****TEST TOOK:  125111  ms ****
I/jxcore-log(12891): 
,I/jxcore-log(12891): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILURE]****
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 
,I/jxcore-log(12891): No internet connection
I/jxcore-log(12891): 


LGE-LG-H815: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(21287): Initializing JXcore engine
W/jxcore-log(21287): JXcore engine is ready
W/jxcore-log(21287): Starting JXcore engine
W/jxcore-log(21287): Platform android
W/jxcore-log(21287): 
W/jxcore-log(21287): Process ARCH arm
W/jxcore-log(21287): 
I/jxcore-log(21287): JXcore Cordova bridge is ready!
I/jxcore-log(21287): 
W/jxcore-log(21287): JXcore engine is started
E/jxcore-log(21287): >> LGE-LG-H815
E/jxcore-log(21287): 
I/jxcore-log(21287): Total memory 2968948736
I/jxcore-log(21287): 
I/jxcore-log(21287): Free memory 267706368
I/jxcore-log(21287): 
I/jxcore-log(21287): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21287): 
I/jxcore-log(21287): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21287): 
I/jxcore-log(21287): userPath [ 'www' ]
I/jxcore-log(21287): 
I/jxcore-log(21287): Size 1440 2392
I/jxcore-log(21287): 
I/jxcore-log(21287): Screen Brightness 255
I/jxcore-log(21287): 
E/jxcore-log(21287): Dummy Error Log.
E/jxcore-log(21287): 
,I/jxcore-log(21287): getBuffer is called!!!!
I/jxcore-log(21287): 
,I/jxcore-log(15361): DBG, CoordinatorConnector connect_error called
I/jxcore-log(15361): 
,I/jxcore-log(15361): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(15361): 
I/jxcore-log(15361): printNetworkInfo
I/jxcore-log(15361): 
,I/jxcore-log(15361): found interfaceName: lo
I/jxcore-log(15361): 
I/jxcore-log(15361): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(15361): 
,I/jxcore-log(15361): found interfaceName: wlan0
I/jxcore-log(15361): 
I/jxcore-log(15361): -iface: IPv4 is internal : false, has ip: 192.168.1.143
I/jxcore-log(15361): 
,I/jxcore-log(15361): DBG, CoordinatorConnector connect_error called
I/jxcore-log(15361): 
,I/jxcore-log(15361): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(15361): 
I/jxcore-log(15361): printNetworkInfo
I/jxcore-log(15361): 
,I/jxcore-log(15361): found interfaceName: lo
I/jxcore-log(15361): 
I/jxcore-log(15361): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(15361): 
I/jxcore-log(15361): found interfaceName: wlan0
I/jxcore-log(15361): 
I/jxcore-log(15361): -iface: IPv4 is internal : false, has ip: 192.168.1.143
I/jxcore-log(15361): 
,I/jxcore-log(21287): Bluetooth turned on
I/jxcore-log(21287): 
I/jxcore-log(21287): WiFi turned off
I/jxcore-log(21287): 
I/jxcore-log(21287): WiFi turned on
I/jxcore-log(21287): 
,I/jxcore-log(21287): No internet connection
I/jxcore-log(21287): 
,I/jxcore-log(15361): DBG, CoordinatorConnector connect_error called
I/jxcore-log(15361): 
,I/jxcore-log(15361): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(15361): 
I/jxcore-log(15361): printNetworkInfo
I/jxcore-log(15361): 
,I/jxcore-log(21287): No internet connection
I/jxcore-log(21287): 
,I/jxcore-log(15361): found interfaceName: lo
I/jxcore-log(15361): 
,I/jxcore-log(15361): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(15361): 
,I/jxcore-log(15361): DBG, CoordinatorConnector connect_error called
I/jxcore-log(15361): 
,I/jxcore-log(15361): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(15361): 
I/jxcore-log(15361): printNetworkInfo
I/jxcore-log(15361): 
I/jxcore-log(15361): found interfaceName: lo
I/jxcore-log(15361): 
I/jxcore-log(15361): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(15361): 
,I/jxcore-log(21287): No internet connection
I/jxcore-log(21287): 
,I/jxcore-log(21287): No internet connection
I/jxcore-log(21287): 
,I/jxcore-log(21287): No internet connection
I/jxcore-log(21287): 
,I/jxcore-log(21287): No internet connection
I/jxcore-log(21287): 
,I/jxcore-log(21287): WiFi
I/jxcore-log(21287): 
,I/jxcore-log(21287): Response status code was: 200
I/jxcore-log(21287): 
I/jxcore-log(21287): ****TEST TOOK:  12481  ms ****
I/jxcore-log(21287): 
I/jxcore-log(21287): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(21287): 
,I/jxcore-log(15361): DBG, CoordinatorConnector connect_error called
I/jxcore-log(15361): 
,I/jxcore-log(15361): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(15361): 
I/jxcore-log(15361): printNetworkInfo
I/jxcore-log(15361): 
I/jxcore-log(15361): found interfaceName: lo
I/jxcore-log(15361): 
I/jxcore-log(15361): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(15361): 
I/jxcore-log(15361): found interfaceName: wlan0
I/jxcore-log(15361): 
I/jxcore-log(15361): -iface: IPv4 is internal : false, has ip: 192.168.1.143
I/jxcore-log(15361): 
,I/jxcore-log(15361): DBG, CoordinatorConnector connect_error called
I/jxcore-log(15361): 
I/jxcore-log(15361): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(15361): 
I/jxcore-log(15361): printNetworkInfo
I/jxcore-log(15361): 
,I/jxcore-log(15361): found interfaceName: lo
I/jxcore-log(15361): 
I/jxcore-log(15361): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(15361): 
I/jxcore-log(15361): found interfaceName: wlan0
I/jxcore-log(15361): 
I/jxcore-log(15361): -iface: IPv4 is internal : false, has ip: 192.168.1.143
I/jxcore-log(15361): 
,I/jxcore-log(15361): DBG, CoordinatorConnector connect_error called
I/jxcore-log(15361): 
I/jxcore-log(15361): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(15361): 
I/jxcore-log(15361): printNetworkInfo
I/jxcore-log(15361): 
,I/jxcore-log(15361): found interfaceName: lo
I/jxcore-log(15361): 
I/jxcore-log(15361): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(15361): 
I/jxcore-log(15361): found interfaceName: wlan0
I/jxcore-log(15361): 
I/jxcore-log(15361): -iface: IPv4 is internal : false, has ip: 192.168.1.143
I/jxcore-log(15361): 


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
,W/jxcore-log(31342): Initializing JXcore engine
W/jxcore-log(31342): JXcore engine is ready
,W/jxcore-log(31342): Starting JXcore engine
,W/jxcore-log(31342): Platform android
W/jxcore-log(31342): 
W/jxcore-log(31342): Process ARCH arm
W/jxcore-log(31342): 
,I/jxcore-log(31342): JXcore Cordova bridge is ready!
I/jxcore-log(31342): 
W/jxcore-log(31342): JXcore engine is started
,E/jxcore-log(31342): >> HUAWEI-ALE-L21
E/jxcore-log(31342): 
,I/jxcore-log(31342): Total memory 1949741056
I/jxcore-log(31342): 
,I/jxcore-log(31342): Free memory 177520640
I/jxcore-log(31342): 
I/jxcore-log(31342): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(31342): 
I/jxcore-log(31342): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(31342): 
,I/jxcore-log(31342): userPath [ 'www' ]
I/jxcore-log(31342): 
,I/jxcore-log(31342): Size 720 1184
I/jxcore-log(31342): 
,I/jxcore-log(31342): Screen Brightness 242
I/jxcore-log(31342): 
,E/jxcore-log(31342): Dummy Error Log.
E/jxcore-log(31342): 
,I/jxcore-log(31342): getBuffer is called!!!!
I/jxcore-log(31342): 
,I/jxcore-log(31342): Bluetooth turned on
I/jxcore-log(31342): 
,I/jxcore-log(31342): WiFi turned off
I/jxcore-log(31342): 
,I/jxcore-log(31342): WiFi turned on
I/jxcore-log(31342): 
,I/jxcore-log(31342): No internet connection
I/jxcore-log(31342): 
,I/jxcore-log(31342): No internet connection
I/jxcore-log(31342): 
,I/jxcore-log(31342): No internet connection
I/jxcore-log(31342): 
,I/jxcore-log(31342): No internet connection
I/jxcore-log(31342): 
,I/jxcore-log(31342): No internet connection
I/jxcore-log(31342): 
,I/jxcore-log(31342): No internet connection
I/jxcore-log(31342): 
,I/jxcore-log(31342): No internet connection
I/jxcore-log(31342): 
,I/jxcore-log(31342): WiFi
I/jxcore-log(31342): 
,I/jxcore-log(31342): Response status code was: 200
I/jxcore-log(31342): 
I/jxcore-log(31342): ****TEST TOOK:  13412  ms ****
I/jxcore-log(31342): 
I/jxcore-log(31342): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(31342): 


```

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 6056): Initializing JXcore engine
W/jxcore-log( 6056): JXcore engine is ready
,W/jxcore-log( 6056): Starting JXcore engine
,W/jxcore-log( 6056): Platform android
W/jxcore-log( 6056): 
W/jxcore-log( 6056): Process ARCH arm
W/jxcore-log( 6056): 
,I/jxcore-log( 6056): JXcore Cordova bridge is ready!
I/jxcore-log( 6056): 
W/jxcore-log( 6056): JXcore engine is started
,E/jxcore-log( 6056): >> LGE-Nexus 5
E/jxcore-log( 6056): 
I/jxcore-log( 6056): Total memory 1946181632
I/jxcore-log( 6056): 
I/jxcore-log( 6056): Free memory 325992448
I/jxcore-log( 6056): 
I/jxcore-log( 6056): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6056): 
I/jxcore-log( 6056): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): userPath [ 'www' ]
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): Size 1080 1776
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): Screen Brightness 82
I/jxcore-log( 6056): 
,E/jxcore-log( 6056): Dummy Error Log.
E/jxcore-log( 6056): 
,I/jxcore-log( 6056): getBuffer is called!!!!
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): Bluetooth turned on
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): WiFi turned off
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): WiFi turned on
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): Timeout in log.js file reached!
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): ****TEST TOOK:  125158  ms ****
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILURE]****
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): No internet connection
I/jxcore-log( 6056): 


LGE-LG-D722: 
--------- beginning of main
--------- beginning of system
W/jxcore-log( 2719): Initializing JXcore engine
W/jxcore-log( 2719): JXcore engine is ready
W/jxcore-log( 2719): Starting JXcore engine
W/jxcore-log( 2719): Platform android
W/jxcore-log( 2719): 
W/jxcore-log( 2719): Process ARCH arm
W/jxcore-log( 2719): 
I/jxcore-log( 2719): JXcore Cordova bridge is ready!
I/jxcore-log( 2719): 
W/jxcore-log( 2719): JXcore engine is started
E/jxcore-log( 2719): >> LGE-LG-D722
E/jxcore-log( 2719): 
I/jxcore-log( 2719): Total memory 906309632
I/jxcore-log( 2719): 
I/jxcore-log( 2719): Free memory 16363520
I/jxcore-log( 2719): 
I/jxcore-log( 2719): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2719): 
I/jxcore-log( 2719): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2719): 
I/jxcore-log( 2719): userPath [ 'www' ]
I/jxcore-log( 2719): 
I/jxcore-log( 2719): Size 720 1196
I/jxcore-log( 2719): 
I/jxcore-log( 2719): Screen Brightness 255
I/jxcore-log( 2719): 
E/jxcore-log( 2719): Dummy Error Log.
E/jxcore-log( 2719): 
I/jxcore-log( 2719): getBuffer is called!!!!
I/jxcore-log( 2719): 
I/jxcore-log( 2719): Bluetooth toggled
I/jxcore-log( 2719): 
I/jxcore-log( 2719): WiFi toggled
I/jxcore-log( 2719): 
I/jxcore-log( 2719): WiFi
I/jxcore-log( 2719): 
I/jxcore-log( 2719): Response status code was: 200
I/jxcore-log( 2719): 
I/jxcore-log( 2719): ****TEST TOOK:  6246  ms ****
I/jxcore-log( 2719): 
I/jxcore-log( 2719): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2719): 
,W/jxcore-log( 4052): Initializing JXcore engine
W/jxcore-log( 4052): JXcore engine is ready
W/jxcore-log( 4052): Starting JXcore engine
W/jxcore-log( 4052): Platform android
W/jxcore-log( 4052): 
W/jxcore-log( 4052): Process ARCH arm
W/jxcore-log( 4052): 
I/jxcore-log( 4052): JXcore Cordova bridge is ready!
I/jxcore-log( 4052): 
W/jxcore-log( 4052): JXcore engine is started
,W/jxcore-log( 5760): Initializing JXcore engine
,W/jxcore-log( 5760): JXcore engine is ready
,W/jxcore-log( 5760): Starting JXcore engine
,W/jxcore-log( 5760): Platform android
W/jxcore-log( 5760): 
W/jxcore-log( 5760): Process ARCH arm
W/jxcore-log( 5760): 
I/jxcore-log( 5760): JXcore Cordova bridge is ready!
I/jxcore-log( 5760): 
W/jxcore-log( 5760): JXcore engine is started
E/jxcore-log( 5760): >> LGE-LG-D722
E/jxcore-log( 5760): 
I/jxcore-log( 5760): Total memory 906309632
I/jxcore-log( 5760): 
I/jxcore-log( 5760): Free memory 24268800
I/jxcore-log( 5760): 
I/jxcore-log( 5760): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5760): 
I/jxcore-log( 5760): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5760): 
I/jxcore-log( 5760): userPath [ 'www' ]
I/jxcore-log( 5760): 
I/jxcore-log( 5760): Size 720 1196
I/jxcore-log( 5760): 
I/jxcore-log( 5760): Screen Brightness 255
I/jxcore-log( 5760): 
E/jxcore-log( 5760): Dummy Error Log.
E/jxcore-log( 5760): 


```

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
Device test finished on 320414cd475f91e3 
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
Android task is completed 
```

Logcat output:
```
motorola-XT1039: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log(17902): Initializing JXcore engine
,W/jxcore-log(17902): JXcore engine is ready
,W/jxcore-log(17902): Starting JXcore engine
,W/jxcore-log(17902): Platform android
W/jxcore-log(17902): 
,W/jxcore-log(17902): Process ARCH arm
W/jxcore-log(17902): 
,I/jxcore-log(17902): JXcore Cordova bridge is ready!
I/jxcore-log(17902): 
,W/jxcore-log(17902): JXcore engine is started
,E/jxcore-log(17902): >> motorola-XT1039
E/jxcore-log(17902): 
I/jxcore-log(17902): Total memory 893136896
I/jxcore-log(17902): 
I/jxcore-log(17902): Free memory 50364416
I/jxcore-log(17902): 
I/jxcore-log(17902): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(17902): 
,I/jxcore-log(17902): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(17902): 
,I/jxcore-log(17902): userPath [ 'www' ]
I/jxcore-log(17902): 
,I/jxcore-log(17902): Size 720 1184
I/jxcore-log(17902): 
I/jxcore-log(17902): Screen Brightness 210
I/jxcore-log(17902): 
,E/jxcore-log(17902): Dummy Error Log.
E/jxcore-log(17902): 
,I/jxcore-log(17902): getBuffer is called!!!!
I/jxcore-log(17902): 
,I/jxcore-log(17902): Bluetooth turned on
I/jxcore-log(17902): 
,I/jxcore-log(17902): WiFi turned off
I/jxcore-log(17902): 
,I/jxcore-log(17902): WiFi turned on
I/jxcore-log(17902): 
,I/jxcore-log(17902): No internet connection
I/jxcore-log(17902): 
,I/jxcore-log(17902): No internet connection
I/jxcore-log(17902): 
,I/jxcore-log(17902): No internet connection
I/jxcore-log(17902): 
,I/jxcore-log(17902): No internet connection
I/jxcore-log(17902): 
,I/jxcore-log(17902): WiFi
I/jxcore-log(17902): 
,I/jxcore-log(17902): Response status code was: 200
I/jxcore-log(17902): 
I/jxcore-log(17902): ****TEST TOOK:  10329  ms ****
I/jxcore-log(17902): 
,I/jxcore-log(17902): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(17902): 


LGE-LG-D855: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(15361): Initializing JXcore engine
W/jxcore-log(15361): JXcore engine is ready
W/jxcore-log(15361): Starting JXcore engine
W/jxcore-log(15361): Platform android
W/jxcore-log(15361): 
W/jxcore-log(15361): Process ARCH arm
W/jxcore-log(15361): 
I/jxcore-log(15361): JXcore Cordova bridge is ready!
I/jxcore-log(15361): 
W/jxcore-log(15361): JXcore engine is started
,E/jxcore-log(15361): >> LGE-LG-D855
E/jxcore-log(15361): 
,I/jxcore-log(15361): Total memory 2995761152
I/jxcore-log(15361): 
I/jxcore-log(15361): Free memory 311504896
I/jxcore-log(15361): 
I/jxcore-log(15361): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(15361): 
I/jxcore-log(15361): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(15361): 
I/jxcore-log(15361): userPath [ 'www' ]
I/jxcore-log(15361): 
I/jxcore-log(15361): Size 1440 2392
I/jxcore-log(15361): 
I/jxcore-log(15361): Screen Brightness 177
I/jxcore-log(15361): 
E/jxcore-log(15361): Dummy Error Log.
E/jxcore-log(15361): 
I/jxcore-log(15361): getBuffer is called!!!!
I/jxcore-log(15361): 
,I/jxcore-log(15361): Bluetooth turned on
I/jxcore-log(15361): 
,I/jxcore-log(15361): WiFi turned off
I/jxcore-log(15361): 
,I/jxcore-log(15361): WiFi turned on
I/jxcore-log(15361): 
,I/jxcore-log(15361): No internet connection
I/jxcore-log(15361): 
,I/jxcore-log(15361): No internet connection
I/jxcore-log(15361): 
,I/jxcore-log(15361): WiFi
I/jxcore-log(15361): 
,I/jxcore-log(15361): Response status code was: 200
I/jxcore-log(15361): 
,I/jxcore-log(15361): ****TEST TOOK:  8542  ms ****
I/jxcore-log(15361): 
I/jxcore-log(15361): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(15361): 


samsung-SM-G800F: 
--------- beginning of /dev/log/main
,I/jxcore-log(20670): DBG, CoordinatorConnector connect_error called
I/jxcore-log(20670): 
I/jxcore-log(20670): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(20670): 
I/jxcore-log(20670): printNetworkInfo
I/jxcore-log(20670): 
I/jxcore-log(20670): found interfaceName: lo
I/jxcore-log(20670): 
I/jxcore-log(20670): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(20670): 
I/jxcore-log(20670): DBG, CoordinatorConnector connect_error called
I/jxcore-log(20670): 
I/jxcore-log(20670): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(20670): 
I/jxcore-log(20670): printNetworkInfo
I/jxcore-log(20670): 
I/jxcore-log(20670): found interfaceName: lo
I/jxcore-log(20670): 
I/jxcore-log(20670): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(20670): 
--------- beginning of /dev/log/system
,W/jxcore-log(26059): Initializing JXcore engine
,W/jxcore-log(26059): JXcore engine is ready
,W/jxcore-log(26059): Starting JXcore engine
,W/jxcore-log(26059): Platform android
W/jxcore-log(26059): 
,W/jxcore-log(26059): Process ARCH arm
W/jxcore-log(26059): 
,I/jxcore-log(26059): JXcore Cordova bridge is ready!
I/jxcore-log(26059): 
,W/jxcore-log(26059): JXcore engine is started
,E/jxcore-log(26059): >> samsung-SM-G800F
E/jxcore-log(26059): 
,I/jxcore-log(26059): Total memory 1319530496
I/jxcore-log(26059): 
I/jxcore-log(26059): Free memory 33488896
I/jxcore-log(26059): 
I/jxcore-log(26059): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(26059): 
,I/jxcore-log(26059): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(26059): 
,I/jxcore-log(26059): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(26059): 
,I/jxcore-log(26059): Size 720 1280
I/jxcore-log(26059): 
,I/jxcore-log(26059): Screen Brightness 255
I/jxcore-log(26059): 
,E/jxcore-log(26059): Dummy Error Log.
E/jxcore-log(26059): 
,I/jxcore-log(26059): getBuffer is called!!!!
I/jxcore-log(26059): 
,I/jxcore-log(20670): DBG, CoordinatorConnector connect_error called
I/jxcore-log(20670): 
I/jxcore-log(20670): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(20670): 
,I/jxcore-log(20670): printNetworkInfo
I/jxcore-log(20670): 
I/jxcore-log(20670): found interfaceName: lo
I/jxcore-log(20670): 
,I/jxcore-log(20670): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(20670): 
,I/jxcore-log(20670): DBG, CoordinatorConnector connect_error called
I/jxcore-log(20670): 
I/jxcore-log(20670): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(20670): 
,I/jxcore-log(20670): printNetworkInfo
I/jxcore-log(20670): 
,I/jxcore-log(20670): found interfaceName: lo
I/jxcore-log(20670): 
,I/jxcore-log(20670): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(20670): 
,I/jxcore-log(20670): DBG, CoordinatorConnector connect_error called
I/jxcore-log(20670): 
I/jxcore-log(20670): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(20670): 
,I/jxcore-log(20670): printNetworkInfo
I/jxcore-log(20670): 
I/jxcore-log(20670): found interfaceName: lo
I/jxcore-log(20670): 
,I/jxcore-log(20670): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(20670): 
,I/jxcore-log(20670): DBG, CoordinatorConnector connect_error called
I/jxcore-log(20670): 
I/jxcore-log(20670): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(20670): 
,I/jxcore-log(20670): printNetworkInfo
I/jxcore-log(20670): 
,I/jxcore-log(20670): found interfaceName: lo
I/jxcore-log(20670): 
,I/jxcore-log(20670): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(20670): 
,I/jxcore-log(20670): DBG, CoordinatorConnector connect_error called
I/jxcore-log(20670): 
,I/jxcore-log(20670): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(20670): 
,I/jxcore-log(20670): printNetworkInfo
I/jxcore-log(20670): 
I/jxcore-log(20670): found interfaceName: lo
I/jxcore-log(20670): 
,I/jxcore-log(20670): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(20670): 
,I/jxcore-log(26059): Bluetooth turned on
I/jxcore-log(26059): 
,I/jxcore-log(26059): WiFi turned off
I/jxcore-log(26059): 
,I/jxcore-log(26059): WiFi turned on
I/jxcore-log(26059): 
,I/jxcore-log(26059): No internet connection
I/jxcore-log(26059): 
,I/jxcore-log(20670): DBG, CoordinatorConnector connect_error called
I/jxcore-log(20670): 
,I/jxcore-log(20670): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(20670): 
,I/jxcore-log(20670): printNetworkInfo
I/jxcore-log(20670): 
,I/jxcore-log(20670): found interfaceName: lo
I/jxcore-log(20670): 
,I/jxcore-log(20670): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(20670): 
I/jxcore-log(20670): DBG, CoordinatorConnector connect_error called
I/jxcore-log(20670): 
I/jxcore-log(20670): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(20670): 
I/jxcore-log(20670): printNetworkInfo
I/jxcore-log(20670): 
I/jxcore-log(20670): found interfaceName: lo
I/jxcore-log(20670): 
I/jxcore-log(20670): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(20670): 
,I/jxcore-log(26059): No internet connection
I/jxcore-log(26059): 
,I/jxcore-log(26059): No internet connection
I/jxcore-log(26059): 
,I/jxcore-log(26059): No internet connection
I/jxcore-log(26059): 
,I/jxcore-log(26059): WiFi
I/jxcore-log(26059): 
,I/jxcore-log(26059): Response status code was: 200
I/jxcore-log(26059): 
I/jxcore-log(26059): ****TEST TOOK:  10568  ms ****
I/jxcore-log(26059): 
,I/jxcore-log(26059): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(26059): 
,I/jxcore-log(20670): DBG, CoordinatorConnector connect_error called
I/jxcore-log(20670): 
,I/jxcore-log(20670): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(20670): 
I/jxcore-log(20670): printNetworkInfo
I/jxcore-log(20670): 
,I/jxcore-log(20670): found interfaceName: lo
I/jxcore-log(20670): 
,I/jxcore-log(20670): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(20670): 
I/jxcore-log(20670): found interfaceName: wlan0
I/jxcore-log(20670): 
,I/jxcore-log(20670): -iface: IPv4 is internal : false, has ip: 192.168.1.112
I/jxcore-log(20670): 
,I/jxcore-log(20670): DBG, CoordinatorConnector connect_error called
I/jxcore-log(20670): 
,I/jxcore-log(20670): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(20670): 
,I/jxcore-log(20670): printNetworkInfo
I/jxcore-log(20670): 
,I/jxcore-log(20670): found interfaceName: lo
I/jxcore-log(20670): 
,I/jxcore-log(20670): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(20670): 
,I/jxcore-log(20670): found interfaceName: wlan0
I/jxcore-log(20670): 
,I/jxcore-log(20670): -iface: IPv4 is internal : false, has ip: 192.168.1.112
I/jxcore-log(20670): 
,I/jxcore-log(20670): DBG, CoordinatorConnector connect_error called
I/jxcore-log(20670): 
I/jxcore-log(20670): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(20670): 
,I/jxcore-log(20670): printNetworkInfo
I/jxcore-log(20670): 
I/jxcore-log(20670): found interfaceName: lo
I/jxcore-log(20670): 
I/jxcore-log(20670): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(20670): 
I/jxcore-log(20670): found interfaceName: wlan0
I/jxcore-log(20670): 
,I/jxcore-log(20670): -iface: IPv4 is internal : false, has ip: 192.168.1.112
I/jxcore-log(20670): 


```

####Node name: thali05
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
STOP log received from  1d6a772d Test has  SUCCEEDED
Device test finished on 1d6a772d 
STOP log received from  SH47FWM00508 Test has  SUCCEEDED
Device test finished on SH47FWM00508 
Android task is completed 
```

Logcat output:
```
HTC-HTC One_M8: 
--------- beginning of main,
--------- beginning of system
,W/jxcore-log(27211): Initializing JXcore engine
W/jxcore-log(27211): JXcore engine is ready
,W/jxcore-log(27211): Starting JXcore engine
,W/jxcore-log(27211): Platform android
W/jxcore-log(27211): 
,W/jxcore-log(27211): Process ARCH arm
W/jxcore-log(27211): 
,I/jxcore-log(27211): JXcore Cordova bridge is ready!
I/jxcore-log(27211): 
,W/jxcore-log(27211): JXcore engine is started
,E/jxcore-log(27211): >> HTC-HTC One_M8
E/jxcore-log(27211): 
,I/jxcore-log(27211): Total memory 1912020992
I/jxcore-log(27211): 
I/jxcore-log(27211): Free memory 413888512
I/jxcore-log(27211): 
I/jxcore-log(27211): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(27211): 
I/jxcore-log(27211): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(27211): 
,I/jxcore-log(27211): userPath [ 'www' ]
I/jxcore-log(27211): 
,I/jxcore-log(27211): Size 1080 1776
I/jxcore-log(27211): 
,I/jxcore-log(27211): Screen Brightness 142
I/jxcore-log(27211): 
,E/jxcore-log(27211): Dummy Error Log.
E/jxcore-log(27211): 
,I/jxcore-log(27211): getBuffer is called!!!!
I/jxcore-log(27211): 
,I/jxcore-log(27211): Bluetooth turned on,
,I/jxcore-log(27211): 
,I/jxcore-log(27211): WiFi turned off,
I/jxcore-log(27211): 
,I/jxcore-log(27211): WiFi turned on,
I/jxcore-log(27211): 
,I/jxcore-log(27211): No internet connection
I/jxcore-log(27211): 
,I/jxcore-log(27211): No internet connection
I/jxcore-log(27211): 
,I/jxcore-log(27211): No internet connection
I/jxcore-log(27211): 
,I/jxcore-log(27211): No internet connection,
I/jxcore-log(27211): 
,I/jxcore-log(27211): No internet connection,
I/jxcore-log(27211): 
,I/jxcore-log(27211): No internet connection,
I/jxcore-log(27211): 
,I/jxcore-log(27211): WiFi,
I/jxcore-log(27211): 
,I/jxcore-log(27211): Response status code was: 200,
I/jxcore-log(27211): 
I/jxcore-log(27211): ****TEST TOOK:  12612  ms ****
I/jxcore-log(27211): 
I/jxcore-log(27211): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(27211): 


samsung-SM-N9005: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(30067): Initializing JXcore engine
,W/jxcore-log(30067): JXcore engine is ready
,W/jxcore-log(30067): Starting JXcore engine
,W/jxcore-log(30067): Platform android
W/jxcore-log(30067): 
,W/jxcore-log(30067): Process ARCH arm
W/jxcore-log(30067): 
,I/jxcore-log(30067): JXcore Cordova bridge is ready!
I/jxcore-log(30067): 
,W/jxcore-log(30067): JXcore engine is started
,E/jxcore-log(30067): >> samsung-SM-N9005
E/jxcore-log(30067): 
,I/jxcore-log(30067): Total memory 2971471872
I/jxcore-log(30067): 
,I/jxcore-log(30067): Free memory 336109568
I/jxcore-log(30067): 
I/jxcore-log(30067): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(30067): 
I/jxcore-log(30067): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(30067): 
,I/jxcore-log(30067): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(30067): 
,I/jxcore-log(30067): Size 1080 1920
I/jxcore-log(30067): 
,I/jxcore-log(30067): Screen Brightness 255
I/jxcore-log(30067): 
,E/jxcore-log(30067): Dummy Error Log.
E/jxcore-log(30067): 
,I/jxcore-log(30067): getBuffer is called!!!!
I/jxcore-log(30067): 
,I/jxcore-log(30067): Bluetooth turned on
I/jxcore-log(30067): 
,I/jxcore-log(30067): WiFi turned off
I/jxcore-log(30067): 
,I/jxcore-log(30067): WiFi turned on
I/jxcore-log(30067): 
,I/jxcore-log(30067): No internet connection
I/jxcore-log(30067): 
,I/jxcore-log(30067): No internet connection
,I/jxcore-log(30067): 
,I/jxcore-log(30067): No internet connection
I/jxcore-log(30067): 
,I/jxcore-log(30067): No internet connection
I/jxcore-log(30067): 
,I/jxcore-log(30067): No internet connection
I/jxcore-log(30067): 
,I/jxcore-log(30067): No internet connection
I/jxcore-log(30067): 
,I/jxcore-log(30067): WiFi
I/jxcore-log(30067): 
,I/jxcore-log(30067): Response status code was: 200
I/jxcore-log(30067): 
I/jxcore-log(30067): ****TEST TOOK:  12323  ms ****
I/jxcore-log(30067): 
I/jxcore-log(30067): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(30067): 


motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(31084): Initializing JXcore engine
W/jxcore-log(31084): JXcore engine is ready
W/jxcore-log(31084): Starting JXcore engine
W/jxcore-log(31084): Platform android
W/jxcore-log(31084): 
W/jxcore-log(31084): Process ARCH arm
W/jxcore-log(31084): 
I/jxcore-log(31084): JXcore Cordova bridge is ready!
I/jxcore-log(31084): 
W/jxcore-log(31084): JXcore engine is started
,E/jxcore-log(31084): >> motorola-Nexus 6
E/jxcore-log(31084): 
I/jxcore-log(31084): Total memory 3114405888
I/jxcore-log(31084): 
I/jxcore-log(31084): Free memory 596205568
I/jxcore-log(31084): 
I/jxcore-log(31084): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(31084): 
I/jxcore-log(31084): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(31084): 
I/jxcore-log(31084): userPath [ 'www' ]
I/jxcore-log(31084): 
,I/jxcore-log(31084): Size 1440 2392
I/jxcore-log(31084): 
,I/jxcore-log(31084): Screen Brightness 82
I/jxcore-log(31084): 
,E/jxcore-log(31084): Dummy Error Log.
E/jxcore-log(31084): 
,I/jxcore-log(31084): getBuffer is called!!!!
I/jxcore-log(31084): 
,I/jxcore-log(31084): Bluetooth turned on
I/jxcore-log(31084): 
,I/jxcore-log(31084): WiFi turned off
I/jxcore-log(31084): 
,I/jxcore-log(31084): WiFi turned on
I/jxcore-log(31084): 
,I/jxcore-log(31084): No internet connection
I/jxcore-log(31084): 
,I/jxcore-log(31084): No internet connection
I/jxcore-log(31084): 
,I/jxcore-log(31084): No internet connection
I/jxcore-log(31084): 
,I/jxcore-log(31084): No internet connection
I/jxcore-log(31084): 
,I/jxcore-log(31084): No internet connection
I/jxcore-log(31084): 
,I/jxcore-log(31084): WiFi
I/jxcore-log(31084): 
,I/jxcore-log(31084): Response status code was: 200
I/jxcore-log(31084): 
,I/jxcore-log(31084): ****TEST TOOK:  11316  ms ****
I/jxcore-log(31084): 
I/jxcore-log(31084): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(31084): 


```

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
Android task is completed 
```

Logcat output:
```
HTC-HTC One M8s: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log( 6619): Initializing JXcore engine,
W/jxcore-log( 6619): JXcore engine is ready
,W/jxcore-log( 6619): Starting JXcore engine
,W/jxcore-log( 6619): Platform android,
W/jxcore-log( 6619): 
W/jxcore-log( 6619): Process ARCH arm
W/jxcore-log( 6619): 
,I/jxcore-log( 6619): JXcore Cordova bridge is ready!,
I/jxcore-log( 6619): 
W/jxcore-log( 6619): JXcore engine is started
,E/jxcore-log( 6619): >> HTC-HTC One M8s,
E/jxcore-log( 6619): 
,I/jxcore-log( 6619): Total memory 1931808768
I/jxcore-log( 6619): 
I/jxcore-log( 6619): Free memory 294359040
I/jxcore-log( 6619): 
I/jxcore-log( 6619): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6619): 
I/jxcore-log( 6619): process.cwd /data/data/com.example.hello/files/www/jxcore
,I/jxcore-log( 6619): 
,I/jxcore-log( 6619): userPath [ 'www' ]
I/jxcore-log( 6619): 
,I/jxcore-log( 6619): Size 1080 1776
I/jxcore-log( 6619): 
,I/jxcore-log( 6619): Screen Brightness 142,
I/jxcore-log( 6619): 
E/jxcore-log( 6619): Dummy Error Log.
E/jxcore-log( 6619): 
,I/jxcore-log( 6619): getBuffer is called!!!!,
I/jxcore-log( 6619): 
,I/jxcore-log( 6619): Bluetooth turned on,
I/jxcore-log( 6619): 
,I/jxcore-log( 6619): WiFi turned off
I/jxcore-log( 6619): 
,I/jxcore-log( 6619): WiFi turned on
I/jxcore-log( 6619): 
,I/jxcore-log( 6619): No internet connection,
I/jxcore-log( 6619): 
,I/jxcore-log( 6619): No internet connection,
I/jxcore-log( 6619): 
,I/jxcore-log( 6619): No internet connection
I/jxcore-log( 6619): 
,I/jxcore-log( 6619): No internet connection,
I/jxcore-log( 6619): 
,I/jxcore-log( 6619): No internet connection,
I/jxcore-log( 6619): 
,I/jxcore-log( 6619): No internet connection,
I/jxcore-log( 6619): 
,I/jxcore-log( 6619): WiFi
I/jxcore-log( 6619): 
,I/jxcore-log( 6619): Response status code was: 200,
I/jxcore-log( 6619): 
I/jxcore-log( 6619): ****TEST TOOK:  12316  ms ****
I/jxcore-log( 6619): 
I/jxcore-log( 6619): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6619): 


samsung-SM-A300FU: 
--------- beginning of system,
--------- beginning of main
,W/jxcore-log(13944): Initializing JXcore engine
W/jxcore-log(13944): JXcore engine is ready
,W/jxcore-log(13944): Starting JXcore engine
,W/jxcore-log(13944): Platform android
W/jxcore-log(13944): 
W/jxcore-log(13944): Process ARCH arm
W/jxcore-log(13944): 
,I/jxcore-log(13944): JXcore Cordova bridge is ready!
I/jxcore-log(13944): 
,W/jxcore-log(13944): JXcore engine is started
,E/jxcore-log(13944): >> samsung-SM-A300FU
E/jxcore-log(13944): 
,I/jxcore-log(13944): Total memory 1451114496
I/jxcore-log(13944): 
,I/jxcore-log(13944): Free memory 174985216
I/jxcore-log(13944): 
I/jxcore-log(13944): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13944): 
I/jxcore-log(13944): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13944): 
,I/jxcore-log(13944): userPath [ 'www' ]
I/jxcore-log(13944): 
,I/jxcore-log(13944): Size 540 960
I/jxcore-log(13944): 
,I/jxcore-log(13944): Screen Brightness 160
I/jxcore-log(13944): 
,E/jxcore-log(13944): Dummy Error Log.
E/jxcore-log(13944): 
,I/jxcore-log(13944): getBuffer is called!!!!
I/jxcore-log(13944): 
,I/jxcore-log(13944): Bluetooth turned on
I/jxcore-log(13944): 
,I/jxcore-log(13944): WiFi turned off
I/jxcore-log(13944): 
,I/jxcore-log(13944): WiFi turned on
I/jxcore-log(13944): 
,I/jxcore-log(13944): No internet connection
I/jxcore-log(13944): 
,I/jxcore-log(13944): No internet connection
I/jxcore-log(13944): 
,I/jxcore-log(13944): No internet connection
I/jxcore-log(13944): 
,I/jxcore-log(13944): No internet connection
I/jxcore-log(13944): 
,I/jxcore-log(13944): No internet connection,
I/jxcore-log(13944): 
,I/jxcore-log(13944): WiFi
I/jxcore-log(13944): 
,I/jxcore-log(13944): Response status code was: 200
I/jxcore-log(13944): 
,I/jxcore-log(13944): ****TEST TOOK:  11265  ms ****
I/jxcore-log(13944): 
I/jxcore-log(13944): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(13944): 


LGE-LG-D802: 
--------- beginning of /dev/log/main,
--------- beginning of /dev/log/system
,W/jxcore-log(12045): Initializing JXcore engine
,W/jxcore-log(12045): JXcore engine is ready
,W/jxcore-log(12045): Starting JXcore engine
,W/jxcore-log(12045): Platform android
W/jxcore-log(12045): 
W/jxcore-log(12045): Process ARCH arm
W/jxcore-log(12045): 
I/jxcore-log(12045): JXcore Cordova bridge is ready!
I/jxcore-log(12045): 
W/jxcore-log(12045): JXcore engine is started
E/jxcore-log(12045): >> LGE-LG-D802
E/jxcore-log(12045): 
I/jxcore-log(12045): Total memory 1943035904
I/jxcore-log(12045): 
I/jxcore-log(12045): Free memory 90918912
I/jxcore-log(12045): 
I/jxcore-log(12045): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(12045): 
I/jxcore-log(12045): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(12045): 
I/jxcore-log(12045): userPath [ 'www' ]
I/jxcore-log(12045): 
I/jxcore-log(12045): Size 1080 1776
I/jxcore-log(12045): 
I/jxcore-log(12045): Screen Brightness 255
I/jxcore-log(12045): 
E/jxcore-log(12045): Dummy Error Log.
E/jxcore-log(12045): 
,I/jxcore-log( 6275): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): found interfaceName: wlan0
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : false, has ip: 192.168.1.141
I/jxcore-log( 6275): 
,I/jxcore-log(12045): getBuffer is called!!!!
I/jxcore-log(12045): 
,I/jxcore-log(12045): Bluetooth turned on
I/jxcore-log(12045): 
,I/jxcore-log(12045): WiFi turned off
I/jxcore-log(12045): 
,I/jxcore-log(12045): WiFi turned on
I/jxcore-log(12045): 
,I/jxcore-log( 6275): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6275): 
I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6275): 
I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6275): 
I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log( 6275): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log( 6275): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log( 6275): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log( 6275): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log(12045): No internet connection
I/jxcore-log(12045): 
,I/jxcore-log(12045): WiFi
I/jxcore-log(12045): 
,I/jxcore-log( 6275): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
I/jxcore-log( 6275): found interfaceName: wlan0
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : false, has ip: 192.168.1.141
I/jxcore-log( 6275): 
,I/jxcore-log(12045): Response status code was: 200
I/jxcore-log(12045): 
I/jxcore-log(12045): ****TEST TOOK:  34397  ms ****
I/jxcore-log(12045): 
,I/jxcore-log(12045): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(12045): 


```

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
Android task is completed 
```

Logcat output:
```
samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(21519): Initializing JXcore engine
W/jxcore-log(21519): JXcore engine is ready
,W/jxcore-log(21519): Starting JXcore engine
,W/jxcore-log(21519): Platform android
W/jxcore-log(21519): 
W/jxcore-log(21519): Process ARCH arm
W/jxcore-log(21519): 
,I/jxcore-log(21519): JXcore Cordova bridge is ready!
I/jxcore-log(21519): 
,W/jxcore-log(21519): JXcore engine is started
,E/jxcore-log(21519): >> samsung-SM-G900F
E/jxcore-log(21519): 
,I/jxcore-log(21519): Total memory 1787449344
I/jxcore-log(21519): 
,I/jxcore-log(21519): Free memory 58195968
I/jxcore-log(21519): 
I/jxcore-log(21519): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21519): 
I/jxcore-log(21519): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21519): 
,I/jxcore-log(21519): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(21519): 
,I/jxcore-log(21519): Size 1080 1920
I/jxcore-log(21519): 
,I/jxcore-log(21519): Screen Brightness 134
I/jxcore-log(21519): 
,E/jxcore-log(21519): Dummy Error Log.
E/jxcore-log(21519): 
,I/jxcore-log(21519): getBuffer is called!!!!
I/jxcore-log(21519): 
,I/jxcore-log(21519): Bluetooth turned on
I/jxcore-log(21519): 
,I/jxcore-log(21519): WiFi turned off
I/jxcore-log(21519): 
,I/jxcore-log(21519): WiFi turned on
I/jxcore-log(21519): 
,I/jxcore-log(21519): No internet connection
I/jxcore-log(21519): 
,I/jxcore-log(21519): No internet connection
I/jxcore-log(21519): 
,I/jxcore-log(21519): No internet connection
I/jxcore-log(21519): 
,I/jxcore-log(21519): No internet connection
I/jxcore-log(21519): 
,I/jxcore-log(21519): No internet connection
I/jxcore-log(21519): 
,I/jxcore-log(21519): No internet connection
I/jxcore-log(21519): 
,I/jxcore-log(21519): WiFi
I/jxcore-log(21519): 
,I/jxcore-log(21519): Response status code was: 200
I/jxcore-log(21519): 
I/jxcore-log(21519): ****TEST TOOK:  12398  ms ****
I/jxcore-log(21519): 
I/jxcore-log(21519): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(21519): 


```

####Node name: thali08
Console output:
```
STOP log received from  HT574YC04723 Test has  SUCCEEDED
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
Device test finished on HT574YC04723 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of system
--------- beginning of main
,W/jxcore-log(21376): Initializing JXcore engine
W/jxcore-log(21376): JXcore engine is ready
,W/jxcore-log(21376): Starting JXcore engine
,W/jxcore-log(21376): Platform android
W/jxcore-log(21376): 
,W/jxcore-log(21376): Process ARCH arm
W/jxcore-log(21376): 
,I/jxcore-log(21376): JXcore Cordova bridge is ready!
I/jxcore-log(21376): 
,W/jxcore-log(21376): JXcore engine is started
,E/jxcore-log(21376): >> samsung-SM-A300FU
E/jxcore-log(21376): 
,I/jxcore-log(21376): Total memory 1451114496
I/jxcore-log(21376): 
,I/jxcore-log(21376): Free memory 142307328
I/jxcore-log(21376): 
I/jxcore-log(21376): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21376): 
I/jxcore-log(21376): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21376): 
,I/jxcore-log(21376): userPath [ 'www' ],
I/jxcore-log(21376): 
,I/jxcore-log(21376): Size 540 960,
I/jxcore-log(21376): 
,I/jxcore-log(21376): Screen Brightness 255
I/jxcore-log(21376): 
,E/jxcore-log(21376): Dummy Error Log.
E/jxcore-log(21376): 
,I/jxcore-log(21376): getBuffer is called!!!!
I/jxcore-log(21376): 
,I/jxcore-log(21376): Bluetooth turned on
I/jxcore-log(21376): 
,I/jxcore-log(21376): WiFi turned off
I/jxcore-log(21376): 
,I/jxcore-log(21376): WiFi turned on
I/jxcore-log(21376): 
,I/jxcore-log(21376): No internet connection
I/jxcore-log(21376): 
,I/jxcore-log(21376): No internet connection
I/jxcore-log(21376): 
,I/jxcore-log(21376): No internet connection
I/jxcore-log(21376): 
,I/jxcore-log(21376): No internet connection,
I/jxcore-log(21376): 
,I/jxcore-log(21376): No internet connection
I/jxcore-log(21376): 
,I/jxcore-log(21376): No internet connection
I/jxcore-log(21376): 
,I/jxcore-log(21376): No internet connection
I/jxcore-log(21376): 
,I/jxcore-log(21376): WiFi
I/jxcore-log(21376): 
,I/jxcore-log(21376): Response status code was: 200
I/jxcore-log(21376): 
I/jxcore-log(21376): ****TEST TOOK:  13290  ms ****
I/jxcore-log(21376): 
I/jxcore-log(21376): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(21376): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(27744): Initializing JXcore engine
W/jxcore-log(27744): JXcore engine is ready
W/jxcore-log(27744): Starting JXcore engine
W/jxcore-log(27744): Platform android
W/jxcore-log(27744): 
W/jxcore-log(27744): Process ARCH arm
W/jxcore-log(27744): 
I/jxcore-log(27744): JXcore Cordova bridge is ready!
I/jxcore-log(27744): 
W/jxcore-log(27744): JXcore engine is started
E/jxcore-log(27744): >> HTC-HTC Desire 820
E/jxcore-log(27744): 
I/jxcore-log(27744): Total memory 1964650496
I/jxcore-log(27744): 
I/jxcore-log(27744): Free memory 181915648
I/jxcore-log(27744): 
I/jxcore-log(27744): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(27744): 
I/jxcore-log(27744): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(27744): 
I/jxcore-log(27744): userPath [ 'www' ]
I/jxcore-log(27744): 
I/jxcore-log(27744): Size 720 1184
I/jxcore-log(27744): 
I/jxcore-log(27744): Screen Brightness 10
I/jxcore-log(27744): 
E/jxcore-log(27744): Dummy Error Log.
E/jxcore-log(27744): 
,I/jxcore-log(27744): getBuffer is called!!!!
I/jxcore-log(27744): 
,I/jxcore-log(27744): Bluetooth turned on
I/jxcore-log(27744): 
,I/jxcore-log(27744): WiFi turned off
I/jxcore-log(27744): 
,I/jxcore-log(27744): WiFi turned on
I/jxcore-log(27744): 
,I/jxcore-log(27744): No internet connection
I/jxcore-log(27744): 
,I/jxcore-log(27744): No internet connection
I/jxcore-log(27744): 
,I/jxcore-log(27744): No internet connection
I/jxcore-log(27744): 
,I/jxcore-log(27744): No internet connection
I/jxcore-log(27744): 
,I/jxcore-log(27744): No internet connection
I/jxcore-log(27744): 
,I/jxcore-log(27744): No internet connection
I/jxcore-log(27744): 
,I/jxcore-log(27744): No internet connection
I/jxcore-log(27744): 
,I/jxcore-log(27744): WiFi
I/jxcore-log(27744): 
,I/jxcore-log(27744): Response status code was: 200
I/jxcore-log(27744): 
I/jxcore-log(27744): ****TEST TOOK:  14340  ms ****
I/jxcore-log(27744): 
,I/jxcore-log(27744): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(27744): 


```

####Node name: thali09
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log( 2135): Initializing JXcore engine
,W/jxcore-log( 2135): JXcore engine is ready
,W/jxcore-log( 2135): Starting JXcore engine
,W/jxcore-log( 2135): Platform android
W/jxcore-log( 2135): 
,W/jxcore-log( 2135): Process ARCH arm
W/jxcore-log( 2135): 
,I/jxcore-log( 2135): JXcore Cordova bridge is ready!
I/jxcore-log( 2135): 
,W/jxcore-log( 2135): JXcore engine is started
,E/jxcore-log( 2135): >> LGE-Nexus 5
E/jxcore-log( 2135): 
,I/jxcore-log( 2135): Total memory 1945137152
I/jxcore-log( 2135): 
I/jxcore-log( 2135): Free memory 422641664
I/jxcore-log( 2135): 
I/jxcore-log( 2135): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2135): 
,I/jxcore-log( 2135): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2135): 
,I/jxcore-log( 2135): userPath [ 'www' ]
I/jxcore-log( 2135): 
,I/jxcore-log( 2135): Size 1080 1776
I/jxcore-log( 2135): 
,I/jxcore-log( 2135): Screen Brightness 82
I/jxcore-log( 2135): 
,E/jxcore-log( 2135): Dummy Error Log.
E/jxcore-log( 2135): 
,I/jxcore-log( 2135): getBuffer is called!!!!
I/jxcore-log( 2135): 
,I/jxcore-log( 2135): Bluetooth turned on
I/jxcore-log( 2135): 
,I/jxcore-log( 2135): WiFi turned off
I/jxcore-log( 2135): 
,I/jxcore-log( 2135): WiFi turned on
I/jxcore-log( 2135): 
,I/jxcore-log( 2135): No internet connection
I/jxcore-log( 2135): 
,I/jxcore-log( 2135): No internet connection
I/jxcore-log( 2135): 
,I/jxcore-log( 2135): No internet connection
I/jxcore-log( 2135): 
,I/jxcore-log( 2135): No internet connection
I/jxcore-log( 2135): 
,I/jxcore-log( 2135): WiFi
I/jxcore-log( 2135): 
,I/jxcore-log( 2135): Response status code was: 200
I/jxcore-log( 2135): 
,I/jxcore-log( 2135): ****TEST TOOK:  10303  ms ****
I/jxcore-log( 2135): 
,I/jxcore-log( 2135): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2135): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log(19726): Initializing JXcore engine
W/jxcore-log(19726): JXcore engine is ready
W/jxcore-log(19726): Starting JXcore engine
W/jxcore-log(19726): Platform android
W/jxcore-log(19726): 
W/jxcore-log(19726): Process ARCH arm
W/jxcore-log(19726): 
I/jxcore-log(19726): JXcore Cordova bridge is ready!
I/jxcore-log(19726): 
W/jxcore-log(19726): JXcore engine is started
E/jxcore-log(19726): >> HTC-HTC Desire 820
E/jxcore-log(19726): 
I/jxcore-log(19726): Total memory 1964650496
I/jxcore-log(19726): 
I/jxcore-log(19726): Free memory 224174080
I/jxcore-log(19726): 
I/jxcore-log(19726): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19726): 
I/jxcore-log(19726): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19726): 
I/jxcore-log(19726): userPath [ 'www' ]
I/jxcore-log(19726): 
I/jxcore-log(19726): Size 720 1184
I/jxcore-log(19726): 
I/jxcore-log(19726): Screen Brightness 142
I/jxcore-log(19726): 
E/jxcore-log(19726): Dummy Error Log.
E/jxcore-log(19726): 
,I/jxcore-log(19726): getBuffer is called!!!!
I/jxcore-log(19726): 
,I/jxcore-log(19726): Bluetooth turned on
I/jxcore-log(19726): 
,I/jxcore-log(19726): WiFi turned off
I/jxcore-log(19726): 
,I/jxcore-log(19726): WiFi turned on
I/jxcore-log(19726): 
,I/jxcore-log(19726): No internet connection
I/jxcore-log(19726): 
,I/jxcore-log(19726): No internet connection
I/jxcore-log(19726): 
,I/jxcore-log(19726): No internet connection
I/jxcore-log(19726): 
,I/jxcore-log(19726): No internet connection
I/jxcore-log(19726): 
,I/jxcore-log(19726): No internet connection
I/jxcore-log(19726): 
,I/jxcore-log(19726): No internet connection
I/jxcore-log(19726): 
,I/jxcore-log(19726): No internet connection
I/jxcore-log(19726): 
,I/jxcore-log(19726): WiFi
I/jxcore-log(19726): 
,I/jxcore-log(19726): Response status code was: 200
I/jxcore-log(19726): 
,I/jxcore-log(19726): ****TEST TOOK:  13544  ms ****
I/jxcore-log(19726): 
,I/jxcore-log(19726): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(19726): 


```


