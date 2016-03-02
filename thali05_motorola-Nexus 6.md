#### Test 613623666a5dbc7_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1450): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1450): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1450): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1450): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1450): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1450): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GLSActivity( 1450): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1450): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1450): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1450): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1450): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1450): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1450): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 2669): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2669): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2669): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2669): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2669): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2669): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2669): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2669): Ignoring header User-Agent because its value was null.
D/AndroidRuntime( 3195): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3195): CheckJNI is OFF
D/AndroidRuntime( 3195): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{27120825 token=Token{3ccbd41c ActivityRecord{24d4098f u0 com.test.thalitest/.MainActivity t34}}} to stack=1 task=34 at 0
D/AndroidRuntime( 3195): Shutting down VM
I/HotwordDetector( 1476): Closing mic
I/MicrophoneInputStream( 1476): mic_close com.google.android.apps.gsa.speech.audio.u@187af5ad
I/ActivityManager(  820): Start proc 3211:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
V/ActivityManager(  820): Display changed displayId=0
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1476): Stopping hotword detection.
I/HotwordRecognitionRnr( 1476): Hotword detection finished
I/ActivityManager(  820): Killing 2628:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,I/ActivityManager(  820): Killing 2760:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/WebViewFactory( 3211): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3211): Time to load native libraries: 4 ms (timestamps 9928-9932)
I/LibraryLoader( 3211): Expected native library version number "",actual native library version number ""
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660159251
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,V/WebViewChromiumFactoryProvider( 3211): Binding Chromium to main looper Looper (main, tid 1) {357441aa},
I/LibraryLoader( 3211): Expected native library version number "",actual native library version number ""
I/chromium( 3211): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3211): Initializing chromium process, singleProcess=true
,W/art     ( 3211): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3211): ApplicationContext is null in ApplicationStatus
,W/chromium( 3211): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3211): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3211): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3211): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3211): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26099e20:true
D/BluetoothAdapter( 3211): 24037709: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3211): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3211): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3211): CordovaWebView is running on device made by: motorola
,W/art     ( 3211): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3211): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3211): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3211): Validating map...
,V/WindowManager(  820): Adding window Window{3650cf50 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 7 (after Window{8258045 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
,W/chromium( 3211): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3211): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3211): Enabling debug mode 0
,I/ActivityManager(  820): Displayed com.test.thalitest/.MainActivity: +962ms
,I/Keyboard.Facilitator( 1214): onFinishInput()
,W/IInputConnectionWrapper( 3211): showStatusIcon on inactive InputConnection
,W/BindingManager( 3211): Cannot call determinedVisibility() - never saw a connection for the pid: 3211
,D/JsMessageQueue( 3211): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3211): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576401152
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3211): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3211):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3211):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3211):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3211):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3211): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b18144 added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211):     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da67cf3 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3211): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  820): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3211): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211): setDiscoveryMode: Discovery mode BLE is supported
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3211): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 3211): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3211): Initializing JXcore engine
W/jxcore-log( 3211): JXcore engine is ready
,W/Thread-334( 3265): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12970]" dev="sockfs" ino=12970 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-334( 3265): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-334( 3265): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[13072]" dev="sockfs" ino=13072 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-334( 3265): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[22618]" dev="sockfs" ino=22618 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3211): Starting JXcore engine,
,W/jxcore-log( 3211): Platform android
W/jxcore-log( 3211): 
,W/jxcore-log( 3211): Process ARCH arm
W/jxcore-log( 3211): 
,I/jxcore-log( 3211): JXcore Cordova bridge is ready!
I/jxcore-log( 3211): 
W/jxcore-log( 3211): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 3211): execute: REQUEST_ACCESS_COARSE_LOCATION
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3211): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
V/io.jxcore.node.JXcoreExtension( 3211): isBleMultipleAdvertisementSupported: NOT_RESOLVED
,I/jxcore-log( 3211): BLE multiple advertisement supported
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): My device name is: motorola-Nexus 6
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 3211): 
I/jxcore-log( 3211): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 3211): 
,I/io.jxcore.node.ConnectivityInfo( 3211): updateConnectivityInfo: ,
I/io.jxcore.node.ConnectivityInfo( 3211):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3211):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3211):     - is Wi-Fi enabled: false
I/io.jxcore.node.ConnectivityInfo( 3211):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 3211):     - BSSID name: null
I/io.jxcore.node.ConnectivityInfo( 3211):     - is connected/connecting to active network: false
I/io.jxcore.node.ConnectivityInfo( 3211):     - active network type is Wi-Fi: false
,I/io.jxcore.node.ConnectivityInfo( 3211):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 3211): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,I/jxcore-log( 3211): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 3211): ,
,I/jxcore-log( 3211): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native,
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,I/jxcore-log( 3211): 
,I/jxcore-log( 3211): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
,I/jxcore-log( 3211): 
,I/jxcore-log( 3211): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3211): ,
,I/jxcore-log( 3211): Unit Test app is loaded
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"off","blueTooth":"off","wifi":"off","cellular":"doNotCare"}
I/jxcore-log( 3211): 
,I/chromium( 3211): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1214): run()
I/Keyboard.Facilitator( 1214): flushDynamicLanguageModels()
,I/ConfigService( 1450): onCreate
,I/ConfigService( 1450): onDestroy
,V/GLSActivity( 1450): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1450): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1450): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1450): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1450): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1450): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1450): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1450): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1450): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1450): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1450): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1450): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1450): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2669): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2669): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2669): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2669): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2669): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
,E/PlayEventLogger( 2669): ,	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2669): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2669): Ignoring header User-Agent because its value was null.
,I/art     ( 1450): Explicit concurrent mark sweep GC freed 54053(2MB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.514ms total 46.715ms
,I/art     (  820): Explicit concurrent mark sweep GC freed 34931(1719KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.381ms total 87.383ms
,V/GLSActivity( 1450): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1450): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1450): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1450): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1450): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1450): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1450): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1450): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1450): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1450): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1450): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1450): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1450): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2669): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2669): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2669): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2669): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2669): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2669): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2669): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2669): Ignoring header User-Agent because its value was null.
,I/UsageStatsService(  820): User[0] Flushing usage stats to disk
,V/GLSActivity( 1450): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1450): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1450): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1450): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1450): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1450): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1450): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1450): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
,W/GLSActivity( 1450): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1450): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1450): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1450): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1450): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2669): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2669): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2669): 	,at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2669): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2669): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2669): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2669): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2669): Ignoring header User-Agent because its value was null.
,V/GLSActivity( 1450): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1450): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1450): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1450): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1450): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1450): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1450): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1450): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1450): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1450): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1450): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1450): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1450): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2669): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 2669): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2669): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2669): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2669): ,	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2669): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2669): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2669): Ignoring header User-Agent because its value was null.
,TIME-OUT KILL (timeout was 1200000ms)
```
