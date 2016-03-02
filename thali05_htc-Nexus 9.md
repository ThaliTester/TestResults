#### Test 613623661dfc74c_thali05_htc-Nexus 9 Logs


```
--------- beginning of system
,I/PowerManagerService(  465): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  465): Sleeping (uid 1000)...
--------- beginning of main
I/MicrophoneInputStream( 1009): mic_close com.google.android.apps.gsa.speech.audio.u@38d6f771
I/HotwordDetector( 1009): Closing mic
I/SoundTriggerHwService::Module(  206): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1009): Hotword detection finished
I/HotwordRecognitionRnr( 1009): Stopping hotword detection.
I/WifiNative-HAL(  465): startHal
E/wifi    (  465): getStaticLongField sWifiHalHandle 0x7f68b7e390
I/WifiHAL (  465): Initializing wifi
I/WifiHAL (  465): Creating socket
I/WifiHAL (  465): Initialized Wifi HAL Successfully; vendor cmd = 103
D/wifi    (  465): Did set static halHandle = 0x5592ba1160
D/wifi    (  465): halHandle = 0x5592ba1160, mVM = 0x559213c2d0, mCls = 0x20130a
E/wifi    (  465): getStaticLongField sWifiHalHandle 0x7f68b7e300
D/wifi    (  465): array field set
I/WifiNative-HAL(  465): interface[0] = wlan0
E/wifi    (  465): android_net_wifi_getLinkLayerStats: failed to get link statistics
I/WifiNative-HAL(  465): Waiting for HAL events mWifiHalHandle=367533887840
D/wifi    (  465): waitForHalEvents called, vm = 0x559213c2d0, obj = 0x20130a, env = 0x559232f4f0
E/wifi    (  465): getStaticLongField sWifiHalHandle 0x7f67e2c7b0
E/audio_a2dp_hw(  206): adev_set_parameters: ERROR: set param called even when stream out is null
D/PermissionCache(  153): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (105 us)
D/AndroidRuntime( 2214): 
D/AndroidRuntime( 2214): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2214): CheckJNI is OFF
I/ActivityManager(  465): Killing 1874:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
D/AndroidRuntime( 2214): Calling main entry com.android.commands.am.Am
I/ActivityManager(  465): Killing 1897:com.google.android.deskclock/u0a38 (adj 15): empty #18
I/ActivityManager(  465): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  465): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2231 uid=10082 gids={50082, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup(  465): failed to open /acct/uid_10038/pid_1897/cgroup.procs: No such file or directory
W/libprocessgroup(  465): failed to open /acct/uid_10045/pid_1874/cgroup.procs: No such file or directory
D/AndroidRuntime( 2214): Shutting down VM
E/wifi    (  465): android_net_wifi_getLinkLayerStats: failed to get link statistics
E/audio_a2dp_hw(  206): adev_set_parameters: ERROR: set param called even when stream out is null
I/WebViewFactory( 2231): Loading com.google.android.webview version 44.0.2403.90 (code 240309050)
D/SurfaceFlinger(  153): Set power mode=0, type=0 flinger=0x559de4e3c0
D/hwcomposer(  153): hwc_blank: display 0: blank
D/hwcomposer(  153): hwc_blank_display: display 0: [0 -> 1]
I/DisplayManagerService(  465): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1536 x 2048, 59.0 fps, supportedRefreshRates [59.0], density 320, 288.995 x 288.995 dpi, appVsyncOff 0, presDeadline 17949152, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  465): Display changed displayId=0
,I/LibraryLoader( 2231): Time to load native libraries: 16 ms (timestamps 7088-7104)
I/LibraryLoader( 2231): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 2231): Binding Chromium to main looper Looper (main, tid 1) {b0b6d5}
I/LibraryLoader( 2231): Expected native library version number "",actual native library version number ""
,I/chromium( 2231): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2231): Initializing chromium process, singleProcess=true
,W/art     ( 2231): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2231): ApplicationContext is null in ApplicationStatus
,W/chromium( 2231): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2231): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2231): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2231): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,D/BluetoothManagerService(  465): Message: 20
D/BluetoothManagerService(  465): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23b0c7e:true
,D/BluetoothAdapter( 2231): 466807633: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  465): Activity pause timeout for ActivityRecord{3c957bf6 u0 com.test.thalitest/.MainActivity t29}
,D/SurfaceControl(  465): Excessive delay in setPowerMode(): 362ms
,W/art     ( 2231): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2231): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2231): CordovaWebView is running on device made by: htc
,W/art     ( 2231): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2231): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2231): Render dirty regions requested: true
,W/chromium( 2231): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2231): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2231): Enabling debug mode 0
,I/Keyboard.Facilitator(  833): onFinishInput()
,I/ActivityManager(  465): Displayed com.test.thalitest/.MainActivity: +874ms (total +962ms)
W/IInputConnectionWrapper( 2231): showStatusIcon on inactive InputConnection
,W/BindingManager( 2231): Cannot call determinedVisibility() - never saw a connection for the pid: 2231
,D/JsMessageQueue( 2231): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2231): JniHelper::setJavaVM(0xab35b290), pthread_self() = -1417913696
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2231): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2231):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2231):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2231):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2231):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2231): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27646631 added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2231): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2231):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2231):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2231):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2231):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2231):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2231):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2231):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2231):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2231):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2231): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21f96484 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2231): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  465): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2231): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2231): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2231): setDiscoveryMode: Discovery mode BLE is supported
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2231): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2231): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 2231): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 2231): Initializing JXcore engine
,W/jxcore-log( 2231): JXcore engine is ready
,W/Thread-54( 2280): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6009]" dev="sockfs" ino=6009 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-54( 2280): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=449 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-54( 2280): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[11337]" dev="sockfs" ino=11337 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-54( 2280): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17028]" dev="sockfs" ino=17028 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 2231): Starting JXcore engine
,W/jxcore-log( 2231): Platform android
W/jxcore-log( 2231): 
W/jxcore-log( 2231): Process ARCH arm
W/jxcore-log( 2231): 
,I/jxcore-log( 2231): JXcore Cordova bridge is ready!
I/jxcore-log( 2231): 
W/jxcore-log( 2231): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 2231): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 2231): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 2231): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 2231): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,I/ActivityManager(  465): Killing 1946:com.google.android.gm.exchange/u0a70 (adj 15): empty #17
,W/libprocessgroup(  465): failed to open /acct/uid_10070/pid_1946/cgroup.procs: No such file or directory
,W/PluginManager( 2231): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 63ms. Plugin should use CordovaInterface.getThreadPool().
,I/Keyboard.Facilitator.LanguageModelFlusher(  833): run()
I/Keyboard.Facilitator(  833): flushDynamicLanguageModels()
,I/ConfigService( 1029): onCreate
,I/ConfigService( 1029): onDestroy
,V/GLSActivity( 1029): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1029): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1029): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1029): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1029): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1029): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1029): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1029): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1029): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1029): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1029): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1029): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1029): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1670): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1670): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1670): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1670): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1670): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1670): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 1670): Ignoring header User-Agent because its value was null.
,V/GLSActivity( 1029): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1029): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1029): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1029): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1029): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1029): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1029): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1029): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1029): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1029): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1029): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1029): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1029): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1670): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1670): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1670): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1670): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1670): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1670): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 1670): Ignoring header User-Agent because its value was null.
,I/art     (  465): Explicit concurrent mark sweep GC freed 22728(1179KB) AllocSpace objects, 4(100KB) LOS objects, 33% free, 19MB/28MB, paused 2.177ms total 298.539ms
,V/GLSActivity( 1029): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1029): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1029): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1029): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1029): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1029): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1029): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1029): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1029): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1029): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1029): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1029): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1029): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1670): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1670): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1670): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1670): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1670): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1670): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 1670): Ignoring header User-Agent because its value was null.
,I/EventLogService( 1189): Aggregate from 1456919455961 (log), 1456919455961 (data)
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 21418(1296KB) AllocSpace objects, 7(280KB) LOS objects, 40% free, 10MB/17MB, paused 665us total 52.854ms
,I/UsageStatsService(  465): User[0] Flushing usage stats to disk
,V/GLSActivity( 1029): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1029): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1029): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1029): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1029): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1029): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1029): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1029): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1029): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1029): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1029): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1029): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1029): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 1670): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1670): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 1670): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 1670): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 1670): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 1670): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 1670): Ignoring header User-Agent because its value was null.
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 2309): 
D/AndroidRuntime( 2309): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2309): CheckJNI is OFF
D/AndroidRuntime( 2309): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  465): Force stopping com.test.thalitest appid=10082 user=-1: uninstall pkg
I/ActivityManager(  465): Killing 2231:com.test.thalitest/u0a82 (adj 9): stop com.test.thalitest
D/WifiService(  465): Client connection lost with reason: 4
W/PackageSettings(  465): Skipping PackageSetting{fee999e com.example.hello/10095} due to missing metadata
W/ActivityManager(  465): Spurious death for ProcessRecord{3ae7c37f 2231:com.test.thalitest/u0a82}, curProc for 2231: null
I/ActivityManager(  465): Force stopping com.test.thalitest appid=10082 user=0: pkg removed
I/art     (  941): Explicit concurrent mark sweep GC freed 5988(396KB) AllocSpace objects, 4(268KB) LOS objects, 40% free, 14MB/23MB, paused 552us total 56.455ms
I/InputReader(  465): Reconfiguring input devices.  changes=0x00000010
I/art     ( 1009): Explicit concurrent mark sweep GC freed 2708(219KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 12MB/17MB, paused 454us total 101.869ms
I/Keyboard.Facilitator(  833): resetDictionaries() : en_US
W/GeofencerStateMachine(  979): Ignoring removeGeofence because network location is disabled.
I/art     (  465): Explicit concurrent mark sweep GC freed 11495(865KB) AllocSpace objects, 9(220KB) LOS objects, 33% free, 18MB/28MB, paused 1.135ms total 147.362ms
I/art     (  465): WaitForGcToComplete blocked for 119.840ms for cause Explicit
I/Keyboard.Facilitator.DecoderInitializer(  833): run()
D/VoicemailCleanupService(  968): Cleaning up data for package: com.test.thalitest
I/Decoder (  833): createOrResetDecoder
I/ActivityManager(  465): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2324 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=arm64-v8a
I/ConfigService( 1029): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader(  833): run()
W/ContextImpl( 2324): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
D/BackupManagerService(  465): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  465): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  465): removeObsoleteFile: deleting file=29_task.xml
E/NetworkScheduler.SchedulerReceiver( 1029): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1029): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
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
D/ChimeraCfgMgr( 1189): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/PackageBroadcastService( 1189): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraModuleLdr( 1189): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1189): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1189): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1189): Module APK com.google.android.play.games already loaded
I/UpdateIcingCorporaServi( 1009): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/InputMethodManagerService(  465): Got RemoteException sending setActive(false) notification to pid 2231 uid 10082
I/Keyboard.Facilitator(  833): onFinishInput()
I/LocationSettingsChecker( 1189): Removing dialog suppression flag for package com.test.thalitest
W/Launcher(  941): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2a2f54b7 new=com.google.android.velvet.VelvetApplication@2a2f54b7
I/ActivityManager(  465): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/ActivityManager(  465): Resuming delayed broadcast
I/ActivityManager(  465): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=2356 uid=10039 gids={50039, 9997} abi=arm64-v8a
I/ConfigFetchService( 1189): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
D/GOOGLEHELP_CompatibleDatabase( 1189): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1189): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1189): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1189): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/ConfigFetchService( 1189): service connected
I/PeopleContactsSync( 1189): CP2 sync disabled
D/GOOGLEHELP_CompatibleDatabase( 1189): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1189): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1189): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
W/BaseAppContext( 1189): Using Auth Proxy for data requests.
I/Launcher(  941): Deferring update until onResume
D/GOOGLEHELP_CompatibleDatabase( 1189): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1189): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1189): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1189): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1189): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
W/BaseAppContext( 1189): Using Auth Proxy for data requests.
D/GOOGLEHELP_CompatibleDatabase( 1189): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/Icing   ( 1189): doRemovePackageData com.test.thalitest
I/UpdateIcingCorporaServi( 1009): UpdateCorporaTask done [took 378 ms] updated apps [took 377 ms] 
I/ActivityManager(  465): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=2376 uid=10006 gids={50006, 9997, 1028, 1015, 1023} abi=arm64-v8a
W/DriveInitializer( 1189): Awaiting to be initialized
W/DriveInitializer( 1189): Background init thread started
I/art     (  465): Explicit concurrent mark sweep GC freed 10414(495KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/28MB, paused 10.136ms total 926.452ms
I/ActivityManager(  465): Killing 1925:com.google.android.gm/u0a71 (adj 15): empty #17
D/AndroidRuntime( 2309): Shutting down VM
W/libprocessgroup(  465): failed to open /acct/uid_10071/pid_1925/cgroup.procs: No such file or directory
W/DriveInitializer( 1189): Background init thread ended
D/ExternalStorage( 2376): After updating volumes, found 1 active roots
W/ResourcesManager( 2163): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2163): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Documents( 2356): Update found 7 roots in 531ms
E/native  (  833): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  (  833): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  (  833): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  (  833): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  (  833): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  (  833): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
D/Documents( 2356): Update found 7 roots in 194ms

```
