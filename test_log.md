#### Test 495261846d7bbdf Logs

Status: 
```

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":20,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_495261846d7bbdf/Sub/serverApp/index.js',
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
  '/home/pi/Test/server_495261846d7bbdf/Sub/serverApp/index.js',
  '{"devices":{"android":20,"cancel":1}}' ]

JSON { devices: { android: 20, cancel: 1 } }


```

###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
STOP log received from  03157df360a1882a Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Device test finished on 03157df360a1882a 
Device test finished on W3D7N15428022572 
STOP log received from  30049d9501da2100 Test has  SUCCEEDED
Device test finished on 30049d9501da2100 
Android task is completed 
```

Logcat output:
```
samsung-SM-G920F: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log( 9541): Initializing JXcore engine
W/jxcore-log( 9541): JXcore engine is ready
,W/jxcore-log( 9541): Starting JXcore engine
,W/jxcore-log( 9541): Platform android
W/jxcore-log( 9541): 
W/jxcore-log( 9541): Process ARCH arm
W/jxcore-log( 9541): 
,I/jxcore-log( 9541): JXcore Cordova bridge is ready!
I/jxcore-log( 9541): 
W/jxcore-log( 9541): JXcore engine is started
,E/jxcore-log( 9541): >> samsung-SM-G920F
E/jxcore-log( 9541): 
,I/jxcore-log( 9541): Total memory 2829074432
I/jxcore-log( 9541): 
I/jxcore-log( 9541): Free memory 201359360
I/jxcore-log( 9541): 
I/jxcore-log( 9541): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9541): 
,I/jxcore-log( 9541): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9541): 
,I/jxcore-log( 9541): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 9541): 
,I/jxcore-log( 9541): Size 1440 2560
I/jxcore-log( 9541): 
,I/jxcore-log( 9541): Screen Brightness 255
I/jxcore-log( 9541): 
E/jxcore-log( 9541): Dummy Error Log.
E/jxcore-log( 9541): 
,I/jxcore-log( 9541): getBuffer is called!!!!
I/jxcore-log( 9541): 
,I/jxcore-log( 9541): Bluetooth turned on
I/jxcore-log( 9541): 
,I/jxcore-log( 9541): WiFi turned off
I/jxcore-log( 9541): 
,I/jxcore-log( 9541): WiFi turned on
I/jxcore-log( 9541): 
,I/jxcore-log( 9541): No internet connection
I/jxcore-log( 9541): 
,I/jxcore-log( 9541): No internet connection
I/jxcore-log( 9541): 
,I/jxcore-log( 9541): No internet connection
I/jxcore-log( 9541): 
,I/jxcore-log( 9541): No internet connection
I/jxcore-log( 9541): 
,I/jxcore-log( 9541): No internet connection
I/jxcore-log( 9541): 
,I/jxcore-log( 9541): WiFi
I/jxcore-log( 9541): 
,I/jxcore-log( 9541): Response status code was: 200
I/jxcore-log( 9541): 
I/jxcore-log( 9541): ****TEST TOOK:  11301  ms ****
I/jxcore-log( 9541): 
I/jxcore-log( 9541): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9541): 


samsung-SM-T232: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
W/jxcore-log(13120): Initializing JXcore engine
W/jxcore-log(13120): JXcore engine is ready
W/jxcore-log(13120): Starting JXcore engine
W/jxcore-log(13120): Platform android
W/jxcore-log(13120): 
W/jxcore-log(13120): Process ARCH arm
W/jxcore-log(13120): 
,I/jxcore-log(13120): JXcore Cordova bridge is ready!
I/jxcore-log(13120): 
W/jxcore-log(13120): JXcore engine is started
E/jxcore-log(13120): >> samsung-SM-T232
E/jxcore-log(13120): 
I/jxcore-log(13120): Total memory 1352024064
I/jxcore-log(13120): 
I/jxcore-log(13120): Free memory 177565696
I/jxcore-log(13120): 
I/jxcore-log(13120): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13120): 
I/jxcore-log(13120): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13120): 
I/jxcore-log(13120): userPath [ 'www' ]
I/jxcore-log(13120): 
I/jxcore-log(13120): Size 800 1280
I/jxcore-log(13120): 
I/jxcore-log(13120): Screen Brightness 255
I/jxcore-log(13120): 
E/jxcore-log(13120): Dummy Error Log.
E/jxcore-log(13120): 
I/jxcore-log(13120): getBuffer is called!!!!
I/jxcore-log(13120): 
,I/jxcore-log(13120): Bluetooth turned on
I/jxcore-log(13120): 
,I/jxcore-log(13120): WiFi turned off
I/jxcore-log(13120): 
,I/jxcore-log(13120): WiFi turned on
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): Timeout in log.js file reached!
I/jxcore-log(13120): 
I/jxcore-log(13120): ****TEST TOOK:  125112  ms ****
I/jxcore-log(13120): 
,I/jxcore-log(13120): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILURE]****
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 
,I/jxcore-log(13120): No internet connection
I/jxcore-log(13120): 


LGE-LG-H815: 
--------- beginning of main
I/jxcore-log(15361): DBG, CoordinatorConnector connect_error called
I/jxcore-log(15361): 
I/jxcore-log(15361): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
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
I/jxcore-log(15361): DBG, CoordinatorConnector connect_error called
I/jxcore-log(15361): 
I/jxcore-log(15361): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
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
I/jxcore-log(15361): DBG, CoordinatorConnector connect_error called
I/jxcore-log(15361): 
I/jxcore-log(15361): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
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
,--------- beginning of system
,W/jxcore-log(22717): Initializing JXcore engine
W/jxcore-log(22717): JXcore engine is ready
W/jxcore-log(22717): Starting JXcore engine
W/jxcore-log(22717): Platform android
W/jxcore-log(22717): 
W/jxcore-log(22717): Process ARCH arm
W/jxcore-log(22717): 
I/jxcore-log(22717): JXcore Cordova bridge is ready!
I/jxcore-log(22717): 
W/jxcore-log(22717): JXcore engine is started
E/jxcore-log(22717): >> LGE-LG-H815
E/jxcore-log(22717): 
I/jxcore-log(22717): Total memory 2968948736
I/jxcore-log(22717): 
I/jxcore-log(22717): Free memory 396267520
I/jxcore-log(22717): 
I/jxcore-log(22717): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(22717): 
I/jxcore-log(22717): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(22717): 
I/jxcore-log(22717): userPath [ 'www' ]
I/jxcore-log(22717): 
I/jxcore-log(22717): Size 1440 2392
I/jxcore-log(22717): 
I/jxcore-log(22717): Screen Brightness 255
I/jxcore-log(22717): 
E/jxcore-log(22717): Dummy Error Log.
E/jxcore-log(22717): 
I/jxcore-log(22717): getBuffer is called!!!!
I/jxcore-log(22717): 
,I/jxcore-log(15361): DBG, CoordinatorConnector connect_error called
I/jxcore-log(15361): 
,I/jxcore-log(15361): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(15361): 
I/jxcore-log(15361): printNetworkInfo
I/jxcore-log(15361): 
,I/jxcore-log(15361): found interfaceName: lo
I/jxcore-log(15361): 
,I/jxcore-log(15361): -iface: IPv4 is internal : true, has ip: 127.0.0.1
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
,I/jxcore-log(22717): Bluetooth turned on
I/jxcore-log(22717): 
,I/jxcore-log(22717): WiFi turned off
I/jxcore-log(22717): 
,I/jxcore-log(22717): WiFi turned on
I/jxcore-log(22717): 
,I/jxcore-log(22717): No internet connection
I/jxcore-log(22717): 
,I/jxcore-log(22717): No internet connection
I/jxcore-log(22717): 
,I/jxcore-log(15361): DBG, CoordinatorConnector connect_error called
I/jxcore-log(15361): 
,I/jxcore-log(15361): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(15361): 
I/jxcore-log(15361): printNetworkInfo
I/jxcore-log(15361): 
,I/jxcore-log(15361): found interfaceName: lo
I/jxcore-log(15361): 
I/jxcore-log(15361): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(15361): 
I/jxcore-log(15361): DBG, CoordinatorConnector connect_error called
I/jxcore-log(15361): 
I/jxcore-log(15361): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(15361): 
I/jxcore-log(15361): printNetworkInfo
I/jxcore-log(15361): 
I/jxcore-log(15361): found interfaceName: lo
I/jxcore-log(15361): 
I/jxcore-log(15361): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(15361): 
,I/jxcore-log(15361): DBG, CoordinatorConnector connect_error called
I/jxcore-log(15361): 
,I/jxcore-log(15361): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(15361): 
I/jxcore-log(15361): printNetworkInfo
I/jxcore-log(15361): 
,I/jxcore-log(15361): found interfaceName: lo
I/jxcore-log(15361): 
I/jxcore-log(15361): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(15361): 
,I/jxcore-log(15361): DBG, CoordinatorConnector connect_error called
I/jxcore-log(15361): 
,I/jxcore-log(15361): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(15361): 
I/jxcore-log(15361): printNetworkInfo
I/jxcore-log(15361): 
,I/jxcore-log(15361): found interfaceName: lo
I/jxcore-log(15361): 
I/jxcore-log(15361): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(15361): 
,I/jxcore-log(22717): No internet connection
I/jxcore-log(22717): 
,I/jxcore-log(22717): No internet connection
I/jxcore-log(22717): 
,I/jxcore-log(22717): No internet connection
I/jxcore-log(22717): 
,I/jxcore-log(22717): No internet connection
I/jxcore-log(22717): 
,I/jxcore-log(22717): WiFi
I/jxcore-log(22717): 
,I/jxcore-log(22717): Response status code was: 200
I/jxcore-log(22717): 
,I/jxcore-log(22717): ****TEST TOOK:  12542  ms ****
I/jxcore-log(22717): 
I/jxcore-log(22717): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(22717): 
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


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
W/jxcore-log( 1060): Initializing JXcore engine
W/jxcore-log( 1060): JXcore engine is ready
W/jxcore-log( 1060): Starting JXcore engine
W/jxcore-log( 1060): Platform android
W/jxcore-log( 1060): 
W/jxcore-log( 1060): Process ARCH arm
W/jxcore-log( 1060): 
I/jxcore-log( 1060): JXcore Cordova bridge is ready!
I/jxcore-log( 1060): 
W/jxcore-log( 1060): JXcore engine is started
E/jxcore-log( 1060): >> HUAWEI-ALE-L21
E/jxcore-log( 1060): 
I/jxcore-log( 1060): Total memory 1949741056
I/jxcore-log( 1060): 
I/jxcore-log( 1060): Free memory 104558592
I/jxcore-log( 1060): 
I/jxcore-log( 1060): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1060): 
I/jxcore-log( 1060): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1060): 
,I/jxcore-log( 1060): userPath [ 'www' ]
I/jxcore-log( 1060): 
,I/jxcore-log( 1060): Size 720 1184
I/jxcore-log( 1060): 
,I/jxcore-log( 1060): Screen Brightness 242
I/jxcore-log( 1060): 
,E/jxcore-log( 1060): Dummy Error Log.
E/jxcore-log( 1060): 
,I/jxcore-log( 1060): getBuffer is called!!!!
I/jxcore-log( 1060): 
,I/jxcore-log( 1060): Bluetooth turned on
I/jxcore-log( 1060): 
,I/jxcore-log( 1060): WiFi turned off
I/jxcore-log( 1060): 
,I/jxcore-log( 1060): WiFi turned on
I/jxcore-log( 1060): 
,I/jxcore-log( 1060): No internet connection
I/jxcore-log( 1060): 
,I/jxcore-log( 1060): No internet connection
I/jxcore-log( 1060): 
,I/jxcore-log( 1060): No internet connection
I/jxcore-log( 1060): 
,I/jxcore-log( 1060): No internet connection
I/jxcore-log( 1060): 
,I/jxcore-log( 1060): No internet connection
I/jxcore-log( 1060): 
,I/jxcore-log( 1060): No internet connection
I/jxcore-log( 1060): 
,I/jxcore-log( 1060): WiFi
I/jxcore-log( 1060): 
,I/jxcore-log( 1060): Response status code was: 200
I/jxcore-log( 1060): 
I/jxcore-log( 1060): ****TEST TOOK:  12408  ms ****
I/jxcore-log( 1060): 
I/jxcore-log( 1060): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 1060): 


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
,W/jxcore-log( 6677): Initializing JXcore engine
W/jxcore-log( 6677): JXcore engine is ready
,W/jxcore-log( 6677): Starting JXcore engine
,W/jxcore-log( 6677): Platform android
W/jxcore-log( 6677): 
W/jxcore-log( 6677): Process ARCH arm
W/jxcore-log( 6677): 
,I/jxcore-log( 6677): JXcore Cordova bridge is ready!
I/jxcore-log( 6677): 
W/jxcore-log( 6677): JXcore engine is started
,E/jxcore-log( 6677): >> LGE-Nexus 5
E/jxcore-log( 6677): 
,I/jxcore-log( 6677): Total memory 1946181632
I/jxcore-log( 6677): 
I/jxcore-log( 6677): Free memory 292761600
I/jxcore-log( 6677): 
I/jxcore-log( 6677): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6677): 
I/jxcore-log( 6677): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6677): 
,I/jxcore-log( 6677): userPath [ 'www' ]
I/jxcore-log( 6677): 
,I/jxcore-log( 6677): Size 1080 1776
I/jxcore-log( 6677): 
,I/jxcore-log( 6677): Screen Brightness 82
I/jxcore-log( 6677): 
,E/jxcore-log( 6677): Dummy Error Log.
E/jxcore-log( 6677): 
,I/jxcore-log( 6677): getBuffer is called!!!!
I/jxcore-log( 6677): 
,I/jxcore-log( 6677): Bluetooth turned on
I/jxcore-log( 6677): 
,I/jxcore-log( 6677): WiFi turned off
I/jxcore-log( 6677): 
,I/jxcore-log( 6677): WiFi turned on
I/jxcore-log( 6677): 
,I/jxcore-log( 6677): No internet connection
I/jxcore-log( 6677): 
,I/jxcore-log( 6677): No internet connection
I/jxcore-log( 6677): 
,I/jxcore-log( 6677): No internet connection
I/jxcore-log( 6677): 
,I/jxcore-log( 6677): No internet connection
I/jxcore-log( 6677): 
,I/jxcore-log( 6677): No internet connection
I/jxcore-log( 6677): 
,I/jxcore-log( 6677): WiFi
I/jxcore-log( 6677): 
,I/jxcore-log( 6677): Response status code was: 200
I/jxcore-log( 6677): 
I/jxcore-log( 6677): ****TEST TOOK:  11373  ms ****
I/jxcore-log( 6677): 
I/jxcore-log( 6677): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6677): 


LGE-LG-D722: 
--------- beginning of system
--------- beginning of main
,W/jxcore-log( 6786): Initializing JXcore engine
,W/jxcore-log( 6786): JXcore engine is ready
,W/jxcore-log( 6786): Starting JXcore engine
,W/jxcore-log( 6786): Platform android
W/jxcore-log( 6786): 
W/jxcore-log( 6786): Process ARCH arm
W/jxcore-log( 6786): 
I/jxcore-log( 6786): JXcore Cordova bridge is ready!
I/jxcore-log( 6786): 
W/jxcore-log( 6786): JXcore engine is started
,E/jxcore-log( 6786): >> LGE-LG-D722
E/jxcore-log( 6786): 
,I/jxcore-log( 6786): Total memory 906309632
I/jxcore-log( 6786): 
I/jxcore-log( 6786): Free memory 24215552
I/jxcore-log( 6786): 
I/jxcore-log( 6786): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6786): 
I/jxcore-log( 6786): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6786): 
I/jxcore-log( 6786): userPath [ 'www' ]
I/jxcore-log( 6786): 
I/jxcore-log( 6786): Size 720 1196
I/jxcore-log( 6786): 
,I/jxcore-log( 6786): Screen Brightness 255
I/jxcore-log( 6786): 
E/jxcore-log( 6786): Dummy Error Log.
E/jxcore-log( 6786): 
,I/jxcore-log( 6786): getBuffer is called!!!!
I/jxcore-log( 6786): 
,I/jxcore-log( 6786): Bluetooth turned on
I/jxcore-log( 6786): 
,I/jxcore-log( 6786): WiFi turned off
I/jxcore-log( 6786): 
,I/jxcore-log( 6786): WiFi turned on
I/jxcore-log( 6786): 
,I/jxcore-log( 6786): No internet connection
I/jxcore-log( 6786): 
,I/jxcore-log( 6786): No internet connection
I/jxcore-log( 6786): 
,I/jxcore-log( 6786): No internet connection
I/jxcore-log( 6786): 
,I/jxcore-log( 6786): WiFi
I/jxcore-log( 6786): 
,I/jxcore-log( 6786): Response status code was: 200
I/jxcore-log( 6786): 
I/jxcore-log( 6786): ****TEST TOOK:  9386  ms ****
I/jxcore-log( 6786): 
I/jxcore-log( 6786): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6786): 


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
,W/jxcore-log(18731): Initializing JXcore engine
,W/jxcore-log(18731): JXcore engine is ready
,W/jxcore-log(18731): Starting JXcore engine
,W/jxcore-log(18731): Platform android
W/jxcore-log(18731): 
,W/jxcore-log(18731): Process ARCH arm
W/jxcore-log(18731): 
,I/jxcore-log(18731): JXcore Cordova bridge is ready!
I/jxcore-log(18731): 
,W/jxcore-log(18731): JXcore engine is started
,E/jxcore-log(18731): >> motorola-XT1039
E/jxcore-log(18731): 
I/jxcore-log(18731): Total memory 893136896
I/jxcore-log(18731): 
I/jxcore-log(18731): Free memory 52187136
I/jxcore-log(18731): 
I/jxcore-log(18731): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(18731): 
,I/jxcore-log(18731): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(18731): 
,I/jxcore-log(18731): userPath [ 'www' ]
I/jxcore-log(18731): 
,I/jxcore-log(18731): Size 720 1184
I/jxcore-log(18731): 
I/jxcore-log(18731): Screen Brightness 210
I/jxcore-log(18731): 
,E/jxcore-log(18731): Dummy Error Log.
E/jxcore-log(18731): 
,I/jxcore-log(18731): getBuffer is called!!!!
I/jxcore-log(18731): 
,I/jxcore-log(18731): Bluetooth turned on
I/jxcore-log(18731): 
,I/jxcore-log(18731): WiFi turned off
I/jxcore-log(18731): 
,I/jxcore-log(18731): WiFi turned on
I/jxcore-log(18731): 
,I/jxcore-log(18731): No internet connection
I/jxcore-log(18731): 
,I/jxcore-log(18731): No internet connection
I/jxcore-log(18731): 
,I/jxcore-log(18731): No internet connection
I/jxcore-log(18731): 
,I/jxcore-log(18731): No internet connection
I/jxcore-log(18731): 
,I/jxcore-log(18731): No internet connection
I/jxcore-log(18731): 
,I/jxcore-log(18731): WiFi
I/jxcore-log(18731): 
,I/jxcore-log(18731): Response status code was: 200
I/jxcore-log(18731): 
I/jxcore-log(18731): ****TEST TOOK:  11393  ms ****
I/jxcore-log(18731): 
,I/jxcore-log(18731): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(18731): 


LGE-LG-D855: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(17883): Initializing JXcore engine
W/jxcore-log(17883): JXcore engine is ready
W/jxcore-log(17883): Starting JXcore engine
W/jxcore-log(17883): Platform android
W/jxcore-log(17883): 
W/jxcore-log(17883): Process ARCH arm
W/jxcore-log(17883): 
I/jxcore-log(17883): JXcore Cordova bridge is ready!
I/jxcore-log(17883): 
W/jxcore-log(17883): JXcore engine is started
E/jxcore-log(17883): >> LGE-LG-D855
E/jxcore-log(17883): 
I/jxcore-log(17883): Total memory 2995761152
I/jxcore-log(17883): 
I/jxcore-log(17883): Free memory 283058176
I/jxcore-log(17883): 
I/jxcore-log(17883): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(17883): 
I/jxcore-log(17883): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(17883): 
,I/jxcore-log(17883): userPath [ 'www' ]
I/jxcore-log(17883): 
I/jxcore-log(17883): Size 1440 2392
I/jxcore-log(17883): 
I/jxcore-log(17883): Screen Brightness 177
I/jxcore-log(17883): 
E/jxcore-log(17883): Dummy Error Log.
E/jxcore-log(17883): 
I/jxcore-log(17883): getBuffer is called!!!!
I/jxcore-log(17883): 
,I/jxcore-log(17883): Bluetooth turned on
I/jxcore-log(17883): 
,I/jxcore-log(17883): WiFi turned off
I/jxcore-log(17883): 
,I/jxcore-log(17883): WiFi turned on
I/jxcore-log(17883): 
,I/jxcore-log(17883): No internet connection
I/jxcore-log(17883): 
,I/jxcore-log(17883): No internet connection
I/jxcore-log(17883): 
,I/jxcore-log(17883): WiFi
I/jxcore-log(17883): 
,I/jxcore-log(17883): Response status code was: 200
I/jxcore-log(17883): 
I/jxcore-log(17883): ****TEST TOOK:  8383  ms ****
I/jxcore-log(17883): 
I/jxcore-log(17883): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(17883): 


samsung-SM-G800F: 
--------- beginning of /dev/log/system
--------- beginning of /dev/log/main
,I/jxcore-log(20670): DBG, CoordinatorConnector connect_error called,
I/jxcore-log(20670): 
I/jxcore-log(20670): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(20670): 
I/jxcore-log(20670): printNetworkInfo
I/jxcore-log(20670): 
I/jxcore-log(20670): found interfaceName: lo
I/jxcore-log(20670): 
,I/jxcore-log(20670): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(20670): 
,I/jxcore-log(20670): found interfaceName: wlan0
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
I/jxcore-log(20670): found interfaceName: wlan0
I/jxcore-log(20670): 
,I/jxcore-log(20670): -iface: IPv4 is internal : false, has ip: 192.168.1.112
I/jxcore-log(20670): 
,W/jxcore-log(28064): Initializing JXcore engine
,W/jxcore-log(28064): JXcore engine is ready
,W/jxcore-log(28064): Starting JXcore engine
,W/jxcore-log(28064): Platform android
W/jxcore-log(28064): 
,W/jxcore-log(28064): Process ARCH arm
W/jxcore-log(28064): 
,I/jxcore-log(28064): JXcore Cordova bridge is ready!
I/jxcore-log(28064): 
,W/jxcore-log(28064): JXcore engine is started
,E/jxcore-log(28064): >> samsung-SM-G800F
E/jxcore-log(28064): 
,I/jxcore-log(28064): Total memory 1319530496
I/jxcore-log(28064): 
,I/jxcore-log(28064): Free memory 37679104
I/jxcore-log(28064): 
,I/jxcore-log(28064): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(28064): 
,I/jxcore-log(28064): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(28064): 
,I/jxcore-log(28064): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(28064): 
,I/jxcore-log(28064): Size 720 1280
I/jxcore-log(28064): 
,I/jxcore-log(28064): Screen Brightness 255
I/jxcore-log(28064): 
,E/jxcore-log(28064): Dummy Error Log.
E/jxcore-log(28064): 
,I/jxcore-log(28064): getBuffer is called!!!!
I/jxcore-log(28064): 
,I/jxcore-log(20670): DBG, CoordinatorConnector connect_error called
I/jxcore-log(20670): 
I/jxcore-log(20670): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(20670): 
,I/jxcore-log(20670): printNetworkInfo
I/jxcore-log(20670): 
,I/jxcore-log(20670): found interfaceName: lo
I/jxcore-log(20670): 
I/jxcore-log(20670): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(20670): 
I/jxcore-log(20670): found interfaceName: wlan0
I/jxcore-log(20670): 
,I/jxcore-log(20670): -iface: IPv4 is internal : false, has ip: 192.168.1.112
I/jxcore-log(20670): 
,I/jxcore-log(28064): Bluetooth turned on
I/jxcore-log(28064): 
,I/jxcore-log(28064): WiFi turned off
I/jxcore-log(28064): 
,I/jxcore-log(28064): WiFi turned on
I/jxcore-log(28064): 
,I/jxcore-log(28064): No internet connection
I/jxcore-log(28064): 
,I/jxcore-log(28064): No internet connection
I/jxcore-log(28064): 
,I/jxcore-log(28064): No internet connection
I/jxcore-log(28064): 
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
,I/jxcore-log(28064): No internet connection
I/jxcore-log(28064): 
,I/jxcore-log(28064): No internet connection
I/jxcore-log(28064): 
,I/jxcore-log(28064): WiFi
I/jxcore-log(28064): 
,I/jxcore-log(28064): Response status code was: 200
I/jxcore-log(28064): 
I/jxcore-log(28064): ****TEST TOOK:  11506  ms ****
I/jxcore-log(28064): 
,I/jxcore-log(28064): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(28064): 
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
,W/jxcore-log(28656): Initializing JXcore engine
,W/jxcore-log(28656): JXcore engine is ready
,W/jxcore-log(28656): Starting JXcore engine
,W/jxcore-log(28656): Platform android
W/jxcore-log(28656): 
W/jxcore-log(28656): Process ARCH arm
W/jxcore-log(28656): 
,I/jxcore-log(28656): JXcore Cordova bridge is ready!,
I/jxcore-log(28656): 
W/jxcore-log(28656): JXcore engine is started
,E/jxcore-log(28656): >> HTC-HTC One_M8,
E/jxcore-log(28656): 
I/jxcore-log(28656): Total memory 1912020992
I/jxcore-log(28656): 
I/jxcore-log(28656): Free memory 417546240
I/jxcore-log(28656): 
I/jxcore-log(28656): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(28656): 
I/jxcore-log(28656): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(28656): 
,I/jxcore-log(28656): userPath [ 'www' ]
I/jxcore-log(28656): 
I/jxcore-log(28656): Size 1080 1776
I/jxcore-log(28656): 
I/jxcore-log(28656): Screen Brightness 142
I/jxcore-log(28656): 
E/jxcore-log(28656): Dummy Error Log.
E/jxcore-log(28656): 
,I/jxcore-log(28656): getBuffer is called!!!!,
I/jxcore-log(28656): 
,I/jxcore-log(28656): Bluetooth turned on,
I/jxcore-log(28656): 
,I/jxcore-log(28656): WiFi turned off,
I/jxcore-log(28656): 
,I/jxcore-log(28656): WiFi turned on,
I/jxcore-log(28656): 
,I/jxcore-log(28656): No internet connection,
I/jxcore-log(28656): ,
,I/jxcore-log(28656): No internet connection
I/jxcore-log(28656): 
,I/jxcore-log(28656): No internet connection
I/jxcore-log(28656): 
,I/jxcore-log(28656): No internet connection
I/jxcore-log(28656): 
,I/jxcore-log(28656): WiFi
I/jxcore-log(28656): 
,I/jxcore-log(28656): Response status code was: 200,
I/jxcore-log(28656): 
I/jxcore-log(28656): ****TEST TOOK:  10292  ms ****
I/jxcore-log(28656): 
I/jxcore-log(28656): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(28656): 


samsung-SM-N9005: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(32172): Initializing JXcore engine
,W/jxcore-log(32172): JXcore engine is ready
,W/jxcore-log(32172): Starting JXcore engine,
,W/jxcore-log(32172): Platform android
W/jxcore-log(32172): 
W/jxcore-log(32172): Process ARCH arm
W/jxcore-log(32172): 
,I/jxcore-log(32172): JXcore Cordova bridge is ready!
I/jxcore-log(32172): 
W/jxcore-log(32172): JXcore engine is started
,E/jxcore-log(32172): >> samsung-SM-N9005
E/jxcore-log(32172): 
,I/jxcore-log(32172): Total memory 2971471872
I/jxcore-log(32172): 
,I/jxcore-log(32172): Free memory 336326656
I/jxcore-log(32172): 
I/jxcore-log(32172): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32172): 
I/jxcore-log(32172): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32172): 
,I/jxcore-log(32172): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(32172): 
,I/jxcore-log(32172): Size 1080 1920
I/jxcore-log(32172): 
,I/jxcore-log(32172): Screen Brightness 255
I/jxcore-log(32172): 
,E/jxcore-log(32172): Dummy Error Log.
E/jxcore-log(32172): 
,I/jxcore-log(32172): getBuffer is called!!!!
I/jxcore-log(32172): 
,I/jxcore-log(32172): Bluetooth turned on
I/jxcore-log(32172): 
,I/jxcore-log(32172): WiFi turned off
I/jxcore-log(32172): 
,I/jxcore-log(32172): WiFi turned on
I/jxcore-log(32172): 
,I/jxcore-log(32172): No internet connection
I/jxcore-log(32172): 
,I/jxcore-log(32172): No internet connection
I/jxcore-log(32172): 
,I/jxcore-log(32172): No internet connection
I/jxcore-log(32172): 
,I/jxcore-log(32172): No internet connection
I/jxcore-log(32172): 
,I/jxcore-log(32172): No internet connection
I/jxcore-log(32172): 
,I/jxcore-log(32172): WiFi
I/jxcore-log(32172): 
,I/jxcore-log(32172): Response status code was: 200
I/jxcore-log(32172): 
,I/jxcore-log(32172): ****TEST TOOK:  11307  ms ****
I/jxcore-log(32172): 
I/jxcore-log(32172): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(32172): 


motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(31687): Initializing JXcore engine
,W/jxcore-log(31687): JXcore engine is ready
,W/jxcore-log(31687): Starting JXcore engine
,W/jxcore-log(31687): Platform android
W/jxcore-log(31687): 
,W/jxcore-log(31687): Process ARCH arm
W/jxcore-log(31687): 
,I/jxcore-log(31687): JXcore Cordova bridge is ready!
I/jxcore-log(31687): 
,W/jxcore-log(31687): JXcore engine is started
,E/jxcore-log(31687): >> motorola-Nexus 6
E/jxcore-log(31687): 
,I/jxcore-log(31687): Total memory 3114405888
I/jxcore-log(31687): 
I/jxcore-log(31687): Free memory 566304768
I/jxcore-log(31687): 
I/jxcore-log(31687): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(31687): 
I/jxcore-log(31687): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(31687): 
,I/jxcore-log(31687): userPath [ 'www' ]
I/jxcore-log(31687): 
,I/jxcore-log(31687): Size 1440 2392
I/jxcore-log(31687): 
,I/jxcore-log(31687): Screen Brightness 82
I/jxcore-log(31687): 
,E/jxcore-log(31687): Dummy Error Log.
E/jxcore-log(31687): 
,I/jxcore-log(31687): getBuffer is called!!!!
I/jxcore-log(31687): 
,I/jxcore-log(31687): Bluetooth turned on
I/jxcore-log(31687): 
,I/jxcore-log(31687): WiFi turned off
I/jxcore-log(31687): 
,I/jxcore-log(31687): WiFi turned on
I/jxcore-log(31687): 
,I/jxcore-log(31687): No internet connection
I/jxcore-log(31687): 
,I/jxcore-log(31687): No internet connection
I/jxcore-log(31687): 
,I/jxcore-log(31687): No internet connection
I/jxcore-log(31687): ,
,I/jxcore-log(31687): No internet connection
I/jxcore-log(31687): 
,I/jxcore-log(31687): WiFi
I/jxcore-log(31687): 
,I/jxcore-log(31687): Response status code was: 200
I/jxcore-log(31687): 
,I/jxcore-log(31687): ****TEST TOOK:  10321  ms ****
I/jxcore-log(31687): 
I/jxcore-log(31687): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(31687): 


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
,W/jxcore-log( 8121): Initializing JXcore engine
,W/jxcore-log( 8121): JXcore engine is ready
,W/jxcore-log( 8121): Starting JXcore engine
,W/jxcore-log( 8121): Platform android,
W/jxcore-log( 8121): 
W/jxcore-log( 8121): Process ARCH arm
W/jxcore-log( 8121): 
,I/jxcore-log( 8121): JXcore Cordova bridge is ready!,
I/jxcore-log( 8121): 
,W/jxcore-log( 8121): JXcore engine is started
,E/jxcore-log( 8121): >> HTC-HTC One M8s,
E/jxcore-log( 8121): 
,I/jxcore-log( 8121): Total memory 1931808768,
I/jxcore-log( 8121): 
I/jxcore-log( 8121): Free memory 233058304
I/jxcore-log( 8121): 
I/jxcore-log( 8121): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): userPath [ 'www' ]
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): Size 1080 1776,
I/jxcore-log( 8121): 
I/jxcore-log( 8121): Screen Brightness 142
I/jxcore-log( 8121): 
E/jxcore-log( 8121): Dummy Error Log.
E/jxcore-log( 8121): 
,I/jxcore-log( 8121): getBuffer is called!!!!,
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): Bluetooth turned on,
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): WiFi turned off
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): WiFi turned on
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection,
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection,
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection,
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection,
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection,
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection,
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection,
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection,
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection,
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection,
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection,
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection,
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): Timeout in log.js file reached!
I/jxcore-log( 8121): 
I/jxcore-log( 8121): ****TEST TOOK:  125077  ms ****
I/jxcore-log( 8121): 
I/jxcore-log( 8121): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILURE]****
I/jxcore-log( 8121): 
,I/jxcore-log( 8121): No internet connection
I/jxcore-log( 8121): 


samsung-SM-A300FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(15795): Initializing JXcore engine
W/jxcore-log(15795): JXcore engine is ready
,W/jxcore-log(15795): Starting JXcore engine
,W/jxcore-log(15795): Platform android
W/jxcore-log(15795): 
W/jxcore-log(15795): Process ARCH arm
W/jxcore-log(15795): 
,I/jxcore-log(15795): JXcore Cordova bridge is ready!
I/jxcore-log(15795): 
,W/jxcore-log(15795): JXcore engine is started
,E/jxcore-log(15795): >> samsung-SM-A300FU
E/jxcore-log(15795): 
,I/jxcore-log(15795): Total memory 1451114496
I/jxcore-log(15795): 
,I/jxcore-log(15795): Free memory 19955712
I/jxcore-log(15795): 
I/jxcore-log(15795): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(15795): 
I/jxcore-log(15795): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(15795): 
,I/jxcore-log(15795): userPath [ 'www' ]
I/jxcore-log(15795): 
,I/jxcore-log(15795): Size 540 960
I/jxcore-log(15795): 
,I/jxcore-log(15795): Screen Brightness 160
I/jxcore-log(15795): 
,E/jxcore-log(15795): Dummy Error Log.
E/jxcore-log(15795): 
,I/jxcore-log(15795): getBuffer is called!!!!
I/jxcore-log(15795): 
,I/jxcore-log(15795): Bluetooth turned on
I/jxcore-log(15795): 
,I/jxcore-log(15795): WiFi turned off
I/jxcore-log(15795): 
,I/jxcore-log(15795): WiFi turned on
I/jxcore-log(15795): 
,I/jxcore-log(15795): No internet connection
I/jxcore-log(15795): 
,I/jxcore-log(15795): No internet connection
I/jxcore-log(15795): 
,I/jxcore-log(15795): No internet connection,
I/jxcore-log(15795): 
,I/jxcore-log(15795): No internet connection
I/jxcore-log(15795): 
,I/jxcore-log(15795): No internet connection
I/jxcore-log(15795): 
,I/jxcore-log(15795): No internet connection
I/jxcore-log(15795): 
,I/jxcore-log(15795): No internet connection
I/jxcore-log(15795): 
,I/jxcore-log(15795): WiFi
I/jxcore-log(15795): 
,I/jxcore-log(15795): Response status code was: 200
I/jxcore-log(15795): 
I/jxcore-log(15795): ****TEST TOOK:  13289  ms ****
I/jxcore-log(15795): 
I/jxcore-log(15795): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(15795): 


LGE-LG-D802: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log(14866): Initializing JXcore engine
,W/jxcore-log(14866): JXcore engine is ready
,W/jxcore-log(14866): Starting JXcore engine
,W/jxcore-log(14866): Platform android
W/jxcore-log(14866): 
,W/jxcore-log(14866): Process ARCH arm
W/jxcore-log(14866): 
,I/jxcore-log(14866): JXcore Cordova bridge is ready!
I/jxcore-log(14866): 
,W/jxcore-log(14866): JXcore engine is started
,E/jxcore-log(14866): >> LGE-LG-D802
E/jxcore-log(14866): 
,I/jxcore-log(14866): Total memory 1943035904
I/jxcore-log(14866): 
,I/jxcore-log(14866): Free memory 99401728
I/jxcore-log(14866): 
I/jxcore-log(14866): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(14866): 
,I/jxcore-log(14866): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(14866): 
,I/jxcore-log(14866): userPath [ 'www' ]
I/jxcore-log(14866): 
,I/jxcore-log(14866): Size 1080 1776
I/jxcore-log(14866): 
,I/jxcore-log(14866): Screen Brightness 255
I/jxcore-log(14866): 
,E/jxcore-log(14866): Dummy Error Log.
E/jxcore-log(14866): 
,I/jxcore-log(14866): getBuffer is called!!!!
I/jxcore-log(14866): 
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
,I/jxcore-log( 6275): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): found interfaceName: wlan0
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : false, has ip: 192.168.1.141
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): found interfaceName: wlan0
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : false, has ip: 192.168.1.141
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): found interfaceName: wlan0
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : false, has ip: 192.168.1.141
I/jxcore-log( 6275): 
,I/jxcore-log(14866): Bluetooth turned on
I/jxcore-log(14866): 
,I/jxcore-log(14866): WiFi turned off
I/jxcore-log(14866): 
,I/jxcore-log(14866): WiFi turned on
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
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
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
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
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
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
,I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
I/jxcore-log( 6275): found interfaceName: lo
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
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
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
I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
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
,I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
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
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
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
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
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
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
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
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
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
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
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
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
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
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
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
,I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
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
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
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
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
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
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
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
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
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
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
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
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
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
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
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
I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
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
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log(14866): No internet connection
I/jxcore-log(14866): 
,I/jxcore-log( 6275): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): found interfaceName: wlan0
I/jxcore-log( 6275): 
I/jxcore-log( 6275): -iface: IPv4 is internal : false, has ip: 192.168.1.141
I/jxcore-log( 6275): 
I/jxcore-log(14866): WiFi
I/jxcore-log(14866): 
,I/jxcore-log( 6275): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6275): 
I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
I/jxcore-log( 6275): found interfaceName: wlan0
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : false, has ip: 192.168.1.141
I/jxcore-log( 6275): 
,I/jxcore-log(14866): Response status code was: 200
I/jxcore-log(14866): 
,I/jxcore-log(14866): ****TEST TOOK:  110707  ms ****
I/jxcore-log(14866): 
,I/jxcore-log(14866): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(14866): 


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
,W/jxcore-log(23472): Initializing JXcore engine
W/jxcore-log(23472): JXcore engine is ready
,W/jxcore-log(23472): Starting JXcore engine
,W/jxcore-log(23472): Platform android
W/jxcore-log(23472): 
W/jxcore-log(23472): Process ARCH arm
W/jxcore-log(23472): 
,I/jxcore-log(23472): JXcore Cordova bridge is ready!
I/jxcore-log(23472): 
,W/jxcore-log(23472): JXcore engine is started
,E/jxcore-log(23472): >> samsung-SM-G900F
E/jxcore-log(23472): 
,I/jxcore-log(23472): Total memory 1787449344
I/jxcore-log(23472): 
,I/jxcore-log(23472): Free memory 55574528
I/jxcore-log(23472): 
I/jxcore-log(23472): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23472): 
,I/jxcore-log(23472): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23472): 
,I/jxcore-log(23472): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(23472): 
,I/jxcore-log(23472): Size 1080 1920
I/jxcore-log(23472): 
,I/jxcore-log(23472): Screen Brightness 134
I/jxcore-log(23472): 
,E/jxcore-log(23472): Dummy Error Log.
E/jxcore-log(23472): 
,I/jxcore-log(23472): getBuffer is called!!!!
I/jxcore-log(23472): 
,I/jxcore-log(23472): Bluetooth turned on
I/jxcore-log(23472): 
,I/jxcore-log(23472): WiFi turned off
I/jxcore-log(23472): 
,I/jxcore-log(23472): WiFi turned on
I/jxcore-log(23472): 
,I/jxcore-log(23472): No internet connection
I/jxcore-log(23472): 
,I/jxcore-log(23472): No internet connection
I/jxcore-log(23472): 
,I/jxcore-log(23472): No internet connection
I/jxcore-log(23472): 
,I/jxcore-log(23472): No internet connection
,I/jxcore-log(23472): 
,I/jxcore-log(23472): No internet connection
I/jxcore-log(23472): 
,I/jxcore-log(23472): WiFi
I/jxcore-log(23472): 
,I/jxcore-log(23472): Response status code was: 200
I/jxcore-log(23472): 
I/jxcore-log(23472): ****TEST TOOK:  11512  ms ****
I/jxcore-log(23472): 
I/jxcore-log(23472): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(23472): 


```

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
STOP log received from  HT574YC04723 Test has  SUCCEEDED
Device test finished on 4325e43f 
Device test finished on HT574YC04723 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(22791): Initializing JXcore engine
W/jxcore-log(22791): JXcore engine is ready
W/jxcore-log(22791): Starting JXcore engine
W/jxcore-log(22791): Platform android
W/jxcore-log(22791): 
W/jxcore-log(22791): Process ARCH arm
W/jxcore-log(22791): 
I/jxcore-log(22791): JXcore Cordova bridge is ready!
I/jxcore-log(22791): 
W/jxcore-log(22791): JXcore engine is started
E/jxcore-log(22791): >> samsung-SM-A300FU
E/jxcore-log(22791): 
I/jxcore-log(22791): Total memory 1451114496
I/jxcore-log(22791): 
I/jxcore-log(22791): Free memory 81240064
I/jxcore-log(22791): 
I/jxcore-log(22791): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(22791): 
I/jxcore-log(22791): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(22791): 
I/jxcore-log(22791): userPath [ 'www' ]
I/jxcore-log(22791): 
I/jxcore-log(22791): Size 540 960
I/jxcore-log(22791): 
I/jxcore-log(22791): Screen Brightness 255
I/jxcore-log(22791): 
E/jxcore-log(22791): Dummy Error Log.
E/jxcore-log(22791): 
,I/jxcore-log(22791): getBuffer is called!!!!
I/jxcore-log(22791): 
,I/jxcore-log(22791): Bluetooth turned on
I/jxcore-log(22791): 
,I/jxcore-log(22791): WiFi turned off
I/jxcore-log(22791): 
,I/jxcore-log(22791): WiFi turned on
I/jxcore-log(22791): 
,I/jxcore-log(22791): No internet connection
I/jxcore-log(22791): 
,I/jxcore-log(22791): No internet connection
I/jxcore-log(22791): 
,I/jxcore-log(22791): No internet connection
I/jxcore-log(22791): 
,I/jxcore-log(22791): No internet connection
I/jxcore-log(22791): 
,I/jxcore-log(22791): No internet connection
I/jxcore-log(22791): 
,I/jxcore-log(22791): No internet connection
I/jxcore-log(22791): 
,I/jxcore-log(22791): No internet connection
I/jxcore-log(22791): 
,I/jxcore-log(22791): No internet connection
I/jxcore-log(22791): 
,I/jxcore-log(22791): No internet connection
I/jxcore-log(22791): 
,I/jxcore-log(22791): WiFi
I/jxcore-log(22791): 
,I/jxcore-log(22791): Response status code was: 200
I/jxcore-log(22791): 
,I/jxcore-log(22791): ****TEST TOOK:  15290  ms ****
I/jxcore-log(22791): 
I/jxcore-log(22791): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(22791): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main,
--------- beginning of /dev/log/system
,W/jxcore-log(28462): Initializing JXcore engine
,W/jxcore-log(28462): JXcore engine is ready
,W/jxcore-log(28462): Starting JXcore engine
,W/jxcore-log(28462): Platform android
W/jxcore-log(28462): 
,W/jxcore-log(28462): Process ARCH arm
W/jxcore-log(28462): 
,I/jxcore-log(28462): JXcore Cordova bridge is ready!
I/jxcore-log(28462): 
,W/jxcore-log(28462): JXcore engine is started
,E/jxcore-log(28462): >> HTC-HTC Desire 820
E/jxcore-log(28462): 
,I/jxcore-log(28462): Total memory 1964650496
I/jxcore-log(28462): 
I/jxcore-log(28462): Free memory 166936576
I/jxcore-log(28462): 
,I/jxcore-log(28462): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(28462): 
,I/jxcore-log(28462): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(28462): 
,I/jxcore-log(28462): userPath [ 'www' ]
I/jxcore-log(28462): 
,I/jxcore-log(28462): Size 720 1184
I/jxcore-log(28462): 
,I/jxcore-log(28462): Screen Brightness 10
I/jxcore-log(28462): 
,E/jxcore-log(28462): Dummy Error Log.
E/jxcore-log(28462): 
,I/jxcore-log(28462): getBuffer is called!!!!
I/jxcore-log(28462): 
,I/jxcore-log(28462): Bluetooth turned on
I/jxcore-log(28462): 
,I/jxcore-log(28462): WiFi turned off
I/jxcore-log(28462): 
,I/jxcore-log(28462): WiFi turned on
I/jxcore-log(28462): 
,I/jxcore-log(28462): No internet connection
I/jxcore-log(28462): 
,I/jxcore-log(28462): No internet connection
I/jxcore-log(28462): 
,I/jxcore-log(28462): No internet connection
I/jxcore-log(28462): 
,I/jxcore-log(28462): No internet connection
I/jxcore-log(28462): 
,I/jxcore-log(28462): No internet connection
I/jxcore-log(28462): 
,I/jxcore-log(28462): No internet connection
I/jxcore-log(28462): 
,I/jxcore-log(28462): No internet connection
I/jxcore-log(28462): 
,I/jxcore-log(28462): No internet connection
I/jxcore-log(28462): 
,I/jxcore-log(28462): WiFi
I/jxcore-log(28462): 
,I/jxcore-log(28462): Response status code was: 200
I/jxcore-log(28462): 
I/jxcore-log(28462): ****TEST TOOK:  14863  ms ****
I/jxcore-log(28462): 
I/jxcore-log(28462): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(28462): 


```

####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log( 2674): Initializing JXcore engine
,W/jxcore-log( 2674): JXcore engine is ready
,W/jxcore-log( 2674): Starting JXcore engine
,W/jxcore-log( 2674): Platform android
W/jxcore-log( 2674): 
,W/jxcore-log( 2674): Process ARCH arm
W/jxcore-log( 2674): 
,I/jxcore-log( 2674): JXcore Cordova bridge is ready!
I/jxcore-log( 2674): 
,W/jxcore-log( 2674): JXcore engine is started
,E/jxcore-log( 2674): >> LGE-Nexus 5
E/jxcore-log( 2674): 
,I/jxcore-log( 2674): Total memory 1945137152
I/jxcore-log( 2674): 
I/jxcore-log( 2674): Free memory 395149312
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): userPath [ 'www' ]
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): Size 1080 1776
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): Screen Brightness 82
I/jxcore-log( 2674): 
,E/jxcore-log( 2674): Dummy Error Log.
E/jxcore-log( 2674): 
,I/jxcore-log( 2674): getBuffer is called!!!!
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): Bluetooth turned on
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): WiFi turned off
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): WiFi turned on
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): No internet connection
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): No internet connection
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): No internet connection
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): No internet connection
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): No internet connection
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): No internet connection
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): No internet connection
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): No internet connection
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): No internet connection
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): No internet connection
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): No internet connection
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): No internet connection
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): No internet connection
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): No internet connection
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): No internet connection
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): No internet connection
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): No internet connection
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): No internet connection
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): No internet connection
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): No internet connection
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): No internet connection
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): WiFi
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): Response status code was: 200
I/jxcore-log( 2674): 
I/jxcore-log( 2674): ****TEST TOOK:  27501  ms ****
I/jxcore-log( 2674): 
,I/jxcore-log( 2674): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2674): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log(20465): Initializing JXcore engine
,W/jxcore-log(20465): JXcore engine is ready
,W/jxcore-log(20465): Starting JXcore engine
,W/jxcore-log(20465): Platform android
W/jxcore-log(20465): 
,W/jxcore-log(20465): Process ARCH arm
W/jxcore-log(20465): 
,I/jxcore-log(20465): JXcore Cordova bridge is ready!
I/jxcore-log(20465): 
,W/jxcore-log(20465): JXcore engine is started
,E/jxcore-log(20465): >> HTC-HTC Desire 820
E/jxcore-log(20465): 
,I/jxcore-log(20465): Total memory 1964650496
I/jxcore-log(20465): 
I/jxcore-log(20465): Free memory 209891328
I/jxcore-log(20465): 
,I/jxcore-log(20465): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20465): 
,I/jxcore-log(20465): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20465): 
,I/jxcore-log(20465): userPath [ 'www' ]
I/jxcore-log(20465): 
,I/jxcore-log(20465): Size 720 1184
I/jxcore-log(20465): 
,I/jxcore-log(20465): Screen Brightness 142
I/jxcore-log(20465): 
,E/jxcore-log(20465): Dummy Error Log.
E/jxcore-log(20465): 
,I/jxcore-log(20465): getBuffer is called!!!!
I/jxcore-log(20465): 
,I/jxcore-log(20465): Bluetooth turned on
I/jxcore-log(20465): 
,I/jxcore-log(20465): WiFi turned off,
I/jxcore-log(20465): 
,I/jxcore-log(20465): WiFi turned on
I/jxcore-log(20465): 
,I/jxcore-log(20465): No internet connection
I/jxcore-log(20465): 
,I/jxcore-log(20465): No internet connection
I/jxcore-log(20465): 
,I/jxcore-log(20465): No internet connection
I/jxcore-log(20465): 
,I/jxcore-log(20465): No internet connection
I/jxcore-log(20465): 
,I/jxcore-log(20465): No internet connection
I/jxcore-log(20465): 
,I/jxcore-log(20465): No internet connection
I/jxcore-log(20465): 
,I/jxcore-log(20465): WiFi
I/jxcore-log(20465): 
,I/jxcore-log(20465): Request error was: Error: connect ENETUNREACH
I/jxcore-log(20465): 
I/jxcore-log(20465): Response status code was: null
I/jxcore-log(20465): 
I/jxcore-log(20465): ****TEST TOOK:  12296  ms ****
I/jxcore-log(20465): 
,I/jxcore-log(20465): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILURE]****
I/jxcore-log(20465): 


```


