#### Test 50388019c82294c_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
W/System  ( 2309): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2309): Installed default security provider GmsCore_OpenSSL
E/YouTube MDX( 2309): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
I/dex2oat ( 2346): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-616876219.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads-616876219.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 2346): dex2oat took 29.782ms (threads: 4)
W/InstanceID/Rpc( 2309): Found 10008
V/Babel   ( 1845): babel boot account: thalitester@gmail.com
--------- beginning of system
I/ActivityManager(  761): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2406 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
E/SQLiteLog( 1845): (284) automatic index on conversation_participants_view(conversation_id)
W/VideoCapabilities( 1845): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 1845): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 1845): Unrecognized profile 2130706433 for video/avc
E/SQLiteLog( 1845): (284) automatic index on conversation_participants_view(conversation_id)
E/SQLiteLog( 1845): (284) automatic index on conversation_participants_view(conversation_id)
I/GAv4    ( 2406): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2406):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2406):   adb logcat -s GAv4
W/GAv4    ( 2406): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2406): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2406): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  761): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2428 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  761): Killing 1678:com.android.settings/1000 (adj 15): empty #17
D/WifiService(  761): Client connection lost with reason: 4
W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_1678/cgroup.procs: No such file or directory
I/Gmail   ( 2428): getAccountsCursor
D/ActivityThread( 2428): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  761): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=2454 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/GAV2    ( 2428): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/art     (  761): Explicit concurrent mark sweep GC freed 21072(1052KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/40MB, paused 911us total 49.880ms
W/ActivityManager(  761): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 2428): Observing account changes for notifications
I/Gmail   ( 2428): getAccountsCursor
I/Exchange( 2454): EasService.onCreate
V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  761): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2489 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  194): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 169us total 10.151ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 169us total 7.328ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.781ms
V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Exchange( 2454): RestartPingTask
I/Exchange( 2454): RestartPingsTask did not start any pings.
I/Exchange( 2454): PSS stopIfIdle
I/Exchange( 2454): PSS has no active accounts; stopping service.
I/Exchange( 2454): onDestroy
I/ActivityManager(  761): Killing 1711:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
E/SQLiteLog( 2428): (283) recovered 125 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
I/Gmail   ( 2428): notifyAccountChanged
I/Gmail   ( 2428): getAccountsCursor
I/Gmail   ( 2428): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 2428): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 2428): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 2428): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/libprocessgroup(  761): failed to open /acct/uid_10061/pid_1711/cgroup.procs: No such file or directory
V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  761): Killing 1219:com.android.printspooler/u0a72 (adj 15): empty #17
W/libprocessgroup(  761): failed to open /acct/uid_10072/pid_1219/cgroup.procs: No such file or directory
D/Finsky  ( 2489): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/Gmail   ( 2428): getAccountsCursor
V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2489): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 2489): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 2489): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/Volley  ( 2489): [227] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 2489): [234] DiskBasedCache.clear: Cache cleared.
I/ActivityManager(  761): Killing 1936:com.android.keychain/1000 (adj 15): empty #17
D/Ads     ( 2489): Skipping gmscore version check
I/SystemBroadcastReceiver( 1072): Boot has been completed
I/SystemBroadcastReceiver( 1072): toggleAppIcon() : FLAG_SYSTEM = true
W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_1936/cgroup.procs: No such file or directory
D/Finsky  ( 2489): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 2489): [1] 2.run: Finished loading 1 libraries.
V/UserPresentBroadcastReceiver( 1266): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/Finsky  ( 2489): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 2489): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  761): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=2548 uid=10003 gids={50003, 9997} abi=armeabi-v7a
D/CellBroadcastReceiver( 2548): onReceive Intent { act=android.intent.action.SERVICE_STATE flg=0x10 cmp=com.android.cellbroadcastreceiver/.CellBroadcastReceiver (has extras) }
D/CellBroadcastReceiver( 2548): Intent ACTION_SERVICE_STATE_CHANGED
D/CellBroadcastReceiver( 2548): Service state changed! 3 Full: 3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=false Current state=-1
I/ActivityManager(  761): Killing 1900:com.google.android.dialer/u0a10 (adj 15): empty #17
D/AndroidRuntime( 2575): 
D/AndroidRuntime( 2575): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2575): CheckJNI is OFF
W/libprocessgroup(  761): failed to open /acct/uid_10010/pid_1900/cgroup.procs: No such file or directory
D/AndroidRuntime( 2575): Calling main entry com.android.commands.am.Am
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 2575): Shutting down VM
D/SIP     ( 1190): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
I/ActivityManager(  761): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2599 uid=10277 gids={50277, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/MicrophoneInputStream( 1364): mic_close gfk@2f5c215a
I/ActivityManager(  761): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2617 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/audio_hw_primary(  183): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  183): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1364): Hotword detection finished
I/HotwordRecognitionRnr( 1364): Stopping hotword detection.
I/WebViewFactory( 2599): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2599): Time to load native libraries: 1 ms (timestamps 8264-8265)
I/LibraryLoader( 2599): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2599): Binding Chromium to main looper Looper (main, tid 1) {2f28ac1e}
I/LibraryLoader( 2599): Expected native library version number "",actual native library version number ""
I/chromium( 2599): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2599): Initializing chromium process, singleProcess=true
,W/art     ( 2599): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2599): ApplicationContext is null in ApplicationStatus
,W/chromium( 2599): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2599): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2599): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 2599): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2599): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/GAV2    ( 1364): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 1613): Google Analytics 8.3.01 is starting up.
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@317a34ae:true
,D/BluetoothAdapter( 2599): 645691793: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2599): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2599): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2599): CordovaWebView is running on device made by: LGE
,W/art     ( 2599): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 2599): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2599): Render dirty regions requested: true
,D/Atlas   ( 2599): Validating map...
,W/chromium( 2599): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/MusicStore( 2617): Database version: 120
,I/OpenGLRenderer( 2599): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2599): Enabling debug mode 0
,I/ActivityManager(  761): Displayed com.example.hello/.MainActivity: +455ms (total +15s195ms)
,I/Keyboard.Facilitator( 1072): onFinishInput()
,W/BindingManager( 2599): Cannot call determinedVisibility() - never saw a connection for the pid: 2599
,I/chromium( 2599): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,W/ContextImpl( 2107): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 2107): Thread[GAThread,5,main]: No campaign data found.
,D/JsMessageQueue( 2599): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 2599): Unable to open asset URL: file:///android_asset/www/jxcore.js
,W/ResourcesManager( 2617): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2617): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2617): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/jxcore_app_log( 2599): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 2599): jxcore cordova android initializing
,W/ActivityThread( 2617): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 2617): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@75977bc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2617): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 2617): GMSCore installation verified
,I/ConfigStore( 2617): Config Database version: 1
,W/jxcore-log( 2599): Initializing JXcore engine
W/jxcore-log( 2599): JXcore engine is ready
,W/jxcore-log( 2599): Starting JXcore engine
,W/m.example.hello( 2599): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9387]" dev="sockfs" ino=9387 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 2599): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/m.example.hello( 2599): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8026]" dev="sockfs" ino=8026 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 2599): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[16090]" dev="sockfs" ino=16090 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,I/MediaRouter( 2617): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=11, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/GHttpClientFactory( 2617): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2617): Using platform SSLCertificateSocketFactory
,W/jxcore-log( 2599): Platform android
W/jxcore-log( 2599): 
,W/jxcore-log( 2599): Process ARCH arm
W/jxcore-log( 2599): 
,I/jxcore-log( 2599): JXcore Cordova bridge is ready!
I/jxcore-log( 2599): 
W/jxcore-log( 2599): JXcore engine is started
,E/jxcore-log( 2599): >> LGE-Nexus 5
E/jxcore-log( 2599): 
,I/jxcore-log( 2599): Total memory 1946181632
I/jxcore-log( 2599): 
I/jxcore-log( 2599): Free memory 364179456
I/jxcore-log( 2599): 
I/jxcore-log( 2599): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2599): 
I/jxcore-log( 2599): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2599): 
,I/art     (  761): Explicit concurrent mark sweep GC freed 9289(478KB) AllocSpace objects, 2(36KB) LOS objects, 33% free, 27MB/40MB, paused 1.105ms total 81.019ms
I/jxcore-log( 2599): userPath [ 'www' ]
I/jxcore-log( 2599): 
,I/jxcore-log( 2599): Size 1080 1776
I/jxcore-log( 2599): 
,I/jxcore-log( 2599): Screen Brightness 82
I/jxcore-log( 2599): 
,E/jxcore-log( 2599): Dummy Error Log.
E/jxcore-log( 2599): 
,I/ActivityManager(  761): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2701 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1364): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/ChimeraCfgMgr( 1613): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1613): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 1613): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,I/ActivityManager(  761): Killing 2011:com.google.android.onetimeinitializer/u0a12 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10012/pid_2011/cgroup.procs: No such file or directory
,I/MediaStoreImporter( 2617): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  761): Killing 2036:com.android.managedprovisioning/u0a14 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10014/pid_2036/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 1613): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1613): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1613): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/PeopleContactsSync( 1613): CP2 sync disabled
,D/AsyncTaskServiceImpl( 1613): Submit a task: h
,D/ChimeraCfgMgr( 1613): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1613): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/h       ( 1613): Processing package: com.example.hello
,D/GassUtils( 1613): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
,D/h       ( 1613): Found info for package com.example.hello in db.
,I/ActivityManager(  761): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2730 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,W/BaseAppContext( 1613): Using Auth Proxy for data requests.
W/BaseAppContext( 1613): Using Auth Proxy for data requests.
,W/BaseAppContext( 1613): Using Auth Proxy for data requests.
,W/BaseAppContext( 1613): Using Auth Proxy for data requests.
,W/BaseAppContext( 1613): Using Auth Proxy for data requests.
,W/BaseAppContext( 1613): Using Auth Proxy for data requests.
,I/art     ( 1333): Explicit concurrent mark sweep GC freed 5206(258KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 19MB/32MB, paused 619us total 19.202ms
,I/jxcore-log( 2599): getBuffer is called!!!!
I/jxcore-log( 2599): 
,I/UpdateIcingCorporaServi( 1364): UpdateCorporaTask done [took 463 ms] updated apps [took 462 ms] 
,D/ChimeraCfgMgr( 1613): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1613): Module APK com.google.android.play.games already loaded
,I/GAv4    ( 2730): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2730):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2730):   adb logcat -s GAv4
,W/GAv4    ( 2730): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2730): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2730): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 2730): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,D/Finsky  ( 2489): [1] ExternalReferrer.access$100: Package state data is missing for com.example.hello
,W/ResourcesManager( 2730): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2730): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  761): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2766 uid=10067 gids={50067, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 1982:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10002/pid_1982/cgroup.procs: No such file or directory
,W/ResourcesManager( 2766): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 2730): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 2730): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 2730): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  761): Killing 2142:com.google.android.configupdater/u0a36 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10036/pid_2142/cgroup.procs: No such file or directory
,I/Icing   ( 1613): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
,D/Icing   ( 1613): Loaded CLD2 Version V2.0 - 20141016
,W/GCoreFlp( 1266): No location to return for getLastLocation()
,W/FusedLocationProvider( 1333): location=null
,D/ChimeraCfgMgr( 1613): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1613): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1613): [KidAccountFixer] No network connection
,D/GCM     ( 1333): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Icing   ( 1613): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,I/ActivityManager(  761): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=2811 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 1845): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1845): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2811): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,V/JNIHelp ( 1845): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/CalendarProvider2( 2811): Created com.android.providers.calendar.CalendarAlarmManager@33311859(com.android.providers.calendar.CalendarProvider2@2f28ac1e)
,W/System  ( 1845): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 1845): Installed default security provider GmsCore_OpenSSL
,E/SQLiteLog( 2811): (284) automatic index on view_events(_id)
,I/CalendarProvider2( 2811): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 2811): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/GAV2    ( 2428): Thread[GAThread,5,main]: No campaign data found.
,I/iu.UploadsManager( 1613): End new media; added: 0, uploading: 0, time: 97 ms
,I/ActivityManager(  761): Killing 2182:com.google.android.keep/u0a71 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10071/pid_2182/cgroup.procs: No such file or directory
,I/art     (  761): Explicit concurrent mark sweep GC freed 11097(553KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.049ms total 72.161ms
,D/WearableService( 1266): callingUid 10008, callindPid: 1266
,I/MusicLeanback( 2617): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 2617): Stop autocaching.
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService(  761): Message: 2
,D/WifiService(  761): New client listening to asynchronous messages
D/WifiService(  761): setWifiEnabled: false pid=2599, uid=10277
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 2599): ****TEST TOOK:  5029  ms ****
I/jxcore-log( 2599): 
I/jxcore-log( 2599): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2599): 
,E/GmsUtils( 2617): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 2617): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/AndroidRuntime( 2864): 
D/AndroidRuntime( 2864): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 2864): CheckJNI is OFF
,D/AndroidRuntime( 2864): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  761): Force stopping com.example.hello appid=10277 user=-1: uninstall pkg
I/ActivityManager(  761): Killing 2599:com.example.hello/u0a277 (adj 0): stop com.example.hello
,I/WindowState(  761): WIN DEATH: Window{34b3255e u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  761): Client connection lost with reason: 4
,W/PackageSettings(  761): Skipping PackageSetting{1c877646 com.test.thalitest/10270} due to missing metadata
,W/ActivityManager(  761): Force removing ActivityRecord{2e117414 u0 com.example.hello/.MainActivity t214}: app died, no saved state
,W/ActivityManager(  761): Spurious death for ProcessRecord{1b7e9c24 2599:com.example.hello/u0a277}, curProc for 2599: null
,I/ActivityManager(  761): Force stopping com.example.hello appid=10277 user=0: pkg removed
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1072): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1266): Ignoring removeGeofence because network location is disabled.
,D/VoicemailCleanupService( 1299): Cleaning up data for package: com.example.hello
,I/Keyboard.Facilitator.DecoderInitializer( 1072): run()
,I/art     ( 1364): Explicit concurrent mark sweep GC freed 24660(1715KB) AllocSpace objects, 18(3MB) LOS objects, 24% free, 18MB/24MB, paused 340us total 36.879ms
,I/Decoder ( 1072): createOrResetDecoder
,I/UpdateIcingCorporaServi( 1364): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,W/InputMethodManagerService(  761): Got RemoteException sending setActive(false) notification to pid 2599 uid 10277
,W/Launcher( 1231): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@35f69cff new=com.google.android.velvet.VelvetApplication@35f69cff
,I/Keyboard.Facilitator( 1072): onFinishInput()
,D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
,I/MicrophoneInputStream( 1364): mic_starting gfk@3ec7c112
,I/AudioFlinger(  183): AudioFlinger's thread 0xb4abb000 ready to run
,I/HotwordRecognitionRnr( 1364): Starting hotword detection.
,I/MicrophoneInputStream( 1364): mic_started gfk@3ec7c112
,D/audio_hw_primary(  183): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  183): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
D/        (  183): Failed to fetch the lookup information of the device 0000003E 
E/ACDB-LOADER(  183): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  183): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  183): enable_audio_route: apply and update mixer path: audio-record
,I/ActivityManager(  761): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2908 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/TaskPersister(  761): removeObsoleteFile: deleting file=214_task.xml
,I/ConfigService( 1333): onCreate
,I/art     (  761): Explicit concurrent mark sweep GC freed 9442(663KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 845us total 115.714ms
,I/UpdateIcingCorporaServi( 1364): UpdateCorporaTask done [took 115 ms] updated apps [took 115 ms] 
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1072): run()
,I/HotwordWorker( 1364): onReady
,W/ContextImpl( 2908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1613): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1613): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1613): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1613): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1613): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1613): Module APK com.google.android.play.games already loaded
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1072): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/LocationSettingsChecker( 1613): Removing dialog suppression flag for package com.example.hello
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Loading LM = contacts
,E/NetworkScheduler.SchedulerReceiver( 1333): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1333): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Loading LM = history
,D/AndroidRuntime( 2864): Shutting down VM
,D/gH_CompatibleDatabase( 1613): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1613): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1613): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1613): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1613): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1613): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1613): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Loaded File = UserHistory.en_US.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1072): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1072): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1072): run()
I/StatsUtilsManager( 1072): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1072): shouldRecordStats() = Too Soon
,D/gH_CompatibleDatabase( 1613): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1613): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1613): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1613): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1613): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1613): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/art     ( 1613): Explicit concurrent mark sweep GC freed 33748(2MB) AllocSpace objects, 22(352KB) LOS objects, 39% free, 21MB/35MB, paused 784us total 75.190ms
,I/ActivityManager(  761): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=2940 uid=10039 gids={50039, 9997} abi=armeabi-v7a
I/ActivityManager(  761): Killing 2210:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,W/ResourcesManager( 1231): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1231): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2210/cgroup.procs: No such file or directory
,W/BaseAppContext( 1613): Using Auth Proxy for data requests.
,W/BaseAppContext( 1613): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1613): App measurement is starting up
,I/PeopleContactsSync( 1613): CP2 sync disabled
,I/Icing   ( 1613): doRemovePackageData com.example.hello
,I/ActivityManager(  761): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=2969 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 2309:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/OpenGLRenderer( 1231): Incorrectly called buildLayer on View: adg, destroying layer...
W/OpenGLRenderer( 1231): Incorrectly called buildLayer on View: adg, destroying layer...
,I/ActivityManager(  761): Killing 2406:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10080/pid_2309/cgroup.procs: No such file or directory
,W/libprocessgroup(  761): failed to open /acct/uid_10038/pid_2406/cgroup.procs: No such file or directory
,D/ConnectivityService(  761): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ExternalStorage( 2969): After updating volumes, found 1 active roots
,W/DriveInitializer( 1613): Awaiting to be initialized
,W/DriveInitializer( 1613): Background init thread started
,W/ResourcesManager( 2730): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2730): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
,I/UpdateIcingCorporaServi( 1364): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/Launcher( 1231): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@35f69cff new=com.google.android.velvet.VelvetApplication@35f69cff
,D/PackageBroadcastService( 1613): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 1613): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1613): updateResources: need to parse f{com.google.android.gms}
,V/GmsNetworkLocationProvi( 1266): DISABLE
,I/GCoreNlp( 1266): shouldConfirmNlp, NLP off. Ensuring opt-in disabled

```
