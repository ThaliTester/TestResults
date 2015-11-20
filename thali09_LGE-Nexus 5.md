#### Test 5133502893bec48_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
D/dalvikvm( 1219): GC_CONCURRENT freed 450K, 3% free 18681K/19248K, paused 2ms+1ms, total 14ms
I/Icing.InternalIcingCorporaProvider( 1219): UpdateCorporaTask done [took 53 ms] updated apps [took 53 ms] 
,D/AndroidRuntime( 2977): 
D/AndroidRuntime( 2977): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2977): CheckJNI is OFF
D/dalvikvm( 2977): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2977): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2977): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2977): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2977): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2977): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 2977): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager(  775): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2977
D/PermissionCache(  185): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (2021 us)
D/AndroidRuntime( 2977): Shutting down VM
D/dalvikvm( 2977): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+0ms, total 1ms
I/ActivityManager(  775): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2999 uid=10108 gids={50108, 3003, 3001, 3002, 1028, 1015}
D/dalvikvm(  187): GC_EXPLICIT freed 42K, 1% free 16697K/16772K, paused 1ms+2ms, total 14ms
D/dalvikvm(  187): GC_EXPLICIT freed <1K, 1% free 16697K/16772K, paused 0ms+1ms, total 12ms
D/dalvikvm(  187): GC_EXPLICIT freed <1K, 1% free 16697K/16772K, paused 1ms+2ms, total 14ms
I/SearchController( 1219): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1219): mic_close
V/WebViewChromiumFactoryProvider( 2999): Binding Chromium to main looper Looper (main, tid 1) {425a46c8}
I/LibraryLoader( 2999): Expected native library version number "",actual native library version number ""
I/chromium( 2999): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2999): Initializing chromium process, renderers=0
D/BluetoothManagerService(  775): Message: 20
D/BluetoothManagerService(  775): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@441cfa68:true
I/MicroHotwordRecognitionRunner( 1219): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1219): Stopping hotword detection.
I/Adreno-EGL( 2999): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
W/chromium( 2999): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 2999): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2999): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2999): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2999): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2999): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2999): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 2999): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2999): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2999): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2999): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2999): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2999): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2999): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2999): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2999): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2999): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2999): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2999): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2999): CordovaWebView is running on device made by: LGE
,D/OpenGLRenderer( 2999): Enabling debug mode 0
,W/AwContents( 2999): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  775): Displayed com.test.thalitest/.MainActivity: +337ms
,I/Icing   ( 1335): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,D/dalvikvm( 1335): GC_CONCURRENT freed 642K, 4% free 18927K/19604K, paused 3ms+3ms, total 30ms
,I/dalvikvm(  775): Jit: resizing JitTable from 8192 to 16384
,I/Icing   ( 1335): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
I/Icing   ( 1335): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
I/Icing   ( 1335): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
I/ActivityManager(  775): Killing 1899:com.google.android.gm/u0a41 (adj 15): empty #17
D/dalvikvm( 2999): GC_CONCURRENT freed 228K, 2% free 16861K/17120K, paused 3ms+8ms, total 20ms
D/JsMessageQueue( 2999): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 2999): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x425a89e0
D/dalvikvm( 2999): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x425a89e0
D/jxcore_app_log( 2999): JniHelper::setJavaVM(0x41488f00), pthread_self() = 1982047888
D/JX-Cordova( 2999): jxcore cordova android initializing
I/dalvikvm( 2999): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 2999): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 2999): VFY: replacing opcode 0x6e at 0x0045
D/dalvikvm( 2999): GC_CONCURRENT freed 238K, 2% free 17134K/17404K, paused 2ms+1ms, total 14ms
D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 5ms
D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 4ms
D/dalvikvm( 2999): GC_CONCURRENT freed 160K, 2% free 17479K/17680K, paused 0ms+1ms, total 9ms
D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 3ms
D/dalvikvm( 2999): GC_CONCURRENT freed 157K, 2% free 17823K/18024K, paused 1ms+2ms, total 16ms
D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 10ms
D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 10ms
D/dalvikvm( 2999): GC_CONCURRENT freed 154K, 2% free 18167K/18368K, paused 2ms+2ms, total 21ms
D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 14ms
D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 14ms
D/dalvikvm( 2999): GC_CONCURRENT freed 159K, 2% free 18502K/18712K, paused 1ms+2ms, total 23ms
D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 18ms
D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/dalvikvm( 2999): GC_CONCURRENT freed 177K, 2% free 18909K/19140K, paused 2ms+1ms, total 15ms
D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 9ms
D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 6ms
D/dalvikvm( 2999): GC_CONCURRENT freed 217K, 2% free 19405K/19680K, paused 1ms+1ms, total 15ms
D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 7ms
D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/dalvikvm( 2999): GC_CONCURRENT freed 276K, 2% free 20004K/20344K, paused 2ms+1ms, total 21ms
D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 9ms
D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 14ms
D/dalvikvm( 2999): GC_CONCURRENT freed 322K, 2% free 20747K/21140K, paused 1ms+3ms, total 34ms
D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 30ms
D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 24ms
D/dalvikvm( 2999): GC_CONCURRENT freed 395K, 3% free 21659K/22132K, paused 1ms+2ms, total 23ms
D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 18ms
D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/dalvikvm( 2999): GC_CONCURRENT freed 1136K, 6% free 22146K/23348K, paused 1ms+2ms, total 25ms
D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 13ms
D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2999): GC_FOR_ALLOC freed 751K, 7% free 22228K/23672K, paused 18ms, total 18ms
,I/dalvikvm-heap( 2999): Grow heap (frag case) to 22.208MB for 496096-byte allocation
,D/dalvikvm( 2999): GC_FOR_ALLOC freed <1K, 6% free 22713K/24160K, paused 20ms, total 20ms
,D/dalvikvm( 2999): GC_FOR_ALLOC freed 890K, 8% free 22398K/24160K, paused 20ms, total 20ms
,I/dalvikvm-heap( 2999): Grow heap (frag case) to 22.611MB for 744140-byte allocation
,D/dalvikvm( 2999): GC_FOR_ALLOC freed 484K, 10% free 22640K/24888K, paused 20ms, total 20ms
,D/dalvikvm( 2999): GC_FOR_ALLOC freed 821K, 9% free 22658K/24888K, paused 21ms, total 21ms
,I/dalvikvm-heap( 2999): Grow heap (frag case) to 23.220MB for 1116206-byte allocation
,D/dalvikvm( 2999): GC_FOR_ALLOC freed 731K, 12% free 23017K/25980K, paused 20ms, total 20ms
,D/dalvikvm( 2999): GC_FOR_ALLOC freed 1273K, 12% free 23077K/25980K, paused 21ms, total 21ms
,I/dalvikvm-heap( 2999): Grow heap (frag case) to 24.161MB for 1674304-byte allocation
,D/dalvikvm( 2999): GC_FOR_ALLOC freed 1090K, 15% free 23621K/27616K, paused 19ms, total 19ms
,D/dalvikvm( 2999): GC_FOR_ALLOC freed 2033K, 15% free 23721K/27616K, paused 24ms, total 24ms
,I/dalvikvm-heap( 2999): Grow heap (frag case) to 25.588MB for 2511452-byte allocation
,D/dalvikvm( 2999): GC_CONCURRENT freed 68K, 14% free 26105K/30072K, paused 2ms+1ms, total 21ms
,D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 2999): GC_CONCURRENT freed 4599K, 19% free 24645K/30072K, paused 1ms+6ms, total 48ms
,D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 41ms
,D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 35ms
,D/dalvikvm( 2999): GC_FOR_ALLOC freed 196K, 19% free 24517K/30072K, paused 20ms, total 20ms
,I/dalvikvm-heap( 2999): Grow heap (frag case) to 27.563MB for 3767174-byte allocation
,D/dalvikvm( 2999): GC_FOR_ALLOC freed 2498K, 24% free 25697K/33752K, paused 23ms, total 23ms
,D/dalvikvm( 2999): GC_CONCURRENT freed 277K, 25% free 25562K/33752K, paused 2ms+1ms, total 33ms
,D/dalvikvm( 2999): GC_FOR_ALLOC freed 402K, 25% free 25588K/33752K, paused 19ms, total 19ms
,W/jxcore-log( 2999): Initializing JXcore engine
,W/jxcore-log( 2999): JXcore engine is ready
,D/dalvikvm( 2999): GC_CONCURRENT freed 5250K, 32% free 23287K/33752K, paused 2ms+1ms, total 22ms
D/dalvikvm( 2999): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/jxcore-log( 2999): Starting JXcore engine
,W/jxcore-log( 2999): Platform android
W/jxcore-log( 2999): 
,W/jxcore-log( 2999): Process ARCH arm
W/jxcore-log( 2999): 
,I/jxcore-log( 2999): JXcore Cordova bridge is ready!
I/jxcore-log( 2999): 
,W/jxcore-log( 2999): JXcore engine is started
,I/Choreographer( 2999): Skipped 155 frames!  The application may be doing too much work on its main thread.
,I/chromium( 2999): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2999): Turning radios to true
I/jxcore-log( 2999): 
,D/BluetoothAdapter( 2999): enable(): BT is already enabled..!
,I/jxcore-log( 2999): toggleBluetooth - 
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): toggleWiFi
I/jxcore-log( 2999): 
D/WifiService(  775): setWifiEnabled: true pid=2999, uid=10108
,I/ActivityManager(  775): Killing 1812:com.google.android.calendar/u0a28 (adj 15): empty #17
,D/BluetoothManagerService(  775): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 2999): Got Device Bluetooth address: 34:FC:EF:11:B1:66
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): my name is : LGE-Nexus 5_PT9685
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): attempting to connect to test coordinator
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): check test folder
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found test : ./testFindPeers.js
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found test : ./testReConnect.js
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found test : ./testSendData.js
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Test app app.js loaded
I/jxcore-log( 2999): 
,I/Choreographer( 2999): Skipped 113 frames!  The application may be doing too much work on its main thread.
,I/chromium( 2999): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): BLE advertisement not supported: Build version is 19
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/dalvikvm( 2471): GC_CONCURRENT freed 670K, 5% free 19967K/20812K, paused 3ms+5ms, total 45ms
,D/dalvikvm( 1219): GC_CONCURRENT freed 1373K, 8% free 17970K/19376K, paused 2ms+2ms, total 15ms
,D/dalvikvm( 1219): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/dalvikvm( 1219): WAIT_FOR_CONCURRENT_GC blocked 9ms
,V/GLSActivity( 1100): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1100): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2471): Failed write_ctrl(u 52) res=-1 errno=22
,I/qtaguid ( 2471): Untagging socket 52 failed errno=-22
,W/NetworkManagementSocketTagger( 2471): untagSocket(52) failed with errno -22
,D/Finsky  ( 2471): [1] 5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/dalvikvm( 1100): GC_CONCURRENT freed 387K, 3% free 18380K/18876K, paused 3ms+1ms, total 34ms
,I/VacuumService( 1100): Vacuum at: now=1448013093063 tag=VacuumService
,D/UdcCache:FPQuery( 1335): Bootstrapping UDC settings cache for all accounts
,D/dalvikvm( 1100): GC_CONCURRENT freed 588K, 4% free 18292K/18984K, paused 2ms+1ms, total 16ms
,V/GLSActivity( 1100): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1100): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1335): GC_CONCURRENT freed 288K, 2% free 19331K/19656K, paused 2ms+2ms, total 18ms
,D/dalvikvm(  775): GC_EXPLICIT freed 23220K, 53% free 26751K/56340K, paused 2ms+6ms, total 107ms
,D/GetConfigurationSnapshotOperation( 1100): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1100): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1100): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1100): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 1100): GC_FOR_ALLOC freed 340K, 4% free 18364K/18984K, paused 58ms, total 59ms
,I/dalvikvm-heap( 1100): Grow heap (frag case) to 18.101MB for 79892-byte allocation
,D/dalvikvm( 1100): GC_FOR_ALLOC freed 39K, 4% free 18402K/19064K, paused 14ms, total 15ms
,D/dalvikvm( 1100): GC_CONCURRENT freed 461K, 4% free 18446K/19064K, paused 3ms+4ms, total 27ms
,D/GetCommittedConfigurationOperation( 1100): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 1100): GC_CONCURRENT freed 396K, 3% free 18585K/19084K, paused 2ms+2ms, total 16ms
,D/dalvikvm( 1100): GC_CONCURRENT freed 499K, 4% free 18645K/19240K, paused 3ms+3ms, total 18ms
,D/dalvikvm( 1100): GC_CONCURRENT freed 567K, 4% free 18660K/19324K, paused 2ms+4ms, total 21ms
,D/GetCommittedConfigurationOperation( 1100): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1100):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1100): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1100): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 1100): GC_CONCURRENT freed 708K, 5% free 18581K/19408K, paused 2ms+4ms, total 25ms
,D/GetCommittedConfigurationOperation( 1100): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1100): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1100): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 1100): GC_FOR_ALLOC freed 563K, 5% free 18477K/19408K, paused 34ms, total 34ms
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/rmt_storage(  181): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb87bf160
I/rmt_storage(  181): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  181): wakelock acquired: 1, error no: 2
,I/rmt_storage(  181): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1199836640)
,I/rmt_storage(  181): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  181): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  181): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1199836640) wakelock released: 1, error no: 0
I/rmt_storage(  181): 
,I/rmt_storage(  181): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb87bf160
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/PowerManagerService(  775): Going to sleep due to screen timeout...
,I/Adreno-EGL(  775): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/SurfaceFlinger(  185): Screen released, type=0 flinger=0xb7b7b450
,D/qdhwcomposer(  185): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  185): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  775): Excessive delay in blankDisplay() while turning screen off: 287ms
,V/KeyguardServiceDelegate(  775): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@42c02ca0)
,V/KeyguardServiceDelegate(  775): **** SHOWN CALLED ****
I/WindowManager(  775): No lock screen! windowToken=null
,D/NfcService( 1048): NFC-C OFF
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
,I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Coordinator is now connected to the server!
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
I/jxcore-log( 2999): found interfaceName: wlan0
I/jxcore-log( 2999): 
I/jxcore-log( 2999): -iface: IPv4 is internal : false, has ip: 192.168.1.146
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): DBG, CoordinatorConnector command called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":20,"addressList":[{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"90:E7:C4:F6:69:77","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"
,I/jxcore-log( 2999): Start now : testSendData.js
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): stop tests now !
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): testSendData created {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 20
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): check server
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): serverPort is 59407
I/jxcore-log( 2999): 
,D/BluetoothManagerService(  775): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2999): Stoping All
I/        ( 2999): Stopping services
I/        ( 2999): Stop Bluetooth
D/BluetoothManagerService(  775): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2999): Start-My BT: 34:FC:EF:11:B1:66
,D/BluetoothManagerService(  775): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2999):  mInstanceString : {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT9685"}
,I/        ( 2999): All stuff available and enabled
I/        ( 2999): Stoping All
I/        ( 2999): Stopping services
I/        ( 2999): Stop Bluetooth
I/        ( 2999): Starting All
I/        ( 2999): Stopping services
I/        ( 2999): Starting services address: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT9685"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@4259c018
I/        ( 2999): Stopping services
,I/        ( 2999): Starting services address: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT9685"}
,I/        ( 2999): Add local service :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT9685"}, length : 77
,I/        ( 2999): peerDiscoveryTimer timeout value:8318
,I/        ( 2999): Stop Bluetooth
I/        ( 2999): StartBluetooth listener
I/        ( 2999): StartBluetooth listener
,D/BluetoothManagerService(  775): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 2999): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1597): SOCK FLAG = 0 ***********************
,I/jxcore-log( 2999): StartBroadcasting started ok
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): do fake peer & start
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2999): 
I/jxcore-log( 2999): SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server  is bound to : undefined
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 2999): We already were running, thus doing nothing
I/        ( 2999): Added local service
I/        ( 2999): Cleared service requests
I/        ( 2999): Stopped peer discovery
,I/        ( 2999): Started peer discovery
,I/        ( 2999): Discovery state changed to Started.
,I/BTListenerThread( 2999): starting to listen
,I/BTListenerThread( 2999): waiting to accept incoming Connection
,I/wpa_supplicant(  934): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
I/wpa_supplicant(  934): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  934): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/wpa_supplicant(  934): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2999): Found 3 peers.
,I/SS      ( 2999): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 2999): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 2999): Peer(3): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 2999): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2999): Added service request
,I/wpa_supplicant(  934): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant(  934): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2999): Started service discovery
,I/wpa_supplicant(  934): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  934): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/wpa_supplicant(  934): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/        ( 2999): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7222","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 2999): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7222","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7222, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 2999): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7222, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 2999): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9998","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 2999): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9998","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT9998, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2999): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT9998, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 2999): SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: Connect (retry count 0) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: do connect now
I/jxcore-log( 2999): 
,I/        ( 2999): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/        ( 2999): Connecting to null, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 2999): Starting to connect
,W/BluetoothAdapter( 2999): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1597): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 2999): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[342]}
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75199428 rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 1597): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 1597): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,I/BluetoothBondStateMachine( 1597): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 1597): Entering PendingCommandState State
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75199428 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btif ( 1597): services_to_search = 3fffffff
,E/bt-btif ( 1597): ****************search UUID = 1200***********
,D/BluetoothManagerService(  775): Message: 20
,D/BluetoothManagerService(  775): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42b01720:true
,I/BluetoothConnectionReceiver( 1219): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1219): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,W/bt-btif ( 1597): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2999): Starting to Handshake
W/bt-btif ( 1597): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 1597): bta_dm_pm_ssr:2, lat:1200
I/BTHandshakeSocketThread( 2999): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2999): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2999): BTHandshakeSocketThread started
,I/BTConnectToThread( 2999): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 2999): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT4990"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2999): HandshakeOk : motorola-XT1039_PT4990
I/HS      ( 2999): Hand Shake finished outgoing for : motorola-XT1039_PT4990
,I/BTHandshakeSocketThread( 2999): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 2999): Starting the connected thread incoming : false, motorola-XT1039_PT4990
I/BtToSocketBase( 2999): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2999): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 2999): mHTTPPort  set to : 59045
I/BtConnectorHelper( 2999): Request socket is using : 59045
,I/BtToRequestSocket( 2999): Now accepting connections
,I/BtConnectorHelper( 2999): Calling ConnectionStatusUpdate with port :59045
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT connected to 59045, error: null
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2999): 
,I/BtToRequestSocket( 2999): incoming data from: /127.0.0.1, port: 59045
,I/BtToRequestSocket( 2999): Set local streams
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2999): 
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BtToRequestSocket( 2999): rin ended ---------------------------;
,I/jxcore-log( 2999): SendDataConnector.js: resetDataTimeout called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2999): 
,I/BluetoothConnectionReceiver( 1219): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1219): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,I/jxcore-log( 2999): SendDataConnector.js: resetDataTimeout called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2999): 
,D/dalvikvm(  996): GC_CONCURRENT freed 348K, 3% free 17963K/18460K, paused 2ms+33ms, total 52ms
,I/jxcore-log( 2999): SendDataConnector.js: resetDataTimeout called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: resetDataTimeout called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2999): 
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75199428 rs_disc_pending=1
W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,I/        ( 2999): Cleared service requests
,I/        ( 2999): Started peer discovery
,I/jxcore-log( 2999): SendDataConnector.js: resetDataTimeout called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: resetDataTimeout called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: resetDataTimeout called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: resetDataTimeout called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: resetDataTimeout called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: resetDataTimeout called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: resetDataTimeout called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: got all data for this round
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2999): 
,I/BtConnectorHelper( 2999): Disconnect outgoing peer: F4:F1:E1:5C:3B:E2
,I/BtToSocketBase( 2999): Stop ReceivingThread
I/BtToSocketBase( 2999): Stop SendingThread
,I/BtToSocketBase( 2999): Close local in
,I/BtToSocketBase( 2999): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 2999): Close LocalOutputStream
I/BtToSocketBase( 2999): Close localHostSocket
I/BtToSocketBase( 2999): Close bt in
I/BtToSocketBase( 2999): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2999): Close bt out
,I/BtToSocketBase( 2999): Close bt socket
,I/BtToRequestSocket( 2999): Close server socket
,I/jxcore-log( 2999): SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): ---- round done--------
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): do fake peer & start
I/jxcore-log( 2999): 
I/jxcore-log( 2999): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 2999): 
I/jxcore-log( 2999): SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback round[0] time: 13072 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT is closed
I/jxcore-log( 2999): 
,I/wpa_supplicant(  934): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  934): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  934): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2999): Found 10 peers.
,I/SS      ( 2999): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2999): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 2999): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2999): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2999): Peer(5): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 2999): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2999): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 2999): Peer(8): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 2999): Peer(9): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 2999): Peer(10): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2999): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2999): Added service request
,W/bt-btif ( 1597): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,I/        ( 2999): Started service discovery
,W/bt-sdp  ( 1597): process_service_search_attr_rsp
,E/bt-btif ( 1597): services_to_search = 3ffffffe
,E/bt-btif ( 1597): ****************search UUID = 0100***********
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 1597): process_service_search_attr_rsp
,E/bt-btif ( 1597): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1597): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1597): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1597): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1597): Index: 4 uuid:0000112f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1597): Index: 5 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1597): Index: 6 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1597): Index: 7 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1597): Index: 8 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 1597): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 1597): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 1597): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,I/BluetoothBondStateMachine( 1597): StableState(): Entering Off State
,I/wpa_supplicant(  934): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  934): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1219): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1219): Bluetooth Device Name: XT1039
,D/dalvikvm( 1219): GC_CONCURRENT freed 508K, 8% free 17974K/19376K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 1219): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,I/        ( 2999): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT2640"}, typeCordovap2p._tcp.local.:
,I/        ( 2999): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT2640"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT2640, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 2999): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT2640, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 2999): SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: Connect (retry count 0) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: do connect now
I/jxcore-log( 2999): 
,I/        ( 2999): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 2999): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 2999): Starting to connect
,W/BluetoothAdapter( 2999): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1597): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 2999): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[343]}
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 1597): process_service_search_attr_rsp
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75199428 rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1597): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2999): Starting to Handshake
W/bt-btif ( 1597): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 1597): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 2999): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2999): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2999): BTHandshakeSocketThread started
,I/BTConnectToThread( 2999): got MESSAGE_READ 80 bytes.
,I/BTConnectToThread( 2999): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT8157","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2999): HandshakeOk : HUAWEI-ALE-L21_PT8157
,I/HS      ( 2999): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT8157
,I/BtConnectorHelper( 2999): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT8157
,I/BtToSocketBase( 2999): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2999): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2999): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2999): mHTTPPort  set to : 34065
,I/BtConnectorHelper( 2999): Request socket is using : 34065
,I/BtToRequestSocket( 2999): Now accepting connections
,I/BtConnectorHelper( 2999): Calling ConnectionStatusUpdate with port :34065
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT connected to 34065, error: null
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2999): 
,I/BtToRequestSocket( 2999): incoming data from: /127.0.0.1, port: 34065
,I/BtToRequestSocket( 2999): Set local streams
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2999): 
,W/bt-btif ( 1597): new conn_srvc id:26, app_id:255
,W/bt-btif ( 1597): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 1597): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 1597): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2999): we got incoming connection
,I/BTHandshakeSocketThread( 2999): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2999): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2999): BTHandshakeSocketThread started
,I/BtToRequestSocket( 2999): rin ended ---------------------------;
,I/jxcore-log( 2999): SendDataConnector.js: resetDataTimeout called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2999): 
,I/BTListenerThread( 2999): got MESSAGE_READ 80 bytes.
,I/BTListenerThread( 2999): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT8157","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 2999): MESSAGE_WRITE 77 bytes.
,I/HS      ( 2999): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT8157
,I/BTHandshakeSocketThread( 2999): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 2999): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT8157
I/BtToSocketBase( 2999): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2999): Creating BTConnectedThread
,I/BtConnectorHelper( 2999): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2999): --DoOneRunRound started
,I/BtToRequestSocket( 2999): LocalHost address: localhost/127.0.0.1, port: 59407
,I/jxcore-log( 2999): TCP/IP server connected
I/jxcore-log( 2999): 
,I/BtToRequestSocket( 2999): --DoOneRunRound ended
,I/jxcore-log( 2999): SendDataConnector.js: resetDataTimeout called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: resetDataTimeout called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: resetDataTimeout called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: resetDataTimeout called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: resetDataTimeout called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: resetDataTimeout called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: resetDataTimeout called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: resetDataTimeout called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 33660 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 35640 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 37620 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 39600 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 41580 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 43560 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 45540 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 47520 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 49500 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 51480 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: resetDataTimeout called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 53460 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 55440 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 57420 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 59400 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 61380 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: resetDataTimeout called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: got all data for this round
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2999): 
,I/BtConnectorHelper( 2999): Disconnect outgoing peer: 58:2A:F7:ED:96:BE
I/BtToSocketBase( 2999): Stop ReceivingThread
,I/BtToSocketBase( 2999): Stop SendingThread
,I/BtToSocketBase( 2999): Close local in
,I/BtToSocketBase( 2999): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2999): Close LocalOutputStream
I/BtToSocketBase( 2999): Close localHostSocket
,I/BtToSocketBase( 2999): Close bt in
,I/BtToSocketBase( 2999): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2999): Close bt out
I/BtToSocketBase( 2999): Close bt socket
,I/BtToRequestSocket( 2999): Close server socket
,I/jxcore-log( 2999): SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): ---- round done--------
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): do fake peer & start
I/jxcore-log( 2999): 
I/jxcore-log( 2999): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 2999): 
I/jxcore-log( 2999): SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 2999): 
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback round[0] time: 9288 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2999): TCP/IP server has received 63360 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: CLIENT is closed
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 65340 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 67320 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 69300 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 71280 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 73260 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 75240 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 77220 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 79200 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 81180 bytes of data
I/jxcore-log( 2999): 
,W/bt-btif ( 1597): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/jxcore-log( 2999): TCP/IP server has received 83160 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 85140 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 87120 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 89100 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 91080 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 93060 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 97020 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 99000 bytes of data
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2999): 
,I/wpa_supplicant(  934): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/ConnectivityService(  775): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  775): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  775): Attempting to switch to mobile
,D/ConnectivityService(  775): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  775): android_net_utils_resetConnections in env=0x75e05578 clazz=0x5ea00001 iface=wlan0 mask=0x3
,I/jxcore-log( 2999): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): The Coordinator has disconnected!
I/jxcore-log( 2999): 
D/ConnectivityService(  775): resetConnections(wlan0, 3)
,V/NativeCrypto( 1100): Read error: ssl=0x78aadba0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1100): SSL shutdown failed: ssl=0x78aadba0: I/O error during system call, Broken pipe
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  775): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,I/        ( 2999): Cleared service requests
,I/        ( 2999): Started peer discovery
,I/jxcore-log( 2999): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): printNetworkInfo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): found interfaceName: lo
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): Turning Wifi off
I/jxcore-log( 2999): 
,D/WifiService(  775): setWifiEnabled: false pid=2999, uid=10108
,I/jxcore-log( 2999): Turning Wifi back on
I/jxcore-log( 2999): 
D/WifiService(  775): setWifiEnabled: true pid=2999, uid=10108
,E/WifiStateMachine(  775): scanCount==0 - aborting
,D/WifiController(  775): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 484ms
,I/jxcore-log( 2999): toggleWiFi finished
I/jxcore-log( 2999): 
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,I/jxcore-log( 2999): ReconnectWifiAP finished
I/jxcore-log( 2999): 
,I/WB      ( 2999): Wifi is DISABLED !!
,I/        ( 2999): Stoping All
I/        ( 2999): Stopping services
,I/        ( 2999): Stopping services
,I/        ( 2999): Stop Bluetooth
,I/        ( 2999): Stop Bluetooth
I/BTListenerThread( 2999): Stopped
,E/bt-btif ( 1597): bta_jv_rfcomm_stop_server
,I/chromium( 2999): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
I/SS      ( 2999): We got empty peers list
I/        ( 2999): Clearing local services failed, error code 2
I/        ( 2999): Clearing service requests failed, error code 2
,I/        ( 2999): Stopping peer discovery failed, error code 2
,I/ActivityManager(  775): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3295 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
,I/wpa_supplicant(  934): P2P-FIND-STOPPED 
I/wpa_supplicant(  934): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant(  934): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  934): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant(  934): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  934): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  934): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant(  934): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  934): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant(  934): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  934): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/wpa_supplicant(  934): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant(  934): p2p0: CTRL-EVENT-TERMINATING 
,D/BluetoothManagerService(  775): Message: 20
,D/BluetoothManagerService(  775): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42a95538:true
,D/LocalBluetoothProfileManager( 3295): Adding local A2DP profile
,D/BluetoothManagerService(  775): Message: 30
,D/LocalBluetoothProfileManager( 3295): Adding local HEADSET profile
,D/BluetoothManagerService(  775): Message: 30
W/ContextImpl( 3295): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
W/ContextImpl( 3295): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
,D/BluetoothManagerService(  775): Message: 30
,D/BluetoothManagerService(  775): Message: 30
,D/LocalBluetoothProfileManager( 3295): Adding local MAP profile
D/BluetoothMap( 3295): Create BluetoothMap proxy object
,D/BluetoothManagerService(  775): Message: 30
,D/BluetoothManagerService(  775): Message: 30
,D/LocalBluetoothProfileManager( 3295): LocalBluetoothProfileManager construction complete
W/ContextImpl( 3295): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
W/ContextImpl( 3295): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
W/ContextImpl( 3295): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1376 
,W/ContextImpl( 3295): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/dalvikvm( 3295): GC_CONCURRENT freed 328K, 3% free 16823K/17184K, paused 4ms+2ms, total 24ms
D/BluetoothA2dp( 3295): Proxy object connected
,D/A2dpProfile( 3295): Bluetooth service connected
,I/ActivityManager(  775): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3324 uid=10052 gids={50052, 3003, 1028, 1015}
,I/ActivityManager(  775): Killing 2314:com.android.providers.calendar/u0a1 (adj 15): empty #17
,D/BluetoothHeadset( 3295): Proxy object connected
,D/HeadsetProfile( 3295): Bluetooth service connected
,D/BluetoothInputDevice( 3295): Proxy object connected
,D/HidProfile( 3295): Bluetooth service connected
,D/BluetoothPan( 3295): BluetoothPAN Proxy object connected
D/PanProfile( 3295): Bluetooth service connected
D/BluetoothMap( 3295): Proxy object connected
D/MapProfile( 3295): Bluetooth service connected
,D/BluetoothMap( 3295): getConnectedDevices()
,D/BluetoothPbap( 3295): Proxy object connected
,D/PbapServerProfile( 3295): Bluetooth service connected
,D/Tethering(  775): InitialState.processMessage what=4
,D/Tethering(  775): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant(  934): wlan0: CTRL-EVENT-TERMINATING 
,D/dalvikvm( 3324): GC_CONCURRENT freed 181K, 2% free 16923K/17136K, paused 2ms+2ms, total 15ms
,I/ActivityManager(  775): Killing 2734:com.android.keychain/1000 (adj 15): empty #17
,W/Settings( 2005): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  996): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/jxcore-log( 2999): SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 2999): 
I/jxcore-log( 2999): SendDataConnector.js: Connect (retry count 0) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 2999): 
I/jxcore-log( 2999): SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 2999): 
,I/jxcore-log( 2999): SendDataConnector.js: do connect now
I/jxcore-log( 2999): 
D/AndroidRuntime( 2999): Shutting down VM
W/dalvikvm( 2999): threadid=1: thread exiting with uncaught exception (group=0x4154fba8)
I/dalvikvm( 2999): threadid=1: stack overflow on call to Ljava/lang/ThreadGroup;.uncaughtException:VLL
I/dalvikvm( 2999):   method requires 16+20+12=48 bytes, fp is 0x6d3ef314 (20 left)
I/dalvikvm( 2999):   expanding stack end (0x6d3ef300 to 0x6d3ef000)
,I/dalvikvm( 2999): Shrank stack (to 0x6d3ef300, curFrame is 0x6d3f4fb0)
,D/WifiController(  775): DEFERRED_TOGGLE handled
,D/SoftapController(  182): Softap fwReload - Ok
D/CommandListener(  182): Setting iface cfg
,D/CommandListener(  182): Trying to bring down wlan0
,I/wpa_supplicant( 3345): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3345): rfkill: Cannot open RFKILL control device
,D/WifiMonitor(  775): startMonitoring(wlan0) with mConnected = false
,D/Tethering(  775): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3345): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  775): Loading config and enabling all networks
,W/Settings( 2005): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  182): Setting iface cfg
,D/CommandListener(  182): Trying to bring up p2p0
,D/WifiMonitor(  775): startMonitoring(p2p0) with mConnected = true
,D/Tethering(  775): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  775): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  775): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/dalvikvm( 1238): GC_CONCURRENT freed 325K, 3% free 16763K/17120K, paused 3ms+1ms, total 16ms
,I/ActivityManager(  775): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=3356 uid=10031 gids={50031, 3003, 1028, 1015}
,D/dalvikvm( 3356): DexOpt: couldn't find static field Landroid/support/v4/e/a;.common_ic_googleplayservices
,W/dalvikvm( 3356): VFY: unable to resolve static field 811 (common_ic_googleplayservices) in Landroid/support/v4/e/a;
D/dalvikvm( 3356): VFY: replacing opcode 0x60 at 0x0051
I/dalvikvm( 3356): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.e.a
W/dalvikvm( 3356): VFY: unable to resolve virtual method 323: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 3356): VFY: replacing opcode 0x6e at 0x018f
,I/dalvikvm( 3356): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.e.a
W/dalvikvm( 3356): VFY: unable to resolve virtual method 671: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 3356): VFY: replacing opcode 0x6e at 0x000b
D/dalvikvm( 3356): DexOpt: couldn't find static field Landroid/support/v4/e/a;.common_full_open_on_phone
,I/dalvikvm( 3356): DexOpt: unable to optimize static field ref 0x032a at 0x85 in Lcom/google/android/gms/common/e;.a
,D/dalvikvm( 3356): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 3356): VFY: unable to resolve instance field 71
D/dalvikvm( 3356): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 3356): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3356): DexOpt: unable to optimize instance field ref 0x0047 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 3356): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 3356): DexOpt: unable to optimize instance field ref 0x0047 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,I/iu.Environment( 1335): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/dalvikvm( 3356): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 3356): VFY: unable to resolve instance field 71
,D/dalvikvm( 3356): VFY: replacing opcode 0x54 at 0x0011
D/dalvikvm( 3356): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3356): DexOpt: unable to optimize instance field ref 0x0047 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,D/dalvikvm( 3356): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3356): DexOpt: unable to optimize instance field ref 0x0047 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 3356): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 3356): DexOpt: unable to optimize instance field ref 0x003d at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,I/SystemUpdateService( 1335): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1335): onCreate
,D/SystemUpdateService( 1335): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/Babel   ( 2005): connection state changed from CONNECTED to DISCONNECTED
,I/iu.UploadsManager( 1335): num queued entries: 0
,I/SystemUpdateService( 1335): active receiver: enabled
I/iu.UploadsManager( 1335): num updated entries: 0
,I/SystemUpdateService( 1335): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1335): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/iu.SyncManager( 1335): NEXT; no task
I/SystemUpdateService( 1335): now status is 0 (complete)
I/SystemUpdateService( 1335): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1335): file has been verified
,I/SystemUpdateService( 1335): OTA package size = 2571501
,I/SystemUpdateService( 1335): showing system update notification
,D/SystemUpdateService( 1335): onDestroy
I/ActivityManager(  775): Killing 2851:com.google.android.apps.magazines/u0a56 (adj 15): empty #17
,W/bt-btif ( 1597): dm_pm_timer expires
,W/bt-btif ( 1597): dm_pm_timer expires 0
,W/bt-btif ( 1597): proc dm_pm_timer expires
,E/bt-btif ( 1597): bta_dm_pm_btm_status  hci_status=36
,I/BtToSocketBase( 2999): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2999): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2999): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT8157
,I/BtToSocketBase( 2999): Stop ReceivingThread
I/BtToSocketBase( 2999): Stop SendingThread
,I/BtToSocketBase( 2999): Close local in
,I/BtToSocketBase( 2999): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,W/bt-btif ( 1597): invalid rfc slot id: 4
I/BtConnectorHelper( 2999): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 2999): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT8157
,I/BtToSocketBase( 2999): Close LocalOutputStream
,I/BtToSocketBase( 2999): Close localHostSocket
I/BtToSocketBase( 2999): Close bt in
,I/BtToSocketBase( 2999): Close bt out
I/BtToSocketBase( 2999): Close bt socket
,I/BtToSocketBase( 2999): Close bt in
I/BtToSocketBase( 2999): Close bt out
,I/BtToSocketBase( 2999): Close bt socket
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1219): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1219): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,W/bt-l2cap( 1597): l2cu_get_conn_role 1
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BluetoothConnectionReceiver( 1219): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1219): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75199428 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1219): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1219): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 1597): l2cu_get_conn_role 1
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [58:2a:f7:ed:96:be]: 6, 1d, 7d3
,I/BluetoothConnectionReceiver( 1219): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1219): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1219): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1219): Bluetooth Device Name: ALE-L21
,W/bt-l2cap( 1597): l2cu_get_conn_role 1
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [58:3f:54:73:64:c0]: 6, 10f, 608
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3345): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3345): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3345): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  775): scanCount==0 - aborting
,W/bt-btif ( 1597): info:x10
D/        ( 1597): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/WifiStateMachine(  775): VerifyingLinkState enter
,D/WifiStateMachine(  775): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  775): CaptivePortalCheckState enter
D/ConnectivityService(  775): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  775): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  775): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  775): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  775): Unexpected mtu value: android.net.wifi.WifiStateTracker@42ace698
,D/Nat464Xlat(  775): requiresClat: netType=1, hasIPv4Address=true
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [58:2a:f7:ed:96:be]: 6, f, 410d
,I/BluetoothConnectionReceiver( 1219): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1219): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/ConnectivityService(  775): NetTransition Wakelock for ConnectedState released by timeout
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519995c rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,D/ConnectivityService(  775): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  775):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  775): requiresClat: netType=1, hasIPv4Address=true
,I/wpa_supplicant( 3345): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3345): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  775): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  775): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1335): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1335): num queued entries: 0
,I/wpa_supplicant( 3345): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/iu.UploadsManager( 1335): num updated entries: 0
,I/SystemUpdateService( 1335): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/iu.SyncManager( 1335): NEXT; no task
,D/dalvikvm( 1169): GC_CONCURRENT freed 338K, 3% free 17212K/17660K, paused 3ms+6ms, total 18ms
,D/SystemUpdateService( 1335): onCreate
,D/SystemUpdateService( 1335): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1335): active receiver: enabled
,I/SystemUpdateService( 1335): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1335): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1335): now status is 0 (complete)
I/SystemUpdateService( 1335): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1335): file has been verified
,I/SystemUpdateService( 1335): OTA package size = 2571501
,I/SystemUpdateService( 1335): showing system update notification
,D/SystemUpdateService( 1335): onDestroy
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/dalvikvm( 1597): GC_CONCURRENT freed 388K, 3% free 16893K/17316K, paused 17ms+1ms, total 52ms
,I/BluetoothConnectionReceiver( 1219): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1219): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,I/Babel   ( 2005): connection state changed from DISCONNECTED to CONNECTED
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3345): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,D/ConnectivityService(  775): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [00:f4:6f:30:e0:6c]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751995e4 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3345): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/CaptivePortalTracker(  775): DelayedCaptiveCheckState{ when=-5ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  775): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  775): Checking http://216.58.209.46/generate_204
,I/wpa_supplicant( 3345): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/CaptivePortalTracker(  775): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  775): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  775): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  775): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  775): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant( 3345): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3345): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [58:3f:54:73:64:c0]: 6, f, 410d
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3345): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3345): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [00:f4:6f:30:e0:6c]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/ConnectivityService(  775): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  775): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  775): Attempting to switch to mobile
,D/ConnectivityService(  775): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  775): android_net_utils_resetConnections in env=0x75e05578 clazz=0x7db00001 iface=wlan0 mask=0x3
D/ConnectivityService(  775): resetConnections(wlan0, 3)
,V/NativeCrypto( 1100): Read error: ssl=0x7912cfb0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1100): SSL shutdown failed: ssl=0x7912cfb0: I/O error during system call, Broken pipe
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  775): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,D/dalvikvm(  775): GC_CONCURRENT freed 2289K, 53% free 26857K/56340K, paused 3ms+4ms, total 56ms
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [58:3f:54:73:64:c0]: 7, f, 610c
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [7c:f9:0e:34:8a:a0]: 0, 0, 0
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/Tethering(  775): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  775): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  775): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/iu.Environment( 1335): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1335): num queued entries: 0
,I/Babel   ( 2005): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1335): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1335): onCreate
,D/SystemUpdateService( 1335): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.UploadsManager( 1335): num updated entries: 0
,I/SystemUpdateService( 1335): active receiver: enabled
,I/wpa_supplicant( 3345): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/iu.SyncManager( 1335): NEXT; no task
,I/SystemUpdateService( 1335): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1335): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1335): now status is 0 (complete)
I/SystemUpdateService( 1335): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1335): file has been verified
,I/SystemUpdateService( 1335): OTA package size = 2571501
,I/SystemUpdateService( 1335): showing system update notification
,D/SystemUpdateService( 1335): onDestroy
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751995e4 rs_disc_pending=1
E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3345): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [7c:f9:0e:34:8a:a0]: 6, f, 410d
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [00:f4:6f:30:e0:6c]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751995e4 rs_disc_pending=1
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3345): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-l2cap( 1597): l2cu_get_conn_role 1
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3345): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3345): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3345): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 3345): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3345): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 3345): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/wpa_supplicant( 3345): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3345): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/wpa_supplicant( 3345): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,D/ConnectivityService(  775): NetTransition Wakelock for ConnectedState released by timeout
,I/wpa_supplicant( 3345): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3345): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,W/bt-l2cap( 1597): l2cu_get_conn_role 1
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [7c:f9:0e:37:96:ab]: 7, f, 610c
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3345): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3345): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/wpa_supplicant( 3345): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3345): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/wpa_supplicant( 3345): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/wpa_supplicant( 3345): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 3345): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 3345): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 3345): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/wpa_supplicant( 3345): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
E/wpa_supplicant( 3345): Retrying assoc: 1 
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/wpa_supplicant( 3345): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3345): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3345): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  775): scanCount==0 - aborting
,D/WifiStateMachine(  775): VerifyingLinkState enter
,D/WifiStateMachine(  775): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  775): CaptivePortalCheckState enter
,D/WifiStateMachine(  775): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  775): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  775): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  775): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  775): Unexpected mtu value: android.net.wifi.WifiStateTracker@42ace698
,D/Nat464Xlat(  775): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  775): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  775):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  775): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  775): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  775): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1335): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1335): num queued entries: 0
,I/SystemUpdateService( 1335): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/iu.UploadsManager( 1335): num updated entries: 0
,D/SystemUpdateService( 1335): onCreate
,D/SystemUpdateService( 1335): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1335): active receiver: enabled
,I/iu.SyncManager( 1335): NEXT; no task
D/ConnectivityService(  775): Sampling interval elapsed, updating statistics ..
,I/SystemUpdateService( 1335): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1335): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1335): now status is 0 (complete)
I/SystemUpdateService( 1335): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1335): file has been verified
,I/SystemUpdateService( 1335): OTA package size = 2571501
D/ConnectivityService(  775): Done.
D/ConnectivityService(  775): Setting timer for 720seconds
,I/SystemUpdateService( 1335): showing system update notification
,D/SystemUpdateService( 1335): onDestroy
,I/Babel   ( 2005): connection state changed from DISCONNECTED to CONNECTED
,D/dalvikvm( 1100): GC_CONCURRENT freed 530K, 5% free 18452K/19352K, paused 12ms+1ms, total 61ms
,D/ConnectivityService(  775): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3345): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3345): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3345): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/wpa_supplicant( 3345): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3345): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/wpa_supplicant( 3345): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/CaptivePortalTracker(  775): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  775): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  775): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  775): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  775): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  775): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  775): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  775): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,W/bt-l2cap( 1597): l2cu_get_conn_role 1
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/ConnectivityService(  775): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  775): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  775): Attempting to switch to mobile
,D/ConnectivityService(  775): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  775): android_net_utils_resetConnections in env=0x75e05578 clazz=0xbd900001 iface=wlan0 mask=0x3
D/ConnectivityService(  775): resetConnections(wlan0, 3)
,V/NativeCrypto( 1100): Read error: ssl=0x78aadba0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1100): SSL shutdown failed: ssl=0x78aadba0: I/O error during system call, Broken pipe
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  775): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 3345): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3345): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3345): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  775): scanCount==0 - aborting
,D/Tethering(  775): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  775): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  775): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/iu.Environment( 1335): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1335): num queued entries: 0
,I/Babel   ( 2005): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1335): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1335): onCreate
,D/SystemUpdateService( 1335): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.UploadsManager( 1335): num updated entries: 0
,I/SystemUpdateService( 1335): active receiver: enabled
,I/SystemUpdateService( 1335): Already downloaded, skipping offpeak checks.
,I/iu.SyncManager( 1335): NEXT; no task
,I/SystemUpdateService( 1335): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1335): now status is 0 (complete)
I/SystemUpdateService( 1335): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1335): file has been verified
,I/SystemUpdateService( 1335): OTA package size = 2571501
,I/SystemUpdateService( 1335): showing system update notification
,D/SystemUpdateService( 1335): onDestroy
,D/WifiStateMachine(  775): VerifyingLinkState enter
,D/WifiStateMachine(  775): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  775): CaptivePortalCheckState enter
D/ConnectivityService(  775): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  775): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  775): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  775): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  775): Unexpected mtu value: android.net.wifi.WifiStateTracker@42ace698
,D/Nat464Xlat(  775): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  775): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  775): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  775):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  775): requiresClat: netType=1, hasIPv4Address=true
,W/bt-l2cap( 1597): l2cu_get_conn_role 1
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/Tethering(  775): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  775): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1335): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1335): num queued entries: 0
,I/SystemUpdateService( 1335): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1335): onCreate
,I/iu.UploadsManager( 1335): num updated entries: 0
,D/SystemUpdateService( 1335): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.SyncManager( 1335): NEXT; no task
,I/SystemUpdateService( 1335): active receiver: enabled
,I/SystemUpdateService( 1335): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1335): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1335): now status is 0 (complete)
I/SystemUpdateService( 1335): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1335): file has been verified
,I/SystemUpdateService( 1335): OTA package size = 2571501
,I/SystemUpdateService( 1335): showing system update notification
,D/SystemUpdateService( 1335): onDestroy
,D/dalvikvm( 2005): GC_CONCURRENT freed 1326K, 6% free 22812K/24180K, paused 3ms+1ms, total 50ms
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,I/Babel   ( 2005): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  775): handleInetConditionHoldEnd: net=1, condition=0, published condition=0
,W/bt-l2cap( 1597): l2cu_get_conn_role 1
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/dalvikvm( 1597): GC_CONCURRENT freed 410K, 3% free 16871K/17316K, paused 8ms+4ms, total 66ms
,D/CaptivePortalTracker(  775): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker(  775): Checking http://216.58.209.46/generate_204
D/ConnectivityService(  775): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/CaptivePortalTracker(  775): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  775): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  775): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  775): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  775): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/ConnectivityService(  775): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,W/bt-l2cap( 1597): l2cu_get_conn_role 1
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/ConnectivityService(  775): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  775): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  775): Attempting to switch to mobile
,D/ConnectivityService(  775): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  775): android_net_utils_resetConnections in env=0x75e05578 clazz=0xdc600001 iface=wlan0 mask=0x3
D/ConnectivityService(  775): resetConnections(wlan0, 3)
,V/NativeCrypto( 1100): Read error: ssl=0x7912cfb0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1100): SSL shutdown failed: ssl=0x7912cfb0: I/O error during system call, Broken pipe
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  775): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,D/dalvikvm(  775): GC_CONCURRENT freed 2353K, 53% free 27003K/56320K, paused 3ms+5ms, total 70ms
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/Tethering(  775): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  775): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  775): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/iu.Environment( 1335): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1335): num queued entries: 0
,I/Babel   ( 2005): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1335): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1335): onCreate
,D/SystemUpdateService( 1335): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.UploadsManager( 1335): num updated entries: 0
,I/SystemUpdateService( 1335): active receiver: enabled
,I/iu.SyncManager( 1335): NEXT; no task
,I/SystemUpdateService( 1335): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1335): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1335): now status is 0 (complete)
I/SystemUpdateService( 1335): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1335): file has been verified
,I/SystemUpdateService( 1335): OTA package size = 2571501
,I/SystemUpdateService( 1335): showing system update notification
,D/SystemUpdateService( 1335): onDestroy
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,W/bt-l2cap( 1597): l2cu_get_conn_role 1
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/SocketClient(  182): write error (Broken pipe)
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1597): l2cu_get_conn_role 1
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1597): l2cu_get_conn_role 1
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  775): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 3345): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3345): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3345): wlan0: Authentication with c0:ff:d4:d3:aa:48 timed out.
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/wpa_supplicant( 3345): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3345): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-SSID-TEMP-DISABLED id=0 ssid="NG700" auth_failures=1 duration=10
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-SSID-REENABLED id=0 ssid="NG700"
,I/wpa_supplicant( 3345): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3345): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3345): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  775): scanCount==0 - aborting
,D/WifiStateMachine(  775): VerifyingLinkState enter
,D/WifiStateMachine(  775): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  775): CaptivePortalCheckState enter
D/ConnectivityService(  775): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  775): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  775): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  775): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  775): Unexpected mtu value: android.net.wifi.WifiStateTracker@42ace698
,D/Nat464Xlat(  775): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  775): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  775):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  775): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  775): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  775): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1335): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1335): num queued entries: 0
,I/SystemUpdateService( 1335): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/iu.UploadsManager( 1335): num updated entries: 0
,I/iu.SyncManager( 1335): NEXT; no task
,D/SystemUpdateService( 1335): onCreate
,D/SystemUpdateService( 1335): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1335): active receiver: enabled
,I/SystemUpdateService( 1335): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1335): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1335): now status is 0 (complete)
I/SystemUpdateService( 1335): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1335): file has been verified
,I/SystemUpdateService( 1335): OTA package size = 2571501
,I/SystemUpdateService( 1335): showing system update notification
,D/SystemUpdateService( 1335): onDestroy
,W/ProcessCpuTracker(  775): Skipping unknown process pid 3788
,W/ProcessCpuTracker(  775): Skipping unknown process pid 3789
W/ProcessCpuTracker(  775): Skipping unknown process pid 3792
W/ProcessCpuTracker(  775): Skipping unknown process pid 3793
,W/ProcessCpuTracker(  775): Skipping unknown process pid 3796
W/ProcessCpuTracker(  775): Skipping unknown process pid 3797
W/ProcessCpuTracker(  775): Skipping unknown process pid 3800
,W/ProcessCpuTracker(  775): Skipping unknown process pid 3801
W/ProcessCpuTracker(  775): Skipping unknown process pid 3802
,W/ProcessCpuTracker(  775): Skipping unknown process pid 3803
W/ProcessCpuTracker(  775): Skipping unknown process pid 3804
,W/ProcessCpuTracker(  775): Skipping unknown process pid 3805
W/ProcessCpuTracker(  775): Skipping unknown process pid 3806
,W/ProcessCpuTracker(  775): Skipping unknown process pid 3809
,W/ProcessCpuTracker(  775): Skipping unknown process pid 3812
I/Babel   ( 2005): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  775): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  775): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=5 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  775): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  775): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  775): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  775): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  775): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  775): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  775): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/ConnectivityService(  775): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  775): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  775): Attempting to switch to mobile
,D/ConnectivityService(  775): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  775): android_net_utils_resetConnections in env=0x75e05578 clazz=0xfc500001 iface=wlan0 mask=0x3
D/ConnectivityService(  775): resetConnections(wlan0, 3)
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1100): Read error: ssl=0x78aadba0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1100): SSL shutdown failed: ssl=0x78aadba0: I/O error during system call, Broken pipe
,D/Nat464Xlat(  775): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,D/Tethering(  775): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  775): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  775): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/iu.Environment( 1335): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1335): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/Babel   ( 2005): connection state changed from CONNECTED to DISCONNECTED
,I/iu.UploadsManager( 1335): num queued entries: 0
I/iu.UploadsManager( 1335): num updated entries: 0
,D/SystemUpdateService( 1335): onCreate
,I/iu.SyncManager( 1335): NEXT; no task
,D/dalvikvm( 1335): GC_CONCURRENT freed 1159K, 6% free 18959K/20148K, paused 2ms+2ms, total 38ms
,D/SystemUpdateService( 1335): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1335): active receiver: enabled
,I/SystemUpdateService( 1335): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1335): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1335): now status is 0 (complete)
I/SystemUpdateService( 1335): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1335): file has been verified
,I/SystemUpdateService( 1335): OTA package size = 2571501
,I/SystemUpdateService( 1335): showing system update notification
,D/SystemUpdateService( 1335): onDestroy
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  182): write error (Broken pipe)
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 3345): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3345): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3345): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  775): scanCount==0 - aborting
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,D/WifiStateMachine(  775): VerifyingLinkState enter
,D/WifiStateMachine(  775): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  775): CaptivePortalCheckState enter
D/ConnectivityService(  775): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  775): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  775): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  775): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  775): Unexpected mtu value: android.net.wifi.WifiStateTracker@42ace698
,D/Nat464Xlat(  775): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  775): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  775): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  775):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  775): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  775): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  775): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1335): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1335): num queued entries: 0
,I/SystemUpdateService( 1335): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1335): onCreate
,D/SystemUpdateService( 1335): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.UploadsManager( 1335): num updated entries: 0
,I/iu.SyncManager( 1335): NEXT; no task
,I/SystemUpdateService( 1335): active receiver: enabled
,I/SystemUpdateService( 1335): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1335): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1335): now status is 0 (complete)
I/SystemUpdateService( 1335): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1335): file has been verified
,I/SystemUpdateService( 1335): OTA package size = 2571501
,I/SystemUpdateService( 1335): showing system update notification
,D/SystemUpdateService( 1335): onDestroy
,I/Babel   ( 2005): connection state changed from DISCONNECTED to CONNECTED
,D/dalvikvm( 1100): GC_CONCURRENT freed 573K, 5% free 18411K/19320K, paused 2ms+3ms, total 30ms
,D/ConnectivityService(  775): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/ConnectivityService(  775): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  775): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  775): Attempting to switch to mobile
,D/ConnectivityService(  775): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  775): android_net_utils_resetConnections in env=0x75e05578 clazz=0x1bc00001 iface=wlan0 mask=0x3
D/ConnectivityService(  775): resetConnections(wlan0, 3)
,V/NativeCrypto( 1100): Read error: ssl=0x7912cfb0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1100): SSL shutdown failed: ssl=0x7912cfb0: I/O error during system call, Broken pipe
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  775): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/CaptivePortalTracker(  775): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=6 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  775): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  775): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  775): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  775): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  775): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/Tethering(  775): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  775): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  775): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/iu.Environment( 1335): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1335): num queued entries: 0
,I/SystemUpdateService( 1335): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1335): onCreate
,D/SystemUpdateService( 1335): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/Babel   ( 2005): connection state changed from CONNECTED to DISCONNECTED
,D/dalvikvm( 3356): GC_CONCURRENT freed 282K, 2% free 16804K/17120K, paused 2ms+1ms, total 39ms
,I/iu.UploadsManager( 1335): num updated entries: 0
,I/SystemUpdateService( 1335): active receiver: enabled
,I/iu.SyncManager( 1335): NEXT; no task
,I/SystemUpdateService( 1335): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1335): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1335): now status is 0 (complete)
I/SystemUpdateService( 1335): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1335): file has been verified
,I/SystemUpdateService( 1335): OTA package size = 2571501
,I/SystemUpdateService( 1335): showing system update notification
,D/SystemUpdateService( 1335): onDestroy
,W/bt-l2cap( 1597): l2cu_get_conn_role 1
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10,
,D/        ( 1597): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BluetoothConnectionReceiver( 1219): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=7936, deviceClass=7936]),
,I/BluetoothClassifier( 1219): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1219): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1219): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,W/bt-l2cap( 1597): l2cu_get_conn_role 1
,D/dalvikvm(  996): GC_CONCURRENT freed 446K, 3% free 17906K/18460K, paused 3ms+1ms, total 18ms
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:76:27]: 6, f, 410d
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 3345): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3345): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
I/wpa_supplicant( 3345): wlan0: WPA: 4-Way Handshake failed - pre-shared key may be incorrect
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-SSID-TEMP-DISABLED id=0 ssid="NG700" auth_failures=1 duration=10
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  775): NetTransition Wakelock for ConnectedState released by timeout
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-SSID-REENABLED id=0 ssid="NG700"
,I/wpa_supplicant( 3345): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
E/wpa_supplicant( 3345): Retrying assoc: 1 
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/wpa_supplicant( 3345): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3345): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
I/wpa_supplicant( 3345): wlan0: WPA: 4-Way Handshake failed - pre-shared key may be incorrect
,I/wpa_supplicant( 3345): wlan0: CTRL-EVENT-SSID-TEMP-DISABLED id=0 ssid="NG700" auth_failures=2 duration=20
,D/SupplicantStateTracker(  775): Failed to authenticate, disabling network 0
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,W/bt-l2cap( 1597): l2cu_get_conn_role 1
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/ConnectivityService(  775): handleInetConditionChange: no active default network - ignore
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1597): l2cu_get_conn_role 0
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [58:3f:54:73:64:c0]: 6, f, 410d
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/dalvikvm( 1597): GC_CONCURRENT freed 395K, 3% free 16871K/17312K, paused 7ms+0ms, total 50ms
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519995c rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519aab4 rs_disc_pending=1
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 6109
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75199b18 rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [34:fc:ef:11:ae:67]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): RS in progress - Set DISC Pending flag in btm_sec_send_hci_disconnect to delay disconnect
,W/bt-btm  ( 1597): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75199b18 rs_disc_pending=2
E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519aab4 rs_disc_pending=1
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [58:3f:54:73:64:c0]: 7, f, 6109
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:76:27]: 7, f, 610c
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [7c:f9:0e:34:8a:a0]: 0, 0, 0
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75199b18 rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75199b18 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [34:fc:ef:11:ae:67]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): RS in progress - Set DISC Pending flag in btm_sec_send_hci_disconnect to delay disconnect
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btm  ( 1597): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519aab4 rs_disc_pending=2
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 7, f, 6109
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75199b18 rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 7, f, 610c
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75199b18 rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75199b18 rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [b4:ce:f6:ab:a4:6a]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): RS in progress - Set DISC Pending flag in btm_sec_send_hci_disconnect to delay disconnect
,D/dalvikvm( 1597): GC_CONCURRENT freed 397K, 3% free 16871K/17304K, paused 7ms+0ms, total 44ms
,W/bt-btm  ( 1597): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75199b18 rs_disc_pending=2
W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:76:27]: 7, f, 610c
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1597): l2cu_get_conn_role 0
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75199e90 rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75199e90 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [34:fc:ef:9d:93:0b]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 6, f, 4106
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [34:fc:ef:9d:93:0b]: 7, 1d, 7d3
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:76:27]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [34:fc:ef:11:ae:67]: 7, f, 610c
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): RS in progress - Set DISC Pending flag in btm_sec_send_hci_disconnect to delay disconnect
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btm  ( 1597): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519aab4 rs_disc_pending=2
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [34:fc:ef:9d:93:0b]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [f8:cf:c5:d9:e5:61]: 6, f, 4106
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519ac70 rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519a04c rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519a04c rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519ac70 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/dalvikvm( 1597): GC_CONCURRENT freed 395K, 3% free 16884K/17312K, paused 9ms+8ms, total 61ms
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [b4:ce:f6:ab:a4:6a]: 6, f, 4106
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519ac70 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 7, f, 230f
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [34:fc:ef:9d:93:0b]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [f8:cf:c5:d9:e5:61]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519a04c rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519a04c rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519ac70 rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519ac70 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 6, f, 4106
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [34:fc:ef:9d:93:0b]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519a04c rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [90:e7:c4:f6:69:77]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519a04c rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519ac70 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [f8:95:c7:87:85:54]: 6, f, 4106
,I/BluetoothConnectionReceiver( 1219): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1219): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75198d38 rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75198d38 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1219): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1219): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:76:27]: 6, f, 410d
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519a04c rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/dalvikvm( 1597): GC_CONCURRENT freed 410K, 3% free 16871K/17312K, paused 8ms+2ms, total 56ms
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519a04c rs_disc_pending=1
W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [90:e7:c4:f6:69:77]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519ac70 rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [f8:95:c7:87:85:54]: 7, 1d, 7d3
,I/BluetoothConnectionReceiver( 1219): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1219): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519ac70 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75198d38 rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75198d38 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1219): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1219): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:76:27]: 6, f, 410d
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519a04c rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [58:3f:54:73:64:c0]: 7, f, 230f
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519a04c rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [f8:95:c7:87:85:54]: 7, 1d, 7d3
,I/BluetoothConnectionReceiver( 1219): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1219): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75198d38 rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 7, f, 230f
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75198d38 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1219): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1219): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:76:27]: 6, f, 410d
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [80:01:84:8a:b3:68]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [f8:95:c7:87:85:54]: 6, 1d, 7d3
,I/BluetoothConnectionReceiver( 1219): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1219): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75198d38 rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75198d38 rs_disc_pending=1
W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:76:27]: 7, f, 6109
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1219): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1219): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,E/bt-btm  ( 1597): RS in progress - Set DISC Pending flag in btm_sec_send_hci_disconnect to delay disconnect
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,W/bt-btm  ( 1597): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=2
W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
D/dalvikvm( 1597): GC_CONCURRENT freed 393K, 3% free 16870K/17296K, paused 1ms+1ms, total 9ms
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [7c:f9:0e:37:96:ab]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [f8:95:c7:87:85:54]: 6, 1d, 7d3
,I/BluetoothConnectionReceiver( 1219): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1219): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75198d38 rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [58:3f:54:73:64:c0]: 6, f, 410d
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75198d38 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1219): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1219): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,D/BluetoothAdapterService(1113238024)( 1597): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1597): getBondedDevices: length=3
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:76:27]: 6, f, 410d
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [7c:f9:0e:37:96:ab]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:76:27]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [7c:f9:0e:37:96:ab]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [f8:cf:c5:d9:e5:61]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519ac70 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519a04c rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519ac70 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14),
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/dalvikvm( 1597): GC_CONCURRENT freed 392K, 3% free 16871K/17296K, paused 7ms+6ms, total 53ms
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x751997a0 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519ac70 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519a04c rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519ac70 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/dalvikvm(  775): GC_CONCURRENT freed 2452K, 52% free 27033K/56300K, paused 3ms+4ms, total 57ms
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [90:e7:c4:f6:69:77]: 7, f, 230f
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519ac70 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,D/ConnectivityService(  775): Sampling interval elapsed, updating statistics ..
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519a04c rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,I/ProcessStatsService(  775): Prepared write state in 45ms
,D/ConnectivityService(  775): Done.
,D/ConnectivityService(  775): Setting timer for 720seconds
,I/ProcessStatsService(  775): Prepared write state in 9ms
,V/GLSActivity( 1100): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1100): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1335): Aggregate from 1448013017923 (log), 1448013017923 (data)
,I/ProcessStatsService(  775): Pruning old procstats: /data/system/procstats/state-2015-11-19-10-39-42.bin
,V/NativeCrypto( 1100): SSL shutdown failed: ssl=0x78adc590: I/O error during system call, Connection timed out
,V/NativeCrypto( 1100): SSL shutdown failed: ssl=0x78ab5b88: I/O error during system call, Connection timed out
W/SocketClient(  182): write error (Broken pipe)
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519ac70 rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519a04c rs_disc_pending=1
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [f8:cf:c5:d9:e5:61]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519a04c rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [90:e7:c4:f6:69:77]: 7, f, 230f
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [34:fc:ef:9d:93:0b]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:76:27]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [90:e7:c4:f6:69:77]: 7, f, 230f
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): RS in progress - Set DISC Pending flag in btm_sec_send_hci_disconnect to delay disconnect
,W/bt-btm  ( 1597): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75199cd4 rs_disc_pending=2
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 1597): l2cu_get_conn_role 0
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:76:27]: 6, f, 4106
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/dalvikvm( 1597): GC_CONCURRENT freed 395K, 3% free 16871K/17300K, paused 12ms+4ms, total 61ms
,W/bt-l2cap( 1597): l2cu_get_conn_role 1
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [34:fc:ef:9d:93:0b]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): RS in progress - Set DISC Pending flag in btm_sec_send_hci_disconnect to delay disconnect
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,W/bt-btm  ( 1597): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75199cd4 rs_disc_pending=2
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1597): bta_dm_check_av:0
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 6, f, 4106
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [34:fc:ef:9d:93:0b]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): RS in progress - Set DISC Pending flag in btm_sec_send_hci_disconnect to delay disconnect
,W/bt-btm  ( 1597): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75199cd4 rs_disc_pending=2
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 1597): l2cu_get_conn_role 0
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [08:ec:a9:50:76:27]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1597): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): RS in progress - Set DISC Pending flag in btm_sec_send_hci_disconnect to delay disconnect
,W/bt-btm  ( 1597): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x75199cd4 rs_disc_pending=2
,E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1597): info:x10
,D/        ( 1597): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 2205
,E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519a04c rs_disc_pending=0
,W/bt-btif ( 1597): bta_dm_check_av:0
,W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
,TIME-OUT KILL (timeout was 1800000ms),W/bt-btif ( 1597): info:x10
D/        ( 1597): remote version info [08:ec:a9:50:76:27]: 6, f, 4106
E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
E/bt-btm  ( 1597): tBTM_SEC_DEV:0x7519a04c rs_disc_pending=1
W/bt-btif ( 1597): bta_dm_check_av:0
W/bt-btif ( 1597): btif_dm_cback : unhandled event (14)
E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
W/bt-btif ( 1597): info:x10
D/        ( 1597): remote version info [08:ec:a9:50:75:41]: 7, f, 230f
E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
W/bt-btif ( 1597): info:x10
D/        ( 1597): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
W/bt-btif ( 1597): info:x10
D/        ( 1597): remote version info [34:fc:ef:9d:93:0b]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
D/AndroidRuntime( 4013): 
D/AndroidRuntime( 4013): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4013): CheckJNI is OFF
D/dalvikvm( 4013): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4013): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4013): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4013): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4013): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4013): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
E/bt-btm  ( 1597): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 1597): aclStateChangeCallback: Device is NULL
D/AndroidRuntime( 4013): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  775): Force stopping com.test.thalitest appid=10108 user=-1: uninstall pkg
I/ActivityManager(  775): Killing 2999:com.test.thalitest/u0a108 (adj 0): stop com.test.thalitest
I/ActivityManager(  775): Killing 2773:com.google.android.apps.docs/u0a35 (adj 15): empty for 1820s
I/ActivityManager(  775): Killing 2751:com.quickoffice.android/u0a65 (adj 15): empty for 1820s
I/ActivityManager(  775): Killing 2698:com.android.musicfx/u0a13 (adj 15): empty for 1820s
I/ActivityManager(  775): Killing 2808:com.google.android.partnersetup/u0a11 (adj 15): empty for 1820s
I/ActivityManager(  775): Killing 956:android.process.acore/u0a3 (adj 15): empty for 1820s
I/ActivityManager(  775): Killing 2651:com.android.defcontainer/u0a4 (adj 15): empty for 1821s
I/ActivityManager(  775): Killing 2893:com.google.android.apps.cloudprint/u0a32 (adj 15): empty for 1831s
I/ActivityManager(  775):   Force finishing activity ActivityRecord{448c3578 u0 com.test.thalitest/.MainActivity t2}
I/WindowState(  775): WIN DEATH: Window{448cfc80 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  775): Skipping PackageSetting{426ece78 com.example.hello/10115} due to missing metadata
I/ActivityManager(  775): Force stopping com.test.thalitest appid=10108 user=0: pkg removed
I/InputReader(  775): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine(  996): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  775):   Scheme: "sms"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/ActivityManager(  775): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4046 uid=10003 gids={50003, 3003, 1028, 1015}
D/dalvikvm( 1065): GC_EXPLICIT freed 1358K, 8% free 26155K/28288K, paused 2ms+5ms, total 31ms
I/LatinIME:LogUtils(  983): Dictionary info: dictionary = main:en_us ; version = 44 ; date = 1393228158
I/Launcher( 1065): Deferring update until onResume
D/dalvikvm( 1219): GC_EXPLICIT freed 445K, 8% free 17872K/19376K, paused 2ms+1ms, total 40ms
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  775):   Scheme: "smsto"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/Launcher( 1065): Deferring update until onResume
D/dalvikvm(  775): GC_EXPLICIT freed 1153K, 53% free 26774K/56300K, paused 3ms+5ms, total 73ms
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  775):   Scheme: "mms"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  775):   Scheme: "mmsto"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
W/Binder  (  983): Caught a RuntimeException from the binder stub implementation.
W/Binder  (  983): java.lang.NullPointerException
W/Binder  (  983): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  (  983): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  (  983): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  (  983): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  775): Got RemoteException sending setActive(false) notification to pid 2999 uid 10108
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  775):   Scheme: "sms"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  775):   Scheme: "smsto"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/BackupManagerService(  775): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  775): removePackageParticipantsLocked: uid=10108 #1
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  775):   Scheme: "mms"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/dalvikvm(  775): GC_EXPLICIT freed 362K, 53% free 26812K/56300K, paused 3ms+7ms, total 98ms
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  775):   Scheme: "mmsto"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/dalvikvm( 4046): GC_CONCURRENT freed 255K, 2% free 16942K/17228K, paused 1ms+1ms, total 16ms
D/dalvikvm( 1017): GC_CONCURRENT freed 385K, 3% free 17067K/17484K, paused 1ms+0ms, total 10ms
D/VoicemailCleanupService( 4046): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  775): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=4063 uid=10013 gids={50013, 3003, 3002}
D/AndroidRuntime( 4013): Shutting down VM
D/dalvikvm( 4013): GC_CONCURRENT freed 94K, 15% free 558K/656K, paused 0ms+0ms, total 2ms
I/Icing.InternalIcingCorporaProvider( 1219): Updating corpora: A: com.test.thalitest, C: MAYBE
I/ActivityManager(  775): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/ActivityManager(  775): Resuming delayed broadcast
W/Launcher( 1065): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@425a1b98 new=com.google.android.velvet.VelvetApplication@425a1b98
I/ActivityManager(  775): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4078 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
W/ContextImpl( 4078): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2407 
I/ActivityManager(  775): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
I/ContactLocale( 4046): AddressBook Labels [en_US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/Icing.InternalIcingCorporaProvider( 1219): UpdateCorporaTask done [took 56 ms] updated apps [took 56 ms] 
I/ActivityManager(  775): Resuming delayed broadcast
I/ActivityManager(  775): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PackageBroadcastService( 1335): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1335): Clearing selected account for com.test.thalitest
I/ActivityManager(  775): Resuming delayed broadcast
I/ActivityManager(  775): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/ActivityManager(  775): Resuming delayed broadcast
I/ActivityManager(  775): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/LocationSettingsChecker( 1335): Removing dialog suppression flag for package com.test.thalitest
W/BaseAppContext( 1335): Using Auth Proxy for data requests.
W/BaseAppContext( 1335): Using Auth Proxy for data requests.
D/gH_CompatibleDatabase( 1335): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1335): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1335): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1335): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/dalvikvm( 1335): GC_CONCURRENT freed 696K, 6% free 19012K/20148K, paused 3ms+4ms, total 26ms
D/gH_CompatibleDatabase( 1335): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1335): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1335): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1335): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1335): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1335): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1335): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1335): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1335): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/GMPM-SVC( 1335): App measurement is starting up
I/PeopleContactsSync( 1335): CP2 sync disabled
I/Icing   ( 1335): doRemovePackageData com.test.thalitest
D/dalvikvm( 1335): GC_CONCURRENT freed 483K, 5% free 19222K/20148K, paused 4ms+3ms, total 38ms
W/DriveInitializer( 1335): Background init thread started
W/DriveInitializer( 1335): Awaiting to be initialized
E/SQLiteLog( 1335): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock154] disk I/O error
E/DocListDatabase( 1335): Failed to delete from ContentFileDeletionLock154 table
E/DocListDatabase( 1335): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1335): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1335): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1335): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1335): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1335): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/DocListDatabase( 1335): 	at com.google.android.gms.drive.database.k.a(SourceFile:329)
E/DocListDatabase( 1335): 	at com.google.android.gms.drive.database.f.h(SourceFile:1062)
E/DocListDatabase( 1335): 	at com.google.android.gms.drive.s.run(SourceFile:62)
W/DriveInitializer( 1335): Background init thread ended
W/dalvikvm( 1335): threadid=26: thread exiting with uncaught exception (group=0x4154fba8)
E/SQLiteLog( 1335): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1335): disk I/O error (code 3850)
E/DriveAsyncService( 1335): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1335): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1335): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1335): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1335): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1335): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1335): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1335): 	at com.google.android.gms.drive.database.k.k(SourceFile:485)
E/DriveAsyncService( 1335): 	at com.google.android.gms.drive.database.k.b(SourceFile:460)
E/DriveAsyncService( 1335): 	at com.google.android.gms.drive.database.f.i(SourceFile:1516)
E/DriveAsyncService( 1335): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1335): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/DriveAsyncService( 1335): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1335): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1335): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1335): 	at java.lang.Thread.run(Thread.java:841)
E/GAv4-SVC( 1335): Error creating clientId file: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/gaClientId: open failed: EROFS (Read-only file system)
E/SharedPreferencesImpl( 1335): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 1335): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteLog( 1335): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GAv4-SVC( 1335): Failed to update Analytics property: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SharedPreferencesImpl( 1335): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4-SVC( 1335): Job execution failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 1335): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/FileUtils( 1335): Failed to chmod(/data/data/com.google.android.gms/files): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
E/SQLiteLog( 1335): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GAv4-SVC( 1335): Sync local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 1335): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteLog( 1335): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GAv4-SVC( 1335): Local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 1335): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/AndroidRuntime( 1335): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1335): Process: com.google.android.gms, PID: 1335
E/AndroidRuntime( 1335): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1335): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1335): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1335): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1335): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1335): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1335): 	at com.google.android.gms.drive.database.k.a(SourceFile:329)
E/AndroidRuntime( 1335): 	at com.google.android.gms.drive.database.f.h(SourceFile:1062)
E/AndroidRuntime( 1335): 	at com.google.android.gms.drive.s.run(SourceFile:62)
E/SharedPreferencesImpl( 1335): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/Process ( 1335): Sending signal. PID: 1335 SIG: 9
E/DropBoxManagerService(  775): Can't write: system_app_crash
E/DropBoxManagerService(  775): java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  775): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  775): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  775): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  775): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  775): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  775): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10018)
E/DropBoxManagerService(  775): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  775): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  775): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  775): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  775): 	... 5 more
I/ActivityManager(  775): Process com.google.android.gms (pid 1335) has died.
W/ActivityManager(  775): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  775): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  775): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 11000ms
W/ActivityManager(  775): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 11000ms
I/ActivityManager(  775): Resuming delayed broadcast
W/ActivityManager(  775): Scheduling restart of crashed service com.google.android.gms/.analytics.AnalyticsService in 10999ms
I/ActivityManager(  775): Start proc com.google.android.gms for broadcast com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy: pid=4110 uid=10007 gids={50007, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}

```
