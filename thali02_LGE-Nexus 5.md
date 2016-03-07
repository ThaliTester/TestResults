#### Test 6170335106d974e_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/art     ( 1564): Explicit concurrent mark sweep GC freed 30337(2MB) AllocSpace objects, 25(400KB) LOS objects, 39% free, 21MB/36MB, paused 1.034ms total 44.268ms
D/a       ( 1564): Opening database auth.proximity.permit_store...
--------- beginning of system
I/ValidateNoPeople(  756): skipping global notification
V/SystemUpdateService( 1564): retry (wakeup: false) in 3599834 ms
D/SystemUpdateService( 1564): onDestroy
D/AuthZenTransactionCache( 1564): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1564): Clearing transaction cache
W/ResourcesManager(  917): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  917): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 1441): Explicit concurrent mark sweep GC freed 2886(114KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/26MB, paused 1.465ms total 19.899ms
D/GCM     ( 1265): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
I/GCoreUlr( 1265): DispatchingService.onCreate()
,I/GCoreUlr( 1265): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
W/GCoreFlp( 1265): No location to return for getLastLocation()
W/FusedLocationProvider( 1265): location=null
W/GCoreFlp( 1265): No location to return for getLastLocation()
W/FusedLocationProvider( 1265): location=null
W/Auth    ( 1265): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PersistentNotificationBroadcastReceiver( 1265): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
I/GCoreUlr( 1265): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1265): Unbound from all location providers
I/GCoreUlr( 1265): Place inference reporting - stopped
I/ActivityManager(  756): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2384 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/GCoreUlr( 1265): DispatchingService.onDestroy()
I/GCoreUlr( 1265): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1265): Unbound from all location providers
I/GCoreUlr( 1265): Place inference reporting - stopped
D/AndroidRuntime( 2376): 
D/AndroidRuntime( 2376): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2376): CheckJNI is OFF
D/AndroidRuntime( 2376): Calling main entry com.android.commands.am.Am
I/ActivityManager(  756): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 2376): Shutting down VM
W/ResourcesManager( 2384): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2384): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  756): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2416 uid=10278 gids={50278, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/art     (  194): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 180us total 8.007ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 7.542ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 170us total 7.307ms
I/MicrophoneInputStream( 1347): mic_close gfk@36006a92
V/JNIHelp ( 2384): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/audio_hw_primary(  183): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  183): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1347): Hotword detection finished
I/HotwordRecognitionRnr( 1347): Stopping hotword detection.
I/WebViewFactory( 2416): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2416): Time to load native libraries: 1 ms (timestamps 4851-4852)
I/LibraryLoader( 2416): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 2416): Binding Chromium to main looper Looper (main, tid 1) {1bce55b}
I/LibraryLoader( 2416): Expected native library version number "",actual native library version number ""
I/chromium( 2416): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/System  ( 2384): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2384): Installed default security provider GmsCore_OpenSSL
I/BrowserStartupController( 2416): Initializing chromium process, singleProcess=true
W/art     ( 2416): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2416): ApplicationContext is null in ApplicationStatus
W/chromium( 2416): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 2416): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2416): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2416): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2416): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothManagerService(  756): Message: 20
D/BluetoothManagerService(  756): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@85f20a9:true
D/BluetoothAdapter( 2416): 7949: getState() :  mService = null. Returning STATE_OFF
W/art     ( 2416): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 2416): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 2416): CordovaWebView is running on device made by: LGE
W/art     ( 2416): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2416): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 2416): Render dirty regions requested: true
D/Atlas   ( 2416): Validating map...
W/chromium( 2416): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 2416): Initialized EGL, version 1.4
D/OpenGLRenderer( 2416): Enabling debug mode 0
E/YouTube MDX( 2384): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
I/dex2oat ( 2480): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads437488482.jar --oat-fd=26 --oat-location=/data/data/com.google.android.youtube/cache/ads437488482.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/ActivityManager(  756): Displayed com.example.hello/.MainActivity: +466ms (total +12s178ms)
I/Keyboard.Facilitator( 1065): onFinishInput()
W/BindingManager( 2416): Cannot call determinedVisibility() - never saw a connection for the pid: 2416
I/chromium( 2416): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/dex2oat ( 2480): dex2oat took 65.728ms (threads: 4)
D/JsMessageQueue( 2416): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 2416): Unable to open asset URL: file:///android_asset/www/jxcore.js
,W/InstanceID/Rpc( 2384): Found 10008
,D/jxcore_app_log( 2416): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,W/jxcore-log( 2416): Initializing JXcore engine
W/jxcore-log( 2416): JXcore engine is ready
,W/Thread-241( 2516): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8400]" dev="sockfs" ino=8400 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-241( 2516): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-241( 2516): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9565]" dev="sockfs" ino=9565 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-241( 2516): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[16458]" dev="sockfs" ino=16458 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2416): Starting JXcore engine
,I/ActivityManager(  756): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=2541 uid=10054 gids={50054, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/jxcore-log( 2416): Platform android
W/jxcore-log( 2416): 
W/jxcore-log( 2416): Process ARCH arm
W/jxcore-log( 2416): 
,I/ActivityManager(  756): Killing 1830:com.android.musicfx/u0a15 (adj 15): empty #17
,W/ResourcesManager( 2541): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/jxcore-log( 2416): JXcore Cordova bridge is ready!
I/jxcore-log( 2416): 
W/jxcore-log( 2416): JXcore engine is started
,W/libprocessgroup(  756): failed to open /acct/uid_10015/pid_1830/cgroup.procs: No such file or directory
,E/jxcore-log( 2416): >> LGE-Nexus 5
E/jxcore-log( 2416): 
,I/jxcore-log( 2416): Total memory 1946181632
I/jxcore-log( 2416): 
,I/jxcore-log( 2416): Free memory 388374528
I/jxcore-log( 2416): 
I/jxcore-log( 2416): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2416): 
I/jxcore-log( 2416): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2416): 
I/jxcore-log( 2416): userPath [ 'www', 'www' ]
I/jxcore-log( 2416): 
,I/jxcore-log( 2416): Size 1080 1776
I/jxcore-log( 2416): 
,I/jxcore-log( 2416): Screen Brightness 82
I/jxcore-log( 2416): 
E/jxcore-log( 2416): Dummy Error Log.
E/jxcore-log( 2416): 
,I/Babel_SMS( 2541): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 2541): MmsConfig.loadMmsSettings
,I/Babel_SMS( 2541): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/Babel_SMS( 2541): MmsConfig.loadFromDatabase
,E/Babel_SMS( 2541): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 2541): MmsConfig.loadFromResources
,E/Babel_SMS( 2541): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 2541): MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/Babel_SMS( 2541): ApnsOta: OTA version -1
,W/Settings( 2541): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 2541): startup - clean
,I/Babel   ( 2541): deleted: false for 0
,V/Babel   ( 2541): babel boot account: thalitester@gmail.com
,W/VideoCapabilities( 2541): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 2541): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 2541): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2541): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2541): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2541): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 2541): onServiceConnected
,W/Babel   ( 2541): Attempted to change video mute state without an active call.
,I/ActivityManager(  756): Start proc com.google.android.apps.fitness for broadcast com.google.android.apps.fitness/.FitnessBootReceiver: pid=2578 uid=10045 gids={50045, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/jxcore-log( 2416): getBuffer is called!!!!
I/jxcore-log( 2416): 
,E/SQLiteLog( 2541): (284) automatic index on conversation_participants_view(conversation_id)
,W/VideoCapabilities( 2541): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2541): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2541): Unrecognized profile 2130706433 for video/avc
,E/SQLiteLog( 2541): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 2541): (284) automatic index on conversation_participants_view(conversation_id)
,I/FitnessApp( 2578): Initializers took 0 milliseconds
,I/art     (  756): Explicit concurrent mark sweep GC freed 14148(700KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/40MB, paused 690us total 49.051ms
,I/ActivityManager(  756): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2598 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
I/ActivityManager(  756): Killing 1862:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10040/pid_1862/cgroup.procs: No such file or directory
,I/ActivityManager(  756): Killing 1960:com.google.android.apps.plus/u0a67 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10067/pid_1960/cgroup.procs: No such file or directory
,I/GAv4    ( 2598): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2598):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2598):   adb logcat -s GAv4
,W/GAv4    ( 2598): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2598): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2598): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  756): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2630 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  756): Killing 2015:com.android.keychain/1000 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_1000/pid_2015/cgroup.procs: No such file or directory
,I/Gmail   ( 2630): getAccountsCursor
,D/ActivityThread( 2630): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  756): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=2656 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GAV2    ( 2630): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  756): Killing 2035:com.google.android.dialer/u0a10 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10010/pid_2035/cgroup.procs: No such file or directory
,W/ActivityManager(  756): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 2656): EasService.onCreate
,I/Gmail   ( 2630): Observing account changes for notifications
,I/Gmail   ( 2630): getAccountsCursor
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Exchange( 2656): RestartPingTask
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Volley  ( 1902): [163] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 1902): [156] DiskBasedCache.clear: Cache cleared.
,I/SystemBroadcastReceiver( 1065): Boot has been completed
I/SystemBroadcastReceiver( 1065): toggleAppIcon() : FLAG_SYSTEM = true
,V/UserPresentBroadcastReceiver( 1265): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,E/SQLiteLog( 2630): (283) recovered 47 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/ActivityManager(  756): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=2703 uid=10003 gids={50003, 9997} abi=armeabi-v7a
,I/Exchange( 2656): RestartPingsTask did not start any pings.
,I/Exchange( 2656): PSS stopIfIdle
I/Exchange( 2656): PSS has no active accounts; stopping service.
,E/ActivityThread( 2630): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@917d0f that was originally bound here
E/ActivityThread( 2630): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@917d0f that was originally bound here
E/ActivityThread( 2630): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2630): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2630): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2630): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2630): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2630): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 2630): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 2630): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 2630): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 2630): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 2630): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 2630): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 2630): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 2630): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2630): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2630): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/a       ( 2630): RuntimeException when trying to unbind from service
E/a       ( 2630): java.lang.IllegalArgumentException: Service not registered: com.android.emailcommon.service.am@917d0f
E/a       ( 2630): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1024)
E/a       ( 2630): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1802)
E/a       ( 2630): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/a       ( 2630): 	at com.android.emailcommon.service.an.a(SourceFile:124)
E/a       ( 2630): 	at com.android.emailcommon.service.an.doInBackground(SourceFile:111)
E/a       ( 2630): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/a       ( 2630): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/a       ( 2630): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/a       ( 2630): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/a       ( 2630): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/a       ( 2630): 	at java.lang.Thread.run(Thread.java:818)
,I/Gmail   ( 2630): notifyAccountChanged
,I/Gmail   ( 2630): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 2630): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager(  756): Killing 1308:android.process.acore/u0a4 (adj 15): empty #17
,I/Gmail   ( 2630): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 2630): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/libprocessgroup(  756): failed to open /acct/uid_10004/pid_1308/cgroup.procs: No such file or directory
,D/CellBroadcastReceiver( 2703): onReceive Intent { act=android.intent.action.SERVICE_STATE flg=0x10 cmp=com.android.cellbroadcastreceiver/.CellBroadcastReceiver (has extras) }
D/CellBroadcastReceiver( 2703): Intent ACTION_SERVICE_STATE_CHANGED
,D/CellBroadcastReceiver( 2703): Service state changed! 3 Full: 3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=false Current state=-1
,I/ActivityManager(  756): Killing 2122:com.google.android.onetimeinitializer/u0a12 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10012/pid_2122/cgroup.procs: No such file or directory
,D/SIP     ( 1188): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,D/LocationInitializer( 1564): Restart initialization of location
,E/MDM     ( 1265): [184] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1265): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/Gmail   ( 2630): getAccountsCursor
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 2630): getAccountsCursor
,I/ActivityManager(  756): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2736 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1265): No location to return for getLastLocation()
,W/FusedLocationProvider( 1265): location=null
,I/MusicStore( 2736): Database version: 120
,I/GAv4-SVC( 1564): Google Analytics 8.4.89 is starting up.
,I/GAV2    ( 1347): Thread[GAThread,5,main]: No campaign data found.
,D/CAR.SERVICE( 2103): mConnectedToCar = false, abort
,E/ActivityThread( 2103): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@60553a0 that was originally bound here
E/ActivityThread( 2103): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@60553a0 that was originally bound here
E/ActivityThread( 2103): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2103): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2103): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2103): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2103): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2103): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2103): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2103): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 2103): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 2103): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 2103): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 2103): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 2103): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 2103): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 2103): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 2103): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 2103): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2103): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2103): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 2103): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2103): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2103): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 2103): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 2103): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@704e51b that was originally bound here
E/ActivityThread( 2103): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@704e51b that was originally bound here
E/ActivityThread( 2103): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2103): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2103): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2103): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2103): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2103): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 2103): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 2103): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 2103): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 2103): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 2103): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 2103): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 2103): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 2103): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 2103): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 2103): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2103): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2103): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 2103): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2103): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2103): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 2103): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  756): Unbind failed: could not find connection for android.os.BinderProxy@a025936
,W/ResourcesManager( 2736): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2736): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2736): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 2736): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 2736): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@22027c01: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2736): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 2736): GMSCore installation verified
,I/ConfigStore( 2736): Config Database version: 1
,W/ContextImpl( 2189): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 2189): Thread[GAThread,5,main]: No campaign data found.
,I/MediaRouter( 2736): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/GHttpClientFactory( 2736): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2736): Using platform SSLCertificateSocketFactory
,I/art     ( 1265): Explicit concurrent mark sweep GC freed 15707(1023KB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 21MB/35MB, paused 1.528ms total 35.412ms
,D/Finsky  ( 1902): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 1902): [182] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,I/art     (  756): Explicit concurrent mark sweep GC freed 8801(463KB) AllocSpace objects, 3(52KB) LOS objects, 33% free, 27MB/40MB, paused 785us total 48.036ms
,V/GLSActivity( 1265): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1265): No location to return for getLastLocation()
,W/FusedLocationProvider( 1265): location=null
,I/art     ( 1441): Explicit concurrent mark sweep GC freed 2625(103KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 552us total 18.555ms
,D/GCM     ( 1265): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/MediaStoreImporter( 2736): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  756): Killing 2154:com.android.managedprovisioning/u0a14 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10014/pid_2154/cgroup.procs: No such file or directory
,E/SQLiteLog( 2075): (284) automatic index on view_events(_id)
,W/ResourcesManager( 2541): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2541): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2541): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/art     ( 2541): Suspending all threads took: 6.466ms
,W/System  ( 2541): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2541): Installed default security provider GmsCore_OpenSSL
,D/BluetoothManagerService(  756): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  756): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  756): Message: 2
,D/WifiService(  756): New client listening to asynchronous messages
,D/WifiService(  756): setWifiEnabled: false pid=2416, uid=10278
E/WifiService(  756): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 2416): ****TEST TOOK:  5035  ms ****
I/jxcore-log( 2416): 
I/jxcore-log( 2416): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2416): 
,D/AndroidRuntime( 2817): 
D/AndroidRuntime( 2817): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2817): CheckJNI is OFF
,D/AndroidRuntime( 2817): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  756): Force stopping com.example.hello appid=10278 user=-1: uninstall pkg
I/ActivityManager(  756): Killing 2416:com.example.hello/u0a278 (adj 0): stop com.example.hello
,I/WindowState(  756): WIN DEATH: Window{3dc6538c u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  756): Client connection lost with reason: 4
,W/PackageSettings(  756): Skipping PackageSetting{13da2d0c com.test.thalitest/10270} due to missing metadata
,W/ActivityManager(  756): Force removing ActivityRecord{1cd8a432 u0 com.example.hello/.MainActivity t220}: app died, no saved state
,W/ActivityManager(  756): Spurious death for ProcessRecord{3dcf2bf6 2416:com.example.hello/u0a278}, curProc for 2416: null
,I/ActivityManager(  756): Force stopping com.example.hello appid=10278 user=0: pkg removed
,I/Keyboard.Facilitator( 1065): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1265): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  756): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  756): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=2839 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,I/art     ( 1564): Explicit concurrent mark sweep GC freed 19930(1421KB) AllocSpace objects, 23(368KB) LOS objects, 39% free, 21MB/36MB, paused 960us total 61.853ms
,I/Keyboard.Facilitator.DecoderInitializer( 1065): run()
,I/Decoder ( 1065): createOrResetDecoder
,I/ConfigService( 1265): onCreate
,D/BackupManagerService(  756): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  756): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  756): removeObsoleteFile: deleting file=220_task.xml
,W/InputMethodManagerService(  756): Got RemoteException sending setActive(false) notification to pid 2416 uid 10278
,I/Keyboard.Facilitator( 1065): onFinishInput()
,I/MicrophoneInputStream( 1347): mic_starting gfk@1cb2d687
,I/HotwordRecognitionRnr( 1347): Starting hotword detection.
,I/AudioFlinger(  183): AudioFlinger's thread 0xb46b9000 ready to run
,I/MicrophoneInputStream( 1347): mic_started gfk@1cb2d687
,D/audio_hw_primary(  183): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  183): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
D/        (  183): Failed to fetch the lookup information of the device 0000003E 
E/ACDB-LOADER(  183): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  183): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  183): enable_audio_route: apply and update mixer path: audio-record
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1065): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1065): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1065): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1065): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1065): run()
I/StatsUtilsManager( 1065): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1065): shouldRecordStats() = Too Soon
,D/VoicemailCleanupService( 2839): Cleaning up data for package: com.example.hello
,W/ResourcesManager( 1218): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  756): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2881 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/art     (  756): Explicit concurrent mark sweep GC freed 18761(1122KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 2.296ms total 147.752ms
,W/ResourcesManager( 1218): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/HotwordWorker( 1347): onReady
,I/ContactLocale( 2839): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/AndroidRuntime( 2817): Shutting down VM
,I/UpdateIcingCorporaServi( 1347): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/ActivityManager(  756): Killing 2229:com.google.android.configupdater/u0a36 (adj 15): empty #17
,W/Launcher( 1218): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@ab191f8 new=com.google.android.velvet.VelvetApplication@ab191f8
,I/ActivityManager(  756): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2911 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,W/libprocessgroup(  756): failed to open /acct/uid_10036/pid_2229/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1347): UpdateCorporaTask done [took 97 ms] updated apps [took 97 ms] 
,W/ContextImpl( 2911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1564): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1564): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1564): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1564): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1564): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1564): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1564): Removing dialog suppression flag for package com.example.hello
,I/ActivityManager(  756): Killing 2269:com.google.android.keep/u0a71 (adj 15): empty #17
,D/gH_CompatibleDatabase( 1564): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1564): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1564): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1564): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1564): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1564): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1564): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1564): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1564): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1564): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1564): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1564): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1564): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/libprocessgroup(  756): failed to open /acct/uid_10071/pid_2269/cgroup.procs: No such file or directory
,E/NetworkScheduler.SchedulerReceiver( 1265): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1265): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  756): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2936 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/art     (  194): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 252us total 9.820ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 12.073ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 180us total 8.177ms
,W/BaseAppContext( 1564): Using Auth Proxy for data requests.
,W/BaseAppContext( 1564): Using Auth Proxy for data requests.
,W/OpenGLRenderer( 1218): Incorrectly called buildLayer on View: adg, destroying layer...
W/OpenGLRenderer( 1218): Incorrectly called buildLayer on View: adg, destroying layer...
,I/GMPM-SVC( 1564): App measurement is starting up, version: 8489
,I/GMPM-SVC( 1564): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/Icing   ( 1564): doRemovePackageData com.example.hello
,D/ConnectivityService(  756): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/SQLiteLog( 1564): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/GMPM-SVC( 1564): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
,E/SharedPreferencesImpl( 1564): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,W/DriveInitializer( 1564): Awaiting to be initialized
W/DriveInitializer( 1564): Background init thread started
E/SQLiteLog( 1564): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock163] disk I/O error
,E/DocListDatabase( 1564): Failed to delete from ContentFileDeletionLock163 table
E/DocListDatabase( 1564): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1564): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1564): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1564): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1564): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1564): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1564): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 1564): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/DocListDatabase( 1564): 	at com.google.android.gms.drive.t.run(SourceFile:62)
W/DriveInitializer( 1564): Background init thread ended
E/SQLiteLog( 1564): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 1564): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1564): Process: com.google.android.gms, PID: 1564
E/AndroidRuntime( 1564): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1564): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1564): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1564): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1564): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1564): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1564): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 1564): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/AndroidRuntime( 1564): 	at com.google.android.gms.drive.t.run(SourceFile:62)
E/DriveAsyncService( 1564): disk I/O error (code 3850)
E/DriveAsyncService( 1564): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1564): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1564): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1564): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1564): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1564): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1564): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1564): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1564): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1564): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1564): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1564): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1564): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1564): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1564): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1564): 	at java.lang.Thread.run(Thread.java:818)
,E/DropBoxManagerService(  756): Can't write: system_app_crash
E/DropBoxManagerService(  756): java.io.FileNotFoundException: /data/system/dropbox/drop86.tmp: open failed: EROFS (Read-only file system)
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
W/ResourcesManager(  756): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  756): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/OpenGLRenderer(  756): Render dirty regions requested: true
D/Atlas   (  756): Validating map...
,E/qdhwcomposer(  172): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  172): hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
E/qdoverlay(  172): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  172): MdpData failed to play
,E/qdoverlay(  172): == Dump MdpData start ==
E/qdoverlay(  172): == Dump OvFD fd=33 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  172): mOvData msmfb_overlay_data id=64
E/qdoverlay(  172): data msmfb_data offset=0 memid=49 id=0 flags=0x0 priv=0
E/qdoverlay(  172): == Dump MdpData end ==
E/qdhwcomposer(  172): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  172): hwc_set_primary: MDPComp draw failed
E/qdhwcomposer(  172): display_commit: MSMFB_DISPLAY_COMMIT for primary failed
E/qdhwcomposer(  172): hwc_set_primary: display commit fail!
,E/qdoverlay(  172): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
,E/qdoverlay(  172): MdpCtrl failed to setOverlay, restoring last known good ov info
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
,I/Adreno-EGL(  756): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  756): Initialized EGL, version 1.4
,D/OpenGLRenderer(  756): Enabling debug mode 0

```
