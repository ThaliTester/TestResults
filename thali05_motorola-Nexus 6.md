#### Test 50388019385b4d9_thali05_motorola-Nexus 6 Logs


```
--------- beginning of system
I/ActivityManager(  822): Killing 2454:com.android.managedprovisioning/u0a17 (adj 15): empty #17
,--------- beginning of main
V/Finsky  ( 2909): [1] GearheadStateMonitor.onReady: sIsProjecting:false
I/Gmail   ( 2968): getAccountsCursor
D/ActivityThread( 2968): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3001): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3001): CheckJNI is OFF
I/ActivityManager(  822): Start proc 3017:com.google.android.gm.exchange/u0a77 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
D/AndroidRuntime( 3001): Calling main entry com.android.commands.am.Am
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{3b9098a2 token=Token{21b2946d ActivityRecord{ef14484 u0 com.example.hello/.MainActivity t26}}} to stack=1 task=26 at 0
V/WindowManager(  822): Adding window Window{1dee858f u0 Starting com.example.hello} at 2 of 7 (after Window{223f93ce u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1501): Closing mic
I/MicrophoneInputStream( 1501): mic_close com.google.android.apps.gsa.speech.audio.u@1ac7e3e5
D/AndroidRuntime( 3001): Shutting down VM
I/ActivityManager(  822): Start proc 3037:com.example.hello/u0a273 for activity com.example.hello/.MainActivity
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
E/ActivityThread( 1276): Performing stop of activity that is not resumed: {com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
E/ActivityThread( 1276): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
E/ActivityThread( 1276): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3344)
E/ActivityThread( 1276): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3425)
E/ActivityThread( 1276): 	at android.app.ActivityThread.access$1100(ActivityThread.java:151)
E/ActivityThread( 1276): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1332)
E/ActivityThread( 1276): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1276): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 1276): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/ActivityThread( 1276): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 1276): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 1276): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/ActivityThread( 1276): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1501): Stopping hotword detection.
I/HotwordRecognitionRnr( 1501): Hotword detection finished
I/WebViewFactory( 3037): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3037): Time to load native libraries: 1 ms (timestamps 3269-3270)
I/LibraryLoader( 3037): Expected native library version number "",actual native library version number ""
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1700316435
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/art     (  822): Explicit concurrent mark sweep GC freed 12596(628KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 32MB/48MB, paused 857us total 70.657ms
V/WebViewChromiumFactoryProvider( 3037): Binding Chromium to main looper Looper (main, tid 1) {311ffb94}
I/LibraryLoader( 3037): Expected native library version number "",actual native library version number ""
I/chromium( 3037): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/ActivityManager(  822): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/ActivityManager(  822): Activity reported stop, but no longer stopping: ActivityRecord{3bb979 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t25}
I/BrowserStartupController( 3037): Initializing chromium process, singleProcess=true
I/ActivityManager(  822): Killing 1565:com.google.android.partnersetup/u0a16 (adj 15): empty #17
W/art     ( 3037): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3037): ApplicationContext is null in ApplicationStatus
W/chromium( 3037): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
I/Gmail   ( 2968): Observing account changes for notifications
W/GAV2    ( 2968): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/chromium( 3037): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3037): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3037): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3037): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/SystemBroadcastReceiver( 1212): Boot has been completed
I/SystemBroadcastReceiver( 1212): toggleAppIcon() : FLAG_SYSTEM = true
I/Gmail   ( 2968): getAccountsCursor
V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ecff149:true
D/BluetoothAdapter( 3037): 354363705: getState() :  mService = null. Returning STATE_OFF
W/art     ( 3037): Attempt to remove local handle scope entry from IRT, ignoring
E/SQLiteLog( 2968): (283) recovered 43 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
W/AwContents( 3037): onDetachedFromWindow called when already detached. Ignoring
I/ActivityManager(  822): Start proc 3097:com.google.android.apps.messaging/u0a75 for broadcast com.google.android.apps.messaging/.receiver.BootAndPackageReplacedReceiver
V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SystemWebViewEngine( 3037): CordovaWebView is running on device made by: motorola
I/Exchange( 3017): EasService.onCreate
W/art     ( 3037): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3037): Attempt to remove local handle scope entry from IRT, ignoring
E/ActivityThread( 2968): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@3400bcd5 that was originally bound here
E/ActivityThread( 2968): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@3400bcd5 that was originally bound here
E/ActivityThread( 2968): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
E/ActivityThread( 2968): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
E/ActivityThread( 2968): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
E/ActivityThread( 2968): 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
E/ActivityThread( 2968): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
E/ActivityThread( 2968): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 2968): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 2968): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 2968): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 2968): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 2968): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 2968): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 2968): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 2968): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2968): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2968): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Exchange( 3017): RestartPingTask
E/a       ( 2968): RuntimeException when trying to unbind from service
E/a       ( 2968): java.lang.IllegalArgumentException: Service not registered: com.android.emailcommon.service.am@3400bcd5
E/a       ( 2968): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/a       ( 2968): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/a       ( 2968): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/a       ( 2968): 	at com.android.emailcommon.service.an.a(SourceFile:124)
E/a       ( 2968): 	at com.android.emailcommon.service.an.doInBackground(SourceFile:111)
E/a       ( 2968): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/a       ( 2968): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/a       ( 2968): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/a       ( 2968): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/a       ( 2968): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/a       ( 2968): 	at java.lang.Thread.run(Thread.java:818)
D/OpenGLRenderer( 3037): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3037): Validating map...
V/WindowManager(  822): Adding window Window{3a6d33d6 u0 com.example.hello/com.example.hello.MainActivity} at 2 of 8 (before Window{1dee858f u0 Starting com.example.hello})
W/chromium( 3037): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/Exchange( 3017): RestartPingsTask did not start any pings.
I/Exchange( 3017): PSS stopIfIdle
I/Exchange( 3017): PSS has no active accounts; stopping service.
I/Exchange( 3017): onDestroy
I/ActivityManager(  822): Killing 2475:com.android.settings/1000 (adj 15): empty #17
I/Gmail   ( 2968): notifyAccountChanged
I/Gmail   ( 2968): getAccountsCursor
I/Gmail   ( 2968): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/OpenGLRenderer( 3037): Initialized EGL, version 1.4
D/OpenGLRenderer( 3037): Enabling debug mode 0
I/Gmail   ( 2968): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 2968): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 2968): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Keyboard.Facilitator( 1212): onFinishInput()
W/BindingManager( 3037): Cannot call determinedVisibility() - never saw a connection for the pid: 3037
I/ActivityManager(  822): Displayed com.example.hello/.MainActivity: +488ms
V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/chromium( 3037): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/Gmail   ( 2968): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
D/JsMessageQueue( 3037): Set native->JS mode to OnlineEventsBridgeMode
I/Gmail   ( 2968): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
I/Gmail   ( 2968): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
I/ActivityManager(  822): Killing 2493:org.simalliance.openmobileapi.service/u0a23 (adj 15): empty #17
E/AndroidProtocolHandler( 3037): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/jxcore_app_log( 3037): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576455680
D/JX-Cordova( 3037): jxcore cordova android initializing
W/jxcore-log( 3037): Initializing JXcore engine
W/jxcore-log( 3037): JXcore engine is ready
W/jxcore-log( 3037): Starting JXcore engine
I/Gmail   ( 2968): getAccountsCursor
V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/m.example.hello( 3037): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10517]" dev="sockfs" ino=10517 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3037): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 3037): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[13378]" dev="sockfs" ino=13378 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3037): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20658]" dev="sockfs" ino=20658 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/art     ( 3097): Note: end time exceeds epoch: 
W/VideoCapabilities( 3097): Unrecognized profile 2130706433 for video/avc
W/jxcore-log( 3037): Platform android
W/jxcore-log( 3037): 
W/jxcore-log( 3037): Process ARCH arm
W/jxcore-log( 3037): 
I/VideoCapabilities( 3097): Unsupported profile 4 for video/mp4v-es
W/Bugle   ( 3097): PhoneUtils.getForLMR1(): invalid subId = -1
W/Bugle   ( 3097): PhoneUtils.getForLMR1(): invalid subId = -1
D/GCM     ( 1430): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1430): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 1732): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
W/Bugle   ( 3097): PhoneUtils.getForLMR1(): invalid subId = -1
W/ResourcesManager( 3097): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3097): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/jxcore-log( 3037): JXcore Cordova bridge is ready!
I/jxcore-log( 3037): 
W/jxcore-log( 3037): JXcore engine is started
I/ActivityManager(  822): Start proc 3139:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
W/ResourcesManager( 3139): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
E/jxcore-log( 3037): >> motorola-Nexus 6
E/jxcore-log( 3037): 
W/ResourcesManager( 3139): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/UserPresentBroadcastReceiver( 1703): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
I/jxcore-log( 3037): Total memory 3113791488
I/jxcore-log( 3037): 
I/jxcore-log( 3037): Free memory 1076994048
I/jxcore-log( 3037): 
I/jxcore-log( 3037): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3037): 
I/jxcore-log( 3037): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3037): 
I/jxcore-log( 3037): userPath [ 'www' ]
I/jxcore-log( 3037): 
I/jxcore-log( 3037): Size 1440 2392
I/jxcore-log( 3037): 
I/jxcore-log( 3037): Screen Brightness 82
I/jxcore-log( 3037): 
E/jxcore-log( 3037): Dummy Error Log.
E/jxcore-log( 3037): 
D/LocationInitializer( 1732): Restart initialization of location
I/Bugle   ( 3097): ApnsOta: OTA version -1
I/MultiDex( 3139): VM with version 2.1.0 has multidex support
I/MultiDex( 3139): install
I/MultiDex( 3139): VM has multidex support, MultiDex support library is disabled.
W/Bugle   ( 3097): PhoneUtils.getForLMR1(): invalid subId = -1
W/Bugle   ( 3097): PhoneUtils.getForLMR1(): invalid subId = -1
V/JNIHelp ( 3139): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ProviderInstaller( 3139): Installed default security provider GmsCore_OpenSSL
D/WearableService( 3139): callingUid 10011, callindPid: 3139
W/Bugle   ( 3097): PhoneUtils.getForLMR1(): invalid subId = -1
W/Bugle   ( 3097): PhoneUtils.getForLMR1(): invalid subId = -1
I/BugleDataModel( 3097): Fixup: Send failed - 0 Download failed - 0
I/ActivityManager(  822): Start proc 3172:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver
W/Bugle   ( 3097): PhoneUtils.getForLMR1(): invalid subId = -1
E/MDM     ( 1703): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/BugleUsageStatistics( 3097): PlayLogger.onLoggerConnected
W/Bugle   ( 3097): PhoneUtils.getForLMR1(): invalid subId = -1
W/Bugle   ( 3097): PhoneUtils.getForLMR1(): invalid subId = -1
W/Bugle   ( 3097): PhoneUtils.getSelfRawNumber: subInfo is null for -1
W/Bugle   ( 3097): PhoneUtils.getForLMR1(): invalid subId = -1
I/BugleDataModel( 3097): SyncMessagesAction: Starting batch for messages from 1450156519280 to 1450189310601 (message update limit = 80, message scan limit = 4000)
W/Bugle   ( 3097): PhoneUtils.getForLMR1(): invalid subId = -1
I/art     (  822): Explicit concurrent mark sweep GC freed 10806(514KB) AllocSpace objects, 1(14KB) LOS objects, 32% free, 32MB/48MB, paused 978us total 51.387ms
I/BugleDataModel( 3097): SyncMessagesAction: All messages now in sync
I/ActivityManager(  822): Killing 2380:com.android.providers.calendar/u0a3 (adj 15): empty #17
I/MusicStore( 3172): Database version: 120
I/jxcore-log( 3037): getBuffer is called!!!!
I/jxcore-log( 3037): 
W/ResourcesManager( 3172): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3172): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 3172): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ProviderInstaller( 3172): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3172): GMSCore installation verified
I/ConfigStore( 3172): Config Database version: 1
I/art     ( 1430): Explicit concurrent mark sweep GC freed 11156(534KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.063ms total 28.899ms
I/MediaRouter( 3172): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
I/GHttpClientFactory( 3172): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 3172): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  822): Start proc 3210:com.android.providers.calendar/u0a3 for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,W/ResourcesManager( 3210): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/iu.UploadsManager( 1732): End new media; added: 0, uploading: 0, time: 36 ms
,I/CalendarProvider2( 3210): Created com.android.providers.calendar.CalendarAlarmManager@1ffac3e7(com.android.providers.calendar.CalendarProvider2@311ffb94)
,E/SQLiteLog( 3210): (284) automatic index on view_events(_id)
,I/ActivityManager(  822): Waited long enough for: ServiceRecord{28930e37 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,D/GCM     ( 1430): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ChimeraCfgMgr( 1732): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1732): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1732): [KidAccountFixer] No network connection
,I/MediaStoreImporter( 3172): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  822): Killing 2558:com.google.android.configupdater/u0a42 (adj 15): empty #17
,D/GCM     ( 1430): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1430): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1732): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1703): [125] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ConfigService( 1430): onDestroy
,D/LocationInitializer( 1732): Restart initialization of location
,D/GCM     ( 1430): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1430): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1732): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1703): [128] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1732): Restart initialization of location
,I/NotifUtils( 2968): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,I/ActivityManager(  822): Delay finish: com.google.android.gm/.widget.GmailWidgetProvider
,I/ActivityManager(  822): Resuming delayed broadcast
,I/NotifUtils( 2968): validateNotifications - cancelling 1729800001 for 61035162 / -317575340
,W/ResourcesManager( 2827): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2827): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2827): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 2827): Installed default security provider GmsCore_OpenSSL
,I/Babel_telephony( 2827): TeleIncomingWifiCallController.getRegistrationState, wifi calling not enabled
,W/VideoCapabilities( 2827): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2827): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2827): Unrecognized profile 2130706433 for video/avc
,I/Babel   ( 2827): connection state changed from UNKNOWN to DISCONNECTED
,I/CalendarProvider2( 3210): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3210): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAV2    ( 2968): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PackageBroadcastService( 1732): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1732): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1732): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 1501): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1276): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@48248df new=com.google.android.velvet.VelvetApplication@48248df
,D/Finsky  ( 2909): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2909): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2909): [1] 5.onFinished: Scheduling replication attempt 1.
,I/UpdateIcingCorporaServi( 1501): UpdateCorporaTask done [took 34 ms] updated apps [took 34 ms] 
,D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  822): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  822): Start proc 3274:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/BackupManagerService(  822): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/ResourcesManager( 3274): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/BackupManagerService(  822): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  822): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@30267c7b
,I/Launcher( 1276): Deferring update until onResume
,I/art     (  822): Explicit concurrent mark sweep GC freed 21087(1072KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 2.048ms total 52.577ms
,I/art     ( 1703): Explicit concurrent mark sweep GC freed 13887(796KB) AllocSpace objects, 5(80KB) LOS objects, 37% free, 26MB/42MB, paused 1.100ms total 26.183ms
,E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2cc24e11)
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  822): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  822): Message: 2
,V/GmsNetworkLocationProvi( 1703): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
D/WifiService(  822): New client listening to asynchronous messages
D/WifiService(  822): setWifiEnabled: false pid=3037, uid=10273
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3037): ****TEST TOOK:  5041  ms ****
I/jxcore-log( 3037): 
I/jxcore-log( 3037): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3037): 
,V/GmsNetworkLocationProvi( 1703): DISABLE
,V/GmsNetworkLocationProvi( 1703): ENABLE
,V/GmsNetworkLocationProvi( 1703): SET-REQUEST
V/GmsNetworkLocationProvi( 1703): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,I/ActivityManager(  822): Killing 2592:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,D/AndroidRuntime( 3299): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3299): CheckJNI is OFF
,D/AndroidRuntime( 3299): Calling main entry com.android.commands.pm.Pm
,W/PackageSettings(  822): Skipping PackageSetting{2898e713 com.test.thalitest/10265} due to missing metadata
,I/ActivityManager(  822): Force stopping com.example.hello appid=10273 user=-1: uninstall pkg,
I/ActivityManager(  822): Killing 3037:com.example.hello/u0a273 (adj 0): stop com.example.hello
,D/WifiService(  822): Client connection lost with reason: 4
I/WindowState(  822): WIN DEATH: Window{3a6d33d6 u0 com.example.hello/com.example.hello.MainActivity}
,E/libprocessgroup(  822): failed to kill 1 processes for processgroup 3037,
,W/ActivityManager(  822): Force removing ActivityRecord{ef14484 u0 com.example.hello/.MainActivity t26}: app died, no saved state
,I/ActivityManager(  822): Force stopping com.example.hello appid=10273 user=0: pkg removed
,W/ActivityManager(  822): Spurious death for ProcessRecord{36cb7a6b 3037:com.example.hello/u0a273}, curProc for 3037: null
,D/TaskPersister(  822): removeObsoleteFile: deleting file=26_task.xml
,I/Keyboard.Facilitator( 1212): resetDictionaries() : en_US
,I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
,D/BuaReceiver( 2125): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/Atfwd_Daemon(  376): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
I/Atfwd_Daemon(  376): ATFWD --> QMI Port : rmnet_usb0
,I/art     ( 1062): Explicit concurrent mark sweep GC freed 35541(1478KB) AllocSpace objects, 1(30MB) LOS objects, 18% free, 69MB/85MB, paused 1.357ms total 70.335ms
,D/VoicemailCleanupService( 1340): Cleaning up data for package: com.example.hello
,D/JobSchedulerService(  822): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/ActivityManager(  822): Start proc 3321:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,I/art     (  370): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 206us total 9.093ms
,I/Atfwd_Daemon(  376): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 486606848
I/Atfwd_Daemon(  376): Trying to register 8 commands:
I/Atfwd_Daemon(  376): cmd0: +CKPD
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): cmd1: +CTSA
I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 247us total 9.929ms
,I/Keyboard.Facilitator.DecoderInitializer( 1212): run()
,I/Decoder ( 1212): createOrResetDecoder
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): cmd2: +CFUN
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 194us total 10.078ms
,W/InputMethodManagerService(  822): Got RemoteException sending setActive(false) notification to pid 3037 uid 10273
I/Keyboard.Facilitator( 1212): onFinishInput()
I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): cmd3: +CMAR
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): cmd4: +CDIS
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): cmd5: +CRSL
,I/art     (  822): Explicit concurrent mark sweep GC freed 13921(1022KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.876ms total 160.505ms
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): cmd6: +CSS
,I/ActivityManager(  822): Start proc 3342:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): cmd7: $QCPWRDN
,I/ConfigService( 1430): onCreate
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): Registered AT Commands event handler
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1212): run()
,W/LocationOracleImpl( 1501): Best location was null
,W/ErrorReporter( 1501): reportError [type: 29, code: 917507]: null
,I/art     ( 3299): System.exit called, status: 0
I/AndroidRuntime( 3299): VM exiting with result code 0.
,D/Launcher.Workspace( 1276): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1276): 11683562 - stripEmptyScreens()
,I/HotwordRecognitionRnr( 1501): Starting hotword detection.
,I/MicrophoneInputStream( 1501): mic_starting com.google.android.apps.gsa.speech.audio.u@3c4bef19
,I/AudioFlinger(  359): AudioFlinger's thread 0xb40f9000 ready to run
,I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1501): mic_started com.google.android.apps.gsa.speech.audio.u@3c4bef19
,W/GCoreFlp( 1703): No location to return for getLastLocation()
,D/audio_hw_primary(  359): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  359): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  359): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  359): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  359): enable_audio_route: apply and update mixer path: audio-record
,W/GCoreFlp( 1703): No location to return for getLastLocation()
,W/ContextImpl( 3342): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1700316435
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
W/GCoreFlp( 1703): No location to return for getLastLocation()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1212): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 20184(1359KB) AllocSpace objects, 15(240KB) LOS objects, 36% free, 27MB/43MB, paused 2.136ms total 49.344ms
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1212): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1212): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1212): run()
I/StatsUtilsManager( 1212): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1212): shouldRecordStats() = Too Soon
,E/NetworkScheduler.SchedulerReceiver( 1430): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1430): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/HotwordWorker( 1501): onReady
,I/ActivityManager(  822): Killing 2614:com.google.android.keep/u0a79 (adj 15): empty #17
,D/PackageBroadcastService( 1732): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/ChimeraCfgMgr( 1732): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1732): Module APK com.google.android.play.games already loaded
,D/AccountUtils( 1732): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1732): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1732): Module APK com.google.android.play.games already loaded
,E/SQLiteLog( 1732): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,I/UpdateIcingCorporaServi( 1501): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,W/Launcher( 1276): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@48248df new=com.google.android.velvet.VelvetApplication@48248df
,I/LocationSettingsChecker( 1732): Removing dialog suppression flag for package com.example.hello
--------- beginning of crash
E/AndroidRuntime( 1732): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1732): Process: com.google.android.gms, PID: 1732
E/AndroidRuntime( 1732): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1732): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1732): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1732): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1732): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1732): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1732): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/AndroidRuntime( 1732): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1732): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1732): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1732): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 1732): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 1732): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
E/AndroidRuntime( 1732): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1732): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
E/AndroidRuntime( 1732): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1732): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1732): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1732): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1276): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
E/SQLiteLog( 1501): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/ActivityManager(  822): Start proc 3387:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,E/SQLiteDatabase( 1732): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1732): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1732): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1732): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1732): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1732): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1732): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1732): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1732): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1732): ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1732): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1732): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1732): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1732): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1732): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1732): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1732): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1732): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1732): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1732): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1732): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1732): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1732): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1732): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1732): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1732): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1732): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1732): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1732): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1732): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1732): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1732): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1732): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1732): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1732): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1732): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1732): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1732): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 1732): Opened metrics.db in read-only mode
D/GOOGLEHELP_CompatibleDatabase( 1732): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1732): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1732): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.example.hello"] attempt to write a readonly database
D/GOOGLEHELP_CompatibleDatabase( 1732): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Process ( 1732): Sending signal. PID: 1732 SIG: 9
I/ActivityManager(  822): Start proc 3404:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
E/lowmemorykiller(  256): Error writing /proc/1732/oom_score_adj; errno=22
E/SharedPreferencesImpl( 1501): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
E/AndroidRuntime( 1501): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 1501): Process: com.google.android.googlequicksearchbox:search, PID: 1501
E/AndroidRuntime( 1501): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1501): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1501): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1501): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1501): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1501): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1501): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1501): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 1501): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 1501): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 1501): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AndroidRuntime( 1501): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 1501): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 1501): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 1501): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 1501): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 1501): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 1501): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1501): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1501): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1501): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop86.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  822): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  822): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  822): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  822): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  822): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  822): 	... 5 more
W/ResourcesManager(  822): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  822): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/OpenGLRenderer(  822): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  822): Validating map...
W/ActivityManager(  822): Failure sending service ComponentInfo{com.google.android.gms/com.google.android.location.util.PreferenceService} to connection android.os.BinderProxy@10f0d93a (in com.google.android.gms)
W/ActivityManager(  822): android.os.DeadObjectException
W/ActivityManager(  822): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  822): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  822): 	at android.app.IServiceConnection$Stub$Proxy.connected(IServiceConnection.java:92)
W/ActivityManager(  822): 	at com.android.server.am.ActiveServices.publishServiceLocked(ActiveServices.java:885)
W/ActivityManager(  822): 	at com.android.server.am.ActivityManagerService.publishService(ActivityManagerService.java:15342)
W/ActivityManager(  822): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:978)
W/ActivityManager(  822): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  822): 	at android.os.Binder.execTransact(Binder.java:446)
I/ActivityManager(  822): Process com.google.android.gms (pid 1732) has died
W/ActivityManager(  822): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager(  822): Scheduling restart of crashed service com.google.android.gms/.ads.identifier.service.AdvertisingIdService in 1000ms
W/ActivityManager(  822): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 11000ms
W/ActivityManager(  822): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 11000ms
W/ActivityManager(  822): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 21000ms
W/ActivityManager(  822): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20999ms
W/ActivityManager(  822): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 30999ms
W/ActivityManager(  822): Scheduling restart of crashed service com.google.android.gms/.usagereporting.service.UsageReportingService in 30999ms
,E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop88.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  822): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  822): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  822): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  822): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  822): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  822): 	... 5 more
I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
I/OpenGLRenderer(  822): Initialized EGL, version 1.4
D/OpenGLRenderer(  822): Enabling debug mode 0
W/InputMethodManagerService(  822): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@4ed7c9a attribute=null, token = android.os.BinderProxy@301910c9
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/OpenGLRenderer(  822): Initialized EGL, version 1.4
,I/ActivityManager(  822): Start proc 3430:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
,W/OpenGLRenderer( 1276): Incorrectly called buildLayer on View: ew, destroying layer...
,W/ResourcesManager( 3430): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3430): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3430): VM with version 2.1.0 has multidex support
I/MultiDex( 3430): install
I/MultiDex( 3430): VM has multidex support, MultiDex support library is disabled.
,I/HotwordDetector( 1501): Closing mic
I/MicrophoneInputStream( 1501): mic_close com.google.android.apps.gsa.speech.audio.u@3c4bef19
,I/ActivityManager(  822): Waited long enough for: ServiceRecord{2abc617f u0 org.simalliance.openmobileapi.service/.SmartcardService}
,E/SQLiteDatabase( 3430): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 3430): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3430): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3430): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1181)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1200)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 3430): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 3430): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3430): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 3430): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 3430): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3430): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3430): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteOpenHelper.getWr,itableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.security.snet.aa.b(SourceFile:826)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.security.snet.aa.a(SourceFile:847)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 3430): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 3430): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3430): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3430): 	at java.lang.Thread.run(Thread.java:818)
V/JNIHelp ( 3430): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1501): Hotword detection finished
I/HotwordRecognitionRnr( 1501): Stopping hotword detection.
,I/ProviderInstaller( 3430): Installed default security provider GmsCore_OpenSSL
,W/NativeLibraryUtils( 3430): Failed to open lock file
W/NativeLibraryUtils( 3430): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 3430): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 3430): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 3430): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 3430): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 3430): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 3430): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 3430): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 3430): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 3430): 	... 3 more
,I/ActivityManager(  822): Killing 2661:com.qualcomm.telephony/1001 (adj 15): empty #17
,I/GAv4    ( 3387): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3387):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3387):   adb logcat -s GAv4
,W/GAv4    ( 3387): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/GAv4-SVC( 3430): Google Analytics 7.8.99 is starting up.
,I/ActivityManager(  822): Killing 2037:com.android.defcontainer/u0a7 (adj 15): empty #17
,W/GAv4    ( 3387): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 3387): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/Icing   ( 3430): Storage manager: low false usage 2.04MB avail 20.74GB capacity 22.09GB
E/SharedPreferencesImpl( 3387): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 3387): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 3387): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/Icing   ( 3430): Received bad json for section weights override -- ignoring.
,W/AnalyticsTrackerProxyImpl( 3387): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,W/Icing   ( 3430): Received bad json for corpus context scoring override -- ignoring.
,W/Icing   ( 3430): Received bad json for section weights override -- ignoring.
,W/Icing   ( 3430): Received bad json for corpus context scoring override -- ignoring.
,E/SQLiteDatabase( 3387): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3387): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3387): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3387): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 3387): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 3387): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 3387): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 3387): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 3387): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 3387): 	at gir$c.run(Unknown Source)
E/GAv4    ( 3387): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 3387): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 3387): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3387): 	,at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463),
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
,E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3387): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148),
E/SQLiteDatabase( 3387): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163),
E/SQLiteDatabase( 3387): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 3387): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 3387): 	,at fdw.a(Unknown Source)
E/SQLiteDatabase( 3387): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 3387): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 3387): 	,at feb.run(Unknown Source)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 3387): ,	at gir$c.run(Unknown Source)
E/SQLiteDatabase( 3387): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3387): 	,at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3387): 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806),
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3387): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3387): 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3387): 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3387): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 3387): 	at ael.a(PG:1521)
E/SQLiteDatabase( 3387): 	at hix$a.a(PG:125),
E/SQLiteDatabase( 3387): 	at aen.run(PG:536)
E/Icing   ( 3430): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids for write failed: Read-only file system
E/Icing   ( 3430): Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids
,E/Icing   ( 3430): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata for write failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata failed: Read-only file system
E/Icing   ( 3430): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring for write failed: Read-only file system
,E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring failed: Read-only file system
E/Icing   ( 3430): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs for write failed: Read-only file system
E/Icing   ( 3430): Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs
E/Icing   ( 3430): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.tags.h for write failed: Read-only file system
E/Icing   ( 3430): Trie initialize fail
,E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.counts failed: Read-only file system
E/Icing   ( 3430): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h for write failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.n failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.x failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.s failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.deleted failed: Read-only file system
,E/Icing   ( 3430): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage for write failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage failed: Read-only file system
E/Icing   ( 3430): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage for write failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage failed: Read-only file system
E/Icing   ( 3430): Init docstore failed
E/Icing   ( 3430): Index init failed, resetting corpora
E/GAv4    ( 3387): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 3387): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 3387): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 3387): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 3387): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 3387): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/idx.index failed: Read-only file system
E/Icing   ( 3430): Clearing index failed
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-0 failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-24 failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-30 failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user.__unseen__i.43133bd20a9b3232 failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.counts failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.n failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.x failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.s failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.deleted failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage failed: Read-only file system
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage failed: Read-only file system
E/Icing   ( 3430): Clearing docstore failed
E/Icing   ( 3430): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/compact_status failed: Read-only file system
E/Icing   ( 3430): Deleting compact status failed
,E/SQLiteDatabase( 3430): Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 3430): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3430): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3430): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:884)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.analytics.internal.v.o(SourceFile:812)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.analytics.internal.v.a(SourceFile:630)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.analytics.internal.v.q(SourceFile:264)
E/SQLiteDatabase( 3430): 	,at com.google.android.gms.analytics.internal.v.e(SourceFile:274)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
E/SQLiteDatabase( 3430): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3430): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.e.k.run(SourceFile:388)
,E/GAv4-SVC( 3430): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 3430): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 3430): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 3430): Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 3430): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3430): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3430): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:897)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.analytics.internal.v.o(SourceFile:812)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.analytics.internal.v.a(SourceFile:630)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.analytics.internal.v.q(SourceFile:264)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.analytics.internal.v.e(SourceFile:274)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
E/SQLiteDatabase( 3430): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3430): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.e.k.run(SourceFile:388)
,E/GAv4-SVC( 3430): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,W/GAv4-SVC( 3430): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 3430): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 3430): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4-SVC( 3430): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 3430): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,I/art     ( 1430): Explicit concurrent mark sweep GC freed 23265(1091KB) AllocSpace objects, 2(32KB) LOS objects, 38% free, 25MB/41MB, paused 1.295ms total 32.775ms
,E/SQLiteDatabase( 3430): Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
E/SQLiteDatabase( 3430): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3430): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3430): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteDatabase( 3430): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteDatabase( 3430): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteDatabase( 3430): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteDatabase( 3430): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteDatabase( 3430): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 3430): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3430): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 3430): Couldn't open reminders.db for writing (will try read-only):
E/SQLiteOpenHelper( 3430): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3430): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 3430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 3430): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3430): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 3430): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 3430): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHe,lper( 3430): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 3430): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 3430): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 3430): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 3430): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteOpenHelper( 3430): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteOpenHelper( 3430): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteOpenHelper( 3430): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteOpenHelper( 3430): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteOpenHelper( 3430): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteOpenHelper( 3430): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteOpenHelper( 3430): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteOpenHelper( 3430): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 3430): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteOpenHelper( 3430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 3430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 3430): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 3430): Opened reminders.db in read-only mode
D/GFEEDBACK_SendErrorReportOperation( 3430): Error doing instant send: java.io.IOException: failed to create reports directory
E/GFEEDBACK_SendErrorReportOperation( 3430): Error saving report: java.io.IOException: failed to create reports directory
E/SQLiteDatabase( 3430): Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
E/SQLiteDatabase( 3430): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3430): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3430): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3430): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/SQLiteDatabase( 3430): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/SQLiteDatabase( 3430): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 3430): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3430): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3430): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 3430): FATAL EXCEPTION: AsyncTask #3
E/AndroidRuntime( 3430): Process: com.google.android.gms, PID: 3430
E/AndroidRuntime( 3430): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 3430): 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
E/AndroidRuntime( 3430): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 3430): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 3430): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 3430): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime( 3430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 3430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 3430): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 3430): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3430): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 3430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 3430): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3430): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 3430): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 3430): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 3430): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 3430): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 3430): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 3430): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 3430): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
E/AndroidRuntime( 3430): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/AndroidRuntime( 3430): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/AndroidRuntime( 3430): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/AndroidRuntime( 3430): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 3430): 	... 4 more
E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop91.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  822): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  822): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  822): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  822): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  822): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  822): 	... 5 more
W/GAv4    ( 3387): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 3387): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3387): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 3387): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 3387): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3387): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3387): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3387): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 3387): 	at ael.a(PG:1521)
E/SQLiteDatabase( 3387): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 3387): 	at aej.c(PG:139)
E/SQLiteDatabase( 3387): 	at aej.b(PG:398)
E/SQLiteDatabase( 3387): 	at agf.f(PG:417)
E/SQLiteDatabase( 3387): 	at oe.run(PG:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 3387): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 3387): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 3387): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 3387): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 3387): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 3387): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 3387): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 3387): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 3387): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 3387): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 3387): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 3387): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 3387): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 3387): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 3387): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 3387): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 3387): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 3387): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 3387): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 3387): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 3387): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 3387): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 3387): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 3387): 	at java.lang.Thread.run(Thread.java:818)
W/GAv4    ( 3387): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3387): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 3387): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3387): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 3387): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3387): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 3387): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 3387): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3387): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 3387): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3387): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 3387): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3387): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 3387): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
,E/CAKEMIX_CRASHED( 3387): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 3387): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 3387): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 3387): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 3387): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 3387): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 3387): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 3387): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 3387): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 3387): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 3387): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 3387): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 3387): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 3387): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 3387): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 3387): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 3387): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 3387): 	at aen.run(PG:536)
W/ResourcesManager( 3387): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
E/SharedPreferencesImpl( 3387): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/ResourcesManager( 3387): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  822): Start proc 3486:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
I/ActivityManager(  822): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{38c2139b token=Token{e0babaa ActivityRecord{17816e95 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t27}}} to stack=1 task=27 at 0
I/Process ( 3387): Sending signal. PID: 3387 SIG: 9
,E/lowmemorykiller(  256): Error writing /proc/3387/oom_score_adj; errno=22
,E/JavaBinder(  822): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  822): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  822): android.os.TransactionTooLargeException
W/ActivityManager(  822): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  822): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  822): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:797)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1181)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1281)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1891)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1455)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2473)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:998)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:896)
W/ActivityManager(  822): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6311)
W/ActivityManager(  822): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:512)
W/ActivityManager(  822): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  822): 	at android.os.Binder.execTransact(Binder.java:446)
,V/WindowManager(  822): Adding window Window{1ddddf49 u0 Starting com.google.android.apps.docs} at 2 of 9 (after Window{223f93ce u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
,E/native  ( 1212): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1212): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,I/ActivityManager(  822): Start proc 3504:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
,I/ActivityManager(  822): Waited long enough for: ServiceRecord{36f6a86f u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,W/ActivityManager(  822): Spurious death for ProcessRecord{1c6ff869 3504:com.google.android.apps.docs/u0a46}, curProc for 3387: null
,E/native  ( 1212): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1212): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,I/art     ( 3097): Note: end time exceeds epoch: 
,E/Icing   ( 3430): Not initialized
,E/Icing   ( 3430): Not initialized
,E/native  ( 1212): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1212): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1212): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1212): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/SQLiteDatabase( 3486): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 3486): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3486): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3486): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3486): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3486): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3486): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3486): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3486): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3486): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3486): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3486): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3486): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3486): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3486): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3486): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 3486): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 3486): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 3486): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 3486): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 3486): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 3486): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 3486): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 3486): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3486): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 3486): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 3486): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 3486): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 3486): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 3486): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/AndroidRuntime( 3486): Shutting down VM
,E/AndroidRuntime( 3486): FATAL EXCEPTION: main
E/AndroidRuntime( 3486): Process: com.android.documentsui, PID: 3486
E/AndroidRuntime( 3486): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3486): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 3486): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 3486): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 3486): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3486): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 3486): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 3486): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 3486): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 3486): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 3486): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 3486): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3486): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3486): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 3486): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 3486): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3486): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3486): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3486): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 3486): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 3486): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 3486): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 3486): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 3486): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 3486): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 3486): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 3486): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 3486): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 3486): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 3486): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 3486): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 3486): 	... 9 more
,E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop93.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  822): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  822): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  822): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  822): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  822): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  822): 	... 5 more
,D/WearableService( 3139): callingUid 10011, callindPid: 3139
,D/GCM     ( 1430): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/art     (  822): Explicit concurrent mark sweep GC freed 21392(1171KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.623ms total 88.445ms
,D/AuthorizationBluetoothService( 1430): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 3430): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1703): [129] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager(  822): Start proc 3534:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,I/MusicLeanback( 3172): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3172): Stop autocaching.
,W/FileUtils( 3139): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
W/ServiceConnection( 3139): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/service.connections: open failed: EROFS (Read-only file system)
W/ServiceConnection( 3139): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/ServiceConnection( 3139): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/ServiceConnection( 3139): 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:982)
W/ServiceConnection( 3139): 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:182)
W/ServiceConnection( 3139): 	at com.google.android.gms.common.internal.cm.b(SourceFile:80)
W/ServiceConnection( 3139): 	at com.google.android.gms.common.internal.cm.a(SourceFile:27)
W/ServiceConnection( 3139): 	at com.google.android.gms.common.internal.cn.run(SourceFile:64)
W/ServiceConnection( 3139): 	at java.lang.Thread.run(Thread.java:818)
W/ServiceConnection( 3139): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/ServiceConnection( 3139): 	at libcore.io.Posix.open(Native Method)
W/ServiceConnection( 3139): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/ServiceConnection( 3139): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/ServiceConnection( 3139): 	... 7 more
,E/GmsUtils( 3172): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/FileUtils( 3139): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
W/ServiceConnection( 3139): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/service.connections: open failed: EROFS (Read-only file system)
W/ServiceConnection( 3139): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/ServiceConnection( 3139): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/ServiceConnection( 3139): 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:982)
W/ServiceConnection( 3139): 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:182)
W/ServiceConnection( 3139): 	at com.google.android.gms.common.internal.cm.b(SourceFile:80)
W/ServiceConnection( 3139): 	at com.google.android.gms.common.internal.cm.a(SourceFile:27)
W/ServiceConnection( 3139): 	at com.google.android.gms.common.internal.cn.run(SourceFile:64)
W/ServiceConnection( 3139): 	at java.lang.Thread.run(Thread.java:818)
W/ServiceConnection( 3139): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/ServiceConnection( 3139): 	at libcore.io.Posix.open(Native Method)
W/ServiceConnection( 3139): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/ServiceConnection( 3139): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/ServiceConnection( 3139): 	... 7 more
,D/LocationInitializer( 3430): Restart initialization of location
,E/GmsUtils( 3172): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager(  822): Killing 2725:com.google.android.youtube/u0a86 (adj 15): empty #17
,D/ExternalStorage( 3534): After updating volumes, found 1 active roots
,I/GAv4    ( 3504): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3504):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3504):   adb logcat -s GAv4
,W/GAv4    ( 3504): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3504): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 3504): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 3504): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 3504): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 3504): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 3504): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 3504): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3504): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3504): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 3504): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 3504): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 3504): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 3504): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 3504): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 3504): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3504): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3504): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3504): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3504): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 3504): 	at gir$c.run(Unknown Source)
E/GAv4    ( 3504): Opening the database failed, dropping the table and recreating it
,W/AnalyticsTrackerProxyImpl( 3504): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SharedPreferencesImpl( 3504): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 1430): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1430): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1430): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1430): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1430): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1430): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1430): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1430): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1430): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1430): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1430): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1430): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 1430): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1430): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1430): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1430): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1430): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1430): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1430): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1430): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1430): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1430): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1430): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1430): 	at android.databa,se.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1430): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 1430): Opened phenotype.db in read-only mode
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteDatabase( 3504): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 3504): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3504): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3504): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 3504): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 3504): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 3504): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 3504): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 3504): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 3504): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3504): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3504): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3504): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3504): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 3504): 	at gir$c.run(Unknown Source)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/GAv4    ( 3504): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 3504): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	,at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
W/GAv4    ( 3504): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	,at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
,E/SharedPreferencesImpl( 3504): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 3504): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
,E/SharedPreferencesImpl( 3504): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	,at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	,at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): ,	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
,E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	,at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/SQLiteDatabase( 3504): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 3504): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3504): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3504): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 3504): 	at ael.a(PG:1521)
E/SQLiteDatabase( 3504): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 3504): 	at aen.run(PG:536)
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteDatabase( 3504): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 3504): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3504): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3504): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 3504): 	at ael.a(PG:1521)
E/SQLiteDatabase( 3504): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 3504): 	at aej.c(PG:139)
E/SQLiteDatabase( 3504): 	at aej.b(PG:398)
E/SQLiteDatabase( 3504): 	at agf.f(PG:417)
E/SQLiteDatabase( 3504): 	at oe.run(PG:1112)
E/SQLiteDatabase( 3504): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3504): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3504): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3504): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3504): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 3504): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 3504): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 3504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 3504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 3504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 3504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 3504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 3504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 3504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 3504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 3504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 3504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 3504): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 3504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 3504): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 3504): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 3504): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 3504): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 3504): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 3504): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 3504): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 3504): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 3504): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 3504): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 3504): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 3504): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 3504): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 3504): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3504): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3504): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/ErrorNotificationActivity( 3504): Google Drive has stopped unexpectedly. Please provide additional details to help us diagnose the issue.
,I/ProviderInstaller( 3504): Installed default security provider GmsCore_OpenSSL
,D/OpenGLRenderer( 3504): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3504): Validating map...
,V/WindowManager(  822): Adding window Window{30d2e0c5 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 11 (before Window{1ddddf49 u0 Starting com.google.android.apps.docs})
,V/WindowManager(  822): Adding window Window{3c3ac94b u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 12 (before Window{30d2e0c5 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}),
,W/GAv4    ( 3504): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 3504): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 3504): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 3504): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 3504): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 3504): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3504): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3504): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 3504): 	at ael.a(PG:1521)
E/SQLiteDatabase( 3504): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 3504): 	at aej.c(PG:139)
E/SQLiteDatabase( 3504): 	at aej.a(PG:358)
E/SQLiteDatabase( 3504): 	at aej.a(PG:345)
E/SQLiteDatabase( 3504): 	at agf.d(PG:281)
E/SQLiteDatabase( 3504): 	at agf.b(PG:312)
E/SQLiteDatabase( 3504): 	at agf.a(PG:221)
E/SQLiteDatabase( 3504): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/SQLiteDatabase( 3504): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/SQLiteDatabase( 3504): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteDatabase( 3504): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteDatabase( 3504): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase( 3504): 	at android.os.Binder.execTransact(Binder.java:446)
E/AbstractDatabaseInstance( 3504): Failed to query Account133 object
E/AbstractDatabaseInstance( 3504): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 3504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 3504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 3504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 3504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 3504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 3504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 3504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 3504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 3504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 3504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 3504): 	at ,android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 3504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 3504): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 3504): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 3504): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 3504): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 3504): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 3504): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 3504): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 3504): 	at agf.d(PG:281)
E/AbstractDatabaseInstance( 3504): 	at agf.b(PG:312)
E/AbstractDatabaseInstance( 3504): 	at agf.a(PG:221)
E/AbstractDatabaseInstance( 3504): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/AbstractDatabaseInstance( 3504): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/AbstractDatabaseInstance( 3504): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/AbstractDatabaseInstance( 3504): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/AbstractDatabaseInstance( 3504): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/AbstractDatabaseInstance( 3504): 	at android.os.Binder.execTransact(Binder.java:446)
W/GAv4    ( 3504): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3504): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 3504): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 3504): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 3504): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
,E/DatabaseUtils( 3504): Writing exception to parcel
E/DatabaseUtils( 3504): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DatabaseUtils( 3504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DatabaseUtils( 3504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/DatabaseUtils( 3504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/DatabaseUtils( 3504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/DatabaseUtils( 3504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/DatabaseUtils( 3504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/DatabaseUtils( 3504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/DatabaseUtils( 3504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/DatabaseUtils( 3504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/DatabaseUtils( 3504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/DatabaseUtils( 3504): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/DatabaseUtils( 3504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/DatabaseUtils( 3504): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/DatabaseUtils( 3504): 	at aev.getWritableDatabase(PG:238)
E/DatabaseUtils( 3504): 	at ael.a(PG:1521)
E/DatabaseUtils( 3504): 	at hix$a.a(PG:125)
E/DatabaseUtils( 3504): 	at aej.c(PG:139)
E/DatabaseUtils( 3504): 	at aej.a(PG:358)
E/DatabaseUtils( 3504): 	at aej.a(PG:345)
E/DatabaseUtils( 3504): 	at agf.d(PG:281)
E/DatabaseUtils( 3504): 	at agf.b(PG:312)
E/DatabaseUtils( 3504): 	at agf.a(PG:221)
E/DatabaseUtils( 3504): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/DatabaseUtils( 3504): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/DatabaseUtils( 3504): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/DatabaseUtils( 3504): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/DatabaseUtils( 3504): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 3504): 	at android.os.Binder.execTransact(Binder.java:446)
,E/SharedPreferencesImpl( 3504): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 3504): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 3504): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,W/Documents( 3486): Failed to load some roots from com.google.android.apps.docs.storage: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
D/Documents( 3486): Update found 6 roots in 551ms
,E/SharedPreferencesImpl( 3504): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 3504): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
,W/GAv4    ( 3504): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3504): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 3504): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 3504): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 3504): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 3504): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 3504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 3504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 3504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 3504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 3504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 3504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 3504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 3504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 3504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 3504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 3504): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 3504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 3504): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 3504): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 3504): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 3504): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 3504): 	at aen.run(PG:536)
,I/ActivityManager(  822): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
,I/Adreno  ( 3504): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/Process ( 3504): Sending signal. PID: 3504 SIG: 9
,W/InputDispatcher(  822): channel '30d2e0c5 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  822): channel '30d2e0c5 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  822): channel '3c3ac94b com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  822): channel '3c3ac94b com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,I/WindowState(  822): WIN DEATH: Window{30d2e0c5 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
W/InputDispatcher(  822): Attempted to unregister already unregistered input channel '30d2e0c5 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)'
I/ActivityManager(  822): Process com.google.android.apps.docs (pid 3504) has died,
W/ActivityManager(  822): Force removing ActivityRecord{17816e95 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t27}: app died, no saved state
,I/WindowState(  822): WIN DEATH: Window{3c3ac94b u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
,W/InputDispatcher(  822): Attempted to unregister already unregistered input channel '3c3ac94b com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)'
,W/WindowManager(  822): Failed looking up window
W/WindowManager(  822): java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@2ab9c150 does not exist
,W/WindowManager(  822): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8539)
W/WindowManager(  822): 	,at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8530)
W/WindowManager(  822): 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:2593)
W/WindowManager(  822): 	at com.android.server.wm.Session.remove(Session.java:187)
W/WindowManager(  822): 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3009),
W/WindowManager(  822): 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:5496)
W/WindowManager(  822): 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:3315)
W/WindowManager(  822): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/WindowManager(  822): 	at android.os.Looper.loop(Looper.java:135)
W/WindowManager(  822): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/WindowManager(  822): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database,
,E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8),
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
,E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): ,	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): ,	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1430): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1430): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
,W/OpenGLRenderer( 1276): Incorrectly called buildLayer on View: ew, destroying layer...
,I/ActivityManager(  822): Waited long enough for: ServiceRecord{affa5dc u0 com.qualcomm.atfwd/.AtFwdService}
,F/PackageManager(  822): Unable to backup user packages state file, current changes will be lost at reboot
,E/DropBoxManagerService(  822): Can't write: system_server_wtf
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop19.tmp: open failed: EROFS (Read-only file system),
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  822): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  822): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  822): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  822): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12002)
E/DropBoxManagerService(  822): 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:11815)
E/DropBoxManagerService(  822): 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:11787)
E/DropBoxManagerService(  822): 	at android.os.Handler.handleCallback(Handler.java:739)
E/DropBoxManagerService(  822): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService(  822): 	at android.os.Looper.loop(Looper.java:135)
E/DropBoxManagerService(  822): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  822): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
E/DropBoxManagerService(  822): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  822): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  822): 	... 13 more
,E/SQLiteLog( 2827): (3850) statement aborts at 28: [UPDATE requests SET server_target_retry=?,server_fail_count=?,fail_count=? WHERE _id=?] disk I/O error
,E/Babel_Crash( 2827): Uncaught exception in background thread Thread[default_queue1,5,main]
,E/Babel_Crash( 2827): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/Babel_Crash( 2827): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/Babel_Crash( 2827): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/Babel_Crash( 2827): 	,at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/Babel_Crash( 2827): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/Babel_Crash( 2827): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1576)
E/Babel_Crash( 2827): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1522)
E/Babel_Crash( 2827): 	at dhe.a(SourceFile:3360)
E/Babel_Crash( 2827): 	at cap.d(SourceFile:393)
E/Babel_Crash( 2827): 	at caq.run(SourceFile:81)
,E/SharedPreferencesImpl( 2827): Couldn't rename file /data/data/com.google.android.talk/shared_prefs/EsApplication.xml to backup file /data/data/com.google.android.talk/shared_prefs/EsApplication.xml.bak
,E/AndroidRuntime( 2827): FATAL EXCEPTION: default_queue1
E/AndroidRuntime( 2827): Process: com.google.android.talk, PID: 2827
E/AndroidRuntime( 2827): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2827): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2827): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 2827): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2827): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2827): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1576)
E/AndroidRuntime( 2827): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1522)
E/AndroidRuntime( 2827): 	at dhe.a(SourceFile:3360)
E/AndroidRuntime( 2827): 	at cap.d(SourceFile:393)
E/AndroidRuntime( 2827): 	at caq.run(SourceFile:81)
,E/SQLiteDatabase( 1430): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 1430): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1430): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1430): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1430): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1430): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1430): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1430): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1430): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1430): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1430): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1430): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1430): 	at com.google.android.gms.playlog.store.g.b(SourceFile:384)
E/SQLiteDatabase( 1430): 	at com.google.android.gms.playlog.store.g.a(SourceFile:352)
E/SQLiteDatabase( 1430): 	at com.google.android.gms.playlog.service.c.a(SourceFile:103)
E/SQLiteDatabase( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1430): 	at java.lang.Thread.run(Thread.java:818)
E/PlayLogIntentService( 1430): not an error (code 0): Could not open the database in read/write mode.
E/PlayLogIntentService( 1430): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PlayLogIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PlayLogIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PlayLogIntentService( 1430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PlayLogIntentService( 1430): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PlayLogIntentService( 1430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PlayLogIntentService( 1430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PlayLogIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/PlayLogIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/PlayLogIntentService( 1430): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PlayLogIntentService( 1430): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/PlayLogIntentService( 1430): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PlayLogIntentService( 1430): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PlayLogIntentService( 1430): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelp,er.java:223)
E/PlayLogIntentService( 1430): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PlayLogIntentService( 1430): 	at com.google.android.gms.playlog.store.g.b(SourceFile:384)
E/PlayLogIntentService( 1430): 	at com.google.android.gms.playlog.store.g.a(SourceFile:352)
E/PlayLogIntentService( 1430): 	at com.google.android.gms.playlog.service.c.a(SourceFile:103)
E/PlayLogIntentService( 1430): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/PlayLogIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/PlayLogIntentService( 1430): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/PlayLogIntentService( 1430): 	at java.lang.Thread.run(Thread.java:818)
,E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  822): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  822): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  822): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  822): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  822): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  822): 	... 5 more
,E/SQLiteLog( 3210): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DatabaseUtils( 3210): Writing exception to parcel
E/DatabaseUtils( 3210): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DatabaseUtils( 3210): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DatabaseUtils( 3210): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DatabaseUtils( 3210): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DatabaseUtils( 3210): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DatabaseUtils( 3210): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DatabaseUtils( 3210): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DatabaseUtils( 3210): 	at com.android.providers.calendar.CalendarProvider2.acquireInstanceRange(CalendarProvider2.java:1351)
E/DatabaseUtils( 3210): 	at com.android.providers.calendar.CalendarProvider2.handleInstanceQuery(CalendarProvider2.java:1109)
E/DatabaseUtils( 3210): 	at com.android.providers.calendar.CalendarProvider2.queryInternal(CalendarProvider2.java:938)
E/DatabaseUtils( 3210): 	at com.android.providers.calendar.CalendarProvider2.query(CalendarProvider2.java:839)
E/DatabaseUtils( 3210): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/DatabaseUtils( 3210): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/DatabaseUtils( 3210): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 3210): 	at android.os.Binder.execTransact(Binder.java:446)
,E/AndroidRuntime( 2530): FATAL EXCEPTION: AlertService
E/AndroidRuntime( 2530): Process: com.google.android.calendar, PID: 2530
E/AndroidRuntime( 2530): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2530): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
E/AndroidRuntime( 2530): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
E/AndroidRuntime( 2530): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
E/AndroidRuntime( 2530): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/AndroidRuntime( 2530): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/AndroidRuntime( 2530): 	at com.android.calendar.alerts.AlarmScheduler.queryUpcomingEvents(AlarmScheduler.java:158)
E/AndroidRuntime( 2530): 	at com.android.calendar.alerts.AlarmScheduler.scheduleNextAlarm(AlarmScheduler.java:115)
E/AndroidRuntime( 2530): 	at com.android.calendar.alerts.AlarmScheduler.scheduleNextAlarm(AlarmScheduler.java:106)
E/AndroidRuntime( 2530): 	at com.android.calendar.alerts.AlertService.processMessage(AlertService.java:244)
E/AndroidRuntime( 2530): 	at com.android.calendar.alerts.AlertService$ServiceHandler.handleMessage(AlertService.java:897)
E/AndroidRuntime( 2530): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2530): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2530): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
,E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  822): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
,E/DropBoxManagerService(  822): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  822): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  822): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  822): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  822): 	... 5 more
,I/ConfigService( 1430): onDestroy
,E/QMI_FW  (  822): xport_send: Sendto failed for port 4608
E/LocSvc_api_v02(  822): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1700316435
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,E/qdhwcomposer(  259): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  259): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=14 dpy=0 numHwLayers=11
E/qdoverlay(  259): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  259): MdpData failed to play
E/qdoverlay(  259): == Dump MdpData start ==
E/qdoverlay(  259): == Dump OvFD fd=26 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  259): mOvData msmfb_overlay_data id=8
E/qdoverlay(  259): data msmfb_data offset=0 memid=32 id=0 flags=0x0 priv=0
E/qdoverlay(  259): == Dump MdpData end ==
E/qdhwcomposer(  259): draw: queue failed for left of dpy = 0
E/qdoverlay(  259): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  259): MdpData failed to play
,E/qdoverlay(  259): == Dump MdpData start ==
E/qdoverlay(  259): == Dump OvFD fd=29 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  259): mOvData msmfb_overlay_data id=16
E/qdoverlay(  259): data msmfb_data offset=0 memid=32 id=0 flags=0x0 priv=0
E/qdoverlay(  259): == Dump MdpData end ==
E/qdhwcomposer(  259): draw: queue failed for right of dpy = 0
E/qdhwcomposer(  259): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  259): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  259): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  259): hwc_set_primary: display commit fail for 0 dpy!
E/kickstart(  872): ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
,E/kickstart(  872): ERROR: function: sahara_main:1143 Sahara protocol error
E/kickstart(  872): ERROR: function: main:268 Uploading  Image using Sahara protocol failed
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
,E/Icing   ( 3430): Not initialized
,E/Icing   ( 3430): Not initialized
,D/        (  359): csd_client_error_cb: error -2 cb_data 0xb603e060
D/        (  359): csd_client_error_cb: MDM reset
E/        (  359): deinit: QMI - result 0, error 0, CSD - valid 0, status 0, rc -2
E/        (  359): csd_service_deinit: Error -1 deiniting CSD,
E/ThermalEngine(  367): qmi_clnt_error_cb: with error -2 called for clnt FUSION
,I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb0
E/ThermalEngine(  367): modem_clnt_error_cb: with -2 called for clnt 0x8
I/Atfwd_Daemon(  376): Modem Out Of Service --> Release ATCOP service client handles, if any
,I/Atfwd_Daemon(  376): release_client returns -1, qmiErroCode = 0 for qmiPort: rmnet_usb0 & userHandle: 486606848
,I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb4
,I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb1
I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb7
I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb3
I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb2
I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb6
,I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb5
,I/ThermalEngine(  367): qmi: Instance id 157 for fusion TS,
,E/        (  359): csd_service_deinit: notifier handle release rc:0
,E/ThermalEngine(  367): qmi_clnt_error_cb: with error -2 called for clnt MODEM,

```
