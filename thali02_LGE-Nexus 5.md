#### Test 61703351436c7c0_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
W/Auth    ( 1436): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
I/CheckinService( 1618): Checkin interval check for package: unspecified last checkin: 1457078428929 min interval config: 0 actual interval: 454839587
V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GCM     ( 1618): COMPAT: Multi user ser=0 current=0
I/CheckinService( 1618): Disabling old GoogleServicesFramework version
D/SystemUpdateService( 1618): onCreate
I/GCoreUlr( 1618): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
D/SystemUpdateService( 1618): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
V/AuthZen ( 1618): Handling intent: android.intent.action.BOOT_COMPLETED
D/AuthZenEventHandler( 1618): Handling event: android.intent.action.BOOT_COMPLETED
I/SystemUpdateService( 1618): active receiver: enabled
W/BaseAppContext( 1618): Using Auth Proxy for data requests.
I/CheckinService( 1618): Checking schedule, now: 1457533268586 next: 1457120595901
I/CheckinService( 1618): active receiver: enabled
I/AuthZen ( 1618): Fetching signing key...
,W/chromium(  948): [WARNING:server_connection_manager.cc(296)] ServerConnectionManager forcing SYNC_AUTH_ERROR
W/chromium(  948): [WARNING:syncer_proto_util.cc(280)] Error posting from syncer: Response Code (bogus on error): -1 Content-Length (bogus on error): -1 Server Status: SYNC_AUTH_ERROR
E/chromium(  948): [ERROR:get_updates_processor.cc(243)] PostClientToServerMessage() failed during GetUpdates
I/AuthZen ( 1618): Signing key fetched successfully!
W/BaseAppContext( 1618): Using Auth Proxy for data requests.
I/art     ( 1618): Explicit concurrent mark sweep GC freed 44199(3MB) AllocSpace objects, 27(432KB) LOS objects, 40% free, 21MB/36MB, paused 3.828ms total 55.526ms
D/a       ( 1618): Opening database auth.proximity.permit_store...
D/AuthZenTransactionCache( 1618): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1618): Clearing transaction cache
I/SystemUpdateService( 1618): showing system update notification
I/art     ( 1529): Explicit concurrent mark sweep GC freed 2687(106KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/26MB, paused 826us total 12.113ms
--------- beginning of system
I/ValidateNoPeople(  756): skipping global notification
W/ResourcesManager(  897): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  897): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/SystemUpdateService( 1618): retry (wakeup: false) in 3599848 ms
D/GCM     ( 1436): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
I/GCoreUlr( 1436): DispatchingService.onCreate()
D/AndroidRuntime( 2450): 
D/AndroidRuntime( 2450): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2450): CheckJNI is OFF
D/PersistentNotificationBroadcastReceiver( 1436): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1436): No location to return for getLastLocation()
W/FusedLocationProvider( 1436): location=null
W/GCoreFlp( 1436): No location to return for getLastLocation()
W/FusedLocationProvider( 1436): location=null
I/GCoreUlr( 1436): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
E/Auth    ( 1436): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.android.chrome, Service: oauth2:https://www.googleapis.com/auth/chromesync
W/GLSActivity( 1436): java.io.IOException: NetworkError
W/GLSActivity( 1436): 	at com.google.android.gms.auth.t.a(SourceFile:498)
W/GLSActivity( 1436): 	at com.google.android.gms.auth.s.a(SourceFile:908)
W/GLSActivity( 1436): 	at com.google.android.gms.auth.s.e(SourceFile:528)
W/GLSActivity( 1436): 	at com.google.android.gms.auth.q.f(SourceFile:315)
W/GLSActivity( 1436): 	at com.google.android.gms.auth.q.b(SourceFile:195)
W/GLSActivity( 1436): 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:195)
W/GLSActivity( 1436): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1436): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1436): 	at android.os.Binder.execTransact(Binder.java:446)
W/AccountManagerHelper(  948): Auth token - IO exception
W/AccountManagerHelper(  948): java.io.IOException: NetworkError
W/AccountManagerHelper(  948): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1874)
W/AccountManagerHelper(  948): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/AccountManagerHelper(  948): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
W/AccountManagerHelper(  948): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/AccountManagerHelper(  948): 	at android.os.Binder.execTransact(Binder.java:446)
D/SystemUpdateService( 1618): onDestroy
I/ActivityManager(  756): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2473 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2450): Calling main entry com.android.commands.am.Am
I/art     (  194): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 186us total 9.559ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 169us total 7.261ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.288ms
I/ActivityManager(  756): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 2450): Shutting down VM
I/GCoreUlr( 1436): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/ActivityManager(  756): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2492 uid=10278 gids={50278, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/MicrophoneInputStream( 1454): mic_close gfk@dba07f
I/GCoreUlr( 1436): Unbound from all location providers
I/GCoreUlr( 1436): Place inference reporting - stopped
I/GCoreUlr( 1436): DispatchingService.onDestroy()
I/GCoreUlr( 1436): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1436): Unbound from all location providers
I/GCoreUlr( 1436): Place inference reporting - stopped
D/audio_hw_primary(  183): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  183): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1454): Hotword detection finished
I/HotwordRecognitionRnr( 1454): Stopping hotword detection.
I/WebViewFactory( 2492): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2492): Time to load native libraries: 4 ms (timestamps 5203-5207)
I/LibraryLoader( 2492): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2492): Binding Chromium to main looper Looper (main, tid 1) {39bb80d2}
I/LibraryLoader( 2492): Expected native library version number "",actual native library version number ""
I/chromium( 2492): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2492): Initializing chromium process, singleProcess=true
W/art     ( 2492): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2492): ApplicationContext is null in ApplicationStatus
W/ResourcesManager( 2473): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2473): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/chromium( 2492): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 2492): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2492): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2492): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2492): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
V/JNIHelp ( 2473): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/BluetoothManagerService(  756): Message: 20
D/BluetoothManagerService(  756): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2cc0fc6f:true
D/BluetoothAdapter( 2492): 833411102: getState() :  mService = null. Returning STATE_OFF
W/System  ( 2473): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2473): Installed default security provider GmsCore_OpenSSL
W/art     ( 2492): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 2492): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 2492): CordovaWebView is running on device made by: LGE
W/art     ( 2492): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2492): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 2492): Render dirty regions requested: true
D/Atlas   ( 2492): Validating map...
W/chromium( 2492): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 2492): Initialized EGL, version 1.4
D/OpenGLRenderer( 2492): Enabling debug mode 0
I/ActivityManager(  756): Displayed com.example.hello/.MainActivity: +488ms (total +13s845ms)
W/BindingManager( 2492): Cannot call determinedVisibility() - never saw a connection for the pid: 2492
I/chromium( 2492): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 2492): Set native->JS mode to OnlineEventsBridgeMode
E/YouTube MDX( 2473): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
E/AndroidProtocolHandler( 2492): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/dex2oat ( 2562): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads2010227009.jar --oat-fd=27 --oat-location=/data/data/com.google.android.youtube/cache/ads2010227009.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 2562): dex2oat took 55.400ms (threads: 4)
,D/jxcore_app_log( 2492): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,W/jxcore-log( 2492): Initializing JXcore engine
W/jxcore-log( 2492): JXcore engine is ready
,W/Thread-246( 2577): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8023]" dev="sockfs" ino=8023 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-246( 2577): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-246( 2577): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8467]" dev="sockfs" ino=8467 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-246( 2577): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[16172]" dev="sockfs" ino=16172 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2492): Starting JXcore engine
,W/InstanceID/Rpc( 2473): Found 10008
,W/jxcore-log( 2492): Platform android
W/jxcore-log( 2492): 
W/jxcore-log( 2492): Process ARCH arm
W/jxcore-log( 2492): 
,I/jxcore-log( 2492): JXcore Cordova bridge is ready!
I/jxcore-log( 2492): 
,W/jxcore-log( 2492): JXcore engine is started
,E/jxcore-log( 2492): >> LGE-Nexus 5
E/jxcore-log( 2492): 
,I/jxcore-log( 2492): Total memory 1946181632
I/jxcore-log( 2492): 
I/jxcore-log( 2492): Free memory 375627776
I/jxcore-log( 2492): 
I/jxcore-log( 2492): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2492): 
I/jxcore-log( 2492): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2492): 
,I/jxcore-log( 2492): userPath [ 'www', 'www' ]
I/jxcore-log( 2492): 
,I/jxcore-log( 2492): Size 1080 1776
I/jxcore-log( 2492): 
,I/jxcore-log( 2492): Screen Brightness 82
I/jxcore-log( 2492): 
,E/jxcore-log( 2492): Dummy Error Log.
E/jxcore-log( 2492): 
,I/ActivityManager(  756): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=2611 uid=10054 gids={50054, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  756): Killing 1879:com.android.musicfx/u0a15 (adj 15): empty #17
,W/ResourcesManager( 2611): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/libprocessgroup(  756): failed to open /acct/uid_10015/pid_1879/cgroup.procs: No such file or directory
,I/Babel_SMS( 2611): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 2611): MmsConfig.loadMmsSettings
,I/Babel_SMS( 2611): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/Babel_SMS( 2611): MmsConfig.loadFromDatabase
,E/Babel_SMS( 2611): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 2611): MmsConfig.loadFromResources
E/Babel_SMS( 2611): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 2611): MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/Babel_SMS( 2611): ApnsOta: OTA version -1
,I/Babel   ( 2611): deleted: false for 0
,W/Settings( 2611): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 2611): startup - clean
,I/jxcore-log( 2492): getBuffer is called!!!!
I/jxcore-log( 2492): 
,V/Babel   ( 2611): babel boot account: thalitester@gmail.com
,W/VideoCapabilities( 2611): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 2611): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 2611): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2611): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2611): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2611): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 2611): onServiceConnected
,W/Babel   ( 2611): Attempted to change video mute state without an active call.
,I/ActivityManager(  756): Start proc com.google.android.apps.fitness for broadcast com.google.android.apps.fitness/.FitnessBootReceiver: pid=2646 uid=10045 gids={50045, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/SQLiteLog( 2611): (284) automatic index on conversation_participants_view(conversation_id)
,W/VideoCapabilities( 2611): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2611): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2611): Unrecognized profile 2130706433 for video/avc
,E/SQLiteLog( 2611): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 2611): (284) automatic index on conversation_participants_view(conversation_id)
,I/ActivityManager(  756): Killing 1912:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,I/FitnessApp( 2646): Initializers took 0 milliseconds
,I/ActivityManager(  756): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2665 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
I/ActivityManager(  756): Killing 2010:com.google.android.apps.plus/u0a67 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10040/pid_1912/cgroup.procs: No such file or directory,
W/libprocessgroup(  756): failed to open /acct/uid_10067/pid_2010/cgroup.procs: No such file or directory
,I/ActivityManager(  756): Killing 2086:com.android.keychain/1000 (adj 15): empty #17
,I/art     (  756): Explicit concurrent mark sweep GC freed 14464(711KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/41MB, paused 908us total 52.392ms
,W/libprocessgroup(  756): failed to open /acct/uid_1000/pid_2086/cgroup.procs: No such file or directory
,I/GAv4    ( 2665): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2665):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2665):   adb logcat -s GAv4
,W/GAv4    ( 2665): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2665): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2665): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  756): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2691 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  756): Killing 2070:com.google.android.dialer/u0a10 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10010/pid_2070/cgroup.procs: No such file or directory
,I/Gmail   ( 2691): getAccountsCursor
,D/ActivityThread( 2691): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  756): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=2714 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GAV2    ( 2691): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Gmail   ( 2691): getAccountsCursor
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  756): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 2691): Observing account changes for notifications
,I/SystemBroadcastReceiver( 1085): Boot has been completed
D/Volley  ( 1951): [168] DiskBasedCache.clear: Cache cleared.
I/SystemBroadcastReceiver( 1085): toggleAppIcon() : FLAG_SYSTEM = true
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Volley  ( 1951): [161] DiskBasedCache.clear: Cache cleared.
,I/Exchange( 2714): EasService.onCreate
,V/UserPresentBroadcastReceiver( 1436): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,I/Exchange( 2714): RestartPingTask
,I/ActivityManager(  756): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=2758 uid=10003 gids={50003, 9997} abi=armeabi-v7a
,E/ActivityThread( 2691): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@1491338a that was originally bound here
E/ActivityThread( 2691): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@1491338a that was originally bound here
E/ActivityThread( 2691): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2691): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2691): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2691): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2691): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2691): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 2691): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 2691): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 2691): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 2691): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 2691): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 2691): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 2691): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 2691): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2691): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2691): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/a       ( 2691): RuntimeException when trying to unbind from service
E/a       ( 2691): java.lang.IllegalArgumentException: Service not registered: com.android.emailcommon.service.am@1491338a
E/a       ( 2691): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1024)
E/a       ( 2691): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1802)
E/a       ( 2691): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/a       ( 2691): 	at com.android.emailcommon.service.an.a(SourceFile:124)
E/a       ( 2691): 	at com.android.emailcommon.service.an.doInBackground(SourceFile:111)
E/a       ( 2691): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/a       ( 2691): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/a       ( 2691): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/a       ( 2691): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/a       ( 2691): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/a       ( 2691): 	at java.lang.Thread.run(Thread.java:818)
,I/Exchange( 2714): RestartPingsTask did not start any pings.
I/Exchange( 2714): PSS stopIfIdle
I/Exchange( 2714): PSS has no active accounts; stopping service.
,I/Exchange( 2714): onDestroy
,I/ActivityManager(  756): Killing 1319:android.process.acore/u0a4 (adj 15): empty #17
,E/SQLiteLog( 2691): (283) recovered 67 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,W/libprocessgroup(  756): failed to open /acct/uid_10004/pid_1319/cgroup.procs: No such file or directory
,D/CellBroadcastReceiver( 2758): onReceive Intent { act=android.intent.action.SERVICE_STATE flg=0x10 cmp=com.android.cellbroadcastreceiver/.CellBroadcastReceiver (has extras) }
D/CellBroadcastReceiver( 2758): Intent ACTION_SERVICE_STATE_CHANGED
,D/CellBroadcastReceiver( 2758): Service state changed! 3 Full: 3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=false Current state=-1
,I/ActivityManager(  756): Killing 2199:com.google.android.onetimeinitializer/u0a12 (adj 15): empty #17
,I/Gmail   ( 2691): notifyAccountChanged
,I/Gmail   ( 2691): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 2691): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/libprocessgroup(  756): failed to open /acct/uid_10012/pid_2199/cgroup.procs: No such file or directory
,I/Gmail   ( 2691): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 2691): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  756): Killing 2226:com.android.managedprovisioning/u0a14 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10014/pid_2226/cgroup.procs: No such file or directory
,D/SIP     ( 1222): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,E/MDM     ( 1436): [189] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1436): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1618): Restart initialization of location
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  756): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2800 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1436): No location to return for getLastLocation()
,W/FusedLocationProvider( 1436): location=null
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 2691): getAccountsCursor
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 2691): getAccountsCursor
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/CAR.SERVICE( 2176): mConnectedToCar = false, abort
,E/ActivityThread( 2176): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@34378beb that was originally bound here
E/ActivityThread( 2176): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@34378beb that was originally bound here
E/ActivityThread( 2176): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2176): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2176): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2176): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2176): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2176): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2176): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2176): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 2176): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 2176): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 2176): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 2176): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 2176): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 2176): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 2176): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 2176): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 2176): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2176): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2176): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 2176): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2176): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2176): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 2176): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 2176): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@6c74f92 that was originally bound here
E/ActivityThread( 2176): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@6c74f92 that was originally bound here
E/ActivityThread( 2176): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2176): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2176): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2176): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2176): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2176): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 2176): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 2176): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 2176): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 2176): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 2176): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 2176): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 2176): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 2176): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 2176): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 2176): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2176): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2176): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 2176): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2176): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2176): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 2176): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  756): Unbind failed: could not find connection for android.os.BinderProxy@3502300
,I/GAv4-SVC( 1618): Google Analytics 8.4.89 is starting up.
,I/GAV2    ( 1454): Thread[GAThread,5,main]: No campaign data found.
,W/ContextImpl( 2261): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 2261): Thread[GAThread,5,main]: No campaign data found.
,I/MusicStore( 2800): Database version: 120
,W/ResourcesManager( 2800): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2800): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2800): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 2800): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 2800): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d9f0e90: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2800): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 2800): GMSCore installation verified
,I/ConfigStore( 2800): Config Database version: 1
,I/MediaRouter( 2800): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/GHttpClientFactory( 2800): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2800): Using platform SSLCertificateSocketFactory
,D/Finsky  ( 1951): [187] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 1951): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1436): Explicit concurrent mark sweep GC freed 17419(1138KB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 21MB/35MB, paused 760us total 30.479ms
,I/art     (  756): Explicit concurrent mark sweep GC freed 9958(530KB) AllocSpace objects, 3(52KB) LOS objects, 33% free, 27MB/41MB, paused 1.170ms total 57.531ms
,W/GCoreFlp( 1436): No location to return for getLastLocation()
,W/FusedLocationProvider( 1436): location=null
,I/art     ( 1529): Explicit concurrent mark sweep GC freed 2928(114KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/26MB, paused 3.407ms total 20.451ms
,D/GCM     ( 1436): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/MediaStoreImporter( 2800): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,E/SQLiteLog( 2147): (284) automatic index on view_events(_id)
,W/ResourcesManager( 2611): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2611): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2611): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 2611): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 2611): Installed default security provider GmsCore_OpenSSL
,E/PhoneInterfaceManager( 1222): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/Babel   ( 2611): connection state changed from UNKNOWN to DISCONNECTED
,D/BluetoothManagerService(  756): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  756): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  756): Message: 2
,D/WifiService(  756): New client listening to asynchronous messages
,D/WifiService(  756): setWifiEnabled: false pid=2492, uid=10278
E/WifiService(  756): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 2492): ****TEST TOOK:  5040  ms ****
I/jxcore-log( 2492): 
I/jxcore-log( 2492): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2492): 
,D/AndroidRuntime( 2902): 
D/AndroidRuntime( 2902): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 2902): CheckJNI is OFF
,D/AndroidRuntime( 2902): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  756): Force stopping com.example.hello appid=10278 user=-1: uninstall pkg
I/ActivityManager(  756): Killing 2492:com.example.hello/u0a278 (adj 0): stop com.example.hello
,I/WindowState(  756): WIN DEATH: Window{158fdf5f u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  756): Client connection lost with reason: 4
,W/PackageSettings(  756): Skipping PackageSetting{2e9e1c07 com.test.thalitest/10270} due to missing metadata
,W/ActivityManager(  756): Force removing ActivityRecord{777b20 u0 com.example.hello/.MainActivity t220}: app died, no saved state
,W/ActivityManager(  756): Spurious death for ProcessRecord{38e88884 2492:com.example.hello/u0a278}, curProc for 2492: null
,I/ActivityManager(  756): Force stopping com.example.hello appid=10278 user=0: pkg removed
,I/Keyboard.Facilitator( 1085): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1085): run()
,W/GeofencerStateMachine( 1436): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  756): Reconfiguring input devices.  changes=0x00000010
,I/Decoder ( 1085): createOrResetDecoder
,I/ActivityManager(  756): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=2937 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,I/art     ( 1618): Explicit concurrent mark sweep GC freed 21602(1515KB) AllocSpace objects, 23(368KB) LOS objects, 39% free, 21MB/36MB, paused 926us total 39.341ms
,I/ConfigService( 1436): onCreate
,D/BackupManagerService(  756): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  756): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  756): removeObsoleteFile: deleting file=220_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1085): run()
,I/art     (  756): Explicit concurrent mark sweep GC freed 14789(932KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 3.078ms total 134.075ms
,I/HotwordRecognitionRnr( 1454): Starting hotword detection.
,I/MicrophoneInputStream( 1454): mic_starting gfk@6b2450e
,I/AudioFlinger(  183): AudioFlinger's thread 0xb1bbe000 ready to run
,I/MicrophoneInputStream( 1454): mic_started gfk@6b2450e
,D/audio_hw_primary(  183): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  183): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
D/        (  183): Failed to fetch the lookup information of the device 0000003E 
E/ACDB-LOADER(  183): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  183): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  183): enable_audio_route: apply and update mixer path: audio-record
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1085): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1085): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1085): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1085): run()
I/StatsUtilsManager( 1085): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1085): shouldRecordStats() = Too Soon
,D/VoicemailCleanupService( 2937): Cleaning up data for package: com.example.hello
,D/AndroidRuntime( 2902): Shutting down VM
,I/ActivityManager(  756): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2971 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/HotwordWorker( 1454): onReady
,I/ContactLocale( 2937): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/ResourcesManager( 1269): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1454): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,W/ResourcesManager( 1269): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  756): Killing 2303:com.google.android.configupdater/u0a36 (adj 15): empty #17
,W/Launcher( 1269): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2a8205a3 new=com.google.android.velvet.VelvetApplication@2a8205a3
,W/libprocessgroup(  756): failed to open /acct/uid_10036/pid_2303/cgroup.procs: No such file or directory
,I/ActivityManager(  756): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2995 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/art     (  194): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 189us total 9.165ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 205us total 7.483ms
,I/ActivityManager(  756): Killing 2341:com.google.android.keep/u0a71 (adj 15): empty #17
,I/UpdateIcingCorporaServi( 1454): UpdateCorporaTask done [took 148 ms] updated apps [took 148 ms] 
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 174us total 8.134ms
,W/libprocessgroup(  756): failed to open /acct/uid_10071/pid_2341/cgroup.procs: No such file or directory
,W/ContextImpl( 2995): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1618): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1618): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1618): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1618): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1618): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1618): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1436): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1436): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  756): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3020 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  756): Killing 2367:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,I/LocationSettingsChecker( 1618): Removing dialog suppression flag for package com.example.hello
,E/SQLiteDatabase( 1618): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1618): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1618): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1618): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1618): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1618): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1618): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1618): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1618): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1618): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1618): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1618): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1618): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1618): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1618): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1618): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1618): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1618): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1618): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1618): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1618): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1618): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1618): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 1618): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1618): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1618): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1618): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1618): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1618): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1618): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1618): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1618): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1618): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1618): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1618): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteOpenHelper( 1618): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1618): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1618): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1618): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1618): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1618): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1618): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1618): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1618): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1618): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1618): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 1618): Opened metrics.db in read-only mode
,D/gH_CompatibleDatabase( 1618): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1618): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1618): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.example.hello"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1618): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
--------- beginning of crash
E/AndroidRuntime( 1618): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1618): Process: com.google.android.gms, PID: 1618
E/AndroidRuntime( 1618): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 1618): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1618): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1618): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1618): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1618): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1618): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1618): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1618): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1618): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1618): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1618): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/libprocessgroup(  756): failed to open /acct/uid_1000/pid_2367/cgroup.procs: No such file or directory
,E/SQLiteDatabase( 1618): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1618): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1618): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1618): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1618): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1618): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1618): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1618): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1618): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1618): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1618): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1618): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1618): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1618): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1618): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1618): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1618): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1618): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1618): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1618): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1618): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 1618): Could not unregister android package com.example.hello
E/PhenotypeInitializer( 1618): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1618): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1618): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PhenotypeInitializer( 1618): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PhenotypeInitializer( 1618): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1618): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1618): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1618): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/PhenotypeInitializer( 1618): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/PhenotypeInitializer( 1618): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PhenotypeInitializer( 1618): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/PhenotypeInitializer( 1618): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/PhenotypeInitializer( 1618): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/PhenotypeInitializer( 1618): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 1618): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 1618): 	at com.google.android.g,ms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1618): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1618): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1618): 	at android.os.Looper.loop(Looper.java:135)
E/PhenotypeInitializer( 1618): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  756): Can't write: system_app_crash
E/DropBoxManagerService(  756): java.io.FileNotFoundException: /data/system/dropbox/drop83.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  756): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  756): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  756): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  756): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  756): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  756): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  756): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  756): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  756): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  756): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  756): 	... 5 more
D/OpenGLRenderer(  756): Render dirty regions requested: true
D/Atlas   (  756): Validating map...
W/OpenGLRenderer( 1269): Incorrectly called buildLayer on View: adg, destroying layer...
W/OpenGLRenderer( 1269): Incorrectly called buildLayer on View: adg, destroying layer...
E/qdhwcomposer(  172): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  172): hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
E/qdoverlay(  172): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  172): MdpData failed to play
E/qdoverlay(  172): == Dump MdpData start ==
E/qdoverlay(  172): == Dump OvFD fd=34 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  172): mOvData msmfb_overlay_data id=64
E/qdoverlay(  172): data msmfb_data offset=0 memid=53 id=0 flags=0x0 priv=0
E/qdoverlay(  172): == Dump MdpData end ==
E/qdhwcomposer(  172): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  172): hwc_set_primary: MDPComp draw failed
E/qdhwcomposer(  172): display_commit: MSMFB_DISPLAY_COMMIT for primary failed
E/qdhwcomposer(  172): hwc_set_primary: display commit fail!
,W/BaseAppContext( 1618): Using Auth Proxy for data requests.
,W/BaseAppContext( 1618): Using Auth Proxy for data requests.
,E/qdhwcomposer(  172): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  172): hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
,E/qdoverlay(  172): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  172): MdpData failed to play
E/qdoverlay(  172): == Dump MdpData start ==
E/qdoverlay(  172): == Dump OvFD fd=34 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  172): mOvData msmfb_overlay_data id=64
E/qdoverlay(  172): data msmfb_data offset=0 memid=53 id=0 flags=0x0 priv=0
E/qdoverlay(  172): == Dump MdpData end ==
E/qdhwcomposer(  172): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  172): hwc_set_primary: MDPComp draw failed
E/qdhwcomposer(  172): display_commit: MSMFB_DISPLAY_COMMIT for primary failed
E/qdhwcomposer(  172): hwc_set_primary: display commit fail!
,I/Adreno-EGL(  756): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  756): Initialized EGL, version 1.4
,D/OpenGLRenderer(  756): Enabling debug mode 0
,E/qdoverlay(  172): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  172): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  172): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  172): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  172): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  172): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  172): == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  172): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  172): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  172): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  172): Ctrl commit failed set overlay
E/qdhwcomposer(  172): configureLowRes: commit failed for low res panel
E/qdoverlay(  172): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  172): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  172): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  172): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  172): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  172): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  172): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  172): src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
E/qdoverlay(  172): src_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  172): dst_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  172): Ctrl commit failed set overlay
E/qdhwcomposer(  172): configure: commit fails
E/qdoverlay(  172): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  172): MdpCtrl close error in unset

```
