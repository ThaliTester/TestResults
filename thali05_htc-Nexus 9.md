#### Test 61362366121daa0_thali05_htc-Nexus 9 Logs


```
--------- beginning of main
,V/GLSActivity( 1046): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1046): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1046): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1046): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1046): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1046): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GLSActivity( 1046): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1046): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1046): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1046): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1046): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1046): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1046): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 1657): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1657): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1657): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1657): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1657): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1657): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1657): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 1657): Ignoring header User-Agent because its value was null.
D/AndroidRuntime( 2196): 
D/AndroidRuntime( 2196): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2196): CheckJNI is OFF
D/AndroidRuntime( 2196): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  462): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  462): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2212 uid=10082 gids={50082, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2196): Shutting down VM
V/ActivityManager(  462): Display changed displayId=0
,I/WebViewFactory( 2212): Loading com.google.android.webview version 44.0.2403.90 (code 240309050)
,I/LibraryLoader( 2212): Time to load native libraries: 21 ms (timestamps 2150-2171)
I/LibraryLoader( 2212): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 2212): Binding Chromium to main looper Looper (main, tid 1) {293dae0c}
,I/LibraryLoader( 2212): Expected native library version number "",actual native library version number ""
,I/chromium( 2212): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2212): Initializing chromium process, singleProcess=true
,W/art     ( 2212): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2212): ApplicationContext is null in ApplicationStatus
,W/chromium( 2212): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2212): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,W/ActivityManager(  462): Activity pause timeout for ActivityRecord{37b166fe u0 com.test.thalitest/.MainActivity t29}
,E/libEGL  ( 2212): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2212): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,D/BluetoothManagerService(  462): Message: 20
D/BluetoothManagerService(  462): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d4e6a2d:true
,D/BluetoothAdapter( 2212): 689807096: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2212): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2212): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2212): CordovaWebView is running on device made by: htc
,W/art     ( 2212): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2212): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2212): Render dirty regions requested: true
,W/chromium( 2212): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2212): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2212): Enabling debug mode 0
,I/Keyboard.Facilitator(  833): onFinishInput()
,I/ActivityManager(  462): Displayed com.test.thalitest/.MainActivity: +1s279ms (total +1s380ms)
W/IInputConnectionWrapper( 2212): showStatusIcon on inactive InputConnection
,W/BindingManager( 2212): Cannot call determinedVisibility() - never saw a connection for the pid: 2212
,D/JsMessageQueue( 2212): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2212): JniHelper::setJavaVM(0xab258290), pthread_self() = -1418969248
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2212): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2212):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2212):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2212):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2212):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2212): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2513f958 added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2212): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2212):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2212):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2212):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2212):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2212):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2212):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2212):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2212):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2212):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2212): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9381317 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2212): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  462): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2212): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2212): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2212): setDiscoveryMode: Discovery mode BLE is supported
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2212): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2212): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 2212): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 2212): Initializing JXcore engine
W/jxcore-log( 2212): JXcore engine is ready
,W/Thread-53( 2258): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5983]" dev="sockfs" ino=5983 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-53( 2258): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=449 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-53( 2258): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10413]" dev="sockfs" ino=10413 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-53( 2258): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17019]" dev="sockfs" ino=17019 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 2212): Starting JXcore engine
,W/jxcore-log( 2212): Platform android
W/jxcore-log( 2212): 
,W/jxcore-log( 2212): Process ARCH arm
W/jxcore-log( 2212): 
,I/jxcore-log( 2212): JXcore Cordova bridge is ready!
I/jxcore-log( 2212): 
,W/jxcore-log( 2212): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 2212): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 2212): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 2212): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 2212): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,I/ActivityManager(  462): Killing 1915:com.google.android.gm.exchange/u0a70 (adj 15): empty #17
,W/libprocessgroup(  462): failed to open /acct/uid_10070/pid_1915/cgroup.procs: No such file or directory
,W/PluginManager( 2212): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 62ms. Plugin should use CordovaInterface.getThreadPool().
,I/Keyboard.Facilitator.LanguageModelFlusher(  833): run()
I/Keyboard.Facilitator(  833): flushDynamicLanguageModels()
,I/ConfigService( 1046): onCreate
,I/art     ( 1046): Explicit concurrent mark sweep GC freed 19498(1138KB) AllocSpace objects, 3(120KB) LOS objects, 40% free, 10MB/17MB, paused 593us total 58.253ms
,I/ConfigService( 1046): onDestroy
,V/GLSActivity( 1046): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  462): Explicit concurrent mark sweep GC freed 20029(1021KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 19MB/28MB, paused 992us total 135.362ms
,I/GLSUser ( 1046): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1046): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1046): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1046): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1046): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1046): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1046): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1046): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1046): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1046): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1046): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1046): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1657): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1657): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1657): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1657): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1657): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1657): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1657): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 1657): Ignoring header User-Agent because its value was null.
,V/GLSActivity( 1046): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1046): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1046): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1046): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1046): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1046): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1046): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1046): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1046): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1046): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1046): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1046): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1046): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1657): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1657): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1657): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1657): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1657): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1657): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1657): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 1657): Ignoring header User-Agent because its value was null.
,I/UsageStatsService(  462): User[0] Flushing usage stats to disk
,V/GLSActivity( 1046): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1046): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1046): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1046): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1046): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1046): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1046): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1046): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1046): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1046): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1046): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1046): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1046): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1657): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1657): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1657): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1657): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1657): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1657): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1657): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 1657): Ignoring header User-Agent because its value was null.
,I/EventLogService( 1190): Aggregate from 1456925130920 (log), 1456925130920 (data)
,I/VacuumService( 1046): Vacuum at: now=1456926941638 tag=VacuumService
,V/GLSActivity( 1046): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1046): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1046): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1046): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1046): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1046): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1046): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1046): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1046): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1046): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1046): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1046): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1046): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 1657): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1657): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1657): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1657): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1657): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1657): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1657): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 1657): Ignoring header User-Agent because its value was null.
,TIME-OUT KILL (timeout was 1400000ms),D/AndroidRuntime( 2283): 
D/AndroidRuntime( 2283): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2283): CheckJNI is OFF
D/AndroidRuntime( 2283): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  462): Force stopping com.test.thalitest appid=10082 user=-1: uninstall pkg
I/ActivityManager(  462): Killing 2212:com.test.thalitest/u0a82 (adj 9): stop com.test.thalitest
D/WifiService(  462): Client connection lost with reason: 4
W/PackageSettings(  462): Skipping PackageSetting{285c4059 com.example.hello/10095} due to missing metadata
I/ActivityManager(  462): Force stopping com.test.thalitest appid=10082 user=0: pkg removed
I/art     ( 1026): Explicit concurrent mark sweep GC freed 2279(174KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 12MB/17MB, paused 531us total 91.754ms
W/ActivityManager(  462): Spurious death for ProcessRecord{77188a3 2212:com.test.thalitest/u0a82}, curProc for 2212: null
I/InputReader(  462): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1011): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator(  833): resetDictionaries() : en_US
I/art     (  941): Explicit concurrent mark sweep GC freed 11627(582KB) AllocSpace objects, 4(336KB) LOS objects, 40% free, 14MB/23MB, paused 7.619ms total 152.814ms
I/Keyboard.Facilitator.DecoderInitializer(  833): run()
D/VoicemailCleanupService(  971): Cleaning up data for package: com.test.thalitest
I/Decoder (  833): createOrResetDecoder
I/ActivityManager(  462): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2298 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=arm64-v8a
I/ConfigService( 1046): onCreate
I/art     (  462): Explicit concurrent mark sweep GC freed 17524(1131KB) AllocSpace objects, 11(300KB) LOS objects, 33% free, 18MB/28MB, paused 1.390ms total 286.398ms
I/art     (  462): WaitForGcToComplete blocked for 188.667ms for cause Explicit
W/InputMethodManagerService(  462): Got RemoteException sending setActive(false) notification to pid 2212 uid 10082
I/Keyboard.Facilitator(  833): onFinishInput()
I/Keyboard.Facilitator.MainLanguageModelLoader(  833): run()
W/ContextImpl( 2298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
E/NetworkScheduler.SchedulerReceiver( 1046): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1046): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/BackupManagerService(  462): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  462): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  462): removeObsoleteFile: deleting file=29_task.xml
I/Keyboard.Facilitator.MainLanguageModelLoader(  833): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5150672, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  833): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  833): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  833): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  833): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  833): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  833): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  833): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader(  833): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper(  833): run()
I/Keyboard.Facilitator.RecurringTaskScheduler(  833): run()
I/StatsUtilsManager(  833): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder(  833): shouldRecordStats() = Too Soon
D/ChimeraCfgMgr( 1190): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1190): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1190): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1190): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1190): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1190): Module APK com.google.android.play.games already loaded
I/UpdateIcingCorporaServi( 1026): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher(  941): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@b937a36 new=com.google.android.velvet.VelvetApplication@b937a36
I/LocationSettingsChecker( 1190): Removing dialog suppression flag for package com.test.thalitest
I/ActivityManager(  462): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/ActivityManager(  462): Resuming delayed broadcast
I/ActivityManager(  462): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=2330 uid=10039 gids={50039, 9997} abi=arm64-v8a
I/ConfigFetchService( 1190): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1190): service connected
D/GOOGLEHELP_CompatibleDatabase( 1190): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1190): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1190): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1190): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/PeopleContactsSync( 1190): CP2 sync disabled
D/GOOGLEHELP_CompatibleDatabase( 1190): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1190): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1190): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/UpdateIcingCorporaServi( 1026): UpdateCorporaTask done [took 292 ms] updated apps [took 292 ms] 
I/Icing   ( 1190): doRemovePackageData com.test.thalitest
W/BaseAppContext( 1190): Using Auth Proxy for data requests.
D/GOOGLEHELP_CompatibleDatabase( 1190): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1190): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1190): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1190): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1190): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1190): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/BaseAppContext( 1190): Using Auth Proxy for data requests.
I/art     (  462): Explicit concurrent mark sweep GC freed 8566(407KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/28MB, paused 5.819ms total 659.868ms
I/ActivityManager(  462): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=2353 uid=10006 gids={50006, 9997, 1028, 1015, 1023} abi=arm64-v8a
I/ActivityManager(  462): Killing 1889:com.google.android.gm/u0a71 (adj 15): empty #17
D/AndroidRuntime( 2283): Shutting down VM
W/libprocessgroup(  462): failed to open /acct/uid_10071/pid_1889/cgroup.procs: No such file or directory
I/Launcher(  941): Deferring update until onResume
D/ExternalStorage( 2353): After updating volumes, found 1 active roots
W/DriveInitializer( 1190): Awaiting to be initialized
W/DriveInitializer( 1190): Background init thread started
W/ResourcesManager( 2133): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2133): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 1046): Explicit concurrent mark sweep GC freed 21543(1180KB) AllocSpace objects, 11(400KB) LOS objects, 40% free, 10MB/17MB, paused 1.256ms total 68.066ms
D/Documents( 2330): Update found 7 roots in 632ms
E/SQLiteLog( 1190): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/DriveInitializer( 1190): Background init thread ended
E/DriveAsyncService( 1190): disk I/O error (code 3850)
E/DriveAsyncService( 1190): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1190): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1190): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1190): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1190): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1190): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1190): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1190): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1190): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1190): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1190): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1190): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1190): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1190): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1190): 	at java.lang.Thread.run(Thread.java:818)
E/native  (  833): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  (  833): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  (  833): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  (  833): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  (  833): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  (  833): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  (  833): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  (  833): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
D/Documents( 2330): Update found 7 roots in 287ms

```
