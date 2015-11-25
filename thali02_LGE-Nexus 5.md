#### Test 503880194bce128_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GCoreUlr( 1273): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
W/Kids    ( 1560): [AbstractKidsOperation] Invalid device state 3
I/Kids    ( 1560): [KidAccountFixer] No network connection
V/GmsCoreStatsServiceLauncher( 1560): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
W/GCoreFlp( 1273): No location to return for getLastLocation()
W/FusedLocationProvider( 1560): location=null
I/AuthZen ( 1560): Fetching signing key...
D/PersistentNotificationBroadcastReceiver( 1366): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
I/AuthZen ( 1560): Signing key fetched successfully!
--------- beginning of system
I/ActivityManager(  759): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2249 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/BaseAppContext( 1560): Using Auth Proxy for data requests.
I/art     ( 1560): Explicit concurrent mark sweep GC freed 27841(2MB) AllocSpace objects, 32(512KB) LOS objects, 39% free, 19MB/32MB, paused 775us total 54.197ms
I/SystemUpdateService( 1560): showing system update notification
D/a       ( 1560): Opening database auth.proximity.permit_store...
D/AuthZenTransactionCache( 1560): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1560): Clearing transaction cache
I/ValidateNoPeople(  759): skipping global notification
V/SystemUpdateService( 1560): retry (wakeup: false) in 3599757 ms
D/SystemUpdateService( 1560): onDestroy
W/ResourcesManager(  899): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  899): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/GCoreUlr( 1273): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1273): Unbound from all location providers
I/GCoreUlr( 1273): DispatchingService.onDestroy()
I/GCoreUlr( 1273): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1273): Unbound from all location providers
W/ResourcesManager( 2249): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2249): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 2249): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 2249): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2249): Installed default security provider GmsCore_OpenSSL
E/YouTube MDX( 2249): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
I/dex2oat ( 2287): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads178033921.jar --oat-fd=21 --oat-location=/data/data/com.google.android.youtube/cache/ads178033921.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 2287): dex2oat took 31.810ms (threads: 4)
W/InstanceID/Rpc( 2249): Found 10008
V/Babel   ( 1800): babel boot account: thalitester@gmail.com
I/ActivityManager(  759): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2351 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
E/SQLiteLog( 1800): (284) automatic index on conversation_participants_view(conversation_id)
W/VideoCapabilities( 1800): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 1800): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 1800): Unrecognized profile 2130706433 for video/avc
E/SQLiteLog( 1800): (284) automatic index on conversation_participants_view(conversation_id)
E/SQLiteLog( 1800): (284) automatic index on conversation_participants_view(conversation_id)
,I/GAv4    ( 2351): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2351):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2351):   adb logcat -s GAv4
I/art     (  759): Explicit concurrent mark sweep GC freed 17488(849KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/40MB, paused 840us total 53.161ms
W/GAv4    ( 2351): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2351): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2351): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  759): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2376 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  759): Killing 1625:com.android.settings/1000 (adj 15): empty #17
D/WifiService(  759): Client connection lost with reason: 4
D/AndroidRuntime( 2372): 
D/AndroidRuntime( 2372): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2372): CheckJNI is OFF
W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_1625/cgroup.procs: No such file or directory
D/AndroidRuntime( 2372): Calling main entry com.android.commands.am.Am
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 2372): Shutting down VM
I/ActivityManager(  759): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2408 uid=10277 gids={50277, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/MicrophoneInputStream( 1352): mic_close gfk@1b77ddc7
I/art     ( 1366): Explicit concurrent mark sweep GC freed 7323(415KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 19MB/32MB, paused 557us total 26.774ms
D/audio_hw_primary(  184): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  184): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1352): Hotword detection finished
I/HotwordRecognitionRnr( 1352): Stopping hotword detection.
I/WebViewFactory( 2408): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2408): Time to load native libraries: 2 ms (timestamps 6219-6221)
I/LibraryLoader( 2408): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2408): Binding Chromium to main looper Looper (main, tid 1) {98e5d5f}
I/LibraryLoader( 2408): Expected native library version number "",actual native library version number ""
I/chromium( 2408): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2408): Initializing chromium process, singleProcess=true
W/art     ( 2408): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2408): ApplicationContext is null in ApplicationStatus
I/Gmail   ( 2376): getAccountsCursor
D/ActivityThread( 2376): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
W/chromium( 2408): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/chromium( 2408): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2408): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2408): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2408): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3db28cd:true
,D/BluetoothAdapter( 2408): 811991766: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2408): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2408): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2408): CordovaWebView is running on device made by: LGE
,W/art     ( 2408): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2408): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2408): Render dirty regions requested: true
,D/Atlas   ( 2408): Validating map...
,W/chromium( 2408): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2408): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2408): Enabling debug mode 0
,I/Keyboard.Facilitator( 1071): onFinishInput()
,W/BindingManager( 2408): Cannot call determinedVisibility() - never saw a connection for the pid: 2408
,I/chromium( 2408): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/ActivityManager(  759): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=2470 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/JsMessageQueue( 2408): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 2408): Unable to open asset URL: file:///android_asset/www/jxcore.js
,W/GAV2    ( 2376): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/SurfaceFlinger(  176): shader cache generated - 24 shaders in 178.537766 ms
,I/ActivityManager(  759): Displayed com.example.hello/.MainActivity: +593ms (total +13s801ms)
,D/jxcore_app_log( 2408): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258381056
D/JX-Cordova( 2408): jxcore cordova android initializing
,I/Gmail   ( 2376): getAccountsCursor
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemBroadcastReceiver( 1071): Boot has been completed
,I/SystemBroadcastReceiver( 1071): toggleAppIcon() : FLAG_SYSTEM = true
,W/ActivityManager(  759): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/jxcore-log( 2408): Initializing JXcore engine
,W/jxcore-log( 2408): JXcore engine is ready
I/Exchange( 2470): EasService.onCreate
,W/jxcore-log( 2408): Starting JXcore engine
,I/ActivityManager(  759): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2504 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  195): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 175us total 9.021ms
,W/m.example.hello( 2408): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7840]" dev="sockfs" ino=7840 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 2408): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/m.example.hello( 2408): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8539]" dev="sockfs" ino=8539 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 2408): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[15814]" dev="sockfs" ino=15814 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 195us total 9.124ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 7.559ms
,I/Exchange( 2470): RestartPingTask
I/Gmail   ( 2376): Observing account changes for notifications
,E/SQLiteLog( 2376): (283) recovered 75 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Exchange( 2470): RestartPingsTask did not start any pings.
I/Exchange( 2470): PSS stopIfIdle
I/Exchange( 2470): PSS has no active accounts; stopping service.
,W/jxcore-log( 2408): Platform android
W/jxcore-log( 2408): 
,W/jxcore-log( 2408): Process ARCH arm
W/jxcore-log( 2408): 
,E/a       ( 2376): RuntimeException when trying to unbind from service
E/a       ( 2376): java.lang.IllegalArgumentException: Service not registered: com.android.emailcommon.service.am@25fb040e
E/a       ( 2376): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1024)
E/a       ( 2376): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1802)
E/a       ( 2376): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/a       ( 2376): 	at com.android.emailcommon.service.an.a(SourceFile:124)
E/a       ( 2376): 	at com.android.emailcommon.service.an.doInBackground(SourceFile:111)
E/a       ( 2376): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/a       ( 2376): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/a       ( 2376): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/a       ( 2376): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/a       ( 2376): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/a       ( 2376): 	at java.lang.Thread.run(Thread.java:818)
,E/ActivityThread( 2376): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@25fb040e that was originally bound here
E/ActivityThread( 2376): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@25fb040e that was originally bound here
E/ActivityThread( 2376): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2376): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2376): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2376): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2376): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2376): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 2376): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 2376): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 2376): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 2376): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 2376): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 2376): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 2376): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 2376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2376): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2376): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/jxcore-log( 2408): JXcore Cordova bridge is ready!
I/jxcore-log( 2408): 
,W/jxcore-log( 2408): JXcore engine is started
,E/jxcore-log( 2408): >> LGE-Nexus 5
E/jxcore-log( 2408): 
I/jxcore-log( 2408): Total memory 1946181632
I/jxcore-log( 2408): 
,I/jxcore-log( 2408): Free memory 406728704
I/jxcore-log( 2408): 
,I/jxcore-log( 2408): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2408): 
I/jxcore-log( 2408): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2408): 
,I/jxcore-log( 2408): userPath [ 'www' ]
I/jxcore-log( 2408): 
,I/jxcore-log( 2408): Size 1080 1776
I/jxcore-log( 2408): 
,I/jxcore-log( 2408): Screen Brightness 82
I/jxcore-log( 2408): 
,E/jxcore-log( 2408): Dummy Error Log.
E/jxcore-log( 2408): 
,D/Finsky  ( 2504): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Gmail   ( 2376): notifyAccountChanged
,I/jxcore-log( 2408): getBuffer is called!!!!
I/jxcore-log( 2408): 
,I/ActivityManager(  759): Killing 1660:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
,I/Gmail   ( 2376): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 2376): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/Finsky  ( 2504): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/Gmail   ( 2376): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 2376): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/Settings( 2504): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 2504): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/libprocessgroup(  759): failed to open /acct/uid_10061/pid_1660/cgroup.procs: No such file or directory
,D/Volley  ( 2504): [226] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 2504): [233] DiskBasedCache.clear: Cache cleared.
,I/ActivityManager(  759): Killing 1201:com.android.printspooler/u0a72 (adj 15): empty #17
,D/Ads     ( 2504): Skipping gmscore version check
,W/libprocessgroup(  759): failed to open /acct/uid_10072/pid_1201/cgroup.procs: No such file or directory
,V/UserPresentBroadcastReceiver( 1273): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/Finsky  ( 2504): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 2504): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 2504): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  759): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=2570 uid=10003 gids={50003, 9997} abi=armeabi-v7a
,D/Finsky  ( 2504): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/CellBroadcastReceiver( 2570): onReceive Intent { act=android.intent.action.SERVICE_STATE flg=0x10 cmp=com.android.cellbroadcastreceiver/.CellBroadcastReceiver (has extras) }
,D/CellBroadcastReceiver( 2570): Intent ACTION_SERVICE_STATE_CHANGED
,D/CellBroadcastReceiver( 2570): Service state changed! 3 Full: 3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=false Current state=-1
I/ActivityManager(  759): Killing 1865:com.android.keychain/1000 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_1865/cgroup.procs: No such file or directory
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 2376): getAccountsCursor
,I/Gmail   ( 2376): getAccountsCursor
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SIP     ( 1179): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,I/ActivityManager(  759): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2593 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  759): Explicit concurrent mark sweep GC freed 9744(495KB) AllocSpace objects, 2(36KB) LOS objects, 33% free, 27MB/40MB, paused 922us total 76.884ms
,I/MusicStore( 2593): Database version: 120
,W/ContextImpl( 2051): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAv4-SVC( 1560): Google Analytics 8.3.01 is starting up.
,I/GAV2    ( 2051): Thread[GAThread,5,main]: No campaign data found.
,W/ResourcesManager( 2593): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2593): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2593): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 2593): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 2593): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2d1a12a5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2593): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 2593): GMSCore installation verified
,I/ConfigStore( 2593): Config Database version: 1
,I/MediaRouter( 2593): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=11, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/GHttpClientFactory( 2593): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2593): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  759): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2640 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1352): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/PackageBroadcastService( 1560): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
D/ChimeraCfgMgr( 1560): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1560): Loading module APK com.google.android.play.games
,I/ActivityManager(  759): Killing 1878:com.google.android.dialer/u0a10 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10010/pid_1878/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 1560): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1560): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1560): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1560): Submit a task: h
,D/ChimeraCfgMgr( 1560): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1560): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/h       ( 1560): Processing package: com.example.hello
,D/GassUtils( 1560): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
,D/h       ( 1560): Found info for package com.example.hello in db.
,I/ActivityManager(  759): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2675 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/PeopleContactsSync( 1560): CP2 sync disabled
,W/BaseAppContext( 1560): Using Auth Proxy for data requests.
W/BaseAppContext( 1560): Using Auth Proxy for data requests.
,W/BaseAppContext( 1560): Using Auth Proxy for data requests.
,W/BaseAppContext( 1560): Using Auth Proxy for data requests.
,W/BaseAppContext( 1560): Using Auth Proxy for data requests.
,I/MediaStoreImporter( 2593): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  759): Killing 1998:com.google.android.onetimeinitializer/u0a12 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10012/pid_1998/cgroup.procs: No such file or directory
,W/BaseAppContext( 1560): Using Auth Proxy for data requests.
,I/UpdateIcingCorporaServi( 1352): UpdateCorporaTask done [took 618 ms] updated apps [took 618 ms] 
,D/ChimeraCfgMgr( 1560): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1560): Module APK com.google.android.play.games already loaded
,I/GAv4    ( 2675): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2675):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2675):   adb logcat -s GAv4
,W/GAv4    ( 2675): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2675): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2675): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 2675): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,W/ResourcesManager( 2675): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2675): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  759): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2727 uid=10067 gids={50067, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  759): Killing 2023:com.android.managedprovisioning/u0a14 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10014/pid_2023/cgroup.procs: No such file or directory
,W/ResourcesManager( 2727): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 2675): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 2675): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2675): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2504): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
,I/art     ( 1366): Explicit concurrent mark sweep GC freed 6740(339KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 19MB/32MB, paused 870us total 21.981ms
,I/ActivityManager(  759): Killing 1970:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10002/pid_1970/cgroup.procs: No such file or directory
,W/GCoreFlp( 1273): No location to return for getLastLocation()
,W/FusedLocationProvider( 1366): location=null
,D/ChimeraCfgMgr( 1560): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1560): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1560): [KidAccountFixer] No network connection
,D/GCM     ( 1366): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  759): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=2774 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 1560): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
,I/art     (  759): Explicit concurrent mark sweep GC freed 10045(504KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/40MB, paused 1.728ms total 46.231ms
,W/ResourcesManager( 2774): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 1800): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 1800): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Icing   ( 1560): Loaded CLD2 Version V2.0 - 20141016
,V/JNIHelp ( 1800): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/CalendarProvider2( 2774): Created com.android.providers.calendar.CalendarAlarmManager@3cffb1fe(com.android.providers.calendar.CalendarProvider2@98e5d5f)
,E/SQLiteLog( 2774): (284) automatic index on view_events(_id)
,I/Icing   ( 1560): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,W/System  ( 1800): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 1800): Installed default security provider GmsCore_OpenSSL
,I/CalendarProvider2( 2774): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 2774): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/GAV2    ( 2376): Thread[GAThread,5,main]: No campaign data found.
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  759): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  759): Message: 2
,D/WifiService(  759): New client listening to asynchronous messages
,D/WifiService(  759): setWifiEnabled: false pid=2408, uid=10277
E/WifiService(  759): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 2408): ****TEST TOOK:  5048  ms ****
I/jxcore-log( 2408): 
,I/jxcore-log( 2408): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2408): 
,D/AndroidRuntime( 2809): 
D/AndroidRuntime( 2809): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 2809): CheckJNI is OFF
,D/AndroidRuntime( 2809): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  759): Force stopping com.example.hello appid=10277 user=-1: uninstall pkg
I/ActivityManager(  759): Killing 2408:com.example.hello/u0a277 (adj 0): stop com.example.hello
,I/WindowState(  759): WIN DEATH: Window{3a54df3d u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  759): Client connection lost with reason: 4
,W/PackageSettings(  759): Skipping PackageSetting{ee92214 com.test.thalitest/10270} due to missing metadata
,W/ActivityManager(  759): Force removing ActivityRecord{2384ff7a u0 com.example.hello/.MainActivity t214}: app died, no saved state
,W/ActivityManager(  759): Spurious death for ProcessRecord{26acc310 2408:com.example.hello/u0a277}, curProc for 2408: null
,I/ActivityManager(  759): Force stopping com.example.hello appid=10277 user=0: pkg removed
,W/GeofencerStateMachine( 1273): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1071): resetDictionaries() : en_US
,I/InputReader(  759): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1071): run()
,I/Decoder ( 1071): createOrResetDecoder
,I/ConfigService( 1366): onCreate
,I/art     ( 1352): Explicit concurrent mark sweep GC freed 23561(1654KB) AllocSpace objects, 15(3MB) LOS objects, 40% free, 18MB/31MB, paused 793us total 115.758ms
,I/UpdateIcingCorporaServi( 1352): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/VoicemailCleanupService( 1299): Cleaning up data for package: com.example.hello
,D/BackupManagerService(  759): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  759): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  759): removeObsoleteFile: deleting file=214_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1071): run()
,W/InputMethodManagerService(  759): Got RemoteException sending setActive(false) notification to pid 2408 uid 10277
,I/Keyboard.Facilitator( 1071): onFinishInput()
,W/Launcher( 1231): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@88ae3ac new=com.google.android.velvet.VelvetApplication@88ae3ac
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1071): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1071): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1071): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1071): run()
I/StatsUtilsManager( 1071): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1071): shouldRecordStats() = Too Soon
,I/ActivityManager(  759): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2851 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/art     (  759): Explicit concurrent mark sweep GC freed 12194(843KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.210ms total 200.348ms
,I/MicrophoneInputStream( 1352): mic_starting gfk@dec844a
,I/HotwordRecognitionRnr( 1352): Starting hotword detection.
,I/AudioFlinger(  184): AudioFlinger's thread 0xb2f3e000 ready to run
,I/MicrophoneInputStream( 1352): mic_started gfk@dec844a
,D/audio_hw_primary(  184): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  184): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
D/        (  184): Failed to fetch the lookup information of the device 0000003E 
E/ACDB-LOADER(  184): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  184): enable_snd_device: snd_device(55: voice-rec-mic)
,I/UpdateIcingCorporaServi( 1352): UpdateCorporaTask done [took 119 ms] updated apps [took 119 ms] 
,D/audio_hw_primary(  184): enable_audio_route: apply and update mixer path: audio-record
,W/ContextImpl( 2851): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/AndroidRuntime( 2809): Shutting down VM
,D/PackageBroadcastService( 1560): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1560): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1560): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1560): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1560): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1560): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1560): Removing dialog suppression flag for package com.example.hello
,E/NetworkScheduler.SchedulerReceiver( 1366): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1366): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/ResourcesManager( 1231): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1560): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1560): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1560): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1560): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/ResourcesManager( 1231): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/gH_CompatibleDatabase( 1560): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1560): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1560): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/HotwordWorker( 1352): onReady
,D/gH_CompatibleDatabase( 1560): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1560): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1560): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1560): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1560): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1560): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/BaseAppContext( 1560): Using Auth Proxy for data requests.
,I/ActivityManager(  759): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=2888 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/ActivityManager(  759): Killing 2084:com.google.android.configupdater/u0a36 (adj 15): empty #17
,I/GMPM-SVC( 1560): App measurement is starting up
,W/BaseAppContext( 1560): Using Auth Proxy for data requests.
,W/libprocessgroup(  759): failed to open /acct/uid_10036/pid_2084/cgroup.procs: No such file or directory
,I/PeopleContactsSync( 1560): CP2 sync disabled
,I/Icing   ( 1560): doRemovePackageData com.example.hello
,I/ActivityManager(  759): Killing 2124:com.google.android.keep/u0a71 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10071/pid_2124/cgroup.procs: No such file or directory
,I/ActivityManager(  759): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=2913 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,W/OpenGLRenderer( 1231): Incorrectly called buildLayer on View: adg, destroying layer...
W/OpenGLRenderer( 1231): Incorrectly called buildLayer on View: adg, destroying layer...
,I/art     ( 1560): Explicit concurrent mark sweep GC freed 37971(2MB) AllocSpace objects, 23(368KB) LOS objects, 39% free, 21MB/36MB, paused 852us total 53.672ms
,D/ConnectivityService(  759): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ActivityManager(  759): Killing 2148:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_2148/cgroup.procs: No such file or directory
,I/ActivityManager(  759): Killing 2249:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10080/pid_2249/cgroup.procs: No such file or directory
,D/ExternalStorage( 2913): After updating volumes, found 1 active roots
,W/DriveInitializer( 1560): Awaiting to be initialized
,W/DriveInitializer( 1560): Background init thread started
,E/SQLiteLog( 1560): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock154] disk I/O error
,E/DocListDatabase( 1560): Failed to delete from ContentFileDeletionLock154 table
E/DocListDatabase( 1560): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1560): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1560): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1560): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1560): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1560): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1560): 	at com.google.android.gms.drive.database.k.a(SourceFile:329)
E/DocListDatabase( 1560): 	at com.google.android.gms.drive.database.f.h(SourceFile:1062)
E/DocListDatabase( 1560): 	at com.google.android.gms.drive.s.run(SourceFile:62)
W/DriveInitializer( 1560): Background init thread ended
E/SQLiteLog( 1560): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 1560): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1560): Process: com.google.android.gms, PID: 1560
E/AndroidRuntime( 1560): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1560): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1560): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1560): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1560): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1560): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1560): 	at com.google.android.gms.drive.database.k.a(SourceFile:329)
E/AndroidRuntime( 1560): 	at com.google.android.gms.drive.database.f.h(SourceFile:1062)
E/AndroidRuntime( 1560): 	at com.google.android.gms.drive.s.run(SourceFile:62)
E/DriveAsyncService( 1560): disk I/O error (code 3850)
E/DriveAsyncService( 1560): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1560): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1560): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1560): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1560): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298),
E/DriveAsyncService( 1560): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1560): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1560): 	at com.google.android.gms.drive.database.k.k(SourceFile:485)
E/DriveAsyncService( 1560): 	at com.google.android.gms.drive.database.k.b(SourceFile:460)
E/DriveAsyncService( 1560): 	at com.google.android.gms.drive.database.f.i(SourceFile:1516)
E/DriveAsyncService( 1560): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1560): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/DriveAsyncService( 1560): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1560): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1560): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1560): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager(  759): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  759): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/OpenGLRenderer(  759): Render dirty regions requested: true
D/Atlas   (  759): Validating map...
,E/qdhwcomposer(  176): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  176): hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
E/qdoverlay(  176): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  176): MdpData failed to play
E/qdoverlay(  176): == Dump MdpData start ==
E/qdoverlay(  176): == Dump OvFD fd=29 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  176): mOvData msmfb_overlay_data id=64
E/qdoverlay(  176): data msmfb_data offset=0 memid=34 id=0 flags=0x0 priv=0
E/qdoverlay(  176): == Dump MdpData end ==
E/qdhwcomposer(  176): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  176): hwc_set_primary: MDPComp draw failed
E/qdhwcomposer(  176): display_commit: MSMFB_DISPLAY_COMMIT for primary failed
E/qdhwcomposer(  176): hwc_set_primary: display commit fail!
,I/Adreno-EGL(  759): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  759): Initialized EGL, version 1.4
,D/OpenGLRenderer(  759): Enabling debug mode 0
,E/qdoverlay(  176): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  176): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  176): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  176): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  176): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  176): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  176): == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  176): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  176): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  176): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  176): Ctrl commit failed set overlay
E/qdhwcomposer(  176): configureLowRes: commit failed for low res panel
E/qdoverlay(  176): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  176): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  176): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  176): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  176): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  176): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  176): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  176): src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
E/qdoverlay(  176): src_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  176): dst_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  176): Ctrl commit failed set overlay
E/qdhwcomposer(  176): configure: commit fails
E/qdoverlay(  176): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  176): MdpCtrl close error in unset
,I/iu.UploadsManager( 1560): End new media; added: 0, uploading: 0, time: 20 ms

```
