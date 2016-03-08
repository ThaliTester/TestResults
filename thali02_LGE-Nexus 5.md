#### Test 617033519c823d7_thali02_LGE-Nexus 5 Logs


```
--------- beginning of system
I/ActivityManager(  758): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2376 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 2376): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2376): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
--------- beginning of main
V/JNIHelp ( 2376): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 2376): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2376): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 2400): 
D/AndroidRuntime( 2400): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2400): CheckJNI is OFF
D/AndroidRuntime( 2400): Calling main entry com.android.commands.am.Am
I/ActivityManager(  758): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 2400): Shutting down VM
E/YouTube MDX( 2376): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
I/dex2oat ( 2425): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-911291594.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads-911291594.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/art     (  195): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 166us total 8.869ms
I/ActivityManager(  758): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2431 uid=10278 gids={50278, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 173us total 7.536ms
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 7.873ms
I/dex2oat ( 2425): dex2oat took 47.978ms (threads: 4)
I/MicrophoneInputStream( 1347): mic_close gfk@2f20cfcf
D/audio_hw_primary(  184): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  184): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1347): Hotword detection finished
I/HotwordRecognitionRnr( 1347): Stopping hotword detection.
I/WebViewFactory( 2431): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2431): Time to load native libraries: 1 ms (timestamps 4972-4973)
I/LibraryLoader( 2431): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2431): Binding Chromium to main looper Looper (main, tid 1) {343362f1}
I/LibraryLoader( 2431): Expected native library version number "",actual native library version number ""
I/chromium( 2431): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2431): Initializing chromium process, singleProcess=true
W/art     ( 2431): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2431): ApplicationContext is null in ApplicationStatus
W/chromium( 2431): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 2431): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2431): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2431): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2431): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothAdapter( 2431): 329741488: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@283aa4cf:true
W/InstanceID/Rpc( 2376): Found 10008
W/art     ( 2431): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 2431): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 2431): CordovaWebView is running on device made by: LGE
W/art     ( 2431): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2431): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 2431): Render dirty regions requested: true
D/Atlas   ( 2431): Validating map...
W/chromium( 2431): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 2431): Initialized EGL, version 1.4
D/OpenGLRenderer( 2431): Enabling debug mode 0
W/BindingManager( 2431): Cannot call determinedVisibility() - never saw a connection for the pid: 2431
I/chromium( 2431): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 2431): Set native->JS mode to OnlineEventsBridgeMode
I/ActivityManager(  758): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=2537 uid=10054 gids={50054, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
E/AndroidProtocolHandler( 2431): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/SurfaceFlinger(  174): shader cache generated - 24 shaders in 141.099579 ms
I/ActivityManager(  758): Displayed com.example.hello/.MainActivity: +590ms (total +13s620ms)
I/ActivityManager(  758): Killing 1822:com.android.musicfx/u0a15 (adj 15): empty #17
W/ResourcesManager( 2537): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/jxcore_app_log( 2431): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,W/libprocessgroup(  758): failed to open /acct/uid_10015/pid_1822/cgroup.procs: No such file or directory
,W/jxcore-log( 2431): Initializing JXcore engine
W/jxcore-log( 2431): JXcore engine is ready
,W/Thread-241( 2555): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8041]" dev="sockfs" ino=8041 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-241( 2555): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/Thread-241( 2555): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8591]" dev="sockfs" ino=8591 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-241( 2555): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[15823]" dev="sockfs" ino=15823 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2431): Starting JXcore engine
,W/jxcore-log( 2431): Platform android
W/jxcore-log( 2431): 
W/jxcore-log( 2431): Process ARCH arm
W/jxcore-log( 2431): 
,I/jxcore-log( 2431): JXcore Cordova bridge is ready!
I/jxcore-log( 2431): 
,W/jxcore-log( 2431): JXcore engine is started
,E/jxcore-log( 2431): >> LGE-Nexus 5
E/jxcore-log( 2431): 
,I/jxcore-log( 2431): Total memory 1946181632
I/jxcore-log( 2431): 
,I/jxcore-log( 2431): Free memory 391290880
I/jxcore-log( 2431): 
,I/jxcore-log( 2431): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2431): 
I/jxcore-log( 2431): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2431): 
,I/jxcore-log( 2431): userPath [ 'www', 'www' ]
I/jxcore-log( 2431): 
,I/jxcore-log( 2431): Size 1080 1776
I/jxcore-log( 2431): 
,I/jxcore-log( 2431): Screen Brightness 82
I/jxcore-log( 2431): 
E/jxcore-log( 2431): Dummy Error Log.
E/jxcore-log( 2431): 
,I/Babel_SMS( 2537): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 2537): MmsConfig.loadMmsSettings
I/Babel_SMS( 2537): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
I/Babel_SMS( 2537): MmsConfig.loadFromDatabase
,E/Babel_SMS( 2537): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 2537): MmsConfig.loadFromResources
,E/Babel_SMS( 2537): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 2537): MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/Babel_SMS( 2537): ApnsOta: OTA version -1
,W/Settings( 2537): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 2537): startup - clean
,I/Babel   ( 2537): deleted: false for 0
,V/Babel   ( 2537): babel boot account: thalitester@gmail.com
,W/VideoCapabilities( 2537): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 2537): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 2537): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2537): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2537): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2537): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 2537): onServiceConnected
,W/Babel   ( 2537): Attempted to change video mute state without an active call.
,I/ActivityManager(  758): Start proc com.google.android.apps.fitness for broadcast com.google.android.apps.fitness/.FitnessBootReceiver: pid=2574 uid=10045 gids={50045, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/SQLiteLog( 2537): (284) automatic index on conversation_participants_view(conversation_id)
,W/VideoCapabilities( 2537): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2537): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2537): Unrecognized profile 2130706433 for video/avc
,E/SQLiteLog( 2537): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 2537): (284) automatic index on conversation_participants_view(conversation_id)
,I/ActivityManager(  758): Killing 1855:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,I/FitnessApp( 2574): Initializers took 0 milliseconds
,I/jxcore-log( 2431): getBuffer is called!!!!
I/jxcore-log( 2431): 
,I/ActivityManager(  758): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2593 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  758): Killing 1936:com.google.android.apps.plus/u0a67 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10040/pid_1855/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10067/pid_1936/cgroup.procs: No such file or directory
,I/GAv4    ( 2593): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2593):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2593):   adb logcat -s GAv4
,W/GAv4    ( 2593): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2593): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2593): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  758): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2618 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  758): Killing 2014:com.android.keychain/1000 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_1000/pid_2014/cgroup.procs: No such file or directory
,I/Gmail   ( 2618): getAccountsCursor
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityThread( 2618): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,I/ActivityManager(  758): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=2641 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GAV2    ( 2618): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Gmail   ( 2618): getAccountsCursor
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Volley  ( 1895): [157] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 1895): [164] DiskBasedCache.clear: Cache cleared.
,I/Exchange( 2641): EasService.onCreate
,I/art     (  758): Explicit concurrent mark sweep GC freed 9723(464KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/40MB, paused 893us total 56.434ms
,I/SystemBroadcastReceiver( 1082): Boot has been completed
,I/SystemBroadcastReceiver( 1082): toggleAppIcon() : FLAG_SYSTEM = true
,W/ActivityManager(  758): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 2641): RestartPingTask
,I/Gmail   ( 2618): Observing account changes for notifications
,I/Exchange( 2641): RestartPingsTask did not start any pings.
I/Exchange( 2641): PSS stopIfIdle
,I/Exchange( 2641): PSS has no active accounts; stopping service.
,V/UserPresentBroadcastReceiver( 1301): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,I/ActivityManager(  758): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=2693 uid=10003 gids={50003, 9997} abi=armeabi-v7a
,E/SQLiteLog( 2618): (283) recovered 58 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  758): Killing 1999:com.google.android.dialer/u0a10 (adj 15): empty #17
,I/Gmail   ( 2618): notifyAccountChanged
,I/Gmail   ( 2618): getAccountsCursor
,I/Gmail   ( 2618): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 2618): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/libprocessgroup(  758): failed to open /acct/uid_10010/pid_1999/cgroup.procs: No such file or directory
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 2618): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 2618): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/CellBroadcastReceiver( 2693): onReceive Intent { act=android.intent.action.SERVICE_STATE flg=0x10 cmp=com.android.cellbroadcastreceiver/.CellBroadcastReceiver (has extras) }
D/CellBroadcastReceiver( 2693): Intent ACTION_SERVICE_STATE_CHANGED
D/CellBroadcastReceiver( 2693): Service state changed! 3 Full: 3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=false Current state=-1
,I/ActivityManager(  758): Killing 1335:android.process.acore/u0a4 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10004/pid_1335/cgroup.procs: No such file or directory
,I/ActivityManager(  758): Killing 2116:com.google.android.onetimeinitializer/u0a12 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10012/pid_2116/cgroup.procs: No such file or directory
,I/Gmail   ( 2618): getAccountsCursor
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SIP     ( 1220): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,I/GAV2    ( 1347): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 1551): Google Analytics 8.4.89 is starting up.
,E/MDM     ( 1301): [177] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1551): Restart initialization of location
,D/AuthorizationBluetoothService( 1301): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  758): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2731 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1301): No location to return for getLastLocation()
,W/FusedLocationProvider( 1301): location=null
,D/CAR.SERVICE( 2136): mConnectedToCar = false, abort
,E/ActivityThread( 2136): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@e2dc8be that was originally bound here
E/ActivityThread( 2136): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@e2dc8be that was originally bound here
E/ActivityThread( 2136): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2136): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2136): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2136): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2136): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2136): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2136): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2136): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 2136): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 2136): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 2136): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 2136): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 2136): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 2136): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 2136): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 2136): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 2136): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2136): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2136): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 2136): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2136): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2136): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 2136): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 2136): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@36fde8b1 that was originally bound here
E/ActivityThread( 2136): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@36fde8b1 that was originally bound here
E/ActivityThread( 2136): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2136): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2136): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2136): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2136): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2136): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 2136): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 2136): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 2136): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 2136): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 2136): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 2136): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 2136): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 2136): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 2136): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 2136): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2136): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2136): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 2136): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2136): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2136): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 2136): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  758): Unbind failed: could not find connection for android.os.BinderProxy@3f5aa3f3
,W/ContextImpl( 2193): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 2193): Thread[GAThread,5,main]: No campaign data found.
,I/MusicStore( 2731): Database version: 120
,W/ResourcesManager( 2731): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2731): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2731): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 2731): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 2731): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@284a5e07: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2731): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 2731): GMSCore installation verified
,I/ConfigStore( 2731): Config Database version: 1
,I/MediaRouter( 2731): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/GHttpClientFactory( 2731): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2731): Using platform SSLCertificateSocketFactory
,D/Finsky  ( 1895): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 1895): [182] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1301): No location to return for getLastLocation()
,W/FusedLocationProvider( 1301): location=null
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 2727(106KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/26MB, paused 844us total 19.987ms
,D/GCM     ( 1301): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/MediaStoreImporter( 2731): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  758): Killing 2160:com.android.managedprovisioning/u0a14 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10014/pid_2160/cgroup.procs: No such file or directory
,E/SQLiteLog( 2072): (284) automatic index on view_events(_id)
,W/ResourcesManager( 2537): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2537): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2537): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 2537): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2537): Installed default security provider GmsCore_OpenSSL
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  758): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  758): Message: 2
,D/WifiService(  758): New client listening to asynchronous messages
,D/WifiService(  758): setWifiEnabled: false pid=2431, uid=10278
E/WifiService(  758): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 2431): ****TEST TOOK:  5036  ms ****
I/jxcore-log( 2431): 
I/jxcore-log( 2431): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2431): 
,D/AndroidRuntime( 2812): 
D/AndroidRuntime( 2812): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 2812): CheckJNI is OFF
,D/AndroidRuntime( 2812): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  758): Force stopping com.example.hello appid=10278 user=-1: uninstall pkg
I/ActivityManager(  758): Killing 2431:com.example.hello/u0a278 (adj 0): stop com.example.hello
,I/WindowState(  758): WIN DEATH: Window{3265bb24 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  758): Client connection lost with reason: 4
,W/PackageSettings(  758): Skipping PackageSetting{31e4080a com.test.thalitest/10270} due to missing metadata
,W/ActivityManager(  758): Force removing ActivityRecord{2811f093 u0 com.example.hello/.MainActivity t220}: app died, no saved state
,W/ActivityManager(  758): Spurious death for ProcessRecord{339ee421 2431:com.example.hello/u0a278}, curProc for 2431: null
,I/ActivityManager(  758): Force stopping com.example.hello appid=10278 user=0: pkg removed
,I/InputReader(  758): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1082): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1082): run()
,I/Decoder ( 1082): createOrResetDecoder
,W/GeofencerStateMachine( 1301): Ignoring removeGeofence because network location is disabled.
,I/art     ( 1551): Explicit concurrent mark sweep GC freed 18590(1241KB) AllocSpace objects, 16(256KB) LOS objects, 39% free, 21MB/36MB, paused 805us total 48.469ms
,I/ActivityManager(  758): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=2833 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,I/ConfigService( 1301): onCreate
,D/BackupManagerService(  758): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  758): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  758): removeObsoleteFile: deleting file=220_task.xml
,I/art     (  758): Explicit concurrent mark sweep GC freed 20826(1246KB) AllocSpace objects, 5(84KB) LOS objects, 33% free, 27MB/41MB, paused 1.306ms total 102.803ms
I/art     (  758): WaitForGcToComplete blocked for 33.880ms for cause Explicit
,D/AndroidRuntime( 2812): Shutting down VM
,I/art     (  758): Explicit concurrent mark sweep GC freed 2453(160KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/40MB, paused 1.062ms total 57.344ms
,I/MicrophoneInputStream( 1347): mic_starting gfk@24d15716
,I/HotwordRecognitionRnr( 1347): Starting hotword detection.
,I/AudioFlinger(  184): AudioFlinger's thread 0xb2e3f000 ready to run
,I/MicrophoneInputStream( 1347): mic_started gfk@24d15716
,D/audio_hw_primary(  184): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
,D/msm8974_platform(  184): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
D/        (  184): Failed to fetch the lookup information of the device 0000003E 
E/ACDB-LOADER(  184): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  184): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  184): enable_audio_route: apply and update mixer path: audio-record
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1082): run()
,I/art     ( 1301): Explicit concurrent mark sweep GC freed 28087(1720KB) AllocSpace objects, 13(208KB) LOS objects, 40% free, 21MB/35MB, paused 2.319ms total 44.165ms
,E/DataBuffer( 1301): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@49090f1)
,E/DataBuffer( 1301): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@91d54d6)
E/DataBuffer( 1301): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4da8357)
E/DataBuffer( 1301): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@11589e44)
E/DataBuffer( 1301): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@f8c4b2d)
D/VoicemailCleanupService( 2833): Cleaning up data for package: com.example.hello
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1082): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/ActivityManager(  758): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2875 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1082): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1082): run() : Loading LM = contacts
,I/HotwordWorker( 1347): onReady
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1082): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1082): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1082): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1082): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1082): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1082): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1082): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1082): run()
I/StatsUtilsManager( 1082): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1082): shouldRecordStats() = Too Soon
,I/ContactLocale( 2833): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/UpdateIcingCorporaServi( 1347): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,W/ResourcesManager( 1259): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/Launcher( 1259): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@196cbed6 new=com.google.android.velvet.VelvetApplication@196cbed6
,W/ResourcesManager( 1259): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  758): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2903 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  758): Killing 2224:com.google.android.configupdater/u0a36 (adj 15): empty #17
,E/SQLiteLog( 2833): (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
,--------- beginning of crash
E/AndroidRuntime( 2833): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 2833): Process: android.process.acore, PID: 2833
E/AndroidRuntime( 2833): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2833): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2833): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 2833): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2833): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2833): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 2833): 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
E/AndroidRuntime( 2833): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
E/AndroidRuntime( 2833): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 2833): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2833): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2833): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/libprocessgroup(  758): failed to open /acct/uid_10036/pid_2224/cgroup.procs: No such file or directory
,E/SQLiteLog( 1347): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/IcingCorporaProvider( 1347): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 1347): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 1347): 	at beg.a(PG:301)
E/IcingCorporaProvider( 1347): 	at beg.c(PG:222)
E/IcingCorporaProvider( 1347): 	at cun.b(PG:660)
E/IcingCorporaProvider( 1347): 	at cun.a(PG:651)
E/IcingCorporaProvider( 1347): 	at cun.g(PG:597)
E/IcingCorporaProvider( 1347): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 1347): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/IcingCorporaProvider( 1347): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/IcingCorporaProvider( 1347): 	at cuw.Tg(PG:368)
E/IcingCorporaProvider( 1347): 	at cuy.ub(PG:301)
E/IcingCorporaProvider( 1347): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/IcingCorporaProvider( 1347): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/IcingCorporaProvider( 1347): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 1347): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 1347): 	at android.os.Looper.loop(Looper.java:135)
E/IcingCorporaProvider( 1347): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 1347): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 1347): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 1347): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/IcingCorporaProvider( 1347): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 1347): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 1347): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/IcingCorporaProvider( 1347): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/IcingCorporaProvider( 1347): 	at bea.a(PG:382)
E/IcingCorporaProvider( 1347): 	at beg.i(PG:325)
E/IcingCorporaProvider( 1347): 	at beh.call(PG:215)
E/IcingCorporaProvider( 1347): 	at beg.a(PG:299)
E/IcingCorporaProvider( 1347): 	... 15 more
W/IcingCorporaProvider( 1347): notifyTableChanged failed.
W/IcingCorporaProvider( 1347): Table change notification failed for TableStorageSpec[applications]
I/UpdateIcingCorporaServi( 1347): UpdateCorporaTask done [took 134 ms] updated apps [took 134 ms] 
,E/DropBoxManagerService(  758): Can't write: system_app_crash
E/DropBoxManagerService(  758): java.io.FileNotFoundException: /data/system/dropbox/drop84.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  758): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  758): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  758): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  758): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  758): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  758): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  758): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  758): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  758): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  758): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  758): 	... 5 more
D/OpenGLRenderer(  758): Render dirty regions requested: true
W/ContextImpl( 2903): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
D/Atlas   (  758): Validating map...
D/PackageBroadcastService( 1551): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1551): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1551): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1551): Module APK com.google.android.play.games already loaded
,E/SQLiteDatabase( 2903): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 2903): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2903): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2903): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 2903): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 2903): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2903): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2903): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2903): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 2903): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 2903): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 2903): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 2903): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2903): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2903): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2903): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/SQLiteDatabase( 2903): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/SQLiteDatabase( 2903): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2903): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2903): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 2903): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 2903): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 2903): Process: com.android.keychain, PID: 2903
E/AndroidRuntime( 2903): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2903): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 2903): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 2903): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 2903): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 2903): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 2903): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 2903): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 2903): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 2903): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 2903): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/AndroidRuntime( 2903): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 2903): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 2903): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 2903): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/AndroidRuntime( 2903): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396,)
E/AndroidRuntime( 2903): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2903): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2903): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2903): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ChimeraCfgMgr( 1551): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1551): Module APK com.google.android.play.games already loaded
E/DropBoxManagerService(  758): Can't write: system_app_crash
E/DropBoxManagerService(  758): java.io.FileNotFoundException: /data/system/dropbox/drop86.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  758): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  758): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  758): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  758): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  758): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  758): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  758): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  758): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  758): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  758): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  758): 	... 5 more
E/SQLiteLog( 1551): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/LocationSettingsChecker( 1551): Removing dialog suppression flag for package com.example.hello
E/SQLiteLog( 1301): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1301): Shutting down VM
E/AndroidRuntime( 1551): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1551): Process: com.google.android.gms, PID: 1551
E/AndroidRuntime( 1551): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1551): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1551): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1551): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1551): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1551): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1551): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/AndroidRuntime( 1551): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1551): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1551): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1551): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/AndroidRuntime( 1551): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 1551): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3332)
E/AndroidRuntime( 1551): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:32)
E/AndroidRuntime( 1551): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 1551): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:177)
E/AndroidRuntime( 1551): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1551): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1551): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 1301): FATAL EXCEPTION: main
E/AndroidRuntime( 1301): Process: com.google.android.gms.persistent, PID: 1301
E/AndroidRuntime( 1301): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1301): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
E/AndroidRuntime( 1301): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1301): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/AndroidRuntime( 1301): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1301): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1301): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/AndroidRuntime( 1301): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1301): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1301): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/AndroidRuntime( 1301): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/AndroidRuntime( 1301): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1301): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1301): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1301): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1301): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1301): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1301): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1301): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1301): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1301): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/AndroidRuntime( 1301): 	... 9 more
W/ActivityManager(  758): Process com.google.android.gms has crashed too many times: killing!
I/ActivityManager(  758): Killing 1551:com.google.android.gms/u0a8 (adj 1): crash
E/DropBoxManagerService(  758): Can't write: system_app_crash
E/DropBoxManagerService(  758): java.io.FileNotFoundException: /data/system/dropbox/drop88.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  758): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  758): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  758): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  758): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  758): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  758): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  758): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  758): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  758): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  758): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  758): 	... 5 more
E/qdhwcomposer(  174): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  174): hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
E/qdoverlay(  174): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  174): MdpData failed to play
E/qdoverlay(  174): == Dump MdpData start ==
E/qdoverlay(  174): == Dump OvFD fd=30 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  174): mOvData msmfb_overlay_data id=64
E/qdoverlay(  174): data msmfb_data offset=0 memid=39 id=0 flags=0x0 priv=0
E/qdoverlay(  174): == Dump MdpData end ==
E/qdhwcomposer(  174): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  174): hwc_set_primary: MDPComp draw failed
E/qdhwcomposer(  174): display_commit: MSMFB_DISPLAY_COMMIT for primary failed
E/qdhwcomposer(  174): hwc_set_primary: display commit fail!
E/DropBoxManagerService(  758): Can't write: system_app_crash
E/DropBoxManagerService(  758): java.io.FileNotFoundException: /data/system/dropbox/drop87.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  758): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  758): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  758): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  758): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  758): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  758): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  758): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  758): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  758): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  758): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  758): 	... 5 more
I/Adreno-EGL(  758): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  758): Initialized EGL, version 1.4
,W/OpenGLRenderer( 1259): Incorrectly called buildLayer on View: adg, destroying layer...
W/OpenGLRenderer( 1259): Incorrectly called buildLayer on View: adg, destroying layer...
D/OpenGLRenderer(  758): Enabling debug mode 0
E/qdoverlay(  174): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  174): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  174): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  174): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  174): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  174): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  174): == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  174): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  174): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  174): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  174): Ctrl commit failed set overlay
E/qdhwcomposer(  174): configureLowRes: commit failed for low res panel
E/qdoverlay(  174): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  174): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  174): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  174): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  174): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  174): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  174): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  174): src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
E/qdoverlay(  174): src_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  174): dst_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  174): Ctrl commit failed set overlay
E/qdhwcomposer(  174): configure: commit fails
E/qdoverlay(  174): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  174): MdpCtrl close error in unset
W/ActivityManager(  758): Spurious death for ProcessRecord{97ea5e4 1551:com.google.android.gms/u0a8}, curProc for 1551: null
,I/ActivityManager(  758): Start proc com.google.android.gms for service com.google.android.gms/.analytics.service.AnalyticsService: pid=2943 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     (  195): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 394us total 15.966ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 170us total 7.937ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 170us total 7.501ms
,E/qdoverlay(  174): GenericPipe failed to close ctrl
,E/qdoverlay(  174): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  174): MdpCtrl close error in unset
E/qdoverlay(  174): GenericPipe failed to close ctrl
E/qdoverlay(  174): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  174): MdpCtrl close error in unset
E/qdoverlay(  174): GenericPipe failed to close ctrl

```
