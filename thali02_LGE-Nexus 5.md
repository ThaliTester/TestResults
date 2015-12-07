#### Test 502422852e23b2c_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/FileApkUtils( 1569): Spent 26ms computing apk sha1.
D/FileApkUtils( 1569): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 1569): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-2707d05c501ef4bf821813f1789ad0e56682eb5a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-2707d05c501ef4bf821813f1789ad0e56682eb5a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
D/DexOptUtils( 1569): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-2707d05c501ef4bf821813f1789ad0e56682eb5a/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 1569): Keeping up-to-date module: module-2707d05c501ef4bf821813f1789ad0e56682eb5a
D/GmsModuleFndr( 1569): Beginning GMS chimera module scan
D/GmsModuleFndr( 1569): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 1569): Beginning module configuration check
D/ChimeraCfgMgr( 1569): Module APKs unchanged, check complete
V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ChimeraCfgMgr( 1569): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GCM     ( 1569): COMPAT: Multi user ser=0 current=0
D/GCM     ( 1330): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
I/GCoreUlr( 1569): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
I/GCoreUlr( 1304): DispatchingService.onCreate()
I/CheckinService( 1569): Checkin interval check for package: unspecified last checkin: 1449470914839 min interval config: 0 actual interval: 26337987
I/art     ( 1304): Explicit concurrent mark sweep GC freed 14559(881KB) AllocSpace objects, 10(160KB) LOS objects, 40% free, 19MB/32MB, paused 1.241ms total 29.508ms
I/CheckinService( 1569): Disabling old GoogleServicesFramework version
D/SystemUpdateService( 1569): onCreate
D/SystemUpdateService( 1569): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
D/ChimeraCfgMgr( 1569): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/SystemUpdateService( 1569): active receiver: enabled
V/AuthZen ( 1569): Handling intent: android.intent.action.BOOT_COMPLETED
D/AuthZenEventHandler( 1569): Handling event: android.intent.action.BOOT_COMPLETED
I/GCoreUlr( 1304): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1304): No location to return for getLastLocation()
W/FusedLocationProvider( 1569): location=null
I/CheckinService( 1569): Checking schedule, now: 1449497252910 next: 1449513081796
I/CheckinService( 1569): active receiver: disabled
V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Kids    ( 1569): [AbstractKidsOperation] Invalid device state 3
W/GCoreFlp( 1304): No location to return for getLastLocation()
W/FusedLocationProvider( 1569): location=null
I/Kids    ( 1569): [KidAccountFixer] No network connection
W/Auth    ( 1330): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GmsCoreStatsServiceLauncher( 1569): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
W/BaseAppContext( 1569): Using Auth Proxy for data requests.
I/SystemUpdateService( 1569): showing system update notification
D/PersistentNotificationBroadcastReceiver( 1330): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
--------- beginning of system
I/ActivityManager(  734): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2252 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 1569): Explicit concurrent mark sweep GC freed 27326(2MB) AllocSpace objects, 28(448KB) LOS objects, 40% free, 19MB/32MB, paused 926us total 51.622ms
I/AuthZen ( 1569): Fetching signing key...
I/ValidateNoPeople(  734): skipping global notification
V/SystemUpdateService( 1569): retry (wakeup: false) in 3599816 ms
W/ResourcesManager(  898): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  898): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/GCoreUlr( 1304): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/SystemUpdateService( 1569): onDestroy
I/AuthZen ( 1569): Signing key fetched successfully!
I/GCoreUlr( 1304): Unbound from all location providers
W/BaseAppContext( 1569): Using Auth Proxy for data requests.
I/GCoreUlr( 1304): DispatchingService.onDestroy()
I/GCoreUlr( 1304): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1304): Unbound from all location providers
D/a       ( 1569): Opening database auth.proximity.permit_store...
D/AuthZenTransactionCache( 1569): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1569): Clearing transaction cache
W/ResourcesManager( 2252): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2252): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 2252): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
I/art     ( 1330): Explicit concurrent mark sweep GC freed 7344(418KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 19MB/32MB, paused 580us total 28.756ms
W/System  ( 2252): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2252): Installed default security provider GmsCore_OpenSSL
E/YouTube MDX( 2252): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
I/dex2oat ( 2285): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-183669986.jar --oat-fd=21 --oat-location=/data/data/com.google.android.youtube/cache/ads-183669986.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 2285): dex2oat took 41.102ms (threads: 4)
,W/InstanceID/Rpc( 2252): Found 10008
D/AndroidRuntime( 2312): 
D/AndroidRuntime( 2312): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2312): CheckJNI is OFF
I/art     (  734): Explicit concurrent mark sweep GC freed 17051(827KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/40MB, paused 4.113ms total 52.302ms
V/Babel   ( 1787): babel boot account: thalitester@gmail.com
D/AndroidRuntime( 2312): Calling main entry com.android.commands.am.Am
E/SQLiteLog( 1787): (284) automatic index on conversation_participants_view(conversation_id)
I/ActivityManager(  734): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2365 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
I/ActivityManager(  734): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 2312): Shutting down VM
I/ActivityManager(  734): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2384 uid=10277 gids={50277, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/MicrophoneInputStream( 1386): mic_close gfk@3517b052
W/VideoCapabilities( 1787): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 1787): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 1787): Unrecognized profile 2130706433 for video/avc
E/SQLiteLog( 1787): (284) automatic index on conversation_participants_view(conversation_id)
E/SQLiteLog( 1787): (284) automatic index on conversation_participants_view(conversation_id)
D/audio_hw_primary(  185): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  185): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1386): Stopping hotword detection.
I/HotwordRecognitionRnr( 1386): Hotword detection finished
I/WebViewFactory( 2384): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/GAv4    ( 2365): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2365):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2365):   adb logcat -s GAv4
I/LibraryLoader( 2384): Time to load native libraries: 1 ms (timestamps 3650-3651)
I/LibraryLoader( 2384): Expected native library version number "",actual native library version number ""
W/GAv4    ( 2365): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
V/WebViewChromiumFactoryProvider( 2384): Binding Chromium to main looper Looper (main, tid 1) {5a1409c}
I/LibraryLoader( 2384): Expected native library version number "",actual native library version number ""
I/chromium( 2384): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2384): Initializing chromium process, singleProcess=true
W/art     ( 2384): Attempt to remove local handle scope entry from IRT, ignoring
W/GAv4    ( 2365): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SysUtils( 2384): ApplicationContext is null in ApplicationStatus
W/GAv4    ( 2365): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/chromium( 2384): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 2384): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2384): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2384): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2384): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@275c76bc:true
D/BluetoothAdapter( 2384): 430269995: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  734): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2420 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  734): Killing 1622:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  734): Client connection lost with reason: 4
,W/libprocessgroup(  734): failed to open /acct/uid_1000/pid_1622/cgroup.procs: No such file or directory
,W/art     ( 2384): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2384): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2384): CordovaWebView is running on device made by: LGE
,W/art     ( 2384): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2384): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2384): Render dirty regions requested: true
,D/Atlas   ( 2384): Validating map...
,W/chromium( 2384): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/Gmail   ( 2420): getAccountsCursor
,D/ActivityThread( 2420): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SurfaceFlinger(  171): shader cache generated - 24 shaders in 140.954224 ms
,I/OpenGLRenderer( 2384): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2384): Enabling debug mode 0
,I/ActivityManager(  734): Displayed com.example.hello/.MainActivity: +652ms (total +13s648ms)
,W/BindingManager( 2384): Cannot call determinedVisibility() - never saw a connection for the pid: 2384
,I/chromium( 2384): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/ActivityManager(  734): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=2467 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/JsMessageQueue( 2384): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 2384): Unable to open asset URL: file:///android_asset/www/jxcore.js
,W/GAV2    ( 2420): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Gmail   ( 2420): getAccountsCursor
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemBroadcastReceiver( 1074): Boot has been completed
I/SystemBroadcastReceiver( 1074): toggleAppIcon() : FLAG_SYSTEM = true
,D/jxcore_app_log( 2384): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 2384): jxcore cordova android initializing
,W/ActivityManager(  734): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 2420): Observing account changes for notifications
,I/Exchange( 2467): EasService.onCreate
,E/ActivityThread( 2420): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@b2547e7 that was originally bound here
E/ActivityThread( 2420): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@b2547e7 that was originally bound here
E/ActivityThread( 2420): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2420): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2420): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2420): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2420): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2420): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 2420): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 2420): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 2420): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 2420): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 2420): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 2420): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 2420): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2420): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Exchange( 2467): RestartPingTask
,W/jxcore-log( 2384): Initializing JXcore engine
W/jxcore-log( 2384): JXcore engine is ready
,W/jxcore-log( 2384): Starting JXcore engine
,I/ActivityManager(  734): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2509 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  196): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 178us total 8.928ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 166us total 7.405ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 166us total 7.541ms
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Exchange( 2467): RestartPingsTask did not start any pings.
,I/Exchange( 2467): PSS stopIfIdle
I/Exchange( 2467): PSS has no active accounts; stopping service.
,W/m.example.hello( 2384): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7873]" dev="sockfs" ino=7873 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 2384): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/m.example.hello( 2384): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7963]" dev="sockfs" ino=7963 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 2384): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[15820]" dev="sockfs" ino=15820 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,E/SQLiteLog( 2420): (283) recovered 106 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Exchange( 2467): onDestroy
I/ActivityManager(  734): Killing 1650:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
,W/jxcore-log( 2384): Platform android
W/jxcore-log( 2384): 
W/jxcore-log( 2384): Process ARCH arm
W/jxcore-log( 2384): 
,I/Gmail   ( 2420): notifyAccountChanged
,I/Gmail   ( 2420): getAccountsCursor
,I/Gmail   ( 2420): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 2420): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 2420): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 2420): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/jxcore-log( 2384): JXcore Cordova bridge is ready!
I/jxcore-log( 2384): 
,W/jxcore-log( 2384): JXcore engine is started
,E/jxcore-log( 2384): >> LGE-Nexus 5
E/jxcore-log( 2384): 
I/jxcore-log( 2384): Total memory 1946181632
I/jxcore-log( 2384): 
,I/jxcore-log( 2384): Free memory 420290560
I/jxcore-log( 2384): 
I/jxcore-log( 2384): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2384): 
I/jxcore-log( 2384): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2384): 
,I/jxcore-log( 2384): userPath [ 'www' ]
I/jxcore-log( 2384): 
,I/jxcore-log( 2384): Size 1080 1776
I/jxcore-log( 2384): 
,I/jxcore-log( 2384): Screen Brightness 82
I/jxcore-log( 2384): 
,E/jxcore-log( 2384): Dummy Error Log.
E/jxcore-log( 2384): 
,W/libprocessgroup(  734): failed to open /acct/uid_10061/pid_1650/cgroup.procs: No such file or directory
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  734): Killing 1241:com.android.printspooler/u0a72 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10072/pid_1241/cgroup.procs: No such file or directory
,I/Gmail   ( 2420): getAccountsCursor
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  734): Explicit concurrent mark sweep GC freed 9171(480KB) AllocSpace objects, 2(36KB) LOS objects, 33% free, 27MB/40MB, paused 717us total 44.867ms
,D/Finsky  ( 2509): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 2509): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 2509): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 2509): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Volley  ( 2509): [233] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 2509): [226] DiskBasedCache.clear: Cache cleared.
I/ActivityManager(  734): Killing 1902:com.android.keychain/1000 (adj 15): empty #17
,D/Ads     ( 2509): Skipping gmscore version check
,W/libprocessgroup(  734): failed to open /acct/uid_1000/pid_1902/cgroup.procs: No such file or directory
,V/UserPresentBroadcastReceiver( 1304): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/Finsky  ( 2509): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 2509): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  734): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=2561 uid=10003 gids={50003, 9997} abi=armeabi-v7a
,D/Finsky  ( 2509): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 2509): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/CellBroadcastReceiver( 2561): onReceive Intent { act=android.intent.action.SERVICE_STATE flg=0x10 cmp=com.android.cellbroadcastreceiver/.CellBroadcastReceiver (has extras) }
,D/CellBroadcastReceiver( 2561): Intent ACTION_SERVICE_STATE_CHANGED
D/CellBroadcastReceiver( 2561): Service state changed! 3 Full: 3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=false Current state=-1
,I/ActivityManager(  734): Killing 1872:com.google.android.dialer/u0a10 (adj 15): empty #17
,I/jxcore-log( 2384): getBuffer is called!!!!
I/jxcore-log( 2384): 
,W/libprocessgroup(  734): failed to open /acct/uid_10010/pid_1872/cgroup.procs: No such file or directory
,D/SIP     ( 1211): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,I/ActivityManager(  734): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2583 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 2583): Database version: 120
,W/ResourcesManager( 2583): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2583): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2583): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 2583): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 2583): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@372750ea: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2583): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 2583): GMSCore installation verified
,I/ConfigStore( 2583): Config Database version: 1
,I/GAv4-SVC( 1569): Google Analytics 8.3.01 is starting up.
,I/GAV2    ( 1386): Thread[GAThread,5,main]: No campaign data found.
,I/MediaRouter( 2583): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=11, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/GHttpClientFactory( 2583): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2583): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  734): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2624 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1386): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/PackageBroadcastService( 1569): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
D/ChimeraCfgMgr( 1569): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1569): Loading module APK com.google.android.play.games
,I/ActivityManager(  734): Killing 1983:com.google.android.onetimeinitializer/u0a12 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10012/pid_1983/cgroup.procs: No such file or directory
,W/ContextImpl( 2040): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 2040): Thread[GAThread,5,main]: No campaign data found.
,D/ChimeraCfgMgr( 1569): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1569): Module APK com.google.android.play.games already loaded
,I/MediaStoreImporter( 2583): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  734): Killing 2008:com.android.managedprovisioning/u0a14 (adj 15): empty #17
,D/ChimeraCfgMgr( 1569): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1569): Submit a task: h
,W/libprocessgroup(  734): failed to open /acct/uid_10014/pid_2008/cgroup.procs: No such file or directory
D/ChimeraCfgMgr( 1569): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1569): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/h       ( 1569): Processing package: com.example.hello
,I/PeopleContactsSync( 1569): CP2 sync disabled
D/GassUtils( 1569): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
D/h       ( 1569): Found info for package com.example.hello in db.
,I/ActivityManager(  734): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2660 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,W/BaseAppContext( 1569): Using Auth Proxy for data requests.
W/BaseAppContext( 1569): Using Auth Proxy for data requests.
,W/BaseAppContext( 1569): Using Auth Proxy for data requests.
,W/BaseAppContext( 1569): Using Auth Proxy for data requests.
,W/BaseAppContext( 1569): Using Auth Proxy for data requests.
,W/BaseAppContext( 1569): Using Auth Proxy for data requests.
,I/art     ( 1330): Explicit concurrent mark sweep GC freed 5372(266KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 19MB/32MB, paused 689us total 24.962ms
,I/UpdateIcingCorporaServi( 1386): UpdateCorporaTask done [took 525 ms] updated apps [took 525 ms] 
,D/ChimeraCfgMgr( 1569): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1569): Module APK com.google.android.play.games already loaded
,I/GAv4    ( 2660): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2660):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2660):   adb logcat -s GAv4
,W/GAv4    ( 2660): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2660): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2660): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 2660): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,W/ResourcesManager( 2660): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2660): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  734): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2697 uid=10067 gids={50067, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  734): Killing 1949:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10002/pid_1949/cgroup.procs: No such file or directory
,W/ResourcesManager( 2697): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 2660): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 2660): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 2660): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2509): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
,I/art     (  734): Explicit concurrent mark sweep GC freed 10068(487KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/40MB, paused 661us total 48.597ms
,D/ChimeraCfgMgr( 1569): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1569): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  734): Killing 2088:com.google.android.configupdater/u0a36 (adj 15): empty #17
,I/Kids    ( 1569): [KidAccountFixer] No network connection
,W/libprocessgroup(  734): failed to open /acct/uid_10036/pid_2088/cgroup.procs: No such file or directory
,W/GCoreFlp( 1304): No location to return for getLastLocation()
W/FusedLocationProvider( 1330): location=null
,D/GCM     ( 1330): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Icing   ( 1569): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
,D/Icing   ( 1569): Loaded CLD2 Version V2.0 - 20141016
,I/ActivityManager(  734): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=2741 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 1569): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,W/ResourcesManager( 2741): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 1787): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1787): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 1787): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/CalendarProvider2( 2741): Created com.android.providers.calendar.CalendarAlarmManager@3421580f(com.android.providers.calendar.CalendarProvider2@5a1409c)
,W/System  ( 1787): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 1787): Installed default security provider GmsCore_OpenSSL
,E/SQLiteLog( 2741): (284) automatic index on view_events(_id)
,E/PhoneInterfaceManager( 1211): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/Babel   ( 1787): connection state changed from UNKNOWN to DISCONNECTED
,I/CalendarProvider2( 2741): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 2741): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/GAV2    ( 2420): Thread[GAThread,5,main]: No campaign data found.
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  734): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  734): Message: 2
,D/WifiService(  734): New client listening to asynchronous messages
,D/WifiService(  734): setWifiEnabled: false pid=2384, uid=10277
E/WifiService(  734): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 2384): ****TEST TOOK:  5024  ms ****
I/jxcore-log( 2384): 
I/jxcore-log( 2384): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2384): 
,D/AndroidRuntime( 2782): 
D/AndroidRuntime( 2782): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 2782): CheckJNI is OFF
,I/ActivityManager(  734): Killing 2122:com.google.android.keep/u0a71 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10071/pid_2122/cgroup.procs: No such file or directory
,D/AndroidRuntime( 2782): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  734): Force stopping com.example.hello appid=10277 user=-1: uninstall pkg
I/ActivityManager(  734): Killing 2384:com.example.hello/u0a277 (adj 0): stop com.example.hello
,D/WifiService(  734): Client connection lost with reason: 4
I/WindowState(  734): WIN DEATH: Window{34110c16 u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings(  734): Skipping PackageSetting{49226ed com.test.thalitest/10270} due to missing metadata
,W/ActivityManager(  734): Force removing ActivityRecord{2e6654db u0 com.example.hello/.MainActivity t214}: app died, no saved state
,W/ActivityManager(  734): Spurious death for ProcessRecord{1ea907f5 2384:com.example.hello/u0a277}, curProc for 2384: null
I/ActivityManager(  734): Force stopping com.example.hello appid=10277 user=0: pkg removed
,I/Keyboard.Facilitator( 1074): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1304): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  734): Reconfiguring input devices.  changes=0x00000010
,D/VoicemailCleanupService( 1364): Cleaning up data for package: com.example.hello
I/Keyboard.Facilitator.DecoderInitializer( 1074): run()
,I/art     ( 1386): Explicit concurrent mark sweep GC freed 27595(1966KB) AllocSpace objects, 20(2MB) LOS objects, 24% free, 19MB/25MB, paused 19.033ms total 97.823ms
,I/Decoder ( 1074): createOrResetDecoder
,I/UpdateIcingCorporaServi( 1386): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/ConfigService( 1330): onCreate
,W/Launcher( 1264): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1c003aa5 new=com.google.android.velvet.VelvetApplication@1c003aa5
D/BackupManagerService(  734): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  734): Receieved: android.intent.action.PACKAGE_REMOVED
,I/MicrophoneInputStream( 1386): mic_starting gfk@3459ce9d
I/HotwordRecognitionRnr( 1386): Starting hotword detection.
,I/ActivityManager(  734): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2824 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/TaskPersister(  734): removeObsoleteFile: deleting file=214_task.xml
,I/art     (  734): Explicit concurrent mark sweep GC freed 15107(957KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.695ms total 104.642ms
,I/AudioFlinger(  185): AudioFlinger's thread 0xb47b9000 ready to run
,D/AndroidRuntime( 2782): Shutting down VM
,I/MicrophoneInputStream( 1386): mic_started gfk@3459ce9d
,D/audio_hw_primary(  185): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  185): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
,D/        (  185): Failed to fetch the lookup information of the device 0000003E 
E/ACDB-LOADER(  185): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  185): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  185): enable_audio_route: apply and update mixer path: audio-record
,W/ResourcesManager( 1264): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1074): run()
,I/UpdateIcingCorporaServi( 1386): UpdateCorporaTask done [took 156 ms] updated apps [took 156 ms] 
,W/ResourcesManager( 1264): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ContextImpl( 2824): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/Keyboard.Facilitator.MainLanguageModelLoader( 1074): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1074): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1074): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1074): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1074): run() : Loading LM = history
,D/ChimeraCfgMgr( 1569): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1569): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1569): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1569): Clearing selected account for com.example.hello
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1074): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1074): run() : Loading LM = user
,D/ChimeraCfgMgr( 1569): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1569): Module APK com.google.android.play.games already loaded
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1074): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1074): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1074): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1074): run()
,I/StatsUtilsManager( 1074): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1074): shouldRecordStats() = Too Soon
,I/LocationSettingsChecker( 1569): Removing dialog suppression flag for package com.example.hello
,E/NetworkScheduler.SchedulerReceiver( 1330): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1330): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1569): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1569): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1569): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1569): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/HotwordWorker( 1386): onReady
D/gH_CompatibleDatabase( 1569): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1569): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1569): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1569): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1569): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1569): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1569): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1569): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1569): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/BaseAppContext( 1569): Using Auth Proxy for data requests.
,W/BaseAppContext( 1569): Using Auth Proxy for data requests.
,I/ActivityManager(  734): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=2866 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/ActivityManager(  734): Killing 2159:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,I/GMPM-SVC( 1569): App measurement is starting up
,I/art     ( 1569): Explicit concurrent mark sweep GC freed 37235(2MB) AllocSpace objects, 27(432KB) LOS objects, 40% free, 21MB/36MB, paused 900us total 47.939ms
,I/PeopleContactsSync( 1569): CP2 sync disabled
,I/Icing   ( 1569): doRemovePackageData com.example.hello
,W/libprocessgroup(  734): failed to open /acct/uid_1000/pid_2159/cgroup.procs: No such file or directory
,D/ConnectivityService(  734): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/FileUtils( 1569): Failed to chmod(/data/data/com.google.android.gms/databases/google_app_measurement.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/SQLiteLog( 1569): (3850) statement aborts at 22: [DELETE FROM events WHERE app_id=?] disk I/O error
,E/GMPM-SVC( 1569): Error deleting application data. appId, error: com.example.hello, android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.d.d(SourceFile:911)
,W/OpenGLRenderer( 1264): Incorrectly called buildLayer on View: adg, destroying layer...
W/OpenGLRenderer( 1264): Incorrectly called buildLayer on View: adg, destroying layer...
,E/SharedPreferencesImpl( 1569): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,E/SQLiteDatabase( 2866): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 2866): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2866): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2866): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 2866): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 2866): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2866): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2866): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2866): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 2866): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 2866): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 2866): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 2866): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2866): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2866): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2866): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 2866): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 2866): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:367)
E/SQLiteDatabase( 2866): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 2866): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 2866): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/SQLiteDatabase( 2866): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/SQLiteDatabase( 2866): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/SQLiteDatabase( 2866): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2866): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 2866): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/SQLiteDatabase( 2866): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 2866): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 2866): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/SQLiteDatabase( 2866): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
D/AndroidRuntime( 2866): Shutting down VM
,--------- beginning of crash
E/AndroidRuntime( 2866): FATAL EXCEPTION: main
E/AndroidRuntime( 2866): Process: com.android.documentsui, PID: 2866
E/AndroidRuntime( 2866): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2866): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
E/AndroidRuntime( 2866): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 2866): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/AndroidRuntime( 2866): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2866): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2866): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/AndroidRuntime( 2866): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 2866): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 2866): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/AndroidRuntime( 2866): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/AndroidRuntime( 2866): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2866): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 2866): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 2866): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 2866): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 2866): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 2866): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 2866): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 2866): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 2866): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 2866): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/AndroidRuntime( 2866): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 2866): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 2866): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 2866): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 2866): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 2866): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:367)
E/AndroidRuntime( 2866): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 2866): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 2866): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/AndroidRuntime( 2866): 	... 9 more
,I/ActivityManager(  734): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=2891 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  734): Killing 2252:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10080/pid_2252/cgroup.procs: No such file or directory
,I/ActivityManager(  734): Killing 2365:com.google.android.deskclock/u0a38 (adj 15): empty #17
,D/OpenGLRenderer(  734): Render dirty regions requested: true
,D/Atlas   (  734): Validating map...
,W/DriveInitializer( 1569): Awaiting to be initialized
W/DriveInitializer( 1569): Background init thread started
,E/qdhwcomposer(  171): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  171): hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
,E/qdoverlay(  171): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  171): MdpData failed to play
E/qdoverlay(  171): == Dump MdpData start ==
E/qdoverlay(  171): == Dump OvFD fd=30 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  171): mOvData msmfb_overlay_data id=64
E/qdoverlay(  171): data msmfb_data offset=0 memid=39 id=0 flags=0x0 priv=0
E/qdoverlay(  171): == Dump MdpData end ==
E/qdhwcomposer(  171): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  171): hwc_set_primary: MDPComp draw failed
E/qdhwcomposer(  171): display_commit: MSMFB_DISPLAY_COMMIT for primary failed
E/qdhwcomposer(  171): hwc_set_primary: display commit fail!
,I/Adreno-EGL(  734): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  734): Initialized EGL, version 1.4
,D/OpenGLRenderer(  734): Enabling debug mode 0
,E/qdoverlay(  171): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  171): MdpCtrl failed to setOverlay, restoring last known good ov info
,E/qdoverlay(  171): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  171): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  171): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  171): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  171): == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  171): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  171): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  171): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  171): Ctrl commit failed set overlay
E/qdhwcomposer(  171): configureLowRes: commit failed for low res panel
E/qdoverlay(  171): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  171): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  171): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  171): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  171): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  171): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  171): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  171): src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
E/qdoverlay(  171): src_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  171): dst_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  171): Ctrl commit failed set overlay
E/qdhwcomposer(  171): configure: commit fails
E/qdoverlay(  171): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  171): MdpCtrl close error in unset

```
