#### Test 50242285e132180_thali05_motorola-Nexus 6 Logs


```
--------- beginning of system
W/ResourcesManager( 3017): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3017): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
--------- beginning of main
I/MultiDex( 3017): VM with version 2.1.0 has multidex support
I/MultiDex( 3017): install
I/MultiDex( 3017): VM has multidex support, MultiDex support library is disabled.
D/Volley  ( 2981): [296] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 2981): [303] DiskBasedCache.clear: Cache cleared.
I/ActivityManager(  821): Start proc 3044:com.google.android.gm/u0a78 for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver
I/ActivityManager(  821): Killing 2491:com.google.android.onetimeinitializer/u0a15 (adj 15): empty #17
,D/Finsky  ( 2981): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 2981): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 2981): [1] GmsCoreHelper.cleanupNlp: result=false type=4
V/JNIHelp ( 3017): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/Finsky  ( 2981): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ProviderInstaller( 3017): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 3061): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3061): CheckJNI is OFF
I/ActivityManager(  821): Killing 2515:com.android.managedprovisioning/u0a17 (adj 15): empty #17
D/AndroidRuntime( 3061): Calling main entry com.android.commands.am.Am
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{f7f5416 token=Token{33ca0531 ActivityRecord{2c58add8 u0 com.example.hello/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3061): Shutting down VM
V/WindowManager(  821): Adding window Window{227dd033 u0 Starting com.example.hello} at 3 of 8 (after Window{30a7ad2c u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/HotwordDetector( 1531): Closing mic
I/MicrophoneInputStream( 1531): mic_close com.google.android.apps.gsa.speech.audio.u@18877267
I/Gmail   ( 3044): getAccountsCursor
I/ActivityManager(  821): Start proc 3087:com.example.hello/u0a272 for activity com.example.hello/.MainActivity
D/ActivityThread( 3044): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
V/GLSActivity( 1500): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
V/Finsky  ( 2981): [1] GearheadStateMonitor.onReady: sIsProjecting:false
I/HotwordRecognitionRnr( 1531): Hotword detection finished
I/HotwordRecognitionRnr( 1531): Stopping hotword detection.
I/art     (  821): Explicit concurrent mark sweep GC freed 12795(633KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 32MB/48MB, paused 957us total 50.477ms
I/ActivityManager(  821): Start proc 3109:com.google.android.gm.exchange/u0a77 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
W/GCoreFlp( 1759): No location to return for getLastLocation()
I/ActivityManager(  821): Killing 1600:com.google.android.partnersetup/u0a16 (adj 15): empty #17
I/WebViewFactory( 3087): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/ActivityManager(  821): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/LibraryLoader( 3087): Time to load native libraries: 2 ms (timestamps 4831-4833)
I/LibraryLoader( 3087): Expected native library version number "",actual native library version number ""
I/Gmail   ( 3044): Observing account changes for notifications
V/WebViewChromiumFactoryProvider( 3087): Binding Chromium to main looper Looper (main, tid 1) {2077ffcc}
I/LibraryLoader( 3087): Expected native library version number "",actual native library version number ""
I/chromium( 3087): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/Exchange( 3109): EasService.onCreate
I/Exchange( 3109): RestartPingTask
W/GAV2    ( 3044): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/BrowserStartupController( 3087): Initializing chromium process, singleProcess=true
W/art     ( 3087): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3087): ApplicationContext is null in ApplicationStatus
W/chromium( 3087): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3087): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659516179
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
E/libEGL  ( 3087): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3087): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3087): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
I/Exchange( 3109): RestartPingsTask did not start any pings.
I/Exchange( 3109): PSS stopIfIdle
I/Exchange( 3109): PSS has no active accounts; stopping service.
I/Gmail   ( 3044): getAccountsCursor
V/GLSActivity( 1500): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SystemBroadcastReceiver( 1221): Boot has been completed
I/SystemBroadcastReceiver( 1221): toggleAppIcon() : FLAG_SYSTEM = true
V/GLSActivity( 1500): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  821): Start proc 3152:com.google.android.apps.messaging/u0a75 for broadcast com.google.android.apps.messaging/.receiver.BootAndPackageReplacedReceiver
D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1019c0b2:true
D/BluetoothAdapter( 3087): 763357841: getState() :  mService = null. Returning STATE_OFF
W/art     ( 3087): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3087): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3087): CordovaWebView is running on device made by: motorola
W/art     ( 3087): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3087): Attempt to remove local handle scope entry from IRT, ignoring
E/SQLiteLog( 3044): (283) recovered 60 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
D/OpenGLRenderer( 3087): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3087): Validating map...
V/WindowManager(  821): Adding window Window{2e1fba62 u0 com.example.hello/com.example.hello.MainActivity} at 3 of 9 (before Window{227dd033 u0 Starting com.example.hello})
W/chromium( 3087): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3087): Initialized EGL, version 1.4
D/OpenGLRenderer( 3087): Enabling debug mode 0
I/Gmail   ( 3044): notifyAccountChanged
I/Keyboard.Facilitator( 1221): onFinishInput()
I/ActivityManager(  821): Displayed com.example.hello/.MainActivity: +616ms (total +21s823ms)
W/BindingManager( 3087): Cannot call determinedVisibility() - never saw a connection for the pid: 3087
I/Gmail   ( 3044): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/chromium( 3087): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/Gmail   ( 3044): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
I/Gmail   ( 3044): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 3044): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
I/Gmail   ( 3044): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
I/Gmail   ( 3044): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 3044): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ActivityManager(  821): Killing 2536:com.android.settings/1000 (adj 15): empty #17
D/JsMessageQueue( 3087): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 3087): Unable to open asset URL: file:///android_asset/www/jxcore.js
V/GLSActivity( 1500): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/jxcore_app_log( 3087): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576511360
D/JX-Cordova( 3087): jxcore cordova android initializing
I/Gmail   ( 3044): getAccountsCursor
V/GLSActivity( 1500): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 3044): getAccountsCursor
V/GLSActivity( 1500): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/jxcore-log( 3087): Initializing JXcore engine
W/jxcore-log( 3087): JXcore engine is ready
W/jxcore-log( 3087): Starting JXcore engine
W/VideoCapabilities( 3152): Unrecognized profile 2130706433 for video/avc
I/VideoCapabilities( 3152): Unsupported profile 4 for video/mp4v-es
W/m.example.hello( 3087): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9591]" dev="sockfs" ino=9591 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3087): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 3087): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10713]" dev="sockfs" ino=10713 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3087): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19126]" dev="sockfs" ino=19126 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/Bugle   ( 3152): PhoneUtils.getForLMR1(): invalid subId = -1
W/Bugle   ( 3152): PhoneUtils.getForLMR1(): invalid subId = -1
W/ResourcesManager( 3152): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/GCM     ( 1500): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1500): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/Bugle   ( 3152): ApnsOta: OTA version -1
V/GmsCoreStatsServiceLauncher( 1794): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
W/Bugle   ( 3152): PhoneUtils.getForLMR1(): invalid subId = -1
I/art     ( 3152): Note: end time exceeds epoch: 
I/BugleUsageStatistics( 3152): PlayLogger.onLoggerConnected
W/Bugle   ( 3152): PhoneUtils.getForLMR1(): invalid subId = -1
W/Bugle   ( 3152): PhoneUtils.getForLMR1(): invalid subId = -1
I/ActivityManager(  821): Start proc 3208:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
W/jxcore-log( 3087): Platform android
W/jxcore-log( 3087): 
W/jxcore-log( 3087): Process ARCH arm
W/jxcore-log( 3087): 
D/LocationInitializer( 1794): Restart initialization of location
V/UserPresentBroadcastReceiver( 1759): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
I/BugleDataModel( 3152): Fixup: Send failed - 0 Download failed - 0
W/ResourcesManager( 3208): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3208): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/jxcore-log( 3087): JXcore Cordova bridge is ready!
I/jxcore-log( 3087): 
W/jxcore-log( 3087): JXcore engine is started
E/jxcore-log( 3087): >> motorola-Nexus 6
E/jxcore-log( 3087): 
I/jxcore-log( 3087): Total memory 3113791488
I/jxcore-log( 3087): 
I/jxcore-log( 3087): Free memory 1026936832
I/jxcore-log( 3087): 
I/jxcore-log( 3087): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3087): 
I/jxcore-log( 3087): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3087): 
E/DataBuffer( 1759): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3f3bd084)
I/MultiDex( 3208): VM with version 2.1.0 has multidex support
I/MultiDex( 3208): install
I/art     ( 1759): Explicit concurrent mark sweep GC freed 13638(775KB) AllocSpace objects, 5(80KB) LOS objects, 37% free, 26MB/42MB, paused 20.090ms total 59.155ms
I/MultiDex( 3208): VM has multidex support, MultiDex support library is disabled.
I/jxcore-log( 3087): userPath [ 'www' ]
I/jxcore-log( 3087): 
I/jxcore-log( 3087): Size 1440 2392
I/jxcore-log( 3087): 
I/jxcore-log( 3087): Screen Brightness 82
I/jxcore-log( 3087): 
E/jxcore-log( 3087): Dummy Error Log.
E/jxcore-log( 3087): 
W/Bugle   ( 3152): PhoneUtils.getForLMR1(): invalid subId = -1
I/art     (  821): Explicit concurrent mark sweep GC freed 10156(514KB) AllocSpace objects, 1(14KB) LOS objects, 32% free, 32MB/48MB, paused 941us total 53.254ms
I/ActivityManager(  821): Start proc 3232:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver
V/JNIHelp ( 3208): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ProviderInstaller( 3208): Installed default security provider GmsCore_OpenSSL
D/WearableService( 3208): callingUid 10011, callindPid: 3208
W/Bugle   ( 3152): PhoneUtils.getForLMR1(): invalid subId = -1
W/Bugle   ( 3152): PhoneUtils.getForLMR1(): invalid subId = -1
W/Bugle   ( 3152): PhoneUtils.getSelfRawNumber: subInfo is null for -1
W/Bugle   ( 3152): PhoneUtils.getForLMR1(): invalid subId = -1
E/MDM     ( 1759): [153] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
W/Bugle   ( 3152): PhoneUtils.getForLMR1(): invalid subId = -1
I/BugleDataModel( 3152): SyncMessagesAction: Starting batch for messages from 1449499030229 to 1449501111210 (message update limit = 80, message scan limit = 4000)
I/BugleDataModel( 3152): SyncMessagesAction: All messages now in sync
I/ActivityManager(  821): Killing 2558:org.simalliance.openmobileapi.service/u0a23 (adj 15): empty #17
,I/jxcore-log( 3087): getBuffer is called!!!!
I/jxcore-log( 3087): 
I/MusicStore( 3232): Database version: 120
I/art     ( 1500): Explicit concurrent mark sweep GC freed 11768(570KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.215ms total 50.417ms
W/ResourcesManager( 3232): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3232): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 3232): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ProviderInstaller( 3232): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3232): GMSCore installation verified
I/ConfigStore( 3232): Config Database version: 1
I/MediaRouter( 3232): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
I/ActivityManager(  821): Waited long enough for: ServiceRecord{a6cf6e u0 com.motorola.android.buacontactadapter/.AuthenticationService}
I/GHttpClientFactory( 3232): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 3232): Using platform SSLCertificateSocketFactory
,E/SQLiteLog( 2440): (284) automatic index on view_events(_id)
,D/GCM     ( 1500): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ChimeraCfgMgr( 1794): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 1794): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Kids    ( 1794): [KidAccountFixer] No network connection
I/ConfigService( 1500): onDestroy
D/GCM     ( 1500): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1500): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 1794): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1759): [135] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1794): Restart initialization of location
,I/MediaStoreImporter( 3232): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/art     ( 1794): Explicit concurrent mark sweep GC freed 19740(1389KB) AllocSpace objects, 25(400KB) LOS objects, 36% free, 27MB/43MB, paused 988us total 33.872ms
,D/GCM     ( 1500): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1500): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1794): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1759): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1794): Restart initialization of location
,I/iu.UploadsManager( 1794): End new media; added: 0, uploading: 0, time: 38 ms
,I/NotifUtils( 3044): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,I/NotifUtils( 3044): validateNotifications - cancelling 1729800001 for 61035162 / -317575340
,W/ResourcesManager( 2885): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2885): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2885): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 2885): Installed default security provider GmsCore_OpenSSL
,I/Babel_telephony( 2885): TeleIncomingWifiCallController.getRegistrationState, wifi calling not enabled
,W/VideoCapabilities( 2885): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2885): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2885): Unrecognized profile 2130706433 for video/avc
,I/Babel   ( 2885): connection state changed from UNKNOWN to DISCONNECTED
,V/GLSActivity( 1500): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAV2    ( 3044): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 1500): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 14712(762KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 32MB/48MB, paused 1.505ms total 84.589ms
,I/GLSUser ( 1500): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1500): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1500): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1500): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1500): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2981): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2981): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2981): [1] 5.onFinished: Scheduling replication attempt 1.
,I/Atfwd_Daemon(  376): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
I/Atfwd_Daemon(  376): ATFWD --> QMI Port : rmnet_usb0
,I/Atfwd_Daemon(  376): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 486606848,
I/Atfwd_Daemon(  376): Trying to register 8 commands:
I/Atfwd_Daemon(  376): cmd0: +CKPD
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0,
I/Atfwd_Daemon(  376): cmd1: +CTSA
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  376): cmd2: +CFUN
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  376): cmd3: +CMAR
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0,
I/Atfwd_Daemon(  376): cmd4: +CDIS
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0,
I/Atfwd_Daemon(  376): cmd5: +CRSL
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): cmd6: +CSS,
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  376): cmd7: $QCPWRDN
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  376): Registered AT Commands event handler
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  821): Message: 2
,D/WifiService(  821): setWifiEnabled: false pid=3087, uid=10272,
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  821): New client listening to asynchronous messages
,I/jxcore-log( 3087): ****TEST TOOK:  5040  ms ****
I/jxcore-log( 3087): 
,I/jxcore-log( 3087): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3087): 
,D/AndroidRuntime( 3314): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 3314): CheckJNI is OFF
,I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
,D/PackageBroadcastService( 1794): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1794): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 1531): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1326): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@23085f7 new=com.google.android.velvet.VelvetApplication@23085f7
,I/Icing   ( 1794): updateResources: need to parse f{com.google.android.gms}
,D/AndroidRuntime( 3314): Calling main entry com.android.commands.pm.Pm
,I/UpdateIcingCorporaServi( 1531): UpdateCorporaTask done [took 48 ms] updated apps [took 48 ms] 
,I/ActivityManager(  821): Start proc 3335:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  821): Force stopping com.example.hello appid=10272 user=-1: uninstall pkg
I/ActivityManager(  821): Killing 3087:com.example.hello/u0a272 (adj 0): stop com.example.hello
,I/art     (  370): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 213us total 9.629ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 247us total 8.992ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 193us total 8.344ms
,W/PackageSettings(  821): Skipping PackageSetting{3b9cab com.test.thalitest/10265} due to missing metadata
,D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  821): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,I/WindowState(  821): WIN DEATH: Window{2e1fba62 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  821): Client connection lost with reason: 4
,W/ActivityManager(  821): Force removing ActivityRecord{2c58add8 u0 com.example.hello/.MainActivity t24}: app died, no saved state
,I/ActivityManager(  821): Force stopping com.example.hello appid=10272 user=0: pkg removed
,I/BackupManagerService(  821): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/ResourcesManager( 3335): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ActivityManager(  821): Spurious death for ProcessRecord{13c50e02 3087:com.example.hello/u0a272}, curProc for 3087: null
,D/TaskPersister(  821): removeObsoleteFile: deleting file=24_task.xml
,I/Keyboard.Facilitator( 1221): resetDictionaries() : en_US
,I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1221): run()
,I/Decoder ( 1221): createOrResetDecoder
,I/art     ( 1073): Explicit concurrent mark sweep GC freed 36984(1533KB) AllocSpace objects, 0(0B) LOS objects, 18% free, 70MB/86MB, paused 601us total 29.903ms
V/GmsNetworkLocationProvi( 1759): DISABLE
,D/JobSchedulerService(  821): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,W/InputMethodManagerService(  821): Got RemoteException sending setActive(false) notification to pid 3087 uid 10272
,V/BackupManagerService(  821): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  821): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2fa7a16b
,I/Keyboard.Facilitator( 1221): onFinishInput()
,I/ConfigService( 1500): onCreate
,W/LocationOracleImpl( 1531): Best location was null
,W/ErrorReporter( 1531): reportError [type: 29, code: 917507]: null
,I/HotwordRecognitionRnr( 1531): Starting hotword detection.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1221): run()
,I/MicrophoneInputStream( 1531): mic_starting com.google.android.apps.gsa.speech.audio.u@34d03948
,I/AudioFlinger(  359): AudioFlinger's thread 0xb4cd0000 ready to run
,I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,W/GCoreFlp( 1759): No location to return for getLastLocation()
,I/MicrophoneInputStream( 1531): mic_started com.google.android.apps.gsa.speech.audio.u@34d03948
,D/audio_hw_primary(  359): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  359): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  359): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  359): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  359): enable_audio_route: apply and update mixer path: audio-record
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1221): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1221): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1221): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1221): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1221): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1221): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1221): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1221): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1221): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1221): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1221): run()
I/StatsUtilsManager( 1221): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1221): shouldRecordStats() = Too Soon
,I/art     (  821): Explicit concurrent mark sweep GC freed 18984(1235KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.164ms total 179.921ms
,W/GCoreFlp( 1759): No location to return for getLastLocation()
,W/GCoreFlp( 1759): No location to return for getLastLocation()
I/HotwordWorker( 1531): onReady
,I/art     ( 3314): System.exit called, status: 0
I/AndroidRuntime( 3314): VM exiting with result code 0.
,W/GCoreFlp( 1759): No location to return for getLastLocation()
,D/BuaReceiver( 2186): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659516179
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,D/Launcher.Workspace( 1326): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1326): 11683562 - stripEmptyScreens()
,V/GmsNetworkLocationProvi( 1759): ENABLE
,D/VoicemailCleanupService( 1399): Cleaning up data for package: com.example.hello
V/GmsNetworkLocationProvi( 1759): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
V/GmsNetworkLocationProvi( 1759): SET-REQUEST
,V/GmsNetworkLocationProvi( 1759): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,I/ActivityManager(  821): Start proc 3379:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,E/SQLiteLog( 1399): (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.example.hello'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
E/AndroidRuntime( 1399): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 1399): Process: android.process.acore, PID: 1399
E/AndroidRuntime( 1399): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1399): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1399): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1399): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1399): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1399): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1399): 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:156)
E/AndroidRuntime( 1399): 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:209)
E/AndroidRuntime( 1399): 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:130)
E/AndroidRuntime( 1399): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 1399): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 1399): 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime( 1399): 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 1399): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1399): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1399): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1399): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/OpenGLRenderer(  821): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   (  821): Validating map...
,E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop88.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  821): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  821): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  821): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  821): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  821): 	... 5 more
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/OpenGLRenderer(  821): Initialized EGL, version 1.4
,I/ActivityManager(  821): Start proc 3403:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,D/OpenGLRenderer(  821): Enabling debug mode 0
,W/ContextImpl( 3403): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/SQLiteLog( 1500): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,D/AndroidRuntime( 1500): Shutting down VM
,E/AndroidRuntime( 1500): FATAL EXCEPTION: main
E/AndroidRuntime( 1500): Process: com.google.process.gapps, PID: 1500
E/AndroidRuntime( 1500): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1500): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 1500): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 1500): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 1500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1500): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1500): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 1500): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1500): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1500): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 1500): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 1500): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1500): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1500): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1500): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1500): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1500): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1500): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1500): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1500): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1500): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 1500): 	... 9 more
,E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop92.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  821): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  821): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  821): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  821): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  821): 	... 5 more
E/SQLiteDatabase( 3403): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 3403): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3403): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3403): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3403): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3403): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3403): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3403): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3403): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3403): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3403): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3403): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3403): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3403): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3403): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3403): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/SQLiteDatabase( 3403): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/SQLiteDatabase( 3403): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3403): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 3403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 3403): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 3403): Process: com.android.keychain, PID: 3403
E/AndroidRuntime( 3403): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3403): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3403): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 3403): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 3403): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3403): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3403): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3403): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 3403): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 3403): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 3403): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 3403): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 3403): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 3403): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 3403): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/AndroidRuntime( 3403): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/AndroidRuntime( 3403): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 3403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3403): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 3403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop93.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  821): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  821): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  821): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  821): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  821): 	... 5 more
,W/OpenGLRenderer( 1326): Incorrectly called buildLayer on View: ew, destroying layer...
,I/HotwordDetector( 1531): Closing mic
I/MicrophoneInputStream( 1531): mic_close com.google.android.apps.gsa.speech.audio.u@34d03948
,D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1531): Hotword detection finished
,I/HotwordRecognitionRnr( 1531): Stopping hotword detection.
,I/ActivityManager(  821): Killing 2620:com.google.android.configupdater/u0a42 (adj 15): empty #17
,I/ActivityManager(  821): Killing 2654:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,E/native  ( 1221): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1221): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1221): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1221): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1221): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp,
E/native  ( 1221): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1221): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1221): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,I/ActivityManager(  821): Waited long enough for: ServiceRecord{da57daa u0 org.simalliance.openmobileapi.service/.SmartcardService}
,I/ActivityManager(  821): Waited long enough for: ServiceRecord{2cf0a55a u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,E/SQLiteLog( 2885): (3850) statement aborts at 28: [UPDATE requests SET server_target_retry=?,server_fail_count=?,fail_count=? WHERE _id=?] disk I/O error
,E/Babel_Crash( 2885): Uncaught exception in background thread Thread[default_queue1,5,main],
,E/Babel_Crash( 2885): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/Babel_Crash( 2885): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/Babel_Crash( 2885): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/Babel_Crash( 2885): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/Babel_Crash( 2885): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/Babel_Crash( 2885): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1576)
E/Babel_Crash( 2885): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1522)
E/Babel_Crash( 2885): 	at dhe.a(SourceFile:3360)
E/Babel_Crash( 2885): 	at cap.d(SourceFile:393)
E/Babel_Crash( 2885): 	at caq.run(SourceFile:81)
,E/AndroidRuntime( 2885): FATAL EXCEPTION: default_queue1
E/AndroidRuntime( 2885): Process: com.google.android.talk, PID: 2885
E/AndroidRuntime( 2885): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2885): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2885): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 2885): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2885): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2885): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1576)
E/AndroidRuntime( 2885): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1522)
E/AndroidRuntime( 2885): 	at dhe.a(SourceFile:3360)
E/AndroidRuntime( 2885): 	at cap.d(SourceFile:393)
E/AndroidRuntime( 2885): 	at caq.run(SourceFile:81)
,E/SharedPreferencesImpl( 2885): Couldn't rename file /data/data/com.google.android.talk/shared_prefs/EsApplication.xml to backup file /data/data/com.google.android.talk/shared_prefs/EsApplication.xml.bak
,E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop94.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  821): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  821): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  821): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  821): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  821): 	... 5 more
,I/ActivityManager(  821): Waited long enough for: ServiceRecord{3ce2236b u0 com.qualcomm.atfwd/.AtFwdService}
,E/QMI_FW  (  821): xport_send: Sendto failed for port 4096
E/LocSvc_api_v02(  821): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1659516179
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,E/kickstart(  877): ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
E/kickstart(  877): ERROR: function: sahara_main:1143 Sahara protocol error
,E/kickstart(  877): ERROR: function: main:268 Uploading  Image using Sahara protocol failed
,I/kickstart(  877): STATUS: Wrote to /sys/power/wake_unlock
,E/ThermalEngine(  367): modem_clnt_error_cb: with -2 called for clnt 0x6
I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb0
E/ThermalEngine(  367): qmi_clnt_error_cb: with error -2 called for clnt FUSION
I/Atfwd_Daemon(  376): Modem Out Of Service --> Release ATCOP service client handles, if any
I/Atfwd_Daemon(  376): release_client returns -1, qmiErroCode = 0 for qmiPort: rmnet_usb0 & userHandle: 486606848
,D/        (  359): csd_client_error_cb: error -2 cb_data 0xb6040060
,I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb4
,D/        (  359): csd_client_error_cb: MDM reset
,I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb5
I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb1,
I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb2,
E/        (  359): deinit: QMI - result 0, error 0, CSD - valid 0, status 0, rc -2
E/        (  359): csd_service_deinit: Error -1 deiniting CSD
I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb6
I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb7,
I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb3
,I/ThermalEngine(  367): qmi: Instance id 157 for fusion TS

```
