#### Test 623445121bdd37c_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/dex2oat ( 2457): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-403021450.jar --oat-fd=21 --oat-location=/data/data/com.google.android.youtube/cache/ads-403021450.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 2457): dex2oat took 30.673ms (threads: 4)
,W/InstanceID/Rpc( 2427): Found 10008
D/AndroidRuntime( 2490): 
D/AndroidRuntime( 2490): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2490): CheckJNI is OFF
--------- beginning of system
I/ActivityManager(  734): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=2521 uid=10054 gids={50054, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/art     (  195): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 201us total 7.787ms
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 166us total 7.353ms
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.689ms
I/ActivityManager(  734): Killing 1822:com.android.musicfx/u0a15 (adj 15): empty #17
W/ResourcesManager( 2521): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/AndroidRuntime( 2490): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  734): failed to open /acct/uid_10015/pid_1822/cgroup.procs: No such file or directory
I/ActivityManager(  734): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 2490): Shutting down VM
I/ActivityManager(  734): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2551 uid=10278 gids={50278, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/MicrophoneInputStream( 1340): mic_close gfk@206d537
D/audio_hw_primary(  184): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  184): disable_snd_device: snd_device(55: voice-rec-mic)
I/WebViewFactory( 2551): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/HotwordRecognitionRnr( 1340): Hotword detection finished
I/HotwordRecognitionRnr( 1340): Stopping hotword detection.
I/LibraryLoader( 2551): Time to load native libraries: 1 ms (timestamps 4814-4815)
I/LibraryLoader( 2551): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2551): Binding Chromium to main looper Looper (main, tid 1) {23bb44cb}
I/LibraryLoader( 2551): Expected native library version number "",actual native library version number ""
I/chromium( 2551): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2551): Initializing chromium process, singleProcess=true
W/art     ( 2551): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2551): ApplicationContext is null in ApplicationStatus
W/chromium( 2551): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 2551): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2551): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2551): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2551): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3728b188:true
D/BluetoothAdapter( 2551): 867656359: getState() :  mService = null. Returning STATE_OFF
W/art     ( 2551): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 2551): onDetachedFromWindow called when already detached. Ignoring
I/Babel_SMS( 2521): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 2521): MmsConfig.loadMmsSettings
I/Babel_SMS( 2521): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
I/Babel_SMS( 2521): MmsConfig.loadFromDatabase
D/SystemWebViewEngine( 2551): CordovaWebView is running on device made by: LGE
W/art     ( 2551): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2551): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 2551): Render dirty regions requested: true
D/Atlas   ( 2551): Validating map...
W/chromium( 2551): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
E/Babel_SMS( 2521): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 2521): MmsConfig.loadFromResources
E/Babel_SMS( 2521): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 2521): MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
I/Babel_SMS( 2521): ApnsOta: OTA version -1
I/OpenGLRenderer( 2551): Initialized EGL, version 1.4
D/OpenGLRenderer( 2551): Enabling debug mode 0
I/Babel   ( 2521): deleted: false for 0
W/Settings( 2521): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 2521): startup - clean
W/BindingManager( 2551): Cannot call determinedVisibility() - never saw a connection for the pid: 2551
I/chromium( 2551): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
V/Babel   ( 2521): babel boot account: thalitester@gmail.com
D/JsMessageQueue( 2551): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 2551): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/SurfaceFlinger(  170): shader cache generated - 24 shaders in 146.130112 ms
W/VideoCapabilities( 2521): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  734): Displayed com.example.hello/.MainActivity: +571ms (total +14s334ms)
I/VideoCapabilities( 2521): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 2521): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2521): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2521): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2521): Unrecognized profile 2130706433 for video/avc
D/jxcore_app_log( 2551): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 2551): jxcore cordova android initializing
I/vclib   ( 2521): onServiceConnected
W/Babel   ( 2521): Attempted to change video mute state without an active call.
,I/ActivityManager(  734): Start proc com.google.android.apps.fitness for broadcast com.google.android.apps.fitness/.FitnessBootReceiver: pid=2612 uid=10045 gids={50045, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/SQLiteLog( 2521): (284) automatic index on conversation_participants_view(conversation_id)
,W/jxcore-log( 2551): Initializing JXcore engine
W/jxcore-log( 2551): JXcore engine is ready
,W/jxcore-log( 2551): Starting JXcore engine
,W/VideoCapabilities( 2521): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2521): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2521): Unrecognized profile 2130706433 for video/avc
,E/SQLiteLog( 2521): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 2521): (284) automatic index on conversation_participants_view(conversation_id)
,W/m.example.hello( 2551): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8091]" dev="sockfs" ino=8091 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/m.example.hello( 2551): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/m.example.hello( 2551): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9502]" dev="sockfs" ino=9502 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/m.example.hello( 2551): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[16635]" dev="sockfs" ino=16635 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,I/ActivityManager(  734): Killing 1883:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,I/FitnessApp( 2612): Initializers took 0 milliseconds
,W/jxcore-log( 2551): Platform android
W/jxcore-log( 2551): 
W/jxcore-log( 2551): Process ARCH arm
W/jxcore-log( 2551): 
,W/libprocessgroup(  734): failed to open /acct/uid_10040/pid_1883/cgroup.procs: No such file or directory
,I/ActivityManager(  734): Killing 1981:com.google.android.apps.plus/u0a67 (adj 15): empty #17
,I/jxcore-log( 2551): JXcore Cordova bridge is ready!
I/jxcore-log( 2551): 
,W/jxcore-log( 2551): JXcore engine is started
,E/jxcore-log( 2551): >> LGE-Nexus 5
E/jxcore-log( 2551): 
,I/jxcore-log( 2551): Total memory 1946181632
I/jxcore-log( 2551): 
I/jxcore-log( 2551): Free memory 400924672
I/jxcore-log( 2551): 
I/jxcore-log( 2551): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2551): 
I/jxcore-log( 2551): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2551): 
,I/jxcore-log( 2551): userPath [ 'www', 'www' ]
I/jxcore-log( 2551): 
,I/jxcore-log( 2551): Size 1080 1776
I/jxcore-log( 2551): 
,I/jxcore-log( 2551): Screen Brightness 82
I/jxcore-log( 2551): 
,E/jxcore-log( 2551): Dummy Error Log.
E/jxcore-log( 2551): 
,I/ActivityManager(  734): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2631 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,W/libprocessgroup(  734): failed to open /acct/uid_10067/pid_1981/cgroup.procs: No such file or directory
,I/GAv4    ( 2631): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2631):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2631):   adb logcat -s GAv4
,W/GAv4    ( 2631): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2631): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2631): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  734): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2659 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  734): Killing 2035:com.android.keychain/1000 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_1000/pid_2035/cgroup.procs: No such file or directory
,I/jxcore-log( 2551): getBuffer is called!!!!
I/jxcore-log( 2551): 
,D/ActivityThread( 2659): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,I/Gmail   ( 2659): getAccountsCursor
,V/GLSActivity( 1291): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  734): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=2682 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GAV2    ( 2659): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  734): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 2682): EasService.onCreate
,I/Gmail   ( 2659): Observing account changes for notifications
,I/Exchange( 2682): RestartPingTask
,I/Exchange( 2682): RestartPingsTask did not start any pings.
I/Exchange( 2682): PSS stopIfIdle
I/Exchange( 2682): PSS has no active accounts; stopping service.
,I/Gmail   ( 2659): getAccountsCursor
V/GLSActivity( 1291): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  734): Explicit concurrent mark sweep GC freed 8663(410KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 708us total 53.786ms
,D/Volley  ( 1935): [164] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 1935): [157] DiskBasedCache.clear: Cache cleared.
,I/Exchange( 2682): onDestroy
,I/SystemBroadcastReceiver( 1068): Boot has been completed
I/SystemBroadcastReceiver( 1068): toggleAppIcon() : FLAG_SYSTEM = true
,V/GLSActivity( 1291): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/UserPresentBroadcastReceiver( 1291): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,I/Exchange( 2682): EasService.onCreate
,I/Exchange( 2682): RestartPingTask
,E/SQLiteLog( 2659): (283) recovered 74 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/ActivityManager(  734): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=2738 uid=10003 gids={50003, 9997} abi=armeabi-v7a
,I/Exchange( 2682): RestartPingsTask did not start any pings.
,I/Exchange( 2682): PSS stopIfIdle
I/Exchange( 2682): PSS has no active accounts; stopping service.
,I/Exchange( 2682): onDestroy
,I/ActivityManager(  734): Killing 2056:com.google.android.dialer/u0a10 (adj 15): empty #17
,I/Gmail   ( 2659): notifyAccountChanged
,I/Gmail   ( 2659): getAccountsCursor
,I/Gmail   ( 2659): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 2659): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 2659): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 2659): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/libprocessgroup(  734): failed to open /acct/uid_10010/pid_2056/cgroup.procs: No such file or directory
,V/GLSActivity( 1291): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  734): Killing 1385:android.process.acore/u0a4 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10004/pid_1385/cgroup.procs: No such file or directory
,D/CellBroadcastReceiver( 2738): onReceive Intent { act=android.intent.action.SERVICE_STATE flg=0x10 cmp=com.android.cellbroadcastreceiver/.CellBroadcastReceiver (has extras) }
D/CellBroadcastReceiver( 2738): Intent ACTION_SERVICE_STATE_CHANGED
D/CellBroadcastReceiver( 2738): Service state changed! 3 Full: 3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=false Current state=-1
,I/ActivityManager(  734): Killing 2157:com.google.android.onetimeinitializer/u0a12 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10012/pid_2157/cgroup.procs: No such file or directory
,D/SIP     ( 1220): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,I/GAV2    ( 1340): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 1569): Google Analytics 8.4.89 is starting up.
,I/Gmail   ( 2659): getAccountsCursor
,V/GLSActivity( 1291): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1291): [179] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1291): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 1569): Restart initialization of location
,V/GLSActivity( 1291): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  734): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2771 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1291): No location to return for getLastLocation()
,W/FusedLocationProvider( 1291): location=null
,D/CAR.SERVICE( 2177): mConnectedToCar = false, abort
,E/ActivityThread( 2177): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@e236050 that was originally bound here
E/ActivityThread( 2177): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@e236050 that was originally bound here
E/ActivityThread( 2177): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2177): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2177): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2177): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2177): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2177): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2177): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2177): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 2177): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 2177): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 2177): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 2177): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 2177): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 2177): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 2177): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 2177): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 2177): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2177): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2177): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 2177): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2177): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2177): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 2177): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/ActivityThread( 2177): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1e28348b that was originally bound here
E/ActivityThread( 2177): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1e28348b that was originally bound here
E/ActivityThread( 2177): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2177): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2177): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2177): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2177): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2177): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 2177): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 2177): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 2177): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 2177): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 2177): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 2177): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 2177): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 2177): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 2177): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 2177): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2177): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2177): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 2177): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2177): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2177): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 2177): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  734): Unbind failed: could not find connection for android.os.BinderProxy@14db68a8
,I/ActivityManager(  734): Killing 2201:com.android.managedprovisioning/u0a14 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10014/pid_2201/cgroup.procs: No such file or directory
,I/MusicStore( 2771): Database version: 120
,W/ResourcesManager( 2771): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2771): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2771): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ContextImpl( 2235): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 2235): Thread[GAThread,5,main]: No campaign data found.
,W/ActivityThread( 2771): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 2771): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c868cf1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2771): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 2771): GMSCore installation verified
,I/ConfigStore( 2771): Config Database version: 1
,I/MediaRouter( 2771): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/GHttpClientFactory( 2771): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2771): Using platform SSLCertificateSocketFactory
,D/Finsky  ( 1935): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 1935): [182] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1291): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1291): No location to return for getLastLocation()
,W/FusedLocationProvider( 1291): location=null
,D/GCM     ( 1291): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 2933(115KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 546us total 11.898ms
,W/SQLiteConnectionPool( 1465): A SQLiteConnection object for database '/data/user/0/com.google.android.gsf/databases/gservices.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/MediaStoreImporter( 2771): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  734): Killing 2113:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10002/pid_2113/cgroup.procs: No such file or directory
,I/ActivityManager(  734): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=2846 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 2521): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2521): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2846): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,V/JNIHelp ( 2521): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/CalendarProvider2( 2846): Created com.android.providers.calendar.CalendarAlarmManager@2e33239a(com.android.providers.calendar.CalendarProvider2@23bb44cb)
,E/SQLiteLog( 2846): (284) automatic index on view_events(_id)
,W/System  ( 2521): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 2521): Installed default security provider GmsCore_OpenSSL
,E/PhoneInterfaceManager( 1220): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  734): Explicit concurrent mark sweep GC freed 12546(622KB) AllocSpace objects, 3(52KB) LOS objects, 33% free, 27MB/41MB, paused 712us total 46.730ms
,I/Babel   ( 2521): connection state changed from UNKNOWN to DISCONNECTED
,I/CalendarProvider2( 2846): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 2846): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  734): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  734): Message: 2
,D/WifiService(  734): New client listening to asynchronous messages
,D/WifiService(  734): setWifiEnabled: false pid=2551, uid=10278
E/WifiService(  734): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 2551): ****TEST TOOK:  5025  ms ****
I/jxcore-log( 2551): 
I/jxcore-log( 2551): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2551): 
,D/AndroidRuntime( 2900): 
D/AndroidRuntime( 2900): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2900): CheckJNI is OFF
,D/AndroidRuntime( 2900): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  734): Force stopping com.example.hello appid=10278 user=-1: uninstall pkg
I/ActivityManager(  734): Killing 2551:com.example.hello/u0a278 (adj 0): stop com.example.hello
,I/WindowState(  734): WIN DEATH: Window{2bd1c5f7 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  734): Client connection lost with reason: 4
,W/PackageSettings(  734): Skipping PackageSetting{166c24bc com.test.thalitest/10270} due to missing metadata
,W/ActivityManager(  734): Force removing ActivityRecord{3a8f4535 u0 com.example.hello/.MainActivity t220}: app died, no saved state
,W/ActivityManager(  734): Spurious death for ProcessRecord{3f091e44 2551:com.example.hello/u0a278}, curProc for 2551: null
,I/ActivityManager(  734): Force stopping com.example.hello appid=10278 user=0: pkg removed
,W/GeofencerStateMachine( 1291): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  734): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1068): resetDictionaries() : en_US
,I/art     ( 1569): Explicit concurrent mark sweep GC freed 20460(1399KB) AllocSpace objects, 22(352KB) LOS objects, 39% free, 21MB/36MB, paused 893us total 38.361ms
,I/ActivityManager(  734): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=2921 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,I/Keyboard.Facilitator.DecoderInitializer( 1068): run()
,I/Decoder ( 1068): createOrResetDecoder
,I/ConfigService( 1291): onCreate
,D/BackupManagerService(  734): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  734): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  734): removeObsoleteFile: deleting file=220_task.xml
,I/MicrophoneInputStream( 1340): mic_starting gfk@28003983
,I/HotwordRecognitionRnr( 1340): Starting hotword detection.
,I/AudioFlinger(  184): AudioFlinger's thread 0xb49be000 ready to run
,I/MicrophoneInputStream( 1340): mic_started gfk@28003983
,I/art     ( 1291): Explicit concurrent mark sweep GC freed 27556(1707KB) AllocSpace objects, 15(240KB) LOS objects, 40% free, 21MB/35MB, paused 1.212ms total 56.039ms
,D/audio_hw_primary(  184): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
,D/msm8974_platform(  184): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
D/        (  184): Failed to fetch the lookup information of the device 0000003E 
E/ACDB-LOADER(  184): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  184): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  184): enable_audio_route: apply and update mixer path: audio-record
,I/art     (  734): Explicit concurrent mark sweep GC freed 12015(811KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 2.068ms total 133.829ms
,D/AndroidRuntime( 2900): Shutting down VM
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1068): run()
,D/VoicemailCleanupService( 2921): Cleaning up data for package: com.example.hello
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1068): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,I/ActivityManager(  734): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2963 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1068): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1068): run() : Loading LM = contacts
,I/HotwordWorker( 1340): onReady
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1068): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1068): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1068): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1068): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1068): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1068): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1068): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1068): run()
I/StatsUtilsManager( 1068): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1068): shouldRecordStats() = Too Soon
,W/ResourcesManager( 1263): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ContactLocale( 2921): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  734): Killing 2281:com.google.android.configupdater/u0a36 (adj 15): empty #17
,I/GAV2    ( 2659): Thread[GAThread,5,main]: No campaign data found.
,W/ResourcesManager( 1263): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  734): failed to open /acct/uid_10036/pid_2281/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1340): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,W/Launcher( 1263): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@5b454a8 new=com.google.android.velvet.VelvetApplication@5b454a8
,I/ActivityManager(  734): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2992 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  734): Killing 2316:com.google.android.keep/u0a71 (adj 15): empty #17
I/art     (  195): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 179us total 12.637ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 177us total 8.463ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 170us total 8.500ms
,W/libprocessgroup(  734): failed to open /acct/uid_10071/pid_2316/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1340): UpdateCorporaTask done [took 103 ms] updated apps [took 103 ms] 
,W/ContextImpl( 2992): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1569): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1569): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1569): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1569): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1569): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1569): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1569): Removing dialog suppression flag for package com.example.hello
,E/NetworkScheduler.SchedulerReceiver( 1291): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1291): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/FileUtils( 2992): Failed to chmod(/data/data/com.android.keychain/databases/grants.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/SQLiteLog( 2992): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,--------- beginning of crash
E/AndroidRuntime( 2992): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 2992): Process: com.android.keychain, PID: 2992
E/AndroidRuntime( 2992): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2992): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2992): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 2992): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2992): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2992): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 2992): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 2992): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:404)
E/AndroidRuntime( 2992): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/AndroidRuntime( 2992): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2992): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2992): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2992): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteDatabase( 1569): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1569): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1569): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1569): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1569): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1569): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1569): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1569): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1569): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1569): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1569): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1569): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1569): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1569): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1569): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1569): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1569): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1569): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1569): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1569): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1569): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1569): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1569): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1569): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1569): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1569): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1569): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1569): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1569): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1569): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1569): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1569): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1569): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1569): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1569): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteOpenHelper( 1569): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1569): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1569): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1569): 	at com.google.android.g,ms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1569): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1569): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1569): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1569): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1569): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1569): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1569): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1569): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1569): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1569): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1569): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.example.hello"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1569): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/AndroidRuntime( 1569): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1569): Process: com.google.android.gms, PID: 1569
E/AndroidRuntime( 1569): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 1569): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1569): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1569): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1569): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1569): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1569): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1569): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1569): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1569): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1569): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1569): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  734): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3019 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
E/SQLiteDatabase( 1569): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1569): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1569): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1569): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1569): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1569): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1569): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1569): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1569): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1569): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1569): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1569): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1569): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1569): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1569): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1569): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1569): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1569): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1569): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1569): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1569): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 1569): Could not unregister android package com.example.hello
E/PhenotypeInitializer( 1569): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1569): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1569): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PhenotypeInitializer( 1569): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PhenotypeInitializer( 1569): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1569): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1569): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1569): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/PhenotypeInitializer( 1569): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/PhenotypeInitializer( 1569): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PhenotypeInitializer( 1569): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/PhenotypeInitializer( 1569): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/PhenotypeInitializer( 1569): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/PhenotypeInitializer( 1569): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 1569): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 1569): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1569): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1569): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1569): 	at android.os.Looper.loop(Looper.java:135)
E/PhenotypeInitializer( 1569): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  734): Can't write: system_app_crash
E/DropBoxManagerService(  734): java.io.FileNotFoundException: /data/system/dropbox/drop83.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  734): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  734): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  734): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  734): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  734): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  734): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  734): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  734): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  734): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  734): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  734): 	... 5 more
E/DropBoxManagerService(  734): Can't write: system_app_crash
E/DropBoxManagerService(  734): java.io.FileNotFoundException: /data/system/dropbox/drop84.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  734): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  734): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  734): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  734): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  734): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  734): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  734): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  734): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  734): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  734): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  734): 	... 5 more
D/OpenGLRenderer(  734): Render dirty regions requested: true
D/Atlas   (  734): Validating map...
,W/OpenGLRenderer( 1263): Incorrectly called buildLayer on View: adg, destroying layer...
W/OpenGLRenderer( 1263): Incorrectly called buildLayer on View: adg, destroying layer...
I/GMPM-SVC( 1569): App measurement is starting up, version: 8489
I/GMPM-SVC( 1569): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/BaseAppContext( 1569): Using Auth Proxy for data requests.
,E/GMPM-SVC( 1569): Scheduler not set. Not logging error/warn.
,W/BaseAppContext( 1569): Using Auth Proxy for data requests.
,I/Icing   ( 1569): doRemovePackageData com.example.hello
,E/qdhwcomposer(  170): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  170): hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
E/qdoverlay(  170): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  170): MdpData failed to play
E/qdoverlay(  170): == Dump MdpData start ==
E/qdoverlay(  170): == Dump OvFD fd=30 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  170): mOvData msmfb_overlay_data id=64
E/qdoverlay(  170): data msmfb_data offset=0 memid=41 id=0 flags=0x0 priv=0
E/qdoverlay(  170): == Dump MdpData end ==
E/qdhwcomposer(  170): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  170): hwc_set_primary: MDPComp draw failed
E/qdhwcomposer(  170): display_commit: MSMFB_DISPLAY_COMMIT for primary failed
,E/qdhwcomposer(  170): hwc_set_primary: display commit fail!
,E/qdoverlay(  170): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  170): MdpCtrl failed to setOverlay, restoring last known good ov info
,E/qdoverlay(  170): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  170): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  170): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  170): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  170): == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  170): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  170): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  170): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  170): Ctrl commit failed set overlay
E/qdhwcomposer(  170): configureLowRes: commit failed for low res panel
E/qdoverlay(  170): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  170): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  170): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  170): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  170): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  170): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdoverlay(  170): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  170): src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
E/qdoverlay(  170): src_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  170): dst_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  170): Ctrl commit failed set overlay
E/qdhwcomposer(  170): configure: commit fails
E/qdoverlay(  170): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  170): MdpCtrl close error in unset
,I/Adreno-EGL(  734): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  734): Initialized EGL, version 1.4
,D/OpenGLRenderer(  734): Enabling debug mode 0

```
