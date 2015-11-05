#### Test 49526184a3a5cb3 Logs

Status: 
```

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":20,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_49526184a3a5cb3/Sub/serverApp/index.js',
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
  '/home/pi/Test/server_49526184a3a5cb3/Sub/serverApp/index.js',
  '{"devices":{"android":20,"cancel":1}}' ]

JSON { devices: { android: 20, cancel: 1 } }


```

###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on W3D7N15428022572 
Device test finished on LGH8153b36be34 
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
,W/jxcore-log(11846): Initializing JXcore engine,
,W/jxcore-log(11846): JXcore engine is ready
,W/jxcore-log(11846): Starting JXcore engine
,W/jxcore-log(11846): Platform android
W/jxcore-log(11846): 
,W/jxcore-log(11846): Process ARCH arm
W/jxcore-log(11846): 
,I/jxcore-log(11846): JXcore Cordova bridge is ready!
I/jxcore-log(11846): 
,W/jxcore-log(11846): JXcore engine is started
,E/jxcore-log(11846): >> samsung-SM-G920F
E/jxcore-log(11846): 
,I/jxcore-log(11846): Total memory 2829074432
I/jxcore-log(11846): 
,I/jxcore-log(11846): Free memory 144138240
I/jxcore-log(11846): 
I/jxcore-log(11846): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11846): 
I/jxcore-log(11846): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11846): 
I/jxcore-log(11846): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(11846): 
I/jxcore-log(11846): Size 1440 2560
I/jxcore-log(11846): 
,I/jxcore-log(11846): Screen Brightness 255
I/jxcore-log(11846): 
,E/jxcore-log(11846): Dummy Error Log.
E/jxcore-log(11846): 
,I/jxcore-log(11846): getBuffer is called!!!!
I/jxcore-log(11846): 
,I/jxcore-log(11846): Bluetooth turned on
I/jxcore-log(11846): 
,I/jxcore-log(11846): WiFi turned off
I/jxcore-log(11846): 
,I/jxcore-log(11846): WiFi turned on
I/jxcore-log(11846): 
,I/jxcore-log(11846): No internet connection
I/jxcore-log(11846): 
,I/jxcore-log(11846): No internet connection
I/jxcore-log(11846): 
,I/jxcore-log(11846): No internet connection
I/jxcore-log(11846): 
,I/jxcore-log(11846): No internet connection
I/jxcore-log(11846): 
,I/jxcore-log(11846): No internet connection
I/jxcore-log(11846): 
,I/jxcore-log(11846): No internet connection
I/jxcore-log(11846): 
,I/jxcore-log(11846): WiFi
I/jxcore-log(11846): 
,I/jxcore-log(11846): Response status code was: 200
I/jxcore-log(11846): 
I/jxcore-log(11846): ****TEST TOOK:  12451  ms ****
I/jxcore-log(11846): 
,I/jxcore-log(11846): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11846): 


samsung-SM-T232: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log(13316): Initializing JXcore engine
W/jxcore-log(13316): JXcore engine is ready
W/jxcore-log(13316): Starting JXcore engine
W/jxcore-log(13316): Platform android
W/jxcore-log(13316): 
W/jxcore-log(13316): Process ARCH arm
W/jxcore-log(13316): 
I/jxcore-log(13316): JXcore Cordova bridge is ready!
I/jxcore-log(13316): 
W/jxcore-log(13316): JXcore engine is started
E/jxcore-log(13316): >> samsung-SM-T232
E/jxcore-log(13316): 
I/jxcore-log(13316): Total memory 1352024064
I/jxcore-log(13316): 
I/jxcore-log(13316): Free memory 156295168
I/jxcore-log(13316): 
I/jxcore-log(13316): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13316): 
I/jxcore-log(13316): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13316): 
I/jxcore-log(13316): userPath [ 'www' ]
I/jxcore-log(13316): 
I/jxcore-log(13316): Size 800 1280
I/jxcore-log(13316): 
I/jxcore-log(13316): Screen Brightness 255
I/jxcore-log(13316): 
E/jxcore-log(13316): Dummy Error Log.
E/jxcore-log(13316): 
,I/jxcore-log(13316): getBuffer is called!!!!
I/jxcore-log(13316): 
,I/jxcore-log(13316): Bluetooth turned on
I/jxcore-log(13316): 
,I/jxcore-log(13316): WiFi turned off
I/jxcore-log(13316): 
,I/jxcore-log(13316): WiFi turned on
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): Timeout in log.js file reached!
I/jxcore-log(13316): 
,I/jxcore-log(13316): ****TEST TOOK:  125116  ms ****
I/jxcore-log(13316): 
,I/jxcore-log(13316): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILURE]****
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 
,I/jxcore-log(13316): No internet connection
I/jxcore-log(13316): 


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
,--------- beginning of system
,W/jxcore-log(24210): Initializing JXcore engine
W/jxcore-log(24210): JXcore engine is ready
,W/jxcore-log(24210): Starting JXcore engine
,W/jxcore-log(24210): Platform android
W/jxcore-log(24210): 
W/jxcore-log(24210): Process ARCH arm
W/jxcore-log(24210): 
,I/jxcore-log(24210): JXcore Cordova bridge is ready!
I/jxcore-log(24210): 
,W/jxcore-log(24210): JXcore engine is started
,E/jxcore-log(24210): >> LGE-LG-H815
E/jxcore-log(24210): 
,I/jxcore-log(24210): Total memory 2968948736
I/jxcore-log(24210): 
,I/jxcore-log(24210): Free memory 380350464
I/jxcore-log(24210): 
I/jxcore-log(24210): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(24210): 
I/jxcore-log(24210): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(24210): 
,I/jxcore-log(24210): userPath [ 'www' ]
I/jxcore-log(24210): 
,I/jxcore-log(24210): Size 1440 2392
I/jxcore-log(24210): 
,I/jxcore-log(24210): Screen Brightness 255
I/jxcore-log(24210): 
,E/jxcore-log(24210): Dummy Error Log.
E/jxcore-log(24210): 
,I/jxcore-log(24210): getBuffer is called!!!!
I/jxcore-log(24210): 
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
,I/jxcore-log(24210): Bluetooth turned on
I/jxcore-log(24210): 
,I/jxcore-log(24210): WiFi turned off
I/jxcore-log(24210): 
,I/jxcore-log(24210): WiFi turned on
I/jxcore-log(24210): 
,I/jxcore-log(24210): No internet connection
I/jxcore-log(24210): 
,I/jxcore-log(24210): No internet connection
I/jxcore-log(24210): 
,I/jxcore-log(15361): DBG, CoordinatorConnector connect_error called
I/jxcore-log(15361): 
,I/jxcore-log(15361): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(15361): 
,I/jxcore-log(15361): printNetworkInfo
I/jxcore-log(15361): 
,I/jxcore-log(15361): found interfaceName: lo
I/jxcore-log(15361): 
I/jxcore-log(15361): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(15361): 
,I/jxcore-log(24210): No internet connection
I/jxcore-log(24210): 
,I/jxcore-log(24210): No internet connection
I/jxcore-log(24210): 
,I/jxcore-log(24210): No internet connection
I/jxcore-log(24210): 
,I/jxcore-log(24210): No internet connection
I/jxcore-log(24210): 
,I/jxcore-log(24210): WiFi
I/jxcore-log(24210): 
,I/jxcore-log(24210): Response status code was: 200
I/jxcore-log(24210): 
I/jxcore-log(24210): ****TEST TOOK:  12609  ms ****
I/jxcore-log(24210): 
I/jxcore-log(24210): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(24210): 
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
W/jxcore-log( 2792): Initializing JXcore engine
W/jxcore-log( 2792): JXcore engine is ready
W/jxcore-log( 2792): Starting JXcore engine
W/jxcore-log( 2792): Platform android
W/jxcore-log( 2792): 
W/jxcore-log( 2792): Process ARCH arm
W/jxcore-log( 2792): 
,I/jxcore-log( 2792): JXcore Cordova bridge is ready!
I/jxcore-log( 2792): 
W/jxcore-log( 2792): JXcore engine is started
,E/jxcore-log( 2792): >> HUAWEI-ALE-L21
E/jxcore-log( 2792): 
,I/jxcore-log( 2792): Total memory 1949741056
I/jxcore-log( 2792): 
,I/jxcore-log( 2792): Free memory 123666432
I/jxcore-log( 2792): 
I/jxcore-log( 2792): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2792): 
I/jxcore-log( 2792): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2792): 
,I/jxcore-log( 2792): userPath [ 'www' ]
I/jxcore-log( 2792): 
,I/jxcore-log( 2792): Size 720 1184
I/jxcore-log( 2792): 
,I/jxcore-log( 2792): Screen Brightness 242
I/jxcore-log( 2792): 
,E/jxcore-log( 2792): Dummy Error Log.
E/jxcore-log( 2792): 
,I/jxcore-log( 2792): getBuffer is called!!!!
I/jxcore-log( 2792): 
,I/jxcore-log( 2792): Bluetooth turned on
I/jxcore-log( 2792): 
,I/jxcore-log( 2792): WiFi turned off
I/jxcore-log( 2792): 
,I/jxcore-log( 2792): WiFi turned on
I/jxcore-log( 2792): 
,I/jxcore-log( 2792): No internet connection
I/jxcore-log( 2792): 
,I/jxcore-log( 2792): No internet connection
I/jxcore-log( 2792): 
,I/jxcore-log( 2792): No internet connection
I/jxcore-log( 2792): 
,I/jxcore-log( 2792): No internet connection
I/jxcore-log( 2792): 
,I/jxcore-log( 2792): No internet connection
I/jxcore-log( 2792): 
,I/jxcore-log( 2792): WiFi
I/jxcore-log( 2792): 
,I/jxcore-log( 2792): Response status code was: 200
I/jxcore-log( 2792): 
I/jxcore-log( 2792): ****TEST TOOK:  11321  ms ****
I/jxcore-log( 2792): 
I/jxcore-log( 2792): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2792): 


```

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Device test finished on 09a9416e0297d102 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 7342): Initializing JXcore engine
W/jxcore-log( 7342): JXcore engine is ready
,W/jxcore-log( 7342): Starting JXcore engine
,W/jxcore-log( 7342): Platform android
W/jxcore-log( 7342): 
,W/jxcore-log( 7342): Process ARCH arm
W/jxcore-log( 7342): 
,I/jxcore-log( 7342): JXcore Cordova bridge is ready!
I/jxcore-log( 7342): 
,W/jxcore-log( 7342): JXcore engine is started
,E/jxcore-log( 7342): >> LGE-Nexus 5
E/jxcore-log( 7342): 
,I/jxcore-log( 7342): Total memory 1946181632
I/jxcore-log( 7342): 
I/jxcore-log( 7342): Free memory 292851712
I/jxcore-log( 7342): 
I/jxcore-log( 7342): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7342): 
I/jxcore-log( 7342): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7342): 
,I/jxcore-log( 7342): userPath [ 'www' ]
I/jxcore-log( 7342): 
,I/jxcore-log( 7342): Size 1080 1776
I/jxcore-log( 7342): 
,I/jxcore-log( 7342): Screen Brightness 82
I/jxcore-log( 7342): 
,E/jxcore-log( 7342): Dummy Error Log.
E/jxcore-log( 7342): 
,I/jxcore-log( 7342): getBuffer is called!!!!
I/jxcore-log( 7342): 
,I/jxcore-log( 7342): Bluetooth turned on
I/jxcore-log( 7342): 
,I/jxcore-log( 7342): WiFi turned off
I/jxcore-log( 7342): 
,I/jxcore-log( 7342): WiFi turned on
I/jxcore-log( 7342): 
,I/jxcore-log( 7342): No internet connection
I/jxcore-log( 7342): 
,I/jxcore-log( 7342): No internet connection
I/jxcore-log( 7342): 
,I/jxcore-log( 7342): No internet connection
I/jxcore-log( 7342): 
,I/jxcore-log( 7342): No internet connection
I/jxcore-log( 7342): 
,I/jxcore-log( 7342): No internet connection
I/jxcore-log( 7342): 
,I/jxcore-log( 7342): WiFi
I/jxcore-log( 7342): 
,I/jxcore-log( 7342): Response status code was: 200
I/jxcore-log( 7342): 
I/jxcore-log( 7342): ****TEST TOOK:  11340  ms ****
I/jxcore-log( 7342): 
I/jxcore-log( 7342): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7342): 


LGE-LG-D722: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(10018): Initializing JXcore engine
W/jxcore-log(10018): JXcore engine is ready
,W/jxcore-log(10018): Starting JXcore engine
,W/jxcore-log(10018): Platform android
W/jxcore-log(10018): 
W/jxcore-log(10018): Process ARCH arm
W/jxcore-log(10018): 
,I/jxcore-log(10018): JXcore Cordova bridge is ready!
I/jxcore-log(10018): 
W/jxcore-log(10018): JXcore engine is started
E/jxcore-log(10018): >> LGE-LG-D722
E/jxcore-log(10018): 
,I/jxcore-log(10018): Total memory 906309632
I/jxcore-log(10018): 
,I/jxcore-log(10018): Free memory 17600512
I/jxcore-log(10018): 
I/jxcore-log(10018): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10018): 
I/jxcore-log(10018): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10018): 
,I/jxcore-log(10018): userPath [ 'www' ]
I/jxcore-log(10018): 
I/jxcore-log(10018): Size 720 1196
I/jxcore-log(10018): 
,I/jxcore-log(10018): Screen Brightness 255
I/jxcore-log(10018): 
,E/jxcore-log(10018): Dummy Error Log.
E/jxcore-log(10018): 
,I/jxcore-log(10018): getBuffer is called!!!!
I/jxcore-log(10018): 
,I/jxcore-log(10018): Bluetooth turned on
I/jxcore-log(10018): 
,I/jxcore-log(10018): WiFi turned off
I/jxcore-log(10018): 
,I/jxcore-log(10018): WiFi turned on
I/jxcore-log(10018): 
,I/jxcore-log(10018): No internet connection
I/jxcore-log(10018): 
,I/jxcore-log(10018): No internet connection
I/jxcore-log(10018): 
,I/jxcore-log(10018): No internet connection
I/jxcore-log(10018): 
,I/jxcore-log(10018): WiFi
I/jxcore-log(10018): 
,I/jxcore-log(10018): Response status code was: 200
I/jxcore-log(10018): 
,I/jxcore-log(10018): ****TEST TOOK:  9460  ms ****
I/jxcore-log(10018): 
I/jxcore-log(10018): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10018): 


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
,W/jxcore-log(19629): Initializing JXcore engine
,W/jxcore-log(19629): JXcore engine is ready
,W/jxcore-log(19629): Starting JXcore engine
,W/jxcore-log(19629): Platform android
W/jxcore-log(19629): 
,W/jxcore-log(19629): Process ARCH arm
W/jxcore-log(19629): 
,I/jxcore-log(19629): JXcore Cordova bridge is ready!
I/jxcore-log(19629): 
,W/jxcore-log(19629): JXcore engine is started
,E/jxcore-log(19629): >> motorola-XT1039
E/jxcore-log(19629): 
,I/jxcore-log(19629): Total memory 893136896
I/jxcore-log(19629): 
I/jxcore-log(19629): Free memory 59899904
I/jxcore-log(19629): 
,I/jxcore-log(19629): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19629): 
,I/jxcore-log(19629): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19629): 
,I/jxcore-log(19629): userPath [ 'www' ]
I/jxcore-log(19629): 
,I/jxcore-log(19629): Size 720 1184
I/jxcore-log(19629): 
,I/jxcore-log(19629): Screen Brightness 210
I/jxcore-log(19629): 
,E/jxcore-log(19629): Dummy Error Log.
E/jxcore-log(19629): 
,I/jxcore-log(19629): getBuffer is called!!!!
I/jxcore-log(19629): 
,I/jxcore-log(19629): Bluetooth turned on
I/jxcore-log(19629): 
,I/jxcore-log(19629): WiFi turned off
I/jxcore-log(19629): 
,I/jxcore-log(19629): WiFi turned on
I/jxcore-log(19629): 
,I/jxcore-log(19629): No internet connection
I/jxcore-log(19629): 
,I/jxcore-log(19629): No internet connection
I/jxcore-log(19629): 
,I/jxcore-log(19629): No internet connection
I/jxcore-log(19629): 
,I/jxcore-log(19629): No internet connection
I/jxcore-log(19629): 
,I/jxcore-log(19629): WiFi
I/jxcore-log(19629): 
,I/jxcore-log(19629): Response status code was: 200
I/jxcore-log(19629): 
I/jxcore-log(19629): ****TEST TOOK:  10329  ms ****
I/jxcore-log(19629): 
,I/jxcore-log(19629): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(19629): 


LGE-LG-D855: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(19766): Initializing JXcore engine
W/jxcore-log(19766): JXcore engine is ready
W/jxcore-log(19766): Starting JXcore engine
W/jxcore-log(19766): Platform android
W/jxcore-log(19766): 
W/jxcore-log(19766): Process ARCH arm
W/jxcore-log(19766): 
I/jxcore-log(19766): JXcore Cordova bridge is ready!
I/jxcore-log(19766): 
W/jxcore-log(19766): JXcore engine is started
E/jxcore-log(19766): >> LGE-LG-D855
E/jxcore-log(19766): 
I/jxcore-log(19766): Total memory 2995761152
I/jxcore-log(19766): 
I/jxcore-log(19766): Free memory 296935424
I/jxcore-log(19766): 
I/jxcore-log(19766): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19766): 
I/jxcore-log(19766): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19766): 
,I/jxcore-log(19766): userPath [ 'www' ]
I/jxcore-log(19766): 
,I/jxcore-log(19766): Size 1440 2392
I/jxcore-log(19766): 
,I/jxcore-log(19766): Screen Brightness 177
I/jxcore-log(19766): 
,E/jxcore-log(19766): Dummy Error Log.
E/jxcore-log(19766): 
,I/jxcore-log(19766): getBuffer is called!!!!
I/jxcore-log(19766): 
,I/jxcore-log(19766): Bluetooth turned on
I/jxcore-log(19766): 
,I/jxcore-log(19766): WiFi turned off
I/jxcore-log(19766): 
,I/jxcore-log(19766): WiFi turned on
I/jxcore-log(19766): 
,I/jxcore-log(19766): No internet connection
I/jxcore-log(19766): 
,I/jxcore-log(19766): No internet connection
I/jxcore-log(19766): 
,I/jxcore-log(19766): WiFi
I/jxcore-log(19766): 
,I/jxcore-log(19766): Response status code was: 200
I/jxcore-log(19766): 
,I/jxcore-log(19766): ****TEST TOOK:  8322  ms ****
I/jxcore-log(19766): 
I/jxcore-log(19766): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(19766): 


samsung-SM-G800F: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log(29274): Initializing JXcore engine
,W/jxcore-log(29274): JXcore engine is ready
,I/jxcore-log(20670): DBG, CoordinatorConnector connect_error called
I/jxcore-log(20670): 
,I/jxcore-log(20670): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(20670): 
,I/jxcore-log(20670): printNetworkInfo
I/jxcore-log(20670): 
,I/jxcore-log(20670): found interfaceName: lo
I/jxcore-log(20670): 
I/jxcore-log(20670): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(20670): 
,I/jxcore-log(20670): found interfaceName: wlan0
I/jxcore-log(20670): 
,I/jxcore-log(20670): -iface: IPv4 is internal : false, has ip: 192.168.1.112
I/jxcore-log(20670): 
,W/jxcore-log(29274): Starting JXcore engine
,I/jxcore-log(20670): DBG, CoordinatorConnector connect_error called
I/jxcore-log(20670): 
,I/jxcore-log(20670): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(20670): 
,I/jxcore-log(20670): printNetworkInfo
I/jxcore-log(20670): 
,I/jxcore-log(20670): found interfaceName: lo
I/jxcore-log(20670): 
I/jxcore-log(20670): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(20670): 
,I/jxcore-log(20670): found interfaceName: wlan0
I/jxcore-log(20670): 
,I/jxcore-log(20670): -iface: IPv4 is internal : false, has ip: 192.168.1.112
I/jxcore-log(20670): 
,W/jxcore-log(29274): Platform android
W/jxcore-log(29274): 
,W/jxcore-log(29274): Process ARCH arm
W/jxcore-log(29274): 
,I/jxcore-log(29274): JXcore Cordova bridge is ready!
I/jxcore-log(29274): 
,W/jxcore-log(29274): JXcore engine is started
,E/jxcore-log(29274): >> samsung-SM-G800F
E/jxcore-log(29274): 
,I/jxcore-log(29274): Total memory 1319530496
I/jxcore-log(29274): 
I/jxcore-log(29274): Free memory 34164736
I/jxcore-log(29274): 
I/jxcore-log(29274): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(29274): 
,I/jxcore-log(29274): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(29274): 
,I/jxcore-log(29274): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(29274): 
,I/jxcore-log(29274): Size 720 1280
I/jxcore-log(29274): 
,I/jxcore-log(29274): Screen Brightness 255
I/jxcore-log(29274): 
,E/jxcore-log(29274): Dummy Error Log.
E/jxcore-log(29274): 
,I/jxcore-log(29274): getBuffer is called!!!!
I/jxcore-log(29274): 
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
,I/jxcore-log(20670): found interfaceName: lo
I/jxcore-log(20670): 
I/jxcore-log(20670): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(20670): 
,I/jxcore-log(20670): found interfaceName: wlan0
I/jxcore-log(20670): 
,I/jxcore-log(20670): -iface: IPv4 is internal : false, has ip: 192.168.1.112
I/jxcore-log(20670): 
,I/jxcore-log(29274): Bluetooth turned on
I/jxcore-log(29274): 
,I/jxcore-log(29274): WiFi turned off
I/jxcore-log(29274): 
,I/jxcore-log(29274): WiFi turned on
I/jxcore-log(29274): 
,I/jxcore-log(29274): No internet connection
I/jxcore-log(29274): 
,I/jxcore-log(29274): No internet connection
I/jxcore-log(29274): 
,I/jxcore-log(29274): No internet connection
I/jxcore-log(29274): 
,I/jxcore-log(29274): No internet connection
I/jxcore-log(29274): 
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
,I/jxcore-log(29274): No internet connection
I/jxcore-log(29274): 
,I/jxcore-log(29274): WiFi
I/jxcore-log(29274): 
,I/jxcore-log(29274): Response status code was: 200
I/jxcore-log(29274): 
I/jxcore-log(29274): ****TEST TOOK:  11597  ms ****
I/jxcore-log(29274): 
,I/jxcore-log(29274): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(29274): 


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
--------- beginning of system,
--------- beginning of main
,W/jxcore-log(29929): Initializing JXcore engine,
W/jxcore-log(29929): JXcore engine is ready
,W/jxcore-log(29929): Starting JXcore engine
,W/jxcore-log(29929): Platform android
W/jxcore-log(29929): 
,W/jxcore-log(29929): Process ARCH arm
W/jxcore-log(29929): 
,I/jxcore-log(29929): JXcore Cordova bridge is ready!,
I/jxcore-log(29929): 
W/jxcore-log(29929): JXcore engine is started
,E/jxcore-log(29929): >> HTC-HTC One_M8
E/jxcore-log(29929): 
,I/jxcore-log(29929): Total memory 1912020992
I/jxcore-log(29929): 
,I/jxcore-log(29929): Free memory 410193920
I/jxcore-log(29929): 
I/jxcore-log(29929): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(29929): 
I/jxcore-log(29929): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(29929): 
,I/jxcore-log(29929): userPath [ 'www' ]
I/jxcore-log(29929): 
,I/jxcore-log(29929): Size 1080 1776
I/jxcore-log(29929): 
I/jxcore-log(29929): Screen Brightness 142
I/jxcore-log(29929): 
E/jxcore-log(29929): Dummy Error Log.
E/jxcore-log(29929): 
,I/jxcore-log(29929): getBuffer is called!!!!
I/jxcore-log(29929): 
,I/jxcore-log(29929): Bluetooth turned on,
,I/jxcore-log(29929): 
,I/jxcore-log(29929): WiFi turned off,
I/jxcore-log(29929): 
,I/jxcore-log(29929): WiFi turned on,
I/jxcore-log(29929): 
,I/jxcore-log(29929): No internet connection,
,I/jxcore-log(29929): 
,I/jxcore-log(29929): No internet connection
I/jxcore-log(29929): 
,I/jxcore-log(29929): No internet connection
I/jxcore-log(29929): 
,I/jxcore-log(29929): WiFi,
I/jxcore-log(29929): 
,I/jxcore-log(29929): Response status code was: 200
I/jxcore-log(29929): 
I/jxcore-log(29929): ****TEST TOOK:  9259  ms ****
I/jxcore-log(29929): 
I/jxcore-log(29929): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(29929): 


samsung-SM-N9005: 
--------- beginning of main,
--------- beginning of system
,W/jxcore-log( 1570): Initializing JXcore engine
,W/jxcore-log( 1570): JXcore engine is ready
,W/jxcore-log( 1570): Starting JXcore engine
,W/jxcore-log( 1570): Platform android
W/jxcore-log( 1570): 
W/jxcore-log( 1570): Process ARCH arm
W/jxcore-log( 1570): 
,I/jxcore-log( 1570): JXcore Cordova bridge is ready!
I/jxcore-log( 1570): 
,W/jxcore-log( 1570): JXcore engine is started
,E/jxcore-log( 1570): >> samsung-SM-N9005
E/jxcore-log( 1570): 
,I/jxcore-log( 1570): Total memory 2971471872
I/jxcore-log( 1570): 
,I/jxcore-log( 1570): Free memory 330100736
I/jxcore-log( 1570): 
I/jxcore-log( 1570): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1570): 
I/jxcore-log( 1570): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1570): 
,I/jxcore-log( 1570): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 1570): 
,I/jxcore-log( 1570): Size 1080 1920
I/jxcore-log( 1570): 
,I/jxcore-log( 1570): Screen Brightness 255
I/jxcore-log( 1570): 
,E/jxcore-log( 1570): Dummy Error Log.
E/jxcore-log( 1570): 
,I/jxcore-log( 1570): getBuffer is called!!!!
I/jxcore-log( 1570): 
,I/jxcore-log( 1570): Bluetooth turned on
I/jxcore-log( 1570): 
,I/jxcore-log( 1570): WiFi turned off
I/jxcore-log( 1570): 
,I/jxcore-log( 1570): WiFi turned on
I/jxcore-log( 1570): 
,I/jxcore-log( 1570): No internet connection
I/jxcore-log( 1570): 
,I/jxcore-log( 1570): No internet connection
I/jxcore-log( 1570): 
,I/jxcore-log( 1570): No internet connection
I/jxcore-log( 1570): 
,I/jxcore-log( 1570): No internet connection
I/jxcore-log( 1570): 
,I/jxcore-log( 1570): No internet connection
I/jxcore-log( 1570): 
,I/jxcore-log( 1570): No internet connection
I/jxcore-log( 1570): 
,I/jxcore-log( 1570): No internet connection
I/jxcore-log( 1570): 
,I/jxcore-log( 1570): WiFi
I/jxcore-log( 1570): 
,I/jxcore-log( 1570): Response status code was: 200
I/jxcore-log( 1570): 
I/jxcore-log( 1570): ****TEST TOOK:  13429  ms ****
I/jxcore-log( 1570): 
I/jxcore-log( 1570): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 1570): 


motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(32246): Initializing JXcore engine
,W/jxcore-log(32246): JXcore engine is ready
,W/jxcore-log(32246): Starting JXcore engine
,W/jxcore-log(32246): Platform android
W/jxcore-log(32246): 
,W/jxcore-log(32246): Process ARCH arm
W/jxcore-log(32246): 
,I/jxcore-log(32246): JXcore Cordova bridge is ready!
I/jxcore-log(32246): 
,W/jxcore-log(32246): JXcore engine is started
,E/jxcore-log(32246): >> motorola-Nexus 6
E/jxcore-log(32246): 
,I/jxcore-log(32246): Total memory 3114405888
I/jxcore-log(32246): 
,I/jxcore-log(32246): Free memory 553656320
I/jxcore-log(32246): 
I/jxcore-log(32246): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32246): 
I/jxcore-log(32246): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32246): 
I/jxcore-log(32246): userPath [ 'www' ]
I/jxcore-log(32246): 
I/jxcore-log(32246): Size 1440 2392
I/jxcore-log(32246): 
I/jxcore-log(32246): Screen Brightness 82
I/jxcore-log(32246): 
,E/jxcore-log(32246): Dummy Error Log.
E/jxcore-log(32246): 
,I/jxcore-log(32246): getBuffer is called!!!!
I/jxcore-log(32246): 
,I/jxcore-log(32246): Bluetooth turned on
I/jxcore-log(32246): 
,I/jxcore-log(32246): WiFi turned off
I/jxcore-log(32246): 
,I/jxcore-log(32246): WiFi turned on
I/jxcore-log(32246): 
,I/jxcore-log(32246): No internet connection
I/jxcore-log(32246): 
,I/jxcore-log(32246): No internet connection
I/jxcore-log(32246): 
,I/jxcore-log(32246): No internet connection
I/jxcore-log(32246): 
,I/jxcore-log(32246): No internet connection
I/jxcore-log(32246): 
,I/jxcore-log(32246): No internet connection
I/jxcore-log(32246): 
,I/jxcore-log(32246): No internet connection
I/jxcore-log(32246): 
,I/jxcore-log(32246): WiFi
I/jxcore-log(32246): 
,I/jxcore-log(32246): Response status code was: 200
I/jxcore-log(32246): 
I/jxcore-log(32246): ****TEST TOOK:  12310  ms ****
I/jxcore-log(32246): 
I/jxcore-log(32246): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(32246): 


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
,W/jxcore-log( 8896): Initializing JXcore engine
,W/jxcore-log( 8896): JXcore engine is ready
,W/jxcore-log( 8896): Starting JXcore engine,
,W/jxcore-log( 8896): Platform android,
W/jxcore-log( 8896): 
W/jxcore-log( 8896): Process ARCH arm
W/jxcore-log( 8896): 
,I/jxcore-log( 8896): JXcore Cordova bridge is ready!,
I/jxcore-log( 8896): 
W/jxcore-log( 8896): JXcore engine is started
,E/jxcore-log( 8896): >> HTC-HTC One M8s,
E/jxcore-log( 8896): 
,I/jxcore-log( 8896): Total memory 1931808768,
I/jxcore-log( 8896): 
I/jxcore-log( 8896): Free memory 238931968
I/jxcore-log( 8896): 
I/jxcore-log( 8896): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8896): 
I/jxcore-log( 8896): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8896): 
,I/jxcore-log( 8896): userPath [ 'www' ]
I/jxcore-log( 8896): 
I/jxcore-log( 8896): Size 1080 1776
I/jxcore-log( 8896): 
,I/jxcore-log( 8896): Screen Brightness 142,
I/jxcore-log( 8896): 
E/jxcore-log( 8896): Dummy Error Log.
E/jxcore-log( 8896): 
,I/jxcore-log( 8896): getBuffer is called!!!!,
I/jxcore-log( 8896): 
,I/jxcore-log( 8896): Bluetooth turned on,
I/jxcore-log( 8896): 
,I/jxcore-log( 8896): WiFi turned off
I/jxcore-log( 8896): 
,I/jxcore-log( 8896): WiFi turned on,
I/jxcore-log( 8896): 
,I/jxcore-log( 8896): No internet connection,
I/jxcore-log( 8896): 
,I/jxcore-log( 8896): No internet connection,
I/jxcore-log( 8896): 
,I/jxcore-log( 8896): No internet connection,
I/jxcore-log( 8896): 
,I/jxcore-log( 8896): No internet connection,
I/jxcore-log( 8896): 
,I/jxcore-log( 8896): No internet connection,
I/jxcore-log( 8896): 
,I/jxcore-log( 8896): No internet connection,
I/jxcore-log( 8896): 
,I/jxcore-log( 8896): WiFi,
I/jxcore-log( 8896): 
,I/jxcore-log( 8896): Response status code was: 200,
I/jxcore-log( 8896): 
I/jxcore-log( 8896): ****TEST TOOK:  12351  ms ****
I/jxcore-log( 8896): 
,I/jxcore-log( 8896): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 8896): 


samsung-SM-A300FU: 
--------- beginning of main,
--------- beginning of system
,W/jxcore-log(17214): Initializing JXcore engine
,W/jxcore-log(17214): JXcore engine is ready
,W/jxcore-log(17214): Starting JXcore engine
,W/jxcore-log(17214): Platform android
W/jxcore-log(17214): 
W/jxcore-log(17214): Process ARCH arm
W/jxcore-log(17214): 
,I/jxcore-log(17214): JXcore Cordova bridge is ready!
I/jxcore-log(17214): 
,W/jxcore-log(17214): JXcore engine is started
,E/jxcore-log(17214): >> samsung-SM-A300FU
E/jxcore-log(17214): 
,I/jxcore-log(17214): Total memory 1451114496
I/jxcore-log(17214): 
,I/jxcore-log(17214): Free memory 90841088
I/jxcore-log(17214): 
I/jxcore-log(17214): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(17214): 
I/jxcore-log(17214): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(17214): 
,I/jxcore-log(17214): userPath [ 'www' ]
I/jxcore-log(17214): 
,I/jxcore-log(17214): Size 540 960
I/jxcore-log(17214): 
,I/jxcore-log(17214): Screen Brightness 160
I/jxcore-log(17214): 
,E/jxcore-log(17214): Dummy Error Log.
E/jxcore-log(17214): 
,I/jxcore-log(17214): getBuffer is called!!!!
I/jxcore-log(17214): 
,I/jxcore-log(17214): Bluetooth turned on
I/jxcore-log(17214): 
,I/jxcore-log(17214): WiFi turned off
I/jxcore-log(17214): 
,I/jxcore-log(17214): WiFi turned on
I/jxcore-log(17214): 
,I/jxcore-log(17214): No internet connection
I/jxcore-log(17214): 
,I/jxcore-log(17214): No internet connection
I/jxcore-log(17214): 
,I/jxcore-log(17214): No internet connection
I/jxcore-log(17214): 
,I/jxcore-log(17214): No internet connection
I/jxcore-log(17214): 
,I/jxcore-log(17214): No internet connection
I/jxcore-log(17214): 
,I/jxcore-log(17214): No internet connection
I/jxcore-log(17214): 
,I/jxcore-log(17214): No internet connection
I/jxcore-log(17214): 
,I/jxcore-log(17214): WiFi
I/jxcore-log(17214): 
,I/jxcore-log(17214): Response status code was: 200
I/jxcore-log(17214): 
,I/jxcore-log(17214): ****TEST TOOK:  13286  ms ****
I/jxcore-log(17214): 
I/jxcore-log(17214): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(17214): 


LGE-LG-D802: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(17447): Initializing JXcore engine
,W/jxcore-log(17447): JXcore engine is ready
,W/jxcore-log(17447): Starting JXcore engine
,W/jxcore-log(17447): Platform android
W/jxcore-log(17447): 
,W/jxcore-log(17447): Process ARCH arm
W/jxcore-log(17447): 
,I/jxcore-log(17447): JXcore Cordova bridge is ready!
I/jxcore-log(17447): 
,W/jxcore-log(17447): JXcore engine is started
,E/jxcore-log(17447): >> LGE-LG-D802
E/jxcore-log(17447): 
,I/jxcore-log(17447): Total memory 1943035904
I/jxcore-log(17447): 
,I/jxcore-log(17447): Free memory 122339328
I/jxcore-log(17447): 
I/jxcore-log(17447): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(17447): 
,I/jxcore-log(17447): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(17447): 
,I/jxcore-log(17447): userPath [ 'www' ]
I/jxcore-log(17447): 
,I/jxcore-log(17447): Size 1080 1776
I/jxcore-log(17447): 
,I/jxcore-log(17447): Screen Brightness 255
I/jxcore-log(17447): 
,E/jxcore-log(17447): Dummy Error Log.
E/jxcore-log(17447): 
,I/jxcore-log(17447): getBuffer is called!!!!
I/jxcore-log(17447): 
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
,I/jxcore-log(17447): Bluetooth turned on
I/jxcore-log(17447): 
,I/jxcore-log(17447): WiFi turned off
I/jxcore-log(17447): 
,I/jxcore-log(17447): WiFi turned on
I/jxcore-log(17447): 
,I/jxcore-log(17447): No internet connection
I/jxcore-log(17447): 
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
,I/jxcore-log(17447): No internet connection
I/jxcore-log(17447): 
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
,I/jxcore-log(17447): No internet connection
I/jxcore-log(17447): 
,I/jxcore-log(17447): No internet connection
I/jxcore-log(17447): 
,I/jxcore-log(17447): No internet connection
I/jxcore-log(17447): 
,I/jxcore-log(17447): No internet connection
I/jxcore-log(17447): 
,I/jxcore-log(17447): No internet connection
I/jxcore-log(17447): 
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
,I/jxcore-log(17447): No internet connection
I/jxcore-log(17447): 
,I/jxcore-log(17447): No internet connection
I/jxcore-log(17447): 
,I/jxcore-log(17447): No internet connection
I/jxcore-log(17447): 
,I/jxcore-log(17447): No internet connection
I/jxcore-log(17447): 
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
,I/jxcore-log(17447): No internet connection
I/jxcore-log(17447): 
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
,I/jxcore-log(17447): No internet connection
I/jxcore-log(17447): 
,I/jxcore-log(17447): No internet connection
I/jxcore-log(17447): 
,I/jxcore-log(17447): No internet connection
I/jxcore-log(17447): 
,I/jxcore-log(17447): WiFi
I/jxcore-log(17447): 
,I/jxcore-log(17447): Response status code was: 200
I/jxcore-log(17447): 
I/jxcore-log(17447): ****TEST TOOK:  22256  ms ****
I/jxcore-log(17447): 
,I/jxcore-log(17447): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(17447): 
,I/jxcore-log( 6275): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6275): 
I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
I/jxcore-log( 6275): found interfaceName: wlan0
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : false, has ip: 192.168.1.141
I/jxcore-log( 6275): 


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
,W/jxcore-log(25388): Initializing JXcore engine
W/jxcore-log(25388): JXcore engine is ready
,W/jxcore-log(25388): Starting JXcore engine
,W/jxcore-log(25388): Platform android
W/jxcore-log(25388): 
W/jxcore-log(25388): Process ARCH arm
W/jxcore-log(25388): 
,I/jxcore-log(25388): JXcore Cordova bridge is ready!
I/jxcore-log(25388): 
,W/jxcore-log(25388): JXcore engine is started
,E/jxcore-log(25388): >> samsung-SM-G900F
E/jxcore-log(25388): 
,I/jxcore-log(25388): Total memory 1787449344
I/jxcore-log(25388): 
,I/jxcore-log(25388): Free memory 65785856
I/jxcore-log(25388): 
I/jxcore-log(25388): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25388): 
I/jxcore-log(25388): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25388): 
,I/jxcore-log(25388): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(25388): 
,I/jxcore-log(25388): Size 1080 1920
I/jxcore-log(25388): 
,I/jxcore-log(25388): Screen Brightness 134
I/jxcore-log(25388): 
,E/jxcore-log(25388): Dummy Error Log.
E/jxcore-log(25388): 
,I/jxcore-log(25388): getBuffer is called!!!!
I/jxcore-log(25388): 
,I/jxcore-log(25388): Bluetooth turned on
I/jxcore-log(25388): 
,I/jxcore-log(25388): WiFi turned off
I/jxcore-log(25388): 
,I/jxcore-log(25388): WiFi turned on
I/jxcore-log(25388): 
,I/jxcore-log(25388): No internet connection
I/jxcore-log(25388): 
,I/jxcore-log(25388): No internet connection
I/jxcore-log(25388): 
,I/jxcore-log(25388): No internet connection
I/jxcore-log(25388): 
,I/jxcore-log(25388): No internet connection
I/jxcore-log(25388): 
,I/jxcore-log(25388): No internet connection
I/jxcore-log(25388): 
,I/jxcore-log(25388): No internet connection
I/jxcore-log(25388): 
,I/jxcore-log(25388): WiFi
I/jxcore-log(25388): 
,I/jxcore-log(25388): Response status code was: 200
I/jxcore-log(25388): 
,I/jxcore-log(25388): ****TEST TOOK:  12460  ms ****
I/jxcore-log(25388): 
,I/jxcore-log(25388): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(25388): 


```

####Node name: thali08
Console output:
```
STOP log received from  HT574YC04723 Test has  SUCCEEDED
Device test finished on HT574YC04723 
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(23922): Initializing JXcore engine
W/jxcore-log(23922): JXcore engine is ready
,W/jxcore-log(23922): Starting JXcore engine
,W/jxcore-log(23922): Platform android
W/jxcore-log(23922): 
W/jxcore-log(23922): Process ARCH arm
W/jxcore-log(23922): 
,I/jxcore-log(23922): JXcore Cordova bridge is ready!
I/jxcore-log(23922): 
,W/jxcore-log(23922): JXcore engine is started
,E/jxcore-log(23922): >> samsung-SM-A300FU
E/jxcore-log(23922): 
,I/jxcore-log(23922): Total memory 1451114496
I/jxcore-log(23922): 
,I/jxcore-log(23922): Free memory 132382720
I/jxcore-log(23922): 
I/jxcore-log(23922): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23922): 
I/jxcore-log(23922): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23922): 
,I/jxcore-log(23922): userPath [ 'www' ]
I/jxcore-log(23922): 
,I/jxcore-log(23922): Size 540 960
I/jxcore-log(23922): 
,I/jxcore-log(23922): Screen Brightness 255
I/jxcore-log(23922): 
,E/jxcore-log(23922): Dummy Error Log.
E/jxcore-log(23922): 
,I/jxcore-log(23922): getBuffer is called!!!!,
I/jxcore-log(23922): 
,I/jxcore-log(23922): Bluetooth turned on
I/jxcore-log(23922): 
,I/jxcore-log(23922): WiFi turned off,
I/jxcore-log(23922): 
,I/jxcore-log(23922): WiFi turned on
I/jxcore-log(23922): 
,I/jxcore-log(23922): No internet connection
I/jxcore-log(23922): 
,I/jxcore-log(23922): No internet connection
I/jxcore-log(23922): 
,I/jxcore-log(23922): No internet connection
I/jxcore-log(23922): 
,I/jxcore-log(23922): No internet connection
I/jxcore-log(23922): 
,I/jxcore-log(23922): No internet connection
I/jxcore-log(23922): 
,I/jxcore-log(23922): No internet connection
I/jxcore-log(23922): 
,I/jxcore-log(23922): No internet connection
I/jxcore-log(23922): 
,I/jxcore-log(23922): No internet connection
I/jxcore-log(23922): 
,I/jxcore-log(23922): No internet connection,
,I/jxcore-log(23922): 
,I/jxcore-log(23922): WiFi
I/jxcore-log(23922): 
,I/jxcore-log(23922): Response status code was: 200
I/jxcore-log(23922): 
,I/jxcore-log(23922): ****TEST TOOK:  15285  ms ****
I/jxcore-log(23922): 
,I/jxcore-log(23922): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(23922): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log(29167): Initializing JXcore engine
W/jxcore-log(29167): JXcore engine is ready
W/jxcore-log(29167): Starting JXcore engine
W/jxcore-log(29167): Platform android
W/jxcore-log(29167): 
W/jxcore-log(29167): Process ARCH arm
W/jxcore-log(29167): 
I/jxcore-log(29167): JXcore Cordova bridge is ready!
I/jxcore-log(29167): 
W/jxcore-log(29167): JXcore engine is started
E/jxcore-log(29167): >> HTC-HTC Desire 820
E/jxcore-log(29167): 
I/jxcore-log(29167): Total memory 1964650496
I/jxcore-log(29167): 
I/jxcore-log(29167): Free memory 166572032
I/jxcore-log(29167): 
I/jxcore-log(29167): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(29167): 
I/jxcore-log(29167): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(29167): 
I/jxcore-log(29167): userPath [ 'www' ]
I/jxcore-log(29167): 
I/jxcore-log(29167): Size 720 1184
I/jxcore-log(29167): 
I/jxcore-log(29167): Screen Brightness 10
I/jxcore-log(29167): 
E/jxcore-log(29167): Dummy Error Log.
E/jxcore-log(29167): 
,I/jxcore-log(29167): getBuffer is called!!!!
I/jxcore-log(29167): 
,I/jxcore-log(29167): Bluetooth turned on
I/jxcore-log(29167): 
,I/jxcore-log(29167): WiFi turned off
I/jxcore-log(29167): 
,I/jxcore-log(29167): WiFi turned on
I/jxcore-log(29167): 
,I/jxcore-log(29167): No internet connection
I/jxcore-log(29167): 
,I/jxcore-log(29167): No internet connection
I/jxcore-log(29167): 
,I/jxcore-log(29167): No internet connection
I/jxcore-log(29167): 
,I/jxcore-log(29167): No internet connection
I/jxcore-log(29167): 
,I/jxcore-log(29167): No internet connection
I/jxcore-log(29167): 
,I/jxcore-log(29167): No internet connection
I/jxcore-log(29167): 
,I/jxcore-log(29167): WiFi
I/jxcore-log(29167): 
,I/jxcore-log(29167): Response status code was: 200
I/jxcore-log(29167): 
,I/jxcore-log(29167): ****TEST TOOK:  12945  ms ****
I/jxcore-log(29167): 
,I/jxcore-log(29167): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(29167): 


```

####Node name: thali09
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
Device test finished on CC51WYC03425 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log( 3105): Initializing JXcore engine
,W/jxcore-log( 3105): JXcore engine is ready
,W/jxcore-log( 3105): Starting JXcore engine
,W/jxcore-log( 3105): Platform android
W/jxcore-log( 3105): 
,W/jxcore-log( 3105): Process ARCH arm
W/jxcore-log( 3105): 
,I/jxcore-log( 3105): JXcore Cordova bridge is ready!
I/jxcore-log( 3105): 
,W/jxcore-log( 3105): JXcore engine is started
,E/jxcore-log( 3105): >> LGE-Nexus 5
E/jxcore-log( 3105): 
,I/jxcore-log( 3105): Total memory 1945137152
I/jxcore-log( 3105): 
I/jxcore-log( 3105): Free memory 394481664
I/jxcore-log( 3105): 
I/jxcore-log( 3105): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3105): 
,I/jxcore-log( 3105): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3105): 
,I/jxcore-log( 3105): userPath [ 'www' ]
I/jxcore-log( 3105): 
,I/jxcore-log( 3105): Size 1080 1776
I/jxcore-log( 3105): 
,I/jxcore-log( 3105): Screen Brightness 82
I/jxcore-log( 3105): 
,E/jxcore-log( 3105): Dummy Error Log.
E/jxcore-log( 3105): 
,I/jxcore-log( 3105): getBuffer is called!!!!
I/jxcore-log( 3105): 
,I/jxcore-log( 3105): Bluetooth turned on
I/jxcore-log( 3105): 
,I/jxcore-log( 3105): WiFi turned off
I/jxcore-log( 3105): 
,I/jxcore-log( 3105): WiFi turned on
I/jxcore-log( 3105): 
,I/jxcore-log( 3105): No internet connection
I/jxcore-log( 3105): 
,I/jxcore-log( 3105): No internet connection
I/jxcore-log( 3105): 
,I/jxcore-log( 3105): No internet connection
I/jxcore-log( 3105): 
,I/jxcore-log( 3105): No internet connection
I/jxcore-log( 3105): 
,I/jxcore-log( 3105): No internet connection
I/jxcore-log( 3105): 
,I/jxcore-log( 3105): WiFi
I/jxcore-log( 3105): 
,I/jxcore-log( 3105): Response status code was: 200
I/jxcore-log( 3105): 
,I/jxcore-log( 3105): ****TEST TOOK:  11390  ms ****
I/jxcore-log( 3105): 
,I/jxcore-log( 3105): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3105): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main,
--------- beginning of /dev/log/system
,W/jxcore-log(21185): Initializing JXcore engine,
,W/jxcore-log(21185): JXcore engine is ready
,W/jxcore-log(21185): Starting JXcore engine
,W/jxcore-log(21185): Platform android
W/jxcore-log(21185): 
,W/jxcore-log(21185): Process ARCH arm
W/jxcore-log(21185): 
,I/jxcore-log(21185): JXcore Cordova bridge is ready!
I/jxcore-log(21185): 
,W/jxcore-log(21185): JXcore engine is started
,E/jxcore-log(21185): >> HTC-HTC Desire 820
E/jxcore-log(21185): 
,I/jxcore-log(21185): Total memory 1964650496
I/jxcore-log(21185): 
I/jxcore-log(21185): Free memory 198356992
I/jxcore-log(21185): 
I/jxcore-log(21185): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21185): 
,I/jxcore-log(21185): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21185): 
,I/jxcore-log(21185): userPath [ 'www' ]
I/jxcore-log(21185): 
,I/jxcore-log(21185): Size 720 1184
I/jxcore-log(21185): 
,I/jxcore-log(21185): Screen Brightness 142
I/jxcore-log(21185): 
,E/jxcore-log(21185): Dummy Error Log.
E/jxcore-log(21185): 
,I/jxcore-log(21185): getBuffer is called!!!!
I/jxcore-log(21185): 
,I/jxcore-log(21185): Bluetooth turned on
I/jxcore-log(21185): 
,I/jxcore-log(21185): WiFi turned off
I/jxcore-log(21185): 
,I/jxcore-log(21185): WiFi turned on
I/jxcore-log(21185): 
,I/jxcore-log(21185): No internet connection
I/jxcore-log(21185): 
,I/jxcore-log(21185): No internet connection
I/jxcore-log(21185): 
,I/jxcore-log(21185): No internet connection
I/jxcore-log(21185): 
,I/jxcore-log(21185): No internet connection
I/jxcore-log(21185): 
,I/jxcore-log(21185): No internet connection
I/jxcore-log(21185): 
,I/jxcore-log(21185): No internet connection
I/jxcore-log(21185): 
,I/jxcore-log(21185): No internet connection
I/jxcore-log(21185): 
,I/jxcore-log(21185): WiFi
I/jxcore-log(21185): 
,I/jxcore-log(21185): Response status code was: 200
I/jxcore-log(21185): 
I/jxcore-log(21185): ****TEST TOOK:  14390  ms ****
I/jxcore-log(21185): 
,I/jxcore-log(21185): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(21185): 


```


