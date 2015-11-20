#### Test 513350285301d5d_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3099): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3099):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3099):   adb logcat -s GAv4
W/GAv4    ( 3099): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3099): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3099): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3099): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,--------- beginning of system
W/ResourcesManager( 3099): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3099): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 2604): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  747): Killing 2036:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 3099): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 3099): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3099): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 3155): 
D/AndroidRuntime( 3155): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3155): CheckJNI is OFF
W/libprocessgroup(  747): failed to open /acct/uid_10038/pid_2036/cgroup.procs: No such file or directory
V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3155): Calling main entry com.android.commands.am.Am
I/ActivityManager(  747): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  747): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3180 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3155): Shutting down VM
V/ActivityManager(  747): Display changed displayId=0
I/Icing   ( 1601): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/Icing   ( 1601): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1601): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/WebViewFactory( 3180): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3180): Time to load native libraries: 2 ms (timestamps 9479-9481)
I/LibraryLoader( 3180): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3180): Binding Chromium to main looper Looper (main, tid 1) {39bebdd1}
I/LibraryLoader( 3180): Expected native library version number "",actual native library version number ""
I/chromium( 3180): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3180): Initializing chromium process, singleProcess=true
W/art     ( 3180): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3180): ApplicationContext is null in ApplicationStatus
W/chromium( 3180): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3180): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3180): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3180): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothManagerService(  747): Message: 20
D/BluetoothManagerService(  747): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2fceca11:true
W/art     ( 3180): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3180): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3180): CordovaWebView is running on device made by: LGE
W/art     ( 3180): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3180): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3180): Render dirty regions requested: true
D/Atlas   ( 3180): Validating map...
W/chromium( 3180): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3180): Initialized EGL, version 1.4
D/OpenGLRenderer( 3180): Enabling debug mode 0
W/IInputConnectionWrapper( 3180): showStatusIcon on inactive InputConnection
I/ActivityManager(  747): Displayed com.test.thalitest/.MainActivity: +468ms (total +58s247ms)
W/BindingManager( 3180): Cannot call determinedVisibility() - never saw a connection for the pid: 3180
D/JsMessageQueue( 3180): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3180): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257343360
D/JX-Cordova( 3180): jxcore cordova android initializing
,I/ActivityManager(  747): Killing 2567:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  747): failed to open /acct/uid_10069/pid_2567/cgroup.procs: No such file or directory
,W/jxcore-log( 3180): Initializing JXcore engine
W/jxcore-log( 3180): JXcore engine is ready
,W/jxcore-log( 3180): Starting JXcore engine
,W/.test.thalitest( 3180): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7998]" dev="sockfs" ino=7998 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3180): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3180): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8415]" dev="sockfs" ino=8415 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3180): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19013]" dev="sockfs" ino=19013 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3180): Platform android
W/jxcore-log( 3180): 
W/jxcore-log( 3180): Process ARCH arm
W/jxcore-log( 3180): 
,I/jxcore-log( 3180): JXcore Cordova bridge is ready!
I/jxcore-log( 3180): 
,W/jxcore-log( 3180): JXcore engine is started
,I/Choreographer( 3180): Skipped 109 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3180): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3180): Turning radios to true
I/jxcore-log( 3180): 
,D/BluetoothAdapter( 3180): enable(): BT is already enabled..!
I/jxcore-log( 3180): toggleBluetooth - 
I/jxcore-log( 3180): 
,D/WifiService(  747): setWifiEnabled: true pid=3180, uid=10270
E/WifiService(  747): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  747): New client listening to asynchronous messages
,I/jxcore-log( 3180): toggleWiFi
I/jxcore-log( 3180): 
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BluetoothManagerService(  747): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3180): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): my name is : LGE-Nexus 5_PT6584
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): attempting to connect to test coordinator
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): check test folder
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): found test : ./testFindPeers.js
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): found test : ./testReConnect.js
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): found test : ./testSendData.js
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): Test app app.js loaded
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/art     ( 1328): Explicit concurrent mark sweep GC freed 13555(807KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 19MB/32MB, paused 1.004ms total 36.451ms
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2604): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2604): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/VacuumService( 1328): Vacuum at: now=1448016159049 tag=VacuumService
,D/UdcCache:FPQuery( 1601): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetConfigurationSnapshotOperation( 1328): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1328): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1328): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1328): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1328): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1328):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1328): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1328): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1328): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1328): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1328): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1328): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1328): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/ClearcutLoggerApiImpl( 1563): disconnect managed GoogleApiClient
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/ClearcutLoggerApiImpl( 1328): disconnect managed GoogleApiClient
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): found interfaceName: lo,
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/ActivityManager(  747): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3313 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3313): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3313):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3313):   adb logcat -s GAv4
,W/GAv4    ( 3313): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3313): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3313): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  747): Killing 2511:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  747): failed to open /acct/uid_10045/pid_2511/cgroup.procs: No such file or directory
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3180): 
I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector connect called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Coordinator is now connected to the server!
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): printNetworkInfo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: lo
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3180): 
I/jxcore-log( 3180): found interfaceName: wlan0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): DBG, CoordinatorConnector command called
I/jxcore-log( 3180): 
I/jxcore-log( 3180): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":17,"addressList":[{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"F4:F1:E1:5C:3B:E2","tryCount":0}]}
I/jxcore-log( 3180): Start now : testSendData.js
I/jxcore-log( 3180): 
I/jxcore-log( 3180): stop tests now !
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): testSendData created {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 17
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): check server
I/jxcore-log( 3180): 
I/jxcore-log( 3180): serverPort is 42499
I/jxcore-log( 3180): 
,D/BluetoothManagerService(  747): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3180): Stoping All
I/        ( 3180): Stopping services
I/        ( 3180): Stop Bluetooth
,D/BluetoothManagerService(  747): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3180): Start-My BT: 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  747): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3180):  mInstanceString : {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6584","ra":"34:FC:EF:11:AE:67"}
,I/        ( 3180): All stuff available and enabled
I/        ( 3180): Stoping All
I/        ( 3180): Stopping services
I/        ( 3180): Stop Bluetooth
I/        ( 3180): Starting All
I/        ( 3180): Stopping services
I/        ( 3180): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6584","ra":"34:FC:EF:11:AE:67"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@ed1ebe3
I/        ( 3180): Stopping services
I/        ( 3180): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6584","ra":"34:FC:EF:11:AE:67"}
,I/        ( 3180): Add local service :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6584","ra":"34:FC:EF:11:AE:67"}, length : 77
,I/        ( 3180): peerDiscoveryTimer timeout value:8320
,I/        ( 3180): Stop Bluetooth
I/        ( 3180): StartBluetooth listener
I/        ( 3180): StartBluetooth listener
,D/BluetoothManagerService(  747): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 3180): StartBroadcasting started ok
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:50:32.588Z SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:50:32.588Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:32.589Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
I/jxcore-log( 3180): 
I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 3180): We already were running, thus doing nothing
,I/        ( 3180): Added local service
I/        ( 3180): Cleared service requests
I/        ( 3180): Stopped peer discovery
I/        ( 3180): Started peer discovery
I/        ( 3180): Discovery state changed to Started.
,I/BTListenerThread( 3180): starting to listen
I/BTListenerThread( 3180): waiting to accept incoming Connection
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 1 peers.
I/SS      ( 3180): Peer(1): Android_2dc2 52:55:27:f0:ff:f0
,D/WifiP2pManager( 3180): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3180): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT1268"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT1268"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT1268, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT1268, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3180): 2015-11-20T10:50:37.593Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:50:37.594Z SendDataConnector.js: Connect (retry count 0) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:50:37.596Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:50:37.596Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/        ( 3180): Connecting to null, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/art     (  747): Explicit concurrent mark sweep GC freed 25009(1132KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 999us total 83.307ms
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 2066): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2066): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
,E/bt-btif ( 2066): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2066): Entering PendingCommandState State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 2066): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,I/BluetoothBondStateMachine( 2066): StableState(): Entering Off State
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3180): we got incoming connection
,I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
I/BTListenerThread( 3180): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTListenerThread( 3180): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3180): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1397","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3180): MESSAGE_WRITE 77 bytes.
I/HS      ( 3180): Incoming connection Hand Shake finished for : samsung-SM-N9005_PT1397
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : true, samsung-SM-N9005_PT1397
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BTConnectedThread
I/BtConnectorHelper( 3180): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3180): --DoOneRunRound started
,I/jxcore-log( 3180): 2015-11-20T10:50:41.279Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): LocalHost address: localhost/127.0.0.1, port: 42499
,I/BtToRequestSocket( 3180): --DoOneRunRound ended
,I/jxcore-log( 3180): 2015-11-20T10:50:41.785Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:42.336Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:42.348Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:42.379Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:42.389Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:42.403Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:42.424Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:42.453Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:42.501Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3180): 
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:5, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 5
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T10:50:42.874Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:50:42.874Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:50:42.875Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:42.976Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:42.980Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.016Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.023Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.029Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.038Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.074Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.125Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.174Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.183Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.187Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.225Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3180): 
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
E/bt-btif ( 2066): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2066): Entering PendingCommandState State
,I/jxcore-log( 3180): 2015-11-20T10:50:43.285Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3180): 
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,I/jxcore-log( 3180): 2015-11-20T10:50:43.297Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3180): 
,E/BluetoothEventManager( 2659): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,I/jxcore-log( 3180): 2015-11-20T10:50:43.487Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.537Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.550Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.573Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.594Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.633Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.675Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.707Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.739Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.773Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.793Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.823Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.878Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.905Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.943Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.988Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:43.996Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): invalid rfc slot id: 4
,I/BtToSocketBase( 3180): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT1397
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT1397
I/BtToSocketBase( 3180): Close LocalOutputStream
,I/BtToSocketBase( 3180): Close localHostSocket
,I/BtToSocketBase( 3180): Close bt in
I/BtToSocketBase( 3180): Close bt out
,I/BtToSocketBase( 3180): Close bt in
I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,I/BtToSocketBase( 3180): Close bt socket
,I/jxcore-log( 3180): 2015-11-20T10:50:44.121Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3180): 
,W/bt-rfcomm( 2066): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 2066): RFCOMM_DisconnectInd LCID:0x42
,I/jxcore-log( 3180): 2015-11-20T10:50:44.136Z SendDataTCPServer.js: TCP/IP server is close
I/jxcore-log( 3180): 
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 2066): Failed to remove device: 00:F4:6F:30:E0:6C
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2066): StableState(): Entering Off State
,E/BluetoothEventManager( 2659): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,I/BTListenerThread( 3180): we got incoming connection
W/bt-btif ( 2066): new conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
I/BTListenerThread( 3180): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTListenerThread( 3180): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3180): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT230"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3180): MESSAGE_WRITE 77 bytes.
I/HS      ( 3180): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT230
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : true, samsung-SM-G800F_PT230
,I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BTConnectedThread
,I/BtConnectorHelper( 3180): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3180): --DoOneRunRound started
,I/jxcore-log( 3180): 2015-11-20T10:50:45.034Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): LocalHost address: localhost/127.0.0.1, port: 42499
,I/BtToRequestSocket( 3180): --DoOneRunRound ended
,I/jxcore-log( 3180): 2015-11-20T10:50:45.664Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3180): 
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3180): 2015-11-20T10:50:46.947Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:46.986Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:47.183Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:47.234Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3180): 
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3180): 2015-11-20T10:50:47.324Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:47.359Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:47.455Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:47.482Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:47.670Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:47.876Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:50:47.878Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:47.900Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:47.953Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3180): 
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/jxcore-log( 3180): 2015-11-20T10:50:48.000Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3180): 
,D/BluetoothManagerService(  747): Message: 20
D/BluetoothManagerService(  747): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c854809:true
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/jxcore-log( 3180): 2015-11-20T10:50:48.038Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3180): 
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Note3-1
,I/jxcore-log( 3180): 2015-11-20T10:50:48.104Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3180): 
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/jxcore-log( 3180): 2015-11-20T10:50:48.140Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:48.168Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:48.233Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:48.296Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:48.338Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:48.369Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:48.459Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:48.534Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:48.573Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:48.583Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:48.626Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:48.639Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:48.708Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:48.756Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:48.891Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:48.905Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:48.943Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:49.024Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:49.055Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:49.063Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:49.094Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:49.182Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:49.218Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:49.239Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:49.275Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:49.312Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:49.319Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:49.362Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:49.395Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:49.458Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:50:49.507Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): invalid rfc slot id: 6
,I/BtToSocketBase( 3180): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT230
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
,I/BtToSocketBase( 3180): Close local in
I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3180): 2015-11-20T10:50:49.622Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:50:49.623Z SendDataTCPServer.js: TCP/IP server is close
I/jxcore-log( 3180): 
,W/bt-rfcomm( 2066): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 2066): RFCOMM_DisconnectInd LCID:0x45
,I/jxcore-log( 3180): 2015-11-20T10:50:52.883Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:50:52.884Z SendDataConnector.js: Connect (retry count 1) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:50:52.884Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:50:52.885Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/        ( 3180): Connecting to null, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: S5mini-1
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 8
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T10:50:58.248Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:50:58.248Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:50:58.248Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 8 peers.
I/SS      ( 3180): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3180): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3180): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3180): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3180): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3180): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3180): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3180): Peer(8): G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 3180): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3180): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5843"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5843"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5843, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5843, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3180): 2015-11-20T10:51:03.248Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:03.249Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:51:08.252Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:08.253Z SendDataConnector.js: Connect (retry count 2) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:08.254Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:08.254Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/        ( 3180): Connecting to null, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:9, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 9
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T10:51:13.426Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:13.427Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:13.427Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 10 peers.
I/SS      ( 3180): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3180): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3180): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3180): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3180): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3180): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3180): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3180): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3180): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3180): Peer(10): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3180): Started service discovery
,I/        ( 3180): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1397","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1397","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1397, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1397, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3180): 2015-11-20T10:51:18.427Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:18.427Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
,I/        ( 3180): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5843"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5843"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5843, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5843, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3180): 2015-11-20T10:51:23.431Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:51:23.435Z SendDataConnector.js: Connect (retry count 3) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:51:23.436Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:23.438Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/        ( 3180): Connecting to null, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2066): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2066): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 1
E/bt-btif ( 2066): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2066): Entering PendingCommandState State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 0
,D/BluetoothAdapterProperties( 2066): Failed to remove device: 50:2E:6C:AC:21:50
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2066): StableState(): Entering Off State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3180): Starting to Handshake
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3180): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTConnectToThread( 3180): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 3180): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT9545","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3180): HandshakeOk : HTC-HTC One_M8_PT9545
I/HS      ( 3180): Hand Shake finished outgoing for : HTC-HTC One_M8_PT9545
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : false, HTC-HTC One_M8_PT9545
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3180): mHTTPPort  set to : 52515
I/BtConnectorHelper( 3180): Request socket is using : 52515
I/BtToRequestSocket( 3180): Now accepting connections
,I/BtConnectorHelper( 3180): Calling ConnectionStatusUpdate with port :52515
I/jxcore-log( 3180): 2015-11-20T10:51:28.916Z SendDataConnector.js: CLIENT connected to 52515, error: null
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:28.916Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:51:28.918Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): incoming data from: /127.0.0.1, port: 52515
I/BtToRequestSocket( 3180): Set local streams
I/BtToRequestSocket( 3180): rin ended ---------------------------;
,I/jxcore-log( 3180): 2015-11-20T10:51:28.979Z SendDataConnector.js: resetDataTimeout called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=0
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3180): 2015-11-20T10:51:29.899Z SendDataConnector.js: resetDataTimeout called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:51:29.901Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:51:29.936Z SendDataConnector.js: resetDataTimeout called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:29.938Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13817
,I/jxcore-log( 3180): 2015-11-20T10:51:29.987Z SendDataConnector.js: resetDataTimeout called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:29.988Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:51:30.060Z SendDataConnector.js: resetDataTimeout called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:51:30.066Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3917
,I/jxcore-log( 3180): 2015-11-20T10:51:30.105Z SendDataConnector.js: resetDataTimeout called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:30.106Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:51:30.159Z SendDataConnector.js: resetDataTimeout called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:30.160Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:51:30.204Z SendDataConnector.js: resetDataTimeout called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:30.205Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:51:30.266Z SendDataConnector.js: resetDataTimeout called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:30.267Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:51:30.360Z SendDataConnector.js: resetDataTimeout called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:51:30.361Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:51:30.579Z SendDataConnector.js: resetDataTimeout called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:51:30.581Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:51:30.586Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:30.589Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:30.590Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3180): 
,I/BtConnectorHelper( 3180): Disconnect outgoing peer: 50:2E:6C:AC:21:50
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
I/BtToRequestSocket( 3180): Close server socket
I/jxcore-log( 3180): 2015-11-20T10:51:30.624Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:30.645Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:30.646Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 58036 ms, rnd: 4, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): 2015-11-20T10:51:30.659Z SendDataConnector.js: CLIENT is closed
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 10 peers.
I/SS      ( 3180): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3180): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3180): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3180): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3180): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3180): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3180): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3180): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3180): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3180): Peer(10): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pManager( 3180): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/BluetoothRemoteDevices( 2066): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3180): Started service discovery
,I/        ( 3180): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1397","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1397","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1397, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1397, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3180): 2015-11-20T10:51:35.652Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:35.653Z SendDataConnector.js: Connect (retry count 0) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:35.653Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:35.654Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 3180): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2066): aclStateChangeCallback: Device is NULL
,W/bt-btm  ( 2066): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=2
E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: HTC One_M8
,I/ActivityManager(  747): Killing 2681:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  747): failed to open /acct/uid_10003/pid_2681/cgroup.procs: No such file or directory
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 11
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T10:51:40.817Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:40.818Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:40.819Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/        ( 3180): Cleared service requests
,I/        ( 3180): Started peer discovery
,I/jxcore-log( 3180): 2015-11-20T10:51:45.820Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:51:45.821Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 11 peers.
I/SS      ( 3180): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3180): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3180): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3180): Peer(4): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3180): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3180): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3180): Peer(7): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3180): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3180): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3180): Peer(10): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3180): Peer(11): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pManager( 3180): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3180): 2015-11-20T10:51:50.829Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:50.830Z SendDataConnector.js: Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:50.830Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:50.831Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 3180): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 12
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T10:51:56.004Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:51:56.004Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:51:56.005Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/jxcore-log( 3180): 2015-11-20T10:52:01.006Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:01.007Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:06.011Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:06.012Z SendDataConnector.js: Connect (retry count 2) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:06.013Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:06.013Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 3180): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 13
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T10:52:11.185Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:11.185Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:11.185Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:16.186Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:16.187Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [80:01:84:8a:b3:68]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2066): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
E/bt-btif ( 2066): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2066): Entering PendingCommandState State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 2066): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2066): StableState(): Entering Off State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3180): we got incoming connection
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
I/BTListenerThread( 3180): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTListenerThread( 3180): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 3180): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2083"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3180): MESSAGE_WRITE 77 bytes.
I/HS      ( 3180): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT2083
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT2083
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BTConnectedThread
I/BtConnectorHelper( 3180): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3180): --DoOneRunRound started
,I/BtToRequestSocket( 3180): LocalHost address: localhost/127.0.0.1, port: 42499
,I/jxcore-log( 3180): 2015-11-20T10:52:19.765Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): --DoOneRunRound ended
,I/jxcore-log( 3180): 2015-11-20T10:52:20.167Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:20.179Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:20.182Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:20.190Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:20.230Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:20.238Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:20.245Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:20.283Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:20.288Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:20.326Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:20.337Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:20.375Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:20.382Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:20.391Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:20.404Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:20.434Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:20.449Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:20.485Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:20.497Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:20.535Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:20.573Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): invalid rfc slot id: 7
,I/BtToSocketBase( 3180): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT2083
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3180): 2015-11-20T10:52:20.628Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:20.638Z SendDataTCPServer.js: TCP/IP server is close
I/jxcore-log( 3180): 
,W/bt-rfcomm( 2066): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
W/bt-rfcomm( 2066): RFCOMM_DisconnectInd LCID:0x43
,I/jxcore-log( 3180): 2015-11-20T10:52:21.190Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:21.191Z SendDataConnector.js: Connect (retry count 3) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:21.195Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:21.198Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 3180): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: HTC Desire 820
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2066): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 2066): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2066): Entering PendingCommandState State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2066): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2066): StableState(): Entering Off State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3180): we got incoming connection
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
I/BTListenerThread( 3180): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTListenerThread( 3180): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3180): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7533","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3180): MESSAGE_WRITE 77 bytes.
I/HS      ( 3180): Incoming connection Hand Shake finished for : samsung-SM-N910C_PT7533
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : true, samsung-SM-N910C_PT7533
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BTConnectedThread
I/BtConnectorHelper( 3180): Server socket is using : 0, and is now connected.
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3180): --DoOneRunRound started
,I/BtToRequestSocket( 3180): LocalHost address: localhost/127.0.0.1, port: 42499
I/BtToRequestSocket( 3180): --DoOneRunRound ended
,I/jxcore-log( 3180): 2015-11-20T10:52:40.164Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:40.620Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:40.662Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:40.667Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:40.699Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:40.710Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:40.720Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:40.748Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:40.784Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:40.790Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:40.800Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:40.824Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:40.866Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:40.876Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:40.913Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:40.940Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:40.973Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:40.982Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:41.030Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:41.040Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:41.049Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:41.075Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:41.113Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:41.169Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:41.205Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:41.211Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:41.220Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:41.227Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:41.264Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:41.305Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:41.319Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:41.326Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:41.350Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:41.383Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): invalid rfc slot id: 14
,I/BtToSocketBase( 3180): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT7533
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT7533
I/BtToSocketBase( 3180): Close bt in
I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,W/bt-rfcomm( 2066): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
,W/bt-rfcomm( 2066): RFCOMM_DisconnectInd LCID:0x46
,I/BtToSocketBase( 3180): Close bt in
I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,I/jxcore-log( 3180): 2015-11-20T10:52:41.503Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:41.504Z SendDataTCPServer.js: TCP/IP server is close
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2066): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2066): process_service_search_attr_rsp
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 2066): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1
E/bt-btif ( 2066): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2066): Entering PendingCommandState State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 0
,D/BluetoothAdapterProperties( 2066): Failed to remove device: B4:CE:F6:AB:A4:6A
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2066): StableState(): Entering Off State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=0
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3180): Starting to Handshake
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3180): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTConnectToThread( 3180): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 3180): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT1268"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3180): HandshakeOk : HTC-HTC Desire 820_PT1268
I/HS      ( 3180): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT1268
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT1268
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3180): mHTTPPort  set to : 46872
I/BtConnectorHelper( 3180): Request socket is using : 46872
I/BtToRequestSocket( 3180): Now accepting connections
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=1
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/BtConnectorHelper( 3180): Calling ConnectionStatusUpdate with port :46872
,I/jxcore-log( 3180): 2015-11-20T10:52:43.746Z SendDataConnector.js: CLIENT connected to 46872, error: null
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:43.747Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): incoming data from: /127.0.0.1, port: 46872
I/BtToRequestSocket( 3180): Set local streams
I/BtToRequestSocket( 3180): rin ended ---------------------------;
,I/jxcore-log( 3180): 2015-11-20T10:52:43.767Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:43.840Z SendDataConnector.js: resetDataTimeout called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:44.061Z SendDataConnector.js: resetDataTimeout called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:44.061Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:44.202Z SendDataConnector.js: resetDataTimeout called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:44.204Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:44.243Z SendDataConnector.js: resetDataTimeout called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:44.244Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3180): 
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
E/bt-btif ( 2066): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2066): Entering PendingCommandState State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,I/jxcore-log( 3180): 2015-11-20T10:52:44.368Z SendDataConnector.js: resetDataTimeout called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:44.370Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:44.455Z SendDataConnector.js: resetDataTimeout called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:44.456Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:44.533Z SendDataConnector.js: resetDataTimeout called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:44.535Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:44.597Z SendDataConnector.js: resetDataTimeout called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:44.598Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3180): 
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,D/BluetoothAdapterProperties( 2066): Failed to remove device: F8:CF:C5:D9:E5:61
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2066): StableState(): Entering Off State
,E/BluetoothEventManager( 2659): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,I/jxcore-log( 3180): 2015-11-20T10:52:44.684Z SendDataConnector.js: resetDataTimeout called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:44.685Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:44.793Z SendDataConnector.js: resetDataTimeout called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:44.793Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:44.817Z SendDataConnector.js: resetDataTimeout called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:44.817Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:44.817Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:44.817Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:44.817Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3180): 
I/BtConnectorHelper( 3180): Disconnect outgoing peer: B4:CE:F6:AB:A4:6A
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
I/BtToRequestSocket( 3180): Close server socket
,I/jxcore-log( 3180): 2015-11-20T10:52:44.822Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:44.826Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:44.826Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 74176 ms, rnd: 4, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): 2015-11-20T10:52:44.829Z SendDataConnector.js: CLIENT is closed
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3180): we got incoming connection
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
I/BTListenerThread( 3180): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Note4-1
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=0
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3180): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3180): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8419","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3180): MESSAGE_WRITE 77 bytes.
I/HS      ( 3180): Incoming connection Hand Shake finished for : motorola-Nexus 6_PT8419
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : true, motorola-Nexus 6_PT8419
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BTConnectedThread
I/BtConnectorHelper( 3180): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3180): --DoOneRunRound started
,I/BtToRequestSocket( 3180): LocalHost address: localhost/127.0.0.1, port: 42499
,I/jxcore-log( 3180): 2015-11-20T10:52:45.527Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): --DoOneRunRound ended
,I/jxcore-log( 3180): 2015-11-20T10:52:45.934Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:45.939Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:45.959Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.014Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.044Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.050Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.060Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.081Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.115Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.130Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.164Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.178Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.182Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.217Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.245Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.285Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.296Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.337Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.414Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.443Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.450Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.458Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.469Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.495Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.537Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.544Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.572Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.603Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.616Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.626Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.663Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.676Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.717Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.769Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:46.798Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): invalid rfc slot id: 16
,I/BtToSocketBase( 3180): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :motorola-Nexus 6_PT8419
,I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :motorola-Nexus 6_PT8419
I/BtToSocketBase( 3180): Close bt in
I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,I/jxcore-log( 3180): 2015-11-20T10:52:46.906Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:46.907Z SendDataTCPServer.js: TCP/IP server is close
I/jxcore-log( 3180): 
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=1
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2066): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 2066): RFCOMM_DisconnectInd LCID:0x4a
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=0
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: HTC Desire 820
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3180): 2015-11-20T10:52:49.828Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:49.829Z SendDataConnector.js: Connect (retry count 0) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:49.830Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:49.830Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: F8:95:C7:87:3C:51, name: null
,I/        ( 3180): Connecting to null, at F8:95:C7:87:3C:51
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3180): Found 6 peers.
I/SS      ( 3180): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3180): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3180): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3180): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3180): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3180): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3180): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=1
W/bt-btif ( 2066): bta_dm_check_av:0
W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3180): Started service discovery
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2066): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 2066): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2066): Entering PendingCommandState State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Nexus 6
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 2066): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2066): StableState(): Entering Off State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3180): we got incoming connection
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3180): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTListenerThread( 3180): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3180): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5843"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3180): MESSAGE_WRITE 77 bytes.
I/HS      ( 3180): Incoming connection Hand Shake finished for : motorola-XT1039_PT5843
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : true, motorola-XT1039_PT5843
,I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3180): Creating BTConnectedThread
,I/BtConnectorHelper( 3180): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3180): --DoOneRunRound started
,I/jxcore-log( 3180): 2015-11-20T10:52:52.737Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): LocalHost address: localhost/127.0.0.1, port: 42499
I/BtToRequestSocket( 3180): --DoOneRunRound ended
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
E/BluetoothRemoteDevices( 2066): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3180): 2015-11-20T10:52:53.157Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3180): 
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e51b34 rs_disc_pending=1
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3180): 2015-11-20T10:52:53.226Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:53.232Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:53.241Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:53.250Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3180): 
,W/bt-sdp  ( 2066): process_service_search_attr_rsp
,I/jxcore-log( 3180): 2015-11-20T10:52:53.326Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:53.363Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:53.395Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:53.436Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:53.557Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3180): 
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2066): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2066): Entering PendingCommandState State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/jxcore-log( 3180): 2015-11-20T10:52:53.676Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:53.684Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:53.690Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:53.763Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:53.771Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3180): 
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2066): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2066): StableState(): Entering Off State
,I/jxcore-log( 3180): 2015-11-20T10:52:53.829Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3180): 
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/jxcore-log( 3180): 2015-11-20T10:52:53.842Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:53.848Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:53.882Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:53.898Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:53.926Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:53.932Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:53.942Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:53.982Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:54.006Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:54.063Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:54.089Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:54.123Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:54.133Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:54.138Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:54.523Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:54.612Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3180): 
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e51cfc rs_disc_pending=0
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3180): 2015-11-20T10:52:54.917Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:54.974Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:54.987Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:55.002Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:55.035Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:55.064Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3180): 
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e51b34 rs_disc_pending=0
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3180): 2015-11-20T10:52:55.111Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:55.146Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3180): Starting to Handshake
,I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3180): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTConnectToThread( 3180): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3180): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4879","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3180): HandshakeOk : LGE-LG-H815_PT4879
I/HS      ( 3180): Hand Shake finished outgoing for : LGE-LG-H815_PT4879
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : false, LGE-LG-H815_PT4879
,I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3180): mHTTPPort  set to : 53621
I/BtConnectorHelper( 3180): Request socket is using : 53621
I/BtToRequestSocket( 3180): Now accepting connections
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e51cfc rs_disc_pending=1
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/BtConnectorHelper( 3180): Calling ConnectionStatusUpdate with port :53621
I/jxcore-log( 3180): 2015-11-20T10:52:55.543Z SendDataConnector.js: CLIENT connected to 53621, error: null
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:55.543Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): incoming data from: /127.0.0.1, port: 53621
I/BtToRequestSocket( 3180): Set local streams
I/BtToRequestSocket( 3180): rin ended ---------------------------;
,I/jxcore-log( 3180): 2015-11-20T10:52:55.565Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): invalid rfc slot id: 17
,I/BtToSocketBase( 3180): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT5843
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT5843
I/BtToSocketBase( 3180): Close bt in
I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,I/jxcore-log( 3180): 2015-11-20T10:52:55.624Z SendDataConnector.js: resetDataTimeout called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:55.630Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:55.630Z SendDataTCPServer.js: TCP/IP server is close
I/jxcore-log( 3180): 
,W/bt-rfcomm( 2066): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
W/bt-rfcomm( 2066): RFCOMM_DisconnectInd LCID:0x4e
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e51b34 rs_disc_pending=1
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3180): 2015-11-20T10:52:56.513Z SendDataConnector.js: resetDataTimeout called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:56.514Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:56.598Z SendDataConnector.js: resetDataTimeout called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:56.600Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:56.703Z SendDataConnector.js: resetDataTimeout called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:56.704Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:56.857Z SendDataConnector.js: resetDataTimeout called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:56.858Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:56.885Z SendDataConnector.js: resetDataTimeout called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:56.886Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3180): 
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e51cfc rs_disc_pending=0
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3180): 2015-11-20T10:52:57.050Z SendDataConnector.js: resetDataTimeout called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:57.055Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3180): 
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e51b34 rs_disc_pending=0
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3180): 2015-11-20T10:52:58.829Z SendDataConnector.js: resetDataTimeout called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:52:58.830Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3180): 
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: XT1039
,I/jxcore-log( 3180): 2015-11-20T10:52:59.594Z SendDataConnector.js: resetDataTimeout called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:52:59.594Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3180): 2015-11-20T10:53:00.134Z SendDataConnector.js: resetDataTimeout called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:00.136Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:00.183Z SendDataConnector.js: resetDataTimeout called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:00.184Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:00.185Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:00.185Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:00.186Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3180): 
I/BtConnectorHelper( 3180): Disconnect outgoing peer: F8:95:C7:87:3C:51
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
,I/BtToSocketBase( 3180): Close bt in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
I/BtToRequestSocket( 3180): Close server socket
,I/jxcore-log( 3180): 2015-11-20T10:53:00.221Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:00.248Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:00.248Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3180): 
I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 15396 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): 2015-11-20T10:53:00.259Z SendDataConnector.js: CLIENT is closed
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3180): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6801","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6801","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT6801, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT6801, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: G4-1
,I/jxcore-log( 3180): 2015-11-20T10:53:05.253Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:05.254Z SendDataConnector.js: Connect (retry count 0) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:05.255Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:05.255Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: E0:DB:10:1F:C9:5E, name: Note3-1
,I/        ( 3180): Connecting to Note3-1, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [e0:db:10:1f:c9:5e]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Note3-1
,W/bt-sdp  ( 2066): process_service_search_attr_rsp
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3180): Starting to Handshake
,I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3180): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTConnectToThread( 3180): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3180): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1397","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3180): HandshakeOk : samsung-SM-N9005_PT1397
I/HS      ( 3180): Hand Shake finished outgoing for : samsung-SM-N9005_PT1397
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : false, samsung-SM-N9005_PT1397
,I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3180): mHTTPPort  set to : 36327
,I/BtConnectorHelper( 3180): Request socket is using : 36327
I/BtToRequestSocket( 3180): Now accepting connections
,I/BtConnectorHelper( 3180): Calling ConnectionStatusUpdate with port :36327
I/jxcore-log( 3180): 2015-11-20T10:53:06.629Z SendDataConnector.js: CLIENT connected to 36327, error: null
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:06.630Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): incoming data from: /127.0.0.1, port: 36327
I/BtToRequestSocket( 3180): Set local streams
,I/BtToRequestSocket( 3180): rin ended ---------------------------;
,I/jxcore-log( 3180): 2015-11-20T10:53:06.653Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:06.717Z SendDataConnector.js: resetDataTimeout called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:06.807Z SendDataConnector.js: resetDataTimeout called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:06.808Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:06.892Z SendDataConnector.js: resetDataTimeout called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:06.892Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:07.012Z SendDataConnector.js: resetDataTimeout called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:07.013Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:07.061Z SendDataConnector.js: resetDataTimeout called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:07.064Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:07.108Z SendDataConnector.js: resetDataTimeout called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:07.110Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:07.152Z SendDataConnector.js: resetDataTimeout called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:07.153Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:07.272Z SendDataConnector.js: resetDataTimeout called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:07.274Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:07.330Z SendDataConnector.js: resetDataTimeout called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:07.334Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:07.405Z SendDataConnector.js: resetDataTimeout called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:07.407Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:07.454Z SendDataConnector.js: resetDataTimeout called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:07.455Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:07.456Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:07.457Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:07.457Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3180): 
I/BtConnectorHelper( 3180): Disconnect outgoing peer: E0:DB:10:1F:C9:5E
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
I/BtToRequestSocket( 3180): Close server socket
,I/jxcore-log( 3180): 2015-11-20T10:53:07.481Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:07.507Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:07.507Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3180): 
I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 7238 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): 2015-11-20T10:53:07.510Z SendDataConnector.js: CLIENT is closed
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Note3-1
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 6 peers.
I/SS      ( 3180): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3180): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3180): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3180): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3180): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3180): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3180): Ignored { when=-6ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3180): 2015-11-20T10:53:12.512Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:12.513Z SendDataConnector.js: Connect (retry count 0) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:12.515Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:12.516Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3180): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2066): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2066): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2066): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2066): Entering PendingCommandState State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2066): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2066): StableState(): Entering Off State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3180): Starting to Handshake
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3180): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTConnectToThread( 3180): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3180): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9856","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3180): HandshakeOk : LGE-LG-D722_PT9856
I/HS      ( 3180): Hand Shake finished outgoing for : LGE-LG-D722_PT9856
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : false, LGE-LG-D722_PT9856
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3180): mHTTPPort  set to : 45469
I/BtConnectorHelper( 3180): Request socket is using : 45469
I/BtToRequestSocket( 3180): Now accepting connections
,I/BtConnectorHelper( 3180): Calling ConnectionStatusUpdate with port :45469
,I/jxcore-log( 3180): 2015-11-20T10:53:14.025Z SendDataConnector.js: CLIENT connected to 45469, error: null
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:14.026Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): incoming data from: /127.0.0.1, port: 45469
I/BtToRequestSocket( 3180): Set local streams
I/BtToRequestSocket( 3180): rin ended ---------------------------;
,I/jxcore-log( 3180): 2015-11-20T10:53:14.062Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:14.110Z SendDataConnector.js: resetDataTimeout called with peer F8:95:C7:87:85:54
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:14.358Z SendDataConnector.js: resetDataTimeout called with peer F8:95:C7:87:85:54
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:14.360Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:14.510Z SendDataConnector.js: resetDataTimeout called with peer F8:95:C7:87:85:54
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:14.511Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:14.597Z SendDataConnector.js: resetDataTimeout called with peer F8:95:C7:87:85:54
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:14.598Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:14.790Z SendDataConnector.js: resetDataTimeout called with peer F8:95:C7:87:85:54
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:14.794Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:15.184Z SendDataConnector.js: resetDataTimeout called with peer F8:95:C7:87:85:54
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:15.185Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:15.383Z SendDataConnector.js: resetDataTimeout called with peer F8:95:C7:87:85:54
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:15.384Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:15.463Z SendDataConnector.js: resetDataTimeout called with peer F8:95:C7:87:85:54
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:15.464Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:15.681Z SendDataConnector.js: resetDataTimeout called with peer F8:95:C7:87:85:54
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:15.682Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:15.883Z SendDataConnector.js: resetDataTimeout called with peer F8:95:C7:87:85:54
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:15.884Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:15.927Z SendDataConnector.js: resetDataTimeout called with peer F8:95:C7:87:85:54
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:15.928Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:15.929Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:15.929Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:15.930Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3180): 
,I/BtConnectorHelper( 3180): Disconnect outgoing peer: F8:95:C7:87:85:54
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
,I/BtToSocketBase( 3180): Close bt in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
I/BtToRequestSocket( 3180): Close server socket
I/jxcore-log( 3180): 2015-11-20T10:53:15.969Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:15.997Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:15.997Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3180): 
I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 8463 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): 2015-11-20T10:53:16.003Z SendDataConnector.js: CLIENT is closed
I/jxcore-log( 3180): 
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: G3s-1
,I/jxcore-log( 3180): 2015-11-20T10:53:21.000Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:21.001Z SendDataConnector.js: Connect (retry count 0) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:21.006Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:21.008Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 3180): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 22
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T10:53:26.187Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:26.188Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:26.189Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 3180): 2015-11-20T10:53:31.190Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:31.191Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3180): 2015-11-20T10:53:36.199Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:36.200Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:36.200Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:36.201Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 3180): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2066): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2066): process_service_search_attr_rsp
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 2066): check_cod: remote_cod = 0x5a020c
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2066): Entering PendingCommandState State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2066): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2066): StableState(): Entering Off State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3180): Starting to Handshake
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3180): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectToThread( 3180): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 3180): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT7166","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3180): HandshakeOk : motorola-XT1072_PT7166
I/HS      ( 3180): Hand Shake finished outgoing for : motorola-XT1072_PT7166
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : false, motorola-XT1072_PT7166
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3180): mHTTPPort  set to : 51734
,I/BtConnectorHelper( 3180): Request socket is using : 51734
I/BtToRequestSocket( 3180): Now accepting connections
,I/BtConnectorHelper( 3180): Calling ConnectionStatusUpdate with port :51734
I/jxcore-log( 3180): 2015-11-20T10:53:38.128Z SendDataConnector.js: CLIENT connected to 51734, error: null
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:38.129Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): incoming data from: /127.0.0.1, port: 51734
I/BtToRequestSocket( 3180): Set local streams
I/BtToRequestSocket( 3180): rin ended ---------------------------;
,I/jxcore-log( 3180): 2015-11-20T10:53:38.150Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:38.200Z SendDataConnector.js: resetDataTimeout called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3180): 2015-11-20T10:53:38.531Z SendDataConnector.js: resetDataTimeout called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:38.536Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18767
,I/jxcore-log( 3180): 2015-11-20T10:53:38.597Z SendDataConnector.js: resetDataTimeout called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:38.599Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:38.672Z SendDataConnector.js: resetDataTimeout called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:38.674Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8867
,I/jxcore-log( 3180): 2015-11-20T10:53:38.916Z SendDataConnector.js: resetDataTimeout called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:38.917Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:39.010Z SendDataConnector.js: resetDataTimeout called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:39.011Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3180): 
,I/        ( 3180): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9856","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9856","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9856, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9856, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 3180): 2015-11-20T10:53:39.077Z SendDataConnector.js: resetDataTimeout called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:39.078Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3180): 2015-11-20T10:53:39.304Z SendDataConnector.js: resetDataTimeout called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:39.305Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:39.436Z SendDataConnector.js: resetDataTimeout called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:39.437Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:39.446Z SendDataConnector.js: resetDataTimeout called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:39.447Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:39.588Z SendDataConnector.js: resetDataTimeout called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:39.590Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:39.591Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:39.591Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:39.599Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3180): 
,I/BtConnectorHelper( 3180): Disconnect outgoing peer: 44:80:EB:7B:5A:05
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3180): Close LocalOutputStream
,I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
I/BtToRequestSocket( 3180): Close server socket
I/jxcore-log( 3180): 2015-11-20T10:53:39.629Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:39.649Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:39.649Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3180): 
I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 23633 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 3180): 2015-11-20T10:53:39.650Z SendDataConnector.js: CLIENT is closed
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: XT1072
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3180): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT9545","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT9545","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT9545, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT9545, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3180): 2015-11-20T10:53:44.652Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:44.653Z SendDataConnector.js: Connect (retry count 0) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:44.653Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:44.654Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 3180): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [e0:db:10:14:e2:c0]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 2066): process_service_search_attr_rsp
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3180): Starting to Handshake
,I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3180): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTConnectToThread( 3180): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3180): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7533","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3180): HandshakeOk : samsung-SM-N910C_PT7533
I/HS      ( 3180): Hand Shake finished outgoing for : samsung-SM-N910C_PT7533
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : false, samsung-SM-N910C_PT7533
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3180): mHTTPPort  set to : 59777
,I/BtConnectorHelper( 3180): Request socket is using : 59777
I/BtToRequestSocket( 3180): Now accepting connections
,I/BtConnectorHelper( 3180): Calling ConnectionStatusUpdate with port :59777
I/jxcore-log( 3180): 2015-11-20T10:53:47.843Z SendDataConnector.js: CLIENT connected to 59777, error: null
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:47.844Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): incoming data from: /127.0.0.1, port: 59777
I/BtToRequestSocket( 3180): Set local streams
I/BtToRequestSocket( 3180): rin ended ---------------------------;
,I/jxcore-log( 3180): 2015-11-20T10:53:47.870Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:47.938Z SendDataConnector.js: resetDataTimeout called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:48.025Z SendDataConnector.js: resetDataTimeout called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:48.025Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:48.197Z SendDataConnector.js: resetDataTimeout called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:48.198Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:48.248Z SendDataConnector.js: resetDataTimeout called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:48.250Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:48.304Z SendDataConnector.js: resetDataTimeout called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:48.305Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:48.316Z SendDataConnector.js: resetDataTimeout called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:48.318Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:48.326Z SendDataConnector.js: resetDataTimeout called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:48.331Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:48.379Z SendDataConnector.js: resetDataTimeout called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:48.380Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:48.401Z SendDataConnector.js: resetDataTimeout called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:48.405Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:48.438Z SendDataConnector.js: resetDataTimeout called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:48.439Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:48.440Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:48.440Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:48.441Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3180): 
,I/BtConnectorHelper( 3180): Disconnect outgoing peer: E0:DB:10:14:E2:C0
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
,I/BtToSocketBase( 3180): Close bt in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
I/BtToRequestSocket( 3180): Close server socket
I/jxcore-log( 3180): 2015-11-20T10:53:48.472Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:48.498Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:48.498Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 8824 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): 2015-11-20T10:53:48.500Z SendDataConnector.js: CLIENT is closed
I/jxcore-log( 3180): 
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Note4-1
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3180): 2015-11-20T10:53:53.500Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:53.501Z SendDataConnector.js: Connect (retry count 0) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:53.505Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:53:53.509Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 11 peers.
I/SS      ( 3180): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3180): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3180): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3180): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3180): Peer(5): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3180): Peer(6): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3180): Peer(7): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3180): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3180): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3180): Peer(10): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3180): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3180): Started service discovery
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 25
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T10:53:58.688Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:58.689Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:53:58.690Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:03.693Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:03.694Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:08.697Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:08.698Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:08.698Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:08.699Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [44:80:eb:7b:5a:05]: 7, f, 2205
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: XT1072
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3180): we got incoming connection
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
I/BTListenerThread( 3180): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTListenerThread( 3180): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3180): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT7166","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3180): MESSAGE_WRITE 77 bytes.
I/HS      ( 3180): Incoming connection Hand Shake finished for : motorola-XT1072_PT7166
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : true, motorola-XT1072_PT7166
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BTConnectedThread
I/BtConnectorHelper( 3180): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3180): --DoOneRunRound started
,I/jxcore-log( 3180): 2015-11-20T10:54:12.097Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): LocalHost address: localhost/127.0.0.1, port: 42499
I/BtToRequestSocket( 3180): --DoOneRunRound ended
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3180): 2015-11-20T10:54:13.247Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:13.290Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:13.304Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:13.319Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:13.331Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:13.342Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:13.375Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:13.383Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:13.393Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:13.427Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:13.774Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3180): 
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 26
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T10:54:13.874Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:13.874Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:13.874Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:13.953Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:13.959Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:14.278Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:14.290Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:14.379Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:14.672Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:14.718Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:14.855Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:14.880Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:14.990Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:15.135Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:15.481Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:15.550Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:15.581Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:15.643Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:15.777Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:15.835Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:16.135Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:16.175Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:16.352Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:16.654Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:18.323Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:18.332Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:18.428Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:18.876Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:18.876Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:19.083Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:19.125Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2066): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 2066): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2066): Entering PendingCommandState State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2066): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2066): StableState(): Entering Off State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3180): we got incoming connection
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
I/BTListenerThread( 3180): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTListenerThread( 3180): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3180): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6801","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3180): MESSAGE_WRITE 77 bytes.
I/HS      ( 3180): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT6801
I/BtConnectorHelper( 3180): Starting the connected thread incoming : true, samsung-SM-G900F_PT6801
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BTConnectedThread
I/BtConnectorHelper( 3180): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3180): --DoOneRunRound started
,I/jxcore-log( 3180): 2015-11-20T10:54:20.395Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): LocalHost address: localhost/127.0.0.1, port: 42499
,I/BtToRequestSocket( 3180): --DoOneRunRound ended
,I/jxcore-log( 3180): 2015-11-20T10:54:20.478Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:20.689Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:20.798Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:20.871Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:20.884Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:20.925Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:20.991Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.001Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.073Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.127Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.144Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.220Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.227Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3180): 
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e5208c rs_disc_pending=0
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3180): 2015-11-20T10:54:21.302Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.333Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.344Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.408Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.414Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): invalid rfc slot id: 19
,I/BtToSocketBase( 3180): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT7166
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3180): 2015-11-20T10:54:21.495Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.496Z SendDataTCPServer.js: TCP/IP server is close
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.517Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.575Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.719Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.722Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.730Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.767Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3180): 
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e5208c rs_disc_pending=1
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3180): 2015-11-20T10:54:21.784Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.794Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3180): 
,W/bt-rfcomm( 2066): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
W/bt-rfcomm( 2066): RFCOMM_DisconnectInd LCID:0x4f
,I/jxcore-log( 3180): 2015-11-20T10:54:21.826Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.833Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.843Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.875Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.905Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.919Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.956Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.968Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:21.977Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:22.013Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:22.027Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): invalid rfc slot id: 27
,I/BtToSocketBase( 3180): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT6801
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
,I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT6801
I/BtToSocketBase( 3180): Close bt in
I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,I/BtToSocketBase( 3180): Close bt in
I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,I/jxcore-log( 3180): 2015-11-20T10:54:22.224Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:22.231Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:22.237Z SendDataTCPServer.js: TCP/IP server is close
I/jxcore-log( 3180): 
,W/bt-rfcomm( 2066): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
W/bt-rfcomm( 2066): RFCOMM_DisconnectInd LCID:0x4e
,I/jxcore-log( 3180): 2015-11-20T10:54:23.881Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:23.883Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:23.884Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:23.884Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: XT1072
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: S5-1
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 29
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T10:54:29.063Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:29.065Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:29.065Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2066): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 2066): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2066): Entering PendingCommandState State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2066): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2066): StableState(): Entering Off State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3180): we got incoming connection
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
I/BTListenerThread( 3180): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTListenerThread( 3180): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3180): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3840","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3180): MESSAGE_WRITE 77 bytes.
I/HS      ( 3180): Incoming connection Hand Shake finished for : LGE-LG-D855_PT3840
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : true, LGE-LG-D855_PT3840
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BTConnectedThread
I/BtConnectorHelper( 3180): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3180): --DoOneRunRound started
,I/BtToRequestSocket( 3180): LocalHost address: localhost/127.0.0.1, port: 42499
,I/jxcore-log( 3180): 2015-11-20T10:54:29.522Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): --DoOneRunRound ended
,I/jxcore-log( 3180): 2015-11-20T10:54:29.956Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:29.966Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:29.975Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:29.984Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:30.023Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:30.051Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:30.059Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:30.067Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:30.106Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:30.120Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:30.145Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:30.183Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:30.203Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:30.245Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:30.260Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:30.297Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:30.306Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:30.316Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:30.353Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:30.361Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:30.370Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:30.382Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:30.414Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): invalid rfc slot id: 28
,I/BtToSocketBase( 3180): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT3840
I/BtToSocketBase( 3180): Stop ReceivingThread
,I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT3840
I/BtToSocketBase( 3180): Close bt in
I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,I/jxcore-log( 3180): 2015-11-20T10:54:30.555Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3180): 
,W/bt-rfcomm( 2066): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,W/bt-rfcomm( 2066): RFCOMM_DisconnectInd LCID:0x43
,I/jxcore-log( 3180): 2015-11-20T10:54:30.556Z SendDataTCPServer.js: TCP/IP server is close
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:34.066Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:34.067Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: G3-1
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3180): 2015-11-20T10:54:39.071Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:39.072Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:39.072Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:39.073Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [f8:95:c7:87:85:54]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: G3s-1
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2066): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2066): Entering PendingCommandState State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2066): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 2066): StableState(): Entering Off State
,E/BluetoothEventManager( 2659): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 31
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T10:54:44.242Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:44.242Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:44.243Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3180): we got incoming connection
,I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
I/BTListenerThread( 3180): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
I/BTListenerThread( 3180): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3180): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9856","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3180): MESSAGE_WRITE 77 bytes.
I/HS      ( 3180): Incoming connection Hand Shake finished for : LGE-LG-D722_PT9856
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : true, LGE-LG-D722_PT9856
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BTConnectedThread
I/BtConnectorHelper( 3180): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3180): --DoOneRunRound started
,I/jxcore-log( 3180): 2015-11-20T10:54:44.406Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): LocalHost address: localhost/127.0.0.1, port: 42499
I/BtToRequestSocket( 3180): --DoOneRunRound ended
,I/jxcore-log( 3180): 2015-11-20T10:54:44.796Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:44.809Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:44.839Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:44.847Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:44.859Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:44.892Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:44.895Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:44.932Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:44.955Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:44.963Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:44.992Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:44.997Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:45.000Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:45.032Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:45.038Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:45.041Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:45.045Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:45.048Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:45.084Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:45.093Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:54:45.122Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): invalid rfc slot id: 30
,I/BtToSocketBase( 3180): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT9856
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT9856
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close bt in
I/BtToSocketBase( 3180): Close bt out
,I/BtToSocketBase( 3180): Close bt socket
,W/bt-rfcomm( 2066): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 2066): RFCOMM_DisconnectInd LCID:0x42
,I/jxcore-log( 3180): 2015-11-20T10:54:45.146Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:45.146Z SendDataTCPServer.js: TCP/IP server is close
I/jxcore-log( 3180): 
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: G3s-1
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3180): 2015-11-20T10:54:49.244Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:49.244Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 12 peers.
I/SS      ( 3180): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3180): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3180): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3180): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3180): Peer(5): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3180): Peer(6): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3180): Peer(7): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3180): Peer(8): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3180): Peer(9): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3180): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3180): Peer(11): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3180): Peer(12): S5mini-1 02:f4:6f:30:e0:6d
,I/jxcore-log( 3180): 2015-11-20T10:54:54.255Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:54.256Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:54.257Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:54.257Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
D/WifiP2pManager( 3180): Ignored { when=-13ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3180): Started service discovery
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 33
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T10:54:59.422Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:59.422Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:59.422Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:59.423Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 1
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:59.427Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:54:59.427Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3180): 
I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 70925 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/jxcore-log( 3180): 2015-11-20T10:55:04.430Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:04.431Z SendDataConnector.js: Connect (retry count 0) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:04.431Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:04.435Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 7C:F9:0E:34:8A:A0, name: S5-1
,I/        ( 3180): Connecting to S5-1, at 7C:F9:0E:34:8A:A0
,I/BTConnectToThread( 3180): Starting to connect
,W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [7c:f9:0e:34:8a:a0]: 6, f, 410d
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: S5-1
,W/bt-sdp  ( 2066): process_service_search_attr_rsp
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3180): Starting to Handshake
,I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3180): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTConnectToThread( 3180): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3180): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6801","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3180): HandshakeOk : samsung-SM-G900F_PT6801
I/HS      ( 3180): Hand Shake finished outgoing for : samsung-SM-G900F_PT6801
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : false, samsung-SM-G900F_PT6801
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3180): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3180): mHTTPPort  set to : 39020
I/BtConnectorHelper( 3180): Request socket is using : 39020
,I/BtToRequestSocket( 3180): Now accepting connections
,I/BtConnectorHelper( 3180): Calling ConnectionStatusUpdate with port :39020
I/jxcore-log( 3180): 2015-11-20T10:55:07.314Z SendDataConnector.js: CLIENT connected to 39020, error: null
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:07.315Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): incoming data from: /127.0.0.1, port: 39020
I/BtToRequestSocket( 3180): Set local streams
I/BtToRequestSocket( 3180): rin ended ---------------------------;
,I/jxcore-log( 3180): 2015-11-20T10:55:07.335Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:07.381Z SendDataConnector.js: resetDataTimeout called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:07.763Z SendDataConnector.js: resetDataTimeout called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:07.765Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:07.806Z SendDataConnector.js: resetDataTimeout called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:07.811Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:07.854Z SendDataConnector.js: resetDataTimeout called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:07.855Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:07.873Z SendDataConnector.js: resetDataTimeout called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:07.878Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:07.925Z SendDataConnector.js: resetDataTimeout called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:07.927Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:07.996Z SendDataConnector.js: resetDataTimeout called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:07.997Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:08.007Z SendDataConnector.js: resetDataTimeout called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:08.009Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:08.058Z SendDataConnector.js: resetDataTimeout called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:08.067Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3180): 
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3180): 2015-11-20T10:55:08.515Z SendDataConnector.js: resetDataTimeout called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:08.516Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:08.874Z SendDataConnector.js: resetDataTimeout called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:08.876Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:08.876Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:08.877Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:08.877Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3180): 
I/BtConnectorHelper( 3180): Disconnect outgoing peer: 7C:F9:0E:34:8A:A0
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
I/BtToRequestSocket( 3180): Close server socket
I/jxcore-log( 3180): 2015-11-20T10:55:08.903Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:08.927Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:08.930Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 9477 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): 2015-11-20T10:55:08.938Z SendDataConnector.js: CLIENT is closed
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: S5-1
,I/jxcore-log( 3180): 2015-11-20T10:55:13.939Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:13.939Z SendDataConnector.js: Connect (retry count 0) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:13.940Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:13.940Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 3180): Connecting to null, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2066): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2066): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
E/bt-btif ( 2066): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2066): Entering PendingCommandState State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 2066): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2066): StableState(): Entering Off State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3180): Starting to Handshake
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3180): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTConnectToThread( 3180): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 3180): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT4378","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3180): HandshakeOk : HUAWEI-ALE-L21_PT4378
I/HS      ( 3180): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT4378
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT4378
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3180): mHTTPPort  set to : 35961
I/BtConnectorHelper( 3180): Request socket is using : 35961
I/BtToRequestSocket( 3180): Now accepting connections
,I/BtConnectorHelper( 3180): Calling ConnectionStatusUpdate with port :35961
I/jxcore-log( 3180): 2015-11-20T10:55:18.668Z SendDataConnector.js: CLIENT connected to 35961, error: null
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:18.669Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): incoming data from: /127.0.0.1, port: 35961
I/BtToRequestSocket( 3180): Set local streams
I/BtToRequestSocket( 3180): rin ended ---------------------------;
,I/jxcore-log( 3180): 2015-11-20T10:55:18.690Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:18.749Z SendDataConnector.js: resetDataTimeout called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3180): 2015-11-20T10:55:18.882Z SendDataConnector.js: resetDataTimeout called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:18.882Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:18.946Z SendDataConnector.js: resetDataTimeout called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:18.946Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13817
,I/jxcore-log( 3180): 2015-11-20T10:55:19.099Z SendDataConnector.js: resetDataTimeout called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:19.100Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:19.227Z SendDataConnector.js: resetDataTimeout called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:19.229Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3917
,I/jxcore-log( 3180): 2015-11-20T10:55:19.356Z SendDataConnector.js: resetDataTimeout called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:19.357Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:19.451Z SendDataConnector.js: resetDataTimeout called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:19.454Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:19.484Z SendDataConnector.js: resetDataTimeout called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:19.486Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:19.594Z SendDataConnector.js: resetDataTimeout called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:19.596Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:19.738Z SendDataConnector.js: resetDataTimeout called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:19.739Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:19.924Z SendDataConnector.js: resetDataTimeout called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:19.926Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:19.926Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:19.927Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:19.927Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3180): 
I/BtConnectorHelper( 3180): Disconnect outgoing peer: 58:2A:F7:ED:96:BE
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
I/BtToRequestSocket( 3180): Close server socket
,I/jxcore-log( 3180): 2015-11-20T10:55:19.952Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:19.986Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:19.994Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3180): 
I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 11023 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): 2015-11-20T10:55:20.005Z SendDataConnector.js: CLIENT is closed
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: ALE-L21
,I/jxcore-log( 3180): 2015-11-20T10:55:25.011Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:25.012Z SendDataConnector.js: Connect (retry count 0) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:25.013Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:25.013Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 58:3F:54:73:64:C0, name: G3-1
,I/        ( 3180): Connecting to G3-1, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [58:3f:54:73:64:c0]: 6, 10f, 608
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: G3-1
,W/bt-sdp  ( 2066): process_service_search_attr_rsp
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3180): Starting to Handshake
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3180): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTConnectToThread( 3180): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3180): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3840","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3180): HandshakeOk : LGE-LG-D855_PT3840
I/HS      ( 3180): Hand Shake finished outgoing for : LGE-LG-D855_PT3840
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : false, LGE-LG-D855_PT3840
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BtConnectedRequestSocket
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3180): mHTTPPort  set to : 45899
I/BtConnectorHelper( 3180): Request socket is using : 45899
I/BtToRequestSocket( 3180): Now accepting connections
,I/BtConnectorHelper( 3180): Calling ConnectionStatusUpdate with port :45899
I/jxcore-log( 3180): 2015-11-20T10:55:28.410Z SendDataConnector.js: CLIENT connected to 45899, error: null
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:28.410Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): incoming data from: /127.0.0.1, port: 45899
I/BtToRequestSocket( 3180): Set local streams
I/BtToRequestSocket( 3180): rin ended ---------------------------;
,I/jxcore-log( 3180): 2015-11-20T10:55:28.431Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:28.506Z SendDataConnector.js: resetDataTimeout called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3180): 2015-11-20T10:55:28.590Z SendDataConnector.js: resetDataTimeout called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:28.590Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:28.634Z SendDataConnector.js: resetDataTimeout called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:28.634Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12827
,I/jxcore-log( 3180): 2015-11-20T10:55:28.693Z SendDataConnector.js: resetDataTimeout called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:28.693Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:28.803Z SendDataConnector.js: resetDataTimeout called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:28.804Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3917
,I/jxcore-log( 3180): 2015-11-20T10:55:28.876Z SendDataConnector.js: resetDataTimeout called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:28.877Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:28.955Z SendDataConnector.js: resetDataTimeout called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:28.956Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:29.023Z SendDataConnector.js: resetDataTimeout called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:29.024Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:29.078Z SendDataConnector.js: resetDataTimeout called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:29.079Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:29.149Z SendDataConnector.js: resetDataTimeout called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:29.172Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:29.206Z SendDataConnector.js: resetDataTimeout called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:29.208Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:29.208Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:29.218Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:29.218Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3180): 
,I/BtConnectorHelper( 3180): Disconnect outgoing peer: 58:3F:54:73:64:C0
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
I/BtToRequestSocket( 3180): Close server socket
,I/jxcore-log( 3180): 2015-11-20T10:55:29.223Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:29.227Z SendDataConnector.js: Start called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:29.227Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 9231 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): 2015-11-20T10:55:29.230Z SendDataConnector.js: CLIENT is closed
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: G3-1
,I/jxcore-log( 3180): 2015-11-20T10:55:34.230Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:34.231Z SendDataConnector.js: Connect (retry count 0) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:34.236Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:34.236Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 3180): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 3180): Starting to connect
,W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 2066): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 610c
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Nexus 6
,W/bt-sdp  ( 2066): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
E/bt-btif ( 2066): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2066): Entering PendingCommandState State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,D/BluetoothAdapterProperties( 2066): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2066): StableState(): Entering Off State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e527ac rs_disc_pending=1
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3180): we got incoming connection
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
I/BTListenerThread( 3180): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTListenerThread( 3180): got MESSAGE_READ 76 bytes.
I/BTListenerThread( 3180): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT256"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3180): MESSAGE_WRITE 77 bytes.
I/HS      ( 3180): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT256
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : true, LGE-Nexus 5_PT256
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BTConnectedThread
I/BtConnectorHelper( 3180): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3180): --DoOneRunRound started
,I/jxcore-log( 3180): 2015-11-20T10:55:37.717Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): LocalHost address: localhost/127.0.0.1, port: 42499
,I/BtToRequestSocket( 3180): --DoOneRunRound ended
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2066): invalid rfc slot id: 37
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/BluetoothMapService( 2066): onReceive
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T10:55:38.048Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:38.048Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:38.049Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 3180): 2015-11-20T10:55:38.135Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.147Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.252Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.255Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.295Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.299Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.304Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.342Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.345Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.352Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.406Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.417Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.455Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.521Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.529Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.536Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.544Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.586Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.595Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.634Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.679Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.688Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.712Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.743Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.750Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.756Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.766Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.803Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.810Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.837Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.848Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:38.883Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:39.071Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:39.081Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:39.107Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:39.145Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:39.162Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:39.240Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:39.284Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:39.327Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:39.339Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:39.374Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:39.395Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): invalid rfc slot id: 32
,I/BtToSocketBase( 3180): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT256
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,W/bt-rfcomm( 2066): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
W/bt-rfcomm( 2066): RFCOMM_DisconnectInd LCID:0x43
,I/jxcore-log( 3180): 2015-11-20T10:55:39.487Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:39.488Z SendDataTCPServer.js: TCP/IP server is close
I/jxcore-log( 3180): 
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3180): 2015-11-20T10:55:43.051Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:43.055Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3180): 
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 3180): 2015-11-20T10:55:48.058Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:48.059Z SendDataConnector.js: Connect (retry count 1) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:48.059Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:48.060Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 3180): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [f8:cf:c5:d9:e5:61]: 6, f, 6109
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,W/bt-sdp  ( 2066): process_service_search_attr_rsp
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Nexus 6
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3180): Starting to Handshake
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3180): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTConnectToThread( 3180): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3180): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8419","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3180): HandshakeOk : motorola-Nexus 6_PT8419
I/HS      ( 3180): Hand Shake finished outgoing for : motorola-Nexus 6_PT8419
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : false, motorola-Nexus 6_PT8419
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3180): mHTTPPort  set to : 51930
I/BtConnectorHelper( 3180): Request socket is using : 51930
I/BtToRequestSocket( 3180): Now accepting connections
,I/BtConnectorHelper( 3180): Calling ConnectionStatusUpdate with port :51930
I/jxcore-log( 3180): 2015-11-20T10:55:49.840Z SendDataConnector.js: CLIENT connected to 51930, error: null
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:49.840Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:49.851Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): incoming data from: /127.0.0.1, port: 51930
I/BtToRequestSocket( 3180): Set local streams
I/BtToRequestSocket( 3180): rin ended ---------------------------;
,I/jxcore-log( 3180): 2015-11-20T10:55:49.906Z SendDataConnector.js: resetDataTimeout called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3180): 2015-11-20T10:55:49.974Z SendDataConnector.js: resetDataTimeout called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:49.975Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16787
,I/jxcore-log( 3180): 2015-11-20T10:55:50.028Z SendDataConnector.js: resetDataTimeout called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:50.028Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:50.047Z SendDataConnector.js: resetDataTimeout called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:50.047Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7877
,I/jxcore-log( 3180): 2015-11-20T10:55:50.159Z SendDataConnector.js: resetDataTimeout called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:50.159Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:50.199Z SendDataConnector.js: resetDataTimeout called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:50.199Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:50.248Z SendDataConnector.js: resetDataTimeout called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:50.249Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:50.299Z SendDataConnector.js: resetDataTimeout called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:50.306Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:50.332Z SendDataConnector.js: resetDataTimeout called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:50.334Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:50.377Z SendDataConnector.js: resetDataTimeout called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:50.379Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:50.379Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:50.380Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:50.380Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3180): 
,I/BtConnectorHelper( 3180): Disconnect outgoing peer: F8:CF:C5:D9:E5:61
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
I/BtToRequestSocket( 3180): Close server socket
I/jxcore-log( 3180): 2015-11-20T10:55:50.408Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:50.427Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): bta_jv_rfc_port_to_cb(port_handle:0x1e):jv handle:0x0 not FOUND
,I/jxcore-log( 3180): 2015-11-20T10:55:50.427Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 21182 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): 2015-11-20T10:55:50.440Z SendDataConnector.js: CLIENT is closed
I/jxcore-log( 3180): 
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Nexus 6
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3180): 2015-11-20T10:55:55.440Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:55.441Z SendDataConnector.js: Connect (retry count 0) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:55:55.445Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:55:55.448Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3180): Connecting to null, at 08:EC:A9:50:76:27
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3180): Found 2 peers.
I/SS      ( 3180): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3180): Peer(2): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3180): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 40
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T10:56:00.643Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:56:00.644Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:56:00.645Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/jxcore-log( 3180): 2015-11-20T10:56:05.650Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:56:05.651Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3180): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT230"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT230"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT230, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT230, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3180): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7533","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7533","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT7533, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT7533, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3180): 2015-11-20T10:56:10.658Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:56:10.658Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:56:10.659Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:56:10.659Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3180): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 3 peers.
I/SS      ( 3180): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3180): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3180): Peer(3): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3180): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5843"}, typeCordovap2p._tcp.local.:
,I/        ( 3180): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5843"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5843, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5843, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 6 peers.
I/SS      ( 3180): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3180): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3180): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3180): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3180): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3180): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3180): Started service discovery
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x8  CID 0x47
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 41
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T10:56:35.584Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:56:35.585Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:56:35.585Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:56:40.586Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:56:40.587Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:56:45.590Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:56:45.591Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:56:45.596Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:56:45.599Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3180): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:42, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 42
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T10:56:50.773Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:56:50.773Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:56:50.773Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:56:55.774Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:56:55.775Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [b4:ce:f6:ab:a4:6a]: 7, f, 230f
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3180): we got incoming connection
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
I/BTListenerThread( 3180): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTListenerThread( 3180): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 3180): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT1268"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3180): MESSAGE_WRITE 77 bytes.
I/HS      ( 3180): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT1268
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT1268
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BTConnectedThread
,I/BtConnectorHelper( 3180): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3180): --DoOneRunRound started
,I/BtToRequestSocket( 3180): LocalHost address: localhost/127.0.0.1, port: 42499
I/BtToRequestSocket( 3180): --DoOneRunRound ended
I/jxcore-log( 3180): 2015-11-20T10:57:00.345Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:00.765Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:00.772Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:00.776Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:00.776Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:00.777Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:00.777Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 08:EC:A9:50:76:27, name: null
I/        ( 3180): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3180): 2015-11-20T10:57:00.826Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3180): 
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3180): 2015-11-20T10:57:01.019Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.026Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.038Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.071Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.088Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.129Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.162Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.207Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.323Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.356Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.367Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.444Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.457Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.491Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.498Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.527Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.565Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.607Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.616Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.626Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2066): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3180): 2015-11-20T10:57:01.693Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.699Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.735Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.742Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.768Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.803Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.810Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.817Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.830Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.863Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.890Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.899Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.953Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:01.983Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:02.080Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:02.113Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:02.134Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:02.140Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3180): 
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e52974 rs_disc_pending=1
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2066): invalid rfc slot id: 38
,I/BtToSocketBase( 3180): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT1268
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,W/bt-rfcomm( 2066): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 2066): RFCOMM_DisconnectInd LCID:0x45
,W/bt-sdp  ( 2066): process_service_search_attr_rsp
,I/jxcore-log( 3180): 2015-11-20T10:57:02.292Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:02.300Z SendDataTCPServer.js: TCP/IP server is close
I/jxcore-log( 3180): 
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 2066): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2066): Entering PendingCommandState State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 2066): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2066): StableState(): Entering Off State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e52974 rs_disc_pending=0
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3180): Starting to Handshake
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3180): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e52974 rs_disc_pending=1
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3180): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 3180): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3480","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3180): HandshakeOk : samsung-SM-A300FU_PT3480
,I/HS      ( 3180): Hand Shake finished outgoing for : samsung-SM-A300FU_PT3480
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : false, samsung-SM-A300FU_PT3480
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3180): mHTTPPort  set to : 33917
I/BtConnectorHelper( 3180): Request socket is using : 33917
I/BtToRequestSocket( 3180): Now accepting connections
,I/BtConnectorHelper( 3180): Calling ConnectionStatusUpdate with port :33917
I/jxcore-log( 3180): 2015-11-20T10:57:05.874Z SendDataConnector.js: CLIENT connected to 33917, error: null
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:05.874Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): incoming data from: /127.0.0.1, port: 33917
I/BtToRequestSocket( 3180): Set local streams
I/BtToRequestSocket( 3180): rin ended ---------------------------;
,I/jxcore-log( 3180): 2015-11-20T10:57:05.895Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:05.949Z SendDataConnector.js: resetDataTimeout called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3180): 2015-11-20T10:57:06.144Z SendDataConnector.js: resetDataTimeout called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:06.145Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:06.241Z SendDataConnector.js: resetDataTimeout called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:06.242Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3180): 
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13817
,I/jxcore-log( 3180): 2015-11-20T10:57:06.398Z SendDataConnector.js: resetDataTimeout called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:06.398Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3180): 
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3180): 2015-11-20T10:57:06.486Z SendDataConnector.js: resetDataTimeout called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:06.487Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2927
,I/jxcore-log( 3180): 2015-11-20T10:57:06.577Z SendDataConnector.js: resetDataTimeout called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:06.577Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:06.579Z SendDataConnector.js: resetDataTimeout called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:06.579Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:06.787Z SendDataConnector.js: resetDataTimeout called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:06.788Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:07.034Z SendDataConnector.js: resetDataTimeout called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:07.035Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:07.163Z SendDataConnector.js: resetDataTimeout called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:07.164Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:07.324Z SendDataConnector.js: resetDataTimeout called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:07.325Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:07.325Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:07.326Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:07.326Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3180): 
I/BtConnectorHelper( 3180): Disconnect outgoing peer: 08:EC:A9:50:76:27
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
,I/BtToSocketBase( 3180): Close bt in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
I/BtToRequestSocket( 3180): Close server socket
I/jxcore-log( 3180): 2015-11-20T10:57:07.353Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:07.373Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:07.373Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3180): 
I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 76926 ms, rnd: 4, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 3180): 2015-11-20T10:57:07.379Z SendDataConnector.js: CLIENT is closed
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): bta_jv_rfc_port_to_cb(port_handle:0x7):jv handle:0x0 not FOUND
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e52974 rs_disc_pending=0
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 3180): 2015-11-20T10:57:12.377Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:12.377Z SendDataConnector.js: Connect (retry count 0) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:12.378Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:12.378Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/        ( 3180): Connecting to null, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2066): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2066): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 2066): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2066): Entering PendingCommandState State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2066): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2066): StableState(): Entering Off State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3180): Starting to Handshake
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3180): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTConnectToThread( 3180): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 3180): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT7255","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3180): HandshakeOk : samsung-SM-A500FU_PT7255
I/HS      ( 3180): Hand Shake finished outgoing for : samsung-SM-A500FU_PT7255
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : false, samsung-SM-A500FU_PT7255
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3180): mHTTPPort  set to : 56672
I/BtConnectorHelper( 3180): Request socket is using : 56672
I/BtToRequestSocket( 3180): Now accepting connections
,I/BtConnectorHelper( 3180): Calling ConnectionStatusUpdate with port :56672
I/jxcore-log( 3180): 2015-11-20T10:57:14.667Z SendDataConnector.js: CLIENT connected to 56672, error: null
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:14.667Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:14.669Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): incoming data from: /127.0.0.1, port: 56672
I/BtToRequestSocket( 3180): Set local streams
I/BtToRequestSocket( 3180): rin ended ---------------------------;
,I/jxcore-log( 3180): 2015-11-20T10:57:14.732Z SendDataConnector.js: resetDataTimeout called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3180): 2015-11-20T10:57:14.775Z SendDataConnector.js: resetDataTimeout called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:14.775Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14807
,I/jxcore-log( 3180): 2015-11-20T10:57:14.811Z SendDataConnector.js: resetDataTimeout called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:14.811Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:14.815Z SendDataConnector.js: resetDataTimeout called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:14.815Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7877
,I/jxcore-log( 3180): 2015-11-20T10:57:14.851Z SendDataConnector.js: resetDataTimeout called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:14.852Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3917
,I/jxcore-log( 3180): 2015-11-20T10:57:14.853Z SendDataConnector.js: resetDataTimeout called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:14.853Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:14.902Z SendDataConnector.js: resetDataTimeout called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:14.902Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:14.950Z SendDataConnector.js: resetDataTimeout called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:14.950Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:14.955Z SendDataConnector.js: resetDataTimeout called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:14.956Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:15.009Z SendDataConnector.js: resetDataTimeout called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:15.010Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:15.059Z SendDataConnector.js: resetDataTimeout called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:15.060Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:15.061Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:15.061Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:15.066Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3180): 
,I/BtConnectorHelper( 3180): Disconnect outgoing peer: 7C:F9:0E:37:96:AB
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
,I/BtToSocketBase( 3180): Close bt in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
I/BtToRequestSocket( 3180): Close server socket
I/jxcore-log( 3180): 2015-11-20T10:57:15.096Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:15.118Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:15.119Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3180): 
I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 7724 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): 2015-11-20T10:57:15.120Z SendDataConnector.js: CLIENT is closed
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3180): we got incoming connection
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
I/BTListenerThread( 3180): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTListenerThread( 3180): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3180): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT7255","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3180): MESSAGE_WRITE 77 bytes.
I/HS      ( 3180): Incoming connection Hand Shake finished for : samsung-SM-A500FU_PT7255
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : true, samsung-SM-A500FU_PT7255
,I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BTConnectedThread
I/BtConnectorHelper( 3180): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3180): --DoOneRunRound started
,I/jxcore-log( 3180): 2015-11-20T10:57:15.943Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): LocalHost address: localhost/127.0.0.1, port: 42499
,I/BtToRequestSocket( 3180): --DoOneRunRound ended
,I/jxcore-log( 3180): 2015-11-20T10:57:16.318Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:16.325Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:16.334Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:16.342Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:16.350Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:16.362Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:16.394Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:16.419Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:16.444Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:16.457Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:16.512Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:16.528Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:16.562Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:16.564Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:16.569Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:16.602Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:16.604Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:16.642Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:16.648Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): invalid rfc slot id: 43
,I/BtToSocketBase( 3180): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT7255
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3180): 2015-11-20T10:57:16.675Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:16.677Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:16.677Z SendDataTCPServer.js: TCP/IP server is close
I/jxcore-log( 3180): 
,W/bt-rfcomm( 2066): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 2066): RFCOMM_DisconnectInd LCID:0x41
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: A5-1
,I/jxcore-log( 3180): 2015-11-20T10:57:20.119Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:20.119Z SendDataConnector.js: Connect (retry count 0) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:20.119Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:20.119Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 3180): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 3180): Starting to connect
,W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [f4:f1:e1:5c:3b:e2]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: XT1039
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [50:2e:6c:ac:21:50]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: HTC One_M8
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3180): we got incoming connection
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
I/BTListenerThread( 3180): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTListenerThread( 3180): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 3180): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT9545","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3180): MESSAGE_WRITE 77 bytes.
I/HS      ( 3180): Incoming connection Hand Shake finished for : HTC-HTC One_M8_PT9545
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : true, HTC-HTC One_M8_PT9545
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BTConnectedThread
,I/BtConnectorHelper( 3180): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3180): --DoOneRunRound started
,I/jxcore-log( 3180): 2015-11-20T10:57:21.002Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): LocalHost address: localhost/127.0.0.1, port: 42499
,I/BtToRequestSocket( 3180): --DoOneRunRound ended
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e51cfc rs_disc_pending=0
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2066): process_service_search_attr_rsp
,I/jxcore-log( 3180): 2015-11-20T10:57:21.435Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.443Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.450Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.488Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.513Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.522Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.532Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.569Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.596Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.603Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.644Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.659Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3180): Starting to Handshake
,I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3180): MESSAGE_WRITE 77 bytes.
,I/jxcore-log( 3180): 2015-11-20T10:57:21.703Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3180): 
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/jxcore-log( 3180): 2015-11-20T10:57:21.740Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.747Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.790Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.802Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.835Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.844Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.871Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.881Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.907Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.946Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.954Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.966Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:21.999Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:22.056Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:22.061Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:22.068Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:22.143Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:22.150Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:22.190Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:22.224Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:22.230Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:22.270Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:22.337Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:22.373Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:22.380Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:22.414Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:22.448Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:22.483Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:22.498Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:22.507Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:22.518Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:22.537Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:22.573Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:22.579Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): invalid rfc slot id: 46
,I/BtToSocketBase( 3180): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT9545
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT9545
I/BtToSocketBase( 3180): Close bt in
I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,W/bt-rfcomm( 2066): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
W/bt-rfcomm( 2066): RFCOMM_DisconnectInd LCID:0x43
,I/jxcore-log( 3180): 2015-11-20T10:57:22.702Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:22.703Z SendDataTCPServer.js: TCP/IP server is close
I/jxcore-log( 3180): 
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=0
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e51cfc rs_disc_pending=1
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3180): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 3180): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5843"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3180): HandshakeOk : motorola-XT1039_PT5843
I/HS      ( 3180): Hand Shake finished outgoing for : motorola-XT1039_PT5843
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : false, motorola-XT1039_PT5843
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3180): mHTTPPort  set to : 55020
I/BtConnectorHelper( 3180): Request socket is using : 55020
I/BtToRequestSocket( 3180): Now accepting connections
,I/BtConnectorHelper( 3180): Calling ConnectionStatusUpdate with port :55020
I/jxcore-log( 3180): 2015-11-20T10:57:25.641Z SendDataConnector.js: CLIENT connected to 55020, error: null
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:25.650Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): incoming data from: /127.0.0.1, port: 55020
I/BtToRequestSocket( 3180): Set local streams
I/BtToRequestSocket( 3180): rin ended ---------------------------;
,I/jxcore-log( 3180): 2015-11-20T10:57:25.668Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:25.710Z SendDataConnector.js: resetDataTimeout called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3180): 2015-11-20T10:57:25.992Z SendDataConnector.js: resetDataTimeout called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:25.994Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:26.040Z SendDataConnector.js: resetDataTimeout called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:26.045Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12827
,I/jxcore-log( 3180): 2015-11-20T10:57:26.129Z SendDataConnector.js: resetDataTimeout called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:26.130Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:26.170Z SendDataConnector.js: resetDataTimeout called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:26.174Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3180): 
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2927
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/jxcore-log( 3180): 2015-11-20T10:57:26.350Z SendDataConnector.js: resetDataTimeout called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:26.354Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3180): 
,I/BluetoothClassifier( 1362): Bluetooth Device Name: HTC One_M8
,I/jxcore-log( 3180): 2015-11-20T10:57:26.420Z SendDataConnector.js: resetDataTimeout called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:26.420Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:26.458Z SendDataConnector.js: resetDataTimeout called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:26.458Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:26.499Z SendDataConnector.js: resetDataTimeout called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:26.499Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3180): 
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3180): 2015-11-20T10:57:26.589Z SendDataConnector.js: resetDataTimeout called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:26.590Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:26.623Z SendDataConnector.js: resetDataTimeout called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:26.624Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:26.624Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:26.625Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:26.625Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3180): 
I/BtConnectorHelper( 3180): Disconnect outgoing peer: F4:F1:E1:5C:3B:E2
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
I/BtToRequestSocket( 3180): Close server socket
I/jxcore-log( 3180): 2015-11-20T10:57:26.639Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:26.655Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:26.656Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 11520 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 3180): 2015-11-20T10:57:26.661Z SendDataConnector.js: CLIENT is closed
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [08:ec:a9:50:76:27]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/GCM     ( 1328): Heartbeat timeout, GCM connection reset -4
,D/ConnectivityService(  747): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  747): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  747): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  747): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  747): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  747): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  747): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 20 Nov 2015 10:57:29 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448017049513], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448017049498]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  747): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  747): Validated
,D/ConnectivityService(  747): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  747): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  747): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
,D/ConnectivityService(  747): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1601): CM callback handler got msg 524290
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e52974 rs_disc_pending=0
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: XT1039
,I/jxcore-log( 3180): 2015-11-20T10:57:31.658Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:31.658Z SendDataConnector.js: Connect (retry count 0) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:31.659Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:31.659Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 34:FC:EF:11:B1:66, name: Nexus 5
,I/        ( 3180): Connecting to Nexus 5, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 3180): Starting to connect
,W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 3 peers.
I/SS      ( 3180): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3180): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3180): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3180): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3180): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3480","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3480","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT3480, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT3480, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 49
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T10:57:41.608Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:41.608Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:41.609Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 4 peers.
I/SS      ( 3180): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3180): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3180): Peer(3): S5-1 ee:1f:72:63:11:86
I/SS      ( 3180): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3180): 2015-11-20T10:57:46.610Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:46.611Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3180): Started service discovery
,I/        ( 3180): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3840","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3840","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT3840, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT3840, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e52974 rs_disc_pending=1
E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/        ( 3180): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9856","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9856","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9856, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9856, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 3180): 2015-11-20T10:57:51.620Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:51.620Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:51.621Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:51.624Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 34:FC:EF:11:B1:66, name: Nexus 5
,I/        ( 3180): Connecting to Nexus 5, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3180): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3480","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3480","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT3480, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT3480, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [34:fc:ef:11:b1:66]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Nexus 5
,W/bt-sdp  ( 2066): process_service_search_attr_rsp
,I/        ( 3180): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2083"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2083"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT2083, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT2083, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3180): Starting to Handshake
,I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3180): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTConnectToThread( 3180): got MESSAGE_READ 76 bytes.
I/BTConnectToThread( 3180): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT256"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3180): HandshakeOk : LGE-Nexus 5_PT256
I/HS      ( 3180): Hand Shake finished outgoing for : LGE-Nexus 5_PT256
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : false, LGE-Nexus 5_PT256
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3180): mHTTPPort  set to : 33491
I/BtConnectorHelper( 3180): Request socket is using : 33491
I/BtToRequestSocket( 3180): Now accepting connections
,I/        ( 3180): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5843"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5843"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5843, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5843, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3180): Calling ConnectionStatusUpdate with port :33491
I/jxcore-log( 3180): 2015-11-20T10:57:53.498Z SendDataConnector.js: CLIENT connected to 33491, error: null
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:53.499Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): incoming data from: /127.0.0.1, port: 33491
I/BtToRequestSocket( 3180): Set local streams
,I/BtToRequestSocket( 3180): rin ended ---------------------------;
,I/jxcore-log( 3180): 2015-11-20T10:57:53.525Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:53.570Z SendDataConnector.js: resetDataTimeout called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3180): 2015-11-20T10:57:53.981Z SendDataConnector.js: resetDataTimeout called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:53.982Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:54.015Z SendDataConnector.js: resetDataTimeout called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:54.016Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13817
,I/jxcore-log( 3180): 2015-11-20T10:57:54.209Z SendDataConnector.js: resetDataTimeout called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:54.210Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:54.341Z SendDataConnector.js: resetDataTimeout called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:54.345Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3180): 
,D/        ( 2066): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3917
,I/jxcore-log( 3180): 2015-11-20T10:57:54.655Z SendDataConnector.js: resetDataTimeout called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:54.656Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:54.731Z SendDataConnector.js: resetDataTimeout called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:54.731Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:54.785Z SendDataConnector.js: resetDataTimeout called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:54.785Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:54.994Z SendDataConnector.js: resetDataTimeout called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:54.995Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3180): 
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3180): 2015-11-20T10:57:56.476Z SendDataConnector.js: resetDataTimeout called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:56.487Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:57:56.693Z SendDataConnector.js: resetDataTimeout called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:56.694Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:56.695Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:56.695Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:56.696Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3180): 
,I/BtConnectorHelper( 3180): Disconnect outgoing peer: 34:FC:EF:11:B1:66
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
I/BtToRequestSocket( 3180): Close server socket
I/jxcore-log( 3180): 2015-11-20T10:57:56.728Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:56.746Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:57:56.746Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3180): 
W/bt-btif ( 2066): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 30073 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 3180): 2015-11-20T10:57:56.758Z SendDataConnector.js: CLIENT is closed
I/jxcore-log( 3180): 
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [08:ec:a9:50:76:27]: 6, f, 6109
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3180): we got incoming connection
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3180): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTListenerThread( 3180): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3180): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3480","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3180): MESSAGE_WRITE 77 bytes.
I/HS      ( 3180): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT3480
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : true, samsung-SM-A300FU_PT3480
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BTConnectedThread
I/BtConnectorHelper( 3180): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3180): --DoOneRunRound started
,I/BtToRequestSocket( 3180): LocalHost address: localhost/127.0.0.1, port: 42499
,I/jxcore-log( 3180): 2015-11-20T10:58:01.458Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): --DoOneRunRound ended
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/jxcore-log( 3180): 2015-11-20T10:58:01.749Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:01.749Z SendDataConnector.js: Connect (retry count 0) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:01.749Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:01.749Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/        ( 3180): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3180): 2015-11-20T10:58:01.926Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3180): 
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e52974 rs_disc_pending=1
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3180): 2015-11-20T10:58:02.159Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:02.165Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:02.222Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:02.236Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:02.265Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:02.423Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:02.544Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:02.552Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:02.559Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e52974 rs_disc_pending=0
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3180): 2015-11-20T10:58:03.449Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:03.483Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:03.547Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:03.556Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:03.621Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:03.634Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:03.663Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:03.713Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:03.739Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:03.746Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:03.805Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:03.845Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:03.898Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:03.906Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:03.913Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:04.057Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:04.149Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:04.157Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:04.163Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:04.236Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:04.248Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3180): 
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3180): 2015-11-20T10:58:04.335Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:04.344Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:04.397Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:04.434Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:04.489Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:04.525Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:04.584Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:04.592Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:04.613Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:04.685Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:04.724Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:04.811Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:04.816Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:04.833Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3180): 
,W/bt-sdp  ( 2066): process_service_search_attr_rsp
,W/bt-btif ( 2066): invalid rfc slot id: 48
,I/BtToSocketBase( 3180): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT3480
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3180): 2015-11-20T10:58:04.948Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:04.948Z SendDataTCPServer.js: TCP/IP server is close
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e52974 rs_disc_pending=1
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2066): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 2066): RFCOMM_DisconnectInd LCID:0x49
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3180): Starting to Handshake
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3180): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3180): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 3180): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2083"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3180): HandshakeOk : HTC-HTC Desire 820_PT2083
I/HS      ( 3180): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT2083
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT2083
,I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3180): mHTTPPort  set to : 45636
I/BtConnectorHelper( 3180): Request socket is using : 45636
I/BtToRequestSocket( 3180): Now accepting connections
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BtConnectorHelper( 3180): Calling ConnectionStatusUpdate with port :45636
I/jxcore-log( 3180): 2015-11-20T10:58:08.078Z SendDataConnector.js: CLIENT connected to 45636, error: null
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:08.079Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): incoming data from: /127.0.0.1, port: 45636
I/BtToRequestSocket( 3180): Set local streams
I/BtToRequestSocket( 3180): rin ended ---------------------------;
,I/jxcore-log( 3180): 2015-11-20T10:58:08.100Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:08.142Z SendDataConnector.js: resetDataTimeout called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3180): 2015-11-20T10:58:08.389Z SendDataConnector.js: resetDataTimeout called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:08.389Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3180): Found 5 peers.
I/SS      ( 3180): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3180): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3180): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3180): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3180): Peer(5): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3180): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3180): 2015-11-20T10:58:09.185Z SendDataConnector.js: resetDataTimeout called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:09.187Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3180): Started service discovery
,I/jxcore-log( 3180): 2015-11-20T10:58:09.985Z SendDataConnector.js: resetDataTimeout called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:09.986Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:10.586Z SendDataConnector.js: resetDataTimeout called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:10.587Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3180): 
,I/        ( 3180): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT256"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT256"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT256, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT256, WifiDirectName: , WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,E/bt-btm  ( 2066): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 2066): bta_dm_check_av:0
,W/bt-btif ( 2066): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3180): 2015-11-20T10:58:12.827Z SendDataConnector.js: resetDataTimeout called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:12.829Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3180): 
,I/        ( 3180): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT7255","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT7255","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT7255, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT7255, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/jxcore-log( 3180): 2015-11-20T10:58:14.411Z SendDataConnector.js: resetDataTimeout called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:14.412Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:14.920Z SendDataConnector.js: resetDataTimeout called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:14.921Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:15.764Z SendDataConnector.js: resetDataTimeout called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:15.765Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:17.196Z SendDataConnector.js: resetDataTimeout called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:17.197Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:18.631Z SendDataConnector.js: resetDataTimeout called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:18.634Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:18.635Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:18.635Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:18.636Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3180): 
,I/BtConnectorHelper( 3180): Disconnect outgoing peer: 80:01:84:8A:B3:68
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
I/BtToRequestSocket( 3180): Close server socket
I/jxcore-log( 3180): 2015-11-20T10:58:18.667Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:18.687Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:18.688Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 21922 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): 2015-11-20T10:58:18.690Z SendDataConnector.js: CLIENT is closed
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3180): 2015-11-20T10:58:23.691Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:23.691Z SendDataConnector.js: Connect (retry count 0) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:23.692Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:23.692Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:53, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 53
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T10:58:28.878Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:28.879Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:28.879Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3180): Found 5 peers.
,I/SS      ( 3180): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3180): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3180): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3180): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3180): Peer(5): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 3180): 2015-11-20T10:58:33.881Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:33.881Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/        ( 3180): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3840","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3840","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT3840, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT3840, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 3180): 2015-11-20T10:58:38.888Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:38.889Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:38.889Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:38.889Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 54
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T10:58:44.064Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:44.064Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:44.065Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [f8:95:c7:87:3c:51]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: G4-1
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,E/bt-btif ( 2066): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2066): Entering PendingCommandState State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2066): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2066): StableState(): Entering Off State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3180): we got incoming connection
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
I/BTListenerThread( 3180): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTListenerThread( 3180): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3180): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4879","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3180): MESSAGE_WRITE 77 bytes.
I/HS      ( 3180): Incoming connection Hand Shake finished for : LGE-LG-H815_PT4879
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : true, LGE-LG-H815_PT4879
I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BTConnectedThread
I/BtConnectorHelper( 3180): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3180): --DoOneRunRound started
,I/BtToRequestSocket( 3180): LocalHost address: localhost/127.0.0.1, port: 42499
I/BtToRequestSocket( 3180): --DoOneRunRound ended
,I/jxcore-log( 3180): 2015-11-20T10:58:47.614Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:47.998Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:48.027Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:48.035Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:48.038Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:48.057Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:48.063Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:48.074Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:48.103Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:48.117Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:48.130Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:48.165Z SendDataTCPServer.js: TCP/IP server has received 34476 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:48.176Z SendDataTCPServer.js: TCP/IP server has received 38436 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:48.217Z SendDataTCPServer.js: TCP/IP server has received 56256 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:48.233Z SendDataTCPServer.js: TCP/IP server has received 60216 bytes of data
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:48.235Z SendDataTCPServer.js: TCP/IP server has received 62196 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:48.242Z SendDataTCPServer.js: TCP/IP server has received 64176 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:48.279Z SendDataTCPServer.js: TCP/IP server has received 78036 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:48.316Z SendDataTCPServer.js: TCP/IP server has received 81996 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:48.355Z SendDataTCPServer.js: TCP/IP server has received 97836 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:48.365Z SendDataTCPServer.js: TCP/IP server has received 99816 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:48.374Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): invalid rfc slot id: 51
,I/BtToSocketBase( 3180): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT4879
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,W/bt-rfcomm( 2066): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
,W/bt-rfcomm( 2066): RFCOMM_DisconnectInd LCID:0x4b
,I/jxcore-log( 3180): 2015-11-20T10:58:48.450Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:48.454Z SendDataTCPServer.js: TCP/IP server is close
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:49.064Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:49.065Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 5 peers.
I/SS      ( 3180): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3180): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3180): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3180): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3180): Peer(5): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: G4-1
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3180): Started service discovery
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3180): 2015-11-20T10:58:54.069Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:54.070Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:54.070Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:58:54.078Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:56, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 56
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T10:58:59.260Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:59.261Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:58:59.267Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:59:04.268Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:59:04.268Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/jxcore-log( 3180): 2015-11-20T10:59:09.274Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:09.275Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:09.275Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:09.276Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:57, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 57
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T10:59:14.446Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:14.447Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:14.447Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:59:19.448Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:19.448Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:59:24.451Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:24.453Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:24.453Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:24.454Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:58, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 58
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T10:59:29.625Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:29.625Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:59:29.626Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:29.627Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 2
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:29.630Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:29.630Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 70939 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): 2015-11-20T10:59:34.632Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:34.633Z SendDataConnector.js: Connect (retry count 0) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:34.633Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:34.634Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:59, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 59
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T10:59:39.818Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:39.819Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:39.820Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:59:44.821Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:44.823Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T10:59:49.826Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:49.827Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:49.828Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:49.828Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:60, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 60
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T10:59:55.001Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:55.001Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T10:59:55.001Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 3 peers.
I/SS      ( 3180): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3180): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3180): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3180): Started service discovery
,I/jxcore-log( 3180): 2015-11-20T11:00:00.002Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:00.003Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3180): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT256"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT256"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT256, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT256, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/jxcore-log( 3180): 2015-11-20T11:00:05.006Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:05.007Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:05.007Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:05.008Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:61, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 61
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T11:00:10.197Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:00:10.197Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:10.198Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3180): Found 3 peers.
I/SS      ( 3180): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3180): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3180): Peer(3): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3180): 2015-11-20T11:00:15.203Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:15.204Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/        ( 3180): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5843"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5843"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5843, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5843, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3180): 2015-11-20T11:00:20.207Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:20.208Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:20.208Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:20.208Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 62
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:00:25.385Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:25.385Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:25.385Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3180): Found 4 peers.
I/SS      ( 3180): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3180): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3180): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3180): Peer(4): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 3180): 2015-11-20T11:00:30.386Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:30.386Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:00:35.389Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:35.390Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:35.390Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:00:35.391Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:63, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 63
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:00:40.573Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:40.573Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:40.573Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:00:40.575Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 3
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:00:40.576Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:40.578Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 70945 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): 2015-11-20T11:00:45.583Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:45.584Z SendDataConnector.js: Connect (retry count 0) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:45.584Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:45.585Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2066): info:x10
,D/        ( 2066): remote version info [58:2a:f7:ed:96:be]: 7, f, 6109
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: ALE-L21
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
E/bt-btif ( 2066): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2066): Entering PendingCommandState State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,I/BluetoothBondStateMachine( 2066): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 2066): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 2066): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2066): StableState(): Entering Off State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:64, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 64
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:00:50.768Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:50.769Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:50.770Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): new conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2066): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3180): we got incoming connection
I/BTHandshakeSocketThread( 3180): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3180): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread started
,I/BTListenerThread( 3180): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 3180): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT4378","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3180): MESSAGE_WRITE 77 bytes.
I/HS      ( 3180): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT4378
I/BTHandshakeSocketThread( 3180): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3180): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT4378
,I/BtToSocketBase( 3180): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3180): Creating BTConnectedThread
,I/BtConnectorHelper( 3180): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3180): --DoOneRunRound started
,I/jxcore-log( 3180): 2015-11-20T11:00:50.909Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3180): 
,I/BtToRequestSocket( 3180): LocalHost address: localhost/127.0.0.1, port: 42499
I/BtToRequestSocket( 3180): --DoOneRunRound ended
,I/jxcore-log( 3180): 2015-11-20T11:00:51.282Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:00:51.289Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:00:51.296Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:00:51.307Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:00:51.316Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:00:51.330Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:00:51.368Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:00:51.387Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:00:51.425Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:00:51.439Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:00:51.473Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:00:51.492Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:00:51.526Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:00:51.540Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:00:51.546Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:00:51.574Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3180): 
,W/bt-btif ( 2066): invalid rfc slot id: 55
,I/BtToSocketBase( 3180): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3180): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT4378
I/BtToSocketBase( 3180): Stop ReceivingThread
I/BtToSocketBase( 3180): Stop SendingThread
I/BtToSocketBase( 3180): Close local in
I/BtToSocketBase( 3180): Close LocalOutputStream
I/BtToSocketBase( 3180): Close localHostSocket
I/BtToSocketBase( 3180): Close bt in
I/BtToSocketBase( 3180): Close bt out
I/BtToSocketBase( 3180): Close bt socket
,I/BtToSocketBase( 3180): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3180): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,W/bt-rfcomm( 2066): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 2066): RFCOMM_DisconnectInd LCID:0x49
,I/jxcore-log( 3180): 2015-11-20T11:00:51.649Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:51.650Z SendDataTCPServer.js: TCP/IP server is close
I/jxcore-log( 3180): 
,D/btif_config_util( 2066): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2066): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2066): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: ALE-L21
,I/jxcore-log( 3180): 2015-11-20T11:00:55.771Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:00:55.772Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:01:00.776Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:00.777Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:00.777Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:00.778Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:66, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 66
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T11:01:05.952Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:05.952Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:05.952Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:01:10.953Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:10.954Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:01:15.957Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:15.958Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:15.958Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:15.959Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 67
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T11:01:21.132Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:21.132Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:21.132Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/UsageStatsService(  747): User[0] Flushing usage stats to disk
,I/jxcore-log( 3180): 2015-11-20T11:01:26.133Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:26.134Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 6 peers.
I/SS      ( 3180): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3180): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3180): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3180): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3180): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3180): Peer(6): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3180): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3180): Started service discovery
,I/jxcore-log( 3180): 2015-11-20T11:01:31.139Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:31.140Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:31.141Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:01:31.141Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:68, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 68
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:01:36.316Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:01:36.317Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:36.317Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/jxcore-log( 3180): 2015-11-20T11:01:41.317Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:01:41.318Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:01:46.321Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:46.323Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:46.324Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:46.324Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:69, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2066): invalid rfc slot id: 69
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T11:01:51.496Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:51.497Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:51.497Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:01:51.498Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 4
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:51.500Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:51.500Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 70920 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): 2015-11-20T11:01:56.502Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:56.502Z SendDataConnector.js: Connect (retry count 0) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:56.503Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:01:56.503Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:70, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 70
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:02:01.688Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:02:01.689Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:02:01.689Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:02:06.691Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:02:06.692Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:02:11.696Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:02:11.697Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:02:11.697Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:02:11.697Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
,W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:71, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2066): invalid rfc slot id: 71
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T11:02:16.872Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:02:16.873Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:02:16.873Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:02:21.873Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:02:21.874Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:02:26.877Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:02:26.877Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:02:26.878Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:02:26.878Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3180): Found 2 peers.
I/SS      ( 3180): Peer(1): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3180): Peer(2): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:72, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2066): invalid rfc slot id: 72
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:02:32.051Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:02:32.051Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:02:32.052Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3180): 2015-11-20T11:02:37.053Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:02:37.054Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/jxcore-log( 3180): 2015-11-20T11:02:42.057Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:02:42.058Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:02:42.059Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:02:42.059Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:73, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2066): invalid rfc slot id: 73
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T11:02:47.234Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:02:47.235Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:02:47.235Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:02:52.235Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:02:52.235Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:02:57.239Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:02:57.240Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:02:57.240Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:02:57.241Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:74, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2066): invalid rfc slot id: 74
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T11:03:02.415Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:02.416Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:02.416Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:02.417Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 5
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:02.419Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:02.419Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 70917 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): 2015-11-20T11:03:07.422Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:07.423Z SendDataConnector.js: Connect (retry count 0) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:07.423Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:07.423Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:75, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 75
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:03:12.610Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:03:12.611Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:03:12.616Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:03:17.618Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:17.619Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:03:22.625Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:22.625Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:22.626Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:22.626Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:76, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 76
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:03:27.797Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:27.798Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:27.798Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3180): 2015-11-20T11:03:32.799Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:32.799Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 2 peers.
I/SS      ( 3180): Peer(1): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3180): Peer(2): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3180): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3180): 2015-11-20T11:03:37.806Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:37.807Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:37.807Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:37.808Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:77, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 77
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:03:42.984Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:42.984Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:42.984Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:03:47.985Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:47.985Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:03:52.988Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:52.989Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:52.989Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:52.990Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:78, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2066): invalid rfc slot id: 78
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:03:58.164Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:58.164Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:03:58.164Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:04:03.165Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:03.166Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:04:08.169Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:08.170Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:08.170Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:08.171Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:79, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2066): invalid rfc slot id: 79
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T11:04:13.344Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:13.344Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:13.344Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:13.345Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 6
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:13.347Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:13.347Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 70926 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): 2015-11-20T11:04:18.350Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:18.351Z SendDataConnector.js: Connect (retry count 0) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:04:18.356Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:18.357Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:80, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 80
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:04:23.542Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:23.543Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:23.543Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:04:28.544Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:28.545Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 4 peers.
I/SS      ( 3180): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3180): Peer(2): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3180): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3180): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/jxcore-log( 3180): 2015-11-20T11:04:33.549Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:33.549Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:33.550Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:33.550Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3180): Started service discovery
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:81, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2066): invalid rfc slot id: 81
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T11:04:38.736Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:38.736Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:38.736Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/jxcore-log( 3180): 2015-11-20T11:04:43.738Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:43.739Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:04:48.744Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:48.744Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:48.745Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:48.745Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:82, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2066): invalid rfc slot id: 82
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:04:53.917Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:53.917Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:53.917Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:04:58.918Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:04:58.918Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:05:03.921Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:03.923Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:03.924Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:03.924Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:83, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 83
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:05:09.095Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:09.095Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:09.096Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:05:14.095Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:14.096Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:05:19.099Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:19.100Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:19.100Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:19.100Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:84, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 84
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:05:24.274Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:24.274Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:24.274Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:05:24.275Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 7
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:05:24.277Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:24.279Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 70929 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): 2015-11-20T11:05:29.284Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:29.285Z SendDataConnector.js: Connect (retry count 0) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:29.285Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:29.286Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:85, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 85
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:05:34.470Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:34.471Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:05:34.474Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 3 peers.
I/SS      ( 3180): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3180): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3180): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3180): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT230"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT230"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT230, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT230, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3180): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3480","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3480","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT3480, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT3480, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3180): 2015-11-20T11:05:39.479Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:39.479Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/jxcore-log( 3180): 2015-11-20T11:05:44.484Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:44.488Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:44.489Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:44.489Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 3 peers.
I/SS      ( 3180): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3180): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3180): Peer(3): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:86, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 86
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:05:49.664Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:49.664Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:49.664Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:05:54.664Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:54.664Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:05:59.668Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:59.669Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:59.669Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:05:59.670Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:87, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 87
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:06:04.844Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:04.844Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:04.844Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:06:09.844Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:09.845Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:06:14.849Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:14.849Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:14.850Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:14.850Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:88, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 88
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T11:06:20.025Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:20.025Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:20.025Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:06:25.026Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:25.026Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:06:30.030Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:30.030Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:30.031Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:06:30.031Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:89, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 89
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T11:06:35.207Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:35.207Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:35.207Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:35.208Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 8
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:35.212Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:35.212Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 70929 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): 2015-11-20T11:06:40.214Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:40.215Z SendDataConnector.js: Connect (retry count 0) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:40.215Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:40.216Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/art     (  747): Explicit concurrent mark sweep GC freed 58946(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 28MB/42MB, paused 1.071ms total 81.351ms
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:90, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 90
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:06:45.480Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:45.481Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:06:45.486Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 2 peers.
I/SS      ( 3180): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3180): Peer(2): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3180): 2015-11-20T11:06:50.490Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:50.491Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/        ( 3180): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8419","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8419","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT8419, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT8419, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/jxcore-log( 3180): 2015-11-20T11:06:55.494Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:55.495Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:55.496Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:06:55.496Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:91, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 91
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:07:00.671Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:00.671Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:00.671Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3180): Found 6 peers.
I/SS      ( 3180): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3180): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3180): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3180): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3180): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3180): Peer(6): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3180): 2015-11-20T11:07:05.673Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:05.674Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3180): Started service discovery
,I/        ( 3180): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5843"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5843"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5843, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5843, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3180): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3840","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3840","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT3840, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT3840, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 3180): 2015-11-20T11:07:10.685Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:10.686Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:10.686Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:10.687Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:92, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 92
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:07:15.863Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:15.863Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:15.863Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3180): Found 6 peers.
I/SS      ( 3180): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3180): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3180): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3180): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3180): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3180): Peer(6): Android_1950 b6:ce:f6:ad:a4:6b
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 3180): 2015-11-20T11:07:20.864Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:20.864Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:07:25.867Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:25.868Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:07:25.869Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:25.869Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:93, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 93
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:07:31.044Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:31.044Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:31.044Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:07:36.045Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:36.045Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:07:41.048Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:41.049Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:41.049Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:41.049Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:94, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 94
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T11:07:46.224Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:46.224Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:46.224Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:46.225Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 9
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:46.227Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:46.227Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 71013 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3180): 2015-11-20T11:07:51.229Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:51.230Z SendDataConnector.js: Connect (retry count 0) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:51.230Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:07:51.231Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:95, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 95
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T11:07:56.442Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:56.443Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:07:56.444Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:08:01.448Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:01.448Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:08:06.454Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:06.454Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:06.455Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:06.455Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:96, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 96
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:08:11.626Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:11.626Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:11.626Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3180): 2015-11-20T11:08:16.627Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:16.628Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 7 peers.
I/SS      ( 3180): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3180): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3180): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3180): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3180): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3180): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3180): Peer(7): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3180): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3840","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3840","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT3840, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT3840, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 3180): 2015-11-20T11:08:21.634Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:21.635Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:21.635Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:21.635Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:97, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 97
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:08:26.814Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:26.814Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:26.814Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 8 peers.
I/SS      ( 3180): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3180): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3180): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3180): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3180): Peer(5): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3180): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3180): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3180): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 3180): 2015-11-20T11:08:31.814Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:31.815Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3180): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3840","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3840","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT3840, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT3840, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3180): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1397","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1397","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1397, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1397, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3180): 2015-11-20T11:08:36.819Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:36.819Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:36.820Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:36.820Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:98, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 98
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:08:41.995Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:41.995Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:41.995Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3180): Found 7 peers.
I/SS      ( 3180): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3180): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3180): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3180): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3180): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3180): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3180): Peer(7): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3180): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT7255","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3180): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT7255","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT7255, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT7255, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/jxcore-log( 3180): 2015-11-20T11:08:46.995Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:46.995Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/        ( 3180): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2083"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2083"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT2083, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT2083, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 3180): 2015-11-20T11:08:52.000Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:52.000Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:08:52.001Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:52.004Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:99, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 99
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:08:57.177Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:57.177Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:57.177Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:08:57.178Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 10
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:57.180Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:08:57.180Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 70951 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3180): Found 8 peers.
,I/SS      ( 3180): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3180): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3180): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3180): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3180): Peer(5): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3180): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3180): Peer(7): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3180): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3180): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3180): Started service discovery
,I/jxcore-log( 3180): 2015-11-20T11:09:02.183Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:09:02.184Z SendDataConnector.js: Connect (retry count 0) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:09:02.184Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:09:02.185Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:100, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 100
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:09:07.370Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:09:07.371Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:09:07.374Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:09:12.378Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:09:12.379Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:09:17.384Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:09:17.384Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:09:17.385Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:09:17.385Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:101, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 101
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:09:22.557Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:09:22.557Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:09:22.557Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:09:27.558Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:09:27.559Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:09:32.563Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:09:32.564Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:09:32.564Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:09:32.565Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:102, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 102
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:09:37.736Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:09:37.736Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:09:37.736Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/jxcore-log( 3180): 2015-11-20T11:09:42.736Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:09:42.737Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:09:47.741Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:09:47.743Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:09:47.743Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:09:47.744Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:103, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 103
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:09:52.929Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:09:52.930Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:09:52.930Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:09:57.930Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:09:57.931Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/        ( 3180): Cleared service requests
,I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3180): Found 9 peers.
I/SS      ( 3180): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3180): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3180): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3180): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3180): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3180): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3180): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3180): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3180): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3180): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3480","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3480","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT3480, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT3480, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3180): 2015-11-20T11:10:02.939Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:02.939Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:02.940Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:02.940Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:104, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 104
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:10:08.115Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:08.115Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:08.115Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:10:08.116Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 11
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:08.118Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:08.118Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 70936 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/SS      ( 3180): Found 4 peers.
I/SS      ( 3180): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3180): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3180): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3180): Peer(4): G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 3180): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3180): Added service request
,I/        ( 3180): Started service discovery
,I/jxcore-log( 3180): 2015-11-20T11:10:13.122Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:13.122Z SendDataConnector.js: Connect (retry count 0) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:13.123Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:13.123Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:105, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 105
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:10:18.327Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:18.328Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:18.328Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:10:23.328Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:23.329Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3180): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT1268"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT1268"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT1268, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT1268, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3180): 2015-11-20T11:10:28.334Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:28.335Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:10:28.335Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:28.343Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:106, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 106
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:10:33.533Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:33.533Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:33.533Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3180): Found 6 peers.
I/SS      ( 3180): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3180): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3180): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3180): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3180): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3180): Peer(6): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3180): 2015-11-20T11:10:38.533Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:38.534Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/        ( 3180): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT9545","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
I/        ( 3180): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT9545","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT9545, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT9545, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3180): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT1268"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT1268"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT1268, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT1268, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3180): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT230"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT230"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT230, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT230, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 3180): 2015-11-20T11:10:43.537Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:43.538Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:43.538Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:10:43.539Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:107, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 107
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:10:48.722Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:48.722Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:48.722Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3180): Found 8 peers.
I/SS      ( 3180): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3180): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3180): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3180): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3180): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3180): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3180): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3180): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1044): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3180): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1397","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1397","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1397, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1397, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3180): 2015-11-20T11:10:53.723Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:53.724Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:10:58.727Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:58.728Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:58.728Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:10:58.729Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:108, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 108
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:11:03.915Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:03.916Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:03.916Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3180): Found 9 peers.
I/SS      ( 3180): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3180): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3180): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3180): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3180): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3180): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3180): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3180): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3180): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3180): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7533","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7533","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT7533, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT7533, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/jxcore-log( 3180): 2015-11-20T11:11:08.917Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:08.917Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/        ( 3180): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT1268"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT1268"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT1268, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT1268, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3180): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT230"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT230"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT230, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT230, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 3180): 2015-11-20T11:11:13.920Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:13.925Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:13.925Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:13.926Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:109, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 109
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T11:11:19.096Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:19.096Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:19.096Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:19.097Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 12
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:19.099Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:19.099Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 70979 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3180): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2083"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2083"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT2083, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT2083, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 3180): 2015-11-20T11:11:24.101Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:24.102Z SendDataConnector.js: Connect (retry count 0) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:24.102Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:24.103Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:110, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 110
,I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:11:29.289Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:29.290Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:29.290Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1044): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3180): Found 10 peers.
I/SS      ( 3180): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3180): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3180): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3180): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3180): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3180): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3180): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3180): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3180): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3180): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/ProcessStatsService(  747): Prepared write state in 3ms
,I/ProcessStatsService(  747): Pruning old procstats: /data/system/procstats/state-2015-11-19-10-39-29.bin
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3180): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9856","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3180): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9856","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9856, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3180): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9856, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 3180): 2015-11-20T11:11:34.292Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:34.292Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:11:39.295Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:39.296Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:39.296Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:39.296Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3180): Cleared service requests
I/        ( 3180): Started peer discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/SS      ( 3180): Found 9 peers.
I/SS      ( 3180): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3180): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3180): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3180): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3180): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3180): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3180): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3180): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3180): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3180): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3180): Added service request
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3180): Started service discovery
,I/wpa_supplicant( 1044): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:111, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 111
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:11:44.468Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:44.468Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:44.468Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:11:49.469Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:49.469Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:11:54.473Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:54.473Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:54.474Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:54.474Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:112, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 112
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:11:59.647Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:59.647Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:11:59.647Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/ActivityManager(  747): Killing 2704:com.google.android.music:main/u0a60 (adj 15): empty for 1816s
,I/ActivityManager(  747): Killing 1958:com.google.android.calendar/u0a31 (adj 15): empty for 1821s
,I/ActivityManager(  747): Killing 2531:com.google.android.gm/u0a70 (adj 15): empty for 1821s
,W/libprocessgroup(  747): failed to open /acct/uid_10060/pid_2704/cgroup.procs: No such file or directory
,W/libprocessgroup(  747): failed to open /acct/uid_10031/pid_1958/cgroup.procs: No such file or directory
,W/libprocessgroup(  747): failed to open /acct/uid_10070/pid_2531/cgroup.procs: No such file or directory
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1601): Aggregate from 1448015813921 (log), 1448015813921 (data)
,I/jxcore-log( 3180): 2015-11-20T11:12:04.648Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:12:04.649Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:12:09.653Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:12:09.654Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:12:09.654Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:12:09.655Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1044): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:113, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 113
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3180): 2015-11-20T11:12:14.826Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:12:14.826Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:12:14.826Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:12:19.826Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:12:19.827Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:12:24.830Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:12:24.831Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:12:24.836Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): 2015-11-20T11:12:24.836Z SendDataConnector.js: do connect now
I/jxcore-log( 3180): 
,I/        ( 3180): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3180): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3180): Starting to connect
W/BluetoothAdapter( 3180): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2066): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2066): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2066): DISCOVERY_COMP_EVT slot id:114, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2066): invalid rfc slot id: 114
I/BTConnectToThread( 3180): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3180): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3180): 2015-11-20T11:12:30.028Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:12:30.028Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:12:30.028Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:12:30.028Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): ---- round done--------
I/jxcore-log( 3180): 
I/jxcore-log( 3180): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 13
I/jxcore-log( 3180): 
I/jxcore-log( 3180): do fake peer & start
I/jxcore-log( 3180): 
I/jxcore-log( 3180): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:12:30.031Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
I/jxcore-log( 3180): 2015-11-20T11:12:30.031Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3180): 
,I/chromium( 3180): [INFO:CONSOLE(63)] "logCallback round[0] time: 70930 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,TIME-OUT KILL (timeout was 1800000ms),I/ActivityManager(  747): Killing 1472:com.google.android.partnersetup/u0a13 (adj 13): empty for 1813s
I/ActivityManager(  747): Killing 1375:android.process.acore/u0a4 (adj 13): empty for 1813s
I/ActivityManager(  747): Killing 1978:com.android.providers.calendar/u0a2 (adj 15): empty for 1822s
I/ActivityManager(  747): Killing 2946:com.google.android.gms:car/u0a8 (adj 15): empty for 1822s
W/libprocessgroup(  747): failed to open /acct/uid_10013/pid_1472/cgroup.procs: No such file or directory
W/libprocessgroup(  747): failed to open /acct/uid_10004/pid_1375/cgroup.procs: No such file or directory
W/libprocessgroup(  747): failed to open /acct/uid_10002/pid_1978/cgroup.procs: No such file or directory
W/libprocessgroup(  747): failed to open /acct/uid_10008/pid_2946/cgroup.procs: No such file or directory
D/AndroidRuntime( 3721): 
D/AndroidRuntime( 3721): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3721): CheckJNI is OFF
D/AndroidRuntime( 3721): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  747): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  747): Killing 3180:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  747): WIN DEATH: Window{29e55981 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  747): Client connection lost with reason: 4
W/PackageSettings(  747): Skipping PackageSetting{f846099 com.example.hello/10277} due to missing metadata
I/ActivityManager(  747):   Force finishing activity ActivityRecord{36a2a352 u0 com.test.thalitest/.MainActivity t214}
W/ActivityManager(  747): Spurious death for ProcessRecord{2e75a2be 3180:com.test.thalitest/u0a270}, curProc for 3180: null
I/ActivityManager(  747): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  747):   Force finishing activity ActivityRecord{36a2a352 u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  747): Duplicate finish request for ActivityRecord{36a2a352 u0 com.test.thalitest/.MainActivity t214 f}
I/art     ( 1362): Explicit concurrent mark sweep GC freed 8436(369KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 19MB/25MB, paused 283us total 18.753ms
I/InputReader(  747): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1563): Ignoring removeGeofence because network location is disabled.
I/art     ( 1236): Explicit concurrent mark sweep GC freed 3940(293KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 231us total 29.442ms
I/Keyboard.Facilitator( 1070): resetDictionaries() : en_US
I/ActivityManager(  747): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=3742 uid=10004 gids={50004, 9997} abi=armeabi-v7a
I/Keyboard.Facilitator.DecoderInitializer( 1070): run()
I/Decoder ( 1070): createOrResetDecoder
I/ConfigService( 1328): onCreate
I/art     (  747): Explicit concurrent mark sweep GC freed 45769(2MB) AllocSpace objects, 5(152KB) LOS objects, 33% free, 28MB/42MB, paused 1.212ms total 110.841ms
I/art     (  747): WaitForGcToComplete blocked for 71.204ms for cause Explicit
I/Adreno-EGL(  948): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  948): Initialized EGL, version 1.4
D/OpenGLRenderer(  948): Enabling debug mode 0
I/Keyboard.Facilitator.MainLanguageModelLoader( 1070): run()
W/InputMethodManagerService(  747): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@646a5c9 (uid=10034 pid=948)
I/Keyboard.Facilitator.MainLanguageModelLoader( 1070): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1070): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1070): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1070): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1070): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1070): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1070): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1070): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1070): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1070): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1070): run()
I/StatsUtilsManager( 1070): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1070): shouldRecordStats() = Too Soon
D/BackupManagerService(  747): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  747): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  747): removeObsoleteFile: deleting file=214_task.xml
I/Launcher( 1236): Deferring update until onResume
W/ResourcesManager( 1236): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/art     (  747): Explicit concurrent mark sweep GC freed 7959(436KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 8.455ms total 146.411ms
D/VoicemailCleanupService( 3742): Cleaning up data for package: com.test.thalitest
W/ResourcesManager( 1236): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/UpdateIcingCorporaServi( 1362): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1236): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@14b2b036 new=com.google.android.velvet.VelvetApplication@14b2b036
I/Launcher( 1236): Deferring update until onResume
I/ActivityManager(  747): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3786 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/ContactLocale( 3742): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/UpdateIcingCorporaServi( 1362): UpdateCorporaTask done [took 75 ms] updated apps [took 75 ms] 
W/ContextImpl( 3786): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
D/AndroidRuntime( 3721): Shutting down VM
D/PackageBroadcastService( 1601): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1601): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1601): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1601): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1601): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1601): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1601): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1328): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1328): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  747): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/ActivityManager(  747): Resuming delayed broadcast
D/gH_CompatibleDatabase( 1601): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1601): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1601): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1601): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1601): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1601): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1601): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1601): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1601): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1601): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1601): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1601): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1601): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  747): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3815 uid=10039 gids={50039, 9997} abi=armeabi-v7a
I/ActivityManager(  747): Killing 3009:com.android.defcontainer/u0a5 (adj 15): empty for 1813s
W/libprocessgroup(  747): failed to open /acct/uid_10005/pid_3009/cgroup.procs: No such file or directory
W/BaseAppContext( 1601): Using Auth Proxy for data requests.
W/BaseAppContext( 1601): Using Auth Proxy for data requests.
I/GMPM-SVC( 1601): App measurement is starting up
I/PeopleContactsSync( 1601): CP2 sync disabled
I/Icing   ( 1601): doRemovePackageData com.test.thalitest
I/ActivityManager(  747): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3837 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
D/ExternalStorage( 3837): After updating volumes, found 1 active roots
W/ResourcesManager( 3099): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3099): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Documents( 3815): Update found 7 roots in 114ms
D/Documents( 3815): Update found 7 roots in 50ms

```
