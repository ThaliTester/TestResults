#### Test 51193821e3da755_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3211): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3211):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3211):   adb logcat -s GAv4
W/GAv4    ( 3211): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3211): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3211): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 3211): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2736): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3211): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3211): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  758): Killing 2538:com.google.android.youtube/u0a80 (adj 15): empty #17
V/JNIHelp ( 3211): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 3211): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3211): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 3252): 
D/AndroidRuntime( 3252): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3252): CheckJNI is OFF
W/libprocessgroup(  758): failed to open /acct/uid_10080/pid_2538/cgroup.procs: No such file or directory
V/GLSActivity( 1383): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3252): Calling main entry com.android.commands.am.Am
I/ActivityManager(  758): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  758): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3276 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3252): Shutting down VM
V/ActivityManager(  758): Display changed displayId=0
I/WebViewFactory( 3276): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/Icing   ( 1697): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/LibraryLoader( 3276): Time to load native libraries: 2 ms (timestamps 361-363)
I/LibraryLoader( 3276): Expected native library version number "",actual native library version number ""
D/Icing   ( 1697): Loaded CLD2 Version V2.0 - 20141016
V/WebViewChromiumFactoryProvider( 3276): Binding Chromium to main looper Looper (main, tid 1) {684b273}
I/LibraryLoader( 3276): Expected native library version number "",actual native library version number ""
I/chromium( 3276): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3276): Initializing chromium process, singleProcess=true
W/art     ( 3276): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3276): ApplicationContext is null in ApplicationStatus
,W/chromium( 3276): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3276): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3276): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3276): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/Icing   ( 1697): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a1dd12e:true
W/art     ( 3276): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3276): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3276): CordovaWebView is running on device made by: LGE
W/art     ( 3276): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3276): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3276): Render dirty regions requested: true
D/Atlas   ( 3276): Validating map...
W/chromium( 3276): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3276): Initialized EGL, version 1.4
D/OpenGLRenderer( 3276): Enabling debug mode 0
I/Keyboard.Facilitator( 1099): onFinishInput()
W/IInputConnectionWrapper( 3276): showStatusIcon on inactive InputConnection
W/BindingManager( 3276): Cannot call determinedVisibility() - never saw a connection for the pid: 3276
I/ActivityManager(  758): Displayed com.test.thalitest/.MainActivity: +495ms (total +58s916ms)
D/JsMessageQueue( 3276): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3276): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257343360
D/JX-Cordova( 3276): jxcore cordova android initializing
I/ActivityManager(  758): Killing 2132:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/libprocessgroup(  758): failed to open /acct/uid_10038/pid_2132/cgroup.procs: No such file or directory
,W/jxcore-log( 3276): Initializing JXcore engine
W/jxcore-log( 3276): JXcore engine is ready
,W/jxcore-log( 3276): Starting JXcore engine
,W/.test.thalitest( 3276): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8084]" dev="sockfs" ino=8084 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3276): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3276): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8464]" dev="sockfs" ino=8464 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3276): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19652]" dev="sockfs" ino=19652 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3276): Platform android
W/jxcore-log( 3276): 
,W/jxcore-log( 3276): Process ARCH arm
W/jxcore-log( 3276): 
,V/GLSActivity( 1383): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1383): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3276): JXcore Cordova bridge is ready!
I/jxcore-log( 3276): 
,W/jxcore-log( 3276): JXcore engine is started
,I/chromium( 3276): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3276): Turning radios to true
I/jxcore-log( 3276): 
,D/BluetoothAdapter( 3276): enable(): BT is already enabled..!
,I/jxcore-log( 3276): toggleBluetooth - 
I/jxcore-log( 3276): 
,D/WifiService(  758): New client listening to asynchronous messages
,D/WifiService(  758): setWifiEnabled: true pid=3276, uid=10270
E/WifiService(  758): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3276): toggleWiFi
I/jxcore-log( 3276): 
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3276): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3276): 
I/jxcore-log( 3276): my name is : LGE-Nexus 5_PT8166
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): attempting to connect to test coordinator
I/jxcore-log( 3276): 
I/jxcore-log( 3276): check test folder
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found test : ./testFindPeers.js
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found test : ./testReConnect.js
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found test : ./testSendData.js
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): Test app app.js loaded
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1383): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1383): Vacuum at: now=1447926062156 tag=VacuumService
,D/Finsky  ( 2736): [270] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2736): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/UdcCache:FPQuery( 1697): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1383): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1383): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetConfigurationSnapshotOperation( 1383): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1383): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1383): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1383): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1383): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1383): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1383):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1383): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1383): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1383): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1383): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1383): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1383): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1099): run()
I/Keyboard.Facilitator( 1099): flushDynamicLanguageModels()
,I/ConfigService( 1383): onCreate
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/ConfigService( 1383): onDestroy
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/ClearcutLoggerApiImpl( 1669): disconnect managed GoogleApiClient
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,E/DataBuffer( 1383): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@36ef48a7)
,E/DataBuffer( 1383): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@242f0154)
E/DataBuffer( 1383): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@156358fd)
E/DataBuffer( 1383): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@311829f2)
E/DataBuffer( 1383): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@273dc843)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 2154): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HeadsetStateMachine( 2154): Disconnected process message: 11, size: 0
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Coordinator is now connected to the server!
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ActivityManager(  758): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3412 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3412): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3412):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3412):   adb logcat -s GAv4
,W/GAv4    ( 3412): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3412): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3412): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  758): Killing 2698:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10069/pid_2698/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 2154): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 2154): Disconnected process message: 11, size: 0
,I/jxcore-log( 3276): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): DBG, CoordinatorConnector command called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"1000000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":15,"addressList":[{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"90:E7:C4:F6:69:77","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"F4:F1:E1:5C:3B:E2","tryCount":0}]}
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Start now : testSendData.js
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): stop tests now !
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): testSendData created {"timeout":"500000","rounds":"1","dataTimeout":"10000","dataAmount":"1000000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 15
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): check server
I/jxcore-log( 3276): 
I/jxcore-log( 3276): serverPort is 48644
I/jxcore-log( 3276): 
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3276): Stoping All
I/        ( 3276): Stopping services
I/        ( 3276): Stop Bluetooth
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3276): Start-My BT: 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3276):  mInstanceString : {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8166","ra":"34:FC:EF:11:AE:67"}
,I/art     (  758): Explicit concurrent mark sweep GC freed 23802(1085KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.136ms total 50.686ms
,I/        ( 3276): All stuff available and enabled
I/        ( 3276): Stoping All
I/        ( 3276): Stopping services
I/        ( 3276): Stop Bluetooth
I/        ( 3276): Starting All
I/        ( 3276): Stopping services
I/        ( 3276): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8166","ra":"34:FC:EF:11:AE:67"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@a18c5d2
I/        ( 3276): Stopping services
I/        ( 3276): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8166","ra":"34:FC:EF:11:AE:67"}
I/        ( 3276): Add local service :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8166","ra":"34:FC:EF:11:AE:67"}, length : 77
I/        ( 3276): peerDiscoveryTimer timeout value:6023
,I/        ( 3276): Stop Bluetooth
I/        ( 3276): StartBluetooth listener
I/        ( 3276): StartBluetooth listener
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3276): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 3276): StartBroadcasting started ok
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do fake peer & start
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3276): 
I/jxcore-log( 3276): TCP/IP server  is bound to : undefined
I/jxcore-log( 3276): 
I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 3276): We already were running, thus doing nothing
,I/        ( 3276): Added local service
I/        ( 3276): Cleared service requests
I/        ( 3276): Stopped peer discovery
I/        ( 3276): Started peer discovery
I/        ( 3276): Discovery state changed to Started.
,I/BTListenerThread( 3276): starting to listen
I/BTListenerThread( 3276): waiting to accept incoming Connection
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3276): Found 2 peers.
I/SS      ( 3276): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3276): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pManager( 3276): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3276): Started service discovery
,I/        ( 3276): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3126"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3126"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT3126, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT3126, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3276): Connect (retry count 0) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): do connect now
I/jxcore-log( 3276): 
,I/        ( 3276): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 3276): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3276): Starting to connect
W/BluetoothAdapter( 3276): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2154): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2154): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2154): DISCOVERY_COMP_EVT slot id:5, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2154): invalid rfc slot id: 5
,I/BTConnectToThread( 3276): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3276): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3276): CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3276): 
I/jxcore-log( 3276): tryAgain afer: 5000 ms.
I/jxcore-log( 3276): 
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/jxcore-log( 3276): re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 4 peers.
I/SS      ( 3276): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3276): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3276): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(4): G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 3276): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3276): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9121","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3276): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9121","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9121, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9121, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 3276): Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do connect now
I/jxcore-log( 3276): 
,I/        ( 3276): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 3276): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3276): Starting to connect
W/BluetoothAdapter( 3276): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2154): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2154): info:x10
,D/        ( 2154): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2154): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2154): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2154): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 2154): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2154): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2154): Entering PendingCommandState State
,W/BluetoothEventManager( 2787): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2787): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 2154): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2154): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2154): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,W/BluetoothEventManager( 2787): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2787): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 2154): StableState(): Entering Off State
,W/bt-btif ( 2154): new conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3276): Starting to Handshake
I/BTHandshakeSocketThread( 3276): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3276): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread started
,I/BTConnectToThread( 3276): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3276): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT575","ra":"08:EC:A9:50:75:41"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3276): HandshakeOk : samsung-SM-A300FU_PT575
I/HS      ( 3276): Hand Shake finished outgoing for : samsung-SM-A300FU_PT575
I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3276): Starting the connected thread incoming : false, samsung-SM-A300FU_PT575
,I/BtToSocketBase( 3276): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3276): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3276): mHTTPPort  set to : 46002
I/BtConnectorHelper( 3276): Request socket is using : 46002
I/BtToRequestSocket( 3276): Now accepting connections
,I/BtConnectorHelper( 3276): Calling ConnectionStatusUpdate with port :46002
I/jxcore-log( 3276): CLIENT connected to 46002, error: null
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT starting client 
I/jxcore-log( 3276): 
,I/BtToRequestSocket( 3276): incoming data from: /127.0.0.1, port: 46002
I/BtToRequestSocket( 3276): Set local streams
I/BtToRequestSocket( 3276): rin ended ---------------------------;
,I/jxcore-log( 3276): CLIENT now sending 1000000 bytes of data
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:76970
,I/jxcore-log( 3276): CLIENT is data received : 10000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 20000
I/jxcore-log( 3276): 
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71166
,I/jxcore-log( 3276): CLIENT is data received : 30000
I/jxcore-log( 3276): 
,D/btif_config_util( 2154): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3276): CLIENT is data received : 40000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69458
,I/jxcore-log( 3276): CLIENT is data received : 50000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 8 peers.
I/SS      ( 3276): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3276): Peer(2): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(5): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3276): Peer(6): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3276): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3276): Peer(8): Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3276): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3276): CLIENT is data received : 60000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71846
,I/jxcore-log( 3276): CLIENT is data received : 70000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3276): CLIENT is data received : 80000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70138
,I/jxcore-log( 3276): CLIENT is data received : 90000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 100000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68430
,I/jxcore-log( 3276): CLIENT is data received : 110000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 120000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69828
,I/jxcore-log( 3276): CLIENT is data received : 130000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 140000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68120
,I/jxcore-log( 3276): CLIENT is data received : 150000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 160000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70508
,I/jxcore-log( 3276): CLIENT is data received : 170000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 180000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68800
,I/jxcore-log( 3276): CLIENT is data received : 190000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 200000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71188
,I/jxcore-log( 3276): CLIENT is data received : 210000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 220000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69480
,I/jxcore-log( 3276): CLIENT is data received : 230000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 240000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71868
,I/jxcore-log( 3276): CLIENT is data received : 250000
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=0
,W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3276): CLIENT is data received : 260000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70160
,I/jxcore-log( 3276): CLIENT is data received : 270000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 280000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68452
,I/jxcore-log( 3276): CLIENT is data received : 290000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 300000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70840
,I/jxcore-log( 3276): CLIENT is data received : 310000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71112
,I/jxcore-log( 3276): CLIENT is data received : 320000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 330000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69404
,I/jxcore-log( 3276): CLIENT is data received : 340000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 350000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73772
,I/jxcore-log( 3276): CLIENT is data received : 360000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 370000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67968
,I/jxcore-log( 3276): CLIENT is data received : 380000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 390000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69366
,I/jxcore-log( 3276): CLIENT is data received : 400000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 410000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72744
,I/jxcore-log( 3276): CLIENT is data received : 420000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 430000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71036
,I/jxcore-log( 3276): CLIENT is data received : 440000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 450000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69328
,I/jxcore-log( 3276): CLIENT is data received : 460000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 470000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71716
,I/jxcore-log( 3276): CLIENT is data received : 480000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 490000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69018
,I/jxcore-log( 3276): CLIENT is data received : 500000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:76356
,I/jxcore-log( 3276): CLIENT is data received : 510000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 520000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70552
,I/jxcore-log( 3276): CLIENT is data received : 530000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 540000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67854
,I/jxcore-log( 3276): CLIENT is data received : 550000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:75192
,I/jxcore-log( 3276): CLIENT is data received : 560000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 570000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 580000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70378
,I/ActivityManager(  758): Killing 2645:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10045/pid_2645/cgroup.procs: No such file or directory
,I/jxcore-log( 3276): CLIENT is data received : 590000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68670
,I/jxcore-log( 3276): CLIENT is data received : 600000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 610000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70068
,I/jxcore-log( 3276): CLIENT is data received : 620000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 630000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69350
,I/jxcore-log( 3276): CLIENT is data received : 640000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 650000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71738
,I/jxcore-log( 3276): CLIENT is data received : 660000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72010
,I/jxcore-log( 3276): CLIENT is data received : 670000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 680000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71292
,I/jxcore-log( 3276): CLIENT is data received : 690000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:75524
,I/jxcore-log( 3276): CLIENT is data received : 700000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 710000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69720
,I/jxcore-log( 3276): CLIENT is data received : 720000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72962
,I/jxcore-log( 3276): CLIENT is data received : 730000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 740000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71254
,I/jxcore-log( 3276): CLIENT is data received : 750000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 760000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69546
,I/jxcore-log( 3276): CLIENT is data received : 770000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74904
,I/jxcore-log( 3276): CLIENT is data received : 780000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 790000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71080
,I/jxcore-log( 3276): CLIENT is data received : 800000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 810000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69372
,I/jxcore-log( 3276): CLIENT is data received : 820000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 830000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:63857
,I/jxcore-log( 3276): CLIENT is data received : 840000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 850000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:53957
,I/jxcore-log( 3276): CLIENT is data received : 860000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 870000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:44057
,I/jxcore-log( 3276): CLIENT is data received : 880000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 890000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:34157
,I/jxcore-log( 3276): CLIENT is data received : 900000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 910000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23267
,I/jxcore-log( 3276): CLIENT is data received : 920000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 930000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13367
,I/jxcore-log( 3276): CLIENT is data received : 940000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 950000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3467
,I/jxcore-log( 3276): CLIENT is data received : 960000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 970000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 980000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 990000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 1000000
I/jxcore-log( 3276): 
I/jxcore-log( 3276): got all data for this round
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT Stop now
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT closeClientSocket
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT Stop now
I/jxcore-log( 3276): 
I/jxcore-log( 3276): ---- round done--------
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do fake peer & start
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback round[0] time: 60170 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3276): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3276): Disconnect outgoing peer: samsung-SM-A300FU_PT575
I/BtToSocketBase( 3276): Stop ReceivingThread
I/BtToSocketBase( 3276): Stop SendingThread
I/BtToSocketBase( 3276): Close local in
I/BtToSocketBase( 3276): Close LocalOutputStream
,I/BtToSocketBase( 3276): Close localHostSocket
I/BtToSocketBase( 3276): Close bt in
,I/BtToSocketBase( 3276): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3276): Close bt out
I/BtToSocketBase( 3276): Close bt socket
I/BtToRequestSocket( 3276): Close server socket
,I/jxcore-log( 3276): CLIENT is closed
I/jxcore-log( 3276): 
,W/bt-btif ( 2154): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,E/bt-btm  ( 2154): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2154): onReceive
,D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@276c0db4:true
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: A3-1
,I/jxcore-log( 3276): Connect (retry count 0) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do connect now
I/jxcore-log( 3276): 
,I/        ( 3276): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3276): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3276): Starting to connect
W/BluetoothAdapter( 3276): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2154): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,W/bt-btif ( 2154): info:x10
,D/        ( 2154): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2154): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2154): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2154): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 2154): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2154): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2154): Entering PendingCommandState State
,W/BluetoothEventManager( 2787): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2787): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2154): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2154): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 2154): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2154): StableState(): Entering Off State
,W/BluetoothEventManager( 2787): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2787): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,W/bt-btif ( 2154): new conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3276): Starting to Handshake
I/BTHandshakeSocketThread( 3276): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3276): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread started
,I/BTConnectToThread( 3276): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3276): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6448","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3276): HandshakeOk : samsung-SM-N910C_PT6448
I/HS      ( 3276): Hand Shake finished outgoing for : samsung-SM-N910C_PT6448
I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3276): Starting the connected thread incoming : false, samsung-SM-N910C_PT6448
I/BtToSocketBase( 3276): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3276): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3276): mHTTPPort  set to : 46616
,I/BtConnectorHelper( 3276): Request socket is using : 46616
I/BtToRequestSocket( 3276): Now accepting connections
,I/BtConnectorHelper( 3276): Calling ConnectionStatusUpdate with port :46616
I/jxcore-log( 3276): CLIENT connected to 46616, error: null
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT starting client 
I/jxcore-log( 3276): 
,I/BtToRequestSocket( 3276): incoming data from: /127.0.0.1, port: 46616
I/BtToRequestSocket( 3276): Set local streams
I/BtToRequestSocket( 3276): rin ended ---------------------------;
,I/jxcore-log( 3276): CLIENT now sending 1000000 bytes of data
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69050
,I/jxcore-log( 3276): CLIENT is data received : 10000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 20000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74408
,I/jxcore-log( 3276): CLIENT is data received : 30000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 40000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67614
,I/jxcore-log( 3276): CLIENT is data received : 50000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 60000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:64062
,I/jxcore-log( 3276): CLIENT is data received : 70000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 80000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:65596
,I/jxcore-log( 3276): CLIENT is data received : 80000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 90000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:58084
,I/jxcore-log( 3276): CLIENT is data received : 90000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 100000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67674
,I/jxcore-log( 3276): CLIENT is data received : 110000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 120000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70062
,I/jxcore-log( 3276): CLIENT is data received : 130000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:59444
,I/jxcore-log( 3276): CLIENT is data received : 130000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 140000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69034
,I/jxcore-log( 3276): CLIENT is data received : 150000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 160000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69442
,I/jxcore-log( 3276): CLIENT is data received : 170000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 170000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:65890
,I/jxcore-log( 3276): CLIENT is data received : 180000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 190000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70258
,I/jxcore-log( 3276): CLIENT is data received : 200000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 210000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67560
,I/jxcore-log( 3276): CLIENT is data received : 220000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:65988
,I/jxcore-log( 3276): CLIENT is data received : 220000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 230000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69366
,I/jxcore-log( 3276): CLIENT is data received : 240000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 250000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72744
,I/jxcore-log( 3276): CLIENT is data received : 260000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 270000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:59156
,I/jxcore-log( 3276): CLIENT is data received : 270000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 280000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71716
,I/jxcore-log( 3276): CLIENT is data received : 290000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 300000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70008
,I/jxcore-log( 3276): CLIENT is data received : 310000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 320000
I/jxcore-log( 3276): 
,D/btif_config_util( 2154): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:56420
,I/jxcore-log( 3276): CLIENT is data received : 320000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:75056
,I/jxcore-log( 3276): CLIENT is data received : 330000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 340000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69252
,I/jxcore-log( 3276): CLIENT is data received : 350000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:57780
,I/jxcore-log( 3276): CLIENT is data received : 350000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 360000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69350
,I/jxcore-log( 3276): CLIENT is data received : 370000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:64536
,I/jxcore-log( 3276): CLIENT is data received : 370000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 380000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:59140
,I/jxcore-log( 3276): CLIENT is data received : 380000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 390000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71700
,I/jxcore-log( 3276): CLIENT is data received : 400000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 410000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72962
,I/jxcore-log( 3276): CLIENT is data received : 420000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 430000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:56404
,I/jxcore-log( 3276): CLIENT is data received : 430000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 440000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:64167
,I/jxcore-log( 3276): CLIENT is data received : 450000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 460000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:54267
,I/jxcore-log( 3276): CLIENT is data received : 470000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 480000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:33477
,I/jxcore-log( 3276): CLIENT is data received : 480000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 490000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23577
,I/jxcore-log( 3276): CLIENT is data received : 500000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 510000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13677
,I/jxcore-log( 3276): CLIENT is data received : 520000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 530000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 530000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 540000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 550000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 560000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 570000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 580000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 580000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 590000
I/jxcore-log( 3276): 
,W/bt-btif ( 2154): dm_pm_timer expires
W/bt-btif ( 2154): dm_pm_timer expires 0
W/bt-btif ( 2154): proc dm_pm_timer expires
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3276): Found 7 peers.
I/SS      ( 3276): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3276): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3276): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3276): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3276): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3276): Receiving data timeout now
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT closeClientSocket
I/jxcore-log( 3276): 
,I/BtToSocketBase( 3276): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3276): Disconnect outgoing peer: samsung-SM-N910C_PT6448
,I/BtToSocketBase( 3276): Stop ReceivingThread
I/BtToSocketBase( 3276): Stop SendingThread
I/BtToSocketBase( 3276): Close local in
,I/BtToSocketBase( 3276): Close LocalOutputStream
I/BtToSocketBase( 3276): Close localHostSocket
I/BtToSocketBase( 3276): Close bt in
,I/BtToSocketBase( 3276): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BtToSocketBase( 3276): Close bt out
I/BtToSocketBase( 3276): Close bt socket
I/BtToRequestSocket( 3276): Close server socket
,I/jxcore-log( 3276): tryAgain afer: 5000 ms.
I/jxcore-log( 3276): 
I/jxcore-log( 3276): ----------------- closeClientSocket
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT is closed
I/jxcore-log( 3276): 
I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2154): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3276): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8840"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8840"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8840, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8840, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT1545"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT1545"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT1545, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT1545, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3276): re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2154): onReceive
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: Note4-1
,I/jxcore-log( 3276): Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do connect now
I/jxcore-log( 3276): 
,I/        ( 3276): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 3276): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3276): Starting to connect
W/BluetoothAdapter( 3276): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2154): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3276): Cleared service requests
,I/        ( 3276): Started peer discovery
,W/bt-btif ( 2154): info:x10
,D/        ( 2154): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 2154): process_service_search_attr_rsp
,W/bt-btif ( 2154): new conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3276): Starting to Handshake
,I/BTHandshakeSocketThread( 3276): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3276): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread started
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/BTConnectToThread( 3276): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3276): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6448","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3276): HandshakeOk : samsung-SM-N910C_PT6448
,I/HS      ( 3276): Hand Shake finished outgoing for : samsung-SM-N910C_PT6448
I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3276): Starting the connected thread incoming : false, samsung-SM-N910C_PT6448
I/BtToSocketBase( 3276): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3276): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3276): mHTTPPort  set to : 40864
I/BtConnectorHelper( 3276): Request socket is using : 40864
I/BtToRequestSocket( 3276): Now accepting connections
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 6 peers.
I/SS      ( 3276): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3276): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3276): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3276): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3276): Added service request
,I/BtConnectorHelper( 3276): Calling ConnectionStatusUpdate with port :40864
,I/jxcore-log( 3276): CLIENT connected to 40864, error: null
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT starting client 
I/jxcore-log( 3276): 
,I/BtToRequestSocket( 3276): incoming data from: /127.0.0.1, port: 40864
I/BtToRequestSocket( 3276): Set local streams
,I/BtToRequestSocket( 3276): rin ended ---------------------------;
,I/jxcore-log( 3276): CLIENT now sending 410000 bytes of data
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71030
,I/jxcore-log( 3276): CLIENT is data received : 600000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 610000
I/jxcore-log( 3276): 
,D/btif_config_util( 2154): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3276): Started service discovery
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70312
,I/jxcore-log( 3276): CLIENT is data received : 620000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 630000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67614
,I/jxcore-log( 3276): CLIENT is data received : 640000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 650000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68022
,I/jxcore-log( 3276): CLIENT is data received : 660000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 670000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68430
,I/jxcore-log( 3276): CLIENT is data received : 680000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 690000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70818
,I/jxcore-log( 3276): CLIENT is data received : 700000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:66140
,I/jxcore-log( 3276): CLIENT is data received : 700000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 710000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70508
,I/jxcore-log( 3276): CLIENT is data received : 720000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 730000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68800
,I/jxcore-log( 3276): CLIENT is data received : 740000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 750000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:51317
,I/jxcore-log( 3276): CLIENT is data received : 750000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 760000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:44387
,I/jxcore-log( 3276): CLIENT is data received : 770000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 780000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:34487
,I/jxcore-log( 3276): CLIENT is data received : 790000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 800000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11717
,I/jxcore-log( 3276): CLIENT is data received : 800000
I/jxcore-log( 3276): 
,I/        ( 3276): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT1545"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT1545"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT1545, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT1545, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 3276): CLIENT is data received : 810000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3797
,I/jxcore-log( 3276): CLIENT is data received : 820000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 830000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 840000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 850000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 850000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 860000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 870000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 880000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 890000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 900000
I/jxcore-log( 3276): 
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2154): dm_pm_timer expires
W/bt-btif ( 2154): dm_pm_timer expires 0
,W/bt-btif ( 2154): proc dm_pm_timer expires
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 6 peers.
I/SS      ( 3276): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3276): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3276): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3276): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3276): Started service discovery
,I/        ( 3276): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9121","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9121","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9121, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9121, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 3276): Receiving data timeout now
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT closeClientSocket
I/jxcore-log( 3276): 
,I/BtToSocketBase( 3276): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3276): Disconnect outgoing peer: samsung-SM-N910C_PT6448
I/BtToSocketBase( 3276): Stop ReceivingThread
I/BtToSocketBase( 3276): Stop SendingThread
I/BtToSocketBase( 3276): Close local in
I/BtToSocketBase( 3276): Close LocalOutputStream
I/BtToSocketBase( 3276): Close localHostSocket
I/BtToSocketBase( 3276): Close bt in
,I/BtToSocketBase( 3276): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3276): Close bt out
I/BtToSocketBase( 3276): Close bt socket
I/BtToRequestSocket( 3276): Close server socket
,I/jxcore-log( 3276): tryAgain afer: 5000 ms.
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): ----------------- closeClientSocket
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT is closed
I/jxcore-log( 3276): 
,W/bt-btif ( 2154): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/jxcore-log( 3276): re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2154): onReceive
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: Note4-1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 7 peers.
I/SS      ( 3276): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3276): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3276): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3276): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3617","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3617","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT3617, peerAddress: F8:CF:C5:D9:E5:61
,I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT3617, WifiDirectName: , WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/        ( 3276): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9121","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9121","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9121, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9121, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 3276): Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do connect now
I/jxcore-log( 3276): 
,I/        ( 3276): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 3276): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3276): Starting to connect
W/BluetoothAdapter( 3276): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2154): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2154): info:x10
,D/        ( 2154): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,W/bt-sdp  ( 2154): process_service_search_attr_rsp
,I/BluetoothClassifier( 1427): Bluetooth Device Name: Note4-1
,W/bt-btif ( 2154): new conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3276): Starting to Handshake
I/BTHandshakeSocketThread( 3276): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3276): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread started
,I/BTConnectToThread( 3276): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3276): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6448","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3276): HandshakeOk : samsung-SM-N910C_PT6448
I/HS      ( 3276): Hand Shake finished outgoing for : samsung-SM-N910C_PT6448
I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3276): Starting the connected thread incoming : false, samsung-SM-N910C_PT6448
,I/BtToSocketBase( 3276): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3276): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3276): mHTTPPort  set to : 40438
I/BtConnectorHelper( 3276): Request socket is using : 40438
I/BtToRequestSocket( 3276): Now accepting connections
,I/BtConnectorHelper( 3276): Calling ConnectionStatusUpdate with port :40438
I/jxcore-log( 3276): CLIENT connected to 40438, error: null
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT starting client 
I/jxcore-log( 3276): 
,I/BtToRequestSocket( 3276): incoming data from: /127.0.0.1, port: 40438
I/BtToRequestSocket( 3276): Set local streams
I/BtToRequestSocket( 3276): rin ended ---------------------------;
,I/jxcore-log( 3276): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1257
,I/jxcore-log( 3276): CLIENT is data received : 910000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 920000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 930000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 940000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 950000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 960000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 970000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 980000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 990000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 1000000
I/jxcore-log( 3276): 
I/jxcore-log( 3276): got all data for this round
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT Stop now
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT closeClientSocket
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT Stop now
I/jxcore-log( 3276): 
I/jxcore-log( 3276): ---- round done--------
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do fake peer & start
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3276): 
I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback round[0] time: 88203 ms, rnd: 3, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3276): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3276): Disconnect outgoing peer: samsung-SM-N910C_PT6448
I/BtToSocketBase( 3276): Stop ReceivingThread
I/BtToSocketBase( 3276): Stop SendingThread
I/BtToSocketBase( 3276): Close local in
I/BtToSocketBase( 3276): Close LocalOutputStream
I/BtToSocketBase( 3276): Close localHostSocket
I/BtToSocketBase( 3276): Close bt in
,I/BtToSocketBase( 3276): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3276): Close bt out
,I/BtToSocketBase( 3276): Close bt socket
I/BtToRequestSocket( 3276): Close server socket
,I/jxcore-log( 3276): CLIENT is closed
I/jxcore-log( 3276): 
,W/bt-btif ( 2154): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,D/btif_config_util( 2154): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3276): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT1545"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT1545"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT1545, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT1545, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,E/bt-btm  ( 2154): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2154): onReceive
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: Note4-1
,I/        ( 3276): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8840"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8840"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8840, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8840, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 3276): Connect (retry count 0) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do connect now
I/jxcore-log( 3276): 
,I/        ( 3276): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 3276): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3276): Starting to connect
W/BluetoothAdapter( 3276): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2154): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2154): info:x10
,D/        ( 2154): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2154): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2154): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2154): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1
,E/bt-btif ( 2154): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2154): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2154): Entering PendingCommandState State
,W/BluetoothEventManager( 2787): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 2787): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,I/BluetoothBondStateMachine( 2154): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 0
,D/BluetoothAdapterProperties( 2154): Failed to remove device: B4:CE:F6:AB:A4:6A
,I/BluetoothBondStateMachine( 2154): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2154): StableState(): Entering Off State
,W/BluetoothEventManager( 2787): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 2787): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,W/bt-btif ( 2154): new conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3276): Starting to Handshake
I/BTHandshakeSocketThread( 3276): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3276): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread started
,I/BTConnectToThread( 3276): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 3276): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3126"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3276): HandshakeOk : HTC-HTC Desire 820_PT3126
I/HS      ( 3276): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT3126
,I/BtConnectorHelper( 3276): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT3126
I/BtToSocketBase( 3276): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3276): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3276): mHTTPPort  set to : 55069
I/BtConnectorHelper( 3276): Request socket is using : 55069
I/BtToRequestSocket( 3276): Now accepting connections
,I/BtConnectorHelper( 3276): Calling ConnectionStatusUpdate with port :55069
I/jxcore-log( 3276): CLIENT connected to 55069, error: null
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT starting client 
I/jxcore-log( 3276): 
,I/BtToRequestSocket( 3276): incoming data from: /127.0.0.1, port: 55069
I/BtToRequestSocket( 3276): Set local streams
I/BtToRequestSocket( 3276): rin ended ---------------------------;
,I/jxcore-log( 3276): CLIENT now sending 1000000 bytes of data
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10542,tx.queue.count:11,available:79940
,I/jxcore-log( 3276): CLIENT is data received : 10000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 20000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70040
,I/jxcore-log( 3276): CLIENT is data received : 30000
I/jxcore-log( 3276): 
,I/        ( 3276): Cleared service requests
,I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3276): Found 7 peers.
I/SS      ( 3276): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3276): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3276): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3276): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/jxcore-log( 3276): CLIENT is data received : 40000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2154): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3276): Started service discovery
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:66352
,I/jxcore-log( 3276): CLIENT is data received : 50000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 60000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69730
,I/jxcore-log( 3276): CLIENT is data received : 70000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 80000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69012
,I/jxcore-log( 3276): CLIENT is data received : 90000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 100000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71400
,I/jxcore-log( 3276): CLIENT is data received : 110000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 120000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69692
,I/jxcore-log( 3276): CLIENT is data received : 130000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:62044
,I/jxcore-log( 3276): CLIENT is data received : 130000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 140000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68528
,I/jxcore-log( 3276): CLIENT is data received : 150000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 160000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70916
,I/jxcore-log( 3276): CLIENT is data received : 170000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 180000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:59308
,I/jxcore-log( 3276): CLIENT is data received : 180000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 190000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69888
,I/jxcore-log( 3276): CLIENT is data received : 200000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 210000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68180
,I/jxcore-log( 3276): CLIENT is data received : 220000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 230000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:60668
,I/jxcore-log( 3276): CLIENT is data received : 230000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 240000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:76198
,I/jxcore-log( 3276): CLIENT is data received : 250000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 260000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67424
,I/jxcore-log( 3276): CLIENT is data received : 270000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 280000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:57932
,I/jxcore-log( 3276): CLIENT is data received : 280000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 290000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70492
,I/jxcore-log( 3276): CLIENT is data received : 300000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 310000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70764
,I/jxcore-log( 3276): CLIENT is data received : 320000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 330000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:55196
,I/jxcore-log( 3276): CLIENT is data received : 330000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 340000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73832
,I/jxcore-log( 3276): CLIENT is data received : 350000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 360000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68028
,I/jxcore-log( 3276): CLIENT is data received : 370000
I/jxcore-log( 3276): 
,I/art     (  758): Explicit concurrent mark sweep GC freed 26309(1446KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.041ms total 102.158ms
,I/jxcore-log( 3276): CLIENT is data received : 380000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:56556
,I/jxcore-log( 3276): CLIENT is data received : 380000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 390000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71232
,I/jxcore-log( 3276): CLIENT is data received : 400000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 410000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72494
,I/jxcore-log( 3276): CLIENT is data received : 420000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 430000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:57916
,I/jxcore-log( 3276): CLIENT is data received : 430000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 440000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70476
,I/jxcore-log( 3276): CLIENT is data received : 450000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 460000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69758
,I/jxcore-log( 3276): CLIENT is data received : 470000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 480000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:55180
,I/jxcore-log( 3276): CLIENT is data received : 480000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 490000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72826
,I/jxcore-log( 3276): CLIENT is data received : 500000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 510000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70128
,I/jxcore-log( 3276): CLIENT is data received : 520000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 530000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:56540
,I/jxcore-log( 3276): CLIENT is data received : 530000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 540000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:47919
,I/jxcore-log( 3276): CLIENT is data received : 550000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 560000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:39009
,I/jxcore-log( 3276): CLIENT is data received : 570000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 580000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:17229
,I/jxcore-log( 3276): CLIENT is data received : 580000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 590000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:9309
,I/jxcore-log( 3276): CLIENT is data received : 600000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 610000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 620000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 630000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 630000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 640000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 650000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 660000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 670000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 680000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 690000
I/jxcore-log( 3276): 
,W/bt-btif ( 2154): dm_pm_timer expires
W/bt-btif ( 2154): dm_pm_timer expires 0
W/bt-btif ( 2154): proc dm_pm_timer expires
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/jxcore-log( 3276): Receiving data timeout now
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT closeClientSocket
I/jxcore-log( 3276): 
,I/BtToSocketBase( 3276): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3276): Disconnect outgoing peer: HTC-HTC Desire 820_PT3126
I/BtToSocketBase( 3276): Stop ReceivingThread
I/BtToSocketBase( 3276): Stop SendingThread
I/BtToSocketBase( 3276): Close local in
I/BtToSocketBase( 3276): Close LocalOutputStream
I/BtToSocketBase( 3276): Close localHostSocket
I/BtToSocketBase( 3276): Close bt in
,I/BtToSocketBase( 3276): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3276): Close bt out
I/BtToSocketBase( 3276): Close bt socket
I/BtToRequestSocket( 3276): Close server socket
,I/jxcore-log( 3276): tryAgain afer: 5000 ms.
I/jxcore-log( 3276): 
I/jxcore-log( 3276): ----------------- closeClientSocket
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT is closed
I/jxcore-log( 3276): 
,W/bt-btif ( 2154): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,I/jxcore-log( 3276): re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2154): onReceive
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3276): Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do connect now
I/jxcore-log( 3276): 
,I/        ( 3276): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 3276): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3276): Starting to connect
W/BluetoothAdapter( 3276): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2154): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2154): info:x10
,D/        ( 2154): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 2154): process_service_search_attr_rsp
,W/bt-btif ( 2154): new conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2154): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3276): Starting to Handshake
I/BTHandshakeSocketThread( 3276): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3276): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread started
,I/BTConnectToThread( 3276): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 3276): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3126"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3276): HandshakeOk : HTC-HTC Desire 820_PT3126
I/HS      ( 3276): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT3126
I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3276): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT3126
I/BtToSocketBase( 3276): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3276): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3276): mHTTPPort  set to : 33894
I/BtConnectorHelper( 3276): Request socket is using : 33894
I/BtToRequestSocket( 3276): Now accepting connections
,I/BtConnectorHelper( 3276): Calling ConnectionStatusUpdate with port :33894
I/jxcore-log( 3276): CLIENT connected to 33894, error: null
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT starting client 
I/jxcore-log( 3276): 
,I/BtToRequestSocket( 3276): incoming data from: /127.0.0.1, port: 33894
I/BtToRequestSocket( 3276): Set local streams
I/BtToRequestSocket( 3276): rin ended ---------------------------;
,I/jxcore-log( 3276): CLIENT now sending 310000 bytes of data
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10036,tx.queue.count:11,available:72020
,I/jxcore-log( 3276): CLIENT is data received : 700000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 710000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69322
,I/jxcore-log( 3276): CLIENT is data received : 720000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 730000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71710
,I/jxcore-log( 3276): CLIENT is data received : 740000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 750000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67032
,I/jxcore-log( 3276): CLIENT is data received : 760000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 770000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:62697
,I/jxcore-log( 3276): CLIENT is data received : 780000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 790000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 800000
I/jxcore-log( 3276): 
,D/btif_config_util( 2154): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:47847
,I/jxcore-log( 3276): CLIENT is data received : 810000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:34977
,I/jxcore-log( 3276): CLIENT is data received : 810000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 820000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:28047
,I/jxcore-log( 3276): CLIENT is data received : 830000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 840000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19137
,I/jxcore-log( 3276): CLIENT is data received : 850000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 860000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 860000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 870000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 880000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 890000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 900000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 910000
I/jxcore-log( 3276): 
,W/bt-btif ( 2154): dm_pm_timer expires
W/bt-btif ( 2154): dm_pm_timer expires 0
W/bt-btif ( 2154): proc dm_pm_timer expires
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/jxcore-log( 3276): Receiving data timeout now
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT closeClientSocket
I/jxcore-log( 3276): 
I/jxcore-log( 3276): tryAgain afer: 5000 ms.
I/jxcore-log( 3276): 
I/jxcore-log( 3276): ----------------- closeClientSocket
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT is closed
I/jxcore-log( 3276): 
,I/BtToSocketBase( 3276): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3276): Disconnect outgoing peer: HTC-HTC Desire 820_PT3126
I/BtToSocketBase( 3276): Stop ReceivingThread
I/BtToSocketBase( 3276): Stop SendingThread
I/BtToSocketBase( 3276): Close local in
I/BtToSocketBase( 3276): Close LocalOutputStream
I/BtToSocketBase( 3276): Close localHostSocket
I/BtToSocketBase( 3276): Close bt in
,I/BtToSocketBase( 3276): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3276): Close bt out
I/BtToSocketBase( 3276): Close bt socket
,I/BtToRequestSocket( 3276): Close server socket
,W/bt-btif ( 2154): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 4 peers.
I/SS      ( 3276): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3276): Peer(2): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(3): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3276): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3276): re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2154): onReceive
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: HTC Desire 820
,I/        ( 3276): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2757","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2757","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2757, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2757, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3276): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6448","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6448","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT6448, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT6448, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/        ( 3276): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8840"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8840"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8840, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8840, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3276): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT1545"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT1545"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT1545, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT1545, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 3276): Connect (retry count 2) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do connect now
I/jxcore-log( 3276): 
,I/        ( 3276): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 3276): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3276): Starting to connect
W/BluetoothAdapter( 3276): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2154): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3276): Cleared service requests
,I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,W/bt-sdp  ( 2154): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2154): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2154): invalid rfc slot id: 12
,I/BTConnectToThread( 3276): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3276): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3276): CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3276): 
I/jxcore-log( 3276): tryAgain afer: 5000 ms.
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 4 peers.
I/SS      ( 3276): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3276): Peer(2): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(3): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3276): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3276): re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3276): 
,I/        ( 3276): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT1545"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT1545"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT1545, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT1545, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 3276): Connect (retry count 3) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): do connect now
I/jxcore-log( 3276): 
,I/        ( 3276): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 3276): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3276): Starting to connect
W/BluetoothAdapter( 3276): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2154): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/SS      ( 3276): Found 4 peers.
I/SS      ( 3276): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3276): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3276): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(4): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3276): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,W/bt-btif ( 2154): info:x10
,D/        ( 2154): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 2154): process_service_search_attr_rsp
,W/bt-btif ( 2154): new conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3276): Starting to Handshake
I/BTHandshakeSocketThread( 3276): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3276): MESSAGE_WRITE 77 bytes.
,I/        ( 3276): Started service discovery
,I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread started
,I/BTConnectToThread( 3276): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 3276): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3126"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3276): HandshakeOk : HTC-HTC Desire 820_PT3126
I/HS      ( 3276): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT3126
I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3276): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT3126
I/BtToSocketBase( 3276): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3276): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3276): mHTTPPort  set to : 46835
I/BtConnectorHelper( 3276): Request socket is using : 46835
,I/BtToRequestSocket( 3276): Now accepting connections
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BtConnectorHelper( 3276): Calling ConnectionStatusUpdate with port :46835
I/jxcore-log( 3276): CLIENT connected to 46835, error: null
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT starting client 
I/jxcore-log( 3276): 
,I/BtToRequestSocket( 3276): incoming data from: /127.0.0.1, port: 46835
I/BtToRequestSocket( 3276): Set local streams
,I/BtToRequestSocket( 3276): rin ended ---------------------------;
,I/jxcore-log( 3276): CLIENT now sending 90000 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 920000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3276): CLIENT is data received : 930000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 940000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 950000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 960000
I/jxcore-log( 3276): 
,D/btif_config_util( 2154): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3276): CLIENT is data received : 970000
I/jxcore-log( 3276): 
,W/bt-btif ( 2154): dm_pm_timer expires
W/bt-btif ( 2154): dm_pm_timer expires 0
,W/bt-btif ( 2154): proc dm_pm_timer expires
,W/bt-btif ( 2154): invalid rfc slot id: 13
,E/bt-btm  ( 2154): btm_sec_disconnected - Clearing Pending flag
,I/BtToSocketBase( 3276): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3276): Disconnect outgoing peer: HTC-HTC Desire 820_PT3126
I/BtToSocketBase( 3276): Stop ReceivingThread
I/BtToSocketBase( 3276): Stop SendingThread
I/BtToSocketBase( 3276): Close local in
I/BtToSocketBase( 3276): Close LocalOutputStream
I/BtToSocketBase( 3276): Close localHostSocket
I/BtToSocketBase( 3276): Close bt in
I/BtToSocketBase( 3276): Close bt out
I/BtToSocketBase( 3276): Close bt socket
I/BtToRequestSocket( 3276): Close server socket
,I/BtToSocketBase( 3276): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3276): CLIENT is closed
I/jxcore-log( 3276): 
,D/BluetoothMapService( 2154): onReceive
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3276): Receiving data timeout now
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT closeClientSocket
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): tryAgain afer: 5000 ms.
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): ----------------- closeClientSocket
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): Connect (retry count 4) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do connect now
I/jxcore-log( 3276): 
,I/        ( 3276): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 3276): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3276): Starting to connect
W/BluetoothAdapter( 3276): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2154): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2154): info:x10
,D/        ( 2154): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,W/bt-sdp  ( 2154): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 2154): new conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3276): Starting to Handshake
I/BTHandshakeSocketThread( 3276): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3276): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread started
,I/BTConnectToThread( 3276): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 3276): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3126"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3276): HandshakeOk : HTC-HTC Desire 820_PT3126
I/HS      ( 3276): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT3126
,I/BtConnectorHelper( 3276): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT3126
I/BtToSocketBase( 3276): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3276): Creating BtConnectedRequestSocket
I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3276): mHTTPPort  set to : 36002
I/BtConnectorHelper( 3276): Request socket is using : 36002
I/BtToRequestSocket( 3276): Now accepting connections
,I/BtConnectorHelper( 3276): Calling ConnectionStatusUpdate with port :36002
,I/jxcore-log( 3276): CLIENT connected to 36002, error: null
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT starting client 
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT now sending 30000 bytes of data
I/jxcore-log( 3276): 
,I/BtToRequestSocket( 3276): incoming data from: /127.0.0.1, port: 36002
I/BtToRequestSocket( 3276): Set local streams
I/BtToRequestSocket( 3276): rin ended ---------------------------;
,I/jxcore-log( 3276): CLIENT is data received : 980000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 990000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 1000000
I/jxcore-log( 3276): 
I/jxcore-log( 3276): got all data for this round
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT Stop now
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT closeClientSocket
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT Stop now
I/jxcore-log( 3276): 
I/jxcore-log( 3276): ---- round done--------
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do fake peer & start
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3276): 
I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback round[0] time: 126237 ms, rnd: 5, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3276): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3276): Disconnect outgoing peer: HTC-HTC Desire 820_PT3126
I/BtToSocketBase( 3276): Stop ReceivingThread
I/BtToSocketBase( 3276): Stop SendingThread
I/BtToSocketBase( 3276): Close local in
I/BtToSocketBase( 3276): Close LocalOutputStream
I/BtToSocketBase( 3276): Close localHostSocket
I/BtToSocketBase( 3276): Close bt in
,I/BtToSocketBase( 3276): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3276): Close bt out
I/BtToSocketBase( 3276): Close bt socket
I/BtToRequestSocket( 3276): Close server socket
,I/jxcore-log( 3276): CLIENT is closed
I/jxcore-log( 3276): 
,W/bt-btif ( 2154): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,D/btif_config_util( 2154): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2154): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2154): onReceive
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3276): Connect (retry count 0) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do connect now
I/jxcore-log( 3276): 
,I/        ( 3276): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/        ( 3276): Connecting to null, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 3276): Starting to connect
W/BluetoothAdapter( 3276): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2154): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2154): info:x10
,D/        ( 2154): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2154): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2154): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2154): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 2154): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2154): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2154): Entering PendingCommandState State
,W/BluetoothEventManager( 2787): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2787): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,I/BluetoothBondStateMachine( 2154): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 2154): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 2154): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2154): StableState(): Entering Off State
,W/BluetoothEventManager( 2787): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2787): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,W/bt-btif ( 2154): new conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3276): Starting to Handshake
I/BTHandshakeSocketThread( 3276): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3276): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread started
,I/BTConnectToThread( 3276): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 3276): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7881"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3276): HandshakeOk : motorola-XT1039_PT7881
I/HS      ( 3276): Hand Shake finished outgoing for : motorola-XT1039_PT7881
,I/BtConnectorHelper( 3276): Starting the connected thread incoming : false, motorola-XT1039_PT7881
I/BtToSocketBase( 3276): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3276): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3276): mHTTPPort  set to : 45977
I/BtConnectorHelper( 3276): Request socket is using : 45977
I/BtToRequestSocket( 3276): Now accepting connections
,I/BtConnectorHelper( 3276): Calling ConnectionStatusUpdate with port :45977
I/jxcore-log( 3276): CLIENT connected to 45977, error: null
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT starting client 
I/jxcore-log( 3276): 
,I/BtToRequestSocket( 3276): incoming data from: /127.0.0.1, port: 45977
I/BtToRequestSocket( 3276): Set local streams
I/BtToRequestSocket( 3276): rin ended ---------------------------;
,I/jxcore-log( 3276): CLIENT now sending 1000000 bytes of data
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:76970
I/jxcore-log( 3276): CLIENT is data received : 10000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 20000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71166
,I/jxcore-log( 3276): CLIENT is data received : 30000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72428
,I/jxcore-log( 3276): CLIENT is data received : 40000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 50000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72700
,I/jxcore-log( 3276): CLIENT is data received : 60000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72972
,I/jxcore-log( 3276): CLIENT is data received : 70000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 80000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74234
,I/jxcore-log( 3276): CLIENT is data received : 90000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69420
,I/jxcore-log( 3276): CLIENT is data received : 100000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 110000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74778
,I/jxcore-log( 3276): CLIENT is data received : 120000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68974
,I/jxcore-log( 3276): CLIENT is data received : 120000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74332
,I/jxcore-log( 3276): CLIENT is data received : 130000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71498
,I/jxcore-log( 3276): CLIENT is data received : 130000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73750
,I/jxcore-log( 3276): CLIENT is data received : 140000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68936
,I/jxcore-log( 3276): CLIENT is data received : 150000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 160000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:75284
,I/jxcore-log( 3276): CLIENT is data received : 170000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71460
,I/jxcore-log( 3276): CLIENT is data received : 180000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 190000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70742
,I/jxcore-log( 3276): CLIENT is data received : 200000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72004
,I/jxcore-log( 3276): CLIENT is data received : 210000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 220000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74256
,I/jxcore-log( 3276): CLIENT is data received : 230000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70432
,I/jxcore-log( 3276): CLIENT is data received : 240000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 250000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70704
,I/jxcore-log( 3276): CLIENT is data received : 260000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69986
,I/jxcore-log( 3276): CLIENT is data received : 270000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 280000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71248
,I/jxcore-log( 3276): CLIENT is data received : 290000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 300000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67560
,I/jxcore-log( 3276): CLIENT is data received : 310000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 320000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72918
,I/jxcore-log( 3276): CLIENT is data received : 330000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 340000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70220
,I/jxcore-log( 3276): CLIENT is data received : 350000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71482
,I/jxcore-log( 3276): CLIENT is data received : 360000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 370000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72744
,I/jxcore-log( 3276): CLIENT is data received : 380000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71036
,I/jxcore-log( 3276): CLIENT is data received : 390000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 400000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74278
,I/jxcore-log( 3276): CLIENT is data received : 410000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68474
,I/jxcore-log( 3276): CLIENT is data received : 420000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 430000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:56594
,I/jxcore-log( 3276): CLIENT is data received : 440000
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT is data received : 450000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72260
,I/jxcore-log( 3276): CLIENT is data received : 460000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 470000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74512
,I/jxcore-log( 3276): CLIENT is data received : 480000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 490000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68708
,I/jxcore-log( 3276): CLIENT is data received : 500000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73076
,I/jxcore-log( 3276): CLIENT is data received : 510000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 520000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73348
,I/jxcore-log( 3276): CLIENT is data received : 530000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 540000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69660
,I/jxcore-log( 3276): CLIENT is data received : 550000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73892
I/jxcore-log( 3276): CLIENT is data received : 560000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71058
,I/jxcore-log( 3276): CLIENT is data received : 570000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 580000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73310
,I/jxcore-log( 3276): CLIENT is data received : 590000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 600000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69622
,I/jxcore-log( 3276): CLIENT is data received : 610000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 620000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73990
,I/jxcore-log( 3276): CLIENT is data received : 630000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 640000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:66206
,I/jxcore-log( 3276): CLIENT is data received : 650000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74534
,I/jxcore-log( 3276): CLIENT is data received : 660000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70710
,I/jxcore-log( 3276): CLIENT is data received : 670000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 680000
I/jxcore-log( 3276): 
,D/btif_config_util( 2154): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72962
,I/jxcore-log( 3276): CLIENT is data received : 690000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 700000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69274
,I/jxcore-log( 3276): CLIENT is data received : 710000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:78592
,I/jxcore-log( 3276): CLIENT is data received : 720000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70672
,I/jxcore-log( 3276): CLIENT is data received : 730000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 740000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71934
,I/jxcore-log( 3276): CLIENT is data received : 750000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 760000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69236
,I/jxcore-log( 3276): CLIENT is data received : 770000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70787
,I/jxcore-log( 3276): CLIENT is data received : 780000
I/jxcore-log( 3276): 
,I/art     ( 2154): Explicit concurrent mark sweep GC freed 27695(1366KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 15MB/26MB, paused 615us total 80.364ms
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:60887
,I/jxcore-log( 3276): CLIENT is data received : 780000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 790000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:50987
,I/jxcore-log( 3276): CLIENT is data received : 800000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:46037
,I/jxcore-log( 3276): CLIENT is data received : 810000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:38117
,I/jxcore-log( 3276): CLIENT is data received : 820000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 830000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:33167
,I/jxcore-log( 3276): CLIENT is data received : 840000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:26237
,I/jxcore-log( 3276): CLIENT is data received : 850000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19307
,I/jxcore-log( 3276): CLIENT is data received : 860000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 870000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12377
,I/jxcore-log( 3276): CLIENT is data received : 880000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:5447
,I/jxcore-log( 3276): CLIENT is data received : 890000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 900000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 910000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 920000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 930000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 940000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 950000
I/jxcore-log( 3276): 
,W/bt-btif ( 2154): dm_pm_timer expires
W/bt-btif ( 2154): dm_pm_timer expires 0
,W/bt-btif ( 2154): proc dm_pm_timer expires
,I/jxcore-log( 3276): Receiving data timeout now
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT closeClientSocket
I/jxcore-log( 3276): 
,I/BtToSocketBase( 3276): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3276): Disconnect outgoing peer: motorola-XT1039_PT7881
,I/BtToSocketBase( 3276): Stop ReceivingThread
I/BtToSocketBase( 3276): Stop SendingThread
I/BtToSocketBase( 3276): Close local in
,I/BtToSocketBase( 3276): Close LocalOutputStream
I/BtToSocketBase( 3276): Close localHostSocket
I/BtToSocketBase( 3276): Close bt in
,I/BtToSocketBase( 3276): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3276): Close bt out
I/BtToSocketBase( 3276): Close bt socket
I/BtToRequestSocket( 3276): Close server socket
,I/jxcore-log( 3276): tryAgain afer: 5000 ms.
I/jxcore-log( 3276): 
I/jxcore-log( 3276): ----------------- closeClientSocket
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT is closed
I/jxcore-log( 3276): 
,W/bt-btif ( 2154): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,I/jxcore-log( 3276): re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2154): onReceive
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: XT1039
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/        ( 3276): Cleared service requests
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 4 peers.
I/SS      ( 3276): Peer(1): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3276): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3276): Peer(3): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3276): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3276): Added service request
,I/jxcore-log( 3276): Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do connect now
I/jxcore-log( 3276): 
,I/        ( 3276): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 3276): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 3276): Starting to connect
W/BluetoothAdapter( 3276): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2154): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2154): info:x10
,D/        ( 2154): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 2154): process_service_search_attr_rsp
,W/bt-btif ( 2154): new conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3276): Starting to Handshake
I/BTHandshakeSocketThread( 3276): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3276): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread started
,I/BTConnectToThread( 3276): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 3276): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7881"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3276): HandshakeOk : motorola-XT1039_PT7881
I/HS      ( 3276): Hand Shake finished outgoing for : motorola-XT1039_PT7881
I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3276): Starting the connected thread incoming : false, motorola-XT1039_PT7881
I/BtToSocketBase( 3276): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3276): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3276): mHTTPPort  set to : 38956
,I/BtConnectorHelper( 3276): Request socket is using : 38956
I/BtToRequestSocket( 3276): Now accepting connections
,I/BtConnectorHelper( 3276): Calling ConnectionStatusUpdate with port :38956
I/jxcore-log( 3276): CLIENT connected to 38956, error: null
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT starting client 
I/jxcore-log( 3276): 
,I/BtToRequestSocket( 3276): incoming data from: /127.0.0.1, port: 38956
I/BtToRequestSocket( 3276): Set local streams
,I/BtToRequestSocket( 3276): rin ended ---------------------------;
,I/jxcore-log( 3276): CLIENT now sending 50000 bytes of data
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:3667
,I/jxcore-log( 3276): CLIENT is data received : 960000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 970000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 980000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 990000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 1000000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): got all data for this round
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT Stop now
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT closeClientSocket
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT Stop now
I/jxcore-log( 3276): 
I/jxcore-log( 3276): ---- round done--------
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do fake peer & start
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3276): 
I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback round[0] time: 38924 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3276): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3276): Disconnect outgoing peer: motorola-XT1039_PT7881
I/BtToSocketBase( 3276): Stop ReceivingThread
I/BtToSocketBase( 3276): Stop SendingThread
I/BtToSocketBase( 3276): Close local in
I/BtToSocketBase( 3276): Close LocalOutputStream
I/BtToSocketBase( 3276): Close localHostSocket
I/BtToSocketBase( 3276): Close bt in
,I/BtToSocketBase( 3276): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3276): Close bt out
I/BtToSocketBase( 3276): Close bt socket
I/BtToRequestSocket( 3276): Close server socket
,W/bt-btif ( 2154): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,I/jxcore-log( 3276): CLIENT is closed
I/jxcore-log( 3276): 
,I/        ( 3276): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT575","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT575","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT575, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT575, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2154): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2154): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2154): onReceive
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: XT1039
,I/jxcore-log( 3276): Connect (retry count 0) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do connect now
I/jxcore-log( 3276): 
,I/        ( 3276): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3276): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3276): Starting to connect
,W/BluetoothAdapter( 3276): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2154): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2154): info:x10
,D/        ( 2154): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2154): aclStateChangeCallback: Device is NULL
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,W/bt-sdp  ( 2154): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2154): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
E/bt-btif ( 2154): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2154): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2154): Entering PendingCommandState State
,W/BluetoothEventManager( 2787): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 2787): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,I/BluetoothBondStateMachine( 2154): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 2154): Failed to remove device: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 2154): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2154): StableState(): Entering Off State
,W/BluetoothEventManager( 2787): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 2787): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,W/bt-btif ( 2154): new conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3276): Starting to Handshake
,I/BTHandshakeSocketThread( 3276): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3276): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread started
,I/BTConnectToThread( 3276): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3276): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8840"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3276): HandshakeOk : samsung-SM-G800F_PT8840
I/HS      ( 3276): Hand Shake finished outgoing for : samsung-SM-G800F_PT8840
I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3276): Starting the connected thread incoming : false, samsung-SM-G800F_PT8840
I/BtToSocketBase( 3276): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3276): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3276): mHTTPPort  set to : 60974
I/BtConnectorHelper( 3276): Request socket is using : 60974
I/BtToRequestSocket( 3276): Now accepting connections
,I/BtConnectorHelper( 3276): Calling ConnectionStatusUpdate with port :60974
,I/jxcore-log( 3276): CLIENT connected to 60974, error: null
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT starting client 
I/jxcore-log( 3276): 
,I/BtToRequestSocket( 3276): incoming data from: /127.0.0.1, port: 60974
I/BtToRequestSocket( 3276): Set local streams
I/BtToRequestSocket( 3276): rin ended ---------------------------;
,I/jxcore-log( 3276): CLIENT now sending 1000000 bytes of data
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71030
,I/jxcore-log( 3276): CLIENT is data received : 10000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 20000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69322
,I/jxcore-log( 3276): CLIENT is data received : 30000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 40000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68740
,I/jxcore-log( 3276): CLIENT is data received : 50000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 60000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71128
,I/jxcore-log( 3276): CLIENT is data received : 70000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 80000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68430
,I/jxcore-log( 3276): CLIENT is data received : 90000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3276): CLIENT is data received : 100000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3276): Found 5 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3276): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3276): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3276): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68838
,I/jxcore-log( 3276): CLIENT is data received : 110000
I/jxcore-log( 3276): 
,I/        ( 3276): Started service discovery
,I/jxcore-log( 3276): CLIENT is data received : 110000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67266
,I/jxcore-log( 3276): CLIENT is data received : 120000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3276): CLIENT is data received : 130000
I/jxcore-log( 3276): 
,D/btif_config_util( 2154): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70644
,I/jxcore-log( 3276): CLIENT is data received : 140000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 150000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68936
,I/jxcore-log( 3276): CLIENT is data received : 160000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:64394
,I/jxcore-log( 3276): CLIENT is data received : 160000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3276): CLIENT is data received : 170000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71868
,I/jxcore-log( 3276): CLIENT is data received : 180000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 190000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71150
,I/jxcore-log( 3276): CLIENT is data received : 200000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3276): CLIENT is data received : 210000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:57562
,I/jxcore-log( 3276): CLIENT is data received : 210000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 220000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69132
,I/jxcore-log( 3276): CLIENT is data received : 230000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3276): CLIENT is data received : 240000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71520
,I/jxcore-log( 3276): CLIENT is data received : 250000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3276): CLIENT is data received : 260000
I/jxcore-log( 3276): 
,I/        ( 3276): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9121","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9121","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9121, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9121, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:58922
,I/jxcore-log( 3276): CLIENT is data received : 260000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3276): CLIENT is data received : 270000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70492
,I/jxcore-log( 3276): CLIENT is data received : 280000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 290000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68784
,I/jxcore-log( 3276): CLIENT is data received : 300000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3276): CLIENT is data received : 310000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:60282
,I/jxcore-log( 3276): CLIENT is data received : 310000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3276): CLIENT is data received : 320000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70862
,I/jxcore-log( 3276): CLIENT is data received : 330000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3276): CLIENT is data received : 340000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69154
,I/jxcore-log( 3276): CLIENT is data received : 350000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/jxcore-log( 3276): CLIENT is data received : 360000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 9 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3276): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3276): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:61642
,I/jxcore-log( 3276): CLIENT is data received : 360000
I/jxcore-log( 3276): 
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3276): CLIENT is data received : 370000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68126
,I/jxcore-log( 3276): CLIENT is data received : 380000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3276): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5538","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5538","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT5538, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT5538, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 3276): CLIENT is data received : 390000
I/jxcore-log( 3276): 
,I/        ( 3276): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9121","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9121","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9121, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9121, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69524
,I/jxcore-log( 3276): CLIENT is data received : 400000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 410000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:63002
,I/jxcore-log( 3276): CLIENT is data received : 410000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 420000
I/jxcore-log( 3276): 
,I/        ( 3276): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7881"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7881"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT7881, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT7881, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69486
,I/jxcore-log( 3276): CLIENT is data received : 430000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 440000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71874
,I/jxcore-log( 3276): CLIENT is data received : 450000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 460000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:60266
,I/jxcore-log( 3276): CLIENT is data received : 460000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 470000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72826
,I/jxcore-log( 3276): CLIENT is data received : 480000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 490000
I/jxcore-log( 3276): 
I/        ( 3276): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT575","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT575","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT575, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT575, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73098
,I/jxcore-log( 3276): CLIENT is data received : 500000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 510000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:57530
,I/jxcore-log( 3276): CLIENT is data received : 510000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 520000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:64167
,I/jxcore-log( 3276): CLIENT is data received : 530000
I/jxcore-log( 3276): 
,I/        ( 3276): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9704","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9704","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT9704, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT9704, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3276): CLIENT is data received : 540000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:54267
,I/jxcore-log( 3276): CLIENT is data received : 550000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 560000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:30507
,I/jxcore-log( 3276): CLIENT is data received : 560000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 570000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:22587
,I/jxcore-log( 3276): CLIENT is data received : 580000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 590000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13677
,I/jxcore-log( 3276): CLIENT is data received : 600000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 610000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 610000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 620000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 630000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 640000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 650000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 660000
I/jxcore-log( 3276): 
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/jxcore-log( 3276): CLIENT is data received : 660000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 670000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 9 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3276): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3276): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2154): dm_pm_timer expires
W/bt-btif ( 2154): dm_pm_timer expires 0
W/bt-btif ( 2154): proc dm_pm_timer expires
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 2154): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HeadsetStateMachine( 2154): Disconnected process message: 11, size: 0
,W/bt-btif ( 2154): info:x10
,D/        ( 2154): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2154): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3276): Receiving data timeout now
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT closeClientSocket
I/jxcore-log( 3276): 
,I/BtToSocketBase( 3276): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3276): Disconnect outgoing peer: samsung-SM-G800F_PT8840
I/BtToSocketBase( 3276): Stop ReceivingThread
I/BtToSocketBase( 3276): Stop SendingThread
I/BtToSocketBase( 3276): Close local in
I/BtToSocketBase( 3276): Close LocalOutputStream
I/BtToSocketBase( 3276): Close localHostSocket
I/BtToSocketBase( 3276): Close bt in
,I/BtToSocketBase( 3276): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3276): Close bt out
I/BtToSocketBase( 3276): Close bt socket
I/BtToRequestSocket( 3276): Close server socket
,I/jxcore-log( 3276): tryAgain afer: 5000 ms.
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): ----------------- closeClientSocket
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT is closed
I/jxcore-log( 3276): 
,I/BluetoothBondStateMachine( 2154): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2154): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2154): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2154): Entering PendingCommandState State
,W/BluetoothEventManager( 2787): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2787): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2154): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2154): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2154): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2154): StableState(): Entering Off State
,W/BluetoothEventManager( 2787): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2787): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 2154): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,W/bt-btif ( 2154): new conn_srvc id:26, app_id:255
W/bt-btif ( 2154): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2154): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3276): we got incoming connection
I/BTHandshakeSocketThread( 3276): Creating BTHandshakeSocketThread
I/BTListenerThread( 3276): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread started
,I/BTListenerThread( 3276): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3276): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9121","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3276): MESSAGE_WRITE 77 bytes.
I/HS      ( 3276): Incoming connection Hand Shake finished for : LGE-LG-D722_PT9121
,I/BtConnectorHelper( 3276): Starting the connected thread incoming : true, LGE-LG-D722_PT9121
I/BtToSocketBase( 3276): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3276): Creating BTConnectedThread
I/BtConnectorHelper( 3276): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3276): --DoOneRunRound started
,I/jxcore-log( 3276): TCP/IP server connected
I/jxcore-log( 3276): 
,I/BtToRequestSocket( 3276): LocalHost address: localhost/127.0.0.1, port: 48644
,I/BtToRequestSocket( 3276): --DoOneRunRound ended
,I/jxcore-log( 3276): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 26012 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 27992 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 33932 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 37892 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 41852 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 45812 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 47792 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 49772 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 59672 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 61652 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 67592 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 69572 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 71552 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 73532 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 75512 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 77492 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 79472 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 81452 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 83432 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 85412 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 87392 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 89372 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 93332 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 95312 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 97292 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 101252 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 105212 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 111152 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 113132 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 119072 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 123032 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 125012 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 134912 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 136892 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 140852 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 142832 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 146792 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 148772 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 150752 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 152732 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 160652 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 162632 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 164612 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 166592 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 168572 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 170552 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 180452 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 182432 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 190352 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 192332 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 198272 bytes of data
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2154): onReceive
,I/jxcore-log( 3276): TCP/IP server has received 200252 bytes of data
I/jxcore-log( 3276): 
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/jxcore-log( 3276): TCP/IP server has received 204212 bytes of data
I/jxcore-log( 3276): 
,I/BluetoothClassifier( 1427): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 3276): TCP/IP server has received 206192 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 220052 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 222032 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 224012 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 229952 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 241832 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 243812 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 245792 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 253712 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 255692 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 265592 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 267572 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 279452 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 281432 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 285392 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 293312 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 301232 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 305192 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 309152 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 311132 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 313112 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 315092 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 324992 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 326972 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 338852 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 340832 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 344792 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 350732 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 352712 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 364592 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 366572 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 378452 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 380432 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 384392 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 400232 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 402212 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 404192 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 406172 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 414092 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 416072 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 423992 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 425972 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 439832 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3276): 
I/jxcore-log( 3276): TCP/IP server has received 443792 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 445772 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 457652 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 459632 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 465572 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 467552 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 473492 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 475472 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 481412 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 483392 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 491312 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 493292 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 501212 bytes of data
I/jxcore-log( 3276): 
,D/btif_config_util( 2154): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3276): TCP/IP server has received 503192 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 513092 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 515072 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 521012 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 522992 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 532892 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 534872 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 544772 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 546752 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 554672 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 556652 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 562592 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 564572 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 572492 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 574472 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 584372 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 586352 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 590312 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 592292 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 594272 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 604172 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 606152 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 618032 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 620012 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 623972 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 631892 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 640084 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 643772 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 645752 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 647732 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 653672 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 655652 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 663572 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 665552 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 675452 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 677432 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 683372 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 687332 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 707132 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 709112 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 711092 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 719012 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 732872 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 734852 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 738812 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 756632 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 758612 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 764552 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 770492 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 778412 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 796232 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 798212 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 800192 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 802172 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 814052 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 816032 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 833852 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 835832 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 837812 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 857612 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 859592 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 861572 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 863552 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 875432 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 879392 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 891272 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 893252 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 895232 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 911072 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 913052 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 917012 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 932852 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 934832 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 940772 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 948692 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 966512 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 976412 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 982352 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 988292 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 992252 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 994232 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 1000002 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): do connect now
I/jxcore-log( 3276): 
,I/        ( 3276): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3276): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3276): Starting to connect
W/BluetoothAdapter( 3276): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2154): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2154): info:x10
,D/        ( 2154): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: S5mini-1
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2154): process_service_search_attr_rsp
,W/bt-btif ( 2154): new conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3276): Starting to Handshake
,I/BTHandshakeSocketThread( 3276): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3276): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread started
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3276): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3276): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8840"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3276): HandshakeOk : samsung-SM-G800F_PT8840
I/HS      ( 3276): Hand Shake finished outgoing for : samsung-SM-G800F_PT8840
I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3276): Starting the connected thread incoming : false, samsung-SM-G800F_PT8840
I/BtToSocketBase( 3276): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3276): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3276): mHTTPPort  set to : 40512
I/BtConnectorHelper( 3276): Request socket is using : 40512
,I/BtToRequestSocket( 3276): Now accepting connections
,I/BtConnectorHelper( 3276): Calling ConnectionStatusUpdate with port :40512
I/jxcore-log( 3276): CLIENT connected to 40512, error: null
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT starting client 
I/jxcore-log( 3276): 
,I/BtToRequestSocket( 3276): incoming data from: /127.0.0.1, port: 40512
I/BtToRequestSocket( 3276): Set local streams
I/BtToRequestSocket( 3276): rin ended ---------------------------;
,I/jxcore-log( 3276): CLIENT now sending 330000 bytes of data
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70040
,I/jxcore-log( 3276): CLIENT is data received : 680000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 690000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69322
,I/jxcore-log( 3276): CLIENT is data received : 700000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 710000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71710
,I/jxcore-log( 3276): CLIENT is data received : 720000
I/jxcore-log( 3276): 
,D/btif_config_util( 2154): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3276): CLIENT is data received : 730000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68022
,I/jxcore-log( 3276): CLIENT is data received : 740000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 750000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68430
,I/jxcore-log( 3276): CLIENT is data received : 760000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 770000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:63787
,I/jxcore-log( 3276): CLIENT is data received : 780000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:51907
,I/jxcore-log( 3276): CLIENT is data received : 780000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 790000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:43987
,I/jxcore-log( 3276): CLIENT is data received : 800000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 810000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:34087
,I/jxcore-log( 3276): CLIENT is data received : 820000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 830000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12307
,I/jxcore-log( 3276): CLIENT is data received : 830000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 840000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1417
,I/jxcore-log( 3276): CLIENT is data received : 850000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 860000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 870000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 880000
I/jxcore-log( 3276): 
,W/bt-btif ( 2154): invalid rfc slot id: 4
,I/BtToSocketBase( 3276): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3276): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3276): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT9121
I/BtToSocketBase( 3276): Stop ReceivingThread
I/BtToSocketBase( 3276): Stop SendingThread
I/BtToSocketBase( 3276): Close local in
I/BtToSocketBase( 3276): Close LocalOutputStream
I/BtToSocketBase( 3276): Close localHostSocket
I/BtToSocketBase( 3276): Close bt in
I/BtToSocketBase( 3276): Close bt out
I/BtToSocketBase( 3276): Close bt socket
,I/BtToSocketBase( 3276): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3276): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3276): TCP/IP server is ended
I/jxcore-log( 3276): 
I/jxcore-log( 3276): TCP/IP server is close
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2154): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
W/bt-rfcomm( 2154): RFCOMM_DisconnectInd LCID:0x4f
,I/jxcore-log( 3276): CLIENT is data received : 880000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 890000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 900000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 910000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 920000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 930000
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2154): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2154): onReceive
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: G3s-1
,W/bt-btif ( 2154): dm_pm_timer expires
W/bt-btif ( 2154): dm_pm_timer expires 0
,W/bt-btif ( 2154): proc dm_pm_timer expires
,W/bt-btif ( 2154): info:x10
,D/        ( 2154): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: G3s-1
,I/BluetoothBondStateMachine( 2154): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2154): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2154): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2154): Entering PendingCommandState State
,W/BluetoothEventManager( 2787): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2787): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 2154): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2154): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2154): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2154): StableState(): Entering Off State
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
,W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,W/BluetoothEventManager( 2787): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2787): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 2154): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2154): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2154): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3276): we got incoming connection
I/BTHandshakeSocketThread( 3276): Creating BTHandshakeSocketThread
I/BTListenerThread( 3276): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread started
,I/BTListenerThread( 3276): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3276): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9121","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3276): MESSAGE_WRITE 77 bytes.
I/HS      ( 3276): Incoming connection Hand Shake finished for : LGE-LG-D722_PT9121
I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3276): Starting the connected thread incoming : true, LGE-LG-D722_PT9121
I/BtToSocketBase( 3276): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3276): Creating BTConnectedThread
I/BtConnectorHelper( 3276): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3276): --DoOneRunRound started
,I/BtToRequestSocket( 3276): LocalHost address: localhost/127.0.0.1, port: 48644
,I/jxcore-log( 3276): TCP/IP server connected
I/jxcore-log( 3276): 
,I/BtToRequestSocket( 3276): --DoOneRunRound ended
,I/jxcore-log( 3276): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 50002 bytes of data
I/jxcore-log( 3276): 
,W/bt-btif ( 2154): invalid rfc slot id: 18
,I/BtToSocketBase( 3276): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3276): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3276): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT9121
I/BtToSocketBase( 3276): Stop ReceivingThread
I/BtToSocketBase( 3276): Stop SendingThread
I/BtToSocketBase( 3276): Close local in
I/BtToSocketBase( 3276): Close LocalOutputStream
I/BtToSocketBase( 3276): Close localHostSocket
I/BtToSocketBase( 3276): Close bt in
I/BtToSocketBase( 3276): Close bt out
I/BtToSocketBase( 3276): Close bt socket
,I/BtToSocketBase( 3276): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3276): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3276): TCP/IP server is ended
I/jxcore-log( 3276): 
I/jxcore-log( 3276): TCP/IP server is close
I/jxcore-log( 3276): 
,W/bt-rfcomm( 2154): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
W/bt-rfcomm( 2154): RFCOMM_DisconnectInd LCID:0x43
,I/jxcore-log( 3276): Receiving data timeout now
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT closeClientSocket
I/jxcore-log( 3276): 
,I/BtToSocketBase( 3276): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3276): Disconnect outgoing peer: samsung-SM-G800F_PT8840
I/BtToSocketBase( 3276): Stop ReceivingThread
I/BtToSocketBase( 3276): Stop SendingThread
I/BtToSocketBase( 3276): Close local in
I/BtToSocketBase( 3276): Close LocalOutputStream
I/BtToSocketBase( 3276): Close localHostSocket
I/BtToSocketBase( 3276): Close bt in
,I/BtToSocketBase( 3276): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3276): Close bt out
I/BtToSocketBase( 3276): Close bt socket
I/BtToRequestSocket( 3276): Close server socket
,I/jxcore-log( 3276): tryAgain afer: 5000 ms.
I/jxcore-log( 3276): 
I/jxcore-log( 3276): ----------------- closeClientSocket
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT is closed
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2154): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,D/btif_config_util( 2154): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2154): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2154): onReceive
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 2154): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2154): onReceive
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 3276): re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do connect now
I/jxcore-log( 3276): 
,I/        ( 3276): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3276): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3276): Starting to connect
W/BluetoothAdapter( 3276): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2154): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2154): info:x10
,D/        ( 2154): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 2154): process_service_search_attr_rsp
,W/bt-btif ( 2154): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2154): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3276): Starting to Handshake
I/BTHandshakeSocketThread( 3276): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3276): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread started
,I/BTConnectToThread( 3276): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3276): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8840"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3276): HandshakeOk : samsung-SM-G800F_PT8840
I/HS      ( 3276): Hand Shake finished outgoing for : samsung-SM-G800F_PT8840
I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3276): Starting the connected thread incoming : false, samsung-SM-G800F_PT8840
I/BtToSocketBase( 3276): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3276): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3276): mHTTPPort  set to : 38073
I/BtConnectorHelper( 3276): Request socket is using : 38073
I/BtToRequestSocket( 3276): Now accepting connections
,I/BtConnectorHelper( 3276): Calling ConnectionStatusUpdate with port :38073
I/jxcore-log( 3276): CLIENT connected to 38073, error: null
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT starting client 
I/jxcore-log( 3276): 
,I/BtToRequestSocket( 3276): incoming data from: /127.0.0.1, port: 38073
I/BtToRequestSocket( 3276): Set local streams
I/BtToRequestSocket( 3276): rin ended ---------------------------;
,I/jxcore-log( 3276): CLIENT now sending 70000 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 940000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 950000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 960000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 970000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 980000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 990000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 1000000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): got all data for this round
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT Stop now
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT closeClientSocket
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT Stop now
I/jxcore-log( 3276): 
I/jxcore-log( 3276): ---- round done--------
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do fake peer & start
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 3276): 
I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback round[0] time: 95801 ms, rnd: 3, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3276): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3276): Disconnect outgoing peer: samsung-SM-G800F_PT8840
I/BtToSocketBase( 3276): Stop ReceivingThread
I/BtToSocketBase( 3276): Stop SendingThread
I/BtToSocketBase( 3276): Close local in
I/BtToSocketBase( 3276): Close LocalOutputStream
I/BtToSocketBase( 3276): Close localHostSocket
I/BtToSocketBase( 3276): Close bt in
,I/BtToSocketBase( 3276): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3276): Close bt out
I/BtToSocketBase( 3276): Close bt socket
I/BtToRequestSocket( 3276): Close server socket
,I/jxcore-log( 3276): CLIENT is closed
I/jxcore-log( 3276): 
,W/bt-btif ( 2154): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,D/btif_config_util( 2154): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2154): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2154): onReceive
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: S5mini-1
,I/art     (  758): Explicit concurrent mark sweep GC freed 28706(1546KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 3.254ms total 126.959ms
,I/jxcore-log( 3276): Connect (retry count 0) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do connect now
I/jxcore-log( 3276): 
,I/        ( 3276): Selected device address: F8:CF:C5:D9:E5:61, name: null
,I/        ( 3276): Connecting to null, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 3276): Starting to connect
W/BluetoothAdapter( 3276): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2154): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2154): info:x10
,D/        ( 2154): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 2154): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2154): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2154): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
E/bt-btif ( 2154): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2154): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2154): Entering PendingCommandState State
,W/BluetoothEventManager( 2787): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2787): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,I/BluetoothBondStateMachine( 2154): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,D/BluetoothAdapterProperties( 2154): Failed to remove device: F8:CF:C5:D9:E5:61
,I/BluetoothBondStateMachine( 2154): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2154): StableState(): Entering Off State
,W/BluetoothEventManager( 2787): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2787): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,W/bt-btif ( 2154): new conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3276): Starting to Handshake
I/BTHandshakeSocketThread( 3276): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3276): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread started
,I/BTConnectToThread( 3276): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3276): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3617","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3276): HandshakeOk : motorola-Nexus 6_PT3617
I/HS      ( 3276): Hand Shake finished outgoing for : motorola-Nexus 6_PT3617
I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3276): Starting the connected thread incoming : false, motorola-Nexus 6_PT3617
I/BtToSocketBase( 3276): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3276): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3276): mHTTPPort  set to : 39709
I/BtConnectorHelper( 3276): Request socket is using : 39709
I/BtToRequestSocket( 3276): Now accepting connections
,I/BtConnectorHelper( 3276): Calling ConnectionStatusUpdate with port :39709
I/jxcore-log( 3276): CLIENT connected to 39709, error: null
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT starting client 
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT now sending 1000000 bytes of data
I/jxcore-log( 3276): 
,I/BtToRequestSocket( 3276): incoming data from: /127.0.0.1, port: 39709
I/BtToRequestSocket( 3276): Set local streams
I/BtToRequestSocket( 3276): rin ended ---------------------------;
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:75980
,I/jxcore-log( 3276): CLIENT is data received : 10000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70176
,I/jxcore-log( 3276): CLIENT is data received : 20000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71438
,I/jxcore-log( 3276): CLIENT is data received : 20000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 30000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68740
,I/jxcore-log( 3276): CLIENT is data received : 30000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71128
,I/jxcore-log( 3276): CLIENT is data received : 40000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:77340
,I/jxcore-log( 3276): CLIENT is data received : 50000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73516
,I/jxcore-log( 3276): CLIENT is data received : 60000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 70000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71808
,I/jxcore-log( 3276): CLIENT is data received : 80000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 90000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73070
,I/jxcore-log( 3276): CLIENT is data received : 100000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74332
,I/jxcore-log( 3276): CLIENT is data received : 110000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68528
,I/jxcore-log( 3276): CLIENT is data received : 110000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73886
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:76002
,I/jxcore-log( 3276): CLIENT is data received : 120000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 130000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71188
,I/jxcore-log( 3276): CLIENT is data received : 140000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 150000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72450
,I/jxcore-log( 3276): CLIENT is data received : 160000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 170000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71732
,I/jxcore-log( 3276): CLIENT is data received : 180000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72994
,I/jxcore-log( 3276): CLIENT is data received : 190000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74256
,I/jxcore-log( 3276): CLIENT is data received : 200000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 210000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69442
,I/jxcore-log( 3276): CLIENT is data received : 220000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 230000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73810
,I/jxcore-log( 3276): CLIENT is data received : 240000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69986
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:75208
,I/jxcore-log( 3276): CLIENT is data received : 250000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 260000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 270000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68414
,I/jxcore-log( 3276): CLIENT is data received : 280000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74762
,I/jxcore-log( 3276): CLIENT is data received : 290000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 300000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71928
,I/jxcore-log( 3276): CLIENT is data received : 310000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 320000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68240
,I/jxcore-log( 3276): CLIENT is data received : 330000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 340000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73598
,I/jxcore-log( 3276): CLIENT is data received : 350000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74860
,I/jxcore-log( 3276): CLIENT is data received : 360000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69056
,I/jxcore-log( 3276): CLIENT is data received : 370000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 380000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 390000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73424
,I/jxcore-log( 3276): CLIENT is data received : 400000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 410000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69736
,I/jxcore-log( 3276): CLIENT is data received : 420000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 430000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69018
,I/jxcore-log( 3276): CLIENT is data received : 440000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:77346
,I/jxcore-log( 3276): CLIENT is data received : 450000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74512
,I/jxcore-log( 3276): CLIENT is data received : 460000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68708
,I/jxcore-log( 3276): CLIENT is data received : 470000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 480000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 490000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72086
,I/jxcore-log( 3276): CLIENT is data received : 500000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 510000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69388
,I/jxcore-log( 3276): CLIENT is data received : 520000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73756
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73892
,I/jxcore-log( 3276): CLIENT is data received : 530000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 540000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 550000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:66108
,I/jxcore-log( 3276): CLIENT is data received : 560000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:75426
,I/jxcore-log( 3276): CLIENT is data received : 570000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 580000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71602
,I/jxcore-log( 3276): CLIENT is data received : 590000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 600000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68904
,I/jxcore-log( 3276): CLIENT is data received : 610000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:76242
,I/jxcore-log( 3276): CLIENT is data received : 620000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71428
,I/jxcore-log( 3276): CLIENT is data received : 630000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 640000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 650000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67740
,I/jxcore-log( 3276): CLIENT is data received : 660000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73098
,I/jxcore-log( 3276): CLIENT is data received : 670000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 680000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74360
,I/jxcore-log( 3276): CLIENT is data received : 690000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71526
,I/jxcore-log( 3276): CLIENT is data received : 700000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72788
,I/jxcore-log( 3276): CLIENT is data received : 710000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 720000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:75040
,I/jxcore-log( 3276): CLIENT is data received : 730000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 740000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70226
,I/jxcore-log( 3276): CLIENT is data received : 750000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71488
,I/jxcore-log( 3276): CLIENT is data received : 760000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 770000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:60887
,I/jxcore-log( 3276): CLIENT is data received : 780000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 790000
I/jxcore-log( 3276): 
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:51977
,I/jxcore-log( 3276): CLIENT is data received : 800000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:48017
,I/jxcore-log( 3276): CLIENT is data received : 810000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 820000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:38117
,I/jxcore-log( 3276): CLIENT is data received : 830000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:33167
,I/jxcore-log( 3276): CLIENT is data received : 840000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 850000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23267
,I/jxcore-log( 3276): CLIENT is data received : 860000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18317
,I/jxcore-log( 3276): CLIENT is data received : 870000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3276): CLIENT is data received : 880000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 9 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3276): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(4): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3276): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3276): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3276): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8417
,I/jxcore-log( 3276): CLIENT is data received : 890000
I/jxcore-log( 3276): 
D/WifiP2pManager( 3276): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,D/btif_config_util( 2154): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3276): CLIENT is data received : 900000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 3276): CLIENT is data received : 910000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3276): CLIENT is data received : 920000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Started service discovery
,I/jxcore-log( 3276): CLIENT is data received : 930000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 940000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 950000
I/jxcore-log( 3276): 
,W/bt-btif ( 2154): info:x10
,D/        ( 2154): remote version info [b4:ce:f6:ab:a4:6a]: 6, f, 410d
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=1
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2154): new conn_srvc id:26, app_id:255
W/bt-btif ( 2154): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2154): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3276): we got incoming connection
I/BTHandshakeSocketThread( 3276): Creating BTHandshakeSocketThread
I/BTListenerThread( 3276): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread started
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,W/bt-btif ( 2154): dm_pm_timer expires
W/bt-btif ( 2154): dm_pm_timer expires 0
W/bt-btif ( 2154): proc dm_pm_timer expires
,D/btif_config_util( 2154): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BTListenerThread( 3276): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 3276): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3126"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3276): MESSAGE_WRITE 77 bytes.
I/HS      ( 3276): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT3126
I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3276): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT3126
I/BtToSocketBase( 3276): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3276): Creating BTConnectedThread
I/BtConnectorHelper( 3276): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3276): --DoOneRunRound started
,I/jxcore-log( 3276): TCP/IP server connected
I/jxcore-log( 3276): 
,I/BtToRequestSocket( 3276): LocalHost address: localhost/127.0.0.1, port: 48644
,I/BtToRequestSocket( 3276): --DoOneRunRound ended
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=0
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3276): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): Receiving data timeout now
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT closeClientSocket
I/jxcore-log( 3276): 
,I/BtToSocketBase( 3276): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3276): Disconnect outgoing peer: motorola-Nexus 6_PT3617
,I/BtToSocketBase( 3276): Stop ReceivingThread
I/BtToSocketBase( 3276): Stop SendingThread
I/BtToSocketBase( 3276): Close local in
I/BtToSocketBase( 3276): Close LocalOutputStream
,I/BtToSocketBase( 3276): Close localHostSocket
I/BtToSocketBase( 3276): Close bt in
,I/BtToSocketBase( 3276): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3276): Close bt out
I/BtToSocketBase( 3276): Close bt socket
I/BtToRequestSocket( 3276): Close server socket
,I/jxcore-log( 3276): tryAgain afer: 5000 ms.
I/jxcore-log( 3276): 
I/jxcore-log( 3276): ----------------- closeClientSocket
I/jxcore-log( 3276): 
I/jxcore-log( 3276): TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT is closed
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=1
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3276): TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=0
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2154): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
,I/jxcore-log( 3276): TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3276): TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 100980 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 102960 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 104940 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 106920 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 108900 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 110880 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 112860 bytes of data
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2154): onReceive
,I/jxcore-log( 3276): TCP/IP server has received 114840 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 116820 bytes of data
I/jxcore-log( 3276): 
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 3276): TCP/IP server has received 118800 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 120780 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 122760 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 124740 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 126720 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 128700 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 130680 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 132660 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 134640 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 136620 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 138600 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 140580 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 142560 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 144540 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 146520 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 148500 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 150480 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 152460 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 154440 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 156420 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 158400 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 160380 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 162360 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 164340 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 166320 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 168300 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 170280 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 172260 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 174240 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 176220 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 178200 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 180180 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 182160 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 184140 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 186120 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 188100 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 190080 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 192060 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 194040 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 196020 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 198000 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 199980 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 201960 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 203940 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 205920 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 207900 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 209880 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 211860 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 215820 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 217800 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 219780 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 221760 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 223740 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 225720 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 227700 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 229680 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 231660 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 233640 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 235620 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 237600 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 239580 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 241560 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 243540 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 245520 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 247500 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 249480 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 251460 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 253440 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 257400 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 259380 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 261360 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 263340 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 265320 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 267300 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 269280 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 271260 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 273240 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 275220 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 277200 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 279180 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 281160 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 283140 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 285120 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 287100 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 289080 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 291060 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 293040 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 297000 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 298980 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 300960 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 302940 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 304920 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 306900 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 308880 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 310860 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 312840 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 314820 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 316800 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 318780 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 320760 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 322740 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 324720 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 326700 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 328680 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 330660 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 332640 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 334620 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 336600 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 338580 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 340560 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 342540 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 344520 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 346500 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 348480 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 350460 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 352440 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 354420 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 356400 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 358380 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 360360 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 362340 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 364320 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 366300 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 368280 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 370260 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 372240 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 374220 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 376200 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 378180 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 380160 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 382140 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 384120 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 386100 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 388080 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 390060 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 392040 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 394020 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 396000 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 397980 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 399960 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 401940 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 403920 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 405900 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 407880 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 409860 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 411840 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 413820 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 417780 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 421740 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 423720 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 429660 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 435600 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 437580 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 439560 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 441540 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 443520 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 447480 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 453420 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 455400 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 457380 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 461340 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 463320 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): Connect (retry count 1) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do connect now
I/jxcore-log( 3276): 
,I/        ( 3276): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 3276): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/jxcore-log( 3276): TCP/IP server has received 467280 bytes of data
I/jxcore-log( 3276): 
,I/BTConnectToThread( 3276): Starting to connect
W/BluetoothAdapter( 3276): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2154): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3276): TCP/IP server has received 469260 bytes of data
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3276): TCP/IP server has received 473220 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 475200 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 477180 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 479160 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 481140 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 483120 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 491040 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 493020 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 495000 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 496980 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 498960 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 500940 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 502920 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 504900 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 506880 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 508860 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 510840 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 512820 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 514800 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 516780 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 518760 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 520740 bytes of data
I/jxcore-log( 3276): 
,W/bt-btif ( 2154): info:x10
,D/        ( 2154): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 3276): TCP/IP server has received 522720 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 524700 bytes of data
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=1
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3276): TCP/IP server has received 526680 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 528660 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 530640 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 532620 bytes of data
I/jxcore-log( 3276): 
,W/bt-sdp  ( 2154): process_service_search_attr_rsp
,I/jxcore-log( 3276): TCP/IP server has received 534600 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 536580 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 540540 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 542520 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 544500 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 546480 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 548460 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 550440 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 552420 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 554400 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 556380 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 558360 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 560340 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 562320 bytes of data
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=0
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3276): TCP/IP server has received 564300 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 566280 bytes of data
I/jxcore-log( 3276): 
,W/bt-btif ( 2154): new conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3276): Starting to Handshake
,I/BTHandshakeSocketThread( 3276): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3276): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread started
,I/jxcore-log( 3276): TCP/IP server has received 568260 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 570240 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 572220 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 574200 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 576180 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 578160 bytes of data
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=1
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3276): TCP/IP server has received 580140 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 582120 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 584100 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 586080 bytes of data
I/jxcore-log( 3276): 
,I/BTConnectToThread( 3276): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3276): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3617","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3276): HandshakeOk : motorola-Nexus 6_PT3617
I/HS      ( 3276): Hand Shake finished outgoing for : motorola-Nexus 6_PT3617
I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3276): Starting the connected thread incoming : false, motorola-Nexus 6_PT3617
,I/BtToSocketBase( 3276): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3276): Creating BtConnectedRequestSocket
,I/jxcore-log( 3276): TCP/IP server has received 588060 bytes of data
I/jxcore-log( 3276): 
,I/BtToRequestSocket( 3276): mHTTPPort  set to : 39835
I/BtConnectorHelper( 3276): Request socket is using : 39835
I/BtToRequestSocket( 3276): Now accepting connections
,D/btif_config_util( 2154): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3276): TCP/IP server has received 590040 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 592020 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 594000 bytes of data
I/jxcore-log( 3276): 
,I/BtConnectorHelper( 3276): Calling ConnectionStatusUpdate with port :39835
I/jxcore-log( 3276): CLIENT connected to 39835, error: null
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT starting client 
I/jxcore-log( 3276): 
,I/BtToRequestSocket( 3276): incoming data from: /127.0.0.1, port: 39835
I/BtToRequestSocket( 3276): Set local streams
I/BtToRequestSocket( 3276): rin ended ---------------------------;
,I/jxcore-log( 3276): CLIENT now sending 50000 bytes of data
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:3667
,I/jxcore-log( 3276): CLIENT is data received : 960000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 595980 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 970000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 597960 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 599940 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 601920 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 980000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 990000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 603900 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 1000000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): got all data for this round
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT Stop now
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT closeClientSocket
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT Stop now
I/jxcore-log( 3276): 
I/jxcore-log( 3276): ---- round done--------
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do fake peer & start
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 3276): 
I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback round[0] time: 40410 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3276): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3276): Disconnect outgoing peer: motorola-Nexus 6_PT3617
,I/BtToSocketBase( 3276): Stop ReceivingThread
I/BtToSocketBase( 3276): Stop SendingThread
I/BtToSocketBase( 3276): Close local in
I/BtToSocketBase( 3276): Close LocalOutputStream
,I/BtToSocketBase( 3276): Close localHostSocket
I/BtToSocketBase( 3276): Close bt in
,I/BtToSocketBase( 3276): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3276): Close bt out
I/BtToSocketBase( 3276): Close bt socket
I/BtToRequestSocket( 3276): Close server socket
,I/jxcore-log( 3276): TCP/IP server has received 605880 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is closed
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 607860 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 609840 bytes of data
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=0
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2154): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3276): TCP/IP server has received 611820 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 613800 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 615780 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 617760 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 619740 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 621720 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 623700 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 625680 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 627660 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 629640 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 631620 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 633600 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 635580 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 637560 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 639540 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 641520 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 643500 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 645480 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 647460 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 649440 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 651420 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 653400 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 655380 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 657360 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 661320 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 663300 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 665280 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 667260 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 669240 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 673200 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 675180 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 679140 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 683100 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 685080 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 687060 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 689040 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 691020 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 693000 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 694980 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 696960 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 698940 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 700920 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 702900 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 704880 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 706860 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 708840 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 712800 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 714780 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 716760 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 718740 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 720720 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 722700 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 724680 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 726660 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 730620 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 732600 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 734580 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 736560 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 738540 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 740520 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 742500 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 744480 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 746460 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 748440 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 752400 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 754380 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 756360 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 758340 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 760320 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 762300 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 764280 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 766260 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 768240 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 772200 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 774180 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 776160 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 778140 bytes of data
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2154): onReceive
,I/jxcore-log( 3276): TCP/IP server has received 780120 bytes of data
I/jxcore-log( 3276): 
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 3276): TCP/IP server has received 782100 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 784080 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 788040 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 790020 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 792000 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 793980 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 799920 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 803880 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 805860 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 807840 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 809820 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): Connect (retry count 0) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do connect now
I/jxcore-log( 3276): 
,I/        ( 3276): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 3276): Connecting to null, at 34:FC:EF:11:B1:66
,I/jxcore-log( 3276): TCP/IP server has received 815760 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 817740 bytes of data
I/jxcore-log( 3276): 
,I/BTConnectToThread( 3276): Starting to connect
W/BluetoothAdapter( 3276): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2154): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3276): TCP/IP server has received 821700 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 823680 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 829620 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 831600 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 833580 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 835560 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 837540 bytes of data
I/jxcore-log( 3276): 
,W/bt-btif ( 2154): info:x10
,D/        ( 2154): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 2154): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3276): TCP/IP server has received 839520 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 843480 bytes of data
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e51b34 rs_disc_pending=1
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3276): TCP/IP server has received 845460 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 847440 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 849420 bytes of data
I/jxcore-log( 3276): 
,W/bt-sdp  ( 2154): process_service_search_attr_rsp
,I/jxcore-log( 3276): TCP/IP server has received 851400 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 853380 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 855360 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 857340 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 859320 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 861300 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 863280 bytes of data
I/jxcore-log( 3276): 
,I/BluetoothBondStateMachine( 2154): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
E/bt-btif ( 2154): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2154): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2154): Entering PendingCommandState State
,W/BluetoothEventManager( 2787): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2787): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,I/jxcore-log( 3276): TCP/IP server has received 865260 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 867240 bytes of data
I/jxcore-log( 3276): 
,I/BluetoothBondStateMachine( 2154): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,D/BluetoothAdapterProperties( 2154): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 2154): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,W/BluetoothEventManager( 2787): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 2154): StableState(): Entering Off State
,E/BluetoothEventManager( 2787): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,I/jxcore-log( 3276): TCP/IP server has received 869220 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 871200 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 873180 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 875160 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 877140 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 879120 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 881100 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 883080 bytes of data
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e51b34 rs_disc_pending=0
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2154): new conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2154): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3276): Starting to Handshake
,I/BTHandshakeSocketThread( 3276): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3276): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread started
,I/jxcore-log( 3276): TCP/IP server has received 885060 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 887040 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 889020 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 891000 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 892980 bytes of data
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e51b34 rs_disc_pending=1
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3276): TCP/IP server has received 894960 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 896940 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 898920 bytes of data
I/jxcore-log( 3276): 
,I/BTConnectToThread( 3276): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3276): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT3417"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3276): HandshakeOk : LGE-Nexus 5_PT3417
I/HS      ( 3276): Hand Shake finished outgoing for : LGE-Nexus 5_PT3417
I/BTHandshakeSocketThread( 3276): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3276): Starting the connected thread incoming : false, LGE-Nexus 5_PT3417
I/BtToSocketBase( 3276): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3276): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3276): mHTTPPort  set to : 52823
I/BtConnectorHelper( 3276): Request socket is using : 52823
I/BtToRequestSocket( 3276): Now accepting connections
,I/jxcore-log( 3276): TCP/IP server has received 900900 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 902880 bytes of data
I/jxcore-log( 3276): 
,I/BtConnectorHelper( 3276): Calling ConnectionStatusUpdate with port :52823
I/jxcore-log( 3276): CLIENT connected to 52823, error: null
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT starting client 
I/jxcore-log( 3276): 
,I/BtToRequestSocket( 3276): incoming data from: /127.0.0.1, port: 52823
I/BtToRequestSocket( 3276): Set local streams
I/BtToRequestSocket( 3276): rin ended ---------------------------;
,I/jxcore-log( 3276): TCP/IP server has received 904860 bytes of data
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT now sending 1000000 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 914760 bytes of data
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:76970
,I/jxcore-log( 3276): CLIENT is data received : 10000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 916740 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 918720 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 920700 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 922680 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 924660 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 20000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 926640 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 928620 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 930600 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 932580 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 934560 bytes of data
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71166
,I/jxcore-log( 3276): CLIENT is data received : 30000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 936540 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 40000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 938520 bytes of data
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3276): TCP/IP server has received 940500 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 942480 bytes of data
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69458
,I/jxcore-log( 3276): CLIENT is data received : 50000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 944460 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 946440 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 948420 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 950400 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 952380 bytes of data
I/jxcore-log( 3276): 
,D/btif_config_util( 2154): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3276): TCP/IP server has received 954360 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 956340 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 958320 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 960300 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 962280 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 60000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 964260 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 966240 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 968220 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 970200 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 972180 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 974160 bytes of data
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70856
,I/jxcore-log( 3276): CLIENT is data received : 70000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 976140 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 978120 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 980100 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 982080 bytes of data
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e51b34 rs_disc_pending=0
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3276): TCP/IP server has received 984060 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 986040 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 80000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 988020 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 990000 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 991980 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 993960 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 995940 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 997920 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 999900 bytes of data
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): TCP/IP server has received 1000002 bytes of data
I/jxcore-log( 3276): 
,W/bt-btif ( 2154): invalid rfc slot id: 20
,I/BtToSocketBase( 3276): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3276): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3276): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT3126
I/BtToSocketBase( 3276): Stop ReceivingThread
I/BtToSocketBase( 3276): Stop SendingThread
I/BtToSocketBase( 3276): Close local in
I/BtToSocketBase( 3276): Close LocalOutputStream
I/BtToSocketBase( 3276): Close localHostSocket
I/BtToSocketBase( 3276): Close bt in
I/BtToSocketBase( 3276): Close bt out
I/BtToSocketBase( 3276): Close bt socket
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70138
,I/BtToSocketBase( 3276): Dunno which thread got error: disconnected: java.io.IOException: Broken pipe
I/BtConnectorHelper( 3276): BT Disconnected with error : disconnected: java.io.IOException: Broken pipe
,I/jxcore-log( 3276): TCP/IP server is ended
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 90000
I/jxcore-log( 3276): 
I/jxcore-log( 3276): TCP/IP server is close
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 100000
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2154): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 2154): RFCOMM_DisconnectInd LCID:0x49
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e51b34 rs_disc_pending=1
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68430
,I/jxcore-log( 3276): CLIENT is data received : 110000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 120000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69828
,I/jxcore-log( 3276): CLIENT is data received : 130000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 140000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68120
,I/jxcore-log( 3276): CLIENT is data received : 150000
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): tBTM_SEC_DEV:0xa3e51b34 rs_disc_pending=0
W/bt-btif ( 2154): bta_dm_check_av:0
,W/bt-btif ( 2154): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3276): CLIENT is data received : 160000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70508
,I/jxcore-log( 3276): CLIENT is data received : 170000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 180000
I/jxcore-log( 3276): 
,E/bt-btm  ( 2154): btm_sec_disconnected - Clearing Pending flag
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68800
,D/BluetoothMapService( 2154): onReceive
,I/jxcore-log( 3276): CLIENT is data received : 190000
I/jxcore-log( 3276): 
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3276): CLIENT is data received : 200000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71188
,I/jxcore-log( 3276): CLIENT is data received : 210000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 220000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68490
,I/jxcore-log( 3276): CLIENT is data received : 230000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 240000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71868
,I/jxcore-log( 3276): CLIENT is data received : 250000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 260000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69170
,I/jxcore-log( 3276): CLIENT is data received : 270000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 280000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72548
,I/jxcore-log( 3276): CLIENT is data received : 290000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 300000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70840
,I/jxcore-log( 3276): CLIENT is data received : 310000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 320000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68142
,I/jxcore-log( 3276): CLIENT is data received : 330000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 340000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69540
,I/jxcore-log( 3276): CLIENT is data received : 350000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 360000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72918
,I/jxcore-log( 3276): CLIENT is data received : 370000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 380000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70220
,I/jxcore-log( 3276): CLIENT is data received : 390000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71482
,I/jxcore-log( 3276): CLIENT is data received : 400000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 410000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72744
,I/jxcore-log( 3276): CLIENT is data received : 420000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 430000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71036
,I/jxcore-log( 3276): CLIENT is data received : 440000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 450000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68338
,I/jxcore-log( 3276): CLIENT is data received : 460000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 470000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71716
,I/jxcore-log( 3276): CLIENT is data received : 480000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 490000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69018
,I/jxcore-log( 3276): CLIENT is data received : 500000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 510000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71406
,I/jxcore-log( 3276): CLIENT is data received : 520000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 530000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69698
,I/jxcore-log( 3276): CLIENT is data received : 540000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 550000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:66010
,I/jxcore-log( 3276): CLIENT is data received : 560000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 570000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70378
,I/jxcore-log( 3276): CLIENT is data received : 580000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71640
,I/jxcore-log( 3276): CLIENT is data received : 590000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 600000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70922
,I/jxcore-log( 3276): CLIENT is data received : 610000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 620000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69214
,I/jxcore-log( 3276): CLIENT is data received : 630000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74572
,I/jxcore-log( 3276): CLIENT is data received : 640000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 650000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70748
,I/jxcore-log( 3276): CLIENT is data received : 660000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 670000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70030
,I/jxcore-log( 3276): CLIENT is data received : 680000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 690000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:66342
,I/jxcore-log( 3276): CLIENT is data received : 700000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 710000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69720
,I/jxcore-log( 3276): CLIENT is data received : 720000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71972
,I/jxcore-log( 3276): CLIENT is data received : 730000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 740000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71254
,I/jxcore-log( 3276): CLIENT is data received : 750000
I/jxcore-log( 3276): 
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3276): CLIENT is data received : 760000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69546
,I/jxcore-log( 3276): CLIENT is data received : 770000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3276): CLIENT is data received : 780000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 4 peers.
I/SS      ( 3276): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3276): Peer(2): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(3): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3276): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70944
,I/jxcore-log( 3276): CLIENT is data received : 790000
I/jxcore-log( 3276): 
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3276): CLIENT is data received : 800000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70226
,I/jxcore-log( 3276): CLIENT is data received : 810000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 3276): CLIENT is data received : 820000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68518
,I/jxcore-log( 3276): CLIENT is data received : 830000
I/jxcore-log( 3276): 
,I/        ( 3276): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3126"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3126"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT3126, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT3126, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:61877
,I/jxcore-log( 3276): CLIENT is data received : 840000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 850000
I/jxcore-log( 3276): 
,I/        ( 3276): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT3417"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT3417"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT3417, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT3417, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3276): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9704","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9704","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT9704, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT9704, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:53957
,I/jxcore-log( 3276): CLIENT is data received : 860000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 870000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:44057
,I/jxcore-log( 3276): CLIENT is data received : 880000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 890000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:34157
,I/jxcore-log( 3276): CLIENT is data received : 900000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 910000
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/SS      ( 3276): Found 3 peers.
I/SS      ( 3276): Peer(1): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(2): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3276): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23267
,I/jxcore-log( 3276): CLIENT is data received : 920000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:17327
,I/jxcore-log( 3276): CLIENT is data received : 930000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 940000
I/jxcore-log( 3276): 
,D/        ( 2154): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8417
,I/jxcore-log( 3276): CLIENT is data received : 950000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 960000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 970000
I/jxcore-log( 3276): 
,I/        ( 3276): Started service discovery
,I/jxcore-log( 3276): CLIENT is data received : 980000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 990000
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT is data received : 1000000
I/jxcore-log( 3276): 
I/jxcore-log( 3276): got all data for this round
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT Stop now
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT closeClientSocket
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): CLIENT Stop now
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): ---- round done--------
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do fake peer & start
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3276): 
I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback round[0] time: 44701 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3276): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3276): Disconnect outgoing peer: LGE-Nexus 5_PT3417
I/BtToSocketBase( 3276): Stop ReceivingThread
I/BtToSocketBase( 3276): Stop SendingThread
I/BtToSocketBase( 3276): Close local in
I/BtToSocketBase( 3276): Close LocalOutputStream
I/BtToSocketBase( 3276): Close localHostSocket
I/BtToSocketBase( 3276): Close bt in
,I/BtToSocketBase( 3276): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3276): Close bt out
I/BtToSocketBase( 3276): Close bt socket
I/BtToRequestSocket( 3276): Close server socket
,I/jxcore-log( 3276): CLIENT is closed
I/jxcore-log( 3276): 
,W/bt-btif ( 2154): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2154): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2154): onReceive
,I/BTConnectionReceiver( 1427): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1427): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 3276): Connect (retry count 0) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3276): 
I/jxcore-log( 3276): do connect now
I/jxcore-log( 3276): 
,I/        ( 3276): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 3276): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 3276): Starting to connect
W/BluetoothAdapter( 3276): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2154): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3276): timeout now
I/jxcore-log( 3276): 
I/jxcore-log( 3276): dun
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): weAreDoneNow , resultArray.length: 7
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): done, now sending data to server
I/jxcore-log( 3276): 
I/jxcore-log( 3276): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): -- RESULT DATA {"name:":"LGE-Nexus 5_PT8166","time":500105,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:75:41","time":60170,"result":"OK","connections":2,"tryCount":1},{"name":"E0:DB:10:14:E2:C0","time":88203,"result":"OK","connections":3,"tryCount":1},{"name":"B4:CE:F6:AB:A4:6A","time":126237,"result":"OK","connections":5,"tryCount":1},{"name":"F4:F1:E1:5C:3B:E2","time":38924,"result":"OK","connections":2,"tryCount":1},{"name":"00:F4:6F:30:E0:6C","time":95801,"result":"OK","connections":3,"tryCount":1},{"name":"F8:CF:C5:D9:E5:61","time":40410,"result":"OK","connections":2,"tryCount":1},{"name":"34:FC:EF:11:B1:66","time":44701,"result":"OK","connections":1,"tryCount":1},{"connections":1,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"res
I/jxcore-log( 3276): sendList : 100% : 126237 ms, 99% : 126237 ms, 95 : 126237 ms, 90% : 95801 ms.
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Result count 7, range 38924 ms to  126237 ms.
I/jxcore-log( 3276): 
I/jxcore-log( 3276): sendList failed peers count : 1 [12.5 %]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): - Peer ID : 44:80:EB:7B:5A:05, Tried : 1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): sendList never tried peers count : 7 [46.666666666666664 %]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): - Peer ID : F8:95:C7:87:85:54
I/jxcore-log( 3276): 
I/jxcore-log( 3276): - Peer ID : 34:FC:EF:9D:93:0B
I/jxcore-log( 3276): 
I/jxcore-log( 3276): - Peer ID : 58:3F:54:73:64:C0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): - Peer ID : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): - Peer ID : 90:E7:C4:F6:69:77
I/jxcore-log( 3276): 
I/jxcore-log( 3276): - Peer ID : 50:2E:6C:AC:21:50
I/jxcore-log( 3276): 
I/jxcore-log( 3276): - Peer ID : E0:DB:10:1F:C9:5E
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT Stop now
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-sdp  ( 2154): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2154): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2154): invalid rfc slot id: 26
,I/BTConnectToThread( 3276): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3276): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3276): CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3276): 
I/jxcore-log( 3276): CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3276): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2757","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2757","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2757, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2757, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT575","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT575","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT575, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT575, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3276): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5538","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5538","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT5538, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT5538, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9121","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9121","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9121, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9121, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3617","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3617","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT3617, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT3617, WifiDirectName: , WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3276): Found 8 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3276): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3276): Found 7 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3276): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3276): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3276): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3276): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT1433","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT1433","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT1433, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT1433, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3276): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7881"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7881"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT7881, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT7881, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3276): Cleared service requests
,I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3276): Found 9 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3276): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(8): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3276): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3276): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3617","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3617","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT3617, peerAddress: F8:CF:C5:D9:E5:61
,I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT3617, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3276): Found 11 peers.
I/SS      ( 3276): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3276): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3276): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(10): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3276): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/UsageStatsService(  758): User[0] Flushing usage stats to disk
,I/        ( 3276): Cleared service requests
,I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3276): Found 10 peers.
I/SS      ( 3276): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3276): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(6): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3276): Peer(7): G3-1 02:9a:02:7b:60:ac
,I/SS      ( 3276): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(9): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3276): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3276): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3126"}, typeCordovap2p._tcp.local.:
,I/        ( 3276): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3126"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT3126, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT3126, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3276): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2757","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2757","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2757, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2757, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3276): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7881"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7881"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT7881, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT7881, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 5 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3276): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3276): Peer(5): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3276): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3276): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3617","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3617","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT3617, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT3617, WifiDirectName: , WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/        ( 3276): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT1545"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT1545"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT1545, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT1545, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3276): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT575","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT575","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT575, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT575, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3276): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3126"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3126"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT3126, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT3126, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3276): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT3417"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT3417"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT3417, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT3417, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3276): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2757","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2757","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2757, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2757, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3276): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5538","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5538","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT5538, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT5538, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3276): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7881"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7881"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT7881, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT7881, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3276): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9121","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9121","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9121, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9121, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3276): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8840"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8840"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8840, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8840, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3276): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9704","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9704","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT9704, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT9704, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 9 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3276): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3276): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT1433","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT1433","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT1433, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT1433, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 9 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3276): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 9 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(8): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3276): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3276): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5538","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5538","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT5538, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT5538, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 11 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3276): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3276): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3276): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3276): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3276): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3276): Found 6 peers.
I/SS      ( 3276): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3276): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 8 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3276): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3276): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3276): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3276): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8840"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8840"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8840, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8840, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3276): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9704","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3276): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9704","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT9704, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT9704, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3276): Found 9 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3276): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3276): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 10 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3276): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3276): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3276): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2757","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2757","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2757, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2757, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3276): Cleared service requests
,I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 10 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3276): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3276): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-smp  ( 2154): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2154): Plain text(LSB ~ MSB) = 86 99 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2154): Encrypted text(LSB ~ MSB) = 26 02 36 7c c7 d1 f7 18 39 8d 79 ca 9f 34 4c 67 
,W/bt-btm  ( 2154): Stopping oneshot timer
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3276): Found 9 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3276): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3276): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 10 peers.
I/SS      ( 3276): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3276): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3276): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3276): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3276): Started service discovery
,I/        ( 3276): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4525","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3276): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4525","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4525, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4525, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3276): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT1545"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT1545"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT1545, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT1545, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3276): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT575","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT575","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT575, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT575, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED ,
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 11 peers.
I/SS      ( 3276): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3276): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3276): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(8): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3276): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3276): Peer(10): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3276): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4525","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4525","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4525, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4525, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 11 peers.
I/SS      ( 3276): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3276): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3276): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(8): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3276): Peer(10): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 9 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3276): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3276): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3276): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT1545"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT1545"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT1545, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT1545, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 6 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3276): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(6): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3276): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3276): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8840"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8840"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8840, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8840, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3276): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9704","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9704","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT9704, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT9704, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3276): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7881"}, typeCordovap2p._tcp.local.:
,I/        ( 3276): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7881"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT7881, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT7881, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3276): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9121","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9121","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9121, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9121, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3276): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3126"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3126"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT3126, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT3126, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Cleared service requests
,I/        ( 3276): Started peer discovery
,I/ProcessStatsService(  758): Prepared write state in 33ms
,I/ProcessStatsService(  758): Prepared write state in 5ms
,I/EventLogService( 1697): Aggregate from 1447925889238 (log), 1447925889238 (data)
,V/GLSActivity( 1383): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1383): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  758): Pruning old procstats: /data/system/procstats/state-2015-11-18-14-12-29.bin
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3276): Found 9 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3276): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3276): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3276): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6448","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6448","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT6448, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT6448, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/ActivityManager(  758): Killing 2069:com.google.android.calendar/u0a31 (adj 13): empty for 1801s
,I/ActivityManager(  758): Killing 2667:com.google.android.gm/u0a70 (adj 15): empty for 1801s
,I/ActivityManager(  758): Killing 2808:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty for 1802s
,W/libprocessgroup(  758): failed to open /acct/uid_10031/pid_2069/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10070/pid_2667/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10003/pid_2808/cgroup.procs: No such file or directory
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 9 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3276): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(7): G3-1 02:9a:02:7b:60:ac
,I/SS      ( 3276): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3276): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6448","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6448","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT6448, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT6448, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/        ( 3276): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3126"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3126"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT3126, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT3126, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3276): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2757","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2757","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2757, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2757, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 11 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 3276): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3276): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3276): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3276): Found 11 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3276): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3276): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3276): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3276): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT575","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT575","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT575, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT575, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/        ( 3276): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3126"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3126"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT3126, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT3126, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3276): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT1545"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT1545"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT1545, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT1545, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3276): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT3417"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT3417"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT3417, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT3417, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3276): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8840"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8840"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8840, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8840, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3276): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7881"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7881"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT7881, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT7881, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3276): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9121","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9121","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9121, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9121, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3276): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2757","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2757","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2757, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2757, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3276): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT575","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3276): Found 9 peers.
I/SS      ( 3276): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3276): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3276): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2,
I/SS      ( 3276): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3276): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT1433","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT1433","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT1433, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT1433, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3276): Cleared service requests
I/        ( 3276): Started peer discovery
,I/ClearcutLoggerApiImpl( 1383): disconnect managed GoogleApiClient
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3276): Found 10 peers.
I/SS      ( 3276): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3276): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3276): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3276): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3276): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3276): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3276): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3276): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3276): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3276): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3276): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3276): Added service request
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3276): Started service discovery
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3276): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9704","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9704","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT9704, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT9704, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3276): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT1433","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3276): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT1433","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT1433, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3276): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT1433, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 3276): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): The Coordinator has disconnected!
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
I/jxcore-log( 3276): found interfaceName: wlan0
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): Turning Wifi off
I/jxcore-log( 3276): 
,D/WifiService(  758): setWifiEnabled: false pid=3276, uid=10270
E/WifiService(  758): Invoking mWifiStateMachine.setWifiEnabled
,E/WifiStateMachine(  758): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  758): do suspend true
,I/jxcore-log( 3276): Turning Wifi back on
I/jxcore-log( 3276): 
,D/WifiService(  758): setWifiEnabled: true pid=3276, uid=10270
E/WifiService(  758): Invoking mWifiStateMachine.setWifiEnabled
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/WifiController(  758): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 456ms
,V/NativeCrypto( 1383): Read error: ssl=0xa4122e00: I/O error during system call, Connection timed out
,I/jxcore-log( 3276): toggleWiFi finished
I/jxcore-log( 3276): 
,V/NativeCrypto( 1383): SSL shutdown failed: ssl=0xa4122e00: I/O error during system call, Broken pipe
I/jxcore-log( 3276): ReconnectWifiAP finished
I/jxcore-log( 3276): 
,E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  758): scanCount==0 - aborting
,I/ActivityManager(  758): Killing 2091:com.android.providers.calendar/u0a2 (adj 13): empty for 1894s
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  758): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/ConnectivityService(  758): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  758): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/CSLegacyTypeTracker(  758): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1697): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524292
,I/ActivityManager(  758): Killing 3098:com.google.android.gms:car/u0a8 (adj 13): empty for 1895s
,I/ActivityManager(  758): Killing 1964:com.google.android.talk/u0a54 (adj 15): empty for 1919s
,I/ActivityManager(  758): Killing 2832:com.google.android.music:main/u0a60 (adj 15): empty for 1921s
,D/WifiScanningService(  758): SCAN_AVAILABLE : 1
W/libprocessgroup(  758): failed to open /acct/uid_10002/pid_2091/cgroup.procs: No such file or directory
D/RttService(  758): SCAN_AVAILABLE : 1
,D/WifiScanningService(  758): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  758): DefaultState
D/RttService(  758): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/libprocessgroup(  758): failed to open /acct/uid_10054/pid_1964/cgroup.procs: No such file or directory
D/ConnectivityService(  758): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1239): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  758): NetworkAgent: NetworkAgent channel lost
W/libprocessgroup(  758): failed to open /acct/uid_10008/pid_3098/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10060/pid_2832/cgroup.procs: No such file or directory
,E/native  (  758): do suspend true
,I/        ( 3276): Discovery state changed to Stopped.
I/        ( 3276): Starting peer discovery failed, error code 2
,I/WB      ( 3276): Wifi is DISABLED !!
I/        ( 3276): Stoping All
I/        ( 3276): Stopping services
I/        ( 3276): Stopping services
,I/        ( 3276): Stop Bluetooth
I/        ( 3276): Stop Bluetooth
I/BTListenerThread( 3276): Stopped
,I/        ( 3276): Clearing local services failed, error code 2
I/        ( 3276): Clearing service requests failed, error code 2
,I/        ( 3276): Stopping peer discovery failed, error code 2
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,I/ActivityManager(  758): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=3700 uid=10054 gids={50054, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,W/ResourcesManager( 3700): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant(  983): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,D/WifiController(  758): DEFERRED_TOGGLE handled
,I/Babel_SMS( 3700): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 3700): MmsConfig.loadMmsSettings
I/Babel_SMS( 3700): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
I/Babel_SMS( 3700): MmsConfig.loadFromDatabase
,E/Babel_SMS( 3700): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 3700): MmsConfig.loadFromResources
,E/Babel_SMS( 3700): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 3700): MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/Babel_SMS( 3700): ApnsOta: OTA version -1
,I/Babel   ( 3700): deleted: false for 0
,W/Settings( 3700): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Tethering(  758): InitialState.processMessage what=4
I/wpa_supplicant(  983): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  758): sendTetherStateChangedBroadcast 0, 0, 0
,I/Babel_Crash( 3700): startup - clean
,W/Settings( 1669): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  758): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3737 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 3700): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 3700): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 3700): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3700): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3700): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3700): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  758): Killing 1536:com.google.android.partnersetup/u0a13 (adj 15): empty for 1890s
,D/SoftapController(  179): Softap fwReload - Ok
,D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring down wlan0
D/CommandListener(  179): Clearing all IP addresses on wlan0
,W/libprocessgroup(  758): failed to open /acct/uid_10013/pid_1536/cgroup.procs: No such file or directory
,W/Settings( 3700): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiMonitor(  758): startMonitoring(wlan0) with mConnected = false
,I/vclib   ( 3700): onServiceConnected
,W/Babel   ( 3700): Attempted to change video mute state without an active call.
,I/wpa_supplicant( 3755): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3755): rfkill: Cannot open RFKILL control device
,I/ActivityManager(  758): Killing 3184:com.android.musicfx/u0a15 (adj 15): empty for 1891s
,W/libprocessgroup(  758): failed to open /acct/uid_10015/pid_3184/cgroup.procs: No such file or directory
,I/jxcore-log( 3276): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3276): 
I/jxcore-log( 3276): printNetworkInfo
I/jxcore-log( 3276): 
,D/Tethering(  758): sendTetherStateChangedBroadcast 1, 0, 0
I/jxcore-log( 3276): found interfaceName: lo
I/jxcore-log( 3276): 
I/jxcore-log( 3276): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3276): 
,I/chromium( 3276): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3755): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  758): Loading config and enabling all networks 
,E/WifiConfigStore(  758): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 3700): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-HAL(  758): Setting external_sim to 1
,D/WifiStateMachine(  758): Setting OUI to DA-A1-19
I/WifiNative-HAL(  758): startHal
D/wifi    (  758): setting scan oui 0xa1336280
D/WifiHAL (  758): Sending mac address OUI
,E/WifiHAL (  758): failed to set scanning mac OUI; result = -95
,E/native  (  758): do suspend true
,D/WifiScanningService(  758): SCAN_AVAILABLE : 3
D/WifiScanningService(  758): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  758): startHal
,D/RttService(  758): SCAN_AVAILABLE : 3
,D/RttService(  758): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/wifi    (  758): getting scan capabilities on interface[1] = 0xa1336280
D/WifiHAL (  758): Creating message to get scan capablities; iface = 21
D/WifiHAL (  758): In GetCapabilities::handleResponse
D/WifiHAL (  758): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  758): StartedState
,D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  758): startMonitoring(p2p0) with mConnected = true
,I/WB      ( 3276): Wifi is now enabled !
I/        ( 3276): Stoping All
I/        ( 3276): Stopping services
I/        ( 3276): Stop Bluetooth
I/        ( 3276): Starting All
I/        ( 3276): Stopping services
I/        ( 3276): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8166","ra":"34:FC:EF:11:AE:67"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@a18c5d2
I/        ( 3276): Stopping services
I/        ( 3276): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8166","ra":"34:FC:EF:11:AE:67"}
I/        ( 3276): Add local service :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8166","ra":"34:FC:EF:11:AE:67"}, length : 77
I/        ( 3276): peerDiscoveryTimer timeout value:5195
,I/        ( 3276): Stop Bluetooth
I/        ( 3276): StartBluetooth listener
I/        ( 3276): StartBluetooth listener
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3276): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3276): Discovery state changed to Stopped.
,I/wpa_supplicant( 3755): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/BTListenerThread( 3276): starting to listen
I/BTListenerThread( 3276): waiting to accept incoming Connection
,D/WifiNative-HAL(  758): p2pGetDeviceAddress
,D/WifiNative-HAL(  758): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/        ( 3276): Added local service
,I/        ( 3276): Cleared service requests
,I/        ( 3276): Stopped peer discovery
I/        ( 3276): Started peer discovery
I/        ( 3276): Discovery state changed to Started.
,I/wpa_supplicant( 3755): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3755): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3276): Started peer discovery

```
