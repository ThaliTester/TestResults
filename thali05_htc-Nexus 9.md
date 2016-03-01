#### Test 6122644500803c8_thali05_htc-Nexus 9 Logs


```
--------- beginning of system
,I/PowerManagerService(  464): Going to sleep due to screen timeout (uid 1000)...
--------- beginning of main
I/MicrophoneInputStream( 1006): mic_close com.google.android.apps.gsa.speech.audio.u@1dd41509
I/HotwordDetector( 1006): Closing mic
I/SoundTriggerHwService::Module(  205): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1006): Stopping hotword detection.
I/HotwordRecognitionRnr( 1006): Hotword detection finished
I/PowerManagerService(  464): Sleeping (uid 1000)...
I/WifiNative-HAL(  464): startHal
E/wifi    (  464): getStaticLongField sWifiHalHandle 0x7f634d0390
I/WifiHAL (  464): Initializing wifi
I/WifiHAL (  464): Creating socket
I/WifiHAL (  464): Initialized Wifi HAL Successfully; vendor cmd = 103
D/wifi    (  464): Did set static halHandle = 0x557a120f10
D/wifi    (  464): halHandle = 0x557a120f10, mVM = 0x557975b2d0, mCls = 0x40119e
E/wifi    (  464): getStaticLongField sWifiHalHandle 0x7f634d0300
D/wifi    (  464): array field set
I/WifiNative-HAL(  464): interface[0] = wlan0
E/wifi    (  464): android_net_wifi_getLinkLayerStats: failed to get link statistics
E/audio_a2dp_hw(  205): adev_set_parameters: ERROR: set param called even when stream out is null
I/WifiNative-HAL(  464): Waiting for HAL events mWifiHalHandle=367120224016
D/wifi    (  464): waitForHalEvents called, vm = 0x557975b2d0, obj = 0x40119e, env = 0x5579e38260
E/wifi    (  464): getStaticLongField sWifiHalHandle 0x7f628887b0
I/ActivityManager(  464): Killing 1858:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
D/PermissionCache(  152): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (113 us)
D/AndroidRuntime( 2184): 
D/AndroidRuntime( 2184): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2184): CheckJNI is OFF
I/ActivityManager(  464): Killing 1875:com.google.android.deskclock/u0a38 (adj 15): empty #18
D/AndroidRuntime( 2184): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  464): failed to open /acct/uid_10045/pid_1858/cgroup.procs: No such file or directory
I/ActivityManager(  464): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  464): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2201 uid=10082 gids={50082, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup(  464): failed to open /acct/uid_10038/pid_1875/cgroup.procs: No such file or directory
D/AndroidRuntime( 2184): Shutting down VM
E/wifi    (  464): android_net_wifi_getLinkLayerStats: failed to get link statistics
E/audio_a2dp_hw(  205): adev_set_parameters: ERROR: set param called even when stream out is null
I/WebViewFactory( 2201): Loading com.google.android.webview version 44.0.2403.90 (code 240309050)
,I/LibraryLoader( 2201): Time to load native libraries: 18 ms (timestamps 1311-1329)
I/LibraryLoader( 2201): Expected native library version number "",actual native library version number ""
,D/SurfaceFlinger(  152): Set power mode=0, type=0 flinger=0x5570cf33c0
D/hwcomposer(  152): hwc_blank: display 0: blank
D/hwcomposer(  152): hwc_blank_display: display 0: [0 -> 1]
I/DisplayManagerService(  464): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1536 x 2048, 59.0 fps, supportedRefreshRates [59.0], density 320, 288.995 x 288.995 dpi, appVsyncOff 0, presDeadline 17949152, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  464): Display changed displayId=0
,V/WebViewChromiumFactoryProvider( 2201): Binding Chromium to main looper Looper (main, tid 1) {123a92a9}
,I/LibraryLoader( 2201): Expected native library version number "",actual native library version number ""
,I/chromium( 2201): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2201): Initializing chromium process, singleProcess=true
,W/art     ( 2201): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2201): ApplicationContext is null in ApplicationStatus
,W/chromium( 2201): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2201): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2201): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2201): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,W/ActivityManager(  464): Activity pause timeout for ActivityRecord{1d693f7d u0 com.test.thalitest/.MainActivity t29}
,D/BluetoothAdapter( 2201): 1042813242: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  464): Message: 20
D/BluetoothManagerService(  464): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39d281a5:true
,D/SurfaceControl(  464): Excessive delay in setPowerMode(): 364ms
,W/art     ( 2201): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2201): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2201): CordovaWebView is running on device made by: htc
,W/art     ( 2201): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 2201): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2201): Render dirty regions requested: true
,W/chromium( 2201): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2201): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2201): Enabling debug mode 0
,I/ActivityManager(  464): Displayed com.test.thalitest/.MainActivity: +925ms (total +1s7ms)
,W/IInputConnectionWrapper( 2201): showStatusIcon on inactive InputConnection
,W/BindingManager( 2201): Cannot call determinedVisibility() - never saw a connection for the pid: 2201
,D/JsMessageQueue( 2201): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2201): JniHelper::setJavaVM(0xab132290), pthread_self() = -1420123128
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2201): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2201):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2201):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2201):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2201):     - Handshake required: true
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2201): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24724545 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2201): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2201): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2201):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2201):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2201):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2201):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2201):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2201):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2201):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2201):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2201):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2201): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@295ecda8 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2201): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  464): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2201): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2201): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2201): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2201): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2201): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2201): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2201): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2201): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 2201): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 2201): Initializing JXcore engine
W/jxcore-log( 2201): JXcore engine is ready
W/Thread-54( 2249): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[10343]" dev="sockfs" ino=10343 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-54( 2249): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=449 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-54( 2249): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[11309]" dev="sockfs" ino=11309 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-54( 2249): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17760]" dev="sockfs" ino=17760 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 2201): Starting JXcore engine
W/jxcore-log( 2201): Platform android
W/jxcore-log( 2201): 
W/jxcore-log( 2201): Process ARCH arm
W/jxcore-log( 2201): 
,I/jxcore-log( 2201): JXcore Cordova bridge is ready!
I/jxcore-log( 2201): 
,W/jxcore-log( 2201): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 2201): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 2201): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 2201): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 2201): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,I/ActivityManager(  464): Killing 1917:com.google.android.gm.exchange/u0a70 (adj 15): empty #17
,W/libprocessgroup(  464): failed to open /acct/uid_10070/pid_1917/cgroup.procs: No such file or directory
,W/PluginManager( 2201): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 62ms. Plugin should use CordovaInterface.getThreadPool().
,V/GLSActivity( 1055): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1055): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1055): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1055): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1055): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1055): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1055): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1055): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1055): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1055): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1055): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1055): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1055): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1658): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1658): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 1658): Ignoring header User-Agent because its value was null.
,V/GLSActivity( 1055): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1055): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1055): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1055): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1055): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1055): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  464): Explicit concurrent mark sweep GC freed 21180(1128KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 19MB/28MB, paused 1.069ms total 128.862ms
,W/GLSActivity( 1055): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1055): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1055): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1055): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1055): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1055): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1055): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1658): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1658): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 1658): Ignoring header User-Agent because its value was null.
,V/GLSActivity( 1055): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1055): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1055): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1055): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1055): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1055): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1055): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1055): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1055): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1055): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1055): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1055): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1055): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1658): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1658): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 1658): Ignoring header User-Agent because its value was null.
,I/UsageStatsService(  464): User[0] Flushing usage stats to disk
,V/GLSActivity( 1055): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1055): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1055): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1055): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1055): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1055): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1055): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1055): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1055): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1055): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1055): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1055): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1055): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1658): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1658): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 1658): Ignoring header User-Agent because its value was null.
,I/EventLogService( 1193): Aggregate from 1456844723129 (log), 1456844723129 (data)
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 2276): 
D/AndroidRuntime( 2276): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2276): CheckJNI is OFF
D/AndroidRuntime( 2276): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  464): Force stopping com.test.thalitest appid=10082 user=-1: uninstall pkg
I/ActivityManager(  464): Killing 2201:com.test.thalitest/u0a82 (adj 9): stop com.test.thalitest
D/WifiService(  464): Client connection lost with reason: 4
W/ActivityManager(  464): Spurious death for ProcessRecord{2ec4839a 2201:com.test.thalitest/u0a82}, curProc for 2201: null
W/PackageSettings(  464): Skipping PackageSetting{3565466d com.example.hello/10095} due to missing metadata
I/ActivityManager(  464): Force stopping com.test.thalitest appid=10082 user=0: pkg removed
W/GeofencerStateMachine( 1037): Ignoring removeGeofence because network location is disabled.
I/InputReader(  464): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator(  832): resetDictionaries() : en_US
I/art     (  934): Explicit concurrent mark sweep GC freed 9271(485KB) AllocSpace objects, 4(336KB) LOS objects, 40% free, 14MB/23MB, paused 1.360ms total 72.969ms
I/ActivityManager(  464): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2291 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=arm64-v8a
I/Keyboard.Facilitator.DecoderInitializer(  832): run()
D/VoicemailCleanupService(  964): Cleaning up data for package: com.test.thalitest
I/art     (  464): Explicit concurrent mark sweep GC freed 13511(970KB) AllocSpace objects, 10(260KB) LOS objects, 33% free, 18MB/28MB, paused 5.859ms total 209.693ms
I/art     (  464): WaitForGcToComplete blocked for 214.316ms for cause Explicit
I/Decoder (  832): createOrResetDecoder
I/ConfigService( 1055): onCreate
D/BackupManagerService(  464): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  464): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.MainLanguageModelLoader(  832): run()
D/TaskPersister(  464): removeObsoleteFile: deleting file=29_task.xml
I/Keyboard.Facilitator.MainLanguageModelLoader(  832): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5150672, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  832): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  832): run() : Loading LM = contacts
W/ContextImpl( 2291): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
E/NetworkScheduler.SchedulerReceiver( 1055): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1055): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  832): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  832): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  832): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  832): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  832): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader(  832): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper(  832): run()
I/Keyboard.Facilitator.RecurringTaskScheduler(  832): run()
I/StatsUtilsManager(  832): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder(  832): shouldRecordStats() = Too Soon
I/art     ( 1006): Explicit concurrent mark sweep GC freed 1851(146KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 12MB/16MB, paused 436us total 387.199ms
D/ChimeraCfgMgr( 1193): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1193): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1193): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1193): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1193): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1193): Clearing selected account for com.test.thalitest
W/Launcher(  934): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3e28113a new=com.google.android.velvet.VelvetApplication@3e28113a
I/UpdateIcingCorporaServi( 1006): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/LocationSettingsChecker( 1193): Removing dialog suppression flag for package com.test.thalitest
D/GOOGLEHELP_CompatibleDatabase( 1193): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1193): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1193): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1193): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/ActivityManager(  464): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=2323 uid=10039 gids={50039, 9997} abi=arm64-v8a
D/GOOGLEHELP_CompatibleDatabase( 1193): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1193): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1193): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1193): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1193): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1193): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1193): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1193): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1193): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/BaseAppContext( 1193): Using Auth Proxy for data requests.
W/BaseAppContext( 1193): Using Auth Proxy for data requests.
I/ConfigFetchService( 1193): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1193): service connected
I/PeopleContactsSync( 1193): CP2 sync disabled
I/art     ( 1055): Explicit concurrent mark sweep GC freed 18066(1059KB) AllocSpace objects, 11(400KB) LOS objects, 40% free, 10MB/17MB, paused 695us total 52.370ms
I/Icing   ( 1193): doRemovePackageData com.test.thalitest
I/UpdateIcingCorporaServi( 1006): UpdateCorporaTask done [took 418 ms] updated apps [took 418 ms] 
I/art     (  464): Explicit concurrent mark sweep GC freed 5625(248KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/28MB, paused 2.360ms total 728.371ms
I/ActivityManager(  464): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=2346 uid=10006 gids={50006, 9997, 1028, 1015, 1023} abi=arm64-v8a
I/ActivityManager(  464): Killing 1896:com.google.android.gm/u0a71 (adj 15): empty #17
D/AndroidRuntime( 2276): Shutting down VM
W/libprocessgroup(  464): failed to open /acct/uid_10071/pid_1896/cgroup.procs: No such file or directory
I/Launcher(  934): Deferring update until onResume
W/DriveInitializer( 1193): Awaiting to be initialized
W/DriveInitializer( 1193): Background init thread started
D/ExternalStorage( 2346): After updating volumes, found 1 active roots
W/ResourcesManager( 2133): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2133): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/DriveInitializer( 1193): Background init thread ended
E/SQLiteLog( 1193): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/Documents( 2323): Update found 7 roots in 561ms
E/DriveAsyncService( 1193): disk I/O error (code 3850)
E/DriveAsyncService( 1193): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1193): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1193): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1193): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1193): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1193): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1193): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1193): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1193): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1193): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1193): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1193): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1193): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1193): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1193): 	at java.lang.Thread.run(Thread.java:818)
E/native  (  832): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  (  832): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
D/Documents( 2323): Update found 7 roots in 197ms
E/native  (  832): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  (  832): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  (  832): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  (  832): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  (  832): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  (  832): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp

```
