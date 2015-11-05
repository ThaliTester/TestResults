#### Test 49526184a3a5cb3 Logs

Status: 
```

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":22,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_49526184a3a5cb3/Sub/serverApp/index.js',
  '{"devices":{"android":22,"cancel":1}}' ]

JSON { devices: { android: 22, cancel: 1 } }



android : false
```


#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":22,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_49526184a3a5cb3/Sub/serverApp/index.js',
  '{"devices":{"android":22,"cancel":1}}' ]

JSON { devices: { android: 22, cancel: 1 } }


```

###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  30049d9501da2100 Test has  SUCCEEDED
STOP log received from  03157df360a1882a Test has  SUCCEEDED
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
Device test finished on 30049d9501da2100 
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Device test finished on W3D7N15428022572 
Device test finished on 03157df360a1882a 
Android task is completed 
```

Logcat output:
```
samsung-SM-G920F: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(16256): Initializing JXcore engine
W/jxcore-log(16256): JXcore engine is ready
,W/jxcore-log(16256): Starting JXcore engine
,W/jxcore-log(16256): Platform android
W/jxcore-log(16256): 
W/jxcore-log(16256): Process ARCH arm
W/jxcore-log(16256): 
,I/jxcore-log(16256): JXcore Cordova bridge is ready!
I/jxcore-log(16256): 
W/jxcore-log(16256): JXcore engine is started
,E/jxcore-log(16256): >> samsung-SM-G920F
E/jxcore-log(16256): 
,I/jxcore-log(16256): Total memory 2829074432
I/jxcore-log(16256): 
I/jxcore-log(16256): Free memory 112881664
I/jxcore-log(16256): 
I/jxcore-log(16256): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(16256): 
I/jxcore-log(16256): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(16256): 
,I/jxcore-log(16256): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(16256): 
,I/jxcore-log(16256): Size 1440 2560
I/jxcore-log(16256): 
,I/jxcore-log(16256): Screen Brightness 255
I/jxcore-log(16256): 
E/jxcore-log(16256): Dummy Error Log.
E/jxcore-log(16256): 
,I/jxcore-log(16256): getBuffer is called!!!!
I/jxcore-log(16256): 
,I/jxcore-log(16256): Bluetooth turned on
I/jxcore-log(16256): 
,I/jxcore-log(16256): WiFi turned off
I/jxcore-log(16256): 
,I/jxcore-log(16256): WiFi turned on
I/jxcore-log(16256): 
,I/jxcore-log(16256): No internet connection
I/jxcore-log(16256): 
,I/jxcore-log(16256): No internet connection
I/jxcore-log(16256): 
,I/jxcore-log(16256): No internet connection
I/jxcore-log(16256): 
,I/jxcore-log(16256): No internet connection
I/jxcore-log(16256): 
,I/jxcore-log(16256): No internet connection
I/jxcore-log(16256): 
,I/jxcore-log(16256): WiFi
I/jxcore-log(16256): 
,I/jxcore-log(16256): Response status code was: 200
I/jxcore-log(16256): 
I/jxcore-log(16256): ****TEST TOOK:  11770  ms ****
I/jxcore-log(16256): 
I/jxcore-log(16256): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(16256): 


samsung-SM-T232: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log(16011): Initializing JXcore engine
W/jxcore-log(16011): JXcore engine is ready
W/jxcore-log(16011): Starting JXcore engine
W/jxcore-log(16011): Platform android
W/jxcore-log(16011): 
W/jxcore-log(16011): Process ARCH arm
W/jxcore-log(16011): 
I/jxcore-log(16011): JXcore Cordova bridge is ready!
I/jxcore-log(16011): 
W/jxcore-log(16011): JXcore engine is started
E/jxcore-log(16011): >> samsung-SM-T232
E/jxcore-log(16011): 
I/jxcore-log(16011): Total memory 1352024064
I/jxcore-log(16011): 
I/jxcore-log(16011): Free memory 234418176
I/jxcore-log(16011): 
I/jxcore-log(16011): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(16011): 
I/jxcore-log(16011): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(16011): 
I/jxcore-log(16011): userPath [ 'www' ]
I/jxcore-log(16011): 
I/jxcore-log(16011): Size 800 1280
I/jxcore-log(16011): 
I/jxcore-log(16011): Screen Brightness 255
I/jxcore-log(16011): 
E/jxcore-log(16011): Dummy Error Log.
E/jxcore-log(16011): 
,I/jxcore-log(16011): getBuffer is called!!!!
I/jxcore-log(16011): 
,I/jxcore-log(16011): Bluetooth turned on
I/jxcore-log(16011): 
,I/jxcore-log(16011): WiFi turned off
I/jxcore-log(16011): 
,I/jxcore-log(16011): WiFi turned on
I/jxcore-log(16011): 
,I/jxcore-log(16011): No internet connection
I/jxcore-log(16011): 
,I/jxcore-log(16011): No internet connection
I/jxcore-log(16011): 
,I/jxcore-log(16011): No internet connection
I/jxcore-log(16011): 
,I/jxcore-log(16011): No internet connection
I/jxcore-log(16011): 
,I/jxcore-log(16011): No internet connection
I/jxcore-log(16011): 
,I/jxcore-log(16011): WiFi
I/jxcore-log(16011): 
,I/jxcore-log(16011): Response status code was: 200
I/jxcore-log(16011): 
I/jxcore-log(16011): ****TEST TOOK:  11407  ms ****
I/jxcore-log(16011): 
,I/jxcore-log(16011): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(16011): 


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
,--------- beginning of system
,W/jxcore-log(26603): Initializing JXcore engine
W/jxcore-log(26603): JXcore engine is ready
W/jxcore-log(26603): Starting JXcore engine
W/jxcore-log(26603): Platform android
W/jxcore-log(26603): 
W/jxcore-log(26603): Process ARCH arm
W/jxcore-log(26603): 
I/jxcore-log(26603): JXcore Cordova bridge is ready!
I/jxcore-log(26603): 
W/jxcore-log(26603): JXcore engine is started
E/jxcore-log(26603): >> LGE-LG-H815
E/jxcore-log(26603): 
I/jxcore-log(26603): Total memory 2968948736
I/jxcore-log(26603): 
I/jxcore-log(26603): Free memory 277745664
I/jxcore-log(26603): 
I/jxcore-log(26603): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(26603): 
I/jxcore-log(26603): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(26603): 
I/jxcore-log(26603): userPath [ 'www' ]
I/jxcore-log(26603): 
I/jxcore-log(26603): Size 1440 2392
I/jxcore-log(26603): 
I/jxcore-log(26603): Screen Brightness 255
I/jxcore-log(26603): 
E/jxcore-log(26603): Dummy Error Log.
E/jxcore-log(26603): 
,I/jxcore-log(26603): getBuffer is called!!!!
I/jxcore-log(26603): 
,I/jxcore-log(26603): Bluetooth turned on
I/jxcore-log(26603): 
,I/jxcore-log(26603): WiFi turned off
I/jxcore-log(26603): 
,I/jxcore-log(26603): WiFi turned on
I/jxcore-log(26603): 
,I/jxcore-log(15361): DBG, CoordinatorConnector connect_error called
I/jxcore-log(15361): 
I/jxcore-log(15361): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ETIMEDOUT","errno":"ETIMEDOUT","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(15361): 
I/jxcore-log(15361): printNetworkInfo
I/jxcore-log(15361): 
,I/jxcore-log(15361): found interfaceName: lo
I/jxcore-log(15361): 
,I/jxcore-log(15361): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(15361): 
,I/jxcore-log(15361): DBG, CoordinatorConnector connect_error called
I/jxcore-log(15361): 
I/jxcore-log(15361): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(15361): 
I/jxcore-log(15361): printNetworkInfo
I/jxcore-log(15361): 
,I/jxcore-log(15361): found interfaceName: lo
I/jxcore-log(15361): 
I/jxcore-log(15361): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(15361): 
,I/jxcore-log(26603): No internet connection
I/jxcore-log(26603): 
,I/jxcore-log(26603): No internet connection
I/jxcore-log(26603): 
,I/jxcore-log(26603): No internet connection
I/jxcore-log(26603): 
,I/jxcore-log(26603): No internet connection
I/jxcore-log(26603): 
,I/jxcore-log(15361): DBG, CoordinatorConnector connect_error called
I/jxcore-log(15361): 
,I/jxcore-log(15361): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(15361): 
,I/jxcore-log(15361): printNetworkInfo
I/jxcore-log(15361): 
,I/jxcore-log(15361): found interfaceName: lo
I/jxcore-log(15361): 
,I/jxcore-log(15361): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(15361): 
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
,I/jxcore-log(15361): DBG, CoordinatorConnector connect_error called
I/jxcore-log(15361): 
,I/jxcore-log(15361): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(15361): 
I/jxcore-log(15361): printNetworkInfo
I/jxcore-log(15361): 
,I/jxcore-log(15361): found interfaceName: lo
I/jxcore-log(15361): 
,I/jxcore-log(15361): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(15361): 
,I/jxcore-log(26603): No internet connection
I/jxcore-log(26603): 
,I/jxcore-log(26603): No internet connection
I/jxcore-log(26603): 
,I/jxcore-log(26603): WiFi
I/jxcore-log(26603): 
,I/jxcore-log(26603): Response status code was: 200
I/jxcore-log(26603): 
I/jxcore-log(26603): ****TEST TOOK:  13004  ms ****
I/jxcore-log(26603): 
I/jxcore-log(26603): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(26603): 


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
W/jxcore-log( 9461): Initializing JXcore engine
W/jxcore-log( 9461): JXcore engine is ready
W/jxcore-log( 9461): Starting JXcore engine
,W/jxcore-log( 9461): Platform android
W/jxcore-log( 9461): 
W/jxcore-log( 9461): Process ARCH arm
W/jxcore-log( 9461): 
I/jxcore-log( 9461): JXcore Cordova bridge is ready!
I/jxcore-log( 9461): 
W/jxcore-log( 9461): JXcore engine is started
E/jxcore-log( 9461): >> HUAWEI-ALE-L21
E/jxcore-log( 9461): 
I/jxcore-log( 9461): Total memory 1949741056
I/jxcore-log( 9461): 
I/jxcore-log( 9461): Free memory 113074176
I/jxcore-log( 9461): 
I/jxcore-log( 9461): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9461): 
I/jxcore-log( 9461): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9461): 
I/jxcore-log( 9461): userPath [ 'www' ]
I/jxcore-log( 9461): 
I/jxcore-log( 9461): Size 720 1184
I/jxcore-log( 9461): 
I/jxcore-log( 9461): Screen Brightness 242
I/jxcore-log( 9461): 
E/jxcore-log( 9461): Dummy Error Log.
E/jxcore-log( 9461): 
I/jxcore-log( 9461): getBuffer is called!!!!
I/jxcore-log( 9461): 
,I/jxcore-log( 9461): Bluetooth turned on
I/jxcore-log( 9461): 
,I/jxcore-log( 9461): WiFi turned off
I/jxcore-log( 9461): 
,I/jxcore-log( 9461): WiFi turned on
I/jxcore-log( 9461): 
,I/jxcore-log( 9461): No internet connection
I/jxcore-log( 9461): 
,I/jxcore-log( 9461): No internet connection
I/jxcore-log( 9461): 
,I/jxcore-log( 9461): No internet connection
I/jxcore-log( 9461): 
,I/jxcore-log( 9461): No internet connection
I/jxcore-log( 9461): 
,I/jxcore-log( 9461): No internet connection
I/jxcore-log( 9461): 
,I/jxcore-log( 9461): No internet connection
I/jxcore-log( 9461): 
,I/jxcore-log( 9461): WiFi
I/jxcore-log( 9461): 
,I/jxcore-log( 9461): Response status code was: 200
I/jxcore-log( 9461): 
I/jxcore-log( 9461): ****TEST TOOK:  13105  ms ****
I/jxcore-log( 9461): 
I/jxcore-log( 9461): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9461): 


```

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
STOP log received from  FA533YJ03104 Test has  SUCCEEDED
Device test finished on FA533YJ03104 
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 8413): Initializing JXcore engine
W/jxcore-log( 8413): JXcore engine is ready
,W/jxcore-log( 8413): Starting JXcore engine
,W/jxcore-log( 8413): Platform android
W/jxcore-log( 8413): 
W/jxcore-log( 8413): Process ARCH arm
W/jxcore-log( 8413): 
,I/jxcore-log( 8413): JXcore Cordova bridge is ready!
I/jxcore-log( 8413): 
,W/jxcore-log( 8413): JXcore engine is started
,E/jxcore-log( 8413): >> LGE-Nexus 5
E/jxcore-log( 8413): 
I/jxcore-log( 8413): Total memory 1946181632
I/jxcore-log( 8413): 
I/jxcore-log( 8413): Free memory 333393920
I/jxcore-log( 8413): 
I/jxcore-log( 8413): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8413): 
I/jxcore-log( 8413): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): userPath [ 'www' ]
I/jxcore-log( 8413): 
I/jxcore-log( 8413): Size 1080 1776
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): Screen Brightness 82
I/jxcore-log( 8413): 
,E/jxcore-log( 8413): Dummy Error Log.
E/jxcore-log( 8413): 
,I/jxcore-log( 8413): getBuffer is called!!!!
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): Bluetooth turned on
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): WiFi turned off
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): WiFi turned on
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): Timeout in log.js file reached!
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): ****TEST TOOK:  125132  ms ****
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILURE]****
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 
,I/jxcore-log( 8413): No internet connection
I/jxcore-log( 8413): 


HTC-HTC One M9: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 7937): Initializing JXcore engine
W/jxcore-log( 7937): JXcore engine is ready
,W/jxcore-log( 7937): Starting JXcore engine
,W/jxcore-log( 7937): Platform android
W/jxcore-log( 7937): 
W/jxcore-log( 7937): Process ARCH arm
W/jxcore-log( 7937): 
,I/jxcore-log( 7937): JXcore Cordova bridge is ready!
I/jxcore-log( 7937): 
W/jxcore-log( 7937): JXcore engine is started
,E/jxcore-log( 7937): >> HTC-HTC One M9
E/jxcore-log( 7937): 
,I/jxcore-log( 7937): Total memory 2860257280
I/jxcore-log( 7937): 
I/jxcore-log( 7937): Free memory 148283392
I/jxcore-log( 7937): 
I/jxcore-log( 7937): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7937): 
I/jxcore-log( 7937): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7937): 
,I/jxcore-log( 7937): userPath [ 'www' ]
I/jxcore-log( 7937): 
,I/jxcore-log( 7937): Size 1080 1776
I/jxcore-log( 7937): 
I/jxcore-log( 7937): Screen Brightness 142
I/jxcore-log( 7937): 
E/jxcore-log( 7937): Dummy Error Log.
E/jxcore-log( 7937): 
,I/jxcore-log( 7937): getBuffer is called!!!!,
I/jxcore-log( 7937): 
,I/jxcore-log( 7937): Bluetooth turned on
I/jxcore-log( 7937): 
,I/jxcore-log( 7937): WiFi turned off
I/jxcore-log( 7937): 
,I/jxcore-log( 7937): WiFi turned on
I/jxcore-log( 7937): 
,I/jxcore-log( 7937): No internet connection
I/jxcore-log( 7937): 
,I/jxcore-log( 7937): No internet connection
I/jxcore-log( 7937): 
,I/jxcore-log( 7937): No internet connection,
I/jxcore-log( 7937): 
,I/jxcore-log( 7937): No internet connection
I/jxcore-log( 7937): 
,I/jxcore-log( 7937): No internet connection,
I/jxcore-log( 7937): 
,I/jxcore-log( 7937): No internet connection
I/jxcore-log( 7937): ,
,I/jxcore-log( 7937): WiFi
I/jxcore-log( 7937): 
,I/jxcore-log( 7937): Response status code was: 200,
I/jxcore-log( 7937): 
,I/jxcore-log( 7937): ****TEST TOOK:  12963  ms ****
I/jxcore-log( 7937): 
I/jxcore-log( 7937): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 7937): 


LGE-LG-D722: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(14368): Initializing JXcore engine
W/jxcore-log(14368): JXcore engine is ready
W/jxcore-log(14368): Starting JXcore engine
,W/jxcore-log(14368): Platform android
W/jxcore-log(14368): 
W/jxcore-log(14368): Process ARCH arm
W/jxcore-log(14368): 
,I/jxcore-log(14368): JXcore Cordova bridge is ready!
I/jxcore-log(14368): 
,W/jxcore-log(14368): JXcore engine is started
,E/jxcore-log(14368): >> LGE-LG-D722
E/jxcore-log(14368): 
I/jxcore-log(14368): Total memory 906309632
I/jxcore-log(14368): 
I/jxcore-log(14368): Free memory 17555456
I/jxcore-log(14368): 
I/jxcore-log(14368): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(14368): 
I/jxcore-log(14368): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(14368): 
,I/jxcore-log(14368): userPath [ 'www' ]
I/jxcore-log(14368): 
I/jxcore-log(14368): Size 720 1196
I/jxcore-log(14368): 
I/jxcore-log(14368): Screen Brightness 255
I/jxcore-log(14368): 
E/jxcore-log(14368): Dummy Error Log.
E/jxcore-log(14368): 
,I/jxcore-log(14368): getBuffer is called!!!!
I/jxcore-log(14368): 
,I/jxcore-log(14368): Bluetooth turned on
I/jxcore-log(14368): 
,I/jxcore-log(14368): WiFi turned off
I/jxcore-log(14368): 
,I/jxcore-log(14368): WiFi turned on
I/jxcore-log(14368): 
,I/jxcore-log(14368): No internet connection
I/jxcore-log(14368): 
,I/jxcore-log(14368): No internet connection
I/jxcore-log(14368): 
,I/jxcore-log(14368): WiFi
I/jxcore-log(14368): 
,I/jxcore-log(14368): Response status code was: 200
I/jxcore-log(14368): 
I/jxcore-log(14368): ****TEST TOOK:  8412  ms ****
I/jxcore-log(14368): 
I/jxcore-log(14368): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(14368): 


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
,W/jxcore-log(20998): Initializing JXcore engine
,W/jxcore-log(20998): JXcore engine is ready
,W/jxcore-log(20998): Starting JXcore engine
,W/jxcore-log(20998): Platform android
W/jxcore-log(20998): 
,W/jxcore-log(20998): Process ARCH arm
W/jxcore-log(20998): 
,I/jxcore-log(20998): JXcore Cordova bridge is ready!
I/jxcore-log(20998): 
,W/jxcore-log(20998): JXcore engine is started
,E/jxcore-log(20998): >> motorola-XT1039
E/jxcore-log(20998): 
,I/jxcore-log(20998): Total memory 893136896
I/jxcore-log(20998): 
I/jxcore-log(20998): Free memory 79929344
I/jxcore-log(20998): 
I/jxcore-log(20998): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20998): 
,I/jxcore-log(20998): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20998): 
,I/jxcore-log(20998): userPath [ 'www' ]
I/jxcore-log(20998): 
,I/jxcore-log(20998): Size 720 1184
I/jxcore-log(20998): 
,I/jxcore-log(20998): Screen Brightness 210
I/jxcore-log(20998): 
,E/jxcore-log(20998): Dummy Error Log.
E/jxcore-log(20998): 
,I/jxcore-log(20998): getBuffer is called!!!!
I/jxcore-log(20998): 
,I/jxcore-log(20998): Bluetooth turned on
I/jxcore-log(20998): 
,I/jxcore-log(20998): WiFi turned off
I/jxcore-log(20998): 
,I/jxcore-log(20998): WiFi turned on
I/jxcore-log(20998): 
,I/jxcore-log(20998): No internet connection
I/jxcore-log(20998): 
,I/jxcore-log(20998): No internet connection
I/jxcore-log(20998): 
,I/jxcore-log(20998): No internet connection
I/jxcore-log(20998): 
,I/jxcore-log(20998): No internet connection
I/jxcore-log(20998): 
,I/jxcore-log(20998): No internet connection
I/jxcore-log(20998): 
,I/jxcore-log(20998): WiFi
I/jxcore-log(20998): 
,I/jxcore-log(20998): Response status code was: 200
I/jxcore-log(20998): 
I/jxcore-log(20998): ****TEST TOOK:  12276  ms ****
I/jxcore-log(20998): 
,I/jxcore-log(20998): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(20998): 


LGE-LG-D855: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(22442): Initializing JXcore engine
W/jxcore-log(22442): JXcore engine is ready
W/jxcore-log(22442): Starting JXcore engine
W/jxcore-log(22442): Platform android
W/jxcore-log(22442): 
W/jxcore-log(22442): Process ARCH arm
W/jxcore-log(22442): 
I/jxcore-log(22442): JXcore Cordova bridge is ready!
I/jxcore-log(22442): 
W/jxcore-log(22442): JXcore engine is started
E/jxcore-log(22442): >> LGE-LG-D855
E/jxcore-log(22442): 
I/jxcore-log(22442): Total memory 2995761152
I/jxcore-log(22442): 
I/jxcore-log(22442): Free memory 286457856
I/jxcore-log(22442): 
I/jxcore-log(22442): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(22442): 
I/jxcore-log(22442): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(22442): 
I/jxcore-log(22442): userPath [ 'www' ]
I/jxcore-log(22442): 
I/jxcore-log(22442): Size 1440 2392
I/jxcore-log(22442): 
I/jxcore-log(22442): Screen Brightness 177
I/jxcore-log(22442): 
E/jxcore-log(22442): Dummy Error Log.
E/jxcore-log(22442): 
,I/jxcore-log(22442): getBuffer is called!!!!
I/jxcore-log(22442): 
,I/jxcore-log(22442): Bluetooth turned on
I/jxcore-log(22442): 
,I/jxcore-log(22442): WiFi turned off
I/jxcore-log(22442): 
,I/jxcore-log(22442): WiFi turned on
I/jxcore-log(22442): 
,I/jxcore-log(22442): No internet connection
I/jxcore-log(22442): 
,I/jxcore-log(22442): No internet connection
I/jxcore-log(22442): 
,I/jxcore-log(22442): WiFi
I/jxcore-log(22442): 
,I/jxcore-log(22442): Response status code was: 200
I/jxcore-log(22442): 
I/jxcore-log(22442): ****TEST TOOK:  8617  ms ****
I/jxcore-log(22442): 
I/jxcore-log(22442): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(22442): 


samsung-SM-G800F: 
--------- beginning of /dev/log/main
I/jxcore-log(20670): DBG, CoordinatorConnector connect_error called
I/jxcore-log(20670): 
I/jxcore-log(20670): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(20670): 
I/jxcore-log(20670): printNetworkInfo
I/jxcore-log(20670): 
I/jxcore-log(20670): found interfaceName: lo
I/jxcore-log(20670): 
I/jxcore-log(20670): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(20670): 
I/jxcore-log(20670): found interfaceName: wlan0
I/jxcore-log(20670): 
I/jxcore-log(20670): -iface: IPv4 is internal : false, has ip: 192.168.1.112
I/jxcore-log(20670): 
,--------- beginning of /dev/log/system
,W/jxcore-log(32556): Initializing JXcore engine
,W/jxcore-log(32556): JXcore engine is ready
,W/jxcore-log(32556): Starting JXcore engine
,W/jxcore-log(32556): Platform android
W/jxcore-log(32556): 
,W/jxcore-log(32556): Process ARCH arm
W/jxcore-log(32556): 
,I/jxcore-log(32556): JXcore Cordova bridge is ready!
I/jxcore-log(32556): 
,W/jxcore-log(32556): JXcore engine is started
,E/jxcore-log(32556): >> samsung-SM-G800F
E/jxcore-log(32556): 
,I/jxcore-log(32556): Total memory 1319530496
I/jxcore-log(32556): 
,I/jxcore-log(32556): Free memory 37462016
I/jxcore-log(32556): 
I/jxcore-log(32556): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32556): 
,I/jxcore-log(32556): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32556): 
,I/jxcore-log(32556): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(32556): 
,I/jxcore-log(32556): Size 720 1280
I/jxcore-log(32556): 
,I/jxcore-log(32556): Screen Brightness 255
I/jxcore-log(32556): 
,E/jxcore-log(32556): Dummy Error Log.
E/jxcore-log(32556): 
,I/jxcore-log(32556): getBuffer is called!!!!
I/jxcore-log(32556): 
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
,I/jxcore-log(20670): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
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
,I/jxcore-log(32556): Bluetooth turned on
I/jxcore-log(32556): 
,I/jxcore-log(32556): WiFi turned off
I/jxcore-log(32556): 
,I/jxcore-log(32556): WiFi turned on
I/jxcore-log(32556): 
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
,I/jxcore-log(32556): No internet connection
I/jxcore-log(32556): 
,I/jxcore-log(32556): No internet connection
I/jxcore-log(32556): 
,I/jxcore-log(32556): No internet connection
I/jxcore-log(32556): 
,I/jxcore-log(32556): No internet connection
I/jxcore-log(32556): 
,I/jxcore-log(32556): No internet connection
I/jxcore-log(32556): 
,I/jxcore-log(32556): WiFi
I/jxcore-log(32556): 
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
I/jxcore-log(20670): found interfaceName: lo
I/jxcore-log(20670): 
I/jxcore-log(20670): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(20670): 
,I/jxcore-log(20670): found interfaceName: wlan0
I/jxcore-log(20670): 
,I/jxcore-log(20670): -iface: IPv4 is internal : false, has ip: 192.168.1.112
I/jxcore-log(20670): 
,I/jxcore-log(32556): Response status code was: 200
I/jxcore-log(32556): 
I/jxcore-log(32556): ****TEST TOOK:  11554  ms ****
I/jxcore-log(32556): 
,I/jxcore-log(32556): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(32556): 


```

####Node name: thali05
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
STOP log received from  1d6a772d Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Device test finished on 1d6a772d 
STOP log received from  SH47FWM00508 Test has  SUCCEEDED
Device test finished on SH47FWM00508 
Android task is completed 
```

Logcat output:
```
HTC-HTC One_M8: 
--------- beginning of system
--------- beginning of main
,W/jxcore-log(31516): Initializing JXcore engine
W/jxcore-log(31516): JXcore engine is ready
,W/jxcore-log(31516): Starting JXcore engine
,W/jxcore-log(31516): Platform android
W/jxcore-log(31516): 
W/jxcore-log(31516): Process ARCH arm
W/jxcore-log(31516): 
,I/jxcore-log(31516): JXcore Cordova bridge is ready!
I/jxcore-log(31516): 
,W/jxcore-log(31516): JXcore engine is started
,E/jxcore-log(31516): >> HTC-HTC One_M8
E/jxcore-log(31516): 
,I/jxcore-log(31516): Total memory 1912020992
I/jxcore-log(31516): 
I/jxcore-log(31516): Free memory 433557504
I/jxcore-log(31516): 
I/jxcore-log(31516): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(31516): 
I/jxcore-log(31516): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(31516): 
,I/jxcore-log(31516): userPath [ 'www' ]
I/jxcore-log(31516): 
,I/jxcore-log(31516): Size 1080 1776
I/jxcore-log(31516): 
,I/jxcore-log(31516): Screen Brightness 142
I/jxcore-log(31516): 
,E/jxcore-log(31516): Dummy Error Log.
E/jxcore-log(31516): 
,I/jxcore-log(31516): getBuffer is called!!!!
I/jxcore-log(31516): 
,I/jxcore-log(31516): Bluetooth turned on,
,I/jxcore-log(31516): ,
,I/jxcore-log(31516): WiFi turned off,
I/jxcore-log(31516): 
,I/jxcore-log(31516): WiFi turned on,
I/jxcore-log(31516): 
,I/jxcore-log(31516): No internet connection,
I/jxcore-log(31516): 
,I/jxcore-log(31516): No internet connection,
I/jxcore-log(31516): 
,I/jxcore-log(31516): No internet connection,
I/jxcore-log(31516): 
,I/jxcore-log(31516): No internet connection
I/jxcore-log(31516): 
,I/jxcore-log(31516): No internet connection
I/jxcore-log(31516): 
,I/jxcore-log(31516): No internet connection,
,I/jxcore-log(31516): 
,I/jxcore-log(31516): WiFi
I/jxcore-log(31516): 
,I/jxcore-log(31516): Response status code was: 200
I/jxcore-log(31516): 
,I/jxcore-log(31516): ****TEST TOOK:  12362  ms ****
I/jxcore-log(31516): 
I/jxcore-log(31516): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(31516): 


samsung-SM-N9005: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 3663): Initializing JXcore engine
W/jxcore-log( 3663): JXcore engine is ready
,W/jxcore-log( 3663): Starting JXcore engine
,W/jxcore-log( 3663): Platform android
W/jxcore-log( 3663): 
,W/jxcore-log( 3663): Process ARCH arm
W/jxcore-log( 3663): 
,I/jxcore-log( 3663): JXcore Cordova bridge is ready!
I/jxcore-log( 3663): 
,W/jxcore-log( 3663): JXcore engine is started
,E/jxcore-log( 3663): >> samsung-SM-N9005
E/jxcore-log( 3663): 
,I/jxcore-log( 3663): Total memory 2971471872
I/jxcore-log( 3663): 
I/jxcore-log( 3663): Free memory 363950080
I/jxcore-log( 3663): 
I/jxcore-log( 3663): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3663): 
I/jxcore-log( 3663): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3663): 
,I/jxcore-log( 3663): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 3663): 
,I/jxcore-log( 3663): Size 1080 1920
I/jxcore-log( 3663): 
,I/jxcore-log( 3663): Screen Brightness 255
I/jxcore-log( 3663): 
,E/jxcore-log( 3663): Dummy Error Log.
E/jxcore-log( 3663): 
,I/jxcore-log( 3663): getBuffer is called!!!!
I/jxcore-log( 3663): 
,I/jxcore-log( 3663): Bluetooth turned on
I/jxcore-log( 3663): 
,I/jxcore-log( 3663): WiFi turned off
I/jxcore-log( 3663): 
,I/jxcore-log( 3663): WiFi turned on
I/jxcore-log( 3663): 
,I/jxcore-log( 3663): No internet connection
I/jxcore-log( 3663): 
,I/jxcore-log( 3663): No internet connection
I/jxcore-log( 3663): 
,I/jxcore-log( 3663): No internet connection
I/jxcore-log( 3663): 
,I/jxcore-log( 3663): No internet connection
I/jxcore-log( 3663): 
,I/jxcore-log( 3663): No internet connection
I/jxcore-log( 3663): 
,I/jxcore-log( 3663): WiFi
I/jxcore-log( 3663): 
,I/jxcore-log( 3663): Response status code was: 200
I/jxcore-log( 3663): 
I/jxcore-log( 3663): ****TEST TOOK:  11360  ms ****
I/jxcore-log( 3663): 
,I/jxcore-log( 3663): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3663): 


motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 2282): Initializing JXcore engine
W/jxcore-log( 2282): JXcore engine is ready
W/jxcore-log( 2282): Starting JXcore engine
W/jxcore-log( 2282): Platform android
W/jxcore-log( 2282): 
W/jxcore-log( 2282): Process ARCH arm
W/jxcore-log( 2282): 
I/jxcore-log( 2282): JXcore Cordova bridge is ready!
I/jxcore-log( 2282): 
W/jxcore-log( 2282): JXcore engine is started
E/jxcore-log( 2282): >> motorola-Nexus 6
E/jxcore-log( 2282): 
I/jxcore-log( 2282): Total memory 3114405888
I/jxcore-log( 2282): 
I/jxcore-log( 2282): Free memory 561025024
I/jxcore-log( 2282): 
I/jxcore-log( 2282): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2282): 
I/jxcore-log( 2282): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2282): 
I/jxcore-log( 2282): userPath [ 'www' ]
I/jxcore-log( 2282): 
I/jxcore-log( 2282): Size 1440 2392
I/jxcore-log( 2282): 
I/jxcore-log( 2282): Screen Brightness 82
I/jxcore-log( 2282): 
E/jxcore-log( 2282): Dummy Error Log.
E/jxcore-log( 2282): 
,I/jxcore-log( 2282): getBuffer is called!!!!
,I/jxcore-log( 2282): 
,I/jxcore-log( 2282): Bluetooth turned on
I/jxcore-log( 2282): 
,I/jxcore-log( 2282): WiFi turned off
I/jxcore-log( 2282): 
,I/jxcore-log( 2282): WiFi turned on
I/jxcore-log( 2282): 
,I/jxcore-log( 2282): No internet connection
I/jxcore-log( 2282): 
,I/jxcore-log( 2282): No internet connection
I/jxcore-log( 2282): 
,I/jxcore-log( 2282): No internet connection
I/jxcore-log( 2282): 
,I/jxcore-log( 2282): No internet connection
I/jxcore-log( 2282): 
,I/jxcore-log( 2282): No internet connection
I/jxcore-log( 2282): 
,I/jxcore-log( 2282): WiFi
I/jxcore-log( 2282): 
I/jxcore-log( 2282): Response status code was: 200
I/jxcore-log( 2282): 
I/jxcore-log( 2282): ****TEST TOOK:  11313  ms ****
I/jxcore-log( 2282): 
I/jxcore-log( 2282): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2282): 


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
--------- beginning of system,
--------- beginning of main
,W/jxcore-log( 9905): Initializing JXcore engine,
W/jxcore-log( 9905): JXcore engine is ready
,W/jxcore-log( 9905): Starting JXcore engine,
,W/jxcore-log( 9905): Platform android,
W/jxcore-log( 9905): 
W/jxcore-log( 9905): Process ARCH arm
W/jxcore-log( 9905): 
,I/jxcore-log( 9905): JXcore Cordova bridge is ready!
I/jxcore-log( 9905): 
W/jxcore-log( 9905): JXcore engine is started
,E/jxcore-log( 9905): >> HTC-HTC One M8s,
E/jxcore-log( 9905): 
,I/jxcore-log( 9905): Total memory 1931808768
I/jxcore-log( 9905): 
I/jxcore-log( 9905): Free memory 234094592
I/jxcore-log( 9905): 
I/jxcore-log( 9905): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9905): 
I/jxcore-log( 9905): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): userPath [ 'www' ],
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): Size 1080 1776,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): Screen Brightness 142,
I/jxcore-log( 9905): 
E/jxcore-log( 9905): Dummy Error Log.
E/jxcore-log( 9905): 
,I/jxcore-log( 9905): getBuffer is called!!!!,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): Bluetooth turned on,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): WiFi turned off,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): WiFi turned on
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
,I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection,
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): Timeout in log.js file reached!
I/jxcore-log( 9905): 
I/jxcore-log( 9905): ****TEST TOOK:  125101  ms ****
I/jxcore-log( 9905): 
I/jxcore-log( 9905): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILURE]****
I/jxcore-log( 9905): 
,I/jxcore-log( 9905): No internet connection
I/jxcore-log( 9905): 


samsung-SM-A300FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(20902): Initializing JXcore engine
W/jxcore-log(20902): JXcore engine is ready
W/jxcore-log(20902): Starting JXcore engine
W/jxcore-log(20902): Platform android
W/jxcore-log(20902): 
W/jxcore-log(20902): Process ARCH arm
W/jxcore-log(20902): 
I/jxcore-log(20902): JXcore Cordova bridge is ready!
I/jxcore-log(20902): 
W/jxcore-log(20902): JXcore engine is started
E/jxcore-log(20902): >> samsung-SM-A300FU
E/jxcore-log(20902): 
I/jxcore-log(20902): Total memory 1451114496
I/jxcore-log(20902): 
I/jxcore-log(20902): Free memory 74293248
I/jxcore-log(20902): 
I/jxcore-log(20902): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20902): 
I/jxcore-log(20902): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20902): 
I/jxcore-log(20902): userPath [ 'www' ]
I/jxcore-log(20902): 
I/jxcore-log(20902): Size 540 960
I/jxcore-log(20902): 
I/jxcore-log(20902): Screen Brightness 160
I/jxcore-log(20902): 
E/jxcore-log(20902): Dummy Error Log.
E/jxcore-log(20902): 
,I/jxcore-log(20902): getBuffer is called!!!!
I/jxcore-log(20902): 
,I/jxcore-log(20902): Bluetooth turned on
I/jxcore-log(20902): 
,I/jxcore-log(20902): WiFi turned off
I/jxcore-log(20902): 
,I/jxcore-log(20902): WiFi turned on
I/jxcore-log(20902): 
,I/jxcore-log(20902): No internet connection
I/jxcore-log(20902): 
,I/jxcore-log(20902): No internet connection
I/jxcore-log(20902): 
,I/jxcore-log(20902): No internet connection
I/jxcore-log(20902): 
,I/jxcore-log(20902): No internet connection
I/jxcore-log(20902): 
,I/jxcore-log(20902): No internet connection,
I/jxcore-log(20902): 
,I/jxcore-log(20902): No internet connection
I/jxcore-log(20902): 
,I/jxcore-log(20902): No internet connection,
I/jxcore-log(20902): 
,I/jxcore-log(20902): WiFi
I/jxcore-log(20902): 
,I/jxcore-log(20902): Response status code was: 200
I/jxcore-log(20902): 
,I/jxcore-log(20902): ****TEST TOOK:  14085  ms ****
I/jxcore-log(20902): 
I/jxcore-log(20902): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(20902): 


LGE-LG-D802: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,I/jxcore-log( 6275): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6275): 
I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
I/jxcore-log( 6275): found interfaceName: wlan0
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): -iface: IPv4 is internal : false, has ip: 192.168.1.141
I/jxcore-log( 6275): 
,W/jxcore-log(  869): Initializing JXcore engine
,W/jxcore-log(  869): JXcore engine is ready
,W/jxcore-log(  869): Starting JXcore engine
,W/jxcore-log(  869): Platform android
W/jxcore-log(  869): 
,W/jxcore-log(  869): Process ARCH arm
W/jxcore-log(  869): 
,I/jxcore-log(  869): JXcore Cordova bridge is ready!
I/jxcore-log(  869): 
,W/jxcore-log(  869): JXcore engine is started
,E/jxcore-log(  869): >> LGE-LG-D802
E/jxcore-log(  869): 
,I/jxcore-log(  869): Total memory 1943035904
I/jxcore-log(  869): 
I/jxcore-log(  869): Free memory 113119232
I/jxcore-log(  869): 
I/jxcore-log(  869): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(  869): 
,I/jxcore-log(  869): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(  869): 
,I/jxcore-log(  869): userPath [ 'www' ]
I/jxcore-log(  869): 
,I/jxcore-log(  869): Size 1080 1776
I/jxcore-log(  869): 
,I/jxcore-log(  869): Screen Brightness 255
I/jxcore-log(  869): 
,E/jxcore-log(  869): Dummy Error Log.
E/jxcore-log(  869): 
,I/jxcore-log(  869): getBuffer is called!!!!
I/jxcore-log(  869): 
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
,I/jxcore-log(  869): Bluetooth turned on
I/jxcore-log(  869): 
,I/jxcore-log(  869): WiFi turned off
I/jxcore-log(  869): 
,I/jxcore-log(  869): WiFi turned on
I/jxcore-log(  869): 
,I/jxcore-log(  869): No internet connection
I/jxcore-log(  869): 
,I/jxcore-log(  869): No internet connection
I/jxcore-log(  869): 
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
,I/jxcore-log(  869): No internet connection
I/jxcore-log(  869): 
,I/jxcore-log(  869): No internet connection
I/jxcore-log(  869): 
,I/jxcore-log(  869): No internet connection
I/jxcore-log(  869): 
,I/jxcore-log(  869): No internet connection
I/jxcore-log(  869): 
,I/jxcore-log(  869): No internet connection
I/jxcore-log(  869): 
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
,I/jxcore-log(  869): No internet connection
I/jxcore-log(  869): 
,I/jxcore-log(  869): No internet connection
I/jxcore-log(  869): 
,I/jxcore-log(  869): No internet connection
I/jxcore-log(  869): 
,I/jxcore-log(  869): No internet connection
I/jxcore-log(  869): 
,I/jxcore-log(  869): No internet connection
I/jxcore-log(  869): 
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
,I/jxcore-log(  869): No internet connection
I/jxcore-log(  869): 
,I/jxcore-log(  869): No internet connection
I/jxcore-log(  869): 
,I/jxcore-log(  869): No internet connection
I/jxcore-log(  869): 
,I/jxcore-log(  869): No internet connection
I/jxcore-log(  869): 
,I/jxcore-log(  869): No internet connection
I/jxcore-log(  869): 
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
,I/jxcore-log(  869): No internet connection
I/jxcore-log(  869): 
,I/jxcore-log(  869): No internet connection
I/jxcore-log(  869): 
,I/jxcore-log(  869): No internet connection
I/jxcore-log(  869): 
,I/jxcore-log(  869): WiFi
I/jxcore-log(  869): 
,I/jxcore-log( 6275): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6275): 
,I/jxcore-log( 6275): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"EHOSTUNREACH","errno":"EHOSTUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6275): 
I/jxcore-log( 6275): printNetworkInfo
I/jxcore-log( 6275): 
,I/jxcore-log(  869): Request error was: Error: connect EHOSTUNREACH
I/jxcore-log(  869): 
I/jxcore-log(  869): Response status code was: null
I/jxcore-log(  869): 
I/jxcore-log(  869): ****TEST TOOK:  29434  ms ****
I/jxcore-log(  869): 
,I/jxcore-log(  869): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILURE]****
I/jxcore-log(  869): 
,I/jxcore-log( 6275): found interfaceName: lo
I/jxcore-log( 6275): 
I/jxcore-log( 6275): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 6275): 
I/jxcore-log( 6275): found interfaceName: wlan0
I/jxcore-log( 6275): 
I/jxcore-log( 6275): -iface: IPv4 is internal : false, has ip: 192.168.1.141
I/jxcore-log( 6275): 


```

####Node name: thali07
Console output:
```
STOP log received from  f56ad48d Test has  SUCCEEDED
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on f56ad48d 
Device test finished on c5afcdcb 
Android task is completed 
```

Logcat output:
```
samsung-SM-A500FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 5939): Initializing JXcore engine
W/jxcore-log( 5939): JXcore engine is ready
,W/jxcore-log( 5939): Starting JXcore engine
,W/jxcore-log( 5939): Platform android
W/jxcore-log( 5939): 
W/jxcore-log( 5939): Process ARCH arm
W/jxcore-log( 5939): 
,I/jxcore-log( 5939): JXcore Cordova bridge is ready!
I/jxcore-log( 5939): 
,W/jxcore-log( 5939): JXcore engine is started
,E/jxcore-log( 5939): >> samsung-SM-A500FU
E/jxcore-log( 5939): 
,I/jxcore-log( 5939): Total memory 1983787008
I/jxcore-log( 5939): 
,I/jxcore-log( 5939): Free memory 36745216
I/jxcore-log( 5939): 
I/jxcore-log( 5939): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5939): 
I/jxcore-log( 5939): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5939): 
,I/jxcore-log( 5939): userPath [ 'rList-com.example.hello.MainActivity', 'www' ],
I/jxcore-log( 5939): 
,I/jxcore-log( 5939): Size 720 1280
I/jxcore-log( 5939): 
,I/jxcore-log( 5939): Screen Brightness 255
I/jxcore-log( 5939): 
,E/jxcore-log( 5939): Dummy Error Log.
E/jxcore-log( 5939): 
,I/jxcore-log( 5939): getBuffer is called!!!!
I/jxcore-log( 5939): 
,I/jxcore-log( 5939): Bluetooth turned on
I/jxcore-log( 5939): 
,I/jxcore-log( 5939): WiFi turned off,
I/jxcore-log( 5939): 
,I/jxcore-log( 5939): WiFi turned on
I/jxcore-log( 5939): 
,I/jxcore-log( 5939): No internet connection
I/jxcore-log( 5939): 
,I/jxcore-log( 5939): No internet connection
I/jxcore-log( 5939): 
,I/jxcore-log( 5939): No internet connection,
I/jxcore-log( 5939): 
,I/jxcore-log( 5939): No internet connection
I/jxcore-log( 5939): 
,I/jxcore-log( 5939): WiFi
I/jxcore-log( 5939): 
,I/jxcore-log( 5939): Response status code was: 200
I/jxcore-log( 5939): 
,I/jxcore-log( 5939): ****TEST TOOK:  16231  ms ****
I/jxcore-log( 5939): 
I/jxcore-log( 5939): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5939): 


samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(28131): Initializing JXcore engine
W/jxcore-log(28131): JXcore engine is ready
W/jxcore-log(28131): Starting JXcore engine
W/jxcore-log(28131): Platform android
W/jxcore-log(28131): 
W/jxcore-log(28131): Process ARCH arm
W/jxcore-log(28131): 
I/jxcore-log(28131): JXcore Cordova bridge is ready!
I/jxcore-log(28131): 
W/jxcore-log(28131): JXcore engine is started
E/jxcore-log(28131): >> samsung-SM-G900F
E/jxcore-log(28131): 
I/jxcore-log(28131): Total memory 1787449344
I/jxcore-log(28131): 
I/jxcore-log(28131): Free memory 66207744
I/jxcore-log(28131): 
I/jxcore-log(28131): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(28131): 
I/jxcore-log(28131): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(28131): 
I/jxcore-log(28131): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(28131): 
I/jxcore-log(28131): Size 1080 1920
I/jxcore-log(28131): 
I/jxcore-log(28131): Screen Brightness 134
I/jxcore-log(28131): 
E/jxcore-log(28131): Dummy Error Log.
E/jxcore-log(28131): 
,I/jxcore-log(28131): getBuffer is called!!!!
I/jxcore-log(28131): 
,I/jxcore-log(28131): Bluetooth turned on
I/jxcore-log(28131): 
,I/jxcore-log(28131): WiFi turned off
I/jxcore-log(28131): 
,I/jxcore-log(28131): WiFi turned on
I/jxcore-log(28131): 
,I/jxcore-log(28131): No internet connection
I/jxcore-log(28131): 
,I/jxcore-log(28131): No internet connection
I/jxcore-log(28131): 
,I/jxcore-log(28131): No internet connection
I/jxcore-log(28131): 
,I/jxcore-log(28131): No internet connection
I/jxcore-log(28131): 
,I/jxcore-log(28131): No internet connection
I/jxcore-log(28131): 
,I/jxcore-log(28131): WiFi
I/jxcore-log(28131): 
,I/jxcore-log(28131): Response status code was: 200
I/jxcore-log(28131): 
,I/jxcore-log(28131): ****TEST TOOK:  12313  ms ****
I/jxcore-log(28131): 
I/jxcore-log(28131): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(28131): 


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
--------- beginning of main
,W/jxcore-log(27557): Initializing JXcore engine
,W/jxcore-log(27557): JXcore engine is ready
,W/jxcore-log(27557): Starting JXcore engine
,W/jxcore-log(27557): Platform android
W/jxcore-log(27557): 
W/jxcore-log(27557): Process ARCH arm
W/jxcore-log(27557): 
,I/jxcore-log(27557): JXcore Cordova bridge is ready!
I/jxcore-log(27557): 
,W/jxcore-log(27557): JXcore engine is started
,E/jxcore-log(27557): >> samsung-SM-A300FU
E/jxcore-log(27557): 
,I/jxcore-log(27557): Total memory 1451114496
I/jxcore-log(27557): 
,I/jxcore-log(27557): Free memory 101761024
I/jxcore-log(27557): 
I/jxcore-log(27557): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(27557): 
I/jxcore-log(27557): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(27557): 
,I/jxcore-log(27557): userPath [ 'www' ]
I/jxcore-log(27557): 
,I/jxcore-log(27557): Size 540 960
I/jxcore-log(27557): 
,I/jxcore-log(27557): Screen Brightness 255
I/jxcore-log(27557): 
,E/jxcore-log(27557): Dummy Error Log.
E/jxcore-log(27557): 
,I/jxcore-log(27557): getBuffer is called!!!!
I/jxcore-log(27557): 
,I/jxcore-log(27557): Bluetooth turned on
I/jxcore-log(27557): 
,I/jxcore-log(27557): WiFi turned off
I/jxcore-log(27557): 
,I/jxcore-log(27557): WiFi turned on
I/jxcore-log(27557): 
,I/jxcore-log(27557): No internet connection
I/jxcore-log(27557): 
,I/jxcore-log(27557): No internet connection
I/jxcore-log(27557): 
,I/jxcore-log(27557): No internet connection
I/jxcore-log(27557): 
,I/jxcore-log(27557): No internet connection
I/jxcore-log(27557): 
,I/jxcore-log(27557): No internet connection
I/jxcore-log(27557): 
,I/jxcore-log(27557): No internet connection
I/jxcore-log(27557): 
,I/jxcore-log(27557): No internet connection
I/jxcore-log(27557): 
,I/jxcore-log(27557): WiFi
I/jxcore-log(27557): 
,I/jxcore-log(27557): Response status code was: 200,
I/jxcore-log(27557): 
I/jxcore-log(27557): ****TEST TOOK:  13748  ms ****
I/jxcore-log(27557): 
I/jxcore-log(27557): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(27557): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log(30073): Initializing JXcore engine
W/jxcore-log(30073): JXcore engine is ready
W/jxcore-log(30073): Starting JXcore engine
W/jxcore-log(30073): Platform android
W/jxcore-log(30073): 
W/jxcore-log(30073): Process ARCH arm
W/jxcore-log(30073): 
I/jxcore-log(30073): JXcore Cordova bridge is ready!
I/jxcore-log(30073): 
W/jxcore-log(30073): JXcore engine is started
E/jxcore-log(30073): >> HTC-HTC Desire 820
E/jxcore-log(30073): 
I/jxcore-log(30073): Total memory 1964650496
I/jxcore-log(30073): 
I/jxcore-log(30073): Free memory 161693696
I/jxcore-log(30073): 
I/jxcore-log(30073): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(30073): 
I/jxcore-log(30073): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(30073): 
I/jxcore-log(30073): userPath [ 'www' ]
I/jxcore-log(30073): 
I/jxcore-log(30073): Size 720 1184
I/jxcore-log(30073): 
I/jxcore-log(30073): Screen Brightness 10
I/jxcore-log(30073): 
E/jxcore-log(30073): Dummy Error Log.
E/jxcore-log(30073): 
,I/jxcore-log(30073): getBuffer is called!!!!
I/jxcore-log(30073): 
,I/jxcore-log(30073): Bluetooth turned on
I/jxcore-log(30073): 
,I/jxcore-log(30073): WiFi turned off
I/jxcore-log(30073): 
,I/jxcore-log(30073): WiFi turned on
I/jxcore-log(30073): 
,I/jxcore-log(30073): No internet connection
I/jxcore-log(30073): 
,I/jxcore-log(30073): No internet connection
I/jxcore-log(30073): 
,I/jxcore-log(30073): No internet connection
I/jxcore-log(30073): 
,I/jxcore-log(30073): No internet connection
I/jxcore-log(30073): 
,I/jxcore-log(30073): No internet connection
I/jxcore-log(30073): 
,I/jxcore-log(30073): No internet connection
I/jxcore-log(30073): 
,I/jxcore-log(30073): No internet connection
I/jxcore-log(30073): 
,I/jxcore-log(30073): WiFi
I/jxcore-log(30073): 
,I/jxcore-log(30073): Response status code was: 200
I/jxcore-log(30073): 
I/jxcore-log(30073): ****TEST TOOK:  15245  ms ****
I/jxcore-log(30073): 
,I/jxcore-log(30073): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(30073): 


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
,W/jxcore-log( 3957): Initializing JXcore engine
,W/jxcore-log( 3957): JXcore engine is ready
,W/jxcore-log( 3957): Starting JXcore engine
,W/jxcore-log( 3957): Platform android
W/jxcore-log( 3957): 
,W/jxcore-log( 3957): Process ARCH arm
W/jxcore-log( 3957): 
,I/jxcore-log( 3957): JXcore Cordova bridge is ready!
I/jxcore-log( 3957): 
,W/jxcore-log( 3957): JXcore engine is started
,E/jxcore-log( 3957): >> LGE-Nexus 5
E/jxcore-log( 3957): 
I/jxcore-log( 3957): Total memory 1945137152
I/jxcore-log( 3957): 
I/jxcore-log( 3957): Free memory 446410752
I/jxcore-log( 3957): 
I/jxcore-log( 3957): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3957): 
,I/jxcore-log( 3957): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3957): 
,I/jxcore-log( 3957): userPath [ 'www' ]
I/jxcore-log( 3957): 
,I/jxcore-log( 3957): Size 1080 1776
I/jxcore-log( 3957): 
I/jxcore-log( 3957): Screen Brightness 82
I/jxcore-log( 3957): 
,E/jxcore-log( 3957): Dummy Error Log.
E/jxcore-log( 3957): 
,I/jxcore-log( 3957): getBuffer is called!!!!
I/jxcore-log( 3957): 
,I/jxcore-log( 3957): Bluetooth turned on
I/jxcore-log( 3957): 
,I/jxcore-log( 3957): WiFi turned off
I/jxcore-log( 3957): 
,I/jxcore-log( 3957): WiFi turned on
I/jxcore-log( 3957): 
,I/jxcore-log( 3957): No internet connection
I/jxcore-log( 3957): 
,I/jxcore-log( 3957): No internet connection
I/jxcore-log( 3957): 
,I/jxcore-log( 3957): No internet connection
I/jxcore-log( 3957): 
,I/jxcore-log( 3957): No internet connection
I/jxcore-log( 3957): 
,I/jxcore-log( 3957): WiFi
I/jxcore-log( 3957): 
,I/jxcore-log( 3957): Response status code was: 200
I/jxcore-log( 3957): 
,I/jxcore-log( 3957): ****TEST TOOK:  10717  ms ****
I/jxcore-log( 3957): 
,I/jxcore-log( 3957): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3957): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log(22418): Initializing JXcore engine
,W/jxcore-log(22418): JXcore engine is ready
,W/jxcore-log(22418): Starting JXcore engine
,W/jxcore-log(22418): Platform android
W/jxcore-log(22418): 
,W/jxcore-log(22418): Process ARCH arm
W/jxcore-log(22418): 
,I/jxcore-log(22418): JXcore Cordova bridge is ready!
I/jxcore-log(22418): 
,W/jxcore-log(22418): JXcore engine is started
,E/jxcore-log(22418): >> HTC-HTC Desire 820
E/jxcore-log(22418): 
,I/jxcore-log(22418): Total memory 1964650496
I/jxcore-log(22418): 
I/jxcore-log(22418): Free memory 198156288
I/jxcore-log(22418): 
I/jxcore-log(22418): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(22418): 
,I/jxcore-log(22418): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(22418): 
,I/jxcore-log(22418): userPath [ 'www' ]
I/jxcore-log(22418): 
,I/jxcore-log(22418): Size 720 1184
I/jxcore-log(22418): 
,I/jxcore-log(22418): Screen Brightness 142
I/jxcore-log(22418): 
,E/jxcore-log(22418): Dummy Error Log.
E/jxcore-log(22418): 
,I/jxcore-log(22418): getBuffer is called!!!!
I/jxcore-log(22418): 
,I/jxcore-log(22418): Bluetooth turned on
I/jxcore-log(22418): 
,I/jxcore-log(22418): WiFi turned off
I/jxcore-log(22418): 
,I/jxcore-log(22418): WiFi turned on
I/jxcore-log(22418): 
,I/jxcore-log(22418): No internet connection
I/jxcore-log(22418): 
,I/jxcore-log(22418): No internet connection
I/jxcore-log(22418): 
,I/jxcore-log(22418): No internet connection
I/jxcore-log(22418): 
,I/jxcore-log(22418): No internet connection
I/jxcore-log(22418): 
,I/jxcore-log(22418): No internet connection
I/jxcore-log(22418): 
,I/jxcore-log(22418): No internet connection
I/jxcore-log(22418): 
,I/jxcore-log(22418): No internet connection
I/jxcore-log(22418): 
,I/jxcore-log(22418): WiFi
I/jxcore-log(22418): 
,I/jxcore-log(22418): Response status code was: 200
I/jxcore-log(22418): 
I/jxcore-log(22418): ****TEST TOOK:  17026  ms ****
I/jxcore-log(22418): 
,I/jxcore-log(22418): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(22418): 


```


