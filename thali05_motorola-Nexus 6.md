#### Test 579720943a29850_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SystemBroadcastReceiver( 1211): Boot has been completed
I/SystemBroadcastReceiver( 1211): toggleAppIcon() : FLAG_SYSTEM = true
V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SQLiteLog( 2713): (283) recovered 25 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
--------- beginning of system
I/ActivityManager(  818): Start proc 2786:com.google.android.apps.messaging/u0a75 for broadcast com.google.android.apps.messaging/.receiver.BootAndPackageReplacedReceiver
I/Exchange( 2751): EasService.onCreate
E/ActivityThread( 2713): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@222257d that was originally bound here
E/ActivityThread( 2713): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@222257d that was originally bound here
E/ActivityThread( 2713): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
E/ActivityThread( 2713): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
E/ActivityThread( 2713): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
E/ActivityThread( 2713): 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
E/ActivityThread( 2713): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
E/ActivityThread( 2713): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 2713): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 2713): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 2713): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 2713): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 2713): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 2713): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 2713): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 2713): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2713): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2713): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Exchange( 2751): RestartPingTask
I/Exchange( 2751): RestartPingsTask did not start any pings.
I/Exchange( 2751): PSS stopIfIdle
I/Exchange( 2751): PSS has no active accounts; stopping service.
I/Exchange( 2751): onDestroy
I/ActivityManager(  818): Killing 2262:com.android.managedprovisioning/u0a17 (adj 15): empty #17
I/Gmail   ( 2713): notifyAccountChanged
I/Gmail   ( 2713): getAccountsCursor
I/Gmail   ( 2713): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 2713): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 2713): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 2713): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 2713): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
I/Gmail   ( 2713): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
I/Gmail   ( 2713): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
I/ActivityManager(  818): Killing 1581:com.google.android.partnersetup/u0a16 (adj 15): empty #17
I/art     ( 1430): Explicit concurrent mark sweep GC freed 7917(441KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.477ms total 49.684ms
I/Gmail   ( 2713): getAccountsCursor
V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/VideoCapabilities( 2786): Unrecognized profile 2130706433 for video/avc
I/VideoCapabilities( 2786): Unsupported profile 4 for video/mp4v-es
W/Bugle   ( 2786): PhoneUtils.getForLMR1(): invalid subId = -1
W/Bugle   ( 2786): PhoneUtils.getForLMR1(): invalid subId = -1
W/ResourcesManager( 2786): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/UserPresentBroadcastReceiver( 1703): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
W/Bugle   ( 2786): PhoneUtils.getForLMR1(): invalid subId = -1
I/BugleUsageStatistics( 2786): PlayLogger.onLoggerConnected
I/art     ( 2786): Note: end time exceeds epoch: 
I/Bugle   ( 2786): ApnsOta: OTA version -1
W/Bugle   ( 2786): PhoneUtils.getForLMR1(): invalid subId = -1
W/Bugle   ( 2786): PhoneUtils.getForLMR1(): invalid subId = -1
I/ActivityManager(  818): Start proc 2823:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver
I/BugleDataModel( 2786): Fixup: Send failed - 0 Download failed - 0
W/Bugle   ( 2786): PhoneUtils.getForLMR1(): invalid subId = -1
W/Bugle   ( 2786): PhoneUtils.getForLMR1(): invalid subId = -1
W/Bugle   ( 2786): PhoneUtils.getForLMR1(): invalid subId = -1
W/Bugle   ( 2786): PhoneUtils.getSelfRawNumber: subInfo is null for -1
W/Bugle   ( 2786): PhoneUtils.getForLMR1(): invalid subId = -1
W/Bugle   ( 2786): PhoneUtils.getForLMR1(): invalid subId = -1
I/BugleDataModel( 2786): SyncMessagesAction: Starting batch for messages from 1454414552260 to 1454414785420 (message update limit = 80, message scan limit = 4000)
I/BugleDataModel( 2786): SyncMessagesAction: All messages now in sync
I/ActivityManager(  818): Killing 2283:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  818): Killing 2302:org.simalliance.openmobileapi.service/u0a23 (adj 15): empty #17
I/MusicStore( 2823): Database version: 120
D/AndroidRuntime( 2845): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 2845): CheckJNI is OFF
I/art     (  818): Explicit concurrent mark sweep GC freed 10625(490KB) AllocSpace objects, 1(14KB) LOS objects, 32% free, 33MB/49MB, paused 1.203ms total 45.070ms
D/AndroidRuntime( 2845): Calling main entry com.android.commands.am.Am
I/ActivityManager(  818): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  818): addAppToken: AppWindowToken{2cf839ca token=Token{266ce135 ActivityRecord{1d75276c u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 2845): Shutting down VM
V/WindowManager(  818): Adding window Window{1b1b2c17 u0 Starting com.test.thalitest} at 2 of 7 (after Window{1561c4d9 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1518): Closing mic
I/MicrophoneInputStream( 1518): mic_close com.google.android.apps.gsa.speech.audio.u@31597a8e
I/ActivityManager(  818): Start proc 2866:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  356): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  356): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1518): Hotword detection finished
I/HotwordRecognitionRnr( 1518): Stopping hotword detection.
W/ResourcesManager( 2823): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2823): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  818): Killing 2189:com.android.providers.calendar/u0a3 (adj 15): empty #17
V/JNIHelp ( 2823): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659991315
E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/ProviderInstaller( 2823): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 2823): GMSCore installation verified
I/ConfigStore( 2823): Config Database version: 1
I/WebViewFactory( 2866): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 2866): Time to load native libraries: 1 ms (timestamps 635-636)
,I/LibraryLoader( 2866): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 2866): Binding Chromium to main looper Looper (main, tid 1) {2be658dc}
,I/LibraryLoader( 2866): Expected native library version number "",actual native library version number ""
I/chromium( 2866): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2866): Initializing chromium process, singleProcess=true
,W/art     ( 2866): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2866): ApplicationContext is null in ApplicationStatus
,W/chromium( 2866): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2866): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2866): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2866): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 2866): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/MediaRouter( 2823): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
D/BluetoothManagerService(  818): Message: 20
D/BluetoothManagerService(  818): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@249c6f82:true
D/BluetoothAdapter( 2866): 585605985: getState() :  mService = null. Returning STATE_OFF
,I/GHttpClientFactory( 2823): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/art     ( 2866): Attempt to remove local handle scope entry from IRT, ignoring
,I/GoogleURLConnFactory( 2823): Using platform SSLCertificateSocketFactory
,W/AwContents( 2866): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2866): CordovaWebView is running on device made by: motorola
,W/art     ( 2866): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2866): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2866): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 2866): Validating map...
,V/WindowManager(  818): Adding window Window{1c752d30 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{1b1b2c17 u0 Starting com.test.thalitest})
,W/chromium( 2866): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2866): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2866): Enabling debug mode 0
,D/GCM     ( 1430): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Keyboard.Facilitator( 1211): onFinishInput()
,I/ActivityManager(  818): Displayed com.test.thalitest/.MainActivity: +557ms
D/ChimeraCfgMgr( 1733): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1733): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1733): [KidAccountFixer] No network connection
,W/BindingManager( 2866): Cannot call determinedVisibility() - never saw a connection for the pid: 2866
,I/MediaStoreImporter( 2823): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  818): Killing 2365:com.google.android.configupdater/u0a42 (adj 15): empty #17
,D/JsMessageQueue( 2866): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  818): Start proc 2935:com.android.providers.calendar/u0a3 for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,I/art     (  367): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 228us total 12.448ms
,I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 198us total 11.150ms
,W/ResourcesManager( 2935): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 225us total 10.688ms
,I/CalendarProvider2( 2935): Created com.android.providers.calendar.CalendarAlarmManager@e6a94f(com.android.providers.calendar.CalendarProvider2@2be658dc)
,D/GCM     ( 1430): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1430): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1733): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1772): callingUid 10011, callindPid: 1772
,D/LocationInitializer( 1733): Restart initialization of location
,E/MDM     ( 1703): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/SQLiteLog( 2935): (284) automatic index on view_events(_id)
,D/jxcore_app_log( 2866): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576396416
,I/chromium( 2866): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  818): Start proc 2958:com.motorola.android.buacontactadapter/u0a88 for broadcast com.motorola.android.buacontactadapter/.BuaReceiver
,D/BuaReceiver( 2958): ====== got intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/ActivityManager(  818): Start proc 2975:com.google.android.partnersetup/u0a16 for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  818): Start proc 2995:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,D/PackageBroadcastService( 1733): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1733): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1733): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  818): Killing 2399:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/ConfigFetchService( 1733): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1733): launchTask
,D/ChimeraCfgMgr( 1733): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1733): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1733): Loading module com.google.android.gms.vision from APK com.google.android.gms
,I/PeopleContactsSync( 1733): CP2 sync disabled
,D/Vision  ( 1733): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1733): Failed to find package metadata for com.test.thalitest
,D/Vision  ( 1733): No vision deps
,V/ConfigFetchTask( 1733): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1Ud92CzeZSjQyaPMMnvOo1HjjLtgq32sCHY0ET820GDalIdM0tzdnNyuCal99b6tVtyEab-sV9HK1M6aTbXmzERzfcMFnDzJiQb764ePMim6q0pjACGHsgRQfK6OCo9oVrKhf6eVSrlNxLnv3r-KakLfU3p5RVr5fZU8hB7w2_8kBSUJx7UIX-aB4sYsKYF5TYBz3b6
,I/GoogleURLConnFactory( 1733): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  818): Start proc 3023:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,I/UpdateIcingCorporaServi( 1518): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/ConfigFetchTask( 1733): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1733): fetch service done; releasing wakelock
I/ConfigFetchService( 1733): stopping self
,I/UpdateIcingCorporaServi( 1518): UpdateCorporaTask done [took 75 ms] updated apps [took 75 ms] 
,W/BaseAppContext( 1733): Using Auth Proxy for data requests.
,W/BaseAppContext( 1733): Using Auth Proxy for data requests.
,W/BaseAppContext( 1733): Using Auth Proxy for data requests.
,W/BaseAppContext( 1733): Using Auth Proxy for data requests.
,W/BaseAppContext( 1733): Using Auth Proxy for data requests.
,W/BaseAppContext( 1733): Using Auth Proxy for data requests.
,I/art     (  818): Explicit concurrent mark sweep GC freed 12461(652KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.064ms total 49.039ms
,I/CalendarProvider2( 2935): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 2935): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  818): Killing 2065:com.google.android.keep/u0a79 (adj 15): empty #17
,I/GAv4    ( 3023): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3023):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3023):   adb logcat -s GAv4
,W/GAv4    ( 3023): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3023): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3023): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 3023): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,W/jxcore-log( 2866): Initializing JXcore engine
W/jxcore-log( 2866): JXcore engine is ready
,W/Thread-291( 2957): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9763]" dev="sockfs" ino=9763 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-291( 2957): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-291( 2957): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9928]" dev="sockfs" ino=9928 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-291( 2957): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[18974]" dev="sockfs" ino=18974 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 2866): Starting JXcore engine
,W/ResourcesManager( 3023): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3023): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  818): Start proc 3061:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  818): Killing 2444:com.qualcomm.telephony/1001 (adj 15): empty #17
,W/jxcore-log( 2866): Platform android
W/jxcore-log( 2866): 
,W/jxcore-log( 2866): Process ARCH arm
W/jxcore-log( 2866): 
,W/ResourcesManager( 3061): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 3023): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3023): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 2866): JXcore Cordova bridge is ready!
I/jxcore-log( 2866): 
W/jxcore-log( 2866): JXcore engine is started
,I/jxcore-log( 2866): Toggling radios to true
I/jxcore-log( 2866): 
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  818): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  818): Message: 1
,D/BluetoothManagerService(  818): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  818): setWifiEnabled: true pid=2866, uid=10265
E/WifiService(  818): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  818): New client listening to asynchronous messages
,I/jxcore-log( 2866): Radios toggled
I/jxcore-log( 2866): 
,I/jxcore-log( 2866): My device name is: motorola-Nexus 6
I/jxcore-log( 2866): 
,D/SoftapController(  352): Softap fwReload - Ok
D/CommandListener(  352): Setting iface cfg
D/CommandListener(  352): Trying to bring down wlan0
D/CommandListener(  352): Clearing all IP addresses on wlan0
I/ActivityManager(  818): Start proc 3082:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
E/WifiMonitor(  818): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,W/ResourcesManager( 3082): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3090): Successfully initialized wpa_supplicant
,D/AdapterServiceConfig( 3082): Adding HeadsetService
,D/AdapterServiceConfig( 3082): Adding A2dpService
D/AdapterServiceConfig( 3082): Adding HidService
D/AdapterServiceConfig( 3082): Adding HealthService
D/AdapterServiceConfig( 3082): Adding PanService
D/AdapterServiceConfig( 3082): Adding GattService
D/AdapterServiceConfig( 3082): Adding BluetoothMapService
,D/BluetoothManagerService(  818): Message: 20
D/BluetoothManagerService(  818): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31cf4e16:true
D/BluetoothAdapterState( 3082): make
,I/bluedroid( 3082): init
D/WifiMonitor(  818): startMonitoring(wlan0) with mConnected = false
,I/BluetoothAdapterState( 3082): Entering OffState
I/bte_conf( 3082): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3082): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3082): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3082): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3082): get_profile_interface socket
I/bluedroid( 3082): get_profile_interface map_client
I/GKI_LINUX( 3082): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterProperties( 3082): Address is:F8:CF:C5:D9:E5:61
D/BluetoothManagerService(  818): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  818): Stored Bluetooth name: Nexus 6
,D/BluetoothAdapterProperties( 3082): Name is: Nexus 6
D/BluetoothManagerService(  818): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  818): Message: 40
D/BluetoothManagerService(  818): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3082): config_hci_snoop_log
D/BluetoothManagerService(  818): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  818): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3082): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3082): Setting state to 11
I/BluetoothAdapterState( 3082): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  818): Message: 60
D/BluetoothManagerService(  818): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  818): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3082): make
,I/BluetoothBondStateMachine( 3082): StableState(): Entering Off State
,I/BluetoothAdapterState( 3082): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAdapterService( 3082): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@364f0de5,
D/HeadsetService( 3082): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3082): classInitNative: succeeds
D/HeadsetStateMachine( 3082): make
,D/HeadsetStateMachine( 3082): max_hf_connections = 1
I/bluedroid( 3082): get_profile_interface handsfree
D/HeadsetStateMachine( 3082): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3082): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@364f0de5
,I/wpa_supplicant( 3090): rfkill: Cannot open RFKILL control device
D/BluetoothA2dp(  818): Proxy object connected
D/BluetoothA2dp( 1063): Proxy object connected
D/A2dpService( 3082): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 3082): classInitNative: succeeds
I/bluedroid( 3082): get_profile_interface avrcp
,E/RemoteController( 3082): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3082): classInitNative: succeeds
D/A2dpStateMachine( 3082): make
I/bluedroid( 3082): get_profile_interface a2dp
I/GKI_LINUX( 3082): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 3082): Enter Disconnected: -2
I/BluetoothHidServiceJni( 3082): classInitNative: succeeds
,D/BluetoothAdapterService( 3082): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@364f0de5
,D/BluetoothInputDevice( 1063): Proxy object connected
D/HidService( 3082): Received start request. Starting profile...
I/bluedroid( 3082): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 3082): classInitNative: succeeds
,D/BluetoothAdapterService( 3082): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@364f0de5
D/HealthService( 3082): Received start request. Starting profile...
,I/bluedroid( 3082): get_profile_interface health
I/BluetoothPanServiceJni( 3082): classInitNative(L105): succeeds
D/BluetoothAdapterService( 3082): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@364f0de5
,D/BluetoothPan( 1063): BluetoothPAN Proxy object connected
,D/PanService( 3082): Received start request. Starting profile...
,D/BluetoothPanServiceJni( 3082): initializeNative(L110): pan
I/bluedroid( 3082): get_profile_interface pan
,I/BtGatt.JNI( 3082): classInitNative(L873): classInitNative: Success!
,D/BluetoothAdapterService( 3082): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@364f0de5
D/BtGatt.DebugUtils( 3082): handleDebugAction() action=null
D/BtGatt.GattService( 3082): Received start request. Starting profile...
,D/BtGatt.GattService( 3082): start()
I/bluedroid( 3082): get_profile_interface gatt
D/BluetoothAdapterService( 3082): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@364f0de5
D/BtGatt.AdvertiseManager( 3082): advertise manager created
,D/BluetoothAdapterService( 3082): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@364f0de5
,D/BluetoothMap( 1063): Proxy object connected
D/BluetoothMapService( 3082): Received start request. Starting profile...
D/BluetoothMapService( 3082): start()
,D/BluetoothMapEmailSettingsLoader( 3082): Found 0 applications
,D/BluetoothMapEmailAppObserver( 3082): createReceiver()
,D/BluetoothMapEmailAppObserver( 3082): initObservers()
D/BluetoothMapEmailAppObserver( 3082): getEnabledAccountItems()
,D/HeadsetStateMachine( 3082): Proxy object connected
D/HeadsetStateMachine( 3082): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3082): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3082): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 3082): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3082): enable
I/bt_hci_bdroid( 3082): init
I/GKI_LINUX( 3082): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3082): btu_task pending for preload complete event
,I/bt_vendor( 3082): init
I/bt_vnd_conf( 3082): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3082): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3082): userial_init
,I/iu.UploadsManager( 1733): End new media; added: 0, uploading: 0, time: 32 ms
,I/bt_userial_vendor( 3082): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3082): device fd = 53 open
D/bt_userial( 3082): Entering userial_read_thread()
,I/bt_hwcfg( 3082): bt vendor lib: set UART baud 3000000
,D/bt_hwcfg( 3082): Chipset BCM4354A2
D/bt_hwcfg( 3082): Target name = [BCM4354A2]
I/bt_hwcfg( 3082): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,I/ActivityManager(  818): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  818): Resuming delayed broadcast
,W/ResourcesManager( 2090): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2090): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/NotifUtils( 2713): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,V/JNIHelp ( 2090): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/art     ( 1430): Explicit concurrent mark sweep GC freed 15664(725KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 892us total 23.004ms
,I/ActivityManager(  818): Start proc 3140:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,I/ProviderInstaller( 2090): Installed default security provider GmsCore_OpenSSL
,I/Babel_telephony( 2090): TeleIncomingWifiCallController.getRegistrationState, wifi calling not enabled
,W/VideoCapabilities( 2090): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2090): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2090): Unrecognized profile 2130706433 for video/avc
,I/GAV2    ( 2713): Thread[GAThread,5,main]: No campaign data found.
,I/NotifUtils( 2713): validateNotifications - cancelling 1729800001 for 61035162 / -317575340
,D/Tethering(  818): sendTetherStateChangedBroadcast 1, 0, 0
,I/Babel   ( 2090): connection state changed from UNKNOWN to DISCONNECTED
,I/bt_hwcfg( 3082): bt vendor lib: set UART baud 115200
I/ActivityManager(  818): Start proc 3173:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
D/bt_hwcfg( 3082): Settlement delay -- 100 ms
I/bt_hwcfg( 3082): Setting fw settlement delay to 100 
,I/ActivityManager(  818): Killing 2508:com.google.android.youtube/u0a86 (adj 15): empty #17
,I/wpa_supplicant( 3090): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 3090): Could not read interface p2p-dev-wlan0 flags: No such device
,I/bt_hwcfg( 3082): bt vendor lib: set UART baud 3000000
I/bt_hwcfg( 3082): Setting local bd addr to F8:CF:C5:D9:E5:61
,D/WifiConfigStore(  818): Loading config and enabling all networks 
,D/WifiService(  818): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@766e67}
,E/WifiConfigStore(  818): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/bt_hwcfg( 3082): vendor lib fwcfg completed
,I/bt-btu  ( 3082): btu_task received preload complete event
,I/        ( 3082): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3082): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3082): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3082): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3082): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3082): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3082): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3082): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3082): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3082): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3082): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3082): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3082): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3082): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3082): BTE_InitTraceLevels -- TRC_BTIF
W/Settings( 2090): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-HAL(  818): Setting external_sim to 1
D/WifiStateMachine(  818): Setting OUI to 92-68-C3
I/WifiNative-HAL(  818): startHal
D/wifi    (  818): setting scan oui 0xb4b8c340
D/WifiHAL (  818): Sending mac address OUI
,E/WifiStateMachine(  818): cancelDelayedScan -> 1
D/WifiScanningService(  818): SCAN_AVAILABLE : 3
D/RttService(  818): SCAN_AVAILABLE : 3
D/WifiScanningService(  818): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  818): startHal
D/RttService(  818): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/wifi    (  818): getting scan capabilities on interface[0] = 0xb4b8c340
D/WifiHAL (  818): Creating message to get scan capablities; iface = 5
D/WifiHAL (  818): In GetCapabilities::handleResponse
D/WifiHAL (  818): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  818): StartedState
,W/CommandListener(  352): Failed to retrieve HW addr for p2p0 (No such device)
D/CommandListener(  352): Setting iface cfg
,I/wpa_supplicant( 3090): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/WifiP2pService(  818): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiMonitor(  818): startMonitoring(p2p0) with mConnected = true
,D/WifiNative-HAL(  818): p2pGetDeviceAddress
D/WifiNative-HAL(  818): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,E/native  (  818): do suspend false
,E/bt-btm  ( 3082): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2dc6085 
E/bt-btm  ( 3082): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2dc6085 
,I/ActivityManager(  818): Start proc 3197:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,I/ActivityManager(  818): Killing 2628:com.google.android.deskclock/u0a44 (adj 15): empty #17
,D/BluetoothAdapterProperties( 3082): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3082): Calling BTA_HhEnable
E/bt-btif ( 3082): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3082): Address is:F8:CF:C5:D9:E5:61
,W/bt-btm  ( 3082): Stopping oneshot timer
,D/BluetoothAdapterProperties( 3082): Name is: Nexus 6
D/BluetoothManagerService(  818): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  818): Stored Bluetooth name: Nexus 6
,D/BluetoothAdapterProperties( 3082): Scan Mode:20
D/BluetoothAdapterProperties( 3082): Discoverable Timeout:120
,D/bte_conf( 3082): Device ID record 1 : primary
D/bte_conf( 3082):   vendorId            = 000f
D/bte_conf( 3082):   vendorIdSource      = 0001
D/bte_conf( 3082):   product             = 1200
D/bte_conf( 3082):   version             = 1436
D/bte_conf( 3082):   clientExecutableURL = 
D/bte_conf( 3082):   serviceDescription  = 
D/bte_conf( 3082):   documentationURL    = 
D/bte_conf( 3082): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 3082): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3082): ScanMode =  20
D/BluetoothAdapterProperties( 3082): State =  11
D/BluetoothAdapterProperties( 3082): Setting state to 12
I/BluetoothAdapterState( 3082): Bluetooth adapter state changed: 11-> 12
D/BluetoothPanServiceJni( 3082): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
I/BluetoothAdapterState( 3082): Entering On State
D/BluetoothManagerService(  818): Message: 60
,D/BluetoothManagerService(  818): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  818): Broadcasting onBluetoothStateChange(true) to 13 receivers.
,D/BluetoothHeadset( 1269): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 3082): Scan Mode:21
D/BluetoothAdapterProperties( 3082): Discoverable Timeout:120
,D/BluetoothManagerService(  818): Creating new ProfileServiceConnections object for profile: 1
D/BluetoothInputDevice( 1063): onBluetoothStateChange: up=true,
D/BluetoothHeadset(  818): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1063): onBluetoothStateChange: up=true
D/BluetoothHeadset(  818): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 1063): onBluetoothStateChange: up=true
,D/BluetoothPan( 1063): onBluetoothStateChange(on) call bindService
E/bt_h4   ( 3082): vendor lib postload completed
,D/BluetoothMap( 1063): onBluetoothStateChange: up=true
D/BluetoothHeadset(  818): onBluetoothStateChange: up=true
,D/BluetoothAvrcpController( 1063): onBluetoothStateChange: up=true
E/BluetoothAvrcpController( 1063): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController },
D/BluetoothA2dpSink( 1063): onBluetoothStateChange: up=true,
E/BluetoothA2dpSink( 1063): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
,D/BluetoothHeadsetClient( 1063): onBluetoothStateChange: up=true
,E/BluetoothHeadsetClient( 1063): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
D/BluetoothA2dp(  818): onBluetoothStateChange: up=true
D/BluetoothManagerService(  818): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothMapService( 3082): onReceive
D/BluetoothMapService( 3082): STATE_ON
D/BluetoothManagerService(  818): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  818): Message: 40
D/BluetoothManagerService(  818): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapMasInstance( 3082): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 3082): MAS initSocket()
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3082): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 3082): Accepting socket connection...
,I/ActivityManager(  818): Killing 2751:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,D/BluetoothManagerService(  818): Message: 400
,D/BluetoothHeadset( 1269): Proxy object connected
D/BluetoothManagerService(  818): Message: 400
,D/BluetoothHeadset(  818): Proxy object connected
,D/BluetoothManagerService(  818): Message: 400
D/BluetoothHeadset( 1063): Proxy object connected
,D/BluetoothManagerService(  818): Message: 400
D/BluetoothHeadset(  818): Proxy object connected
,D/BluetoothManagerService(  818): Message: 400
D/BluetoothHeadset(  818): Proxy object connected
,I/ActivityManager(  818): Start proc 3219:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/StrictMode( 3219): StrictMode policy violation; ~duration=246 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3219): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3219): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3219): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3219): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3219): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3219): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3219): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3219): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3219): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3219): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3219): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3219): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3219): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3219): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3219): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3219): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3219): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3219): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3219): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3219): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3219): StrictMode policy violation; ~duration=245 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3219): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3219): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3219): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3219): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3219): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3219): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3219): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3219): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3219): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3219): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3219): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3219): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3219): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3219): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3219): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3219): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3219): StrictMode policy violation; ~duration=242 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3219): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3219): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3219): 	at libcore.io.IoUtils,.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3219): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3219): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3219): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3219): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3219): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3219): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3219): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3219): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3219): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3219): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3219): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3219): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3219): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3219): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3219): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3219): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3219): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3219): StrictMode policy violation; ~duration=237 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3219): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3219): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3219): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3219): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3219): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3219): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3219): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3219): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3219): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3219): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3219): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3219): 	at java.lang.reflect.Method.invoke(Native Method)
,D/StrictMode( 3219): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3219): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3219): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3219): StrictMode policy violation; ~duration=183 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3219): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3219): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3219): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3219): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3219): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3219): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3219): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3219): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3219): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3219): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3219): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3219): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3219): 	at android.os.Looper.loop(Looper.java:135)
,D/StrictMode( 3219): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3219): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3219): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3219): ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3219): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3219): StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3219): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3219): 	,at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3219): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3219): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3219): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3219): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3219): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3219): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3219): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3219): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3219): # via Binder call with stack:
D/StrictMode( 3219): android.os.StrictMode$LogStackTrace
D/StrictMode( 3219): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3219): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3219): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3219): 	,at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3219): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3219): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3219): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3219): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3219): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3219): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3219): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3219): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3219): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3219): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3219): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3219): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3219): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3219): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3219): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3219): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3219): StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3219): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3219): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3219): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3219): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3219): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3219): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3219): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3219): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3219): ,	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3219): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3219): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3219): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3219): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3219): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3219): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3219): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3219): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3219): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run,(ZygoteInit.java:903)
D/StrictMode( 3219): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3219): StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3219): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3219): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3219): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3219): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3219): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3219): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3219): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3219): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3219): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3219): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3219): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3219): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3219): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3219): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3219): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3219): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3219): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3219): StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3219): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3219): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3219): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3219): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3219): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3219): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3219): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3219): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3219): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3219): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3219): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3219): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3219): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3219): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3219): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3219): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3219): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3219): StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3219): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3219): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3219): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3219): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3219): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3219): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3219): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3219): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3219): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3219): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3219): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3219): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3219): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3219): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3219): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3219): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3219): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3219): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3219): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3219): 	,at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3219): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3219): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3219): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3219): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/com.google.a.a.a.b.a( 3219): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  818): Message: 20
D/BluetoothManagerService(  818): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1cc30dba:true
,I/ActivityManager(  818): Killing 2610:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1430): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/InputReader(  818): Reconfiguring input devices.  changes=0x00000010
,V/GmsNetworkLocationProvi( 1703): DISABLE
,D/BackupManagerService(  818): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  818): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  818): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/art     (  818): Explicit concurrent mark sweep GC freed 28181(1406KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 2.174ms total 70.303ms
,W/ContextImpl( 3197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  818): Message: 20
D/BluetoothManagerService(  818): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e9e0d01:true
,I/art     ( 1703): Explicit concurrent mark sweep GC freed 13232(733KB) AllocSpace objects, 5(80KB) LOS objects, 37% free, 26MB/42MB, paused 993us total 29.069ms
,I/Launcher( 1301): Deferring update until onResume
,V/GmsNetworkLocationProvi( 1703): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3082): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 3197): Adding local A2DP profile
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  818): Message: 30
,W/BluetoothAdapter( 3082): getBluetoothService() called with no BluetoothManagerCallback
,D/AuthorizationBluetoothService( 1430): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/LocalBluetoothProfileManager( 3197): Adding local HEADSET profile
I/BtOppRfcommListener( 3082): Accept thread started.
,D/BluetoothManagerService(  818): Message: 30
,V/BackupManagerService(  818): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  818): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2c9fd1e2
,V/GmsNetworkLocationProvi( 1703): ENABLE
,V/GmsNetworkLocationProvi( 1703): SET-REQUEST
,V/GmsNetworkLocationProvi( 1703): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,D/BluetoothManagerService(  818): Message: 30
,D/BluetoothManagerService(  818): Message: 30
,D/LocalBluetoothProfileManager( 3197): Adding local MAP profile
,D/BluetoothMap( 3197): Create BluetoothMap proxy object
D/BluetoothManagerService(  818): Message: 30
,D/BluetoothManagerService(  818): Message: 30
,D/LocalBluetoothProfileManager( 3197): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3197): finishStartingService: stopping service
,D/BluetoothA2dp( 3197): Proxy object connected
D/A2dpProfile( 3197): Bluetooth service connected
,D/BluetoothInputDevice( 3197): Proxy object connected
,D/HidProfile( 3197): Bluetooth service connected
,D/BluetoothPan( 3197): BluetoothPAN Proxy object connected
,D/PanProfile( 3197): Bluetooth service connected
,D/BluetoothMap( 3197): Proxy object connected
D/MapProfile( 3197): Bluetooth service connected
D/BluetoothMap( 3197): getConnectedDevices()
,D/BluetoothPbap( 3197): Proxy object connected
D/PbapServerProfile( 3197): Bluetooth service connected
,D/PackageBroadcastService( 1733): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1733): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1733): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 1518): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1301): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@22887347 new=com.google.android.velvet.VelvetApplication@22887347
,I/ActivityManager(  818): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  818): Resuming delayed broadcast
,D/BluetoothManagerService(  818): Message: 400
D/BluetoothHeadset( 3197): Proxy object connected
,D/HeadsetProfile( 3197): Bluetooth service connected
,I/UpdateIcingCorporaServi( 1518): UpdateCorporaTask done [took 88 ms] updated apps [took 88 ms] 
,I/wpa_supplicant( 3090): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  818): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  818):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  818):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  818): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3,
E/WifiConfigStore(  818): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  818): writeKnownNetworkHistory write linked 1
,E/WifiStateMachine(  818): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
E/WifiConfigStore(  818): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  818): will read network variables netId=0
,E/WifiStateMachine(  818): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  818): will read network variables netId=0
,I/wpa_supplicant( 3090): wlan0: Trying to associate with SSID 'NG7005g'
,I/MusicLeanback( 2823): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 2823): Stop autocaching.
,E/GmsUtils( 2823): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 2823): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/wpa_supplicant( 3090): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/ActivityManager(  818): Killing 2786:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,I/wpa_supplicant( 3090): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3090): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  818): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  818): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  818): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  818): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  352): Setting iface cfg
,E/WifiStateMachine(  818): Start Dhcp Watchdog 1
,E/WifiStateMachine(  818):  WifiLinkLayerStats: 
E/WifiStateMachine(  818):  my bss beacon rx: 1
E/WifiStateMachine(  818):  RSSI mgmt: -51
E/WifiStateMachine(  818):  BE :  rx=1 tx=2 lost=0 retries=0
E/WifiStateMachine(  818):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  818):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  818):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  818):  on_time : 0 tx_time=59 rx_time=100 scan_time=0
,D/ConnectivityService(  818): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60,
,E/native  (  818): do suspend false
,E/WifiStateMachine(  818): scanCount==0 - aborting,
,I/ConfigService( 1430): onDestroy
,I/dhcpcd  ( 3278): version 5.5.6 starting
,I/dhcpcd  ( 3278): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3278): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3278): wlan0: leased 192.168.1.122 for 86400 seconds,
,D/ConnectivityService(  818): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  818): Adding iface wlan0 to network 100
,E/WifiStateMachine(  818): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  818): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  818): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  818): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService(  818): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100,
,D/ConnectivityService(  818): Setting Dns servers for network 100 to [/192.168.1.1]
,D/ConnectivityService(  818): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  818): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  818): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  818):    accepting network in place of null
,D/ConnectivityService(  818): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  818): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  818): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1063): CM callback handler got msg 524290
D/CSLegacyTypeTracker(  818): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PhoneInterfaceManager( 1269): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
D/Tethering(  818): MasterInitialState.processMessage what=3
,E/PhoneInterfaceManager( 1269): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,V/BackupManagerService(  818): Scheduling immediate backup pass
,V/BackupManagerService(  818): Running a backup pass
,V/BackupManagerService(  818): clearing pending backups
,I/jxcore-log( 2866): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 2866): 
I/NetworkMonitor( 2823): type=WIFI subType= reason=null isConnected=true
D/TelephonyManager(  818): getDataEnabled: retVal=false
,V/MusicLeanback( 2823): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,V/PerformBackupTask(  818): Beginning backup of 14 targets
,E/GpsLocationProvider(  818): No APN found to select.
,D/PerformBackupTask(  818): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  818): doBackup() invoked
,I/PMBA    (  818): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,D/AlarmManagerService(  818): Setting time of day to sec=1454414793
W/AlarmManagerService(  818): Unable to set rtc to 1454414793: Invalid argument
,I/BackupRestoreController(  818): Getting widget state for user: 0
,I/ActivityManager(  818): Start proc 3319:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/art     (  367): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 205us total 12.199ms
,I/art     (  367): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 208us total 10.580ms
,I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 204us total 10.559ms
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 12:06:33 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454414793657], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454414793635]}
,D/SprintDMReceiver( 3319): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): Validated
D/ConnectivityService(  818): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/ConnectivityService(  818): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  818): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  818): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  818): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1063): CM callback handler got msg 524290
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/SprintDMHelper( 3319): simOperator:  IMSI: null
D/SprintDMReceiver( 3319): Not Sprint UICC, don't do anything.
D/GpsLocationProvider(  818): NTP server returned: 1454414793591 (Tue Feb 02 13:06:33 GMT+01:00 2016) reference: 57589 certainty: 9 system time offset: -86
,V/GoogleAuthProtoRequest( 3140): [321] a.<init>: mAccountName set to: thalitester@gmail.com
,W/GmsBackupTransport( 1703): Unknown package in backup request: @pm@
V/GmsBackupTransport( 1703): starting performBackup for @pm@
,V/GmsBackupTransport( 1703): performBackup done for @pm@
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1430): Explicit concurrent mark sweep GC freed 9887(489KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 846us total 21.712ms
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Auth.Api.Credentials( 1733): [CredentialSyncAdapter] Unknown sync event.
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3140): [321] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3140): [321] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3140): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3140): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3140): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3140): 	at com.a.a.k.run(SourceFile:110)
,W/GLSActivity( 1430): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1430): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1430): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1430): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1430): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1430): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1430): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GmsBackupTransport( 1703): Error sending final backup to server: 
W/GmsBackupTransport( 1703): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1703): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1703): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1703): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1703): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1703): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1703): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1703): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1703): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1703): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1703): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1703): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1703): 	... 1 more
,D/BackupManagerService(  818): Now staging backup of com.google.android.talk
,D/BackupManagerService(  818): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  818): Now staging backup of com.android.providers.settings
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 25758(1843KB) AllocSpace objects, 15(240KB) LOS objects, 36% free, 28MB/44MB, paused 1.266ms total 50.765ms
,D/BackupManagerService(  818): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  818): Now staging backup of com.google.android.gm
,D/BackupManagerService(  818): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  818): Now staging backup of com.android.nfc
,V/GoogleAuthProtoRequest( 3140): [322] a.<init>: mAccountName set to: thalitester@gmail.com
,D/BackupManagerService(  818): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  818): Now staging backup of com.google.android.marvin.talkback
,I/art     ( 3061): WaitForGcToComplete blocked for 5.669ms for cause DisableMovingGc
,I/SystemUpdateService( 1733): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
W/DriveInitializer( 1733): Background init thread started
,D/BackupManagerService(  818): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  818): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  818): Now staging backup of com.android.vending
,D/BackupManagerService(  818): Now staging backup of android
,I/art     (  818): Explicit concurrent mark sweep GC freed 40054(2MB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 1.532ms total 59.004ms
,D/BackupManagerService(  818): Now staging backup of com.google.android.googlequicksearchbox
,D/SystemUpdateService( 1733): onCreate
,D/SystemUpdateService( 1733): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/GmsBackupTransport( 1703): Next backup will happen in 43199826 millis.
,W/DriveInitializer( 1733): Background init thread ended
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemUpdateService( 1733): active receiver: enabled
,I/BackupManagerService(  818): Backup pass finished.
,I/SystemUpdateService( 1733): showing system update notification
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/iu.SyncManager( 1733): SYNC; picasa accounts
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NetworkLogImpl( 1733): Loaded NetworkSpeedPredictor
,I/ActivityManager(  818): Waited long enough for: ServiceRecord{27182395 u0 org.simalliance.openmobileapi.service/.SmartcardService}
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/iu.Environment( 1733): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/iu.UploadsManager( 1733): num queued entries: 0
,I/iu.UploadsManager( 1733): num updated entries: 0
I/iu.SyncManager( 1733): NEXT; no task
,E/Ads     ( 1733): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,D/ChimeraCfgMgr( 1733): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1733): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  818): skipping global notification
,V/SystemUpdateService( 1733): retry (wakeup: false) in 3599890 ms
,I/ActivityManager(  818): Start proc 3377:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1733): onDestroy
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3140): [322] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3140): [322] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3140): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3140): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3140): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3140): 	at com.a.a.k.run(SourceFile:110)
,W/Kids    ( 1733): [AccountUtils] Account not ready
W/Kids    ( 1733): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1733): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1733): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1733): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1733): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1733): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1733): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1733): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1733): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1733): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1733): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1733): 	at java.lang.Thread.run(Thread.java:818)
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 2090): connection state changed from DISCONNECTED to CONNECTED
,E/HttpOperation( 3061): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3061): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3061): 	at jdm.a(PG:82)
E/HttpOperation( 3061): 	at jcs.o(PG:406)
E/HttpOperation( 3061): 	at jcn.a(PG:1379)
E/HttpOperation( 3061): 	at jcs.i(PG:143)
E/HttpOperation( 3061): 	at blb.a(PG:3937)
E/HttpOperation( 3061): 	at czp.a(PG:18188)
E/HttpOperation( 3061): 	at czp.a(PG:9081)
E/HttpOperation( 3061): 	at czq.run(PG:1686)
E/HttpOperation( 3061): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3061): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3061): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3061): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3061): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3061): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3061): 	at jdj.a(PG:4091)
E/HttpOperation( 3061): 	at jdj.a(PG:1125)
E/HttpOperation( 3061): 	at jdm.a(PG:77)
E/HttpOperation( 3061): 	... 12 more
E/HttpOperation( 3061): Caused by: faj: BadAuthentication
E/HttpOperation( 3061): 	at fal.a(PG:38)
E/HttpOperation( 3061): 	at jdj.a(PG:4089)
E/HttpOperation( 3061): 	... 14 more
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3061): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3061): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3061): 	at jdm.a(PG:82)
E/HttpOperation( 3061): 	at jcs.o(PG:406)
E/HttpOperation( 3061): 	at jcn.a(PG:1379)
E/HttpOperation( 3061): 	at jcs.i(PG:143)
E/HttpOperation( 3061): 	at hec.a(PG:42)
E/HttpOperation( 3061): 	at hee.a(PG:102)
E/HttpOperation( 3061): 	at czr.a(PG:65)
E/HttpOperation( 3061): 	at kka.a(PG:108)
E/HttpOperation( 3061): 	at czp.a(PG:19176)
E/HttpOperation( 3061): 	at czp.a(PG:9081)
E/HttpOperation( 3061): 	at czq.run(PG:1686)
E/HttpOperation( 3061): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3061): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3061): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3061): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3061): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3061): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3061): 	at jdj.a(PG:4091)
E/HttpOperation( 3061): 	at jdj.a(PG:1125)
E/HttpOperation( 3061): 	at jdm.a(PG:77)
E/HttpOperation( 3061): 	... 15 more
E/HttpOperation( 3061): Caused by: faj: BadAuthentication
E/HttpOperation( 3061): 	at fal.a(PG:38)
E/HttpOperation( 3061): 	at jdj.a(PG:4089)
E/HttpOperation( 3061): 	... 17 more
E/ExperimentLoader( 3061): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3061): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3061): 	at jdm.a(PG:82)
E/ExperimentLoader( 3061): 	at jcs.o(PG:406)
E/ExperimentLoader( 3061): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3061): 	at jcs.i(PG:143)
E/ExperimentLoader( 3061): 	at hec.a(PG:42)
E/ExperimentLoader( 3061): 	at hee.a(PG:102)
E/ExperimentLoader( 3061): 	at czr.a(PG:65)
E/ExperimentLoader( 3061): 	at kka.a(PG:108)
E/ExperimentLoader( 3061): 	at czp.a(PG:19176)
E/ExperimentLoader( 3061): 	at czp.a(PG:9081)
E/ExperimentLoader( 3061): 	at czq.run(PG:1686)
E/ExperimentLoader( 3061): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3061): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3061): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3061): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3061): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3061): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3061): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3061): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3061): 	at jdm.a(PG:77)
E/ExperimentLoader( 3061): 	... 15 more
E/ExperimentLoader( 3061): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3061): 	at fal.a(PG:38)
E/ExperimentLoader( 3061): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3061): 	... 17 more
,D/GCM     ( 1430): Connected
,D/GCM     ( 1430): Message class com.google.f.a.a.p
,I/GAv4    ( 3377): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3377):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3377):   adb logcat -s GAv4
,V/KeepSync( 3173): Connecting to GoogleApiClient
,W/GAv4    ( 3377): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3377): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3377): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  818): Start proc 3406:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,I/VacuumService( 1430): Vacuum at: now=1454414794354 tag=VacuumService
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 37155, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/art     ( 1430): Explicit concurrent mark sweep GC freed 24640(1445KB) AllocSpace objects, 2(32KB) LOS objects, 37% free, 26MB/42MB, paused 1.034ms total 26.725ms
,W/BaseAppContext( 1733): Using Auth Proxy for data requests.
,W/BaseAppContext( 1733): Using Auth Proxy for data requests.
,W/ResourcesManager( 3406): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3406): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  818): Start proc 3429:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/jxcore-log( 2866): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 2866): 
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1733): Handling authorization failure
E/ClientConnectionOperation( 1733): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1733): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1733): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1733): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1733): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1733): 	... 7 more
,V/KeepSync( 3173): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3173): (284) automatic index on blob_node(is_deleted)
,V/JNIHelp ( 3406): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/SQLiteLog( 3173): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3173): (284) automatic index on blob_node(is_deleted)
,I/ProviderInstaller( 3406): Installed default security provider GmsCore_OpenSSL
,I/jxcore-log( 2866): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 2866): 
I/jxcore-log( 2866): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 2866): 
,I/ActivityManager(  818): Waited long enough for: ServiceRecord{3eca1c05 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,I/jxcore-log( 2866): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 2866): 
,I/WebViewFactory( 3377): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/dex2oat ( 3469): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1525435026.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads1525435026.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/jxcore-log( 2866): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 2866): 
I/LibraryLoader( 3377): Time to load native libraries: 3 ms (timestamps 8645-8648)
I/LibraryLoader( 3377): Expected native library version number "",actual native library version number ""
,I/jxcore-log( 2866): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 2866): 
V/WebViewChromiumFactoryProvider( 3377): Binding Chromium to main looper Looper (main, tid 1) {30b495e9}
I/LibraryLoader( 3377): Expected native library version number "",actual native library version number ""
I/chromium( 3377): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/jxcore-log( 2866): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 2866): 
,I/BrowserStartupController( 3377): Initializing chromium process, singleProcess=true
W/art     ( 3377): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3377): ApplicationContext is null in ApplicationStatus
,E/YouTube MDX( 3406): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium( 3377): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3377): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3377): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3377): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,E/KeepSync( 3173): IOException
E/KeepSync( 3173): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3173): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3173): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3173): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3173): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3173): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3173): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3173): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3173): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3173): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3173): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3173): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3173): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3173): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3173): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3173): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3173): 	... 10 more
W/KeepSync( 3173): Sync result 2
,I/dex2oat ( 3469): dex2oat took 117.471ms (threads: 4) arena alloc=116KB java alloc=12KB native alloc=834KB free=7MB
,I/ActivityManager(  818): Killing 1868:com.android.defcontainer/u0a7 (adj 15): empty #17
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 37158, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/AudioManagerAndroid( 3377): Requires BLUETOOTH permission
,I/NSApplication( 3377): Starting up...
,W/InstanceID/Rpc( 3406): Found 10011
,I/ActivityManager(  818): Start proc 3520:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  818): Killing 2975:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,W/GAV2    ( 3429): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3429): Created application version: 3.6.8 (30608)
,I/art     (  818): Explicit concurrent mark sweep GC freed 29383(1336KB) AllocSpace objects, 5(121KB) LOS objects, 32% free, 33MB/49MB, paused 1.006ms total 48.122ms
,I/BooksSync( 3429): Starting books sync for 61035162, extras: ade
,I/ActivityManager(  818): Waited long enough for: ServiceRecord{22e0c0b0 u0 com.qualcomm.atfwd/.AtFwdService}
,I/BooksConfig( 3429): GmsCore Version = 7.8.99 (2134222-430)
,I/ActivityManager(  818): Start proc 3579:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/ActivityManager(  818): Killing 2995:com.android.musicfx/u0a18 (adj 15): empty #17
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3429): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3429): Soft error
E/BooksSync( 3429): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3429): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3429): Sync error
E/BooksSync( 3429): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3429): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3429): Finished books sync
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 37159, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  818): Killing 2693:com.google.android.gms:car/u0a11 (adj 15): empty #17
,I/Atfwd_Daemon(  373): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/Atfwd_Daemon(  373): ATFWD --> QMI Port : rmnet_usb0
,I/Atfwd_Daemon(  373): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 486606848
I/Atfwd_Daemon(  373): Trying to register 8 commands:
I/Atfwd_Daemon(  373): cmd0: +CKPD
,I/Atfwd_Daemon(  373): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  373): cmd1: +CTSA
,I/Atfwd_Daemon(  373): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  373): cmd2: +CFUN
,I/Atfwd_Daemon(  373): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  373): cmd3: +CMAR
,I/Atfwd_Daemon(  373): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  373): cmd4: +CDIS
,I/Atfwd_Daemon(  373): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  373): cmd5: +CRSL
,I/Atfwd_Daemon(  373): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  373): cmd6: +CSS
,I/Atfwd_Daemon(  373): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  373): cmd7: $QCPWRDN
,I/Atfwd_Daemon(  373): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  373): Registered AT Commands event handler
,I/ActivityManager(  818): Killing 3023:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/ActivityManager(  818): Start proc 3601:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,D/TimeService( 3601): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454414796587
,D/        ( 3601): TimeServiceNative: User Time to be set is 1454414796587
D/QC-time-services( 3601): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3601): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3601): Lib:time_genoff_operation: pargs->ts_val = 1454414796587
D/QC-time-services(  371): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 3601): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  371): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454414796587
D/QC-time-services(  371): Daemon:genoff_opr: Base = 2, val = 1454414796587, operation = 0
D/QC-time-services(  371): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/20/70 8:18:59
D/QC-time-services(  371): Daemon:Value read from RTC seconds = 14717939000
D/QC-time-services(  371): Daemon:new time 1454414796587 
D/QC-time-services(  371): Daemon: delta 1439696857587 genoff 1439696857587 
D/QC-time-services(  371): Daemon:genoff_persistent_update: Writing genoff = 1439696857587 to memory
D/QC-time-services(  371): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  371): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  371): Updating the TOD offset
D/QC-time-services(  371): Daemon:genoff_persistent_update: Writing genoff = 1439696857587 to memory
D/QC-time-services(  371): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  371): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  371): Daemon:Update to modem bit set
D/QC-time-services(  371): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  371): Daemon: Base = 2, Value being sent to MODEM = 1138449996587
,E/QC-time-services( 3601): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager(  818): Killing 2935:com.android.providers.calendar/u0a3 (adj 15): empty #17
,E/QC-time-services(  371): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  371): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40,
,I/ActivityManager(  818): Start proc 3622:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/GAv4    ( 3622): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3622):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3622):   adb logcat -s GAv4
,W/GAv4    ( 3622): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3622): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3622): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  818): Start proc 3644:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,I/ActivityManager(  818): Killing 2713:com.google.android.gm/u0a78 (adj 15): empty #17
,W/ResourcesManager( 3644): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3644): Created com.android.providers.calendar.CalendarAlarmManager@e6a94f(com.android.providers.calendar.CalendarProvider2@2be658dc)
,V/Herrevad( 1733): NQAS connected
,D/WifiService(  818): New client listening to asynchronous messages
,D/WifiService(  818): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@766e67}
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 17508(1161KB) AllocSpace objects, 14(224KB) LOS objects, 35% free, 28MB/44MB, paused 894us total 31.635ms
,I/ActivityManager(  818): Killing 3197:com.android.settings/1000 (adj 15): empty #17
,I/CalendarProvider2( 3644): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3644): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  818): Killing 3219:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,E/SQLiteLog( 3644): (284) automatic index on view_events(_id)
,I/art     (  818): Explicit concurrent mark sweep GC freed 16764(745KB) AllocSpace objects, 3(236KB) LOS objects, 32% free, 33MB/49MB, paused 3.069ms total 61.913ms
,I/jxcore-log( 2866): Test app app.js loaded
I/jxcore-log( 2866): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2866): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2866): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2866): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2866): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2866): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2866): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2866): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2866): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2866): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2866): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d62ba9d added. We now have 1 listener(s)
,I/chromium( 2866): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 2866): BLE advertisement is supported,
I/jxcore-log( 2866): ,
,I/GAV2    ( 3429): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=33.25 rxSuccessRate=30.09 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  818): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 4 -> obsolete
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=33.25 rxSuccessRate=30.09 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  818): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 4 -> obsolete
,D/HeadsetStateMachine( 3082): Disconnected process message: 10, size: 0
,I/CheckinService( 1733): Done disabling old GoogleServicesFramework version
,I/ActivityManager(  818): Killing 2650:com.android.vending/u0a19 (adj 15): empty #17
,I/ActivityManager(  818): Waited long enough for: ServiceRecord{2493e53 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/ActivityManager(  818): Start proc 3686:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,D/HeadsetStateMachine( 3082): Disconnected process message: 10, size: 0
,D/Finsky  ( 3686): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 3686): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  818): Start proc 3723:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,W/Settings( 3686): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3686): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 3723): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3723): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 3686): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3686): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 3686): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/MultiDex( 3723): VM with version 2.1.0 has multidex support
I/MultiDex( 3723): install
I/MultiDex( 3723): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 3686): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/JNIHelp ( 3723): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3723): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1430): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1430): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1733): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1772): callingUid 10011, callindPid: 1772
,E/MDM     ( 1703): [126] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1733): Restart initialization of location
,I/art     ( 1430): Explicit concurrent mark sweep GC freed 16497(939KB) AllocSpace objects, 5(551KB) LOS objects, 37% free, 26MB/42MB, paused 932us total 37.258ms
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Finsky  ( 3686): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3686): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3686): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3686): [1] 5.onFinished: Scheduling replication attempt 1.
,I/ActivityManager(  818): Killing 2823:com.google.android.music:main/u0a66 (adj 15): empty #17
,D/Finsky  ( 3686): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3686): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3686): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3686): [374] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3686): [374] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3686): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3686): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3686): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3686): [1] DailyHygiene.reschedule: Scheduling new run in 835 minutes (failures=5)
,D/DeviceConnectionService( 1703): client connected with version: 7571000
,I/ActivityManager(  818): Killing 3319:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/ActivityManager(  818): Killing 3406:com.google.android.youtube/u0a86 (adj 15): empty #17
,I/ActivityManager(  818): Killing 3377:com.google.android.apps.magazines/u0a67 (adj 15): empty #18
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 2090): UserRecoverableAuthException.
E/Babel   ( 2090): eei: BadAuthentication
E/Babel   ( 2090): 	at eeg.a(Unknown Source)
E/Babel   ( 2090): 	at eeg.a(Unknown Source)
E/Babel   ( 2090): 	at eeg.a(Unknown Source)
E/Babel   ( 2090): 	at g.a(Unknown Source)
E/Babel   ( 2090): 	at cae.a(SourceFile:3089)
E/Babel   ( 2090): 	at cae.a(SourceFile:1131)
E/Babel   ( 2090): 	at cws.a(SourceFile:4333)
E/Babel   ( 2090): 	at cws.a(SourceFile:1419)
E/Babel   ( 2090): 	at crl.a(SourceFile:492)
E/Babel   ( 2090): 	at crl.a(SourceFile:1468)
E/Babel   ( 2090): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2090): 	at cas.b(SourceFile:106)
E/Babel   ( 2090): 	at cap.d(SourceFile:335)
E/Babel   ( 2090): 	at caq.run(SourceFile:81)
E/Babel   ( 2090): Error getting auth token
,E/Babel   ( 2090): dvm
E/Babel   ( 2090): 	at g.a(Unknown Source)
E/Babel   ( 2090): 	at cae.a(SourceFile:3089)
E/Babel   ( 2090): 	at cae.a(SourceFile:1131)
E/Babel   ( 2090): 	at cws.a(SourceFile:4333)
E/Babel   ( 2090): 	at cws.a(SourceFile:1419)
E/Babel   ( 2090): 	at crl.a(SourceFile:492)
E/Babel   ( 2090): 	at crl.a(SourceFile:1468)
E/Babel   ( 2090): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2090): 	at cas.b(SourceFile:106)
E/Babel   ( 2090): 	at cap.d(SourceFile:335)
E/Babel   ( 2090): 	at caq.run(SourceFile:81)
,E/Babel   ( 2090): Account registration failed 1-Redacted-21
,E/Babel   ( 2090): cyp: null -- null
E/Babel   ( 2090): 	at cae.a(SourceFile:3121)
E/Babel   ( 2090): 	at cae.a(SourceFile:1131)
E/Babel   ( 2090): 	at cws.a(SourceFile:4333)
E/Babel   ( 2090): 	at cws.a(SourceFile:1419)
E/Babel   ( 2090): 	at crl.a(SourceFile:492)
E/Babel   ( 2090): 	at crl.a(SourceFile:1468)
E/Babel   ( 2090): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2090): 	at cas.b(SourceFile:106)
E/Babel   ( 2090): 	at cap.d(SourceFile:335)
E/Babel   ( 2090): 	at caq.run(SourceFile:81)
,I/art     ( 2090): Note: end time exceeds epoch: 
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native,
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ResourcesManager( 1430): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Babel   ( 2090): Unexpected exception while authenticating.
,E/Babel   ( 2090): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2090): 	at eeg.b(Unknown Source)
E/Babel   ( 2090): 	at eeg.b(Unknown Source)
E/Babel   ( 2090): 	at g.a(Unknown Source)
E/Babel   ( 2090): 	at cae.b(SourceFile:1146)
E/Babel   ( 2090): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2090): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2090): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2090): 	at java.lang.Thread.run(Thread.java:818)
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=3.76 rxSuccessRate=5.97 targetRoamBSSID=any RSSI=-51
,I/wpa_supplicant( 3090): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,I/art     (  818): Explicit concurrent mark sweep GC freed 24205(1122KB) AllocSpace objects, 5(174KB) LOS objects, 32% free, 33MB/49MB, paused 2.396ms total 93.406ms
,E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3686): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3686): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3686): [1] 5.onFinished: Scheduling replication attempt 2.
,V/GoogleAuthProtoRequest( 3140): [323] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3140): [324] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3140): [323] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3140): [323] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3140): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3140): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3140): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3140): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3140): [324] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3140): [324] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3140): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3140): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3140): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3140): 	at com.a.a.k.run(SourceFile:110)
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.36 rxSuccessRate=1.75 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  818): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1430): Explicit concurrent mark sweep GC freed 32773(1848KB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 2.053ms total 49.565ms
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3686): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3686): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3686): [1] 5.onFinished: Scheduling replication attempt 3.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1211): run()
I/Keyboard.Facilitator( 1211): flushDynamicLanguageModels()
,I/ConfigService( 1430): onCreate
,I/ConfigService( 1430): onDestroy
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.83 rxSuccessRate=2.45 targetRoamBSSID=any RSSI=-51
,I/BooksSync( 3429): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3173): Connecting to GoogleApiClient
,I/BooksConfig( 3429): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1733): Handling authorization failure
E/ClientConnectionOperation( 1733): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1733): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1733): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1733): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1733): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1733): 	... 7 more
V/KeepSync( 3173): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3173): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3173): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3173): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3429): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3429): Soft error
E/BooksSync( 3429): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3429): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3429): Sync error
E/BooksSync( 3429): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3429): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3429): Finished books sync
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 90127, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3173): IOException
E/KeepSync( 3173): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3173): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3173): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3173): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3173): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3173): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3173): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3173): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3173): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3173): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3173): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3173): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3173): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3173): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3173): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3173): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3173): 	... 10 more
W/KeepSync( 3173): Sync result 2
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 88874, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3061): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3061): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3061): 	at jdm.a(PG:82)
E/HttpOperation( 3061): 	at jcs.o(PG:406)
E/HttpOperation( 3061): 	at jcn.a(PG:1379)
E/HttpOperation( 3061): 	at jcs.i(PG:143)
E/HttpOperation( 3061): 	at blb.a(PG:3937)
E/HttpOperation( 3061): 	at czp.a(PG:18188)
E/HttpOperation( 3061): 	at czp.a(PG:9081)
E/HttpOperation( 3061): 	at czq.run(PG:1686)
E/HttpOperation( 3061): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3061): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3061): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3061): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3061): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3061): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3061): 	at jdj.a(PG:4091)
E/HttpOperation( 3061): 	at jdj.a(PG:1125)
E/HttpOperation( 3061): 	at jdm.a(PG:77)
E/HttpOperation( 3061): 	... 12 more
E/HttpOperation( 3061): Caused by: faj: BadAuthentication
E/HttpOperation( 3061): 	at fal.a(PG:38)
E/HttpOperation( 3061): 	at jdj.a(PG:4089)
E/HttpOperation( 3061): 	... 14 more
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3061): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3061): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3061): 	at jdm.a(PG:82)
E/HttpOperation( 3061): 	at jcs.o(PG:406)
E/HttpOperation( 3061): 	at jcn.a(PG:1379)
E/HttpOperation( 3061): 	at jcs.i(PG:143)
E/HttpOperation( 3061): 	at hec.a(PG:42)
E/HttpOperation( 3061): 	at hee.a(PG:102)
E/HttpOperation( 3061): 	at czr.a(PG:65)
E/HttpOperation( 3061): 	at kka.a(PG:108)
E/HttpOperation( 3061): 	at czp.a(PG:19176)
E/HttpOperation( 3061): 	at czp.a(PG:9081)
E/HttpOperation( 3061): 	at czq.run(PG:1686)
E/HttpOperation( 3061): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3061): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3061): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3061): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3061): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3061): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3061): 	at jdj.a(PG:4091)
E/HttpOperation( 3061): 	at jdj.a(PG:1125)
E/HttpOperation( 3061): 	at jdm.a(PG:77)
E/HttpOperation( 3061): 	... 15 more
E/HttpOperation( 3061): Caused by: faj: BadAuthentication
E/HttpOperation( 3061): 	at fal.a(PG:38)
E/HttpOperation( 3061): 	at jdj.a(PG:4089)
E/HttpOperation( 3061): 	... 17 more
E/ExperimentLoader( 3061): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3061): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3061): 	at jdm.a(PG:82)
E/ExperimentLoader( 3061): 	at jcs.o(PG:406)
E/ExperimentLoader( 3061): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3061): 	at jcs.i(PG:143)
E/ExperimentLoader( 3061): 	at hec.a(PG:42)
E/ExperimentLoader( 3061): 	at hee.a(PG:102)
E/ExperimentLoader( 3061): 	at czr.a(PG:65)
E/ExperimentLoader( 3061): 	at kka.a(PG:108)
E/ExperimentLoader( 3061): 	at czp.a(PG:19176)
E/ExperimentLoader( 3061): 	at czp.a(PG:9081)
E/ExperimentLoader( 3061): 	at czq.run(PG:1686)
E/ExperimentLoader( 3061): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3061): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3061): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3061): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3061): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3061): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3061): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3061): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3061): 	at jdm.a(PG:77)
E/ExperimentLoader( 3061): 	... 15 more
E/ExperimentLoader( 3061): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3061): 	at fal.a(PG:38)
E/ExperimentLoader( 3061): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3061): 	... 17 more
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 91344, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3082): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3082): Disconnected process message: 10, size: 0
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3686): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3686): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3686): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.69 rxSuccessRate=3.34 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  818): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,V/GoogleAuthProtoRequest( 3140): [325] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     (  818): Explicit concurrent mark sweep GC freed 49895(2MB) AllocSpace objects, 18(382KB) LOS objects, 31% free, 34MB/50MB, paused 1.234ms total 53.253ms
,V/GoogleAuthProtoRequest( 3140): [326] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3686): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3686): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3686): [1] 5.onFinished: Scheduling replication attempt 5.
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3140): [325] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3140): [325] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3140): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3140): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3140): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3140): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3140): [326] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3140): [326] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3140): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3140): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3140): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3140): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1430): Using platform SSLCertificateSocketFactory
,W/Uploader( 1430): No account for auth token provided
,W/Uploader( 1430): No account for auth token provided
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1430): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1430): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1430): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1430): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1430): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1430): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1430): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1430): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1430): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1430): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1430): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1430): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1430): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1430): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1430): No account for auth token provided
,W/Uploader( 1430): No account for auth token provided
,W/Uploader( 1430): No account for auth token provided
,W/Uploader( 1430): No account for auth token provided
,W/Uploader( 1430): No account for auth token provided
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1430): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1430): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1430): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1430): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1430): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1430): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1430): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1430): No account for auth token provided
,W/Uploader( 1430): No account for auth token provided,
,W/Uploader( 1430): No account for auth token provided,
,W/Uploader( 1430):  no longer exists, so no auth token.,
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1430): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1430): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1430): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1430): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1430): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1430): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1430): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1430): No account for auth token provided
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1430): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1430): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1430): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1430): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1430): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1430): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1430): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1430): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1430): No account for auth token provided
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=21.91 rxSuccessRate=16.69 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  818): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  818): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  818): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (336 us)
,I/DisplayManagerService(  818): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  818): Display changed displayId=0
,D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb6082000
,D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
,I/kickstart(  868): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000,
I/kickstart(  868): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  868): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  868): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  818): Excessive delay in setPowerMode(): 269ms
,I/DreamManagerService(  818): Entering dreamland.
I/PowerManagerService(  818): Dozing...
,I/DreamController(  818): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  356): adev_set_parameters: enter: screen_state=on,
D/mot_vr_audio_hw(  356): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  818): cancelDelayedScan -> 10
,E/native  (  818): do suspend false
,I/Keyboard.Facilitator( 1211): onFinishInput()
,E/WifiStateMachine(  818): cancelDelayedScan -> 12
E/native  (  818): do suspend true
,D/audio_hw_primary(  356): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  356): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  818): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,I/kickstart(  868): STATUS: Received file 'm9kefs2'
I/kickstart(  868): STATUS: 950272 bytes transferred in 0.994227 seconds
I/kickstart(  868): STATUS: Successfully downloaded files from target 
,I/kickstart(  868): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  868): STATUS: Sahara protocol completed
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3686): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3686): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3686): [1] 5.onFinished: Giving up after 6 failures.
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  818): WifiStateMachine L2Connected CMD_START_SCAN source -2 9, 12 -> obsolete
,I/art     ( 1430): Explicit concurrent mark sweep GC freed 70553(4MB) AllocSpace objects, 6(404KB) LOS objects, 36% free, 27MB/43MB, paused 1.679ms total 58.177ms
,V/KeepSync( 3173): Connecting to GoogleApiClient
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1733): Handling authorization failure
E/ClientConnectionOperation( 1733): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1733): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1733): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1733): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1733): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1733): 	... 7 more
,V/KeepSync( 3173): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3173): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3173): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3173): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3173): IOException
E/KeepSync( 3173): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3173): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3173): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3173): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3173): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3173): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3173): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3173): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3173): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3173): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3173): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3173): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3173): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3173): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3173): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3173): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3173): 	... 10 more
W/KeepSync( 3173): Sync result 2
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 178262, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3082): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3082): Disconnected process message: 10, size: 0
,I/BooksSync( 3429): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3429): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  818): Explicit concurrent mark sweep GC freed 41440(1937KB) AllocSpace objects, 7(300KB) LOS objects, 31% free, 34MB/50MB, paused 1.275ms total 69.350ms
,E/HttpOperation( 3061): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3061): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3061): 	at jdm.a(PG:82)
E/HttpOperation( 3061): 	at jcs.o(PG:406)
E/HttpOperation( 3061): 	at jcn.a(PG:1379)
E/HttpOperation( 3061): 	at jcs.i(PG:143)
E/HttpOperation( 3061): 	at blb.a(PG:3937)
E/HttpOperation( 3061): 	at czp.a(PG:18188)
E/HttpOperation( 3061): 	at czp.a(PG:9081)
E/HttpOperation( 3061): 	at czq.run(PG:1686)
E/HttpOperation( 3061): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3061): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3061): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3061): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3061): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3061): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3061): 	at jdj.a(PG:4091)
E/HttpOperation( 3061): 	at jdj.a(PG:1125)
E/HttpOperation( 3061): 	at jdm.a(PG:77)
E/HttpOperation( 3061): 	... 12 more
E/HttpOperation( 3061): Caused by: faj: BadAuthentication
E/HttpOperation( 3061): 	at fal.a(PG:38)
E/HttpOperation( 3061): 	at jdj.a(PG:4089)
E/HttpOperation( 3061): 	... 14 more
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3429): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3429): Soft error
E/BooksSync( 3429): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3429): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3429): Sync error
E/BooksSync( 3429): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3429): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3429): Finished books sync
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 178933, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/HttpOperation( 3061): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3061): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3061): 	at jdm.a(PG:82)
E/HttpOperation( 3061): 	at jcs.o(PG:406)
E/HttpOperation( 3061): 	at jcn.a(PG:1379)
E/HttpOperation( 3061): 	at jcs.i(PG:143)
E/HttpOperation( 3061): 	at hec.a(PG:42)
E/HttpOperation( 3061): 	at hee.a(PG:102)
E/HttpOperation( 3061): 	at czr.a(PG:65)
E/HttpOperation( 3061): 	at kka.a(PG:108)
E/HttpOperation( 3061): 	at czp.a(PG:19176)
E/HttpOperation( 3061): 	at czp.a(PG:9081)
E/HttpOperation( 3061): 	at czq.run(PG:1686)
E/HttpOperation( 3061): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3061): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3061): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3061): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3061): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3061): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3061): 	at jdj.a(PG:4091)
E/HttpOperation( 3061): 	at jdj.a(PG:1125)
E/HttpOperation( 3061): 	at jdm.a(PG:77)
E/HttpOperation( 3061): 	... 15 more
E/HttpOperation( 3061): Caused by: faj: BadAuthentication
E/HttpOperation( 3061): 	at fal.a(PG:38)
E/HttpOperation( 3061): 	at jdj.a(PG:4089)
E/HttpOperation( 3061): 	... 17 more
E/ExperimentLoader( 3061): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3061): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3061): 	at jdm.a(PG:82)
E/ExperimentLoader( 3061): 	at jcs.o(PG:406)
E/ExperimentLoader( 3061): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3061): 	at jcs.i(PG:143)
E/ExperimentLoader( 3061): 	at hec.a(PG:42)
E/ExperimentLoader( 3061): 	at hee.a(PG:102)
E/ExperimentLoader( 3061): 	at czr.a(PG:65)
E/ExperimentLoader( 3061): 	at kka.a(PG:108)
E/ExperimentLoader( 3061): 	at czp.a(PG:19176)
E/ExperimentLoader( 3061): 	at czp.a(PG:9081)
E/ExperimentLoader( 3061): 	at czq.run(PG:1686)
E/ExperimentLoader( 3061): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3061): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3061): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3061): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3061): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3061): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3061): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3061): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3061): 	at jdm.a(PG:77)
E/ExperimentLoader( 3061): 	... 15 more
E/ExperimentLoader( 3061): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3061): 	at fal.a(PG:38)
E/ExperimentLoader( 3061): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3061): 	... 17 more
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 184181, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1211): run()
I/Keyboard.Facilitator( 1211): flushDynamicLanguageModels()
,I/ConfigService( 1430): onCreate,
,I/ConfigService( 1430): onDestroy
,D/HeadsetStateMachine( 3082): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3082): Disconnected process message: 10, size: 0
,I/jxcore-log( 2866): --= Surplus to requirements =--
I/jxcore-log( 2866): 
I/jxcore-log( 2866): ****TEST TOOK:  ms ****
I/jxcore-log( 2866): 
I/jxcore-log( 2866): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2866): 
,V/GoogleAuthProtoRequest( 3140): [327] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3140): [328] a.<init>: mAccountName set to: thalitester@gmail.com
,D/AndroidRuntime( 3847): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3847): CheckJNI is OFF
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1430): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1430): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1430): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1430): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1430): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3140): [328] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3140): [327] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3140): [328] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3140): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3140): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3140): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3140): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3140): [327] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3140): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3140): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3140): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3140): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3140): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3140): 	at com.a.a.k.run(SourceFile:110)
,D/AndroidRuntime( 3847): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  818): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  818): Killing 2866:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,W/PackageSettings(  818): Skipping PackageSetting{2e855518 com.example.hello/10273} due to missing metadata
,I/WindowState(  818): WIN DEATH: Window{1c752d30 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  818): Client connection lost with reason: 4
,W/ActivityManager(  818): Force removing ActivityRecord{1d75276c u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
,V/ActivityManager(  818): Display changed displayId=0
,W/ActivityManager(  818): Spurious death for ProcessRecord{8747263 2866:com.test.thalitest/u0a265}, curProc for 2866: null
I/ActivityManager(  818): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,I/Keyboard.Facilitator( 1211): resetDictionaries() : en_US
,I/InputReader(  818): Reconfiguring input devices.  changes=0x00000010
,D/TaskPersister(  818): removeObsoleteFile: deleting file=28_task.xml
,D/BuaReceiver( 2958): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/art     ( 1063): Explicit concurrent mark sweep GC freed 51032(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 70MB/86MB, paused 1.314ms total 43.397ms
I/Keyboard.Facilitator.DecoderInitializer( 1211): run()
,D/VoicemailCleanupService( 1395): Cleaning up data for package: com.test.thalitest
,I/Decoder ( 1211): createOrResetDecoder
,I/art     (  818): Explicit concurrent mark sweep GC freed 20196(1245KB) AllocSpace objects, 11(835KB) LOS objects, 32% free, 33MB/49MB, paused 3.774ms total 75.534ms
I/art     (  818): WaitForGcToComplete blocked for 43.246ms for cause Explicit
,I/ActivityManager(  818): Start proc 3867:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
I/art     ( 1518): Explicit concurrent mark sweep GC freed 6439(425KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 26MB/34MB, paused 841us total 92.579ms
,I/art     (  367): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 199us total 9.493ms
,I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 193us total 8.473ms
,I/ConfigService( 1430): onCreate
,I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 195us total 9.146ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1211): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1211): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,W/InputMethodManagerService(  818): Got RemoteException sending setActive(false) notification to pid 2866 uid 10265
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1211): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1211): run() : Loading LM = contacts
,I/Keyboard.Facilitator( 1211): onFinishInput()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1211): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1211): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1211): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1211): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1211): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1211): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1211): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1211): run()
I/StatsUtilsManager( 1211): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1211): shouldRecordStats() = Too Soon
,I/ActivityManager(  818): Start proc 3889:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,D/JobSchedulerService(  818): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  818): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/art     ( 1301): Explicit concurrent mark sweep GC freed 9803(516KB) AllocSpace objects, 11(1212KB) LOS objects, 31% free, 35MB/51MB, paused 680us total 25.047ms
,W/ContextImpl( 3889): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,W/LocationOracleImpl( 1518): Best location was null
,I/HotwordRecognitionRnr( 1518): Starting hotword detection.
,I/MicrophoneInputStream( 1518): mic_starting com.google.android.apps.gsa.speech.audio.u@24710196
,E/NetworkScheduler.SchedulerReceiver( 1430): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1430): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/AudioFlinger(  356): AudioFlinger's thread 0xb406b000 ready to run
,I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1518): mic_started com.google.android.apps.gsa.speech.audio.u@24710196
,I/art     (  818): Explicit concurrent mark sweep GC freed 5900(285KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 3.460ms total 165.827ms
,D/Launcher.Workspace( 1301): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1301): 11683562 - stripEmptyScreens()
,D/audio_hw_primary(  356): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  356): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  356): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  356): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  356): enable_audio_route: apply and update mixer path: audio-record
,D/ChimeraCfgMgr( 1733): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1733): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1733): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1733): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1733): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1733): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1733): Removing dialog suppression flag for package com.test.thalitest
,I/UpdateIcingCorporaServi( 1518): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/GOOGLEHELP_CompatibleDatabase( 1733): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1733): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1733): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1733): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1733): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1733): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1733): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,W/Launcher( 1301): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@22887347 new=com.google.android.velvet.VelvetApplication@22887347
D/GOOGLEHELP_CompatibleDatabase( 1733): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1733): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1733): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1733): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1733): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1733): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,D/WifiService(  818): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@273da20c}
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
,I/HotwordWorker( 1518): onReady
,I/ActivityManager(  818): Start proc 3931:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,I/ConfigFetchService( 1733): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,W/BaseAppContext( 1733): Using Auth Proxy for data requests.
,I/ConfigFetchService( 1733): service connected
,I/PeopleContactsSync( 1733): CP2 sync disabled
,W/BaseAppContext( 1733): Using Auth Proxy for data requests.
,I/Icing   ( 1733): doRemovePackageData com.test.thalitest
,E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659991315
E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/art     ( 3847): System.exit called, status: 0
I/AndroidRuntime( 3847): VM exiting with result code 0.
,I/UpdateIcingCorporaServi( 1518): UpdateCorporaTask done [took 105 ms] updated apps [took 105 ms] 
,I/GAv4    ( 3931): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3931):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3931):   adb logcat -s GAv4
,W/GAv4    ( 3931): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3931): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 3931): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 3931): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 3931): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 3931): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 3931): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/SQLiteDatabase( 3931): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
,E/SQLiteDatabase( 3931): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3931): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185),
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3931): ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3931): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3931): 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3931): ,	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 3931): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 3931): 	at fdw.a(Unknown Source)
,E/SQLiteDatabase( 3931): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 3931): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 3931): ,	at feb.run(Unknown Source)
E/SQLiteDatabase( 3931): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3931): 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3931): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3931): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/SQLiteDatabase( 3931): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 3931): 	at gir$c.run(Unknown Source)
,E/GAv4    ( 3931): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 3931): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 3931): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 3931): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3931): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
,E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3931): 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
,E/SQLiteDatabase( 3931): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3931): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3931): 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3931): 	at fdw$a.getWritableDatabase(Unknown Source)
,E/SQLiteDatabase( 3931): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 3931): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 3931): 	,at fdw.e(Unknown Source)
E/SQLiteDatabase( 3931): 	at fdy.b(Unknown Source),
E/SQLiteDatabase( 3931): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 3931): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3931): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3931): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3931): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3931): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 3931): 	at gir$c.run(Unknown Source)
,E/GAv4    ( 3931): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 3931): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 3931): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 3931): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 3931): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 3931): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 3931): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 3931): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3931): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3931): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3931): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 3931): 	at ael.a(PG:1521)
E/SQLiteDatabase( 3931): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 3931): 	at aen.run(PG:536)
,W/GAv4    ( 3931): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 3931): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 3931): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 3931): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 3931): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 3931): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 3931): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SQLiteDatabase( 3931): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 3931): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3931): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3931): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3931): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3931): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 3931): 	at ael.a(PG:1521)
E/SQLiteDatabase( 3931): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 3931): 	at aej.c(PG:139)
E/SQLiteDatabase( 3931): 	at aej.b(PG:398)
E/SQLiteDatabase( 3931): 	at agf.f(PG:417)
E/SQLiteDatabase( 3931): 	at oe.run(PG:1112)
E/SQLiteDatabase( 3931): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3931): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3931): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3931): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3931): 	at java.lang.Thread.run(Thread.java:818)
,E/AbstractDatabaseInstance( 3931): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 3931): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 3931): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 3931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 3931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 3931): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 3931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 3931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 3931): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 3931): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 3931): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 3931): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 3931): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 3931): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 3931): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 3931): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 3931): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 3931): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 3931): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 3931): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 3931): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 3931): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 3931): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 3931): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 3931): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 3931): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 3931): 	at java.lang.Thread.run(Thread.java:818)
E/SharedPreferencesImpl( 3931): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 3931): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
,W/GAv4    ( 3931): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 3931): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 3931): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 3931): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 3931): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/CAKEMIX_CRASHED( 3931): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 3931): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 3931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 3931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 3931): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 3931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 3931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 3931): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 3931): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 3931): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 3931): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 3931): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 3931): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 3931): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 3931): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 3931): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 3931): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 3931): 	at aen.run(PG:536)
,E/SharedPreferencesImpl( 3931): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 3931): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 3931): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 3931): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 3931): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/ResourcesManager( 3931): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3931): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  818): Start proc 3969:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,I/ActivityManager(  818): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
V/WindowManager(  818): addAppToken: AppWindowToken{2b411627 token=Token{10aa30e6 ActivityRecord{34b61341 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
,I/Process ( 3931): Sending signal. PID: 3931 SIG: 9
,E/lowmemorykiller(  255): Error writing /proc/3931/oom_score_adj; errno=22
,E/JavaBinder(  818): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  818): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  818): android.os.TransactionTooLargeException
W/ActivityManager(  818): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  818): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  818): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:797)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1181)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1281)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1891)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1455)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2473)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:998)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:896)
W/ActivityManager(  818): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6311)
W/ActivityManager(  818): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:512)
W/ActivityManager(  818): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  818): 	at android.os.Binder.execTransact(Binder.java:446)
,I/HotwordDetector( 1518): Closing mic
I/MicrophoneInputStream( 1518): mic_close com.google.android.apps.gsa.speech.audio.u@24710196
,D/audio_hw_primary(  356): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  356): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1518): Stopping hotword detection.
I/HotwordRecognitionRnr( 1518): Hotword detection finished
,I/ActivityManager(  818): Start proc 3986:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
,W/ActivityManager(  818): Spurious death for ProcessRecord{8f9ec09 3986:com.google.android.apps.docs/u0a46}, curProc for 3931: null
,W/OpenGLRenderer( 1301): Incorrectly called buildLayer on View: ew, destroying layer...
,E/Search.SharedPreferencesProto( 1518): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/ActivityManager(  818): Killing 3520:com.android.chrome/u0a40 (adj 15): empty #17
,E/native  ( 1211): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1211): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/SQLiteDatabase( 3969): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 3969): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3969): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3969): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3969): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3969): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3969): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3969): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3969): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3969): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3969): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3969): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3969): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3969): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3969): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3969): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 3969): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 3969): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 3969): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 3969): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 3969): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 3969): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 3969): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 3969): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3969): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 3969): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 3969): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 3969): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 3969): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 3969): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/AndroidRuntime( 3969): Shutting down VM
,--------- beginning of crash
E/AndroidRuntime( 3969): FATAL EXCEPTION: main
E/AndroidRuntime( 3969): Process: com.android.documentsui, PID: 3969
E/AndroidRuntime( 3969): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3969): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 3969): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 3969): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 3969): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3969): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 3969): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 3969): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 3969): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 3969): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 3969): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 3969): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3969): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3969): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 3969): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 3969): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3969): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3969): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3969): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 3969): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 3969): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 3969): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 3969): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 3969): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 3969): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 3969): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 3969): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 3969): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 3969): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 3969): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 3969): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 3969): 	... 9 more
I/ActivityManager(  818): Killing 3601:com.qualcomm.timeservice/1000 (adj 15): empty #17
,E/native  ( 1211): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1211): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,I/Icing   ( 1733): Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
,E/DropBoxManagerService(  818): Can't write: system_app_crash
E/DropBoxManagerService(  818): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  818): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  818): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  818): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  818): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  818): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  818): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  818): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  818): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  818): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  818): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  818): 	... 5 more
,I/ActivityManager(  818): Start proc 4010:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,E/Icing   ( 1733): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1733): Could not init tag ds.tag.deleted
,D/OpenGLRenderer(  818): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   (  818): Validating map...
,I/ActivityManager(  818): Killing 3622:com.google.android.deskclock/u0a44 (adj 15): empty #17
,D/ExternalStorage( 4010): After updating volumes, found 1 active roots
,E/native  ( 1211): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1211): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1211): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1211): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,I/OpenGLRenderer(  818): Initialized EGL, version 1.4
,D/OpenGLRenderer(  818): Enabling debug mode 0
,I/GAv4    ( 3986): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3986):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3986):   adb logcat -s GAv4
,W/GAv4    ( 3986): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3986): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,I/Icing   ( 1733): Indexing done 0A4562BF807829C124E952811A67787B55D6217E
,W/GAv4    ( 3986): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 3986): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 3986): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3986): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3986): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3986): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 3986): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 3986): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 3986): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 3986): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 3986): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 3986): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3986): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3986): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3986): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3986): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 3986): 	at gir$c.run(Unknown Source)
,E/GAv4    ( 3986): Opening the database failed, dropping the table and recreating it
,E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 3986): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 3986): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3986): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3986): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3986): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 3986): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 3986): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 3986): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 3986): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 3986): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 3986): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3986): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3986): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3986): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3986): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 3986): 	at gir$c.run(Unknown Source)
E/GAv4    ( 3986): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4    ( 3986): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/GAv4    ( 3986): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 3986): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/Icing   ( 1733): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1733): Writing status failed
E/Icing   ( 1733): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
E/SQLiteDatabase( 3986): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 3986): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3986): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3986): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3986): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 3986): 	at ael.a(PG:1521)
E/SQLiteDatabase( 3986): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 3986): 	at aen.run(PG:536)
,E/SQLiteDatabase( 3986): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 3986): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3986): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3986): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3986): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 3986): 	at ael.a(PG:1521)
E/SQLiteDatabase( 3986): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 3986): 	at aej.c(PG:139)
E/SQLiteDatabase( 3986): 	at aej.b(PG:398)
E/SQLiteDatabase( 3986): 	at agf.f(PG:417)
E/SQLiteDatabase( 3986): 	at oe.run(PG:1112)
E/SQLiteDatabase( 3986): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3986): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3986): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3986): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3986): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 3986): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 3986): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 3986): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 3986): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/Abstract,DatabaseInstance( 3986): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 3986): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 3986): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 3986): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 3986): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 3986): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 3986): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 3986): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 3986): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 3986): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 3986): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 3986): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 3986): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorNotificationActivity( 3986): Google Drive has stopped unexpectedly. Please provide additional details to help us diagnose the issue.
W/ResourcesManager( 3986): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3986): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/WifiService(  818): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@273da20c}
,D/OpenGLRenderer( 3986): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,V/JNIHelp ( 3986): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Atlas   ( 3986): Validating map...
,V/WindowManager(  818): Adding window Window{2d461cff u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 8 (after Window{1561c4d9 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
,V/WindowManager(  818): Adding window Window{2a6d6115 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 9 (before Window{2d461cff u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity})
,I/ProviderInstaller( 3986): Installed default security provider GmsCore_OpenSSL
,W/GAv4    ( 3986): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/GAv4    ( 3986): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 3986): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 3986): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 3986): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 3986): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 3986): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 3986): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 3986): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 3986): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3986): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3986): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3986): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 3986): 	at ael.a(PG:1521)
E/SQLiteDatabase( 3986): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 3986): 	at aej.c(PG:139)
E/SQLiteDatabase( 3986): 	at aej.a(PG:358)
E/SQLiteDatabase( 3986): 	at aej.a(PG:345)
E/SQLiteDatabase( 3986): 	at agf.d(PG:281)
E/SQLiteDatabase( 3986): 	at agf.b(PG:312)
E/SQLiteDatabase( 3986): 	at agf.a(PG:221)
E/SQLiteDatabase( 3986): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/SQLiteDatabase( 3986): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/SQLiteDatabase( 3986): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteDatabase( 3986): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteDatabase( 3986): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase( 3986): 	at android.os.Binder.execTransact(Binder.java:446)
E/GAv4    ( 3986): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 3986): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 3986): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 3986): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 3986): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 3986): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 3986): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 3986): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 3986): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 3986): 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 3986): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 3986): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 3986): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 3986): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 3986): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 3986): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 3986): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 3986): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 3986): 	,at aen.run(PG:536)
E/AbstractDatabaseInstance( 3986): Failed to query Account133 object
E/AbstractDatabaseInstance( 3986): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 3986): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
,E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 3986): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 3986): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 3986): 	at aev.getWritableDatabase(PG:238)
,E/AbstractDatabaseInstance( 3986): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 3986): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 3986): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 3986): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 3986): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 3986): 	at agf.d(PG:281)
E/AbstractDatabaseInstance( 3986): 	at agf.b(PG:312)
,E/AbstractDatabaseInstance( 3986): 	at agf.a(PG:221)
E/AbstractDatabaseInstance( 3986): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/AbstractDatabaseInstance( 3986): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/AbstractDatabaseInstance( 3986): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/AbstractDatabaseInstance( 3986): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/AbstractDatabaseInstance( 3986): ,	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/AbstractDatabaseInstance( 3986): 	at android.os.Binder.execTransact(Binder.java:446)
E/DatabaseUtils( 3986): Writing exception to parcel
E/DatabaseUtils( 3986): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DatabaseUtils( 3986): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DatabaseUtils( 3986): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209),
E/DatabaseUtils( 3986): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/DatabaseUtils( 3986): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/DatabaseUtils( 3986): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/DatabaseUtils( 3986): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/DatabaseUtils( 3986): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/DatabaseUtils( 3986): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/DatabaseUtils( 3986): ,	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/DatabaseUtils( 3986): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/DatabaseUtils( 3986): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/DatabaseUtils( 3986): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/DatabaseUtils( 3986): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/DatabaseUtils( 3986): 	,at aev.getWritableDatabase(PG:238)
E/DatabaseUtils( 3986): 	at ael.a(PG:1521)
E/DatabaseUtils( 3986): 	at hix$a.a(PG:125)
E/DatabaseUtils( 3986): 	at aej.c(PG:139)
E/DatabaseUtils( 3986): 	at aej.a(PG:358)
E/DatabaseUtils( 3986): 	at aej.a(PG:345)
E/DatabaseUtils( 3986): 	at agf.d(PG:281),
E/DatabaseUtils( 3986): 	at agf.b(PG:312)
E/DatabaseUtils( 3986): 	at agf.a(PG:221)
E/DatabaseUtils( 3986): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/DatabaseUtils( 3986): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/DatabaseUtils( 3986): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/DatabaseUtils( 3986): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/DatabaseUtils( 3986): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
,E/DatabaseUtils( 3986): 	at android.os.Binder.execTransact(Binder.java:446)
W/Documents( 3969): Failed to load some roots from com.google.android.apps.docs.storage: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
D/Documents( 3969): Update found 6 roots in 898ms
E/SQLiteDatabase( 3986): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 3986): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3986): 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3986): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3986): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3986): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3986): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 3986): 	at ael.a(PG:1521)
E/SQLiteDatabase( 3986): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 3986): 	at aej.c(PG:139)
E/SQLiteDatabase( 3986): 	at aej.a(PG:358)
E/SQLiteDatabase( 3986): 	at aej.a(PG:345)
E/SQLiteDatabase( 3986): 	at agf.c(PG:884)
E/SQLiteDatabase( 3986): 	at aii.doInBackground(PG:1063)
E/SQLiteDatabase( 3986): 	at an,droid.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 3986): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3986): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3986): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3986): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3986): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 3986): Failed to query Account133 object
E/AbstractDatabaseInstance( 3986): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 3986): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148),
E/AbstractDatabaseInstance( 3986): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 3986): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 3986): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 3986): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 3986): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 3986): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 3986): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 3986): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 3986): 	at agf.c(PG:884)
E/AbstractDatabaseInstance( 3986): 	at aii.doInBackground(PG:1063)
E/AbstractDatabaseInstance( 3986): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/AbstractDatabaseInstance( 3986): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 3986): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AbstractDatabaseInstance( 3986): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 3986): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 3986): 	at java.lang.Thread.run(Thread.java:818)
,W/GAv4    ( 3986): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 3986): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 3986): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 3986): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 3986): Local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 3986): Error opening database: android.database.sqlite.SQLiteException: Database open failed
I/ActivityManager(  818): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 3986): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 3986): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
W/GAv4    ( 3986): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 3986): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 3986): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 3986): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 3986): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/Adreno  ( 3986): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 3986): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 3986): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,I/Process ( 3986): Sending signal. PID: 3986 SIG: 9
,W/InputDispatcher(  818): channel '2d461cff com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  818): channel '2d461cff com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
I/WindowState(  818): WIN DEATH: Window{2a6d6115 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
W/InputDispatcher(  818): channel '2a6d6115 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  818): channel '2a6d6115 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  818): Attempted to unregister already unregistered input channel '2a6d6115 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)'
,I/ActivityManager(  818): Process com.google.android.apps.docs (pid 3986) has died
,W/ActivityManager(  818): Force removing ActivityRecord{34b61341 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}: app died, no saved state
,W/InputDispatcher(  818): Attempted to unregister already unregistered input channel '2d461cff com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)'
,W/WindowManager(  818): Failed looking up window
W/WindowManager(  818): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@3c062c1e does not exist
W/WindowManager(  818): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8539)
W/WindowManager(  818): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8530)
W/WindowManager(  818): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1142)
W/WindowManager(  818): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
,I/WindowState(  818): WIN DEATH: null
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
,I/ActivityManager(  818): Killing 3579:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,E/Search.SharedPreferencesProto( 1518): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/ConfigService( 1430): onDestroy
,E/QMI_FW  (  818): xport_send: Sendto failed for port 4352
E/LocSvc_api_v02(  818): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1659991315
E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
E/QMI_FW  (  818): xport_send: Sendto failed for port 4352
,E/LocSvc_api_v02(  818): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed,
E/QMI_FW  (  818): xport_send: Sendto failed for port 4352
E/LocSvc_api_v02(  818): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_ApiV02(  818): E/virtual loc_api_adapter_err LocApiV02::injectPosition(double, double, float):565]: error! status = eLOC_CLIENT_FAILURE_INTERNAL, inject_pos_ind.status = eQMI_LOC_SUCCESS_V02
E/QMI_FW  (  818): xport_send: Sendto failed for port 4352
E/LocSvc_api_v02(  818): E/locClientSendReq:2446]: send_msg_sync error: -1
,E/LocSvc_ApiV02(  818): E/virtual loc_api_adapter_err LocApiV02::injectPosition(double, double, float):565]: error! status = eLOC_CLIENT_FAILURE_INTERNAL, inject_pos_ind.status = eQMI_LOC_SUCCESS_V02
,E/kickstart(  868): ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
E/kickstart(  868): ERROR: function: sahara_main:1143 Sahara protocol error
E/kickstart(  868): ERROR: function: main:268 Uploading  Image using Sahara protocol failed
,I/kickstart(  868): STATUS: Wrote to /sys/power/wake_unlock
,I/Atfwd_Daemon(  373): Received sys_event: 2 from QMI devId: rmnet_usb1,
E/ThermalEngine(  364): modem_clnt_error_cb: with -2 called for clnt 0x7
E/ThermalEngine(  364): qmi_clnt_error_cb: with error -2 called for clnt FUSION
D/        (  356): csd_client_error_cb: error -2 cb_data 0xb546b060
D/        (  356): csd_client_error_cb: MDM reset
E/        (  356): deinit: QMI - result 0, error 0, CSD - valid 0, status 0, rc -2
E/        (  356): csd_service_deinit: Error -1 deiniting CSD
,I/Atfwd_Daemon(  373): Received sys_event: 2 from QMI devId: rmnet_usb0
I/Atfwd_Daemon(  373): Modem Out Of Service --> Release ATCOP service client handles, if any
I/Atfwd_Daemon(  373): release_client returns -1, qmiErroCode = 0 for qmiPort: rmnet_usb0 & userHandle: 486606848
I/Atfwd_Daemon(  373): Received sys_event: 2 from QMI devId: rmnet_usb5
,I/Atfwd_Daemon(  373): Received sys_event: 2 from QMI devId: rmnet_usb2,
I/Atfwd_Daemon(  373): Received sys_event: 2 from QMI devId: rmnet_usb3
I/Atfwd_Daemon(  373): Received sys_event: 2 from QMI devId: rmnet_usb4
I/Atfwd_Daemon(  373): Received sys_event: 2 from QMI devId: rmnet_usb6
,I/Atfwd_Daemon(  373): Received sys_event: 2 from QMI devId: rmnet_usb7
I/ThermalEngine(  364): qmi: Instance id 157 for fusion TS
,E/        (  356): csd_service_deinit: notifier handle release rc:0
,D/        (  356): csd_service_init: qmi_client_notifier_init() successful
,E/ThermalEngine(  364): qmi_clnt_error_cb: with error -2 called for clnt MODEM
,E/LocSvc_ApiV02(  818): E/void LocApiV02::errorCb(locClientHandleType, locClientErrorEnumType):2688]: Service unavailable error
,E/LocSvc_ApiV02(  818): E/void LocApiV02::errorCb(locClientHandleType, locClientErrorEnumType):2688]: Service unavailable error
,V/ImsSenderRxr( 1269): Read packet: 15 bytes
,V/ImsSenderRxr( 1269): processResponse
D/ImsSenderRxr( 1269): Response data: [12, 13, -1, -1, -1, -1, 16, 3, 24, -43, 1, 32, 0, 8, 0]
D/ImsSenderRxr( 1269):  Tag -1 3 213 0
,I/str_params(  356): key: 'all_call_states' value: ''
,I/str_params(  356): key: 'all_call_states' value: ''
I/str_params(  356): key: 'all_call_states' value: ''
,W/WindowManager(  818): App freeze timeout expired.

```
