#### Test 613623666a5dbc7_thali05_htc-Nexus 9 Logs


```
--------- beginning of main
,V/GLSActivity( 1025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1025): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1025): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1025): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1025): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GLSActivity( 1025): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1025): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1025): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1025): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1025): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1025): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1025): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 1666): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1666): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1666): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1666): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1666): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1666): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1666): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 1666): Ignoring header User-Agent because its value was null.
D/AndroidRuntime( 2231): 
D/AndroidRuntime( 2231): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2231): CheckJNI is OFF
D/AndroidRuntime( 2231): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  463): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  463): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2245 uid=10082 gids={50082, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2231): Shutting down VM
V/ActivityManager(  463): Display changed displayId=0
,I/WebViewFactory( 2245): Loading com.google.android.webview version 44.0.2403.90 (code 240309050)
,I/LibraryLoader( 2245): Time to load native libraries: 20 ms (timestamps 369-389)
,I/LibraryLoader( 2245): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 2245): Binding Chromium to main looper Looper (main, tid 1) {2c2a2213}
I/LibraryLoader( 2245): Expected native library version number "",actual native library version number ""
,I/chromium( 2245): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2245): Initializing chromium process, singleProcess=true
,W/art     ( 2245): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2245): ApplicationContext is null in ApplicationStatus
,W/chromium( 2245): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2245): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2245): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2245): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,W/ActivityManager(  463): Activity pause timeout for ActivityRecord{10d66d23 u0 com.test.thalitest/.MainActivity t29}
,D/BluetoothManagerService(  463): Message: 20
D/BluetoothManagerService(  463): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3dc52a76:true
,D/BluetoothAdapter( 2245): 205327740: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2245): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2245): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2245): CordovaWebView is running on device made by: htc
,W/art     ( 2245): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2245): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2245): Render dirty regions requested: true
,W/chromium( 2245): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2245): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2245): Enabling debug mode 0
,I/Keyboard.Facilitator(  824): onFinishInput()
,I/ActivityManager(  463): Displayed com.test.thalitest/.MainActivity: +1s217ms (total +1s319ms)
,W/IInputConnectionWrapper( 2245): showStatusIcon on inactive InputConnection
,W/BindingManager( 2245): Cannot call determinedVisibility() - never saw a connection for the pid: 2245
,D/JsMessageQueue( 2245): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2245): JniHelper::setJavaVM(0xaaf41290), pthread_self() = -1422211896
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2245): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2245):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2245):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2245):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2245):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2245): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25072e4f added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2245): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2245):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2245):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2245):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2245):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2245):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2245):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2245):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2245):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2245):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2245): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37ace9ba added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2245): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  463): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2245): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2245): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2245): setDiscoveryMode: Discovery mode BLE is supported
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2245): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2245): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 2245): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 2245): Initializing JXcore engine
W/jxcore-log( 2245): JXcore engine is ready
,W/Thread-54( 2292): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5996]" dev="sockfs" ino=5996 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-54( 2292): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=449 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-54( 2292): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6133]" dev="sockfs" ino=6133 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-54( 2292): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18501]" dev="sockfs" ino=18501 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 2245): Starting JXcore engine
,W/jxcore-log( 2245): Platform android
W/jxcore-log( 2245): 
W/jxcore-log( 2245): Process ARCH arm
W/jxcore-log( 2245): 
,I/jxcore-log( 2245): JXcore Cordova bridge is ready!
I/jxcore-log( 2245): 
,W/jxcore-log( 2245): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 2245): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 2245): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 2245): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 2245): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,I/ActivityManager(  463): Killing 1934:com.google.android.gm.exchange/u0a70 (adj 15): empty #17
,W/libprocessgroup(  463): failed to open /acct/uid_10070/pid_1934/cgroup.procs: No such file or directory
,W/PluginManager( 2245): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 63ms. Plugin should use CordovaInterface.getThreadPool().
,I/Keyboard.Facilitator.LanguageModelFlusher(  824): run()
I/Keyboard.Facilitator(  824): flushDynamicLanguageModels()
,I/ConfigService( 1025): onCreate
,I/ConfigService( 1025): onDestroy
,V/GLSActivity( 1025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1025): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1025): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1025): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1025): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1025): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1025): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1025): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1025): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1025): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1025): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1025): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1666): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1666): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1666): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1666): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1666): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1666): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1666): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 1666): Ignoring header User-Agent because its value was null.
,D/Finsky  ( 1666): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/art     (  463): Explicit concurrent mark sweep GC freed 22516(1172KB) AllocSpace objects, 6(160KB) LOS objects, 33% free, 19MB/28MB, paused 1.106ms total 140.502ms
,V/GLSActivity( 1025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1025): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1025): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1025): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1025): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 1666): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1025): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1025): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1025): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1025): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1188): Aggregate from 1456904739855 (log), 1456904739855 (data)
,V/GLSActivity( 1025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1025): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1025): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1025): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1025): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1025): Explicit concurrent mark sweep GC freed 20599(1239KB) AllocSpace objects, 5(200KB) LOS objects, 40% free, 10MB/17MB, paused 596us total 48.235ms
,W/Finsky  ( 1666): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1025): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1025): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1025): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1025): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 1666): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 1666): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 1666): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 1666): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/DeviceConnectionService( 1058): client connected with version: 7571000
,D/Finsky  ( 1666): [191] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 1666): [1] 5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1025): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1025): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1025): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1025): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1025): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1025): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1025): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1025): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1025): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1025): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1025): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1666): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1666): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1666): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1666): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1666): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1666): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1666): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 1666): Ignoring header User-Agent because its value was null.
,I/UsageStatsService(  463): User[0] Flushing usage stats to disk
,V/GLSActivity( 1025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1025): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1025): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1025): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1025): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1025): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1025): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1025): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1025): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1025): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1025): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1025): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1666): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1666): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1666): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1666): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1666): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1666): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1666): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 1666): Ignoring header User-Agent because its value was null.
,V/GLSActivity( 1025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1025): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1025): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1025): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1025): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1025): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1025): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1025): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1025): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1025): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1025): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1025): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1666): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1666): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1666): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1666): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1666): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1666): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1666): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 1666): Ignoring header User-Agent because its value was null.
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 2317): 
D/AndroidRuntime( 2317): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2317): CheckJNI is OFF
D/AndroidRuntime( 2317): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  463): Force stopping com.test.thalitest appid=10082 user=-1: uninstall pkg
I/ActivityManager(  463): Killing 2245:com.test.thalitest/u0a82 (adj 9): stop com.test.thalitest
D/WifiService(  463): Client connection lost with reason: 4
W/PackageSettings(  463): Skipping PackageSetting{3d2a52a4 com.example.hello/10095} due to missing metadata
W/ActivityManager(  463): Spurious death for ProcessRecord{3d974eb8 2245:com.test.thalitest/u0a82}, curProc for 2245: null
I/ActivityManager(  463): Force stopping com.test.thalitest appid=10082 user=0: pkg removed
I/art     (  938): Explicit concurrent mark sweep GC freed 8434(499KB) AllocSpace objects, 4(336KB) LOS objects, 40% free, 14MB/23MB, paused 697us total 77.010ms
W/GeofencerStateMachine( 1058): Ignoring removeGeofence because network location is disabled.
I/InputReader(  463): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator(  824): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer(  824): run()
I/Decoder (  824): createOrResetDecoder
I/ActivityManager(  463): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2332 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=arm64-v8a
D/VoicemailCleanupService(  985): Cleaning up data for package: com.test.thalitest
I/art     (  463): Explicit concurrent mark sweep GC freed 18023(1120KB) AllocSpace objects, 9(240KB) LOS objects, 33% free, 18MB/28MB, paused 1.769ms total 244.175ms
I/art     (  463): WaitForGcToComplete blocked for 147.357ms for cause Explicit
I/ConfigService( 1025): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader(  824): run()
I/art     ( 1011): Explicit concurrent mark sweep GC freed 2785(229KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 12MB/17MB, paused 1.562ms total 365.572ms
W/ContextImpl( 2332): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/Keyboard.Facilitator.MainLanguageModelLoader(  824): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5150672, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  824): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  824): run() : Loading LM = contacts
E/NetworkScheduler.SchedulerReceiver( 1025): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1025): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  824): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  824): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  824): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  824): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  824): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader(  824): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper(  824): run()
I/Keyboard.Facilitator.RecurringTaskScheduler(  824): run()
I/StatsUtilsManager(  824): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder(  824): shouldRecordStats() = Too Soon
D/ChimeraCfgMgr( 1188): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1188): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1188): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1188): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1188): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1188): Clearing selected account for com.test.thalitest
I/UpdateIcingCorporaServi( 1011): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/BackupManagerService(  463): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  463): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  463): removeObsoleteFile: deleting file=29_task.xml
I/LocationSettingsChecker( 1188): Removing dialog suppression flag for package com.test.thalitest
W/InputMethodManagerService(  463): Got RemoteException sending setActive(false) notification to pid 2245 uid 10082
I/Keyboard.Facilitator(  824): onFinishInput()
W/Launcher(  938): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3a02b605 new=com.google.android.velvet.VelvetApplication@3a02b605
I/UpdateIcingCorporaServi( 1011): UpdateCorporaTask done [took 148 ms] updated apps [took 148 ms] 
D/GOOGLEHELP_CompatibleDatabase( 1188): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1188): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1188): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1188): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/ActivityManager(  463): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=2365 uid=10039 gids={50039, 9997} abi=arm64-v8a
I/ConfigFetchService( 1188): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1188): service connected
D/GOOGLEHELP_CompatibleDatabase( 1188): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1188): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
I/PeopleContactsSync( 1188): CP2 sync disabled
W/BaseAppContext( 1188): Using Auth Proxy for data requests.
I/Icing   ( 1188): doRemovePackageData com.test.thalitest
D/GOOGLEHELP_CompatibleDatabase( 1188): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
W/BaseAppContext( 1188): Using Auth Proxy for data requests.
D/GOOGLEHELP_CompatibleDatabase( 1188): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1188): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1188): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1188): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1188): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1188): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/art     (  463): Explicit concurrent mark sweep GC freed 9866(484KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 18MB/28MB, paused 1.760ms total 609.681ms
I/ActivityManager(  463): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=2386 uid=10006 gids={50006, 9997, 1028, 1015, 1023} abi=arm64-v8a
I/Launcher(  938): Deferring update until onResume
I/ActivityManager(  463): Killing 1912:com.google.android.gm/u0a71 (adj 15): empty #17
D/AndroidRuntime( 2317): Shutting down VM
W/libprocessgroup(  463): failed to open /acct/uid_10071/pid_1912/cgroup.procs: No such file or directory
W/DriveInitializer( 1188): Awaiting to be initialized
W/DriveInitializer( 1188): Background init thread started
D/ExternalStorage( 2386): After updating volumes, found 1 active roots
W/ResourcesManager( 2169): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2169): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/DriveInitializer( 1188): Background init thread ended
E/native  (  824): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  (  824): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  (  824): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  (  824): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
D/Documents( 2365): Update found 7 roots in 562ms
D/Documents( 2365): Update found 7 roots in 230ms
E/SQLiteDatabase( 1025): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1025): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1025): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1025): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1025): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1025): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1025): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1025): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1025): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1025): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1025): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1025): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1025): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1025): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1025): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1025): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1025): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1025): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1025): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1025): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1025): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1025): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1025): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 1025): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1025): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1025): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1025): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1025): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1025): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1025): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1025): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1025): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1025): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1025): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1025): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteOpenHelper( 1025): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1025): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1025): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1025): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1025): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1025): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1025): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1025): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1025): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1025): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1025): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 1025): Opened phenotype.db in read-only mode
E/SQLiteLog( 1025): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1025): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1025): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1025): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1025): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1025): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1025): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1025): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1025): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1025): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1025): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1025): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1025): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1025): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1025): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1025): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1025): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1025): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1025): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1025): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1025): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1025): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1025): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1025): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1025): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1025): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1025): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1025): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1025): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1025): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1025): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1025): 	at java.lang.Thread.run(Thread.java:818)

```
