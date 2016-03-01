#### Test 61248225a3bd1fe_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
E/Auth    ( 1784): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.android.chrome, Service: oauth2:https://www.googleapis.com/auth/userinfo.email https://www.googleapis.com/auth/userinfo.profile
,W/GLSActivity( 1784): java.io.IOException: NetworkError
W/GLSActivity( 1784): 	at com.google.android.gms.auth.t.a(SourceFile:498)
W/GLSActivity( 1784): 	at com.google.android.gms.auth.s.a(SourceFile:908)
W/GLSActivity( 1784): 	at com.google.android.gms.auth.s.e(SourceFile:528)
W/GLSActivity( 1784): 	at com.google.android.gms.auth.q.f(SourceFile:315)
W/GLSActivity( 1784): 	at com.google.android.gms.auth.q.b(SourceFile:195)
W/GLSActivity( 1784): 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:195)
W/GLSActivity( 1784): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1784): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1784): 	at android.os.Binder.execTransact(Binder.java:446)
W/AccountManagerHelper(  946): Auth token - IO exception
W/AccountManagerHelper(  946): java.io.IOException: NetworkError
W/AccountManagerHelper(  946): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1874)
W/AccountManagerHelper(  946): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/AccountManagerHelper(  946): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
W/AccountManagerHelper(  946): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/AccountManagerHelper(  946): 	at android.os.Binder.execTransact(Binder.java:446)
W/chromium(  946): [WARNING:server_connection_manager.cc(296)] ServerConnectionManager forcing SYNC_AUTH_ERROR
W/chromium(  946): [WARNING:syncer_proto_util.cc(280)] Error posting from syncer: Response Code (bogus on error): -1 Content-Length (bogus on error): -1 Server Status: SYNC_AUTH_ERROR
V/GLSActivity( 1784): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/chromium(  946): [ERROR:get_updates_processor.cc(243)] PostClientToServerMessage() failed during GetUpdates
I/art     (  759): Explicit concurrent mark sweep GC freed 15635(716KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/40MB, paused 807us total 47.188ms
E/Auth    ( 1784): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.android.chrome, Service: oauth2:https://www.googleapis.com/auth/chromesync
W/GLSActivity( 1784): java.io.IOException: NetworkError
W/GLSActivity( 1784): 	at com.google.android.gms.auth.t.a(SourceFile:498)
W/GLSActivity( 1784): 	at com.google.android.gms.auth.s.a(SourceFile:908)
W/GLSActivity( 1784): 	at com.google.android.gms.auth.s.e(SourceFile:528)
W/GLSActivity( 1784): 	at com.google.android.gms.auth.q.f(SourceFile:315)
W/GLSActivity( 1784): 	at com.google.android.gms.auth.q.b(SourceFile:195)
W/GLSActivity( 1784): 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:195)
W/GLSActivity( 1784): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1784): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1784): 	at android.os.Binder.execTransact(Binder.java:446)
W/AccountManagerHelper(  946): Auth token - IO exception
W/AccountManagerHelper(  946): java.io.IOException: NetworkError
W/AccountManagerHelper(  946): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1874)
W/AccountManagerHelper(  946): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/AccountManagerHelper(  946): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
W/AccountManagerHelper(  946): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/AccountManagerHelper(  946): 	at android.os.Binder.execTransact(Binder.java:446)
D/AndroidRuntime( 1938): 
D/AndroidRuntime( 1938): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 1938): CheckJNI is OFF
D/AndroidRuntime( 1938): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 1938): Shutting down VM
I/ActivityManager(  759): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=1973 uid=10278 gids={50278, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/MicrophoneInputStream( 1424): mic_close gfk@1f60fd1e
D/audio_hw_primary(  184): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  184): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1424): Stopping hotword detection.
I/HotwordRecognitionRnr( 1424): Hotword detection finished
I/WebViewFactory( 1973): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 1973): Time to load native libraries: 3 ms (timestamps 8048-8051)
,I/LibraryLoader( 1973): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 1973): Binding Chromium to main looper Looper (main, tid 1) {342755b5}
I/LibraryLoader( 1973): Expected native library version number "",actual native library version number ""
I/chromium( 1973): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 1973): Initializing chromium process, singleProcess=true
,W/art     ( 1973): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 1973): ApplicationContext is null in ApplicationStatus
,W/chromium( 1973): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 1973): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 1973): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 1973): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e878c25:true
,D/BluetoothAdapter( 1973): 419031830: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 1973): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 1973): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 1973): CordovaWebView is running on device made by: LGE
,W/art     ( 1973): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1973): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 1973): Render dirty regions requested: true
,D/Atlas   ( 1973): Validating map...
,W/chromium( 1973): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 1973): Initialized EGL, version 1.4
,D/OpenGLRenderer( 1973): Enabling debug mode 0
,I/ActivityManager(  759): Displayed com.example.hello/.MainActivity: +485ms (total +35s869ms)
,I/Keyboard.Facilitator( 1065): onFinishInput()
,W/BindingManager( 1973): Cannot call determinedVisibility() - never saw a connection for the pid: 1973
,I/chromium( 1973): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 1973): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 1973): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 1973): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,D/JX-Cordova( 1973): jxcore cordova android initializing
,W/jxcore-log( 1973): Initializing JXcore engine
W/jxcore-log( 1973): JXcore engine is ready
,W/jxcore-log( 1973): Starting JXcore engine
,W/m.example.hello( 1973): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7803]" dev="sockfs" ino=7803 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 1973): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/m.example.hello( 1973): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8752]" dev="sockfs" ino=8752 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 1973): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[14586]" dev="sockfs" ino=14586 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 1973): Platform android
W/jxcore-log( 1973): 
,W/jxcore-log( 1973): Process ARCH arm
W/jxcore-log( 1973): 
,I/jxcore-log( 1973): JXcore Cordova bridge is ready!
I/jxcore-log( 1973): 
W/jxcore-log( 1973): JXcore engine is started
,E/jxcore-log( 1973): >> LGE-Nexus 5
E/jxcore-log( 1973): 
,I/jxcore-log( 1973): Total memory 1946181632
I/jxcore-log( 1973): 
,I/jxcore-log( 1973): Free memory 629055488
I/jxcore-log( 1973): 
,I/jxcore-log( 1973): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1973): 
I/jxcore-log( 1973): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1973): 
,I/jxcore-log( 1973): userPath [ 'www', 'www' ]
I/jxcore-log( 1973): 
I/jxcore-log( 1973): Size 1080 1776
I/jxcore-log( 1973): 
,I/jxcore-log( 1973): Screen Brightness 82
I/jxcore-log( 1973): 
E/jxcore-log( 1973): Dummy Error Log.
E/jxcore-log( 1973): 
,I/jxcore-log( 1973): getBuffer is called!!!!
I/jxcore-log( 1973): 
,I/GCoreNlp( 1784): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/GCoreUlr( 1784): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.location.PROVIDERS_CHANGED}]
,I/GCoreUlr( 1784): DispatchingService.onCreate()
,D/BluetoothAdapter( 1093): 874993077: getState() :  mService = null. Returning STATE_OFF
,I/GCoreUlr( 1784): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.location.PROVIDERS_CHANGED
,I/GCoreUlr( 1784): WorldUpdater:android.location.PROVIDERS_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1784): Unbound from all location providers
I/GCoreUlr( 1784): Place inference reporting - stopped
,I/GAv4-SVC( 1784): Google Analytics 8.4.89 is starting up.
,D/WifiService(  759): New client listening to asynchronous messages
,D/BluetoothAdapter( 1093): 874993077: getState() :  mService = null. Returning STATE_OFF
,E/WifiStateMachine(  759): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.68 rxSuccessRate=3.08 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-50
E/WifiStateMachine(  759): WifiStateMachine starting scan for "NG700"WPA_PSK with 2437
,I/wpa_supplicant(  983): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager(  759): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.audio.MediaButtonIntentReceiver: pid=2077 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/BluetoothAdapter( 1784): 599727339: getState() :  mService = null. Returning STATE_OFF
I/BleScanCompatLib( 1784): Building BLE scanner compat:  'L/M' hardware access layer is not available: BluetoothAdapter.getBluetoothLeScanner() is null.
,I/BleScanCompatLib( 1784): BLE 'JB+' software access layer enabled
,I/art     ( 1784): Explicit concurrent mark sweep GC freed 30745(2MB) AllocSpace objects, 19(304KB) LOS objects, 40% free, 20MB/33MB, paused 541us total 46.586ms
,W/GeofencerStateMachine( 1784): Ignoring removeGeofence because network location is disabled.
,I/GCoreUlr( 1784): DispatchingService.onDestroy()
I/GCoreUlr( 1784): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1784): Unbound from all location providers
I/GCoreUlr( 1784): Place inference reporting - stopped
,I/Places  ( 1784): b.c:195: PlacesBleScanner stop()
,I/BleScanCompatLib( 1784): Scan : No clients left, canceling alarm.
,I/GAv4    ( 2077): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2077):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2077):   adb logcat -s GAv4
,W/GAv4    ( 2077): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2077): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2077): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 2077): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 2077): Time to load native libraries: 1 ms (timestamps 1704-1705)
I/LibraryLoader( 2077): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 2077): Binding Chromium to main looper Looper (main, tid 1) {1b967c5f}
,I/LibraryLoader( 2077): Expected native library version number "",actual native library version number ""
,I/chromium( 2077): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2077): Initializing chromium process, singleProcess=true
,W/art     ( 2077): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2077): ApplicationContext is null in ApplicationStatus
,W/chromium( 2077): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2077): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2077): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2077): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 2077): Requires BLUETOOTH permission
,I/NSApplication( 2077): Starting up...
,E/WifiStateMachine(  759): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.68 rxSuccessRate=3.08 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-50
E/WifiStateMachine(  759): WifiStateMachine starting scan for "NG700"WPA_PSK with 2437
,I/wpa_supplicant(  983): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager(  759): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=2141 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/MusicStore( 2141): Database version: 120
,W/ResourcesManager( 2141): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2141): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2141): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 2141): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 2141): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@11fc3d6b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 2141): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 2141): GMSCore installation verified
,I/ConfigStore( 2141): Config Database version: 1
,I/MediaRouter( 2141): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 2141): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2141): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 2141): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1701): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1701): onCreate
,I/GHttpClientFactory( 2141): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2141): Using platform SSLCertificateSocketFactory
,D/SystemUpdateService( 1701): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1701): active receiver: enabled
,I/SystemUpdateService( 1701): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1701): retry (wakeup: false) in 3599975 ms
,W/ResourcesManager(  901): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  901): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/art     ( 1701): No such thread id for suspend: 26
,I/iu.SyncManager( 1701): SYNC; picasa accounts
,D/NetworkLogImpl( 1701): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1701): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/SystemUpdateService( 1701): onDestroy
,I/iu.UploadsManager( 1701): num queued entries: 0
I/iu.UploadsManager( 1701): num updated entries: 0
I/iu.SyncManager( 1701): NEXT; no task
,I/art     (  759): Explicit concurrent mark sweep GC freed 17337(899KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/40MB, paused 735us total 57.680ms
,D/GCM     ( 1784): COMPAT: Multi user ser=0 current=0
,I/ActivityManager(  759): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=2183 uid=10054 gids={50054, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     ( 1537): Explicit concurrent mark sweep GC freed 1433(50KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/26MB, paused 607us total 24.346ms
,W/ResourcesManager( 2183): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 2183): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 2183): MmsConfig.loadMmsSettings
I/Babel_SMS( 2183): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
I/Babel_SMS( 2183): MmsConfig.loadFromDatabase
,E/Babel_SMS( 2183): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 2183): MmsConfig.loadFromResources
E/Babel_SMS( 2183): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 2183): MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/Babel_SMS( 2183): ApnsOta: OTA version -1
,I/Babel   ( 2183): deleted: false for 0
,W/Settings( 2183): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 2183): startup - clean
,I/ActivityManager(  759): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=2221 uid=10067 gids={50067, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 2221): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/VideoCapabilities( 2183): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 2183): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 2183): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2183): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2183): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2183): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 2183): onServiceConnected
,W/Babel   ( 2183): Attempted to change video mute state without an active call.
,V/UserPresentBroadcastReceiver( 1784): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,I/ActivityManager(  759): Start proc com.google.android.apps.fitness for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider: pid=2265 uid=10045 gids={50045, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/art     (  195): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 173us total 9.445ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 8.190ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 165us total 8.001ms
,I/FitnessApp( 2265): Initializers took 3 milliseconds
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  759): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  759): Message: 2
,D/WifiService(  759): New client listening to asynchronous messages
,D/WifiService(  759): setWifiEnabled: false pid=1973, uid=10278
,E/WifiService(  759): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 1973): ****TEST TOOK:  5075  ms ****
I/jxcore-log( 1973): 
I/jxcore-log( 1973): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 1973): 
E/WifiStateMachine(  759): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/CommandListener(  180): Clearing all IP addresses on wlan0
I/art     ( 1537): Explicit concurrent mark sweep GC freed 2702(104KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 771us total 24.297ms
,D/WearableService( 1784): callingUid 10008, callindPid: 1784
,E/GmsWearableNodeHelper( 1784): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,E/MDM     ( 1784): [194] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  759): scanCount==0 - aborting
,D/WifiScanningService(  759): SCAN_AVAILABLE : 1
,D/WifiScanningService(  759): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  759): DefaultState
,D/RttService(  759): SCAN_AVAILABLE : 1
,D/RttService(  759): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNetworkAgent(  759): NetworkAgent: NetworkAgent channel lost
,D/LocationInitializer( 1701): Restart initialization of location
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  759): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
W/Babel_NetworkConnectionCheckingService( 2183): IO exceptions, probably not a captive portal 
,I/Babel   ( 2183): connection state changed from UNKNOWN to CONNECTED
D/Nat464Xlat(  759): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  759): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  759): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  759): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/art     ( 1784): Explicit concurrent mark sweep GC freed 10701(626KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 20MB/34MB, paused 812us total 65.590ms
,W/IcingInternalCorpora( 1701): getNumBytesRead when not calculated.
,D/AndroidRuntime( 2290): 
D/AndroidRuntime( 2290): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 2290): CheckJNI is OFF
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant(  983): wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,D/AuthorizationBluetoothService( 1784): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/a       ( 1784): Opening database auth.proximity.permit_store...
,D/AndroidRuntime( 2290): Calling main entry com.android.commands.pm.Pm
,V/GLSActivity( 1784): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  759): Force stopping com.example.hello appid=10278 user=-1: uninstall pkg
I/ActivityManager(  759): Killing 1973:com.example.hello/u0a278 (adj 0): stop com.example.hello
,I/WindowState(  759): WIN DEATH: Window{266cc895 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  759): Client connection lost with reason: 4
,W/PackageSettings(  759): Skipping PackageSetting{1122e3e com.test.thalitest/10270} due to missing metadata
,D/Tethering(  759): InitialState.processMessage what=4
,I/wpa_supplicant(  983): wlan0: CTRL-EVENT-TERMINATING 
,W/ActivityManager(  759): Force removing ActivityRecord{b7bb03e u0 com.example.hello/.MainActivity t218}: app died, no saved state
,W/ActivityManager(  759): Spurious death for ProcessRecord{2b91bed9 1973:com.example.hello/u0a278}, curProc for 1973: null
,I/ActivityManager(  759): Force stopping com.example.hello appid=10278 user=0: pkg removed
,D/Tethering(  759): sendTetherStateChangedBroadcast 0, 0, 0
,I/Keyboard.Facilitator( 1065): resetDictionaries() : en_US
,W/Settings( 2183): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/InputReader(  759): Reconfiguring input devices.  changes=0x00000010
,W/Settings( 1784): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Keyboard.Facilitator.DecoderInitializer( 1065): run()
,I/Decoder ( 1065): createOrResetDecoder
,W/GeofencerStateMachine( 1784): Ignoring removeGeofence because network location is disabled.
,W/GCoreFlp( 1784): No location to return for getLastLocation()
,W/FusedLocationProvider( 1784): location=null
,D/BackupManagerService(  759): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  759): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  759): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2357 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,D/TaskPersister(  759): removeObsoleteFile: deleting file=218_task.xml
,W/InputMethodManagerService(  759): Got RemoteException sending setActive(false) notification to pid 1973 uid 10278
,I/Keyboard.Facilitator( 1065): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1065): run()
,I/art     (  759): Explicit concurrent mark sweep GC freed 26568(1524KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/40MB, paused 1.734ms total 165.620ms
,I/HotwordRecognitionRnr( 1424): Starting hotword detection.
,W/ResourcesManager( 1272): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/MicrophoneInputStream( 1424): mic_starting gfk@23bf1ceb
,I/AudioFlinger(  184): AudioFlinger's thread 0xb48b7000 ready to run
,I/MicrophoneInputStream( 1424): mic_started gfk@23bf1ceb
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1065): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,W/ResourcesManager( 1272): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Loading LM = contacts
,D/audio_hw_primary(  184): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  184): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
D/        (  184): Failed to fetch the lookup information of the device 0000003E 
E/ACDB-LOADER(  184): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  184): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  184): enable_audio_route: apply and update mixer path: audio-record
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Loading LM = history
D/AndroidRuntime( 2290): Shutting down VM
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1065): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1065): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1065): run()
I/StatsUtilsManager( 1065): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1065): shouldRecordStats() = Too Soon
,I/UpdateIcingCorporaServi( 1424): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/ChimeraCfgMgr( 1701): Reading stored module config
,D/ChimeraCfgMgr( 1701): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1701): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 1701): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,I/HotwordWorker( 1424): onReady
,D/ChimeraCfgMgr( 1701): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1701): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1701): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1701): Submit a task: k
,D/ChimeraCfgMgr( 1701): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1701): Loading module com.google.android.gms.vision from APK com.google.android.gms
E/Vision  ( 1701): Failed to find package com.example.hello
D/k       ( 1701): Processing package: com.example.hello
,W/k       ( 1701): Failed to find package com.example.hello
,E/Icing   ( 1701): Package com.example.hello not found
,I/ActivityManager(  759): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2400 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,W/BaseAppContext( 1701): Using Auth Proxy for data requests.
,W/OpenGLRenderer( 1272): Incorrectly called buildLayer on View: adg, destroying layer...
W/OpenGLRenderer( 1272): Incorrectly called buildLayer on View: adg, destroying layer...
,E/BaseAppContext( 1701): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 1701): Using Auth Proxy for data requests.
,W/BaseAppContext( 1701): Using Auth Proxy for data requests.
,W/BaseAppContext( 1701): Using Auth Proxy for data requests.
,W/BaseAppContext( 1701): Using Auth Proxy for data requests.
W/BaseAppContext( 1701): Using Auth Proxy for data requests.
,W/BaseAppContext( 1701): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 1701): cleanUpNonGplusAccounts done.
,W/FileUtils( 1701): Failed to chmod(/data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/SharedPreferencesImpl( 1701): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml.bak
,E/SQLiteDatabase( 1424): Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db'.
E/SQLiteDatabase( 1424): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1424): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1424): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1424): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1424): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1424): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1424): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1424): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1424): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1424): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1424): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1424): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1424): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1424): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1424): 	at cun.getWritableDatabase(PG:568)
E/SQLiteDatabase( 1424): 	at bea.a(PG:378)
E/SQLiteDatabase( 1424): 	at beg.i(PG:325)
E/SQLiteDatabase( 1424): 	at bef.call(PG:156)
E/SQLiteDatabase( 1424): 	at beg.a(PG:299)
E/SQLiteDatabase( 1424): 	at bed.a(PG:171)
E/SQLiteDatabase( 1424): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.b(PG:415)
E/SQLiteDatabase( 1424): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.k(PG:369)
E/SQLiteDatabase( 1424): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:286)
E/SQLiteDatabase( 1424): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/SQLiteDatabase( 1424): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/SQLiteDatabase( 1424): 	at cuw.Tg(PG:368)
E/SQLiteDatabase( 1424): 	at cuy.ub(PG:301)
E/SQLiteDatabase( 1424): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/SQLiteDatabase( 1424): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/SQLiteDatabase( 1424): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1424): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1424): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1424): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/IcingCorporaProvider( 1424): Exception thrown from registerCorpora
E/IcingCorporaProvider( 1424): java.lang.RuntimeException: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/IcingCorporaProvider( 1424): 	at beg.a(PG:301)
E/IcingCorporaProvider( 1424): 	at bed.a(PG:171)
E/IcingCorporaProvider( 1424): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.b(PG:415)
E/IcingCorporaProvider( 1424): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.k(PG:369)
E/IcingCorporaProvider( 1424): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:286)
E/IcingCorporaProvider( 1424): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/IcingCorporaProvider( 1424): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/IcingCorporaProvider( 1424): 	at cuw.Tg(PG:368)
E/IcingCorporaProvider( 1424): 	at cuy.ub(PG:301)
E/IcingCorporaProvider( 1424): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/IcingCorporaProvider( 1424): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/IcingCorporaProvider( 1424): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 1424): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 1424): 	at android.os.Looper.loop(Looper.java:135)
E/IcingCorporaProvider( 1424): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 1424): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/IcingCorporaProvider( 1424): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/IcingCorporaProvider( 1424): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/IcingCorporaProvider( 1424): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/IcingCorporaProvider( 1424): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/IcingCorporaProvider( 1424): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/IcingCorporaProvider( 1424): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/IcingCorporaProvider( 1424): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/IcingCorporaProvider( 1424): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/IcingCorporaProvider( 1424): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/IcingCorporaProvider( 1424): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/IcingCorporaProvider( 1424): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/IcingCorporaProvider( 1424): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/IcingCorporaProvider( 1424): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/IcingCorporaProvider( 1424): 	at cun.getWritableDatabase(PG:568)
E/IcingCorporaProvider( 1424): 	at bea.a(PG:378)
E/IcingCorporaProvider( 1424): 	at beg.i(PG:325)
E/IcingCorporaProvider( 1424): 	at bef.call(PG:156)
E/IcingCorporaProvider( 1424): 	at beg.a(PG:299)
E/IcingCorporaProvider( 1424): 	... 14 more
W/IcingCorporaProvider( 1424): Corpora registration failed
,E/SQLiteDatabase( 1424): Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db'.
E/SQLiteDatabase( 1424): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1424): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1424): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1424): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1424): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1424): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1424): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1424): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1424): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1424): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1424): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1424): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1424): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1424): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1424): 	at cun.getWritableDatabase(PG:568)
E/SQLiteDatabase( 1424): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:294)
E/SQLiteDatabase( 1424): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/SQLiteDatabase( 1424): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/SQLiteDatabase( 1424): 	at cuw.Tg(PG:368)
E/SQLiteDatabase( 1424): 	at cuy.ub(PG:301)
E/SQLiteDatabase( 1424): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/SQLiteDatabase( 1424): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/SQLiteDatabase( 1424): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1424): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1424): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1424): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,--------- beginning of crash
E/AndroidRuntime( 1424): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 1424): Process: com.google.android.googlequicksearchbox:search, PID: 1424
E/AndroidRuntime( 1424): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 1424): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 1424): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 1424): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 1424): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 1424): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 1424): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 1424): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 1424): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 1424): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 1424): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/AndroidRuntime( 1424): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 1424): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 1424): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 1424): 	at cun.getWritableDatabase(PG:568)
E/AndroidRuntime( 1424): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:294)
E/AndroidRuntime( 1424): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/AndroidRuntime( 1424): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 1424): 	at cuw.Tg(PG:368)
E/AndroidRuntime( 1424): 	at cuy.ub(PG:301)
E/AndroidRuntime( 1424): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/AndroidRuntime( 1424): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/AndroidRuntime( 1424): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1424): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1424): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1424): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  759): Can't write: system_app_crash
E/DropBoxManagerService(  759): java.io.FileNotFoundException: /data/system/dropbox/drop90.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  759): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  759): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  759): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  759): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  759): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  759): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  759): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  759): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  759): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  759): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  759): 	... 5 more
,D/OpenGLRenderer(  759): Render dirty regions requested: true
,D/Atlas   (  759): Validating map...
,E/qdoverlay(  170): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  170): MdpData failed to play
E/qdoverlay(  170): == Dump MdpData start ==
,E/qdoverlay(  170): == Dump OvFD fd=36 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  170): mOvData msmfb_overlay_data id=64
E/qdoverlay(  170): data msmfb_data offset=0 memid=48 id=0 flags=0x0 priv=0
E/qdoverlay(  170): == Dump MdpData end ==
E/qdhwcomposer(  170): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  170): hwc_set_primary: MDPComp draw failed
E/qdhwcomposer(  170): display_commit: MSMFB_DISPLAY_COMMIT for primary failed
E/qdhwcomposer(  170): hwc_set_primary: display commit fail!
,I/Adreno-EGL(  759): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  759): Initialized EGL, version 1.4
,D/OpenGLRenderer(  759): Enabling debug mode 0
,E/qdoverlay(  170): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  170): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  170): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  170): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  170): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  170): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  170): == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  170): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  170): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  170): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  170): Ctrl commit failed set overlay
E/qdhwcomposer(  170): configureLowRes: commit failed for low res panel
E/qdoverlay(  170): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  170): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  170): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  170): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  170): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  170): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  170): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  170): src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
E/qdoverlay(  170): src_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  170): dst_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  170): Ctrl commit failed set overlay
E/qdhwcomposer(  170): configure: commit fails
E/qdoverlay(  170): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  170): MdpCtrl close error in unset

```
