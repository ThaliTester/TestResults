#### Test 6136236661fd38c_thali05_htc-Nexus 9 Logs


```
--------- beginning of system
,I/PowerManagerService(  462): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  462): Sleeping (uid 1000)...
--------- beginning of main
I/HotwordDetector( 1008): Closing mic
I/WifiNative-HAL(  462): startHal
E/wifi    (  462): getStaticLongField sWifiHalHandle 0x7f855c9390
I/WifiHAL (  462): Initializing wifi
I/WifiHAL (  462): Creating socket
I/MicrophoneInputStream( 1008): mic_close com.google.android.apps.gsa.speech.audio.u@1af2b347
E/audio_a2dp_hw(  202): adev_set_parameters: ERROR: set param called even when stream out is null
I/SoundTriggerHwService::Module(  202): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/WifiHAL (  462): Initialized Wifi HAL Successfully; vendor cmd = 103
D/wifi    (  462): Did set static halHandle = 0x556f268d90
D/wifi    (  462): halHandle = 0x556f268d90, mVM = 0x556e7c12d0, mCls = 0x20132e
E/wifi    (  462): getStaticLongField sWifiHalHandle 0x7f855c9300
D/wifi    (  462): array field set
I/WifiNative-HAL(  462): interface[0] = wlan0
I/HotwordRecognitionRnr( 1008): Stopping hotword detection.
E/wifi    (  462): android_net_wifi_getLinkLayerStats: failed to get link statistics
I/HotwordRecognitionRnr( 1008): Hotword detection finished
I/WifiNative-HAL(  462): Waiting for HAL events mWifiHalHandle=366937017744
D/wifi    (  462): waitForHalEvents called, vm = 0x556e7c12d0, obj = 0x20132e, env = 0x556f09fb70
E/wifi    (  462): getStaticLongField sWifiHalHandle 0x7f865887b0
I/ActivityManager(  462): Killing 1387:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
I/ActivityManager(  462): Killing 1868:com.google.android.deskclock/u0a38 (adj 15): empty #18
D/PermissionCache(  150): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (119 us)
D/AndroidRuntime( 2198): 
D/AndroidRuntime( 2198): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2198): CheckJNI is OFF
W/libprocessgroup(  462): failed to open /acct/uid_10045/pid_1387/cgroup.procs: No such file or directory
W/libprocessgroup(  462): failed to open /acct/uid_10038/pid_1868/cgroup.procs: No such file or directory
D/AndroidRuntime( 2198): Calling main entry com.android.commands.am.Am
I/ActivityManager(  462): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  462): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2214 uid=10082 gids={50082, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2198): Shutting down VM
E/wifi    (  462): android_net_wifi_getLinkLayerStats: failed to get link statistics
E/audio_a2dp_hw(  202): adev_set_parameters: ERROR: set param called even when stream out is null
I/WebViewFactory( 2214): Loading com.google.android.webview version 44.0.2403.90 (code 240309050)
I/LibraryLoader( 2214): Time to load native libraries: 18 ms (timestamps 1130-1148)
I/LibraryLoader( 2214): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 2214): Binding Chromium to main looper Looper (main, tid 1) {14b2a6cc}
,I/LibraryLoader( 2214): Expected native library version number "",actual native library version number ""
,I/chromium( 2214): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2214): Initializing chromium process, singleProcess=true
,W/art     ( 2214): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2214): ApplicationContext is null in ApplicationStatus
,W/chromium( 2214): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,D/SurfaceFlinger(  150): Set power mode=0, type=0 flinger=0x55b0c2c3c0
D/hwcomposer(  150): hwc_blank: display 0: blank
D/hwcomposer(  150): hwc_blank_display: display 0: [0 -> 1]
,I/DisplayManagerService(  462): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1536 x 2048, 59.0 fps, supportedRefreshRates [59.0], density 320, 288.995 x 288.995 dpi, appVsyncOff 0, presDeadline 17949152, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  462): Display changed displayId=0
,W/chromium( 2214): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2214): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2214): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,W/ActivityManager(  462): Activity pause timeout for ActivityRecord{2ea48527 u0 com.test.thalitest/.MainActivity t29}
,D/BluetoothManagerService(  462): Message: 20
D/BluetoothManagerService(  462): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b05d9e9:true
D/BluetoothAdapter( 2214): 667509688: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2214): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2214): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2214): CordovaWebView is running on device made by: htc
,W/art     ( 2214): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2214): Attempt to remove local handle scope entry from IRT, ignoring
,D/SurfaceControl(  462): Excessive delay in setPowerMode(): 360ms
,D/OpenGLRenderer( 2214): Render dirty regions requested: true
,W/chromium( 2214): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2214): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2214): Enabling debug mode 0
,I/Keyboard.Facilitator(  830): onFinishInput()
,I/ActivityManager(  462): Displayed com.test.thalitest/.MainActivity: +820ms (total +867ms)
,W/IInputConnectionWrapper( 2214): showStatusIcon on inactive InputConnection
,W/BindingManager( 2214): Cannot call determinedVisibility() - never saw a connection for the pid: 2214
,D/JsMessageQueue( 2214): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2214): JniHelper::setJavaVM(0xab828290), pthread_self() = -1412874352
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2214): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2214):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2214):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2214):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2214):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2214): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f811e18 added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2214): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2214):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2214):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2214):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2214):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2214):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2214):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2214):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2214):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2214):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2214): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11200ed7 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2214): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  462): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2214): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2214): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2214): setDiscoveryMode: Discovery mode BLE is supported
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2214): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2214): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 2214): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 2214): Initializing JXcore engine
W/jxcore-log( 2214): JXcore engine is ready
,W/Thread-53( 2260): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9653]" dev="sockfs" ino=9653 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-53( 2260): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=449 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-53( 2260): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[11001]" dev="sockfs" ino=11001 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-53( 2260): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17276]" dev="sockfs" ino=17276 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 2214): Starting JXcore engine
,W/jxcore-log( 2214): Platform android
W/jxcore-log( 2214): 
W/jxcore-log( 2214): Process ARCH arm
W/jxcore-log( 2214): 
,I/jxcore-log( 2214): JXcore Cordova bridge is ready!
I/jxcore-log( 2214): 
W/jxcore-log( 2214): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 2214): SDK.Build.VERSION: 21
,I/org.thaliproject.p2p.ThaliPermissions( 2214): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 2214): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 2214): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 2214): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,I/ActivityManager(  462): Killing 1926:com.google.android.gm.exchange/u0a70 (adj 15): empty #17
,W/libprocessgroup(  462): failed to open /acct/uid_10070/pid_1926/cgroup.procs: No such file or directory
,W/PluginManager( 2214): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 116ms. Plugin should use CordovaInterface.getThreadPool().
,I/Keyboard.Facilitator.LanguageModelFlusher(  830): run()
I/Keyboard.Facilitator(  830): flushDynamicLanguageModels()
,I/ConfigService( 1051): onCreate
,I/ConfigService( 1051): onDestroy
,V/GLSActivity( 1051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1051): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1051): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1051): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1051): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1051): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1051): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1051): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1658): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1658): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 1658): Ignoring header User-Agent because its value was null.
,V/GLSActivity( 1051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1051): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1051): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1051): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1051): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1051): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1051): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1051): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1658): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1658): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 1658): Ignoring header User-Agent because its value was null.
,D/Finsky  ( 1658): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  462): Explicit concurrent mark sweep GC freed 22171(1158KB) AllocSpace objects, 6(160KB) LOS objects, 33% free, 19MB/28MB, paused 1.043ms total 136.531ms
,I/GLSUser ( 1051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 1658): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 1658): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 1658): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 1658): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 1658): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 1658): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/DeviceConnectionService( 1000): client connected with version: 7571000
,D/Finsky  ( 1658): [190] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 1658): [1] 5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1051): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1051): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1051): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1051): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1051): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1051): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1051): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1658): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1658): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 1658): Ignoring header User-Agent because its value was null.
,I/UsageStatsService(  462): User[0] Flushing usage stats to disk
,V/GLSActivity( 1051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1051): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1051): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1051): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1051): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1051): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1051): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1051): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1658): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1658): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 1658): Ignoring header User-Agent because its value was null.
,V/GLSActivity( 1051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1051): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1051): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1051): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1051): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1051): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1051): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1051): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1658): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1658): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 1658): Ignoring header User-Agent because its value was null.
,I/VacuumService( 1051): Vacuum at: now=1457014980404 tag=VacuumService
,I/art     ( 1051): Explicit concurrent mark sweep GC freed 35830(2MB) AllocSpace objects, 11(440KB) LOS objects, 40% free, 10MB/17MB, paused 1.129ms total 68.941ms
,D/Batterystats( 1190): User is not opted-in to Usage & Diagnostics.
,TIME-OUT KILL (timeout was 1400000ms),D/AndroidRuntime( 2299): 
D/AndroidRuntime( 2299): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2299): CheckJNI is OFF
D/AndroidRuntime( 2299): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  462): Force stopping com.test.thalitest appid=10082 user=-1: uninstall pkg
I/ActivityManager(  462): Killing 2214:com.test.thalitest/u0a82 (adj 9): stop com.test.thalitest
W/PackageSettings(  462): Skipping PackageSetting{305d4e19 com.example.hello/10095} due to missing metadata
D/WifiService(  462): Client connection lost with reason: 4
W/ActivityManager(  462): Spurious death for ProcessRecord{28599438 2214:com.test.thalitest/u0a82}, curProc for 2214: null
I/ActivityManager(  462): Force stopping com.test.thalitest appid=10082 user=0: pkg removed
I/art     (  940): Explicit concurrent mark sweep GC freed 15406(696KB) AllocSpace objects, 3(252KB) LOS objects, 40% free, 14MB/24MB, paused 464us total 68.665ms
I/InputReader(  462): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1000): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator(  830): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer(  830): run()
D/VoicemailCleanupService(  980): Cleaning up data for package: com.test.thalitest
I/Decoder (  830): createOrResetDecoder
I/ActivityManager(  462): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2314 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=arm64-v8a
I/art     (  462): Explicit concurrent mark sweep GC freed 21826(1256KB) AllocSpace objects, 10(260KB) LOS objects, 33% free, 19MB/28MB, paused 6.612ms total 208.903ms
I/art     ( 1008): Explicit concurrent mark sweep GC freed 2225(178KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 12MB/17MB, paused 480us total 299.350ms
I/ConfigService( 1051): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader(  830): run()
D/BackupManagerService(  462): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  462): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  462): removeObsoleteFile: deleting file=29_task.xml
W/InputMethodManagerService(  462): Got RemoteException sending setActive(false) notification to pid 2214 uid 10082
I/Keyboard.Facilitator(  830): onFinishInput()
W/ContextImpl( 2314): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/Keyboard.Facilitator.MainLanguageModelLoader(  830): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5150672, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  830): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  830): run() : Loading LM = contacts
E/NetworkScheduler.SchedulerReceiver( 1051): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1051): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  830): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  830): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  830): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  830): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader(  830): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader(  830): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper(  830): run()
I/Keyboard.Facilitator.RecurringTaskScheduler(  830): run()
I/StatsUtilsManager(  830): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder(  830): shouldRecordStats() = Too Soon
I/Launcher(  940): Deferring update until onResume
D/ChimeraCfgMgr( 1190): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1190): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1190): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1190): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1190): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1190): Clearing selected account for com.test.thalitest
W/Launcher(  940): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@15e2acf6 new=com.google.android.velvet.VelvetApplication@15e2acf6
I/UpdateIcingCorporaServi( 1008): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/LocationSettingsChecker( 1190): Removing dialog suppression flag for package com.test.thalitest
I/ActivityManager(  462): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=2344 uid=10039 gids={50039, 9997} abi=arm64-v8a
D/GOOGLEHELP_CompatibleDatabase( 1190): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1190): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
I/ConfigFetchService( 1190): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
D/gH_MetricsDatabase( 1190): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1190): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/art     (  462): Explicit concurrent mark sweep GC freed 9008(461KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/28MB, paused 4.270ms total 452.963ms
W/BaseAppContext( 1190): Using Auth Proxy for data requests.
D/GOOGLEHELP_CompatibleDatabase( 1190): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1190): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1190): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
W/BaseAppContext( 1190): Using Auth Proxy for data requests.
I/ConfigFetchService( 1190): service connected
I/PeopleContactsSync( 1190): CP2 sync disabled
D/GOOGLEHELP_CompatibleDatabase( 1190): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1190): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
I/Icing   ( 1190): doRemovePackageData com.test.thalitest
D/GOOGLEHELP_CompatibleDatabase( 1190): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1190): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1190): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1190): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/UpdateIcingCorporaServi( 1008): UpdateCorporaTask done [took 321 ms] updated apps [took 321 ms] 
D/AndroidRuntime( 2299): Shutting down VM
I/ActivityManager(  462): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=2368 uid=10006 gids={50006, 9997, 1028, 1015, 1023} abi=arm64-v8a
I/ActivityManager(  462): Killing 1898:com.google.android.gm/u0a71 (adj 15): empty #17
W/libprocessgroup(  462): failed to open /acct/uid_10071/pid_1898/cgroup.procs: No such file or directory
D/ExternalStorage( 2368): After updating volumes, found 1 active roots
W/DriveInitializer( 1190): Awaiting to be initialized
W/DriveInitializer( 1190): Background init thread started
E/SQLiteLog( 1190): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock112] disk I/O error
E/DocListDatabase( 1190): Failed to delete from ContentFileDeletionLock112
E/DocListDatabase( 1190): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1190): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1190): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1190): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1190): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1190): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1190): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 1190): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/DocListDatabase( 1190): 	at com.google.android.gms.drive.r.run(SourceFile:69)
W/DriveInitializer( 1190): Background init thread ended
--------- beginning of crash
E/AndroidRuntime( 1190): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1190): Process: com.google.android.gms, PID: 1190
E/AndroidRuntime( 1190): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1190): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1190): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1190): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1190): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1190): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1190): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/AndroidRuntime( 1190): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/AndroidRuntime( 1190): 	at com.google.android.gms.drive.r.run(SourceFile:69)
E/SQLiteLog( 1190): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
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
I/Process ( 1190): Sending signal. PID: 1190 SIG: 9
E/DropBoxManagerService(  462): Can't write: system_app_crash
E/DropBoxManagerService(  462): java.io.FileNotFoundException: /data/system/dropbox/drop82.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  462): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  462): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  462): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  462): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  462): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  462): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  462): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  462): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  462): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  462): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  462): 	... 5 more
W/ResourcesManager( 2147): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2147): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  462): Process com.google.android.gms (pid 1190) has died
W/ActivityManager(  462): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  462): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  462): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  462): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 21000ms

```
