#### Test 49526184176a311 Logs

Status: 
```

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":25}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_49526184176a311/Sub/serverApp/index.js',
  '{"devices":{"android":25}}' ]

JSON { devices: { android: 25 } }



android : false
```


#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":25}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_49526184176a311/Sub/serverApp/index.js',
  '{"devices":{"android":25}}' ]

JSON { devices: { android: 25 } }


```

###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  30049d9501da2100 Test has  SUCCEEDED
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
STOP log received from  03157df360a1882a Test has  SUCCEEDED
Device test finished on 30049d9501da2100 
Device test finished on W3D7N15428022572 
Device test finished on LGH8153b36be34 
Device test finished on 03157df360a1882a 
Android task is completed 
```

Logcat output:
```
samsung-SM-G920F: 
--------- beginning of system
--------- beginning of main
,W/jxcore-log(10836): Initializing JXcore engine
W/jxcore-log(10836): JXcore engine is ready
,W/jxcore-log(10836): Starting JXcore engine
,W/jxcore-log(10836): Platform android
W/jxcore-log(10836): 
W/jxcore-log(10836): Process ARCH arm
W/jxcore-log(10836): 
,I/jxcore-log(10836): JXcore Cordova bridge is ready!
I/jxcore-log(10836): 
W/jxcore-log(10836): JXcore engine is started
,E/jxcore-log(10836): >> samsung-SM-G920F
E/jxcore-log(10836): 
,I/jxcore-log(10836): Total memory 2829074432
I/jxcore-log(10836): 
I/jxcore-log(10836): Free memory 323444736
I/jxcore-log(10836): 
I/jxcore-log(10836): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10836): 
I/jxcore-log(10836): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10836): 
,I/jxcore-log(10836): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(10836): 
,I/jxcore-log(10836): Size 1440 2560
I/jxcore-log(10836): 
,I/jxcore-log(10836): Screen Brightness 255
I/jxcore-log(10836): 
E/jxcore-log(10836): Dummy Error Log.
E/jxcore-log(10836): 
,I/jxcore-log(10836): getBuffer is called!!!!
I/jxcore-log(10836): 
,I/jxcore-log(10836): ****TEST TOOK:  5122  ms ****
I/jxcore-log(10836): 
I/jxcore-log(10836): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10836): 


samsung-SM-T232: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log(32511): Initializing JXcore engine
W/jxcore-log(32511): JXcore engine is ready
W/jxcore-log(32511): Starting JXcore engine
,W/jxcore-log(32511): Platform android
W/jxcore-log(32511): 
W/jxcore-log(32511): Process ARCH arm
W/jxcore-log(32511): 
I/jxcore-log(32511): JXcore Cordova bridge is ready!
I/jxcore-log(32511): 
W/jxcore-log(32511): JXcore engine is started
E/jxcore-log(32511): >> samsung-SM-T232
E/jxcore-log(32511): 
I/jxcore-log(32511): Total memory 1352024064
I/jxcore-log(32511): 
I/jxcore-log(32511): Free memory 234868736
I/jxcore-log(32511): 
I/jxcore-log(32511): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32511): 
I/jxcore-log(32511): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32511): 
I/jxcore-log(32511): userPath [ 'www' ]
I/jxcore-log(32511): 
I/jxcore-log(32511): Size 800 1280
I/jxcore-log(32511): 
I/jxcore-log(32511): Screen Brightness 255
I/jxcore-log(32511): 
E/jxcore-log(32511): Dummy Error Log.
E/jxcore-log(32511): 
,I/jxcore-log(32511): getBuffer is called!!!!
I/jxcore-log(32511): 
,I/jxcore-log(32511): ****TEST TOOK:  5111  ms ****
I/jxcore-log(32511): 
,I/jxcore-log(32511): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(32511): 


LGE-LG-H815: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(30448): Initializing JXcore engine
W/jxcore-log(30448): JXcore engine is ready
W/jxcore-log(30448): Starting JXcore engine
W/jxcore-log(30448): Platform android
W/jxcore-log(30448): 
W/jxcore-log(30448): Process ARCH arm
W/jxcore-log(30448): 
I/jxcore-log(30448): JXcore Cordova bridge is ready!
I/jxcore-log(30448): 
W/jxcore-log(30448): JXcore engine is started
E/jxcore-log(30448): >> LGE-LG-H815
E/jxcore-log(30448): 
I/jxcore-log(30448): Total memory 2968948736
I/jxcore-log(30448): 
I/jxcore-log(30448): Free memory 180690944
I/jxcore-log(30448): 
I/jxcore-log(30448): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(30448): 
I/jxcore-log(30448): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(30448): 
I/jxcore-log(30448): userPath [ 'www' ]
I/jxcore-log(30448): 
I/jxcore-log(30448): Size 1440 2392
I/jxcore-log(30448): 
I/jxcore-log(30448): Screen Brightness 255
I/jxcore-log(30448): 
E/jxcore-log(30448): Dummy Error Log.
E/jxcore-log(30448): 
,I/jxcore-log(30448): getBuffer is called!!!!
I/jxcore-log(30448): 
,I/jxcore-log(25812): DBG, CoordinatorConnector connect_error called
I/jxcore-log(25812): 
,I/jxcore-log(25812): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(25812): 
I/jxcore-log(25812): printNetworkInfo
I/jxcore-log(25812): 
,I/jxcore-log(25812): found interfaceName: lo
I/jxcore-log(25812): 
I/jxcore-log(25812): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(25812): 
,I/jxcore-log(30448): ****TEST TOOK:  5091  ms ****
I/jxcore-log(30448): 
I/jxcore-log(30448): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(30448): 
,I/jxcore-log(25812): DBG, CoordinatorConnector connect_error called
I/jxcore-log(25812): 
,I/jxcore-log(25812): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(25812): 
I/jxcore-log(25812): printNetworkInfo
I/jxcore-log(25812): 
I/jxcore-log(25812): found interfaceName: lo
I/jxcore-log(25812): 
I/jxcore-log(25812): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(25812): 
,I/jxcore-log(25812): DBG, CoordinatorConnector connect_error called
I/jxcore-log(25812): 
I/jxcore-log(25812): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log(25812): 
I/jxcore-log(25812): printNetworkInfo
I/jxcore-log(25812): 
,I/jxcore-log(25812): found interfaceName: lo
I/jxcore-log(25812): 
I/jxcore-log(25812): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log(25812): 


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
,W/jxcore-log(10969): Initializing JXcore engine
W/jxcore-log(10969): JXcore engine is ready
W/jxcore-log(10969): Starting JXcore engine
W/jxcore-log(10969): Platform android
W/jxcore-log(10969): 
W/jxcore-log(10969): Process ARCH arm
W/jxcore-log(10969): 
I/jxcore-log(10969): JXcore Cordova bridge is ready!
I/jxcore-log(10969): 
W/jxcore-log(10969): JXcore engine is started
E/jxcore-log(10969): >> HUAWEI-ALE-L21
E/jxcore-log(10969): 
I/jxcore-log(10969): Total memory 1949741056
I/jxcore-log(10969): 
I/jxcore-log(10969): Free memory 169721856
I/jxcore-log(10969): 
I/jxcore-log(10969): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10969): 
I/jxcore-log(10969): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10969): 
I/jxcore-log(10969): userPath [ 'www' ]
I/jxcore-log(10969): 
I/jxcore-log(10969): Size 720 1184
I/jxcore-log(10969): 
I/jxcore-log(10969): Screen Brightness 242
I/jxcore-log(10969): 
E/jxcore-log(10969): Dummy Error Log.
E/jxcore-log(10969): 
I/jxcore-log(10969): getBuffer is called!!!!
I/jxcore-log(10969): 
,I/jxcore-log(10969): ****TEST TOOK:  5120  ms ****
I/jxcore-log(10969): 
I/jxcore-log(10969): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10969): 


```

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(13283): Initializing JXcore engine
W/jxcore-log(13283): JXcore engine is ready
,W/jxcore-log(13283): Starting JXcore engine
,W/jxcore-log(13283): Platform android
W/jxcore-log(13283): 
W/jxcore-log(13283): Process ARCH arm
W/jxcore-log(13283): 
,I/jxcore-log(13283): JXcore Cordova bridge is ready!
I/jxcore-log(13283): 
,W/jxcore-log(13283): JXcore engine is started
,E/jxcore-log(13283): >> LGE-Nexus 5
E/jxcore-log(13283): 
I/jxcore-log(13283): Total memory 1946181632
I/jxcore-log(13283): 
I/jxcore-log(13283): Free memory 366145536
I/jxcore-log(13283): 
I/jxcore-log(13283): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13283): 
I/jxcore-log(13283): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13283): 
,I/jxcore-log(13283): userPath [ 'www' ]
I/jxcore-log(13283): 
,I/jxcore-log(13283): Size 1080 1776
I/jxcore-log(13283): 
,I/jxcore-log(13283): Screen Brightness 82
I/jxcore-log(13283): 
,E/jxcore-log(13283): Dummy Error Log.
E/jxcore-log(13283): 
,I/jxcore-log(13283): getBuffer is called!!!!
I/jxcore-log(13283): 
,I/jxcore-log(13283): ****TEST TOOK:  5065  ms ****
I/jxcore-log(13283): 
,I/jxcore-log(13283): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(13283): 


LGE-LG-D722: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(32255): Initializing JXcore engine
W/jxcore-log(32255): JXcore engine is ready
,W/jxcore-log(32255): Starting JXcore engine
,W/jxcore-log(32255): Platform android
W/jxcore-log(32255): 
W/jxcore-log(32255): Process ARCH arm
W/jxcore-log(32255): 
,I/jxcore-log(32255): JXcore Cordova bridge is ready!
I/jxcore-log(32255): 
W/jxcore-log(32255): JXcore engine is started
,E/jxcore-log(32255): >> LGE-LG-D722
E/jxcore-log(32255): 
,I/jxcore-log(32255): Total memory 906309632
I/jxcore-log(32255): 
,I/jxcore-log(32255): Free memory 15724544
I/jxcore-log(32255): 
,I/jxcore-log(32255): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32255): 
I/jxcore-log(32255): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32255): 
I/jxcore-log(32255): userPath [ 'www' ]
I/jxcore-log(32255): 
I/jxcore-log(32255): Size 720 1196
I/jxcore-log(32255): 
I/jxcore-log(32255): Screen Brightness 255
I/jxcore-log(32255): 
E/jxcore-log(32255): Dummy Error Log.
E/jxcore-log(32255): 
,I/jxcore-log(32255): getBuffer is called!!!!
I/jxcore-log(32255): 
,I/jxcore-log(32255): ****TEST TOOK:  5078  ms ****
I/jxcore-log(32255): 
I/jxcore-log(32255): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(32255): 


```

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
Device test finished on 320414cd475f91e3 
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
Android task is completed 
```

Logcat output:
```
motorola-XT1039: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(14318): Initializing JXcore engine
,W/jxcore-log(14318): JXcore engine is ready
,W/jxcore-log(14318): Starting JXcore engine
,W/jxcore-log(14318): Platform android
W/jxcore-log(14318): 
,W/jxcore-log(14318): Process ARCH arm
W/jxcore-log(14318): 
,I/jxcore-log(14318): JXcore Cordova bridge is ready!
I/jxcore-log(14318): 
,W/jxcore-log(14318): JXcore engine is started
,E/jxcore-log(14318): >> motorola-XT1039
E/jxcore-log(14318): 
,I/jxcore-log(14318): Total memory 893136896
I/jxcore-log(14318): 
I/jxcore-log(14318): Free memory 48185344
I/jxcore-log(14318): 
,I/jxcore-log(14318): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(14318): 
,I/jxcore-log(14318): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(14318): 
,I/jxcore-log(14318): userPath [ 'www' ]
I/jxcore-log(14318): 
,I/jxcore-log(14318): Size 720 1184
I/jxcore-log(14318): 
,I/jxcore-log(14318): Screen Brightness 210
I/jxcore-log(14318): 
E/jxcore-log(14318): Dummy Error Log.
E/jxcore-log(14318): 
,I/jxcore-log(14318): getBuffer is called!!!!
I/jxcore-log(14318): 
,I/jxcore-log(14318): ****TEST TOOK:  5046  ms ****
I/jxcore-log(14318): 
I/jxcore-log(14318): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(14318): 


LGE-LG-D855: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(19345): Initializing JXcore engine
W/jxcore-log(19345): JXcore engine is ready
W/jxcore-log(19345): Starting JXcore engine
W/jxcore-log(19345): Platform android
W/jxcore-log(19345): 
W/jxcore-log(19345): Process ARCH arm
W/jxcore-log(19345): 
,I/jxcore-log(19345): JXcore Cordova bridge is ready!
I/jxcore-log(19345): 
,W/jxcore-log(19345): JXcore engine is started
,E/jxcore-log(19345): >> LGE-LG-D855
E/jxcore-log(19345): 
,I/jxcore-log(19345): Total memory 2995761152
I/jxcore-log(19345): 
,I/jxcore-log(19345): Free memory 467025920
I/jxcore-log(19345): 
I/jxcore-log(19345): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19345): 
,I/jxcore-log(19345): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19345): 
,I/jxcore-log(19345): userPath [ 'www' ]
I/jxcore-log(19345): 
,I/jxcore-log(19345): Size 1440 2392
I/jxcore-log(19345): 
I/jxcore-log(19345): Screen Brightness 177
I/jxcore-log(19345): 
E/jxcore-log(19345): Dummy Error Log.
E/jxcore-log(19345): 
,I/jxcore-log(19345): getBuffer is called!!!!
I/jxcore-log(19345): 
,I/jxcore-log(19345): ****TEST TOOK:  5078  ms ****
I/jxcore-log(19345): 
I/jxcore-log(19345): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(19345): 


samsung-SM-G800F: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,I/jxcore-log( 9022): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 9022): 
,I/jxcore-log( 9022): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 9022): 
I/jxcore-log( 9022): printNetworkInfo
I/jxcore-log( 9022): 
I/jxcore-log( 9022): found interfaceName: lo
I/jxcore-log( 9022): 
,I/jxcore-log( 9022): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 9022): 
,I/jxcore-log( 9022): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 9022): 
,I/jxcore-log( 9022): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 9022): 
,I/jxcore-log( 9022): printNetworkInfo
I/jxcore-log( 9022): 
,I/jxcore-log( 9022): found interfaceName: lo
I/jxcore-log( 9022): 
,I/jxcore-log( 9022): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 9022): 
,I/jxcore-log( 9022): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 9022): 
,I/jxcore-log( 9022): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 9022): 
,I/jxcore-log( 9022): printNetworkInfo
I/jxcore-log( 9022): 
,I/jxcore-log( 9022): found interfaceName: lo
I/jxcore-log( 9022): 
,I/jxcore-log( 9022): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 9022): 
,I/jxcore-log( 9022): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 9022): 
,I/jxcore-log( 9022): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 9022): 
,I/jxcore-log( 9022): printNetworkInfo
I/jxcore-log( 9022): 
,I/jxcore-log( 9022): found interfaceName: lo
I/jxcore-log( 9022): 
,I/jxcore-log( 9022): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 9022): 
,W/jxcore-log( 7801): Initializing JXcore engine
,W/jxcore-log( 7801): JXcore engine is ready
,W/jxcore-log( 7801): Starting JXcore engine
,W/jxcore-log( 7801): Platform android
W/jxcore-log( 7801): 
,W/jxcore-log( 7801): Process ARCH arm
W/jxcore-log( 7801): 
,I/jxcore-log( 7801): JXcore Cordova bridge is ready!
I/jxcore-log( 7801): 
,W/jxcore-log( 7801): JXcore engine is started
,E/jxcore-log( 7801): >> samsung-SM-G800F
E/jxcore-log( 7801): 
,I/jxcore-log( 7801): Total memory 1319530496
I/jxcore-log( 7801): 
I/jxcore-log( 7801): Free memory 32280576
I/jxcore-log( 7801): 
I/jxcore-log( 7801): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7801): 
,I/jxcore-log( 7801): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7801): 
,I/jxcore-log( 7801): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 7801): 
,I/jxcore-log( 7801): Size 720 1280
I/jxcore-log( 7801): 
,I/jxcore-log( 7801): Screen Brightness 255
I/jxcore-log( 7801): 
,E/jxcore-log( 7801): Dummy Error Log.
E/jxcore-log( 7801): 
,I/jxcore-log( 7801): getBuffer is called!!!!
I/jxcore-log( 7801): 
,I/jxcore-log( 9022): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 9022): 
I/jxcore-log( 9022): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 9022): 
,I/jxcore-log( 9022): printNetworkInfo
I/jxcore-log( 9022): 
I/jxcore-log( 9022): found interfaceName: lo
I/jxcore-log( 9022): 
,I/jxcore-log( 9022): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 9022): 
,I/jxcore-log( 7801): ****TEST TOOK:  5150  ms ****
I/jxcore-log( 7801): 
,I/jxcore-log( 7801): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7801): 


```

####Node name: thali04
Console output:
```
Error: problem stopping Android apk(com.example.hello) to device 41006f95c8139173 error: device not found
 
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on 0be0c6c6 
Device test finished on f56ad48d 
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed 
```

Logcat output:
```
samsung-SM-G900F: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log( 2959): Initializing JXcore engine
W/jxcore-log( 2959): JXcore engine is ready
W/jxcore-log( 2959): Starting JXcore engine
W/jxcore-log( 2959): Platform android
W/jxcore-log( 2959): 
W/jxcore-log( 2959): Process ARCH arm
W/jxcore-log( 2959): 
I/jxcore-log( 2959): JXcore Cordova bridge is ready!
I/jxcore-log( 2959): 
W/jxcore-log( 2959): JXcore engine is started
E/jxcore-log( 2959): >> samsung-SM-G900F
E/jxcore-log( 2959): 
I/jxcore-log( 2959): Total memory 1787449344
I/jxcore-log( 2959): 
I/jxcore-log( 2959): Free memory 46456832
I/jxcore-log( 2959): 
I/jxcore-log( 2959): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2959): 
I/jxcore-log( 2959): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2959): 
I/jxcore-log( 2959): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 2959): 
I/jxcore-log( 2959): Size 1080 1920
I/jxcore-log( 2959): 
I/jxcore-log( 2959): Screen Brightness 255
I/jxcore-log( 2959): 
E/jxcore-log( 2959): Dummy Error Log.
E/jxcore-log( 2959): 
,I/jxcore-log( 2959): getBuffer is called!!!!
I/jxcore-log( 2959): 
,I/jxcore-log( 2959): ****TEST TOOK:  5256  ms ****
I/jxcore-log( 2959): 
,I/jxcore-log( 2959): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2959): 


motorola-XT1072: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(20305): Initializing JXcore engine
,W/jxcore-log(20305): JXcore engine is ready
,W/jxcore-log(20305): Starting JXcore engine
,W/jxcore-log(20305): Platform android
W/jxcore-log(20305): 
,W/jxcore-log(20305): Process ARCH arm
W/jxcore-log(20305): 
,I/jxcore-log(20305): JXcore Cordova bridge is ready!
I/jxcore-log(20305): 
,W/jxcore-log(20305): JXcore engine is started
,E/jxcore-log(20305): >> motorola-XT1072
E/jxcore-log(20305): 
,I/jxcore-log(20305): Total memory 916258816
I/jxcore-log(20305): 
I/jxcore-log(20305): Free memory 56451072
I/jxcore-log(20305): 
I/jxcore-log(20305): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20305): 
,I/jxcore-log(20305): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20305): 
,I/jxcore-log(20305): userPath [ 'www' ]
I/jxcore-log(20305): 
,I/jxcore-log(20305): Size 720 1184
I/jxcore-log(20305): 
,I/jxcore-log(20305): Screen Brightness 82
I/jxcore-log(20305): 
,E/jxcore-log(20305): Dummy Error Log.
E/jxcore-log(20305): 
,I/jxcore-log(20305): getBuffer is called!!!!
I/jxcore-log(20305): 
,I/jxcore-log(20305): ****TEST TOOK:  5260  ms ****
I/jxcore-log(20305): 
I/jxcore-log(20305): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(20305): 


samsung-SM-A500FU: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(25572): Initializing JXcore engine
W/jxcore-log(25572): JXcore engine is ready
W/jxcore-log(25572): Starting JXcore engine
W/jxcore-log(25572): Platform android
W/jxcore-log(25572): 
W/jxcore-log(25572): Process ARCH arm
W/jxcore-log(25572): 
I/jxcore-log(25572): JXcore Cordova bridge is ready!
I/jxcore-log(25572): 
W/jxcore-log(25572): JXcore engine is started
,E/jxcore-log(25572): >> samsung-SM-A500FU
E/jxcore-log(25572): 
,I/jxcore-log(25572): Total memory 1983787008
I/jxcore-log(25572): 
,I/jxcore-log(25572): Free memory 183324672
I/jxcore-log(25572): 
,I/jxcore-log(25572): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25572): 
I/jxcore-log(25572): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25572): 
,I/jxcore-log(25572): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(25572): 
,I/jxcore-log(25572): Size 720 1280
I/jxcore-log(25572): 
,I/jxcore-log(25572): Screen Brightness 255
I/jxcore-log(25572): 
,E/jxcore-log(25572): Dummy Error Log.
E/jxcore-log(25572): 
,I/jxcore-log(25572): getBuffer is called!!!!
I/jxcore-log(25572): 
,I/jxcore-log(25572): ****TEST TOOK:  5088  ms ****
I/jxcore-log(25572): 
,I/jxcore-log(25572): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(25572): 


samsung-SM-N910C: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(30162): Initializing JXcore engine
W/jxcore-log(30162): JXcore engine is ready
W/jxcore-log(30162): Starting JXcore engine
W/jxcore-log(30162): Platform android
W/jxcore-log(30162): 
W/jxcore-log(30162): Process ARCH arm
W/jxcore-log(30162): 
I/jxcore-log(30162): JXcore Cordova bridge is ready!
I/jxcore-log(30162): 
W/jxcore-log(30162): JXcore engine is started
E/jxcore-log(30162): >> samsung-SM-N910C
E/jxcore-log(30162): 
I/jxcore-log(30162): Total memory 2971066368
I/jxcore-log(30162): 
I/jxcore-log(30162): Free memory 230473728
I/jxcore-log(30162): 
I/jxcore-log(30162): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(30162): 
I/jxcore-log(30162): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(30162): 
I/jxcore-log(30162): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(30162): 
I/jxcore-log(30162): Size 1440 2560
I/jxcore-log(30162): 
I/jxcore-log(30162): Screen Brightness 134
I/jxcore-log(30162): 
E/jxcore-log(30162): Dummy Error Log.
E/jxcore-log(30162): 
,I/jxcore-log(30162): getBuffer is called!!!!
I/jxcore-log(30162): 
,I/jxcore-log(30162): ****TEST TOOK:  5087  ms ****
I/jxcore-log(30162): 
,I/jxcore-log(30162): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(30162): 


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
--------- beginning of main
--------- beginning of system
,W/jxcore-log(20687): Initializing JXcore engine
W/jxcore-log(20687): JXcore engine is ready
,W/jxcore-log(20687): Starting JXcore engine,
,W/jxcore-log(20687): Platform android,
W/jxcore-log(20687): 
W/jxcore-log(20687): Process ARCH arm
W/jxcore-log(20687): 
,I/jxcore-log(20687): JXcore Cordova bridge is ready!,
I/jxcore-log(20687): 
W/jxcore-log(20687): JXcore engine is started
,E/jxcore-log(20687): >> HTC-HTC One_M8,
E/jxcore-log(20687): 
,I/jxcore-log(20687): Total memory 1912020992
I/jxcore-log(20687): 
I/jxcore-log(20687): Free memory 450404352
I/jxcore-log(20687): 
I/jxcore-log(20687): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20687): 
I/jxcore-log(20687): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20687): 
,I/jxcore-log(20687): userPath [ 'www' ]
I/jxcore-log(20687): 
,I/jxcore-log(20687): Size 1080 1776,
I/jxcore-log(20687): 
,I/jxcore-log(20687): Screen Brightness 142
I/jxcore-log(20687): 
E/jxcore-log(20687): Dummy Error Log.
E/jxcore-log(20687): 
,I/jxcore-log(20687): getBuffer is called!!!!,
I/jxcore-log(20687): 
,I/jxcore-log(20687): ****TEST TOOK:  5089  ms ****,
I/jxcore-log(20687): 
I/jxcore-log(20687): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(20687): 


samsung-SM-N9005: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(26642): Initializing JXcore engine
,W/jxcore-log(26642): JXcore engine is ready
,W/jxcore-log(26642): Starting JXcore engine
,W/jxcore-log(26642): Platform android
W/jxcore-log(26642): 
W/jxcore-log(26642): Process ARCH arm
W/jxcore-log(26642): 
,I/jxcore-log(26642): JXcore Cordova bridge is ready!
I/jxcore-log(26642): 
W/jxcore-log(26642): JXcore engine is started
,E/jxcore-log(26642): >> samsung-SM-N9005
E/jxcore-log(26642): 
,I/jxcore-log(26642): Total memory 2971471872
I/jxcore-log(26642): 
I/jxcore-log(26642): Free memory 576200704
I/jxcore-log(26642): 
I/jxcore-log(26642): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(26642): 
,I/jxcore-log(26642): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(26642): 
,I/jxcore-log(26642): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(26642): 
,I/jxcore-log(26642): Size 1080 1920
I/jxcore-log(26642): 
,I/jxcore-log(26642): Screen Brightness 255
I/jxcore-log(26642): 
,E/jxcore-log(26642): Dummy Error Log.
E/jxcore-log(26642): 
,I/jxcore-log(26642): getBuffer is called!!!!
I/jxcore-log(26642): 
,I/jxcore-log(26642): ****TEST TOOK:  5092  ms ****
I/jxcore-log(26642): 
I/jxcore-log(26642): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(26642): 


motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(13002): Initializing JXcore engine
,W/jxcore-log(13002): JXcore engine is ready
,W/jxcore-log(13002): Starting JXcore engine
,W/jxcore-log(13002): Platform android
W/jxcore-log(13002): 
,W/jxcore-log(13002): Process ARCH arm,
W/jxcore-log(13002): 
,I/jxcore-log(13002): JXcore Cordova bridge is ready!
I/jxcore-log(13002): 
,W/jxcore-log(13002): JXcore engine is started,
,E/jxcore-log(13002): >> motorola-Nexus 6
E/jxcore-log(13002): 
,I/jxcore-log(13002): Total memory 3114405888
I/jxcore-log(13002): 
,I/jxcore-log(13002): Free memory 604315648
I/jxcore-log(13002): 
I/jxcore-log(13002): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13002): 
I/jxcore-log(13002): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13002): 
,I/jxcore-log(13002): userPath [ 'www' ]
I/jxcore-log(13002): 
,I/jxcore-log(13002): Size 1440 2392
I/jxcore-log(13002): 
,I/jxcore-log(13002): Screen Brightness 82
I/jxcore-log(13002): 
,E/jxcore-log(13002): Dummy Error Log.
E/jxcore-log(13002): 
,I/jxcore-log(13002): getBuffer is called!!!!
I/jxcore-log(13002): 
,I/jxcore-log(13002): ****TEST TOOK:  5054  ms ****
I/jxcore-log(13002): 
,I/jxcore-log(13002): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(13002): 


```

####Node name: thali06
Console output:
```
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
Device test finished on 7970f88c 
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
Android task is completed 
```

Logcat output:
```
HTC-HTC One M8s: 
--------- beginning of system,
--------- beginning of main
,W/jxcore-log(24241): Initializing JXcore engine
W/jxcore-log(24241): JXcore engine is ready
,W/jxcore-log(24241): Starting JXcore engine
,W/jxcore-log(24241): Platform android
W/jxcore-log(24241): 
W/jxcore-log(24241): Process ARCH arm
W/jxcore-log(24241): 
,I/jxcore-log(24241): JXcore Cordova bridge is ready!
I/jxcore-log(24241): 
W/jxcore-log(24241): JXcore engine is started
,E/jxcore-log(24241): >> HTC-HTC One M8s
E/jxcore-log(24241): 
,I/jxcore-log(24241): Total memory 1931808768
I/jxcore-log(24241): 
I/jxcore-log(24241): Free memory 312352768
I/jxcore-log(24241): 
I/jxcore-log(24241): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(24241): 
I/jxcore-log(24241): process.cwd /data/data/com.example.hello/files/www/jxcore
,I/jxcore-log(24241): 
,I/jxcore-log(24241): userPath [ 'www' ],
I/jxcore-log(24241): 
,I/jxcore-log(24241): Size 1080 1776,
I/jxcore-log(24241): 
,I/jxcore-log(24241): Screen Brightness 142,
I/jxcore-log(24241): 
E/jxcore-log(24241): Dummy Error Log.
E/jxcore-log(24241): 
,I/jxcore-log(24241): getBuffer is called!!!!
I/jxcore-log(24241): 
,I/jxcore-log(24241): ****TEST TOOK:  5169  ms ****
I/jxcore-log(24241): 
I/jxcore-log(24241): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(24241): 


samsung-SM-A300FU: 
--------- beginning of main,
--------- beginning of system
,W/jxcore-log(12742): Initializing JXcore engine
W/jxcore-log(12742): JXcore engine is ready
,W/jxcore-log(12742): Starting JXcore engine
,W/jxcore-log(12742): Platform android
W/jxcore-log(12742): 
W/jxcore-log(12742): Process ARCH arm
W/jxcore-log(12742): 
,I/jxcore-log(12742): JXcore Cordova bridge is ready!
I/jxcore-log(12742): 
,W/jxcore-log(12742): JXcore engine is started
,E/jxcore-log(12742): >> samsung-SM-A300FU
E/jxcore-log(12742): 
,I/jxcore-log(12742): Total memory 1451114496
I/jxcore-log(12742): 
I/jxcore-log(12742): Free memory 193748992
I/jxcore-log(12742): 
,I/jxcore-log(12742): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(12742): 
I/jxcore-log(12742): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(12742): 
,I/jxcore-log(12742): userPath [ 'www' ]
I/jxcore-log(12742): 
,I/jxcore-log(12742): Size 540 960
I/jxcore-log(12742): 
,I/jxcore-log(12742): Screen Brightness 160
I/jxcore-log(12742): 
,E/jxcore-log(12742): Dummy Error Log.
E/jxcore-log(12742): 
,I/jxcore-log(12742): getBuffer is called!!!!
I/jxcore-log(12742): 
,I/jxcore-log(12742): ****TEST TOOK:  5113  ms ****
I/jxcore-log(12742): 
,I/jxcore-log(12742): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(12742): 


LGE-LG-D802: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(15546): Initializing JXcore engine
W/jxcore-log(15546): JXcore engine is ready
W/jxcore-log(15546): Starting JXcore engine
W/jxcore-log(15546): Platform android
W/jxcore-log(15546): 
W/jxcore-log(15546): Process ARCH arm
W/jxcore-log(15546): 
I/jxcore-log(15546): JXcore Cordova bridge is ready!
I/jxcore-log(15546): 
W/jxcore-log(15546): JXcore engine is started
E/jxcore-log(15546): >> LGE-LG-D802
E/jxcore-log(15546): 
I/jxcore-log(15546): Total memory 1943035904
I/jxcore-log(15546): 
I/jxcore-log(15546): Free memory 171040768
I/jxcore-log(15546): 
I/jxcore-log(15546): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(15546): 
I/jxcore-log(15546): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(15546): 
I/jxcore-log(15546): userPath [ 'www' ]
I/jxcore-log(15546): 
I/jxcore-log(15546): Size 1080 1776
I/jxcore-log(15546): 
,I/jxcore-log(15546): Screen Brightness 255
I/jxcore-log(15546): 
,E/jxcore-log(15546): Dummy Error Log.
E/jxcore-log(15546): 
,I/jxcore-log(15546): getBuffer is called!!!!
I/jxcore-log(15546): 
,I/jxcore-log(15546): ****TEST TOOK:  5088  ms ****
I/jxcore-log(15546): 
,I/jxcore-log(15546): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(15546): 


```

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on c5afcdcb 
Device test finished on 4db5c8cc 
Android task is completed 
```

Logcat output:
```
samsung-SM-A500FU: 
--------- beginning of system,
--------- beginning of main
,W/jxcore-log(14239): Initializing JXcore engine
W/jxcore-log(14239): JXcore engine is ready
,W/jxcore-log(14239): Starting JXcore engine
,W/jxcore-log(14239): Platform android,
W/jxcore-log(14239): 
W/jxcore-log(14239): Process ARCH arm
W/jxcore-log(14239): 
,I/jxcore-log(14239): JXcore Cordova bridge is ready!,
I/jxcore-log(14239): 
W/jxcore-log(14239): JXcore engine is started
,E/jxcore-log(14239): >> samsung-SM-A500FU
E/jxcore-log(14239): 
,I/jxcore-log(14239): Total memory 1983787008
I/jxcore-log(14239): 
,I/jxcore-log(14239): Free memory 385519616
I/jxcore-log(14239): 
I/jxcore-log(14239): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(14239): 
I/jxcore-log(14239): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(14239): 
,I/jxcore-log(14239): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(14239): 
,I/jxcore-log(14239): Size 720 1280
I/jxcore-log(14239): 
,I/jxcore-log(14239): Screen Brightness 255
I/jxcore-log(14239): 
,E/jxcore-log(14239): Dummy Error Log.
E/jxcore-log(14239): 
,I/jxcore-log(14239): getBuffer is called!!!!
I/jxcore-log(14239): 
,I/jxcore-log(14239): ****TEST TOOK:  5079  ms ****
I/jxcore-log(14239): 
,I/jxcore-log(14239): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(14239): 


samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(21196): Initializing JXcore engine
W/jxcore-log(21196): JXcore engine is ready
W/jxcore-log(21196): Starting JXcore engine
W/jxcore-log(21196): Platform android
W/jxcore-log(21196): 
W/jxcore-log(21196): Process ARCH arm
W/jxcore-log(21196): 
I/jxcore-log(21196): JXcore Cordova bridge is ready!
I/jxcore-log(21196): 
W/jxcore-log(21196): JXcore engine is started
E/jxcore-log(21196): >> samsung-SM-G900F
E/jxcore-log(21196): 
I/jxcore-log(21196): Total memory 1787449344
I/jxcore-log(21196): 
I/jxcore-log(21196): Free memory 47824896
I/jxcore-log(21196): 
I/jxcore-log(21196): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21196): 
I/jxcore-log(21196): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21196): 
I/jxcore-log(21196): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(21196): 
I/jxcore-log(21196): Size 1080 1920
I/jxcore-log(21196): 
I/jxcore-log(21196): Screen Brightness 134
I/jxcore-log(21196): 
E/jxcore-log(21196): Dummy Error Log.
E/jxcore-log(21196): 
,I/jxcore-log(21196): getBuffer is called!!!!
I/jxcore-log(21196): 
,I/jxcore-log(21196): ****TEST TOOK:  5237  ms ****
I/jxcore-log(21196): 
I/jxcore-log(21196): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(21196): 


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
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(10972): Initializing JXcore engine
W/jxcore-log(10972): JXcore engine is ready
W/jxcore-log(10972): Starting JXcore engine
W/jxcore-log(10972): Platform android
W/jxcore-log(10972): 
W/jxcore-log(10972): Process ARCH arm
W/jxcore-log(10972): 
I/jxcore-log(10972): JXcore Cordova bridge is ready!
I/jxcore-log(10972): 
W/jxcore-log(10972): JXcore engine is started
E/jxcore-log(10972): >> samsung-SM-A300FU
E/jxcore-log(10972): 
I/jxcore-log(10972): Total memory 1451114496
I/jxcore-log(10972): 
I/jxcore-log(10972): Free memory 214474752
I/jxcore-log(10972): 
I/jxcore-log(10972): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10972): 
I/jxcore-log(10972): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10972): 
I/jxcore-log(10972): userPath [ 'www' ]
I/jxcore-log(10972): 
I/jxcore-log(10972): Size 540 960
I/jxcore-log(10972): 
I/jxcore-log(10972): Screen Brightness 255
I/jxcore-log(10972): 
E/jxcore-log(10972): Dummy Error Log.
E/jxcore-log(10972): 
,I/jxcore-log(10972): getBuffer is called!!!!
I/jxcore-log(10972): 
,I/jxcore-log(10972): ****TEST TOOK:  5073  ms ****
I/jxcore-log(10972): 
,I/jxcore-log(10972): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10972): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log( 6561): Initializing JXcore engine
,W/jxcore-log( 6561): JXcore engine is ready
,W/jxcore-log( 6561): Starting JXcore engine
,W/jxcore-log( 6561): Platform android
W/jxcore-log( 6561): 
,W/jxcore-log( 6561): Process ARCH arm
W/jxcore-log( 6561): 
,I/jxcore-log( 6561): JXcore Cordova bridge is ready!
I/jxcore-log( 6561): 
,W/jxcore-log( 6561): JXcore engine is started
,E/jxcore-log( 6561): >> HTC-HTC Desire 820
E/jxcore-log( 6561): 
,I/jxcore-log( 6561): Total memory 1964650496
I/jxcore-log( 6561): 
I/jxcore-log( 6561): Free memory 198615040
I/jxcore-log( 6561): 
I/jxcore-log( 6561): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6561): 
,I/jxcore-log( 6561): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6561): 
,I/jxcore-log( 6561): userPath [ 'www' ]
I/jxcore-log( 6561): 
,I/jxcore-log( 6561): Size 720 1184
I/jxcore-log( 6561): 
,I/jxcore-log( 6561): Screen Brightness 10
I/jxcore-log( 6561): 
,E/jxcore-log( 6561): Dummy Error Log.
E/jxcore-log( 6561): 
,I/jxcore-log( 6561): getBuffer is called!!!!
I/jxcore-log( 6561): 
,I/jxcore-log( 6561): ****TEST TOOK:  5181  ms ****
I/jxcore-log( 6561): 
,I/jxcore-log( 6561): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6561): 


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
,W/jxcore-log(12108): Initializing JXcore engine
,W/jxcore-log(12108): JXcore engine is ready
,W/jxcore-log(12108): Starting JXcore engine
,W/jxcore-log(12108): Platform android
W/jxcore-log(12108): 
,W/jxcore-log(12108): Process ARCH arm
W/jxcore-log(12108): 
,I/jxcore-log(12108): JXcore Cordova bridge is ready!
I/jxcore-log(12108): 
,W/jxcore-log(12108): JXcore engine is started
,E/jxcore-log(12108): >> LGE-Nexus 5
E/jxcore-log(12108): 
,I/jxcore-log(12108): Total memory 1945137152
I/jxcore-log(12108): 
I/jxcore-log(12108): Free memory 523440128
I/jxcore-log(12108): 
I/jxcore-log(12108): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(12108): 
,I/jxcore-log(12108): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(12108): 
,I/jxcore-log(12108): userPath [ 'www' ]
I/jxcore-log(12108): 
,I/jxcore-log(12108): Size 1080 1776
I/jxcore-log(12108): 
,I/jxcore-log(12108): Screen Brightness 82
I/jxcore-log(12108): 
,E/jxcore-log(12108): Dummy Error Log.
E/jxcore-log(12108): 
,I/jxcore-log(12108): getBuffer is called!!!!
I/jxcore-log(12108): 
,I/jxcore-log(12108): ****TEST TOOK:  5039  ms ****
I/jxcore-log(12108): 
I/jxcore-log(12108): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(12108): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log(32015): Initializing JXcore engine
,W/jxcore-log(32015): JXcore engine is ready
,W/jxcore-log(32015): Starting JXcore engine
,W/jxcore-log(32015): Platform android
W/jxcore-log(32015): 
,W/jxcore-log(32015): Process ARCH arm
W/jxcore-log(32015): 
,I/jxcore-log(32015): JXcore Cordova bridge is ready!
I/jxcore-log(32015): 
,W/jxcore-log(32015): JXcore engine is started
,E/jxcore-log(32015): >> HTC-HTC Desire 820
E/jxcore-log(32015): 
,I/jxcore-log(32015): Total memory 1964650496
I/jxcore-log(32015): 
I/jxcore-log(32015): Free memory 348913664
I/jxcore-log(32015): 
I/jxcore-log(32015): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32015): 
,I/jxcore-log(32015): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32015): 
,I/jxcore-log(32015): userPath [ 'www' ]
I/jxcore-log(32015): 
,I/jxcore-log(32015): Size 720 1184
I/jxcore-log(32015): 
,I/jxcore-log(32015): Screen Brightness 142
I/jxcore-log(32015): 
,E/jxcore-log(32015): Dummy Error Log.
E/jxcore-log(32015): 
,I/jxcore-log(32015): getBuffer is called!!!!
I/jxcore-log(32015): 
,I/jxcore-log(32015): ****TEST TOOK:  5055  ms ****
I/jxcore-log(32015): 
,I/jxcore-log(32015): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(32015): 


```


