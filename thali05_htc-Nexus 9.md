#### Test 613623660556c10_thali05_htc-Nexus 9 Logs


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
D/AndroidRuntime( 2206): 
D/AndroidRuntime( 2206): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2206): CheckJNI is OFF
D/AndroidRuntime( 2206): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  462): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  462): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2220 uid=10082 gids={50082, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2206): Shutting down VM
V/ActivityManager(  462): Display changed displayId=0
,I/WebViewFactory( 2220): Loading com.google.android.webview version 44.0.2403.90 (code 240309050)
,I/LibraryLoader( 2220): Time to load native libraries: 21 ms (timestamps 643-664)
I/LibraryLoader( 2220): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 2220): Binding Chromium to main looper Looper (main, tid 1) {8f06470}
I/LibraryLoader( 2220): Expected native library version number "",actual native library version number ""
,I/chromium( 2220): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2220): Initializing chromium process, singleProcess=true
,W/art     ( 2220): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2220): ApplicationContext is null in ApplicationStatus
,W/chromium( 2220): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2220): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2220): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2220): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,W/ActivityManager(  462): Activity pause timeout for ActivityRecord{10e5eb01 u0 com.test.thalitest/.MainActivity t29}
,D/BluetoothManagerService(  462): Message: 20
D/BluetoothManagerService(  462): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@233e392c:true
,D/BluetoothAdapter( 2220): 924821803: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2220): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2220): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2220): CordovaWebView is running on device made by: htc
,W/art     ( 2220): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2220): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2220): Render dirty regions requested: true
,W/chromium( 2220): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2220): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2220): Enabling debug mode 0
,I/Keyboard.Facilitator(  826): onFinishInput()
,I/ActivityManager(  462): Displayed com.test.thalitest/.MainActivity: +1s222ms (total +1s334ms)
W/IInputConnectionWrapper( 2220): showStatusIcon on inactive InputConnection
,W/BindingManager( 2220): Cannot call determinedVisibility() - never saw a connection for the pid: 2220
,D/JsMessageQueue( 2220): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2220): JniHelper::setJavaVM(0xab752290), pthread_self() = -1413754784
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2220): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2220):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2220):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2220):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2220):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2220): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b86d3fc added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2220): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2220):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2220):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2220):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2220):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2220):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2220):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2220):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2220):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2220):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2220): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2311190b added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2220): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  462): New client listening to asynchronous messages
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2220): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2220): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2220): setDiscoveryMode: Discovery mode BLE is supported
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2220): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2220): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 2220): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     ( 2220): Background partial concurrent mark sweep GC freed 11081(862KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 12MB/20MB, paused 5.030ms total 78.201ms
,W/jxcore-log( 2220): Initializing JXcore engine
W/jxcore-log( 2220): JXcore engine is ready
,I/art     ( 2220): Background sticky concurrent mark sweep GC freed 20037(1790KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 20MB/20MB, paused 5.341ms total 53.767ms
,W/Thread-54( 2268): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[10362]" dev="sockfs" ino=10362 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-54( 2268): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=449 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-54( 2268): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10524]" dev="sockfs" ino=10524 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-54( 2268): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17508]" dev="sockfs" ino=17508 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 2220): Starting JXcore engine
,W/jxcore-log( 2220): Platform android
W/jxcore-log( 2220): 
W/jxcore-log( 2220): Process ARCH arm
W/jxcore-log( 2220): 
,I/jxcore-log( 2220): JXcore Cordova bridge is ready!
I/jxcore-log( 2220): 
W/jxcore-log( 2220): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 2220): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 2220): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 2220): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 2220): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,I/ActivityManager(  462): Killing 1928:com.google.android.gm.exchange/u0a70 (adj 15): empty #17
,W/libprocessgroup(  462): failed to open /acct/uid_10070/pid_1928/cgroup.procs: No such file or directory
,W/PluginManager( 2220): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 63ms. Plugin should use CordovaInterface.getThreadPool().
,I/Keyboard.Facilitator.LanguageModelFlusher(  826): run()
I/Keyboard.Facilitator(  826): flushDynamicLanguageModels()
,I/ConfigService( 1042): onCreate
,I/ConfigService( 1042): onDestroy
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
,I/art     (  462): Explicit concurrent mark sweep GC freed 20489(1058KB) AllocSpace objects, 4(100KB) LOS objects, 33% free, 19MB/28MB, paused 960us total 157.858ms
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
,I/UsageStatsService(  462): User[0] Flushing usage stats to disk
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
W/System  ( 1669): Ignoring header User-Agent because its value was null.
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 2287): 
D/AndroidRuntime( 2287): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2287): CheckJNI is OFF
D/AndroidRuntime( 2287): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  462): Force stopping com.test.thalitest appid=10082 user=-1: uninstall pkg
I/ActivityManager(  462): Killing 2220:com.test.thalitest/u0a82 (adj 9): stop com.test.thalitest
D/WifiService(  462): Client connection lost with reason: 4
W/PackageSettings(  462): Skipping PackageSetting{497bb02 com.example.hello/10095} due to missing metadata
W/ActivityManager(  462): Spurious death for ProcessRecord{2e4152f0 2220:com.test.thalitest/u0a82}, curProc for 2220: null
I/ActivityManager(  462): Force stopping com.test.thalitest appid=10082 user=0: pkg removed
I/art     (  936): Explicit concurrent mark sweep GC freed 13064(598KB) AllocSpace objects, 4(336KB) LOS objects, 40% free, 14MB/24MB, paused 760us total 71.285ms
W/GeofencerStateMachine( 1022): Ignoring removeGeofence because network location is disabled.
I/InputReader(  462): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator(  826): resetDictionaries() : en_US
I/art     (  993): Explicit concurrent mark sweep GC freed 2034(160KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 12MB/16MB, paused 460us total 188.803ms
D/VoicemailCleanupService(  979): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.DecoderInitializer(  826): run()
I/art     (  462): Explicit concurrent mark sweep GC freed 12448(884KB) AllocSpace objects, 10(260KB) LOS objects, 33% free, 18MB/28MB, paused 1.745ms total 234.207ms
I/art     (  462): WaitForGcToComplete blocked for 76.297ms for cause Explicit
I/ActivityManager(  462): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2303 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=arm64-v8a
I/Decoder (  826): createOrResetDecoder
I/ConfigService( 1042): onCreate
W/ContextImpl( 2303): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
D/BackupManagerService(  462): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  462): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  462): removeObsoleteFile: deleting file=29_task.xml
I/Keyboard.Facilitator.MainLanguageModelLoader(  826): run()
W/InputMethodManagerService(  462): Got RemoteException sending setActive(false) notification to pid 2220 uid 10082
I/Keyboard.Facilitator(  826): onFinishInput()
E/NetworkScheduler.SchedulerReceiver( 1042): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1042): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Keyboard.Facilitator.MainLanguageModelLoader(  826): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5150672, length=4014912) with up to date LoudsLmContentVersion = 20150512
D/PackageBroadcastService( 1183): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1183): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1183): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1183): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1183): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1183): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  826): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  826): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  826): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  826): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  826): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  826): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  826): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader(  826): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper(  826): run()
I/Keyboard.Facilitator.RecurringTaskScheduler(  826): run()
I/StatsUtilsManager(  826): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder(  826): shouldRecordStats() = Too Soon
I/LocationSettingsChecker( 1183): Removing dialog suppression flag for package com.test.thalitest
W/Launcher(  936): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@14e06ecb new=com.google.android.velvet.VelvetApplication@14e06ecb
I/UpdateIcingCorporaServi(  993): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ConfigFetchService( 1183): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
D/GOOGLEHELP_CompatibleDatabase( 1183): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1183): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1183): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1183): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/ActivityManager(  462): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
D/GOOGLEHELP_CompatibleDatabase( 1183): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1183): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
W/BaseAppContext( 1183): Using Auth Proxy for data requests.
D/GOOGLEHELP_CompatibleDatabase( 1183): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/ConfigFetchService( 1183): service connected
D/GOOGLEHELP_CompatibleDatabase( 1183): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1183): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1183): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
I/PeopleContactsSync( 1183): CP2 sync disabled
W/BaseAppContext( 1183): Using Auth Proxy for data requests.
D/GOOGLEHELP_CompatibleDatabase( 1183): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1183): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1183): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  462): Resuming delayed broadcast
I/Icing   ( 1183): doRemovePackageData com.test.thalitest
I/ActivityManager(  462): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=2336 uid=10039 gids={50039, 9997} abi=arm64-v8a
I/UpdateIcingCorporaServi(  993): UpdateCorporaTask done [took 295 ms] updated apps [took 295 ms] 
I/art     (  462): Explicit concurrent mark sweep GC freed 8493(393KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/28MB, paused 7.268ms total 659.642ms
I/Launcher(  936): Deferring update until onResume
D/AndroidRuntime( 2287): Shutting down VM
I/ActivityManager(  462): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=2356 uid=10006 gids={50006, 9997, 1028, 1015, 1023} abi=arm64-v8a
I/art     ( 1042): Explicit concurrent mark sweep GC freed 20724(1216KB) AllocSpace objects, 13(480KB) LOS objects, 40% free, 10MB/17MB, paused 550us total 70.343ms
W/DriveInitializer( 1183): Awaiting to be initialized
W/DriveInitializer( 1183): Background init thread started
I/ActivityManager(  462): Killing 1907:com.google.android.gm/u0a71 (adj 15): empty #17
W/libprocessgroup(  462): failed to open /acct/uid_10071/pid_1907/cgroup.procs: No such file or directory
D/ExternalStorage( 2356): After updating volumes, found 1 active roots
W/DriveInitializer( 1183): Background init thread ended
W/ResourcesManager( 2143): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2143): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/SQLiteDatabase( 1042): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1042): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1042): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1042): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1042): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1042): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1042): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1042): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1042): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1042): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1042): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1042): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1042): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1042): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1042): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1042): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1042): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1042): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1042): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1042): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1042): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1042): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1042): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 1042): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1042): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1042): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1042): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1042): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1042): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1042): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1042): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1042): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1042): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1042): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1042): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteOpenHelper( 1042): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1042): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1042): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1042): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1042): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1042): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1042): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1042): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1042): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1042): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1042): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 1042): Opened phenotype.db in read-only mode
E/SQLiteLog( 1042): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1042): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1042): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1042): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1042): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1042): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1042): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1042): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1042): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1042): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1042): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1042): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1042): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1042): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1042): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1042): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1042): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1042): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1042): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1042): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1042): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1042): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1042): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1042): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1042): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1042): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1042): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1042): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1042): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1042): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1042): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1042): 	at java.lang.Thread.run(Thread.java:818)
D/Documents( 2336): Update found 7 roots in 464ms
D/Documents( 2336): Update found 7 roots in 138ms

```
