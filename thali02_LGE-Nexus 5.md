#### Test 503880196dc97cd_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
W/GAV2    ( 2352): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
--------- beginning of system
W/ActivityManager(  755): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 2352): Observing account changes for notifications
I/Gmail   ( 2352): getAccountsCursor
V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SystemBroadcastReceiver( 1078): Boot has been completed
I/SystemBroadcastReceiver( 1078): toggleAppIcon() : FLAG_SYSTEM = true
V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Exchange( 2383): EasService.onCreate
I/Exchange( 2383): RestartPingTask
I/ActivityManager(  755): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2438 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SQLiteLog( 2352): (283) recovered 73 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
I/Exchange( 2383): RestartPingsTask did not start any pings.
I/Exchange( 2383): PSS stopIfIdle
I/Exchange( 2383): PSS has no active accounts; stopping service.
I/Exchange( 2383): onDestroy
I/ActivityManager(  755): Killing 1653:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
I/Gmail   ( 2352): notifyAccountChanged
I/Gmail   ( 2352): getAccountsCursor
I/Gmail   ( 2352): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 2352): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 2352): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 2352): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/libprocessgroup(  755): failed to open /acct/uid_10061/pid_1653/cgroup.procs: No such file or directory
V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  755): Killing 1240:com.android.printspooler/u0a72 (adj 15): empty #17
W/libprocessgroup(  755): failed to open /acct/uid_10072/pid_1240/cgroup.procs: No such file or directory
I/Gmail   ( 2352): getAccountsCursor
V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2438): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/Finsky  ( 2438): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 2438): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 2438): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/Volley  ( 2438): [222] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 2438): [229] DiskBasedCache.clear: Cache cleared.
I/ActivityManager(  755): Killing 1877:com.android.keychain/1000 (adj 15): empty #17
W/libprocessgroup(  755): failed to open /acct/uid_1000/pid_1877/cgroup.procs: No such file or directory
V/UserPresentBroadcastReceiver( 1311): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/Ads     ( 2438): Skipping gmscore version check
I/ActivityManager(  755): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=2489 uid=10003 gids={50003, 9997} abi=armeabi-v7a
I/art     (  194): Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 187us total 8.272ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 7.348ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 166us total 9.716ms
D/Finsky  ( 2438): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 2438): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 2438): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 2438): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/CellBroadcastReceiver( 2489): onReceive Intent { act=android.intent.action.SERVICE_STATE flg=0x10 cmp=com.android.cellbroadcastreceiver/.CellBroadcastReceiver (has extras) }
D/CellBroadcastReceiver( 2489): Intent ACTION_SERVICE_STATE_CHANGED
D/CellBroadcastReceiver( 2489): Service state changed! 3 Full: 3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=false Current state=-1
I/ActivityManager(  755): Killing 1844:com.google.android.dialer/u0a10 (adj 15): empty #17
W/libprocessgroup(  755): failed to open /acct/uid_10010/pid_1844/cgroup.procs: No such file or directory
,D/SIP     ( 1218): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
I/ActivityManager(  755): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2526 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/GAv4-SVC( 1577): Google Analytics 8.3.01 is starting up.
I/GAV2    ( 1376): Thread[GAThread,5,main]: No campaign data found.
D/AndroidRuntime( 2532): 
D/AndroidRuntime( 2532): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2532): CheckJNI is OFF
W/ContextImpl( 2003): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
I/GAV2    ( 2003): Thread[GAThread,5,main]: No campaign data found.
D/AndroidRuntime( 2532): Calling main entry com.android.commands.am.Am
I/ActivityManager(  755): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 2532): Shutting down VM
I/MusicStore( 2526): Database version: 120
I/ActivityManager(  755): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2567 uid=10277 gids={50277, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/MicrophoneInputStream( 1376): mic_close gfk@3ebd0c7e
D/audio_hw_primary(  183): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  183): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1376): Stopping hotword detection.
I/HotwordRecognitionRnr( 1376): Hotword detection finished
I/WebViewFactory( 2567): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/art     (  755): Explicit concurrent mark sweep GC freed 13366(680KB) AllocSpace objects, 2(36KB) LOS objects, 33% free, 27MB/40MB, paused 689us total 58.637ms
I/LibraryLoader( 2567): Time to load native libraries: 1 ms (timestamps 6251-6252)
,I/LibraryLoader( 2567): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 2567): Binding Chromium to main looper Looper (main, tid 1) {1ae6aff1}
,I/LibraryLoader( 2567): Expected native library version number "",actual native library version number ""
I/chromium( 2567): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2567): Initializing chromium process, singleProcess=true
,W/art     ( 2567): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2567): ApplicationContext is null in ApplicationStatus
,W/chromium( 2567): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2567): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2567): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2567): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2567): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/ResourcesManager( 2526): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2526): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2526): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/BluetoothManagerService(  755): Message: 20
D/BluetoothManagerService(  755): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@eafc78e:true
,D/BluetoothAdapter( 2567): 677848307: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2567): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2567): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2567): CordovaWebView is running on device made by: LGE
,W/ActivityThread( 2526): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 2526): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@17533307: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 2526): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 2526): GMSCore installation verified
,W/art     ( 2567): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2567): Attempt to remove local handle scope entry from IRT, ignoring
,I/ConfigStore( 2526): Config Database version: 1
,D/OpenGLRenderer( 2567): Render dirty regions requested: true
,D/Atlas   ( 2567): Validating map...
,W/chromium( 2567): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2567): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2567): Enabling debug mode 0
,I/MediaRouter( 2526): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=11, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/ActivityManager(  755): Displayed com.example.hello/.MainActivity: +490ms (total +15s101ms)
,W/BindingManager( 2567): Cannot call determinedVisibility() - never saw a connection for the pid: 2567
,I/chromium( 2567): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/GHttpClientFactory( 2526): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2526): Using platform SSLCertificateSocketFactory
,D/JsMessageQueue( 2567): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 2567): Unable to open asset URL: file:///android_asset/www/jxcore.js
,W/GCoreFlp( 1311): No location to return for getLastLocation()
,W/FusedLocationProvider( 1337): location=null
,D/ChimeraCfgMgr( 1577): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1577): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1577): [KidAccountFixer] No network connection
,D/GCM     ( 1337): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/jxcore_app_log( 2567): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258381056
,D/JX-Cordova( 2567): jxcore cordova android initializing
,I/MediaStoreImporter( 2526): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,W/jxcore-log( 2567): Initializing JXcore engine
W/jxcore-log( 2567): JXcore engine is ready
,W/jxcore-log( 2567): Starting JXcore engine
,I/ActivityManager(  755): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2639 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,W/m.example.hello( 2567): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6625]" dev="sockfs" ino=6625 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/m.example.hello( 2567): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/m.example.hello( 2567): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6703]" dev="sockfs" ino=6703 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 2567): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17715]" dev="sockfs" ino=17715 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,I/ActivityManager(  755): Killing 1952:com.google.android.onetimeinitializer/u0a12 (adj 15): empty #17
,W/jxcore-log( 2567): Platform android
W/jxcore-log( 2567): 
W/jxcore-log( 2567): Process ARCH arm
W/jxcore-log( 2567): 
,W/libprocessgroup(  755): failed to open /acct/uid_10012/pid_1952/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1376): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
D/PackageBroadcastService( 1577): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/ChimeraCfgMgr( 1577): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1577): Loading module APK com.google.android.play.games
,I/jxcore-log( 2567): JXcore Cordova bridge is ready!
I/jxcore-log( 2567): 
W/jxcore-log( 2567): JXcore engine is started
,I/ActivityManager(  755): Killing 1978:com.android.managedprovisioning/u0a14 (adj 15): empty #17
,E/jxcore-log( 2567): >> LGE-Nexus 5
E/jxcore-log( 2567): 
,I/jxcore-log( 2567): Total memory 1946181632
I/jxcore-log( 2567): 
,I/jxcore-log( 2567): Free memory 377475072
I/jxcore-log( 2567): 
I/jxcore-log( 2567): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2567): 
I/jxcore-log( 2567): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2567): 
,I/jxcore-log( 2567): userPath [ 'www' ]
I/jxcore-log( 2567): 
,I/jxcore-log( 2567): Size 1080 1776
I/jxcore-log( 2567): 
,W/libprocessgroup(  755): failed to open /acct/uid_10014/pid_1978/cgroup.procs: No such file or directory
,I/jxcore-log( 2567): Screen Brightness 82
I/jxcore-log( 2567): 
,E/jxcore-log( 2567): Dummy Error Log.
E/jxcore-log( 2567): 
,D/ChimeraCfgMgr( 1577): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1577): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1577): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/PeopleContactsSync( 1577): CP2 sync disabled
,D/AsyncTaskServiceImpl( 1577): Submit a task: h
,D/ChimeraCfgMgr( 1577): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 1577): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/h       ( 1577): Processing package: com.example.hello
,D/GassUtils( 1577): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
D/h       ( 1577): Found info for package com.example.hello in db.
,I/ActivityManager(  755): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2668 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,W/BaseAppContext( 1577): Using Auth Proxy for data requests.
W/BaseAppContext( 1577): Using Auth Proxy for data requests.
,I/art     ( 1337): Explicit concurrent mark sweep GC freed 9961(512KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 19MB/32MB, paused 633us total 24.077ms
,W/BaseAppContext( 1577): Using Auth Proxy for data requests.
,W/BaseAppContext( 1577): Using Auth Proxy for data requests.
,W/BaseAppContext( 1577): Using Auth Proxy for data requests.
,W/BaseAppContext( 1577): Using Auth Proxy for data requests.
,I/UpdateIcingCorporaServi( 1376): UpdateCorporaTask done [took 402 ms] updated apps [took 402 ms] 
,I/jxcore-log( 2567): getBuffer is called!!!!
I/jxcore-log( 2567): 
,D/ChimeraCfgMgr( 1577): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1577): Module APK com.google.android.play.games already loaded
,I/GAv4    ( 2668): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2668):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2668):   adb logcat -s GAv4
,W/GAv4    ( 2668): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2668): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2668): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 2668): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,W/ResourcesManager( 2668): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2668): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  755): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2706 uid=10067 gids={50067, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  755): Killing 1924:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_10002/pid_1924/cgroup.procs: No such file or directory
,W/ResourcesManager( 2706): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 2668): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 2668): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2668): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  755): Explicit concurrent mark sweep GC freed 10566(526KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/40MB, paused 655us total 46.337ms
,I/Icing   ( 1577): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
,D/Icing   ( 1577): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1577): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,D/Finsky  ( 2438): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
,I/ActivityManager(  755): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=2738 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 1790): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1790): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2738): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,V/JNIHelp ( 1790): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/CalendarProvider2( 2738): Created com.android.providers.calendar.CalendarAlarmManager@10264b98(com.android.providers.calendar.CalendarProvider2@1ae6aff1)
,E/SQLiteLog( 2738): (284) automatic index on view_events(_id)
,W/System  ( 1790): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 1790): Installed default security provider GmsCore_OpenSSL
,I/CalendarProvider2( 2738): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 2738): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  755): Killing 2029:com.google.android.configupdater/u0a36 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_10036/pid_2029/cgroup.procs: No such file or directory
,I/GAV2    ( 2352): Thread[GAThread,5,main]: No campaign data found.
,I/iu.UploadsManager( 1577): End new media; added: 0, uploading: 0, time: 44 ms
,D/WearableService( 1311): callingUid 10008, callindPid: 1311
,I/MusicLeanback( 2526): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 2526): Stop autocaching.
,E/GmsUtils( 2526): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 2526): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  755): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  755): Message: 2
,D/WifiService(  755): New client listening to asynchronous messages
,D/WifiService(  755): setWifiEnabled: false pid=2567, uid=10277
E/WifiService(  755): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 2567): ****TEST TOOK:  5059  ms ****
I/jxcore-log( 2567): 
I/jxcore-log( 2567): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2567): 
,W/ProcessCpuTracker(  755): Skipping unknown process pid 2796
W/ProcessCpuTracker(  755): Skipping unknown process pid 2797
W/ProcessCpuTracker(  755): Skipping unknown process pid 2799
W/ProcessCpuTracker(  755): Skipping unknown process pid 2800
W/ProcessCpuTracker(  755): Skipping unknown process pid 2801
,I/InputReader(  755): Reconfiguring input devices.  changes=0x00000010
,I/UpdateIcingCorporaServi( 1376): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1260): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@33a87d6 new=com.google.android.velvet.VelvetApplication@33a87d6
,D/PackageBroadcastService( 1577): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1577): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1577): updateResources: need to parse f{com.google.android.gms}
,D/BackupManagerService(  755): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  755): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  755): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  755): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  755): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@99be4fb
,V/GmsNetworkLocationProvi( 1311): DISABLE
,I/GCoreNlp( 1311): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/AndroidRuntime( 2805): 
D/AndroidRuntime( 2805): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 2805): CheckJNI is OFF
,I/Launcher( 1260): Deferring update until onResume
,W/ResourcesManager( 1260): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/AndroidRuntime( 2805): Calling main entry com.android.commands.pm.Pm
W/ResourcesManager( 1260): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  755): Force stopping com.example.hello appid=10277 user=-1: uninstall pkg
I/ActivityManager(  755): Killing 2567:com.example.hello/u0a277 (adj 0): stop com.example.hello
,I/Launcher( 1260): Deferring update until onResume
,I/WindowState(  755): WIN DEATH: Window{7d8cbb5 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  755): Client connection lost with reason: 4
,W/PackageSettings(  755): Skipping PackageSetting{1372f2fe com.test.thalitest/10270} due to missing metadata
,W/ActivityManager(  755): Force removing ActivityRecord{3df3f265 u0 com.example.hello/.MainActivity t214}: app died, no saved state
,W/ActivityManager(  755): Spurious death for ProcessRecord{2514d442 2567:com.example.hello/u0a277}, curProc for 2567: null
,I/ActivityManager(  755): Force stopping com.example.hello appid=10277 user=0: pkg removed
,I/InputReader(  755): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1078): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1311): Ignoring removeGeofence because network location is disabled.,
,I/Keyboard.Facilitator.DecoderInitializer( 1078): run()
,D/BackupManagerService(  755): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/Decoder ( 1078): createOrResetDecoder
,D/JobSchedulerService(  755): Receieved: android.intent.action.PACKAGE_REMOVED
,D/VoicemailCleanupService( 1367): Cleaning up data for package: com.example.hello
,D/TaskPersister(  755): removeObsoleteFile: deleting file=214_task.xml
,I/ConfigService( 1337): onCreate
,I/art     ( 1376): Explicit concurrent mark sweep GC freed 24827(1760KB) AllocSpace objects, 16(2MB) LOS objects, 25% free, 18MB/25MB, paused 2.464ms total 68.713ms
,I/UpdateIcingCorporaServi( 1376): UpdateCorporaTask done [took 391 ms] updated apps [took 391 ms] 
,I/UpdateIcingCorporaServi( 1376): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1078): run()
,I/art     (  755): Explicit concurrent mark sweep GC freed 23367(1413KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 2.106ms total 104.940ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1078): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1078): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1078): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1078): run()
I/StatsUtilsManager( 1078): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1078): shouldRecordStats() = Too Soon
,W/Launcher( 1260): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@33a87d6 new=com.google.android.velvet.VelvetApplication@33a87d6
,D/AndroidRuntime( 2805): Shutting down VM
,I/ActivityManager(  755): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2860 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1376): UpdateCorporaTask done [took 125 ms] updated apps [took 125 ms] 
,W/ContextImpl( 2860): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1577): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1577): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1577): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1577): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1577): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1577): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1337): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1337): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1577): Removing dialog suppression flag for package com.example.hello
,I/MicrophoneInputStream( 1376): mic_starting gfk@36e28d97
,I/HotwordRecognitionRnr( 1376): Starting hotword detection.
,I/AudioFlinger(  183): AudioFlinger's thread 0xb1db9000 ready to run
,I/MicrophoneInputStream( 1376): mic_started gfk@36e28d97
,I/art     ( 1577): Explicit concurrent mark sweep GC freed 37542(2MB) AllocSpace objects, 26(416KB) LOS objects, 40% free, 21MB/35MB, paused 1.620ms total 52.215ms
,D/audio_hw_primary(  183): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
,D/msm8974_platform(  183): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
D/        (  183): Failed to fetch the lookup information of the device 0000003E 
E/ACDB-LOADER(  183): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  183): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  183): enable_audio_route: apply and update mixer path: audio-record
I/ActivityManager(  755): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=2892 uid=10039 gids={50039, 9997} abi=armeabi-v7a
D/gH_CompatibleDatabase( 1577): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1577): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1577): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1577): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1577): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1577): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1577): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1577): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1577): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
I/ActivityManager(  755): Killing 2063:com.google.android.keep/u0a71 (adj 15): empty #17
,D/gH_CompatibleDatabase( 1577): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1577): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1577): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1577): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/HotwordWorker( 1376): onReady
,I/ActivityManager(  755): Killing 2088:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_1000/pid_2088/cgroup.procs: No such file or directory
,W/libprocessgroup(  755): failed to open /acct/uid_10071/pid_2063/cgroup.procs: No such file or directory
,W/BaseAppContext( 1577): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1577): App measurement is starting up
,W/BaseAppContext( 1577): Using Auth Proxy for data requests.
,I/PeopleContactsSync( 1577): CP2 sync disabled
,E/SQLiteDatabase( 1577): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 1577): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1577): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1577): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.drive.database.m.b(SourceFile:600)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.drive.database.m.a(SourceFile:594)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.drive.database.o.run(SourceFile:615)
,I/Icing   ( 1577): doRemovePackageData com.example.hello
,E/SQLiteDatabase( 1577): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1577): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1577): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1577): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/SQLiteDatabase( 1577): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/SQLiteDatabase( 1577): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/SQLiteDatabase( 1577): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1577): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/SQLiteDatabase( 1577): 	at java.lang.Thread.run(Thread.java:818)
E/ClearPendingStateOp( 1577): Runtime exception while performing operation
E/ClearPendingStateOp( 1577): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1577): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1577): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 1577): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 1577): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1577): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1577): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1577): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 1577): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 1577): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 1577): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/ClearPendingStateOp( 1577): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearPendingStateOp( 1577): 	at android.database.sqlite.SQLiteOpenHel,per.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 1577): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 1577): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/ClearPendingStateOp( 1577): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/ClearPendingStateOp( 1577): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1577): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1577): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1577): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/ClearPendingStateOp( 1577): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1577): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1577): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 1577): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1577): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1577): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1577): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1577): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 1577): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 1577): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1577): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1577): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1577): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 1577): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 1577): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 1577): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
F/ClearPendingStateOp( 1577): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
F/ClearPendingStateOp( 1577): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 1577): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 1577): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
F/ClearPendingStateOp( 1577): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
F/ClearPendingStateOp( 1577): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1577): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1577): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1577): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
F/ClearPendingStateOp( 1577): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1577): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1577): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 1577): 	at java.lang.Thread.run(Thread.java:818)
--------- beginning of crash
E/AndroidRuntime( 1577): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 1577): Process: com.google.android.gms, PID: 1577
E/AndroidRuntime( 1577): android.database.sqlite.SQLiteException: not an error (code 0,): Could not open the database in read/write mode.
E/AndroidRuntime( 1577): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 1577): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 1577): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 1577): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 1577): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 1577): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 1577): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 1577): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 1577): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 1577): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/AndroidRuntime( 1577): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 1577): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 1577): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 1577): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
E/AndroidRuntime( 1577): 	at com.google.android.gms.drive.database.m.b(SourceFile:600)
E/AndroidRuntime( 1577): 	at com.google.android.gms.drive.database.m.a(SourceFile:594)
E/AndroidRuntime( 1577): 	at com.google.android.gms.drive.database.o.run(SourceFile:615)
E/DropBoxManagerService(  755): Can't write: system_app_wtf
E/DropBoxManagerService(  755): java.io.FileNotFoundException: /data/system/dropbox/drop85.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  755): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  755): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  755): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  755): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  755): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  755): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  755): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  755): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  755): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  755): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  755): 	... 5 more
E/DropBoxManagerService(  755): Can't write: system_app_crash
E/DropBoxManagerService(  755): java.io.FileNotFoundException: /data/system/dropbox/drop86.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  755): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  755): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  755): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  755): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  755): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  755): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  755): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  755): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  755): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  755): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  755): 	... 5 more
E/SQLiteDatabase( 1577): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 1577): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1577): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1577): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1062)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.measurement.internal.d.k(SourceFile:281)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.measurement.internal.d.e(SourceFile:724)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.measurement.internal.ak.n(SourceFile:1003)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.measurement.internal.ak.k(SourceFile:1014)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.measurement.internal.ak.b(SourceFile:263)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.measurement.internal.al.run(SourceFile:162)
E/SQLiteDatabase( 1577): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 1577): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.measurement.internal.aj.run(SourceFile:272)
E/GMPM-SVC( 1577): Opening the database failed, dropping and recreating it
E/SQLiteDatabase( 1577): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 1577): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1577): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1577): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1074)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.measurement.internal.d.k(SourceFile:281)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.measurement.internal.d.e(SourceFile:724)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.measurement.internal.ak.n(SourceFile:1003)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.measurement.internal.ak.k(SourceFile:1014)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.measurement.internal.ak.b(SourceFile:263)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.measurement.internal.al.run(SourceFile:162)
E/SQLiteDatabase( 1577): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 1577): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.measurement.internal.aj.run(SourceFile:272)
E/GMPM-SVC( 1577): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1074)
W/GMPM-SVC( 1577): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1074)
E/GMPM-SVC( 1577): Task exception on worker thread: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1074)
W/GMPM-SVC( 1577): Error opening database: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1058)
E/GMPM-SVC( 1577): Error deleting application data. appId, error: com.example.hello, android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1058)
W/ResourcesManager(  755): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  755): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/SharedPreferencesImpl( 1577): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1577): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1577): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1577): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1577): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1577): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
D/OpenGLRenderer(  755): Render dirty regions requested: true
D/Atlas   (  755): Validating map...
D/ConnectivityService(  755): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/qdhwcomposer(  171): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  171): hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
E/qdoverlay(  171): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  171): MdpData failed to play
E/qdoverlay(  171): == Dump MdpData start ==
E/qdoverlay(  171): == Dump OvFD fd=30 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  171): mOvData msmfb_overlay_data id=64
E/qdoverlay(  171): data msmfb_data offset=0 memid=35 id=0 flags=0x0 priv=0
E/qdoverlay(  171): == Dump MdpData end ==
E/qdhwcomposer(  171): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  171): hwc_set_primary: MDPComp draw failed
E/qdhwcomposer(  171): display_commit: MSMFB_DISPLAY_COMMIT for primary failed
E/qdhwcomposer(  171): hwc_set_primary: display commit fail!
I/Adreno-EGL(  755): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  755): Initialized EGL, version 1.4
D/OpenGLRenderer(  755): Enabling debug mode 0
I/ActivityManager(  755): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=2926 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,E/qdoverlay(  171): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  171): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  171): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
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
,W/DriveInitializer( 1577): Awaiting to be initialized
,W/DriveInitializer( 1577): Background init thread started
,E/SQLiteDatabase( 1577): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 1577): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1577): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1577): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1577): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.drive.database.m.b(SourceFile:600)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.drive.database.m.a(SourceFile:594)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.drive.database.k.a(SourceFile:248)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.drive.database.k.a(SourceFile:329)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.drive.database.f.h(SourceFile:1062)
E/SQLiteDatabase( 1577): 	at com.google.android.gms.drive.s.run(SourceFile:62)
,E/DocListDatabase( 1577): Failed to delete from ContentFileDeletionLock154 table
E/DocListDatabase( 1577): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DocListDatabase( 1577): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DocListDatabase( 1577): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/DocListDatabase( 1577): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/DocListDatabase( 1577): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/DocListDatabase( 1577): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/DocListDatabase( 1577): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/DocListDatabase( 1577): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/DocListDatabase( 1577): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/DocListDatabase( 1577): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/DocListDatabase( 1577): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/DocListDatabase( 1577): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/DocListDatabase( 1577): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/DocListDatabase( 1577): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/DocListDatabase( 1577): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
E/DocListDatabase( 1577): 	at com.google.android.gms.drive.database.m.b(SourceFile:600)
E/DocListDatabase( 1577): 	at com.google.android.gms.drive.database.m.a(SourceFile:594)
E/DocListDatabase( 1577): 	at com.google.android.gms.drive.database.k.a(SourceFile:248)
E/DocListDatabase( 1577): 	at com.google.android.gms.drive.database.k.a(SourceFile:329)
E/DocListDatabase( 1577): 	at com.google.android.gms.drive.database.f.h(SourceFile:1062)
E/DocListDatabase( 1577): 	at com.google.android.gms.drive.s.run(SourceFile:62)
W/DriveInitializer( 1577): Background init thread ended
I/Process ( 1577): Sending signal. PID: 1577 SIG: 9
,W/OpenGLRenderer( 1260): Incorrectly called buildLayer on View: adg, destroying layer...
W/OpenGLRenderer( 1260): Incorrectly called buildLayer on View: adg, destroying layer...
,D/ConnectivityService(  755): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@31e4dc75)
D/ConnectivityService(  755): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  755): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ActivityManager(  755): Process com.google.android.gms (pid 1577) has died
,W/ActivityManager(  755): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
,W/ActivityManager(  755): Scheduling restart of crashed service com.google.android.gms/.usagereporting.service.UsageReportingService in 11000ms
,W/ActivityManager(  755): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 21000ms
W/ActivityManager(  755): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 21000ms
W/ActivityManager(  755): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 31000ms
W/ActivityManager(  755): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 31000ms
W/ActivityManager(  755): Scheduling restart of crashed service com.google.android.gms/.ads.identifier.service.AdvertisingIdService in 31000ms
W/ActivityManager(  755): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 41000ms

```
