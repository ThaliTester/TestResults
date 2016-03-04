#### Test 61703351a2a4153_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
D/Finsky  ( 2984): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/Finsky  ( 2984): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
--------- beginning of system
I/ActivityManager(  824): Start proc 3025:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
W/Settings( 2984): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 2984): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ResourcesManager( 3025): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3025): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Volley  ( 2984): [303] DiskBasedCache.clear: Cache cleared.
I/MultiDex( 3025): VM with version 2.1.0 has multidex support
I/MultiDex( 3025): install
I/MultiDex( 3025): VM has multidex support, MultiDex support library is disabled.
D/Volley  ( 2984): [296] DiskBasedCache.clear: Cache cleared.
I/ActivityManager(  824): Start proc 3047:com.google.android.gm/u0a78 for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver
I/ActivityManager(  824): Killing 2517:com.google.android.onetimeinitializer/u0a15 (adj 15): empty #17
D/Finsky  ( 2984): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 2984): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 2984): [1] GmsCoreHelper.cleanupNlp: result=false type=4
V/JNIHelp ( 3025): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/Finsky  ( 2984): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ProviderInstaller( 3025): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  824): Killing 2541:com.android.managedprovisioning/u0a17 (adj 15): empty #17
V/Finsky  ( 2984): [1] GearheadStateMonitor.onReady: sIsProjecting:false
D/ActivityThread( 3047): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
I/Gmail   ( 3047): getAccountsCursor
V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     (  824): Explicit concurrent mark sweep GC freed 13007(624KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.125ms total 50.367ms
I/ActivityManager(  824): Start proc 3078:com.google.android.gm.exchange/u0a77 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
W/ActivityManager(  824): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/GAV2    ( 3047): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/Gmail   ( 3047): Observing account changes for notifications
I/Gmail   ( 3047): getAccountsCursor
V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SystemBroadcastReceiver( 1243): Boot has been completed
I/SystemBroadcastReceiver( 1243): toggleAppIcon() : FLAG_SYSTEM = true
V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SQLiteLog( 3047): (283) recovered 11 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
I/ActivityManager(  824): Start proc 3111:com.google.android.apps.messaging/u0a75 for broadcast com.google.android.apps.messaging/.receiver.BootAndPackageReplacedReceiver
V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Exchange( 3078): EasService.onCreate
E/ActivityThread( 3047): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@67e5e1 that was originally bound here
E/ActivityThread( 3047): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@67e5e1 that was originally bound here
E/ActivityThread( 3047): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
E/ActivityThread( 3047): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
E/ActivityThread( 3047): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
E/ActivityThread( 3047): 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
E/ActivityThread( 3047): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
E/ActivityThread( 3047): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 3047): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 3047): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 3047): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 3047): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 3047): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 3047): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 3047): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3047): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3047): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3047): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Exchange( 3078): RestartPingTask
I/Exchange( 3078): RestartPingsTask did not start any pings.
I/Exchange( 3078): PSS stopIfIdle
I/Exchange( 3078): PSS has no active accounts; stopping service.
I/Exchange( 3078): onDestroy
I/ActivityManager(  824): Killing 1641:com.google.android.partnersetup/u0a16 (adj 15): empty #17
I/Gmail   ( 3047): notifyAccountChanged
I/Gmail   ( 3047): getAccountsCursor
I/Gmail   ( 3047): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 3047): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 3047): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 3047): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 3047): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
I/Gmail   ( 3047): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
I/Gmail   ( 3047): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
I/ActivityManager(  824): Killing 2563:com.android.settings/1000 (adj 15): empty #17
,I/Gmail   ( 3047): getAccountsCursor
V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3135): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3135): CheckJNI is OFF
I/ValidateNoPeople(  824): skipping global notification
W/VideoCapabilities( 3111): Unrecognized profile 2130706433 for video/avc
I/VideoCapabilities( 3111): Unsupported profile 4 for video/mp4v-es
D/AndroidRuntime( 3135): Calling main entry com.android.commands.am.Am
W/Bugle   ( 3111): PhoneUtils.getForLMR1(): invalid subId = -1
I/ActivityManager(  824): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/WindowManager(  824): addAppToken: AppWindowToken{e312255 token=Token{5cb390c ActivityRecord{34af2c3f u0 com.example.hello/.MainActivity t2}}} to stack=1 task=2 at 0
W/Bugle   ( 3111): PhoneUtils.getForLMR1(): invalid subId = -1
V/WindowManager(  824): Adding window Window{1f7cad36 u0 Starting com.example.hello} at 2 of 7 (after Window{363c6f2a u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
D/AndroidRuntime( 3135): Shutting down VM
I/HotwordDetector( 1520): Closing mic
I/MicrophoneInputStream( 1520): mic_close com.google.android.apps.gsa.speech.audio.u@6796b44
W/ResourcesManager( 3111): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  824): Start proc 3154:com.example.hello/u0a273 for activity com.example.hello/.MainActivity
D/GCM     ( 1260): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/Bugle   ( 3111): ApnsOta: OTA version -1
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
D/AuthorizationBluetoothService( 1260): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1520): Stopping hotword detection.
V/GmsCoreStatsServiceLauncher( 1780): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/HotwordRecognitionRnr( 1520): Hotword detection finished
I/WebViewFactory( 3154): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/BugleUsageStatistics( 3111): PlayLogger.onLoggerConnected
I/ActivityManager(  824): Start proc 3183:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
W/Bugle   ( 3111): PhoneUtils.getForLMR1(): invalid subId = -1
D/LocationInitializer( 1780): Restart initialization of location
I/LibraryLoader( 3154): Time to load native libraries: 5 ms (timestamps 6086-6091)
I/LibraryLoader( 3154): Expected native library version number "",actual native library version number ""
V/UserPresentBroadcastReceiver( 1802): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
I/art     ( 3111): Note: end time exceeds epoch: 
W/ResourcesManager( 3183): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3183): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/Bugle   ( 3111): PhoneUtils.getForLMR1(): invalid subId = -1
V/WebViewChromiumFactoryProvider( 3154): Binding Chromium to main looper Looper (main, tid 1) {1976d7d0}
I/LibraryLoader( 3154): Expected native library version number "",actual native library version number ""
I/chromium( 3154): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3154): Initializing chromium process, singleProcess=true
W/art     ( 3154): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3154): ApplicationContext is null in ApplicationStatus
W/chromium( 3154): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/Bugle   ( 3111): PhoneUtils.getForLMR1(): invalid subId = -1
I/BugleDataModel( 3111): Fixup: Send failed - 0 Download failed - 0
,W/chromium( 3154): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1658533139
E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,E/libEGL  ( 3154): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3154): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3154): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/ActivityManager(  824): Start proc 3210:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,I/ActivityManager(  824): Killing 2581:org.simalliance.openmobileapi.service/u0a23 (adj 15): empty #17
,I/MultiDex( 3183): VM with version 2.1.0 has multidex support
I/MultiDex( 3183): install
I/MultiDex( 3183): VM has multidex support, MultiDex support library is disabled.
,W/Bugle   ( 3111): PhoneUtils.getForLMR1(): invalid subId = -1
,W/Bugle   ( 3111): PhoneUtils.getForLMR1(): invalid subId = -1
,W/Bugle   ( 3111): PhoneUtils.getSelfRawNumber: subInfo is null for -1
,W/Bugle   ( 3111): PhoneUtils.getForLMR1(): invalid subId = -1
,D/BluetoothManagerService(  824): Message: 20
D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d07f5be:true
,W/Bugle   ( 3111): PhoneUtils.getForLMR1(): invalid subId = -1
,V/JNIHelp ( 3183): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/art     ( 3154): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3154): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3154): CordovaWebView is running on device made by: motorola
,W/art     ( 3154): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3154): Attempt to remove local handle scope entry from IRT, ignoring
I/ProviderInstaller( 3183): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 3183): callingUid 10011, callindPid: 3183
,I/art     (  824): Explicit concurrent mark sweep GC freed 13850(683KB) AllocSpace objects, 1(14KB) LOS objects, 32% free, 33MB/49MB, paused 1.540ms total 58.171ms
,D/OpenGLRenderer( 3154): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3154): Validating map...
,V/WindowManager(  824): Adding window Window{75de388 u0 com.example.hello/com.example.hello.MainActivity} at 2 of 8 (before Window{1f7cad36 u0 Starting com.example.hello})
I/ActivityManager(  824): Killing 2460:com.android.providers.calendar/u0a3 (adj 15): empty #17
,W/chromium( 3154): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/AuthorizationBluetoothService( 1260): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/MDM     ( 1802): [158] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/ActivityManager(  824): Waited long enough for: ServiceRecord{27449bb1 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,W/ContextImpl( 3210): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
W/Bugle   ( 3111): PhoneUtils.getForLMR1(): invalid subId = -1
,I/OpenGLRenderer( 3154): Initialized EGL, version 1.4
D/BluetoothManagerService(  824): Message: 20
D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@35a4a3d2:true
D/OpenGLRenderer( 3154): Enabling debug mode 0
,I/BugleDataModel( 3111): SyncMessagesAction: Starting batch for messages from 1457093804303 to 1457094139462 (message update limit = 80, message scan limit = 4000)
,D/LocalBluetoothProfileManager( 3210): Adding local A2DP profile
,D/BluetoothManagerService(  824): Message: 30
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 2357): getBluetoothService() called with no BluetoothManagerCallback
,I/ActivityManager(  824): Displayed com.example.hello/.MainActivity: +673ms
,D/AuthorizationBluetoothService( 1260): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 2357): getBluetoothService() called with no BluetoothManagerCallback
I/Keyboard.Facilitator( 1243): onFinishInput()
,I/BtOppRfcommListener( 2357): Accept thread started.
,D/LocalBluetoothProfileManager( 3210): Adding local HEADSET profile
D/BluetoothManagerService(  824): Message: 30
,D/BluetoothManagerService(  824): Message: 30
,W/BindingManager( 3154): Cannot call determinedVisibility() - never saw a connection for the pid: 3154
,I/ActivityManager(  824): Start proc 3271:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver
,D/BluetoothManagerService(  824): Message: 30
,I/chromium( 3154): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/LocalBluetoothProfileManager( 3210): Adding local MAP profile
D/BluetoothMap( 3210): Create BluetoothMap proxy object
D/BluetoothManagerService(  824): Message: 30
,D/BluetoothManagerService(  824): Message: 30
,I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 211us total 17.031ms
,D/LocalBluetoothProfileManager( 3210): LocalBluetoothProfileManager construction complete
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 197us total 10.075ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 200us total 8.519ms
,D/DockEventReceiver( 3210): finishStartingService: stopping service
,D/BluetoothA2dp( 3210): Proxy object connected
,D/A2dpProfile( 3210): Bluetooth service connected
,D/BluetoothInputDevice( 3210): Proxy object connected
D/HidProfile( 3210): Bluetooth service connected
,D/BluetoothPan( 3210): BluetoothPAN Proxy object connected
D/PanProfile( 3210): Bluetooth service connected
D/BluetoothMap( 3210): Proxy object connected
D/MapProfile( 3210): Bluetooth service connected
D/BluetoothMap( 3210): getConnectedDevices()
,D/BluetoothPbap( 3210): Proxy object connected
D/PbapServerProfile( 3210): Bluetooth service connected
,I/BugleDataModel( 3111): SyncMessagesAction: All messages now in sync
,I/ActivityManager(  824): Killing 2646:com.google.android.configupdater/u0a42 (adj 15): empty #17
,D/BluetoothManagerService(  824): Message: 400
,D/BluetoothHeadset( 3210): Proxy object connected
,D/HeadsetProfile( 3210): Bluetooth service connected
,D/JsMessageQueue( 3154): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 3154): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 3154): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1575602176
,W/jxcore-log( 3154): Initializing JXcore engine
W/jxcore-log( 3154): JXcore engine is ready
,W/Thread-337( 3292): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9462]" dev="sockfs" ino=9462 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-337( 3292): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-337( 3292): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[13148]" dev="sockfs" ino=13148 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-337( 3292): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20859]" dev="sockfs" ino=20859 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3154): Starting JXcore engine
,I/ConfigService( 1260): onDestroy
,W/jxcore-log( 3154): Platform android
W/jxcore-log( 3154): 
,W/jxcore-log( 3154): Process ARCH arm
W/jxcore-log( 3154): 
,I/jxcore-log( 3154): JXcore Cordova bridge is ready!
I/jxcore-log( 3154): 
W/jxcore-log( 3154): JXcore engine is started
,I/MusicStore( 3271): Database version: 120
,E/jxcore-log( 3154): >> motorola-Nexus 6
E/jxcore-log( 3154): 
,I/jxcore-log( 3154): Total memory 3113791488
I/jxcore-log( 3154): 
,I/jxcore-log( 3154): Free memory 1078390784
I/jxcore-log( 3154): 
I/jxcore-log( 3154): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3154): 
,I/jxcore-log( 3154): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3154): 
,I/jxcore-log( 3154): userPath [ 'www', 'www' ]
I/jxcore-log( 3154): 
,I/jxcore-log( 3154): Size 1440 2392
I/jxcore-log( 3154): 
,I/jxcore-log( 3154): Screen Brightness 82
I/jxcore-log( 3154): 
,E/jxcore-log( 3154): Dummy Error Log.
E/jxcore-log( 3154): 
,W/ResourcesManager( 3271): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3271): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/iu.UploadsManager( 1780): End new media; added: 0, uploading: 0, time: 54 ms
,V/JNIHelp ( 3271): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3271): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 3271): GMSCore installation verified
,I/ConfigStore( 3271): Config Database version: 1,
,I/art     ( 1260): Explicit concurrent mark sweep GC freed 11804(579KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 988us total 51.323ms
,I/jxcore-log( 3154): getBuffer is called!!!!
I/jxcore-log( 3154): 
,I/MediaRouter( 3271): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/GHttpClientFactory( 3271): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3271): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  824): Start proc 3311:com.android.providers.calendar/u0a3 for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,W/ResourcesManager( 3311): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3311): Created com.android.providers.calendar.CalendarAlarmManager@35c6bb93(com.android.providers.calendar.CalendarProvider2@1976d7d0)
,E/SQLiteLog( 3311): (284) automatic index on view_events(_id)
,I/art     (  824): Explicit concurrent mark sweep GC freed 5670(266KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.352ms total 72.056ms
,I/MediaStoreImporter( 3271): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  824): Killing 2702:com.google.android.keep/u0a79 (adj 15): empty #17
,I/ActivityManager(  824): Killing 2752:com.qualcomm.telephony/1001 (adj 15): empty #17
,D/GCM     ( 1260): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ChimeraCfgMgr( 1780): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1780): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/GCM     ( 1260): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1260): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1780): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1802): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1780): Restart initialization of location
,D/GCM     ( 1260): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1260): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 1780): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1802): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/NotifUtils( 3047): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,I/art     ( 1780): Explicit concurrent mark sweep GC freed 17094(1181KB) AllocSpace objects, 17(272KB) LOS objects, 36% free, 27MB/43MB, paused 1.298ms total 44.696ms
,D/LocationInitializer( 1780): Restart initialization of location
,I/ActivityManager(  824): Delay finish: com.google.android.gm/.widget.GmailWidgetProvider
,I/ActivityManager(  824): Resuming delayed broadcast
,I/NotifUtils( 3047): validateNotifications - cancelling 1729800001 for 61035162 / -317575340
,W/ResourcesManager( 2908): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2908): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2908): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 2908): Installed default security provider GmsCore_OpenSSL
,I/Babel_telephony( 2908): TeleIncomingWifiCallController.getRegistrationState, wifi calling not enabled
,W/VideoCapabilities( 2908): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2908): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2908): Unrecognized profile 2130706433 for video/avc
,I/Babel   ( 2908): connection state changed from UNKNOWN to DISCONNECTED
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CalendarProvider2( 3311): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3311): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/GAV2    ( 3047): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/Atfwd_Daemon(  375): result : 0 	 ,Init step :2 ,	 ,qmiErrorCode: 0
I/Atfwd_Daemon(  375): ATFWD --> QMI Port : rmnet_usb0
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 2984): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2984): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2984): [1] 5.onFinished: Scheduling replication attempt 1.
,I/Atfwd_Daemon(  375): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 486606848
I/Atfwd_Daemon(  375): Trying to register 8 commands:
I/Atfwd_Daemon(  375): cmd0: +CKPD
,I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): cmd1: +CTSA
,I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  375): cmd2: +CFUN
,I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  375): cmd3: +CMAR
,I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): cmd4: +CDIS
,I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): cmd5: +CRSL
,I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  375): cmd6: +CSS
,I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  375): cmd7: $QCPWRDN
,I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  375): Registered AT Commands event handler
,I/InputReader(  824): Reconfiguring input devices.  changes=0x00000010
,D/PackageBroadcastService( 1780): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1780): Null package name or gms related package.  Ignoreing.
I/UpdateIcingCorporaServi( 1520): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 1780): updateResources: need to parse f{com.google.android.gms}
,W/Launcher( 1337): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@24080a0b new=com.google.android.velvet.VelvetApplication@24080a0b
,I/ActivityManager(  824): Start proc 3375:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/BackupManagerService(  824): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  824): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  824): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  824): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  824): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1cfbf22f
,W/ResourcesManager( 3375): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/GmsNetworkLocationProvi( 1802): DISABLE
,I/UpdateIcingCorporaServi( 1520): UpdateCorporaTask done [took 127 ms] updated apps [took 127 ms] 
,I/art     ( 1802): Explicit concurrent mark sweep GC freed 15121(864KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 841us total 27.333ms
I/Launcher( 1337): Deferring update until onResume
,E/DataBuffer( 1802): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1c9394d9)
,V/GmsNetworkLocationProvi( 1802): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,V/GmsNetworkLocationProvi( 1802): ENABLE
,V/GmsNetworkLocationProvi( 1802): SET-REQUEST
V/GmsNetworkLocationProvi( 1802): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  824): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@116e76a5 mBinding = false
,D/BluetoothManagerService(  824): Message: 2,
,D/BluetoothManagerService(  824): Sending off request.
,D/BluetoothAdapterState( 2357): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2357): Setting state to 13
I/BluetoothAdapterState( 2357): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 2357): onBluetoothDisable()
I/BluetoothAdapterState( 2357): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothManagerService(  824): Message: 60,
D/BluetoothManagerService(  824): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  824): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothAdapterProperties( 2357): Scan Mode:20
D/BluetoothAdapterState( 2357): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/btif_config_util( 2357): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
E/BtOppRfcommListener( 2357): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 2357): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 2357): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2357): L2CAP - PSM: 0x0017 not found for deregistration
V/BluetoothMapMasInstance( 2357): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2357): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2357): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2357): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2357): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2357): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2357): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2357): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,D/WifiService(  824): New client listening to asynchronous messages
D/BluetoothMapService( 2357): onReceive
D/BluetoothMapService( 2357): STATE_TURNING_OFF
D/WifiService(  824): setWifiEnabled: false pid=3154, uid=10273
E/WifiService(  824): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothMapService( 2357): MAP Service closeService in
D/BluetoothMapMasInstance( 2357): MAP Service shutdown
I/BtOppRfcommListener( 2357): stopping Accept Thread
I/BtOppRfcommListener( 2357): BluetoothSocket listen thread finished
,W/ContextImpl( 3210): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/jxcore-log( 3154): ****TEST TOOK:  5112  ms ****
I/jxcore-log( 3154): 
I/jxcore-log( 3154): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3154): 
,E/WifiStateMachine(  824): scanCount==0 - aborting
D/WifiScanningService(  824): SCAN_AVAILABLE : 1
D/RttService(  824): SCAN_AVAILABLE : 1
D/WifiScanningService(  824): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  824): DefaultState
D/RttService(  824): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  354): Clearing all IP addresses on wlan0
D/DockEventReceiver( 3210): finishStartingService: stopping service
D/BluetoothPbap( 3210): Proxy object disconnected
D/PbapServerProfile( 3210): Bluetooth service disconnected
D/AuthorizationBluetoothService( 1260): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/WifiStateMachine(  824): SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown,
,I/ActivityManager(  824): Start proc 3408:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,I/wpa_supplicant( 1151): p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  824): Waited long enough for: ServiceRecord{c3bddc u0 org.simalliance.openmobileapi.service/.SmartcardService}
,W/bt-btif ( 2357): ag scb idx 1 not allocated
E/bt-btif ( 2357): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2357): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2357): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2357): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2357): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2357): L2CAP - PSM: 0x0019 not found for deregistration
D/bt_userial( 2357): RX termination
W/bt-l2cap( 2357): L2CAP - PSM: 0x0017 not found for deregistration
W/bt_userial( 2357): select_read return size <=0:-1, exiting userial_read_thread,
D/bt_userial( 2357): Leaving userial_read_thread()
D/bt_userial( 2357): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 2357): hw_epilog_process
I/bt_userial_vendor( 2357): device fd = 53 close
,I/wpa_supplicant( 1151): wlan0: CTRL-EVENT-TERMINATING 
I/ActivityManager(  824): Start proc 3437:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
D/Tethering(  824): InitialState.processMessage what=4
,D/AndroidRuntime( 3425): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,E/WifiMonitor(  824): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
D/AndroidRuntime( 3425): CheckJNI is OFF
I/ActivityManager(  824): Killing 2093:com.android.defcontainer/u0a7 (adj 15): empty #17
,I/GKI_LINUX( 2357): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2357): GKI_exit_task 0 done
I/GKI_LINUX( 2357): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 2357): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/Tethering(  824): sendTetherStateChangedBroadcast 0, 0, 0
,D/AndroidRuntime( 3425): Calling main entry com.android.commands.pm.Pm
,W/Settings( 2908): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1802): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  824): Force stopping com.example.hello appid=10273 user=-1: uninstall pkg
,I/ActivityManager(  824): Killing 3154:com.example.hello/u0a273 (adj 0): stop com.example.hello
,D/HeadsetService( 2357): Received stop request...Stopping profile...
,W/PackageSettings(  824): Skipping PackageSetting{3d11d27f com.test.thalitest/10265} due to missing metadata
,I/WindowState(  824): WIN DEATH: Window{75de388 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  824): Client connection lost with reason: 4
,W/ActivityManager(  824): Force removing ActivityRecord{34af2c3f u0 com.example.hello/.MainActivity t2}: app died, no saved state
,D/HeadsetStateMachine( 2357): Exit Disconnected: -1
,W/ActivityManager(  824): Spurious death for ProcessRecord{35ae9607 3154:com.example.hello/u0a273}, curProc for 3154: null
,I/ActivityManager(  824): Force stopping com.example.hello appid=10273 user=0: pkg removed
D/BluetoothAdapterState( 2357): Stopping profile services that were post enabled
,D/BluetoothHeadset( 1318): Proxy object disconnected
D/A2dpService( 2357): Received stop request...Stopping profile...
,D/A2dpStateMachine( 2357): Exit Disconnected: -1
,D/BluetoothHeadset( 1073): Proxy object disconnected
,D/BluetoothHeadset( 3210): Proxy object disconnected
,D/BluetoothHeadset(  824): Proxy object disconnected
D/BluetoothHeadset(  824): Proxy object disconnected
D/BluetoothHeadset(  824): Proxy object disconnected
D/HeadsetProfile( 3210): Bluetooth service disconnected
,I/InputReader(  824): Reconfiguring input devices.  changes=0x00000010
,D/BluetoothA2dp( 3210): Proxy object disconnected
D/A2dpProfile( 3210): Bluetooth service disconnected
,I/Keyboard.Facilitator( 1243): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1243): run()
,I/Decoder ( 1243): createOrResetDecoder
,D/HidService( 2357): Received stop request...Stopping profile...
,D/HealthService( 2357): Received stop request...Stopping profile...
D/TaskPersister(  824): removeObsoleteFile: deleting file=2_task.xml
,I/art     ( 1073): Explicit concurrent mark sweep GC freed 8073(372KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 56MB/72MB, paused 2.165ms total 39.951ms
,D/PanService( 2357): Received stop request...Stopping profile...
,D/BluetoothInputDevice( 3210): Proxy object disconnected
D/HidProfile( 3210): Bluetooth service disconnected
,D/BluetoothA2dp( 1073): Proxy object disconnected
D/BluetoothInputDevice( 1073): Proxy object disconnected
,D/BtGatt.DebugUtils( 2357): handleDebugAction() action=null
,D/BluetoothPan( 1073): BluetoothPAN Proxy object disconnected
,D/JobSchedulerService(  824): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  824): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/BluetoothPan( 3210): BluetoothPAN Proxy object disconnected
D/PanProfile( 3210): Bluetooth service disconnected
,D/BluetoothA2dp(  824): Proxy object disconnected
,D/BtGatt.GattService( 2357): Received stop request...Stopping profile...
D/BtGatt.GattService( 2357): stop()
D/BtGatt.AdvertiseManager( 2357): advertise clients cleared
,I/art     (  824): Explicit concurrent mark sweep GC freed 32124(1923KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 1.356ms total 74.540ms
I/art     (  824): WaitForGcToComplete blocked for 71.748ms for cause Explicit
,I/art     ( 3425): System.exit called, status: 0
I/AndroidRuntime( 3425): VM exiting with result code 0.
,I/art     (  824): Explicit concurrent mark sweep GC freed 3743(203KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.984ms total 76.852ms
,I/ConfigService( 1260): onCreate
,D/HeadsetStateMachine( 2357): Unbinding service...
,W/BluetoothHeadsetServiceJni( 2357): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2357): Cleaning up Bluetooth Handsfree callback object
,D/BluetoothMapService( 2357): Received stop request...Stopping profile...
D/BluetoothMapService( 2357): stop()
D/BluetoothMapEmailAppObserver( 2357): deinitObservers()
D/BluetoothMapEmailAppObserver( 2357): removeReceiver()
D/BluetoothMap( 1073): Proxy object disconnected
I/GKI_LINUX( 2357): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2357): GKI_exit_task 2 done
I/GKI_LINUX( 2357): GKI_shutdown(): task [A2DP-MEDIA] terminated
,W/BluetoothHidServiceJni( 2357): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2357): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2357): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 2357): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2357): Cleaning up Bluetooth Health object
,W/BluetoothPanServiceJni( 2357): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2357): Cleaning up Bluetooth PAN callback object
,D/BluetoothMapService( 2357): MAP Service closeService in
D/BluetoothMapService( 2357): cleanup()
,D/BluetoothMapService( 2357): MAP Service closeService in
D/BluetoothAdapterState( 2357): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2357): Setting state to 10
I/BluetoothAdapterState( 2357): Bluetooth adapter state changed: 13-> 10,
,D/BluetoothManagerService(  824): Message: 60
D/BluetoothManagerService(  824): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  824): Broadcasting onBluetoothStateChange(false) to 19 receivers.
D/BluetoothA2dp( 3210): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 2357): Entering OffState
,I/ActivityManager(  824): Waited long enough for: ServiceRecord{22a29d3f u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
D/BluetoothHeadset(  824): onBluetoothStateChange: up=false
D/BluetoothHeadset(  824): onBluetoothStateChange: up=false
D/BluetoothMap( 3210): onBluetoothStateChange: up=false
D/BluetoothHeadset( 3210): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  824): onBluetoothStateChange: up=false
D/BluetoothAvrcpController( 1073): onBluetoothStateChange: up=false
E/BluetoothAvrcpController( 1073): 
E/BluetoothAvrcpController( 1073): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothAvrcpController$2@347cd222
E/BluetoothAvrcpController( 1073): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothAvrcpController( 1073): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothAvrcpController( 1073): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothAvrcpController( 1073): 	at android.bluetooth.BluetoothAvrcpController$1.onBluetoothStateChange(BluetoothAvrcpController.java:80)
E/BluetoothAvrcpController( 1073): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothAvrcpController( 1073): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothA2dp( 1073): onBluetoothStateChange: up=false
,D/BluetoothMap( 3210): Proxy object disconnected
D/MapProfile( 3210): Bluetooth service disconnected
D/BluetoothA2dp(  824): onBluetoothStateChange: up=false
,D/BluetoothPbap( 3210): onBluetoothStateChange: up=false
,D/BluetoothHeadsetClient( 1073): onBluetoothStateChange: up=false
E/BluetoothHeadsetClient( 1073): 
E/BluetoothHeadsetClient( 1073): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothHeadsetClient$2@97804b3
E/BluetoothHeadsetClient( 1073): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothHeadsetClient( 1073): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothHeadsetClient( 1073): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothHeadsetClient( 1073): 	at android.bluetooth.BluetoothHeadsetClient$1.onBluetoothStateChange(BluetoothHeadsetClient.java:382)
E/BluetoothHeadsetClient( 1073): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothHeadsetClient( 1073): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothInputDevice( 1073): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1318): onBluetoothStateChange: up=false
,D/BluetoothA2dpSink( 1073): onBluetoothStateChange: up=false
E/BluetoothA2dpSink( 1073): 
E/BluetoothA2dpSink( 1073): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dpSink$2@2efaba70
E/BluetoothA2dpSink( 1073): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dpSink( 1073): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dpSink( 1073): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothA2dpSink( 1073): 	at android.bluetooth.BluetoothA2dpSink$1.onBluetoothStateChange(BluetoothA2dpSink.java:139)
E/BluetoothA2dpSink( 1073): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothA2dpSink( 1073): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothHeadset( 1073): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 3210): onBluetoothStateChange: up=false
,D/BluetoothMap( 1073): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  824): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  824): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService(  824): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@116e76a5 mBinding = false
,D/BluetoothManagerService(  824): Sending unbind request.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1243): run()
,D/BluetoothManagerService(  824): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter( 1073): 23888954: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1073): 23888954: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1073): 23888954: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 2357): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2357): GKI_exit_task 1 done
I/GKI_LINUX( 2357): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2357): cleanupNative: return from cleanup
,I/art     ( 2357): System.exit called, status: 0
I/AndroidRuntime( 2357): VM exiting with result code 0, cleanup skipped.
,W/InputMethodManagerService(  824): Got RemoteException sending setActive(false) notification to pid 3154 uid 10273
,I/Keyboard.Facilitator( 1243): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1243): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1243): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1243): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1243): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1243): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1243): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1243): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1243): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1243): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1243): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1243): run()
I/StatsUtilsManager( 1243): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1243): shouldRecordStats() = Too Soon
,I/ActivityManager(  824): Process com.android.bluetooth (pid 2357) has died
,W/LocationOracleImpl( 1520): Best location was null
,W/ErrorReporter( 1520): reportError [type: 29, code: 917507]: null
,E/SQLiteLog( 1260): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/ClearcutLoggerIntentService( 1260): disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1260): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1260): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1260): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1260): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1260): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1260): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1260): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1260): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1260): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/ClearcutLoggerIntentService( 1260): disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1260): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1260): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1260): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1260): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1260): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1260): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1260): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1260): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1260): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/ClearcutLoggerIntentService( 1260): disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1260): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1260): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1260): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1260): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1260): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1260): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1260): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1260): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1260): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/ClearcutLoggerIntentService( 1260): disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1260): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1260): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1260): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1260): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1260): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1260): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1260): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1260): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1260): 	at java.lang.Thread.run(Thread.java:818)
,I/HotwordRecognitionRnr( 1520): Starting hotword detection.
,I/MicrophoneInputStream( 1520): mic_starting com.google.android.apps.gsa.speech.audio.u@34da7ae2
,I/AudioFlinger(  358): AudioFlinger's thread 0xb4e19000 ready to run
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1520): mic_started com.google.android.apps.gsa.speech.audio.u@34da7ae2
,D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
,W/FileUtils( 1520): Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/FileBytesWriter( 1520): Failed to write new file: loracle.new
,D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
,E/Search.SharedPreferencesProto( 1520): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/art     ( 1260): Explicit concurrent mark sweep GC freed 22666(1106KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.240ms total 50.373ms
,W/FileUtils( 1520): Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/FileBytesWriter( 1520): Failed to write new file: loracle.new
,D/Launcher.Workspace( 1337): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1337): 11683562 - stripEmptyScreens()
,E/SQLiteLog( 1337): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,I/HotwordWorker( 1520): onReady
,E/SQLiteLog( 3437): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 3437): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/Process ( 3437): Sending signal. PID: 3437 SIG: 9
,E/QMI_FW  (  824): xport_send: Sendto failed for port 4352
E/LocSvc_api_v02(  824): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1658533139
E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  824): Process com.google.android.keep (pid 3437) has died
W/ActivityManager(  824): Scheduling restart of crashed service com.google.android.keep/.notification.AlertService in 1000ms
,I/MusicLeanback( 3271): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3271): Stop autocaching.
,D/BuaReceiver( 2168): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,E/SQLiteLog( 1441): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/VoicemailCleanupService( 1441): Cleaning up data for package: com.example.hello
,--------- beginning of crash
E/AndroidRuntime( 1441): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 1441): Process: android.process.acore, PID: 1441
E/AndroidRuntime( 1441): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1441): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1441): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1441): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1441): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1441): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1441): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1441): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
E/AndroidRuntime( 1441): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
E/AndroidRuntime( 1441): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1706)
E/AndroidRuntime( 1441): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 1441): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1441): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1441): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 1441): (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.example.hello'))) AND ((type = 4))] disk I/O error
I/Process ( 1441): Sending signal. PID: 1441 SIG: 9
,I/ActivityManager(  824): Start proc 3504:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,E/lowmemorykiller(  256): Error writing /proc/1441/oom_score_adj; errno=22
,E/lowmemorykiller(  256): Error writing /proc/1441/oom_score_adj; errno=22
,E/DropBoxManagerService(  824): Can't write: system_app_crash
E/DropBoxManagerService(  824): java.io.FileNotFoundException: /data/system/dropbox/drop94.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  824): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  824): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  824): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  824): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  824): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  824): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  824): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  824): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  824): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  824): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  824): 	... 5 more
,D/OpenGLRenderer(  824): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   (  824): Validating map...
,I/ActivityManager(  824): Process android.process.acore (pid 1441) has died
W/ActivityManager(  824): Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 10867ms
W/FileUtils( 3183): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,W/ServiceConnection( 3183): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/service.connections: open failed: EROFS (Read-only file system)
W/ServiceConnection( 3183): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/ServiceConnection( 3183): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/ServiceConnection( 3183): 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:982)
W/ServiceConnection( 3183): 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:182)
W/ServiceConnection( 3183): 	at com.google.android.gms.common.internal.cm.b(SourceFile:80)
W/ServiceConnection( 3183): 	at com.google.android.gms.common.internal.cm.a(SourceFile:27)
W/ServiceConnection( 3183): 	at com.google.android.gms.common.internal.cn.run(SourceFile:64)
W/ServiceConnection( 3183): 	at java.lang.Thread.run(Thread.java:818)
W/ServiceConnection( 3183): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/ServiceConnection( 3183): 	at libcore.io.Posix.open(Native Method)
W/ServiceConnection( 3183): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/ServiceConnection( 3183): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/ServiceConnection( 3183): 	... 7 more
,W/FileUtils( 3183): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
W/ServiceConnection( 3183): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/service.connections: open failed: EROFS (Read-only file system)
W/ServiceConnection( 3183): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/ServiceConnection( 3183): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/ServiceConnection( 3183): 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:982)
W/ServiceConnection( 3183): 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:182)
W/ServiceConnection( 3183): 	at com.google.android.gms.common.internal.cm.b(SourceFile:80)
W/ServiceConnection( 3183): 	at com.google.android.gms.common.internal.cm.a(SourceFile:27)
W/ServiceConnection( 3183): 	at com.google.android.gms.common.internal.cn.run(SourceFile:64)
W/ServiceConnection( 3183): 	at java.lang.Thread.run(Thread.java:818)
W/ServiceConnection( 3183): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/ServiceConnection( 3183): 	at libcore.io.Posix.open(Native Method)
W/ServiceConnection( 3183): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/ServiceConnection( 3183): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/ServiceConnection( 3183): 	... 7 more
,E/GmsUtils( 3271): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 3271): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/Adreno  (  824): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/OpenGLRenderer(  824): Initialized EGL, version 1.4
,D/OpenGLRenderer(  824): Enabling debug mode 0
,I/ActivityManager(  824): Start proc 3528:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,W/InputMethodManagerService(  824): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@2b5b85d9 attribute=null, token = android.os.BinderProxy@3db51015
,E/qdoverlay(  259): Bad ov dump:  mdp_overlay z=1 fg=0 alpha=255 mask=-1 flags=0x60200 id=8
E/qdoverlay(  259): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
E/qdoverlay(  259): src_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  259): dst_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  259): Bad ov dump:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  259): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
E/qdoverlay(  259): src_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  259): dst_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  259): Bad ov dump:  mdp_overlay z=1 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  259): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
E/qdoverlay(  259): src_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  259): dst_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  259): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  259): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
E/qdoverlay(  259): src_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  259): dst_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  259): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  259): MdpCtrl close error in unset
,W/OpenGLRenderer( 1337): Incorrectly called buildLayer on View: ew, destroying layer...
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
E/qdoverlay(  259): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  259): MdpCtrl close error in unset
E/qdoverlay(  259): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  259): MdpCtrl close error in unset
E/qdoverlay(  259): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  259): MdpCtrl close error in unset
E/qdoverlay(  259): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  259): MdpCtrl close error in unset
E/qdoverlay(  259): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  259): MdpCtrl close error in unset
E/qdoverlay(  259): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  259): MdpCtrl close error in unset
E/qdoverlay(  259): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  259): MdpCtrl close error in unset

```
