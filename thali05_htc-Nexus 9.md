#### Test 61432979123161a_thali05_htc-Nexus 9 Logs


```
--------- beginning of main
,V/GLSActivity( 1042): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1042): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1042): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1042): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1042): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1042): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GLSActivity( 1042): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1042): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1042): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1042): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1042): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1042): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1042): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 1669): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1669): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1669): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1669): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1669): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1669): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1669): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 1669): Ignoring header User-Agent because its value was null.
D/AndroidRuntime( 2210): 
D/AndroidRuntime( 2210): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2210): CheckJNI is OFF
D/AndroidRuntime( 2210): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  463): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  463): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2224 uid=10082 gids={50082, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2210): Shutting down VM
V/ActivityManager(  463): Display changed displayId=0
I/WebViewFactory( 2224): Loading com.google.android.webview version 44.0.2403.90 (code 240309050)
,I/LibraryLoader( 2224): Time to load native libraries: 20 ms (timestamps 4239-4259)
I/LibraryLoader( 2224): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 2224): Binding Chromium to main looper Looper (main, tid 1) {44a252e}
I/LibraryLoader( 2224): Expected native library version number "",actual native library version number ""
,I/chromium( 2224): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2224): Initializing chromium process, singleProcess=true
,W/art     ( 2224): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2224): ApplicationContext is null in ApplicationStatus
,W/chromium( 2224): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2224): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2224): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2224): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,W/ActivityManager(  463): Activity pause timeout for ActivityRecord{377c59ef u0 com.test.thalitest/.MainActivity t29}
,D/BluetoothManagerService(  463): Message: 20
D/BluetoothManagerService(  463): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b233232:true
,D/BluetoothAdapter( 2224): 181888570: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2224): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2224): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2224): CordovaWebView is running on device made by: htc
,W/art     ( 2224): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2224): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2224): Render dirty regions requested: true
,W/chromium( 2224): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2224): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2224): Enabling debug mode 0
,I/Keyboard.Facilitator(  828): onFinishInput()
,I/ActivityManager(  463): Displayed com.test.thalitest/.MainActivity: +1s180ms (total +1s270ms)
W/IInputConnectionWrapper( 2224): showStatusIcon on inactive InputConnection
,W/BindingManager( 2224): Cannot call determinedVisibility() - never saw a connection for the pid: 2224
,D/JsMessageQueue( 2224): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2224): JniHelper::setJavaVM(0xab2fd290), pthread_self() = -1418291520
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2224): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2224):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2224):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2224):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2224):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2224): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1e899a added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2224): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2224):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2224):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2224):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2224):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2224):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2224):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2224):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2224):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2224):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2224): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20da89c1 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2224): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  463): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2224): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2224): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2224): setDiscoveryMode: Discovery mode BLE is supported
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2224): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2224): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 2224): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 2224): Initializing JXcore engine
W/jxcore-log( 2224): JXcore engine is ready
,W/Thread-53( 2273): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[10426]" dev="sockfs" ino=10426 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-53( 2273): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=449 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-53( 2273): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10692]" dev="sockfs" ino=10692 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-53( 2273): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17657]" dev="sockfs" ino=17657 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 2224): Starting JXcore engine
,W/jxcore-log( 2224): Platform android
W/jxcore-log( 2224): 
W/jxcore-log( 2224): Process ARCH arm
W/jxcore-log( 2224): 
,I/jxcore-log( 2224): JXcore Cordova bridge is ready!
I/jxcore-log( 2224): 
W/jxcore-log( 2224): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 2224): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 2224): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 2224): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 2224): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,I/ActivityManager(  463): Killing 1930:com.google.android.gm.exchange/u0a70 (adj 15): empty #17
,W/libprocessgroup(  463): failed to open /acct/uid_10070/pid_1930/cgroup.procs: No such file or directory
,W/PluginManager( 2224): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 63ms. Plugin should use CordovaInterface.getThreadPool().
,I/Keyboard.Facilitator.LanguageModelFlusher(  828): run()
I/Keyboard.Facilitator(  828): flushDynamicLanguageModels()
,I/ConfigService( 1042): onCreate
,I/ConfigService( 1042): onDestroy
,V/GLSActivity( 1042): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1042): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1042): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1042): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1042): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1042): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  463): Explicit concurrent mark sweep GC freed 19962(1027KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 19MB/28MB, paused 1.009ms total 129.932ms
,W/GLSActivity( 1042): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1042): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1042): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1042): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1042): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1042): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1042): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1669): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1669): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1669): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1669): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1669): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1669): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1669): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 1669): Ignoring header User-Agent because its value was null.
,V/GLSActivity( 1042): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1042): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1042): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1042): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1042): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1042): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1042): Explicit concurrent mark sweep GC freed 19048(1153KB) AllocSpace objects, 5(200KB) LOS objects, 39% free, 10MB/17MB, paused 843us total 81.868ms
,W/GLSActivity( 1042): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1042): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1042): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1042): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1042): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1042): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1042): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1669): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1669): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1669): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1669): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1669): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1669): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1669): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 1669): Ignoring header User-Agent because its value was null.
,I/UsageStatsService(  463): User[0] Flushing usage stats to disk
,V/GLSActivity( 1042): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1042): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1042): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1042): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1042): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1042): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1042): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1042): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1042): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1042): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1042): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1042): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1042): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1669): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1669): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1669): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1669): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1669): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1669): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1669): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 1669): Ignoring header User-Agent because its value was null.
,V/GLSActivity( 1042): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1042): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1042): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1042): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1042): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1042): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1042): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1042): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1042): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1042): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1042): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1042): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1042): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1669): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1669): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1669): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1669): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1669): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1669): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1669): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 1669): Ignoring header User-Agent because its value was null.
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 2294): 
D/AndroidRuntime( 2294): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2294): CheckJNI is OFF
D/AndroidRuntime( 2294): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  463): Force stopping com.test.thalitest appid=10082 user=-1: uninstall pkg
I/ActivityManager(  463): Killing 2224:com.test.thalitest/u0a82 (adj 9): stop com.test.thalitest
D/WifiService(  463): Client connection lost with reason: 4
W/PackageSettings(  463): Skipping PackageSetting{33c29c33 com.example.hello/10095} due to missing metadata
W/ActivityManager(  463): Spurious death for ProcessRecord{8e1b316 2224:com.test.thalitest/u0a82}, curProc for 2224: null
I/ActivityManager(  463): Force stopping com.test.thalitest appid=10082 user=0: pkg removed
I/art     (  937): Explicit concurrent mark sweep GC freed 9738(500KB) AllocSpace objects, 3(252KB) LOS objects, 40% free, 14MB/23MB, paused 846us total 71.153ms
W/GeofencerStateMachine(  971): Ignoring removeGeofence because network location is disabled.
I/InputReader(  463): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator(  828): resetDictionaries() : en_US
I/art     ( 1018): Explicit concurrent mark sweep GC freed 2614(215KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 12MB/17MB, paused 525us total 87.898ms
I/Keyboard.Facilitator.DecoderInitializer(  828): run()
I/Decoder (  828): createOrResetDecoder
D/VoicemailCleanupService(  989): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  463): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2309 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=arm64-v8a
I/ConfigService( 1042): onCreate
W/InputMethodManagerService(  463): Got RemoteException sending setActive(false) notification to pid 2224 uid 10082
I/art     (  463): Explicit concurrent mark sweep GC freed 15867(1048KB) AllocSpace objects, 12(320KB) LOS objects, 33% free, 19MB/28MB, paused 2.389ms total 269.583ms
I/art     (  463): WaitForGcToComplete blocked for 279.959ms for cause Explicit
I/Keyboard.Facilitator(  828): onFinishInput()
I/Keyboard.Facilitator.MainLanguageModelLoader(  828): run()
W/ContextImpl( 2309): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
E/NetworkScheduler.SchedulerReceiver( 1042): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1042): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Keyboard.Facilitator.MainLanguageModelLoader(  828): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5150672, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  828): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  828): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  828): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  828): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  828): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  828): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  828): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader(  828): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper(  828): run()
I/Keyboard.Facilitator.RecurringTaskScheduler(  828): run()
I/StatsUtilsManager(  828): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder(  828): shouldRecordStats() = Too Soon
D/BackupManagerService(  463): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  463): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  463): removeObsoleteFile: deleting file=29_task.xml
D/ChimeraCfgMgr( 1189): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1189): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1189): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1189): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1189): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1189): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1189): Removing dialog suppression flag for package com.test.thalitest
W/Launcher(  937): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3e67e848 new=com.google.android.velvet.VelvetApplication@3e67e848
I/UpdateIcingCorporaServi( 1018): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  463): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/Launcher(  937): Deferring update until onResume
I/ActivityManager(  463): Resuming delayed broadcast
I/ActivityManager(  463): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=2342 uid=10039 gids={50039, 9997} abi=arm64-v8a
I/VacuumService( 1042): Vacuum at: now=1456941698144 tag=VacuumService
I/ConfigFetchService( 1189): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
W/BaseAppContext( 1189): Using Auth Proxy for data requests.
I/ConfigFetchService( 1189): service connected
D/GOOGLEHELP_CompatibleDatabase( 1189): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1189): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1189): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1189): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1189): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1189): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1189): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/PeopleContactsSync( 1189): CP2 sync disabled
D/GOOGLEHELP_CompatibleDatabase( 1189): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1189): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1189): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1189): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1189): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1189): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/BaseAppContext( 1189): Using Auth Proxy for data requests.
I/Icing   ( 1189): doRemovePackageData com.test.thalitest
I/UpdateIcingCorporaServi( 1018): UpdateCorporaTask done [took 341 ms] updated apps [took 341 ms] 
I/art     (  463): Explicit concurrent mark sweep GC freed 10209(452KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/28MB, paused 1.942ms total 704.946ms
I/ActivityManager(  463): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=2365 uid=10006 gids={50006, 9997, 1028, 1015, 1023} abi=arm64-v8a
I/ActivityManager(  463): Killing 1902:com.google.android.gm/u0a71 (adj 15): empty #17
D/AndroidRuntime( 2294): Shutting down VM
W/libprocessgroup(  463): failed to open /acct/uid_10071/pid_1902/cgroup.procs: No such file or directory
D/ExternalStorage( 2365): After updating volumes, found 1 active roots
W/DriveInitializer( 1189): Awaiting to be initialized
W/DriveInitializer( 1189): Background init thread started
W/ResourcesManager( 2149): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2149): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/SQLiteLog( 1189): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/native  (  828): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
W/DriveInitializer( 1189): Background init thread ended
E/native  (  828): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/DriveAsyncService( 1189): disk I/O error (code 3850)
E/DriveAsyncService( 1189): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1189): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1189): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1189): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1189): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1189): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1189): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1189): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1189): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1189): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1189): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1189): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1189): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1189): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1189): 	at java.lang.Thread.run(Thread.java:818)
E/native  (  828): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  (  828): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  (  828): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  (  828): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  (  828): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  (  828): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
D/Documents( 2342): Update found 7 roots in 553ms
D/Documents( 2342): Update found 7 roots in 240ms

```
